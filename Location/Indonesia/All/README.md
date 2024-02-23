Linux in Indonesia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Indonesia/Desktop/README.md) and [notebooks](/Location/Indonesia/Notebook/README.md).

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

Total: 2072

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| realme        | CloudProXXXX                | Notebook    | [1299621a5e](https://linux-hardware.org/?probe=1299621a5e) | Feb 01, 2024 |
| Lenovo        | G405 20239                  | Notebook    | [7afc820794](https://linux-hardware.org/?probe=7afc820794) | Feb 01, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [98de51c101](https://linux-hardware.org/?probe=98de51c101) | Jan 31, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [348c7c4e82](https://linux-hardware.org/?probe=348c7c4e82) | Jan 31, 2024 |
| Intel         | H81                         | Desktop     | [fac0a305d4](https://linux-hardware.org/?probe=fac0a305d4) | Jan 29, 2024 |
| Lenovo        | ThinkPad L440 20ASS01400    | Notebook    | [c8fad8ec59](https://linux-hardware.org/?probe=c8fad8ec59) | Jan 28, 2024 |
| Dell          | XPS 9320                    | Notebook    | [0214714fb9](https://linux-hardware.org/?probe=0214714fb9) | Jan 27, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [931f000daf](https://linux-hardware.org/?probe=931f000daf) | Jan 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e6681b71bc](https://linux-hardware.org/?probe=e6681b71bc) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [65a3715aa3](https://linux-hardware.org/?probe=65a3715aa3) | Jan 25, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [fe98e7026e](https://linux-hardware.org/?probe=fe98e7026e) | Jan 25, 2024 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | Notebook    | [0e4d078f49](https://linux-hardware.org/?probe=0e4d078f49) | Jan 25, 2024 |
| Lenovo        | ThinkPad T480 20L6S3L400    | Notebook    | [3861071640](https://linux-hardware.org/?probe=3861071640) | Jan 24, 2024 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [b8fc987633](https://linux-hardware.org/?probe=b8fc987633) | Jan 24, 2024 |
| Clevo         | M720SRS                     | Notebook    | [c0f6248edd](https://linux-hardware.org/?probe=c0f6248edd) | Jan 24, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [8edec841f0](https://linux-hardware.org/?probe=8edec841f0) | Jan 22, 2024 |
| Lenovo        | G400 20235                  | Notebook    | [2097e4f7e6](https://linux-hardware.org/?probe=2097e4f7e6) | Jan 22, 2024 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [2b604752a0](https://linux-hardware.org/?probe=2b604752a0) | Jan 21, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [92f943771a](https://linux-hardware.org/?probe=92f943771a) | Jan 19, 2024 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | Notebook    | [9efd333805](https://linux-hardware.org/?probe=9efd333805) | Jan 18, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [040715bf2d](https://linux-hardware.org/?probe=040715bf2d) | Jan 17, 2024 |
| Dell          | 0MHWCY A00                  | All in one  | [021cf9cd7c](https://linux-hardware.org/?probe=021cf9cd7c) | Jan 17, 2024 |
| Microsoft     | Surface Pro 8               | Tablet      | [0a7cafc47f](https://linux-hardware.org/?probe=0a7cafc47f) | Jan 16, 2024 |
| ECS           | H61H2-MV                    | Desktop     | [09c20c7740](https://linux-hardware.org/?probe=09c20c7740) | Jan 15, 2024 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [22802134b7](https://linux-hardware.org/?probe=22802134b7) | Jan 15, 2024 |
| Lenovo        | ThinkPad T420 4180PV4       | Notebook    | [3277e75c3e](https://linux-hardware.org/?probe=3277e75c3e) | Jan 15, 2024 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [1af5c7bda4](https://linux-hardware.org/?probe=1af5c7bda4) | Jan 15, 2024 |
| HP            | 81B4 01                     | Desktop     | [2a8624aed6](https://linux-hardware.org/?probe=2a8624aed6) | Jan 15, 2024 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [7b76b0de4f](https://linux-hardware.org/?probe=7b76b0de4f) | Jan 13, 2024 |
| HP            | 250 G5 Notebook PC          | Notebook    | [8fb1c8650f](https://linux-hardware.org/?probe=8fb1c8650f) | Jan 12, 2024 |
| Dell          | Vostro 3401                 | Notebook    | [cd47812859](https://linux-hardware.org/?probe=cd47812859) | Jan 11, 2024 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [8431e0e3d7](https://linux-hardware.org/?probe=8431e0e3d7) | Jan 10, 2024 |
| Unknown       | Unknown                     | Notebook    | [2d74d756b3](https://linux-hardware.org/?probe=2d74d756b3) | Jan 10, 2024 |
| Unknown       | DS16                        | Notebook    | [1951d37c43](https://linux-hardware.org/?probe=1951d37c43) | Jan 10, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [9cfcebcd8c](https://linux-hardware.org/?probe=9cfcebcd8c) | Jan 09, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [0306a42404](https://linux-hardware.org/?probe=0306a42404) | Jan 09, 2024 |
| ASUSTek       | TP410UR                     | Convertible | [3063278c30](https://linux-hardware.org/?probe=3063278c30) | Jan 09, 2024 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [825a5ed72b](https://linux-hardware.org/?probe=825a5ed72b) | Jan 08, 2024 |
| Dell          | Inspiron 3576               | Notebook    | [ff3dc4d39e](https://linux-hardware.org/?probe=ff3dc4d39e) | Jan 08, 2024 |
| HP            | Presario CQ42               | Notebook    | [6addf001a5](https://linux-hardware.org/?probe=6addf001a5) | Jan 08, 2024 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4572d32ab9](https://linux-hardware.org/?probe=4572d32ab9) | Jan 06, 2024 |
| HP            | Laptop 14s-cf3xxx           | Notebook    | [416bb92e6e](https://linux-hardware.org/?probe=416bb92e6e) | Jan 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [afb1d878cd](https://linux-hardware.org/?probe=afb1d878cd) | Jan 04, 2024 |
| Lenovo        | ThinkPad X250 20CL001LUS    | Notebook    | [f0f3c9a66c](https://linux-hardware.org/?probe=f0f3c9a66c) | Jan 04, 2024 |
| Acidanther... | MacBookPro16,4              | Notebook    | [3c8c520472](https://linux-hardware.org/?probe=3c8c520472) | Jan 02, 2024 |
| Lenovo        | ThinkPad X200s 7469W92      | Notebook    | [6ea14ec02e](https://linux-hardware.org/?probe=6ea14ec02e) | Jan 01, 2024 |
| Lenovo        | G400s 20244                 | Notebook    | [29ab65f09e](https://linux-hardware.org/?probe=29ab65f09e) | Jan 01, 2024 |
| Lenovo        | G400s 20244                 | Notebook    | [3afdb557c8](https://linux-hardware.org/?probe=3afdb557c8) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [d2112b91c1](https://linux-hardware.org/?probe=d2112b91c1) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [252e78398a](https://linux-hardware.org/?probe=252e78398a) | Jan 01, 2024 |
| Lenovo        | ThinkPad P50 20EQS3YS00     | Notebook    | [34294e5b8b](https://linux-hardware.org/?probe=34294e5b8b) | Dec 31, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [0d985ff465](https://linux-hardware.org/?probe=0d985ff465) | Dec 31, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [32ce52498b](https://linux-hardware.org/?probe=32ce52498b) | Dec 28, 2023 |
| Dell          | 033FF6 A00                  | Desktop     | [f54cfd23ee](https://linux-hardware.org/?probe=f54cfd23ee) | Dec 28, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | Notebook    | [1192d8e746](https://linux-hardware.org/?probe=1192d8e746) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | Notebook    | [3fdb3a1cc7](https://linux-hardware.org/?probe=3fdb3a1cc7) | Dec 27, 2023 |
| Dell          | 033FF6 A00                  | Desktop     | [977367b99e](https://linux-hardware.org/?probe=977367b99e) | Dec 26, 2023 |
| AZW           | MINI S 10                   | Desktop     | [fbeeeb79f5](https://linux-hardware.org/?probe=fbeeeb79f5) | Dec 25, 2023 |
| Intel         | B75                         | Desktop     | [65bfc8c4cf](https://linux-hardware.org/?probe=65bfc8c4cf) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [3bd91ab067](https://linux-hardware.org/?probe=3bd91ab067) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [d49a8fe4d4](https://linux-hardware.org/?probe=d49a8fe4d4) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [f1c9eab3f4](https://linux-hardware.org/?probe=f1c9eab3f4) | Dec 24, 2023 |
| ASUSTek       | X441BA                      | Notebook    | [04e5c55b92](https://linux-hardware.org/?probe=04e5c55b92) | Dec 23, 2023 |
| Dell          | 033FF6 A00                  | Desktop     | [88cad415fb](https://linux-hardware.org/?probe=88cad415fb) | Dec 21, 2023 |
| ECS           | H81H3-MV                    | Desktop     | [95bd5100ac](https://linux-hardware.org/?probe=95bd5100ac) | Dec 20, 2023 |
| Dell          | Latitude E6400              | Notebook    | [67d4d37a04](https://linux-hardware.org/?probe=67d4d37a04) | Dec 20, 2023 |
| Unknown       | Unknown                     | Other       | [92d87c0e52](https://linux-hardware.org/?probe=92d87c0e52) | Dec 19, 2023 |
| Lenovo        | ThinkPad T590 20N5S44300    | Notebook    | [5a90e712d1](https://linux-hardware.org/?probe=5a90e712d1) | Dec 19, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [ec237cc638](https://linux-hardware.org/?probe=ec237cc638) | Dec 19, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [97e3b8d570](https://linux-hardware.org/?probe=97e3b8d570) | Dec 18, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a6d28b0e6a](https://linux-hardware.org/?probe=a6d28b0e6a) | Dec 18, 2023 |
| Medion        | S17403                      | Notebook    | [250e479ad5](https://linux-hardware.org/?probe=250e479ad5) | Dec 18, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [9afc3e4d49](https://linux-hardware.org/?probe=9afc3e4d49) | Dec 16, 2023 |
| ASUSTek       | UX490UAR                    | Notebook    | [e8aa69b910](https://linux-hardware.org/?probe=e8aa69b910) | Dec 16, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [25c5c9bb33](https://linux-hardware.org/?probe=25c5c9bb33) | Dec 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b7194dbbb8](https://linux-hardware.org/?probe=b7194dbbb8) | Dec 15, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [f4af1a07e3](https://linux-hardware.org/?probe=f4af1a07e3) | Dec 15, 2023 |
| Lenovo        | ThinkPad L330 34701V0       | Notebook    | [d418989434](https://linux-hardware.org/?probe=d418989434) | Dec 15, 2023 |
| Samsung       | 300E5E/300E4E/300E5V/300... | Notebook    | [e7d5f85bea](https://linux-hardware.org/?probe=e7d5f85bea) | Dec 13, 2023 |
| Dell          | Latitude E7240              | Notebook    | [4fcd011c61](https://linux-hardware.org/?probe=4fcd011c61) | Dec 13, 2023 |
| ASUSTek       | TP410UR                     | Convertible | [2442ce24b5](https://linux-hardware.org/?probe=2442ce24b5) | Dec 11, 2023 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [e7bbe1d5e7](https://linux-hardware.org/?probe=e7bbe1d5e7) | Dec 10, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [72c0c4e3a0](https://linux-hardware.org/?probe=72c0c4e3a0) | Dec 09, 2023 |
| Dell          | Latitude E6400              | Notebook    | [0f4aeac8ca](https://linux-hardware.org/?probe=0f4aeac8ca) | Dec 09, 2023 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [4167bf6fe4](https://linux-hardware.org/?probe=4167bf6fe4) | Dec 08, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [29a2194396](https://linux-hardware.org/?probe=29a2194396) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [1b3b476186](https://linux-hardware.org/?probe=1b3b476186) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [58547d36b7](https://linux-hardware.org/?probe=58547d36b7) | Dec 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [b5430476af](https://linux-hardware.org/?probe=b5430476af) | Dec 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [6e61bec2ab](https://linux-hardware.org/?probe=6e61bec2ab) | Dec 06, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [daa41db960](https://linux-hardware.org/?probe=daa41db960) | Dec 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [becdc5222d](https://linux-hardware.org/?probe=becdc5222d) | Dec 05, 2023 |
| ASUSTek       | X441BA                      | Notebook    | [272c82d8eb](https://linux-hardware.org/?probe=272c82d8eb) | Dec 05, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [b3a0f94dfd](https://linux-hardware.org/?probe=b3a0f94dfd) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [b3bc756e27](https://linux-hardware.org/?probe=b3bc756e27) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [9af224bc40](https://linux-hardware.org/?probe=9af224bc40) | Dec 04, 2023 |
| Xiaomi        | Redmi 2 (Wingtech WT8804... | Soc         | [a35cc27d50](https://linux-hardware.org/?probe=a35cc27d50) | Dec 03, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [9a4c0266e8](https://linux-hardware.org/?probe=9a4c0266e8) | Dec 02, 2023 |
| Intel         | H61                         | Desktop     | [9951d7579f](https://linux-hardware.org/?probe=9951d7579f) | Dec 02, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [92a2b35bc8](https://linux-hardware.org/?probe=92a2b35bc8) | Dec 01, 2023 |
| Intel         | H61                         | Desktop     | [a0a26787ca](https://linux-hardware.org/?probe=a0a26787ca) | Nov 30, 2023 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | Notebook    | [f43aaf1d39](https://linux-hardware.org/?probe=f43aaf1d39) | Nov 29, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [12e26441e1](https://linux-hardware.org/?probe=12e26441e1) | Nov 27, 2023 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [96bb14bbf4](https://linux-hardware.org/?probe=96bb14bbf4) | Nov 25, 2023 |
| Minix         | H61M-USB3 V1.2              | Desktop     | [2024379183](https://linux-hardware.org/?probe=2024379183) | Nov 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [dbfedd49f8](https://linux-hardware.org/?probe=dbfedd49f8) | Nov 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [a6240c8d6a](https://linux-hardware.org/?probe=a6240c8d6a) | Nov 20, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B30... | Notebook    | [5685f17122](https://linux-hardware.org/?probe=5685f17122) | Nov 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [95624a1d82](https://linux-hardware.org/?probe=95624a1d82) | Nov 18, 2023 |
| Dell          | XPS 9320                    | Notebook    | [04760461ba](https://linux-hardware.org/?probe=04760461ba) | Nov 17, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [39c7028c1e](https://linux-hardware.org/?probe=39c7028c1e) | Nov 15, 2023 |
| ADVAN         | 1405                        | Notebook    | [55a639a506](https://linux-hardware.org/?probe=55a639a506) | Nov 14, 2023 |
| ASUSTek       | T100TAS                     | Notebook    | [ff4068e60a](https://linux-hardware.org/?probe=ff4068e60a) | Nov 12, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [be4c8862d0](https://linux-hardware.org/?probe=be4c8862d0) | Nov 11, 2023 |
| Khadas        | VIM2                        | Soc         | [3db877cd01](https://linux-hardware.org/?probe=3db877cd01) | Nov 09, 2023 |
| Lenovo        | 0x36C6                      | All in one  | [8a4dfa9648](https://linux-hardware.org/?probe=8a4dfa9648) | Nov 09, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [ba5db231dd](https://linux-hardware.org/?probe=ba5db231dd) | Nov 08, 2023 |
| Dell          | 0HH807                      | Desktop     | [300ee3d8f5](https://linux-hardware.org/?probe=300ee3d8f5) | Nov 08, 2023 |
| Lenovo        | ThinkPad Edge E465 BE465... | Notebook    | [54b9aa1cac](https://linux-hardware.org/?probe=54b9aa1cac) | Nov 07, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [1e2ba13164](https://linux-hardware.org/?probe=1e2ba13164) | Nov 06, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [04327aa85c](https://linux-hardware.org/?probe=04327aa85c) | Nov 06, 2023 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [61828bc39f](https://linux-hardware.org/?probe=61828bc39f) | Nov 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [669430e32e](https://linux-hardware.org/?probe=669430e32e) | Nov 04, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [f0354d2416](https://linux-hardware.org/?probe=f0354d2416) | Nov 04, 2023 |
| Acidanther... | MacBookPro15,2              | Notebook    | [ae60650070](https://linux-hardware.org/?probe=ae60650070) | Nov 04, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [0ce0a4d87a](https://linux-hardware.org/?probe=0ce0a4d87a) | Nov 04, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | X456UR                      | Notebook    | [9a0a4dfd02](https://linux-hardware.org/?probe=9a0a4dfd02) | Nov 02, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [2b76c45313](https://linux-hardware.org/?probe=2b76c45313) | Nov 02, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [fffa5fb420](https://linux-hardware.org/?probe=fffa5fb420) | Nov 02, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [a7f47546e5](https://linux-hardware.org/?probe=a7f47546e5) | Nov 01, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [8901bca741](https://linux-hardware.org/?probe=8901bca741) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [5787618dae](https://linux-hardware.org/?probe=5787618dae) | Oct 31, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [bc8c6e67a9](https://linux-hardware.org/?probe=bc8c6e67a9) | Oct 28, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [63b5c65c01](https://linux-hardware.org/?probe=63b5c65c01) | Oct 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [220dddac59](https://linux-hardware.org/?probe=220dddac59) | Oct 28, 2023 |
| Dell          | Precision 5530              | Notebook    | [e707fe59cc](https://linux-hardware.org/?probe=e707fe59cc) | Oct 27, 2023 |
| Dell          | 0HH807                      | Desktop     | [7f15d65c22](https://linux-hardware.org/?probe=7f15d65c22) | Oct 27, 2023 |
| HP            | Notebook                    | Notebook    | [1f270f615f](https://linux-hardware.org/?probe=1f270f615f) | Oct 27, 2023 |
| Acer          | EG31M R01-C3                | Desktop     | [8a4232c8f0](https://linux-hardware.org/?probe=8a4232c8f0) | Oct 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [a70d4b8a0d](https://linux-hardware.org/?probe=a70d4b8a0d) | Oct 25, 2023 |
| HP            | 198E                        | Desktop     | [3102593d74](https://linux-hardware.org/?probe=3102593d74) | Oct 25, 2023 |
| Dell          | Inspiron One 2310           | Notebook    | [1a8d313e86](https://linux-hardware.org/?probe=1a8d313e86) | Oct 25, 2023 |
| Dell          | Latitude 5285               | Notebook    | [9af5195620](https://linux-hardware.org/?probe=9af5195620) | Oct 24, 2023 |
| Dell          | Latitude 5320               | Notebook    | [520c2effa3](https://linux-hardware.org/?probe=520c2effa3) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [5b608b97fc](https://linux-hardware.org/?probe=5b608b97fc) | Oct 23, 2023 |
| Dell          | Latitude 5285               | Notebook    | [9552613f54](https://linux-hardware.org/?probe=9552613f54) | Oct 23, 2023 |
| Dell          | Latitude E6320              | Notebook    | [c6965e07e3](https://linux-hardware.org/?probe=c6965e07e3) | Oct 21, 2023 |
| Dell          | Inspiron 3458               | Notebook    | [ff4adff045](https://linux-hardware.org/?probe=ff4adff045) | Oct 21, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [fe4a9ec4d0](https://linux-hardware.org/?probe=fe4a9ec4d0) | Oct 20, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [1c0c1df851](https://linux-hardware.org/?probe=1c0c1df851) | Oct 20, 2023 |
| MSI           | 770T-C45                    | Desktop     | [bbe901612f](https://linux-hardware.org/?probe=bbe901612f) | Oct 20, 2023 |
| Toshiba       | dynabook R732/H             | Notebook    | [4852b6da95](https://linux-hardware.org/?probe=4852b6da95) | Oct 20, 2023 |
| HP            | Notebook                    | Notebook    | [3fb8313450](https://linux-hardware.org/?probe=3fb8313450) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [71ffea0397](https://linux-hardware.org/?probe=71ffea0397) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [9ab2c722a5](https://linux-hardware.org/?probe=9ab2c722a5) | Oct 19, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [459dc02cda](https://linux-hardware.org/?probe=459dc02cda) | Oct 18, 2023 |
| Acer          | Aspire E3-112M              | Notebook    | [11d6580d3e](https://linux-hardware.org/?probe=11d6580d3e) | Oct 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [0270e71d5e](https://linux-hardware.org/?probe=0270e71d5e) | Oct 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [329a5f99e0](https://linux-hardware.org/?probe=329a5f99e0) | Oct 18, 2023 |
| MicroByte     | ezbook                      | Notebook    | [c67055c10c](https://linux-hardware.org/?probe=c67055c10c) | Oct 17, 2023 |
| MicroByte     | ezbook                      | Notebook    | [5018eaffae](https://linux-hardware.org/?probe=5018eaffae) | Oct 17, 2023 |
| Toshiba       | Satellite L645              | Notebook    | [5bea545bf5](https://linux-hardware.org/?probe=5bea545bf5) | Oct 16, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [bfbd0b0a49](https://linux-hardware.org/?probe=bfbd0b0a49) | Oct 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [ec059c9ea7](https://linux-hardware.org/?probe=ec059c9ea7) | Oct 15, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [3d63dd4590](https://linux-hardware.org/?probe=3d63dd4590) | Oct 13, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [c1e1d017af](https://linux-hardware.org/?probe=c1e1d017af) | Oct 13, 2023 |
| Toshiba       | Satellite C55D-C            | Notebook    | [e083a8012f](https://linux-hardware.org/?probe=e083a8012f) | Oct 11, 2023 |
| HP            | 430                         | Notebook    | [e62771b9a7](https://linux-hardware.org/?probe=e62771b9a7) | Oct 09, 2023 |
| HP            | 430                         | Notebook    | [71211a4eda](https://linux-hardware.org/?probe=71211a4eda) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f3348806a2](https://linux-hardware.org/?probe=f3348806a2) | Oct 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f269e7a6ee](https://linux-hardware.org/?probe=f269e7a6ee) | Oct 09, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [1bb42f8755](https://linux-hardware.org/?probe=1bb42f8755) | Oct 09, 2023 |
| Acer          | Swift SF314-56G             | Notebook    | [2696a8d9c0](https://linux-hardware.org/?probe=2696a8d9c0) | Oct 08, 2023 |
| Acidanther... | MacBookPro16,4              | Notebook    | [c40356b94d](https://linux-hardware.org/?probe=c40356b94d) | Oct 05, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [d48122086b](https://linux-hardware.org/?probe=d48122086b) | Oct 04, 2023 |
| Acer          | Swift SF314-56G             | Notebook    | [15b613a264](https://linux-hardware.org/?probe=15b613a264) | Oct 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [0df81159a2](https://linux-hardware.org/?probe=0df81159a2) | Oct 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a3773ae099](https://linux-hardware.org/?probe=a3773ae099) | Oct 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [25211e6ce1](https://linux-hardware.org/?probe=25211e6ce1) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| ASRock        | A88M-G                      | Desktop     | [a918b08771](https://linux-hardware.org/?probe=a918b08771) | Sep 30, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [80ac43658d](https://linux-hardware.org/?probe=80ac43658d) | Sep 30, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [79b4f4f30e](https://linux-hardware.org/?probe=79b4f4f30e) | Sep 30, 2023 |
| Gigabyte      | P31-ES3G                    | Desktop     | [bee14e504c](https://linux-hardware.org/?probe=bee14e504c) | Sep 30, 2023 |
| Lenovo        | ThinkPad L530 24783R8       | Notebook    | [eda040f456](https://linux-hardware.org/?probe=eda040f456) | Sep 30, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [7c8b825512](https://linux-hardware.org/?probe=7c8b825512) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [d95e370c54](https://linux-hardware.org/?probe=d95e370c54) | Sep 29, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [eeb582da25](https://linux-hardware.org/?probe=eeb582da25) | Sep 28, 2023 |
| Dell          | Latitude 7490               | Notebook    | [6f5e4547fa](https://linux-hardware.org/?probe=6f5e4547fa) | Sep 27, 2023 |
| ZOTAC         | NM10                        | Desktop     | [8932b16aa1](https://linux-hardware.org/?probe=8932b16aa1) | Sep 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [8bb2e054ec](https://linux-hardware.org/?probe=8bb2e054ec) | Sep 26, 2023 |
| Acer          | Aspire M5910                | Desktop     | [5b44d1de35](https://linux-hardware.org/?probe=5b44d1de35) | Sep 25, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [6383f263a8](https://linux-hardware.org/?probe=6383f263a8) | Sep 25, 2023 |
| Toshiba       | dynabook R632/H             | Notebook    | [7279759e40](https://linux-hardware.org/?probe=7279759e40) | Sep 25, 2023 |
| Acer          | Aspire S3                   | Notebook    | [4b2b76bdb3](https://linux-hardware.org/?probe=4b2b76bdb3) | Sep 24, 2023 |
| Acer          | Aspire S3                   | Notebook    | [723a872112](https://linux-hardware.org/?probe=723a872112) | Sep 24, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [4c12bddd77](https://linux-hardware.org/?probe=4c12bddd77) | Sep 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [80e28a9df2](https://linux-hardware.org/?probe=80e28a9df2) | Sep 22, 2023 |
| HP            | Laptop 14-ep0xxx            | Notebook    | [ee7b0c8506](https://linux-hardware.org/?probe=ee7b0c8506) | Sep 21, 2023 |
| Lenovo        | V14 G3 IAP 82TS             | Notebook    | [2528381c0e](https://linux-hardware.org/?probe=2528381c0e) | Sep 21, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [efafe71bd6](https://linux-hardware.org/?probe=efafe71bd6) | Sep 21, 2023 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [a1356bddb2](https://linux-hardware.org/?probe=a1356bddb2) | Sep 21, 2023 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [77e008b6d9](https://linux-hardware.org/?probe=77e008b6d9) | Sep 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [09433de4b0](https://linux-hardware.org/?probe=09433de4b0) | Sep 20, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [98a32c8241](https://linux-hardware.org/?probe=98a32c8241) | Sep 19, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [a8995def08](https://linux-hardware.org/?probe=a8995def08) | Sep 19, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [417ad95c4c](https://linux-hardware.org/?probe=417ad95c4c) | Sep 18, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c27b81ea3e](https://linux-hardware.org/?probe=c27b81ea3e) | Sep 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [378490ed0b](https://linux-hardware.org/?probe=378490ed0b) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| HP            | 245 G7 Notebook PC          | Notebook    | [ab68dea087](https://linux-hardware.org/?probe=ab68dea087) | Sep 14, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [877e70bb6f](https://linux-hardware.org/?probe=877e70bb6f) | Sep 14, 2023 |
| MSI           | MS-B9091                    | Desktop     | [5b1250945b](https://linux-hardware.org/?probe=5b1250945b) | Sep 11, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [6259de24be](https://linux-hardware.org/?probe=6259de24be) | Sep 11, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [00e5dd81d7](https://linux-hardware.org/?probe=00e5dd81d7) | Sep 10, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [16c285bb07](https://linux-hardware.org/?probe=16c285bb07) | Sep 10, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [c59551fc6f](https://linux-hardware.org/?probe=c59551fc6f) | Sep 09, 2023 |
| MSI           | MS-B9091                    | Desktop     | [226300a88d](https://linux-hardware.org/?probe=226300a88d) | Sep 09, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [5564e70c85](https://linux-hardware.org/?probe=5564e70c85) | Sep 09, 2023 |
| ASUSTek       | X201EP                      | Notebook    | [a714c5a35a](https://linux-hardware.org/?probe=a714c5a35a) | Sep 09, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [34e95a943a](https://linux-hardware.org/?probe=34e95a943a) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [cbd5cf3e4b](https://linux-hardware.org/?probe=cbd5cf3e4b) | Sep 08, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [89b56b4baf](https://linux-hardware.org/?probe=89b56b4baf) | Sep 06, 2023 |
| Intel         | NUC12WSBi5 M46425-304       | Mini pc     | [d75c936b50](https://linux-hardware.org/?probe=d75c936b50) | Sep 06, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [56f00eec4a](https://linux-hardware.org/?probe=56f00eec4a) | Sep 05, 2023 |
| Sony          | VGN-CS108D                  | Notebook    | [24bf5bb06c](https://linux-hardware.org/?probe=24bf5bb06c) | Sep 05, 2023 |
| Acer          | Veriton M480                | Desktop     | [0c97015cce](https://linux-hardware.org/?probe=0c97015cce) | Sep 05, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [1a1c5e43bc](https://linux-hardware.org/?probe=1a1c5e43bc) | Sep 05, 2023 |
| AXIOO         | Mybook 14E                  | Notebook    | [b6ddb628dc](https://linux-hardware.org/?probe=b6ddb628dc) | Sep 04, 2023 |
| Foxconn       | G31MX Series                | Desktop     | [4b4c5fb5f8](https://linux-hardware.org/?probe=4b4c5fb5f8) | Sep 04, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [6edc4e910d](https://linux-hardware.org/?probe=6edc4e910d) | Sep 04, 2023 |
| HP            | EliteBook Revolve 810 G2    | Notebook    | [3f102b35e3](https://linux-hardware.org/?probe=3f102b35e3) | Sep 04, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [e27673ed4c](https://linux-hardware.org/?probe=e27673ed4c) | Sep 03, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [959fb04734](https://linux-hardware.org/?probe=959fb04734) | Sep 03, 2023 |
| Sony          | VPCYB15AG                   | Notebook    | [e192029ff0](https://linux-hardware.org/?probe=e192029ff0) | Sep 03, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [2180bc1b72](https://linux-hardware.org/?probe=2180bc1b72) | Sep 01, 2023 |
| Acer          | Aspire E5-475G              | Notebook    | [55542f9b89](https://linux-hardware.org/?probe=55542f9b89) | Aug 31, 2023 |
| Dell          | Latitude E6410              | Notebook    | [c2337bbe75](https://linux-hardware.org/?probe=c2337bbe75) | Aug 31, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [13ec5c53cf](https://linux-hardware.org/?probe=13ec5c53cf) | Aug 31, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [5cfa9a748f](https://linux-hardware.org/?probe=5cfa9a748f) | Aug 31, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [02708536f4](https://linux-hardware.org/?probe=02708536f4) | Aug 30, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [f7a484830d](https://linux-hardware.org/?probe=f7a484830d) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aa10544f35](https://linux-hardware.org/?probe=aa10544f35) | Aug 30, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2a2adfdc2e](https://linux-hardware.org/?probe=2a2adfdc2e) | Aug 30, 2023 |
| Fujitsu       | FMVU14003                   | Notebook    | [8da3625e06](https://linux-hardware.org/?probe=8da3625e06) | Aug 27, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [5b334ec725](https://linux-hardware.org/?probe=5b334ec725) | Aug 27, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [1986877980](https://linux-hardware.org/?probe=1986877980) | Aug 25, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [2a72d00223](https://linux-hardware.org/?probe=2a72d00223) | Aug 25, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [f79de96905](https://linux-hardware.org/?probe=f79de96905) | Aug 23, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [abae84243d](https://linux-hardware.org/?probe=abae84243d) | Aug 23, 2023 |
| Dell          | Latitude E6410              | Notebook    | [fbaef9218f](https://linux-hardware.org/?probe=fbaef9218f) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [8fd1db4fee](https://linux-hardware.org/?probe=8fd1db4fee) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [2cbbb89cd4](https://linux-hardware.org/?probe=2cbbb89cd4) | Aug 21, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [1d023bc980](https://linux-hardware.org/?probe=1d023bc980) | Aug 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c1a5eb75bf](https://linux-hardware.org/?probe=c1a5eb75bf) | Aug 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c47971e406](https://linux-hardware.org/?probe=c47971e406) | Aug 21, 2023 |
| Intel         | H81                         | Desktop     | [70d2da2312](https://linux-hardware.org/?probe=70d2da2312) | Aug 20, 2023 |
| Lenovo        | ThinkPad T540p 20BFS02S0... | Notebook    | [2f59ec7141](https://linux-hardware.org/?probe=2f59ec7141) | Aug 18, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [f368b5bf17](https://linux-hardware.org/?probe=f368b5bf17) | Aug 18, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [7f7f077fda](https://linux-hardware.org/?probe=7f7f077fda) | Aug 18, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [2c4ded9440](https://linux-hardware.org/?probe=2c4ded9440) | Aug 18, 2023 |
| Toshiba       | Satellite L510              | Notebook    | [f06d068ca0](https://linux-hardware.org/?probe=f06d068ca0) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [b7a28997df](https://linux-hardware.org/?probe=b7a28997df) | Aug 15, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [b78f4bf01d](https://linux-hardware.org/?probe=b78f4bf01d) | Aug 15, 2023 |
| MSI           | 3666h                       | Desktop     | [d3f51a2bf0](https://linux-hardware.org/?probe=d3f51a2bf0) | Aug 15, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | Notebook    | [c192c37af2](https://linux-hardware.org/?probe=c192c37af2) | Aug 14, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [857539aaba](https://linux-hardware.org/?probe=857539aaba) | Aug 14, 2023 |
| Dell          | 03015M A01                  | Server      | [82a456951b](https://linux-hardware.org/?probe=82a456951b) | Aug 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0ecb69efbc](https://linux-hardware.org/?probe=0ecb69efbc) | Aug 14, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2a753fd907](https://linux-hardware.org/?probe=2a753fd907) | Aug 14, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [182445f47d](https://linux-hardware.org/?probe=182445f47d) | Aug 13, 2023 |
| MSI           | Katana GF66 11UD            | Notebook    | [e7e9bfd605](https://linux-hardware.org/?probe=e7e9bfd605) | Aug 13, 2023 |
| Samsung       | 960XFH                      | Notebook    | [b7f35fe8b5](https://linux-hardware.org/?probe=b7f35fe8b5) | Aug 13, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [5d3d27c8bb](https://linux-hardware.org/?probe=5d3d27c8bb) | Aug 12, 2023 |
| Acer          | One Z1402                   | Notebook    | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [fadee3e38d](https://linux-hardware.org/?probe=fadee3e38d) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [49a3480efb](https://linux-hardware.org/?probe=49a3480efb) | Aug 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | Notebook    | [6de592988e](https://linux-hardware.org/?probe=6de592988e) | Aug 09, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [f78ce03ad4](https://linux-hardware.org/?probe=f78ce03ad4) | Aug 08, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [60d9dcfa89](https://linux-hardware.org/?probe=60d9dcfa89) | Aug 08, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [1c68b4d24a](https://linux-hardware.org/?probe=1c68b4d24a) | Aug 08, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [8491f5fc3b](https://linux-hardware.org/?probe=8491f5fc3b) | Aug 07, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [eab0544dc6](https://linux-hardware.org/?probe=eab0544dc6) | Aug 06, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [738a42f72e](https://linux-hardware.org/?probe=738a42f72e) | Aug 05, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [abb19010d2](https://linux-hardware.org/?probe=abb19010d2) | Aug 05, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [50be5e5725](https://linux-hardware.org/?probe=50be5e5725) | Aug 05, 2023 |
| Dell          | Latitude E6410              | Notebook    | [ad46549b01](https://linux-hardware.org/?probe=ad46549b01) | Aug 04, 2023 |
| Dell          | Latitude E6410              | Notebook    | [e2364d5aac](https://linux-hardware.org/?probe=e2364d5aac) | Aug 04, 2023 |
| MSI           | H81M-E35 V2                 | Desktop     | [2e72dc6560](https://linux-hardware.org/?probe=2e72dc6560) | Aug 04, 2023 |
| Dell          | 0GTK4K A10                  | Desktop     | [b6586709f2](https://linux-hardware.org/?probe=b6586709f2) | Aug 03, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | Notebook    | [73e1dd94b2](https://linux-hardware.org/?probe=73e1dd94b2) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | Notebook    | [a13fd4044e](https://linux-hardware.org/?probe=a13fd4044e) | Aug 01, 2023 |
| Unknown       | Unknown                     | Other       | [db0911c516](https://linux-hardware.org/?probe=db0911c516) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming FX505DD          | Notebook    | [e965235133](https://linux-hardware.org/?probe=e965235133) | Jul 29, 2023 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [7642eb12d5](https://linux-hardware.org/?probe=7642eb12d5) | Jul 29, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [3afa5a3034](https://linux-hardware.org/?probe=3afa5a3034) | Jul 27, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [6632226064](https://linux-hardware.org/?probe=6632226064) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [24c092f0b0](https://linux-hardware.org/?probe=24c092f0b0) | Jul 26, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [bf88e1114e](https://linux-hardware.org/?probe=bf88e1114e) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [69b707119e](https://linux-hardware.org/?probe=69b707119e) | Jul 25, 2023 |
| Lenovo        | ThinkPad X230 23246V9       | Notebook    | [e7bc7dac48](https://linux-hardware.org/?probe=e7bc7dac48) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c78c35de44](https://linux-hardware.org/?probe=c78c35de44) | Jul 23, 2023 |
| Unknown       | Unknown                     | Other       | [18c7d0154b](https://linux-hardware.org/?probe=18c7d0154b) | Jul 22, 2023 |
| HP            | 2187 A01                    | Desktop     | [efd197811b](https://linux-hardware.org/?probe=efd197811b) | Jul 22, 2023 |
| Fujitsu       | FMVNC4BC4                   | Notebook    | [14249b136a](https://linux-hardware.org/?probe=14249b136a) | Jul 19, 2023 |
| Acer          | Aspire E5-476G              | Notebook    | [74af6477be](https://linux-hardware.org/?probe=74af6477be) | Jul 19, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [3649d91857](https://linux-hardware.org/?probe=3649d91857) | Jul 18, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [462a41184d](https://linux-hardware.org/?probe=462a41184d) | Jul 17, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [4c07b0b74c](https://linux-hardware.org/?probe=4c07b0b74c) | Jul 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [eaaf1d2a5a](https://linux-hardware.org/?probe=eaaf1d2a5a) | Jul 16, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [c1c039384c](https://linux-hardware.org/?probe=c1c039384c) | Jul 11, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [94555c5887](https://linux-hardware.org/?probe=94555c5887) | Jul 10, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [de7dbebf49](https://linux-hardware.org/?probe=de7dbebf49) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | Notebook    | [fe9bfd5f77](https://linux-hardware.org/?probe=fe9bfd5f77) | Jul 10, 2023 |
| Unknown       | Unknown                     | Other       | [a5da218315](https://linux-hardware.org/?probe=a5da218315) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | Notebook    | [d4dadd2e77](https://linux-hardware.org/?probe=d4dadd2e77) | Jul 10, 2023 |
| HP            | ProBook 4420s               | Notebook    | [51e917f03e](https://linux-hardware.org/?probe=51e917f03e) | Jul 09, 2023 |
| Gigabyte      | P55-USB3L                   | Desktop     | [b225c530bd](https://linux-hardware.org/?probe=b225c530bd) | Jul 09, 2023 |
| Acer          | Aspire 4720Z                | Notebook    | [312486a5b7](https://linux-hardware.org/?probe=312486a5b7) | Jul 09, 2023 |
| Lenovo        | Unknown                     | Convertible | [7c4ddbebf7](https://linux-hardware.org/?probe=7c4ddbebf7) | Jul 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [06b52888f8](https://linux-hardware.org/?probe=06b52888f8) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0048149cd5](https://linux-hardware.org/?probe=0048149cd5) | Jul 08, 2023 |
| Unknown       | Unknown                     | Soc         | [e31f4bb359](https://linux-hardware.org/?probe=e31f4bb359) | Jul 08, 2023 |
| Toshiba       | PORTEGE R30-C               | Notebook    | [f07f4d423b](https://linux-hardware.org/?probe=f07f4d423b) | Jul 07, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c5fcc4bcf0](https://linux-hardware.org/?probe=c5fcc4bcf0) | Jul 06, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f05e91be82](https://linux-hardware.org/?probe=f05e91be82) | Jul 06, 2023 |
| Toshiba       | Satellite C640              | Notebook    | [680f3038da](https://linux-hardware.org/?probe=680f3038da) | Jul 06, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [a0183085b8](https://linux-hardware.org/?probe=a0183085b8) | Jul 06, 2023 |
| AZW           | Z85                         | Notebook    | [ca44d0b498](https://linux-hardware.org/?probe=ca44d0b498) | Jul 05, 2023 |
| Acer          | Aspire V5-471G              | Notebook    | [6dd5e93eea](https://linux-hardware.org/?probe=6dd5e93eea) | Jul 05, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [f1ad74f37a](https://linux-hardware.org/?probe=f1ad74f37a) | Jul 05, 2023 |
| Dell          | Latitude E6540              | Notebook    | [17ec85df62](https://linux-hardware.org/?probe=17ec85df62) | Jul 05, 2023 |
| Dell          | Latitude 3410               | Notebook    | [11d9814008](https://linux-hardware.org/?probe=11d9814008) | Jul 02, 2023 |
| HP            | 8061                        | Desktop     | [429534fab2](https://linux-hardware.org/?probe=429534fab2) | Jul 01, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5873d04afe](https://linux-hardware.org/?probe=5873d04afe) | Jun 29, 2023 |
| Microsoft     | Surface Pro 2               | Tablet      | [5b92d42213](https://linux-hardware.org/?probe=5b92d42213) | Jun 29, 2023 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
| Intel         | Unknown                     | Desktop     | [3c85a0c7b9](https://linux-hardware.org/?probe=3c85a0c7b9) | Jun 28, 2023 |
| Intel         | Unknown                     | Desktop     | [dbfbe4b6aa](https://linux-hardware.org/?probe=dbfbe4b6aa) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0c87fda1f9](https://linux-hardware.org/?probe=0c87fda1f9) | Jun 27, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [40cbc38a69](https://linux-hardware.org/?probe=40cbc38a69) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [01a9e10a34](https://linux-hardware.org/?probe=01a9e10a34) | Jun 24, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [0cad0d9955](https://linux-hardware.org/?probe=0cad0d9955) | Jun 22, 2023 |
| Notebook      | P870DM                      | Notebook    | [cd318aa5a4](https://linux-hardware.org/?probe=cd318aa5a4) | Jun 21, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [9bcbbbd906](https://linux-hardware.org/?probe=9bcbbbd906) | Jun 21, 2023 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [d432122ffe](https://linux-hardware.org/?probe=d432122ffe) | Jun 21, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [2d8b92b0e6](https://linux-hardware.org/?probe=2d8b92b0e6) | Jun 20, 2023 |
| Dell          | G7 7588                     | Notebook    | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [6a6cfb05d6](https://linux-hardware.org/?probe=6a6cfb05d6) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [5296ca6ae2](https://linux-hardware.org/?probe=5296ca6ae2) | Jun 19, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [16bbd0f687](https://linux-hardware.org/?probe=16bbd0f687) | Jun 18, 2023 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [b1d6af488d](https://linux-hardware.org/?probe=b1d6af488d) | Jun 18, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d7e9625e19](https://linux-hardware.org/?probe=d7e9625e19) | Jun 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [1050576987](https://linux-hardware.org/?probe=1050576987) | Jun 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [76c1fcc4e5](https://linux-hardware.org/?probe=76c1fcc4e5) | Jun 14, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [3e4b7afb1e](https://linux-hardware.org/?probe=3e4b7afb1e) | Jun 10, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [9a69b50d97](https://linux-hardware.org/?probe=9a69b50d97) | Jun 07, 2023 |
| Infinix       | INBook X1 Pro               | Notebook    | [c558de3b74](https://linux-hardware.org/?probe=c558de3b74) | Jun 05, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [0a82b1aed3](https://linux-hardware.org/?probe=0a82b1aed3) | Jun 05, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [6754a25d1d](https://linux-hardware.org/?probe=6754a25d1d) | Jun 03, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3958079ad5](https://linux-hardware.org/?probe=3958079ad5) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| AXIOO         | Mybook-14E                  | Notebook    | [cb04b551d8](https://linux-hardware.org/?probe=cb04b551d8) | May 31, 2023 |
| ASUSTek       | X456URK                     | Notebook    | [6de2588617](https://linux-hardware.org/?probe=6de2588617) | May 29, 2023 |
| ASUSTek       | X456URK                     | Notebook    | [369aa4fc93](https://linux-hardware.org/?probe=369aa4fc93) | May 29, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| AVITA         | NE14A2                      | Notebook    | [89c5edafbc](https://linux-hardware.org/?probe=89c5edafbc) | May 28, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [db7d7cf31d](https://linux-hardware.org/?probe=db7d7cf31d) | May 26, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [b88a90f9d3](https://linux-hardware.org/?probe=b88a90f9d3) | May 25, 2023 |
| Panasonic     | CFSZ5-2                     | Notebook    | [d5b1455382](https://linux-hardware.org/?probe=d5b1455382) | May 25, 2023 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [e51dec5daf](https://linux-hardware.org/?probe=e51dec5daf) | May 24, 2023 |
| MSI           | 2A9C                        | Desktop     | [acaff65dda](https://linux-hardware.org/?probe=acaff65dda) | May 24, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [e752398b87](https://linux-hardware.org/?probe=e752398b87) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cbda228a9](https://linux-hardware.org/?probe=9cbda228a9) | May 23, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | Notebook    | [cfdb07c9ca](https://linux-hardware.org/?probe=cfdb07c9ca) | May 21, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | Notebook    | [379bcdafa9](https://linux-hardware.org/?probe=379bcdafa9) | May 21, 2023 |
| Sony          | VPCSB35FG                   | Notebook    | [81d2592989](https://linux-hardware.org/?probe=81d2592989) | May 20, 2023 |
| Sony          | VPCSB35FG                   | Notebook    | [828fb24994](https://linux-hardware.org/?probe=828fb24994) | May 20, 2023 |
| MSI           | 2A9C                        | Desktop     | [78d54a3ebf](https://linux-hardware.org/?probe=78d54a3ebf) | May 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [59902928be](https://linux-hardware.org/?probe=59902928be) | May 18, 2023 |
| ASUSTek       | V241EA                      | All in one  | [e4f05ea74b](https://linux-hardware.org/?probe=e4f05ea74b) | May 16, 2023 |
| Acer          | One Z1402                   | Notebook    | [390a684064](https://linux-hardware.org/?probe=390a684064) | May 16, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [6353fe7194](https://linux-hardware.org/?probe=6353fe7194) | May 16, 2023 |
| ASUSTek       | GL502VMK                    | Notebook    | [0b7232826d](https://linux-hardware.org/?probe=0b7232826d) | May 13, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [6d0f055f82](https://linux-hardware.org/?probe=6d0f055f82) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [7f90473be2](https://linux-hardware.org/?probe=7f90473be2) | May 11, 2023 |
| Infinix       | INBook X1                   | Notebook    | [c005323a1a](https://linux-hardware.org/?probe=c005323a1a) | May 11, 2023 |
| Intel         | H61                         | Desktop     | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| HP            | 83EB                        | All in one  | [0abdbdd77b](https://linux-hardware.org/?probe=0abdbdd77b) | May 10, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [036d26ffb3](https://linux-hardware.org/?probe=036d26ffb3) | May 10, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [e8f10d5f7e](https://linux-hardware.org/?probe=e8f10d5f7e) | May 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1b0786ec5e](https://linux-hardware.org/?probe=1b0786ec5e) | May 07, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [5491fd5858](https://linux-hardware.org/?probe=5491fd5858) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [98d7593057](https://linux-hardware.org/?probe=98d7593057) | May 05, 2023 |
| Dell          | Latitude D630               | Notebook    | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [9035ec79cd](https://linux-hardware.org/?probe=9035ec79cd) | May 02, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [f1537beedf](https://linux-hardware.org/?probe=f1537beedf) | May 01, 2023 |
| Acer          | Aspire A514-54G             | Notebook    | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Dell          | Latitude D630               | Notebook    | [a3c3e09675](https://linux-hardware.org/?probe=a3c3e09675) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c1616fcd6c](https://linux-hardware.org/?probe=c1616fcd6c) | Apr 28, 2023 |
| Dell          | Latitude D630               | Notebook    | [850df6e76f](https://linux-hardware.org/?probe=850df6e76f) | Apr 26, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [4591d1bf9d](https://linux-hardware.org/?probe=4591d1bf9d) | Apr 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [ff8440808f](https://linux-hardware.org/?probe=ff8440808f) | Apr 22, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [96fd44e94a](https://linux-hardware.org/?probe=96fd44e94a) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [6cf066b06b](https://linux-hardware.org/?probe=6cf066b06b) | Apr 19, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [40ae403838](https://linux-hardware.org/?probe=40ae403838) | Apr 18, 2023 |
| AXIOO         | SlimBook 11                 | Notebook    | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| Intel         | H61                         | Desktop     | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| Intel         | H61                         | Desktop     | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| Dell          | Latitude 7300               | Notebook    | [1064b58edb](https://linux-hardware.org/?probe=1064b58edb) | Apr 13, 2023 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| MSI           | Creator 15 A11UE            | Notebook    | [ca70d48c0e](https://linux-hardware.org/?probe=ca70d48c0e) | Apr 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [fc811580c9](https://linux-hardware.org/?probe=fc811580c9) | Apr 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [ca58518a03](https://linux-hardware.org/?probe=ca58518a03) | Apr 09, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [dbdef76cc2](https://linux-hardware.org/?probe=dbdef76cc2) | Apr 09, 2023 |
| AZW           | U59                         | Desktop     | [404036be4e](https://linux-hardware.org/?probe=404036be4e) | Apr 09, 2023 |
| HP            | Notebook                    | Notebook    | [584a741058](https://linux-hardware.org/?probe=584a741058) | Apr 08, 2023 |
| ASUSTek       | K46CM                       | Notebook    | [d878fad4d0](https://linux-hardware.org/?probe=d878fad4d0) | Apr 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [fcfcfdbbe7](https://linux-hardware.org/?probe=fcfcfdbbe7) | Apr 06, 2023 |
| Acer          | EG31M R01-C3                | Desktop     | [a548c9e661](https://linux-hardware.org/?probe=a548c9e661) | Apr 05, 2023 |
| Toshiba       | Satellite L640              | Notebook    | [8009d927db](https://linux-hardware.org/?probe=8009d927db) | Apr 05, 2023 |
| Lenovo        | ThinkPad Edge 0578RZ3       | Notebook    | [d37b6fa47b](https://linux-hardware.org/?probe=d37b6fa47b) | Apr 05, 2023 |
| Timi          | TM1703                      | Notebook    | [54b062157f](https://linux-hardware.org/?probe=54b062157f) | Apr 04, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [606eb36d59](https://linux-hardware.org/?probe=606eb36d59) | Apr 04, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c59398619e](https://linux-hardware.org/?probe=c59398619e) | Apr 03, 2023 |
| Gigabyte      | H61M-S2P                    | Desktop     | [6d808d8c4d](https://linux-hardware.org/?probe=6d808d8c4d) | Apr 03, 2023 |
| Dell          | Latitude 3410               | Notebook    | [0b29a27e88](https://linux-hardware.org/?probe=0b29a27e88) | Apr 03, 2023 |
| Dell          | Latitude 3410               | Notebook    | [9c8218ebd6](https://linux-hardware.org/?probe=9c8218ebd6) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [e60610d78a](https://linux-hardware.org/?probe=e60610d78a) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| Acer          | Aspire 4738Z                | Notebook    | [20e13078ef](https://linux-hardware.org/?probe=20e13078ef) | Apr 02, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [a959d79d84](https://linux-hardware.org/?probe=a959d79d84) | Apr 01, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [db53e1a333](https://linux-hardware.org/?probe=db53e1a333) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| Gigabyte      | P41T-D3                     | Desktop     | [2941019778](https://linux-hardware.org/?probe=2941019778) | Mar 29, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [6dac36ba2d](https://linux-hardware.org/?probe=6dac36ba2d) | Mar 28, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [0e8125dc1f](https://linux-hardware.org/?probe=0e8125dc1f) | Mar 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [4ac3cde372](https://linux-hardware.org/?probe=4ac3cde372) | Mar 27, 2023 |
| ASUSTek       | X555BA                      | Notebook    | [f7d51f3c2f](https://linux-hardware.org/?probe=f7d51f3c2f) | Mar 26, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [2c3c5a65a5](https://linux-hardware.org/?probe=2c3c5a65a5) | Mar 24, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [8e9a11831c](https://linux-hardware.org/?probe=8e9a11831c) | Mar 24, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [4b6ecef29b](https://linux-hardware.org/?probe=4b6ecef29b) | Mar 19, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [063ed79c8f](https://linux-hardware.org/?probe=063ed79c8f) | Mar 15, 2023 |
| Toshiba       | PORTEGE Z30t-C              | Notebook    | [7098d7537b](https://linux-hardware.org/?probe=7098d7537b) | Mar 15, 2023 |
| Lenovo        | G400s 20244                 | Notebook    | [fed6bb2c17](https://linux-hardware.org/?probe=fed6bb2c17) | Mar 13, 2023 |
| Dell          | Latitude E5440              | Notebook    | [fe81dc02b0](https://linux-hardware.org/?probe=fe81dc02b0) | Mar 13, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [cda777dad9](https://linux-hardware.org/?probe=cda777dad9) | Mar 13, 2023 |
| AXIOO         | Mybook 14E                  | Notebook    | [1b6c10d1d8](https://linux-hardware.org/?probe=1b6c10d1d8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2AX0... | Notebook    | [d6854dc15a](https://linux-hardware.org/?probe=d6854dc15a) | Mar 12, 2023 |
| GALAX         | B550M                       | Desktop     | [7b8e9c7506](https://linux-hardware.org/?probe=7b8e9c7506) | Mar 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [f4ad14a82a](https://linux-hardware.org/?probe=f4ad14a82a) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| ADVAN         | 1405                        | Notebook    | [7f96f0214f](https://linux-hardware.org/?probe=7f96f0214f) | Mar 08, 2023 |
| Lenovo        | G40-80 80E4                 | Notebook    | [01dae27177](https://linux-hardware.org/?probe=01dae27177) | Mar 07, 2023 |
| Dell          | G7 7588                     | Notebook    | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [2cdcded03e](https://linux-hardware.org/?probe=2cdcded03e) | Mar 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fa94a404fa](https://linux-hardware.org/?probe=fa94a404fa) | Mar 04, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [9857559bb5](https://linux-hardware.org/?probe=9857559bb5) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [096c600c1d](https://linux-hardware.org/?probe=096c600c1d) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [cd8d61c1b6](https://linux-hardware.org/?probe=cd8d61c1b6) | Mar 03, 2023 |
| Google        | Vorticon                    | Notebook    | [7e9f3425ab](https://linux-hardware.org/?probe=7e9f3425ab) | Mar 03, 2023 |
| Google        | Vorticon                    | Notebook    | [aaa620e932](https://linux-hardware.org/?probe=aaa620e932) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| ASUSTek       | E202SA                      | Notebook    | [bccde0c9a5](https://linux-hardware.org/?probe=bccde0c9a5) | Feb 28, 2023 |
| Foxconn       | G31MX Series                | Desktop     | [79ee8e5da3](https://linux-hardware.org/?probe=79ee8e5da3) | Feb 28, 2023 |
| Intel         | H61                         | Desktop     | [b61ef1ed65](https://linux-hardware.org/?probe=b61ef1ed65) | Feb 27, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| MSI           | Z97-G43 GAMING              | Desktop     | [b13f16cb2f](https://linux-hardware.org/?probe=b13f16cb2f) | Feb 26, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [302b65ed41](https://linux-hardware.org/?probe=302b65ed41) | Feb 25, 2023 |
| ASRock        | 970A-G                      | Desktop     | [bfdb227a9d](https://linux-hardware.org/?probe=bfdb227a9d) | Feb 24, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| ASRock        | A88M-G                      | Desktop     | [917526ad4d](https://linux-hardware.org/?probe=917526ad4d) | Feb 24, 2023 |
| Dell          | Inspiron 3476               | Notebook    | [58bff0319e](https://linux-hardware.org/?probe=58bff0319e) | Feb 24, 2023 |
| ASUSTek       | X441UA                      | Notebook    | [cd870fc3d3](https://linux-hardware.org/?probe=cd870fc3d3) | Feb 23, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [e9cfac6aa3](https://linux-hardware.org/?probe=e9cfac6aa3) | Feb 21, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [2953555c08](https://linux-hardware.org/?probe=2953555c08) | Feb 19, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [7197aacb00](https://linux-hardware.org/?probe=7197aacb00) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [b01624da44](https://linux-hardware.org/?probe=b01624da44) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f6e519323b](https://linux-hardware.org/?probe=f6e519323b) | Feb 15, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [ac80c33464](https://linux-hardware.org/?probe=ac80c33464) | Feb 14, 2023 |
| Acer          | Aspire 4732Z                | Notebook    | [abf9d41a29](https://linux-hardware.org/?probe=abf9d41a29) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [a8a5ef19de](https://linux-hardware.org/?probe=a8a5ef19de) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [f41fcff6ff](https://linux-hardware.org/?probe=f41fcff6ff) | Feb 13, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [9fd578a21d](https://linux-hardware.org/?probe=9fd578a21d) | Feb 13, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [608ce76690](https://linux-hardware.org/?probe=608ce76690) | Feb 13, 2023 |
| Toshiba       | Satellite L510              | Notebook    | [706759d61d](https://linux-hardware.org/?probe=706759d61d) | Feb 12, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [89365a25ee](https://linux-hardware.org/?probe=89365a25ee) | Feb 12, 2023 |
| AZW           | U59                         | Desktop     | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [f8f0fb1a21](https://linux-hardware.org/?probe=f8f0fb1a21) | Feb 11, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [6dffda8f11](https://linux-hardware.org/?probe=6dffda8f11) | Feb 10, 2023 |
| Intel         | H61                         | Desktop     | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| Dell          | Studio XPS 1340             | Notebook    | [4c96fdcf99](https://linux-hardware.org/?probe=4c96fdcf99) | Feb 09, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | Notebook    | [86297e5638](https://linux-hardware.org/?probe=86297e5638) | Feb 09, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [99f282862c](https://linux-hardware.org/?probe=99f282862c) | Feb 08, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [06ffbacba3](https://linux-hardware.org/?probe=06ffbacba3) | Feb 08, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [d60cd149fb](https://linux-hardware.org/?probe=d60cd149fb) | Feb 07, 2023 |
| ASUSTek       | P453UA                      | Notebook    | [476ff28577](https://linux-hardware.org/?probe=476ff28577) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [6fcc29607c](https://linux-hardware.org/?probe=6fcc29607c) | Feb 06, 2023 |
| Acer          | Aspire E5-476G              | Notebook    | [3b8e69dd3a](https://linux-hardware.org/?probe=3b8e69dd3a) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [cfc187a64c](https://linux-hardware.org/?probe=cfc187a64c) | Feb 05, 2023 |
| ECS           | H81H3-MV                    | Desktop     | [e60810d8e6](https://linux-hardware.org/?probe=e60810d8e6) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| HP            | 198E                        | Desktop     | [7dedbbef80](https://linux-hardware.org/?probe=7dedbbef80) | Feb 04, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [74bf135ed9](https://linux-hardware.org/?probe=74bf135ed9) | Jan 31, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [e0c723e305](https://linux-hardware.org/?probe=e0c723e305) | Jan 31, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [0c220851f3](https://linux-hardware.org/?probe=0c220851f3) | Jan 30, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [41c052436a](https://linux-hardware.org/?probe=41c052436a) | Jan 30, 2023 |
| MSI           | Modern 14 A10RB             | Notebook    | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [343025f50f](https://linux-hardware.org/?probe=343025f50f) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [dac4a44a62](https://linux-hardware.org/?probe=dac4a44a62) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [3b41afb262](https://linux-hardware.org/?probe=3b41afb262) | Jan 27, 2023 |
| HP            | 14                          | Notebook    | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [b41a540bb4](https://linux-hardware.org/?probe=b41a540bb4) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [acf75dbe88](https://linux-hardware.org/?probe=acf75dbe88) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [16277f992b](https://linux-hardware.org/?probe=16277f992b) | Jan 23, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [1fda4d1e4a](https://linux-hardware.org/?probe=1fda4d1e4a) | Jan 23, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [9cee6edc8e](https://linux-hardware.org/?probe=9cee6edc8e) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | Notebook    | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [855c9b8e45](https://linux-hardware.org/?probe=855c9b8e45) | Jan 18, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [e2486858b9](https://linux-hardware.org/?probe=e2486858b9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
| Lenovo        | 3102 NO DPK                 | Desktop     | [fa7b131a50](https://linux-hardware.org/?probe=fa7b131a50) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| Unknown       | Unknown                     | Phone       | [71abbc8c47](https://linux-hardware.org/?probe=71abbc8c47) | Jan 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7fefb8d34c](https://linux-hardware.org/?probe=7fefb8d34c) | Jan 15, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [58f2d0e1b4](https://linux-hardware.org/?probe=58f2d0e1b4) | Jan 12, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| ASUSTek       | X456URK                     | Notebook    | [09c6b0ed0a](https://linux-hardware.org/?probe=09c6b0ed0a) | Jan 12, 2023 |
| Intel         | Unknown                     | Desktop     | [6928fe7911](https://linux-hardware.org/?probe=6928fe7911) | Jan 11, 2023 |
| Acer          | AO756                       | Notebook    | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [5de089f4c0](https://linux-hardware.org/?probe=5de089f4c0) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [d47b3555d6](https://linux-hardware.org/?probe=d47b3555d6) | Jan 08, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [efaaf759cb](https://linux-hardware.org/?probe=efaaf759cb) | Jan 08, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [8056078760](https://linux-hardware.org/?probe=8056078760) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [b8e1b2ec8e](https://linux-hardware.org/?probe=b8e1b2ec8e) | Jan 07, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [7fa69ddddb](https://linux-hardware.org/?probe=7fa69ddddb) | Jan 07, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [b2dfc2437e](https://linux-hardware.org/?probe=b2dfc2437e) | Jan 06, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fd8b340292](https://linux-hardware.org/?probe=fd8b340292) | Jan 05, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [71c1ae09af](https://linux-hardware.org/?probe=71c1ae09af) | Jan 05, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [bc36d65732](https://linux-hardware.org/?probe=bc36d65732) | Jan 02, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [d99426e3d5](https://linux-hardware.org/?probe=d99426e3d5) | Jan 01, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [7e7df16316](https://linux-hardware.org/?probe=7e7df16316) | Jan 01, 2023 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [56e961b0ca](https://linux-hardware.org/?probe=56e961b0ca) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| Biostar       | TA970                       | Desktop     | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Acer          | TravelMate P214             | Notebook    | [436186d9e5](https://linux-hardware.org/?probe=436186d9e5) | Dec 30, 2022 |
| Lenovo        | ThinkPad X240 20AMS1J60B    | Notebook    | [1d8fcd4a75](https://linux-hardware.org/?probe=1d8fcd4a75) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b6413f9cf2](https://linux-hardware.org/?probe=b6413f9cf2) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [4ddf1fecb8](https://linux-hardware.org/?probe=4ddf1fecb8) | Dec 28, 2022 |
| ASUSTek       | A4110                       | All in one  | [fa417dc5c7](https://linux-hardware.org/?probe=fa417dc5c7) | Dec 28, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [a1e4dd02b2](https://linux-hardware.org/?probe=a1e4dd02b2) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [cedf39754e](https://linux-hardware.org/?probe=cedf39754e) | Dec 27, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [7b4b133211](https://linux-hardware.org/?probe=7b4b133211) | Dec 27, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [68963cb64b](https://linux-hardware.org/?probe=68963cb64b) | Dec 25, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [dd7fd03edd](https://linux-hardware.org/?probe=dd7fd03edd) | Dec 24, 2022 |
| MSI           | H61M-P20                    | Desktop     | [07b5fe983c](https://linux-hardware.org/?probe=07b5fe983c) | Dec 24, 2022 |
| MSI           | H61M-P20                    | Desktop     | [e1d50cc8f4](https://linux-hardware.org/?probe=e1d50cc8f4) | Dec 24, 2022 |
| Khadas        | VIM2                        | Soc         | [2ead7fb94b](https://linux-hardware.org/?probe=2ead7fb94b) | Dec 23, 2022 |
| Dell          | 0JJW8N A03                  | Desktop     | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| Langchao      | NF5110                      | Server      | [3578ca8ceb](https://linux-hardware.org/?probe=3578ca8ceb) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [36d833d9c2](https://linux-hardware.org/?probe=36d833d9c2) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [c065eec185](https://linux-hardware.org/?probe=c065eec185) | Dec 20, 2022 |
| ASUSTek       | X45C                        | Notebook    | [80377ba23f](https://linux-hardware.org/?probe=80377ba23f) | Dec 17, 2022 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [00437ce174](https://linux-hardware.org/?probe=00437ce174) | Dec 16, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [19e6ba206d](https://linux-hardware.org/?probe=19e6ba206d) | Dec 16, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [b9184a9ade](https://linux-hardware.org/?probe=b9184a9ade) | Dec 16, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [d09b578699](https://linux-hardware.org/?probe=d09b578699) | Dec 15, 2022 |
| Acer          | EX-215-52                   | Notebook    | [25201732ef](https://linux-hardware.org/?probe=25201732ef) | Dec 14, 2022 |
| Acer          | EX-215-52                   | Notebook    | [4cb72a8770](https://linux-hardware.org/?probe=4cb72a8770) | Dec 14, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [24fefa1408](https://linux-hardware.org/?probe=24fefa1408) | Dec 13, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [ed087084fb](https://linux-hardware.org/?probe=ed087084fb) | Dec 12, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [1a330e248d](https://linux-hardware.org/?probe=1a330e248d) | Dec 11, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| Dell          | 0VC7DK A03                  | Server      | [5e9bc6749d](https://linux-hardware.org/?probe=5e9bc6749d) | Dec 10, 2022 |
| Dell          | 0VC7DK A03                  | Server      | [f7958003c5](https://linux-hardware.org/?probe=f7958003c5) | Dec 10, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [5ca8db90bb](https://linux-hardware.org/?probe=5ca8db90bb) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5250630bdd](https://linux-hardware.org/?probe=5250630bdd) | Dec 09, 2022 |
| Acer          | Unknown                     | Notebook    | [b4eea49cf7](https://linux-hardware.org/?probe=b4eea49cf7) | Dec 09, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| Lenovo        | ThinkPad L530 24783R8       | Notebook    | [406c066d36](https://linux-hardware.org/?probe=406c066d36) | Dec 08, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [7bde3abe5d](https://linux-hardware.org/?probe=7bde3abe5d) | Dec 08, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [c2d30310e8](https://linux-hardware.org/?probe=c2d30310e8) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [a978cbc03b](https://linux-hardware.org/?probe=a978cbc03b) | Dec 06, 2022 |
| Acer          | One Z1401                   | Notebook    | [835ad73eff](https://linux-hardware.org/?probe=835ad73eff) | Dec 05, 2022 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [1cd6da46f3](https://linux-hardware.org/?probe=1cd6da46f3) | Dec 05, 2022 |
| Toshiba       | dynabook R63/P              | Notebook    | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [897f477f2d](https://linux-hardware.org/?probe=897f477f2d) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [9f512598e2](https://linux-hardware.org/?probe=9f512598e2) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [abe82b0f58](https://linux-hardware.org/?probe=abe82b0f58) | Dec 04, 2022 |
| Dell          | Latitude 3420               | Notebook    | [23e8b890d2](https://linux-hardware.org/?probe=23e8b890d2) | Dec 03, 2022 |
| Intel         | DH55PJ AAE93812-302         | Desktop     | [de105b99e4](https://linux-hardware.org/?probe=de105b99e4) | Dec 03, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [62b19626ce](https://linux-hardware.org/?probe=62b19626ce) | Dec 03, 2022 |
| Langchao      | NF5110                      | Server      | [ae8b7868da](https://linux-hardware.org/?probe=ae8b7868da) | Dec 02, 2022 |
| Lenovo        | B40-70 20392                | Notebook    | [a527c5b6e6](https://linux-hardware.org/?probe=a527c5b6e6) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b52b8b590b](https://linux-hardware.org/?probe=b52b8b590b) | Nov 30, 2022 |
| ASUSTek       | E203NAH                     | Notebook    | [3d091ea214](https://linux-hardware.org/?probe=3d091ea214) | Nov 30, 2022 |
| Dell          | Latitude E6440              | Notebook    | [0c3dd709dd](https://linux-hardware.org/?probe=0c3dd709dd) | Nov 30, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [dc35eb3d09](https://linux-hardware.org/?probe=dc35eb3d09) | Nov 30, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [4a49152177](https://linux-hardware.org/?probe=4a49152177) | Nov 29, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Laptop 14s-dq5xxx           | Notebook    | [9bb72cb3e8](https://linux-hardware.org/?probe=9bb72cb3e8) | Nov 28, 2022 |
| HP            | Laptop 14s-dq5xxx           | Notebook    | [e5164649e1](https://linux-hardware.org/?probe=e5164649e1) | Nov 27, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [74d291cf07](https://linux-hardware.org/?probe=74d291cf07) | Nov 24, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [4f0d293e99](https://linux-hardware.org/?probe=4f0d293e99) | Nov 24, 2022 |
| Dell          | Latitude E6230              | Notebook    | [28b93e0f7c](https://linux-hardware.org/?probe=28b93e0f7c) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | Notebook    | [5f72d40c0e](https://linux-hardware.org/?probe=5f72d40c0e) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | Notebook    | [e6acabebb2](https://linux-hardware.org/?probe=e6acabebb2) | Nov 21, 2022 |
| ASUSTek       | X45C                        | Notebook    | [02a232c4ef](https://linux-hardware.org/?probe=02a232c4ef) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASUSTek       | X455YA                      | Notebook    | [70267d756a](https://linux-hardware.org/?probe=70267d756a) | Nov 21, 2022 |
| Dell          | Latitude E6520              | Notebook    | [855dc4dadd](https://linux-hardware.org/?probe=855dc4dadd) | Nov 20, 2022 |
| MSI           | H510M PRO                   | Desktop     | [182b91241d](https://linux-hardware.org/?probe=182b91241d) | Nov 20, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [4f230635de](https://linux-hardware.org/?probe=4f230635de) | Nov 19, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | Notebook    | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [4c05f821c1](https://linux-hardware.org/?probe=4c05f821c1) | Nov 16, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [c1eca34f9c](https://linux-hardware.org/?probe=c1eca34f9c) | Nov 15, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [f67cd83e31](https://linux-hardware.org/?probe=f67cd83e31) | Nov 14, 2022 |
| Intel         | SandyBridge Platform        | Notebook    | [7019c7ba85](https://linux-hardware.org/?probe=7019c7ba85) | Nov 13, 2022 |
| Acer          | AO722                       | Notebook    | [5c51412f98](https://linux-hardware.org/?probe=5c51412f98) | Nov 12, 2022 |
| MSI           | 2A9C                        | Desktop     | [a531fd4d8e](https://linux-hardware.org/?probe=a531fd4d8e) | Nov 11, 2022 |
| MSI           | 2A9C                        | Desktop     | [599470c2f4](https://linux-hardware.org/?probe=599470c2f4) | Nov 11, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Lenovo        | ThinkPad P52s 20LB0026US    | Notebook    | [9443a4ceda](https://linux-hardware.org/?probe=9443a4ceda) | Nov 08, 2022 |
| Toshiba       | Satellite L15-B             | Notebook    | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| GPD           | G1619-04                    | Notebook    | [0c0542ac2e](https://linux-hardware.org/?probe=0c0542ac2e) | Nov 07, 2022 |
| Lenovo        | 7Y51CTO1WW                  | Server      | [6331807ba3](https://linux-hardware.org/?probe=6331807ba3) | Nov 07, 2022 |
| Unknown       | Unknown                     | Server      | [3facb2e9a7](https://linux-hardware.org/?probe=3facb2e9a7) | Nov 07, 2022 |
| Lenovo        | 7X04CTO1WW                  | Server      | [433a068c09](https://linux-hardware.org/?probe=433a068c09) | Nov 07, 2022 |
| Lenovo        | 7X08CTO1WW                  | Server      | [a3236bc9e8](https://linux-hardware.org/?probe=a3236bc9e8) | Nov 07, 2022 |
| Lenovo        | 7X04CTO1WW                  | Server      | [fab16fdb8d](https://linux-hardware.org/?probe=fab16fdb8d) | Nov 07, 2022 |
| Lenovo        | 7Y51CTO1WW                  | Server      | [ce01f7d898](https://linux-hardware.org/?probe=ce01f7d898) | Nov 07, 2022 |
| Lenovo        | 7X04CTO1WW                  | Server      | [8b79ae4568](https://linux-hardware.org/?probe=8b79ae4568) | Nov 07, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [c2e7afc800](https://linux-hardware.org/?probe=c2e7afc800) | Nov 07, 2022 |
| Intel         | P61A-D3                     | Desktop     | [5561c81cf4](https://linux-hardware.org/?probe=5561c81cf4) | Nov 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [98e419a04d](https://linux-hardware.org/?probe=98e419a04d) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Intel         | SandyBridge Platform        | Notebook    | [88c15d34e4](https://linux-hardware.org/?probe=88c15d34e4) | Nov 03, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [391048b46f](https://linux-hardware.org/?probe=391048b46f) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [49d6eb853f](https://linux-hardware.org/?probe=49d6eb853f) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [5de7efb403](https://linux-hardware.org/?probe=5de7efb403) | Nov 01, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [142e1c0695](https://linux-hardware.org/?probe=142e1c0695) | Oct 31, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [87f4a137dc](https://linux-hardware.org/?probe=87f4a137dc) | Oct 31, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| AXIOO         | Mybook 14H                  | Notebook    | [f8a7c19640](https://linux-hardware.org/?probe=f8a7c19640) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [0084d271e4](https://linux-hardware.org/?probe=0084d271e4) | Oct 28, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6d5c1da4b7](https://linux-hardware.org/?probe=6d5c1da4b7) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3b87b259c8](https://linux-hardware.org/?probe=3b87b259c8) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [e438393dca](https://linux-hardware.org/?probe=e438393dca) | Oct 19, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7891f1e18c](https://linux-hardware.org/?probe=7891f1e18c) | Oct 18, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| Lenovo        | IdeaPadFlex 3 11IGL05 82... | Convertible | [6e32a194d3](https://linux-hardware.org/?probe=6e32a194d3) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Dell          | Latitude 3490               | Notebook    | [a739a29b72](https://linux-hardware.org/?probe=a739a29b72) | Oct 16, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [babb66e9c9](https://linux-hardware.org/?probe=babb66e9c9) | Oct 16, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Intel         | SandyBridge Platform        | Notebook    | [3cc3d23297](https://linux-hardware.org/?probe=3cc3d23297) | Oct 14, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [814a533c23](https://linux-hardware.org/?probe=814a533c23) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46bc0c74c6](https://linux-hardware.org/?probe=46bc0c74c6) | Oct 11, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [a6eb228e33](https://linux-hardware.org/?probe=a6eb228e33) | Oct 10, 2022 |
| AXIOO         | Slimbook 13                 | Notebook    | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Acer          | Aspire 4736                 | Notebook    | [48b8af7bcf](https://linux-hardware.org/?probe=48b8af7bcf) | Oct 04, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [ce8e31b40d](https://linux-hardware.org/?probe=ce8e31b40d) | Oct 02, 2022 |
| HP            | Compaq 420                  | Notebook    | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [25e087916a](https://linux-hardware.org/?probe=25e087916a) | Oct 01, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [6f6704ea90](https://linux-hardware.org/?probe=6f6704ea90) | Oct 01, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [5e9a9b60e6](https://linux-hardware.org/?probe=5e9a9b60e6) | Oct 01, 2022 |
| ASUSTek       | X450EA                      | Notebook    | [345600d392](https://linux-hardware.org/?probe=345600d392) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [af7b986ff8](https://linux-hardware.org/?probe=af7b986ff8) | Sep 28, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [4a285e2052](https://linux-hardware.org/?probe=4a285e2052) | Sep 27, 2022 |
| Dell          | Latitude E6540              | Notebook    | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [3414420bc7](https://linux-hardware.org/?probe=3414420bc7) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | Notebook    | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | Notebook    | [ab84311fcc](https://linux-hardware.org/?probe=ab84311fcc) | Sep 24, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | Notebook    | [48a40a2f04](https://linux-hardware.org/?probe=48a40a2f04) | Sep 24, 2022 |
| HP            | 198E                        | Desktop     | [ffa9a79cc0](https://linux-hardware.org/?probe=ffa9a79cc0) | Sep 24, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [31b11c4544](https://linux-hardware.org/?probe=31b11c4544) | Sep 24, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [b879e569d1](https://linux-hardware.org/?probe=b879e569d1) | Sep 24, 2022 |
| ASUSTek       | X450EA                      | Notebook    | [79d9dab7dc](https://linux-hardware.org/?probe=79d9dab7dc) | Sep 24, 2022 |
| HP            | Pavilion 14                 | Notebook    | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [c658e4f48c](https://linux-hardware.org/?probe=c658e4f48c) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | Notebook    | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [64ff44a074](https://linux-hardware.org/?probe=64ff44a074) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [f24f78c803](https://linux-hardware.org/?probe=f24f78c803) | Sep 19, 2022 |
| ECS           | A55F2-M4                    | Desktop     | [335d28e72c](https://linux-hardware.org/?probe=335d28e72c) | Sep 19, 2022 |
| ASUSTek       | ET2013I                     | All in one  | [fddeb02707](https://linux-hardware.org/?probe=fddeb02707) | Sep 18, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [0c383a03ad](https://linux-hardware.org/?probe=0c383a03ad) | Sep 17, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0S10... | Notebook    | [0fd5868b54](https://linux-hardware.org/?probe=0fd5868b54) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| Lenovo        | ZHAOYANG E47                | Notebook    | [7f1fab5ff0](https://linux-hardware.org/?probe=7f1fab5ff0) | Sep 11, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [bfa4cc7ddc](https://linux-hardware.org/?probe=bfa4cc7ddc) | Sep 10, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [e1b3cac9d8](https://linux-hardware.org/?probe=e1b3cac9d8) | Sep 07, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [983d14d741](https://linux-hardware.org/?probe=983d14d741) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [c073d9fb9f](https://linux-hardware.org/?probe=c073d9fb9f) | Sep 03, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | Notebook    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| Acer          | Aspire V5-431               | Notebook    | [5ac694007d](https://linux-hardware.org/?probe=5ac694007d) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | ThinkPad L512 259756M       | Notebook    | [3990fcfeed](https://linux-hardware.org/?probe=3990fcfeed) | Aug 30, 2022 |
| Infinix       | INBOOK X2                   | Notebook    | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [75a6e1e9a1](https://linux-hardware.org/?probe=75a6e1e9a1) | Aug 29, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [8fac02d016](https://linux-hardware.org/?probe=8fac02d016) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [d281087322](https://linux-hardware.org/?probe=d281087322) | Aug 28, 2022 |
| Dell          | Latitude 7280               | Notebook    | [d214e30b1e](https://linux-hardware.org/?probe=d214e30b1e) | Aug 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| Intel         | H61                         | Desktop     | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | Notebook    | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | One Z1402                   | Notebook    | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [9ac20fda5a](https://linux-hardware.org/?probe=9ac20fda5a) | Aug 16, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [0b95f78b15](https://linux-hardware.org/?probe=0b95f78b15) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [903fda443e](https://linux-hardware.org/?probe=903fda443e) | Aug 14, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [a7d615e104](https://linux-hardware.org/?probe=a7d615e104) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| HP            | 14                          | Notebook    | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| ASUSTek       | K43E                        | Notebook    | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [7dbc1a26ca](https://linux-hardware.org/?probe=7dbc1a26ca) | Aug 07, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6dbb0a4eb9](https://linux-hardware.org/?probe=6dbb0a4eb9) | Aug 06, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [4de0aa7ccf](https://linux-hardware.org/?probe=4de0aa7ccf) | Aug 05, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [1c95e4f03d](https://linux-hardware.org/?probe=1c95e4f03d) | Aug 04, 2022 |
| ASUSTek       | K43E                        | Notebook    | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [9c842ec71c](https://linux-hardware.org/?probe=9c842ec71c) | Aug 03, 2022 |
| HP            | 431                         | Notebook    | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | Notebook    | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Lenovo        | ThinkPad X230 23245NJ       | Notebook    | [3c85e43b86](https://linux-hardware.org/?probe=3c85e43b86) | Aug 01, 2022 |
| HP            | 240 G8 Notebook PC          | Notebook    | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| Acer          | Z476                        | Notebook    | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| Dell          | Latitude E7250              | Notebook    | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| Sony          | VPCEA36FG                   | Notebook    | [6c742b6234](https://linux-hardware.org/?probe=6c742b6234) | Jul 30, 2022 |
| ASUSTek       | K43E                        | Notebook    | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| ASUSTek       | X455LF                      | Notebook    | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [3d23b4bbdc](https://linux-hardware.org/?probe=3d23b4bbdc) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [527b25a7f3](https://linux-hardware.org/?probe=527b25a7f3) | Jul 25, 2022 |
| Dell          | G3 3579                     | Notebook    | [96fab186c3](https://linux-hardware.org/?probe=96fab186c3) | Jul 24, 2022 |
| MSI           | 2A9C                        | Desktop     | [b0441c833d](https://linux-hardware.org/?probe=b0441c833d) | Jul 24, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | Notebook    | [a6e3ee128e](https://linux-hardware.org/?probe=a6e3ee128e) | Jul 20, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [1f7429b29d](https://linux-hardware.org/?probe=1f7429b29d) | Jul 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [54c99c7f2f](https://linux-hardware.org/?probe=54c99c7f2f) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [cf41c08ea5](https://linux-hardware.org/?probe=cf41c08ea5) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d651eb1f7d](https://linux-hardware.org/?probe=d651eb1f7d) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [b04b2741a0](https://linux-hardware.org/?probe=b04b2741a0) | Jul 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b00361cdbd](https://linux-hardware.org/?probe=b00361cdbd) | Jul 13, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [cde5f69fef](https://linux-hardware.org/?probe=cde5f69fef) | Jul 13, 2022 |
| Dell          | 0WCWFJ A00                  | All in one  | [89a6f4711c](https://linux-hardware.org/?probe=89a6f4711c) | Jul 11, 2022 |
| HP            | Pavilion g4                 | Notebook    | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Dell          | Latitude E6440              | Notebook    | [495237a0b0](https://linux-hardware.org/?probe=495237a0b0) | Jul 09, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [80e2fc79da](https://linux-hardware.org/?probe=80e2fc79da) | Jul 07, 2022 |
| Toshiba       | Satellite C640              | Notebook    | [cd8f69d739](https://linux-hardware.org/?probe=cd8f69d739) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Lenovo        | ThinkPad L412 0585E86       | Notebook    | [ad82717c98](https://linux-hardware.org/?probe=ad82717c98) | Jul 01, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [97d88d7e00](https://linux-hardware.org/?probe=97d88d7e00) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [3cec3cffbb](https://linux-hardware.org/?probe=3cec3cffbb) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [bac4b49e55](https://linux-hardware.org/?probe=bac4b49e55) | Jun 30, 2022 |
| Biostar       | A68N-5600E                  | Desktop     | [d5cfa78343](https://linux-hardware.org/?probe=d5cfa78343) | Jun 29, 2022 |
| Acer          | Aspire A314-35              | Notebook    | [dfdd48254c](https://linux-hardware.org/?probe=dfdd48254c) | Jun 29, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| HP            | Pavilion g4                 | Notebook    | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [30692c3fdb](https://linux-hardware.org/?probe=30692c3fdb) | Jun 23, 2022 |
| Fujitsu       | FMVS02003                   | Notebook    | [3536a9951f](https://linux-hardware.org/?probe=3536a9951f) | Jun 23, 2022 |
| Dell          | Precision M4500             | Notebook    | [e41b9f3386](https://linux-hardware.org/?probe=e41b9f3386) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [00a254b4ff](https://linux-hardware.org/?probe=00a254b4ff) | Jun 21, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [4ca3721cbb](https://linux-hardware.org/?probe=4ca3721cbb) | Jun 20, 2022 |
| MSI           | 2A9C                        | Desktop     | [73dd2172d3](https://linux-hardware.org/?probe=73dd2172d3) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [4d5fb8a789](https://linux-hardware.org/?probe=4d5fb8a789) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [9f7b97f22f](https://linux-hardware.org/?probe=9f7b97f22f) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| AXIOO         | Mybook 14E                  | Notebook    | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [b71d801e61](https://linux-hardware.org/?probe=b71d801e61) | Jun 18, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [a6cc4351be](https://linux-hardware.org/?probe=a6cc4351be) | Jun 17, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [fe4f649d9b](https://linux-hardware.org/?probe=fe4f649d9b) | Jun 17, 2022 |
| Wearnes       | T1550-A1                    | Desktop     | [b131cd7e0d](https://linux-hardware.org/?probe=b131cd7e0d) | Jun 16, 2022 |
| Wearnes       | T1550-A1                    | Desktop     | [002ebf8c70](https://linux-hardware.org/?probe=002ebf8c70) | Jun 15, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| HP            | 2B43                        | Desktop     | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| Acer          | AO756                       | Notebook    | [008fa33f13](https://linux-hardware.org/?probe=008fa33f13) | Jun 09, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [a74cd897c5](https://linux-hardware.org/?probe=a74cd897c5) | Jun 09, 2022 |
| MSI           | Prestige 14 A11SC           | Notebook    | [ea39fa65a1](https://linux-hardware.org/?probe=ea39fa65a1) | Jun 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [bdb3bbe37f](https://linux-hardware.org/?probe=bdb3bbe37f) | Jun 07, 2022 |
| Lenovo        | Z41-70 80K5                 | Notebook    | [3419d2fd18](https://linux-hardware.org/?probe=3419d2fd18) | Jun 06, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5e4d9a126e](https://linux-hardware.org/?probe=5e4d9a126e) | Jun 05, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| MSI           | H81I                        | Desktop     | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [1019de0d68](https://linux-hardware.org/?probe=1019de0d68) | Jun 01, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [2652284f1a](https://linux-hardware.org/?probe=2652284f1a) | May 31, 2022 |
| ASRock        | A88M-G                      | Desktop     | [9b82b09acc](https://linux-hardware.org/?probe=9b82b09acc) | May 30, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [a1dd5003f5](https://linux-hardware.org/?probe=a1dd5003f5) | May 30, 2022 |
| AXIOO         | NEON HNM MODEL              | Notebook    | [0fbd1cf4af](https://linux-hardware.org/?probe=0fbd1cf4af) | May 30, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| Lenovo        | G400 20235                  | Notebook    | [351b94ec15](https://linux-hardware.org/?probe=351b94ec15) | May 25, 2022 |
| HP            | 1000                        | Notebook    | [e83bc1e8fe](https://linux-hardware.org/?probe=e83bc1e8fe) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Biostar       | GF8200C M2+                 | Desktop     | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| ASUSTek       | K43U                        | Notebook    | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| MSI           | Modern 14 B11MO             | Notebook    | [c3b01c8c1b](https://linux-hardware.org/?probe=c3b01c8c1b) | May 20, 2022 |
| ASRock        | A88M-G                      | Desktop     | [e2baae7114](https://linux-hardware.org/?probe=e2baae7114) | May 19, 2022 |
| ASUSTek       | K43U                        | Notebook    | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [a1b9d7e608](https://linux-hardware.org/?probe=a1b9d7e608) | May 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [843a31b222](https://linux-hardware.org/?probe=843a31b222) | May 17, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [cfba770336](https://linux-hardware.org/?probe=cfba770336) | May 17, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [c19acfde6f](https://linux-hardware.org/?probe=c19acfde6f) | May 17, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [2ee65efb9e](https://linux-hardware.org/?probe=2ee65efb9e) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [e633129a51](https://linux-hardware.org/?probe=e633129a51) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [b207ce7566](https://linux-hardware.org/?probe=b207ce7566) | May 12, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [98b0999339](https://linux-hardware.org/?probe=98b0999339) | May 12, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [c4e0e740bb](https://linux-hardware.org/?probe=c4e0e740bb) | May 12, 2022 |
| Acer          | V1.24                       | Notebook    | [186531d4d8](https://linux-hardware.org/?probe=186531d4d8) | May 11, 2022 |
| Sony          | SVS13137PGB                 | Notebook    | [6dd2b49c52](https://linux-hardware.org/?probe=6dd2b49c52) | May 10, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [19345cd924](https://linux-hardware.org/?probe=19345cd924) | May 10, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [108b57a5a7](https://linux-hardware.org/?probe=108b57a5a7) | May 10, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [ec1fa8e360](https://linux-hardware.org/?probe=ec1fa8e360) | May 08, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [56cecf6472](https://linux-hardware.org/?probe=56cecf6472) | May 07, 2022 |
| MSI           | H55M-P33                    | Desktop     | [0f6b0dc134](https://linux-hardware.org/?probe=0f6b0dc134) | May 07, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [b4b52aad69](https://linux-hardware.org/?probe=b4b52aad69) | May 07, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [c0bfa1dddf](https://linux-hardware.org/?probe=c0bfa1dddf) | May 06, 2022 |
| Acer          | Aspire V5-431               | Notebook    | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [4dcc86a60e](https://linux-hardware.org/?probe=4dcc86a60e) | May 03, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [04dee023e6](https://linux-hardware.org/?probe=04dee023e6) | May 01, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [db2efb40d4](https://linux-hardware.org/?probe=db2efb40d4) | May 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [f93f8fcb35](https://linux-hardware.org/?probe=f93f8fcb35) | Apr 28, 2022 |
| Dell          | Latitude E6510              | Notebook    | [10d60e00c2](https://linux-hardware.org/?probe=10d60e00c2) | Apr 27, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [9f98b410f6](https://linux-hardware.org/?probe=9f98b410f6) | Apr 26, 2022 |
| Gigabyte      | M912                        | Notebook    | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | X450LCP                     | Notebook    | [a2ed4903be](https://linux-hardware.org/?probe=a2ed4903be) | Apr 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c90694a42c](https://linux-hardware.org/?probe=c90694a42c) | Apr 23, 2022 |
| Gigabyte      | AERO 15XV8                  | Notebook    | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [345734b3fd](https://linux-hardware.org/?probe=345734b3fd) | Apr 07, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [eb44050489](https://linux-hardware.org/?probe=eb44050489) | Apr 07, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| ASUSTek       | X455YA                      | Notebook    | [cf17e2bba2](https://linux-hardware.org/?probe=cf17e2bba2) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [ca7ee75e52](https://linux-hardware.org/?probe=ca7ee75e52) | Apr 01, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [c3651e4d3d](https://linux-hardware.org/?probe=c3651e4d3d) | Apr 01, 2022 |
| Dell          | Latitude E6230              | Notebook    | [c45161f6f3](https://linux-hardware.org/?probe=c45161f6f3) | Mar 31, 2022 |
| HP            | 3641h                       | Desktop     | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [84625838c2](https://linux-hardware.org/?probe=84625838c2) | Mar 30, 2022 |
| Lenovo        | 36F2 SDK0Q55754 WIN 3273... | All in one  | [64bc773e5b](https://linux-hardware.org/?probe=64bc773e5b) | Mar 30, 2022 |
| HP            | Pavilion 14                 | Notebook    | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Infinix       | INBook X1                   | Notebook    | [a06d137316](https://linux-hardware.org/?probe=a06d137316) | Mar 28, 2022 |
| Koloe         | X58                         | Desktop     | [8025987817](https://linux-hardware.org/?probe=8025987817) | Mar 27, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [46acaeb2db](https://linux-hardware.org/?probe=46acaeb2db) | Mar 27, 2022 |
| Dell          | Latitude E7240              | Notebook    | [02c34ca310](https://linux-hardware.org/?probe=02c34ca310) | Mar 25, 2022 |
| ASUSTek       | X455YA                      | Notebook    | [b0469d5342](https://linux-hardware.org/?probe=b0469d5342) | Mar 25, 2022 |
| Colorful T... | C.H110M-K D3 PLUS V20       | Desktop     | [191dfebc88](https://linux-hardware.org/?probe=191dfebc88) | Mar 23, 2022 |
| Sony          | VPCSB35FG                   | Notebook    | [79d0465072](https://linux-hardware.org/?probe=79d0465072) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [1b7f98b34d](https://linux-hardware.org/?probe=1b7f98b34d) | Mar 23, 2022 |
| ASUSTek       | X456UQK                     | Notebook    | [863693cc0a](https://linux-hardware.org/?probe=863693cc0a) | Mar 23, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [f0047d02ea](https://linux-hardware.org/?probe=f0047d02ea) | Mar 22, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [dd7543bdb3](https://linux-hardware.org/?probe=dd7543bdb3) | Mar 21, 2022 |
| Dell          | Inspiron 13-5368            | Notebook    | [d98411620e](https://linux-hardware.org/?probe=d98411620e) | Mar 21, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [08985cbe9e](https://linux-hardware.org/?probe=08985cbe9e) | Mar 21, 2022 |
| Intel         | H55                         | Desktop     | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [991793e09e](https://linux-hardware.org/?probe=991793e09e) | Mar 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [222cbe9b4e](https://linux-hardware.org/?probe=222cbe9b4e) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [b7cf53ebcc](https://linux-hardware.org/?probe=b7cf53ebcc) | Mar 15, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | Notebook                    | Notebook    | [6ae78b432d](https://linux-hardware.org/?probe=6ae78b432d) | Mar 12, 2022 |
| ZYREX COMP... | TACTICAL                    | Desktop     | [73a4735670](https://linux-hardware.org/?probe=73a4735670) | Mar 12, 2022 |
| Dell          | Latitude E7240              | Notebook    | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e39d0d9111](https://linux-hardware.org/?probe=e39d0d9111) | Mar 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [5e43e1dd7b](https://linux-hardware.org/?probe=5e43e1dd7b) | Mar 11, 2022 |
| Biostar       | N68S3B                      | Desktop     | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [ed4db5233e](https://linux-hardware.org/?probe=ed4db5233e) | Mar 10, 2022 |
| ASUSTek       | X450EA                      | Notebook    | [a7394d72a0](https://linux-hardware.org/?probe=a7394d72a0) | Mar 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [2f6380807c](https://linux-hardware.org/?probe=2f6380807c) | Mar 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [4702507c0f](https://linux-hardware.org/?probe=4702507c0f) | Mar 09, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Indonesia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 167       | 10.92%  |
| Ubuntu 18.04                 | 105       | 6.86%   |
| Ubuntu 22.04                 | 86        | 5.62%   |
| OpenMandriva 4.3             | 61        | 3.99%   |
| Arch Rolling                 | 38        | 2.48%   |
| OpenMandriva 4.2             | 32        | 2.09%   |
| Pop!_OS 22.04                | 30        | 1.96%   |
| KDE neon 20.04               | 26        | 1.7%    |
| Fedora 38                    | 24        | 1.57%   |
| Zorin 15                     | 23        | 1.5%    |
| ArcoLinux Rolling            | 23        | 1.5%    |
| Arch                         | 22        | 1.44%   |
| Fedora 36                    | 21        | 1.37%   |
| Zorin 16                     | 19        | 1.24%   |
| Manjaro                      | 19        | 1.24%   |
| Elementary 6.1               | 19        | 1.24%   |
| Pop!_OS 20.04                | 18        | 1.18%   |
| OpenMandriva 23.03           | 17        | 1.11%   |
| Debian 11                    | 17        | 1.11%   |
| Ubuntu 21.10                 | 16        | 1.05%   |
| Linux Mint 21.1              | 16        | 1.05%   |
| Linux Mint 20.3              | 16        | 1.05%   |
| Fedora 35                    | 16        | 1.05%   |
| Ubuntu 19.10                 | 15        | 0.98%   |
| OpenMandriva 23.08           | 15        | 0.98%   |
| Fedora 37                    | 15        | 0.98%   |
| OpenMandriva 23.01           | 14        | 0.92%   |
| Linux Mint 19.3              | 14        | 0.92%   |
| Debian 12                    | 14        | 0.92%   |
| Xubuntu 20.04                | 13        | 0.85%   |
| Linux Mint 20                | 12        | 0.78%   |
| EndeavourOS Rolling          | 12        | 0.78%   |
| Kubuntu 22.04                | 11        | 0.72%   |
| Debian 10                    | 11        | 0.72%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.65%   |
| KDE neon 22.04               | 10        | 0.65%   |
| Fedora 32                    | 10        | 0.65%   |
| Ubuntu 23.04                 | 9         | 0.59%   |
| Ubuntu 21.04                 | 9         | 0.59%   |
| Ubuntu 16.04                 | 9         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 423       | 29.05%  |
| OpenMandriva  | 154       | 10.58%  |
| Fedora        | 99        | 6.8%    |
| Linux Mint    | 89        | 6.11%   |
| Pop!_OS       | 63        | 4.33%   |
| Arch          | 60        | 4.12%   |
| Zorin         | 51        | 3.5%    |
| Manjaro       | 51        | 3.5%    |
| Debian        | 46        | 3.16%   |
| Elementary    | 40        | 2.75%   |
| KDE neon      | 36        | 2.47%   |
| Endless       | 34        | 2.34%   |
| Kali          | 32        | 2.2%    |
| Kubuntu       | 31        | 2.13%   |
| Xubuntu       | 27        | 1.85%   |
| ArcoLinux     | 24        | 1.65%   |
| Lubuntu       | 20        | 1.37%   |
| ROSA          | 15        | 1.03%   |
| openSUSE      | 13        | 0.89%   |
| EndeavourOS   | 12        | 0.82%   |
| Ubuntu MATE   | 11        | 0.76%   |
| Ubuntu Unity  | 9         | 0.62%   |
| Nobara        | 8         | 0.55%   |
| LMDE          | 8         | 0.55%   |
| Clear Linux   | 8         | 0.55%   |
| Parrot        | 7         | 0.48%   |
| MX            | 7         | 0.48%   |
| Gentoo        | 6         | 0.41%   |
| SteamOS       | 5         | 0.34%   |
| Deepin        | 5         | 0.34%   |
| CentOS        | 5         | 0.34%   |
| Android       | 5         | 0.34%   |
| Ubuntu Budgie | 4         | 0.27%   |
| Rocky Linux   | 4         | 0.27%   |
| Artix         | 4         | 0.27%   |
| Xero          | 3         | 0.21%   |
| Sparky        | 3         | 0.21%   |
| Solus         | 3         | 0.21%   |
| Garuda Linux  | 3         | 0.21%   |
| UbuntuDDE     | 2         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 60        | 3.66%   |
| 5.10.14-desktop-1omv4002 | 29        | 1.77%   |
| 5.4.0-42-generic         | 28        | 1.71%   |
| 5.15.0-56-generic        | 22        | 1.34%   |
| 5.4.0-26-generic         | 18        | 1.1%    |
| 6.2.6-desktop-1omv2390   | 16        | 0.98%   |
| 5.4.0-52-generic         | 16        | 0.98%   |
| 5.4.0-58-generic         | 15        | 0.91%   |
| 6.4.11-desktop-1omv2390  | 13        | 0.79%   |
| 6.1.1-desktop-1omv2290   | 12        | 0.73%   |
| 4.18.0-15-generic        | 12        | 0.73%   |
| 5.15.0-41-generic        | 11        | 0.67%   |
| 5.0.0-25-generic         | 11        | 0.67%   |
| 5.15.0-48-generic        | 10        | 0.61%   |
| 5.15.0-46-generic        | 10        | 0.61%   |
| 5.15.0-43-generic        | 10        | 0.61%   |
| 5.4.0-80-generic         | 9         | 0.55%   |
| 5.15.0-47-generic        | 9         | 0.55%   |
| 5.11.0-37-generic        | 9         | 0.55%   |
| 5.4.0-54-generic         | 8         | 0.49%   |
| 5.3.0-46-generic         | 8         | 0.49%   |
| 5.3.0-40-generic         | 8         | 0.49%   |
| 5.19.0-46-generic        | 8         | 0.49%   |
| 5.15.0-58-generic        | 8         | 0.49%   |
| 6.6.2-desktop-1omv2390   | 7         | 0.43%   |
| 6.2.0-26-generic         | 7         | 0.43%   |
| 5.8.0-48-generic         | 7         | 0.43%   |
| 5.8.0-14-generic         | 7         | 0.43%   |
| 5.19.0-35-generic        | 7         | 0.43%   |
| 5.15.0-52-generic        | 7         | 0.43%   |
| 5.11.0-43-generic        | 7         | 0.43%   |
| 5.11.0-40-generic        | 7         | 0.43%   |
| 5.11.0-27-generic        | 7         | 0.43%   |
| 6.5.5-desktop-1omv2390   | 6         | 0.37%   |
| 6.2.0-39-generic         | 6         | 0.37%   |
| 5.4.0-33-generic         | 6         | 0.37%   |
| 5.15.0-91-generic        | 6         | 0.37%   |
| 5.11.0-7620-generic      | 6         | 0.37%   |
| 5.11.0-38-generic        | 6         | 0.37%   |
| 5.11.0-35-generic        | 6         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 210       | 13.25%  |
| 5.15.0  | 149       | 9.4%    |
| 5.11.0  | 74        | 4.67%   |
| 5.16.7  | 62        | 3.91%   |
| 5.8.0   | 61        | 3.85%   |
| 4.15.0  | 56        | 3.53%   |
| 5.13.0  | 53        | 3.34%   |
| 5.3.0   | 51        | 3.22%   |
| 5.0.0   | 44        | 2.78%   |
| 6.2.0   | 40        | 2.52%   |
| 5.19.0  | 36        | 2.27%   |
| 5.10.0  | 33        | 2.08%   |
| 4.18.0  | 32        | 2.02%   |
| 5.10.14 | 30        | 1.89%   |
| 6.1.0   | 26        | 1.64%   |
| 6.2.6   | 20        | 1.26%   |
| 6.1.1   | 18        | 1.14%   |
| 6.5.0   | 17        | 1.07%   |
| 6.4.11  | 16        | 1.01%   |
| 6.5.5   | 15        | 0.95%   |
| 4.19.0  | 15        | 0.95%   |
| 5.14.0  | 10        | 0.63%   |
| 5.17.5  | 8         | 0.5%    |
| 6.6.2   | 7         | 0.44%   |
| 6.4.6   | 7         | 0.44%   |
| 4.4.0   | 7         | 0.44%   |
| 6.6.8   | 6         | 0.38%   |
| 6.5.3   | 6         | 0.38%   |
| 5.16.0  | 6         | 0.38%   |
| 6.6.9   | 5         | 0.32%   |
| 6.5.6   | 5         | 0.32%   |
| 6.3.5   | 5         | 0.32%   |
| 5.9.16  | 5         | 0.32%   |
| 5.16.12 | 5         | 0.32%   |
| 6.4.8   | 4         | 0.25%   |
| 6.3.8   | 4         | 0.25%   |
| 6.2.9   | 4         | 0.25%   |
| 6.2.8   | 4         | 0.25%   |
| 6.0.9   | 4         | 0.25%   |
| 6.0.6   | 4         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 220       | 14.11%  |
| 5.15    | 177       | 11.35%  |
| 5.10    | 101       | 6.48%   |
| 5.16    | 84        | 5.39%   |
| 5.11    | 83        | 5.32%   |
| 6.2     | 77        | 4.94%   |
| 5.8     | 76        | 4.87%   |
| 6.1     | 71        | 4.55%   |
| 5.13    | 61        | 3.91%   |
| 4.15    | 56        | 3.59%   |
| 5.3     | 55        | 3.53%   |
| 6.5     | 52        | 3.34%   |
| 5.19    | 51        | 3.27%   |
| 5.0     | 46        | 2.95%   |
| 6.4     | 45        | 2.89%   |
| 4.18    | 35        | 2.25%   |
| 6.0     | 31        | 1.99%   |
| 6.6     | 30        | 1.92%   |
| 5.14    | 26        | 1.67%   |
| 6.3     | 24        | 1.54%   |
| 5.17    | 22        | 1.41%   |
| 4.19    | 20        | 1.28%   |
| 5.18    | 19        | 1.22%   |
| 5.9     | 16        | 1.03%   |
| 5.12    | 12        | 0.77%   |
| 4.9     | 12        | 0.77%   |
| 5.7     | 10        | 0.64%   |
| 5.6     | 10        | 0.64%   |
| 4.4     | 9         | 0.58%   |
| 5.5     | 6         | 0.38%   |
| 5.2     | 3         | 0.19%   |
| 4.13    | 3         | 0.19%   |
| 4.14    | 2         | 0.13%   |
| 4.10    | 2         | 0.13%   |
| 4.1     | 2         | 0.13%   |
| 3.10    | 2         | 0.13%   |
| 6.7     | 1         | 0.06%   |
| 6       | 1         | 0.06%   |
| 5.1     | 1         | 0.06%   |
| 5       | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1364      | 96.94%  |
| i686    | 31        | 2.2%    |
| aarch64 | 6         | 0.43%   |
| armv8l  | 3         | 0.21%   |
| armv7l  | 3         | 0.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 611       | 41.85%  |
| KDE5              | 291       | 19.93%  |
| Unknown           | 151       | 10.34%  |
| XFCE              | 114       | 7.81%   |
| X-Cinnamon        | 80        | 5.48%   |
| Pantheon          | 38        | 2.6%    |
| MATE              | 31        | 2.12%   |
| LXQt              | 24        | 1.64%   |
| KDE               | 22        | 1.51%   |
| Cinnamon          | 16        | 1.1%    |
| Budgie            | 10        | 0.68%   |
| Unity             | 9         | 0.62%   |
| i3                | 8         | 0.55%   |
| Deepin            | 8         | 0.55%   |
| KDE4              | 5         | 0.34%   |
| bspwm             | 5         | 0.34%   |
| Hyprland          | 4         | 0.27%   |
| GNOME Flashback   | 4         | 0.27%   |
| DWM               | 4         | 0.27%   |
| sway              | 3         | 0.21%   |
| ICEWM             | 3         | 0.21%   |
| Cutefish          | 3         | 0.21%   |
| Yaru:ubuntu:GNOME | 2         | 0.14%   |
| xmonad            | 2         | 0.14%   |
| qtile             | 2         | 0.14%   |
| LXDE              | 2         | 0.14%   |
| lightdm-xsession  | 2         | 0.14%   |
| Phosh:GNOME       | 1         | 0.07%   |
| Peux Gnome        | 1         | 0.07%   |
| openbox           | 1         | 0.07%   |
| Lubuntu           | 1         | 0.07%   |
| awesomeminimal    | 1         | 0.07%   |
| awesome           | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1036      | 71.45%  |
| Wayland | 293       | 20.21%  |
| Unknown | 102       | 7.03%   |
| Tty     | 19        | 1.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 641       | 44.12%  |
| SDDM    | 271       | 18.65%  |
| GDM     | 184       | 12.66%  |
| LightDM | 156       | 10.74%  |
| GDM3    | 153       | 10.53%  |
| TDM     | 37        | 2.55%   |
| KDM     | 5         | 0.34%   |
| SLiM    | 3         | 0.21%   |
| Ly      | 2         | 0.14%   |
| LXDM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1147      | 80.38%  |
| Unknown | 124       | 8.69%   |
| id_ID   | 92        | 6.45%   |
| C       | 21        | 1.47%   |
| en_GB   | 17        | 1.19%   |
| en_AU   | 6         | 0.42%   |
| en_AG   | 5         | 0.35%   |
| en_SG   | 3         | 0.21%   |
| de_DE   | 3         | 0.21%   |
| fr_FR   | 2         | 0.14%   |
| en_IN   | 2         | 0.14%   |
| jv_ID   | 1         | 0.07%   |
| it_IT   | 1         | 0.07%   |
| en_CA   | 1         | 0.07%   |
| de_CH   | 1         | 0.07%   |
| Default | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 779       | 54.17%  |
| BIOS | 659       | 45.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1076      | 74.88%  |
| Btrfs   | 141       | 9.81%   |
| Overlay | 107       | 7.45%   |
| Unknown | 45        | 3.13%   |
| Tmpfs   | 29        | 2.02%   |
| Xfs     | 22        | 1.53%   |
| Zfs     | 6         | 0.42%   |
| Ext2    | 5         | 0.35%   |
| F2fs    | 4         | 0.28%   |
| Ext3    | 2         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 650       | 45.23%  |
| GPT     | 602       | 41.89%  |
| MBR     | 185       | 12.87%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1243      | 86.92%  |
| Yes       | 187       | 13.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 837       | 58.37%  |
| Yes       | 597       | 41.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 298       | 21.18%  |
| ASUSTek Computer        | 266       | 18.91%  |
| Hewlett-Packard         | 185       | 13.15%  |
| Acer                    | 147       | 10.45%  |
| Dell                    | 108       | 7.68%   |
| MSI                     | 64        | 4.55%   |
| Gigabyte Technology     | 52        | 3.7%    |
| ASRock                  | 40        | 2.84%   |
| Toshiba                 | 34        | 2.42%   |
| Intel                   | 26        | 1.85%   |
| ECS                     | 18        | 1.28%   |
| Biostar                 | 18        | 1.28%   |
| Apple                   | 17        | 1.21%   |
| Unknown                 | 16        | 1.14%   |
| AXIOO                   | 12        | 0.85%   |
| Sony                    | 10        | 0.71%   |
| Fujitsu                 | 9         | 0.64%   |
| Samsung Electronics     | 8         | 0.57%   |
| Infinix                 | 5         | 0.36%   |
| AZW                     | 5         | 0.36%   |
| HUAWEI                  | 4         | 0.28%   |
| Clevo                   | 4         | 0.28%   |
| Valve                   | 3         | 0.21%   |
| Foxconn                 | 3         | 0.21%   |
| Timi                    | 2         | 0.14%   |
| Supermicro              | 2         | 0.14%   |
| realme                  | 2         | 0.14%   |
| Raspberry Pi Foundation | 2         | 0.14%   |
| Pegatron                | 2         | 0.14%   |
| Panasonic               | 2         | 0.14%   |
| OEM                     | 2         | 0.14%   |
| Microsoft               | 2         | 0.14%   |
| LORD ELECTRONICS        | 2         | 0.14%   |
| Langchao                | 2         | 0.14%   |
| ADVAN                   | 2         | 0.14%   |
| Acidanthera             | 2         | 0.14%   |
| ZYREX COMPUTER SYSTEMS  | 1         | 0.07%   |
| ZOTAC                   | 1         | 0.07%   |
| Xiaomi                  | 1         | 0.07%   |
| Wearnes                 | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 23        | 1.63%   |
| Lenovo IdeaPad 330-14AST 81D5           | 11        | 0.78%   |
| Lenovo G40-45 80E1                      | 11        | 0.78%   |
| HP Notebook                             | 11        | 0.78%   |
| HP Pavilion Aero Laptop 13-be0xxx       | 9         | 0.64%   |
| Acer Aspire 4752                        | 8         | 0.57%   |
| Lenovo G400 20235                       | 7         | 0.5%    |
| Intel H61                               | 7         | 0.5%    |
| Lenovo IdeaPad S340-14API 81NB          | 6         | 0.43%   |
| HP Laptop 14-bw0xx                      | 6         | 0.43%   |
| HP 14                                   | 6         | 0.43%   |
| Acer Aspire 4750                        | 6         | 0.43%   |
| HP Pavilion g4                          | 5         | 0.36%   |
| ASUS X455YA                             | 5         | 0.36%   |
| ASUS X455LF                             | 5         | 0.36%   |
| ASUS X441BA                             | 5         | 0.36%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 5         | 0.36%   |
| ASUS GL553VD                            | 5         | 0.36%   |
| ASUS All Series                         | 5         | 0.36%   |
| Apple MacBookPro12,1                    | 5         | 0.36%   |
| Acer Swift SFX14-41G                    | 5         | 0.36%   |
| Acer Swift SF314-71                     | 5         | 0.36%   |
| Acer One Z1402                          | 5         | 0.36%   |
| Lenovo Yoga C640-13IML 81UE             | 4         | 0.28%   |
| Lenovo IdeaPad 320-14AST 80XU           | 4         | 0.28%   |
| Lenovo G400s 20244                      | 4         | 0.28%   |
| Lenovo G40-30 80FY                      | 4         | 0.28%   |
| HP Pavilion 14                          | 4         | 0.28%   |
| HP Laptop 14-cm0xxx                     | 4         | 0.28%   |
| HP Laptop 14-bs0xx                      | 4         | 0.28%   |
| HP EliteBook 2570p                      | 4         | 0.28%   |
| HP 1000                                 | 4         | 0.28%   |
| Gigabyte H61M-DS2                       | 4         | 0.28%   |
| Dell OptiPlex 7010                      | 4         | 0.28%   |
| ASUS X456URK                            | 4         | 0.28%   |
| ASUS X453SA                             | 4         | 0.28%   |
| ASUS X450CC                             | 4         | 0.28%   |
| ASUS X442URR                            | 4         | 0.28%   |
| ASUS X441NA                             | 4         | 0.28%   |
| ASUS X200MA                             | 4         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 97        | 6.89%   |
| Lenovo ThinkPad    | 92        | 6.54%   |
| Acer Aspire        | 85        | 6.04%   |
| ASUS VivoBook      | 41        | 2.91%   |
| HP Laptop          | 40        | 2.84%   |
| HP Pavilion        | 38        | 2.7%    |
| Dell Latitude      | 38        | 2.7%    |
| Dell Inspiron      | 26        | 1.85%   |
| Unknown            | 23        | 1.63%   |
| Toshiba Satellite  | 22        | 1.56%   |
| Acer Swift         | 22        | 1.56%   |
| HP EliteBook       | 21        | 1.49%   |
| Dell OptiPlex      | 14        | 1%      |
| Lenovo Yoga        | 13        | 0.92%   |
| Dell Vostro        | 13        | 0.92%   |
| ASUS ROG           | 12        | 0.85%   |
| Lenovo ThinkCentre | 11        | 0.78%   |
| Lenovo G40-45      | 11        | 0.78%   |
| HP Notebook        | 11        | 0.78%   |
| Acer Nitro         | 10        | 0.71%   |
| Lenovo ThinkBook   | 9         | 0.64%   |
| HP ENVY            | 9         | 0.64%   |
| ASUS TUF           | 9         | 0.64%   |
| ASUS PRIME         | 8         | 0.57%   |
| ASUS ASUS          | 8         | 0.57%   |
| Toshiba PORTEGE    | 7         | 0.5%    |
| Lenovo G400        | 7         | 0.5%    |
| Intel H61          | 7         | 0.5%    |
| HP ProBook         | 7         | 0.5%    |
| MSI Modern         | 6         | 0.43%   |
| Lenovo ThinkSystem | 6         | 0.43%   |
| Lenovo IdeaPadFlex | 6         | 0.43%   |
| HP Compaq          | 6         | 0.43%   |
| HP 14              | 6         | 0.43%   |
| Acer One           | 6         | 0.43%   |
| Infinix INBook     | 5         | 0.36%   |
| HP ProLiant        | 5         | 0.36%   |
| Gigabyte H61M-DS2  | 5         | 0.36%   |
| AXIOO Mybook       | 5         | 0.36%   |
| ASUS X455YA        | 5         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 136       | 9.67%   |
| 2019    | 133       | 9.45%   |
| 2013    | 121       | 8.6%    |
| 2021    | 115       | 8.17%   |
| 2012    | 108       | 7.68%   |
| 2011    | 108       | 7.68%   |
| 2020    | 103       | 7.32%   |
| 2014    | 97        | 6.89%   |
| 2017    | 94        | 6.68%   |
| 2015    | 83        | 5.9%    |
| 2010    | 77        | 5.47%   |
| 2016    | 66        | 4.69%   |
| 2009    | 42        | 2.99%   |
| 2008    | 39        | 2.77%   |
| 2022    | 36        | 2.56%   |
| 2023    | 17        | 1.21%   |
| 2007    | 17        | 1.21%   |
| Unknown | 11        | 0.78%   |
| 2006    | 4         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 970       | 68.94%  |
| Desktop        | 329       | 23.38%  |
| Convertible    | 40        | 2.84%   |
| Server         | 21        | 1.49%   |
| All in one     | 19        | 1.35%   |
| Tablet         | 9         | 0.64%   |
| Mini pc        | 7         | 0.5%    |
| System on chip | 6         | 0.43%   |
| Phone          | 5         | 0.36%   |
| Other          | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1312      | 92.39%  |
| Enabled  | 108       | 7.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1406      | 99.93%  |
| Yes  | 1         | 0.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 423       | 29.73%  |
| 3.01-4.0        | 360       | 25.3%   |
| 8.01-16.0       | 255       | 17.92%  |
| 16.01-24.0      | 188       | 13.21%  |
| 1.01-2.0        | 101       | 7.1%    |
| 32.01-64.0      | 49        | 3.44%   |
| 2.01-3.0        | 15        | 1.05%   |
| 24.01-32.0      | 12        | 0.84%   |
| 64.01-256.0     | 11        | 0.77%   |
| 0.51-1.0        | 8         | 0.56%   |
| More than 256.0 | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 553       | 35.63%  |
| 2.01-3.0   | 427       | 27.51%  |
| 4.01-8.0   | 213       | 13.72%  |
| 3.01-4.0   | 209       | 13.47%  |
| 0.51-1.0   | 96        | 6.19%   |
| 8.01-16.0  | 38        | 2.45%   |
| 0.01-0.5   | 9         | 0.58%   |
| 16.01-24.0 | 6         | 0.39%   |
| Unknown    | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 949       | 65.86%  |
| 2       | 384       | 26.65%  |
| 3       | 64        | 4.44%   |
| 4       | 22        | 1.53%   |
| 0       | 11        | 0.76%   |
| 5       | 5         | 0.35%   |
| 6       | 2         | 0.14%   |
| 15      | 1         | 0.07%   |
| 8       | 1         | 0.07%   |
| 7       | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 964       | 67.89%  |
| Yes       | 456       | 32.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1163      | 82.6%   |
| No        | 245       | 17.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1216      | 85.88%  |
| No        | 200       | 14.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 916       | 64.46%  |
| No        | 505       | 35.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Indonesia | 1407      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Jakarta         | 404       | 26.37%  |
| Surabaya        | 133       | 8.68%   |
| Bandung         | 115       | 7.51%   |
| Yogyakarta      | 66        | 4.31%   |
| Semarang        | 48        | 3.13%   |
| Bogor           | 48        | 3.13%   |
| Bekasi          | 43        | 2.81%   |
| Tangerang       | 40        | 2.61%   |
| Malang          | 34        | 2.22%   |
| South Tangerang | 33        | 2.15%   |
| Medan           | 32        | 2.09%   |
| Denpasar        | 31        | 2.02%   |
| Depok           | 22        | 1.44%   |
| Palembang       | 19        | 1.24%   |
| Makassar        | 16        | 1.04%   |
| Banjarmasin     | 15        | 0.98%   |
| Sleman          | 14        | 0.91%   |
| Balikpapan      | 13        | 0.85%   |
| Tasikmalaya     | 11        | 0.72%   |
| Samarinda       | 11        | 0.72%   |
| Surakarta       | 10        | 0.65%   |
| Blitar          | 10        | 0.65%   |
| Banda Aceh      | 10        | 0.65%   |
| Gresik          | 9         | 0.59%   |
| Batam           | 9         | 0.59%   |
| Pasuruan        | 8         | 0.52%   |
| Mataram         | 8         | 0.52%   |
| Magelang        | 8         | 0.52%   |
| Jember          | 8         | 0.52%   |
| Brebes          | 7         | 0.46%   |
| Pontianak       | 6         | 0.39%   |
| Pekanbaru       | 6         | 0.39%   |
| Kudus           | 6         | 0.39%   |
| Kediri          | 6         | 0.39%   |
| Cirebon         | 6         | 0.39%   |
| Sukabumi        | 5         | 0.33%   |
| Pekan Baru      | 5         | 0.33%   |
| Demak           | 5         | 0.33%   |
| Bandar Lampung  | 5         | 0.33%   |
| Tanjung Pinang  | 4         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 354       | 478    | 18.73%  |
| WDC                   | 257       | 338    | 13.6%   |
| Samsung Electronics   | 172       | 229    | 9.1%    |
| Toshiba               | 157       | 175    | 8.31%   |
| HGST                  | 73        | 85     | 3.86%   |
| Hitachi               | 69        | 85     | 3.65%   |
| Unknown               | 66        | 87     | 3.49%   |
| SanDisk               | 65        | 80     | 3.44%   |
| Intel                 | 50        | 69     | 2.65%   |
| V-GeN                 | 46        | 50     | 2.43%   |
| Kingston              | 46        | 56     | 2.43%   |
| A-DATA Technology     | 45        | 55     | 2.38%   |
| SK hynix              | 40        | 46     | 2.12%   |
| MidasForce            | 34        | 38     | 1.8%    |
| Micron Technology     | 32        | 44     | 1.69%   |
| China                 | 25        | 28     | 1.32%   |
| Unknown               | 25        | 26     | 1.32%   |
| Silicon Motion        | 19        | 22     | 1.01%   |
| Apacer                | 18        | 21     | 0.95%   |
| Patriot               | 14        | 24     | 0.74%   |
| JMicron Technology    | 14        | 15     | 0.74%   |
| VISIPRO               | 13        | 16     | 0.69%   |
| Team                  | 12        | 15     | 0.63%   |
| RX7                   | 12        | 15     | 0.63%   |
| EYOTA                 | 12        | 16     | 0.63%   |
| Fujitsu               | 11        | 12     | 0.58%   |
| Crucial               | 10        | 12     | 0.53%   |
| Apple                 | 10        | 11     | 0.53%   |
| Transcend             | 7         | 11     | 0.37%   |
| ADATA Technology      | 7         | 14     | 0.37%   |
| Pioneer               | 6         | 6      | 0.32%   |
| Phison Electronics    | 6         | 7      | 0.32%   |
| KIOXIA                | 6         | 6      | 0.32%   |
| External              | 6         | 6      | 0.32%   |
| XPG                   | 5         | 8      | 0.26%   |
| Wellcomm              | 5         | 5      | 0.26%   |
| Realtek Semiconductor | 5         | 5      | 0.26%   |
| Ramos Technology      | 5         | 12     | 0.26%   |
| PNY                   | 5         | 6      | 0.26%   |
| Phison                | 5         | 7      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 44        | 2.19%   |
| Seagate ST500LT012-1DG142 500GB    | 43        | 2.14%   |
| Toshiba MQ01ABF050 500GB           | 30        | 1.49%   |
| Toshiba MQ04ABF100 1TB             | 25        | 1.25%   |
| Unknown                            | 25        | 1.25%   |
| Toshiba MQ01ABD100 1TB             | 22        | 1.1%    |
| Seagate ST3500312CS 500GB          | 22        | 1.1%    |
| HGST HTS545050A7E680 500GB         | 21        | 1.05%   |
| A-DATA SU650 120GB SSD             | 19        | 0.95%   |
| Seagate ST500DM002-1BD142 500GB    | 18        | 0.9%    |
| Hitachi HTS543232A7A384 320GB      | 14        | 0.7%    |
| MidasForce SSD 128GB               | 12        | 0.6%    |
| Seagate ST9500325AS 500GB          | 11        | 0.55%   |
| Seagate ST500LT012-9WS142 500GB    | 11        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB     | 11        | 0.55%   |
| HGST HTS721010A9E630 1TB           | 11        | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 10        | 0.5%    |
| Seagate ST9320325AS 320GB          | 10        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 10        | 0.5%    |
| SanDisk NVMe SSD Drive 512GB       | 10        | 0.5%    |
| Samsung SSD 860 EVO 250GB          | 10        | 0.5%    |
| Samsung SSD 850 EVO 250GB          | 10        | 0.5%    |
| Hitachi HTS545050A7E380 500GB      | 10        | 0.5%    |
| HGST HTS725050A7E630 500GB         | 10        | 0.5%    |
| HGST HTS545050A7E380 500GB         | 10        | 0.5%    |
| Unknown MMC Card  64GB             | 9         | 0.45%   |
| Unknown MMC Card  128GB            | 9         | 0.45%   |
| Seagate ST3250318AS 250GB          | 9         | 0.45%   |
| Seagate ST1000LM049-2GH172 1TB     | 9         | 0.45%   |
| Intel SSDPEKNW512G8 512GB          | 9         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 8         | 0.4%    |
| WDC WD10SPZX-21Z10T0 1TB           | 8         | 0.4%    |
| Unknown SD/MMC/MS PRO 256GB        | 8         | 0.4%    |
| Unknown MMC Card  32GB             | 8         | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB     | 8         | 0.4%    |
| MidasForce SSD 120GB               | 8         | 0.4%    |
| JMicron Generic 8GB                | 8         | 0.4%    |
| Apacer AS340 240GB SSD             | 8         | 0.4%    |
| A-DATA SU650 240GB SSD             | 8         | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 7         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 351       | 471    | 39.09%  |
| WDC                 | 203       | 266    | 22.61%  |
| Toshiba             | 137       | 152    | 15.26%  |
| HGST                | 73        | 85     | 8.13%   |
| Hitachi             | 69        | 85     | 7.68%   |
| Samsung Electronics | 13        | 13     | 1.45%   |
| Unknown             | 9         | 9      | 1%      |
| JMicron Technology  | 9         | 9      | 1%      |
| Fujitsu             | 9         | 9      | 1%      |
| External            | 6         | 6      | 0.67%   |
| Maxtor              | 4         | 4      | 0.45%   |
| Apple               | 4         | 4      | 0.45%   |
| Hewlett-Packard     | 3         | 3      | 0.33%   |
| TO Exter            | 2         | 2      | 0.22%   |
| Unknown             | 2         | 2      | 0.22%   |
| SYMTEC              | 1         | 1      | 0.11%   |
| HGST HTS            | 1         | 3      | 0.11%   |
| ExcelStor           | 1         | 1      | 0.11%   |
| CLOVER              | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 76        | 101    | 14.62%  |
| WDC                 | 35        | 44     | 6.73%   |
| SanDisk             | 34        | 46     | 6.54%   |
| MidasForce          | 33        | 37     | 6.35%   |
| A-DATA Technology   | 32        | 39     | 6.15%   |
| V-GeN               | 31        | 35     | 5.96%   |
| Kingston            | 30        | 33     | 5.77%   |
| China               | 25        | 28     | 4.81%   |
| Apacer              | 18        | 21     | 3.46%   |
| Patriot             | 14        | 24     | 2.69%   |
| Unknown             | 14        | 14     | 2.69%   |
| VISIPRO             | 10        | 13     | 1.92%   |
| Team                | 10        | 13     | 1.92%   |
| Intel               | 10        | 14     | 1.92%   |
| EYOTA               | 10        | 13     | 1.92%   |
| Toshiba             | 9         | 10     | 1.73%   |
| Crucial             | 9         | 11     | 1.73%   |
| RX7                 | 8         | 9      | 1.54%   |
| Seagate             | 6         | 6      | 1.15%   |
| Pioneer             | 6         | 6      | 1.15%   |
| Wellcomm            | 5         | 5      | 0.96%   |
| Transcend           | 5         | 8      | 0.96%   |
| Ramos Technology    | 5         | 12     | 0.96%   |
| Micron Technology   | 5         | 7      | 0.96%   |
| Apple               | 5         | 5      | 0.96%   |
| SK hynix            | 4         | 5      | 0.77%   |
| LITEON              | 4         | 5      | 0.77%   |
| XSTAR               | 3         | 3      | 0.58%   |
| Unknown             | 3         | 4      | 0.58%   |
| PNY                 | 3         | 3      | 0.58%   |
| OCZ                 | 3         | 3      | 0.58%   |
| LITEONIT            | 3         | 4      | 0.58%   |
| Kingmax             | 3         | 3      | 0.58%   |
| GALAX               | 3         | 3      | 0.58%   |
| Varro               | 2         | 2      | 0.38%   |
| USB3.0              | 2         | 2      | 0.38%   |
| T-FORCE             | 2         | 2      | 0.38%   |
| SPCC                | 2         | 2      | 0.38%   |
| Smart               | 2         | 2      | 0.38%   |
| Netac               | 2         | 2      | 0.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 799       | 1126   | 46.03%  |
| SSD     | 475       | 638    | 27.36%  |
| NVMe    | 359       | 478    | 20.68%  |
| Unknown | 52        | 61     | 3%      |
| MMC     | 51        | 71     | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1088      | 1753   | 69.65%  |
| NVMe | 359       | 476    | 22.98%  |
| SAS  | 64        | 74     | 4.1%    |
| MMC  | 51        | 71     | 3.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 836       | 1223   | 67.37%  |
| 0.51-1.0   | 335       | 438    | 26.99%  |
| 1.01-2.0   | 51        | 79     | 4.11%   |
| 3.01-4.0   | 9         | 14     | 0.73%   |
| 2.01-3.0   | 7         | 7      | 0.56%   |
| 4.01-10.0  | 3         | 3      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 425       | 28.79%  |
| 251-500        | 365       | 24.73%  |
| 501-1000       | 174       | 11.79%  |
| 51-100         | 153       | 10.37%  |
| 1-20           | 105       | 7.11%   |
| 1001-2000      | 97        | 6.57%   |
| 21-50          | 87        | 5.89%   |
| Unknown        | 29        | 1.96%   |
| More than 3000 | 23        | 1.56%   |
| 2001-3000      | 18        | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 575       | 37.36%  |
| 21-50          | 286       | 18.58%  |
| 101-250        | 206       | 13.39%  |
| 51-100         | 189       | 12.28%  |
| 251-500        | 135       | 8.77%   |
| 501-1000       | 80        | 5.2%    |
| Unknown        | 29        | 1.88%   |
| 1001-2000      | 24        | 1.56%   |
| More than 3000 | 10        | 0.65%   |
| 2001-3000      | 5         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB            | 9         | 10     | 4.21%   |
| Seagate ST500LT012-1DG142 500GB       | 7         | 7      | 3.27%   |
| Seagate ST500DM002-1BD142 500GB       | 7         | 9      | 3.27%   |
| Seagate ST500LT012-9WS142 500GB       | 6         | 6      | 2.8%    |
| Seagate ST9500325AS 500GB             | 5         | 5      | 2.34%   |
| HGST HTS545050A7E380 500GB            | 4         | 5      | 1.87%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 3         | 3      | 1.4%    |
| Toshiba MQ01ABF050 500GB              | 3         | 3      | 1.4%    |
| Toshiba MQ01ABD032 320GB              | 3         | 3      | 1.4%    |
| Seagate ST1000LX015-1U7172 1TB        | 3         | 4      | 1.4%    |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 3      | 1.4%    |
| Hitachi HTS545050A7E380 500GB         | 3         | 3      | 1.4%    |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.4%    |
| WDC WD800JD-08LSA0 80GB               | 2         | 2      | 0.93%   |
| WDC WD3200BEKT-60V5T1 320GB           | 2         | 2      | 0.93%   |
| WDC WD3200AAKS-61L9A0 320GB           | 2         | 3      | 0.93%   |
| WDC WD10JPCX-24UE4T0 1TB              | 2         | 3      | 0.93%   |
| WDC WD10EZEX-08M2NA0 1TB              | 2         | 2      | 0.93%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.93%   |
| Toshiba MQ01ABD050 500GB              | 2         | 2      | 0.93%   |
| Toshiba MK5059GSXP 500GB              | 2         | 2      | 0.93%   |
| Toshiba MK3265GSX 320GB               | 2         | 3      | 0.93%   |
| Seagate ST9500420AS 500GB             | 2         | 2      | 0.93%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 0.93%   |
| Seagate ST9250410AS 250GB             | 2         | 2      | 0.93%   |
| Seagate ST320LT012-9WS14C 320GB       | 2         | 2      | 0.93%   |
| Seagate ST1000DM003-1ER162 1TB        | 2         | 2      | 0.93%   |
| SanDisk SSD PLUS 120 GB               | 2         | 2      | 0.93%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 2      | 0.93%   |
| Hitachi HTS545032B9A300 320GB         | 2         | 2      | 0.93%   |
| Hitachi HTS545016B9A300 160GB         | 2         | 2      | 0.93%   |
| Hitachi HTS543232A7A384 320GB         | 2         | 2      | 0.93%   |
| A-DATA Technology SU800NS38 256GB SSD | 2         | 2      | 0.93%   |
| Unknown                               | 2         | 2      | 0.93%   |
| WellcommMaster 128GB SSD              | 1         | 1      | 0.47%   |
| Wellcomm Master 128GB SSD             | 1         | 1      | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.47%   |
| WDC WD7500BPVT-55HXZT4 752GB          | 1         | 1      | 0.47%   |
| WDC WD6400AADS-00M2B0 640GB           | 1         | 1      | 0.47%   |
| WDC WD5000LPVX-80V0TT0 500GB          | 1         | 1      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 72     | 28.64%  |
| WDC                 | 42        | 49     | 20.39%  |
| Toshiba             | 24        | 26     | 11.65%  |
| Hitachi             | 21        | 21     | 10.19%  |
| HGST                | 20        | 23     | 9.71%   |
| Samsung Electronics | 5         | 6      | 2.43%   |
| SanDisk             | 4         | 4      | 1.94%   |
| A-DATA Technology   | 4         | 6      | 1.94%   |
| Micron Technology   | 3         | 3      | 1.46%   |
| KLEVV               | 2         | 2      | 0.97%   |
| Kingston            | 2         | 2      | 0.97%   |
| Crucial             | 2         | 2      | 0.97%   |
| China               | 2         | 2      | 0.97%   |
| Unknown             | 2         | 2      | 0.97%   |
| WellcommMaster      | 1         | 1      | 0.49%   |
| Wellcomm            | 1         | 1      | 0.49%   |
| VISIPRO             | 1         | 3      | 0.49%   |
| ValueTech           | 1         | 1      | 0.49%   |
| T-FORCE             | 1         | 1      | 0.49%   |
| SK hynix            | 1         | 1      | 0.49%   |
| Silicon Motion      | 1         | 1      | 0.49%   |
| RX7                 | 1         | 1      | 0.49%   |
| Maxtor              | 1         | 1      | 0.49%   |
| Intel               | 1         | 1      | 0.49%   |
| EYOTA               | 1         | 1      | 0.49%   |
| CLOVER              | 1         | 1      | 0.49%   |
| Apple               | 1         | 1      | 0.49%   |
| Apacer              | 1         | 2      | 0.49%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 72     | 34.3%   |
| WDC                 | 41        | 48     | 23.84%  |
| Toshiba             | 24        | 26     | 13.95%  |
| Hitachi             | 21        | 21     | 12.21%  |
| HGST                | 20        | 23     | 11.63%  |
| Samsung Electronics | 3         | 3      | 1.74%   |
| Maxtor              | 1         | 1      | 0.58%   |
| CLOVER              | 1         | 1      | 0.58%   |
| Apple               | 1         | 1      | 0.58%   |
| Unknown             | 1         | 1      | 0.58%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 159       | 197    | 82.81%  |
| SSD  | 28        | 34     | 14.58%  |
| NVMe | 5         | 6      | 2.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3250318AS 250GB         | 2         | 2      | 28.57%  |
| WDC WD5000BPVT-60HXZT1 500GB      | 1         | 1      | 14.29%  |
| Toshiba MK2575GSX 250GB           | 1         | 1      | 14.29%  |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 14.29%  |
| Hitachi HTS543232A7A384 320GB     | 1         | 1      | 14.29%  |
| A-DATA Technology SX8200PNP 256GB | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 2         | 2      | 28.57%  |
| Hitachi           | 2         | 2      | 28.57%  |
| WDC               | 1         | 1      | 14.29%  |
| Toshiba           | 1         | 1      | 14.29%  |
| A-DATA Technology | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 756       | 1239   | 49.19%  |
| Works    | 587       | 891    | 38.19%  |
| Malfunc  | 187       | 237    | 12.17%  |
| Failed   | 7         | 7      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 967       | 58.78%  |
| AMD                              | 287       | 17.45%  |
| Samsung Electronics              | 91        | 5.53%   |
| SanDisk                          | 53        | 3.22%   |
| SK hynix                         | 35        | 2.13%   |
| Silicon Motion                   | 29        | 1.76%   |
| Micron Technology                | 27        | 1.64%   |
| ADATA Technology                 | 24        | 1.46%   |
| Kingston Technology Company      | 20        | 1.22%   |
| Phison Electronics               | 16        | 0.97%   |
| ASMedia Technology               | 11        | 0.67%   |
| Toshiba America Info Systems     | 9         | 0.55%   |
| Realtek Semiconductor            | 8         | 0.49%   |
| KIOXIA                           | 8         | 0.49%   |
| JMicron Technology               | 7         | 0.43%   |
| Union Memory (Shenzhen)          | 6         | 0.36%   |
| Broadcom / LSI                   | 6         | 0.36%   |
| Silicon Integrated Systems [SiS] | 5         | 0.3%    |
| Nvidia                           | 5         | 0.3%    |
| VIA Technologies                 | 4         | 0.24%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.24%   |
| Hewlett-Packard                  | 4         | 0.24%   |
| Shenzhen Longsys Electronics     | 3         | 0.18%   |
| Micron/Crucial Technology        | 3         | 0.18%   |
| Marvell Technology Group         | 3         | 0.18%   |
| LSI Logic / Symbios Logic        | 2         | 0.12%   |
| Adaptec                          | 2         | 0.12%   |
| Solid State Storage Technology   | 1         | 0.06%   |
| O2 Micro                         | 1         | 0.06%   |
| Lenovo                           | 1         | 0.06%   |
| INNOGRIT                         | 1         | 0.06%   |
| Biwin Storage Technology         | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 225       | 12.08%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 93        | 4.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 91        | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 54        | 2.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 53        | 2.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 49        | 2.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 49        | 2.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 41        | 2.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 41        | 2.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 36        | 1.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 35        | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 33        | 1.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 30        | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 29        | 1.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 23        | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 23        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 23        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 23        | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 22        | 1.18%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 21        | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 21        | 1.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 21        | 1.13%   |
| Intel SSD 660P Series                                                                   | 20        | 1.07%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 19        | 1.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 19        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 18        | 0.97%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 18        | 0.97%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 17        | 0.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17        | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 17        | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 16        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 16        | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 15        | 0.81%   |
| AMD FCH IDE Controller                                                                  | 14        | 0.75%   |
| AMD 500 Series Chipset SATA Controller                                                  | 14        | 0.75%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 13        | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 13        | 0.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13        | 0.7%    |
| SK hynix BC511 NVMe SSD                                                                 | 12        | 0.64%   |
| Micron 2210 NVMe SSD [Cobain]                                                           | 12        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1066      | 62.71%  |
| NVMe | 359       | 21.12%  |
| IDE  | 167       | 9.82%   |
| RAID | 103       | 6.06%   |
| SAS  | 4         | 0.24%   |
| SCSI | 1         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1046      | 74.34%  |
| AMD      | 349       | 24.8%   |
| ARM      | 8         | 0.57%   |
| QUALCOMM | 4         | 0.28%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 18        | 1.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.21%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 1.14%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 16        | 1.14%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 16        | 1.14%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 1.06%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 14        | 0.99%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 14        | 0.99%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 0.99%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 0.92%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 13        | 0.92%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 13        | 0.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 12        | 0.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 12        | 0.85%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 12        | 0.85%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 12        | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 0.78%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 11        | 0.78%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 11        | 0.78%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 11        | 0.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 0.71%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 10        | 0.71%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 10        | 0.71%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 10        | 0.71%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 10        | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 0.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 0.64%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 9         | 0.64%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 9         | 0.64%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 9         | 0.64%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.64%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 9         | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.57%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 8         | 0.57%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 8         | 0.57%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 8         | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 324       | 23%     |
| Intel Core i3           | 187       | 13.27%  |
| Intel Core i7           | 168       | 11.92%  |
| Other                   | 119       | 8.45%   |
| Intel Celeron           | 98        | 6.96%   |
| AMD Ryzen 5             | 86        | 6.1%    |
| Intel Core 2 Duo        | 57        | 4.05%   |
| AMD Ryzen 3             | 40        | 2.84%   |
| Intel Pentium           | 33        | 2.34%   |
| AMD Ryzen 7             | 32        | 2.27%   |
| AMD A8                  | 27        | 1.92%   |
| Intel Xeon              | 26        | 1.85%   |
| Intel Atom              | 19        | 1.35%   |
| AMD A6                  | 16        | 1.14%   |
| Intel Pentium Dual-Core | 15        | 1.06%   |
| AMD A4                  | 15        | 1.06%   |
| AMD E1                  | 11        | 0.78%   |
| Intel Core 2 Quad       | 10        | 0.71%   |
| AMD FX                  | 10        | 0.71%   |
| AMD E                   | 9         | 0.64%   |
| AMD Athlon              | 9         | 0.64%   |
| AMD Ryzen 9             | 8         | 0.57%   |
| Intel Genuine           | 7         | 0.5%    |
| AMD E2                  | 7         | 0.5%    |
| AMD A10                 | 7         | 0.5%    |
| Intel Pentium Dual      | 6         | 0.43%   |
| AMD Athlon II X2        | 6         | 0.43%   |
| Intel Core 2            | 5         | 0.35%   |
| Intel Xeon Bronze       | 4         | 0.28%   |
| AMD Ryzen 5 PRO         | 4         | 0.28%   |
| AMD Phenom II X6        | 4         | 0.28%   |
| AMD Athlon X4           | 4         | 0.28%   |
| QUALCOMM AArch64        | 3         | 0.21%   |
| Intel Pentium Silver    | 3         | 0.21%   |
| Intel Pentium Gold      | 3         | 0.21%   |
| AMD Phenom II X4        | 3         | 0.21%   |
| AMD C-60                | 3         | 0.21%   |
| Intel Xeon Silver       | 2         | 0.14%   |
| Intel Pentium D         | 2         | 0.14%   |
| AMD Ryzen 3 PRO         | 2         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 777       | 55.15%  |
| 4       | 412       | 29.24%  |
| 6       | 114       | 8.09%   |
| 8       | 53        | 3.76%   |
| 1       | 16        | 1.14%   |
| 10      | 15        | 1.06%   |
| 12      | 12        | 0.85%   |
| 3       | 3         | 0.21%   |
| 16      | 2         | 0.14%   |
| 14      | 2         | 0.14%   |
| Unknown | 2         | 0.14%   |
| 44      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1393      | 99%     |
| 2       | 10        | 0.71%   |
| 3       | 2         | 0.14%   |
| Unknown | 2         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 915       | 64.99%  |
| 1       | 491       | 34.87%  |
| Unknown | 2         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1377      | 97.87%  |
| Unknown        | 22        | 1.56%   |
| 64-bit         | 4         | 0.28%   |
| 32-bit         | 4         | 0.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 373       | 25.44%  |
| 0x206a7    | 91        | 6.21%   |
| 0x306a9    | 83        | 5.66%   |
| 0x1067a    | 50        | 3.41%   |
| 0x306c3    | 44        | 3%      |
| 0x40651    | 43        | 2.93%   |
| 0x306d4    | 34        | 2.32%   |
| 0x806ec    | 33        | 2.25%   |
| 0x906ea    | 30        | 2.05%   |
| 0x806ea    | 30        | 2.05%   |
| 0x06006705 | 29        | 1.98%   |
| 0x08108109 | 27        | 1.84%   |
| 0x806e9    | 26        | 1.77%   |
| 0x806c1    | 26        | 1.77%   |
| 0x406e3    | 26        | 1.77%   |
| 0x20655    | 24        | 1.64%   |
| 0x0a50000c | 21        | 1.43%   |
| 0x906e9    | 19        | 1.3%    |
| 0x6fd      | 17        | 1.16%   |
| 0x08108102 | 17        | 1.16%   |
| 0x806eb    | 16        | 1.09%   |
| 0x20652    | 15        | 1.02%   |
| 0x07030105 | 15        | 1.02%   |
| 0x706e5    | 13        | 0.89%   |
| 0x30678    | 13        | 0.89%   |
| 0x08608103 | 13        | 0.89%   |
| 0x706a8    | 12        | 0.82%   |
| 0x506e3    | 11        | 0.75%   |
| 0x406c4    | 11        | 0.75%   |
| 0x0810100b | 11        | 0.75%   |
| 0x06001119 | 11        | 0.75%   |
| 0x406c3    | 10        | 0.68%   |
| 0x08600104 | 10        | 0.68%   |
| 0x10676    | 9         | 0.61%   |
| 0x0700010f | 8         | 0.55%   |
| 0x906a3    | 7         | 0.48%   |
| 0x706a1    | 7         | 0.48%   |
| 0x6fb      | 7         | 0.48%   |
| 0x08101007 | 7         | 0.48%   |
| 0x05000119 | 7         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 215       | 15.27%  |
| SandyBridge      | 122       | 8.66%   |
| IvyBridge        | 115       | 8.17%   |
| Haswell          | 108       | 7.67%   |
| Penryn           | 67        | 4.76%   |
| Westmere         | 58        | 4.12%   |
| Unknown          | 56        | 3.98%   |
| Skylake          | 55        | 3.91%   |
| Excavator        | 54        | 3.84%   |
| Zen+             | 53        | 3.76%   |
| Silvermont       | 49        | 3.48%   |
| Broadwell        | 47        | 3.34%   |
| TigerLake        | 38        | 2.7%    |
| Zen 3            | 35        | 2.49%   |
| Zen              | 34        | 2.41%   |
| Core             | 32        | 2.27%   |
| Zen 2            | 31        | 2.2%    |
| Puma             | 27        | 1.92%   |
| IceLake          | 26        | 1.85%   |
| Goldmont plus    | 24        | 1.7%    |
| Alderlake Hybrid | 22        | 1.56%   |
| Piledriver       | 20        | 1.42%   |
| CometLake        | 18        | 1.28%   |
| Bobcat           | 17        | 1.21%   |
| K10              | 14        | 0.99%   |
| Jaguar           | 11        | 0.78%   |
| Goldmont         | 11        | 0.78%   |
| Bonnell          | 9         | 0.64%   |
| Steamroller      | 8         | 0.57%   |
| Nehalem          | 8         | 0.57%   |
| K10 Llano        | 8         | 0.57%   |
| Tremont          | 6         | 0.43%   |
| K8 Hammer        | 3         | 0.21%   |
| P6               | 2         | 0.14%   |
| NetBurst         | 2         | 0.14%   |
| Bulldozer        | 2         | 0.14%   |
| Gracemont        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 907       | 52.95%  |
| AMD                              | 436       | 25.45%  |
| Nvidia                           | 345       | 20.14%  |
| Matrox Electronics Systems       | 14        | 0.82%   |
| Silicon Integrated Systems [SiS] | 5         | 0.29%   |
| ASPEED Technology                | 5         | 0.29%   |
| Silicon Motion                   | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 103       | 5.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 75        | 4.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 52        | 2.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 51        | 2.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 45        | 2.53%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 41        | 2.31%   |
| Intel UHD Graphics 620                                                                   | 39        | 2.19%   |
| Intel HD Graphics 620                                                                    | 38        | 2.14%   |
| Intel HD Graphics 5500                                                                   | 38        | 2.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 36        | 2.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 29        | 1.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 28        | 1.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 1.46%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 1.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 1.41%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 25        | 1.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 24        | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 1.35%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 1.29%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 23        | 1.29%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 22        | 1.24%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22        | 1.24%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 21        | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 20        | 1.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 20        | 1.13%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 20        | 1.13%   |
| AMD Lucienne                                                                             | 19        | 1.07%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 17        | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.84%   |
| Intel HD Graphics 630                                                                    | 15        | 0.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 0.84%   |
| Nvidia GT218 [GeForce 210]                                                               | 13        | 0.73%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 13        | 0.73%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 13        | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 0.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 13        | 0.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 625       | 44.11%  |
| 1 x AMD                | 308       | 21.74%  |
| Intel + Nvidia         | 211       | 14.89%  |
| 1 x Nvidia             | 97        | 6.85%   |
| Intel + AMD            | 57        | 4.02%   |
| 2 x AMD                | 39        | 2.75%   |
| AMD + Nvidia           | 32        | 2.26%   |
| 1 x Matrox             | 14        | 0.99%   |
| Other                  | 13        | 0.92%   |
| 2 x Intel              | 7         | 0.49%   |
| 1 x SiS                | 5         | 0.35%   |
| 1 x ASPEED             | 4         | 0.28%   |
| 2 x Nvidia             | 2         | 0.14%   |
| 1 x Silicon Motion     | 1         | 0.07%   |
| Nvidia + ASPEED        | 1         | 0.07%   |
| 1 x Intel + 4 x Nvidia | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1211      | 84.8%   |
| Proprietary | 171       | 11.97%  |
| Unknown     | 46        | 3.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 855       | 59.01%  |
| 1.01-2.0   | 215       | 14.84%  |
| 0.01-0.5   | 175       | 12.08%  |
| 0.51-1.0   | 96        | 6.63%   |
| 3.01-4.0   | 66        | 4.55%   |
| 5.01-6.0   | 17        | 1.17%   |
| 7.01-8.0   | 15        | 1.04%   |
| 8.01-16.0  | 7         | 0.48%   |
| 2.01-3.0   | 3         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 231       | 16.33%  |
| Chimei Innolux          | 214       | 15.12%  |
| BOE                     | 179       | 12.65%  |
| LG Display              | 143       | 10.11%  |
| Samsung Electronics     | 128       | 9.05%   |
| Goldstar                | 118       | 8.34%   |
| Dell                    | 50        | 3.53%   |
| Lenovo                  | 41        | 2.9%    |
| Hewlett-Packard         | 25        | 1.77%   |
| AOC                     | 22        | 1.55%   |
| InfoVision              | 19        | 1.34%   |
| Acer                    | 19        | 1.34%   |
| Sharp                   | 18        | 1.27%   |
| Philips                 | 17        | 1.2%    |
| ViewSonic               | 16        | 1.13%   |
| PANDA                   | 16        | 1.13%   |
| Apple                   | 16        | 1.13%   |
| Chi Mei Optoelectronics | 11        | 0.78%   |
| BenQ                    | 10        | 0.71%   |
| Toshiba                 | 9         | 0.64%   |
| LG Electronics          | 8         | 0.57%   |
| InnoLux Display         | 8         | 0.57%   |
| LG Philips              | 6         | 0.42%   |
| Ancor Communications    | 6         | 0.42%   |
| Mi                      | 5         | 0.35%   |
| Sony                    | 4         | 0.28%   |
| Panasonic               | 4         | 0.28%   |
| KDC                     | 4         | 0.28%   |
| HKC                     | 4         | 0.28%   |
| HannStar                | 4         | 0.28%   |
| CPT                     | 4         | 0.28%   |
| Valve                   | 3         | 0.21%   |
| Unknown                 | 3         | 0.21%   |
| Quanta Display          | 3         | 0.21%   |
| QCM                     | 3         | 0.21%   |
| JRY                     | 3         | 0.21%   |
| ASUSTek Computer        | 3         | 0.21%   |
| TMX                     | 2         | 0.14%   |
| SPC                     | 2         | 0.14%   |
| Seiko/Epson             | 2         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 20        | 1.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 19        | 1.33%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch      | 19        | 1.33%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 17        | 1.19%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 16        | 1.12%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 15        | 1.05%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 14        | 0.98%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 13        | 0.91%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 12        | 0.84%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                 | 12        | 0.84%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 11        | 0.77%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 11        | 0.77%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch        | 11        | 0.77%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 11        | 0.77%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 10        | 0.7%    |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 10        | 0.7%    |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch        | 10        | 0.7%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 9         | 0.63%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 9         | 0.63%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                 | 9         | 0.63%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 9         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 8         | 0.56%   |
| LG Display LCD Monitor LGD02F8 1366x768 310x170mm 13.9-inch          | 7         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch      | 7         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch      | 7         | 0.49%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 7         | 0.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 7         | 0.49%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch        | 7         | 0.49%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch          | 6         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch      | 6         | 0.42%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 6         | 0.42%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch       | 6         | 0.42%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 5         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch | 5         | 0.35%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch          | 5         | 0.35%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 5         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 5         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch     | 5         | 0.35%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                | 5         | 0.35%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch        | 5         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 630       | 46.02%  |
| 1920x1080 (FHD)    | 470       | 34.33%  |
| 3840x2160 (4K)     | 40        | 2.92%   |
| 1440x900 (WXGA+)   | 35        | 2.56%   |
| 1600x900 (HD+)     | 32        | 2.34%   |
| 1280x800 (WXGA)    | 27        | 1.97%   |
| 2560x1440 (QHD)    | 23        | 1.68%   |
| 1920x1200 (WUXGA)  | 18        | 1.31%   |
| 1360x768           | 17        | 1.24%   |
| 2560x1600          | 10        | 0.73%   |
| 1280x1024 (SXGA)   | 9         | 0.66%   |
| 2560x1080          | 8         | 0.58%   |
| 2880x1800          | 7         | 0.51%   |
| 3440x1440          | 5         | 0.37%   |
| 1024x768 (XGA)     | 4         | 0.29%   |
| 1024x600           | 4         | 0.29%   |
| 800x1280           | 3         | 0.22%   |
| 2800x1752          | 3         | 0.22%   |
| Unknown            | 3         | 0.22%   |
| 3840x2400          | 2         | 0.15%   |
| 3840x1080          | 2         | 0.15%   |
| 2160x1440          | 2         | 0.15%   |
| 1680x1050 (WSXGA+) | 2         | 0.15%   |
| 1280x720 (HD)      | 2         | 0.15%   |
| 640x480            | 1         | 0.07%   |
| 5760x2160          | 1         | 0.07%   |
| 3200x1800 (QHD+)   | 1         | 0.07%   |
| 2966x900           | 1         | 0.07%   |
| 2880x1920          | 1         | 0.07%   |
| 2736x1824          | 1         | 0.07%   |
| 2240x1400          | 1         | 0.07%   |
| 1920x550           | 1         | 0.07%   |
| 1920x1280          | 1         | 0.07%   |
| 1280x960           | 1         | 0.07%   |
| 1152x864           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 333       | 23.58%  |
| 14      | 318       | 22.52%  |
| 15      | 232       | 16.43%  |
| 18      | 90        | 6.37%   |
| 21      | 75        | 5.31%   |
| 23      | 67        | 4.75%   |
| 12      | 49        | 3.47%   |
| 11      | 36        | 2.55%   |
| 24      | 33        | 2.34%   |
| 19      | 33        | 2.34%   |
| Unknown | 28        | 1.98%   |
| 27      | 24        | 1.7%    |
| 17      | 16        | 1.13%   |
| 34      | 11        | 0.78%   |
| 40      | 9         | 0.64%   |
| 31      | 8         | 0.57%   |
| 16      | 8         | 0.57%   |
| 48      | 4         | 0.28%   |
| 20      | 4         | 0.28%   |
| 10      | 4         | 0.28%   |
| 7       | 4         | 0.28%   |
| 84      | 3         | 0.21%   |
| 67      | 3         | 0.21%   |
| 72      | 2         | 0.14%   |
| 60      | 2         | 0.14%   |
| 52      | 2         | 0.14%   |
| 37      | 2         | 0.14%   |
| 22      | 2         | 0.14%   |
| 65      | 1         | 0.07%   |
| 57      | 1         | 0.07%   |
| 54      | 1         | 0.07%   |
| 42      | 1         | 0.07%   |
| 39      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 35      | 1         | 0.07%   |
| 26      | 1         | 0.07%   |
| 25      | 1         | 0.07%   |
| 9       | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 798       | 57.08%  |
| 401-500     | 194       | 13.88%  |
| 201-300     | 167       | 11.95%  |
| 501-600     | 121       | 8.66%   |
| 351-400     | 30        | 2.15%   |
| Unknown     | 28        | 2%      |
| 701-800     | 16        | 1.14%   |
| 801-900     | 13        | 0.93%   |
| 601-700     | 11        | 0.79%   |
| 1001-1500   | 10        | 0.72%   |
| 1501-2000   | 5         | 0.36%   |
| 1-100       | 3         | 0.21%   |
| 101-200     | 1         | 0.07%   |
| 901-1000    | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1139      | 87.08%  |
| 16/10   | 101       | 7.72%   |
| Unknown | 26        | 1.99%   |
| 21/9    | 12        | 0.92%   |
| 5/4     | 8         | 0.61%   |
| 4/3     | 7         | 0.54%   |
| 3/2     | 7         | 0.54%   |
| 0.67    | 3         | 0.23%   |
| 0.45    | 3         | 0.23%   |
| 32/9    | 1         | 0.08%   |
| 0.56    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 582       | 41.28%  |
| 101-110        | 226       | 16.03%  |
| 201-250        | 150       | 10.64%  |
| 141-150        | 91        | 6.45%   |
| 71-80          | 64        | 4.54%   |
| 151-200        | 56        | 3.97%   |
| 61-70          | 48        | 3.4%    |
| 51-60          | 36        | 2.55%   |
| Unknown        | 28        | 1.99%   |
| 301-350        | 25        | 1.77%   |
| 351-500        | 20        | 1.42%   |
| More than 1000 | 19        | 1.35%   |
| 501-1000       | 14        | 0.99%   |
| 251-300        | 10        | 0.71%   |
| 121-130        | 10        | 0.71%   |
| 91-100         | 9         | 0.64%   |
| 111-120        | 8         | 0.57%   |
| 41-50          | 5         | 0.35%   |
| 131-140        | 5         | 0.35%   |
| 1-40           | 4         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 571       | 40.87%  |
| 121-160       | 374       | 26.77%  |
| 51-100        | 306       | 21.9%   |
| 161-240       | 77        | 5.51%   |
| Unknown       | 28        | 2%      |
| 1-50          | 21        | 1.5%    |
| More than 240 | 20        | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1227      | 85.51%  |
| 2     | 136       | 9.48%   |
| 0     | 69        | 4.81%   |
| 3     | 3         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 865       | 39.25%  |
| Intel                             | 504       | 22.87%  |
| Qualcomm Atheros                  | 373       | 16.92%  |
| Broadcom                          | 130       | 5.9%    |
| Ralink Technology                 | 48        | 2.18%   |
| MediaTek                          | 40        | 1.81%   |
| TP-Link                           | 37        | 1.68%   |
| Xiaomi                            | 31        | 1.41%   |
| Samsung Electronics               | 22        | 1%      |
| Qualcomm Atheros Communications   | 18        | 0.82%   |
| Broadcom Limited                  | 17        | 0.77%   |
| Ralink                            | 15        | 0.68%   |
| Marvell Technology Group          | 13        | 0.59%   |
| OPPO Electronics                  | 12        | 0.54%   |
| ASIX Electronics                  | 7         | 0.32%   |
| Qualcomm                          | 6         | 0.27%   |
| JMicron Technology                | 6         | 0.27%   |
| IBM                               | 6         | 0.27%   |
| Huawei Technologies               | 5         | 0.23%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.18%   |
| Sierra Wireless                   | 4         | 0.18%   |
| Nvidia                            | 4         | 0.18%   |
| Ericsson Business Mobile Networks | 4         | 0.18%   |
| D-Link System                     | 4         | 0.18%   |
| D-Link                            | 4         | 0.18%   |
| ICS Advent                        | 3         | 0.14%   |
| Attansic Technology               | 3         | 0.14%   |
| AboCom Systems                    | 3         | 0.14%   |
| Lenovo                            | 2         | 0.09%   |
| HMD Global                        | 2         | 0.09%   |
| Hewlett-Packard                   | 2         | 0.09%   |
| ASUSTek Computer                  | 2         | 0.09%   |
| vivo                              | 1         | 0.05%   |
| VIA Technologies                  | 1         | 0.05%   |
| QinHeng Electronics               | 1         | 0.05%   |
| Microchip Technology              | 1         | 0.05%   |
| HTC (High Tech Computer)          | 1         | 0.05%   |
| Foxconn / Hon Hai                 | 1         | 0.05%   |
| Fibocom                           | 1         | 0.05%   |
| Edimax Technology                 | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 553       | 21.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 164       | 6.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 89        | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 77        | 2.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 62        | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 47        | 1.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 43        | 1.66%   |
| Intel Wireless 8265 / 8275                                             | 40        | 1.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 36        | 1.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 35        | 1.36%   |
| Ralink MT7601U Wireless Adapter                                        | 33        | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 32        | 1.24%   |
| Intel Wireless 7265                                                    | 31        | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 30        | 1.16%   |
| Intel Wi-Fi 6 AX201                                                    | 26        | 1.01%   |
| Intel Wi-Fi 6 AX200                                                    | 26        | 1.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 26        | 1.01%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 25        | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 25        | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 24        | 0.93%   |
| Intel Wireless 7260                                                    | 23        | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 23        | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 22        | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 22        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 22        | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                          | 21        | 0.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 20        | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 20        | 0.77%   |
| Qualcomm Atheros AR9271 802.11n                                        | 18        | 0.7%    |
| Intel Wireless 8260                                                    | 18        | 0.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 17        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 15        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 15        | 0.58%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 15        | 0.58%   |
| Intel Wireless 3165                                                    | 15        | 0.58%   |
| Intel Ethernet Connection I218-LM                                      | 14        | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 14        | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 13        | 0.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 13        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 411       | 32.08%  |
| Qualcomm Atheros                  | 320       | 24.98%  |
| Realtek Semiconductor             | 290       | 22.64%  |
| Broadcom                          | 86        | 6.71%   |
| Ralink Technology                 | 48        | 3.75%   |
| TP-Link                           | 32        | 2.5%    |
| MediaTek                          | 31        | 2.42%   |
| Qualcomm Atheros Communications   | 18        | 1.41%   |
| Ralink                            | 15        | 1.17%   |
| Broadcom Limited                  | 13        | 1.01%   |
| Sierra Wireless                   | 4         | 0.31%   |
| D-Link                            | 4         | 0.31%   |
| AboCom Systems                    | 3         | 0.23%   |
| D-Link System                     | 2         | 0.16%   |
| Fibocom                           | 1         | 0.08%   |
| Ericsson Business Mobile Networks | 1         | 0.08%   |
| Edimax Technology                 | 1         | 0.08%   |
| ASUSTek Computer                  | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 89        | 6.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 77        | 5.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 62        | 4.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 43        | 3.33%   |
| Intel Wireless 8265 / 8275                                     | 40        | 3.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 36        | 2.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 35        | 2.71%   |
| Ralink MT7601U Wireless Adapter                                | 33        | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 32        | 2.48%   |
| Intel Wireless 7265                                            | 31        | 2.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 30        | 2.32%   |
| Intel Wi-Fi 6 AX201                                            | 26        | 2.01%   |
| Intel Wi-Fi 6 AX200                                            | 26        | 2.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 26        | 2.01%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 25        | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 25        | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 24        | 1.86%   |
| Intel Wireless 7260                                            | 23        | 1.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 23        | 1.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 22        | 1.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 22        | 1.7%    |
| Broadcom BCM43142 802.11b/g/n                                  | 21        | 1.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 20        | 1.55%   |
| Qualcomm Atheros AR9271 802.11n                                | 18        | 1.39%   |
| Intel Wireless 8260                                            | 18        | 1.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 17        | 1.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 1.16%   |
| Intel Wireless 3165                                            | 15        | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 14        | 1.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 13        | 1.01%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 13        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13        | 1.01%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 12        | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 12        | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 12        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 10        | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 10        | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 10        | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 8         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 749       | 59.07%  |
| Intel                            | 215       | 16.96%  |
| Qualcomm Atheros                 | 94        | 7.41%   |
| Broadcom                         | 55        | 4.34%   |
| Xiaomi                           | 31        | 2.44%   |
| Samsung Electronics              | 22        | 1.74%   |
| Marvell Technology Group         | 13        | 1.03%   |
| OPPO Electronics                 | 12        | 0.95%   |
| MediaTek                         | 10        | 0.79%   |
| ASIX Electronics                 | 7         | 0.55%   |
| Qualcomm                         | 6         | 0.47%   |
| JMicron Technology               | 6         | 0.47%   |
| IBM                              | 6         | 0.47%   |
| Broadcom Limited                 | 6         | 0.47%   |
| TP-Link                          | 5         | 0.39%   |
| Silicon Integrated Systems [SiS] | 4         | 0.32%   |
| Nvidia                           | 4         | 0.32%   |
| ICS Advent                       | 3         | 0.24%   |
| Attansic Technology              | 3         | 0.24%   |
| Lenovo                           | 2         | 0.16%   |
| Huawei Technologies              | 2         | 0.16%   |
| HMD Global                       | 2         | 0.16%   |
| Hewlett-Packard                  | 2         | 0.16%   |
| D-Link System                    | 2         | 0.16%   |
| vivo                             | 1         | 0.08%   |
| VIA Technologies                 | 1         | 0.08%   |
| QinHeng Electronics              | 1         | 0.08%   |
| Microchip Technology             | 1         | 0.08%   |
| HTC (High Tech Computer)         | 1         | 0.08%   |
| Foxconn / Hon Hai                | 1         | 0.08%   |
| ASUSTek Computer                 | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 553       | 43%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 164       | 12.75%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 47        | 3.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 22        | 1.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 20        | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 1.24%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 15        | 1.17%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 15        | 1.17%   |
| Intel Ethernet Connection I218-LM                                      | 14        | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                                  | 13        | 1.01%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 12        | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 10        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 9         | 0.7%    |
| Realtek RTL8125 2.5GbE Controller                                      | 9         | 0.7%    |
| Intel Ethernet Connection I217-LM                                      | 9         | 0.7%    |
| Intel Ethernet Connection I219-LM                                      | 8         | 0.62%   |
| Intel 82577LM Gigabit Network Connection                               | 8         | 0.62%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 7         | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 7         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 7         | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 7         | 0.54%   |
| MediaTek File-CD Gadget                                                | 7         | 0.54%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 0.54%   |
| Intel 82574L Gigabit Network Connection                                | 7         | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 6         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 6         | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.47%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 6         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 6         | 0.47%   |
| Intel Ethernet Connection (6) I219-LM                                  | 6         | 0.47%   |
| Intel 82579V Gigabit Network Connection                                | 6         | 0.47%   |
| Intel 82567LM Gigabit Network Connection                               | 6         | 0.47%   |
| IBM RNDIS/CDC ETHER                                                    | 6         | 0.47%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 0.47%   |
| Qualcomm Redmi 9T                                                      | 5         | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 5         | 0.39%   |
| Intel Ethernet Connection I217-V                                       | 5         | 0.39%   |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1216      | 51.03%  |
| Ethernet | 1161      | 48.72%  |
| Modem    | 6         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1027      | 74.1%   |
| Ethernet | 358       | 25.83%  |
| Modem    | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 839       | 59.38%  |
| 1     | 514       | 36.38%  |
| 0     | 31        | 2.19%   |
| 3     | 17        | 1.2%    |
| 4     | 10        | 0.71%   |
| 8     | 1         | 0.07%   |
| 6     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1316      | 92.42%  |
| Yes  | 108       | 7.58%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 330       | 35.68%  |
| Realtek Semiconductor           | 156       | 16.86%  |
| IMC Networks                    | 89        | 9.62%   |
| Qualcomm Atheros Communications | 85        | 9.19%   |
| Lite-On Technology              | 63        | 6.81%   |
| Cambridge Silicon Radio         | 50        | 5.41%   |
| Broadcom                        | 50        | 5.41%   |
| Foxconn / Hon Hai               | 34        | 3.68%   |
| Apple                           | 15        | 1.62%   |
| Toshiba                         | 14        | 1.51%   |
| Dell                            | 10        | 1.08%   |
| Hewlett-Packard                 | 6         | 0.65%   |
| Ralink                          | 5         | 0.54%   |
| Foxconn International           | 4         | 0.43%   |
| Realtek                         | 3         | 0.32%   |
| MediaTek                        | 3         | 0.32%   |
| ASUSTek Computer                | 3         | 0.32%   |
| Micro Star International        | 2         | 0.22%   |
| Marvell Semiconductor           | 1         | 0.11%   |
| Chicony Electronics             | 1         | 0.11%   |
| Alps Electric                   | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 126       | 13.62%  |
| Realtek Bluetooth Radio                             | 95        | 10.27%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 80        | 8.65%   |
| IMC Networks Bluetooth Device                       | 53        | 5.73%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 50        | 5.41%   |
| Intel AX201 Bluetooth                               | 49        | 5.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 42        | 4.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 39        | 4.22%   |
| Intel AX200 Bluetooth                               | 26        | 2.81%   |
| Lite-On Bluetooth Device                            | 24        | 2.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 17        | 1.84%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 1.84%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 1.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 1.51%   |
| IMC Networks Bluetooth Radio                        | 14        | 1.51%   |
| Realtek RTL8723B Bluetooth                          | 13        | 1.41%   |
| Intel Bluetooth Device                              | 12        | 1.3%    |
| Lite-On Wireless_Device                             | 11        | 1.19%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 1.19%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 1.08%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 9         | 0.97%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.97%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 9         | 0.97%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.86%   |
| Lite-On Atheros Bluetooth                           | 6         | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.65%   |
| IMC Networks Wireless_Device                        | 6         | 0.65%   |
| Apple Bluetooth Host Controller                     | 6         | 0.65%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.54%   |
| Intel AX210 Bluetooth                               | 5         | 0.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 0.54%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 5         | 0.54%   |
| Broadcom HP Portable SoftSailing                    | 5         | 0.54%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 5         | 0.54%   |
| Toshiba RT Bluetooth Radio                          | 4         | 0.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 0.43%   |
| Qualcomm Atheros Bluetooth                          | 4         | 0.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 0.43%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.43%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1004      | 61.18%  |
| AMD                                  | 398       | 24.25%  |
| Nvidia                               | 167       | 10.18%  |
| C-Media Electronics                  | 11        | 0.67%   |
| Generalplus Technology               | 9         | 0.55%   |
| JMTek                                | 6         | 0.37%   |
| Silicon Integrated Systems [SiS]     | 5         | 0.3%    |
| Samson Technologies                  | 4         | 0.24%   |
| Creative Labs                        | 4         | 0.24%   |
| Texas Instruments                    | 3         | 0.18%   |
| Logitech                             | 3         | 0.18%   |
| BR23                                 | 3         | 0.18%   |
| ASUSTek Computer                     | 3         | 0.18%   |
| Samsung Electronics                  | 2         | 0.12%   |
| Razer USA                            | 2         | 0.12%   |
| KTMicro                              | 2         | 0.12%   |
| Barco Display Systems                | 2         | 0.12%   |
| Weltrend Semiconductor               | 1         | 0.06%   |
| USB-MIC                              | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.06%   |
| STMicroelectronics                   | 1         | 0.06%   |
| SteelSeries ApS                      | 1         | 0.06%   |
| Sony                                 | 1         | 0.06%   |
| Solid State Logic                    | 1         | 0.06%   |
| SAVITECH                             | 1         | 0.06%   |
| Nordic Semiconductor ASA             | 1         | 0.06%   |
| Hewlett-Packard                      | 1         | 0.06%   |
| Creative Technology                  | 1         | 0.06%   |
| Cooler Master                        | 1         | 0.06%   |
| Conexant Systems                     | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 159       | 7.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 114       | 5.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 113       | 5.43%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 112       | 5.38%   |
| AMD FCH Azalia Controller                                                                         | 79        | 3.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 69        | 3.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 64        | 3.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 60        | 2.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 52        | 2.5%    |
| Intel 8 Series HD Audio Controller                                                                | 52        | 2.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 50        | 2.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 50        | 2.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 49        | 2.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 49        | 2.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 43        | 2.07%   |
| Intel Broadwell-U Audio Controller                                                                | 43        | 2.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 41        | 1.97%   |
| AMD High Definition Audio Controller                                                              | 41        | 1.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 39        | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 38        | 1.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 38        | 1.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 31        | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 30        | 1.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 29        | 1.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 24        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 22        | 1.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 21        | 1.01%   |
| Nvidia High Definition Audio Controller                                                           | 19        | 0.91%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 19        | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 0.82%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 17        | 0.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 0.77%   |
| AMD Wrestler HDMI Audio                                                                           | 16        | 0.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 0.67%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14        | 0.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 13        | 0.62%   |
| Intel 200 Series PCH HD Audio                                                                     | 13        | 0.62%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 13        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 276       | 27.27%  |
| SK hynix                                | 189       | 18.68%  |
| Micron Technology                       | 104       | 10.28%  |
| Kingston                                | 91        | 8.99%   |
| Unknown                                 | 87        | 8.6%    |
| Corsair                                 | 44        | 4.35%   |
| Team                                    | 42        | 4.15%   |
| V-GeN                                   | 30        | 2.96%   |
| Ramaxel Technology                      | 23        | 2.27%   |
| Elpida                                  | 20        | 1.98%   |
| Unknown                                 | 13        | 1.28%   |
| Nanya Technology                        | 12        | 1.19%   |
| A-DATA Technology                       | 11        | 1.09%   |
| Unknown (ABCD)                          | 10        | 0.99%   |
| G.Skill                                 | 8         | 0.79%   |
| Crucial                                 | 6         | 0.59%   |
| Transcend                               | 5         | 0.49%   |
| Apacer                                  | 4         | 0.4%    |
| Visipro                                 | 3         | 0.3%    |
| SHARETRONIC                             | 3         | 0.3%    |
| Patriot                                 | 3         | 0.3%    |
| Unknown (0x0DD5)                        | 2         | 0.2%    |
| Lexar                                   | 2         | 0.2%    |
| Kingmax                                 | 2         | 0.2%    |
| Hewlett-Packard                         | 2         | 0.2%    |
| ASint Technology                        | 2         | 0.2%    |
| A Force                                 | 2         | 0.2%    |
| Unknown (8AA1)                          | 1         | 0.1%    |
| Unknown (8A02)                          | 1         | 0.1%    |
| Unknown (0x0080)                        | 1         | 0.1%    |
| Super Talent                            | 1         | 0.1%    |
| Strontium                               | 1         | 0.1%    |
| Silicon Power Computer & Communications | 1         | 0.1%    |
| Silicon Power                           | 1         | 0.1%    |
| Qumo                                    | 1         | 0.1%    |
| HPE                                     | 1         | 0.1%    |
| GOODRAM                                 | 1         | 0.1%    |
| Goldkey                                 | 1         | 0.1%    |
| Foxline                                 | 1         | 0.1%    |
| ff                                      | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 20        | 1.83%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 15        | 1.37%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 14        | 1.28%   |
| Unknown                                                             | 13        | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 12        | 1.1%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 12        | 1.1%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 12        | 1.1%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 11        | 1.01%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 10        | 0.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 9         | 0.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 9         | 0.82%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s               | 9         | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 8         | 0.73%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 8         | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 8         | 0.73%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 8         | 0.73%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 8         | 0.73%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s               | 7         | 0.64%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s                | 7         | 0.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 7         | 0.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 7         | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 7         | 0.64%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 7         | 0.64%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 6         | 0.55%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 6         | 0.55%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 6         | 0.55%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 0.55%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 0.55%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 6         | 0.55%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s                 | 5         | 0.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 5         | 0.46%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 0.46%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 3200MT/s               | 5         | 0.46%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 5         | 0.46%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s                | 5         | 0.46%   |
| Kingston RAM 9905625-004.A03LF 4GB SODIMM DDR3 3200MT/s             | 5         | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 4         | 0.37%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s                | 4         | 0.37%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s                | 4         | 0.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 357       | 44.02%  |
| DDR3    | 325       | 40.07%  |
| LPDDR4  | 34        | 4.19%   |
| DDR2    | 30        | 3.7%    |
| SDRAM   | 21        | 2.59%   |
| Unknown | 15        | 1.85%   |
| LPDDR3  | 12        | 1.48%   |
| LPDDR5  | 9         | 1.11%   |
| DDR5    | 4         | 0.49%   |
| DRAM    | 2         | 0.25%   |
| DDR     | 2         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 586       | 72.35%  |
| DIMM         | 158       | 19.51%  |
| Row Of Chips | 59        | 7.28%   |
| Chip         | 5         | 0.62%   |
| Unknown      | 2         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 346       | 37.61%  |
| 8192  | 300       | 32.61%  |
| 2048  | 140       | 15.22%  |
| 16384 | 81        | 8.8%    |
| 32768 | 31        | 3.37%   |
| 1024  | 19        | 2.07%   |
| 512   | 2         | 0.22%   |
| 65536 | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 222       | 24.03%  |
| 3200    | 137       | 14.83%  |
| 2667    | 137       | 14.83%  |
| 2400    | 76        | 8.23%   |
| 1333    | 65        | 7.03%   |
| 2133    | 43        | 4.65%   |
| 1334    | 32        | 3.46%   |
| 1067    | 21        | 2.27%   |
| 3266    | 20        | 2.16%   |
| 800     | 20        | 2.16%   |
| Unknown | 18        | 1.95%   |
| 667     | 13        | 1.41%   |
| 4267    | 9         | 0.97%   |
| 4266    | 9         | 0.97%   |
| 1867    | 9         | 0.97%   |
| 1800    | 8         | 0.87%   |
| 8400    | 7         | 0.76%   |
| 6400    | 7         | 0.76%   |
| 3600    | 6         | 0.65%   |
| 4199    | 5         | 0.54%   |
| 3800    | 5         | 0.54%   |
| 3733    | 5         | 0.54%   |
| 1866    | 5         | 0.54%   |
| 1066    | 4         | 0.43%   |
| 533     | 4         | 0.43%   |
| 3400    | 3         | 0.32%   |
| 2666    | 3         | 0.32%   |
| 333     | 3         | 0.32%   |
| 5200    | 2         | 0.22%   |
| 3151    | 2         | 0.22%   |
| 2048    | 2         | 0.22%   |
| 50410   | 1         | 0.11%   |
| 7467    | 1         | 0.11%   |
| 5600    | 1         | 0.11%   |
| 5500    | 1         | 0.11%   |
| 4800    | 1         | 0.11%   |
| 4040    | 1         | 0.11%   |
| 3866    | 1         | 0.11%   |
| 3666    | 1         | 0.11%   |
| 3534    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 23        | 60.53%  |
| Hewlett-Packard    | 6         | 15.79%  |
| Canon              | 3         | 7.89%   |
| Brother Industries | 3         | 7.89%   |
| STMicroelectronics | 2         | 5.26%   |
| Fuji Xerox         | 1         | 2.63%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seiko Epson L120 Series                 | 6         | 15.79%  |
| Seiko Epson L360 Series                 | 5         | 13.16%  |
| Seiko Epson L310 Series                 | 3         | 7.89%   |
| Seiko Epson L3210 Series                | 2         | 5.26%   |
| Seiko Epson L3110 Series                | 2         | 5.26%   |
| Seiko Epson L300 Series                 | 2         | 5.26%   |
| Canon iP2700 series                     | 2         | 5.26%   |
| Brother DCP-T300                        | 2         | 5.26%   |
| STMicroelectronics USB Printing Support | 1         | 2.63%   |
| STMicroelectronics JRSVC Printer        | 1         | 2.63%   |
| Seiko Epson L405 Series                 | 1         | 2.63%   |
| Seiko Epson L355 Series                 | 1         | 2.63%   |
| Seiko Epson L1300 Series                | 1         | 2.63%   |
| HP LaserJet P1102                       | 1         | 2.63%   |
| HP LaserJet P1006                       | 1         | 2.63%   |
| HP LaserJet M101-M106                   | 1         | 2.63%   |
| HP Ink Tank 110 series                  | 1         | 2.63%   |
| HP DeskJet 5820 series                  | 1         | 2.63%   |
| HP DeskJet 2130 series                  | 1         | 2.63%   |
| Fuji Xerox DocuPrint M205 b             | 1         | 2.63%   |
| Canon CanoScan LiDE 300                 | 1         | 2.63%   |
| Brother DCP-T310                        | 1         | 2.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 50%     |
| Canon CanoScan 4400F   | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 261       | 26.77%  |
| IMC Networks                           | 134       | 13.74%  |
| Realtek Semiconductor                  | 83        | 8.51%   |
| Bison Electronics                      | 63        | 6.46%   |
| Quanta                                 | 51        | 5.23%   |
| Sunplus Innovation Technology          | 50        | 5.13%   |
| Syntek                                 | 48        | 4.92%   |
| Microdia                               | 44        | 4.51%   |
| Cheng Uei Precision Industry (Foxlink) | 44        | 4.51%   |
| Suyin                                  | 25        | 2.56%   |
| Alcor Micro                            | 24        | 2.46%   |
| Acer                                   | 21        | 2.15%   |
| Apple                                  | 16        | 1.64%   |
| Lite-On Technology                     | 13        | 1.33%   |
| Luxvisions Innotech Limited            | 11        | 1.13%   |
| Sonix Technology                       | 7         | 0.72%   |
| Silicon Motion                         | 7         | 0.72%   |
| Ricoh                                  | 6         | 0.62%   |
| Logitech                               | 6         | 0.62%   |
| Importek                               | 6         | 0.62%   |
| Primax Electronics                     | 4         | 0.41%   |
| Lenovo                                 | 4         | 0.41%   |
| Jieli Technology                       | 4         | 0.41%   |
| ANYKA                                  | 4         | 0.41%   |
| Generalplus Technology                 | 3         | 0.31%   |
| GEMBIRD                                | 3         | 0.31%   |
| Z-Star Microelectronics                | 2         | 0.21%   |
| SunplusIT                              | 2         | 0.21%   |
| Sunplus Technology                     | 2         | 0.21%   |
| Huawei Technologies                    | 2         | 0.21%   |
| Cubeternet                             | 2         | 0.21%   |
| ALi                                    | 2         | 0.21%   |
| 04004000_P040200_SN0002                | 2         | 0.21%   |
| Unknown                                | 2         | 0.21%   |
| webcamvendor                           | 1         | 0.1%    |
| WCM_USB                                | 1         | 0.1%    |
| Tripath Technology                     | 1         | 0.1%    |
| Razer USA                              | 1         | 0.1%    |
| Pixart Imaging                         | 1         | 0.1%    |
| OPPO Electronics                       | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 45        | 4.59%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 35        | 3.57%   |
| Chicony HD WebCam                                               | 33        | 3.37%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 31        | 3.16%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 31        | 3.16%   |
| Syntek Integrated Camera                                        | 30        | 3.06%   |
| IMC Networks Integrated Camera                                  | 23        | 2.35%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 17        | 1.73%   |
| Microdia Integrated_Webcam_HD                                   | 17        | 1.73%   |
| Chicony USB2.0 HD UVC WebCam                                    | 17        | 1.73%   |
| Bison Integrated Camera                                         | 17        | 1.73%   |
| Chicony HP TrueVision HD Camera                                 | 15        | 1.53%   |
| Realtek USB Camera                                              | 14        | 1.43%   |
| Bison Lenovo EasyCamera                                         | 13        | 1.33%   |
| Quanta HD User Facing                                           | 12        | 1.22%   |
| IMC Networks Lenovo EasyCamera                                  | 12        | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 12        | 1.22%   |
| Realtek Integrated_Webcam_HD                                    | 11        | 1.12%   |
| IMC Networks EasyCamera                                         | 11        | 1.12%   |
| Sunplus Asus Webcam                                             | 10        | 1.02%   |
| Chicony HP TrueVision HD                                        | 10        | 1.02%   |
| Chicony EasyCamera                                              | 10        | 1.02%   |
| Realtek USB2.0 HD UVC WebCam                                    | 9         | 0.92%   |
| Microdia Integrated Webcam                                      | 9         | 0.92%   |
| Chicony Lenovo EasyCamera                                       | 9         | 0.92%   |
| Syntek Lenovo EasyCamera                                        | 8         | 0.82%   |
| Syntek EasyCamera                                               | 8         | 0.82%   |
| Sunplus Integrated_Webcam_HD                                    | 8         | 0.82%   |
| Chicony TOSHIBA Web Camera - HD                                 | 8         | 0.82%   |
| Alcor Micro USB 2.0 Camera                                      | 8         | 0.82%   |
| Suyin 1.3M HD WebCam                                            | 7         | 0.71%   |
| Quanta VGA WebCam                                               | 7         | 0.71%   |
| Quanta HP TrueVision HD Camera                                  | 7         | 0.71%   |
| Chicony HD User Facing                                          | 7         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 7         | 0.71%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                              | 7         | 0.71%   |
| Alcor Micro Asus Integrated Webcam                              | 7         | 0.71%   |
| Sonix USB2.0 HD UVC WebCam                                      | 6         | 0.61%   |
| Quanta HD Webcam                                                | 6         | 0.61%   |
| Lite-On Integrated Camera                                       | 6         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 45        | 28.48%  |
| Synaptics                  | 35        | 22.15%  |
| Elan Microelectronics      | 28        | 17.72%  |
| Shenzhen Goodix Technology | 19        | 12.03%  |
| LighTuning Technology      | 12        | 7.59%   |
| AuthenTec                  | 9         | 5.7%    |
| Upek                       | 5         | 3.16%   |
| STMicroelectronics         | 4         | 2.53%   |
| DigitalPersona             | 1         | 0.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                          | 14        | 8.86%   |
| Elan ELAN:Fingerprint                                     | 13        | 8.23%   |
| Shenzhen Goodix Fingerprint Reader                        | 12        | 7.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 11        | 6.96%   |
| Validity Sensors VFS495 Fingerprint Reader                | 9         | 5.7%    |
| Validity Sensors VFS 5011 fingerprint sensor              | 9         | 5.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 9         | 5.7%    |
| Shenzhen Goodix  FingerPrint Device                       | 7         | 4.43%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 6         | 3.8%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 6         | 3.8%    |
| Validity Sensors Swipe Fingerprint Sensor                 | 5         | 3.16%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 5         | 3.16%   |
| Synaptics WBDI                                            | 5         | 3.16%   |
| Validity Sensors VFS491                                   | 4         | 2.53%   |
| Validity Sensors VFS Fingerprint sensor                   | 4         | 2.53%   |
| Synaptics UWP WBDI                                        | 4         | 2.53%   |
| Synaptics  WBDI                                           | 4         | 2.53%   |
| STMicroelectronics Fingerprint Reader                     | 4         | 2.53%   |
| AuthenTec AES1600                                         | 4         | 2.53%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 3         | 1.9%    |
| Validity Sensors VFS471 Fingerprint Reader                | 3         | 1.9%    |
| Synaptics WBDI Fingerprint Reader USB 086                 | 2         | 1.27%   |
| Synaptics Fingerprint reader [HP G6]                      | 2         | 1.27%   |
| AuthenTec Fingerprint Sensor                              | 2         | 1.27%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 2         | 1.27%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 0.63%   |
| Validity Sensors Synaptics WBDI                           | 1         | 0.63%   |
| Synaptics WBDI Fingerprint Reader USB 102                 | 1         | 0.63%   |
| Synaptics UWP WBDI Device                                 | 1         | 0.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 0.63%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 0.63%   |
| Elan fingerprint sensor [FeinTech FPS00200]               | 1         | 0.63%   |
| DigitalPersona Fingerprint Reader                         | 1         | 0.63%   |
| AuthenTec AES2810                                         | 1         | 0.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 21        | 53.85%  |
| Alcor Micro | 7         | 17.95%  |
| O2 Micro    | 5         | 12.82%  |
| Upek        | 4         | 10.26%  |
| Lenovo      | 2         | 5.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 12        | 30.77%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 17.95%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 12.82%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 12.82%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 10.26%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.13%   |
| Broadcom 5880                                                                | 2         | 5.13%   |
| Broadcom 58200                                                               | 2         | 5.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1039      | 72.35%  |
| 1     | 314       | 21.87%  |
| 2     | 67        | 4.67%   |
| 3     | 8         | 0.56%   |
| 4     | 6         | 0.42%   |
| 6     | 2         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 155       | 32.63%  |
| Graphics card            | 107       | 22.53%  |
| Net/wireless             | 58        | 12.21%  |
| Chipcard                 | 35        | 7.37%   |
| Multimedia controller    | 29        | 6.11%   |
| Communication controller | 24        | 5.05%   |
| Bluetooth                | 19        | 4%      |
| Unassigned class         | 11        | 2.32%   |
| Net/ethernet             | 10        | 2.11%   |
| Camera                   | 9         | 1.89%   |
| Storage                  | 4         | 0.84%   |
| Sound                    | 3         | 0.63%   |
| Flash memory             | 3         | 0.63%   |
| Storage/ide              | 2         | 0.42%   |
| Card reader              | 2         | 0.42%   |
| Wireless                 | 1         | 0.21%   |
| Video                    | 1         | 0.21%   |
| Network                  | 1         | 0.21%   |
| Modem                    | 1         | 0.21%   |

