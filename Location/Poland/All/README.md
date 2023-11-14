Linux in Poland - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Poland/Desktop/README.md) and [notebooks](/Location/Poland/Notebook/README.md).

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

Total: 8377

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [5b992d974a](https://linux-hardware.org/?probe=5b992d974a) | Nov 06, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [4d3a7373ae](https://linux-hardware.org/?probe=4d3a7373ae) | Nov 06, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [1da691596b](https://linux-hardware.org/?probe=1da691596b) | Nov 06, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d385d4714c](https://linux-hardware.org/?probe=d385d4714c) | Nov 06, 2023 |
| MSI           | B560M PRO-E                 | Desktop     | [89a24ae9fa](https://linux-hardware.org/?probe=89a24ae9fa) | Nov 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ff44a3299b](https://linux-hardware.org/?probe=ff44a3299b) | Nov 06, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [d40cc6e0a4](https://linux-hardware.org/?probe=d40cc6e0a4) | Nov 05, 2023 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | Notebook    | [e25bb48957](https://linux-hardware.org/?probe=e25bb48957) | Nov 05, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [39e8a692ae](https://linux-hardware.org/?probe=39e8a692ae) | Nov 05, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [b3669f73a8](https://linux-hardware.org/?probe=b3669f73a8) | Nov 05, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [f0399efc08](https://linux-hardware.org/?probe=f0399efc08) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [fd9594de89](https://linux-hardware.org/?probe=fd9594de89) | Nov 05, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b5b47ea33a](https://linux-hardware.org/?probe=b5b47ea33a) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [a5a8cf5c09](https://linux-hardware.org/?probe=a5a8cf5c09) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [74099b3a6e](https://linux-hardware.org/?probe=74099b3a6e) | Nov 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [2cbd472a6e](https://linux-hardware.org/?probe=2cbd472a6e) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [bdad71bf99](https://linux-hardware.org/?probe=bdad71bf99) | Nov 05, 2023 |
| MSI           | B560M PRO-E                 | Desktop     | [1488a8a70f](https://linux-hardware.org/?probe=1488a8a70f) | Nov 05, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [bdd24f60d2](https://linux-hardware.org/?probe=bdd24f60d2) | Nov 05, 2023 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [534fcded19](https://linux-hardware.org/?probe=534fcded19) | Nov 05, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [29fc753f1e](https://linux-hardware.org/?probe=29fc753f1e) | Nov 04, 2023 |
| Lenovo        | ThinkPad T460 20FMS3YT01    | Notebook    | [89b8df73c1](https://linux-hardware.org/?probe=89b8df73c1) | Nov 04, 2023 |
| HP            | 21D0                        | Desktop     | [160964fbab](https://linux-hardware.org/?probe=160964fbab) | Nov 04, 2023 |
| HP            | 89B5 A                      | Desktop     | [e31ecc3904](https://linux-hardware.org/?probe=e31ecc3904) | Nov 04, 2023 |
| Dell          | Inspiron 16 5620            | Notebook    | [04d425d450](https://linux-hardware.org/?probe=04d425d450) | Nov 04, 2023 |
| Lenovo        | 80SY                        | Notebook    | [7c7a6ba82f](https://linux-hardware.org/?probe=7c7a6ba82f) | Nov 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [9999b9fa3d](https://linux-hardware.org/?probe=9999b9fa3d) | Nov 04, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [a6ce21c9de](https://linux-hardware.org/?probe=a6ce21c9de) | Nov 04, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [2d4845b6b9](https://linux-hardware.org/?probe=2d4845b6b9) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [db71fb65bf](https://linux-hardware.org/?probe=db71fb65bf) | Nov 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [43ccf36bf0](https://linux-hardware.org/?probe=43ccf36bf0) | Nov 03, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [4ccd2ef567](https://linux-hardware.org/?probe=4ccd2ef567) | Nov 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0e493c7b85](https://linux-hardware.org/?probe=0e493c7b85) | Nov 03, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [3a0023b4ba](https://linux-hardware.org/?probe=3a0023b4ba) | Nov 03, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [3ddccb994b](https://linux-hardware.org/?probe=3ddccb994b) | Nov 03, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [d48f7514df](https://linux-hardware.org/?probe=d48f7514df) | Nov 02, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [027a0a96da](https://linux-hardware.org/?probe=027a0a96da) | Nov 02, 2023 |
| Dell          | Latitude E6420              | Notebook    | [cdef3b5f1c](https://linux-hardware.org/?probe=cdef3b5f1c) | Nov 02, 2023 |
| Dell          | 0CNCJW A08                  | Server      | [c166457131](https://linux-hardware.org/?probe=c166457131) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [0c8b2cd660](https://linux-hardware.org/?probe=0c8b2cd660) | Nov 01, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [45d3b00840](https://linux-hardware.org/?probe=45d3b00840) | Nov 01, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [a9ed160c1c](https://linux-hardware.org/?probe=a9ed160c1c) | Nov 01, 2023 |
| ASUSTek       | Z97-AR                      | Desktop     | [39741158bc](https://linux-hardware.org/?probe=39741158bc) | Nov 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [7dd972fb0d](https://linux-hardware.org/?probe=7dd972fb0d) | Nov 01, 2023 |
| HP            | Pavilion g7                 | Notebook    | [157c592b3a](https://linux-hardware.org/?probe=157c592b3a) | Nov 01, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [6d00cda16c](https://linux-hardware.org/?probe=6d00cda16c) | Nov 01, 2023 |
| ZOTAC         | ZBOX-MI623/MI643 Rev.00     | Mini pc     | [4b769dbcca](https://linux-hardware.org/?probe=4b769dbcca) | Oct 31, 2023 |
| Dell          | Latitude 3190               | Notebook    | [dc68dc55c9](https://linux-hardware.org/?probe=dc68dc55c9) | Oct 31, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [1323e3ad04](https://linux-hardware.org/?probe=1323e3ad04) | Oct 31, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [00ffbda72d](https://linux-hardware.org/?probe=00ffbda72d) | Oct 31, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ff0dfe1642](https://linux-hardware.org/?probe=ff0dfe1642) | Oct 30, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [fca3ef2e73](https://linux-hardware.org/?probe=fca3ef2e73) | Oct 30, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [12e8c83970](https://linux-hardware.org/?probe=12e8c83970) | Oct 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fe7dbb2385](https://linux-hardware.org/?probe=fe7dbb2385) | Oct 29, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [eeddd1e3e1](https://linux-hardware.org/?probe=eeddd1e3e1) | Oct 29, 2023 |
| Dell          | Precision M6600             | Notebook    | [30e8d1522d](https://linux-hardware.org/?probe=30e8d1522d) | Oct 29, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [09d76f025a](https://linux-hardware.org/?probe=09d76f025a) | Oct 29, 2023 |
| OrangePi      | Zero3                       | Soc         | [6d3ecf003f](https://linux-hardware.org/?probe=6d3ecf003f) | Oct 29, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [101c8c676c](https://linux-hardware.org/?probe=101c8c676c) | Oct 29, 2023 |
| Shenzhen M... | TH80                        | Desktop     | [22dea9593a](https://linux-hardware.org/?probe=22dea9593a) | Oct 28, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [f78fcbc612](https://linux-hardware.org/?probe=f78fcbc612) | Oct 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bbba3e21c7](https://linux-hardware.org/?probe=bbba3e21c7) | Oct 27, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [3cc39678ff](https://linux-hardware.org/?probe=3cc39678ff) | Oct 27, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [e76ead66bc](https://linux-hardware.org/?probe=e76ead66bc) | Oct 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [15488b723a](https://linux-hardware.org/?probe=15488b723a) | Oct 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [54aa16ef1e](https://linux-hardware.org/?probe=54aa16ef1e) | Oct 27, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [0a0a08dd5f](https://linux-hardware.org/?probe=0a0a08dd5f) | Oct 26, 2023 |
| MSI           | MS-1688                     | Notebook    | [c3689c0452](https://linux-hardware.org/?probe=c3689c0452) | Oct 26, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [7f10f1b379](https://linux-hardware.org/?probe=7f10f1b379) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [700ceddf43](https://linux-hardware.org/?probe=700ceddf43) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [f43adee740](https://linux-hardware.org/?probe=f43adee740) | Oct 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [e3c1de1472](https://linux-hardware.org/?probe=e3c1de1472) | Oct 26, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [f1bcad7519](https://linux-hardware.org/?probe=f1bcad7519) | Oct 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [38a8824fe8](https://linux-hardware.org/?probe=38a8824fe8) | Oct 25, 2023 |
| HP            | Compaq 610                  | Notebook    | [f449560c8a](https://linux-hardware.org/?probe=f449560c8a) | Oct 25, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [dab53e45c9](https://linux-hardware.org/?probe=dab53e45c9) | Oct 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [6c88fcef70](https://linux-hardware.org/?probe=6c88fcef70) | Oct 25, 2023 |
| ASRock        | Z370 Killer SLI             | Desktop     | [b01d80e583](https://linux-hardware.org/?probe=b01d80e583) | Oct 24, 2023 |
| Gigabyte      | 965P-DS3                    | Desktop     | [b33d6b8a3c](https://linux-hardware.org/?probe=b33d6b8a3c) | Oct 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3eee01cd16](https://linux-hardware.org/?probe=3eee01cd16) | Oct 24, 2023 |
| Notebook      | P7xxDM(-G)                  | Notebook    | [bb211b2fb4](https://linux-hardware.org/?probe=bb211b2fb4) | Oct 24, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | Desktop     | [67564f88a0](https://linux-hardware.org/?probe=67564f88a0) | Oct 24, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [06247cab2e](https://linux-hardware.org/?probe=06247cab2e) | Oct 24, 2023 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [7be979fc66](https://linux-hardware.org/?probe=7be979fc66) | Oct 23, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [6f72e3839d](https://linux-hardware.org/?probe=6f72e3839d) | Oct 23, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [def0406ec0](https://linux-hardware.org/?probe=def0406ec0) | Oct 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8da5e9e836](https://linux-hardware.org/?probe=8da5e9e836) | Oct 23, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [047f359430](https://linux-hardware.org/?probe=047f359430) | Oct 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [6ef12aa776](https://linux-hardware.org/?probe=6ef12aa776) | Oct 23, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | Notebook    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [9538ff99bf](https://linux-hardware.org/?probe=9538ff99bf) | Oct 22, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [9fcaeda183](https://linux-hardware.org/?probe=9fcaeda183) | Oct 22, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [66d1164d86](https://linux-hardware.org/?probe=66d1164d86) | Oct 21, 2023 |
| Dell          | Precision 5520              | Notebook    | [79b5c73851](https://linux-hardware.org/?probe=79b5c73851) | Oct 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [dca6ad28b3](https://linux-hardware.org/?probe=dca6ad28b3) | Oct 21, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [d6bd0eda6d](https://linux-hardware.org/?probe=d6bd0eda6d) | Oct 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [83811b2a84](https://linux-hardware.org/?probe=83811b2a84) | Oct 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [1ff62f5fd7](https://linux-hardware.org/?probe=1ff62f5fd7) | Oct 21, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e8d5f9186c](https://linux-hardware.org/?probe=e8d5f9186c) | Oct 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [2ca3451a04](https://linux-hardware.org/?probe=2ca3451a04) | Oct 20, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [7deca235e3](https://linux-hardware.org/?probe=7deca235e3) | Oct 20, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [65f3d76afa](https://linux-hardware.org/?probe=65f3d76afa) | Oct 19, 2023 |
| Dell          | Latitude 5440               | Notebook    | [e3760f51a8](https://linux-hardware.org/?probe=e3760f51a8) | Oct 19, 2023 |
| ASRock        | A88M-G                      | Desktop     | [05d17c88b7](https://linux-hardware.org/?probe=05d17c88b7) | Oct 18, 2023 |
| Dell          | Latitude 5440               | Notebook    | [257850f5d8](https://linux-hardware.org/?probe=257850f5d8) | Oct 18, 2023 |
| Dell          | Latitude 5440               | Notebook    | [2097e4ed5e](https://linux-hardware.org/?probe=2097e4ed5e) | Oct 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [e1751f1726](https://linux-hardware.org/?probe=e1751f1726) | Oct 17, 2023 |
| Dell          | Latitude E6420              | Notebook    | [f703c6bd74](https://linux-hardware.org/?probe=f703c6bd74) | Oct 17, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [a4661384e1](https://linux-hardware.org/?probe=a4661384e1) | Oct 17, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [9eb823dcdd](https://linux-hardware.org/?probe=9eb823dcdd) | Oct 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7b5cf8abfc](https://linux-hardware.org/?probe=7b5cf8abfc) | Oct 17, 2023 |
| Dell          | Latitude 3190               | Notebook    | [6524dff50f](https://linux-hardware.org/?probe=6524dff50f) | Oct 17, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [cc5a77d2c3](https://linux-hardware.org/?probe=cc5a77d2c3) | Oct 16, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [e8dd286f6d](https://linux-hardware.org/?probe=e8dd286f6d) | Oct 16, 2023 |
| HP            | ProBook 6560b               | Notebook    | [3567f55849](https://linux-hardware.org/?probe=3567f55849) | Oct 15, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [04afaee575](https://linux-hardware.org/?probe=04afaee575) | Oct 15, 2023 |
| HP            | 1589                        | Desktop     | [88e5bbcc5a](https://linux-hardware.org/?probe=88e5bbcc5a) | Oct 15, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [7d2501217c](https://linux-hardware.org/?probe=7d2501217c) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [dfee331121](https://linux-hardware.org/?probe=dfee331121) | Oct 15, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [b09d2e33fd](https://linux-hardware.org/?probe=b09d2e33fd) | Oct 15, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [af4857609e](https://linux-hardware.org/?probe=af4857609e) | Oct 15, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [38155dfb23](https://linux-hardware.org/?probe=38155dfb23) | Oct 15, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [475107b82f](https://linux-hardware.org/?probe=475107b82f) | Oct 15, 2023 |
| ACTION        | M5A78L-M lX V2              | Desktop     | [fe141a8a31](https://linux-hardware.org/?probe=fe141a8a31) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [fd52faa27e](https://linux-hardware.org/?probe=fd52faa27e) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [39d3b3133e](https://linux-hardware.org/?probe=39d3b3133e) | Oct 14, 2023 |
| HP            | ProBook 6560b               | Notebook    | [49ffe8b6c5](https://linux-hardware.org/?probe=49ffe8b6c5) | Oct 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [d68359ee50](https://linux-hardware.org/?probe=d68359ee50) | Oct 14, 2023 |
| HP            | EliteBook 830 13 inch G1... | Notebook    | [e9ced529e2](https://linux-hardware.org/?probe=e9ced529e2) | Oct 14, 2023 |
| Lenovo        | ThinkPad T430u 3352A83      | Notebook    | [c5a829d842](https://linux-hardware.org/?probe=c5a829d842) | Oct 14, 2023 |
| Lenovo        | ThinkPad T400 64757D7       | Notebook    | [b374e214af](https://linux-hardware.org/?probe=b374e214af) | Oct 13, 2023 |
| HPE           | ProLiant MicroServer Gen... | Server      | [62f56cc610](https://linux-hardware.org/?probe=62f56cc610) | Oct 13, 2023 |
| MSI           | GE72 6QF                    | Notebook    | [94f1c85d10](https://linux-hardware.org/?probe=94f1c85d10) | Oct 13, 2023 |
| HP            | Grunt                       | Notebook    | [af80cd9bd6](https://linux-hardware.org/?probe=af80cd9bd6) | Oct 13, 2023 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | Desktop     | [0400bae582](https://linux-hardware.org/?probe=0400bae582) | Oct 12, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [32ffcc827b](https://linux-hardware.org/?probe=32ffcc827b) | Oct 12, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [c3992a85f0](https://linux-hardware.org/?probe=c3992a85f0) | Oct 12, 2023 |
| ASUSTek       | X510UQ                      | Notebook    | [0494369566](https://linux-hardware.org/?probe=0494369566) | Oct 12, 2023 |
| Lenovo        | IdeaPad P500 20210          | Notebook    | [ba316cb723](https://linux-hardware.org/?probe=ba316cb723) | Oct 12, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [02414ff1af](https://linux-hardware.org/?probe=02414ff1af) | Oct 11, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [c83831e304](https://linux-hardware.org/?probe=c83831e304) | Oct 11, 2023 |
| MSI           | GL75 9SE                    | Notebook    | [bffc7bdfe6](https://linux-hardware.org/?probe=bffc7bdfe6) | Oct 11, 2023 |
| Dell          | Latitude 5511               | Notebook    | [164cc57420](https://linux-hardware.org/?probe=164cc57420) | Oct 10, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9827df8ea8](https://linux-hardware.org/?probe=9827df8ea8) | Oct 10, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [04fbcfc11b](https://linux-hardware.org/?probe=04fbcfc11b) | Oct 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [078d4619a6](https://linux-hardware.org/?probe=078d4619a6) | Oct 09, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [df4f5f4e21](https://linux-hardware.org/?probe=df4f5f4e21) | Oct 09, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [d4efaf21cb](https://linux-hardware.org/?probe=d4efaf21cb) | Oct 08, 2023 |
| Google        | Sasuke                      | Notebook    | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| HP            | EliteBook 745 G4            | Notebook    | [8a9290f8a1](https://linux-hardware.org/?probe=8a9290f8a1) | Oct 08, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [889b36122b](https://linux-hardware.org/?probe=889b36122b) | Oct 08, 2023 |
| Google        | Lindar                      | Notebook    | [75852e1ad7](https://linux-hardware.org/?probe=75852e1ad7) | Oct 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3cfe6c7d0c](https://linux-hardware.org/?probe=3cfe6c7d0c) | Oct 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | Notebook    | [c0a093d7d2](https://linux-hardware.org/?probe=c0a093d7d2) | Oct 08, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [a95183052c](https://linux-hardware.org/?probe=a95183052c) | Oct 08, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [3854022982](https://linux-hardware.org/?probe=3854022982) | Oct 08, 2023 |
| HP            | 83E8                        | Desktop     | [c1028de72b](https://linux-hardware.org/?probe=c1028de72b) | Oct 07, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [9d6684c4a9](https://linux-hardware.org/?probe=9d6684c4a9) | Oct 07, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [372a2d0189](https://linux-hardware.org/?probe=372a2d0189) | Oct 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [0bf2deeb16](https://linux-hardware.org/?probe=0bf2deeb16) | Oct 07, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [61fef3256c](https://linux-hardware.org/?probe=61fef3256c) | Oct 07, 2023 |
| MSI           | MS-7235                     | Desktop     | [afb00bf553](https://linux-hardware.org/?probe=afb00bf553) | Oct 07, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [665a7ff2eb](https://linux-hardware.org/?probe=665a7ff2eb) | Oct 06, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [3ce37336af](https://linux-hardware.org/?probe=3ce37336af) | Oct 06, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [355bc3fdfc](https://linux-hardware.org/?probe=355bc3fdfc) | Oct 06, 2023 |
| Dell          | Latitude 5310 2-in-1        | Convertible | [a88c9fdbb6](https://linux-hardware.org/?probe=a88c9fdbb6) | Oct 06, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [c07c01c9e6](https://linux-hardware.org/?probe=c07c01c9e6) | Oct 06, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [fbd07d95c2](https://linux-hardware.org/?probe=fbd07d95c2) | Oct 06, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [21ec0f4129](https://linux-hardware.org/?probe=21ec0f4129) | Oct 06, 2023 |
| Intel         | X99                         | Desktop     | [9bc14ff597](https://linux-hardware.org/?probe=9bc14ff597) | Oct 06, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6c5a7d30f3](https://linux-hardware.org/?probe=6c5a7d30f3) | Oct 06, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [f496e4dfff](https://linux-hardware.org/?probe=f496e4dfff) | Oct 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3b01422b2a](https://linux-hardware.org/?probe=3b01422b2a) | Oct 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [6e8b2e49f0](https://linux-hardware.org/?probe=6e8b2e49f0) | Oct 05, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [7ad16296eb](https://linux-hardware.org/?probe=7ad16296eb) | Oct 05, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [5529ffcf1b](https://linux-hardware.org/?probe=5529ffcf1b) | Oct 05, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [94ac6e4439](https://linux-hardware.org/?probe=94ac6e4439) | Oct 04, 2023 |
| ASRock        | P4i945GC                    | Desktop     | [9e7c1b2d58](https://linux-hardware.org/?probe=9e7c1b2d58) | Oct 04, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [18675da607](https://linux-hardware.org/?probe=18675da607) | Oct 04, 2023 |
| HP            | 1589                        | Desktop     | [75f8ba109d](https://linux-hardware.org/?probe=75f8ba109d) | Oct 04, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [8a684c7512](https://linux-hardware.org/?probe=8a684c7512) | Oct 04, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [e7b2bada83](https://linux-hardware.org/?probe=e7b2bada83) | Oct 04, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [57b66fc6eb](https://linux-hardware.org/?probe=57b66fc6eb) | Oct 04, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [e31f443ff9](https://linux-hardware.org/?probe=e31f443ff9) | Oct 04, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [4161bb4b7f](https://linux-hardware.org/?probe=4161bb4b7f) | Oct 04, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [27d781a357](https://linux-hardware.org/?probe=27d781a357) | Oct 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c40f80d33a](https://linux-hardware.org/?probe=c40f80d33a) | Oct 03, 2023 |
| Dell          | Latitude 3190               | Notebook    | [21aac15234](https://linux-hardware.org/?probe=21aac15234) | Oct 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [001368f3a9](https://linux-hardware.org/?probe=001368f3a9) | Oct 03, 2023 |
| Dell          | 0NGT4D A01                  | Mini pc     | [457dfea13d](https://linux-hardware.org/?probe=457dfea13d) | Oct 03, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [880b4780ee](https://linux-hardware.org/?probe=880b4780ee) | Oct 03, 2023 |
| Lenovo        | ThinkPad X390 20Q1S5K400    | Notebook    | [4d9d1bf62a](https://linux-hardware.org/?probe=4d9d1bf62a) | Oct 02, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [09b97f9681](https://linux-hardware.org/?probe=09b97f9681) | Oct 02, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [ea10bf8eab](https://linux-hardware.org/?probe=ea10bf8eab) | Oct 02, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [43062f3c9a](https://linux-hardware.org/?probe=43062f3c9a) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b8068a8e68](https://linux-hardware.org/?probe=b8068a8e68) | Oct 02, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [c095e62997](https://linux-hardware.org/?probe=c095e62997) | Oct 02, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [b7463e19f8](https://linux-hardware.org/?probe=b7463e19f8) | Oct 02, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cbd8df2f8a](https://linux-hardware.org/?probe=cbd8df2f8a) | Oct 02, 2023 |
| Intel         | NUC10i5FNB K61361-306       | Mini pc     | [f612ea4b42](https://linux-hardware.org/?probe=f612ea4b42) | Oct 02, 2023 |
| HP            | ProBook 6560b               | Notebook    | [ea59e8557f](https://linux-hardware.org/?probe=ea59e8557f) | Oct 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [f52bb9587d](https://linux-hardware.org/?probe=f52bb9587d) | Oct 01, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [06371cc0f7](https://linux-hardware.org/?probe=06371cc0f7) | Oct 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [34b8e1853b](https://linux-hardware.org/?probe=34b8e1853b) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [f9be6afb3a](https://linux-hardware.org/?probe=f9be6afb3a) | Oct 01, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [6faa4fd636](https://linux-hardware.org/?probe=6faa4fd636) | Oct 01, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [61a08e5e89](https://linux-hardware.org/?probe=61a08e5e89) | Oct 01, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0a11dba9ac](https://linux-hardware.org/?probe=0a11dba9ac) | Sep 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [48ff113276](https://linux-hardware.org/?probe=48ff113276) | Sep 30, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [d180995f93](https://linux-hardware.org/?probe=d180995f93) | Sep 30, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [63c99972d1](https://linux-hardware.org/?probe=63c99972d1) | Sep 30, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [b223d9b4f5](https://linux-hardware.org/?probe=b223d9b4f5) | Sep 30, 2023 |
| Dell          | Latitude 5430               | Notebook    | [eee2a34ff5](https://linux-hardware.org/?probe=eee2a34ff5) | Sep 30, 2023 |
| HP            | ProBook 6560b               | Notebook    | [904f0eb2cb](https://linux-hardware.org/?probe=904f0eb2cb) | Sep 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a0e4942d9f](https://linux-hardware.org/?probe=a0e4942d9f) | Sep 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [702d68e226](https://linux-hardware.org/?probe=702d68e226) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3bec9011bd](https://linux-hardware.org/?probe=3bec9011bd) | Sep 30, 2023 |
| HP            | Notebook                    | Notebook    | [193ec8deb3](https://linux-hardware.org/?probe=193ec8deb3) | Sep 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8e039e23f3](https://linux-hardware.org/?probe=8e039e23f3) | Sep 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [6e7e482b2d](https://linux-hardware.org/?probe=6e7e482b2d) | Sep 29, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [e1f22fdce4](https://linux-hardware.org/?probe=e1f22fdce4) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [cd9628c344](https://linux-hardware.org/?probe=cd9628c344) | Sep 29, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [b734ec49e2](https://linux-hardware.org/?probe=b734ec49e2) | Sep 29, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [4befa6db63](https://linux-hardware.org/?probe=4befa6db63) | Sep 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [0e4e90fac1](https://linux-hardware.org/?probe=0e4e90fac1) | Sep 29, 2023 |
| Lenovo        | IdeaPad Y530                | Notebook    | [83a6d1b19b](https://linux-hardware.org/?probe=83a6d1b19b) | Sep 28, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| HP            | 620                         | Notebook    | [1bdfd56638](https://linux-hardware.org/?probe=1bdfd56638) | Sep 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4ef9eaaaba](https://linux-hardware.org/?probe=4ef9eaaaba) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [5646b6da22](https://linux-hardware.org/?probe=5646b6da22) | Sep 27, 2023 |
| HP            | 1589                        | Desktop     | [1063a6e665](https://linux-hardware.org/?probe=1063a6e665) | Sep 27, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [8e70938939](https://linux-hardware.org/?probe=8e70938939) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [4f1f07158b](https://linux-hardware.org/?probe=4f1f07158b) | Sep 26, 2023 |
| Google        | Blorb                       | Notebook    | [efa4ad9e2c](https://linux-hardware.org/?probe=efa4ad9e2c) | Sep 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [09a71cddc4](https://linux-hardware.org/?probe=09a71cddc4) | Sep 26, 2023 |
| Lenovo        | ThinkPad T590 20N5S31U02    | Notebook    | [d4137582b5](https://linux-hardware.org/?probe=d4137582b5) | Sep 26, 2023 |
| Google        | Phaser360                   | Notebook    | [95686db08c](https://linux-hardware.org/?probe=95686db08c) | Sep 26, 2023 |
| Lenovo        | ThinkPad T590 20N5S31U02    | Notebook    | [aa988ac4df](https://linux-hardware.org/?probe=aa988ac4df) | Sep 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8S77U1... | Notebook    | [4a3185fd78](https://linux-hardware.org/?probe=4a3185fd78) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [5ab77e3f48](https://linux-hardware.org/?probe=5ab77e3f48) | Sep 26, 2023 |
| Dell          | Latitude 3190               | Notebook    | [8ebd8669f2](https://linux-hardware.org/?probe=8ebd8669f2) | Sep 26, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [32a39c6a01](https://linux-hardware.org/?probe=32a39c6a01) | Sep 25, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [2881d9e4ec](https://linux-hardware.org/?probe=2881d9e4ec) | Sep 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [4c68092d28](https://linux-hardware.org/?probe=4c68092d28) | Sep 25, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [3afc2a0804](https://linux-hardware.org/?probe=3afc2a0804) | Sep 24, 2023 |
| Huanan        | X99-TF V1.1                 | Desktop     | [694b4ab1f2](https://linux-hardware.org/?probe=694b4ab1f2) | Sep 24, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [408377c3fd](https://linux-hardware.org/?probe=408377c3fd) | Sep 24, 2023 |
| HP            | 3397                        | Desktop     | [cc6f1cc8ba](https://linux-hardware.org/?probe=cc6f1cc8ba) | Sep 24, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [3b050c2582](https://linux-hardware.org/?probe=3b050c2582) | Sep 24, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [ff891ca545](https://linux-hardware.org/?probe=ff891ca545) | Sep 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [da4274c691](https://linux-hardware.org/?probe=da4274c691) | Sep 24, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b3a0648c6e](https://linux-hardware.org/?probe=b3a0648c6e) | Sep 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [6b3c3ce703](https://linux-hardware.org/?probe=6b3c3ce703) | Sep 23, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [5735f79e4f](https://linux-hardware.org/?probe=5735f79e4f) | Sep 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [46a99bb50a](https://linux-hardware.org/?probe=46a99bb50a) | Sep 23, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [e2dd7767f0](https://linux-hardware.org/?probe=e2dd7767f0) | Sep 23, 2023 |
| Dell          | Precision M6600             | Notebook    | [1cef385aec](https://linux-hardware.org/?probe=1cef385aec) | Sep 23, 2023 |
| ASUSTek       | P5K                         | Desktop     | [4d67ad50cf](https://linux-hardware.org/?probe=4d67ad50cf) | Sep 22, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [4bf358cd4f](https://linux-hardware.org/?probe=4bf358cd4f) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Dell          | Latitude 5421               | Notebook    | [fd5892945d](https://linux-hardware.org/?probe=fd5892945d) | Sep 21, 2023 |
| Dell          | Latitude 5421               | Notebook    | [50a3d79521](https://linux-hardware.org/?probe=50a3d79521) | Sep 21, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [37990955f8](https://linux-hardware.org/?probe=37990955f8) | Sep 21, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [8e60d0df9c](https://linux-hardware.org/?probe=8e60d0df9c) | Sep 21, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [ff9bab7040](https://linux-hardware.org/?probe=ff9bab7040) | Sep 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [459e666cd3](https://linux-hardware.org/?probe=459e666cd3) | Sep 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [dfb78764ea](https://linux-hardware.org/?probe=dfb78764ea) | Sep 20, 2023 |
| Lenovo        | ThinkPad X270 20HMS0DF00    | Notebook    | [276048d4f4](https://linux-hardware.org/?probe=276048d4f4) | Sep 20, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a7eae64ec7](https://linux-hardware.org/?probe=a7eae64ec7) | Sep 20, 2023 |
| Lenovo        | ThinkPad E580 20KS001RUK    | Notebook    | [9882734ee2](https://linux-hardware.org/?probe=9882734ee2) | Sep 20, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [b66d6be0cf](https://linux-hardware.org/?probe=b66d6be0cf) | Sep 19, 2023 |
| HP            | 3047h                       | Desktop     | [f684816e88](https://linux-hardware.org/?probe=f684816e88) | Sep 19, 2023 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [e76f3de142](https://linux-hardware.org/?probe=e76f3de142) | Sep 19, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [0ad032f320](https://linux-hardware.org/?probe=0ad032f320) | Sep 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0748266b0a](https://linux-hardware.org/?probe=0748266b0a) | Sep 19, 2023 |
| Medion        | MS-7848                     | Desktop     | [acbe0e1821](https://linux-hardware.org/?probe=acbe0e1821) | Sep 19, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [8d1653a141](https://linux-hardware.org/?probe=8d1653a141) | Sep 19, 2023 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [1ac41cc2e4](https://linux-hardware.org/?probe=1ac41cc2e4) | Sep 19, 2023 |
| Dell          | Latitude 3190               | Notebook    | [0a698044d8](https://linux-hardware.org/?probe=0a698044d8) | Sep 19, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [5680b32e39](https://linux-hardware.org/?probe=5680b32e39) | Sep 18, 2023 |
| Dell          | 0DY2X0 A01                  | Server      | [2384b2e12c](https://linux-hardware.org/?probe=2384b2e12c) | Sep 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [7b51f6f455](https://linux-hardware.org/?probe=7b51f6f455) | Sep 18, 2023 |
| HP            | Notebook                    | Notebook    | [c41430992d](https://linux-hardware.org/?probe=c41430992d) | Sep 18, 2023 |
| Dell          | Latitude 5490               | Notebook    | [94eb709dfc](https://linux-hardware.org/?probe=94eb709dfc) | Sep 18, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMS    | Notebook    | [13de66f73a](https://linux-hardware.org/?probe=13de66f73a) | Sep 17, 2023 |
| Dell          | Latitude E5420              | Notebook    | [56c6b73d62](https://linux-hardware.org/?probe=56c6b73d62) | Sep 17, 2023 |
| Dell          | Latitude E5420              | Notebook    | [5931b51b00](https://linux-hardware.org/?probe=5931b51b00) | Sep 17, 2023 |
| HP            | G72                         | Notebook    | [b77f2ba361](https://linux-hardware.org/?probe=b77f2ba361) | Sep 17, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [832c9cf416](https://linux-hardware.org/?probe=832c9cf416) | Sep 17, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [8368825071](https://linux-hardware.org/?probe=8368825071) | Sep 17, 2023 |
| Dell          | Latitude 5421               | Notebook    | [a42c87b953](https://linux-hardware.org/?probe=a42c87b953) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | Notebook    | [ba678c25e1](https://linux-hardware.org/?probe=ba678c25e1) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | Notebook    | [b056244ce9](https://linux-hardware.org/?probe=b056244ce9) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [8af23c2e56](https://linux-hardware.org/?probe=8af23c2e56) | Sep 17, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [35d0dc4629](https://linux-hardware.org/?probe=35d0dc4629) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [50bfb485e5](https://linux-hardware.org/?probe=50bfb485e5) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d795a474b2](https://linux-hardware.org/?probe=d795a474b2) | Sep 16, 2023 |
| ASUSTek       | PRIME H770-PLUS             | Desktop     | [c58fea9225](https://linux-hardware.org/?probe=c58fea9225) | Sep 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9915642af4](https://linux-hardware.org/?probe=9915642af4) | Sep 16, 2023 |
| Acer          | Predator G3-710             | Desktop     | [aa2ac7f07c](https://linux-hardware.org/?probe=aa2ac7f07c) | Sep 16, 2023 |
| Dell          | Latitude 9420               | Notebook    | [35feb16995](https://linux-hardware.org/?probe=35feb16995) | Sep 15, 2023 |
| HP            | 339A                        | Desktop     | [5808e19d94](https://linux-hardware.org/?probe=5808e19d94) | Sep 15, 2023 |
| Dell          | Latitude 9420               | Notebook    | [da407d0553](https://linux-hardware.org/?probe=da407d0553) | Sep 15, 2023 |
| Gigabyte      | P35-DS3                     | Desktop     | [7cf209e4c1](https://linux-hardware.org/?probe=7cf209e4c1) | Sep 15, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [a3d82edc9c](https://linux-hardware.org/?probe=a3d82edc9c) | Sep 15, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [8f1762e098](https://linux-hardware.org/?probe=8f1762e098) | Sep 15, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [d321e5cfc8](https://linux-hardware.org/?probe=d321e5cfc8) | Sep 14, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [96f4c972a0](https://linux-hardware.org/?probe=96f4c972a0) | Sep 14, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [c3d0531198](https://linux-hardware.org/?probe=c3d0531198) | Sep 14, 2023 |
| Huanan        | X99-TF V1.1                 | Desktop     | [a5acc6026f](https://linux-hardware.org/?probe=a5acc6026f) | Sep 14, 2023 |
| Toshiba       | Intel H81/Q87 PCH 32        | All in one  | [43275b430f](https://linux-hardware.org/?probe=43275b430f) | Sep 14, 2023 |
| ASUSTek       | P553UJ                      | Notebook    | [3463413300](https://linux-hardware.org/?probe=3463413300) | Sep 14, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [df814b2a84](https://linux-hardware.org/?probe=df814b2a84) | Sep 13, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a09109e90c](https://linux-hardware.org/?probe=a09109e90c) | Sep 13, 2023 |
| Dell          | 07T4MC A06                  | Desktop     | [393a33da8c](https://linux-hardware.org/?probe=393a33da8c) | Sep 12, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d4e392a0ad](https://linux-hardware.org/?probe=d4e392a0ad) | Sep 12, 2023 |
| MSI           | Z170A GAMING M9 ACK         | Desktop     | [49cc8ea6d2](https://linux-hardware.org/?probe=49cc8ea6d2) | Sep 12, 2023 |
| Dell          | Latitude E4200              | Notebook    | [ab13ebe930](https://linux-hardware.org/?probe=ab13ebe930) | Sep 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a03ec42023](https://linux-hardware.org/?probe=a03ec42023) | Sep 12, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [34149789e7](https://linux-hardware.org/?probe=34149789e7) | Sep 12, 2023 |
| HP            | 620                         | Notebook    | [59577ac122](https://linux-hardware.org/?probe=59577ac122) | Sep 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [27b430aa3f](https://linux-hardware.org/?probe=27b430aa3f) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [7c32a84014](https://linux-hardware.org/?probe=7c32a84014) | Sep 11, 2023 |
| Dell          | 0HJK12 A03                  | Server      | [b4ec3650ef](https://linux-hardware.org/?probe=b4ec3650ef) | Sep 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [3716cce5f9](https://linux-hardware.org/?probe=3716cce5f9) | Sep 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [77105eb7da](https://linux-hardware.org/?probe=77105eb7da) | Sep 11, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [de229ab61f](https://linux-hardware.org/?probe=de229ab61f) | Sep 11, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a25f4b1c5c](https://linux-hardware.org/?probe=a25f4b1c5c) | Sep 11, 2023 |
| Dell          | Precision 5530              | Notebook    | [7e0e7dca27](https://linux-hardware.org/?probe=7e0e7dca27) | Sep 10, 2023 |
| Dell          | 07T4MC A06                  | Desktop     | [ec26895704](https://linux-hardware.org/?probe=ec26895704) | Sep 10, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [9b4b4d897f](https://linux-hardware.org/?probe=9b4b4d897f) | Sep 10, 2023 |
| LG Electro... | 15Z990-U.AAS5U1             | Notebook    | [61eed61cd5](https://linux-hardware.org/?probe=61eed61cd5) | Sep 10, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [f01636c129](https://linux-hardware.org/?probe=f01636c129) | Sep 09, 2023 |
| Lenovo        | ThinkPad L390 20NSS04400    | Notebook    | [e35abd1445](https://linux-hardware.org/?probe=e35abd1445) | Sep 09, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [dffd28975a](https://linux-hardware.org/?probe=dffd28975a) | Sep 09, 2023 |
| HP            | ProBook 6470b               | Notebook    | [1c8817d025](https://linux-hardware.org/?probe=1c8817d025) | Sep 09, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [23e3266b07](https://linux-hardware.org/?probe=23e3266b07) | Sep 08, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [032db27cfa](https://linux-hardware.org/?probe=032db27cfa) | Sep 08, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [786aafb0e9](https://linux-hardware.org/?probe=786aafb0e9) | Sep 07, 2023 |
| HP            | 1589                        | Desktop     | [550b95765c](https://linux-hardware.org/?probe=550b95765c) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d3e36fc6ea](https://linux-hardware.org/?probe=d3e36fc6ea) | Sep 05, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [89f4028960](https://linux-hardware.org/?probe=89f4028960) | Sep 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [01ede034b7](https://linux-hardware.org/?probe=01ede034b7) | Sep 05, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [1aa546be8c](https://linux-hardware.org/?probe=1aa546be8c) | Sep 05, 2023 |
| MSI           | P55-GD65                    | Desktop     | [2b514a72b1](https://linux-hardware.org/?probe=2b514a72b1) | Sep 05, 2023 |
| Dell          | Precision M4800             | Notebook    | [2e40a27b2e](https://linux-hardware.org/?probe=2e40a27b2e) | Sep 04, 2023 |
| Prestigio     | Smartbook PSB116A           | Notebook    | [d70df77a35](https://linux-hardware.org/?probe=d70df77a35) | Sep 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1d6a4b4279](https://linux-hardware.org/?probe=1d6a4b4279) | Sep 04, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f51b98f4cd](https://linux-hardware.org/?probe=f51b98f4cd) | Sep 04, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [2973871c04](https://linux-hardware.org/?probe=2973871c04) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [2a24e7410f](https://linux-hardware.org/?probe=2a24e7410f) | Sep 03, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [26c9b8cc2c](https://linux-hardware.org/?probe=26c9b8cc2c) | Sep 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [8585671bfb](https://linux-hardware.org/?probe=8585671bfb) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [efd96ce796](https://linux-hardware.org/?probe=efd96ce796) | Sep 03, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [a9fdf4f92b](https://linux-hardware.org/?probe=a9fdf4f92b) | Sep 03, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [dcb8595c51](https://linux-hardware.org/?probe=dcb8595c51) | Sep 03, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [5f73c55303](https://linux-hardware.org/?probe=5f73c55303) | Sep 03, 2023 |
| Lenovo        | ThinkPad X280 20KESAA400    | Notebook    | [461a3a9bc9](https://linux-hardware.org/?probe=461a3a9bc9) | Sep 02, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [8533d021f8](https://linux-hardware.org/?probe=8533d021f8) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [9f3df2894e](https://linux-hardware.org/?probe=9f3df2894e) | Sep 02, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [f6a5d73879](https://linux-hardware.org/?probe=f6a5d73879) | Sep 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [fd0297e4e0](https://linux-hardware.org/?probe=fd0297e4e0) | Sep 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [678bbd1366](https://linux-hardware.org/?probe=678bbd1366) | Sep 01, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [d5d9154715](https://linux-hardware.org/?probe=d5d9154715) | Sep 01, 2023 |
| Lenovo        | ThinkPad X301 2774LEG       | Notebook    | [50f297712d](https://linux-hardware.org/?probe=50f297712d) | Sep 01, 2023 |
| HP            | 1589                        | Desktop     | [447cae1b4c](https://linux-hardware.org/?probe=447cae1b4c) | Sep 01, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [ff1be33f8e](https://linux-hardware.org/?probe=ff1be33f8e) | Sep 01, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [e811db37c5](https://linux-hardware.org/?probe=e811db37c5) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | Notebook    | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [0ac2938640](https://linux-hardware.org/?probe=0ac2938640) | Aug 31, 2023 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [85cb771ac1](https://linux-hardware.org/?probe=85cb771ac1) | Aug 31, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ca52538b46](https://linux-hardware.org/?probe=ca52538b46) | Aug 31, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [b900fd0bc7](https://linux-hardware.org/?probe=b900fd0bc7) | Aug 31, 2023 |
| HP            | ProBook 4530s               | Notebook    | [09fddaab4d](https://linux-hardware.org/?probe=09fddaab4d) | Aug 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [a9c1ad1756](https://linux-hardware.org/?probe=a9c1ad1756) | Aug 31, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [ca7a99ecd9](https://linux-hardware.org/?probe=ca7a99ecd9) | Aug 31, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [76f095d7c2](https://linux-hardware.org/?probe=76f095d7c2) | Aug 31, 2023 |
| HP            | 8158 A01                    | Mini pc     | [9be38fb21f](https://linux-hardware.org/?probe=9be38fb21f) | Aug 30, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [f3e3f12f08](https://linux-hardware.org/?probe=f3e3f12f08) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3977e85dce](https://linux-hardware.org/?probe=3977e85dce) | Aug 30, 2023 |
| HP            | 3047h                       | Desktop     | [5a35a1ebd1](https://linux-hardware.org/?probe=5a35a1ebd1) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [a2f37c4111](https://linux-hardware.org/?probe=a2f37c4111) | Aug 30, 2023 |
| Dell          | Latitude 5430               | Notebook    | [477898be1f](https://linux-hardware.org/?probe=477898be1f) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470p 20J60014P... | Notebook    | [7690eb9089](https://linux-hardware.org/?probe=7690eb9089) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Dell          | Latitude E6520              | Notebook    | [4918e66ad8](https://linux-hardware.org/?probe=4918e66ad8) | Aug 29, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [567a59e1bc](https://linux-hardware.org/?probe=567a59e1bc) | Aug 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [6e16da127a](https://linux-hardware.org/?probe=6e16da127a) | Aug 29, 2023 |
| Dell          | Latitude D630               | Notebook    | [d23ff7e118](https://linux-hardware.org/?probe=d23ff7e118) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [8741a9bb96](https://linux-hardware.org/?probe=8741a9bb96) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [7efcdba9ef](https://linux-hardware.org/?probe=7efcdba9ef) | Aug 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [7e48b59643](https://linux-hardware.org/?probe=7e48b59643) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | Notebook    | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [9071631c6d](https://linux-hardware.org/?probe=9071631c6d) | Aug 28, 2023 |
| ASUSTek       | ZenBook UX362FA_UX362FA     | Convertible | [e09a09d01e](https://linux-hardware.org/?probe=e09a09d01e) | Aug 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e6e9efdb61](https://linux-hardware.org/?probe=e6e9efdb61) | Aug 26, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [af55d05855](https://linux-hardware.org/?probe=af55d05855) | Aug 26, 2023 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | Desktop     | [228bdfda30](https://linux-hardware.org/?probe=228bdfda30) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | Desktop     | [9ce89a0c87](https://linux-hardware.org/?probe=9ce89a0c87) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [3ee57cbdbe](https://linux-hardware.org/?probe=3ee57cbdbe) | Aug 26, 2023 |
| Lenovo        | ThinkPad E520 1143CWG       | Notebook    | [66d9a31686](https://linux-hardware.org/?probe=66d9a31686) | Aug 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [01ae0852df](https://linux-hardware.org/?probe=01ae0852df) | Aug 25, 2023 |
| Dell          | Latitude E6400              | Notebook    | [4526151015](https://linux-hardware.org/?probe=4526151015) | Aug 25, 2023 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [38448389ce](https://linux-hardware.org/?probe=38448389ce) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [bb854d7896](https://linux-hardware.org/?probe=bb854d7896) | Aug 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f69210d69](https://linux-hardware.org/?probe=1f69210d69) | Aug 25, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [d1e0d41982](https://linux-hardware.org/?probe=d1e0d41982) | Aug 24, 2023 |
| Dell          | XPS 9320                    | Notebook    | [1ba8e13634](https://linux-hardware.org/?probe=1ba8e13634) | Aug 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e6c72eb614](https://linux-hardware.org/?probe=e6c72eb614) | Aug 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [12ac0bf5ed](https://linux-hardware.org/?probe=12ac0bf5ed) | Aug 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [097bbaf86a](https://linux-hardware.org/?probe=097bbaf86a) | Aug 24, 2023 |
| Dell          | Latitude 3520               | Notebook    | [92ef936c86](https://linux-hardware.org/?probe=92ef936c86) | Aug 24, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [71ba491330](https://linux-hardware.org/?probe=71ba491330) | Aug 24, 2023 |
| Gigabyte      | P67A-UD7-B3                 | Desktop     | [912d956729](https://linux-hardware.org/?probe=912d956729) | Aug 24, 2023 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [a28ee4ea6b](https://linux-hardware.org/?probe=a28ee4ea6b) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [26d59e1060](https://linux-hardware.org/?probe=26d59e1060) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [d10b0c4ca0](https://linux-hardware.org/?probe=d10b0c4ca0) | Aug 23, 2023 |
| HP            | Compaq nc8430 (EM741AV)     | Notebook    | [02d656a746](https://linux-hardware.org/?probe=02d656a746) | Aug 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [25d163ad9e](https://linux-hardware.org/?probe=25d163ad9e) | Aug 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [61ddf042df](https://linux-hardware.org/?probe=61ddf042df) | Aug 22, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [5a9badb376](https://linux-hardware.org/?probe=5a9badb376) | Aug 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c080c15699](https://linux-hardware.org/?probe=c080c15699) | Aug 22, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a03d5e6451](https://linux-hardware.org/?probe=a03d5e6451) | Aug 21, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [fd5614f8d1](https://linux-hardware.org/?probe=fd5614f8d1) | Aug 21, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [5fa4b8ae13](https://linux-hardware.org/?probe=5fa4b8ae13) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [3911bdd51d](https://linux-hardware.org/?probe=3911bdd51d) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [1979db3345](https://linux-hardware.org/?probe=1979db3345) | Aug 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d1af143bed](https://linux-hardware.org/?probe=d1af143bed) | Aug 19, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [637bd422c5](https://linux-hardware.org/?probe=637bd422c5) | Aug 19, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f5751cb101](https://linux-hardware.org/?probe=f5751cb101) | Aug 19, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [800ad97443](https://linux-hardware.org/?probe=800ad97443) | Aug 19, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [054a5a44ad](https://linux-hardware.org/?probe=054a5a44ad) | Aug 18, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [2173b6b2b0](https://linux-hardware.org/?probe=2173b6b2b0) | Aug 18, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d84596d3c1](https://linux-hardware.org/?probe=d84596d3c1) | Aug 18, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [d05585906d](https://linux-hardware.org/?probe=d05585906d) | Aug 18, 2023 |
| Lenovo        | ThinkPad L480 20LTS6S904    | Notebook    | [32ded049ec](https://linux-hardware.org/?probe=32ded049ec) | Aug 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [b2c7c5cb9f](https://linux-hardware.org/?probe=b2c7c5cb9f) | Aug 17, 2023 |
| HP            | Laptop 14-df0xxx            | Notebook    | [7d3c3dc329](https://linux-hardware.org/?probe=7d3c3dc329) | Aug 17, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [75556aed08](https://linux-hardware.org/?probe=75556aed08) | Aug 16, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [b9134a5ee3](https://linux-hardware.org/?probe=b9134a5ee3) | Aug 16, 2023 |
| Unknown       | Unknown                     | Convertible | [24b989fc80](https://linux-hardware.org/?probe=24b989fc80) | Aug 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [f3c603341d](https://linux-hardware.org/?probe=f3c603341d) | Aug 16, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [2486dc323f](https://linux-hardware.org/?probe=2486dc323f) | Aug 16, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [bd75f21361](https://linux-hardware.org/?probe=bd75f21361) | Aug 16, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [4906f87d9e](https://linux-hardware.org/?probe=4906f87d9e) | Aug 16, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [abb0a09230](https://linux-hardware.org/?probe=abb0a09230) | Aug 16, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| Lenovo        | ThinkPad T470 20HES07J00    | Notebook    | [32ec341753](https://linux-hardware.org/?probe=32ec341753) | Aug 16, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [51b04bf027](https://linux-hardware.org/?probe=51b04bf027) | Aug 16, 2023 |
| Samsung       | 530U4E/540U4E               | Notebook    | [7189151ffc](https://linux-hardware.org/?probe=7189151ffc) | Aug 15, 2023 |
| MSI           | H310M PRO-VDH               | Desktop     | [fe173bc6ed](https://linux-hardware.org/?probe=fe173bc6ed) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| Lenovo        | G580                        | Notebook    | [ceeee3c405](https://linux-hardware.org/?probe=ceeee3c405) | Aug 15, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [69deac32bd](https://linux-hardware.org/?probe=69deac32bd) | Aug 14, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [076c807d2d](https://linux-hardware.org/?probe=076c807d2d) | Aug 14, 2023 |
| Samsung       | 530U4E/540U4E               | Notebook    | [6a886e53b9](https://linux-hardware.org/?probe=6a886e53b9) | Aug 14, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7ff2052c0f](https://linux-hardware.org/?probe=7ff2052c0f) | Aug 14, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0SQ... | Tablet      | [833489f8a8](https://linux-hardware.org/?probe=833489f8a8) | Aug 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [8af14f1aaa](https://linux-hardware.org/?probe=8af14f1aaa) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [1d77ac2450](https://linux-hardware.org/?probe=1d77ac2450) | Aug 13, 2023 |
| Acer          | Predator G5-793             | Notebook    | [bb25759563](https://linux-hardware.org/?probe=bb25759563) | Aug 13, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [84b4b40450](https://linux-hardware.org/?probe=84b4b40450) | Aug 13, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [25a3921b74](https://linux-hardware.org/?probe=25a3921b74) | Aug 13, 2023 |
| HP            | EliteBook 845 G9            | Notebook    | [cf6dfa50ef](https://linux-hardware.org/?probe=cf6dfa50ef) | Aug 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [b770999baf](https://linux-hardware.org/?probe=b770999baf) | Aug 12, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [b296a33ab3](https://linux-hardware.org/?probe=b296a33ab3) | Aug 12, 2023 |
| ECS           | H61H2-M6                    | Desktop     | [b9b9ef9f84](https://linux-hardware.org/?probe=b9b9ef9f84) | Aug 12, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [b43e2738d9](https://linux-hardware.org/?probe=b43e2738d9) | Aug 12, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [6986ca63da](https://linux-hardware.org/?probe=6986ca63da) | Aug 12, 2023 |
| Fujitsu       | FMVA0800C                   | Notebook    | [1dae7b170b](https://linux-hardware.org/?probe=1dae7b170b) | Aug 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [7e4a63e58c](https://linux-hardware.org/?probe=7e4a63e58c) | Aug 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [fc48a936d7](https://linux-hardware.org/?probe=fc48a936d7) | Aug 12, 2023 |
| Gigabyte      | Z170N-WIFI-CF               | Desktop     | [2ee88f0ec0](https://linux-hardware.org/?probe=2ee88f0ec0) | Aug 11, 2023 |
| HP            | 83E8                        | Desktop     | [a782638343](https://linux-hardware.org/?probe=a782638343) | Aug 11, 2023 |
| Lenovo        | ThinkPad T430s 2356LPG      | Notebook    | [97dfe9511b](https://linux-hardware.org/?probe=97dfe9511b) | Aug 10, 2023 |
| Google        | Kip                         | Notebook    | [553df8dcdc](https://linux-hardware.org/?probe=553df8dcdc) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d38ef662d4](https://linux-hardware.org/?probe=d38ef662d4) | Aug 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [78f477986b](https://linux-hardware.org/?probe=78f477986b) | Aug 10, 2023 |
| Dell          | Latitude E6540              | Notebook    | [758d587fbb](https://linux-hardware.org/?probe=758d587fbb) | Aug 10, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [a6eabbbfef](https://linux-hardware.org/?probe=a6eabbbfef) | Aug 09, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | EliteBook 845 G9            | Notebook    | [1ff8d81e4e](https://linux-hardware.org/?probe=1ff8d81e4e) | Aug 09, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a5e0e043cb](https://linux-hardware.org/?probe=a5e0e043cb) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| MSI           | 970A-G43 PLUS               | Desktop     | [133d4b58c9](https://linux-hardware.org/?probe=133d4b58c9) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [f6b63d9967](https://linux-hardware.org/?probe=f6b63d9967) | Aug 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [f2547c0339](https://linux-hardware.org/?probe=f2547c0339) | Aug 08, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [93e4fee7df](https://linux-hardware.org/?probe=93e4fee7df) | Aug 08, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [9094c29548](https://linux-hardware.org/?probe=9094c29548) | Aug 07, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [25bb416eb3](https://linux-hardware.org/?probe=25bb416eb3) | Aug 07, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [f4beee823e](https://linux-hardware.org/?probe=f4beee823e) | Aug 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [beecacb434](https://linux-hardware.org/?probe=beecacb434) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [08b395f8d6](https://linux-hardware.org/?probe=08b395f8d6) | Aug 07, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [fb8e926bd4](https://linux-hardware.org/?probe=fb8e926bd4) | Aug 07, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [5a254fe1d6](https://linux-hardware.org/?probe=5a254fe1d6) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [164e109040](https://linux-hardware.org/?probe=164e109040) | Aug 06, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [270c9a3ea0](https://linux-hardware.org/?probe=270c9a3ea0) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [f77c465da0](https://linux-hardware.org/?probe=f77c465da0) | Aug 06, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [db5a797fc0](https://linux-hardware.org/?probe=db5a797fc0) | Aug 06, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [23ecc4a8e5](https://linux-hardware.org/?probe=23ecc4a8e5) | Aug 06, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [dcd061dff8](https://linux-hardware.org/?probe=dcd061dff8) | Aug 05, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [4f0b615c8e](https://linux-hardware.org/?probe=4f0b615c8e) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G731GU_GL731GU    | Notebook    | [b3c77ee42f](https://linux-hardware.org/?probe=b3c77ee42f) | Aug 05, 2023 |
| Dell          | Latitude 5421               | Notebook    | [d01013b679](https://linux-hardware.org/?probe=d01013b679) | Aug 05, 2023 |
| Dell          | Latitude 5421               | Notebook    | [5dfde4e6ac](https://linux-hardware.org/?probe=5dfde4e6ac) | Aug 05, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [420353bf79](https://linux-hardware.org/?probe=420353bf79) | Aug 04, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [6ad0758102](https://linux-hardware.org/?probe=6ad0758102) | Aug 04, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [34edcb7dae](https://linux-hardware.org/?probe=34edcb7dae) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [bd994e4cc6](https://linux-hardware.org/?probe=bd994e4cc6) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [ab2f3b8c7b](https://linux-hardware.org/?probe=ab2f3b8c7b) | Aug 04, 2023 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [9f27152a86](https://linux-hardware.org/?probe=9f27152a86) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8036065591](https://linux-hardware.org/?probe=8036065591) | Aug 03, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [a61b8168b7](https://linux-hardware.org/?probe=a61b8168b7) | Aug 02, 2023 |
| ECS           | H61H2-M6                    | Desktop     | [12990c5c80](https://linux-hardware.org/?probe=12990c5c80) | Aug 02, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9be3b9bb83](https://linux-hardware.org/?probe=9be3b9bb83) | Aug 02, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [1acfa69d70](https://linux-hardware.org/?probe=1acfa69d70) | Aug 02, 2023 |
| HP            | 8054                        | Desktop     | [f53df18325](https://linux-hardware.org/?probe=f53df18325) | Aug 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [8bc1531bf6](https://linux-hardware.org/?probe=8bc1531bf6) | Aug 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ca00849760](https://linux-hardware.org/?probe=ca00849760) | Aug 02, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [695e2dec6b](https://linux-hardware.org/?probe=695e2dec6b) | Aug 02, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [5d63b469f8](https://linux-hardware.org/?probe=5d63b469f8) | Aug 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c2c27c3268](https://linux-hardware.org/?probe=c2c27c3268) | Aug 01, 2023 |
| ECS           | H61H2-M6                    | Desktop     | [836267e5f7](https://linux-hardware.org/?probe=836267e5f7) | Aug 01, 2023 |
| HP            | 82B5                        | All in one  | [e63af4a7b9](https://linux-hardware.org/?probe=e63af4a7b9) | Aug 01, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [30389578ca](https://linux-hardware.org/?probe=30389578ca) | Aug 01, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [af6a2cb993](https://linux-hardware.org/?probe=af6a2cb993) | Jul 31, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [3aeae112c3](https://linux-hardware.org/?probe=3aeae112c3) | Jul 31, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [ce76d8b410](https://linux-hardware.org/?probe=ce76d8b410) | Jul 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [762d07665a](https://linux-hardware.org/?probe=762d07665a) | Jul 31, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [cd8671be26](https://linux-hardware.org/?probe=cd8671be26) | Jul 31, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [eb13fb97fb](https://linux-hardware.org/?probe=eb13fb97fb) | Jul 30, 2023 |
| ASUSTek       | E200HA                      | Notebook    | [6ab93e7940](https://linux-hardware.org/?probe=6ab93e7940) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [8e59554b8d](https://linux-hardware.org/?probe=8e59554b8d) | Jul 30, 2023 |
| Google        | Relm                        | Notebook    | [1c8bd1f9dd](https://linux-hardware.org/?probe=1c8bd1f9dd) | Jul 30, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [39bd06bd9b](https://linux-hardware.org/?probe=39bd06bd9b) | Jul 30, 2023 |
| Lenovo        | ThinkPad A285 20MXS0AE00    | Notebook    | [a6ada51a02](https://linux-hardware.org/?probe=a6ada51a02) | Jul 29, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [fad00d6412](https://linux-hardware.org/?probe=fad00d6412) | Jul 29, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [24b2f4274d](https://linux-hardware.org/?probe=24b2f4274d) | Jul 29, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [690e49362b](https://linux-hardware.org/?probe=690e49362b) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [b277fcda26](https://linux-hardware.org/?probe=b277fcda26) | Jul 28, 2023 |
| Gigabyte      | EP45T-UD3LR                 | Desktop     | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ca9b6e0320](https://linux-hardware.org/?probe=ca9b6e0320) | Jul 28, 2023 |
| Toshiba       | Satellite C50D-A-11G        | Notebook    | [b67508b754](https://linux-hardware.org/?probe=b67508b754) | Jul 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [f0bd5c3409](https://linux-hardware.org/?probe=f0bd5c3409) | Jul 27, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e882db39b8](https://linux-hardware.org/?probe=e882db39b8) | Jul 27, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e235fb3a23](https://linux-hardware.org/?probe=e235fb3a23) | Jul 26, 2023 |
| Dell          | Latitude 9420               | Notebook    | [03c3ca79c4](https://linux-hardware.org/?probe=03c3ca79c4) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [355fadbc12](https://linux-hardware.org/?probe=355fadbc12) | Jul 26, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [863a5cb9da](https://linux-hardware.org/?probe=863a5cb9da) | Jul 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e79fd50f34](https://linux-hardware.org/?probe=e79fd50f34) | Jul 26, 2023 |
| Lenovo        | ThinkCentre M58 3231W2Y     | Desktop     | [72f09cd320](https://linux-hardware.org/?probe=72f09cd320) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [24f65961ef](https://linux-hardware.org/?probe=24f65961ef) | Jul 26, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [3cb7454711](https://linux-hardware.org/?probe=3cb7454711) | Jul 25, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [af0355313e](https://linux-hardware.org/?probe=af0355313e) | Jul 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [290a0dd297](https://linux-hardware.org/?probe=290a0dd297) | Jul 25, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [346055ca33](https://linux-hardware.org/?probe=346055ca33) | Jul 25, 2023 |
| ZOTAC         | ZBOX-BI322                  | Mini pc     | [f595927b7b](https://linux-hardware.org/?probe=f595927b7b) | Jul 25, 2023 |
| HP            | 212B                        | Desktop     | [8e6a290d51](https://linux-hardware.org/?probe=8e6a290d51) | Jul 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5ec24ea9ad](https://linux-hardware.org/?probe=5ec24ea9ad) | Jul 25, 2023 |
| Dell          | Latitude 3190               | Notebook    | [b1730d834d](https://linux-hardware.org/?probe=b1730d834d) | Jul 25, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [9ffd99b082](https://linux-hardware.org/?probe=9ffd99b082) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [412bc51f72](https://linux-hardware.org/?probe=412bc51f72) | Jul 24, 2023 |
| HP            | 198E                        | Desktop     | [c2f7b19d13](https://linux-hardware.org/?probe=c2f7b19d13) | Jul 24, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [816a8d70bb](https://linux-hardware.org/?probe=816a8d70bb) | Jul 24, 2023 |
| Timi          | TM1701                      | Notebook    | [eb1246586e](https://linux-hardware.org/?probe=eb1246586e) | Jul 24, 2023 |
| ASUSTek       | F7E                         | Notebook    | [2aef1cc2c4](https://linux-hardware.org/?probe=2aef1cc2c4) | Jul 24, 2023 |
| Timi          | TM1701                      | Notebook    | [17fefbecba](https://linux-hardware.org/?probe=17fefbecba) | Jul 24, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [fbfa8af465](https://linux-hardware.org/?probe=fbfa8af465) | Jul 24, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [b27862dc34](https://linux-hardware.org/?probe=b27862dc34) | Jul 24, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [9243bb6a08](https://linux-hardware.org/?probe=9243bb6a08) | Jul 24, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a2fcdf6c36](https://linux-hardware.org/?probe=a2fcdf6c36) | Jul 24, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [732fe69d59](https://linux-hardware.org/?probe=732fe69d59) | Jul 23, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [44958ef86b](https://linux-hardware.org/?probe=44958ef86b) | Jul 23, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [10e8c0d4ad](https://linux-hardware.org/?probe=10e8c0d4ad) | Jul 23, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b21b29c46e](https://linux-hardware.org/?probe=b21b29c46e) | Jul 23, 2023 |
| Google        | Snappy                      | Notebook    | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Dell          | 0VD92X A00                  | Desktop     | [675e646d05](https://linux-hardware.org/?probe=675e646d05) | Jul 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [467cc30f89](https://linux-hardware.org/?probe=467cc30f89) | Jul 22, 2023 |
| ASRock        | B85M                        | Desktop     | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| MSI           | PR601/VR603                 | Notebook    | [b982476d84](https://linux-hardware.org/?probe=b982476d84) | Jul 21, 2023 |
| HP            | 3032h                       | Desktop     | [f6a4202b21](https://linux-hardware.org/?probe=f6a4202b21) | Jul 21, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [73a56d2df7](https://linux-hardware.org/?probe=73a56d2df7) | Jul 21, 2023 |
| Razer         | Blade 15 Base Model (Mid... | Notebook    | [d2d53e7406](https://linux-hardware.org/?probe=d2d53e7406) | Jul 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [fcdb1fdeed](https://linux-hardware.org/?probe=fcdb1fdeed) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [0bd52b9adf](https://linux-hardware.org/?probe=0bd52b9adf) | Jul 20, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [26c19ee81f](https://linux-hardware.org/?probe=26c19ee81f) | Jul 19, 2023 |
| Dell          | Latitude 9420               | Notebook    | [750f80b869](https://linux-hardware.org/?probe=750f80b869) | Jul 19, 2023 |
| Dell          | Latitude 9420               | Notebook    | [a4ba4bfde1](https://linux-hardware.org/?probe=a4ba4bfde1) | Jul 19, 2023 |
| Dell          | Latitude E6400              | Notebook    | [7e9ef12f0d](https://linux-hardware.org/?probe=7e9ef12f0d) | Jul 19, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [17c6866da9](https://linux-hardware.org/?probe=17c6866da9) | Jul 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8ff38f3782](https://linux-hardware.org/?probe=8ff38f3782) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [35d510901b](https://linux-hardware.org/?probe=35d510901b) | Jul 18, 2023 |
| Teclast       | F6 Pro                      | Notebook    | [d9f3a038e0](https://linux-hardware.org/?probe=d9f3a038e0) | Jul 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [18f41b2be6](https://linux-hardware.org/?probe=18f41b2be6) | Jul 17, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [c527cf56ad](https://linux-hardware.org/?probe=c527cf56ad) | Jul 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS07T00    | Notebook    | [0c460a8007](https://linux-hardware.org/?probe=0c460a8007) | Jul 17, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f4936b2064](https://linux-hardware.org/?probe=f4936b2064) | Jul 17, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [111c0b962d](https://linux-hardware.org/?probe=111c0b962d) | Jul 16, 2023 |
| Dell          | Latitude E6440              | Notebook    | [4e40dc49f3](https://linux-hardware.org/?probe=4e40dc49f3) | Jul 16, 2023 |
| HP            | Pavilion HDX9200            | Notebook    | [d893c8a2d1](https://linux-hardware.org/?probe=d893c8a2d1) | Jul 16, 2023 |
| Dell          | Latitude E6330              | Notebook    | [6adb67344f](https://linux-hardware.org/?probe=6adb67344f) | Jul 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0T101    | Notebook    | [6154504eac](https://linux-hardware.org/?probe=6154504eac) | Jul 15, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [d91fe40195](https://linux-hardware.org/?probe=d91fe40195) | Jul 15, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [f8ddf3a3a3](https://linux-hardware.org/?probe=f8ddf3a3a3) | Jul 15, 2023 |
| Lenovo        | ThinkPad X240 20AMS07T00    | Notebook    | [8ce6db48b9](https://linux-hardware.org/?probe=8ce6db48b9) | Jul 15, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9e829a5538](https://linux-hardware.org/?probe=9e829a5538) | Jul 14, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [f416cb06c2](https://linux-hardware.org/?probe=f416cb06c2) | Jul 14, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [f0736c39fe](https://linux-hardware.org/?probe=f0736c39fe) | Jul 13, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Dell          | Latitude E6330              | Notebook    | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| Toshiba       | Satellite S75-B             | Notebook    | [ee71e28c8f](https://linux-hardware.org/?probe=ee71e28c8f) | Jul 12, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [67ef58f2b3](https://linux-hardware.org/?probe=67ef58f2b3) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | Notebook    | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a78428eb21](https://linux-hardware.org/?probe=a78428eb21) | Jul 11, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ec95cc29fd](https://linux-hardware.org/?probe=ec95cc29fd) | Jul 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [ef1f607a84](https://linux-hardware.org/?probe=ef1f607a84) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [97f39991c3](https://linux-hardware.org/?probe=97f39991c3) | Jul 11, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [1ed238ea9b](https://linux-hardware.org/?probe=1ed238ea9b) | Jul 11, 2023 |
| ASRock        | H81M                        | Desktop     | [042e2e3b56](https://linux-hardware.org/?probe=042e2e3b56) | Jul 11, 2023 |
| ASRock        | H81M                        | Desktop     | [c4b398d08c](https://linux-hardware.org/?probe=c4b398d08c) | Jul 11, 2023 |
| HP            | 82B5                        | All in one  | [3f1fecd5c3](https://linux-hardware.org/?probe=3f1fecd5c3) | Jul 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ab32a0e447](https://linux-hardware.org/?probe=ab32a0e447) | Jul 11, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f067ca0dbf](https://linux-hardware.org/?probe=f067ca0dbf) | Jul 11, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [8b9677cc2a](https://linux-hardware.org/?probe=8b9677cc2a) | Jul 10, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [acdd4ea952](https://linux-hardware.org/?probe=acdd4ea952) | Jul 10, 2023 |
| Lenovo        | ThinkPad Edge 0578P6G       | Notebook    | [e79fbdad2d](https://linux-hardware.org/?probe=e79fbdad2d) | Jul 10, 2023 |
| Google        | Guado                       | Desktop     | [d14465ad06](https://linux-hardware.org/?probe=d14465ad06) | Jul 10, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [38420a6afe](https://linux-hardware.org/?probe=38420a6afe) | Jul 10, 2023 |
| MSI           | X99A GAMING 9 ACK           | Desktop     | [4a36d070b4](https://linux-hardware.org/?probe=4a36d070b4) | Jul 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [73b13fd5eb](https://linux-hardware.org/?probe=73b13fd5eb) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [03da98871c](https://linux-hardware.org/?probe=03da98871c) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [15e8251d36](https://linux-hardware.org/?probe=15e8251d36) | Jul 10, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [d4ca6c4f81](https://linux-hardware.org/?probe=d4ca6c4f81) | Jul 10, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [b91bb21dfc](https://linux-hardware.org/?probe=b91bb21dfc) | Jul 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [1e6fc6f253](https://linux-hardware.org/?probe=1e6fc6f253) | Jul 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [14c6f3f286](https://linux-hardware.org/?probe=14c6f3f286) | Jul 10, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [6a55de667a](https://linux-hardware.org/?probe=6a55de667a) | Jul 09, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [215d2135b3](https://linux-hardware.org/?probe=215d2135b3) | Jul 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [42aaaa0acb](https://linux-hardware.org/?probe=42aaaa0acb) | Jul 09, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [60e671ef49](https://linux-hardware.org/?probe=60e671ef49) | Jul 09, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [2dfec77944](https://linux-hardware.org/?probe=2dfec77944) | Jul 09, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b29db59f6a](https://linux-hardware.org/?probe=b29db59f6a) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [570f59305c](https://linux-hardware.org/?probe=570f59305c) | Jul 08, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [6d62d0cdbf](https://linux-hardware.org/?probe=6d62d0cdbf) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [9b8e16f852](https://linux-hardware.org/?probe=9b8e16f852) | Jul 08, 2023 |
| Toshiba       | PORTEGE M700                | Notebook    | [6a67dec7ab](https://linux-hardware.org/?probe=6a67dec7ab) | Jul 08, 2023 |
| Toshiba       | PORTEGE M700                | Notebook    | [b735ddd9a6](https://linux-hardware.org/?probe=b735ddd9a6) | Jul 08, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [54ac55c49e](https://linux-hardware.org/?probe=54ac55c49e) | Jul 07, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [296474a1b1](https://linux-hardware.org/?probe=296474a1b1) | Jul 07, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [e4bb31a52c](https://linux-hardware.org/?probe=e4bb31a52c) | Jul 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [49c59b6c86](https://linux-hardware.org/?probe=49c59b6c86) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [df2a737853](https://linux-hardware.org/?probe=df2a737853) | Jul 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9ecae424ad](https://linux-hardware.org/?probe=9ecae424ad) | Jul 07, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [43034103ef](https://linux-hardware.org/?probe=43034103ef) | Jul 06, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [54611e82ec](https://linux-hardware.org/?probe=54611e82ec) | Jul 06, 2023 |
| Google        | Guado                       | Desktop     | [8bd38f802a](https://linux-hardware.org/?probe=8bd38f802a) | Jul 06, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [23a6105e01](https://linux-hardware.org/?probe=23a6105e01) | Jul 06, 2023 |
| ASRock        | Z370 Killer SLI             | Desktop     | [b7a676e2fc](https://linux-hardware.org/?probe=b7a676e2fc) | Jul 05, 2023 |
| Dell          | Latitude 7420               | Notebook    | [44c51e8365](https://linux-hardware.org/?probe=44c51e8365) | Jul 05, 2023 |
| AAEON         | AEC-6637                    | Notebook    | [53f8e37edc](https://linux-hardware.org/?probe=53f8e37edc) | Jul 05, 2023 |
| AAEON         | AEC-6637                    | Notebook    | [a105861e1d](https://linux-hardware.org/?probe=a105861e1d) | Jul 05, 2023 |
| Dell          | Latitude 7420               | Notebook    | [9eae2c6ad4](https://linux-hardware.org/?probe=9eae2c6ad4) | Jul 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [c997aced4e](https://linux-hardware.org/?probe=c997aced4e) | Jul 05, 2023 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [685f105356](https://linux-hardware.org/?probe=685f105356) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3e5dc0c313](https://linux-hardware.org/?probe=3e5dc0c313) | Jul 05, 2023 |
| HP            | 339A                        | Desktop     | [8d051ead1c](https://linux-hardware.org/?probe=8d051ead1c) | Jul 05, 2023 |
| ASRock        | Z370 Killer SLI             | Desktop     | [e7c0ca1bfc](https://linux-hardware.org/?probe=e7c0ca1bfc) | Jul 05, 2023 |
| HP            | 550                         | Notebook    | [f788d05211](https://linux-hardware.org/?probe=f788d05211) | Jul 05, 2023 |
| HP            | 650                         | Notebook    | [a3077996ad](https://linux-hardware.org/?probe=a3077996ad) | Jul 05, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [71ab16d717](https://linux-hardware.org/?probe=71ab16d717) | Jul 05, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [1a32b23618](https://linux-hardware.org/?probe=1a32b23618) | Jul 04, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [abc4554a51](https://linux-hardware.org/?probe=abc4554a51) | Jul 04, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [2be3b17236](https://linux-hardware.org/?probe=2be3b17236) | Jul 04, 2023 |
| Dell          | Latitude 3190               | Notebook    | [b895b6dced](https://linux-hardware.org/?probe=b895b6dced) | Jul 04, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [df1fff149d](https://linux-hardware.org/?probe=df1fff149d) | Jul 04, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [22a13c2e16](https://linux-hardware.org/?probe=22a13c2e16) | Jul 03, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [75a8750d34](https://linux-hardware.org/?probe=75a8750d34) | Jul 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [f567c6c550](https://linux-hardware.org/?probe=f567c6c550) | Jul 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8bb4af1cb5](https://linux-hardware.org/?probe=8bb4af1cb5) | Jul 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [67281face4](https://linux-hardware.org/?probe=67281face4) | Jul 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f928781025](https://linux-hardware.org/?probe=f928781025) | Jul 03, 2023 |
| Acer          | FX58M                       | Desktop     | [44e563ac2a](https://linux-hardware.org/?probe=44e563ac2a) | Jul 02, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [6e52890194](https://linux-hardware.org/?probe=6e52890194) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| Google        | Relm                        | Notebook    | [ef72648bb6](https://linux-hardware.org/?probe=ef72648bb6) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| Acer          | FX58M                       | Desktop     | [69f3a5d4fb](https://linux-hardware.org/?probe=69f3a5d4fb) | Jul 02, 2023 |
| Gigabyte      | P55M-UD2                    | Desktop     | [babec703df](https://linux-hardware.org/?probe=babec703df) | Jul 02, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [03879163c2](https://linux-hardware.org/?probe=03879163c2) | Jul 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9e65cd9bd1](https://linux-hardware.org/?probe=9e65cd9bd1) | Jul 02, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [f923d36676](https://linux-hardware.org/?probe=f923d36676) | Jul 01, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [9d8f40247e](https://linux-hardware.org/?probe=9d8f40247e) | Jul 01, 2023 |
| Packard Be... | EasyNote TSX66HR            | Notebook    | [96253a3da8](https://linux-hardware.org/?probe=96253a3da8) | Jul 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [c99236ef84](https://linux-hardware.org/?probe=c99236ef84) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | Notebook    | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a526c901ee](https://linux-hardware.org/?probe=a526c901ee) | Jun 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [723de914e2](https://linux-hardware.org/?probe=723de914e2) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Medion        | BTDD-TI                     | All in one  | [64b84cf34d](https://linux-hardware.org/?probe=64b84cf34d) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | Desktop     | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [34df27504f](https://linux-hardware.org/?probe=34df27504f) | Jun 28, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [cab34ec3dc](https://linux-hardware.org/?probe=cab34ec3dc) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| ASUSTek       | K54C                        | Notebook    | [4152d1fcff](https://linux-hardware.org/?probe=4152d1fcff) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [1aa332e26f](https://linux-hardware.org/?probe=1aa332e26f) | Jun 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [0817dd25ff](https://linux-hardware.org/?probe=0817dd25ff) | Jun 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [5f68b5235f](https://linux-hardware.org/?probe=5f68b5235f) | Jun 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [157d424ec0](https://linux-hardware.org/?probe=157d424ec0) | Jun 26, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [f02bb9a43a](https://linux-hardware.org/?probe=f02bb9a43a) | Jun 26, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b4fcf1904c](https://linux-hardware.org/?probe=b4fcf1904c) | Jun 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e55023fb8b](https://linux-hardware.org/?probe=e55023fb8b) | Jun 26, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0b72aec1b9](https://linux-hardware.org/?probe=0b72aec1b9) | Jun 26, 2023 |
| HP            | 255 G5 Notebook PC          | Notebook    | [cad891675f](https://linux-hardware.org/?probe=cad891675f) | Jun 25, 2023 |
| HP            | 21B4 A01                    | Desktop     | [e277fd2772](https://linux-hardware.org/?probe=e277fd2772) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [3c54b7ee02](https://linux-hardware.org/?probe=3c54b7ee02) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| eMachines     | eME732ZG                    | Notebook    | [4e1d6873ff](https://linux-hardware.org/?probe=4e1d6873ff) | Jun 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [0ec7fedf29](https://linux-hardware.org/?probe=0ec7fedf29) | Jun 24, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [314e344780](https://linux-hardware.org/?probe=314e344780) | Jun 24, 2023 |
| Intel         | H81                         | Desktop     | [65ad18a4bd](https://linux-hardware.org/?probe=65ad18a4bd) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | Notebook    | [a8a9689ea6](https://linux-hardware.org/?probe=a8a9689ea6) | Jun 24, 2023 |
| Lenovo        | ThinkPad L390 20NSS04400    | Notebook    | [feced26491](https://linux-hardware.org/?probe=feced26491) | Jun 23, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [c75670186a](https://linux-hardware.org/?probe=c75670186a) | Jun 23, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [a036f44a4c](https://linux-hardware.org/?probe=a036f44a4c) | Jun 22, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [17db397c48](https://linux-hardware.org/?probe=17db397c48) | Jun 22, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0b8cf1cae7](https://linux-hardware.org/?probe=0b8cf1cae7) | Jun 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [8845f67824](https://linux-hardware.org/?probe=8845f67824) | Jun 22, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d4d7534ac3](https://linux-hardware.org/?probe=d4d7534ac3) | Jun 22, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [0f5435c665](https://linux-hardware.org/?probe=0f5435c665) | Jun 22, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [f96a1a3552](https://linux-hardware.org/?probe=f96a1a3552) | Jun 21, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [5de086be7a](https://linux-hardware.org/?probe=5de086be7a) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [52c4c32098](https://linux-hardware.org/?probe=52c4c32098) | Jun 21, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [873c70b184](https://linux-hardware.org/?probe=873c70b184) | Jun 21, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [d7c44291c1](https://linux-hardware.org/?probe=d7c44291c1) | Jun 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bbfb6ff07f](https://linux-hardware.org/?probe=bbfb6ff07f) | Jun 20, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [b51dda105a](https://linux-hardware.org/?probe=b51dda105a) | Jun 20, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [f2d80b2558](https://linux-hardware.org/?probe=f2d80b2558) | Jun 19, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [f37d67a18d](https://linux-hardware.org/?probe=f37d67a18d) | Jun 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1559b0a68d](https://linux-hardware.org/?probe=1559b0a68d) | Jun 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [22d8476417](https://linux-hardware.org/?probe=22d8476417) | Jun 19, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e2fc6bb607](https://linux-hardware.org/?probe=e2fc6bb607) | Jun 19, 2023 |
| Razer         | Blade Stealth 13 (Early ... | Notebook    | [e3843be450](https://linux-hardware.org/?probe=e3843be450) | Jun 18, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [dcd3e79cb1](https://linux-hardware.org/?probe=dcd3e79cb1) | Jun 18, 2023 |
| HP            | Pavilion dv2                | Notebook    | [3f3b0104a4](https://linux-hardware.org/?probe=3f3b0104a4) | Jun 18, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [17c61c0aee](https://linux-hardware.org/?probe=17c61c0aee) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| HP            | Notebook                    | Notebook    | [60eebb0602](https://linux-hardware.org/?probe=60eebb0602) | Jun 18, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [e01ed6ab42](https://linux-hardware.org/?probe=e01ed6ab42) | Jun 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f7c9224ef1](https://linux-hardware.org/?probe=f7c9224ef1) | Jun 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f553a4e5e7](https://linux-hardware.org/?probe=f553a4e5e7) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [c60ca4bcc4](https://linux-hardware.org/?probe=c60ca4bcc4) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [444f324394](https://linux-hardware.org/?probe=444f324394) | Jun 16, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [93da970965](https://linux-hardware.org/?probe=93da970965) | Jun 16, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [858be00df4](https://linux-hardware.org/?probe=858be00df4) | Jun 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [dc48180bc7](https://linux-hardware.org/?probe=dc48180bc7) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [9536ebc16b](https://linux-hardware.org/?probe=9536ebc16b) | Jun 16, 2023 |
| Dell          | Latitude E6400              | Notebook    | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [00a14ade70](https://linux-hardware.org/?probe=00a14ade70) | Jun 16, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [558c031517](https://linux-hardware.org/?probe=558c031517) | Jun 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [29869b2464](https://linux-hardware.org/?probe=29869b2464) | Jun 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [bdd96d41a7](https://linux-hardware.org/?probe=bdd96d41a7) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [16ad11571a](https://linux-hardware.org/?probe=16ad11571a) | Jun 15, 2023 |
| Lenovo        | ThinkPad T490 20N20032US    | Notebook    | [3df7663e0d](https://linux-hardware.org/?probe=3df7663e0d) | Jun 15, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [c612df2e8c](https://linux-hardware.org/?probe=c612df2e8c) | Jun 15, 2023 |
| ASUSTek       | K52N                        | Notebook    | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| ASRock        | B85M                        | Desktop     | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [8a04ec65f7](https://linux-hardware.org/?probe=8a04ec65f7) | Jun 15, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [7670492b40](https://linux-hardware.org/?probe=7670492b40) | Jun 15, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [dbe7676807](https://linux-hardware.org/?probe=dbe7676807) | Jun 15, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [7ae654d4e2](https://linux-hardware.org/?probe=7ae654d4e2) | Jun 14, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [39e2711f1f](https://linux-hardware.org/?probe=39e2711f1f) | Jun 13, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [2ae3c4aaca](https://linux-hardware.org/?probe=2ae3c4aaca) | Jun 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ad01f2c38d](https://linux-hardware.org/?probe=ad01f2c38d) | Jun 13, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [1361d3551c](https://linux-hardware.org/?probe=1361d3551c) | Jun 12, 2023 |
| Xunlong       | Orange Pi PC                | Soc         | [2a93adb1f0](https://linux-hardware.org/?probe=2a93adb1f0) | Jun 12, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [1fad9d3d52](https://linux-hardware.org/?probe=1fad9d3d52) | Jun 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | Notebook    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [2ea9fd5a4a](https://linux-hardware.org/?probe=2ea9fd5a4a) | Jun 12, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [273795ce3d](https://linux-hardware.org/?probe=273795ce3d) | Jun 12, 2023 |
| Google        | Blorb                       | Notebook    | [0083999b8a](https://linux-hardware.org/?probe=0083999b8a) | Jun 12, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8a9a32ba11](https://linux-hardware.org/?probe=8a9a32ba11) | Jun 12, 2023 |
| Google        | Blorb                       | Notebook    | [516c0548dc](https://linux-hardware.org/?probe=516c0548dc) | Jun 12, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [de08f65c4d](https://linux-hardware.org/?probe=de08f65c4d) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| HP            | 3397                        | Desktop     | [9f71c4173c](https://linux-hardware.org/?probe=9f71c4173c) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| Dell          | Precision 5520              | Notebook    | [bcbd324c4b](https://linux-hardware.org/?probe=bcbd324c4b) | Jun 11, 2023 |
| Dell          | Precision 5520              | Notebook    | [ab408edcbd](https://linux-hardware.org/?probe=ab408edcbd) | Jun 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [d6681f05ec](https://linux-hardware.org/?probe=d6681f05ec) | Jun 11, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0e257c3bd8](https://linux-hardware.org/?probe=0e257c3bd8) | Jun 11, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [fb9e2f9fc8](https://linux-hardware.org/?probe=fb9e2f9fc8) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [92fd36b27a](https://linux-hardware.org/?probe=92fd36b27a) | Jun 09, 2023 |
| Panasonic     | CF-53ASCZGFG                | Notebook    | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [5d8df77ade](https://linux-hardware.org/?probe=5d8df77ade) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [c98ac6e82c](https://linux-hardware.org/?probe=c98ac6e82c) | Jun 08, 2023 |
| MSI           | Z87-G43                     | Desktop     | [554f8ea405](https://linux-hardware.org/?probe=554f8ea405) | Jun 08, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [04d84e44a5](https://linux-hardware.org/?probe=04d84e44a5) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [7879db73f8](https://linux-hardware.org/?probe=7879db73f8) | Jun 08, 2023 |
| Unknown       | Unknown                     | Soc         | [b23e0f6e09](https://linux-hardware.org/?probe=b23e0f6e09) | Jun 08, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [a1e397f4a7](https://linux-hardware.org/?probe=a1e397f4a7) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [022138ad16](https://linux-hardware.org/?probe=022138ad16) | Jun 06, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [16c5f74991](https://linux-hardware.org/?probe=16c5f74991) | Jun 06, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e56988bf8e](https://linux-hardware.org/?probe=e56988bf8e) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [50304f8088](https://linux-hardware.org/?probe=50304f8088) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [fc49284b9f](https://linux-hardware.org/?probe=fc49284b9f) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1df787c227](https://linux-hardware.org/?probe=1df787c227) | Jun 05, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [e22c496628](https://linux-hardware.org/?probe=e22c496628) | Jun 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [83982c1aa9](https://linux-hardware.org/?probe=83982c1aa9) | Jun 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [38882f47af](https://linux-hardware.org/?probe=38882f47af) | Jun 05, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [72eb9f0d86](https://linux-hardware.org/?probe=72eb9f0d86) | Jun 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [580ae6529e](https://linux-hardware.org/?probe=580ae6529e) | Jun 05, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [969354604a](https://linux-hardware.org/?probe=969354604a) | Jun 04, 2023 |
| HP            | 21B4 A01                    | Desktop     | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [8706eff580](https://linux-hardware.org/?probe=8706eff580) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [7af9263ba9](https://linux-hardware.org/?probe=7af9263ba9) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [ae24cbf98d](https://linux-hardware.org/?probe=ae24cbf98d) | Jun 04, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [514b3788ed](https://linux-hardware.org/?probe=514b3788ed) | Jun 04, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e3770a95f6](https://linux-hardware.org/?probe=e3770a95f6) | Jun 04, 2023 |
| Dell          | Latitude D620               | Notebook    | [0e1b7f4320](https://linux-hardware.org/?probe=0e1b7f4320) | Jun 03, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [7a760e7ad6](https://linux-hardware.org/?probe=7a760e7ad6) | Jun 03, 2023 |
| Lenovo        | ThinkPad L490 20Q5002DMH    | Notebook    | [6d42b7647b](https://linux-hardware.org/?probe=6d42b7647b) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [fa4bd41f4b](https://linux-hardware.org/?probe=fa4bd41f4b) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [1a4437e831](https://linux-hardware.org/?probe=1a4437e831) | Jun 02, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [5e3a2796a9](https://linux-hardware.org/?probe=5e3a2796a9) | Jun 01, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [c9409c532d](https://linux-hardware.org/?probe=c9409c532d) | Jun 01, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| HP            | 845A                        | Desktop     | [b68054952b](https://linux-hardware.org/?probe=b68054952b) | Jun 01, 2023 |
| Supermicro    | X8DTU                       | Server      | [2e1d03c7da](https://linux-hardware.org/?probe=2e1d03c7da) | Jun 01, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| Unknown       | Unknown                     | Phone       | [bd6f4745f0](https://linux-hardware.org/?probe=bd6f4745f0) | Jun 01, 2023 |
| HP            | 82B5                        | All in one  | [77ecbfa91c](https://linux-hardware.org/?probe=77ecbfa91c) | Jun 01, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [b819db60d1](https://linux-hardware.org/?probe=b819db60d1) | Jun 01, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| Inventec      | 0PY33N A01                  | Mini pc     | [01452a68b3](https://linux-hardware.org/?probe=01452a68b3) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [1903d991a3](https://linux-hardware.org/?probe=1903d991a3) | May 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [c02695ea7d](https://linux-hardware.org/?probe=c02695ea7d) | May 30, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1df34e179b](https://linux-hardware.org/?probe=1df34e179b) | May 30, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ca1cea162c](https://linux-hardware.org/?probe=ca1cea162c) | May 29, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [edfe02a7ae](https://linux-hardware.org/?probe=edfe02a7ae) | May 29, 2023 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [92b569d076](https://linux-hardware.org/?probe=92b569d076) | May 28, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [4d002c31be](https://linux-hardware.org/?probe=4d002c31be) | May 28, 2023 |
| Dell          | Latitude 7480               | Notebook    | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [c51af54d34](https://linux-hardware.org/?probe=c51af54d34) | May 28, 2023 |
| Gateway       | DT55                        | Desktop     | [22d84550c6](https://linux-hardware.org/?probe=22d84550c6) | May 28, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c2408a1885](https://linux-hardware.org/?probe=c2408a1885) | May 28, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [d06e7ba405](https://linux-hardware.org/?probe=d06e7ba405) | May 28, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [9099d721d2](https://linux-hardware.org/?probe=9099d721d2) | May 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [8311d009bd](https://linux-hardware.org/?probe=8311d009bd) | May 27, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [c8c8087ee8](https://linux-hardware.org/?probe=c8c8087ee8) | May 27, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [4e7b273239](https://linux-hardware.org/?probe=4e7b273239) | May 27, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [2baf5b889b](https://linux-hardware.org/?probe=2baf5b889b) | May 26, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a7fbdc21bc](https://linux-hardware.org/?probe=a7fbdc21bc) | May 26, 2023 |
| Dell          | Latitude E5440              | Notebook    | [4a5501c365](https://linux-hardware.org/?probe=4a5501c365) | May 26, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [750cb90d83](https://linux-hardware.org/?probe=750cb90d83) | May 26, 2023 |
| Acer          | WG43M                       | Desktop     | [9afcfc4a44](https://linux-hardware.org/?probe=9afcfc4a44) | May 26, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [53db1863ab](https://linux-hardware.org/?probe=53db1863ab) | May 25, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [0466edde83](https://linux-hardware.org/?probe=0466edde83) | May 25, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [d72352c0dc](https://linux-hardware.org/?probe=d72352c0dc) | May 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [654aa3909f](https://linux-hardware.org/?probe=654aa3909f) | May 24, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [06333c9c97](https://linux-hardware.org/?probe=06333c9c97) | May 24, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [dd15a8197e](https://linux-hardware.org/?probe=dd15a8197e) | May 24, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [6531b22151](https://linux-hardware.org/?probe=6531b22151) | May 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [ba72bf9d52](https://linux-hardware.org/?probe=ba72bf9d52) | May 24, 2023 |
| Google        | Snappy                      | Notebook    | [8e9ad9e9d3](https://linux-hardware.org/?probe=8e9ad9e9d3) | May 24, 2023 |
| Lenovo        | Unknown                     | Notebook    | [e7148e7a18](https://linux-hardware.org/?probe=e7148e7a18) | May 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [b5e28ef2ab](https://linux-hardware.org/?probe=b5e28ef2ab) | May 23, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [7b6c90320b](https://linux-hardware.org/?probe=7b6c90320b) | May 23, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [d8d33293ef](https://linux-hardware.org/?probe=d8d33293ef) | May 23, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e4f2e7ecb6](https://linux-hardware.org/?probe=e4f2e7ecb6) | May 23, 2023 |
| HP            | 530                         | Notebook    | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b7fbda70d3](https://linux-hardware.org/?probe=b7fbda70d3) | May 23, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [74a0ea4304](https://linux-hardware.org/?probe=74a0ea4304) | May 22, 2023 |
| MSI           | B360M PRO-VDH               | Desktop     | [93a41eca5e](https://linux-hardware.org/?probe=93a41eca5e) | May 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [46de86898c](https://linux-hardware.org/?probe=46de86898c) | May 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [ef28026334](https://linux-hardware.org/?probe=ef28026334) | May 22, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e7af79968d](https://linux-hardware.org/?probe=e7af79968d) | May 22, 2023 |
| ASUSTek       | K84L                        | Notebook    | [5f14f3b293](https://linux-hardware.org/?probe=5f14f3b293) | May 21, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [b160fbf41e](https://linux-hardware.org/?probe=b160fbf41e) | May 21, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [cc90a5ca05](https://linux-hardware.org/?probe=cc90a5ca05) | May 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [03b17bc271](https://linux-hardware.org/?probe=03b17bc271) | May 21, 2023 |
| HP            | Unknown                     | Notebook    | [8894bf0f31](https://linux-hardware.org/?probe=8894bf0f31) | May 21, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [04ea462ce6](https://linux-hardware.org/?probe=04ea462ce6) | May 21, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [2e68f6cae7](https://linux-hardware.org/?probe=2e68f6cae7) | May 21, 2023 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [f7d7036598](https://linux-hardware.org/?probe=f7d7036598) | May 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [72adb50172](https://linux-hardware.org/?probe=72adb50172) | May 20, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [50e85498e7](https://linux-hardware.org/?probe=50e85498e7) | May 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [cf5c419d13](https://linux-hardware.org/?probe=cf5c419d13) | May 20, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [87e60904b9](https://linux-hardware.org/?probe=87e60904b9) | May 20, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [fc125408b5](https://linux-hardware.org/?probe=fc125408b5) | May 20, 2023 |
| Dell          | 0F3KHR A01                  | Desktop     | [c48ab194c6](https://linux-hardware.org/?probe=c48ab194c6) | May 20, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [8c6b9dc52f](https://linux-hardware.org/?probe=8c6b9dc52f) | May 19, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [db9774a799](https://linux-hardware.org/?probe=db9774a799) | May 19, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [76bae0c7fb](https://linux-hardware.org/?probe=76bae0c7fb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Intel         | NUC12WSBi7 M46422-304       | Mini pc     | [b63f2ef351](https://linux-hardware.org/?probe=b63f2ef351) | May 18, 2023 |
| Medion        | BTDD-TI                     | All in one  | [cc45e1f2f4](https://linux-hardware.org/?probe=cc45e1f2f4) | May 18, 2023 |
| MSI           | GL75 9SE                    | Notebook    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [99d6173179](https://linux-hardware.org/?probe=99d6173179) | May 18, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [bc0a4ba851](https://linux-hardware.org/?probe=bc0a4ba851) | May 18, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | Desktop     | [af1e17cc95](https://linux-hardware.org/?probe=af1e17cc95) | May 17, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [89d938fcef](https://linux-hardware.org/?probe=89d938fcef) | May 17, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [200610da74](https://linux-hardware.org/?probe=200610da74) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Pegatron      | VIOLET                      | Desktop     | [197ec890d6](https://linux-hardware.org/?probe=197ec890d6) | May 16, 2023 |
| Pegatron      | VIOLET                      | Desktop     | [fa6dc417d4](https://linux-hardware.org/?probe=fa6dc417d4) | May 16, 2023 |
| Foxconn       | P35A01                      | Desktop     | [d3f10a59ba](https://linux-hardware.org/?probe=d3f10a59ba) | May 16, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d4ad39c5d7](https://linux-hardware.org/?probe=d4ad39c5d7) | May 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4a352d010e](https://linux-hardware.org/?probe=4a352d010e) | May 15, 2023 |
| Dell          | Latitude 3190               | Notebook    | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0aa84055bf](https://linux-hardware.org/?probe=0aa84055bf) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [3466945196](https://linux-hardware.org/?probe=3466945196) | May 15, 2023 |
| HP            | 339A                        | Desktop     | [35fdefb4eb](https://linux-hardware.org/?probe=35fdefb4eb) | May 15, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [70b604bc30](https://linux-hardware.org/?probe=70b604bc30) | May 14, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Fujitsu       | CELSIUS H760                | Notebook    | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| Lenovo        | ThinkCentre M58 7627AD5     | Desktop     | [e0b4de3daf](https://linux-hardware.org/?probe=e0b4de3daf) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [660bd404a0](https://linux-hardware.org/?probe=660bd404a0) | May 14, 2023 |
| ASUSTek       | K53BR                       | Notebook    | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [091a42a1c0](https://linux-hardware.org/?probe=091a42a1c0) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [309a617781](https://linux-hardware.org/?probe=309a617781) | May 13, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [55abeba9a3](https://linux-hardware.org/?probe=55abeba9a3) | May 13, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [d2dbc10885](https://linux-hardware.org/?probe=d2dbc10885) | May 13, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [82dbe1cdf7](https://linux-hardware.org/?probe=82dbe1cdf7) | May 13, 2023 |
| Fujitsu       | CELSIUS H760                | Notebook    | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | Notebook    | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [afb2844cb4](https://linux-hardware.org/?probe=afb2844cb4) | May 13, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [8fdc05a6ad](https://linux-hardware.org/?probe=8fdc05a6ad) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [6950584e4c](https://linux-hardware.org/?probe=6950584e4c) | May 12, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [29b8cfc7e6](https://linux-hardware.org/?probe=29b8cfc7e6) | May 12, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9f88d81e33](https://linux-hardware.org/?probe=9f88d81e33) | May 12, 2023 |
| HP            | ProBook 4535s               | Notebook    | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | 3047h                       | Desktop     | [bb0087d307](https://linux-hardware.org/?probe=bb0087d307) | May 12, 2023 |
| Dell          | Latitude 7390               | Notebook    | [cbd8c5fdbe](https://linux-hardware.org/?probe=cbd8c5fdbe) | May 12, 2023 |
| Dell          | Latitude 7390               | Notebook    | [5677bfdac5](https://linux-hardware.org/?probe=5677bfdac5) | May 12, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [b9a3dfd029](https://linux-hardware.org/?probe=b9a3dfd029) | May 12, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [39f854e5de](https://linux-hardware.org/?probe=39f854e5de) | May 11, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [9945f20a3a](https://linux-hardware.org/?probe=9945f20a3a) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4ca3ad7158](https://linux-hardware.org/?probe=4ca3ad7158) | May 11, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [9346ce422f](https://linux-hardware.org/?probe=9346ce422f) | May 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [5bfb32e683](https://linux-hardware.org/?probe=5bfb32e683) | May 11, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 595       | 10.23%  |
| OpenMandriva 4.2             | 317       | 5.45%   |
| Ubuntu 22.04                 | 284       | 4.88%   |
| Ubuntu 18.04                 | 281       | 4.83%   |
| OpenMandriva 4.3             | 235       | 4.04%   |
| Debian 11                    | 161       | 2.77%   |
| Arch Rolling                 | 149       | 2.56%   |
| OpenMandriva 23.03           | 101       | 1.74%   |
| ROSA R10                     | 98        | 1.69%   |
| OpenMandriva 23.01           | 92        | 1.58%   |
| Zorin 16                     | 86        | 1.48%   |
| Linux Mint 21.1              | 79        | 1.36%   |
| Manjaro                      | 76        | 1.31%   |
| Linux Mint 20.3              | 72        | 1.24%   |
| Fedora 38                    | 72        | 1.24%   |
| ROSA R9                      | 70        | 1.2%    |
| ROSA R11                     | 69        | 1.19%   |
| Arch                         | 68        | 1.17%   |
| Fedora 37                    | 67        | 1.15%   |
| Linux Mint 20.1              | 66        | 1.13%   |
| ROSA R11.1                   | 65        | 1.12%   |
| KDE neon 20.04               | 64        | 1.1%    |
| Pop!_OS 22.04                | 61        | 1.05%   |
| Fedora 36                    | 60        | 1.03%   |
| Ubuntu 20.10                 | 57        | 0.98%   |
| Linux Mint 20.2              | 53        | 0.91%   |
| Ubuntu 21.04                 | 50        | 0.86%   |
| Linux Mint 20                | 49        | 0.84%   |
| Linux Mint 19.3              | 49        | 0.84%   |
| Ubuntu 19.10                 | 48        | 0.83%   |
| Ubuntu 22.10                 | 46        | 0.79%   |
| Ubuntu 21.10                 | 44        | 0.76%   |
| Fedora 35                    | 43        | 0.74%   |
| Debian 12                    | 43        | 0.74%   |
| ROSA R8                      | 42        | 0.72%   |
| Fedora 33                    | 41        | 0.7%    |
| openSUSE Tumbleweed-XXXXXXXX | 40        | 0.69%   |
| Linux Mint 21                | 40        | 0.69%   |
| Fedora 34                    | 40        | 0.69%   |
| Debian 10                    | 40        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1418      | 26.44%  |
| OpenMandriva  | 788       | 14.69%  |
| Linux Mint    | 443       | 8.26%   |
| Fedora        | 367       | 6.84%   |
| ROSA          | 336       | 6.27%   |
| Debian        | 272       | 5.07%   |
| Arch          | 209       | 3.9%    |
| Manjaro       | 205       | 3.82%   |
| Pop!_OS       | 158       | 2.95%   |
| Zorin         | 125       | 2.33%   |
| Kubuntu       | 109       | 2.03%   |
| KDE neon      | 95        | 1.77%   |
| Xubuntu       | 83        | 1.55%   |
| openSUSE      | 54        | 1.01%   |
| Kali          | 51        | 0.95%   |
| Gentoo        | 50        | 0.93%   |
| ArcoLinux     | 41        | 0.76%   |
| Lubuntu       | 39        | 0.73%   |
| Endless       | 37        | 0.69%   |
| Elementary    | 36        | 0.67%   |
| EndeavourOS   | 34        | 0.63%   |
| LMDE          | 33        | 0.62%   |
| SteamOS       | 28        | 0.52%   |
| Ubuntu Unity  | 22        | 0.41%   |
| Ubuntu MATE   | 22        | 0.41%   |
| MX            | 21        | 0.39%   |
| Clear Linux   | 21        | 0.39%   |
| Nobara        | 20        | 0.37%   |
| BlackPanther  | 18        | 0.34%   |
| Garuda Linux  | 16        | 0.3%    |
| Xero          | 15        | 0.28%   |
| CentOS        | 15        | 0.28%   |
| Ubuntu Budgie | 14        | 0.26%   |
| Peppermint    | 10        | 0.19%   |
| LinuxFX       | 10        | 0.19%   |
| Raspbian      | 9         | 0.17%   |
| NixOS         | 8         | 0.15%   |
| Linux Lite    | 8         | 0.15%   |
| EuroLinux     | 7         | 0.13%   |
| Parrot        | 6         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 303       | 4.66%   |
| 5.16.7-desktop-1omv4003         | 214       | 3.29%   |
| 6.2.6-desktop-1omv2390          | 96        | 1.48%   |
| 6.1.1-desktop-1omv2290          | 82        | 1.26%   |
| 5.4.0-42-generic                | 78        | 1.2%    |
| 5.15.0-56-generic               | 60        | 0.92%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 54        | 0.83%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 53        | 0.82%   |
| 5.15.0-43-generic               | 41        | 0.63%   |
| 5.4.0-26-generic                | 40        | 0.62%   |
| 5.15.0-58-generic               | 39        | 0.6%    |
| 4.15.0-desktop-45.1rosa-x86_64  | 39        | 0.6%    |
| 5.4.0-52-generic                | 38        | 0.58%   |
| 5.4.0-48-generic                | 36        | 0.55%   |
| 5.15.0-52-generic               | 36        | 0.55%   |
| 5.19.0-35-generic               | 35        | 0.54%   |
| 5.4.0-58-generic                | 33        | 0.51%   |
| 5.4.0-29-generic                | 30        | 0.46%   |
| 5.3.0-46-generic                | 30        | 0.46%   |
| 6.4.11-desktop-1omv2390         | 29        | 0.45%   |
| 5.4.0-54-generic                | 29        | 0.45%   |
| 5.19.0-32-generic               | 29        | 0.45%   |
| 5.8.0-43-generic                | 27        | 0.42%   |
| 5.13.0-39-generic               | 27        | 0.42%   |
| 5.11.0-37-generic               | 27        | 0.42%   |
| 5.4.0-40-generic                | 26        | 0.4%    |
| 5.4.0-37-generic                | 25        | 0.38%   |
| 5.16.13-desktop-1omv4003        | 25        | 0.38%   |
| 5.15.0-48-generic               | 25        | 0.38%   |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 24        | 0.37%   |
| 5.4.0-66-generic                | 23        | 0.35%   |
| 5.4.0-33-generic                | 23        | 0.35%   |
| 5.13.0-27-generic               | 23        | 0.35%   |
| 5.3.0-42-generic                | 22        | 0.34%   |
| 5.15.0-60-generic               | 22        | 0.34%   |
| 5.11.0-27-generic               | 22        | 0.34%   |
| 5.0.0-37-generic                | 22        | 0.34%   |
| 5.10.0-21-amd64                 | 21        | 0.32%   |
| 5.8.0-48-generic                | 20        | 0.31%   |
| 5.4.0-91-generic                | 20        | 0.31%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 771       | 12.59%  |
| 5.15.0  | 464       | 7.58%   |
| 5.10.14 | 305       | 4.98%   |
| 4.15.0  | 288       | 4.7%    |
| 5.11.0  | 223       | 3.64%   |
| 5.8.0   | 222       | 3.63%   |
| 5.16.7  | 217       | 3.54%   |
| 5.13.0  | 204       | 3.33%   |
| 5.10.0  | 170       | 2.78%   |
| 5.19.0  | 169       | 2.76%   |
| 5.3.0   | 166       | 2.71%   |
| 6.2.6   | 118       | 1.93%   |
| 5.0.0   | 101       | 1.65%   |
| 6.2.0   | 92        | 1.5%    |
| 4.18.0  | 91        | 1.49%   |
| 6.1.1   | 84        | 1.37%   |
| 4.9.60  | 66        | 1.08%   |
| 6.1.0   | 63        | 1.03%   |
| 4.9.20  | 62        | 1.01%   |
| 4.19.0  | 55        | 0.9%    |
| 5.14.0  | 37        | 0.6%    |
| 6.4.11  | 33        | 0.54%   |
| 4.1.34  | 32        | 0.52%   |
| 4.1.38  | 28        | 0.46%   |
| 5.16.13 | 27        | 0.44%   |
| 6.0.0   | 26        | 0.42%   |
| 5.17.5  | 20        | 0.33%   |
| 5.11.12 | 19        | 0.31%   |
| 5.9.0   | 18        | 0.29%   |
| 5.4.32  | 18        | 0.29%   |
| 6.0.12  | 17        | 0.28%   |
| 6.5.5   | 16        | 0.26%   |
| 4.9.76  | 16        | 0.26%   |
| 4.9.155 | 16        | 0.26%   |
| 4.9.124 | 16        | 0.26%   |
| 6.0.7   | 15        | 0.24%   |
| 5.17.0  | 15        | 0.24%   |
| 6.3.5   | 14        | 0.23%   |
| 6.0.8   | 14        | 0.23%   |
| 6.1.12  | 13        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 873       | 14.72%  |
| 5.15    | 608       | 10.25%  |
| 5.10    | 590       | 9.95%   |
| 5.16    | 313       | 5.28%   |
| 6.2     | 296       | 4.99%   |
| 5.11    | 289       | 4.87%   |
| 4.15    | 288       | 4.86%   |
| 5.8     | 280       | 4.72%   |
| 6.1     | 266       | 4.48%   |
| 5.13    | 235       | 3.96%   |
| 5.19    | 227       | 3.83%   |
| 5.3     | 186       | 3.14%   |
| 4.9     | 184       | 3.1%    |
| 6.0     | 131       | 2.21%   |
| 5.0     | 111       | 1.87%   |
| 4.18    | 103       | 1.74%   |
| 5.14    | 98        | 1.65%   |
| 6.4     | 96        | 1.62%   |
| 5.17    | 80        | 1.35%   |
| 5.9     | 74        | 1.25%   |
| 5.6     | 70        | 1.18%   |
| 5.18    | 70        | 1.18%   |
| 6.3     | 68        | 1.15%   |
| 4.19    | 68        | 1.15%   |
| 4.1     | 63        | 1.06%   |
| 6.5     | 62        | 1.05%   |
| 5.12    | 60        | 1.01%   |
| 5.5     | 39        | 0.66%   |
| 5.7     | 35        | 0.59%   |
| 4.4     | 17        | 0.29%   |
| 5.1     | 8         | 0.13%   |
| 3.10    | 7         | 0.12%   |
| 5.2     | 5         | 0.08%   |
| 4.20    | 4         | 0.07%   |
| 6.6     | 3         | 0.05%   |
| 4.16    | 3         | 0.05%   |
| 4.13    | 3         | 0.05%   |
| 4.8     | 2         | 0.03%   |
| 4.7     | 2         | 0.03%   |
| 4.14    | 2         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4944      | 96.04%  |
| i686    | 151       | 2.93%   |
| aarch64 | 27        | 0.52%   |
| armv7l  | 19        | 0.37%   |
| armv8l  | 3         | 0.06%   |
| armv6l  | 2         | 0.04%   |
| ppc64   | 1         | 0.02%   |
| ppc     | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1954      | 35.97%  |
| KDE5            | 1444      | 26.58%  |
| Unknown         | 506       | 9.31%   |
| XFCE            | 379       | 6.98%   |
| X-Cinnamon      | 312       | 5.74%   |
| KDE4            | 177       | 3.26%   |
| MATE            | 137       | 2.52%   |
| KDE             | 126       | 2.32%   |
| LXQt            | 77        | 1.42%   |
| Cinnamon        | 70        | 1.29%   |
| LXDE            | 50        | 0.92%   |
| Pantheon        | 35        | 0.64%   |
| i3              | 35        | 0.64%   |
| Unity           | 25        | 0.46%   |
| Budgie          | 23        | 0.42%   |
| Deepin          | 16        | 0.29%   |
| GNOME Flashback | 12        | 0.22%   |
| Hyprland        | 8         | 0.15%   |
| GNOME Classic   | 7         | 0.13%   |
| awesome         | 6         | 0.11%   |
| sway            | 5         | 0.09%   |
| openbox         | 5         | 0.09%   |
| qtile           | 4         | 0.07%   |
| icewm           | 3         | 0.06%   |
| fluxbox         | 3         | 0.06%   |
| DWM             | 3         | 0.06%   |
| trinity         | 2         | 0.04%   |
| xmonad          | 1         | 0.02%   |
| stumpwm         | 1         | 0.02%   |
| ratflow         | 1         | 0.02%   |
| qt5ct           | 1         | 0.02%   |
| jwm             | 1         | 0.02%   |
| GNUstep         | 1         | 0.02%   |
| gnome-xorg      | 1         | 0.02%   |
| Endless:GNOME   | 1         | 0.02%   |
| BunsenLabs      | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 4131      | 77.48%  |
| Wayland     | 845       | 15.85%  |
| Unknown     | 244       | 4.58%   |
| Tty         | 111       | 2.08%   |
| Unspecified | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2143      | 39.66%  |
| SDDM    | 1336      | 24.73%  |
| GDM     | 568       | 10.51%  |
| GDM3    | 503       | 9.31%   |
| LightDM | 485       | 8.98%   |
| KDM     | 187       | 3.46%   |
| TDM     | 152       | 2.81%   |
| XDM     | 11        | 0.2%    |
| Ly      | 4         | 0.07%   |
| SLiM    | 3         | 0.06%   |
| LXDM    | 3         | 0.06%   |
| SLIMSKI | 2         | 0.04%   |
| NODM    | 2         | 0.04%   |
| MDM     | 2         | 0.04%   |
| SU      | 1         | 0.02%   |
| LY-DM   | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pl_PL       | 2887      | 53.96%  |
| en_US       | 1420      | 26.54%  |
| Unknown     | 652       | 12.19%  |
| en_GB       | 150       | 2.8%    |
| C           | 103       | 1.93%   |
| ru_RU       | 36        | 0.67%   |
| szl_PL      | 12        | 0.22%   |
| de_DE       | 11        | 0.21%   |
| uk_UA       | 10        | 0.19%   |
| ru_UA       | 9         | 0.17%   |
| en_CA       | 8         | 0.15%   |
| en_IE       | 6         | 0.11%   |
| POSIX       | 5         | 0.09%   |
| fr_FR       | 5         | 0.09%   |
| en_DK       | 4         | 0.07%   |
| en_AG       | 4         | 0.07%   |
| it_IT       | 3         | 0.06%   |
| C.UTF8      | 3         | 0.06%   |
| nl_NL       | 2         | 0.04%   |
| hu_HU       | 2         | 0.04%   |
| en_US.utf-8 | 2         | 0.04%   |
| en_IN       | 2         | 0.04%   |
| sv_SE       | 1         | 0.02%   |
| sk_SK       | 1         | 0.02%   |
| pl_PL.UTF8  | 1         | 0.02%   |
| es_ES       | 1         | 0.02%   |
| es_AR       | 1         | 0.02%   |
| en_US.UTF8  | 1         | 0.02%   |
| en_SE       | 1         | 0.02%   |
| en_AU       | 1         | 0.02%   |
| el_GR       | 1         | 0.02%   |
| de_CH       | 1         | 0.02%   |
| Default     | 1         | 0.02%   |
| be_BY       | 1         | 0.02%   |
| af_ZA       | 1         | 0.02%   |
| aa_DJ       | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2824      | 53.55%  |
| EFI  | 2450      | 46.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3596      | 66.96%  |
| Overlay  | 732       | 13.63%  |
| Btrfs    | 506       | 9.42%   |
| Unknown  | 299       | 5.57%   |
| Tmpfs    | 81        | 1.51%   |
| Xfs      | 78        | 1.45%   |
| Zfs      | 35        | 0.65%   |
| F2fs     | 20        | 0.37%   |
| Ext2     | 7         | 0.13%   |
| Ext3     | 6         | 0.11%   |
| Rootfs   | 3         | 0.06%   |
| Jfs      | 3         | 0.06%   |
| XXXXX    | 1         | 0.02%   |
| SquXshfs | 1         | 0.02%   |
| Bcachefs | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2347      | 43.98%  |
| GPT     | 2082      | 39.02%  |
| MBR     | 907       | 17%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4305      | 81.32%  |
| Yes       | 989       | 18.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3460      | 65.75%  |
| Yes       | 1802      | 34.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 916       | 17.82%  |
| Dell                    | 815       | 15.86%  |
| ASUSTek Computer        | 781       | 15.2%   |
| Hewlett-Packard         | 636       | 12.38%  |
| Gigabyte Technology     | 436       | 8.48%   |
| MSI                     | 381       | 7.41%   |
| Acer                    | 215       | 4.18%   |
| ASRock                  | 177       | 3.44%   |
| Samsung Electronics     | 84        | 1.63%   |
| Toshiba                 | 83        | 1.62%   |
| Fujitsu                 | 57        | 1.11%   |
| Apple                   | 48        | 0.93%   |
| Sony                    | 37        | 0.72%   |
| Intel                   | 35        | 0.68%   |
| HUAWEI                  | 35        | 0.68%   |
| Fujitsu Siemens         | 34        | 0.66%   |
| Unknown                 | 26        | 0.51%   |
| Raspberry Pi Foundation | 25        | 0.49%   |
| Google                  | 25        | 0.49%   |
| Valve                   | 23        | 0.45%   |
| Packard Bell            | 16        | 0.31%   |
| Notebook                | 16        | 0.31%   |
| Medion                  | 16        | 0.31%   |
| Foxconn                 | 14        | 0.27%   |
| Kiano                   | 12        | 0.23%   |
| eMachines               | 11        | 0.21%   |
| Timi                    | 9         | 0.18%   |
| Inventec                | 9         | 0.18%   |
| AMI                     | 7         | 0.14%   |
| Huanan                  | 6         | 0.12%   |
| ZOTAC                   | 5         | 0.1%    |
| Supermicro              | 5         | 0.1%    |
| mPTech                  | 5         | 0.1%    |
| Kruger&Matz             | 4         | 0.08%   |
| GPU Company             | 4         | 0.08%   |
| Gateway                 | 4         | 0.08%   |
| ECS                     | 4         | 0.08%   |
| Alienware               | 4         | 0.08%   |
| Xunlong                 | 3         | 0.06%   |
| XIAOMI                  | 3         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 51        | 0.99%   |
| ASUS All Series                     | 35        | 0.68%   |
| Dell Inspiron 3451                  | 31        | 0.6%    |
| Valve Jupiter                       | 23        | 0.45%   |
| MSI MS-7B86                         | 18        | 0.35%   |
| Gigabyte B450M DS3H                 | 18        | 0.35%   |
| ASUS SABERTOOTH Z77                 | 18        | 0.35%   |
| Dell Latitude E6400                 | 17        | 0.33%   |
| MSI MS-7817                         | 16        | 0.31%   |
| Dell OptiPlex 780                   | 15        | 0.29%   |
| Dell Latitude E6540                 | 15        | 0.29%   |
| MSI MS-7C37                         | 13        | 0.25%   |
| MSI MS-7C02                         | 13        | 0.25%   |
| Lenovo G50-30 80G0                  | 13        | 0.25%   |
| HP Pavilion dv7                     | 12        | 0.23%   |
| Dell Latitude 5480                  | 12        | 0.23%   |
| Dell OptiPlex 7010                  | 11        | 0.21%   |
| Dell Latitude E6430                 | 11        | 0.21%   |
| Dell Latitude D630                  | 11        | 0.21%   |
| Dell Latitude 5490                  | 11        | 0.21%   |
| ASUS X555LJ                         | 11        | 0.21%   |
| MSI MS-7B79                         | 10        | 0.19%   |
| Lenovo Legion Y530-15ICH 81FV       | 10        | 0.19%   |
| Lenovo G580 20150                   | 10        | 0.19%   |
| Gigabyte B450 AORUS ELITE           | 10        | 0.19%   |
| Dell Latitude E6420                 | 10        | 0.19%   |
| MSI MS-7721                         | 9         | 0.18%   |
| Lenovo G510 20238                   | 9         | 0.18%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 9         | 0.18%   |
| HP Notebook                         | 9         | 0.18%   |
| HP 15                               | 9         | 0.18%   |
| Gigabyte B85M-D3H                   | 9         | 0.18%   |
| Gigabyte B550 AORUS ELITE V2        | 9         | 0.18%   |
| Dell OptiPlex 755                   | 9         | 0.18%   |
| Dell Latitude E7440                 | 9         | 0.18%   |
| Dell Latitude 5420                  | 9         | 0.18%   |
| ASUS TUF Gaming X570-PLUS           | 9         | 0.18%   |
| MSI MS-7A38                         | 8         | 0.16%   |
| MSI MS-7816                         | 8         | 0.16%   |
| Lenovo Legion Y540-15IRH 81SX       | 8         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 381       | 7.41%   |
| Dell Latitude         | 331       | 6.44%   |
| Dell Inspiron         | 167       | 3.25%   |
| Lenovo IdeaPad        | 166       | 3.23%   |
| Acer Aspire           | 128       | 2.49%   |
| HP EliteBook          | 112       | 2.18%   |
| Dell OptiPlex         | 111       | 2.16%   |
| HP Pavilion           | 107       | 2.08%   |
| ASUS PRIME            | 78        | 1.52%   |
| HP Compaq             | 73        | 1.42%   |
| HP ProBook            | 72        | 1.4%    |
| Dell Precision        | 71        | 1.38%   |
| Toshiba Satellite     | 66        | 1.28%   |
| Lenovo Legion         | 64        | 1.25%   |
| ASUS TUF              | 61        | 1.19%   |
| ASUS ROG              | 51        | 0.99%   |
| Unknown               | 51        | 0.99%   |
| Dell Vostro           | 45        | 0.88%   |
| Lenovo ThinkCentre    | 43        | 0.84%   |
| ASUS VivoBook         | 41        | 0.8%    |
| HP Laptop             | 37        | 0.72%   |
| Dell XPS              | 35        | 0.68%   |
| ASUS All              | 35        | 0.68%   |
| ASUS ASUS             | 29        | 0.56%   |
| Gigabyte B450M        | 27        | 0.53%   |
| RPi Raspberry         | 25        | 0.49%   |
| Valve Jupiter         | 23        | 0.45%   |
| HP EliteDesk          | 23        | 0.45%   |
| HP 250                | 21        | 0.41%   |
| Fujitsu LIFEBOOK      | 21        | 0.41%   |
| Fujitsu ESPRIMO       | 20        | 0.39%   |
| ASUS SABERTOOTH       | 20        | 0.39%   |
| Lenovo Yoga           | 19        | 0.37%   |
| MSI MS-7B86           | 18        | 0.35%   |
| HP ZBook              | 17        | 0.33%   |
| Packard Bell EasyNote | 16        | 0.31%   |
| MSI MS-7817           | 16        | 0.31%   |
| Gigabyte B550         | 16        | 0.31%   |
| Acer Nitro            | 16        | 0.31%   |
| Lenovo ThinkBook      | 15        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 446       | 8.68%   |
| 2012    | 437       | 8.5%    |
| 2013    | 419       | 8.15%   |
| 2019    | 408       | 7.94%   |
| 2020    | 389       | 7.57%   |
| 2011    | 367       | 7.14%   |
| 2014    | 334       | 6.5%    |
| 2017    | 305       | 5.94%   |
| 2015    | 283       | 5.51%   |
| 2008    | 271       | 5.27%   |
| 2021    | 267       | 5.2%    |
| 2010    | 256       | 4.98%   |
| 2016    | 226       | 4.4%    |
| 2009    | 225       | 4.38%   |
| 2007    | 198       | 3.85%   |
| 2022    | 139       | 2.7%    |
| 2006    | 79        | 1.54%   |
| Unknown | 43        | 0.84%   |
| 2023    | 29        | 0.56%   |
| 2005    | 11        | 0.21%   |
| 2004    | 6         | 0.12%   |
| 2001    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3061      | 59.56%  |
| Desktop        | 1849      | 35.98%  |
| Convertible    | 64        | 1.25%   |
| Mini pc        | 44        | 0.86%   |
| System on chip | 43        | 0.84%   |
| Server         | 30        | 0.58%   |
| All in one     | 23        | 0.45%   |
| Tablet         | 19        | 0.37%   |
| Phone          | 6         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4866      | 94.03%  |
| Enabled  | 309       | 5.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5110      | 99.44%  |
| Yes  | 29        | 0.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1085      | 20.65%  |
| 3.01-4.0        | 1075      | 20.46%  |
| 16.01-24.0      | 970       | 18.47%  |
| 8.01-16.0       | 959       | 18.26%  |
| 32.01-64.0      | 564       | 10.74%  |
| 1.01-2.0        | 207       | 3.94%   |
| 2.01-3.0        | 125       | 2.38%   |
| 64.01-256.0     | 123       | 2.34%   |
| 24.01-32.0      | 94        | 1.79%   |
| 0.51-1.0        | 43        | 0.82%   |
| More than 256.0 | 4         | 0.08%   |
| 0.01-0.5        | 4         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 2094      | 35.75%  |
| 2.01-3.0        | 1281      | 21.87%  |
| 4.01-8.0        | 846       | 14.44%  |
| 3.01-4.0        | 689       | 11.76%  |
| 0.51-1.0        | 508       | 8.67%   |
| 8.01-16.0       | 263       | 4.49%   |
| 0.01-0.5        | 97        | 1.66%   |
| 16.01-24.0      | 53        | 0.9%    |
| 24.01-32.0      | 14        | 0.24%   |
| Unknown         | 5         | 0.09%   |
| 32.01-64.0      | 4         | 0.07%   |
| 64.01-256.0     | 3         | 0.05%   |
| More than 256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3139      | 58.62%  |
| 2       | 1349      | 25.19%  |
| 3       | 462       | 8.63%   |
| 4       | 181       | 3.38%   |
| 5       | 78        | 1.46%   |
| 0       | 77        | 1.44%   |
| 6       | 33        | 0.62%   |
| 7       | 17        | 0.32%   |
| 8       | 7         | 0.13%   |
| 11      | 3         | 0.06%   |
| 9       | 3         | 0.06%   |
| 10      | 2         | 0.04%   |
| Unknown | 2         | 0.04%   |
| 13      | 1         | 0.02%   |
| 12      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3023      | 58.03%  |
| Yes       | 2186      | 41.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4605      | 89.33%  |
| No        | 550       | 10.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3896      | 75.13%  |
| No        | 1290      | 24.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2977      | 56.93%  |
| No        | 2252      | 43.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 5139      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 1185      | 20.98%  |
| Krakow                 | 417       | 7.38%   |
| Wroclaw                | 338       | 5.99%   |
| Poznan                 | 283       | 5.01%   |
| Gdansk                 | 189       | 3.35%   |
| Lodz                   | 172       | 3.05%   |
| Katowice               | 149       | 2.64%   |
| Lublin                 | 81        | 1.43%   |
| Gdynia                 | 74        | 1.31%   |
| Szczecin               | 62        | 1.1%    |
| Bialystok              | 53        | 0.94%   |
| Gliwice                | 44        | 0.78%   |
| Częstochowa           | 42        | 0.74%   |
| Torun                  | 39        | 0.69%   |
| Rzeszów               | 39        | 0.69%   |
| Bydgoszcz              | 38        | 0.67%   |
| Ruda Śląska          | 37        | 0.66%   |
| Bytom                  | 37        | 0.66%   |
| Płock                 | 30        | 0.53%   |
| Zabrze                 | 27        | 0.48%   |
| Sosnowiec              | 27        | 0.48%   |
| Kielce                 | 27        | 0.48%   |
| Elblag                 | 27        | 0.48%   |
| Bielsko-Biala          | 26        | 0.46%   |
| Rybnik                 | 24        | 0.43%   |
| Olsztyn                | 23        | 0.41%   |
| Radom                  | 22        | 0.39%   |
| Opole                  | 22        | 0.39%   |
| Strzyzow               | 21        | 0.37%   |
| Chorzów               | 21        | 0.37%   |
| Tarnów                | 20        | 0.35%   |
| Siemianowice Śląskie | 19        | 0.34%   |
| Tychy                  | 18        | 0.32%   |
| Zielona Góra          | 15        | 0.27%   |
| Piaseczno              | 15        | 0.27%   |
| Debica                 | 15        | 0.27%   |
| Cieszyn                | 15        | 0.27%   |
| Słupsk                | 14        | 0.25%   |
| Legnica                | 14        | 0.25%   |
| Jaworzno               | 14        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 1063      | 1628   | 13.85%  |
| Seagate                   | 1049      | 1632   | 13.67%  |
| WDC                       | 1010      | 1565   | 13.16%  |
| GOODRAM                   | 521       | 793    | 6.79%   |
| Toshiba                   | 463       | 694    | 6.03%   |
| Crucial                   | 293       | 485    | 3.82%   |
| Kingston                  | 290       | 414    | 3.78%   |
| A-DATA Technology         | 288       | 391    | 3.75%   |
| Unknown                   | 286       | 425    | 3.73%   |
| SanDisk                   | 281       | 383    | 3.66%   |
| Hitachi                   | 250       | 374    | 3.26%   |
| Intel                     | 191       | 257    | 2.49%   |
| SK hynix                  | 176       | 226    | 2.29%   |
| Micron Technology         | 117       | 152    | 1.52%   |
| HGST                      | 111       | 144    | 1.45%   |
| Patriot                   | 102       | 133    | 1.33%   |
| SPCC                      | 84        | 137    | 1.09%   |
| Plextor                   | 59        | 79     | 0.77%   |
| PNY                       | 57        | 63     | 0.74%   |
| KIOXIA                    | 57        | 63     | 0.74%   |
| Phison                    | 45        | 60     | 0.59%   |
| XPG                       | 44        | 63     | 0.57%   |
| Fujitsu                   | 41        | 45     | 0.53%   |
| Apacer                    | 40        | 65     | 0.52%   |
| Phison Electronics        | 39        | 53     | 0.51%   |
| China                     | 38        | 58     | 0.5%    |
| OCZ                       | 30        | 33     | 0.39%   |
| LITEON                    | 29        | 38     | 0.38%   |
| Silicon Motion            | 28        | 36     | 0.36%   |
| Transcend                 | 27        | 31     | 0.35%   |
| Corsair                   | 26        | 36     | 0.34%   |
| ADATA Technology          | 24        | 29     | 0.31%   |
| Maxtor                    | 22        | 22     | 0.29%   |
| Unknown                   | 22        | 25     | 0.29%   |
| Realtek Semiconductor     | 21        | 33     | 0.27%   |
| Micron/Crucial Technology | 21        | 21     | 0.27%   |
| Apple                     | 21        | 26     | 0.27%   |
| KIOXIA-EXCERIA            | 20        | 27     | 0.26%   |
| JMicron Technology        | 20        | 25     | 0.26%   |
| ASMT                      | 19        | 20     | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB                      | 68        | 0.81%   |
| Seagate ST500LT012-1DG142 500GB                   | 66        | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 64        | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB                    | 60        | 0.71%   |
| Toshiba HDWD110 1TB                               | 57        | 0.68%   |
| Samsung SSD 850 EVO 250GB                         | 56        | 0.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 55        | 0.65%   |
| GOODRAM SSDPR-CX400-256-G2 256GB                  | 55        | 0.65%   |
| GOODRAM SSD 120GB                                 | 51        | 0.61%   |
| Crucial CT1000MX500SSD1 1TB                       | 48        | 0.57%   |
| Unknown MMC Card  32GB                            | 44        | 0.52%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                  | 43        | 0.51%   |
| Samsung SSD 860 EVO 500GB                         | 42        | 0.5%    |
| Seagate ST500DM002-1BD142 500GB                   | 41        | 0.49%   |
| GOODRAM SSD 240GB                                 | 41        | 0.49%   |
| Kingston SA400S37240G 240GB SSD                   | 40        | 0.48%   |
| GOODRAM SSDPR-CX400-512 512GB                     | 38        | 0.45%   |
| Crucial CT240BX500SSD1 240GB                      | 37        | 0.44%   |
| Unknown MMC Card  64GB                            | 36        | 0.43%   |
| Toshiba MQ01ABD100 1TB                            | 34        | 0.4%    |
| Samsung SSD 980 1TB                               | 34        | 0.4%    |
| Kingston SV300S37A120G 120GB SSD                  | 34        | 0.4%    |
| Seagate ST1000DM010-2EP102 1TB                    | 33        | 0.39%   |
| Samsung SSD 860 EVO 250GB                         | 33        | 0.39%   |
| A-DATA SU800 256GB SSD                            | 33        | 0.39%   |
| Seagate ST9500325AS 500GB                         | 32        | 0.38%   |
| Seagate ST1000DM003-1ER162 1TB                    | 32        | 0.38%   |
| Samsung NVMe SSD Drive 500GB                      | 32        | 0.38%   |
| Seagate ST3500418AS 500GB                         | 31        | 0.37%   |
| Patriot Burst 120GB SSD                           | 31        | 0.37%   |
| Samsung SSD 980 500GB                             | 30        | 0.36%   |
| Samsung NVMe SSD Drive 512GB                      | 28        | 0.33%   |
| HGST HTS721010A9E630 1TB                          | 28        | 0.33%   |
| GOODRAM SSDPR-CX400-256 256GB                     | 28        | 0.33%   |
| Seagate Expansion 1TB                             | 27        | 0.32%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 27        | 0.32%   |
| Toshiba MQ01ABF050 500GB                          | 26        | 0.31%   |
| Samsung HD502HJ 500GB                             | 26        | 0.31%   |
| Kingston SA400S37480G 480GB SSD                   | 26        | 0.31%   |
| Intel NVMe SSD Drive 512GB                        | 26        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1042      | 1621   | 36.26%  |
| WDC                 | 837       | 1321   | 29.12%  |
| Toshiba             | 352       | 556    | 12.25%  |
| Hitachi             | 250       | 374    | 8.7%    |
| Samsung Electronics | 172       | 244    | 5.98%   |
| HGST                | 111       | 144    | 3.86%   |
| Fujitsu             | 41        | 45     | 1.43%   |
| Maxtor              | 20        | 20     | 0.7%    |
| Unknown             | 10        | 11     | 0.35%   |
| Apple               | 7         | 7      | 0.24%   |
| ASMT                | 5         | 6      | 0.17%   |
| USB3.0              | 4         | 4      | 0.14%   |
| WD MediaMax         | 2         | 3      | 0.07%   |
| SAGE                | 2         | 2      | 0.07%   |
| IBM/Hitachi         | 2         | 2      | 0.07%   |
| ASMedia             | 2         | 2      | 0.07%   |
| Unknown             | 2         | 2      | 0.07%   |
| USB                 | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| LaCie               | 1         | 2      | 0.03%   |
| JMicron Technology  | 1         | 4      | 0.03%   |
| IB-377U3            | 1         | 6      | 0.03%   |
| HPE                 | 1         | 1      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| Hewlett-Packard     | 1         | 1      | 0.03%   |
| ExcelStor           | 1         | 1      | 0.03%   |
| ASUSTOR             | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| GOODRAM             | 506       | 762    | 18.06%  |
| Samsung Electronics | 451       | 640    | 16.1%   |
| Crucial             | 283       | 473    | 10.1%   |
| A-DATA Technology   | 239       | 323    | 8.53%   |
| Kingston            | 202       | 280    | 7.21%   |
| SanDisk             | 183       | 256    | 6.53%   |
| WDC                 | 94        | 113    | 3.36%   |
| Patriot             | 92        | 123    | 3.28%   |
| SPCC                | 76        | 127    | 2.71%   |
| Intel               | 61        | 75     | 2.18%   |
| Micron Technology   | 57        | 72     | 2.03%   |
| Plextor             | 50        | 70     | 1.79%   |
| Toshiba             | 48        | 53     | 1.71%   |
| SK hynix            | 47        | 56     | 1.68%   |
| PNY                 | 44        | 49     | 1.57%   |
| China               | 37        | 57     | 1.32%   |
| Apacer              | 36        | 60     | 1.29%   |
| OCZ                 | 30        | 33     | 1.07%   |
| LITEON              | 29        | 38     | 1.04%   |
| Transcend           | 26        | 30     | 0.93%   |
| LITEONIT            | 16        | 18     | 0.57%   |
| KIOXIA-EXCERIA      | 16        | 21     | 0.57%   |
| ASMT                | 14        | 14     | 0.5%    |
| Apple               | 12        | 12     | 0.43%   |
| Corsair             | 11        | 12     | 0.39%   |
| KingSpec            | 9         | 10     | 0.32%   |
| Team                | 8         | 9      | 0.29%   |
| Intenso             | 8         | 13     | 0.29%   |
| Gigabyte Technology | 7         | 8      | 0.25%   |
| POLION              | 5         | 5      | 0.18%   |
| Lexar               | 5         | 5      | 0.18%   |
| BIWIN               | 5         | 5      | 0.18%   |
| Argon               | 4         | 6      | 0.14%   |
| Unknown             | 4         | 4      | 0.14%   |
| WDC WDS2            | 3         | 3      | 0.11%   |
| Phison              | 3         | 3      | 0.11%   |
| PHD 3.0             | 3         | 3      | 0.11%   |
| Kingchuxing         | 3         | 5      | 0.11%   |
| Hewlett-Packard     | 3         | 3      | 0.11%   |
| Biostar             | 3         | 3      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2444      | 4386   | 35.98%  |
| SSD     | 2426      | 3931   | 35.72%  |
| NVMe    | 1564      | 2376   | 23.03%  |
| MMC     | 269       | 390    | 3.96%   |
| Unknown | 89        | 128    | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3927      | 8113   | 65.36%  |
| NVMe | 1554      | 2348   | 25.87%  |
| MMC  | 269       | 390    | 4.48%   |
| SAS  | 258       | 360    | 4.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3180      | 5256   | 64.11%  |
| 0.51-1.0   | 1315      | 2132   | 26.51%  |
| 1.01-2.0   | 261       | 439    | 5.26%   |
| 3.01-4.0   | 74        | 161    | 1.49%   |
| 2.01-3.0   | 67        | 185    | 1.35%   |
| 4.01-10.0  | 44        | 102    | 0.89%   |
| 10.01-20.0 | 19        | 42     | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1526      | 27.24%  |
| 251-500        | 1069      | 19.08%  |
| 1-20           | 677       | 12.08%  |
| 501-1000       | 661       | 11.8%   |
| 51-100         | 464       | 8.28%   |
| 1001-2000      | 388       | 6.93%   |
| 21-50          | 277       | 4.94%   |
| Unknown        | 238       | 4.25%   |
| More than 3000 | 172       | 3.07%   |
| 2001-3000      | 130       | 2.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2374      | 41.14%  |
| 21-50          | 851       | 14.75%  |
| 101-250        | 709       | 12.29%  |
| 51-100         | 638       | 11.06%  |
| 251-500        | 372       | 6.45%   |
| 501-1000       | 305       | 5.29%   |
| Unknown        | 238       | 4.12%   |
| 1001-2000      | 164       | 2.84%   |
| 2001-3000      | 60        | 1.04%   |
| More than 3000 | 56        | 0.97%   |
| 0              | 3         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 14        | 17     | 1.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 11        | 13     | 1.48%   |
| Seagate ST500LT012-9WS142 500GB      | 10        | 29     | 1.35%   |
| Seagate ST3500418AS 500GB            | 9         | 12     | 1.21%   |
| Seagate ST500LT012-1DG142 500GB      | 8         | 11     | 1.08%   |
| Seagate ST500DM002-1BD142 500GB      | 8         | 8      | 1.08%   |
| Seagate ST1000DM003-9YN162 1TB       | 7         | 7      | 0.94%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 6         | 7      | 0.81%   |
| HGST HTS545050A7E680 500GB           | 6         | 6      | 0.81%   |
| Toshiba MQ01ABD100 1TB               | 5         | 6      | 0.67%   |
| Kingston SV300S37A120G 120GB SSD     | 5         | 5      | 0.67%   |
| GOODRAM SSD 120GB                    | 5         | 5      | 0.67%   |
| ASMT 2135 18TB                       | 5         | 5      | 0.67%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 4         | 4      | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 4      | 0.54%   |
| Seagate ST9500420AS 500GB            | 4         | 4      | 0.54%   |
| Seagate ST9320325AS 320GB            | 4         | 4      | 0.54%   |
| Seagate ST92505610AS 250GB           | 4         | 4      | 0.54%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 4         | 4      | 0.54%   |
| Seagate ST3320613AS 320GB            | 4         | 4      | 0.54%   |
| Seagate ST1000LM014-SSHD-8GB         | 4         | 4      | 0.54%   |
| Seagate ST1000LM014-1EJ164 1TB       | 4         | 5      | 0.54%   |
| Seagate ST1000DX001-1CM162 1TB       | 4         | 7      | 0.54%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 4      | 0.54%   |
| Hitachi HTS543225L9SA00 250GB        | 4         | 4      | 0.54%   |
| Hitachi HTS541612J9SA00 120GB        | 4         | 5      | 0.54%   |
| A-DATA Technology SU800 512GB SSD    | 4         | 4      | 0.54%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 3         | 3      | 0.4%    |
| WDC WD10JFCX-68N6GN0 1TB             | 3         | 4      | 0.4%    |
| Toshiba MK3265GSX 320GB              | 3         | 3      | 0.4%    |
| Toshiba MK1637GSX 160GB              | 3         | 3      | 0.4%    |
| Toshiba MK1246GSX 120GB              | 3         | 3      | 0.4%    |
| Seagate ST980811AS 80GB              | 3         | 3      | 0.4%    |
| Seagate ST9250827AS 250GB            | 3         | 4      | 0.4%    |
| Seagate ST9250410AS 250GB            | 3         | 3      | 0.4%    |
| Seagate ST9250315AS 250GB            | 3         | 3      | 0.4%    |
| Seagate ST9160821AS 160GB            | 3         | 4      | 0.4%    |
| Seagate ST3500320AS 500GB            | 3         | 3      | 0.4%    |
| Seagate ST3500312CS 500GB            | 3         | 3      | 0.4%    |
| Seagate ST3320418AS 320GB            | 3         | 3      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 209       | 278    | 29.31%  |
| WDC                   | 130       | 188    | 18.23%  |
| Hitachi               | 62        | 77     | 8.7%    |
| Samsung Electronics   | 54        | 63     | 7.57%   |
| Toshiba               | 50        | 61     | 7.01%   |
| A-DATA Technology     | 32        | 35     | 4.49%   |
| SanDisk               | 18        | 21     | 2.52%   |
| HGST                  | 17        | 18     | 2.38%   |
| SK hynix              | 16        | 17     | 2.24%   |
| Kingston              | 16        | 16     | 2.24%   |
| Fujitsu               | 10        | 12     | 1.4%    |
| Micron Technology     | 8         | 8      | 1.12%   |
| Intel                 | 8         | 8      | 1.12%   |
| GOODRAM               | 8         | 8      | 1.12%   |
| Crucial               | 7         | 16     | 0.98%   |
| LITEON                | 6         | 6      | 0.84%   |
| ASMT                  | 6         | 7      | 0.84%   |
| Maxtor                | 5         | 5      | 0.7%    |
| China                 | 5         | 6      | 0.7%    |
| SPCC                  | 4         | 4      | 0.56%   |
| LITEONIT              | 4         | 4      | 0.56%   |
| Apacer                | 4         | 7      | 0.56%   |
| Patriot               | 3         | 5      | 0.42%   |
| OCZ                   | 3         | 3      | 0.42%   |
| Hewlett-Packard       | 3         | 3      | 0.42%   |
| ASMedia               | 3         | 3      | 0.42%   |
| SSSTC                 | 2         | 2      | 0.28%   |
| Apple                 | 2         | 2      | 0.28%   |
| XPG                   | 1         | 1      | 0.14%   |
| WDC WDS2              | 1         | 1      | 0.14%   |
| WD MediaMax           | 1         | 2      | 0.14%   |
| SAGE                  | 1         | 1      | 0.14%   |
| RENICE                | 1         | 1      | 0.14%   |
| Realtek Semiconductor | 1         | 1      | 0.14%   |
| POLION                | 1         | 1      | 0.14%   |
| Plextor               | 1         | 1      | 0.14%   |
| Platinet              | 1         | 1      | 0.14%   |
| OWC                   | 1         | 1      | 0.14%   |
| Lexar                 | 1         | 1      | 0.14%   |
| Lenovo                | 1         | 1      | 0.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 209       | 278    | 39.81%  |
| WDC                 | 127       | 184    | 24.19%  |
| Hitachi             | 62        | 77     | 11.81%  |
| Toshiba             | 47        | 58     | 8.95%   |
| Samsung Electronics | 40        | 46     | 7.62%   |
| HGST                | 17        | 18     | 3.24%   |
| Fujitsu             | 10        | 12     | 1.9%    |
| Maxtor              | 5         | 5      | 0.95%   |
| WD MediaMax         | 1         | 2      | 0.19%   |
| SAGE                | 1         | 1      | 0.19%   |
| JMicron Technology  | 1         | 2      | 0.19%   |
| Hewlett-Packard     | 1         | 1      | 0.19%   |
| ASMT                | 1         | 2      | 0.19%   |
| ASMedia             | 1         | 1      | 0.19%   |
| Apple               | 1         | 1      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 486       | 689    | 72.65%  |
| SSD  | 156       | 185    | 23.32%  |
| NVMe | 27        | 30     | 4.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB         | 1         | 1      | 7.69%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 1      | 7.69%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1      | 7.69%   |
| WDC WD2500BEVS-22UST0 250GB       | 1         | 1      | 7.69%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 7.69%   |
| Toshiba MK3265GSXN 320GB          | 1         | 1      | 7.69%   |
| Toshiba DT01ACA100 1TB            | 1         | 2      | 7.69%   |
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 7.69%   |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 7.69%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 7.69%   |
| Samsung Electronics HD250HJ 250GB | 1         | 1      | 7.69%   |
| OCZ-AGIL ITY3 64GB SSD            | 1         | 1      | 7.69%   |
| HGST HTS725025A7 250GB            | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 38.46%  |
| Seagate             | 3         | 3      | 23.08%  |
| Toshiba             | 2         | 3      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| OCZ-AGIL            | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2599      | 5514   | 45.83%  |
| Works    | 2405      | 4779   | 42.41%  |
| Malfunc  | 654       | 904    | 11.53%  |
| Failed   | 13        | 14     | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3521      | 54.06%  |
| AMD                              | 946       | 14.52%  |
| Samsung Electronics              | 518       | 7.95%   |
| SanDisk                          | 183       | 2.81%   |
| Phison Electronics               | 135       | 2.07%   |
| SK hynix                         | 125       | 1.92%   |
| ASMedia Technology               | 109       | 1.67%   |
| ADATA Technology                 | 109       | 1.67%   |
| Kingston Technology Company      | 108       | 1.66%   |
| JMicron Technology               | 106       | 1.63%   |
| Nvidia                           | 93        | 1.43%   |
| Toshiba America Info Systems     | 67        | 1.03%   |
| KIOXIA                           | 63        | 0.97%   |
| Micron Technology                | 61        | 0.94%   |
| Silicon Motion                   | 54        | 0.83%   |
| Marvell Technology Group         | 52        | 0.8%    |
| Realtek Semiconductor            | 35        | 0.54%   |
| Micron/Crucial Technology        | 30        | 0.46%   |
| Lite-On Technology               | 29        | 0.45%   |
| VIA Technologies                 | 23        | 0.35%   |
| LSI Logic / Symbios Logic        | 21        | 0.32%   |
| Shenzhen Longsys Electronics     | 20        | 0.31%   |
| Union Memory (Shenzhen)          | 16        | 0.25%   |
| Silicon Integrated Systems [SiS] | 11        | 0.17%   |
| Solid State Storage Technology   | 10        | 0.15%   |
| Lenovo                           | 9         | 0.14%   |
| Hewlett-Packard                  | 9         | 0.14%   |
| Silicon Image                    | 8         | 0.12%   |
| Broadcom / LSI                   | 8         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.11%   |
| INNOGRIT                         | 4         | 0.06%   |
| Apple                            | 4         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| ULi Electronics                  | 2         | 0.03%   |
| Seagate Technology               | 2         | 0.03%   |
| O2 Micro                         | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| Adaptec                          | 2         | 0.03%   |
| Tekram Technology                | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 626       | 8.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 257       | 3.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 251       | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 247       | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 220       | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 184       | 2.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 178       | 2.32%   |
| AMD 400 Series Chipset SATA Controller                                         | 176       | 2.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 148       | 1.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 142       | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 130       | 1.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 128       | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 117       | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 115       | 1.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 111       | 1.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 109       | 1.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 108       | 1.41%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 104       | 1.36%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 102       | 1.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 100       | 1.31%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 96        | 1.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 92        | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 88        | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 88        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 84        | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 83        | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 83        | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 80        | 1.04%   |
| Intel SSD 660P Series                                                          | 79        | 1.03%   |
| JMicron JMB363 SATA/IDE Controller                                             | 71        | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 71        | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 71        | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 69        | 0.9%    |
| Phison E12 NVMe Controller                                                     | 63        | 0.82%   |
| Intel SATA Controller [RAID mode]                                              | 63        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 62        | 0.81%   |
| AMD 500 Series Chipset SATA Controller                                         | 61        | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 57        | 0.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 54        | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 50        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3703      | 56.11%  |
| NVMe | 1565      | 23.71%  |
| IDE  | 902       | 13.67%  |
| RAID | 398       | 6.03%   |
| SAS  | 18        | 0.27%   |
| SCSI | 14        | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3857      | 75.05%  |
| AMD          | 1227      | 23.88%  |
| ARM          | 47        | 0.91%   |
| Qualcomm     | 3         | 0.06%   |
| CentaurHauls | 2         | 0.04%   |
| PowerMac11,2 | 1         | 0.02%   |
| PowerBook6,7 | 1         | 0.02%   |
| AppliedMicro | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 51        | 0.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 47        | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 46        | 0.89%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 46        | 0.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 45        | 0.87%   |
| AMD Ryzen 5 3600 6-Core Processor             | 45        | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 42        | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 39        | 0.76%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 38        | 0.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 0.7%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 36        | 0.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 35        | 0.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 34        | 0.66%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 34        | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 33        | 0.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 32        | 0.62%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 30        | 0.58%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 30        | 0.58%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 0.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 28        | 0.54%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 28        | 0.54%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 28        | 0.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 27        | 0.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 27        | 0.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 27        | 0.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 25        | 0.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 25        | 0.48%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 24        | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 24        | 0.46%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 23        | 0.45%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 23        | 0.45%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 23        | 0.45%   |
| ARM Processor                                 | 23        | 0.45%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 23        | 0.45%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 23        | 0.45%   |
| AMD Custom APU 0405                           | 23        | 0.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 22        | 0.43%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.43%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 0.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 20        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1251      | 24.27%  |
| Intel Core i7           | 780       | 15.13%  |
| Intel Core i3           | 356       | 6.91%   |
| AMD Ryzen 5             | 345       | 6.69%   |
| Intel Core 2 Duo        | 321       | 6.23%   |
| Other                   | 287       | 5.57%   |
| Intel Celeron           | 227       | 4.4%    |
| AMD Ryzen 7             | 220       | 4.27%   |
| Intel Pentium           | 144       | 2.79%   |
| Intel Xeon              | 132       | 2.56%   |
| Intel Atom              | 84        | 1.63%   |
| Intel Pentium Dual-Core | 74        | 1.44%   |
| Intel Core 2 Quad       | 71        | 1.38%   |
| AMD Ryzen 9             | 65        | 1.26%   |
| AMD FX                  | 52        | 1.01%   |
| Intel Core 2            | 43        | 0.83%   |
| AMD Phenom II X4        | 40        | 0.78%   |
| AMD A6                  | 40        | 0.78%   |
| AMD A8                  | 39        | 0.76%   |
| AMD Ryzen 3             | 38        | 0.74%   |
| Intel Pentium Dual      | 34        | 0.66%   |
| AMD Athlon 64 X2        | 33        | 0.64%   |
| AMD A10                 | 33        | 0.64%   |
| AMD Athlon II X2        | 29        | 0.56%   |
| AMD Ryzen 7 PRO         | 21        | 0.41%   |
| AMD A4                  | 21        | 0.41%   |
| AMD Athlon II X4        | 20        | 0.39%   |
| Intel Genuine           | 18        | 0.35%   |
| Intel Core i9           | 17        | 0.33%   |
| AMD E                   | 17        | 0.33%   |
| AMD GX                  | 14        | 0.27%   |
| AMD E1                  | 14        | 0.27%   |
| ARM BCM                 | 13        | 0.25%   |
| AMD Ryzen 5 PRO         | 13        | 0.25%   |
| Intel Celeron M         | 11        | 0.21%   |
| AMD Ryzen Threadripper  | 11        | 0.21%   |
| AMD Athlon              | 11        | 0.21%   |
| Intel Pentium Silver    | 10        | 0.19%   |
| AMD Athlon X2           | 9         | 0.17%   |
| Intel Pentium M         | 8         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2183      | 42.22%  |
| 4       | 1771      | 34.26%  |
| 6       | 511       | 9.88%   |
| 8       | 319       | 6.17%   |
| 1       | 113       | 2.19%   |
| 12      | 88        | 1.7%    |
| Unknown | 72        | 1.39%   |
| 16      | 29        | 0.56%   |
| 10      | 25        | 0.48%   |
| 3       | 23        | 0.44%   |
| 14      | 19        | 0.37%   |
| 20      | 4         | 0.08%   |
| 32      | 3         | 0.06%   |
| 24      | 2         | 0.04%   |
| 192     | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 44      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5083      | 98.85%  |
| 2       | 50        | 0.97%   |
| Unknown | 8         | 0.16%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3181      | 61.53%  |
| 1       | 1915      | 37.04%  |
| Unknown | 72        | 1.39%   |
| 8       | 1         | 0.02%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5007      | 97.24%  |
| Unknown        | 86        | 1.67%   |
| 32-bit         | 54        | 1.05%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1347      | 25.03%  |
| 0x306a9    | 302       | 5.61%   |
| 0x206a7    | 288       | 5.35%   |
| 0x306c3    | 254       | 4.72%   |
| 0x1067a    | 226       | 4.2%    |
| 0x906ea    | 136       | 2.53%   |
| 0x506e3    | 121       | 2.25%   |
| 0x40651    | 109       | 2.03%   |
| 0x806ec    | 93        | 1.73%   |
| 0x20655    | 93        | 1.73%   |
| 0x906e9    | 91        | 1.69%   |
| 0x6fd      | 91        | 1.69%   |
| 0x30678    | 90        | 1.67%   |
| 0x306d4    | 87        | 1.62%   |
| 0x806c1    | 85        | 1.58%   |
| 0x806ea    | 81        | 1.51%   |
| 0x406e3    | 81        | 1.51%   |
| 0x10676    | 77        | 1.43%   |
| 0x806e9    | 70        | 1.3%    |
| 0x0800820d | 70        | 1.3%    |
| 0x08701021 | 64        | 1.19%   |
| 0x010000c8 | 64        | 1.19%   |
| 0x0a50000c | 61        | 1.13%   |
| 0x6fb      | 46        | 0.85%   |
| 0x06001119 | 44        | 0.82%   |
| 0x08600106 | 43        | 0.8%    |
| 0x08108109 | 40        | 0.74%   |
| 0x20652    | 34        | 0.63%   |
| 0xa0652    | 33        | 0.61%   |
| 0x6f6      | 33        | 0.61%   |
| 0x08108102 | 30        | 0.56%   |
| 0x806eb    | 29        | 0.54%   |
| 0x406c4    | 28        | 0.52%   |
| 0x08701013 | 28        | 0.52%   |
| 0xa0653    | 27        | 0.5%    |
| 0x906ed    | 27        | 0.5%    |
| 0x06000852 | 24        | 0.45%   |
| 0x706e5    | 23        | 0.43%   |
| 0x106e5    | 22        | 0.41%   |
| 0x08001138 | 22        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 718       | 13.93%  |
| Haswell          | 479       | 9.29%   |
| IvyBridge        | 386       | 7.49%   |
| SandyBridge      | 368       | 7.14%   |
| Penryn           | 363       | 7.04%   |
| Skylake          | 282       | 5.47%   |
| Zen 2            | 241       | 4.68%   |
| Core             | 237       | 4.6%    |
| Zen+             | 183       | 3.55%   |
| Unknown          | 180       | 3.49%   |
| Silvermont       | 176       | 3.41%   |
| Westmere         | 172       | 3.34%   |
| Zen 3            | 143       | 2.77%   |
| K10              | 129       | 2.5%    |
| Broadwell        | 129       | 2.5%    |
| TigerLake        | 113       | 2.19%   |
| Zen              | 95        | 1.84%   |
| Piledriver       | 93        | 1.8%    |
| CometLake        | 91        | 1.77%   |
| K8 Hammer        | 65        | 1.26%   |
| Alderlake Hybrid | 63        | 1.22%   |
| IceLake          | 56        | 1.09%   |
| Bobcat           | 46        | 0.89%   |
| Nehalem          | 41        | 0.8%    |
| Goldmont plus    | 39        | 0.76%   |
| Bonnell          | 35        | 0.68%   |
| P6               | 33        | 0.64%   |
| Excavator        | 31        | 0.6%    |
| Jaguar           | 28        | 0.54%   |
| Goldmont         | 26        | 0.5%    |
| Steamroller      | 23        | 0.45%   |
| Puma             | 21        | 0.41%   |
| NetBurst         | 19        | 0.37%   |
| K10 Llano        | 19        | 0.37%   |
| K8 & K10 hybrid  | 16        | 0.31%   |
| Bulldozer        | 12        | 0.23%   |
| Tremont          | 3         | 0.06%   |
| Gracemont        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2896      | 47.07%  |
| Nvidia                           | 1838      | 29.87%  |
| AMD                              | 1379      | 22.41%  |
| Matrox Electronics Systems       | 18        | 0.29%   |
| ASPEED Technology                | 8         | 0.13%   |
| VIA Technologies                 | 7         | 0.11%   |
| Silicon Integrated Systems [SiS] | 6         | 0.1%    |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 293       | 4.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 243       | 3.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 138       | 2.16%   |
| Intel UHD Graphics 620                                                                   | 116       | 1.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 115       | 1.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 113       | 1.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 109       | 1.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 109       | 1.7%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 108       | 1.69%   |
| Intel HD Graphics 530                                                                    | 106       | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 104       | 1.63%   |
| Intel HD Graphics 5500                                                                   | 104       | 1.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 104       | 1.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 103       | 1.61%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 102       | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 96        | 1.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 91        | 1.42%   |
| Intel HD Graphics 620                                                                    | 89        | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 88        | 1.38%   |
| Intel HD Graphics 630                                                                    | 79        | 1.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 76        | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 75        | 1.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 75        | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 66        | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 59        | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 56        | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 56        | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 50        | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 47        | 0.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 45        | 0.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 45        | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 45        | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 44        | 0.69%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 43        | 0.67%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 40        | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 39        | 0.61%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 35        | 0.55%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 33        | 0.52%   |
| Nvidia GT218 [GeForce 210]                                                               | 32        | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 32        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1973      | 37.94%  |
| 1 x Nvidia               | 1028      | 19.77%  |
| 1 x AMD                  | 1001      | 19.25%  |
| Intel + Nvidia           | 682       | 13.12%  |
| Intel + AMD              | 188       | 3.62%   |
| AMD + Nvidia             | 116       | 2.23%   |
| 2 x AMD                  | 77        | 1.48%   |
| Other                    | 58        | 1.12%   |
| 2 x Intel                | 26        | 0.5%    |
| 1 x Matrox               | 18        | 0.35%   |
| 2 x Nvidia               | 8         | 0.15%   |
| 1 x VIA                  | 7         | 0.13%   |
| 1 x SiS                  | 6         | 0.12%   |
| 1 x ASPEED               | 5         | 0.1%    |
| Nvidia + ASPEED          | 3         | 0.06%   |
| 3 x AMD                  | 2         | 0.04%   |
| 1 x S3 Graphics          | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4108      | 78.25%  |
| Proprietary | 916       | 17.45%  |
| Unknown     | 226       | 4.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2760      | 51.7%   |
| 1.01-2.0   | 686       | 12.85%  |
| 0.01-0.5   | 667       | 12.5%   |
| 0.51-1.0   | 455       | 8.52%   |
| 3.01-4.0   | 355       | 6.65%   |
| 7.01-8.0   | 201       | 3.77%   |
| 5.01-6.0   | 133       | 2.49%   |
| 8.01-16.0  | 51        | 0.96%   |
| 2.01-3.0   | 22        | 0.41%   |
| 16.01-24.0 | 7         | 0.13%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 794       | 13.92%  |
| AU Optronics            | 653       | 11.44%  |
| LG Display              | 548       | 9.6%    |
| BOE                     | 435       | 7.62%   |
| Chimei Innolux          | 396       | 6.94%   |
| Dell                    | 341       | 5.98%   |
| Goldstar                | 316       | 5.54%   |
| Iiyama                  | 192       | 3.36%   |
| Philips                 | 182       | 3.19%   |
| BenQ                    | 145       | 2.54%   |
| Lenovo                  | 142       | 2.49%   |
| Hewlett-Packard         | 140       | 2.45%   |
| Acer                    | 135       | 2.37%   |
| AOC                     | 118       | 2.07%   |
| Chi Mei Optoelectronics | 114       | 2%      |
| Eizo                    | 87        | 1.52%   |
| NEC Computers           | 85        | 1.49%   |
| Ancor Communications    | 70        | 1.23%   |
| Sharp                   | 61        | 1.07%   |
| PANDA                   | 50        | 0.88%   |
| LG Philips              | 47        | 0.82%   |
| Sony                    | 43        | 0.75%   |
| Fujitsu Siemens         | 41        | 0.72%   |
| InfoVision              | 40        | 0.7%    |
| Apple                   | 36        | 0.63%   |
| LG Electronics          | 34        | 0.6%    |
| ASUSTek Computer        | 29        | 0.51%   |
| Unknown                 | 23        | 0.4%    |
| Valve                   | 18        | 0.32%   |
| Toshiba                 | 18        | 0.32%   |
| MSI                     | 18        | 0.32%   |
| Idek Iiyama             | 18        | 0.32%   |
| HannStar                | 18        | 0.32%   |
| CSO                     | 16        | 0.28%   |
| CPT                     | 16        | 0.28%   |
| ViewSonic               | 14        | 0.25%   |
| Panasonic               | 14        | 0.25%   |
| Gateway                 | 14        | 0.25%   |
| Belinea                 | 13        | 0.23%   |
| Gigabyte Technology     | 11        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 32        | 0.54%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 28        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 28        | 0.47%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 26        | 0.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 26        | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 25        | 0.42%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 22        | 0.37%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 20        | 0.34%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch              | 19        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 19        | 0.32%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 19        | 0.32%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 18        | 0.3%    |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 17        | 0.29%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 17        | 0.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 17        | 0.29%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 16        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 16        | 0.27%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 16        | 0.27%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 15        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 15        | 0.25%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 15        | 0.25%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 14        | 0.24%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.24%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 14        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.24%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 14        | 0.24%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 14        | 0.24%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 13        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 13        | 0.22%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 13        | 0.22%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 13        | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 13        | 0.22%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 12        | 0.2%    |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                     | 12        | 0.2%    |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 12        | 0.2%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 12        | 0.2%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 12        | 0.2%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 11        | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 11        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2319      | 43.02%  |
| 1366x768 (WXGA)    | 908       | 16.84%  |
| 2560x1440 (QHD)    | 255       | 4.73%   |
| 3840x2160 (4K)     | 248       | 4.6%    |
| 1280x1024 (SXGA)   | 235       | 4.36%   |
| 1600x900 (HD+)     | 231       | 4.28%   |
| 1280x800 (WXGA)    | 196       | 3.64%   |
| 1680x1050 (WSXGA+) | 191       | 3.54%   |
| 1920x1200 (WUXGA)  | 189       | 3.51%   |
| 1440x900 (WXGA+)   | 150       | 2.78%   |
| 3440x1440          | 55        | 1.02%   |
| Unknown            | 53        | 0.98%   |
| 2560x1080          | 42        | 0.78%   |
| 2560x1600          | 32        | 0.59%   |
| 1024x600           | 27        | 0.5%    |
| 1360x768           | 24        | 0.45%   |
| 1024x768 (XGA)     | 23        | 0.43%   |
| 1600x1200          | 21        | 0.39%   |
| 800x1280           | 19        | 0.35%   |
| 3840x1080          | 18        | 0.33%   |
| 2160x1440          | 13        | 0.24%   |
| 2880x1800          | 12        | 0.22%   |
| 1920x540           | 12        | 0.22%   |
| 3840x2400          | 11        | 0.2%    |
| 2288x1287          | 9         | 0.17%   |
| 3200x1800 (QHD+)   | 7         | 0.13%   |
| 1280x720 (HD)      | 7         | 0.13%   |
| 2048x1152          | 5         | 0.09%   |
| 1280x768           | 5         | 0.09%   |
| 5120x1440          | 4         | 0.07%   |
| 3200x2000          | 4         | 0.07%   |
| 1680x945           | 4         | 0.07%   |
| 1400x1050          | 4         | 0.07%   |
| 1280x960           | 4         | 0.07%   |
| 3840x1600          | 3         | 0.06%   |
| 3840x1200          | 3         | 0.06%   |
| 3286x1080          | 3         | 0.06%   |
| 3200x1080          | 3         | 0.06%   |
| 5760x1080          | 2         | 0.04%   |
| 4480x1440          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1528      | 26.85%  |
| 24      | 460       | 8.08%   |
| 13      | 449       | 7.89%   |
| 14      | 407       | 7.15%   |
| 23      | 372       | 6.54%   |
| 17      | 358       | 6.29%   |
| 27      | 349       | 6.13%   |
| 21      | 339       | 5.96%   |
| Unknown | 270       | 4.74%   |
| 19      | 203       | 3.57%   |
| 12      | 117       | 2.06%   |
| 22      | 113       | 1.99%   |
| 34      | 91        | 1.6%    |
| 18      | 82        | 1.44%   |
| 31      | 67        | 1.18%   |
| 11      | 54        | 0.95%   |
| 20      | 52        | 0.91%   |
| 16      | 36        | 0.63%   |
| 25      | 35        | 0.62%   |
| 10      | 31        | 0.54%   |
| 84      | 30        | 0.53%   |
| 72      | 30        | 0.53%   |
| 32      | 25        | 0.44%   |
| 40      | 24        | 0.42%   |
| 54      | 18        | 0.32%   |
| 7       | 16        | 0.28%   |
| 48      | 15        | 0.26%   |
| 65      | 13        | 0.23%   |
| 28      | 11        | 0.19%   |
| 46      | 10        | 0.18%   |
| 33      | 10        | 0.18%   |
| 26      | 9         | 0.16%   |
| 142     | 8         | 0.14%   |
| 43      | 8         | 0.14%   |
| 42      | 8         | 0.14%   |
| 37      | 5         | 0.09%   |
| 3       | 5         | 0.09%   |
| 49      | 4         | 0.07%   |
| 39      | 4         | 0.07%   |
| 29      | 4         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2237      | 40.03%  |
| 501-600        | 1126      | 20.15%  |
| 401-500        | 646       | 11.56%  |
| 351-400        | 451       | 8.07%   |
| 201-300        | 407       | 7.28%   |
| Unknown        | 270       | 4.83%   |
| 701-800        | 127       | 2.27%   |
| 601-700        | 109       | 1.95%   |
| 1001-1500      | 73        | 1.31%   |
| 1501-2000      | 61        | 1.09%   |
| 801-900        | 37        | 0.66%   |
| 1-100          | 20        | 0.36%   |
| 901-1000       | 16        | 0.29%   |
| More than 2000 | 8         | 0.14%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3652      | 71.33%  |
| 16/10   | 752       | 14.69%  |
| Unknown | 235       | 4.59%   |
| 5/4     | 223       | 4.36%   |
| 21/9    | 98        | 1.91%   |
| 3/2     | 59        | 1.15%   |
| 4/3     | 55        | 1.07%   |
| 0.67    | 16        | 0.31%   |
| 32/9    | 10        | 0.2%    |
| 6/5     | 9         | 0.18%   |
| 1.00    | 8         | 0.16%   |
| 0.56    | 2         | 0.04%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1521      | 26.95%  |
| 201-250        | 991       | 17.56%  |
| 81-90          | 678       | 12.01%  |
| 301-350        | 356       | 6.31%   |
| 151-200        | 335       | 5.94%   |
| Unknown        | 270       | 4.78%   |
| 251-300        | 233       | 4.13%   |
| 121-130        | 212       | 3.76%   |
| 351-500        | 204       | 3.61%   |
| 71-80          | 172       | 3.05%   |
| 141-150        | 160       | 2.83%   |
| More than 1000 | 125       | 2.21%   |
| 61-70          | 110       | 1.95%   |
| 501-1000       | 68        | 1.2%    |
| 51-60          | 54        | 0.96%   |
| 131-140        | 50        | 0.89%   |
| 41-50          | 31        | 0.55%   |
| 111-120        | 30        | 0.53%   |
| 91-100         | 23        | 0.41%   |
| 1-40           | 21        | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1880      | 34.28%  |
| 121-160       | 1507      | 27.47%  |
| 101-120       | 1386      | 25.27%  |
| Unknown       | 270       | 4.92%   |
| 161-240       | 248       | 4.52%   |
| 1-50          | 112       | 2.04%   |
| More than 240 | 82        | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4148      | 78.35%  |
| 2     | 793       | 14.98%  |
| 0     | 217       | 4.1%    |
| 3     | 118       | 2.23%   |
| 4     | 16        | 0.3%    |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2638      | 33.22%  |
| Intel                                  | 2519      | 31.73%  |
| Qualcomm Atheros                       | 940       | 11.84%  |
| Broadcom                               | 453       | 5.71%   |
| Broadcom Limited                       | 130       | 1.64%   |
| TP-Link                                | 122       | 1.54%   |
| Marvell Technology Group               | 97        | 1.22%   |
| Huawei Technologies                    | 90        | 1.13%   |
| MediaTek                               | 89        | 1.12%   |
| Dell                                   | 84        | 1.06%   |
| Ralink                                 | 73        | 0.92%   |
| Ralink Technology                      | 72        | 0.91%   |
| Nvidia                                 | 65        | 0.82%   |
| Qualcomm Atheros Communications        | 56        | 0.71%   |
| Samsung Electronics                    | 42        | 0.53%   |
| Xiaomi                                 | 40        | 0.5%    |
| Microsoft                              | 34        | 0.43%   |
| Ericsson Business Mobile Networks      | 31        | 0.39%   |
| ASUSTek Computer                       | 30        | 0.38%   |
| Hewlett-Packard                        | 24        | 0.3%    |
| ASIX Electronics                       | 23        | 0.29%   |
| Sierra Wireless                        | 21        | 0.26%   |
| Lenovo                                 | 17        | 0.21%   |
| JMicron Technology                     | 17        | 0.21%   |
| NetGear                                | 12        | 0.15%   |
| Edimax Technology                      | 12        | 0.15%   |
| Aquantia                               | 12        | 0.15%   |
| VIA Technologies                       | 11        | 0.14%   |
| Motorola PCS                           | 11        | 0.14%   |
| Fibocom                                | 11        | 0.14%   |
| DisplayLink                            | 10        | 0.13%   |
| ZTE WCDMA Technologies MSM             | 9         | 0.11%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.11%   |
| Qualcomm                               | 9         | 0.11%   |
| D-Link                                 | 9         | 0.11%   |
| Microchip Technology                   | 7         | 0.09%   |
| OPPO Electronics                       | 6         | 0.08%   |
| HTC (High Tech Computer)               | 6         | 0.08%   |
| Texas Instruments                      | 5         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1898      | 20.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 272       | 2.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 248       | 2.67%   |
| Intel Wi-Fi 6 AX200                                               | 177       | 1.9%    |
| Intel Wireless 8265 / 8275                                        | 153       | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 137       | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 122       | 1.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 121       | 1.3%    |
| Intel Wireless 7260                                               | 118       | 1.27%   |
| Intel Wireless 8260                                               | 109       | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 108       | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 101       | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 101       | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 95        | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 94        | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 90        | 0.97%   |
| Intel Wi-Fi 6 AX201                                               | 88        | 0.95%   |
| Intel Ethernet Connection I217-LM                                 | 87        | 0.93%   |
| Intel Wireless 7265                                               | 86        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 85        | 0.91%   |
| Intel I211 Gigabit Network Connection                             | 84        | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 75        | 0.81%   |
| Intel Wireless 3160                                               | 69        | 0.74%   |
| Intel Wireless 3165                                               | 68        | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 67        | 0.72%   |
| Intel Ethernet Connection (2) I219-V                              | 66        | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 61        | 0.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 59        | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 58        | 0.62%   |
| Intel 82567LM Gigabit Network Connection                          | 56        | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 55        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 55        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 54        | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                     | 53        | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 52        | 0.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 52        | 0.56%   |
| Intel Centrino Ultimate-N 6300                                    | 50        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 48        | 0.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 48        | 0.52%   |
| Huawei E353/E3131                                                 | 48        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1938      | 46.55%  |
| Qualcomm Atheros                  | 714       | 17.15%  |
| Realtek Semiconductor             | 546       | 13.12%  |
| Broadcom                          | 273       | 6.56%   |
| TP-Link                           | 117       | 2.81%   |
| MediaTek                          | 85        | 2.04%   |
| Ralink                            | 73        | 1.75%   |
| Ralink Technology                 | 72        | 1.73%   |
| Broadcom Limited                  | 64        | 1.54%   |
| Qualcomm Atheros Communications   | 56        | 1.35%   |
| Dell                              | 52        | 1.25%   |
| Microsoft                         | 33        | 0.79%   |
| ASUSTek Computer                  | 30        | 0.72%   |
| Sierra Wireless                   | 21        | 0.5%    |
| Edimax Technology                 | 12        | 0.29%   |
| Fibocom                           | 11        | 0.26%   |
| Ericsson Business Mobile Networks | 9         | 0.22%   |
| D-Link                            | 9         | 0.22%   |
| NetGear                           | 8         | 0.19%   |
| Qualcomm                          | 6         | 0.14%   |
| Hewlett-Packard                   | 6         | 0.14%   |
| Sagem                             | 4         | 0.1%    |
| D-Link System                     | 3         | 0.07%   |
| Belkin Components                 | 3         | 0.07%   |
| ZyXEL Communications              | 2         | 0.05%   |
| ZyDAS                             | 2         | 0.05%   |
| Marvell Technology Group          | 2         | 0.05%   |
| Linksys                           | 2         | 0.05%   |
| Unknown                           | 2         | 0.05%   |
| Z-Com                             | 1         | 0.02%   |
| Wacom                             | 1         | 0.02%   |
| Tenda                             | 1         | 0.02%   |
| Sweex                             | 1         | 0.02%   |
| Ovislink                          | 1         | 0.02%   |
| IMC Networks                      | 1         | 0.02%   |
| AVM                               | 1         | 0.02%   |
| Accton Technology                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 177       | 4.24%   |
| Intel Wireless 8265 / 8275                                              | 153       | 3.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 137       | 3.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 122       | 2.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 121       | 2.9%    |
| Intel Wireless 7260                                                     | 118       | 2.83%   |
| Intel Wireless 8260                                                     | 109       | 2.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 108       | 2.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 101       | 2.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 95        | 2.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 94        | 2.25%   |
| Intel Wi-Fi 6 AX201                                                     | 88        | 2.11%   |
| Intel Wireless 7265                                                     | 86        | 2.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 85        | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 75        | 1.8%    |
| Intel Wireless 3160                                                     | 69        | 1.65%   |
| Intel Wireless 3165                                                     | 68        | 1.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 67        | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 61        | 1.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 59        | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 55        | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 54        | 1.29%   |
| Broadcom BCM43142 802.11b/g/n                                           | 53        | 1.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 52        | 1.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 52        | 1.25%   |
| Intel Centrino Ultimate-N 6300                                          | 50        | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 48        | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 47        | 1.13%   |
| Intel WiFi Link 5100                                                    | 46        | 1.1%    |
| Intel Wireless-AC 9260                                                  | 44        | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 44        | 1.05%   |
| Qualcomm Atheros AR9271 802.11n                                         | 42        | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 41        | 0.98%   |
| Intel Centrino Advanced-N 6235                                          | 39        | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 38        | 0.91%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 36        | 0.86%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 0.79%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 0.79%   |
| Ralink MT7601U Wireless Adapter                                         | 32        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2413      | 49.22%  |
| Intel                                  | 1373      | 28.01%  |
| Qualcomm Atheros                       | 331       | 6.75%   |
| Broadcom                               | 224       | 4.57%   |
| Marvell Technology Group               | 96        | 1.96%   |
| Broadcom Limited                       | 67        | 1.37%   |
| Nvidia                                 | 65        | 1.33%   |
| Huawei Technologies                    | 60        | 1.22%   |
| Samsung Electronics                    | 40        | 0.82%   |
| Xiaomi                                 | 39        | 0.8%    |
| ASIX Electronics                       | 23        | 0.47%   |
| Lenovo                                 | 17        | 0.35%   |
| JMicron Technology                     | 17        | 0.35%   |
| Aquantia                               | 12        | 0.24%   |
| VIA Technologies                       | 11        | 0.22%   |
| Motorola PCS                           | 10        | 0.2%    |
| DisplayLink                            | 10        | 0.2%    |
| Silicon Integrated Systems [SiS]       | 9         | 0.18%   |
| ZTE WCDMA Technologies MSM             | 8         | 0.16%   |
| Microchip Technology                   | 7         | 0.14%   |
| TP-Link                                | 6         | 0.12%   |
| OPPO Electronics                       | 6         | 0.12%   |
| HTC (High Tech Computer)               | 6         | 0.12%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.08%   |
| NetGear                                | 4         | 0.08%   |
| ICS Advent                             | 4         | 0.08%   |
| Hewlett-Packard                        | 4         | 0.08%   |
| Attansic Technology                    | 4         | 0.08%   |
| Qualcomm                               | 3         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.06%   |
| MediaTek                               | 3         | 0.06%   |
| Apple                                  | 3         | 0.06%   |
| Research In Motion                     | 2         | 0.04%   |
| QLogic                                 | 2         | 0.04%   |
| NetXen Incorporated                    | 2         | 0.04%   |
| Google                                 | 2         | 0.04%   |
| 3Com                                   | 2         | 0.04%   |
| QinHeng Electronics                    | 1         | 0.02%   |
| Mellanox Technologies                  | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1898      | 38.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 272       | 5.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 248       | 4.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 101       | 2.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 90        | 1.81%   |
| Intel Ethernet Connection I217-LM                                 | 87        | 1.75%   |
| Intel I211 Gigabit Network Connection                             | 84        | 1.69%   |
| Intel Ethernet Connection (2) I219-V                              | 66        | 1.33%   |
| Intel 82579V Gigabit Network Connection                           | 58        | 1.16%   |
| Intel 82567LM Gigabit Network Connection                          | 56        | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                             | 55        | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 48        | 0.96%   |
| Huawei E353/E3131                                                 | 48        | 0.96%   |
| Intel Ethernet Connection I218-LM                                 | 46        | 0.92%   |
| Intel 82577LM Gigabit Network Connection                          | 42        | 0.84%   |
| Intel Ethernet Connection (7) I219-V                              | 41        | 0.82%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 40        | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                             | 39        | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 38        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 38        | 0.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 37        | 0.74%   |
| Intel Ethernet Connection I219-LM                                 | 35        | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                             | 34        | 0.68%   |
| Intel Ethernet Connection (6) I219-V                              | 33        | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 31        | 0.62%   |
| Nvidia MCP61 Ethernet                                             | 30        | 0.6%    |
| Intel Ethernet Controller I225-V                                  | 30        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 29        | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 28        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 28        | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 26        | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 25        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 25        | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 25        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 24        | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 23        | 0.46%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 22        | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 21        | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 21        | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 21        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4595      | 53.21%  |
| WiFi     | 3896      | 45.11%  |
| Modem    | 129       | 1.49%   |
| Unknown  | 16        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2999      | 57.22%  |
| Ethernet | 2241      | 42.76%  |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3001      | 58.13%  |
| 1     | 1951      | 37.79%  |
| 0     | 110       | 2.13%   |
| 3     | 69        | 1.34%   |
| 4     | 16        | 0.31%   |
| 5     | 6         | 0.12%   |
| 6     | 5         | 0.1%    |
| 17    | 1         | 0.02%   |
| 10    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4796      | 92.44%  |
| Yes  | 392       | 7.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1384      | 45.89%  |
| Qualcomm Atheros Communications | 269       | 8.92%   |
| Realtek Semiconductor           | 213       | 7.06%   |
| Broadcom                        | 191       | 6.33%   |
| Cambridge Silicon Radio         | 187       | 6.2%    |
| IMC Networks                    | 136       | 4.51%   |
| ASUSTek Computer                | 100       | 3.32%   |
| Foxconn / Hon Hai               | 90        | 2.98%   |
| Dell                            | 89        | 2.95%   |
| Lite-On Technology              | 77        | 2.55%   |
| Hewlett-Packard                 | 63        | 2.09%   |
| Apple                           | 44        | 1.46%   |
| Toshiba                         | 31        | 1.03%   |
| Ralink                          | 21        | 0.7%    |
| Realtek                         | 19        | 0.63%   |
| Foxconn International           | 18        | 0.6%    |
| TP-Link                         | 13        | 0.43%   |
| MediaTek                        | 13        | 0.43%   |
| Alps Electric                   | 8         | 0.27%   |
| Integrated System Solution      | 7         | 0.23%   |
| Edimax Technology               | 6         | 0.2%    |
| Chicony Electronics             | 6         | 0.2%    |
| Taiyo Yuden                     | 5         | 0.17%   |
| Ralink Technology               | 3         | 0.1%    |
| Conwise Technology              | 3         | 0.1%    |
| Unknown                         | 3         | 0.1%    |
| USI                             | 2         | 0.07%   |
| Opticis                         | 2         | 0.07%   |
| Micro Star International        | 2         | 0.07%   |
| Logitech                        | 2         | 0.07%   |
| Belkin Components               | 2         | 0.07%   |
| Askey Computer                  | 2         | 0.07%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Marvell Semiconductor           | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |
| AboCom Systems                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 594       | 19.68%  |
| Intel AX201 Bluetooth                               | 196       | 6.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 187       | 6.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 175       | 5.8%    |
| Intel AX200 Bluetooth                               | 170       | 5.63%   |
| Realtek Bluetooth Radio                             | 141       | 4.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 115       | 3.81%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 65        | 2.15%   |
| Intel Bluetooth Device                              | 65        | 2.15%   |
| IMC Networks Bluetooth Radio                        | 58        | 1.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 57        | 1.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 54        | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                    | 53        | 1.76%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 50        | 1.66%   |
| Realtek  Bluetooth 4.2 Adapter                      | 40        | 1.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 39        | 1.29%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 1.29%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.16%   |
| Dell BCM20702A0 Bluetooth Module                    | 29        | 0.96%   |
| Intel AX210 Bluetooth                               | 28        | 0.93%   |
| IMC Networks Wireless_Device                        | 28        | 0.93%   |
| HP Broadcom 2070 Bluetooth Combo                    | 27        | 0.89%   |
| Foxconn / Hon Hai Wireless_Device                   | 26        | 0.86%   |
| Dell DW375 Bluetooth Module                         | 25        | 0.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 24        | 0.79%   |
| Lite-On Bluetooth Device                            | 24        | 0.79%   |
| IMC Networks Bluetooth Device                       | 24        | 0.79%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.7%    |
| Realtek RTL8723B Bluetooth                          | 20        | 0.66%   |
| Realtek Bluetooth Radio                             | 19        | 0.63%   |
| Apple Bluetooth Host Controller                     | 19        | 0.63%   |
| Foxconn International BCM43142A0 Bluetooth module   | 18        | 0.6%    |
| Broadcom BCM2070 Bluetooth Device                   | 18        | 0.6%    |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.56%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 16        | 0.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 0.5%    |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 14        | 0.46%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 14        | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3703      | 52.08%  |
| AMD                                  | 1424      | 20.03%  |
| Nvidia                               | 1269      | 17.85%  |
| C-Media Electronics                  | 104       | 1.46%   |
| Creative Labs                        | 87        | 1.22%   |
| Creative Technology                  | 51        | 0.72%   |
| Logitech                             | 32        | 0.45%   |
| Realtek Semiconductor                | 26        | 0.37%   |
| JMTek                                | 25        | 0.35%   |
| VIA Technologies                     | 22        | 0.31%   |
| Texas Instruments                    | 21        | 0.3%    |
| Lenovo                               | 20        | 0.28%   |
| SteelSeries ApS                      | 18        | 0.25%   |
| Plantronics                          | 18        | 0.25%   |
| GN Netcom                            | 18        | 0.25%   |
| Kingston Technology                  | 16        | 0.23%   |
| Generalplus Technology               | 14        | 0.2%    |
| GYROCOM C&C                          | 12        | 0.17%   |
| Dell                                 | 12        | 0.17%   |
| Silicon Integrated Systems [SiS]     | 11        | 0.15%   |
| ASUSTek Computer                     | 11        | 0.15%   |
| Hewlett-Packard                      | 10        | 0.14%   |
| SAVITECH                             | 9         | 0.13%   |
| BEHRINGER International              | 8         | 0.11%   |
| Razer USA                            | 7         | 0.1%    |
| Focusrite-Novation                   | 7         | 0.1%    |
| Sony                                 | 6         | 0.08%   |
| Samson Technologies                  | 6         | 0.08%   |
| AOKEO                                | 6         | 0.08%   |
| RODE Microphones                     | 5         | 0.07%   |
| M-Audio                              | 5         | 0.07%   |
| AudioQuest                           | 5         | 0.07%   |
| Valve Software                       | 4         | 0.06%   |
| Trust                                | 4         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.06%   |
| OS AS700 USB                         | 4         | 0.06%   |
| Micro Star International             | 4         | 0.06%   |
| Corsair                              | 4         | 0.06%   |
| Sennheiser Communications            | 3         | 0.04%   |
| ROCCAT                               | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 404       | 4.82%   |
| AMD Family 17h/19h HD Audio Controller                                     | 394       | 4.7%    |
| Intel Sunrise Point-LP HD Audio                                            | 328       | 3.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 321       | 3.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 267       | 3.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 228       | 2.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 217       | 2.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 203       | 2.42%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 200       | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 174       | 2.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 173       | 2.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 172       | 2.05%   |
| AMD Starship/Matisse HD Audio Controller                                   | 172       | 2.05%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 171       | 2.04%   |
| AMD FCH Azalia Controller                                                  | 159       | 1.9%    |
| Intel 8 Series HD Audio Controller                                         | 144       | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                      | 142       | 1.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 142       | 1.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 129       | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                            | 122       | 1.45%   |
| Intel Broadwell-U Audio Controller                                         | 120       | 1.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 120       | 1.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 117       | 1.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 113       | 1.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 110       | 1.31%   |
| Nvidia GF108 High Definition Audio Controller                              | 101       | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 93        | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 89        | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 82        | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                              | 78        | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 76        | 0.91%   |
| Intel 200 Series PCH HD Audio                                              | 74        | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 70        | 0.83%   |
| Nvidia TU116 High Definition Audio Controller                              | 67        | 0.8%    |
| Intel CM238 HD Audio Controller                                            | 65        | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                              | 59        | 0.7%    |
| AMD Kabini HDMI/DP Audio                                                   | 59        | 0.7%    |
| Nvidia High Definition Audio Controller                                    | 58        | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 58        | 0.69%   |
| Intel Comet Lake PCH-LP cAVS                                               | 58        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 822       | 21.3%   |
| SK hynix                     | 644       | 16.68%  |
| Kingston                     | 507       | 13.13%  |
| Unknown                      | 430       | 11.14%  |
| Micron Technology            | 329       | 8.52%   |
| GOODRAM                      | 237       | 6.14%   |
| Crucial                      | 170       | 4.4%    |
| G.Skill                      | 110       | 2.85%   |
| Corsair                      | 91        | 2.36%   |
| A-DATA Technology            | 82        | 2.12%   |
| Ramaxel Technology           | 72        | 1.87%   |
| Nanya Technology             | 59        | 1.53%   |
| Patriot                      | 58        | 1.5%    |
| Elpida                       | 54        | 1.4%    |
| Unknown                      | 28        | 0.73%   |
| Unknown (ABCD)               | 20        | 0.52%   |
| Wilk                         | 17        | 0.44%   |
| Qimonda                      | 13        | 0.34%   |
| Apacer                       | 12        | 0.31%   |
| Wilk Elektronik              | 10        | 0.26%   |
| GeIL                         | 10        | 0.26%   |
| ASint Technology             | 9         | 0.23%   |
| Silicon Power                | 6         | 0.16%   |
| Patriot Memory (PDP Systems) | 5         | 0.13%   |
| 48spaces                     | 5         | 0.13%   |
| Unifosa                      | 4         | 0.1%    |
| Transcend                    | 4         | 0.1%    |
| Team                         | 4         | 0.1%    |
| fef5                         | 4         | 0.1%    |
| Toshiba                      | 3         | 0.08%   |
| OCZ                          | 3         | 0.08%   |
| SHARETRONIC                  | 2         | 0.05%   |
| PNY                          | 2         | 0.05%   |
| Lexar                        | 2         | 0.05%   |
| KingFast                     | 2         | 0.05%   |
| ff                           | 2         | 0.05%   |
| ChangXin Memory              | 2         | 0.05%   |
| AMD                          | 2         | 0.05%   |
| Aeneon                       | 2         | 0.05%   |
| 4ea5                         | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 42        | 1%      |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s     | 37        | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 34        | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 32        | 0.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 31        | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 29        | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 29        | 0.69%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 28        | 0.66%   |
| Unknown                                                   | 28        | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 27        | 0.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 26        | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 26        | 0.62%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s   | 25        | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 24        | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 24        | 0.57%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s   | 22        | 0.52%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s  | 21        | 0.5%    |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s     | 19        | 0.45%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 18        | 0.43%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s    | 18        | 0.43%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s   | 17        | 0.4%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 17        | 0.4%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s          | 16        | 0.38%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 16        | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 16        | 0.38%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 16        | 0.38%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s        | 16        | 0.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 16        | 0.38%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s     | 16        | 0.38%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 15        | 0.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 15        | 0.36%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 15        | 0.36%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 15        | 0.36%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 15        | 0.36%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 14        | 0.33%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 14        | 0.33%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 14        | 0.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 14        | 0.33%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s       | 14        | 0.33%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s   | 14        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1323      | 40.43%  |
| DDR3    | 1189      | 36.34%  |
| DDR2    | 244       | 7.46%   |
| Unknown | 154       | 4.71%   |
| SDRAM   | 142       | 4.34%   |
| LPDDR4  | 82        | 2.51%   |
| LPDDR3  | 45        | 1.38%   |
| DDR5    | 35        | 1.07%   |
| DDR     | 33        | 1.01%   |
| LPDDR5  | 17        | 0.52%   |
| DRAM    | 8         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1946      | 60.53%  |
| DIMM            | 1119      | 34.81%  |
| Row Of Chips    | 120       | 3.73%   |
| Chip            | 13        | 0.4%    |
| Unknown         | 13        | 0.4%    |
| RIMM            | 2         | 0.06%   |
| Proprietary Car | 1         | 0.03%   |
| FB-DIMM         | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 1165      | 32.24%  |
| 4096    | 976       | 27.01%  |
| 2048    | 592       | 16.39%  |
| 16384   | 513       | 14.2%   |
| 1024    | 212       | 5.87%   |
| 32768   | 116       | 3.21%   |
| 512     | 28        | 0.77%   |
| Unknown | 4         | 0.11%   |
| 131072  | 2         | 0.06%   |
| 1536    | 2         | 0.06%   |
| 256     | 2         | 0.06%   |
| 64      | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 811       | 22.59%  |
| 3200    | 449       | 12.51%  |
| 2667    | 447       | 12.45%  |
| 1333    | 228       | 6.35%   |
| 2400    | 211       | 5.88%   |
| 1334    | 148       | 4.12%   |
| 2133    | 146       | 4.07%   |
| 667     | 134       | 3.73%   |
| 800     | 128       | 3.57%   |
| 3600    | 83        | 2.31%   |
| Unknown | 81        | 2.26%   |
| 1067    | 58        | 1.62%   |
| 1867    | 48        | 1.34%   |
| 4199    | 46        | 1.28%   |
| 3266    | 35        | 0.97%   |
| 533     | 32        | 0.89%   |
| 3000    | 29        | 0.81%   |
| 2048    | 29        | 0.81%   |
| 1066    | 29        | 0.81%   |
| 975     | 28        | 0.78%   |
| 4800    | 27        | 0.75%   |
| 3733    | 25        | 0.7%    |
| 4267    | 24        | 0.67%   |
| 400     | 22        | 0.61%   |
| 1800    | 21        | 0.58%   |
| 2933    | 20        | 0.56%   |
| 1866    | 20        | 0.56%   |
| 6400    | 19        | 0.53%   |
| 3400    | 19        | 0.53%   |
| 2666    | 19        | 0.53%   |
| 3866    | 17        | 0.47%   |
| 8400    | 11        | 0.31%   |
| 3533    | 11        | 0.31%   |
| 3333    | 10        | 0.28%   |
| 333     | 10        | 0.28%   |
| 3800    | 9         | 0.25%   |
| 2866    | 8         | 0.22%   |
| 4266    | 7         | 0.19%   |
| 3933    | 7         | 0.19%   |
| 3466    | 6         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 52        | 44.83%  |
| Samsung Electronics   | 15        | 12.93%  |
| Brother Industries    | 14        | 12.07%  |
| Canon                 | 11        | 9.48%   |
| Seiko Epson           | 7         | 6.03%   |
| Prolific Technology   | 5         | 4.31%   |
| Lexmark International | 4         | 3.45%   |
| Zebra                 | 3         | 2.59%   |
| Xerox                 | 2         | 1.72%   |
| Minolta               | 1         | 0.86%   |
| MIIIW                 | 1         | 0.86%   |
| Datamax-O'Neil        | 1         | 0.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port           | 5         | 4.24%   |
| HP LaserJet 1020                        | 5         | 4.24%   |
| Samsung M2020 Series                    | 3         | 2.54%   |
| HP LaserJet P2015 series                | 3         | 2.54%   |
| HP LaserJet M14-M17                     | 3         | 2.54%   |
| Canon iP7200 series                     | 3         | 2.54%   |
| Seiko Epson AL-M310DN                   | 2         | 1.69%   |
| Samsung SCX-3400 Series                 | 2         | 1.69%   |
| Samsung ML-216x Series Laser Printer    | 2         | 1.69%   |
| Samsung ML-2010P Mono Laser Printer     | 2         | 1.69%   |
| HP LaserJet P1102                       | 2         | 1.69%   |
| HP Deskjet F4500 series                 | 2         | 1.69%   |
| HP DeskJet F4100 Printer series         | 2         | 1.69%   |
| HP Deskjet F2280 series                 | 2         | 1.69%   |
| HP DeskJet 845c                         | 2         | 1.69%   |
| HP DeskJet 840c                         | 2         | 1.69%   |
| HP DeskJet 4530 series                  | 2         | 1.69%   |
| HP DeskJet 3700 series                  | 2         | 1.69%   |
| HP DeskJet 2600 series                  | 2         | 1.69%   |
| HP Deskjet 2540 series                  | 2         | 1.69%   |
| HP Deskjet 1050 J410                    | 2         | 1.69%   |
| Canon PIXMA MG5600 Series               | 2         | 1.69%   |
| Canon LiDE 400                          | 2         | 1.69%   |
| Brother DCP-J105                        | 2         | 1.69%   |
| Brother DCP-1610W                       | 2         | 1.69%   |
| Zebra ZTC GX420t                        | 1         | 0.85%   |
| Zebra LP2844 Printer                    | 1         | 0.85%   |
| Zebra LP2824                            | 1         | 0.85%   |
| Xerox WorkCentre PE16                   | 1         | 0.85%   |
| Xerox Phaser 6000B                      | 1         | 0.85%   |
| Seiko Epson Stylus NX230/SX235W Series  | 1         | 0.85%   |
| Seiko Epson L405 Series                 | 1         | 0.85%   |
| Seiko Epson L1110 Series                | 1         | 0.85%   |
| Seiko Epson ET-2710 Series              | 1         | 0.85%   |
| Seiko Epson ET-2600 Series              | 1         | 0.85%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 0.85%   |
| Samsung SCX-6545 Series                 | 1         | 0.85%   |
| Samsung SCX-4300 Series                 | 1         | 0.85%   |
| Samsung SCX-4200 series                 | 1         | 0.85%   |
| Samsung ML-3050/ML-3051 Laser Printer   | 1         | 0.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 13        | 61.9%   |
| Seiko Epson                 | 2         | 9.52%   |
| Plustek                     | 2         | 9.52%   |
| Ultima Electronics          | 1         | 4.76%   |
| Mustek Systems              | 1         | 4.76%   |
| Microtek International      | 1         | 4.76%   |
| Acer Peripherals (now BenQ) | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 5         | 23.81%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 9.52%   |
| Canon CanoScan LiDE 120                                  | 2         | 9.52%   |
| Canon CanoScan LiDE 110                                  | 2         | 9.52%   |
| Ultima Artec E+ 48U                                      | 1         | 4.76%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 4.76%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 4.76%   |
| Plustek OpticSlim 1200 Scanner                           | 1         | 4.76%   |
| Plustek OpticPro 1248U Scanner #2                        | 1         | 4.76%   |
| Mustek Systems BearPaw 2448 TA Pro                       | 1         | 4.76%   |
| Microtek International USB1200 Scanner                   | 1         | 4.76%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 4.76%   |
| Canon CanoScan LIDE 25                                   | 1         | 4.76%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 668       | 22.32%  |
| Microdia                               | 291       | 9.72%   |
| IMC Networks                           | 282       | 9.42%   |
| Realtek Semiconductor                  | 252       | 8.42%   |
| Bison Electronics                      | 186       | 6.21%   |
| Sunplus Innovation Technology          | 151       | 5.05%   |
| Quanta                                 | 135       | 4.51%   |
| Suyin                                  | 118       | 3.94%   |
| Logitech                               | 114       | 3.81%   |
| Cheng Uei Precision Industry (Foxlink) | 96        | 3.21%   |
| Syntek                                 | 88        | 2.94%   |
| Lite-On Technology                     | 66        | 2.21%   |
| Silicon Motion                         | 60        | 2%      |
| Apple                                  | 45        | 1.5%    |
| Acer                                   | 45        | 1.5%    |
| Creative Technology                    | 36        | 1.2%    |
| Luxvisions Innotech Limited            | 33        | 1.1%    |
| Ricoh                                  | 32        | 1.07%   |
| Alcor Micro                            | 31        | 1.04%   |
| Lenovo                                 | 29        | 0.97%   |
| Z-Star Microelectronics                | 24        | 0.8%    |
| Samsung Electronics                    | 24        | 0.8%    |
| Microsoft                              | 21        | 0.7%    |
| Sonix Technology                       | 14        | 0.47%   |
| Intel                                  | 11        | 0.37%   |
| DigiTech                               | 11        | 0.37%   |
| Primax Electronics                     | 10        | 0.33%   |
| Generalplus Technology                 | 9         | 0.3%    |
| Cubeternet                             | 9         | 0.3%    |
| ALi                                    | 9         | 0.3%    |
| Jieli Technology                       | 8         | 0.27%   |
| Hewlett-Packard                        | 7         | 0.23%   |
| SunplusIT                              | 5         | 0.17%   |
| Importek                               | 5         | 0.17%   |
| Trust                                  | 4         | 0.13%   |
| Sunplus Technology                     | 4         | 0.13%   |
| Razer USA                              | 4         | 0.13%   |
| MacroSilicon                           | 4         | 0.13%   |
| LG Electronics                         | 4         | 0.13%   |
| GEMBIRD                                | 4         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 136       | 4.53%   |
| Microdia Integrated_Webcam_HD            | 94        | 3.13%   |
| Realtek Integrated_Webcam_HD             | 79        | 2.63%   |
| IMC Networks Integrated Camera           | 77        | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam        | 69        | 2.3%    |
| Sunplus Integrated_Webcam_HD             | 56        | 1.86%   |
| Chicony Lenovo EasyCamera                | 48        | 1.6%    |
| Microdia Integrated Webcam               | 43        | 1.43%   |
| Bison Lenovo EasyCamera                  | 42        | 1.4%    |
| Chicony HD WebCam                        | 41        | 1.36%   |
| Bison Integrated Camera                  | 37        | 1.23%   |
| Syntek Integrated Camera                 | 36        | 1.2%    |
| Suyin Integrated_Webcam_HD               | 36        | 1.2%    |
| Syntek Lenovo EasyCamera                 | 32        | 1.06%   |
| Lite-On Integrated Camera                | 30        | 1%      |
| Realtek Lenovo EasyCamera                | 29        | 0.97%   |
| Quanta HP TrueVision HD Camera           | 28        | 0.93%   |
| Chicony HP HD Camera                     | 28        | 0.93%   |
| Logitech Webcam C270                     | 27        | 0.9%    |
| Realtek USB Camera                       | 25        | 0.83%   |
| Bison Lenovo Integrated Webcam           | 25        | 0.83%   |
| Realtek Integrated Webcam HD             | 23        | 0.77%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 23        | 0.77%   |
| Chicony USB2.0 HD UVC WebCam             | 23        | 0.77%   |
| Samsung Galaxy series, misc. (MTP mode)  | 22        | 0.73%   |
| Bison SunplusIT Integrated Camera        | 21        | 0.7%    |
| Suyin Acer/HP Integrated Webcam [CN0314] | 20        | 0.67%   |
| Quanta HD User Facing                    | 20        | 0.67%   |
| Microdia Laptop_Integrated_Webcam_HD     | 20        | 0.67%   |
| Chicony Integrated Camera (1280x720@30)  | 19        | 0.63%   |
| Realtek Integrated Webcam                | 18        | 0.6%    |
| Creative Live! Cam Sync HD [VF0770]      | 18        | 0.6%    |
| Chicony USB2.0 VGA UVC WebCam            | 18        | 0.6%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 18        | 0.6%    |
| IMC Networks Integrated Webcam           | 17        | 0.57%   |
| Sunplus HD WebCam                        | 16        | 0.53%   |
| Acer Integrated Camera                   | 16        | 0.53%   |
| Logitech HD Pro Webcam C920              | 15        | 0.5%    |
| Lite-On HP HD Camera                     | 15        | 0.5%    |
| Chicony Lenovo Integrated Camera (0.3MP) | 15        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 213       | 36.16%  |
| Synaptics                          | 146       | 24.79%  |
| Shenzhen Goodix Technology         | 74        | 12.56%  |
| AuthenTec                          | 63        | 10.7%   |
| Upek                               | 38        | 6.45%   |
| Elan Microelectronics              | 23        | 3.9%    |
| LighTuning Technology              | 16        | 2.72%   |
| STMicroelectronics                 | 14        | 2.38%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.34%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 46        | 7.81%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 7.13%   |
| Shenzhen Goodix  Fingerprint Device                                        | 42        | 7.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 36        | 6.11%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 30        | 5.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 26        | 4.41%   |
| Shenzhen Goodix Fingerprint Reader                                         | 25        | 4.24%   |
| AuthenTec AES2810                                                          | 25        | 4.24%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 24        | 4.07%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 18        | 3.06%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 2.72%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 15        | 2.55%   |
| Synaptics Fingerprint reader [HP G6]                                       | 15        | 2.55%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.38%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 2.38%   |
| Elan ELAN:Fingerprint                                                      | 14        | 2.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 13        | 2.21%   |
| Validity Sensors VFS491                                                    | 13        | 2.21%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 12        | 2.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.7%    |
| Validity Sensors Fingerprint scanner                                       | 10        | 1.7%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.53%   |
| Synaptics  WBDI                                                            | 9         | 1.53%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.53%   |
| Elan ELAN:ARM-M4                                                           | 8         | 1.36%   |
| AuthenTec AES1600                                                          | 8         | 1.36%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 1.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.19%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.19%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.02%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.85%   |
| Synaptics WBDI                                                             | 5         | 0.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.85%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.68%   |
| Synaptics UWP WBDI                                                         | 4         | 0.68%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.68%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.68%   |
| Synaptics WBDI Device                                                      | 3         | 0.51%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 238       | 55.09%  |
| Alcor Micro               | 90        | 20.83%  |
| O2 Micro                  | 45        | 10.42%  |
| Upek                      | 22        | 5.09%   |
| Lenovo                    | 20        | 4.63%   |
| Gemalto (was Gemplus)     | 5         | 1.16%   |
| Advanced Card Systems     | 3         | 0.69%   |
| OmniKey                   | 2         | 0.46%   |
| Clay Logic                | 2         | 0.46%   |
| Cherry                    | 2         | 0.46%   |
| SCM Microsystems          | 1         | 0.23%   |
| Reiner SCT Kartensysteme  | 1         | 0.23%   |
| Aladdin Knowledge Systems | 1         | 0.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 87        | 20.14%  |
| Broadcom BCM5880 Secure Applications Processor                               | 74        | 17.13%  |
| Broadcom 58200                                                               | 64        | 14.81%  |
| Broadcom 5880                                                                | 57        | 13.19%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 42        | 9.72%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 38        | 8.8%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 5.09%   |
| Lenovo Integrated Smart Card Reader                                          | 20        | 4.63%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.62%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.69%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.46%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.46%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.46%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.46%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.46%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.23%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.23%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.23%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.23%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.23%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.23%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.23%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3576      | 67.61%  |
| 1     | 1351      | 25.54%  |
| 2     | 300       | 5.67%   |
| 3     | 47        | 0.89%   |
| 4     | 7         | 0.13%   |
| 7     | 3         | 0.06%   |
| 5     | 3         | 0.06%   |
| 6     | 2         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 582       | 28.2%   |
| Graphics card            | 484       | 23.45%  |
| Chipcard                 | 384       | 18.6%   |
| Net/wireless             | 182       | 8.82%   |
| Multimedia controller    | 75        | 3.63%   |
| Communication controller | 58        | 2.81%   |
| Bluetooth                | 57        | 2.76%   |
| Storage                  | 54        | 2.62%   |
| Camera                   | 44        | 2.13%   |
| Unassigned class         | 37        | 1.79%   |
| Sound                    | 25        | 1.21%   |
| Card reader              | 19        | 0.92%   |
| Net/ethernet             | 11        | 0.53%   |
| Modem                    | 11        | 0.53%   |
| Network                  | 9         | 0.44%   |
| Firewire controller      | 8         | 0.39%   |
| Storage/ide              | 6         | 0.29%   |
| Dvb card                 | 6         | 0.29%   |
| Storage/raid             | 4         | 0.19%   |
| Flash memory             | 4         | 0.19%   |
| Wireless                 | 1         | 0.05%   |
| Unclassified device      | 1         | 0.05%   |
| Tv card                  | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |

