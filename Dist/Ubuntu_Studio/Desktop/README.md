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

Total: 93

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming X570-PLUS        | [50ee937fb2](https://linux-hardware.org/?probe=50ee937fb2) | Aug 02, 2023 |
| Shenzhen M... | HX90G                       | [c04f6d6467](https://linux-hardware.org/?probe=c04f6d6467) | Aug 01, 2023 |
| MSI           | PRO B760M-P DDR4            | [6a0b0513cd](https://linux-hardware.org/?probe=6a0b0513cd) | Jul 22, 2023 |
| Gigabyte      | 970A-DS3P                   | [97ebfed554](https://linux-hardware.org/?probe=97ebfed554) | Jul 02, 2023 |
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
| Ubuntu Studio 20.04 | 40       | 48.78%  |
| Ubuntu Studio 22.04 | 22       | 26.83%  |
| Ubuntu Studio 20.10 | 9        | 10.98%  |
| Ubuntu Studio 22.10 | 3        | 3.66%   |
| Ubuntu Studio 21.10 | 3        | 3.66%   |
| Ubuntu Studio 23.04 | 2        | 2.44%   |
| Ubuntu Studio 21.04 | 2        | 2.44%   |
| Ubuntu Studio 16.04 | 1        | 1.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu Studio | 81       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.0-58-lowlatency   | 3        | 3.61%   |
| 5.11.0-44-lowlatency   | 3        | 3.61%   |
| 5.8.0-48-lowlatency    | 2        | 2.41%   |
| 5.8.0-44-lowlatency    | 2        | 2.41%   |
| 5.8.0-25-lowlatency    | 2        | 2.41%   |
| 5.4.0-58-lowlatency    | 2        | 2.41%   |
| 5.4.0-56-lowlatency    | 2        | 2.41%   |
| 5.4.0-42-lowlatency    | 2        | 2.41%   |
| 5.4.0-26-lowlatency    | 2        | 2.41%   |
| 5.19.0-1021-lowlatency | 2        | 2.41%   |
| 5.15.0-71-lowlatency   | 2        | 2.41%   |
| 5.15.0-56-lowlatency   | 2        | 2.41%   |
| 5.15.0-53-lowlatency   | 2        | 2.41%   |
| 5.15.0-52-lowlatency   | 2        | 2.41%   |
| 5.15.0-46-lowlatency   | 2        | 2.41%   |
| 5.13.0-28-lowlatency   | 2        | 2.41%   |
| 6.2.0-1009-lowlatency  | 1        | 1.2%    |
| 6.2.0-1007-lowlatency  | 1        | 1.2%    |
| 5.8.0-50-lowlatency    | 1        | 1.2%    |
| 5.8.0-45-lowlatency    | 1        | 1.2%    |
| 5.8.0-36-lowlatency    | 1        | 1.2%    |
| 5.8.0-34-lowlatency    | 1        | 1.2%    |
| 5.8.0-33-lowlatency    | 1        | 1.2%    |
| 5.8.0-29-lowlatency    | 1        | 1.2%    |
| 5.4.0-99-lowlatency    | 1        | 1.2%    |
| 5.4.0-72-lowlatency    | 1        | 1.2%    |
| 5.4.0-71-lowlatency    | 1        | 1.2%    |
| 5.4.0-70-lowlatency    | 1        | 1.2%    |
| 5.4.0-65-lowlatency    | 1        | 1.2%    |
| 5.4.0-65-generic       | 1        | 1.2%    |
| 5.4.0-64-lowlatency    | 1        | 1.2%    |
| 5.4.0-62-lowlatency    | 1        | 1.2%    |
| 5.4.0-60-lowlatency    | 1        | 1.2%    |
| 5.4.0-53-lowlatency    | 1        | 1.2%    |
| 5.4.0-52-lowlatency    | 1        | 1.2%    |
| 5.4.0-51-lowlatency    | 1        | 1.2%    |
| 5.4.0-48-lowlatency    | 1        | 1.2%    |
| 5.4.0-47-lowlatency    | 1        | 1.2%    |
| 5.4.0-39-lowlatency    | 1        | 1.2%    |
| 5.4.0-33-lowlatency    | 1        | 1.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 31       | 37.8%   |
| 5.15.0  | 22       | 26.83%  |
| 5.8.0   | 12       | 14.63%  |
| 5.11.0  | 6        | 7.32%   |
| 5.19.0  | 4        | 4.88%   |
| 5.13.0  | 3        | 3.66%   |
| 6.2.0   | 2        | 2.44%   |
| 5.15.6  | 1        | 1.22%   |
| 4.4.0   | 1        | 1.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 31       | 37.8%   |
| 5.15    | 23       | 28.05%  |
| 5.8     | 12       | 14.63%  |
| 5.11    | 6        | 7.32%   |
| 5.19    | 4        | 4.88%   |
| 5.13    | 3        | 3.66%   |
| 6.2     | 2        | 2.44%   |
| 4.4     | 1        | 1.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 80       | 98.77%  |
| i686   | 1        | 1.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| XFCE            | 36       | 43.9%   |
| KDE5            | 34       | 41.46%  |
| GNOME           | 5        | 6.1%    |
| MATE            | 2        | 2.44%   |
| LXQt            | 2        | 2.44%   |
| KDE             | 1        | 1.22%   |
| GNOME Flashback | 1        | 1.22%   |
| Cinnamon        | 1        | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 76       | 92.68%  |
| Tty     | 4        | 4.88%   |
| Wayland | 2        | 2.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 32       | 39.51%  |
| TDM     | 25       | 30.86%  |
| LightDM | 17       | 20.99%  |
| GDM     | 6        | 7.41%   |
| GDM3    | 1        | 1.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 32       | 39.51%  |
| de_DE      | 9        | 11.11%  |
| fr_FR      | 8        | 9.88%   |
| en_GB      | 5        | 6.17%   |
| pt_BR      | 4        | 4.94%   |
| it_IT      | 3        | 3.7%    |
| ru_RU      | 2        | 2.47%   |
| en_AU      | 2        | 2.47%   |
| sv_SE      | 1        | 1.23%   |
| nl_NL      | 1        | 1.23%   |
| nl_BE      | 1        | 1.23%   |
| nb_NO      | 1        | 1.23%   |
| fr_FR.UTF8 | 1        | 1.23%   |
| fr_CH      | 1        | 1.23%   |
| fr_BE      | 1        | 1.23%   |
| es_GT      | 1        | 1.23%   |
| es_ES      | 1        | 1.23%   |
| es_AR      | 1        | 1.23%   |
| en_DE      | 1        | 1.23%   |
| en_CA      | 1        | 1.23%   |
| de_AT      | 1        | 1.23%   |
| ca_ES      | 1        | 1.23%   |
| ca_AD      | 1        | 1.23%   |
| C          | 1        | 1.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 48       | 59.26%  |
| EFI  | 33       | 40.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 79       | 97.53%  |
| Xfs  | 1        | 1.23%   |
| Ext2 | 1        | 1.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 42       | 51.85%  |
| MBR  | 39       | 48.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 75.61%  |
| Yes       | 20       | 24.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 56.1%   |
| Yes       | 36       | 43.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 22       | 27.16%  |
| Gigabyte Technology                  | 12       | 14.81%  |
| Dell                                 | 12       | 14.81%  |
| Hewlett-Packard                      | 10       | 12.35%  |
| Fujitsu                              | 4        | 4.94%   |
| MSI                                  | 3        | 3.7%    |
| ASRock                               | 3        | 3.7%    |
| System76                             | 1        | 1.23%   |
| Shenzhen Meigao Electronic Equipment | 1        | 1.23%   |
| Pegatron                             | 1        | 1.23%   |
| Packard Bell                         | 1        | 1.23%   |
| Medion                               | 1        | 1.23%   |
| Lenovo                               | 1        | 1.23%   |
| Intel                                | 1        | 1.23%   |
| IBM                                  | 1        | 1.23%   |
| Foxconn                              | 1        | 1.23%   |
| ECS                                  | 1        | 1.23%   |
| DEPO Computers                       | 1        | 1.23%   |
| AZW                                  | 1        | 1.23%   |
| Apple                                | 1        | 1.23%   |
| Acidanthera                          | 1        | 1.23%   |
| Acer                                 | 1        | 1.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 4        | 4.94%   |
| Dell OptiPlex 790                          | 2        | 2.47%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 2.47%   |
| ASUS PRIME X570-PRO                        | 2        | 2.47%   |
| ASUS M4A785-M                              | 2        | 2.47%   |
| System76 Thelio                            | 1        | 1.23%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 1.23%   |
| Pegatron FL368AA-UUZ SR5612CH              | 1        | 1.23%   |
| Packard Bell IMEDIA S3220                  | 1        | 1.23%   |
| MSI MS-7E02                                | 1        | 1.23%   |
| MSI MS-7A57                                | 1        | 1.23%   |
| MSI MS-7752                                | 1        | 1.23%   |
| Medion MD34207/C746                        | 1        | 1.23%   |
| Lenovo ThinkCentre M93p 10A8S45S00         | 1        | 1.23%   |
| Intel DQ965GF HD/FP Audio                  | 1        | 1.23%   |
| IBM 8188PPV                                | 1        | 1.23%   |
| HP Z620 Workstation                        | 1        | 1.23%   |
| HP Z2 Tower G4 Workstation                 | 1        | 1.23%   |
| HP ProDesk 600 G1 SFF                      | 1        | 1.23%   |
| HP Compaq Pro 6305 SFF                     | 1        | 1.23%   |
| HP Compaq Elite 8300 CMT                   | 1        | 1.23%   |
| HP Compaq dc7600 Small Form Factor         | 1        | 1.23%   |
| HP Compaq 8200 Elite SFF PC                | 1        | 1.23%   |
| HP Compaq 8100 Elite SFF PC                | 1        | 1.23%   |
| HP Compaq 6200 Pro MT PC                   | 1        | 1.23%   |
| HP Compaq 6005 Pro MT PC                   | 1        | 1.23%   |
| Gigabyte X79S-UP5                          | 1        | 1.23%   |
| Gigabyte X570 AORUS ELITE WIFI             | 1        | 1.23%   |
| Gigabyte H170-HD3-CF                       | 1        | 1.23%   |
| Gigabyte GA-MA770-DS3                      | 1        | 1.23%   |
| Gigabyte F2A78M-HD2                        | 1        | 1.23%   |
| Gigabyte B550M DS3H                        | 1        | 1.23%   |
| Gigabyte B450M S2H                         | 1        | 1.23%   |
| Gigabyte B450 I AORUS PRO WIFI             | 1        | 1.23%   |
| Gigabyte B150M-D2V DDR3                    | 1        | 1.23%   |
| Gigabyte A520M H                           | 1        | 1.23%   |
| Gigabyte A320M-S2H                         | 1        | 1.23%   |
| Gigabyte 970A-DS3P                         | 1        | 1.23%   |
| Fujitsu TERRA_PC                           | 1        | 1.23%   |
| Fujitsu ESPRIMO P420                       | 1        | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 9        | 11.11%  |
| HP Compaq                                  | 7        | 8.64%   |
| ASUS All                                   | 4        | 4.94%   |
| Fujitsu ESPRIMO                            | 3        | 3.7%    |
| ASUS TUF                                   | 3        | 3.7%    |
| ASUS ROG                                   | 3        | 3.7%    |
| Dell Precision                             | 2        | 2.47%   |
| ASUS PRIME                                 | 2        | 2.47%   |
| ASUS P8P67                                 | 2        | 2.47%   |
| ASUS M4A785-M                              | 2        | 2.47%   |
| System76 Thelio                            | 1        | 1.23%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 1.23%   |
| Pegatron FL368AA-UUZ                       | 1        | 1.23%   |
| Packard Bell IMEDIA                        | 1        | 1.23%   |
| MSI MS-7E02                                | 1        | 1.23%   |
| MSI MS-7A57                                | 1        | 1.23%   |
| MSI MS-7752                                | 1        | 1.23%   |
| Medion MD34207                             | 1        | 1.23%   |
| Lenovo ThinkCentre                         | 1        | 1.23%   |
| Intel DQ965GF                              | 1        | 1.23%   |
| IBM 8188PPV                                | 1        | 1.23%   |
| HP Z620                                    | 1        | 1.23%   |
| HP Z2                                      | 1        | 1.23%   |
| HP ProDesk                                 | 1        | 1.23%   |
| Gigabyte X79S-UP5                          | 1        | 1.23%   |
| Gigabyte X570                              | 1        | 1.23%   |
| Gigabyte H170-HD3-CF                       | 1        | 1.23%   |
| Gigabyte GA-MA770-DS3                      | 1        | 1.23%   |
| Gigabyte F2A78M-HD2                        | 1        | 1.23%   |
| Gigabyte B550M                             | 1        | 1.23%   |
| Gigabyte B450M                             | 1        | 1.23%   |
| Gigabyte B450                              | 1        | 1.23%   |
| Gigabyte B150M-D2V                         | 1        | 1.23%   |
| Gigabyte A520M                             | 1        | 1.23%   |
| Gigabyte A320M-S2H                         | 1        | 1.23%   |
| Gigabyte 970A-DS3P                         | 1        | 1.23%   |
| Fujitsu TERRA                              | 1        | 1.23%   |
| Foxconn Pro3500                            | 1        | 1.23%   |
| ECS LIVA                                   | 1        | 1.23%   |
| DEPO Computers MS-7846                     | 1        | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 12       | 14.81%  |
| 2019 | 8        | 9.88%   |
| 2018 | 7        | 8.64%   |
| 2020 | 6        | 7.41%   |
| 2011 | 6        | 7.41%   |
| 2014 | 5        | 6.17%   |
| 2012 | 5        | 6.17%   |
| 2009 | 5        | 6.17%   |
| 2017 | 4        | 4.94%   |
| 2015 | 4        | 4.94%   |
| 2010 | 4        | 4.94%   |
| 2016 | 3        | 3.7%    |
| 2008 | 3        | 3.7%    |
| 2005 | 3        | 3.7%    |
| 2022 | 2        | 2.47%   |
| 2021 | 2        | 2.47%   |
| 2007 | 2        | 2.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 81       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 80       | 98.77%  |
| Enabled  | 1        | 1.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 81       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 22       | 27.16%  |
| 8.01-16.0   | 16       | 19.75%  |
| 4.01-8.0    | 13       | 16.05%  |
| 32.01-64.0  | 10       | 12.35%  |
| 64.01-256.0 | 8        | 9.88%   |
| 3.01-4.0    | 7        | 8.64%   |
| 1.01-2.0    | 3        | 3.7%    |
| 24.01-32.0  | 1        | 1.23%   |
| 2.01-3.0    | 1        | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 27       | 32.93%  |
| 4.01-8.0   | 17       | 20.73%  |
| 2.01-3.0   | 17       | 20.73%  |
| 3.01-4.0   | 9        | 10.98%  |
| 8.01-16.0  | 8        | 9.76%   |
| 0.51-1.0   | 3        | 3.66%   |
| 24.01-32.0 | 1        | 1.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 31       | 38.27%  |
| 1      | 31       | 38.27%  |
| 3      | 8        | 9.88%   |
| 7      | 3        | 3.7%    |
| 4      | 3        | 3.7%    |
| 5      | 2        | 2.47%   |
| 16     | 1        | 1.23%   |
| 11     | 1        | 1.23%   |
| 10     | 1        | 1.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 48       | 59.26%  |
| No        | 33       | 40.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 81       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 54.32%  |
| Yes       | 37       | 45.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 74.07%  |
| Yes       | 21       | 25.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 19       | 23.46%  |
| Germany                | 12       | 14.81%  |
| France                 | 10       | 12.35%  |
| Italy                  | 6        | 7.41%   |
| Brazil                 | 5        | 6.17%   |
| Belgium                | 4        | 4.94%   |
| Austria                | 4        | 4.94%   |
| Spain                  | 3        | 3.7%    |
| UK                     | 2        | 2.47%   |
| Sweden                 | 2        | 2.47%   |
| Russia                 | 2        | 2.47%   |
| Australia              | 2        | 2.47%   |
| Switzerland            | 1        | 1.23%   |
| Romania                | 1        | 1.23%   |
| Norway                 | 1        | 1.23%   |
| Netherlands            | 1        | 1.23%   |
| Mexico                 | 1        | 1.23%   |
| Luxembourg             | 1        | 1.23%   |
| Kenya                  | 1        | 1.23%   |
| Guatemala              | 1        | 1.23%   |
| Bosnia and Herzegovina | 1        | 1.23%   |
| Argentina              | 1        | 1.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Paris                   | 3        | 3.66%   |
| Houston                 | 3        | 3.66%   |
| Vienna                  | 2        | 2.44%   |
| Stockholm               | 2        | 2.44%   |
| Zanesville              | 1        | 1.22%   |
| Wildenfels              | 1        | 1.22%   |
| West Mifflin            | 1        | 1.22%   |
| Villefontaine           | 1        | 1.22%   |
| Verviers                | 1        | 1.22%   |
| Turin                   | 1        | 1.22%   |
| Tilburg                 | 1        | 1.22%   |
| Stuttgart               | 1        | 1.22%   |
| Sherman Oaks            | 1        | 1.22%   |
| Sarajevo                | 1        | 1.22%   |
| Sao Paulo               | 1        | 1.22%   |
| Santa Barbara d'Oeste   | 1        | 1.22%   |
| San Secondo di Pinerolo | 1        | 1.22%   |
| Saint-Ouen-l'Aumone     | 1        | 1.22%   |
| Rio Grande da Serra     | 1        | 1.22%   |
| Rennes                  | 1        | 1.22%   |
| Potsdam                 | 1        | 1.22%   |
| Philadelphia            | 1        | 1.22%   |
| Perth                   | 1        | 1.22%   |
| Palermo                 | 1        | 1.22%   |
| Oslo                    | 1        | 1.22%   |
| Olympia                 | 1        | 1.22%   |
| Oldenburg               | 1        | 1.22%   |
| Naumburg                | 1        | 1.22%   |
| Namur                   | 1        | 1.22%   |
| Nairobi                 | 1        | 1.22%   |
| Münster                | 1        | 1.22%   |
| Munich                  | 1        | 1.22%   |
| Moscow                  | 1        | 1.22%   |
| Modesto                 | 1        | 1.22%   |
| Miami                   | 1        | 1.22%   |
| Mérida                 | 1        | 1.22%   |
| Merced                  | 1        | 1.22%   |
| Mediglia                | 1        | 1.22%   |
| Maule                   | 1        | 1.22%   |
| Manchester              | 1        | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 27       | 34     | 17.53%  |
| Seagate               | 26       | 49     | 16.88%  |
| Samsung Electronics   | 24       | 34     | 15.58%  |
| SanDisk               | 11       | 12     | 7.14%   |
| Toshiba               | 9        | 10     | 5.84%   |
| Hitachi               | 6        | 7      | 3.9%    |
| Crucial               | 6        | 6      | 3.9%    |
| Kingston              | 5        | 6      | 3.25%   |
| HGST                  | 4        | 5      | 2.6%    |
| Phison                | 3        | 3      | 1.95%   |
| Intenso               | 3        | 3      | 1.95%   |
| Team                  | 2        | 2      | 1.3%    |
| SPCC                  | 2        | 2      | 1.3%    |
| JMicron Technology    | 2        | 2      | 1.3%    |
| Intel                 | 2        | 2      | 1.3%    |
| Corsair               | 2        | 3      | 1.3%    |
| ASMT                  | 2        | 2      | 1.3%    |
| A-DATA Technology     | 2        | 2      | 1.3%    |
| USB 3.0               | 1        | 2      | 0.65%   |
| TO Exter              | 1        | 1      | 0.65%   |
| Realtek Semiconductor | 1        | 1      | 0.65%   |
| PNY                   | 1        | 1      | 0.65%   |
| Phison Electronics    | 1        | 1      | 0.65%   |
| Patriot               | 1        | 1      | 0.65%   |
| OCZ                   | 1        | 1      | 0.65%   |
| NGFF                  | 1        | 1      | 0.65%   |
| Micron Technology     | 1        | 1      | 0.65%   |
| Maxtor                | 1        | 1      | 0.65%   |
| Leven                 | 1        | 1      | 0.65%   |
| Integral              | 1        | 1      | 0.65%   |
| Fujitsu               | 1        | 1      | 0.65%   |
| China                 | 1        | 1      | 0.65%   |
| BHT                   | 1        | 1      | 0.65%   |
| Apple                 | 1        | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 4        | 2.22%   |
| Seagate ST2000DM001-1ER164 2TB  | 4        | 2.22%   |
| Seagate ST2000DM008-2FR102 2TB  | 3        | 1.67%   |
| WDC WDS200T2B0A-00SM50 2TB SSD  | 2        | 1.11%   |
| Toshiba HDWD130 3TB             | 2        | 1.11%   |
| Toshiba DT01ACA050 500GB        | 2        | 1.11%   |
| Team T253X6001T 1024GB SSD      | 2        | 1.11%   |
| SPCC Solid State Disk 256GB     | 2        | 1.11%   |
| Seagate ST5000LM000-2AN170 5TB  | 2        | 1.11%   |
| Seagate Expansion 1TB           | 2        | 1.11%   |
| SanDisk SDSSDA240G 240GB        | 2        | 1.11%   |
| Samsung SSD 970 EVO Plus 500GB  | 2        | 1.11%   |
| Samsung SSD 870 EVO 1TB         | 2        | 1.11%   |
| Samsung SSD 860 EVO 1TB         | 2        | 1.11%   |
| Samsung SSD 850 EVO 500GB       | 2        | 1.11%   |
| Samsung HD753LJ 752GB           | 2        | 1.11%   |
| Kingston SA400S37120G 120GB SSD | 2        | 1.11%   |
| Crucial CT500MX500SSD1 500GB    | 2        | 1.11%   |
| Crucial CT1000MX500SSD1 1TB     | 2        | 1.11%   |
| WDC WDS512G1X0C-00ENX0 512GB    | 1        | 0.56%   |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 0.56%   |
| WDC WD5000BPKT-60PK4T0 500GB    | 1        | 0.56%   |
| WDC WD5000AVDS-63U7B1 500GB     | 1        | 0.56%   |
| WDC WD5000AAKS-75V0A0 500GB     | 1        | 0.56%   |
| WDC WD40EZRZ-00GXCB0 4TB        | 1        | 0.56%   |
| WDC WD40EFRX-68N32N0 4TB        | 1        | 0.56%   |
| WDC WD40EFAX-68JH4N1 4TB        | 1        | 0.56%   |
| WDC WD40EFAX-68JH4N0 4TB        | 1        | 0.56%   |
| WDC WD3200BUCT-63TWBY0 320GB    | 1        | 0.56%   |
| WDC WD3200BPVT-75JJ5T0 320GB    | 1        | 0.56%   |
| WDC WD3200BEVT-22ZCT0 320GB     | 1        | 0.56%   |
| WDC WD3200AAKS-00VYA0 320GB     | 1        | 0.56%   |
| WDC WD30EZRZ-00Z5HB0 3TB        | 1        | 0.56%   |
| WDC WD30EZRX-00SPEB0 3TB        | 1        | 0.56%   |
| WDC WD2500BEVT-80A23T0 250GB    | 1        | 0.56%   |
| WDC WD2500AAKX-001CA0 250GB     | 1        | 0.56%   |
| WDC WD20PURZ-85GU6Y0 2TB        | 1        | 0.56%   |
| WDC WD20EZRX-00D8PB0 2TB        | 1        | 0.56%   |
| WDC WD20EZAZ-00GGJB0 2TB        | 1        | 0.56%   |
| WDC WD1600AAJS-60Z0A0 160GB     | 1        | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 48     | 33.77%  |
| WDC                 | 24       | 31     | 31.17%  |
| Toshiba             | 9        | 10     | 11.69%  |
| Hitachi             | 6        | 7      | 7.79%   |
| HGST                | 4        | 5      | 5.19%   |
| Samsung Electronics | 3        | 3      | 3.9%    |
| USB 3.0             | 1        | 2      | 1.3%    |
| Maxtor              | 1        | 1      | 1.3%    |
| JMicron Technology  | 1        | 1      | 1.3%    |
| Fujitsu             | 1        | 1      | 1.3%    |
| ASMT                | 1        | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 14       | 19     | 24.14%  |
| SanDisk             | 10       | 11     | 17.24%  |
| Crucial             | 6        | 6      | 10.34%  |
| Kingston            | 5        | 6      | 8.62%   |
| Intenso             | 3        | 3      | 5.17%   |
| WDC                 | 2        | 2      | 3.45%   |
| Team                | 2        | 2      | 3.45%   |
| SPCC                | 2        | 2      | 3.45%   |
| A-DATA Technology   | 2        | 2      | 3.45%   |
| TO Exter            | 1        | 1      | 1.72%   |
| PNY                 | 1        | 1      | 1.72%   |
| Patriot             | 1        | 1      | 1.72%   |
| OCZ                 | 1        | 1      | 1.72%   |
| NGFF                | 1        | 1      | 1.72%   |
| Micron Technology   | 1        | 1      | 1.72%   |
| Leven               | 1        | 1      | 1.72%   |
| Integral            | 1        | 1      | 1.72%   |
| Corsair             | 1        | 1      | 1.72%   |
| China               | 1        | 1      | 1.72%   |
| BHT                 | 1        | 1      | 1.72%   |
| ASMT                | 1        | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 55       | 110    | 45.83%  |
| SSD     | 46       | 65     | 38.33%  |
| NVMe    | 17       | 24     | 14.17%  |
| Unknown | 2        | 2      | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 76       | 163    | 75.25%  |
| NVMe | 17       | 24     | 16.83%  |
| SAS  | 8        | 14     | 7.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 53       | 77     | 45.3%   |
| 0.51-1.0   | 33       | 44     | 28.21%  |
| 1.01-2.0   | 15       | 18     | 12.82%  |
| 4.01-10.0  | 7        | 24     | 5.98%   |
| 3.01-4.0   | 6        | 8      | 5.13%   |
| 2.01-3.0   | 3        | 4      | 2.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 21       | 25.61%  |
| 501-1000       | 18       | 21.95%  |
| 1001-2000      | 14       | 17.07%  |
| More than 3000 | 13       | 15.85%  |
| 251-500        | 8        | 9.76%   |
| 51-100         | 4        | 4.88%   |
| 21-50          | 2        | 2.44%   |
| 2001-3000      | 1        | 1.22%   |
| 1-20           | 1        | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 21       | 25.3%   |
| 21-50          | 13       | 15.66%  |
| 101-250        | 12       | 14.46%  |
| More than 3000 | 8        | 9.64%   |
| 251-500        | 8        | 9.64%   |
| 51-100         | 7        | 8.43%   |
| 1001-2000      | 5        | 6.02%   |
| 501-1000       | 5        | 6.02%   |
| 2001-3000      | 4        | 4.82%   |

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
| Works    | 75       | 158    | 71.43%  |
| Malfunc  | 19       | 26     | 18.1%   |
| Detected | 9        | 15     | 8.57%   |
| Failed   | 2        | 2      | 1.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 53       | 46.49%  |
| AMD                       | 24       | 21.05%  |
| Samsung Electronics       | 9        | 7.89%   |
| Phison Electronics        | 5        | 4.39%   |
| Marvell Technology Group  | 5        | 4.39%   |
| ASMedia Technology        | 5        | 4.39%   |
| Nvidia                    | 3        | 2.63%   |
| SanDisk                   | 2        | 1.75%   |
| JMicron Technology        | 2        | 1.75%   |
| VIA Technologies          | 1        | 0.88%   |
| Silicon Image             | 1        | 0.88%   |
| Realtek Semiconductor     | 1        | 0.88%   |
| LSI Logic / Symbios Logic | 1        | 0.88%   |
| Apple                     | 1        | 0.88%   |
| Adaptec                   | 1        | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13       | 9.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11       | 7.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7        | 4.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6        | 4.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 3.47%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 3.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5        | 3.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4        | 2.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 2.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4        | 2.78%   |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 2.78%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.39%   |
| Phison E12 NVMe Controller                                                     | 2        | 1.39%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2        | 1.39%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2        | 1.39%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2        | 1.39%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.39%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.39%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2        | 1.39%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 1.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 1.39%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 1.39%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 0.69%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.69%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 0.69%   |
| SanDisk WD Black NVMe SSD                                                      | 1        | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.69%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1        | 0.69%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 0.69%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.69%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.69%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                        | 1        | 0.69%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.69%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1        | 0.69%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 1        | 0.69%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1        | 0.69%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 0.69%   |
| JMicron JMB362 SATA Controller                                                 | 1        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 67       | 59.29%  |
| IDE  | 21       | 18.58%  |
| NVMe | 17       | 15.04%  |
| RAID | 4        | 3.54%   |
| SAS  | 3        | 2.65%   |
| SCSI | 1        | 0.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 54       | 66.67%  |
| AMD    | 27       | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz       | 3        | 3.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz       | 3        | 3.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz       | 2        | 2.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2        | 2.47%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2        | 2.47%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 2        | 2.47%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 2.47%   |
| AMD Ryzen 9 3950X 16-Core Processor    | 2        | 2.47%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 2        | 2.47%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 2        | 2.47%   |
| AMD Phenom II X4 945 Processor         | 2        | 2.47%   |
| Intel Xeon W-2150B CPU @ 3.00GHz       | 1        | 1.23%   |
| Intel Xeon CPU E5420 @ 2.50GHz         | 1        | 1.23%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz    | 1        | 1.23%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz     | 1        | 1.23%   |
| Intel Pentium D CPU 3.40GHz            | 1        | 1.23%   |
| Intel Pentium CPU G3220 @ 3.00GHz      | 1        | 1.23%   |
| Intel Pentium 4 CPU 3.20GHz            | 1        | 1.23%   |
| Intel Pentium 4 CPU 2.80GHz            | 1        | 1.23%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 1        | 1.23%   |
| Intel Core i9-10900K CPU @ 3.70GHz     | 1        | 1.23%   |
| Intel Core i9-10900 CPU @ 2.80GHz      | 1        | 1.23%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 1        | 1.23%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 1        | 1.23%   |
| Intel Core i7-4770K CPU @ 3.50GHz      | 1        | 1.23%   |
| Intel Core i7-3930K CPU @ 3.20GHz      | 1        | 1.23%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 1.23%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1        | 1.23%   |
| Intel Core i7 CPU 930 @ 2.80GHz        | 1        | 1.23%   |
| Intel Core i5-9400T CPU @ 1.80GHz      | 1        | 1.23%   |
| Intel Core i5-8600K CPU @ 3.60GHz      | 1        | 1.23%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1        | 1.23%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 1        | 1.23%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 1        | 1.23%   |
| Intel Core i5-3330 CPU @ 3.00GHz       | 1        | 1.23%   |
| Intel Core i5-2500K CPU @ 3.30GHz      | 1        | 1.23%   |
| Intel Core i5 CPU 650 @ 3.20GHz        | 1        | 1.23%   |
| Intel Core i3-6100T CPU @ 3.20GHz      | 1        | 1.23%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 1        | 1.23%   |
| Intel Core i3-4340 CPU @ 3.60GHz       | 1        | 1.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 20       | 24.69%  |
| Intel Core i7          | 11       | 13.58%  |
| Intel Core i3          | 8        | 9.88%   |
| AMD Ryzen 9            | 5        | 6.17%   |
| Intel Xeon             | 4        | 4.94%   |
| AMD Ryzen 5            | 4        | 4.94%   |
| AMD Phenom II X4       | 4        | 4.94%   |
| Intel Core i9          | 3        | 3.7%    |
| Intel Pentium 4        | 2        | 2.47%   |
| AMD Ryzen 7            | 2        | 2.47%   |
| AMD FX                 | 2        | 2.47%   |
| AMD Athlon II X2       | 2        | 2.47%   |
| Other                  | 1        | 1.23%   |
| Intel Pentium D        | 1        | 1.23%   |
| Intel Pentium          | 1        | 1.23%   |
| Intel Core 2 Duo       | 1        | 1.23%   |
| Intel Core 2           | 1        | 1.23%   |
| Intel Celeron          | 1        | 1.23%   |
| AMD Ryzen Threadripper | 1        | 1.23%   |
| AMD Ryzen 3            | 1        | 1.23%   |
| AMD E                  | 1        | 1.23%   |
| AMD Athlon X4          | 1        | 1.23%   |
| AMD Athlon Dual Core   | 1        | 1.23%   |
| AMD Athlon 64 X2       | 1        | 1.23%   |
| AMD A4                 | 1        | 1.23%   |
| AMD A10                | 1        | 1.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 36       | 44.44%  |
| 2      | 19       | 23.46%  |
| 6      | 9        | 11.11%  |
| 8      | 6        | 7.41%   |
| 10     | 3        | 3.7%    |
| 1      | 3        | 3.7%    |
| 16     | 2        | 2.47%   |
| 12     | 2        | 2.47%   |
| 32     | 1        | 1.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 80       | 98.77%  |
| 2      | 1        | 1.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 45       | 55.56%  |
| 1      | 36       | 44.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 80       | 98.77%  |
| 32-bit         | 1        | 1.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 12       | 14.81%  |
| Unknown    | 10       | 12.35%  |
| 0x306a9    | 6        | 7.41%   |
| 0x206a7    | 6        | 7.41%   |
| 0x506e3    | 4        | 4.94%   |
| 0x08701021 | 4        | 4.94%   |
| 0x906ea    | 3        | 3.7%    |
| 0x0a50000d | 3        | 3.7%    |
| 0x010000c8 | 3        | 3.7%    |
| 0xf41      | 2        | 2.47%   |
| 0xa0655    | 2        | 2.47%   |
| 0x906ed    | 2        | 2.47%   |
| 0x206d7    | 2        | 2.47%   |
| 0x10676    | 2        | 2.47%   |
| 0x010000b6 | 2        | 2.47%   |
| 0xf65      | 1        | 1.23%   |
| 0x90675    | 1        | 1.23%   |
| 0x6f6      | 1        | 1.23%   |
| 0x506ca    | 1        | 1.23%   |
| 0x50654    | 1        | 1.23%   |
| 0x306f2    | 1        | 1.23%   |
| 0x20655    | 1        | 1.23%   |
| 0x106a5    | 1        | 1.23%   |
| 0x0a201009 | 1        | 1.23%   |
| 0x08701013 | 1        | 1.23%   |
| 0x08301039 | 1        | 1.23%   |
| 0x08108109 | 1        | 1.23%   |
| 0x08101016 | 1        | 1.23%   |
| 0x06003106 | 1        | 1.23%   |
| 0x06001119 | 1        | 1.23%   |
| 0x06000852 | 1        | 1.23%   |
| 0x0600081f | 1        | 1.23%   |
| 0x010000c7 | 1        | 1.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 13       | 16.05%  |
| Zen 2            | 8        | 9.88%   |
| SandyBridge      | 8        | 9.88%   |
| Skylake          | 7        | 8.64%   |
| IvyBridge        | 7        | 8.64%   |
| KabyLake         | 6        | 7.41%   |
| K10              | 6        | 7.41%   |
| Zen 3            | 4        | 4.94%   |
| Piledriver       | 3        | 3.7%    |
| NetBurst         | 3        | 3.7%    |
| Westmere         | 2        | 2.47%   |
| Penryn           | 2        | 2.47%   |
| K8 Hammer        | 2        | 2.47%   |
| CometLake        | 2        | 2.47%   |
| Zen+             | 1        | 1.23%   |
| Zen              | 1        | 1.23%   |
| Steamroller      | 1        | 1.23%   |
| Nehalem          | 1        | 1.23%   |
| Goldmont         | 1        | 1.23%   |
| Excavator        | 1        | 1.23%   |
| Core             | 1        | 1.23%   |
| Alderlake Hybrid | 1        | 1.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 40       | 45.98%  |
| Intel  | 27       | 31.03%  |
| AMD    | 20       | 22.99%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 7.87%   |
| Intel HD Graphics 530                                                       | 4        | 4.49%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 3.37%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.37%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 3.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 3.37%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.25%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.25%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 2.25%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 2.25%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 2.25%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 2.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.25%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.25%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 2.25%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 2.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.25%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.12%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1        | 1.12%   |
| Nvidia GT216 [GeForce 315]                                                  | 1        | 1.12%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.12%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.12%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.12%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.12%   |
| Nvidia GK208 [GeForce GT 720]                                               | 1        | 1.12%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 1.12%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.12%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.12%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.12%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.12%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 1.12%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.12%   |
| Nvidia G98 [Quadro NVS 450]                                                 | 1        | 1.12%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.12%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.12%   |
| Nvidia C77 [GeForce 8200]                                                   | 1        | 1.12%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 1.12%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.12%   |
| Intel HD Graphics 630                                                       | 1        | 1.12%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 36       | 44.44%  |
| 1 x Intel      | 22       | 27.16%  |
| 1 x AMD        | 18       | 22.22%  |
| Intel + Nvidia | 2        | 2.47%   |
| 2 x Nvidia     | 1        | 1.23%   |
| 2 x AMD        | 1        | 1.23%   |
| AMD + Nvidia   | 1        | 1.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 57       | 69.51%  |
| Proprietary | 25       | 30.49%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 31.71%  |
| 1.01-2.0   | 14       | 17.07%  |
| 0.01-0.5   | 12       | 14.63%  |
| 0.51-1.0   | 10       | 12.2%   |
| 3.01-4.0   | 6        | 7.32%   |
| 7.01-8.0   | 5        | 6.1%    |
| 8.01-16.0  | 4        | 4.88%   |
| 5.01-6.0   | 3        | 3.66%   |
| 2.01-3.0   | 1        | 1.22%   |
| 16.01-24.0 | 1        | 1.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 14       | 15.56%  |
| Goldstar             | 10       | 11.11%  |
| Dell                 | 9        | 10%     |
| Philips              | 8        | 8.89%   |
| Hewlett-Packard      | 8        | 8.89%   |
| Acer                 | 8        | 8.89%   |
| Ancor Communications | 5        | 5.56%   |
| AOC                  | 3        | 3.33%   |
| ONN                  | 2        | 2.22%   |
| Fujitsu Siemens      | 2        | 2.22%   |
| Eizo                 | 2        | 2.22%   |
| ViewSonic            | 1        | 1.11%   |
| VIE                  | 1        | 1.11%   |
| Unknown              | 1        | 1.11%   |
| TVT                  | 1        | 1.11%   |
| Targa Visionary      | 1        | 1.11%   |
| Sony                 | 1        | 1.11%   |
| Seiki                | 1        | 1.11%   |
| Onkyo                | 1        | 1.11%   |
| NEC Computers        | 1        | 1.11%   |
| MSI                  | 1        | 1.11%   |
| Medion               | 1        | 1.11%   |
| KTC                  | 1        | 1.11%   |
| Iiyama               | 1        | 1.11%   |
| Hannspree            | 1        | 1.11%   |
| DENON                | 1        | 1.11%   |
| BenQ                 | 1        | 1.11%   |
| ASUSTek Computer     | 1        | 1.11%   |
| Apple                | 1        | 1.11%   |
| Unknown              | 1        | 1.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                   | 2        | 2%      |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2        | 2%      |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1        | 1%      |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 1%      |
| Unknown LCD Monitor SAMSUNG 5760x2160                                 | 1        | 1%      |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                        | 1        | 1%      |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch   | 1        | 1%      |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                    | 1        | 1%      |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                   | 1        | 1%      |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1        | 1%      |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1        | 1%      |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch  | 1        | 1%      |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1        | 1%      |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch   | 1        | 1%      |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch  | 1        | 1%      |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch  | 1        | 1%      |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1        | 1%      |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch  | 1        | 1%      |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch   | 1        | 1%      |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch   | 1        | 1%      |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1        | 1%      |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 1%      |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch  | 1        | 1%      |
| Samsung Electronics LCD Monitor SyncMaster                            | 1        | 1%      |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 1        | 1%      |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch  | 1        | 1%      |
| Samsung Electronics LCD Monitor S34J55x 3440x1440                     | 1        | 1%      |
| Samsung Electronics LC27T55 SAM701F 1920x1080 610x350mm 27.7-inch     | 1        | 1%      |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch             | 1        | 1%      |
| Philips PHL 278E8Q PHLC161 1920x1080 598x336mm 27.0-inch              | 1        | 1%      |
| Philips 247E4 PHLC0C0 1920x1080 521x293mm 23.5-inch                   | 1        | 1%      |
| Philips 227E4LH PHLC0AC 1920x1080 477x268mm 21.5-inch                 | 1        | 1%      |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1        | 1%      |
| Philips 201E PHLC033 1600x900 443x249mm 20.0-inch                     | 1        | 1%      |
| Philips 190V PHL0847 1280x1024 376x301mm 19.0-inch                    | 1        | 1%      |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                    | 1        | 1%      |
| Onkyo HT-R494 ONK0F43 3840x2160 1150x650mm 52.0-inch                  | 1        | 1%      |
| NEC Computers LCD2180UX NEC662C 1600x1200 430x320mm 21.1-inch         | 1        | 1%      |
| MSI MP242 MSI30A1 1920x1080 527x296mm 23.8-inch                       | 1        | 1%      |
| MSI MAG241C MSI3EA2 1920x1080 521x293mm 23.5-inch                     | 1        | 1%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 41       | 46.59%  |
| 3840x2160 (4K)     | 10       | 11.36%  |
| 1280x1024 (SXGA)   | 9        | 10.23%  |
| 1680x1050 (WSXGA+) | 5        | 5.68%   |
| 1920x1200 (WUXGA)  | 4        | 4.55%   |
| 1440x900 (WXGA+)   | 3        | 3.41%   |
| 1366x768 (WXGA)    | 3        | 3.41%   |
| 2560x1440 (QHD)    | 2        | 2.27%   |
| 1600x900 (HD+)     | 2        | 2.27%   |
| 1360x768           | 2        | 2.27%   |
| Unknown            | 2        | 2.27%   |
| 5760x2160          | 1        | 1.14%   |
| 3440x1440          | 1        | 1.14%   |
| 3280x1080          | 1        | 1.14%   |
| 1600x1200          | 1        | 1.14%   |
| 1400x1050          | 1        | 1.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 15       | 16.67%  |
| 21      | 13       | 14.44%  |
| 27      | 11       | 12.22%  |
| 24      | 11       | 12.22%  |
| 19      | 7        | 7.78%   |
| 31      | 6        | 6.67%   |
| 22      | 5        | 5.56%   |
| 17      | 5        | 5.56%   |
| 18      | 4        | 4.44%   |
| 20      | 3        | 3.33%   |
| Unknown | 3        | 3.33%   |
| 84      | 1        | 1.11%   |
| 65      | 1        | 1.11%   |
| 52      | 1        | 1.11%   |
| 50      | 1        | 1.11%   |
| 43      | 1        | 1.11%   |
| 32      | 1        | 1.11%   |
| 15      | 1        | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 34       | 39.08%  |
| 401-500     | 26       | 29.89%  |
| 601-700     | 8        | 9.2%    |
| 301-350     | 6        | 6.9%    |
| 351-400     | 4        | 4.6%    |
| 1001-1500   | 3        | 3.45%   |
| Unknown     | 3        | 3.45%   |
| 701-800     | 1        | 1.15%   |
| 1501-2000   | 1        | 1.15%   |
| 901-1000    | 1        | 1.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 56       | 67.47%  |
| 16/10   | 13       | 15.66%  |
| 5/4     | 8        | 9.64%   |
| Unknown | 3        | 3.61%   |
| 4/3     | 2        | 2.41%   |
| 3/2     | 1        | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 36       | 41.38%  |
| 301-350        | 11       | 12.64%  |
| 151-200        | 11       | 12.64%  |
| 141-150        | 9        | 10.34%  |
| 351-500        | 7        | 8.05%   |
| More than 1000 | 4        | 4.6%    |
| 251-300        | 4        | 4.6%    |
| Unknown        | 3        | 3.45%   |
| 111-120        | 1        | 1.15%   |
| 501-1000       | 1        | 1.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 59       | 71.08%  |
| 101-120 | 16       | 19.28%  |
| 121-160 | 3        | 3.61%   |
| Unknown | 3        | 3.61%   |
| 1-50    | 1        | 1.2%    |
| 161-240 | 1        | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 57       | 70.37%  |
| 2     | 24       | 29.63%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 45       | 37.19%  |
| Intel                           | 39       | 32.23%  |
| Qualcomm Atheros                | 11       | 9.09%   |
| Broadcom                        | 5        | 4.13%   |
| TP-Link                         | 3        | 2.48%   |
| Nvidia                          | 3        | 2.48%   |
| MediaTek                        | 2        | 1.65%   |
| Broadcom Limited                | 2        | 1.65%   |
| Aquantia                        | 2        | 1.65%   |
| ZyDAS                           | 1        | 0.83%   |
| Wacom                           | 1        | 0.83%   |
| Ralink Technology               | 1        | 0.83%   |
| Qualcomm Atheros Communications | 1        | 0.83%   |
| NetGear                         | 1        | 0.83%   |
| Microsoft                       | 1        | 0.83%   |
| InterBiometrics                 | 1        | 0.83%   |
| Input Club                      | 1        | 0.83%   |
| ASIX Electronics                | 1        | 0.83%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 38       | 28.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 7.52%   |
| Intel I211 Gigabit Network Connection                                         | 6        | 4.51%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 3.76%   |
| Intel Wireless-AC 9260                                                        | 4        | 3.01%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 1.5%    |
| Realtek 802.11ac NIC                                                          | 2        | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 1.5%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2        | 1.5%    |
| Nvidia MCP77 Ethernet                                                         | 2        | 1.5%    |
| Intel Ethernet Controller I225-V                                              | 2        | 1.5%    |
| Intel Ethernet Connection I217-V                                              | 2        | 1.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 1.5%    |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.5%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 1.5%    |
| ZyDAS ZD1211B 802.11g                                                         | 1        | 0.75%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1        | 0.75%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.75%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 0.75%   |
| TP-Link 802.11ac NIC                                                          | 1        | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.75%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1        | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.75%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 0.75%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.75%   |
| Realtek 802.11ax WLAN Adapter                                                 | 1        | 0.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.75%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.75%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.75%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 0.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.75%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 0.75%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.75%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                   | 1        | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 9        | 23.08%  |
| Intel                           | 9        | 23.08%  |
| Realtek Semiconductor           | 8        | 20.51%  |
| TP-Link                         | 3        | 7.69%   |
| MediaTek                        | 2        | 5.13%   |
| Broadcom                        | 2        | 5.13%   |
| ZyDAS                           | 1        | 2.56%   |
| Wacom                           | 1        | 2.56%   |
| Ralink Technology               | 1        | 2.56%   |
| Qualcomm Atheros Communications | 1        | 2.56%   |
| NetGear                         | 1        | 2.56%   |
| Microsoft                       | 1        | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wireless-AC 9260                                                        | 4        | 10.26%  |
| Realtek 802.11ac NIC                                                          | 2        | 5.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 5.13%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2        | 5.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 5.13%   |
| ZyDAS ZD1211B 802.11g                                                         | 1        | 2.56%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1        | 2.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 2.56%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 2.56%   |
| TP-Link 802.11ac NIC                                                          | 1        | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 2.56%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1        | 2.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 2.56%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 2.56%   |
| Realtek 802.11ax WLAN Adapter                                                 | 1        | 2.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 2.56%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 2.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 2.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 2.56%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 2.56%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 2.56%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                   | 1        | 2.56%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 2.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 1        | 2.56%   |
| MediaTek 802.11 n WLAN                                                        | 1        | 2.56%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 2.56%   |
| Intel Wireless 3165                                                           | 1        | 2.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 2.56%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                            | 1        | 2.56%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1        | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 41       | 45.56%  |
| Intel                 | 36       | 40%     |
| Nvidia                | 3        | 3.33%   |
| Broadcom              | 3        | 3.33%   |
| Qualcomm Atheros      | 2        | 2.22%   |
| Broadcom Limited      | 2        | 2.22%   |
| Aquantia              | 2        | 2.22%   |
| ASIX Electronics      | 1        | 1.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38       | 41.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 10.87%  |
| Intel I211 Gigabit Network Connection                             | 6        | 6.52%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 5.43%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 2.17%   |
| Nvidia MCP77 Ethernet                                             | 2        | 2.17%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.17%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.17%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.17%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.17%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.09%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.09%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.09%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.09%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.09%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.09%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.09%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.09%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.09%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 1.09%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 1.09%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.09%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.09%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 1.09%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 1.09%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 1.09%   |
| ASIX AX88772B                                                     | 1        | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 81       | 67.5%   |
| WiFi     | 37       | 30.83%  |
| Modem    | 2        | 1.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 73       | 82.02%  |
| WiFi     | 16       | 17.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 51       | 62.96%  |
| 2     | 27       | 33.33%  |
| 3     | 3        | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 67       | 81.71%  |
| Yes  | 15       | 18.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 9        | 40.91%  |
| Cambridge Silicon Radio         | 6        | 27.27%  |
| ASUSTek Computer                | 3        | 13.64%  |
| Qualcomm Atheros Communications | 2        | 9.09%   |
| Realtek Semiconductor           | 1        | 4.55%   |
| MediaTek                        | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 27.27%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 18.18%  |
| Intel Bluetooth wireless interface                  | 2        | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 9.09%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 9.09%   |
| Realtek Bluetooth Radio                             | 1        | 4.55%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 4.55%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 4.55%   |
| MediaTek Wireless_Device                            | 1        | 4.55%   |
| Intel AX210 Bluetooth                               | 1        | 4.55%   |
| ASUS BCM20702A0                                     | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 49       | 30.82%  |
| Nvidia                               | 34       | 21.38%  |
| AMD                                  | 29       | 18.24%  |
| C-Media Electronics                  | 5        | 3.14%   |
| Texas Instruments                    | 4        | 2.52%   |
| Yamaha                               | 3        | 1.89%   |
| JMTek                                | 3        | 1.89%   |
| PreSonus Audio Electronics           | 2        | 1.26%   |
| M-Audio                              | 2        | 1.26%   |
| Logitech                             | 2        | 1.26%   |
| ZOOM                                 | 1        | 0.63%   |
| Xilinx                               | 1        | 0.63%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.63%   |
| Textech International                | 1        | 0.63%   |
| Tenx Technology                      | 1        | 0.63%   |
| TEAC                                 | 1        | 0.63%   |
| Studiologic                          | 1        | 0.63%   |
| SteelSeries ApS                      | 1        | 0.63%   |
| Samson Technologies                  | 1        | 0.63%   |
| QinHeng Electronics                  | 1        | 0.63%   |
| Plantronics                          | 1        | 0.63%   |
| MIDITECH                             | 1        | 0.63%   |
| Medeli Electronics                   | 1        | 0.63%   |
| Mark of the Unicorn                  | 1        | 0.63%   |
| KTMicro                              | 1        | 0.63%   |
| Harman                               | 1        | 0.63%   |
| Generalplus Technology               | 1        | 0.63%   |
| Focusrite-Novation                   | 1        | 0.63%   |
| Ensoniq                              | 1        | 0.63%   |
| Creative Technology                  | 1        | 0.63%   |
| BEHRINGER International              | 1        | 0.63%   |
| Audient                              | 1        | 0.63%   |
| ASUSTek Computer                     | 1        | 0.63%   |
| Apple                                | 1        | 0.63%   |
| Alesis                               | 1        | 0.63%   |
| AKAI Professional M.I.               | 1        | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12       | 6.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 4.37%   |
| AMD Starship/Matisse HD Audio Controller                                          | 8        | 4.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 3.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 3.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6        | 3.28%   |
| AMD Family 17h/19h HD Audio Controller                                            | 5        | 2.73%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 2.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 2.19%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 2.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 2.19%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3        | 1.64%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 1.64%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 1.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 1.64%   |
| AMD FCH Azalia Controller                                                         | 3        | 1.64%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.64%   |
| PreSonus Audio Electronics Studio 24c                                             | 2        | 1.09%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 1.09%   |
| Nvidia High Definition Audio Controller                                           | 2        | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 1.09%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1.09%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 1.09%   |
| M-Audio M-Track                                                                   | 2        | 1.09%   |
| JMTek USB PnP Audio Device                                                        | 2        | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 1.09%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 2        | 1.09%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 2        | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.09%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 1.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 1.09%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 1.09%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 1.09%   |
| ZOOM U-22                                                                         | 1        | 0.55%   |
| Yamaha YMF-744B [DS-1S Audio Controller]                                          | 1        | 0.55%   |
| Yamaha MG-XU                                                                      | 1        | 0.55%   |
| Yamaha AG06/AG03                                                                  | 1        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 15       | 14.56%  |
| Kingston            | 14       | 13.59%  |
| Samsung Electronics | 13       | 12.62%  |
| Unknown             | 11       | 10.68%  |
| Crucial             | 10       | 9.71%   |
| Corsair             | 10       | 9.71%   |
| G.Skill             | 7        | 6.8%    |
| Micron Technology   | 6        | 5.83%   |
| Patriot             | 4        | 3.88%   |
| Unifosa             | 1        | 0.97%   |
| Smart               | 1        | 0.97%   |
| S                   | 1        | 0.97%   |
| PNY                 | 1        | 0.97%   |
| OCZ                 | 1        | 0.97%   |
| Nanya Technology    | 1        | 0.97%   |
| M                   | 1        | 0.97%   |
| HBS                 | 1        | 0.97%   |
| Goldkey             | 1        | 0.97%   |
| Elpida              | 1        | 0.97%   |
| Aeneon              | 1        | 0.97%   |
| A-DATA Technology   | 1        | 0.97%   |
| 0194808980CE        | 1        | 0.97%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s         | 3        | 2.56%   |
| Patriot RAM 3200 C16 Series 8192MB DIMM DDR4 3266MT/s       | 3        | 2.56%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                     | 2        | 1.71%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                    | 2        | 1.71%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s        | 2        | 1.71%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s         | 2        | 1.71%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 2        | 1.71%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s       | 2        | 1.71%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 2        | 1.71%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s      | 2        | 1.71%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1        | 0.85%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                   | 1        | 0.85%   |
| Unknown RAM Module 512MB DIMM DDR                           | 1        | 0.85%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s                    | 1        | 0.85%   |
| Unknown RAM Module 256MB DIMM DDR                           | 1        | 0.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1        | 0.85%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1        | 0.85%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                    | 1        | 0.85%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1        | 0.85%   |
| Unknown RAM Module 1024MB DIMM DDR                          | 1        | 0.85%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1        | 0.85%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s                 | 1        | 0.85%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s           | 1        | 0.85%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s          | 1        | 0.85%   |
| SK hynix RAM TMT41GU6BFR8C-PBSC 8192MB DIMM DDR3 1600MT/s   | 1        | 0.85%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 0.85%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2666MT/s               | 1        | 0.85%   |
| SK hynix RAM Module 32GB DIMM DDR4 2667MT/s                 | 1        | 0.85%   |
| SK hynix RAM HYMP564U64BP8-C4 512MB DIMM DDR 533MT/s        | 1        | 0.85%   |
| SK hynix RAM HYMP125F72CP8N3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.85%   |
| SK hynix RAM HYMP125F72CP8D3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.85%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s        | 1        | 0.85%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1        | 0.85%   |
| SK hynix RAM HMT351U7CFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1        | 0.85%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s        | 1        | 0.85%   |
| SK hynix RAM HMT325U7CFR8C-PB 2GB DIMM DDR3 1600MT/s        | 1        | 0.85%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s        | 1        | 0.85%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 0.85%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1        | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 39       | 46.43%  |
| DDR4    | 29       | 34.52%  |
| DDR2    | 7        | 8.33%   |
| Unknown | 4        | 4.76%   |
| DDR     | 3        | 3.57%   |
| SDRAM   | 2        | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 74       | 90.24%  |
| SODIMM  | 6        | 7.32%   |
| RIMM    | 1        | 1.22%   |
| FB-DIMM | 1        | 1.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 26       | 27.66%  |
| 8192  | 25       | 26.6%   |
| 2048  | 13       | 13.83%  |
| 16384 | 11       | 11.7%   |
| 32768 | 8        | 8.51%   |
| 1024  | 8        | 8.51%   |
| 512   | 2        | 2.13%   |
| 256   | 1        | 1.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 25       | 26.32%  |
| 1333    | 10       | 10.53%  |
| 3600    | 5        | 5.26%   |
| 3200    | 5        | 5.26%   |
| 2133    | 5        | 5.26%   |
| 1866    | 5        | 5.26%   |
| 667     | 5        | 5.26%   |
| 3266    | 4        | 4.21%   |
| 1800    | 4        | 4.21%   |
| 1066    | 4        | 4.21%   |
| 2667    | 3        | 3.16%   |
| 800     | 3        | 3.16%   |
| 2933    | 2        | 2.11%   |
| 2400    | 2        | 2.11%   |
| 1867    | 2        | 2.11%   |
| 533     | 2        | 2.11%   |
| Unknown | 2        | 2.11%   |
| 3500    | 1        | 1.05%   |
| 3466    | 1        | 1.05%   |
| 3000    | 1        | 1.05%   |
| 2934    | 1        | 1.05%   |
| 2800    | 1        | 1.05%   |
| 2666    | 1        | 1.05%   |
| 2472    | 1        | 1.05%   |

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
| Logitech                      | 6        | 31.58%  |
| Samsung Electronics           | 2        | 10.53%  |
| Microsoft                     | 2        | 10.53%  |
| Microdia                      | 2        | 10.53%  |
| ViewSonic                     | 1        | 5.26%   |
| Sweex                         | 1        | 5.26%   |
| Sunplus IT                    | 1        | 5.26%   |
| Sunplus Innovation Technology | 1        | 5.26%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 5.26%   |
| Philips (or NXP)              | 1        | 5.26%   |
| MacroSilicon                  | 1        | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)           | 2        | 10.53%  |
| Logitech Webcam C270                              | 2        | 10.53%  |
| ViewSonic PC Camera                               | 1        | 5.26%   |
| Sweex WC060 Series HD Webcam                      | 1        | 5.26%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 1        | 5.26%   |
| Sunplus HD 720P webcam                            | 1        | 5.26%   |
| SHENZHEN AONI ELECTRONIC NexiGo N930AF FHD Webcam | 1        | 5.26%   |
| Philips (or NXP) Webcam SPC530NC                  | 1        | 5.26%   |
| Microsoft LifeCam VX-5000                         | 1        | 5.26%   |
| Microsoft LifeCam Cinema                          | 1        | 5.26%   |
| Microdia USB 2.0 Camera                           | 1        | 5.26%   |
| Microdia MSI Starcam Racer                        | 1        | 5.26%   |
| MacroSilicon USB Video                            | 1        | 5.26%   |
| Logitech QuickCam Communicate MP/S5500            | 1        | 5.26%   |
| Logitech Portable Webcam C905                     | 1        | 5.26%   |
| Logitech HD Webcam C910                           | 1        | 5.26%   |
| Logitech HD Pro Webcam C920                       | 1        | 5.26%   |

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
| 0     | 71       | 87.65%  |
| 1     | 9        | 11.11%  |
| 2     | 1        | 1.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 5        | 45.45%  |
| Sound                    | 2        | 18.18%  |
| Unassigned class         | 1        | 9.09%   |
| Modem                    | 1        | 9.09%   |
| Graphics card            | 1        | 9.09%   |
| Communication controller | 1        | 9.09%   |

