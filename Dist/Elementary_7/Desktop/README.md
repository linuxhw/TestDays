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

Total: 83

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte  | 970A-DS3P                   | [2ce7b78a76](https://linux-hardware.org/?probe=2ce7b78a76) | Sep 06, 2023 |
| Dell      | 0J3C2F A00                  | [9374424bbd](https://linux-hardware.org/?probe=9374424bbd) | Aug 30, 2023 |
| MSI       | B450 TOMAHAWK MAX II        | [2a2adfdc2e](https://linux-hardware.org/?probe=2a2adfdc2e) | Aug 30, 2023 |
| ASRock    | X370 Pro4                   | [190a0f1eee](https://linux-hardware.org/?probe=190a0f1eee) | Aug 23, 2023 |
| HP        | 18E7                        | [0bd07157fb](https://linux-hardware.org/?probe=0bd07157fb) | Aug 20, 2023 |
| ASUSTek   | P8Z68-V PRO GEN3            | [d05585906d](https://linux-hardware.org/?probe=d05585906d) | Aug 18, 2023 |
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
| 5.15.0-58-generic   | 15       | 24.59%  |
| 5.19.0-32-generic   | 9        | 14.75%  |
| 5.19.0-35-generic   | 6        | 9.84%   |
| 5.19.0-38-generic   | 5        | 8.2%    |
| 6.2.0-26-generic    | 4        | 6.56%   |
| 5.19.0-46-generic   | 4        | 6.56%   |
| 5.19.0-41-generic   | 4        | 6.56%   |
| 5.15.0-60-generic   | 4        | 6.56%   |
| 5.19.0-43-generic   | 3        | 4.92%   |
| 5.19.0-42-generic   | 3        | 4.92%   |
| 5.19.0-40-generic   | 2        | 3.28%   |
| 6.4.5-x64v3-xanmod1 | 1        | 1.64%   |
| 5.15.0-56-generic   | 1        | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19.0  | 34       | 57.63%  |
| 5.15.0  | 20       | 33.9%   |
| 6.2.0   | 4        | 6.78%   |
| 6.4.5   | 1        | 1.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19    | 34       | 57.63%  |
| 5.15    | 20       | 33.9%   |
| 6.2     | 4        | 6.78%   |
| 6.4     | 1        | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 58       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 58       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 58       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 86.21%  |
| LightDM | 8        | 13.79%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 21       | 35.59%  |
| de_DE | 10       | 16.95%  |
| es_ES | 5        | 8.47%   |
| ru_RU | 4        | 6.78%   |
| pt_BR | 3        | 5.08%   |
| it_IT | 3        | 5.08%   |
| pl_PL | 2        | 3.39%   |
| en_CA | 2        | 3.39%   |
| tr_TR | 1        | 1.69%   |
| sv_SE | 1        | 1.69%   |
| pt_PT | 1        | 1.69%   |
| nl_NL | 1        | 1.69%   |
| ja_JP | 1        | 1.69%   |
| fr_FR | 1        | 1.69%   |
| fi_FI | 1        | 1.69%   |
| en_AU | 1        | 1.69%   |
| cs_CZ | 1        | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 55       | 94.83%  |
| EFI  | 3        | 5.17%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 53       | 91.38%  |
| Tmpfs | 2        | 3.45%   |
| Btrfs | 2        | 3.45%   |
| Xfs   | 1        | 1.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 86.21%  |
| GPT     | 6        | 10.34%  |
| MBR     | 2        | 3.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 98.28%  |
| Yes       | 1        | 1.72%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 94.83%  |
| Yes       | 3        | 5.17%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 12       | 20.69%  |
| Gigabyte Technology | 9        | 15.52%  |
| MSI                 | 6        | 10.34%  |
| Hewlett-Packard     | 6        | 10.34%  |
| Dell                | 4        | 6.9%    |
| ASRock              | 3        | 5.17%   |
| Acer                | 3        | 5.17%   |
| Pegatron            | 2        | 3.45%   |
| Foxconn             | 2        | 3.45%   |
| Unknown             | 2        | 3.45%   |
| Wortmann AG         | 1        | 1.72%   |
| MACHINIST           | 1        | 1.72%   |
| Lenovo              | 1        | 1.72%   |
| Inventec            | 1        | 1.72%   |
| Intel               | 1        | 1.72%   |
| ECS                 | 1        | 1.72%   |
| AZW                 | 1        | 1.72%   |
| Apple               | 1        | 1.72%   |
| Alienware           | 1        | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Dell OptiPlex 790                    | 2        | 3.45%   |
| ASUS H110M-A/M.2                     | 2        | 3.45%   |
| Unknown                              | 2        | 3.45%   |
| Wortmann AG TERRA_PC                 | 1        | 1.72%   |
| Pegatron Pro 3010 Microtower PC      | 1        | 1.72%   |
| Pegatron IPMIP-GS                    | 1        | 1.72%   |
| MSI MS-7C52                          | 1        | 1.72%   |
| MSI MS-7C31                          | 1        | 1.72%   |
| MSI MS-7C02                          | 1        | 1.72%   |
| MSI MS-7B84                          | 1        | 1.72%   |
| MSI MS-7B17                          | 1        | 1.72%   |
| MSI MS-7816                          | 1        | 1.72%   |
| MACHINIST E5-MR9A PRO V1.1           | 1        | 1.72%   |
| Lenovo ThinkCentre M910s 10MLS05C00  | 1        | 1.72%   |
| Inventec Z CLASS                     | 1        | 1.72%   |
| Intel Jasper Lake Client Platform    | 1        | 1.72%   |
| HP ProDesk 600 G2 SFF                | 1        | 1.72%   |
| HP ProDesk 600 G1 SFF                | 1        | 1.72%   |
| HP EliteDesk 800 G2 DM 35W           | 1        | 1.72%   |
| HP EliteDesk 705 G2 MT               | 1        | 1.72%   |
| HP Compaq dc7900 Ultra-Slim Desktop  | 1        | 1.72%   |
| HP 1998                              | 1        | 1.72%   |
| Gigabyte Z77X-UD5H                   | 1        | 1.72%   |
| Gigabyte Z270-Gaming K3              | 1        | 1.72%   |
| Gigabyte H81M-S2V                    | 1        | 1.72%   |
| Gigabyte H410M H V3                  | 1        | 1.72%   |
| Gigabyte GA-E6010N                   | 1        | 1.72%   |
| Gigabyte F2A88XM-DS2                 | 1        | 1.72%   |
| Gigabyte B560M H                     | 1        | 1.72%   |
| Gigabyte B550 AORUS ELITE            | 1        | 1.72%   |
| Gigabyte 970A-DS3P                   | 1        | 1.72%   |
| Foxconn A76GMV                       | 1        | 1.72%   |
| Foxconn 400-034                      | 1        | 1.72%   |
| ECS G41T-M                           | 1        | 1.72%   |
| Dell OptiPlex 3070                   | 1        | 1.72%   |
| Dell Inspiron 5675                   | 1        | 1.72%   |
| AZW U59                              | 1        | 1.72%   |
| ASUS Z170 PRO GAMING                 | 1        | 1.72%   |
| ASUS TUF X470-PLUS GAMING            | 1        | 1.72%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4 | 1        | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 3        | 5.17%   |
| HP ProDesk           | 2        | 3.45%   |
| HP EliteDesk         | 2        | 3.45%   |
| ASUS ROG             | 2        | 3.45%   |
| ASUS PRIME           | 2        | 3.45%   |
| ASUS H110M-A         | 2        | 3.45%   |
| Acer Aspire          | 2        | 3.45%   |
| Unknown              | 2        | 3.45%   |
| Wortmann AG TERRA    | 1        | 1.72%   |
| Pegatron Pro         | 1        | 1.72%   |
| Pegatron IPMIP-GS    | 1        | 1.72%   |
| MSI MS-7C52          | 1        | 1.72%   |
| MSI MS-7C31          | 1        | 1.72%   |
| MSI MS-7C02          | 1        | 1.72%   |
| MSI MS-7B84          | 1        | 1.72%   |
| MSI MS-7B17          | 1        | 1.72%   |
| MSI MS-7816          | 1        | 1.72%   |
| MACHINIST E5-MR9A    | 1        | 1.72%   |
| Lenovo ThinkCentre   | 1        | 1.72%   |
| Inventec Z           | 1        | 1.72%   |
| Intel Jasper         | 1        | 1.72%   |
| HP Compaq            | 1        | 1.72%   |
| HP 1998              | 1        | 1.72%   |
| Gigabyte Z77X-UD5H   | 1        | 1.72%   |
| Gigabyte Z270-Gaming | 1        | 1.72%   |
| Gigabyte H81M-S2V    | 1        | 1.72%   |
| Gigabyte H410M       | 1        | 1.72%   |
| Gigabyte GA-E6010N   | 1        | 1.72%   |
| Gigabyte F2A88XM-DS2 | 1        | 1.72%   |
| Gigabyte B560M       | 1        | 1.72%   |
| Gigabyte B550        | 1        | 1.72%   |
| Gigabyte 970A-DS3P   | 1        | 1.72%   |
| Foxconn A76GMV       | 1        | 1.72%   |
| Foxconn 400-034      | 1        | 1.72%   |
| ECS G41T-M           | 1        | 1.72%   |
| Dell Inspiron        | 1        | 1.72%   |
| AZW U59              | 1        | 1.72%   |
| ASUS Z170            | 1        | 1.72%   |
| ASUS TUF             | 1        | 1.72%   |
| ASUS P8H61-MX        | 1        | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 8        | 13.79%  |
| 2018 | 7        | 12.07%  |
| 2012 | 6        | 10.34%  |
| 2021 | 5        | 8.62%   |
| 2009 | 5        | 8.62%   |
| 2019 | 4        | 6.9%    |
| 2016 | 4        | 6.9%    |
| 2015 | 4        | 6.9%    |
| 2020 | 3        | 5.17%   |
| 2017 | 3        | 5.17%   |
| 2022 | 2        | 3.45%   |
| 2010 | 2        | 3.45%   |
| 2008 | 2        | 3.45%   |
| 2023 | 1        | 1.72%   |
| 2014 | 1        | 1.72%   |
| 2011 | 1        | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 58       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 58       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 16       | 27.12%  |
| 16.01-24.0  | 15       | 25.42%  |
| 32.01-64.0  | 10       | 16.95%  |
| 8.01-16.0   | 9        | 15.25%  |
| 3.01-4.0    | 6        | 10.17%  |
| 24.01-32.0  | 1        | 1.69%   |
| 64.01-256.0 | 1        | 1.69%   |
| 1.01-2.0    | 1        | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 28       | 46.67%  |
| 1.01-2.0  | 13       | 21.67%  |
| 3.01-4.0  | 10       | 16.67%  |
| 4.01-8.0  | 8        | 13.33%  |
| 8.01-16.0 | 1        | 1.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 22       | 37.93%  |
| 1      | 22       | 37.93%  |
| 3      | 8        | 13.79%  |
| 5      | 3        | 5.17%   |
| 4      | 3        | 5.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 64.41%  |
| Yes       | 21       | 35.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 58       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 55.17%  |
| Yes       | 26       | 44.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 58.62%  |
| Yes       | 24       | 41.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 12       | 20.69%  |
| USA         | 10       | 17.24%  |
| Russia      | 4        | 6.9%    |
| Italy       | 4        | 6.9%    |
| Brazil      | 4        | 6.9%    |
| Spain       | 3        | 5.17%   |
| Netherlands | 3        | 5.17%   |
| India       | 2        | 3.45%   |
| Canada      | 2        | 3.45%   |
| Venezuela   | 1        | 1.72%   |
| Ukraine     | 1        | 1.72%   |
| Turkey      | 1        | 1.72%   |
| Sweden      | 1        | 1.72%   |
| Portugal    | 1        | 1.72%   |
| Mexico      | 1        | 1.72%   |
| Japan       | 1        | 1.72%   |
| Greece      | 1        | 1.72%   |
| France      | 1        | 1.72%   |
| Finland     | 1        | 1.72%   |
| Czechia     | 1        | 1.72%   |
| Chile       | 1        | 1.72%   |
| Australia   | 1        | 1.72%   |
| Argentina   | 1        | 1.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Munich            | 2        | 3.33%   |
| Moscow            | 2        | 3.33%   |
| Amsterdam         | 2        | 3.33%   |
| Yorktown          | 1        | 1.67%   |
| West Jordan       | 1        | 1.67%   |
| Viareggio         | 1        | 1.67%   |
| Valencia          | 1        | 1.67%   |
| Tucson            | 1        | 1.67%   |
| Stuttgart         | 1        | 1.67%   |
| Stockholm         | 1        | 1.67%   |
| Steti             | 1        | 1.67%   |
| St Petersburg     | 1        | 1.67%   |
| Spokane           | 1        | 1.67%   |
| Sorel-Tracy       | 1        | 1.67%   |
| Sao Paulo         | 1        | 1.67%   |
| Santiago          | 1        | 1.67%   |
| Sandim            | 1        | 1.67%   |
| San Marcos        | 1        | 1.67%   |
| Roetgen           | 1        | 1.67%   |
| Plauen            | 1        | 1.67%   |
| Piea              | 1        | 1.67%   |
| Padova            | 1        | 1.67%   |
| Ojicho            | 1        | 1.67%   |
| Nossen            | 1        | 1.67%   |
| New York          | 1        | 1.67%   |
| Mumbai            | 1        | 1.67%   |
| Morehead City     | 1        | 1.67%   |
| Monsummano Terme  | 1        | 1.67%   |
| Milano            | 1        | 1.67%   |
| Melbourne         | 1        | 1.67%   |
| Mariupol          | 1        | 1.67%   |
| Madrid            | 1        | 1.67%   |
| Los Montesinos    | 1        | 1.67%   |
| Lorena            | 1        | 1.67%   |
| Las Vegas         | 1        | 1.67%   |
| Lanus             | 1        | 1.67%   |
| Lagerdorf         | 1        | 1.67%   |
| Laberweinting     | 1        | 1.67%   |
| Juazeiro do Norte | 1        | 1.67%   |
| Irvine            | 1        | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 21       | 25     | 19.81%  |
| Seagate                     | 13       | 19     | 12.26%  |
| Samsung Electronics         | 11       | 16     | 10.38%  |
| Toshiba                     | 7        | 9      | 6.6%    |
| Sandisk                     | 6        | 7      | 5.66%   |
| Kingston                    | 6        | 6      | 5.66%   |
| Crucial                     | 5        | 6      | 4.72%   |
| Hitachi                     | 4        | 5      | 3.77%   |
| A-DATA Technology           | 3        | 3      | 2.83%   |
| Team                        | 2        | 3      | 1.89%   |
| PNY                         | 2        | 2      | 1.89%   |
| Netac                       | 2        | 3      | 1.89%   |
| Micron/Crucial Technology   | 2        | 2      | 1.89%   |
| China                       | 2        | 2      | 1.89%   |
| Unknown                     | 2        | 2      | 1.89%   |
| Yeestor                     | 1        | 1      | 0.94%   |
| XrayDisk                    | 1        | 1      | 0.94%   |
| Unknown                     | 1        | 1      | 0.94%   |
| Silicon Motion              | 1        | 1      | 0.94%   |
| SD                          | 1        | 1      | 0.94%   |
| Realtek Semiconductor       | 1        | 2      | 0.94%   |
| OCZ-VERTEX2                 | 1        | 1      | 0.94%   |
| NGFF                        | 1        | 1      | 0.94%   |
| Micron Technology           | 1        | 1      | 0.94%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.94%   |
| LuminouTek                  | 1        | 1      | 0.94%   |
| LITEONIT                    | 1        | 1      | 0.94%   |
| KingDian                    | 1        | 2      | 0.94%   |
| Intenso                     | 1        | 2      | 0.94%   |
| HS-SSD-E100                 | 1        | 2      | 0.94%   |
| Hewlett-Packard             | 1        | 1      | 0.94%   |
| Corsair                     | 1        | 1      | 0.94%   |
| Apacer                      | 1        | 1      | 0.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 4        | 3.45%   |
| WDC WD10EZEX-60WN4A0 1TB                              | 3        | 2.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 3        | 2.59%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 2        | 1.72%   |
| Toshiba MQ01ABD100 1TB                                | 2        | 1.72%   |
| Toshiba DT01ACA200 2TB                                | 2        | 1.72%   |
| Seagate ST4000DM004-2CV104 4TB                        | 2        | 1.72%   |
| Samsung SSD 850 EVO 250GB                             | 2        | 1.72%   |
| Crucial CT500MX500SSD1 500GB                          | 2        | 1.72%   |
| Crucial CT240BX500SSD1 240GB                          | 2        | 1.72%   |
| Unknown                                               | 2        | 1.72%   |
| Yeestor 512GB                                         | 1        | 0.86%   |
| XrayDisk 512GB SSD                                    | 1        | 0.86%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 1        | 0.86%   |
| WDC WDS480G2G0C-00AJM0 480GB                          | 1        | 0.86%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 1        | 0.86%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 1        | 0.86%   |
| WDC WD5000AAKS-00V6A0 500GB                           | 1        | 0.86%   |
| WDC WD5000AAKS-00UU3A0 500GB                          | 1        | 0.86%   |
| WDC WD40EZRZ-00GXCB0 4TB                              | 1        | 0.86%   |
| WDC WD2500JB-55GVA0 250GB                             | 1        | 0.86%   |
| WDC WD20EZRX-22D8PB0 2TB                              | 1        | 0.86%   |
| WDC WD20EZRX-00D8PB0 2TB                              | 1        | 0.86%   |
| WDC WD10PURZ-85U8XY0 1TB                              | 1        | 0.86%   |
| WDC WD10EZEX-60ZF5A0 1TB                              | 1        | 0.86%   |
| WDC WD10EZEX-21WN4A0 1TB                              | 1        | 0.86%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 1        | 0.86%   |
| WDC WD10EZEX-00BBHA0 1TB                              | 1        | 0.86%   |
| WDC WD1002FBYS-18W8B0 1TB                             | 1        | 0.86%   |
| Unknown SD/MMC/MS PRO 1GB                             | 1        | 0.86%   |
| Toshiba XG4 NVMe SSD Controller 256GB                 | 1        | 0.86%   |
| Toshiba HDWD110 1TB                                   | 1        | 0.86%   |
| Toshiba DT01ACA100 1TB                                | 1        | 0.86%   |
| Toshiba DT01ACA050 500GB                              | 1        | 0.86%   |
| Team T253X2001T 1TB SSD                               | 1        | 0.86%   |
| Team T253X1480G 480GB SSD                             | 1        | 0.86%   |
| Team L3 SSD 240GB                                     | 1        | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 1        | 0.86%   |
| Seagate ST9500325AS 500GB                             | 1        | 0.86%   |
| Seagate ST750LM022 HN-M750MBB 752GB                   | 1        | 0.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 20     | 39.53%  |
| Seagate             | 12       | 16     | 27.91%  |
| Toshiba             | 7        | 8      | 16.28%  |
| Hitachi             | 4        | 5      | 9.3%    |
| Samsung Electronics | 2        | 2      | 4.65%   |
| Unknown             | 1        | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 8      | 12.5%   |
| Kingston            | 6        | 6      | 12.5%   |
| Crucial             | 5        | 6      | 10.42%  |
| WDC                 | 3        | 4      | 6.25%   |
| SanDisk             | 3        | 4      | 6.25%   |
| A-DATA Technology   | 3        | 3      | 6.25%   |
| Team                | 2        | 3      | 4.17%   |
| Seagate             | 2        | 2      | 4.17%   |
| PNY                 | 2        | 2      | 4.17%   |
| China               | 2        | 2      | 4.17%   |
| XrayDisk            | 1        | 1      | 2.08%   |
| SD                  | 1        | 1      | 2.08%   |
| OCZ-VERTEX2         | 1        | 1      | 2.08%   |
| NGFF                | 1        | 1      | 2.08%   |
| Netac               | 1        | 1      | 2.08%   |
| Micron Technology   | 1        | 1      | 2.08%   |
| LITEONIT            | 1        | 1      | 2.08%   |
| KingDian            | 1        | 2      | 2.08%   |
| Intenso             | 1        | 2      | 2.08%   |
| HS-SSD-E100         | 1        | 1      | 2.08%   |
| Hewlett-Packard     | 1        | 1      | 2.08%   |
| Corsair             | 1        | 1      | 2.08%   |
| Apacer              | 1        | 1      | 2.08%   |
| Unknown             | 1        | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 44       | 56     | 44.9%   |
| HDD     | 34       | 52     | 34.69%  |
| NVMe    | 14       | 17     | 14.29%  |
| Unknown | 6        | 7      | 6.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 57       | 111    | 76%     |
| NVMe | 14       | 17     | 18.67%  |
| SAS  | 4        | 4      | 5.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 42       | 61     | 54.55%  |
| 0.51-1.0   | 27       | 38     | 35.06%  |
| 1.01-2.0   | 5        | 6      | 6.49%   |
| 3.01-4.0   | 3        | 3      | 3.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 24       | 41.38%  |
| 501-1000   | 14       | 24.14%  |
| 251-500    | 13       | 22.41%  |
| 2001-3000  | 2        | 3.45%   |
| 1001-2000  | 2        | 3.45%   |
| 51-100     | 2        | 3.45%   |
| 21-50      | 1        | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 22       | 37.29%  |
| 21-50     | 16       | 27.12%  |
| 51-100    | 9        | 15.25%  |
| 101-250   | 8        | 13.56%  |
| 251-500   | 3        | 5.08%   |
| 1001-2000 | 1        | 1.69%   |

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
| Detected | 55       | 123    | 88.71%  |
| Works    | 6        | 8      | 9.68%   |
| Malfunc  | 1        | 1      | 1.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 39       | 50.65%  |
| AMD                          | 19       | 24.68%  |
| Samsung Electronics          | 5        | 6.49%   |
| SanDisk                      | 3        | 3.9%    |
| ASMedia Technology           | 3        | 3.9%    |
| Micron/Crucial Technology    | 2        | 2.6%    |
| Marvell Technology Group     | 2        | 2.6%    |
| Toshiba America Info Systems | 1        | 1.3%    |
| Silicon Motion               | 1        | 1.3%    |
| Realtek Semiconductor        | 1        | 1.3%    |
| MAXIO Technology (Hangzhou)  | 1        | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 14.74%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 6.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 4.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 4.21%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 4.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 3.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 3.16%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 3.16%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 3.16%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 2.11%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 2.11%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 2.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.11%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 2.11%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 2.11%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 2.11%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 1.05%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 1.05%   |
| SanDisk WD Green SN350 NVMe SSD 240GB (DRAM-less)                                       | 1        | 1.05%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.05%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                                   | 1        | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.05%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.05%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 1        | 1.05%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 1.05%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                               | 1        | 1.05%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1        | 1.05%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 1.05%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 1.05%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.05%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.05%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 55       | 72.37%  |
| NVMe | 13       | 17.11%  |
| IDE  | 7        | 9.21%   |
| RAID | 1        | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 39       | 67.24%  |
| AMD    | 19       | 32.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 3.45%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 3.45%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 3.45%   |
| Intel Celeron N5105 @ 2.00GHz               | 2        | 3.45%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 1.72%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 1.72%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1        | 1.72%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.72%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 1.72%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.72%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 1        | 1.72%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i5-9400T CPU @ 1.80GHz           | 1        | 1.72%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1        | 1.72%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 1.72%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.72%   |
| Intel Core i5-2500S CPU @ 2.70GHz           | 1        | 1.72%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.72%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1        | 1.72%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.72%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.72%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 1.72%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 1.72%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.72%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.72%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.72%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.72%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 1.72%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 1        | 1.72%   |
| Intel 12th Gen Core i7-12700K               | 1        | 1.72%   |
| Intel 12th Gen Core i7-12700F               | 1        | 1.72%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 1        | 1.72%   |
| AMD Sempron 145 Processor                   | 1        | 1.72%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 1.72%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 1        | 1.72%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 1.72%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 1        | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 10       | 17.24%  |
| Intel Core i7           | 8        | 13.79%  |
| Intel Core i3           | 6        | 10.34%  |
| Other                   | 4        | 6.9%    |
| Intel Celeron           | 4        | 6.9%    |
| AMD Ryzen 5             | 4        | 6.9%    |
| Intel Xeon              | 2        | 3.45%   |
| Intel Core i9           | 2        | 3.45%   |
| Intel Core 2 Duo        | 2        | 3.45%   |
| AMD Ryzen 9             | 2        | 3.45%   |
| AMD Ryzen 7             | 2        | 3.45%   |
| AMD A8                  | 2        | 3.45%   |
| Intel Pentium Dual-Core | 1        | 1.72%   |
| Intel Pentium           | 1        | 1.72%   |
| AMD Sempron             | 1        | 1.72%   |
| AMD Ryzen 5 PRO         | 1        | 1.72%   |
| AMD Ryzen 3             | 1        | 1.72%   |
| AMD Phenom II X6        | 1        | 1.72%   |
| AMD G                   | 1        | 1.72%   |
| AMD FX                  | 1        | 1.72%   |
| AMD E1                  | 1        | 1.72%   |
| AMD Athlon              | 1        | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 23       | 38.98%  |
| 2      | 15       | 25.42%  |
| 6      | 8        | 13.56%  |
| 8      | 5        | 8.47%   |
| 12     | 4        | 6.78%   |
| 1      | 3        | 5.08%   |
| 5      | 1        | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 58       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 36       | 62.07%  |
| 1      | 22       | 37.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 58       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 87.93%  |
| 0x306a9    | 2        | 3.45%   |
| 0x906e9    | 1        | 1.72%   |
| 0x906c0    | 1        | 1.72%   |
| 0x08108109 | 1        | 1.72%   |
| 0x07030106 | 1        | 1.72%   |
| 0x010000c8 | 1        | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 8        | 13.79%  |
| IvyBridge     | 6        | 10.34%  |
| Skylake       | 5        | 8.62%   |
| Haswell       | 5        | 8.62%   |
| Unknown       | 4        | 6.9%    |
| Zen 3         | 3        | 5.17%   |
| Zen 2         | 3        | 5.17%   |
| Zen           | 3        | 5.17%   |
| Penryn        | 3        | 5.17%   |
| Zen+          | 2        | 3.45%   |
| Steamroller   | 2        | 3.45%   |
| SandyBridge   | 2        | 3.45%   |
| Nehalem       | 2        | 3.45%   |
| K10           | 2        | 3.45%   |
| Westmere      | 1        | 1.72%   |
| Tremont       | 1        | 1.72%   |
| Puma          | 1        | 1.72%   |
| Piledriver    | 1        | 1.72%   |
| Goldmont plus | 1        | 1.72%   |
| Excavator     | 1        | 1.72%   |
| CometLake     | 1        | 1.72%   |
| Bobcat        | 1        | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 22       | 34.92%  |
| AMD    | 22       | 34.92%  |
| Nvidia | 19       | 30.16%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 630                                                       | 3        | 4.62%   |
| Intel HD Graphics 530                                                       | 3        | 4.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 4.62%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 3.08%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 3.08%   |
| Nvidia GK107 [GeForce GT 640]                                               | 2        | 3.08%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 3.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 3.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 3.08%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 3.08%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 3.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 3.08%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.54%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.54%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.54%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.54%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.54%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.54%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.54%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.54%   |
| Nvidia GA103 [GeForce RTX 3060 Ti]                                          | 1        | 1.54%   |
| Nvidia G96C [GeForce GT 120]                                                | 1        | 1.54%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.54%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 1.54%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.54%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 1.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.54%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 1.54%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.54%   |
| AMD RV535 [Radeon X1650 PRO] (Secondary)                                    | 1        | 1.54%   |
| AMD RV535 [Radeon X1650 PRO]                                                | 1        | 1.54%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 1.54%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 20       | 34.48%  |
| 1 x Intel       | 18       | 31.03%  |
| 1 x Nvidia      | 17       | 29.31%  |
| 2 x AMD         | 1        | 1.72%   |
| Intel + 2 x AMD | 1        | 1.72%   |
| Intel + Nvidia  | 1        | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 53       | 91.38%  |
| Proprietary | 5        | 8.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 52       | 89.66%  |
| 7.01-8.0   | 2        | 3.45%   |
| 0.51-1.0   | 2        | 3.45%   |
| 1.01-2.0   | 1        | 1.72%   |
| 0.01-0.5   | 1        | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 13.33%  |
| Goldstar             | 8        | 13.33%  |
| Dell                 | 4        | 6.67%   |
| Acer                 | 4        | 6.67%   |
| ViewSonic            | 3        | 5%      |
| Hewlett-Packard      | 3        | 5%      |
| Sceptre Tech         | 2        | 3.33%   |
| Philips              | 2        | 3.33%   |
| NEC Computers        | 2        | 3.33%   |
| BenQ                 | 2        | 3.33%   |
| ASUSTek Computer     | 2        | 3.33%   |
| AOC                  | 2        | 3.33%   |
| ___                  | 1        | 1.67%   |
| Vizio                | 1        | 1.67%   |
| Unknown              | 1        | 1.67%   |
| Sony                 | 1        | 1.67%   |
| Sharp                | 1        | 1.67%   |
| RCA                  | 1        | 1.67%   |
| Positivo             | 1        | 1.67%   |
| NSL                  | 1        | 1.67%   |
| MYS                  | 1        | 1.67%   |
| MSI                  | 1        | 1.67%   |
| Lenovo               | 1        | 1.67%   |
| Kogan                | 1        | 1.67%   |
| Hitachi              | 1        | 1.67%   |
| HannStar             | 1        | 1.67%   |
| Fujitsu Siemens      | 1        | 1.67%   |
| Eizo                 | 1        | 1.67%   |
| CVT                  | 1        | 1.67%   |
| Ancor Communications | 1        | 1.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch        | 2        | 3.13%   |
| ___ LCDTV16 ___3393 1920x1080                                        | 1        | 1.56%   |
| Vizio E420VO VIZ0070 1920x1080 930x523mm 42.0-inch                   | 1        | 1.56%   |
| ViewSonic VP201b VSC6911 1600x1200 408x306mm 20.1-inch               | 1        | 1.56%   |
| Unknown LCDTV16 3393 1920x1080 1600x900mm 72.3-inch                  | 1        | 1.56%   |
| Sony TV SNY7A02 1360x768 576x324mm 26.0-inch                         | 1        | 1.56%   |
| Sharp HDMI SHP1048 1920x1080 820x460mm 37.0-inch                     | 1        | 1.56%   |
| Sceptre Tech Sceptre Q27 SPT0AD2 2560x1440 597x336mm 27.0-inch       | 1        | 1.56%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch               | 1        | 1.56%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch | 1        | 1.56%   |
| Samsung Electronics SMB2030HD SAM0709 1600x900 443x249mm 20.0-inch   | 1        | 1.56%   |
| Samsung Electronics S27A950D SAM079F 1920x1080 598x336mm 27.0-inch   | 1        | 1.56%   |
| Samsung Electronics S24E450 SAM0C7F 1920x1080 521x293mm 23.5-inch    | 1        | 1.56%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 1        | 1.56%   |
| Samsung Electronics LS27AG55x SAM71E0 2560x1440 597x336mm 27.0-inch  | 1        | 1.56%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch   | 1        | 1.56%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch    | 1        | 1.56%   |
| RCA RTR3261-B-CA RCA0B01 1920x1080 698x392mm 31.5-inch               | 1        | 1.56%   |
| Positivo MC35120QWQHD NON3503 3440x1440 819x346mm 35.0-inch          | 1        | 1.56%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 1        | 1.56%   |
| Philips 220TS PHLC06B 1920x1080 477x268mm 21.5-inch                  | 1        | 1.56%   |
| NSL RGB-27QHD NSL2711 2560x1440 597x336mm 27.0-inch                  | 1        | 1.56%   |
| NEC Computers EA234WMi NEC691E 1920x1080 509x286mm 23.0-inch         | 1        | 1.56%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch          | 1        | 1.56%   |
| MYS LCD Monitor MYS1700 1280x1024 360x240mm 17.0-inch                | 1        | 1.56%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                       | 1        | 1.56%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                | 1        | 1.56%   |
| Kogan KAMN27QF7TA KGN0270 2560x1440 698x393mm 31.5-inch              | 1        | 1.56%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch              | 1        | 1.56%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch          | 1        | 1.56%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch         | 1        | 1.56%   |
| Hewlett-Packard E231 HWP3063 1920x1080 509x286mm 23.0-inch           | 1        | 1.56%   |
| HannStar HSG1074 HSP0019 1920x1080 543x305mm 24.5-inch               | 1        | 1.56%   |
| Goldstar W1953 GSM4BA7 1360x768 406x229mm 18.4-inch                  | 1        | 1.56%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 1        | 1.56%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                  | 1        | 1.56%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch             | 1        | 1.56%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch             | 1        | 1.56%   |
| Goldstar HDR WFHD GSM5BA0 2560x1080 798x334mm 34.1-inch              | 1        | 1.56%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch               | 1        | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 32       | 52.46%  |
| 2560x1440 (QHD)    | 6        | 9.84%   |
| 1920x1200 (WUXGA)  | 3        | 4.92%   |
| 1366x768 (WXGA)    | 3        | 4.92%   |
| 3840x2160 (4K)     | 2        | 3.28%   |
| 3440x1440          | 2        | 3.28%   |
| 2560x1080          | 2        | 3.28%   |
| 1680x1050 (WSXGA+) | 2        | 3.28%   |
| 1360x768           | 2        | 3.28%   |
| 1280x1024 (SXGA)   | 2        | 3.28%   |
| 3840x1080          | 1        | 1.64%   |
| 2560x1600          | 1        | 1.64%   |
| 1600x900 (HD+)     | 1        | 1.64%   |
| 1600x1200          | 1        | 1.64%   |
| 1440x900 (WXGA+)   | 1        | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 11       | 17.46%  |
| 27      | 9        | 14.29%  |
| 21      | 8        | 12.7%   |
| 23      | 5        | 7.94%   |
| 18      | 4        | 6.35%   |
| 34      | 3        | 4.76%   |
| 31      | 3        | 4.76%   |
| 22      | 2        | 3.17%   |
| 20      | 2        | 3.17%   |
| 19      | 2        | 3.17%   |
| Unknown | 2        | 3.17%   |
| 84      | 1        | 1.59%   |
| 72      | 1        | 1.59%   |
| 60      | 1        | 1.59%   |
| 49      | 1        | 1.59%   |
| 42      | 1        | 1.59%   |
| 36      | 1        | 1.59%   |
| 35      | 1        | 1.59%   |
| 32      | 1        | 1.59%   |
| 29      | 1        | 1.59%   |
| 26      | 1        | 1.59%   |
| 17      | 1        | 1.59%   |
| 14      | 1        | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 24       | 39.34%  |
| 401-500     | 17       | 27.87%  |
| 701-800     | 5        | 8.2%    |
| 601-700     | 4        | 6.56%   |
| 351-400     | 2        | 3.28%   |
| 1501-2000   | 2        | 3.28%   |
| 1001-1500   | 2        | 3.28%   |
| Unknown     | 2        | 3.28%   |
| 801-900     | 1        | 1.64%   |
| 201-300     | 1        | 1.64%   |
| 901-1000    | 1        | 1.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 43       | 71.67%  |
| 16/10   | 7        | 11.67%  |
| 21/9    | 4        | 6.67%   |
| 4/3     | 2        | 3.33%   |
| 6/5     | 1        | 1.67%   |
| 32/9    | 1        | 1.67%   |
| 3/2     | 1        | 1.67%   |
| Unknown | 1        | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 19       | 30.65%  |
| 351-500        | 9        | 14.52%  |
| 301-350        | 9        | 14.52%  |
| 151-200        | 7        | 11.29%  |
| 251-300        | 4        | 6.45%   |
| 141-150        | 4        | 6.45%   |
| More than 1000 | 3        | 4.84%   |
| 501-1000       | 3        | 4.84%   |
| Unknown        | 2        | 3.23%   |
| 131-140        | 1        | 1.61%   |
| 101-110        | 1        | 1.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 37       | 64.91%  |
| 101-120 | 13       | 22.81%  |
| 1-50    | 3        | 5.26%   |
| 121-160 | 2        | 3.51%   |
| Unknown | 2        | 3.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 48       | 82.76%  |
| 2     | 10       | 17.24%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 31       | 36.9%   |
| Intel                    | 27       | 32.14%  |
| Qualcomm Atheros         | 8        | 9.52%   |
| TP-Link                  | 4        | 4.76%   |
| Broadcom                 | 3        | 3.57%   |
| Xiaomi                   | 2        | 2.38%   |
| Marvell Technology Group | 2        | 2.38%   |
| Samsung Electronics      | 1        | 1.19%   |
| Ralink                   | 1        | 1.19%   |
| Qualcomm                 | 1        | 1.19%   |
| MediaTek                 | 1        | 1.19%   |
| Linksys                  | 1        | 1.19%   |
| Huawei Technologies      | 1        | 1.19%   |
| ASUSTek Computer         | 1        | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28       | 29.47%  |
| Intel Wireless 3165                                               | 4        | 4.21%   |
| Intel Ethernet Controller I225-V                                  | 3        | 3.16%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 2.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 2.11%   |
| Intel I211 Gigabit Network Connection                             | 2        | 2.11%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.11%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 2.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.11%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 2.11%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 1.05%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 1.05%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 1.05%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 1.05%   |
| TP-Link Archer T4U ver.3                                          | 1        | 1.05%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.05%   |
| Realtek 802.11ac NIC                                              | 1        | 1.05%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 1.05%   |
| Qualcomm Redmi Note 8                                             | 1        | 1.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 1.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.05%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.05%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.05%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 1.05%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 1.05%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 1.05%   |
| Marvell Group Libertas 802.11b/g Wireless LAN Client Adapter      | 1        | 1.05%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless               | 1        | 1.05%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]     | 1        | 1.05%   |
| Intel Wireless-AC 9260                                            | 1        | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 10       | 34.48%  |
| Realtek Semiconductor    | 5        | 17.24%  |
| Qualcomm Atheros         | 4        | 13.79%  |
| TP-Link                  | 3        | 10.34%  |
| Marvell Technology Group | 2        | 6.9%    |
| Ralink                   | 1        | 3.45%   |
| MediaTek                 | 1        | 3.45%   |
| Linksys                  | 1        | 3.45%   |
| Broadcom                 | 1        | 3.45%   |
| ASUSTek Computer         | 1        | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                           | 4        | 13.33%  |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 6.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2        | 6.67%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 2        | 6.67%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1        | 3.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1        | 3.33%   |
| TP-Link Archer T4U ver.3                                      | 1        | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1        | 3.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1        | 3.33%   |
| Realtek 802.11ac NIC                                          | 1        | 3.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1        | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1        | 3.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1        | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1        | 3.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 1        | 3.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1        | 3.33%   |
| Marvell Group Libertas 802.11b/g Wireless LAN Client Adapter  | 1        | 3.33%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless           | 1        | 3.33%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235] | 1        | 3.33%   |
| Intel Wireless-AC 9260                                        | 1        | 3.33%   |
| Intel Wireless 8260                                           | 1        | 3.33%   |
| Intel Wi-Fi 6 AX200                                           | 1        | 3.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 1        | 3.33%   |
| ASUS 802.11ac WLAN Adapter                                    | 1        | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 29       | 44.62%  |
| Intel                 | 23       | 35.38%  |
| Qualcomm Atheros      | 5        | 7.69%   |
| Xiaomi                | 2        | 3.08%   |
| Broadcom              | 2        | 3.08%   |
| TP-Link               | 1        | 1.54%   |
| Samsung Electronics   | 1        | 1.54%   |
| Qualcomm              | 1        | 1.54%   |
| Huawei Technologies   | 1        | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28       | 43.08%  |
| Intel Ethernet Controller I225-V                                  | 3        | 4.62%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 4.62%   |
| Intel I211 Gigabit Network Connection                             | 2        | 3.08%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 3.08%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 3.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 3.08%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.54%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 1.54%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 1.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.54%   |
| Qualcomm Redmi Note 8                                             | 1        | 1.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.54%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 1.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.54%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 1.54%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.54%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.54%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.54%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.54%   |
| Huawei MLA-L11                                                    | 1        | 1.54%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                    | 1        | 1.54%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 1.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 59       | 69.41%  |
| WiFi     | 26       | 30.59%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 43       | 76.79%  |
| WiFi     | 13       | 23.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 56.9%   |
| 2     | 20       | 34.48%  |
| 3     | 4        | 6.9%    |
| 0     | 1        | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 36       | 62.07%  |
| Yes  | 22       | 37.93%  |

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
| Intel                    | 39       | 41.05%  |
| AMD                      | 24       | 25.26%  |
| Nvidia                   | 17       | 17.89%  |
| C-Media Electronics      | 6        | 6.32%   |
| Logitech                 | 3        | 3.16%   |
| Razer USA                | 1        | 1.05%   |
| Nordic Semiconductor ASA | 1        | 1.05%   |
| KTMicro                  | 1        | 1.05%   |
| Goldvish                 | 1        | 1.05%   |
| Creative Labs            | 1        | 1.05%   |
| ASUSTek Computer         | 1        | 1.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 5.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 4.46%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5        | 4.46%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 3.57%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 3.57%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4        | 3.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 2.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 2.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 2.68%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 2.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 2.68%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 2.68%   |
| AMD FCH Azalia Controller                                                  | 3        | 2.68%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 2.68%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 1.79%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.79%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 1.79%   |
| Intel Jasper Lake HD Audio                                                 | 2        | 1.79%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.79%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.79%   |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 1.79%   |
| Razer USA Razer Barracuda X                                                | 1        | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.89%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.89%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.89%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.89%   |
| Nvidia Audio device                                                        | 1        | 0.89%   |
| Nordic Semiconductor ASA SG Control Mic                                    | 1        | 0.89%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1        | 0.89%   |
| Logitech Logi Z407                                                         | 1        | 0.89%   |
| Logitech G432 Gaming Headset                                               | 1        | 0.89%   |
| KTMicro KT USB Audio                                                       | 1        | 0.89%   |

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
| Sunplus Innovation Technology | 1        | 25%     |
| Samsung Electronics           | 1        | 25%     |
| Generalplus Technology        | 1        | 25%     |
| Apple                         | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Sunplus FHD Camera Microphone           | 1        | 25%     |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 25%     |
| Generalplus WEB CAM                     | 1        | 25%     |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 1        | 25%     |

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
| OmniKey     | 1        | 50%     |
| Alcor Micro | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| OmniKey CardMan 3121 (HID Technologies) | 1        | 50%     |
| Alcor Micro AU9540 Smartcard Reader     | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 47       | 81.03%  |
| 1     | 9        | 15.52%  |
| 2     | 2        | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 6        | 46.15%  |
| Chipcard              | 2        | 15.38%  |
| Network               | 1        | 7.69%   |
| Net/ethernet          | 1        | 7.69%   |
| Multimedia controller | 1        | 7.69%   |
| Graphics card         | 1        | 7.69%   |
| Card reader           | 1        | 7.69%   |

