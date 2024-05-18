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

Total: 110

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B450M-A               | [1572659f68](https://linux-hardware.org/?probe=1572659f68) | Apr 24, 2024 |
| ASUSTek       | P5WDG2 WS Pro               | [c370aff195](https://linux-hardware.org/?probe=c370aff195) | Apr 13, 2024 |
| Unknown       | Unknown                     | [b3cf1a2d4e](https://linux-hardware.org/?probe=b3cf1a2d4e) | Apr 05, 2024 |
| ASUSTek       | P5G41-M                     | [cbab9e248d](https://linux-hardware.org/?probe=cbab9e248d) | Dec 20, 2023 |
| Intel         | Unknown                     | [3ae9554945](https://linux-hardware.org/?probe=3ae9554945) | Dec 05, 2023 |
| Dell          | 0PRR48 A01                  | [0942eb512e](https://linux-hardware.org/?probe=0942eb512e) | Nov 30, 2023 |
| Gigabyte      | X58A-UD3R                   | [99719fb0f6](https://linux-hardware.org/?probe=99719fb0f6) | Nov 27, 2023 |
| Gigabyte      | X58A-UD3R                   | [eec1358334](https://linux-hardware.org/?probe=eec1358334) | Nov 27, 2023 |
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
| Ubuntu Studio 20.04 | 42       | 44.68%  |
| Ubuntu Studio 22.04 | 29       | 30.85%  |
| Ubuntu Studio 20.10 | 9        | 9.57%   |
| Ubuntu Studio 23.10 | 3        | 3.19%   |
| Ubuntu Studio 22.10 | 3        | 3.19%   |
| Ubuntu Studio 21.10 | 3        | 3.19%   |
| Ubuntu Studio 23.04 | 2        | 2.13%   |
| Ubuntu Studio 21.04 | 2        | 2.13%   |
| Ubuntu Studio 16.04 | 1        | 1.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu Studio | 93       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 6.2.0-1009-lowlatency  | 3        | 3.13%   |
| 5.15.0-58-lowlatency   | 3        | 3.13%   |
| 5.11.0-44-lowlatency   | 3        | 3.13%   |
| 5.8.0-48-lowlatency    | 2        | 2.08%   |
| 5.8.0-44-lowlatency    | 2        | 2.08%   |
| 5.8.0-25-lowlatency    | 2        | 2.08%   |
| 5.4.0-58-lowlatency    | 2        | 2.08%   |
| 5.4.0-56-lowlatency    | 2        | 2.08%   |
| 5.4.0-42-lowlatency    | 2        | 2.08%   |
| 5.4.0-26-lowlatency    | 2        | 2.08%   |
| 5.19.0-1021-lowlatency | 2        | 2.08%   |
| 5.15.0-89-lowlatency   | 2        | 2.08%   |
| 5.15.0-79-lowlatency   | 2        | 2.08%   |
| 5.15.0-71-lowlatency   | 2        | 2.08%   |
| 5.15.0-56-lowlatency   | 2        | 2.08%   |
| 5.15.0-53-lowlatency   | 2        | 2.08%   |
| 5.15.0-52-lowlatency   | 2        | 2.08%   |
| 5.15.0-46-lowlatency   | 2        | 2.08%   |
| 5.13.0-28-lowlatency   | 2        | 2.08%   |
| 6.5.0-5-lowlatency     | 1        | 1.04%   |
| 6.5.0-28-lowlatency    | 1        | 1.04%   |
| 6.5.0-27-lowlatency    | 1        | 1.04%   |
| 6.5.0-13-lowlatency    | 1        | 1.04%   |
| 6.2.0-1014-lowlatency  | 1        | 1.04%   |
| 6.2.0-1007-lowlatency  | 1        | 1.04%   |
| 5.8.0-50-lowlatency    | 1        | 1.04%   |
| 5.8.0-45-lowlatency    | 1        | 1.04%   |
| 5.8.0-36-lowlatency    | 1        | 1.04%   |
| 5.8.0-34-lowlatency    | 1        | 1.04%   |
| 5.8.0-33-lowlatency    | 1        | 1.04%   |
| 5.8.0-29-lowlatency    | 1        | 1.04%   |
| 5.4.0-99-lowlatency    | 1        | 1.04%   |
| 5.4.0-72-lowlatency    | 1        | 1.04%   |
| 5.4.0-71-lowlatency    | 1        | 1.04%   |
| 5.4.0-70-lowlatency    | 1        | 1.04%   |
| 5.4.0-65-lowlatency    | 1        | 1.04%   |
| 5.4.0-65-generic       | 1        | 1.04%   |
| 5.4.0-64-lowlatency    | 1        | 1.04%   |
| 5.4.0-62-lowlatency    | 1        | 1.04%   |
| 5.4.0-60-lowlatency    | 1        | 1.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 34.04%  |
| 5.15.0  | 26       | 27.66%  |
| 5.8.0   | 12       | 12.77%  |
| 5.11.0  | 6        | 6.38%   |
| 6.2.0   | 5        | 5.32%   |
| 6.5.0   | 4        | 4.26%   |
| 5.19.0  | 4        | 4.26%   |
| 5.13.0  | 3        | 3.19%   |
| 5.15.6  | 1        | 1.06%   |
| 4.4.0   | 1        | 1.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 32       | 34.04%  |
| 5.15    | 27       | 28.72%  |
| 5.8     | 12       | 12.77%  |
| 5.11    | 6        | 6.38%   |
| 6.2     | 5        | 5.32%   |
| 6.5     | 4        | 4.26%   |
| 5.19    | 4        | 4.26%   |
| 5.13    | 3        | 3.19%   |
| 4.4     | 1        | 1.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 92       | 98.92%  |
| i686   | 1        | 1.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 44       | 46.81%  |
| XFCE            | 38       | 40.43%  |
| GNOME           | 5        | 5.32%   |
| MATE            | 2        | 2.13%   |
| LXQt            | 2        | 2.13%   |
| KDE             | 1        | 1.06%   |
| GNOME Flashback | 1        | 1.06%   |
| Cinnamon        | 1        | 1.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 87       | 92.55%  |
| Tty     | 4        | 4.26%   |
| Wayland | 3        | 3.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 41       | 44.09%  |
| TDM     | 25       | 26.88%  |
| LightDM | 20       | 21.51%  |
| GDM     | 6        | 6.45%   |
| GDM3    | 1        | 1.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 35       | 37.63%  |
| de_DE      | 10       | 10.75%  |
| fr_FR      | 9        | 9.68%   |
| it_IT      | 5        | 5.38%   |
| en_GB      | 5        | 5.38%   |
| pt_BR      | 4        | 4.3%    |
| ru_RU      | 3        | 3.23%   |
| es_ES      | 2        | 2.15%   |
| en_AU      | 2        | 2.15%   |
| C          | 2        | 2.15%   |
| sv_SE      | 1        | 1.08%   |
| nl_NL      | 1        | 1.08%   |
| nl_BE      | 1        | 1.08%   |
| nb_NO      | 1        | 1.08%   |
| fr_FR.UTF8 | 1        | 1.08%   |
| fr_CH      | 1        | 1.08%   |
| fr_BE      | 1        | 1.08%   |
| es_GT      | 1        | 1.08%   |
| es_AR      | 1        | 1.08%   |
| en_IL      | 1        | 1.08%   |
| en_DE      | 1        | 1.08%   |
| en_CA      | 1        | 1.08%   |
| de_AT      | 1        | 1.08%   |
| ca_ES      | 1        | 1.08%   |
| ca_AD      | 1        | 1.08%   |
| bg_BG      | 1        | 1.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 54       | 58.06%  |
| EFI  | 39       | 41.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 90       | 96.77%  |
| Xfs     | 1        | 1.08%   |
| Overlay | 1        | 1.08%   |
| Ext2    | 1        | 1.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 50       | 53.76%  |
| MBR  | 43       | 46.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 70       | 74.47%  |
| Yes       | 24       | 25.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 54.26%  |
| Yes       | 43       | 45.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 26       | 27.96%  |
| Gigabyte Technology                  | 15       | 16.13%  |
| Dell                                 | 13       | 13.98%  |
| Hewlett-Packard                      | 10       | 10.75%  |
| MSI                                  | 4        | 4.3%    |
| Fujitsu                              | 4        | 4.3%    |
| ASRock                               | 3        | 3.23%   |
| Intel                                | 2        | 2.15%   |
| Unknown                              | 2        | 2.15%   |
| System76                             | 1        | 1.08%   |
| Shenzhen Meigao Electronic Equipment | 1        | 1.08%   |
| Pegatron                             | 1        | 1.08%   |
| Packard Bell                         | 1        | 1.08%   |
| Medion                               | 1        | 1.08%   |
| Lenovo                               | 1        | 1.08%   |
| IBM                                  | 1        | 1.08%   |
| Foxconn                              | 1        | 1.08%   |
| ECS                                  | 1        | 1.08%   |
| DEPO Computers                       | 1        | 1.08%   |
| AZW                                  | 1        | 1.08%   |
| Apple                                | 1        | 1.08%   |
| Acidanthera                          | 1        | 1.08%   |
| Acer                                 | 1        | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 4        | 4.3%    |
| Unknown                                    | 3        | 3.23%   |
| Dell OptiPlex 790                          | 2        | 2.15%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 2.15%   |
| ASUS PRIME X570-PRO                        | 2        | 2.15%   |
| ASUS M4A785-M                              | 2        | 2.15%   |
| System76 Thelio                            | 1        | 1.08%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 1.08%   |
| Pegatron FL368AA-UUZ SR5612CH              | 1        | 1.08%   |
| Packard Bell IMEDIA S3220                  | 1        | 1.08%   |
| MSI MS-7E02                                | 1        | 1.08%   |
| MSI MS-7C95                                | 1        | 1.08%   |
| MSI MS-7A57                                | 1        | 1.08%   |
| MSI MS-7752                                | 1        | 1.08%   |
| Medion MD34207/C746                        | 1        | 1.08%   |
| Lenovo ThinkCentre M93p 10A8S45S00         | 1        | 1.08%   |
| Intel DQ965GF HD/FP Audio                  | 1        | 1.08%   |
| IBM 8188PPV                                | 1        | 1.08%   |
| HP Z620 Workstation                        | 1        | 1.08%   |
| HP Z2 Tower G4 Workstation                 | 1        | 1.08%   |
| HP ProDesk 600 G1 SFF                      | 1        | 1.08%   |
| HP Compaq Pro 6305 SFF                     | 1        | 1.08%   |
| HP Compaq Elite 8300 CMT                   | 1        | 1.08%   |
| HP Compaq dc7600 Small Form Factor         | 1        | 1.08%   |
| HP Compaq 8200 Elite SFF PC                | 1        | 1.08%   |
| HP Compaq 8100 Elite SFF PC                | 1        | 1.08%   |
| HP Compaq 6200 Pro MT PC                   | 1        | 1.08%   |
| HP Compaq 6005 Pro MT PC                   | 1        | 1.08%   |
| Gigabyte X79S-UP5                          | 1        | 1.08%   |
| Gigabyte X58A-UD3R                         | 1        | 1.08%   |
| Gigabyte X570 AORUS ELITE WIFI             | 1        | 1.08%   |
| Gigabyte H61M-D2-B3                        | 1        | 1.08%   |
| Gigabyte H270-HD3P                         | 1        | 1.08%   |
| Gigabyte H170-HD3-CF                       | 1        | 1.08%   |
| Gigabyte GA-MA770-DS3                      | 1        | 1.08%   |
| Gigabyte F2A78M-HD2                        | 1        | 1.08%   |
| Gigabyte B550M DS3H                        | 1        | 1.08%   |
| Gigabyte B450M S2H                         | 1        | 1.08%   |
| Gigabyte B450 I AORUS PRO WIFI             | 1        | 1.08%   |
| Gigabyte B150M-D2V DDR3                    | 1        | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 9        | 9.68%   |
| HP Compaq                                  | 7        | 7.53%   |
| ASUS ROG                                   | 4        | 4.3%    |
| ASUS All                                   | 4        | 4.3%    |
| Fujitsu ESPRIMO                            | 3        | 3.23%   |
| Dell Precision                             | 3        | 3.23%   |
| ASUS TUF                                   | 3        | 3.23%   |
| ASUS PRIME                                 | 3        | 3.23%   |
| Unknown                                    | 3        | 3.23%   |
| ASUS P8P67                                 | 2        | 2.15%   |
| ASUS M4A785-M                              | 2        | 2.15%   |
| System76 Thelio                            | 1        | 1.08%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 1.08%   |
| Pegatron FL368AA-UUZ                       | 1        | 1.08%   |
| Packard Bell IMEDIA                        | 1        | 1.08%   |
| MSI MS-7E02                                | 1        | 1.08%   |
| MSI MS-7C95                                | 1        | 1.08%   |
| MSI MS-7A57                                | 1        | 1.08%   |
| MSI MS-7752                                | 1        | 1.08%   |
| Medion MD34207                             | 1        | 1.08%   |
| Lenovo ThinkCentre                         | 1        | 1.08%   |
| Intel DQ965GF                              | 1        | 1.08%   |
| IBM 8188PPV                                | 1        | 1.08%   |
| HP Z620                                    | 1        | 1.08%   |
| HP Z2                                      | 1        | 1.08%   |
| HP ProDesk                                 | 1        | 1.08%   |
| Gigabyte X79S-UP5                          | 1        | 1.08%   |
| Gigabyte X58A-UD3R                         | 1        | 1.08%   |
| Gigabyte X570                              | 1        | 1.08%   |
| Gigabyte H61M-D2-B3                        | 1        | 1.08%   |
| Gigabyte H270-HD3P                         | 1        | 1.08%   |
| Gigabyte H170-HD3-CF                       | 1        | 1.08%   |
| Gigabyte GA-MA770-DS3                      | 1        | 1.08%   |
| Gigabyte F2A78M-HD2                        | 1        | 1.08%   |
| Gigabyte B550M                             | 1        | 1.08%   |
| Gigabyte B450M                             | 1        | 1.08%   |
| Gigabyte B450                              | 1        | 1.08%   |
| Gigabyte B150M-D2V                         | 1        | 1.08%   |
| Gigabyte A520M                             | 1        | 1.08%   |
| Gigabyte A320M-S2H                         | 1        | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 13       | 13.98%  |
| 2018 | 9        | 9.68%   |
| 2019 | 8        | 8.6%    |
| 2020 | 7        | 7.53%   |
| 2011 | 7        | 7.53%   |
| 2009 | 7        | 7.53%   |
| 2016 | 6        | 6.45%   |
| 2014 | 5        | 5.38%   |
| 2012 | 5        | 5.38%   |
| 2022 | 4        | 4.3%    |
| 2010 | 4        | 4.3%    |
| 2008 | 4        | 4.3%    |
| 2017 | 3        | 3.23%   |
| 2015 | 3        | 3.23%   |
| 2005 | 3        | 3.23%   |
| 2021 | 2        | 2.15%   |
| 2007 | 2        | 2.15%   |
| 2023 | 1        | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 93       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 92       | 98.92%  |
| Enabled  | 1        | 1.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 25       | 26.88%  |
| 8.01-16.0   | 18       | 19.35%  |
| 4.01-8.0    | 14       | 15.05%  |
| 32.01-64.0  | 12       | 12.9%   |
| 64.01-256.0 | 11       | 11.83%  |
| 3.01-4.0    | 8        | 8.6%    |
| 1.01-2.0    | 3        | 3.23%   |
| 24.01-32.0  | 1        | 1.08%   |
| 2.01-3.0    | 1        | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 29       | 30.85%  |
| 2.01-3.0   | 21       | 22.34%  |
| 4.01-8.0   | 20       | 21.28%  |
| 3.01-4.0   | 11       | 11.7%   |
| 8.01-16.0  | 9        | 9.57%   |
| 0.51-1.0   | 3        | 3.19%   |
| 24.01-32.0 | 1        | 1.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 36       | 38.71%  |
| 2      | 34       | 36.56%  |
| 3      | 10       | 10.75%  |
| 5      | 4        | 4.3%    |
| 7      | 3        | 3.23%   |
| 4      | 3        | 3.23%   |
| 16     | 1        | 1.08%   |
| 11     | 1        | 1.08%   |
| 10     | 1        | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 53       | 56.99%  |
| No        | 40       | 43.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 93       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 54.84%  |
| Yes       | 42       | 45.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 70.97%  |
| Yes       | 27       | 29.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 22       | 23.66%  |
| Germany                | 14       | 15.05%  |
| France                 | 11       | 11.83%  |
| Italy                  | 8        | 8.6%    |
| Brazil                 | 5        | 5.38%   |
| Spain                  | 4        | 4.3%    |
| Belgium                | 4        | 4.3%    |
| Austria                | 4        | 4.3%    |
| Russia                 | 3        | 3.23%   |
| UK                     | 2        | 2.15%   |
| Sweden                 | 2        | 2.15%   |
| Australia              | 2        | 2.15%   |
| Switzerland            | 1        | 1.08%   |
| Romania                | 1        | 1.08%   |
| Norway                 | 1        | 1.08%   |
| Netherlands            | 1        | 1.08%   |
| Mexico                 | 1        | 1.08%   |
| Luxembourg             | 1        | 1.08%   |
| Kenya                  | 1        | 1.08%   |
| Israel                 | 1        | 1.08%   |
| Guatemala              | 1        | 1.08%   |
| Bulgaria               | 1        | 1.08%   |
| Bosnia and Herzegovina | 1        | 1.08%   |
| Argentina              | 1        | 1.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Paris                   | 3        | 3.19%   |
| Houston                 | 3        | 3.19%   |
| Vienna                  | 2        | 2.13%   |
| Stockholm               | 2        | 2.13%   |
| Madrid                  | 2        | 2.13%   |
| Zanesville              | 1        | 1.06%   |
| Wildenfels              | 1        | 1.06%   |
| West Mifflin            | 1        | 1.06%   |
| Villetaneuse            | 1        | 1.06%   |
| Villefontaine           | 1        | 1.06%   |
| Verviers                | 1        | 1.06%   |
| Turin                   | 1        | 1.06%   |
| Tilburg                 | 1        | 1.06%   |
| Stuttgart               | 1        | 1.06%   |
| Sherman Oaks            | 1        | 1.06%   |
| Sarajevo                | 1        | 1.06%   |
| Sao Paulo               | 1        | 1.06%   |
| Santa Barbara d'Oeste   | 1        | 1.06%   |
| San Secondo di Pinerolo | 1        | 1.06%   |
| Saint-Ouen-l'Aumone     | 1        | 1.06%   |
| Rome                    | 1        | 1.06%   |
| Rio Grande da Serra     | 1        | 1.06%   |
| Rennes                  | 1        | 1.06%   |
| Potsdam                 | 1        | 1.06%   |
| Pisa                    | 1        | 1.06%   |
| Philadelphia            | 1        | 1.06%   |
| Perth                   | 1        | 1.06%   |
| Palermo                 | 1        | 1.06%   |
| Oslo                    | 1        | 1.06%   |
| Olympia                 | 1        | 1.06%   |
| Oldenburg               | 1        | 1.06%   |
| Novosibirsk             | 1        | 1.06%   |
| Naumburg                | 1        | 1.06%   |
| Namur                   | 1        | 1.06%   |
| Nairobi                 | 1        | 1.06%   |
| Münster                | 1        | 1.06%   |
| Munich                  | 1        | 1.06%   |
| Moscow                  | 1        | 1.06%   |
| Morehead City           | 1        | 1.06%   |
| Modesto                 | 1        | 1.06%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 32       | 41     | 18.08%  |
| Seagate                     | 29       | 53     | 16.38%  |
| Samsung Electronics         | 27       | 39     | 15.25%  |
| SanDisk                     | 12       | 13     | 6.78%   |
| Toshiba                     | 10       | 11     | 5.65%   |
| Hitachi                     | 8        | 9      | 4.52%   |
| Kingston                    | 7        | 8      | 3.95%   |
| Crucial                     | 6        | 6      | 3.39%   |
| HGST                        | 4        | 5      | 2.26%   |
| PNY                         | 3        | 4      | 1.69%   |
| Phison                      | 3        | 3      | 1.69%   |
| Intenso                     | 3        | 3      | 1.69%   |
| Team                        | 2        | 2      | 1.13%   |
| SPCC                        | 2        | 2      | 1.13%   |
| JMicron Technology          | 2        | 2      | 1.13%   |
| Intel                       | 2        | 2      | 1.13%   |
| Corsair                     | 2        | 3      | 1.13%   |
| ASMT                        | 2        | 2      | 1.13%   |
| A-DATA Technology           | 2        | 2      | 1.13%   |
| USB 3.0                     | 1        | 2      | 0.56%   |
| TO Exter                    | 1        | 1      | 0.56%   |
| Timetec                     | 1        | 1      | 0.56%   |
| SK hynix                    | 1        | 1      | 0.56%   |
| Silicon Motion              | 1        | 1      | 0.56%   |
| Realtek Semiconductor       | 1        | 1      | 0.56%   |
| Phison Electronics          | 1        | 1      | 0.56%   |
| Patriot                     | 1        | 1      | 0.56%   |
| OCZ                         | 1        | 1      | 0.56%   |
| NGFF                        | 1        | 1      | 0.56%   |
| Micron Technology           | 1        | 1      | 0.56%   |
| Maxtor                      | 1        | 1      | 0.56%   |
| Leven                       | 1        | 1      | 0.56%   |
| Kingston Technology Company | 1        | 1      | 0.56%   |
| Integral                    | 1        | 1      | 0.56%   |
| Fujitsu                     | 1        | 1      | 0.56%   |
| China                       | 1        | 1      | 0.56%   |
| BHT                         | 1        | 1      | 0.56%   |
| Apple                       | 1        | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 4        | 1.95%   |
| Seagate ST2000DM001-1ER164 2TB  | 4        | 1.95%   |
| Seagate ST2000DM008-2FR102 2TB  | 3        | 1.46%   |
| WDC WDS200T2B0A-00SM50 2TB SSD  | 2        | 0.98%   |
| Toshiba HDWD130 3TB             | 2        | 0.98%   |
| Toshiba DT01ACA100 1TB          | 2        | 0.98%   |
| Toshiba DT01ACA050 500GB        | 2        | 0.98%   |
| Team T253X6001T 1TB SSD         | 2        | 0.98%   |
| SPCC Solid State Disk 256GB     | 2        | 0.98%   |
| Seagate ST5000LM000-2AN170 5TB  | 2        | 0.98%   |
| Seagate Expansion+ Desk 4TB     | 2        | 0.98%   |
| Seagate Expansion 2TB           | 2        | 0.98%   |
| SanDisk SDSSDA240G 240GB        | 2        | 0.98%   |
| Samsung SSD 970 EVO Plus 500GB  | 2        | 0.98%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 0.98%   |
| Samsung SSD 870 EVO 1TB         | 2        | 0.98%   |
| Samsung SSD 860 EVO 1TB         | 2        | 0.98%   |
| Samsung SSD 850 EVO 500GB       | 2        | 0.98%   |
| Samsung HD753LJ 752GB           | 2        | 0.98%   |
| Kingston SA400S37480G 480GB SSD | 2        | 0.98%   |
| Kingston SA400S37120G 120GB SSD | 2        | 0.98%   |
| Crucial CT500MX500SSD1 500GB    | 2        | 0.98%   |
| Crucial CT1000MX500SSD1 1TB     | 2        | 0.98%   |
| WDC WDS512G1X0C-00ENX0 512GB    | 1        | 0.49%   |
| WDC WDBNCE5000PNC 500GB SSD     | 1        | 0.49%   |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 0.49%   |
| WDC WD5000BPKT-60PK4T0 500GB    | 1        | 0.49%   |
| WDC WD5000AVDS-63U7B1 500GB     | 1        | 0.49%   |
| WDC WD5000AAKS-75V0A0 500GB     | 1        | 0.49%   |
| WDC WD5000AAKS-00TMA0 500GB     | 1        | 0.49%   |
| WDC WD40EZRZ-00GXCB0 4TB        | 1        | 0.49%   |
| WDC WD40EFRX-68N32N0 4TB        | 1        | 0.49%   |
| WDC WD40EFAX-68JH4N1 4TB        | 1        | 0.49%   |
| WDC WD40EFAX-68JH4N0 4TB        | 1        | 0.49%   |
| WDC WD3200BUCT-63TWBY0 320GB    | 1        | 0.49%   |
| WDC WD3200BPVT-75JJ5T0 320GB    | 1        | 0.49%   |
| WDC WD3200BEVT-22ZCT0 320GB     | 1        | 0.49%   |
| WDC WD3200AAKS-00VYA0 320GB     | 1        | 0.49%   |
| WDC WD30EZRZ-00Z5HB0 3TB        | 1        | 0.49%   |
| WDC WD30EZRX-00SPEB0 3TB        | 1        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 52     | 33.33%  |
| WDC                 | 28       | 37     | 32.18%  |
| Toshiba             | 10       | 11     | 11.49%  |
| Hitachi             | 8        | 9      | 9.2%    |
| HGST                | 4        | 5      | 4.6%    |
| Samsung Electronics | 3        | 3      | 3.45%   |
| USB 3.0             | 1        | 2      | 1.15%   |
| TO Exter            | 1        | 1      | 1.15%   |
| Maxtor              | 1        | 1      | 1.15%   |
| JMicron Technology  | 1        | 1      | 1.15%   |
| Fujitsu             | 1        | 1      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 15       | 20     | 23.44%  |
| SanDisk             | 10       | 11     | 15.63%  |
| Kingston            | 7        | 8      | 10.94%  |
| Crucial             | 6        | 6      | 9.38%   |
| WDC                 | 3        | 3      | 4.69%   |
| PNY                 | 3        | 4      | 4.69%   |
| Intenso             | 3        | 3      | 4.69%   |
| Team                | 2        | 2      | 3.13%   |
| SPCC                | 2        | 2      | 3.13%   |
| ASMT                | 2        | 2      | 3.13%   |
| A-DATA Technology   | 2        | 2      | 3.13%   |
| Patriot             | 1        | 1      | 1.56%   |
| OCZ                 | 1        | 1      | 1.56%   |
| NGFF                | 1        | 1      | 1.56%   |
| Micron Technology   | 1        | 1      | 1.56%   |
| Leven               | 1        | 1      | 1.56%   |
| Integral            | 1        | 1      | 1.56%   |
| Corsair             | 1        | 1      | 1.56%   |
| China               | 1        | 1      | 1.56%   |
| BHT                 | 1        | 1      | 1.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 62       | 123    | 44.93%  |
| SSD     | 51       | 72     | 36.96%  |
| NVMe    | 23       | 33     | 16.67%  |
| Unknown | 2        | 2      | 1.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 85       | 181    | 72.03%  |
| NVMe | 23       | 33     | 19.49%  |
| SAS  | 10       | 16     | 8.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 59       | 89     | 44.36%  |
| 0.51-1.0   | 39       | 49     | 29.32%  |
| 1.01-2.0   | 17       | 20     | 12.78%  |
| 3.01-4.0   | 9        | 11     | 6.77%   |
| 4.01-10.0  | 6        | 22     | 4.51%   |
| 2.01-3.0   | 3        | 4      | 2.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 24       | 25.53%  |
| 501-1000       | 20       | 21.28%  |
| 1001-2000      | 18       | 19.15%  |
| More than 3000 | 16       | 17.02%  |
| 251-500        | 8        | 8.51%   |
| 51-100         | 4        | 4.26%   |
| 21-50          | 2        | 2.13%   |
| 2001-3000      | 1        | 1.06%   |
| 1-20           | 1        | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 22       | 23.16%  |
| 21-50          | 15       | 15.79%  |
| 101-250        | 12       | 12.63%  |
| 251-500        | 11       | 11.58%  |
| More than 3000 | 10       | 10.53%  |
| 1001-2000      | 7        | 7.37%   |
| 501-1000       | 7        | 7.37%   |
| 51-100         | 7        | 7.37%   |
| 2001-3000      | 4        | 4.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 3        | 3      | 12.5%   |
| Samsung Electronics HD753LJ 752GB     | 2        | 2      | 8.33%   |
| WDC WD5000AVDS-63U7B1 500GB           | 1        | 1      | 4.17%   |
| WDC WD5000AAKS-00TMA0 500GB           | 1        | 1      | 4.17%   |
| WDC WD1600AAJS-08L7A0 160GB           | 1        | 1      | 4.17%   |
| WDC WD10EZEX-22BN5A0 1TB              | 1        | 1      | 4.17%   |
| WDC WD10EAVS-32D7B1 1TB               | 1        | 1      | 4.17%   |
| WDC WD10EADS-00M2B0 1TB               | 1        | 1      | 4.17%   |
| Toshiba MQ01ABF050 500GB              | 1        | 1      | 4.17%   |
| Toshiba HDWE140 4TB                   | 1        | 1      | 4.17%   |
| Seagate ST8000DM004-2CX1 8TB          | 1        | 6      | 4.17%   |
| Seagate ST3320820AS 320GB             | 1        | 1      | 4.17%   |
| Seagate ST3200822AS 200GB             | 1        | 1      | 4.17%   |
| Seagate ST1000VM002-9ZL162 1TB        | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 960 PRO 512GB | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1        | 2      | 4.17%   |
| Hitachi HDS721010CLA332 1TB           | 1        | 1      | 4.17%   |
| Hitachi HDS5C1010CLA382 1TB           | 1        | 1      | 4.17%   |
| HGST HTS721010A9 1TB                  | 1        | 1      | 4.17%   |
| A-DATA Technology SU650 240GB SSD     | 1        | 1      | 4.17%   |
| A-DATA Technology SP550 240GB SSD     | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 12     | 30.43%  |
| WDC                 | 5        | 6      | 21.74%  |
| Samsung Electronics | 4        | 5      | 17.39%  |
| Toshiba             | 2        | 2      | 8.7%    |
| Hitachi             | 2        | 2      | 8.7%    |
| A-DATA Technology   | 2        | 2      | 8.7%    |
| HGST                | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 12     | 36.84%  |
| WDC                 | 5        | 6      | 26.32%  |
| Toshiba             | 2        | 2      | 10.53%  |
| Samsung Electronics | 2        | 2      | 10.53%  |
| Hitachi             | 2        | 2      | 10.53%  |
| HGST                | 1        | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 25     | 80.95%  |
| SSD  | 3        | 4      | 14.29%  |
| NVMe | 1        | 1      | 4.76%   |

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
| Works    | 87       | 180    | 71.9%   |
| Malfunc  | 21       | 30     | 17.36%  |
| Detected | 11       | 18     | 9.09%   |
| Failed   | 2        | 2      | 1.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 62       | 46.27%  |
| AMD                         | 27       | 20.15%  |
| Samsung Electronics         | 11       | 8.21%   |
| Marvell Technology Group    | 6        | 4.48%   |
| Phison Electronics          | 5        | 3.73%   |
| ASMedia Technology          | 5        | 3.73%   |
| SanDisk                     | 3        | 2.24%   |
| Nvidia                      | 3        | 2.24%   |
| Silicon Motion              | 2        | 1.49%   |
| JMicron Technology          | 2        | 1.49%   |
| VIA Technologies            | 1        | 0.75%   |
| SK hynix                    | 1        | 0.75%   |
| Silicon Image               | 1        | 0.75%   |
| Realtek Semiconductor       | 1        | 0.75%   |
| LSI Logic / Symbios Logic   | 1        | 0.75%   |
| Kingston Technology Company | 1        | 0.75%   |
| Apple                       | 1        | 0.75%   |
| Adaptec                     | 1        | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 15       | 8.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 6.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 4.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 4.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.96%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 5        | 2.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 2.96%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 2.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 2.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.37%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.78%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 2        | 1.18%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 2        | 1.18%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.18%   |
| Phison E12 NVMe Controller                                                              | 2        | 1.18%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2        | 1.18%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 2        | 1.18%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 1.18%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.18%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.18%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.18%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.59%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1        | 0.59%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.59%   |
| SanDisk WD Black NVMe SSD                                                               | 1        | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.59%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 1        | 0.59%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 1        | 0.59%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.59%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.59%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 75       | 57.25%  |
| IDE  | 25       | 19.08%  |
| NVMe | 23       | 17.56%  |
| RAID | 4        | 3.05%   |
| SAS  | 3        | 2.29%   |
| SCSI | 1        | 0.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 63       | 67.74%  |
| AMD    | 30       | 32.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz        | 3        | 3.23%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3        | 3.23%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2        | 2.15%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2        | 2.15%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2        | 2.15%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2        | 2.15%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2        | 2.15%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 2        | 2.15%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 2        | 2.15%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 2        | 2.15%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2        | 2.15%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2        | 2.15%   |
| AMD Phenom II X4 945 Processor          | 2        | 2.15%   |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1        | 1.08%   |
| Intel Xeon CPU E5420 @ 2.50GHz          | 1        | 1.08%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz     | 1        | 1.08%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1        | 1.08%   |
| Intel Pentium D CPU 3.40GHz             | 1        | 1.08%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1        | 1.08%   |
| Intel Pentium 4 CPU 3.20GHz             | 1        | 1.08%   |
| Intel Pentium 4 CPU 2.80GHz             | 1        | 1.08%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 1        | 1.08%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1        | 1.08%   |
| Intel Core i9-10900 CPU @ 2.80GHz       | 1        | 1.08%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 1        | 1.08%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 1        | 1.08%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1        | 1.08%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1        | 1.08%   |
| Intel Core i7-3930K CPU @ 3.20GHz       | 1        | 1.08%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1        | 1.08%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1        | 1.08%   |
| Intel Core i7 CPU 960 @ 3.20GHz         | 1        | 1.08%   |
| Intel Core i7 CPU 930 @ 2.80GHz         | 1        | 1.08%   |
| Intel Core i5-9400T CPU @ 1.80GHz       | 1        | 1.08%   |
| Intel Core i5-8600K CPU @ 3.60GHz       | 1        | 1.08%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 1        | 1.08%   |
| Intel Core i5-7600K CPU @ 3.80GHz       | 1        | 1.08%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 1        | 1.08%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 1        | 1.08%   |
| Intel Core i5-3330 CPU @ 3.00GHz        | 1        | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 23       | 24.73%  |
| Intel Core i7          | 13       | 13.98%  |
| Intel Core i3          | 8        | 8.6%    |
| AMD Ryzen 9            | 6        | 6.45%   |
| AMD Ryzen 5            | 5        | 5.38%   |
| Intel Xeon             | 4        | 4.3%    |
| AMD Phenom II X4       | 4        | 4.3%    |
| Other                  | 3        | 3.23%   |
| Intel Core i9          | 3        | 3.23%   |
| AMD Ryzen 7            | 3        | 3.23%   |
| Intel Pentium 4        | 2        | 2.15%   |
| Intel Core 2 Quad      | 2        | 2.15%   |
| AMD FX                 | 2        | 2.15%   |
| AMD Athlon II X2       | 2        | 2.15%   |
| Intel Pentium D        | 1        | 1.08%   |
| Intel Pentium          | 1        | 1.08%   |
| Intel Core 2 Duo       | 1        | 1.08%   |
| Intel Core 2           | 1        | 1.08%   |
| Intel Celeron          | 1        | 1.08%   |
| AMD Ryzen Threadripper | 1        | 1.08%   |
| AMD Ryzen 3            | 1        | 1.08%   |
| AMD E                  | 1        | 1.08%   |
| AMD Athlon X4          | 1        | 1.08%   |
| AMD Athlon Dual Core   | 1        | 1.08%   |
| AMD Athlon 64 X2       | 1        | 1.08%   |
| AMD A4                 | 1        | 1.08%   |
| AMD A10                | 1        | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 41       | 44.09%  |
| 2      | 20       | 21.51%  |
| 6      | 10       | 10.75%  |
| 8      | 9        | 9.68%   |
| 10     | 4        | 4.3%    |
| 16     | 3        | 3.23%   |
| 1      | 3        | 3.23%   |
| 12     | 2        | 2.15%   |
| 32     | 1        | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 92       | 98.92%  |
| 2      | 1        | 1.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 52       | 55.91%  |
| 1      | 41       | 44.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 92       | 98.92%  |
| 32-bit         | 1        | 1.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 15.05%  |
| 0x306c3    | 12       | 12.9%   |
| 0x206a7    | 7        | 7.53%   |
| 0x306a9    | 6        | 6.45%   |
| 0x506e3    | 4        | 4.3%    |
| 0x08701021 | 4        | 4.3%    |
| 0x906ea    | 3        | 3.23%   |
| 0x0a50000d | 3        | 3.23%   |
| 0x010000c8 | 3        | 3.23%   |
| 0xf41      | 2        | 2.15%   |
| 0xa0655    | 2        | 2.15%   |
| 0x906ed    | 2        | 2.15%   |
| 0x206d7    | 2        | 2.15%   |
| 0x106a5    | 2        | 2.15%   |
| 0x10676    | 2        | 2.15%   |
| 0x010000b6 | 2        | 2.15%   |
| 0xf65      | 1        | 1.08%   |
| 0x906ec    | 1        | 1.08%   |
| 0x906a4    | 1        | 1.08%   |
| 0x90675    | 1        | 1.08%   |
| 0x6f6      | 1        | 1.08%   |
| 0x506ca    | 1        | 1.08%   |
| 0x50654    | 1        | 1.08%   |
| 0x306f2    | 1        | 1.08%   |
| 0x20655    | 1        | 1.08%   |
| 0x20652    | 1        | 1.08%   |
| 0x0a50000c | 1        | 1.08%   |
| 0x0a20120a | 1        | 1.08%   |
| 0x0a201009 | 1        | 1.08%   |
| 0x08701013 | 1        | 1.08%   |
| 0x08301039 | 1        | 1.08%   |
| 0x08108109 | 1        | 1.08%   |
| 0x08101016 | 1        | 1.08%   |
| 0x08001138 | 1        | 1.08%   |
| 0x06003106 | 1        | 1.08%   |
| 0x06001119 | 1        | 1.08%   |
| 0x06000852 | 1        | 1.08%   |
| 0x0600081f | 1        | 1.08%   |
| 0x010000c7 | 1        | 1.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 13       | 13.98%  |
| SandyBridge      | 9        | 9.68%   |
| Zen 2            | 8        | 8.6%    |
| KabyLake         | 8        | 8.6%    |
| Skylake          | 7        | 7.53%   |
| IvyBridge        | 7        | 7.53%   |
| Zen 3            | 6        | 6.45%   |
| K10              | 6        | 6.45%   |
| Westmere         | 3        | 3.23%   |
| Piledriver       | 3        | 3.23%   |
| Penryn           | 3        | 3.23%   |
| NetBurst         | 3        | 3.23%   |
| Alderlake Hybrid | 3        | 3.23%   |
| Zen              | 2        | 2.15%   |
| Nehalem          | 2        | 2.15%   |
| K8 Hammer        | 2        | 2.15%   |
| Core             | 2        | 2.15%   |
| CometLake        | 2        | 2.15%   |
| Zen+             | 1        | 1.08%   |
| Steamroller      | 1        | 1.08%   |
| Goldmont         | 1        | 1.08%   |
| Excavator        | 1        | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 46       | 45.54%  |
| Intel  | 32       | 31.68%  |
| AMD    | 23       | 22.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 6.8%    |
| Intel HD Graphics 530                                                       | 4        | 3.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 3.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 3.88%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 2.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.91%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 2.91%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.94%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.94%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.94%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.94%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 1.94%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 1.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1.94%   |
| Intel HD Graphics 630                                                       | 2        | 1.94%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.94%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.94%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 1.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 1.94%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.97%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.97%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1        | 0.97%   |
| Nvidia GT216 [GeForce 315]                                                  | 1        | 0.97%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1        | 0.97%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.97%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.97%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.97%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.97%   |
| Nvidia GK208 [GeForce GT 720]                                               | 1        | 0.97%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 0.97%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 0.97%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.97%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 0.97%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.97%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.97%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.97%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 0.97%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 0.97%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 41       | 44.09%  |
| 1 x Intel      | 25       | 26.88%  |
| 1 x AMD        | 21       | 22.58%  |
| Intel + Nvidia | 3        | 3.23%   |
| 2 x Nvidia     | 1        | 1.08%   |
| 2 x AMD        | 1        | 1.08%   |
| AMD + Nvidia   | 1        | 1.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 66       | 70.21%  |
| Proprietary | 28       | 29.79%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 30.85%  |
| 1.01-2.0   | 15       | 15.96%  |
| 0.01-0.5   | 14       | 14.89%  |
| 0.51-1.0   | 12       | 12.77%  |
| 7.01-8.0   | 8        | 8.51%   |
| 3.01-4.0   | 6        | 6.38%   |
| 8.01-16.0  | 5        | 5.32%   |
| 5.01-6.0   | 3        | 3.19%   |
| 2.01-3.0   | 1        | 1.06%   |
| 16.01-24.0 | 1        | 1.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 17       | 16.5%   |
| Goldstar             | 13       | 12.62%  |
| Philips              | 9        | 8.74%   |
| Dell                 | 9        | 8.74%   |
| Acer                 | 9        | 8.74%   |
| Hewlett-Packard      | 8        | 7.77%   |
| Ancor Communications | 6        | 5.83%   |
| AOC                  | 3        | 2.91%   |
| ONN                  | 2        | 1.94%   |
| Fujitsu Siemens      | 2        | 1.94%   |
| Eizo                 | 2        | 1.94%   |
| BenQ                 | 2        | 1.94%   |
| ASUSTek Computer     | 2        | 1.94%   |
| ViewSonic            | 1        | 0.97%   |
| VIE                  | 1        | 0.97%   |
| Unknown              | 1        | 0.97%   |
| TVT                  | 1        | 0.97%   |
| TCH                  | 1        | 0.97%   |
| Targa Visionary      | 1        | 0.97%   |
| Sony                 | 1        | 0.97%   |
| Seiki                | 1        | 0.97%   |
| Onkyo                | 1        | 0.97%   |
| NEC Computers        | 1        | 0.97%   |
| MSI                  | 1        | 0.97%   |
| Medion               | 1        | 0.97%   |
| KTC                  | 1        | 0.97%   |
| Iiyama               | 1        | 0.97%   |
| Hitachi              | 1        | 0.97%   |
| Hannspree            | 1        | 0.97%   |
| DENON                | 1        | 0.97%   |
| Apple                | 1        | 0.97%   |
| Unknown              | 1        | 0.97%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 2        | 1.77%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2        | 1.77%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1        | 0.88%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 0.88%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                 | 1        | 0.88%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                        | 1        | 0.88%   |
| TCH HDMI TCH5600 1920x1080 344x194mm 15.5-inch                        | 1        | 0.88%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch   | 1        | 0.88%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                    | 1        | 0.88%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                   | 1        | 0.88%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1        | 0.88%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM0484 1920x1080 520x320mm 24.0-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch   | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch  | 1        | 0.88%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch  | 1        | 0.88%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch   | 1        | 0.88%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch   | 1        | 0.88%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1        | 0.88%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch     | 1        | 0.88%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch  | 1        | 0.88%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch  | 1        | 0.88%   |
| Samsung Electronics LCD Monitor S34J55x 3440x1440                     | 1        | 0.88%   |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch     | 1        | 0.88%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch             | 1        | 0.88%   |
| Philips PHL 278E8Q PHLC161 1920x1080 598x336mm 27.0-inch              | 1        | 0.88%   |
| Philips 247E4 PHLC0C0 1920x1080 521x293mm 23.5-inch                   | 1        | 0.88%   |
| Philips 227E4LH PHLC0AC 1920x1080 477x268mm 21.5-inch                 | 1        | 0.88%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1        | 0.88%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1        | 0.88%   |
| Philips 201E PHLC033 1600x900 443x249mm 20.0-inch                     | 1        | 0.88%   |
| Philips 190V PHL0847 1280x1024 376x301mm 19.0-inch                    | 1        | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 47       | 47%     |
| 3840x2160 (4K)     | 11       | 11%     |
| 1280x1024 (SXGA)   | 10       | 10%     |
| 1680x1050 (WSXGA+) | 8        | 8%      |
| 1920x1200 (WUXGA)  | 4        | 4%      |
| 2560x1440 (QHD)    | 3        | 3%      |
| 1440x900 (WXGA+)   | 3        | 3%      |
| 1366x768 (WXGA)    | 3        | 3%      |
| 1600x900 (HD+)     | 2        | 2%      |
| 1360x768           | 2        | 2%      |
| Unknown            | 2        | 2%      |
| 5760x2160          | 1        | 1%      |
| 3440x1440          | 1        | 1%      |
| 3280x1080          | 1        | 1%      |
| 1600x1200          | 1        | 1%      |
| 1400x1050          | 1        | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 16       | 15.53%  |
| 21      | 15       | 14.56%  |
| 27      | 13       | 12.62%  |
| 24      | 13       | 12.62%  |
| 22      | 8        | 7.77%   |
| 19      | 7        | 6.8%    |
| 31      | 6        | 5.83%   |
| 17      | 6        | 5.83%   |
| 18      | 4        | 3.88%   |
| 20      | 3        | 2.91%   |
| Unknown | 3        | 2.91%   |
| 84      | 2        | 1.94%   |
| 15      | 2        | 1.94%   |
| 65      | 1        | 0.97%   |
| 52      | 1        | 0.97%   |
| 50      | 1        | 0.97%   |
| 43      | 1        | 0.97%   |
| 32      | 1        | 0.97%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 38       | 38.38%  |
| 401-500     | 31       | 31.31%  |
| 601-700     | 8        | 8.08%   |
| 301-350     | 8        | 8.08%   |
| 351-400     | 4        | 4.04%   |
| 1001-1500   | 3        | 3.03%   |
| Unknown     | 3        | 3.03%   |
| 1501-2000   | 2        | 2.02%   |
| 701-800     | 1        | 1.01%   |
| 901-1000    | 1        | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 63       | 66.32%  |
| 16/10   | 17       | 17.89%  |
| 5/4     | 9        | 9.47%   |
| Unknown | 3        | 3.16%   |
| 4/3     | 2        | 2.11%   |
| 3/2     | 1        | 1.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 42       | 42.42%  |
| 301-350        | 13       | 13.13%  |
| 151-200        | 11       | 11.11%  |
| 141-150        | 10       | 10.1%   |
| 351-500        | 7        | 7.07%   |
| More than 1000 | 5        | 5.05%   |
| 251-300        | 5        | 5.05%   |
| Unknown        | 3        | 3.03%   |
| 111-120        | 1        | 1.01%   |
| 101-110        | 1        | 1.01%   |
| 501-1000       | 1        | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 66       | 70.21%  |
| 101-120 | 19       | 20.21%  |
| 121-160 | 4        | 4.26%   |
| Unknown | 3        | 3.19%   |
| 1-50    | 1        | 1.06%   |
| 161-240 | 1        | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 67       | 72.04%  |
| 2     | 26       | 27.96%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 52       | 37.96%  |
| Intel                           | 44       | 32.12%  |
| Qualcomm Atheros                | 12       | 8.76%   |
| Broadcom                        | 5        | 3.65%   |
| TP-Link                         | 3        | 2.19%   |
| Nvidia                          | 3        | 2.19%   |
| MediaTek                        | 3        | 2.19%   |
| Ralink Technology               | 2        | 1.46%   |
| Broadcom Limited                | 2        | 1.46%   |
| Aquantia                        | 2        | 1.46%   |
| ZyDAS                           | 1        | 0.73%   |
| Wacom                           | 1        | 0.73%   |
| Qualcomm Atheros Communications | 1        | 0.73%   |
| NetGear                         | 1        | 0.73%   |
| Microsoft                       | 1        | 0.73%   |
| Marvell Technology Group        | 1        | 0.73%   |
| InterBiometrics                 | 1        | 0.73%   |
| Input Club                      | 1        | 0.73%   |
| ASIX Electronics                | 1        | 0.73%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 44       | 28.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10       | 6.54%   |
| Intel I211 Gigabit Network Connection                                          | 6        | 3.92%   |
| Intel Ethernet Connection I217-LM                                              | 5        | 3.27%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 4        | 2.61%   |
| Intel Ethernet Connection (2) I219-V                                           | 4        | 2.61%   |
| Intel Ethernet Controller I225-V                                               | 3        | 1.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 2        | 1.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 1.31%   |
| Realtek 802.11ac NIC                                                           | 2        | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2        | 1.31%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2        | 1.31%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 2        | 1.31%   |
| Nvidia MCP77 Ethernet                                                          | 2        | 1.31%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 2        | 1.31%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 2        | 1.31%   |
| Intel Ethernet Connection I217-V                                               | 2        | 1.31%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 2        | 1.31%   |
| Intel 82574L Gigabit Network Connection                                        | 2        | 1.31%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 1.31%   |
| ZyDAS ZD1211B 802.11g                                                          | 1        | 0.65%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                       | 1        | 0.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 1        | 0.65%   |
| TP-Link 802.11ac WLAN Adapter                                                  | 1        | 0.65%   |
| TP-Link 802.11ac NIC                                                           | 1        | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.65%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                | 1        | 0.65%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                        | 1        | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.65%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1        | 0.65%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.65%   |
| Realtek 802.11ax WLAN Adapter                                                  | 1        | 0.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1        | 0.65%   |
| Ralink MT7601U Wireless Adapter                                                | 1        | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1        | 0.65%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1        | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 24.44%  |
| Realtek Semiconductor           | 10       | 22.22%  |
| Qualcomm Atheros                | 9        | 20%     |
| TP-Link                         | 3        | 6.67%   |
| MediaTek                        | 3        | 6.67%   |
| Ralink Technology               | 2        | 4.44%   |
| Broadcom                        | 2        | 4.44%   |
| ZyDAS                           | 1        | 2.22%   |
| Wacom                           | 1        | 2.22%   |
| Qualcomm Atheros Communications | 1        | 2.22%   |
| NetGear                         | 1        | 2.22%   |
| Microsoft                       | 1        | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 4        | 8.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2        | 4.44%   |
| Realtek 802.11ac NIC                                                          | 2        | 4.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 4.44%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2        | 4.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 4.44%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 2        | 4.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 4.44%   |
| ZyDAS ZD1211B 802.11g                                                         | 1        | 2.22%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1        | 2.22%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 2.22%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 2.22%   |
| TP-Link 802.11ac NIC                                                          | 1        | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.22%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 2.22%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1        | 2.22%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 2.22%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 2.22%   |
| Realtek 802.11ax WLAN Adapter                                                 | 1        | 2.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 2.22%   |
| Ralink MT7601U Wireless Adapter                                               | 1        | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 2.22%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 2.22%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 2.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 2.22%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 2.22%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 2.22%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                   | 1        | 2.22%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 2.22%   |
| MediaTek 802.11 n WLAN                                                        | 1        | 2.22%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 2.22%   |
| Intel Wireless 3165                                                           | 1        | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 2.22%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                            | 1        | 2.22%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                  | 1        | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 48       | 46.6%   |
| Intel                    | 40       | 38.83%  |
| Qualcomm Atheros         | 3        | 2.91%   |
| Nvidia                   | 3        | 2.91%   |
| Broadcom                 | 3        | 2.91%   |
| Broadcom Limited         | 2        | 1.94%   |
| Aquantia                 | 2        | 1.94%   |
| Marvell Technology Group | 1        | 0.97%   |
| ASIX Electronics         | 1        | 0.97%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 44       | 41.51%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10       | 9.43%   |
| Intel I211 Gigabit Network Connection                                          | 6        | 5.66%   |
| Intel Ethernet Connection I217-LM                                              | 5        | 4.72%   |
| Intel Ethernet Connection (2) I219-V                                           | 4        | 3.77%   |
| Intel Ethernet Controller I225-V                                               | 3        | 2.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 1.89%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2        | 1.89%   |
| Nvidia MCP77 Ethernet                                                          | 2        | 1.89%   |
| Intel Ethernet Connection I217-V                                               | 2        | 1.89%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 1.89%   |
| Intel 82574L Gigabit Network Connection                                        | 2        | 1.89%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 1.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.94%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.94%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1        | 0.94%   |
| Nvidia MCP61 Ethernet                                                          | 1        | 0.94%   |
| Marvell Group 88E8052 PCI-E ASF Gigabit Ethernet Controller                    | 1        | 0.94%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1        | 0.94%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.94%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 0.94%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1        | 0.94%   |
| Intel 82579V Gigabit Network Connection                                        | 1        | 0.94%   |
| Intel 82578DM Gigabit Network Connection                                       | 1        | 0.94%   |
| Intel 82566DM Gigabit Network Connection                                       | 1        | 0.94%   |
| Intel 82562EZ 10/100 Ethernet Controller                                       | 1        | 0.94%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1        | 0.94%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 1        | 0.94%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                        | 1        | 0.94%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 0.94%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1        | 0.94%   |
| ASIX AX88772B                                                                  | 1        | 0.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 93       | 67.88%  |
| WiFi     | 42       | 30.66%  |
| Modem    | 2        | 1.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 83       | 81.37%  |
| WiFi     | 19       | 18.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 59       | 63.44%  |
| 2     | 30       | 32.26%  |
| 3     | 4        | 4.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 81.91%  |
| Yes  | 17       | 18.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 39.29%  |
| Cambridge Silicon Radio         | 7        | 25%     |
| ASUSTek Computer                | 3        | 10.71%  |
| Realtek Semiconductor           | 2        | 7.14%   |
| Qualcomm Atheros Communications | 2        | 7.14%   |
| MediaTek                        | 2        | 7.14%   |
| Broadcom                        | 1        | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 25%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 14.29%  |
| Realtek Bluetooth Radio                             | 2        | 7.14%   |
| MediaTek Wireless_Device                            | 2        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 7.14%   |
| Intel AX210 Bluetooth                               | 2        | 7.14%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 7.14%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 3.57%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 3.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.57%   |
| Intel Bluetooth wireless interface                  | 1        | 3.57%   |
| Intel Bluetooth Device                              | 1        | 3.57%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 3.57%   |
| ASUS BCM20702A0                                     | 1        | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 58       | 31.69%  |
| Nvidia                               | 39       | 21.31%  |
| AMD                                  | 33       | 18.03%  |
| C-Media Electronics                  | 6        | 3.28%   |
| Texas Instruments                    | 4        | 2.19%   |
| M-Audio                              | 4        | 2.19%   |
| Yamaha                               | 3        | 1.64%   |
| JMTek                                | 3        | 1.64%   |
| PreSonus Audio Electronics           | 2        | 1.09%   |
| Logitech                             | 2        | 1.09%   |
| Focusrite-Novation                   | 2        | 1.09%   |
| ZOOM                                 | 1        | 0.55%   |
| Xilinx                               | 1        | 0.55%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.55%   |
| Textech International                | 1        | 0.55%   |
| Tenx Technology                      | 1        | 0.55%   |
| TEAC                                 | 1        | 0.55%   |
| Studiologic                          | 1        | 0.55%   |
| SteelSeries ApS                      | 1        | 0.55%   |
| Samson Technologies                  | 1        | 0.55%   |
| QinHeng Electronics                  | 1        | 0.55%   |
| Plantronics                          | 1        | 0.55%   |
| MIDITECH                             | 1        | 0.55%   |
| Medeli Electronics                   | 1        | 0.55%   |
| Mark of the Unicorn                  | 1        | 0.55%   |
| KTMicro                              | 1        | 0.55%   |
| Harman                               | 1        | 0.55%   |
| Generalplus Technology               | 1        | 0.55%   |
| Focusrite                            | 1        | 0.55%   |
| Evolution Electronics                | 1        | 0.55%   |
| Ensoniq                              | 1        | 0.55%   |
| Creative Technology                  | 1        | 0.55%   |
| BEHRINGER International              | 1        | 0.55%   |
| Audient                              | 1        | 0.55%   |
| ASUSTek Computer                     | 1        | 0.55%   |
| Apple                                | 1        | 0.55%   |
| Alesis                               | 1        | 0.55%   |
| AKAI Professional M.I.               | 1        | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12       | 5.74%   |
| AMD Starship/Matisse HD Audio Controller                                          | 9        | 4.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 8        | 3.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 2.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6        | 2.87%   |
| AMD Family 17h/19h HD Audio Controller                                            | 6        | 2.87%   |
| Intel Cannon Lake PCH cAVS                                                        | 5        | 2.39%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 2.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 1.91%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 1.91%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3        | 1.44%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 1.44%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 1.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 1.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 1.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 1.44%   |
| AMD FCH Azalia Controller                                                         | 3        | 1.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 1.44%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.44%   |
| PreSonus Audio Electronics Studio 24c                                             | 2        | 0.96%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 0.96%   |
| Nvidia High Definition Audio Controller                                           | 2        | 0.96%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 0.96%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 0.96%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.96%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2        | 0.96%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 0.96%   |
| M-Audio M-Track                                                                   | 2        | 0.96%   |
| JMTek USB PnP Audio Device                                                        | 2        | 0.96%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 2        | 0.96%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 2        | 0.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 0.96%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 0.96%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 0.96%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 0.96%   |
| ZOOM U-22                                                                         | 1        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 16       | 13.91%  |
| SK hynix            | 15       | 13.04%  |
| Samsung Electronics | 14       | 12.17%  |
| Kingston            | 14       | 12.17%  |
| Corsair             | 12       | 10.43%  |
| Crucial             | 11       | 9.57%   |
| G.Skill             | 8        | 6.96%   |
| Micron Technology   | 6        | 5.22%   |
| Patriot             | 4        | 3.48%   |
| A-DATA Technology   | 2        | 1.74%   |
| Unifosa             | 1        | 0.87%   |
| Smart               | 1        | 0.87%   |
| S                   | 1        | 0.87%   |
| PNY                 | 1        | 0.87%   |
| OCZ                 | 1        | 0.87%   |
| Nanya Technology    | 1        | 0.87%   |
| M                   | 1        | 0.87%   |
| HBS                 | 1        | 0.87%   |
| Goldkey             | 1        | 0.87%   |
| Elpida              | 1        | 0.87%   |
| Avant               | 1        | 0.87%   |
| Aeneon              | 1        | 0.87%   |
| 0194808980CE        | 1        | 0.87%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s         | 3        | 2.31%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s          | 3        | 2.31%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 3        | 2.31%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                     | 2        | 1.54%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                    | 2        | 1.54%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s        | 2        | 1.54%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s         | 2        | 1.54%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 2        | 1.54%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s       | 2        | 1.54%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s      | 2        | 1.54%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1        | 0.77%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                   | 1        | 0.77%   |
| Unknown RAM Module 512MB DIMM DDR                           | 1        | 0.77%   |
| Unknown RAM Module 4GB DIMM SDRAM                           | 1        | 0.77%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s                    | 1        | 0.77%   |
| Unknown RAM Module 4GB DIMM 400MT/s                         | 1        | 0.77%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1        | 0.77%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 1        | 0.77%   |
| Unknown RAM Module 2GB DIMM DDR2                            | 1        | 0.77%   |
| Unknown RAM Module 256MB DIMM DDR                           | 1        | 0.77%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1        | 0.77%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1        | 0.77%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                    | 1        | 0.77%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1        | 0.77%   |
| Unknown RAM Module 1024MB DIMM DDR                          | 1        | 0.77%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1        | 0.77%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s                 | 1        | 0.77%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s           | 1        | 0.77%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s          | 1        | 0.77%   |
| SK hynix RAM TMT41GU6BFR8C-PBSC 8192MB DIMM DDR3 1600MT/s   | 1        | 0.77%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 0.77%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2666MT/s               | 1        | 0.77%   |
| SK hynix RAM Module 32GB DIMM DDR4 2667MT/s                 | 1        | 0.77%   |
| SK hynix RAM HYMP564U64BP8-C4 512MB DIMM DDR 533MT/s        | 1        | 0.77%   |
| SK hynix RAM HYMP125F72CP8N3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.77%   |
| SK hynix RAM HYMP125F72CP8D3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.77%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s        | 1        | 0.77%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1        | 0.77%   |
| SK hynix RAM HMT351U7CFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1        | 0.77%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1        | 0.77%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 39       | 40.63%  |
| DDR4    | 35       | 36.46%  |
| DDR2    | 9        | 9.38%   |
| Unknown | 6        | 6.25%   |
| SDRAM   | 3        | 3.13%   |
| DDR     | 3        | 3.13%   |
| DDR5    | 1        | 1.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 84       | 89.36%  |
| SODIMM  | 8        | 8.51%   |
| RIMM    | 1        | 1.06%   |
| FB-DIMM | 1        | 1.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 30       | 28.04%  |
| 8192  | 27       | 25.23%  |
| 2048  | 15       | 14.02%  |
| 16384 | 13       | 12.15%  |
| 32768 | 11       | 10.28%  |
| 1024  | 8        | 7.48%   |
| 512   | 2        | 1.87%   |
| 256   | 1        | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 24       | 22.22%  |
| 1333    | 11       | 10.19%  |
| 3600    | 10       | 9.26%   |
| 2133    | 6        | 5.56%   |
| 3200    | 5        | 4.63%   |
| 1866    | 5        | 4.63%   |
| 667     | 5        | 4.63%   |
| 1800    | 4        | 3.7%    |
| 1066    | 4        | 3.7%    |
| 800     | 4        | 3.7%    |
| Unknown | 4        | 3.7%    |
| 2667    | 3        | 2.78%   |
| 2400    | 3        | 2.78%   |
| 3400    | 2        | 1.85%   |
| 2933    | 2        | 1.85%   |
| 1867    | 2        | 1.85%   |
| 533     | 2        | 1.85%   |
| 4802    | 1        | 0.93%   |
| 3866    | 1        | 0.93%   |
| 3500    | 1        | 0.93%   |
| 3466    | 1        | 0.93%   |
| 3266    | 1        | 0.93%   |
| 3000    | 1        | 0.93%   |
| 2934    | 1        | 0.93%   |
| 2800    | 1        | 0.93%   |
| 2666    | 1        | 0.93%   |
| 2472    | 1        | 0.93%   |
| 1632    | 1        | 0.93%   |
| 400     | 1        | 0.93%   |

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
| Logitech                      | 7        | 30.43%  |
| Samsung Electronics           | 2        | 8.7%    |
| Microsoft                     | 2        | 8.7%    |
| Microdia                      | 2        | 8.7%    |
| Xiongmai                      | 1        | 4.35%   |
| ViewSonic                     | 1        | 4.35%   |
| Trust                         | 1        | 4.35%   |
| Sweex                         | 1        | 4.35%   |
| Sunplus IT                    | 1        | 4.35%   |
| Sunplus Innovation Technology | 1        | 4.35%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 4.35%   |
| Philips (or NXP)              | 1        | 4.35%   |
| MacroSilicon                  | 1        | 4.35%   |
| Jieli Technology              | 1        | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)           | 2        | 8.7%    |
| Logitech Webcam C270                              | 2        | 8.7%    |
| Xiongmai web camera                               | 1        | 4.35%   |
| ViewSonic PC Camera                               | 1        | 4.35%   |
| Trust AUKEY PC-LM1A Webcam                        | 1        | 4.35%   |
| Sweex WC060 Series HD Webcam                      | 1        | 4.35%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 1        | 4.35%   |
| Sunplus HD 720P webcam                            | 1        | 4.35%   |
| SHENZHEN AONI ELECTRONIC NexiGo N930AF FHD Webcam | 1        | 4.35%   |
| Philips (or NXP) Webcam SPC530NC                  | 1        | 4.35%   |
| Microsoft LifeCam VX-5000                         | 1        | 4.35%   |
| Microsoft LifeCam Cinema                          | 1        | 4.35%   |
| Microdia MSI Starcam Racer                        | 1        | 4.35%   |
| Microdia HoverCam Solo Spark Audio                | 1        | 4.35%   |
| MacroSilicon MiraBox Capture                      | 1        | 4.35%   |
| Logitech QuickCam Communicate MP/S5500            | 1        | 4.35%   |
| Logitech Portable Webcam C905                     | 1        | 4.35%   |
| Logitech HD Webcam C910                           | 1        | 4.35%   |
| Logitech HD Webcam C510                           | 1        | 4.35%   |
| Logitech HD Pro Webcam C920                       | 1        | 4.35%   |
| Jieli USB PHY 2.0                                 | 1        | 4.35%   |

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
| 0     | 79       | 84.95%  |
| 1     | 12       | 12.9%   |
| 2     | 2        | 2.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 6        | 37.5%   |
| Graphics card            | 3        | 18.75%  |
| Sound                    | 2        | 12.5%   |
| Multimedia controller    | 2        | 12.5%   |
| Unassigned class         | 1        | 6.25%   |
| Modem                    | 1        | 6.25%   |
| Communication controller | 1        | 6.25%   |

