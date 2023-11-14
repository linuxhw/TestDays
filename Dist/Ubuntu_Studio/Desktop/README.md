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

Total: 102

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | H270-HD3P-CF                | [43fedd61b1](https://linux-hardware.org/?probe=43fedd61b1) | Oct 23, 2023 |
| Gigabyte      | H270-HD3P-CF                | [22baba8799](https://linux-hardware.org/?probe=22baba8799) | Oct 23, 2023 |
| Unknown       | Unknown                     | [7e1caa679f](https://linux-hardware.org/?probe=7e1caa679f) | Sep 24, 2023 |
| Unknown       | Unknown                     | [5a57428971](https://linux-hardware.org/?probe=5a57428971) | Sep 24, 2023 |
| Gigabyte      | H61M-D2-B3                  | [6ffb2379fa](https://linux-hardware.org/?probe=6ffb2379fa) | Aug 30, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [17136ed242](https://linux-hardware.org/?probe=17136ed242) | Aug 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [fcfb9cd970](https://linux-hardware.org/?probe=fcfb9cd970) | Aug 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [c3490914f6](https://linux-hardware.org/?probe=c3490914f6) | Aug 26, 2023 |
| MSI           | PRO B760M-P DDR4            | [499c14b0f7](https://linux-hardware.org/?probe=499c14b0f7) | Aug 26, 2023 |
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
| Ubuntu Studio 20.04 | 42       | 48.28%  |
| Ubuntu Studio 22.04 | 24       | 27.59%  |
| Ubuntu Studio 20.10 | 9        | 10.34%  |
| Ubuntu Studio 22.10 | 3        | 3.45%   |
| Ubuntu Studio 21.10 | 3        | 3.45%   |
| Ubuntu Studio 23.04 | 2        | 2.3%    |
| Ubuntu Studio 21.04 | 2        | 2.3%    |
| Ubuntu Studio 23.10 | 1        | 1.15%   |
| Ubuntu Studio 16.04 | 1        | 1.15%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu Studio | 86       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.0-58-lowlatency   | 3        | 3.37%   |
| 5.11.0-44-lowlatency   | 3        | 3.37%   |
| 6.2.0-1009-lowlatency  | 2        | 2.25%   |
| 5.8.0-48-lowlatency    | 2        | 2.25%   |
| 5.8.0-44-lowlatency    | 2        | 2.25%   |
| 5.8.0-25-lowlatency    | 2        | 2.25%   |
| 5.4.0-58-lowlatency    | 2        | 2.25%   |
| 5.4.0-56-lowlatency    | 2        | 2.25%   |
| 5.4.0-42-lowlatency    | 2        | 2.25%   |
| 5.4.0-26-lowlatency    | 2        | 2.25%   |
| 5.19.0-1021-lowlatency | 2        | 2.25%   |
| 5.15.0-79-lowlatency   | 2        | 2.25%   |
| 5.15.0-71-lowlatency   | 2        | 2.25%   |
| 5.15.0-56-lowlatency   | 2        | 2.25%   |
| 5.15.0-53-lowlatency   | 2        | 2.25%   |
| 5.15.0-52-lowlatency   | 2        | 2.25%   |
| 5.15.0-46-lowlatency   | 2        | 2.25%   |
| 5.13.0-28-lowlatency   | 2        | 2.25%   |
| 6.5.0-5-lowlatency     | 1        | 1.12%   |
| 6.2.0-1014-lowlatency  | 1        | 1.12%   |
| 6.2.0-1007-lowlatency  | 1        | 1.12%   |
| 5.8.0-50-lowlatency    | 1        | 1.12%   |
| 5.8.0-45-lowlatency    | 1        | 1.12%   |
| 5.8.0-36-lowlatency    | 1        | 1.12%   |
| 5.8.0-34-lowlatency    | 1        | 1.12%   |
| 5.8.0-33-lowlatency    | 1        | 1.12%   |
| 5.8.0-29-lowlatency    | 1        | 1.12%   |
| 5.4.0-99-lowlatency    | 1        | 1.12%   |
| 5.4.0-72-lowlatency    | 1        | 1.12%   |
| 5.4.0-71-lowlatency    | 1        | 1.12%   |
| 5.4.0-70-lowlatency    | 1        | 1.12%   |
| 5.4.0-65-lowlatency    | 1        | 1.12%   |
| 5.4.0-65-generic       | 1        | 1.12%   |
| 5.4.0-64-lowlatency    | 1        | 1.12%   |
| 5.4.0-62-lowlatency    | 1        | 1.12%   |
| 5.4.0-60-lowlatency    | 1        | 1.12%   |
| 5.4.0-53-lowlatency    | 1        | 1.12%   |
| 5.4.0-52-lowlatency    | 1        | 1.12%   |
| 5.4.0-51-lowlatency    | 1        | 1.12%   |
| 5.4.0-48-lowlatency    | 1        | 1.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 36.78%  |
| 5.15.0  | 23       | 26.44%  |
| 5.8.0   | 12       | 13.79%  |
| 5.11.0  | 6        | 6.9%    |
| 6.2.0   | 4        | 4.6%    |
| 5.19.0  | 4        | 4.6%    |
| 5.13.0  | 3        | 3.45%   |
| 6.5.0   | 1        | 1.15%   |
| 5.15.6  | 1        | 1.15%   |
| 4.4.0   | 1        | 1.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 32       | 36.78%  |
| 5.15    | 24       | 27.59%  |
| 5.8     | 12       | 13.79%  |
| 5.11    | 6        | 6.9%    |
| 6.2     | 4        | 4.6%    |
| 5.19    | 4        | 4.6%    |
| 5.13    | 3        | 3.45%   |
| 6.5     | 1        | 1.15%   |
| 4.4     | 1        | 1.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 85       | 98.84%  |
| i686   | 1        | 1.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| XFCE            | 38       | 43.68%  |
| KDE5            | 37       | 42.53%  |
| GNOME           | 5        | 5.75%   |
| MATE            | 2        | 2.3%    |
| LXQt            | 2        | 2.3%    |
| KDE             | 1        | 1.15%   |
| GNOME Flashback | 1        | 1.15%   |
| Cinnamon        | 1        | 1.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 81       | 93.1%   |
| Tty     | 4        | 4.6%    |
| Wayland | 2        | 2.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 35       | 40.7%   |
| TDM     | 25       | 29.07%  |
| LightDM | 19       | 22.09%  |
| GDM     | 6        | 6.98%   |
| GDM3    | 1        | 1.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 33       | 38.37%  |
| de_DE      | 10       | 11.63%  |
| fr_FR      | 8        | 9.3%    |
| en_GB      | 5        | 5.81%   |
| pt_BR      | 4        | 4.65%   |
| it_IT      | 4        | 4.65%   |
| ru_RU      | 3        | 3.49%   |
| en_AU      | 2        | 2.33%   |
| sv_SE      | 1        | 1.16%   |
| nl_NL      | 1        | 1.16%   |
| nl_BE      | 1        | 1.16%   |
| nb_NO      | 1        | 1.16%   |
| fr_FR.UTF8 | 1        | 1.16%   |
| fr_CH      | 1        | 1.16%   |
| fr_BE      | 1        | 1.16%   |
| es_GT      | 1        | 1.16%   |
| es_ES      | 1        | 1.16%   |
| es_AR      | 1        | 1.16%   |
| en_IL      | 1        | 1.16%   |
| en_DE      | 1        | 1.16%   |
| en_CA      | 1        | 1.16%   |
| de_AT      | 1        | 1.16%   |
| ca_ES      | 1        | 1.16%   |
| ca_AD      | 1        | 1.16%   |
| C          | 1        | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 49       | 56.98%  |
| EFI  | 37       | 43.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 84       | 97.67%  |
| Xfs  | 1        | 1.16%   |
| Ext2 | 1        | 1.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 46       | 53.49%  |
| MBR  | 40       | 46.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 75.86%  |
| Yes       | 21       | 24.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 56.32%  |
| Yes       | 38       | 43.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 23       | 26.74%  |
| Gigabyte Technology                  | 14       | 16.28%  |
| Dell                                 | 12       | 13.95%  |
| Hewlett-Packard                      | 10       | 11.63%  |
| MSI                                  | 4        | 4.65%   |
| Fujitsu                              | 4        | 4.65%   |
| ASRock                               | 3        | 3.49%   |
| System76                             | 1        | 1.16%   |
| Shenzhen Meigao Electronic Equipment | 1        | 1.16%   |
| Pegatron                             | 1        | 1.16%   |
| Packard Bell                         | 1        | 1.16%   |
| Medion                               | 1        | 1.16%   |
| Lenovo                               | 1        | 1.16%   |
| Intel                                | 1        | 1.16%   |
| IBM                                  | 1        | 1.16%   |
| Foxconn                              | 1        | 1.16%   |
| ECS                                  | 1        | 1.16%   |
| DEPO Computers                       | 1        | 1.16%   |
| AZW                                  | 1        | 1.16%   |
| Apple                                | 1        | 1.16%   |
| Acidanthera                          | 1        | 1.16%   |
| Acer                                 | 1        | 1.16%   |
| Unknown                              | 1        | 1.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 4        | 4.65%   |
| Dell OptiPlex 790                          | 2        | 2.33%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 2.33%   |
| ASUS PRIME X570-PRO                        | 2        | 2.33%   |
| ASUS M4A785-M                              | 2        | 2.33%   |
| System76 Thelio                            | 1        | 1.16%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 1.16%   |
| Pegatron FL368AA-UUZ SR5612CH              | 1        | 1.16%   |
| Packard Bell IMEDIA S3220                  | 1        | 1.16%   |
| MSI MS-7E02                                | 1        | 1.16%   |
| MSI MS-7C95                                | 1        | 1.16%   |
| MSI MS-7A57                                | 1        | 1.16%   |
| MSI MS-7752                                | 1        | 1.16%   |
| Medion MD34207/C746                        | 1        | 1.16%   |
| Lenovo ThinkCentre M93p 10A8S45S00         | 1        | 1.16%   |
| Intel DQ965GF HD/FP Audio                  | 1        | 1.16%   |
| IBM 8188PPV                                | 1        | 1.16%   |
| HP Z620 Workstation                        | 1        | 1.16%   |
| HP Z2 Tower G4 Workstation                 | 1        | 1.16%   |
| HP ProDesk 600 G1 SFF                      | 1        | 1.16%   |
| HP Compaq Pro 6305 SFF                     | 1        | 1.16%   |
| HP Compaq Elite 8300 CMT                   | 1        | 1.16%   |
| HP Compaq dc7600 Small Form Factor         | 1        | 1.16%   |
| HP Compaq 8200 Elite SFF PC                | 1        | 1.16%   |
| HP Compaq 8100 Elite SFF PC                | 1        | 1.16%   |
| HP Compaq 6200 Pro MT PC                   | 1        | 1.16%   |
| HP Compaq 6005 Pro MT PC                   | 1        | 1.16%   |
| Gigabyte X79S-UP5                          | 1        | 1.16%   |
| Gigabyte X570 AORUS ELITE WIFI             | 1        | 1.16%   |
| Gigabyte H61M-D2-B3                        | 1        | 1.16%   |
| Gigabyte H270-HD3P                         | 1        | 1.16%   |
| Gigabyte H170-HD3-CF                       | 1        | 1.16%   |
| Gigabyte GA-MA770-DS3                      | 1        | 1.16%   |
| Gigabyte F2A78M-HD2                        | 1        | 1.16%   |
| Gigabyte B550M DS3H                        | 1        | 1.16%   |
| Gigabyte B450M S2H                         | 1        | 1.16%   |
| Gigabyte B450 I AORUS PRO WIFI             | 1        | 1.16%   |
| Gigabyte B150M-D2V DDR3                    | 1        | 1.16%   |
| Gigabyte A520M H                           | 1        | 1.16%   |
| Gigabyte A320M-S2H                         | 1        | 1.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 9        | 10.47%  |
| HP Compaq                                  | 7        | 8.14%   |
| ASUS ROG                                   | 4        | 4.65%   |
| ASUS All                                   | 4        | 4.65%   |
| Fujitsu ESPRIMO                            | 3        | 3.49%   |
| ASUS TUF                                   | 3        | 3.49%   |
| Dell Precision                             | 2        | 2.33%   |
| ASUS PRIME                                 | 2        | 2.33%   |
| ASUS P8P67                                 | 2        | 2.33%   |
| ASUS M4A785-M                              | 2        | 2.33%   |
| System76 Thelio                            | 1        | 1.16%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 1.16%   |
| Pegatron FL368AA-UUZ                       | 1        | 1.16%   |
| Packard Bell IMEDIA                        | 1        | 1.16%   |
| MSI MS-7E02                                | 1        | 1.16%   |
| MSI MS-7C95                                | 1        | 1.16%   |
| MSI MS-7A57                                | 1        | 1.16%   |
| MSI MS-7752                                | 1        | 1.16%   |
| Medion MD34207                             | 1        | 1.16%   |
| Lenovo ThinkCentre                         | 1        | 1.16%   |
| Intel DQ965GF                              | 1        | 1.16%   |
| IBM 8188PPV                                | 1        | 1.16%   |
| HP Z620                                    | 1        | 1.16%   |
| HP Z2                                      | 1        | 1.16%   |
| HP ProDesk                                 | 1        | 1.16%   |
| Gigabyte X79S-UP5                          | 1        | 1.16%   |
| Gigabyte X570                              | 1        | 1.16%   |
| Gigabyte H61M-D2-B3                        | 1        | 1.16%   |
| Gigabyte H270-HD3P                         | 1        | 1.16%   |
| Gigabyte H170-HD3-CF                       | 1        | 1.16%   |
| Gigabyte GA-MA770-DS3                      | 1        | 1.16%   |
| Gigabyte F2A78M-HD2                        | 1        | 1.16%   |
| Gigabyte B550M                             | 1        | 1.16%   |
| Gigabyte B450M                             | 1        | 1.16%   |
| Gigabyte B450                              | 1        | 1.16%   |
| Gigabyte B150M-D2V                         | 1        | 1.16%   |
| Gigabyte A520M                             | 1        | 1.16%   |
| Gigabyte A320M-S2H                         | 1        | 1.16%   |
| Gigabyte 970A-DS3P                         | 1        | 1.16%   |
| Fujitsu TERRA                              | 1        | 1.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 12       | 13.95%  |
| 2019 | 8        | 9.3%    |
| 2018 | 8        | 9.3%    |
| 2020 | 7        | 8.14%   |
| 2011 | 7        | 8.14%   |
| 2014 | 5        | 5.81%   |
| 2012 | 5        | 5.81%   |
| 2009 | 5        | 5.81%   |
| 2017 | 4        | 4.65%   |
| 2016 | 4        | 4.65%   |
| 2015 | 4        | 4.65%   |
| 2010 | 4        | 4.65%   |
| 2022 | 3        | 3.49%   |
| 2008 | 3        | 3.49%   |
| 2005 | 3        | 3.49%   |
| 2021 | 2        | 2.33%   |
| 2007 | 2        | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 86       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 85       | 98.84%  |
| Enabled  | 1        | 1.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 86       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 23       | 26.74%  |
| 8.01-16.0   | 17       | 19.77%  |
| 4.01-8.0    | 13       | 15.12%  |
| 32.01-64.0  | 11       | 12.79%  |
| 64.01-256.0 | 10       | 11.63%  |
| 3.01-4.0    | 7        | 8.14%   |
| 1.01-2.0    | 3        | 3.49%   |
| 24.01-32.0  | 1        | 1.16%   |
| 2.01-3.0    | 1        | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 27       | 31.03%  |
| 4.01-8.0   | 19       | 21.84%  |
| 2.01-3.0   | 18       | 20.69%  |
| 3.01-4.0   | 11       | 12.64%  |
| 8.01-16.0  | 8        | 9.2%    |
| 0.51-1.0   | 3        | 3.45%   |
| 24.01-32.0 | 1        | 1.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 33       | 38.37%  |
| 2      | 32       | 37.21%  |
| 3      | 9        | 10.47%  |
| 7      | 3        | 3.49%   |
| 5      | 3        | 3.49%   |
| 4      | 3        | 3.49%   |
| 16     | 1        | 1.16%   |
| 11     | 1        | 1.16%   |
| 10     | 1        | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 48       | 55.81%  |
| No        | 38       | 44.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 86       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 54.65%  |
| Yes       | 39       | 45.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 70.93%  |
| Yes       | 25       | 29.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 20       | 23.26%  |
| Germany                | 13       | 15.12%  |
| France                 | 10       | 11.63%  |
| Italy                  | 7        | 8.14%   |
| Brazil                 | 5        | 5.81%   |
| Belgium                | 4        | 4.65%   |
| Austria                | 4        | 4.65%   |
| Spain                  | 3        | 3.49%   |
| Russia                 | 3        | 3.49%   |
| UK                     | 2        | 2.33%   |
| Sweden                 | 2        | 2.33%   |
| Australia              | 2        | 2.33%   |
| Switzerland            | 1        | 1.16%   |
| Romania                | 1        | 1.16%   |
| Norway                 | 1        | 1.16%   |
| Netherlands            | 1        | 1.16%   |
| Mexico                 | 1        | 1.16%   |
| Luxembourg             | 1        | 1.16%   |
| Kenya                  | 1        | 1.16%   |
| Israel                 | 1        | 1.16%   |
| Guatemala              | 1        | 1.16%   |
| Bosnia and Herzegovina | 1        | 1.16%   |
| Argentina              | 1        | 1.16%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Paris                   | 3        | 3.45%   |
| Houston                 | 3        | 3.45%   |
| Vienna                  | 2        | 2.3%    |
| Stockholm               | 2        | 2.3%    |
| Zanesville              | 1        | 1.15%   |
| Wildenfels              | 1        | 1.15%   |
| West Mifflin            | 1        | 1.15%   |
| Villefontaine           | 1        | 1.15%   |
| Verviers                | 1        | 1.15%   |
| Turin                   | 1        | 1.15%   |
| Tilburg                 | 1        | 1.15%   |
| Stuttgart               | 1        | 1.15%   |
| Sherman Oaks            | 1        | 1.15%   |
| Sarajevo                | 1        | 1.15%   |
| Sao Paulo               | 1        | 1.15%   |
| Santa Barbara d'Oeste   | 1        | 1.15%   |
| San Secondo di Pinerolo | 1        | 1.15%   |
| Saint-Ouen-l'Aumone     | 1        | 1.15%   |
| Rio Grande da Serra     | 1        | 1.15%   |
| Rennes                  | 1        | 1.15%   |
| Potsdam                 | 1        | 1.15%   |
| Pisa                    | 1        | 1.15%   |
| Philadelphia            | 1        | 1.15%   |
| Perth                   | 1        | 1.15%   |
| Palermo                 | 1        | 1.15%   |
| Oslo                    | 1        | 1.15%   |
| Olympia                 | 1        | 1.15%   |
| Oldenburg               | 1        | 1.15%   |
| Novosibirsk             | 1        | 1.15%   |
| Naumburg                | 1        | 1.15%   |
| Namur                   | 1        | 1.15%   |
| Nairobi                 | 1        | 1.15%   |
| Münster                | 1        | 1.15%   |
| Munich                  | 1        | 1.15%   |
| Moscow                  | 1        | 1.15%   |
| Modesto                 | 1        | 1.15%   |
| Miami                   | 1        | 1.15%   |
| Mérida                 | 1        | 1.15%   |
| Merced                  | 1        | 1.15%   |
| Mediglia                | 1        | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 29       | 38     | 17.79%  |
| Seagate               | 27       | 51     | 16.56%  |
| Samsung Electronics   | 27       | 39     | 16.56%  |
| Sandisk               | 11       | 12     | 6.75%   |
| Toshiba               | 9        | 10     | 5.52%   |
| Hitachi               | 7        | 8      | 4.29%   |
| Crucial               | 6        | 6      | 3.68%   |
| Kingston              | 5        | 6      | 3.07%   |
| HGST                  | 4        | 5      | 2.45%   |
| Phison                | 3        | 3      | 1.84%   |
| Intenso               | 3        | 3      | 1.84%   |
| Team                  | 2        | 2      | 1.23%   |
| SPCC                  | 2        | 2      | 1.23%   |
| PNY                   | 2        | 2      | 1.23%   |
| JMicron Technology    | 2        | 2      | 1.23%   |
| Intel                 | 2        | 2      | 1.23%   |
| Corsair               | 2        | 3      | 1.23%   |
| ASMT                  | 2        | 2      | 1.23%   |
| A-DATA Technology     | 2        | 2      | 1.23%   |
| USB 3.0               | 1        | 2      | 0.61%   |
| TO Exter              | 1        | 1      | 0.61%   |
| Silicon Motion        | 1        | 1      | 0.61%   |
| Realtek Semiconductor | 1        | 1      | 0.61%   |
| Phison Electronics    | 1        | 1      | 0.61%   |
| Patriot               | 1        | 1      | 0.61%   |
| OCZ                   | 1        | 1      | 0.61%   |
| NGFF                  | 1        | 1      | 0.61%   |
| Micron Technology     | 1        | 1      | 0.61%   |
| Maxtor                | 1        | 1      | 0.61%   |
| Leven                 | 1        | 1      | 0.61%   |
| Integral              | 1        | 1      | 0.61%   |
| Fujitsu               | 1        | 1      | 0.61%   |
| China                 | 1        | 1      | 0.61%   |
| BHT                   | 1        | 1      | 0.61%   |
| Apple                 | 1        | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 4        | 2.11%   |
| Seagate ST2000DM001-1ER164 2TB  | 4        | 2.11%   |
| Seagate ST2000DM008-2FR102 2TB  | 3        | 1.58%   |
| WDC WDS200T2B0A-00SM50 2TB SSD  | 2        | 1.05%   |
| Toshiba HDWD130 3TB             | 2        | 1.05%   |
| Toshiba DT01ACA050 500GB        | 2        | 1.05%   |
| Team T253X6001T 1024GB SSD      | 2        | 1.05%   |
| SPCC Solid State Disk 256GB     | 2        | 1.05%   |
| Seagate ST5000LM000-2AN170 5TB  | 2        | 1.05%   |
| Seagate Expansion 1TB           | 2        | 1.05%   |
| SanDisk SDSSDA240G 240GB        | 2        | 1.05%   |
| Samsung SSD 970 EVO Plus 500GB  | 2        | 1.05%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 1.05%   |
| Samsung SSD 870 EVO 1TB         | 2        | 1.05%   |
| Samsung SSD 860 EVO 1TB         | 2        | 1.05%   |
| Samsung SSD 850 EVO 500GB       | 2        | 1.05%   |
| Samsung HD753LJ 752GB           | 2        | 1.05%   |
| Kingston SA400S37120G 120GB SSD | 2        | 1.05%   |
| Crucial CT500MX500SSD1 500GB    | 2        | 1.05%   |
| Crucial CT1000MX500SSD1 1TB     | 2        | 1.05%   |
| WDC WDS512G1X0C-00ENX0 512GB    | 1        | 0.53%   |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 0.53%   |
| WDC WD5000BPKT-60PK4T0 500GB    | 1        | 0.53%   |
| WDC WD5000AVDS-63U7B1 500GB     | 1        | 0.53%   |
| WDC WD5000AAKS-75V0A0 500GB     | 1        | 0.53%   |
| WDC WD40EZRZ-00GXCB0 4TB        | 1        | 0.53%   |
| WDC WD40EFRX-68N32N0 4TB        | 1        | 0.53%   |
| WDC WD40EFAX-68JH4N1 4TB        | 1        | 0.53%   |
| WDC WD40EFAX-68JH4N0 4TB        | 1        | 0.53%   |
| WDC WD3200BUCT-63TWBY0 320GB    | 1        | 0.53%   |
| WDC WD3200BPVT-75JJ5T0 320GB    | 1        | 0.53%   |
| WDC WD3200BEVT-22ZCT0 320GB     | 1        | 0.53%   |
| WDC WD3200AAKS-00VYA0 320GB     | 1        | 0.53%   |
| WDC WD30EZRZ-00Z5HB0 3TB        | 1        | 0.53%   |
| WDC WD30EZRX-00SPEB0 3TB        | 1        | 0.53%   |
| WDC WD2500BEVT-80A23T0 250GB    | 1        | 0.53%   |
| WDC WD2500AAKX-001CA0 250GB     | 1        | 0.53%   |
| WDC WD20PURZ-85GU6Y0 2TB        | 1        | 0.53%   |
| WDC WD20EZRZ-00Z5HB0 2TB        | 1        | 0.53%   |
| WDC WD20EZRX-00D8PB0 2TB        | 1        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 50     | 34.18%  |
| WDC                 | 26       | 35     | 32.91%  |
| Toshiba             | 9        | 10     | 11.39%  |
| Hitachi             | 7        | 8      | 8.86%   |
| HGST                | 4        | 5      | 5.06%   |
| Samsung Electronics | 3        | 3      | 3.8%    |
| USB 3.0             | 1        | 2      | 1.27%   |
| Maxtor              | 1        | 1      | 1.27%   |
| Fujitsu             | 1        | 1      | 1.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 15       | 20     | 24.59%  |
| SanDisk             | 10       | 11     | 16.39%  |
| Crucial             | 6        | 6      | 9.84%   |
| Kingston            | 5        | 6      | 8.2%    |
| Intenso             | 3        | 3      | 4.92%   |
| WDC                 | 2        | 2      | 3.28%   |
| Team                | 2        | 2      | 3.28%   |
| SPCC                | 2        | 2      | 3.28%   |
| PNY                 | 2        | 2      | 3.28%   |
| ASMT                | 2        | 2      | 3.28%   |
| A-DATA Technology   | 2        | 2      | 3.28%   |
| TO Exter            | 1        | 1      | 1.64%   |
| Patriot             | 1        | 1      | 1.64%   |
| OCZ                 | 1        | 1      | 1.64%   |
| NGFF                | 1        | 1      | 1.64%   |
| Micron Technology   | 1        | 1      | 1.64%   |
| Leven               | 1        | 1      | 1.64%   |
| Integral            | 1        | 1      | 1.64%   |
| Corsair             | 1        | 1      | 1.64%   |
| China               | 1        | 1      | 1.64%   |
| BHT                 | 1        | 1      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 56       | 115    | 44.44%  |
| SSD     | 48       | 68     | 38.1%   |
| NVMe    | 20       | 30     | 15.87%  |
| Unknown | 2        | 2      | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 79       | 171    | 73.15%  |
| NVMe | 20       | 29     | 18.52%  |
| SAS  | 9        | 15     | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 54       | 79     | 43.9%   |
| 0.51-1.0   | 34       | 47     | 27.64%  |
| 1.01-2.0   | 17       | 20     | 13.82%  |
| 3.01-4.0   | 8        | 10     | 6.5%    |
| 4.01-10.0  | 6        | 22     | 4.88%   |
| 2.01-3.0   | 4        | 5      | 3.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 22       | 25.29%  |
| 501-1000       | 19       | 21.84%  |
| 1001-2000      | 16       | 18.39%  |
| More than 3000 | 14       | 16.09%  |
| 251-500        | 8        | 9.2%    |
| 51-100         | 4        | 4.6%    |
| 21-50          | 2        | 2.3%    |
| 2001-3000      | 1        | 1.15%   |
| 1-20           | 1        | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 21       | 23.86%  |
| 21-50          | 14       | 15.91%  |
| 101-250        | 12       | 13.64%  |
| More than 3000 | 9        | 10.23%  |
| 251-500        | 9        | 10.23%  |
| 51-100         | 7        | 7.95%   |
| 1001-2000      | 6        | 6.82%   |
| 501-1000       | 6        | 6.82%   |
| 2001-3000      | 4        | 4.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 3        | 3      | 13.04%  |
| Samsung Electronics HD753LJ 752GB     | 2        | 2      | 8.7%    |
| WDC WD5000AVDS-63U7B1 500GB           | 1        | 1      | 4.35%   |
| WDC WD1600AAJS-08L7A0 160GB           | 1        | 1      | 4.35%   |
| WDC WD10EZEX-22BN5A0 1TB              | 1        | 1      | 4.35%   |
| WDC WD10EAVS-32D7B1 1TB               | 1        | 1      | 4.35%   |
| WDC WD10EADS-00M2B0 1TB               | 1        | 1      | 4.35%   |
| Toshiba MQ01ABF050 500GB              | 1        | 1      | 4.35%   |
| Toshiba HDWE140 4TB                   | 1        | 1      | 4.35%   |
| Seagate ST8000DM004-2CX1 8TB          | 1        | 6      | 4.35%   |
| Seagate ST3320820AS 320GB             | 1        | 1      | 4.35%   |
| Seagate ST3200822AS 200GB             | 1        | 1      | 4.35%   |
| Seagate ST1000VM002-9ZL162 1TB        | 1        | 1      | 4.35%   |
| Samsung Electronics SSD 960 PRO 512GB | 1        | 1      | 4.35%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1        | 2      | 4.35%   |
| Hitachi HDS721010CLA332 1TB           | 1        | 1      | 4.35%   |
| Hitachi HDS5C1010CLA382 1TB           | 1        | 1      | 4.35%   |
| HGST HTS721010A9 1TB                  | 1        | 1      | 4.35%   |
| A-DATA Technology SU650 240GB SSD     | 1        | 1      | 4.35%   |
| A-DATA Technology SP550 240GB SSD     | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 12     | 31.82%  |
| WDC                 | 4        | 5      | 18.18%  |
| Samsung Electronics | 4        | 5      | 18.18%  |
| Toshiba             | 2        | 2      | 9.09%   |
| Hitachi             | 2        | 2      | 9.09%   |
| A-DATA Technology   | 2        | 2      | 9.09%   |
| HGST                | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 12     | 38.89%  |
| WDC                 | 4        | 5      | 22.22%  |
| Toshiba             | 2        | 2      | 11.11%  |
| Samsung Electronics | 2        | 2      | 11.11%  |
| Hitachi             | 2        | 2      | 11.11%  |
| HGST                | 1        | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 24     | 80%     |
| SSD  | 3        | 4      | 15%     |
| NVMe | 1        | 1      | 5%      |

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
| Works    | 80       | 168    | 71.43%  |
| Malfunc  | 20       | 29     | 17.86%  |
| Detected | 10       | 16     | 8.93%   |
| Failed   | 2        | 2      | 1.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 56       | 45.9%   |
| AMD                       | 26       | 21.31%  |
| Samsung Electronics       | 11       | 9.02%   |
| Phison Electronics        | 5        | 4.1%    |
| Marvell Technology Group  | 5        | 4.1%    |
| ASMedia Technology        | 5        | 4.1%    |
| Nvidia                    | 3        | 2.46%   |
| SanDisk                   | 2        | 1.64%   |
| JMicron Technology        | 2        | 1.64%   |
| VIA Technologies          | 1        | 0.82%   |
| Silicon Motion            | 1        | 0.82%   |
| Silicon Image             | 1        | 0.82%   |
| Realtek Semiconductor     | 1        | 0.82%   |
| LSI Logic / Symbios Logic | 1        | 0.82%   |
| Apple                     | 1        | 0.82%   |
| Adaptec                   | 1        | 0.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 9.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 7.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 5.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 4.58%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 3.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 3.27%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 3.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 3.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 2.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.61%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.61%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 2.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.96%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.96%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.31%   |
| Phison E12 NVMe Controller                                                              | 2        | 1.31%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2        | 1.31%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 2        | 1.31%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 1.31%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.31%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.31%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.31%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.31%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 0.65%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.65%   |
| SanDisk WD Black NVMe SSD                                                               | 1        | 0.65%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 1        | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.65%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 1        | 0.65%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 1        | 0.65%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.65%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.65%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 0.65%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1        | 0.65%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.65%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 71       | 58.68%  |
| IDE  | 22       | 18.18%  |
| NVMe | 20       | 16.53%  |
| RAID | 4        | 3.31%   |
| SAS  | 3        | 2.48%   |
| SCSI | 1        | 0.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 57       | 66.28%  |
| AMD    | 29       | 33.72%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz        | 3        | 3.49%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3        | 3.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2        | 2.33%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2        | 2.33%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2        | 2.33%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2        | 2.33%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2        | 2.33%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 2        | 2.33%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 2        | 2.33%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2        | 2.33%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2        | 2.33%   |
| AMD Phenom II X4 945 Processor          | 2        | 2.33%   |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1        | 1.16%   |
| Intel Xeon CPU E5420 @ 2.50GHz          | 1        | 1.16%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz     | 1        | 1.16%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1        | 1.16%   |
| Intel Pentium D CPU 3.40GHz             | 1        | 1.16%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1        | 1.16%   |
| Intel Pentium 4 CPU 3.20GHz             | 1        | 1.16%   |
| Intel Pentium 4 CPU 2.80GHz             | 1        | 1.16%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 1        | 1.16%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1        | 1.16%   |
| Intel Core i9-10900 CPU @ 2.80GHz       | 1        | 1.16%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 1        | 1.16%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 1        | 1.16%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1        | 1.16%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1        | 1.16%   |
| Intel Core i7-3930K CPU @ 3.20GHz       | 1        | 1.16%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1        | 1.16%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1        | 1.16%   |
| Intel Core i7 CPU 930 @ 2.80GHz         | 1        | 1.16%   |
| Intel Core i5-9400T CPU @ 1.80GHz       | 1        | 1.16%   |
| Intel Core i5-8600K CPU @ 3.60GHz       | 1        | 1.16%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 1        | 1.16%   |
| Intel Core i5-7600K CPU @ 3.80GHz       | 1        | 1.16%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 1        | 1.16%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 1        | 1.16%   |
| Intel Core i5-3330 CPU @ 3.00GHz        | 1        | 1.16%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 1        | 1.16%   |
| Intel Core i5-2500 CPU @ 3.30GHz        | 1        | 1.16%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 22       | 25.58%  |
| Intel Core i7          | 12       | 13.95%  |
| Intel Core i3          | 8        | 9.3%    |
| AMD Ryzen 9            | 6        | 6.98%   |
| AMD Ryzen 5            | 5        | 5.81%   |
| Intel Xeon             | 4        | 4.65%   |
| AMD Phenom II X4       | 4        | 4.65%   |
| Intel Core i9          | 3        | 3.49%   |
| Intel Pentium 4        | 2        | 2.33%   |
| AMD Ryzen 7            | 2        | 2.33%   |
| AMD FX                 | 2        | 2.33%   |
| AMD Athlon II X2       | 2        | 2.33%   |
| Other                  | 1        | 1.16%   |
| Intel Pentium D        | 1        | 1.16%   |
| Intel Pentium          | 1        | 1.16%   |
| Intel Core 2 Duo       | 1        | 1.16%   |
| Intel Core 2           | 1        | 1.16%   |
| Intel Celeron          | 1        | 1.16%   |
| AMD Ryzen Threadripper | 1        | 1.16%   |
| AMD Ryzen 3            | 1        | 1.16%   |
| AMD E                  | 1        | 1.16%   |
| AMD Athlon X4          | 1        | 1.16%   |
| AMD Athlon Dual Core   | 1        | 1.16%   |
| AMD Athlon 64 X2       | 1        | 1.16%   |
| AMD A4                 | 1        | 1.16%   |
| AMD A10                | 1        | 1.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 38       | 44.19%  |
| 2      | 19       | 22.09%  |
| 6      | 10       | 11.63%  |
| 8      | 8        | 9.3%    |
| 10     | 3        | 3.49%   |
| 1      | 3        | 3.49%   |
| 16     | 2        | 2.33%   |
| 12     | 2        | 2.33%   |
| 32     | 1        | 1.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 85       | 98.84%  |
| 2      | 1        | 1.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 47       | 54.65%  |
| 1      | 39       | 45.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 85       | 98.84%  |
| 32-bit         | 1        | 1.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 12       | 13.95%  |
| Unknown    | 11       | 12.79%  |
| 0x206a7    | 7        | 8.14%   |
| 0x306a9    | 6        | 6.98%   |
| 0x506e3    | 4        | 4.65%   |
| 0x08701021 | 4        | 4.65%   |
| 0x906ea    | 3        | 3.49%   |
| 0x0a50000d | 3        | 3.49%   |
| 0x010000c8 | 3        | 3.49%   |
| 0xf41      | 2        | 2.33%   |
| 0xa0655    | 2        | 2.33%   |
| 0x906ed    | 2        | 2.33%   |
| 0x206d7    | 2        | 2.33%   |
| 0x10676    | 2        | 2.33%   |
| 0x010000b6 | 2        | 2.33%   |
| 0xf65      | 1        | 1.16%   |
| 0x906ec    | 1        | 1.16%   |
| 0x90675    | 1        | 1.16%   |
| 0x6f6      | 1        | 1.16%   |
| 0x506ca    | 1        | 1.16%   |
| 0x50654    | 1        | 1.16%   |
| 0x306f2    | 1        | 1.16%   |
| 0x20655    | 1        | 1.16%   |
| 0x106a5    | 1        | 1.16%   |
| 0x0a50000c | 1        | 1.16%   |
| 0x0a20120a | 1        | 1.16%   |
| 0x0a201009 | 1        | 1.16%   |
| 0x08701013 | 1        | 1.16%   |
| 0x08301039 | 1        | 1.16%   |
| 0x08108109 | 1        | 1.16%   |
| 0x08101016 | 1        | 1.16%   |
| 0x06003106 | 1        | 1.16%   |
| 0x06001119 | 1        | 1.16%   |
| 0x06000852 | 1        | 1.16%   |
| 0x0600081f | 1        | 1.16%   |
| 0x010000c7 | 1        | 1.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 13       | 15.12%  |
| SandyBridge      | 9        | 10.47%  |
| Zen 2            | 8        | 9.3%    |
| KabyLake         | 8        | 9.3%    |
| Skylake          | 7        | 8.14%   |
| IvyBridge        | 7        | 8.14%   |
| Zen 3            | 6        | 6.98%   |
| K10              | 6        | 6.98%   |
| Piledriver       | 3        | 3.49%   |
| NetBurst         | 3        | 3.49%   |
| Westmere         | 2        | 2.33%   |
| Penryn           | 2        | 2.33%   |
| K8 Hammer        | 2        | 2.33%   |
| CometLake        | 2        | 2.33%   |
| Zen+             | 1        | 1.16%   |
| Zen              | 1        | 1.16%   |
| Steamroller      | 1        | 1.16%   |
| Nehalem          | 1        | 1.16%   |
| Goldmont         | 1        | 1.16%   |
| Excavator        | 1        | 1.16%   |
| Core             | 1        | 1.16%   |
| Alderlake Hybrid | 1        | 1.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 43       | 46.24%  |
| Intel  | 29       | 31.18%  |
| AMD    | 21       | 22.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 7.37%   |
| Intel HD Graphics 530                                                       | 4        | 4.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 4.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 4.21%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 3.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.16%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 3.16%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.11%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 2.11%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 2.11%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 2.11%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 2.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.11%   |
| Intel HD Graphics 630                                                       | 2        | 2.11%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.11%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 2.11%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 2.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.11%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.05%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 1.05%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1        | 1.05%   |
| Nvidia GT216 [GeForce 315]                                                  | 1        | 1.05%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.05%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.05%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.05%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.05%   |
| Nvidia GK208 [GeForce GT 720]                                               | 1        | 1.05%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 1.05%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.05%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.05%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.05%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.05%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 1.05%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.05%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 1.05%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.05%   |
| Nvidia G98 [Quadro NVS 450]                                                 | 1        | 1.05%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.05%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 39       | 45.35%  |
| 1 x Intel      | 23       | 26.74%  |
| 1 x AMD        | 19       | 22.09%  |
| Intel + Nvidia | 2        | 2.33%   |
| 2 x Nvidia     | 1        | 1.16%   |
| 2 x AMD        | 1        | 1.16%   |
| AMD + Nvidia   | 1        | 1.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 59       | 67.82%  |
| Proprietary | 28       | 32.18%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 31.03%  |
| 1.01-2.0   | 15       | 17.24%  |
| 0.01-0.5   | 13       | 14.94%  |
| 0.51-1.0   | 10       | 11.49%  |
| 7.01-8.0   | 7        | 8.05%   |
| 3.01-4.0   | 6        | 6.9%    |
| 8.01-16.0  | 4        | 4.6%    |
| 5.01-6.0   | 3        | 3.45%   |
| 2.01-3.0   | 1        | 1.15%   |
| 16.01-24.0 | 1        | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 16       | 16.49%  |
| Goldstar             | 10       | 10.31%  |
| Dell                 | 9        | 9.28%   |
| Acer                 | 9        | 9.28%   |
| Philips              | 8        | 8.25%   |
| Hewlett-Packard      | 8        | 8.25%   |
| Ancor Communications | 6        | 6.19%   |
| AOC                  | 3        | 3.09%   |
| ONN                  | 2        | 2.06%   |
| Fujitsu Siemens      | 2        | 2.06%   |
| Eizo                 | 2        | 2.06%   |
| BenQ                 | 2        | 2.06%   |
| ASUSTek Computer     | 2        | 2.06%   |
| ViewSonic            | 1        | 1.03%   |
| VIE                  | 1        | 1.03%   |
| Unknown              | 1        | 1.03%   |
| TVT                  | 1        | 1.03%   |
| TCH                  | 1        | 1.03%   |
| Targa Visionary      | 1        | 1.03%   |
| Sony                 | 1        | 1.03%   |
| Seiki                | 1        | 1.03%   |
| Onkyo                | 1        | 1.03%   |
| NEC Computers        | 1        | 1.03%   |
| MSI                  | 1        | 1.03%   |
| Medion               | 1        | 1.03%   |
| KTC                  | 1        | 1.03%   |
| Iiyama               | 1        | 1.03%   |
| Hannspree            | 1        | 1.03%   |
| DENON                | 1        | 1.03%   |
| Apple                | 1        | 1.03%   |
| Unknown              | 1        | 1.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                     | 2        | 1.87%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 2        | 1.87%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch              | 1        | 0.93%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                   | 1        | 0.93%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                   | 1        | 0.93%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                          | 1        | 0.93%   |
| TCH TYPE-C TCH5600 1920x1080 344x194mm 15.5-inch                        | 1        | 0.93%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch     | 1        | 0.93%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                      | 1        | 0.93%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                     | 1        | 0.93%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1        | 0.93%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch    | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch    | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch     | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch    | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch    | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch    | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch    | 1        | 0.93%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch    | 1        | 0.93%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch     | 1        | 0.93%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch     | 1        | 0.93%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch      | 1        | 0.93%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1        | 0.93%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch    | 1        | 0.93%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.93%   |
| Samsung Electronics LCD Monitor SyncMaster                              | 1        | 0.93%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 0.93%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 580x320mm 26.1-inch    | 1        | 0.93%   |
| Samsung Electronics LCD Monitor S34J55x 3440x1440                       | 1        | 0.93%   |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch       | 1        | 0.93%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch               | 1        | 0.93%   |
| Philips PHL 278E8Q PHLC161 1920x1080 598x336mm 27.0-inch                | 1        | 0.93%   |
| Philips 247E4 PHLC0C0 1920x1080 521x293mm 23.5-inch                     | 1        | 0.93%   |
| Philips 227E4LH PHLC0AC 1920x1080 477x268mm 21.5-inch                   | 1        | 0.93%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 1        | 0.93%   |
| Philips 201E PHLC033 1600x900 443x249mm 20.0-inch                       | 1        | 0.93%   |
| Philips 190V PHL0847 1280x1024 376x301mm 19.0-inch                      | 1        | 0.93%   |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                      | 1        | 0.93%   |
| Onkyo HT-R494 ONK0F43 3840x2160 1150x650mm 52.0-inch                    | 1        | 0.93%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 44       | 46.81%  |
| 3840x2160 (4K)     | 10       | 10.64%  |
| 1280x1024 (SXGA)   | 9        | 9.57%   |
| 1680x1050 (WSXGA+) | 7        | 7.45%   |
| 1920x1200 (WUXGA)  | 4        | 4.26%   |
| 2560x1440 (QHD)    | 3        | 3.19%   |
| 1440x900 (WXGA+)   | 3        | 3.19%   |
| 1366x768 (WXGA)    | 3        | 3.19%   |
| 1600x900 (HD+)     | 2        | 2.13%   |
| 1360x768           | 2        | 2.13%   |
| Unknown            | 2        | 2.13%   |
| 5760x2160          | 1        | 1.06%   |
| 3440x1440          | 1        | 1.06%   |
| 3280x1080          | 1        | 1.06%   |
| 1600x1200          | 1        | 1.06%   |
| 1400x1050          | 1        | 1.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 16       | 16.49%  |
| 27      | 13       | 13.4%   |
| 21      | 13       | 13.4%   |
| 24      | 12       | 12.37%  |
| 22      | 7        | 7.22%   |
| 19      | 7        | 7.22%   |
| 31      | 6        | 6.19%   |
| 17      | 5        | 5.15%   |
| 18      | 4        | 4.12%   |
| 20      | 3        | 3.09%   |
| Unknown | 3        | 3.09%   |
| 15      | 2        | 2.06%   |
| 84      | 1        | 1.03%   |
| 65      | 1        | 1.03%   |
| 52      | 1        | 1.03%   |
| 50      | 1        | 1.03%   |
| 43      | 1        | 1.03%   |
| 32      | 1        | 1.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 37       | 39.78%  |
| 401-500     | 28       | 30.11%  |
| 601-700     | 8        | 8.6%    |
| 301-350     | 7        | 7.53%   |
| 351-400     | 4        | 4.3%    |
| 1001-1500   | 3        | 3.23%   |
| Unknown     | 3        | 3.23%   |
| 701-800     | 1        | 1.08%   |
| 1501-2000   | 1        | 1.08%   |
| 901-1000    | 1        | 1.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 60       | 67.42%  |
| 16/10   | 15       | 16.85%  |
| 5/4     | 8        | 8.99%   |
| Unknown | 3        | 3.37%   |
| 4/3     | 2        | 2.25%   |
| 3/2     | 1        | 1.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 39       | 41.94%  |
| 301-350        | 13       | 13.98%  |
| 151-200        | 11       | 11.83%  |
| 141-150        | 9        | 9.68%   |
| 351-500        | 7        | 7.53%   |
| More than 1000 | 4        | 4.3%    |
| 251-300        | 4        | 4.3%    |
| Unknown        | 3        | 3.23%   |
| 111-120        | 1        | 1.08%   |
| 101-110        | 1        | 1.08%   |
| 501-1000       | 1        | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 62       | 70.45%  |
| 101-120 | 17       | 19.32%  |
| 121-160 | 4        | 4.55%   |
| Unknown | 3        | 3.41%   |
| 1-50    | 1        | 1.14%   |
| 161-240 | 1        | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 60       | 69.77%  |
| 2     | 26       | 30.23%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 48       | 37.5%   |
| Intel                           | 42       | 32.81%  |
| Qualcomm Atheros                | 11       | 8.59%   |
| Broadcom                        | 5        | 3.91%   |
| TP-Link                         | 3        | 2.34%   |
| Nvidia                          | 3        | 2.34%   |
| MediaTek                        | 3        | 2.34%   |
| Broadcom Limited                | 2        | 1.56%   |
| Aquantia                        | 2        | 1.56%   |
| ZyDAS                           | 1        | 0.78%   |
| Wacom                           | 1        | 0.78%   |
| Ralink Technology               | 1        | 0.78%   |
| Qualcomm Atheros Communications | 1        | 0.78%   |
| NetGear                         | 1        | 0.78%   |
| Microsoft                       | 1        | 0.78%   |
| InterBiometrics                 | 1        | 0.78%   |
| Input Club                      | 1        | 0.78%   |
| ASIX Electronics                | 1        | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 41       | 29.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 7.14%   |
| Intel I211 Gigabit Network Connection                                         | 6        | 4.29%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 3.57%   |
| Intel Wireless-AC 9260                                                        | 4        | 2.86%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 1.43%   |
| Realtek 802.11ac NIC                                                          | 2        | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 1.43%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2        | 1.43%   |
| Nvidia MCP77 Ethernet                                                         | 2        | 1.43%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 1.43%   |
| Intel Ethernet Controller I225-V                                              | 2        | 1.43%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.43%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 1.43%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.43%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 1.43%   |
| ZyDAS ZD1211B 802.11g                                                         | 1        | 0.71%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1        | 0.71%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.71%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 0.71%   |
| TP-Link 802.11ac NIC                                                          | 1        | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.71%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.71%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1        | 0.71%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.71%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.71%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 0.71%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.71%   |
| Realtek 802.11ax WLAN Adapter                                                 | 1        | 0.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.71%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.71%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.71%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 0.71%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.71%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 24.39%  |
| Qualcomm Atheros                | 9        | 21.95%  |
| Realtek Semiconductor           | 8        | 19.51%  |
| TP-Link                         | 3        | 7.32%   |
| MediaTek                        | 3        | 7.32%   |
| Broadcom                        | 2        | 4.88%   |
| ZyDAS                           | 1        | 2.44%   |
| Wacom                           | 1        | 2.44%   |
| Ralink Technology               | 1        | 2.44%   |
| Qualcomm Atheros Communications | 1        | 2.44%   |
| NetGear                         | 1        | 2.44%   |
| Microsoft                       | 1        | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wireless-AC 9260                                                        | 4        | 9.76%   |
| Realtek 802.11ac NIC                                                          | 2        | 4.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 4.88%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2        | 4.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 4.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 4.88%   |
| ZyDAS ZD1211B 802.11g                                                         | 1        | 2.44%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1        | 2.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 2.44%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 2.44%   |
| TP-Link 802.11ac NIC                                                          | 1        | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 2.44%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1        | 2.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 2.44%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 2.44%   |
| Realtek 802.11ax WLAN Adapter                                                 | 1        | 2.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 2.44%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 2.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 2.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 2.44%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 2.44%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 2.44%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                   | 1        | 2.44%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 2.44%   |
| MediaTek 802.11 n WLAN                                                        | 1        | 2.44%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 2.44%   |
| Intel Wireless 3165                                                           | 1        | 2.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 2.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 2.44%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                            | 1        | 2.44%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                  | 1        | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 44       | 46.32%  |
| Intel                 | 38       | 40%     |
| Nvidia                | 3        | 3.16%   |
| Broadcom              | 3        | 3.16%   |
| Qualcomm Atheros      | 2        | 2.11%   |
| Broadcom Limited      | 2        | 2.11%   |
| Aquantia              | 2        | 2.11%   |
| ASIX Electronics      | 1        | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41       | 42.27%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 10.31%  |
| Intel I211 Gigabit Network Connection                             | 6        | 6.19%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 5.15%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 4.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 2.06%   |
| Nvidia MCP77 Ethernet                                             | 2        | 2.06%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.06%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.06%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 2.06%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.06%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.06%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.03%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.03%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.03%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.03%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.03%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.03%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.03%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 1.03%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 1.03%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.03%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.03%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 1.03%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 1.03%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 1.03%   |
| ASIX AX88772B                                                     | 1        | 1.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 86       | 67.72%  |
| WiFi     | 39       | 30.71%  |
| Modem    | 2        | 1.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 77       | 81.91%  |
| WiFi     | 17       | 18.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 54       | 62.79%  |
| 2     | 29       | 33.72%  |
| 3     | 3        | 3.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 72       | 82.76%  |
| Yes  | 15       | 17.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 38.46%  |
| Cambridge Silicon Radio         | 6        | 23.08%  |
| ASUSTek Computer                | 3        | 11.54%  |
| Realtek Semiconductor           | 2        | 7.69%   |
| Qualcomm Atheros Communications | 2        | 7.69%   |
| MediaTek                        | 2        | 7.69%   |
| Broadcom                        | 1        | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 23.08%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 15.38%  |
| Realtek Bluetooth Radio                             | 2        | 7.69%   |
| MediaTek Wireless_Device                            | 2        | 7.69%   |
| Intel Bluetooth wireless interface                  | 2        | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 7.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 7.69%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 3.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 3.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.85%   |
| Intel AX210 Bluetooth                               | 1        | 3.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 3.85%   |
| ASUS BCM20702A0                                     | 1        | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 52       | 30.77%  |
| Nvidia                               | 37       | 21.89%  |
| AMD                                  | 31       | 18.34%  |
| C-Media Electronics                  | 6        | 3.55%   |
| Texas Instruments                    | 4        | 2.37%   |
| Yamaha                               | 3        | 1.78%   |
| M-Audio                              | 3        | 1.78%   |
| JMTek                                | 3        | 1.78%   |
| PreSonus Audio Electronics           | 2        | 1.18%   |
| Logitech                             | 2        | 1.18%   |
| ZOOM                                 | 1        | 0.59%   |
| Xilinx                               | 1        | 0.59%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.59%   |
| Textech International                | 1        | 0.59%   |
| Tenx Technology                      | 1        | 0.59%   |
| TEAC                                 | 1        | 0.59%   |
| Studiologic                          | 1        | 0.59%   |
| SteelSeries ApS                      | 1        | 0.59%   |
| Samson Technologies                  | 1        | 0.59%   |
| QinHeng Electronics                  | 1        | 0.59%   |
| Plantronics                          | 1        | 0.59%   |
| MIDITECH                             | 1        | 0.59%   |
| Medeli Electronics                   | 1        | 0.59%   |
| Mark of the Unicorn                  | 1        | 0.59%   |
| KTMicro                              | 1        | 0.59%   |
| Harman                               | 1        | 0.59%   |
| Generalplus Technology               | 1        | 0.59%   |
| Focusrite-Novation                   | 1        | 0.59%   |
| Ensoniq                              | 1        | 0.59%   |
| Creative Technology                  | 1        | 0.59%   |
| BEHRINGER International              | 1        | 0.59%   |
| Audient                              | 1        | 0.59%   |
| ASUSTek Computer                     | 1        | 0.59%   |
| Apple                                | 1        | 0.59%   |
| Alesis                               | 1        | 0.59%   |
| AKAI Professional M.I.               | 1        | 0.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12       | 6.19%   |
| AMD Starship/Matisse HD Audio Controller                                          | 9        | 4.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 8        | 4.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 3.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6        | 3.09%   |
| AMD Family 17h/19h HD Audio Controller                                            | 6        | 3.09%   |
| Intel Cannon Lake PCH cAVS                                                        | 5        | 2.58%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 2.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 2.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 2.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 2.06%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3        | 1.55%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 1.55%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 1.55%   |
| AMD FCH Azalia Controller                                                         | 3        | 1.55%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.55%   |
| PreSonus Audio Electronics Studio 24c                                             | 2        | 1.03%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 1.03%   |
| Nvidia High Definition Audio Controller                                           | 2        | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 1.03%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 1.03%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 1.03%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 1.03%   |
| M-Audio M-Track                                                                   | 2        | 1.03%   |
| JMTek USB PnP Audio Device                                                        | 2        | 1.03%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 1.03%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 2        | 1.03%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 2        | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 1.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 1.03%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 1.03%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 1.03%   |
| ZOOM U-22                                                                         | 1        | 0.52%   |
| Yamaha YMF-744B [DS-1S Audio Controller]                                          | 1        | 0.52%   |
| Yamaha MG-XU                                                                      | 1        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 15       | 13.89%  |
| Kingston            | 14       | 12.96%  |
| Samsung Electronics | 13       | 12.04%  |
| Unknown             | 12       | 11.11%  |
| Crucial             | 11       | 10.19%  |
| Corsair             | 11       | 10.19%  |
| G.Skill             | 8        | 7.41%   |
| Micron Technology   | 6        | 5.56%   |
| Patriot             | 4        | 3.7%    |
| A-DATA Technology   | 2        | 1.85%   |
| Unifosa             | 1        | 0.93%   |
| Smart               | 1        | 0.93%   |
| S                   | 1        | 0.93%   |
| PNY                 | 1        | 0.93%   |
| OCZ                 | 1        | 0.93%   |
| Nanya Technology    | 1        | 0.93%   |
| M                   | 1        | 0.93%   |
| HBS                 | 1        | 0.93%   |
| Goldkey             | 1        | 0.93%   |
| Elpida              | 1        | 0.93%   |
| Aeneon              | 1        | 0.93%   |
| 0194808980CE        | 1        | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s         | 3        | 2.44%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s          | 3        | 2.44%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 3        | 2.44%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                     | 2        | 1.63%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                    | 2        | 1.63%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s        | 2        | 1.63%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s         | 2        | 1.63%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 2        | 1.63%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s       | 2        | 1.63%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s      | 2        | 1.63%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1        | 0.81%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                   | 1        | 0.81%   |
| Unknown RAM Module 512MB DIMM DDR                           | 1        | 0.81%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s                    | 1        | 0.81%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1        | 0.81%   |
| Unknown RAM Module 256MB DIMM DDR                           | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1        | 0.81%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1        | 0.81%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                    | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM DDR                          | 1        | 0.81%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1        | 0.81%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s                 | 1        | 0.81%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM DDR3 1333MT/s        | 1        | 0.81%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s          | 1        | 0.81%   |
| SK hynix RAM TMT41GU6BFR8C-PBSC 8192MB DIMM DDR3 1600MT/s   | 1        | 0.81%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 0.81%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2666MT/s               | 1        | 0.81%   |
| SK hynix RAM Module 32GB DIMM DDR4 2667MT/s                 | 1        | 0.81%   |
| SK hynix RAM HYMP564U64BP8-C4 512MB DIMM DDR 533MT/s        | 1        | 0.81%   |
| SK hynix RAM HYMP125F72CP8N3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.81%   |
| SK hynix RAM HYMP125F72CP8D3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.81%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s        | 1        | 0.81%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1        | 0.81%   |
| SK hynix RAM HMT351U7CFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1        | 0.81%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s        | 1        | 0.81%   |
| SK hynix RAM HMT325U7CFR8C-PB 2GB DIMM DDR3 1600MT/s        | 1        | 0.81%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s        | 1        | 0.81%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 0.81%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 39       | 43.82%  |
| DDR4    | 33       | 37.08%  |
| DDR2    | 7        | 7.87%   |
| Unknown | 5        | 5.62%   |
| DDR     | 3        | 3.37%   |
| SDRAM   | 2        | 2.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 78       | 89.66%  |
| SODIMM  | 7        | 8.05%   |
| RIMM    | 1        | 1.15%   |
| FB-DIMM | 1        | 1.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 28       | 28%     |
| 8192  | 26       | 26%     |
| 2048  | 13       | 13%     |
| 16384 | 12       | 12%     |
| 32768 | 10       | 10%     |
| 1024  | 8        | 8%      |
| 512   | 2        | 2%      |
| 256   | 1        | 1%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 24       | 23.76%  |
| 1333    | 11       | 10.89%  |
| 3600    | 7        | 6.93%   |
| 3200    | 6        | 5.94%   |
| 2133    | 6        | 5.94%   |
| 1866    | 5        | 4.95%   |
| 667     | 5        | 4.95%   |
| 3266    | 4        | 3.96%   |
| 1800    | 4        | 3.96%   |
| 1066    | 4        | 3.96%   |
| 2667    | 3        | 2.97%   |
| 2400    | 3        | 2.97%   |
| 800     | 3        | 2.97%   |
| 2933    | 2        | 1.98%   |
| 1867    | 2        | 1.98%   |
| 533     | 2        | 1.98%   |
| Unknown | 2        | 1.98%   |
| 3500    | 1        | 0.99%   |
| 3466    | 1        | 0.99%   |
| 3000    | 1        | 0.99%   |
| 2934    | 1        | 0.99%   |
| 2800    | 1        | 0.99%   |
| 2666    | 1        | 0.99%   |
| 2472    | 1        | 0.99%   |
| 1632    | 1        | 0.99%   |

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
| Logitech                      | 7        | 31.82%  |
| Samsung Electronics           | 2        | 9.09%   |
| Microsoft                     | 2        | 9.09%   |
| Microdia                      | 2        | 9.09%   |
| ViewSonic                     | 1        | 4.55%   |
| Trust                         | 1        | 4.55%   |
| Sweex                         | 1        | 4.55%   |
| Sunplus IT                    | 1        | 4.55%   |
| Sunplus Innovation Technology | 1        | 4.55%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 4.55%   |
| Philips (or NXP)              | 1        | 4.55%   |
| MacroSilicon                  | 1        | 4.55%   |
| Jieli Technology              | 1        | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)           | 2        | 9.09%   |
| Logitech Webcam C270                              | 2        | 9.09%   |
| ViewSonic PC Camera                               | 1        | 4.55%   |
| Trust AUKEY PC-LM1A Webcam                        | 1        | 4.55%   |
| Sweex WC060 Series HD Webcam                      | 1        | 4.55%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 1        | 4.55%   |
| Sunplus Full HD webcam                            | 1        | 4.55%   |
| SHENZHEN AONI ELECTRONIC NexiGo N930AF FHD Webcam | 1        | 4.55%   |
| Philips (or NXP) Webcam SPC530NC                  | 1        | 4.55%   |
| Microsoft LifeCam VX-5000                         | 1        | 4.55%   |
| Microsoft LifeCam Cinema                          | 1        | 4.55%   |
| Microdia USB 2.0 Camera                           | 1        | 4.55%   |
| Microdia MSI Starcam Racer                        | 1        | 4.55%   |
| MacroSilicon USB Video                            | 1        | 4.55%   |
| Logitech QuickCam Communicate MP/S5500            | 1        | 4.55%   |
| Logitech Portable Webcam C905                     | 1        | 4.55%   |
| Logitech HD Webcam C910                           | 1        | 4.55%   |
| Logitech HD Webcam C510                           | 1        | 4.55%   |
| Logitech HD Pro Webcam C920                       | 1        | 4.55%   |
| Jieli USB PHY 2.0                                 | 1        | 4.55%   |

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
| 0     | 76       | 88.37%  |
| 1     | 9        | 10.47%  |
| 2     | 1        | 1.16%   |

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

