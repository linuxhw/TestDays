Ubuntu Budgie 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

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

Total: 42

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu  | D3233-A1 S26361-D3233-A1    | [4622902df7](https://linux-hardware.org/?probe=4622902df7) | Jun 17, 2023 |
| Gigabyte | GA-890GPA-UD3H              | [f04b28a0e5](https://linux-hardware.org/?probe=f04b28a0e5) | Jun 10, 2023 |
| ASRock   | B450M Steel Legend          | [5d75bba35e](https://linux-hardware.org/?probe=5d75bba35e) | Jun 06, 2023 |
| Gigabyte | H310M HD2                   | [b28787ecb7](https://linux-hardware.org/?probe=b28787ecb7) | Jun 04, 2023 |
| ASUSTek  | ROG STRIX X670E-E GAMING... | [f87233a295](https://linux-hardware.org/?probe=f87233a295) | Apr 29, 2023 |
| Intel    | H61                         | [b8f0acdf61](https://linux-hardware.org/?probe=b8f0acdf61) | Apr 28, 2023 |
| MSI      | X99S SLI PLUS               | [8c6fb84b12](https://linux-hardware.org/?probe=8c6fb84b12) | Feb 09, 2023 |
| ASRock   | FM2A88X Extreme4+           | [9f812fe2a7](https://linux-hardware.org/?probe=9f812fe2a7) | Feb 02, 2023 |
| Fujitsu  | D3183-A1 S26361-D3183-A1    | [bfb86ee660](https://linux-hardware.org/?probe=bfb86ee660) | Jan 29, 2023 |
| Lenovo   | 36F7 SDK0J40700 WIN 3258... | [831fd897ec](https://linux-hardware.org/?probe=831fd897ec) | Jan 25, 2023 |
| Lenovo   | ThinkStation C20 4263BA7    | [38ff99d952](https://linux-hardware.org/?probe=38ff99d952) | Jan 10, 2023 |
| Fujitsu  | D3348-B2 S26361-D3348-B2    | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu  | D3348-B2 S26361-D3348-B2    | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Fujitsu  | D3348-B2 S26361-D3348-B2    | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Dell     | 0RW199                      | [2a2fa5baf8](https://linux-hardware.org/?probe=2a2fa5baf8) | Nov 20, 2022 |
| MSI      | B550M PRO-VDH WIFI          | [afb716fb12](https://linux-hardware.org/?probe=afb716fb12) | Nov 18, 2022 |
| Dell     | 0C27VV A01                  | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| MSI      | B450-A PRO MAX              | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| Dell     | 0C27VV A01                  | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell     | 0C27VV A01                  | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Gigabyte | M68MT-S2                    | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| Gigabyte | B75M-D3P                    | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte | M68MT-S2                    | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Gigabyte | X570S AORUS PRO AX          | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel    | DP55WB AAE64798-206         | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| ASUSTek  | A88X-PRO                    | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Intel    | X79M-S                      | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| HP       | 828A                        | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| Biostar  | A960D+V3                    | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock   | A300M-STX                   | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock   | A300M-STX                   | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Intel    | STK1A32SC H95551-301        | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Gigabyte | GA-890GPA-UD3H              | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP       | 212B                        | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| Gigabyte | B75M-D3H                    | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Gigabyte | F2A78M-HD2                  | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek  | PRIME B560M-A               | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| MSI      | X370 GAMING PRO CARBON      | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Gigabyte | B75M-D3H                    | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte | B450 I AORUS PRO WIFI-CF    | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| HP       | 1825                        | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Gigabyte | B550 AORUS ELITE AX V2      | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.0-52-generic      | 4        | 11.43%  |
| 5.15.0-57-generic      | 3        | 8.57%   |
| 5.15.0-46-generic      | 3        | 8.57%   |
| 5.15.0-43-generic      | 3        | 8.57%   |
| 5.15.0-30-generic      | 3        | 8.57%   |
| 5.19.0-40-generic      | 2        | 5.71%   |
| 5.15.0-33-generic      | 2        | 5.71%   |
| 5.15.0-27-generic      | 2        | 5.71%   |
| 5.15.0-25-generic      | 2        | 5.71%   |
| 5.19.0-45-generic      | 1        | 2.86%   |
| 5.17.2-051702-generic  | 1        | 2.86%   |
| 5.15.92-051592-generic | 1        | 2.86%   |
| 5.15.0-73-generic      | 1        | 2.86%   |
| 5.15.0-71-generic      | 1        | 2.86%   |
| 5.15.0-56-generic      | 1        | 2.86%   |
| 5.15.0-50-generic      | 1        | 2.86%   |
| 5.15.0-48-generic      | 1        | 2.86%   |
| 5.15.0-47-generic      | 1        | 2.86%   |
| 5.15.0-41-generic      | 1        | 2.86%   |
| 5.13.0-44-generic      | 1        | 2.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 27       | 81.82%  |
| 5.19.0  | 3        | 9.09%   |
| 5.17.2  | 1        | 3.03%   |
| 5.15.92 | 1        | 3.03%   |
| 5.13.0  | 1        | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 28       | 84.85%  |
| 5.19    | 3        | 9.09%   |
| 5.17    | 1        | 3.03%   |
| 5.13    | 1        | 3.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 32       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 32       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 32       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 23       | 71.88%  |
| Unknown | 8        | 25%     |
| GDM     | 1        | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 15       | 46.88%  |
| de_DE | 5        | 15.63%  |
| pt_BR | 2        | 6.25%   |
| fr_FR | 2        | 6.25%   |
| es_ES | 2        | 6.25%   |
| en_GB | 2        | 6.25%   |
| es_MX | 1        | 3.13%   |
| en_ZA | 1        | 3.13%   |
| en_CA | 1        | 3.13%   |
| el_GR | 1        | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 22       | 66.67%  |
| EFI  | 11       | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 27       | 84.38%  |
| Overlay | 3        | 9.38%   |
| Zfs     | 1        | 3.13%   |
| Btrfs   | 1        | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 18       | 54.55%  |
| Unknown | 15       | 45.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 78.13%  |
| Yes       | 7        | 21.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 62.5%   |
| Yes       | 12       | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 9        | 28.13%  |
| MSI                 | 4        | 12.5%   |
| Intel               | 3        | 9.38%   |
| Hewlett-Packard     | 3        | 9.38%   |
| Fujitsu             | 3        | 9.38%   |
| ASUSTek Computer    | 3        | 9.38%   |
| ASRock              | 3        | 9.38%   |
| Dell                | 2        | 6.25%   |
| Lenovo              | 1        | 3.13%   |
| Biostar             | 1        | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| MSI MS-7C95                        | 1        | 3.13%   |
| MSI MS-7B86                        | 1        | 3.13%   |
| MSI MS-7A32                        | 1        | 3.13%   |
| MSI MS-7885                        | 1        | 3.13%   |
| Lenovo ThinkStation C20 4263BA7    | 1        | 3.13%   |
| Intel STK1A32SC                    | 1        | 3.13%   |
| Intel H61                          | 1        | 3.13%   |
| Intel DP55WB AAE64798-206          | 1        | 3.13%   |
| HP Z440 Workstation                | 1        | 3.13%   |
| HP EliteDesk 800 G1 DM             | 1        | 3.13%   |
| HP 750-417c                        | 1        | 3.13%   |
| Gigabyte X570S AORUS PRO AX        | 1        | 3.13%   |
| Gigabyte M68MT-S2                  | 1        | 3.13%   |
| Gigabyte H310MHD2                  | 1        | 3.13%   |
| Gigabyte GA-890GPA-UD3H            | 1        | 3.13%   |
| Gigabyte F2A78M-HD2                | 1        | 3.13%   |
| Gigabyte B75M-D3P                  | 1        | 3.13%   |
| Gigabyte B75M-D3H                  | 1        | 3.13%   |
| Gigabyte B550 AORUS ELITE AX V2    | 1        | 3.13%   |
| Gigabyte B450 I AORUS PRO WIFI     | 1        | 3.13%   |
| Fujitsu ESPRIMO Q920               | 1        | 3.13%   |
| Fujitsu ESPRIMO Q910               | 1        | 3.13%   |
| Fujitsu D3348-B2                   | 1        | 3.13%   |
| Dell Precision WorkStation T7400   | 1        | 3.13%   |
| Dell OptiPlex 780                  | 1        | 3.13%   |
| Biostar A960D+V3                   | 1        | 3.13%   |
| ASUS ROG STRIX X670E-E GAMING WIFI | 1        | 3.13%   |
| ASUS PRIME B560M-A                 | 1        | 3.13%   |
| ASUS A88X-PRO                      | 1        | 3.13%   |
| ASRock FM2A88X Extreme4+           | 1        | 3.13%   |
| ASRock B450M Steel Legend          | 1        | 3.13%   |
| ASRock A300M-STX                   | 1        | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Fujitsu ESPRIMO         | 2        | 6.25%   |
| MSI MS-7C95             | 1        | 3.13%   |
| MSI MS-7B86             | 1        | 3.13%   |
| MSI MS-7A32             | 1        | 3.13%   |
| MSI MS-7885             | 1        | 3.13%   |
| Lenovo ThinkStation     | 1        | 3.13%   |
| Intel STK1A32SC         | 1        | 3.13%   |
| Intel H61               | 1        | 3.13%   |
| Intel DP55WB            | 1        | 3.13%   |
| HP Z440                 | 1        | 3.13%   |
| HP EliteDesk            | 1        | 3.13%   |
| HP 750-417c             | 1        | 3.13%   |
| Gigabyte X570S          | 1        | 3.13%   |
| Gigabyte M68MT-S2       | 1        | 3.13%   |
| Gigabyte H310MHD2       | 1        | 3.13%   |
| Gigabyte GA-890GPA-UD3H | 1        | 3.13%   |
| Gigabyte F2A78M-HD2     | 1        | 3.13%   |
| Gigabyte B75M-D3P       | 1        | 3.13%   |
| Gigabyte B75M-D3H       | 1        | 3.13%   |
| Gigabyte B550           | 1        | 3.13%   |
| Gigabyte B450           | 1        | 3.13%   |
| Fujitsu D3348-B2        | 1        | 3.13%   |
| Dell Precision          | 1        | 3.13%   |
| Dell OptiPlex           | 1        | 3.13%   |
| Biostar A960D+V3        | 1        | 3.13%   |
| ASUS ROG                | 1        | 3.13%   |
| ASUS PRIME              | 1        | 3.13%   |
| ASUS A88X-PRO           | 1        | 3.13%   |
| ASRock FM2A88X          | 1        | 3.13%   |
| ASRock B450M            | 1        | 3.13%   |
| ASRock A300M-STX        | 1        | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 4        | 12.5%   |
| 2014 | 4        | 12.5%   |
| 2017 | 3        | 9.38%   |
| 2015 | 3        | 9.38%   |
| 2010 | 3        | 9.38%   |
| 2021 | 2        | 6.25%   |
| 2020 | 2        | 6.25%   |
| 2019 | 2        | 6.25%   |
| 2016 | 2        | 6.25%   |
| 2012 | 2        | 6.25%   |
| 2022 | 1        | 3.13%   |
| 2013 | 1        | 3.13%   |
| 2011 | 1        | 3.13%   |
| 2009 | 1        | 3.13%   |
| 2008 | 1        | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 32       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 32       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 10       | 31.25%  |
| 8.01-16.0       | 8        | 25%     |
| 4.01-8.0        | 6        | 18.75%  |
| 32.01-64.0      | 2        | 6.25%   |
| 24.01-32.0      | 2        | 6.25%   |
| 64.01-256.0     | 2        | 6.25%   |
| More than 256.0 | 1        | 3.13%   |
| 1.01-2.0        | 1        | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 12       | 34.29%  |
| 2.01-3.0   | 11       | 31.43%  |
| 4.01-8.0   | 6        | 17.14%  |
| 3.01-4.0   | 4        | 11.43%  |
| 16.01-24.0 | 1        | 2.86%   |
| 8.01-16.0  | 1        | 2.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 31.25%  |
| 1      | 10       | 31.25%  |
| 3      | 5        | 15.63%  |
| 4      | 3        | 9.38%   |
| 6      | 2        | 6.25%   |
| 8      | 1        | 3.13%   |
| 7      | 1        | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 59.38%  |
| Yes       | 13       | 40.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 31       | 96.88%  |
| No        | 1        | 3.13%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 53.13%  |
| No        | 15       | 46.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 65.63%  |
| Yes       | 11       | 34.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 9        | 28.13%  |
| Germany      | 4        | 12.5%   |
| Brazil       | 3        | 9.38%   |
| UK           | 2        | 6.25%   |
| Switzerland  | 2        | 6.25%   |
| France       | 2        | 6.25%   |
| Spain        | 1        | 3.13%   |
| South Africa | 1        | 3.13%   |
| Slovenia     | 1        | 3.13%   |
| Romania      | 1        | 3.13%   |
| Norway       | 1        | 3.13%   |
| Mexico       | 1        | 3.13%   |
| Greece       | 1        | 3.13%   |
| Croatia      | 1        | 3.13%   |
| Austria      | 1        | 3.13%   |
| Argentina    | 1        | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milwaukee             | 2        | 5.88%   |
| Zurich                | 1        | 2.94%   |
| Walled Lake           | 1        | 2.94%   |
| Trondheim             | 1        | 2.94%   |
| Tocantins             | 1        | 2.94%   |
| Tann                  | 1        | 2.94%   |
| Seattle               | 1        | 2.94%   |
| San Luis Potosí City | 1        | 2.94%   |
| San Diego             | 1        | 2.94%   |
| Rueil-Malmaison       | 1        | 2.94%   |
| Pula                  | 1        | 2.94%   |
| Pine Island           | 1        | 2.94%   |
| New York              | 1        | 2.94%   |
| Maribor               | 1        | 2.94%   |
| Manaus                | 1        | 2.94%   |
| Madrid                | 1        | 2.94%   |
| London                | 1        | 2.94%   |
| Limay                 | 1        | 2.94%   |
| Kittsee               | 1        | 2.94%   |
| Kirkcaldy             | 1        | 2.94%   |
| Houston               | 1        | 2.94%   |
| Hamburg               | 1        | 2.94%   |
| Ennepetal             | 1        | 2.94%   |
| Dortmund              | 1        | 2.94%   |
| Delbrueck             | 1        | 2.94%   |
| Colon                 | 1        | 2.94%   |
| Caslano               | 1        | 2.94%   |
| Cape Town             | 1        | 2.94%   |
| Camp Hill             | 1        | 2.94%   |
| Brasília             | 1        | 2.94%   |
| Bradenton             | 1        | 2.94%   |
| Baia Mare             | 1        | 2.94%   |
| Athens                | 1        | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 22     | 22.22%  |
| WDC                 | 7        | 8      | 11.11%  |
| Samsung Electronics | 7        | 27     | 11.11%  |
| SanDisk             | 5        | 6      | 7.94%   |
| Toshiba             | 3        | 3      | 4.76%   |
| Crucial             | 3        | 3      | 4.76%   |
| OCZ                 | 2        | 2      | 3.17%   |
| Micron Technology   | 2        | 2      | 3.17%   |
| Kingston            | 2        | 3      | 3.17%   |
| China               | 2        | 2      | 3.17%   |
| Zheino              | 1        | 1      | 1.59%   |
| Unknown             | 1        | 1      | 1.59%   |
| Transcend           | 1        | 1      | 1.59%   |
| SPCC                | 1        | 1      | 1.59%   |
| SK hynix            | 1        | 1      | 1.59%   |
| PNY                 | 1        | 1      | 1.59%   |
| Phison              | 1        | 1      | 1.59%   |
| Mushkin             | 1        | 1      | 1.59%   |
| MicroFrom           | 1        | 1      | 1.59%   |
| Maxtor              | 1        | 1      | 1.59%   |
| JMicron Technology  | 1        | 1      | 1.59%   |
| Intel               | 1        | 1      | 1.59%   |
| HGST                | 1        | 1      | 1.59%   |
| ASMT109x            | 1        | 1      | 1.59%   |
| A-DATA Technology   | 1        | 1      | 1.59%   |
| 4Life               | 1        | 1      | 1.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 2        | 2.6%    |
| Seagate ST3500418AS 500GB          | 2        | 2.6%    |
| Seagate ST1000LM048-2E7172 1TB     | 2        | 2.6%    |
| SanDisk SDSSDA120G 120GB           | 2        | 2.6%    |
| Samsung SSD 870 EVO 250GB          | 2        | 2.6%    |
| Samsung SSD 850 PRO 256GB          | 2        | 2.6%    |
| Zheino CHN-25SATAC3-120 120GB SSD  | 1        | 1.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 1.3%    |
| WDC WD40PURZ-85TTDY0 4TB           | 1        | 1.3%    |
| WDC WD3200LPVX-22V0TT0 320GB       | 1        | 1.3%    |
| WDC WD1600AAJS-60WAA0 160GB        | 1        | 1.3%    |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1.3%    |
| WDC WD10EADS-00M2B0 1TB            | 1        | 1.3%    |
| Unknown SD/MMC/MS PRO 250GB        | 1        | 1.3%    |
| Transcend TS128GMTE110S 128GB      | 1        | 1.3%    |
| Toshiba MD04ACA400 4TB             | 1        | 1.3%    |
| Toshiba HDWD240 4TB                | 1        | 1.3%    |
| Toshiba HDWD220 2TB                | 1        | 1.3%    |
| SPCC Solid State Disk 256GB        | 1        | 1.3%    |
| SK hynix SC210 2.5 7MM 128GB SSD   | 1        | 1.3%    |
| Seagate ST9500325AS 500GB          | 1        | 1.3%    |
| Seagate ST8000VN0022-2EL112 8TB    | 1        | 1.3%    |
| Seagate ST500LT012-1DG142 500GB    | 1        | 1.3%    |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 1.3%    |
| Seagate ST380815AS 80GB            | 1        | 1.3%    |
| Seagate ST3500412AS 500GB          | 1        | 1.3%    |
| Seagate ST3160815AS 160GB          | 1        | 1.3%    |
| Seagate ST2000DM008-2FR102 2TB     | 1        | 1.3%    |
| Seagate ST2000DM006-2DM164 2TB     | 1        | 1.3%    |
| Seagate ST2000DM001-1ER164 2TB     | 1        | 1.3%    |
| Seagate ST1000LM035-1RK172 1TB     | 1        | 1.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1.3%    |
| Seagate ST1000LM014-1EJ164 1TB     | 1        | 1.3%    |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1.3%    |
| Seagate ST1000DM003-1SB10C 1TB     | 1        | 1.3%    |
| Seagate NVMe SSD Drive 500GB       | 1        | 1.3%    |
| Sandisk WD Blue SN550 NVMe SSD 1TB | 1        | 1.3%    |
| SanDisk NVMe SSD Drive 500GB       | 1        | 1.3%    |
| SanDisk DF4032  32GB               | 1        | 1.3%    |
| Samsung SSD 980 1TB                | 1        | 1.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 21     | 50%     |
| WDC                 | 6        | 7      | 21.43%  |
| Toshiba             | 3        | 3      | 10.71%  |
| Unknown             | 1        | 1      | 3.57%   |
| Samsung Electronics | 1        | 2      | 3.57%   |
| Maxtor              | 1        | 1      | 3.57%   |
| HGST                | 1        | 1      | 3.57%   |
| ASMT109x            | 1        | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 20     | 20.83%  |
| Crucial             | 3        | 3      | 12.5%   |
| SanDisk             | 2        | 2      | 8.33%   |
| China               | 2        | 2      | 8.33%   |
| Zheino              | 1        | 1      | 4.17%   |
| WDC                 | 1        | 1      | 4.17%   |
| SPCC                | 1        | 1      | 4.17%   |
| SK hynix            | 1        | 1      | 4.17%   |
| PNY                 | 1        | 1      | 4.17%   |
| OCZ                 | 1        | 1      | 4.17%   |
| Mushkin             | 1        | 1      | 4.17%   |
| Micron Technology   | 1        | 1      | 4.17%   |
| MicroFrom           | 1        | 1      | 4.17%   |
| Kingston            | 1        | 2      | 4.17%   |
| A-DATA Technology   | 1        | 1      | 4.17%   |
| 4Life               | 1        | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 21       | 40     | 38.18%  |
| HDD  | 21       | 37     | 38.18%  |
| NVMe | 12       | 16     | 21.82%  |
| MMC  | 1        | 1      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 30       | 75     | 66.67%  |
| NVMe | 11       | 15     | 24.44%  |
| SAS  | 3        | 3      | 6.67%   |
| MMC  | 1        | 1      | 2.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 27       | 49     | 58.7%   |
| 0.51-1.0   | 10       | 16     | 21.74%  |
| 3.01-4.0   | 5        | 6      | 10.87%  |
| 1.01-2.0   | 3        | 4      | 6.52%   |
| 4.01-10.0  | 1        | 2      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 10       | 31.25%  |
| More than 3000 | 4        | 12.5%   |
| 1-20           | 4        | 12.5%   |
| 51-100         | 4        | 12.5%   |
| 251-500        | 3        | 9.38%   |
| 1001-2000      | 3        | 9.38%   |
| 2001-3000      | 2        | 6.25%   |
| 21-50          | 1        | 3.13%   |
| 501-1000       | 1        | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 9        | 27.27%  |
| 21-50          | 8        | 24.24%  |
| 51-100         | 7        | 21.21%  |
| 101-250        | 3        | 9.09%   |
| 1001-2000      | 3        | 9.09%   |
| More than 3000 | 1        | 3.03%   |
| 251-500        | 1        | 3.03%   |
| 2001-3000      | 1        | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1        | 1      | 50%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

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
| Detected | 23       | 64     | 63.89%  |
| Works    | 11       | 28     | 30.56%  |
| Malfunc  | 2        | 2      | 5.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 17       | 36.96%  |
| AMD                         | 14       | 30.43%  |
| Samsung Electronics         | 4        | 8.7%    |
| SanDisk                     | 2        | 4.35%   |
| Transcend                   | 1        | 2.17%   |
| Seagate Technology          | 1        | 2.17%   |
| Phison Electronics          | 1        | 2.17%   |
| OCZ Technology Group        | 1        | 2.17%   |
| Nvidia                      | 1        | 2.17%   |
| Micron Technology           | 1        | 2.17%   |
| Marvell Technology Group    | 1        | 2.17%   |
| Kingston Technology Company | 1        | 2.17%   |
| JMicron Technology          | 1        | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 12.07%  |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 5.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 3.45%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 3.45%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 3.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 3.45%   |
| AMD FCH IDE Controller                                                         | 2        | 3.45%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 3.45%   |
| Transcend Non-Volatile memory controller                                       | 1        | 1.72%   |
| Seagate Non-Volatile memory controller                                         | 1        | 1.72%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 1.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 1.72%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.72%   |
| Samsung NVMe SSD Controller 172X                                               | 1        | 1.72%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 1.72%   |
| OCZ Group RD400/400A SSD                                                       | 1        | 1.72%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.72%   |
| Micron NVMe Storage Controller                                                 | 1        | 1.72%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 1.72%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 1.72%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 1.72%   |
| Intel Non-Volatile memory controller                                           | 1        | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.72%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                     | 1        | 1.72%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 1.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 1.72%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 1.72%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 1.72%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 1.72%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                     | 1        | 1.72%   |
| Intel 631xESB/632xESB IDE Controller                                           | 1        | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.72%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 1.72%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1        | 1.72%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 1        | 1.72%   |
| AMD X370 Series Chipset SATA Controller                                        | 1        | 1.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 27       | 56.25%  |
| NVMe | 11       | 22.92%  |
| IDE  | 9        | 18.75%  |
| RAID | 1        | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 17       | 53.13%  |
| AMD    | 15       | 46.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-4590T CPU @ 2.00GHz               | 2        | 6.25%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 2        | 6.25%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 2        | 6.25%   |
| Intel Xeon CPU X5492 @ 3.40GHz                  | 1        | 3.13%   |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 1        | 3.13%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz            | 1        | 3.13%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz             | 1        | 3.13%   |
| Intel Core i7-5820K CPU @ 3.30GHz               | 1        | 3.13%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 3.13%   |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 3.13%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1        | 3.13%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 3.13%   |
| Intel Core i5-3470T CPU @ 2.90GHz               | 1        | 3.13%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 3.13%   |
| Intel Core i3-3225 CPU @ 3.30GHz                | 1        | 3.13%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 3.13%   |
| Intel Atom x5-Z8330 CPU @ 1.44GHz               | 1        | 3.13%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz          | 1        | 3.13%   |
| AMD Ryzen 9 7900X 12-Core Processor             | 1        | 3.13%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1        | 3.13%   |
| AMD Ryzen 5 5600 6-Core Processor               | 1        | 3.13%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 3.13%   |
| AMD Phenom II X4 965 Processor                  | 1        | 3.13%   |
| AMD FX-8150 Eight-Core Processor                | 1        | 3.13%   |
| AMD Athlon X4 845 Quad Core Processor           | 1        | 3.13%   |
| AMD Athlon II X3 445 Processor                  | 1        | 3.13%   |
| AMD Athlon 3000G with Radeon Vega Graphics      | 1        | 3.13%   |
| AMD A4-4000 APU with Radeon HD Graphics         | 1        | 3.13%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 6        | 18.75%  |
| AMD Ryzen 5       | 6        | 18.75%  |
| Intel Xeon        | 4        | 12.5%   |
| Intel Core i7     | 3        | 9.38%   |
| AMD Ryzen 9       | 2        | 6.25%   |
| Other             | 1        | 3.13%   |
| Intel Core i3     | 1        | 3.13%   |
| Intel Core 2 Quad | 1        | 3.13%   |
| Intel Atom        | 1        | 3.13%   |
| AMD Phenom II X4  | 1        | 3.13%   |
| AMD FX            | 1        | 3.13%   |
| AMD Athlon X4     | 1        | 3.13%   |
| AMD Athlon II X3  | 1        | 3.13%   |
| AMD Athlon        | 1        | 3.13%   |
| AMD A4            | 1        | 3.13%   |
| AMD A10           | 1        | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 13       | 40.63%  |
| 6      | 7        | 21.88%  |
| 2      | 5        | 15.63%  |
| 12     | 2        | 6.25%   |
| 8      | 2        | 6.25%   |
| 16     | 1        | 3.13%   |
| 3      | 1        | 3.13%   |
| 1      | 1        | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 30       | 93.75%  |
| 2      | 2        | 6.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 22       | 68.75%  |
| 1      | 10       | 31.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 32       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 58.82%  |
| 0x306a9    | 3        | 8.82%   |
| 0x406f1    | 2        | 5.88%   |
| 0xa0671    | 1        | 2.94%   |
| 0x406c4    | 1        | 2.94%   |
| 0x306c3    | 1        | 2.94%   |
| 0x10677    | 1        | 2.94%   |
| 0x0a50000c | 1        | 2.94%   |
| 0x0a201205 | 1        | 2.94%   |
| 0x08108109 | 1        | 2.94%   |
| 0x08108102 | 1        | 2.94%   |
| 0x06001119 | 1        | 2.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen+        | 4        | 12.5%   |
| Zen 3       | 4        | 12.5%   |
| IvyBridge   | 3        | 9.38%   |
| Haswell     | 3        | 9.38%   |
| Penryn      | 2        | 6.25%   |
| K10         | 2        | 6.25%   |
| Broadwell   | 2        | 6.25%   |
| Westmere    | 1        | 3.13%   |
| Steamroller | 1        | 3.13%   |
| Skylake     | 1        | 3.13%   |
| Silvermont  | 1        | 3.13%   |
| SandyBridge | 1        | 3.13%   |
| Piledriver  | 1        | 3.13%   |
| Nehalem     | 1        | 3.13%   |
| KabyLake    | 1        | 3.13%   |
| Icelake     | 1        | 3.13%   |
| Excavator   | 1        | 3.13%   |
| Bulldozer   | 1        | 3.13%   |
| Unknown     | 1        | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 13       | 38.24%  |
| AMD    | 13       | 38.24%  |
| Intel  | 8        | 23.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 8.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 5.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 5.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 5.88%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 5.88%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 2.94%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 2.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 2.94%   |
| Nvidia GP104GL [Quadro P4000]                                                            | 1        | 2.94%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 2.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 2.94%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1        | 2.94%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 2.94%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1        | 2.94%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1        | 2.94%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1        | 2.94%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 2.94%   |
| Nvidia AD102 [GeForce RTX 4090]                                                          | 1        | 2.94%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 2.94%   |
| Intel HD Graphics 530                                                                    | 1        | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 2.94%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 2.94%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1        | 2.94%   |
| AMD Juniper PRO [Radeon HD 5750]                                                         | 1        | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 2.94%   |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 2.94%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 12       | 37.5%   |
| 1 x AMD      | 12       | 37.5%   |
| 1 x Intel    | 7        | 21.88%  |
| AMD + Nvidia | 1        | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 24       | 72.73%  |
| Proprietary | 8        | 24.24%  |
| Unknown     | 1        | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 62.5%   |
| 7.01-8.0   | 3        | 9.38%   |
| 3.01-4.0   | 3        | 9.38%   |
| 1.01-2.0   | 3        | 9.38%   |
| 0.01-0.5   | 2        | 6.25%   |
| 0.51-1.0   | 1        | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 10       | 31.25%  |
| AOC                 | 4        | 12.5%   |
| Hewlett-Packard     | 3        | 9.38%   |
| SANYO               | 2        | 6.25%   |
| Philips             | 2        | 6.25%   |
| Goldstar            | 2        | 6.25%   |
| Fujitsu Siemens     | 2        | 6.25%   |
| Unknown (XXX)       | 1        | 3.13%   |
| Sony                | 1        | 3.13%   |
| Panasonic           | 1        | 3.13%   |
| LG Electronics      | 1        | 3.13%   |
| HKC                 | 1        | 3.13%   |
| Dell                | 1        | 3.13%   |
| BenQ                | 1        | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 2.94%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 2.94%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                | 1        | 2.94%   |
| SANYO LCD SAN0A12 1920x540                                            | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch  | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch  | 1        | 2.94%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 2.94%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch     | 1        | 2.94%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1        | 2.94%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 530x300mm 24.0-inch     | 1        | 2.94%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 2.94%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 800x330mm 34.1-inch     | 1        | 2.94%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 2.94%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch              | 1        | 2.94%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch               | 1        | 2.94%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                   | 1        | 2.94%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                               | 1        | 2.94%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                      | 1        | 2.94%   |
| HKC '' HKC2160 1920x1080 360x270mm 17.7-inch                          | 1        | 2.94%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 1        | 2.94%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1        | 2.94%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 2.94%   |
| Goldstar W2343 GSM5701 1920x1080 510x290mm 23.1-inch                  | 1        | 2.94%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1        | 2.94%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch               | 1        | 2.94%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 1        | 2.94%   |
| Fujitsu Siemens B27T-7 Pro FUS0891 1920x1080 598x336mm 27.0-inch      | 1        | 2.94%   |
| Dell LCD Monitor 1704FPV 1280x1024                                    | 1        | 2.94%   |
| BenQ GW2750H BNQ78C3 1920x1080 598x336mm 27.0-inch                    | 1        | 2.94%   |
| AOC U34G2G1 AOC3402 3440x1440 797x334mm 34.0-inch                     | 1        | 2.94%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1        | 2.94%   |
| AOC LE22H138 AOC2218 1920x1080 480x270mm 21.7-inch                    | 1        | 2.94%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 1        | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 56.25%  |
| 1920x540           | 3        | 9.38%   |
| 3840x2160 (4K)     | 2        | 6.25%   |
| 3440x1440          | 2        | 6.25%   |
| 1920x1200 (WUXGA)  | 2        | 6.25%   |
| 2560x1440 (QHD)    | 1        | 3.13%   |
| 2560x1080          | 1        | 3.13%   |
| 1680x1050 (WSXGA+) | 1        | 3.13%   |
| 1366x768 (WXGA)    | 1        | 3.13%   |
| 1280x1024 (SXGA)   | 1        | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 7        | 21.21%  |
| 23      | 5        | 15.15%  |
| 27      | 4        | 12.12%  |
| 34      | 3        | 9.09%   |
| Unknown | 3        | 9.09%   |
| 21      | 2        | 6.06%   |
| 72      | 1        | 3.03%   |
| 54      | 1        | 3.03%   |
| 47      | 1        | 3.03%   |
| 40      | 1        | 3.03%   |
| 33      | 1        | 3.03%   |
| 31      | 1        | 3.03%   |
| 28      | 1        | 3.03%   |
| 18      | 1        | 3.03%   |
| 17      | 1        | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 15       | 46.88%  |
| 701-800     | 4        | 12.5%   |
| 401-500     | 3        | 9.38%   |
| Unknown     | 3        | 9.38%   |
| 601-700     | 2        | 6.25%   |
| 1001-1500   | 2        | 6.25%   |
| 801-900     | 1        | 3.13%   |
| 351-400     | 1        | 3.13%   |
| 1501-2000   | 1        | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 21       | 67.74%  |
| 21/9    | 3        | 9.68%   |
| 16/10   | 3        | 9.68%   |
| Unknown | 2        | 6.45%   |
| 4/3     | 1        | 3.23%   |
| 32/9    | 1        | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 32.26%  |
| 351-500        | 6        | 19.35%  |
| 301-350        | 4        | 12.9%   |
| Unknown        | 3        | 9.68%   |
| More than 1000 | 2        | 6.45%   |
| 251-300        | 2        | 6.45%   |
| 501-1000       | 2        | 6.45%   |
| 151-200        | 1        | 3.23%   |
| 141-150        | 1        | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 67.74%  |
| 1-50    | 3        | 9.68%   |
| Unknown | 3        | 9.68%   |
| 121-160 | 2        | 6.45%   |
| 101-120 | 2        | 6.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 90.63%  |
| 2     | 3        | 9.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 18       | 41.86%  |
| Realtek Semiconductor | 17       | 39.53%  |
| Broadcom              | 2        | 4.65%   |
| Ralink Technology     | 1        | 2.33%   |
| Qualcomm Atheros      | 1        | 2.33%   |
| Nvidia                | 1        | 2.33%   |
| Microsoft             | 1        | 2.33%   |
| MediaTek              | 1        | 2.33%   |
| Broadcom Limited      | 1        | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 26%     |
| Intel Ethernet Connection I217-LM                                 | 3        | 6%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 6%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 4%      |
| Intel I211 Gigabit Network Connection                             | 2        | 4%      |
| Intel Ethernet Controller I225-V                                  | 2        | 4%      |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 2%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 2%      |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 2%      |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2%      |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2%      |
| Realtek 802.11ac NIC                                              | 1        | 2%      |
| Ralink RT3072 Wireless Adapter                                    | 1        | 2%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2%      |
| Nvidia MCP61 Ethernet                                             | 1        | 2%      |
| Microsoft Wireless XBox Controller Dongle                         | 1        | 2%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 2%      |
| Intel Wireless-AC 9260                                            | 1        | 2%      |
| Intel Wireless 7265                                               | 1        | 2%      |
| Intel Wi-Fi 6 AX200                                               | 1        | 2%      |
| Intel I210 Gigabit Network Connection                             | 1        | 2%      |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2%      |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 2%      |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2%      |
| Intel 82578DC Gigabit Network Connection                          | 1        | 2%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2%      |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 2%      |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 2%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 2%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 47.06%  |
| Realtek Semiconductor | 5        | 29.41%  |
| Ralink Technology     | 1        | 5.88%   |
| Microsoft             | 1        | 5.88%   |
| MediaTek              | 1        | 5.88%   |
| Broadcom              | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]      | 3        | 17.65%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                | 2        | 11.76%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter   | 1        | 5.88%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter | 1        | 5.88%   |
| Realtek RTL8188EE Wireless Network Adapter            | 1        | 5.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter               | 1        | 5.88%   |
| Realtek 802.11ac NIC                                  | 1        | 5.88%   |
| Ralink RT3072 Wireless Adapter                        | 1        | 5.88%   |
| Microsoft Wireless XBox Controller Dongle             | 1        | 5.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz               | 1        | 5.88%   |
| Intel Wireless-AC 9260                                | 1        | 5.88%   |
| Intel Wireless 7265                                   | 1        | 5.88%   |
| Intel Wi-Fi 6 AX200                                   | 1        | 5.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter    | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 45.16%  |
| Intel                 | 13       | 41.94%  |
| Qualcomm Atheros      | 1        | 3.23%   |
| Nvidia                | 1        | 3.23%   |
| Broadcom Limited      | 1        | 3.23%   |
| Broadcom              | 1        | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 39.39%  |
| Intel Ethernet Connection I217-LM                                 | 3        | 9.09%   |
| Intel I211 Gigabit Network Connection                             | 2        | 6.06%   |
| Intel Ethernet Controller I225-V                                  | 2        | 6.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 3.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 3.03%   |
| Nvidia MCP61 Ethernet                                             | 1        | 3.03%   |
| Intel I210 Gigabit Network Connection                             | 1        | 3.03%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.03%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 3.03%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.03%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 3.03%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 3.03%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 3.03%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 64.58%  |
| WiFi     | 17       | 35.42%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 72.73%  |
| WiFi     | 9        | 27.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 62.5%   |
| 2     | 12       | 37.5%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 78.13%  |
| Yes  | 7        | 21.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 7        | 63.64%  |
| Cambridge Silicon Radio | 2        | 18.18%  |
| MediaTek                | 1        | 9.09%   |
| Broadcom                | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 18.18%  |
| Intel AX210 Bluetooth                               | 2        | 18.18%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 18.18%  |
| MediaTek Wireless_Device                            | 1        | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 9.09%   |
| Intel Bluetooth wireless interface                  | 1        | 9.09%   |
| Intel AX200 Bluetooth                               | 1        | 9.09%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AMD                   | 17       | 34.69%  |
| Intel                 | 15       | 30.61%  |
| Nvidia                | 13       | 26.53%  |
| Texas Instruments     | 1        | 2.04%   |
| Shure                 | 1        | 2.04%   |
| Realtek Semiconductor | 1        | 2.04%   |
| ASUSTek Computer      | 1        | 2.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 5        | 8.33%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 5%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 5%      |
| AMD FCH Azalia Controller                                                  | 3        | 5%      |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 3.33%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 3.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 3.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 3.33%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.67%   |
| Shure MV88+                                                                | 1        | 1.67%   |
| Realtek Semiconductor USB Audio                                            | 1        | 1.67%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.67%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.67%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.67%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.67%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 1.67%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 1.67%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.67%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 1.67%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.67%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.67%   |
| ASUSTek Computer USB Audio                                                 | 1        | 1.67%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 1.67%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 1.67%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1        | 1.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 1.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.67%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]      | 1        | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 22.22%  |
| Crucial             | 4        | 22.22%  |
| SK hynix            | 2        | 11.11%  |
| Samsung Electronics | 2        | 11.11%  |
| Micron Technology   | 2        | 11.11%  |
| Transcend           | 1        | 5.56%   |
| Elpida              | 1        | 5.56%   |
| Corsair             | 1        | 5.56%   |
| A-DATA Technology   | 1        | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 10%     |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s     | 1        | 5%      |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s             | 1        | 5%      |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 5%      |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s   | 1        | 5%      |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s    | 1        | 5%      |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s | 1        | 5%      |
| Micron RAM 16JTF51264AZ-1G4D1 4GB DIMM DDR3 1333MT/s   | 1        | 5%      |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s      | 1        | 5%      |
| Kingston RAM 9905403-011.A02LF 2GB DIMM DDR3 1333MT/s  | 1        | 5%      |
| Elpida RAM EBJ20UF8BCF0-DJ-F 2GB DIMM DDR3 1333MT/s    | 1        | 5%      |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s | 1        | 5%      |
| Crucial RAM CT8G4DFD8213.C16FAD 8GB DIMM DDR4 2133MT/s | 1        | 5%      |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s  | 1        | 5%      |
| Crucial RAM BLS8G4D26BFSBK.8FD 8GB DIMM DDR4 2933MT/s  | 1        | 5%      |
| Crucial RAM BL8G26C16U4B.8FD 8GB DIMM DDR4 2667MT/s    | 1        | 5%      |
| Corsair RAM CMV8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s    | 1        | 5%      |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s    | 1        | 5%      |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s            | 1        | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 8        | 57.14%  |
| DDR3  | 5        | 35.71%  |
| SDRAM | 1        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 11       | 84.62%  |
| SODIMM | 2        | 15.38%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 33.33%  |
| 4096  | 4        | 26.67%  |
| 16384 | 3        | 20%     |
| 2048  | 2        | 13.33%  |
| 32768 | 1        | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 29.41%  |
| 3200  | 2        | 11.76%  |
| 2667  | 2        | 11.76%  |
| 2400  | 2        | 11.76%  |
| 1333  | 2        | 11.76%  |
| 3600  | 1        | 5.88%   |
| 2933  | 1        | 5.88%   |
| 2133  | 1        | 5.88%   |
| 1066  | 1        | 5.88%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 2        | 33.33%  |
| Sunplus Innovation Technology | 1        | 16.67%  |
| Samsung Electronics           | 1        | 16.67%  |
| Microdia                      | 1        | 16.67%  |
| Generalplus Technology        | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920              | 2        | 33.33%  |
| Sunplus FHD Camera Microphone            | 1        | 16.67%  |
| Samsung Galaxy A5 (MTP)                  | 1        | 16.67%  |
| Microdia Camera                          | 1        | 16.67%  |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 16.67%  |

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
| 0     | 26       | 78.79%  |
| 1     | 4        | 12.12%  |
| 2     | 2        | 6.06%   |
| 4     | 1        | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 3        | 30%     |
| Sound            | 2        | 20%     |
| Net/wireless     | 2        | 20%     |
| Net/ethernet     | 1        | 10%     |
| Graphics card    | 1        | 10%     |
| Bluetooth        | 1        | 10%     |

