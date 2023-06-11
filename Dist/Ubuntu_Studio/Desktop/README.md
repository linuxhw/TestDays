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

Total: 89

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M4A785-M                    | [cbf9d11153](https://linux-hardware.org/?probe=cbf9d11153) | May 07, 2023 |
| ECS           | H410-SF110                  | [5e5011bdd3](https://linux-hardware.org/?probe=5e5011bdd3) | May 07, 2023 |
| HP            | 1495                        | [d6e629523f](https://linux-hardware.org/?probe=d6e629523f) | May 01, 2023 |
| DEPO Compu... | MS-7846                     | [bf72733735](https://linux-hardware.org/?probe=bf72733735) | Apr 13, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [35bae3b94d](https://linux-hardware.org/?probe=35bae3b94d) | Apr 01, 2023 |
| Fujitsu       | D3162-B1 S26361-D3162-B1    | [a2c287936d](https://linux-hardware.org/?probe=a2c287936d) | Mar 24, 2023 |
| Dell          | 0HHV7N A00                  | [8553f4abea](https://linux-hardware.org/?probe=8553f4abea) | Mar 13, 2023 |
| Dell          | 0HHV7N A00                  | [7d9e6e46db](https://linux-hardware.org/?probe=7d9e6e46db) | Mar 13, 2023 |
| Dell          | 0WR7PY A02                  | [257b3941af](https://linux-hardware.org/?probe=257b3941af) | Mar 10, 2023 |
| HP            | 8455                        | [f75db6c5d5](https://linux-hardware.org/?probe=f75db6c5d5) | Feb 12, 2023 |
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
| Ubuntu Studio 20.04 | 39       | 50%     |
| Ubuntu Studio 22.04 | 21       | 26.92%  |
| Ubuntu Studio 20.10 | 9        | 11.54%  |
| Ubuntu Studio 22.10 | 3        | 3.85%   |
| Ubuntu Studio 21.10 | 3        | 3.85%   |
| Ubuntu Studio 21.04 | 2        | 2.56%   |
| Ubuntu Studio 16.04 | 1        | 1.28%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu Studio | 77       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.0-58-lowlatency   | 3        | 3.8%    |
| 5.11.0-44-lowlatency   | 3        | 3.8%    |
| 5.8.0-48-lowlatency    | 2        | 2.53%   |
| 5.8.0-44-lowlatency    | 2        | 2.53%   |
| 5.8.0-25-lowlatency    | 2        | 2.53%   |
| 5.4.0-58-lowlatency    | 2        | 2.53%   |
| 5.4.0-56-lowlatency    | 2        | 2.53%   |
| 5.4.0-42-lowlatency    | 2        | 2.53%   |
| 5.4.0-26-lowlatency    | 2        | 2.53%   |
| 5.19.0-1021-lowlatency | 2        | 2.53%   |
| 5.15.0-71-lowlatency   | 2        | 2.53%   |
| 5.15.0-56-lowlatency   | 2        | 2.53%   |
| 5.15.0-53-lowlatency   | 2        | 2.53%   |
| 5.15.0-52-lowlatency   | 2        | 2.53%   |
| 5.15.0-46-lowlatency   | 2        | 2.53%   |
| 5.13.0-28-lowlatency   | 2        | 2.53%   |
| 5.8.0-50-lowlatency    | 1        | 1.27%   |
| 5.8.0-45-lowlatency    | 1        | 1.27%   |
| 5.8.0-36-lowlatency    | 1        | 1.27%   |
| 5.8.0-34-lowlatency    | 1        | 1.27%   |
| 5.8.0-33-lowlatency    | 1        | 1.27%   |
| 5.8.0-29-lowlatency    | 1        | 1.27%   |
| 5.4.0-99-lowlatency    | 1        | 1.27%   |
| 5.4.0-72-lowlatency    | 1        | 1.27%   |
| 5.4.0-71-lowlatency    | 1        | 1.27%   |
| 5.4.0-70-lowlatency    | 1        | 1.27%   |
| 5.4.0-65-lowlatency    | 1        | 1.27%   |
| 5.4.0-65-generic       | 1        | 1.27%   |
| 5.4.0-64-lowlatency    | 1        | 1.27%   |
| 5.4.0-62-lowlatency    | 1        | 1.27%   |
| 5.4.0-60-lowlatency    | 1        | 1.27%   |
| 5.4.0-53-lowlatency    | 1        | 1.27%   |
| 5.4.0-52-lowlatency    | 1        | 1.27%   |
| 5.4.0-51-lowlatency    | 1        | 1.27%   |
| 5.4.0-48-lowlatency    | 1        | 1.27%   |
| 5.4.0-47-lowlatency    | 1        | 1.27%   |
| 5.4.0-39-lowlatency    | 1        | 1.27%   |
| 5.4.0-33-lowlatency    | 1        | 1.27%   |
| 5.4.0-131-lowlatency   | 1        | 1.27%   |
| 5.4.0-125-lowlatency   | 1        | 1.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 30       | 38.46%  |
| 5.15.0  | 21       | 26.92%  |
| 5.8.0   | 12       | 15.38%  |
| 5.11.0  | 6        | 7.69%   |
| 5.19.0  | 4        | 5.13%   |
| 5.13.0  | 3        | 3.85%   |
| 5.15.6  | 1        | 1.28%   |
| 4.4.0   | 1        | 1.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 30       | 38.46%  |
| 5.15    | 22       | 28.21%  |
| 5.8     | 12       | 15.38%  |
| 5.11    | 6        | 7.69%   |
| 5.19    | 4        | 5.13%   |
| 5.13    | 3        | 3.85%   |
| 4.4     | 1        | 1.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 76       | 98.7%   |
| i686   | 1        | 1.3%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| XFCE            | 35       | 44.87%  |
| KDE5            | 31       | 39.74%  |
| GNOME           | 5        | 6.41%   |
| MATE            | 2        | 2.56%   |
| LXQt            | 2        | 2.56%   |
| KDE             | 1        | 1.28%   |
| GNOME Flashback | 1        | 1.28%   |
| Cinnamon        | 1        | 1.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 72       | 92.31%  |
| Tty     | 4        | 5.13%   |
| Wayland | 2        | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 30       | 38.96%  |
| TDM     | 25       | 32.47%  |
| LightDM | 15       | 19.48%  |
| GDM     | 6        | 7.79%   |
| GDM3    | 1        | 1.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 31       | 40.26%  |
| de_DE      | 9        | 11.69%  |
| fr_FR      | 7        | 9.09%   |
| pt_BR      | 4        | 5.19%   |
| en_GB      | 4        | 5.19%   |
| it_IT      | 3        | 3.9%    |
| ru_RU      | 2        | 2.6%    |
| en_AU      | 2        | 2.6%    |
| sv_SE      | 1        | 1.3%    |
| nl_NL      | 1        | 1.3%    |
| nl_BE      | 1        | 1.3%    |
| nb_NO      | 1        | 1.3%    |
| fr_FR.UTF8 | 1        | 1.3%    |
| fr_CH      | 1        | 1.3%    |
| fr_BE      | 1        | 1.3%    |
| es_GT      | 1        | 1.3%    |
| es_AR      | 1        | 1.3%    |
| en_DE      | 1        | 1.3%    |
| en_CA      | 1        | 1.3%    |
| de_AT      | 1        | 1.3%    |
| ca_ES      | 1        | 1.3%    |
| ca_AD      | 1        | 1.3%    |
| C          | 1        | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 45       | 58.44%  |
| EFI  | 32       | 41.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 75       | 97.4%   |
| Xfs  | 1        | 1.3%    |
| Ext2 | 1        | 1.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 39       | 50.65%  |
| MBR  | 38       | 49.35%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 74.36%  |
| Yes       | 20       | 25.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 57.69%  |
| Yes       | 33       | 42.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 27.27%  |
| Dell                | 12       | 15.58%  |
| Gigabyte Technology | 11       | 14.29%  |
| Hewlett-Packard     | 10       | 12.99%  |
| Fujitsu             | 4        | 5.19%   |
| ASRock              | 3        | 3.9%    |
| MSI                 | 2        | 2.6%    |
| System76            | 1        | 1.3%    |
| Pegatron            | 1        | 1.3%    |
| Packard Bell        | 1        | 1.3%    |
| Medion              | 1        | 1.3%    |
| Lenovo              | 1        | 1.3%    |
| Intel               | 1        | 1.3%    |
| IBM                 | 1        | 1.3%    |
| Foxconn             | 1        | 1.3%    |
| ECS                 | 1        | 1.3%    |
| DEPO Computers      | 1        | 1.3%    |
| AZW                 | 1        | 1.3%    |
| Apple               | 1        | 1.3%    |
| Acidanthera         | 1        | 1.3%    |
| Acer                | 1        | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 4        | 5.19%   |
| Dell OptiPlex 790                  | 2        | 2.6%    |
| ASUS PRIME X570-PRO                | 2        | 2.6%    |
| ASUS M4A785-M                      | 2        | 2.6%    |
| System76 Thelio                    | 1        | 1.3%    |
| Pegatron FL368AA-UUZ SR5612CH      | 1        | 1.3%    |
| Packard Bell IMEDIA S3220          | 1        | 1.3%    |
| MSI MS-7A57                        | 1        | 1.3%    |
| MSI MS-7752                        | 1        | 1.3%    |
| Medion MD34207/C746                | 1        | 1.3%    |
| Lenovo ThinkCentre M93p 10A8S45S00 | 1        | 1.3%    |
| Intel DQ965GF HD/FP Audio          | 1        | 1.3%    |
| IBM 8188PPV                        | 1        | 1.3%    |
| HP Z620 Workstation                | 1        | 1.3%    |
| HP Z2 Tower G4 Workstation         | 1        | 1.3%    |
| HP ProDesk 600 G1 SFF              | 1        | 1.3%    |
| HP Compaq Pro 6305 SFF             | 1        | 1.3%    |
| HP Compaq Elite 8300 CMT           | 1        | 1.3%    |
| HP Compaq dc7600 Small Form Factor | 1        | 1.3%    |
| HP Compaq 8200 Elite SFF PC        | 1        | 1.3%    |
| HP Compaq 8100 Elite SFF PC        | 1        | 1.3%    |
| HP Compaq 6200 Pro MT PC           | 1        | 1.3%    |
| HP Compaq 6005 Pro MT PC           | 1        | 1.3%    |
| Gigabyte X79S-UP5                  | 1        | 1.3%    |
| Gigabyte X570 AORUS ELITE WIFI     | 1        | 1.3%    |
| Gigabyte H170-HD3-CF               | 1        | 1.3%    |
| Gigabyte GA-MA770-DS3              | 1        | 1.3%    |
| Gigabyte F2A78M-HD2                | 1        | 1.3%    |
| Gigabyte B550M DS3H                | 1        | 1.3%    |
| Gigabyte B450M S2H                 | 1        | 1.3%    |
| Gigabyte B450 I AORUS PRO WIFI     | 1        | 1.3%    |
| Gigabyte B150M-D2V DDR3            | 1        | 1.3%    |
| Gigabyte A520M H                   | 1        | 1.3%    |
| Gigabyte A320M-S2H                 | 1        | 1.3%    |
| Fujitsu TERRA_PC                   | 1        | 1.3%    |
| Fujitsu ESPRIMO P420               | 1        | 1.3%    |
| Fujitsu ESPRIMO G558               | 1        | 1.3%    |
| Fujitsu ESPRIMO E720               | 1        | 1.3%    |
| Foxconn Pro3500 Series             | 1        | 1.3%    |
| ECS LIVA One H410                  | 1        | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 9        | 11.69%  |
| HP Compaq              | 7        | 9.09%   |
| ASUS All               | 4        | 5.19%   |
| Fujitsu ESPRIMO        | 3        | 3.9%    |
| ASUS ROG               | 3        | 3.9%    |
| Dell Precision         | 2        | 2.6%    |
| ASUS TUF               | 2        | 2.6%    |
| ASUS PRIME             | 2        | 2.6%    |
| ASUS P8P67             | 2        | 2.6%    |
| ASUS M4A785-M          | 2        | 2.6%    |
| System76 Thelio        | 1        | 1.3%    |
| Pegatron FL368AA-UUZ   | 1        | 1.3%    |
| Packard Bell IMEDIA    | 1        | 1.3%    |
| MSI MS-7A57            | 1        | 1.3%    |
| MSI MS-7752            | 1        | 1.3%    |
| Medion MD34207         | 1        | 1.3%    |
| Lenovo ThinkCentre     | 1        | 1.3%    |
| Intel DQ965GF          | 1        | 1.3%    |
| IBM 8188PPV            | 1        | 1.3%    |
| HP Z620                | 1        | 1.3%    |
| HP Z2                  | 1        | 1.3%    |
| HP ProDesk             | 1        | 1.3%    |
| Gigabyte X79S-UP5      | 1        | 1.3%    |
| Gigabyte X570          | 1        | 1.3%    |
| Gigabyte H170-HD3-CF   | 1        | 1.3%    |
| Gigabyte GA-MA770-DS3  | 1        | 1.3%    |
| Gigabyte F2A78M-HD2    | 1        | 1.3%    |
| Gigabyte B550M         | 1        | 1.3%    |
| Gigabyte B450M         | 1        | 1.3%    |
| Gigabyte B450          | 1        | 1.3%    |
| Gigabyte B150M-D2V     | 1        | 1.3%    |
| Gigabyte A520M         | 1        | 1.3%    |
| Gigabyte A320M-S2H     | 1        | 1.3%    |
| Fujitsu TERRA          | 1        | 1.3%    |
| Foxconn Pro3500        | 1        | 1.3%    |
| ECS LIVA               | 1        | 1.3%    |
| DEPO Computers MS-7846 | 1        | 1.3%    |
| Dell Inspiron          | 1        | 1.3%    |
| AZW GK35               | 1        | 1.3%    |
| ASUS P6T               | 1        | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 10       | 12.99%  |
| 2019 | 7        | 9.09%   |
| 2018 | 7        | 9.09%   |
| 2020 | 6        | 7.79%   |
| 2014 | 6        | 7.79%   |
| 2011 | 6        | 7.79%   |
| 2012 | 5        | 6.49%   |
| 2009 | 5        | 6.49%   |
| 2017 | 4        | 5.19%   |
| 2015 | 4        | 5.19%   |
| 2010 | 4        | 5.19%   |
| 2016 | 3        | 3.9%    |
| 2008 | 3        | 3.9%    |
| 2005 | 3        | 3.9%    |
| 2021 | 2        | 2.6%    |
| 2007 | 2        | 2.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 77       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 76       | 98.7%   |
| Enabled  | 1        | 1.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 19       | 24.68%  |
| 8.01-16.0   | 16       | 20.78%  |
| 4.01-8.0    | 13       | 16.88%  |
| 32.01-64.0  | 9        | 11.69%  |
| 64.01-256.0 | 8        | 10.39%  |
| 3.01-4.0    | 7        | 9.09%   |
| 1.01-2.0    | 3        | 3.9%    |
| 24.01-32.0  | 1        | 1.3%    |
| 2.01-3.0    | 1        | 1.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 27       | 34.62%  |
| 4.01-8.0   | 17       | 21.79%  |
| 2.01-3.0   | 15       | 19.23%  |
| 8.01-16.0  | 8        | 10.26%  |
| 3.01-4.0   | 7        | 8.97%   |
| 0.51-1.0   | 3        | 3.85%   |
| 24.01-32.0 | 1        | 1.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 40.26%  |
| 2      | 29       | 37.66%  |
| 3      | 7        | 9.09%   |
| 4      | 3        | 3.9%    |
| 7      | 2        | 2.6%    |
| 5      | 2        | 2.6%    |
| 16     | 1        | 1.3%    |
| 11     | 1        | 1.3%    |
| 10     | 1        | 1.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 49       | 63.64%  |
| No        | 28       | 36.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 77       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 55.84%  |
| Yes       | 34       | 44.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 74.03%  |
| Yes       | 20       | 25.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 19       | 24.68%  |
| Germany                | 12       | 15.58%  |
| France                 | 10       | 12.99%  |
| Italy                  | 6        | 7.79%   |
| Brazil                 | 5        | 6.49%   |
| Belgium                | 3        | 3.9%    |
| Austria                | 3        | 3.9%    |
| UK                     | 2        | 2.6%    |
| Sweden                 | 2        | 2.6%    |
| Spain                  | 2        | 2.6%    |
| Russia                 | 2        | 2.6%    |
| Australia              | 2        | 2.6%    |
| Switzerland            | 1        | 1.3%    |
| Romania                | 1        | 1.3%    |
| Norway                 | 1        | 1.3%    |
| Netherlands            | 1        | 1.3%    |
| Mexico                 | 1        | 1.3%    |
| Kenya                  | 1        | 1.3%    |
| Guatemala              | 1        | 1.3%    |
| Bosnia and Herzegovina | 1        | 1.3%    |
| Argentina              | 1        | 1.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Paris                   | 3        | 3.85%   |
| Houston                 | 3        | 3.85%   |
| Stockholm               | 2        | 2.56%   |
| Zanesville              | 1        | 1.28%   |
| Wildenfels              | 1        | 1.28%   |
| West Mifflin            | 1        | 1.28%   |
| Villefontaine           | 1        | 1.28%   |
| Vienna                  | 1        | 1.28%   |
| Turin                   | 1        | 1.28%   |
| Tilburg                 | 1        | 1.28%   |
| Stuttgart               | 1        | 1.28%   |
| Sherman Oaks            | 1        | 1.28%   |
| Sarajevo                | 1        | 1.28%   |
| Sao Paulo               | 1        | 1.28%   |
| Santa Barbara d'Oeste   | 1        | 1.28%   |
| San Secondo di Pinerolo | 1        | 1.28%   |
| Saint-Ouen-l'Aumone     | 1        | 1.28%   |
| Rio Grande da Serra     | 1        | 1.28%   |
| Rennes                  | 1        | 1.28%   |
| Potsdam                 | 1        | 1.28%   |
| Philadelphia            | 1        | 1.28%   |
| Perth                   | 1        | 1.28%   |
| Palermo                 | 1        | 1.28%   |
| Oslo                    | 1        | 1.28%   |
| Olympia                 | 1        | 1.28%   |
| Oldenburg               | 1        | 1.28%   |
| Naumburg                | 1        | 1.28%   |
| Namur                   | 1        | 1.28%   |
| Nairobi                 | 1        | 1.28%   |
| Münster                | 1        | 1.28%   |
| Munich                  | 1        | 1.28%   |
| Moscow                  | 1        | 1.28%   |
| Modesto                 | 1        | 1.28%   |
| Miami                   | 1        | 1.28%   |
| Mérida                 | 1        | 1.28%   |
| Merced                  | 1        | 1.28%   |
| Mediglia                | 1        | 1.28%   |
| Maule                   | 1        | 1.28%   |
| Manchester              | 1        | 1.28%   |
| Maidenhead              | 1        | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 25       | 32     | 17.61%  |
| Seagate               | 24       | 46     | 16.9%   |
| Samsung Electronics   | 23       | 33     | 16.2%   |
| Toshiba               | 9        | 10     | 6.34%   |
| SanDisk               | 9        | 10     | 6.34%   |
| Hitachi               | 6        | 7      | 4.23%   |
| Crucial               | 6        | 6      | 4.23%   |
| Kingston              | 4        | 4      | 2.82%   |
| HGST                  | 4        | 5      | 2.82%   |
| Intenso               | 3        | 3      | 2.11%   |
| Team                  | 2        | 2      | 1.41%   |
| SPCC                  | 2        | 2      | 1.41%   |
| Intel                 | 2        | 2      | 1.41%   |
| Corsair               | 2        | 3      | 1.41%   |
| ASMT                  | 2        | 2      | 1.41%   |
| A-DATA Technology     | 2        | 2      | 1.41%   |
| USB 3.0               | 1        | 2      | 0.7%    |
| TO Exter              | 1        | 1      | 0.7%    |
| Realtek Semiconductor | 1        | 1      | 0.7%    |
| Phison Electronics    | 1        | 1      | 0.7%    |
| Phison                | 1        | 1      | 0.7%    |
| Patriot               | 1        | 1      | 0.7%    |
| OCZ                   | 1        | 1      | 0.7%    |
| NGFF                  | 1        | 1      | 0.7%    |
| Micron Technology     | 1        | 1      | 0.7%    |
| Maxtor                | 1        | 1      | 0.7%    |
| Leven                 | 1        | 1      | 0.7%    |
| JMicron Technology    | 1        | 1      | 0.7%    |
| Integral              | 1        | 1      | 0.7%    |
| Fujitsu               | 1        | 1      | 0.7%    |
| China                 | 1        | 1      | 0.7%    |
| BHT                   | 1        | 1      | 0.7%    |
| Apple                 | 1        | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 4        | 2.41%   |
| Seagate ST2000DM001-1ER164 2TB  | 4        | 2.41%   |
| WDC WDS200T2B0A-00SM50 2TB SSD  | 2        | 1.2%    |
| Toshiba HDWD130 3TB             | 2        | 1.2%    |
| Toshiba DT01ACA050 500GB        | 2        | 1.2%    |
| Team T253X6001T 1TB SSD         | 2        | 1.2%    |
| SPCC Solid State Disk 256GB     | 2        | 1.2%    |
| Seagate ST5000LM000-2AN170 5TB  | 2        | 1.2%    |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 1.2%    |
| Seagate Expansion 1TB           | 2        | 1.2%    |
| SanDisk SDSSDA240G 240GB        | 2        | 1.2%    |
| Samsung SSD 970 EVO Plus 500GB  | 2        | 1.2%    |
| Samsung SSD 870 EVO 1TB         | 2        | 1.2%    |
| Samsung SSD 860 EVO 1TB         | 2        | 1.2%    |
| Samsung SSD 850 EVO 500GB       | 2        | 1.2%    |
| Samsung HD753LJ 752GB           | 2        | 1.2%    |
| Crucial CT500MX500SSD1 500GB    | 2        | 1.2%    |
| Crucial CT1000MX500SSD1 1TB     | 2        | 1.2%    |
| WDC WDS512G1X0C-00ENX0 512GB    | 1        | 0.6%    |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 0.6%    |
| WDC WD5000BPKT-60PK4T0 500GB    | 1        | 0.6%    |
| WDC WD5000AVDS-63U7B1 500GB     | 1        | 0.6%    |
| WDC WD5000AAKS-75V0A0 500GB     | 1        | 0.6%    |
| WDC WD40EZRZ-00GXCB0 4TB        | 1        | 0.6%    |
| WDC WD40EFRX-68N32N0 4TB        | 1        | 0.6%    |
| WDC WD40EFAX-68JH4N1 4TB        | 1        | 0.6%    |
| WDC WD40EFAX-68JH4N0 4TB        | 1        | 0.6%    |
| WDC WD3200BPVT-75JJ5T0 320GB    | 1        | 0.6%    |
| WDC WD3200BEVT-22ZCT0 320GB     | 1        | 0.6%    |
| WDC WD3200AAKS-00VYA0 320GB     | 1        | 0.6%    |
| WDC WD30EZRZ-00Z5HB0 3TB        | 1        | 0.6%    |
| WDC WD30EZRX-00SPEB0 3TB        | 1        | 0.6%    |
| WDC WD2500AAKX-001CA0 250GB     | 1        | 0.6%    |
| WDC WD20PURZ-85GU6Y0 2TB        | 1        | 0.6%    |
| WDC WD20EZRX-00D8PB0 2TB        | 1        | 0.6%    |
| WDC WD20EZAZ-00GGJB0 2TB        | 1        | 0.6%    |
| WDC WD1600AAJS-60Z0A0 160GB     | 1        | 0.6%    |
| WDC WD1600AAJS-08L7A0 160GB     | 1        | 0.6%    |
| WDC WD10EZEX-22RKKA0 1TB        | 1        | 0.6%    |
| WDC WD10EZEX-22MFCA0 1TB        | 1        | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 24       | 45     | 33.8%   |
| WDC                 | 22       | 29     | 30.99%  |
| Toshiba             | 9        | 10     | 12.68%  |
| Hitachi             | 6        | 7      | 8.45%   |
| HGST                | 4        | 5      | 5.63%   |
| Samsung Electronics | 3        | 3      | 4.23%   |
| USB 3.0             | 1        | 2      | 1.41%   |
| Maxtor              | 1        | 1      | 1.41%   |
| Fujitsu             | 1        | 1      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 18     | 23.21%  |
| SanDisk             | 9        | 10     | 16.07%  |
| Crucial             | 6        | 6      | 10.71%  |
| Kingston            | 4        | 4      | 7.14%   |
| Intenso             | 3        | 3      | 5.36%   |
| WDC                 | 2        | 2      | 3.57%   |
| Team                | 2        | 2      | 3.57%   |
| SPCC                | 2        | 2      | 3.57%   |
| ASMT                | 2        | 2      | 3.57%   |
| A-DATA Technology   | 2        | 2      | 3.57%   |
| TO Exter            | 1        | 1      | 1.79%   |
| Patriot             | 1        | 1      | 1.79%   |
| OCZ                 | 1        | 1      | 1.79%   |
| NGFF                | 1        | 1      | 1.79%   |
| Micron Technology   | 1        | 1      | 1.79%   |
| Leven               | 1        | 1      | 1.79%   |
| JMicron Technology  | 1        | 1      | 1.79%   |
| Integral            | 1        | 1      | 1.79%   |
| Corsair             | 1        | 1      | 1.79%   |
| China               | 1        | 1      | 1.79%   |
| BHT                 | 1        | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 51       | 103    | 45.95%  |
| SSD     | 44       | 62     | 39.64%  |
| NVMe    | 15       | 21     | 13.51%  |
| Unknown | 1        | 1      | 0.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 73       | 153    | 76.84%  |
| NVMe | 15       | 21     | 15.79%  |
| SAS  | 7        | 13     | 7.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 50       | 70     | 44.64%  |
| 0.51-1.0   | 35       | 45     | 31.25%  |
| 1.01-2.0   | 12       | 15     | 10.71%  |
| 3.01-4.0   | 6        | 8      | 5.36%   |
| 4.01-10.0  | 6        | 23     | 5.36%   |
| 2.01-3.0   | 3        | 4      | 2.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 20       | 25.64%  |
| 501-1000       | 16       | 20.51%  |
| 1001-2000      | 14       | 17.95%  |
| More than 3000 | 12       | 15.38%  |
| 251-500        | 8        | 10.26%  |
| 51-100         | 4        | 5.13%   |
| 21-50          | 2        | 2.56%   |
| 2001-3000      | 1        | 1.28%   |
| 1-20           | 1        | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 21       | 26.58%  |
| 21-50          | 13       | 16.46%  |
| 101-250        | 10       | 12.66%  |
| 251-500        | 8        | 10.13%  |
| More than 3000 | 7        | 8.86%   |
| 51-100         | 6        | 7.59%   |
| 1001-2000      | 5        | 6.33%   |
| 501-1000       | 5        | 6.33%   |
| 2001-3000      | 4        | 5.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 3        | 3      | 15%     |
| Samsung Electronics HD753LJ 752GB     | 2        | 2      | 10%     |
| WDC WD5000AVDS-63U7B1 500GB           | 1        | 1      | 5%      |
| WDC WD1600AAJS-08L7A0 160GB           | 1        | 1      | 5%      |
| WDC WD10EZEX-22BN5A0 1TB              | 1        | 1      | 5%      |
| Toshiba MQ01ABF050 500GB              | 1        | 1      | 5%      |
| Toshiba HDWE140 4TB                   | 1        | 1      | 5%      |
| Seagate ST8000DM004-2CX1 8TB          | 1        | 6      | 5%      |
| Seagate ST3320820AS 320GB             | 1        | 1      | 5%      |
| Seagate ST3200822AS 200GB             | 1        | 1      | 5%      |
| Seagate ST1000VM002-9ZL162 1TB        | 1        | 1      | 5%      |
| Samsung Electronics SSD 960 PRO 512GB | 1        | 1      | 5%      |
| Samsung Electronics SSD 870 EVO 1TB   | 1        | 2      | 5%      |
| Hitachi HDS5C1010CLA382 1TB           | 1        | 1      | 5%      |
| HGST HTS721010A9 1TB                  | 1        | 1      | 5%      |
| A-DATA Technology SU650 240GB SSD     | 1        | 1      | 5%      |
| A-DATA Technology SP550 240GB SSD     | 1        | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 12     | 35%     |
| Samsung Electronics | 4        | 5      | 20%     |
| WDC                 | 3        | 3      | 15%     |
| Toshiba             | 2        | 2      | 10%     |
| A-DATA Technology   | 2        | 2      | 10%     |
| Hitachi             | 1        | 1      | 5%      |
| HGST                | 1        | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 12     | 43.75%  |
| WDC                 | 3        | 3      | 18.75%  |
| Toshiba             | 2        | 2      | 12.5%   |
| Samsung Electronics | 2        | 2      | 12.5%   |
| Hitachi             | 1        | 1      | 6.25%   |
| HGST                | 1        | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 21     | 78.95%  |
| SSD  | 3        | 4      | 15.79%  |
| NVMe | 1        | 1      | 5.26%   |

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
| Works    | 71       | 145    | 71%     |
| Malfunc  | 19       | 26     | 19%     |
| Detected | 8        | 14     | 8%      |
| Failed   | 2        | 2      | 2%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 52       | 48.6%   |
| AMD                       | 21       | 19.63%  |
| Samsung Electronics       | 9        | 8.41%   |
| Marvell Technology Group  | 5        | 4.67%   |
| ASMedia Technology        | 5        | 4.67%   |
| Phison Electronics        | 3        | 2.8%    |
| Nvidia                    | 3        | 2.8%    |
| JMicron Technology        | 2        | 1.87%   |
| VIA Technologies          | 1        | 0.93%   |
| Silicon Image             | 1        | 0.93%   |
| SanDisk                   | 1        | 0.93%   |
| Realtek Semiconductor     | 1        | 0.93%   |
| LSI Logic / Symbios Logic | 1        | 0.93%   |
| Apple                     | 1        | 0.93%   |
| Adaptec                   | 1        | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11       | 8.03%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11       | 8.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7        | 5.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6        | 4.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 3.65%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 3.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4        | 2.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 2.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 2.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4        | 2.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4        | 2.92%   |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 2.92%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.46%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2        | 1.46%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2        | 1.46%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2        | 1.46%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.46%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.46%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.46%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2        | 1.46%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 1.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 1.46%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 1.46%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 0.73%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.73%   |
| SanDisk WD Black NVMe SSD                                                      | 1        | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.73%   |
| Realtek NVMe Controller                                                        | 1        | 0.73%   |
| Phison E12 NVMe Controller                                                     | 1        | 0.73%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.73%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.73%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                        | 1        | 0.73%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.73%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1        | 0.73%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 1        | 0.73%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1        | 0.73%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 0.73%   |
| JMicron JMB362 SATA Controller                                                 | 1        | 0.73%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1        | 0.73%   |
| Intel NVMe Optane Memory Series                                                | 1        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 63       | 58.88%  |
| IDE  | 21       | 19.63%  |
| NVMe | 15       | 14.02%  |
| RAID | 4        | 3.74%   |
| SAS  | 3        | 2.8%    |
| SCSI | 1        | 0.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 53       | 68.83%  |
| AMD    | 24       | 31.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz       | 3        | 3.9%    |
| Intel Core i5-3470 CPU @ 3.20GHz       | 3        | 3.9%    |
| Intel Core i7-4790 CPU @ 3.60GHz       | 2        | 2.6%    |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2        | 2.6%    |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2        | 2.6%    |
| Intel Core i5-4440 CPU @ 3.10GHz       | 2        | 2.6%    |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 2.6%    |
| AMD Ryzen 9 3950X 16-Core Processor    | 2        | 2.6%    |
| AMD Ryzen 9 3900X 12-Core Processor    | 2        | 2.6%    |
| AMD Ryzen 5 5600G with Radeon Graphics | 2        | 2.6%    |
| AMD Phenom II X4 945 Processor         | 2        | 2.6%    |
| Intel Xeon W-2150B CPU @ 3.00GHz       | 1        | 1.3%    |
| Intel Xeon CPU E5420 @ 2.50GHz         | 1        | 1.3%    |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz    | 1        | 1.3%    |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz     | 1        | 1.3%    |
| Intel Pentium D CPU 3.40GHz            | 1        | 1.3%    |
| Intel Pentium CPU G3220 @ 3.00GHz      | 1        | 1.3%    |
| Intel Pentium 4 CPU 3.20GHz            | 1        | 1.3%    |
| Intel Pentium 4 CPU 2.80GHz            | 1        | 1.3%    |
| Intel Core i9-9900K CPU @ 3.60GHz      | 1        | 1.3%    |
| Intel Core i9-10900K CPU @ 3.70GHz     | 1        | 1.3%    |
| Intel Core i9-10900 CPU @ 2.80GHz      | 1        | 1.3%    |
| Intel Core i7-9700 CPU @ 3.00GHz       | 1        | 1.3%    |
| Intel Core i7-7700K CPU @ 4.20GHz      | 1        | 1.3%    |
| Intel Core i7-4770K CPU @ 3.50GHz      | 1        | 1.3%    |
| Intel Core i7-3930K CPU @ 3.20GHz      | 1        | 1.3%    |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 1.3%    |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1        | 1.3%    |
| Intel Core i7 CPU 930 @ 2.80GHz        | 1        | 1.3%    |
| Intel Core i5-9400T CPU @ 1.80GHz      | 1        | 1.3%    |
| Intel Core i5-8600K CPU @ 3.60GHz      | 1        | 1.3%    |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1        | 1.3%    |
| Intel Core i5-6400 CPU @ 2.70GHz       | 1        | 1.3%    |
| Intel Core i5-4570 CPU @ 3.20GHz       | 1        | 1.3%    |
| Intel Core i5-3330 CPU @ 3.00GHz       | 1        | 1.3%    |
| Intel Core i5-2500K CPU @ 3.30GHz      | 1        | 1.3%    |
| Intel Core i5 CPU 650 @ 3.20GHz        | 1        | 1.3%    |
| Intel Core i3-6100T CPU @ 3.20GHz      | 1        | 1.3%    |
| Intel Core i3-6100 CPU @ 3.70GHz       | 1        | 1.3%    |
| Intel Core i3-4340 CPU @ 3.60GHz       | 1        | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 20       | 25.97%  |
| Intel Core i7          | 11       | 14.29%  |
| Intel Core i3          | 8        | 10.39%  |
| Intel Xeon             | 4        | 5.19%   |
| AMD Ryzen 9            | 4        | 5.19%   |
| AMD Phenom II X4       | 4        | 5.19%   |
| Intel Core i9          | 3        | 3.9%    |
| AMD Ryzen 5            | 3        | 3.9%    |
| Intel Pentium 4        | 2        | 2.6%    |
| AMD Ryzen 7            | 2        | 2.6%    |
| AMD Athlon II X2       | 2        | 2.6%    |
| Intel Pentium D        | 1        | 1.3%    |
| Intel Pentium          | 1        | 1.3%    |
| Intel Core 2 Duo       | 1        | 1.3%    |
| Intel Core 2           | 1        | 1.3%    |
| Intel Celeron          | 1        | 1.3%    |
| AMD Ryzen Threadripper | 1        | 1.3%    |
| AMD Ryzen 3            | 1        | 1.3%    |
| AMD FX                 | 1        | 1.3%    |
| AMD E                  | 1        | 1.3%    |
| AMD Athlon X4          | 1        | 1.3%    |
| AMD Athlon Dual Core   | 1        | 1.3%    |
| AMD Athlon 64 X2       | 1        | 1.3%    |
| AMD A4                 | 1        | 1.3%    |
| AMD A10                | 1        | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 34       | 44.16%  |
| 2      | 19       | 24.68%  |
| 6      | 8        | 10.39%  |
| 8      | 5        | 6.49%   |
| 10     | 3        | 3.9%    |
| 1      | 3        | 3.9%    |
| 16     | 2        | 2.6%    |
| 12     | 2        | 2.6%    |
| 32     | 1        | 1.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 76       | 98.7%   |
| 2      | 1        | 1.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 41       | 53.25%  |
| 1      | 36       | 46.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 76       | 98.7%   |
| 32-bit         | 1        | 1.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 12       | 15.58%  |
| Unknown    | 10       | 12.99%  |
| 0x306a9    | 6        | 7.79%   |
| 0x206a7    | 6        | 7.79%   |
| 0x506e3    | 4        | 5.19%   |
| 0x08701021 | 4        | 5.19%   |
| 0x906ea    | 3        | 3.9%    |
| 0x010000c8 | 3        | 3.9%    |
| 0xf41      | 2        | 2.6%    |
| 0xa0655    | 2        | 2.6%    |
| 0x906ed    | 2        | 2.6%    |
| 0x206d7    | 2        | 2.6%    |
| 0x10676    | 2        | 2.6%    |
| 0x0a50000d | 2        | 2.6%    |
| 0x010000b6 | 2        | 2.6%    |
| 0xf65      | 1        | 1.3%    |
| 0x6f6      | 1        | 1.3%    |
| 0x506ca    | 1        | 1.3%    |
| 0x50654    | 1        | 1.3%    |
| 0x306f2    | 1        | 1.3%    |
| 0x20655    | 1        | 1.3%    |
| 0x106a5    | 1        | 1.3%    |
| 0x0a201009 | 1        | 1.3%    |
| 0x08301039 | 1        | 1.3%    |
| 0x08108109 | 1        | 1.3%    |
| 0x08101016 | 1        | 1.3%    |
| 0x06003106 | 1        | 1.3%    |
| 0x06001119 | 1        | 1.3%    |
| 0x06000852 | 1        | 1.3%    |
| 0x010000c7 | 1        | 1.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 13       | 16.88%  |
| SandyBridge | 8        | 10.39%  |
| Zen 2       | 7        | 9.09%   |
| Skylake     | 7        | 9.09%   |
| IvyBridge   | 7        | 9.09%   |
| KabyLake    | 6        | 7.79%   |
| K10         | 6        | 7.79%   |
| Zen 3       | 3        | 3.9%    |
| NetBurst    | 3        | 3.9%    |
| Westmere    | 2        | 2.6%    |
| Piledriver  | 2        | 2.6%    |
| Penryn      | 2        | 2.6%    |
| K8 Hammer   | 2        | 2.6%    |
| CometLake   | 2        | 2.6%    |
| Zen+        | 1        | 1.3%    |
| Zen         | 1        | 1.3%    |
| Steamroller | 1        | 1.3%    |
| Nehalem     | 1        | 1.3%    |
| Goldmont    | 1        | 1.3%    |
| Excavator   | 1        | 1.3%    |
| Core        | 1        | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 37       | 44.58%  |
| Intel  | 27       | 32.53%  |
| AMD    | 19       | 22.89%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 8.33%   |
| Intel HD Graphics 530                                                       | 4        | 4.76%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 3.57%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.57%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 3.57%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.57%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.38%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 2.38%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 2.38%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 2.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.38%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.38%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 2.38%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 2.38%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.38%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.19%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1        | 1.19%   |
| Nvidia GT216 [GeForce 315]                                                  | 1        | 1.19%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.19%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.19%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.19%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.19%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.19%   |
| Nvidia GK208 [GeForce GT 720]                                               | 1        | 1.19%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 1.19%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.19%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.19%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.19%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.19%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 1.19%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.19%   |
| Nvidia G98 [Quadro NVS 450]                                                 | 1        | 1.19%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.19%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.19%   |
| Nvidia C77 [GeForce 8200]                                                   | 1        | 1.19%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 1.19%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.19%   |
| Intel HD Graphics 630                                                       | 1        | 1.19%   |
| Intel HD Graphics 500                                                       | 1        | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 33       | 42.86%  |
| 1 x Intel      | 22       | 28.57%  |
| 1 x AMD        | 18       | 23.38%  |
| Intel + Nvidia | 2        | 2.6%    |
| 2 x Nvidia     | 1        | 1.3%    |
| AMD + Nvidia   | 1        | 1.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 55       | 70.51%  |
| Proprietary | 23       | 29.49%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 33.33%  |
| 1.01-2.0   | 12       | 15.38%  |
| 0.01-0.5   | 12       | 15.38%  |
| 0.51-1.0   | 10       | 12.82%  |
| 3.01-4.0   | 6        | 7.69%   |
| 7.01-8.0   | 4        | 5.13%   |
| 8.01-16.0  | 4        | 5.13%   |
| 5.01-6.0   | 2        | 2.56%   |
| 2.01-3.0   | 1        | 1.28%   |
| 16.01-24.0 | 1        | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 14.94%  |
| Goldstar             | 10       | 11.49%  |
| Dell                 | 9        | 10.34%  |
| Philips              | 8        | 9.2%    |
| Acer                 | 8        | 9.2%    |
| Hewlett-Packard      | 7        | 8.05%   |
| Ancor Communications | 5        | 5.75%   |
| AOC                  | 3        | 3.45%   |
| ONN                  | 2        | 2.3%    |
| Fujitsu Siemens      | 2        | 2.3%    |
| Eizo                 | 2        | 2.3%    |
| ViewSonic            | 1        | 1.15%   |
| VIE                  | 1        | 1.15%   |
| Unknown              | 1        | 1.15%   |
| TVT                  | 1        | 1.15%   |
| Targa Visionary      | 1        | 1.15%   |
| Sony                 | 1        | 1.15%   |
| Seiki                | 1        | 1.15%   |
| Onkyo                | 1        | 1.15%   |
| NEC Computers        | 1        | 1.15%   |
| Medion               | 1        | 1.15%   |
| KTC                  | 1        | 1.15%   |
| Iiyama               | 1        | 1.15%   |
| Hannspree            | 1        | 1.15%   |
| DENON                | 1        | 1.15%   |
| BenQ                 | 1        | 1.15%   |
| ASUSTek Computer     | 1        | 1.15%   |
| Apple                | 1        | 1.15%   |
| Unknown              | 1        | 1.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                    | 2        | 2.08%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 2        | 2.08%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch              | 1        | 1.04%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                   | 1        | 1.04%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                   | 1        | 1.04%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                          | 1        | 1.04%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch     | 1        | 1.04%   |
| Sony TV *00 SNY8004 3840x2160 1085x610mm 49.0-inch                      | 1        | 1.04%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                     | 1        | 1.04%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1        | 1.04%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1        | 1.04%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch    | 1        | 1.04%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch    | 1        | 1.04%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch     | 1        | 1.04%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch    | 1        | 1.04%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch    | 1        | 1.04%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch    | 1        | 1.04%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch    | 1        | 1.04%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch     | 1        | 1.04%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch     | 1        | 1.04%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch      | 1        | 1.04%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1        | 1.04%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch    | 1        | 1.04%   |
| Samsung Electronics LCD Monitor SyncMaster                              | 1        | 1.04%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 1.04%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch    | 1        | 1.04%   |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch       | 1        | 1.04%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch               | 1        | 1.04%   |
| Philips PHL 278E8Q PHLC161 1920x1080 598x336mm 27.0-inch                | 1        | 1.04%   |
| Philips PHL 244E5 PHLC0C0 1920x1080 527x296mm 23.8-inch                 | 1        | 1.04%   |
| Philips 227E4LH PHLC0AC 1920x1080 477x268mm 21.5-inch                   | 1        | 1.04%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 1        | 1.04%   |
| Philips 201E PHLC033 1600x900 443x249mm 20.0-inch                       | 1        | 1.04%   |
| Philips 190V PHL0847 1280x1024 376x301mm 19.0-inch                      | 1        | 1.04%   |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                      | 1        | 1.04%   |
| Onkyo HT-R494 ONK0F43 3840x2160 1150x650mm 52.0-inch                    | 1        | 1.04%   |
| NEC Computers LCD2180UX NEC662C 1600x1200 430x320mm 21.1-inch           | 1        | 1.04%   |
| Medion MD32119PR MED89C1 1280x1024 376x301mm 19.0-inch                  | 1        | 1.04%   |
| KTC H-W2206S-D KTC2203 1680x1050 433x270mm 20.1-inch                    | 1        | 1.04%   |
| Iiyama PL2435M IVM6112 1920x1080 521x293mm 23.5-inch                    | 1        | 1.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 39       | 45.88%  |
| 3840x2160 (4K)     | 10       | 11.76%  |
| 1280x1024 (SXGA)   | 9        | 10.59%  |
| 1680x1050 (WSXGA+) | 5        | 5.88%   |
| 1920x1200 (WUXGA)  | 4        | 4.71%   |
| 1440x900 (WXGA+)   | 3        | 3.53%   |
| 1366x768 (WXGA)    | 3        | 3.53%   |
| 2560x1440 (QHD)    | 2        | 2.35%   |
| 1600x900 (HD+)     | 2        | 2.35%   |
| 1360x768           | 2        | 2.35%   |
| Unknown            | 2        | 2.35%   |
| 5760x2160          | 1        | 1.18%   |
| 3280x1080          | 1        | 1.18%   |
| 1600x1200          | 1        | 1.18%   |
| 1400x1050          | 1        | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 13       | 14.94%  |
| 21      | 13       | 14.94%  |
| 27      | 11       | 12.64%  |
| 24      | 11       | 12.64%  |
| 19      | 7        | 8.05%   |
| 31      | 6        | 6.9%    |
| 22      | 5        | 5.75%   |
| 17      | 5        | 5.75%   |
| 18      | 4        | 4.6%    |
| 20      | 3        | 3.45%   |
| Unknown | 2        | 2.3%    |
| 84      | 1        | 1.15%   |
| 65      | 1        | 1.15%   |
| 52      | 1        | 1.15%   |
| 50      | 1        | 1.15%   |
| 43      | 1        | 1.15%   |
| 32      | 1        | 1.15%   |
| 15      | 1        | 1.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 32       | 38.1%   |
| 401-500     | 26       | 30.95%  |
| 601-700     | 8        | 9.52%   |
| 301-350     | 6        | 7.14%   |
| 351-400     | 4        | 4.76%   |
| 1001-1500   | 3        | 3.57%   |
| Unknown     | 2        | 2.38%   |
| 701-800     | 1        | 1.19%   |
| 1501-2000   | 1        | 1.19%   |
| 901-1000    | 1        | 1.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 54       | 67.5%   |
| 16/10   | 13       | 16.25%  |
| 5/4     | 8        | 10%     |
| 4/3     | 2        | 2.5%    |
| Unknown | 2        | 2.5%    |
| 3/2     | 1        | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 34       | 40.48%  |
| 301-350        | 11       | 13.1%   |
| 151-200        | 11       | 13.1%   |
| 141-150        | 9        | 10.71%  |
| 351-500        | 7        | 8.33%   |
| More than 1000 | 4        | 4.76%   |
| 251-300        | 4        | 4.76%   |
| Unknown        | 2        | 2.38%   |
| 111-120        | 1        | 1.19%   |
| 501-1000       | 1        | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 57       | 71.25%  |
| 101-120 | 16       | 20%     |
| 121-160 | 3        | 3.75%   |
| Unknown | 2        | 2.5%    |
| 1-50    | 1        | 1.25%   |
| 161-240 | 1        | 1.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 54       | 70.13%  |
| 2     | 23       | 29.87%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 42       | 36.21%  |
| Intel                           | 38       | 32.76%  |
| Qualcomm Atheros                | 11       | 9.48%   |
| Broadcom                        | 5        | 4.31%   |
| TP-Link                         | 3        | 2.59%   |
| Nvidia                          | 3        | 2.59%   |
| Broadcom Limited                | 2        | 1.72%   |
| Aquantia                        | 2        | 1.72%   |
| ZyDAS                           | 1        | 0.86%   |
| Wacom                           | 1        | 0.86%   |
| Ralink Technology               | 1        | 0.86%   |
| Qualcomm Atheros Communications | 1        | 0.86%   |
| NetGear                         | 1        | 0.86%   |
| Microsoft                       | 1        | 0.86%   |
| MediaTek                        | 1        | 0.86%   |
| InterBiometrics                 | 1        | 0.86%   |
| Input Club                      | 1        | 0.86%   |
| ASIX Electronics                | 1        | 0.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 35       | 28%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 8%      |
| Intel I211 Gigabit Network Connection                                         | 6        | 4.8%    |
| Intel Ethernet Connection I217-LM                                             | 5        | 4%      |
| Intel Wireless-AC 9260                                                        | 4        | 3.2%    |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.4%    |
| Realtek 802.11ac NIC                                                          | 2        | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 1.6%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2        | 1.6%    |
| Nvidia MCP77 Ethernet                                                         | 2        | 1.6%    |
| Intel Ethernet Connection I217-V                                              | 2        | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 1.6%    |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.6%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 1.6%    |
| ZyDAS ZD1211B 802.11g                                                         | 1        | 0.8%    |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1        | 0.8%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.8%    |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 0.8%    |
| TP-Link 802.11ac NIC                                                          | 1        | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.8%    |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1        | 0.8%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.8%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1        | 0.8%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 0.8%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.8%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.8%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.8%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 0.8%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.8%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 0.8%    |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.8%    |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                   | 1        | 0.8%    |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 0.8%    |
| MediaTek 802.11 n WLAN                                                        | 1        | 0.8%    |
| InterBiometrics Io                                                            | 1        | 0.8%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 9        | 25%     |
| Intel                           | 9        | 25%     |
| Realtek Semiconductor           | 6        | 16.67%  |
| TP-Link                         | 3        | 8.33%   |
| Broadcom                        | 2        | 5.56%   |
| ZyDAS                           | 1        | 2.78%   |
| Wacom                           | 1        | 2.78%   |
| Ralink Technology               | 1        | 2.78%   |
| Qualcomm Atheros Communications | 1        | 2.78%   |
| NetGear                         | 1        | 2.78%   |
| Microsoft                       | 1        | 2.78%   |
| MediaTek                        | 1        | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wireless-AC 9260                                                        | 4        | 11.11%  |
| Realtek 802.11ac NIC                                                          | 2        | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 5.56%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2        | 5.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 5.56%   |
| ZyDAS ZD1211B 802.11g                                                         | 1        | 2.78%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1        | 2.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 2.78%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 2.78%   |
| TP-Link 802.11ac NIC                                                          | 1        | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.78%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1        | 2.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 2.78%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 2.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 2.78%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 2.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 2.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 2.78%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 2.78%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 2.78%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                   | 1        | 2.78%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 2.78%   |
| MediaTek 802.11 n WLAN                                                        | 1        | 2.78%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 2.78%   |
| Intel Wireless 3165                                                           | 1        | 2.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 2.78%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                            | 1        | 2.78%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1        | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 38       | 44.19%  |
| Intel                 | 35       | 40.7%   |
| Nvidia                | 3        | 3.49%   |
| Broadcom              | 3        | 3.49%   |
| Qualcomm Atheros      | 2        | 2.33%   |
| Broadcom Limited      | 2        | 2.33%   |
| Aquantia              | 2        | 2.33%   |
| ASIX Electronics      | 1        | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35       | 40.23%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 11.49%  |
| Intel I211 Gigabit Network Connection                             | 6        | 6.9%    |
| Intel Ethernet Connection I217-LM                                 | 5        | 5.75%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.45%   |
| Nvidia MCP77 Ethernet                                             | 2        | 2.3%    |
| Intel Ethernet Connection I217-V                                  | 2        | 2.3%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.3%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.15%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.15%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.15%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.15%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.15%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.15%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.15%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.15%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.15%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.15%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 1.15%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 1.15%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.15%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.15%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 1.15%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 1.15%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 1.15%   |
| ASIX AX88772B                                                     | 1        | 1.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 77       | 68.14%  |
| WiFi     | 34       | 30.09%  |
| Modem    | 2        | 1.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 69       | 81.18%  |
| WiFi     | 16       | 18.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 63.64%  |
| 2     | 25       | 32.47%  |
| 3     | 3        | 3.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 65       | 83.33%  |
| Yes  | 13       | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 9        | 42.86%  |
| Cambridge Silicon Radio         | 6        | 28.57%  |
| ASUSTek Computer                | 3        | 14.29%  |
| Qualcomm Atheros Communications | 2        | 9.52%   |
| Realtek Semiconductor           | 1        | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 28.57%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 19.05%  |
| Intel Bluetooth wireless interface                  | 2        | 9.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 9.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 9.52%   |
| Realtek Bluetooth Radio                             | 1        | 4.76%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 4.76%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 4.76%   |
| Intel AX210 Bluetooth                               | 1        | 4.76%   |
| ASUS BCM20702A0                                     | 1        | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 48       | 32%     |
| Nvidia                               | 31       | 20.67%  |
| AMD                                  | 26       | 17.33%  |
| Texas Instruments                    | 4        | 2.67%   |
| C-Media Electronics                  | 4        | 2.67%   |
| Yamaha                               | 3        | 2%      |
| JMTek                                | 3        | 2%      |
| PreSonus Audio Electronics           | 2        | 1.33%   |
| M-Audio                              | 2        | 1.33%   |
| Logitech                             | 2        | 1.33%   |
| ZOOM                                 | 1        | 0.67%   |
| Xilinx                               | 1        | 0.67%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.67%   |
| Textech International                | 1        | 0.67%   |
| Tenx Technology                      | 1        | 0.67%   |
| TEAC                                 | 1        | 0.67%   |
| Studiologic                          | 1        | 0.67%   |
| SteelSeries ApS                      | 1        | 0.67%   |
| Samson Technologies                  | 1        | 0.67%   |
| QinHeng Electronics                  | 1        | 0.67%   |
| Plantronics                          | 1        | 0.67%   |
| MIDITECH                             | 1        | 0.67%   |
| Medeli Electronics                   | 1        | 0.67%   |
| Mark of the Unicorn                  | 1        | 0.67%   |
| KTMicro                              | 1        | 0.67%   |
| Harman                               | 1        | 0.67%   |
| Generalplus Technology               | 1        | 0.67%   |
| Focusrite-Novation                   | 1        | 0.67%   |
| Ensoniq                              | 1        | 0.67%   |
| Creative Technology                  | 1        | 0.67%   |
| BEHRINGER International              | 1        | 0.67%   |
| ASUSTek Computer                     | 1        | 0.67%   |
| Apple                                | 1        | 0.67%   |
| Alesis                               | 1        | 0.67%   |
| AKAI Professional M.I.               | 1        | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12       | 6.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 4.07%   |
| AMD Starship/Matisse HD Audio Controller                                          | 7        | 4.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 2.91%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5        | 2.91%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 2.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 2.33%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 2.33%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4        | 2.33%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3        | 1.74%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 1.74%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 1.74%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 1.74%   |
| AMD FCH Azalia Controller                                                         | 3        | 1.74%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.74%   |
| PreSonus Audio Electronics Studio 24c                                             | 2        | 1.16%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 1.16%   |
| Nvidia High Definition Audio Controller                                           | 2        | 1.16%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 1.16%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 1.16%   |
| M-Audio M-Track                                                                   | 2        | 1.16%   |
| JMTek USB PnP Audio Device                                                        | 2        | 1.16%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 1.16%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 2        | 1.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 1.16%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 1.16%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 1.16%   |
| ZOOM U-22                                                                         | 1        | 0.58%   |
| Yamaha YMF-744B [DS-1S Audio Controller]                                          | 1        | 0.58%   |
| Yamaha MG-XU                                                                      | 1        | 0.58%   |
| Yamaha AG06/AG03                                                                  | 1        | 0.58%   |
| Xilinx RME Hammerfall DSP                                                         | 1        | 0.58%   |
| Thesycon Systemsoftware & Consulting USB HiRes Audio                              | 1        | 0.58%   |
| Textech International MIDI Interface cable                                        | 1        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 15       | 15.15%  |
| Kingston            | 14       | 14.14%  |
| Samsung Electronics | 13       | 13.13%  |
| Unknown             | 11       | 11.11%  |
| Corsair             | 10       | 10.1%   |
| Crucial             | 9        | 9.09%   |
| Micron Technology   | 6        | 6.06%   |
| G.Skill             | 6        | 6.06%   |
| Patriot             | 3        | 3.03%   |
| Unifosa             | 1        | 1.01%   |
| Smart               | 1        | 1.01%   |
| S                   | 1        | 1.01%   |
| PNY                 | 1        | 1.01%   |
| OCZ                 | 1        | 1.01%   |
| Nanya Technology    | 1        | 1.01%   |
| M                   | 1        | 1.01%   |
| HBS                 | 1        | 1.01%   |
| Goldkey             | 1        | 1.01%   |
| Elpida              | 1        | 1.01%   |
| Aeneon              | 1        | 1.01%   |
| 0194808980CE        | 1        | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s         | 3        | 2.65%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                     | 2        | 1.77%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                    | 2        | 1.77%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s        | 2        | 1.77%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s         | 2        | 1.77%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s         | 2        | 1.77%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 2        | 1.77%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s       | 2        | 1.77%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s     | 2        | 1.77%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s      | 2        | 1.77%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1        | 0.88%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                   | 1        | 0.88%   |
| Unknown RAM Module 512MB DIMM DDR                           | 1        | 0.88%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s                    | 1        | 0.88%   |
| Unknown RAM Module 256MB DIMM DDR                           | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1        | 0.88%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                    | 1        | 0.88%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1        | 0.88%   |
| Unknown RAM Module 1024MB DIMM DDR                          | 1        | 0.88%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1        | 0.88%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s                 | 1        | 0.88%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s           | 1        | 0.88%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s          | 1        | 0.88%   |
| SK hynix RAM TMT41GU6BFR8C-PBSC 8192MB DIMM DDR3 1600MT/s   | 1        | 0.88%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 0.88%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2666MT/s               | 1        | 0.88%   |
| SK hynix RAM Module 32GB DIMM DDR4 2667MT/s                 | 1        | 0.88%   |
| SK hynix RAM HYMP564U64BP8-C4 512MB DIMM DDR 533MT/s        | 1        | 0.88%   |
| SK hynix RAM HYMP125F72CP8N3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.88%   |
| SK hynix RAM HYMP125F72CP8D3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.88%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s        | 1        | 0.88%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1        | 0.88%   |
| SK hynix RAM HMT351U7CFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1        | 0.88%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s        | 1        | 0.88%   |
| SK hynix RAM HMT325U7CFR8C-PB 2GB DIMM DDR3 1600MT/s        | 1        | 0.88%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s        | 1        | 0.88%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 0.88%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1        | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 38       | 47.5%   |
| DDR4    | 26       | 32.5%   |
| DDR2    | 7        | 8.75%   |
| Unknown | 4        | 5%      |
| DDR     | 3        | 3.75%   |
| SDRAM   | 2        | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 71       | 91.03%  |
| SODIMM  | 5        | 6.41%   |
| RIMM    | 1        | 1.28%   |
| FB-DIMM | 1        | 1.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 26       | 29.21%  |
| 8192  | 22       | 24.72%  |
| 2048  | 13       | 14.61%  |
| 16384 | 10       | 11.24%  |
| 1024  | 8        | 8.99%   |
| 32768 | 7        | 7.87%   |
| 512   | 2        | 2.25%   |
| 256   | 1        | 1.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 25       | 27.47%  |
| 1333    | 10       | 10.99%  |
| 3600    | 5        | 5.49%   |
| 2133    | 5        | 5.49%   |
| 667     | 5        | 5.49%   |
| 1866    | 4        | 4.4%    |
| 1800    | 4        | 4.4%    |
| 1066    | 4        | 4.4%    |
| 3266    | 3        | 3.3%    |
| 3200    | 3        | 3.3%    |
| 2667    | 3        | 3.3%    |
| 800     | 3        | 3.3%    |
| 2933    | 2        | 2.2%    |
| 2400    | 2        | 2.2%    |
| 1867    | 2        | 2.2%    |
| 533     | 2        | 2.2%    |
| Unknown | 2        | 2.2%    |
| 3500    | 1        | 1.1%    |
| 3466    | 1        | 1.1%    |
| 3000    | 1        | 1.1%    |
| 2934    | 1        | 1.1%    |
| 2800    | 1        | 1.1%    |
| 2666    | 1        | 1.1%    |
| 2472    | 1        | 1.1%    |

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
| Logitech                      | 6        | 33.33%  |
| Samsung Electronics           | 2        | 11.11%  |
| Microsoft                     | 2        | 11.11%  |
| Microdia                      | 2        | 11.11%  |
| ViewSonic                     | 1        | 5.56%   |
| Sweex                         | 1        | 5.56%   |
| Sunplus IT                    | 1        | 5.56%   |
| Sunplus Innovation Technology | 1        | 5.56%   |
| Philips (or NXP)              | 1        | 5.56%   |
| MacroSilicon                  | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 2        | 11.11%  |
| Logitech Webcam C270                    | 2        | 11.11%  |
| ViewSonic PC Camera                     | 1        | 5.56%   |
| Sweex WC060 Series HD Webcam            | 1        | 5.56%   |
| Sunplus IT AUKEY PC-LM1 USB Camera      | 1        | 5.56%   |
| Sunplus HD 720P webcam                  | 1        | 5.56%   |
| Philips (or NXP) Webcam SPC530NC        | 1        | 5.56%   |
| Microsoft LifeCam VX-5000               | 1        | 5.56%   |
| Microsoft LifeCam Cinema                | 1        | 5.56%   |
| Microdia MSI Starcam Racer              | 1        | 5.56%   |
| Microdia HoverCam Solo Spark Audio      | 1        | 5.56%   |
| MacroSilicon usb video                  | 1        | 5.56%   |
| Logitech QuickCam Communicate MP/S5500  | 1        | 5.56%   |
| Logitech Portable Webcam C905           | 1        | 5.56%   |
| Logitech HD Webcam C910                 | 1        | 5.56%   |
| Logitech HD Pro Webcam C920             | 1        | 5.56%   |

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
| 0     | 68       | 88.31%  |
| 1     | 8        | 10.39%  |
| 2     | 1        | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 4        | 40%     |
| Sound                    | 2        | 20%     |
| Unassigned class         | 1        | 10%     |
| Modem                    | 1        | 10%     |
| Graphics card            | 1        | 10%     |
| Communication controller | 1        | 10%     |

