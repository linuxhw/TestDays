Linux in Colombia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Colombia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Colombia/Desktop/README.md) and [notebooks](/Location/Colombia/Notebook/README.md).

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

Total: 2049

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | G40-30 80FY                 | Notebook    | [398cb6b840](https://linux-hardware.org/?probe=398cb6b840) | Jan 06, 2025 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3b12d86f3d](https://linux-hardware.org/?probe=3b12d86f3d) | Dec 31, 2024 |
| Dell          | Vostro 3420                 | Notebook    | [d5a414f6d5](https://linux-hardware.org/?probe=d5a414f6d5) | Dec 30, 2024 |
| HP            | 1497                        | Desktop     | [256c3def88](https://linux-hardware.org/?probe=256c3def88) | Dec 29, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [5c7c3a9849](https://linux-hardware.org/?probe=5c7c3a9849) | Dec 19, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [9365cddb5a](https://linux-hardware.org/?probe=9365cddb5a) | Dec 19, 2024 |
| Unknown       | Unknown                     | Notebook    | [a1f0651a5b](https://linux-hardware.org/?probe=a1f0651a5b) | Dec 18, 2024 |
| Unknown       | Unknown                     | Notebook    | [f149e767ce](https://linux-hardware.org/?probe=f149e767ce) | Dec 18, 2024 |
| Lenovo        | G580 2189                   | Notebook    | [661f3fb17a](https://linux-hardware.org/?probe=661f3fb17a) | Dec 15, 2024 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [8dda7ef237](https://linux-hardware.org/?probe=8dda7ef237) | Dec 12, 2024 |
| JGINYUE       | X99 TITANIUM D3             | Desktop     | [bb9134a8a6](https://linux-hardware.org/?probe=bb9134a8a6) | Dec 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [02a4e78e26](https://linux-hardware.org/?probe=02a4e78e26) | Dec 11, 2024 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [275b70a9b3](https://linux-hardware.org/?probe=275b70a9b3) | Dec 09, 2024 |
| ASUSTek       | X441NA                      | Notebook    | [a093d05841](https://linux-hardware.org/?probe=a093d05841) | Dec 08, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [22bfeaf18d](https://linux-hardware.org/?probe=22bfeaf18d) | Dec 08, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [424cad5338](https://linux-hardware.org/?probe=424cad5338) | Dec 07, 2024 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [422c8408b1](https://linux-hardware.org/?probe=422c8408b1) | Dec 07, 2024 |
| HP            | 3398                        | Desktop     | [3be901c90e](https://linux-hardware.org/?probe=3be901c90e) | Dec 06, 2024 |
| HP            | ProBook 440 14 inch G10 ... | Notebook    | [d0e114834e](https://linux-hardware.org/?probe=d0e114834e) | Dec 04, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [0b71bb31ea](https://linux-hardware.org/?probe=0b71bb31ea) | Dec 03, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [f02fe6c8da](https://linux-hardware.org/?probe=f02fe6c8da) | Dec 03, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [f9aa503983](https://linux-hardware.org/?probe=f9aa503983) | Dec 03, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cb0e4decea](https://linux-hardware.org/?probe=cb0e4decea) | Dec 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [acc5619ba9](https://linux-hardware.org/?probe=acc5619ba9) | Nov 28, 2024 |
| HP            | 8374 1100                   | All in one  | [9fe1f0456a](https://linux-hardware.org/?probe=9fe1f0456a) | Nov 27, 2024 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [acfddbe112](https://linux-hardware.org/?probe=acfddbe112) | Nov 27, 2024 |
| Acer          | Nitro AN515-53              | Notebook    | [b0da0c19f6](https://linux-hardware.org/?probe=b0da0c19f6) | Nov 23, 2024 |
| Gigabyte      | H97M-DS3P                   | Desktop     | [0d1e9eec2d](https://linux-hardware.org/?probe=0d1e9eec2d) | Nov 20, 2024 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [64c284bbb0](https://linux-hardware.org/?probe=64c284bbb0) | Nov 18, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [70aebceb5e](https://linux-hardware.org/?probe=70aebceb5e) | Nov 18, 2024 |
| Dell          | Latitude 7490               | Notebook    | [7199d706be](https://linux-hardware.org/?probe=7199d706be) | Nov 17, 2024 |
| Dell          | Latitude 7490               | Notebook    | [41be043794](https://linux-hardware.org/?probe=41be043794) | Nov 17, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1e4f8fa6f5](https://linux-hardware.org/?probe=1e4f8fa6f5) | Nov 16, 2024 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [2f5cd15407](https://linux-hardware.org/?probe=2f5cd15407) | Nov 14, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [3439677f78](https://linux-hardware.org/?probe=3439677f78) | Nov 14, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [60639f7365](https://linux-hardware.org/?probe=60639f7365) | Nov 14, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [d3d7f3e562](https://linux-hardware.org/?probe=d3d7f3e562) | Nov 12, 2024 |
| Toshiba       | PORTEGE Z930                | Notebook    | [722e3a5231](https://linux-hardware.org/?probe=722e3a5231) | Nov 12, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [5d1b0d2964](https://linux-hardware.org/?probe=5d1b0d2964) | Nov 12, 2024 |
| HP            | Pavilion g4                 | Notebook    | [2f7cb31cab](https://linux-hardware.org/?probe=2f7cb31cab) | Nov 06, 2024 |
| Acer          | Aspire AL14-51M             | Notebook    | [8ff6a7a1cd](https://linux-hardware.org/?probe=8ff6a7a1cd) | Nov 05, 2024 |
| Acer          | Aspire AL14-51M             | Notebook    | [50b858616d](https://linux-hardware.org/?probe=50b858616d) | Nov 05, 2024 |
| h             | Unknown                     | Notebook    | [890d21f9de](https://linux-hardware.org/?probe=890d21f9de) | Nov 04, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [4cf37031b7](https://linux-hardware.org/?probe=4cf37031b7) | Nov 03, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [22176b1e5e](https://linux-hardware.org/?probe=22176b1e5e) | Oct 31, 2024 |
| Lenovo        | 36E0 SDK0J40688 WIN 3424... | All in one  | [f781facd17](https://linux-hardware.org/?probe=f781facd17) | Oct 31, 2024 |
| Toshiba       | Satellite L845              | Notebook    | [7e634d4ee6](https://linux-hardware.org/?probe=7e634d4ee6) | Oct 27, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [4ab4fd20bc](https://linux-hardware.org/?probe=4ab4fd20bc) | Oct 26, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [7b016cc848](https://linux-hardware.org/?probe=7b016cc848) | Oct 26, 2024 |
| MSI           | MPG B550I GAMING EDGE MA... | Desktop     | [62bd667a99](https://linux-hardware.org/?probe=62bd667a99) | Oct 26, 2024 |
| HP            | 2B2F MVB,A                  | All in one  | [006b770f80](https://linux-hardware.org/?probe=006b770f80) | Oct 26, 2024 |
| Acer          | Aspire A514-53              | Notebook    | [f2045607ab](https://linux-hardware.org/?probe=f2045607ab) | Oct 24, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [a898b84b4e](https://linux-hardware.org/?probe=a898b84b4e) | Oct 24, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [9dc1b13a4c](https://linux-hardware.org/?probe=9dc1b13a4c) | Oct 22, 2024 |
| HP            | Pavilion g4                 | Notebook    | [2aef3c978b](https://linux-hardware.org/?probe=2aef3c978b) | Oct 21, 2024 |
| HP            | Pavilion g4                 | Notebook    | [c677956f41](https://linux-hardware.org/?probe=c677956f41) | Oct 21, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [26bd161f46](https://linux-hardware.org/?probe=26bd161f46) | Oct 21, 2024 |
| Quanta        | 2AC7 011                    | Desktop     | [36d655acf6](https://linux-hardware.org/?probe=36d655acf6) | Oct 16, 2024 |
| HUAWEI        | KPL-W0X                     | Notebook    | [bf9c1c8578](https://linux-hardware.org/?probe=bf9c1c8578) | Oct 14, 2024 |
| Dell          | Latitude E6430              | Notebook    | [bdebcd33a6](https://linux-hardware.org/?probe=bdebcd33a6) | Oct 12, 2024 |
| Intel         | H81                         | Desktop     | [6a28d6befb](https://linux-hardware.org/?probe=6a28d6befb) | Oct 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [30e368c030](https://linux-hardware.org/?probe=30e368c030) | Oct 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [a6c3210fa6](https://linux-hardware.org/?probe=a6c3210fa6) | Oct 08, 2024 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [dd98315fff](https://linux-hardware.org/?probe=dd98315fff) | Oct 07, 2024 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [5af38c50d6](https://linux-hardware.org/?probe=5af38c50d6) | Oct 07, 2024 |
| MSI           | B150A GAMING PRO            | Desktop     | [4d5f7679d0](https://linux-hardware.org/?probe=4d5f7679d0) | Oct 06, 2024 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [37e187d1c9](https://linux-hardware.org/?probe=37e187d1c9) | Oct 06, 2024 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [a8c1a124a9](https://linux-hardware.org/?probe=a8c1a124a9) | Oct 06, 2024 |
| Acer          | Aspire 4738                 | Notebook    | [d7bd115a64](https://linux-hardware.org/?probe=d7bd115a64) | Oct 05, 2024 |
| HP            | 430                         | Notebook    | [361d07ebd0](https://linux-hardware.org/?probe=361d07ebd0) | Oct 04, 2024 |
| Compumax C... | AMD Ryzen 5000U             | Desktop     | [9f694c0c87](https://linux-hardware.org/?probe=9f694c0c87) | Oct 02, 2024 |
| Dell          | 0PM2CW A00                  | Server      | [1e51138d9b](https://linux-hardware.org/?probe=1e51138d9b) | Oct 02, 2024 |
| ECS           | H61H2-MV                    | Desktop     | [29d29072da](https://linux-hardware.org/?probe=29d29072da) | Oct 01, 2024 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | Notebook    | [2c916dede8](https://linux-hardware.org/?probe=2c916dede8) | Sep 30, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ba8072bee4](https://linux-hardware.org/?probe=ba8072bee4) | Sep 29, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [d6ed4a9deb](https://linux-hardware.org/?probe=d6ed4a9deb) | Sep 29, 2024 |
| MSI           | H81M-E33                    | Desktop     | [358f1f3405](https://linux-hardware.org/?probe=358f1f3405) | Sep 28, 2024 |
| ASUSTek       | B150 PRO GAMING D3          | Desktop     | [9342e97a46](https://linux-hardware.org/?probe=9342e97a46) | Sep 28, 2024 |
| Dell          | Latitude 7490               | Notebook    | [bb2ef7aeaa](https://linux-hardware.org/?probe=bb2ef7aeaa) | Sep 28, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [2b248e2664](https://linux-hardware.org/?probe=2b248e2664) | Sep 28, 2024 |
| Acer          | Aspire A314-22              | Notebook    | [83988eaa09](https://linux-hardware.org/?probe=83988eaa09) | Sep 27, 2024 |
| Dell          | Latitude E5420              | Notebook    | [86ca4e5044](https://linux-hardware.org/?probe=86ca4e5044) | Sep 22, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [7fb7c1c4aa](https://linux-hardware.org/?probe=7fb7c1c4aa) | Sep 21, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [a365378bd0](https://linux-hardware.org/?probe=a365378bd0) | Sep 20, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [3cc7205695](https://linux-hardware.org/?probe=3cc7205695) | Sep 20, 2024 |
| ASUSTek       | M4A79T Deluxe               | Desktop     | [cef2225be4](https://linux-hardware.org/?probe=cef2225be4) | Sep 19, 2024 |
| MSI           | PRO H510M-B                 | Desktop     | [020620e4c2](https://linux-hardware.org/?probe=020620e4c2) | Sep 18, 2024 |
| MSI           | PRO H510M-B                 | Desktop     | [892b66d32f](https://linux-hardware.org/?probe=892b66d32f) | Sep 18, 2024 |
| MSI           | H81M-E33                    | Desktop     | [c91a805424](https://linux-hardware.org/?probe=c91a805424) | Sep 18, 2024 |
| HP            | 245 G7                      | Notebook    | [479ad2d2d8](https://linux-hardware.org/?probe=479ad2d2d8) | Sep 14, 2024 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [fef809274c](https://linux-hardware.org/?probe=fef809274c) | Sep 12, 2024 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [4a71430939](https://linux-hardware.org/?probe=4a71430939) | Sep 12, 2024 |
| Intel         | H61                         | Desktop     | [26ad2a6fdf](https://linux-hardware.org/?probe=26ad2a6fdf) | Sep 10, 2024 |
| HP            | Notebook                    | Notebook    | [7392bbfc0f](https://linux-hardware.org/?probe=7392bbfc0f) | Sep 09, 2024 |
| Acer          | Predator PT315-53           | Notebook    | [2d1010c782](https://linux-hardware.org/?probe=2d1010c782) | Sep 07, 2024 |
| Foxconn       | G31MV/G31MV-K FAB           | Desktop     | [cdd64926ef](https://linux-hardware.org/?probe=cdd64926ef) | Sep 06, 2024 |
| HP            | ProBook 650 G4              | Notebook    | [e8edfbf65e](https://linux-hardware.org/?probe=e8edfbf65e) | Sep 05, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8fe595fe5f](https://linux-hardware.org/?probe=8fe595fe5f) | Sep 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [60a1900f85](https://linux-hardware.org/?probe=60a1900f85) | Sep 03, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [c679b1e522](https://linux-hardware.org/?probe=c679b1e522) | Sep 03, 2024 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [21851ce5cc](https://linux-hardware.org/?probe=21851ce5cc) | Sep 02, 2024 |
| Toshiba       | Satellite C845              | Notebook    | [9424888f5f](https://linux-hardware.org/?probe=9424888f5f) | Sep 02, 2024 |
| Toshiba       | Satellite C845              | Notebook    | [47b262adf3](https://linux-hardware.org/?probe=47b262adf3) | Sep 02, 2024 |
| Acer          | Aspire A114-32              | Notebook    | [e037cd30aa](https://linux-hardware.org/?probe=e037cd30aa) | Sep 02, 2024 |
| Acer          | Spin SP513-52N              | Convertible | [4116f7820f](https://linux-hardware.org/?probe=4116f7820f) | Sep 01, 2024 |
| Acer          | Aspire A315-41G             | Notebook    | [71e96b0436](https://linux-hardware.org/?probe=71e96b0436) | Aug 31, 2024 |
| Dell          | Latitude 5310               | Notebook    | [db35ad3649](https://linux-hardware.org/?probe=db35ad3649) | Aug 31, 2024 |
| Dell          | Latitude 5310               | Notebook    | [a8bb75b996](https://linux-hardware.org/?probe=a8bb75b996) | Aug 31, 2024 |
| ECS           | MB45II7                     | Notebook    | [6f49af5e02](https://linux-hardware.org/?probe=6f49af5e02) | Aug 30, 2024 |
| Dell          | Latitude E5420              | Notebook    | [1aa4784afb](https://linux-hardware.org/?probe=1aa4784afb) | Aug 29, 2024 |
| Google        | Delbin                      | Notebook    | [867ab5e440](https://linux-hardware.org/?probe=867ab5e440) | Aug 29, 2024 |
| ECS           | H81H3-M4                    | Desktop     | [a1a53ea4b7](https://linux-hardware.org/?probe=a1a53ea4b7) | Aug 29, 2024 |
| ECS           | H81H3-M4                    | Desktop     | [07bf45f673](https://linux-hardware.org/?probe=07bf45f673) | Aug 29, 2024 |
| HP            | EliteBook 725 G2            | Notebook    | [d6ab70ffb7](https://linux-hardware.org/?probe=d6ab70ffb7) | Aug 26, 2024 |
| Acer          | Aspire A515-51              | Notebook    | [9e95831bce](https://linux-hardware.org/?probe=9e95831bce) | Aug 25, 2024 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [6bfb0ed86d](https://linux-hardware.org/?probe=6bfb0ed86d) | Aug 24, 2024 |
| MSI           | MS-7253                     | Desktop     | [024d2de5c9](https://linux-hardware.org/?probe=024d2de5c9) | Aug 24, 2024 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [a099b50209](https://linux-hardware.org/?probe=a099b50209) | Aug 23, 2024 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [b235f2f382](https://linux-hardware.org/?probe=b235f2f382) | Aug 23, 2024 |
| HP            | 2129                        | Desktop     | [1eb65765a8](https://linux-hardware.org/?probe=1eb65765a8) | Aug 22, 2024 |
| MSI           | WE75 9TK                    | Notebook    | [4d05773644](https://linux-hardware.org/?probe=4d05773644) | Aug 22, 2024 |
| Lenovo        | SHARKBAY 31900059 STD       | All in one  | [eba82837d7](https://linux-hardware.org/?probe=eba82837d7) | Aug 22, 2024 |
| HP            | 2129                        | Desktop     | [23ae96f746](https://linux-hardware.org/?probe=23ae96f746) | Aug 20, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [bd7e312add](https://linux-hardware.org/?probe=bd7e312add) | Aug 18, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [accba7b6c9](https://linux-hardware.org/?probe=accba7b6c9) | Aug 18, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [dbda8656d2](https://linux-hardware.org/?probe=dbda8656d2) | Aug 18, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [befe3e1358](https://linux-hardware.org/?probe=befe3e1358) | Aug 15, 2024 |
| Dell          | Vostro 3405                 | Notebook    | [e0edcf5178](https://linux-hardware.org/?probe=e0edcf5178) | Aug 15, 2024 |
| Acer          | Aspire A515-52              | Notebook    | [d4a0f1dabc](https://linux-hardware.org/?probe=d4a0f1dabc) | Aug 15, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | Notebook    | [f80bb9feb6](https://linux-hardware.org/?probe=f80bb9feb6) | Aug 15, 2024 |
| HP            | Laptop 14-ck2xxx            | Notebook    | [d1700c44a6](https://linux-hardware.org/?probe=d1700c44a6) | Aug 14, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [5fa457df46](https://linux-hardware.org/?probe=5fa457df46) | Aug 12, 2024 |
| Acer          | Aspire E5-475               | Notebook    | [08272656f2](https://linux-hardware.org/?probe=08272656f2) | Aug 11, 2024 |
| HP            | ENVY dv6                    | Notebook    | [04c052dd7a](https://linux-hardware.org/?probe=04c052dd7a) | Aug 10, 2024 |
| MSI           | Z77A-G41                    | Desktop     | [85eb1d0f02](https://linux-hardware.org/?probe=85eb1d0f02) | Aug 09, 2024 |
| HP            | ENVY dv6                    | Notebook    | [9fbd9c2b30](https://linux-hardware.org/?probe=9fbd9c2b30) | Aug 08, 2024 |
| ECS           | H81H3-M4                    | Desktop     | [64dcbcc2da](https://linux-hardware.org/?probe=64dcbcc2da) | Aug 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d5c408cf5e](https://linux-hardware.org/?probe=d5c408cf5e) | Aug 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [13c021557a](https://linux-hardware.org/?probe=13c021557a) | Aug 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [5c1d1b5170](https://linux-hardware.org/?probe=5c1d1b5170) | Jul 29, 2024 |
| HP            | Notebook                    | Notebook    | [566987604c](https://linux-hardware.org/?probe=566987604c) | Jul 29, 2024 |
| Notebook      | N150CU                      | Notebook    | [c208631141](https://linux-hardware.org/?probe=c208631141) | Jul 28, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [e5c379682b](https://linux-hardware.org/?probe=e5c379682b) | Jul 27, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [62fef05b9b](https://linux-hardware.org/?probe=62fef05b9b) | Jul 25, 2024 |
| MSI           | MS-7253                     | Desktop     | [89164c8b71](https://linux-hardware.org/?probe=89164c8b71) | Jul 25, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [56534da03e](https://linux-hardware.org/?probe=56534da03e) | Jul 23, 2024 |
| Google        | Delbin                      | Notebook    | [38c32f57b2](https://linux-hardware.org/?probe=38c32f57b2) | Jul 21, 2024 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [027ce3ae0f](https://linux-hardware.org/?probe=027ce3ae0f) | Jul 21, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [765d412d98](https://linux-hardware.org/?probe=765d412d98) | Jul 20, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [08b321e009](https://linux-hardware.org/?probe=08b321e009) | Jul 20, 2024 |
| Dell          | 08NPPY A01                  | Desktop     | [03c5024ab6](https://linux-hardware.org/?probe=03c5024ab6) | Jul 19, 2024 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [67f8fcdd69](https://linux-hardware.org/?probe=67f8fcdd69) | Jul 19, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [84c93954c0](https://linux-hardware.org/?probe=84c93954c0) | Jul 18, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ea7ab46b40](https://linux-hardware.org/?probe=ea7ab46b40) | Jul 17, 2024 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [3cdace374a](https://linux-hardware.org/?probe=3cdace374a) | Jul 16, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [e8b1fe9ed6](https://linux-hardware.org/?probe=e8b1fe9ed6) | Jul 16, 2024 |
| Acer          | Aspire E5-432               | Notebook    | [9d95bfc4d2](https://linux-hardware.org/?probe=9d95bfc4d2) | Jul 15, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [2b4f4b4a12](https://linux-hardware.org/?probe=2b4f4b4a12) | Jul 14, 2024 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [d2c62dfa17](https://linux-hardware.org/?probe=d2c62dfa17) | Jul 11, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ab1d6d4f02](https://linux-hardware.org/?probe=ab1d6d4f02) | Jul 11, 2024 |
| HP            | 245 G7 Notebook PC          | Notebook    | [9ac235fa31](https://linux-hardware.org/?probe=9ac235fa31) | Jul 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1f993157aa](https://linux-hardware.org/?probe=1f993157aa) | Jul 07, 2024 |
| HP            | 8A24 0100                   | All in one  | [8dfe1e306a](https://linux-hardware.org/?probe=8dfe1e306a) | Jul 07, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 3 2... | Notebook    | [b4ed6bb1af](https://linux-hardware.org/?probe=b4ed6bb1af) | Jul 06, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [c54b7538dc](https://linux-hardware.org/?probe=c54b7538dc) | Jul 01, 2024 |
| MSI           | GE72 2QE                    | Notebook    | [cf24c50272](https://linux-hardware.org/?probe=cf24c50272) | Jun 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [17c5c8cb74](https://linux-hardware.org/?probe=17c5c8cb74) | Jun 28, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [b20676b126](https://linux-hardware.org/?probe=b20676b126) | Jun 28, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [b7a2770091](https://linux-hardware.org/?probe=b7a2770091) | Jun 28, 2024 |
| MSI           | A520M-A PRO                 | Notebook    | [3df6b0c991](https://linux-hardware.org/?probe=3df6b0c991) | Jun 25, 2024 |
| Dell          | 0KYJ8C A00                  | Desktop     | [0cda74adb5](https://linux-hardware.org/?probe=0cda74adb5) | Jun 25, 2024 |
| Dell          | Latitude E5420              | Notebook    | [3aaef67b1e](https://linux-hardware.org/?probe=3aaef67b1e) | Jun 24, 2024 |
| Samsung       | 530U3C/530U4C               | Notebook    | [70f5730b96](https://linux-hardware.org/?probe=70f5730b96) | Jun 24, 2024 |
| ASUSTek       | PRIME X670-P                | Desktop     | [157fc29a20](https://linux-hardware.org/?probe=157fc29a20) | Jun 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [ba2fcdc6b1](https://linux-hardware.org/?probe=ba2fcdc6b1) | Jun 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d1321209ae](https://linux-hardware.org/?probe=d1321209ae) | Jun 20, 2024 |
| Dell          | Latitude 7480               | Notebook    | [2db9b2a9d4](https://linux-hardware.org/?probe=2db9b2a9d4) | Jun 19, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [53d5c7cd29](https://linux-hardware.org/?probe=53d5c7cd29) | Jun 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [53ef7abbb9](https://linux-hardware.org/?probe=53ef7abbb9) | Jun 18, 2024 |
| PCsmart       | PCSGOB14p-C                 | Notebook    | [0385eed94e](https://linux-hardware.org/?probe=0385eed94e) | Jun 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [dc995bcdc4](https://linux-hardware.org/?probe=dc995bcdc4) | Jun 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [cf4e34380f](https://linux-hardware.org/?probe=cf4e34380f) | Jun 14, 2024 |
| Lenovo        | Unknown                     | Notebook    | [5262e15d02](https://linux-hardware.org/?probe=5262e15d02) | Jun 13, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [bde1d0fcea](https://linux-hardware.org/?probe=bde1d0fcea) | Jun 13, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [95a4c08be3](https://linux-hardware.org/?probe=95a4c08be3) | Jun 12, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [dab5f00a78](https://linux-hardware.org/?probe=dab5f00a78) | Jun 12, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [6619966a0a](https://linux-hardware.org/?probe=6619966a0a) | Jun 12, 2024 |
| HP            | 2B0C                        | All in one  | [ce31398bf7](https://linux-hardware.org/?probe=ce31398bf7) | Jun 12, 2024 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [d424fc5802](https://linux-hardware.org/?probe=d424fc5802) | Jun 11, 2024 |
| Lenovo        | IdeaPad Flex-14IML 81XG     | Convertible | [b3b27df403](https://linux-hardware.org/?probe=b3b27df403) | Jun 11, 2024 |
| HP            | 430                         | Notebook    | [a96448dc30](https://linux-hardware.org/?probe=a96448dc30) | Jun 10, 2024 |
| ECS           | MB45II7                     | Notebook    | [e905ca5cd3](https://linux-hardware.org/?probe=e905ca5cd3) | Jun 10, 2024 |
| Dell          | Vostro 3405                 | Notebook    | [5f158b3516](https://linux-hardware.org/?probe=5f158b3516) | Jun 09, 2024 |
| Lenovo        | G480 20156                  | Notebook    | [a204cf4d1e](https://linux-hardware.org/?probe=a204cf4d1e) | Jun 09, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [00347da833](https://linux-hardware.org/?probe=00347da833) | Jun 09, 2024 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [02e64270cf](https://linux-hardware.org/?probe=02e64270cf) | Jun 09, 2024 |
| MACHINIST     | E5-MR9A PRO V1.2            | Desktop     | [decba51c01](https://linux-hardware.org/?probe=decba51c01) | Jun 08, 2024 |
| Gigabyte      | X670E AORUS PRO X           | Desktop     | [fd6dc7b85b](https://linux-hardware.org/?probe=fd6dc7b85b) | Jun 06, 2024 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e555435a07](https://linux-hardware.org/?probe=e555435a07) | Jun 05, 2024 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [5cd9b65fe2](https://linux-hardware.org/?probe=5cd9b65fe2) | Jun 05, 2024 |
| Dell          | Latitude E6440              | Notebook    | [74814a37e4](https://linux-hardware.org/?probe=74814a37e4) | Jun 05, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c2c43351e9](https://linux-hardware.org/?probe=c2c43351e9) | Jun 05, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d7c0e11e24](https://linux-hardware.org/?probe=d7c0e11e24) | Jun 05, 2024 |
| ASUSTek       | X555LB                      | Notebook    | [9c9451d483](https://linux-hardware.org/?probe=9c9451d483) | Jun 04, 2024 |
| ASUSTek       | X555LB                      | Notebook    | [5212c48bcc](https://linux-hardware.org/?probe=5212c48bcc) | Jun 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [944b18a334](https://linux-hardware.org/?probe=944b18a334) | Jun 03, 2024 |
| Dell          | 0D883F A06                  | Desktop     | [b05d49d4c6](https://linux-hardware.org/?probe=b05d49d4c6) | Jun 03, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [13999beb87](https://linux-hardware.org/?probe=13999beb87) | Jun 03, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5631280fa6](https://linux-hardware.org/?probe=5631280fa6) | Jun 03, 2024 |
| Lenovo        | 375A WIN SDK0T76466 3424... | All in one  | [29c9441e48](https://linux-hardware.org/?probe=29c9441e48) | May 31, 2024 |
| Apple         | MacBookAir5,2               | Notebook    | [11cbeead14](https://linux-hardware.org/?probe=11cbeead14) | May 31, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [8e3332a712](https://linux-hardware.org/?probe=8e3332a712) | May 31, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU603ZE... | Notebook    | [ea87d9525c](https://linux-hardware.org/?probe=ea87d9525c) | May 31, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [d81c54a77c](https://linux-hardware.org/?probe=d81c54a77c) | May 30, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [30a3957cfe](https://linux-hardware.org/?probe=30a3957cfe) | May 29, 2024 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [4b5c79152f](https://linux-hardware.org/?probe=4b5c79152f) | May 29, 2024 |
| HP            | ProBook 4440s               | Notebook    | [e3a0679bb2](https://linux-hardware.org/?probe=e3a0679bb2) | May 28, 2024 |
| Dell          | 08NPPY A01                  | Desktop     | [30ae7d8cc1](https://linux-hardware.org/?probe=30ae7d8cc1) | May 27, 2024 |
| HP            | ProBook 4440s               | Notebook    | [b0946f2c86](https://linux-hardware.org/?probe=b0946f2c86) | May 27, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [c573a16710](https://linux-hardware.org/?probe=c573a16710) | May 27, 2024 |
| Lenovo        | 375A WIN SDK0T76466 3424... | All in one  | [801ae34199](https://linux-hardware.org/?probe=801ae34199) | May 24, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [0a28f50162](https://linux-hardware.org/?probe=0a28f50162) | May 24, 2024 |
| HP            | Laptop 14-ck2xxx            | Notebook    | [b7924793c6](https://linux-hardware.org/?probe=b7924793c6) | May 24, 2024 |
| Acer          | AOD270                      | Notebook    | [7b3930b5cd](https://linux-hardware.org/?probe=7b3930b5cd) | May 24, 2024 |
| ASUSTek       | H61M-K                      | Desktop     | [ed0fb6e87d](https://linux-hardware.org/?probe=ed0fb6e87d) | May 24, 2024 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [62a04b2b5d](https://linux-hardware.org/?probe=62a04b2b5d) | May 22, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [babb1dcba6](https://linux-hardware.org/?probe=babb1dcba6) | May 22, 2024 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [0f5a351e75](https://linux-hardware.org/?probe=0f5a351e75) | May 22, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [36eb3289fa](https://linux-hardware.org/?probe=36eb3289fa) | May 17, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [a667660a0c](https://linux-hardware.org/?probe=a667660a0c) | May 17, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [146a53575b](https://linux-hardware.org/?probe=146a53575b) | May 17, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [762e11217b](https://linux-hardware.org/?probe=762e11217b) | May 16, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [3d297e3790](https://linux-hardware.org/?probe=3d297e3790) | May 16, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [d69896c6f9](https://linux-hardware.org/?probe=d69896c6f9) | May 16, 2024 |
| Dell          | 0D883F A06                  | Desktop     | [d979b83929](https://linux-hardware.org/?probe=d979b83929) | May 16, 2024 |
| ASRock        | Z590 Steel Legend WiFi 6... | Desktop     | [9afb28537a](https://linux-hardware.org/?probe=9afb28537a) | May 16, 2024 |
| ASUSTek       | M3402WFA                    | All in one  | [0ffcb537c4](https://linux-hardware.org/?probe=0ffcb537c4) | May 15, 2024 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [3e68a71909](https://linux-hardware.org/?probe=3e68a71909) | May 15, 2024 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [1274f38873](https://linux-hardware.org/?probe=1274f38873) | May 15, 2024 |
| Toshiba       | QOSMIO X875                 | Notebook    | [0d5cc8e6ec](https://linux-hardware.org/?probe=0d5cc8e6ec) | May 14, 2024 |
| Notebook      | N150CU                      | Notebook    | [f57c924d44](https://linux-hardware.org/?probe=f57c924d44) | May 14, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [345ddaf7ed](https://linux-hardware.org/?probe=345ddaf7ed) | May 13, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | Desktop     | [0fdd6d8d04](https://linux-hardware.org/?probe=0fdd6d8d04) | May 12, 2024 |
| Biostar       | G41D3B                      | Desktop     | [3f88596c99](https://linux-hardware.org/?probe=3f88596c99) | May 12, 2024 |
| ASUSTek       | ZenBook UX431FAC_UX431FA    | Notebook    | [411cc3a5eb](https://linux-hardware.org/?probe=411cc3a5eb) | May 12, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [4720614db4](https://linux-hardware.org/?probe=4720614db4) | May 09, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [64289cb32c](https://linux-hardware.org/?probe=64289cb32c) | May 08, 2024 |
| PCSMART       | 7.0                         | Desktop     | [66d6082bf4](https://linux-hardware.org/?probe=66d6082bf4) | May 07, 2024 |
| Gigabyte      | H410M H V3                  | Desktop     | [486c191884](https://linux-hardware.org/?probe=486c191884) | May 07, 2024 |
| Notebook      | N150CU                      | Notebook    | [348d0cab2d](https://linux-hardware.org/?probe=348d0cab2d) | May 07, 2024 |
| HP            | G60                         | Notebook    | [c9e5d3832d](https://linux-hardware.org/?probe=c9e5d3832d) | May 07, 2024 |
| PCSMART       | 7.0                         | Desktop     | [18ea3d8d19](https://linux-hardware.org/?probe=18ea3d8d19) | May 05, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [93da978d38](https://linux-hardware.org/?probe=93da978d38) | May 04, 2024 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [ba1456ce87](https://linux-hardware.org/?probe=ba1456ce87) | May 03, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [94b445552d](https://linux-hardware.org/?probe=94b445552d) | May 03, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [2cf97ed4d6](https://linux-hardware.org/?probe=2cf97ed4d6) | May 03, 2024 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [15e7baeeb3](https://linux-hardware.org/?probe=15e7baeeb3) | May 03, 2024 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [9cfa5ae2c5](https://linux-hardware.org/?probe=9cfa5ae2c5) | May 03, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [c8e2add151](https://linux-hardware.org/?probe=c8e2add151) | May 03, 2024 |
| ASUSTek       | X540YA                      | Notebook    | [e163aa8e32](https://linux-hardware.org/?probe=e163aa8e32) | May 03, 2024 |
| Intel         | X79G V2.x                   | Desktop     | [00807bfaa6](https://linux-hardware.org/?probe=00807bfaa6) | May 02, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [cd1ed35419](https://linux-hardware.org/?probe=cd1ed35419) | May 02, 2024 |
| Biostar       | G41D3B                      | Desktop     | [748e0749c5](https://linux-hardware.org/?probe=748e0749c5) | Apr 30, 2024 |
| ASRock        | N68-S                       | Desktop     | [a099ad6775](https://linux-hardware.org/?probe=a099ad6775) | Apr 30, 2024 |
| MSI           | Sword 15 A12VE              | Notebook    | [90ad4b4438](https://linux-hardware.org/?probe=90ad4b4438) | Apr 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JL0... | Notebook    | [5f82ffafd9](https://linux-hardware.org/?probe=5f82ffafd9) | Apr 28, 2024 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [be4fcee6fb](https://linux-hardware.org/?probe=be4fcee6fb) | Apr 28, 2024 |
| MSI           | Sword 15 A12VE              | Notebook    | [54953e1bae](https://linux-hardware.org/?probe=54953e1bae) | Apr 27, 2024 |
| ASUSTek       | ZenBook UX431FAC_UX431FA    | Notebook    | [7c4a5dba54](https://linux-hardware.org/?probe=7c4a5dba54) | Apr 27, 2024 |
| Dell          | Inspiron 15 3520            | Notebook    | [e8f25e02cb](https://linux-hardware.org/?probe=e8f25e02cb) | Apr 27, 2024 |
| HP            | Pavilion 15                 | Notebook    | [ef9f89946b](https://linux-hardware.org/?probe=ef9f89946b) | Apr 26, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [24559368fd](https://linux-hardware.org/?probe=24559368fd) | Apr 25, 2024 |
| ASUSTek       | ZenBook UX431FAC_UX431FA    | Notebook    | [cc693892db](https://linux-hardware.org/?probe=cc693892db) | Apr 24, 2024 |
| Gigabyte      | X670E AORUS PRO X           | Desktop     | [ac94661695](https://linux-hardware.org/?probe=ac94661695) | Apr 24, 2024 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [276ff854fe](https://linux-hardware.org/?probe=276ff854fe) | Apr 20, 2024 |
| ASUSTek       | ASUS P1412CEA_P1412CEA      | Notebook    | [1cc39c7bdc](https://linux-hardware.org/?probe=1cc39c7bdc) | Apr 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d173c3e7d7](https://linux-hardware.org/?probe=d173c3e7d7) | Apr 18, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [07cede8279](https://linux-hardware.org/?probe=07cede8279) | Apr 17, 2024 |
| HP            | 245 G6                      | Notebook    | [17b7e55361](https://linux-hardware.org/?probe=17b7e55361) | Apr 17, 2024 |
| HP            | 245 G6                      | Notebook    | [7c3534813c](https://linux-hardware.org/?probe=7c3534813c) | Apr 17, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [983c22ff1b](https://linux-hardware.org/?probe=983c22ff1b) | Apr 17, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [88862b5c78](https://linux-hardware.org/?probe=88862b5c78) | Apr 16, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [3e03fa9446](https://linux-hardware.org/?probe=3e03fa9446) | Apr 14, 2024 |
| HP            | G42                         | Notebook    | [3fc8c107a9](https://linux-hardware.org/?probe=3fc8c107a9) | Apr 14, 2024 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [3d32f9eea8](https://linux-hardware.org/?probe=3d32f9eea8) | Apr 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [fe388e2f15](https://linux-hardware.org/?probe=fe388e2f15) | Apr 11, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [be0f54854d](https://linux-hardware.org/?probe=be0f54854d) | Apr 10, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [75b15c6330](https://linux-hardware.org/?probe=75b15c6330) | Apr 09, 2024 |
| Acer          | Aspire E5-475               | Notebook    | [31e70b6cc1](https://linux-hardware.org/?probe=31e70b6cc1) | Apr 08, 2024 |
| MSI           | NF725M-P43                  | Desktop     | [9fc3ac2e10](https://linux-hardware.org/?probe=9fc3ac2e10) | Apr 07, 2024 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [943c2e486a](https://linux-hardware.org/?probe=943c2e486a) | Apr 05, 2024 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [61f8f4ee36](https://linux-hardware.org/?probe=61f8f4ee36) | Apr 03, 2024 |
| Acer          | Nitro AN515-43              | Notebook    | [76e26b9d8d](https://linux-hardware.org/?probe=76e26b9d8d) | Apr 02, 2024 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [d3bb728f76](https://linux-hardware.org/?probe=d3bb728f76) | Apr 02, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [56d6828ee1](https://linux-hardware.org/?probe=56d6828ee1) | Apr 02, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [88b5d2f855](https://linux-hardware.org/?probe=88b5d2f855) | Apr 01, 2024 |
| HP            | Compaq CQ45                 | Notebook    | [f407a35faa](https://linux-hardware.org/?probe=f407a35faa) | Mar 31, 2024 |
| ASUSTek       | X542UR                      | Notebook    | [4710a67397](https://linux-hardware.org/?probe=4710a67397) | Mar 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [2086c8754a](https://linux-hardware.org/?probe=2086c8754a) | Mar 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [97a323caf9](https://linux-hardware.org/?probe=97a323caf9) | Mar 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [b2c4278c2c](https://linux-hardware.org/?probe=b2c4278c2c) | Mar 24, 2024 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [8a64818a8c](https://linux-hardware.org/?probe=8a64818a8c) | Mar 22, 2024 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [6815c42449](https://linux-hardware.org/?probe=6815c42449) | Mar 22, 2024 |
| MSI           | 760GM-P21                   | Desktop     | [9ea00e6ebb](https://linux-hardware.org/?probe=9ea00e6ebb) | Mar 22, 2024 |
| Lenovo        | SHARKBAY 31900059 STD       | All in one  | [db9bb64be9](https://linux-hardware.org/?probe=db9bb64be9) | Mar 20, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [3a1d89395a](https://linux-hardware.org/?probe=3a1d89395a) | Mar 20, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [90f80551da](https://linux-hardware.org/?probe=90f80551da) | Mar 20, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dddc8e40c7](https://linux-hardware.org/?probe=dddc8e40c7) | Mar 20, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dfc5f12487](https://linux-hardware.org/?probe=dfc5f12487) | Mar 19, 2024 |
| Acer          | Predator G3-710             | Desktop     | [81423396ff](https://linux-hardware.org/?probe=81423396ff) | Mar 16, 2024 |
| Acer          | Predator G3-710             | Desktop     | [4a28c9273f](https://linux-hardware.org/?probe=4a28c9273f) | Mar 16, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [6c43f0d8df](https://linux-hardware.org/?probe=6c43f0d8df) | Mar 14, 2024 |
| MSI           | Katana 15 B13VGK            | Notebook    | [b442691d34](https://linux-hardware.org/?probe=b442691d34) | Mar 12, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [903192b99a](https://linux-hardware.org/?probe=903192b99a) | Mar 09, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [27e68f4135](https://linux-hardware.org/?probe=27e68f4135) | Mar 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [b82f1b6779](https://linux-hardware.org/?probe=b82f1b6779) | Mar 07, 2024 |
| MACHINIST     | X99-RS9 V1.11               | Notebook    | [52886e70b7](https://linux-hardware.org/?probe=52886e70b7) | Mar 07, 2024 |
| Lenovo        | ThinkPad X201 3680DQ1       | Notebook    | [34753ba966](https://linux-hardware.org/?probe=34753ba966) | Mar 07, 2024 |
| HP            | Compaq CQ45                 | Notebook    | [8b9fbadb38](https://linux-hardware.org/?probe=8b9fbadb38) | Mar 07, 2024 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [6e87e2444b](https://linux-hardware.org/?probe=6e87e2444b) | Mar 05, 2024 |
| Dell          | Inspiron 5521               | Notebook    | [88afd1df62](https://linux-hardware.org/?probe=88afd1df62) | Mar 04, 2024 |
| Lenovo        | IdeaPad 3-15ALC6 82KU       | Notebook    | [b8fd99274c](https://linux-hardware.org/?probe=b8fd99274c) | Mar 03, 2024 |
| Lenovo        | IdeaPad 3-15ALC6 82KU       | Notebook    | [ed871e7a4c](https://linux-hardware.org/?probe=ed871e7a4c) | Mar 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [438db8c531](https://linux-hardware.org/?probe=438db8c531) | Mar 02, 2024 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [72de749595](https://linux-hardware.org/?probe=72de749595) | Mar 02, 2024 |
| HP            | 1495                        | Desktop     | [ee01c60448](https://linux-hardware.org/?probe=ee01c60448) | Feb 29, 2024 |
| Lenovo        | Larne CRB 31900059 WIN 2... | All in one  | [bf9708459b](https://linux-hardware.org/?probe=bf9708459b) | Feb 29, 2024 |
| Dell          | XPS 15 9510                 | Notebook    | [398ee4b3fd](https://linux-hardware.org/?probe=398ee4b3fd) | Feb 25, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [8bc3b77cc1](https://linux-hardware.org/?probe=8bc3b77cc1) | Feb 24, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6780bc7e37](https://linux-hardware.org/?probe=6780bc7e37) | Feb 22, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [d1df1f4690](https://linux-hardware.org/?probe=d1df1f4690) | Feb 21, 2024 |
| Toshiba       | Satellite P55t-B            | Notebook    | [a5bb579413](https://linux-hardware.org/?probe=a5bb579413) | Feb 21, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [6898b49b84](https://linux-hardware.org/?probe=6898b49b84) | Feb 21, 2024 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [da65aaff1d](https://linux-hardware.org/?probe=da65aaff1d) | Feb 20, 2024 |
| Acer          | Aspire A315-56              | Notebook    | [31fb70770e](https://linux-hardware.org/?probe=31fb70770e) | Feb 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [8dcedb7dea](https://linux-hardware.org/?probe=8dcedb7dea) | Feb 16, 2024 |
| Intel         | X79G V2.x                   | Desktop     | [077f5b4397](https://linux-hardware.org/?probe=077f5b4397) | Feb 15, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ba049eb9f2](https://linux-hardware.org/?probe=ba049eb9f2) | Feb 14, 2024 |
| Lenovo        | ThinkStation D30 4223AU4    | Desktop     | [bd10aa2839](https://linux-hardware.org/?probe=bd10aa2839) | Feb 13, 2024 |
| HP            | 245 G7                      | Notebook    | [6a17d5afe5](https://linux-hardware.org/?probe=6a17d5afe5) | Feb 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [0cb65112ff](https://linux-hardware.org/?probe=0cb65112ff) | Feb 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8f47ad3e3b](https://linux-hardware.org/?probe=8f47ad3e3b) | Feb 12, 2024 |
| HP            | 240 G7 Notebook PC          | Notebook    | [de6bdd8e6b](https://linux-hardware.org/?probe=de6bdd8e6b) | Feb 12, 2024 |
| HP            | 420                         | Notebook    | [810770c1ad](https://linux-hardware.org/?probe=810770c1ad) | Feb 11, 2024 |
| HP            | Pavilion dm1                | Notebook    | [2a8da8e595](https://linux-hardware.org/?probe=2a8da8e595) | Feb 11, 2024 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [f4a064bb65](https://linux-hardware.org/?probe=f4a064bb65) | Feb 10, 2024 |
| Dell          | Inspiron 5521               | Notebook    | [ec2bc4253e](https://linux-hardware.org/?probe=ec2bc4253e) | Feb 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6b61926dd2](https://linux-hardware.org/?probe=6b61926dd2) | Feb 09, 2024 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [f85fa50f25](https://linux-hardware.org/?probe=f85fa50f25) | Feb 08, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [139cdcc6d9](https://linux-hardware.org/?probe=139cdcc6d9) | Feb 08, 2024 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [3e2e86741b](https://linux-hardware.org/?probe=3e2e86741b) | Feb 08, 2024 |
| Biostar       | A58ML                       | Desktop     | [207acb5012](https://linux-hardware.org/?probe=207acb5012) | Feb 07, 2024 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [1421d1168c](https://linux-hardware.org/?probe=1421d1168c) | Feb 05, 2024 |
| ASRock        | X670E Pro RS                | Desktop     | [b5f16b7125](https://linux-hardware.org/?probe=b5f16b7125) | Feb 03, 2024 |
| ASRock        | X670E Pro RS                | Desktop     | [fd02477c14](https://linux-hardware.org/?probe=fd02477c14) | Feb 02, 2024 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [bbf603e6e6](https://linux-hardware.org/?probe=bbf603e6e6) | Jan 30, 2024 |
| Acer          | Aspire E1-470               | Notebook    | [732a523ea8](https://linux-hardware.org/?probe=732a523ea8) | Jan 28, 2024 |
| Notebook      | N150CU                      | Notebook    | [fc98de3ad4](https://linux-hardware.org/?probe=fc98de3ad4) | Jan 28, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [0fce3dbe59](https://linux-hardware.org/?probe=0fce3dbe59) | Jan 27, 2024 |
| HP            | ProBook 440 G7              | Notebook    | [47b3929229](https://linux-hardware.org/?probe=47b3929229) | Jan 25, 2024 |
| Lenovo        | IdeaPad 3-15ALC6 82KU       | Notebook    | [c91921bbe1](https://linux-hardware.org/?probe=c91921bbe1) | Jan 24, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [7c453fba6f](https://linux-hardware.org/?probe=7c453fba6f) | Jan 23, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6dbdc40268](https://linux-hardware.org/?probe=6dbdc40268) | Jan 22, 2024 |
| Lenovo        | ThinkCentre A62 9486E4S     | Desktop     | [426fe50b95](https://linux-hardware.org/?probe=426fe50b95) | Jan 21, 2024 |
| Lenovo        | ThinkCentre A62 9486E4S     | Desktop     | [9712c9e135](https://linux-hardware.org/?probe=9712c9e135) | Jan 21, 2024 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [409e7e4e42](https://linux-hardware.org/?probe=409e7e4e42) | Jan 17, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [a8557f8a49](https://linux-hardware.org/?probe=a8557f8a49) | Jan 17, 2024 |
| Acer          | TravelMate P214-53          | Notebook    | [dbe5ed82b8](https://linux-hardware.org/?probe=dbe5ed82b8) | Jan 16, 2024 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [24da300af6](https://linux-hardware.org/?probe=24da300af6) | Jan 16, 2024 |
| HP            | ProBook 445 G7              | Notebook    | [a9499322c3](https://linux-hardware.org/?probe=a9499322c3) | Jan 15, 2024 |
| Lenovo        | ThinkPad T430 2347AF3       | Notebook    | [c52851e59b](https://linux-hardware.org/?probe=c52851e59b) | Jan 15, 2024 |
| COIN COMPU... | LUM580                      | Notebook    | [e9f6bacb29](https://linux-hardware.org/?probe=e9f6bacb29) | Jan 15, 2024 |
| HP            | 18E5                        | Desktop     | [4fb3a76631](https://linux-hardware.org/?probe=4fb3a76631) | Jan 15, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [23c4e3e208](https://linux-hardware.org/?probe=23c4e3e208) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b98091e5e6](https://linux-hardware.org/?probe=b98091e5e6) | Jan 13, 2024 |
| Intel         | X79G V2.x                   | Desktop     | [cf61b1759b](https://linux-hardware.org/?probe=cf61b1759b) | Jan 12, 2024 |
| MSI           | GF615M-P33                  | Desktop     | [7d32db9104](https://linux-hardware.org/?probe=7d32db9104) | Jan 12, 2024 |
| ASRock        | X670E Pro RS                | Desktop     | [2f899514f8](https://linux-hardware.org/?probe=2f899514f8) | Jan 12, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [74e153aeed](https://linux-hardware.org/?probe=74e153aeed) | Jan 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [be9bd3885e](https://linux-hardware.org/?probe=be9bd3885e) | Jan 11, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [54e682c32b](https://linux-hardware.org/?probe=54e682c32b) | Jan 10, 2024 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | Notebook    | [9a12d1146d](https://linux-hardware.org/?probe=9a12d1146d) | Jan 09, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [5de015033e](https://linux-hardware.org/?probe=5de015033e) | Jan 08, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f9da9135c7](https://linux-hardware.org/?probe=f9da9135c7) | Jan 08, 2024 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [3ff7f414fe](https://linux-hardware.org/?probe=3ff7f414fe) | Jan 07, 2024 |
| MSI           | H81M-E33                    | Desktop     | [cced2d2e95](https://linux-hardware.org/?probe=cced2d2e95) | Jan 07, 2024 |
| Lenovo        | IdeaPad 3 14IAU7 82RJ       | Notebook    | [9b3ba608ee](https://linux-hardware.org/?probe=9b3ba608ee) | Jan 06, 2024 |
| HP            | Presario CQ45               | Notebook    | [8a0a9f1dc0](https://linux-hardware.org/?probe=8a0a9f1dc0) | Jan 04, 2024 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [442c8e3a83](https://linux-hardware.org/?probe=442c8e3a83) | Jan 03, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [f10936a9f7](https://linux-hardware.org/?probe=f10936a9f7) | Jan 02, 2024 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [40362f198b](https://linux-hardware.org/?probe=40362f198b) | Dec 31, 2023 |
| HP            | 8374 1100                   | All in one  | [29b989dbb6](https://linux-hardware.org/?probe=29b989dbb6) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [61c1444cfc](https://linux-hardware.org/?probe=61c1444cfc) | Dec 29, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [4ba914628d](https://linux-hardware.org/?probe=4ba914628d) | Dec 29, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [863f0b5c06](https://linux-hardware.org/?probe=863f0b5c06) | Dec 29, 2023 |
| COIN COMPU... | LUM580                      | Notebook    | [6a8246b500](https://linux-hardware.org/?probe=6a8246b500) | Dec 28, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [8250429628](https://linux-hardware.org/?probe=8250429628) | Dec 28, 2023 |
| Lenovo        | ThinkPad T510 43492RU       | Notebook    | [87b76140e0](https://linux-hardware.org/?probe=87b76140e0) | Dec 28, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [6b98d84cb0](https://linux-hardware.org/?probe=6b98d84cb0) | Dec 28, 2023 |
| HP            | 339A                        | Desktop     | [49cb574539](https://linux-hardware.org/?probe=49cb574539) | Dec 27, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [3c0ecabaa3](https://linux-hardware.org/?probe=3c0ecabaa3) | Dec 27, 2023 |
| Lenovo        | ThinkPad T510 43492RU       | Notebook    | [d3f51b650d](https://linux-hardware.org/?probe=d3f51b650d) | Dec 27, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [53fae0e708](https://linux-hardware.org/?probe=53fae0e708) | Dec 25, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [0a5b67d3f4](https://linux-hardware.org/?probe=0a5b67d3f4) | Dec 24, 2023 |
| Toshiba       | Satellite Pro L450          | Notebook    | [8da0c619f3](https://linux-hardware.org/?probe=8da0c619f3) | Dec 24, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [8becdfe1a4](https://linux-hardware.org/?probe=8becdfe1a4) | Dec 23, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [ff13629db9](https://linux-hardware.org/?probe=ff13629db9) | Dec 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [41256541b5](https://linux-hardware.org/?probe=41256541b5) | Dec 21, 2023 |
| Dell          | Latitude E7270              | Notebook    | [4574a46c78](https://linux-hardware.org/?probe=4574a46c78) | Dec 21, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [5266cee35b](https://linux-hardware.org/?probe=5266cee35b) | Dec 21, 2023 |
| Dell          | Latitude E5450              | Notebook    | [6d4e378f53](https://linux-hardware.org/?probe=6d4e378f53) | Dec 20, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [7b4cd22d8d](https://linux-hardware.org/?probe=7b4cd22d8d) | Dec 20, 2023 |
| Dell          | Latitude E5450              | Notebook    | [627a81b211](https://linux-hardware.org/?probe=627a81b211) | Dec 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2d2f0f8de2](https://linux-hardware.org/?probe=2d2f0f8de2) | Dec 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4e18aeb53f](https://linux-hardware.org/?probe=4e18aeb53f) | Dec 18, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [1c7f9648af](https://linux-hardware.org/?probe=1c7f9648af) | Dec 14, 2023 |
| Acer          | Spin SP513-52N              | Convertible | [7e8dd058b9](https://linux-hardware.org/?probe=7e8dd058b9) | Dec 14, 2023 |
| MSI           | A88XM GAMING                | Desktop     | [1f17749a2e](https://linux-hardware.org/?probe=1f17749a2e) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [756283ec58](https://linux-hardware.org/?probe=756283ec58) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [c258c213e6](https://linux-hardware.org/?probe=c258c213e6) | Dec 12, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [03c91234ae](https://linux-hardware.org/?probe=03c91234ae) | Dec 11, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [06651b08d9](https://linux-hardware.org/?probe=06651b08d9) | Dec 11, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [ccd16e5c8d](https://linux-hardware.org/?probe=ccd16e5c8d) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c71a153915](https://linux-hardware.org/?probe=c71a153915) | Dec 11, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [ba6f3ac46c](https://linux-hardware.org/?probe=ba6f3ac46c) | Dec 10, 2023 |
| Sony          | SVE11115ELW                 | Notebook    | [68fa8c6081](https://linux-hardware.org/?probe=68fa8c6081) | Dec 10, 2023 |
| Sony          | SVE11115ELW                 | Notebook    | [567787c7d3](https://linux-hardware.org/?probe=567787c7d3) | Dec 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [31943290a3](https://linux-hardware.org/?probe=31943290a3) | Dec 09, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [c5a3d157b2](https://linux-hardware.org/?probe=c5a3d157b2) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [74512675b8](https://linux-hardware.org/?probe=74512675b8) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0c4e850e29](https://linux-hardware.org/?probe=0c4e850e29) | Dec 08, 2023 |
| HP            | G42                         | Notebook    | [f23e6ffe56](https://linux-hardware.org/?probe=f23e6ffe56) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [cf8f25ba97](https://linux-hardware.org/?probe=cf8f25ba97) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [673016ba0f](https://linux-hardware.org/?probe=673016ba0f) | Dec 07, 2023 |
| Notebook      | P15SM-A/SM1-A               | Notebook    | [f7c8033eef](https://linux-hardware.org/?probe=f7c8033eef) | Dec 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [fc51759095](https://linux-hardware.org/?probe=fc51759095) | Dec 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [1cfd81f715](https://linux-hardware.org/?probe=1cfd81f715) | Dec 05, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [219f784b96](https://linux-hardware.org/?probe=219f784b96) | Dec 04, 2023 |
| Acer          | Aspire E1-470               | Notebook    | [507314cc1f](https://linux-hardware.org/?probe=507314cc1f) | Dec 04, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [218e5c18f3](https://linux-hardware.org/?probe=218e5c18f3) | Dec 04, 2023 |
| Sony          | SVP13215PLS                 | Notebook    | [6c360dc427](https://linux-hardware.org/?probe=6c360dc427) | Dec 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [7b5d061328](https://linux-hardware.org/?probe=7b5d061328) | Dec 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1729d2c4c1](https://linux-hardware.org/?probe=1729d2c4c1) | Dec 02, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [46a43fa59d](https://linux-hardware.org/?probe=46a43fa59d) | Dec 02, 2023 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [8646f4d21b](https://linux-hardware.org/?probe=8646f4d21b) | Dec 01, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [d91455d676](https://linux-hardware.org/?probe=d91455d676) | Nov 30, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6865be0fd7](https://linux-hardware.org/?probe=6865be0fd7) | Nov 29, 2023 |
| Dell          | 0478VN A00                  | Desktop     | [9673d66df0](https://linux-hardware.org/?probe=9673d66df0) | Nov 28, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [ee5fe89209](https://linux-hardware.org/?probe=ee5fe89209) | Nov 28, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [5aee774fa3](https://linux-hardware.org/?probe=5aee774fa3) | Nov 27, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [8378baf644](https://linux-hardware.org/?probe=8378baf644) | Nov 26, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e05084a6aa](https://linux-hardware.org/?probe=e05084a6aa) | Nov 26, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [653b4e617f](https://linux-hardware.org/?probe=653b4e617f) | Nov 25, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [92392e304b](https://linux-hardware.org/?probe=92392e304b) | Nov 24, 2023 |
| ASUSTek       | Vivobook Go E1504GAB_E15... | Notebook    | [d733fc5f50](https://linux-hardware.org/?probe=d733fc5f50) | Nov 24, 2023 |
| ASUSTek       | Vivobook Go E1504GAB_E15... | Notebook    | [17fd894479](https://linux-hardware.org/?probe=17fd894479) | Nov 24, 2023 |
| Dell          | Latitude 3410               | Notebook    | [db53da231e](https://linux-hardware.org/?probe=db53da231e) | Nov 22, 2023 |
| HP            | 1495                        | Desktop     | [c03adda1fa](https://linux-hardware.org/?probe=c03adda1fa) | Nov 20, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [b3b8fff6bb](https://linux-hardware.org/?probe=b3b8fff6bb) | Nov 19, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [1e7be1c070](https://linux-hardware.org/?probe=1e7be1c070) | Nov 18, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [2af4aec091](https://linux-hardware.org/?probe=2af4aec091) | Nov 17, 2023 |
| Dell          | Inspiron 5421               | Notebook    | [e8f49a554a](https://linux-hardware.org/?probe=e8f49a554a) | Nov 16, 2023 |
| Dell          | Inspiron 5421               | Notebook    | [5e6d967f4d](https://linux-hardware.org/?probe=5e6d967f4d) | Nov 16, 2023 |
| Toshiba       | NB205                       | Notebook    | [a3f0bef4d4](https://linux-hardware.org/?probe=a3f0bef4d4) | Nov 15, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [6806c7c828](https://linux-hardware.org/?probe=6806c7c828) | Nov 15, 2023 |
| HP            | 8105                        | Desktop     | [d77d0abf96](https://linux-hardware.org/?probe=d77d0abf96) | Nov 15, 2023 |
| Lenovo        | G40-70 20369                | Notebook    | [c103e79147](https://linux-hardware.org/?probe=c103e79147) | Nov 14, 2023 |
| Toshiba       | Satellite A665D             | Notebook    | [eed03ef68f](https://linux-hardware.org/?probe=eed03ef68f) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [4a32a91914](https://linux-hardware.org/?probe=4a32a91914) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [5fdbcfb950](https://linux-hardware.org/?probe=5fdbcfb950) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [6185a29334](https://linux-hardware.org/?probe=6185a29334) | Nov 09, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b0d207b140](https://linux-hardware.org/?probe=b0d207b140) | Nov 07, 2023 |
| Lenovo        | IdeaPad S400u 20213         | Notebook    | [5ddd610c2d](https://linux-hardware.org/?probe=5ddd610c2d) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b3e37dd334](https://linux-hardware.org/?probe=b3e37dd334) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [f5a032555f](https://linux-hardware.org/?probe=f5a032555f) | Nov 06, 2023 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [8d789a3937](https://linux-hardware.org/?probe=8d789a3937) | Nov 06, 2023 |
| HP            | 198E                        | Desktop     | [f1d1b6839f](https://linux-hardware.org/?probe=f1d1b6839f) | Nov 05, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [4236902f3d](https://linux-hardware.org/?probe=4236902f3d) | Nov 03, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [f07206a75c](https://linux-hardware.org/?probe=f07206a75c) | Nov 02, 2023 |
| Dell          | Latitude 3410               | Notebook    | [4ffdc962bf](https://linux-hardware.org/?probe=4ffdc962bf) | Nov 01, 2023 |
| Notebook      | N150CU                      | Notebook    | [a345496524](https://linux-hardware.org/?probe=a345496524) | Nov 01, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [385c30cad6](https://linux-hardware.org/?probe=385c30cad6) | Oct 31, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [e3db582993](https://linux-hardware.org/?probe=e3db582993) | Oct 31, 2023 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [ec6be29d3e](https://linux-hardware.org/?probe=ec6be29d3e) | Oct 29, 2023 |
| Notebook      | N150CU                      | Notebook    | [12347d42c1](https://linux-hardware.org/?probe=12347d42c1) | Oct 28, 2023 |
| Dell          | 08NPPY A01                  | Desktop     | [62bc2b3e7a](https://linux-hardware.org/?probe=62bc2b3e7a) | Oct 28, 2023 |
| Lenovo        | 0B98409 STD                 | Desktop     | [b89f42b23f](https://linux-hardware.org/?probe=b89f42b23f) | Oct 24, 2023 |
| Dell          | Inspiron 14-3467            | Notebook    | [ea07cbb7c4](https://linux-hardware.org/?probe=ea07cbb7c4) | Oct 24, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [92dbf8615b](https://linux-hardware.org/?probe=92dbf8615b) | Oct 24, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [de15a66a8b](https://linux-hardware.org/?probe=de15a66a8b) | Oct 22, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [037cfc67ae](https://linux-hardware.org/?probe=037cfc67ae) | Oct 22, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [dd755eb3a0](https://linux-hardware.org/?probe=dd755eb3a0) | Oct 22, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [c511cce283](https://linux-hardware.org/?probe=c511cce283) | Oct 22, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [49d37b87cf](https://linux-hardware.org/?probe=49d37b87cf) | Oct 21, 2023 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [125e76df80](https://linux-hardware.org/?probe=125e76df80) | Oct 20, 2023 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [3a5c553fcb](https://linux-hardware.org/?probe=3a5c553fcb) | Oct 20, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [01c73b9338](https://linux-hardware.org/?probe=01c73b9338) | Oct 18, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [b552badf93](https://linux-hardware.org/?probe=b552badf93) | Oct 17, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [8b92e44d64](https://linux-hardware.org/?probe=8b92e44d64) | Oct 17, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [64738e1724](https://linux-hardware.org/?probe=64738e1724) | Oct 15, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [0702e52c02](https://linux-hardware.org/?probe=0702e52c02) | Oct 14, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [4ba8548e96](https://linux-hardware.org/?probe=4ba8548e96) | Oct 14, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4b5b669131](https://linux-hardware.org/?probe=4b5b669131) | Oct 12, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [cc8062e568](https://linux-hardware.org/?probe=cc8062e568) | Oct 12, 2023 |
| Lenovo        | ThinkCentre M90 5485AK7     | Desktop     | [02e02dbca5](https://linux-hardware.org/?probe=02e02dbca5) | Oct 11, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [d773c4faf0](https://linux-hardware.org/?probe=d773c4faf0) | Oct 09, 2023 |
| MACHINIST     | E5-MR9A PRO V1.2            | Desktop     | [668d09e797](https://linux-hardware.org/?probe=668d09e797) | Oct 07, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [4f9d192833](https://linux-hardware.org/?probe=4f9d192833) | Oct 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6ff82127e5](https://linux-hardware.org/?probe=6ff82127e5) | Oct 05, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [f10db8b926](https://linux-hardware.org/?probe=f10db8b926) | Oct 04, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [4c6c3c41b3](https://linux-hardware.org/?probe=4c6c3c41b3) | Oct 03, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [380e23e27d](https://linux-hardware.org/?probe=380e23e27d) | Oct 03, 2023 |
| Intel         | DG41RQ AAE54511-202         | Desktop     | [5d2ec27525](https://linux-hardware.org/?probe=5d2ec27525) | Oct 03, 2023 |
| Lenovo        | ThinkPad E495 20NES07V00    | Notebook    | [935dc10f6b](https://linux-hardware.org/?probe=935dc10f6b) | Sep 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c1a605af33](https://linux-hardware.org/?probe=c1a605af33) | Sep 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6275e5c1d4](https://linux-hardware.org/?probe=6275e5c1d4) | Sep 29, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [e44f45e8d6](https://linux-hardware.org/?probe=e44f45e8d6) | Sep 28, 2023 |
| Acer          | Predator G3-571             | Notebook    | [f301a514ad](https://linux-hardware.org/?probe=f301a514ad) | Sep 27, 2023 |
| Acer          | Predator G3-571             | Notebook    | [06b0300670](https://linux-hardware.org/?probe=06b0300670) | Sep 27, 2023 |
| Lenovo        | ThinkPad T430 2347H6U       | Notebook    | [7fc871cd5e](https://linux-hardware.org/?probe=7fc871cd5e) | Sep 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [73d2dae51c](https://linux-hardware.org/?probe=73d2dae51c) | Sep 26, 2023 |
| ASUSTek       | X550DP                      | Notebook    | [a743f84823](https://linux-hardware.org/?probe=a743f84823) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0531db8cb8](https://linux-hardware.org/?probe=0531db8cb8) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [01b1c1acdb](https://linux-hardware.org/?probe=01b1c1acdb) | Sep 24, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [2edb781d68](https://linux-hardware.org/?probe=2edb781d68) | Sep 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [a9cfc8946d](https://linux-hardware.org/?probe=a9cfc8946d) | Sep 21, 2023 |
| Dell          | Vostro 1310                 | Notebook    | [bc0c23c23c](https://linux-hardware.org/?probe=bc0c23c23c) | Sep 21, 2023 |
| Intel         | NUC13SBBi9 M58736-303       | Mini pc     | [a2a7eacfe6](https://linux-hardware.org/?probe=a2a7eacfe6) | Sep 18, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [bd7a7a6f22](https://linux-hardware.org/?probe=bd7a7a6f22) | Sep 17, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [c8ecd1e0c9](https://linux-hardware.org/?probe=c8ecd1e0c9) | Sep 17, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [bd4081fcfc](https://linux-hardware.org/?probe=bd4081fcfc) | Sep 17, 2023 |
| Dell          | System XPS L502X            | Notebook    | [d3154f94d7](https://linux-hardware.org/?probe=d3154f94d7) | Sep 17, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [8934a85f1f](https://linux-hardware.org/?probe=8934a85f1f) | Sep 16, 2023 |
| ASUSTek       | NAGAMI2                     | Desktop     | [c0e4ce344f](https://linux-hardware.org/?probe=c0e4ce344f) | Sep 14, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [7050f11f50](https://linux-hardware.org/?probe=7050f11f50) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0317b3bcf6](https://linux-hardware.org/?probe=0317b3bcf6) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [37f8406bab](https://linux-hardware.org/?probe=37f8406bab) | Sep 13, 2023 |
| Lenovo        | E41-55 82FJ                 | Notebook    | [20b3dd0858](https://linux-hardware.org/?probe=20b3dd0858) | Sep 13, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [0893eb24cb](https://linux-hardware.org/?probe=0893eb24cb) | Sep 13, 2023 |
| HP            | 240 14 inch G9 Notebook ... | Notebook    | [23652eaf70](https://linux-hardware.org/?probe=23652eaf70) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d4178bc91c](https://linux-hardware.org/?probe=d4178bc91c) | Sep 11, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [4c5091412b](https://linux-hardware.org/?probe=4c5091412b) | Sep 11, 2023 |
| HP            | 2B0C MVB,A                  | All in one  | [95d9e2cb1f](https://linux-hardware.org/?probe=95d9e2cb1f) | Sep 11, 2023 |
| Toshiba       | Satellite M645              | Notebook    | [40c02e9bc9](https://linux-hardware.org/?probe=40c02e9bc9) | Sep 10, 2023 |
| Lenovo        | ThinkPad X220 42872WS       | Notebook    | [9bd18b41ed](https://linux-hardware.org/?probe=9bd18b41ed) | Sep 09, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [c0bbe7d2b4](https://linux-hardware.org/?probe=c0bbe7d2b4) | Sep 09, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [3f247b15c6](https://linux-hardware.org/?probe=3f247b15c6) | Sep 09, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [95d13f26f0](https://linux-hardware.org/?probe=95d13f26f0) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [4e30077177](https://linux-hardware.org/?probe=4e30077177) | Sep 08, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [d5430e9279](https://linux-hardware.org/?probe=d5430e9279) | Sep 08, 2023 |
| Sony          | SVE14A25CLW                 | Notebook    | [9646f55c7d](https://linux-hardware.org/?probe=9646f55c7d) | Sep 08, 2023 |
| Sony          | SVE14A25CLW                 | Notebook    | [3f8a5dcaaf](https://linux-hardware.org/?probe=3f8a5dcaaf) | Sep 08, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [5d575aeb4f](https://linux-hardware.org/?probe=5d575aeb4f) | Sep 06, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [732a32bc98](https://linux-hardware.org/?probe=732a32bc98) | Sep 06, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [9614656d9b](https://linux-hardware.org/?probe=9614656d9b) | Sep 05, 2023 |
| HP            | 82E0                        | Desktop     | [a86ac881df](https://linux-hardware.org/?probe=a86ac881df) | Sep 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [3e2b7d52c5](https://linux-hardware.org/?probe=3e2b7d52c5) | Sep 05, 2023 |
| Lenovo        | ThinkPad T430 2349MPS       | Notebook    | [183e5c528c](https://linux-hardware.org/?probe=183e5c528c) | Sep 03, 2023 |
| Intel         | DG31PR AAD97573-301         | Desktop     | [359e7817c3](https://linux-hardware.org/?probe=359e7817c3) | Sep 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [3143c94134](https://linux-hardware.org/?probe=3143c94134) | Sep 02, 2023 |
| HP            | 245 G7 Notebook PC          | Notebook    | [bb268c3828](https://linux-hardware.org/?probe=bb268c3828) | Sep 02, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [c972b65ed6](https://linux-hardware.org/?probe=c972b65ed6) | Sep 02, 2023 |
| Dell          | Latitude 5430               | Notebook    | [7a9eb9995d](https://linux-hardware.org/?probe=7a9eb9995d) | Sep 02, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [c0030f3b3b](https://linux-hardware.org/?probe=c0030f3b3b) | Sep 01, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [24ad5e2b06](https://linux-hardware.org/?probe=24ad5e2b06) | Aug 31, 2023 |
| Lenovo        | G40-70 20369                | Notebook    | [f3cef329f6](https://linux-hardware.org/?probe=f3cef329f6) | Aug 30, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [bc78db6077](https://linux-hardware.org/?probe=bc78db6077) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [de34a44939](https://linux-hardware.org/?probe=de34a44939) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [776efe803f](https://linux-hardware.org/?probe=776efe803f) | Aug 29, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [78d168c88e](https://linux-hardware.org/?probe=78d168c88e) | Aug 29, 2023 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | Notebook    | [90e0cad295](https://linux-hardware.org/?probe=90e0cad295) | Aug 28, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [9fcb646019](https://linux-hardware.org/?probe=9fcb646019) | Aug 27, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [9ce11e1efa](https://linux-hardware.org/?probe=9ce11e1efa) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [657c08f61f](https://linux-hardware.org/?probe=657c08f61f) | Aug 27, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [cbbaecabb1](https://linux-hardware.org/?probe=cbbaecabb1) | Aug 26, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [b910d52198](https://linux-hardware.org/?probe=b910d52198) | Aug 26, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [658431c5b8](https://linux-hardware.org/?probe=658431c5b8) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5f2a27253a](https://linux-hardware.org/?probe=5f2a27253a) | Aug 21, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5e76f9bfc3](https://linux-hardware.org/?probe=5e76f9bfc3) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4006007a76](https://linux-hardware.org/?probe=4006007a76) | Aug 20, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [21750fb927](https://linux-hardware.org/?probe=21750fb927) | Aug 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [ed75b0702f](https://linux-hardware.org/?probe=ed75b0702f) | Aug 19, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [0af0e7a958](https://linux-hardware.org/?probe=0af0e7a958) | Aug 17, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [65a1f155c0](https://linux-hardware.org/?probe=65a1f155c0) | Aug 17, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [3a916bde7d](https://linux-hardware.org/?probe=3a916bde7d) | Aug 16, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [aeb3f34daa](https://linux-hardware.org/?probe=aeb3f34daa) | Aug 16, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582ZM_... | Notebook    | [b3f31fbc53](https://linux-hardware.org/?probe=b3f31fbc53) | Aug 16, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [8b4200849d](https://linux-hardware.org/?probe=8b4200849d) | Aug 15, 2023 |
| Intel         | DH61CR AAG14064-207         | Desktop     | [25d122723f](https://linux-hardware.org/?probe=25d122723f) | Aug 15, 2023 |
| Intel         | DH61CR AAG14064-207         | Desktop     | [ae4eca1596](https://linux-hardware.org/?probe=ae4eca1596) | Aug 15, 2023 |
| Lenovo        | IdeaPad 1 14ALC7 82R3       | Notebook    | [0766dc4b96](https://linux-hardware.org/?probe=0766dc4b96) | Aug 13, 2023 |
| Lenovo        | IdeaPad 1 14ALC7 82R3       | Notebook    | [6480e1b649](https://linux-hardware.org/?probe=6480e1b649) | Aug 13, 2023 |
| Dell          | G15 5510                    | Notebook    | [3cfac2d234](https://linux-hardware.org/?probe=3cfac2d234) | Aug 12, 2023 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [edd47d65b6](https://linux-hardware.org/?probe=edd47d65b6) | Aug 12, 2023 |
| Acer          | Aspire V5-471P              | Notebook    | [cbd4a63b2e](https://linux-hardware.org/?probe=cbd4a63b2e) | Aug 10, 2023 |
| Dell          | Precision 5530              | Notebook    | [3b10bebb7d](https://linux-hardware.org/?probe=3b10bebb7d) | Aug 10, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7637f0d91d](https://linux-hardware.org/?probe=7637f0d91d) | Aug 06, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [5889bc8dc7](https://linux-hardware.org/?probe=5889bc8dc7) | Aug 06, 2023 |
| COMPUMAX C... | MOBIL                       | Notebook    | [60293c1ac3](https://linux-hardware.org/?probe=60293c1ac3) | Aug 06, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [4afe306798](https://linux-hardware.org/?probe=4afe306798) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [364aa911cf](https://linux-hardware.org/?probe=364aa911cf) | Aug 05, 2023 |
| MSI           | PRO H610M-G WIFI DDR4       | Desktop     | [d8b172537e](https://linux-hardware.org/?probe=d8b172537e) | Aug 04, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [e066712070](https://linux-hardware.org/?probe=e066712070) | Aug 03, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [d0bad7993f](https://linux-hardware.org/?probe=d0bad7993f) | Aug 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [3ea3ff2535](https://linux-hardware.org/?probe=3ea3ff2535) | Jul 31, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [f5cc7a2d00](https://linux-hardware.org/?probe=f5cc7a2d00) | Jul 30, 2023 |
| MSI           | Katana 17 B13VFK            | Notebook    | [8bc597da6e](https://linux-hardware.org/?probe=8bc597da6e) | Jul 29, 2023 |
| HP            | 86F3 00100                  | All in one  | [485fcbfa5d](https://linux-hardware.org/?probe=485fcbfa5d) | Jul 29, 2023 |
| ASRock        | B85M                        | Desktop     | [d69487eb8d](https://linux-hardware.org/?probe=d69487eb8d) | Jul 26, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [5f44d0b1d8](https://linux-hardware.org/?probe=5f44d0b1d8) | Jul 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS15W07    | Notebook    | [6a77133959](https://linux-hardware.org/?probe=6a77133959) | Jul 25, 2023 |
| Google        | Treeya                      | Notebook    | [808e203694](https://linux-hardware.org/?probe=808e203694) | Jul 24, 2023 |
| Google        | Treeya                      | Notebook    | [db2b782253](https://linux-hardware.org/?probe=db2b782253) | Jul 24, 2023 |
| HP            | 86F3 00100                  | All in one  | [26504c2968](https://linux-hardware.org/?probe=26504c2968) | Jul 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d8d58cb5fb](https://linux-hardware.org/?probe=d8d58cb5fb) | Jul 21, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [689b191bae](https://linux-hardware.org/?probe=689b191bae) | Jul 21, 2023 |
| Intel X79     | Unknown                     | Desktop     | [360facd1fb](https://linux-hardware.org/?probe=360facd1fb) | Jul 19, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [1763ff7356](https://linux-hardware.org/?probe=1763ff7356) | Jul 18, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [04dce054f4](https://linux-hardware.org/?probe=04dce054f4) | Jul 17, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [ef2395800e](https://linux-hardware.org/?probe=ef2395800e) | Jul 16, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [c9a21bf55e](https://linux-hardware.org/?probe=c9a21bf55e) | Jul 14, 2023 |
| HP            | 245 G8                      | Notebook    | [07eefc20b0](https://linux-hardware.org/?probe=07eefc20b0) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| MSI           | 970A-G46                    | Desktop     | [09496b3221](https://linux-hardware.org/?probe=09496b3221) | Jul 12, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [e99992afd5](https://linux-hardware.org/?probe=e99992afd5) | Jul 12, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [93d94feca6](https://linux-hardware.org/?probe=93d94feca6) | Jul 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [eccd385af4](https://linux-hardware.org/?probe=eccd385af4) | Jul 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [9cc59dffca](https://linux-hardware.org/?probe=9cc59dffca) | Jul 11, 2023 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [bd1c8f9529](https://linux-hardware.org/?probe=bd1c8f9529) | Jul 11, 2023 |
| HP            | 2820h                       | Desktop     | [ecbafa25c0](https://linux-hardware.org/?probe=ecbafa25c0) | Jul 10, 2023 |
| HP            | 2820h                       | Desktop     | [9d4f48820d](https://linux-hardware.org/?probe=9d4f48820d) | Jul 10, 2023 |
| HP            | Notebook                    | Notebook    | [9242935b2b](https://linux-hardware.org/?probe=9242935b2b) | Jul 10, 2023 |
| AYANEO        | AIR Pro                     | Tablet      | [90413e073a](https://linux-hardware.org/?probe=90413e073a) | Jul 09, 2023 |
| HP            | 304Ah                       | Desktop     | [029412ce85](https://linux-hardware.org/?probe=029412ce85) | Jul 05, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [75dc3bfda0](https://linux-hardware.org/?probe=75dc3bfda0) | Jul 04, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [a7c8848746](https://linux-hardware.org/?probe=a7c8848746) | Jul 03, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [2f5812cb86](https://linux-hardware.org/?probe=2f5812cb86) | Jul 01, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [d0ea6a2d9d](https://linux-hardware.org/?probe=d0ea6a2d9d) | Jun 30, 2023 |
| Dell          | Latitude E5450              | Notebook    | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [ef54ec3027](https://linux-hardware.org/?probe=ef54ec3027) | Jun 30, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| Gigabyte      | H61M-HD2                    | Desktop     | [404728f350](https://linux-hardware.org/?probe=404728f350) | Jun 29, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [aa24aa071b](https://linux-hardware.org/?probe=aa24aa071b) | Jun 28, 2023 |
| PCsmart       | PCSGOB14p-C                 | Notebook    | [a45977461f](https://linux-hardware.org/?probe=a45977461f) | Jun 27, 2023 |
| HP            | 8430 1000                   | All in one  | [cba036b5d2](https://linux-hardware.org/?probe=cba036b5d2) | Jun 26, 2023 |
| ASRock        | H55M                        | Desktop     | [cb9e89e20e](https://linux-hardware.org/?probe=cb9e89e20e) | Jun 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b47fa47ef7](https://linux-hardware.org/?probe=b47fa47ef7) | Jun 23, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [71f5fde47b](https://linux-hardware.org/?probe=71f5fde47b) | Jun 23, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [cc8a15081a](https://linux-hardware.org/?probe=cc8a15081a) | Jun 22, 2023 |
| Dell          | Vostro 1400                 | Notebook    | [7b5011ff7c](https://linux-hardware.org/?probe=7b5011ff7c) | Jun 22, 2023 |
| Dell          | Vostro 1400                 | Notebook    | [c41c17d657](https://linux-hardware.org/?probe=c41c17d657) | Jun 22, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [544b40258b](https://linux-hardware.org/?probe=544b40258b) | Jun 21, 2023 |
| Acer          | Veriton X490G               | Desktop     | [a181339180](https://linux-hardware.org/?probe=a181339180) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [5ff46d41fd](https://linux-hardware.org/?probe=5ff46d41fd) | Jun 18, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [676efbb266](https://linux-hardware.org/?probe=676efbb266) | Jun 18, 2023 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [2fb2088533](https://linux-hardware.org/?probe=2fb2088533) | Jun 17, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [4cc6199522](https://linux-hardware.org/?probe=4cc6199522) | Jun 15, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ddb9fc5a43](https://linux-hardware.org/?probe=ddb9fc5a43) | Jun 14, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [f3b0b03ace](https://linux-hardware.org/?probe=f3b0b03ace) | Jun 12, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [1b8ad811e0](https://linux-hardware.org/?probe=1b8ad811e0) | Jun 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [29d4909dd4](https://linux-hardware.org/?probe=29d4909dd4) | Jun 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [235239b42b](https://linux-hardware.org/?probe=235239b42b) | Jun 11, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| HP            | 82C9                        | Desktop     | [b696990030](https://linux-hardware.org/?probe=b696990030) | Jun 09, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [2f0f8eb596](https://linux-hardware.org/?probe=2f0f8eb596) | Jun 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [baf92c8b36](https://linux-hardware.org/?probe=baf92c8b36) | Jun 08, 2023 |
| HP            | 18EA                        | Desktop     | [d6e48a99e7](https://linux-hardware.org/?probe=d6e48a99e7) | Jun 08, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [42eab3e3af](https://linux-hardware.org/?probe=42eab3e3af) | Jun 08, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [ac292cca00](https://linux-hardware.org/?probe=ac292cca00) | Jun 08, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [5c63c42a5c](https://linux-hardware.org/?probe=5c63c42a5c) | Jun 04, 2023 |
| Acer          | Predator G3-710             | Desktop     | [7193d24262](https://linux-hardware.org/?probe=7193d24262) | Jun 04, 2023 |
| Acer          | Predator G3-710             | Desktop     | [96834ea12b](https://linux-hardware.org/?probe=96834ea12b) | Jun 04, 2023 |
| Acer          | Predator G3-710             | Desktop     | [c200dbb9cf](https://linux-hardware.org/?probe=c200dbb9cf) | Jun 04, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [8ba76b1e88](https://linux-hardware.org/?probe=8ba76b1e88) | Jun 03, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [8f73724b8a](https://linux-hardware.org/?probe=8f73724b8a) | Jun 02, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3de415ea72](https://linux-hardware.org/?probe=3de415ea72) | Jun 01, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [3f08f70d3a](https://linux-hardware.org/?probe=3f08f70d3a) | May 31, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [e091c09373](https://linux-hardware.org/?probe=e091c09373) | May 29, 2023 |
| Gigabyte      | H61M-HD2                    | Desktop     | [7c57f43d4a](https://linux-hardware.org/?probe=7c57f43d4a) | May 29, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [d38a3af9af](https://linux-hardware.org/?probe=d38a3af9af) | May 27, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [bca0574da6](https://linux-hardware.org/?probe=bca0574da6) | May 27, 2023 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [2f5d8e6789](https://linux-hardware.org/?probe=2f5d8e6789) | May 26, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [063077bd52](https://linux-hardware.org/?probe=063077bd52) | May 25, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [776f5c2411](https://linux-hardware.org/?probe=776f5c2411) | May 25, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [e2110ab5da](https://linux-hardware.org/?probe=e2110ab5da) | May 25, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [87a75f9dd9](https://linux-hardware.org/?probe=87a75f9dd9) | May 16, 2023 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [d7503c22b2](https://linux-hardware.org/?probe=d7503c22b2) | May 16, 2023 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [cc42c4e227](https://linux-hardware.org/?probe=cc42c4e227) | May 15, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [ac4be1ce4d](https://linux-hardware.org/?probe=ac4be1ce4d) | May 11, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [53bd721aab](https://linux-hardware.org/?probe=53bd721aab) | May 10, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [1f5654331d](https://linux-hardware.org/?probe=1f5654331d) | May 09, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [96c2411d79](https://linux-hardware.org/?probe=96c2411d79) | May 08, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [6e28d6fd76](https://linux-hardware.org/?probe=6e28d6fd76) | May 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a375533daa](https://linux-hardware.org/?probe=a375533daa) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [fe61386871](https://linux-hardware.org/?probe=fe61386871) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [764f38bb65](https://linux-hardware.org/?probe=764f38bb65) | May 05, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [a00f293aa7](https://linux-hardware.org/?probe=a00f293aa7) | May 04, 2023 |
| Gigabyte      | Z590 VISION G               | Desktop     | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [d29dae3c91](https://linux-hardware.org/?probe=d29dae3c91) | May 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [2dffd7bed6](https://linux-hardware.org/?probe=2dffd7bed6) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [dca12f3f6a](https://linux-hardware.org/?probe=dca12f3f6a) | Apr 29, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [740c70097e](https://linux-hardware.org/?probe=740c70097e) | Apr 29, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [a931ac9451](https://linux-hardware.org/?probe=a931ac9451) | Apr 28, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [7720195dfe](https://linux-hardware.org/?probe=7720195dfe) | Apr 24, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [32546113c8](https://linux-hardware.org/?probe=32546113c8) | Apr 24, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [18fc5f09ed](https://linux-hardware.org/?probe=18fc5f09ed) | Apr 23, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [e3dc4788e7](https://linux-hardware.org/?probe=e3dc4788e7) | Apr 22, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [50408f04cb](https://linux-hardware.org/?probe=50408f04cb) | Apr 22, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [f4578519ad](https://linux-hardware.org/?probe=f4578519ad) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [901b3d11dc](https://linux-hardware.org/?probe=901b3d11dc) | Apr 20, 2023 |
| HP            | G42                         | Notebook    | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [923b3fd46b](https://linux-hardware.org/?probe=923b3fd46b) | Apr 19, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [c4d3eabb55](https://linux-hardware.org/?probe=c4d3eabb55) | Apr 17, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [d532f6fdbd](https://linux-hardware.org/?probe=d532f6fdbd) | Apr 16, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [12bb3d9268](https://linux-hardware.org/?probe=12bb3d9268) | Apr 16, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [337102cd4c](https://linux-hardware.org/?probe=337102cd4c) | Apr 15, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [a817b0fcaf](https://linux-hardware.org/?probe=a817b0fcaf) | Apr 14, 2023 |
| Gigabyte      | H61M-HD2                    | Desktop     | [ea4bae8ef7](https://linux-hardware.org/?probe=ea4bae8ef7) | Apr 13, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [29d92f085a](https://linux-hardware.org/?probe=29d92f085a) | Apr 12, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [7852e88a19](https://linux-hardware.org/?probe=7852e88a19) | Apr 11, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [6e4aea5587](https://linux-hardware.org/?probe=6e4aea5587) | Apr 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [1bc09aed8a](https://linux-hardware.org/?probe=1bc09aed8a) | Apr 10, 2023 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [d478080e54](https://linux-hardware.org/?probe=d478080e54) | Apr 09, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [5d39494c01](https://linux-hardware.org/?probe=5d39494c01) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [1a6e63f6b2](https://linux-hardware.org/?probe=1a6e63f6b2) | Apr 08, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [441d7f391e](https://linux-hardware.org/?probe=441d7f391e) | Apr 08, 2023 |
| ASUSTek       | M4N98TD EVO                 | Desktop     | [a2423b5193](https://linux-hardware.org/?probe=a2423b5193) | Apr 07, 2023 |
| ASUSTek       | M4N98TD EVO                 | Desktop     | [8a2a2cf1ce](https://linux-hardware.org/?probe=8a2a2cf1ce) | Apr 07, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | Notebook    | [29f00590fb](https://linux-hardware.org/?probe=29f00590fb) | Apr 05, 2023 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [b3e9bc2fb0](https://linux-hardware.org/?probe=b3e9bc2fb0) | Apr 04, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [cb94d3ff68](https://linux-hardware.org/?probe=cb94d3ff68) | Apr 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [9f33f20fc4](https://linux-hardware.org/?probe=9f33f20fc4) | Apr 04, 2023 |
| PCSMART S.... | PNTGOB11CPE                 | Notebook    | [874d355cc4](https://linux-hardware.org/?probe=874d355cc4) | Apr 02, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [6d4878cdbf](https://linux-hardware.org/?probe=6d4878cdbf) | Apr 01, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [03da618edb](https://linux-hardware.org/?probe=03da618edb) | Mar 31, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [1dc323a9e9](https://linux-hardware.org/?probe=1dc323a9e9) | Mar 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [18f4d18529](https://linux-hardware.org/?probe=18f4d18529) | Mar 30, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| Lenovo        | ThinkServer TS130           | Desktop     | [2a36fc5043](https://linux-hardware.org/?probe=2a36fc5043) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [5c811e496f](https://linux-hardware.org/?probe=5c811e496f) | Mar 24, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [117d507724](https://linux-hardware.org/?probe=117d507724) | Mar 24, 2023 |
| ASUSTek       | M4N98TD EVO                 | Desktop     | [9cb4b84924](https://linux-hardware.org/?probe=9cb4b84924) | Mar 24, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [8437e47a82](https://linux-hardware.org/?probe=8437e47a82) | Mar 24, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [56d564423e](https://linux-hardware.org/?probe=56d564423e) | Mar 24, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e14a63a1e4](https://linux-hardware.org/?probe=e14a63a1e4) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [592d9de1cb](https://linux-hardware.org/?probe=592d9de1cb) | Mar 23, 2023 |
| HP            | 18E9                        | Desktop     | [2cc6071591](https://linux-hardware.org/?probe=2cc6071591) | Mar 20, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [04ba5a6790](https://linux-hardware.org/?probe=04ba5a6790) | Mar 18, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [fcbb054633](https://linux-hardware.org/?probe=fcbb054633) | Mar 18, 2023 |
| HP            | 1850                        | Desktop     | [c805a3a08f](https://linux-hardware.org/?probe=c805a3a08f) | Mar 17, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [c6f835ae33](https://linux-hardware.org/?probe=c6f835ae33) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [b72b91fd00](https://linux-hardware.org/?probe=b72b91fd00) | Mar 16, 2023 |
| MSI           | H81M-P33                    | Desktop     | [cb3d11f591](https://linux-hardware.org/?probe=cb3d11f591) | Mar 15, 2023 |
| HP            | 1850                        | Desktop     | [c5439b2fea](https://linux-hardware.org/?probe=c5439b2fea) | Mar 15, 2023 |
| ASRock        | G31M-S                      | Desktop     | [7672cc15a2](https://linux-hardware.org/?probe=7672cc15a2) | Mar 13, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [0c5b1ebe0a](https://linux-hardware.org/?probe=0c5b1ebe0a) | Mar 11, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [5371ec61c1](https://linux-hardware.org/?probe=5371ec61c1) | Mar 11, 2023 |
| Biostar       | H61MHV                      | Desktop     | [9f184e6e93](https://linux-hardware.org/?probe=9f184e6e93) | Mar 11, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [bccc889328](https://linux-hardware.org/?probe=bccc889328) | Mar 10, 2023 |
| Lenovo        | ThinkPad X201 36806V4       | Notebook    | [1921dc6d6b](https://linux-hardware.org/?probe=1921dc6d6b) | Mar 09, 2023 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [b960fb0ebf](https://linux-hardware.org/?probe=b960fb0ebf) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Acer          | Aspire X1400                | Desktop     | [195337bbc6](https://linux-hardware.org/?probe=195337bbc6) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [4cb7f38354](https://linux-hardware.org/?probe=4cb7f38354) | Mar 05, 2023 |
| HP            | G42                         | Notebook    | [7dee433139](https://linux-hardware.org/?probe=7dee433139) | Mar 05, 2023 |
| LG Electro... | 22V240 FAB3                 | All in one  | [163c52fd3c](https://linux-hardware.org/?probe=163c52fd3c) | Mar 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| HP            | 806A                        | Desktop     | [66c29ddd8a](https://linux-hardware.org/?probe=66c29ddd8a) | Mar 03, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [81889ddc9c](https://linux-hardware.org/?probe=81889ddc9c) | Mar 02, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [b4be9a72dd](https://linux-hardware.org/?probe=b4be9a72dd) | Feb 28, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [66e63a311d](https://linux-hardware.org/?probe=66e63a311d) | Feb 28, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [e20478d60e](https://linux-hardware.org/?probe=e20478d60e) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [39f48414bc](https://linux-hardware.org/?probe=39f48414bc) | Feb 23, 2023 |
| HP            | 2ADE                        | Desktop     | [b4309c2b06](https://linux-hardware.org/?probe=b4309c2b06) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [cc447f6c07](https://linux-hardware.org/?probe=cc447f6c07) | Feb 19, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [906d11e2a3](https://linux-hardware.org/?probe=906d11e2a3) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [66c33604c4](https://linux-hardware.org/?probe=66c33604c4) | Feb 17, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [4e0e31fd72](https://linux-hardware.org/?probe=4e0e31fd72) | Feb 17, 2023 |
| Lenovo        | IdeaPad Z585 20152          | Notebook    | [e03f8ffaf1](https://linux-hardware.org/?probe=e03f8ffaf1) | Feb 17, 2023 |
| HP            | 18E9                        | Desktop     | [e3461fcb74](https://linux-hardware.org/?probe=e3461fcb74) | Feb 16, 2023 |
| Lenovo        | IdeaPad Z585 20152          | Notebook    | [bc95a7befb](https://linux-hardware.org/?probe=bc95a7befb) | Feb 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [28db1ad82e](https://linux-hardware.org/?probe=28db1ad82e) | Feb 14, 2023 |
| HP            | 1497                        | Desktop     | [b27560d384](https://linux-hardware.org/?probe=b27560d384) | Feb 14, 2023 |
| Dell          | Latitude 3410               | Notebook    | [7ccc73c7bf](https://linux-hardware.org/?probe=7ccc73c7bf) | Feb 13, 2023 |
| Dell          | Latitude 3410               | Notebook    | [374ddffec8](https://linux-hardware.org/?probe=374ddffec8) | Feb 13, 2023 |
| Dell          | Inspiron 1420               | Notebook    | [77c6839e06](https://linux-hardware.org/?probe=77c6839e06) | Feb 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3c8717baf4](https://linux-hardware.org/?probe=3c8717baf4) | Feb 12, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [e4496f3ff8](https://linux-hardware.org/?probe=e4496f3ff8) | Feb 11, 2023 |
| ASUSTek       | X455YA                      | Notebook    | [ba987663d8](https://linux-hardware.org/?probe=ba987663d8) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [5fe8eef781](https://linux-hardware.org/?probe=5fe8eef781) | Feb 09, 2023 |
| HP            | 450                         | Notebook    | [26d3505372](https://linux-hardware.org/?probe=26d3505372) | Feb 06, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [298310a082](https://linux-hardware.org/?probe=298310a082) | Feb 06, 2023 |
| HP            | Pavilion 10 TS              | Notebook    | [522345a482](https://linux-hardware.org/?probe=522345a482) | Feb 05, 2023 |
| PCsmart       | PCSGOB14p-C                 | Notebook    | [9cf7aff807](https://linux-hardware.org/?probe=9cf7aff807) | Feb 05, 2023 |
| Unknown       | X79A                        | Desktop     | [eedea973ca](https://linux-hardware.org/?probe=eedea973ca) | Feb 05, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [edbd391f2d](https://linux-hardware.org/?probe=edbd391f2d) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [42d855f568](https://linux-hardware.org/?probe=42d855f568) | Feb 04, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [00a3607d18](https://linux-hardware.org/?probe=00a3607d18) | Jan 30, 2023 |
| HP            | Pavilion dv6                | Notebook    | [ce950f0a28](https://linux-hardware.org/?probe=ce950f0a28) | Jan 28, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| Acer          | Aspire V5-431               | Notebook    | [abf4a51513](https://linux-hardware.org/?probe=abf4a51513) | Jan 24, 2023 |
| Acer          | Aspire V5-431               | Notebook    | [3da8ac521c](https://linux-hardware.org/?probe=3da8ac521c) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [364a07a435](https://linux-hardware.org/?probe=364a07a435) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [546a896e7f](https://linux-hardware.org/?probe=546a896e7f) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0c65146f4c](https://linux-hardware.org/?probe=0c65146f4c) | Jan 21, 2023 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [d6ea5bde87](https://linux-hardware.org/?probe=d6ea5bde87) | Jan 21, 2023 |
| Lenovo        | IdeaPad Z400 20201          | Notebook    | [9e49dc44eb](https://linux-hardware.org/?probe=9e49dc44eb) | Jan 21, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [bb63f70764](https://linux-hardware.org/?probe=bb63f70764) | Jan 21, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [5973a7db86](https://linux-hardware.org/?probe=5973a7db86) | Jan 21, 2023 |
| HP            | 1000                        | Notebook    | [62ee01ee38](https://linux-hardware.org/?probe=62ee01ee38) | Jan 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| Toshiba       | QOSMIO X505                 | Notebook    | [8b6dfa9517](https://linux-hardware.org/?probe=8b6dfa9517) | Jan 18, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [4a997fa99d](https://linux-hardware.org/?probe=4a997fa99d) | Jan 17, 2023 |
| ASRock        | G965M-S                     | Desktop     | [c1a6d7685b](https://linux-hardware.org/?probe=c1a6d7685b) | Jan 17, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [f9141ba069](https://linux-hardware.org/?probe=f9141ba069) | Jan 17, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [923765c4aa](https://linux-hardware.org/?probe=923765c4aa) | Jan 17, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [b769a91b4f](https://linux-hardware.org/?probe=b769a91b4f) | Jan 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [d569a3f698](https://linux-hardware.org/?probe=d569a3f698) | Jan 15, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | Notebook    | [0ece2f508b](https://linux-hardware.org/?probe=0ece2f508b) | Jan 14, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [b6c21b8d35](https://linux-hardware.org/?probe=b6c21b8d35) | Jan 14, 2023 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [7193100d05](https://linux-hardware.org/?probe=7193100d05) | Jan 14, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [923d70951e](https://linux-hardware.org/?probe=923d70951e) | Jan 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e275cc7891](https://linux-hardware.org/?probe=e275cc7891) | Jan 13, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [d534567752](https://linux-hardware.org/?probe=d534567752) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2349MPS       | Notebook    | [c04ba99a13](https://linux-hardware.org/?probe=c04ba99a13) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3b767cfcef](https://linux-hardware.org/?probe=3b767cfcef) | Jan 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ac7ae437c8](https://linux-hardware.org/?probe=ac7ae437c8) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [7e32892067](https://linux-hardware.org/?probe=7e32892067) | Jan 09, 2023 |
| Dell          | System XPS L502X            | Notebook    | [7d053f0ab1](https://linux-hardware.org/?probe=7d053f0ab1) | Jan 09, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | Notebook    | [2f9ff5256a](https://linux-hardware.org/?probe=2f9ff5256a) | Jan 08, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | Notebook    | [b952438f2c](https://linux-hardware.org/?probe=b952438f2c) | Jan 08, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [5f1d6f0533](https://linux-hardware.org/?probe=5f1d6f0533) | Jan 07, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [892098deef](https://linux-hardware.org/?probe=892098deef) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [dc2a0809aa](https://linux-hardware.org/?probe=dc2a0809aa) | Jan 07, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e7107ee8b4](https://linux-hardware.org/?probe=e7107ee8b4) | Jan 06, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e351ff5e1d](https://linux-hardware.org/?probe=e351ff5e1d) | Jan 05, 2023 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [db8d3007ee](https://linux-hardware.org/?probe=db8d3007ee) | Jan 03, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [f871c26332](https://linux-hardware.org/?probe=f871c26332) | Jan 01, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [217bb0ea0f](https://linux-hardware.org/?probe=217bb0ea0f) | Dec 29, 2022 |
| MSI           | 880GM-E41                   | Desktop     | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fe4ef75450](https://linux-hardware.org/?probe=fe4ef75450) | Dec 21, 2022 |
| Lenovo        | ThinkCentre A62 9486E4S     | Desktop     | [cb7cb7b7d7](https://linux-hardware.org/?probe=cb7cb7b7d7) | Dec 21, 2022 |
| Lenovo        | ThinkCentre A62 9486E4S     | Desktop     | [fcd0306cd3](https://linux-hardware.org/?probe=fcd0306cd3) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [b30bf77d27](https://linux-hardware.org/?probe=b30bf77d27) | Dec 19, 2022 |
| HP            | 2000                        | Notebook    | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [2da9ae7906](https://linux-hardware.org/?probe=2da9ae7906) | Dec 14, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [ed92313ebc](https://linux-hardware.org/?probe=ed92313ebc) | Dec 13, 2022 |
| Notebook      | NL40_50ZU                   | Notebook    | [8e0e4867f8](https://linux-hardware.org/?probe=8e0e4867f8) | Dec 13, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [660fe07867](https://linux-hardware.org/?probe=660fe07867) | Dec 07, 2022 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [4f93d8895e](https://linux-hardware.org/?probe=4f93d8895e) | Dec 06, 2022 |
| HP            | 245 G7                      | Notebook    | [57ed16df1f](https://linux-hardware.org/?probe=57ed16df1f) | Dec 05, 2022 |
| HP            | ProBook 6450b               | Notebook    | [f602f6c0bc](https://linux-hardware.org/?probe=f602f6c0bc) | Dec 05, 2022 |
| HP            | ProBook 6450b               | Notebook    | [de39c86a4c](https://linux-hardware.org/?probe=de39c86a4c) | Dec 05, 2022 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [9b0de50c65](https://linux-hardware.org/?probe=9b0de50c65) | Dec 04, 2022 |
| HP            | 18E9                        | Desktop     | [9086d1a1e5](https://linux-hardware.org/?probe=9086d1a1e5) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | Desktop     | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Dell          | 0TP406                      | Desktop     | [3eceea61d2](https://linux-hardware.org/?probe=3eceea61d2) | Nov 30, 2022 |
| Dell          | 0TP406                      | Desktop     | [d22689331c](https://linux-hardware.org/?probe=d22689331c) | Nov 30, 2022 |
| HP            | 339A                        | Desktop     | [ea5cacd50e](https://linux-hardware.org/?probe=ea5cacd50e) | Nov 29, 2022 |
| Dell          | 0HJ054                      | Desktop     | [0e3d082d5a](https://linux-hardware.org/?probe=0e3d082d5a) | Nov 22, 2022 |
| Lenovo        | IdeaPad U400 09932JU        | Notebook    | [cb5d9871d0](https://linux-hardware.org/?probe=cb5d9871d0) | Nov 22, 2022 |
| ASUSTek       | X442UA                      | Notebook    | [781e1c13ac](https://linux-hardware.org/?probe=781e1c13ac) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b3473a1862](https://linux-hardware.org/?probe=b3473a1862) | Nov 13, 2022 |
| Lenovo        | ThinkCentre M70e 0830AC4    | Desktop     | [8eb9b40274](https://linux-hardware.org/?probe=8eb9b40274) | Nov 10, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [4577f6db37](https://linux-hardware.org/?probe=4577f6db37) | Nov 10, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [1a298da454](https://linux-hardware.org/?probe=1a298da454) | Nov 09, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [962ca3ceb5](https://linux-hardware.org/?probe=962ca3ceb5) | Nov 06, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [2d78dbce09](https://linux-hardware.org/?probe=2d78dbce09) | Nov 03, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [a5d58af861](https://linux-hardware.org/?probe=a5d58af861) | Oct 31, 2022 |
| ASUSTek       | V241DA                      | All in one  | [8a9451cb9c](https://linux-hardware.org/?probe=8a9451cb9c) | Oct 31, 2022 |
| HP            | G72                         | Notebook    | [08a732911d](https://linux-hardware.org/?probe=08a732911d) | Oct 31, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [150c8ac0ac](https://linux-hardware.org/?probe=150c8ac0ac) | Oct 30, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [b132f4c4e9](https://linux-hardware.org/?probe=b132f4c4e9) | Oct 30, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [7e1df59daa](https://linux-hardware.org/?probe=7e1df59daa) | Oct 30, 2022 |
| Biostar       | H61MH                       | Desktop     | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7daabab955](https://linux-hardware.org/?probe=7daabab955) | Oct 27, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [947259d1f6](https://linux-hardware.org/?probe=947259d1f6) | Oct 26, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [1ca42d6148](https://linux-hardware.org/?probe=1ca42d6148) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [aca44a3eab](https://linux-hardware.org/?probe=aca44a3eab) | Oct 20, 2022 |
| HP            | 245 G7                      | Notebook    | [9ec088c343](https://linux-hardware.org/?probe=9ec088c343) | Oct 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ff6d42a3ef](https://linux-hardware.org/?probe=ff6d42a3ef) | Oct 17, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [d8372069b0](https://linux-hardware.org/?probe=d8372069b0) | Oct 16, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [742bc1f2eb](https://linux-hardware.org/?probe=742bc1f2eb) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [a318dbfcc9](https://linux-hardware.org/?probe=a318dbfcc9) | Oct 15, 2022 |
| HP            | Pavilion dv6000 (RG266UA... | Notebook    | [1601ca9a83](https://linux-hardware.org/?probe=1601ca9a83) | Oct 14, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [f785339c71](https://linux-hardware.org/?probe=f785339c71) | Oct 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [4ca8fc6d34](https://linux-hardware.org/?probe=4ca8fc6d34) | Oct 11, 2022 |
| HP            | Pavilion g4                 | Notebook    | [19fe60b14c](https://linux-hardware.org/?probe=19fe60b14c) | Oct 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6edc8b1444](https://linux-hardware.org/?probe=6edc8b1444) | Oct 06, 2022 |
| Lanix         | Neuron V                    | Notebook    | [6bd3c14cc9](https://linux-hardware.org/?probe=6bd3c14cc9) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [45557ec6e6](https://linux-hardware.org/?probe=45557ec6e6) | Oct 03, 2022 |
| HP            | 245 G7 Notebook PC          | Notebook    | [7b92fcd976](https://linux-hardware.org/?probe=7b92fcd976) | Oct 02, 2022 |
| HP            | 245 G7 Notebook PC          | Notebook    | [de8eb62c07](https://linux-hardware.org/?probe=de8eb62c07) | Oct 02, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| HP            | Pavilion 10 TS              | Notebook    | [28003748e6](https://linux-hardware.org/?probe=28003748e6) | Sep 27, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [c0b1c8ad8f](https://linux-hardware.org/?probe=c0b1c8ad8f) | Sep 27, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [56e06deea2](https://linux-hardware.org/?probe=56e06deea2) | Sep 26, 2022 |
| HP            | Pavilion 10 TS              | Notebook    | [1186e5b5d8](https://linux-hardware.org/?probe=1186e5b5d8) | Sep 23, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [acf36b1555](https://linux-hardware.org/?probe=acf36b1555) | Sep 20, 2022 |
| Acer          | Aspire V3-471               | Notebook    | [b04cc2ea05](https://linux-hardware.org/?probe=b04cc2ea05) | Sep 20, 2022 |
| ASUSTek       | X455LAB                     | Notebook    | [4a71131e80](https://linux-hardware.org/?probe=4a71131e80) | Sep 19, 2022 |
| ASUSTek       | X455LAB                     | Notebook    | [f7c5412964](https://linux-hardware.org/?probe=f7c5412964) | Sep 19, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [282f984233](https://linux-hardware.org/?probe=282f984233) | Sep 19, 2022 |
| HP            | 18E7                        | Desktop     | [710a40851e](https://linux-hardware.org/?probe=710a40851e) | Sep 18, 2022 |
| Dell          | Latitude E5420              | Notebook    | [7416dc3fb1](https://linux-hardware.org/?probe=7416dc3fb1) | Sep 18, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [9e4267bcc6](https://linux-hardware.org/?probe=9e4267bcc6) | Sep 15, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [bd9b94b7f8](https://linux-hardware.org/?probe=bd9b94b7f8) | Sep 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a26e1ad502](https://linux-hardware.org/?probe=a26e1ad502) | Sep 15, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [09f7be676c](https://linux-hardware.org/?probe=09f7be676c) | Sep 15, 2022 |
| ASUSTek       | X405UA                      | Notebook    | [3b098addea](https://linux-hardware.org/?probe=3b098addea) | Sep 14, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [8fa2ea42ed](https://linux-hardware.org/?probe=8fa2ea42ed) | Sep 14, 2022 |
| HP            | 1494                        | Desktop     | [0faa06cff4](https://linux-hardware.org/?probe=0faa06cff4) | Sep 12, 2022 |
| HP            | Notebook                    | Notebook    | [2984aef090](https://linux-hardware.org/?probe=2984aef090) | Sep 11, 2022 |
| Dell          | Precision 3510              | Notebook    | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| Acer          | Aspire V3-472P              | Notebook    | [632117c524](https://linux-hardware.org/?probe=632117c524) | Sep 10, 2022 |
| Toshiba       | Satellite L635              | Notebook    | [6d0bbfb576](https://linux-hardware.org/?probe=6d0bbfb576) | Sep 07, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [cc43cdda9a](https://linux-hardware.org/?probe=cc43cdda9a) | Sep 04, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [b635e1c2ba](https://linux-hardware.org/?probe=b635e1c2ba) | Sep 01, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [9735a8ef90](https://linux-hardware.org/?probe=9735a8ef90) | Sep 01, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [8ea91d6b4b](https://linux-hardware.org/?probe=8ea91d6b4b) | Aug 30, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [04474401fc](https://linux-hardware.org/?probe=04474401fc) | Aug 26, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [5351e31366](https://linux-hardware.org/?probe=5351e31366) | Aug 26, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [72ebc08e0c](https://linux-hardware.org/?probe=72ebc08e0c) | Aug 26, 2022 |
| HP            | ENVY 15                     | Notebook    | [db06c354d4](https://linux-hardware.org/?probe=db06c354d4) | Aug 26, 2022 |
| ASUSTek       | TUF B365-PLUS GAMING        | Desktop     | [83e59cf9a5](https://linux-hardware.org/?probe=83e59cf9a5) | Aug 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d64f8a64fa](https://linux-hardware.org/?probe=d64f8a64fa) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [bb928725a6](https://linux-hardware.org/?probe=bb928725a6) | Aug 23, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [97ec1c67e8](https://linux-hardware.org/?probe=97ec1c67e8) | Aug 21, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [8ab7fcb6ff](https://linux-hardware.org/?probe=8ab7fcb6ff) | Aug 21, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [24849a5c23](https://linux-hardware.org/?probe=24849a5c23) | Aug 15, 2022 |
| ASUSTek       | X550DP                      | Notebook    | [ce42b65252](https://linux-hardware.org/?probe=ce42b65252) | Aug 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [298cf4b527](https://linux-hardware.org/?probe=298cf4b527) | Aug 13, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [9321e2df1a](https://linux-hardware.org/?probe=9321e2df1a) | Aug 13, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [e71b330285](https://linux-hardware.org/?probe=e71b330285) | Aug 13, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [03159c112c](https://linux-hardware.org/?probe=03159c112c) | Aug 12, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [f90572b8e2](https://linux-hardware.org/?probe=f90572b8e2) | Aug 11, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7fa92e1cb6](https://linux-hardware.org/?probe=7fa92e1cb6) | Aug 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [08b891334e](https://linux-hardware.org/?probe=08b891334e) | Aug 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fcc8ebfb00](https://linux-hardware.org/?probe=fcc8ebfb00) | Aug 04, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [6d65ac3351](https://linux-hardware.org/?probe=6d65ac3351) | Aug 02, 2022 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [7a12318176](https://linux-hardware.org/?probe=7a12318176) | Aug 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [bdc243bf9f](https://linux-hardware.org/?probe=bdc243bf9f) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [41a0eba80f](https://linux-hardware.org/?probe=41a0eba80f) | Jul 31, 2022 |
| Sony          | VPCEG33FL                   | Notebook    | [6d371d6c32](https://linux-hardware.org/?probe=6d371d6c32) | Jul 31, 2022 |
| HP            | 245 G6                      | Notebook    | [ae4b0ce17e](https://linux-hardware.org/?probe=ae4b0ce17e) | Jul 28, 2022 |
| Sony          | VPCEG33FL                   | Notebook    | [886dfc7777](https://linux-hardware.org/?probe=886dfc7777) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c2fc2235eb](https://linux-hardware.org/?probe=c2fc2235eb) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [f18835e5a1](https://linux-hardware.org/?probe=f18835e5a1) | Jul 27, 2022 |
| Lenovo        | G410 20237                  | Notebook    | [c23a040e55](https://linux-hardware.org/?probe=c23a040e55) | Jul 25, 2022 |
| Sony          | VPCEG33FL                   | Notebook    | [8767e87e9e](https://linux-hardware.org/?probe=8767e87e9e) | Jul 24, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [49af56cbe0](https://linux-hardware.org/?probe=49af56cbe0) | Jul 24, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [acdc35979c](https://linux-hardware.org/?probe=acdc35979c) | Jul 23, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [635f096b70](https://linux-hardware.org/?probe=635f096b70) | Jul 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9863a7ed67](https://linux-hardware.org/?probe=9863a7ed67) | Jul 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [12ef7e83a2](https://linux-hardware.org/?probe=12ef7e83a2) | Jul 20, 2022 |
| Sony          | VPCEH37FJ                   | Notebook    | [1cc39f5c15](https://linux-hardware.org/?probe=1cc39f5c15) | Jul 19, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [68d8843883](https://linux-hardware.org/?probe=68d8843883) | Jul 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [057b18a904](https://linux-hardware.org/?probe=057b18a904) | Jul 16, 2022 |
| ASUSTek       | V241DA                      | All in one  | [51c040abed](https://linux-hardware.org/?probe=51c040abed) | Jul 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| Toshiba       | Satellite M645              | Notebook    | [0149367a4e](https://linux-hardware.org/?probe=0149367a4e) | Jul 12, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [2af75f4744](https://linux-hardware.org/?probe=2af75f4744) | Jul 12, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [ebbc4ebc1d](https://linux-hardware.org/?probe=ebbc4ebc1d) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [d200cc6f06](https://linux-hardware.org/?probe=d200cc6f06) | Jul 11, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [36b1a0480d](https://linux-hardware.org/?probe=36b1a0480d) | Jul 10, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [c7c8a9031c](https://linux-hardware.org/?probe=c7c8a9031c) | Jul 05, 2022 |
| Dell          | Latitude E7450              | Notebook    | [34913911ca](https://linux-hardware.org/?probe=34913911ca) | Jul 05, 2022 |
| Dell          | Latitude E7450              | Notebook    | [60e633e563](https://linux-hardware.org/?probe=60e633e563) | Jul 04, 2022 |
| Dell          | 054KM3 A01                  | Desktop     | [149f746382](https://linux-hardware.org/?probe=149f746382) | Jul 02, 2022 |
| Sony          | VPCEH37FJ                   | Notebook    | [509fe56362](https://linux-hardware.org/?probe=509fe56362) | Jul 01, 2022 |
| HP            | Pavilion g4                 | Notebook    | [3626d9afe4](https://linux-hardware.org/?probe=3626d9afe4) | Jul 01, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [35ca7c4868](https://linux-hardware.org/?probe=35ca7c4868) | Jun 30, 2022 |
| Lenovo        | Z40-75 80DW                 | Notebook    | [1fc3b34132](https://linux-hardware.org/?probe=1fc3b34132) | Jun 27, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [ec991b1524](https://linux-hardware.org/?probe=ec991b1524) | Jun 27, 2022 |
| MSI           | H81M-E33                    | Desktop     | [d79b11186c](https://linux-hardware.org/?probe=d79b11186c) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [8caff7e62e](https://linux-hardware.org/?probe=8caff7e62e) | Jun 25, 2022 |
| Dell          | 0J2J3Y A00                  | Desktop     | [50f015312c](https://linux-hardware.org/?probe=50f015312c) | Jun 23, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [3bbbcaea72](https://linux-hardware.org/?probe=3bbbcaea72) | Jun 20, 2022 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [15d402e40c](https://linux-hardware.org/?probe=15d402e40c) | Jun 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a71adbf68f](https://linux-hardware.org/?probe=a71adbf68f) | Jun 18, 2022 |
| MSI           | H81M-E33                    | Desktop     | [0d2ace0dde](https://linux-hardware.org/?probe=0d2ace0dde) | Jun 16, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Colombia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 132       | 8.79%   |
| Ubuntu 22.04        | 107       | 7.13%   |
| Ubuntu 18.04        | 105       | 7%      |
| Arch Rolling        | 38        | 2.53%   |
| OpenMandriva 4.3    | 37        | 2.47%   |
| Fedora 38           | 36        | 2.4%    |
| Debian 12           | 30        | 2%      |
| Fedora 40           | 28        | 1.87%   |
| Debian 11           | 23        | 1.53%   |
| Zorin 16            | 22        | 1.47%   |
| OpenMandriva 23.08  | 22        | 1.47%   |
| Linux Mint 20.3     | 21        | 1.4%    |
| Ubuntu 24.04        | 20        | 1.33%   |
| Zorin 17            | 19        | 1.27%   |
| Manjaro             | 19        | 1.27%   |
| Fedora 39           | 19        | 1.27%   |
| OpenMandriva 4.2    | 18        | 1.2%    |
| KDE neon 20.04      | 18        | 1.2%    |
| ArcoLinux Rolling   | 17        | 1.13%   |
| Zorin 15            | 16        | 1.07%   |
| Pop!_OS 22.04       | 16        | 1.07%   |
| Ubuntu 19.04        | 15        | 1%      |
| OpenMandriva 23.01  | 15        | 1%      |
| Linux Mint 21.2     | 15        | 1%      |
| Linux Mint 21.1     | 15        | 1%      |
| KDE neon 22.04      | 15        | 1%      |
| OpenMandriva 23.03  | 14        | 0.93%   |
| Linux Mint 20.2     | 14        | 0.93%   |
| Linux Mint 21.3     | 13        | 0.87%   |
| Linux Mint 19.3     | 13        | 0.87%   |
| Arch                | 13        | 0.87%   |
| Fedora 36           | 12        | 0.8%    |
| Fedora 37           | 11        | 0.73%   |
| Ubuntu 19.10        | 10        | 0.67%   |
| Linux Mint 20.1     | 10        | 0.67%   |
| Fedora 35           | 10        | 0.67%   |
| Fedora 34           | 10        | 0.67%   |
| ROSA R10            | 9         | 0.6%    |
| Kubuntu 20.04       | 9         | 0.6%    |
| EndeavourOS Rolling | 9         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 418       | 29.5%   |
| Fedora        | 136       | 9.6%    |
| Linux Mint    | 123       | 8.68%   |
| OpenMandriva  | 115       | 8.12%   |
| Endless       | 77        | 5.43%   |
| Debian        | 68        | 4.8%    |
| Zorin         | 60        | 4.23%   |
| Arch          | 51        | 3.6%    |
| Manjaro       | 47        | 3.32%   |
| KDE neon      | 34        | 2.4%    |
| Pop!_OS       | 33        | 2.33%   |
| Kubuntu       | 28        | 1.98%   |
| ROSA          | 26        | 1.83%   |
| Xubuntu       | 21        | 1.48%   |
| ArcoLinux     | 19        | 1.34%   |
| Kali          | 16        | 1.13%   |
| Elementary    | 15        | 1.06%   |
| openSUSE      | 13        | 0.92%   |
| Ubuntu Unity  | 11        | 0.78%   |
| Lubuntu       | 11        | 0.78%   |
| Nobara        | 10        | 0.71%   |
| EndeavourOS   | 9         | 0.64%   |
| MX            | 7         | 0.49%   |
| Garuda Linux  | 7         | 0.49%   |
| Ubuntu Budgie | 6         | 0.42%   |
| Deepin        | 5         | 0.35%   |
| Parrot        | 4         | 0.28%   |
| Xero          | 3         | 0.21%   |
| Clear Linux   | 3         | 0.21%   |
| Ubuntu MATE   | 2         | 0.14%   |
| RHEL          | 2         | 0.14%   |
| Reborn OS     | 2         | 0.14%   |
| Mageia        | 2         | 0.14%   |
| LMDE          | 2         | 0.14%   |
| LinuxFX       | 2         | 0.14%   |
| Linux Lite    | 2         | 0.14%   |
| Lilidog       | 2         | 0.14%   |
| ChimeraOS     | 2         | 0.14%   |
| CentOS        | 2         | 0.14%   |
| BlackPanther  | 2         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 36        | 2.24%   |
| 5.4.0-42-generic         | 28        | 1.74%   |
| 6.4.11-desktop-1omv2390  | 20        | 1.25%   |
| 5.10.14-desktop-1omv4002 | 18        | 1.12%   |
| 6.5.0-35-generic         | 17        | 1.06%   |
| 5.8.0-14-generic         | 16        | 1%      |
| 6.1.1-desktop-1omv2290   | 15        | 0.93%   |
| 6.2.6-desktop-1omv2390   | 14        | 0.87%   |
| 5.4.0-58-generic         | 14        | 0.87%   |
| 5.4.0-19-generic         | 12        | 0.75%   |
| 5.4.0-48-generic         | 9         | 0.56%   |
| 5.3.0-46-generic         | 9         | 0.56%   |
| 5.15.0-56-generic        | 9         | 0.56%   |
| 5.15.0-47-generic        | 9         | 0.56%   |
| 4.18.0-15-generic        | 9         | 0.56%   |
| 6.8.0-45-generic         | 8         | 0.5%    |
| 5.15.0-91-generic        | 8         | 0.5%    |
| 5.15.0-48-generic        | 8         | 0.5%    |
| 4.18.0-25-generic        | 8         | 0.5%    |
| 6.8.0-41-generic         | 7         | 0.44%   |
| 6.5.0-10-generic         | 7         | 0.44%   |
| 6.2.0-26-generic         | 7         | 0.44%   |
| 5.8.0-43-generic         | 7         | 0.44%   |
| 5.4.0-37-generic         | 7         | 0.44%   |
| 5.4.0-31-generic         | 7         | 0.44%   |
| 5.3.0-28-generic         | 7         | 0.44%   |
| 5.15.0-88-generic        | 7         | 0.44%   |
| 5.15.0-46-generic        | 7         | 0.44%   |
| 5.11.0-35-generic        | 7         | 0.44%   |
| 5.0.0-37-generic         | 7         | 0.44%   |
| 6.8.0-49-generic         | 6         | 0.37%   |
| 6.8.0-40-generic         | 6         | 0.37%   |
| 6.5.0-14-generic         | 6         | 0.37%   |
| 6.1.0-23-amd64           | 6         | 0.37%   |
| 6.1.0-18-amd64           | 6         | 0.37%   |
| 5.19.0-35-generic        | 6         | 0.37%   |
| 5.15.0-60-generic        | 6         | 0.37%   |
| 5.13.0-40-generic        | 6         | 0.37%   |
| 5.13.0-30-generic        | 6         | 0.37%   |
| 5.11.0-34-generic        | 6         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 196       | 12.66%  |
| 5.15.0  | 136       | 8.79%   |
| 6.5.0   | 68        | 4.39%   |
| 4.15.0  | 66        | 4.26%   |
| 5.8.0   | 53        | 3.42%   |
| 5.3.0   | 51        | 3.29%   |
| 5.0.0   | 48        | 3.1%    |
| 6.8.0   | 46        | 2.97%   |
| 5.11.0  | 43        | 2.78%   |
| 4.18.0  | 41        | 2.65%   |
| 6.2.0   | 40        | 2.58%   |
| 5.13.0  | 39        | 2.52%   |
| 5.16.7  | 36        | 2.33%   |
| 6.1.0   | 34        | 2.2%    |
| 5.19.0  | 32        | 2.07%   |
| 5.10.0  | 26        | 1.68%   |
| 6.4.11  | 20        | 1.29%   |
| 5.10.14 | 18        | 1.16%   |
| 6.1.1   | 16        | 1.03%   |
| 6.2.6   | 14        | 0.9%    |
| 4.19.0  | 8         | 0.52%   |
| 6.8.11  | 7         | 0.45%   |
| 6.6.9   | 7         | 0.45%   |
| 6.6.2   | 7         | 0.45%   |
| 6.8.7   | 6         | 0.39%   |
| 6.9.3   | 5         | 0.32%   |
| 6.9.12  | 5         | 0.32%   |
| 6.7.4   | 5         | 0.32%   |
| 6.5.7   | 5         | 0.32%   |
| 6.5.6   | 5         | 0.32%   |
| 6.5.5   | 5         | 0.32%   |
| 6.4.8   | 5         | 0.32%   |
| 6.4.14  | 5         | 0.32%   |
| 6.10.11 | 5         | 0.32%   |
| 5.10.74 | 5         | 0.32%   |
| 4.9.60  | 5         | 0.32%   |
| 4.4.0   | 5         | 0.32%   |
| 6.8.5   | 4         | 0.26%   |
| 6.3.8   | 4         | 0.26%   |
| 6.3.5   | 4         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 205       | 13.45%  |
| 5.15    | 153       | 10.04%  |
| 6.5     | 91        | 5.97%   |
| 6.1     | 79        | 5.18%   |
| 6.8     | 67        | 4.4%    |
| 6.2     | 67        | 4.4%    |
| 5.10    | 67        | 4.4%    |
| 4.15    | 66        | 4.33%   |
| 5.8     | 64        | 4.2%    |
| 5.3     | 56        | 3.67%   |
| 5.13    | 51        | 3.35%   |
| 5.11    | 49        | 3.22%   |
| 5.0     | 49        | 3.22%   |
| 6.4     | 47        | 3.08%   |
| 4.18    | 44        | 2.89%   |
| 5.16    | 43        | 2.82%   |
| 6.6     | 38        | 2.49%   |
| 5.19    | 37        | 2.43%   |
| 6.9     | 24        | 1.57%   |
| 6.10    | 24        | 1.57%   |
| 6.3     | 17        | 1.12%   |
| 4.9     | 17        | 1.12%   |
| 5.14    | 16        | 1.05%   |
| 6.0     | 15        | 0.98%   |
| 5.6     | 15        | 0.98%   |
| 6.7     | 14        | 0.92%   |
| 6.11    | 14        | 0.92%   |
| 5.17    | 14        | 0.92%   |
| 5.18    | 11        | 0.72%   |
| 5.9     | 10        | 0.66%   |
| 5.12    | 9         | 0.59%   |
| 4.19    | 9         | 0.59%   |
| 5.7     | 8         | 0.52%   |
| 6.12    | 6         | 0.39%   |
| 4.4     | 5         | 0.33%   |
| 5.5     | 4         | 0.26%   |
| 4.13    | 4         | 0.26%   |
| 5.1     | 3         | 0.2%    |
| 4.12    | 3         | 0.2%    |
| 5.2     | 2         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1334      | 98.09%  |
| i686    | 23        | 1.69%   |
| aarch64 | 3         | 0.22%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 663       | 46.72%  |
| KDE5             | 231       | 16.28%  |
| Unknown          | 146       | 10.29%  |
| XFCE             | 100       | 7.05%   |
| X-Cinnamon       | 87        | 6.13%   |
| KDE              | 28        | 1.97%   |
| MATE             | 23        | 1.62%   |
| KDE6             | 22        | 1.55%   |
| Pantheon         | 15        | 1.06%   |
| LXQt             | 13        | 0.92%   |
| KDE4             | 13        | 0.92%   |
| Cinnamon         | 13        | 0.92%   |
| Unity            | 11        | 0.78%   |
| i3               | 9         | 0.63%   |
| Budgie           | 9         | 0.63%   |
| Deepin           | 7         | 0.49%   |
| LXDE             | 5         | 0.35%   |
| Endless:GNOME    | 4         | 0.28%   |
| Hyprland         | 3         | 0.21%   |
| GNOME Classic    | 3         | 0.21%   |
| bspwm            | 3         | 0.21%   |
| lightdm-xsession | 2         | 0.14%   |
| awesome          | 2         | 0.14%   |
| ubuntu=GNOME     | 1         | 0.07%   |
| ICEWM            | 1         | 0.07%   |
| GNOME Flashback  | 1         | 0.07%   |
| Enlightenment    | 1         | 0.07%   |
| dwm              | 1         | 0.07%   |
| DDE              | 1         | 0.07%   |
| BunsenLabs       | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 948       | 67.23%  |
| Wayland | 357       | 25.32%  |
| Unknown | 91        | 6.45%   |
| Tty     | 14        | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 700       | 49.75%  |
| SDDM    | 214       | 15.21%  |
| GDM3    | 188       | 13.36%  |
| LightDM | 143       | 10.16%  |
| GDM     | 127       | 9.03%   |
| TDM     | 20        | 1.42%   |
| KDM     | 12        | 0.85%   |
| LXDM    | 2         | 0.14%   |
| SLiM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_CO      | 661       | 47.05%  |
| en_US      | 394       | 28.04%  |
| Unknown    | 149       | 10.6%   |
| es_ES      | 102       | 7.26%   |
| es_MX      | 37        | 2.63%   |
| C          | 23        | 1.64%   |
| en_GB      | 6         | 0.43%   |
| pt_BR      | 3         | 0.21%   |
| es_VE      | 3         | 0.21%   |
| es_PE      | 3         | 0.21%   |
| es_AR      | 3         | 0.21%   |
| fr_FR      | 2         | 0.14%   |
| es_EC      | 2         | 0.14%   |
| es_DO      | 2         | 0.14%   |
| en_AU      | 2         | 0.14%   |
| pt_PT      | 1         | 0.07%   |
| pl_PL      | 1         | 0.07%   |
| it_IT      | 1         | 0.07%   |
| es_US      | 1         | 0.07%   |
| es_ES.UTF8 | 1         | 0.07%   |
| es_CO.UTF8 | 1         | 0.07%   |
| es_CL      | 1         | 0.07%   |
| es_BO      | 1         | 0.07%   |
| en_CA      | 1         | 0.07%   |
| en         | 1         | 0.07%   |
| de_DE      | 1         | 0.07%   |
| cs_CZ      | 1         | 0.07%   |
| C.UTF8     | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 731       | 52.67%  |
| BIOS | 657       | 47.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 993       | 70.58%  |
| Btrfs   | 167       | 11.87%  |
| Overlay | 106       | 7.53%   |
| Tmpfs   | 67        | 4.76%   |
| Unknown | 47        | 3.34%   |
| Xfs     | 18        | 1.28%   |
| Zfs     | 5         | 0.36%   |
| Ext2    | 2         | 0.14%   |
| F2fs    | 1         | 0.07%   |
| Ext3    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 728       | 52.45%  |
| GPT     | 517       | 37.25%  |
| MBR     | 143       | 10.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1215      | 87.16%  |
| Yes       | 179       | 12.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 941       | 67.7%   |
| Yes       | 449       | 32.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ASUSTek Computer             | 300       | 22.06%  |
| Hewlett-Packard              | 261       | 19.19%  |
| Lenovo                       | 201       | 14.78%  |
| Dell                         | 109       | 8.01%   |
| Acer                         | 90        | 6.62%   |
| Gigabyte Technology          | 66        | 4.85%   |
| MSI                          | 62        | 4.56%   |
| ASRock                       | 37        | 2.72%   |
| Toshiba                      | 34        | 2.5%    |
| Apple                        | 33        | 2.43%   |
| Intel                        | 26        | 1.91%   |
| HUAWEI                       | 16        | 1.18%   |
| Samsung Electronics          | 15        | 1.1%    |
| Sony                         | 13        | 0.96%   |
| Unknown                      | 10        | 0.74%   |
| Compumax Computer            | 9         | 0.66%   |
| ECS                          | 8         | 0.59%   |
| Biostar                      | 8         | 0.59%   |
| PCsmart                      | 7         | 0.51%   |
| Pegatron                     | 5         | 0.37%   |
| Notebook                     | 5         | 0.37%   |
| Foxconn                      | 5         | 0.37%   |
| Google                       | 3         | 0.22%   |
| Supermicro                   | 2         | 0.15%   |
| Raspberry Pi Foundation      | 2         | 0.15%   |
| MACHINIST                    | 2         | 0.15%   |
| Gateway                      | 2         | 0.15%   |
| Framework                    | 2         | 0.15%   |
| VIT                          | 1         | 0.07%   |
| TYAN Computer                | 1         | 0.07%   |
| Timi                         | 1         | 0.07%   |
| Quanta                       | 1         | 0.07%   |
| PCSMART S.A.S.               | 1         | 0.07%   |
| PCChips                      | 1         | 0.07%   |
| ONDA                         | 1         | 0.07%   |
| Nvidia                       | 1         | 0.07%   |
| MPS Mayorista de Colombia SA | 1         | 0.07%   |
| Microsoft                    | 1         | 0.07%   |
| LG Electronics               | 1         | 0.07%   |
| Lanix                        | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 15        | 1.1%    |
| ASUS Vivobook Go E1504FA_E1504FA         | 13        | 0.96%   |
| HP Laptop 15-db0xxx                      | 12        | 0.88%   |
| HP Notebook                              | 8         | 0.59%   |
| Gigabyte B450M DS3H                      | 8         | 0.59%   |
| Compumax ONIX-CEL-0001                   | 8         | 0.59%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 7         | 0.51%   |
| MSI MS-7817                              | 6         | 0.44%   |
| Lenovo IdeaPad 320-15ABR 80XS            | 6         | 0.44%   |
| HP Laptop 15-ef2xxx                      | 6         | 0.44%   |
| HP Laptop 14-cf2xxx                      | 6         | 0.44%   |
| ASUS VivoBook_ASUSLaptop X1504ZA_X1504ZA | 6         | 0.44%   |
| Samsung 300E4C/300E5C/300E7C             | 5         | 0.37%   |
| HP Laptop 14-cm1xxx                      | 5         | 0.37%   |
| HP Laptop 14-bs0xx                       | 5         | 0.37%   |
| HP 245 G6                                | 5         | 0.37%   |
| Dell Vostro 3400                         | 5         | 0.37%   |
| ASUS VivoBook_ASUSLaptop X512FB_X512FB   | 5         | 0.37%   |
| ASUS VivoBook_ASUSLaptop X415JA_X415JA   | 5         | 0.37%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA  | 5         | 0.37%   |
| ASUS All Series                          | 5         | 0.37%   |
| Acer Aspire 4750                         | 5         | 0.37%   |
| MSI MS-7309                              | 4         | 0.29%   |
| Lenovo IdeaPad S340-14API 81NB           | 4         | 0.29%   |
| Lenovo IdeaPad 110-14IBR 80T6            | 4         | 0.29%   |
| Lenovo G40-45 80E1                       | 4         | 0.29%   |
| HUAWEI NBLB-WAX9N                        | 4         | 0.29%   |
| HP ProBook 440 G7                        | 4         | 0.29%   |
| HP Pavilion g4                           | 4         | 0.29%   |
| HP Laptop 15-da0xxx                      | 4         | 0.29%   |
| HP G42                                   | 4         | 0.29%   |
| HP 245 G7                                | 4         | 0.29%   |
| HP 14                                    | 4         | 0.29%   |
| Gigabyte H81M-H                          | 4         | 0.29%   |
| Dell XPS 15 9550                         | 4         | 0.29%   |
| ASUS ZenBook UX431DA_UM431DA             | 4         | 0.29%   |
| ASUS X455LJ                              | 4         | 0.29%   |
| ASUS PRIME B450M-A II                    | 4         | 0.29%   |
| ASUS PRIME A320M-K                       | 4         | 0.29%   |
| ASRock Wolfdale1333-D667                 | 4         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUS VivoBook          | 107       | 7.87%   |
| Lenovo IdeaPad         | 72        | 5.29%   |
| Acer Aspire            | 58        | 4.26%   |
| HP Laptop              | 54        | 3.97%   |
| Lenovo ThinkPad        | 50        | 3.68%   |
| HP Pavilion            | 45        | 3.31%   |
| Dell Inspiron          | 33        | 2.43%   |
| ASUS PRIME             | 31        | 2.28%   |
| Toshiba Satellite      | 27        | 1.99%   |
| HP ProBook             | 27        | 1.99%   |
| HP Compaq              | 26        | 1.91%   |
| Dell Latitude          | 23        | 1.69%   |
| Dell Vostro            | 17        | 1.25%   |
| ASUS TUF               | 17        | 1.25%   |
| Acer Nitro             | 16        | 1.18%   |
| ASUS ROG               | 15        | 1.1%    |
| Unknown                | 15        | 1.1%    |
| HP 245                 | 14        | 1.03%   |
| Dell OptiPlex          | 12        | 0.88%   |
| Lenovo ThinkCentre     | 11        | 0.81%   |
| ASUS ZenBook           | 11        | 0.81%   |
| Gigabyte B450M         | 9         | 0.66%   |
| ASUS ASUS              | 9         | 0.66%   |
| HP Notebook            | 8         | 0.59%   |
| HP EliteBook           | 8         | 0.59%   |
| Dell XPS               | 8         | 0.59%   |
| Compumax ONIX-CEL-0001 | 8         | 0.59%   |
| Lenovo Yoga            | 7         | 0.51%   |
| HP ProDesk             | 7         | 0.51%   |
| HP ENVY                | 7         | 0.51%   |
| HP 240                 | 7         | 0.51%   |
| MSI MS-7817            | 6         | 0.44%   |
| HP All-in-One          | 6         | 0.44%   |
| Samsung 300E4C         | 5         | 0.37%   |
| Lenovo IdeaCentre      | 5         | 0.37%   |
| Dell Precision         | 5         | 0.37%   |
| ASUS All               | 5         | 0.37%   |
| MSI MS-7309            | 4         | 0.29%   |
| Lenovo ThinkBook       | 4         | 0.29%   |
| Lenovo Legion          | 4         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 132       | 9.71%   |
| 2019    | 131       | 9.63%   |
| 2020    | 129       | 9.49%   |
| 2012    | 118       | 8.68%   |
| 2017    | 105       | 7.72%   |
| 2021    | 94        | 6.91%   |
| 2013    | 89        | 6.54%   |
| 2010    | 81        | 5.96%   |
| 2011    | 74        | 5.44%   |
| 2014    | 71        | 5.22%   |
| 2015    | 68        | 5%      |
| 2009    | 48        | 3.53%   |
| 2022    | 47        | 3.46%   |
| 2016    | 46        | 3.38%   |
| 2023    | 39        | 2.87%   |
| 2008    | 38        | 2.79%   |
| 2007    | 26        | 1.91%   |
| 2006    | 14        | 1.03%   |
| 2024    | 4         | 0.29%   |
| Unknown | 3         | 0.22%   |
| 2005    | 2         | 0.15%   |
| 2003    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 907       | 66.69%  |
| Desktop        | 371       | 27.28%  |
| All in one     | 40        | 2.94%   |
| Convertible    | 20        | 1.47%   |
| Tablet         | 10        | 0.74%   |
| Mini pc        | 5         | 0.37%   |
| Server         | 4         | 0.29%   |
| System on chip | 3         | 0.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1243      | 90.8%   |
| Enabled  | 126       | 9.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1357      | 99.78%  |
| Yes  | 3         | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 415       | 30.09%  |
| 3.01-4.0    | 304       | 22.04%  |
| 8.01-16.0   | 274       | 19.87%  |
| 16.01-24.0  | 174       | 12.62%  |
| 32.01-64.0  | 77        | 5.58%   |
| 1.01-2.0    | 56        | 4.06%   |
| 2.01-3.0    | 29        | 2.1%    |
| 24.01-32.0  | 24        | 1.74%   |
| 64.01-256.0 | 18        | 1.31%   |
| 0.51-1.0    | 8         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 463       | 30.78%  |
| 2.01-3.0   | 435       | 28.92%  |
| 4.01-8.0   | 228       | 15.16%  |
| 3.01-4.0   | 228       | 15.16%  |
| 0.51-1.0   | 75        | 4.99%   |
| 8.01-16.0  | 64        | 4.26%   |
| 0.01-0.5   | 5         | 0.33%   |
| 16.01-24.0 | 4         | 0.27%   |
| 24.01-32.0 | 2         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 974       | 69.97%  |
| 2      | 301       | 21.62%  |
| 3      | 73        | 5.24%   |
| 4      | 20        | 1.44%   |
| 5      | 12        | 0.86%   |
| 6      | 6         | 0.43%   |
| 8      | 3         | 0.22%   |
| 9      | 1         | 0.07%   |
| 7      | 1         | 0.07%   |
| 0      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 943       | 68.93%  |
| Yes       | 425       | 31.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1138      | 83.49%  |
| No        | 225       | 16.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1128      | 82.58%  |
| No        | 238       | 17.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 900       | 65.79%  |
| No        | 468       | 34.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Colombia | 1360      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Bogotá          | 557       | 39.01%  |
| Medellín        | 213       | 14.92%  |
| Santiago de Cali | 117       | 8.19%   |
| Barranquilla     | 66        | 4.62%   |
| Bucaramanga      | 57        | 3.99%   |
| Pereira          | 40        | 2.8%    |
| Cartagena        | 24        | 1.68%   |
| Manizales        | 20        | 1.4%    |
| Ibague           | 18        | 1.26%   |
| Villavicencio    | 15        | 1.05%   |
| Pasto            | 15        | 1.05%   |
| Cúcuta          | 15        | 1.05%   |
| Tunja            | 14        | 0.98%   |
| Santa Marta      | 14        | 0.98%   |
| Popayán         | 13        | 0.91%   |
| Envigado         | 11        | 0.77%   |
| Chia             | 11        | 0.77%   |
| Armenia          | 11        | 0.77%   |
| Neiva            | 10        | 0.7%    |
| Valledupar       | 9         | 0.63%   |
| Montería        | 9         | 0.63%   |
| Bello            | 9         | 0.63%   |
| Fusagasuga       | 8         | 0.56%   |
| Rionegro         | 6         | 0.42%   |
| Palmira          | 6         | 0.42%   |
| Madrid           | 6         | 0.42%   |
| Zipaquirá       | 4         | 0.28%   |
| Yopal            | 4         | 0.28%   |
| Floridablanca    | 4         | 0.28%   |
| Duitama          | 4         | 0.28%   |
| Tuluá           | 3         | 0.21%   |
| Soacha           | 3         | 0.21%   |
| Sincelejo        | 3         | 0.21%   |
| Ocaña           | 3         | 0.21%   |
| Los Patios       | 3         | 0.21%   |
| Lorica           | 3         | 0.21%   |
| Jamundi          | 3         | 0.21%   |
| Ipiales          | 3         | 0.21%   |
| Barrancabermeja  | 3         | 0.21%   |
| Soledad          | 2         | 0.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 276       | 372    | 14.8%   |
| WDC                         | 248       | 331    | 13.3%   |
| Toshiba                     | 221       | 276    | 11.85%  |
| Samsung Electronics         | 139       | 188    | 7.45%   |
| Kingston                    | 124       | 192    | 6.65%   |
| SanDisk                     | 91        | 125    | 4.88%   |
| Hitachi                     | 86        | 106    | 4.61%   |
| Crucial                     | 75        | 92     | 4.02%   |
| A-DATA Technology           | 68        | 81     | 3.65%   |
| Unknown                     | 50        | 61     | 2.68%   |
| Intel                       | 50        | 58     | 2.68%   |
| HGST                        | 50        | 60     | 2.68%   |
| SK hynix                    | 39        | 48     | 2.09%   |
| Micron Technology           | 38        | 40     | 2.04%   |
| Maxtor                      | 21        | 23     | 1.13%   |
| Realtek Semiconductor       | 19        | 21     | 1.02%   |
| Apple                       | 19        | 27     | 1.02%   |
| China                       | 17        | 18     | 0.91%   |
| Kingston Technology Company | 14        | 19     | 0.75%   |
| Silicon Motion              | 11        | 15     | 0.59%   |
| Phison                      | 11        | 17     | 0.59%   |
| Patriot                     | 11        | 12     | 0.59%   |
| Micron/Crucial Technology   | 11        | 14     | 0.59%   |
| Lexar                       | 11        | 11     | 0.59%   |
| KIOXIA                      | 10        | 11     | 0.54%   |
| ADATA Technology            | 10        | 11     | 0.54%   |
| Team                        | 9         | 10     | 0.48%   |
| PNY                         | 9         | 12     | 0.48%   |
| JMicron Technology          | 9         | 9      | 0.48%   |
| Gigabyte Technology         | 8         | 9      | 0.43%   |
| Hewlett-Packard             | 7         | 9      | 0.38%   |
| Fujitsu                     | 7         | 7      | 0.38%   |
| SPCC                        | 6         | 10     | 0.32%   |
| Phison Electronics          | 6         | 6      | 0.32%   |
| XrayDisk                    | 5         | 5      | 0.27%   |
| XPG                         | 5         | 6      | 0.27%   |
| Union Memory                | 4         | 4      | 0.21%   |
| KingSpec                    | 4         | 4      | 0.21%   |
| Unknown                     | 4         | 5      | 0.21%   |
| Transcend                   | 3         | 4      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                       | 51        | 2.61%   |
| Toshiba MQ04ABF100 1TB                               | 45        | 2.3%    |
| Toshiba DT01ACA100 1TB                               | 37        | 1.89%   |
| Kingston SA400S37240G 240GB SSD                      | 31        | 1.59%   |
| Toshiba MQ01ABF050 500GB                             | 29        | 1.48%   |
| Toshiba MQ01ABD100 1TB                               | 25        | 1.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 23        | 1.18%   |
| Crucial CT240BX500SSD1 240GB                         | 22        | 1.13%   |
| Seagate ST500LT012-1DG142 500GB                      | 20        | 1.02%   |
| Intel SSDPEKNU512GZ 512GB                            | 19        | 0.97%   |
| Kingston SA400S37480G 480GB SSD                      | 16        | 0.82%   |
| Kingston SA400S37120G 120GB SSD                      | 15        | 0.77%   |
| Crucial CT1000BX500SSD1 1TB                          | 14        | 0.72%   |
| Toshiba DT01ACA050 500GB                             | 13        | 0.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 13        | 0.67%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 12        | 0.61%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 12        | 0.61%   |
| HGST HTS541010A9E680 1TB                             | 12        | 0.61%   |
| Unknown MMC Card  64GB                               | 11        | 0.56%   |
| Toshiba HDWD110 1TB                                  | 11        | 0.56%   |
| SanDisk NVMe SSD Drive 512GB                         | 11        | 0.56%   |
| Unknown SD/MMC/MS PRO 128GB                          | 10        | 0.51%   |
| Toshiba DT01ACA200 2TB                               | 10        | 0.51%   |
| Seagate ST500LT012-9WS142 500GB                      | 10        | 0.51%   |
| A-DATA SU650 120GB SSD                               | 10        | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 9         | 0.46%   |
| Seagate ST2000LM007-1R8174 2TB                       | 9         | 0.46%   |
| Seagate ST1000DM010-2EP102 1TB                       | 9         | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 9         | 0.46%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 9         | 0.46%   |
| Kingston SV300S37A120G 120GB SSD                     | 9         | 0.46%   |
| HGST HTS545050A7E680 500GB                           | 9         | 0.46%   |
| HGST HTS541010B7E610 1TB                             | 9         | 0.46%   |
| Crucial CT500MX500SSD1 500GB                         | 9         | 0.46%   |
| Seagate ST500DM002-1BD142 500GB                      | 8         | 0.41%   |
| SanDisk NVMe SSD Drive 256GB                         | 8         | 0.41%   |
| SanDisk NVMe SSD Drive 1TB                           | 8         | 0.41%   |
| Kingston Company SNV2S1000G 1TB                      | 8         | 0.41%   |
| Hitachi HDS721050CLA362 500GB                        | 8         | 0.41%   |
| Crucial CT480BX500SSD1 480GB                         | 8         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 273       | 366    | 29.74%  |
| Toshiba             | 213       | 266    | 23.2%   |
| WDC                 | 210       | 276    | 22.88%  |
| Hitachi             | 86        | 106    | 9.37%   |
| HGST                | 50        | 60     | 5.45%   |
| Samsung Electronics | 24        | 30     | 2.61%   |
| Maxtor              | 21        | 23     | 2.29%   |
| Unknown             | 10        | 12     | 1.09%   |
| JMicron Technology  | 7         | 7      | 0.76%   |
| Fujitsu             | 7         | 7      | 0.76%   |
| Apple               | 7         | 10     | 0.76%   |
| SAGE                | 2         | 1      | 0.22%   |
| Hewlett-Packard     | 2         | 3      | 0.22%   |
| XrayDisk            | 1         | 1      | 0.11%   |
| Phison              | 1         | 2      | 0.11%   |
| Min Yi U            | 1         | 1      | 0.11%   |
| Inateck             | 1         | 1      | 0.11%   |
| IBM/Hitachi         | 1         | 1      | 0.11%   |
| ExcelStor           | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 103       | 158    | 22.59%  |
| Crucial             | 65        | 81     | 14.25%  |
| A-DATA Technology   | 59        | 72     | 12.94%  |
| Samsung Electronics | 36        | 43     | 7.89%   |
| SanDisk             | 28        | 32     | 6.14%   |
| WDC                 | 19        | 31     | 4.17%   |
| China               | 16        | 17     | 3.51%   |
| Lexar               | 11        | 11     | 2.41%   |
| Patriot             | 10        | 11     | 2.19%   |
| Team                | 8         | 9      | 1.75%   |
| PNY                 | 8         | 11     | 1.75%   |
| Apple               | 8         | 8      | 1.75%   |
| Toshiba             | 7         | 8      | 1.54%   |
| Micron Technology   | 7         | 7      | 1.54%   |
| Intel               | 7         | 8      | 1.54%   |
| Gigabyte Technology | 7         | 8      | 1.54%   |
| SPCC                | 6         | 10     | 1.32%   |
| SK hynix            | 6         | 11     | 1.32%   |
| KingSpec            | 4         | 4      | 0.88%   |
| Unknown             | 3         | 3      | 0.66%   |
| Transcend           | 3         | 4      | 0.66%   |
| LITEONIT            | 3         | 3      | 0.66%   |
| LITEON              | 3         | 4      | 0.66%   |
| KingDian            | 3         | 3      | 0.66%   |
| XrayDisk            | 2         | 2      | 0.44%   |
| Seagate             | 2         | 3      | 0.44%   |
| Netac               | 2         | 2      | 0.44%   |
| Hewlett-Packard     | 2         | 2      | 0.44%   |
| DTECHCO             | 2         | 4      | 0.44%   |
| Corsair             | 2         | 5      | 0.44%   |
| Zheino              | 1         | 1      | 0.22%   |
| XSTAR               | 1         | 1      | 0.22%   |
| USB3.0              | 1         | 1      | 0.22%   |
| Timetec             | 1         | 1      | 0.22%   |
| SATAFIRM            | 1         | 1      | 0.22%   |
| OCZ                 | 1         | 1      | 0.22%   |
| KingFast            | 1         | 1      | 0.22%   |
| HS-SSD-C100         | 1         | 1      | 0.22%   |
| Hised               | 1         | 2      | 0.22%   |
| EAGET               | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 791       | 1174   | 47.48%  |
| SSD     | 414       | 591    | 24.85%  |
| NVMe    | 410       | 569    | 24.61%  |
| MMC     | 36        | 43     | 2.16%   |
| Unknown | 15        | 19     | 0.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1033      | 1723   | 67.38%  |
| NVMe | 410       | 567    | 26.74%  |
| SAS  | 54        | 63     | 3.52%   |
| MMC  | 36        | 43     | 2.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 689       | 1000   | 56.11%  |
| 0.51-1.0   | 461       | 634    | 37.54%  |
| 1.01-2.0   | 55        | 83     | 4.48%   |
| 3.01-4.0   | 7         | 16     | 0.57%   |
| 2.01-3.0   | 6         | 11     | 0.49%   |
| 4.01-10.0  | 6         | 13     | 0.49%   |
| 10.01-20.0 | 3         | 6      | 0.24%   |
| 0          | 1         | 2      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 375       | 25.86%  |
| 101-250        | 362       | 24.97%  |
| 501-1000       | 278       | 19.17%  |
| 1-20           | 113       | 7.79%   |
| 51-100         | 95        | 6.55%   |
| 1001-2000      | 93        | 6.41%   |
| 21-50          | 49        | 3.38%   |
| More than 3000 | 36        | 2.48%   |
| 2001-3000      | 25        | 1.72%   |
| Unknown        | 24        | 1.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 590       | 39.39%  |
| 21-50          | 295       | 19.69%  |
| 101-250        | 204       | 13.62%  |
| 51-100         | 173       | 11.55%  |
| 251-500        | 94        | 6.28%   |
| 501-1000       | 76        | 5.07%   |
| 1001-2000      | 25        | 1.67%   |
| Unknown        | 24        | 1.6%    |
| More than 3000 | 11        | 0.73%   |
| 2001-3000      | 4         | 0.27%   |
| 0              | 2         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                     | Computers | Drives | Percent |
|-----------------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                        | 5         | 5      | 2.72%   |
| Seagate ST500DM002-1BD142 500GB                           | 4         | 4      | 2.17%   |
| Seagate ST9500325AS 500GB                                 | 3         | 3      | 1.63%   |
| Seagate ST500LT012-9WS142 500GB                           | 3         | 3      | 1.63%   |
| Seagate ST500LT012-1DG142 500GB                           | 3         | 3      | 1.63%   |
| Hitachi HDS721050CLA362 500GB                             | 3         | 3      | 1.63%   |
| A-DATA Technology SU630 480GB SSD                         | 3         | 4      | 1.63%   |
| A-DATA Technology SU630 240GB SSD                         | 3         | 3      | 1.63%   |
| WDC WD3200AAJS-56M0A0 320GB                               | 2         | 2      | 1.09%   |
| Toshiba MQ04ABF100 1TB                                    | 2         | 3      | 1.09%   |
| Toshiba MQ01ABF050 500GB                                  | 2         | 2      | 1.09%   |
| Toshiba MQ01ABD100 1TB                                    | 2         | 3      | 1.09%   |
| Toshiba DT01ACA100 1TB                                    | 2         | 2      | 1.09%   |
| Toshiba DT01ACA050 500GB                                  | 2         | 2      | 1.09%   |
| Seagate ST9500420AS 500GB                                 | 2         | 3      | 1.09%   |
| Seagate ST9320423AS 320GB                                 | 2         | 2      | 1.09%   |
| Seagate ST750LM022 HN-M750MBB 752GB                       | 2         | 2      | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB                            | 2         | 2      | 1.09%   |
| Seagate ST1000DM003-1SB102 1TB                            | 2         | 2      | 1.09%   |
| Seagate ST1000DM003-1ER162 1TB                            | 2         | 2      | 1.09%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 256GB | 2         | 2      | 1.09%   |
| Hitachi HTS545050A7E380 500GB                             | 2         | 2      | 1.09%   |
| Hitachi HDP725032GLA360 320GB                             | 2         | 2      | 1.09%   |
| HGST HTS545050A7E680 500GB                                | 2         | 2      | 1.09%   |
| HGST HTS541010A9E680 1TB                                  | 2         | 2      | 1.09%   |
| XrayDisk SSD 256GB                                        | 1         | 1      | 0.54%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                            | 1         | 2      | 0.54%   |
| WDC WD800JD-75MSA3 80GB                                   | 1         | 1      | 0.54%   |
| WDC WD800JD-60LSA0 80GB                                   | 1         | 1      | 0.54%   |
| WDC WD800BD-22MRA1 80GB                                   | 1         | 1      | 0.54%   |
| WDC WD6400AAKS-65Z7B0 640GB                               | 1         | 1      | 0.54%   |
| WDC WD5000LPVX-22V0TT0 500GB                              | 1         | 1      | 0.54%   |
| WDC WD5000LPLX-66ZNTT1 500GB                              | 1         | 1      | 0.54%   |
| WDC WD5000BPVT-22HXZT3 500GB                              | 1         | 1      | 0.54%   |
| WDC WD5000BEVT-22A0RT0 500GB                              | 1         | 1      | 0.54%   |
| WDC WD5000AAKX-60U6AA0 500GB                              | 1         | 1      | 0.54%   |
| WDC WD5000AAKS-08V0A0 500GB                               | 1         | 1      | 0.54%   |
| WDC WD3200BPVT-24JJ5T0 320GB                              | 1         | 1      | 0.54%   |
| WDC WD3200BEVT-22ZCT0 320GB                               | 1         | 1      | 0.54%   |
| WDC WD3200BEKT-60F3T1 320GB                               | 1         | 1      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 44        | 53     | 25.43%  |
| WDC                   | 33        | 42     | 19.08%  |
| Hitachi               | 24        | 30     | 13.87%  |
| Toshiba               | 22        | 24     | 12.72%  |
| HGST                  | 9         | 9      | 5.2%    |
| Samsung Electronics   | 8         | 8      | 4.62%   |
| Maxtor                | 7         | 8      | 4.05%   |
| A-DATA Technology     | 7         | 8      | 4.05%   |
| Crucial               | 3         | 3      | 1.73%   |
| SK hynix              | 2         | 3      | 1.16%   |
| Realtek Semiconductor | 2         | 2      | 1.16%   |
| Intel                 | 2         | 3      | 1.16%   |
| XrayDisk              | 1         | 1      | 0.58%   |
| SanDisk               | 1         | 1      | 0.58%   |
| Min Yi U              | 1         | 1      | 0.58%   |
| Micron Technology     | 1         | 1      | 0.58%   |
| Kingston              | 1         | 1      | 0.58%   |
| Inateck               | 1         | 1      | 0.58%   |
| Fujitsu               | 1         | 1      | 0.58%   |
| DTECHCO               | 1         | 1      | 0.58%   |
| BAITITON              | 1         | 1      | 0.58%   |
| Apple                 | 1         | 1      | 0.58%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 53     | 29.93%  |
| WDC                 | 32        | 40     | 21.77%  |
| Hitachi             | 24        | 30     | 16.33%  |
| Toshiba             | 22        | 24     | 14.97%  |
| HGST                | 9         | 9      | 6.12%   |
| Maxtor              | 7         | 8      | 4.76%   |
| Samsung Electronics | 5         | 5      | 3.4%    |
| Min Yi U            | 1         | 1      | 0.68%   |
| Inateck             | 1         | 1      | 0.68%   |
| Fujitsu             | 1         | 1      | 0.68%   |
| Apple               | 1         | 1      | 0.68%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 133       | 173    | 83.65%  |
| SSD  | 20        | 24     | 12.58%  |
| NVMe | 6         | 6      | 3.77%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Maxtor STM380211AS 80GB   | 1         | 1      | 50%     |
| Crucial CT500P2SSD8 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Maxtor  | 1         | 1      | 50%     |
| Crucial | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 850       | 1511   | 58.1%   |
| Works    | 454       | 680    | 31.03%  |
| Malfunc  | 157       | 203    | 10.73%  |
| Failed   | 2         | 2      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 872       | 52.34%  |
| AMD                                  | 333       | 19.99%  |
| Samsung Electronics                  | 85        | 5.1%    |
| SanDisk                              | 80        | 4.8%    |
| Kingston Technology Company          | 37        | 2.22%   |
| SK hynix                             | 33        | 1.98%   |
| Micron Technology                    | 33        | 1.98%   |
| Nvidia                               | 31        | 1.86%   |
| Realtek Semiconductor                | 26        | 1.56%   |
| Phison Electronics                   | 20        | 1.2%    |
| Micron/Crucial Technology            | 17        | 1.02%   |
| ADATA Technology                     | 16        | 0.96%   |
| Silicon Motion                       | 15        | 0.9%    |
| KIOXIA                               | 10        | 0.6%    |
| ASMedia Technology                   | 9         | 0.54%   |
| VIA Technologies                     | 8         | 0.48%   |
| Union Memory (Shenzhen)              | 6         | 0.36%   |
| MAXIO Technology (Hangzhou)          | 6         | 0.36%   |
| Marvell Technology Group             | 4         | 0.24%   |
| Seagate Technology                   | 3         | 0.18%   |
| JMicron Technology                   | 3         | 0.18%   |
| Biwin Storage Technology             | 3         | 0.18%   |
| Apple                                | 3         | 0.18%   |
| Toshiba America Info Systems         | 2         | 0.12%   |
| Shenzhen Longsys Electronics         | 2         | 0.12%   |
| LSI Logic / Symbios Logic            | 2         | 0.12%   |
| INNOGRIT                             | 2         | 0.12%   |
| Solid State Storage Technology       | 1         | 0.06%   |
| Ramaxel Technology(Shenzhen) Limited | 1         | 0.06%   |
| Lenovo                               | 1         | 0.06%   |
| Hewlett-Packard                      | 1         | 0.06%   |
| Broadcom / LSI                       | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 246       | 12.79%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 82        | 4.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 75        | 3.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 72        | 3.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 53        | 2.76%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 47        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 40        | 2.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 38        | 1.98%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 34        | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 30        | 1.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 29        | 1.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 28        | 1.46%   |
| AMD 500 Series Chipset SATA Controller                                                  | 28        | 1.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 27        | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 27        | 1.4%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 26        | 1.35%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 25        | 1.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 24        | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 24        | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 24        | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 23        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 21        | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 20        | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 19        | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 19        | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 19        | 0.99%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 18        | 0.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 18        | 0.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 17        | 0.88%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 17        | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 16        | 0.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 16        | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 16        | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 15        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 14        | 0.73%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 14        | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 14        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 14        | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 14        | 0.73%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 13        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 996       | 57.81%  |
| NVMe | 409       | 23.74%  |
| IDE  | 168       | 9.75%   |
| RAID | 145       | 8.42%   |
| SAS  | 5         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 933       | 68.6%   |
| AMD    | 424       | 31.18%  |
| ARM    | 3         | 0.22%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 34        | 2.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 20        | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 15        | 1.1%    |
| AMD Ryzen 5 7520U with Radeon Graphics          | 15        | 1.1%    |
| Intel Core i5-8300H CPU @ 2.30GHz               | 14        | 1.03%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 14        | 1.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 13        | 0.95%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 13        | 0.95%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 13        | 0.95%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 13        | 0.95%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 13        | 0.95%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 11        | 0.81%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 11        | 0.81%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 11        | 0.81%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 11        | 0.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 11        | 0.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 11        | 0.81%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 11        | 0.81%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G    | 11        | 0.81%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 10        | 0.73%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 10        | 0.73%   |
| AMD Ryzen 5 3600 6-Core Processor               | 10        | 0.73%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 9         | 0.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 9         | 0.66%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 9         | 0.66%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 9         | 0.66%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 8         | 0.59%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 8         | 0.59%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 8         | 0.59%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 8         | 0.59%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 8         | 0.59%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 7         | 0.51%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 7         | 0.51%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 7         | 0.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 7         | 0.51%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 7         | 0.51%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 7         | 0.51%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 7         | 0.51%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 7         | 0.51%   |
| Intel 12th Gen Core i5-1235U                    | 7         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 280       | 20.54%  |
| Intel Core i7           | 179       | 13.13%  |
| Intel Core i3           | 144       | 10.56%  |
| AMD Ryzen 5             | 141       | 10.34%  |
| Other                   | 123       | 9.02%   |
| Intel Celeron           | 84        | 6.16%   |
| AMD Ryzen 7             | 45        | 3.3%    |
| Intel Core 2 Duo        | 35        | 2.57%   |
| AMD Ryzen 3             | 33        | 2.42%   |
| Intel Atom              | 26        | 1.91%   |
| Intel Xeon              | 18        | 1.32%   |
| Intel Pentium Dual-Core | 18        | 1.32%   |
| Intel Pentium           | 18        | 1.32%   |
| AMD A10                 | 17        | 1.25%   |
| Intel Pentium Dual      | 15        | 1.1%    |
| AMD FX                  | 15        | 1.1%    |
| AMD A12                 | 14        | 1.03%   |
| AMD E1                  | 12        | 0.88%   |
| AMD A8                  | 12        | 0.88%   |
| AMD Ryzen 9             | 11        | 0.81%   |
| AMD Athlon              | 11        | 0.81%   |
| AMD A4                  | 9         | 0.66%   |
| AMD Athlon II X2        | 8         | 0.59%   |
| AMD A6                  | 8         | 0.59%   |
| AMD Ryzen 7 PRO         | 7         | 0.51%   |
| AMD E2                  | 6         | 0.44%   |
| AMD E                   | 6         | 0.44%   |
| AMD Athlon 64 X2        | 6         | 0.44%   |
| Intel Core 2 Quad       | 5         | 0.37%   |
| Intel Core 2            | 5         | 0.37%   |
| AMD Sempron             | 5         | 0.37%   |
| AMD Phenom II X6        | 5         | 0.37%   |
| AMD Turion 64 X2 Mobile | 3         | 0.22%   |
| AMD Ryzen Threadripper  | 3         | 0.22%   |
| AMD Phenom II X4        | 3         | 0.22%   |
| AMD Phenom              | 3         | 0.22%   |
| Intel Pentium D         | 2         | 0.15%   |
| Intel Pentium 4         | 2         | 0.15%   |
| Intel Genuine           | 2         | 0.15%   |
| Intel Core m5           | 2         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 639       | 46.81%  |
| 4       | 439       | 32.16%  |
| 6       | 110       | 8.06%   |
| 8       | 69        | 5.05%   |
| 1       | 40        | 2.93%   |
| 12      | 22        | 1.61%   |
| 10      | 20        | 1.47%   |
| 14      | 9         | 0.66%   |
| 3       | 8         | 0.59%   |
| 16      | 7         | 0.51%   |
| 24      | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1350      | 99.26%  |
| 2      | 10        | 0.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 935       | 68.5%   |
| 1       | 425       | 31.14%  |
| 8       | 2         | 0.15%   |
| 4       | 2         | 0.15%   |
| Unknown | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1313      | 96.19%  |
| Unknown        | 39        | 2.86%   |
| 64-bit         | 7         | 0.51%   |
| 32-bit         | 6         | 0.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 497       | 35.25%  |
| 0x306a9    | 64        | 4.54%   |
| 0x206a7    | 59        | 4.18%   |
| 0x08108109 | 41        | 2.91%   |
| 0x306c3    | 37        | 2.62%   |
| 0x806ec    | 34        | 2.41%   |
| 0x806ea    | 34        | 2.41%   |
| 0x406e3    | 27        | 1.91%   |
| 0x1067a    | 26        | 1.84%   |
| 0x06006705 | 24        | 1.7%    |
| 0x40651    | 22        | 1.56%   |
| 0x6fd      | 21        | 1.49%   |
| 0x306d4    | 21        | 1.49%   |
| 0x20655    | 20        | 1.42%   |
| 0x906ea    | 19        | 1.35%   |
| 0x806c1    | 18        | 1.28%   |
| 0x406c4    | 18        | 1.28%   |
| 0x806e9    | 17        | 1.21%   |
| 0x08608103 | 17        | 1.21%   |
| 0x0a50000c | 15        | 1.06%   |
| 0x706e5    | 14        | 0.99%   |
| 0x08108102 | 14        | 0.99%   |
| 0x506e3    | 13        | 0.92%   |
| 0x08701021 | 11        | 0.78%   |
| 0x05000119 | 11        | 0.78%   |
| 0x010000c8 | 11        | 0.78%   |
| 0x706a1    | 10        | 0.71%   |
| 0x10676    | 10        | 0.71%   |
| 0x06000852 | 10        | 0.71%   |
| 0x906e9    | 9         | 0.64%   |
| 0x06006118 | 9         | 0.64%   |
| 0x806eb    | 8         | 0.57%   |
| 0x30678    | 8         | 0.57%   |
| 0x20652    | 8         | 0.57%   |
| 0x08600106 | 8         | 0.57%   |
| 0x0600611a | 8         | 0.57%   |
| 0x06001119 | 8         | 0.57%   |
| 0xa0652    | 7         | 0.5%    |
| 0x706a8    | 7         | 0.5%    |
| 0x106e5    | 7         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 184       | 13.52%  |
| IvyBridge        | 105       | 7.71%   |
| Haswell          | 91        | 6.69%   |
| Zen+             | 88        | 6.47%   |
| SandyBridge      | 88        | 6.47%   |
| Unknown          | 68        | 5%      |
| Skylake          | 54        | 3.97%   |
| Excavator        | 53        | 3.89%   |
| Zen 2            | 47        | 3.45%   |
| Penryn           | 47        | 3.45%   |
| Silvermont       | 44        | 3.23%   |
| Westmere         | 43        | 3.16%   |
| Core             | 42        | 3.09%   |
| Zen 3            | 39        | 2.87%   |
| Alderlake Hybrid | 38        | 2.79%   |
| TigerLake        | 36        | 2.65%   |
| Zen              | 30        | 2.2%    |
| Broadwell        | 29        | 2.13%   |
| Goldmont plus    | 28        | 2.06%   |
| CometLake        | 28        | 2.06%   |
| K10              | 27        | 1.98%   |
| Icelake          | 27        | 1.98%   |
| Piledriver       | 25        | 1.84%   |
| K8 Hammer        | 17        | 1.25%   |
| Puma             | 16        | 1.18%   |
| Bonnell          | 14        | 1.03%   |
| Bobcat           | 13        | 0.96%   |
| Nehalem          | 8         | 0.59%   |
| NetBurst         | 7         | 0.51%   |
| Jaguar           | 7         | 0.51%   |
| Steamroller      | 5         | 0.37%   |
| Goldmont         | 4         | 0.29%   |
| K10 Llano        | 3         | 0.22%   |
| K8 & K10 hybrid  | 2         | 0.15%   |
| Bulldozer        | 2         | 0.15%   |
| P6               | 1         | 0.07%   |
| Gracemont        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 819       | 52.13%  |
| AMD                        | 424       | 26.99%  |
| Nvidia                     | 316       | 20.11%  |
| Matrox Electronics Systems | 7         | 0.45%   |
| VIA Technologies           | 5         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 80        | 4.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 70        | 4.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 67        | 4.09%   |
| Intel UHD Graphics 620                                                                   | 43        | 2.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 34        | 2.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 32        | 1.95%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 32        | 1.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 31        | 1.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 31        | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 30        | 1.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 27        | 1.65%   |
| AMD Lucienne                                                                             | 26        | 1.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 25        | 1.53%   |
| Intel HD Graphics 620                                                                    | 25        | 1.53%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 25        | 1.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 24        | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 1.46%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 22        | 1.34%   |
| Intel HD Graphics 5500                                                                   | 21        | 1.28%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 21        | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 1.22%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 19        | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 18        | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 18        | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18        | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 18        | 1.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 17        | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 1.04%   |
| Intel HD Graphics 530                                                                    | 17        | 1.04%   |
| AMD Mendocino                                                                            | 17        | 1.04%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 15        | 0.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 14        | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 0.73%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 12        | 0.73%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 11        | 0.67%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 0.67%   |
| Intel HD Graphics 630                                                                    | 10        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 635       | 46.28%  |
| 1 x AMD         | 338       | 24.64%  |
| Intel + Nvidia  | 155       | 11.3%   |
| 1 x Nvidia      | 139       | 10.13%  |
| 2 x AMD         | 46        | 3.35%   |
| Intel + AMD     | 21        | 1.53%   |
| AMD + Nvidia    | 20        | 1.46%   |
| 1 x Matrox      | 6         | 0.44%   |
| 1 x VIA         | 5         | 0.36%   |
| Other           | 3         | 0.22%   |
| 2 x Intel       | 3         | 0.22%   |
| Nvidia + Matrox | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1168      | 84.76%  |
| Proprietary | 142       | 10.3%   |
| Unknown     | 68        | 4.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 848       | 60.92%  |
| 0.01-0.5   | 178       | 12.79%  |
| 1.01-2.0   | 167       | 12%     |
| 0.51-1.0   | 84        | 6.03%   |
| 3.01-4.0   | 65        | 4.67%   |
| 7.01-8.0   | 22        | 1.58%   |
| 5.01-6.0   | 13        | 0.93%   |
| 8.01-16.0  | 9         | 0.65%   |
| 2.01-3.0   | 6         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 253       | 17.28%  |
| Samsung Electronics     | 233       | 15.92%  |
| AU Optronics            | 177       | 12.09%  |
| BOE                     | 161       | 11%     |
| Goldstar                | 110       | 7.51%   |
| LG Display              | 100       | 6.83%   |
| Hewlett-Packard         | 73        | 4.99%   |
| Dell                    | 43        | 2.94%   |
| Apple                   | 33        | 2.25%   |
| PANDA                   | 27        | 1.84%   |
| Acer                    | 26        | 1.78%   |
| Lenovo                  | 22        | 1.5%    |
| AOC                     | 17        | 1.16%   |
| Chi Mei Optoelectronics | 16        | 1.09%   |
| Sharp                   | 11        | 0.75%   |
| ViewSonic               | 10        | 0.68%   |
| ASUSTek Computer        | 10        | 0.68%   |
| InfoVision              | 9         | 0.61%   |
| HKC                     | 8         | 0.55%   |
| RTK                     | 7         | 0.48%   |
| MSI                     | 7         | 0.48%   |
| LG Electronics          | 7         | 0.48%   |
| Sony                    | 6         | 0.41%   |
| SAC                     | 6         | 0.41%   |
| LG Philips              | 6         | 0.41%   |
| BenQ                    | 6         | 0.41%   |
| SANYO                   | 5         | 0.34%   |
| InnoLux Display         | 5         | 0.34%   |
| CS_                     | 5         | 0.34%   |
| Ancor Communications    | 5         | 0.34%   |
| Unknown                 | 4         | 0.27%   |
| Sceptre Tech            | 4         | 0.27%   |
| HannStar                | 4         | 0.27%   |
| CSO                     | 4         | 0.27%   |
| NCS                     | 3         | 0.2%    |
| Panasonic               | 2         | 0.14%   |
| KTC                     | 2         | 0.14%   |
| Envision                | 2         | 0.14%   |
| AGO                     | 2         | 0.14%   |
| YSP                     | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 25        | 1.68%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 22        | 1.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 20        | 1.35%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 15        | 1.01%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch         | 13        | 0.88%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 12        | 0.81%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 12        | 0.81%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 12        | 0.81%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 11        | 0.74%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 10        | 0.67%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 10        | 0.67%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9         | 0.61%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 9         | 0.61%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 9         | 0.61%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 8         | 0.54%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 8         | 0.54%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 8         | 0.54%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 7         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 7         | 0.47%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 7         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 7         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 7         | 0.47%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 7         | 0.47%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 7         | 0.47%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 6         | 0.4%    |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 6         | 0.4%    |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 6         | 0.4%    |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                   | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 6         | 0.4%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.4%    |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch     | 5         | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 5         | 0.34%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 5         | 0.34%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 5         | 0.34%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 5         | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.34%   |
| CS_ LCD Monitor CS_5211 1920x1080 519x324mm 24.1-inch                 | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch       | 5         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 546       | 38.92%  |
| 1920x1080 (FHD)    | 465       | 33.14%  |
| 1600x900 (HD+)     | 64        | 4.56%   |
| 3840x2160 (4K)     | 60        | 4.28%   |
| 1440x900 (WXGA+)   | 48        | 3.42%   |
| 1280x1024 (SXGA)   | 32        | 2.28%   |
| 1280x800 (WXGA)    | 28        | 2%      |
| 1920x1200 (WUXGA)  | 23        | 1.64%   |
| 2560x1440 (QHD)    | 21        | 1.5%    |
| 2560x1080          | 17        | 1.21%   |
| 1360x768           | 16        | 1.14%   |
| 1680x1050 (WSXGA+) | 13        | 0.93%   |
| 2560x1600          | 9         | 0.64%   |
| 1024x600           | 9         | 0.64%   |
| 2880x1800          | 8         | 0.57%   |
| 1024x768 (XGA)     | 6         | 0.43%   |
| Unknown            | 6         | 0.43%   |
| 3840x1080          | 4         | 0.29%   |
| 2160x1440          | 4         | 0.29%   |
| 3456x2160          | 3         | 0.21%   |
| 3440x1440          | 3         | 0.21%   |
| 2256x1504          | 2         | 0.14%   |
| 1280x960           | 2         | 0.14%   |
| 1280x720 (HD)      | 2         | 0.14%   |
| 6400x2160          | 1         | 0.07%   |
| 3840x2400          | 1         | 0.07%   |
| 3840x1100          | 1         | 0.07%   |
| 3200x1080          | 1         | 0.07%   |
| 2880x1920          | 1         | 0.07%   |
| 2288x1287          | 1         | 0.07%   |
| 2160x1350          | 1         | 0.07%   |
| 1920x540           | 1         | 0.07%   |
| 1680x945           | 1         | 0.07%   |
| 1600x2560          | 1         | 0.07%   |
| 1536x2048          | 1         | 0.07%   |
| 1152x864           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 355       | 24.13%  |
| 13      | 246       | 16.72%  |
| 14      | 214       | 14.55%  |
| 21      | 87        | 5.91%   |
| 23      | 65        | 4.42%   |
| 19      | 64        | 4.35%   |
| 18      | 62        | 4.21%   |
| 17      | 52        | 3.54%   |
| 24      | 45        | 3.06%   |
| 31      | 41        | 2.79%   |
| 27      | 40        | 2.72%   |
| 20      | 30        | 2.04%   |
| Unknown | 25        | 1.7%    |
| 12      | 20        | 1.36%   |
| 11      | 16        | 1.09%   |
| 34      | 13        | 0.88%   |
| 10      | 12        | 0.82%   |
| 54      | 11        | 0.75%   |
| 22      | 11        | 0.75%   |
| 84      | 10        | 0.68%   |
| 72      | 8         | 0.54%   |
| 16      | 8         | 0.54%   |
| 28      | 5         | 0.34%   |
| 40      | 4         | 0.27%   |
| 29      | 4         | 0.27%   |
| 26      | 4         | 0.27%   |
| 48      | 3         | 0.2%    |
| 32      | 3         | 0.2%    |
| 8       | 3         | 0.2%    |
| 86      | 1         | 0.07%   |
| 63      | 1         | 0.07%   |
| 61      | 1         | 0.07%   |
| 60      | 1         | 0.07%   |
| 58      | 1         | 0.07%   |
| 52      | 1         | 0.07%   |
| 46      | 1         | 0.07%   |
| 44      | 1         | 0.07%   |
| 43      | 1         | 0.07%   |
| 9       | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 783       | 53.96%  |
| 401-500     | 242       | 16.68%  |
| 501-600     | 137       | 9.44%   |
| 201-300     | 95        | 6.55%   |
| 601-700     | 59        | 4.07%   |
| 351-400     | 45        | 3.1%    |
| Unknown     | 25        | 1.72%   |
| 1001-1500   | 21        | 1.45%   |
| 1501-2000   | 18        | 1.24%   |
| 701-800     | 16        | 1.1%    |
| 801-900     | 4         | 0.28%   |
| 101-200     | 4         | 0.28%   |
| 901-1000    | 2         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1088      | 82.49%  |
| 16/10   | 128       | 9.7%    |
| 5/4     | 32        | 2.43%   |
| Unknown | 21        | 1.59%   |
| 21/9    | 20        | 1.52%   |
| 4/3     | 13        | 0.99%   |
| 3/2     | 10        | 0.76%   |
| 32/9    | 3         | 0.23%   |
| 3.40    | 1         | 0.08%   |
| 0.75    | 1         | 0.08%   |
| 0.58    | 1         | 0.08%   |
| 0.56    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 432       | 29.53%  |
| 101-110        | 354       | 24.2%   |
| 201-250        | 166       | 11.35%  |
| 151-200        | 117       | 8%      |
| 141-150        | 82        | 5.6%    |
| 351-500        | 58        | 3.96%   |
| 301-350        | 48        | 3.28%   |
| More than 1000 | 36        | 2.46%   |
| 71-80          | 30        | 2.05%   |
| Unknown        | 25        | 1.71%   |
| 121-130        | 22        | 1.5%    |
| 251-300        | 21        | 1.44%   |
| 51-60          | 17        | 1.16%   |
| 61-70          | 15        | 1.03%   |
| 41-50          | 13        | 0.89%   |
| 501-1000       | 9         | 0.62%   |
| 131-140        | 8         | 0.55%   |
| 111-120        | 6         | 0.41%   |
| 1-40           | 3         | 0.21%   |
| 91-100         | 1         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 587       | 41.14%  |
| 51-100        | 407       | 28.52%  |
| 121-160       | 307       | 21.51%  |
| 161-240       | 45        | 3.15%   |
| 1-50          | 33        | 2.31%   |
| Unknown       | 25        | 1.75%   |
| More than 240 | 23        | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1108      | 79.14%  |
| 2     | 219       | 15.64%  |
| 0     | 62        | 4.43%   |
| 3     | 10        | 0.71%   |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 897       | 43.73%  |
| Intel                             | 432       | 21.06%  |
| Qualcomm Atheros                  | 275       | 13.41%  |
| Broadcom                          | 119       | 5.8%    |
| MediaTek                          | 55        | 2.68%   |
| Broadcom Limited                  | 38        | 1.85%   |
| Ralink Technology                 | 37        | 1.8%    |
| TP-Link                           | 31        | 1.51%   |
| Nvidia                            | 25        | 1.22%   |
| Ralink                            | 22        | 1.07%   |
| Marvell Technology Group          | 15        | 0.73%   |
| Samsung Electronics               | 14        | 0.68%   |
| Xiaomi                            | 11        | 0.54%   |
| Qualcomm Atheros Communications   | 11        | 0.54%   |
| ASIX Electronics                  | 11        | 0.54%   |
| ICS Advent                        | 7         | 0.34%   |
| VIA Technologies                  | 5         | 0.24%   |
| Huawei Technologies               | 5         | 0.24%   |
| Motorola PCS                      | 4         | 0.2%    |
| Mercucys                          | 4         | 0.2%    |
| D-Link System                     | 4         | 0.2%    |
| Qualcomm                          | 3         | 0.15%   |
| DisplayLink                       | 3         | 0.15%   |
| T & A Mobile Phones               | 2         | 0.1%    |
| Sundance Technology Inc / IC Plus | 2         | 0.1%    |
| OPPO Electronics                  | 2         | 0.1%    |
| Aquantia                          | 2         | 0.1%    |
| Wistron NeWeb                     | 1         | 0.05%   |
| STMicroelectronics                | 1         | 0.05%   |
| Quanta                            | 1         | 0.05%   |
| QinHeng Electronics               | 1         | 0.05%   |
| Prolific Technology               | 1         | 0.05%   |
| Netchip Technology                | 1         | 0.05%   |
| Mellanox Technologies             | 1         | 0.05%   |
| LG Electronics                    | 1         | 0.05%   |
| Lenovo                            | 1         | 0.05%   |
| JMicron Technology                | 1         | 0.05%   |
| Google                            | 1         | 0.05%   |
| Encore Electronics                | 1         | 0.05%   |
| Dell                              | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 564       | 23.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 143       | 5.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 75        | 3.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 66        | 2.74%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 46        | 1.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 42        | 1.75%   |
| Intel Wireless 8265 / 8275                                             | 38        | 1.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 36        | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 33        | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 31        | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 31        | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 30        | 1.25%   |
| Intel Wi-Fi 6 AX200                                                    | 29        | 1.21%   |
| Intel Wi-Fi 6 AX201                                                    | 26        | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 24        | 1%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 24        | 1%      |
| Realtek RTL8125 2.5GbE Controller                                      | 23        | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 23        | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 23        | 0.96%   |
| Realtek 802.11ac NIC                                                   | 22        | 0.91%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 22        | 0.91%   |
| Intel Wireless 7260                                                    | 20        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 20        | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 19        | 0.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 18        | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 18        | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 17        | 0.71%   |
| Ralink MT7601U Wireless Adapter                                        | 17        | 0.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 16        | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 16        | 0.67%   |
| Intel Centrino Wireless-N 2230                                         | 16        | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                          | 16        | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 14        | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 13        | 0.54%   |
| Intel Wireless 8260                                                    | 13        | 0.54%   |
| Intel Wireless 7265                                                    | 12        | 0.5%    |
| Intel Ethernet Controller I225-V                                       | 12        | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 11        | 0.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 11        | 0.46%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 366       | 30.73%  |
| Realtek Semiconductor           | 325       | 27.29%  |
| Qualcomm Atheros                | 228       | 19.14%  |
| Broadcom                        | 80        | 6.72%   |
| MediaTek                        | 50        | 4.2%    |
| Ralink Technology               | 37        | 3.11%   |
| TP-Link                         | 31        | 2.6%    |
| Broadcom Limited                | 25        | 2.1%    |
| Ralink                          | 22        | 1.85%   |
| Qualcomm Atheros Communications | 11        | 0.92%   |
| Mercucys                        | 4         | 0.34%   |
| D-Link System                   | 3         | 0.25%   |
| Marvell Technology Group        | 2         | 0.17%   |
| Wistron NeWeb                   | 1         | 0.08%   |
| Qualcomm                        | 1         | 0.08%   |
| LG Electronics                  | 1         | 0.08%   |
| Encore Electronics              | 1         | 0.08%   |
| Dell                            | 1         | 0.08%   |
| D-Link                          | 1         | 0.08%   |
| 3Com                            | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 75        | 6.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 66        | 5.52%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 46        | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 42        | 3.51%   |
| Intel Wireless 8265 / 8275                                     | 38        | 3.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 36        | 3.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 33        | 2.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 31        | 2.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 30        | 2.51%   |
| Intel Wi-Fi 6 AX200                                            | 29        | 2.42%   |
| Intel Wi-Fi 6 AX201                                            | 26        | 2.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 24        | 2.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 23        | 1.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 23        | 1.92%   |
| Realtek 802.11ac NIC                                           | 22        | 1.84%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 22        | 1.84%   |
| Intel Wireless 7260                                            | 20        | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 1.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 19        | 1.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 18        | 1.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 18        | 1.51%   |
| Ralink MT7601U Wireless Adapter                                | 17        | 1.42%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 16        | 1.34%   |
| Intel Centrino Wireless-N 2230                                 | 16        | 1.34%   |
| Broadcom BCM43142 802.11b/g/n                                  | 16        | 1.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 14        | 1.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 13        | 1.09%   |
| Intel Wireless 8260                                            | 13        | 1.09%   |
| Intel Wireless 7265                                            | 12        | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                     | 11        | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 10        | 0.84%   |
| Qualcomm Atheros AR9271 802.11n                                | 10        | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 10        | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10        | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 10        | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 0.84%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 9         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 9         | 0.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 9         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 789       | 66.36%  |
| Intel                             | 155       | 13.04%  |
| Qualcomm Atheros                  | 67        | 5.63%   |
| Broadcom                          | 51        | 4.29%   |
| Nvidia                            | 25        | 2.1%    |
| Marvell Technology Group          | 13        | 1.09%   |
| Broadcom Limited                  | 13        | 1.09%   |
| Xiaomi                            | 11        | 0.93%   |
| ASIX Electronics                  | 11        | 0.93%   |
| Samsung Electronics               | 9         | 0.76%   |
| ICS Advent                        | 7         | 0.59%   |
| VIA Technologies                  | 5         | 0.42%   |
| Huawei Technologies               | 5         | 0.42%   |
| Motorola PCS                      | 4         | 0.34%   |
| MediaTek                          | 4         | 0.34%   |
| DisplayLink                       | 3         | 0.25%   |
| T & A Mobile Phones               | 2         | 0.17%   |
| Sundance Technology Inc / IC Plus | 2         | 0.17%   |
| Qualcomm                          | 2         | 0.17%   |
| OPPO Electronics                  | 2         | 0.17%   |
| Aquantia                          | 2         | 0.17%   |
| Quanta                            | 1         | 0.08%   |
| Prolific Technology               | 1         | 0.08%   |
| Netchip Technology                | 1         | 0.08%   |
| Mellanox Technologies             | 1         | 0.08%   |
| Lenovo                            | 1         | 0.08%   |
| JMicron Technology                | 1         | 0.08%   |
| D-Link System                     | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 564       | 47%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 143       | 11.92%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 31        | 2.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 24        | 2%      |
| Realtek RTL8125 2.5GbE Controller                                      | 23        | 1.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 17        | 1.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 16        | 1.33%   |
| Intel Ethernet Controller I225-V                                       | 12        | 1%      |
| Intel I211 Gigabit Network Connection                                  | 11        | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 10        | 0.83%   |
| Nvidia MCP61 Ethernet                                                  | 10        | 0.83%   |
| Intel Ethernet Connection I219-LM                                      | 10        | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9         | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 9         | 0.75%   |
| Realtek Killer E2600 GbE Controller                                    | 9         | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 8         | 0.67%   |
| Intel 82579V Gigabit Network Connection                                | 8         | 0.67%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 8         | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                          | 8         | 0.67%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 7         | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 7         | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 7         | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 6         | 0.5%    |
| Nvidia MCP79 Ethernet                                                  | 6         | 0.5%    |
| Intel Ethernet Connection I217-LM                                      | 6         | 0.5%    |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.5%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 6         | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                           | 5         | 0.42%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 5         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 5         | 0.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 5         | 0.42%   |
| Intel Ethernet Connection I219-V                                       | 5         | 0.42%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 0.42%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 5         | 0.42%   |
| Huawei FOA-LX9                                                         | 5         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 0.33%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 0.33%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.33%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1136      | 50.04%  |
| WiFi     | 1125      | 49.56%  |
| Modem    | 7         | 0.31%   |
| Unknown  | 2         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 866       | 60.06%  |
| Ethernet | 574       | 39.81%  |
| Modem    | 1         | 0.07%   |
| Unknown  | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 778       | 57.04%  |
| 1     | 559       | 40.98%  |
| 0     | 16        | 1.17%   |
| 3     | 8         | 0.59%   |
| 7     | 1         | 0.07%   |
| 6     | 1         | 0.07%   |
| 4     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1203      | 86.86%  |
| Yes  | 182       | 13.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 315       | 34.5%   |
| Realtek Semiconductor           | 175       | 19.17%  |
| IMC Networks                    | 116       | 12.71%  |
| Qualcomm Atheros Communications | 72        | 7.89%   |
| Cambridge Silicon Radio         | 47        | 5.15%   |
| Lite-On Technology              | 46        | 5.04%   |
| Broadcom                        | 30        | 3.29%   |
| Apple                           | 29        | 3.18%   |
| Foxconn / Hon Hai               | 24        | 2.63%   |
| Ralink                          | 10        | 1.1%    |
| Toshiba                         | 8         | 0.88%   |
| MediaTek                        | 8         | 0.88%   |
| Hewlett-Packard                 | 8         | 0.88%   |
| Realtek                         | 7         | 0.77%   |
| Foxconn International           | 5         | 0.55%   |
| Dell                            | 5         | 0.55%   |
| ASUSTek Computer                | 3         | 0.33%   |
| Alps Electric                   | 3         | 0.33%   |
| TP-Link                         | 1         | 0.11%   |
| Marvell Semiconductor           | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 96        | 10.51%  |
| Realtek  Bluetooth 4.2 Adapter                      | 73        | 8%      |
| Realtek Bluetooth Radio                             | 70        | 7.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 64        | 7.01%   |
| Intel AX201 Bluetooth                               | 61        | 6.68%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 47        | 5.15%   |
| IMC Networks Bluetooth Radio                        | 43        | 4.71%   |
| IMC Networks Wireless_Device                        | 38        | 4.16%   |
| Qualcomm Atheros  Bluetooth Device                  | 33        | 3.61%   |
| Intel AX200 Bluetooth                               | 29        | 3.18%   |
| IMC Networks Bluetooth Device                       | 28        | 3.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 20        | 2.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 1.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 1.75%   |
| Intel AX211 Bluetooth                               | 16        | 1.75%   |
| Apple Bluetooth Host Controller                     | 12        | 1.31%   |
| Realtek 802.11ac WLAN Adapter                       | 11        | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 1.2%    |
| Ralink RT3290 Bluetooth                             | 10        | 1.1%    |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 1.1%    |
| Apple Bluetooth USB Host Controller                 | 10        | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 9         | 0.99%   |
| Lite-On Bluetooth Device                            | 9         | 0.99%   |
| Realtek RTL8723B Bluetooth                          | 8         | 0.88%   |
| MediaTek Wireless_Device                            | 8         | 0.88%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 8         | 0.88%   |
| Realtek Bluetooth Radio                             | 7         | 0.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 0.77%   |
| Intel AX210 Bluetooth                               | 7         | 0.77%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 0.77%   |
| Realtek RTL8821A Bluetooth                          | 6         | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.66%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 0.55%   |
| Foxconn International BCM43142A0 Bluetooth module   | 5         | 0.55%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.55%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 5         | 0.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 901       | 53.35%  |
| AMD                                  | 449       | 26.58%  |
| Nvidia                               | 223       | 13.2%   |
| C-Media Electronics                  | 19        | 1.12%   |
| Logitech                             | 11        | 0.65%   |
| Generalplus Technology               | 11        | 0.65%   |
| VIA Technologies                     | 7         | 0.41%   |
| Texas Instruments                    | 6         | 0.36%   |
| Realtek Semiconductor                | 6         | 0.36%   |
| JMTek                                | 6         | 0.36%   |
| Creative Labs                        | 4         | 0.24%   |
| Corsair                              | 4         | 0.24%   |
| Plantronics                          | 3         | 0.18%   |
| M-Audio                              | 3         | 0.18%   |
| KTMicro                              | 3         | 0.18%   |
| Blue Microphones                     | 3         | 0.18%   |
| SteelSeries ApS                      | 2         | 0.12%   |
| Sony                                 | 2         | 0.12%   |
| Kingston Technology                  | 2         | 0.12%   |
| Turtle Beach                         | 1         | 0.06%   |
| Trust                                | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.06%   |
| Sennheiser Communications            | 1         | 0.06%   |
| SAVITECH                             | 1         | 0.06%   |
| Razer USA                            | 1         | 0.06%   |
| Microsoft                            | 1         | 0.06%   |
| Micro Star International             | 1         | 0.06%   |
| Jieli Technology                     | 1         | 0.06%   |
| JBL                                  | 1         | 0.06%   |
| HiBy                                 | 1         | 0.06%   |
| GN Netcom                            | 1         | 0.06%   |
| Giga-Byte Technology                 | 1         | 0.06%   |
| Earth Computer Technologies          | 1         | 0.06%   |
| Drop                                 | 1         | 0.06%   |
| Creative Technology                  | 1         | 0.06%   |
| Conexant Systems                     | 1         | 0.06%   |
| Cirrus Logic                         | 1         | 0.06%   |
| BEHRINGER International              | 1         | 0.06%   |
| Avid Technology                      | 1         | 0.06%   |
| ASUSTek Computer                     | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 203       | 9.47%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 108       | 5.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 96        | 4.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 96        | 4.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 90        | 4.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 73        | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 57        | 2.66%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 52        | 2.43%   |
| AMD FCH Azalia Controller                                                                         | 50        | 2.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 49        | 2.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 48        | 2.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 43        | 2.01%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 40        | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 39        | 1.82%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 37        | 1.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 36        | 1.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 33        | 1.54%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 32        | 1.49%   |
| AMD High Definition Audio Controller                                                              | 32        | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 31        | 1.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 30        | 1.4%    |
| Intel 8 Series HD Audio Controller                                                                | 29        | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 28        | 1.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 27        | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 27        | 1.26%   |
| Intel Broadwell-U Audio Controller                                                                | 27        | 1.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 26        | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 24        | 1.12%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 23        | 1.07%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 23        | 1.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 22        | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 22        | 1.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 21        | 0.98%   |
| Nvidia High Definition Audio Controller                                                           | 19        | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 17        | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 17        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 0.75%   |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 0.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15        | 0.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 14        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 209       | 24.82%  |
| SK hynix                     | 147       | 17.46%  |
| Micron Technology            | 108       | 12.83%  |
| Kingston                     | 63        | 7.48%   |
| Unknown                      | 61        | 7.24%   |
| A-DATA Technology            | 55        | 6.53%   |
| Crucial                      | 32        | 3.8%    |
| Corsair                      | 25        | 2.97%   |
| Ramaxel Technology           | 20        | 2.38%   |
| Nanya Technology             | 13        | 1.54%   |
| Elpida                       | 11        | 1.31%   |
| Team                         | 10        | 1.19%   |
| Patriot                      | 7         | 0.83%   |
| G.Skill                      | 7         | 0.83%   |
| Unknown                      | 7         | 0.83%   |
| Super Talent                 | 6         | 0.71%   |
| Avant                        | 6         | 0.71%   |
| Unknown (ABCD)               | 5         | 0.59%   |
| PNY                          | 5         | 0.59%   |
| Hewlett-Packard              | 5         | 0.59%   |
| Apacer                       | 5         | 0.59%   |
| GeIL                         | 4         | 0.48%   |
| PUSKILL                      | 2         | 0.24%   |
| Kreton                       | 2         | 0.24%   |
| Kllisre                      | 2         | 0.24%   |
| Hikvision                    | 2         | 0.24%   |
| Unknown (AD8A)               | 1         | 0.12%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 0.12%   |
| Unknown (0B85)               | 1         | 0.12%   |
| Unknown (08AE)               | 1         | 0.12%   |
| Unigen                       | 1         | 0.12%   |
| Transcend                    | 1         | 0.12%   |
| Toshiba                      | 1         | 0.12%   |
| Silicon Power                | 1         | 0.12%   |
| Sesame                       | 1         | 0.12%   |
| RZX                          | 1         | 0.12%   |
| Ramos Technology             | 1         | 0.12%   |
| Qumo                         | 1         | 0.12%   |
| Qimonda                      | 1         | 0.12%   |
| Patriot Memory (PDP Systems) | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 13        | 1.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1.34%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 1.12%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 10        | 1.12%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 8         | 0.89%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.89%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.89%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 7         | 0.78%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.78%   |
| Unknown                                                          | 7         | 0.78%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 6         | 0.67%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s            | 6         | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 6         | 0.67%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 6         | 0.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.67%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.67%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 5         | 0.56%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 5         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.56%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.56%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.56%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.56%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 5         | 0.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.56%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 5         | 0.56%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 4         | 0.45%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.45%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 0.45%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.45%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.45%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 3200MT/s            | 4         | 0.45%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 334       | 49.55%  |
| DDR3    | 213       | 31.6%   |
| DDR2    | 27        | 4.01%   |
| LPDDR4  | 24        | 3.56%   |
| SDRAM   | 23        | 3.41%   |
| LPDDR5  | 21        | 3.12%   |
| LPDDR3  | 9         | 1.34%   |
| Unknown | 8         | 1.19%   |
| DDR5    | 7         | 1.04%   |
| DDR     | 5         | 0.74%   |
| DRAM    | 3         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 442       | 66.67%  |
| DIMM         | 181       | 27.3%   |
| Row Of Chips | 38        | 5.73%   |
| Unknown      | 2         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 275       | 35.21%  |
| 4096  | 254       | 32.52%  |
| 16384 | 106       | 13.57%  |
| 2048  | 91        | 11.65%  |
| 32768 | 31        | 3.97%   |
| 1024  | 21        | 2.69%   |
| 512   | 2         | 0.26%   |
| 128   | 1         | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 149       | 20.05%  |
| 2667    | 131       | 17.63%  |
| 3200    | 129       | 17.36%  |
| 2400    | 45        | 6.06%   |
| 1333    | 41        | 5.52%   |
| 1334    | 29        | 3.9%    |
| 3600    | 24        | 3.23%   |
| 2133    | 24        | 3.23%   |
| Unknown | 21        | 2.83%   |
| 6400    | 19        | 2.56%   |
| 3266    | 12        | 1.62%   |
| 800     | 11        | 1.48%   |
| 1867    | 9         | 1.21%   |
| 667     | 8         | 1.08%   |
| 3733    | 7         | 0.94%   |
| 3000    | 7         | 0.94%   |
| 4800    | 6         | 0.81%   |
| 1067    | 6         | 0.81%   |
| 1066    | 6         | 0.81%   |
| 4267    | 5         | 0.67%   |
| 4199    | 5         | 0.67%   |
| 2666    | 5         | 0.67%   |
| 3800    | 4         | 0.54%   |
| 533     | 4         | 0.54%   |
| 5500    | 3         | 0.4%    |
| 3066    | 3         | 0.4%    |
| 1866    | 3         | 0.4%    |
| 1800    | 3         | 0.4%    |
| 5600    | 2         | 0.27%   |
| 3400    | 2         | 0.27%   |
| 1776    | 2         | 0.27%   |
| 975     | 2         | 0.27%   |
| 400     | 2         | 0.27%   |
| 333     | 2         | 0.27%   |
| 8400    | 1         | 0.13%   |
| 5200    | 1         | 0.13%   |
| 4266    | 1         | 0.13%   |
| 3666    | 1         | 0.13%   |
| 3500    | 1         | 0.13%   |
| 3467    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 32.14%  |
| Seiko Epson         | 7         | 25%     |
| Samsung Electronics | 4         | 14.29%  |
| Ricoh               | 2         | 7.14%   |
| iDPRT               | 2         | 7.14%   |
| Prolific Technology | 1         | 3.57%   |
| Philips (or NXP)    | 1         | 3.57%   |
| Canon               | 1         | 3.57%   |
| Brother Industries  | 1         | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Seiko Epson L120 Series                                | 3         | 10.71%  |
| iDPRT SP410                                            | 2         | 7.14%   |
| HP LaserJet Professional P 1102w                       | 2         | 7.14%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 3.57%   |
| Seiko Epson L360 Series                                | 1         | 3.57%   |
| Seiko Epson L3110 Series                               | 1         | 3.57%   |
| Seiko Epson L210 Series                                | 1         | 3.57%   |
| Samsung SCX-3400 Series                                | 1         | 3.57%   |
| Samsung ML-2010P Mono Laser Printer                    | 1         | 3.57%   |
| Samsung M2020 Series                                   | 1         | 3.57%   |
| Samsung Composite Device                               | 1         | 3.57%   |
| Ricoh Printing Support                                 | 1         | 3.57%   |
| Ricoh Aficio SP 3510DN                                 | 1         | 3.57%   |
| Prolific PL2305 Parallel Port                          | 1         | 3.57%   |
| Philips (or NXP) USB Printer                           | 1         | 3.57%   |
| HP Smart Tank 530 series                               | 1         | 3.57%   |
| HP Smart Tank 510 series                               | 1         | 3.57%   |
| HP LaserJet CP 1025                                    | 1         | 3.57%   |
| HP LaserJet 1020                                       | 1         | 3.57%   |
| HP HP Laser 107w                                       | 1         | 3.57%   |
| HP DeskJet 5810 series                                 | 1         | 3.57%   |
| HP Deskjet 2540 series                                 | 1         | 3.57%   |
| Canon G3000 series                                     | 1         | 3.57%   |
| Brother DCP-T710W                                      | 1         | 3.57%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 191       | 18.84%  |
| IMC Networks                           | 165       | 16.27%  |
| Quanta                                 | 72        | 7.1%    |
| Cheng Uei Precision Industry (Foxlink) | 72        | 7.1%    |
| Realtek Semiconductor                  | 68        | 6.71%   |
| Microdia                               | 62        | 6.11%   |
| Bison Electronics                      | 52        | 5.13%   |
| Sunplus Innovation Technology          | 35        | 3.45%   |
| Logitech                               | 29        | 2.86%   |
| Lite-On Technology                     | 29        | 2.86%   |
| Syntek                                 | 26        | 2.56%   |
| Apple                                  | 24        | 2.37%   |
| Silicon Motion                         | 19        | 1.87%   |
| Suyin                                  | 15        | 1.48%   |
| Acer                                   | 14        | 1.38%   |
| Sonix Technology                       | 13        | 1.28%   |
| KYE Systems (Mouse Systems)            | 11        | 1.08%   |
| ShineTech                              | 10        | 0.99%   |
| Ricoh                                  | 9         | 0.89%   |
| Luxvisions Innotech Limited            | 9         | 0.89%   |
| Y Media                                | 8         | 0.79%   |
| Cubeternet                             | 7         | 0.69%   |
| Generalplus Technology                 | 6         | 0.59%   |
| ALi                                    | 6         | 0.59%   |
| Alcor Micro                            | 6         | 0.59%   |
| OmniVision Technologies                | 5         | 0.49%   |
| Samsung Electronics                    | 4         | 0.39%   |
| Microsoft                              | 4         | 0.39%   |
| Lenovo                                 | 4         | 0.39%   |
| Importek                               | 4         | 0.39%   |
| Huawei Technologies                    | 4         | 0.39%   |
| Z-Star Microelectronics                | 3         | 0.3%    |
| GEMBIRD                                | 3         | 0.3%    |
| Arkmicro Technologies                  | 3         | 0.3%    |
| Sunplus Technology                     | 2         | 0.2%    |
| Pixart Imaging                         | 2         | 0.2%    |
| Genesys Logic                          | 2         | 0.2%    |
| WaveRider Communications               | 1         | 0.1%    |
| Unknown                                | 1         | 0.1%    |
| Trust                                  | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                             | 56        | 5.52%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 56        | 5.52%   |
| Chicony Integrated Camera                                      | 24        | 2.36%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 23        | 2.27%   |
| Microdia Integrated_Webcam_HD                                  | 21        | 2.07%   |
| IMC Networks Integrated Camera                                 | 19        | 1.87%   |
| Syntek Integrated Camera                                       | 17        | 1.67%   |
| Bison Integrated Camera                                        | 16        | 1.58%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 1.48%   |
| Chicony HP Truevision HD camera                                | 14        | 1.38%   |
| Sunplus Integrated_Webcam_HD                                   | 12        | 1.18%   |
| Realtek Integrated_Webcam_HD                                   | 12        | 1.18%   |
| Chicony HP Webcam                                              | 11        | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 11        | 1.08%   |
| Quanta HD Webcam                                               | 10        | 0.99%   |
| Chicony Lenovo EasyCamera                                      | 10        | 0.99%   |
| Bison HD Webcam                                                | 10        | 0.99%   |
| Apple FaceTime HD Camera (Built-in)                            | 10        | 0.99%   |
| Sonix USB2.0 HD UVC WebCam                                     | 9         | 0.89%   |
| ShineTech USB2.0 HD UVC WebCam                                 | 9         | 0.89%   |
| Quanta HD User Facing                                          | 9         | 0.89%   |
| Y Media USB Camera                                             | 8         | 0.79%   |
| Realtek USB Camera                                             | 8         | 0.79%   |
| Logitech HD Pro Webcam C920                                    | 8         | 0.79%   |
| Lite-On HP Webcam                                              | 8         | 0.79%   |
| Quanta HP Webcam                                               | 7         | 0.69%   |
| Quanta HP TrueVision HD Camera                                 | 7         | 0.69%   |
| Chicony HP Wide Vision HD Camera                               | 7         | 0.69%   |
| Chicony HD WebCam                                              | 7         | 0.69%   |
| Chicony EasyCamera                                             | 7         | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 7         | 0.69%   |
| Realtek Lenovo EasyCamera                                      | 6         | 0.59%   |
| Quanta USB2.0 HD UVC WebCam                                    | 6         | 0.59%   |
| Quanta ACER HD User Facing                                     | 6         | 0.59%   |
| Microdia Lenovo EasyCamera                                     | 6         | 0.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 6         | 0.59%   |
| Logitech HD Webcam C525                                        | 6         | 0.59%   |
| Lite-On HP Wide Vision HD Camera                               | 6         | 0.59%   |
| IMC Networks VGA UVC WebCam                                    | 6         | 0.59%   |
| Chicony HP High Definition 1MP Webcam                          | 6         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 35        | 29.17%  |
| Synaptics                  | 28        | 23.33%  |
| Elan Microelectronics      | 23        | 19.17%  |
| Shenzhen Goodix Technology | 22        | 18.33%  |
| Upek                       | 6         | 5%      |
| LighTuning Technology      | 3         | 2.5%    |
| AuthenTec                  | 2         | 1.67%   |
| STMicroelectronics         | 1         | 0.83%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 17        | 14.17%  |
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 13.33%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 5.83%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 5%      |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 5%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 3.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 3.33%   |
| Elan ELAN:ARM-M4                                                           | 4         | 3.33%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 2.5%    |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.5%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.5%    |
| Synaptics  WBDI                                                            | 3         | 2.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.67%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.67%   |
| Synaptics WBDI                                                             | 2         | 1.67%   |
| Synaptics UWP WBDI                                                         | 2         | 1.67%   |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 1.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 1.67%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.67%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 1.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.67%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 1.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.83%   |
| Validity Sensors VFS491                                                    | 1         | 0.83%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.83%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.83%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.83%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.83%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.83%   |
| Synaptics WBDI Device                                                      | 1         | 0.83%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.83%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.83%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.83%   |
| AuthenTec AES2810                                                          | 1         | 0.83%   |
| AuthenTec AES1600                                                          | 1         | 0.83%   |
| Unknown                                                                    | 1         | 0.83%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 13        | 54.17%  |
| Upek                  | 4         | 16.67%  |
| O2 Micro              | 2         | 8.33%   |
| Lenovo                | 2         | 8.33%   |
| Alcor Micro           | 2         | 8.33%   |
| Gemalto (was Gemplus) | 1         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 8         | 33.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 8.33%   |
| Broadcom 58200                                                               | 2         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 8.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.17%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 4.17%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 958       | 68.77%  |
| 1     | 365       | 26.2%   |
| 2     | 64        | 4.59%   |
| 3     | 3         | 0.22%   |
| 7     | 1         | 0.07%   |
| 6     | 1         | 0.07%   |
| 4     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 120       | 24.14%  |
| Net/wireless             | 109       | 21.93%  |
| Graphics card            | 109       | 21.93%  |
| Multimedia controller    | 45        | 9.05%   |
| Chipcard                 | 23        | 4.63%   |
| Camera                   | 23        | 4.63%   |
| Bluetooth                | 21        | 4.23%   |
| Communication controller | 16        | 3.22%   |
| Sound                    | 8         | 1.61%   |
| Storage                  | 6         | 1.21%   |
| Card reader              | 6         | 1.21%   |
| Net/ethernet             | 3         | 0.6%    |
| Unassigned class         | 2         | 0.4%    |
| Storage/raid             | 2         | 0.4%    |
| Network                  | 2         | 0.4%    |
| Flash memory             | 1         | 0.2%    |
| Firewire controller      | 1         | 0.2%    |

