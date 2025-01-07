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

Total: 128

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | 3728 SDK0J40709 WIN 3259... | [04c0c560d4](https://linux-hardware.org/?probe=04c0c560d4) | Jan 03, 2025 |
| Gigabyte      | X570 AORUS PRO WIFI         | [27824c7505](https://linux-hardware.org/?probe=27824c7505) | Dec 09, 2024 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [0dc0dd7a62](https://linux-hardware.org/?probe=0dc0dd7a62) | Nov 20, 2024 |
| MSI           | Z370 PC PRO                 | [518166326c](https://linux-hardware.org/?probe=518166326c) | Nov 11, 2024 |
| ASRock        | H97M Pro4                   | [c694317e1f](https://linux-hardware.org/?probe=c694317e1f) | Nov 08, 2024 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7ae1cb1ad0](https://linux-hardware.org/?probe=7ae1cb1ad0) | Nov 01, 2024 |
| Gigabyte      | GA-A75M-DS2                 | [1bf6907ed6](https://linux-hardware.org/?probe=1bf6907ed6) | Oct 20, 2024 |
| Lenovo        | ThinkCentre M58p 7220RY8    | [9a160a771d](https://linux-hardware.org/?probe=9a160a771d) | Sep 16, 2024 |
| Alienware     | 01NYPT A00                  | [953351e395](https://linux-hardware.org/?probe=953351e395) | Aug 31, 2024 |
| MSI           | 970A SLI Krait Edition      | [a1636d9c36](https://linux-hardware.org/?probe=a1636d9c36) | Aug 01, 2024 |
| MSI           | 970A SLI Krait Edition      | [337a3488ce](https://linux-hardware.org/?probe=337a3488ce) | Aug 01, 2024 |
| HP            | 2B16                        | [f8836660b7](https://linux-hardware.org/?probe=f8836660b7) | Jul 24, 2024 |
| ASUSTek       | P5KPL-CM                    | [93e318f098](https://linux-hardware.org/?probe=93e318f098) | Jul 24, 2024 |
| ASUSTek       | B150M-A/M.2                 | [e3507bd66f](https://linux-hardware.org/?probe=e3507bd66f) | Jul 08, 2024 |
| ASUSTek       | PRIME B550M-A AC            | [34e04923f3](https://linux-hardware.org/?probe=34e04923f3) | Jun 28, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | [54b86a5399](https://linux-hardware.org/?probe=54b86a5399) | Jun 23, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [0bf1e098c0](https://linux-hardware.org/?probe=0bf1e098c0) | Jun 19, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | [134f7ad848](https://linux-hardware.org/?probe=134f7ad848) | May 10, 2024 |
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
| Ubuntu Studio 20.04 | 42       | 38.18%  |
| Ubuntu Studio 22.04 | 32       | 29.09%  |
| Ubuntu Studio 24.04 | 10       | 9.09%   |
| Ubuntu Studio 20.10 | 9        | 8.18%   |
| Ubuntu Studio 23.10 | 5        | 4.55%   |
| Ubuntu Studio 22.10 | 4        | 3.64%   |
| Ubuntu Studio 21.10 | 3        | 2.73%   |
| Ubuntu Studio 23.04 | 2        | 1.82%   |
| Ubuntu Studio 21.04 | 2        | 1.82%   |
| Ubuntu Studio 16.04 | 1        | 0.91%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu Studio | 109      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 6.8.0-47-lowlatency    | 5        | 4.42%   |
| 6.2.0-1009-lowlatency  | 3        | 2.65%   |
| 5.15.0-58-lowlatency   | 3        | 2.65%   |
| 5.11.0-44-lowlatency   | 3        | 2.65%   |
| 6.5.0-41-lowlatency    | 2        | 1.77%   |
| 6.5.0-28-lowlatency    | 2        | 1.77%   |
| 5.8.0-48-lowlatency    | 2        | 1.77%   |
| 5.8.0-44-lowlatency    | 2        | 1.77%   |
| 5.8.0-25-lowlatency    | 2        | 1.77%   |
| 5.4.0-58-lowlatency    | 2        | 1.77%   |
| 5.4.0-56-lowlatency    | 2        | 1.77%   |
| 5.4.0-42-lowlatency    | 2        | 1.77%   |
| 5.4.0-26-lowlatency    | 2        | 1.77%   |
| 5.19.0-1021-lowlatency | 2        | 1.77%   |
| 5.15.0-89-lowlatency   | 2        | 1.77%   |
| 5.15.0-79-lowlatency   | 2        | 1.77%   |
| 5.15.0-71-lowlatency   | 2        | 1.77%   |
| 5.15.0-56-lowlatency   | 2        | 1.77%   |
| 5.15.0-53-lowlatency   | 2        | 1.77%   |
| 5.15.0-52-lowlatency   | 2        | 1.77%   |
| 5.15.0-46-lowlatency   | 2        | 1.77%   |
| 5.13.0-28-lowlatency   | 2        | 1.77%   |
| 6.8.0-49-lowlatency    | 1        | 0.88%   |
| 6.8.0-41-lowlatency    | 1        | 0.88%   |
| 6.8.0-39-lowlatency    | 1        | 0.88%   |
| 6.8.0-38-generic       | 1        | 0.88%   |
| 6.8.0-36-lowlatency    | 1        | 0.88%   |
| 6.8.0-35-lowlatency    | 1        | 0.88%   |
| 6.5.0-9-lowlatency     | 1        | 0.88%   |
| 6.5.0-5-lowlatency     | 1        | 0.88%   |
| 6.5.0-44-lowlatency    | 1        | 0.88%   |
| 6.5.0-27-lowlatency    | 1        | 0.88%   |
| 6.5.0-13-lowlatency    | 1        | 0.88%   |
| 6.2.0-1014-lowlatency  | 1        | 0.88%   |
| 6.2.0-1007-lowlatency  | 1        | 0.88%   |
| 5.8.0-50-lowlatency    | 1        | 0.88%   |
| 5.8.0-45-lowlatency    | 1        | 0.88%   |
| 5.8.0-36-lowlatency    | 1        | 0.88%   |
| 5.8.0-34-lowlatency    | 1        | 0.88%   |
| 5.8.0-33-lowlatency    | 1        | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 29.09%  |
| 5.15.0  | 26       | 23.64%  |
| 5.8.0   | 12       | 10.91%  |
| 6.8.0   | 11       | 10%     |
| 6.5.0   | 8        | 7.27%   |
| 5.11.0  | 6        | 5.45%   |
| 6.2.0   | 5        | 4.55%   |
| 5.19.0  | 5        | 4.55%   |
| 5.13.0  | 3        | 2.73%   |
| 5.15.6  | 1        | 0.91%   |
| 4.4.0   | 1        | 0.91%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 32       | 29.09%  |
| 5.15    | 27       | 24.55%  |
| 5.8     | 12       | 10.91%  |
| 6.8     | 11       | 10%     |
| 6.5     | 8        | 7.27%   |
| 5.11    | 6        | 5.45%   |
| 6.2     | 5        | 4.55%   |
| 5.19    | 5        | 4.55%   |
| 5.13    | 3        | 2.73%   |
| 4.4     | 1        | 0.91%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 108      | 99.08%  |
| i686   | 1        | 0.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 59       | 53.64%  |
| XFCE            | 39       | 35.45%  |
| GNOME           | 5        | 4.55%   |
| MATE            | 2        | 1.82%   |
| LXQt            | 2        | 1.82%   |
| KDE             | 1        | 0.91%   |
| GNOME Flashback | 1        | 0.91%   |
| Cinnamon        | 1        | 0.91%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 103      | 93.64%  |
| Tty     | 4        | 3.64%   |
| Wayland | 3        | 2.73%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 55       | 50.46%  |
| TDM     | 25       | 22.94%  |
| LightDM | 22       | 20.18%  |
| GDM     | 6        | 5.5%    |
| GDM3    | 1        | 0.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 44       | 40.37%  |
| de_DE      | 11       | 10.09%  |
| fr_FR      | 9        | 8.26%   |
| en_GB      | 7        | 6.42%   |
| it_IT      | 5        | 4.59%   |
| pt_BR      | 4        | 3.67%   |
| ru_RU      | 3        | 2.75%   |
| C          | 3        | 2.75%   |
| es_ES      | 2        | 1.83%   |
| en_CA      | 2        | 1.83%   |
| en_AU      | 2        | 1.83%   |
| tr_TR      | 1        | 0.92%   |
| sv_SE      | 1        | 0.92%   |
| nl_NL      | 1        | 0.92%   |
| nl_BE      | 1        | 0.92%   |
| nb_NO      | 1        | 0.92%   |
| fr_FR.UTF8 | 1        | 0.92%   |
| fr_CH      | 1        | 0.92%   |
| fr_BE      | 1        | 0.92%   |
| es_GT      | 1        | 0.92%   |
| es_AR      | 1        | 0.92%   |
| en_NZ      | 1        | 0.92%   |
| en_IL      | 1        | 0.92%   |
| en_DE      | 1        | 0.92%   |
| de_AT      | 1        | 0.92%   |
| ca_ES      | 1        | 0.92%   |
| ca_AD      | 1        | 0.92%   |
| bg_BG      | 1        | 0.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 61       | 55.96%  |
| EFI  | 48       | 44.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 105      | 96.33%  |
| Overlay | 2        | 1.83%   |
| Xfs     | 1        | 0.92%   |
| Ext2    | 1        | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 62       | 56.88%  |
| MBR  | 47       | 43.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 70.91%  |
| Yes       | 32       | 29.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 56.36%  |
| Yes       | 48       | 43.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 31       | 28.44%  |
| Gigabyte Technology                  | 18       | 16.51%  |
| Dell                                 | 13       | 11.93%  |
| Hewlett-Packard                      | 11       | 10.09%  |
| MSI                                  | 7        | 6.42%   |
| Fujitsu                              | 4        | 3.67%   |
| ASRock                               | 4        | 3.67%   |
| Lenovo                               | 3        | 2.75%   |
| Intel                                | 2        | 1.83%   |
| Unknown                              | 2        | 1.83%   |
| System76                             | 1        | 0.92%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.92%   |
| Pegatron                             | 1        | 0.92%   |
| Packard Bell                         | 1        | 0.92%   |
| Medion                               | 1        | 0.92%   |
| IBM                                  | 1        | 0.92%   |
| Foxconn                              | 1        | 0.92%   |
| ECS                                  | 1        | 0.92%   |
| DEPO Computers                       | 1        | 0.92%   |
| AZW                                  | 1        | 0.92%   |
| Apple                                | 1        | 0.92%   |
| Alienware                            | 1        | 0.92%   |
| Acidanthera                          | 1        | 0.92%   |
| Acer                                 | 1        | 0.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 4        | 3.67%   |
| Unknown                                    | 3        | 2.75%   |
| Dell OptiPlex 790                          | 2        | 1.83%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 1.83%   |
| ASUS PRIME X570-PRO                        | 2        | 1.83%   |
| ASUS M4A785-M                              | 2        | 1.83%   |
| System76 Thelio                            | 1        | 0.92%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.92%   |
| Pegatron FL368AA-UUZ SR5612CH              | 1        | 0.92%   |
| Packard Bell IMEDIA S3220                  | 1        | 0.92%   |
| MSI PC Primescan AC                        | 1        | 0.92%   |
| MSI MS-7E06                                | 1        | 0.92%   |
| MSI MS-7E02                                | 1        | 0.92%   |
| MSI MS-7C95                                | 1        | 0.92%   |
| MSI MS-7A57                                | 1        | 0.92%   |
| MSI MS-7752                                | 1        | 0.92%   |
| MSI MS-7693                                | 1        | 0.92%   |
| Medion MD34207/C746                        | 1        | 0.92%   |
| Lenovo ThinkCentre M93p 10A8S45S00         | 1        | 0.92%   |
| Lenovo ThinkCentre M58p 7220RY8            | 1        | 0.92%   |
| Lenovo IdeaCentre 5 14ARE05 90Q3004YMH     | 1        | 0.92%   |
| Intel DQ965GF HD/FP Audio                  | 1        | 0.92%   |
| IBM 8188PPV                                | 1        | 0.92%   |
| HP Z620 Workstation                        | 1        | 0.92%   |
| HP Z2 Tower G4 Workstation                 | 1        | 0.92%   |
| HP ProDesk 600 G1 SFF                      | 1        | 0.92%   |
| HP Compaq Pro 6305 SFF                     | 1        | 0.92%   |
| HP Compaq Elite 8300 CMT                   | 1        | 0.92%   |
| HP Compaq dc7600 Small Form Factor         | 1        | 0.92%   |
| HP Compaq 8200 Elite SFF PC                | 1        | 0.92%   |
| HP Compaq 8100 Elite SFF PC                | 1        | 0.92%   |
| HP Compaq 6200 Pro MT PC                   | 1        | 0.92%   |
| HP Compaq 6005 Pro MT PC                   | 1        | 0.92%   |
| HP 23-s010                                 | 1        | 0.92%   |
| Gigabyte X79S-UP5                          | 1        | 0.92%   |
| Gigabyte X58A-UD3R                         | 1        | 0.92%   |
| Gigabyte X570 AORUS PRO WIFI               | 1        | 0.92%   |
| Gigabyte X570 AORUS ELITE WIFI             | 1        | 0.92%   |
| Gigabyte H61M-D2-B3                        | 1        | 0.92%   |
| Gigabyte H270-HD3P                         | 1        | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 9        | 8.26%   |
| HP Compaq                                  | 7        | 6.42%   |
| ASUS ROG                                   | 6        | 5.5%    |
| ASUS PRIME                                 | 4        | 3.67%   |
| ASUS All                                   | 4        | 3.67%   |
| Fujitsu ESPRIMO                            | 3        | 2.75%   |
| Dell Precision                             | 3        | 2.75%   |
| ASUS TUF                                   | 3        | 2.75%   |
| Unknown                                    | 3        | 2.75%   |
| Lenovo ThinkCentre                         | 2        | 1.83%   |
| Gigabyte X570                              | 2        | 1.83%   |
| ASUS P8P67                                 | 2        | 1.83%   |
| ASUS M4A785-M                              | 2        | 1.83%   |
| System76 Thelio                            | 1        | 0.92%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.92%   |
| Pegatron FL368AA-UUZ                       | 1        | 0.92%   |
| Packard Bell IMEDIA                        | 1        | 0.92%   |
| MSI PC                                     | 1        | 0.92%   |
| MSI MS-7E06                                | 1        | 0.92%   |
| MSI MS-7E02                                | 1        | 0.92%   |
| MSI MS-7C95                                | 1        | 0.92%   |
| MSI MS-7A57                                | 1        | 0.92%   |
| MSI MS-7752                                | 1        | 0.92%   |
| MSI MS-7693                                | 1        | 0.92%   |
| Medion MD34207                             | 1        | 0.92%   |
| Lenovo IdeaCentre                          | 1        | 0.92%   |
| Intel DQ965GF                              | 1        | 0.92%   |
| IBM 8188PPV                                | 1        | 0.92%   |
| HP Z620                                    | 1        | 0.92%   |
| HP Z2                                      | 1        | 0.92%   |
| HP ProDesk                                 | 1        | 0.92%   |
| HP 23-s010                                 | 1        | 0.92%   |
| Gigabyte X79S-UP5                          | 1        | 0.92%   |
| Gigabyte X58A-UD3R                         | 1        | 0.92%   |
| Gigabyte H61M-D2-B3                        | 1        | 0.92%   |
| Gigabyte H270-HD3P                         | 1        | 0.92%   |
| Gigabyte H170-HD3-CF                       | 1        | 0.92%   |
| Gigabyte GA-MA770-DS3                      | 1        | 0.92%   |
| Gigabyte GA-A75M-DS2                       | 1        | 0.92%   |
| Gigabyte GA-78LMT-USB3                     | 1        | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 13       | 11.93%  |
| 2019 | 10       | 9.17%   |
| 2018 | 10       | 9.17%   |
| 2020 | 8        | 7.34%   |
| 2016 | 8        | 7.34%   |
| 2014 | 8        | 7.34%   |
| 2011 | 7        | 6.42%   |
| 2009 | 7        | 6.42%   |
| 2012 | 6        | 5.5%    |
| 2008 | 6        | 5.5%    |
| 2022 | 5        | 4.59%   |
| 2015 | 4        | 3.67%   |
| 2010 | 4        | 3.67%   |
| 2021 | 3        | 2.75%   |
| 2017 | 3        | 2.75%   |
| 2005 | 3        | 2.75%   |
| 2023 | 2        | 1.83%   |
| 2007 | 2        | 1.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 109      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 108      | 99.08%  |
| Enabled  | 1        | 0.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 109      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 28       | 25.69%  |
| 32.01-64.0  | 18       | 16.51%  |
| 8.01-16.0   | 18       | 16.51%  |
| 4.01-8.0    | 17       | 15.6%   |
| 64.01-256.0 | 14       | 12.84%  |
| 3.01-4.0    | 9        | 8.26%   |
| 1.01-2.0    | 3        | 2.75%   |
| 24.01-32.0  | 1        | 0.92%   |
| 2.01-3.0    | 1        | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 31       | 27.93%  |
| 4.01-8.0   | 28       | 25.23%  |
| 2.01-3.0   | 24       | 21.62%  |
| 3.01-4.0   | 11       | 9.91%   |
| 8.01-16.0  | 11       | 9.91%   |
| 0.51-1.0   | 3        | 2.7%    |
| 32.01-64.0 | 1        | 0.9%    |
| 24.01-32.0 | 1        | 0.9%    |
| 16.01-24.0 | 1        | 0.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 40       | 36.7%   |
| 1      | 39       | 35.78%  |
| 3      | 13       | 11.93%  |
| 5      | 5        | 4.59%   |
| 4      | 5        | 4.59%   |
| 7      | 4        | 3.67%   |
| 16     | 1        | 0.92%   |
| 11     | 1        | 0.92%   |
| 10     | 1        | 0.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 57       | 52.29%  |
| No        | 52       | 47.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 108      | 99.08%  |
| No        | 1        | 0.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 52.29%  |
| Yes       | 52       | 47.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 72       | 66.06%  |
| Yes       | 37       | 33.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 27       | 24.77%  |
| Germany                | 15       | 13.76%  |
| France                 | 11       | 10.09%  |
| Italy                  | 8        | 7.34%   |
| Brazil                 | 5        | 4.59%   |
| UK                     | 4        | 3.67%   |
| Spain                  | 4        | 3.67%   |
| Belgium                | 4        | 3.67%   |
| Austria                | 4        | 3.67%   |
| Russia                 | 3        | 2.75%   |
| Sweden                 | 2        | 1.83%   |
| Netherlands            | 2        | 1.83%   |
| Mexico                 | 2        | 1.83%   |
| Israel                 | 2        | 1.83%   |
| Canada                 | 2        | 1.83%   |
| Australia              | 2        | 1.83%   |
| Turkey                 | 1        | 0.92%   |
| Switzerland            | 1        | 0.92%   |
| Romania                | 1        | 0.92%   |
| Philippines            | 1        | 0.92%   |
| Norway                 | 1        | 0.92%   |
| New Zealand            | 1        | 0.92%   |
| Luxembourg             | 1        | 0.92%   |
| Kenya                  | 1        | 0.92%   |
| Guatemala              | 1        | 0.92%   |
| Bulgaria               | 1        | 0.92%   |
| Bosnia and Herzegovina | 1        | 0.92%   |
| Argentina              | 1        | 0.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Paris                   | 3        | 2.7%    |
| Houston                 | 3        | 2.7%    |
| Vienna                  | 2        | 1.8%    |
| Stockholm               | 2        | 1.8%    |
| Madrid                  | 2        | 1.8%    |
| Zanesville              | 1        | 0.9%    |
| Wildenfels              | 1        | 0.9%    |
| West Mifflin            | 1        | 0.9%    |
| Villetaneuse            | 1        | 0.9%    |
| Villefontaine           | 1        | 0.9%    |
| Verviers                | 1        | 0.9%    |
| Vaals                   | 1        | 0.9%    |
| Turin                   | 1        | 0.9%    |
| Tucson                  | 1        | 0.9%    |
| Tilburg                 | 1        | 0.9%    |
| Tel Aviv                | 1        | 0.9%    |
| Stuttgart               | 1        | 0.9%    |
| Sherman Oaks            | 1        | 0.9%    |
| Sarajevo                | 1        | 0.9%    |
| Sao Paulo               | 1        | 0.9%    |
| Santa Barbara d'Oeste   | 1        | 0.9%    |
| San Secondo di Pinerolo | 1        | 0.9%    |
| Saint-Ouen-l'Aumone     | 1        | 0.9%    |
| Rome                    | 1        | 0.9%    |
| Rio Grande da Serra     | 1        | 0.9%    |
| Rennes                  | 1        | 0.9%    |
| Potsdam                 | 1        | 0.9%    |
| Port Moody              | 1        | 0.9%    |
| Pisa                    | 1        | 0.9%    |
| Philadelphia            | 1        | 0.9%    |
| Perth                   | 1        | 0.9%    |
| Palermo                 | 1        | 0.9%    |
| Oslo                    | 1        | 0.9%    |
| Olympia                 | 1        | 0.9%    |
| Oldenburg               | 1        | 0.9%    |
| Oberhausen              | 1        | 0.9%    |
| Novosibirsk             | 1        | 0.9%    |
| Nottingham              | 1        | 0.9%    |
| Naumburg                | 1        | 0.9%    |
| Namur                   | 1        | 0.9%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 39       | 52     | 18.57%  |
| Seagate                     | 36       | 63     | 17.14%  |
| Samsung Electronics         | 31       | 45     | 14.76%  |
| SanDisk                     | 15       | 16     | 7.14%   |
| Toshiba                     | 12       | 13     | 5.71%   |
| Kingston                    | 9        | 10     | 4.29%   |
| Hitachi                     | 9        | 10     | 4.29%   |
| Crucial                     | 8        | 9      | 3.81%   |
| HGST                        | 4        | 5      | 1.9%    |
| PNY                         | 3        | 4      | 1.43%   |
| Phison                      | 3        | 3      | 1.43%   |
| Intenso                     | 3        | 3      | 1.43%   |
| Team                        | 2        | 2      | 0.95%   |
| SPCC                        | 2        | 2      | 0.95%   |
| Kingston Technology Company | 2        | 2      | 0.95%   |
| JMicron Technology          | 2        | 2      | 0.95%   |
| Intel                       | 2        | 2      | 0.95%   |
| Corsair                     | 2        | 3      | 0.95%   |
| ASMT                        | 2        | 2      | 0.95%   |
| A-DATA Technology           | 2        | 2      | 0.95%   |
| USB 3.0                     | 1        | 2      | 0.48%   |
| UMIS                        | 1        | 1      | 0.48%   |
| TO Exter                    | 1        | 1      | 0.48%   |
| Timetec                     | 1        | 1      | 0.48%   |
| SK hynix                    | 1        | 1      | 0.48%   |
| Silicon Motion              | 1        | 1      | 0.48%   |
| Realtek Semiconductor       | 1        | 1      | 0.48%   |
| Phison Electronics          | 1        | 1      | 0.48%   |
| Patriot                     | 1        | 1      | 0.48%   |
| OCZ                         | 1        | 1      | 0.48%   |
| NGFF                        | 1        | 1      | 0.48%   |
| Micron Technology           | 1        | 1      | 0.48%   |
| Maxtor                      | 1        | 1      | 0.48%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.48%   |
| LITEON                      | 1        | 1      | 0.48%   |
| Lexar                       | 1        | 4      | 0.48%   |
| Leven                       | 1        | 1      | 0.48%   |
| Integral                    | 1        | 1      | 0.48%   |
| Fujitsu                     | 1        | 1      | 0.48%   |
| China                       | 1        | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 4        | 1.62%   |
| Seagate ST2000DM001-1ER164 2TB   | 4        | 1.62%   |
| WDC WDS200T2B0A-00SM50 2TB SSD   | 3        | 1.21%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.21%   |
| Toshiba DT01ACA050 500GB         | 3        | 1.21%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 1.21%   |
| Seagate Expansion 1TB            | 3        | 1.21%   |
| Samsung SSD 850 EVO 500GB        | 3        | 1.21%   |
| Crucial CT1000MX500SSD1 1TB      | 3        | 1.21%   |
| WDC WD20EZRX-00D8PB0 2TB         | 2        | 0.81%   |
| Toshiba HDWD130 3TB              | 2        | 0.81%   |
| Team T253X6001T 1024GB SSD       | 2        | 0.81%   |
| SPCC Solid State Disk 256GB      | 2        | 0.81%   |
| Seagate ST5000LM000-2AN170 5TB   | 2        | 0.81%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 0.81%   |
| Seagate Expansion Desk 5TB       | 2        | 0.81%   |
| SanDisk SDSSDA240G 240GB         | 2        | 0.81%   |
| Samsung SSD 970 EVO Plus 500GB   | 2        | 0.81%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 0.81%   |
| Samsung SSD 870 EVO 1TB          | 2        | 0.81%   |
| Samsung SSD 860 EVO 1TB          | 2        | 0.81%   |
| Samsung HD753LJ 752GB            | 2        | 0.81%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 0.81%   |
| Kingston SA400S37480G 480GB SSD  | 2        | 0.81%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 0.81%   |
| Hitachi HDS721010CLA332 1TB      | 2        | 0.81%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 0.81%   |
| WDC WDS512G1X0C-00ENX0 512GB     | 1        | 0.4%    |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 0.4%    |
| WDC WDBNCE5000PNC 500GB SSD      | 1        | 0.4%    |
| WDC WD6400AAKS-22A7B2 640GB      | 1        | 0.4%    |
| WDC WD60EFAX-68JH4N1 6TB         | 1        | 0.4%    |
| WDC WD5000BPKT-60PK4T0 500GB     | 1        | 0.4%    |
| WDC WD5000AVDS-63U7B1 500GB      | 1        | 0.4%    |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.4%    |
| WDC WD5000AAKS-75V0A0 500GB      | 1        | 0.4%    |
| WDC WD5000AAKS-00TMA0 500GB      | 1        | 0.4%    |
| WDC WD40EZRZ-00GXCB0 4TB         | 1        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 35       | 60     | 33.98%  |
| WDC                 | 34       | 43     | 33.01%  |
| Toshiba             | 12       | 13     | 11.65%  |
| Hitachi             | 9        | 10     | 8.74%   |
| HGST                | 4        | 5      | 3.88%   |
| Samsung Electronics | 3        | 3      | 2.91%   |
| USB 3.0             | 1        | 2      | 0.97%   |
| TO Exter            | 1        | 1      | 0.97%   |
| Maxtor              | 1        | 1      | 0.97%   |
| JMicron Technology  | 1        | 1      | 0.97%   |
| Fujitsu             | 1        | 1      | 0.97%   |
| ASMT                | 1        | 1      | 0.97%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 22     | 22.67%  |
| SanDisk             | 13       | 14     | 17.33%  |
| Kingston            | 9        | 10     | 12%     |
| Crucial             | 8        | 9      | 10.67%  |
| WDC                 | 5        | 7      | 6.67%   |
| PNY                 | 3        | 4      | 4%      |
| Intenso             | 3        | 3      | 4%      |
| Team                | 2        | 2      | 2.67%   |
| SPCC                | 2        | 2      | 2.67%   |
| A-DATA Technology   | 2        | 2      | 2.67%   |
| Seagate             | 1        | 1      | 1.33%   |
| Patriot             | 1        | 1      | 1.33%   |
| OCZ                 | 1        | 1      | 1.33%   |
| NGFF                | 1        | 1      | 1.33%   |
| Micron Technology   | 1        | 1      | 1.33%   |
| Leven               | 1        | 1      | 1.33%   |
| Integral            | 1        | 1      | 1.33%   |
| Corsair             | 1        | 1      | 1.33%   |
| China               | 1        | 1      | 1.33%   |
| BHT                 | 1        | 1      | 1.33%   |
| ASMT                | 1        | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 74       | 141    | 44.31%  |
| SSD     | 60       | 86     | 35.93%  |
| NVMe    | 30       | 46     | 17.96%  |
| Unknown | 3        | 3      | 1.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 99       | 211    | 70.21%  |
| NVMe | 30       | 46     | 21.28%  |
| SAS  | 12       | 19     | 8.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 68       | 98     | 43.87%  |
| 0.51-1.0   | 44       | 57     | 28.39%  |
| 1.01-2.0   | 22       | 30     | 14.19%  |
| 3.01-4.0   | 8        | 10     | 5.16%   |
| 4.01-10.0  | 8        | 25     | 5.16%   |
| 2.01-3.0   | 5        | 7      | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 26       | 23.64%  |
| 501-1000       | 23       | 20.91%  |
| More than 3000 | 21       | 19.09%  |
| 1001-2000      | 21       | 19.09%  |
| 251-500        | 9        | 8.18%   |
| 51-100         | 4        | 3.64%   |
| 21-50          | 2        | 1.82%   |
| 2001-3000      | 2        | 1.82%   |
| 1-20           | 2        | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 24       | 21.43%  |
| 21-50          | 16       | 14.29%  |
| 101-250        | 14       | 12.5%   |
| 251-500        | 13       | 11.61%  |
| More than 3000 | 12       | 10.71%  |
| 51-100         | 10       | 8.93%   |
| 1001-2000      | 9        | 8.04%   |
| 501-1000       | 9        | 8.04%   |
| 2001-3000      | 5        | 4.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 3        | 3      | 11.54%  |
| Samsung Electronics HD753LJ 752GB     | 2        | 2      | 7.69%   |
| WDC WD5000AVDS-63U7B1 500GB           | 1        | 1      | 3.85%   |
| WDC WD5000AAKS-00TMA0 500GB           | 1        | 1      | 3.85%   |
| WDC WD1600AAJS-08L7A0 160GB           | 1        | 1      | 3.85%   |
| WDC WD10EZEX-22BN5A0 1TB              | 1        | 1      | 3.85%   |
| WDC WD10EAVS-32D7B1 1TB               | 1        | 1      | 3.85%   |
| WDC WD10EADS-00M2B0 1TB               | 1        | 1      | 3.85%   |
| Toshiba MQ01ABF050 500GB              | 1        | 1      | 3.85%   |
| Toshiba HDWE140 4TB                   | 1        | 1      | 3.85%   |
| Seagate ST8000DM004-2CX1 8TB          | 1        | 6      | 3.85%   |
| Seagate ST3320820AS 320GB             | 1        | 1      | 3.85%   |
| Seagate ST3200822AS 200GB             | 1        | 1      | 3.85%   |
| Seagate ST2000DM006-2DM164 2TB        | 1        | 1      | 3.85%   |
| Seagate ST1000VM002-9ZL162 1TB        | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 970 EVO 1TB   | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 960 PRO 512GB | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1        | 2      | 3.85%   |
| Hitachi HDS721010CLA332 1TB           | 1        | 1      | 3.85%   |
| Hitachi HDS5C1010CLA382 1TB           | 1        | 1      | 3.85%   |
| HGST HTS721010A9 1TB                  | 1        | 1      | 3.85%   |
| A-DATA Technology SU650 240GB SSD     | 1        | 1      | 3.85%   |
| A-DATA Technology SP550 240GB SSD     | 1        | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 13     | 32%     |
| WDC                 | 5        | 6      | 20%     |
| Samsung Electronics | 5        | 6      | 20%     |
| Toshiba             | 2        | 2      | 8%      |
| Hitachi             | 2        | 2      | 8%      |
| A-DATA Technology   | 2        | 2      | 8%      |
| HGST                | 1        | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 13     | 40%     |
| WDC                 | 5        | 6      | 25%     |
| Toshiba             | 2        | 2      | 10%     |
| Samsung Electronics | 2        | 2      | 10%     |
| Hitachi             | 2        | 2      | 10%     |
| HGST                | 1        | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 26     | 78.26%  |
| SSD  | 3        | 4      | 13.04%  |
| NVMe | 2        | 2      | 8.7%    |

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
| Works    | 103      | 220    | 72.54%  |
| Malfunc  | 23       | 32     | 16.2%   |
| Detected | 13       | 21     | 9.15%   |
| Failed   | 2        | 2      | 1.41%   |
| Fixed    | 1        | 1      | 0.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 71       | 44.38%  |
| AMD                          | 34       | 21.25%  |
| Samsung Electronics          | 14       | 8.75%   |
| Marvell Technology Group     | 6        | 3.75%   |
| ASMedia Technology           | 6        | 3.75%   |
| Phison Electronics           | 5        | 3.13%   |
| SanDisk                      | 4        | 2.5%    |
| Nvidia                       | 3        | 1.88%   |
| Silicon Motion               | 2        | 1.25%   |
| Kingston Technology Company  | 2        | 1.25%   |
| JMicron Technology           | 2        | 1.25%   |
| VIA Technologies             | 1        | 0.63%   |
| Union Memory (Shenzhen)      | 1        | 0.63%   |
| SK hynix                     | 1        | 0.63%   |
| Silicon Image                | 1        | 0.63%   |
| Shenzhen Longsys Electronics | 1        | 0.63%   |
| Realtek Semiconductor        | 1        | 0.63%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.63%   |
| LSI Logic / Symbios Logic    | 1        | 0.63%   |
| Lite-On Technology           | 1        | 0.63%   |
| Apple                        | 1        | 0.63%   |
| Adaptec                      | 1        | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 17       | 8.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 5.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 4.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 3.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 3.02%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 6        | 3.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 2.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 2.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 2.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.51%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 2.51%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 2.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 2.01%   |
| Intel SATA Controller [RAID Mode]                                                       | 3        | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.51%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 2        | 1.01%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 2        | 1.01%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.01%   |
| Phison E12 NVMe Controller                                                              | 2        | 1.01%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2        | 1.01%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 2        | 1.01%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 1.01%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 2        | 1.01%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 2        | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.01%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.01%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.01%   |
| AMD FCH IDE Controller                                                                  | 2        | 1.01%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.5%    |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                                   | 1        | 0.5%    |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1        | 0.5%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.5%    |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                                       | 1        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 90       | 57.32%  |
| NVMe | 30       | 19.11%  |
| IDE  | 29       | 18.47%  |
| RAID | 4        | 2.55%   |
| SAS  | 3        | 1.91%   |
| SCSI | 1        | 0.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 72       | 66.06%  |
| AMD    | 37       | 33.94%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz        | 3        | 2.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3        | 2.75%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 2        | 1.83%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2        | 1.83%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2        | 1.83%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2        | 1.83%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2        | 1.83%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2        | 1.83%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 2        | 1.83%   |
| Intel Core i3-6100 CPU @ 3.70GHz        | 2        | 1.83%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2        | 1.83%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 2        | 1.83%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 2        | 1.83%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2        | 1.83%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 2        | 1.83%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2        | 1.83%   |
| AMD Phenom II X4 945 Processor          | 2        | 1.83%   |
| AMD FX-8350 Eight-Core Processor        | 2        | 1.83%   |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1        | 0.92%   |
| Intel Xeon CPU E5420 @ 2.50GHz          | 1        | 0.92%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz     | 1        | 0.92%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1        | 0.92%   |
| Intel Pentium D CPU 3.40GHz             | 1        | 0.92%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1        | 0.92%   |
| Intel Pentium 4 CPU 3.20GHz             | 1        | 0.92%   |
| Intel Pentium 4 CPU 2.80GHz             | 1        | 0.92%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1        | 0.92%   |
| Intel Core i9-10900 CPU @ 2.80GHz       | 1        | 0.92%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 1        | 0.92%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 1        | 0.92%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1        | 0.92%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1        | 0.92%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1        | 0.92%   |
| Intel Core i7-4790S CPU @ 3.20GHz       | 1        | 0.92%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 1        | 0.92%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1        | 0.92%   |
| Intel Core i7-3930K CPU @ 3.20GHz       | 1        | 0.92%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1        | 0.92%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1        | 0.92%   |
| Intel Core i7 CPU 960 @ 3.20GHz         | 1        | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 24       | 22.02%  |
| Intel Core i7          | 17       | 15.6%   |
| Intel Core i3          | 9        | 8.26%   |
| AMD Ryzen 5            | 8        | 7.34%   |
| AMD Ryzen 9            | 7        | 6.42%   |
| Intel Xeon             | 4        | 3.67%   |
| Intel Core i9          | 4        | 3.67%   |
| AMD Phenom II X4       | 4        | 3.67%   |
| AMD FX                 | 4        | 3.67%   |
| Other                  | 3        | 2.75%   |
| Intel Core 2 Quad      | 3        | 2.75%   |
| AMD Ryzen 7            | 3        | 2.75%   |
| Intel Pentium 4        | 2        | 1.83%   |
| Intel Core 2 Duo       | 2        | 1.83%   |
| AMD Athlon II X2       | 2        | 1.83%   |
| Intel Pentium D        | 1        | 0.92%   |
| Intel Pentium          | 1        | 0.92%   |
| Intel Core 2           | 1        | 0.92%   |
| Intel Celeron          | 1        | 0.92%   |
| AMD Ryzen Threadripper | 1        | 0.92%   |
| AMD Ryzen 3            | 1        | 0.92%   |
| AMD E                  | 1        | 0.92%   |
| AMD Athlon X4          | 1        | 0.92%   |
| AMD Athlon II X4       | 1        | 0.92%   |
| AMD Athlon Dual Core   | 1        | 0.92%   |
| AMD Athlon 64 X2       | 1        | 0.92%   |
| AMD A4                 | 1        | 0.92%   |
| AMD A10                | 1        | 0.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 48       | 44.04%  |
| 2      | 22       | 20.18%  |
| 6      | 14       | 12.84%  |
| 8      | 10       | 9.17%   |
| 16     | 4        | 3.67%   |
| 10     | 4        | 3.67%   |
| 1      | 3        | 2.75%   |
| 12     | 2        | 1.83%   |
| 32     | 1        | 0.92%   |
| 14     | 1        | 0.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 108      | 99.08%  |
| 2      | 1        | 0.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 65       | 59.63%  |
| 1      | 44       | 40.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 108      | 99.08%  |
| 32-bit         | 1        | 0.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 26.61%  |
| 0x306c3    | 12       | 11.01%  |
| 0x206a7    | 7        | 6.42%   |
| 0x306a9    | 6        | 5.5%    |
| 0x906ea    | 4        | 3.67%   |
| 0x506e3    | 4        | 3.67%   |
| 0x08701021 | 4        | 3.67%   |
| 0x0a50000d | 3        | 2.75%   |
| 0x010000c8 | 3        | 2.75%   |
| 0xf41      | 2        | 1.83%   |
| 0xa0655    | 2        | 1.83%   |
| 0x906ed    | 2        | 1.83%   |
| 0x206d7    | 2        | 1.83%   |
| 0x106a5    | 2        | 1.83%   |
| 0x10676    | 2        | 1.83%   |
| 0x010000b6 | 2        | 1.83%   |
| 0xf65      | 1        | 0.92%   |
| 0x906ec    | 1        | 0.92%   |
| 0x906a4    | 1        | 0.92%   |
| 0x90675    | 1        | 0.92%   |
| 0x6f6      | 1        | 0.92%   |
| 0x506ca    | 1        | 0.92%   |
| 0x50654    | 1        | 0.92%   |
| 0x306f2    | 1        | 0.92%   |
| 0x20655    | 1        | 0.92%   |
| 0x20652    | 1        | 0.92%   |
| 0x0a50000c | 1        | 0.92%   |
| 0x0a20120a | 1        | 0.92%   |
| 0x0a201009 | 1        | 0.92%   |
| 0x08701013 | 1        | 0.92%   |
| 0x08301039 | 1        | 0.92%   |
| 0x08108109 | 1        | 0.92%   |
| 0x08101016 | 1        | 0.92%   |
| 0x08001138 | 1        | 0.92%   |
| 0x06003106 | 1        | 0.92%   |
| 0x06001119 | 1        | 0.92%   |
| 0x06000852 | 1        | 0.92%   |
| 0x0600081f | 1        | 0.92%   |
| 0x010000c7 | 1        | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 15       | 13.76%  |
| Zen 2            | 10       | 9.17%   |
| KabyLake         | 10       | 9.17%   |
| Skylake          | 9        | 8.26%   |
| SandyBridge      | 9        | 8.26%   |
| Zen 3            | 7        | 6.42%   |
| IvyBridge        | 7        | 6.42%   |
| K10              | 6        | 5.5%    |
| Piledriver       | 5        | 4.59%   |
| Penryn           | 5        | 4.59%   |
| Alderlake Hybrid | 4        | 3.67%   |
| Westmere         | 3        | 2.75%   |
| NetBurst         | 3        | 2.75%   |
| Zen              | 2        | 1.83%   |
| Nehalem          | 2        | 1.83%   |
| K8 Hammer        | 2        | 1.83%   |
| Core             | 2        | 1.83%   |
| CometLake        | 2        | 1.83%   |
| Zen+             | 1        | 0.92%   |
| Steamroller      | 1        | 0.92%   |
| K10 Llano        | 1        | 0.92%   |
| Goldmont         | 1        | 0.92%   |
| Excavator        | 1        | 0.92%   |
| Unknown          | 1        | 0.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 57       | 46.72%  |
| Intel  | 36       | 29.51%  |
| AMD    | 29       | 23.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 7.14%   |
| Intel HD Graphics 530                                                       | 5        | 3.97%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 3.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 3.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 3.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 3.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.38%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 2.38%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 2.38%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 2.38%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 2.38%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.59%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.59%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 1.59%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 1.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1.59%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2        | 1.59%   |
| Intel HD Graphics 630                                                       | 2        | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.59%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.59%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.59%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 1.59%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.79%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.79%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1        | 0.79%   |
| Nvidia GT216 [GeForce 315]                                                  | 1        | 0.79%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.79%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.79%   |
| Nvidia GK208 [GeForce GT 720]                                               | 1        | 0.79%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 0.79%   |
| Nvidia GK107M [GeForce GT 745M]                                             | 1        | 0.79%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 0.79%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.79%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 0.79%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.79%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 49       | 44.55%  |
| 1 x Intel      | 25       | 22.73%  |
| 1 x AMD        | 25       | 22.73%  |
| Intel + Nvidia | 5        | 4.55%   |
| 2 x Nvidia     | 2        | 1.82%   |
| 2 x AMD        | 2        | 1.82%   |
| AMD + Nvidia   | 2        | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 72       | 65.45%  |
| Proprietary | 38       | 34.55%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 27.03%  |
| 1.01-2.0   | 19       | 17.12%  |
| 0.01-0.5   | 16       | 14.41%  |
| 0.51-1.0   | 13       | 11.71%  |
| 7.01-8.0   | 10       | 9.01%   |
| 3.01-4.0   | 8        | 7.21%   |
| 8.01-16.0  | 8        | 7.21%   |
| 5.01-6.0   | 3        | 2.7%    |
| 16.01-24.0 | 2        | 1.8%    |
| 32.01-64.0 | 1        | 0.9%    |
| 2.01-3.0   | 1        | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 20       | 16.39%  |
| Goldstar             | 13       | 10.66%  |
| Hewlett-Packard      | 12       | 9.84%   |
| Dell                 | 11       | 9.02%   |
| Philips              | 10       | 8.2%    |
| Acer                 | 9        | 7.38%   |
| Ancor Communications | 6        | 4.92%   |
| BenQ                 | 3        | 2.46%   |
| AOC                  | 3        | 2.46%   |
| ViewSonic            | 2        | 1.64%   |
| Unknown              | 2        | 1.64%   |
| Sony                 | 2        | 1.64%   |
| ONN                  | 2        | 1.64%   |
| Hitachi              | 2        | 1.64%   |
| Fujitsu Siemens      | 2        | 1.64%   |
| Eizo                 | 2        | 1.64%   |
| ASUSTek Computer     | 2        | 1.64%   |
| Westinghouse         | 1        | 0.82%   |
| VIE                  | 1        | 0.82%   |
| TVT                  | 1        | 0.82%   |
| TCH                  | 1        | 0.82%   |
| Targa Visionary      | 1        | 0.82%   |
| Seiki                | 1        | 0.82%   |
| Onkyo                | 1        | 0.82%   |
| NEC Computers        | 1        | 0.82%   |
| MSI                  | 1        | 0.82%   |
| Medion               | 1        | 0.82%   |
| LOE                  | 1        | 0.82%   |
| KTC                  | 1        | 0.82%   |
| Iiyama               | 1        | 0.82%   |
| Hyundai ImageQuest   | 1        | 0.82%   |
| Hannspree            | 1        | 0.82%   |
| Gigabyte Technology  | 1        | 0.82%   |
| DENON                | 1        | 0.82%   |
| Apple                | 1        | 0.82%   |
| Unknown              | 1        | 0.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                     | 2        | 1.48%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 2        | 1.48%   |
| Westinghouse SK-26H730S WDE15CC 1366x768 575x323mm 26.0-inch            | 1        | 0.74%   |
| ViewSonic VX2758-C-MH VSC35DD 1920x1080 597x336mm 27.0-inch             | 1        | 0.74%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch              | 1        | 0.74%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                   | 1        | 0.74%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                   | 1        | 0.74%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1        | 0.74%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                          | 1        | 0.74%   |
| TCH HDMI TCH5600 1920x1080 344x194mm 15.5-inch                          | 1        | 0.74%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch     | 1        | 0.74%   |
| Sony TV SNYEA01 1920x1080                                               | 1        | 0.74%   |
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                     | 1        | 0.74%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                     | 1        | 0.74%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1        | 0.74%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1        | 0.74%   |
| Samsung Electronics T22D390 SAM0B6B 1920x1080 477x268mm 21.5-inch       | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch    | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM0484 1920x1080 520x320mm 24.0-inch    | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch    | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch     | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch    | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch    | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch    | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch    | 1        | 0.74%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch    | 1        | 0.74%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch     | 1        | 0.74%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch     | 1        | 0.74%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch      | 1        | 0.74%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch       | 1        | 0.74%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch    | 1        | 0.74%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 598x336mm 27.0-inch       | 1        | 0.74%   |
| Samsung Electronics S27D590C SAM0BEA 1920x1080 598x336mm 27.0-inch      | 1        | 0.74%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.74%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch       | 1        | 0.74%   |
| Samsung Electronics LCD Monitor SyncMaster                              | 1        | 0.74%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 0.74%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch    | 1        | 0.74%   |
| Samsung Electronics LCD Monitor S34J55x 3440x1440                       | 1        | 0.74%   |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch       | 1        | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 58       | 48.33%  |
| 3840x2160 (4K)     | 12       | 10%     |
| 1280x1024 (SXGA)   | 11       | 9.17%   |
| 1680x1050 (WSXGA+) | 8        | 6.67%   |
| 2560x1440 (QHD)    | 5        | 4.17%   |
| 1920x1200 (WUXGA)  | 5        | 4.17%   |
| 1366x768 (WXGA)    | 4        | 3.33%   |
| 1440x900 (WXGA+)   | 3        | 2.5%    |
| 1600x900 (HD+)     | 2        | 1.67%   |
| 1360x768           | 2        | 1.67%   |
| Unknown            | 2        | 1.67%   |
| 5760x2160          | 1        | 0.83%   |
| 3440x1440          | 1        | 0.83%   |
| 3280x1080          | 1        | 0.83%   |
| 2288x1287          | 1        | 0.83%   |
| 1920x540           | 1        | 0.83%   |
| 1600x1200          | 1        | 0.83%   |
| 1400x1050          | 1        | 0.83%   |
| 1024x768 (XGA)     | 1        | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 17       | 13.93%  |
| 23      | 17       | 13.93%  |
| 21      | 17       | 13.93%  |
| 24      | 16       | 13.11%  |
| 31      | 9        | 7.38%   |
| 22      | 8        | 6.56%   |
| 19      | 7        | 5.74%   |
| 17      | 6        | 4.92%   |
| 18      | 4        | 3.28%   |
| 84      | 3        | 2.46%   |
| 20      | 3        | 2.46%   |
| Unknown | 3        | 2.46%   |
| 32      | 2        | 1.64%   |
| 15      | 2        | 1.64%   |
| 142     | 1        | 0.82%   |
| 72      | 1        | 0.82%   |
| 65      | 1        | 0.82%   |
| 52      | 1        | 0.82%   |
| 50      | 1        | 0.82%   |
| 43      | 1        | 0.82%   |
| 26      | 1        | 0.82%   |
| 16      | 1        | 0.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 46       | 39.32%  |
| 401-500        | 33       | 28.21%  |
| 601-700        | 11       | 9.4%    |
| 301-350        | 9        | 7.69%   |
| 351-400        | 4        | 3.42%   |
| 1501-2000      | 4        | 3.42%   |
| 1001-1500      | 3        | 2.56%   |
| Unknown        | 3        | 2.56%   |
| 701-800        | 2        | 1.71%   |
| More than 2000 | 1        | 0.85%   |
| 901-1000       | 1        | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 76       | 68.47%  |
| 16/10   | 18       | 16.22%  |
| 5/4     | 9        | 8.11%   |
| Unknown | 3        | 2.7%    |
| 4/3     | 2        | 1.8%    |
| 6/5     | 1        | 0.9%    |
| 3/2     | 1        | 0.9%    |
| 1.00    | 1        | 0.9%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 48       | 40.34%  |
| 301-350        | 17       | 14.29%  |
| 351-500        | 11       | 9.24%   |
| 151-200        | 11       | 9.24%   |
| 141-150        | 10       | 8.4%    |
| More than 1000 | 8        | 6.72%   |
| 251-300        | 7        | 5.88%   |
| Unknown        | 3        | 2.52%   |
| 131-140        | 1        | 0.84%   |
| 111-120        | 1        | 0.84%   |
| 101-110        | 1        | 0.84%   |
| 501-1000       | 1        | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 77       | 69.37%  |
| 101-120 | 22       | 19.82%  |
| 1-50    | 4        | 3.6%    |
| 121-160 | 4        | 3.6%    |
| Unknown | 3        | 2.7%    |
| 161-240 | 1        | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 76       | 69.72%  |
| 2     | 32       | 29.36%  |
| 3     | 1        | 0.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 58       | 36.71%  |
| Intel                           | 52       | 32.91%  |
| Qualcomm Atheros                | 14       | 8.86%   |
| Broadcom                        | 7        | 4.43%   |
| TP-Link                         | 4        | 2.53%   |
| Nvidia                          | 3        | 1.9%    |
| MediaTek                        | 3        | 1.9%    |
| Ralink Technology               | 2        | 1.27%   |
| Qualcomm Atheros Communications | 2        | 1.27%   |
| Broadcom Limited                | 2        | 1.27%   |
| Aquantia                        | 2        | 1.27%   |
| ZyDAS                           | 1        | 0.63%   |
| Wacom                           | 1        | 0.63%   |
| NetGear                         | 1        | 0.63%   |
| Microsoft                       | 1        | 0.63%   |
| Marvell Technology Group        | 1        | 0.63%   |
| InterBiometrics                 | 1        | 0.63%   |
| Input Club                      | 1        | 0.63%   |
| ASUSTek Computer                | 1        | 0.63%   |
| ASIX Electronics                | 1        | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 49       | 27.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10       | 5.59%   |
| Intel I211 Gigabit Network Connection                                          | 7        | 3.91%   |
| Intel Ethernet Controller I225-V                                               | 5        | 2.79%   |
| Intel Ethernet Connection I217-LM                                              | 5        | 2.79%   |
| Intel Ethernet Connection (2) I219-V                                           | 5        | 2.79%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 4        | 2.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3        | 1.68%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 3        | 1.68%   |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 1.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 2        | 1.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 2        | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2        | 1.12%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2        | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 1.12%   |
| Realtek 802.11ac NIC                                                           | 2        | 1.12%   |
| Qualcomm Atheros AR9271 802.11n                                                | 2        | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2        | 1.12%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 2        | 1.12%   |
| Nvidia MCP77 Ethernet                                                          | 2        | 1.12%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 2        | 1.12%   |
| Intel Wireless 3165                                                            | 2        | 1.12%   |
| Intel Ethernet Connection I217-V                                               | 2        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 2        | 1.12%   |
| Intel 82574L Gigabit Network Connection                                        | 2        | 1.12%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 1.12%   |
| ZyDAS ZD1211B 802.11g                                                          | 1        | 0.56%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                       | 1        | 0.56%   |
| TP-Link 802.11ac WLAN Adapter                                                  | 1        | 0.56%   |
| TP-Link 802.11ac NIC                                                           | 1        | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                | 1        | 0.56%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                        | 1        | 0.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 0.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.56%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1        | 0.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.56%   |
| Realtek 802.11ax WLAN Adapter                                                  | 1        | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                                | 1        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 26.79%  |
| Realtek Semiconductor           | 12       | 21.43%  |
| Qualcomm Atheros                | 9        | 16.07%  |
| TP-Link                         | 4        | 7.14%   |
| Broadcom                        | 4        | 7.14%   |
| MediaTek                        | 3        | 5.36%   |
| Ralink Technology               | 2        | 3.57%   |
| Qualcomm Atheros Communications | 2        | 3.57%   |
| ZyDAS                           | 1        | 1.79%   |
| Wacom                           | 1        | 1.79%   |
| NetGear                         | 1        | 1.79%   |
| Microsoft                       | 1        | 1.79%   |
| ASUSTek Computer                | 1        | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 4        | 7.14%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 3        | 5.36%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2        | 3.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2        | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 3.57%   |
| Realtek 802.11ac NIC                                                          | 2        | 3.57%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 3.57%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2        | 3.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 3.57%   |
| Intel Wireless 3165                                                           | 2        | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 3.57%   |
| ZyDAS ZD1211B 802.11g                                                         | 1        | 1.79%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1        | 1.79%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 1.79%   |
| TP-Link 802.11ac NIC                                                          | 1        | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 1.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 1.79%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1        | 1.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 1.79%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 1.79%   |
| Realtek 802.11ax WLAN Adapter                                                 | 1        | 1.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 1.79%   |
| Ralink MT7601U Wireless Adapter                                               | 1        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 1.79%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 1.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 1.79%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 1.79%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 1.79%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                   | 1        | 1.79%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 1.79%   |
| MediaTek 802.11 n WLAN                                                        | 1        | 1.79%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 1.79%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 1.79%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                             | 1        | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 1.79%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                            | 1        | 1.79%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 1        | 1.79%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                  | 1        | 1.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 1        | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 54       | 45.76%  |
| Intel                    | 47       | 39.83%  |
| Qualcomm Atheros         | 5        | 4.24%   |
| Nvidia                   | 3        | 2.54%   |
| Broadcom                 | 3        | 2.54%   |
| Broadcom Limited         | 2        | 1.69%   |
| Aquantia                 | 2        | 1.69%   |
| Marvell Technology Group | 1        | 0.85%   |
| ASIX Electronics         | 1        | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 49       | 40.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10       | 8.26%   |
| Intel I211 Gigabit Network Connection                                          | 7        | 5.79%   |
| Intel Ethernet Controller I225-V                                               | 5        | 4.13%   |
| Intel Ethernet Connection I217-LM                                              | 5        | 4.13%   |
| Intel Ethernet Connection (2) I219-V                                           | 5        | 4.13%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3        | 2.48%   |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 2.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2        | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 1.65%   |
| Nvidia MCP77 Ethernet                                                          | 2        | 1.65%   |
| Intel Ethernet Connection I217-V                                               | 2        | 1.65%   |
| Intel 82574L Gigabit Network Connection                                        | 2        | 1.65%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 1.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.83%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1        | 0.83%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1        | 0.83%   |
| Nvidia MCP61 Ethernet                                                          | 1        | 0.83%   |
| Marvell Group 88E8052 PCI-E ASF Gigabit Ethernet Controller                    | 1        | 0.83%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1        | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.83%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 0.83%   |
| Intel Ethernet Connection (2) I218-V                                           | 1        | 0.83%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1        | 0.83%   |
| Intel 82579V Gigabit Network Connection                                        | 1        | 0.83%   |
| Intel 82578DM Gigabit Network Connection                                       | 1        | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1        | 0.83%   |
| Intel 82566DM Gigabit Network Connection                                       | 1        | 0.83%   |
| Intel 82562EZ 10/100 Ethernet Controller                                       | 1        | 0.83%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1        | 0.83%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 1        | 0.83%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                        | 1        | 0.83%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 0.83%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1        | 0.83%   |
| ASIX AX88772B                                                                  | 1        | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 108      | 67.08%  |
| WiFi     | 51       | 31.68%  |
| Modem    | 2        | 1.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 95       | 79.83%  |
| WiFi     | 24       | 20.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 66       | 60.55%  |
| 2     | 38       | 34.86%  |
| 3     | 4        | 3.67%   |
| 0     | 1        | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 89       | 80.91%  |
| Yes  | 21       | 19.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 39.47%  |
| Cambridge Silicon Radio         | 7        | 18.42%  |
| Realtek Semiconductor           | 4        | 10.53%  |
| MediaTek                        | 3        | 7.89%   |
| ASUSTek Computer                | 3        | 7.89%   |
| Qualcomm Atheros Communications | 2        | 5.26%   |
| Broadcom                        | 2        | 5.26%   |
| TP-Link                         | 1        | 2.63%   |
| IMC Networks                    | 1        | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 18.42%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 10.53%  |
| Realtek Bluetooth Radio                             | 3        | 7.89%   |
| MediaTek Wireless_Device                            | 3        | 7.89%   |
| Intel Bluetooth wireless interface                  | 3        | 7.89%   |
| Intel AX210 Bluetooth                               | 3        | 7.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 5.26%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 5.26%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 1        | 2.63%   |
| Realtek 802.11ac WLAN Adapter                       | 1        | 2.63%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 2.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 2.63%   |
| Intel AX211 Bluetooth                               | 1        | 2.63%   |
| Intel AX200 Bluetooth                               | 1        | 2.63%   |
| IMC Networks Bluetooth Radio                        | 1        | 2.63%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 2.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 2.63%   |
| ASUS BCM20702A0                                     | 1        | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 66       | 29.73%  |
| Nvidia                               | 49       | 22.07%  |
| AMD                                  | 43       | 19.37%  |
| C-Media Electronics                  | 6        | 2.7%    |
| Yamaha                               | 4        | 1.8%    |
| Texas Instruments                    | 4        | 1.8%    |
| M-Audio                              | 4        | 1.8%    |
| JMTek                                | 4        | 1.8%    |
| PreSonus Audio Electronics           | 3        | 1.35%   |
| Logitech                             | 3        | 1.35%   |
| Focusrite-Novation                   | 3        | 1.35%   |
| Plantronics                          | 2        | 0.9%    |
| ASUSTek Computer                     | 2        | 0.9%    |
| ZOOM                                 | 1        | 0.45%   |
| Xilinx                               | 1        | 0.45%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.45%   |
| Textech International                | 1        | 0.45%   |
| Tenx Technology                      | 1        | 0.45%   |
| TEAC                                 | 1        | 0.45%   |
| Studiologic                          | 1        | 0.45%   |
| SteelSeries ApS                      | 1        | 0.45%   |
| Samson Technologies                  | 1        | 0.45%   |
| Razer USA                            | 1        | 0.45%   |
| QinHeng Electronics                  | 1        | 0.45%   |
| MIDITECH                             | 1        | 0.45%   |
| Medeli Electronics                   | 1        | 0.45%   |
| Mark of the Unicorn                  | 1        | 0.45%   |
| KTMicro                              | 1        | 0.45%   |
| Harman                               | 1        | 0.45%   |
| Generalplus Technology               | 1        | 0.45%   |
| Evolution Electronics                | 1        | 0.45%   |
| ESI Audiotechnik                     | 1        | 0.45%   |
| Ensoniq                              | 1        | 0.45%   |
| Elektron Music Machines              | 1        | 0.45%   |
| Creative Technology                  | 1        | 0.45%   |
| Creative Labs                        | 1        | 0.45%   |
| CME (Central Music)                  | 1        | 0.45%   |
| BEHRINGER International              | 1        | 0.45%   |
| Audient                              | 1        | 0.45%   |
| Apple                                | 1        | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12       | 4.74%   |
| AMD Starship/Matisse HD Audio Controller                                          | 11       | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9        | 3.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 8        | 3.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8        | 3.16%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 7        | 2.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 2.37%   |
| Intel Cannon Lake PCH cAVS                                                        | 6        | 2.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6        | 2.37%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 1.98%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 5        | 1.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 5        | 1.98%   |
| Nvidia GP108 High Definition Audio Controller                                     | 4        | 1.58%   |
| Nvidia GA106 High Definition Audio Controller                                     | 4        | 1.58%   |
| Nvidia GA102 High Definition Audio Controller                                     | 4        | 1.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4        | 1.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 1.58%   |
| AMD FCH Azalia Controller                                                         | 4        | 1.58%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3        | 1.19%   |
| PreSonus Audio Electronics Studio 24c                                             | 3        | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 1.19%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3        | 1.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 1.19%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 1.19%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 1.19%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.19%   |
| Yamaha AG06/AG03                                                                  | 2        | 0.79%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 0.79%   |
| Nvidia High Definition Audio Controller                                           | 2        | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.79%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 0.79%   |
| M-Audio M-Track                                                                   | 2        | 0.79%   |
| JMTek USB PnP Audio Device                                                        | 2        | 0.79%   |
| Intel Raptor Lake High Definition Audio Controller                                | 2        | 0.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 0.79%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 2        | 0.79%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 2        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 19       | 14.5%   |
| Unknown             | 18       | 13.74%  |
| SK hynix            | 17       | 12.98%  |
| Samsung Electronics | 15       | 11.45%  |
| Corsair             | 14       | 10.69%  |
| Crucial             | 12       | 9.16%   |
| G.Skill             | 9        | 6.87%   |
| Micron Technology   | 6        | 4.58%   |
| Patriot             | 4        | 3.05%   |
| A-DATA Technology   | 2        | 1.53%   |
| Unknown             | 2        | 1.53%   |
| Unifosa             | 1        | 0.76%   |
| Smart               | 1        | 0.76%   |
| S                   | 1        | 0.76%   |
| PNY                 | 1        | 0.76%   |
| OCZ                 | 1        | 0.76%   |
| Nanya Technology    | 1        | 0.76%   |
| M                   | 1        | 0.76%   |
| HBS                 | 1        | 0.76%   |
| Goldkey             | 1        | 0.76%   |
| Elpida              | 1        | 0.76%   |
| Avant               | 1        | 0.76%   |
| Aeneon              | 1        | 0.76%   |
| 0194808980CE        | 1        | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s         | 3        | 2.04%   |
| Patriot RAM 3200 C16 Series 4GB DIMM DDR4 3600MT/s          | 3        | 2.04%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 3        | 2.04%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                     | 2        | 1.36%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 2        | 1.36%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                    | 2        | 1.36%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s        | 2        | 1.36%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s      | 2        | 1.36%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s              | 2        | 1.36%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s       | 2        | 1.36%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s      | 2        | 1.36%   |
| Unknown                                                     | 2        | 1.36%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                        | 1        | 0.68%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1        | 0.68%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                   | 1        | 0.68%   |
| Unknown RAM Module 512MB DIMM DDR                           | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM SDRAM                           | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s                    | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM 400MT/s                         | 1        | 0.68%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2                            | 1        | 0.68%   |
| Unknown RAM Module 256MB DIMM DDR                           | 1        | 0.68%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1        | 0.68%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1        | 0.68%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                    | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR                          | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1        | 0.68%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s                 | 1        | 0.68%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s           | 1        | 0.68%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s          | 1        | 0.68%   |
| SK hynix RAM TMT41GU6BFR8C-PBSC 8192MB DIMM DDR3 1600MT/s   | 1        | 0.68%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 0.68%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2666MT/s               | 1        | 0.68%   |
| SK hynix RAM Module 32GB DIMM DDR4 2667MT/s                 | 1        | 0.68%   |
| SK hynix RAM HYMP564U64BP8-C4 512MB DIMM DDR 533MT/s        | 1        | 0.68%   |
| SK hynix RAM HYMP125F72CP8N3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.68%   |
| SK hynix RAM HYMP125F72CP8D3-Y5 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 1        | 0.68%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s        | 1        | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 42       | 37.5%   |
| DDR3    | 42       | 37.5%   |
| DDR2    | 11       | 9.82%   |
| Unknown | 8        | 7.14%   |
| SDRAM   | 3        | 2.68%   |
| DDR5    | 3        | 2.68%   |
| DDR     | 3        | 2.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 99       | 90%     |
| SODIMM  | 9        | 8.18%   |
| RIMM    | 1        | 0.91%   |
| FB-DIMM | 1        | 0.91%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 35       | 28.46%  |
| 4096  | 32       | 26.02%  |
| 16384 | 17       | 13.82%  |
| 2048  | 16       | 13.01%  |
| 32768 | 12       | 9.76%   |
| 1024  | 8        | 6.5%    |
| 512   | 2        | 1.63%   |
| 256   | 1        | 0.81%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 20.8%   |
| 3600    | 11       | 8.8%    |
| 1333    | 11       | 8.8%    |
| 3200    | 6        | 4.8%    |
| 2133    | 6        | 4.8%    |
| 1866    | 6        | 4.8%    |
| 2400    | 5        | 4%      |
| 800     | 5        | 4%      |
| 667     | 5        | 4%      |
| 1800    | 4        | 3.2%    |
| 1066    | 4        | 3.2%    |
| Unknown | 4        | 3.2%    |
| 2933    | 3        | 2.4%    |
| 2667    | 3        | 2.4%    |
| 1867    | 3        | 2.4%    |
| 3400    | 2        | 1.6%    |
| 2666    | 2        | 1.6%    |
| 533     | 2        | 1.6%    |
| 7200    | 1        | 0.8%    |
| 5600    | 1        | 0.8%    |
| 4802    | 1        | 0.8%    |
| 3866    | 1        | 0.8%    |
| 3800    | 1        | 0.8%    |
| 3733    | 1        | 0.8%    |
| 3500    | 1        | 0.8%    |
| 3467    | 1        | 0.8%    |
| 3466    | 1        | 0.8%    |
| 3266    | 1        | 0.8%    |
| 3000    | 1        | 0.8%    |
| 2934    | 1        | 0.8%    |
| 2800    | 1        | 0.8%    |
| 2465    | 1        | 0.8%    |
| 1632    | 1        | 0.8%    |
| 1067    | 1        | 0.8%    |
| 400     | 1        | 0.8%    |

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
| Logitech                      | 9        | 30%     |
| Samsung Electronics           | 2        | 6.67%   |
| Microsoft                     | 2        | 6.67%   |
| Microdia                      | 2        | 6.67%   |
| Xiongmai                      | 1        | 3.33%   |
| ViewSonic                     | 1        | 3.33%   |
| Trust                         | 1        | 3.33%   |
| Sweex                         | 1        | 3.33%   |
| Sunplus IT                    | 1        | 3.33%   |
| Sunplus Innovation Technology | 1        | 3.33%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 3.33%   |
| Philips (or NXP)              | 1        | 3.33%   |
| OmniVision Technologies       | 1        | 3.33%   |
| MacroSilicon                  | 1        | 3.33%   |
| Jieli Technology              | 1        | 3.33%   |
| Intel                         | 1        | 3.33%   |
| Huawei Technologies           | 1        | 3.33%   |
| Generalplus Technology        | 1        | 3.33%   |
| Chicony Electronics           | 1        | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 3        | 10%     |
| Samsung Galaxy series, misc. (MTP mode)           | 2        | 6.67%   |
| Xiongmai web camera                               | 1        | 3.33%   |
| ViewSonic PC Camera                               | 1        | 3.33%   |
| Trust Canyon CNS-CWC6 Webcam                      | 1        | 3.33%   |
| Sweex WC060 Series HD Webcam                      | 1        | 3.33%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 1        | 3.33%   |
| Sunplus HD 720P webcam                            | 1        | 3.33%   |
| SHENZHEN AONI ELECTRONIC NexiGo N930AF FHD Webcam | 1        | 3.33%   |
| Philips (or NXP) Webcam SPC530NC                  | 1        | 3.33%   |
| OmniVision USB Camera-OV580                       | 1        | 3.33%   |
| Microsoft LifeCam VX-5000                         | 1        | 3.33%   |
| Microsoft LifeCam Cinema                          | 1        | 3.33%   |
| Microdia USB 2.0 Camera                           | 1        | 3.33%   |
| Microdia MSI Starcam Racer                        | 1        | 3.33%   |
| MacroSilicon USB Video                            | 1        | 3.33%   |
| Logitech QuickCam Communicate MP/S5500            | 1        | 3.33%   |
| Logitech Portable Webcam C905                     | 1        | 3.33%   |
| Logitech Logitech Webcam C925e                    | 1        | 3.33%   |
| Logitech HD Webcam C910                           | 1        | 3.33%   |
| Logitech HD Webcam C510                           | 1        | 3.33%   |
| Logitech HD Pro Webcam C920                       | 1        | 3.33%   |
| Jieli USB PHY 2.0                                 | 1        | 3.33%   |
| Intel RealSense 3D Camera (Front F200)            | 1        | 3.33%   |
| Huawei HiCamera                                   | 1        | 3.33%   |
| Generalplus GENERAL WEBCAM                        | 1        | 3.33%   |
| Chicony HP High Definition 1MP Webcam             | 1        | 3.33%   |

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
| 0     | 93       | 84.55%  |
| 1     | 15       | 13.64%  |
| 2     | 2        | 1.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 8        | 42.11%  |
| Graphics card            | 3        | 15.79%  |
| Sound                    | 2        | 10.53%  |
| Multimedia controller    | 2        | 10.53%  |
| Unassigned class         | 1        | 5.26%   |
| Net/ethernet             | 1        | 5.26%   |
| Modem                    | 1        | 5.26%   |
| Communication controller | 1        | 5.26%   |

