Alpine - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Alpine.

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

Total: 40

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B550 AORUS ELITE V2         | [bbf4464c41](https://linux-hardware.org/?probe=bbf4464c41) | Nov 27, 2022 |
| Fujitsu       | FujitsuTP7000 -1            | [89198d262f](https://linux-hardware.org/?probe=89198d262f) | Nov 17, 2022 |
| Lenovo        | 31900058 STD                | [d7cc344b2f](https://linux-hardware.org/?probe=d7cc344b2f) | Oct 31, 2022 |
| Lenovo        | 31900058 STD                | [9f7158b883](https://linux-hardware.org/?probe=9f7158b883) | Oct 16, 2022 |
| HP            | 1493                        | [60ebd1d8dd](https://linux-hardware.org/?probe=60ebd1d8dd) | Sep 29, 2022 |
| Gateway       | SX2185                      | [8372be8fe3](https://linux-hardware.org/?probe=8372be8fe3) | Sep 29, 2022 |
| ASRock        | H81M                        | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| Intel         | DH61BF AAG81311-101         | [5a3ed0cf62](https://linux-hardware.org/?probe=5a3ed0cf62) | Jul 30, 2022 |
| Intel         | DH61BF AAG81311-101         | [719bbf817c](https://linux-hardware.org/?probe=719bbf817c) | Jul 30, 2022 |
| Intel         | DQ67SW AAG12527-310         | [9a4907d88c](https://linux-hardware.org/?probe=9a4907d88c) | Jul 17, 2022 |
| Unknown       | Unknown                     | [d857b93614](https://linux-hardware.org/?probe=d857b93614) | Jul 13, 2022 |
| Lenovo        | 31900058 STD                | [2f6356a177](https://linux-hardware.org/?probe=2f6356a177) | Jun 17, 2022 |
| Lenovo        | 31900058 STD                | [582fd88dbe](https://linux-hardware.org/?probe=582fd88dbe) | Jun 14, 2022 |
| MSI           | Z170A GAMING PRO            | [73b3e29101](https://linux-hardware.org/?probe=73b3e29101) | Jun 14, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [e692b2a091](https://linux-hardware.org/?probe=e692b2a091) | May 26, 2022 |
| ASUSTek       | H97-PLUS                    | [cab2025064](https://linux-hardware.org/?probe=cab2025064) | May 24, 2022 |
| MSI           | J1900I                      | [86f37a71f5](https://linux-hardware.org/?probe=86f37a71f5) | May 15, 2022 |
| MSI           | J1900I                      | [5a48d83596](https://linux-hardware.org/?probe=5a48d83596) | May 15, 2022 |
| ASUSTek       | Z97-K                       | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Dell          | 02YRK5 A02                  | [58c2ed388b](https://linux-hardware.org/?probe=58c2ed388b) | Dec 02, 2021 |
| HP            | 21B4 A01                    | [98accc83e4](https://linux-hardware.org/?probe=98accc83e4) | Nov 11, 2021 |
| Dell          | 0T10XW A00                  | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| Shuttle       | FS81                        | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| Dell          | 0VRWRC A00                  | [37a6ad6e02](https://linux-hardware.org/?probe=37a6ad6e02) | Apr 09, 2021 |
| ASUSTek       | P8H67-V                     | [89edd8b343](https://linux-hardware.org/?probe=89edd8b343) | Mar 17, 2021 |
| HP            | ProLiant MicroServer Gen... | [af637820c2](https://linux-hardware.org/?probe=af637820c2) | Feb 12, 2021 |
| VIA Techno... | KM266APro-835               | [1334ad3f74](https://linux-hardware.org/?probe=1334ad3f74) | Dec 22, 2020 |
| Fujitsu       | D2779 S26361-D2779-A1       | [07795a357a](https://linux-hardware.org/?probe=07795a357a) | Oct 09, 2020 |
| Dell          | 0PU052                      | [9a31999f07](https://linux-hardware.org/?probe=9a31999f07) | Aug 31, 2020 |
| ASUSTek       | TS10                        | [71d7f6e110](https://linux-hardware.org/?probe=71d7f6e110) | Aug 20, 2020 |
| VIA Techno... | KM266APro-835               | [25ec3d44ff](https://linux-hardware.org/?probe=25ec3d44ff) | Aug 16, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | [58dce1215c](https://linux-hardware.org/?probe=58dce1215c) | Aug 13, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | [0c50242cc5](https://linux-hardware.org/?probe=0c50242cc5) | Aug 09, 2020 |
| ASRock        | J3455M                      | [05f9d5c3b4](https://linux-hardware.org/?probe=05f9d5c3b4) | Aug 06, 2020 |
| eMachines     | EL1352G                     | [4513d2931f](https://linux-hardware.org/?probe=4513d2931f) | Jul 03, 2020 |
| eMachines     | EL1352G                     | [4b26717c89](https://linux-hardware.org/?probe=4b26717c89) | Jul 03, 2020 |
| ASRock        | J3455M                      | [3719f96b60](https://linux-hardware.org/?probe=3719f96b60) | Jul 03, 2020 |
| Unknown       | i855GM/E-ITE8712            | [7b9cbd816b](https://linux-hardware.org/?probe=7b9cbd816b) | Dec 27, 2019 |
| ASRock        | D1800B-ITX                  | [f962d4bbf9](https://linux-hardware.org/?probe=f962d4bbf9) | Dec 22, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Alpine 3.12.0               | 5        | 16.13%  |
| Alpine 3.17_alpha20220809   | 4        | 12.9%   |
| Alpine 3.16.0               | 3        | 9.68%   |
| Alpine 3.13.0_alpha20200626 | 3        | 9.68%   |
| Alpine 3.15.4               | 2        | 6.45%   |
| Alpine 3.11.2               | 2        | 6.45%   |
| Alpine 3.8.4                | 1        | 3.23%   |
| Alpine 3.16.2               | 1        | 3.23%   |
| Alpine 3.16.1               | 1        | 3.23%   |
| Alpine 3.16.0_alpha20220328 | 1        | 3.23%   |
| Alpine 3.15.6               | 1        | 3.23%   |
| Alpine 3.15.0               | 1        | 3.23%   |
| Alpine 3.14.2               | 1        | 3.23%   |
| Alpine 3.13.6               | 1        | 3.23%   |
| Alpine 3.13.2               | 1        | 3.23%   |
| Alpine 3.13.1               | 1        | 3.23%   |
| Alpine 3.13.0_alpha20201218 | 1        | 3.23%   |
| Alpine 3.12.3               | 1        | 3.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Alpine | 29       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.43-1-lts      | 5        | 16.13%  |
| 5.15.60-0-lts     | 2        | 6.45%   |
| 6.0.10-0-edge     | 1        | 3.23%   |
| 5.8.0             | 1        | 3.23%   |
| 5.4.84-0-lts      | 1        | 3.23%   |
| 5.4.6-0-lts       | 1        | 3.23%   |
| 5.4.58-0-lts      | 1        | 3.23%   |
| 5.4.57-0-lts      | 1        | 3.23%   |
| 5.18.0-0-asahi    | 1        | 3.23%   |
| 5.17.9-0-edge     | 1        | 3.23%   |
| 5.17.3-0-edge     | 1        | 3.23%   |
| 5.15.74-0-lts     | 1        | 3.23%   |
| 5.15.70-0-lts     | 1        | 3.23%   |
| 5.15.57-0-lts     | 1        | 3.23%   |
| 5.15.46-1-lts     | 1        | 3.23%   |
| 5.15.40-0-lts     | 1        | 3.23%   |
| 5.15.38-0-lts     | 1        | 3.23%   |
| 5.15.32-0-lts     | 1        | 3.23%   |
| 5.15.17-0-lts     | 1        | 3.23%   |
| 5.10.81           | 1        | 3.23%   |
| 5.10.61-0-lts     | 1        | 3.23%   |
| 5.10.16-0-lts     | 1        | 3.23%   |
| 5.10.12-0-lts     | 1        | 3.23%   |
| 5.10.1-0-lts      | 1        | 3.23%   |
| 4.14.89-0-vanilla | 1        | 3.23%   |
| 3.10.105          | 1        | 3.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.43   | 5        | 16.13%  |
| 5.15.60  | 2        | 6.45%   |
| 6.0.10   | 1        | 3.23%   |
| 5.8.0    | 1        | 3.23%   |
| 5.4.84   | 1        | 3.23%   |
| 5.4.6    | 1        | 3.23%   |
| 5.4.58   | 1        | 3.23%   |
| 5.4.57   | 1        | 3.23%   |
| 5.18.0   | 1        | 3.23%   |
| 5.17.9   | 1        | 3.23%   |
| 5.17.3   | 1        | 3.23%   |
| 5.15.74  | 1        | 3.23%   |
| 5.15.70  | 1        | 3.23%   |
| 5.15.57  | 1        | 3.23%   |
| 5.15.46  | 1        | 3.23%   |
| 5.15.40  | 1        | 3.23%   |
| 5.15.38  | 1        | 3.23%   |
| 5.15.32  | 1        | 3.23%   |
| 5.15.17  | 1        | 3.23%   |
| 5.10.81  | 1        | 3.23%   |
| 5.10.61  | 1        | 3.23%   |
| 5.10.16  | 1        | 3.23%   |
| 5.10.12  | 1        | 3.23%   |
| 5.10.1   | 1        | 3.23%   |
| 4.14.89  | 1        | 3.23%   |
| 3.10.105 | 1        | 3.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 9        | 30%     |
| 5.15    | 9        | 30%     |
| 5.10    | 5        | 16.67%  |
| 5.17    | 2        | 6.67%   |
| 6.0     | 1        | 3.33%   |
| 5.8     | 1        | 3.33%   |
| 5.18    | 1        | 3.33%   |
| 4.14    | 1        | 3.33%   |
| 3.10    | 1        | 3.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 25       | 86.21%  |
| i686    | 3        | 10.34%  |
| aarch64 | 1        | 3.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 26       | 89.66%  |
| XFCE    | 1        | 3.45%   |
| sway    | 1        | 3.45%   |
| i3      | 1        | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 75.86%  |
| X11     | 6        | 20.69%  |
| Wayland | 1        | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 93.1%   |
| LightDM | 2        | 6.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 17       | 58.62%  |
| Unknown | 11       | 37.93%  |
| en_US   | 1        | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 20       | 68.97%  |
| EFI  | 9        | 31.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 25       | 86.21%  |
| Btrfs   | 2        | 6.9%    |
| Tmpfs   | 1        | 3.45%   |
| Unknown | 1        | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 53.33%  |
| GPT     | 9        | 30%     |
| MBR     | 5        | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 79.31%  |
| Yes       | 6        | 20.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 93.1%   |
| Yes       | 2        | 6.9%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 5        | 17.24%  |
| Dell                | 4        | 13.79%  |
| Gigabyte Technology | 3        | 10.34%  |
| ASRock              | 3        | 10.34%  |
| Intel               | 2        | 6.9%    |
| Hewlett-Packard     | 2        | 6.9%    |
| Fujitsu             | 2        | 6.9%    |
| Unknown             | 2        | 6.9%    |
| VIA Technologies    | 1        | 3.45%   |
| Shuttle             | 1        | 3.45%   |
| MSI                 | 1        | 3.45%   |
| Lenovo              | 1        | 3.45%   |
| Gateway             | 1        | 3.45%   |
| eMachines           | 1        | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Gigabyte Z490I AORUS ULTRA   | 2        | 6.9%    |
| ASUS All Series              | 2        | 6.9%    |
| Unknown                      | 2        | 6.9%    |
| VIA KM266APro-835            | 1        | 3.45%   |
| Shuttle DS81D                | 1        | 3.45%   |
| MSI MS-7877                  | 1        | 3.45%   |
| Lenovo H535 10117            | 1        | 3.45%   |
| Intel DQ67SW                 | 1        | 3.45%   |
| Intel DH61BF AAG81311-101    | 1        | 3.45%   |
| HP ProLiant MicroServer Gen8 | 1        | 3.45%   |
| HP Compaq 4000 Pro SFF PC    | 1        | 3.45%   |
| Gigabyte B550 AORUS ELITE V2 | 1        | 3.45%   |
| Gateway SX2185               | 1        | 3.45%   |
| Fujitsu PRIMERGY TX100 S2    | 1        | 3.45%   |
| Fujitsu FujitsuTP7000        | 1        | 3.45%   |
| eMachines EL1352G            | 1        | 3.45%   |
| Dell OptiPlex 755            | 1        | 3.45%   |
| Dell OptiPlex 3020M          | 1        | 3.45%   |
| Dell OptiPlex 3010           | 1        | 3.45%   |
| Dell Inspiron 3647           | 1        | 3.45%   |
| ASUS TS10                    | 1        | 3.45%   |
| ASUS PRIME H370M-PLUS        | 1        | 3.45%   |
| ASUS P8H67-V                 | 1        | 3.45%   |
| ASRock J3455M                | 1        | 3.45%   |
| ASRock H81M                  | 1        | 3.45%   |
| ASRock D1800B-ITX            | 1        | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 3        | 10.34%  |
| Gigabyte Z490I        | 2        | 6.9%    |
| ASUS All              | 2        | 6.9%    |
| Unknown               | 2        | 6.9%    |
| VIA KM266APro-835     | 1        | 3.45%   |
| Shuttle DS81D         | 1        | 3.45%   |
| MSI MS-7877           | 1        | 3.45%   |
| Lenovo H535           | 1        | 3.45%   |
| Intel DQ67SW          | 1        | 3.45%   |
| Intel DH61BF          | 1        | 3.45%   |
| HP ProLiant           | 1        | 3.45%   |
| HP Compaq             | 1        | 3.45%   |
| Gigabyte B550         | 1        | 3.45%   |
| Gateway SX2185        | 1        | 3.45%   |
| Fujitsu PRIMERGY      | 1        | 3.45%   |
| Fujitsu FujitsuTP7000 | 1        | 3.45%   |
| eMachines EL1352G     | 1        | 3.45%   |
| Dell Inspiron         | 1        | 3.45%   |
| ASUS TS10             | 1        | 3.45%   |
| ASUS PRIME            | 1        | 3.45%   |
| ASUS P8H67-V          | 1        | 3.45%   |
| ASRock J3455M         | 1        | 3.45%   |
| ASRock H81M           | 1        | 3.45%   |
| ASRock D1800B-ITX     | 1        | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 7        | 24.14%  |
| 2013    | 4        | 13.79%  |
| 2020    | 3        | 10.34%  |
| 2012    | 3        | 10.34%  |
| 2010    | 3        | 10.34%  |
| 2018    | 2        | 6.9%    |
| 2017    | 1        | 3.45%   |
| 2016    | 1        | 3.45%   |
| 2011    | 1        | 3.45%   |
| 2009    | 1        | 3.45%   |
| 2007    | 1        | 3.45%   |
| 2004    | 1        | 3.45%   |
| Unknown | 1        | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 29       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 29       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 29       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 7        | 22.58%  |
| 8.01-16.0  | 6        | 19.35%  |
| 4.01-8.0   | 5        | 16.13%  |
| 16.01-24.0 | 4        | 12.9%   |
| 32.01-64.0 | 3        | 9.68%   |
| 1.01-2.0   | 2        | 6.45%   |
| 0.51-1.0   | 2        | 6.45%   |
| 2.01-3.0   | 1        | 3.23%   |
| 0.01-0.5   | 1        | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 11       | 37.93%  |
| 1.01-2.0  | 8        | 27.59%  |
| 3.01-4.0  | 3        | 10.34%  |
| 0.51-1.0  | 3        | 10.34%  |
| 4.01-8.0  | 1        | 3.45%   |
| 2.01-3.0  | 1        | 3.45%   |
| 8.01-16.0 | 1        | 3.45%   |
| Unknown   | 1        | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 41.38%  |
| 3      | 7        | 24.14%  |
| 2      | 7        | 24.14%  |
| 4      | 3        | 10.34%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 86.21%  |
| Yes       | 4        | 13.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 96.55%  |
| No        | 1        | 3.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 75.86%  |
| Yes       | 7        | 24.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 82.76%  |
| Yes       | 5        | 17.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 24.14%  |
| Russia      | 4        | 13.79%  |
| Germany     | 3        | 10.34%  |
| UK          | 2        | 6.9%    |
| Sweden      | 2        | 6.9%    |
| Norway      | 2        | 6.9%    |
| Ukraine     | 1        | 3.45%   |
| Switzerland | 1        | 3.45%   |
| Spain       | 1        | 3.45%   |
| Poland      | 1        | 3.45%   |
| Pakistan    | 1        | 3.45%   |
| Indonesia   | 1        | 3.45%   |
| Guatemala   | 1        | 3.45%   |
| Austria     | 1        | 3.45%   |
| Argentina   | 1        | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Springfield         | 4        | 13.79%  |
| St Petersburg       | 3        | 10.34%  |
| Manitowoc           | 2        | 6.9%    |
| As                  | 2        | 6.9%    |
| Zurich              | 1        | 3.45%   |
| Stockholm           | 1        | 3.45%   |
| Salzburg            | 1        | 3.45%   |
| Redwood City        | 1        | 3.45%   |
| Penza               | 1        | 3.45%   |
| Oberhausen          | 1        | 3.45%   |
| Lahore              | 1        | 3.45%   |
| Kharkiv             | 1        | 3.45%   |
| Jember              | 1        | 3.45%   |
| Hamburg             | 1        | 3.45%   |
| Guatemala City      | 1        | 3.45%   |
| Gothenburg          | 1        | 3.45%   |
| Glasgow             | 1        | 3.45%   |
| General San Martin  | 1        | 3.45%   |
| Frankfurt am Main   | 1        | 3.45%   |
| Czarna Białostocka | 1        | 3.45%   |
| Barrow in Furness   | 1        | 3.45%   |
| Barcelona           | 1        | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 14     | 18.18%  |
| Samsung Electronics | 8        | 15     | 18.18%  |
| WDC                 | 5        | 6      | 11.36%  |
| Hitachi             | 3        | 3      | 6.82%   |
| Toshiba             | 2        | 2      | 4.55%   |
| Kingston            | 2        | 2      | 4.55%   |
| Intel               | 2        | 3      | 4.55%   |
| HGST                | 2        | 2      | 4.55%   |
| Crucial             | 2        | 5      | 4.55%   |
| A-DATA Technology   | 2        | 2      | 4.55%   |
| Unknown             | 1        | 1      | 2.27%   |
| Transcend           | 1        | 1      | 2.27%   |
| SK hynix            | 1        | 1      | 2.27%   |
| SanDisk             | 1        | 1      | 2.27%   |
| LITEON              | 1        | 1      | 2.27%   |
| Lexar               | 1        | 1      | 2.27%   |
| Kingmax             | 1        | 1      | 2.27%   |
| Apple               | 1        | 3      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Samsung SSD 960 EVO 500GB                     | 2        | 4%      |
| WDC WD800AAJS-00 80GB                         | 1        | 2%      |
| WDC WD3200AAKX-0 320GB                        | 1        | 2%      |
| WDC WD20EZRZ-00Z 2TB                          | 1        | 2%      |
| WDC WD1600BEVT-2 160GB                        | 1        | 2%      |
| WDC WD10JPVX-75JC3T0 1TB                      | 1        | 2%      |
| WDC WD10EZEX-21M2NA0 1TB                      | 1        | 2%      |
| Unknown MMC Card  32GB                        | 1        | 2%      |
| Transcend SSD 1GB                             | 1        | 2%      |
| Toshiba MQ01ABF050 500GB                      | 1        | 2%      |
| Toshiba MK3252GS 320GB                        | 1        | 2%      |
| SK hynix SC300 M.2 2280 256 256GB SSD         | 1        | 2%      |
| Seagate ST980310AS 80GB                       | 1        | 2%      |
| Seagate ST4000VN008-2DR1 4TB                  | 1        | 2%      |
| Seagate ST4000NC000-1FR1 4TB                  | 1        | 2%      |
| Seagate ST380815AS 80GB                       | 1        | 2%      |
| Seagate ST3500418AS 500GB                     | 1        | 2%      |
| Seagate ST2000DL001-9VT1 2TB                  | 1        | 2%      |
| Seagate ST1000LM048-2E71 1TB                  | 1        | 2%      |
| Seagate ST1000DM010-2EP102 1TB                | 1        | 2%      |
| SanDisk SDSA6MM 16GB SSD                      | 1        | 2%      |
| Samsung SSD 980 PRO 1TB                       | 1        | 2%      |
| Samsung SSD 980 500GB                         | 1        | 2%      |
| Samsung SSD 970 EVO Plus 1TB                  | 1        | 2%      |
| Samsung SSD 970 EVO 250GB                     | 1        | 2%      |
| Samsung SSD 870 QVO 1TB                       | 1        | 2%      |
| Samsung SSD 870 EVO 1TB                       | 1        | 2%      |
| Samsung SSD 850 EVO 500GB                     | 1        | 2%      |
| Samsung SSD 750 EVO 250GB                     | 1        | 2%      |
| Samsung SP0411N 40GB                          | 1        | 2%      |
| Samsung NVMe SSD Controller SM951/PM951 256GB | 1        | 2%      |
| LITEON CV3-CE128 128GB SSD                    | 1        | 2%      |
| Lexar 256GB SSD                               | 1        | 2%      |
| Kingston SVP200S 120GB SSD                    | 1        | 2%      |
| Kingston SA400S3 120GB SSD                    | 1        | 2%      |
| Kingmax SSD 120G                              | 1        | 2%      |
| Intel SSDSC2BW24 240GB                        | 1        | 2%      |
| Intel SSDSC2BW120A4 120GB                     | 1        | 2%      |
| Intel SSDSC2BB24 240GB                        | 1        | 2%      |
| Hitachi HTS722080K9A300 80GB                  | 1        | 2%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 14     | 38.1%   |
| WDC                 | 5        | 6      | 23.81%  |
| Hitachi             | 3        | 3      | 14.29%  |
| Toshiba             | 2        | 2      | 9.52%   |
| HGST                | 2        | 2      | 9.52%   |
| Samsung Electronics | 1        | 2      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 6      | 22.22%  |
| Kingston            | 2        | 2      | 11.11%  |
| Intel               | 2        | 3      | 11.11%  |
| Crucial             | 2        | 5      | 11.11%  |
| A-DATA Technology   | 2        | 2      | 11.11%  |
| Transcend           | 1        | 1      | 5.56%   |
| SK hynix            | 1        | 1      | 5.56%   |
| SanDisk             | 1        | 1      | 5.56%   |
| LITEON              | 1        | 1      | 5.56%   |
| Lexar               | 1        | 1      | 5.56%   |
| Kingmax             | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 29     | 41.46%  |
| SSD  | 16       | 24     | 39.02%  |
| NVMe | 7        | 10     | 17.07%  |
| MMC  | 1        | 1      | 2.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 26       | 51     | 74.29%  |
| NVMe | 7        | 10     | 20%     |
| SAS  | 1        | 2      | 2.86%   |
| MMC  | 1        | 1      | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 23       | 34     | 71.88%  |
| 0.51-1.0   | 5        | 9      | 15.63%  |
| 3.01-4.0   | 2        | 6      | 6.25%   |
| 1.01-2.0   | 1        | 3      | 3.13%   |
| 4.01-10.0  | 1        | 1      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 7        | 24.14%  |
| Unknown        | 7        | 24.14%  |
| 21-50          | 4        | 13.79%  |
| 1-20           | 4        | 13.79%  |
| 251-500        | 2        | 6.9%    |
| 2001-3000      | 2        | 6.9%    |
| More than 3000 | 1        | 3.45%   |
| 1001-2000      | 1        | 3.45%   |
| 51-100         | 1        | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 15       | 51.72%  |
| Unknown   | 7        | 24.14%  |
| 21-50     | 3        | 10.34%  |
| 251-500   | 1        | 3.45%   |
| 2001-3000 | 1        | 3.45%   |
| 1001-2000 | 1        | 3.45%   |
| 51-100    | 1        | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD3200AAKX-0 320GB           | 1        | 1      | 16.67%  |
| Toshiba MK3252GS 320GB           | 1        | 1      | 16.67%  |
| SanDisk SDSA6MM 16GB SSD         | 1        | 1      | 16.67%  |
| Samsung Electronics SP0411N 40GB | 1        | 2      | 16.67%  |
| Kingmax SSD 120G                 | 1        | 1      | 16.67%  |
| Hitachi HTS722080K9A300 80GB     | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 16.67%  |
| Toshiba             | 1        | 1      | 16.67%  |
| SanDisk             | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 2      | 16.67%  |
| Kingmax             | 1        | 1      | 16.67%  |
| Hitachi             | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 25%     |
| Toshiba             | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 2      | 25%     |
| Hitachi             | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 5      | 66.67%  |
| SSD  | 2        | 2      | 33.33%  |

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
| Works    | 25       | 53     | 73.53%  |
| Malfunc  | 6        | 7      | 17.65%  |
| Detected | 3        | 4      | 8.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 22       | 59.46%  |
| Samsung Electronics       | 5        | 13.51%  |
| AMD                       | 3        | 8.11%   |
| Adaptec                   | 2        | 5.41%   |
| VIA Technologies          | 1        | 2.7%    |
| Promise Technology        | 1        | 2.7%    |
| Nvidia                    | 1        | 2.7%    |
| LSI Logic / Symbios Logic | 1        | 2.7%    |
| ASMedia Technology        | 1        | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 9.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 9.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 4.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 4.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 4.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 4.76%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2        | 4.76%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 4.76%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 2        | 4.76%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1        | 2.38%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 2.38%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 2.38%   |
| Promise PDC42819 [FastTrak TX2650/TX4650]                                      | 1        | 2.38%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 2.38%   |
| Nvidia MCP61 IDE                                                               | 1        | 2.38%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1        | 2.38%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 2.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1        | 2.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 2.38%   |
| Intel 82Q35 Express PT IDER Controller                                         | 1        | 2.38%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 2.38%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 2.38%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 1        | 2.38%   |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                        | 1        | 2.38%   |
| Intel 5 Series/3400 Series Chipset SATA RAID Controller                        | 1        | 2.38%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 2.38%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 2.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 21       | 53.85%  |
| RAID | 6        | 15.38%  |
| IDE  | 6        | 15.38%  |
| NVMe | 5        | 12.82%  |
| SAS  | 1        | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 23       | 79.31%  |
| AMD     | 5        | 17.24%  |
| Unknown | 1        | 3.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i9-10900 CPU @ 2.80GHz       | 2        | 6.9%    |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2        | 6.9%    |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2        | 6.9%    |
| Intel Core i3-4150 CPU @ 3.50GHz        | 2        | 6.9%    |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1        | 3.45%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz  | 1        | 3.45%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 1        | 3.45%   |
| Intel Core i5-4590T CPU @ 2.00GHz       | 1        | 3.45%   |
| Intel Core i5-3450 CPU @ 3.10GHz        | 1        | 3.45%   |
| Intel Core i3-3240 CPU @ 3.40GHz        | 1        | 3.45%   |
| Intel Core i3-3220T CPU @ 2.80GHz       | 1        | 3.45%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 1        | 3.45%   |
| Intel Celeron M processor 1.00GHz       | 1        | 3.45%   |
| Intel Celeron CPU J3455 @ 1.50GHz       | 1        | 3.45%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 1        | 3.45%   |
| Intel Celeron CPU J1800 @ 2.41GHz       | 1        | 3.45%   |
| Intel Celeron CPU G1850 @ 2.90GHz       | 1        | 3.45%   |
| Intel Celeron CPU E3400 @ 2.60GHz       | 1        | 3.45%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 1        | 3.45%   |
| AMD Sempron 145 Processor               | 1        | 3.45%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 1        | 3.45%   |
| AMD Mobile Duron processor              | 1        | 3.45%   |
| AMD E1-2500 APU with Radeon HD Graphics | 1        | 3.45%   |
| AMD A8-5500 APU with Radeon HD Graphics | 1        | 3.45%   |
|                                         | 1        | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 5        | 17.24%  |
| Intel Core i3      | 5        | 17.24%  |
| Intel Celeron      | 5        | 17.24%  |
| Other              | 2        | 6.9%    |
| Intel Core i9      | 2        | 6.9%    |
| Intel Core i7      | 2        | 6.9%    |
| Intel Xeon         | 1        | 3.45%   |
| Intel Pentium Dual | 1        | 3.45%   |
| Intel Celeron M    | 1        | 3.45%   |
| Intel Atom         | 1        | 3.45%   |
| AMD Sempron        | 1        | 3.45%   |
| AMD Ryzen 9        | 1        | 3.45%   |
| AMD E1             | 1        | 3.45%   |
| AMD A8             | 1        | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 12       | 41.38%  |
| 2      | 10       | 34.48%  |
| 1      | 3        | 10.34%  |
| 10     | 2        | 6.9%    |
| 12     | 1        | 3.45%   |
| 6      | 1        | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 29       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 65.52%  |
| 2      | 10       | 34.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 15       | 51.72%  |
| 32-bit, 64-bit | 11       | 37.93%  |
| 32-bit         | 2        | 6.9%    |
| 64-bit         | 1        | 3.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 53.33%  |
| 0x306c3    | 3        | 10%     |
| 0x306a9    | 2        | 6.67%   |
| 0xa0655    | 1        | 3.33%   |
| 0x906ea    | 1        | 3.33%   |
| 0x6fd      | 1        | 3.33%   |
| 0x6d8      | 1        | 3.33%   |
| 0x506c9    | 1        | 3.33%   |
| 0x406c4    | 1        | 3.33%   |
| 0x106e5    | 1        | 3.33%   |
| 0x08701021 | 1        | 3.33%   |
| 0x010000b6 | 1        | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 6        | 20.69%  |
| Silvermont  | 3        | 10.34%  |
| SandyBridge | 3        | 10.34%  |
| IvyBridge   | 3        | 10.34%  |
| CometLake   | 2        | 6.9%    |
| Zen 2       | 1        | 3.45%   |
| Piledriver  | 1        | 3.45%   |
| Penryn      | 1        | 3.45%   |
| P6          | 1        | 3.45%   |
| Nehalem     | 1        | 3.45%   |
| KabyLake    | 1        | 3.45%   |
| K6          | 1        | 3.45%   |
| K10         | 1        | 3.45%   |
| Jaguar      | 1        | 3.45%   |
| Goldmont    | 1        | 3.45%   |
| Core        | 1        | 3.45%   |
| Unknown     | 1        | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 20       | 68.97%  |
| AMD                        | 5        | 17.24%  |
| Nvidia                     | 2        | 6.9%    |
| VIA Technologies           | 1        | 3.45%   |
| Matrox Electronics Systems | 1        | 3.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 10.34%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 10.34%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 6.9%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 6.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 6.9%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 6.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 6.9%    |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1        | 3.45%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1        | 3.45%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 3.45%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 3.45%   |
| Intel HD Graphics 500                                                                    | 1        | 3.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 3.45%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 3.45%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1        | 3.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 3.45%   |
| AMD Trinity [Radeon HD 7560D]                                                            | 1        | 3.45%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                                   | 1        | 3.45%   |
| AMD ES1000                                                                               | 1        | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 18       | 62.07%  |
| 1 x AMD    | 5        | 17.24%  |
| 1 x Nvidia | 2        | 6.9%    |
| Other      | 1        | 3.45%   |
| 2 x Intel  | 1        | 3.45%   |
| 1 x VIA    | 1        | 3.45%   |
| 1 x Matrox | 1        | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 24       | 82.76%  |
| Unknown | 5        | 17.24%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 79.31%  |
| 7.01-8.0   | 2        | 6.9%    |
| 0.01-0.5   | 2        | 6.9%    |
| 3.01-4.0   | 1        | 3.45%   |
| 1.01-2.0   | 1        | 3.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 5        | 23.81%  |
| Samsung Electronics | 3        | 14.29%  |
| BenQ                | 3        | 14.29%  |
| AOC                 | 3        | 14.29%  |
| Acer                | 2        | 9.52%   |
| ViewSonic           | 1        | 4.76%   |
| Mi                  | 1        | 4.76%   |
| Goldstar            | 1        | 4.76%   |
| Elo Touch           | 1        | 4.76%   |
| CTC                 | 1        | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                      | 3        | 13.64%  |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 2        | 9.09%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1        | 4.55%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch  | 1        | 4.55%   |
| Samsung Electronics LCD Monitor SAM0B60 1680x1050 887x500mm 40.1-inch | 1        | 4.55%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                      | 1        | 4.55%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1        | 4.55%   |
| Elo Touch ET1717L ELO1717 1280x1024 338x270mm 17.0-inch               | 1        | 4.55%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                     | 1        | 4.55%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                     | 1        | 4.55%   |
| CTC KD02909-8770A CTC0770 1024x768 304x228mm 15.0-inch                | 1        | 4.55%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch               | 1        | 4.55%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                     | 1        | 4.55%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                     | 1        | 4.55%   |
| AOC 718Swag-1 AOCC750 1440x900 367x230mm 17.1-inch                    | 1        | 4.55%   |
| AOC 2476WM AOC2476 1920x1080 521x293mm 23.5-inch                      | 1        | 4.55%   |
| AOC 2269W AOC2269 1920x1080 480x270mm 21.7-inch                       | 1        | 4.55%   |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                     | 1        | 4.55%   |
| Acer S236HL ACR0387 1920x1080 510x286mm 23.0-inch                     | 1        | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 8        | 38.1%   |
| 1680x1050 (WSXGA+) | 4        | 19.05%  |
| 1280x1024 (SXGA)   | 3        | 14.29%  |
| 3440x1440          | 2        | 9.52%   |
| 3840x2160 (4K)     | 1        | 4.76%   |
| 2560x1440 (QHD)    | 1        | 4.76%   |
| 1440x900 (WXGA+)   | 1        | 4.76%   |
| 1024x768 (XGA)     | 1        | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 20     | 4        | 18.18%  |
| 23     | 3        | 13.64%  |
| 21     | 3        | 13.64%  |
| 17     | 3        | 13.64%  |
| 34     | 2        | 9.09%   |
| 27     | 2        | 9.09%   |
| 24     | 2        | 9.09%   |
| 54     | 1        | 4.55%   |
| 19     | 1        | 4.55%   |
| 15     | 1        | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 7        | 31.82%  |
| 401-500     | 7        | 31.82%  |
| 301-350     | 3        | 13.64%  |
| 701-800     | 2        | 9.09%   |
| 351-400     | 2        | 9.09%   |
| 1001-1500   | 1        | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 9        | 47.37%  |
| 16/10 | 4        | 21.05%  |
| 5/4   | 3        | 15.79%  |
| 21/9  | 2        | 10.53%  |
| 4/3   | 1        | 5.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 31.82%  |
| 151-200        | 6        | 27.27%  |
| 351-500        | 2        | 9.09%   |
| 301-350        | 2        | 9.09%   |
| 141-150        | 2        | 9.09%   |
| More than 1000 | 1        | 4.55%   |
| 131-140        | 1        | 4.55%   |
| 101-110        | 1        | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 13       | 65%     |
| 1-50    | 3        | 15%     |
| 101-120 | 3        | 15%     |
| 161-240 | 1        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 58.62%  |
| 0     | 10       | 34.48%  |
| 4     | 1        | 3.45%   |
| 2     | 1        | 3.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 16       | 41.03%  |
| Intel                           | 8        | 20.51%  |
| Broadcom                        | 4        | 10.26%  |
| Qualcomm Atheros                | 3        | 7.69%   |
| Xiaomi                          | 2        | 5.13%   |
| VIA Technologies                | 1        | 2.56%   |
| T & A Mobile Phones             | 1        | 2.56%   |
| Qualcomm Atheros Communications | 1        | 2.56%   |
| Qualcomm                        | 1        | 2.56%   |
| Nvidia                          | 1        | 2.56%   |
| D-Link System                   | 1        | 2.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 29.55%  |
| Intel Ethernet Controller I225-V                                  | 2        | 4.55%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 4.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 2.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 2.27%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 2.27%   |
| T & A Mobile Phones A509DL                                        | 1        | 2.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 2.27%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.27%   |
| Qualcomm Redmi Note 8                                             | 1        | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 2.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.27%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 2.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.27%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.27%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.27%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2.27%   |
| Intel 82567V-4 Gigabit Network Connection                         | 1        | 2.27%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2.27%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 2.27%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 2.27%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 2.27%   |
| Broadcom BRCM4378 Wireless Network Adapter                        | 1        | 2.27%   |
| Broadcom BRCM4378 Bluetooth Controller                            | 1        | 2.27%   |
| Broadcom BCM43227 802.11b/g/n                                     | 1        | 2.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 2        | 25%     |
| Intel                           | 2        | 25%     |
| Broadcom                        | 2        | 25%     |
| Qualcomm Atheros Communications | 1        | 12.5%   |
| Qualcomm Atheros                | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Comet Lake PCH CNVi WiFi                             | 2        | 25%     |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1        | 12.5%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 12.5%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 12.5%   |
| Qualcomm Atheros AR9271 802.11n                            | 1        | 12.5%   |
| Broadcom BRCM4378 Wireless Network Adapter                 | 1        | 12.5%   |
| Broadcom BCM43227 802.11b/g/n                              | 1        | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 16       | 47.06%  |
| Intel                 | 8        | 23.53%  |
| Xiaomi                | 2        | 5.88%   |
| Qualcomm Atheros      | 2        | 5.88%   |
| Broadcom              | 2        | 5.88%   |
| VIA Technologies      | 1        | 2.94%   |
| Qualcomm              | 1        | 2.94%   |
| Nvidia                | 1        | 2.94%   |
| D-Link System         | 1        | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 38.24%  |
| Intel Ethernet Controller I225-V                                  | 2        | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 5.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 2.94%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 2.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.94%   |
| Qualcomm Redmi Note 8                                             | 1        | 2.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.94%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.94%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.94%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2.94%   |
| Intel 82567V-4 Gigabit Network Connection                         | 1        | 2.94%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2.94%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 2.94%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 2.94%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 75.68%  |
| WiFi     | 7        | 18.92%  |
| Unknown  | 2        | 5.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 89.29%  |
| WiFi     | 3        | 10.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 63.33%  |
| 2     | 7        | 23.33%  |
| 3     | 2        | 6.67%   |
| 5     | 1        | 3.33%   |
| 4     | 1        | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 93.1%   |
| Yes  | 2        | 6.9%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 40%     |
| Cambridge Silicon Radio | 2        | 40%     |
| IMC Networks            | 1        | 20%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX201 Bluetooth                               | 2        | 40%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 40%     |
| IMC Networks Bluetooth Device                       | 1        | 20%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 19       | 65.52%  |
| AMD                                  | 5        | 17.24%  |
| VIA Technologies                     | 1        | 3.45%   |
| Thesycon Systemsoftware & Consulting | 1        | 3.45%   |
| RODE Microphones                     | 1        | 3.45%   |
| Nvidia                               | 1        | 3.45%   |
| Native Instruments                   | 1        | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 11.43%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 11.43%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 8.57%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 5.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 5.71%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 5.71%   |
| AMD FCH Azalia Controller                                                  | 2        | 5.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 5.71%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 2.86%   |
| Thesycon Systemsoftware & Consulting D90                                   | 1        | 2.86%   |
| RODE Microphones RODE NT-USB Mini                                          | 1        | 2.86%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 2.86%   |
| Native Instruments Komplete Audio 2                                        | 1        | 2.86%   |
| Intel USB PnP Sound Device                                                 | 1        | 2.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.86%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 2.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 2.86%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1        | 2.86%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 2.86%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 2.86%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 2.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 6        | 15.38%  |
| Crucial             | 6        | 15.38%  |
| Unknown             | 5        | 12.82%  |
| Kingston            | 5        | 12.82%  |
| Samsung Electronics | 4        | 10.26%  |
| Elpida              | 4        | 10.26%  |
| Micron Technology   | 2        | 5.13%   |
| Corsair             | 2        | 5.13%   |
| Qimonda             | 1        | 2.56%   |
| Patriot             | 1        | 2.56%   |
| Hewlett-Packard     | 1        | 2.56%   |
| Cors                | 1        | 2.56%   |
| A-DATA Technology   | 1        | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s      | 2        | 4.65%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s | 2        | 4.65%   |
| Unknown RAM Module 512MB DIMM                            | 1        | 2.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 2.33%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s             | 1        | 2.33%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 2.33%   |
| Unknown RAM Module 128MB DIMM                            | 1        | 2.33%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 2.33%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 2.33%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 2.33%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s  | 1        | 2.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2.33%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 2.33%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 2.33%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s   | 1        | 2.33%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1600MT/s   | 1        | 2.33%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.33%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s         | 1        | 2.33%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 2.33%   |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s      | 1        | 2.33%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 2.33%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s      | 1        | 2.33%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 1        | 2.33%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 2.33%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s    | 1        | 2.33%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 2.33%   |
| Kingston RAM 9905595-005.A00LF 2GB DIMM DDR3 1600MT/s    | 1        | 2.33%   |
| Kingston RAM 9905474-019.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 2.33%   |
| HP RAM Module 4GB DIMM DDR3 1600MT/s                     | 1        | 2.33%   |
| Elpida RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 2.33%   |
| Elpida RAM EBE10UE8ACWA-6E-E 1GB DIMM DDR2 667MT/s       | 1        | 2.33%   |
| Crucial RAM CT51264BF160B.C16F 4096MB DIMM DDR3 1600MT/s | 1        | 2.33%   |
| Crucial RAM CT25664BA160B.C16F 2GB DIMM DDR3 1600MT/s    | 1        | 2.33%   |
| Crucial RAM CT102464BA160B.M16 8GB DIMM DDR3 1600MT/s    | 1        | 2.33%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s   | 1        | 2.33%   |
| Corsair RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 2.33%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 1        | 2.33%   |
| Cors RAM CMX16GX3M2A1333C9 8192MB DIMM DDR3 1333MT/s     | 1        | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 21       | 70%     |
| DDR4    | 5        | 16.67%  |
| SDRAM   | 2        | 6.67%   |
| DDR2    | 1        | 3.33%   |
| Unknown | 1        | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 27       | 93.1%   |
| SODIMM | 2        | 6.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 11       | 32.35%  |
| 4096  | 10       | 29.41%  |
| 2048  | 7        | 20.59%  |
| 16384 | 2        | 5.88%   |
| 1024  | 2        | 5.88%   |
| 512   | 1        | 2.94%   |
| 128   | 1        | 2.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 17       | 50%     |
| 1333    | 4        | 11.76%  |
| 3600    | 3        | 8.82%   |
| 2400    | 2        | 5.88%   |
| 1866    | 2        | 5.88%   |
| Unknown | 2        | 5.88%   |
| 2200    | 1        | 2.94%   |
| 2133    | 1        | 2.94%   |
| 1800    | 1        | 2.94%   |
| 667     | 1        | 2.94%   |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Z-Star Microelectronics | 2        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Z-Star Vimicro USB2.0 Camera      | 1        | 50%     |
| Z-Star A4 TECH USB2.0 PC Camera J | 1        | 50%     |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 22       | 75.86%  |
| 1     | 5        | 17.24%  |
| 5     | 1        | 3.45%   |
| 3     | 1        | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 45.45%  |
| Net/wireless             | 2        | 18.18%  |
| Sound                    | 1        | 9.09%   |
| Network                  | 1        | 9.09%   |
| Net/ethernet             | 1        | 9.09%   |
| Communication controller | 1        | 9.09%   |

