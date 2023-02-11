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

Total: 57

| Vendor        | Model                   | Probe                                                      | Date         |
|---------------|-------------------------|------------------------------------------------------------|--------------|
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
| Rocky Linux 8.5 | 12       | 24.49%  |
| Rocky Linux 9.1 | 9        | 18.37%  |
| Rocky Linux 8.4 | 9        | 18.37%  |
| Rocky Linux 8.6 | 8        | 16.33%  |
| Rocky Linux 9.0 | 7        | 14.29%  |
| Rocky Linux 8.7 | 3        | 6.12%   |
| Rocky Linux 8.3 | 1        | 2.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Rocky Linux | 48       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 6        | 12.24%  |
| 4.18.0-348.12.2.el8_5.x86_64     | 6        | 12.24%  |
| 5.14.0-70.30.1.el9_0.x86_64      | 3        | 6.12%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 3        | 6.12%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 3        | 6.12%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 2        | 4.08%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 2        | 4.08%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2        | 4.08%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2        | 4.08%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 2        | 4.08%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2        | 4.08%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2        | 4.08%   |
| 6.1.6-1.el8.elrepo.x86_64        | 1        | 2.04%   |
| 6.0.10_tkg_bmq                   | 1        | 2.04%   |
| 6.0.10-1.el9.elrepo.x86_64       | 1        | 2.04%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1        | 2.04%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 1        | 2.04%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 1        | 2.04%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 1        | 2.04%   |
| 4.18.0-425.3.1.el8.x86_64        | 1        | 2.04%   |
| 4.18.0-425.10.1.el8_7.x86_64     | 1        | 2.04%   |
| 4.18.0-372.9.1.el8.x86_64        | 1        | 2.04%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 1        | 2.04%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 1        | 2.04%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 1        | 2.04%   |
| 4.18.0-240.22.1.el8.x86_64       | 1        | 2.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 31       | 63.27%  |
| 5.14.0  | 14       | 28.57%  |
| 6.0.10  | 2        | 4.08%   |
| 6.1.6   | 1        | 2.04%   |
| 5.14.1  | 1        | 2.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 31       | 63.27%  |
| 5.14    | 15       | 30.61%  |
| 6.0     | 2        | 4.08%   |
| 6.1     | 1        | 2.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 48       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 29       | 60.42%  |
| Unknown       | 8        | 16.67%  |
| KDE5          | 6        | 12.5%   |
| MATE          | 2        | 4.17%   |
| GNOME Classic | 2        | 4.17%   |
| XFCE          | 1        | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 23       | 46%     |
| X11     | 20       | 40%     |
| Unknown | 3        | 6%      |
| Web     | 2        | 4%      |
| Tty     | 2        | 4%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 47.92%  |
| GDM     | 20       | 41.67%  |
| SDDM    | 4        | 8.33%   |
| LightDM | 1        | 2.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 28       | 58.33%  |
| ru_RU | 4        | 8.33%   |
| en_IL | 3        | 6.25%   |
| en_SG | 2        | 4.17%   |
| en_AU | 2        | 4.17%   |
| C     | 2        | 4.17%   |
| pl_PL | 1        | 2.08%   |
| ko_KR | 1        | 2.08%   |
| ja_JP | 1        | 2.08%   |
| es_CO | 1        | 2.08%   |
| es_AR | 1        | 2.08%   |
| en_CA | 1        | 2.08%   |
| af_ZA | 1        | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 26       | 54.17%  |
| BIOS | 22       | 45.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 40       | 83.33%  |
| Ext4 | 8        | 16.67%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 25       | 52.08%  |
| Unknown | 14       | 29.17%  |
| MBR     | 9        | 18.75%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 79.17%  |
| Yes       | 10       | 20.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 91.67%  |
| Yes       | 4        | 8.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 15       | 31.25%  |
| Dell                | 9        | 18.75%  |
| MSI                 | 5        | 10.42%  |
| Gigabyte Technology | 5        | 10.42%  |
| Hewlett-Packard     | 3        | 6.25%   |
| Lenovo              | 2        | 4.17%   |
| ASRock              | 2        | 4.17%   |
| Unknown             | 2        | 4.17%   |
| NCR                 | 1        | 2.08%   |
| Intel               | 1        | 2.08%   |
| Google              | 1        | 2.08%   |
| BESSTAR Tech        | 1        | 2.08%   |
| AZW                 | 1        | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell OptiPlex 9020                  | 2        | 4.17%   |
| Unknown                             | 2        | 4.17%   |
| NCR xxxx-xxxx-xxxx                  | 1        | 2.08%   |
| MSI MS-7D46                         | 1        | 2.08%   |
| MSI MS-7B89                         | 1        | 2.08%   |
| MSI MS-7A94                         | 1        | 2.08%   |
| MSI MS-7917                         | 1        | 2.08%   |
| MSI H510M PRO-E                     | 1        | 2.08%   |
| Lenovo ThinkStation P620 30E0S0PR00 | 1        | 2.08%   |
| Lenovo ThinkCentre M72e 36601Y8     | 1        | 2.08%   |
| Intel PRO412081                     | 1        | 2.08%   |
| HP Z600 Workstation                 | 1        | 2.08%   |
| HP ProDesk 600 G2 SFF               | 1        | 2.08%   |
| HP EliteDesk 800 G2 SFF             | 1        | 2.08%   |
| Google Panther                      | 1        | 2.08%   |
| Gigabyte X570 AORUS ULTRA           | 1        | 2.08%   |
| Gigabyte H87-D3H                    | 1        | 2.08%   |
| Gigabyte H81M-S2PV                  | 1        | 2.08%   |
| Gigabyte G41MT-USB3                 | 1        | 2.08%   |
| Gigabyte 970A-UD3P                  | 1        | 2.08%   |
| Dell XPS 8300                       | 1        | 2.08%   |
| Dell Vostro 3681                    | 1        | 2.08%   |
| Dell Precision Tower 7810           | 1        | 2.08%   |
| Dell Precision T7610                | 1        | 2.08%   |
| Dell Precision T5610                | 1        | 2.08%   |
| Dell OptiPlex 390                   | 1        | 2.08%   |
| Dell OptiPlex 3020M                 | 1        | 2.08%   |
| BESSTAR Tech HM90                   | 1        | 2.08%   |
| AZW Gemini M                        | 1        | 2.08%   |
| ASUS ROG STRIX X470-F GAMING        | 1        | 2.08%   |
| ASUS PRIME TRX40-PRO S              | 1        | 2.08%   |
| ASUS PRIME H570-PLUS                | 1        | 2.08%   |
| ASUS PRIME H510M-E                  | 1        | 2.08%   |
| ASUS PRIME B550M-K                  | 1        | 2.08%   |
| ASUS PRIME B550-PLUS                | 1        | 2.08%   |
| ASUS PRIME B460M-A R2.0             | 1        | 2.08%   |
| ASUS PRIME B450M-A II               | 1        | 2.08%   |
| ASUS PRIME B450-PLUS                | 1        | 2.08%   |
| ASUS PRIME B365-PLUS                | 1        | 2.08%   |
| ASUS P8B WS                         | 1        | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 9        | 18.75%  |
| Dell OptiPlex       | 4        | 8.33%   |
| Dell Precision      | 3        | 6.25%   |
| Unknown             | 2        | 4.17%   |
| NCR xxxx-xxxx-xxxx  | 1        | 2.08%   |
| MSI MS-7D46         | 1        | 2.08%   |
| MSI MS-7B89         | 1        | 2.08%   |
| MSI MS-7A94         | 1        | 2.08%   |
| MSI MS-7917         | 1        | 2.08%   |
| MSI H510M           | 1        | 2.08%   |
| Lenovo ThinkStation | 1        | 2.08%   |
| Lenovo ThinkCentre  | 1        | 2.08%   |
| Intel PRO412081     | 1        | 2.08%   |
| HP Z600             | 1        | 2.08%   |
| HP ProDesk          | 1        | 2.08%   |
| HP EliteDesk        | 1        | 2.08%   |
| Google Panther      | 1        | 2.08%   |
| Gigabyte X570       | 1        | 2.08%   |
| Gigabyte H87-D3H    | 1        | 2.08%   |
| Gigabyte H81M-S2PV  | 1        | 2.08%   |
| Gigabyte G41MT-USB3 | 1        | 2.08%   |
| Gigabyte 970A-UD3P  | 1        | 2.08%   |
| Dell XPS            | 1        | 2.08%   |
| Dell Vostro         | 1        | 2.08%   |
| BESSTAR Tech HM90   | 1        | 2.08%   |
| AZW Gemini          | 1        | 2.08%   |
| ASUS ROG            | 1        | 2.08%   |
| ASUS P8B            | 1        | 2.08%   |
| ASUS P5Q            | 1        | 2.08%   |
| ASUS ORION          | 1        | 2.08%   |
| ASUS M5A97          | 1        | 2.08%   |
| ASUS Crosshair      | 1        | 2.08%   |
| ASRock H610M-HDV    | 1        | 2.08%   |
| ASRock B450M        | 1        | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 7        | 14.58%  |
| 2020 | 6        | 12.5%   |
| 2018 | 5        | 10.42%  |
| 2015 | 5        | 10.42%  |
| 2013 | 5        | 10.42%  |
| 2011 | 5        | 10.42%  |
| 2014 | 4        | 8.33%   |
| 2019 | 3        | 6.25%   |
| 2022 | 2        | 4.17%   |
| 2012 | 2        | 4.17%   |
| 2008 | 2        | 4.17%   |
| 2017 | 1        | 2.08%   |
| 2010 | 1        | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 48       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 45       | 93.75%  |
| Enabled  | 3        | 6.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 47       | 97.92%  |
| Yes  | 1        | 2.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 12       | 25%     |
| 16.01-24.0  | 9        | 18.75%  |
| 8.01-16.0   | 9        | 18.75%  |
| 4.01-8.0    | 6        | 12.5%   |
| 64.01-256.0 | 5        | 10.42%  |
| 3.01-4.0    | 3        | 6.25%   |
| 1.01-2.0    | 2        | 4.17%   |
| 24.01-32.0  | 1        | 2.08%   |
| 2.01-3.0    | 1        | 2.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 16       | 33.33%  |
| 4.01-8.0   | 10       | 20.83%  |
| 3.01-4.0   | 9        | 18.75%  |
| 1.01-2.0   | 6        | 12.5%   |
| 0.51-1.0   | 3        | 6.25%   |
| 8.01-16.0  | 2        | 4.17%   |
| 16.01-24.0 | 1        | 2.08%   |
| 0.01-0.5   | 1        | 2.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 43.75%  |
| 2      | 10       | 20.83%  |
| 3      | 7        | 14.58%  |
| 4      | 5        | 10.42%  |
| 5      | 2        | 4.17%   |
| 9      | 1        | 2.08%   |
| 8      | 1        | 2.08%   |
| 6      | 1        | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 58.33%  |
| Yes       | 20       | 41.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 47       | 97.92%  |
| No        | 1        | 2.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 67.35%  |
| Yes       | 16       | 32.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 77.08%  |
| Yes       | 11       | 22.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 10       | 20.83%  |
| Russia       | 4        | 8.33%   |
| Singapore    | 3        | 6.25%   |
| Israel       | 3        | 6.25%   |
| Canada       | 3        | 6.25%   |
| Australia    | 3        | 6.25%   |
| South Korea  | 2        | 4.17%   |
| Italy        | 2        | 4.17%   |
| Indonesia    | 2        | 4.17%   |
| Germany      | 2        | 4.17%   |
| Sweden       | 1        | 2.08%   |
| South Africa | 1        | 2.08%   |
| Portugal     | 1        | 2.08%   |
| Poland       | 1        | 2.08%   |
| Norway       | 1        | 2.08%   |
| Netherlands  | 1        | 2.08%   |
| Mexico       | 1        | 2.08%   |
| Japan        | 1        | 2.08%   |
| India        | 1        | 2.08%   |
| France       | 1        | 2.08%   |
| Finland      | 1        | 2.08%   |
| Czechia      | 1        | 2.08%   |
| Colombia     | 1        | 2.08%   |
| Argentina    | 1        | 2.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Singapore              | 3        | 6.25%   |
| Haifa                  | 2        | 4.17%   |
| Yogyakarta             | 1        | 2.08%   |
| Wells                  | 1        | 2.08%   |
| Waltham                | 1        | 2.08%   |
| Voronezh               | 1        | 2.08%   |
| Vancouver              | 1        | 2.08%   |
| Toronto                | 1        | 2.08%   |
| Tlaxcala City          | 1        | 2.08%   |
| St. John's             | 1        | 2.08%   |
| St Petersburg          | 1        | 2.08%   |
| Sobral de Monte Agraco | 1        | 2.08%   |
| Semarang               | 1        | 2.08%   |
| Rotterdam              | 1        | 2.08%   |
| Rehovot                | 1        | 2.08%   |
| Prague                 | 1        | 2.08%   |
| Paris                  | 1        | 2.08%   |
| Ōtsu                  | 1        | 2.08%   |
| Oslo                   | 1        | 2.08%   |
| Moscow                 | 1        | 2.08%   |
| Monza                  | 1        | 2.08%   |
| Milan                  | 1        | 2.08%   |
| Mequon                 | 1        | 2.08%   |
| Melbourne              | 1        | 2.08%   |
| Lebanon                | 1        | 2.08%   |
| Krasnodar              | 1        | 2.08%   |
| Krakow                 | 1        | 2.08%   |
| Imphal                 | 1        | 2.08%   |
| Helsinki               | 1        | 2.08%   |
| Giessen                | 1        | 2.08%   |
| Fredericksburg         | 1        | 2.08%   |
| Florence               | 1        | 2.08%   |
| Fairfax                | 1        | 2.08%   |
| Enebyberg              | 1        | 2.08%   |
| Corvallis              | 1        | 2.08%   |
| Centurion              | 1        | 2.08%   |
| Calchaqui              | 1        | 2.08%   |
| Burlington             | 1        | 2.08%   |
| Bucheon-si             | 1        | 2.08%   |
| Bucaramanga            | 1        | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 16       | 32     | 20.25%  |
| WDC                         | 15       | 29     | 18.99%  |
| Samsung Electronics         | 12       | 22     | 15.19%  |
| Toshiba                     | 7        | 7      | 8.86%   |
| Hitachi                     | 4        | 5      | 5.06%   |
| Intel                       | 3        | 3      | 3.8%    |
| Crucial                     | 3        | 3      | 3.8%    |
| SanDisk                     | 2        | 2      | 2.53%   |
| Kingston                    | 2        | 2      | 2.53%   |
| HGST                        | 2        | 2      | 2.53%   |
| Team                        | 1        | 1      | 1.27%   |
| SK hynix                    | 1        | 1      | 1.27%   |
| PNY                         | 1        | 1      | 1.27%   |
| Phison                      | 1        | 1      | 1.27%   |
| MyDigitalSSD                | 1        | 1      | 1.27%   |
| Kingston Technology Company | 1        | 1      | 1.27%   |
| Gigabyte Technology         | 1        | 1      | 1.27%   |
| Digma                       | 1        | 1      | 1.27%   |
| Corsair                     | 1        | 1      | 1.27%   |
| China                       | 1        | 1      | 1.27%   |
| Apacer                      | 1        | 1      | 1.27%   |
| ADATA SU                    | 1        | 1      | 1.27%   |
| A-DATA Technology           | 1        | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 3        | 3.16%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 2.11%   |
| Samsung SSD 860 EVO 1TB          | 2        | 2.11%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD | 1        | 1.05%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD | 1        | 1.05%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 1.05%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 1.05%   |
| WDC WDS100T1X0E-00AFY0 1TB       | 1        | 1.05%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD   | 1        | 1.05%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 1        | 1.05%   |
| WDC WD5000AUDX-63WNHY0 500GB     | 1        | 1.05%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 1.05%   |
| WDC WD5000AAKX-001CA0 500GB      | 1        | 1.05%   |
| WDC WD30EZRX-00D8PB0 3TB         | 1        | 1.05%   |
| WDC WD2500AAJS-22VTA0 250GB      | 1        | 1.05%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 1.05%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1        | 1.05%   |
| WDC WD20EZBX-00AYRA0 2TB         | 1        | 1.05%   |
| WDC WD20EFZX-68AWUN0 2TB         | 1        | 1.05%   |
| WDC WD2002FAEX-007BA0 2TB        | 1        | 1.05%   |
| WDC WD10EZEX-75M2NA0 1TB         | 1        | 1.05%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 1.05%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1        | 1.05%   |
| WDC WD1001FALS-00J7B1 1TB        | 1        | 1.05%   |
| WDC WD1001FALS-00J7B0 1TB        | 1        | 1.05%   |
| Toshiba THNSNJ128GCSU 128GB SSD  | 1        | 1.05%   |
| Toshiba MQ01ABD100 1TB           | 1        | 1.05%   |
| Toshiba MK1059GSM 1TB            | 1        | 1.05%   |
| Toshiba MG07ACA12TE 12TB         | 1        | 1.05%   |
| Toshiba MG04ACA400E 4TB          | 1        | 1.05%   |
| Toshiba DT01ACA100 1TB           | 1        | 1.05%   |
| Toshiba DT01ACA050 500GB         | 1        | 1.05%   |
| Team L5 LITE SSD 240GB           | 1        | 1.05%   |
| SK hynix SH920 2.5 7MM 256GB SSD | 1        | 1.05%   |
| Seagate ST9500420AS 500GB        | 1        | 1.05%   |
| Seagate ST9500325AS 500GB        | 1        | 1.05%   |
| Seagate ST9320325AS 320GB        | 1        | 1.05%   |
| Seagate ST4000VN008-2DR166 4TB   | 1        | 1.05%   |
| Seagate ST4000VN006-3CW104 4TB   | 1        | 1.05%   |
| Seagate ST4000DM004-2CV104 4TB   | 1        | 1.05%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 32     | 38.1%   |
| WDC                 | 12       | 21     | 28.57%  |
| Toshiba             | 6        | 6      | 14.29%  |
| Hitachi             | 4        | 5      | 9.52%   |
| Samsung Electronics | 2        | 3      | 4.76%   |
| HGST                | 2        | 2      | 4.76%   |

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
| HDD     | 29       | 69     | 42.65%  |
| SSD     | 23       | 31     | 33.82%  |
| NVMe    | 15       | 19     | 22.06%  |
| Unknown | 1        | 1      | 1.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 42       | 99     | 71.19%  |
| NVMe | 15       | 19     | 25.42%  |
| SAS  | 2        | 2      | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 28       | 48     | 50%     |
| 0.51-1.0   | 16       | 29     | 28.57%  |
| 1.01-2.0   | 6        | 9      | 10.71%  |
| 3.01-4.0   | 4        | 12     | 7.14%   |
| 2.01-3.0   | 1        | 1      | 1.79%   |
| 10.01-20.0 | 1        | 1      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 27.08%  |
| 501-1000       | 11       | 22.92%  |
| 1001-2000      | 8        | 16.67%  |
| 251-500        | 6        | 12.5%   |
| More than 3000 | 4        | 8.33%   |
| 2001-3000      | 2        | 4.17%   |
| 51-100         | 2        | 4.17%   |
| 1-20           | 1        | 2.08%   |
| Unknown        | 1        | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 16       | 32.65%  |
| 21-50          | 10       | 20.41%  |
| 51-100         | 8        | 16.33%  |
| 251-500        | 4        | 8.16%   |
| 501-1000       | 4        | 8.16%   |
| More than 3000 | 3        | 6.12%   |
| 101-250        | 2        | 4.08%   |
| 1001-2000      | 1        | 2.04%   |
| Unknown        | 1        | 2.04%   |

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
| Works    | 33       | 78     | 57.89%  |
| Detected | 15       | 27     | 26.32%  |
| Malfunc  | 8        | 14     | 14.04%  |
| Failed   | 1        | 1      | 1.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 33       | 48.53%  |
| AMD                         | 15       | 22.06%  |
| Samsung Electronics         | 6        | 8.82%   |
| Kingston Technology Company | 2        | 2.94%   |
| Broadcom / LSI              | 2        | 2.94%   |
| ASMedia Technology          | 2        | 2.94%   |
| VIA Technologies            | 1        | 1.47%   |
| SanDisk                     | 1        | 1.47%   |
| Realtek Semiconductor       | 1        | 1.47%   |
| Phison Electronics          | 1        | 1.47%   |
| Micron/Crucial Technology   | 1        | 1.47%   |
| Marvell Technology Group    | 1        | 1.47%   |
| JMicron Technology          | 1        | 1.47%   |
| Adaptec                     | 1        | 1.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 9.88%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 6.17%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 6.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 3.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 2.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 2.47%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.47%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 2.47%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.47%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.47%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 1.23%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 1.23%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.23%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 1.23%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.23%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.23%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 1.23%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 1.23%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 1.23%   |
| JMicron JMB58x AHCI SATA controller                                                     | 1        | 1.23%   |
| Intel PCIe Data Center SSD                                                              | 1        | 1.23%   |
| Intel Non-Volatile memory controller                                                    | 1        | 1.23%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.23%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1        | 1.23%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.23%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 1.23%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 1.23%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.23%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 1.23%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.23%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 36       | 52.17%  |
| NVMe | 15       | 21.74%  |
| RAID | 8        | 11.59%  |
| IDE  | 7        | 10.14%  |
| SAS  | 2        | 2.9%    |
| SCSI | 1        | 1.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 33       | 68.75%  |
| AMD    | 15       | 31.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 4.17%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz         | 2        | 4.17%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1        | 2.08%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz           | 1        | 2.08%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 2.08%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz            | 1        | 2.08%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1        | 2.08%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz         | 1        | 2.08%   |
| Intel Core i9-7920X CPU @ 2.90GHz              | 1        | 2.08%   |
| Intel Core i7-6950X CPU @ 3.00GHz              | 1        | 2.08%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 1        | 2.08%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 2.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 2.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 2.08%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 2.08%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 2.08%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 2.08%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1        | 2.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 2.08%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 2.08%   |
| Intel Core i5-10600KF CPU @ 4.10GHz            | 1        | 2.08%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 1        | 2.08%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 2.08%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 1        | 2.08%   |
| Intel Core i3-3217U CPU @ 1.80GHz              | 1        | 2.08%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 2.08%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1        | 2.08%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1        | 2.08%   |
| Intel Celeron 2955U @ 1.40GHz                  | 1        | 2.08%   |
| Intel 12th Gen Core i5-12400F                  | 1        | 2.08%   |
| Intel 12th Gen Core i5-12400                   | 1        | 2.08%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores     | 1        | 2.08%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 2.08%   |
| AMD Ryzen Embedded V1500B                      | 1        | 2.08%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 2.08%   |
| AMD Ryzen 9 4900H with Radeon Graphics         | 1        | 2.08%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics     | 1        | 2.08%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 2.08%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 2.08%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1        | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 9        | 18.75%  |
| Intel Core i5           | 6        | 12.5%   |
| Other                   | 4        | 8.33%   |
| Intel Xeon              | 4        | 8.33%   |
| Intel Core i3           | 4        | 8.33%   |
| AMD Ryzen 7             | 3        | 6.25%   |
| Intel Celeron           | 2        | 4.17%   |
| AMD Ryzen Threadripper  | 2        | 4.17%   |
| AMD Ryzen 9             | 2        | 4.17%   |
| AMD Ryzen 5             | 2        | 4.17%   |
| AMD FX                  | 2        | 4.17%   |
| Intel Pentium Dual-Core | 1        | 2.08%   |
| Intel Pentium Dual      | 1        | 2.08%   |
| Intel Core i9           | 1        | 2.08%   |
| Intel Core 2 Quad       | 1        | 2.08%   |
| AMD Ryzen Embedded      | 1        | 2.08%   |
| AMD Ryzen 7 PRO         | 1        | 2.08%   |
| AMD Ryzen 3             | 1        | 2.08%   |
| AMD Phenom II X6        | 1        | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 15       | 31.25%  |
| 6      | 10       | 20.83%  |
| 8      | 9        | 18.75%  |
| 2      | 7        | 14.58%  |
| 12     | 3        | 6.25%   |
| 24     | 1        | 2.08%   |
| 16     | 1        | 2.08%   |
| 10     | 1        | 2.08%   |
| 3      | 1        | 2.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 95.83%  |
| 2      | 2        | 4.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 36       | 75%     |
| 1      | 12       | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 48       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 5        | 10.42%  |
| 0x306a9    | 3        | 6.25%   |
| 0x206a7    | 3        | 6.25%   |
| 0xa0671    | 2        | 4.17%   |
| 0xa0655    | 2        | 4.17%   |
| 0x506e3    | 2        | 4.17%   |
| 0x306e4    | 2        | 4.17%   |
| 0x08600106 | 2        | 4.17%   |
| 0x06000852 | 2        | 4.17%   |
| 0xa0653    | 1        | 2.08%   |
| 0x906ed    | 1        | 2.08%   |
| 0x90675    | 1        | 2.08%   |
| 0x90672    | 1        | 2.08%   |
| 0x706a8    | 1        | 2.08%   |
| 0x6fd      | 1        | 2.08%   |
| 0x50654    | 1        | 2.08%   |
| 0x406f1    | 1        | 2.08%   |
| 0x40651    | 1        | 2.08%   |
| 0x306f2    | 1        | 2.08%   |
| 0x206c2    | 1        | 2.08%   |
| 0x10677    | 1        | 2.08%   |
| 0x10676    | 1        | 2.08%   |
| 0x0a20120a | 1        | 2.08%   |
| 0x0a201016 | 1        | 2.08%   |
| 0x0a201009 | 1        | 2.08%   |
| 0x0870100a | 1        | 2.08%   |
| 0x0830104d | 1        | 2.08%   |
| 0x08301039 | 1        | 2.08%   |
| 0x08108109 | 1        | 2.08%   |
| 0x08101016 | 1        | 2.08%   |
| 0x0800820d | 1        | 2.08%   |
| 0x08001138 | 1        | 2.08%   |
| 0x010000dc | 1        | 2.08%   |
| Unknown    | 1        | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 8        | 16.67%  |
| Zen 2            | 5        | 10.42%  |
| IvyBridge        | 5        | 10.42%  |
| Zen 3            | 3        | 6.25%   |
| Skylake          | 3        | 6.25%   |
| SandyBridge      | 3        | 6.25%   |
| CometLake        | 3        | 6.25%   |
| Zen+             | 2        | 4.17%   |
| Zen              | 2        | 4.17%   |
| Piledriver       | 2        | 4.17%   |
| Penryn           | 2        | 4.17%   |
| Icelake          | 2        | 4.17%   |
| Alderlake Hybrid | 2        | 4.17%   |
| Westmere         | 1        | 2.08%   |
| KabyLake         | 1        | 2.08%   |
| K10              | 1        | 2.08%   |
| Goldmont plus    | 1        | 2.08%   |
| Core             | 1        | 2.08%   |
| Broadwell        | 1        | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 22       | 42.31%  |
| Intel             | 20       | 38.46%  |
| AMD               | 9        | 17.31%  |
| ASPEED Technology | 1        | 1.92%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 5.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 5.66%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2        | 3.77%   |
| Intel HD Graphics 530                                                       | 2        | 3.77%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 3.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.77%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2        | 3.77%   |
| AMD Renoir                                                                  | 2        | 3.77%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 3.77%   |
| Nvidia TU117GL [T600]                                                       | 1        | 1.89%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.89%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.89%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.89%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 1.89%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.89%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.89%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.89%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.89%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 1.89%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 1.89%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 1.89%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.89%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 1.89%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 1.89%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.89%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.89%   |
| Nvidia GA102GL [RTX A6000]                                                  | 1        | 1.89%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.89%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.89%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.89%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 1.89%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.89%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.89%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 1.89%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.89%   |
| AMD R480 [Radeon X850 XT Platinum Edition] (Secondary)                      | 1        | 1.89%   |
| AMD R480 [Radeon X850 XT Platinum Edition]                                  | 1        | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 18       | 37.5%   |
| 1 x Intel       | 18       | 37.5%   |
| 1 x AMD         | 8        | 16.67%  |
| Intel + Nvidia  | 2        | 4.17%   |
| 2 x AMD         | 1        | 2.08%   |
| Nvidia + ASPEED | 1        | 2.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 36       | 75%     |
| Proprietary | 9        | 18.75%  |
| Unknown     | 3        | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 43.75%  |
| 1.01-2.0   | 9        | 18.75%  |
| 0.01-0.5   | 6        | 12.5%   |
| 0.51-1.0   | 5        | 10.42%  |
| 7.01-8.0   | 2        | 4.17%   |
| 8.01-16.0  | 2        | 4.17%   |
| 32.01-64.0 | 1        | 2.08%   |
| 5.01-6.0   | 1        | 2.08%   |
| 3.01-4.0   | 1        | 2.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 7        | 15.91%  |
| Samsung Electronics  | 6        | 13.64%  |
| Acer                 | 6        | 13.64%  |
| Ancor Communications | 4        | 9.09%   |
| Philips              | 3        | 6.82%   |
| Iiyama               | 3        | 6.82%   |
| Goldstar             | 3        | 6.82%   |
| Hewlett-Packard      | 2        | 4.55%   |
| Sony                 | 1        | 2.27%   |
| SGT                  | 1        | 2.27%   |
| OEM                  | 1        | 2.27%   |
| NEC Computers        | 1        | 2.27%   |
| HUAWEI               | 1        | 2.27%   |
| HCL                  | 1        | 2.27%   |
| Eizo                 | 1        | 2.27%   |
| BenQ                 | 1        | 2.27%   |
| ASUSTek Computer     | 1        | 2.27%   |
| AOC                  | 1        | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                    | 1        | 2.17%   |
| SGT HDMI SGT1560 1920x1080 330x220mm 15.6-inch                        | 1        | 2.17%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch     | 1        | 2.17%   |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch  | 1        | 2.17%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 1        | 2.17%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1        | 2.17%   |
| Samsung Electronics LF27T35 SAM7080 1920x1080 598x337mm 27.0-inch     | 1        | 2.17%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1        | 2.17%   |
| Philips PHL 275E2F PHLC23A 2560x1440 597x336mm 27.0-inch              | 1        | 2.17%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1        | 2.17%   |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch             | 1        | 2.17%   |
| OEM 22W_LCD_TV OEM3700 1920x1080                                      | 1        | 2.17%   |
| NEC Computers LCD1760NX NEC6604 1280x1024 338x270mm 17.0-inch         | 1        | 2.17%   |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                  | 1        | 2.17%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                  | 1        | 2.17%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 1        | 2.17%   |
| HUAWEI SSN-24 HWV6E4E 1920x1080 527x296mm 23.8-inch                   | 1        | 2.17%   |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch          | 1        | 2.17%   |
| Hewlett-Packard 2509 HWP283B 1920x1080 553x311mm 25.0-inch            | 1        | 2.17%   |
| HCL HCMELWBN11 HCME444 1366x768 410x230mm 18.5-inch                   | 1        | 2.17%   |
| Goldstar WFHD GSM7748 2560x1080 798x334mm 34.1-inch                   | 1        | 2.17%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch              | 1        | 2.17%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 1        | 2.17%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1        | 2.17%   |
| Eizo CG247X ENC2801 1920x1200 520x330mm 24.2-inch                     | 1        | 2.17%   |
| Dell P2416D DELA0C4 2560x1440 527x296mm 23.8-inch                     | 1        | 2.17%   |
| Dell P2014H DEL4096 1600x900 434x236mm 19.4-inch                      | 1        | 2.17%   |
| Dell P1913 DELA088 1440x900 410x260mm 19.1-inch                       | 1        | 2.17%   |
| Dell LCD Monitor U2414H 3840x1080                                     | 1        | 2.17%   |
| Dell LCD Monitor U2414H                                               | 1        | 2.17%   |
| Dell IN2030M DELF03C 1600x900 443x249mm 20.0-inch                     | 1        | 2.17%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 1        | 2.17%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                     | 1        | 2.17%   |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                     | 1        | 2.17%   |
| ASUSTek Computer VP247 AUS24DA 1920x1080 521x293mm 23.5-inch          | 1        | 2.17%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1        | 2.17%   |
| Ancor Communications VW22A ACI22E3 1680x1050 480x300mm 22.3-inch      | 1        | 2.17%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 1        | 2.17%   |
| Ancor Communications ASUS VW247 ACI2496 1920x1080 531x299mm 24.0-inch | 1        | 2.17%   |
| Ancor Communications ASUS PB278 ACI27A3 1920x1080 597x336mm 27.0-inch | 1        | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 17       | 37.78%  |
| 2560x1440 (QHD)    | 5        | 11.11%  |
| 1280x1024 (SXGA)   | 4        | 8.89%   |
| 3840x2160 (4K)     | 2        | 4.44%   |
| 3840x1080          | 2        | 4.44%   |
| 3440x1440          | 2        | 4.44%   |
| 1920x540           | 2        | 4.44%   |
| 1920x1200 (WUXGA)  | 2        | 4.44%   |
| 1600x900 (HD+)     | 2        | 4.44%   |
| 1440x900 (WXGA+)   | 2        | 4.44%   |
| 2560x1080          | 1        | 2.22%   |
| 1680x1050 (WSXGA+) | 1        | 2.22%   |
| 1366x768 (WXGA)    | 1        | 2.22%   |
| 1280x768           | 1        | 2.22%   |
| Unknown            | 1        | 2.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 9        | 20.45%  |
| 27      | 8        | 18.18%  |
| 17      | 4        | 9.09%   |
| 34      | 3        | 6.82%   |
| 31      | 3        | 6.82%   |
| 23      | 3        | 6.82%   |
| 19      | 3        | 6.82%   |
| 20      | 2        | 4.55%   |
| 65      | 1        | 2.27%   |
| 48      | 1        | 2.27%   |
| 40      | 1        | 2.27%   |
| 28      | 1        | 2.27%   |
| 25      | 1        | 2.27%   |
| 22      | 1        | 2.27%   |
| 21      | 1        | 2.27%   |
| 18      | 1        | 2.27%   |
| Unknown | 1        | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 46.51%  |
| 401-500     | 8        | 18.6%   |
| 601-700     | 4        | 9.3%    |
| 301-350     | 4        | 9.3%    |
| 701-800     | 3        | 6.98%   |
| 1001-1500   | 2        | 4.65%   |
| 801-900     | 1        | 2.33%   |
| Unknown     | 1        | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 29       | 69.05%  |
| 5/4     | 4        | 9.52%   |
| 16/10   | 4        | 9.52%   |
| 21/9    | 2        | 4.76%   |
| 32/9    | 1        | 2.38%   |
| 3/2     | 1        | 2.38%   |
| Unknown | 1        | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 25.58%  |
| 301-350        | 8        | 18.6%   |
| 351-500        | 6        | 13.95%  |
| 151-200        | 5        | 11.63%  |
| 141-150        | 5        | 11.63%  |
| 251-300        | 3        | 6.98%   |
| 501-1000       | 3        | 6.98%   |
| More than 1000 | 1        | 2.33%   |
| Unknown        | 1        | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 33       | 78.57%  |
| 101-120 | 3        | 7.14%   |
| 1-50    | 2        | 4.76%   |
| 121-160 | 2        | 4.76%   |
| 161-240 | 1        | 2.38%   |
| Unknown | 1        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 37       | 77.08%  |
| 0     | 6        | 12.5%   |
| 2     | 5        | 10.42%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 27       | 40.91%  |
| Realtek Semiconductor     | 23       | 34.85%  |
| Ralink Technology         | 2        | 3.03%   |
| Qualcomm Atheros          | 2        | 3.03%   |
| Marvell Technology Group  | 2        | 3.03%   |
| Linksys                   | 2        | 3.03%   |
| Broadcom                  | 2        | 3.03%   |
| TP-Link                   | 1        | 1.52%   |
| Solarflare Communications | 1        | 1.52%   |
| Microsoft                 | 1        | 1.52%   |
| MediaTek                  | 1        | 1.52%   |
| BUFFALO                   | 1        | 1.52%   |
| Aquantia                  | 1        | 1.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 28%     |
| Intel I211 Gigabit Network Connection                             | 3        | 4%      |
| Intel Ethernet Connection I217-LM                                 | 3        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 4%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 2.67%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 2.67%   |
| Intel Wireless 3165                                               | 2        | 2.67%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 2.67%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.67%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 2.67%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 2.67%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 1.33%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 1.33%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.33%   |
| Realtek 802.11ac NIC                                              | 1        | 1.33%   |
| Ralink RT3071 Wireless Adapter                                    | 1        | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 1.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 1.33%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 1.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 1.33%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.33%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 1.33%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.33%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1        | 1.33%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]    | 1        | 1.33%   |
| Intel Wireless 7260                                               | 1        | 1.33%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.33%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 1.33%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.33%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.33%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.33%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.33%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.33%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.33%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]          | 1        | 1.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.33%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1        | 1.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 5        | 26.32%  |
| Realtek Semiconductor | 3        | 15.79%  |
| Ralink Technology     | 2        | 10.53%  |
| Qualcomm Atheros      | 2        | 10.53%  |
| Linksys               | 2        | 10.53%  |
| TP-Link               | 1        | 5.26%   |
| Microsoft             | 1        | 5.26%   |
| MediaTek              | 1        | 5.26%   |
| BUFFALO               | 1        | 5.26%   |
| Broadcom              | 1        | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2        | 9.52%   |
| Ralink MT7601U Wireless Adapter                                | 2        | 9.52%   |
| Intel Wireless 3165                                            | 2        | 9.52%   |
| Intel Wi-Fi 6 AX200                                            | 2        | 9.52%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 4.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 4.76%   |
| Realtek 802.11ac NIC                                           | 1        | 4.76%   |
| Ralink RT3071 Wireless Adapter                                 | 1        | 4.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 4.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 4.76%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1        | 4.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1        | 4.76%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1        | 4.76%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236] | 1        | 4.76%   |
| Intel Wireless 7260                                            | 1        | 4.76%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]       | 1        | 4.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1        | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 24       | 46.15%  |
| Realtek Semiconductor     | 22       | 42.31%  |
| Marvell Technology Group  | 2        | 3.85%   |
| Broadcom                  | 2        | 3.85%   |
| Solarflare Communications | 1        | 1.92%   |
| Aquantia                  | 1        | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 38.89%  |
| Intel I211 Gigabit Network Connection                             | 3        | 5.56%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 5.56%   |
| Intel Ethernet Controller I225-V                                  | 2        | 3.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 3.7%    |
| Intel Ethernet Connection (17) I219-V                             | 2        | 3.7%    |
| Intel Ethernet Connection (14) I219-V                             | 2        | 3.7%    |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 1.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.85%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.85%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 1.85%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.85%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.85%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 1.85%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.85%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.85%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.85%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.85%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.85%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.85%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.85%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 47       | 74.6%   |
| WiFi     | 16       | 25.4%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 41       | 87.23%  |
| WiFi     | 6        | 12.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 60.42%  |
| 2     | 17       | 35.42%  |
| 3     | 2        | 4.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 39       | 81.25%  |
| Yes  | 9        | 18.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 5        | 45.45%  |
| Cambridge Silicon Radio    | 2        | 18.18%  |
| MediaTek                   | 1        | 9.09%   |
| Integrated System Solution | 1        | 9.09%   |
| IMC Networks               | 1        | 9.09%   |
| Broadcom                   | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                    | 3        | 27.27%  |
| Intel AX200 Bluetooth                                 | 2        | 18.18%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2        | 18.18%  |
| MediaTek Wireless_Device                              | 1        | 9.09%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 9.09%   |
| IMC Networks Bluetooth Device                         | 1        | 9.09%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 33       | 42.31%  |
| Nvidia              | 21       | 26.92%  |
| AMD                 | 17       | 21.79%  |
| C-Media Electronics | 3        | 3.85%   |
| Unknown             | 1        | 1.28%   |
| Nektar              | 1        | 1.28%   |
| Creative Technology | 1        | 1.28%   |
| ASUSTek Computer    | 1        | 1.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5        | 5.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5        | 5.62%   |
| AMD Starship/Matisse HD Audio Controller                                          | 5        | 5.62%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 4.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4        | 4.49%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4        | 4.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 3.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 3.37%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 2.25%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 2.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 2.25%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 2.25%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 2.25%   |
| Intel Alder Lake-S HD Audio Controller                                            | 2        | 2.25%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 2.25%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 2.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 2.25%   |
| C-Media Electronics TONOR TC-777 Audio Device                                     | 2        | 2.25%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 2        | 2.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 2.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 2.25%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 2.25%   |
| Unknown Realtek USB Audio Rear                                                    | 1        | 1.12%   |
| Unknown Realtek USB Audio Front                                                   | 1        | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 1.12%   |
| Nvidia High Definition Audio Controller                                           | 1        | 1.12%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 1.12%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 1.12%   |
| Nvidia GM200 High Definition Audio                                                | 1        | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 1.12%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 1.12%   |
| Nvidia GF106 High Definition Audio Controller                                     | 1        | 1.12%   |
| Nvidia GA106 High Definition Audio Controller                                     | 1        | 1.12%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 1.12%   |
| Nvidia GA102 High Definition Audio Controller                                     | 1        | 1.12%   |
| Nektar Impact GX61                                                                | 1        | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1        | 1.12%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 1.12%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 1.12%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 6        | 15.79%  |
| Corsair             | 6        | 15.79%  |
| Unknown             | 5        | 13.16%  |
| G.Skill             | 5        | 13.16%  |
| Micron Technology   | 4        | 10.53%  |
| Kingston            | 4        | 10.53%  |
| Crucial             | 2        | 5.26%   |
| Team                | 1        | 2.63%   |
| SK hynix            | 1        | 2.63%   |
| PNY                 | 1        | 2.63%   |
| Patriot             | 1        | 2.63%   |
| Gold Key            | 1        | 2.63%   |
| A-DATA Technology   | 1        | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s               | 1        | 2.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 2.44%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 1        | 2.44%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s          | 1        | 2.44%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                | 1        | 2.44%   |
| Unknown RAM Module 1GB DIMM 667MT/s                     | 1        | 2.44%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s     | 1        | 2.44%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 2.44%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s  | 1        | 2.44%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s    | 1        | 2.44%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s     | 1        | 2.44%   |
| Samsung RAM M378B5273DH0-CH9 4GB SODIMM DDR3 1333MT/s   | 1        | 2.44%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s    | 1        | 2.44%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s    | 1        | 2.44%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s    | 1        | 2.44%   |
| Patriot RAM 1333EL Series 8GB DIMM DDR3 1333MT/s        | 1        | 2.44%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                | 1        | 2.44%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                | 1        | 2.44%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s     | 1        | 2.44%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s      | 1        | 2.44%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s     | 1        | 2.44%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s | 1        | 2.44%   |
| Kingston RAM 9965600-012.A01G 16GB RIMM DDR4 2133MT/s   | 1        | 2.44%   |
| Kingston RAM 9965600-011.A01G 16GB RIMM DDR4 2133MT/s   | 1        | 2.44%   |
| Kingston RAM 9905402-670.A00LF 4GB DIMM DDR3 1333MT/s   | 1        | 2.44%   |
| Gold Key RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s    | 1        | 2.44%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 3666MT/s     | 1        | 2.44%   |
| G.Skill RAM F4-3600C16-8GTZ 8GB DIMM DDR4 3333MT/s      | 1        | 2.44%   |
| G.Skill RAM F4-2666C18-32GVK 32GB DIMM DDR4 2667MT/s    | 1        | 2.44%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s      | 1        | 2.44%   |
| G.Skill RAM F3-12800CL10 8GB DIMM DDR3 1600MT/s         | 1        | 2.44%   |
| Crucial RAM CT8G4DFRA32A.C8FN 8GB DIMM DDR4 3200MT/s    | 1        | 2.44%   |
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2400MT/s    | 1        | 2.44%   |
| Corsair RAM CMX4GX3M2A1333C8 2GB DIMM DDR3 1333MT/s     | 1        | 2.44%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s   | 1        | 2.44%   |
| Corsair RAM CMK8GX4M1Z3200C16 8GB DIMM DDR4 3200MT/s    | 1        | 2.44%   |
| Corsair RAM CMK64GX4M4A2666C16 16GB DIMM DDR4 2667MT/s  | 1        | 2.44%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s  | 1        | 2.44%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s  | 1        | 2.44%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 1        | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 21       | 63.64%  |
| DDR3    | 10       | 30.3%   |
| DDR2    | 1        | 3.03%   |
| Unknown | 1        | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 28       | 84.85%  |
| SODIMM | 4        | 12.12%  |
| RIMM   | 1        | 3.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 14       | 37.84%  |
| 32768 | 6        | 16.22%  |
| 16384 | 6        | 16.22%  |
| 4096  | 6        | 16.22%  |
| 2048  | 3        | 8.11%   |
| 1024  | 2        | 5.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 9        | 24.32%  |
| 2667  | 4        | 10.81%  |
| 2400  | 3        | 8.11%   |
| 2133  | 3        | 8.11%   |
| 1600  | 3        | 8.11%   |
| 1333  | 3        | 8.11%   |
| 667   | 2        | 5.41%   |
| 3733  | 1        | 2.7%    |
| 3666  | 1        | 2.7%    |
| 3600  | 1        | 2.7%    |
| 3400  | 1        | 2.7%    |
| 3333  | 1        | 2.7%    |
| 3100  | 1        | 2.7%    |
| 3000  | 1        | 2.7%    |
| 2200  | 1        | 2.7%    |
| 1866  | 1        | 2.7%    |
| 1800  | 1        | 2.7%    |

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
| Huawei UVC Camera                          | 1        | 14.29%  |
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
| 0     | 34       | 70.83%  |
| 1     | 10       | 20.83%  |
| 2     | 3        | 6.25%   |
| 3     | 1        | 2.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Net/wireless        | 5        | 29.41%  |
| Graphics card       | 4        | 23.53%  |
| Unassigned class    | 2        | 11.76%  |
| Storage/raid        | 1        | 5.88%   |
| Storage             | 1        | 5.88%   |
| Sound               | 1        | 5.88%   |
| Net/ethernet        | 1        | 5.88%   |
| Firewire controller | 1        | 5.88%   |
| Dvb card            | 1        | 5.88%   |

