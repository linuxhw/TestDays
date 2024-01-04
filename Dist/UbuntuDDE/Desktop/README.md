UbuntuDDE - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for UbuntuDDE.

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

Total: 54

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| Fujitsu       | D3062-A1 S26361-D3062-A1 | [c2dc388cd3](https://linux-hardware.org/?probe=c2dc388cd3) | Oct 25, 2023 |
| ASRock        | B560M-C                  | [c8d399d95d](https://linux-hardware.org/?probe=c8d399d95d) | Jul 20, 2023 |
| ASUSTek       | P8Z68-V LX               | [7153762b68](https://linux-hardware.org/?probe=7153762b68) | Nov 23, 2022 |
| ASUSTek       | H81I-PLUS                | [d5d3ad3491](https://linux-hardware.org/?probe=d5d3ad3491) | Oct 18, 2022 |
| MSI           | A320M PRO-M2 V2          | [7a3fa3e4a4](https://linux-hardware.org/?probe=7a3fa3e4a4) | Apr 16, 2022 |
| ECS           | Nettle2                  | [7de5975b89](https://linux-hardware.org/?probe=7de5975b89) | Mar 20, 2022 |
| ECS           | Nettle2                  | [cd98e7180c](https://linux-hardware.org/?probe=cd98e7180c) | Feb 12, 2022 |
| Gigabyte      | F2A55M-HD2               | [e8b8cb1cf7](https://linux-hardware.org/?probe=e8b8cb1cf7) | Sep 01, 2021 |
| Acer          | F672CR R01-B1            | [652ed79c86](https://linux-hardware.org/?probe=652ed79c86) | May 29, 2021 |
| Acer          | F672CR R01-B1            | [bd8067c8cf](https://linux-hardware.org/?probe=bd8067c8cf) | May 16, 2021 |
| Intel         | D33217CK G76541-302      | [1db9d29c38](https://linux-hardware.org/?probe=1db9d29c38) | Apr 19, 2021 |
| MSI           | G41M-S01                 | [fae5d5a101](https://linux-hardware.org/?probe=fae5d5a101) | Mar 31, 2021 |
| ASUSTek       | PRIME B450M-A II         | [292671b8bb](https://linux-hardware.org/?probe=292671b8bb) | Mar 26, 2021 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1 | [826729feac](https://linux-hardware.org/?probe=826729feac) | Feb 07, 2021 |
| MSI           | G41M-P26                 | [2b503c1c1d](https://linux-hardware.org/?probe=2b503c1c1d) | Jan 07, 2021 |
| BANGHO        | MZBSWAP-00               | [c0b3c1bae1](https://linux-hardware.org/?probe=c0b3c1bae1) | Nov 13, 2020 |
| Intel         | DQ45CB AAE30148-207      | [51733fd6ab](https://linux-hardware.org/?probe=51733fd6ab) | Nov 02, 2020 |
| MSI           | Z87-G43                  | [055e733f90](https://linux-hardware.org/?probe=055e733f90) | Nov 01, 2020 |
| Gigabyte      | GA-970A-D3               | [8f5f5aba10](https://linux-hardware.org/?probe=8f5f5aba10) | Oct 31, 2020 |
| Dell          | 0GTK4K A02               | [5e81f45485](https://linux-hardware.org/?probe=5e81f45485) | Oct 09, 2020 |
| Dell          | 0GTK4K A02               | [83adab7085](https://linux-hardware.org/?probe=83adab7085) | Oct 08, 2020 |
| ASUSTek       | P5G41C-M LX              | [1865dce38e](https://linux-hardware.org/?probe=1865dce38e) | Sep 24, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING  | [006c313ab9](https://linux-hardware.org/?probe=006c313ab9) | Sep 13, 2020 |
| Unknown       | SKYBAY                   | [8abc37bdcc](https://linux-hardware.org/?probe=8abc37bdcc) | Sep 06, 2020 |
| ASUSTek       | P5G41C-M LX              | [ae07f658e9](https://linux-hardware.org/?probe=ae07f658e9) | Sep 04, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z    | [5779a0397d](https://linux-hardware.org/?probe=5779a0397d) | Aug 26, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE      | [21af10b11c](https://linux-hardware.org/?probe=21af10b11c) | Jul 03, 2020 |
| ASUSTek       | H61M-D                   | [ef9bd4541a](https://linux-hardware.org/?probe=ef9bd4541a) | Jun 27, 2020 |
| ASUSTek       | H61M-D                   | [d9b6cb6c0b](https://linux-hardware.org/?probe=d9b6cb6c0b) | Jun 27, 2020 |
| ASUSTek       | H110I-PLUS               | [75682d8cbd](https://linux-hardware.org/?probe=75682d8cbd) | Jun 23, 2020 |
| ASUSTek       | H110I-PLUS               | [ffccba3844](https://linux-hardware.org/?probe=ffccba3844) | Jun 23, 2020 |
| Intel         | B75                      | [cbfecb01d1](https://linux-hardware.org/?probe=cbfecb01d1) | Jun 14, 2020 |
| Dell          | 0H4VK7 A01               | [0d7b561033](https://linux-hardware.org/?probe=0d7b561033) | May 24, 2020 |
| Dell          | 0H4VK7 A01               | [6c8989e6c6](https://linux-hardware.org/?probe=6c8989e6c6) | May 24, 2020 |
| Gigabyte      | MQLP7AP-00               | [7ec29f824e](https://linux-hardware.org/?probe=7ec29f824e) | May 16, 2020 |
| ASUSTek       | P6X58D-E                 | [5a566d4992](https://linux-hardware.org/?probe=5a566d4992) | May 12, 2020 |
| HP            | 8433 11                  | [e302f75c67](https://linux-hardware.org/?probe=e302f75c67) | May 12, 2020 |
| MSI           | 970 GAMING               | [ad8e2069c8](https://linux-hardware.org/?probe=ad8e2069c8) | May 11, 2020 |
| ASUSTek       | A68HM-PLUS               | [2a575bf9f0](https://linux-hardware.org/?probe=2a575bf9f0) | May 11, 2020 |
| ASUSTek       | A68HM-PLUS               | [0b99805df1](https://linux-hardware.org/?probe=0b99805df1) | May 09, 2020 |
| ASUSTek       | A68HM-PLUS               | [628255b107](https://linux-hardware.org/?probe=628255b107) | May 08, 2020 |
| ASUSTek       | A68HM-PLUS               | [6f59de9a48](https://linux-hardware.org/?probe=6f59de9a48) | May 08, 2020 |
| MSI           | G41M-P25                 | [e1592a090c](https://linux-hardware.org/?probe=e1592a090c) | May 08, 2020 |
| HP            | 3397                     | [3e224cf71e](https://linux-hardware.org/?probe=3e224cf71e) | May 07, 2020 |
| Medion        | MS-7848                  | [6c60cef00e](https://linux-hardware.org/?probe=6c60cef00e) | May 06, 2020 |
| Gigabyte      | GA-MA74GM-S2             | [7580875f9d](https://linux-hardware.org/?probe=7580875f9d) | May 06, 2020 |
| HP            | 3397                     | [d5693de014](https://linux-hardware.org/?probe=d5693de014) | May 06, 2020 |
| Dell          | 0FM586                   | [0d813a7cc7](https://linux-hardware.org/?probe=0d813a7cc7) | Apr 27, 2020 |
| ASUSTek       | P5KPL-AM                 | [76eb877783](https://linux-hardware.org/?probe=76eb877783) | Apr 26, 2020 |
| ASRock        | AM2NF6G-VSTA             | [e5ec721a65](https://linux-hardware.org/?probe=e5ec721a65) | Apr 23, 2020 |
| eMachines     | WMCP61M                  | [0d3017399b](https://linux-hardware.org/?probe=0d3017399b) | Apr 16, 2020 |
| ASRock        | X370 Gaming K4           | [76bbb57b26](https://linux-hardware.org/?probe=76bbb57b26) | Apr 11, 2020 |
| ASUSTek       | PRIME B360M-A            | [ed6853b51d](https://linux-hardware.org/?probe=ed6853b51d) | Feb 28, 2020 |
| Gigabyte      | B75M-D3H                 | [d33696bceb](https://linux-hardware.org/?probe=d33696bceb) | Nov 24, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| UbuntuDDE 20.04 | 29       | 70.73%  |
| UbuntuDDE 22.04 | 3        | 7.32%   |
| UbuntuDDE 20.10 | 3        | 7.32%   |
| UbuntuDDE 18.04 | 3        | 7.32%   |
| UbuntuDDE 21.10 | 2        | 4.88%   |
| UbuntuDDE 21.04 | 1        | 2.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| UbuntuDDE | 41       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.4.0-29-generic    | 9        | 21.43%  |
| 5.4.0-42-generic    | 3        | 7.14%   |
| 5.4.0-21-generic    | 3        | 7.14%   |
| 5.4.0-48-generic    | 2        | 4.76%   |
| 6.2.0-35-generic    | 1        | 2.38%   |
| 5.8.0-53-generic    | 1        | 2.38%   |
| 5.8.0-50-generic    | 1        | 2.38%   |
| 5.8.0-48-generic    | 1        | 2.38%   |
| 5.8.0-41-generic    | 1        | 2.38%   |
| 5.8.0-33-generic    | 1        | 2.38%   |
| 5.4.0-53-generic    | 1        | 2.38%   |
| 5.4.0-52-generic    | 1        | 2.38%   |
| 5.4.0-45-generic    | 1        | 2.38%   |
| 5.4.0-40-lowlatency | 1        | 2.38%   |
| 5.4.0-39-generic    | 1        | 2.38%   |
| 5.4.0-37-generic    | 1        | 2.38%   |
| 5.4.0-31-generic    | 1        | 2.38%   |
| 5.4.0-26-generic    | 1        | 2.38%   |
| 5.4.0-24-generic    | 1        | 2.38%   |
| 5.3.0-40-generic    | 1        | 2.38%   |
| 5.19.0-46-generic   | 1        | 2.38%   |
| 5.15.0-53-generic   | 1        | 2.38%   |
| 5.15.0-50-generic   | 1        | 2.38%   |
| 5.13.0-39-generic   | 1        | 2.38%   |
| 5.13.0-35-generic   | 1        | 2.38%   |
| 5.13.0-28-generic   | 1        | 2.38%   |
| 5.11.0-31-generic   | 1        | 2.38%   |
| 5.0.0-36-generic    | 1        | 2.38%   |
| 4.15.0-122-generic  | 1        | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 26       | 63.41%  |
| 5.8.0   | 5        | 12.2%   |
| 5.15.0  | 2        | 4.88%   |
| 5.13.0  | 2        | 4.88%   |
| 6.2.0   | 1        | 2.44%   |
| 5.3.0   | 1        | 2.44%   |
| 5.19.0  | 1        | 2.44%   |
| 5.11.0  | 1        | 2.44%   |
| 5.0.0   | 1        | 2.44%   |
| 4.15.0  | 1        | 2.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 26       | 63.41%  |
| 5.8     | 5        | 12.2%   |
| 5.15    | 2        | 4.88%   |
| 5.13    | 2        | 4.88%   |
| 6.2     | 1        | 2.44%   |
| 5.3     | 1        | 2.44%   |
| 5.19    | 1        | 2.44%   |
| 5.11    | 1        | 2.44%   |
| 5.0     | 1        | 2.44%   |
| 4.15    | 1        | 2.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 41       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Deepin | 41       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 41       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28       | 68.29%  |
| TDM     | 5        | 12.2%   |
| LightDM | 5        | 12.2%   |
| GDM     | 2        | 4.88%   |
| GDM3    | 1        | 2.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 16       | 39.02%  |
| pt_BR | 4        | 9.76%   |
| en_GB | 3        | 7.32%   |
| fr_FR | 2        | 4.88%   |
| fi_FI | 2        | 4.88%   |
| de_DE | 2        | 4.88%   |
| C     | 2        | 4.88%   |
| uk_UA | 1        | 2.44%   |
| th_TH | 1        | 2.44%   |
| ru_RU | 1        | 2.44%   |
| pl_PL | 1        | 2.44%   |
| it_IT | 1        | 2.44%   |
| es_ES | 1        | 2.44%   |
| es_CR | 1        | 2.44%   |
| es_AR | 1        | 2.44%   |
| en_CA | 1        | 2.44%   |
| de_CH | 1        | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 23       | 56.1%   |
| EFI  | 18       | 43.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 36       | 87.8%   |
| Tmpfs   | 2        | 4.88%   |
| Overlay | 1        | 2.44%   |
| Btrfs   | 1        | 2.44%   |
| Unknown | 1        | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 70.73%  |
| GPT     | 9        | 21.95%  |
| MBR     | 3        | 7.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 82.93%  |
| Yes       | 7        | 17.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 54.76%  |
| Yes       | 19       | 45.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 26.83%  |
| MSI                 | 6        | 14.63%  |
| Gigabyte Technology | 5        | 12.2%   |
| Intel               | 3        | 7.32%   |
| Hewlett-Packard     | 3        | 7.32%   |
| Dell                | 3        | 7.32%   |
| ASRock              | 2        | 4.88%   |
| Medion              | 1        | 2.44%   |
| Fujitsu Siemens     | 1        | 2.44%   |
| Fujitsu             | 1        | 2.44%   |
| eMachines           | 1        | 2.44%   |
| ECS                 | 1        | 2.44%   |
| BANGHO              | 1        | 2.44%   |
| Acer                | 1        | 2.44%   |
| Unknown             | 1        | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| MSI MS-7592                   | 3        | 7.32%   |
| MSI MS-7B84                   | 1        | 2.44%   |
| MSI MS-7816                   | 1        | 2.44%   |
| MSI MS-7693                   | 1        | 2.44%   |
| Medion MS-7848                | 1        | 2.44%   |
| Intel DQ45CB AAE30148-207     | 1        | 2.44%   |
| Intel D33217CK G76541-302     | 1        | 2.44%   |
| Intel B75                     | 1        | 2.44%   |
| HP Pavilion Desktop 590-p0xxx | 1        | 2.44%   |
| HP Compaq Elite 8300 SFF      | 1        | 2.44%   |
| HP Compaq Elite 8300 MT       | 1        | 2.44%   |
| Gigabyte GB-BXi7-5500         | 1        | 2.44%   |
| Gigabyte GA-MA74GM-S2         | 1        | 2.44%   |
| Gigabyte GA-970A-D3           | 1        | 2.44%   |
| Gigabyte F2A55M-HD2           | 1        | 2.44%   |
| Gigabyte B75M-D3H             | 1        | 2.44%   |
| Fujitsu Siemens ESPRIMO P5730 | 1        | 2.44%   |
| Fujitsu ESPRIMO E900          | 1        | 2.44%   |
| eMachines EL1333G             | 1        | 2.44%   |
| ECS GL307AA-ABA a6123w        | 1        | 2.44%   |
| Dell PowerEdge T40            | 1        | 2.44%   |
| Dell Inspiron 530             | 1        | 2.44%   |
| Dell Inspiron 3670            | 1        | 2.44%   |
| BANGHO CUBIC                  | 1        | 2.44%   |
| ASUS PRIME B450M-A II         | 1        | 2.44%   |
| ASUS PRIME B360M-A            | 1        | 2.44%   |
| ASUS P8Z68-V LX               | 1        | 2.44%   |
| ASUS P6X58D-E                 | 1        | 2.44%   |
| ASUS P5KPL-AM                 | 1        | 2.44%   |
| ASUS P5G41C-M LX              | 1        | 2.44%   |
| ASUS H61M-D                   | 1        | 2.44%   |
| ASUS D820MT_D820SF_BM3CE      | 1        | 2.44%   |
| ASUS CROSSHAIR V FORMULA-Z    | 1        | 2.44%   |
| ASUS All Series               | 1        | 2.44%   |
| ASUS A68HM-PLUS               | 1        | 2.44%   |
| ASRock X370 Gaming K4         | 1        | 2.44%   |
| ASRock B560M-C                | 1        | 2.44%   |
| Acer ASM1610/VTM261           | 1        | 2.44%   |
| Unknown                       | 1        | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| MSI MS-7592             | 3        | 7.32%   |
| HP Compaq               | 2        | 4.88%   |
| Dell Inspiron           | 2        | 4.88%   |
| ASUS PRIME              | 2        | 4.88%   |
| MSI MS-7B84             | 1        | 2.44%   |
| MSI MS-7816             | 1        | 2.44%   |
| MSI MS-7693             | 1        | 2.44%   |
| Medion MS-7848          | 1        | 2.44%   |
| Intel DQ45CB            | 1        | 2.44%   |
| Intel D33217CK          | 1        | 2.44%   |
| Intel B75               | 1        | 2.44%   |
| HP Pavilion             | 1        | 2.44%   |
| Gigabyte GB-BXi7-5500   | 1        | 2.44%   |
| Gigabyte GA-MA74GM-S2   | 1        | 2.44%   |
| Gigabyte GA-970A-D3     | 1        | 2.44%   |
| Gigabyte F2A55M-HD2     | 1        | 2.44%   |
| Gigabyte B75M-D3H       | 1        | 2.44%   |
| Fujitsu Siemens ESPRIMO | 1        | 2.44%   |
| Fujitsu ESPRIMO         | 1        | 2.44%   |
| eMachines EL1333G       | 1        | 2.44%   |
| ECS GL307AA-ABA         | 1        | 2.44%   |
| Dell PowerEdge          | 1        | 2.44%   |
| BANGHO CUBIC            | 1        | 2.44%   |
| ASUS P8Z68-V            | 1        | 2.44%   |
| ASUS P6X58D-E           | 1        | 2.44%   |
| ASUS P5KPL-AM           | 1        | 2.44%   |
| ASUS P5G41C-M           | 1        | 2.44%   |
| ASUS H61M-D             | 1        | 2.44%   |
| ASUS D820MT             | 1        | 2.44%   |
| ASUS CROSSHAIR          | 1        | 2.44%   |
| ASUS All                | 1        | 2.44%   |
| ASUS A68HM-PLUS         | 1        | 2.44%   |
| ASRock X370             | 1        | 2.44%   |
| ASRock B560M-C          | 1        | 2.44%   |
| Acer ASM1610            | 1        | 2.44%   |
| Unknown                 | 1        | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 5        | 12.2%   |
| 2011 | 5        | 12.2%   |
| 2018 | 4        | 9.76%   |
| 2012 | 4        | 9.76%   |
| 2008 | 4        | 9.76%   |
| 2016 | 3        | 7.32%   |
| 2014 | 3        | 7.32%   |
| 2010 | 3        | 7.32%   |
| 2020 | 2        | 4.88%   |
| 2019 | 2        | 4.88%   |
| 2009 | 2        | 4.88%   |
| 2007 | 2        | 4.88%   |
| 2021 | 1        | 2.44%   |
| 2015 | 1        | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 41       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 40       | 97.56%  |
| Enabled  | 1        | 2.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 9        | 21.95%  |
| 8.01-16.0   | 9        | 21.95%  |
| 3.01-4.0    | 8        | 19.51%  |
| 16.01-24.0  | 8        | 19.51%  |
| 32.01-64.0  | 3        | 7.32%   |
| 2.01-3.0    | 2        | 4.88%   |
| 24.01-32.0  | 1        | 2.44%   |
| 64.01-256.0 | 1        | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 17       | 41.46%  |
| 2.01-3.0 | 15       | 36.59%  |
| 4.01-8.0 | 5        | 12.2%   |
| 3.01-4.0 | 2        | 4.88%   |
| 0.51-1.0 | 2        | 4.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 46.34%  |
| 1      | 16       | 39.02%  |
| 3      | 6        | 14.63%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 21       | 51.22%  |
| No        | 20       | 48.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 39       | 95.12%  |
| No        | 2        | 4.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 51.22%  |
| Yes       | 20       | 48.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 60.98%  |
| Yes       | 16       | 39.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 8        | 19.51%  |
| UK         | 4        | 9.76%   |
| Brazil     | 4        | 9.76%   |
| Germany    | 3        | 7.32%   |
| Argentina  | 3        | 7.32%   |
| Portugal   | 2        | 4.88%   |
| France     | 2        | 4.88%   |
| Finland    | 2        | 4.88%   |
| Ukraine    | 1        | 2.44%   |
| Thailand   | 1        | 2.44%   |
| Sweden     | 1        | 2.44%   |
| Russia     | 1        | 2.44%   |
| Poland     | 1        | 2.44%   |
| Mexico     | 1        | 2.44%   |
| Luxembourg | 1        | 2.44%   |
| Italy      | 1        | 2.44%   |
| Indonesia  | 1        | 2.44%   |
| Costa Rica | 1        | 2.44%   |
| Canada     | 1        | 2.44%   |
| Belgium    | 1        | 2.44%   |
| Austria    | 1        | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Helsinki              | 2        | 4.88%   |
| Yogyakarta            | 1        | 2.44%   |
| Tomah                 | 1        | 2.44%   |
| Słubice              | 1        | 2.44%   |
| St Petersburg         | 1        | 2.44%   |
| Sao Paulo             | 1        | 2.44%   |
| Sao Bernardo do Campo | 1        | 2.44%   |
| Sankt Pölten         | 1        | 2.44%   |
| San Telmo             | 1        | 2.44%   |
| Rosario               | 1        | 2.44%   |
| Rome                  | 1        | 2.44%   |
| Rodgau                | 1        | 2.44%   |
| Pontpierre            | 1        | 2.44%   |
| Oakville              | 1        | 2.44%   |
| Newburgh              | 1        | 2.44%   |
| Monterrey             | 1        | 2.44%   |
| Monte Carmelo         | 1        | 2.44%   |
| Molesey               | 1        | 2.44%   |
| Milan                 | 1        | 2.44%   |
| Lviv                  | 1        | 2.44%   |
| Lisbon                | 1        | 2.44%   |
| Las Vegas             | 1        | 2.44%   |
| La Louvière          | 1        | 2.44%   |
| Krefeld               | 1        | 2.44%   |
| Heredia               | 1        | 2.44%   |
| Enskede-Arsta-Vantoer | 1        | 2.44%   |
| Derby                 | 1        | 2.44%   |
| Dayton                | 1        | 2.44%   |
| Curitiba              | 1        | 2.44%   |
| Colorado Springs      | 1        | 2.44%   |
| Colmar                | 1        | 2.44%   |
| Buenos Aires          | 1        | 2.44%   |
| Bristol               | 1        | 2.44%   |
| Bourgoin-Jallieu      | 1        | 2.44%   |
| Bermondsey            | 1        | 2.44%   |
| Berlin                | 1        | 2.44%   |
| Bend                  | 1        | 2.44%   |
| Beja                  | 1        | 2.44%   |
| Bang Bon              | 1        | 2.44%   |
| Auburn                | 1        | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 16     | 22.58%  |
| WDC                 | 10       | 15     | 16.13%  |
| Samsung Electronics | 9        | 9      | 14.52%  |
| Toshiba             | 7        | 7      | 11.29%  |
| Kingston            | 5        | 5      | 8.06%   |
| Hitachi             | 3        | 4      | 4.84%   |
| Crucial             | 3        | 3      | 4.84%   |
| Vaseky              | 1        | 1      | 1.61%   |
| SanDisk             | 1        | 1      | 1.61%   |
| PNY                 | 1        | 2      | 1.61%   |
| Plextor             | 1        | 1      | 1.61%   |
| Maxtor              | 1        | 1      | 1.61%   |
| Leven               | 1        | 1      | 1.61%   |
| KingFast            | 1        | 1      | 1.61%   |
| JMicron Technology  | 1        | 1      | 1.61%   |
| Integral            | 1        | 1      | 1.61%   |
| GOODRAM             | 1        | 1      | 1.61%   |
| ADATA Technology    | 1        | 1      | 1.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB             | 4        | 6.06%   |
| Seagate ST1000DM010-2EP102 1TB     | 3        | 4.55%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 2        | 3.03%   |
| Samsung SSD 850 EVO 250GB          | 2        | 3.03%   |
| WDC WDBNCE2500PNC 250GB SSD        | 1        | 1.52%   |
| WDC WD7501AALS-75J7B0 752GB        | 1        | 1.52%   |
| WDC WD60EDAZ-11BMZB0 6TB           | 1        | 1.52%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 1.52%   |
| WDC WD3200AAJS-00B4A0 320GB        | 1        | 1.52%   |
| WDC WD30EZRX-00MMMB0 3TB           | 1        | 1.52%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1        | 1.52%   |
| WDC WD2500AAKX-001CA0 250GB        | 1        | 1.52%   |
| WDC WD2002FAEX-007BA0 2TB          | 1        | 1.52%   |
| WDC WD1003FZEX-00K3CA0 1TB         | 1        | 1.52%   |
| Vaseky V800/128G 120GB SSD         | 1        | 1.52%   |
| Toshiba THNSFC128GBSJ SSD          | 1        | 1.52%   |
| Toshiba MQ01ABD100 1TB             | 1        | 1.52%   |
| Toshiba MK3275GSX 320GB            | 1        | 1.52%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1.52%   |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 1.52%   |
| Seagate ST3500630AS 500GB          | 1        | 1.52%   |
| Seagate ST3500413AS 500GB          | 1        | 1.52%   |
| Seagate ST3500312CS 500GB          | 1        | 1.52%   |
| Seagate ST3320418AS 320GB          | 1        | 1.52%   |
| Seagate ST3250820AS 250GB          | 1        | 1.52%   |
| Seagate ST31000524AS 1TB           | 1        | 1.52%   |
| Seagate ST2000DM008-2FR102 2TB     | 1        | 1.52%   |
| Seagate ST2000DM001-9YN164 2TB     | 1        | 1.52%   |
| Seagate ST1000VT000 HN-M101MBB 1TB | 1        | 1.52%   |
| Seagate ST1000DM003-1CH162 1TB     | 1        | 1.52%   |
| SanDisk SSD PLUS 240 GB            | 1        | 1.52%   |
| Samsung SSD 850 EVO 500GB          | 1        | 1.52%   |
| Samsung SSD 850 EVO 1TB            | 1        | 1.52%   |
| Samsung NVMe SSD Drive 512GB       | 1        | 1.52%   |
| Samsung HM250HI 250GB              | 1        | 1.52%   |
| Samsung HD161HJ 160GB              | 1        | 1.52%   |
| Samsung HD103SJ 1TB                | 1        | 1.52%   |
| Samsung HD080HJ 80GB               | 1        | 1.52%   |
| PNY CS900 1TB SSD                  | 1        | 1.52%   |
| Plextor PX-128M5M 128GB SSD        | 1        | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 16     | 37.84%  |
| WDC                 | 9        | 11     | 24.32%  |
| Toshiba             | 6        | 6      | 16.22%  |
| Samsung Electronics | 4        | 4      | 10.81%  |
| Hitachi             | 3        | 4      | 8.11%   |
| Maxtor              | 1        | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 4      | 17.39%  |
| Kingston            | 4        | 4      | 17.39%  |
| WDC                 | 3        | 4      | 13.04%  |
| Crucial             | 3        | 3      | 13.04%  |
| Vaseky              | 1        | 1      | 4.35%   |
| Toshiba             | 1        | 1      | 4.35%   |
| SanDisk             | 1        | 1      | 4.35%   |
| PNY                 | 1        | 2      | 4.35%   |
| Plextor             | 1        | 1      | 4.35%   |
| Leven               | 1        | 1      | 4.35%   |
| KingFast            | 1        | 1      | 4.35%   |
| Integral            | 1        | 1      | 4.35%   |
| GOODRAM             | 1        | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 32       | 42     | 58.18%  |
| SSD     | 19       | 25     | 34.55%  |
| NVMe    | 3        | 3      | 5.45%   |
| Unknown | 1        | 1      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 40       | 67     | 90.91%  |
| NVMe | 3        | 3      | 6.82%   |
| SAS  | 1        | 1      | 2.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 27       | 37     | 51.92%  |
| 0.51-1.0   | 18       | 21     | 34.62%  |
| 1.01-2.0   | 3        | 3      | 5.77%   |
| 2.01-3.0   | 2        | 3      | 3.85%   |
| 3.01-4.0   | 1        | 1      | 1.92%   |
| 4.01-10.0  | 1        | 2      | 1.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 14       | 34.15%  |
| 1001-2000      | 8        | 19.51%  |
| 251-500        | 6        | 14.63%  |
| 501-1000       | 6        | 14.63%  |
| More than 3000 | 2        | 4.88%   |
| 21-50          | 2        | 4.88%   |
| 51-100         | 2        | 4.88%   |
| Unknown        | 1        | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 22       | 53.66%  |
| 101-250   | 6        | 14.63%  |
| 251-500   | 4        | 9.76%   |
| 21-50     | 2        | 4.88%   |
| 1001-2000 | 2        | 4.88%   |
| 501-1000  | 2        | 4.88%   |
| 51-100    | 2        | 4.88%   |
| Unknown   | 1        | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| Seagate ST3320418AS 320GB     | 1        | 1      | 50%     |
| Hitachi HTS543232A7A384 320GB | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 50%     |
| Hitachi | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 50%     |
| Hitachi | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 100%    |

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
| Detected | 32       | 56     | 74.42%  |
| Works    | 9        | 13     | 20.93%  |
| Malfunc  | 2        | 2      | 4.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 28       | 57.14%  |
| AMD                              | 10       | 20.41%  |
| Samsung Electronics              | 3        | 6.12%   |
| Nvidia                           | 2        | 4.08%   |
| ASMedia Technology               | 2        | 4.08%   |
| Silicon Integrated Systems [SiS] | 1        | 2.04%   |
| Marvell Technology Group         | 1        | 2.04%   |
| Kingston Technology Company      | 1        | 2.04%   |
| ADATA Technology                 | 1        | 2.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5        | 7.25%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5        | 7.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4        | 5.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3        | 4.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3        | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3        | 4.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 2.9%    |
| Nvidia MCP61 SATA Controller                                                     | 2        | 2.9%    |
| Nvidia MCP61 IDE                                                                 | 2        | 2.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2        | 2.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 2.9%    |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                       | 2        | 2.9%    |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                       | 2        | 2.9%    |
| Intel 4 Series Chipset PT IDER Controller                                        | 2        | 2.9%    |
| ASMedia ASM1062 Serial ATA Controller                                            | 2        | 2.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2        | 2.9%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1        | 1.45%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1        | 1.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1        | 1.45%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                       | 1        | 1.45%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                         | 1        | 1.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1        | 1.45%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1        | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 1.45%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 1.45%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1        | 1.45%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 1        | 1.45%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 1        | 1.45%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 1        | 1.45%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 1        | 1.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1        | 1.45%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1        | 1.45%   |
| AMD X370 Series Chipset SATA Controller                                          | 1        | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [RAID5 mode]                               | 1        | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1        | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1        | 1.45%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1        | 1.45%   |
| AMD FCH SATA Controller D                                                        | 1        | 1.45%   |
| AMD FCH IDE Controller                                                           | 1        | 1.45%   |
| AMD 400 Series Chipset SATA Controller                                           | 1        | 1.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 26       | 54.17%  |
| IDE  | 15       | 31.25%  |
| NVMe | 5        | 10.42%  |
| RAID | 2        | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 29       | 70.73%  |
| AMD    | 12       | 29.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i3-3220 CPU @ 3.30GHz                | 2        | 4.88%   |
| Intel Xeon E-2224G CPU @ 3.50GHz                | 1        | 2.44%   |
| Intel Xeon CPU E5450 @ 3.00GHz                  | 1        | 2.44%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz     | 1        | 2.44%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 1        | 2.44%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz          | 1        | 2.44%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz              | 1        | 2.44%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 2.44%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1        | 2.44%   |
| Intel Core i7-2700K CPU @ 3.50GHz               | 1        | 2.44%   |
| Intel Core i7 CPU 950 @ 3.07GHz                 | 1        | 2.44%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1        | 2.44%   |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1        | 2.44%   |
| Intel Core i5-4670K CPU @ 3.40GHz               | 1        | 2.44%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1        | 2.44%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 1        | 2.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 2.44%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 1        | 2.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 2.44%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1        | 2.44%   |
| Intel Core i3-3217U CPU @ 1.80GHz               | 1        | 2.44%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz           | 1        | 2.44%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz           | 1        | 2.44%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz           | 1        | 2.44%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz            | 1        | 2.44%   |
| Intel Core 2 CPU 6320 @ 1.86GHz                 | 1        | 2.44%   |
| Intel Celeron CPU N3000 @ 1.04GHz               | 1        | 2.44%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz         | 1        | 2.44%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 1        | 2.44%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 2.44%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1        | 2.44%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 1        | 2.44%   |
| AMD Phenom II X6 1055T Processor                | 1        | 2.44%   |
| AMD Phenom 9650 Quad-Core Processor             | 1        | 2.44%   |
| AMD FX-9590 Eight-Core Processor                | 1        | 2.44%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 2.44%   |
| AMD Athlon Dual Core Processor 4850e            | 1        | 2.44%   |
| AMD Athlon 64 X2 Dual Core Processor 4400+      | 1        | 2.44%   |
| AMD A4-4000 APU with Radeon HD Graphics         | 1        | 2.44%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 8        | 19.51%  |
| Intel Core i7           | 5        | 12.2%   |
| Intel Core i3           | 4        | 9.76%   |
| Intel Core 2 Quad       | 3        | 7.32%   |
| AMD Ryzen 5             | 3        | 7.32%   |
| Intel Xeon              | 2        | 4.88%   |
| Intel Pentium Dual-Core | 2        | 4.88%   |
| AMD FX                  | 2        | 4.88%   |
| Other                   | 1        | 2.44%   |
| Intel Pentium Dual      | 1        | 2.44%   |
| Intel Core 2 Duo        | 1        | 2.44%   |
| Intel Core 2            | 1        | 2.44%   |
| Intel Celeron           | 1        | 2.44%   |
| AMD Ryzen 7             | 1        | 2.44%   |
| AMD Phenom II X6        | 1        | 2.44%   |
| AMD Phenom              | 1        | 2.44%   |
| AMD Athlon Dual Core    | 1        | 2.44%   |
| AMD Athlon 64 X2        | 1        | 2.44%   |
| AMD A4                  | 1        | 2.44%   |
| AMD A10                 | 1        | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 21       | 51.22%  |
| 2      | 13       | 31.71%  |
| 6      | 5        | 12.2%   |
| 8      | 1        | 2.44%   |
| 1      | 1        | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 41       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 60.98%  |
| 2      | 16       | 39.02%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 41       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 21.95%  |
| 0x306a9    | 6        | 14.63%  |
| 0x1067a    | 4        | 9.76%   |
| 0x306c3    | 2        | 4.88%   |
| 0x10677    | 2        | 4.88%   |
| 0x06000852 | 2        | 4.88%   |
| 0x906ed    | 1        | 2.44%   |
| 0x906eb    | 1        | 2.44%   |
| 0x906ea    | 1        | 2.44%   |
| 0x6fd      | 1        | 2.44%   |
| 0x6f6      | 1        | 2.44%   |
| 0x506e3    | 1        | 2.44%   |
| 0x406c3    | 1        | 2.44%   |
| 0x306d4    | 1        | 2.44%   |
| 0x206a7    | 1        | 2.44%   |
| 0x106a5    | 1        | 2.44%   |
| 0x08701021 | 1        | 2.44%   |
| 0x08101016 | 1        | 2.44%   |
| 0x08001138 | 1        | 2.44%   |
| 0x06003106 | 1        | 2.44%   |
| 0x010000dc | 1        | 2.44%   |
| 0x01000083 | 1        | 2.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 6        | 14.63%  |
| IvyBridge   | 6        | 14.63%  |
| KabyLake    | 4        | 9.76%   |
| Piledriver  | 3        | 7.32%   |
| Haswell     | 3        | 7.32%   |
| Core        | 3        | 7.32%   |
| Zen         | 2        | 4.88%   |
| SandyBridge | 2        | 4.88%   |
| K8 Hammer   | 2        | 4.88%   |
| K10         | 2        | 4.88%   |
| Zen+        | 1        | 2.44%   |
| Zen 2       | 1        | 2.44%   |
| Steamroller | 1        | 2.44%   |
| Skylake     | 1        | 2.44%   |
| Silvermont  | 1        | 2.44%   |
| Nehalem     | 1        | 2.44%   |
| Broadwell   | 1        | 2.44%   |
| Unknown     | 1        | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 18       | 41.86%  |
| Intel                            | 12       | 27.91%  |
| AMD                              | 12       | 27.91%  |
| Silicon Integrated Systems [SiS] | 1        | 2.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3        | 6.82%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 6.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 4.55%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 4.55%   |
| AMD RV770 [Radeon HD 4850]                                                               | 2        | 4.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 4.55%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 4.55%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1        | 2.27%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 2.27%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 2.27%   |
| Nvidia GT215 [GeForce GT 320]                                                            | 1        | 2.27%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1        | 2.27%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1        | 2.27%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 2.27%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                                        | 1        | 2.27%   |
| Nvidia GF119 [GeForce GT 705]                                                            | 1        | 2.27%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1        | 2.27%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 2.27%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1        | 2.27%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 2.27%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 2.27%   |
| Intel HD Graphics 630                                                                    | 1        | 2.27%   |
| Intel HD Graphics 5500                                                                   | 1        | 2.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                               | 1        | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1        | 2.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 2.27%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 1        | 2.27%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 1        | 2.27%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 2.27%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 2.27%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 1        | 2.27%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1        | 2.27%   |
| AMD Barts PRO [Radeon HD 6850]                                                           | 1        | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 18       | 43.9%   |
| 1 x AMD    | 11       | 26.83%  |
| 1 x Intel  | 10       | 24.39%  |
| 2 x AMD    | 1        | 2.44%   |
| 1 x SiS    | 1        | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 29       | 70.73%  |
| Proprietary | 10       | 24.39%  |
| Unknown     | 2        | 4.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 39.02%  |
| 0.51-1.0   | 12       | 29.27%  |
| 3.01-4.0   | 6        | 14.63%  |
| 1.01-2.0   | 5        | 12.2%   |
| 7.01-8.0   | 1        | 2.44%   |
| 0.01-0.5   | 1        | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Hewlett-Packard      | 5        | 12.82%  |
| Samsung Electronics  | 4        | 10.26%  |
| Goldstar             | 4        | 10.26%  |
| Dell                 | 4        | 10.26%  |
| Ancor Communications | 3        | 7.69%   |
| Philips              | 2        | 5.13%   |
| BenQ                 | 2        | 5.13%   |
| ASUSTek Computer     | 2        | 5.13%   |
| Acer                 | 2        | 5.13%   |
| Vizio                | 1        | 2.56%   |
| ViewSonic            | 1        | 2.56%   |
| Vestel Elektronik    | 1        | 2.56%   |
| Unknown              | 1        | 2.56%   |
| Toshiba              | 1        | 2.56%   |
| SKY                  | 1        | 2.56%   |
| LG Electronics       | 1        | 2.56%   |
| Lenovo               | 1        | 2.56%   |
| Insignia             | 1        | 2.56%   |
| HPN                  | 1        | 2.56%   |
| HannStar             | 1        | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Vizio LCD Monitor VIZ0026 1360x768 580x320mm 26.1-inch                 | 1        | 2.38%   |
| ViewSonic VA912-4SERIES VSC721C 1280x1024 376x301mm 19.0-inch          | 1        | 2.38%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 2.38%   |
| Unknown LCD Monitor Sony 55R617 1920x1080                              | 1        | 2.38%   |
| Toshiba TV TSB0200 1360x768 409x230mm 18.5-inch                        | 1        | 2.38%   |
| SKY TV-monitor SKY0001 1360x768 890x500mm 40.2-inch                    | 1        | 2.38%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1        | 2.38%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch      | 1        | 2.38%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch      | 1        | 2.38%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch   | 1        | 2.38%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch   | 1        | 2.38%   |
| Philips LCD Monitor 150C4 1024x768                                     | 1        | 2.38%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                     | 1        | 2.38%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 1        | 2.38%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch                | 1        | 2.38%   |
| Insignia DX-32L200NA14 BBY0032 1360x768 544x326mm 25.0-inch            | 1        | 2.38%   |
| HPN LCD Monitor HP 24o 1920x1080                                       | 1        | 2.38%   |
| Hewlett-Packard ZR2240w HWP2952 1920x1080 475x267mm 21.5-inch          | 1        | 2.38%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch            | 1        | 2.38%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 510x287mm 23.0-inch           | 1        | 2.38%   |
| Hewlett-Packard L1740 HWP2649 1280x1024 338x270mm 17.0-inch            | 1        | 2.38%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 1        | 2.38%   |
| HannStar iH282 HSD20E6 1920x1200 590x370mm 27.4-inch                   | 1        | 2.38%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch               | 1        | 2.38%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1        | 2.38%   |
| Goldstar E2742 GSM58C9 1920x1080 598x337mm 27.0-inch                   | 1        | 2.38%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                   | 1        | 2.38%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 1        | 2.38%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                       | 1        | 2.38%   |
| Dell S2722DGM DEL423A 2560x1440 597x336mm 27.0-inch                    | 1        | 2.38%   |
| Dell LCD Monitor ST2220L 3840x1080                                     | 1        | 2.38%   |
| Dell LCD Monitor ST2220L                                               | 1        | 2.38%   |
| BenQ G2020HD BNQ781F 1600x900 443x249mm 20.0-inch                      | 1        | 2.38%   |
| BenQ EW2775ZH BNQ7944 1920x1080 598x336mm 27.0-inch                    | 1        | 2.38%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch           | 1        | 2.38%   |
| ASUSTek Computer VC279 AUS27C4 1920x1080 598x336mm 27.0-inch           | 1        | 2.38%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 1        | 2.38%   |
| Ancor Communications LCD Monitor ASUS VS247 3840x1080                  | 1        | 2.38%   |
| Ancor Communications LCD Monitor ASUS VS247                            | 1        | 2.38%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 1        | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 14       | 34.15%  |
| 3840x2160 (4K)    | 5        | 12.2%   |
| 1920x1200 (WUXGA) | 4        | 9.76%   |
| 1280x1024 (SXGA)  | 3        | 7.32%   |
| 3840x1080         | 2        | 4.88%   |
| 2560x1080         | 2        | 4.88%   |
| 1600x900 (HD+)    | 2        | 4.88%   |
| 1440x900 (WXGA+)  | 2        | 4.88%   |
| Unknown           | 2        | 4.88%   |
| 2560x1440 (QHD)   | 1        | 2.44%   |
| 1920x540          | 1        | 2.44%   |
| 1360x768          | 1        | 2.44%   |
| 1280x720 (HD)     | 1        | 2.44%   |
| 1024x768 (XGA)    | 1        | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 8        | 20.51%  |
| 24      | 7        | 17.95%  |
| Unknown | 7        | 17.95%  |
| 19      | 3        | 7.69%   |
| 21      | 2        | 5.13%   |
| 20      | 2        | 5.13%   |
| 17      | 2        | 5.13%   |
| 84      | 1        | 2.56%   |
| 48      | 1        | 2.56%   |
| 43      | 1        | 2.56%   |
| 40      | 1        | 2.56%   |
| 34      | 1        | 2.56%   |
| 31      | 1        | 2.56%   |
| 26      | 1        | 2.56%   |
| 23      | 1        | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 15       | 38.46%  |
| Unknown     | 7        | 17.95%  |
| 401-500     | 6        | 15.38%  |
| 601-700     | 3        | 7.69%   |
| 301-350     | 2        | 5.13%   |
| 801-900     | 1        | 2.56%   |
| 701-800     | 1        | 2.56%   |
| 351-400     | 1        | 2.56%   |
| 1501-2000   | 1        | 2.56%   |
| 1001-1500   | 1        | 2.56%   |
| 901-1000    | 1        | 2.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 50%     |
| 16/10   | 7        | 18.42%  |
| Unknown | 7        | 18.42%  |
| 5/4     | 3        | 7.89%   |
| 21/9    | 1        | 2.63%   |
| 1.96    | 1        | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 8        | 20.51%  |
| 201-250        | 7        | 17.95%  |
| Unknown        | 7        | 17.95%  |
| 151-200        | 5        | 12.82%  |
| 251-300        | 4        | 10.26%  |
| 501-1000       | 3        | 7.69%   |
| 351-500        | 2        | 5.13%   |
| 141-150        | 2        | 5.13%   |
| More than 1000 | 1        | 2.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 22       | 57.89%  |
| Unknown | 7        | 18.42%  |
| 1-50    | 3        | 7.89%   |
| 121-160 | 3        | 7.89%   |
| 101-120 | 3        | 7.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 36       | 85.71%  |
| 2     | 4        | 9.52%   |
| 0     | 2        | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 23       | 39.66%  |
| Intel                            | 15       | 25.86%  |
| Qualcomm Atheros                 | 6        | 10.34%  |
| TP-Link                          | 4        | 6.9%    |
| Qualcomm Atheros Communications  | 2        | 3.45%   |
| Nvidia                           | 2        | 3.45%   |
| T & A Mobile Phones              | 1        | 1.72%   |
| Silicon Integrated Systems [SiS] | 1        | 1.72%   |
| Ralink Technology                | 1        | 1.72%   |
| Marvell Technology Group         | 1        | 1.72%   |
| Linksys                          | 1        | 1.72%   |
| Broadcom                         | 1        | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 20       | 31.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 3        | 4.69%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 3.13%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 2        | 3.13%   |
| Nvidia MCP61 Ethernet                                                                         | 2        | 3.13%   |
| Intel Wireless 3160                                                                           | 2        | 3.13%   |
| Intel I211 Gigabit Network Connection                                                         | 2        | 3.13%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                               | 1        | 1.56%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 1.56%   |
| TP-Link Archer T4U ver.3                                                                      | 1        | 1.56%   |
| TP-Link 802.11ac NIC                                                                          | 1        | 1.56%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                                                    | 1        | 1.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                                 | 1        | 1.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.56%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 1.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 1.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1        | 1.56%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.56%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 1.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1        | 1.56%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 1.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1        | 1.56%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1        | 1.56%   |
| Intel Wireless 8260                                                                           | 1        | 1.56%   |
| Intel Wireless 3165                                                                           | 1        | 1.56%   |
| Intel Ethernet Connection (7) I219-LM                                                         | 1        | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 1        | 1.56%   |
| Intel Ethernet Connection (11) I219-V                                                         | 1        | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 1.56%   |
| Intel Centrino Advanced-N 6235                                                                | 1        | 1.56%   |
| Intel 82583V Gigabit Network Connection                                                       | 1        | 1.56%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 1        | 1.56%   |
| Intel 82567LF-3 Gigabit Network Connection                                                    | 1        | 1.56%   |
| Intel 82562V-2 10/100 Network Connection                                                      | 1        | 1.56%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 1        | 1.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 27.27%  |
| Realtek Semiconductor           | 5        | 22.73%  |
| TP-Link                         | 3        | 13.64%  |
| Qualcomm Atheros                | 3        | 13.64%  |
| Qualcomm Atheros Communications | 2        | 9.09%   |
| Ralink Technology               | 1        | 4.55%   |
| Linksys                         | 1        | 4.55%   |
| Broadcom                        | 1        | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 9.09%   |
| Intel Wireless 3160                                                                           | 2        | 9.09%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 4.55%   |
| TP-Link Archer T4U ver.3                                                                      | 1        | 4.55%   |
| TP-Link 802.11ac NIC                                                                          | 1        | 4.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 4.55%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 4.55%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 4.55%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 4.55%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1        | 4.55%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 4.55%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1        | 4.55%   |
| Intel Wireless 8260                                                                           | 1        | 4.55%   |
| Intel Wireless 3165                                                                           | 1        | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 4.55%   |
| Intel Centrino Advanced-N 6235                                                                | 1        | 4.55%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 20       | 50%     |
| Intel                            | 11       | 27.5%   |
| Qualcomm Atheros                 | 3        | 7.5%    |
| Nvidia                           | 2        | 5%      |
| TP-Link                          | 1        | 2.5%    |
| T & A Mobile Phones              | 1        | 2.5%    |
| Silicon Integrated Systems [SiS] | 1        | 2.5%    |
| Marvell Technology Group         | 1        | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20       | 47.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 7.14%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 4.76%   |
| Nvidia MCP61 Ethernet                                             | 2        | 4.76%   |
| Intel I211 Gigabit Network Connection                             | 2        | 4.76%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 2.38%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                        | 1        | 2.38%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 2.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 2.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 2.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.38%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.38%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2.38%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 2.38%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.38%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 1        | 2.38%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 39       | 66.1%   |
| WiFi     | 20       | 33.9%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 70.73%  |
| WiFi     | 12       | 29.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 63.41%  |
| 2     | 11       | 26.83%  |
| 3     | 2        | 4.88%   |
| 0     | 2        | 4.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 40       | 97.56%  |
| Yes  | 1        | 2.44%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 37.5%   |
| Cambridge Silicon Radio         | 6        | 37.5%   |
| Realtek Semiconductor           | 1        | 6.25%   |
| Qualcomm Atheros Communications | 1        | 6.25%   |
| Integrated System Solution      | 1        | 6.25%   |
| Apple                           | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 37.5%   |
| Intel Bluetooth wireless interface                  | 4        | 25%     |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 6.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 6.25%   |
| Integrated System Solution Bluetooth Device         | 1        | 6.25%   |
| Apple Bluetooth USB Host Controller                 | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 28       | 38.89%  |
| Nvidia                           | 18       | 25%     |
| AMD                              | 16       | 22.22%  |
| Logitech                         | 3        | 4.17%   |
| Texas Instruments                | 2        | 2.78%   |
| C-Media Electronics              | 2        | 2.78%   |
| Silicon Integrated Systems [SiS] | 1        | 1.39%   |
| M2Tech                           | 1        | 1.39%   |
| Generalplus Technology           | 1        | 1.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5        | 6.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5        | 6.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4        | 4.94%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 4.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3        | 3.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 3        | 3.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3        | 3.7%    |
| Nvidia MCP61 High Definition Audio                                                                | 2        | 2.47%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 2.47%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2        | 2.47%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 2.47%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2        | 2.47%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                                        | 2        | 2.47%   |
| AMD FCH Azalia Controller                                                                         | 2        | 2.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 2.47%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 2.47%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 2.47%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1        | 1.23%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1        | 1.23%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1        | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1        | 1.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 1.23%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1        | 1.23%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 1.23%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 1.23%   |
| M2Tech hiFaceDAC UAC2                                                                             | 1        | 1.23%   |
| Logitech QuickCam Fusion                                                                          | 1        | 1.23%   |
| Logitech Logitech G PRO X Gaming Headset                                                          | 1        | 1.23%   |
| Logitech Headset H390                                                                             | 1        | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1        | 1.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 1.23%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 1.23%   |
| Intel CM238 HD Audio Controller                                                                   | 1        | 1.23%   |
| Intel Broadwell-U Audio Controller                                                                | 1        | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.23%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1        | 1.23%   |
| Generalplus Technology USB Audio Device                                                           | 1        | 1.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 4        | 23.53%  |
| Kingston            | 4        | 23.53%  |
| Samsung Electronics | 2        | 11.76%  |
| SK hynix            | 1        | 5.88%   |
| Patriot             | 1        | 5.88%   |
| Nanya Technology    | 1        | 5.88%   |
| Micron Technology   | 1        | 5.88%   |
| G.Skill             | 1        | 5.88%   |
| Crucial             | 1        | 5.88%   |
| Corsair             | 1        | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM SDRAM 800MT/s                            | 1        | 5.56%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                 | 1        | 5.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM 956MT/s                            | 1        | 5.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                            | 1        | 5.56%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                                  | 1        | 5.56%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s                   | 1        | 5.56%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s                | 1        | 5.56%   |
| Samsung RAM 4D332037385432383633515A532D43463720 1GB DIMM DDR2 800MT/s  | 1        | 5.56%   |
| Patriot RAM PSD432G32002 32GB DIMM DDR4 3200MT/s                        | 1        | 5.56%   |
| Nanya RAM NT1GT64U88D0BY-AD 1GB DIMM DDR 49926MT/s                      | 1        | 5.56%   |
| Micron RAM 8JTF25664HZ-1G6M1 2048MB SODIMM DDR3 1600MT/s                | 1        | 5.56%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                               | 1        | 5.56%   |
| Kingston RAM 9905734-018.A00G 16384MB DIMM DDR4 2667MT/s                | 1        | 5.56%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s                   | 1        | 5.56%   |
| Kingston RAM 202020202020202020202020202020202020 2GB DIMM DDR2 800MT/s | 1        | 5.56%   |
| G.Skill RAM F3-19200C10-8GBZHD 8GB DIMM DDR3 1333MT/s                   | 1        | 5.56%   |
| Crucial RAM CT25664A 2GB DIMM DDR2 800MT/s                              | 1        | 5.56%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s                   | 1        | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 4        | 28.57%  |
| DDR3    | 3        | 21.43%  |
| DDR2    | 3        | 21.43%  |
| SDRAM   | 2        | 14.29%  |
| Unknown | 2        | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 12       | 85.71%  |
| SODIMM | 2        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 7        | 41.18%  |
| 8192  | 3        | 17.65%  |
| 4096  | 3        | 17.65%  |
| 1024  | 2        | 11.76%  |
| 32768 | 1        | 5.88%   |
| 16384 | 1        | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 800   | 4        | 28.57%  |
| 2667  | 2        | 14.29%  |
| 1600  | 2        | 14.29%  |
| 1333  | 2        | 14.29%  |
| 49926 | 1        | 7.14%   |
| 3533  | 1        | 7.14%   |
| 3200  | 1        | 7.14%   |
| 956   | 1        | 7.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 40%     |
| Seiko Epson     | 1        | 20%     |
| Fuji Xerox      | 1        | 20%     |
| Canon           | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seiko Epson ET-2720 Series       | 1        | 20%     |
| HP Officejet 6600                | 1        | 20%     |
| HP LaserJet Professional P 1102w | 1        | 20%     |
| Fuji Xerox DocuPrint M205 b      | 1        | 20%     |
| Canon MF240 Series UFRII LT      | 1        | 20%     |

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
| Huawei Technologies     | 2        | 33.33%  |
| Z-Star Microelectronics | 1        | 16.67%  |
| Microdia                | 1        | 16.67%  |
| Logitech                | 1        | 16.67%  |
| Cubeternet              | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Huawei HiCamera                   | 2        | 33.33%  |
| Z-Star A4 TECH USB2.0 PC Camera E | 1        | 16.67%  |
| Microdia Sonix USB 2.0 Camera     | 1        | 16.67%  |
| Logitech HD Pro Webcam C920       | 1        | 16.67%  |
| Cubeternet HDMI to U3 capture     | 1        | 16.67%  |

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
| 0     | 35       | 85.37%  |
| 1     | 5        | 12.2%   |
| 2     | 1        | 2.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 3        | 50%     |
| Net/wireless  | 2        | 33.33%  |
| Bluetooth     | 1        | 16.67%  |

