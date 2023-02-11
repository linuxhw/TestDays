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

Total: 79

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | B450M Pro4                  | [c63c663181](https://linux-hardware.org/?probe=c63c663181) | Jan 30, 2023 |
| HP            | 304Ah                       | [a41a25807f](https://linux-hardware.org/?probe=a41a25807f) | Jan 25, 2023 |
| HP            | 1497                        | [5f7e021023](https://linux-hardware.org/?probe=5f7e021023) | Jan 22, 2023 |
| Gigabyte      | A520M H                     | [db3b391bd0](https://linux-hardware.org/?probe=db3b391bd0) | Jan 20, 2023 |
| ASUSTek       | M4A785-M                    | [f36c085389](https://linux-hardware.org/?probe=f36c085389) | Dec 25, 2022 |
| Gigabyte      | B550M DS3H                  | [ffe85423d8](https://linux-hardware.org/?probe=ffe85423d8) | Dec 15, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | [9d689be2ab](https://linux-hardware.org/?probe=9d689be2ab) | Dec 11, 2022 |
| System76      | Thelio thelio-r1            | [a888eb38b3](https://linux-hardware.org/?probe=a888eb38b3) | Dec 01, 2022 |
| ASUSTek       | PRIME X570-PRO              | [78defd6c12](https://linux-hardware.org/?probe=78defd6c12) | Nov 21, 2022 |
| Dell          | 0XPDFK A01                  | [b76898d624](https://linux-hardware.org/?probe=b76898d624) | Nov 21, 2022 |
| Dell          | 0XPDFK A01                  | [5147db88ea](https://linux-hardware.org/?probe=5147db88ea) | Nov 14, 2022 |
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
| Ubuntu Studio 20.04 | 39       | 55.71%  |
| Ubuntu Studio 22.04 | 15       | 21.43%  |
| Ubuntu Studio 20.10 | 9        | 12.86%  |
| Ubuntu Studio 21.10 | 3        | 4.29%   |
| Ubuntu Studio 21.04 | 2        | 2.86%   |
| Ubuntu Studio 22.10 | 1        | 1.43%   |
| Ubuntu Studio 16.04 | 1        | 1.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu Studio | 70       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.15.0-58-lowlatency | 3        | 4.29%   |
| 5.11.0-44-lowlatency | 3        | 4.29%   |
| 5.8.0-48-lowlatency  | 2        | 2.86%   |
| 5.8.0-44-lowlatency  | 2        | 2.86%   |
| 5.8.0-25-lowlatency  | 2        | 2.86%   |
| 5.4.0-58-lowlatency  | 2        | 2.86%   |
| 5.4.0-56-lowlatency  | 2        | 2.86%   |
| 5.4.0-42-lowlatency  | 2        | 2.86%   |
| 5.4.0-26-lowlatency  | 2        | 2.86%   |
| 5.15.0-56-lowlatency | 2        | 2.86%   |
| 5.15.0-53-lowlatency | 2        | 2.86%   |
| 5.15.0-52-lowlatency | 2        | 2.86%   |
| 5.15.0-46-lowlatency | 2        | 2.86%   |
| 5.13.0-28-lowlatency | 2        | 2.86%   |
| 5.8.0-50-lowlatency  | 1        | 1.43%   |
| 5.8.0-45-lowlatency  | 1        | 1.43%   |
| 5.8.0-36-lowlatency  | 1        | 1.43%   |
| 5.8.0-34-lowlatency  | 1        | 1.43%   |
| 5.8.0-33-lowlatency  | 1        | 1.43%   |
| 5.8.0-29-lowlatency  | 1        | 1.43%   |
| 5.4.0-99-lowlatency  | 1        | 1.43%   |
| 5.4.0-72-lowlatency  | 1        | 1.43%   |
| 5.4.0-71-lowlatency  | 1        | 1.43%   |
| 5.4.0-70-lowlatency  | 1        | 1.43%   |
| 5.4.0-65-lowlatency  | 1        | 1.43%   |
| 5.4.0-65-generic     | 1        | 1.43%   |
| 5.4.0-64-lowlatency  | 1        | 1.43%   |
| 5.4.0-62-lowlatency  | 1        | 1.43%   |
| 5.4.0-60-lowlatency  | 1        | 1.43%   |
| 5.4.0-53-lowlatency  | 1        | 1.43%   |
| 5.4.0-52-lowlatency  | 1        | 1.43%   |
| 5.4.0-51-lowlatency  | 1        | 1.43%   |
| 5.4.0-48-lowlatency  | 1        | 1.43%   |
| 5.4.0-47-lowlatency  | 1        | 1.43%   |
| 5.4.0-39-lowlatency  | 1        | 1.43%   |
| 5.4.0-33-lowlatency  | 1        | 1.43%   |
| 5.4.0-131-lowlatency | 1        | 1.43%   |
| 5.4.0-125-lowlatency | 1        | 1.43%   |
| 5.4.0-122-lowlatency | 1        | 1.43%   |
| 5.4.0-122-generic    | 1        | 1.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 30       | 42.86%  |
| 5.15.0  | 16       | 22.86%  |
| 5.8.0   | 12       | 17.14%  |
| 5.11.0  | 6        | 8.57%   |
| 5.13.0  | 3        | 4.29%   |
| 5.19.0  | 1        | 1.43%   |
| 5.15.6  | 1        | 1.43%   |
| 4.4.0   | 1        | 1.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 30       | 42.86%  |
| 5.15    | 17       | 24.29%  |
| 5.8     | 12       | 17.14%  |
| 5.11    | 6        | 8.57%   |
| 5.13    | 3        | 4.29%   |
| 5.19    | 1        | 1.43%   |
| 4.4     | 1        | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 69       | 98.57%  |
| i686   | 1        | 1.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| XFCE            | 35       | 50%     |
| KDE5            | 24       | 34.29%  |
| GNOME           | 5        | 7.14%   |
| MATE            | 2        | 2.86%   |
| LXQt            | 1        | 1.43%   |
| KDE             | 1        | 1.43%   |
| GNOME Flashback | 1        | 1.43%   |
| Cinnamon        | 1        | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 66       | 94.29%  |
| Wayland | 2        | 2.86%   |
| Tty     | 2        | 2.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 25       | 35.71%  |
| SDDM    | 24       | 34.29%  |
| LightDM | 14       | 20%     |
| GDM     | 6        | 8.57%   |
| GDM3    | 1        | 1.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 27       | 38.57%  |
| de_DE      | 8        | 11.43%  |
| fr_FR      | 7        | 10%     |
| pt_BR      | 4        | 5.71%   |
| en_GB      | 4        | 5.71%   |
| it_IT      | 3        | 4.29%   |
| en_AU      | 2        | 2.86%   |
| ru_RU      | 1        | 1.43%   |
| nl_NL      | 1        | 1.43%   |
| nl_BE      | 1        | 1.43%   |
| nb_NO      | 1        | 1.43%   |
| fr_FR.UTF8 | 1        | 1.43%   |
| fr_CH      | 1        | 1.43%   |
| fr_BE      | 1        | 1.43%   |
| es_GT      | 1        | 1.43%   |
| es_AR      | 1        | 1.43%   |
| en_DE      | 1        | 1.43%   |
| en_CA      | 1        | 1.43%   |
| de_AT      | 1        | 1.43%   |
| ca_ES      | 1        | 1.43%   |
| ca_AD      | 1        | 1.43%   |
| C          | 1        | 1.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 42       | 60%     |
| EFI  | 28       | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 68       | 97.14%  |
| Xfs  | 1        | 1.43%   |
| Ext2 | 1        | 1.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 35       | 50%     |
| GPT  | 35       | 50%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 75.71%  |
| Yes       | 17       | 24.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 57.14%  |
| Yes       | 30       | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 20       | 28.57%  |
| Gigabyte Technology | 11       | 15.71%  |
| Dell                | 10       | 14.29%  |
| Hewlett-Packard     | 9        | 12.86%  |
| Fujitsu             | 3        | 4.29%   |
| ASRock              | 3        | 4.29%   |
| MSI                 | 2        | 2.86%   |
| System76            | 1        | 1.43%   |
| Pegatron            | 1        | 1.43%   |
| Packard Bell        | 1        | 1.43%   |
| Medion              | 1        | 1.43%   |
| Lenovo              | 1        | 1.43%   |
| Intel               | 1        | 1.43%   |
| IBM                 | 1        | 1.43%   |
| Foxconn             | 1        | 1.43%   |
| AZW                 | 1        | 1.43%   |
| Apple               | 1        | 1.43%   |
| Acidanthera         | 1        | 1.43%   |
| Acer                | 1        | 1.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 4        | 5.71%   |
| Dell OptiPlex 790                  | 2        | 2.86%   |
| ASUS PRIME X570-PRO                | 2        | 2.86%   |
| System76 Thelio                    | 1        | 1.43%   |
| Pegatron FL368AA-UUZ SR5612CH      | 1        | 1.43%   |
| Packard Bell IMEDIA S3220          | 1        | 1.43%   |
| MSI MS-7A57                        | 1        | 1.43%   |
| MSI MS-7752                        | 1        | 1.43%   |
| Medion MD34207/C746                | 1        | 1.43%   |
| Lenovo ThinkCentre M93p 10A8S45S00 | 1        | 1.43%   |
| Intel DQ965GF HD/FP Audio          | 1        | 1.43%   |
| IBM 8188PPV                        | 1        | 1.43%   |
| HP Z620 Workstation                | 1        | 1.43%   |
| HP ProDesk 600 G1 SFF              | 1        | 1.43%   |
| HP Compaq Pro 6305 SFF             | 1        | 1.43%   |
| HP Compaq Elite 8300 CMT           | 1        | 1.43%   |
| HP Compaq dc7600 Small Form Factor | 1        | 1.43%   |
| HP Compaq 8200 Elite SFF PC        | 1        | 1.43%   |
| HP Compaq 8100 Elite SFF PC        | 1        | 1.43%   |
| HP Compaq 6200 Pro MT PC           | 1        | 1.43%   |
| HP Compaq 6005 Pro MT PC           | 1        | 1.43%   |
| Gigabyte X79S-UP5                  | 1        | 1.43%   |
| Gigabyte X570 AORUS ELITE WIFI     | 1        | 1.43%   |
| Gigabyte H170-HD3-CF               | 1        | 1.43%   |
| Gigabyte GA-MA770-DS3              | 1        | 1.43%   |
| Gigabyte F2A78M-HD2                | 1        | 1.43%   |
| Gigabyte B550M DS3H                | 1        | 1.43%   |
| Gigabyte B450M S2H                 | 1        | 1.43%   |
| Gigabyte B450 I AORUS PRO WIFI     | 1        | 1.43%   |
| Gigabyte B150M-D2V DDR3-CF         | 1        | 1.43%   |
| Gigabyte A520M H                   | 1        | 1.43%   |
| Gigabyte A320M-S2H                 | 1        | 1.43%   |
| Fujitsu ESPRIMO P420               | 1        | 1.43%   |
| Fujitsu ESPRIMO G558               | 1        | 1.43%   |
| Fujitsu ESPRIMO E720               | 1        | 1.43%   |
| Foxconn Pro3500 Series             | 1        | 1.43%   |
| Dell Precision WorkStation T5400   | 1        | 1.43%   |
| Dell OptiPlex GX620                | 1        | 1.43%   |
| Dell OptiPlex 7050                 | 1        | 1.43%   |
| Dell OptiPlex 7020                 | 1        | 1.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 8        | 11.43%  |
| HP Compaq             | 7        | 10%     |
| ASUS All              | 4        | 5.71%   |
| Fujitsu ESPRIMO       | 3        | 4.29%   |
| ASUS ROG              | 3        | 4.29%   |
| ASUS TUF              | 2        | 2.86%   |
| ASUS PRIME            | 2        | 2.86%   |
| ASUS P8P67            | 2        | 2.86%   |
| System76 Thelio       | 1        | 1.43%   |
| Pegatron FL368AA-UUZ  | 1        | 1.43%   |
| Packard Bell IMEDIA   | 1        | 1.43%   |
| MSI MS-7A57           | 1        | 1.43%   |
| MSI MS-7752           | 1        | 1.43%   |
| Medion MD34207        | 1        | 1.43%   |
| Lenovo ThinkCentre    | 1        | 1.43%   |
| Intel DQ965GF         | 1        | 1.43%   |
| IBM 8188PPV           | 1        | 1.43%   |
| HP Z620               | 1        | 1.43%   |
| HP ProDesk            | 1        | 1.43%   |
| Gigabyte X79S-UP5     | 1        | 1.43%   |
| Gigabyte X570         | 1        | 1.43%   |
| Gigabyte H170-HD3-CF  | 1        | 1.43%   |
| Gigabyte GA-MA770-DS3 | 1        | 1.43%   |
| Gigabyte F2A78M-HD2   | 1        | 1.43%   |
| Gigabyte B550M        | 1        | 1.43%   |
| Gigabyte B450M        | 1        | 1.43%   |
| Gigabyte B450         | 1        | 1.43%   |
| Gigabyte B150M-D2V    | 1        | 1.43%   |
| Gigabyte A520M        | 1        | 1.43%   |
| Gigabyte A320M-S2H    | 1        | 1.43%   |
| Foxconn Pro3500       | 1        | 1.43%   |
| Dell Precision        | 1        | 1.43%   |
| Dell Inspiron         | 1        | 1.43%   |
| AZW GK35              | 1        | 1.43%   |
| ASUS P6T              | 1        | 1.43%   |
| ASUS P5QC             | 1        | 1.43%   |
| ASUS M5A78L-M         | 1        | 1.43%   |
| ASUS M4A88TD-M        | 1        | 1.43%   |
| ASUS M4A785-M         | 1        | 1.43%   |
| ASUS H110M-A          | 1        | 1.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 9        | 12.86%  |
| 2018 | 7        | 10%     |
| 2019 | 6        | 8.57%   |
| 2014 | 6        | 8.57%   |
| 2011 | 6        | 8.57%   |
| 2020 | 5        | 7.14%   |
| 2017 | 4        | 5.71%   |
| 2012 | 4        | 5.71%   |
| 2010 | 4        | 5.71%   |
| 2009 | 4        | 5.71%   |
| 2015 | 3        | 4.29%   |
| 2008 | 3        | 4.29%   |
| 2005 | 3        | 4.29%   |
| 2021 | 2        | 2.86%   |
| 2016 | 2        | 2.86%   |
| 2007 | 2        | 2.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 70       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 69       | 98.57%  |
| Enabled  | 1        | 1.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 70       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 19       | 27.14%  |
| 8.01-16.0   | 14       | 20%     |
| 4.01-8.0    | 11       | 15.71%  |
| 32.01-64.0  | 8        | 11.43%  |
| 3.01-4.0    | 7        | 10%     |
| 64.01-256.0 | 6        | 8.57%   |
| 1.01-2.0    | 3        | 4.29%   |
| 24.01-32.0  | 1        | 1.43%   |
| 2.01-3.0    | 1        | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 25       | 35.71%  |
| 4.01-8.0   | 13       | 18.57%  |
| 2.01-3.0   | 13       | 18.57%  |
| 8.01-16.0  | 8        | 11.43%  |
| 3.01-4.0   | 7        | 10%     |
| 0.51-1.0   | 3        | 4.29%   |
| 24.01-32.0 | 1        | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 38.57%  |
| 1      | 27       | 38.57%  |
| 3      | 7        | 10%     |
| 7      | 2        | 2.86%   |
| 5      | 2        | 2.86%   |
| 4      | 2        | 2.86%   |
| 16     | 1        | 1.43%   |
| 11     | 1        | 1.43%   |
| 10     | 1        | 1.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 45       | 64.29%  |
| No        | 25       | 35.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 70       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 55.71%  |
| Yes       | 31       | 44.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 72.86%  |
| Yes       | 19       | 27.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 16       | 22.86%  |
| Germany                | 10       | 14.29%  |
| France                 | 10       | 14.29%  |
| Italy                  | 6        | 8.57%   |
| Brazil                 | 5        | 7.14%   |
| Belgium                | 3        | 4.29%   |
| Austria                | 3        | 4.29%   |
| UK                     | 2        | 2.86%   |
| Spain                  | 2        | 2.86%   |
| Australia              | 2        | 2.86%   |
| Switzerland            | 1        | 1.43%   |
| Sweden                 | 1        | 1.43%   |
| Russia                 | 1        | 1.43%   |
| Romania                | 1        | 1.43%   |
| Norway                 | 1        | 1.43%   |
| Netherlands            | 1        | 1.43%   |
| Mexico                 | 1        | 1.43%   |
| Kenya                  | 1        | 1.43%   |
| Guatemala              | 1        | 1.43%   |
| Bosnia and Herzegovina | 1        | 1.43%   |
| Argentina              | 1        | 1.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Paris                   | 3        | 4.29%   |
| Houston                 | 2        | 2.86%   |
| Zanesville              | 1        | 1.43%   |
| Villefontaine           | 1        | 1.43%   |
| Vienna                  | 1        | 1.43%   |
| Turin                   | 1        | 1.43%   |
| Tilburg                 | 1        | 1.43%   |
| Stuttgart               | 1        | 1.43%   |
| Stockholm               | 1        | 1.43%   |
| Sherman Oaks            | 1        | 1.43%   |
| Sarajevo                | 1        | 1.43%   |
| Sao Paulo               | 1        | 1.43%   |
| Santa Barbara d'Oeste   | 1        | 1.43%   |
| San Secondo di Pinerolo | 1        | 1.43%   |
| Saint-Ouen-l'Aumone     | 1        | 1.43%   |
| Rio Grande da Serra     | 1        | 1.43%   |
| Rennes                  | 1        | 1.43%   |
| Philadelphia            | 1        | 1.43%   |
| Perth                   | 1        | 1.43%   |
| Palermo                 | 1        | 1.43%   |
| Oslo                    | 1        | 1.43%   |
| Olympia                 | 1        | 1.43%   |
| Oldenburg               | 1        | 1.43%   |
| Naumburg                | 1        | 1.43%   |
| Namur                   | 1        | 1.43%   |
| Nairobi                 | 1        | 1.43%   |
| Münster                | 1        | 1.43%   |
| Munich                  | 1        | 1.43%   |
| Modesto                 | 1        | 1.43%   |
| Miami                   | 1        | 1.43%   |
| Mérida                 | 1        | 1.43%   |
| Merced                  | 1        | 1.43%   |
| Mediglia                | 1        | 1.43%   |
| Maule                   | 1        | 1.43%   |
| Manchester              | 1        | 1.43%   |
| Maidenhead              | 1        | 1.43%   |
| Lyon                    | 1        | 1.43%   |
| Lomas de Zamora         | 1        | 1.43%   |
| Linz                    | 1        | 1.43%   |
| Limbach-Oberfrohna      | 1        | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 23       | 30     | 17.42%  |
| Seagate               | 23       | 43     | 17.42%  |
| Samsung Electronics   | 21       | 29     | 15.91%  |
| SanDisk               | 8        | 9      | 6.06%   |
| Toshiba               | 7        | 8      | 5.3%    |
| Hitachi               | 6        | 6      | 4.55%   |
| Crucial               | 6        | 6      | 4.55%   |
| Kingston              | 4        | 4      | 3.03%   |
| HGST                  | 4        | 5      | 3.03%   |
| Intenso               | 3        | 3      | 2.27%   |
| Intel                 | 2        | 2      | 1.52%   |
| Corsair               | 2        | 3      | 1.52%   |
| ASMT                  | 2        | 2      | 1.52%   |
| A-DATA Technology     | 2        | 2      | 1.52%   |
| USB 3.0               | 1        | 2      | 0.76%   |
| TO Exter              | 1        | 1      | 0.76%   |
| Team                  | 1        | 1      | 0.76%   |
| SPCC                  | 1        | 1      | 0.76%   |
| Realtek Semiconductor | 1        | 1      | 0.76%   |
| Phison Electronics    | 1        | 1      | 0.76%   |
| Phison                | 1        | 1      | 0.76%   |
| Patriot               | 1        | 1      | 0.76%   |
| OCZ                   | 1        | 1      | 0.76%   |
| NGFF                  | 1        | 1      | 0.76%   |
| Micron Technology     | 1        | 1      | 0.76%   |
| Maxtor                | 1        | 1      | 0.76%   |
| Leven                 | 1        | 1      | 0.76%   |
| JMicron Technology    | 1        | 1      | 0.76%   |
| Integral              | 1        | 1      | 0.76%   |
| Fujitsu               | 1        | 1      | 0.76%   |
| China                 | 1        | 1      | 0.76%   |
| BHT                   | 1        | 1      | 0.76%   |
| Apple                 | 1        | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 4        | 2.6%    |
| Seagate ST2000DM001-1ER164 2TB  | 3        | 1.95%   |
| Toshiba HDWD130 3TB             | 2        | 1.3%    |
| Seagate ST5000LM000-2AN170 5TB  | 2        | 1.3%    |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 1.3%    |
| Seagate Expansion 240GB         | 2        | 1.3%    |
| SanDisk SDSSDA240G 240GB        | 2        | 1.3%    |
| Samsung SSD 970 EVO Plus 500GB  | 2        | 1.3%    |
| Samsung SSD 870 EVO 1TB         | 2        | 1.3%    |
| Samsung SSD 860 EVO 1TB         | 2        | 1.3%    |
| Samsung SSD 850 EVO 500GB       | 2        | 1.3%    |
| Samsung HD753LJ 752GB           | 2        | 1.3%    |
| Crucial CT500MX500SSD1 500GB    | 2        | 1.3%    |
| Crucial CT1000MX500SSD1 1TB     | 2        | 1.3%    |
| WDC WDS512G1X0C-00ENX0 512GB    | 1        | 0.65%   |
| WDC WDS200T2B0A-00SM50 2TB SSD  | 1        | 0.65%   |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 0.65%   |
| WDC WD5000BPKT-60PK4T0 500GB    | 1        | 0.65%   |
| WDC WD5000AAKS-75V0A0 500GB     | 1        | 0.65%   |
| WDC WD40EZRZ-00GXCB0 4TB        | 1        | 0.65%   |
| WDC WD40EFRX-68N32N0 4TB        | 1        | 0.65%   |
| WDC WD40EFAX-68JH4N1 4TB        | 1        | 0.65%   |
| WDC WD40EFAX-68JH4N0 4TB        | 1        | 0.65%   |
| WDC WD3200BPVT-75JJ5T0 320GB    | 1        | 0.65%   |
| WDC WD3200BEVT-22ZCT0 320GB     | 1        | 0.65%   |
| WDC WD3200AAKS-00VYA0 320GB     | 1        | 0.65%   |
| WDC WD30EZRZ-00Z5HB0 3TB        | 1        | 0.65%   |
| WDC WD30EZRX-00SPEB0 3TB        | 1        | 0.65%   |
| WDC WD2500AAKX-001CA0 250GB     | 1        | 0.65%   |
| WDC WD20PURZ-85GU6Y0 2TB        | 1        | 0.65%   |
| WDC WD20EZRX-00D8PB0 2TB        | 1        | 0.65%   |
| WDC WD20EZAZ-00GGJB0 2TB        | 1        | 0.65%   |
| WDC WD1600AAJS-60Z0A0 160GB     | 1        | 0.65%   |
| WDC WD1600AAJS-08L7A0 160GB     | 1        | 0.65%   |
| WDC WD10EZEX-22RKKA0 1TB        | 1        | 0.65%   |
| WDC WD10EZEX-22MFCA0 1TB        | 1        | 0.65%   |
| WDC WD10EZEX-22BN5A0 1TB        | 1        | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB        | 1        | 0.65%   |
| WDC WD10EZEX-00RKKA0 1TB        | 1        | 0.65%   |
| WDC WD10EAVS-00D7B1 1TB         | 1        | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 42     | 33.82%  |
| WDC                 | 21       | 28     | 30.88%  |
| Toshiba             | 7        | 8      | 10.29%  |
| Hitachi             | 6        | 6      | 8.82%   |
| HGST                | 4        | 5      | 5.88%   |
| Samsung Electronics | 3        | 3      | 4.41%   |
| USB 3.0             | 1        | 2      | 1.47%   |
| Maxtor              | 1        | 1      | 1.47%   |
| Fujitsu             | 1        | 1      | 1.47%   |
| ASMT                | 1        | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 16     | 25.49%  |
| SanDisk             | 8        | 9      | 15.69%  |
| Crucial             | 6        | 6      | 11.76%  |
| Kingston            | 4        | 4      | 7.84%   |
| Intenso             | 3        | 3      | 5.88%   |
| A-DATA Technology   | 2        | 2      | 3.92%   |
| WDC                 | 1        | 1      | 1.96%   |
| TO Exter            | 1        | 1      | 1.96%   |
| Team                | 1        | 1      | 1.96%   |
| SPCC                | 1        | 1      | 1.96%   |
| Patriot             | 1        | 1      | 1.96%   |
| OCZ                 | 1        | 1      | 1.96%   |
| NGFF                | 1        | 1      | 1.96%   |
| Micron Technology   | 1        | 1      | 1.96%   |
| Leven               | 1        | 1      | 1.96%   |
| JMicron Technology  | 1        | 1      | 1.96%   |
| Integral            | 1        | 1      | 1.96%   |
| Corsair             | 1        | 1      | 1.96%   |
| China               | 1        | 1      | 1.96%   |
| BHT                 | 1        | 1      | 1.96%   |
| ASMT                | 1        | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 49       | 97     | 47.57%  |
| SSD     | 40       | 55     | 38.83%  |
| NVMe    | 13       | 19     | 12.62%  |
| Unknown | 1        | 1      | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 67       | 140    | 77.01%  |
| NVMe | 13       | 19     | 14.94%  |
| SAS  | 7        | 13     | 8.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 44       | 65     | 43.56%  |
| 0.51-1.0   | 32       | 40     | 31.68%  |
| 1.01-2.0   | 10       | 12     | 9.9%    |
| 4.01-10.0  | 7        | 24     | 6.93%   |
| 3.01-4.0   | 5        | 7      | 4.95%   |
| 2.01-3.0   | 3        | 4      | 2.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 19       | 27.14%  |
| 1001-2000      | 13       | 18.57%  |
| More than 3000 | 12       | 17.14%  |
| 501-1000       | 12       | 17.14%  |
| 251-500        | 7        | 10%     |
| 51-100         | 4        | 5.71%   |
| 21-50          | 2        | 2.86%   |
| 1-20           | 1        | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 19       | 27.14%  |
| 21-50          | 13       | 18.57%  |
| 101-250        | 8        | 11.43%  |
| More than 3000 | 6        | 8.57%   |
| 251-500        | 6        | 8.57%   |
| 51-100         | 6        | 8.57%   |
| 2001-3000      | 4        | 5.71%   |
| 1001-2000      | 4        | 5.71%   |
| 501-1000       | 4        | 5.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 3        | 3      | 17.65%  |
| Samsung Electronics HD753LJ 752GB     | 2        | 2      | 11.76%  |
| WDC WD1600AAJS-08L7A0 160GB           | 1        | 1      | 5.88%   |
| WDC WD10EZEX-22BN5A0 1TB              | 1        | 1      | 5.88%   |
| Toshiba HDWE140 4TB                   | 1        | 1      | 5.88%   |
| Seagate ST8000DM004-2CX1 8TB          | 1        | 6      | 5.88%   |
| Seagate ST3320820AS 320GB             | 1        | 1      | 5.88%   |
| Seagate ST3200822AS 200GB             | 1        | 1      | 5.88%   |
| Seagate ST1000VM002-9ZL162 1TB        | 1        | 1      | 5.88%   |
| Samsung Electronics SSD 960 PRO 512GB | 1        | 1      | 5.88%   |
| Hitachi HDS5C1010CLA382 1TB           | 1        | 1      | 5.88%   |
| HGST HTS721010A9 1TB                  | 1        | 1      | 5.88%   |
| A-DATA Technology SU650 240GB SSD     | 1        | 1      | 5.88%   |
| A-DATA Technology SP550 240GB SSD     | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 12     | 41.18%  |
| Samsung Electronics | 3        | 3      | 17.65%  |
| WDC                 | 2        | 2      | 11.76%  |
| A-DATA Technology   | 2        | 2      | 11.76%  |
| Toshiba             | 1        | 1      | 5.88%   |
| Hitachi             | 1        | 1      | 5.88%   |
| HGST                | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 12     | 50%     |
| WDC                 | 2        | 2      | 14.29%  |
| Samsung Electronics | 2        | 2      | 14.29%  |
| Toshiba             | 1        | 1      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |
| HGST                | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 19     | 81.25%  |
| SSD  | 2        | 2      | 12.5%   |
| NVMe | 1        | 1      | 6.25%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD10EAVS-00D7B1 1TB               | 1        | 1      | 50%     |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 64       | 134    | 71.11%  |
| Malfunc  | 16       | 22     | 17.78%  |
| Detected | 8        | 14     | 8.89%   |
| Failed   | 2        | 2      | 2.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 46       | 46.94%  |
| AMD                       | 20       | 20.41%  |
| Samsung Electronics       | 7        | 7.14%   |
| Marvell Technology Group  | 5        | 5.1%    |
| ASMedia Technology        | 5        | 5.1%    |
| Phison Electronics        | 3        | 3.06%   |
| Nvidia                    | 3        | 3.06%   |
| JMicron Technology        | 2        | 2.04%   |
| VIA Technologies          | 1        | 1.02%   |
| Silicon Image             | 1        | 1.02%   |
| SanDisk                   | 1        | 1.02%   |
| Realtek Semiconductor     | 1        | 1.02%   |
| LSI Logic / Symbios Logic | 1        | 1.02%   |
| Apple                     | 1        | 1.02%   |
| Adaptec                   | 1        | 1.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11       | 8.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10       | 7.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7        | 5.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 3.94%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 3.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 3.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 3.15%   |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 3.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 2.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 2.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3        | 2.36%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 2.36%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.57%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2        | 1.57%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2        | 1.57%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2        | 1.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.57%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2        | 1.57%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 1.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 1.57%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 1.57%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 0.79%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.79%   |
| SanDisk WD Black NVMe SSD                                                      | 1        | 0.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.79%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1        | 0.79%   |
| Phison E12 NVMe Controller                                                     | 1        | 0.79%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.79%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.79%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                        | 1        | 0.79%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.79%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1        | 0.79%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 1        | 0.79%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1        | 0.79%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 0.79%   |
| JMicron JMB362 SATA Controller                                                 | 1        | 0.79%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1        | 0.79%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 0.79%   |
| Intel NVMe Optane Memory Series                                                | 1        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 57       | 58.76%  |
| IDE  | 20       | 20.62%  |
| NVMe | 13       | 13.4%   |
| RAID | 3        | 3.09%   |
| SAS  | 3        | 3.09%   |
| SCSI | 1        | 1.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 47       | 67.14%  |
| AMD    | 23       | 32.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz       | 3        | 4.29%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 3        | 4.29%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 2        | 2.86%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 2        | 2.86%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 2.86%   |
| AMD Ryzen 9 3950X 16-Core Processor    | 2        | 2.86%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 2        | 2.86%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 2        | 2.86%   |
| Intel Xeon W-2150B CPU @ 3.00GHz       | 1        | 1.43%   |
| Intel Xeon CPU E5420 @ 2.50GHz         | 1        | 1.43%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz     | 1        | 1.43%   |
| Intel Pentium D CPU 3.40GHz            | 1        | 1.43%   |
| Intel Pentium CPU G3220 @ 3.00GHz      | 1        | 1.43%   |
| Intel Pentium 4 CPU 3.20GHz            | 1        | 1.43%   |
| Intel Pentium 4 CPU 2.80GHz            | 1        | 1.43%   |
| Intel Core i9-10900K CPU @ 3.70GHz     | 1        | 1.43%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 1        | 1.43%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 1        | 1.43%   |
| Intel Core i7-4770K CPU @ 3.50GHz      | 1        | 1.43%   |
| Intel Core i7-3930K CPU @ 3.20GHz      | 1        | 1.43%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 1.43%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 1.43%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1        | 1.43%   |
| Intel Core i7 CPU 930 @ 2.80GHz        | 1        | 1.43%   |
| Intel Core i5-9400T CPU @ 1.80GHz      | 1        | 1.43%   |
| Intel Core i5-8600K CPU @ 3.60GHz      | 1        | 1.43%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1        | 1.43%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 1        | 1.43%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 1        | 1.43%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 1        | 1.43%   |
| Intel Core i5-2500K CPU @ 3.30GHz      | 1        | 1.43%   |
| Intel Core i5 CPU 650 @ 3.20GHz        | 1        | 1.43%   |
| Intel Core i3-6100T CPU @ 3.20GHz      | 1        | 1.43%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 1        | 1.43%   |
| Intel Core i3-4340 CPU @ 3.60GHz       | 1        | 1.43%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 1        | 1.43%   |
| Intel Core i3-4130 CPU @ 3.40GHz       | 1        | 1.43%   |
| Intel Core i3-3245 CPU @ 3.40GHz       | 1        | 1.43%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 1        | 1.43%   |
| Intel Core i3 CPU 540 @ 3.07GHz        | 1        | 1.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 18       | 25.71%  |
| Intel Core i7          | 10       | 14.29%  |
| Intel Core i3          | 8        | 11.43%  |
| AMD Ryzen 9            | 4        | 5.71%   |
| Intel Xeon             | 3        | 4.29%   |
| AMD Ryzen 5            | 3        | 4.29%   |
| AMD Phenom II X4       | 3        | 4.29%   |
| Intel Pentium 4        | 2        | 2.86%   |
| AMD Ryzen 7            | 2        | 2.86%   |
| AMD Athlon II X2       | 2        | 2.86%   |
| Intel Pentium D        | 1        | 1.43%   |
| Intel Pentium          | 1        | 1.43%   |
| Intel Core i9          | 1        | 1.43%   |
| Intel Core 2 Duo       | 1        | 1.43%   |
| Intel Core 2           | 1        | 1.43%   |
| Intel Celeron          | 1        | 1.43%   |
| AMD Ryzen Threadripper | 1        | 1.43%   |
| AMD Ryzen 3            | 1        | 1.43%   |
| AMD FX                 | 1        | 1.43%   |
| AMD E                  | 1        | 1.43%   |
| AMD Athlon X4          | 1        | 1.43%   |
| AMD Athlon Dual Core   | 1        | 1.43%   |
| AMD Athlon 64 X2       | 1        | 1.43%   |
| AMD A4                 | 1        | 1.43%   |
| AMD A10                | 1        | 1.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 30       | 42.86%  |
| 2      | 19       | 27.14%  |
| 6      | 7        | 10%     |
| 8      | 4        | 5.71%   |
| 1      | 3        | 4.29%   |
| 16     | 2        | 2.86%   |
| 12     | 2        | 2.86%   |
| 10     | 2        | 2.86%   |
| 32     | 1        | 1.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 69       | 98.57%  |
| 2      | 1        | 1.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 38       | 54.29%  |
| 1      | 32       | 45.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 69       | 98.57%  |
| 32-bit         | 1        | 1.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 11       | 15.71%  |
| Unknown    | 9        | 12.86%  |
| 0x206a7    | 6        | 8.57%   |
| 0x306a9    | 5        | 7.14%   |
| 0x506e3    | 4        | 5.71%   |
| 0x08701021 | 4        | 5.71%   |
| 0x906ea    | 3        | 4.29%   |
| 0x010000c8 | 3        | 4.29%   |
| 0xf41      | 2        | 2.86%   |
| 0x206d7    | 2        | 2.86%   |
| 0x10676    | 2        | 2.86%   |
| 0x0a50000d | 2        | 2.86%   |
| 0xf65      | 1        | 1.43%   |
| 0xa0655    | 1        | 1.43%   |
| 0x906ed    | 1        | 1.43%   |
| 0x6f6      | 1        | 1.43%   |
| 0x506ca    | 1        | 1.43%   |
| 0x50654    | 1        | 1.43%   |
| 0x20655    | 1        | 1.43%   |
| 0x106a5    | 1        | 1.43%   |
| 0x0a201009 | 1        | 1.43%   |
| 0x08301039 | 1        | 1.43%   |
| 0x08108109 | 1        | 1.43%   |
| 0x08101016 | 1        | 1.43%   |
| 0x06003106 | 1        | 1.43%   |
| 0x06001119 | 1        | 1.43%   |
| 0x06000852 | 1        | 1.43%   |
| 0x010000c7 | 1        | 1.43%   |
| 0x010000b6 | 1        | 1.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 11       | 15.71%  |
| SandyBridge | 8        | 11.43%  |
| Zen 2       | 7        | 10%     |
| Skylake     | 7        | 10%     |
| KabyLake    | 5        | 7.14%   |
| K10         | 5        | 7.14%   |
| IvyBridge   | 5        | 7.14%   |
| Zen 3       | 3        | 4.29%   |
| NetBurst    | 3        | 4.29%   |
| Westmere    | 2        | 2.86%   |
| Piledriver  | 2        | 2.86%   |
| Penryn      | 2        | 2.86%   |
| K8 Hammer   | 2        | 2.86%   |
| Zen+        | 1        | 1.43%   |
| Zen         | 1        | 1.43%   |
| Steamroller | 1        | 1.43%   |
| Nehalem     | 1        | 1.43%   |
| Goldmont    | 1        | 1.43%   |
| Excavator   | 1        | 1.43%   |
| Core        | 1        | 1.43%   |
| CometLake   | 1        | 1.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 36       | 47.37%  |
| Intel  | 23       | 30.26%  |
| AMD    | 17       | 22.37%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 7.79%   |
| Intel HD Graphics 530                                                       | 4        | 5.19%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 3.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.9%    |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 3.9%    |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.6%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 2.6%    |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 2.6%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 2.6%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.6%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 2.6%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.6%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.6%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.3%    |
| Nvidia NV34 [GeForce FX 5500]                                               | 1        | 1.3%    |
| Nvidia GT216 [GeForce 315]                                                  | 1        | 1.3%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.3%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.3%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.3%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.3%    |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.3%    |
| Nvidia GK208 [GeForce GT 720]                                               | 1        | 1.3%    |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 1.3%    |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.3%    |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.3%    |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.3%    |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.3%    |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 1.3%    |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.3%    |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.3%    |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.3%    |
| Nvidia C77 [GeForce 8200]                                                   | 1        | 1.3%    |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 1.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.3%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.3%    |
| Intel HD Graphics 630                                                       | 1        | 1.3%    |
| Intel HD Graphics 500                                                       | 1        | 1.3%    |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.3%    |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 1.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 32       | 45.71%  |
| 1 x Intel      | 18       | 25.71%  |
| 1 x AMD        | 16       | 22.86%  |
| Intel + Nvidia | 2        | 2.86%   |
| 2 x Nvidia     | 1        | 1.43%   |
| AMD + Nvidia   | 1        | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 48       | 68.57%  |
| Proprietary | 22       | 31.43%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 30%     |
| 1.01-2.0   | 12       | 17.14%  |
| 0.01-0.5   | 10       | 14.29%  |
| 0.51-1.0   | 9        | 12.86%  |
| 3.01-4.0   | 6        | 8.57%   |
| 7.01-8.0   | 4        | 5.71%   |
| 8.01-16.0  | 4        | 5.71%   |
| 5.01-6.0   | 2        | 2.86%   |
| 2.01-3.0   | 1        | 1.43%   |
| 16.01-24.0 | 1        | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 16.25%  |
| Goldstar             | 10       | 12.5%   |
| Philips              | 7        | 8.75%   |
| Hewlett-Packard      | 7        | 8.75%   |
| Dell                 | 7        | 8.75%   |
| Acer                 | 7        | 8.75%   |
| Ancor Communications | 6        | 7.5%    |
| AOC                  | 3        | 3.75%   |
| Eizo                 | 2        | 2.5%    |
| VIE                  | 1        | 1.25%   |
| Unknown              | 1        | 1.25%   |
| TVT                  | 1        | 1.25%   |
| Targa Visionary      | 1        | 1.25%   |
| Sony                 | 1        | 1.25%   |
| Seiki                | 1        | 1.25%   |
| ONN                  | 1        | 1.25%   |
| Onkyo                | 1        | 1.25%   |
| NEC Computers        | 1        | 1.25%   |
| Medion               | 1        | 1.25%   |
| KTC                  | 1        | 1.25%   |
| Iiyama               | 1        | 1.25%   |
| Hannspree            | 1        | 1.25%   |
| Fujitsu Siemens      | 1        | 1.25%   |
| DENON                | 1        | 1.25%   |
| BenQ                 | 1        | 1.25%   |
| ASUSTek Computer     | 1        | 1.25%   |
| Apple                | 1        | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 2        | 2.25%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                   | 1        | 1.12%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                   | 1        | 1.12%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                          | 1        | 1.12%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch     | 1        | 1.12%   |
| Sony TV  *00 SNY8004 3840x2160 1440x810mm 65.0-inch                     | 1        | 1.12%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                     | 1        | 1.12%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch       | 1        | 1.12%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1        | 1.12%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 480x270mm 21.7-inch    | 1        | 1.12%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch    | 1        | 1.12%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch     | 1        | 1.12%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch    | 1        | 1.12%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch    | 1        | 1.12%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch    | 1        | 1.12%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch    | 1        | 1.12%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch     | 1        | 1.12%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch     | 1        | 1.12%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch      | 1        | 1.12%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch       | 1        | 1.12%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch    | 1        | 1.12%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 1.12%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch    | 1        | 1.12%   |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch       | 1        | 1.12%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch               | 1        | 1.12%   |
| Philips 247E4 PHLC0C0 1920x1080 521x293mm 23.5-inch                     | 1        | 1.12%   |
| Philips 227E4LH PHLC0AC 1920x1080 477x268mm 21.5-inch                   | 1        | 1.12%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 1        | 1.12%   |
| Philips 201E PHLC033 1600x900 443x249mm 20.0-inch                       | 1        | 1.12%   |
| Philips 190V PHL0847 1280x1024 376x301mm 19.0-inch                      | 1        | 1.12%   |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                      | 1        | 1.12%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                     | 1        | 1.12%   |
| Onkyo HT-R494 ONK0F43 3840x2160 1150x650mm 52.0-inch                    | 1        | 1.12%   |
| NEC Computers LCD2180UX NEC662C 1600x1200 430x320mm 21.1-inch           | 1        | 1.12%   |
| Medion MD32119PR MED89C1 1280x1024 376x301mm 19.0-inch                  | 1        | 1.12%   |
| KTC H-W2206S-D KTC2203 1680x1050 433x270mm 20.1-inch                    | 1        | 1.12%   |
| Iiyama PL2435M IVM6112 1920x1080 521x293mm 23.5-inch                    | 1        | 1.12%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch             | 1        | 1.12%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch             | 1        | 1.12%   |
| Hewlett-Packard LE2202x HWP2966 1920x1080 476x268mm 21.5-inch           | 1        | 1.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 34       | 44.16%  |
| 3840x2160 (4K)     | 10       | 12.99%  |
| 1280x1024 (SXGA)   | 9        | 11.69%  |
| 1680x1050 (WSXGA+) | 5        | 6.49%   |
| 1920x1200 (WUXGA)  | 3        | 3.9%    |
| 1440x900 (WXGA+)   | 3        | 3.9%    |
| 1366x768 (WXGA)    | 3        | 3.9%    |
| 2560x1440 (QHD)    | 2        | 2.6%    |
| 1600x900 (HD+)     | 2        | 2.6%    |
| 1360x768           | 2        | 2.6%    |
| 5760x2160          | 1        | 1.3%    |
| 1600x1200          | 1        | 1.3%    |
| 1400x1050          | 1        | 1.3%    |
| Unknown            | 1        | 1.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 13       | 16.25%  |
| 23      | 12       | 15%     |
| 27      | 9        | 11.25%  |
| 24      | 9        | 11.25%  |
| 19      | 7        | 8.75%   |
| 31      | 5        | 6.25%   |
| 22      | 5        | 6.25%   |
| 17      | 5        | 6.25%   |
| 18      | 4        | 5%      |
| 20      | 3        | 3.75%   |
| 84      | 1        | 1.25%   |
| 65      | 1        | 1.25%   |
| 52      | 1        | 1.25%   |
| 50      | 1        | 1.25%   |
| 43      | 1        | 1.25%   |
| 32      | 1        | 1.25%   |
| 15      | 1        | 1.25%   |
| Unknown | 1        | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 27       | 35.06%  |
| 401-500     | 26       | 33.77%  |
| 601-700     | 7        | 9.09%   |
| 301-350     | 6        | 7.79%   |
| 351-400     | 4        | 5.19%   |
| 1001-1500   | 3        | 3.9%    |
| 701-800     | 1        | 1.3%    |
| 1501-2000   | 1        | 1.3%    |
| 901-1000    | 1        | 1.3%    |
| Unknown     | 1        | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 49       | 67.12%  |
| 16/10   | 12       | 16.44%  |
| 5/4     | 8        | 10.96%  |
| 4/3     | 2        | 2.74%   |
| 3/2     | 1        | 1.37%   |
| Unknown | 1        | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 32       | 41.03%  |
| 151-200        | 12       | 15.38%  |
| 301-350        | 9        | 11.54%  |
| 141-150        | 9        | 11.54%  |
| 351-500        | 6        | 7.69%   |
| More than 1000 | 4        | 5.13%   |
| 251-300        | 3        | 3.85%   |
| 111-120        | 1        | 1.28%   |
| 501-1000       | 1        | 1.28%   |
| Unknown        | 1        | 1.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 51       | 69.86%  |
| 101-120 | 16       | 21.92%  |
| 121-160 | 3        | 4.11%   |
| 1-50    | 1        | 1.37%   |
| 161-240 | 1        | 1.37%   |
| Unknown | 1        | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47       | 67.14%  |
| 2     | 23       | 32.86%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 39       | 37.5%   |
| Intel                           | 32       | 30.77%  |
| Qualcomm Atheros                | 10       | 9.62%   |
| Broadcom                        | 5        | 4.81%   |
| TP-Link                         | 3        | 2.88%   |
| Nvidia                          | 3        | 2.88%   |
| Broadcom Limited                | 2        | 1.92%   |
| Aquantia                        | 2        | 1.92%   |
| ZyDAS                           | 1        | 0.96%   |
| Wacom                           | 1        | 0.96%   |
| Ralink Technology               | 1        | 0.96%   |
| Qualcomm Atheros Communications | 1        | 0.96%   |
| NetGear                         | 1        | 0.96%   |
| Microsoft                       | 1        | 0.96%   |
| InterBiometrics                 | 1        | 0.96%   |
| ASIX Electronics                | 1        | 0.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 32       | 28.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8        | 7.14%   |
| Intel I211 Gigabit Network Connection                                         | 6        | 5.36%   |
| Intel Wireless-AC 9260                                                        | 4        | 3.57%   |
| Intel Ethernet Connection I217-LM                                             | 4        | 3.57%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 1.79%   |
| Nvidia MCP77 Ethernet                                                         | 2        | 1.79%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 1.79%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 1.79%   |
| ZyDAS ZD1211B 802.11g                                                         | 1        | 0.89%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1        | 0.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.89%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 0.89%   |
| TP-Link 802.11ac NIC                                                          | 1        | 0.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.89%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1        | 0.89%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1        | 0.89%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 0.89%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.89%   |
| Realtek 802.11ac NIC                                                          | 1        | 0.89%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.89%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.89%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.89%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 0.89%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.89%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 0.89%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 0.89%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.89%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                   | 1        | 0.89%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 0.89%   |
| InterBiometrics Io                                                            | 1        | 0.89%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 0.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 8        | 25%     |
| Intel                           | 8        | 25%     |
| Realtek Semiconductor           | 5        | 15.63%  |
| TP-Link                         | 3        | 9.38%   |
| Broadcom                        | 2        | 6.25%   |
| ZyDAS                           | 1        | 3.13%   |
| Wacom                           | 1        | 3.13%   |
| Ralink Technology               | 1        | 3.13%   |
| Qualcomm Atheros Communications | 1        | 3.13%   |
| NetGear                         | 1        | 3.13%   |
| Microsoft                       | 1        | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wireless-AC 9260                                                        | 4        | 12.5%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 6.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 6.25%   |
| ZyDAS ZD1211B 802.11g                                                         | 1        | 3.13%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1        | 3.13%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 3.13%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 3.13%   |
| TP-Link 802.11ac NIC                                                          | 1        | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 3.13%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1        | 3.13%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 3.13%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 3.13%   |
| Realtek 802.11ac NIC                                                          | 1        | 3.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 3.13%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 3.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 3.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 3.13%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 3.13%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 3.13%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 3.13%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                   | 1        | 3.13%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 3.13%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 3.13%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                            | 1        | 3.13%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1        | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 35       | 44.87%  |
| Intel                 | 30       | 38.46%  |
| Nvidia                | 3        | 3.85%   |
| Broadcom              | 3        | 3.85%   |
| Qualcomm Atheros      | 2        | 2.56%   |
| Broadcom Limited      | 2        | 2.56%   |
| Aquantia              | 2        | 2.56%   |
| ASIX Electronics      | 1        | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 40.51%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 10.13%  |
| Intel I211 Gigabit Network Connection                             | 6        | 7.59%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 5.06%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.8%    |
| Nvidia MCP77 Ethernet                                             | 2        | 2.53%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.53%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.27%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.27%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.27%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.27%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.27%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.27%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.27%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.27%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.27%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 1.27%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 1.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.27%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.27%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 1.27%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 1.27%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 1.27%   |
| ASIX AX88772B                                                     | 1        | 1.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 70       | 68.63%  |
| WiFi     | 31       | 30.39%  |
| Modem    | 1        | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 62       | 80.52%  |
| WiFi     | 15       | 19.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 44       | 62.86%  |
| 2     | 24       | 34.29%  |
| 3     | 2        | 2.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 60       | 85.71%  |
| Yes  | 10       | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 40%     |
| Cambridge Silicon Radio         | 6        | 30%     |
| ASUSTek Computer                | 3        | 15%     |
| Qualcomm Atheros Communications | 2        | 10%     |
| Realtek Semiconductor           | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 30%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 20%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 10%     |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 10%     |
| Realtek Bluetooth Radio                             | 1        | 5%      |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 5%      |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 5%      |
| Intel Bluetooth wireless interface                  | 1        | 5%      |
| Intel AX210 Bluetooth                               | 1        | 5%      |
| ASUS BCM20702A0                                     | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 43       | 31.16%  |
| Nvidia                               | 31       | 22.46%  |
| AMD                                  | 24       | 17.39%  |
| Texas Instruments                    | 4        | 2.9%    |
| C-Media Electronics                  | 4        | 2.9%    |
| Yamaha                               | 3        | 2.17%   |
| PreSonus Audio Electronics           | 2        | 1.45%   |
| M-Audio                              | 2        | 1.45%   |
| Logitech                             | 2        | 1.45%   |
| JMTek                                | 2        | 1.45%   |
| ZOOM                                 | 1        | 0.72%   |
| Xilinx                               | 1        | 0.72%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.72%   |
| Textech International                | 1        | 0.72%   |
| Studiologic                          | 1        | 0.72%   |
| SteelSeries ApS                      | 1        | 0.72%   |
| Samson Technologies                  | 1        | 0.72%   |
| QinHeng Electronics                  | 1        | 0.72%   |
| Plantronics                          | 1        | 0.72%   |
| Medeli Electronics                   | 1        | 0.72%   |
| Mark of the Unicorn                  | 1        | 0.72%   |
| KTMicro                              | 1        | 0.72%   |
| Generalplus Technology               | 1        | 0.72%   |
| Focusrite-Novation                   | 1        | 0.72%   |
| Ensoniq                              | 1        | 0.72%   |
| Creative Technology                  | 1        | 0.72%   |
| BEHRINGER International              | 1        | 0.72%   |
| ASUSTek Computer                     | 1        | 0.72%   |
| Apple                                | 1        | 0.72%   |
| Alesis                               | 1        | 0.72%   |
| AKAI Professional M.I.               | 1        | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 11       | 6.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 7        | 4.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 4.43%   |
| AMD Starship/Matisse HD Audio Controller                                          | 7        | 4.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 3.16%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 2.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 2.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4        | 2.53%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4        | 2.53%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3        | 1.9%    |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 1.9%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 1.9%    |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 1.9%    |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 1.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 1.9%    |
| AMD FCH Azalia Controller                                                         | 3        | 1.9%    |
| PreSonus Audio Electronics Studio 24c                                             | 2        | 1.27%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 1.27%   |
| Nvidia High Definition Audio Controller                                           | 2        | 1.27%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 1.27%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1.27%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 1.27%   |
| M-Audio M-Track                                                                   | 2        | 1.27%   |
| JMTek USB PnP Audio Device(EEPROM)                                                | 2        | 1.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 1.27%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 2        | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 1.27%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.27%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 1.27%   |
| ZOOM U-22                                                                         | 1        | 0.63%   |
| Yamaha YMF-744B [DS-1S Audio Controller]                                          | 1        | 0.63%   |
| Yamaha MG-XU                                                                      | 1        | 0.63%   |
| Yamaha AG06/AG03                                                                  | 1        | 0.63%   |
| Xilinx RME Hammerfall DSP                                                         | 1        | 0.63%   |
| Thesycon Systemsoftware & Consulting USB HiRes Audio                              | 1        | 0.63%   |
| Textech International MIDI Interface cable                                        | 1        | 0.63%   |
| Texas Instruments PCM2900 Audio Codec                                             | 1        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 13       | 14.29%  |
| Samsung Electronics | 12       | 13.19%  |
| Kingston            | 12       | 13.19%  |
| Unknown             | 10       | 10.99%  |
| Corsair             | 10       | 10.99%  |
| Crucial             | 9        | 9.89%   |
| G.Skill             | 6        | 6.59%   |
| Micron Technology   | 5        | 5.49%   |
| Patriot             | 3        | 3.3%    |
| Unifosa             | 1        | 1.1%    |
| Smart               | 1        | 1.1%    |
| S                   | 1        | 1.1%    |
| PNY                 | 1        | 1.1%    |
| OCZ                 | 1        | 1.1%    |
| Nanya Technology    | 1        | 1.1%    |
| M                   | 1        | 1.1%    |
| HBS                 | 1        | 1.1%    |
| Elpida              | 1        | 1.1%    |
| Aeneon              | 1        | 1.1%    |
| 0194808980CE        | 1        | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1600MT/s                     | 2        | 1.94%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s         | 2        | 1.94%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s         | 2        | 1.94%   |
| Patriot RAM 3200 C16 Series 32GB DIMM DDR4 3266MT/s         | 2        | 1.94%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 2        | 1.94%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s       | 2        | 1.94%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 2        | 1.94%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s      | 2        | 1.94%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1        | 0.97%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                   | 1        | 0.97%   |
| Unknown RAM Module 512MB DIMM DDR                           | 1        | 0.97%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s                    | 1        | 0.97%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                    | 1        | 0.97%   |
| Unknown RAM Module 256MB DIMM DDR                           | 1        | 0.97%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1        | 0.97%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1        | 0.97%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1        | 0.97%   |
| Unknown RAM Module 1024MB DIMM DDR                          | 1        | 0.97%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1        | 0.97%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s                 | 1        | 0.97%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s           | 1        | 0.97%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s          | 1        | 0.97%   |
| SK hynix RAM TMT41GU6BFR8C-PBSC 8192MB DIMM DDR3 1600MT/s   | 1        | 0.97%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 0.97%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2666MT/s               | 1        | 0.97%   |
| SK hynix RAM HYMP564U64BP8-C4 512MB DIMM DDR 533MT/s        | 1        | 0.97%   |
| SK hynix RAM HYMP125F72CP8N3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.97%   |
| SK hynix RAM HYMP125F72CP8D3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.97%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s        | 1        | 0.97%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1        | 0.97%   |
| SK hynix RAM HMT351U7CFR8C-PB 4096MB DIMM DDR3 1600MT/s     | 1        | 0.97%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s        | 1        | 0.97%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s        | 1        | 0.97%   |
| SK hynix RAM HMT325U7CFR8C-PB 2GB DIMM DDR3 1600MT/s        | 1        | 0.97%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s        | 1        | 0.97%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 0.97%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 0.97%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s   | 1        | 0.97%   |
| Samsung RAM Module 2048MB DIMM DDR3 1066MT/s                | 1        | 0.97%   |
| Samsung RAM M395T5750GZ4-CE66 2GB FB-DIMM DDR2 667MT/s      | 1        | 0.97%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 35       | 47.95%  |
| DDR4    | 23       | 31.51%  |
| DDR2    | 6        | 8.22%   |
| Unknown | 4        | 5.48%   |
| DDR     | 3        | 4.11%   |
| SDRAM   | 2        | 2.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 66       | 92.96%  |
| SODIMM  | 4        | 5.63%   |
| FB-DIMM | 1        | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 23       | 28.4%   |
| 8192  | 21       | 25.93%  |
| 2048  | 12       | 14.81%  |
| 16384 | 10       | 12.35%  |
| 1024  | 7        | 8.64%   |
| 32768 | 5        | 6.17%   |
| 512   | 2        | 2.47%   |
| 256   | 1        | 1.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 24       | 29.27%  |
| 1333    | 10       | 12.2%   |
| 3600    | 4        | 4.88%   |
| 3200    | 4        | 4.88%   |
| 2133    | 4        | 4.88%   |
| 1066    | 4        | 4.88%   |
| 667     | 4        | 4.88%   |
| 3266    | 3        | 3.66%   |
| 1866    | 3        | 3.66%   |
| 800     | 3        | 3.66%   |
| 2667    | 2        | 2.44%   |
| 1867    | 2        | 2.44%   |
| 1800    | 2        | 2.44%   |
| 533     | 2        | 2.44%   |
| Unknown | 2        | 2.44%   |
| 3500    | 1        | 1.22%   |
| 3466    | 1        | 1.22%   |
| 3000    | 1        | 1.22%   |
| 2934    | 1        | 1.22%   |
| 2933    | 1        | 1.22%   |
| 2800    | 1        | 1.22%   |
| 2666    | 1        | 1.22%   |
| 2472    | 1        | 1.22%   |
| 2400    | 1        | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 50%     |
| Ricoh           | 1        | 25%     |
| Canon           | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| Ricoh Aficio SP 100SU | 1        | 25%     |
| HP OfficeJet Pro 6960 | 1        | 25%     |
| HP OfficeJet 6950     | 1        | 25%     |
| Canon LiDE 400        | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LiDE 60 | 1        | 50%     |
| Canon CanoScan FB630U  | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 35.29%  |
| Samsung Electronics           | 2        | 11.76%  |
| Microsoft                     | 2        | 11.76%  |
| Microdia                      | 2        | 11.76%  |
| ViewSonic                     | 1        | 5.88%   |
| Sweex                         | 1        | 5.88%   |
| Sunplus IT                    | 1        | 5.88%   |
| Sunplus Innovation Technology | 1        | 5.88%   |
| Philips (or NXP)              | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)                | 2        | 11.76%  |
| Logitech Webcam C270                   | 2        | 11.76%  |
| ViewSonic PC Camera                    | 1        | 5.88%   |
| Sweex WC060 Series HD Webcam           | 1        | 5.88%   |
| Sunplus IT AUKEY PC-LM1 USB Camera     | 1        | 5.88%   |
| Sunplus HD 720P webcam                 | 1        | 5.88%   |
| Philips (or NXP) Webcam SPC530NC       | 1        | 5.88%   |
| Microsoft LifeCam VX-5000              | 1        | 5.88%   |
| Microsoft LifeCam Cinema               | 1        | 5.88%   |
| Microdia USB 2.0 Camera                | 1        | 5.88%   |
| Microdia MSI Starcam Racer             | 1        | 5.88%   |
| Logitech QuickCam Communicate MP/S5500 | 1        | 5.88%   |
| Logitech Portable Webcam C905          | 1        | 5.88%   |
| Logitech HD Webcam C910                | 1        | 5.88%   |
| Logitech HD Pro Webcam C920            | 1        | 5.88%   |

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
| 0     | 62       | 88.57%  |
| 1     | 8        | 11.43%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 3        | 37.5%   |
| Sound                    | 2        | 25%     |
| Modem                    | 1        | 12.5%   |
| Graphics card            | 1        | 12.5%   |
| Communication controller | 1        | 12.5%   |

