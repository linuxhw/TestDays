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

Total: 68

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 09F8h                       | [f1107e91f2](https://linux-hardware.org/?probe=f1107e91f2) | Nov 01, 2022 |
| MSI           | Z77A-G45 Thunderbolt        | [fa189cf50b](https://linux-hardware.org/?probe=fa189cf50b) | Oct 30, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ea04a21af7](https://linux-hardware.org/?probe=ea04a21af7) | Oct 27, 2022 |
| Gigabyte      | X79S-UP5                    | [62f59af32c](https://linux-hardware.org/?probe=62f59af32c) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [5b39dcf114](https://linux-hardware.org/?probe=5b39dcf114) | Sep 19, 2022 |
| ASUSTek       | P8P67 LE                    | [07428c96e1](https://linux-hardware.org/?probe=07428c96e1) | Sep 11, 2022 |
| HP            | 18E7                        | [698520133f](https://linux-hardware.org/?probe=698520133f) | Aug 22, 2022 |
| Dell          | 0T10XW A02                  | [45491460bc](https://linux-hardware.org/?probe=45491460bc) | Aug 12, 2022 |
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
| Ubuntu Studio 20.04 | 39       | 63.93%  |
| Ubuntu Studio 20.10 | 9        | 14.75%  |
| Ubuntu Studio 22.04 | 7        | 11.48%  |
| Ubuntu Studio 21.10 | 3        | 4.92%   |
| Ubuntu Studio 21.04 | 2        | 3.28%   |
| Ubuntu Studio 16.04 | 1        | 1.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu Studio | 61       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.11.0-44-lowlatency     | 3        | 4.92%   |
| 5.8.0-48-lowlatency      | 2        | 3.28%   |
| 5.8.0-44-lowlatency      | 2        | 3.28%   |
| 5.8.0-25-lowlatency      | 2        | 3.28%   |
| 5.4.0-58-lowlatency      | 2        | 3.28%   |
| 5.4.0-56-lowlatency      | 2        | 3.28%   |
| 5.4.0-42-lowlatency      | 2        | 3.28%   |
| 5.4.0-26-lowlatency      | 2        | 3.28%   |
| 5.15.0-52-lowlatency     | 2        | 3.28%   |
| 5.15.0-46-lowlatency     | 2        | 3.28%   |
| 5.13.0-28-lowlatency     | 2        | 3.28%   |
| 5.8.0-50-lowlatency      | 1        | 1.64%   |
| 5.8.0-45-lowlatency      | 1        | 1.64%   |
| 5.8.0-36-lowlatency      | 1        | 1.64%   |
| 5.8.0-34-lowlatency      | 1        | 1.64%   |
| 5.8.0-33-lowlatency      | 1        | 1.64%   |
| 5.8.0-29-lowlatency      | 1        | 1.64%   |
| 5.4.0-99-lowlatency      | 1        | 1.64%   |
| 5.4.0-72-lowlatency      | 1        | 1.64%   |
| 5.4.0-71-lowlatency      | 1        | 1.64%   |
| 5.4.0-70-lowlatency      | 1        | 1.64%   |
| 5.4.0-65-lowlatency      | 1        | 1.64%   |
| 5.4.0-65-generic         | 1        | 1.64%   |
| 5.4.0-64-lowlatency      | 1        | 1.64%   |
| 5.4.0-62-lowlatency      | 1        | 1.64%   |
| 5.4.0-60-lowlatency      | 1        | 1.64%   |
| 5.4.0-53-lowlatency      | 1        | 1.64%   |
| 5.4.0-52-lowlatency      | 1        | 1.64%   |
| 5.4.0-51-lowlatency      | 1        | 1.64%   |
| 5.4.0-48-lowlatency      | 1        | 1.64%   |
| 5.4.0-47-lowlatency      | 1        | 1.64%   |
| 5.4.0-39-lowlatency      | 1        | 1.64%   |
| 5.4.0-33-lowlatency      | 1        | 1.64%   |
| 5.4.0-131-lowlatency     | 1        | 1.64%   |
| 5.4.0-125-lowlatency     | 1        | 1.64%   |
| 5.4.0-122-lowlatency     | 1        | 1.64%   |
| 5.4.0-122-generic        | 1        | 1.64%   |
| 5.4.0-110-lowlatency     | 1        | 1.64%   |
| 5.4.0-109-lowlatency     | 1        | 1.64%   |
| 5.15.6-051506-lowlatency | 1        | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 30       | 49.18%  |
| 5.8.0   | 12       | 19.67%  |
| 5.15.0  | 8        | 13.11%  |
| 5.11.0  | 6        | 9.84%   |
| 5.13.0  | 3        | 4.92%   |
| 5.15.6  | 1        | 1.64%   |
| 4.4.0   | 1        | 1.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 30       | 49.18%  |
| 5.8     | 12       | 19.67%  |
| 5.15    | 9        | 14.75%  |
| 5.11    | 6        | 9.84%   |
| 5.13    | 3        | 4.92%   |
| 4.4     | 1        | 1.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 60       | 98.36%  |
| i686   | 1        | 1.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| XFCE            | 33       | 54.1%   |
| KDE5            | 17       | 27.87%  |
| GNOME           | 5        | 8.2%    |
| MATE            | 2        | 3.28%   |
| LXQt            | 1        | 1.64%   |
| KDE             | 1        | 1.64%   |
| GNOME Flashback | 1        | 1.64%   |
| Cinnamon        | 1        | 1.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 57       | 93.44%  |
| Wayland | 2        | 3.28%   |
| Tty     | 2        | 3.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 25       | 40.98%  |
| SDDM    | 16       | 26.23%  |
| LightDM | 14       | 22.95%  |
| GDM     | 6        | 9.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 24       | 39.34%  |
| de_DE      | 7        | 11.48%  |
| fr_FR      | 6        | 9.84%   |
| pt_BR      | 4        | 6.56%   |
| en_GB      | 4        | 6.56%   |
| it_IT      | 3        | 4.92%   |
| en_AU      | 2        | 3.28%   |
| nl_NL      | 1        | 1.64%   |
| nl_BE      | 1        | 1.64%   |
| nb_NO      | 1        | 1.64%   |
| fr_FR.UTF8 | 1        | 1.64%   |
| fr_CH      | 1        | 1.64%   |
| es_GT      | 1        | 1.64%   |
| es_AR      | 1        | 1.64%   |
| en_DE      | 1        | 1.64%   |
| en_CA      | 1        | 1.64%   |
| ca_ES      | 1        | 1.64%   |
| ca_AD      | 1        | 1.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 36       | 59.02%  |
| EFI  | 25       | 40.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 59       | 96.72%  |
| Xfs  | 1        | 1.64%   |
| Ext2 | 1        | 1.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 32       | 52.46%  |
| GPT  | 29       | 47.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 75.41%  |
| Yes       | 15       | 24.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 54.1%   |
| Yes       | 28       | 45.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 18       | 29.51%  |
| Dell                | 10       | 16.39%  |
| Gigabyte Technology | 8        | 13.11%  |
| Hewlett-Packard     | 7        | 11.48%  |
| Fujitsu             | 3        | 4.92%   |
| MSI                 | 2        | 3.28%   |
| ASRock              | 2        | 3.28%   |
| Pegatron            | 1        | 1.64%   |
| Packard Bell        | 1        | 1.64%   |
| Medion              | 1        | 1.64%   |
| Lenovo              | 1        | 1.64%   |
| Intel               | 1        | 1.64%   |
| IBM                 | 1        | 1.64%   |
| Foxconn             | 1        | 1.64%   |
| AZW                 | 1        | 1.64%   |
| Apple               | 1        | 1.64%   |
| Acidanthera         | 1        | 1.64%   |
| Acer                | 1        | 1.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 4        | 6.56%   |
| Dell OptiPlex 790                  | 2        | 3.28%   |
| Pegatron FL368AA-UUZ SR5612CH      | 1        | 1.64%   |
| Packard Bell IMEDIA S3220          | 1        | 1.64%   |
| MSI MS-7A57                        | 1        | 1.64%   |
| MSI MS-7752                        | 1        | 1.64%   |
| Medion MD34207/C746                | 1        | 1.64%   |
| Lenovo ThinkCentre M93p 10A8S45S00 | 1        | 1.64%   |
| Intel DQ965GF HD/FP Audio          | 1        | 1.64%   |
| IBM 8188PPV                        | 1        | 1.64%   |
| HP Z620 Workstation                | 1        | 1.64%   |
| HP ProDesk 600 G1 SFF              | 1        | 1.64%   |
| HP Compaq Pro 6305 SFF             | 1        | 1.64%   |
| HP Compaq Elite 8300 CMT           | 1        | 1.64%   |
| HP Compaq dc7600 Small Form Factor | 1        | 1.64%   |
| HP Compaq 8200 Elite SFF PC        | 1        | 1.64%   |
| HP Compaq 6005 Pro MT PC           | 1        | 1.64%   |
| Gigabyte X79S-UP5                  | 1        | 1.64%   |
| Gigabyte X570 AORUS ELITE WIFI     | 1        | 1.64%   |
| Gigabyte H170-HD3-CF               | 1        | 1.64%   |
| Gigabyte GA-MA770-DS3              | 1        | 1.64%   |
| Gigabyte F2A78M-HD2                | 1        | 1.64%   |
| Gigabyte B450M S2H                 | 1        | 1.64%   |
| Gigabyte B450 I AORUS PRO WIFI     | 1        | 1.64%   |
| Gigabyte A320M-S2H                 | 1        | 1.64%   |
| Fujitsu ESPRIMO P420               | 1        | 1.64%   |
| Fujitsu ESPRIMO G558               | 1        | 1.64%   |
| Fujitsu ESPRIMO E720               | 1        | 1.64%   |
| Foxconn Pro3500 Series             | 1        | 1.64%   |
| Dell Precision WorkStation T5400   | 1        | 1.64%   |
| Dell OptiPlex GX620                | 1        | 1.64%   |
| Dell OptiPlex 7050                 | 1        | 1.64%   |
| Dell OptiPlex 7020                 | 1        | 1.64%   |
| Dell OptiPlex 3040                 | 1        | 1.64%   |
| Dell OptiPlex 3020                 | 1        | 1.64%   |
| Dell OptiPlex 3010                 | 1        | 1.64%   |
| Dell Inspiron 3647                 | 1        | 1.64%   |
| AZW GK35                           | 1        | 1.64%   |
| ASUS TUF Gaming X570-PLUS          | 1        | 1.64%   |
| ASUS TUF B360-PRO GAMING           | 1        | 1.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 8        | 13.11%  |
| HP Compaq             | 5        | 8.2%    |
| ASUS All              | 4        | 6.56%   |
| Fujitsu ESPRIMO       | 3        | 4.92%   |
| ASUS ROG              | 3        | 4.92%   |
| ASUS TUF              | 2        | 3.28%   |
| ASUS P8P67            | 2        | 3.28%   |
| Pegatron FL368AA-UUZ  | 1        | 1.64%   |
| Packard Bell IMEDIA   | 1        | 1.64%   |
| MSI MS-7A57           | 1        | 1.64%   |
| MSI MS-7752           | 1        | 1.64%   |
| Medion MD34207        | 1        | 1.64%   |
| Lenovo ThinkCentre    | 1        | 1.64%   |
| Intel DQ965GF         | 1        | 1.64%   |
| IBM 8188PPV           | 1        | 1.64%   |
| HP Z620               | 1        | 1.64%   |
| HP ProDesk            | 1        | 1.64%   |
| Gigabyte X79S-UP5     | 1        | 1.64%   |
| Gigabyte X570         | 1        | 1.64%   |
| Gigabyte H170-HD3-CF  | 1        | 1.64%   |
| Gigabyte GA-MA770-DS3 | 1        | 1.64%   |
| Gigabyte F2A78M-HD2   | 1        | 1.64%   |
| Gigabyte B450M        | 1        | 1.64%   |
| Gigabyte B450         | 1        | 1.64%   |
| Gigabyte A320M-S2H    | 1        | 1.64%   |
| Foxconn Pro3500       | 1        | 1.64%   |
| Dell Precision        | 1        | 1.64%   |
| Dell Inspiron         | 1        | 1.64%   |
| AZW GK35              | 1        | 1.64%   |
| ASUS PRIME            | 1        | 1.64%   |
| ASUS P6T              | 1        | 1.64%   |
| ASUS P5QC             | 1        | 1.64%   |
| ASUS M5A78L-M         | 1        | 1.64%   |
| ASUS M4A88TD-M        | 1        | 1.64%   |
| ASUS H110M-A          | 1        | 1.64%   |
| ASUS A68HM-PLUS       | 1        | 1.64%   |
| ASRock H55M           | 1        | 1.64%   |
| ASRock B250M-HDV      | 1        | 1.64%   |
| Apple iMacPro1        | 1        | 1.64%   |
| Acidanthera MacPro6   | 1        | 1.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 9        | 14.75%  |
| 2014 | 6        | 9.84%   |
| 2019 | 5        | 8.2%    |
| 2018 | 5        | 8.2%    |
| 2011 | 5        | 8.2%    |
| 2017 | 4        | 6.56%   |
| 2012 | 4        | 6.56%   |
| 2010 | 4        | 6.56%   |
| 2020 | 3        | 4.92%   |
| 2008 | 3        | 4.92%   |
| 2005 | 3        | 4.92%   |
| 2021 | 2        | 3.28%   |
| 2016 | 2        | 3.28%   |
| 2015 | 2        | 3.28%   |
| 2009 | 2        | 3.28%   |
| 2007 | 2        | 3.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 61       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 60       | 98.36%  |
| Enabled  | 1        | 1.64%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 61       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 19       | 31.15%  |
| 8.01-16.0   | 11       | 18.03%  |
| 4.01-8.0    | 10       | 16.39%  |
| 3.01-4.0    | 6        | 9.84%   |
| 32.01-64.0  | 5        | 8.2%    |
| 64.01-256.0 | 5        | 8.2%    |
| 1.01-2.0    | 3        | 4.92%   |
| 24.01-32.0  | 1        | 1.64%   |
| 2.01-3.0    | 1        | 1.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 23       | 37.7%   |
| 2.01-3.0   | 13       | 21.31%  |
| 4.01-8.0   | 11       | 18.03%  |
| 8.01-16.0  | 6        | 9.84%   |
| 3.01-4.0   | 4        | 6.56%   |
| 0.51-1.0   | 3        | 4.92%   |
| 24.01-32.0 | 1        | 1.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 25       | 40.98%  |
| 1      | 23       | 37.7%   |
| 3      | 6        | 9.84%   |
| 7      | 2        | 3.28%   |
| 4      | 2        | 3.28%   |
| 11     | 1        | 1.64%   |
| 10     | 1        | 1.64%   |
| 5      | 1        | 1.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 40       | 65.57%  |
| No        | 21       | 34.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 61       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 54.1%   |
| Yes       | 28       | 45.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 70.49%  |
| Yes       | 18       | 29.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 13       | 21.31%  |
| Germany                | 9        | 14.75%  |
| France                 | 9        | 14.75%  |
| Italy                  | 5        | 8.2%    |
| Brazil                 | 5        | 8.2%    |
| UK                     | 2        | 3.28%   |
| Spain                  | 2        | 3.28%   |
| Belgium                | 2        | 3.28%   |
| Austria                | 2        | 3.28%   |
| Australia              | 2        | 3.28%   |
| Switzerland            | 1        | 1.64%   |
| Sweden                 | 1        | 1.64%   |
| Romania                | 1        | 1.64%   |
| Norway                 | 1        | 1.64%   |
| Netherlands            | 1        | 1.64%   |
| Mexico                 | 1        | 1.64%   |
| Kenya                  | 1        | 1.64%   |
| Guatemala              | 1        | 1.64%   |
| Bosnia and Herzegovina | 1        | 1.64%   |
| Argentina              | 1        | 1.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Paris                   | 3        | 4.92%   |
| Houston                 | 2        | 3.28%   |
| Zanesville              | 1        | 1.64%   |
| Villefontaine           | 1        | 1.64%   |
| Turin                   | 1        | 1.64%   |
| Tilburg                 | 1        | 1.64%   |
| Stuttgart               | 1        | 1.64%   |
| Stockholm               | 1        | 1.64%   |
| Sherman Oaks            | 1        | 1.64%   |
| Sarajevo                | 1        | 1.64%   |
| Sao Paulo               | 1        | 1.64%   |
| Santa Barbara d'Oeste   | 1        | 1.64%   |
| San Secondo di Pinerolo | 1        | 1.64%   |
| Saint-Ouen-l'Aumone     | 1        | 1.64%   |
| Rio Grande da Serra     | 1        | 1.64%   |
| Rennes                  | 1        | 1.64%   |
| Perth                   | 1        | 1.64%   |
| Palermo                 | 1        | 1.64%   |
| Oslo                    | 1        | 1.64%   |
| Olympia                 | 1        | 1.64%   |
| Oldenburg               | 1        | 1.64%   |
| Naumburg                | 1        | 1.64%   |
| Nairobi                 | 1        | 1.64%   |
| Munich                  | 1        | 1.64%   |
| Modesto                 | 1        | 1.64%   |
| Miami                   | 1        | 1.64%   |
| Mérida                 | 1        | 1.64%   |
| Merced                  | 1        | 1.64%   |
| Manchester              | 1        | 1.64%   |
| Maidenhead              | 1        | 1.64%   |
| Lyon                    | 1        | 1.64%   |
| Lomas de Zamora         | 1        | 1.64%   |
| Linz                    | 1        | 1.64%   |
| Limbach-Oberfrohna      | 1        | 1.64%   |
| Leongatha               | 1        | 1.64%   |
| Langenhagen             | 1        | 1.64%   |
| Haldensleben I          | 1        | 1.64%   |
| Haar                    | 1        | 1.64%   |
| Guatemala City          | 1        | 1.64%   |
| Gresham                 | 1        | 1.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 29     | 19.3%   |
| Seagate             | 20       | 28     | 17.54%  |
| Samsung Electronics | 18       | 25     | 15.79%  |
| SanDisk             | 7        | 8      | 6.14%   |
| Toshiba             | 6        | 7      | 5.26%   |
| Crucial             | 5        | 5      | 4.39%   |
| Kingston            | 4        | 4      | 3.51%   |
| Hitachi             | 3        | 3      | 2.63%   |
| HGST                | 3        | 3      | 2.63%   |
| Intenso             | 2        | 2      | 1.75%   |
| Intel               | 2        | 2      | 1.75%   |
| Corsair             | 2        | 3      | 1.75%   |
| ASMT                | 2        | 2      | 1.75%   |
| A-DATA Technology   | 2        | 2      | 1.75%   |
| USB 3.0             | 1        | 2      | 0.88%   |
| TO Exter            | 1        | 1      | 0.88%   |
| SPCC                | 1        | 1      | 0.88%   |
| Phison Electronics  | 1        | 1      | 0.88%   |
| Patriot             | 1        | 1      | 0.88%   |
| OCZ                 | 1        | 1      | 0.88%   |
| NGFF                | 1        | 1      | 0.88%   |
| Micron Technology   | 1        | 1      | 0.88%   |
| Maxtor              | 1        | 1      | 0.88%   |
| Leven               | 1        | 1      | 0.88%   |
| JMicron Technology  | 1        | 1      | 0.88%   |
| Integral            | 1        | 1      | 0.88%   |
| Fujitsu             | 1        | 1      | 0.88%   |
| China               | 1        | 1      | 0.88%   |
| BHT                 | 1        | 1      | 0.88%   |
| Apple               | 1        | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 4        | 3.01%   |
| Seagate ST2000DM001-1ER164 2TB  | 3        | 2.26%   |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 1.5%    |
| Seagate Expansion 2TB           | 2        | 1.5%    |
| SanDisk SDSSDA240G 240GB        | 2        | 1.5%    |
| Samsung SSD 970 EVO Plus 500GB  | 2        | 1.5%    |
| Samsung SSD 870 EVO 1TB         | 2        | 1.5%    |
| Samsung SSD 860 EVO 1TB         | 2        | 1.5%    |
| Samsung SSD 850 EVO 500GB       | 2        | 1.5%    |
| Crucial CT500MX500SSD1 500GB    | 2        | 1.5%    |
| WDC WDS512G1X0C-00ENX0 512GB    | 1        | 0.75%   |
| WDC WDS200T2B0A-00SM50 2TB SSD  | 1        | 0.75%   |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 0.75%   |
| WDC WD5000BPKT-60PK4T0 500GB    | 1        | 0.75%   |
| WDC WD5000AAKS-75V0A0 500GB     | 1        | 0.75%   |
| WDC WD40EZRZ-00GXCB0 4TB        | 1        | 0.75%   |
| WDC WD40EFRX-68N32N0 4TB        | 1        | 0.75%   |
| WDC WD40EFAX-68JH4N1 4TB        | 1        | 0.75%   |
| WDC WD40EFAX-68JH4N0 4TB        | 1        | 0.75%   |
| WDC WD3200BPVT-75JJ5T0 320GB    | 1        | 0.75%   |
| WDC WD3200BEVT-22ZCT0 320GB     | 1        | 0.75%   |
| WDC WD3200AAKS-00VYA0 320GB     | 1        | 0.75%   |
| WDC WD30EZRZ-00Z5HB0 3TB        | 1        | 0.75%   |
| WDC WD30EZRX-00SPEB0 3TB        | 1        | 0.75%   |
| WDC WD2500AAKX-001CA0 250GB     | 1        | 0.75%   |
| WDC WD20EZRX-00D8PB0 2TB        | 1        | 0.75%   |
| WDC WD20EZAZ-00GGJB0 2TB        | 1        | 0.75%   |
| WDC WD1600AAJS-60Z0A0 160GB     | 1        | 0.75%   |
| WDC WD1600AAJS-08L7A0 160GB     | 1        | 0.75%   |
| WDC WD10EZEX-22RKKA0 1TB        | 1        | 0.75%   |
| WDC WD10EZEX-22MFCA0 1TB        | 1        | 0.75%   |
| WDC WD10EZEX-22BN5A0 1TB        | 1        | 0.75%   |
| WDC WD10EZEX-08WN4A0 1TB        | 1        | 0.75%   |
| WDC WD10EZEX-00RKKA0 1TB        | 1        | 0.75%   |
| WDC WD10EAVS-00D7B1 1TB         | 1        | 0.75%   |
| WDC WD10EARS-00Y5B1 1TB         | 1        | 0.75%   |
| WDC WD10EADS-00L5B1 1TB         | 1        | 0.75%   |
| WDC WD1003FBYZ-010FB0 1TB       | 1        | 0.75%   |
| USB 3.0 Disk 640GB              | 1        | 0.75%   |
| Toshiba MQ01ABB200 2TB          | 1        | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 27     | 35.09%  |
| Seagate             | 20       | 27     | 35.09%  |
| Toshiba             | 6        | 7      | 10.53%  |
| Hitachi             | 3        | 3      | 5.26%   |
| HGST                | 3        | 3      | 5.26%   |
| Samsung Electronics | 2        | 2      | 3.51%   |
| USB 3.0             | 1        | 2      | 1.75%   |
| Maxtor              | 1        | 1      | 1.75%   |
| Fujitsu             | 1        | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 12       | 15     | 26.09%  |
| SanDisk             | 7        | 8      | 15.22%  |
| Crucial             | 5        | 5      | 10.87%  |
| Kingston            | 4        | 4      | 8.7%    |
| Intenso             | 2        | 2      | 4.35%   |
| ASMT                | 2        | 2      | 4.35%   |
| A-DATA Technology   | 2        | 2      | 4.35%   |
| WDC                 | 1        | 1      | 2.17%   |
| TO Exter            | 1        | 1      | 2.17%   |
| SPCC                | 1        | 1      | 2.17%   |
| Patriot             | 1        | 1      | 2.17%   |
| OCZ                 | 1        | 1      | 2.17%   |
| NGFF                | 1        | 1      | 2.17%   |
| Micron Technology   | 1        | 1      | 2.17%   |
| Leven               | 1        | 1      | 2.17%   |
| Integral            | 1        | 1      | 2.17%   |
| Corsair             | 1        | 1      | 2.17%   |
| China               | 1        | 1      | 2.17%   |
| BHT                 | 1        | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 41       | 73     | 46.59%  |
| SSD     | 36       | 50     | 40.91%  |
| NVMe    | 10       | 16     | 11.36%  |
| Unknown | 1        | 1      | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 58       | 112    | 77.33%  |
| NVMe | 10       | 15     | 13.33%  |
| SAS  | 7        | 13     | 9.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 40       | 56     | 43.48%  |
| 0.51-1.0   | 28       | 36     | 30.43%  |
| 1.01-2.0   | 11       | 13     | 11.96%  |
| 3.01-4.0   | 7        | 9      | 7.61%   |
| 4.01-10.0  | 4        | 6      | 4.35%   |
| 2.01-3.0   | 2        | 3      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 19       | 31.15%  |
| 1001-2000      | 11       | 18.03%  |
| 501-1000       | 10       | 16.39%  |
| More than 3000 | 9        | 14.75%  |
| 251-500        | 6        | 9.84%   |
| 51-100         | 3        | 4.92%   |
| 21-50          | 2        | 3.28%   |
| 1-20           | 1        | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 18       | 29.51%  |
| 21-50          | 13       | 21.31%  |
| 101-250        | 6        | 9.84%   |
| More than 3000 | 5        | 8.2%    |
| 251-500        | 5        | 8.2%    |
| 51-100         | 5        | 8.2%    |
| 501-1000       | 4        | 6.56%   |
| 1001-2000      | 3        | 4.92%   |
| 2001-3000      | 2        | 3.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 3        | 3      | 20%     |
| WDC WD1600AAJS-08L7A0 160GB           | 1        | 1      | 6.67%   |
| WDC WD10EZEX-22BN5A0 1TB              | 1        | 1      | 6.67%   |
| Toshiba HDWE140 4TB                   | 1        | 1      | 6.67%   |
| Seagate ST3320820AS 320GB             | 1        | 1      | 6.67%   |
| Seagate ST3200822AS 200GB             | 1        | 1      | 6.67%   |
| Seagate ST1000VM002-9ZL162 1TB        | 1        | 1      | 6.67%   |
| Samsung Electronics SSD 960 PRO 512GB | 1        | 1      | 6.67%   |
| Samsung Electronics HD753LJ 752GB     | 1        | 1      | 6.67%   |
| Hitachi HDS5C1010CLA382 1TB           | 1        | 1      | 6.67%   |
| HGST HTS721010A9 1TB                  | 1        | 1      | 6.67%   |
| A-DATA Technology SU650 240GB SSD     | 1        | 1      | 6.67%   |
| A-DATA Technology SP550 240GB SSD     | 1        | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 6      | 40%     |
| WDC                 | 2        | 2      | 13.33%  |
| Samsung Electronics | 2        | 2      | 13.33%  |
| A-DATA Technology   | 2        | 2      | 13.33%  |
| Toshiba             | 1        | 1      | 6.67%   |
| Hitachi             | 1        | 1      | 6.67%   |
| HGST                | 1        | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 6      | 50%     |
| WDC                 | 2        | 2      | 16.67%  |
| Toshiba             | 1        | 1      | 8.33%   |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |
| HGST                | 1        | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 12     | 78.57%  |
| SSD  | 2        | 2      | 14.29%  |
| NVMe | 1        | 1      | 7.14%   |

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
| Works    | 55       | 111    | 71.43%  |
| Malfunc  | 14       | 15     | 18.18%  |
| Detected | 7        | 13     | 9.09%   |
| Failed   | 1        | 1      | 1.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 43       | 51.19%  |
| AMD                      | 14       | 16.67%  |
| Samsung Electronics      | 5        | 5.95%   |
| Marvell Technology Group | 5        | 5.95%   |
| ASMedia Technology       | 5        | 5.95%   |
| Nvidia                   | 3        | 3.57%   |
| Phison Electronics       | 2        | 2.38%   |
| JMicron Technology       | 2        | 2.38%   |
| VIA Technologies         | 1        | 1.19%   |
| Silicon Image            | 1        | 1.19%   |
| SanDisk                  | 1        | 1.19%   |
| Apple                    | 1        | 1.19%   |
| Adaptec                  | 1        | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10       | 9.01%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 9        | 8.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 5.41%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 4.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 3.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 3.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 2.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 2.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 1.8%    |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2        | 1.8%    |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2        | 1.8%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2        | 1.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.8%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2        | 1.8%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 1.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2        | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 1.8%    |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.8%    |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 0.9%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.9%    |
| SanDisk WD Black NVMe SSD                                                      | 1        | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.9%    |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.9%    |
| Phison E12 NVMe Controller                                                     | 1        | 0.9%    |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.9%    |
| Nvidia MCP61 IDE                                                               | 1        | 0.9%    |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                        | 1        | 0.9%    |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.9%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1        | 0.9%    |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 1        | 0.9%    |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 0.9%    |
| JMicron JMB362 SATA Controller                                                 | 1        | 0.9%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1        | 0.9%    |
| Intel SATA Controller [RAID mode]                                              | 1        | 0.9%    |
| Intel NVMe Optane Memory Series                                                | 1        | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1        | 0.9%    |
| Intel C606 chipset Dual 4-Port SATA/SAS Storage Control Unit                   | 1        | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 48       | 57.83%  |
| IDE  | 19       | 22.89%  |
| NVMe | 10       | 12.05%  |
| RAID | 3        | 3.61%   |
| SAS  | 2        | 2.41%   |
| SCSI | 1        | 1.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 44       | 72.13%  |
| AMD    | 17       | 27.87%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz               | 3        | 4.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 3        | 4.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 2        | 3.28%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 2        | 3.28%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 2        | 3.28%   |
| Intel Xeon W-2150B CPU @ 3.00GHz               | 1        | 1.64%   |
| Intel Xeon CPU E5420 @ 2.50GHz                 | 1        | 1.64%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz             | 1        | 1.64%   |
| Intel Pentium D CPU 3.40GHz                    | 1        | 1.64%   |
| Intel Pentium CPU G3220 @ 3.00GHz              | 1        | 1.64%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 1.64%   |
| Intel Pentium 4 CPU 2.80GHz                    | 1        | 1.64%   |
| Intel Core i9-10900K CPU @ 3.70GHz             | 1        | 1.64%   |
| Intel Core i7-9700 CPU @ 3.00GHz               | 1        | 1.64%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 1.64%   |
| Intel Core i7-4770K CPU @ 3.50GHz              | 1        | 1.64%   |
| Intel Core i7-3930K CPU @ 3.20GHz              | 1        | 1.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 1.64%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1        | 1.64%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 1.64%   |
| Intel Core i7 CPU 930 @ 2.80GHz                | 1        | 1.64%   |
| Intel Core i5-9400T CPU @ 1.80GHz              | 1        | 1.64%   |
| Intel Core i5-8600K CPU @ 3.60GHz              | 1        | 1.64%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 1        | 1.64%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1        | 1.64%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 1        | 1.64%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.64%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 1        | 1.64%   |
| Intel Core i3-6100T CPU @ 3.20GHz              | 1        | 1.64%   |
| Intel Core i3-4340 CPU @ 3.60GHz               | 1        | 1.64%   |
| Intel Core i3-4150 CPU @ 3.50GHz               | 1        | 1.64%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 1        | 1.64%   |
| Intel Core i3-3245 CPU @ 3.40GHz               | 1        | 1.64%   |
| Intel Core i3 CPU 540 @ 3.07GHz                | 1        | 1.64%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 1        | 1.64%   |
| Intel Core 2 CPU 6600 @ 2.40GHz                | 1        | 1.64%   |
| Intel Celeron CPU J3455 @ 1.50GHz              | 1        | 1.64%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1        | 1.64%   |
| AMD Ryzen 9 3950X 16-Core Processor            | 1        | 1.64%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 1.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 17       | 27.87%  |
| Intel Core i7          | 10       | 16.39%  |
| Intel Core i3          | 6        | 9.84%   |
| Intel Xeon             | 3        | 4.92%   |
| Intel Pentium 4        | 2        | 3.28%   |
| AMD Ryzen 9            | 2        | 3.28%   |
| AMD Phenom II X4       | 2        | 3.28%   |
| AMD Athlon II X2       | 2        | 3.28%   |
| Intel Pentium D        | 1        | 1.64%   |
| Intel Pentium          | 1        | 1.64%   |
| Intel Core i9          | 1        | 1.64%   |
| Intel Core 2 Duo       | 1        | 1.64%   |
| Intel Core 2           | 1        | 1.64%   |
| Intel Celeron          | 1        | 1.64%   |
| AMD Ryzen Threadripper | 1        | 1.64%   |
| AMD Ryzen 7            | 1        | 1.64%   |
| AMD Ryzen 5            | 1        | 1.64%   |
| AMD Ryzen 3            | 1        | 1.64%   |
| AMD FX                 | 1        | 1.64%   |
| AMD E                  | 1        | 1.64%   |
| AMD Athlon X4          | 1        | 1.64%   |
| AMD Athlon Dual Core   | 1        | 1.64%   |
| AMD Athlon 64 X2       | 1        | 1.64%   |
| AMD A4                 | 1        | 1.64%   |
| AMD A10                | 1        | 1.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 29       | 47.54%  |
| 2      | 16       | 26.23%  |
| 6      | 5        | 8.2%    |
| 8      | 3        | 4.92%   |
| 1      | 3        | 4.92%   |
| 10     | 2        | 3.28%   |
| 32     | 1        | 1.64%   |
| 16     | 1        | 1.64%   |
| 12     | 1        | 1.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 60       | 98.36%  |
| 2      | 1        | 1.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 50.82%  |
| 2      | 30       | 49.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 60       | 98.36%  |
| 32-bit         | 1        | 1.64%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 11       | 18.03%  |
| Unknown    | 7        | 11.48%  |
| 0x306a9    | 5        | 8.2%    |
| 0x206a7    | 5        | 8.2%    |
| 0x906ea    | 3        | 4.92%   |
| 0x506e3    | 3        | 4.92%   |
| 0x010000c8 | 3        | 4.92%   |
| 0xf41      | 2        | 3.28%   |
| 0x206d7    | 2        | 3.28%   |
| 0x10676    | 2        | 3.28%   |
| 0x08701021 | 2        | 3.28%   |
| 0xf65      | 1        | 1.64%   |
| 0xa0655    | 1        | 1.64%   |
| 0x906ed    | 1        | 1.64%   |
| 0x6f6      | 1        | 1.64%   |
| 0x506ca    | 1        | 1.64%   |
| 0x50654    | 1        | 1.64%   |
| 0x20655    | 1        | 1.64%   |
| 0x106a5    | 1        | 1.64%   |
| 0x0a201009 | 1        | 1.64%   |
| 0x08301039 | 1        | 1.64%   |
| 0x08108109 | 1        | 1.64%   |
| 0x08101016 | 1        | 1.64%   |
| 0x06003106 | 1        | 1.64%   |
| 0x06001119 | 1        | 1.64%   |
| 0x06000852 | 1        | 1.64%   |
| 0x010000c7 | 1        | 1.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 11       | 18.03%  |
| SandyBridge | 7        | 11.48%  |
| Skylake     | 6        | 9.84%   |
| KabyLake    | 5        | 8.2%    |
| IvyBridge   | 5        | 8.2%    |
| Zen 2       | 4        | 6.56%   |
| K10         | 4        | 6.56%   |
| NetBurst    | 3        | 4.92%   |
| Piledriver  | 2        | 3.28%   |
| Penryn      | 2        | 3.28%   |
| K8 Hammer   | 2        | 3.28%   |
| Zen+        | 1        | 1.64%   |
| Zen 3       | 1        | 1.64%   |
| Zen         | 1        | 1.64%   |
| Westmere    | 1        | 1.64%   |
| Steamroller | 1        | 1.64%   |
| Nehalem     | 1        | 1.64%   |
| Goldmont    | 1        | 1.64%   |
| Excavator   | 1        | 1.64%   |
| Core        | 1        | 1.64%   |
| CometLake   | 1        | 1.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 32       | 48.48%  |
| Intel  | 21       | 31.82%  |
| AMD    | 13       | 19.7%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 8.96%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 4.48%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 4.48%   |
| Intel HD Graphics 530                                                       | 3        | 4.48%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.99%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 2.99%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 2.99%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 2.99%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 2.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.99%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 2.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.99%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.49%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1        | 1.49%   |
| Nvidia GT216 [GeForce 315]                                                  | 1        | 1.49%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.49%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.49%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.49%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.49%   |
| Nvidia GK208 [GeForce GT 720]                                               | 1        | 1.49%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 1.49%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.49%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.49%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 1.49%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.49%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.49%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.49%   |
| Nvidia C77 [GeForce 8200]                                                   | 1        | 1.49%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 1.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.49%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.49%   |
| Intel HD Graphics 630                                                       | 1        | 1.49%   |
| Intel HD Graphics 500                                                       | 1        | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.49%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.49%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 1.49%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.49%   |
| AMD Vega 10 [Radeon Instinct MI25]                                          | 1        | 1.49%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.49%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 1.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 28       | 45.9%   |
| 1 x Intel      | 17       | 27.87%  |
| 1 x AMD        | 12       | 19.67%  |
| Intel + Nvidia | 2        | 3.28%   |
| 2 x Nvidia     | 1        | 1.64%   |
| AMD + Nvidia   | 1        | 1.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 42       | 68.85%  |
| Proprietary | 19       | 31.15%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 31.15%  |
| 1.01-2.0   | 11       | 18.03%  |
| 0.51-1.0   | 8        | 13.11%  |
| 0.01-0.5   | 7        | 11.48%  |
| 3.01-4.0   | 6        | 9.84%   |
| 8.01-16.0  | 4        | 6.56%   |
| 7.01-8.0   | 2        | 3.28%   |
| 5.01-6.0   | 2        | 3.28%   |
| 2.01-3.0   | 1        | 1.64%   |
| 16.01-24.0 | 1        | 1.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 13.7%   |
| Goldstar             | 9        | 12.33%  |
| Philips              | 7        | 9.59%   |
| Hewlett-Packard      | 7        | 9.59%   |
| Dell                 | 7        | 9.59%   |
| Ancor Communications | 6        | 8.22%   |
| Acer                 | 6        | 8.22%   |
| Eizo                 | 2        | 2.74%   |
| AOC                  | 2        | 2.74%   |
| VIE                  | 1        | 1.37%   |
| Unknown              | 1        | 1.37%   |
| TVT                  | 1        | 1.37%   |
| Targa Visionary      | 1        | 1.37%   |
| Sony                 | 1        | 1.37%   |
| Seiki                | 1        | 1.37%   |
| Onkyo                | 1        | 1.37%   |
| NEC Computers        | 1        | 1.37%   |
| Medion               | 1        | 1.37%   |
| KTC                  | 1        | 1.37%   |
| Iiyama               | 1        | 1.37%   |
| Hannspree            | 1        | 1.37%   |
| Fujitsu Siemens      | 1        | 1.37%   |
| DENON                | 1        | 1.37%   |
| BenQ                 | 1        | 1.37%   |
| ASUSTek Computer     | 1        | 1.37%   |
| Apple                | 1        | 1.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2        | 2.47%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 1.23%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                 | 1        | 1.23%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                        | 1        | 1.23%   |
| Targa Visionary LCD Monitor TARA240 1920x1080 520x300mm 23.6-inch     | 1        | 1.23%   |
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                   | 1        | 1.23%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                   | 1        | 1.23%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1        | 1.23%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch   | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch  | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch  | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1        | 1.23%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch  | 1        | 1.23%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch   | 1        | 1.23%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch   | 1        | 1.23%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1        | 1.23%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 1.23%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch  | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 1        | 1.23%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch             | 1        | 1.23%   |
| Philips 247E4 PHLC0C0 1920x1080 521x293mm 23.5-inch                   | 1        | 1.23%   |
| Philips 227E4LH PHLC0AC 1920x1080 477x268mm 21.5-inch                 | 1        | 1.23%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1        | 1.23%   |
| Philips 201E PHLC033 1600x900 443x249mm 20.0-inch                     | 1        | 1.23%   |
| Philips 190V PHL0847 1280x1024 376x301mm 19.0-inch                    | 1        | 1.23%   |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                    | 1        | 1.23%   |
| Onkyo HT-R494 ONK0F43 3840x2160 1150x650mm 52.0-inch                  | 1        | 1.23%   |
| NEC Computers LCD2180UX NEC662C 1600x1200 430x320mm 21.1-inch         | 1        | 1.23%   |
| Medion MD32119PR MED89C1 1280x1024 376x301mm 19.0-inch                | 1        | 1.23%   |
| KTC H-W2206S-D KTC2203 1680x1050 433x270mm 20.1-inch                  | 1        | 1.23%   |
| Iiyama PL2435M IVM6112 1920x1080 521x293mm 23.5-inch                  | 1        | 1.23%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch           | 1        | 1.23%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 1        | 1.23%   |
| Hewlett-Packard LE2202x HWP2966 1920x1080 476x268mm 21.5-inch         | 1        | 1.23%   |
| Hewlett-Packard L1902 HWP261E 1280x1024 340x270mm 17.1-inch           | 1        | 1.23%   |
| Hewlett-Packard 24y HPN3504 1920x1080 530x300mm 24.0-inch             | 1        | 1.23%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 1        | 1.23%   |
| Hewlett-Packard 22yh HPN3533 1920x1080 477x268mm 21.5-inch            | 1        | 1.23%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                  | 1        | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 29       | 42.03%  |
| 3840x2160 (4K)     | 9        | 13.04%  |
| 1280x1024 (SXGA)   | 9        | 13.04%  |
| 1680x1050 (WSXGA+) | 5        | 7.25%   |
| 1440x900 (WXGA+)   | 3        | 4.35%   |
| 1366x768 (WXGA)    | 3        | 4.35%   |
| 2560x1440 (QHD)    | 2        | 2.9%    |
| 1920x1200 (WUXGA)  | 2        | 2.9%    |
| 1600x900 (HD+)     | 2        | 2.9%    |
| 5760x2160          | 1        | 1.45%   |
| 1600x1200          | 1        | 1.45%   |
| 1400x1050          | 1        | 1.45%   |
| 1360x768           | 1        | 1.45%   |
| Unknown            | 1        | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 12       | 16.67%  |
| 23      | 11       | 15.28%  |
| 24      | 8        | 11.11%  |
| 27      | 7        | 9.72%   |
| 19      | 7        | 9.72%   |
| 22      | 5        | 6.94%   |
| 17      | 5        | 6.94%   |
| 18      | 4        | 5.56%   |
| 20      | 3        | 4.17%   |
| 31      | 2        | 2.78%   |
| 84      | 1        | 1.39%   |
| 65      | 1        | 1.39%   |
| 52      | 1        | 1.39%   |
| 50      | 1        | 1.39%   |
| 43      | 1        | 1.39%   |
| 32      | 1        | 1.39%   |
| 15      | 1        | 1.39%   |
| Unknown | 1        | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 25       | 36.23%  |
| 501-600     | 24       | 34.78%  |
| 301-350     | 6        | 8.7%    |
| 351-400     | 4        | 5.8%    |
| 601-700     | 3        | 4.35%   |
| 1001-1500   | 3        | 4.35%   |
| 701-800     | 1        | 1.45%   |
| 1501-2000   | 1        | 1.45%   |
| 901-1000    | 1        | 1.45%   |
| Unknown     | 1        | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 43       | 65.15%  |
| 16/10   | 11       | 16.67%  |
| 5/4     | 8        | 12.12%  |
| 4/3     | 2        | 3.03%   |
| 3/2     | 1        | 1.52%   |
| Unknown | 1        | 1.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 30       | 42.86%  |
| 151-200        | 12       | 17.14%  |
| 141-150        | 9        | 12.86%  |
| 301-350        | 7        | 10%     |
| More than 1000 | 4        | 5.71%   |
| 351-500        | 3        | 4.29%   |
| 251-300        | 2        | 2.86%   |
| 111-120        | 1        | 1.43%   |
| 501-1000       | 1        | 1.43%   |
| Unknown        | 1        | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 45       | 69.23%  |
| 101-120 | 15       | 23.08%  |
| 121-160 | 3        | 4.62%   |
| 161-240 | 1        | 1.54%   |
| Unknown | 1        | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 63.93%  |
| 2     | 22       | 36.07%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 34       | 36.96%  |
| Intel                           | 28       | 30.43%  |
| Qualcomm Atheros                | 8        | 8.7%    |
| Broadcom                        | 5        | 5.43%   |
| TP-Link                         | 3        | 3.26%   |
| Nvidia                          | 3        | 3.26%   |
| Broadcom Limited                | 2        | 2.17%   |
| Aquantia                        | 2        | 2.17%   |
| ZyDAS                           | 1        | 1.09%   |
| Wacom                           | 1        | 1.09%   |
| Ralink Technology               | 1        | 1.09%   |
| Qualcomm Atheros Communications | 1        | 1.09%   |
| NetGear                         | 1        | 1.09%   |
| Microsoft                       | 1        | 1.09%   |
| ASIX Electronics                | 1        | 1.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 27.27%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 7.07%   |
| Intel I211 Gigabit Network Connection                             | 4        | 4.04%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 4.04%   |
| Intel Wireless-AC 9260                                            | 3        | 3.03%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 2.02%   |
| Nvidia MCP77 Ethernet                                             | 2        | 2.02%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 2.02%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.02%   |
| ZyDAS ZD1211B 802.11g                                             | 1        | 1.01%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                          | 1        | 1.01%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 1.01%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 1.01%   |
| TP-Link 802.11ac NIC                                              | 1        | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.01%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter           | 1        | 1.01%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 1.01%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.01%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 1        | 1.01%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.01%   |
| Realtek 802.11ac NIC                                              | 1        | 1.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 1.01%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.01%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 1.01%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 1.01%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 1.01%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.01%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 1.01%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.01%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1        | 1.01%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 1.01%   |
| Intel Wireless 8265 / 8275                                        | 1        | 1.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 1.01%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.01%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.01%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.01%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 24.14%  |
| Qualcomm Atheros                | 6        | 20.69%  |
| Realtek Semiconductor           | 5        | 17.24%  |
| TP-Link                         | 3        | 10.34%  |
| Broadcom                        | 2        | 6.9%    |
| ZyDAS                           | 1        | 3.45%   |
| Wacom                           | 1        | 3.45%   |
| Ralink Technology               | 1        | 3.45%   |
| Qualcomm Atheros Communications | 1        | 3.45%   |
| NetGear                         | 1        | 3.45%   |
| Microsoft                       | 1        | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Wireless-AC 9260                                      | 3        | 10.34%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter            | 2        | 6.9%    |
| Intel Cannon Lake PCH CNVi WiFi                             | 2        | 6.9%    |
| ZyDAS ZD1211B 802.11g                                       | 1        | 3.45%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                    | 1        | 3.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]  | 1        | 3.45%   |
| TP-Link 802.11ac WLAN Adapter                               | 1        | 3.45%   |
| TP-Link 802.11ac NIC                                        | 1        | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 1        | 3.45%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter     | 1        | 3.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                     | 1        | 3.45%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller   | 1        | 3.45%   |
| Realtek 802.11ac NIC                                        | 1        | 3.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                       | 1        | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 1        | 3.45%   |
| Qualcomm Atheros AR9271 802.11n                             | 1        | 3.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter            | 1        | 3.45%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter            | 1        | 3.45%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter  | 1        | 3.45%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU] | 1        | 3.45%   |
| Microsoft Xbox 360 Wireless Adapter                         | 1        | 3.45%   |
| Intel Wireless 8265 / 8275                                  | 1        | 3.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                      | 1        | 3.45%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter          | 1        | 3.45%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter          | 1        | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 30       | 43.48%  |
| Intel                 | 26       | 37.68%  |
| Nvidia                | 3        | 4.35%   |
| Broadcom              | 3        | 4.35%   |
| Qualcomm Atheros      | 2        | 2.9%    |
| Broadcom Limited      | 2        | 2.9%    |
| Aquantia              | 2        | 2.9%    |
| ASIX Electronics      | 1        | 1.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 38.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 10%     |
| Intel I211 Gigabit Network Connection                             | 4        | 5.71%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 5.71%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 4.29%   |
| Nvidia MCP77 Ethernet                                             | 2        | 2.86%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.86%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.86%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.43%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.43%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.43%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.43%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.43%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.43%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.43%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.43%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 1.43%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 1.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.43%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.43%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 1.43%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 1.43%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 1.43%   |
| ASIX AX88772B                                                     | 1        | 1.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 61       | 68.54%  |
| WiFi     | 28       | 31.46%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 54       | 80.6%   |
| WiFi     | 13       | 19.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 62.3%   |
| 2     | 21       | 34.43%  |
| 3     | 2        | 3.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 54       | 88.52%  |
| Yes  | 7        | 11.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 36.84%  |
| Cambridge Silicon Radio         | 6        | 31.58%  |
| ASUSTek Computer                | 3        | 15.79%  |
| Qualcomm Atheros Communications | 2        | 10.53%  |
| Realtek Semiconductor           | 1        | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 31.58%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 15.79%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 10.53%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 10.53%  |
| Realtek Bluetooth Radio                             | 1        | 5.26%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 5.26%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 5.26%   |
| Intel Bluetooth wireless interface                  | 1        | 5.26%   |
| Intel AX210 Bluetooth                               | 1        | 5.26%   |
| ASUS BCM20702A0                                     | 1        | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 40       | 33.61%  |
| Nvidia                               | 27       | 22.69%  |
| AMD                                  | 18       | 15.13%  |
| Texas Instruments                    | 4        | 3.36%   |
| C-Media Electronics                  | 4        | 3.36%   |
| Yamaha                               | 3        | 2.52%   |
| Logitech                             | 2        | 1.68%   |
| ZOOM                                 | 1        | 0.84%   |
| Xilinx                               | 1        | 0.84%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.84%   |
| Textech International                | 1        | 0.84%   |
| Studiologic                          | 1        | 0.84%   |
| SteelSeries ApS                      | 1        | 0.84%   |
| Samson Technologies                  | 1        | 0.84%   |
| QinHeng Electronics                  | 1        | 0.84%   |
| PreSonus Audio Electronics           | 1        | 0.84%   |
| Plantronics                          | 1        | 0.84%   |
| Medeli Electronics                   | 1        | 0.84%   |
| Mark of the Unicorn                  | 1        | 0.84%   |
| M-Audio                              | 1        | 0.84%   |
| KTMicro                              | 1        | 0.84%   |
| JMTek                                | 1        | 0.84%   |
| Focusrite-Novation                   | 1        | 0.84%   |
| Ensoniq                              | 1        | 0.84%   |
| BEHRINGER International              | 1        | 0.84%   |
| ASUSTek Computer                     | 1        | 0.84%   |
| Apple                                | 1        | 0.84%   |
| Alesis                               | 1        | 0.84%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 11       | 8.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 7        | 5.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6        | 4.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4        | 2.96%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 2.96%   |
| AMD Starship/Matisse HD Audio Controller                                          | 4        | 2.96%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3        | 2.22%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 2.22%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 2.22%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 2.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 2.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 2.22%   |
| AMD FCH Azalia Controller                                                         | 3        | 2.22%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 1.48%   |
| Nvidia High Definition Audio Controller                                           | 2        | 1.48%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1.48%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 1.48%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 2        | 1.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.48%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 1.48%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 1.48%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.48%   |
| ZOOM U-22                                                                         | 1        | 0.74%   |
| Yamaha YMF-744B [DS-1S Audio Controller]                                          | 1        | 0.74%   |
| Yamaha MG-XU                                                                      | 1        | 0.74%   |
| Yamaha AG06/AG03                                                                  | 1        | 0.74%   |
| Xilinx RME Hammerfall DSP                                                         | 1        | 0.74%   |
| Thesycon Systemsoftware & Consulting USB HiRes Audio                              | 1        | 0.74%   |
| Textech International MIDI Interface cable                                        | 1        | 0.74%   |
| Texas Instruments PCM2900 Audio Codec                                             | 1        | 0.74%   |
| Studiologic SL STUDIO                                                             | 1        | 0.74%   |
| SteelSeries ApS Arctis Pro Wireless                                               | 1        | 0.74%   |
| Samson Technologies Meteor condenser microphone                                   | 1        | 0.74%   |
| QinHeng Electronics CH345 MIDI adapter                                            | 1        | 0.74%   |
| PreSonus Audio Electronics Studio 24c                                             | 1        | 0.74%   |
| Plantronics DA40                                                                  | 1        | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.74%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 12       | 15.58%  |
| Samsung Electronics | 11       | 14.29%  |
| Kingston            | 11       | 14.29%  |
| Unknown             | 9        | 11.69%  |
| Corsair             | 8        | 10.39%  |
| Crucial             | 7        | 9.09%   |
| Micron Technology   | 5        | 6.49%   |
| G.Skill             | 4        | 5.19%   |
| Patriot             | 2        | 2.6%    |
| Smart               | 1        | 1.3%    |
| S                   | 1        | 1.3%    |
| PNY                 | 1        | 1.3%    |
| Nanya Technology    | 1        | 1.3%    |
| M                   | 1        | 1.3%    |
| HBS                 | 1        | 1.3%    |
| Aeneon              | 1        | 1.3%    |
| 0194808980CE        | 1        | 1.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1600MT/s                     | 2        | 2.27%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s         | 2        | 2.27%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s         | 2        | 2.27%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s          | 2        | 2.27%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 2        | 2.27%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s    | 2        | 2.27%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1        | 1.14%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                   | 1        | 1.14%   |
| Unknown RAM Module 512MB DIMM DDR                           | 1        | 1.14%   |
| Unknown RAM Module 256MB DIMM DDR                           | 1        | 1.14%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1        | 1.14%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1        | 1.14%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1        | 1.14%   |
| Unknown RAM Module 1024MB DIMM DDR                          | 1        | 1.14%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1        | 1.14%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s                 | 1        | 1.14%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s          | 1        | 1.14%   |
| SK hynix RAM TMT41GU6BFR8C-PBSC 8192MB DIMM DDR3 1600MT/s   | 1        | 1.14%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2666MT/s               | 1        | 1.14%   |
| SK hynix RAM HYMP564U64BP8-C4 512MB DIMM DDR 533MT/s        | 1        | 1.14%   |
| SK hynix RAM HYMP125F72CP8N3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 1.14%   |
| SK hynix RAM HYMP125F72CP8D3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 1.14%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s        | 1        | 1.14%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1        | 1.14%   |
| SK hynix RAM HMT351U7CFR8C-PB 4096MB DIMM DDR3 1600MT/s     | 1        | 1.14%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s        | 1        | 1.14%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s     | 1        | 1.14%   |
| SK hynix RAM HMT325U7CFR8C-PB 2GB DIMM DDR3 1600MT/s        | 1        | 1.14%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s        | 1        | 1.14%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 1.14%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 1.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1        | 1.14%   |
| Samsung RAM Module 2048MB DIMM DDR3 1066MT/s                | 1        | 1.14%   |
| Samsung RAM M395T5750GZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1        | 1.14%   |
| Samsung RAM M395T5160QZ4-CE66 4GB FB-DIMM DDR2 667MT/s      | 1        | 1.14%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s      | 1        | 1.14%   |
| Samsung RAM M378B5173EB0-CK0 4096MB DIMM DDR3 1600MT/s      | 1        | 1.14%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s         | 1        | 1.14%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s      | 1        | 1.14%   |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s         | 1        | 1.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 31       | 50%     |
| DDR4    | 18       | 29.03%  |
| DDR2    | 5        | 8.06%   |
| Unknown | 4        | 6.45%   |
| DDR     | 3        | 4.84%   |
| SDRAM   | 1        | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 56       | 91.8%   |
| SODIMM  | 4        | 6.56%   |
| FB-DIMM | 1        | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 19       | 27.94%  |
| 4096  | 18       | 26.47%  |
| 2048  | 11       | 16.18%  |
| 16384 | 7        | 10.29%  |
| 1024  | 6        | 8.82%   |
| 32768 | 4        | 5.88%   |
| 512   | 2        | 2.94%   |
| 256   | 1        | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 20       | 28.99%  |
| 1333    | 8        | 11.59%  |
| 3200    | 4        | 5.8%    |
| 2133    | 4        | 5.8%    |
| 2667    | 3        | 4.35%   |
| 1866    | 3        | 4.35%   |
| 1066    | 3        | 4.35%   |
| 800     | 3        | 4.35%   |
| 667     | 3        | 4.35%   |
| 3600    | 2        | 2.9%    |
| 1867    | 2        | 2.9%    |
| 1800    | 2        | 2.9%    |
| 533     | 2        | 2.9%    |
| Unknown | 2        | 2.9%    |
| 3500    | 1        | 1.45%   |
| 3466    | 1        | 1.45%   |
| 3266    | 1        | 1.45%   |
| 2933    | 1        | 1.45%   |
| 2800    | 1        | 1.45%   |
| 2666    | 1        | 1.45%   |
| 2472    | 1        | 1.45%   |
| 2400    | 1        | 1.45%   |

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
| Logitech                      | 5        | 33.33%  |
| Samsung Electronics           | 2        | 13.33%  |
| Microsoft                     | 2        | 13.33%  |
| Microdia                      | 2        | 13.33%  |
| ViewSonic                     | 1        | 6.67%   |
| Sweex                         | 1        | 6.67%   |
| Sunplus Innovation Technology | 1        | 6.67%   |
| Philips (or NXP)              | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 2        | 13.33%  |
| ViewSonic PC Camera                     | 1        | 6.67%   |
| Sweex WC060 Series HD Webcam            | 1        | 6.67%   |
| Sunplus HD 720P webcam                  | 1        | 6.67%   |
| Philips (or NXP) Webcam SPC530NC        | 1        | 6.67%   |
| Microsoft LifeCam VX-5000               | 1        | 6.67%   |
| Microsoft LifeCam Cinema                | 1        | 6.67%   |
| Microdia USB 2.0 Camera                 | 1        | 6.67%   |
| Microdia MSI Starcam Racer              | 1        | 6.67%   |
| Logitech Webcam C270                    | 1        | 6.67%   |
| Logitech QuickCam Communicate MP/S5500  | 1        | 6.67%   |
| Logitech Portable Webcam C905           | 1        | 6.67%   |
| Logitech HD Webcam C910                 | 1        | 6.67%   |
| Logitech HD Pro Webcam C920             | 1        | 6.67%   |

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
| 0     | 55       | 90.16%  |
| 1     | 6        | 9.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 3        | 50%     |
| Sound                    | 2        | 33.33%  |
| Communication controller | 1        | 16.67%  |

