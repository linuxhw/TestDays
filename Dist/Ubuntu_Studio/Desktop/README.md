Ubuntu Studio - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Studio.

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

Total: 60

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 08WKV3 A00                  | [fe23b6e49a](https://linux-hardware.org/?probe=fe23b6e49a) | Jul 27, 2022 |
| Dell          | 0TTDMJ A00                  | [e45e0b0c90](https://linux-hardware.org/?probe=e45e0b0c90) | Jun 29, 2022 |
| ASRock        | B250M-HDV                   | [a4aa661ab1](https://linux-hardware.org/?probe=a4aa661ab1) | Jun 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | [0754e1c6e6](https://linux-hardware.org/?probe=0754e1c6e6) | May 23, 2022 |
| Gigabyte      | F2A78M-HD2                  | [fdc743e9e1](https://linux-hardware.org/?probe=fdc743e9e1) | May 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | [900181bbff](https://linux-hardware.org/?probe=900181bbff) | May 22, 2022 |
| ASUSTek       | Z87-DELUXE                  | [bcd22d5d0e](https://linux-hardware.org/?probe=bcd22d5d0e) | May 20, 2022 |
| Dell          | 0RW203                      | [fc3e449b4d](https://linux-hardware.org/?probe=fc3e449b4d) | May 09, 2022 |
| Gigabyte      | H170-HD3-CF                 | [cebf5b3135](https://linux-hardware.org/?probe=cebf5b3135) | Apr 17, 2022 |
| ASUSTek       | H81M-PLUS                   | [a517bb6633](https://linux-hardware.org/?probe=a517bb6633) | Apr 03, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [01ad19348a](https://linux-hardware.org/?probe=01ad19348a) | Mar 20, 2022 |
| ASUSTek       | P5QC                        | [82f706b315](https://linux-hardware.org/?probe=82f706b315) | Feb 11, 2022 |
| Dell          | 055H3G A01                  | [05f63f2396](https://linux-hardware.org/?probe=05f63f2396) | Feb 04, 2022 |
| HP            | 3396                        | [97720dddd1](https://linux-hardware.org/?probe=97720dddd1) | Jan 10, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [7f94c66f93](https://linux-hardware.org/?probe=7f94c66f93) | Jan 09, 2022 |
| AZW           | GK35                        | [ed1be3dbf7](https://linux-hardware.org/?probe=ed1be3dbf7) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [4c55363bc2](https://linux-hardware.org/?probe=4c55363bc2) | Dec 04, 2021 |
| ASUSTek       | H110M-A/M.2                 | [b62225a801](https://linux-hardware.org/?probe=b62225a801) | Jul 24, 2021 |
| HP            | 1495                        | [56251d62e1](https://linux-hardware.org/?probe=56251d62e1) | Jun 17, 2021 |
| Pegatron      | NARRA3                      | [38ac9a9ea6](https://linux-hardware.org/?probe=38ac9a9ea6) | May 18, 2021 |
| HP            | 158A                        | [2fac0fa486](https://linux-hardware.org/?probe=2fac0fa486) | May 01, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ef264215af](https://linux-hardware.org/?probe=ef264215af) | Apr 24, 2021 |
| ASUSTek       | H110M-A/M.2                 | [04a4129216](https://linux-hardware.org/?probe=04a4129216) | Apr 20, 2021 |
| ASUSTek       | P8P67 EVO                   | [5e98e0ae38](https://linux-hardware.org/?probe=5e98e0ae38) | Apr 14, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | [43cb3af3a5](https://linux-hardware.org/?probe=43cb3af3a5) | Apr 12, 2021 |
| Foxconn       | 2ABF                        | [9414f40cf2](https://linux-hardware.org/?probe=9414f40cf2) | Apr 03, 2021 |
| Fujitsu       | D3654-C1 S26361-D3654-C1    | [4cd56bcfa1](https://linux-hardware.org/?probe=4cd56bcfa1) | Apr 02, 2021 |
| ASUSTek       | P6T SE                      | [5ff7a11404](https://linux-hardware.org/?probe=5ff7a11404) | Mar 28, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [7b7a266de6](https://linux-hardware.org/?probe=7b7a266de6) | Mar 22, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [d9f29b65da](https://linux-hardware.org/?probe=d9f29b65da) | Mar 15, 2021 |
| ASUSTek       | TUF B360-PRO GAMING         | [19bc1494c6](https://linux-hardware.org/?probe=19bc1494c6) | Feb 21, 2021 |
| ASUSTek       | A68HM-PLUS                  | [387cfadf45](https://linux-hardware.org/?probe=387cfadf45) | Feb 06, 2021 |
| IBM           | 8188PPV                     | [6d4f098a65](https://linux-hardware.org/?probe=6d4f098a65) | Jan 31, 2021 |
| Dell          | 02YRK5 A01                  | [6a2d5cd538](https://linux-hardware.org/?probe=6a2d5cd538) | Jan 30, 2021 |
| Gigabyte      | GA-MA770-DS3                | [c9af16a580](https://linux-hardware.org/?probe=c9af16a580) | Jan 24, 2021 |
| Dell          | 0D28YY A03                  | [e74dbb590d](https://linux-hardware.org/?probe=e74dbb590d) | Jan 21, 2021 |
| Intel         | DQ965GF AAD41676-402        | [2e9a342427](https://linux-hardware.org/?probe=2e9a342427) | Jan 13, 2021 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [772bf2459f](https://linux-hardware.org/?probe=772bf2459f) | Jan 11, 2021 |
| Gigabyte      | B450M S2H                   | [13edd89415](https://linux-hardware.org/?probe=13edd89415) | Jan 11, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [a8ebb648f7](https://linux-hardware.org/?probe=a8ebb648f7) | Jan 03, 2021 |
| Acer          | Aspire X3400                | [da9e0d0bb4](https://linux-hardware.org/?probe=da9e0d0bb4) | Jan 02, 2021 |
| Packard Be... | WMCP78M                     | [6a6c4577d4](https://linux-hardware.org/?probe=6a6c4577d4) | Dec 31, 2020 |
| HP            | 1850                        | [b86e749745](https://linux-hardware.org/?probe=b86e749745) | Dec 30, 2020 |
| Dell          | 0J3C2F A00                  | [b2e5d9d8b0](https://linux-hardware.org/?probe=b2e5d9d8b0) | Dec 09, 2020 |
| ASUSTek       | M4A88TD-M/USB3              | [2291f0c106](https://linux-hardware.org/?probe=2291f0c106) | Dec 08, 2020 |
| Dell          | 04YP6J A02                  | [6c15ba650c](https://linux-hardware.org/?probe=6c15ba650c) | Dec 06, 2020 |
| MSI           | Z270 MPOWER GAMING TITAN... | [73e35c07b8](https://linux-hardware.org/?probe=73e35c07b8) | Dec 02, 2020 |
| MSI           | Z270 MPOWER GAMING TITAN... | [3b24badd98](https://linux-hardware.org/?probe=3b24badd98) | Dec 02, 2020 |
| Medion        | B360H4-EM V1.0              | [1915ad5c58](https://linux-hardware.org/?probe=1915ad5c58) | Nov 15, 2020 |
| ASUSTek       | CS-B                        | [4e0f76c433](https://linux-hardware.org/?probe=4e0f76c433) | Nov 02, 2020 |
| HP            | 3047h                       | [a23efe0e20](https://linux-hardware.org/?probe=a23efe0e20) | Oct 26, 2020 |
| ASRock        | H55M/USB3                   | [74202436b2](https://linux-hardware.org/?probe=74202436b2) | Oct 18, 2020 |
| Dell          | 0F8098                      | [a2217fa6a7](https://linux-hardware.org/?probe=a2217fa6a7) | Sep 25, 2020 |
| Dell          | 0F8098                      | [2c747bcc47](https://linux-hardware.org/?probe=2c747bcc47) | Sep 25, 2020 |
| ASRock        | X470 Master SLI             | [03bcf3b1fd](https://linux-hardware.org/?probe=03bcf3b1fd) | Sep 02, 2020 |
| ASRock        | B450M Pro4                  | [d2851c54e9](https://linux-hardware.org/?probe=d2851c54e9) | Aug 18, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [96ba8dc0e8](https://linux-hardware.org/?probe=96ba8dc0e8) | Jul 31, 2020 |
| ASUSTek       | H81M-C/BR                   | [d21c458a4f](https://linux-hardware.org/?probe=d21c458a4f) | Jul 24, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [957ec007de](https://linux-hardware.org/?probe=957ec007de) | Jun 27, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [cb240b6e7e](https://linux-hardware.org/?probe=cb240b6e7e) | Jun 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu Studio 20.04 | 35       | 66.04%  |
| Ubuntu Studio 20.10 | 9        | 16.98%  |
| Ubuntu Studio 22.04 | 3        | 5.66%   |
| Ubuntu Studio 21.10 | 3        | 5.66%   |
| Ubuntu Studio 21.04 | 2        | 3.77%   |
| Ubuntu Studio 16.04 | 1        | 1.89%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu Studio | 53       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.11.0-44-lowlatency     | 3        | 5.66%   |
| 5.8.0-48-lowlatency      | 2        | 3.77%   |
| 5.8.0-44-lowlatency      | 2        | 3.77%   |
| 5.8.0-25-lowlatency      | 2        | 3.77%   |
| 5.4.0-58-lowlatency      | 2        | 3.77%   |
| 5.4.0-56-lowlatency      | 2        | 3.77%   |
| 5.4.0-42-lowlatency      | 2        | 3.77%   |
| 5.4.0-26-lowlatency      | 2        | 3.77%   |
| 5.13.0-28-lowlatency     | 2        | 3.77%   |
| 5.8.0-50-lowlatency      | 1        | 1.89%   |
| 5.8.0-45-lowlatency      | 1        | 1.89%   |
| 5.8.0-36-lowlatency      | 1        | 1.89%   |
| 5.8.0-34-lowlatency      | 1        | 1.89%   |
| 5.8.0-33-lowlatency      | 1        | 1.89%   |
| 5.8.0-29-lowlatency      | 1        | 1.89%   |
| 5.4.0-99-lowlatency      | 1        | 1.89%   |
| 5.4.0-72-lowlatency      | 1        | 1.89%   |
| 5.4.0-71-lowlatency      | 1        | 1.89%   |
| 5.4.0-70-lowlatency      | 1        | 1.89%   |
| 5.4.0-65-lowlatency      | 1        | 1.89%   |
| 5.4.0-65-generic         | 1        | 1.89%   |
| 5.4.0-64-lowlatency      | 1        | 1.89%   |
| 5.4.0-62-lowlatency      | 1        | 1.89%   |
| 5.4.0-60-lowlatency      | 1        | 1.89%   |
| 5.4.0-53-lowlatency      | 1        | 1.89%   |
| 5.4.0-52-lowlatency      | 1        | 1.89%   |
| 5.4.0-51-lowlatency      | 1        | 1.89%   |
| 5.4.0-48-lowlatency      | 1        | 1.89%   |
| 5.4.0-47-lowlatency      | 1        | 1.89%   |
| 5.4.0-39-lowlatency      | 1        | 1.89%   |
| 5.4.0-33-lowlatency      | 1        | 1.89%   |
| 5.4.0-122-generic        | 1        | 1.89%   |
| 5.4.0-110-lowlatency     | 1        | 1.89%   |
| 5.4.0-109-lowlatency     | 1        | 1.89%   |
| 5.15.6-051506-lowlatency | 1        | 1.89%   |
| 5.15.0-40-lowlatency     | 1        | 1.89%   |
| 5.15.0-30-lowlatency     | 1        | 1.89%   |
| 5.15.0-24-lowlatency     | 1        | 1.89%   |
| 5.13.0-35-lowlatency     | 1        | 1.89%   |
| 5.11.0-49-lowlatency     | 1        | 1.89%   |
| 5.11.0-34-lowlatency     | 1        | 1.89%   |
| 5.11.0-18-lowlatency     | 1        | 1.89%   |
| 4.4.0-189-generic        | 1        | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 27       | 50.94%  |
| 5.8.0   | 12       | 22.64%  |
| 5.11.0  | 6        | 11.32%  |
| 5.15.0  | 3        | 5.66%   |
| 5.13.0  | 3        | 5.66%   |
| 5.15.6  | 1        | 1.89%   |
| 4.4.0   | 1        | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 27       | 50.94%  |
| 5.8     | 12       | 22.64%  |
| 5.11    | 6        | 11.32%  |
| 5.15    | 4        | 7.55%   |
| 5.13    | 3        | 5.66%   |
| 4.4     | 1        | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 52       | 98.11%  |
| i686   | 1        | 1.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| XFCE            | 28       | 52.83%  |
| KDE5            | 14       | 26.42%  |
| GNOME           | 5        | 9.43%   |
| MATE            | 2        | 3.77%   |
| LXQt            | 1        | 1.89%   |
| KDE             | 1        | 1.89%   |
| GNOME Flashback | 1        | 1.89%   |
| Cinnamon        | 1        | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 49       | 92.45%  |
| Wayland | 2        | 3.77%   |
| Tty     | 2        | 3.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 25       | 47.17%  |
| SDDM    | 13       | 24.53%  |
| LightDM | 9        | 16.98%  |
| GDM     | 6        | 11.32%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 20       | 37.74%  |
| de_DE      | 7        | 13.21%  |
| fr_FR      | 6        | 11.32%  |
| pt_BR      | 4        | 7.55%   |
| en_GB      | 3        | 5.66%   |
| it_IT      | 2        | 3.77%   |
| en_AU      | 2        | 3.77%   |
| nl_NL      | 1        | 1.89%   |
| nl_BE      | 1        | 1.89%   |
| nb_NO      | 1        | 1.89%   |
| fr_FR.UTF8 | 1        | 1.89%   |
| fr_CH      | 1        | 1.89%   |
| es_AR      | 1        | 1.89%   |
| en_DE      | 1        | 1.89%   |
| en_CA      | 1        | 1.89%   |
| ca_ES      | 1        | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 31       | 58.49%  |
| EFI  | 22       | 41.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 51       | 96.23%  |
| Xfs  | 1        | 1.89%   |
| Ext2 | 1        | 1.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 28       | 52.83%  |
| GPT  | 25       | 47.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 75.47%  |
| Yes       | 13       | 24.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 56.6%   |
| Yes       | 23       | 43.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 15       | 28.3%   |
| Dell                | 9        | 16.98%  |
| Gigabyte Technology | 7        | 13.21%  |
| Hewlett-Packard     | 5        | 9.43%   |
| Fujitsu             | 3        | 5.66%   |
| ASRock              | 2        | 3.77%   |
| Pegatron            | 1        | 1.89%   |
| Packard Bell        | 1        | 1.89%   |
| MSI                 | 1        | 1.89%   |
| Medion              | 1        | 1.89%   |
| Lenovo              | 1        | 1.89%   |
| Intel               | 1        | 1.89%   |
| IBM                 | 1        | 1.89%   |
| Foxconn             | 1        | 1.89%   |
| AZW                 | 1        | 1.89%   |
| Apple               | 1        | 1.89%   |
| Acidanthera         | 1        | 1.89%   |
| Acer                | 1        | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 4        | 7.55%   |
| Dell OptiPlex 790                  | 2        | 3.77%   |
| Pegatron FL368AA-UUZ SR5612CH      | 1        | 1.89%   |
| Packard Bell IMEDIA S3220          | 1        | 1.89%   |
| MSI MS-7A57                        | 1        | 1.89%   |
| Medion MD34207/C746                | 1        | 1.89%   |
| Lenovo ThinkCentre M93p 10A8S45S00 | 1        | 1.89%   |
| Intel DQ965GF HD/FP Audio          | 1        | 1.89%   |
| IBM 8188PPV                        | 1        | 1.89%   |
| HP Z620 Workstation                | 1        | 1.89%   |
| HP Compaq Pro 6305 SFF             | 1        | 1.89%   |
| HP Compaq Elite 8300 CMT           | 1        | 1.89%   |
| HP Compaq 8200 Elite SFF PC        | 1        | 1.89%   |
| HP Compaq 6005 Pro MT PC           | 1        | 1.89%   |
| Gigabyte X570 AORUS ELITE WIFI     | 1        | 1.89%   |
| Gigabyte H170-HD3-CF               | 1        | 1.89%   |
| Gigabyte GA-MA770-DS3              | 1        | 1.89%   |
| Gigabyte F2A78M-HD2                | 1        | 1.89%   |
| Gigabyte B450M S2H                 | 1        | 1.89%   |
| Gigabyte B450 I AORUS PRO WIFI     | 1        | 1.89%   |
| Gigabyte A320M-S2H                 | 1        | 1.89%   |
| Fujitsu ESPRIMO P420               | 1        | 1.89%   |
| Fujitsu ESPRIMO G558               | 1        | 1.89%   |
| Fujitsu ESPRIMO E720               | 1        | 1.89%   |
| Foxconn Pro3500 Series             | 1        | 1.89%   |
| Dell Precision WorkStation T5400   | 1        | 1.89%   |
| Dell OptiPlex GX620                | 1        | 1.89%   |
| Dell OptiPlex 7050                 | 1        | 1.89%   |
| Dell OptiPlex 7020                 | 1        | 1.89%   |
| Dell OptiPlex 3040                 | 1        | 1.89%   |
| Dell OptiPlex 3020                 | 1        | 1.89%   |
| Dell Inspiron 3647                 | 1        | 1.89%   |
| AZW GK35                           | 1        | 1.89%   |
| ASUS TUF Gaming X570-PLUS          | 1        | 1.89%   |
| ASUS TUF B360-PRO GAMING           | 1        | 1.89%   |
| ASUS ROG ZENITH II EXTREME ALPHA   | 1        | 1.89%   |
| ASUS ROG STRIX Z490-I GAMING       | 1        | 1.89%   |
| ASUS P8P67 EVO                     | 1        | 1.89%   |
| ASUS P6T SE                        | 1        | 1.89%   |
| ASUS P5QC                          | 1        | 1.89%   |
| ASUS M5A78L-M/USB3                 | 1        | 1.89%   |
| ASUS M4A88TD-M/USB3                | 1        | 1.89%   |
| ASUS H110M-A/M.2                   | 1        | 1.89%   |
| ASUS A68HM-PLUS                    | 1        | 1.89%   |
| ASRock H55M/USB3                   | 1        | 1.89%   |
| ASRock B250M-HDV                   | 1        | 1.89%   |
| Apple iMacPro1,1                   | 1        | 1.89%   |
| Acidanthera MacPro6,1              | 1        | 1.89%   |
| Acer Aspire X3400                  | 1        | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 7        | 13.21%  |
| HP Compaq             | 4        | 7.55%   |
| ASUS All              | 4        | 7.55%   |
| Fujitsu ESPRIMO       | 3        | 5.66%   |
| ASUS TUF              | 2        | 3.77%   |
| ASUS ROG              | 2        | 3.77%   |
| Pegatron FL368AA-UUZ  | 1        | 1.89%   |
| Packard Bell IMEDIA   | 1        | 1.89%   |
| MSI MS-7A57           | 1        | 1.89%   |
| Medion MD34207        | 1        | 1.89%   |
| Lenovo ThinkCentre    | 1        | 1.89%   |
| Intel DQ965GF         | 1        | 1.89%   |
| IBM 8188PPV           | 1        | 1.89%   |
| HP Z620               | 1        | 1.89%   |
| Gigabyte X570         | 1        | 1.89%   |
| Gigabyte H170-HD3-CF  | 1        | 1.89%   |
| Gigabyte GA-MA770-DS3 | 1        | 1.89%   |
| Gigabyte F2A78M-HD2   | 1        | 1.89%   |
| Gigabyte B450M        | 1        | 1.89%   |
| Gigabyte B450         | 1        | 1.89%   |
| Gigabyte A320M-S2H    | 1        | 1.89%   |
| Foxconn Pro3500       | 1        | 1.89%   |
| Dell Precision        | 1        | 1.89%   |
| Dell Inspiron         | 1        | 1.89%   |
| AZW GK35              | 1        | 1.89%   |
| ASUS P8P67            | 1        | 1.89%   |
| ASUS P6T              | 1        | 1.89%   |
| ASUS P5QC             | 1        | 1.89%   |
| ASUS M5A78L-M         | 1        | 1.89%   |
| ASUS M4A88TD-M        | 1        | 1.89%   |
| ASUS H110M-A          | 1        | 1.89%   |
| ASUS A68HM-PLUS       | 1        | 1.89%   |
| ASRock H55M           | 1        | 1.89%   |
| ASRock B250M-HDV      | 1        | 1.89%   |
| Apple iMacPro1        | 1        | 1.89%   |
| Acidanthera MacPro6   | 1        | 1.89%   |
| Acer Aspire           | 1        | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 6        | 11.32%  |
| 2018 | 5        | 9.43%   |
| 2013 | 5        | 9.43%   |
| 2019 | 4        | 7.55%   |
| 2012 | 4        | 7.55%   |
| 2011 | 4        | 7.55%   |
| 2010 | 4        | 7.55%   |
| 2020 | 3        | 5.66%   |
| 2017 | 3        | 5.66%   |
| 2008 | 3        | 5.66%   |
| 2021 | 2        | 3.77%   |
| 2016 | 2        | 3.77%   |
| 2015 | 2        | 3.77%   |
| 2009 | 2        | 3.77%   |
| 2007 | 2        | 3.77%   |
| 2005 | 2        | 3.77%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 53       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 52       | 98.11%  |
| Enabled  | 1        | 1.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 17       | 32.08%  |
| 8.01-16.0   | 9        | 16.98%  |
| 4.01-8.0    | 8        | 15.09%  |
| 32.01-64.0  | 5        | 9.43%   |
| 3.01-4.0    | 5        | 9.43%   |
| 64.01-256.0 | 4        | 7.55%   |
| 1.01-2.0    | 3        | 5.66%   |
| 24.01-32.0  | 1        | 1.89%   |
| 2.01-3.0    | 1        | 1.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 22       | 41.51%  |
| 2.01-3.0   | 11       | 20.75%  |
| 4.01-8.0   | 8        | 15.09%  |
| 8.01-16.0  | 6        | 11.32%  |
| 3.01-4.0   | 3        | 5.66%   |
| 0.51-1.0   | 2        | 3.77%   |
| 24.01-32.0 | 1        | 1.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 22       | 41.51%  |
| 2      | 21       | 39.62%  |
| 3      | 5        | 9.43%   |
| 4      | 2        | 3.77%   |
| 11     | 1        | 1.89%   |
| 10     | 1        | 1.89%   |
| 7      | 1        | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 64.15%  |
| No        | 19       | 35.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 53       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 54.72%  |
| Yes       | 24       | 45.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 75.47%  |
| Yes       | 13       | 24.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 10       | 18.87%  |
| France                 | 9        | 16.98%  |
| Germany                | 8        | 15.09%  |
| Brazil                 | 5        | 9.43%   |
| Italy                  | 4        | 7.55%   |
| Belgium                | 2        | 3.77%   |
| Austria                | 2        | 3.77%   |
| Australia              | 2        | 3.77%   |
| UK                     | 1        | 1.89%   |
| Switzerland            | 1        | 1.89%   |
| Sweden                 | 1        | 1.89%   |
| Spain                  | 1        | 1.89%   |
| Romania                | 1        | 1.89%   |
| Norway                 | 1        | 1.89%   |
| Netherlands            | 1        | 1.89%   |
| Mexico                 | 1        | 1.89%   |
| Kenya                  | 1        | 1.89%   |
| Bosnia and Herzegovina | 1        | 1.89%   |
| Argentina              | 1        | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Paris                   | 3        | 5.66%   |
| Houston                 | 2        | 3.77%   |
| Zanesville              | 1        | 1.89%   |
| Villefontaine           | 1        | 1.89%   |
| Turin                   | 1        | 1.89%   |
| Tilburg                 | 1        | 1.89%   |
| Stuttgart               | 1        | 1.89%   |
| Stockholm               | 1        | 1.89%   |
| Sherman Oaks            | 1        | 1.89%   |
| Sarajevo                | 1        | 1.89%   |
| Sao Paulo               | 1        | 1.89%   |
| Santa Barbara d'Oeste   | 1        | 1.89%   |
| San Secondo di Pinerolo | 1        | 1.89%   |
| Saint-Ouen-l'Aumone     | 1        | 1.89%   |
| Rio Grande da Serra     | 1        | 1.89%   |
| Rennes                  | 1        | 1.89%   |
| Perth                   | 1        | 1.89%   |
| Palermo                 | 1        | 1.89%   |
| Oslo                    | 1        | 1.89%   |
| Olympia                 | 1        | 1.89%   |
| Oldenburg               | 1        | 1.89%   |
| Naumburg                | 1        | 1.89%   |
| Nairobi                 | 1        | 1.89%   |
| Modesto                 | 1        | 1.89%   |
| Mérida                 | 1        | 1.89%   |
| Merced                  | 1        | 1.89%   |
| Maidenhead              | 1        | 1.89%   |
| Lyon                    | 1        | 1.89%   |
| Lomas de Zamora         | 1        | 1.89%   |
| Linz                    | 1        | 1.89%   |
| Limbach-Oberfrohna      | 1        | 1.89%   |
| Leongatha               | 1        | 1.89%   |
| Langenhagen             | 1        | 1.89%   |
| Haldensleben I          | 1        | 1.89%   |
| Haar                    | 1        | 1.89%   |
| Gresham                 | 1        | 1.89%   |
| Graz                    | 1        | 1.89%   |
| Geneva                  | 1        | 1.89%   |
| Formosa                 | 1        | 1.89%   |
| Évreux                 | 1        | 1.89%   |
| Ephrata                 | 1        | 1.89%   |
| Diessen am Ammersee     | 1        | 1.89%   |
| Curitiba                | 1        | 1.89%   |
| Cape Coral              | 1        | 1.89%   |
| Bucharest               | 1        | 1.89%   |
| Brussels                | 1        | 1.89%   |
| Bologna                 | 1        | 1.89%   |
| Boisjean                | 1        | 1.89%   |
| Badalona                | 1        | 1.89%   |
| Antwerp                 | 1        | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 21     | 17.02%  |
| Seagate             | 16       | 24     | 17.02%  |
| Samsung Electronics | 15       | 22     | 15.96%  |
| Toshiba             | 6        | 7      | 6.38%   |
| SanDisk             | 5        | 5      | 5.32%   |
| Kingston            | 4        | 4      | 4.26%   |
| Crucial             | 4        | 4      | 4.26%   |
| Hitachi             | 3        | 3      | 3.19%   |
| HGST                | 3        | 3      | 3.19%   |
| Intel               | 2        | 2      | 2.13%   |
| A-DATA Technology   | 2        | 2      | 2.13%   |
| USB 3.0             | 1        | 2      | 1.06%   |
| TO Exter            | 1        | 1      | 1.06%   |
| SPCC                | 1        | 1      | 1.06%   |
| Phison Electronics  | 1        | 1      | 1.06%   |
| Patriot             | 1        | 1      | 1.06%   |
| OCZ                 | 1        | 1      | 1.06%   |
| NGFF                | 1        | 1      | 1.06%   |
| Micron Technology   | 1        | 1      | 1.06%   |
| Maxtor              | 1        | 1      | 1.06%   |
| Leven               | 1        | 1      | 1.06%   |
| Intenso             | 1        | 1      | 1.06%   |
| Integral            | 1        | 1      | 1.06%   |
| Fujitsu             | 1        | 1      | 1.06%   |
| Corsair             | 1        | 1      | 1.06%   |
| China               | 1        | 1      | 1.06%   |
| BHT                 | 1        | 1      | 1.06%   |
| ASMT                | 1        | 1      | 1.06%   |
| Apple               | 1        | 1      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 3        | 2.68%   |
| Seagate ST2000DM001-1ER164 2TB  | 3        | 2.68%   |
| Seagate Expansion 1TB           | 2        | 1.79%   |
| SanDisk SDSSDA240G 240GB        | 2        | 1.79%   |
| Samsung SSD 970 EVO Plus 500GB  | 2        | 1.79%   |
| Samsung SSD 870 EVO 1TB         | 2        | 1.79%   |
| Samsung SSD 850 EVO 500GB       | 2        | 1.79%   |
| Crucial CT500MX500SSD1 500GB    | 2        | 1.79%   |
| WDC WDS200T2B0A-00SM50 2TB SSD  | 1        | 0.89%   |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 0.89%   |
| WDC WD5000AAKS-75V0A0 500GB     | 1        | 0.89%   |
| WDC WD40EZRZ-00GXCB0 4TB        | 1        | 0.89%   |
| WDC WD3200BEVT-22ZCT0 320GB     | 1        | 0.89%   |
| WDC WD3200AAKS-00VYA0 320GB     | 1        | 0.89%   |
| WDC WD30EZRZ-00Z5HB0 3TB        | 1        | 0.89%   |
| WDC WD30EZRX-00SPEB0 3TB        | 1        | 0.89%   |
| WDC WD2500AAKX-001CA0 250GB     | 1        | 0.89%   |
| WDC WD20EZRX-00D8PB0 2TB        | 1        | 0.89%   |
| WDC WD20EZAZ-00GGJB0 2TB        | 1        | 0.89%   |
| WDC WD1600AAJS-60Z0A0 160GB     | 1        | 0.89%   |
| WDC WD1600AAJS-08L7A0 160GB     | 1        | 0.89%   |
| WDC WD10EZEX-22RKKA0 1TB        | 1        | 0.89%   |
| WDC WD10EZEX-22MFCA0 1TB        | 1        | 0.89%   |
| WDC WD10EZEX-22BN5A0 1TB        | 1        | 0.89%   |
| WDC WD10EZEX-08WN4A0 1TB        | 1        | 0.89%   |
| WDC WD10EAVS-00D7B1 1TB         | 1        | 0.89%   |
| WDC WD10EARS-00Y5B1 1TB         | 1        | 0.89%   |
| WDC WD10EADS-00L5B1 1TB         | 1        | 0.89%   |
| WDC WD1003FBYZ-010FB0 1TB       | 1        | 0.89%   |
| USB 3.0 Disk 640GB              | 1        | 0.89%   |
| Toshiba MQ01ABB200 2TB          | 1        | 0.89%   |
| Toshiba HDWE150 5TB             | 1        | 0.89%   |
| Toshiba HDWE140 4TB             | 1        | 0.89%   |
| Toshiba HDWD130 3TB             | 1        | 0.89%   |
| Toshiba DT01ACA200 2TB          | 1        | 0.89%   |
| Toshiba DT01ACA100 1TB          | 1        | 0.89%   |
| Toshiba DT01ACA050 500GB        | 1        | 0.89%   |
| TO Exter nal USB 3.0 1TB        | 1        | 0.89%   |
| SPCC Solid State Disk 256GB     | 1        | 0.89%   |
| Seagate ST8000NM0105 8TB        | 1        | 0.89%   |
| Seagate ST8000DM004-2CX188 8TB  | 1        | 0.89%   |
| Seagate ST5000LM000-2AN170 5TB  | 1        | 0.89%   |
| Seagate ST3320820AS 320GB       | 1        | 0.89%   |
| Seagate ST3320620AS 320GB       | 1        | 0.89%   |
| Seagate ST3250410AS 250GB       | 1        | 0.89%   |
| Seagate ST2000LX001-1RG174 2TB  | 1        | 0.89%   |
| Seagate ST2000DM008-2FR102 2TB  | 1        | 0.89%   |
| Seagate ST1000VM002-9ZL162 1TB  | 1        | 0.89%   |
| Seagate ST1000DM003-1CH162 1TB  | 1        | 0.89%   |
| Seagate ST1000DL004 HD105SI 1TB | 1        | 0.89%   |
| Seagate Expansion Desk 4TB      | 1        | 0.89%   |
| Seagate BUP Portable 5TB        | 1        | 0.89%   |
| Seagate Backup+ Hub BK 4TB      | 1        | 0.89%   |
| Seagate Backup+ BK 2TB          | 1        | 0.89%   |
| SanDisk SSD PLUS 240GB          | 1        | 0.89%   |
| SanDisk SDSSDP064G 64GB         | 1        | 0.89%   |
| SanDisk SDSSDH3500G 500GB       | 1        | 0.89%   |
| Samsung SSD 980 PRO 2TB         | 1        | 0.89%   |
| Samsung SSD 980 PRO 1TB         | 1        | 0.89%   |
| Samsung SSD 970 EVO Plus 1TB    | 1        | 0.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 23     | 33.33%  |
| WDC                 | 15       | 20     | 31.25%  |
| Toshiba             | 6        | 7      | 12.5%   |
| Hitachi             | 3        | 3      | 6.25%   |
| HGST                | 3        | 3      | 6.25%   |
| Samsung Electronics | 2        | 2      | 4.17%   |
| USB 3.0             | 1        | 2      | 2.08%   |
| Maxtor              | 1        | 1      | 2.08%   |
| Fujitsu             | 1        | 1      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 23.68%  |
| SanDisk             | 5        | 5      | 13.16%  |
| Kingston            | 4        | 4      | 10.53%  |
| Crucial             | 4        | 4      | 10.53%  |
| A-DATA Technology   | 2        | 2      | 5.26%   |
| WDC                 | 1        | 1      | 2.63%   |
| TO Exter            | 1        | 1      | 2.63%   |
| SPCC                | 1        | 1      | 2.63%   |
| Patriot             | 1        | 1      | 2.63%   |
| OCZ                 | 1        | 1      | 2.63%   |
| NGFF                | 1        | 1      | 2.63%   |
| Micron Technology   | 1        | 1      | 2.63%   |
| Leven               | 1        | 1      | 2.63%   |
| Intenso             | 1        | 1      | 2.63%   |
| Integral            | 1        | 1      | 2.63%   |
| Corsair             | 1        | 1      | 2.63%   |
| China               | 1        | 1      | 2.63%   |
| BHT                 | 1        | 1      | 2.63%   |
| ASMT                | 1        | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 35       | 62     | 46.05%  |
| SSD     | 32       | 41     | 42.11%  |
| NVMe    | 8        | 12     | 10.53%  |
| Unknown | 1        | 1      | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 50       | 94     | 78.13%  |
| NVMe | 8        | 12     | 12.5%   |
| SAS  | 6        | 10     | 9.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 35       | 48     | 45.45%  |
| 0.51-1.0   | 24       | 31     | 31.17%  |
| 1.01-2.0   | 8        | 10     | 10.39%  |
| 3.01-4.0   | 5        | 5      | 6.49%   |
| 4.01-10.0  | 3        | 6      | 3.9%    |
| 2.01-3.0   | 2        | 3      | 2.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 19       | 35.85%  |
| 501-1000       | 10       | 18.87%  |
| 1001-2000      | 8        | 15.09%  |
| More than 3000 | 7        | 13.21%  |
| 251-500        | 4        | 7.55%   |
| 21-50          | 2        | 3.77%   |
| 51-100         | 2        | 3.77%   |
| 1-20           | 1        | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 18       | 33.96%  |
| 21-50          | 11       | 20.75%  |
| 101-250        | 5        | 9.43%   |
| 51-100         | 5        | 9.43%   |
| More than 3000 | 4        | 7.55%   |
| 501-1000       | 4        | 7.55%   |
| 251-500        | 3        | 5.66%   |
| 1001-2000      | 2        | 3.77%   |
| 2001-3000      | 1        | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 15.38%  |
| WDC WD1600AAJS-08L7A0 160GB           | 1        | 1      | 7.69%   |
| WDC WD10EZEX-22BN5A0 1TB              | 1        | 1      | 7.69%   |
| Toshiba HDWE140 4TB                   | 1        | 1      | 7.69%   |
| Seagate ST3320820AS 320GB             | 1        | 1      | 7.69%   |
| Seagate ST1000VM002-9ZL162 1TB        | 1        | 1      | 7.69%   |
| Samsung Electronics SSD 960 PRO 512GB | 1        | 1      | 7.69%   |
| Samsung Electronics HD753LJ 752GB     | 1        | 1      | 7.69%   |
| Hitachi HDS5C1010CLA382 1TB           | 1        | 1      | 7.69%   |
| HGST HTS721010A9 1TB                  | 1        | 1      | 7.69%   |
| A-DATA Technology SU650 240GB SSD     | 1        | 1      | 7.69%   |
| A-DATA Technology SP550 240GB SSD     | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 30.77%  |
| WDC                 | 2        | 2      | 15.38%  |
| Samsung Electronics | 2        | 2      | 15.38%  |
| A-DATA Technology   | 2        | 2      | 15.38%  |
| Toshiba             | 1        | 1      | 7.69%   |
| Hitachi             | 1        | 1      | 7.69%   |
| HGST                | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 40%     |
| WDC                 | 2        | 2      | 20%     |
| Toshiba             | 1        | 1      | 10%     |
| Samsung Electronics | 1        | 1      | 10%     |
| Hitachi             | 1        | 1      | 10%     |
| HGST                | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 10     | 75%     |
| SSD  | 2        | 2      | 16.67%  |
| NVMe | 1        | 1      | 8.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| WDC WD10EAVS-00D7B1 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 48       | 92     | 71.64%  |
| Malfunc  | 12       | 13     | 17.91%  |
| Detected | 6        | 10     | 8.96%   |
| Failed   | 1        | 1      | 1.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 36       | 50%     |
| AMD                      | 13       | 18.06%  |
| Samsung Electronics      | 5        | 6.94%   |
| ASMedia Technology       | 5        | 6.94%   |
| Nvidia                   | 3        | 4.17%   |
| Marvell Technology Group | 3        | 4.17%   |
| JMicron Technology       | 2        | 2.78%   |
| VIA Technologies         | 1        | 1.39%   |
| Silicon Image            | 1        | 1.39%   |
| Phison Electronics       | 1        | 1.39%   |
| Apple                    | 1        | 1.39%   |
| Adaptec                  | 1        | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 9.38%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 8.33%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 5.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 4.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 3.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 3.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 2.08%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2        | 2.08%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 2        | 2.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 2.08%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 2.08%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 2.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 2.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 2.08%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 1.04%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.04%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.04%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.04%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.04%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 1.04%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 1.04%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 1.04%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.04%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 1.04%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1        | 1.04%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.04%   |
| Intel NVMe Optane Memory Series                                                         | 1        | 1.04%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 1.04%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.04%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 1.04%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 1.04%   |
| Intel 82Q963/Q965 PT IDER Controller                                                    | 1        | 1.04%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 1.04%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.04%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 1        | 1.04%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 1.04%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1        | 1.04%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 1        | 1.04%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 1.04%   |
| Apple ANS2 NVMe Controller                                                              | 1        | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.04%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 1        | 1.04%   |
| AMD SB600 IDE                                                                           | 1        | 1.04%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.04%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.04%   |
| Adaptec AIC-7850T/7856T [AVA-2902/4/6 / AHA-2910]                                       | 1        | 1.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 41       | 57.75%  |
| IDE  | 17       | 23.94%  |
| NVMe | 8        | 11.27%  |
| RAID | 3        | 4.23%   |
| SAS  | 1        | 1.41%   |
| SCSI | 1        | 1.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 37       | 69.81%  |
| AMD    | 16       | 30.19%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz                | 3        | 5.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 3        | 5.66%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 2        | 3.77%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 2        | 3.77%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 2        | 3.77%   |
| Intel Xeon W-2150B CPU @ 3.00GHz                | 1        | 1.89%   |
| Intel Xeon CPU E5420 @ 2.50GHz                  | 1        | 1.89%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz              | 1        | 1.89%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 1        | 1.89%   |
| Intel Pentium 4 CPU 3.20GHz                     | 1        | 1.89%   |
| Intel Pentium 4 CPU 2.80GHz                     | 1        | 1.89%   |
| Intel Core i9-10900K CPU @ 3.70GHz              | 1        | 1.89%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1        | 1.89%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 1        | 1.89%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1        | 1.89%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 1.89%   |
| Intel Core i7 CPU 930 @ 2.80GHz                 | 1        | 1.89%   |
| Intel Core i5-9400T CPU @ 1.80GHz               | 1        | 1.89%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1        | 1.89%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 1.89%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1        | 1.89%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1        | 1.89%   |
| Intel Core i3-6100T CPU @ 3.20GHz               | 1        | 1.89%   |
| Intel Core i3-4340 CPU @ 3.60GHz                | 1        | 1.89%   |
| Intel Core i3-4150 CPU @ 3.50GHz                | 1        | 1.89%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 1        | 1.89%   |
| Intel Core i3 CPU 540 @ 3.07GHz                 | 1        | 1.89%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 1        | 1.89%   |
| Intel Core 2 CPU 6600 @ 2.40GHz                 | 1        | 1.89%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1        | 1.89%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor  | 1        | 1.89%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1        | 1.89%   |
| AMD Ryzen 7 3800X 8-Core Processor              | 1        | 1.89%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1        | 1.89%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics     | 1        | 1.89%   |
| AMD Phenom II X4 B97 Processor                  | 1        | 1.89%   |
| AMD Phenom II X4 B55 Processor                  | 1        | 1.89%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 1.89%   |
| AMD Eng Sample: PD340SC5M4MFH_37/34_Y           | 1        | 1.89%   |
| AMD Athlon X4 845 Quad Core Processor           | 1        | 1.89%   |
| AMD Athlon II X2 240 Processor                  | 1        | 1.89%   |
| AMD Athlon II X2 220 Processor                  | 1        | 1.89%   |
| AMD Athlon Dual Core Processor 4450e            | 1        | 1.89%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+      | 1        | 1.89%   |
| AMD A4-5300B APU with Radeon HD Graphics        | 1        | 1.89%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 15       | 28.3%   |
| Intel Core i7          | 7        | 13.21%  |
| Intel Core i3          | 5        | 9.43%   |
| Intel Xeon             | 3        | 5.66%   |
| Intel Pentium 4        | 2        | 3.77%   |
| AMD Phenom II X4       | 2        | 3.77%   |
| AMD Athlon II X2       | 2        | 3.77%   |
| Intel Pentium          | 1        | 1.89%   |
| Intel Core i9          | 1        | 1.89%   |
| Intel Core 2 Duo       | 1        | 1.89%   |
| Intel Core 2           | 1        | 1.89%   |
| Intel Celeron          | 1        | 1.89%   |
| AMD Ryzen Threadripper | 1        | 1.89%   |
| AMD Ryzen 9            | 1        | 1.89%   |
| AMD Ryzen 7            | 1        | 1.89%   |
| AMD Ryzen 5            | 1        | 1.89%   |
| AMD Ryzen 3            | 1        | 1.89%   |
| AMD FX                 | 1        | 1.89%   |
| AMD E                  | 1        | 1.89%   |
| AMD Athlon X4          | 1        | 1.89%   |
| AMD Athlon Dual Core   | 1        | 1.89%   |
| AMD Athlon 64 X2       | 1        | 1.89%   |
| AMD A4                 | 1        | 1.89%   |
| AMD A10                | 1        | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 26       | 49.06%  |
| 2      | 14       | 26.42%  |
| 8      | 3        | 5.66%   |
| 6      | 3        | 5.66%   |
| 1      | 3        | 5.66%   |
| 10     | 2        | 3.77%   |
| 32     | 1        | 1.89%   |
| 16     | 1        | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 52       | 98.11%  |
| 2      | 1        | 1.89%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 28       | 52.83%  |
| 2      | 25       | 47.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 52       | 98.11%  |
| 32-bit         | 1        | 1.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 10       | 18.87%  |
| Unknown    | 7        | 13.21%  |
| 0x206a7    | 4        | 7.55%   |
| 0x506e3    | 3        | 5.66%   |
| 0x306a9    | 3        | 5.66%   |
| 0x010000c8 | 3        | 5.66%   |
| 0xf41      | 2        | 3.77%   |
| 0x906ea    | 2        | 3.77%   |
| 0x10676    | 2        | 3.77%   |
| 0xa0655    | 1        | 1.89%   |
| 0x906ed    | 1        | 1.89%   |
| 0x6f6      | 1        | 1.89%   |
| 0x506ca    | 1        | 1.89%   |
| 0x50654    | 1        | 1.89%   |
| 0x206d7    | 1        | 1.89%   |
| 0x20655    | 1        | 1.89%   |
| 0x106a5    | 1        | 1.89%   |
| 0x0a201009 | 1        | 1.89%   |
| 0x08701021 | 1        | 1.89%   |
| 0x08301039 | 1        | 1.89%   |
| 0x08108109 | 1        | 1.89%   |
| 0x08101016 | 1        | 1.89%   |
| 0x06003106 | 1        | 1.89%   |
| 0x06001119 | 1        | 1.89%   |
| 0x06000852 | 1        | 1.89%   |
| 0x010000c7 | 1        | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 10       | 18.87%  |
| Skylake     | 6        | 11.32%  |
| SandyBridge | 5        | 9.43%   |
| KabyLake    | 4        | 7.55%   |
| K10         | 4        | 7.55%   |
| Zen 2       | 3        | 5.66%   |
| IvyBridge   | 3        | 5.66%   |
| Piledriver  | 2        | 3.77%   |
| Penryn      | 2        | 3.77%   |
| NetBurst    | 2        | 3.77%   |
| K8 Hammer   | 2        | 3.77%   |
| Zen+        | 1        | 1.89%   |
| Zen 3       | 1        | 1.89%   |
| Zen         | 1        | 1.89%   |
| Westmere    | 1        | 1.89%   |
| Steamroller | 1        | 1.89%   |
| Nehalem     | 1        | 1.89%   |
| Goldmont    | 1        | 1.89%   |
| Excavator   | 1        | 1.89%   |
| Core        | 1        | 1.89%   |
| CometLake   | 1        | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 27       | 47.37%  |
| Intel  | 17       | 29.82%  |
| AMD    | 13       | 22.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 8.62%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 5.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 5.17%   |
| Intel HD Graphics 530                                                       | 3        | 5.17%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 3.45%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 3.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 3.45%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.72%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1        | 1.72%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.72%   |
| Nvidia GT216 [GeForce 315]                                                  | 1        | 1.72%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.72%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.72%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.72%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.72%   |
| Nvidia GK208 [GeForce GT 720]                                               | 1        | 1.72%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 1.72%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.72%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.72%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.72%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.72%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.72%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.72%   |
| Nvidia C77 [GeForce 8200]                                                   | 1        | 1.72%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 1.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.72%   |
| Intel HD Graphics 630                                                       | 1        | 1.72%   |
| Intel HD Graphics 500                                                       | 1        | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.72%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 1.72%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.72%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.72%   |
| AMD Vega 10 [Radeon Instinct MI25]                                          | 1        | 1.72%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.72%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 1.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.72%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 1        | 1.72%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 1.72%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 1        | 1.72%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 1.72%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                               | 1        | 1.72%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 24       | 45.28%  |
| 1 x Intel      | 14       | 26.42%  |
| 1 x AMD        | 12       | 22.64%  |
| 2 x Nvidia     | 1        | 1.89%   |
| Intel + Nvidia | 1        | 1.89%   |
| AMD + Nvidia   | 1        | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 38       | 71.7%   |
| Proprietary | 15       | 28.3%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 30.19%  |
| 1.01-2.0   | 11       | 20.75%  |
| 0.51-1.0   | 7        | 13.21%  |
| 0.01-0.5   | 7        | 13.21%  |
| 3.01-4.0   | 5        | 9.43%   |
| 7.01-8.0   | 2        | 3.77%   |
| 8.01-16.0  | 2        | 3.77%   |
| 5.01-6.0   | 1        | 1.89%   |
| 2.01-3.0   | 1        | 1.89%   |
| 16.01-24.0 | 1        | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 9        | 14.06%  |
| Goldstar             | 8        | 12.5%   |
| Philips              | 6        | 9.38%   |
| Dell                 | 6        | 9.38%   |
| Acer                 | 6        | 9.38%   |
| Ancor Communications | 5        | 7.81%   |
| Hewlett-Packard      | 4        | 6.25%   |
| Eizo                 | 2        | 3.13%   |
| AOC                  | 2        | 3.13%   |
| VIE                  | 1        | 1.56%   |
| Unknown              | 1        | 1.56%   |
| TVT                  | 1        | 1.56%   |
| Targa Visionary      | 1        | 1.56%   |
| Sony                 | 1        | 1.56%   |
| Seiki                | 1        | 1.56%   |
| Onkyo                | 1        | 1.56%   |
| NEC Computers        | 1        | 1.56%   |
| Medion               | 1        | 1.56%   |
| KTC                  | 1        | 1.56%   |
| Iiyama               | 1        | 1.56%   |
| Hannspree            | 1        | 1.56%   |
| Fujitsu Siemens      | 1        | 1.56%   |
| DENON                | 1        | 1.56%   |
| ASUSTek Computer     | 1        | 1.56%   |
| Apple                | 1        | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 2        | 2.86%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                   | 1        | 1.43%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                   | 1        | 1.43%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                          | 1        | 1.43%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch     | 1        | 1.43%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                      | 1        | 1.43%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                     | 1        | 1.43%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1        | 1.43%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch       | 1        | 1.43%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch     | 1        | 1.43%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch    | 1        | 1.43%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch    | 1        | 1.43%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch    | 1        | 1.43%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch    | 1        | 1.43%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch      | 1        | 1.43%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1        | 1.43%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch    | 1        | 1.43%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 1.43%   |
| Philips PHL 244E5 PHLC0C0 1920x1080 527x296mm 23.8-inch                 | 1        | 1.43%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                   | 1        | 1.43%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 1        | 1.43%   |
| Philips 201E PHLC033 1600x900 443x249mm 20.0-inch                       | 1        | 1.43%   |
| Philips 190V PHL0847 1280x1024 376x301mm 19.0-inch                      | 1        | 1.43%   |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                      | 1        | 1.43%   |
| Onkyo HT-R494 ONK0F43 3840x2160 1150x650mm 52.0-inch                    | 1        | 1.43%   |
| NEC Computers LCD2180UX NEC662C 1600x1200 430x320mm 21.1-inch           | 1        | 1.43%   |
| Medion MD32119PR MED89C1 1280x1024 376x301mm 19.0-inch                  | 1        | 1.43%   |
| KTC H-W2206S-D KTC2203 1680x1050 433x270mm 20.1-inch                    | 1        | 1.43%   |
| Iiyama PL2435M IVM6112 1920x1080 521x293mm 23.5-inch                    | 1        | 1.43%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch             | 1        | 1.43%   |
| Hewlett-Packard LE2202x HWP2966 1920x1080 476x268mm 21.5-inch           | 1        | 1.43%   |
| Hewlett-Packard L1902 HWP261E 1280x1024 340x270mm 17.1-inch             | 1        | 1.43%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch               | 1        | 1.43%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                    | 1        | 1.43%   |
| Goldstar W2253 GSM56DC 1920x1080 510x290mm 23.1-inch                    | 1        | 1.43%   |
| Goldstar LG UltraFine GSM5B11                                           | 1        | 1.43%   |
| Goldstar L227W GSM566F 1680x1050 474x296mm 22.0-inch                    | 1        | 1.43%   |
| Goldstar L194WT GSM4B06 1440x900 408x255mm 18.9-inch                    | 1        | 1.43%   |
| Goldstar L1942 GSM4B85 1280x1024 376x301mm 19.0-inch                    | 1        | 1.43%   |
| Goldstar E1960 GSM4BE6 1360x768 406x229mm 18.4-inch                     | 1        | 1.43%   |
| Goldstar BK550Y GSM5B41 1920x1080 480x270mm 21.7-inch                   | 1        | 1.43%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                | 1        | 1.43%   |
| Goldstar 2D FHD TV GSM59C4 1920x1080 509x286mm 23.0-inch                | 1        | 1.43%   |
| Fujitsu Siemens B22W-6 LED FUS07F3 1680x1050 474x296mm 22.0-inch        | 1        | 1.43%   |
| Eizo S1910 ENC1786 1280x1024 376x301mm 19.0-inch                        | 1        | 1.43%   |
| Eizo EV2736W ENC2382 2560x1440 597x336mm 27.0-inch                      | 1        | 1.43%   |
| DENON AVRHD DON0042 3840x2160 1120x630mm 50.6-inch                      | 1        | 1.43%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                       | 1        | 1.43%   |
| Dell SE2216H DELF070 1920x1080 476x268mm 21.5-inch                      | 1        | 1.43%   |
| Dell LCD Monitor S2715H 5760x2160                                       | 1        | 1.43%   |
| Dell E2214H DELA09D 1920x1080 477x268mm 21.5-inch                       | 1        | 1.43%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                       | 1        | 1.43%   |
| Dell 2209WA DELF010 1680x1050 474x296mm 22.0-inch                       | 1        | 1.43%   |
| ASUSTek Computer PA278QV AUS2701 2560x1440 597x336mm 27.0-inch          | 1        | 1.43%   |
| Apple iMac APPAE1D 3840x2160 597x336mm 27.0-inch                        | 1        | 1.43%   |
| AOC G2460 AOC2460 1920x1080 530x300mm 24.0-inch                         | 1        | 1.43%   |
| AOC 2460G5 AOC0001 1920x1080 530x300mm 24.0-inch                        | 1        | 1.43%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                          | 1        | 1.43%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch        | 1        | 1.43%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch   | 1        | 1.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 40.68%  |
| 1280x1024 (SXGA)   | 8        | 13.56%  |
| 3840x2160 (4K)     | 6        | 10.17%  |
| 1680x1050 (WSXGA+) | 5        | 8.47%   |
| 1440x900 (WXGA+)   | 3        | 5.08%   |
| 2560x1440 (QHD)    | 2        | 3.39%   |
| 1920x1200 (WUXGA)  | 2        | 3.39%   |
| 1600x900 (HD+)     | 2        | 3.39%   |
| 1366x768 (WXGA)    | 2        | 3.39%   |
| 5760x2160          | 1        | 1.69%   |
| 1600x1200          | 1        | 1.69%   |
| 1400x1050          | 1        | 1.69%   |
| 1360x768           | 1        | 1.69%   |
| Unknown            | 1        | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 10       | 16.13%  |
| 23      | 9        | 14.52%  |
| 27      | 7        | 11.29%  |
| 19      | 7        | 11.29%  |
| 24      | 6        | 9.68%   |
| 22      | 5        | 8.06%   |
| 17      | 4        | 6.45%   |
| 20      | 3        | 4.84%   |
| 18      | 3        | 4.84%   |
| 84      | 1        | 1.61%   |
| 65      | 1        | 1.61%   |
| 52      | 1        | 1.61%   |
| 50      | 1        | 1.61%   |
| 32      | 1        | 1.61%   |
| 31      | 1        | 1.61%   |
| 15      | 1        | 1.61%   |
| Unknown | 1        | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 22       | 37.29%  |
| 501-600     | 20       | 33.9%   |
| 301-350     | 5        | 8.47%   |
| 351-400     | 4        | 6.78%   |
| 1001-1500   | 3        | 5.08%   |
| 601-700     | 2        | 3.39%   |
| 701-800     | 1        | 1.69%   |
| 1501-2000   | 1        | 1.69%   |
| Unknown     | 1        | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 35       | 61.4%   |
| 16/10   | 11       | 19.3%   |
| 5/4     | 7        | 12.28%  |
| 4/3     | 2        | 3.51%   |
| 3/2     | 1        | 1.75%   |
| Unknown | 1        | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 26       | 42.62%  |
| 151-200        | 11       | 18.03%  |
| 301-350        | 7        | 11.48%  |
| 141-150        | 7        | 11.48%  |
| More than 1000 | 4        | 6.56%   |
| 351-500        | 2        | 3.28%   |
| 251-300        | 2        | 3.28%   |
| 111-120        | 1        | 1.64%   |
| Unknown        | 1        | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 40       | 71.43%  |
| 101-120 | 12       | 21.43%  |
| 121-160 | 2        | 3.57%   |
| 161-240 | 1        | 1.79%   |
| Unknown | 1        | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 35       | 66.04%  |
| 2     | 18       | 33.96%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 29       | 36.71%  |
| Intel                           | 24       | 30.38%  |
| Qualcomm Atheros                | 7        | 8.86%   |
| Broadcom                        | 5        | 6.33%   |
| Nvidia                          | 3        | 3.8%    |
| TP-Link                         | 2        | 2.53%   |
| Aquantia                        | 2        | 2.53%   |
| ZyDAS                           | 1        | 1.27%   |
| Wacom                           | 1        | 1.27%   |
| Qualcomm Atheros Communications | 1        | 1.27%   |
| NetGear                         | 1        | 1.27%   |
| Microsoft                       | 1        | 1.27%   |
| Broadcom Limited                | 1        | 1.27%   |
| ASIX Electronics                | 1        | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23       | 27.06%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 7.06%   |
| Intel Wireless-AC 9260                                            | 3        | 3.53%   |
| Intel I211 Gigabit Network Connection                             | 3        | 3.53%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 2.35%   |
| Nvidia MCP77 Ethernet                                             | 2        | 2.35%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.35%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 2.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.35%   |
| ZyDAS ZD1211B 802.11g                                             | 1        | 1.18%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                          | 1        | 1.18%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 1.18%   |
| TP-Link 802.11ac NIC                                              | 1        | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.18%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 1.18%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.18%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 1        | 1.18%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.18%   |
| Realtek 802.11ac NIC                                              | 1        | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 1.18%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.18%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 1.18%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 1.18%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.18%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 1.18%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.18%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1        | 1.18%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 1.18%   |
| Intel Wireless 8265 / 8275                                        | 1        | 1.18%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.18%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.18%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.18%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.18%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.18%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 1.18%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 1.18%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.18%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.18%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 1.18%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 1.18%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                | 1        | 1.18%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 1.18%   |
| ASIX AX88772B                                                     | 1        | 1.18%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 25%     |
| Qualcomm Atheros                | 5        | 20.83%  |
| Realtek Semiconductor           | 4        | 16.67%  |
| TP-Link                         | 2        | 8.33%   |
| Broadcom                        | 2        | 8.33%   |
| ZyDAS                           | 1        | 4.17%   |
| Wacom                           | 1        | 4.17%   |
| Qualcomm Atheros Communications | 1        | 4.17%   |
| NetGear                         | 1        | 4.17%   |
| Microsoft                       | 1        | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Wireless-AC 9260                                      | 3        | 12.5%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter            | 2        | 8.33%   |
| Intel Cannon Lake PCH CNVi WiFi                             | 2        | 8.33%   |
| ZyDAS ZD1211B 802.11g                                       | 1        | 4.17%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                    | 1        | 4.17%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]  | 1        | 4.17%   |
| TP-Link 802.11ac NIC                                        | 1        | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 1        | 4.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                     | 1        | 4.17%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller   | 1        | 4.17%   |
| Realtek 802.11ac NIC                                        | 1        | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 1        | 4.17%   |
| Qualcomm Atheros AR9271 802.11n                             | 1        | 4.17%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter            | 1        | 4.17%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter  | 1        | 4.17%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU] | 1        | 4.17%   |
| Microsoft Xbox 360 Wireless Adapter                         | 1        | 4.17%   |
| Intel Wireless 8265 / 8275                                  | 1        | 4.17%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter          | 1        | 4.17%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter          | 1        | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 26       | 43.33%  |
| Intel                 | 22       | 36.67%  |
| Nvidia                | 3        | 5%      |
| Broadcom              | 3        | 5%      |
| Qualcomm Atheros      | 2        | 3.33%   |
| Aquantia              | 2        | 3.33%   |
| Broadcom Limited      | 1        | 1.67%   |
| ASIX Electronics      | 1        | 1.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23       | 37.7%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 9.84%   |
| Intel I211 Gigabit Network Connection                             | 3        | 4.92%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 4.92%   |
| Nvidia MCP77 Ethernet                                             | 2        | 3.28%   |
| Intel Ethernet Connection I217-V                                  | 2        | 3.28%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.28%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 3.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.64%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.64%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.64%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.64%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.64%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.64%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.64%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.64%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 1.64%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 1.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.64%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.64%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 1.64%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 1.64%   |
| ASIX AX88772B                                                     | 1        | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 53       | 68.83%  |
| WiFi     | 24       | 31.17%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 81.36%  |
| WiFi     | 11       | 18.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 62.26%  |
| 2     | 19       | 35.85%  |
| 3     | 1        | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 47       | 88.68%  |
| Yes  | 6        | 11.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 46.15%  |
| Cambridge Silicon Radio         | 3        | 23.08%  |
| Qualcomm Atheros Communications | 2        | 15.38%  |
| Realtek Semiconductor           | 1        | 7.69%   |
| ASUSTek Computer                | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth Device                              | 3        | 23.08%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 23.08%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 15.38%  |
| Realtek Bluetooth Radio                             | 1        | 7.69%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 7.69%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 7.69%   |
| Intel Bluetooth wireless interface                  | 1        | 7.69%   |
| ASUS BCM20702A0                                     | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 35       | 33.65%  |
| Nvidia                               | 22       | 21.15%  |
| AMD                                  | 17       | 16.35%  |
| Texas Instruments                    | 4        | 3.85%   |
| C-Media Electronics                  | 4        | 3.85%   |
| Yamaha                               | 3        | 2.88%   |
| Logitech                             | 2        | 1.92%   |
| ZOOM                                 | 1        | 0.96%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.96%   |
| Textech International                | 1        | 0.96%   |
| Studiologic                          | 1        | 0.96%   |
| SteelSeries ApS                      | 1        | 0.96%   |
| QinHeng Electronics                  | 1        | 0.96%   |
| Plantronics                          | 1        | 0.96%   |
| Medeli Electronics                   | 1        | 0.96%   |
| Mark of the Unicorn                  | 1        | 0.96%   |
| M-Audio                              | 1        | 0.96%   |
| KTMicro                              | 1        | 0.96%   |
| JMTek                                | 1        | 0.96%   |
| Focusrite-Novation                   | 1        | 0.96%   |
| Ensoniq                              | 1        | 0.96%   |
| BEHRINGER International              | 1        | 0.96%   |
| ASUSTek Computer                     | 1        | 0.96%   |
| Apple                                | 1        | 0.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 10       | 8.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6        | 5.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5        | 4.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4        | 3.36%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3        | 2.52%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 2.52%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 2.52%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 2.52%   |
| Intel 200 Series PCH HD Audio                                                     | 3        | 2.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 2.52%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 2.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 2.52%   |
| AMD FCH Azalia Controller                                                         | 3        | 2.52%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 1.68%   |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 1.68%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 1.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2        | 1.68%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 2        | 1.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.68%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 1.68%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 1.68%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.68%   |
| ZOOM U-22                                                                         | 1        | 0.84%   |
| Yamaha YMF-744B [DS-1S Audio Controller]                                          | 1        | 0.84%   |
| Yamaha MG-XU                                                                      | 1        | 0.84%   |
| Yamaha AG06/AG03                                                                  | 1        | 0.84%   |
| Thesycon Systemsoftware & Consulting USB HiRes Audio                              | 1        | 0.84%   |
| Textech International MIDI Interface cable                                        | 1        | 0.84%   |
| Texas Instruments PCM2900 Audio Codec                                             | 1        | 0.84%   |
| Studiologic SL STUDIO                                                             | 1        | 0.84%   |
| SteelSeries ApS Arctis Pro Wireless                                               | 1        | 0.84%   |
| QinHeng Electronics CH345 MIDI adapter                                            | 1        | 0.84%   |
| Plantronics DA40                                                                  | 1        | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.84%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 0.84%   |
| Nvidia High Definition Audio Controller                                           | 1        | 0.84%   |
| Nvidia GT216 HDMI Audio Controller                                                | 1        | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1        | 0.84%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1        | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 0.84%   |
| Nvidia GK110 High Definition Audio Controller                                     | 1        | 0.84%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1        | 0.84%   |
| Medeli Electronics USB Audio Device                                               | 1        | 0.84%   |
| Mark of the Unicorn M Series                                                      | 1        | 0.84%   |
| M-Audio M-Track                                                                   | 1        | 0.84%   |
| Logitech USB Headset                                                              | 1        | 0.84%   |
| Logitech Headset H390                                                             | 1        | 0.84%   |
| KTMicro KT_USB_AUDIO                                                              | 1        | 0.84%   |
| JMTek USB PnP Audio Device                                                        | 1        | 0.84%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 1        | 0.84%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 1        | 0.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 1        | 0.84%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                                 | 1        | 0.84%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 1        | 0.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1        | 0.84%   |
| Focusrite-Novation Scarlett 2i4 USB                                               | 1        | 0.84%   |
| Ensoniq 5880B / Creative Labs CT5880                                              | 1        | 0.84%   |
| C-Media Electronics CM8888 [Oxygen Express]                                       | 1        | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 11       | 16.18%  |
| Samsung Electronics | 10       | 14.71%  |
| Unknown             | 9        | 13.24%  |
| Kingston            | 8        | 11.76%  |
| Corsair             | 7        | 10.29%  |
| Crucial             | 6        | 8.82%   |
| Micron Technology   | 5        | 7.35%   |
| G.Skill             | 3        | 4.41%   |
| Patriot             | 2        | 2.94%   |
| Smart               | 1        | 1.47%   |
| S                   | 1        | 1.47%   |
| Nanya Technology    | 1        | 1.47%   |
| M                   | 1        | 1.47%   |
| HBS                 | 1        | 1.47%   |
| Aeneon              | 1        | 1.47%   |
| 0194808980CE        | 1        | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1600MT/s                     | 2        | 2.53%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s         | 2        | 2.53%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s         | 2        | 2.53%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s          | 2        | 2.53%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s      | 2        | 2.53%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s       | 2        | 2.53%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1        | 1.27%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                   | 1        | 1.27%   |
| Unknown RAM Module 512MB DIMM DDR                           | 1        | 1.27%   |
| Unknown RAM Module 256MB DIMM DDR                           | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1        | 1.27%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1        | 1.27%   |
| Unknown RAM Module 1024MB DIMM DDR                          | 1        | 1.27%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1        | 1.27%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s                 | 1        | 1.27%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s          | 1        | 1.27%   |
| SK hynix RAM TMT41GU6BFR8C-PBSC 8192MB DIMM DDR3 1600MT/s   | 1        | 1.27%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2666MT/s               | 1        | 1.27%   |
| SK hynix RAM HYMP564U64BP8-C4 512MB DIMM DDR 533MT/s        | 1        | 1.27%   |
| SK hynix RAM HYMP125F72CP8N3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 1.27%   |
| SK hynix RAM HYMP125F72CP8D3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 1.27%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s        | 1        | 1.27%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1        | 1.27%   |
| SK hynix RAM HMT351U7CFR8C-PB 4096MB DIMM DDR3 1600MT/s     | 1        | 1.27%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s        | 1        | 1.27%   |
| SK hynix RAM HMT325U7CFR8C-PB 2GB DIMM DDR3 1600MT/s        | 1        | 1.27%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s        | 1        | 1.27%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 1.27%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 1.27%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1        | 1.27%   |
| Samsung RAM Module 2048MB DIMM DDR3 1066MT/s                | 1        | 1.27%   |
| Samsung RAM M395T5750GZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1        | 1.27%   |
| Samsung RAM M395T5160QZ4-CE66 4GB FB-DIMM DDR2 667MT/s      | 1        | 1.27%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s      | 1        | 1.27%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s         | 1        | 1.27%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s      | 1        | 1.27%   |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s         | 1        | 1.27%   |
| S RAM Module 8192MB DIMM DDR3 1600MT/s                      | 1        | 1.27%   |
| Nanya RAM M2F2G64CB88B7N-CG 2048MB DIMM 1333MT/s            | 1        | 1.27%   |
| Micron RAM 8HTF6464AY-53EB7 512MB DIMM DDR 533MT/s          | 1        | 1.27%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 1        | 1.27%   |
| Micron RAM 18JSF51272AZ-1G9K 4096MB DIMM DDR3 1866MT/s      | 1        | 1.27%   |
| Micron RAM 18JSF1G72AZ-1G6E1 8192MB DIMM DDR3 1600MT/s      | 1        | 1.27%   |
| M RAM Module 8192MB DIMM DDR3 1600MT/s                      | 1        | 1.27%   |
| Kingston RAM Module 4096MB DIMM DDR3 1066MT/s               | 1        | 1.27%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s      | 1        | 1.27%   |
| Kingston RAM K531R8-MIN 4096MB DIMM DDR3 1600MT/s           | 1        | 1.27%   |
| Kingston RAM 99U5471-036.A00LF 8GB DIMM DDR3 1600MT/s       | 1        | 1.27%   |
| Kingston RAM 99U5458-035.A00LF 8192MB DIMM DDR3 1333MT/s    | 1        | 1.27%   |
| Kingston RAM 9965525-033.A00LF 4096MB DIMM DDR3 1333MT/s    | 1        | 1.27%   |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s           | 1        | 1.27%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s       | 1        | 1.27%   |
| HBS RAM HB3DU004GFM8MMC16 4096MB DIMM DDR3 1333MT/s         | 1        | 1.27%   |
| G.Skill RAM F4-3200C16-32GTZN 32GB DIMM DDR4 3200MT/s       | 1        | 1.27%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 1        | 1.27%   |
| G.Skill RAM F3-1866C10-8GAB 8GB DIMM DDR3 1867MT/s          | 1        | 1.27%   |
| Crucial RAM CT8G4DFS8266.M8FD 8192MB DIMM DDR4 2667MT/s     | 1        | 1.27%   |
| Crucial RAM CT8G4DFS8213.M8FB 8GB DIMM DDR4 2133MT/s        | 1        | 1.27%   |
| Crucial RAM CT51272BD160B.M18 4096MB DIMM DDR3 1600MT/s     | 1        | 1.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 26       | 48.15%  |
| DDR4    | 16       | 29.63%  |
| DDR2    | 4        | 7.41%   |
| Unknown | 4        | 7.41%   |
| DDR     | 3        | 5.56%   |
| SDRAM   | 1        | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 48       | 90.57%  |
| SODIMM  | 4        | 7.55%   |
| FB-DIMM | 1        | 1.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 18       | 30.51%  |
| 4096  | 15       | 25.42%  |
| 2048  | 8        | 13.56%  |
| 16384 | 6        | 10.17%  |
| 1024  | 5        | 8.47%   |
| 32768 | 4        | 6.78%   |
| 512   | 2        | 3.39%   |
| 256   | 1        | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 19       | 31.67%  |
| 1333    | 6        | 10%     |
| 3200    | 4        | 6.67%   |
| 2667    | 3        | 5%      |
| 2133    | 3        | 5%      |
| 1866    | 3        | 5%      |
| 1066    | 3        | 5%      |
| 800     | 3        | 5%      |
| 1867    | 2        | 3.33%   |
| 667     | 2        | 3.33%   |
| Unknown | 2        | 3.33%   |
| 3600    | 1        | 1.67%   |
| 3500    | 1        | 1.67%   |
| 3466    | 1        | 1.67%   |
| 3266    | 1        | 1.67%   |
| 2933    | 1        | 1.67%   |
| 2800    | 1        | 1.67%   |
| 2666    | 1        | 1.67%   |
| 2400    | 1        | 1.67%   |
| 1800    | 1        | 1.67%   |
| 533     | 1        | 1.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 66.67%  |
| Canon           | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| HP OfficeJet Pro 6960 | 1        | 33.33%  |
| HP OfficeJet 6950     | 1        | 33.33%  |
| Canon LiDE 400        | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| Canon CanoScan FB630U | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 5        | 38.46%  |
| Samsung Electronics           | 2        | 15.38%  |
| Microsoft                     | 2        | 15.38%  |
| ViewSonic                     | 1        | 7.69%   |
| Sweex                         | 1        | 7.69%   |
| Sunplus Innovation Technology | 1        | 7.69%   |
| Philips (or NXP)              | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)                | 2        | 15.38%  |
| ViewSonic PC Camera                    | 1        | 7.69%   |
| Sweex WC060 Series HD Webcam           | 1        | 7.69%   |
| Sunplus HD 720P webcam                 | 1        | 7.69%   |
| Philips (or NXP) Webcam SPC530NC       | 1        | 7.69%   |
| Microsoft LifeCam VX-5000              | 1        | 7.69%   |
| Microsoft LifeCam Cinema               | 1        | 7.69%   |
| Logitech Webcam C270                   | 1        | 7.69%   |
| Logitech QuickCam Communicate MP/S5500 | 1        | 7.69%   |
| Logitech Portable Webcam C905          | 1        | 7.69%   |
| Logitech HD Webcam C910                | 1        | 7.69%   |
| Logitech HD Pro Webcam C920            | 1        | 7.69%   |

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
| 0     | 48       | 90.57%  |
| 1     | 5        | 9.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 2        | 40%     |
| Net/wireless             | 2        | 40%     |
| Communication controller | 1        | 20%     |

