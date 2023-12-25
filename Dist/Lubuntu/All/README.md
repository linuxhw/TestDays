Lubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Lubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu/Desktop/README.md) and [notebooks](/Dist/Lubuntu/Notebook/README.md).

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

Total: 2020

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0XPDFK A01                  | Desktop     | [538aa9126b](https://linux-hardware.org/?probe=538aa9126b) | Dec 23, 2023 |
| ATARI         | VCS 800 Black Walnut        | Notebook    | [34456982d3](https://linux-hardware.org/?probe=34456982d3) | Dec 23, 2023 |
| Google        | Treeya                      | Notebook    | [b6541ef594](https://linux-hardware.org/?probe=b6541ef594) | Dec 19, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [9e7c59246d](https://linux-hardware.org/?probe=9e7c59246d) | Dec 19, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [6528f813b7](https://linux-hardware.org/?probe=6528f813b7) | Dec 17, 2023 |
| Google        | Candy                       | Notebook    | [be56752bfd](https://linux-hardware.org/?probe=be56752bfd) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [65d7452931](https://linux-hardware.org/?probe=65d7452931) | Dec 17, 2023 |
| PELADN        | HA-3                        | Desktop     | [cd40102512](https://linux-hardware.org/?probe=cd40102512) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [acdb6ef8aa](https://linux-hardware.org/?probe=acdb6ef8aa) | Dec 17, 2023 |
| XFX           | MI-9300-7AS9                | Desktop     | [a3015ca40c](https://linux-hardware.org/?probe=a3015ca40c) | Dec 14, 2023 |
| HP            | ZBook 17                    | Notebook    | [d1269ca08c](https://linux-hardware.org/?probe=d1269ca08c) | Dec 13, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [295f9127b0](https://linux-hardware.org/?probe=295f9127b0) | Dec 12, 2023 |
| Lenovo        | 3111 SDK0J40700 WIN 3258... | Mini pc     | [52be4d3e15](https://linux-hardware.org/?probe=52be4d3e15) | Dec 12, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [e126cdbf4b](https://linux-hardware.org/?probe=e126cdbf4b) | Dec 10, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [213b775f8b](https://linux-hardware.org/?probe=213b775f8b) | Dec 08, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [d4c43fe4f4](https://linux-hardware.org/?probe=d4c43fe4f4) | Dec 08, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [5ebbbca196](https://linux-hardware.org/?probe=5ebbbca196) | Dec 04, 2023 |
| Dell          | 0PU052                      | Desktop     | [4a653cc26a](https://linux-hardware.org/?probe=4a653cc26a) | Dec 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d25f6b4dd3](https://linux-hardware.org/?probe=d25f6b4dd3) | Dec 02, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [5a628a7b0f](https://linux-hardware.org/?probe=5a628a7b0f) | Nov 30, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [3b82362902](https://linux-hardware.org/?probe=3b82362902) | Nov 29, 2023 |
| SGIN          | M15                         | Notebook    | [c7fb994367](https://linux-hardware.org/?probe=c7fb994367) | Nov 28, 2023 |
| Dell          | Latitude E6520              | Notebook    | [a03b74a3d3](https://linux-hardware.org/?probe=a03b74a3d3) | Nov 28, 2023 |
| ASUSTek       | X550ZE                      | Notebook    | [dedc54db8f](https://linux-hardware.org/?probe=dedc54db8f) | Nov 27, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [370ddc00c4](https://linux-hardware.org/?probe=370ddc00c4) | Nov 24, 2023 |
| Chuwi         | X312B                       | Notebook    | [7f13217449](https://linux-hardware.org/?probe=7f13217449) | Nov 23, 2023 |
| eMachines     | EL1358                      | Desktop     | [f22b0b98c3](https://linux-hardware.org/?probe=f22b0b98c3) | Nov 23, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [1e58f5a4f9](https://linux-hardware.org/?probe=1e58f5a4f9) | Nov 21, 2023 |
| MSI           | Raider GE76 12UE            | Notebook    | [bad07cc00d](https://linux-hardware.org/?probe=bad07cc00d) | Nov 20, 2023 |
| Packard Be... | ENLE11BZ                    | Notebook    | [905ad855b3](https://linux-hardware.org/?probe=905ad855b3) | Nov 19, 2023 |
| ASUSTek       | X201E                       | Notebook    | [3532136698](https://linux-hardware.org/?probe=3532136698) | Nov 18, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [d297e1365c](https://linux-hardware.org/?probe=d297e1365c) | Nov 16, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [dde4f98b29](https://linux-hardware.org/?probe=dde4f98b29) | Nov 16, 2023 |
| HUAWEI        | MRGFG-XX                    | Notebook    | [b7dda3ece0](https://linux-hardware.org/?probe=b7dda3ece0) | Nov 14, 2023 |
| Acer          | Extensa 5620                | Notebook    | [3c206e8578](https://linux-hardware.org/?probe=3c206e8578) | Nov 13, 2023 |
| MSI           | MS-7309                     | Desktop     | [c6ca259cae](https://linux-hardware.org/?probe=c6ca259cae) | Nov 13, 2023 |
| Intel         | STK2MV64CC H89290-502       | Desktop     | [041670b7d8](https://linux-hardware.org/?probe=041670b7d8) | Nov 13, 2023 |
| ASUSTek       | T100TAS                     | Notebook    | [ff4068e60a](https://linux-hardware.org/?probe=ff4068e60a) | Nov 12, 2023 |
| HP            | 255 G1                      | Notebook    | [988c1c2454](https://linux-hardware.org/?probe=988c1c2454) | Nov 12, 2023 |
| HP            | 255 G1                      | Notebook    | [9aa30be183](https://linux-hardware.org/?probe=9aa30be183) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fa680be8d9](https://linux-hardware.org/?probe=fa680be8d9) | Nov 10, 2023 |
| ASUSTek       | X550ZE                      | Notebook    | [31d4fc8694](https://linux-hardware.org/?probe=31d4fc8694) | Nov 09, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [94bc809d57](https://linux-hardware.org/?probe=94bc809d57) | Nov 05, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [cf0c02a17a](https://linux-hardware.org/?probe=cf0c02a17a) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [fdb464fed7](https://linux-hardware.org/?probe=fdb464fed7) | Nov 02, 2023 |
| PCChips       | P49G                        | Desktop     | [6b1de00356](https://linux-hardware.org/?probe=6b1de00356) | Nov 02, 2023 |
| ZOTAC         | NM10                        | Desktop     | [5a951d80a6](https://linux-hardware.org/?probe=5a951d80a6) | Oct 31, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [d63ccd5259](https://linux-hardware.org/?probe=d63ccd5259) | Oct 30, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4f0b8be2f6](https://linux-hardware.org/?probe=4f0b8be2f6) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [115cf0d371](https://linux-hardware.org/?probe=115cf0d371) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [6fbbd2a061](https://linux-hardware.org/?probe=6fbbd2a061) | Oct 30, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [48785f697c](https://linux-hardware.org/?probe=48785f697c) | Oct 29, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [3fa8a23f12](https://linux-hardware.org/?probe=3fa8a23f12) | Oct 29, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c86a40c419](https://linux-hardware.org/?probe=c86a40c419) | Oct 28, 2023 |
| Intel         | H61                         | Desktop     | [fccff5fcb2](https://linux-hardware.org/?probe=fccff5fcb2) | Oct 27, 2023 |
| Acer          | Veriton N4660G              | Desktop     | [712511f568](https://linux-hardware.org/?probe=712511f568) | Oct 27, 2023 |
| Acer          | Aspire 9300                 | Notebook    | [3094b549c5](https://linux-hardware.org/?probe=3094b549c5) | Oct 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [358936d398](https://linux-hardware.org/?probe=358936d398) | Oct 25, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5a23f97862](https://linux-hardware.org/?probe=5a23f97862) | Oct 23, 2023 |
| Dixonsxp      | Unknown                     | Notebook    | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| Dell          | XPS 9315                    | Notebook    | [8c9d16e737](https://linux-hardware.org/?probe=8c9d16e737) | Oct 22, 2023 |
| ZOTAC         | NM10                        | Desktop     | [2e0ab67bec](https://linux-hardware.org/?probe=2e0ab67bec) | Oct 21, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [5ddf61741f](https://linux-hardware.org/?probe=5ddf61741f) | Oct 20, 2023 |
| HP            | 8265                        | Desktop     | [f1bdedb075](https://linux-hardware.org/?probe=f1bdedb075) | Oct 20, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [8ff07b1c79](https://linux-hardware.org/?probe=8ff07b1c79) | Oct 19, 2023 |
| Positivo      | AT300b                      | Notebook    | [a39989b55b](https://linux-hardware.org/?probe=a39989b55b) | Oct 18, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c60b3dbfa2](https://linux-hardware.org/?probe=c60b3dbfa2) | Oct 17, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | Notebook    | [9d142e587e](https://linux-hardware.org/?probe=9d142e587e) | Oct 17, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [99490448ae](https://linux-hardware.org/?probe=99490448ae) | Oct 16, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [431b672bf5](https://linux-hardware.org/?probe=431b672bf5) | Oct 16, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [1f161ae269](https://linux-hardware.org/?probe=1f161ae269) | Oct 16, 2023 |
| Google        | Careena                     | Notebook    | [8359c8c3e8](https://linux-hardware.org/?probe=8359c8c3e8) | Oct 15, 2023 |
| Google        | Careena                     | Notebook    | [4292c49150](https://linux-hardware.org/?probe=4292c49150) | Oct 15, 2023 |
| HP            | Notebook                    | Notebook    | [fb39ee7d9d](https://linux-hardware.org/?probe=fb39ee7d9d) | Oct 13, 2023 |
| Thomson       | NEO14-4W64                  | Notebook    | [f68e52a8a1](https://linux-hardware.org/?probe=f68e52a8a1) | Oct 12, 2023 |
| BLANK         | Intel powered classmate ... | Notebook    | [78cc4b7937](https://linux-hardware.org/?probe=78cc4b7937) | Oct 11, 2023 |
| BLANK         | Intel powered classmate ... | Notebook    | [bc4093e3c7](https://linux-hardware.org/?probe=bc4093e3c7) | Oct 11, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [ee4617fa73](https://linux-hardware.org/?probe=ee4617fa73) | Oct 10, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
| Google        | Sasuke                      | Notebook    | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [f8ad7736e2](https://linux-hardware.org/?probe=f8ad7736e2) | Oct 07, 2023 |
| Insyde        | Braswell                    | Notebook    | [c4261097f5](https://linux-hardware.org/?probe=c4261097f5) | Oct 07, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bf8761b854](https://linux-hardware.org/?probe=bf8761b854) | Oct 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ae4ee327c0](https://linux-hardware.org/?probe=ae4ee327c0) | Oct 06, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [f88a18cfef](https://linux-hardware.org/?probe=f88a18cfef) | Oct 06, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [92e214fb3e](https://linux-hardware.org/?probe=92e214fb3e) | Oct 04, 2023 |
| Getac         | X500G3                      | Notebook    | [919772eed0](https://linux-hardware.org/?probe=919772eed0) | Oct 02, 2023 |
| Panasonic     | CF-F9KWPZFFE                | Notebook    | [33cf16d622](https://linux-hardware.org/?probe=33cf16d622) | Oct 01, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [d14bc5c139](https://linux-hardware.org/?probe=d14bc5c139) | Sep 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [f4326ad956](https://linux-hardware.org/?probe=f4326ad956) | Sep 26, 2023 |
| ASUSTek       | E1600WKA                    | All in one  | [43c8a9b758](https://linux-hardware.org/?probe=43c8a9b758) | Sep 26, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [3ff273b73c](https://linux-hardware.org/?probe=3ff273b73c) | Sep 26, 2023 |
| Intel         | H61                         | Desktop     | [ee0266b53c](https://linux-hardware.org/?probe=ee0266b53c) | Sep 25, 2023 |
| ASUSTek       | X451MA                      | Notebook    | [ed779c5de4](https://linux-hardware.org/?probe=ed779c5de4) | Sep 20, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [7b1aae3e2b](https://linux-hardware.org/?probe=7b1aae3e2b) | Sep 20, 2023 |
| Mini PC       | Cherry Trail CR             | Notebook    | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [47d423039b](https://linux-hardware.org/?probe=47d423039b) | Sep 19, 2023 |
| Dell          | Precision 3570              | Notebook    | [fd3441ff1d](https://linux-hardware.org/?probe=fd3441ff1d) | Sep 18, 2023 |
| Google        | Blooglet                    | Notebook    | [79ce749655](https://linux-hardware.org/?probe=79ce749655) | Sep 17, 2023 |
| Intel         | D945GCZ AAD32112-503        | Desktop     | [806f698174](https://linux-hardware.org/?probe=806f698174) | Sep 14, 2023 |
| HP            | 15                          | Notebook    | [03e1207549](https://linux-hardware.org/?probe=03e1207549) | Sep 12, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [04666fa9b7](https://linux-hardware.org/?probe=04666fa9b7) | Sep 11, 2023 |
| HP            | 2000                        | Notebook    | [48790bd831](https://linux-hardware.org/?probe=48790bd831) | Sep 09, 2023 |
| HP            | 2000                        | Notebook    | [ce9ba2b7c4](https://linux-hardware.org/?probe=ce9ba2b7c4) | Sep 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [6aea4eb6c4](https://linux-hardware.org/?probe=6aea4eb6c4) | Sep 09, 2023 |
| eMachines     | eM350                       | Notebook    | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [60f82737fa](https://linux-hardware.org/?probe=60f82737fa) | Sep 06, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [89f4028960](https://linux-hardware.org/?probe=89f4028960) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [23f0f9321c](https://linux-hardware.org/?probe=23f0f9321c) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7d6ff14b38](https://linux-hardware.org/?probe=7d6ff14b38) | Sep 05, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [69fec63660](https://linux-hardware.org/?probe=69fec63660) | Sep 04, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [ea00f871b9](https://linux-hardware.org/?probe=ea00f871b9) | Sep 04, 2023 |
| HP            | 255 G2                      | Notebook    | [27b48aa011](https://linux-hardware.org/?probe=27b48aa011) | Sep 02, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [8ba55e98ec](https://linux-hardware.org/?probe=8ba55e98ec) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d169572a6b](https://linux-hardware.org/?probe=d169572a6b) | Aug 31, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [ddcb97361b](https://linux-hardware.org/?probe=ddcb97361b) | Aug 30, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [cab1480dc6](https://linux-hardware.org/?probe=cab1480dc6) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bd35d44f1](https://linux-hardware.org/?probe=2bd35d44f1) | Aug 29, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [f37ab96772](https://linux-hardware.org/?probe=f37ab96772) | Aug 28, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [7abf0d31d8](https://linux-hardware.org/?probe=7abf0d31d8) | Aug 28, 2023 |
| Toshiba       | Satellite P770              | Notebook    | [8618c83c93](https://linux-hardware.org/?probe=8618c83c93) | Aug 26, 2023 |
| Google        | Robo                        | Notebook    | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| Acer          | Predator G3610              | Desktop     | [04153b05c7](https://linux-hardware.org/?probe=04153b05c7) | Aug 22, 2023 |
| Compal        | PBL20                       | Notebook    | [ae09076b4e](https://linux-hardware.org/?probe=ae09076b4e) | Aug 22, 2023 |
| HP            | Notebook                    | Notebook    | [11d2993965](https://linux-hardware.org/?probe=11d2993965) | Aug 20, 2023 |
| Google        | Madoo                       | Notebook    | [8eea1017dc](https://linux-hardware.org/?probe=8eea1017dc) | Aug 20, 2023 |
| HP            | Notebook                    | Notebook    | [f6e4865586](https://linux-hardware.org/?probe=f6e4865586) | Aug 19, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [3dfc4104a4](https://linux-hardware.org/?probe=3dfc4104a4) | Aug 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [62ecbe2f01](https://linux-hardware.org/?probe=62ecbe2f01) | Aug 18, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [92a3afc475](https://linux-hardware.org/?probe=92a3afc475) | Aug 17, 2023 |
| Lenovo        | ThinkPad T430 2349TFK       | Notebook    | [390899a281](https://linux-hardware.org/?probe=390899a281) | Aug 17, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [dd8d164747](https://linux-hardware.org/?probe=dd8d164747) | Aug 17, 2023 |
| Acer          | Aspire 5050                 | Notebook    | [63329f0ff6](https://linux-hardware.org/?probe=63329f0ff6) | Aug 16, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [374096baa6](https://linux-hardware.org/?probe=374096baa6) | Aug 15, 2023 |
| ASUSTek       | BM6875_BM6675_BP6375        | Desktop     | [0a2cdad4c1](https://linux-hardware.org/?probe=0a2cdad4c1) | Aug 15, 2023 |
| Apple         | Mac-F223BEC8                | Desktop     | [74a3be9a4a](https://linux-hardware.org/?probe=74a3be9a4a) | Aug 14, 2023 |
| HP            | Pavilion g7                 | Notebook    | [43351d6476](https://linux-hardware.org/?probe=43351d6476) | Aug 12, 2023 |
| Positivo      | C4128B-1                    | Convertible | [ef67e885dc](https://linux-hardware.org/?probe=ef67e885dc) | Aug 11, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [abaa0512b0](https://linux-hardware.org/?probe=abaa0512b0) | Aug 11, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [0028486d9d](https://linux-hardware.org/?probe=0028486d9d) | Aug 10, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [ced8776e4d](https://linux-hardware.org/?probe=ced8776e4d) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Toshiba       | Satellite L875D             | Notebook    | [de1a418102](https://linux-hardware.org/?probe=de1a418102) | Aug 08, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [3e037493db](https://linux-hardware.org/?probe=3e037493db) | Aug 06, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ca00849760](https://linux-hardware.org/?probe=ca00849760) | Aug 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [52c5dda710](https://linux-hardware.org/?probe=52c5dda710) | Jul 31, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [1a2d3f1778](https://linux-hardware.org/?probe=1a2d3f1778) | Jul 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [80a34d344b](https://linux-hardware.org/?probe=80a34d344b) | Jul 28, 2023 |
| Unknown       | SCHNEIDER                   | Desktop     | [6ab609f07e](https://linux-hardware.org/?probe=6ab609f07e) | Jul 27, 2023 |
| Dell          | Inspiron 1520               | Notebook    | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [5539799efa](https://linux-hardware.org/?probe=5539799efa) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [5ca26c7da9](https://linux-hardware.org/?probe=5ca26c7da9) | Jul 26, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | Notebook    | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4fe4e8b639](https://linux-hardware.org/?probe=4fe4e8b639) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [742d3b24c8](https://linux-hardware.org/?probe=742d3b24c8) | Jul 24, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | Notebook    | [c7dd142af9](https://linux-hardware.org/?probe=c7dd142af9) | Jul 24, 2023 |
| Dell          | Inspiron 5576               | Notebook    | [54c338bb01](https://linux-hardware.org/?probe=54c338bb01) | Jul 22, 2023 |
| Dell          | Inspiron 5576               | Notebook    | [6654328e2c](https://linux-hardware.org/?probe=6654328e2c) | Jul 22, 2023 |
| HP            | 2187 A01                    | Desktop     | [efd197811b](https://linux-hardware.org/?probe=efd197811b) | Jul 22, 2023 |
| HP            | 3646h                       | Desktop     | [01f2207fe0](https://linux-hardware.org/?probe=01f2207fe0) | Jul 22, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| Dell          | Latitude 5290               | Notebook    | [66860827b9](https://linux-hardware.org/?probe=66860827b9) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Fujitsu       | FMVNC4BC4                   | Notebook    | [14249b136a](https://linux-hardware.org/?probe=14249b136a) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | Notebook    | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| HP            | 255 G2                      | Notebook    | [eaf9befa3a](https://linux-hardware.org/?probe=eaf9befa3a) | Jul 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [07809870aa](https://linux-hardware.org/?probe=07809870aa) | Jul 19, 2023 |
| LG Electro... | 15Z90N-U.ARS5U1             | Notebook    | [54b03a096b](https://linux-hardware.org/?probe=54b03a096b) | Jul 19, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [2d896167d8](https://linux-hardware.org/?probe=2d896167d8) | Jul 16, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [493d7a5ab7](https://linux-hardware.org/?probe=493d7a5ab7) | Jul 12, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d0035bb703](https://linux-hardware.org/?probe=d0035bb703) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [8fb942eccd](https://linux-hardware.org/?probe=8fb942eccd) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [ff650dc0df](https://linux-hardware.org/?probe=ff650dc0df) | Jul 10, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2f1b70e168](https://linux-hardware.org/?probe=2f1b70e168) | Jul 08, 2023 |
| Acer          | Aspire E5-523G              | Notebook    | [6535e7c6d1](https://linux-hardware.org/?probe=6535e7c6d1) | Jul 08, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [282c9db256](https://linux-hardware.org/?probe=282c9db256) | Jul 08, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [8337bfbb61](https://linux-hardware.org/?probe=8337bfbb61) | Jul 08, 2023 |
| Acer          | Swift SFE16-42              | Notebook    | [c8b8a7d737](https://linux-hardware.org/?probe=c8b8a7d737) | Jul 07, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| HP            | ProBook 4525s               | Notebook    | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| Unknown       | Unknown                     | Other       | [f49e789b52](https://linux-hardware.org/?probe=f49e789b52) | Jul 04, 2023 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [b0eefed750](https://linux-hardware.org/?probe=b0eefed750) | Jul 03, 2023 |
| Google        | Pyro                        | Notebook    | [9632e7a77b](https://linux-hardware.org/?probe=9632e7a77b) | Jul 02, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b6b1cf5b68](https://linux-hardware.org/?probe=b6b1cf5b68) | Jul 02, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [e9b879f3ff](https://linux-hardware.org/?probe=e9b879f3ff) | Jul 02, 2023 |
| eMachines     | eME443                      | Notebook    | [0d6808da66](https://linux-hardware.org/?probe=0d6808da66) | Jun 30, 2023 |
| UMAX          | N14R                        | Notebook    | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| Sony          | VPCEB37FD                   | Notebook    | [afe6ac4f32](https://linux-hardware.org/?probe=afe6ac4f32) | Jun 27, 2023 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [7c6c7cff66](https://linux-hardware.org/?probe=7c6c7cff66) | Jun 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [fa54c60ae0](https://linux-hardware.org/?probe=fa54c60ae0) | Jun 26, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f0268ac6a8](https://linux-hardware.org/?probe=f0268ac6a8) | Jun 26, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [e094f469bc](https://linux-hardware.org/?probe=e094f469bc) | Jun 25, 2023 |
| Sony          | VPCEB37FD                   | Notebook    | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [19350653f7](https://linux-hardware.org/?probe=19350653f7) | Jun 23, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [004f9be7a7](https://linux-hardware.org/?probe=004f9be7a7) | Jun 21, 2023 |
| Pencents      | U50 Standard                | Mini pc     | [96db8365b1](https://linux-hardware.org/?probe=96db8365b1) | Jun 20, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | Notebook    | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| ASUSTek       | 1011CX                      | Notebook    | [0fa6b0b3dc](https://linux-hardware.org/?probe=0fa6b0b3dc) | Jun 19, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [b4c617c995](https://linux-hardware.org/?probe=b4c617c995) | Jun 19, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [009fdf15c4](https://linux-hardware.org/?probe=009fdf15c4) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e4c0eeb007](https://linux-hardware.org/?probe=e4c0eeb007) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [f52a0ddf99](https://linux-hardware.org/?probe=f52a0ddf99) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [7b9388df1b](https://linux-hardware.org/?probe=7b9388df1b) | Jun 16, 2023 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [af1a5cda08](https://linux-hardware.org/?probe=af1a5cda08) | Jun 16, 2023 |
| Dell          | Precision 3570              | Notebook    | [6f6debf1a4](https://linux-hardware.org/?probe=6f6debf1a4) | Jun 15, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [a96d9ae076](https://linux-hardware.org/?probe=a96d9ae076) | Jun 15, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| HP            | 21B4 A01                    | Desktop     | [16b576ebea](https://linux-hardware.org/?probe=16b576ebea) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| HP            | 3646h                       | Desktop     | [046f5d1a5b](https://linux-hardware.org/?probe=046f5d1a5b) | Jun 09, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | Notebook    | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| HP            | 3646h                       | Desktop     | [02353b5e9f](https://linux-hardware.org/?probe=02353b5e9f) | Jun 06, 2023 |
| HP            | 240 G3                      | Notebook    | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [b6411e69f3](https://linux-hardware.org/?probe=b6411e69f3) | Jun 04, 2023 |
| HP            | 3397                        | Desktop     | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [1375d36b0f](https://linux-hardware.org/?probe=1375d36b0f) | May 28, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [88c6b12404](https://linux-hardware.org/?probe=88c6b12404) | May 27, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [84953a504d](https://linux-hardware.org/?probe=84953a504d) | May 26, 2023 |
| Dell          | Latitude E6430              | Notebook    | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbab0f6dd8](https://linux-hardware.org/?probe=cbab0f6dd8) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [20c80a45a8](https://linux-hardware.org/?probe=20c80a45a8) | May 22, 2023 |
| Foxconn       | G41MXE-V                    | Desktop     | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [eea6382d39](https://linux-hardware.org/?probe=eea6382d39) | May 19, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [ce80a21736](https://linux-hardware.org/?probe=ce80a21736) | May 19, 2023 |
| ZOTAC         | NM10                        | Desktop     | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [f19d94af88](https://linux-hardware.org/?probe=f19d94af88) | May 18, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [a75df73ade](https://linux-hardware.org/?probe=a75df73ade) | May 18, 2023 |
| Lenovo        | ThinkPad T400 276522G       | Notebook    | [dc8b38dd37](https://linux-hardware.org/?probe=dc8b38dd37) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Medion        | Akoya P6660 MD99790         | Notebook    | [20ecc9b5dc](https://linux-hardware.org/?probe=20ecc9b5dc) | May 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0145d107e8](https://linux-hardware.org/?probe=0145d107e8) | May 15, 2023 |
| Intel         | W7650                       | Notebook    | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Toshiba       | Satellite Radius P55W-B     | Notebook    | [e2ed5e2135](https://linux-hardware.org/?probe=e2ed5e2135) | May 11, 2023 |
| Acer          | EQ45M                       | Desktop     | [57fa86c8dc](https://linux-hardware.org/?probe=57fa86c8dc) | May 11, 2023 |
| libre-comp... | roc-rk3328-cc               | Soc         | [9709c9cf35](https://linux-hardware.org/?probe=9709c9cf35) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0b08b7a631](https://linux-hardware.org/?probe=0b08b7a631) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| HP            | Notebook                    | Notebook    | [70ee3adf89](https://linux-hardware.org/?probe=70ee3adf89) | May 08, 2023 |
| Samsung       | 530XBB                      | Notebook    | [4d039b72a7](https://linux-hardware.org/?probe=4d039b72a7) | May 08, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| HP            | x2 210                      | Notebook    | [f60c4cb29b](https://linux-hardware.org/?probe=f60c4cb29b) | May 07, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| Google        | Glimmer                     | Notebook    | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | Notebook    | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| Unknown       | Phitronics N68C-M           | Desktop     | [77747ce79b](https://linux-hardware.org/?probe=77747ce79b) | May 02, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [4eb2bc6e88](https://linux-hardware.org/?probe=4eb2bc6e88) | May 01, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| Sony          | SVF1521C6EW                 | Notebook    | [57e1c14061](https://linux-hardware.org/?probe=57e1c14061) | Apr 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [6976f884e6](https://linux-hardware.org/?probe=6976f884e6) | Apr 29, 2023 |
| HP            | Laptop 15-bs2xx             | Notebook    | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Google        | Chell                       | Notebook    | [1d1b263f21](https://linux-hardware.org/?probe=1d1b263f21) | Apr 27, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [e9237f0d53](https://linux-hardware.org/?probe=e9237f0d53) | Apr 27, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| ASUSTek       | F1A55-M LK R2.0             | Desktop     | [234e0d0738](https://linux-hardware.org/?probe=234e0d0738) | Apr 23, 2023 |
| Dell          | Latitude 5290               | Notebook    | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | Notebook    | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [f79af9bad0](https://linux-hardware.org/?probe=f79af9bad0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [70a0b986fa](https://linux-hardware.org/?probe=70a0b986fa) | Apr 18, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| GPU Compan... | GWTN116-3                   | Notebook    | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | Notebook    | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d938ba339d](https://linux-hardware.org/?probe=d938ba339d) | Apr 14, 2023 |
| Intel         | W7650                       | Notebook    | [3e4c54a5f0](https://linux-hardware.org/?probe=3e4c54a5f0) | Apr 11, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | Notebook    | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| Toshiba       | Satellite P70-A             | Notebook    | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [ad70ba8e9d](https://linux-hardware.org/?probe=ad70ba8e9d) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b16afcac8b](https://linux-hardware.org/?probe=b16afcac8b) | Apr 03, 2023 |
| ASRock        | G31M-S                      | Desktop     | [70f35c82f1](https://linux-hardware.org/?probe=70f35c82f1) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [0e18c3546c](https://linux-hardware.org/?probe=0e18c3546c) | Apr 01, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| ASRock        | G31M-S                      | Desktop     | [4ad324790c](https://linux-hardware.org/?probe=4ad324790c) | Mar 28, 2023 |
| ASRock        | G31M-S                      | Desktop     | [225f122e05](https://linux-hardware.org/?probe=225f122e05) | Mar 28, 2023 |
| YANYU         | ITX-S192                    | Desktop     | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fe79f70952](https://linux-hardware.org/?probe=fe79f70952) | Mar 27, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4ce0966b14](https://linux-hardware.org/?probe=4ce0966b14) | Mar 26, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4faa2a52d3](https://linux-hardware.org/?probe=4faa2a52d3) | Mar 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| Packard Be... | EasyNote SB65               | Notebook    | [f49cf1aa7a](https://linux-hardware.org/?probe=f49cf1aa7a) | Mar 25, 2023 |
| ASRock        | N68-GS4/USB3 FX             | Desktop     | [b846b11174](https://linux-hardware.org/?probe=b846b11174) | Mar 25, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [cfe369e6b8](https://linux-hardware.org/?probe=cfe369e6b8) | Mar 24, 2023 |
| Samsung       | 530XBB                      | Notebook    | [2bb5946ee7](https://linux-hardware.org/?probe=2bb5946ee7) | Mar 23, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| HP            | 89DC 0100                   | All in one  | [d8afbb81f9](https://linux-hardware.org/?probe=d8afbb81f9) | Mar 21, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | Notebook    | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [5228141efd](https://linux-hardware.org/?probe=5228141efd) | Mar 16, 2023 |
| Dell          | Latitude 5290               | Notebook    | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| Dell          | Latitude 7480               | Notebook    | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [e8c31757e0](https://linux-hardware.org/?probe=e8c31757e0) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | Desktop     | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [309d95f00f](https://linux-hardware.org/?probe=309d95f00f) | Mar 11, 2023 |
| BANGHO        | LITE E34                    | Desktop     | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [4167bec602](https://linux-hardware.org/?probe=4167bec602) | Mar 09, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [256a8abb58](https://linux-hardware.org/?probe=256a8abb58) | Mar 06, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [dbe64de6bd](https://linux-hardware.org/?probe=dbe64de6bd) | Mar 06, 2023 |
| ASUSTek       | A7N8X-E                     | Desktop     | [d0847fb118](https://linux-hardware.org/?probe=d0847fb118) | Mar 06, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f4e7268671](https://linux-hardware.org/?probe=f4e7268671) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [1eef9edf97](https://linux-hardware.org/?probe=1eef9edf97) | Mar 04, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [b492e1c092](https://linux-hardware.org/?probe=b492e1c092) | Mar 04, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| DEXP          | Aquilon C15                 | Notebook    | [9ae006e12a](https://linux-hardware.org/?probe=9ae006e12a) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Intel         | W7650                       | Notebook    | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Intel         | X79 V2.72A                  | Desktop     | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Google        | Celes                       | Notebook    | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | Notebook    | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Acer          | Aspire Z5101                | All in one  | [ec55f791bb](https://linux-hardware.org/?probe=ec55f791bb) | Feb 28, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [264f8cb6db](https://linux-hardware.org/?probe=264f8cb6db) | Feb 27, 2023 |
| Getac         | V200-X                      | Notebook    | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| Acer          | Aspire Z5101                | All in one  | [3dd821cc61](https://linux-hardware.org/?probe=3dd821cc61) | Feb 27, 2023 |
| HP            | Pavilion 17                 | Notebook    | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [9c3a1f5cd5](https://linux-hardware.org/?probe=9c3a1f5cd5) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [4b440b2084](https://linux-hardware.org/?probe=4b440b2084) | Feb 22, 2023 |
| Positivo      | Q232A                       | Notebook    | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [835743de83](https://linux-hardware.org/?probe=835743de83) | Feb 21, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [11739ccfa1](https://linux-hardware.org/?probe=11739ccfa1) | Feb 20, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [6f9ef751cd](https://linux-hardware.org/?probe=6f9ef751cd) | Feb 20, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [1c2d1949fd](https://linux-hardware.org/?probe=1c2d1949fd) | Feb 19, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [edfa765236](https://linux-hardware.org/?probe=edfa765236) | Feb 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Medion        | Akoya E6412T                | Notebook    | [41a31b6bd1](https://linux-hardware.org/?probe=41a31b6bd1) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2420c1fb57](https://linux-hardware.org/?probe=2420c1fb57) | Feb 18, 2023 |
| HP            | Notebook                    | Notebook    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [d159971f77](https://linux-hardware.org/?probe=d159971f77) | Feb 18, 2023 |
| Getac         | V200-X                      | Notebook    | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | Notebook    | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| MSI           | MS-7267                     | Desktop     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [72b29b5f80](https://linux-hardware.org/?probe=72b29b5f80) | Feb 16, 2023 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [1fbc4cea88](https://linux-hardware.org/?probe=1fbc4cea88) | Feb 16, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [553bddf256](https://linux-hardware.org/?probe=553bddf256) | Feb 15, 2023 |
| ECS           | G41T-M7                     | Desktop     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6012e644eb](https://linux-hardware.org/?probe=6012e644eb) | Feb 13, 2023 |
| Acer          | Extensa 2540                | Notebook    | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [49d1ea8b3e](https://linux-hardware.org/?probe=49d1ea8b3e) | Feb 11, 2023 |
| Dell          | 0FPP7F A00                  | Desktop     | [0a67b25026](https://linux-hardware.org/?probe=0a67b25026) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [db3d49fa06](https://linux-hardware.org/?probe=db3d49fa06) | Feb 08, 2023 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [380eb0d0e1](https://linux-hardware.org/?probe=380eb0d0e1) | Feb 08, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [a3384bd952](https://linux-hardware.org/?probe=a3384bd952) | Feb 06, 2023 |
| Toshiba       | Satellite C55D-A            | Notebook    | [38083cc2a4](https://linux-hardware.org/?probe=38083cc2a4) | Feb 05, 2023 |
| Acer          | TravelMate P253             | Notebook    | [b2cad8970a](https://linux-hardware.org/?probe=b2cad8970a) | Feb 04, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| Acer          | AO756                       | Notebook    | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4f6655087b](https://linux-hardware.org/?probe=4f6655087b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Intel         | Unknown                     | Notebook    | [f387a4b732](https://linux-hardware.org/?probe=f387a4b732) | Jan 29, 2023 |
| Intel         | Unknown                     | Notebook    | [79aa357327](https://linux-hardware.org/?probe=79aa357327) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | Notebook    | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| MSI           | MS-7032                     | Desktop     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [be66e9073f](https://linux-hardware.org/?probe=be66e9073f) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [3a8aced1b7](https://linux-hardware.org/?probe=3a8aced1b7) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [1099a3c6c9](https://linux-hardware.org/?probe=1099a3c6c9) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [4944e0cddd](https://linux-hardware.org/?probe=4944e0cddd) | Jan 24, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | Notebook    | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [11964c6701](https://linux-hardware.org/?probe=11964c6701) | Jan 16, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | Desktop     | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| ASRock        | ION3D-HT                    | Desktop     | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Acer          | Aspire One 721              | Notebook    | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | Notebook    | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [deff7fc898](https://linux-hardware.org/?probe=deff7fc898) | Jan 07, 2023 |
| Google        | Candy                       | Notebook    | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [6ef8fba020](https://linux-hardware.org/?probe=6ef8fba020) | Jan 06, 2023 |
| ASUSTek       | F50SV                       | Notebook    | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | Notebook    | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Dell          | Dimension 4500S             | Desktop     | [5b907b07e4](https://linux-hardware.org/?probe=5b907b07e4) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [73a67d66af](https://linux-hardware.org/?probe=73a67d66af) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Google        | Candy                       | Notebook    | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| Dell          | 05KX61 A00                  | Server      | [9f365307f3](https://linux-hardware.org/?probe=9f365307f3) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Google        | Edgar                       | Notebook    | [738a0d9324](https://linux-hardware.org/?probe=738a0d9324) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [fd1cdfc132](https://linux-hardware.org/?probe=fd1cdfc132) | Dec 28, 2022 |
| Acer          | Aspire SW3-013              | Notebook    | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [252a51f201](https://linux-hardware.org/?probe=252a51f201) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| ASRock        | 970DE3/U3S3                 | Desktop     | [1505706e04](https://linux-hardware.org/?probe=1505706e04) | Dec 25, 2022 |
| ASRock        | 970DE3/U3S3                 | Desktop     | [1c996d8122](https://linux-hardware.org/?probe=1c996d8122) | Dec 25, 2022 |
| HP            | Stream Notebook PC 11       | Notebook    | [f33ebabb99](https://linux-hardware.org/?probe=f33ebabb99) | Dec 24, 2022 |
| HP            | Stream 8 Tablet             | Tablet      | [752a0b9007](https://linux-hardware.org/?probe=752a0b9007) | Dec 23, 2022 |
| Positivo      | C14CR21                     | Notebook    | [be49c26bb4](https://linux-hardware.org/?probe=be49c26bb4) | Dec 21, 2022 |
| HP            | Compaq 6715b (RM174UT#AB... | Notebook    | [db3b8615f7](https://linux-hardware.org/?probe=db3b8615f7) | Dec 21, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| Google        | Coral                       | Notebook    | [8e2407d4b2](https://linux-hardware.org/?probe=8e2407d4b2) | Dec 19, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | Notebook    | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| HP            | 2000                        | Notebook    | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| HP            | Compaq 6830s                | Notebook    | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | Notebook    | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| ASUSTek       | K50C                        | Notebook    | [6cf2037e0f](https://linux-hardware.org/?probe=6cf2037e0f) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [abe82b0f58](https://linux-hardware.org/?probe=abe82b0f58) | Dec 04, 2022 |
| ASUSTek       | ET1610PT                    | Desktop     | [d8b1840336](https://linux-hardware.org/?probe=d8b1840336) | Dec 03, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| HP            | 620                         | Notebook    | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [03a1a706d1](https://linux-hardware.org/?probe=03a1a706d1) | Nov 28, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [63487a2957](https://linux-hardware.org/?probe=63487a2957) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [0b632b7ae8](https://linux-hardware.org/?probe=0b632b7ae8) | Nov 27, 2022 |
| Acer          | AO722                       | Notebook    | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [ba7b5c7748](https://linux-hardware.org/?probe=ba7b5c7748) | Nov 26, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2d8e324570](https://linux-hardware.org/?probe=2d8e324570) | Nov 26, 2022 |
| Foxconn       | G41MXP/G41MXP-V             | Desktop     | [f8e0414c84](https://linux-hardware.org/?probe=f8e0414c84) | Nov 26, 2022 |
| Intel         | BTC-T37                     | Desktop     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [b37755877d](https://linux-hardware.org/?probe=b37755877d) | Nov 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| HP            | 620                         | Notebook    | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [2574454ebe](https://linux-hardware.org/?probe=2574454ebe) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3b7077c5ab](https://linux-hardware.org/?probe=3b7077c5ab) | Nov 19, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| HP            | 3048h                       | Desktop     | [33ced86304](https://linux-hardware.org/?probe=33ced86304) | Nov 19, 2022 |
| HP            | 3048h                       | Desktop     | [e5fdb1f67a](https://linux-hardware.org/?probe=e5fdb1f67a) | Nov 19, 2022 |
| ASUSTek       | K55A                        | Notebook    | [d09b309d4d](https://linux-hardware.org/?probe=d09b309d4d) | Nov 19, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [4825e06bd4](https://linux-hardware.org/?probe=4825e06bd4) | Nov 19, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [57bcd4363a](https://linux-hardware.org/?probe=57bcd4363a) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [3d49b98878](https://linux-hardware.org/?probe=3d49b98878) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [db28f53298](https://linux-hardware.org/?probe=db28f53298) | Nov 12, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [8a149b06a1](https://linux-hardware.org/?probe=8a149b06a1) | Nov 12, 2022 |
| Acer          | AOD255E                     | Notebook    | [817724283b](https://linux-hardware.org/?probe=817724283b) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| Toshiba       | Satellite L15-B             | Notebook    | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [3408fb4c36](https://linux-hardware.org/?probe=3408fb4c36) | Nov 07, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [f731a55cc1](https://linux-hardware.org/?probe=f731a55cc1) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [29617200dd](https://linux-hardware.org/?probe=29617200dd) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [24f27140f8](https://linux-hardware.org/?probe=24f27140f8) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [eb15ca5b98](https://linux-hardware.org/?probe=eb15ca5b98) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [20824af437](https://linux-hardware.org/?probe=20824af437) | Nov 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a922f68180](https://linux-hardware.org/?probe=a922f68180) | Nov 03, 2022 |
| Lenovo        | NOK                         | Desktop     | [8c9f8ff505](https://linux-hardware.org/?probe=8c9f8ff505) | Nov 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [027cfb43c4](https://linux-hardware.org/?probe=027cfb43c4) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [113930496e](https://linux-hardware.org/?probe=113930496e) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2934bab108](https://linux-hardware.org/?probe=2934bab108) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a5712d3982](https://linux-hardware.org/?probe=a5712d3982) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [9b53e5c27d](https://linux-hardware.org/?probe=9b53e5c27d) | Oct 31, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [95238cc6e8](https://linux-hardware.org/?probe=95238cc6e8) | Oct 30, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [f416278476](https://linux-hardware.org/?probe=f416278476) | Oct 29, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [2501d67199](https://linux-hardware.org/?probe=2501d67199) | Oct 28, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [4b4c00b0a9](https://linux-hardware.org/?probe=4b4c00b0a9) | Oct 28, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [9c7127a256](https://linux-hardware.org/?probe=9c7127a256) | Oct 27, 2022 |
| Acer          | Extensa 2509                | Notebook    | [a27b3d38a9](https://linux-hardware.org/?probe=a27b3d38a9) | Oct 27, 2022 |
| Google        | Apel                        | Notebook    | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Lenovo        | ThinkCentre M81 5048E2G     | Desktop     | [35840b3b8c](https://linux-hardware.org/?probe=35840b3b8c) | Oct 23, 2022 |
| Acer          | Aspire one                  | Notebook    | [fced25613a](https://linux-hardware.org/?probe=fced25613a) | Oct 18, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| HP            | 431 Notebook                | Notebook    | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | Notebook    | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| AOpen         | D1007 0BBA                  | Desktop     | [b3597a7cbc](https://linux-hardware.org/?probe=b3597a7cbc) | Oct 10, 2022 |
| Acer          | Aspire 4739Z                | Notebook    | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | Desktop     | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Toshiba       | Satellite C655D             | Notebook    | [80ec8503c0](https://linux-hardware.org/?probe=80ec8503c0) | Oct 05, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [1ad22cf7a8](https://linux-hardware.org/?probe=1ad22cf7a8) | Sep 28, 2022 |
| Dell          | 0PU052                      | Desktop     | [2890a8407e](https://linux-hardware.org/?probe=2890a8407e) | Sep 28, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | Notebook    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Dell          | 0R849J A00                  | Desktop     | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| ASUSTek       | UX360CAK                    | Convertible | [015df11bc4](https://linux-hardware.org/?probe=015df11bc4) | Sep 25, 2022 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [cf8128637b](https://linux-hardware.org/?probe=cf8128637b) | Sep 24, 2022 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [e63b24acc3](https://linux-hardware.org/?probe=e63b24acc3) | Sep 24, 2022 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3468d8c911](https://linux-hardware.org/?probe=3468d8c911) | Sep 24, 2022 |
| Dell          | 0PU052                      | Desktop     | [6ca93366df](https://linux-hardware.org/?probe=6ca93366df) | Sep 23, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| ASUSTek       | X451CA                      | Notebook    | [bdfe92eb66](https://linux-hardware.org/?probe=bdfe92eb66) | Sep 21, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c45724d6d3](https://linux-hardware.org/?probe=c45724d6d3) | Sep 20, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2f9ab4273a](https://linux-hardware.org/?probe=2f9ab4273a) | Sep 20, 2022 |
| Gateway       | NE46R                       | Notebook    | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | Notebook    | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Star Labs     | Lite                        | Notebook    | [c08b209f09](https://linux-hardware.org/?probe=c08b209f09) | Sep 09, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | Notebook    | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Acer          | AOA150                      | Notebook    | [3146707963](https://linux-hardware.org/?probe=3146707963) | Sep 02, 2022 |
| Dell          | 0J584C A00                  | Desktop     | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [7763040d56](https://linux-hardware.org/?probe=7763040d56) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Standard      | AHV                         | Notebook    | [1a4d477350](https://linux-hardware.org/?probe=1a4d477350) | Aug 24, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| ASRock        | A520M-HVS                   | Desktop     | [842ad7d4d2](https://linux-hardware.org/?probe=842ad7d4d2) | Aug 22, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [df6dff3fa3](https://linux-hardware.org/?probe=df6dff3fa3) | Aug 19, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | Notebook    | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| Intel         | W7650                       | Notebook    | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| OEM           | Unknown                     | Notebook    | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [98c601bb55](https://linux-hardware.org/?probe=98c601bb55) | Aug 08, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [01e4feaac6](https://linux-hardware.org/?probe=01e4feaac6) | Aug 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 8768 A                      | Desktop     | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | Desktop     | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | Desktop     | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [49ba856687](https://linux-hardware.org/?probe=49ba856687) | Aug 03, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| HP            | 240 G8 Notebook PC          | Notebook    | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [515c5375c1](https://linux-hardware.org/?probe=515c5375c1) | Jul 31, 2022 |
| Google        | Celes                       | Notebook    | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Google        | Celes                       | Notebook    | [fae813e4dc](https://linux-hardware.org/?probe=fae813e4dc) | Jul 31, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Toshiba       | NB250                       | Notebook    | [e320782bcf](https://linux-hardware.org/?probe=e320782bcf) | Jul 30, 2022 |
| HP            | Presario CQ56               | Notebook    | [aead18fee1](https://linux-hardware.org/?probe=aead18fee1) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [894bf232f8](https://linux-hardware.org/?probe=894bf232f8) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [eb752c319e](https://linux-hardware.org/?probe=eb752c319e) | Jul 28, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Dell          | 0X8582                      | Desktop     | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [3451f0e8b5](https://linux-hardware.org/?probe=3451f0e8b5) | Jul 26, 2022 |
| ASRock        | M3A785GMH/128M              | Desktop     | [87836918b2](https://linux-hardware.org/?probe=87836918b2) | Jul 25, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| ASUSTek       | 900                         | Notebook    | [ae42d40b7a](https://linux-hardware.org/?probe=ae42d40b7a) | Jul 25, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [55d8e5a779](https://linux-hardware.org/?probe=55d8e5a779) | Jul 24, 2022 |
| Sony          | VPCEB15FM                   | Notebook    | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [826672a49e](https://linux-hardware.org/?probe=826672a49e) | Jul 22, 2022 |
| Dell          | 0X8582                      | Desktop     | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [cb9ba02bb3](https://linux-hardware.org/?probe=cb9ba02bb3) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | Desktop     | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| Samsung       | N130                        | Notebook    | [4874e0173d](https://linux-hardware.org/?probe=4874e0173d) | Jul 17, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [21b83125d8](https://linux-hardware.org/?probe=21b83125d8) | Jul 14, 2022 |
| Standard      | AHV                         | Notebook    | [2499cab6bd](https://linux-hardware.org/?probe=2499cab6bd) | Jul 12, 2022 |
| Nokia         | Booklet 3G                  | Notebook    | [08b1b304ae](https://linux-hardware.org/?probe=08b1b304ae) | Jul 11, 2022 |
| Foxconn       | 2ACA                        | Desktop     | [92681ef1e5](https://linux-hardware.org/?probe=92681ef1e5) | Jul 07, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| HP            | 1495                        | Desktop     | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [dd80f74e85](https://linux-hardware.org/?probe=dd80f74e85) | Jul 05, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [69e4341e99](https://linux-hardware.org/?probe=69e4341e99) | Jul 05, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| HP            | 1495                        | Desktop     | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [92c11e77c4](https://linux-hardware.org/?probe=92c11e77c4) | Jul 03, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| MSI           | VR630                       | Notebook    | [097cd732b3](https://linux-hardware.org/?probe=097cd732b3) | Jun 27, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [a27f696a28](https://linux-hardware.org/?probe=a27f696a28) | Jun 27, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [357e062693](https://linux-hardware.org/?probe=357e062693) | Jun 25, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [f6f825d83a](https://linux-hardware.org/?probe=f6f825d83a) | Jun 22, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| HP            | Notebook                    | Notebook    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| Gateway       | Sonic-C                     | Notebook    | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| Dell          | Latitude XT                 | Notebook    | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | Notebook    | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [14ed78a258](https://linux-hardware.org/?probe=14ed78a258) | Jun 11, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Notebook                    | Notebook    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| MSI           | MS-AA1511                   | All in one  | [80c9ccb7c7](https://linux-hardware.org/?probe=80c9ccb7c7) | Jun 06, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Intel         | W7650                       | Notebook    | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | G62                         | Notebook    | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| HP            | 3397                        | Desktop     | [2f3fb08195](https://linux-hardware.org/?probe=2f3fb08195) | Jun 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [8350bd6d87](https://linux-hardware.org/?probe=8350bd6d87) | May 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [63ccee44b1](https://linux-hardware.org/?probe=63ccee44b1) | May 28, 2022 |
| HP            | Berknip                     | Notebook    | [c81d3442c2](https://linux-hardware.org/?probe=c81d3442c2) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [9fa4c6beef](https://linux-hardware.org/?probe=9fa4c6beef) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| ASUSTek       | X402CA                      | Notebook    | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [942f142f46](https://linux-hardware.org/?probe=942f142f46) | May 20, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [9254de4361](https://linux-hardware.org/?probe=9254de4361) | May 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [e7a84a12e6](https://linux-hardware.org/?probe=e7a84a12e6) | May 16, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [7807aa5ed4](https://linux-hardware.org/?probe=7807aa5ed4) | May 16, 2022 |
| Google        | Terra                       | Notebook    | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Dell          | 0CRH6C A00                  | Desktop     | [fe2648c1f7](https://linux-hardware.org/?probe=fe2648c1f7) | May 14, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [68ee4b094a](https://linux-hardware.org/?probe=68ee4b094a) | May 13, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [5774e3f483](https://linux-hardware.org/?probe=5774e3f483) | May 12, 2022 |
| Acer          | Aspire A317-33              | Notebook    | [f3bd3e55aa](https://linux-hardware.org/?probe=f3bd3e55aa) | May 12, 2022 |
| Acer          | Aspire A317-33              | Notebook    | [3a09364bb2](https://linux-hardware.org/?probe=3a09364bb2) | May 12, 2022 |
| Toshiba       | Satellite P20               | Notebook    | [923779da79](https://linux-hardware.org/?probe=923779da79) | May 11, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Positivo      | AT300b                      | Notebook    | [7f5c5ceed4](https://linux-hardware.org/?probe=7f5c5ceed4) | May 11, 2022 |
| ASUSTek       | Rampage III GENE            | Desktop     | [798c1f07f6](https://linux-hardware.org/?probe=798c1f07f6) | May 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | Notebook    | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| ASUSTek       | 900                         | Notebook    | [6cbd0391b3](https://linux-hardware.org/?probe=6cbd0391b3) | May 07, 2022 |
| Intel         | W7650                       | Notebook    | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [8ff47b2a2c](https://linux-hardware.org/?probe=8ff47b2a2c) | May 05, 2022 |
| Toshiba       | Satellite C670D-12N         | Notebook    | [f6bd692d1f](https://linux-hardware.org/?probe=f6bd692d1f) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [4682643304](https://linux-hardware.org/?probe=4682643304) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [5a36e4d0fc](https://linux-hardware.org/?probe=5a36e4d0fc) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bf9f724f45](https://linux-hardware.org/?probe=bf9f724f45) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [05585fedf4](https://linux-hardware.org/?probe=05585fedf4) | May 04, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [bc88bd7582](https://linux-hardware.org/?probe=bc88bd7582) | May 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [afad13fa01](https://linux-hardware.org/?probe=afad13fa01) | May 04, 2022 |
| Acer          | Aspire XC100A               | Desktop     | [dbad5c417d](https://linux-hardware.org/?probe=dbad5c417d) | May 04, 2022 |
| ASUSTek       | 900                         | Notebook    | [70b70a4392](https://linux-hardware.org/?probe=70b70a4392) | May 03, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [dd1df3c77d](https://linux-hardware.org/?probe=dd1df3c77d) | May 02, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [c206790d1e](https://linux-hardware.org/?probe=c206790d1e) | May 01, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [2dffdad8a4](https://linux-hardware.org/?probe=2dffdad8a4) | May 01, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [d44c4fd567](https://linux-hardware.org/?probe=d44c4fd567) | Apr 29, 2022 |
| HP            | Pavilion g4                 | Notebook    | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6c4d2173a5](https://linux-hardware.org/?probe=6c4d2173a5) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a547974d27](https://linux-hardware.org/?probe=a547974d27) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [7be2e51c84](https://linux-hardware.org/?probe=7be2e51c84) | Apr 27, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [753e3fda7d](https://linux-hardware.org/?probe=753e3fda7d) | Apr 26, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [727b677ecb](https://linux-hardware.org/?probe=727b677ecb) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| Gigabyte      | M912                        | Notebook    | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [b921f6fbae](https://linux-hardware.org/?probe=b921f6fbae) | Apr 24, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [705fbe0501](https://linux-hardware.org/?probe=705fbe0501) | Apr 23, 2022 |
| Mediacom      | GTZS                        | Notebook    | [41939828a4](https://linux-hardware.org/?probe=41939828a4) | Apr 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [c8f16c0d16](https://linux-hardware.org/?probe=c8f16c0d16) | Apr 22, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [12d817136f](https://linux-hardware.org/?probe=12d817136f) | Apr 22, 2022 |
| Google        | Droid                       | Notebook    | [b7b4dc6117](https://linux-hardware.org/?probe=b7b4dc6117) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ff77bbf8ae](https://linux-hardware.org/?probe=ff77bbf8ae) | Apr 22, 2022 |
| Mediacom      | GTZS                        | Notebook    | [edc22ef82a](https://linux-hardware.org/?probe=edc22ef82a) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| HP            | Pavilion dv4                | Notebook    | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Intel         | W7650                       | Notebook    | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [9d280b4678](https://linux-hardware.org/?probe=9d280b4678) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| Dell          | Latitude E6410              | Notebook    | [e5e350a4a8](https://linux-hardware.org/?probe=e5e350a4a8) | Apr 13, 2022 |
| Google        | Kip                         | Notebook    | [4641a94428](https://linux-hardware.org/?probe=4641a94428) | Apr 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [1a369ad73a](https://linux-hardware.org/?probe=1a369ad73a) | Apr 12, 2022 |
| ASRock        | G31M-S                      | Desktop     | [e02bbd85b4](https://linux-hardware.org/?probe=e02bbd85b4) | Apr 10, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [725f548eab](https://linux-hardware.org/?probe=725f548eab) | Apr 09, 2022 |
| Samsung       | 950QDB                      | Convertible | [41d1bb5ecf](https://linux-hardware.org/?probe=41d1bb5ecf) | Apr 08, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [a09ecdae05](https://linux-hardware.org/?probe=a09ecdae05) | Apr 07, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [0aac536dbf](https://linux-hardware.org/?probe=0aac536dbf) | Apr 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Gigabyte      | Q77M-D2H                    | Desktop     | [ecbd26a0e1](https://linux-hardware.org/?probe=ecbd26a0e1) | Apr 02, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Samsung       | N100SP                      | Notebook    | [6a70399256](https://linux-hardware.org/?probe=6a70399256) | Mar 31, 2022 |
| Acer          | AOA150                      | Notebook    | [a59a005250](https://linux-hardware.org/?probe=a59a005250) | Mar 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [926a8980fc](https://linux-hardware.org/?probe=926a8980fc) | Mar 30, 2022 |
| Intel         | W7650                       | Notebook    | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | Desktop     | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [abdf251dcf](https://linux-hardware.org/?probe=abdf251dcf) | Mar 25, 2022 |
| Haier         | U1520EM                     | Notebook    | [5fde1c39e9](https://linux-hardware.org/?probe=5fde1c39e9) | Mar 25, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [ab84e23108](https://linux-hardware.org/?probe=ab84e23108) | Mar 24, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [af80d44a27](https://linux-hardware.org/?probe=af80d44a27) | Mar 23, 2022 |
| HP            | Pavilion g7                 | Notebook    | [2c480cdfac](https://linux-hardware.org/?probe=2c480cdfac) | Mar 22, 2022 |
| IBM           | Unknown                     | Notebook    | [2bcbb8a946](https://linux-hardware.org/?probe=2bcbb8a946) | Mar 21, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [a3f94c2957](https://linux-hardware.org/?probe=a3f94c2957) | Mar 20, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [d4c7ecbc5e](https://linux-hardware.org/?probe=d4c7ecbc5e) | Mar 20, 2022 |
| Acer          | AO751h                      | Notebook    | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| Google        | Celes                       | Notebook    | [cfcec68610](https://linux-hardware.org/?probe=cfcec68610) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [37a24fa0b8](https://linux-hardware.org/?probe=37a24fa0b8) | Mar 13, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [707be96775](https://linux-hardware.org/?probe=707be96775) | Mar 13, 2022 |
| ASUSTek       | X550LA                      | Notebook    | [eb7071ed13](https://linux-hardware.org/?probe=eb7071ed13) | Mar 12, 2022 |
| Nvidia        | Tegra                       | Soc         | [3f369fa012](https://linux-hardware.org/?probe=3f369fa012) | Mar 11, 2022 |
| ASRock        | Q1900M                      | Desktop     | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [0e1398474c](https://linux-hardware.org/?probe=0e1398474c) | Mar 09, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | Notebook    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| ASUSTek       | M2N-SLI                     | Desktop     | [675f15b6db](https://linux-hardware.org/?probe=675f15b6db) | Mar 07, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [7a4a682f45](https://linux-hardware.org/?probe=7a4a682f45) | Mar 07, 2022 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [9c8ac31778](https://linux-hardware.org/?probe=9c8ac31778) | Mar 07, 2022 |
| HP            | 3647h                       | Desktop     | [11858412ec](https://linux-hardware.org/?probe=11858412ec) | Mar 06, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [efc41b55f4](https://linux-hardware.org/?probe=efc41b55f4) | Mar 06, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [ac36138ae4](https://linux-hardware.org/?probe=ac36138ae4) | Mar 04, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [96416af97f](https://linux-hardware.org/?probe=96416af97f) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [31efa1bb6f](https://linux-hardware.org/?probe=31efa1bb6f) | Mar 03, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [1da1f4ab04](https://linux-hardware.org/?probe=1da1f4ab04) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [6a97a96f56](https://linux-hardware.org/?probe=6a97a96f56) | Mar 01, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [9d63b9e47f](https://linux-hardware.org/?probe=9d63b9e47f) | Mar 01, 2022 |
| HP            | 339A                        | Desktop     | [820ebf5859](https://linux-hardware.org/?probe=820ebf5859) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9a59eff157](https://linux-hardware.org/?probe=9a59eff157) | Feb 26, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [f07aaa2fd3](https://linux-hardware.org/?probe=f07aaa2fd3) | Feb 25, 2022 |
| Insyde        | N116                        | Notebook    | [a6dd43dfb4](https://linux-hardware.org/?probe=a6dd43dfb4) | Feb 21, 2022 |
| HP            | 2AF7                        | Desktop     | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [8551d043a9](https://linux-hardware.org/?probe=8551d043a9) | Feb 20, 2022 |
| Dell          | 0DR845                      | Desktop     | [73ab1563bc](https://linux-hardware.org/?probe=73ab1563bc) | Feb 18, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Intel         | W7650                       | Notebook    | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |
| Alienware     | M17                         | Notebook    | [9d29db918d](https://linux-hardware.org/?probe=9d29db918d) | Feb 18, 2022 |
| Pegatron      | Narra6                      | Desktop     | [712b5069b6](https://linux-hardware.org/?probe=712b5069b6) | Feb 17, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5601a4d596](https://linux-hardware.org/?probe=5601a4d596) | Feb 14, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [c70891d986](https://linux-hardware.org/?probe=c70891d986) | Feb 14, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [27e20ff1d8](https://linux-hardware.org/?probe=27e20ff1d8) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | Notebook    | [1f9694d47d](https://linux-hardware.org/?probe=1f9694d47d) | Feb 12, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [677d24e366](https://linux-hardware.org/?probe=677d24e366) | Feb 11, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a72979e0f8](https://linux-hardware.org/?probe=a72979e0f8) | Feb 11, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [3731e90788](https://linux-hardware.org/?probe=3731e90788) | Feb 11, 2022 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [b3977cd496](https://linux-hardware.org/?probe=b3977cd496) | Feb 10, 2022 |
| Positivo      | N600                        | Notebook    | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| Dell          | Latitude E5540              | Notebook    | [e895dcce0f](https://linux-hardware.org/?probe=e895dcce0f) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [9c5efed237](https://linux-hardware.org/?probe=9c5efed237) | Feb 06, 2022 |
| ASUSTek       | Puffer                      | Desktop     | [a14c8ed9ad](https://linux-hardware.org/?probe=a14c8ed9ad) | Feb 06, 2022 |
| Unknown       | 865G-M8                     | Desktop     | [ecc67cf3bc](https://linux-hardware.org/?probe=ecc67cf3bc) | Feb 06, 2022 |
| Lenovo        | 3000 N200 0769ALU           | Notebook    | [695855f143](https://linux-hardware.org/?probe=695855f143) | Feb 05, 2022 |
| Lenovo        | 3000 N200 0769ALU           | Notebook    | [661ffedd80](https://linux-hardware.org/?probe=661ffedd80) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4c355aa7c2](https://linux-hardware.org/?probe=4c355aa7c2) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [61fc6b2cb0](https://linux-hardware.org/?probe=61fc6b2cb0) | Feb 05, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1a0186c0a7](https://linux-hardware.org/?probe=1a0186c0a7) | Feb 04, 2022 |
| HP            | 0A80h                       | Desktop     | [ad7e41ed45](https://linux-hardware.org/?probe=ad7e41ed45) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | Desktop     | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| Toshiba       | Satellite C875              | Notebook    | [1dd31ebdd6](https://linux-hardware.org/?probe=1dd31ebdd6) | Feb 02, 2022 |
| Insyde        | i101c                       | Notebook    | [375f7e61b2](https://linux-hardware.org/?probe=375f7e61b2) | Feb 02, 2022 |
| Dell          | 0FJM8V A03                  | Server      | [398f8f6326](https://linux-hardware.org/?probe=398f8f6326) | Feb 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2J000    | Notebook    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [5adcd620f6](https://linux-hardware.org/?probe=5adcd620f6) | Jan 30, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| Google        | Peppy                       | Notebook    | [15cd563f21](https://linux-hardware.org/?probe=15cd563f21) | Jan 27, 2022 |
| HP            | 3048h                       | Desktop     | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| ASUSTek       | GL553VW                     | Notebook    | [7713319e74](https://linux-hardware.org/?probe=7713319e74) | Jan 24, 2022 |
| HP            | 3048h                       | Desktop     | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Pegatron      | EVE                         | Desktop     | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | Desktop     | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [433e46caa5](https://linux-hardware.org/?probe=433e46caa5) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [f88ac2dd3e](https://linux-hardware.org/?probe=f88ac2dd3e) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [6c56c2c8b3](https://linux-hardware.org/?probe=6c56c2c8b3) | Jan 19, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [1aa2cd2e8f](https://linux-hardware.org/?probe=1aa2cd2e8f) | Jan 19, 2022 |
| Dell          | Inspiron 15-3573            | Notebook    | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [804b4adedc](https://linux-hardware.org/?probe=804b4adedc) | Jan 15, 2022 |
| Unknown       | K8Upgrade-1689              | Desktop     | [d2e29b9e82](https://linux-hardware.org/?probe=d2e29b9e82) | Jan 15, 2022 |
| Dell          | 07N90W A01                  | Desktop     | [c8db7d01bd](https://linux-hardware.org/?probe=c8db7d01bd) | Jan 15, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| Nvidia        | Tegra                       | Soc         | [143a4e3c60](https://linux-hardware.org/?probe=143a4e3c60) | Jan 13, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [79e8f681f1](https://linux-hardware.org/?probe=79e8f681f1) | Jan 13, 2022 |
| HP            | Notebook                    | Notebook    | [847afd8ac5](https://linux-hardware.org/?probe=847afd8ac5) | Jan 12, 2022 |
| Acer          | WG43M                       | Desktop     | [af76e9bcfe](https://linux-hardware.org/?probe=af76e9bcfe) | Jan 12, 2022 |
| Acer          | WG43M                       | Desktop     | [5784b66aee](https://linux-hardware.org/?probe=5784b66aee) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [e41c34594e](https://linux-hardware.org/?probe=e41c34594e) | Jan 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4c24369bb7](https://linux-hardware.org/?probe=4c24369bb7) | Jan 11, 2022 |
| System76      | Lemur Pro                   | Notebook    | [fa22d4610e](https://linux-hardware.org/?probe=fa22d4610e) | Jan 11, 2022 |
| Positivo      | N600                        | Notebook    | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [9bd6fe4b7c](https://linux-hardware.org/?probe=9bd6fe4b7c) | Jan 08, 2022 |
| HP            | Compaq 6910p (GX316UC#AB... | Notebook    | [0ffa23c15e](https://linux-hardware.org/?probe=0ffa23c15e) | Jan 07, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [e253741d9f](https://linux-hardware.org/?probe=e253741d9f) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [66d00e2cd5](https://linux-hardware.org/?probe=66d00e2cd5) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [7cf1327087](https://linux-hardware.org/?probe=7cf1327087) | Jan 05, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| HP            | Pavilion dv2700             | Notebook    | [c8aafbbc8d](https://linux-hardware.org/?probe=c8aafbbc8d) | Jan 04, 2022 |
| Alienware     | m15                         | Notebook    | [a0d4f93250](https://linux-hardware.org/?probe=a0d4f93250) | Jan 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [eaf2e708d9](https://linux-hardware.org/?probe=eaf2e708d9) | Jan 03, 2022 |
| Acer          | Aspire 7715Z                | Notebook    | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| Lanix         | NeuronALV5                  | Notebook    | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| Dell          | Latitude 7480               | Notebook    | [a338b67d45](https://linux-hardware.org/?probe=a338b67d45) | Dec 30, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [0211323709](https://linux-hardware.org/?probe=0211323709) | Dec 28, 2021 |
| Dell          | Inspiron 15 3515            | Notebook    | [8d130910ab](https://linux-hardware.org/?probe=8d130910ab) | Dec 26, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [f5924cb8b4](https://linux-hardware.org/?probe=f5924cb8b4) | Dec 25, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [d8d2b553bf](https://linux-hardware.org/?probe=d8d2b553bf) | Dec 24, 2021 |
| ASUSTek       | A8N5X                       | Desktop     | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ea7740294a](https://linux-hardware.org/?probe=ea7740294a) | Dec 24, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| HP            | 090Ch                       | Desktop     | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| Acer          | AOA150                      | Notebook    | [47cae573c1](https://linux-hardware.org/?probe=47cae573c1) | Dec 22, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [c5c7ca1d56](https://linux-hardware.org/?probe=c5c7ca1d56) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [2e9fd50292](https://linux-hardware.org/?probe=2e9fd50292) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [452b8c0ac4](https://linux-hardware.org/?probe=452b8c0ac4) | Dec 20, 2021 |
| Dell          | Latitude E6520              | Notebook    | [c7edb79be7](https://linux-hardware.org/?probe=c7edb79be7) | Dec 20, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [c52d7dc596](https://linux-hardware.org/?probe=c52d7dc596) | Dec 17, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [a58123c368](https://linux-hardware.org/?probe=a58123c368) | Dec 17, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [175dda01f6](https://linux-hardware.org/?probe=175dda01f6) | Dec 15, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [b956646608](https://linux-hardware.org/?probe=b956646608) | Dec 12, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [7cf21876b0](https://linux-hardware.org/?probe=7cf21876b0) | Dec 12, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [950da990e7](https://linux-hardware.org/?probe=950da990e7) | Dec 12, 2021 |
| ASUSTek       | 1015BXO                     | Notebook    | [f9eb963d74](https://linux-hardware.org/?probe=f9eb963d74) | Dec 12, 2021 |
| MSI           | Katana GF76 11UC            | Notebook    | [73fd53a50c](https://linux-hardware.org/?probe=73fd53a50c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| Positivo      | AT300b                      | Notebook    | [20b3635188](https://linux-hardware.org/?probe=20b3635188) | Dec 06, 2021 |
| HP            | Compaq 6510b (GR691EA#AB... | Notebook    | [4d657211eb](https://linux-hardware.org/?probe=4d657211eb) | Dec 04, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ddafe324b7](https://linux-hardware.org/?probe=ddafe324b7) | Dec 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [e9b454a745](https://linux-hardware.org/?probe=e9b454a745) | Dec 04, 2021 |
| MSI           | Boston                      | Desktop     | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| HP            | 1497                        | Desktop     | [f848ad29cd](https://linux-hardware.org/?probe=f848ad29cd) | Dec 04, 2021 |
| Acer          | AOD255E                     | Notebook    | [390afd35cb](https://linux-hardware.org/?probe=390afd35cb) | Dec 03, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [155ec30920](https://linux-hardware.org/?probe=155ec30920) | Dec 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [b096d0494e](https://linux-hardware.org/?probe=b096d0494e) | Dec 02, 2021 |
| Gigabyte      | P35-DS3L                    | Desktop     | [2e5a8410bc](https://linux-hardware.org/?probe=2e5a8410bc) | Dec 01, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [edce40927f](https://linux-hardware.org/?probe=edce40927f) | Dec 01, 2021 |
| Toshiba       | Satellite C50-A-19U         | Notebook    | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| ASUSTek       | CM1435                      | Desktop     | [febd571863](https://linux-hardware.org/?probe=febd571863) | Nov 28, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Lubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Lubuntu 20.04    | 453       | 31.44%  |
| Lubuntu 22.04    | 370       | 25.68%  |
| Lubuntu 18.04    | 216       | 14.99%  |
| Lubuntu 21.10    | 80        | 5.55%   |
| Lubuntu 19.10    | 62        | 4.3%    |
| Lubuntu 21.04    | 52        | 3.61%   |
| Lubuntu 20.10    | 48        | 3.33%   |
| Lubuntu 22.10    | 44        | 3.05%   |
| Lubuntu 23.04    | 35        | 2.43%   |
| Lubuntu 16.04    | 31        | 2.15%   |
| Lubuntu 19.04    | 14        | 0.97%   |
| Lubuntu 18.10    | 13        | 0.9%    |
| Lubuntu 23.10    | 12        | 0.83%   |
| Lubuntu          | 3         | 0.21%   |
| Lubuntu 16.10    | 2         | 0.14%   |
| Lubuntu 20.04.1  | 1         | 0.07%   |
| Lubuntu 18.04.05 | 1         | 0.07%   |
| Lubuntu 17.10    | 1         | 0.07%   |
| Lubuntu 17.04    | 1         | 0.07%   |
| Lubuntu 13.04    | 1         | 0.07%   |
| Lubuntu 12.04    | 1         | 0.07%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lubuntu | 1396      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 38        | 2.41%   |
| 5.15.0-43-generic | 37        | 2.34%   |
| 5.4.0-52-generic  | 24        | 1.52%   |
| 5.15.0-56-generic | 21        | 1.33%   |
| 5.13.0-19-generic | 18        | 1.14%   |
| 5.15.0-25-generic | 17        | 1.08%   |
| 5.15.0-60-generic | 16        | 1.01%   |
| 5.13.0-40-generic | 16        | 1.01%   |
| 5.13.0-28-generic | 16        | 1.01%   |
| 5.19.0-32-generic | 15        | 0.95%   |
| 5.15.0-46-generic | 15        | 0.95%   |
| 5.4.0-48-generic  | 14        | 0.89%   |
| 5.4.0-47-generic  | 14        | 0.89%   |
| 5.3.0-46-generic  | 14        | 0.89%   |
| 5.15.0-41-generic | 14        | 0.89%   |
| 5.11.0-16-generic | 14        | 0.89%   |
| 5.11.0-27-generic | 13        | 0.82%   |
| 6.2.0-26-generic  | 12        | 0.76%   |
| 5.4.0-54-generic  | 12        | 0.76%   |
| 5.4.0-26-generic  | 12        | 0.76%   |
| 5.19.0-41-generic | 12        | 0.76%   |
| 5.19.0-35-generic | 12        | 0.76%   |
| 5.15.0-58-generic | 12        | 0.76%   |
| 5.15.0-47-generic | 12        | 0.76%   |
| 5.13.0-30-generic | 12        | 0.76%   |
| 6.2.0-34-generic  | 11        | 0.7%    |
| 5.8.0-50-generic  | 11        | 0.7%    |
| 5.4.0-73-generic  | 11        | 0.7%    |
| 5.4.0-40-generic  | 11        | 0.7%    |
| 5.15.0-53-generic | 11        | 0.7%    |
| 5.15.0-52-generic | 11        | 0.7%    |
| 5.15.0-30-generic | 11        | 0.7%    |
| 5.13.0-35-generic | 11        | 0.7%    |
| 5.4.0-29-generic  | 10        | 0.63%   |
| 5.3.0-18-generic  | 10        | 0.63%   |
| 5.19.0-46-generic | 10        | 0.63%   |
| 4.15.0-91-generic | 10        | 0.63%   |
| 6.2.0-20-generic  | 9         | 0.57%   |
| 5.8.0-63-generic  | 9         | 0.57%   |
| 5.4.0-72-generic  | 9         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 328       | 22.47%  |
| 5.15.0  | 282       | 19.32%  |
| 4.15.0  | 144       | 9.86%   |
| 5.13.0  | 118       | 8.08%   |
| 5.19.0  | 110       | 7.53%   |
| 5.11.0  | 101       | 6.92%   |
| 5.8.0   | 99        | 6.78%   |
| 5.3.0   | 86        | 5.89%   |
| 6.2.0   | 81        | 5.55%   |
| 5.0.0   | 22        | 1.51%   |
| 4.18.0  | 13        | 0.89%   |
| 6.5.0   | 12        | 0.82%   |
| 4.4.0   | 8         | 0.55%   |
| 6.1.0   | 3         | 0.21%   |
| 5.6.0   | 2         | 0.14%   |
| 5.4.30  | 2         | 0.14%   |
| 5.14.0  | 2         | 0.14%   |
| 4.9.253 | 2         | 0.14%   |
| 4.8.0   | 2         | 0.14%   |
| 4.13.0  | 2         | 0.14%   |
| 4.10.0  | 2         | 0.14%   |
| 6.5.8   | 1         | 0.07%   |
| 6.5.1   | 1         | 0.07%   |
| 6.4.12  | 1         | 0.07%   |
| 6.3.3   | 1         | 0.07%   |
| 6.2.8   | 1         | 0.07%   |
| 6.2.6   | 1         | 0.07%   |
| 6.1.6   | 1         | 0.07%   |
| 6.1.46  | 1         | 0.07%   |
| 6.1.3   | 1         | 0.07%   |
| 6.1.26  | 1         | 0.07%   |
| 6.1.12  | 1         | 0.07%   |
| 6.0.9   | 1         | 0.07%   |
| 6.0.8   | 1         | 0.07%   |
| 6.0.14  | 1         | 0.07%   |
| 6.0.12  | 1         | 0.07%   |
| 6.0.10  | 1         | 0.07%   |
| 6.0.0   | 1         | 0.07%   |
| 5.9.0   | 1         | 0.07%   |
| 5.7.9   | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 330       | 22.6%   |
| 5.15    | 283       | 19.38%  |
| 4.15    | 145       | 9.93%   |
| 5.13    | 118       | 8.08%   |
| 5.19    | 112       | 7.67%   |
| 5.11    | 101       | 6.92%   |
| 5.8     | 99        | 6.78%   |
| 5.3     | 87        | 5.96%   |
| 6.2     | 83        | 5.68%   |
| 5.0     | 22        | 1.51%   |
| 6.5     | 14        | 0.96%   |
| 4.18    | 13        | 0.89%   |
| 6.1     | 8         | 0.55%   |
| 4.4     | 8         | 0.55%   |
| 6.0     | 6         | 0.41%   |
| 5.6     | 3         | 0.21%   |
| 4.9     | 3         | 0.21%   |
| 4.13    | 3         | 0.21%   |
| 5.7     | 2         | 0.14%   |
| 5.16    | 2         | 0.14%   |
| 5.14    | 2         | 0.14%   |
| 5.10    | 2         | 0.14%   |
| 4.8     | 2         | 0.14%   |
| 4.10    | 2         | 0.14%   |
| 6.4     | 1         | 0.07%   |
| 6.3     | 1         | 0.07%   |
| 5.9     | 1         | 0.07%   |
| 5.5     | 1         | 0.07%   |
| 5.18    | 1         | 0.07%   |
| 5.12    | 1         | 0.07%   |
| 4.20    | 1         | 0.07%   |
| 4.14    | 1         | 0.07%   |
| 3.13    | 1         | 0.07%   |
| 3.1     | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1255      | 89.9%   |
| i686    | 127       | 9.1%    |
| aarch64 | 11        | 0.79%   |
| armv7l  | 2         | 0.14%   |
| ppc64   | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| LXQt            | 1092      | 77.83%  |
| LXDE            | 240       | 17.11%  |
| Unknown         | 22        | 1.57%   |
| GNOME           | 18        | 1.28%   |
| Openbox         | 7         | 0.5%    |
| X-Cinnamon      | 5         | 0.36%   |
| KDE5            | 4         | 0.29%   |
| Lubuntu         | 3         | 0.21%   |
| XFCE            | 2         | 0.14%   |
| i3              | 2         | 0.14%   |
| GNOME Flashback | 2         | 0.14%   |
| Cinnamon        | 2         | 0.14%   |
| Budgie          | 2         | 0.14%   |
| MATE            | 1         | 0.07%   |
| KDE             | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1350      | 96.22%  |
| Tty         | 40        | 2.85%   |
| Wayland     | 10        | 0.71%   |
| Unknown     | 2         | 0.14%   |
| Unspecified | 1         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 752       | 53.03%  |
| Unknown | 397       | 28%     |
| LightDM | 139       | 9.8%    |
| TDM     | 68        | 4.8%    |
| GDM     | 38        | 2.68%   |
| GDM3    | 18        | 1.27%   |
| XDM     | 3         | 0.21%   |
| LXDM    | 2         | 0.14%   |
| SLiM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 407       | 28.99%  |
| fr_FR   | 131       | 9.33%   |
| pt_BR   | 94        | 6.7%    |
| it_IT   | 87        | 6.2%    |
| en_GB   | 87        | 6.2%    |
| de_DE   | 84        | 5.98%   |
| C       | 67        | 4.77%   |
| ru_RU   | 48        | 3.42%   |
| pl_PL   | 32        | 2.28%   |
| Unknown | 31        | 2.21%   |
| es_ES   | 30        | 2.14%   |
| en_CA   | 27        | 1.92%   |
| en_AU   | 25        | 1.78%   |
| es_AR   | 21        | 1.5%    |
| cs_CZ   | 15        | 1.07%   |
| es_MX   | 14        | 1%      |
| tr_TR   | 13        | 0.93%   |
| hu_HU   | 13        | 0.93%   |
| en_IN   | 12        | 0.85%   |
| en_AG   | 11        | 0.78%   |
| nl_NL   | 10        | 0.71%   |
| ja_JP   | 8         | 0.57%   |
| es_CR   | 8         | 0.57%   |
| fi_FI   | 7         | 0.5%    |
| es_CO   | 7         | 0.5%    |
| nl_BE   | 6         | 0.43%   |
| es_CL   | 6         | 0.43%   |
| el_GR   | 6         | 0.43%   |
| fr_BE   | 5         | 0.36%   |
| es_PE   | 5         | 0.36%   |
| en_IE   | 5         | 0.36%   |
| zh_TW   | 4         | 0.28%   |
| fr_CA   | 4         | 0.28%   |
| es_UY   | 4         | 0.28%   |
| en_ZA   | 4         | 0.28%   |
| en_PH   | 4         | 0.28%   |
| en_NZ   | 4         | 0.28%   |
| pt_PT   | 3         | 0.21%   |
| fr_CH   | 3         | 0.21%   |
| es_VE   | 3         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 898       | 63.78%  |
| EFI  | 510       | 36.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1249      | 88.83%  |
| Overlay | 67        | 4.77%   |
| Tmpfs   | 48        | 3.41%   |
| Btrfs   | 17        | 1.21%   |
| Xfs     | 7         | 0.5%    |
| Aufs    | 5         | 0.36%   |
| Unknown | 5         | 0.36%   |
| Ext3    | 3         | 0.21%   |
| Ext2    | 2         | 0.14%   |
| Zfs     | 1         | 0.07%   |
| XXX4    | 1         | 0.07%   |
| F2fs    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 531       | 37.66%  |
| GPT     | 517       | 36.67%  |
| MBR     | 362       | 25.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1242      | 88.21%  |
| Yes       | 166       | 11.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1013      | 72.1%   |
| Yes       | 392       | 27.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 232       | 16.62%  |
| ASUSTek Computer        | 176       | 12.61%  |
| Lenovo                  | 139       | 9.96%   |
| Dell                    | 139       | 9.96%   |
| Acer                    | 100       | 7.16%   |
| MSI                     | 57        | 4.08%   |
| Gigabyte Technology     | 52        | 3.72%   |
| Toshiba                 | 49        | 3.51%   |
| ASRock                  | 41        | 2.94%   |
| Intel                   | 32        | 2.29%   |
| Apple                   | 30        | 2.15%   |
| Samsung Electronics     | 29        | 2.08%   |
| Unknown                 | 27        | 1.93%   |
| Google                  | 26        | 1.86%   |
| Sony                    | 20        | 1.43%   |
| Positivo                | 19        | 1.36%   |
| Fujitsu                 | 14        | 1%      |
| AMI                     | 12        | 0.86%   |
| Pegatron                | 11        | 0.79%   |
| Packard Bell            | 10        | 0.72%   |
| Mediacom                | 9         | 0.64%   |
| Fujitsu Siemens         | 9         | 0.64%   |
| Foxconn                 | 9         | 0.64%   |
| Raspberry Pi Foundation | 7         | 0.5%    |
| AAEON                   | 6         | 0.43%   |
| Notebook                | 5         | 0.36%   |
| IBM                     | 5         | 0.36%   |
| Gateway                 | 5         | 0.36%   |
| eMachines               | 5         | 0.36%   |
| Biostar                 | 5         | 0.36%   |
| HUAWEI                  | 4         | 0.29%   |
| Alienware               | 4         | 0.29%   |
| TrekStor                | 3         | 0.21%   |
| Thomson                 | 3         | 0.21%   |
| Panasonic               | 3         | 0.21%   |
| OEM                     | 3         | 0.21%   |
| Nvidia                  | 3         | 0.21%   |
| Medion                  | 3         | 0.21%   |
| LG Electronics          | 3         | 0.21%   |
| Insyde                  | 3         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 37        | 2.65%   |
| HP Notebook                           | 11        | 0.79%   |
| HP Pavilion 15                        | 6         | 0.43%   |
| Apple MacBookPro8,1                   | 6         | 0.43%   |
| AAEON MF-001                          | 6         | 0.43%   |
| HP Pavilion g6                        | 5         | 0.36%   |
| HP Pavilion dv6                       | 5         | 0.36%   |
| MSI MS-7C37                           | 4         | 0.29%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 4         | 0.29%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS   | 4         | 0.29%   |
| HP t620 Quad Core TC                  | 4         | 0.29%   |
| Dell OptiPlex 7010                    | 4         | 0.29%   |
| Dell Latitude D630                    | 4         | 0.29%   |
| Apple iMac7,1                         | 4         | 0.29%   |
| Nvidia Tegra                          | 3         | 0.21%   |
| Mediacom WinPad 11,6 FullHD- WPU11    | 3         | 0.21%   |
| Lenovo IdeaPad 320-15AST 80XV         | 3         | 0.21%   |
| Lenovo IdeaPad 100-15IBD 80QQ         | 3         | 0.21%   |
| Lenovo G50-30 80G0                    | 3         | 0.21%   |
| HP ProBook 440 G7                     | 3         | 0.21%   |
| HP Pavilion g7                        | 3         | 0.21%   |
| HP Laptop 15-da0xxx                   | 3         | 0.21%   |
| HP 2000                               | 3         | 0.21%   |
| Google Candy                          | 3         | 0.21%   |
| Dell OptiPlex 790                     | 3         | 0.21%   |
| Dell OptiPlex 755                     | 3         | 0.21%   |
| Dell Inspiron N5010                   | 3         | 0.21%   |
| ASUS V-P8H67E                         | 3         | 0.21%   |
| ASUS All Series                       | 3         | 0.21%   |
| ASUS 1000H                            | 3         | 0.21%   |
| ASRock FM2A85X Extreme6               | 3         | 0.21%   |
| Apple MacBook4,1                      | 3         | 0.21%   |
| Acer Aspire 5742G                     | 3         | 0.21%   |
| Acer Aspire 5735                      | 3         | 0.21%   |
| YASHI MYBOOK 360                      | 2         | 0.14%   |
| Toshiba Satellite L40                 | 2         | 0.14%   |
| Toshiba Satellite L300                | 2         | 0.14%   |
| Toshiba Satellite A205                | 2         | 0.14%   |
| Samsung RV415/RV515                   | 2         | 0.14%   |
| Samsung 275E4E/275E5E                 | 2         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 73        | 5.23%   |
| Lenovo IdeaPad        | 46        | 3.3%    |
| Toshiba Satellite     | 44        | 3.15%   |
| Dell Inspiron         | 44        | 3.15%   |
| Lenovo ThinkPad       | 43        | 3.08%   |
| HP Pavilion           | 43        | 3.08%   |
| HP Compaq             | 39        | 2.79%   |
| Unknown               | 37        | 2.65%   |
| Dell Latitude         | 31        | 2.22%   |
| HP ProBook            | 29        | 2.08%   |
| HP EliteBook          | 21        | 1.5%    |
| Dell OptiPlex         | 21        | 1.5%    |
| HP Laptop             | 17        | 1.22%   |
| Lenovo ThinkCentre    | 14        | 1%      |
| HP Notebook           | 11        | 0.79%   |
| ASUS VivoBook         | 10        | 0.72%   |
| Dell XPS              | 9         | 0.64%   |
| Dell Vostro           | 9         | 0.64%   |
| Fujitsu Siemens AMILO | 8         | 0.57%   |
| RPi Raspberry         | 7         | 0.5%    |
| Packard Bell EasyNote | 7         | 0.5%    |
| Fujitsu LIFEBOOK      | 7         | 0.5%    |
| Dell Precision        | 7         | 0.5%    |
| ASUS PRIME            | 7         | 0.5%    |
| HP t620               | 6         | 0.43%   |
| HP Stream             | 6         | 0.43%   |
| Apple MacBookPro8     | 6         | 0.43%   |
| Acer Extensa          | 6         | 0.43%   |
| AAEON MF-001          | 6         | 0.43%   |
| HP Spectre            | 5         | 0.36%   |
| HP Presario           | 5         | 0.36%   |
| Dell Studio           | 5         | 0.36%   |
| ASUS ROG              | 5         | 0.36%   |
| MSI MS-7C37           | 4         | 0.29%   |
| Mediacom SmartBook    | 4         | 0.29%   |
| HP 255                | 4         | 0.29%   |
| Dell PowerEdge        | 4         | 0.29%   |
| Dell Dimension        | 4         | 0.29%   |
| ASUS M5A97            | 4         | 0.29%   |
| Apple iMac7           | 4         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 126       | 9.03%   |
| 2012    | 115       | 8.24%   |
| 2008    | 109       | 7.81%   |
| 2010    | 105       | 7.52%   |
| 2013    | 98        | 7.02%   |
| 2007    | 91        | 6.52%   |
| 2009    | 81        | 5.8%    |
| 2019    | 75        | 5.37%   |
| 2014    | 74        | 5.3%    |
| 2017    | 71        | 5.09%   |
| 2020    | 68        | 4.87%   |
| 2016    | 66        | 4.73%   |
| 2015    | 63        | 4.51%   |
| 2021    | 60        | 4.3%    |
| 2018    | 53        | 3.8%    |
| 2006    | 49        | 3.51%   |
| 2022    | 36        | 2.58%   |
| 2005    | 18        | 1.29%   |
| Unknown | 13        | 0.93%   |
| 2023    | 12        | 0.86%   |
| 2004    | 6         | 0.43%   |
| 2002    | 3         | 0.21%   |
| 2001    | 2         | 0.14%   |
| 2003    | 1         | 0.07%   |
| 2000    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 862       | 61.75%  |
| Desktop        | 451       | 32.31%  |
| Mini pc        | 20        | 1.43%   |
| Convertible    | 18        | 1.29%   |
| All in one     | 15        | 1.07%   |
| System on chip | 12        | 0.86%   |
| Tablet         | 9         | 0.64%   |
| Server         | 8         | 0.57%   |
| Other          | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1324      | 94.44%  |
| Enabled  | 78        | 5.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1367      | 97.85%  |
| Yes  | 30        | 2.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 425       | 29.99%  |
| 4.01-8.0        | 295       | 20.82%  |
| 1.01-2.0        | 234       | 16.51%  |
| 8.01-16.0       | 159       | 11.22%  |
| 16.01-24.0      | 116       | 8.19%   |
| 2.01-3.0        | 67        | 4.73%   |
| 32.01-64.0      | 47        | 3.32%   |
| 0.51-1.0        | 43        | 3.03%   |
| 24.01-32.0      | 11        | 0.78%   |
| 64.01-256.0     | 10        | 0.71%   |
| 0.01-0.5        | 8         | 0.56%   |
| More than 256.0 | 2         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 656       | 43.97%  |
| 0.51-1.0   | 354       | 23.73%  |
| 2.01-3.0   | 229       | 15.35%  |
| 4.01-8.0   | 95        | 6.37%   |
| 3.01-4.0   | 69        | 4.62%   |
| 0.01-0.5   | 69        | 4.62%   |
| 8.01-16.0  | 15        | 1.01%   |
| 16.01-24.0 | 2         | 0.13%   |
| Unknown    | 2         | 0.13%   |
| 32.01-64.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 958       | 68.04%  |
| 2      | 321       | 22.8%   |
| 3      | 47        | 3.34%   |
| 4      | 29        | 2.06%   |
| 0      | 22        | 1.56%   |
| 5      | 17        | 1.21%   |
| 6      | 5         | 0.36%   |
| 7      | 3         | 0.21%   |
| 8      | 2         | 0.14%   |
| 17     | 1         | 0.07%   |
| 14     | 1         | 0.07%   |
| 12     | 1         | 0.07%   |
| 10     | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 735       | 52.35%  |
| Yes       | 669       | 47.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1197      | 85.56%  |
| No        | 202       | 14.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1050      | 75.05%  |
| No        | 349       | 24.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 758       | 53.61%  |
| Yes       | 656       | 46.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 222       | 15.86%  |
| France       | 135       | 9.64%   |
| Brazil       | 116       | 8.29%   |
| Germany      | 112       | 8%      |
| Italy        | 106       | 7.57%   |
| Russia       | 71        | 5.07%   |
| UK           | 62        | 4.43%   |
| Poland       | 39        | 2.79%   |
| Canada       | 38        | 2.71%   |
| Spain        | 34        | 2.43%   |
| Netherlands  | 29        | 2.07%   |
| Australia    | 23        | 1.64%   |
| Argentina    | 23        | 1.64%   |
| Czechia      | 21        | 1.5%    |
| Indonesia    | 19        | 1.36%   |
| Hungary      | 19        | 1.36%   |
| Turkey       | 18        | 1.29%   |
| Belgium      | 18        | 1.29%   |
| Mexico       | 17        | 1.21%   |
| Finland      | 17        | 1.21%   |
| Switzerland  | 15        | 1.07%   |
| India        | 15        | 1.07%   |
| Ukraine      | 12        | 0.86%   |
| Sweden       | 9         | 0.64%   |
| Costa Rica   | 9         | 0.64%   |
| Colombia     | 9         | 0.64%   |
| Malaysia     | 8         | 0.57%   |
| Ireland      | 8         | 0.57%   |
| Greece       | 8         | 0.57%   |
| South Africa | 7         | 0.5%    |
| Japan        | 7         | 0.5%    |
| Bulgaria     | 7         | 0.5%    |
| Slovakia     | 6         | 0.43%   |
| Portugal     | 6         | 0.43%   |
| Peru         | 6         | 0.43%   |
| Lithuania    | 6         | 0.43%   |
| Chile        | 6         | 0.43%   |
| Vietnam      | 5         | 0.36%   |
| Taiwan       | 5         | 0.36%   |
| Romania      | 5         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 20        | 1.36%   |
| Milan             | 16        | 1.09%   |
| Rome              | 15        | 1.02%   |
| Moscow            | 13        | 0.88%   |
| Melbourne         | 12        | 0.82%   |
| Sao Paulo         | 8         | 0.54%   |
| Prague            | 8         | 0.54%   |
| Oshawa            | 7         | 0.48%   |
| Lyon              | 7         | 0.48%   |
| Heredia           | 7         | 0.48%   |
| Helsinki          | 7         | 0.48%   |
| Bengaluru         | 7         | 0.48%   |
| Zurich            | 6         | 0.41%   |
| Warsaw            | 6         | 0.41%   |
| Rio de Janeiro    | 6         | 0.41%   |
| New York          | 6         | 0.41%   |
| Kyiv              | 6         | 0.41%   |
| Kuala Lumpur      | 6         | 0.41%   |
| Istanbul          | 6         | 0.41%   |
| Budapest          | 6         | 0.41%   |
| Brasília         | 6         | 0.41%   |
| Athens            | 6         | 0.41%   |
| Wellington        | 5         | 0.34%   |
| St Petersburg     | 5         | 0.34%   |
| Porto Alegre      | 5         | 0.34%   |
| Munich            | 5         | 0.34%   |
| Mexico City       | 5         | 0.34%   |
| Madrid            | 5         | 0.34%   |
| Houston           | 5         | 0.34%   |
| Frankfurt am Main | 5         | 0.34%   |
| Bruhl             | 5         | 0.34%   |
| Bogotá           | 5         | 0.34%   |
| Berlin            | 5         | 0.34%   |
| Yekaterinburg     | 4         | 0.27%   |
| Winnipeg          | 4         | 0.27%   |
| Tampere           | 4         | 0.27%   |
| Stuttgart         | 4         | 0.27%   |
| Rio Segundo       | 4         | 0.27%   |
| Hamburg           | 4         | 0.27%   |
| Ghent             | 4         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 293       | 384    | 16.55%  |
| WDC                 | 288       | 383    | 16.27%  |
| Samsung Electronics | 174       | 261    | 9.83%   |
| Unknown             | 155       | 208    | 8.76%   |
| Toshiba             | 120       | 135    | 6.78%   |
| Hitachi             | 111       | 139    | 6.27%   |
| Kingston            | 89        | 105    | 5.03%   |
| SanDisk             | 57        | 63     | 3.22%   |
| Crucial             | 54        | 71     | 3.05%   |
| HGST                | 33        | 39     | 1.86%   |
| Intel               | 28        | 39     | 1.58%   |
| Fujitsu             | 24        | 26     | 1.36%   |
| SK hynix            | 20        | 20     | 1.13%   |
| Micron Technology   | 20        | 21     | 1.13%   |
| A-DATA Technology   | 20        | 22     | 1.13%   |
| Maxtor              | 19        | 21     | 1.07%   |
| China               | 17        | 19     | 0.96%   |
| Unknown             | 17        | 18     | 0.96%   |
| Apacer              | 13        | 13     | 0.73%   |
| Patriot             | 9         | 9      | 0.51%   |
| Transcend           | 8         | 10     | 0.45%   |
| SPCC                | 8         | 11     | 0.45%   |
| PNY                 | 8         | 8      | 0.45%   |
| Silicon Motion      | 7         | 8      | 0.4%    |
| OCZ                 | 7         | 8      | 0.4%    |
| KIOXIA              | 7         | 7      | 0.4%    |
| Apple               | 7         | 14     | 0.4%    |
| LITEONIT            | 6         | 6      | 0.34%   |
| Intenso             | 6         | 6      | 0.34%   |
| LITEON              | 5         | 6      | 0.28%   |
| LDLC                | 5         | 6      | 0.28%   |
| GOODRAM             | 5         | 5      | 0.28%   |
| Corsair             | 5         | 5      | 0.28%   |
| Team                | 4         | 4      | 0.23%   |
| Lexar               | 4         | 4      | 0.23%   |
| KingSpec            | 4         | 6      | 0.23%   |
| JMicron Technology  | 4         | 4      | 0.23%   |
| Hewlett-Packard     | 4         | 9      | 0.23%   |
| TO Exter            | 3         | 3      | 0.17%   |
| Plextor             | 3         | 5      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 31        | 1.62%   |
| Kingston SA400S37240G 240GB SSD     | 25        | 1.3%    |
| Unknown MMC Card  64GB              | 24        | 1.25%   |
| Unknown                             | 17        | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 16        | 0.83%   |
| Seagate ST9500325AS 500GB           | 14        | 0.73%   |
| Seagate ST500LT012-1DG142 500GB     | 13        | 0.68%   |
| Seagate ST500DM002-1BD142 500GB     | 13        | 0.68%   |
| Unknown MMC Card  16GB              | 11        | 0.57%   |
| Toshiba MQ01ABF050 500GB            | 11        | 0.57%   |
| Toshiba MQ01ABD100 1TB              | 11        | 0.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 11        | 0.57%   |
| Seagate ST1000LM035-1RK172 1TB      | 11        | 0.57%   |
| Samsung SSD 850 EVO 250GB           | 11        | 0.57%   |
| Kingston SA400S37120G 120GB SSD     | 11        | 0.57%   |
| Unknown SD/MMC/MS PRO 128GB         | 10        | 0.52%   |
| Unknown NCard  32GB                 | 9         | 0.47%   |
| Kingston SA400S37480G 480GB SSD     | 9         | 0.47%   |
| Crucial CT240BX500SSD1 240GB        | 9         | 0.47%   |
| SanDisk DF4032  32GB                | 8         | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 7         | 0.37%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 7         | 0.37%   |
| Unknown DA4064  64GB                | 7         | 0.37%   |
| Seagate ST1000DM010-2EP102 1TB      | 7         | 0.37%   |
| Seagate Expansion 1TB               | 7         | 0.37%   |
| Toshiba MQ01ABD050 500GB            | 6         | 0.31%   |
| Seagate ST9250315AS 250GB           | 6         | 0.31%   |
| Seagate ST3500418AS 500GB           | 6         | 0.31%   |
| Seagate ST2000DM008-2FR102 2TB      | 6         | 0.31%   |
| Samsung SSD 850 EVO 500GB           | 6         | 0.31%   |
| HGST HTS545050A7E380 500GB          | 6         | 0.31%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 5         | 0.26%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 5         | 0.26%   |
| Unknown M52516  16GB                | 5         | 0.26%   |
| Toshiba MQ04ABF100 1TB              | 5         | 0.26%   |
| Seagate ST9320325AS 320GB           | 5         | 0.26%   |
| Seagate ST3250310AS 250GB           | 5         | 0.26%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 5         | 0.26%   |
| Samsung SSD 970 EVO Plus 500GB      | 5         | 0.26%   |
| Samsung SSD 860 EVO 500GB           | 5         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 291       | 381    | 31.66%  |
| WDC                 | 254       | 333    | 27.64%  |
| Hitachi             | 111       | 139    | 12.08%  |
| Toshiba             | 101       | 111    | 10.99%  |
| Samsung Electronics | 55        | 81     | 5.98%   |
| HGST                | 33        | 39     | 3.59%   |
| Fujitsu             | 24        | 26     | 2.61%   |
| Maxtor              | 18        | 20     | 1.96%   |
| Unknown             | 10        | 12     | 1.09%   |
| TO Exter            | 3         | 3      | 0.33%   |
| IBM/Hitachi         | 3         | 4      | 0.33%   |
| Apple               | 3         | 3      | 0.33%   |
| USB                 | 2         | 2      | 0.22%   |
| Hewlett-Packard     | 2         | 2      | 0.22%   |
| External            | 2         | 2      | 0.22%   |
| XrayDisk            | 1         | 1      | 0.11%   |
| WD MediaMax         | 1         | 1      | 0.11%   |
| USB3.0              | 1         | 1      | 0.11%   |
| RSH-319             | 1         | 1      | 0.11%   |
| LaCie               | 1         | 1      | 0.11%   |
| ASMT                | 1         | 2      | 0.11%   |
| Apricorn            | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 80        | 114    | 15.69%  |
| Kingston            | 77        | 91     | 15.1%   |
| Crucial             | 46        | 63     | 9.02%   |
| SanDisk             | 38        | 44     | 7.45%   |
| WDC                 | 27        | 33     | 5.29%   |
| Intel               | 22        | 32     | 4.31%   |
| A-DATA Technology   | 17        | 19     | 3.33%   |
| China               | 15        | 17     | 2.94%   |
| Apacer              | 13        | 13     | 2.55%   |
| Toshiba             | 12        | 14     | 2.35%   |
| Patriot             | 9         | 9      | 1.76%   |
| Micron Technology   | 9         | 9      | 1.76%   |
| Transcend           | 8         | 10     | 1.57%   |
| PNY                 | 8         | 8      | 1.57%   |
| OCZ                 | 7         | 8      | 1.37%   |
| SPCC                | 6         | 7      | 1.18%   |
| LITEONIT            | 6         | 6      | 1.18%   |
| LITEON              | 5         | 6      | 0.98%   |
| Intenso             | 5         | 5      | 0.98%   |
| GOODRAM             | 5         | 5      | 0.98%   |
| Corsair             | 5         | 5      | 0.98%   |
| Team                | 4         | 4      | 0.78%   |
| Lexar               | 4         | 4      | 0.78%   |
| KingSpec            | 4         | 6      | 0.78%   |
| SK hynix            | 3         | 3      | 0.59%   |
| Plextor             | 3         | 5      | 0.59%   |
| NGFF                | 3         | 3      | 0.59%   |
| LDLC                | 3         | 3      | 0.59%   |
| Dogfish             | 3         | 3      | 0.59%   |
| Apple               | 3         | 9      | 0.59%   |
| Unknown             | 2         | 2      | 0.39%   |
| Teclast             | 2         | 2      | 0.39%   |
| ORTIAL              | 2         | 2      | 0.39%   |
| Mushkin             | 2         | 2      | 0.39%   |
| Londisk             | 2         | 2      | 0.39%   |
| KingDian            | 2         | 2      | 0.39%   |
| JMicron Technology  | 2         | 2      | 0.39%   |
| Hewlett-Packard     | 2         | 7      | 0.39%   |
| Gigabyte Technology | 2         | 2      | 0.39%   |
| XrayDisk            | 1         | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 801       | 1166   | 49.38%  |
| SSD     | 480       | 630    | 29.59%  |
| MMC     | 173       | 228    | 10.67%  |
| NVMe    | 149       | 200    | 9.19%   |
| Unknown | 19        | 25     | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1134      | 1745   | 74.9%   |
| MMC  | 173       | 228    | 11.43%  |
| NVMe | 149       | 200    | 9.84%   |
| SAS  | 58        | 76     | 3.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 944       | 1269   | 72.17%  |
| 0.51-1.0   | 256       | 363    | 19.57%  |
| 1.01-2.0   | 60        | 87     | 4.59%   |
| 3.01-4.0   | 19        | 40     | 1.45%   |
| 4.01-10.0  | 16        | 20     | 1.22%   |
| 2.01-3.0   | 13        | 17     | 0.99%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 430       | 30.24%  |
| 251-500        | 320       | 22.5%   |
| 51-100         | 153       | 10.76%  |
| 501-1000       | 139       | 9.77%   |
| 21-50          | 116       | 8.16%   |
| 1-20           | 114       | 8.02%   |
| 1001-2000      | 66        | 4.64%   |
| More than 3000 | 48        | 3.38%   |
| 2001-3000      | 30        | 2.11%   |
| Unknown        | 6         | 0.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 735       | 50.31%  |
| 21-50          | 272       | 18.62%  |
| 101-250        | 151       | 10.34%  |
| 51-100         | 117       | 8.01%   |
| 251-500        | 61        | 4.18%   |
| 501-1000       | 53        | 3.63%   |
| 1001-2000      | 33        | 2.26%   |
| More than 3000 | 23        | 1.57%   |
| 2001-3000      | 10        | 0.68%   |
| Unknown        | 6         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 8         | 9      | 4.23%   |
| Seagate ST9500325AS 500GB          | 4         | 4      | 2.12%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 4      | 2.12%   |
| Seagate ST9320325AS 320GB          | 3         | 3      | 1.59%   |
| Seagate ST1000DM003-9YN162 1TB     | 3         | 3      | 1.59%   |
| Hitachi HTS545032B9A300 320GB      | 3         | 3      | 1.59%   |
| Apacer 16GB SATA Flash Drive SSD   | 3         | 3      | 1.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 2         | 2      | 1.06%   |
| WDC WD40EFRX-68WT0N0 4TB           | 2         | 3      | 1.06%   |
| Seagate ST9250315AS 250GB          | 2         | 2      | 1.06%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 2      | 1.06%   |
| Samsung Electronics HD502IJ 500GB  | 2         | 2      | 1.06%   |
| Hitachi HTS542512K9SA00 120GB      | 2         | 2      | 1.06%   |
| HGST HTS545050A7E380 500GB         | 2         | 2      | 1.06%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 1      | 0.53%   |
| WDC WD800BEVS-60RST0 80GB          | 1         | 1      | 0.53%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1         | 2      | 0.53%   |
| WDC WD5000LUCT-62C26Y0 500GB       | 1         | 1      | 0.53%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 1      | 0.53%   |
| WDC WD5000BPVT-75HXZT1 500GB       | 1         | 1      | 0.53%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 1      | 0.53%   |
| WDC WD5000AAKX-003CA0 500GB        | 1         | 1      | 0.53%   |
| WDC WD5000AAKX-001CA0 500GB        | 1         | 1      | 0.53%   |
| WDC WD400EB-00CPF0 40GB            | 1         | 1      | 0.53%   |
| WDC WD400BB-75CAA0 40GB            | 1         | 1      | 0.53%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 0.53%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 0.53%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 0.53%   |
| WDC WD3200BEVT-75A23T0 320GB       | 1         | 1      | 0.53%   |
| WDC WD3200BEKT-60PVMT0 320GB       | 1         | 1      | 0.53%   |
| WDC WD3200AAJS-00L7A0 320GB        | 1         | 1      | 0.53%   |
| WDC WD3200AACS-00M6B0 320GB        | 1         | 1      | 0.53%   |
| WDC WD2500HHTZ-04N21V0 250GB       | 1         | 1      | 0.53%   |
| WDC WD2500BEVT-80A23T0 250GB       | 1         | 2      | 0.53%   |
| WDC WD2500AAJS-75M0A0 250GB        | 1         | 1      | 0.53%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1         | 1      | 0.53%   |
| WDC WD2003FYYS-02W0B0 2TB          | 1         | 1      | 0.53%   |
| WDC WD1600AAJS-60B4A0 160GB        | 1         | 2      | 0.53%   |
| WDC WD1200BEVS-60UST0 120GB        | 1         | 1      | 0.53%   |
| WDC WD1200BEVS-07LAT0 120GB        | 1         | 1      | 0.53%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 60     | 27.72%  |
| WDC                 | 39        | 46     | 21.2%   |
| Hitachi             | 22        | 24     | 11.96%  |
| Toshiba             | 10        | 10     | 5.43%   |
| Samsung Electronics | 7         | 15     | 3.8%    |
| HGST                | 7         | 7      | 3.8%    |
| Maxtor              | 5         | 5      | 2.72%   |
| Kingston            | 5         | 5      | 2.72%   |
| Intel               | 5         | 6      | 2.72%   |
| Crucial             | 5         | 5      | 2.72%   |
| Fujitsu             | 4         | 4      | 2.17%   |
| Apacer              | 3         | 3      | 1.63%   |
| SK hynix            | 2         | 2      | 1.09%   |
| OCZ                 | 2         | 3      | 1.09%   |
| LITEON              | 2         | 2      | 1.09%   |
| KingSpec            | 2         | 4      | 1.09%   |
| A-DATA Technology   | 2         | 2      | 1.09%   |
| Transcend           | 1         | 1      | 0.54%   |
| TCSUNBOW            | 1         | 1      | 0.54%   |
| SanDisk             | 1         | 1      | 0.54%   |
| Plextor             | 1         | 1      | 0.54%   |
| ORTIAL              | 1         | 1      | 0.54%   |
| NGFF                | 1         | 1      | 0.54%   |
| Mushkin             | 1         | 1      | 0.54%   |
| Micron Technology   | 1         | 1      | 0.54%   |
| LDLC                | 1         | 1      | 0.54%   |
| Kingmax             | 1         | 1      | 0.54%   |
| Apple               | 1         | 1      | 0.54%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 60     | 35.92%  |
| WDC                 | 36        | 43     | 25.35%  |
| Hitachi             | 22        | 24     | 15.49%  |
| Toshiba             | 10        | 10     | 7.04%   |
| HGST                | 7         | 7      | 4.93%   |
| Samsung Electronics | 6         | 14     | 4.23%   |
| Maxtor              | 5         | 5      | 3.52%   |
| Fujitsu             | 4         | 4      | 2.82%   |
| Apple               | 1         | 1      | 0.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 135       | 168    | 76.27%  |
| SSD  | 41        | 45     | 23.16%  |
| NVMe | 1         | 1      | 0.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-40RYA0 320GB       | 1         | 1      | 8.33%   |
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 8.33%   |
| WDC WD1200BEVS-22UST0 120GB       | 1         | 1      | 8.33%   |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 8.33%   |
| Toshiba HDWD110 1TB               | 1         | 1      | 8.33%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 850 250GB | 1         | 1      | 8.33%   |
| Samsung Electronics HM320JI 320GB | 1         | 1      | 8.33%   |
| Samsung Electronics HD080HJ 80GB  | 1         | 1      | 8.33%   |
| Intel SSDSA1M160G2HP 160GB        | 1         | 1      | 8.33%   |
| HGST HTS725025A7 250GB            | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 33.33%  |
| Samsung Electronics | 4         | 4      | 33.33%  |
| Toshiba             | 1         | 1      | 8.33%   |
| Seagate             | 1         | 1      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 765       | 1207   | 51.24%  |
| Works    | 542       | 815    | 36.3%   |
| Malfunc  | 174       | 214    | 11.65%  |
| Failed   | 12        | 13     | 0.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 896       | 61.54%  |
| AMD                              | 246       | 16.9%   |
| Nvidia                           | 66        | 4.53%   |
| Samsung Electronics              | 45        | 3.09%   |
| SanDisk                          | 21        | 1.44%   |
| JMicron Technology               | 21        | 1.44%   |
| ASMedia Technology               | 18        | 1.24%   |
| VIA Technologies                 | 14        | 0.96%   |
| Kingston Technology Company      | 14        | 0.96%   |
| Micron Technology                | 13        | 0.89%   |
| Marvell Technology Group         | 13        | 0.89%   |
| SK hynix                         | 11        | 0.76%   |
| Silicon Motion                   | 11        | 0.76%   |
| Micron/Crucial Technology        | 10        | 0.69%   |
| Silicon Integrated Systems [SiS] | 9         | 0.62%   |
| Toshiba America Info Systems     | 7         | 0.48%   |
| KIOXIA                           | 7         | 0.48%   |
| Silicon Image                    | 5         | 0.34%   |
| Phison Electronics               | 5         | 0.34%   |
| LSI Logic / Symbios Logic        | 5         | 0.34%   |
| ADATA Technology                 | 3         | 0.21%   |
| Union Memory (Shenzhen)          | 2         | 0.14%   |
| ULi Electronics                  | 2         | 0.14%   |
| Solid State Storage Technology   | 2         | 0.14%   |
| Broadcom / LSI                   | 2         | 0.14%   |
| Zhaoxin                          | 1         | 0.07%   |
| Yangtze Memory Technologies      | 1         | 0.07%   |
| Shenzhen Longsys Electronics     | 1         | 0.07%   |
| Seagate Technology               | 1         | 0.07%   |
| Hewlett-Packard                  | 1         | 0.07%   |
| Broadcom                         | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |
| Adaptec                          | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 146       | 8.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 75        | 4.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 62        | 3.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 51        | 2.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 49        | 2.72%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 48        | 2.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 48        | 2.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 48        | 2.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 46        | 2.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 44        | 2.44%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 36        | 2%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 35        | 1.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 35        | 1.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 34        | 1.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 30        | 1.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 28        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 27        | 1.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 25        | 1.39%   |
| Nvidia MCP61 SATA Controller                                                            | 22        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 22        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 21        | 1.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 20        | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 20        | 1.11%   |
| Nvidia MCP61 IDE                                                                        | 17        | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 17        | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 16        | 0.89%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 16        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 16        | 0.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 15        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 15        | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 15        | 0.83%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 13        | 0.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 13        | 0.72%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 13        | 0.72%   |
| AMD 400 Series Chipset SATA Controller                                                  | 13        | 0.72%   |
| Intel SATA Controller [RAID mode]                                                       | 12        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12        | 0.67%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 11        | 0.61%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 11        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 924       | 59.96%  |
| IDE  | 389       | 25.24%  |
| NVMe | 147       | 9.54%   |
| RAID | 76        | 4.93%   |
| SCSI | 3         | 0.19%   |
| SAS  | 2         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1066      | 76.36%  |
| AMD          | 315       | 22.56%  |
| ARM          | 12        | 0.86%   |
| PowerMac7,2  | 1         | 0.07%   |
| CentaurHauls | 1         | 0.07%   |
| Unknown      | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 28        | 2.01%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 17        | 1.22%   |
| Intel Atom CPU N270 @ 1.60GHz               | 14        | 1%      |
| Intel Celeron N4020 CPU @ 1.10GHz           | 13        | 0.93%   |
| ARM Processor                               | 11        | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 10        | 0.72%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 10        | 0.72%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 10        | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 9         | 0.64%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 9         | 0.64%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 9         | 0.64%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 9         | 0.64%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 9         | 0.64%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 9         | 0.64%   |
| Intel Atom CPU N455 @ 1.66GHz               | 9         | 0.64%   |
| Intel Atom CPU N450 @ 1.66GHz               | 9         | 0.64%   |
| AMD E-450 APU with Radeon HD Graphics       | 9         | 0.64%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 8         | 0.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 8         | 0.57%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 8         | 0.57%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 8         | 0.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 8         | 0.57%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 7         | 0.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 7         | 0.5%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 7         | 0.5%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7         | 0.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz           | 7         | 0.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 7         | 0.5%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 6         | 0.43%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 6         | 0.43%   |
| Intel Pentium 4 CPU 2.80GHz                 | 6         | 0.43%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 6         | 0.43%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 6         | 0.43%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 6         | 0.43%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 6         | 0.43%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 6         | 0.43%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 6         | 0.43%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 6         | 0.43%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 6         | 0.43%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 6         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 205       | 14.68%  |
| Intel Celeron           | 156       | 11.17%  |
| Intel Atom              | 129       | 9.24%   |
| Intel Core i7           | 116       | 8.31%   |
| Intel Core 2 Duo        | 102       | 7.31%   |
| Intel Core i3           | 98        | 7.02%   |
| Other                   | 43        | 3.08%   |
| Intel Pentium           | 39        | 2.79%   |
| Intel Pentium Dual-Core | 35        | 2.51%   |
| Intel Pentium Dual      | 35        | 2.51%   |
| AMD Ryzen 7             | 30        | 2.15%   |
| AMD Ryzen 5             | 29        | 2.08%   |
| AMD Athlon 64 X2        | 23        | 1.65%   |
| Intel Xeon              | 22        | 1.58%   |
| Intel Core 2            | 21        | 1.5%    |
| AMD E                   | 21        | 1.5%    |
| AMD A6                  | 18        | 1.29%   |
| Intel Pentium 4         | 17        | 1.22%   |
| AMD A4                  | 17        | 1.22%   |
| AMD E1                  | 15        | 1.07%   |
| Intel Core 2 Quad       | 14        | 1%      |
| AMD FX                  | 12        | 0.86%   |
| AMD Athlon II X2        | 12        | 0.86%   |
| AMD A10                 | 12        | 0.86%   |
| Intel Genuine           | 11        | 0.79%   |
| AMD E2                  | 10        | 0.72%   |
| AMD A8                  | 10        | 0.72%   |
| AMD Athlon 64           | 8         | 0.57%   |
| Intel Pentium Silver    | 7         | 0.5%    |
| AMD Ryzen 3             | 7         | 0.5%    |
| AMD GX                  | 7         | 0.5%    |
| Intel Pentium D         | 6         | 0.43%   |
| Intel Celeron M         | 6         | 0.43%   |
| Intel Celeron Dual-Core | 6         | 0.43%   |
| AMD Phenom II X4        | 6         | 0.43%   |
| AMD Athlon              | 6         | 0.43%   |
| Intel Pentium M         | 5         | 0.36%   |
| AMD Turion 64 X2 Mobile | 5         | 0.36%   |
| AMD C-50                | 5         | 0.36%   |
| AMD Ryzen 9             | 4         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 798       | 57.16%  |
| 4       | 373       | 26.72%  |
| 1       | 118       | 8.45%   |
| 8       | 41        | 2.94%   |
| 6       | 38        | 2.72%   |
| 3       | 8         | 0.57%   |
| 12      | 5         | 0.36%   |
| 10      | 5         | 0.36%   |
| Unknown | 4         | 0.29%   |
| 16      | 2         | 0.14%   |
| 64      | 1         | 0.07%   |
| 40      | 1         | 0.07%   |
| 20      | 1         | 0.07%   |
| 14      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1382      | 99%     |
| 2       | 9         | 0.64%   |
| Unknown | 4         | 0.29%   |
| 4       | 1         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 799       | 57.23%  |
| 2       | 592       | 42.41%  |
| Unknown | 4         | 0.29%   |
| 8       | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1329      | 95.2%   |
| 32-bit         | 57        | 4.08%   |
| Unknown        | 9         | 0.64%   |
| 64-bit         | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 383       | 26.91%  |
| 0x206a7    | 79        | 5.55%   |
| 0x1067a    | 64        | 4.5%    |
| 0x306a9    | 63        | 4.43%   |
| 0x6fd      | 52        | 3.65%   |
| 0x406c4    | 34        | 2.39%   |
| 0x20655    | 32        | 2.25%   |
| 0x30678    | 31        | 2.18%   |
| 0x05000119 | 29        | 2.04%   |
| 0x40651    | 28        | 1.97%   |
| 0x306c3    | 28        | 1.97%   |
| 0x106ca    | 28        | 1.97%   |
| 0x406c3    | 23        | 1.62%   |
| 0x406e3    | 19        | 1.34%   |
| 0x6fb      | 18        | 1.26%   |
| 0x106c2    | 18        | 1.26%   |
| 0x806ec    | 17        | 1.19%   |
| 0x10676    | 17        | 1.19%   |
| 0x706a8    | 16        | 1.12%   |
| 0x706a1    | 16        | 1.12%   |
| 0x0700010f | 16        | 1.12%   |
| 0x806e9    | 13        | 0.91%   |
| 0x6f6      | 13        | 0.91%   |
| 0x20652    | 13        | 0.91%   |
| 0x06006705 | 13        | 0.91%   |
| 0x806ea    | 12        | 0.84%   |
| 0x06001119 | 12        | 0.84%   |
| 0x010000c8 | 12        | 0.84%   |
| 0x506c9    | 11        | 0.77%   |
| 0x906ea    | 10        | 0.7%    |
| 0x306d4    | 10        | 0.7%    |
| 0x05000029 | 10        | 0.7%    |
| 0x806c1    | 9         | 0.63%   |
| 0x6e8      | 9         | 0.63%   |
| 0x6d8      | 9         | 0.63%   |
| 0x706e5    | 8         | 0.56%   |
| 0x10661    | 8         | 0.56%   |
| 0x06006704 | 8         | 0.56%   |
| 0x06000852 | 8         | 0.56%   |
| 0x30661    | 7         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 130       | 9.31%   |
| Core             | 120       | 8.6%    |
| Penryn           | 109       | 7.81%   |
| SandyBridge      | 107       | 7.66%   |
| IvyBridge        | 90        | 6.45%   |
| KabyLake         | 80        | 5.73%   |
| Haswell          | 78        | 5.59%   |
| Westmere         | 62        | 4.44%   |
| Bonnell          | 60        | 4.3%    |
| K8 Hammer        | 47        | 3.37%   |
| Goldmont plus    | 43        | 3.08%   |
| Bobcat           | 43        | 3.08%   |
| Skylake          | 38        | 2.72%   |
| K10              | 36        | 2.58%   |
| Excavator        | 34        | 2.44%   |
| NetBurst         | 28        | 2.01%   |
| Piledriver       | 26        | 1.86%   |
| Unknown          | 25        | 1.79%   |
| P6               | 24        | 1.72%   |
| Zen 3            | 22        | 1.58%   |
| Zen 2            | 22        | 1.58%   |
| Jaguar           | 21        | 1.5%    |
| Goldmont         | 20        | 1.43%   |
| Zen+             | 19        | 1.36%   |
| Broadwell        | 16        | 1.15%   |
| IceLake          | 14        | 1%      |
| TigerLake        | 13        | 0.93%   |
| Zen              | 10        | 0.72%   |
| Puma             | 10        | 0.72%   |
| CometLake        | 10        | 0.72%   |
| Nehalem          | 9         | 0.64%   |
| Tremont          | 8         | 0.57%   |
| K8 & K10 hybrid  | 6         | 0.43%   |
| Steamroller      | 5         | 0.36%   |
| Alderlake Hybrid | 5         | 0.36%   |
| K10 Llano        | 4         | 0.29%   |
| K6               | 1         | 0.07%   |
| Bulldozer        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 836       | 55.15%  |
| AMD                              | 364       | 24.01%  |
| Nvidia                           | 293       | 19.33%  |
| Matrox Electronics Systems       | 8         | 0.53%   |
| Silicon Integrated Systems [SiS] | 7         | 0.46%   |
| VIA Technologies                 | 6         | 0.4%    |
| Zhaoxin                          | 1         | 0.07%   |
| S3 Graphics                      | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 86        | 5.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 76        | 4.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 58        | 3.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 54        | 3.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 49        | 3.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 49        | 3.01%   |
| Intel Core Processor Integrated Graphics Controller                                      | 40        | 2.46%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 39        | 2.4%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 37        | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 2.09%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 29        | 1.78%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 28        | 1.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 28        | 1.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 1.35%   |
| Intel HD Graphics 500                                                                    | 19        | 1.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18        | 1.11%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 15        | 0.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 0.86%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 14        | 0.86%   |
| Intel HD Graphics 620                                                                    | 14        | 0.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 0.8%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 13        | 0.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 0.8%    |
| Nvidia GT218 [GeForce 210]                                                               | 12        | 0.74%   |
| Intel UHD Graphics 620                                                                   | 12        | 0.74%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 12        | 0.74%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 12        | 0.74%   |
| Intel HD Graphics 5500                                                                   | 11        | 0.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 0.68%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 0.68%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 11        | 0.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 0.68%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 11        | 0.68%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 10        | 0.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 0.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 0.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 0.61%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 10        | 0.61%   |
| Intel JasperLake [UHD Graphics]                                                          | 9         | 0.55%   |
| Intel Iris Plus Graphics G7                                                              | 9         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 709       | 50.64%  |
| 1 x AMD            | 291       | 20.79%  |
| 1 x Nvidia         | 205       | 14.64%  |
| Intel + Nvidia     | 73        | 5.21%   |
| Intel + AMD        | 36        | 2.57%   |
| 2 x AMD            | 27        | 1.93%   |
| Other              | 19        | 1.36%   |
| AMD + Nvidia       | 9         | 0.64%   |
| 1 x SiS            | 7         | 0.5%    |
| 1 x Matrox         | 7         | 0.5%    |
| 1 x VIA            | 6         | 0.43%   |
| 2 x Intel          | 4         | 0.29%   |
| 2 x Nvidia         | 2         | 0.14%   |
| 1 x Zhaoxin        | 1         | 0.07%   |
| 1 x S3 Graphics    | 1         | 0.07%   |
| Nvidia + Matrox    | 1         | 0.07%   |
| Intel + 2 x Nvidia | 1         | 0.07%   |
| Intel + 2 x AMD    | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1226      | 87.45%  |
| Proprietary | 113       | 8.06%   |
| Unknown     | 63        | 4.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 837       | 59.4%   |
| 0.01-0.5   | 306       | 21.72%  |
| 1.01-2.0   | 109       | 7.74%   |
| 0.51-1.0   | 88        | 6.25%   |
| 3.01-4.0   | 35        | 2.48%   |
| 7.01-8.0   | 13        | 0.92%   |
| 5.01-6.0   | 7         | 0.5%    |
| 2.01-3.0   | 7         | 0.5%    |
| 8.01-16.0  | 7         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 196       | 14.53%  |
| AU Optronics            | 175       | 12.97%  |
| LG Display              | 128       | 9.49%   |
| BOE                     | 107       | 7.93%   |
| Chimei Innolux          | 97        | 7.19%   |
| Dell                    | 67        | 4.97%   |
| Acer                    | 44        | 3.26%   |
| Goldstar                | 43        | 3.19%   |
| Hewlett-Packard         | 39        | 2.89%   |
| Chi Mei Optoelectronics | 39        | 2.89%   |
| Apple                   | 28        | 2.08%   |
| Philips                 | 27        | 2%      |
| LG Philips              | 27        | 2%      |
| Lenovo                  | 26        | 1.93%   |
| HannStar                | 23        | 1.7%    |
| AOC                     | 23        | 1.7%    |
| BenQ                    | 19        | 1.41%   |
| Ancor Communications    | 17        | 1.26%   |
| InfoVision              | 15        | 1.11%   |
| Iiyama                  | 14        | 1.04%   |
| CPT                     | 14        | 1.04%   |
| Sharp                   | 12        | 0.89%   |
| Vizio                   | 9         | 0.67%   |
| Unknown                 | 9         | 0.67%   |
| NEC Computers           | 9         | 0.67%   |
| Sony                    | 8         | 0.59%   |
| Toshiba                 | 7         | 0.52%   |
| PANDA                   | 7         | 0.52%   |
| LG Electronics          | 5         | 0.37%   |
| Eizo                    | 5         | 0.37%   |
| ViewSonic               | 4         | 0.3%    |
| Sceptre Tech            | 4         | 0.3%    |
| MSI                     | 4         | 0.3%    |
| Fujitsu Siemens         | 4         | 0.3%    |
| Positivo                | 3         | 0.22%   |
| Panasonic               | 3         | 0.22%   |
| InnoLux Display         | 3         | 0.22%   |
| Belinea                 | 3         | 0.22%   |
| ASUSTek Computer        | 3         | 0.22%   |
| ___                     | 2         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 10        | 0.73%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 0.73%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 9         | 0.66%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 8         | 0.59%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 8         | 0.59%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.51%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 7         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.44%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 5         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 4         | 0.29%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                     | 4         | 0.29%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 4         | 0.29%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.29%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 4         | 0.29%   |
| BOE LCD Monitor BOE0635 1920x1080 309x173mm 13.9-inch                    | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 3         | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 3         | 0.22%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch            | 3         | 0.22%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 3         | 0.22%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch              | 3         | 0.22%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 3         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 421       | 31.56%  |
| 1920x1080 (FHD)    | 362       | 27.14%  |
| 1280x800 (WXGA)    | 108       | 8.1%    |
| 1280x1024 (SXGA)   | 73        | 5.47%   |
| 1600x900 (HD+)     | 69        | 5.17%   |
| 1680x1050 (WSXGA+) | 49        | 3.67%   |
| 1440x900 (WXGA+)   | 39        | 2.92%   |
| 3840x2160 (4K)     | 35        | 2.62%   |
| 1024x600           | 33        | 2.47%   |
| 2560x1440 (QHD)    | 28        | 2.1%    |
| 1920x1200 (WUXGA)  | 27        | 2.02%   |
| 1024x768 (XGA)     | 16        | 1.2%    |
| 1360x768           | 11        | 0.82%   |
| Unknown            | 9         | 0.67%   |
| 2288x1287          | 5         | 0.37%   |
| 3840x2400          | 4         | 0.3%    |
| 2560x1600          | 4         | 0.3%    |
| 1280x720 (HD)      | 4         | 0.3%    |
| 3440x1440          | 3         | 0.22%   |
| 3200x1800 (QHD+)   | 3         | 0.22%   |
| 2560x1080          | 3         | 0.22%   |
| 1920x540           | 3         | 0.22%   |
| 1280x768           | 3         | 0.22%   |
| 3600x1200          | 2         | 0.15%   |
| 3200x1080          | 2         | 0.15%   |
| 2880x1800          | 2         | 0.15%   |
| 2160x1440          | 2         | 0.15%   |
| 2048x1536          | 2         | 0.15%   |
| 1600x1200          | 2         | 0.15%   |
| 800x600            | 1         | 0.07%   |
| 5760x2160          | 1         | 0.07%   |
| 3120x2080          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2736x1824          | 1         | 0.07%   |
| 2160x1200          | 1         | 0.07%   |
| 2048x1152          | 1         | 0.07%   |
| 1528x1222          | 1         | 0.07%   |
| 1360x765           | 1         | 0.07%   |
| 1152x864           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 375       | 27.9%   |
| 14      | 128       | 9.52%   |
| 13      | 124       | 9.23%   |
| 17      | 93        | 6.92%   |
| 24      | 63        | 4.69%   |
| 11      | 63        | 4.69%   |
| 23      | 57        | 4.24%   |
| 19      | 57        | 4.24%   |
| Unknown | 49        | 3.65%   |
| 27      | 46        | 3.42%   |
| 21      | 45        | 3.35%   |
| 10      | 36        | 2.68%   |
| 18      | 33        | 2.46%   |
| 22      | 30        | 2.23%   |
| 20      | 30        | 2.23%   |
| 12      | 30        | 2.23%   |
| 72      | 10        | 0.74%   |
| 84      | 8         | 0.6%    |
| 31      | 7         | 0.52%   |
| 47      | 4         | 0.3%    |
| 40      | 4         | 0.3%    |
| 34      | 4         | 0.3%    |
| 8       | 4         | 0.3%    |
| 32      | 3         | 0.22%   |
| 26      | 3         | 0.22%   |
| 9       | 3         | 0.22%   |
| 142     | 2         | 0.15%   |
| 65      | 2         | 0.15%   |
| 54      | 2         | 0.15%   |
| 52      | 2         | 0.15%   |
| 49      | 2         | 0.15%   |
| 48      | 2         | 0.15%   |
| 39      | 2         | 0.15%   |
| 38      | 2         | 0.15%   |
| 29      | 2         | 0.15%   |
| 28      | 2         | 0.15%   |
| 25      | 2         | 0.15%   |
| 16      | 2         | 0.15%   |
| 7       | 2         | 0.15%   |
| 63      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 586       | 43.9%   |
| 201-300        | 189       | 14.16%  |
| 501-600        | 167       | 12.51%  |
| 401-500        | 156       | 11.69%  |
| 351-400        | 109       | 8.16%   |
| Unknown        | 49        | 3.67%   |
| 1501-2000      | 18        | 1.35%   |
| 1001-1500      | 16        | 1.2%    |
| 601-700        | 14        | 1.05%   |
| 801-900        | 9         | 0.67%   |
| 701-800        | 8         | 0.6%    |
| 101-200        | 8         | 0.6%    |
| 901-1000       | 4         | 0.3%    |
| More than 2000 | 2         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 898       | 70.6%   |
| 16/10   | 221       | 17.37%  |
| 5/4     | 68        | 5.35%   |
| Unknown | 38        | 2.99%   |
| 4/3     | 28        | 2.2%    |
| 3/2     | 10        | 0.79%   |
| 21/9    | 5         | 0.39%   |
| 6/5     | 2         | 0.16%   |
| 1.00    | 2         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 371       | 27.71%  |
| 81-90          | 211       | 15.76%  |
| 201-250        | 160       | 11.95%  |
| 151-200        | 106       | 7.92%   |
| 51-60          | 63        | 4.71%   |
| 141-150        | 58        | 4.33%   |
| Unknown        | 49        | 3.66%   |
| 301-350        | 48        | 3.58%   |
| 121-130        | 46        | 3.44%   |
| 71-80          | 41        | 3.06%   |
| 41-50          | 39        | 2.91%   |
| More than 1000 | 32        | 2.39%   |
| 61-70          | 27        | 2.02%   |
| 251-300        | 26        | 1.94%   |
| 501-1000       | 18        | 1.34%   |
| 351-500        | 16        | 1.19%   |
| 131-140        | 13        | 0.97%   |
| 1-40           | 7         | 0.52%   |
| 111-120        | 5         | 0.37%   |
| 91-100         | 3         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 464       | 35.12%  |
| 101-120       | 459       | 34.75%  |
| 121-160       | 259       | 19.61%  |
| Unknown       | 49        | 3.71%   |
| 161-240       | 43        | 3.26%   |
| 1-50          | 33        | 2.5%    |
| More than 240 | 14        | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1236      | 87.41%  |
| 2     | 121       | 8.56%   |
| 0     | 48        | 3.39%   |
| 3     | 8         | 0.57%   |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 738       | 34.65%  |
| Intel                             | 469       | 22.02%  |
| Qualcomm Atheros                  | 302       | 14.18%  |
| Broadcom                          | 157       | 7.37%   |
| Nvidia                            | 56        | 2.63%   |
| Ralink Technology                 | 54        | 2.54%   |
| Marvell Technology Group          | 54        | 2.54%   |
| Broadcom Limited                  | 42        | 1.97%   |
| Ralink                            | 38        | 1.78%   |
| TP-Link                           | 24        | 1.13%   |
| Samsung Electronics               | 18        | 0.85%   |
| ASIX Electronics                  | 14        | 0.66%   |
| VIA Technologies                  | 11        | 0.52%   |
| MediaTek                          | 11        | 0.52%   |
| Attansic Technology               | 11        | 0.52%   |
| Xiaomi                            | 9         | 0.42%   |
| Qualcomm Atheros Communications   | 8         | 0.38%   |
| NetGear                           | 8         | 0.38%   |
| JMicron Technology                | 7         | 0.33%   |
| Huawei Technologies               | 7         | 0.33%   |
| Belkin Components                 | 7         | 0.33%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.23%   |
| ICS Advent                        | 4         | 0.19%   |
| D-Link System                     | 4         | 0.19%   |
| D-Link                            | 4         | 0.19%   |
| AMD                               | 4         | 0.19%   |
| OPPO Electronics                  | 3         | 0.14%   |
| Micro Star International          | 3         | 0.14%   |
| Hewlett-Packard                   | 3         | 0.14%   |
| Dell                              | 3         | 0.14%   |
| ASUSTek Computer                  | 3         | 0.14%   |
| 3Com                              | 3         | 0.14%   |
| ULi Electronics                   | 2         | 0.09%   |
| Seeed Technology                  | 2         | 0.09%   |
| Qualcomm                          | 2         | 0.09%   |
| Motorola PCS                      | 2         | 0.09%   |
| Intersil                          | 2         | 0.09%   |
| Fibocom                           | 2         | 0.09%   |
| Ericsson Business Mobile Networks | 2         | 0.09%   |
| Accton Technology                 | 2         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 421       | 17.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 150       | 6.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 56        | 2.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 45        | 1.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 40        | 1.64%   |
| Intel Wireless 7260                                                     | 36        | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 35        | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 35        | 1.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 34        | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 33        | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 30        | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 1.02%   |
| Intel Wireless 7265                                                     | 25        | 1.02%   |
| Ralink MT7601U Wireless Adapter                                         | 23        | 0.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 22        | 0.9%    |
| Intel Wireless 3165                                                     | 21        | 0.86%   |
| Nvidia MCP61 Ethernet                                                   | 20        | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 0.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 16        | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 16        | 0.66%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 0.66%   |
| Intel 82577LM Gigabit Network Connection                                | 16        | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 14        | 0.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 14        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 14        | 0.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 14        | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 13        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 13        | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 13        | 0.53%   |
| Intel Wireless 8265 / 8275                                              | 13        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 12        | 0.49%   |
| Realtek 802.11ac NIC                                                    | 11        | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 11        | 0.45%   |
| Intel Wireless 8260                                                     | 11        | 0.45%   |
| Intel Wireless 3160                                                     | 11        | 0.45%   |
| Intel Ethernet Connection I217-LM                                       | 11        | 0.45%   |
| Attansic AR8152 v2.0 Fast Ethernet                                      | 11        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 350       | 31.62%  |
| Qualcomm Atheros                  | 247       | 22.31%  |
| Realtek Semiconductor             | 213       | 19.24%  |
| Broadcom                          | 98        | 8.85%   |
| Ralink Technology                 | 54        | 4.88%   |
| Ralink                            | 38        | 3.43%   |
| Broadcom Limited                  | 24        | 2.17%   |
| TP-Link                           | 22        | 1.99%   |
| MediaTek                          | 10        | 0.9%    |
| Qualcomm Atheros Communications   | 8         | 0.72%   |
| NetGear                           | 7         | 0.63%   |
| Belkin Components                 | 7         | 0.63%   |
| Micro Star International          | 3         | 0.27%   |
| Marvell Technology Group          | 3         | 0.27%   |
| D-Link                            | 3         | 0.27%   |
| ASUSTek Computer                  | 3         | 0.27%   |
| Fibocom                           | 2         | 0.18%   |
| Dell                              | 2         | 0.18%   |
| D-Link System                     | 2         | 0.18%   |
| ZyXEL Communications              | 1         | 0.09%   |
| Tenda                             | 1         | 0.09%   |
| Sitecom Europe                    | 1         | 0.09%   |
| Sierra Wireless                   | 1         | 0.09%   |
| Samsung Electronics               | 1         | 0.09%   |
| Microsoft                         | 1         | 0.09%   |
| Logitec                           | 1         | 0.09%   |
| Linksys                           | 1         | 0.09%   |
| IMC Networks                      | 1         | 0.09%   |
| Ericsson Business Mobile Networks | 1         | 0.09%   |
| Edimax Technology                 | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 56        | 5.02%   |
| Intel Wireless 7260                                                     | 36        | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 35        | 3.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 35        | 3.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 34        | 3.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 33        | 2.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 30        | 2.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 2.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 2.24%   |
| Intel Wireless 7265                                                     | 25        | 2.24%   |
| Ralink MT7601U Wireless Adapter                                         | 23        | 2.06%   |
| Intel Wireless 3165                                                     | 21        | 1.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 16        | 1.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 16        | 1.43%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 1.43%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 14        | 1.26%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 14        | 1.26%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 14        | 1.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 13        | 1.17%   |
| Intel Wireless 8265 / 8275                                              | 13        | 1.17%   |
| Realtek 802.11ac NIC                                                    | 11        | 0.99%   |
| Intel Wireless 8260                                                     | 11        | 0.99%   |
| Intel Wireless 3160                                                     | 11        | 0.99%   |
| Realtek 802.11n WLAN Adapter                                            | 10        | 0.9%    |
| Ralink RT5370 Wireless Adapter                                          | 10        | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 0.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 10        | 0.9%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 10        | 0.9%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 9         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 0.81%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 9         | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 8         | 0.72%   |
| Intel WiFi Link 5100                                                    | 8         | 0.72%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 0.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 8         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 649       | 50.78%  |
| Intel                            | 216       | 16.9%   |
| Qualcomm Atheros                 | 96        | 7.51%   |
| Broadcom                         | 77        | 6.03%   |
| Nvidia                           | 56        | 4.38%   |
| Marvell Technology Group         | 51        | 3.99%   |
| Broadcom Limited                 | 18        | 1.41%   |
| ASIX Electronics                 | 14        | 1.1%    |
| Samsung Electronics              | 13        | 1.02%   |
| VIA Technologies                 | 11        | 0.86%   |
| Attansic Technology              | 11        | 0.86%   |
| Xiaomi                           | 9         | 0.7%    |
| JMicron Technology               | 7         | 0.55%   |
| Silicon Integrated Systems [SiS] | 5         | 0.39%   |
| Huawei Technologies              | 5         | 0.39%   |
| ICS Advent                       | 4         | 0.31%   |
| OPPO Electronics                 | 3         | 0.23%   |
| 3Com                             | 3         | 0.23%   |
| ULi Electronics                  | 2         | 0.16%   |
| TP-Link                          | 2         | 0.16%   |
| Qualcomm                         | 2         | 0.16%   |
| Motorola PCS                     | 2         | 0.16%   |
| D-Link System                    | 2         | 0.16%   |
| Accton Technology                | 2         | 0.16%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.08%   |
| Yulong                           | 1         | 0.08%   |
| Trident Microsystems             | 1         | 0.08%   |
| T & A Mobile Phones              | 1         | 0.08%   |
| Spreadtrum Communications        | 1         | 0.08%   |
| Research In Motion               | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.08%   |
| NetGear                          | 1         | 0.08%   |
| Microchip Technology             | 1         | 0.08%   |
| MediaTek                         | 1         | 0.08%   |
| LG Electronics                   | 1         | 0.08%   |
| Lab126                           | 1         | 0.08%   |
| Intersil                         | 1         | 0.08%   |
| Hewlett-Packard                  | 1         | 0.08%   |
| D-Link                           | 1         | 0.08%   |
| Aquantia                         | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 421       | 32.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 150       | 11.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 45        | 3.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 40        | 3.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 1.7%    |
| Nvidia MCP61 Ethernet                                             | 20        | 1.55%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 1.24%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14        | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 1.01%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 13        | 1.01%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.93%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 11        | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 0.85%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 11        | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 10        | 0.77%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 9         | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.7%    |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 9         | 0.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 9         | 0.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 8         | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 8         | 0.62%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 8         | 0.62%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 7         | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.54%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 7         | 0.54%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 7         | 0.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.46%   |
| Nvidia MCP51 Ethernet Controller                                  | 6         | 0.46%   |
| Nvidia CK804 Ethernet Controller                                  | 6         | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 6         | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 6         | 0.46%   |
| Intel I211 Gigabit Network Connection                             | 6         | 0.46%   |
| Intel Ethernet Controller I225-V                                  | 6         | 0.46%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 6         | 0.46%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 6         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1194      | 52.39%  |
| WiFi     | 1052      | 46.16%  |
| Modem    | 32        | 1.4%    |
| Unknown  | 1         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 808       | 57.76%  |
| Ethernet | 591       | 42.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 760       | 54.4%   |
| 1     | 524       | 37.51%  |
| 0     | 86        | 6.16%   |
| 3     | 22        | 1.57%   |
| 4     | 4         | 0.29%   |
| 6     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1147      | 81.29%  |
| Yes  | 264       | 18.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 225       | 33.83%  |
| Realtek Semiconductor           | 72        | 10.83%  |
| Qualcomm Atheros Communications | 63        | 9.47%   |
| Broadcom                        | 50        | 7.52%   |
| Cambridge Silicon Radio         | 45        | 6.77%   |
| Apple                           | 28        | 4.21%   |
| Lite-On Technology              | 27        | 4.06%   |
| IMC Networks                    | 25        | 3.76%   |
| Foxconn / Hon Hai               | 22        | 3.31%   |
| Hewlett-Packard                 | 20        | 3.01%   |
| Dell                            | 18        | 2.71%   |
| Ralink                          | 14        | 2.11%   |
| Toshiba                         | 12        | 1.8%    |
| ASUSTek Computer                | 10        | 1.5%    |
| Alps Electric                   | 9         | 1.35%   |
| MediaTek                        | 4         | 0.6%    |
| TP-Link                         | 3         | 0.45%   |
| Ralink Technology               | 2         | 0.3%    |
| Micro Star International        | 2         | 0.3%    |
| Marvell Semiconductor           | 2         | 0.3%    |
| Logitech                        | 2         | 0.3%    |
| Askey Computer                  | 2         | 0.3%    |
| Syntek                          | 1         | 0.15%   |
| Smart Modular Technologies      | 1         | 0.15%   |
| Qcom                            | 1         | 0.15%   |
| Integrated System Solution      | 1         | 0.15%   |
| HTC (High Tech Computer)        | 1         | 0.15%   |
| Fujitsu                         | 1         | 0.15%   |
| Dynex                           | 1         | 0.15%   |
| Chicony Electronics             | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 120       | 17.99%  |
| Realtek Bluetooth Radio                                                             | 45        | 6.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 45        | 6.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 34        | 5.1%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 26        | 3.9%    |
| Intel AX201 Bluetooth                                                               | 20        | 3%      |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 15        | 2.25%   |
| Intel AX200 Bluetooth                                                               | 15        | 2.25%   |
| Ralink RT3290 Bluetooth                                                             | 14        | 2.1%    |
| Apple Bluetooth Host Controller                                                     | 13        | 1.95%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 12        | 1.8%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 11        | 1.65%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 11        | 1.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 10        | 1.5%    |
| Apple Bluetooth HCI                                                                 | 10        | 1.5%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 9         | 1.35%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 9         | 1.35%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 9         | 1.35%   |
| Realtek RTL8723B Bluetooth                                                          | 8         | 1.2%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 8         | 1.2%    |
| Realtek 802.11ac WLAN Adapter                                                       | 7         | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 7         | 1.05%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 7         | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 1.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 1.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 0.9%    |
| Intel AX210 Bluetooth                                                               | 6         | 0.9%    |
| IMC Networks Bluetooth Radio                                                        | 6         | 0.9%    |
| IMC Networks Bluetooth Device                                                       | 6         | 0.9%    |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 0.75%   |
| IMC Networks Bluetooth module                                                       | 5         | 0.75%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.75%   |
| Dell Wireless 365 Bluetooth                                                         | 5         | 0.75%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 5         | 0.75%   |
| Broadcom HP Portable Bumble Bee                                                     | 4         | 0.6%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 0.6%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 4         | 0.6%    |
| Broadcom BCM2045 Bluetooth                                                          | 4         | 0.6%    |
| Apple Bluetooth USB Host Controller                                                 | 4         | 0.6%    |
| TP-Link TP-Cdj+ UB5A Adapter                                                        | 3         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 936       | 58.5%   |
| AMD                                          | 328       | 20.5%   |
| Nvidia                                       | 214       | 13.38%  |
| C-Media Electronics                          | 23        | 1.44%   |
| VIA Technologies                             | 14        | 0.88%   |
| Creative Labs                                | 10        | 0.63%   |
| Silicon Integrated Systems [SiS]             | 8         | 0.5%    |
| Logitech                                     | 8         | 0.5%    |
| GN Netcom                                    | 6         | 0.38%   |
| Texas Instruments                            | 5         | 0.31%   |
| ASUSTek Computer                             | 5         | 0.31%   |
| XMOS                                         | 4         | 0.25%   |
| Plantronics                                  | 3         | 0.19%   |
| Generalplus Technology                       | 3         | 0.19%   |
| Creative Technology                          | 3         | 0.19%   |
| ULi Electronics                              | 2         | 0.13%   |
| Realtek Semiconductor                        | 2         | 0.13%   |
| Razer USA                                    | 2         | 0.13%   |
| JMTek                                        | 2         | 0.13%   |
| Focusrite-Novation                           | 2         | 0.13%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.06%   |
| Zhaoxin                                      | 1         | 0.06%   |
| Sony                                         | 1         | 0.06%   |
| Setek Elektronik                             | 1         | 0.06%   |
| QinHeng Electronics                          | 1         | 0.06%   |
| Nordic Semiconductor ASA                     | 1         | 0.06%   |
| MosArt Semiconductor                         | 1         | 0.06%   |
| Microsoft                                    | 1         | 0.06%   |
| Micro Star International                     | 1         | 0.06%   |
| KORG                                         | 1         | 0.06%   |
| Hewlett-Packard                              | 1         | 0.06%   |
| Guillemot                                    | 1         | 0.06%   |
| ESI                                          | 1         | 0.06%   |
| Ensoniq                                      | 1         | 0.06%   |
| Elitegroup Computer Systems (ECS)            | 1         | 0.06%   |
| Elgato Systems                               | 1         | 0.06%   |
| EGO SYStems                                  | 1         | 0.06%   |
| Dell                                         | 1         | 0.06%   |
| Cirrus Logic                                 | 1         | 0.06%   |
| Asahi Kasei Microsystems                     | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 114       | 6.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 103       | 5.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 83        | 4.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 75        | 3.98%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 73        | 3.88%   |
| AMD FCH Azalia Controller                                                                         | 66        | 3.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 65        | 3.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 59        | 3.13%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 56        | 2.97%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 51        | 2.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 43        | 2.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 37        | 1.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 37        | 1.96%   |
| Intel 8 Series HD Audio Controller                                                                | 36        | 1.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 35        | 1.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 35        | 1.86%   |
| AMD Wrestler HDMI Audio                                                                           | 34        | 1.81%   |
| Nvidia High Definition Audio Controller                                                           | 31        | 1.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 31        | 1.65%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 29        | 1.54%   |
| AMD High Definition Audio Controller                                                              | 28        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 27        | 1.43%   |
| Nvidia MCP61 High Definition Audio                                                                | 22        | 1.17%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 20        | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 0.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 17        | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 16        | 0.85%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 16        | 0.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 0.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 0.8%    |
| Intel Broadwell-U Audio Controller                                                                | 15        | 0.8%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 15        | 0.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 0.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 14        | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 13        | 0.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 0.69%   |
| AMD Trinity HDMI Audio Controller                                                                 | 13        | 0.69%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 12        | 0.64%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 12        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 201       | 19.88%  |
| Unknown                      | 197       | 19.49%  |
| SK hynix                     | 171       | 16.91%  |
| Micron Technology            | 80        | 7.91%   |
| Kingston                     | 77        | 7.62%   |
| Crucial                      | 36        | 3.56%   |
| Corsair                      | 31        | 3.07%   |
| Unknown (ABCD)               | 29        | 2.87%   |
| Nanya Technology             | 25        | 2.47%   |
| A-DATA Technology            | 24        | 2.37%   |
| G.Skill                      | 22        | 2.18%   |
| Elpida                       | 20        | 1.98%   |
| Unknown                      | 12        | 1.19%   |
| Smart                        | 10        | 0.99%   |
| Ramaxel Technology           | 9         | 0.89%   |
| Patriot                      | 6         | 0.59%   |
| Transcend                    | 5         | 0.49%   |
| Teikon                       | 5         | 0.49%   |
| Team                         | 4         | 0.4%    |
| Qimonda                      | 3         | 0.3%    |
| PNY                          | 3         | 0.3%    |
| Apacer                       | 3         | 0.3%    |
| Unifosa                      | 2         | 0.2%    |
| Toshiba                      | 2         | 0.2%    |
| Timetec                      | 2         | 0.2%    |
| GOODRAM                      | 2         | 0.2%    |
| fef5                         | 2         | 0.2%    |
| Avant                        | 2         | 0.2%    |
| ASint Technology             | 2         | 0.2%    |
| Unknown (AB)                 | 1         | 0.1%    |
| Unknown (0x4000000000000000) | 1         | 0.1%    |
| Unknown (07FB)               | 1         | 0.1%    |
| Smart Brazil                 | 1         | 0.1%    |
| Silicon Power                | 1         | 0.1%    |
| Sesame                       | 1         | 0.1%    |
| PUSKILL                      | 1         | 0.1%    |
| Princeton                    | 1         | 0.1%    |
| Novatech                     | 1         | 0.1%    |
| Neo Forza                    | 1         | 0.1%    |
| Multilaser                   | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 19        | 1.73%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 12        | 1.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 12        | 1.09%   |
| Unknown                                                           | 12        | 1.09%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 11        | 1%      |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 10        | 0.91%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 10        | 0.91%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                     | 9         | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 9         | 0.82%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s          | 8         | 0.73%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s              | 8         | 0.73%   |
| Unknown RAM Module 1024MB SODIMM DDR2                             | 7         | 0.64%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s             | 7         | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 7         | 0.64%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                       | 6         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 6         | 0.55%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 6         | 0.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 6         | 0.55%   |
| Unknown RAM Module 1024MB SODIMM DRAM                             | 5         | 0.46%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                     | 5         | 0.46%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s            | 5         | 0.46%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 5         | 0.46%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s             | 5         | 0.46%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 5         | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3                                | 4         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                       | 4         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 4         | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 4         | 0.36%   |
| Unknown RAM Module 2048MB SODIMM DDR2                             | 4         | 0.36%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                        | 4         | 0.36%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                     | 4         | 0.36%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 4         | 0.36%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 0.36%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s            | 4         | 0.36%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s             | 4         | 0.36%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 4         | 0.36%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 3200MT/s          | 4         | 0.36%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s           | 4         | 0.36%   |
| Unknown RAM Module 512MB SODIMM DDR2                              | 3         | 0.27%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                       | 3         | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 386       | 43.47%  |
| DDR4    | 209       | 23.54%  |
| DDR2    | 115       | 12.95%  |
| LPDDR4  | 48        | 5.41%   |
| SDRAM   | 47        | 5.29%   |
| Unknown | 32        | 3.6%    |
| DDR     | 17        | 1.91%   |
| LPDDR3  | 16        | 1.8%    |
| DRAM    | 9         | 1.01%   |
| LPDDR5  | 6         | 0.68%   |
| DDR5    | 3         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 565       | 64.72%  |
| DIMM         | 263       | 30.13%  |
| Row Of Chips | 37        | 4.24%   |
| Unknown      | 7         | 0.8%    |
| Chip         | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 290       | 29.23%  |
| 2048  | 264       | 26.61%  |
| 8192  | 236       | 23.79%  |
| 1024  | 101       | 10.18%  |
| 16384 | 62        | 6.25%   |
| 512   | 18        | 1.81%   |
| 32768 | 13        | 1.31%   |
| 256   | 5         | 0.5%    |
| 128   | 2         | 0.2%    |
| 65536 | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 223       | 23.4%   |
| 1333    | 80        | 8.39%   |
| 3200    | 73        | 7.66%   |
| 2400    | 72        | 7.56%   |
| 2667    | 61        | 6.4%    |
| 667     | 56        | 5.88%   |
| Unknown | 53        | 5.56%   |
| 1334    | 49        | 5.14%   |
| 800     | 37        | 3.88%   |
| 1066    | 31        | 3.25%   |
| 2133    | 30        | 3.15%   |
| 1067    | 23        | 2.41%   |
| 533     | 23        | 2.41%   |
| 1867    | 17        | 1.78%   |
| 2048    | 15        | 1.57%   |
| 1866    | 14        | 1.47%   |
| 400     | 10        | 1.05%   |
| 4267    | 9         | 0.94%   |
| 3266    | 9         | 0.94%   |
| 3600    | 6         | 0.63%   |
| 6400    | 5         | 0.52%   |
| 3400    | 5         | 0.52%   |
| 333     | 5         | 0.52%   |
| 4199    | 4         | 0.42%   |
| 975     | 4         | 0.42%   |
| 49926   | 3         | 0.31%   |
| 4800    | 3         | 0.31%   |
| 3866    | 3         | 0.31%   |
| 266     | 3         | 0.31%   |
| 3933    | 2         | 0.21%   |
| 3066    | 2         | 0.21%   |
| 3000    | 2         | 0.21%   |
| 2933    | 2         | 0.21%   |
| 2800    | 2         | 0.21%   |
| 2733    | 2         | 0.21%   |
| 2666    | 2         | 0.21%   |
| 1639    | 2         | 0.21%   |
| 41632   | 1         | 0.1%    |
| 8400    | 1         | 0.1%    |
| 5500    | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 9         | 31.03%  |
| Samsung Electronics   | 6         | 20.69%  |
| Brother Industries    | 5         | 17.24%  |
| Canon                 | 4         | 13.79%  |
| Lexmark International | 2         | 6.9%    |
| STMicroelectronics    | 1         | 3.45%   |
| Seiko Epson           | 1         | 3.45%   |
| Dymo-CoStar           | 1         | 3.45%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SCX-4200 series                 | 2         | 6.9%    |
| Brother DCP-7055W                       | 2         | 6.9%    |
| STMicroelectronics USB Printing Support | 1         | 3.45%   |
| Seiko Epson TM-T20X                     | 1         | 3.45%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 3.45%   |
| Samsung SCX-3400 Series                 | 1         | 3.45%   |
| Samsung ML-1640 Series Laser Printer    | 1         | 3.45%   |
| Samsung M2020 Series                    | 1         | 3.45%   |
| Lexmark International Z33 Printer       | 1         | 3.45%   |
| Lexmark International MS610de           | 1         | 3.45%   |
| HP PSC 1500 series                      | 1         | 3.45%   |
| HP OfficeJet 4650 series                | 1         | 3.45%   |
| HP LaserJet P2015 series                | 1         | 3.45%   |
| HP LaserJet P1102                       | 1         | 3.45%   |
| HP LaserJet 1200                        | 1         | 3.45%   |
| HP DeskJet D2460                        | 1         | 3.45%   |
| HP DeskJet 3630 series                  | 1         | 3.45%   |
| HP Deskjet 3520 series                  | 1         | 3.45%   |
| HP Deskjet 1050 J410                    | 1         | 3.45%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo  | 1         | 3.45%   |
| Canon TS5100 series                     | 1         | 3.45%   |
| Canon PIXMA MP250                       | 1         | 3.45%   |
| Canon MF3110                            | 1         | 3.45%   |
| Canon CanoScan LiDE 300                 | 1         | 3.45%   |
| Brother PTUSB Printing                  | 1         | 3.45%   |
| Brother PT-2450DX                       | 1         | 3.45%   |
| Brother Printer                         | 1         | 3.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 42.86%  |
| Canon           | 3         | 42.86%  |
| Seiko Epson     | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 14.29%  |
| HP scanjet 8270                                               | 1         | 14.29%  |
| HP ScanJet 2400c                                              | 1         | 14.29%  |
| HP HP4470C                                                    | 1         | 14.29%  |
| Canon CanoScan LiDE 500F                                      | 1         | 14.29%  |
| Canon CanoScan LiDE 220                                       | 1         | 14.29%  |
| Canon CanoScan LiDE 200                                       | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 195       | 25.29%  |
| Realtek Semiconductor                  | 65        | 8.43%   |
| Microdia                               | 53        | 6.87%   |
| IMC Networks                           | 50        | 6.49%   |
| Suyin                                  | 37        | 4.8%    |
| Sunplus Innovation Technology          | 32        | 4.15%   |
| Cheng Uei Precision Industry (Foxlink) | 31        | 4.02%   |
| Bison Electronics                      | 30        | 3.89%   |
| Apple                                  | 29        | 3.76%   |
| Quanta                                 | 28        | 3.63%   |
| Alcor Micro                            | 28        | 3.63%   |
| Silicon Motion                         | 22        | 2.85%   |
| Syntek                                 | 19        | 2.46%   |
| Logitech                               | 16        | 2.08%   |
| Lite-On Technology                     | 16        | 2.08%   |
| Ricoh                                  | 9         | 1.17%   |
| Lenovo                                 | 9         | 1.17%   |
| Acer                                   | 9         | 1.17%   |
| ALi                                    | 8         | 1.04%   |
| Luxvisions Innotech Limited            | 7         | 0.91%   |
| GEMBIRD                                | 7         | 0.91%   |
| Z-Star Microelectronics                | 6         | 0.78%   |
| Microsoft                              | 5         | 0.65%   |
| Importek                               | 5         | 0.65%   |
| icSpring                               | 5         | 0.65%   |
| Generalplus Technology                 | 5         | 0.65%   |
| SunplusIT                              | 4         | 0.52%   |
| Samsung Electronics                    | 4         | 0.52%   |
| Genesys Logic                          | 4         | 0.52%   |
| Y Media                                | 2         | 0.26%   |
| USB Camera CS                          | 2         | 0.26%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.26%   |
| OmniVision Technologies                | 2         | 0.26%   |
| LG Electronics                         | 2         | 0.26%   |
| KYE Systems (Mouse Systems)            | 2         | 0.26%   |
| ARC International                      | 2         | 0.26%   |
| WCM_USB                                | 1         | 0.13%   |
| WaveRider Communications               | 1         | 0.13%   |
| Toshiba                                | 1         | 0.13%   |
| Sunplus Technology                     | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Alcor Micro USB 2.0 Camera                              | 21        | 2.71%   |
| Chicony Integrated Camera                               | 20        | 2.58%   |
| Realtek Integrated_Webcam_HD                            | 18        | 2.32%   |
| Chicony HP Truevision HD                                | 12        | 1.55%   |
| Chicony USB 2.0 Camera                                  | 11        | 1.42%   |
| Realtek USB Camera                                      | 10        | 1.29%   |
| Chicony HD WebCam                                       | 10        | 1.29%   |
| Sunplus HD WebCam                                       | 9         | 1.16%   |
| Chicony EasyCamera                                      | 9         | 1.16%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 9         | 1.16%   |
| Chicony HP TrueVision HD Camera                         | 8         | 1.03%   |
| Chicony HP HD Webcam                                    | 8         | 1.03%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 8         | 1.03%   |
| Microdia Integrated_Webcam_HD                           | 7         | 0.9%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 7         | 0.9%    |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 7         | 0.9%    |
| Chicony TOSHIBA Web Camera - HD                         | 7         | 0.9%    |
| Apple FaceTime HD Camera                                | 7         | 0.9%    |
| Apple Built-in iSight                                   | 7         | 0.9%    |
| Microdia 1.3 MPixel Integrated Webcam                   | 6         | 0.77%   |
| Lite-On HP HD Camera                                    | 6         | 0.77%   |
| IMC Networks UVC VGA Webcam                             | 6         | 0.77%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]       | 6         | 0.77%   |
| Chicony HP Webcam                                       | 6         | 0.77%   |
| Bison Lenovo EasyCamera                                 | 6         | 0.77%   |
| Bison Integrated Camera                                 | 6         | 0.77%   |
| Suyin Acer CrystalEye Webcam                            | 5         | 0.65%   |
| Silicon Motion WebCam SC-0311139N                       | 5         | 0.65%   |
| Quanta HP HD Camera                                     | 5         | 0.65%   |
| Microdia Integrated Webcam                              | 5         | 0.65%   |
| Lenovo Integrated Webcam [R5U877]                       | 5         | 0.65%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 5         | 0.65%   |
| icSpring camera                                         | 5         | 0.65%   |
| Chicony VGA WebCam                                      | 5         | 0.65%   |
| Chicony Lenovo EasyCamera                               | 5         | 0.65%   |
| Chicony HP HD Camera                                    | 5         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101    | 5         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 5         | 0.65%   |
| ALi WebCam                                              | 5         | 0.65%   |
| Z-Star Webcam                                           | 4         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 35        | 38.89%  |
| AuthenTec                  | 16        | 17.78%  |
| Upek                       | 11        | 12.22%  |
| Synaptics                  | 8         | 8.89%   |
| STMicroelectronics         | 7         | 7.78%   |
| Shenzhen Goodix Technology | 7         | 7.78%   |
| Samsung Electronics        | 2         | 2.22%   |
| LighTuning Technology      | 2         | 2.22%   |
| Elan Microelectronics      | 2         | 2.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 10        | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader                | 9         | 10%     |
| STMicroelectronics Fingerprint Reader                     | 7         | 7.78%   |
| Validity Sensors VFS471 Fingerprint Reader                | 5         | 5.56%   |
| AuthenTec AES2810                                         | 5         | 5.56%   |
| AuthenTec AES2501 Fingerprint Sensor                      | 5         | 5.56%   |
| Shenzhen Goodix  FingerPrint Device                       | 4         | 4.44%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 3         | 3.33%   |
| Validity Sensors VFS491                                   | 3         | 3.33%   |
| Validity Sensors VFS451 Fingerprint Reader                | 3         | 3.33%   |
| AuthenTec AES1600                                         | 3         | 3.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 2         | 2.22%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 2         | 2.22%   |
| Validity Sensors Fingerprint scanner                      | 2         | 2.22%   |
| Synaptics Fingerprint reader [HP G6]                      | 2         | 2.22%   |
| Shenzhen Goodix FingerPrint                               | 2         | 2.22%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 2         | 2.22%   |
| Elan ELAN:Fingerprint                                     | 2         | 2.22%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 2         | 2.22%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 1.11%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 1.11%   |
| Validity Sensors VFS300 Fingerprint Reader                | 1         | 1.11%   |
| Validity Sensors VFS101 Fingerprint Reader                | 1         | 1.11%   |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 1.11%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 1.11%   |
| Upek TCS5B Fingerprint sensor                             | 1         | 1.11%   |
| Synaptics WBDI                                            | 1         | 1.11%   |
| Synaptics UWP WBDI                                        | 1         | 1.11%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1.11%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 1.11%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 1.11%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 1.11%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 1.11%   |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 1.11%   |
| Samsung Fingerprint Device                                | 1         | 1.11%   |
| AuthenTec Fingerprint Sensor                              | 1         | 1.11%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 12        | 32.43%  |
| Alcor Micro           | 11        | 29.73%  |
| O2 Micro              | 7         | 18.92%  |
| Cherry                | 2         | 5.41%   |
| Upek                  | 1         | 2.7%    |
| Realtek Semiconductor | 1         | 2.7%    |
| OmniKey               | 1         | 2.7%    |
| Lenovo                | 1         | 2.7%    |
| Gemalto (was Gemplus) | 1         | 2.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 27.03%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 13.51%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 13.51%  |
| Broadcom 5880                                                                | 5         | 13.51%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 5.41%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 5.41%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 2.7%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 2.7%    |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 2.7%    |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.7%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.7%    |
| Broadcom 58200                                                               | 1         | 2.7%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 2.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1050      | 74.57%  |
| 1     | 296       | 21.02%  |
| 2     | 51        | 3.62%   |
| 3     | 8         | 0.57%   |
| 4     | 3         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 127       | 29.95%  |
| Fingerprint reader       | 89        | 20.99%  |
| Net/wireless             | 53        | 12.5%   |
| Chipcard                 | 32        | 7.55%   |
| Bluetooth                | 23        | 5.42%   |
| Communication controller | 15        | 3.54%   |
| Multimedia controller    | 14        | 3.3%    |
| Camera                   | 14        | 3.3%    |
| Sound                    | 10        | 2.36%   |
| Net/ethernet             | 9         | 2.12%   |
| Modem                    | 9         | 2.12%   |
| Storage                  | 8         | 1.89%   |
| Unassigned class         | 5         | 1.18%   |
| Flash memory             | 5         | 1.18%   |
| Dvb card                 | 5         | 1.18%   |
| Network                  | 3         | 0.71%   |
| Card reader              | 2         | 0.47%   |
| Storage/raid             | 1         | 0.24%   |

