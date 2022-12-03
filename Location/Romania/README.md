Linux in Romania - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Romania.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Romania/Desktop/README.md) and [notebooks](/Location/Romania/Notebook/README.md).

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

Total: 2256

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | G41M-S03                    | Desktop     | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1FR0... | Notebook    | [517347d2cf](https://linux-hardware.org/?probe=517347d2cf) | Nov 30, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b7a1fc62d1](https://linux-hardware.org/?probe=b7a1fc62d1) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [972f6f4355](https://linux-hardware.org/?probe=972f6f4355) | Nov 28, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [5b2f9bfd5c](https://linux-hardware.org/?probe=5b2f9bfd5c) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a39632439e](https://linux-hardware.org/?probe=a39632439e) | Nov 27, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [c58c83e367](https://linux-hardware.org/?probe=c58c83e367) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [85b508d6d3](https://linux-hardware.org/?probe=85b508d6d3) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [16679f50e3](https://linux-hardware.org/?probe=16679f50e3) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a178e673c3](https://linux-hardware.org/?probe=a178e673c3) | Nov 26, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [c1d5a26691](https://linux-hardware.org/?probe=c1d5a26691) | Nov 26, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a41bb9177a](https://linux-hardware.org/?probe=a41bb9177a) | Nov 23, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [6c797b4554](https://linux-hardware.org/?probe=6c797b4554) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [b8379d261b](https://linux-hardware.org/?probe=b8379d261b) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Dell          | Latitude E6410              | Notebook    | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [75af06e026](https://linux-hardware.org/?probe=75af06e026) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c5ec7b9dcc](https://linux-hardware.org/?probe=c5ec7b9dcc) | Nov 20, 2022 |
| Lenovo        | V15 G1 IML 82NB             | Notebook    | [a120cac88b](https://linux-hardware.org/?probe=a120cac88b) | Nov 18, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2089ec3efb](https://linux-hardware.org/?probe=2089ec3efb) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | Desktop     | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Allview       | Allbook H                   | Notebook    | [4de72c8cba](https://linux-hardware.org/?probe=4de72c8cba) | Nov 17, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| HP            | 843B                        | Desktop     | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [30916d8420](https://linux-hardware.org/?probe=30916d8420) | Nov 16, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [a1e3d4527c](https://linux-hardware.org/?probe=a1e3d4527c) | Nov 15, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fef97563a0](https://linux-hardware.org/?probe=fef97563a0) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [61bcea3891](https://linux-hardware.org/?probe=61bcea3891) | Nov 13, 2022 |
| Alienware     | Area-51m                    | Notebook    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| Dell          | Latitude E7270              | Notebook    | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e80d2221f5](https://linux-hardware.org/?probe=e80d2221f5) | Nov 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [8384350121](https://linux-hardware.org/?probe=8384350121) | Nov 08, 2022 |
| Acer          | Aspire A314-35              | Notebook    | [14751e1ae3](https://linux-hardware.org/?probe=14751e1ae3) | Nov 08, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [5800bb0b18](https://linux-hardware.org/?probe=5800bb0b18) | Nov 06, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d2bbf15a](https://linux-hardware.org/?probe=f8d2bbf15a) | Nov 06, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [f435ef302a](https://linux-hardware.org/?probe=f435ef302a) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [55293ff823](https://linux-hardware.org/?probe=55293ff823) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [7dc3ed5f76](https://linux-hardware.org/?probe=7dc3ed5f76) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [1563c60737](https://linux-hardware.org/?probe=1563c60737) | Oct 31, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81A8     | Notebook    | [85efda7536](https://linux-hardware.org/?probe=85efda7536) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [f9238c2035](https://linux-hardware.org/?probe=f9238c2035) | Oct 28, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [9e8ec19352](https://linux-hardware.org/?probe=9e8ec19352) | Oct 26, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [7dca4296ee](https://linux-hardware.org/?probe=7dca4296ee) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [7274eca48b](https://linux-hardware.org/?probe=7274eca48b) | Oct 23, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [18e52559a4](https://linux-hardware.org/?probe=18e52559a4) | Oct 17, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [84941aaa84](https://linux-hardware.org/?probe=84941aaa84) | Oct 14, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [a6a5cdbf04](https://linux-hardware.org/?probe=a6a5cdbf04) | Oct 13, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [478ba58d34](https://linux-hardware.org/?probe=478ba58d34) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| ASUSTek       | V222GAR                     | All in one  | [e7e07dca5c](https://linux-hardware.org/?probe=e7e07dca5c) | Oct 12, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [79236a7a89](https://linux-hardware.org/?probe=79236a7a89) | Oct 11, 2022 |
| Medion        | Akoya E6239                 | Notebook    | [46ce690b32](https://linux-hardware.org/?probe=46ce690b32) | Oct 10, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [abc991002e](https://linux-hardware.org/?probe=abc991002e) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8694ed82a6](https://linux-hardware.org/?probe=8694ed82a6) | Oct 09, 2022 |
| Dell          | Latitude E6410              | Notebook    | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [889099ff63](https://linux-hardware.org/?probe=889099ff63) | Oct 05, 2022 |
| HP            | 2AED                        | All in one  | [9092720ed6](https://linux-hardware.org/?probe=9092720ed6) | Oct 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d9474bd3b9](https://linux-hardware.org/?probe=d9474bd3b9) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [cf4537f9cb](https://linux-hardware.org/?probe=cf4537f9cb) | Oct 02, 2022 |
| Medion        | Akoya P2214T                | Notebook    | [428205d2a5](https://linux-hardware.org/?probe=428205d2a5) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [26961d1b30](https://linux-hardware.org/?probe=26961d1b30) | Sep 29, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [3e92ba3812](https://linux-hardware.org/?probe=3e92ba3812) | Sep 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [96c4c8ba02](https://linux-hardware.org/?probe=96c4c8ba02) | Sep 28, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [11f99758e6](https://linux-hardware.org/?probe=11f99758e6) | Sep 28, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | Notebook    | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [deed57ec88](https://linux-hardware.org/?probe=deed57ec88) | Sep 23, 2022 |
| Acer          | Aspire 5750Z                | Notebook    | [38e1cc9153](https://linux-hardware.org/?probe=38e1cc9153) | Sep 22, 2022 |
| Fusion5       | S14                         | Notebook    | [9b3e06c4e4](https://linux-hardware.org/?probe=9b3e06c4e4) | Sep 22, 2022 |
| Acer          | Aspire 5750Z                | Notebook    | [b673d5cfe9](https://linux-hardware.org/?probe=b673d5cfe9) | Sep 22, 2022 |
| Dell          | Precision 3561              | Notebook    | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [aba8915769](https://linux-hardware.org/?probe=aba8915769) | Sep 19, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [d52ac897f4](https://linux-hardware.org/?probe=d52ac897f4) | Sep 15, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [39f83f7692](https://linux-hardware.org/?probe=39f83f7692) | Sep 13, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2af6edb7a0](https://linux-hardware.org/?probe=2af6edb7a0) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [43311add57](https://linux-hardware.org/?probe=43311add57) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c13cd2c2ac](https://linux-hardware.org/?probe=c13cd2c2ac) | Sep 09, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [3474424d64](https://linux-hardware.org/?probe=3474424d64) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a2962588fa](https://linux-hardware.org/?probe=a2962588fa) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [e47c8e6967](https://linux-hardware.org/?probe=e47c8e6967) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [3f805d59b5](https://linux-hardware.org/?probe=3f805d59b5) | Sep 04, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| Dell          | Latitude 5521               | Notebook    | [dcf7869cf6](https://linux-hardware.org/?probe=dcf7869cf6) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [c129f7c9b1](https://linux-hardware.org/?probe=c129f7c9b1) | Aug 29, 2022 |
| Dell          | Latitude E7470              | Notebook    | [568c9bfd40](https://linux-hardware.org/?probe=568c9bfd40) | Aug 28, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [4c16a58579](https://linux-hardware.org/?probe=4c16a58579) | Aug 28, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [fbf3d4a87a](https://linux-hardware.org/?probe=fbf3d4a87a) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [8b85141416](https://linux-hardware.org/?probe=8b85141416) | Aug 26, 2022 |
| Complet       | MY8312                      | Notebook    | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [09feb7053d](https://linux-hardware.org/?probe=09feb7053d) | Aug 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [69281b6cc3](https://linux-hardware.org/?probe=69281b6cc3) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [2af48f00ac](https://linux-hardware.org/?probe=2af48f00ac) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [0910ca3887](https://linux-hardware.org/?probe=0910ca3887) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| Dell          | Latitude 7410               | Notebook    | [ae90ce90ed](https://linux-hardware.org/?probe=ae90ce90ed) | Aug 22, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [5cbe471be8](https://linux-hardware.org/?probe=5cbe471be8) | Aug 19, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [1a0800fc4a](https://linux-hardware.org/?probe=1a0800fc4a) | Aug 19, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [4b585d8c34](https://linux-hardware.org/?probe=4b585d8c34) | Aug 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [f45a97ca40](https://linux-hardware.org/?probe=f45a97ca40) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [ca6a3b3fba](https://linux-hardware.org/?probe=ca6a3b3fba) | Aug 12, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [cdee8ca864](https://linux-hardware.org/?probe=cdee8ca864) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [eb79423b1d](https://linux-hardware.org/?probe=eb79423b1d) | Aug 12, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [86523f9a5f](https://linux-hardware.org/?probe=86523f9a5f) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [6826a8d40d](https://linux-hardware.org/?probe=6826a8d40d) | Aug 08, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [83626d765b](https://linux-hardware.org/?probe=83626d765b) | Aug 08, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [94d50a1c56](https://linux-hardware.org/?probe=94d50a1c56) | Aug 08, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1fe8a14d3b](https://linux-hardware.org/?probe=1fe8a14d3b) | Aug 06, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| Unknown       | 1.0                         | Desktop     | [4394243123](https://linux-hardware.org/?probe=4394243123) | Aug 05, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | Notebook    | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| Unknown       | 1.0                         | Desktop     | [545d9cf73c](https://linux-hardware.org/?probe=545d9cf73c) | Aug 04, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [fbe4f4d2ce](https://linux-hardware.org/?probe=fbe4f4d2ce) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [eeccdc2b7f](https://linux-hardware.org/?probe=eeccdc2b7f) | Aug 02, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e6bfde2a29](https://linux-hardware.org/?probe=e6bfde2a29) | Jul 29, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8b3fd99e18](https://linux-hardware.org/?probe=8b3fd99e18) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4ee4fc0689](https://linux-hardware.org/?probe=4ee4fc0689) | Jul 26, 2022 |
| HP            | 8704                        | Desktop     | [eaa4bc0059](https://linux-hardware.org/?probe=eaa4bc0059) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | Notebook    | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [892229b650](https://linux-hardware.org/?probe=892229b650) | Jul 21, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [9a5f11c4b9](https://linux-hardware.org/?probe=9a5f11c4b9) | Jul 19, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [383ec7a7fd](https://linux-hardware.org/?probe=383ec7a7fd) | Jul 18, 2022 |
| Acer          | Aspire SW3-016              | Notebook    | [c48cdf5576](https://linux-hardware.org/?probe=c48cdf5576) | Jul 17, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [84cd652e24](https://linux-hardware.org/?probe=84cd652e24) | Jul 16, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [55efce6cdc](https://linux-hardware.org/?probe=55efce6cdc) | Jul 13, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [be909dd3b4](https://linux-hardware.org/?probe=be909dd3b4) | Jul 12, 2022 |
| HP            | 355 G2                      | Notebook    | [55239c5062](https://linux-hardware.org/?probe=55239c5062) | Jul 11, 2022 |
| HP            | 355 G2                      | Notebook    | [9b5e64b838](https://linux-hardware.org/?probe=9b5e64b838) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| HP            | 250 G4                      | Notebook    | [33dcd9203d](https://linux-hardware.org/?probe=33dcd9203d) | Jul 09, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | Notebook    | [99172a6e6f](https://linux-hardware.org/?probe=99172a6e6f) | Jul 08, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [cb302e010e](https://linux-hardware.org/?probe=cb302e010e) | Jul 08, 2022 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [f991c1fba8](https://linux-hardware.org/?probe=f991c1fba8) | Jul 07, 2022 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [a5f338ae1a](https://linux-hardware.org/?probe=a5f338ae1a) | Jul 07, 2022 |
| HP            | ProBook 4310s               | Notebook    | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [32463f298d](https://linux-hardware.org/?probe=32463f298d) | Jul 05, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [457aa90e64](https://linux-hardware.org/?probe=457aa90e64) | Jul 02, 2022 |
| Dell          | Latitude 5521               | Notebook    | [2fda374f06](https://linux-hardware.org/?probe=2fda374f06) | Jun 24, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [70d6947d54](https://linux-hardware.org/?probe=70d6947d54) | Jun 16, 2022 |
| HP            | 1790                        | Desktop     | [341a6c4c70](https://linux-hardware.org/?probe=341a6c4c70) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [1e88796016](https://linux-hardware.org/?probe=1e88796016) | Jun 15, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4b2037715f](https://linux-hardware.org/?probe=4b2037715f) | Jun 15, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| Dell          | Latitude E6440              | Notebook    | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a144e0b75e](https://linux-hardware.org/?probe=a144e0b75e) | Jun 08, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [992f232db5](https://linux-hardware.org/?probe=992f232db5) | Jun 08, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [ef5b8100ce](https://linux-hardware.org/?probe=ef5b8100ce) | Jun 07, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Prestigio     | PSB141C04CGP                | Notebook    | [4fa2ee47c0](https://linux-hardware.org/?probe=4fa2ee47c0) | Jun 01, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [65ae31976a](https://linux-hardware.org/?probe=65ae31976a) | May 31, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [083e3a354a](https://linux-hardware.org/?probe=083e3a354a) | May 29, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [83209051cb](https://linux-hardware.org/?probe=83209051cb) | May 29, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [74c64ebe72](https://linux-hardware.org/?probe=74c64ebe72) | May 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [51aaf4adcd](https://linux-hardware.org/?probe=51aaf4adcd) | May 24, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [3115570400](https://linux-hardware.org/?probe=3115570400) | May 24, 2022 |
| Allview       | Allbook H                   | Notebook    | [9ea4897c6b](https://linux-hardware.org/?probe=9ea4897c6b) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b01633e1ae](https://linux-hardware.org/?probe=b01633e1ae) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [815dbb114b](https://linux-hardware.org/?probe=815dbb114b) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9a6c29a243](https://linux-hardware.org/?probe=9a6c29a243) | May 21, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [739ffac681](https://linux-hardware.org/?probe=739ffac681) | May 21, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [949f8f3e50](https://linux-hardware.org/?probe=949f8f3e50) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [4d2d33c41c](https://linux-hardware.org/?probe=4d2d33c41c) | May 20, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [60579b7d68](https://linux-hardware.org/?probe=60579b7d68) | May 18, 2022 |
| Lenovo        | ThinkPad P53 20QNS01900     | Notebook    | [158f212b30](https://linux-hardware.org/?probe=158f212b30) | May 13, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [550824d592](https://linux-hardware.org/?probe=550824d592) | May 12, 2022 |
| HP            | 0AA8h                       | Desktop     | [7d29587a1a](https://linux-hardware.org/?probe=7d29587a1a) | May 11, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [324d1abe3b](https://linux-hardware.org/?probe=324d1abe3b) | May 08, 2022 |
| HP            | ProBook 4520s               | Notebook    | [06e044a425](https://linux-hardware.org/?probe=06e044a425) | May 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [52c2a321a4](https://linux-hardware.org/?probe=52c2a321a4) | May 07, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [9fe037820e](https://linux-hardware.org/?probe=9fe037820e) | May 05, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [7a6aa0c236](https://linux-hardware.org/?probe=7a6aa0c236) | May 03, 2022 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [713358f855](https://linux-hardware.org/?probe=713358f855) | May 02, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [a8e967a378](https://linux-hardware.org/?probe=a8e967a378) | May 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6537fb670a](https://linux-hardware.org/?probe=6537fb670a) | May 01, 2022 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| HP            | ProBook 4520s               | Notebook    | [60eab2c6c5](https://linux-hardware.org/?probe=60eab2c6c5) | Apr 30, 2022 |
| Pegatron      | Spring Peak                 | Notebook    | [66a1692171](https://linux-hardware.org/?probe=66a1692171) | Apr 30, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [8dd4d42608](https://linux-hardware.org/?probe=8dd4d42608) | Apr 29, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [efcd6be006](https://linux-hardware.org/?probe=efcd6be006) | Apr 27, 2022 |
| Dell          | Latitude E4310              | Notebook    | [41db45879c](https://linux-hardware.org/?probe=41db45879c) | Apr 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [afe44fa080](https://linux-hardware.org/?probe=afe44fa080) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8ece944a7b](https://linux-hardware.org/?probe=8ece944a7b) | Apr 27, 2022 |
| Dell          | Latitude E6520              | Notebook    | [1ca407a69f](https://linux-hardware.org/?probe=1ca407a69f) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bcc0c7612d](https://linux-hardware.org/?probe=bcc0c7612d) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1EH0... | Notebook    | [fae5ee6551](https://linux-hardware.org/?probe=fae5ee6551) | Apr 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [c7dfc69b32](https://linux-hardware.org/?probe=c7dfc69b32) | Apr 26, 2022 |
| HP            | ProBook 4520s               | Notebook    | [1621eddc70](https://linux-hardware.org/?probe=1621eddc70) | Apr 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1d1c33575f](https://linux-hardware.org/?probe=1d1c33575f) | Apr 24, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | Notebook    | [41276f12db](https://linux-hardware.org/?probe=41276f12db) | Apr 23, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | Notebook    | [55733b5ae3](https://linux-hardware.org/?probe=55733b5ae3) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [a551ef1ec7](https://linux-hardware.org/?probe=a551ef1ec7) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [fd6718859d](https://linux-hardware.org/?probe=fd6718859d) | Apr 23, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [2518b6daad](https://linux-hardware.org/?probe=2518b6daad) | Apr 22, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [17d51c502f](https://linux-hardware.org/?probe=17d51c502f) | Apr 22, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [bc175803f2](https://linux-hardware.org/?probe=bc175803f2) | Apr 22, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a3a204ed56](https://linux-hardware.org/?probe=a3a204ed56) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [4521315d14](https://linux-hardware.org/?probe=4521315d14) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [fff2447e5a](https://linux-hardware.org/?probe=fff2447e5a) | Apr 21, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | Notebook    | [de746c72d1](https://linux-hardware.org/?probe=de746c72d1) | Apr 20, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [5d95841f54](https://linux-hardware.org/?probe=5d95841f54) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | Notebook    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [8b54af493a](https://linux-hardware.org/?probe=8b54af493a) | Apr 19, 2022 |
| Dell          | Latitude E6440              | Notebook    | [33955db41e](https://linux-hardware.org/?probe=33955db41e) | Apr 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1825f45bfa](https://linux-hardware.org/?probe=1825f45bfa) | Apr 17, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| HP            | Pavilion 17                 | Notebook    | [acb0c7fd0e](https://linux-hardware.org/?probe=acb0c7fd0e) | Apr 16, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | Notebook    | [a572c901ca](https://linux-hardware.org/?probe=a572c901ca) | Apr 15, 2022 |
| HP            | Pavilion 17                 | Notebook    | [014f42ecee](https://linux-hardware.org/?probe=014f42ecee) | Apr 15, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [73d1368d93](https://linux-hardware.org/?probe=73d1368d93) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9709ffeb9a](https://linux-hardware.org/?probe=9709ffeb9a) | Apr 14, 2022 |
| Dell          | System XPS L702X            | Notebook    | [9ed530100f](https://linux-hardware.org/?probe=9ed530100f) | Apr 13, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [95ddaa1dae](https://linux-hardware.org/?probe=95ddaa1dae) | Apr 13, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ba6f51707b](https://linux-hardware.org/?probe=ba6f51707b) | Apr 13, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [a06e300bfd](https://linux-hardware.org/?probe=a06e300bfd) | Apr 12, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [ffb5635168](https://linux-hardware.org/?probe=ffb5635168) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [59b9f6ab96](https://linux-hardware.org/?probe=59b9f6ab96) | Apr 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [27e9b2e124](https://linux-hardware.org/?probe=27e9b2e124) | Apr 09, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [5fea9b2c3a](https://linux-hardware.org/?probe=5fea9b2c3a) | Apr 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [d49b3ef408](https://linux-hardware.org/?probe=d49b3ef408) | Apr 08, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dd2c447b48](https://linux-hardware.org/?probe=dd2c447b48) | Apr 07, 2022 |
| HP            | 0AA8h                       | Desktop     | [0de7915496](https://linux-hardware.org/?probe=0de7915496) | Apr 06, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [beeceac759](https://linux-hardware.org/?probe=beeceac759) | Apr 04, 2022 |
| Lenovo        | B590 37612LG                | Notebook    | [153a6c2343](https://linux-hardware.org/?probe=153a6c2343) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| HP            | 1790                        | Desktop     | [9b8f0779ab](https://linux-hardware.org/?probe=9b8f0779ab) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [13aa7656f3](https://linux-hardware.org/?probe=13aa7656f3) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [62982f1e80](https://linux-hardware.org/?probe=62982f1e80) | Apr 02, 2022 |
| Medion        | H81H3-EM2                   | Desktop     | [4c887e357d](https://linux-hardware.org/?probe=4c887e357d) | Mar 31, 2022 |
| HP            | 250 G4                      | Notebook    | [69a3535c1a](https://linux-hardware.org/?probe=69a3535c1a) | Mar 30, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [c2d3fbb93e](https://linux-hardware.org/?probe=c2d3fbb93e) | Mar 30, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [ffde31bd20](https://linux-hardware.org/?probe=ffde31bd20) | Mar 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c1e113a82d](https://linux-hardware.org/?probe=c1e113a82d) | Mar 26, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [2bbea411a6](https://linux-hardware.org/?probe=2bbea411a6) | Mar 24, 2022 |
| Dell          | 0C522T A03                  | Desktop     | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [c55e29b1e9](https://linux-hardware.org/?probe=c55e29b1e9) | Mar 22, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [ce6cc28ca1](https://linux-hardware.org/?probe=ce6cc28ca1) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8d1c371df2](https://linux-hardware.org/?probe=8d1c371df2) | Mar 21, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [35da4bbe2c](https://linux-hardware.org/?probe=35da4bbe2c) | Mar 21, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [626ee37f9b](https://linux-hardware.org/?probe=626ee37f9b) | Mar 21, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a93c59159d](https://linux-hardware.org/?probe=a93c59159d) | Mar 20, 2022 |
| Acer          | Swift SF514-55GT            | Notebook    | [ae09c5da41](https://linux-hardware.org/?probe=ae09c5da41) | Mar 20, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [7e8098be12](https://linux-hardware.org/?probe=7e8098be12) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b8b480e048](https://linux-hardware.org/?probe=b8b480e048) | Mar 20, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [a3a8154156](https://linux-hardware.org/?probe=a3a8154156) | Mar 17, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [177d9b8820](https://linux-hardware.org/?probe=177d9b8820) | Mar 16, 2022 |
| Dell          | 05R2TK A01                  | All in one  | [d678cbb1cc](https://linux-hardware.org/?probe=d678cbb1cc) | Mar 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [5da90f10f4](https://linux-hardware.org/?probe=5da90f10f4) | Mar 15, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [4bc060dc9d](https://linux-hardware.org/?probe=4bc060dc9d) | Mar 14, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [28303b98cc](https://linux-hardware.org/?probe=28303b98cc) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a339fe7a39](https://linux-hardware.org/?probe=a339fe7a39) | Mar 13, 2022 |
| Intel         | DG31PR AAD97573-300         | Desktop     | [509c41b106](https://linux-hardware.org/?probe=509c41b106) | Mar 13, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [c82a0d33a2](https://linux-hardware.org/?probe=c82a0d33a2) | Mar 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [e8c3922bb3](https://linux-hardware.org/?probe=e8c3922bb3) | Mar 12, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [6034a2269a](https://linux-hardware.org/?probe=6034a2269a) | Mar 09, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [385d1914ee](https://linux-hardware.org/?probe=385d1914ee) | Mar 07, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [ad5413d163](https://linux-hardware.org/?probe=ad5413d163) | Mar 06, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [3b3220eeee](https://linux-hardware.org/?probe=3b3220eeee) | Mar 06, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [b1ac4ae8e7](https://linux-hardware.org/?probe=b1ac4ae8e7) | Mar 05, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [6d26072b9e](https://linux-hardware.org/?probe=6d26072b9e) | Mar 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [53d74176e9](https://linux-hardware.org/?probe=53d74176e9) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [73881ad12e](https://linux-hardware.org/?probe=73881ad12e) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Dell          | 0XHGV1 A02                  | Desktop     | [768657efd5](https://linux-hardware.org/?probe=768657efd5) | Mar 03, 2022 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [6090fb66ea](https://linux-hardware.org/?probe=6090fb66ea) | Mar 02, 2022 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [c56a98389f](https://linux-hardware.org/?probe=c56a98389f) | Mar 01, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| Medion        | E16402                      | Notebook    | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c57b3c9081](https://linux-hardware.org/?probe=c57b3c9081) | Feb 26, 2022 |
| Lenovo        | ThinkPad 10 20C3S0P900      | Tablet      | [a7034fd62e](https://linux-hardware.org/?probe=a7034fd62e) | Feb 26, 2022 |
| Lenovo        | ThinkPad 10 20C3S0P900      | Tablet      | [61c4a46887](https://linux-hardware.org/?probe=61c4a46887) | Feb 26, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [c8dd47fb82](https://linux-hardware.org/?probe=c8dd47fb82) | Feb 26, 2022 |
| Lenovo        | IdeaPadFlex 5 15ALC05 82... | Convertible | [800ecfe818](https://linux-hardware.org/?probe=800ecfe818) | Feb 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [402a27e190](https://linux-hardware.org/?probe=402a27e190) | Feb 24, 2022 |
| ASUSTek       | X55U                        | Notebook    | [c7c38f077d](https://linux-hardware.org/?probe=c7c38f077d) | Feb 24, 2022 |
| HP            | 84DE                        | All in one  | [43184fd6bf](https://linux-hardware.org/?probe=43184fd6bf) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6083eed5da](https://linux-hardware.org/?probe=6083eed5da) | Feb 21, 2022 |
| Lenovo        | ThinkPad T430 2349U15       | Notebook    | [38a194c33d](https://linux-hardware.org/?probe=38a194c33d) | Feb 20, 2022 |
| MSI           | MS-7392                     | Desktop     | [c64a5b4adf](https://linux-hardware.org/?probe=c64a5b4adf) | Feb 20, 2022 |
| MSI           | MS-7392                     | Desktop     | [308ed6c0c6](https://linux-hardware.org/?probe=308ed6c0c6) | Feb 20, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [417a759484](https://linux-hardware.org/?probe=417a759484) | Feb 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [dfc7dad0ee](https://linux-hardware.org/?probe=dfc7dad0ee) | Feb 17, 2022 |
| Lenovo        | ThinkPad P50 20ENS0FQ00     | Notebook    | [8d8e30fdfb](https://linux-hardware.org/?probe=8d8e30fdfb) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [5d2de5cd73](https://linux-hardware.org/?probe=5d2de5cd73) | Feb 17, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [be010e2d04](https://linux-hardware.org/?probe=be010e2d04) | Feb 17, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [fec0662c03](https://linux-hardware.org/?probe=fec0662c03) | Feb 16, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [f6383e06d7](https://linux-hardware.org/?probe=f6383e06d7) | Feb 16, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [13989d56ec](https://linux-hardware.org/?probe=13989d56ec) | Feb 14, 2022 |
| MSI           | EX620                       | Notebook    | [8eda01e2a8](https://linux-hardware.org/?probe=8eda01e2a8) | Feb 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e48e07387e](https://linux-hardware.org/?probe=e48e07387e) | Feb 13, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [be994742e1](https://linux-hardware.org/?probe=be994742e1) | Feb 13, 2022 |
| HP            | 09F8h                       | Desktop     | [d887fef9ff](https://linux-hardware.org/?probe=d887fef9ff) | Feb 13, 2022 |
| HP            | EliteBook 8530p             | Notebook    | [6b45115b9e](https://linux-hardware.org/?probe=6b45115b9e) | Feb 13, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [eeeac91ae4](https://linux-hardware.org/?probe=eeeac91ae4) | Feb 13, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [a016adec7d](https://linux-hardware.org/?probe=a016adec7d) | Feb 12, 2022 |
| HP            | 339A                        | Desktop     | [a4eac4d7b8](https://linux-hardware.org/?probe=a4eac4d7b8) | Feb 11, 2022 |
| Lenovo        | NOK                         | Desktop     | [f860aaeaf3](https://linux-hardware.org/?probe=f860aaeaf3) | Feb 11, 2022 |
| HP            | 0AA8h                       | Desktop     | [a78b5c3460](https://linux-hardware.org/?probe=a78b5c3460) | Feb 10, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [5e071a1807](https://linux-hardware.org/?probe=5e071a1807) | Feb 09, 2022 |
| Lenovo        | ThinkPad T410 2522Y15       | Notebook    | [66a496ba4c](https://linux-hardware.org/?probe=66a496ba4c) | Feb 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7d600bcdc7](https://linux-hardware.org/?probe=7d600bcdc7) | Feb 08, 2022 |
| Lenovo        | ThinkPad L380 20M5003FUK    | Notebook    | [fe486b4de6](https://linux-hardware.org/?probe=fe486b4de6) | Feb 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS3W300    | Notebook    | [a49c14ab70](https://linux-hardware.org/?probe=a49c14ab70) | Feb 06, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [275d33a826](https://linux-hardware.org/?probe=275d33a826) | Feb 06, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [23b715cc77](https://linux-hardware.org/?probe=23b715cc77) | Feb 05, 2022 |
| Allview       | Allbook H                   | Notebook    | [f1ba3f22c4](https://linux-hardware.org/?probe=f1ba3f22c4) | Feb 05, 2022 |
| Gigabyte      | P35-DS3R                    | Desktop     | [3164a5ed5b](https://linux-hardware.org/?probe=3164a5ed5b) | Feb 05, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [4975c3b6b7](https://linux-hardware.org/?probe=4975c3b6b7) | Feb 05, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [5eaea69c49](https://linux-hardware.org/?probe=5eaea69c49) | Feb 04, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [d554447e6b](https://linux-hardware.org/?probe=d554447e6b) | Feb 04, 2022 |
| HP            | Pavilion dv6                | Notebook    | [63c8ab5447](https://linux-hardware.org/?probe=63c8ab5447) | Feb 03, 2022 |
| HP            | EliteBook x360 1040 G5      | Notebook    | [4aa3aa1f30](https://linux-hardware.org/?probe=4aa3aa1f30) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [1e330f1e0e](https://linux-hardware.org/?probe=1e330f1e0e) | Feb 02, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [5d9bab6a00](https://linux-hardware.org/?probe=5d9bab6a00) | Feb 02, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [94fefac9e1](https://linux-hardware.org/?probe=94fefac9e1) | Feb 01, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [b80429c5fe](https://linux-hardware.org/?probe=b80429c5fe) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [7c2762f41c](https://linux-hardware.org/?probe=7c2762f41c) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [2aa45a8d1b](https://linux-hardware.org/?probe=2aa45a8d1b) | Jan 31, 2022 |
| Acer          | RS880M05                    | Desktop     | [43b14c0f42](https://linux-hardware.org/?probe=43b14c0f42) | Jan 31, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [b61bba90ad](https://linux-hardware.org/?probe=b61bba90ad) | Jan 30, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Acer          | Extensa 2510                | Notebook    | [1fcabc0254](https://linux-hardware.org/?probe=1fcabc0254) | Jan 26, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [3bcb1d5f53](https://linux-hardware.org/?probe=3bcb1d5f53) | Jan 25, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [6d62bb9596](https://linux-hardware.org/?probe=6d62bb9596) | Jan 24, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [0e47f03d64](https://linux-hardware.org/?probe=0e47f03d64) | Jan 24, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [ded9015aff](https://linux-hardware.org/?probe=ded9015aff) | Jan 23, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [6ab6d3c8b2](https://linux-hardware.org/?probe=6ab6d3c8b2) | Jan 23, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [d90de3e8f7](https://linux-hardware.org/?probe=d90de3e8f7) | Jan 21, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [3609f04919](https://linux-hardware.org/?probe=3609f04919) | Jan 19, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [8e66dbbe5c](https://linux-hardware.org/?probe=8e66dbbe5c) | Jan 19, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [d4187f35fd](https://linux-hardware.org/?probe=d4187f35fd) | Jan 19, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [2f55e0a142](https://linux-hardware.org/?probe=2f55e0a142) | Jan 19, 2022 |
| Dell          | MXG071                      | Notebook    | [cd914ee2f0](https://linux-hardware.org/?probe=cd914ee2f0) | Jan 18, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [e4489c39b8](https://linux-hardware.org/?probe=e4489c39b8) | Jan 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [4b51693e30](https://linux-hardware.org/?probe=4b51693e30) | Jan 17, 2022 |
| Lenovo        | ThinkPad X61s 7666WCQ       | Notebook    | [7e1d764ca8](https://linux-hardware.org/?probe=7e1d764ca8) | Jan 16, 2022 |
| Samsung       | R580/R590                   | Notebook    | [be1e77de84](https://linux-hardware.org/?probe=be1e77de84) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [342f6f2beb](https://linux-hardware.org/?probe=342f6f2beb) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [34f103b8d2](https://linux-hardware.org/?probe=34f103b8d2) | Jan 16, 2022 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [12db3650f6](https://linux-hardware.org/?probe=12db3650f6) | Jan 14, 2022 |
| MSI           | 2A9C                        | Desktop     | [09004ce71d](https://linux-hardware.org/?probe=09004ce71d) | Jan 14, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [efe75d8f3f](https://linux-hardware.org/?probe=efe75d8f3f) | Jan 14, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [6976b6ebbd](https://linux-hardware.org/?probe=6976b6ebbd) | Jan 14, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [15dd95fdfd](https://linux-hardware.org/?probe=15dd95fdfd) | Jan 14, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [615ed31a98](https://linux-hardware.org/?probe=615ed31a98) | Jan 13, 2022 |
| Acer          | Aspire T3-710 V:1.1         | Desktop     | [088a0a9608](https://linux-hardware.org/?probe=088a0a9608) | Jan 12, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [5f41c8e050](https://linux-hardware.org/?probe=5f41c8e050) | Jan 12, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [56d6ea164b](https://linux-hardware.org/?probe=56d6ea164b) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d9bd1bab23](https://linux-hardware.org/?probe=d9bd1bab23) | Jan 09, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [353534e82a](https://linux-hardware.org/?probe=353534e82a) | Jan 08, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [ba78c8aef3](https://linux-hardware.org/?probe=ba78c8aef3) | Jan 07, 2022 |
| HP            | 843B                        | Desktop     | [24e5dae02e](https://linux-hardware.org/?probe=24e5dae02e) | Jan 07, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [1630e680bc](https://linux-hardware.org/?probe=1630e680bc) | Jan 06, 2022 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [3e7d72e09a](https://linux-hardware.org/?probe=3e7d72e09a) | Jan 06, 2022 |
| Chuwi         | Hero Book                   | Notebook    | [b111f44fad](https://linux-hardware.org/?probe=b111f44fad) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Dell          | Inspiron 7586               | Convertible | [9a480f9de9](https://linux-hardware.org/?probe=9a480f9de9) | Jan 04, 2022 |
| ASUSTek       | X550VL                      | Notebook    | [46ed51f6ef](https://linux-hardware.org/?probe=46ed51f6ef) | Jan 04, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [0132076c85](https://linux-hardware.org/?probe=0132076c85) | Jan 04, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| Lenovo        | ThinkPad X220 4291B78       | Notebook    | [76350af57f](https://linux-hardware.org/?probe=76350af57f) | Jan 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a7217db810](https://linux-hardware.org/?probe=a7217db810) | Jan 02, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [286ce69daf](https://linux-hardware.org/?probe=286ce69daf) | Jan 02, 2022 |
| HP            | 1497                        | Desktop     | [540458f943](https://linux-hardware.org/?probe=540458f943) | Jan 02, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [f5eafcc9e4](https://linux-hardware.org/?probe=f5eafcc9e4) | Jan 02, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [50a5dc78eb](https://linux-hardware.org/?probe=50a5dc78eb) | Jan 02, 2022 |
| MSI           | EX705                       | Notebook    | [a969bd4369](https://linux-hardware.org/?probe=a969bd4369) | Dec 31, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [64743b9e56](https://linux-hardware.org/?probe=64743b9e56) | Dec 30, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [a8b3cc88b1](https://linux-hardware.org/?probe=a8b3cc88b1) | Dec 29, 2021 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [af923f06cc](https://linux-hardware.org/?probe=af923f06cc) | Dec 29, 2021 |
| Dell          | Latitude E5420m             | Notebook    | [6f5af5da5c](https://linux-hardware.org/?probe=6f5af5da5c) | Dec 29, 2021 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [a7a37c26c7](https://linux-hardware.org/?probe=a7a37c26c7) | Dec 29, 2021 |
| Dream Mach... | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [c3f88b03df](https://linux-hardware.org/?probe=c3f88b03df) | Dec 28, 2021 |
| Lenovo        | ThinkStation E20 4220RF8    | Desktop     | [e525340bef](https://linux-hardware.org/?probe=e525340bef) | Dec 28, 2021 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [82a0c6cd43](https://linux-hardware.org/?probe=82a0c6cd43) | Dec 28, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b2b9ea9e60](https://linux-hardware.org/?probe=b2b9ea9e60) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 4291B78       | Notebook    | [2c8a912b3e](https://linux-hardware.org/?probe=2c8a912b3e) | Dec 24, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [e4dc4b8711](https://linux-hardware.org/?probe=e4dc4b8711) | Dec 23, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [d6d85114b6](https://linux-hardware.org/?probe=d6d85114b6) | Dec 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1f334f4c1c](https://linux-hardware.org/?probe=1f334f4c1c) | Dec 22, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [85da21d9e9](https://linux-hardware.org/?probe=85da21d9e9) | Dec 22, 2021 |
| HP            | 18E7                        | Desktop     | [b233eb9f3e](https://linux-hardware.org/?probe=b233eb9f3e) | Dec 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [6748ebc68a](https://linux-hardware.org/?probe=6748ebc68a) | Dec 20, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [0a48d9579b](https://linux-hardware.org/?probe=0a48d9579b) | Dec 19, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [00868d9166](https://linux-hardware.org/?probe=00868d9166) | Dec 17, 2021 |
| HP            | 1998                        | Desktop     | [9bfa0ed638](https://linux-hardware.org/?probe=9bfa0ed638) | Dec 17, 2021 |
| Timi          | TM1701                      | Notebook    | [f063712cce](https://linux-hardware.org/?probe=f063712cce) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [ac40d89d27](https://linux-hardware.org/?probe=ac40d89d27) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [7da5a1020d](https://linux-hardware.org/?probe=7da5a1020d) | Dec 15, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [5915e986de](https://linux-hardware.org/?probe=5915e986de) | Dec 15, 2021 |
| Chuwi         | Hero Book                   | Notebook    | [27e37e5a15](https://linux-hardware.org/?probe=27e37e5a15) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [45a5dc5b06](https://linux-hardware.org/?probe=45a5dc5b06) | Dec 13, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [85770fb8f5](https://linux-hardware.org/?probe=85770fb8f5) | Dec 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | Notebook    | [b68de5799e](https://linux-hardware.org/?probe=b68de5799e) | Dec 12, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [5d06e53d08](https://linux-hardware.org/?probe=5d06e53d08) | Dec 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ed065155fb](https://linux-hardware.org/?probe=ed065155fb) | Dec 11, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [7fe98389c6](https://linux-hardware.org/?probe=7fe98389c6) | Dec 11, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [5be7aac3a2](https://linux-hardware.org/?probe=5be7aac3a2) | Dec 09, 2021 |
| ASUSTek       | V241FA                      | All in one  | [60c6c7ea7c](https://linux-hardware.org/?probe=60c6c7ea7c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [98f25277f5](https://linux-hardware.org/?probe=98f25277f5) | Dec 08, 2021 |
| ASRockRack    | E3C232D4U-V1L               | Desktop     | [139a75e689](https://linux-hardware.org/?probe=139a75e689) | Dec 07, 2021 |
| Dell          | Inspiron 7586               | Convertible | [53604c12d1](https://linux-hardware.org/?probe=53604c12d1) | Dec 05, 2021 |
| INET          | Z12B                        | Mini pc     | [95470b9d91](https://linux-hardware.org/?probe=95470b9d91) | Dec 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [1c6db4a61b](https://linux-hardware.org/?probe=1c6db4a61b) | Dec 03, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [902395fcce](https://linux-hardware.org/?probe=902395fcce) | Dec 03, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [ad91050095](https://linux-hardware.org/?probe=ad91050095) | Dec 03, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [b42c2359f4](https://linux-hardware.org/?probe=b42c2359f4) | Dec 03, 2021 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [56bd9b515c](https://linux-hardware.org/?probe=56bd9b515c) | Dec 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [e73cda5c1e](https://linux-hardware.org/?probe=e73cda5c1e) | Dec 02, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [d3040ac7d5](https://linux-hardware.org/?probe=d3040ac7d5) | Nov 30, 2021 |
| Allview       | Allbook J                   | Notebook    | [957074dbe3](https://linux-hardware.org/?probe=957074dbe3) | Nov 30, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [317b686b33](https://linux-hardware.org/?probe=317b686b33) | Nov 29, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [c323b490bf](https://linux-hardware.org/?probe=c323b490bf) | Nov 26, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [89729fef47](https://linux-hardware.org/?probe=89729fef47) | Nov 25, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [755b7b85f5](https://linux-hardware.org/?probe=755b7b85f5) | Nov 24, 2021 |
| Medion        | E7218                       | Notebook    | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [dab6e17223](https://linux-hardware.org/?probe=dab6e17223) | Nov 23, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [dba80843bc](https://linux-hardware.org/?probe=dba80843bc) | Nov 23, 2021 |
| HP            | Compaq 2510p                | Notebook    | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [eb7191f8cb](https://linux-hardware.org/?probe=eb7191f8cb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [1169bef865](https://linux-hardware.org/?probe=1169bef865) | Nov 22, 2021 |
| HP            | Compaq 2510p                | Notebook    | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bb48a45349](https://linux-hardware.org/?probe=bb48a45349) | Nov 22, 2021 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [898f3db0ed](https://linux-hardware.org/?probe=898f3db0ed) | Nov 22, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [9a83e53e34](https://linux-hardware.org/?probe=9a83e53e34) | Nov 22, 2021 |
| ASUSTek       | X450CP                      | Notebook    | [7228a5157c](https://linux-hardware.org/?probe=7228a5157c) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [04fa536869](https://linux-hardware.org/?probe=04fa536869) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [097de81570](https://linux-hardware.org/?probe=097de81570) | Nov 20, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [4a77a751d9](https://linux-hardware.org/?probe=4a77a751d9) | Nov 20, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [00f5cc73fe](https://linux-hardware.org/?probe=00f5cc73fe) | Nov 19, 2021 |
| Dell          | Latitude 7410               | Notebook    | [226f912726](https://linux-hardware.org/?probe=226f912726) | Nov 18, 2021 |
| ASUSTek       | K53U                        | Notebook    | [8b542e61d9](https://linux-hardware.org/?probe=8b542e61d9) | Nov 18, 2021 |
| Dell          | Latitude E7470              | Notebook    | [0358863974](https://linux-hardware.org/?probe=0358863974) | Nov 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2e7ed34d33](https://linux-hardware.org/?probe=2e7ed34d33) | Nov 16, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [6677eae4da](https://linux-hardware.org/?probe=6677eae4da) | Nov 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [48f29ffe3a](https://linux-hardware.org/?probe=48f29ffe3a) | Nov 14, 2021 |
| ASUSTek       | X540SA                      | Notebook    | [1292ab6f15](https://linux-hardware.org/?probe=1292ab6f15) | Nov 14, 2021 |
| Dell          | Latitude E6410              | Notebook    | [1a31fa8433](https://linux-hardware.org/?probe=1a31fa8433) | Nov 13, 2021 |
| ASUSTek       | X540SA                      | Notebook    | [463e1f35a9](https://linux-hardware.org/?probe=463e1f35a9) | Nov 13, 2021 |
| Sony          | SVF14N1E2ES                 | Notebook    | [a04441e5cd](https://linux-hardware.org/?probe=a04441e5cd) | Nov 13, 2021 |
| Dell          | Precision 3541              | Notebook    | [8f6085ab9d](https://linux-hardware.org/?probe=8f6085ab9d) | Nov 12, 2021 |
| Packard Be... | EasyNote TN36               | Notebook    | [17ebc64721](https://linux-hardware.org/?probe=17ebc64721) | Nov 11, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [e70882b3fd](https://linux-hardware.org/?probe=e70882b3fd) | Nov 11, 2021 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [32988fae95](https://linux-hardware.org/?probe=32988fae95) | Nov 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b79aef683b](https://linux-hardware.org/?probe=b79aef683b) | Nov 11, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [c32869e5a8](https://linux-hardware.org/?probe=c32869e5a8) | Nov 08, 2021 |
| ASUSTek       | A58M-K                      | Desktop     | [0dbc01db57](https://linux-hardware.org/?probe=0dbc01db57) | Nov 08, 2021 |
| Gigabyte      | P31-DS3L                    | Desktop     | [c0ef5646a8](https://linux-hardware.org/?probe=c0ef5646a8) | Nov 07, 2021 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [6dd5b7f191](https://linux-hardware.org/?probe=6dd5b7f191) | Nov 06, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [c1bd9abdd2](https://linux-hardware.org/?probe=c1bd9abdd2) | Nov 03, 2021 |
| HP            | 18E4                        | Desktop     | [1c3ea795a0](https://linux-hardware.org/?probe=1c3ea795a0) | Nov 03, 2021 |
| HP            | 18E4                        | Desktop     | [4994f5c700](https://linux-hardware.org/?probe=4994f5c700) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [0243b19a08](https://linux-hardware.org/?probe=0243b19a08) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [f7d58b572d](https://linux-hardware.org/?probe=f7d58b572d) | Nov 03, 2021 |
| Dell          | G3 3579                     | Notebook    | [f9fdeb003b](https://linux-hardware.org/?probe=f9fdeb003b) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [8cdb34dbc8](https://linux-hardware.org/?probe=8cdb34dbc8) | Nov 01, 2021 |
| Lenovo        | ThinkPad T430 2349U15       | Notebook    | [c9d8efc9b9](https://linux-hardware.org/?probe=c9d8efc9b9) | Oct 31, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [f31e6e3dd0](https://linux-hardware.org/?probe=f31e6e3dd0) | Oct 29, 2021 |
| ASUSTek       | V241EA                      | All in one  | [243713e97a](https://linux-hardware.org/?probe=243713e97a) | Oct 28, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| Dell          | 07T4MC A11                  | Desktop     | [219a3a234f](https://linux-hardware.org/?probe=219a3a234f) | Oct 27, 2021 |
| Dell          | 07T4MC A11                  | Desktop     | [870145802c](https://linux-hardware.org/?probe=870145802c) | Oct 27, 2021 |
| Dell          | Latitude E5450              | Notebook    | [fb61a77e5c](https://linux-hardware.org/?probe=fb61a77e5c) | Oct 26, 2021 |
| IBM           | 82121QG                     | Desktop     | [765d524e7f](https://linux-hardware.org/?probe=765d524e7f) | Oct 26, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [109cb750a6](https://linux-hardware.org/?probe=109cb750a6) | Oct 25, 2021 |
| Lenovo        | ThinkPad X230 2325SWF       | Notebook    | [64f9882936](https://linux-hardware.org/?probe=64f9882936) | Oct 25, 2021 |
| Apple         | MacBookPro14,3              | Notebook    | [69a5d79a58](https://linux-hardware.org/?probe=69a5d79a58) | Oct 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [9b3e361eb7](https://linux-hardware.org/?probe=9b3e361eb7) | Oct 24, 2021 |
| Dell          | Latitude E7470              | Notebook    | [69a251cc1f](https://linux-hardware.org/?probe=69a251cc1f) | Oct 22, 2021 |
| Dell          | Latitude E7470              | Notebook    | [96ef0ee68c](https://linux-hardware.org/?probe=96ef0ee68c) | Oct 22, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [21379aad70](https://linux-hardware.org/?probe=21379aad70) | Oct 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f0c049fc34](https://linux-hardware.org/?probe=f0c049fc34) | Oct 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d550d04ac7](https://linux-hardware.org/?probe=d550d04ac7) | Oct 20, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [8563f3786e](https://linux-hardware.org/?probe=8563f3786e) | Oct 19, 2021 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [ac37b3fd23](https://linux-hardware.org/?probe=ac37b3fd23) | Oct 18, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [cbf3c67be2](https://linux-hardware.org/?probe=cbf3c67be2) | Oct 18, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [cc0290a8df](https://linux-hardware.org/?probe=cc0290a8df) | Oct 18, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [0b2123c367](https://linux-hardware.org/?probe=0b2123c367) | Oct 16, 2021 |
| Dell          | Latitude E7470              | Notebook    | [3bbcb85b9f](https://linux-hardware.org/?probe=3bbcb85b9f) | Oct 16, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [28930b356e](https://linux-hardware.org/?probe=28930b356e) | Oct 16, 2021 |
| ASRock        | A75 Extreme6                | Desktop     | [5735bac676](https://linux-hardware.org/?probe=5735bac676) | Oct 16, 2021 |
| ASRock        | 4X4-4000 Series             | Desktop     | [fd95402aa1](https://linux-hardware.org/?probe=fd95402aa1) | Oct 14, 2021 |
| ASRock        | 4X4-4000 Series             | Desktop     | [538c0f7723](https://linux-hardware.org/?probe=538c0f7723) | Oct 14, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [b59de957b3](https://linux-hardware.org/?probe=b59de957b3) | Oct 11, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [a427a26f34](https://linux-hardware.org/?probe=a427a26f34) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1965a71536](https://linux-hardware.org/?probe=1965a71536) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6166a72ec2](https://linux-hardware.org/?probe=6166a72ec2) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [0acb396573](https://linux-hardware.org/?probe=0acb396573) | Oct 11, 2021 |
| Acer          | Aspire 5741G                | Notebook    | [ea162f9171](https://linux-hardware.org/?probe=ea162f9171) | Oct 10, 2021 |
| HP            | 3031h                       | Desktop     | [eb48a6bfe5](https://linux-hardware.org/?probe=eb48a6bfe5) | Oct 10, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [d79188a009](https://linux-hardware.org/?probe=d79188a009) | Oct 10, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [aae51881da](https://linux-hardware.org/?probe=aae51881da) | Oct 10, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [efb88027ec](https://linux-hardware.org/?probe=efb88027ec) | Oct 09, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [ec7609239e](https://linux-hardware.org/?probe=ec7609239e) | Oct 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [1f29f9efba](https://linux-hardware.org/?probe=1f29f9efba) | Oct 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [2236b91c55](https://linux-hardware.org/?probe=2236b91c55) | Oct 05, 2021 |
| HP            | EliteBook 8770w             | Notebook    | [d23574ecf1](https://linux-hardware.org/?probe=d23574ecf1) | Oct 04, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [97333f9cab](https://linux-hardware.org/?probe=97333f9cab) | Oct 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [2f89b6fcf1](https://linux-hardware.org/?probe=2f89b6fcf1) | Oct 03, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [06d254591f](https://linux-hardware.org/?probe=06d254591f) | Oct 02, 2021 |
| Lenovo        | ThinkPad T470 20HES0FA02    | Notebook    | [b368193a4e](https://linux-hardware.org/?probe=b368193a4e) | Oct 02, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [02d6cacb04](https://linux-hardware.org/?probe=02d6cacb04) | Sep 30, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [699985f9e6](https://linux-hardware.org/?probe=699985f9e6) | Sep 28, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [d82bdfcf17](https://linux-hardware.org/?probe=d82bdfcf17) | Sep 28, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [032d34e75b](https://linux-hardware.org/?probe=032d34e75b) | Sep 28, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [68a76785a0](https://linux-hardware.org/?probe=68a76785a0) | Sep 27, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [3cbca1757f](https://linux-hardware.org/?probe=3cbca1757f) | Sep 26, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [7baf276ca0](https://linux-hardware.org/?probe=7baf276ca0) | Sep 26, 2021 |
| Alienware     | 17 R2                       | Notebook    | [cbe7430492](https://linux-hardware.org/?probe=cbe7430492) | Sep 26, 2021 |
| ASUSTek       | FX503VD                     | Notebook    | [c91cad59c2](https://linux-hardware.org/?probe=c91cad59c2) | Sep 25, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [a44995aac4](https://linux-hardware.org/?probe=a44995aac4) | Sep 25, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a97e17fc48](https://linux-hardware.org/?probe=a97e17fc48) | Sep 25, 2021 |
| HP            | EliteBook 8530p             | Notebook    | [8002401481](https://linux-hardware.org/?probe=8002401481) | Sep 23, 2021 |
| Dell          | 0GM819                      | Desktop     | [708ca8f58a](https://linux-hardware.org/?probe=708ca8f58a) | Sep 22, 2021 |
| Dell          | 0GM819                      | Desktop     | [37f5afac35](https://linux-hardware.org/?probe=37f5afac35) | Sep 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [72f179ec58](https://linux-hardware.org/?probe=72f179ec58) | Sep 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | Notebook    | [f6dfc42935](https://linux-hardware.org/?probe=f6dfc42935) | Sep 22, 2021 |
| MSI           | A55M-E33                    | Desktop     | [695bc5477d](https://linux-hardware.org/?probe=695bc5477d) | Sep 22, 2021 |
| ASUSTek       | UX550VE                     | Notebook    | [72925fef5d](https://linux-hardware.org/?probe=72925fef5d) | Sep 21, 2021 |
| ASUSTek       | GL752VW                     | Notebook    | [ec4b89fd42](https://linux-hardware.org/?probe=ec4b89fd42) | Sep 20, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [75c71d1f1e](https://linux-hardware.org/?probe=75c71d1f1e) | Sep 20, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [7b95b06b4d](https://linux-hardware.org/?probe=7b95b06b4d) | Sep 20, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [3a0a2208fb](https://linux-hardware.org/?probe=3a0a2208fb) | Sep 20, 2021 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [c7e3f44f44](https://linux-hardware.org/?probe=c7e3f44f44) | Sep 19, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [c0b5da7979](https://linux-hardware.org/?probe=c0b5da7979) | Sep 19, 2021 |
| Acer          | AOA110                      | Notebook    | [a54c248743](https://linux-hardware.org/?probe=a54c248743) | Sep 19, 2021 |
| HP            | Pavilion dv6                | Notebook    | [b4d25f6f3a](https://linux-hardware.org/?probe=b4d25f6f3a) | Sep 19, 2021 |
| Sony          | VGN-CR21Z_N                 | Notebook    | [6fc19f4c67](https://linux-hardware.org/?probe=6fc19f4c67) | Sep 19, 2021 |
| HP            | 3397                        | Desktop     | [13d358c48e](https://linux-hardware.org/?probe=13d358c48e) | Sep 18, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [252914c6d3](https://linux-hardware.org/?probe=252914c6d3) | Sep 16, 2021 |
| Supermicro    | X11SSL-CF                   | Server      | [50169a0ffb](https://linux-hardware.org/?probe=50169a0ffb) | Sep 15, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | Desktop     | [d47952ec42](https://linux-hardware.org/?probe=d47952ec42) | Sep 15, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | Desktop     | [9c310e15bd](https://linux-hardware.org/?probe=9c310e15bd) | Sep 15, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [1493a2eae1](https://linux-hardware.org/?probe=1493a2eae1) | Sep 15, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| Toshiba       | Satellite C55-C             | Notebook    | [8966b3a7b5](https://linux-hardware.org/?probe=8966b3a7b5) | Sep 14, 2021 |
| HP            | EliteBook 840 G4            | Notebook    | [8bd6acee77](https://linux-hardware.org/?probe=8bd6acee77) | Sep 13, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [da1dd9bb01](https://linux-hardware.org/?probe=da1dd9bb01) | Sep 13, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [bc6963f758](https://linux-hardware.org/?probe=bc6963f758) | Sep 11, 2021 |
| Packard Be... | EasyNote MV86               | Notebook    | [ea018cddf2](https://linux-hardware.org/?probe=ea018cddf2) | Sep 10, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [151a3381f0](https://linux-hardware.org/?probe=151a3381f0) | Sep 09, 2021 |
| Dell          | Inspiron 5520               | Notebook    | [835f9cb8a1](https://linux-hardware.org/?probe=835f9cb8a1) | Sep 07, 2021 |
| Dell          | Latitude 7410               | Notebook    | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell          | Latitude 7410               | Notebook    | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [576b96b6da](https://linux-hardware.org/?probe=576b96b6da) | Sep 06, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [638993c7b0](https://linux-hardware.org/?probe=638993c7b0) | Sep 06, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [bb0ef0735f](https://linux-hardware.org/?probe=bb0ef0735f) | Sep 05, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | Notebook    | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| ASUSTek       | D340MC-C                    | Desktop     | [cf81a7ddc2](https://linux-hardware.org/?probe=cf81a7ddc2) | Sep 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [47c2053681](https://linux-hardware.org/?probe=47c2053681) | Sep 02, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| HP            | 18E9                        | Desktop     | [22f86af485](https://linux-hardware.org/?probe=22f86af485) | Sep 01, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [4765b87a68](https://linux-hardware.org/?probe=4765b87a68) | Sep 01, 2021 |
| MSI           | A88XM-E35                   | Desktop     | [66070c788f](https://linux-hardware.org/?probe=66070c788f) | Sep 01, 2021 |
| HP            | 3032h                       | Desktop     | [7d94cc3baa](https://linux-hardware.org/?probe=7d94cc3baa) | Sep 01, 2021 |
| ASUSTek       | K52F                        | Notebook    | [743e5c8059](https://linux-hardware.org/?probe=743e5c8059) | Sep 01, 2021 |
| ASUSTek       | K52F                        | Notebook    | [54d5076bc6](https://linux-hardware.org/?probe=54d5076bc6) | Sep 01, 2021 |
| ASUSTek       | UX550VE                     | Notebook    | [cd80e1ebb2](https://linux-hardware.org/?probe=cd80e1ebb2) | Aug 31, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [c2b7f1ee7c](https://linux-hardware.org/?probe=c2b7f1ee7c) | Aug 30, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [301be6f800](https://linux-hardware.org/?probe=301be6f800) | Aug 30, 2021 |
| MSI           | MS-16Y1                     | Notebook    | [a9801b616e](https://linux-hardware.org/?probe=a9801b616e) | Aug 29, 2021 |
| HP            | 18E9                        | Desktop     | [539f181954](https://linux-hardware.org/?probe=539f181954) | Aug 29, 2021 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [0a9f1f10d8](https://linux-hardware.org/?probe=0a9f1f10d8) | Aug 29, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [fd9d91270d](https://linux-hardware.org/?probe=fd9d91270d) | Aug 29, 2021 |
| ASUSTek       | X450CP                      | Notebook    | [d646ffd8db](https://linux-hardware.org/?probe=d646ffd8db) | Aug 29, 2021 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [30d745e8d3](https://linux-hardware.org/?probe=30d745e8d3) | Aug 28, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | Notebook    | [954900ccc6](https://linux-hardware.org/?probe=954900ccc6) | Aug 28, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [03a89677c0](https://linux-hardware.org/?probe=03a89677c0) | Aug 26, 2021 |
| HP            | Presario CQ57               | Notebook    | [4b863ffc87](https://linux-hardware.org/?probe=4b863ffc87) | Aug 25, 2021 |
| HP            | 84DE                        | All in one  | [11f4f1348a](https://linux-hardware.org/?probe=11f4f1348a) | Aug 25, 2021 |
| HP            | 84DE                        | All in one  | [ba6157396c](https://linux-hardware.org/?probe=ba6157396c) | Aug 25, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f534340eab](https://linux-hardware.org/?probe=f534340eab) | Aug 22, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4f6bd2a75e](https://linux-hardware.org/?probe=4f6bd2a75e) | Aug 22, 2021 |
| HP            | Presario CQ57               | Notebook    | [a45389ec74](https://linux-hardware.org/?probe=a45389ec74) | Aug 21, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [eb664f1a19](https://linux-hardware.org/?probe=eb664f1a19) | Aug 20, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [cf9c1726af](https://linux-hardware.org/?probe=cf9c1726af) | Aug 19, 2021 |
| HP            | 1587h                       | Desktop     | [3ddbdb3101](https://linux-hardware.org/?probe=3ddbdb3101) | Aug 19, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [70be38d5e1](https://linux-hardware.org/?probe=70be38d5e1) | Aug 18, 2021 |
| HP            | Pavilion dv6                | Notebook    | [40cd012d76](https://linux-hardware.org/?probe=40cd012d76) | Aug 18, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [8cf3477dd1](https://linux-hardware.org/?probe=8cf3477dd1) | Aug 18, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7465dcb16d](https://linux-hardware.org/?probe=7465dcb16d) | Aug 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [8bf5049adc](https://linux-hardware.org/?probe=8bf5049adc) | Aug 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [92e25a1c2c](https://linux-hardware.org/?probe=92e25a1c2c) | Aug 15, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [4b4a995bad](https://linux-hardware.org/?probe=4b4a995bad) | Aug 15, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [f3506aaa1c](https://linux-hardware.org/?probe=f3506aaa1c) | Aug 14, 2021 |
| HP            | 630                         | Notebook    | [eda8d23dba](https://linux-hardware.org/?probe=eda8d23dba) | Aug 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [c8b1a45676](https://linux-hardware.org/?probe=c8b1a45676) | Aug 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [20a828b938](https://linux-hardware.org/?probe=20a828b938) | Aug 11, 2021 |
| ASUSTek       | X550JX                      | Notebook    | [da2cacc763](https://linux-hardware.org/?probe=da2cacc763) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [86ab410358](https://linux-hardware.org/?probe=86ab410358) | Aug 10, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [d7ad85015d](https://linux-hardware.org/?probe=d7ad85015d) | Aug 10, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [99763e52f1](https://linux-hardware.org/?probe=99763e52f1) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | Notebook    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| HP            | 2AE2                        | Desktop     | [e8a9a769fe](https://linux-hardware.org/?probe=e8a9a769fe) | Aug 07, 2021 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [1d3167cdf0](https://linux-hardware.org/?probe=1d3167cdf0) | Aug 05, 2021 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [3118d29bf0](https://linux-hardware.org/?probe=3118d29bf0) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [1a6e7a1825](https://linux-hardware.org/?probe=1a6e7a1825) | Aug 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [a7feba2af0](https://linux-hardware.org/?probe=a7feba2af0) | Aug 04, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [a7c1a61e9f](https://linux-hardware.org/?probe=a7c1a61e9f) | Aug 03, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [d58be51f72](https://linux-hardware.org/?probe=d58be51f72) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [64dcd58bc3](https://linux-hardware.org/?probe=64dcd58bc3) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [462a00dded](https://linux-hardware.org/?probe=462a00dded) | Aug 02, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [5f2773a82c](https://linux-hardware.org/?probe=5f2773a82c) | Aug 02, 2021 |
| Gigabyte      | P75-D3                      | Desktop     | [5f0bee42c2](https://linux-hardware.org/?probe=5f0bee42c2) | Aug 01, 2021 |
| HP            | 2AE2                        | Desktop     | [61acec4a9c](https://linux-hardware.org/?probe=61acec4a9c) | Aug 01, 2021 |
| HP            | 2AE2                        | Desktop     | [3de122823e](https://linux-hardware.org/?probe=3de122823e) | Aug 01, 2021 |
| HP            | 15                          | Notebook    | [715128c8f0](https://linux-hardware.org/?probe=715128c8f0) | Jul 31, 2021 |
| Toshiba       | Satellite Z30-B             | Notebook    | [af9632e99f](https://linux-hardware.org/?probe=af9632e99f) | Jul 30, 2021 |
| Lenovo        | ThinkPad T410 2537CJ0       | Notebook    | [3722a27c42](https://linux-hardware.org/?probe=3722a27c42) | Jul 28, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [f448eea5b9](https://linux-hardware.org/?probe=f448eea5b9) | Jul 27, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [a5cc51aec1](https://linux-hardware.org/?probe=a5cc51aec1) | Jul 26, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [9e05add91a](https://linux-hardware.org/?probe=9e05add91a) | Jul 26, 2021 |
| HP            | 1850                        | Desktop     | [76e386707a](https://linux-hardware.org/?probe=76e386707a) | Jul 24, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [7fa1d5f6ab](https://linux-hardware.org/?probe=7fa1d5f6ab) | Jul 24, 2021 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [b0ce1bc8f5](https://linux-hardware.org/?probe=b0ce1bc8f5) | Jul 24, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [11daeb0d8d](https://linux-hardware.org/?probe=11daeb0d8d) | Jul 24, 2021 |
| HP            | 0AA8h                       | Desktop     | [a04f3a673d](https://linux-hardware.org/?probe=a04f3a673d) | Jul 23, 2021 |
| HP            | 0AA8h                       | Desktop     | [b3bbc0186c](https://linux-hardware.org/?probe=b3bbc0186c) | Jul 22, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [9f6c5866ae](https://linux-hardware.org/?probe=9f6c5866ae) | Jul 20, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [74f54d66b2](https://linux-hardware.org/?probe=74f54d66b2) | Jul 20, 2021 |
| Toshiba       | Satellite C660D             | Notebook    | [039468c7c5](https://linux-hardware.org/?probe=039468c7c5) | Jul 18, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [f50ab25a97](https://linux-hardware.org/?probe=f50ab25a97) | Jul 17, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [594955a00b](https://linux-hardware.org/?probe=594955a00b) | Jul 17, 2021 |
| HP            | 3047h                       | Desktop     | [ac149ca840](https://linux-hardware.org/?probe=ac149ca840) | Jul 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e2c9b58e23](https://linux-hardware.org/?probe=e2c9b58e23) | Jul 17, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [14ce128e1a](https://linux-hardware.org/?probe=14ce128e1a) | Jul 16, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f656b6c149](https://linux-hardware.org/?probe=f656b6c149) | Jul 16, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d1105aa53f](https://linux-hardware.org/?probe=d1105aa53f) | Jul 16, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [a2a1798503](https://linux-hardware.org/?probe=a2a1798503) | Jul 15, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [14b9ddda83](https://linux-hardware.org/?probe=14b9ddda83) | Jul 14, 2021 |
| Dell          | 0X9X1W A00                  | Desktop     | [702d489268](https://linux-hardware.org/?probe=702d489268) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [876c8173d3](https://linux-hardware.org/?probe=876c8173d3) | Jul 13, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f9d7bd513c](https://linux-hardware.org/?probe=f9d7bd513c) | Jul 13, 2021 |
| Lenovo        | 3102 NOK                    | Desktop     | [71974ffb04](https://linux-hardware.org/?probe=71974ffb04) | Jul 12, 2021 |
| Biostar       | N61PA-M2S                   | Desktop     | [346b5914bf](https://linux-hardware.org/?probe=346b5914bf) | Jul 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c9c8fdd393](https://linux-hardware.org/?probe=c9c8fdd393) | Jul 11, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [76dc55b00e](https://linux-hardware.org/?probe=76dc55b00e) | Jul 11, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [e6d4cd2e90](https://linux-hardware.org/?probe=e6d4cd2e90) | Jul 10, 2021 |
| Acer          | One S1003                   | Tablet      | [5b88dd3887](https://linux-hardware.org/?probe=5b88dd3887) | Jul 09, 2021 |
| HP            | ProBook 4330s               | Notebook    | [64030992e8](https://linux-hardware.org/?probe=64030992e8) | Jul 08, 2021 |
| Dell          | System XPS L502X            | Notebook    | [c384fff091](https://linux-hardware.org/?probe=c384fff091) | Jul 08, 2021 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [6aa95f6599](https://linux-hardware.org/?probe=6aa95f6599) | Jul 08, 2021 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [2a2e03aaa8](https://linux-hardware.org/?probe=2a2e03aaa8) | Jul 08, 2021 |
| Dell          | 04GJJT A00                  | Desktop     | [257e9719c0](https://linux-hardware.org/?probe=257e9719c0) | Jul 07, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [d09c65051f](https://linux-hardware.org/?probe=d09c65051f) | Jul 06, 2021 |
| Lenovo        | ThinkPad T470p 20J7S1860... | Notebook    | [6b3e194f93](https://linux-hardware.org/?probe=6b3e194f93) | Jul 06, 2021 |
| Allview       | Allbook H                   | Notebook    | [ac0835f4f5](https://linux-hardware.org/?probe=ac0835f4f5) | Jul 06, 2021 |
| HP            | EliteBook 8560w             | Notebook    | [e609104d2c](https://linux-hardware.org/?probe=e609104d2c) | Jul 06, 2021 |
| HP            | EliteBook 8560w             | Notebook    | [f3ac1ba96d](https://linux-hardware.org/?probe=f3ac1ba96d) | Jul 06, 2021 |
| Dell          | 0VD5HY A07                  | Desktop     | [398ee87d95](https://linux-hardware.org/?probe=398ee87d95) | Jul 04, 2021 |
| Dell          | 0VD5HY A07                  | Desktop     | [0fa3ef38f2](https://linux-hardware.org/?probe=0fa3ef38f2) | Jul 04, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [b35369b2b3](https://linux-hardware.org/?probe=b35369b2b3) | Jul 03, 2021 |
| Dell          | XPS L501X                   | Notebook    | [27ed8f445a](https://linux-hardware.org/?probe=27ed8f445a) | Jul 03, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [9b296f3c9c](https://linux-hardware.org/?probe=9b296f3c9c) | Jul 03, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [42fcbcb1e4](https://linux-hardware.org/?probe=42fcbcb1e4) | Jul 02, 2021 |
| HP            | 15                          | Notebook    | [b435e6f220](https://linux-hardware.org/?probe=b435e6f220) | Jul 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [2e13a4aff4](https://linux-hardware.org/?probe=2e13a4aff4) | Jul 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [618b266cc7](https://linux-hardware.org/?probe=618b266cc7) | Jul 02, 2021 |
| Toshiba       | Satellite C660D             | Notebook    | [fdbefe0e71](https://linux-hardware.org/?probe=fdbefe0e71) | Jul 01, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a8f90b8625](https://linux-hardware.org/?probe=a8f90b8625) | Jun 30, 2021 |
| ASUSTek       | X751LJ                      | Notebook    | [8a67af6b70](https://linux-hardware.org/?probe=8a67af6b70) | Jun 30, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [21e0e9dda8](https://linux-hardware.org/?probe=21e0e9dda8) | Jun 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [f31a585b5d](https://linux-hardware.org/?probe=f31a585b5d) | Jun 28, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [4a3a417531](https://linux-hardware.org/?probe=4a3a417531) | Jun 28, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [14b760d760](https://linux-hardware.org/?probe=14b760d760) | Jun 28, 2021 |
| Acer          | One S1003                   | Tablet      | [db5be6c431](https://linux-hardware.org/?probe=db5be6c431) | Jun 28, 2021 |
| ASUSTek       | X751LJ                      | Notebook    | [d4314245a2](https://linux-hardware.org/?probe=d4314245a2) | Jun 28, 2021 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [83b0ff67dd](https://linux-hardware.org/?probe=83b0ff67dd) | Jun 28, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [7a20aa2c3b](https://linux-hardware.org/?probe=7a20aa2c3b) | Jun 27, 2021 |
| Gigabyte      | P55-UD5                     | Desktop     | [934948c85f](https://linux-hardware.org/?probe=934948c85f) | Jun 27, 2021 |
| Allview       | Allbook H                   | Notebook    | [02832b0883](https://linux-hardware.org/?probe=02832b0883) | Jun 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a6c3875064](https://linux-hardware.org/?probe=a6c3875064) | Jun 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [3fabc021d6](https://linux-hardware.org/?probe=3fabc021d6) | Jun 25, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [59b653ec10](https://linux-hardware.org/?probe=59b653ec10) | Jun 25, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [f19497e31d](https://linux-hardware.org/?probe=f19497e31d) | Jun 22, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [aa753c135b](https://linux-hardware.org/?probe=aa753c135b) | Jun 21, 2021 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [07cc916c5e](https://linux-hardware.org/?probe=07cc916c5e) | Jun 21, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | Notebook    | [7bc2410a2a](https://linux-hardware.org/?probe=7bc2410a2a) | Jun 20, 2021 |
| MSI           | Z87-G43                     | Desktop     | [c049769b6b](https://linux-hardware.org/?probe=c049769b6b) | Jun 20, 2021 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [368b96ef78](https://linux-hardware.org/?probe=368b96ef78) | Jun 20, 2021 |
| HP            | 255 G4                      | Notebook    | [3a4a67761f](https://linux-hardware.org/?probe=3a4a67761f) | Jun 19, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [5ed8c507ef](https://linux-hardware.org/?probe=5ed8c507ef) | Jun 18, 2021 |
| Dell          | Precision M6600             | Notebook    | [3ba95fa890](https://linux-hardware.org/?probe=3ba95fa890) | Jun 18, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [ba202e6f1e](https://linux-hardware.org/?probe=ba202e6f1e) | Jun 17, 2021 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [4bc7b480e0](https://linux-hardware.org/?probe=4bc7b480e0) | Jun 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [01666caf41](https://linux-hardware.org/?probe=01666caf41) | Jun 16, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [ef3ce7621e](https://linux-hardware.org/?probe=ef3ce7621e) | Jun 13, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [86c9df0816](https://linux-hardware.org/?probe=86c9df0816) | Jun 12, 2021 |
| HP            | 829E                        | Mini pc     | [7795bf0d95](https://linux-hardware.org/?probe=7795bf0d95) | Jun 12, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [1df7b23225](https://linux-hardware.org/?probe=1df7b23225) | Jun 11, 2021 |
| HP            | 1494                        | Desktop     | [d34b022996](https://linux-hardware.org/?probe=d34b022996) | Jun 11, 2021 |
| ASUSTek       | V241FA                      | All in one  | [ab5720591e](https://linux-hardware.org/?probe=ab5720591e) | Jun 11, 2021 |
| Dell          | XPS L501X                   | Notebook    | [53b5e4986f](https://linux-hardware.org/?probe=53b5e4986f) | Jun 10, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | Notebook    | [5a8e01e79d](https://linux-hardware.org/?probe=5a8e01e79d) | Jun 05, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | Notebook    | [98c6853a46](https://linux-hardware.org/?probe=98c6853a46) | Jun 05, 2021 |
| Lenovo        | ThinkPad T440 20B7A04RGE    | Notebook    | [5b0de3fa72](https://linux-hardware.org/?probe=5b0de3fa72) | Jun 04, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| Packard Be... | EasyNote MV86               | Notebook    | [c393f3c880](https://linux-hardware.org/?probe=c393f3c880) | Jun 03, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [290d70d292](https://linux-hardware.org/?probe=290d70d292) | Jun 03, 2021 |
| ASUSTek       | P5LD2-VM                    | Desktop     | [6b68ceb0b3](https://linux-hardware.org/?probe=6b68ceb0b3) | Jun 02, 2021 |
| Lenovo        | G550 20023                  | Notebook    | [a962a76b58](https://linux-hardware.org/?probe=a962a76b58) | Jun 01, 2021 |
| ASUSTek       | P5LD2-VM                    | Desktop     | [3bdb847f96](https://linux-hardware.org/?probe=3bdb847f96) | Jun 01, 2021 |
| Lenovo        | G550 20023                  | Notebook    | [1bbec614aa](https://linux-hardware.org/?probe=1bbec614aa) | May 31, 2021 |
| Huanan        | X99-TF                      | Desktop     | [b92f4485e6](https://linux-hardware.org/?probe=b92f4485e6) | May 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [6aff8771b1](https://linux-hardware.org/?probe=6aff8771b1) | May 30, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b63698a4af](https://linux-hardware.org/?probe=b63698a4af) | May 29, 2021 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [d340a44211](https://linux-hardware.org/?probe=d340a44211) | May 28, 2021 |
| HP            | 3031h                       | Desktop     | [d69cd77c4d](https://linux-hardware.org/?probe=d69cd77c4d) | May 28, 2021 |
| Gigabyte      | 965GM-S2                    | Desktop     | [05ac3124f9](https://linux-hardware.org/?probe=05ac3124f9) | May 26, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [7fb630f632](https://linux-hardware.org/?probe=7fb630f632) | May 26, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [b251de2587](https://linux-hardware.org/?probe=b251de2587) | May 26, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [3ff174d668](https://linux-hardware.org/?probe=3ff174d668) | May 26, 2021 |
| ASUSTek       | X555LN                      | Notebook    | [7baba93fdf](https://linux-hardware.org/?probe=7baba93fdf) | May 25, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [87aca59a7c](https://linux-hardware.org/?probe=87aca59a7c) | May 25, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [522583da69](https://linux-hardware.org/?probe=522583da69) | May 25, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [141475f02b](https://linux-hardware.org/?probe=141475f02b) | May 25, 2021 |
| Dell          | Latitude D630               | Notebook    | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [02d50458ce](https://linux-hardware.org/?probe=02d50458ce) | May 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [8fe5ffb1cc](https://linux-hardware.org/?probe=8fe5ffb1cc) | May 21, 2021 |
| HP            | 3029h                       | Desktop     | [1f0ebaa79c](https://linux-hardware.org/?probe=1f0ebaa79c) | May 20, 2021 |
| HP            | 3029h                       | Desktop     | [9eac66bf17](https://linux-hardware.org/?probe=9eac66bf17) | May 20, 2021 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [d4187bad77](https://linux-hardware.org/?probe=d4187bad77) | May 20, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [9bc3a8a33e](https://linux-hardware.org/?probe=9bc3a8a33e) | May 20, 2021 |
| Gigabyte      | 965GM-S2                    | Desktop     | [7db6d2bc1a](https://linux-hardware.org/?probe=7db6d2bc1a) | May 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [1c24b50a75](https://linux-hardware.org/?probe=1c24b50a75) | May 20, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [32546ecaa0](https://linux-hardware.org/?probe=32546ecaa0) | May 17, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [9f12330c51](https://linux-hardware.org/?probe=9f12330c51) | May 15, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [86b562f999](https://linux-hardware.org/?probe=86b562f999) | May 14, 2021 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [110d291fde](https://linux-hardware.org/?probe=110d291fde) | May 13, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [18ca89b617](https://linux-hardware.org/?probe=18ca89b617) | May 11, 2021 |
| HP            | 1494                        | Desktop     | [26a35b5f46](https://linux-hardware.org/?probe=26a35b5f46) | May 10, 2021 |
| ASUSTek       | J1800I-C                    | Desktop     | [2554e9ed0c](https://linux-hardware.org/?probe=2554e9ed0c) | May 10, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [7a0e366273](https://linux-hardware.org/?probe=7a0e366273) | May 09, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [1809630187](https://linux-hardware.org/?probe=1809630187) | May 09, 2021 |
| HP            | 1496                        | Desktop     | [ef4e0697d7](https://linux-hardware.org/?probe=ef4e0697d7) | May 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [356c77df30](https://linux-hardware.org/?probe=356c77df30) | May 07, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [d4cf6a320b](https://linux-hardware.org/?probe=d4cf6a320b) | May 07, 2021 |
| Dell          | Latitude E7470              | Notebook    | [c854d464d4](https://linux-hardware.org/?probe=c854d464d4) | May 07, 2021 |
| Toshiba       | Satellite Pro U200          | Notebook    | [ea94c20118](https://linux-hardware.org/?probe=ea94c20118) | May 06, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [5927d6bfa2](https://linux-hardware.org/?probe=5927d6bfa2) | May 06, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [8770317d57](https://linux-hardware.org/?probe=8770317d57) | May 06, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ec0def5c1e](https://linux-hardware.org/?probe=ec0def5c1e) | May 06, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [cd3b8f3bca](https://linux-hardware.org/?probe=cd3b8f3bca) | May 06, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [6367a7db0a](https://linux-hardware.org/?probe=6367a7db0a) | May 06, 2021 |
| Toshiba       | Satellite Pro U200          | Notebook    | [1442c68bc8](https://linux-hardware.org/?probe=1442c68bc8) | May 05, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f90ca57fa0](https://linux-hardware.org/?probe=f90ca57fa0) | May 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [b1a5da541f](https://linux-hardware.org/?probe=b1a5da541f) | May 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [155da00fc0](https://linux-hardware.org/?probe=155da00fc0) | May 03, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo        | ThinkPad T61 7659W1W        | Notebook    | [c366a3e7a2](https://linux-hardware.org/?probe=c366a3e7a2) | May 01, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [3eeaf82899](https://linux-hardware.org/?probe=3eeaf82899) | May 01, 2021 |
| Dell          | Latitude E7470              | Notebook    | [b4d85c0e7c](https://linux-hardware.org/?probe=b4d85c0e7c) | May 01, 2021 |
| Dell          | Latitude E7470              | Notebook    | [1e60f8c14a](https://linux-hardware.org/?probe=1e60f8c14a) | May 01, 2021 |
| Dell          | Latitude E6430              | Notebook    | [4ba28d9505](https://linux-hardware.org/?probe=4ba28d9505) | May 01, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [d0c8d6944c](https://linux-hardware.org/?probe=d0c8d6944c) | Apr 30, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [a72228a343](https://linux-hardware.org/?probe=a72228a343) | Apr 29, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [7f935099f0](https://linux-hardware.org/?probe=7f935099f0) | Apr 28, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [8dbfa5594e](https://linux-hardware.org/?probe=8dbfa5594e) | Apr 27, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [ed71084f85](https://linux-hardware.org/?probe=ed71084f85) | Apr 27, 2021 |
| ASUSTek       | ROG Strix G531GV_G531GV     | Notebook    | [4dfa28cef5](https://linux-hardware.org/?probe=4dfa28cef5) | Apr 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [d5a5a8496d](https://linux-hardware.org/?probe=d5a5a8496d) | Apr 23, 2021 |
| MSI           | MS-7502 Fab D               | Desktop     | [2a2d112995](https://linux-hardware.org/?probe=2a2d112995) | Apr 23, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [06b060c49c](https://linux-hardware.org/?probe=06b060c49c) | Apr 23, 2021 |
| HP            | G62                         | Notebook    | [d728a70b0b](https://linux-hardware.org/?probe=d728a70b0b) | Apr 23, 2021 |
| ASUSTek       | GL552VX                     | Notebook    | [294a96afbb](https://linux-hardware.org/?probe=294a96afbb) | Apr 22, 2021 |
| ASUSTek       | GL552VX                     | Notebook    | [534b39dba5](https://linux-hardware.org/?probe=534b39dba5) | Apr 22, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1c206551a3](https://linux-hardware.org/?probe=1c206551a3) | Apr 22, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [83c7d6b0a2](https://linux-hardware.org/?probe=83c7d6b0a2) | Apr 22, 2021 |
| Lenovo        | ThinkPad E560 20EV003AUK    | Notebook    | [3f10db447f](https://linux-hardware.org/?probe=3f10db447f) | Apr 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3feeb55814](https://linux-hardware.org/?probe=3feeb55814) | Apr 20, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [42b2eb88ad](https://linux-hardware.org/?probe=42b2eb88ad) | Apr 19, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [b91839a518](https://linux-hardware.org/?probe=b91839a518) | Apr 19, 2021 |
| MSI           | MS-7367                     | Desktop     | [1a103f941a](https://linux-hardware.org/?probe=1a103f941a) | Apr 18, 2021 |
| HP            | 1790                        | Desktop     | [75557f3294](https://linux-hardware.org/?probe=75557f3294) | Apr 18, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [a83dfd361b](https://linux-hardware.org/?probe=a83dfd361b) | Apr 14, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [b8e3c87a38](https://linux-hardware.org/?probe=b8e3c87a38) | Apr 14, 2021 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [22d879f5ea](https://linux-hardware.org/?probe=22d879f5ea) | Apr 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8b5a5a31fb](https://linux-hardware.org/?probe=8b5a5a31fb) | Apr 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d6b88752a0](https://linux-hardware.org/?probe=d6b88752a0) | Apr 12, 2021 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | Notebook    | [d2d3020f8b](https://linux-hardware.org/?probe=d2d3020f8b) | Apr 12, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [082fe11ffb](https://linux-hardware.org/?probe=082fe11ffb) | Apr 12, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [2e69cf4f5a](https://linux-hardware.org/?probe=2e69cf4f5a) | Apr 12, 2021 |
| Dell          | 04GJJT A00                  | Desktop     | [b687e379b9](https://linux-hardware.org/?probe=b687e379b9) | Apr 11, 2021 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [7b4c090391](https://linux-hardware.org/?probe=7b4c090391) | Apr 11, 2021 |
| Lenovo        | ThinkCentre M91p 4524AS3    | Desktop     | [79febd76c3](https://linux-hardware.org/?probe=79febd76c3) | Apr 11, 2021 |
| Dell          | Latitude E6410              | Notebook    | [9fc394df40](https://linux-hardware.org/?probe=9fc394df40) | Apr 10, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [79528a1998](https://linux-hardware.org/?probe=79528a1998) | Apr 09, 2021 |
| HP            | 2215                        | Desktop     | [0ce403b929](https://linux-hardware.org/?probe=0ce403b929) | Apr 09, 2021 |
| Lenovo        | ThinkCentre M58 7373WB7     | Desktop     | [57e7329bf2](https://linux-hardware.org/?probe=57e7329bf2) | Apr 09, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [7730367108](https://linux-hardware.org/?probe=7730367108) | Apr 08, 2021 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [949f9eb773](https://linux-hardware.org/?probe=949f9eb773) | Apr 06, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [af302c8ef5](https://linux-hardware.org/?probe=af302c8ef5) | Apr 05, 2021 |
| Lenovo        | ThinkCentre M58 7359A59     | Desktop     | [0784afdde4](https://linux-hardware.org/?probe=0784afdde4) | Apr 05, 2021 |
| Lenovo        | ThinkCentre M58 7359A59     | Desktop     | [3c49f2205f](https://linux-hardware.org/?probe=3c49f2205f) | Apr 05, 2021 |
| HP            | G62                         | Notebook    | [b706770f8d](https://linux-hardware.org/?probe=b706770f8d) | Apr 05, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [ac0a48160a](https://linux-hardware.org/?probe=ac0a48160a) | Apr 05, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [533ebeaa6e](https://linux-hardware.org/?probe=533ebeaa6e) | Apr 05, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [4b5d46fe3a](https://linux-hardware.org/?probe=4b5d46fe3a) | Apr 03, 2021 |
| Dell          | Latitude E6410              | Notebook    | [297aaeb4ac](https://linux-hardware.org/?probe=297aaeb4ac) | Apr 03, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [f66cd74385](https://linux-hardware.org/?probe=f66cd74385) | Apr 03, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [11d853a6cd](https://linux-hardware.org/?probe=11d853a6cd) | Apr 03, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [a97fe90c04](https://linux-hardware.org/?probe=a97fe90c04) | Apr 03, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [83700e8ca7](https://linux-hardware.org/?probe=83700e8ca7) | Apr 03, 2021 |
| Samsung       | 300V3Z/300V4Z/300V5Z/200... | Notebook    | [51ed7ce2e8](https://linux-hardware.org/?probe=51ed7ce2e8) | Apr 03, 2021 |
| Samsung       | 300V3Z/300V4Z/300V5Z/200... | Notebook    | [a3bd82613b](https://linux-hardware.org/?probe=a3bd82613b) | Apr 03, 2021 |
| Fujitsu       | LIFEBOOK NH751              | Notebook    | [27bf374b6e](https://linux-hardware.org/?probe=27bf374b6e) | Apr 01, 2021 |
| Fujitsu       | LIFEBOOK NH751              | Notebook    | [24b8bc435b](https://linux-hardware.org/?probe=24b8bc435b) | Apr 01, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [c3bc72bfce](https://linux-hardware.org/?probe=c3bc72bfce) | Mar 29, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [93285dae9e](https://linux-hardware.org/?probe=93285dae9e) | Mar 29, 2021 |
| Lenovo        | ThinkPad T480s 20L7001LR... | Notebook    | [440edfbe7e](https://linux-hardware.org/?probe=440edfbe7e) | Mar 26, 2021 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [3fe5519929](https://linux-hardware.org/?probe=3fe5519929) | Mar 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [3d13dd330c](https://linux-hardware.org/?probe=3d13dd330c) | Mar 25, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [0d1ffacb54](https://linux-hardware.org/?probe=0d1ffacb54) | Mar 24, 2021 |
| ASUSTek       | GL552JX                     | Notebook    | [af998c8996](https://linux-hardware.org/?probe=af998c8996) | Mar 22, 2021 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [103f41c99c](https://linux-hardware.org/?probe=103f41c99c) | Mar 21, 2021 |
| Dell          | Latitude E6440              | Notebook    | [6f00c6ac0b](https://linux-hardware.org/?probe=6f00c6ac0b) | Mar 21, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [6270efa573](https://linux-hardware.org/?probe=6270efa573) | Mar 20, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e76eac394d](https://linux-hardware.org/?probe=e76eac394d) | Mar 20, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [a9efbe668e](https://linux-hardware.org/?probe=a9efbe668e) | Mar 20, 2021 |
| HP            | 3029h                       | Desktop     | [0ddf4fe8c8](https://linux-hardware.org/?probe=0ddf4fe8c8) | Mar 20, 2021 |
| HP            | EliteBook x360 1040 G5      | Notebook    | [6c42757430](https://linux-hardware.org/?probe=6c42757430) | Mar 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [35f9677ce6](https://linux-hardware.org/?probe=35f9677ce6) | Mar 19, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [98d6ff8291](https://linux-hardware.org/?probe=98d6ff8291) | Mar 19, 2021 |
| MSI           | EX620                       | Notebook    | [92223bedbf](https://linux-hardware.org/?probe=92223bedbf) | Mar 18, 2021 |
| HP            | Laptop 17-ak0xx             | Notebook    | [2eee8ebb3d](https://linux-hardware.org/?probe=2eee8ebb3d) | Mar 18, 2021 |
| HP            | Laptop 17-ak0xx             | Notebook    | [4e9b5c0bbe](https://linux-hardware.org/?probe=4e9b5c0bbe) | Mar 18, 2021 |
| HP            | Laptop 17-ak0xx             | Notebook    | [f6768a311c](https://linux-hardware.org/?probe=f6768a311c) | Mar 18, 2021 |
| HP            | 3047h                       | Desktop     | [d4a58313d6](https://linux-hardware.org/?probe=d4a58313d6) | Mar 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b1f0621720](https://linux-hardware.org/?probe=b1f0621720) | Mar 15, 2021 |
| Dell          | 0RY007                      | Desktop     | [8c2cacd439](https://linux-hardware.org/?probe=8c2cacd439) | Mar 15, 2021 |
| Dell          | 0RY007                      | Desktop     | [e2527f8f11](https://linux-hardware.org/?probe=e2527f8f11) | Mar 15, 2021 |
| ASUSTek       | V241FF                      | All in one  | [72fcc11e52](https://linux-hardware.org/?probe=72fcc11e52) | Mar 14, 2021 |
| MSI           | 760GM -E51                  | Desktop     | [ed4ec28115](https://linux-hardware.org/?probe=ed4ec28115) | Mar 13, 2021 |
| Gigabyte      | P55-UD5                     | Desktop     | [203d98c6a0](https://linux-hardware.org/?probe=203d98c6a0) | Mar 13, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [d20831473f](https://linux-hardware.org/?probe=d20831473f) | Mar 12, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [e2f95f0c46](https://linux-hardware.org/?probe=e2f95f0c46) | Mar 10, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [e645327b43](https://linux-hardware.org/?probe=e645327b43) | Mar 10, 2021 |
| Toshiba       | Satellite C55-A             | Notebook    | [7404ca8168](https://linux-hardware.org/?probe=7404ca8168) | Mar 10, 2021 |
| Toshiba       | Satellite C55-A             | Notebook    | [07d0435295](https://linux-hardware.org/?probe=07d0435295) | Mar 10, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3f9b2942e1](https://linux-hardware.org/?probe=3f9b2942e1) | Mar 10, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [fa166645b1](https://linux-hardware.org/?probe=fa166645b1) | Mar 09, 2021 |
| HP            | 3047h                       | Desktop     | [970a03f12b](https://linux-hardware.org/?probe=970a03f12b) | Mar 09, 2021 |
| HP            | 3047h                       | Desktop     | [2277d0a259](https://linux-hardware.org/?probe=2277d0a259) | Mar 09, 2021 |
| HP            | 3029h                       | Desktop     | [163d32c75c](https://linux-hardware.org/?probe=163d32c75c) | Mar 09, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [c745fe0fbf](https://linux-hardware.org/?probe=c745fe0fbf) | Mar 09, 2021 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [6eac92f735](https://linux-hardware.org/?probe=6eac92f735) | Mar 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [3eab48365a](https://linux-hardware.org/?probe=3eab48365a) | Mar 08, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2b34023242](https://linux-hardware.org/?probe=2b34023242) | Mar 07, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [44428b2791](https://linux-hardware.org/?probe=44428b2791) | Mar 06, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | Notebook    | [665f41ae68](https://linux-hardware.org/?probe=665f41ae68) | Mar 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [74af4c6f9d](https://linux-hardware.org/?probe=74af4c6f9d) | Mar 05, 2021 |
| ASUSTek       | ZenBook Pro 15 UX550GD_U... | Notebook    | [3123875940](https://linux-hardware.org/?probe=3123875940) | Mar 05, 2021 |
| ASUSTek       | K54LY                       | Notebook    | [6968932b0f](https://linux-hardware.org/?probe=6968932b0f) | Mar 04, 2021 |
| Acer          | Aspire V5-552               | Notebook    | [7a32a8a1c3](https://linux-hardware.org/?probe=7a32a8a1c3) | Mar 03, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [746e41378c](https://linux-hardware.org/?probe=746e41378c) | Mar 03, 2021 |
| HP            | 1497                        | Desktop     | [6d49e950fe](https://linux-hardware.org/?probe=6d49e950fe) | Mar 03, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [395ee9975c](https://linux-hardware.org/?probe=395ee9975c) | Mar 01, 2021 |
| ASUSTek       | GL753VD                     | Notebook    | [bdb6fc8fb3](https://linux-hardware.org/?probe=bdb6fc8fb3) | Feb 27, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [4a0c1cf20f](https://linux-hardware.org/?probe=4a0c1cf20f) | Feb 27, 2021 |
| ASUSTek       | X550MD                      | Notebook    | [75d04a8384](https://linux-hardware.org/?probe=75d04a8384) | Feb 27, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [8b2adea4fc](https://linux-hardware.org/?probe=8b2adea4fc) | Feb 27, 2021 |
| Dell          | Latitude 7410               | Notebook    | [5b725b01aa](https://linux-hardware.org/?probe=5b725b01aa) | Feb 26, 2021 |
| Dell          | Latitude 7410               | Notebook    | [430ac9fa0c](https://linux-hardware.org/?probe=430ac9fa0c) | Feb 24, 2021 |
| Dell          | Latitude 7410               | Notebook    | [7aeb2cc674](https://linux-hardware.org/?probe=7aeb2cc674) | Feb 22, 2021 |
| Dell          | Latitude 7490               | Notebook    | [57718f7826](https://linux-hardware.org/?probe=57718f7826) | Feb 22, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [6a8d2a4826](https://linux-hardware.org/?probe=6a8d2a4826) | Feb 22, 2021 |
| Fujitsu Si... | AMILO Li 2735               | Notebook    | [ca3a6f2e30](https://linux-hardware.org/?probe=ca3a6f2e30) | Feb 21, 2021 |
| Fujitsu Si... | AMILO Li 2735               | Notebook    | [f873a05dc6](https://linux-hardware.org/?probe=f873a05dc6) | Feb 21, 2021 |
| Dell          | Latitude E6400              | Notebook    | [4285e6b02b](https://linux-hardware.org/?probe=4285e6b02b) | Feb 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | Notebook    | [c1dae36682](https://linux-hardware.org/?probe=c1dae36682) | Feb 20, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8f08d3592d](https://linux-hardware.org/?probe=8f08d3592d) | Feb 20, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [2f9c20e9ed](https://linux-hardware.org/?probe=2f9c20e9ed) | Feb 20, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [d8a44d0f28](https://linux-hardware.org/?probe=d8a44d0f28) | Feb 20, 2021 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [f088672fd6](https://linux-hardware.org/?probe=f088672fd6) | Feb 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3f321d1a28](https://linux-hardware.org/?probe=3f321d1a28) | Feb 19, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [663573b53a](https://linux-hardware.org/?probe=663573b53a) | Feb 18, 2021 |
| HP            | 1998                        | Desktop     | [a574c0a6bb](https://linux-hardware.org/?probe=a574c0a6bb) | Feb 18, 2021 |
| Lenovo        | ThinkPad W510 431924G       | Notebook    | [2f320b6b8b](https://linux-hardware.org/?probe=2f320b6b8b) | Feb 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f35f504d4c](https://linux-hardware.org/?probe=f35f504d4c) | Feb 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5d1d62012e](https://linux-hardware.org/?probe=5d1d62012e) | Feb 18, 2021 |
| ASUSTek       | X540NA                      | Notebook    | [ffe6defb70](https://linux-hardware.org/?probe=ffe6defb70) | Feb 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | Notebook    | [f9157c519d](https://linux-hardware.org/?probe=f9157c519d) | Feb 17, 2021 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [dcc226166f](https://linux-hardware.org/?probe=dcc226166f) | Feb 17, 2021 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [d326bb69fd](https://linux-hardware.org/?probe=d326bb69fd) | Feb 16, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [784536a677](https://linux-hardware.org/?probe=784536a677) | Feb 16, 2021 |
| Dell          | Latitude E5540              | Notebook    | [7832e1a3b7](https://linux-hardware.org/?probe=7832e1a3b7) | Feb 16, 2021 |
| Gigabyte      | GA-MA790GP-DS4H             | Desktop     | [d288f0a8cd](https://linux-hardware.org/?probe=d288f0a8cd) | Feb 16, 2021 |
| Gigabyte      | GA-MA790GP-DS4H             | Desktop     | [656a59d9a6](https://linux-hardware.org/?probe=656a59d9a6) | Feb 16, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Romania/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 204       | 12.38%  |
| Ubuntu 18.04      | 106       | 6.43%   |
| BlackPanther 18.1 | 57        | 3.46%   |
| OpenMandriva 4.2  | 43        | 2.61%   |
| Ubuntu 22.04      | 40        | 2.43%   |
| OpenMandriva 4.3  | 39        | 2.37%   |
| Arch              | 28        | 1.7%    |
| ROSA R10          | 27        | 1.64%   |
| Manjaro           | 24        | 1.46%   |
| KDE neon 20.04    | 24        | 1.46%   |
| Pop!_OS 21.04     | 23        | 1.4%    |
| Ubuntu 21.10      | 20        | 1.21%   |
| Pop!_OS 20.04     | 20        | 1.21%   |
| Endless 3.7.8     | 20        | 1.21%   |
| Zorin 15          | 19        | 1.15%   |
| Fedora 35         | 19        | 1.15%   |
| Zorin 16          | 18        | 1.09%   |
| Endless 3.9.5     | 18        | 1.09%   |
| Endless 3.9.1     | 18        | 1.09%   |
| Ubuntu 20.10      | 17        | 1.03%   |
| Ubuntu 19.10      | 17        | 1.03%   |
| Debian 11         | 17        | 1.03%   |
| Ubuntu 21.04      | 16        | 0.97%   |
| ArcoLinux Rolling | 16        | 0.97%   |
| Ubuntu 19.04      | 15        | 0.91%   |
| Pop!_OS 20.10     | 15        | 0.91%   |
| Linux Mint 20.2   | 15        | 0.91%   |
| Fedora 34         | 15        | 0.91%   |
| Endless 3.8.6     | 15        | 0.91%   |
| Endless 3.8.0     | 15        | 0.91%   |
| Linux Mint 20.3   | 14        | 0.85%   |
| Linux Mint 20.1   | 14        | 0.85%   |
| Arch Rolling      | 14        | 0.85%   |
| ROSA R9           | 13        | 0.79%   |
| Pop!_OS 21.10     | 13        | 0.79%   |
| Fedora 36         | 13        | 0.79%   |
| Xubuntu 20.04     | 12        | 0.73%   |
| ROSA R11          | 12        | 0.73%   |
| Pop!_OS 22.04     | 12        | 0.73%   |
| Endless 3.9.0     | 12        | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu            | 437       | 28.67%  |
| Endless           | 242       | 15.88%  |
| OpenMandriva      | 92        | 6.04%   |
| Fedora            | 80        | 5.25%   |
| Pop!_OS           | 79        | 5.18%   |
| Linux Mint        | 77        | 5.05%   |
| ROSA              | 64        | 4.2%    |
| BlackPanther      | 59        | 3.87%   |
| Manjaro           | 53        | 3.48%   |
| Arch              | 41        | 2.69%   |
| Zorin             | 40        | 2.62%   |
| Debian            | 35        | 2.3%    |
| KDE neon          | 26        | 1.71%   |
| Xubuntu           | 21        | 1.38%   |
| Kubuntu           | 18        | 1.18%   |
| ArcoLinux         | 18        | 1.18%   |
| Clear Linux       | 14        | 0.92%   |
| Ubuntu Unity      | 12        | 0.79%   |
| openSUSE          | 12        | 0.79%   |
| Kali              | 10        | 0.66%   |
| Elementary        | 10        | 0.66%   |
| Ubuntu MATE       | 9         | 0.59%   |
| Gentoo            | 8         | 0.52%   |
| Peppermint        | 7         | 0.46%   |
| Garuda Linux      | 6         | 0.39%   |
| SteamOS           | 5         | 0.33%   |
| LMDE              | 5         | 0.33%   |
| Linux Lite        | 5         | 0.33%   |
| Raspbian          | 4         | 0.26%   |
| Lubuntu           | 4         | 0.26%   |
| EndeavourOS       | 4         | 0.26%   |
| CentOS            | 3         | 0.2%    |
| Ubuntu Studio     | 2         | 0.13%   |
| Ubuntu Budgie     | 2         | 0.13%   |
| RHEL              | 2         | 0.13%   |
| Q4OS              | 2         | 0.13%   |
| Oracle Linux      | 2         | 0.13%   |
| MX                | 2         | 0.13%   |
| Xero              | 1         | 0.07%   |
| Ultramarine Linux | 1         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-14-generic                | 69        | 3.99%   |
| 5.4.0-42-generic                | 50        | 2.89%   |
| 4.18.16-desktop-1bP             | 45        | 2.6%    |
| 5.10.14-desktop-1omv4002        | 42        | 2.43%   |
| 5.16.7-desktop-1omv4003         | 34        | 1.97%   |
| 5.4.0-19-generic                | 32        | 1.85%   |
| 5.3.0-28-generic                | 26        | 1.5%    |
| 5.3.0-23-generic                | 18        | 1.04%   |
| 4.18.0-15-generic               | 17        | 0.98%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 16        | 0.92%   |
| 5.0.0-25-generic                | 15        | 0.87%   |
| 5.4.0-40-generic                | 14        | 0.81%   |
| 5.3.0-46-generic                | 13        | 0.75%   |
| 5.6.14-desktop-2bP              | 12        | 0.69%   |
| 5.0.0-20-generic                | 12        | 0.69%   |
| 5.4.0-52-generic                | 11        | 0.64%   |
| 5.4.0-29-generic                | 11        | 0.64%   |
| 5.4.0-26-generic                | 11        | 0.64%   |
| 5.3.0-19-generic                | 11        | 0.64%   |
| 5.15.0-52-generic               | 11        | 0.64%   |
| 5.11.0-35-generic               | 11        | 0.64%   |
| 5.4.0-56-generic                | 10        | 0.58%   |
| 5.4.0-54-generic                | 10        | 0.58%   |
| 5.13.0-28-generic               | 10        | 0.58%   |
| 5.11.0-7620-generic             | 10        | 0.58%   |
| 5.11.0-43-generic               | 10        | 0.58%   |
| 5.0.0-37-generic                | 10        | 0.58%   |
| 4.15.0-15-generic               | 10        | 0.58%   |
| 5.8.0-50-generic                | 9         | 0.52%   |
| 5.4.0-7634-generic              | 9         | 0.52%   |
| 5.4.0-74-generic                | 9         | 0.52%   |
| 5.4.0-66-generic                | 9         | 0.52%   |
| 5.4.0-47-generic                | 9         | 0.52%   |
| 5.4.0-37-generic                | 9         | 0.52%   |
| 5.4.0-31-generic                | 9         | 0.52%   |
| 5.3.0-51-generic                | 9         | 0.52%   |
| 5.15.0-48-generic               | 9         | 0.52%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 9         | 0.52%   |
| 5.8.0-7642-generic              | 8         | 0.46%   |
| 5.4.0-91-generic                | 8         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 302       | 18.34%  |
| 5.8.0   | 149       | 9.05%   |
| 5.3.0   | 117       | 7.1%    |
| 4.15.0  | 96        | 5.83%   |
| 5.11.0  | 93        | 5.65%   |
| 5.0.0   | 80        | 4.86%   |
| 5.15.0  | 68        | 4.13%   |
| 5.13.0  | 65        | 3.95%   |
| 4.18.0  | 52        | 3.16%   |
| 4.18.16 | 45        | 2.73%   |
| 5.10.14 | 43        | 2.61%   |
| 5.16.7  | 34        | 2.06%   |
| 5.10.0  | 24        | 1.46%   |
| 4.9.60  | 18        | 1.09%   |
| 4.9.20  | 15        | 0.91%   |
| 5.6.14  | 13        | 0.79%   |
| 4.19.0  | 11        | 0.67%   |
| 4.13.0  | 10        | 0.61%   |
| 4.9.76  | 8         | 0.49%   |
| 5.8.18  | 7         | 0.43%   |
| 5.19.0  | 6         | 0.36%   |
| 5.18.10 | 6         | 0.36%   |
| 5.9.16  | 5         | 0.3%    |
| 5.9.0   | 5         | 0.3%    |
| 5.18.12 | 5         | 0.3%    |
| 5.16.13 | 5         | 0.3%    |
| 5.15.8  | 5         | 0.3%    |
| 5.15.12 | 5         | 0.3%    |
| 5.8.3   | 4         | 0.24%   |
| 5.4.18  | 4         | 0.24%   |
| 5.3.18  | 4         | 0.24%   |
| 5.18.0  | 4         | 0.24%   |
| 5.17.0  | 4         | 0.24%   |
| 5.16.11 | 4         | 0.24%   |
| 5.15.4  | 4         | 0.24%   |
| 5.14.0  | 4         | 0.24%   |
| 5.12.4  | 4         | 0.24%   |
| 5.1.15  | 4         | 0.24%   |
| 4.9.9   | 4         | 0.24%   |
| 4.9.124 | 4         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 323       | 19.8%   |
| 5.8     | 176       | 10.79%  |
| 5.3     | 127       | 7.79%   |
| 5.15    | 109       | 6.68%   |
| 5.11    | 107       | 6.56%   |
| 4.18    | 99        | 6.07%   |
| 4.15    | 96        | 5.89%   |
| 5.10    | 90        | 5.52%   |
| 5.0     | 85        | 5.21%   |
| 5.13    | 72        | 4.41%   |
| 5.16    | 63        | 3.86%   |
| 4.9     | 49        | 3%      |
| 5.6     | 27        | 1.66%   |
| 5.18    | 25        | 1.53%   |
| 5.9     | 22        | 1.35%   |
| 5.19    | 22        | 1.35%   |
| 5.17    | 20        | 1.23%   |
| 5.12    | 18        | 1.1%    |
| 5.14    | 17        | 1.04%   |
| 6.0     | 16        | 0.98%   |
| 4.19    | 14        | 0.86%   |
| 5.7     | 10        | 0.61%   |
| 4.13    | 10        | 0.61%   |
| 4.1     | 8         | 0.49%   |
| 5.5     | 7         | 0.43%   |
| 5.2     | 5         | 0.31%   |
| 5.1     | 4         | 0.25%   |
| 4.8     | 3         | 0.18%   |
| 4.12    | 2         | 0.12%   |
| 4.4     | 1         | 0.06%   |
| 4.17    | 1         | 0.06%   |
| 4.16    | 1         | 0.06%   |
| 4.14    | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1436      | 97.22%  |
| i686    | 33        | 2.23%   |
| armv7l  | 4         | 0.27%   |
| aarch64 | 4         | 0.27%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 728       | 47.55%  |
| KDE5            | 261       | 17.05%  |
| Unknown         | 220       | 14.37%  |
| XFCE            | 77        | 5.03%   |
| X-Cinnamon      | 58        | 3.79%   |
| KDE4            | 44        | 2.87%   |
| KDE             | 38        | 2.48%   |
| MATE            | 24        | 1.57%   |
| Unity           | 12        | 0.78%   |
| LXDE            | 12        | 0.78%   |
| Cinnamon        | 12        | 0.78%   |
| LXQt            | 10        | 0.65%   |
| Pantheon        | 8         | 0.52%   |
| i3              | 5         | 0.33%   |
| Openbox         | 3         | 0.2%    |
| Deepin          | 3         | 0.2%    |
| Budgie          | 3         | 0.2%    |
| xmonad          | 2         | 0.13%   |
| sway            | 2         | 0.13%   |
| GNOME Flashback | 2         | 0.13%   |
| GNOME Classic   | 2         | 0.13%   |
| jwm             | 1         | 0.07%   |
| GNUstep         | 1         | 0.07%   |
| GNOME-Flashback | 1         | 0.07%   |
| dusk            | 1         | 0.07%   |
| bspwm           | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1205      | 80.07%  |
| Unknown     | 145       | 9.63%   |
| Wayland     | 134       | 8.9%    |
| Tty         | 20        | 1.33%   |
| Unspecified | 1         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 885       | 57.84%  |
| SDDM    | 238       | 15.56%  |
| GDM     | 145       | 9.48%   |
| GDM3    | 89        | 5.82%   |
| LightDM | 81        | 5.29%   |
| KDM     | 44        | 2.88%   |
| TDM     | 41        | 2.68%   |
| XDM     | 3         | 0.2%    |
| SLiM    | 2         | 0.13%   |
| Ly      | 1         | 0.07%   |
| LXDM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 849       | 55.93%  |
| Unknown     | 306       | 20.16%  |
| ro_RO       | 265       | 17.46%  |
| en_GB       | 25        | 1.65%   |
| C           | 23        | 1.52%   |
| hu_HU       | 12        | 0.79%   |
| it_IT       | 10        | 0.66%   |
| de_DE       | 4         | 0.26%   |
| fr_FR       | 3         | 0.2%    |
| es_ES       | 3         | 0.2%    |
| en_IL       | 3         | 0.2%    |
| ru_RU       | 2         | 0.13%   |
| en_IN       | 2         | 0.13%   |
| en_AG       | 2         | 0.13%   |
| nl_NL       | 1         | 0.07%   |
| fr_CH       | 1         | 0.07%   |
| es_MX       | 1         | 0.07%   |
| en_US.UTF8  | 1         | 0.07%   |
| en_US.utf-8 | 1         | 0.07%   |
| en_DE       | 1         | 0.07%   |
| en_CA       | 1         | 0.07%   |
| en_001      | 1         | 0.07%   |
| C.UTF8      | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 756       | 50.33%  |
| EFI  | 746       | 49.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1097      | 72.65%  |
| Unknown | 154       | 10.2%   |
| Overlay | 147       | 9.74%   |
| Btrfs   | 81        | 5.36%   |
| Xfs     | 13        | 0.86%   |
| Tmpfs   | 6         | 0.4%    |
| Zfs     | 4         | 0.26%   |
| F2fs    | 3         | 0.2%    |
| Ext2    | 3         | 0.2%    |
| Jfs     | 1         | 0.07%   |
| Ext3    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 921       | 61.44%  |
| GPT     | 370       | 24.68%  |
| MBR     | 208       | 13.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1307      | 86.9%   |
| Yes       | 197       | 13.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1098      | 73.01%  |
| Yes       | 406       | 26.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 383       | 25.97%  |
| Lenovo                  | 228       | 15.46%  |
| Dell                    | 180       | 12.2%   |
| Hewlett-Packard         | 173       | 11.73%  |
| Gigabyte Technology     | 109       | 7.39%   |
| Acer                    | 97        | 6.58%   |
| MSI                     | 72        | 4.88%   |
| ASRock                  | 37        | 2.51%   |
| Toshiba                 | 21        | 1.42%   |
| Intel                   | 14        | 0.95%   |
| Fujitsu Siemens         | 13        | 0.88%   |
| Apple                   | 13        | 0.88%   |
| Complet                 | 12        | 0.81%   |
| Sony                    | 10        | 0.68%   |
| Medion                  | 9         | 0.61%   |
| Unknown                 | 9         | 0.61%   |
| Raspberry Pi Foundation | 8         | 0.54%   |
| HUAWEI                  | 7         | 0.47%   |
| Fujitsu                 | 7         | 0.47%   |
| Pegatron                | 6         | 0.41%   |
| Foxconn                 | 6         | 0.41%   |
| Samsung Electronics     | 5         | 0.34%   |
| Valve                   | 4         | 0.27%   |
| Packard Bell            | 4         | 0.27%   |
| Chuwi                   | 4         | 0.27%   |
| Allview                 | 4         | 0.27%   |
| Alienware               | 3         | 0.2%    |
| Timi                    | 2         | 0.14%   |
| Supermicro              | 2         | 0.14%   |
| IBM                     | 2         | 0.14%   |
| AMI                     | 2         | 0.14%   |
| ZOTAC                   | 1         | 0.07%   |
| Visual Fan              | 1         | 0.07%   |
| TUXEDO                  | 1         | 0.07%   |
| Thomson                 | 1         | 0.07%   |
| Prestigio               | 1         | 0.07%   |
| Panasonic               | 1         | 0.07%   |
| OEM_MB                  | 1         | 0.07%   |
| Notebook                | 1         | 0.07%   |
| nJoy Romania            | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS X541NA                                | 17        | 1.15%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 16        | 1.08%   |
| Unknown                                    | 12        | 0.81%   |
| ASUS All Series                            | 11        | 0.75%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 10        | 0.68%   |
| ASUS VivoBook_ASUSLaptop X509FA_X509FA     | 9         | 0.61%   |
| Dell XPS 15 9530                           | 7         | 0.47%   |
| Complet MY8312                             | 7         | 0.47%   |
| Lenovo Legion Y530-15ICH 81FV              | 6         | 0.41%   |
| ASUS X406UAR                               | 6         | 0.41%   |
| ASUS VivoBook_ASUSLaptop X509FB_X509FB     | 6         | 0.41%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_A540MA | 6         | 0.41%   |
| Lenovo V330-15IKB 81AX                     | 5         | 0.34%   |
| Gigabyte B450M DS3H                        | 5         | 0.34%   |
| ASUS X541UVK                               | 5         | 0.34%   |
| ASUS X541UAK                               | 5         | 0.34%   |
| ASUS VivoBook_ASUS Laptop X505ZA_A505ZA    | 5         | 0.34%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 5         | 0.34%   |
| Valve Jupiter                              | 4         | 0.27%   |
| MSI MS-7996                                | 4         | 0.27%   |
| MSI MS-7721                                | 4         | 0.27%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 4         | 0.27%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 4         | 0.27%   |
| Lenovo G510 20238                          | 4         | 0.27%   |
| HP Notebook                                | 4         | 0.27%   |
| Gigabyte X470 AORUS ULTRA GAMING           | 4         | 0.27%   |
| Dell OptiPlex 7010                         | 4         | 0.27%   |
| Dell Latitude E6410                        | 4         | 0.27%   |
| Dell Inspiron 5558                         | 4         | 0.27%   |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.27%   |
| ASUS X542UAR                               | 4         | 0.27%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA     | 4         | 0.27%   |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA     | 4         | 0.27%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 4         | 0.27%   |
| ASUS GL552JX                               | 4         | 0.27%   |
| Acer Aspire E5-573G                        | 4         | 0.27%   |
| Acer Aspire E1-531                         | 4         | 0.27%   |
| Acer Aspire A315-21G                       | 4         | 0.27%   |
| RPi Raspberry Pi                           | 3         | 0.2%    |
| Lenovo V110-15ISK 80TL                     | 3         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUS VivoBook           | 107       | 7.25%   |
| Lenovo IdeaPad          | 73        | 4.95%   |
| Lenovo ThinkPad         | 68        | 4.61%   |
| Acer Aspire             | 66        | 4.47%   |
| Dell Latitude           | 50        | 3.39%   |
| Dell Inspiron           | 43        | 2.92%   |
| HP Compaq               | 31        | 2.1%    |
| HP EliteBook            | 27        | 1.83%   |
| ASUS ROG                | 26        | 1.76%   |
| HP ProBook              | 25        | 1.69%   |
| Dell OptiPlex           | 25        | 1.69%   |
| ASUS PRIME              | 23        | 1.56%   |
| Toshiba Satellite       | 20        | 1.36%   |
| Dell XPS                | 19        | 1.29%   |
| HP Pavilion             | 18        | 1.22%   |
| ASUS X541NA             | 17        | 1.15%   |
| Lenovo Legion           | 16        | 1.08%   |
| HP Laptop               | 15        | 1.02%   |
| Lenovo ThinkCentre      | 14        | 0.95%   |
| ASUS TUF                | 14        | 0.95%   |
| ASUS ASUS               | 14        | 0.95%   |
| Dell Vostro             | 12        | 0.81%   |
| Unknown                 | 12        | 0.81%   |
| Dell Precision          | 11        | 0.75%   |
| ASUS All                | 11        | 0.75%   |
| ASUS ZenBook            | 10        | 0.68%   |
| RPi Raspberry           | 8         | 0.54%   |
| Fujitsu Siemens ESPRIMO | 8         | 0.54%   |
| Complet MY8312          | 7         | 0.47%   |
| Acer Extensa            | 7         | 0.47%   |
| HP ZBook                | 6         | 0.41%   |
| Gigabyte X570           | 6         | 0.41%   |
| Gigabyte B450M          | 6         | 0.41%   |
| Dell System             | 6         | 0.41%   |
| Dell PowerEdge          | 6         | 0.41%   |
| ASUS X406UAR            | 6         | 0.41%   |
| Acer Swift              | 6         | 0.41%   |
| Acer Nitro              | 6         | 0.41%   |
| Lenovo Yoga             | 5         | 0.34%   |
| Lenovo V330-15IKB       | 5         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 200       | 13.56%  |
| 2018    | 179       | 12.14%  |
| 2017    | 128       | 8.68%   |
| 2020    | 108       | 7.32%   |
| 2013    | 101       | 6.85%   |
| 2015    | 92        | 6.24%   |
| 2012    | 83        | 5.63%   |
| 2011    | 81        | 5.49%   |
| 2014    | 80        | 5.42%   |
| 2021    | 77        | 5.22%   |
| 2010    | 69        | 4.68%   |
| 2008    | 65        | 4.41%   |
| 2016    | 60        | 4.07%   |
| 2009    | 54        | 3.66%   |
| 2007    | 53        | 3.59%   |
| 2022    | 15        | 1.02%   |
| 2006    | 15        | 1.02%   |
| Unknown | 8         | 0.54%   |
| 2005    | 5         | 0.34%   |
| 2004    | 2         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 961       | 65.15%  |
| Desktop        | 446       | 30.24%  |
| All in one     | 20        | 1.36%   |
| Convertible    | 13        | 0.88%   |
| Mini pc        | 12        | 0.81%   |
| Tablet         | 9         | 0.61%   |
| System on chip | 8         | 0.54%   |
| Server         | 6         | 0.41%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1415      | 95.29%  |
| Enabled  | 70        | 4.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1475      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 431       | 28.7%   |
| 4.01-8.0        | 354       | 23.57%  |
| 8.01-16.0       | 257       | 17.11%  |
| 16.01-24.0      | 231       | 15.38%  |
| 32.01-64.0      | 88        | 5.86%   |
| 1.01-2.0        | 72        | 4.79%   |
| 64.01-256.0     | 26        | 1.73%   |
| 2.01-3.0        | 17        | 1.13%   |
| 0.51-1.0        | 13        | 0.87%   |
| 24.01-32.0      | 12        | 0.8%    |
| More than 256.0 | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 642       | 39.07%  |
| 2.01-3.0    | 392       | 23.86%  |
| 3.01-4.0    | 184       | 11.2%   |
| 0.51-1.0    | 175       | 10.65%  |
| 4.01-8.0    | 158       | 9.62%   |
| 8.01-16.0   | 42        | 2.56%   |
| 0.01-0.5    | 41        | 2.5%    |
| 16.01-24.0  | 3         | 0.18%   |
| 32.01-64.0  | 2         | 0.12%   |
| 24.01-32.0  | 2         | 0.12%   |
| 64.01-256.0 | 2         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1011      | 66.69%  |
| 2      | 334       | 22.03%  |
| 3      | 94        | 6.2%    |
| 4      | 35        | 2.31%   |
| 5      | 16        | 1.06%   |
| 0      | 13        | 0.86%   |
| 6      | 4         | 0.26%   |
| 9      | 2         | 0.13%   |
| 8      | 2         | 0.13%   |
| 24     | 1         | 0.07%   |
| 15     | 1         | 0.07%   |
| 14     | 1         | 0.07%   |
| 11     | 1         | 0.07%   |
| 7      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 880       | 59.14%  |
| Yes       | 608       | 40.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1213      | 82.18%  |
| No        | 263       | 17.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1127      | 75.99%  |
| No        | 356       | 24.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 898       | 60.11%  |
| No        | 596       | 39.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Romania | 1475      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Bucharest             | 483       | 30.84%  |
| Cluj-Napoca           | 109       | 6.96%   |
| Iasi                  | 76        | 4.85%   |
| Timișoara            | 58        | 3.7%    |
| Brasov                | 45        | 2.87%   |
| Târgu Mureş         | 42        | 2.68%   |
| Ploieşti             | 36        | 2.3%    |
| Constanța            | 29        | 1.85%   |
| Oradea                | 27        | 1.72%   |
| Sibiu                 | 26        | 1.66%   |
| Piteşti              | 23        | 1.47%   |
| Arad                  | 23        | 1.47%   |
| Craiova               | 21        | 1.34%   |
| Popesti-Leordeni      | 19        | 1.21%   |
| Galati                | 18        | 1.15%   |
| Baia Mare             | 17        | 1.09%   |
| Zalău                | 15        | 0.96%   |
| Voluntari             | 13        | 0.83%   |
| Râmnicu Vâlcea      | 13        | 0.83%   |
| Satu Mare             | 12        | 0.77%   |
| Miercurea-Ciuc        | 12        | 0.77%   |
| Botosani              | 12        | 0.77%   |
| Bacau                 | 12        | 0.77%   |
| Targoviste            | 11        | 0.7%    |
| Braila                | 11        | 0.7%    |
| Reşiţa              | 10        | 0.64%   |
| Piatra Neamţ         | 10        | 0.64%   |
| Focşani              | 10        | 0.64%   |
| Floresti              | 10        | 0.64%   |
| Drobeta-Turnu Severin | 9         | 0.57%   |
| Alba Iulia            | 9         | 0.57%   |
| Târgu Jiu            | 8         | 0.51%   |
| Mediaş               | 8         | 0.51%   |
| Tulcea                | 7         | 0.45%   |
| Sfantu Gheorghe       | 7         | 0.45%   |
| Deva                  | 7         | 0.45%   |
| Iorcani               | 6         | 0.38%   |
| Alexandria            | 6         | 0.38%   |
| Otopeni               | 5         | 0.32%   |
| Chiajna               | 5         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 314       | 471    | 15.35%  |
| WDC                   | 310       | 435    | 15.16%  |
| Samsung Electronics   | 258       | 336    | 12.62%  |
| Kingston              | 245       | 329    | 11.98%  |
| Toshiba               | 151       | 186    | 7.38%   |
| Unknown               | 81        | 108    | 3.96%   |
| SanDisk               | 81        | 95     | 3.96%   |
| Intel                 | 70        | 88     | 3.42%   |
| A-DATA Technology     | 68        | 86     | 3.33%   |
| Hitachi               | 58        | 71     | 2.84%   |
| HGST                  | 58        | 74     | 2.84%   |
| SK hynix              | 55        | 75     | 2.69%   |
| Micron Technology     | 33        | 38     | 1.61%   |
| Crucial               | 26        | 30     | 1.27%   |
| Patriot               | 19        | 22     | 0.93%   |
| Phison                | 15        | 18     | 0.73%   |
| Maxtor                | 13        | 19     | 0.64%   |
| SPCC                  | 11        | 13     | 0.54%   |
| OCZ                   | 9         | 16     | 0.44%   |
| KIOXIA                | 9         | 9      | 0.44%   |
| Hewlett-Packard       | 9         | 11     | 0.44%   |
| FORESEE               | 9         | 10     | 0.44%   |
| Corsair               | 9         | 12     | 0.44%   |
| XPG                   | 8         | 12     | 0.39%   |
| Fujitsu               | 7         | 8      | 0.34%   |
| Realtek Semiconductor | 6         | 7      | 0.29%   |
| Kingmax               | 6         | 7      | 0.29%   |
| Apple                 | 6         | 9      | 0.29%   |
| Transcend             | 5         | 7      | 0.24%   |
| GOODRAM               | 5         | 5      | 0.24%   |
| Gigabyte Technology   | 5         | 5      | 0.24%   |
| China                 | 5         | 5      | 0.24%   |
| ASMT                  | 5         | 5      | 0.24%   |
| Plextor               | 4         | 4      | 0.2%    |
| Netac                 | 4         | 6      | 0.2%    |
| Apacer                | 4         | 5      | 0.2%    |
| Team                  | 3         | 3      | 0.15%   |
| Silicon Motion        | 3         | 3      | 0.15%   |
| LITEON                | 3         | 3      | 0.15%   |
| Lite-On               | 3         | 3      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 57        | 2.61%   |
| Toshiba MQ01ABF050 500GB               | 43        | 1.97%   |
| Seagate ST1000LM035-1RK172 1TB         | 43        | 1.97%   |
| Seagate ST500LT012-1DG142 500GB        | 26        | 1.19%   |
| Kingston SA400S37120G 120GB SSD        | 26        | 1.19%   |
| Kingston SA400S37480G 480GB SSD        | 23        | 1.05%   |
| Toshiba MQ04ABF100 1TB                 | 21        | 0.96%   |
| Seagate ST1000DM010-2EP102 1TB         | 21        | 0.96%   |
| Samsung NVMe SSD Drive 512GB           | 21        | 0.96%   |
| Kingston SV300S37A120G 120GB SSD       | 21        | 0.96%   |
| Unknown MMC Card  32GB                 | 20        | 0.91%   |
| HGST HTS721010A9E630 1TB               | 20        | 0.91%   |
| SanDisk NVMe SSD Drive 256GB           | 18        | 0.82%   |
| Samsung SSD 850 EVO 250GB              | 18        | 0.82%   |
| Samsung SSD 860 EVO 500GB              | 17        | 0.78%   |
| SanDisk NVMe SSD Drive 512GB           | 16        | 0.73%   |
| WDC WD10EZEX-08WN4A0 1TB               | 14        | 0.64%   |
| Seagate ST500DM002-1BD142 500GB        | 13        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 13        | 0.59%   |
| Kingston SV300S37A240G 240GB SSD       | 13        | 0.59%   |
| SK hynix NVMe SSD Drive 512GB          | 12        | 0.55%   |
| Patriot Burst 120GB SSD                | 12        | 0.55%   |
| Intel NVMe SSD Drive 512GB             | 12        | 0.55%   |
| Toshiba DT01ACA050 500GB               | 11        | 0.5%    |
| Seagate Expansion 1TB                  | 11        | 0.5%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 11        | 0.5%    |
| A-DATA SU650 240GB SSD                 | 11        | 0.5%    |
| Unknown MMC Card  64GB                 | 10        | 0.46%   |
| Kingston SUV400S37120G 120GB SSD       | 10        | 0.46%   |
| HGST HTS545050A7E680 500GB             | 10        | 0.46%   |
| Samsung SSD 860 EVO 250GB              | 9         | 0.41%   |
| Kingston RBUSNS8180DS3256GJ 256GB SSD  | 9         | 0.41%   |
| Kingston RBUSC180DS37256GJ 256GB SSD   | 9         | 0.41%   |
| HGST HTS541010A9E680 1TB               | 9         | 0.41%   |
| WDC WD10SPZX-21Z10T0 1TB               | 8         | 0.37%   |
| Toshiba MQ01ABD100 1TB                 | 8         | 0.37%   |
| Samsung SSD 850 EVO 500GB              | 8         | 0.37%   |
| Kingston SUV500MS480G 480GB SSD        | 8         | 0.37%   |
| A-DATA SU630 240GB SSD                 | 8         | 0.37%   |
| WDC WD10JPCX-24UE4T0 1TB               | 7         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 313       | 470    | 34.97%  |
| WDC                 | 264       | 381    | 29.5%   |
| Toshiba             | 129       | 159    | 14.41%  |
| Hitachi             | 58        | 71     | 6.48%   |
| HGST                | 58        | 74     | 6.48%   |
| Samsung Electronics | 30        | 34     | 3.35%   |
| Maxtor              | 12        | 18     | 1.34%   |
| Unknown             | 7         | 8      | 0.78%   |
| Fujitsu             | 7         | 8      | 0.78%   |
| ASMT                | 5         | 5      | 0.56%   |
| Apple               | 3         | 4      | 0.34%   |
| IBM/Hitachi         | 2         | 2      | 0.22%   |
| Hewlett-Packard     | 2         | 3      | 0.22%   |
| LaCie               | 1         | 4      | 0.11%   |
| Intenso             | 1         | 1      | 0.11%   |
| HGST HTS            | 1         | 1      | 0.11%   |
| ExcelStor           | 1         | 1      | 0.11%   |
| ASMT109x            | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 212       | 283    | 32.27%  |
| Samsung Electronics | 119       | 160    | 18.11%  |
| A-DATA Technology   | 62        | 80     | 9.44%   |
| SanDisk             | 34        | 44     | 5.18%   |
| Intel               | 25        | 28     | 3.81%   |
| Crucial             | 23        | 27     | 3.5%    |
| WDC                 | 20        | 23     | 3.04%   |
| Patriot             | 18        | 21     | 2.74%   |
| SK hynix            | 17        | 25     | 2.59%   |
| Micron Technology   | 14        | 15     | 2.13%   |
| SPCC                | 11        | 13     | 1.67%   |
| Toshiba             | 9         | 9      | 1.37%   |
| OCZ                 | 9         | 16     | 1.37%   |
| FORESEE             | 9         | 10     | 1.37%   |
| Corsair             | 7         | 9      | 1.07%   |
| Kingmax             | 6         | 7      | 0.91%   |
| Hewlett-Packard     | 5         | 5      | 0.76%   |
| GOODRAM             | 5         | 5      | 0.76%   |
| Gigabyte Technology | 5         | 5      | 0.76%   |
| China               | 5         | 5      | 0.76%   |
| Transcend           | 4         | 6      | 0.61%   |
| Netac               | 4         | 6      | 0.61%   |
| Apacer              | 4         | 5      | 0.61%   |
| Team                | 3         | 3      | 0.46%   |
| LITEON              | 3         | 3      | 0.46%   |
| Emtec               | 3         | 3      | 0.46%   |
| Verbatim            | 2         | 3      | 0.3%    |
| Teclast             | 2         | 2      | 0.3%    |
| LITEONIT            | 2         | 2      | 0.3%    |
| Lite-On             | 2         | 2      | 0.3%    |
| W800S               | 1         | 1      | 0.15%   |
| Unknown             | 1         | 1      | 0.15%   |
| TO Exter            | 1         | 3      | 0.15%   |
| PNY                 | 1         | 2      | 0.15%   |
| OCZ-VERTEX3         | 1         | 1      | 0.15%   |
| Maxtor              | 1         | 1      | 0.15%   |
| Kston               | 1         | 5      | 0.15%   |
| KingDian            | 1         | 1      | 0.15%   |
| EDGE SE8            | 1         | 1      | 0.15%   |
| ASUS-PHISON         | 1         | 2      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 782       | 1245   | 42.07%  |
| SSD     | 601       | 847    | 32.33%  |
| NVMe    | 393       | 514    | 21.14%  |
| MMC     | 69        | 92     | 3.71%   |
| Unknown | 14        | 16     | 0.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1136      | 2032   | 68.68%  |
| NVMe | 393       | 513    | 23.76%  |
| MMC  | 69        | 92     | 4.17%   |
| SAS  | 56        | 77     | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 879       | 1360   | 64.16%  |
| 0.51-1.0   | 378       | 508    | 27.59%  |
| 1.01-2.0   | 68        | 102    | 4.96%   |
| 3.01-4.0   | 15        | 27     | 1.09%   |
| 4.01-10.0  | 14        | 46     | 1.02%   |
| 2.01-3.0   | 13        | 44     | 0.95%   |
| 10.01-20.0 | 3         | 5      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 441       | 28.11%  |
| 251-500        | 349       | 22.24%  |
| 501-1000       | 241       | 15.36%  |
| 1-20           | 147       | 9.37%   |
| 51-100         | 113       | 7.2%    |
| 1001-2000      | 78        | 4.97%   |
| 21-50          | 76        | 4.84%   |
| Unknown        | 69        | 4.4%    |
| 2001-3000      | 28        | 1.78%   |
| More than 3000 | 27        | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 653       | 40.43%  |
| 21-50          | 337       | 20.87%  |
| 101-250        | 173       | 10.71%  |
| 51-100         | 171       | 10.59%  |
| 251-500        | 91        | 5.63%   |
| 501-1000       | 72        | 4.46%   |
| Unknown        | 69        | 4.27%   |
| 1001-2000      | 33        | 2.04%   |
| More than 3000 | 11        | 0.68%   |
| 2001-3000      | 5         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Hitachi HTS725032A7E630 320GB            | 7         | 7      | 4.09%   |
| HGST HTS541010A9E680 1TB                 | 4         | 4      | 2.34%   |
| WDC WD5000AAKX-001CA0 500GB              | 3         | 3      | 1.75%   |
| WDC WD3200AAJS-60Z0A0 320GB              | 3         | 6      | 1.75%   |
| Seagate ST9500420AS 500GB                | 3         | 3      | 1.75%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 1.75%   |
| WDC WD5000AADS-00S9B0 500GB              | 2         | 2      | 1.17%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD | 2         | 2      | 1.17%   |
| Seagate ST95005620AS 500GB               | 2         | 5      | 1.17%   |
| Seagate ST9500325AS 500GB                | 2         | 2      | 1.17%   |
| Seagate ST9160821AS 160GB                | 2         | 2      | 1.17%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 3      | 1.17%   |
| Seagate ST500DM002-1BD142 500GB          | 2         | 2      | 1.17%   |
| Seagate ST3500320AS 500GB                | 2         | 3      | 1.17%   |
| Seagate ST3500312CS 500GB                | 2         | 2      | 1.17%   |
| Seagate ST3250318AS 250GB                | 2         | 3      | 1.17%   |
| Seagate ST1000DM010-2EP102 1TB           | 2         | 2      | 1.17%   |
| Seagate ST1000DM003-1SB102 1TB           | 2         | 2      | 1.17%   |
| OCZ ARC100 240GB SSD                     | 2         | 2      | 1.17%   |
| Maxtor STM3250310AS 250GB                | 2         | 3      | 1.17%   |
| Hitachi HTS545016B9A300 160GB            | 2         | 2      | 1.17%   |
| HGST HTS725050A7E630 500GB               | 2         | 2      | 1.17%   |
| Apacer 16GB SATA Flash Drive SSD         | 2         | 3      | 1.17%   |
| WDC WDS120G2G0A-00JH30 120GB SSD         | 1         | 1      | 0.58%   |
| WDC WD7500BPVT-60HXZT3 752GB             | 1         | 2      | 0.58%   |
| WDC WD7500BPVT-22HXZT3 752GB             | 1         | 1      | 0.58%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.58%   |
| WDC WD5000BPKT-60PK4T0 500GB             | 1         | 2      | 0.58%   |
| WDC WD5000BEVT-60A0RT0 500GB             | 1         | 1      | 0.58%   |
| WDC WD5000AACS-00G8B1 500GB              | 1         | 2      | 0.58%   |
| WDC WD400EB-00CPF0 40GB                  | 1         | 1      | 0.58%   |
| WDC WD400BD-08JMC0 40GB                  | 1         | 1      | 0.58%   |
| WDC WD3200BPVT-22JJ5T0 320GB             | 1         | 1      | 0.58%   |
| WDC WD3200AVVS-63L2B0 320GB              | 1         | 1      | 0.58%   |
| WDC WD3200AVBS-63TAA0 320GB              | 1         | 1      | 0.58%   |
| WDC WD3200AAKS-75L9A0 320GB              | 1         | 1      | 0.58%   |
| WDC WD30PURX-64P6ZY0 3TB                 | 1         | 2      | 0.58%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 10     | 0.58%   |
| WDC WD30EFRX-68AX9N0 3TB                 | 1         | 1      | 0.58%   |
| WDC WD2500JS-60MHB5 250GB                | 1         | 3      | 0.58%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 56     | 25.77%  |
| WDC                 | 40        | 61     | 24.54%  |
| Hitachi             | 19        | 21     | 11.66%  |
| Samsung Electronics | 13        | 14     | 7.98%   |
| HGST                | 12        | 12     | 7.36%   |
| Toshiba             | 9         | 10     | 5.52%   |
| Maxtor              | 5         | 7      | 3.07%   |
| Kingston            | 4         | 4      | 2.45%   |
| SK hynix            | 2         | 2      | 1.23%   |
| OCZ                 | 2         | 2      | 1.23%   |
| Intel               | 2         | 2      | 1.23%   |
| Fujitsu             | 2         | 2      | 1.23%   |
| Apacer              | 2         | 3      | 1.23%   |
| Teclast             | 1         | 1      | 0.61%   |
| SanDisk             | 1         | 1      | 0.61%   |
| Plextor             | 1         | 1      | 0.61%   |
| Patriot             | 1         | 1      | 0.61%   |
| Micron Technology   | 1         | 1      | 0.61%   |
| LITEONIT            | 1         | 1      | 0.61%   |
| Hewlett-Packard     | 1         | 1      | 0.61%   |
| Corsair             | 1         | 2      | 0.61%   |
| A-DATA Technology   | 1         | 1      | 0.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 56     | 30.66%  |
| WDC                 | 37        | 58     | 27.01%  |
| Hitachi             | 19        | 21     | 13.87%  |
| HGST                | 12        | 12     | 8.76%   |
| Samsung Electronics | 11        | 12     | 8.03%   |
| Toshiba             | 9         | 10     | 6.57%   |
| Maxtor              | 5         | 7      | 3.65%   |
| Fujitsu             | 2         | 2      | 1.46%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 127       | 178    | 83.01%  |
| SSD  | 25        | 27     | 16.34%  |
| NVMe | 1         | 1      | 0.65%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60KA9T0 320GB | 1         | 1      | 33.33%  |
| WDC WD2500BEVS-22UST0 250GB  | 1         | 1      | 33.33%  |
| Seagate ST3160215A 160GB     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 976       | 1704   | 60.89%  |
| Works    | 478       | 801    | 29.82%  |
| Malfunc  | 146       | 206    | 9.11%   |
| Failed   | 3         | 3      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1101      | 61.3%   |
| AMD                              | 228       | 12.69%  |
| Samsung Electronics              | 126       | 7.02%   |
| SanDisk                          | 70        | 3.9%    |
| Kingston Technology Company      | 43        | 2.39%   |
| SK hynix                         | 37        | 2.06%   |
| Micron Technology                | 19        | 1.06%   |
| Phison Electronics               | 17        | 0.95%   |
| ASMedia Technology               | 17        | 0.95%   |
| ADATA Technology                 | 16        | 0.89%   |
| Marvell Technology Group         | 15        | 0.84%   |
| JMicron Technology               | 15        | 0.84%   |
| Toshiba America Info Systems     | 14        | 0.78%   |
| Nvidia                           | 13        | 0.72%   |
| Realtek Semiconductor            | 11        | 0.61%   |
| KIOXIA                           | 11        | 0.61%   |
| Silicon Motion                   | 8         | 0.45%   |
| Lite-On Technology               | 5         | 0.28%   |
| VIA Technologies                 | 4         | 0.22%   |
| Silicon Integrated Systems [SiS] | 4         | 0.22%   |
| Silicon Image                    | 4         | 0.22%   |
| Micron/Crucial Technology        | 4         | 0.22%   |
| LSI Logic / Symbios Logic        | 4         | 0.22%   |
| Broadcom / LSI                   | 3         | 0.17%   |
| Solid State Storage Technology   | 2         | 0.11%   |
| Lenovo                           | 2         | 0.11%   |
| Seagate Technology               | 1         | 0.06%   |
| Integrated Technology Express    | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 167       | 8.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 94        | 4.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 88        | 4.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 66        | 3.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 63        | 3.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 61        | 2.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 52        | 2.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 45        | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 43        | 2.07%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 39        | 1.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 39        | 1.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 33        | 1.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 32        | 1.54%   |
| AMD 400 Series Chipset SATA Controller                                         | 32        | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 29        | 1.39%   |
| Samsung NVMe SSD Controller 980                                                | 28        | 1.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 28        | 1.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 28        | 1.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 27        | 1.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                            | 26        | 1.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 25        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 25        | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 23        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 23        | 1.11%   |
| Kingston Company A2000 NVMe SSD                                                | 22        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 22        | 1.06%   |
| Intel SSD 660P Series                                                          | 21        | 1.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 21        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 21        | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 20        | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 20        | 0.96%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 19        | 0.91%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 19        | 0.91%   |
| Micron Non-Volatile memory controller                                          | 19        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 18        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 16        | 0.77%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 16        | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 16        | 0.77%   |
| AMD FCH SATA Controller D                                                      | 16        | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1090      | 58.92%  |
| NVMe | 402       | 21.73%  |
| IDE  | 208       | 11.24%  |
| RAID | 144       | 7.78%   |
| SAS  | 6         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1181      | 80.07%  |
| AMD    | 286       | 19.39%  |
| ARM    | 8         | 0.54%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 39        | 2.64%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 25        | 1.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 1.69%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 24        | 1.62%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 19        | 1.29%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 18        | 1.22%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.08%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 15        | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 0.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 0.95%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 14        | 0.95%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 0.88%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 11        | 0.74%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 11        | 0.74%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 10        | 0.68%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 10        | 0.68%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 10        | 0.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 10        | 0.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 0.61%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 9         | 0.61%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 9         | 0.61%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 9         | 0.61%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 9         | 0.61%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 9         | 0.61%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 8         | 0.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 8         | 0.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 8         | 0.54%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 0.54%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 0.54%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 7         | 0.47%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 7         | 0.47%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 7         | 0.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 0.47%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 7         | 0.47%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 7         | 0.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.47%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 7         | 0.47%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.47%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 7         | 0.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 291       | 19.72%  |
| Intel Core i5                  | 282       | 19.11%  |
| Intel Core i3                  | 164       | 11.11%  |
| Intel Celeron                  | 128       | 8.67%   |
| Intel Core 2 Duo               | 78        | 5.28%   |
| AMD Ryzen 5                    | 73        | 4.95%   |
| Other                          | 62        | 4.2%    |
| AMD Ryzen 7                    | 59        | 4%      |
| Intel Pentium                  | 50        | 3.39%   |
| Intel Atom                     | 26        | 1.76%   |
| Intel Xeon                     | 20        | 1.36%   |
| Intel Pentium Dual-Core        | 20        | 1.36%   |
| AMD Ryzen 3                    | 20        | 1.36%   |
| Intel Core 2 Quad              | 16        | 1.08%   |
| AMD A4                         | 15        | 1.02%   |
| Intel Core 2                   | 13        | 0.88%   |
| AMD Ryzen 9                    | 13        | 0.88%   |
| AMD FX                         | 11        | 0.75%   |
| AMD A8                         | 11        | 0.75%   |
| Intel Core i9                  | 10        | 0.68%   |
| Intel Genuine                  | 9         | 0.61%   |
| Intel Pentium Dual             | 8         | 0.54%   |
| AMD Phenom II X4               | 7         | 0.47%   |
| AMD E                          | 6         | 0.41%   |
| AMD Athlon                     | 6         | 0.41%   |
| AMD Ryzen Threadripper         | 5         | 0.34%   |
| AMD E2                         | 5         | 0.34%   |
| Intel Celeron M                | 4         | 0.27%   |
| ARM BCM                        | 4         | 0.27%   |
| AMD Sempron                    | 4         | 0.27%   |
| AMD Ryzen 7 PRO                | 4         | 0.27%   |
| AMD Athlon II X4               | 3         | 0.2%    |
| Intel Pentium Silver           | 2         | 0.14%   |
| Intel Pentium Gold             | 2         | 0.14%   |
| Intel Pentium D                | 2         | 0.14%   |
| Intel Pentium 4                | 2         | 0.14%   |
| Intel Core Duo                 | 2         | 0.14%   |
| Intel Core 2 Extreme           | 2         | 0.14%   |
| AMD V140                       | 2         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 680       | 46.1%   |
| 4      | 518       | 35.12%  |
| 6      | 114       | 7.73%   |
| 8      | 90        | 6.1%    |
| 1      | 38        | 2.58%   |
| 12     | 12        | 0.81%   |
| 3      | 9         | 0.61%   |
| 32     | 3         | 0.2%    |
| 16     | 3         | 0.2%    |
| 10     | 3         | 0.2%    |
| 24     | 2         | 0.14%   |
| 64     | 1         | 0.07%   |
| 20     | 1         | 0.07%   |
| 14     | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1465      | 99.32%  |
| 2      | 10        | 0.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 933       | 63.21%  |
| 1      | 543       | 36.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1381      | 93.25%  |
| Unknown        | 87        | 5.87%   |
| 32-bit         | 13        | 0.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 262       | 17.34%  |
| 0x206a7    | 80        | 5.29%   |
| 0x306c3    | 76        | 5.03%   |
| 0x306a9    | 71        | 4.7%    |
| 0x1067a    | 59        | 3.9%    |
| 0x906ea    | 55        | 3.64%   |
| 0x806ea    | 55        | 3.64%   |
| 0x806ec    | 52        | 3.44%   |
| 0x706a1    | 47        | 3.11%   |
| 0x906e9    | 39        | 2.58%   |
| 0x40651    | 36        | 2.38%   |
| 0x506c9    | 34        | 2.25%   |
| 0x506e3    | 32        | 2.12%   |
| 0x20655    | 30        | 1.99%   |
| 0x806e9    | 26        | 1.72%   |
| 0x306d4    | 26        | 1.72%   |
| 0x806c1    | 25        | 1.65%   |
| 0x10676    | 25        | 1.65%   |
| 0x806eb    | 22        | 1.46%   |
| 0x406e3    | 22        | 1.46%   |
| 0x6fd      | 19        | 1.26%   |
| 0x706e5    | 17        | 1.13%   |
| 0x010000c8 | 17        | 1.13%   |
| 0x406c4    | 16        | 1.06%   |
| 0x0a50000c | 16        | 1.06%   |
| 0x08108102 | 16        | 1.06%   |
| 0x08108109 | 15        | 0.99%   |
| 0xa0652    | 13        | 0.86%   |
| 0x6fb      | 12        | 0.79%   |
| 0x0810100b | 12        | 0.79%   |
| 0x906ed    | 11        | 0.73%   |
| 0x06001119 | 11        | 0.73%   |
| 0x08701013 | 10        | 0.66%   |
| 0x08600104 | 10        | 0.66%   |
| 0x0800820d | 10        | 0.66%   |
| 0x406c3    | 9         | 0.6%    |
| 0x30678    | 9         | 0.6%    |
| 0x08701021 | 9         | 0.6%    |
| 0x806d1    | 8         | 0.53%   |
| 0x706a8    | 7         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 303       | 20.51%  |
| Haswell          | 137       | 9.28%   |
| SandyBridge      | 90        | 6.09%   |
| Penryn           | 90        | 6.09%   |
| IvyBridge        | 82        | 5.55%   |
| Skylake          | 65        | 4.4%    |
| Goldmont plus    | 61        | 4.13%   |
| Core             | 58        | 3.93%   |
| Zen+             | 56        | 3.79%   |
| Zen 2            | 49        | 3.32%   |
| Westmere         | 47        | 3.18%   |
| Silvermont       | 40        | 2.71%   |
| Goldmont         | 39        | 2.64%   |
| Zen              | 37        | 2.51%   |
| Broadwell        | 37        | 2.51%   |
| Zen 3            | 32        | 2.17%   |
| TigerLake        | 32        | 2.17%   |
| IceLake          | 27        | 1.83%   |
| Unknown          | 27        | 1.83%   |
| K10              | 26        | 1.76%   |
| CometLake        | 26        | 1.76%   |
| Piledriver       | 24        | 1.62%   |
| Excavator        | 14        | 0.95%   |
| P6               | 11        | 0.74%   |
| Nehalem          | 10        | 0.68%   |
| K8 Hammer        | 10        | 0.68%   |
| Bonnell          | 10        | 0.68%   |
| Bobcat           | 8         | 0.54%   |
| Puma             | 6         | 0.41%   |
| NetBurst         | 6         | 0.41%   |
| K10 Llano        | 4         | 0.27%   |
| K8 & K10 hybrid  | 3         | 0.2%    |
| Alderlake Hybrid | 3         | 0.2%    |
| Tremont          | 2         | 0.14%   |
| Steamroller      | 2         | 0.14%   |
| Jaguar           | 2         | 0.14%   |
| Bulldozer        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 959       | 52.87%  |
| Nvidia                           | 489       | 26.96%  |
| AMD                              | 354       | 19.51%  |
| Silicon Integrated Systems [SiS] | 4         | 0.22%   |
| ASPEED Technology                | 4         | 0.22%   |
| Matrox Electronics Systems       | 3         | 0.17%   |
| VIA Technologies                 | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 72        | 3.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 60        | 3.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 59        | 3.17%   |
| Intel UHD Graphics 620                                                                   | 51        | 2.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 48        | 2.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 46        | 2.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 2.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 40        | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 38        | 2.04%   |
| Intel HD Graphics 5500                                                                   | 34        | 1.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 34        | 1.83%   |
| Intel HD Graphics 630                                                                    | 31        | 1.66%   |
| Intel HD Graphics 620                                                                    | 31        | 1.66%   |
| Intel HD Graphics 500                                                                    | 28        | 1.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 28        | 1.5%    |
| Intel HD Graphics 530                                                                    | 26        | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 1.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 1.24%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 1.18%   |
| AMD Renoir                                                                               | 22        | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 22        | 1.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 21        | 1.13%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 20        | 1.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 20        | 1.07%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 1.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 1.02%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 17        | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 16        | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 16        | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.81%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 15        | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 15        | 0.81%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 14        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 14        | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 13        | 0.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 13        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 646       | 43.68%  |
| 1 x AMD        | 253       | 17.11%  |
| Intel + Nvidia | 249       | 16.84%  |
| 1 x Nvidia     | 210       | 14.2%   |
| Intel + AMD    | 53        | 3.58%   |
| AMD + Nvidia   | 29        | 1.96%   |
| 2 x AMD        | 18        | 1.22%   |
| Other          | 8         | 0.54%   |
| 1 x SiS        | 4         | 0.27%   |
| 1 x Matrox     | 3         | 0.2%    |
| 1 x ASPEED     | 3         | 0.2%    |
| 2 x Nvidia     | 1         | 0.07%   |
| 1 x VIA        | 1         | 0.07%   |
| AMD + ASPEED   | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1171      | 78.75%  |
| Proprietary | 274       | 18.43%  |
| Unknown     | 42        | 2.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 832       | 54.99%  |
| 1.01-2.0   | 214       | 14.14%  |
| 0.01-0.5   | 156       | 10.31%  |
| 3.01-4.0   | 119       | 7.87%   |
| 0.51-1.0   | 105       | 6.94%   |
| 7.01-8.0   | 43        | 2.84%   |
| 5.01-6.0   | 30        | 1.98%   |
| 2.01-3.0   | 8         | 0.53%   |
| 8.01-16.0  | 5         | 0.33%   |
| 16.01-24.0 | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 211       | 13.53%  |
| Samsung Electronics     | 185       | 11.87%  |
| LG Display              | 165       | 10.58%  |
| Chimei Innolux          | 165       | 10.58%  |
| BOE                     | 161       | 10.33%  |
| Dell                    | 103       | 6.61%   |
| Goldstar                | 68        | 4.36%   |
| Philips                 | 60        | 3.85%   |
| PANDA                   | 39        | 2.5%    |
| BenQ                    | 35        | 2.25%   |
| Chi Mei Optoelectronics | 31        | 1.99%   |
| Lenovo                  | 28        | 1.8%    |
| Sharp                   | 27        | 1.73%   |
| Acer                    | 27        | 1.73%   |
| Hewlett-Packard         | 26        | 1.67%   |
| AOC                     | 25        | 1.6%    |
| Ancor Communications    | 21        | 1.35%   |
| Fujitsu Siemens         | 18        | 1.15%   |
| ASUSTek Computer        | 13        | 0.83%   |
| LG Philips              | 11        | 0.71%   |
| LG Electronics          | 10        | 0.64%   |
| Apple                   | 10        | 0.64%   |
| Unknown                 | 9         | 0.58%   |
| KTC                     | 7         | 0.45%   |
| Vestel Elektronik       | 6         | 0.38%   |
| Sony                    | 6         | 0.38%   |
| Lenovo Group Limited    | 6         | 0.38%   |
| Eizo                    | 6         | 0.38%   |
| Toshiba                 | 5         | 0.32%   |
| Panasonic               | 5         | 0.32%   |
| InfoVision              | 5         | 0.32%   |
| CSO                     | 5         | 0.32%   |
| LGD                     | 4         | 0.26%   |
| Iiyama                  | 4         | 0.26%   |
| ViewSonic               | 3         | 0.19%   |
| HannStar                | 3         | 0.19%   |
| CPT                     | 3         | 0.19%   |
| Belinea                 | 3         | 0.19%   |
| Analogix                | 3         | 0.19%   |
| NAD                     | 2         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 26        | 1.63%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 21        | 1.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 17        | 1.07%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 17        | 1.07%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 15        | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 0.75%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 12        | 0.75%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.69%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 10        | 0.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 9         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 9         | 0.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 8         | 0.5%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 8         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 8         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 8         | 0.5%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 8         | 0.5%    |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                  | 7         | 0.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.44%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 7         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 7         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 7         | 0.44%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 6         | 0.38%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 6         | 0.38%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 6         | 0.38%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 6         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 6         | 0.38%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                    | 6         | 0.38%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                    | 6         | 0.38%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.38%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 5         | 0.31%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch                  | 5         | 0.31%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 5         | 0.31%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 5         | 0.31%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 5         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.31%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 5         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 682       | 45.44%  |
| 1366x768 (WXGA)    | 342       | 22.78%  |
| 1280x1024 (SXGA)   | 69        | 4.6%    |
| 3840x2160 (4K)     | 63        | 4.2%    |
| 1600x900 (HD+)     | 53        | 3.53%   |
| 2560x1440 (QHD)    | 42        | 2.8%    |
| 1680x1050 (WSXGA+) | 39        | 2.6%    |
| 1280x800 (WXGA)    | 34        | 2.27%   |
| 1440x900 (WXGA+)   | 27        | 1.8%    |
| 1920x1200 (WUXGA)  | 23        | 1.53%   |
| Unknown            | 15        | 1%      |
| 1360x768           | 13        | 0.87%   |
| 3200x1800 (QHD+)   | 11        | 0.73%   |
| 2560x1080          | 10        | 0.67%   |
| 3440x1440          | 9         | 0.6%    |
| 2880x1800          | 9         | 0.6%    |
| 1024x600           | 7         | 0.47%   |
| 3840x1080          | 6         | 0.4%    |
| 1024x768 (XGA)     | 6         | 0.4%    |
| 2160x1440          | 5         | 0.33%   |
| 800x1280           | 4         | 0.27%   |
| 2560x1600          | 4         | 0.27%   |
| 5120x1440          | 2         | 0.13%   |
| 3840x2400          | 2         | 0.13%   |
| 1600x1200          | 2         | 0.13%   |
| 1400x1050          | 2         | 0.13%   |
| 1280x720 (HD)      | 2         | 0.13%   |
| 800x600            | 1         | 0.07%   |
| 7680x1440          | 1         | 0.07%   |
| 6400x1440          | 1         | 0.07%   |
| 6000x1440          | 1         | 0.07%   |
| 3926x1440          | 1         | 0.07%   |
| 3840x1600          | 1         | 0.07%   |
| 3600x1200          | 1         | 0.07%   |
| 3286x1080          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2960x1050          | 1         | 0.07%   |
| 2720x1024          | 1         | 0.07%   |
| 2624x1200          | 1         | 0.07%   |
| 2288x1287          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 610       | 39.51%  |
| 14      | 114       | 7.38%   |
| 13      | 102       | 6.61%   |
| 17      | 94        | 6.09%   |
| 24      | 93        | 6.02%   |
| 23      | 82        | 5.31%   |
| 21      | 82        | 5.31%   |
| Unknown | 71        | 4.6%    |
| 27      | 64        | 4.15%   |
| 19      | 45        | 2.91%   |
| 22      | 26        | 1.68%   |
| 18      | 26        | 1.68%   |
| 34      | 17        | 1.1%    |
| 31      | 17        | 1.1%    |
| 12      | 15        | 0.97%   |
| 84      | 14        | 0.91%   |
| 20      | 11        | 0.71%   |
| 10      | 8         | 0.52%   |
| 54      | 7         | 0.45%   |
| 72      | 6         | 0.39%   |
| 32      | 5         | 0.32%   |
| 16      | 5         | 0.32%   |
| 65      | 4         | 0.26%   |
| 11      | 4         | 0.26%   |
| 40      | 3         | 0.19%   |
| 26      | 3         | 0.19%   |
| 52      | 2         | 0.13%   |
| 28      | 2         | 0.13%   |
| 25      | 2         | 0.13%   |
| 8       | 2         | 0.13%   |
| 142     | 1         | 0.06%   |
| 49      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 47      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 43      | 1         | 0.06%   |
| 42      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 796       | 52.09%  |
| 501-600        | 225       | 14.73%  |
| 401-500        | 153       | 10.01%  |
| 351-400        | 117       | 7.66%   |
| 201-300        | 73        | 4.78%   |
| Unknown        | 71        | 4.65%   |
| 601-700        | 25        | 1.64%   |
| 701-800        | 22        | 1.44%   |
| 1501-2000      | 20        | 1.31%   |
| 1001-1500      | 17        | 1.11%   |
| 801-900        | 4         | 0.26%   |
| 101-200        | 2         | 0.13%   |
| 901-1000       | 2         | 0.13%   |
| More than 2000 | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1133      | 78.63%  |
| 16/10   | 137       | 9.51%   |
| 5/4     | 60        | 4.16%   |
| Unknown | 58        | 4.02%   |
| 21/9    | 20        | 1.39%   |
| 4/3     | 13        | 0.9%    |
| 3/2     | 9         | 0.62%   |
| 6/5     | 5         | 0.35%   |
| 0.62    | 4         | 0.28%   |
| 32/9    | 1         | 0.07%   |
| 1.00    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 610       | 39.77%  |
| 201-250        | 227       | 14.8%   |
| 81-90          | 180       | 11.73%  |
| 151-200        | 85        | 5.54%   |
| Unknown        | 71        | 4.63%   |
| 301-350        | 67        | 4.37%   |
| 121-130        | 60        | 3.91%   |
| 141-150        | 46        | 3%      |
| 351-500        | 38        | 2.48%   |
| More than 1000 | 35        | 2.28%   |
| 71-80          | 34        | 2.22%   |
| 251-300        | 29        | 1.89%   |
| 61-70          | 13        | 0.85%   |
| 131-140        | 9         | 0.59%   |
| 501-1000       | 9         | 0.59%   |
| 41-50          | 8         | 0.52%   |
| 51-60          | 4         | 0.26%   |
| 91-100         | 4         | 0.26%   |
| 111-120        | 3         | 0.2%    |
| 1-40           | 2         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 459       | 30.3%   |
| 121-160       | 450       | 29.7%   |
| 51-100        | 424       | 27.99%  |
| Unknown       | 71        | 4.69%   |
| 161-240       | 56        | 3.7%    |
| More than 240 | 29        | 1.91%   |
| 1-50          | 26        | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1282      | 85.3%   |
| 2     | 151       | 10.05%  |
| 0     | 50        | 3.33%   |
| 3     | 19        | 1.26%   |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 836       | 38.9%   |
| Intel                             | 642       | 29.87%  |
| Qualcomm Atheros                  | 258       | 12.01%  |
| Broadcom                          | 125       | 5.82%   |
| TP-Link                           | 45        | 2.09%   |
| MediaTek                          | 31        | 1.44%   |
| Ralink                            | 22        | 1.02%   |
| Broadcom Limited                  | 22        | 1.02%   |
| Marvell Technology Group          | 21        | 0.98%   |
| Ralink Technology                 | 18        | 0.84%   |
| Nvidia                            | 12        | 0.56%   |
| ASUSTek Computer                  | 11        | 0.51%   |
| Huawei Technologies               | 8         | 0.37%   |
| Samsung Electronics               | 7         | 0.33%   |
| D-Link                            | 7         | 0.33%   |
| Xiaomi                            | 6         | 0.28%   |
| Ericsson Business Mobile Networks | 6         | 0.28%   |
| Qualcomm Atheros Communications   | 5         | 0.23%   |
| Microsoft                         | 5         | 0.23%   |
| Hewlett-Packard                   | 5         | 0.23%   |
| ASIX Electronics                  | 5         | 0.23%   |
| Aquantia                          | 5         | 0.23%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.19%   |
| JMicron Technology                | 4         | 0.19%   |
| VIA Technologies                  | 3         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.14%   |
| Standard Microsystems             | 2         | 0.09%   |
| Lenovo                            | 2         | 0.09%   |
| IMC Networks                      | 2         | 0.09%   |
| Giga-Byte Technology              | 2         | 0.09%   |
| Fibocom                           | 2         | 0.09%   |
| Edimax Technology                 | 2         | 0.09%   |
| Dell                              | 2         | 0.09%   |
| D-Link System                     | 2         | 0.09%   |
| Belkin Components                 | 2         | 0.09%   |
| U-Blox                            | 1         | 0.05%   |
| Sierra Wireless                   | 1         | 0.05%   |
| QLogic                            | 1         | 0.05%   |
| Qcom                              | 1         | 0.05%   |
| NetGear                           | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 548       | 21.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 113       | 4.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 69        | 2.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 52        | 2.08%   |
| Intel Wireless 8265 / 8275                                        | 52        | 2.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 51        | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 51        | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 44        | 1.76%   |
| Intel Wi-Fi 6 AX200                                               | 40        | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 38        | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 35        | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 33        | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 32        | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 28        | 1.12%   |
| Intel I211 Gigabit Network Connection                             | 28        | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 26        | 1.04%   |
| Intel Wi-Fi 6 AX201                                               | 25        | 1%      |
| Intel Wireless 7260                                               | 24        | 0.96%   |
| Intel Wireless 7265                                               | 23        | 0.92%   |
| Intel Ethernet Connection I217-LM                                 | 23        | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 20        | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 19        | 0.76%   |
| Intel Wireless 8260                                               | 19        | 0.76%   |
| Intel Wireless 3165                                               | 19        | 0.76%   |
| Intel Wireless 3160                                               | 19        | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 0.72%   |
| Broadcom BCM43142 802.11b/g/n                                     | 18        | 0.72%   |
| Intel Ethernet Connection (2) I219-V                              | 17        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 16        | 0.64%   |
| Intel Centrino Advanced-N 6200                                    | 16        | 0.64%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 15        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 15        | 0.6%    |
| Intel 82577LM Gigabit Network Connection                          | 15        | 0.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 15        | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 13        | 0.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 13        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 13        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 486       | 41.4%   |
| Realtek Semiconductor           | 243       | 20.7%   |
| Qualcomm Atheros                | 207       | 17.63%  |
| Broadcom                        | 81        | 6.9%    |
| TP-Link                         | 38        | 3.24%   |
| MediaTek                        | 26        | 2.21%   |
| Ralink                          | 22        | 1.87%   |
| Ralink Technology               | 18        | 1.53%   |
| Broadcom Limited                | 12        | 1.02%   |
| ASUSTek Computer                | 11        | 0.94%   |
| Qualcomm Atheros Communications | 5         | 0.43%   |
| Microsoft                       | 5         | 0.43%   |
| D-Link                          | 5         | 0.43%   |
| IMC Networks                    | 2         | 0.17%   |
| Fibocom                         | 2         | 0.17%   |
| Edimax Technology               | 2         | 0.17%   |
| Belkin Components               | 2         | 0.17%   |
| Sierra Wireless                 | 1         | 0.09%   |
| Qcom                            | 1         | 0.09%   |
| NetGear                         | 1         | 0.09%   |
| Micro Star International        | 1         | 0.09%   |
| Mercucys                        | 1         | 0.09%   |
| D-Link System                   | 1         | 0.09%   |
| Belkin                          | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 69        | 5.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 52        | 4.41%   |
| Intel Wireless 8265 / 8275                                              | 52        | 4.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 51        | 4.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 44        | 3.73%   |
| Intel Wi-Fi 6 AX200                                                     | 40        | 3.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 38        | 3.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 35        | 2.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 33        | 2.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 32        | 2.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 28        | 2.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 26        | 2.21%   |
| Intel Wi-Fi 6 AX201                                                     | 25        | 2.12%   |
| Intel Wireless 7260                                                     | 24        | 2.04%   |
| Intel Wireless 7265                                                     | 23        | 1.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 20        | 1.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 19        | 1.61%   |
| Intel Wireless 8260                                                     | 19        | 1.61%   |
| Intel Wireless 3165                                                     | 19        | 1.61%   |
| Intel Wireless 3160                                                     | 19        | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 1.53%   |
| Broadcom BCM43142 802.11b/g/n                                           | 18        | 1.53%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 1.36%   |
| Intel Centrino Advanced-N 6200                                          | 16        | 1.36%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 15        | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 1.1%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 9         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                         | 9         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 9         | 0.76%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 0.59%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 7         | 0.59%   |
| Intel Centrino Advanced-N 6235                                          | 7         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 713       | 55.79%  |
| Intel                            | 313       | 24.49%  |
| Qualcomm Atheros                 | 79        | 6.18%   |
| Broadcom                         | 64        | 5.01%   |
| Marvell Technology Group         | 21        | 1.64%   |
| Nvidia                           | 12        | 0.94%   |
| Broadcom Limited                 | 10        | 0.78%   |
| TP-Link                          | 7         | 0.55%   |
| Samsung Electronics              | 7         | 0.55%   |
| Xiaomi                           | 6         | 0.47%   |
| Huawei Technologies              | 6         | 0.47%   |
| MediaTek                         | 5         | 0.39%   |
| ASIX Electronics                 | 5         | 0.39%   |
| Aquantia                         | 5         | 0.39%   |
| JMicron Technology               | 4         | 0.31%   |
| VIA Technologies                 | 3         | 0.23%   |
| Silicon Integrated Systems [SiS] | 3         | 0.23%   |
| Standard Microsystems            | 2         | 0.16%   |
| Lenovo                           | 2         | 0.16%   |
| Giga-Byte Technology             | 2         | 0.16%   |
| D-Link                           | 2         | 0.16%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.08%   |
| QLogic                           | 1         | 0.08%   |
| HMD Global                       | 1         | 0.08%   |
| Google                           | 1         | 0.08%   |
| DisplayLink                      | 1         | 0.08%   |
| D-Link System                    | 1         | 0.08%   |
| 3Com                             | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 548       | 42.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 113       | 8.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 51        | 3.94%   |
| Intel I211 Gigabit Network Connection                             | 28        | 2.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 2.01%   |
| Intel Ethernet Connection I217-LM                                 | 23        | 1.77%   |
| Intel Ethernet Connection (2) I219-V                              | 17        | 1.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 1.16%   |
| Intel 82577LM Gigabit Network Connection                          | 15        | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 1.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 13        | 1%      |
| Intel Ethernet Connection (7) I219-V                              | 12        | 0.93%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.62%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.62%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 8         | 0.62%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8         | 0.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.54%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.54%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.54%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 7         | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 6         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.46%   |
| Nvidia MCP61 Ethernet                                             | 6         | 0.46%   |
| Intel I210 Gigabit Network Connection                             | 6         | 0.46%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 0.46%   |
| Huawei SNE-LX1                                                    | 6         | 0.46%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 6         | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.39%   |
| MediaTek N152DL                                                   | 5         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1211      | 51.21%  |
| WiFi     | 1128      | 47.7%   |
| Modem    | 20        | 0.85%   |
| Unknown  | 6         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 911       | 59.58%  |
| Ethernet | 616       | 40.29%  |
| Unknown  | 2         | 0.13%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 793       | 53.69%  |
| 1     | 624       | 42.25%  |
| 0     | 32        | 2.17%   |
| 3     | 24        | 1.62%   |
| 4     | 3         | 0.2%    |
| 6     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1305      | 86.88%  |
| Yes  | 197       | 13.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 379       | 42.02%  |
| IMC Networks                    | 126       | 13.97%  |
| Realtek Semiconductor           | 103       | 11.42%  |
| Qualcomm Atheros Communications | 66        | 7.32%   |
| Lite-On Technology              | 43        | 4.77%   |
| Broadcom                        | 38        | 4.21%   |
| Cambridge Silicon Radio         | 27        | 2.99%   |
| ASUSTek Computer                | 22        | 2.44%   |
| Foxconn / Hon Hai               | 18        | 2%      |
| Dell                            | 17        | 1.88%   |
| Hewlett-Packard                 | 13        | 1.44%   |
| Toshiba                         | 10        | 1.11%   |
| Apple                           | 10        | 1.11%   |
| Ralink                          | 9         | 1%      |
| Realtek                         | 3         | 0.33%   |
| MediaTek                        | 3         | 0.33%   |
| Alps Electric                   | 3         | 0.33%   |
| Integrated System Solution      | 2         | 0.22%   |
| Chicony Electronics             | 2         | 0.22%   |
| Unknown                         | 1         | 0.11%   |
| SINO WEALTH                     | 1         | 0.11%   |
| Ralink Technology               | 1         | 0.11%   |
| Opticis                         | 1         | 0.11%   |
| Micro Star International        | 1         | 0.11%   |
| Foxconn International           | 1         | 0.11%   |
| Conwise Technology              | 1         | 0.11%   |
| Askey Computer                  | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 161       | 17.85%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 81        | 8.98%   |
| IMC Networks Bluetooth Radio                        | 80        | 8.87%   |
| Realtek Bluetooth Radio                             | 77        | 8.54%   |
| Intel AX201 Bluetooth                               | 62        | 6.87%   |
| Intel AX200 Bluetooth                               | 39        | 4.32%   |
| Qualcomm Atheros  Bluetooth Device                  | 38        | 4.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 27        | 2.99%   |
| IMC Networks Bluetooth Device                       | 25        | 2.77%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 21        | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 2%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 17        | 1.88%   |
| IMC Networks Wireless_Device                        | 15        | 1.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 1.22%   |
| Ralink RT3290 Bluetooth                             | 9         | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1%      |
| Lite-On Bluetooth Device                            | 8         | 0.89%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.89%   |
| Dell DW375 Bluetooth Module                         | 8         | 0.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 0.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 0.78%   |
| Broadcom BCM2045A0                                  | 7         | 0.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 0.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 0.67%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 5         | 0.55%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 0.55%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.55%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.55%   |
| Toshiba Bluetooth Device                            | 4         | 0.44%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.44%   |
| Realtek RTL8723B Bluetooth                          | 4         | 0.44%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.44%   |
| Intel AX210 Bluetooth                               | 4         | 0.44%   |
| Realtek Bluetooth Radio                             | 3         | 0.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.33%   |
| MediaTek Wireless_Device                            | 3         | 0.33%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 0.33%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 3         | 0.33%   |
| Dell Wireless 365 Bluetooth                         | 3         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1141      | 59.06%  |
| AMD                                          | 330       | 17.08%  |
| Nvidia                                       | 307       | 15.89%  |
| C-Media Electronics                          | 30        | 1.55%   |
| Creative Labs                                | 20        | 1.04%   |
| Logitech                                     | 11        | 0.57%   |
| GN Netcom                                    | 9         | 0.47%   |
| Creative Technology                          | 7         | 0.36%   |
| Kingston Technology                          | 5         | 0.26%   |
| Giga-Byte Technology                         | 5         | 0.26%   |
| Trust                                        | 4         | 0.21%   |
| Texas Instruments                            | 4         | 0.21%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.21%   |
| Realtek Semiconductor                        | 4         | 0.21%   |
| VIA Technologies                             | 3         | 0.16%   |
| Sennheiser Communications                    | 3         | 0.16%   |
| Plantronics                                  | 3         | 0.16%   |
| ASUSTek Computer                             | 3         | 0.16%   |
| XMOS                                         | 2         | 0.1%    |
| Tenx Technology                              | 2         | 0.1%    |
| Lenovo                                       | 2         | 0.1%    |
| GYROCOM C&C                                  | 2         | 0.1%    |
| Generalplus Technology                       | 2         | 0.1%    |
| DSEA A/S                                     | 2         | 0.1%    |
| Dell                                         | 2         | 0.1%    |
| Audio-Technica                               | 2         | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.05%   |
| Unknown                                      | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.05%   |
| TEAC                                         | 1         | 0.05%   |
| Studiologic                                  | 1         | 0.05%   |
| Sony                                         | 1         | 0.05%   |
| Samson Technologies                          | 1         | 0.05%   |
| Razer USA                                    | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)                | 1         | 0.05%   |
| Nam Tai E&E Products                         | 1         | 0.05%   |
| JMTek                                        | 1         | 0.05%   |
| iCreate Technologies                         | 1         | 0.05%   |
| Holtek Semiconductor                         | 1         | 0.05%   |
| Hewlett-Packard                              | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 115       | 5.03%   |
| Intel Sunrise Point-LP HD Audio                                            | 114       | 4.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 86        | 3.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 81        | 3.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 78        | 3.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 72        | 3.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 66        | 2.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 63        | 2.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 61        | 2.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 53        | 2.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 53        | 2.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 52        | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 49        | 2.14%   |
| Intel Haswell-ULT HD Audio Controller                                      | 48        | 2.1%    |
| Intel 8 Series HD Audio Controller                                         | 47        | 2.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 46        | 2.01%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 45        | 1.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 41        | 1.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 39        | 1.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 38        | 1.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 35        | 1.53%   |
| Intel Broadwell-U Audio Controller                                         | 35        | 1.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 32        | 1.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 32        | 1.4%    |
| AMD Starship/Matisse HD Audio Controller                                   | 32        | 1.4%    |
| AMD FCH Azalia Controller                                                  | 31        | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                              | 30        | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 30        | 1.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 28        | 1.22%   |
| Intel 200 Series PCH HD Audio                                              | 27        | 1.18%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 26        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 23        | 1.01%   |
| Intel Comet Lake PCH-LP cAVS                                               | 22        | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 19        | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 19        | 0.83%   |
| Intel Comet Lake PCH cAVS                                                  | 19        | 0.83%   |
| Intel CM238 HD Audio Controller                                            | 18        | 0.79%   |
| Nvidia High Definition Audio Controller                                    | 17        | 0.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 17        | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                              | 16        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 168       | 21.68%  |
| SK hynix                     | 137       | 17.68%  |
| Kingston                     | 118       | 15.23%  |
| Micron Technology            | 74        | 9.55%   |
| Unknown                      | 70        | 9.03%   |
| Corsair                      | 58        | 7.48%   |
| Ramaxel Technology           | 24        | 3.1%    |
| Crucial                      | 21        | 2.71%   |
| A-DATA Technology            | 20        | 2.58%   |
| Nanya Technology             | 17        | 2.19%   |
| Elpida                       | 16        | 2.06%   |
| G.Skill                      | 9         | 1.16%   |
| Kingmax                      | 8         | 1.03%   |
| Unknown (ABCD)               | 7         | 0.9%    |
| Unknown                      | 5         | 0.65%   |
| Patriot                      | 4         | 0.52%   |
| Transcend                    | 2         | 0.26%   |
| Qimonda                      | 2         | 0.26%   |
| GOODRAM                      | 2         | 0.26%   |
| Apacer                       | 2         | 0.26%   |
| Unknown (0x7FDA000000000000) | 1         | 0.13%   |
| Unknown (0B45)               | 1         | 0.13%   |
| TakeMS                       | 1         | 0.13%   |
| Silicon Power                | 1         | 0.13%   |
| SHARETRONIC                  | 1         | 0.13%   |
| S                            | 1         | 0.13%   |
| Kingmax Semiconductor        | 1         | 0.13%   |
| H                            | 1         | 0.13%   |
| Exceleram                    | 1         | 0.13%   |
| Avant                        | 1         | 0.13%   |
| ASint Technology             | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 1.17%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 10        | 1.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1.05%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 1.05%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.93%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.82%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 7         | 0.82%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 6         | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.7%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.7%    |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 5         | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.58%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.58%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.58%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.58%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                | 5         | 0.58%   |
| Unknown                                                          | 5         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 4         | 0.47%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.47%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.47%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.47%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s          | 4         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 3         | 0.35%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 3         | 0.35%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 800MT/s          | 3         | 0.35%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 3         | 0.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.35%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.35%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.35%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.35%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.35%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.35%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 3         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 305       | 45.86%  |
| DDR3    | 231       | 34.74%  |
| DDR2    | 49        | 7.37%   |
| SDRAM   | 26        | 3.91%   |
| Unknown | 20        | 3.01%   |
| LPDDR4  | 15        | 2.26%   |
| LPDDR3  | 11        | 1.65%   |
| DDR     | 4         | 0.6%    |
| DDR5    | 2         | 0.3%    |
| LPDDR5  | 1         | 0.15%   |
| DRAM    | 1         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 399       | 61.38%  |
| DIMM         | 221       | 34%     |
| Row Of Chips | 25        | 3.85%   |
| Chip         | 3         | 0.46%   |
| RIMM         | 1         | 0.15%   |
| FB-DIMM      | 1         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 248       | 34.78%  |
| 4096  | 214       | 30.01%  |
| 2048  | 103       | 14.45%  |
| 16384 | 87        | 12.2%   |
| 1024  | 46        | 6.45%   |
| 32768 | 11        | 1.54%   |
| 512   | 4         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 148       | 20.05%  |
| 2667    | 118       | 15.99%  |
| 3200    | 89        | 12.06%  |
| 2400    | 71        | 9.62%   |
| 1333    | 52        | 7.05%   |
| 1334    | 36        | 4.88%   |
| 2133    | 28        | 3.79%   |
| 800     | 28        | 3.79%   |
| 667     | 25        | 3.39%   |
| Unknown | 16        | 2.17%   |
| 3600    | 13        | 1.76%   |
| 3266    | 10        | 1.36%   |
| 3400    | 8         | 1.08%   |
| 1067    | 8         | 1.08%   |
| 975     | 8         | 1.08%   |
| 4267    | 6         | 0.81%   |
| 1867    | 6         | 0.81%   |
| 3000    | 5         | 0.68%   |
| 1066    | 5         | 0.68%   |
| 533     | 5         | 0.68%   |
| 2933    | 4         | 0.54%   |
| 2048    | 4         | 0.54%   |
| 4800    | 3         | 0.41%   |
| 4199    | 3         | 0.41%   |
| 3866    | 3         | 0.41%   |
| 2800    | 3         | 0.41%   |
| 2666    | 3         | 0.41%   |
| 1866    | 3         | 0.41%   |
| 4266    | 2         | 0.27%   |
| 3733    | 2         | 0.27%   |
| 3500    | 2         | 0.27%   |
| 3466    | 2         | 0.27%   |
| 1800    | 2         | 0.27%   |
| 1639    | 2         | 0.27%   |
| 400     | 2         | 0.27%   |
| 49926   | 1         | 0.14%   |
| 8192    | 1         | 0.14%   |
| 6400    | 1         | 0.14%   |
| 3334    | 1         | 0.14%   |
| 3151    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 12        | 25%     |
| Canon                 | 9         | 18.75%  |
| Brother Industries    | 8         | 16.67%  |
| Samsung Electronics   | 7         | 14.58%  |
| Seiko Epson           | 6         | 12.5%   |
| Xerox                 | 2         | 4.17%   |
| Zebra                 | 1         | 2.08%   |
| QinHeng Electronics   | 1         | 2.08%   |
| Lexmark International | 1         | 2.08%   |
| ATEN International    | 1         | 2.08%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                      | 2         | 4.17%   |
| Samsung M2070 Series                          | 2         | 4.17%   |
| Samsung Composite Device                      | 2         | 4.17%   |
| Canon MF4010 series                           | 2         | 4.17%   |
| Brother HL-1110 series                        | 2         | 4.17%   |
| Zebra GK420t Label Printer                    | 1         | 2.08%   |
| Xerox Phaser 6130N                            | 1         | 2.08%   |
| Xerox Phaser 3020                             | 1         | 2.08%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 2.08%   |
| Seiko Epson L3150 Series                      | 1         | 2.08%   |
| Seiko Epson ET-3750 Series                    | 1         | 2.08%   |
| Seiko Epson ET-2600 Series                    | 1         | 2.08%   |
| Samsung ML-216x Series Laser Printer          | 1         | 2.08%   |
| Samsung M2020 Series                          | 1         | 2.08%   |
| Samsung CLP-310 Color Laser Printer           | 1         | 2.08%   |
| QinHeng CH340S                                | 1         | 2.08%   |
| Lexmark International InkJet Color Printer    | 1         | 2.08%   |
| HP LaserJet M14-M17                           | 1         | 2.08%   |
| HP LaserJet 3050                              | 1         | 2.08%   |
| HP LaserJet 1022                              | 1         | 2.08%   |
| HP LaserJet 1018                              | 1         | 2.08%   |
| HP Laser 107a                                 | 1         | 2.08%   |
| HP Deskjet F4500 series                       | 1         | 2.08%   |
| HP DeskJet F2492 All-in-One                   | 1         | 2.08%   |
| HP Deskjet 3050A                              | 1         | 2.08%   |
| HP DeskJet 2700 series                        | 1         | 2.08%   |
| HP DeskJet 2300 series                        | 1         | 2.08%   |
| HP DeskJet 2130 series                        | 1         | 2.08%   |
| HP Deskjet 2050 J510                          | 1         | 2.08%   |
| Canon PIXMA MP280                             | 1         | 2.08%   |
| Canon PIXMA MP250                             | 1         | 2.08%   |
| Canon MF4320-4350                             | 1         | 2.08%   |
| Canon MF3200 series                           | 1         | 2.08%   |
| Canon MF3110                                  | 1         | 2.08%   |
| Canon iP7200 series                           | 1         | 2.08%   |
| Canon CanoScan LiDE 300                       | 1         | 2.08%   |
| Brother MFC-7420                              | 1         | 2.08%   |
| Brother HL-5380DN series                      | 1         | 2.08%   |
| Brother HL-5250DN Printer                     | 1         | 2.08%   |
| Brother HL-1210W series                       | 1         | 2.08%   |

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
| IMC Networks                           | 222       | 22.82%  |
| Chicony Electronics                    | 192       | 19.73%  |
| Realtek Semiconductor                  | 85        | 8.74%   |
| Microdia                               | 74        | 7.61%   |
| Acer                                   | 65        | 6.68%   |
| Sunplus Innovation Technology          | 52        | 5.34%   |
| Quanta                                 | 41        | 4.21%   |
| Syntek                                 | 25        | 2.57%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 2.47%   |
| Alcor Micro                            | 23        | 2.36%   |
| Lite-On Technology                     | 21        | 2.16%   |
| Suyin                                  | 19        | 1.95%   |
| Logitech                               | 19        | 1.95%   |
| Apple                                  | 12        | 1.23%   |
| Sonix Technology                       | 10        | 1.03%   |
| Samsung Electronics                    | 10        | 1.03%   |
| Ricoh                                  | 9         | 0.92%   |
| Microsoft                              | 9         | 0.92%   |
| Z-Star Microelectronics                | 6         | 0.62%   |
| Silicon Motion                         | 6         | 0.62%   |
| Luxvisions Innotech Limited            | 6         | 0.62%   |
| OmniVision Technologies                | 5         | 0.51%   |
| ALi                                    | 4         | 0.41%   |
| Lenovo                                 | 3         | 0.31%   |
| GEMBIRD                                | 3         | 0.31%   |
| Cubeternet                             | 3         | 0.31%   |
| Sunplus Technology                     | 2         | 0.21%   |
| Primax Electronics                     | 2         | 0.21%   |
| Jieli Technology                       | 2         | 0.21%   |
| Importek                               | 2         | 0.21%   |
| Genesys Logic                          | 2         | 0.21%   |
| Aveo Technology                        | 2         | 0.21%   |
| WaveRider Communications               | 1         | 0.1%    |
| Unknown                                | 1         | 0.1%    |
| Trust                                  | 1         | 0.1%    |
| Philips (or NXP)                       | 1         | 0.1%    |
| Novatek Microelectronics               | 1         | 0.1%    |
| KYE Systems (Mouse Systems)            | 1         | 0.1%    |
| Jeilin Technology                      | 1         | 0.1%    |
| Huawei Technologies                    | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam      | 99        | 10.15%  |
| IMC Networks USB2.0 HD UVC WebCam       | 68        | 6.97%   |
| Chicony Integrated Camera               | 39        | 4%      |
| Realtek Integrated_Webcam_HD            | 31        | 3.18%   |
| IMC Networks Integrated Camera          | 22        | 2.26%   |
| Microdia Integrated_Webcam_HD           | 19        | 1.95%   |
| Acer Integrated Camera                  | 19        | 1.95%   |
| Chicony USB2.0 VGA UVC WebCam           | 16        | 1.64%   |
| Realtek USB Camera                      | 14        | 1.44%   |
| Chicony HD WebCam                       | 14        | 1.44%   |
| Syntek Integrated Camera                | 13        | 1.33%   |
| Chicony USB2.0 HD UVC WebCam            | 12        | 1.23%   |
| Sunplus HD WebCam                       | 10        | 1.03%   |
| Samsung Galaxy series, misc. (MTP mode) | 10        | 1.03%   |
| Acer Lenovo EasyCamera                  | 10        | 1.03%   |
| Quanta VGA WebCam                       | 9         | 0.92%   |
| Chicony TOSHIBA Web Camera - HD         | 9         | 0.92%   |
| Sonix USB2.0 HD UVC WebCam              | 8         | 0.82%   |
| Microdia Integrated Webcam              | 8         | 0.82%   |
| Lite-On Integrated Camera               | 8         | 0.82%   |
| Chicony HP Webcam                       | 8         | 0.82%   |
| Chicony EasyCamera                      | 8         | 0.82%   |
| Alcor Micro USB 2.0 PC Camera           | 8         | 0.82%   |
| Acer EasyCamera                         | 8         | 0.82%   |
| Sunplus Integrated_Webcam_HD            | 7         | 0.72%   |
| Realtek USB2.0 HD UVC WebCam            | 7         | 0.72%   |
| Microsoft LifeCam HD-3000               | 7         | 0.72%   |
| Microdia Camera                         | 7         | 0.72%   |
| IMC Networks USB2.0 UVC HD Webcam       | 7         | 0.72%   |
| Chicony VGA WebCam                      | 7         | 0.72%   |
| Acer SunplusIT Integrated Camera        | 7         | 0.72%   |
| Syntek EasyCamera                       | 6         | 0.62%   |
| Realtek Lenovo EasyCamera               | 6         | 0.62%   |
| Chicony HP HD Webcam                    | 6         | 0.62%   |
| Alcor Micro USB 2.0 Camera              | 6         | 0.62%   |
| Syntek Lenovo EasyCamera                | 5         | 0.51%   |
| Sunplus ASUS Webcam                     | 5         | 0.51%   |
| Realtek USB2.0 VGA UVC WebCam           | 5         | 0.51%   |
| Realtek Integrated Webcam               | 5         | 0.51%   |
| Quanta HD Webcam                        | 5         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 52        | 36.36%  |
| Synaptics                  | 38        | 26.57%  |
| Shenzhen Goodix Technology | 16        | 11.19%  |
| Upek                       | 11        | 7.69%   |
| Elan Microelectronics      | 11        | 7.69%   |
| AuthenTec                  | 7         | 4.9%    |
| LighTuning Technology      | 5         | 3.5%    |
| STMicroelectronics         | 1         | 0.7%    |
| GDMicroelectronics         | 1         | 0.7%    |
| Focal-systems.Corp         | 1         | 0.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 7.69%   |
| Synaptics  WBDI                                                            | 11        | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 6.99%   |
| Shenzhen Goodix  Fingerprint Device                                        | 10        | 6.99%   |
| Elan ELAN:Fingerprint                                                      | 9         | 6.29%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 5.59%   |
| Unknown                                                                    | 8         | 5.59%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 4.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 4.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.2%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 3.5%    |
| Validity Sensors Synaptics WBDI                                            | 5         | 3.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 3.5%    |
| AuthenTec AES2810                                                          | 5         | 3.5%    |
| Validity Sensors VFS491                                                    | 4         | 2.8%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.1%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 2.1%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 2.1%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.4%    |
| LighTuning Fingerprint Reader                                              | 2         | 1.4%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.4%    |
| Elan ELAN:ARM-M4                                                           | 2         | 1.4%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.7%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.7%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.7%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.7%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.7%    |
| GDMicroelectronics Touch Fingerprint Sensor                                | 1         | 0.7%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.7%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.7%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 37        | 58.73%  |
| Alcor Micro               | 13        | 20.63%  |
| Lenovo                    | 4         | 6.35%   |
| O2 Micro                  | 3         | 4.76%   |
| Upek                      | 2         | 3.17%   |
| Gemalto (was Gemplus)     | 1         | 1.59%   |
| Fujitsu Siemens Computers | 1         | 1.59%   |
| Chicony Electronics       | 1         | 1.59%   |
| Aladdin Knowledge Systems | 1         | 1.59%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 20.63%  |
| Broadcom 58200                                                               | 12        | 19.05%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 12.7%   |
| Broadcom 5880                                                                | 8         | 12.7%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.35%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 4.76%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.17%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.59%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 1.59%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.59%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.59%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1099      | 73.32%  |
| 1     | 330       | 22.01%  |
| 2     | 63        | 4.2%    |
| 3     | 5         | 0.33%   |
| 10    | 1         | 0.07%   |
| 4     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 142       | 30.15%  |
| Graphics card            | 91        | 19.32%  |
| Net/wireless             | 58        | 12.31%  |
| Chipcard                 | 58        | 12.31%  |
| Multimedia controller    | 30        | 6.37%   |
| Communication controller | 19        | 4.03%   |
| Bluetooth                | 16        | 3.4%    |
| Camera                   | 14        | 2.97%   |
| Storage                  | 13        | 2.76%   |
| Sound                    | 7         | 1.49%   |
| Unassigned class         | 4         | 0.85%   |
| Card reader              | 4         | 0.85%   |
| Network                  | 3         | 0.64%   |
| Net/ethernet             | 3         | 0.64%   |
| Storage/ide              | 2         | 0.42%   |
| Unclassified device      | 1         | 0.21%   |
| Storage/raid             | 1         | 0.21%   |
| Storage/nvme             | 1         | 0.21%   |
| Modem                    | 1         | 0.21%   |
| Flash memory             | 1         | 0.21%   |
| Firewire controller      | 1         | 0.21%   |
| Dvb card                 | 1         | 0.21%   |

