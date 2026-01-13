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

Total: 58

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| HP            | 8433 11                  | [9dcdd4244a](https://linux-hardware.org/?probe=9dcdd4244a) | Jul 01, 2025 |
| HP            | 3032h                    | [a475597288](https://linux-hardware.org/?probe=a475597288) | Apr 24, 2025 |
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
| UbuntuDDE 20.04 | 30       | 68.18%  |
| UbuntuDDE 22.04 | 5        | 11.36%  |
| UbuntuDDE 20.10 | 3        | 6.82%   |
| UbuntuDDE 18.04 | 3        | 6.82%   |
| UbuntuDDE 21.10 | 2        | 4.55%   |
| UbuntuDDE 21.04 | 1        | 2.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| UbuntuDDE | 44       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.4.0-29-generic    | 9        | 20%     |
| 5.4.0-42-generic    | 3        | 6.67%   |
| 5.4.0-21-generic    | 3        | 6.67%   |
| 5.4.0-48-generic    | 2        | 4.44%   |
| 6.8.0-60-generic    | 1        | 2.22%   |
| 6.2.0-35-generic    | 1        | 2.22%   |
| 5.8.0-53-generic    | 1        | 2.22%   |
| 5.8.0-50-generic    | 1        | 2.22%   |
| 5.8.0-48-generic    | 1        | 2.22%   |
| 5.8.0-41-generic    | 1        | 2.22%   |
| 5.8.0-33-generic    | 1        | 2.22%   |
| 5.4.0-53-generic    | 1        | 2.22%   |
| 5.4.0-52-generic    | 1        | 2.22%   |
| 5.4.0-45-generic    | 1        | 2.22%   |
| 5.4.0-40-lowlatency | 1        | 2.22%   |
| 5.4.0-39-generic    | 1        | 2.22%   |
| 5.4.0-37-generic    | 1        | 2.22%   |
| 5.4.0-31-generic    | 1        | 2.22%   |
| 5.4.0-26-generic    | 1        | 2.22%   |
| 5.4.0-24-generic    | 1        | 2.22%   |
| 5.3.0-40-generic    | 1        | 2.22%   |
| 5.19.0-46-generic   | 1        | 2.22%   |
| 5.15.0-88-generic   | 1        | 2.22%   |
| 5.15.0-53-generic   | 1        | 2.22%   |
| 5.15.0-50-generic   | 1        | 2.22%   |
| 5.15.0-48-generic   | 1        | 2.22%   |
| 5.13.0-39-generic   | 1        | 2.22%   |
| 5.13.0-35-generic   | 1        | 2.22%   |
| 5.13.0-28-generic   | 1        | 2.22%   |
| 5.11.0-31-generic   | 1        | 2.22%   |
| 5.0.0-36-generic    | 1        | 2.22%   |
| 4.15.0-122-generic  | 1        | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 26       | 59.09%  |
| 5.8.0   | 5        | 11.36%  |
| 5.15.0  | 4        | 9.09%   |
| 5.13.0  | 2        | 4.55%   |
| 6.8.0   | 1        | 2.27%   |
| 6.2.0   | 1        | 2.27%   |
| 5.3.0   | 1        | 2.27%   |
| 5.19.0  | 1        | 2.27%   |
| 5.11.0  | 1        | 2.27%   |
| 5.0.0   | 1        | 2.27%   |
| 4.15.0  | 1        | 2.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 26       | 59.09%  |
| 5.8     | 5        | 11.36%  |
| 5.15    | 4        | 9.09%   |
| 5.13    | 2        | 4.55%   |
| 6.8     | 1        | 2.27%   |
| 6.2     | 1        | 2.27%   |
| 5.3     | 1        | 2.27%   |
| 5.19    | 1        | 2.27%   |
| 5.11    | 1        | 2.27%   |
| 5.0     | 1        | 2.27%   |
| 4.15    | 1        | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 44       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Deepin | 44       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 44       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 65.91%  |
| LightDM | 7        | 15.91%  |
| TDM     | 5        | 11.36%  |
| GDM     | 2        | 4.55%   |
| GDM3    | 1        | 2.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 17       | 38.64%  |
| pt_BR | 4        | 9.09%   |
| en_GB | 3        | 6.82%   |
| fr_FR | 2        | 4.55%   |
| fi_FI | 2        | 4.55%   |
| es_ES | 2        | 4.55%   |
| de_DE | 2        | 4.55%   |
| C     | 2        | 4.55%   |
| uk_UA | 1        | 2.27%   |
| tr_TR | 1        | 2.27%   |
| th_TH | 1        | 2.27%   |
| ru_RU | 1        | 2.27%   |
| pl_PL | 1        | 2.27%   |
| it_IT | 1        | 2.27%   |
| es_CR | 1        | 2.27%   |
| es_AR | 1        | 2.27%   |
| en_CA | 1        | 2.27%   |
| de_CH | 1        | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 26       | 59.09%  |
| EFI  | 18       | 40.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 36       | 81.82%  |
| Tmpfs   | 4        | 9.09%   |
| Xfs     | 1        | 2.27%   |
| Overlay | 1        | 2.27%   |
| Btrfs   | 1        | 2.27%   |
| Unknown | 1        | 2.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 68.18%  |
| GPT     | 10       | 22.73%  |
| MBR     | 4        | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 81.82%  |
| Yes       | 8        | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 55.56%  |
| Yes       | 20       | 44.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 12       | 27.27%  |
| MSI                 | 6        | 13.64%  |
| Gigabyte Technology | 6        | 13.64%  |
| Hewlett-Packard     | 4        | 9.09%   |
| Intel               | 3        | 6.82%   |
| Dell                | 3        | 6.82%   |
| ASRock              | 2        | 4.55%   |
| Medion              | 1        | 2.27%   |
| Fujitsu Siemens     | 1        | 2.27%   |
| Fujitsu             | 1        | 2.27%   |
| eMachines           | 1        | 2.27%   |
| ECS                 | 1        | 2.27%   |
| BANGHO              | 1        | 2.27%   |
| Acer                | 1        | 2.27%   |
| Unknown             | 1        | 2.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| MSI MS-7592                   | 3        | 6.82%   |
| MSI MS-7B84                   | 1        | 2.27%   |
| MSI MS-7816                   | 1        | 2.27%   |
| MSI MS-7693                   | 1        | 2.27%   |
| Medion MS-7848                | 1        | 2.27%   |
| Intel DQ45CB AAE30148-207     | 1        | 2.27%   |
| Intel D33217CK G76541-302     | 1        | 2.27%   |
| Intel B75                     | 1        | 2.27%   |
| HP Pavilion Desktop 590-p0xxx | 1        | 2.27%   |
| HP Compaq Elite 8300 SFF      | 1        | 2.27%   |
| HP Compaq Elite 8300 MT       | 1        | 2.27%   |
| HP 8433 11                    | 1        | 2.27%   |
| Gigabyte GB-BXi7-5500         | 1        | 2.27%   |
| Gigabyte GA-MA74GM-S2         | 1        | 2.27%   |
| Gigabyte GA-970A-D3           | 1        | 2.27%   |
| Gigabyte GA-770TA-UD3         | 1        | 2.27%   |
| Gigabyte F2A55M-HD2           | 1        | 2.27%   |
| Gigabyte B75M-D3H             | 1        | 2.27%   |
| Fujitsu Siemens ESPRIMO P5730 | 1        | 2.27%   |
| Fujitsu ESPRIMO E900          | 1        | 2.27%   |
| eMachines EL1333G             | 1        | 2.27%   |
| ECS GL307AA-ABA a6123w        | 1        | 2.27%   |
| Dell PowerEdge T40            | 1        | 2.27%   |
| Dell Inspiron 530             | 1        | 2.27%   |
| Dell Inspiron 3670            | 1        | 2.27%   |
| BANGHO CUBIC                  | 1        | 2.27%   |
| ASUS PRIME B450M-A II         | 1        | 2.27%   |
| ASUS PRIME B360M-A            | 1        | 2.27%   |
| ASUS P8Z68-V LX               | 1        | 2.27%   |
| ASUS P6X58D-E                 | 1        | 2.27%   |
| ASUS P5KPL-AM                 | 1        | 2.27%   |
| ASUS P5G41C-M LX              | 1        | 2.27%   |
| ASUS H61M-D                   | 1        | 2.27%   |
| ASUS D820MT_D820SF_BM3CE      | 1        | 2.27%   |
| ASUS CROSSHAIR V FORMULA-Z    | 1        | 2.27%   |
| ASUS All Series               | 1        | 2.27%   |
| ASUS A88X-PRO                 | 1        | 2.27%   |
| ASUS A68HM-PLUS               | 1        | 2.27%   |
| ASRock X370 Gaming K4         | 1        | 2.27%   |
| ASRock B560M-C                | 1        | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| MSI MS-7592             | 3        | 6.82%   |
| HP Compaq               | 2        | 4.55%   |
| Dell Inspiron           | 2        | 4.55%   |
| ASUS PRIME              | 2        | 4.55%   |
| MSI MS-7B84             | 1        | 2.27%   |
| MSI MS-7816             | 1        | 2.27%   |
| MSI MS-7693             | 1        | 2.27%   |
| Medion MS-7848          | 1        | 2.27%   |
| Intel DQ45CB            | 1        | 2.27%   |
| Intel D33217CK          | 1        | 2.27%   |
| Intel B75               | 1        | 2.27%   |
| HP Pavilion             | 1        | 2.27%   |
| HP 8433                 | 1        | 2.27%   |
| Gigabyte GB-BXi7-5500   | 1        | 2.27%   |
| Gigabyte GA-MA74GM-S2   | 1        | 2.27%   |
| Gigabyte GA-970A-D3     | 1        | 2.27%   |
| Gigabyte GA-770TA-UD3   | 1        | 2.27%   |
| Gigabyte F2A55M-HD2     | 1        | 2.27%   |
| Gigabyte B75M-D3H       | 1        | 2.27%   |
| Fujitsu Siemens ESPRIMO | 1        | 2.27%   |
| Fujitsu ESPRIMO         | 1        | 2.27%   |
| eMachines EL1333G       | 1        | 2.27%   |
| ECS GL307AA-ABA         | 1        | 2.27%   |
| Dell PowerEdge          | 1        | 2.27%   |
| BANGHO CUBIC            | 1        | 2.27%   |
| ASUS P8Z68-V            | 1        | 2.27%   |
| ASUS P6X58D-E           | 1        | 2.27%   |
| ASUS P5KPL-AM           | 1        | 2.27%   |
| ASUS P5G41C-M           | 1        | 2.27%   |
| ASUS H61M-D             | 1        | 2.27%   |
| ASUS D820MT             | 1        | 2.27%   |
| ASUS CROSSHAIR          | 1        | 2.27%   |
| ASUS All                | 1        | 2.27%   |
| ASUS A88X-PRO           | 1        | 2.27%   |
| ASUS A68HM-PLUS         | 1        | 2.27%   |
| ASRock X370             | 1        | 2.27%   |
| ASRock B560M-C          | 1        | 2.27%   |
| Acer ASM1610            | 1        | 2.27%   |
| Unknown                 | 1        | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 7        | 15.91%  |
| 2018 | 5        | 11.36%  |
| 2011 | 5        | 11.36%  |
| 2012 | 4        | 9.09%   |
| 2008 | 4        | 9.09%   |
| 2014 | 3        | 6.82%   |
| 2010 | 3        | 6.82%   |
| 2009 | 3        | 6.82%   |
| 2020 | 2        | 4.55%   |
| 2016 | 2        | 4.55%   |
| 2007 | 2        | 4.55%   |
| 2021 | 1        | 2.27%   |
| 2019 | 1        | 2.27%   |
| 2017 | 1        | 2.27%   |
| 2015 | 1        | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 44       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 43       | 97.73%  |
| Enabled  | 1        | 2.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 44       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 11       | 25%     |
| 4.01-8.0    | 9        | 20.45%  |
| 16.01-24.0  | 9        | 20.45%  |
| 3.01-4.0    | 8        | 18.18%  |
| 32.01-64.0  | 3        | 6.82%   |
| 2.01-3.0    | 2        | 4.55%   |
| 24.01-32.0  | 1        | 2.27%   |
| 64.01-256.0 | 1        | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 2.01-3.0 | 17       | 38.64%  |
| 1.01-2.0 | 17       | 38.64%  |
| 4.01-8.0 | 5        | 11.36%  |
| 3.01-4.0 | 3        | 6.82%   |
| 0.51-1.0 | 2        | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 45.45%  |
| 1      | 17       | 38.64%  |
| 3      | 6        | 13.64%  |
| 4      | 1        | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 50%     |
| No        | 22       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 42       | 95.45%  |
| No        | 2        | 4.55%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 23       | 52.27%  |
| No        | 21       | 47.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 61.36%  |
| Yes       | 17       | 38.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 9        | 20.45%  |
| UK         | 4        | 9.09%   |
| Brazil     | 4        | 9.09%   |
| Germany    | 3        | 6.82%   |
| Argentina  | 3        | 6.82%   |
| Portugal   | 2        | 4.55%   |
| France     | 2        | 4.55%   |
| Finland    | 2        | 4.55%   |
| Ukraine    | 1        | 2.27%   |
| Turkey     | 1        | 2.27%   |
| Thailand   | 1        | 2.27%   |
| Sweden     | 1        | 2.27%   |
| Russia     | 1        | 2.27%   |
| Poland     | 1        | 2.27%   |
| Mexico     | 1        | 2.27%   |
| Luxembourg | 1        | 2.27%   |
| Italy      | 1        | 2.27%   |
| Indonesia  | 1        | 2.27%   |
| Costa Rica | 1        | 2.27%   |
| Colombia   | 1        | 2.27%   |
| Canada     | 1        | 2.27%   |
| Belgium    | 1        | 2.27%   |
| Austria    | 1        | 2.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Helsinki              | 2        | 4.55%   |
| Yogyakarta            | 1        | 2.27%   |
| Tomah                 | 1        | 2.27%   |
| Słubice              | 1        | 2.27%   |
| St Petersburg         | 1        | 2.27%   |
| Şişli               | 1        | 2.27%   |
| Sao Paulo             | 1        | 2.27%   |
| Sao Bernardo do Campo | 1        | 2.27%   |
| Sankt Pölten         | 1        | 2.27%   |
| San Telmo             | 1        | 2.27%   |
| Rosario               | 1        | 2.27%   |
| Rome                  | 1        | 2.27%   |
| Rodgau                | 1        | 2.27%   |
| Pontpierre            | 1        | 2.27%   |
| Oakville              | 1        | 2.27%   |
| Newburgh              | 1        | 2.27%   |
| Monterrey             | 1        | 2.27%   |
| Monte Carmelo         | 1        | 2.27%   |
| Molesey               | 1        | 2.27%   |
| Milwaukee             | 1        | 2.27%   |
| Milan                 | 1        | 2.27%   |
| Lviv                  | 1        | 2.27%   |
| Lisbon                | 1        | 2.27%   |
| Las Vegas             | 1        | 2.27%   |
| La Louvière          | 1        | 2.27%   |
| Krefeld               | 1        | 2.27%   |
| Heredia               | 1        | 2.27%   |
| Enskede-Arsta-Vantoer | 1        | 2.27%   |
| Derby                 | 1        | 2.27%   |
| Dayton                | 1        | 2.27%   |
| Curitiba              | 1        | 2.27%   |
| Colorado Springs      | 1        | 2.27%   |
| Colmar                | 1        | 2.27%   |
| Buenos Aires          | 1        | 2.27%   |
| Bristol               | 1        | 2.27%   |
| Bourgoin-Jallieu      | 1        | 2.27%   |
| Bogotá               | 1        | 2.27%   |
| Bermondsey            | 1        | 2.27%   |
| Berlin                | 1        | 2.27%   |
| Bend                  | 1        | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 21     | 24.24%  |
| WDC                 | 10       | 15     | 15.15%  |
| Samsung Electronics | 9        | 9      | 13.64%  |
| Toshiba             | 8        | 8      | 12.12%  |
| Kingston            | 5        | 5      | 7.58%   |
| Hitachi             | 3        | 4      | 4.55%   |
| Crucial             | 3        | 3      | 4.55%   |
| Vaseky              | 1        | 1      | 1.52%   |
| SanDisk             | 1        | 1      | 1.52%   |
| PNY                 | 1        | 2      | 1.52%   |
| Plextor             | 1        | 1      | 1.52%   |
| Maxtor              | 1        | 1      | 1.52%   |
| Leven               | 1        | 1      | 1.52%   |
| KingFast            | 1        | 1      | 1.52%   |
| JMicron Technology  | 1        | 1      | 1.52%   |
| Integral            | 1        | 1      | 1.52%   |
| GOODRAM             | 1        | 1      | 1.52%   |
| China               | 1        | 1      | 1.52%   |
| ADATA Technology    | 1        | 1      | 1.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB             | 5        | 6.85%   |
| Seagate ST1000DM010-2EP102 1TB     | 3        | 4.11%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 2        | 2.74%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 2.74%   |
| Samsung SSD 850 EVO 250GB          | 2        | 2.74%   |
| WDC WDBNCE2500PNC 250GB SSD        | 1        | 1.37%   |
| WDC WD7501AALS-75J7B0 752GB        | 1        | 1.37%   |
| WDC WD60EDAZ-11BMZB0 6TB           | 1        | 1.37%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 1.37%   |
| WDC WD3200AAJS-00B4A0 320GB        | 1        | 1.37%   |
| WDC WD30EZRX-00MMMB0 3TB           | 1        | 1.37%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1        | 1.37%   |
| WDC WD2500AAKX-001CA0 250GB        | 1        | 1.37%   |
| WDC WD2002FAEX-007BA0 2TB          | 1        | 1.37%   |
| WDC WD1003FZEX-00K3CA0 1TB         | 1        | 1.37%   |
| Vaseky V800/128G 128GB SSD         | 1        | 1.37%   |
| Toshiba THNSFC128GBSJ SSD          | 1        | 1.37%   |
| Toshiba MQ01ABD100 1TB             | 1        | 1.37%   |
| Toshiba MK3275GSX 320GB            | 1        | 1.37%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1.37%   |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 1.37%   |
| Seagate ST4000DM 004-2CV104 4TB    | 1        | 1.37%   |
| Seagate ST3500630AS 500GB          | 1        | 1.37%   |
| Seagate ST3500413AS 500GB          | 1        | 1.37%   |
| Seagate ST3500312CS 500GB          | 1        | 1.37%   |
| Seagate ST3320418AS 320GB          | 1        | 1.37%   |
| Seagate ST3250820AS 250GB          | 1        | 1.37%   |
| Seagate ST31000524AS 1TB           | 1        | 1.37%   |
| Seagate ST2000DM001-9YN164 2TB     | 1        | 1.37%   |
| Seagate ST2000DM001-1ER164 2TB     | 1        | 1.37%   |
| Seagate ST1000VT000 HN-M101MBB 1TB | 1        | 1.37%   |
| Seagate ST1000LM014-1EJ164 1TB     | 1        | 1.37%   |
| Seagate ST1000DM003-1SB102 1TB     | 1        | 1.37%   |
| Seagate ST1000DM003-1CH162 1TB     | 1        | 1.37%   |
| SanDisk SSD PLUS 240 GB            | 1        | 1.37%   |
| Samsung SSD 850 EVO 500GB          | 1        | 1.37%   |
| Samsung SSD 850 EVO 1TB            | 1        | 1.37%   |
| Samsung NVMe SSD Drive 512GB       | 1        | 1.37%   |
| Samsung HM250HI 250GB              | 1        | 1.37%   |
| Samsung HD161HJ 160GB              | 1        | 1.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 21     | 40%     |
| WDC                 | 9        | 11     | 22.5%   |
| Toshiba             | 7        | 7      | 17.5%   |
| Samsung Electronics | 4        | 4      | 10%     |
| Hitachi             | 3        | 4      | 7.5%    |
| Maxtor              | 1        | 1      | 2.5%    |

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
| HDD     | 34       | 48     | 58.62%  |
| SSD     | 20       | 26     | 34.48%  |
| NVMe    | 3        | 3      | 5.17%   |
| Unknown | 1        | 1      | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 43       | 73     | 89.58%  |
| NVMe | 3        | 3      | 6.25%   |
| SAS  | 2        | 2      | 4.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 28       | 38     | 49.12%  |
| 0.51-1.0   | 20       | 24     | 35.09%  |
| 1.01-2.0   | 4        | 5      | 7.02%   |
| 3.01-4.0   | 2        | 2      | 3.51%   |
| 2.01-3.0   | 2        | 3      | 3.51%   |
| 4.01-10.0  | 1        | 2      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 16       | 36.36%  |
| 1001-2000      | 8        | 18.18%  |
| 251-500        | 6        | 13.64%  |
| 501-1000       | 6        | 13.64%  |
| 51-100         | 3        | 6.82%   |
| More than 3000 | 2        | 4.55%   |
| 21-50          | 2        | 4.55%   |
| Unknown        | 1        | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 23       | 52.27%  |
| 101-250   | 7        | 15.91%  |
| 251-500   | 4        | 9.09%   |
| 51-100    | 3        | 6.82%   |
| 21-50     | 2        | 4.55%   |
| 1001-2000 | 2        | 4.55%   |
| 501-1000  | 2        | 4.55%   |
| Unknown   | 1        | 2.27%   |

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
| Detected | 35       | 63     | 76.09%  |
| Works    | 9        | 13     | 19.57%  |
| Malfunc  | 2        | 2      | 4.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 28       | 51.85%  |
| AMD                              | 13       | 24.07%  |
| Samsung Electronics              | 3        | 5.56%   |
| Nvidia                           | 2        | 3.7%    |
| Marvell Technology Group         | 2        | 3.7%    |
| ASMedia Technology               | 2        | 3.7%    |
| Silicon Integrated Systems [SiS] | 1        | 1.85%   |
| Kingston Technology Company      | 1        | 1.85%   |
| JMicron Technology               | 1        | 1.85%   |
| ADATA Technology                 | 1        | 1.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 7        | 9.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5        | 6.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4        | 5.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3        | 3.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3        | 3.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3        | 3.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 2.63%   |
| Nvidia MCP61 SATA Controller                                                     | 2        | 2.63%   |
| Nvidia MCP61 IDE                                                                 | 2        | 2.63%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s controller [IDE mode]                    | 2        | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2        | 2.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 2.63%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                       | 2        | 2.63%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                       | 2        | 2.63%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2        | 2.63%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 2        | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2        | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2        | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2        | 2.63%   |
| AMD 300 Series Chipset SATA Controller                                           | 2        | 2.63%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1        | 1.32%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1        | 1.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1        | 1.32%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                       | 1        | 1.32%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1        | 1.32%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1        | 1.32%   |
| Intel SATA Controller [RAID Mode]                                                | 1        | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 1.32%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 1.32%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1        | 1.32%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 1        | 1.32%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 1        | 1.32%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 1        | 1.32%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 1        | 1.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1        | 1.32%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1        | 1.32%   |
| AMD X370 Series Chipset SATA Controller                                          | 1        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [RAID5 mode]                               | 1        | 1.32%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1        | 1.32%   |
| AMD FCH IDE Controller                                                           | 1        | 1.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 29       | 55.77%  |
| IDE  | 16       | 30.77%  |
| NVMe | 5        | 9.62%   |
| RAID | 2        | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 29       | 65.91%  |
| AMD    | 15       | 34.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i3-3220 CPU @ 3.30GHz                | 2        | 4.55%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 2        | 4.55%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 2        | 4.55%   |
| Intel Xeon E-2224G CPU @ 3.50GHz                | 1        | 2.27%   |
| Intel Xeon CPU E5450 @ 3.00GHz                  | 1        | 2.27%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz     | 1        | 2.27%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 1        | 2.27%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz          | 1        | 2.27%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz              | 1        | 2.27%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 2.27%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1        | 2.27%   |
| Intel Core i7-2700K CPU @ 3.50GHz               | 1        | 2.27%   |
| Intel Core i7 CPU 950 @ 3.07GHz                 | 1        | 2.27%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1        | 2.27%   |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1        | 2.27%   |
| Intel Core i5-4670K CPU @ 3.40GHz               | 1        | 2.27%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1        | 2.27%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 1        | 2.27%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 2.27%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 1        | 2.27%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 2.27%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1        | 2.27%   |
| Intel Core i3-3217U CPU @ 1.80GHz               | 1        | 2.27%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz           | 1        | 2.27%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz           | 1        | 2.27%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz           | 1        | 2.27%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz            | 1        | 2.27%   |
| Intel Core 2 CPU 6320 @ 1.86GHz                 | 1        | 2.27%   |
| Intel Celeron CPU N3000 @ 1.04GHz               | 1        | 2.27%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz         | 1        | 2.27%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 1        | 2.27%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 2.27%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1        | 2.27%   |
| AMD Phenom II X6 1055T Processor                | 1        | 2.27%   |
| AMD Phenom II X4 945 Processor                  | 1        | 2.27%   |
| AMD Phenom 9650 Quad-Core Processor             | 1        | 2.27%   |
| AMD FX-9590 Eight-Core Processor                | 1        | 2.27%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 2.27%   |
| AMD Athlon Dual Core Processor 4850e            | 1        | 2.27%   |
| AMD Athlon 64 X2 Dual Core Processor 4400+      | 1        | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 8        | 18.18%  |
| Intel Core i7           | 5        | 11.36%  |
| Intel Core i3           | 4        | 9.09%   |
| AMD Ryzen 5             | 4        | 9.09%   |
| Intel Core 2 Quad       | 3        | 6.82%   |
| Intel Xeon              | 2        | 4.55%   |
| Intel Pentium Dual-Core | 2        | 4.55%   |
| AMD FX                  | 2        | 4.55%   |
| AMD A10                 | 2        | 4.55%   |
| Other                   | 1        | 2.27%   |
| Intel Pentium Dual      | 1        | 2.27%   |
| Intel Core 2 Duo        | 1        | 2.27%   |
| Intel Core 2            | 1        | 2.27%   |
| Intel Celeron           | 1        | 2.27%   |
| AMD Ryzen 7             | 1        | 2.27%   |
| AMD Phenom II X6        | 1        | 2.27%   |
| AMD Phenom II X4        | 1        | 2.27%   |
| AMD Phenom              | 1        | 2.27%   |
| AMD Athlon Dual Core    | 1        | 2.27%   |
| AMD Athlon 64 X2        | 1        | 2.27%   |
| AMD A4                  | 1        | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 23       | 52.27%  |
| 2      | 14       | 31.82%  |
| 6      | 5        | 11.36%  |
| 8      | 1        | 2.27%   |
| 1      | 1        | 2.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 44       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 59.09%  |
| 2      | 18       | 40.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 44       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 27.27%  |
| 0x306a9    | 6        | 13.64%  |
| 0x1067a    | 4        | 9.09%   |
| 0x306c3    | 2        | 4.55%   |
| 0x10677    | 2        | 4.55%   |
| 0x06000852 | 2        | 4.55%   |
| 0x906ed    | 1        | 2.27%   |
| 0x906eb    | 1        | 2.27%   |
| 0x906ea    | 1        | 2.27%   |
| 0x6fd      | 1        | 2.27%   |
| 0x6f6      | 1        | 2.27%   |
| 0x506e3    | 1        | 2.27%   |
| 0x406c3    | 1        | 2.27%   |
| 0x306d4    | 1        | 2.27%   |
| 0x206a7    | 1        | 2.27%   |
| 0x106a5    | 1        | 2.27%   |
| 0x08701021 | 1        | 2.27%   |
| 0x08101016 | 1        | 2.27%   |
| 0x08001138 | 1        | 2.27%   |
| 0x06003106 | 1        | 2.27%   |
| 0x010000dc | 1        | 2.27%   |
| 0x01000083 | 1        | 2.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 6        | 13.64%  |
| IvyBridge   | 6        | 13.64%  |
| KabyLake    | 4        | 9.09%   |
| Zen         | 3        | 6.82%   |
| Piledriver  | 3        | 6.82%   |
| K10         | 3        | 6.82%   |
| Haswell     | 3        | 6.82%   |
| Core        | 3        | 6.82%   |
| Steamroller | 2        | 4.55%   |
| SandyBridge | 2        | 4.55%   |
| K8 Hammer   | 2        | 4.55%   |
| Zen+        | 1        | 2.27%   |
| Zen 2       | 1        | 2.27%   |
| Skylake     | 1        | 2.27%   |
| Silvermont  | 1        | 2.27%   |
| Nehalem     | 1        | 2.27%   |
| Broadwell   | 1        | 2.27%   |
| Unknown     | 1        | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 19       | 40.43%  |
| AMD                              | 15       | 31.91%  |
| Intel                            | 12       | 25.53%  |
| Silicon Integrated Systems [SiS] | 1        | 2.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 8.33%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 6.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 4.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 4.17%   |
| AMD RV770 [Radeon HD 4850]                                                               | 2        | 4.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 4.17%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 4.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 4.17%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 4.17%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1        | 2.08%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 2.08%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 2.08%   |
| Nvidia GT215 [GeForce GT 320]                                                            | 1        | 2.08%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1        | 2.08%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1        | 2.08%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 2.08%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                                        | 1        | 2.08%   |
| Nvidia GF119 [GeForce GT 705]                                                            | 1        | 2.08%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1        | 2.08%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 2.08%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1        | 2.08%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 2.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 2.08%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 1        | 2.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                               | 1        | 2.08%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 1        | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1        | 2.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 2.08%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 1        | 2.08%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 1        | 2.08%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 2.08%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 1        | 2.08%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 1        | 2.08%   |
| AMD Barts PRO [Radeon HD 6850]                                                           | 1        | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 18       | 40.91%  |
| 1 x AMD      | 13       | 29.55%  |
| 1 x Intel    | 10       | 22.73%  |
| 2 x AMD      | 1        | 2.27%   |
| 1 x SiS      | 1        | 2.27%   |
| AMD + Nvidia | 1        | 2.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 32       | 72.73%  |
| Proprietary | 10       | 22.73%  |
| Unknown     | 2        | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 40.91%  |
| 0.51-1.0   | 13       | 29.55%  |
| 3.01-4.0   | 6        | 13.64%  |
| 1.01-2.0   | 5        | 11.36%  |
| 7.01-8.0   | 1        | 2.27%   |
| 0.01-0.5   | 1        | 2.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Hewlett-Packard      | 6        | 14.29%  |
| Samsung Electronics  | 5        | 11.9%   |
| Goldstar             | 4        | 9.52%   |
| Dell                 | 4        | 9.52%   |
| Ancor Communications | 3        | 7.14%   |
| Philips              | 2        | 4.76%   |
| BenQ                 | 2        | 4.76%   |
| ASUSTek Computer     | 2        | 4.76%   |
| Acer                 | 2        | 4.76%   |
| Vizio                | 1        | 2.38%   |
| ViewSonic            | 1        | 2.38%   |
| Vestel Elektronik    | 1        | 2.38%   |
| Unknown              | 1        | 2.38%   |
| Toshiba              | 1        | 2.38%   |
| SKY                  | 1        | 2.38%   |
| LG Electronics       | 1        | 2.38%   |
| Lenovo               | 1        | 2.38%   |
| Insignia             | 1        | 2.38%   |
| HPN                  | 1        | 2.38%   |
| HannStar             | 1        | 2.38%   |
| Fujitsu Siemens      | 1        | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Vizio LCD Monitor VIZ0026 1360x768 580x320mm 26.1-inch               | 1        | 2.22%   |
| ViewSonic VA912-4SERIES VSC721C 1280x1024 376x301mm 19.0-inch        | 1        | 2.22%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch | 1        | 2.22%   |
| Unknown LCD Monitor Sony 55R617 1920x1080                            | 1        | 2.22%   |
| Toshiba TV TSB0200 1920x1080 410x230mm 18.5-inch                     | 1        | 2.22%   |
| SKY TV-monitor SKY0001 1920x1080 885x498mm 40.0-inch                 | 1        | 2.22%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch    | 1        | 2.22%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch    | 1        | 2.22%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch    | 1        | 2.22%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1        | 2.22%   |
| Samsung Electronics LCD Monitor SAM0E4C 1360x768 522x293mm 23.6-inch | 1        | 2.22%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 1        | 2.22%   |
| Philips LCD Monitor 150C4 1024x768                                   | 1        | 2.22%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                   | 1        | 2.22%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 1        | 2.22%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch              | 1        | 2.22%   |
| Insignia NS-19E320A13 BBY0032 1680x1050 640x384mm 29.4-inch          | 1        | 2.22%   |
| HPN LCD Monitor HP 24o 1920x1080                                     | 1        | 2.22%   |
| Hewlett-Packard ZR2240w HWP2952 1920x1080 475x267mm 21.5-inch        | 1        | 2.22%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch          | 1        | 2.22%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 510x287mm 23.0-inch         | 1        | 2.22%   |
| Hewlett-Packard L1740 HWP2649 1280x1024 337x270mm 17.0-inch          | 1        | 2.22%   |
| Hewlett-Packard 24o HPN337C 1920x1080 531x299mm 24.0-inch            | 1        | 2.22%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch            | 1        | 2.22%   |
| HannStar iH282 HSD20E6 1920x1200 593x371mm 27.5-inch                 | 1        | 2.22%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 1        | 2.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 1        | 2.22%   |
| Goldstar E2742 GSM58C9 1920x1080 598x337mm 27.0-inch                 | 1        | 2.22%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 1        | 2.22%   |
| Fujitsu Siemens L20T-2 LED FUS07E3 1600x900 442x249mm 20.0-inch      | 1        | 2.22%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1        | 2.22%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                     | 1        | 2.22%   |
| Dell S2722DGM DEL423A 2560x1440 597x336mm 27.0-inch                  | 1        | 2.22%   |
| Dell LCD Monitor ST2220L 3840x1080                                   | 1        | 2.22%   |
| Dell LCD Monitor ST2220L                                             | 1        | 2.22%   |
| BenQ G2020HD BNQ781F 1600x900 443x249mm 20.0-inch                    | 1        | 2.22%   |
| BenQ EW2775ZH BNQ7944 1920x1080 598x336mm 27.0-inch                  | 1        | 2.22%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch         | 1        | 2.22%   |
| ASUSTek Computer VA27EQSB AUS27C4 1920x1080 598x336mm 27.0-inch      | 1        | 2.22%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch     | 1        | 2.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 14       | 31.82%  |
| 3840x2160 (4K)    | 6        | 13.64%  |
| 1920x1200 (WUXGA) | 4        | 9.09%   |
| 1600x900 (HD+)    | 3        | 6.82%   |
| 1280x1024 (SXGA)  | 3        | 6.82%   |
| 3840x1080         | 2        | 4.55%   |
| 2560x1080         | 2        | 4.55%   |
| 1440x900 (WXGA+)  | 2        | 4.55%   |
| Unknown           | 2        | 4.55%   |
| 2560x1440 (QHD)   | 1        | 2.27%   |
| 1920x540          | 1        | 2.27%   |
| 1366x768 (WXGA)   | 1        | 2.27%   |
| 1360x768          | 1        | 2.27%   |
| 1280x720 (HD)     | 1        | 2.27%   |
| 1024x768 (XGA)    | 1        | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 8        | 19.05%  |
| 24      | 8        | 19.05%  |
| Unknown | 7        | 16.67%  |
| 20      | 3        | 7.14%   |
| 19      | 3        | 7.14%   |
| 31      | 2        | 4.76%   |
| 21      | 2        | 4.76%   |
| 17      | 2        | 4.76%   |
| 84      | 1        | 2.38%   |
| 48      | 1        | 2.38%   |
| 43      | 1        | 2.38%   |
| 40      | 1        | 2.38%   |
| 34      | 1        | 2.38%   |
| 26      | 1        | 2.38%   |
| 23      | 1        | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 38.1%   |
| 401-500     | 7        | 16.67%  |
| Unknown     | 7        | 16.67%  |
| 601-700     | 4        | 9.52%   |
| 301-350     | 2        | 4.76%   |
| 801-900     | 1        | 2.38%   |
| 701-800     | 1        | 2.38%   |
| 351-400     | 1        | 2.38%   |
| 1501-2000   | 1        | 2.38%   |
| 1001-1500   | 1        | 2.38%   |
| 901-1000    | 1        | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 22       | 53.66%  |
| 16/10   | 7        | 17.07%  |
| Unknown | 7        | 17.07%  |
| 5/4     | 3        | 7.32%   |
| 21/9    | 1        | 2.44%   |
| 1.96    | 1        | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 8        | 19.05%  |
| 201-250        | 8        | 19.05%  |
| Unknown        | 7        | 16.67%  |
| 151-200        | 6        | 14.29%  |
| 251-300        | 4        | 9.52%   |
| 351-500        | 3        | 7.14%   |
| 501-1000       | 3        | 7.14%   |
| 141-150        | 2        | 4.76%   |
| More than 1000 | 1        | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 58.54%  |
| Unknown | 7        | 17.07%  |
| 1-50    | 4        | 9.76%   |
| 121-160 | 3        | 7.32%   |
| 101-120 | 3        | 7.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 86.67%  |
| 2     | 4        | 8.89%   |
| 0     | 2        | 4.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 26       | 41.94%  |
| Intel                            | 15       | 24.19%  |
| Qualcomm Atheros                 | 6        | 9.68%   |
| TP-Link                          | 4        | 6.45%   |
| Qualcomm Atheros Communications  | 2        | 3.23%   |
| Nvidia                           | 2        | 3.23%   |
| T & A Mobile Phones              | 1        | 1.61%   |
| Silicon Integrated Systems [SiS] | 1        | 1.61%   |
| Ralink Technology                | 1        | 1.61%   |
| Marvell Technology Group         | 1        | 1.61%   |
| Linksys                          | 1        | 1.61%   |
| Broadcom                         | 1        | 1.61%   |
| ASIX Electronics                 | 1        | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 23       | 32.39%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 3        | 4.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 2.82%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 2.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 2        | 2.82%   |
| Nvidia MCP61 Ethernet                                                                         | 2        | 2.82%   |
| Intel Wireless 3160                                                                           | 2        | 2.82%   |
| Intel I211 Gigabit Network Connection                                                         | 2        | 2.82%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                               | 1        | 1.41%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 1.41%   |
| TP-Link Archer T4U ver.3                                                                      | 1        | 1.41%   |
| TP-Link 802.11ac NIC                                                                          | 1        | 1.41%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                                                    | 1        | 1.41%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                                 | 1        | 1.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 1.41%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 1.41%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 1.41%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 1.41%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1        | 1.41%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.41%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1        | 1.41%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 1.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1        | 1.41%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1        | 1.41%   |
| Intel Wireless 8260                                                                           | 1        | 1.41%   |
| Intel Wireless 3165                                                                           | 1        | 1.41%   |
| Intel Ethernet Connection (7) I219-LM                                                         | 1        | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 1        | 1.41%   |
| Intel Ethernet Connection (11) I219-V                                                         | 1        | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 1.41%   |
| Intel Centrino Advanced-N 6235                                                                | 1        | 1.41%   |
| Intel 82583V Gigabit Network Connection                                                       | 1        | 1.41%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 1        | 1.41%   |
| Intel 82567LF-3 Gigabit Network Connection                                                    | 1        | 1.41%   |
| Intel 82562V-2 10/100 Network Connection                                                      | 1        | 1.41%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 1        | 1.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 8        | 32%     |
| Intel                           | 6        | 24%     |
| TP-Link                         | 3        | 12%     |
| Qualcomm Atheros                | 3        | 12%     |
| Qualcomm Atheros Communications | 2        | 8%      |
| Ralink Technology               | 1        | 4%      |
| Linksys                         | 1        | 4%      |
| Broadcom                        | 1        | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 8%      |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 8%      |
| Intel Wireless 3160                                                                           | 2        | 8%      |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 4%      |
| TP-Link Archer T4U ver.3                                                                      | 1        | 4%      |
| TP-Link 802.11ac NIC                                                                          | 1        | 4%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 4%      |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 4%      |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 4%      |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 4%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 4%      |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 4%      |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 4%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1        | 4%      |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 4%      |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1        | 4%      |
| Intel Wireless 8260                                                                           | 1        | 4%      |
| Intel Wireless 3165                                                                           | 1        | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 4%      |
| Intel Centrino Advanced-N 6235                                                                | 1        | 4%      |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 1        | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 23       | 52.27%  |
| Intel                            | 11       | 25%     |
| Qualcomm Atheros                 | 3        | 6.82%   |
| Nvidia                           | 2        | 4.55%   |
| TP-Link                          | 1        | 2.27%   |
| T & A Mobile Phones              | 1        | 2.27%   |
| Silicon Integrated Systems [SiS] | 1        | 2.27%   |
| Marvell Technology Group         | 1        | 2.27%   |
| ASIX Electronics                 | 1        | 2.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 23       | 50%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 6.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2        | 4.35%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 4.35%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 4.35%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1        | 2.17%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                             | 1        | 2.17%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1        | 2.17%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1        | 2.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 2.17%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 2.17%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 2.17%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 2.17%   |
| Intel 82583V Gigabit Network Connection                                | 1        | 2.17%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 2.17%   |
| Intel 82567LF-3 Gigabit Network Connection                             | 1        | 2.17%   |
| Intel 82562V-2 10/100 Network Connection                               | 1        | 2.17%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1        | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 42       | 64.62%  |
| WiFi     | 23       | 35.38%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 71.11%  |
| WiFi     | 13       | 28.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 28       | 63.64%  |
| 2     | 12       | 27.27%  |
| 3     | 2        | 4.55%   |
| 0     | 2        | 4.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 43       | 97.73%  |
| Yes  | 1        | 2.27%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 35.29%  |
| Cambridge Silicon Radio         | 6        | 35.29%  |
| Realtek Semiconductor           | 2        | 11.76%  |
| Qualcomm Atheros Communications | 1        | 5.88%   |
| Integrated System Solution      | 1        | 5.88%   |
| Apple                           | 1        | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 35.29%  |
| Intel Bluetooth wireless interface                  | 4        | 23.53%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 11.76%  |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 5.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.88%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 5.88%   |
| Integrated System Solution Bluetooth Device         | 1        | 5.88%   |
| Apple Bluetooth Host Controller                     | 1        | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 28       | 36.36%  |
| Nvidia                           | 19       | 24.68%  |
| AMD                              | 19       | 24.68%  |
| Texas Instruments                | 3        | 3.9%    |
| Logitech                         | 3        | 3.9%    |
| C-Media Electronics              | 2        | 2.6%    |
| Silicon Integrated Systems [SiS] | 1        | 1.3%    |
| M2Tech                           | 1        | 1.3%    |
| Generalplus Technology           | 1        | 1.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5        | 5.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5        | 5.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 5.62%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4        | 4.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4        | 4.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3        | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 3.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3        | 3.37%   |
| AMD FCH Azalia Controller                                                                         | 3        | 3.37%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2        | 2.25%   |
| Nvidia MCP61 High Definition Audio                                                                | 2        | 2.25%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 2.25%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2        | 2.25%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 2.25%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2        | 2.25%   |
| AMD Ryzen HD Audio Controller                                                                     | 2        | 2.25%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                                        | 2        | 2.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 2.25%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2        | 2.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 2.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 2.25%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 2.25%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1        | 1.12%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1        | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 1.12%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1        | 1.12%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 1.12%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 1.12%   |
| M2Tech hiFaceDAC UAC2                                                                             | 1        | 1.12%   |
| Logitech QuickCam Fusion                                                                          | 1        | 1.12%   |
| Logitech Logitech G PRO X Gaming Headset                                                          | 1        | 1.12%   |
| Logitech Headset H390                                                                             | 1        | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1        | 1.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 1.12%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 1.12%   |
| Intel CM238 HD Audio Controller                                                                   | 1        | 1.12%   |
| Intel Broadwell-U Audio Controller                                                                | 1        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 1.12%   |

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
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s                   | 1        | 5.56%   |
| Samsung RAM 4D332037385432383633515A532D43463720 1GB DIMM DDR2 800MT/s  | 1        | 5.56%   |
| Patriot RAM PSD432G32002 32GB DIMM DDR4 3200MT/s                        | 1        | 5.56%   |
| Nanya RAM NT1GT64U88D0BY-AD 1GB DIMM DDR2 49926MT/s                     | 1        | 5.56%   |
| Micron RAM 8JTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s                   | 1        | 5.56%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                               | 1        | 5.56%   |
| Kingston RAM 9905734-018.A00G 16GB DIMM DDR4 2932MT/s                   | 1        | 5.56%   |
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
| 32768 | 2        | 11.76%  |
| 16384 | 2        | 11.76%  |
| 1024  | 2        | 11.76%  |
| 8192  | 1        | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 800   | 4        | 28.57%  |
| 3200  | 2        | 14.29%  |
| 1600  | 2        | 14.29%  |
| 1333  | 2        | 14.29%  |
| 49926 | 1        | 7.14%   |
| 3600  | 1        | 7.14%   |
| 2932  | 1        | 7.14%   |
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
| Logitech                | 2        | 28.57%  |
| Huawei Technologies     | 2        | 28.57%  |
| Z-Star Microelectronics | 1        | 14.29%  |
| Microdia                | 1        | 14.29%  |
| Cubeternet              | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Huawei HiCamera                   | 2        | 28.57%  |
| Z-Star A4 TECH USB2.0 PC Camera E | 1        | 14.29%  |
| Microdia Sonix USB 2.0 Camera     | 1        | 14.29%  |
| Logitech Webcam C170              | 1        | 14.29%  |
| Logitech HD Pro Webcam C920       | 1        | 14.29%  |
| Cubeternet HDMI to U3 capture     | 1        | 14.29%  |

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
| 0     | 35       | 79.55%  |
| 1     | 8        | 18.18%  |
| 2     | 1        | 2.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 5        | 50%     |
| Graphics card | 4        | 40%     |
| Bluetooth     | 1        | 10%     |

