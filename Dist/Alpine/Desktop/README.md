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

Total: 29

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Alpine 3.12.0               | 5        | 22.73%  |
| Alpine 3.13.0_alpha20200626 | 3        | 13.64%  |
| Alpine 3.16.0               | 2        | 9.09%   |
| Alpine 3.11.2               | 2        | 9.09%   |
| Alpine 3.8.4                | 1        | 4.55%   |
| Alpine 3.16.0_alpha20220328 | 1        | 4.55%   |
| Alpine 3.15.4               | 1        | 4.55%   |
| Alpine 3.15.0               | 1        | 4.55%   |
| Alpine 3.14.2               | 1        | 4.55%   |
| Alpine 3.13.6               | 1        | 4.55%   |
| Alpine 3.13.2               | 1        | 4.55%   |
| Alpine 3.13.1               | 1        | 4.55%   |
| Alpine 3.13.0_alpha20201218 | 1        | 4.55%   |
| Alpine 3.12.3               | 1        | 4.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Alpine | 21       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.43-1-lts      | 5        | 22.73%  |
| 5.8.0             | 1        | 4.55%   |
| 5.4.84-0-lts      | 1        | 4.55%   |
| 5.4.6-0-lts       | 1        | 4.55%   |
| 5.4.58-0-lts      | 1        | 4.55%   |
| 5.4.57-0-lts      | 1        | 4.55%   |
| 5.17.9-0-edge     | 1        | 4.55%   |
| 5.17.3-0-edge     | 1        | 4.55%   |
| 5.15.46-1-lts     | 1        | 4.55%   |
| 5.15.38-0-lts     | 1        | 4.55%   |
| 5.15.17-0-lts     | 1        | 4.55%   |
| 5.10.81           | 1        | 4.55%   |
| 5.10.61-0-lts     | 1        | 4.55%   |
| 5.10.16-0-lts     | 1        | 4.55%   |
| 5.10.12-0-lts     | 1        | 4.55%   |
| 5.10.1-0-lts      | 1        | 4.55%   |
| 4.14.89-0-vanilla | 1        | 4.55%   |
| 3.10.105          | 1        | 4.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.43   | 5        | 22.73%  |
| 5.8.0    | 1        | 4.55%   |
| 5.4.84   | 1        | 4.55%   |
| 5.4.6    | 1        | 4.55%   |
| 5.4.58   | 1        | 4.55%   |
| 5.4.57   | 1        | 4.55%   |
| 5.17.9   | 1        | 4.55%   |
| 5.17.3   | 1        | 4.55%   |
| 5.15.46  | 1        | 4.55%   |
| 5.15.38  | 1        | 4.55%   |
| 5.15.17  | 1        | 4.55%   |
| 5.10.81  | 1        | 4.55%   |
| 5.10.61  | 1        | 4.55%   |
| 5.10.16  | 1        | 4.55%   |
| 5.10.12  | 1        | 4.55%   |
| 5.10.1   | 1        | 4.55%   |
| 4.14.89  | 1        | 4.55%   |
| 3.10.105 | 1        | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 9        | 40.91%  |
| 5.10    | 5        | 22.73%  |
| 5.15    | 3        | 13.64%  |
| 5.17    | 2        | 9.09%   |
| 5.8     | 1        | 4.55%   |
| 4.14    | 1        | 4.55%   |
| 3.10    | 1        | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 19       | 90.48%  |
| i686   | 2        | 9.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 85.71%  |
| XFCE    | 1        | 4.76%   |
| sway    | 1        | 4.76%   |
| i3      | 1        | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 71.43%  |
| X11     | 5        | 23.81%  |
| Wayland | 1        | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 20       | 95.24%  |
| LightDM | 1        | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 10       | 47.62%  |
| Unknown | 10       | 47.62%  |
| en_US   | 1        | 4.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 15       | 71.43%  |
| EFI  | 6        | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 18       | 85.71%  |
| Tmpfs   | 1        | 4.76%   |
| Btrfs   | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 50%     |
| GPT     | 7        | 31.82%  |
| MBR     | 4        | 18.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 85.71%  |
| Yes       | 3        | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 90.48%  |
| Yes       | 2        | 9.52%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 5        | 23.81%  |
| Dell                | 4        | 19.05%  |
| Gigabyte Technology | 2        | 9.52%   |
| ASRock              | 2        | 9.52%   |
| VIA Technologies    | 1        | 4.76%   |
| Shuttle             | 1        | 4.76%   |
| MSI                 | 1        | 4.76%   |
| Lenovo              | 1        | 4.76%   |
| Hewlett-Packard     | 1        | 4.76%   |
| Fujitsu             | 1        | 4.76%   |
| eMachines           | 1        | 4.76%   |
| Unknown             | 1        | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Gigabyte Z490I AORUS ULTRA   | 2        | 9.52%   |
| ASUS All Series              | 2        | 9.52%   |
| VIA KM266APro-835            | 1        | 4.76%   |
| Shuttle DS81D                | 1        | 4.76%   |
| MSI MS-7877                  | 1        | 4.76%   |
| Lenovo H535 10117            | 1        | 4.76%   |
| HP ProLiant MicroServer Gen8 | 1        | 4.76%   |
| Fujitsu PRIMERGY TX100 S2    | 1        | 4.76%   |
| eMachines EL1352G            | 1        | 4.76%   |
| Dell OptiPlex 755            | 1        | 4.76%   |
| Dell OptiPlex 3020M          | 1        | 4.76%   |
| Dell OptiPlex 3010           | 1        | 4.76%   |
| Dell Inspiron 3647           | 1        | 4.76%   |
| ASUS TS10                    | 1        | 4.76%   |
| ASUS PRIME H370M-PLUS        | 1        | 4.76%   |
| ASUS P8H67-V                 | 1        | 4.76%   |
| ASRock J3455M                | 1        | 4.76%   |
| ASRock D1800B-ITX            | 1        | 4.76%   |
| Unknown                      | 1        | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Dell OptiPlex     | 3        | 14.29%  |
| Gigabyte Z490I    | 2        | 9.52%   |
| ASUS All          | 2        | 9.52%   |
| VIA KM266APro-835 | 1        | 4.76%   |
| Shuttle DS81D     | 1        | 4.76%   |
| MSI MS-7877       | 1        | 4.76%   |
| Lenovo H535       | 1        | 4.76%   |
| HP ProLiant       | 1        | 4.76%   |
| Fujitsu PRIMERGY  | 1        | 4.76%   |
| eMachines EL1352G | 1        | 4.76%   |
| Dell Inspiron     | 1        | 4.76%   |
| ASUS TS10         | 1        | 4.76%   |
| ASUS PRIME        | 1        | 4.76%   |
| ASUS P8H67-V      | 1        | 4.76%   |
| ASRock J3455M     | 1        | 4.76%   |
| ASRock D1800B-ITX | 1        | 4.76%   |
| Unknown           | 1        | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 7        | 33.33%  |
| 2010 | 3        | 14.29%  |
| 2020 | 2        | 9.52%   |
| 2013 | 2        | 9.52%   |
| 2018 | 1        | 4.76%   |
| 2017 | 1        | 4.76%   |
| 2016 | 1        | 4.76%   |
| 2012 | 1        | 4.76%   |
| 2009 | 1        | 4.76%   |
| 2007 | 1        | 4.76%   |
| 2004 | 1        | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 21       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 21       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 5        | 22.73%  |
| 8.01-16.0  | 5        | 22.73%  |
| 32.01-64.0 | 3        | 13.64%  |
| 16.01-24.0 | 3        | 13.64%  |
| 4.01-8.0   | 2        | 9.09%   |
| 0.51-1.0   | 2        | 9.09%   |
| 1.01-2.0   | 1        | 4.55%   |
| 0.01-0.5   | 1        | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 8        | 38.1%   |
| 1.01-2.0  | 5        | 23.81%  |
| 3.01-4.0  | 3        | 14.29%  |
| 0.51-1.0  | 2        | 9.52%   |
| 4.01-8.0  | 1        | 4.76%   |
| 8.01-16.0 | 1        | 4.76%   |
| Unknown   | 1        | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 9        | 42.86%  |
| 2      | 5        | 23.81%  |
| 3      | 4        | 19.05%  |
| 4      | 3        | 14.29%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 80.95%  |
| Yes       | 4        | 19.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 20       | 95.24%  |
| No        | 1        | 4.76%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 76.19%  |
| Yes       | 5        | 23.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 80.95%  |
| Yes       | 4        | 19.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 4        | 19.05%  |
| Russia      | 4        | 19.05%  |
| Sweden      | 2        | 9.52%   |
| Norway      | 2        | 9.52%   |
| Ukraine     | 1        | 4.76%   |
| UK          | 1        | 4.76%   |
| Switzerland | 1        | 4.76%   |
| Spain       | 1        | 4.76%   |
| Pakistan    | 1        | 4.76%   |
| Indonesia   | 1        | 4.76%   |
| Guatemala   | 1        | 4.76%   |
| Germany     | 1        | 4.76%   |
| Austria     | 1        | 4.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| St Petersburg     | 3        | 14.29%  |
| Manitowoc         | 2        | 9.52%   |
| As                | 2        | 9.52%   |
| Zurich            | 1        | 4.76%   |
| Stockholm         | 1        | 4.76%   |
| Springfield       | 1        | 4.76%   |
| Salzburg          | 1        | 4.76%   |
| Redwood City      | 1        | 4.76%   |
| Penza             | 1        | 4.76%   |
| Lahore            | 1        | 4.76%   |
| Kharkiv           | 1        | 4.76%   |
| Jember            | 1        | 4.76%   |
| Hamburg           | 1        | 4.76%   |
| Guatemala City    | 1        | 4.76%   |
| Gothenburg        | 1        | 4.76%   |
| Barrow in Furness | 1        | 4.76%   |
| Barcelona         | 1        | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 13     | 21.88%  |
| Seagate             | 6        | 11     | 18.75%  |
| WDC                 | 4        | 4      | 12.5%   |
| Intel               | 2        | 3      | 6.25%   |
| HGST                | 2        | 2      | 6.25%   |
| Unknown             | 1        | 1      | 3.13%   |
| Transcend           | 1        | 1      | 3.13%   |
| Toshiba             | 1        | 1      | 3.13%   |
| SK hynix            | 1        | 1      | 3.13%   |
| SanDisk             | 1        | 1      | 3.13%   |
| LITEON              | 1        | 1      | 3.13%   |
| Lexar               | 1        | 1      | 3.13%   |
| Kingmax             | 1        | 1      | 3.13%   |
| Hitachi             | 1        | 1      | 3.13%   |
| Crucial             | 1        | 4      | 3.13%   |
| A-DATA Technology   | 1        | 1      | 3.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung SSD 960 EVO 500GB             | 2        | 5.56%   |
| WDC WD800AAJS-00 80GB                 | 1        | 2.78%   |
| WDC WD20EZRZ-00Z 2TB                  | 1        | 2.78%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1        | 2.78%   |
| WDC WD10EZEX-21M2NA0 1TB              | 1        | 2.78%   |
| Unknown MMC Card  32GB                | 1        | 2.78%   |
| Transcend SSD 1GB                     | 1        | 2.78%   |
| Toshiba MK3252GS 320GB                | 1        | 2.78%   |
| SK hynix SC300 M.2 2280 256 256GB SSD | 1        | 2.78%   |
| Seagate ST4000VN008-2DR1 4TB          | 1        | 2.78%   |
| Seagate ST380815AS 80GB               | 1        | 2.78%   |
| Seagate ST3500418AS 500GB             | 1        | 2.78%   |
| Seagate ST2000DL001-9VT1 2TB          | 1        | 2.78%   |
| Seagate ST1000LM048-2E71 1TB          | 1        | 2.78%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 2.78%   |
| SanDisk SDSA6MM 16GB SSD              | 1        | 2.78%   |
| Samsung SSD 980 PRO 1TB               | 1        | 2.78%   |
| Samsung SSD 980 500GB                 | 1        | 2.78%   |
| Samsung SSD 970 EVO Plus 1TB          | 1        | 2.78%   |
| Samsung SSD 970 EVO 250GB             | 1        | 2.78%   |
| Samsung SSD 870 EVO 1TB               | 1        | 2.78%   |
| Samsung SSD 850 EVO 500GB             | 1        | 2.78%   |
| Samsung SSD 750 EVO 250GB             | 1        | 2.78%   |
| Samsung SP0411N 40GB                  | 1        | 2.78%   |
| LITEON CV3-CE128 128GB SSD            | 1        | 2.78%   |
| Lexar 256GB SSD                       | 1        | 2.78%   |
| Kingmax SSD 120G                      | 1        | 2.78%   |
| Intel SSDSC2BW24 240GB                | 1        | 2.78%   |
| Intel SSDSC2BW120A4 120GB             | 1        | 2.78%   |
| Intel SSDSC2BB24 240GB                | 1        | 2.78%   |
| Hitachi HDS72105 500GB                | 1        | 2.78%   |
| HGST HTS541010B7 1TB                  | 1        | 2.78%   |
| HGST HDN728080AL 8TB                  | 1        | 2.78%   |
| Crucial CT120BX500SSD1 120GB          | 1        | 2.78%   |
| A-DATA SU750 256GB SSD                | 1        | 2.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 11     | 40%     |
| WDC                 | 4        | 4      | 26.67%  |
| HGST                | 2        | 2      | 13.33%  |
| Toshiba             | 1        | 1      | 6.67%   |
| Samsung Electronics | 1        | 2      | 6.67%   |
| Hitachi             | 1        | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 5      | 23.08%  |
| Intel               | 2        | 3      | 15.38%  |
| Transcend           | 1        | 1      | 7.69%   |
| SK hynix            | 1        | 1      | 7.69%   |
| SanDisk             | 1        | 1      | 7.69%   |
| LITEON              | 1        | 1      | 7.69%   |
| Lexar               | 1        | 1      | 7.69%   |
| Kingmax             | 1        | 1      | 7.69%   |
| Crucial             | 1        | 4      | 7.69%   |
| A-DATA Technology   | 1        | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 12       | 19     | 40%     |
| HDD  | 12       | 21     | 40%     |
| NVMe | 5        | 6      | 16.67%  |
| MMC  | 1        | 1      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 19       | 38     | 73.08%  |
| NVMe | 5        | 6      | 19.23%  |
| SAS  | 1        | 2      | 3.85%   |
| MMC  | 1        | 1      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 17       | 25     | 70.83%  |
| 0.51-1.0   | 4        | 7      | 16.67%  |
| 3.01-4.0   | 1        | 4      | 4.17%   |
| 1.01-2.0   | 1        | 3      | 4.17%   |
| 4.01-10.0  | 1        | 1      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 28.57%  |
| 21-50      | 4        | 19.05%  |
| 1-20       | 4        | 19.05%  |
| 101-250    | 3        | 14.29%  |
| 2001-3000  | 2        | 9.52%   |
| 251-500    | 1        | 4.76%   |
| 1001-2000  | 1        | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 12       | 57.14%  |
| Unknown   | 6        | 28.57%  |
| 251-500   | 1        | 4.76%   |
| 1001-2000 | 1        | 4.76%   |
| 51-100    | 1        | 4.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Toshiba MK3252GS 320GB           | 1        | 1      | 25%     |
| SanDisk SDSA6MM 16GB SSD         | 1        | 1      | 25%     |
| Samsung Electronics SP0411N 40GB | 1        | 2      | 25%     |
| Kingmax SSD 120G                 | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 1        | 1      | 25%     |
| SanDisk             | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 2      | 25%     |
| Kingmax             | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 2      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 2        | 2      | 50%     |
| HDD  | 2        | 3      | 50%     |

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
| Works    | 17       | 39     | 73.91%  |
| Malfunc  | 4        | 5      | 17.39%  |
| Detected | 2        | 3      | 8.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 17       | 60.71%  |
| Samsung Electronics       | 4        | 14.29%  |
| Adaptec                   | 2        | 7.14%   |
| VIA Technologies          | 1        | 3.57%   |
| Nvidia                    | 1        | 3.57%   |
| LSI Logic / Symbios Logic | 1        | 3.57%   |
| ASMedia Technology        | 1        | 3.57%   |
| AMD                       | 1        | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 9.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 6.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 6.45%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 6.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 6.45%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 6.45%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 2        | 6.45%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1        | 3.23%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 3.23%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 3.23%   |
| Nvidia MCP61 IDE                                                               | 1        | 3.23%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1        | 3.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1        | 3.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 3.23%   |
| Intel 82Q35 Express PT IDER Controller                                         | 1        | 3.23%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 3.23%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 1        | 3.23%   |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                        | 1        | 3.23%   |
| Intel 5 Series/3400 Series Chipset SATA RAID Controller                        | 1        | 3.23%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 3.23%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1        | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 15       | 53.57%  |
| RAID | 4        | 14.29%  |
| NVMe | 4        | 14.29%  |
| IDE  | 4        | 14.29%  |
| SAS  | 1        | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 18       | 85.71%  |
| AMD    | 3        | 14.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i9-10900 CPU @ 2.80GHz       | 2        | 9.52%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2        | 9.52%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1        | 4.76%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz  | 1        | 4.76%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 1        | 4.76%   |
| Intel Core i5-4590T CPU @ 2.00GHz       | 1        | 4.76%   |
| Intel Core i5-3450 CPU @ 3.10GHz        | 1        | 4.76%   |
| Intel Core i3-4150 CPU @ 3.50GHz        | 1        | 4.76%   |
| Intel Core i3-3220T CPU @ 2.80GHz       | 1        | 4.76%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 1        | 4.76%   |
| Intel Celeron M processor 1.00GHz       | 1        | 4.76%   |
| Intel Celeron CPU J3455 @ 1.50GHz       | 1        | 4.76%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 1        | 4.76%   |
| Intel Celeron CPU J1800 @ 2.41GHz       | 1        | 4.76%   |
| Intel Celeron CPU G1850 @ 2.90GHz       | 1        | 4.76%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 1        | 4.76%   |
| AMD Sempron 145 Processor               | 1        | 4.76%   |
| AMD Mobile Duron processor              | 1        | 4.76%   |
| AMD A8-5500 APU with Radeon HD Graphics | 1        | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Celeron      | 4        | 19.05%  |
| Intel Core i5      | 3        | 14.29%  |
| Intel Core i3      | 3        | 14.29%  |
| Intel Core i9      | 2        | 9.52%   |
| Intel Core i7      | 2        | 9.52%   |
| Other              | 1        | 4.76%   |
| Intel Xeon         | 1        | 4.76%   |
| Intel Pentium Dual | 1        | 4.76%   |
| Intel Celeron M    | 1        | 4.76%   |
| Intel Atom         | 1        | 4.76%   |
| AMD Sempron        | 1        | 4.76%   |
| AMD A8             | 1        | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 42.86%  |
| 2      | 6        | 28.57%  |
| 1      | 3        | 14.29%  |
| 10     | 2        | 9.52%   |
| 6      | 1        | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 66.67%  |
| 2      | 7        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 10       | 47.62%  |
| 32-bit, 64-bit | 9        | 42.86%  |
| 32-bit         | 2        | 9.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 40.91%  |
| 0x306c3    | 3        | 13.64%  |
| 0x306a9    | 2        | 9.09%   |
| 0xa0655    | 1        | 4.55%   |
| 0x906ea    | 1        | 4.55%   |
| 0x6fd      | 1        | 4.55%   |
| 0x6d8      | 1        | 4.55%   |
| 0x506c9    | 1        | 4.55%   |
| 0x406c4    | 1        | 4.55%   |
| 0x106e5    | 1        | 4.55%   |
| 0x010000b6 | 1        | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 5        | 23.81%  |
| Silvermont  | 3        | 14.29%  |
| IvyBridge   | 2        | 9.52%   |
| CometLake   | 2        | 9.52%   |
| SandyBridge | 1        | 4.76%   |
| Piledriver  | 1        | 4.76%   |
| P6          | 1        | 4.76%   |
| Nehalem     | 1        | 4.76%   |
| KabyLake    | 1        | 4.76%   |
| K6          | 1        | 4.76%   |
| K10         | 1        | 4.76%   |
| Goldmont    | 1        | 4.76%   |
| Core        | 1        | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 15       | 68.18%  |
| AMD                        | 4        | 18.18%  |
| VIA Technologies           | 1        | 4.55%   |
| Nvidia                     | 1        | 4.55%   |
| Matrox Electronics Systems | 1        | 4.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 13.64%  |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 9.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 9.09%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1        | 4.55%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 4.55%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 4.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 4.55%   |
| Intel HD Graphics 500                                                                    | 1        | 4.55%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 4.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 4.55%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 4.55%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1        | 4.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 4.55%   |
| AMD Trinity [Radeon HD 7560D]                                                            | 1        | 4.55%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                                   | 1        | 4.55%   |
| AMD ES1000                                                                               | 1        | 4.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 4.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 14       | 66.67%  |
| 1 x AMD    | 4        | 19.05%  |
| 1 x VIA    | 1        | 4.76%   |
| 1 x Nvidia | 1        | 4.76%   |
| 1 x Matrox | 1        | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 17       | 80.95%  |
| Unknown | 4        | 19.05%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 76.19%  |
| 0.01-0.5   | 2        | 9.52%   |
| 7.01-8.0   | 1        | 4.76%   |
| 3.01-4.0   | 1        | 4.76%   |
| 1.01-2.0   | 1        | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 18.75%  |
| Dell                | 3        | 18.75%  |
| AOC                 | 3        | 18.75%  |
| BenQ                | 2        | 12.5%   |
| Acer                | 2        | 12.5%   |
| ViewSonic           | 1        | 6.25%   |
| Mi                  | 1        | 6.25%   |
| Goldstar            | 1        | 6.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch       | 2        | 11.76%  |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch               | 1        | 5.88%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch   | 1        | 5.88%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 1210x680mm 54.6-inch | 1        | 5.88%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                       | 1        | 5.88%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 1        | 5.88%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                      | 1        | 5.88%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                      | 1        | 5.88%   |
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                       | 1        | 5.88%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                     | 1        | 5.88%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                      | 1        | 5.88%   |
| AOC 718Swag-1 AOCC750 1440x900 367x230mm 17.1-inch                     | 1        | 5.88%   |
| AOC 2476WM AOC2476 1920x1080 521x293mm 23.5-inch                       | 1        | 5.88%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                       | 1        | 5.88%   |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                      | 1        | 5.88%   |
| Acer S236HL ACR0387 1920x1080 510x286mm 23.0-inch                      | 1        | 5.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 7        | 43.75%  |
| 3440x1440          | 2        | 12.5%   |
| 1680x1050 (WSXGA+) | 2        | 12.5%   |
| 1280x1024 (SXGA)   | 2        | 12.5%   |
| 3840x2160 (4K)     | 1        | 6.25%   |
| 2560x1440 (QHD)    | 1        | 6.25%   |
| 1440x900 (WXGA+)   | 1        | 6.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 23     | 3        | 17.65%  |
| 34     | 2        | 11.76%  |
| 27     | 2        | 11.76%  |
| 24     | 2        | 11.76%  |
| 21     | 2        | 11.76%  |
| 20     | 2        | 11.76%  |
| 17     | 2        | 11.76%  |
| 54     | 1        | 5.88%   |
| 19     | 1        | 5.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 7        | 41.18%  |
| 401-500     | 4        | 23.53%  |
| 701-800     | 2        | 11.76%  |
| 351-400     | 2        | 11.76%  |
| 301-350     | 1        | 5.88%   |
| 1001-1500   | 1        | 5.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 8        | 57.14%  |
| 5/4   | 2        | 14.29%  |
| 21/9  | 2        | 14.29%  |
| 16/10 | 2        | 14.29%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 35.29%  |
| 151-200        | 4        | 23.53%  |
| 351-500        | 2        | 11.76%  |
| 301-350        | 2        | 11.76%  |
| More than 1000 | 1        | 5.88%   |
| 141-150        | 1        | 5.88%   |
| 131-140        | 1        | 5.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 9        | 60%     |
| 1-50    | 3        | 20%     |
| 101-120 | 2        | 13.33%  |
| 161-240 | 1        | 6.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 57.14%  |
| 0     | 8        | 38.1%   |
| 4     | 1        | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 42.86%  |
| Intel                 | 5        | 17.86%  |
| Broadcom              | 3        | 10.71%  |
| Qualcomm Atheros      | 2        | 7.14%   |
| Xiaomi                | 1        | 3.57%   |
| VIA Technologies      | 1        | 3.57%   |
| T & A Mobile Phones   | 1        | 3.57%   |
| Qualcomm              | 1        | 3.57%   |
| Nvidia                | 1        | 3.57%   |
| D-Link System         | 1        | 3.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11       | 35.48%  |
| Intel Ethernet Controller I225-V                                  | 2        | 6.45%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2        | 6.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 3.23%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 3.23%   |
| T & A Mobile Phones A509DL                                        | 1        | 3.23%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 3.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 3.23%   |
| Qualcomm Redmi 9T                                                 | 1        | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 3.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 3.23%   |
| Nvidia MCP61 Ethernet                                             | 1        | 3.23%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 3.23%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 3.23%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 3.23%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 3.23%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 3.23%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 3.23%   |
| Broadcom BCM43227 802.11b/g/n                                     | 1        | 3.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 2        | 40%     |
| Realtek Semiconductor | 1        | 20%     |
| Qualcomm Atheros      | 1        | 20%     |
| Broadcom              | 1        | 20%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Comet Lake PCH CNVi WiFi                             | 2        | 40%     |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 20%     |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 20%     |
| Broadcom BCM43227 802.11b/g/n                              | 1        | 20%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 48%     |
| Intel                 | 5        | 20%     |
| Broadcom              | 2        | 8%      |
| Xiaomi                | 1        | 4%      |
| VIA Technologies      | 1        | 4%      |
| Qualcomm Atheros      | 1        | 4%      |
| Qualcomm              | 1        | 4%      |
| Nvidia                | 1        | 4%      |
| D-Link System         | 1        | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11       | 44%     |
| Intel Ethernet Controller I225-V                                  | 2        | 8%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 4%      |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 4%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 4%      |
| Qualcomm Redmi 9T                                                 | 1        | 4%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 4%      |
| Nvidia MCP61 Ethernet                                             | 1        | 4%      |
| Intel Ethernet Connection (7) I219-V                              | 1        | 4%      |
| Intel 82578DM Gigabit Network Connection                          | 1        | 4%      |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 4%      |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 4%      |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 4%      |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 76.92%  |
| WiFi     | 5        | 19.23%  |
| Unknown  | 1        | 3.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 18       | 85.71%  |
| WiFi     | 3        | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 57.14%  |
| 2     | 6        | 28.57%  |
| 5     | 1        | 4.76%   |
| 4     | 1        | 4.76%   |
| 3     | 1        | 4.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 90.48%  |
| Yes  | 2        | 9.52%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 50%     |
| IMC Networks            | 1        | 25%     |
| Cambridge Silicon Radio | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth Device                              | 2        | 50%     |
| IMC Networks Bluetooth Device                       | 1        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 15       | 71.43%  |
| AMD                                  | 3        | 14.29%  |
| VIA Technologies                     | 1        | 4.76%   |
| Thesycon Systemsoftware & Consulting | 1        | 4.76%   |
| Nvidia                               | 1        | 4.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 15.38%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 11.54%  |
| Intel Comet Lake PCH cAVS                                                  | 2        | 7.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 7.69%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 7.69%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 3.85%   |
| Thesycon Systemsoftware & Consulting E30                                   | 1        | 3.85%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 3.85%   |
| Intel USB PnP Sound Device                                                 | 1        | 3.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 3.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 3.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 3.85%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 3.85%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 3.85%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 3.85%   |
| AMD FCH Azalia Controller                                                  | 1        | 3.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 3.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 6        | 20.69%  |
| Unknown             | 5        | 17.24%  |
| SK hynix            | 5        | 17.24%  |
| Kingston            | 3        | 10.34%  |
| Elpida              | 2        | 6.9%    |
| Samsung Electronics | 1        | 3.45%   |
| Qimonda             | 1        | 3.45%   |
| Patriot             | 1        | 3.45%   |
| Micron Technology   | 1        | 3.45%   |
| Hewlett-Packard     | 1        | 3.45%   |
| Corsair             | 1        | 3.45%   |
| Cors                | 1        | 3.45%   |
| A-DATA Technology   | 1        | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s  | 2        | 6.25%   |
| Unknown RAM Module 512MB DIMM                             | 1        | 3.13%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 3.13%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s              | 1        | 3.13%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 1        | 3.13%   |
| Unknown RAM Module 128MB DIMM                             | 1        | 3.13%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 1        | 3.13%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 3.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s      | 1        | 3.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1        | 3.13%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 1        | 3.13%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 3.13%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1866MT/s    | 1        | 3.13%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s       | 1        | 3.13%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s          | 1        | 3.13%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s            | 1        | 3.13%   |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s       | 1        | 3.13%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s       | 1        | 3.13%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s       | 1        | 3.13%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 3.13%   |
| Kingston RAM 9905595-005.A00LF 2GB DIMM DDR3 1600MT/s     | 1        | 3.13%   |
| HP RAM Module 4GB DIMM DDR3 1600MT/s                      | 1        | 3.13%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s       | 1        | 3.13%   |
| Elpida RAM EBE10UE8ACWA-6E-E 1GB DIMM DDR2 667MT/s        | 1        | 3.13%   |
| Crucial RAM CT51264BF160B.C16F 4GB DIMM DDR3 1600MT/s     | 1        | 3.13%   |
| Crucial RAM CT25664BA160B.C16F 2GB DIMM DDR3 1600MT/s     | 1        | 3.13%   |
| Crucial RAM CT102464BA160B.M16 8GB DIMM DDR3 1600MT/s     | 1        | 3.13%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s    | 1        | 3.13%   |
| Corsair RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 3.13%   |
| Cors RAM CMX16GX3M2A1333C9 8192MB DIMM DDR3 1333MT/s      | 1        | 3.13%   |
| A-DATA RAM DDR4 2400 2OZ 4GB DIMM DDR4 2400MT/s           | 1        | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 15       | 68.18%  |
| DDR4    | 4        | 18.18%  |
| SDRAM   | 1        | 4.55%   |
| DDR2    | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 90.91%  |
| SODIMM | 2        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 9        | 36%     |
| 4096  | 6        | 24%     |
| 2048  | 4        | 16%     |
| 16384 | 2        | 8%      |
| 1024  | 2        | 8%      |
| 512   | 1        | 4%      |
| 128   | 1        | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 12       | 48%     |
| 3600    | 2        | 8%      |
| 2400    | 2        | 8%      |
| 1866    | 2        | 8%      |
| 1333    | 2        | 8%      |
| Unknown | 2        | 8%      |
| 2133    | 1        | 4%      |
| 1800    | 1        | 4%      |
| 667     | 1        | 4%      |

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
| Z-Star Microelectronics | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Z-Star A4 TECH USB2.0 PC Camera J | 1        | 100%    |

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
| 0     | 16       | 76.19%  |
| 1     | 4        | 19.05%  |
| 5     | 1        | 4.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 50%     |
| Sound                    | 1        | 12.5%   |
| Net/wireless             | 1        | 12.5%   |
| Net/ethernet             | 1        | 12.5%   |
| Communication controller | 1        | 12.5%   |

