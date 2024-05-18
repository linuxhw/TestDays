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

Total: 56

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | GA-770TA-UD3             | [a97e21eb8a](https://linux-hardware.org/?probe=a97e21eb8a) | Apr 11, 2024 |
| ASUSTek       | A88X-PRO                 | [b89a7c2325](https://linux-hardware.org/?probe=b89a7c2325) | Mar 14, 2024 |
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
| UbuntuDDE 20.04 | 30       | 69.77%  |
| UbuntuDDE 22.04 | 4        | 9.3%    |
| UbuntuDDE 20.10 | 3        | 6.98%   |
| UbuntuDDE 18.04 | 3        | 6.98%   |
| UbuntuDDE 21.10 | 2        | 4.65%   |
| UbuntuDDE 21.04 | 1        | 2.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| UbuntuDDE | 43       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.4.0-29-generic    | 9        | 20.45%  |
| 5.4.0-42-generic    | 3        | 6.82%   |
| 5.4.0-21-generic    | 3        | 6.82%   |
| 5.4.0-48-generic    | 2        | 4.55%   |
| 6.2.0-35-generic    | 1        | 2.27%   |
| 5.8.0-53-generic    | 1        | 2.27%   |
| 5.8.0-50-generic    | 1        | 2.27%   |
| 5.8.0-48-generic    | 1        | 2.27%   |
| 5.8.0-41-generic    | 1        | 2.27%   |
| 5.8.0-33-generic    | 1        | 2.27%   |
| 5.4.0-53-generic    | 1        | 2.27%   |
| 5.4.0-52-generic    | 1        | 2.27%   |
| 5.4.0-45-generic    | 1        | 2.27%   |
| 5.4.0-40-lowlatency | 1        | 2.27%   |
| 5.4.0-39-generic    | 1        | 2.27%   |
| 5.4.0-37-generic    | 1        | 2.27%   |
| 5.4.0-31-generic    | 1        | 2.27%   |
| 5.4.0-26-generic    | 1        | 2.27%   |
| 5.4.0-24-generic    | 1        | 2.27%   |
| 5.3.0-40-generic    | 1        | 2.27%   |
| 5.19.0-46-generic   | 1        | 2.27%   |
| 5.15.0-88-generic   | 1        | 2.27%   |
| 5.15.0-53-generic   | 1        | 2.27%   |
| 5.15.0-50-generic   | 1        | 2.27%   |
| 5.15.0-48-generic   | 1        | 2.27%   |
| 5.13.0-39-generic   | 1        | 2.27%   |
| 5.13.0-35-generic   | 1        | 2.27%   |
| 5.13.0-28-generic   | 1        | 2.27%   |
| 5.11.0-31-generic   | 1        | 2.27%   |
| 5.0.0-36-generic    | 1        | 2.27%   |
| 4.15.0-122-generic  | 1        | 2.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 26       | 60.47%  |
| 5.8.0   | 5        | 11.63%  |
| 5.15.0  | 4        | 9.3%    |
| 5.13.0  | 2        | 4.65%   |
| 6.2.0   | 1        | 2.33%   |
| 5.3.0   | 1        | 2.33%   |
| 5.19.0  | 1        | 2.33%   |
| 5.11.0  | 1        | 2.33%   |
| 5.0.0   | 1        | 2.33%   |
| 4.15.0  | 1        | 2.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 26       | 60.47%  |
| 5.8     | 5        | 11.63%  |
| 5.15    | 4        | 9.3%    |
| 5.13    | 2        | 4.65%   |
| 6.2     | 1        | 2.33%   |
| 5.3     | 1        | 2.33%   |
| 5.19    | 1        | 2.33%   |
| 5.11    | 1        | 2.33%   |
| 5.0     | 1        | 2.33%   |
| 4.15    | 1        | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 43       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Deepin | 43       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 43       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28       | 65.12%  |
| LightDM | 7        | 16.28%  |
| TDM     | 5        | 11.63%  |
| GDM     | 2        | 4.65%   |
| GDM3    | 1        | 2.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 17       | 39.53%  |
| pt_BR | 4        | 9.3%    |
| en_GB | 3        | 6.98%   |
| fr_FR | 2        | 4.65%   |
| fi_FI | 2        | 4.65%   |
| de_DE | 2        | 4.65%   |
| C     | 2        | 4.65%   |
| uk_UA | 1        | 2.33%   |
| tr_TR | 1        | 2.33%   |
| th_TH | 1        | 2.33%   |
| ru_RU | 1        | 2.33%   |
| pl_PL | 1        | 2.33%   |
| it_IT | 1        | 2.33%   |
| es_ES | 1        | 2.33%   |
| es_CR | 1        | 2.33%   |
| es_AR | 1        | 2.33%   |
| en_CA | 1        | 2.33%   |
| de_CH | 1        | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 25       | 58.14%  |
| EFI  | 18       | 41.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 36       | 83.72%  |
| Tmpfs   | 4        | 9.3%    |
| Overlay | 1        | 2.33%   |
| Btrfs   | 1        | 2.33%   |
| Unknown | 1        | 2.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 67.44%  |
| GPT     | 10       | 23.26%  |
| MBR     | 4        | 9.3%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 81.4%   |
| Yes       | 8        | 18.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 54.55%  |
| Yes       | 20       | 45.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 12       | 27.91%  |
| MSI                 | 6        | 13.95%  |
| Gigabyte Technology | 6        | 13.95%  |
| Intel               | 3        | 6.98%   |
| Hewlett-Packard     | 3        | 6.98%   |
| Dell                | 3        | 6.98%   |
| ASRock              | 2        | 4.65%   |
| Medion              | 1        | 2.33%   |
| Fujitsu Siemens     | 1        | 2.33%   |
| Fujitsu             | 1        | 2.33%   |
| eMachines           | 1        | 2.33%   |
| ECS                 | 1        | 2.33%   |
| BANGHO              | 1        | 2.33%   |
| Acer                | 1        | 2.33%   |
| Unknown             | 1        | 2.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| MSI MS-7592                   | 3        | 6.98%   |
| MSI MS-7B84                   | 1        | 2.33%   |
| MSI MS-7816                   | 1        | 2.33%   |
| MSI MS-7693                   | 1        | 2.33%   |
| Medion MS-7848                | 1        | 2.33%   |
| Intel DQ45CB AAE30148-207     | 1        | 2.33%   |
| Intel D33217CK G76541-302     | 1        | 2.33%   |
| Intel B75                     | 1        | 2.33%   |
| HP Pavilion Desktop 590-p0xxx | 1        | 2.33%   |
| HP Compaq Elite 8300 SFF      | 1        | 2.33%   |
| HP Compaq Elite 8300 MT       | 1        | 2.33%   |
| Gigabyte GB-BXi7-5500         | 1        | 2.33%   |
| Gigabyte GA-MA74GM-S2         | 1        | 2.33%   |
| Gigabyte GA-970A-D3           | 1        | 2.33%   |
| Gigabyte GA-770TA-UD3         | 1        | 2.33%   |
| Gigabyte F2A55M-HD2           | 1        | 2.33%   |
| Gigabyte B75M-D3H             | 1        | 2.33%   |
| Fujitsu Siemens ESPRIMO P5730 | 1        | 2.33%   |
| Fujitsu ESPRIMO E900          | 1        | 2.33%   |
| eMachines EL1333G             | 1        | 2.33%   |
| ECS GL307AA-ABA a6123w        | 1        | 2.33%   |
| Dell PowerEdge T40            | 1        | 2.33%   |
| Dell Inspiron 530             | 1        | 2.33%   |
| Dell Inspiron 3670            | 1        | 2.33%   |
| BANGHO CUBIC                  | 1        | 2.33%   |
| ASUS PRIME B450M-A II         | 1        | 2.33%   |
| ASUS PRIME B360M-A            | 1        | 2.33%   |
| ASUS P8Z68-V LX               | 1        | 2.33%   |
| ASUS P6X58D-E                 | 1        | 2.33%   |
| ASUS P5KPL-AM                 | 1        | 2.33%   |
| ASUS P5G41C-M LX              | 1        | 2.33%   |
| ASUS H61M-D                   | 1        | 2.33%   |
| ASUS D820MT_D820SF_BM3CE      | 1        | 2.33%   |
| ASUS CROSSHAIR V FORMULA-Z    | 1        | 2.33%   |
| ASUS All Series               | 1        | 2.33%   |
| ASUS A88X-PRO                 | 1        | 2.33%   |
| ASUS A68HM-PLUS               | 1        | 2.33%   |
| ASRock X370 Gaming K4         | 1        | 2.33%   |
| ASRock B560M-C                | 1        | 2.33%   |
| Acer ASM1610/VTM261           | 1        | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| MSI MS-7592             | 3        | 6.98%   |
| HP Compaq               | 2        | 4.65%   |
| Dell Inspiron           | 2        | 4.65%   |
| ASUS PRIME              | 2        | 4.65%   |
| MSI MS-7B84             | 1        | 2.33%   |
| MSI MS-7816             | 1        | 2.33%   |
| MSI MS-7693             | 1        | 2.33%   |
| Medion MS-7848          | 1        | 2.33%   |
| Intel DQ45CB            | 1        | 2.33%   |
| Intel D33217CK          | 1        | 2.33%   |
| Intel B75               | 1        | 2.33%   |
| HP Pavilion             | 1        | 2.33%   |
| Gigabyte GB-BXi7-5500   | 1        | 2.33%   |
| Gigabyte GA-MA74GM-S2   | 1        | 2.33%   |
| Gigabyte GA-970A-D3     | 1        | 2.33%   |
| Gigabyte GA-770TA-UD3   | 1        | 2.33%   |
| Gigabyte F2A55M-HD2     | 1        | 2.33%   |
| Gigabyte B75M-D3H       | 1        | 2.33%   |
| Fujitsu Siemens ESPRIMO | 1        | 2.33%   |
| Fujitsu ESPRIMO         | 1        | 2.33%   |
| eMachines EL1333G       | 1        | 2.33%   |
| ECS GL307AA-ABA         | 1        | 2.33%   |
| Dell PowerEdge          | 1        | 2.33%   |
| BANGHO CUBIC            | 1        | 2.33%   |
| ASUS P8Z68-V            | 1        | 2.33%   |
| ASUS P6X58D-E           | 1        | 2.33%   |
| ASUS P5KPL-AM           | 1        | 2.33%   |
| ASUS P5G41C-M           | 1        | 2.33%   |
| ASUS H61M-D             | 1        | 2.33%   |
| ASUS D820MT             | 1        | 2.33%   |
| ASUS CROSSHAIR          | 1        | 2.33%   |
| ASUS All                | 1        | 2.33%   |
| ASUS A88X-PRO           | 1        | 2.33%   |
| ASUS A68HM-PLUS         | 1        | 2.33%   |
| ASRock X370             | 1        | 2.33%   |
| ASRock B560M-C          | 1        | 2.33%   |
| Acer ASM1610            | 1        | 2.33%   |
| Unknown                 | 1        | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 5        | 11.63%  |
| 2011 | 5        | 11.63%  |
| 2014 | 4        | 9.3%    |
| 2012 | 4        | 9.3%    |
| 2008 | 4        | 9.3%    |
| 2018 | 3        | 6.98%   |
| 2016 | 3        | 6.98%   |
| 2010 | 3        | 6.98%   |
| 2009 | 3        | 6.98%   |
| 2020 | 2        | 4.65%   |
| 2019 | 2        | 4.65%   |
| 2007 | 2        | 4.65%   |
| 2021 | 1        | 2.33%   |
| 2017 | 1        | 2.33%   |
| 2015 | 1        | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 43       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 42       | 97.67%  |
| Enabled  | 1        | 2.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 43       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 10       | 23.26%  |
| 4.01-8.0    | 9        | 20.93%  |
| 16.01-24.0  | 9        | 20.93%  |
| 3.01-4.0    | 8        | 18.6%   |
| 32.01-64.0  | 3        | 6.98%   |
| 2.01-3.0    | 2        | 4.65%   |
| 24.01-32.0  | 1        | 2.33%   |
| 64.01-256.0 | 1        | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 2.01-3.0 | 17       | 39.53%  |
| 1.01-2.0 | 17       | 39.53%  |
| 4.01-8.0 | 5        | 11.63%  |
| 3.01-4.0 | 2        | 4.65%   |
| 0.51-1.0 | 2        | 4.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 44.19%  |
| 1      | 17       | 39.53%  |
| 3      | 6        | 13.95%  |
| 4      | 1        | 2.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 51.16%  |
| No        | 21       | 48.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 41       | 95.35%  |
| No        | 2        | 4.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 51.16%  |
| No        | 21       | 48.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 62.79%  |
| Yes       | 16       | 37.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 9        | 20.93%  |
| UK         | 4        | 9.3%    |
| Brazil     | 4        | 9.3%    |
| Germany    | 3        | 6.98%   |
| Argentina  | 3        | 6.98%   |
| Portugal   | 2        | 4.65%   |
| France     | 2        | 4.65%   |
| Finland    | 2        | 4.65%   |
| Ukraine    | 1        | 2.33%   |
| Turkey     | 1        | 2.33%   |
| Thailand   | 1        | 2.33%   |
| Sweden     | 1        | 2.33%   |
| Russia     | 1        | 2.33%   |
| Poland     | 1        | 2.33%   |
| Mexico     | 1        | 2.33%   |
| Luxembourg | 1        | 2.33%   |
| Italy      | 1        | 2.33%   |
| Indonesia  | 1        | 2.33%   |
| Costa Rica | 1        | 2.33%   |
| Canada     | 1        | 2.33%   |
| Belgium    | 1        | 2.33%   |
| Austria    | 1        | 2.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Helsinki              | 2        | 4.65%   |
| Yogyakarta            | 1        | 2.33%   |
| Tomah                 | 1        | 2.33%   |
| Słubice              | 1        | 2.33%   |
| St Petersburg         | 1        | 2.33%   |
| Şişli               | 1        | 2.33%   |
| Sao Paulo             | 1        | 2.33%   |
| Sao Bernardo do Campo | 1        | 2.33%   |
| Sankt Pölten         | 1        | 2.33%   |
| San Telmo             | 1        | 2.33%   |
| Rosario               | 1        | 2.33%   |
| Rome                  | 1        | 2.33%   |
| Rodgau                | 1        | 2.33%   |
| Pontpierre            | 1        | 2.33%   |
| Oakville              | 1        | 2.33%   |
| Newburgh              | 1        | 2.33%   |
| Monterrey             | 1        | 2.33%   |
| Monte Carmelo         | 1        | 2.33%   |
| Molesey               | 1        | 2.33%   |
| Milwaukee             | 1        | 2.33%   |
| Milan                 | 1        | 2.33%   |
| Lviv                  | 1        | 2.33%   |
| Lisbon                | 1        | 2.33%   |
| Las Vegas             | 1        | 2.33%   |
| La Louvière          | 1        | 2.33%   |
| Krefeld               | 1        | 2.33%   |
| Heredia               | 1        | 2.33%   |
| Enskede-Arsta-Vantoer | 1        | 2.33%   |
| Derby                 | 1        | 2.33%   |
| Dayton                | 1        | 2.33%   |
| Curitiba              | 1        | 2.33%   |
| Colorado Springs      | 1        | 2.33%   |
| Colmar                | 1        | 2.33%   |
| Buenos Aires          | 1        | 2.33%   |
| Bristol               | 1        | 2.33%   |
| Bourgoin-Jallieu      | 1        | 2.33%   |
| Bermondsey            | 1        | 2.33%   |
| Berlin                | 1        | 2.33%   |
| Bend                  | 1        | 2.33%   |
| Beja                  | 1        | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 20     | 23.44%  |
| WDC                 | 10       | 15     | 15.63%  |
| Samsung Electronics | 9        | 9      | 14.06%  |
| Toshiba             | 7        | 7      | 10.94%  |
| Kingston            | 5        | 5      | 7.81%   |
| Hitachi             | 3        | 4      | 4.69%   |
| Crucial             | 3        | 3      | 4.69%   |
| Vaseky              | 1        | 1      | 1.56%   |
| SanDisk             | 1        | 1      | 1.56%   |
| PNY                 | 1        | 2      | 1.56%   |
| Plextor             | 1        | 1      | 1.56%   |
| Maxtor              | 1        | 1      | 1.56%   |
| Leven               | 1        | 1      | 1.56%   |
| KingFast            | 1        | 1      | 1.56%   |
| JMicron Technology  | 1        | 1      | 1.56%   |
| Integral            | 1        | 1      | 1.56%   |
| GOODRAM             | 1        | 1      | 1.56%   |
| China               | 1        | 1      | 1.56%   |
| ADATA Technology    | 1        | 1      | 1.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB             | 4        | 5.63%   |
| Seagate ST1000DM010-2EP102 1TB     | 3        | 4.23%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 2        | 2.82%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 2.82%   |
| Samsung SSD 850 EVO 250GB          | 2        | 2.82%   |
| WDC WDBNCE2500PNC 250GB SSD        | 1        | 1.41%   |
| WDC WD7501AALS-75J7B0 752GB        | 1        | 1.41%   |
| WDC WD60EDAZ-11BMZB0 6TB           | 1        | 1.41%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 1.41%   |
| WDC WD3200AAJS-00B4A0 320GB        | 1        | 1.41%   |
| WDC WD30EZRX-00MMMB0 3TB           | 1        | 1.41%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1        | 1.41%   |
| WDC WD2500AAKX-001CA0 250GB        | 1        | 1.41%   |
| WDC WD2002FAEX-007BA0 2TB          | 1        | 1.41%   |
| WDC WD1003FZEX-00K3CA0 1TB         | 1        | 1.41%   |
| Vaseky V800/128G 120GB SSD         | 1        | 1.41%   |
| Toshiba THNSFC128GBSJ SSD          | 1        | 1.41%   |
| Toshiba MQ01ABD100 1TB             | 1        | 1.41%   |
| Toshiba MK3275GSX 320GB            | 1        | 1.41%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1.41%   |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 1.41%   |
| Seagate ST4000DM 004-2CV104 4TB    | 1        | 1.41%   |
| Seagate ST3500630AS 500GB          | 1        | 1.41%   |
| Seagate ST3500413AS 500GB          | 1        | 1.41%   |
| Seagate ST3500312CS 500GB          | 1        | 1.41%   |
| Seagate ST3320418AS 320GB          | 1        | 1.41%   |
| Seagate ST3250820AS 250GB          | 1        | 1.41%   |
| Seagate ST31000524AS 1TB           | 1        | 1.41%   |
| Seagate ST2000DM001-9YN164 2TB     | 1        | 1.41%   |
| Seagate ST2000DM001-1ER164 2TB     | 1        | 1.41%   |
| Seagate ST1000VT000 HN-M101MBB 1TB | 1        | 1.41%   |
| Seagate ST1000LM014-1EJ164 1TB     | 1        | 1.41%   |
| Seagate ST1000DM003-1CH162 1TB     | 1        | 1.41%   |
| SanDisk SSD PLUS 240 GB            | 1        | 1.41%   |
| Samsung SSD 850 EVO 500GB          | 1        | 1.41%   |
| Samsung SSD 850 EVO 1TB            | 1        | 1.41%   |
| Samsung NVMe SSD Drive 512GB       | 1        | 1.41%   |
| Samsung HM250HI 250GB              | 1        | 1.41%   |
| Samsung HD161HJ 160GB              | 1        | 1.41%   |
| Samsung HD103SJ 1TB                | 1        | 1.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 20     | 39.47%  |
| WDC                 | 9        | 11     | 23.68%  |
| Toshiba             | 6        | 6      | 15.79%  |
| Samsung Electronics | 4        | 4      | 10.53%  |
| Hitachi             | 3        | 4      | 7.89%   |
| Maxtor              | 1        | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 4      | 16.67%  |
| Kingston            | 4        | 4      | 16.67%  |
| WDC                 | 3        | 4      | 12.5%   |
| Crucial             | 3        | 3      | 12.5%   |
| Vaseky              | 1        | 1      | 4.17%   |
| Toshiba             | 1        | 1      | 4.17%   |
| SanDisk             | 1        | 1      | 4.17%   |
| PNY                 | 1        | 2      | 4.17%   |
| Plextor             | 1        | 1      | 4.17%   |
| Leven               | 1        | 1      | 4.17%   |
| KingFast            | 1        | 1      | 4.17%   |
| Integral            | 1        | 1      | 4.17%   |
| GOODRAM             | 1        | 1      | 4.17%   |
| China               | 1        | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 33       | 46     | 57.89%  |
| SSD     | 20       | 26     | 35.09%  |
| NVMe    | 3        | 3      | 5.26%   |
| Unknown | 1        | 1      | 1.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 42       | 71     | 89.36%  |
| NVMe | 3        | 3      | 6.38%   |
| SAS  | 2        | 2      | 4.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 28       | 38     | 50%     |
| 0.51-1.0   | 19       | 22     | 33.93%  |
| 1.01-2.0   | 4        | 5      | 7.14%   |
| 3.01-4.0   | 2        | 2      | 3.57%   |
| 2.01-3.0   | 2        | 3      | 3.57%   |
| 4.01-10.0  | 1        | 2      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 15       | 34.88%  |
| 1001-2000      | 8        | 18.6%   |
| 251-500        | 6        | 13.95%  |
| 501-1000       | 6        | 13.95%  |
| 51-100         | 3        | 6.98%   |
| More than 3000 | 2        | 4.65%   |
| 21-50          | 2        | 4.65%   |
| Unknown        | 1        | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 23       | 53.49%  |
| 101-250   | 7        | 16.28%  |
| 251-500   | 4        | 9.3%    |
| 21-50     | 2        | 4.65%   |
| 1001-2000 | 2        | 4.65%   |
| 501-1000  | 2        | 4.65%   |
| 51-100    | 2        | 4.65%   |
| Unknown   | 1        | 2.33%   |

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
| Detected | 34       | 61     | 75.56%  |
| Works    | 9        | 13     | 20%     |
| Malfunc  | 2        | 2      | 4.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 28       | 52.83%  |
| AMD                              | 12       | 22.64%  |
| Samsung Electronics              | 3        | 5.66%   |
| Nvidia                           | 2        | 3.77%   |
| Marvell Technology Group         | 2        | 3.77%   |
| ASMedia Technology               | 2        | 3.77%   |
| Silicon Integrated Systems [SiS] | 1        | 1.89%   |
| Kingston Technology Company      | 1        | 1.89%   |
| JMicron Technology               | 1        | 1.89%   |
| ADATA Technology                 | 1        | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 6        | 8.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5        | 6.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4        | 5.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3        | 4.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3        | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3        | 4.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 2.7%    |
| Nvidia MCP61 SATA Controller                                                     | 2        | 2.7%    |
| Nvidia MCP61 IDE                                                                 | 2        | 2.7%    |
| Marvell Group 88SE91A3 SATA-600 Controller                                       | 2        | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2        | 2.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 2.7%    |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                       | 2        | 2.7%    |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                       | 2        | 2.7%    |
| Intel 4 Series Chipset PT IDER Controller                                        | 2        | 2.7%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 2        | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2        | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2        | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2        | 2.7%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1        | 1.35%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1        | 1.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1        | 1.35%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                         | 1        | 1.35%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1        | 1.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1        | 1.35%   |
| Intel SATA Controller [RAID Mode]                                                | 1        | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 1.35%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 1.35%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1        | 1.35%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 1        | 1.35%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 1        | 1.35%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 1        | 1.35%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 1        | 1.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1        | 1.35%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1        | 1.35%   |
| AMD X370 Series Chipset SATA Controller                                          | 1        | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [RAID5 mode]                               | 1        | 1.35%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1        | 1.35%   |
| AMD FCH SATA Controller D                                                        | 1        | 1.35%   |
| AMD FCH IDE Controller                                                           | 1        | 1.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 28       | 54.9%   |
| IDE  | 16       | 31.37%  |
| NVMe | 5        | 9.8%    |
| RAID | 2        | 3.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 29       | 67.44%  |
| AMD    | 14       | 32.56%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i3-3220 CPU @ 3.30GHz                | 2        | 4.65%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 2        | 4.65%   |
| Intel Xeon E-2224G CPU @ 3.50GHz                | 1        | 2.33%   |
| Intel Xeon CPU E5450 @ 3.00GHz                  | 1        | 2.33%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz     | 1        | 2.33%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 1        | 2.33%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz          | 1        | 2.33%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz              | 1        | 2.33%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 2.33%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1        | 2.33%   |
| Intel Core i7-2700K CPU @ 3.50GHz               | 1        | 2.33%   |
| Intel Core i7 CPU 950 @ 3.07GHz                 | 1        | 2.33%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1        | 2.33%   |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1        | 2.33%   |
| Intel Core i5-4670K CPU @ 3.40GHz               | 1        | 2.33%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1        | 2.33%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 1        | 2.33%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 2.33%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 1        | 2.33%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 2.33%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1        | 2.33%   |
| Intel Core i3-3217U CPU @ 1.80GHz               | 1        | 2.33%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz           | 1        | 2.33%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz           | 1        | 2.33%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz           | 1        | 2.33%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz            | 1        | 2.33%   |
| Intel Core 2 CPU 6320 @ 1.86GHz                 | 1        | 2.33%   |
| Intel Celeron CPU N3000 @ 1.04GHz               | 1        | 2.33%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz         | 1        | 2.33%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 1        | 2.33%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 2.33%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1        | 2.33%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 1        | 2.33%   |
| AMD Phenom II X6 1055T Processor                | 1        | 2.33%   |
| AMD Phenom II X4 945 Processor                  | 1        | 2.33%   |
| AMD Phenom 9650 Quad-Core Processor             | 1        | 2.33%   |
| AMD FX-9590 Eight-Core Processor                | 1        | 2.33%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 2.33%   |
| AMD Athlon Dual Core Processor 4850e            | 1        | 2.33%   |
| AMD Athlon 64 X2 Dual Core Processor 4400+      | 1        | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 8        | 18.6%   |
| Intel Core i7           | 5        | 11.63%  |
| Intel Core i3           | 4        | 9.3%    |
| Intel Core 2 Quad       | 3        | 6.98%   |
| AMD Ryzen 5             | 3        | 6.98%   |
| Intel Xeon              | 2        | 4.65%   |
| Intel Pentium Dual-Core | 2        | 4.65%   |
| AMD FX                  | 2        | 4.65%   |
| AMD A10                 | 2        | 4.65%   |
| Other                   | 1        | 2.33%   |
| Intel Pentium Dual      | 1        | 2.33%   |
| Intel Core 2 Duo        | 1        | 2.33%   |
| Intel Core 2            | 1        | 2.33%   |
| Intel Celeron           | 1        | 2.33%   |
| AMD Ryzen 7             | 1        | 2.33%   |
| AMD Phenom II X6        | 1        | 2.33%   |
| AMD Phenom II X4        | 1        | 2.33%   |
| AMD Phenom              | 1        | 2.33%   |
| AMD Athlon Dual Core    | 1        | 2.33%   |
| AMD Athlon 64 X2        | 1        | 2.33%   |
| AMD A4                  | 1        | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 22       | 51.16%  |
| 2      | 14       | 32.56%  |
| 6      | 5        | 11.63%  |
| 8      | 1        | 2.33%   |
| 1      | 1        | 2.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 43       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 60.47%  |
| 2      | 17       | 39.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 43       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 25.58%  |
| 0x306a9    | 6        | 13.95%  |
| 0x1067a    | 4        | 9.3%    |
| 0x306c3    | 2        | 4.65%   |
| 0x10677    | 2        | 4.65%   |
| 0x06000852 | 2        | 4.65%   |
| 0x906ed    | 1        | 2.33%   |
| 0x906eb    | 1        | 2.33%   |
| 0x906ea    | 1        | 2.33%   |
| 0x6fd      | 1        | 2.33%   |
| 0x6f6      | 1        | 2.33%   |
| 0x506e3    | 1        | 2.33%   |
| 0x406c3    | 1        | 2.33%   |
| 0x306d4    | 1        | 2.33%   |
| 0x206a7    | 1        | 2.33%   |
| 0x106a5    | 1        | 2.33%   |
| 0x08701021 | 1        | 2.33%   |
| 0x08101016 | 1        | 2.33%   |
| 0x08001138 | 1        | 2.33%   |
| 0x06003106 | 1        | 2.33%   |
| 0x010000dc | 1        | 2.33%   |
| 0x01000083 | 1        | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 6        | 13.95%  |
| IvyBridge   | 6        | 13.95%  |
| KabyLake    | 4        | 9.3%    |
| Piledriver  | 3        | 6.98%   |
| K10         | 3        | 6.98%   |
| Haswell     | 3        | 6.98%   |
| Core        | 3        | 6.98%   |
| Zen         | 2        | 4.65%   |
| Steamroller | 2        | 4.65%   |
| SandyBridge | 2        | 4.65%   |
| K8 Hammer   | 2        | 4.65%   |
| Zen+        | 1        | 2.33%   |
| Zen 2       | 1        | 2.33%   |
| Skylake     | 1        | 2.33%   |
| Silvermont  | 1        | 2.33%   |
| Nehalem     | 1        | 2.33%   |
| Broadwell   | 1        | 2.33%   |
| Unknown     | 1        | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 18       | 40%     |
| AMD                              | 14       | 31.11%  |
| Intel                            | 12       | 26.67%  |
| Silicon Integrated Systems [SiS] | 1        | 2.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3        | 6.52%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 6.52%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 4.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 4.35%   |
| AMD RV770 [Radeon HD 4850]                                                               | 2        | 4.35%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 4.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 4.35%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 4.35%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1        | 2.17%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 2.17%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 2.17%   |
| Nvidia GT215 [GeForce GT 320]                                                            | 1        | 2.17%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1        | 2.17%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1        | 2.17%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 2.17%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                                        | 1        | 2.17%   |
| Nvidia GF119 [GeForce GT 705]                                                            | 1        | 2.17%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1        | 2.17%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 2.17%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1        | 2.17%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 2.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 2.17%   |
| Intel HD Graphics 630                                                                    | 1        | 2.17%   |
| Intel HD Graphics 5500                                                                   | 1        | 2.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                               | 1        | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1        | 2.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 2.17%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 1        | 2.17%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 1        | 2.17%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 2.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 2.17%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 1        | 2.17%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 1        | 2.17%   |
| AMD Barts PRO [Radeon HD 6850]                                                           | 1        | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 18       | 41.86%  |
| 1 x AMD    | 13       | 30.23%  |
| 1 x Intel  | 10       | 23.26%  |
| 2 x AMD    | 1        | 2.33%   |
| 1 x SiS    | 1        | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 31       | 72.09%  |
| Proprietary | 10       | 23.26%  |
| Unknown     | 2        | 4.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 39.53%  |
| 0.51-1.0   | 13       | 30.23%  |
| 3.01-4.0   | 6        | 13.95%  |
| 1.01-2.0   | 5        | 11.63%  |
| 7.01-8.0   | 1        | 2.33%   |
| 0.01-0.5   | 1        | 2.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 5        | 12.2%   |
| Hewlett-Packard      | 5        | 12.2%   |
| Goldstar             | 4        | 9.76%   |
| Dell                 | 4        | 9.76%   |
| Ancor Communications | 3        | 7.32%   |
| Philips              | 2        | 4.88%   |
| BenQ                 | 2        | 4.88%   |
| ASUSTek Computer     | 2        | 4.88%   |
| Acer                 | 2        | 4.88%   |
| Vizio                | 1        | 2.44%   |
| ViewSonic            | 1        | 2.44%   |
| Vestel Elektronik    | 1        | 2.44%   |
| Unknown              | 1        | 2.44%   |
| Toshiba              | 1        | 2.44%   |
| SKY                  | 1        | 2.44%   |
| LG Electronics       | 1        | 2.44%   |
| Lenovo               | 1        | 2.44%   |
| Insignia             | 1        | 2.44%   |
| HPN                  | 1        | 2.44%   |
| HannStar             | 1        | 2.44%   |
| Fujitsu Siemens      | 1        | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Vizio LCD Monitor VIZ0026 1360x768 580x320mm 26.1-inch               | 1        | 2.27%   |
| ViewSonic VA912-4SERIES VSC721C 1280x1024 376x301mm 19.0-inch        | 1        | 2.27%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                        | 1        | 2.27%   |
| Unknown LCD Monitor Sony 55R617 1920x1080                            | 1        | 2.27%   |
| Toshiba TV TSB0200 1360x768 409x230mm 18.5-inch                      | 1        | 2.27%   |
| SKY TV-monitor SKY0001 1360x768 890x500mm 40.2-inch                  | 1        | 2.27%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch    | 1        | 2.27%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch    | 1        | 2.27%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch    | 1        | 2.27%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1        | 2.27%   |
| Samsung Electronics LCD Monitor SAM0E4C 1366x768 522x293mm 23.6-inch | 1        | 2.27%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 1        | 2.27%   |
| Philips LCD Monitor 150C4 1024x768                                   | 1        | 2.27%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                   | 1        | 2.27%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 1        | 2.27%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch              | 1        | 2.27%   |
| Insignia DX-15E220A12 BBY0032 1360x768 544x326mm 25.0-inch           | 1        | 2.27%   |
| HPN LCD Monitor HP 24o 1920x1080                                     | 1        | 2.27%   |
| Hewlett-Packard ZR2240w HWP2952 1920x1080 475x267mm 21.5-inch        | 1        | 2.27%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch          | 1        | 2.27%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 509x286mm 23.0-inch         | 1        | 2.27%   |
| Hewlett-Packard L1740 HWP2649 1280x1024 337x270mm 17.0-inch          | 1        | 2.27%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch           | 1        | 2.27%   |
| HannStar iH282 HSD20E6 1920x1200 590x370mm 27.4-inch                 | 1        | 2.27%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 1        | 2.27%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 1        | 2.27%   |
| Goldstar E2742 GSM58C9 1920x1080 598x337mm 27.0-inch                 | 1        | 2.27%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 1        | 2.27%   |
| Fujitsu Siemens L20T-2 LED FUS07E3 1600x900 442x249mm 20.0-inch      | 1        | 2.27%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1        | 2.27%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                     | 1        | 2.27%   |
| Dell S2722DGM DEL423A 2560x1440 597x336mm 27.0-inch                  | 1        | 2.27%   |
| Dell LCD Monitor ST2220L 3840x1080                                   | 1        | 2.27%   |
| Dell LCD Monitor ST2220L                                             | 1        | 2.27%   |
| BenQ G2020HD BNQ781F 1600x900 443x249mm 20.0-inch                    | 1        | 2.27%   |
| BenQ EW2775ZH BNQ7944 1920x1080 598x336mm 27.0-inch                  | 1        | 2.27%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch         | 1        | 2.27%   |
| ASUSTek Computer VC279 AUS27C4 1920x1080 598x336mm 27.0-inch         | 1        | 2.27%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch     | 1        | 2.27%   |
| Ancor Communications LCD Monitor ASUS VS247 3840x1080                | 1        | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 14       | 32.56%  |
| 3840x2160 (4K)    | 5        | 11.63%  |
| 1920x1200 (WUXGA) | 4        | 9.3%    |
| 1600x900 (HD+)    | 3        | 6.98%   |
| 1280x1024 (SXGA)  | 3        | 6.98%   |
| 3840x1080         | 2        | 4.65%   |
| 2560x1080         | 2        | 4.65%   |
| 1440x900 (WXGA+)  | 2        | 4.65%   |
| Unknown           | 2        | 4.65%   |
| 2560x1440 (QHD)   | 1        | 2.33%   |
| 1920x540          | 1        | 2.33%   |
| 1366x768 (WXGA)   | 1        | 2.33%   |
| 1360x768          | 1        | 2.33%   |
| 1280x720 (HD)     | 1        | 2.33%   |
| 1024x768 (XGA)    | 1        | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 8        | 19.51%  |
| 24      | 7        | 17.07%  |
| Unknown | 7        | 17.07%  |
| 20      | 3        | 7.32%   |
| 19      | 3        | 7.32%   |
| 23      | 2        | 4.88%   |
| 21      | 2        | 4.88%   |
| 17      | 2        | 4.88%   |
| 84      | 1        | 2.44%   |
| 48      | 1        | 2.44%   |
| 43      | 1        | 2.44%   |
| 40      | 1        | 2.44%   |
| 34      | 1        | 2.44%   |
| 31      | 1        | 2.44%   |
| 26      | 1        | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 39.02%  |
| 401-500     | 7        | 17.07%  |
| Unknown     | 7        | 17.07%  |
| 601-700     | 3        | 7.32%   |
| 301-350     | 2        | 4.88%   |
| 801-900     | 1        | 2.44%   |
| 701-800     | 1        | 2.44%   |
| 351-400     | 1        | 2.44%   |
| 1501-2000   | 1        | 2.44%   |
| 1001-1500   | 1        | 2.44%   |
| 901-1000    | 1        | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 21       | 52.5%   |
| 16/10   | 7        | 17.5%   |
| Unknown | 7        | 17.5%   |
| 5/4     | 3        | 7.5%    |
| 21/9    | 1        | 2.5%    |
| 1.96    | 1        | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 8        | 19.51%  |
| 201-250        | 8        | 19.51%  |
| Unknown        | 7        | 17.07%  |
| 151-200        | 6        | 14.63%  |
| 251-300        | 4        | 9.76%   |
| 501-1000       | 3        | 7.32%   |
| 351-500        | 2        | 4.88%   |
| 141-150        | 2        | 4.88%   |
| More than 1000 | 1        | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 60%     |
| Unknown | 7        | 17.5%   |
| 1-50    | 3        | 7.5%    |
| 121-160 | 3        | 7.5%    |
| 101-120 | 3        | 7.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 86.36%  |
| 2     | 4        | 9.09%   |
| 0     | 2        | 4.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 25       | 40.98%  |
| Intel                            | 15       | 24.59%  |
| Qualcomm Atheros                 | 6        | 9.84%   |
| TP-Link                          | 4        | 6.56%   |
| Qualcomm Atheros Communications  | 2        | 3.28%   |
| Nvidia                           | 2        | 3.28%   |
| T & A Mobile Phones              | 1        | 1.64%   |
| Silicon Integrated Systems [SiS] | 1        | 1.64%   |
| Ralink Technology                | 1        | 1.64%   |
| Marvell Technology Group         | 1        | 1.64%   |
| Linksys                          | 1        | 1.64%   |
| Broadcom                         | 1        | 1.64%   |
| ASIX Electronics                 | 1        | 1.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 22       | 31.88%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 3        | 4.35%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 2.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 2        | 2.9%    |
| Nvidia MCP61 Ethernet                                                                         | 2        | 2.9%    |
| Intel Wireless 3160                                                                           | 2        | 2.9%    |
| Intel I211 Gigabit Network Connection                                                         | 2        | 2.9%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                               | 1        | 1.45%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 1.45%   |
| TP-Link Archer T4U ver.3                                                                      | 1        | 1.45%   |
| TP-Link 802.11ac NIC                                                                          | 1        | 1.45%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                                                    | 1        | 1.45%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                                 | 1        | 1.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.45%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 1.45%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 1.45%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 1.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1        | 1.45%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.45%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1        | 1.45%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 1.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1        | 1.45%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1        | 1.45%   |
| Intel Wireless 8260                                                                           | 1        | 1.45%   |
| Intel Wireless 3165                                                                           | 1        | 1.45%   |
| Intel Ethernet Connection (7) I219-LM                                                         | 1        | 1.45%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 1        | 1.45%   |
| Intel Ethernet Connection (11) I219-V                                                         | 1        | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 1.45%   |
| Intel Centrino Advanced-N 6235                                                                | 1        | 1.45%   |
| Intel 82583V Gigabit Network Connection                                                       | 1        | 1.45%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 1        | 1.45%   |
| Intel 82567LF-3 Gigabit Network Connection                                                    | 1        | 1.45%   |
| Intel 82562V-2 10/100 Network Connection                                                      | 1        | 1.45%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 1        | 1.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 7        | 29.17%  |
| Intel                           | 6        | 25%     |
| TP-Link                         | 3        | 12.5%   |
| Qualcomm Atheros                | 3        | 12.5%   |
| Qualcomm Atheros Communications | 2        | 8.33%   |
| Ralink Technology               | 1        | 4.17%   |
| Linksys                         | 1        | 4.17%   |
| Broadcom                        | 1        | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 8.33%   |
| Intel Wireless 3160                                                                           | 2        | 8.33%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 4.17%   |
| TP-Link Archer T4U ver.3                                                                      | 1        | 4.17%   |
| TP-Link 802.11ac NIC                                                                          | 1        | 4.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 4.17%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 4.17%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 4.17%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 4.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 4.17%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 4.17%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1        | 4.17%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 4.17%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1        | 4.17%   |
| Intel Wireless 8260                                                                           | 1        | 4.17%   |
| Intel Wireless 3165                                                                           | 1        | 4.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 4.17%   |
| Intel Centrino Advanced-N 6235                                                                | 1        | 4.17%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 1        | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 22       | 51.16%  |
| Intel                            | 11       | 25.58%  |
| Qualcomm Atheros                 | 3        | 6.98%   |
| Nvidia                           | 2        | 4.65%   |
| TP-Link                          | 1        | 2.33%   |
| T & A Mobile Phones              | 1        | 2.33%   |
| Silicon Integrated Systems [SiS] | 1        | 2.33%   |
| Marvell Technology Group         | 1        | 2.33%   |
| ASIX Electronics                 | 1        | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 22       | 48.89%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 6.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2        | 4.44%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 4.44%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 4.44%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1        | 2.22%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                             | 1        | 2.22%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1        | 2.22%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1        | 2.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 2.22%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 2.22%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 2.22%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 2.22%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 2.22%   |
| Intel 82583V Gigabit Network Connection                                | 1        | 2.22%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 2.22%   |
| Intel 82567LF-3 Gigabit Network Connection                             | 1        | 2.22%   |
| Intel 82562V-2 10/100 Network Connection                               | 1        | 2.22%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1        | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 41       | 65.08%  |
| WiFi     | 22       | 34.92%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 72.09%  |
| WiFi     | 12       | 27.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 28       | 65.12%  |
| 2     | 11       | 25.58%  |
| 3     | 2        | 4.65%   |
| 0     | 2        | 4.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 42       | 97.67%  |
| Yes  | 1        | 2.33%   |

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
| Intel Bluetooth wireless interface                  | 3        | 18.75%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 6.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 6.25%   |
| Intel Bluetooth Device                              | 1        | 6.25%   |
| Integrated System Solution Bluetooth Device         | 1        | 6.25%   |
| Apple Bluetooth Host Controller                     | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 28       | 37.33%  |
| Nvidia                           | 18       | 24%     |
| AMD                              | 18       | 24%     |
| Texas Instruments                | 3        | 4%      |
| Logitech                         | 3        | 4%      |
| C-Media Electronics              | 2        | 2.67%   |
| Silicon Integrated Systems [SiS] | 1        | 1.33%   |
| M2Tech                           | 1        | 1.33%   |
| Generalplus Technology           | 1        | 1.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5        | 5.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5        | 5.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 5.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4        | 4.65%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3        | 3.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3        | 3.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3        | 3.49%   |
| AMD FCH Azalia Controller                                                                         | 3        | 3.49%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2        | 2.33%   |
| Nvidia MCP61 High Definition Audio                                                                | 2        | 2.33%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 2.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2        | 2.33%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 2.33%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2        | 2.33%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                                        | 2        | 2.33%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2        | 2.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 2.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 2.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 2.33%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1        | 1.16%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1        | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1        | 1.16%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 1.16%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1        | 1.16%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 1.16%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 1.16%   |
| M2Tech hiFaceDAC UAC2                                                                             | 1        | 1.16%   |
| Logitech QuickCam Fusion                                                                          | 1        | 1.16%   |
| Logitech Logitech G PRO X Gaming Headset                                                          | 1        | 1.16%   |
| Logitech Headset H390                                                                             | 1        | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1        | 1.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 1.16%   |
| Intel CM238 HD Audio Controller                                                                   | 1        | 1.16%   |
| Intel Broadwell-U Audio Controller                                                                | 1        | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.16%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1        | 1.16%   |

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
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                   | 1        | 5.56%   |
| Samsung RAM 4D332037385432383633515A532D43463720 1GB DIMM DDR2 800MT/s  | 1        | 5.56%   |
| Patriot RAM PSD432G32002 32GB DIMM DDR4 3200MT/s                        | 1        | 5.56%   |
| Nanya RAM NT1GT64U88D0BY-AD 1GB DIMM DDR 49926MT/s                      | 1        | 5.56%   |
| Micron RAM 8JTF25664HZ-1G6M1 2048MB SODIMM DDR3 1600MT/s                | 1        | 5.56%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                               | 1        | 5.56%   |
| Kingston RAM 9905734-018.A00G 16GB DIMM DDR4 2667MT/s                   | 1        | 5.56%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s                   | 1        | 5.56%   |
| Kingston RAM 202020202020202020202020202020202020 2GB DIMM DDR2 800MT/s | 1        | 5.56%   |
| G.Skill RAM F3-19200C10-8GBZHD 8GB DIMM DDR3 1333MT/s                   | 1        | 5.56%   |
| Crucial RAM CT25664A 2GB DIMM DDR2 800MT/s                              | 1        | 5.56%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s                   | 1        | 5.56%   |

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
| 4096  | 3        | 17.65%  |
| 16384 | 2        | 11.76%  |
| 8192  | 2        | 11.76%  |
| 1024  | 2        | 11.76%  |
| 32768 | 1        | 5.88%   |

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
| 3600  | 1        | 7.14%   |
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


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Huawei HiCamera                    | 2        | 33.33%  |
| Z-Star Vimicro USB Camera (Altair) | 1        | 16.67%  |
| Microdia Sonix USB 2.0 Camera      | 1        | 16.67%  |
| Logitech HD Pro Webcam C920        | 1        | 16.67%  |
| Cubeternet HDMI to U3 capture      | 1        | 16.67%  |

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
| 0     | 34       | 79.07%  |
| 1     | 8        | 18.6%   |
| 2     | 1        | 2.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 4        | 44.44%  |
| Graphics card | 4        | 44.44%  |
| Bluetooth     | 1        | 11.11%  |

