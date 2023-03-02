Rocky Linux - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

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

Total: 66

| Vendor        | Model                   | Probe                                                      | Date         |
|---------------|-------------------------|------------------------------------------------------------|--------------|
| MSI           | B450M MORTAR TITANIUM   | [b27fb5e204](https://linux-hardware.org/?probe=b27fb5e204) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM   | [a2356a66ba](https://linux-hardware.org/?probe=a2356a66ba) | Feb 26, 2023 |
| Sapphire      | PE-AM2RS690V2           | [8aa6cda98e](https://linux-hardware.org/?probe=8aa6cda98e) | Feb 26, 2023 |
| ASUSTek       | PRIME B550-PLUS         | [feae434e9e](https://linux-hardware.org/?probe=feae434e9e) | Feb 18, 2023 |
| HP            | 1587h                   | [312effb7b7](https://linux-hardware.org/?probe=312effb7b7) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS         | [9de6fe5d90](https://linux-hardware.org/?probe=9de6fe5d90) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS         | [68463d6d4b](https://linux-hardware.org/?probe=68463d6d4b) | Feb 13, 2023 |
| MSI           | B450M MORTAR TITANIUM   | [7fec987264](https://linux-hardware.org/?probe=7fec987264) | Feb 12, 2023 |
| Dell          | 08HPGT A01              | [bf2c6ebd43](https://linux-hardware.org/?probe=bf2c6ebd43) | Feb 03, 2023 |
| ASUSTek       | PRIME B550-PLUS         | [bea57d418a](https://linux-hardware.org/?probe=bea57d418a) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS         | [23b27dab7d](https://linux-hardware.org/?probe=23b27dab7d) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS         | [989e45d84b](https://linux-hardware.org/?probe=989e45d84b) | Jan 31, 2023 |
| ASRock        | H610M-HDV/M.2           | [2936bb8fec](https://linux-hardware.org/?probe=2936bb8fec) | Jan 26, 2023 |
| Lenovo        | NOK                     | [507b602676](https://linux-hardware.org/?probe=507b602676) | Jan 25, 2023 |
| Dell          | 0Y2MRG A00              | [784e2db087](https://linux-hardware.org/?probe=784e2db087) | Jan 25, 2023 |
| MSI           | H510M PRO-E             | [c81f6adb11](https://linux-hardware.org/?probe=c81f6adb11) | Jan 20, 2023 |
| Unknown       | Unknown                 | [49d1097b37](https://linux-hardware.org/?probe=49d1097b37) | Jan 07, 2023 |
| Unknown       | Unknown                 | [2fbec34211](https://linux-hardware.org/?probe=2fbec34211) | Jan 07, 2023 |
| Dell          | 0VRWRC A00              | [2135b5161f](https://linux-hardware.org/?probe=2135b5161f) | Dec 28, 2022 |
| HP            | 805D                    | [cf88e571df](https://linux-hardware.org/?probe=cf88e571df) | Dec 28, 2022 |
| MSI           | B450M MORTAR TITANIUM   | [2a7ce79df8](https://linux-hardware.org/?probe=2a7ce79df8) | Dec 24, 2022 |
| ASUSTek       | X99-WS/IPMI             | [41f02987e9](https://linux-hardware.org/?probe=41f02987e9) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING | [b52b8b590b](https://linux-hardware.org/?probe=b52b8b590b) | Nov 30, 2022 |
| MSI           | PRO H610M-B DDR4        | [dc35eb3d09](https://linux-hardware.org/?probe=dc35eb3d09) | Nov 30, 2022 |
| ASUSTek       | PRIME H510M-E           | [86159f4ef3](https://linux-hardware.org/?probe=86159f4ef3) | Nov 20, 2022 |
| Intel         | D33217GKE G69901-202    | [f10d00e42a](https://linux-hardware.org/?probe=f10d00e42a) | Nov 12, 2022 |
| HP            | 8054                    | [08a9a98d04](https://linux-hardware.org/?probe=08a9a98d04) | Nov 10, 2022 |
| HP            | 8054                    | [4ce3ccc26d](https://linux-hardware.org/?probe=4ce3ccc26d) | Nov 09, 2022 |
| MSI           | X299 RAIDER             | [b7d117fc31](https://linux-hardware.org/?probe=b7d117fc31) | Nov 09, 2022 |
| ASUSTek       | Crosshair V Formula     | [c07ddbeb76](https://linux-hardware.org/?probe=c07ddbeb76) | Oct 31, 2022 |
| Gigabyte      | H81M-S2PV               | [23be2713d2](https://linux-hardware.org/?probe=23be2713d2) | Oct 24, 2022 |
| BESSTAR Te... | HM90                    | [fd411132f6](https://linux-hardware.org/?probe=fd411132f6) | Oct 15, 2022 |
| ASUSTek       | M5A97 R2.0              | [71970edbae](https://linux-hardware.org/?probe=71970edbae) | Oct 11, 2022 |
| ASUSTek       | PRIME H570-PLUS         | [71da92bd30](https://linux-hardware.org/?probe=71da92bd30) | Oct 04, 2022 |
| ASUSTek       | PRIME B550M-K           | [ff511df5c2](https://linux-hardware.org/?probe=ff511df5c2) | Sep 27, 2022 |
| ASUSTek       | P8B WS                  | [bd82f7708c](https://linux-hardware.org/?probe=bd82f7708c) | Sep 02, 2022 |
| Lenovo        | 1046 NO DPK             | [e21e07827d](https://linux-hardware.org/?probe=e21e07827d) | Aug 26, 2022 |
| ASUSTek       | PRIME B460M-A R2.0      | [e29f13e0b6](https://linux-hardware.org/?probe=e29f13e0b6) | Aug 19, 2022 |
| ASUSTek       | PRIME B365-PLUS         | [324410a493](https://linux-hardware.org/?probe=324410a493) | Aug 04, 2022 |
| Gigabyte      | 970A-UD3P               | [0d503b2789](https://linux-hardware.org/?probe=0d503b2789) | Jul 27, 2022 |
| Unknown       | X31_ICH7                | [f8ab18b666](https://linux-hardware.org/?probe=f8ab18b666) | Jun 07, 2022 |
| Dell          | 0GWHMW A01              | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| Dell          | 06CV2N A00              | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Gigabyte      | G41MT-USB3              | [10f3a0eaae](https://linux-hardware.org/?probe=10f3a0eaae) | Apr 21, 2022 |
| Gigabyte      | G41MT-USB3              | [4618c00b42](https://linux-hardware.org/?probe=4618c00b42) | Apr 17, 2022 |
| NCR           | Pocono BIOS.5.1         | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| Dell          | 0NK70N A03              | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| Dell          | 0WN7Y6 A01              | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| Dell          | 0PC5F7 A02              | [7c6c7dcd5e](https://linux-hardware.org/?probe=7c6c7dcd5e) | Feb 18, 2022 |
| ASUSTek       | PRIME B450-PLUS         | [1d3c449e8a](https://linux-hardware.org/?probe=1d3c449e8a) | Feb 18, 2022 |
| ASRock        | B450M Pro4              | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| MSI           | Z97A GAMING 6           | [4b935d705c](https://linux-hardware.org/?probe=4b935d705c) | Jan 20, 2022 |
| AZW           | Gemini M                | [25e63b737c](https://linux-hardware.org/?probe=25e63b737c) | Dec 31, 2021 |
| AZW           | Gemini M                | [05ef59842c](https://linux-hardware.org/?probe=05ef59842c) | Dec 31, 2021 |
| Google        | Panther                 | [92e2626936](https://linux-hardware.org/?probe=92e2626936) | Nov 30, 2021 |
| Gigabyte      | X570 AORUS ULTRA        | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Gigabyte      | H87-D3H-CF              | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| Dell          | 0N4YC8 A00              | [1a94195ddb](https://linux-hardware.org/?probe=1a94195ddb) | Oct 15, 2021 |
| ASUSTek       | PRIME B450M-A II        | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II        | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| ASUSTek       | P5Q DELUXE              | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Lenovo        | NOK                     | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Dell          | 0M5DCD A00              | [91acc7eb93](https://linux-hardware.org/?probe=91acc7eb93) | Aug 15, 2021 |
| ASUSTek       | PRIME TRX40-PRO S       | [59f7d599dd](https://linux-hardware.org/?probe=59f7d599dd) | Aug 04, 2021 |
| Dell          | 0M5DCD A00              | [77c3d7076e](https://linux-hardware.org/?probe=77c3d7076e) | Aug 04, 2021 |
| HP            | 0B54h D                 | [ee9a2da17c](https://linux-hardware.org/?probe=ee9a2da17c) | May 19, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Rocky Linux 8.5 | 12       | 23.08%  |
| Rocky Linux 9.1 | 11       | 21.15%  |
| Rocky Linux 8.4 | 9        | 17.31%  |
| Rocky Linux 8.6 | 8        | 15.38%  |
| Rocky Linux 9.0 | 7        | 13.46%  |
| Rocky Linux 8.7 | 4        | 7.69%   |
| Rocky Linux 8.3 | 1        | 1.92%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Rocky Linux | 51       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 6        | 11.32%  |
| 4.18.0-348.12.2.el8_5.x86_64     | 6        | 11.32%  |
| 5.14.0-70.30.1.el9_0.x86_64      | 3        | 5.66%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 3        | 5.66%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 3        | 5.66%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 2        | 3.77%   |
| 4.18.0-425.10.1.el8_7.x86_64     | 2        | 3.77%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 2        | 3.77%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2        | 3.77%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2        | 3.77%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 2        | 3.77%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2        | 3.77%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2        | 3.77%   |
| 6.1.8-1.el9.elrepo.x86_64        | 1        | 1.89%   |
| 6.1.6-1.el8.elrepo.x86_64        | 1        | 1.89%   |
| 6.0.10_tkg_bmq                   | 1        | 1.89%   |
| 6.0.10-1.el9.elrepo.x86_64       | 1        | 1.89%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1        | 1.89%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 1        | 1.89%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 1        | 1.89%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 1        | 1.89%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 1        | 1.89%   |
| 4.18.0-425.3.1.el8.x86_64        | 1        | 1.89%   |
| 4.18.0-425.13.1.el8_7.x86_64     | 1        | 1.89%   |
| 4.18.0-372.9.1.el8.x86_64        | 1        | 1.89%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 1        | 1.89%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 1        | 1.89%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 1        | 1.89%   |
| 4.18.0-240.22.1.el8.x86_64       | 1        | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 32       | 61.54%  |
| 5.14.0  | 15       | 28.85%  |
| 6.0.10  | 2        | 3.85%   |
| 6.1.8   | 1        | 1.92%   |
| 6.1.6   | 1        | 1.92%   |
| 5.14.1  | 1        | 1.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 32       | 61.54%  |
| 5.14    | 16       | 30.77%  |
| 6.1     | 2        | 3.85%   |
| 6.0     | 2        | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 51       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 30       | 58.82%  |
| Unknown       | 9        | 17.65%  |
| KDE5          | 6        | 11.76%  |
| GNOME Classic | 3        | 5.88%   |
| MATE          | 2        | 3.92%   |
| XFCE          | 1        | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 24       | 44.44%  |
| X11     | 22       | 40.74%  |
| Tty     | 3        | 5.56%   |
| Unknown | 3        | 5.56%   |
| Web     | 2        | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 47.06%  |
| GDM     | 21       | 41.18%  |
| SDDM    | 4        | 7.84%   |
| LightDM | 2        | 3.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 30       | 58.82%  |
| ru_RU | 4        | 7.84%   |
| en_IL | 3        | 5.88%   |
| en_SG | 2        | 3.92%   |
| en_CA | 2        | 3.92%   |
| en_AU | 2        | 3.92%   |
| C     | 2        | 3.92%   |
| pl_PL | 1        | 1.96%   |
| ko_KR | 1        | 1.96%   |
| ja_JP | 1        | 1.96%   |
| es_CO | 1        | 1.96%   |
| es_AR | 1        | 1.96%   |
| af_ZA | 1        | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 27       | 51.92%  |
| BIOS | 25       | 48.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 42       | 82.35%  |
| Ext4 | 9        | 17.65%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 26       | 50.98%  |
| Unknown | 14       | 27.45%  |
| MBR     | 11       | 21.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 80.39%  |
| Yes       | 10       | 19.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 90.2%   |
| Yes       | 5        | 9.8%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 15       | 29.41%  |
| Dell                | 10       | 19.61%  |
| MSI                 | 5        | 9.8%    |
| Gigabyte Technology | 5        | 9.8%    |
| Hewlett-Packard     | 4        | 7.84%   |
| Lenovo              | 2        | 3.92%   |
| ASRock              | 2        | 3.92%   |
| Unknown             | 2        | 3.92%   |
| Sapphire            | 1        | 1.96%   |
| NCR                 | 1        | 1.96%   |
| Intel               | 1        | 1.96%   |
| Google              | 1        | 1.96%   |
| BESSTAR Tech        | 1        | 1.96%   |
| AZW                 | 1        | 1.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell OptiPlex 9020                  | 2        | 3.92%   |
| Unknown                             | 2        | 3.92%   |
| Sapphire PE-AM2RS690V2              | 1        | 1.96%   |
| NCR xxxx-xxxx-xxxx                  | 1        | 1.96%   |
| MSI MS-7D46                         | 1        | 1.96%   |
| MSI MS-7B89                         | 1        | 1.96%   |
| MSI MS-7A94                         | 1        | 1.96%   |
| MSI MS-7917                         | 1        | 1.96%   |
| MSI H510M PRO-E                     | 1        | 1.96%   |
| Lenovo ThinkStation P620 30E0S0PR00 | 1        | 1.96%   |
| Lenovo ThinkCentre M72e 36601Y8     | 1        | 1.96%   |
| Intel PRO412081                     | 1        | 1.96%   |
| HP Z600 Workstation                 | 1        | 1.96%   |
| HP Z210 Workstation                 | 1        | 1.96%   |
| HP ProDesk 600 G2 SFF               | 1        | 1.96%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.96%   |
| Google Panther                      | 1        | 1.96%   |
| Gigabyte X570 AORUS ULTRA           | 1        | 1.96%   |
| Gigabyte H87-D3H                    | 1        | 1.96%   |
| Gigabyte H81M-S2PV                  | 1        | 1.96%   |
| Gigabyte G41MT-USB3                 | 1        | 1.96%   |
| Gigabyte 970A-UD3P                  | 1        | 1.96%   |
| Dell XPS 8300                       | 1        | 1.96%   |
| Dell Vostro 3681                    | 1        | 1.96%   |
| Dell Precision Tower 7810           | 1        | 1.96%   |
| Dell Precision T7610                | 1        | 1.96%   |
| Dell Precision T5610                | 1        | 1.96%   |
| Dell Precision T3600                | 1        | 1.96%   |
| Dell OptiPlex 390                   | 1        | 1.96%   |
| Dell OptiPlex 3020M                 | 1        | 1.96%   |
| BESSTAR Tech HM90                   | 1        | 1.96%   |
| AZW Gemini M                        | 1        | 1.96%   |
| ASUS ROG STRIX X470-F GAMING        | 1        | 1.96%   |
| ASUS PRIME TRX40-PRO S              | 1        | 1.96%   |
| ASUS PRIME H570-PLUS                | 1        | 1.96%   |
| ASUS PRIME H510M-E                  | 1        | 1.96%   |
| ASUS PRIME B550M-K                  | 1        | 1.96%   |
| ASUS PRIME B550-PLUS                | 1        | 1.96%   |
| ASUS PRIME B460M-A R2.0             | 1        | 1.96%   |
| ASUS PRIME B450M-A II               | 1        | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 9        | 17.65%  |
| Dell Precision         | 4        | 7.84%   |
| Dell OptiPlex          | 4        | 7.84%   |
| Unknown                | 2        | 3.92%   |
| Sapphire PE-AM2RS690V2 | 1        | 1.96%   |
| NCR xxxx-xxxx-xxxx     | 1        | 1.96%   |
| MSI MS-7D46            | 1        | 1.96%   |
| MSI MS-7B89            | 1        | 1.96%   |
| MSI MS-7A94            | 1        | 1.96%   |
| MSI MS-7917            | 1        | 1.96%   |
| MSI H510M              | 1        | 1.96%   |
| Lenovo ThinkStation    | 1        | 1.96%   |
| Lenovo ThinkCentre     | 1        | 1.96%   |
| Intel PRO412081        | 1        | 1.96%   |
| HP Z600                | 1        | 1.96%   |
| HP Z210                | 1        | 1.96%   |
| HP ProDesk             | 1        | 1.96%   |
| HP EliteDesk           | 1        | 1.96%   |
| Google Panther         | 1        | 1.96%   |
| Gigabyte X570          | 1        | 1.96%   |
| Gigabyte H87-D3H       | 1        | 1.96%   |
| Gigabyte H81M-S2PV     | 1        | 1.96%   |
| Gigabyte G41MT-USB3    | 1        | 1.96%   |
| Gigabyte 970A-UD3P     | 1        | 1.96%   |
| Dell XPS               | 1        | 1.96%   |
| Dell Vostro            | 1        | 1.96%   |
| BESSTAR Tech HM90      | 1        | 1.96%   |
| AZW Gemini             | 1        | 1.96%   |
| ASUS ROG               | 1        | 1.96%   |
| ASUS P8B               | 1        | 1.96%   |
| ASUS P5Q               | 1        | 1.96%   |
| ASUS ORION             | 1        | 1.96%   |
| ASUS M5A97             | 1        | 1.96%   |
| ASUS Crosshair         | 1        | 1.96%   |
| ASRock H610M-HDV       | 1        | 1.96%   |
| ASRock B450M           | 1        | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 7        | 13.73%  |
| 2020 | 6        | 11.76%  |
| 2011 | 6        | 11.76%  |
| 2018 | 5        | 9.8%    |
| 2015 | 5        | 9.8%    |
| 2013 | 5        | 9.8%    |
| 2014 | 4        | 7.84%   |
| 2019 | 3        | 5.88%   |
| 2012 | 3        | 5.88%   |
| 2008 | 3        | 5.88%   |
| 2022 | 2        | 3.92%   |
| 2017 | 1        | 1.96%   |
| 2010 | 1        | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 51       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 48       | 94.12%  |
| Enabled  | 3        | 5.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 50       | 98.04%  |
| Yes  | 1        | 1.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 13       | 25.49%  |
| 16.01-24.0  | 9        | 17.65%  |
| 8.01-16.0   | 9        | 17.65%  |
| 4.01-8.0    | 7        | 13.73%  |
| 64.01-256.0 | 5        | 9.8%    |
| 3.01-4.0    | 3        | 5.88%   |
| 1.01-2.0    | 3        | 5.88%   |
| 24.01-32.0  | 1        | 1.96%   |
| 2.01-3.0    | 1        | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 17       | 32.69%  |
| 4.01-8.0   | 11       | 21.15%  |
| 3.01-4.0   | 10       | 19.23%  |
| 1.01-2.0   | 6        | 11.54%  |
| 0.51-1.0   | 3        | 5.77%   |
| 8.01-16.0  | 2        | 3.85%   |
| 0.01-0.5   | 2        | 3.85%   |
| 16.01-24.0 | 1        | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 48.08%  |
| 2      | 10       | 19.23%  |
| 3      | 7        | 13.46%  |
| 4      | 5        | 9.62%   |
| 5      | 2        | 3.85%   |
| 9      | 1        | 1.92%   |
| 8      | 1        | 1.92%   |
| 6      | 1        | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 56.86%  |
| Yes       | 22       | 43.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 50       | 98.04%  |
| No        | 1        | 1.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 67.31%  |
| Yes       | 17       | 32.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 76.47%  |
| Yes       | 12       | 23.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 12       | 23.53%  |
| Russia       | 4        | 7.84%   |
| Canada       | 4        | 7.84%   |
| Singapore    | 3        | 5.88%   |
| Israel       | 3        | 5.88%   |
| Australia    | 3        | 5.88%   |
| South Korea  | 2        | 3.92%   |
| Italy        | 2        | 3.92%   |
| Indonesia    | 2        | 3.92%   |
| Germany      | 2        | 3.92%   |
| Sweden       | 1        | 1.96%   |
| South Africa | 1        | 1.96%   |
| Portugal     | 1        | 1.96%   |
| Poland       | 1        | 1.96%   |
| Norway       | 1        | 1.96%   |
| Netherlands  | 1        | 1.96%   |
| Mexico       | 1        | 1.96%   |
| Japan        | 1        | 1.96%   |
| India        | 1        | 1.96%   |
| France       | 1        | 1.96%   |
| Finland      | 1        | 1.96%   |
| Czechia      | 1        | 1.96%   |
| Colombia     | 1        | 1.96%   |
| Argentina    | 1        | 1.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Singapore              | 3        | 5.88%   |
| Haifa                  | 2        | 3.92%   |
| Yogyakarta             | 1        | 1.96%   |
| Woodridge              | 1        | 1.96%   |
| Wells                  | 1        | 1.96%   |
| Waltham                | 1        | 1.96%   |
| Voronezh               | 1        | 1.96%   |
| Vancouver              | 1        | 1.96%   |
| Toronto                | 1        | 1.96%   |
| Tlaxcala City          | 1        | 1.96%   |
| St. John's             | 1        | 1.96%   |
| St Petersburg          | 1        | 1.96%   |
| Sobral de Monte Agraco | 1        | 1.96%   |
| Semarang               | 1        | 1.96%   |
| Rotterdam              | 1        | 1.96%   |
| Rehovot                | 1        | 1.96%   |
| Prague                 | 1        | 1.96%   |
| Paris                  | 1        | 1.96%   |
| Ōtsu                  | 1        | 1.96%   |
| Oslo                   | 1        | 1.96%   |
| Moscow                 | 1        | 1.96%   |
| Monza                  | 1        | 1.96%   |
| Milan                  | 1        | 1.96%   |
| Mequon                 | 1        | 1.96%   |
| Melbourne              | 1        | 1.96%   |
| Lebanon                | 1        | 1.96%   |
| Krasnodar              | 1        | 1.96%   |
| Krakow                 | 1        | 1.96%   |
| Imphal                 | 1        | 1.96%   |
| Helsinki               | 1        | 1.96%   |
| Giessen                | 1        | 1.96%   |
| Fredericksburg         | 1        | 1.96%   |
| Florence               | 1        | 1.96%   |
| Fairfax                | 1        | 1.96%   |
| Enebyberg              | 1        | 1.96%   |
| Corvallis              | 1        | 1.96%   |
| Chicago                | 1        | 1.96%   |
| Centurion              | 1        | 1.96%   |
| Calchaqui              | 1        | 1.96%   |
| Burlington             | 1        | 1.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 17       | 33     | 20.48%  |
| WDC                         | 15       | 29     | 18.07%  |
| Samsung Electronics         | 12       | 22     | 14.46%  |
| Toshiba                     | 7        | 8      | 8.43%   |
| Hitachi                     | 6        | 7      | 7.23%   |
| Intel                       | 3        | 3      | 3.61%   |
| Crucial                     | 3        | 3      | 3.61%   |
| SanDisk                     | 2        | 2      | 2.41%   |
| Kingston                    | 2        | 2      | 2.41%   |
| HGST                        | 2        | 2      | 2.41%   |
| Team                        | 1        | 1      | 1.2%    |
| SK hynix                    | 1        | 1      | 1.2%    |
| PNY                         | 1        | 1      | 1.2%    |
| Phison                      | 1        | 1      | 1.2%    |
| MyDigitalSSD                | 1        | 1      | 1.2%    |
| MAXIO Technology (Hangzhou) | 1        | 1      | 1.2%    |
| Kingston Technology Company | 1        | 1      | 1.2%    |
| Gigabyte Technology         | 1        | 1      | 1.2%    |
| Digma                       | 1        | 1      | 1.2%    |
| Corsair                     | 1        | 1      | 1.2%    |
| China                       | 1        | 1      | 1.2%    |
| Apacer                      | 1        | 1      | 1.2%    |
| ADATA SU                    | 1        | 1      | 1.2%    |
| A-DATA Technology           | 1        | 1      | 1.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 3        | 3.03%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 2.02%   |
| Samsung SSD 860 EVO 1TB          | 2        | 2.02%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD | 1        | 1.01%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD | 1        | 1.01%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 1.01%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 1.01%   |
| WDC WDS100T1X0E-00AFY0 1TB       | 1        | 1.01%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD   | 1        | 1.01%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 1        | 1.01%   |
| WDC WD5000AUDX-63WNHY0 500GB     | 1        | 1.01%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 1.01%   |
| WDC WD5000AAKX-001CA0 500GB      | 1        | 1.01%   |
| WDC WD30EZRX-00D8PB0 3TB         | 1        | 1.01%   |
| WDC WD2500AAJS-22VTA0 250GB      | 1        | 1.01%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 1.01%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1        | 1.01%   |
| WDC WD20EZBX-00AYRA0 2TB         | 1        | 1.01%   |
| WDC WD20EFZX-68AWUN0 2TB         | 1        | 1.01%   |
| WDC WD2002FAEX-007BA0 2TB        | 1        | 1.01%   |
| WDC WD10EZEX-75M2NA0 1TB         | 1        | 1.01%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 1.01%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1        | 1.01%   |
| WDC WD1001FALS-00J7B1 1TB        | 1        | 1.01%   |
| WDC WD1001FALS-00J7B0 1TB        | 1        | 1.01%   |
| Toshiba THNSNJ128GCSU 128GB SSD  | 1        | 1.01%   |
| Toshiba MQ01ABD100 1TB           | 1        | 1.01%   |
| Toshiba MK1059GSM 1TB            | 1        | 1.01%   |
| Toshiba MG07ACA12TE 12TB         | 1        | 1.01%   |
| Toshiba MG04ACA400E 4TB          | 1        | 1.01%   |
| Toshiba DT01ACA100 1TB           | 1        | 1.01%   |
| Toshiba DT01ACA050 500GB         | 1        | 1.01%   |
| Team L5 LITE SSD 240GB           | 1        | 1.01%   |
| SK hynix SH920 2.5 7MM 256GB SSD | 1        | 1.01%   |
| Seagate ST9500420AS 500GB        | 1        | 1.01%   |
| Seagate ST9500325AS 500GB        | 1        | 1.01%   |
| Seagate ST9320325AS 320GB        | 1        | 1.01%   |
| Seagate ST4000VN008-2DR166 4TB   | 1        | 1.01%   |
| Seagate ST4000VN006-3CW104 4TB   | 1        | 1.01%   |
| Seagate ST4000DM004-2CV104 4TB   | 1        | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 33     | 37.78%  |
| WDC                 | 12       | 21     | 26.67%  |
| Toshiba             | 6        | 7      | 13.33%  |
| Hitachi             | 6        | 7      | 13.33%  |
| Samsung Electronics | 2        | 3      | 4.44%   |
| HGST                | 2        | 2      | 4.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 8      | 20%     |
| WDC                 | 4        | 7      | 16%     |
| SanDisk             | 2        | 2      | 8%      |
| Crucial             | 2        | 2      | 8%      |
| Toshiba             | 1        | 1      | 4%      |
| Team                | 1        | 1      | 4%      |
| SK hynix            | 1        | 1      | 4%      |
| PNY                 | 1        | 1      | 4%      |
| MyDigitalSSD        | 1        | 1      | 4%      |
| Kingston            | 1        | 1      | 4%      |
| Intel               | 1        | 1      | 4%      |
| Gigabyte Technology | 1        | 1      | 4%      |
| Corsair             | 1        | 1      | 4%      |
| China               | 1        | 1      | 4%      |
| Apacer              | 1        | 1      | 4%      |
| ADATA SU            | 1        | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 32       | 73     | 45.07%  |
| SSD     | 23       | 31     | 32.39%  |
| NVMe    | 15       | 20     | 21.13%  |
| Unknown | 1        | 1      | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 45       | 103    | 72.58%  |
| NVMe | 15       | 20     | 24.19%  |
| SAS  | 2        | 2      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 29       | 48     | 48.33%  |
| 0.51-1.0   | 18       | 32     | 30%     |
| 1.01-2.0   | 7        | 10     | 11.67%  |
| 3.01-4.0   | 4        | 12     | 6.67%   |
| 2.01-3.0   | 1        | 1      | 1.67%   |
| 10.01-20.0 | 1        | 1      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 25%     |
| 501-1000       | 12       | 23.08%  |
| 1001-2000      | 9        | 17.31%  |
| 251-500        | 7        | 13.46%  |
| More than 3000 | 4        | 7.69%   |
| 2001-3000      | 3        | 5.77%   |
| 51-100         | 2        | 3.85%   |
| 1-20           | 1        | 1.92%   |
| Unknown        | 1        | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 17       | 32.08%  |
| 21-50          | 11       | 20.75%  |
| 51-100         | 8        | 15.09%  |
| 501-1000       | 6        | 11.32%  |
| 251-500        | 4        | 7.55%   |
| More than 3000 | 3        | 5.66%   |
| 101-250        | 2        | 3.77%   |
| 1001-2000      | 1        | 1.89%   |
| Unknown        | 1        | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD1001FALS-00J7B1 1TB     | 1        | 2      | 10%     |
| WDC WD1001FALS-00J7B0 1TB     | 1        | 4      | 10%     |
| Toshiba MK1059GSM 1TB         | 1        | 1      | 10%     |
| Seagate ST9500325AS 500GB     | 1        | 1      | 10%     |
| Seagate ST9320325AS 320GB     | 1        | 1      | 10%     |
| Seagate ST31000528AS 1TB      | 1        | 1      | 10%     |
| Hitachi HTS727575A9E364 752GB | 1        | 1      | 10%     |
| Hitachi HDS725050KLA360 500GB | 1        | 1      | 10%     |
| Hitachi HDS721010CLA632 1TB   | 1        | 1      | 10%     |
| Corsair Neutron SSD 64GB      | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 30%     |
| Hitachi | 3        | 3      | 30%     |
| WDC     | 2        | 6      | 20%     |
| Toshiba | 1        | 1      | 10%     |
| Corsair | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 33.33%  |
| Hitachi | 3        | 3      | 33.33%  |
| WDC     | 2        | 6      | 22.22%  |
| Toshiba | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 13     | 87.5%   |
| SSD  | 1        | 1      | 12.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST9500420AS 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 35       | 80     | 58.33%  |
| Detected | 16       | 30     | 26.67%  |
| Malfunc  | 8        | 14     | 13.33%  |
| Failed   | 1        | 1      | 1.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 35       | 48.61%  |
| AMD                         | 16       | 22.22%  |
| Samsung Electronics         | 6        | 8.33%   |
| Kingston Technology Company | 2        | 2.78%   |
| Broadcom / LSI              | 2        | 2.78%   |
| ASMedia Technology          | 2        | 2.78%   |
| VIA Technologies            | 1        | 1.39%   |
| SanDisk                     | 1        | 1.39%   |
| Realtek Semiconductor       | 1        | 1.39%   |
| Phison Electronics          | 1        | 1.39%   |
| Micron/Crucial Technology   | 1        | 1.39%   |
| MAXIO Technology (Hangzhou) | 1        | 1.39%   |
| Marvell Technology Group    | 1        | 1.39%   |
| JMicron Technology          | 1        | 1.39%   |
| Adaptec                     | 1        | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 9.09%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 6.82%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 5.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 3.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 3.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 3.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 2.27%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 2.27%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.27%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 2.27%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.27%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.27%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 1.14%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 1.14%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.14%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 1.14%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.14%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.14%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1        | 1.14%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 1.14%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 1.14%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 1.14%   |
| JMicron JMB58x AHCI SATA controller                                                     | 1        | 1.14%   |
| Intel PCIe Data Center SSD                                                              | 1        | 1.14%   |
| Intel Non-Volatile memory controller                                                    | 1        | 1.14%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.14%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1        | 1.14%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.14%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.14%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 1.14%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 1.14%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 38       | 50.67%  |
| NVMe | 15       | 20%     |
| RAID | 9        | 12%     |
| IDE  | 9        | 12%     |
| SAS  | 3        | 4%      |
| SCSI | 1        | 1.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 35       | 68.63%  |
| AMD    | 16       | 31.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 3.92%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 2        | 3.92%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz         | 2        | 3.92%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1        | 1.96%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz           | 1        | 1.96%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 1.96%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz            | 1        | 1.96%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz             | 1        | 1.96%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1        | 1.96%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz         | 1        | 1.96%   |
| Intel Core i9-7920X CPU @ 2.90GHz              | 1        | 1.96%   |
| Intel Core i7-6950X CPU @ 3.00GHz              | 1        | 1.96%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 1        | 1.96%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 1.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.96%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 1.96%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 1.96%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 1.96%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1        | 1.96%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 1.96%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 1.96%   |
| Intel Core i5-10600KF CPU @ 4.10GHz            | 1        | 1.96%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 1        | 1.96%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 1.96%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 1        | 1.96%   |
| Intel Core i3-3217U CPU @ 1.80GHz              | 1        | 1.96%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 1.96%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1        | 1.96%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1        | 1.96%   |
| Intel Celeron 2955U @ 1.40GHz                  | 1        | 1.96%   |
| Intel 12th Gen Core i5-12400F                  | 1        | 1.96%   |
| Intel 12th Gen Core i5-12400                   | 1        | 1.96%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores     | 1        | 1.96%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 1.96%   |
| AMD Ryzen Embedded V1500B                      | 1        | 1.96%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 1.96%   |
| AMD Ryzen 9 4900H with Radeon Graphics         | 1        | 1.96%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics     | 1        | 1.96%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 1.96%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 10       | 19.61%  |
| Intel Core i5           | 6        | 11.76%  |
| Other                   | 5        | 9.8%    |
| Intel Xeon              | 5        | 9.8%    |
| Intel Core i3           | 4        | 7.84%   |
| AMD Ryzen 7             | 3        | 5.88%   |
| Intel Celeron           | 2        | 3.92%   |
| AMD Ryzen Threadripper  | 2        | 3.92%   |
| AMD Ryzen 9             | 2        | 3.92%   |
| AMD Ryzen 5             | 2        | 3.92%   |
| AMD FX                  | 2        | 3.92%   |
| Intel Pentium Dual-Core | 1        | 1.96%   |
| Intel Pentium Dual      | 1        | 1.96%   |
| Intel Core i9           | 1        | 1.96%   |
| Intel Core 2 Quad       | 1        | 1.96%   |
| AMD Ryzen Embedded      | 1        | 1.96%   |
| AMD Ryzen 7 PRO         | 1        | 1.96%   |
| AMD Ryzen 3             | 1        | 1.96%   |
| AMD Phenom II X6        | 1        | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 17       | 33.33%  |
| 6      | 10       | 19.61%  |
| 8      | 9        | 17.65%  |
| 2      | 8        | 15.69%  |
| 12     | 3        | 5.88%   |
| 24     | 1        | 1.96%   |
| 16     | 1        | 1.96%   |
| 10     | 1        | 1.96%   |
| 3      | 1        | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 96.08%  |
| 2      | 2        | 3.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 36       | 70.59%  |
| 1      | 15       | 29.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 51       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 5        | 9.8%    |
| 0x206a7    | 4        | 7.84%   |
| 0x306a9    | 3        | 5.88%   |
| 0xa0671    | 2        | 3.92%   |
| 0xa0655    | 2        | 3.92%   |
| 0x506e3    | 2        | 3.92%   |
| 0x306e4    | 2        | 3.92%   |
| 0x08600106 | 2        | 3.92%   |
| 0x06000852 | 2        | 3.92%   |
| Unknown    | 2        | 3.92%   |
| 0xa0653    | 1        | 1.96%   |
| 0x906ed    | 1        | 1.96%   |
| 0x90675    | 1        | 1.96%   |
| 0x90672    | 1        | 1.96%   |
| 0x706a8    | 1        | 1.96%   |
| 0x6fd      | 1        | 1.96%   |
| 0x50654    | 1        | 1.96%   |
| 0x406f1    | 1        | 1.96%   |
| 0x40651    | 1        | 1.96%   |
| 0x306f2    | 1        | 1.96%   |
| 0x206c2    | 1        | 1.96%   |
| 0x10677    | 1        | 1.96%   |
| 0x10676    | 1        | 1.96%   |
| 0x0a20120a | 1        | 1.96%   |
| 0x0a201016 | 1        | 1.96%   |
| 0x0a201009 | 1        | 1.96%   |
| 0x0870100a | 1        | 1.96%   |
| 0x0830104d | 1        | 1.96%   |
| 0x08301039 | 1        | 1.96%   |
| 0x08108109 | 1        | 1.96%   |
| 0x08101016 | 1        | 1.96%   |
| 0x0800820d | 1        | 1.96%   |
| 0x08001138 | 1        | 1.96%   |
| 0x010000dc | 1        | 1.96%   |
| 0x010000c7 | 1        | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 8        | 15.69%  |
| Zen 2            | 5        | 9.8%    |
| SandyBridge      | 5        | 9.8%    |
| IvyBridge        | 5        | 9.8%    |
| Zen 3            | 3        | 5.88%   |
| Skylake          | 3        | 5.88%   |
| CometLake        | 3        | 5.88%   |
| Zen+             | 2        | 3.92%   |
| Zen              | 2        | 3.92%   |
| Piledriver       | 2        | 3.92%   |
| Penryn           | 2        | 3.92%   |
| K10              | 2        | 3.92%   |
| Icelake          | 2        | 3.92%   |
| Alderlake Hybrid | 2        | 3.92%   |
| Westmere         | 1        | 1.96%   |
| KabyLake         | 1        | 1.96%   |
| Goldmont plus    | 1        | 1.96%   |
| Core             | 1        | 1.96%   |
| Broadwell        | 1        | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 23       | 41.82%  |
| Intel             | 21       | 38.18%  |
| AMD               | 10       | 18.18%  |
| ASPEED Technology | 1        | 1.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 5.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 5.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 5.36%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2        | 3.57%   |
| Intel HD Graphics 530                                                       | 2        | 3.57%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 3.57%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2        | 3.57%   |
| AMD Renoir                                                                  | 2        | 3.57%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 3.57%   |
| Nvidia TU117GL [T600]                                                       | 1        | 1.79%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.79%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.79%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.79%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 1.79%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.79%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.79%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.79%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.79%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 1.79%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 1.79%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 1.79%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 1.79%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.79%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 1.79%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 1.79%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.79%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.79%   |
| Nvidia GA102GL [RTX A6000]                                                  | 1        | 1.79%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.79%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.79%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 1.79%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.79%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.79%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 1.79%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.79%   |
| AMD RS690 [Radeon X1200]                                                    | 1        | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 19       | 37.25%  |
| 1 x Intel       | 19       | 37.25%  |
| 1 x AMD         | 9        | 17.65%  |
| Intel + Nvidia  | 2        | 3.92%   |
| 2 x AMD         | 1        | 1.96%   |
| Nvidia + ASPEED | 1        | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 39       | 76.47%  |
| Proprietary | 9        | 17.65%  |
| Unknown     | 3        | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 45.1%   |
| 1.01-2.0   | 9        | 17.65%  |
| 0.01-0.5   | 7        | 13.73%  |
| 0.51-1.0   | 5        | 9.8%    |
| 7.01-8.0   | 2        | 3.92%   |
| 8.01-16.0  | 2        | 3.92%   |
| 32.01-64.0 | 1        | 1.96%   |
| 5.01-6.0   | 1        | 1.96%   |
| 3.01-4.0   | 1        | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 7        | 14.89%  |
| Samsung Electronics  | 6        | 12.77%  |
| Acer                 | 6        | 12.77%  |
| Ancor Communications | 4        | 8.51%   |
| Philips              | 3        | 6.38%   |
| Iiyama               | 3        | 6.38%   |
| Hewlett-Packard      | 3        | 6.38%   |
| Goldstar             | 3        | 6.38%   |
| ViewSonic            | 2        | 4.26%   |
| Sony                 | 1        | 2.13%   |
| SGT                  | 1        | 2.13%   |
| OEM                  | 1        | 2.13%   |
| NEC Computers        | 1        | 2.13%   |
| HUAWEI               | 1        | 2.13%   |
| HCL                  | 1        | 2.13%   |
| Eizo                 | 1        | 2.13%   |
| BenQ                 | 1        | 2.13%   |
| ASUSTek Computer     | 1        | 2.13%   |
| AOC                  | 1        | 2.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch           | 1        | 2.04%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch               | 1        | 2.04%   |
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                   | 1        | 2.04%   |
| SGT HS156PC SGT1560 1920x1080 345x194mm 15.6-inch                    | 1        | 2.04%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch    | 1        | 2.04%   |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch | 1        | 2.04%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch    | 1        | 2.04%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch  | 1        | 2.04%   |
| Samsung Electronics LC32G5xT SAM7080 2560x1440 698x393mm 31.5-inch   | 1        | 2.04%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch   | 1        | 2.04%   |
| Philips PHL 275E2F PHLC23A 2560x1440 597x336mm 27.0-inch             | 1        | 2.04%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 1        | 2.04%   |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch            | 1        | 2.04%   |
| OEM 22W_LCD_TV OEM3700 1920x1080                                     | 1        | 2.04%   |
| NEC Computers LCD1760NX NEC6604 1280x1024 338x270mm 17.0-inch        | 1        | 2.04%   |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                 | 1        | 2.04%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                 | 1        | 2.04%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                  | 1        | 2.04%   |
| HUAWEI SSN-24 HWV6E4E 1920x1080 527x296mm 23.8-inch                  | 1        | 2.04%   |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch         | 1        | 2.04%   |
| Hewlett-Packard E190i HWP3118 1280x1024 374x299mm 18.9-inch          | 1        | 2.04%   |
| Hewlett-Packard 2509 HWP283B 1920x1080 553x311mm 25.0-inch           | 1        | 2.04%   |
| HCL HCMELWBN11 HCME444 1366x768 410x230mm 18.5-inch                  | 1        | 2.04%   |
| Goldstar WFHD GSM7748 2560x1080 798x334mm 34.1-inch                  | 1        | 2.04%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch             | 1        | 2.04%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch             | 1        | 2.04%   |
| Goldstar Ultra HD GSM5B08 3780x2160 600x340mm 27.2-inch              | 1        | 2.04%   |
| Eizo CG247X ENC2801 1920x1200 520x330mm 24.2-inch                    | 1        | 2.04%   |
| Dell P2416D DELA0C4 2560x1440 527x296mm 23.8-inch                    | 1        | 2.04%   |
| Dell P2014H DEL4096 1600x900 434x236mm 19.4-inch                     | 1        | 2.04%   |
| Dell P1913 DELA088 1440x900 408x255mm 18.9-inch                      | 1        | 2.04%   |
| Dell LCD Monitor U2414H 3840x1080                                    | 1        | 2.04%   |
| Dell LCD Monitor U2414H                                              | 1        | 2.04%   |
| Dell IN2030M DELF03C 1600x900 443x249mm 20.0-inch                    | 1        | 2.04%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                    | 1        | 2.04%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                    | 1        | 2.04%   |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                    | 1        | 2.04%   |
| ASUSTek Computer VP247 AUS24DA 1920x1080 521x293mm 23.5-inch         | 1        | 2.04%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                      | 1        | 2.04%   |
| Ancor Communications VW22A ACI22E3 1680x1050 480x300mm 22.3-inch     | 1        | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 37.5%   |
| 1280x1024 (SXGA)   | 6        | 12.5%   |
| 2560x1440 (QHD)    | 5        | 10.42%  |
| 3840x2160 (4K)     | 2        | 4.17%   |
| 3840x1080          | 2        | 4.17%   |
| 3440x1440          | 2        | 4.17%   |
| 1920x540           | 2        | 4.17%   |
| 1920x1200 (WUXGA)  | 2        | 4.17%   |
| 1600x900 (HD+)     | 2        | 4.17%   |
| 1440x900 (WXGA+)   | 2        | 4.17%   |
| 2560x1080          | 1        | 2.08%   |
| 1680x1050 (WSXGA+) | 1        | 2.08%   |
| 1366x768 (WXGA)    | 1        | 2.08%   |
| 1280x768           | 1        | 2.08%   |
| Unknown            | 1        | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 9        | 19.15%  |
| 27      | 8        | 17.02%  |
| 19      | 5        | 10.64%  |
| 17      | 4        | 8.51%   |
| 34      | 3        | 6.38%   |
| 31      | 3        | 6.38%   |
| 23      | 3        | 6.38%   |
| 21      | 2        | 4.26%   |
| 20      | 2        | 4.26%   |
| 65      | 1        | 2.13%   |
| 48      | 1        | 2.13%   |
| 40      | 1        | 2.13%   |
| 28      | 1        | 2.13%   |
| 25      | 1        | 2.13%   |
| 22      | 1        | 2.13%   |
| 18      | 1        | 2.13%   |
| Unknown | 1        | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 43.48%  |
| 401-500     | 9        | 19.57%  |
| 601-700     | 4        | 8.7%    |
| 301-350     | 4        | 8.7%    |
| 701-800     | 3        | 6.52%   |
| 351-400     | 2        | 4.35%   |
| 1001-1500   | 2        | 4.35%   |
| 801-900     | 1        | 2.17%   |
| Unknown     | 1        | 2.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 30       | 66.67%  |
| 5/4     | 6        | 13.33%  |
| 16/10   | 4        | 8.89%   |
| 21/9    | 2        | 4.44%   |
| 32/9    | 1        | 2.22%   |
| 3/2     | 1        | 2.22%   |
| Unknown | 1        | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 26.09%  |
| 301-350        | 8        | 17.39%  |
| 151-200        | 7        | 15.22%  |
| 351-500        | 6        | 13.04%  |
| 141-150        | 5        | 10.87%  |
| 251-300        | 3        | 6.52%   |
| 501-1000       | 3        | 6.52%   |
| More than 1000 | 1        | 2.17%   |
| Unknown        | 1        | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 35       | 77.78%  |
| 101-120 | 4        | 8.89%   |
| 1-50    | 2        | 4.44%   |
| 121-160 | 2        | 4.44%   |
| 161-240 | 1        | 2.22%   |
| Unknown | 1        | 2.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 78.43%  |
| 0     | 6        | 11.76%  |
| 2     | 5        | 9.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 30       | 42.86%  |
| Realtek Semiconductor     | 24       | 34.29%  |
| Ralink Technology         | 2        | 2.86%   |
| Qualcomm Atheros          | 2        | 2.86%   |
| Marvell Technology Group  | 2        | 2.86%   |
| Linksys                   | 2        | 2.86%   |
| Broadcom                  | 2        | 2.86%   |
| TP-Link                   | 1        | 1.43%   |
| Solarflare Communications | 1        | 1.43%   |
| Microsoft                 | 1        | 1.43%   |
| MediaTek                  | 1        | 1.43%   |
| BUFFALO                   | 1        | 1.43%   |
| Aquantia                  | 1        | 1.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 26.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 6.25%   |
| Intel I211 Gigabit Network Connection                             | 3        | 3.75%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 2.5%    |
| Ralink MT7601U Wireless Adapter                                   | 2        | 2.5%    |
| Intel Wireless 3165                                               | 2        | 2.5%    |
| Intel Wi-Fi 6 AX200                                               | 2        | 2.5%    |
| Intel Ethernet Controller I225-V                                  | 2        | 2.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.5%    |
| Intel Ethernet Connection (17) I219-V                             | 2        | 2.5%    |
| Intel Ethernet Connection (14) I219-V                             | 2        | 2.5%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.5%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 1.25%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 1.25%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.25%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.25%   |
| Realtek 802.11ac NIC                                              | 1        | 1.25%   |
| Ralink RT3071 Wireless Adapter                                    | 1        | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 1.25%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 1.25%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 1.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 1.25%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.25%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 1.25%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.25%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1        | 1.25%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]    | 1        | 1.25%   |
| Intel Wireless 7260                                               | 1        | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 1.25%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.25%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 1.25%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.25%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.25%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.25%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.25%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]          | 1        | 1.25%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 30%     |
| Realtek Semiconductor | 3        | 15%     |
| Ralink Technology     | 2        | 10%     |
| Qualcomm Atheros      | 2        | 10%     |
| Linksys               | 2        | 10%     |
| TP-Link               | 1        | 5%      |
| Microsoft             | 1        | 5%      |
| MediaTek              | 1        | 5%      |
| BUFFALO               | 1        | 5%      |
| Broadcom              | 1        | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2        | 9.09%   |
| Ralink MT7601U Wireless Adapter                                | 2        | 9.09%   |
| Intel Wireless 3165                                            | 2        | 9.09%   |
| Intel Wi-Fi 6 AX200                                            | 2        | 9.09%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 4.55%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 4.55%   |
| Realtek 802.11ac NIC                                           | 1        | 4.55%   |
| Ralink RT3071 Wireless Adapter                                 | 1        | 4.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 4.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 4.55%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1        | 4.55%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1        | 4.55%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1        | 4.55%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236] | 1        | 4.55%   |
| Intel Wireless 7260                                            | 1        | 4.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 4.55%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]       | 1        | 4.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 27       | 48.21%  |
| Realtek Semiconductor     | 23       | 41.07%  |
| Marvell Technology Group  | 2        | 3.57%   |
| Broadcom                  | 2        | 3.57%   |
| Solarflare Communications | 1        | 1.79%   |
| Aquantia                  | 1        | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 36.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 8.62%   |
| Intel I211 Gigabit Network Connection                             | 3        | 5.17%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 5.17%   |
| Intel Ethernet Controller I225-V                                  | 2        | 3.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 3.45%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 3.45%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 3.45%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 3.45%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 1.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.72%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.72%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 1.72%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.72%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.72%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 1.72%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.72%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.72%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.72%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.72%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.72%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.72%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.72%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 50       | 74.63%  |
| WiFi     | 17       | 25.37%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 86.27%  |
| WiFi     | 7        | 13.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 60.78%  |
| 2     | 17       | 33.33%  |
| 3     | 3        | 5.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 80.39%  |
| Yes  | 10       | 19.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 6        | 50%     |
| Cambridge Silicon Radio    | 2        | 16.67%  |
| MediaTek                   | 1        | 8.33%   |
| Integrated System Solution | 1        | 8.33%   |
| IMC Networks               | 1        | 8.33%   |
| Broadcom                   | 1        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                    | 3        | 25%     |
| Intel AX200 Bluetooth                                 | 2        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2        | 16.67%  |
| MediaTek Wireless_Device                              | 1        | 8.33%   |
| Intel AX210 Bluetooth                                 | 1        | 8.33%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 8.33%   |
| IMC Networks Bluetooth Device                         | 1        | 8.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 35       | 43.21%  |
| Nvidia              | 22       | 27.16%  |
| AMD                 | 17       | 20.99%  |
| C-Media Electronics | 3        | 3.7%    |
| Unknown             | 1        | 1.23%   |
| Nektar              | 1        | 1.23%   |
| Creative Technology | 1        | 1.23%   |
| ASUSTek Computer    | 1        | 1.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6        | 6.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5        | 5.43%   |
| AMD Starship/Matisse HD Audio Controller                                          | 5        | 5.43%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4        | 4.35%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4        | 4.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 3.26%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3        | 3.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 3.26%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 2.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 2.17%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 2.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 2.17%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 2.17%   |
| Intel Alder Lake-S HD Audio Controller                                            | 2        | 2.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 2.17%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 2.17%   |
| C-Media Electronics USB PnP Audio Device                                          | 2        | 2.17%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 2        | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 2.17%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 2.17%   |
| Unknown Realtek USB Audio Rear                                                    | 1        | 1.09%   |
| Unknown Realtek USB Audio Front                                                   | 1        | 1.09%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 1.09%   |
| Nvidia High Definition Audio Controller                                           | 1        | 1.09%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 1.09%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 1.09%   |
| Nvidia GM200 High Definition Audio                                                | 1        | 1.09%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 1.09%   |
| Nvidia GF106 High Definition Audio Controller                                     | 1        | 1.09%   |
| Nvidia GA106 High Definition Audio Controller                                     | 1        | 1.09%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 1.09%   |
| Nvidia GA102 High Definition Audio Controller                                     | 1        | 1.09%   |
| Nektar Impact GX61                                                                | 1        | 1.09%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1        | 1.09%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 1.09%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 6        | 15%     |
| Corsair             | 6        | 15%     |
| Unknown             | 5        | 12.5%   |
| G.Skill             | 5        | 12.5%   |
| Micron Technology   | 4        | 10%     |
| Kingston            | 4        | 10%     |
| SK hynix            | 2        | 5%      |
| Crucial             | 2        | 5%      |
| Team                | 1        | 2.5%    |
| PNY                 | 1        | 2.5%    |
| Patriot             | 1        | 2.5%    |
| Gold Key            | 1        | 2.5%    |
| A-DATA Technology   | 1        | 2.5%    |
| Unknown             | 1        | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s               | 1        | 2.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 2.33%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 1        | 2.33%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s          | 1        | 2.33%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                | 1        | 2.33%   |
| Unknown RAM Module 1GB DIMM 667MT/s                     | 1        | 2.33%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s     | 1        | 2.33%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 2.33%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 2.33%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s  | 1        | 2.33%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s    | 1        | 2.33%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s     | 1        | 2.33%   |
| Samsung RAM M378B5273DH0-CH9 4GB SODIMM DDR3 1333MT/s   | 1        | 2.33%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s    | 1        | 2.33%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s    | 1        | 2.33%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s    | 1        | 2.33%   |
| Patriot RAM 1333EL Series 8GB DIMM DDR3 1333MT/s        | 1        | 2.33%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                | 1        | 2.33%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                | 1        | 2.33%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s     | 1        | 2.33%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s      | 1        | 2.33%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s     | 1        | 2.33%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s | 1        | 2.33%   |
| Kingston RAM 9965600-012.A01G 16GB RIMM DDR4 2133MT/s   | 1        | 2.33%   |
| Kingston RAM 9965600-011.A01G 16GB RIMM DDR4 2133MT/s   | 1        | 2.33%   |
| Kingston RAM 9905402-670.A00LF 4GB DIMM DDR3 1333MT/s   | 1        | 2.33%   |
| Gold Key RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s    | 1        | 2.33%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 3666MT/s     | 1        | 2.33%   |
| G.Skill RAM F4-3600C16-8GTZ 8GB DIMM DDR4 3333MT/s      | 1        | 2.33%   |
| G.Skill RAM F4-2666C18-32GVK 32GB DIMM DDR4 2667MT/s    | 1        | 2.33%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s      | 1        | 2.33%   |
| G.Skill RAM F3-12800CL10 8GB DIMM DDR3 1600MT/s         | 1        | 2.33%   |
| Crucial RAM CT8G4DFRA32A.C8FN 8GB DIMM DDR4 3200MT/s    | 1        | 2.33%   |
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2400MT/s    | 1        | 2.33%   |
| Corsair RAM CMX4GX3M2A1333C8 2GB DIMM DDR3 1333MT/s     | 1        | 2.33%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s   | 1        | 2.33%   |
| Corsair RAM CMK8GX4M1Z3200C16 8GB DIMM DDR4 3200MT/s    | 1        | 2.33%   |
| Corsair RAM CMK64GX4M4A2666C16 16GB DIMM DDR4 2667MT/s  | 1        | 2.33%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s  | 1        | 2.33%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s  | 1        | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 21       | 60%     |
| DDR3    | 11       | 31.43%  |
| DDR2    | 2        | 5.71%   |
| Unknown | 1        | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 30       | 85.71%  |
| SODIMM | 4        | 11.43%  |
| RIMM   | 1        | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 14       | 35.9%   |
| 32768 | 6        | 15.38%  |
| 16384 | 6        | 15.38%  |
| 4096  | 6        | 15.38%  |
| 2048  | 4        | 10.26%  |
| 1024  | 3        | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 9        | 23.08%  |
| 2667  | 4        | 10.26%  |
| 1333  | 4        | 10.26%  |
| 2400  | 3        | 7.69%   |
| 2133  | 3        | 7.69%   |
| 1600  | 3        | 7.69%   |
| 667   | 2        | 5.13%   |
| 3733  | 1        | 2.56%   |
| 3666  | 1        | 2.56%   |
| 3600  | 1        | 2.56%   |
| 3400  | 1        | 2.56%   |
| 3333  | 1        | 2.56%   |
| 3100  | 1        | 2.56%   |
| 3000  | 1        | 2.56%   |
| 2200  | 1        | 2.56%   |
| 2048  | 1        | 2.56%   |
| 1866  | 1        | 2.56%   |
| 1800  | 1        | 2.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 2        | 66.67%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Seiko Epson XP-4100 Series    | 1        | 33.33%  |
| Seiko Epson Printer           | 1        | 33.33%  |
| Brother HL-2030 Laser Printer | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| HP OfficeJet 6110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 2        | 28.57%  |
| KYE Systems (Mouse Systems) | 1        | 14.29%  |
| Huawei Technologies         | 1        | 14.29%  |
| Generalplus Technology      | 1        | 14.29%  |
| Elgato Systems              | 1        | 14.29%  |
| 2M UVC CAMERA               | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 1        | 14.29%  |
| Logitech HD Pro Webcam C920                | 1        | 14.29%  |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 14.29%  |
| Huawei HD Webcam                           | 1        | 14.29%  |
| Generalplus GENERAL WEBCAM                 | 1        | 14.29%  |
| Elgato Systems Elgato Facecam              | 1        | 14.29%  |
| 2M UVC CAMERA NexiGo N660 FHD Webcam       | 1        | 14.29%  |

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
| 0     | 36       | 70.59%  |
| 1     | 11       | 21.57%  |
| 2     | 3        | 5.88%   |
| 3     | 1        | 1.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Net/wireless        | 5        | 27.78%  |
| Graphics card       | 5        | 27.78%  |
| Unassigned class    | 2        | 11.11%  |
| Storage/raid        | 1        | 5.56%   |
| Storage             | 1        | 5.56%   |
| Sound               | 1        | 5.56%   |
| Net/ethernet        | 1        | 5.56%   |
| Firewire controller | 1        | 5.56%   |
| Dvb card            | 1        | 5.56%   |

