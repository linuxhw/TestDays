Lubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Lubuntu.

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

Total: 1269

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ATARI         | VCS 800 Black Walnut        | [34456982d3](https://linux-hardware.org/?probe=34456982d3) | Dec 23, 2023 |
| Google        | Treeya                      | [b6541ef594](https://linux-hardware.org/?probe=b6541ef594) | Dec 19, 2023 |
| Toshiba       | Satellite L300              | [6528f813b7](https://linux-hardware.org/?probe=6528f813b7) | Dec 17, 2023 |
| Google        | Candy                       | [be56752bfd](https://linux-hardware.org/?probe=be56752bfd) | Dec 17, 2023 |
| HP            | ZBook 17                    | [d1269ca08c](https://linux-hardware.org/?probe=d1269ca08c) | Dec 13, 2023 |
| Acer          | Aspire A515-51G             | [295f9127b0](https://linux-hardware.org/?probe=295f9127b0) | Dec 12, 2023 |
| Dell          | Inspiron 3421               | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| Dell          | Inspiron MM061              | [213b775f8b](https://linux-hardware.org/?probe=213b775f8b) | Dec 08, 2023 |
| Dell          | Inspiron MM061              | [d4c43fe4f4](https://linux-hardware.org/?probe=d4c43fe4f4) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d25f6b4dd3](https://linux-hardware.org/?probe=d25f6b4dd3) | Dec 02, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [5a628a7b0f](https://linux-hardware.org/?probe=5a628a7b0f) | Nov 30, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3b82362902](https://linux-hardware.org/?probe=3b82362902) | Nov 29, 2023 |
| SGIN          | M15                         | [c7fb994367](https://linux-hardware.org/?probe=c7fb994367) | Nov 28, 2023 |
| Dell          | Latitude E6520              | [a03b74a3d3](https://linux-hardware.org/?probe=a03b74a3d3) | Nov 28, 2023 |
| ASUSTek       | X550ZE                      | [dedc54db8f](https://linux-hardware.org/?probe=dedc54db8f) | Nov 27, 2023 |
| Toshiba       | Satellite L300              | [370ddc00c4](https://linux-hardware.org/?probe=370ddc00c4) | Nov 24, 2023 |
| Chuwi         | X312B                       | [7f13217449](https://linux-hardware.org/?probe=7f13217449) | Nov 23, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [1e58f5a4f9](https://linux-hardware.org/?probe=1e58f5a4f9) | Nov 21, 2023 |
| MSI           | Raider GE76 12UE            | [bad07cc00d](https://linux-hardware.org/?probe=bad07cc00d) | Nov 20, 2023 |
| Packard Be... | ENLE11BZ                    | [905ad855b3](https://linux-hardware.org/?probe=905ad855b3) | Nov 19, 2023 |
| ASUSTek       | X201E                       | [3532136698](https://linux-hardware.org/?probe=3532136698) | Nov 18, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [d297e1365c](https://linux-hardware.org/?probe=d297e1365c) | Nov 16, 2023 |
| HP            | 250 G5 Notebook PC          | [dde4f98b29](https://linux-hardware.org/?probe=dde4f98b29) | Nov 16, 2023 |
| HUAWEI        | MRGFG-XX                    | [b7dda3ece0](https://linux-hardware.org/?probe=b7dda3ece0) | Nov 14, 2023 |
| Acer          | Extensa 5620                | [3c206e8578](https://linux-hardware.org/?probe=3c206e8578) | Nov 13, 2023 |
| ASUSTek       | T100TAS                     | [ff4068e60a](https://linux-hardware.org/?probe=ff4068e60a) | Nov 12, 2023 |
| HP            | 255 G1                      | [988c1c2454](https://linux-hardware.org/?probe=988c1c2454) | Nov 12, 2023 |
| HP            | 255 G1                      | [9aa30be183](https://linux-hardware.org/?probe=9aa30be183) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fa680be8d9](https://linux-hardware.org/?probe=fa680be8d9) | Nov 10, 2023 |
| ASUSTek       | X550ZE                      | [31d4fc8694](https://linux-hardware.org/?probe=31d4fc8694) | Nov 09, 2023 |
| ASUSTek       | G75VW                       | [94bc809d57](https://linux-hardware.org/?probe=94bc809d57) | Nov 05, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [cf0c02a17a](https://linux-hardware.org/?probe=cf0c02a17a) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [fdb464fed7](https://linux-hardware.org/?probe=fdb464fed7) | Nov 02, 2023 |
| ASUSTek       | K50IJ                       | [115cf0d371](https://linux-hardware.org/?probe=115cf0d371) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | [6fbbd2a061](https://linux-hardware.org/?probe=6fbbd2a061) | Oct 30, 2023 |
| Acer          | Aspire A315-21              | [48785f697c](https://linux-hardware.org/?probe=48785f697c) | Oct 29, 2023 |
| HP            | EliteBook 820 G3            | [c86a40c419](https://linux-hardware.org/?probe=c86a40c419) | Oct 28, 2023 |
| Acer          | Aspire 9300                 | [3094b549c5](https://linux-hardware.org/?probe=3094b549c5) | Oct 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [358936d398](https://linux-hardware.org/?probe=358936d398) | Oct 25, 2023 |
| Dixonsxp      | Unknown                     | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| Dell          | XPS 9315                    | [8c9d16e737](https://linux-hardware.org/?probe=8c9d16e737) | Oct 22, 2023 |
| HP            | Compaq Presario CQ40        | [5ddf61741f](https://linux-hardware.org/?probe=5ddf61741f) | Oct 20, 2023 |
| Positivo      | AT300b                      | [a39989b55b](https://linux-hardware.org/?probe=a39989b55b) | Oct 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | [9d142e587e](https://linux-hardware.org/?probe=9d142e587e) | Oct 17, 2023 |
| Acer          | Aspire A314-23P             | [99490448ae](https://linux-hardware.org/?probe=99490448ae) | Oct 16, 2023 |
| Acer          | Aspire A314-23P             | [431b672bf5](https://linux-hardware.org/?probe=431b672bf5) | Oct 16, 2023 |
| HP            | Laptop 14-dq0xxx            | [1f161ae269](https://linux-hardware.org/?probe=1f161ae269) | Oct 16, 2023 |
| Google        | Careena                     | [8359c8c3e8](https://linux-hardware.org/?probe=8359c8c3e8) | Oct 15, 2023 |
| Google        | Careena                     | [4292c49150](https://linux-hardware.org/?probe=4292c49150) | Oct 15, 2023 |
| HP            | Notebook                    | [fb39ee7d9d](https://linux-hardware.org/?probe=fb39ee7d9d) | Oct 13, 2023 |
| Thomson       | NEO14-4W64                  | [f68e52a8a1](https://linux-hardware.org/?probe=f68e52a8a1) | Oct 12, 2023 |
| BLANK         | Intel powered classmate ... | [78cc4b7937](https://linux-hardware.org/?probe=78cc4b7937) | Oct 11, 2023 |
| BLANK         | Intel powered classmate ... | [bc4093e3c7](https://linux-hardware.org/?probe=bc4093e3c7) | Oct 11, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [ee4617fa73](https://linux-hardware.org/?probe=ee4617fa73) | Oct 10, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
| Google        | Sasuke                      | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| Insyde        | Braswell                    | [c4261097f5](https://linux-hardware.org/?probe=c4261097f5) | Oct 07, 2023 |
| Apple         | MacBookPro8,1               | [ae4ee327c0](https://linux-hardware.org/?probe=ae4ee327c0) | Oct 06, 2023 |
| HP            | Laptop 15-da0xxx            | [92e214fb3e](https://linux-hardware.org/?probe=92e214fb3e) | Oct 04, 2023 |
| Getac         | X500G3                      | [919772eed0](https://linux-hardware.org/?probe=919772eed0) | Oct 02, 2023 |
| Panasonic     | CF-F9KWPZFFE                | [33cf16d622](https://linux-hardware.org/?probe=33cf16d622) | Oct 01, 2023 |
| HP            | Laptop 14-ck0xxx            | [f4326ad956](https://linux-hardware.org/?probe=f4326ad956) | Sep 26, 2023 |
| HP            | Laptop 14-ck0xxx            | [3ff273b73c](https://linux-hardware.org/?probe=3ff273b73c) | Sep 26, 2023 |
| ASUSTek       | X451MA                      | [ed779c5de4](https://linux-hardware.org/?probe=ed779c5de4) | Sep 20, 2023 |
| Mini PC       | Cherry Trail CR             | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| Dell          | Precision 3570              | [fd3441ff1d](https://linux-hardware.org/?probe=fd3441ff1d) | Sep 18, 2023 |
| Google        | Blooglet                    | [79ce749655](https://linux-hardware.org/?probe=79ce749655) | Sep 17, 2023 |
| HP            | 15                          | [03e1207549](https://linux-hardware.org/?probe=03e1207549) | Sep 12, 2023 |
| HP            | 2000                        | [48790bd831](https://linux-hardware.org/?probe=48790bd831) | Sep 09, 2023 |
| HP            | 2000                        | [ce9ba2b7c4](https://linux-hardware.org/?probe=ce9ba2b7c4) | Sep 09, 2023 |
| eMachines     | eM350                       | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Dell          | Latitude 3190               | [60f82737fa](https://linux-hardware.org/?probe=60f82737fa) | Sep 06, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7d6ff14b38](https://linux-hardware.org/?probe=7d6ff14b38) | Sep 05, 2023 |
| HP            | 255 G2                      | [27b48aa011](https://linux-hardware.org/?probe=27b48aa011) | Sep 02, 2023 |
| Dell          | Inspiron 1545               | [8ba55e98ec](https://linux-hardware.org/?probe=8ba55e98ec) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d169572a6b](https://linux-hardware.org/?probe=d169572a6b) | Aug 31, 2023 |
| ASUSTek       | K52JB                       | [ddcb97361b](https://linux-hardware.org/?probe=ddcb97361b) | Aug 30, 2023 |
| ASUSTek       | X75VD                       | [cab1480dc6](https://linux-hardware.org/?probe=cab1480dc6) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2bd35d44f1](https://linux-hardware.org/?probe=2bd35d44f1) | Aug 29, 2023 |
| Packard Be... | EasyNote TJ65               | [f37ab96772](https://linux-hardware.org/?probe=f37ab96772) | Aug 28, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [7abf0d31d8](https://linux-hardware.org/?probe=7abf0d31d8) | Aug 28, 2023 |
| Toshiba       | Satellite P770              | [8618c83c93](https://linux-hardware.org/?probe=8618c83c93) | Aug 26, 2023 |
| Google        | Robo                        | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| Compal        | PBL20                       | [ae09076b4e](https://linux-hardware.org/?probe=ae09076b4e) | Aug 22, 2023 |
| HP            | Notebook                    | [11d2993965](https://linux-hardware.org/?probe=11d2993965) | Aug 20, 2023 |
| Google        | Madoo                       | [8eea1017dc](https://linux-hardware.org/?probe=8eea1017dc) | Aug 20, 2023 |
| HP            | Notebook                    | [f6e4865586](https://linux-hardware.org/?probe=f6e4865586) | Aug 19, 2023 |
| Lenovo        | ThinkPad T430 2349TFK       | [390899a281](https://linux-hardware.org/?probe=390899a281) | Aug 17, 2023 |
| Acer          | Aspire 5050                 | [63329f0ff6](https://linux-hardware.org/?probe=63329f0ff6) | Aug 16, 2023 |
| HP            | Pavilion g7                 | [43351d6476](https://linux-hardware.org/?probe=43351d6476) | Aug 12, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [abaa0512b0](https://linux-hardware.org/?probe=abaa0512b0) | Aug 11, 2023 |
| Samsung       | N150P/N210P/N220P           | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Toshiba       | Satellite L875D             | [de1a418102](https://linux-hardware.org/?probe=de1a418102) | Aug 08, 2023 |
| Dell          | Inspiron MM061              | [3e037493db](https://linux-hardware.org/?probe=3e037493db) | Aug 06, 2023 |
| Dell          | Inspiron 5720               | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| HP            | Pavilion 15                 | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| Lenovo        | G580 20150                  | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Dell          | Inspiron 1520               | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | [c7dd142af9](https://linux-hardware.org/?probe=c7dd142af9) | Jul 24, 2023 |
| Dell          | Inspiron 5576               | [54c338bb01](https://linux-hardware.org/?probe=54c338bb01) | Jul 22, 2023 |
| Dell          | Inspiron 5576               | [6654328e2c](https://linux-hardware.org/?probe=6654328e2c) | Jul 22, 2023 |
| Acer          | Aspire SW3-013              | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| Dell          | Latitude 5290               | [66860827b9](https://linux-hardware.org/?probe=66860827b9) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Fujitsu       | FMVNC4BC4                   | [14249b136a](https://linux-hardware.org/?probe=14249b136a) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| HP            | 255 G2                      | [eaf9befa3a](https://linux-hardware.org/?probe=eaf9befa3a) | Jul 19, 2023 |
| LG Electro... | 15Z90N-U.ARS5U1             | [54b03a096b](https://linux-hardware.org/?probe=54b03a096b) | Jul 19, 2023 |
| Acer          | Aspire E5-523G              | [6535e7c6d1](https://linux-hardware.org/?probe=6535e7c6d1) | Jul 08, 2023 |
| Dell          | Inspiron 13-5378            | [8337bfbb61](https://linux-hardware.org/?probe=8337bfbb61) | Jul 08, 2023 |
| Acer          | Swift SFE16-42              | [c8b8a7d737](https://linux-hardware.org/?probe=c8b8a7d737) | Jul 07, 2023 |
| Dell          | Inspiron N5110              | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| HP            | ProBook 4525s               | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| Lenovo        | ThinkPad T430 2349G7G       | [b0eefed750](https://linux-hardware.org/?probe=b0eefed750) | Jul 03, 2023 |
| Google        | Pyro                        | [9632e7a77b](https://linux-hardware.org/?probe=9632e7a77b) | Jul 02, 2023 |
| eMachines     | eME443                      | [0d6808da66](https://linux-hardware.org/?probe=0d6808da66) | Jun 30, 2023 |
| UMAX          | N14R                        | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
| Lenovo        | Z70-80 80FG                 | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| Sony          | VPCEB37FD                   | [afe6ac4f32](https://linux-hardware.org/?probe=afe6ac4f32) | Jun 27, 2023 |
| Sony          | VPCEB37FD                   | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| HP            | Laptop 15-da0xxx            | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| HP            | EliteBook 840 G3            | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Toshiba       | Satellite P200              | [19350653f7](https://linux-hardware.org/?probe=19350653f7) | Jun 23, 2023 |
| Dell          | Vostro 3700                 | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| ASUSTek       | 1011CX                      | [0fa6b0b3dc](https://linux-hardware.org/?probe=0fa6b0b3dc) | Jun 19, 2023 |
| HP            | ProBook 650 G3              | [009fdf15c4](https://linux-hardware.org/?probe=009fdf15c4) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | [e4c0eeb007](https://linux-hardware.org/?probe=e4c0eeb007) | Jun 17, 2023 |
| Dell          | Precision 3570              | [6f6debf1a4](https://linux-hardware.org/?probe=6f6debf1a4) | Jun 15, 2023 |
| Dell          | Vostro 3700                 | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y580                | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| Acer          | Aspire 7741                 | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| HP            | 240 G3                      | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| Lenovo        | G580 2189                   | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| Dell          | Latitude E6430              | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Unknown       | Unknown                     | [cbab0f6dd8](https://linux-hardware.org/?probe=cbab0f6dd8) | May 25, 2023 |
| ASUSTek       | X450CC                      | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [20c80a45a8](https://linux-hardware.org/?probe=20c80a45a8) | May 22, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| HP            | ProBook 650 G3              | [ce80a21736](https://linux-hardware.org/?probe=ce80a21736) | May 19, 2023 |
| Lenovo        | ThinkPad T400 276522G       | [dc8b38dd37](https://linux-hardware.org/?probe=dc8b38dd37) | May 17, 2023 |
| Google        | Snappy                      | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Medion        | Akoya P6660 MD99790         | [20ecc9b5dc](https://linux-hardware.org/?probe=20ecc9b5dc) | May 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0145d107e8](https://linux-hardware.org/?probe=0145d107e8) | May 15, 2023 |
| Intel         | W7650                       | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Toshiba       | Satellite Radius P55W-B     | [e2ed5e2135](https://linux-hardware.org/?probe=e2ed5e2135) | May 11, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0b08b7a631](https://linux-hardware.org/?probe=0b08b7a631) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| HP            | Notebook                    | [70ee3adf89](https://linux-hardware.org/?probe=70ee3adf89) | May 08, 2023 |
| Samsung       | 530XBB                      | [4d039b72a7](https://linux-hardware.org/?probe=4d039b72a7) | May 08, 2023 |
| Dell          | XPS 13 9305                 | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| HP            | x2 210                      | [f60c4cb29b](https://linux-hardware.org/?probe=f60c4cb29b) | May 07, 2023 |
| Apple         | MacBook4,1                  | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Latitude E6520              | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| Google        | Glimmer                     | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| Sony          | SVF1521C6EW                 | [57e1c14061](https://linux-hardware.org/?probe=57e1c14061) | Apr 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| HP            | Laptop 15-bs2xx             | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Google        | Chell                       | [1d1b263f21](https://linux-hardware.org/?probe=1d1b263f21) | Apr 27, 2023 |
| ASUSTek       | K52JB                       | [e9237f0d53](https://linux-hardware.org/?probe=e9237f0d53) | Apr 27, 2023 |
| Toshiba       | Satellite C660              | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| Dell          | Latitude 5290               | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| ASUSTek       | K52JB                       | [70a0b986fa](https://linux-hardware.org/?probe=70a0b986fa) | Apr 18, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| GPU Compan... | GWTN116-3                   | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| HP            | Pavilion dv6                | [d938ba339d](https://linux-hardware.org/?probe=d938ba339d) | Apr 14, 2023 |
| Intel         | W7650                       | [3e4c54a5f0](https://linux-hardware.org/?probe=3e4c54a5f0) | Apr 11, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| Toshiba       | Satellite P70-A             | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| Acer          | Aspire E1-570               | [ad70ba8e9d](https://linux-hardware.org/?probe=ad70ba8e9d) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP            | Pavilion 15                 | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | Laptop 15-da0xxx            | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| ASUSTek       | K52JB                       | [0e18c3546c](https://linux-hardware.org/?probe=0e18c3546c) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fe79f70952](https://linux-hardware.org/?probe=fe79f70952) | Mar 27, 2023 |
| Apple         | MacBookPro9,2               | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| Packard Be... | EasyNote SB65               | [f49cf1aa7a](https://linux-hardware.org/?probe=f49cf1aa7a) | Mar 25, 2023 |
| HP            | Laptop 17-ak0xx             | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| Samsung       | 530XBB                      | [2bb5946ee7](https://linux-hardware.org/?probe=2bb5946ee7) | Mar 23, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| Dell          | Latitude 5290               | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| Dell          | Latitude 7480               | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| MSI           | S12T 3M/S12 3M              | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| HP            | Compaq Presario CQ60        | [4167bec602](https://linux-hardware.org/?probe=4167bec602) | Mar 09, 2023 |
| HP            | Laptop 15-da0xxx            | [f4e7268671](https://linux-hardware.org/?probe=f4e7268671) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| MSI           | GS65 Stealth 9SD            | [1eef9edf97](https://linux-hardware.org/?probe=1eef9edf97) | Mar 04, 2023 |
| Dell          | Latitude E6230              | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| HP            | Laptop 14-dk0xxx            | [b492e1c092](https://linux-hardware.org/?probe=b492e1c092) | Mar 04, 2023 |
| DEXP          | Aquilon C15                 | [9ae006e12a](https://linux-hardware.org/?probe=9ae006e12a) | Mar 03, 2023 |
| Intel         | W7650                       | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Google        | Celes                       | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Dell          | Inspiron 1525               | [264f8cb6db](https://linux-hardware.org/?probe=264f8cb6db) | Feb 27, 2023 |
| Getac         | V200-X                      | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| HP            | Pavilion 17                 | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | [9c3a1f5cd5](https://linux-hardware.org/?probe=9c3a1f5cd5) | Feb 26, 2023 |
| Unknown       | Unknown                     | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| Apple         | MacBookPro8,1               | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Positivo      | Q232A                       | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [6f9ef751cd](https://linux-hardware.org/?probe=6f9ef751cd) | Feb 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Medion        | Akoya E6412T                | [41a31b6bd1](https://linux-hardware.org/?probe=41a31b6bd1) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| HP            | Notebook                    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [d159971f77](https://linux-hardware.org/?probe=d159971f77) | Feb 18, 2023 |
| Getac         | V200-X                      | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| Toshiba       | Satellite L650              | [553bddf256](https://linux-hardware.org/?probe=553bddf256) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| Acer          | Extensa 2540                | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| Acer          | Aspire A515-45              | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Insyde        | CherryTrail                 | [db3d49fa06](https://linux-hardware.org/?probe=db3d49fa06) | Feb 08, 2023 |
| Toshiba       | Satellite C55D-A            | [38083cc2a4](https://linux-hardware.org/?probe=38083cc2a4) | Feb 05, 2023 |
| Acer          | TravelMate P253             | [b2cad8970a](https://linux-hardware.org/?probe=b2cad8970a) | Feb 04, 2023 |
| Acer          | AO756                       | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Intel         | Unknown                     | [f387a4b732](https://linux-hardware.org/?probe=f387a4b732) | Jan 29, 2023 |
| Intel         | Unknown                     | [79aa357327](https://linux-hardware.org/?probe=79aa357327) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| Dell          | Latitude E6410              | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | [be66e9073f](https://linux-hardware.org/?probe=be66e9073f) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | [3a8aced1b7](https://linux-hardware.org/?probe=3a8aced1b7) | Jan 25, 2023 |
| Toshiba       | Satellite Pro S500          | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| ASUSTek       | 1011PX                      | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| HP            | Laptop 15-da0xxx            | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| Acer          | Aspire ES1-711              | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Acer          | Aspire One 721              | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| Toshiba       | Satellite Pro S500          | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| Google        | Candy                       | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| ASUSTek       | F50SV                       | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Google        | Celes                       | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| ASUSTek       | T100TA                      | [73a67d66af](https://linux-hardware.org/?probe=73a67d66af) | Jan 02, 2023 |
| Acer          | Aspire SW3-013              | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| Google        | Candy                       | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Google        | Edgar                       | [738a0d9324](https://linux-hardware.org/?probe=738a0d9324) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Acer          | Aspire SW3-013              | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Digma         | CITI E401 ET4007EW          | [252a51f201](https://linux-hardware.org/?probe=252a51f201) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| HP            | Stream Notebook PC 11       | [f33ebabb99](https://linux-hardware.org/?probe=f33ebabb99) | Dec 24, 2022 |
| Positivo      | C14CR21                     | [be49c26bb4](https://linux-hardware.org/?probe=be49c26bb4) | Dec 21, 2022 |
| HP            | Compaq 6715b (RM174UT#AB... | [db3b8615f7](https://linux-hardware.org/?probe=db3b8615f7) | Dec 21, 2022 |
| Dell          | Latitude E7470              | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| Google        | Coral                       | [8e2407d4b2](https://linux-hardware.org/?probe=8e2407d4b2) | Dec 19, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| HP            | 2000                        | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| HP            | Compaq 6830s                | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Apple         | MacBookPro8,1               | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| ASUSTek       | K50C                        | [6cf2037e0f](https://linux-hardware.org/?probe=6cf2037e0f) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Apple         | MacBookPro8,1               | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Toshiba       | Satellite Pro S500          | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| Apple         | MacBookPro8,1               | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| GPU Compan... | GWTC116-2                   | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| HP            | Laptop 15-da0xxx            | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| ASUSTek       | K70IO                       | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| HP            | 620                         | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| Dell          | Inspiron 15-3552            | [03a1a706d1](https://linux-hardware.org/?probe=03a1a706d1) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [b37755877d](https://linux-hardware.org/?probe=b37755877d) | Nov 24, 2022 |
| Unknown       | Unknown                     | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| HP            | Pavilion g6                 | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| HP            | 620                         | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| HP            | Pavilion g6                 | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| ASUSTek       | K55A                        | [d09b309d4d](https://linux-hardware.org/?probe=d09b309d4d) | Nov 19, 2022 |
| GPU Compan... | GWTC116-2                   | [4825e06bd4](https://linux-hardware.org/?probe=4825e06bd4) | Nov 19, 2022 |
| GPU Compan... | GWTC116-2                   | [57bcd4363a](https://linux-hardware.org/?probe=57bcd4363a) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| ASUSTek       | T100TA                      | [3d49b98878](https://linux-hardware.org/?probe=3d49b98878) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| Acer          | AOD255E                     | [817724283b](https://linux-hardware.org/?probe=817724283b) | Nov 11, 2022 |
| Toshiba       | Satellite L15-B             | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| Lenovo        | G50-45 80E3                 | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| HP            | EliteBook 850 G5            | [3408fb4c36](https://linux-hardware.org/?probe=3408fb4c36) | Nov 07, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [29617200dd](https://linux-hardware.org/?probe=29617200dd) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [24f27140f8](https://linux-hardware.org/?probe=24f27140f8) | Nov 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [027cfb43c4](https://linux-hardware.org/?probe=027cfb43c4) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [113930496e](https://linux-hardware.org/?probe=113930496e) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2934bab108](https://linux-hardware.org/?probe=2934bab108) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | [a5712d3982](https://linux-hardware.org/?probe=a5712d3982) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | [9b53e5c27d](https://linux-hardware.org/?probe=9b53e5c27d) | Oct 31, 2022 |
| Acer          | Aspire E1-571               | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Teclast       | F7 Plus                     | [f416278476](https://linux-hardware.org/?probe=f416278476) | Oct 29, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [4b4c00b0a9](https://linux-hardware.org/?probe=4b4c00b0a9) | Oct 28, 2022 |
| Acer          | Extensa 2509                | [a27b3d38a9](https://linux-hardware.org/?probe=a27b3d38a9) | Oct 27, 2022 |
| Google        | Apel                        | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Acer          | Aspire one                  | [fced25613a](https://linux-hardware.org/?probe=fced25613a) | Oct 18, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| HP            | 431 Notebook                | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| Lenovo        | G50-70 20351                | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | Aspire 4739Z                | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Toshiba       | Satellite C655D             | [80ec8503c0](https://linux-hardware.org/?probe=80ec8503c0) | Oct 05, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Packard Be... | EasyNote TS44HR             | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| ASUSTek       | X451CA                      | [bdfe92eb66](https://linux-hardware.org/?probe=bdfe92eb66) | Sep 21, 2022 |
| Gateway       | NE46R                       | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| Dell          | Inspiron 11-3168            | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Star Labs     | Lite                        | [c08b209f09](https://linux-hardware.org/?probe=c08b209f09) | Sep 09, 2022 |
| HP            | ProBook 4730s               | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Acer          | AOA150                      | [3146707963](https://linux-hardware.org/?probe=3146707963) | Sep 02, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| HP            | ProBook 450 G6              | [7763040d56](https://linux-hardware.org/?probe=7763040d56) | Aug 30, 2022 |
| Lenovo        | B590 20208                  | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Standard      | AHV                         | [1a4d477350](https://linux-hardware.org/?probe=1a4d477350) | Aug 24, 2022 |
| Acer          | Aspire 7250G                | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| Dell          | Vostro 3360                 | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| OEM           | Unknown                     | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Dell          | Precision 3510              | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| HP            | 240 G8 Notebook PC          | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| Google        | Celes                       | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Google        | Celes                       | [fae813e4dc](https://linux-hardware.org/?probe=fae813e4dc) | Jul 31, 2022 |
| Dell          | XPS M1330                   | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Toshiba       | NB250                       | [e320782bcf](https://linux-hardware.org/?probe=e320782bcf) | Jul 30, 2022 |
| HP            | Presario CQ56               | [aead18fee1](https://linux-hardware.org/?probe=aead18fee1) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [894bf232f8](https://linux-hardware.org/?probe=894bf232f8) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [eb752c319e](https://linux-hardware.org/?probe=eb752c319e) | Jul 28, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [3451f0e8b5](https://linux-hardware.org/?probe=3451f0e8b5) | Jul 26, 2022 |
| ASUSTek       | 900                         | [ae42d40b7a](https://linux-hardware.org/?probe=ae42d40b7a) | Jul 25, 2022 |
| HP            | Laptop 17-cn0xxx            | [55d8e5a779](https://linux-hardware.org/?probe=55d8e5a779) | Jul 24, 2022 |
| Sony          | VPCEB15FM                   | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| Dell          | Inspiron N5010              | [826672a49e](https://linux-hardware.org/?probe=826672a49e) | Jul 22, 2022 |
| HP            | 245 G2                      | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| Samsung       | N130                        | [4874e0173d](https://linux-hardware.org/?probe=4874e0173d) | Jul 17, 2022 |
| HP            | 245 G2                      | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Lenovo        | G50-30 80G0                 | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Standard      | AHV                         | [2499cab6bd](https://linux-hardware.org/?probe=2499cab6bd) | Jul 12, 2022 |
| Nokia         | Booklet 3G                  | [08b1b304ae](https://linux-hardware.org/?probe=08b1b304ae) | Jul 11, 2022 |
| Chuwi         | GemiBook Pro                | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| Toshiba       | Satellite A300              | [dd80f74e85](https://linux-hardware.org/?probe=dd80f74e85) | Jul 05, 2022 |
| Toshiba       | Satellite A300              | [69e4341e99](https://linux-hardware.org/?probe=69e4341e99) | Jul 05, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| MSI           | VR630                       | [097cd732b3](https://linux-hardware.org/?probe=097cd732b3) | Jun 27, 2022 |
| Apple         | MacBookPro10,1              | [a27f696a28](https://linux-hardware.org/?probe=a27f696a28) | Jun 27, 2022 |
| Google        | Bobba360                    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | [f6f825d83a](https://linux-hardware.org/?probe=f6f825d83a) | Jun 22, 2022 |
| HP            | Notebook                    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| Gateway       | Sonic-C                     | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Dell          | Latitude XT                 | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Notebook                    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| Intel         | W7650                       | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| ASUSTek       | 1000H                       | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | G62                         | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| HP            | Pavilion g6                 | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Packard Be... | EasyNote TE11HC             | [8350bd6d87](https://linux-hardware.org/?probe=8350bd6d87) | May 30, 2022 |
| HP            | Berknip                     | [c81d3442c2](https://linux-hardware.org/?probe=c81d3442c2) | May 27, 2022 |
| ASUSTek       | X205TA                      | [9fa4c6beef](https://linux-hardware.org/?probe=9fa4c6beef) | May 26, 2022 |
| HP            | Pavilion g6                 | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| HP            | OMEN by Laptop              | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| Toshiba       | Satellite L40               | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| ASUSTek       | X402CA                      | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [68ee4b094a](https://linux-hardware.org/?probe=68ee4b094a) | May 13, 2022 |
| Acer          | Swift SF114-34              | [5774e3f483](https://linux-hardware.org/?probe=5774e3f483) | May 12, 2022 |
| Acer          | Aspire A317-33              | [f3bd3e55aa](https://linux-hardware.org/?probe=f3bd3e55aa) | May 12, 2022 |
| Acer          | Aspire A317-33              | [3a09364bb2](https://linux-hardware.org/?probe=3a09364bb2) | May 12, 2022 |
| Toshiba       | Satellite P20               | [923779da79](https://linux-hardware.org/?probe=923779da79) | May 11, 2022 |
| Acer          | Aspire V5-573G              | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Positivo      | AT300b                      | [7f5c5ceed4](https://linux-hardware.org/?probe=7f5c5ceed4) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| ASUSTek       | 900                         | [6cbd0391b3](https://linux-hardware.org/?probe=6cbd0391b3) | May 07, 2022 |
| Intel         | W7650                       | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| ASUSTek       | K55VD                       | [8ff47b2a2c](https://linux-hardware.org/?probe=8ff47b2a2c) | May 05, 2022 |
| Toshiba       | Satellite C670D-12N         | [f6bd692d1f](https://linux-hardware.org/?probe=f6bd692d1f) | May 05, 2022 |
| Apple         | MacBookPro14,1              | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [4682643304](https://linux-hardware.org/?probe=4682643304) | May 05, 2022 |
| Apple         | MacBookPro14,1              | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [5a36e4d0fc](https://linux-hardware.org/?probe=5a36e4d0fc) | May 04, 2022 |
| Samsung       | RV415/RV515                 | [bc88bd7582](https://linux-hardware.org/?probe=bc88bd7582) | May 04, 2022 |
| HP            | Pavilion g4                 | [afad13fa01](https://linux-hardware.org/?probe=afad13fa01) | May 04, 2022 |
| ASUSTek       | 900                         | [70b70a4392](https://linux-hardware.org/?probe=70b70a4392) | May 03, 2022 |
| Fujitsu       | LIFEBOOK S751               | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | [c206790d1e](https://linux-hardware.org/?probe=c206790d1e) | May 01, 2022 |
| HP            | EliteBook 8570p             | [2dffdad8a4](https://linux-hardware.org/?probe=2dffdad8a4) | May 01, 2022 |
| Google        | Bobba360                    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| YASHI         | MYBOOK 360                  | [d44c4fd567](https://linux-hardware.org/?probe=d44c4fd567) | Apr 29, 2022 |
| HP            | Pavilion g4                 | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [753e3fda7d](https://linux-hardware.org/?probe=753e3fda7d) | Apr 26, 2022 |
| Dell          | Latitude 7480               | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| Gigabyte      | M912                        | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | 1215N                       | [b921f6fbae](https://linux-hardware.org/?probe=b921f6fbae) | Apr 24, 2022 |
| Mediacom      | GTZS                        | [41939828a4](https://linux-hardware.org/?probe=41939828a4) | Apr 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [c8f16c0d16](https://linux-hardware.org/?probe=c8f16c0d16) | Apr 22, 2022 |
| Google        | Droid                       | [b7b4dc6117](https://linux-hardware.org/?probe=b7b4dc6117) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ff77bbf8ae](https://linux-hardware.org/?probe=ff77bbf8ae) | Apr 22, 2022 |
| Mediacom      | GTZS                        | [edc22ef82a](https://linux-hardware.org/?probe=edc22ef82a) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| HP            | Pavilion dv4                | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| Intel         | W7650                       | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| HP            | Compaq Presario C700        | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Dell          | Inspiron 3180               | [9d280b4678](https://linux-hardware.org/?probe=9d280b4678) | Apr 14, 2022 |
| Dell          | Latitude E6410              | [e5e350a4a8](https://linux-hardware.org/?probe=e5e350a4a8) | Apr 13, 2022 |
| Google        | Kip                         | [4641a94428](https://linux-hardware.org/?probe=4641a94428) | Apr 13, 2022 |
| Dell          | Latitude E7240              | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| ASUSTek       | 1000H                       | [725f548eab](https://linux-hardware.org/?probe=725f548eab) | Apr 09, 2022 |
| Dell          | Inspiron N4010              | [0aac536dbf](https://linux-hardware.org/?probe=0aac536dbf) | Apr 04, 2022 |
| Samsung       | N100SP                      | [6a70399256](https://linux-hardware.org/?probe=6a70399256) | Mar 31, 2022 |
| Acer          | AOA150                      | [a59a005250](https://linux-hardware.org/?probe=a59a005250) | Mar 30, 2022 |
| Intel         | W7650                       | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| Haier         | U1520EM                     | [5fde1c39e9](https://linux-hardware.org/?probe=5fde1c39e9) | Mar 25, 2022 |
| Fujitsu Si... | AMILO Li3710                | [ab84e23108](https://linux-hardware.org/?probe=ab84e23108) | Mar 24, 2022 |
| AMI           | Cherry Trail CR             | [af80d44a27](https://linux-hardware.org/?probe=af80d44a27) | Mar 23, 2022 |
| HP            | Pavilion g7                 | [2c480cdfac](https://linux-hardware.org/?probe=2c480cdfac) | Mar 22, 2022 |
| IBM           | Unknown                     | [2bcbb8a946](https://linux-hardware.org/?probe=2bcbb8a946) | Mar 21, 2022 |
| HP            | EliteBook 745 G6            | [a3f94c2957](https://linux-hardware.org/?probe=a3f94c2957) | Mar 20, 2022 |
| Apple         | MacBookPro6,2               | [d4c7ecbc5e](https://linux-hardware.org/?probe=d4c7ecbc5e) | Mar 20, 2022 |
| Acer          | AO751h                      | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| Google        | Celes                       | [cfcec68610](https://linux-hardware.org/?probe=cfcec68610) | Mar 15, 2022 |
| HP            | Laptop 15-bs0xx             | [37a24fa0b8](https://linux-hardware.org/?probe=37a24fa0b8) | Mar 13, 2022 |
| HP            | Laptop 15-da0xxx            | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | [707be96775](https://linux-hardware.org/?probe=707be96775) | Mar 13, 2022 |
| ASUSTek       | X550LA                      | [eb7071ed13](https://linux-hardware.org/?probe=eb7071ed13) | Mar 12, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| Fujitsu Si... | AMILO Li3710                | [7a4a682f45](https://linux-hardware.org/?probe=7a4a682f45) | Mar 07, 2022 |
| Lenovo        | G50-30 80G0                 | [efc41b55f4](https://linux-hardware.org/?probe=efc41b55f4) | Mar 06, 2022 |
| Dell          | Inspiron 1090               | [31efa1bb6f](https://linux-hardware.org/?probe=31efa1bb6f) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | [6a97a96f56](https://linux-hardware.org/?probe=6a97a96f56) | Mar 01, 2022 |
| Dell          | Inspiron 1090               | [9d63b9e47f](https://linux-hardware.org/?probe=9d63b9e47f) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [9a59eff157](https://linux-hardware.org/?probe=9a59eff157) | Feb 26, 2022 |
| Toshiba       | Satellite S55-B             | [f07aaa2fd3](https://linux-hardware.org/?probe=f07aaa2fd3) | Feb 25, 2022 |
| Insyde        | N116                        | [a6dd43dfb4](https://linux-hardware.org/?probe=a6dd43dfb4) | Feb 21, 2022 |
| Toshiba       | Satellite S55-B             | [8551d043a9](https://linux-hardware.org/?probe=8551d043a9) | Feb 20, 2022 |
| Intel         | W7650                       | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |
| Alienware     | M17                         | [9d29db918d](https://linux-hardware.org/?probe=9d29db918d) | Feb 18, 2022 |
| HP            | Pavilion g6                 | [5601a4d596](https://linux-hardware.org/?probe=5601a4d596) | Feb 14, 2022 |
| HP            | Laptop 15-da0xxx            | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [1f9694d47d](https://linux-hardware.org/?probe=1f9694d47d) | Feb 12, 2022 |
| Sony          | VGN-SZ71WN_C                | [677d24e366](https://linux-hardware.org/?probe=677d24e366) | Feb 11, 2022 |
| Positivo      | N600                        | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Dell          | Inspiron 11-3168            | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| Dell          | Latitude E5540              | [e895dcce0f](https://linux-hardware.org/?probe=e895dcce0f) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| HP            | 255 G6 Notebook PC          | [9c5efed237](https://linux-hardware.org/?probe=9c5efed237) | Feb 06, 2022 |
| Lenovo        | 3000 N200 0769ALU           | [695855f143](https://linux-hardware.org/?probe=695855f143) | Feb 05, 2022 |
| Lenovo        | 3000 N200 0769ALU           | [661ffedd80](https://linux-hardware.org/?probe=661ffedd80) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | [4c355aa7c2](https://linux-hardware.org/?probe=4c355aa7c2) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | [61fc6b2cb0](https://linux-hardware.org/?probe=61fc6b2cb0) | Feb 05, 2022 |
| Toshiba       | Satellite C875              | [1dd31ebdd6](https://linux-hardware.org/?probe=1dd31ebdd6) | Feb 02, 2022 |
| Insyde        | i101c                       | [375f7e61b2](https://linux-hardware.org/?probe=375f7e61b2) | Feb 02, 2022 |
| Lenovo        | ThinkPad T460 20FMS2J000    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Prestigio     | PSB141C01BFH                | [5adcd620f6](https://linux-hardware.org/?probe=5adcd620f6) | Jan 30, 2022 |
| Google        | Peppy                       | [15cd563f21](https://linux-hardware.org/?probe=15cd563f21) | Jan 27, 2022 |
| ASUSTek       | GL553VW                     | [7713319e74](https://linux-hardware.org/?probe=7713319e74) | Jan 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [433e46caa5](https://linux-hardware.org/?probe=433e46caa5) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | [f88ac2dd3e](https://linux-hardware.org/?probe=f88ac2dd3e) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | [6c56c2c8b3](https://linux-hardware.org/?probe=6c56c2c8b3) | Jan 19, 2022 |
| Apple         | MacBookPro10,1              | [1aa2cd2e8f](https://linux-hardware.org/?probe=1aa2cd2e8f) | Jan 19, 2022 |
| Dell          | Inspiron 15-3573            | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Apple         | MacBookPro10,2              | [804b4adedc](https://linux-hardware.org/?probe=804b4adedc) | Jan 15, 2022 |
| HP            | ProBook 450 G2              | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| HP            | Notebook                    | [847afd8ac5](https://linux-hardware.org/?probe=847afd8ac5) | Jan 12, 2022 |
| System76      | Lemur Pro                   | [fa22d4610e](https://linux-hardware.org/?probe=fa22d4610e) | Jan 11, 2022 |
| Positivo      | N600                        | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| HP            | Compaq 6910p (GX316UC#AB... | [0ffa23c15e](https://linux-hardware.org/?probe=0ffa23c15e) | Jan 07, 2022 |
| Toshiba       | Satellite L50D-B            | [e253741d9f](https://linux-hardware.org/?probe=e253741d9f) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | [66d00e2cd5](https://linux-hardware.org/?probe=66d00e2cd5) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | [7cf1327087](https://linux-hardware.org/?probe=7cf1327087) | Jan 05, 2022 |
| HP            | Pavilion dv2700             | [c8aafbbc8d](https://linux-hardware.org/?probe=c8aafbbc8d) | Jan 04, 2022 |
| Alienware     | m15                         | [a0d4f93250](https://linux-hardware.org/?probe=a0d4f93250) | Jan 04, 2022 |
| Apple         | MacBookPro8,1               | [eaf2e708d9](https://linux-hardware.org/?probe=eaf2e708d9) | Jan 03, 2022 |
| Acer          | Aspire 7715Z                | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| Lanix         | NeuronALV5                  | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| Dell          | Latitude 7480               | [a338b67d45](https://linux-hardware.org/?probe=a338b67d45) | Dec 30, 2021 |
| Sony          | VPCEJ1E1E                   | [0211323709](https://linux-hardware.org/?probe=0211323709) | Dec 28, 2021 |
| Dell          | Inspiron 15 3515            | [8d130910ab](https://linux-hardware.org/?probe=8d130910ab) | Dec 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [f5924cb8b4](https://linux-hardware.org/?probe=f5924cb8b4) | Dec 25, 2021 |
| Sony          | VPCEJ1E1E                   | [d8d2b553bf](https://linux-hardware.org/?probe=d8d2b553bf) | Dec 24, 2021 |
| I-Life Dig... | ZED AIR                     | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| Acer          | AOA150                      | [47cae573c1](https://linux-hardware.org/?probe=47cae573c1) | Dec 22, 2021 |
| Acer          | Aspire E1-572G              | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| Acer          | Aspire F5-573G              | [2e9fd50292](https://linux-hardware.org/?probe=2e9fd50292) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | [452b8c0ac4](https://linux-hardware.org/?probe=452b8c0ac4) | Dec 20, 2021 |
| Dell          | Latitude E6520              | [c7edb79be7](https://linux-hardware.org/?probe=c7edb79be7) | Dec 20, 2021 |
| Samsung       | 275E4E/275E5E               | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [b956646608](https://linux-hardware.org/?probe=b956646608) | Dec 12, 2021 |
| HP            | EliteBook 850 G3            | [7cf21876b0](https://linux-hardware.org/?probe=7cf21876b0) | Dec 12, 2021 |
| Acer          | Aspire 5742G                | [950da990e7](https://linux-hardware.org/?probe=950da990e7) | Dec 12, 2021 |
| ASUSTek       | 1015BXO                     | [f9eb963d74](https://linux-hardware.org/?probe=f9eb963d74) | Dec 12, 2021 |
| MSI           | Katana GF76 11UC            | [73fd53a50c](https://linux-hardware.org/?probe=73fd53a50c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Positivo      | AT300b                      | [20b3635188](https://linux-hardware.org/?probe=20b3635188) | Dec 06, 2021 |
| HP            | Compaq 6510b (GR691EA#AB... | [4d657211eb](https://linux-hardware.org/?probe=4d657211eb) | Dec 04, 2021 |
| Acer          | AOD255E                     | [390afd35cb](https://linux-hardware.org/?probe=390afd35cb) | Dec 03, 2021 |
| HP            | ProBook 440 G7              | [155ec30920](https://linux-hardware.org/?probe=155ec30920) | Dec 03, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [edce40927f](https://linux-hardware.org/?probe=edce40927f) | Dec 01, 2021 |
| Toshiba       | Satellite C50-A-19U         | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| HP            | Compaq 6720s                | [2c62d9df9c](https://linux-hardware.org/?probe=2c62d9df9c) | Nov 28, 2021 |
| ASUSTek       | 1000HE                      | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| I-Life Dig... | ZED AIR                     | [a6e2e61f26](https://linux-hardware.org/?probe=a6e2e61f26) | Nov 24, 2021 |
| Toshiba       | Satellite L40               | [43d9bb451a](https://linux-hardware.org/?probe=43d9bb451a) | Nov 23, 2021 |
| Dell          | Latitude 3330               | [2c8f88588b](https://linux-hardware.org/?probe=2c8f88588b) | Nov 23, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | [867419b410](https://linux-hardware.org/?probe=867419b410) | Nov 21, 2021 |
| Medion        | P6630                       | [edc09031bd](https://linux-hardware.org/?probe=edc09031bd) | Nov 16, 2021 |
| HP            | Pavilion dv6                | [591f986631](https://linux-hardware.org/?probe=591f986631) | Nov 14, 2021 |
| ASUSTek       | 1015BX                      | [51933ea3ac](https://linux-hardware.org/?probe=51933ea3ac) | Nov 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [0e17c0b84d](https://linux-hardware.org/?probe=0e17c0b84d) | Nov 13, 2021 |
| HP            | ProBook 440 G7              | [35b6f85a28](https://linux-hardware.org/?probe=35b6f85a28) | Nov 10, 2021 |
| Acer          | AO751h                      | [e2beb798cc](https://linux-hardware.org/?probe=e2beb798cc) | Nov 10, 2021 |
| Dell          | Inspiron MM061              | [03bba840c5](https://linux-hardware.org/?probe=03bba840c5) | Nov 07, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | [4e3e71f6ab](https://linux-hardware.org/?probe=4e3e71f6ab) | Nov 07, 2021 |
| HP            | Laptop 15s-fq1xxx           | [25f858c7b1](https://linux-hardware.org/?probe=25f858c7b1) | Nov 05, 2021 |
| Mediacom      | GTZS                        | [a2a881793d](https://linux-hardware.org/?probe=a2a881793d) | Nov 03, 2021 |
| HP            | ProBook 4540s               | [fca622f4c4](https://linux-hardware.org/?probe=fca622f4c4) | Nov 01, 2021 |
| Samsung       | R40/R41                     | [5c44d1e88b](https://linux-hardware.org/?probe=5c44d1e88b) | Nov 01, 2021 |
| HP            | Pavilion dv6                | [e84cd86eb0](https://linux-hardware.org/?probe=e84cd86eb0) | Oct 31, 2021 |
| HP            | Pavilion Notebook           | [2c6c86b1fb](https://linux-hardware.org/?probe=2c6c86b1fb) | Oct 31, 2021 |
| HP            | ProBook 4540s               | [e12d7e47e6](https://linux-hardware.org/?probe=e12d7e47e6) | Oct 31, 2021 |
| HP            | ProBook 4540s               | [e565d7befe](https://linux-hardware.org/?probe=e565d7befe) | Oct 31, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f86520f5a7](https://linux-hardware.org/?probe=f86520f5a7) | Oct 28, 2021 |
| HP            | Presario CQ58               | [60d72bdce7](https://linux-hardware.org/?probe=60d72bdce7) | Oct 28, 2021 |
| HP            | Presario CQ58               | [8989debda6](https://linux-hardware.org/?probe=8989debda6) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | [e1e44b58f3](https://linux-hardware.org/?probe=e1e44b58f3) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | [42d3788463](https://linux-hardware.org/?probe=42d3788463) | Oct 27, 2021 |
| HP            | 2000                        | [65ec913842](https://linux-hardware.org/?probe=65ec913842) | Oct 27, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1663dc4946](https://linux-hardware.org/?probe=1663dc4946) | Oct 26, 2021 |
| Samsung       | N100SP                      | [7e4ef50289](https://linux-hardware.org/?probe=7e4ef50289) | Oct 26, 2021 |
| Acer          | TravelMate P253             | [d74c10f41f](https://linux-hardware.org/?probe=d74c10f41f) | Oct 24, 2021 |
| Dell          | Inspiron 3583               | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Sony          | VGN-CR11Z_R                 | [538c03b235](https://linux-hardware.org/?probe=538c03b235) | Oct 23, 2021 |
| Samsung       | N100SP                      | [4d8eadf806](https://linux-hardware.org/?probe=4d8eadf806) | Oct 23, 2021 |
| Apple         | MacBookPro8,1               | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Sony          | VGN-CR11Z_R                 | [57043d09fe](https://linux-hardware.org/?probe=57043d09fe) | Oct 22, 2021 |
| Acer          | Aspire ES1-131              | [de7bee5c36](https://linux-hardware.org/?probe=de7bee5c36) | Oct 20, 2021 |
| Intel         | W7650                       | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| Toshiba       | Satellite C50D-A-13G        | [32f90e6cf8](https://linux-hardware.org/?probe=32f90e6cf8) | Oct 18, 2021 |
| MSI           | Modern 15 A10M              | [184c512c35](https://linux-hardware.org/?probe=184c512c35) | Oct 18, 2021 |
| Lenovo        | ThinkPad X61 76744NG        | [ee90608b54](https://linux-hardware.org/?probe=ee90608b54) | Oct 15, 2021 |
| NOBLEX        | E11IS2                      | [463e1f38e8](https://linux-hardware.org/?probe=463e1f38e8) | Oct 14, 2021 |
| HP            | Pavilion x2 Detachable      | [e5702172f9](https://linux-hardware.org/?probe=e5702172f9) | Oct 11, 2021 |
| HP            | Notebook                    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | 2000                        | [d84546de1b](https://linux-hardware.org/?probe=d84546de1b) | Oct 08, 2021 |
| HP            | Pavilion x2 Detachable      | [f81838645f](https://linux-hardware.org/?probe=f81838645f) | Oct 07, 2021 |
| HP            | Notebook                    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Dell          | Inspiron 15-3567            | [414e52d7a4](https://linux-hardware.org/?probe=414e52d7a4) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a927e8ff8e](https://linux-hardware.org/?probe=a927e8ff8e) | Oct 06, 2021 |
| HP            | Laptop 15-da0xxx            | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| Sony          | VPCSA2FGX                   | [60cfbaebef](https://linux-hardware.org/?probe=60cfbaebef) | Sep 29, 2021 |
| HP            | EliteBook 2560p             | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Apple         | MacBookPro8,1               | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| ASUSTek       | 1215B                       | [c45de8d3b1](https://linux-hardware.org/?probe=c45de8d3b1) | Sep 21, 2021 |
| Toshiba       | Satellite L20               | [654c60e971](https://linux-hardware.org/?probe=654c60e971) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Unknown       | Unknown                     | [64604612b2](https://linux-hardware.org/?probe=64604612b2) | Sep 19, 2021 |
| Lenovo        | G50-80 80L0                 | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| Dell          | Inspiron 3558               | [be96e8a7e1](https://linux-hardware.org/?probe=be96e8a7e1) | Sep 13, 2021 |
| Dell          | Inspiron 3558               | [f1414fdf7b](https://linux-hardware.org/?probe=f1414fdf7b) | Sep 13, 2021 |
| Apple         | MacBookPro8,1               | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| Lenovo        | G50-80 80L0                 | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| HP            | ProBook 450 G1              | [284c0763b3](https://linux-hardware.org/?probe=284c0763b3) | Sep 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| Toshiba       | Satellite A215              | [2d0d778e8e](https://linux-hardware.org/?probe=2d0d778e8e) | Aug 31, 2021 |
| Notebook      | NL40_50GU                   | [977812d04b](https://linux-hardware.org/?probe=977812d04b) | Aug 29, 2021 |
| Google        | Careena                     | [ab1bafda25](https://linux-hardware.org/?probe=ab1bafda25) | Aug 27, 2021 |
| Toshiba       | Satellite A205              | [50f9ce0180](https://linux-hardware.org/?probe=50f9ce0180) | Aug 26, 2021 |
| Dell          | XPS 13 9300                 | [6e1f484406](https://linux-hardware.org/?probe=6e1f484406) | Aug 24, 2021 |
| Toshiba       | Satellite A205              | [63b870739f](https://linux-hardware.org/?probe=63b870739f) | Aug 19, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Toshiba       | Satellite A205              | [bc09a1e988](https://linux-hardware.org/?probe=bc09a1e988) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406138U       | [a72c7ecd8a](https://linux-hardware.org/?probe=a72c7ecd8a) | Aug 14, 2021 |
| Dell          | Inspiron 3583               | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [798feee097](https://linux-hardware.org/?probe=798feee097) | Aug 07, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [9b893159ef](https://linux-hardware.org/?probe=9b893159ef) | Aug 06, 2021 |
| HP            | Pavilion g4                 | [f1d3ddf197](https://linux-hardware.org/?probe=f1d3ddf197) | Aug 06, 2021 |
| Dell          | G3 3500                     | [239b740235](https://linux-hardware.org/?probe=239b740235) | Aug 03, 2021 |
| Mediacom      | SmartBook 14 FullHD - SB... | [0719538c6e](https://linux-hardware.org/?probe=0719538c6e) | Aug 02, 2021 |
| HP            | OMEN by Laptop              | [7ca0de35b4](https://linux-hardware.org/?probe=7ca0de35b4) | Aug 01, 2021 |
| Dell          | Latitude E5450              | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| HP            | ProBook 6450b               | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| Acer          | Aspire 5735                 | [db933e0ebd](https://linux-hardware.org/?probe=db933e0ebd) | Jul 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d77a8cde0f](https://linux-hardware.org/?probe=d77a8cde0f) | Jul 23, 2021 |
| Dell          | Inspiron M5040              | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Dell          | Inspiron 1018               | [2e26e3540a](https://linux-hardware.org/?probe=2e26e3540a) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | [b74062f49d](https://linux-hardware.org/?probe=b74062f49d) | Jul 20, 2021 |
| Sony          | SVE1113M1EW                 | [b01beadd52](https://linux-hardware.org/?probe=b01beadd52) | Jul 16, 2021 |
| Toshiba       | K201                        | [85abf16ca0](https://linux-hardware.org/?probe=85abf16ca0) | Jul 15, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [d4852f4d01](https://linux-hardware.org/?probe=d4852f4d01) | Jul 14, 2021 |
| Google        | Winky                       | [696230b066](https://linux-hardware.org/?probe=696230b066) | Jul 14, 2021 |
| Google        | Winky                       | [6048ac2ff9](https://linux-hardware.org/?probe=6048ac2ff9) | Jul 14, 2021 |
| Apple         | MacBookPro10,2              | [0f8c7a6b66](https://linux-hardware.org/?probe=0f8c7a6b66) | Jul 12, 2021 |
| LEADER        | TW9/SW9                     | [6da16947e1](https://linux-hardware.org/?probe=6da16947e1) | Jul 07, 2021 |
| ASUSTek       | 1015PE                      | [051265df6e](https://linux-hardware.org/?probe=051265df6e) | Jul 05, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [b083bc08c4](https://linux-hardware.org/?probe=b083bc08c4) | Jul 04, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| Apple         | MacBook4,1                  | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| MSI           | GX780R/GT780R/GT780DXR/G... | [212a084b93](https://linux-hardware.org/?probe=212a084b93) | Jul 01, 2021 |
| Samsung       | RV415/RV515                 | [581180a4d8](https://linux-hardware.org/?probe=581180a4d8) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | [99a0739814](https://linux-hardware.org/?probe=99a0739814) | Jun 28, 2021 |
| HP            | EliteBook 840 G6            | [cfd34d8c5b](https://linux-hardware.org/?probe=cfd34d8c5b) | Jun 22, 2021 |
| ASUSTek       | T100TA                      | [8a1c5e9daf](https://linux-hardware.org/?probe=8a1c5e9daf) | Jun 21, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [d94415969c](https://linux-hardware.org/?probe=d94415969c) | Jun 19, 2021 |
| Notebook      | NHxxRZQ                     | [221e4d197b](https://linux-hardware.org/?probe=221e4d197b) | Jun 19, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [fdbc9729c1](https://linux-hardware.org/?probe=fdbc9729c1) | Jun 18, 2021 |
| HP            | EliteBook 2560p             | [b8cf45e412](https://linux-hardware.org/?probe=b8cf45e412) | Jun 15, 2021 |
| Positivo      | Mobile                      | [050aa55013](https://linux-hardware.org/?probe=050aa55013) | Jun 14, 2021 |
| Samsung       | RC512                       | [d8681e5e08](https://linux-hardware.org/?probe=d8681e5e08) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Google        | Kohaku                      | [6de3f99f1d](https://linux-hardware.org/?probe=6de3f99f1d) | Jun 08, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | [0a5cb29f98](https://linux-hardware.org/?probe=0a5cb29f98) | Jun 07, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | [29f66db2d1](https://linux-hardware.org/?probe=29f66db2d1) | Jun 07, 2021 |
| Acer          | Aspire 5715Z                | [5824a05a58](https://linux-hardware.org/?probe=5824a05a58) | Jun 05, 2021 |
| ASUSTek       | T100HAN                     | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| Lenovo        | ThinkPad T410s 2924C39      | [5dc4a1e557](https://linux-hardware.org/?probe=5dc4a1e557) | May 31, 2021 |
| Acer          | Aspire 5715Z                | [2e325cddc1](https://linux-hardware.org/?probe=2e325cddc1) | May 30, 2021 |
| Acer          | Aspire 5715Z                | [417206cc6a](https://linux-hardware.org/?probe=417206cc6a) | May 30, 2021 |
| Dell          | Latitude D820               | [5b23528d58](https://linux-hardware.org/?probe=5b23528d58) | May 29, 2021 |
| MSI           | Modern 15 A10M              | [23182c745b](https://linux-hardware.org/?probe=23182c745b) | May 27, 2021 |
| HP            | ProBook 6550b               | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | Latitude D630               | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| Acer          | Aspire 5715Z                | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Dell          | Inspiron MM061              | [3eb7729825](https://linux-hardware.org/?probe=3eb7729825) | May 23, 2021 |
| Lenovo        | G70-80 80FF                 | [fba07779e2](https://linux-hardware.org/?probe=fba07779e2) | May 21, 2021 |
| MSI           | Modern 15 A10M              | [001eb9ea2f](https://linux-hardware.org/?probe=001eb9ea2f) | May 21, 2021 |
| Lenovo        | ThinkPad W510 4318CTO       | [bc53ad8072](https://linux-hardware.org/?probe=bc53ad8072) | May 20, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | [6e24cb56ad](https://linux-hardware.org/?probe=6e24cb56ad) | May 19, 2021 |
| HP            | Presario V5000 (ET820UA#... | [f91a752d4d](https://linux-hardware.org/?probe=f91a752d4d) | May 19, 2021 |
| ASUSTek       | 1005HA                      | [e819e51835](https://linux-hardware.org/?probe=e819e51835) | May 18, 2021 |
| Acer          | Extensa 5620                | [2da2f6a795](https://linux-hardware.org/?probe=2da2f6a795) | May 17, 2021 |
| Apple         | MacBookPro8,1               | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Toshiba       | Satellite L70-B             | [aba62024a7](https://linux-hardware.org/?probe=aba62024a7) | May 15, 2021 |
| Sony          | VPCSB1V9E                   | [5682d68364](https://linux-hardware.org/?probe=5682d68364) | May 14, 2021 |
| Samsung       | R520/R522/R620              | [2216d5b0b1](https://linux-hardware.org/?probe=2216d5b0b1) | May 14, 2021 |
| Samsung       | R520/R522/R620              | [b724b0cc62](https://linux-hardware.org/?probe=b724b0cc62) | May 14, 2021 |
| Lenovo        | ThinkPad X240 20AMS2P400    | [9f6e7024d4](https://linux-hardware.org/?probe=9f6e7024d4) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | [d044706f11](https://linux-hardware.org/?probe=d044706f11) | May 13, 2021 |
| Lenovo        | G40-30 80FY                 | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | [25eb899222](https://linux-hardware.org/?probe=25eb899222) | May 12, 2021 |
| Unknown       | Unknown                     | [a54c655ae8](https://linux-hardware.org/?probe=a54c655ae8) | May 12, 2021 |
| Packard Be... | EasyNote MH35               | [b755c5449a](https://linux-hardware.org/?probe=b755c5449a) | May 11, 2021 |
| IBM           | ThinkPad Z60m 25303JM       | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [0b34a1f92d](https://linux-hardware.org/?probe=0b34a1f92d) | May 04, 2021 |
| HP            | Laptop 15-da0xxx            | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| HP            | Notebook                    | [ca99bba8dc](https://linux-hardware.org/?probe=ca99bba8dc) | May 02, 2021 |
| Lenovo        | 100-14IBY 80R7              | [61af9638d2](https://linux-hardware.org/?probe=61af9638d2) | Apr 30, 2021 |
| LG Electro... | S425-L.BC22P1               | [791fd9ff12](https://linux-hardware.org/?probe=791fd9ff12) | Apr 28, 2021 |
| Lenovo        | G460 20041                  | [4015285676](https://linux-hardware.org/?probe=4015285676) | Apr 26, 2021 |
| ASUSTek       | X102BA                      | [de8b267423](https://linux-hardware.org/?probe=de8b267423) | Apr 25, 2021 |
| ASUSTek       | X102BA                      | [c660d95c3f](https://linux-hardware.org/?probe=c660d95c3f) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | [e958267bec](https://linux-hardware.org/?probe=e958267bec) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | [cf6e170fcc](https://linux-hardware.org/?probe=cf6e170fcc) | Apr 25, 2021 |
| Dell          | Vostro A90                  | [21b167db8c](https://linux-hardware.org/?probe=21b167db8c) | Apr 25, 2021 |
| HP            | Laptop 15-da0xxx            | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Gateway       | Blade-K8F                   | [13e1a6028e](https://linux-hardware.org/?probe=13e1a6028e) | Apr 24, 2021 |
| Dell          | Inspiron N4020              | [9002772847](https://linux-hardware.org/?probe=9002772847) | Apr 21, 2021 |
| Intel Clie... | LAPQC71B                    | [272956b140](https://linux-hardware.org/?probe=272956b140) | Apr 20, 2021 |
| Acer          | Aspire V5-123               | [448b0afd35](https://linux-hardware.org/?probe=448b0afd35) | Apr 20, 2021 |
| Lenovo        | Z50-70 20354                | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Apple         | MacBook2,1                  | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [6a22991dbe](https://linux-hardware.org/?probe=6a22991dbe) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Dell          | Inspiron 15-3567            | [0a367170ed](https://linux-hardware.org/?probe=0a367170ed) | Apr 17, 2021 |
| HP            | Laptop 15-da0xxx            | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Toshiba       | Satellite L35               | [1abffa2c4c](https://linux-hardware.org/?probe=1abffa2c4c) | Apr 16, 2021 |
| LG Electro... | S425-L.BC22P1               | [64a50f7bb8](https://linux-hardware.org/?probe=64a50f7bb8) | Apr 15, 2021 |
| Dell          | Inspiron N4020              | [e0086be941](https://linux-hardware.org/?probe=e0086be941) | Apr 15, 2021 |
| HP            | Compaq 6820s                | [551053e9d6](https://linux-hardware.org/?probe=551053e9d6) | Apr 15, 2021 |
| Lenovo        | G460 20041                  | [e2dea3ec01](https://linux-hardware.org/?probe=e2dea3ec01) | Apr 14, 2021 |
| Dell          | Studio 1555                 | [c161e182c2](https://linux-hardware.org/?probe=c161e182c2) | Apr 14, 2021 |
| Toshiba       | Satellite L450              | [2c5ef0687b](https://linux-hardware.org/?probe=2c5ef0687b) | Apr 13, 2021 |
| HP            | EliteBook 8440p (VV954AV... | [3e0b56daf3](https://linux-hardware.org/?probe=3e0b56daf3) | Apr 12, 2021 |
| ASHI          | Unknown                     | [68a2b34c2f](https://linux-hardware.org/?probe=68a2b34c2f) | Apr 12, 2021 |
| HP            | ProBook 6560b               | [8c2a2cfdef](https://linux-hardware.org/?probe=8c2a2cfdef) | Apr 12, 2021 |
| Toshiba       | Satellite L40               | [0f6ed90100](https://linux-hardware.org/?probe=0f6ed90100) | Apr 11, 2021 |
| HP            | Laptop 15s-eq1xxx           | [530be6ce7b](https://linux-hardware.org/?probe=530be6ce7b) | Apr 08, 2021 |
| Acer          | Aspire 5715Z                | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| GTZS          | Unknown                     | [5600074bc0](https://linux-hardware.org/?probe=5600074bc0) | Apr 07, 2021 |
| Samsung       | R520/R522/R620              | [a7f2749d3b](https://linux-hardware.org/?probe=a7f2749d3b) | Apr 06, 2021 |
| Toshiba       | Satellite C70D-B            | [f3e45414fa](https://linux-hardware.org/?probe=f3e45414fa) | Apr 04, 2021 |
| Toshiba       | Satellite C70D-B            | [eacca5eceb](https://linux-hardware.org/?probe=eacca5eceb) | Apr 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [db0eb79b4e](https://linux-hardware.org/?probe=db0eb79b4e) | Mar 31, 2021 |
| ASUSTek       | 1005PE                      | [d75411e5b3](https://linux-hardware.org/?probe=d75411e5b3) | Mar 30, 2021 |
| Lenovo        | IdeaPad Z580                | [6224897fde](https://linux-hardware.org/?probe=6224897fde) | Mar 29, 2021 |
| Toshiba       | Satellite L70-B             | [4f1445876a](https://linux-hardware.org/?probe=4f1445876a) | Mar 27, 2021 |
| Toshiba       | Satellite A200              | [b477c99ab7](https://linux-hardware.org/?probe=b477c99ab7) | Mar 27, 2021 |
| Dell          | Vostro 5470                 | [c9dfbce9bd](https://linux-hardware.org/?probe=c9dfbce9bd) | Mar 26, 2021 |
| ASUSTek       | K45VD                       | [74592068ee](https://linux-hardware.org/?probe=74592068ee) | Mar 25, 2021 |
| Dell          | Latitude D810               | [ca3886900f](https://linux-hardware.org/?probe=ca3886900f) | Mar 25, 2021 |
| Toshiba       | Satellite L70-B             | [961ef41a18](https://linux-hardware.org/?probe=961ef41a18) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | [82480a0f24](https://linux-hardware.org/?probe=82480a0f24) | Mar 21, 2021 |
| Lenovo        | S10-3                       | [42884278c4](https://linux-hardware.org/?probe=42884278c4) | Mar 19, 2021 |
| Dell          | System XPS 15Z              | [cb1bcbb365](https://linux-hardware.org/?probe=cb1bcbb365) | Mar 18, 2021 |
| Acer          | Aspire A315-57G             | [4235b59b38](https://linux-hardware.org/?probe=4235b59b38) | Mar 17, 2021 |
| Acer          | Aspire A315-57G             | [4b3b196273](https://linux-hardware.org/?probe=4b3b196273) | Mar 17, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| HP            | EliteBook 8460p             | [821bcfc074](https://linux-hardware.org/?probe=821bcfc074) | Mar 09, 2021 |
| HP            | EliteBook 8460p             | [47a0bdcb00](https://linux-hardware.org/?probe=47a0bdcb00) | Mar 08, 2021 |
| ASUSTek       | P53E                        | [3aacf8a497](https://linux-hardware.org/?probe=3aacf8a497) | Mar 07, 2021 |
| IBM           | 2647KNG                     | [65d3c4c3c2](https://linux-hardware.org/?probe=65d3c4c3c2) | Mar 07, 2021 |
| IBM           | 2647KNG                     | [e4d4761cfe](https://linux-hardware.org/?probe=e4d4761cfe) | Mar 07, 2021 |
| Dell          | Vostro 3700                 | [0b9b8232f9](https://linux-hardware.org/?probe=0b9b8232f9) | Mar 05, 2021 |
| Dell          | Inspiron N5010              | [8273ed53f3](https://linux-hardware.org/?probe=8273ed53f3) | Mar 04, 2021 |
| HP            | Compaq Presario CQ60        | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| Dell          | Inspiron 1012               | [e66eef020e](https://linux-hardware.org/?probe=e66eef020e) | Mar 03, 2021 |
| Toshiba       | Satellite A135              | [05bbae8a9c](https://linux-hardware.org/?probe=05bbae8a9c) | Mar 02, 2021 |
| MSI           | MS-1453                     | [2be581dfbb](https://linux-hardware.org/?probe=2be581dfbb) | Mar 02, 2021 |
| MSI           | MS-1453                     | [bfaf417259](https://linux-hardware.org/?probe=bfaf417259) | Mar 02, 2021 |
| Toshiba       | Satellite A135              | [1986fa7acf](https://linux-hardware.org/?probe=1986fa7acf) | Mar 02, 2021 |
| Toshiba       | Satellite A660              | [70166b0f32](https://linux-hardware.org/?probe=70166b0f32) | Mar 01, 2021 |
| Lenovo        | S10-3                       | [6d4f0001a3](https://linux-hardware.org/?probe=6d4f0001a3) | Mar 01, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Acer          | Aspire 5610                 | [1cac0acc28](https://linux-hardware.org/?probe=1cac0acc28) | Feb 25, 2021 |
| Itautec       | Infoway w7430               | [72a0d46cbd](https://linux-hardware.org/?probe=72a0d46cbd) | Feb 25, 2021 |
| Timi          | TM1612                      | [517a0ea812](https://linux-hardware.org/?probe=517a0ea812) | Feb 23, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [c8fa1fd6d2](https://linux-hardware.org/?probe=c8fa1fd6d2) | Feb 23, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [bda750c182](https://linux-hardware.org/?probe=bda750c182) | Feb 23, 2021 |
| Dell          | Vostro 3700                 | [1063468eed](https://linux-hardware.org/?probe=1063468eed) | Feb 21, 2021 |
| Dell          | Vostro 3700                 | [234fac5997](https://linux-hardware.org/?probe=234fac5997) | Feb 21, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | [e79cbcdc53](https://linux-hardware.org/?probe=e79cbcdc53) | Feb 20, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | [eaeef8bb7b](https://linux-hardware.org/?probe=eaeef8bb7b) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| Dell          | Inspiron 1525               | [eeabc1752d](https://linux-hardware.org/?probe=eeabc1752d) | Feb 15, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [95b0ea2335](https://linux-hardware.org/?probe=95b0ea2335) | Feb 15, 2021 |
| HP            | Spectre Laptop 13-af0xx     | [e40f1f67bd](https://linux-hardware.org/?probe=e40f1f67bd) | Feb 15, 2021 |
| Dell          | Inspiron 15-3565            | [7c39aa2965](https://linux-hardware.org/?probe=7c39aa2965) | Feb 14, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [0f15feb522](https://linux-hardware.org/?probe=0f15feb522) | Feb 13, 2021 |
| HP            | ProBook 440 G6              | [715d525514](https://linux-hardware.org/?probe=715d525514) | Feb 07, 2021 |
| HP            | ProBook 440 G7              | [4fd36e0cb3](https://linux-hardware.org/?probe=4fd36e0cb3) | Feb 07, 2021 |
| Unknown       | Unknown                     | [bcad30556a](https://linux-hardware.org/?probe=bcad30556a) | Feb 07, 2021 |
| HP            | ProBook 440 G6              | [f943690f6e](https://linux-hardware.org/?probe=f943690f6e) | Feb 07, 2021 |
| HP            | Pavilion g7                 | [5151e90c72](https://linux-hardware.org/?probe=5151e90c72) | Feb 06, 2021 |
| HP            | G42                         | [b9fbeca924](https://linux-hardware.org/?probe=b9fbeca924) | Feb 05, 2021 |
| HP            | Compaq 6715b (GP690US#AB... | [e77dbfe4a6](https://linux-hardware.org/?probe=e77dbfe4a6) | Feb 05, 2021 |
| ASUSTek       | GL553VD                     | [51102bc7a6](https://linux-hardware.org/?probe=51102bc7a6) | Feb 04, 2021 |
| HP            | Pavilion dv6000 (RP154UA... | [44347b7399](https://linux-hardware.org/?probe=44347b7399) | Jan 31, 2021 |
| Lenovo        | ThinkPad L460 20FVS20700    | [e456ebd9cc](https://linux-hardware.org/?probe=e456ebd9cc) | Jan 29, 2021 |
| HP            | Notebook                    | [c83f3fcce6](https://linux-hardware.org/?probe=c83f3fcce6) | Jan 27, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [c654b7b4ad](https://linux-hardware.org/?probe=c654b7b4ad) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [20f7e526b4](https://linux-hardware.org/?probe=20f7e526b4) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| Samsung       | RV415/RV515                 | [8cf59ea427](https://linux-hardware.org/?probe=8cf59ea427) | Jan 23, 2021 |
| Apple         | MacBookPro10,2              | [19b2ebc706](https://linux-hardware.org/?probe=19b2ebc706) | Jan 22, 2021 |
| Dell          | Latitude 3440               | [ba52d4afcf](https://linux-hardware.org/?probe=ba52d4afcf) | Jan 22, 2021 |
| ASUSTek       | K53SD                       | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| HP            | ProBook 6360b               | [3e3cda2a19](https://linux-hardware.org/?probe=3e3cda2a19) | Jan 19, 2021 |
| Lenovo        | IdeaPad Y550 4186           | [d6ae69ca34](https://linux-hardware.org/?probe=d6ae69ca34) | Jan 17, 2021 |
| Toshiba       | Satellite A205              | [57f9413b16](https://linux-hardware.org/?probe=57f9413b16) | Jan 16, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| HP            | Pavilion g6                 | [23360e9a39](https://linux-hardware.org/?probe=23360e9a39) | Jan 12, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | [1f7fadda6e](https://linux-hardware.org/?probe=1f7fadda6e) | Jan 10, 2021 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [3aca8223d6](https://linux-hardware.org/?probe=3aca8223d6) | Jan 09, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [9764fca96a](https://linux-hardware.org/?probe=9764fca96a) | Jan 08, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [01626f040a](https://linux-hardware.org/?probe=01626f040a) | Jan 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [1bf71bd97d](https://linux-hardware.org/?probe=1bf71bd97d) | Jan 04, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [266231dab8](https://linux-hardware.org/?probe=266231dab8) | Jan 04, 2021 |
| Sony          | VPCYB35AL                   | [f82ea2b0dc](https://linux-hardware.org/?probe=f82ea2b0dc) | Jan 03, 2021 |
| Lenovo        | G50-45 80E3                 | [65ed0bcd53](https://linux-hardware.org/?probe=65ed0bcd53) | Jan 02, 2021 |
| Positivo      | S14CT01                     | [2b0f53fc1a](https://linux-hardware.org/?probe=2b0f53fc1a) | Jan 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [c11d9786f7](https://linux-hardware.org/?probe=c11d9786f7) | Dec 29, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [752fb8d0c7](https://linux-hardware.org/?probe=752fb8d0c7) | Dec 25, 2020 |
| Sony          | VPCYB35AL                   | [490e3a1b0a](https://linux-hardware.org/?probe=490e3a1b0a) | Dec 23, 2020 |
| Fujitsu       | FMVNFA50                    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| HP            | Pavilion TS 15              | [aea4de88ed](https://linux-hardware.org/?probe=aea4de88ed) | Dec 22, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0RK1... | [0377183ebd](https://linux-hardware.org/?probe=0377183ebd) | Dec 20, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0RK1... | [17467ac4ff](https://linux-hardware.org/?probe=17467ac4ff) | Dec 20, 2020 |
| Toshiba       | Satellite C55D-A            | [f29fb73181](https://linux-hardware.org/?probe=f29fb73181) | Dec 20, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8402e6dc04](https://linux-hardware.org/?probe=8402e6dc04) | Dec 18, 2020 |
| Acer          | Aspire 4720Z                | [88bd8075b2](https://linux-hardware.org/?probe=88bd8075b2) | Dec 16, 2020 |
| Acer          | Aspire 4720Z                | [93cfeab463](https://linux-hardware.org/?probe=93cfeab463) | Dec 16, 2020 |
| Sony          | VGN-S5XP_B                  | [50c6c9d78a](https://linux-hardware.org/?probe=50c6c9d78a) | Dec 15, 2020 |
| ASUSTek       | GL553VD                     | [8cf11c15f8](https://linux-hardware.org/?probe=8cf11c15f8) | Dec 13, 2020 |
| ASUSTek       | K53SD                       | [96067d7a81](https://linux-hardware.org/?probe=96067d7a81) | Dec 13, 2020 |
| Toshiba       | NB510                       | [41d6c29f97](https://linux-hardware.org/?probe=41d6c29f97) | Dec 13, 2020 |
| Gateway       | NE56R                       | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| Acer          | Aspire 5735                 | [8e251a6942](https://linux-hardware.org/?probe=8e251a6942) | Dec 10, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WP0... | [6ee5c7543b](https://linux-hardware.org/?probe=6ee5c7543b) | Dec 10, 2020 |
| ASUSTek       | X58L                        | [a7fd194aaa](https://linux-hardware.org/?probe=a7fd194aaa) | Dec 07, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | [80ecb8f763](https://linux-hardware.org/?probe=80ecb8f763) | Dec 06, 2020 |
| Lenovo        | IdeaPad Z580                | [f31b40572a](https://linux-hardware.org/?probe=f31b40572a) | Dec 02, 2020 |
| Gigabyte      | W466U                       | [527d2ea4da](https://linux-hardware.org/?probe=527d2ea4da) | Nov 30, 2020 |
| Panasonic     | CF-52PGNBE2M                | [e6e31de556](https://linux-hardware.org/?probe=e6e31de556) | Nov 28, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | [503449ba47](https://linux-hardware.org/?probe=503449ba47) | Nov 27, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | [f45a6362f7](https://linux-hardware.org/?probe=f45a6362f7) | Nov 27, 2020 |
| HP            | Presario F700 (KA698EA#A... | [19fd9647b4](https://linux-hardware.org/?probe=19fd9647b4) | Nov 23, 2020 |
| HP            | Presario F700 (KA698EA#A... | [b46ffd3c2e](https://linux-hardware.org/?probe=b46ffd3c2e) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| LG Electro... | C400-G.BG21P1               | [033a9d8cd0](https://linux-hardware.org/?probe=033a9d8cd0) | Nov 19, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [bb11d08947](https://linux-hardware.org/?probe=bb11d08947) | Nov 19, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [4f73e063d1](https://linux-hardware.org/?probe=4f73e063d1) | Nov 19, 2020 |
| HP            | Pavilion TS 11              | [a71dfc4983](https://linux-hardware.org/?probe=a71dfc4983) | Nov 19, 2020 |
| HP            | ProBook 455 G7              | [86e6b8d3b3](https://linux-hardware.org/?probe=86e6b8d3b3) | Nov 18, 2020 |
| Positivo      | S14BW01                     | [13fed8ca27](https://linux-hardware.org/?probe=13fed8ca27) | Nov 17, 2020 |
| HP            | EliteBook 2570p             | [3d005c24b6](https://linux-hardware.org/?probe=3d005c24b6) | Nov 17, 2020 |
| Gateway       | NE56R                       | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| HP            | ProBook 4720s               | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| Dell          | Inspiron 5423               | [3bd134ed30](https://linux-hardware.org/?probe=3bd134ed30) | Nov 11, 2020 |
| Unknown       | Unknown                     | [5ecd7c84ac](https://linux-hardware.org/?probe=5ecd7c84ac) | Nov 09, 2020 |
| Unknown       | Unknown                     | [abc04e2dfd](https://linux-hardware.org/?probe=abc04e2dfd) | Nov 09, 2020 |
| HP            | Unknown                     | [1cee50e485](https://linux-hardware.org/?probe=1cee50e485) | Nov 07, 2020 |
| Sony          | VGN-S5XP_B                  | [62453951ca](https://linux-hardware.org/?probe=62453951ca) | Nov 06, 2020 |
| Apple         | MacBookPro10,2              | [20951f6ce6](https://linux-hardware.org/?probe=20951f6ce6) | Nov 05, 2020 |
| Samsung       | SX11S                       | [7946db3be4](https://linux-hardware.org/?probe=7946db3be4) | Nov 05, 2020 |
| Samsung       | R530/R730/P530              | [f83b2806d0](https://linux-hardware.org/?probe=f83b2806d0) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| HP            | 650                         | [d1e41ec5c0](https://linux-hardware.org/?probe=d1e41ec5c0) | Nov 03, 2020 |
| Acer          | AOD257                      | [a45ddcc3ab](https://linux-hardware.org/?probe=a45ddcc3ab) | Nov 03, 2020 |
| Acer          | AOD257                      | [3daaf2fdad](https://linux-hardware.org/?probe=3daaf2fdad) | Nov 02, 2020 |
| Samsung       | RV408/RV508                 | [208f929309](https://linux-hardware.org/?probe=208f929309) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| ASUSTek       | E200HA                      | [7fd48df4aa](https://linux-hardware.org/?probe=7fd48df4aa) | Oct 31, 2020 |
| Lenovo        | 100-14IBY 80R7              | [48cb3a624d](https://linux-hardware.org/?probe=48cb3a624d) | Oct 31, 2020 |
| Fujitsu Si... | AMILO Li 2727               | [3e90cc2ba4](https://linux-hardware.org/?probe=3e90cc2ba4) | Oct 31, 2020 |
| Samsung       | N150P/N210P/N220P           | [986ac8d550](https://linux-hardware.org/?probe=986ac8d550) | Oct 30, 2020 |
| Toshiba       | Satellite L305              | [c2a545a417](https://linux-hardware.org/?probe=c2a545a417) | Oct 30, 2020 |
| Dell          | Inspiron 5759               | [a9f65003ad](https://linux-hardware.org/?probe=a9f65003ad) | Oct 29, 2020 |
| Samsung       | R530/R730/P530              | [855274d6b0](https://linux-hardware.org/?probe=855274d6b0) | Oct 29, 2020 |
| Notebook      | W740SU                      | [cd23f8c64d](https://linux-hardware.org/?probe=cd23f8c64d) | Oct 28, 2020 |
| Alienware     | 13 R3                       | [c0fc10a320](https://linux-hardware.org/?probe=c0fc10a320) | Oct 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS8CH0... | [bd938bf5fd](https://linux-hardware.org/?probe=bd938bf5fd) | Oct 28, 2020 |
| Positivo      | H14BT58                     | [84c73b4beb](https://linux-hardware.org/?probe=84c73b4beb) | Oct 27, 2020 |
| Itautec       | Infoway                     | [b67c3f6870](https://linux-hardware.org/?probe=b67c3f6870) | Oct 27, 2020 |
| MSI           | U180                        | [7b3f357ff5](https://linux-hardware.org/?probe=7b3f357ff5) | Oct 26, 2020 |
| Toshiba       | Satellite L30               | [0504cfe362](https://linux-hardware.org/?probe=0504cfe362) | Oct 26, 2020 |
| Lenovo        | G575 4383                   | [43b5c51358](https://linux-hardware.org/?probe=43b5c51358) | Oct 25, 2020 |
| Acer          | Aspire F5-573               | [60b785b9cf](https://linux-hardware.org/?probe=60b785b9cf) | Oct 25, 2020 |
| Acer          | Extensa 4620                | [62e829d249](https://linux-hardware.org/?probe=62e829d249) | Oct 22, 2020 |
| Notebook      | W54_55SU1,SUW               | [9655c9ef29](https://linux-hardware.org/?probe=9655c9ef29) | Oct 21, 2020 |
| HP            | Presario V5000 (RE317EA#... | [87b9f12d09](https://linux-hardware.org/?probe=87b9f12d09) | Oct 19, 2020 |
| HP            | Presario V5000 (RE317EA#... | [e09f71e34f](https://linux-hardware.org/?probe=e09f71e34f) | Oct 19, 2020 |
| Acer          | Aspire E1-532P              | [95778c93aa](https://linux-hardware.org/?probe=95778c93aa) | Oct 18, 2020 |
| HP            | Pavilion zd8000 (EL017EA... | [944d295a6b](https://linux-hardware.org/?probe=944d295a6b) | Oct 16, 2020 |
| Toshiba       | Satellite L840              | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| Acer          | Extensa 4620                | [dd858548d7](https://linux-hardware.org/?probe=dd858548d7) | Oct 15, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | [a422be5fc0](https://linux-hardware.org/?probe=a422be5fc0) | Oct 15, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | [1717667731](https://linux-hardware.org/?probe=1717667731) | Oct 13, 2020 |
| LG Electro... | C400-G.BG21P1               | [feb6bd4cac](https://linux-hardware.org/?probe=feb6bd4cac) | Oct 13, 2020 |
| LAMINA        | T-1012B NORD                | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| Google        | Wolf                        | [0ebdfebf96](https://linux-hardware.org/?probe=0ebdfebf96) | Oct 10, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | [03d64c9c3d](https://linux-hardware.org/?probe=03d64c9c3d) | Oct 10, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | [5171d8bc33](https://linux-hardware.org/?probe=5171d8bc33) | Oct 08, 2020 |
| HP            | Pavilion dv6                | [0d0a5ac639](https://linux-hardware.org/?probe=0d0a5ac639) | Oct 07, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | [5e75a35a7d](https://linux-hardware.org/?probe=5e75a35a7d) | Oct 07, 2020 |
| HP            | Unknown                     | [6ff5164672](https://linux-hardware.org/?probe=6ff5164672) | Oct 07, 2020 |
| HP            | Unknown                     | [3815163813](https://linux-hardware.org/?probe=3815163813) | Oct 06, 2020 |
| Dell          | Latitude D630               | [df80a0678a](https://linux-hardware.org/?probe=df80a0678a) | Oct 04, 2020 |
| HP            | Laptop 15-da2xxx            | [a071c6ca32](https://linux-hardware.org/?probe=a071c6ca32) | Sep 30, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | [adb08b74c2](https://linux-hardware.org/?probe=adb08b74c2) | Sep 28, 2020 |
| Panasonic     | CF-31JAGAX1M                | [50fe0189f0](https://linux-hardware.org/?probe=50fe0189f0) | Sep 27, 2020 |
| ASUSTek       | X202EP                      | [7003257b9c](https://linux-hardware.org/?probe=7003257b9c) | Sep 26, 2020 |
| Dell          | Inspiron 1440               | [863493a36c](https://linux-hardware.org/?probe=863493a36c) | Sep 25, 2020 |
| Fujitsu       | LIFEBOOK P702               | [4f2bb45d77](https://linux-hardware.org/?probe=4f2bb45d77) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57e9fe3f34](https://linux-hardware.org/?probe=57e9fe3f34) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [2c253a5689](https://linux-hardware.org/?probe=2c253a5689) | Sep 23, 2020 |
| Samsung       | N230                        | [d4ba29fa0c](https://linux-hardware.org/?probe=d4ba29fa0c) | Sep 23, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [d62d875657](https://linux-hardware.org/?probe=d62d875657) | Sep 22, 2020 |
| Samsung       | N230                        | [786e9275d0](https://linux-hardware.org/?probe=786e9275d0) | Sep 22, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [cb4d6ae384](https://linux-hardware.org/?probe=cb4d6ae384) | Sep 22, 2020 |
| Apple         | MacBook3,1                  | [900daa65d7](https://linux-hardware.org/?probe=900daa65d7) | Sep 20, 2020 |
| Fujitsu       | FMVA05008                   | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| Lenovo        | 3000 N200 0769ALU           | [16fb38706f](https://linux-hardware.org/?probe=16fb38706f) | Sep 17, 2020 |
| ASUSTek       | 1015PE                      | [9328bb0c6a](https://linux-hardware.org/?probe=9328bb0c6a) | Sep 16, 2020 |
| ASUSTek       | X202EP                      | [7331377f2b](https://linux-hardware.org/?probe=7331377f2b) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [bb9ff1e41f](https://linux-hardware.org/?probe=bb9ff1e41f) | Sep 15, 2020 |
| Sony          | VPCEG25EN                   | [10bd76f50c](https://linux-hardware.org/?probe=10bd76f50c) | Sep 14, 2020 |
| Acer          | Prespa M                    | [4310240814](https://linux-hardware.org/?probe=4310240814) | Sep 13, 2020 |
| Acer          | Prespa M                    | [dc7c7827ea](https://linux-hardware.org/?probe=dc7c7827ea) | Sep 13, 2020 |
| ASUSTek       | F7L                         | [0190224dc8](https://linux-hardware.org/?probe=0190224dc8) | Sep 12, 2020 |
| Dell          | MXG071                      | [5fc63c5480](https://linux-hardware.org/?probe=5fc63c5480) | Sep 12, 2020 |
| Apple         | MacBookPro10,2              | [3bc9d8ad1e](https://linux-hardware.org/?probe=3bc9d8ad1e) | Sep 10, 2020 |
| ASUSTek       | P553UA                      | [fca37591fc](https://linux-hardware.org/?probe=fca37591fc) | Sep 10, 2020 |
| Samsung       | SX11S                       | [de5f3f5244](https://linux-hardware.org/?probe=de5f3f5244) | Sep 10, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Lubuntu/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lubuntu 20.04   | 273       | 30.47%  |
| Lubuntu 22.04   | 234       | 26.12%  |
| Lubuntu 18.04   | 131       | 14.62%  |
| Lubuntu 21.10   | 47        | 5.25%   |
| Lubuntu 19.10   | 43        | 4.8%    |
| Lubuntu 21.04   | 37        | 4.13%   |
| Lubuntu 22.10   | 30        | 3.35%   |
| Lubuntu 20.10   | 30        | 3.35%   |
| Lubuntu 23.04   | 19        | 2.12%   |
| Lubuntu 16.04   | 15        | 1.67%   |
| Lubuntu 19.04   | 12        | 1.34%   |
| Lubuntu 23.10   | 10        | 1.12%   |
| Lubuntu 18.10   | 8         | 0.89%   |
| Lubuntu         | 3         | 0.33%   |
| Lubuntu 20.04.1 | 1         | 0.11%   |
| Lubuntu 17.10   | 1         | 0.11%   |
| Lubuntu 13.04   | 1         | 0.11%   |
| Lubuntu 12.04   | 1         | 0.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Lubuntu | 862       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.4.0-42-generic   | 24        | 2.42%   |
| 5.15.0-43-generic  | 23        | 2.32%   |
| 5.15.0-56-generic  | 16        | 1.62%   |
| 5.4.0-52-generic   | 15        | 1.52%   |
| 5.15.0-25-generic  | 12        | 1.21%   |
| 5.3.0-46-generic   | 11        | 1.11%   |
| 5.15.0-46-generic  | 11        | 1.11%   |
| 5.13.0-28-generic  | 11        | 1.11%   |
| 5.13.0-19-generic  | 11        | 1.11%   |
| 5.11.0-16-generic  | 11        | 1.11%   |
| 5.19.0-41-generic  | 10        | 1.01%   |
| 5.13.0-40-generic  | 10        | 1.01%   |
| 6.2.0-34-generic   | 9         | 0.91%   |
| 5.4.0-48-generic   | 9         | 0.91%   |
| 5.4.0-47-generic   | 9         | 0.91%   |
| 5.4.0-26-generic   | 9         | 0.91%   |
| 5.15.0-58-generic  | 9         | 0.91%   |
| 5.15.0-41-generic  | 9         | 0.91%   |
| 5.13.0-35-generic  | 9         | 0.91%   |
| 5.13.0-30-generic  | 9         | 0.91%   |
| 6.2.0-26-generic   | 8         | 0.81%   |
| 5.4.0-65-generic   | 8         | 0.81%   |
| 5.3.0-18-generic   | 8         | 0.81%   |
| 5.15.0-60-generic  | 8         | 0.81%   |
| 5.15.0-30-generic  | 8         | 0.81%   |
| 5.11.0-25-generic  | 8         | 0.81%   |
| 4.15.0-112-generic | 8         | 0.81%   |
| 6.2.0-20-generic   | 7         | 0.71%   |
| 5.4.0-73-generic   | 7         | 0.71%   |
| 5.4.0-54-generic   | 7         | 0.71%   |
| 5.4.0-40-generic   | 7         | 0.71%   |
| 5.19.0-35-generic  | 7         | 0.71%   |
| 5.19.0-32-generic  | 7         | 0.71%   |
| 5.19.0-26-generic  | 7         | 0.71%   |
| 5.15.0-52-generic  | 7         | 0.71%   |
| 5.15.0-47-generic  | 7         | 0.71%   |
| 5.11.0-38-generic  | 7         | 0.71%   |
| 4.15.0-91-generic  | 7         | 0.71%   |
| 5.8.0-63-generic   | 6         | 0.61%   |
| 5.4.0-72-generic   | 6         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.4.0    | 207       | 22.8%   |
| 5.15.0   | 172       | 18.94%  |
| 4.15.0   | 80        | 8.81%   |
| 5.19.0   | 73        | 8.04%   |
| 5.13.0   | 72        | 7.93%   |
| 5.11.0   | 67        | 7.38%   |
| 5.3.0    | 63        | 6.94%   |
| 5.8.0    | 57        | 6.28%   |
| 6.2.0    | 56        | 6.17%   |
| 5.0.0    | 16        | 1.76%   |
| 6.5.0    | 10        | 1.1%    |
| 4.18.0   | 9         | 0.99%   |
| 4.4.0    | 4         | 0.44%   |
| 4.13.0   | 2         | 0.22%   |
| 6.5.1    | 1         | 0.11%   |
| 6.4.12   | 1         | 0.11%   |
| 6.1.6    | 1         | 0.11%   |
| 6.1.12   | 1         | 0.11%   |
| 6.0.12   | 1         | 0.11%   |
| 6.0.0    | 1         | 0.11%   |
| 5.9.0    | 1         | 0.11%   |
| 5.7.9    | 1         | 0.11%   |
| 5.6.0    | 1         | 0.11%   |
| 5.5.2    | 1         | 0.11%   |
| 5.19.8   | 1         | 0.11%   |
| 5.18.0   | 1         | 0.11%   |
| 5.16.0   | 1         | 0.11%   |
| 5.14.0   | 1         | 0.11%   |
| 5.10.0   | 1         | 0.11%   |
| 4.14.225 | 1         | 0.11%   |
| 4.13.9   | 1         | 0.11%   |
| 4.10.0   | 1         | 0.11%   |
| 3.13.0   | 1         | 0.11%   |
| 3.1.10   | 1         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 207       | 22.8%   |
| 5.15    | 172       | 18.94%  |
| 4.15    | 80        | 8.81%   |
| 5.19    | 74        | 8.15%   |
| 5.13    | 72        | 7.93%   |
| 5.11    | 67        | 7.38%   |
| 5.3     | 63        | 6.94%   |
| 5.8     | 57        | 6.28%   |
| 6.2     | 56        | 6.17%   |
| 5.0     | 16        | 1.76%   |
| 6.5     | 11        | 1.21%   |
| 4.18    | 9         | 0.99%   |
| 4.4     | 4         | 0.44%   |
| 4.13    | 3         | 0.33%   |
| 6.1     | 2         | 0.22%   |
| 6.0     | 2         | 0.22%   |
| 6.4     | 1         | 0.11%   |
| 5.9     | 1         | 0.11%   |
| 5.7     | 1         | 0.11%   |
| 5.6     | 1         | 0.11%   |
| 5.5     | 1         | 0.11%   |
| 5.18    | 1         | 0.11%   |
| 5.16    | 1         | 0.11%   |
| 5.14    | 1         | 0.11%   |
| 5.10    | 1         | 0.11%   |
| 4.14    | 1         | 0.11%   |
| 4.10    | 1         | 0.11%   |
| 3.13    | 1         | 0.11%   |
| 3.1     | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 776       | 90.02%  |
| i686   | 85        | 9.86%   |
| armv7l | 1         | 0.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| LXQt            | 686       | 79.31%  |
| LXDE            | 138       | 15.95%  |
| Unknown         | 15        | 1.73%   |
| GNOME           | 6         | 0.69%   |
| Openbox         | 5         | 0.58%   |
| X-Cinnamon      | 3         | 0.35%   |
| KDE5            | 3         | 0.35%   |
| Lubuntu         | 2         | 0.23%   |
| Cinnamon        | 2         | 0.23%   |
| MATE            | 1         | 0.12%   |
| KDE             | 1         | 0.12%   |
| i3              | 1         | 0.12%   |
| GNOME Flashback | 1         | 0.12%   |
| Budgie          | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 841       | 97.34%  |
| Tty     | 18        | 2.08%   |
| Wayland | 5         | 0.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 476       | 54.34%  |
| Unknown | 251       | 28.65%  |
| LightDM | 75        | 8.56%   |
| TDM     | 43        | 4.91%   |
| GDM     | 22        | 2.51%   |
| GDM3    | 8         | 0.91%   |
| XDM     | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 254       | 29.3%   |
| fr_FR   | 76        | 8.77%   |
| pt_BR   | 63        | 7.27%   |
| it_IT   | 57        | 6.57%   |
| en_GB   | 57        | 6.57%   |
| de_DE   | 41        | 4.73%   |
| C       | 36        | 4.15%   |
| ru_RU   | 32        | 3.69%   |
| pl_PL   | 26        | 3%      |
| es_ES   | 18        | 2.08%   |
| Unknown | 18        | 2.08%   |
| en_CA   | 15        | 1.73%   |
| en_AU   | 14        | 1.61%   |
| es_AR   | 10        | 1.15%   |
| tr_TR   | 9         | 1.04%   |
| es_MX   | 9         | 1.04%   |
| en_IN   | 9         | 1.04%   |
| en_AG   | 9         | 1.04%   |
| hu_HU   | 8         | 0.92%   |
| cs_CZ   | 8         | 0.92%   |
| nl_NL   | 6         | 0.69%   |
| nl_BE   | 5         | 0.58%   |
| es_CR   | 5         | 0.58%   |
| es_CO   | 5         | 0.58%   |
| es_CL   | 5         | 0.58%   |
| en_IE   | 5         | 0.58%   |
| ja_JP   | 4         | 0.46%   |
| fr_BE   | 4         | 0.46%   |
| en_PH   | 4         | 0.46%   |
| fr_CH   | 3         | 0.35%   |
| es_VE   | 3         | 0.35%   |
| el_GR   | 3         | 0.35%   |
| zh_TW   | 2         | 0.23%   |
| sk_SK   | 2         | 0.23%   |
| id_ID   | 2         | 0.23%   |
| fr_CA   | 2         | 0.23%   |
| fi_FI   | 2         | 0.23%   |
| es_UY   | 2         | 0.23%   |
| es_PE   | 2         | 0.23%   |
| en_ZA   | 2         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 540       | 61.86%  |
| EFI  | 333       | 38.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 774       | 88.97%  |
| Overlay | 39        | 4.48%   |
| Tmpfs   | 33        | 3.79%   |
| Btrfs   | 10        | 1.15%   |
| Aufs    | 5         | 0.57%   |
| Xfs     | 3         | 0.34%   |
| Unknown | 3         | 0.34%   |
| Ext3    | 2         | 0.23%   |
| Ext2    | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 328       | 37.61%  |
| Unknown | 325       | 37.27%  |
| MBR     | 219       | 25.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 790       | 90.8%   |
| Yes       | 80        | 9.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 643       | 74.08%  |
| Yes       | 225       | 25.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 178       | 20.65%  |
| Lenovo              | 116       | 13.46%  |
| Dell                | 89        | 10.32%  |
| ASUSTek Computer    | 87        | 10.09%  |
| Acer                | 83        | 9.63%   |
| Toshiba             | 49        | 5.68%   |
| Samsung Electronics | 27        | 3.13%   |
| Google              | 26        | 3.02%   |
| Sony                | 20        | 2.32%   |
| Apple               | 19        | 2.2%    |
| Positivo            | 14        | 1.62%   |
| MSI                 | 12        | 1.39%   |
| Unknown             | 11        | 1.28%   |
| Fujitsu             | 10        | 1.16%   |
| Packard Bell        | 9         | 1.04%   |
| Mediacom            | 9         | 1.04%   |
| Fujitsu Siemens     | 7         | 0.81%   |
| Notebook            | 5         | 0.58%   |
| HUAWEI              | 4         | 0.46%   |
| Alienware           | 4         | 0.46%   |
| Thomson             | 3         | 0.35%   |
| Panasonic           | 3         | 0.35%   |
| Intel               | 3         | 0.35%   |
| Insyde              | 3         | 0.35%   |
| IBM                 | 3         | 0.35%   |
| GPU Company         | 3         | 0.35%   |
| Gateway             | 3         | 0.35%   |
| Dixonsxp            | 3         | 0.35%   |
| YASHI               | 2         | 0.23%   |
| TrekStor            | 2         | 0.23%   |
| Standard            | 2         | 0.23%   |
| SGIN                | 2         | 0.23%   |
| Prestigio           | 2         | 0.23%   |
| OEM                 | 2         | 0.23%   |
| LG Electronics      | 2         | 0.23%   |
| Itautec             | 2         | 0.23%   |
| Hampoo              | 2         | 0.23%   |
| Gigabyte Technology | 2         | 0.23%   |
| Getac               | 2         | 0.23%   |
| eMachines           | 2         | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 21        | 2.44%   |
| HP Notebook                           | 11        | 1.28%   |
| HP Pavilion 15                        | 6         | 0.7%    |
| Apple MacBookPro8,1                   | 6         | 0.7%    |
| HP Pavilion g6                        | 5         | 0.58%   |
| HP Pavilion dv6                       | 5         | 0.58%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 4         | 0.46%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS   | 4         | 0.46%   |
| Dell Latitude D630                    | 4         | 0.46%   |
| Mediacom WinPad 11,6 FullHD- WPU11    | 3         | 0.35%   |
| Lenovo IdeaPad 320-15AST 80XV         | 3         | 0.35%   |
| Lenovo IdeaPad 100-15IBD 80QQ         | 3         | 0.35%   |
| Lenovo G50-30 80G0                    | 3         | 0.35%   |
| HP ProBook 440 G7                     | 3         | 0.35%   |
| HP Pavilion g7                        | 3         | 0.35%   |
| HP Laptop 15-da0xxx                   | 3         | 0.35%   |
| HP 2000                               | 3         | 0.35%   |
| Google Candy                          | 3         | 0.35%   |
| Dell Inspiron N5010                   | 3         | 0.35%   |
| ASUS 1000H                            | 3         | 0.35%   |
| Apple MacBook4,1                      | 3         | 0.35%   |
| Acer Aspire 5742G                     | 3         | 0.35%   |
| Acer Aspire 5735                      | 3         | 0.35%   |
| YASHI MYBOOK 360                      | 2         | 0.23%   |
| Toshiba Satellite L40                 | 2         | 0.23%   |
| Toshiba Satellite L300                | 2         | 0.23%   |
| Toshiba Satellite A205                | 2         | 0.23%   |
| Samsung RV415/RV515                   | 2         | 0.23%   |
| Samsung 275E4E/275E5E                 | 2         | 0.23%   |
| Prestigio PSB141C01BFH                | 2         | 0.23%   |
| Positivo Mobile                       | 2         | 0.23%   |
| Positivo H14BT58                      | 2         | 0.23%   |
| Mediacom GTZS                         | 2         | 0.23%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 2         | 0.23%   |
| Lenovo IdeaPad 330-17AST 81D7         | 2         | 0.23%   |
| Lenovo G580 20150                     | 2         | 0.23%   |
| Lenovo G50-45 80E3                    | 2         | 0.23%   |
| Itautec Infoway                       | 2         | 0.23%   |
| HP ProBook 450 G6                     | 2         | 0.23%   |
| HP ProBook 450 G2                     | 2         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 60        | 6.96%   |
| Lenovo IdeaPad        | 46        | 5.34%   |
| Toshiba Satellite     | 44        | 5.1%    |
| Lenovo ThinkPad       | 43        | 4.99%   |
| HP Pavilion           | 41        | 4.76%   |
| Dell Inspiron         | 39        | 4.52%   |
| Dell Latitude         | 29        | 3.36%   |
| HP ProBook            | 28        | 3.25%   |
| HP EliteBook          | 21        | 2.44%   |
| Unknown               | 21        | 2.44%   |
| HP Compaq             | 19        | 2.2%    |
| HP Laptop             | 17        | 1.97%   |
| HP Notebook           | 11        | 1.28%   |
| ASUS VivoBook         | 10        | 1.16%   |
| Packard Bell EasyNote | 7         | 0.81%   |
| Fujitsu Siemens AMILO | 7         | 0.81%   |
| Fujitsu LIFEBOOK      | 7         | 0.81%   |
| Dell XPS              | 7         | 0.81%   |
| Apple MacBookPro8     | 6         | 0.7%    |
| Acer Extensa          | 6         | 0.7%    |
| HP Stream             | 5         | 0.58%   |
| HP Presario           | 5         | 0.58%   |
| Dell Vostro           | 5         | 0.58%   |
| Mediacom SmartBook    | 4         | 0.46%   |
| HP 255                | 4         | 0.46%   |
| Acer Swift            | 4         | 0.46%   |
| Mediacom WinPad       | 3         | 0.35%   |
| Lenovo G50-30         | 3         | 0.35%   |
| HP ZBook              | 3         | 0.35%   |
| HP 2000               | 3         | 0.35%   |
| Google Candy          | 3         | 0.35%   |
| Dell Studio           | 3         | 0.35%   |
| Dell Precision        | 3         | 0.35%   |
| ASUS 1000H            | 3         | 0.35%   |
| Apple MacBookPro10    | 3         | 0.35%   |
| Apple MacBook4        | 3         | 0.35%   |
| Acer TravelMate       | 3         | 0.35%   |
| YASHI MYBOOK          | 2         | 0.23%   |
| Toshiba TECRA         | 2         | 0.23%   |
| Samsung RV415         | 2         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 85        | 9.86%   |
| 2012    | 71        | 8.24%   |
| 2010    | 70        | 8.12%   |
| 2008    | 68        | 7.89%   |
| 2013    | 67        | 7.77%   |
| 2007    | 55        | 6.38%   |
| 2019    | 53        | 6.15%   |
| 2016    | 52        | 6.03%   |
| 2014    | 44        | 5.1%    |
| 2015    | 41        | 4.76%   |
| 2009    | 41        | 4.76%   |
| 2021    | 40        | 4.64%   |
| 2017    | 39        | 4.52%   |
| 2020    | 35        | 4.06%   |
| 2018    | 34        | 3.94%   |
| 2006    | 24        | 2.78%   |
| 2022    | 22        | 2.55%   |
| 2023    | 11        | 1.28%   |
| 2005    | 5         | 0.58%   |
| 2002    | 2         | 0.23%   |
| Unknown | 2         | 0.23%   |
| 2004    | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 862       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 808       | 93.09%  |
| Enabled  | 60        | 6.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 833       | 96.52%  |
| Yes  | 30        | 3.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 288       | 32.99%  |
| 4.01-8.0    | 200       | 22.91%  |
| 1.01-2.0    | 162       | 18.56%  |
| 8.01-16.0   | 81        | 9.28%   |
| 2.01-3.0    | 48        | 5.5%    |
| 16.01-24.0  | 47        | 5.38%   |
| 0.51-1.0    | 27        | 3.09%   |
| 32.01-64.0  | 14        | 1.6%    |
| 0.01-0.5    | 3         | 0.34%   |
| 24.01-32.0  | 2         | 0.23%   |
| 64.01-256.0 | 1         | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 413       | 44.65%  |
| 0.51-1.0   | 232       | 25.08%  |
| 2.01-3.0   | 130       | 14.05%  |
| 4.01-8.0   | 49        | 5.3%    |
| 3.01-4.0   | 48        | 5.19%   |
| 0.01-0.5   | 44        | 4.76%   |
| 8.01-16.0  | 6         | 0.65%   |
| Unknown    | 2         | 0.22%   |
| 16.01-24.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 661       | 75.98%  |
| 2      | 180       | 20.69%  |
| 0      | 15        | 1.72%   |
| 3      | 13        | 1.49%   |
| 4      | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 437       | 50.52%  |
| Yes       | 428       | 49.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 709       | 81.97%  |
| No        | 156       | 18.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 809       | 93.85%  |
| No        | 53        | 6.15%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 530       | 60.5%   |
| No        | 346       | 39.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 128       | 14.81%  |
| France       | 80        | 9.26%   |
| Brazil       | 77        | 8.91%   |
| Italy        | 70        | 8.1%    |
| Germany      | 61        | 7.06%   |
| Russia       | 51        | 5.9%    |
| UK           | 43        | 4.98%   |
| Poland       | 28        | 3.24%   |
| Canada       | 22        | 2.55%   |
| Spain        | 18        | 2.08%   |
| Netherlands  | 18        | 2.08%   |
| Indonesia    | 14        | 1.62%   |
| Turkey       | 13        | 1.5%    |
| Czechia      | 13        | 1.5%    |
| Belgium      | 13        | 1.5%    |
| Mexico       | 12        | 1.39%   |
| Australia    | 12        | 1.39%   |
| Ukraine      | 11        | 1.27%   |
| Argentina    | 11        | 1.27%   |
| India        | 10        | 1.16%   |
| Hungary      | 10        | 1.16%   |
| Switzerland  | 8         | 0.93%   |
| Ireland      | 6         | 0.69%   |
| Finland      | 6         | 0.69%   |
| Costa Rica   | 6         | 0.69%   |
| Colombia     | 6         | 0.69%   |
| Vietnam      | 5         | 0.58%   |
| Portugal     | 5         | 0.58%   |
| Chile        | 5         | 0.58%   |
| Sweden       | 4         | 0.46%   |
| South Africa | 4         | 0.46%   |
| Slovakia     | 4         | 0.46%   |
| Philippines  | 4         | 0.46%   |
| Malaysia     | 4         | 0.46%   |
| Lithuania    | 4         | 0.46%   |
| Taiwan       | 3         | 0.35%   |
| Serbia       | 3         | 0.35%   |
| Romania      | 3         | 0.35%   |
| Peru         | 3         | 0.35%   |
| Norway       | 3         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Paris          | 16        | 1.74%   |
| Moscow         | 11        | 1.2%    |
| Milan          | 11        | 1.2%    |
| Rome           | 9         | 0.98%   |
| Bengaluru      | 6         | 0.65%   |
| Porto Alegre   | 5         | 0.55%   |
| Melbourne      | 5         | 0.55%   |
| Kyiv           | 5         | 0.55%   |
| Houston        | 5         | 0.55%   |
| Heredia        | 5         | 0.55%   |
| Brasília      | 5         | 0.55%   |
| Yekaterinburg  | 4         | 0.44%   |
| Stuttgart      | 4         | 0.44%   |
| Prague         | 4         | 0.44%   |
| New York       | 4         | 0.44%   |
| Munich         | 4         | 0.44%   |
| Mexico City    | 4         | 0.44%   |
| Istanbul       | 4         | 0.44%   |
| Helsinki       | 4         | 0.44%   |
| Ghent          | 4         | 0.44%   |
| Bruhl          | 4         | 0.44%   |
| Bogotá        | 4         | 0.44%   |
| Amsterdam      | 4         | 0.44%   |
| Zurich         | 3         | 0.33%   |
| Winnipeg       | 3         | 0.33%   |
| Warsaw         | 3         | 0.33%   |
| Uberlândia    | 3         | 0.33%   |
| Teresina       | 3         | 0.33%   |
| St Petersburg  | 3         | 0.33%   |
| Sao Paulo      | 3         | 0.33%   |
| Salvador       | 3         | 0.33%   |
| Rio Segundo    | 3         | 0.33%   |
| Rio de Janeiro | 3         | 0.33%   |
| Oshawa         | 3         | 0.33%   |
| Nantes         | 3         | 0.33%   |
| Milano         | 3         | 0.33%   |
| Manchester     | 3         | 0.33%   |
| Madrid         | 3         | 0.33%   |
| Kuala Lumpur   | 3         | 0.33%   |
| Kazan’       | 3         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 132       | 155    | 13.61%  |
| Seagate                   | 126       | 143    | 12.99%  |
| Unknown                   | 113       | 158    | 11.65%  |
| Toshiba                   | 87        | 98     | 8.97%   |
| Samsung Electronics       | 79        | 118    | 8.14%   |
| Hitachi                   | 69        | 86     | 7.11%   |
| Kingston                  | 49        | 56     | 5.05%   |
| Crucial                   | 30        | 33     | 3.09%   |
| SanDisk                   | 29        | 34     | 2.99%   |
| HGST                      | 25        | 29     | 2.58%   |
| Fujitsu                   | 22        | 24     | 2.27%   |
| Intel                     | 21        | 31     | 2.16%   |
| SK hynix                  | 18        | 18     | 1.86%   |
| Micron Technology         | 13        | 14     | 1.34%   |
| Unknown                   | 12        | 13     | 1.24%   |
| Apacer                    | 10        | 10     | 1.03%   |
| China                     | 9         | 11     | 0.93%   |
| A-DATA Technology         | 9         | 9      | 0.93%   |
| Transcend                 | 6         | 7      | 0.62%   |
| Patriot                   | 6         | 6      | 0.62%   |
| SPCC                      | 5         | 6      | 0.52%   |
| LITEON                    | 5         | 6      | 0.52%   |
| KIOXIA                    | 5         | 5      | 0.52%   |
| PNY                       | 4         | 4      | 0.41%   |
| OCZ                       | 4         | 4      | 0.41%   |
| LITEONIT                  | 4         | 4      | 0.41%   |
| KingSpec                  | 4         | 6      | 0.41%   |
| Apple                     | 4         | 11     | 0.41%   |
| Silicon Motion            | 3         | 3      | 0.31%   |
| Phison                    | 3         | 7      | 0.31%   |
| NGFF                      | 3         | 3      | 0.31%   |
| LDLC                      | 3         | 4      | 0.31%   |
| IBM/Hitachi               | 3         | 4      | 0.31%   |
| UMIS                      | 2         | 2      | 0.21%   |
| Teclast                   | 2         | 2      | 0.21%   |
| STEC                      | 2         | 3      | 0.21%   |
| Micron/Crucial Technology | 2         | 2      | 0.21%   |
| KingDian                  | 2         | 2      | 0.21%   |
| JMicron Technology        | 2         | 2      | 0.21%   |
| GOODRAM                   | 2         | 2      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 27        | 2.66%   |
| Unknown MMC Card  64GB              | 16        | 1.58%   |
| Kingston SA400S37240G 240GB SSD     | 14        | 1.38%   |
| Seagate ST9500325AS 500GB           | 12        | 1.18%   |
| Seagate ST500LT012-1DG142 500GB     | 12        | 1.18%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 12        | 1.18%   |
| Unknown                             | 12        | 1.18%   |
| Toshiba MQ01ABF050 500GB            | 10        | 0.99%   |
| Toshiba MQ01ABD100 1TB              | 10        | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB      | 10        | 0.99%   |
| Unknown NCard  32GB                 | 9         | 0.89%   |
| Unknown MMC Card  16GB              | 9         | 0.89%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 8         | 0.79%   |
| Unknown DA4064  64GB                | 7         | 0.69%   |
| Samsung SSD 850 EVO 250GB           | 7         | 0.69%   |
| Crucial CT240BX500SSD1 240GB        | 7         | 0.69%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 6         | 0.59%   |
| Toshiba MQ01ABD050 500GB            | 6         | 0.59%   |
| SanDisk DF4032  32GB                | 6         | 0.59%   |
| Unknown SD/MMC/MS PRO 128GB         | 5         | 0.49%   |
| Seagate ST9320325AS 320GB           | 5         | 0.49%   |
| Kingston SA400S37480G 480GB SSD     | 5         | 0.49%   |
| Kingston SA400S37120G 120GB SSD     | 5         | 0.49%   |
| HGST HTS545050A7E680 500GB          | 5         | 0.49%   |
| HGST HTS545050A7E380 500GB          | 5         | 0.49%   |
| WDC WD10SPZX-24Z10T0 1TB            | 4         | 0.39%   |
| WDC WD10JPVX-22JC3T0 1TB            | 4         | 0.39%   |
| Unknown MMC64G  64GB                | 4         | 0.39%   |
| Unknown DA4032  32GB                | 4         | 0.39%   |
| SK hynix HBG4e  32GB                | 4         | 0.39%   |
| Seagate ST9250315AS 250GB           | 4         | 0.39%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4         | 0.39%   |
| Samsung SSD 860 EVO 500GB           | 4         | 0.39%   |
| Hitachi HTS547575A9E384 752GB       | 4         | 0.39%   |
| Hitachi HTS545050A7E380 500GB       | 4         | 0.39%   |
| Hitachi HTS545032B9A300 320GB       | 4         | 0.39%   |
| Hitachi HTS543216L9SA00 160GB       | 4         | 0.39%   |
| Hitachi HTS542512K9SA00 120GB       | 4         | 0.39%   |
| HGST HTS721010A9E630 1TB            | 4         | 0.39%   |
| Crucial CT480BX500SSD1 480GB        | 4         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 125       | 142    | 27.17%  |
| WDC                 | 113       | 130    | 24.57%  |
| Toshiba             | 74        | 81     | 16.09%  |
| Hitachi             | 69        | 86     | 15%     |
| HGST                | 25        | 29     | 5.43%   |
| Fujitsu             | 22        | 24     | 4.78%   |
| Samsung Electronics | 19        | 34     | 4.13%   |
| Unknown             | 5         | 7      | 1.09%   |
| IBM/Hitachi         | 3         | 4      | 0.65%   |
| XrayDisk            | 1         | 1      | 0.22%   |
| USB3.0              | 1         | 1      | 0.22%   |
| USB                 | 1         | 1      | 0.22%   |
| LaCie               | 1         | 1      | 0.22%   |
| Apple               | 1         | 1      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 41        | 46     | 14.75%  |
| Samsung Electronics | 39        | 55     | 14.03%  |
| Crucial             | 28        | 31     | 10.07%  |
| SanDisk             | 19        | 24     | 6.83%   |
| Intel               | 17        | 27     | 6.12%   |
| WDC                 | 10        | 13     | 3.6%    |
| Apacer              | 10        | 10     | 3.6%    |
| A-DATA Technology   | 9         | 9      | 3.24%   |
| Toshiba             | 8         | 10     | 2.88%   |
| China               | 7         | 9      | 2.52%   |
| Transcend           | 6         | 7      | 2.16%   |
| Patriot             | 6         | 6      | 2.16%   |
| SPCC                | 5         | 6      | 1.8%    |
| LITEON              | 5         | 6      | 1.8%    |
| PNY                 | 4         | 4      | 1.44%   |
| OCZ                 | 4         | 4      | 1.44%   |
| Micron Technology   | 4         | 4      | 1.44%   |
| LITEONIT            | 4         | 4      | 1.44%   |
| KingSpec            | 4         | 6      | 1.44%   |
| SK hynix            | 3         | 3      | 1.08%   |
| NGFF                | 3         | 3      | 1.08%   |
| Teclast             | 2         | 2      | 0.72%   |
| LDLC                | 2         | 2      | 0.72%   |
| KingDian            | 2         | 2      | 0.72%   |
| GOODRAM             | 2         | 2      | 0.72%   |
| Dogfish             | 2         | 2      | 0.72%   |
| Apple               | 2         | 8      | 0.72%   |
| XrayDisk            | 1         | 1      | 0.36%   |
| WALRAM              | 1         | 1      | 0.36%   |
| W800S               | 1         | 1      | 0.36%   |
| Vaseky              | 1         | 1      | 0.36%   |
| Unknown             | 1         | 1      | 0.36%   |
| TEAM T25            | 1         | 1      | 0.36%   |
| TCSUNBOW            | 1         | 1      | 0.36%   |
| Star                | 1         | 1      | 0.36%   |
| Seagate             | 1         | 1      | 0.36%   |
| Rogueware           | 1         | 1      | 0.36%   |
| Plextor             | 1         | 1      | 0.36%   |
| Netac               | 1         | 1      | 0.36%   |
| Neo Forza           | 1         | 1      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 453       | 542    | 47.53%  |
| SSD     | 269       | 336    | 28.23%  |
| MMC     | 128       | 173    | 13.43%  |
| NVMe    | 90        | 113    | 9.44%   |
| Unknown | 13        | 15     | 1.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 679       | 860    | 73.41%  |
| MMC  | 128       | 173    | 13.84%  |
| NVMe | 90        | 113    | 9.73%   |
| SAS  | 28        | 33     | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 559       | 691    | 78.73%  |
| 0.51-1.0   | 133       | 166    | 18.73%  |
| 1.01-2.0   | 11        | 13     | 1.55%   |
| 4.01-10.0  | 4         | 4      | 0.56%   |
| 3.01-4.0   | 2         | 3      | 0.28%   |
| 2.01-3.0   | 1         | 1      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 275       | 31.32%  |
| 251-500        | 214       | 24.37%  |
| 51-100         | 96        | 10.93%  |
| 501-1000       | 88        | 10.02%  |
| 21-50          | 81        | 9.23%   |
| 1-20           | 81        | 9.23%   |
| 1001-2000      | 22        | 2.51%   |
| More than 3000 | 11        | 1.25%   |
| 2001-3000      | 7         | 0.8%    |
| Unknown        | 3         | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 485       | 53.71%  |
| 21-50          | 177       | 19.6%   |
| 101-250        | 94        | 10.41%  |
| 51-100         | 75        | 8.31%   |
| 251-500        | 31        | 3.43%   |
| 501-1000       | 23        | 2.55%   |
| 1001-2000      | 9         | 1%      |
| More than 3000 | 4         | 0.44%   |
| Unknown        | 3         | 0.33%   |
| 2001-3000      | 2         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 6         | 6      | 5.94%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 4      | 3.96%   |
| Seagate ST9500325AS 500GB             | 3         | 3      | 2.97%   |
| Seagate ST9320325AS 320GB             | 3         | 3      | 2.97%   |
| Hitachi HTS545032B9A300 320GB         | 3         | 3      | 2.97%   |
| Hitachi HTS542512K9SA00 120GB         | 2         | 2      | 1.98%   |
| HGST HTS545050A7E380 500GB            | 2         | 2      | 1.98%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.99%   |
| WDC WD800BEVS-60RST0 80GB             | 1         | 1      | 0.99%   |
| WDC WD5000LUCT-62C26Y0 500GB          | 1         | 1      | 0.99%   |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 1      | 0.99%   |
| WDC WD5000BPVT-75HXZT1 500GB          | 1         | 1      | 0.99%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 0.99%   |
| WDC WD3200BPVT-75ZEST0 320GB          | 1         | 1      | 0.99%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 1      | 0.99%   |
| WDC WD3200BEVT-75A23T0 320GB          | 1         | 1      | 0.99%   |
| WDC WD3200BEKT-60PVMT0 320GB          | 1         | 1      | 0.99%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 2      | 0.99%   |
| WDC WD1200BEVS-60UST0 120GB           | 1         | 1      | 0.99%   |
| WDC WD1200BEVS-07LAT0 120GB           | 1         | 1      | 0.99%   |
| WDC WD10SPZX-24Z10T0 1TB              | 1         | 1      | 0.99%   |
| WDC WD10SPCX-21KHST0 1TB              | 1         | 1      | 0.99%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 1      | 0.99%   |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 1      | 0.99%   |
| Transcend TS256GSSD720 256GB          | 1         | 1      | 0.99%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 0.99%   |
| Toshiba MK5065GSXN 500GB              | 1         | 1      | 0.99%   |
| Toshiba MK5059GSXP 500GB              | 1         | 1      | 0.99%   |
| Toshiba MK3276GSX 320GB               | 1         | 1      | 0.99%   |
| Toshiba MK2556GSY 250GB               | 1         | 1      | 0.99%   |
| Toshiba MK2046GSX 200GB               | 1         | 1      | 0.99%   |
| TCSUNBOW X1 32GB SSD                  | 1         | 1      | 0.99%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 0.99%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 0.99%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 0.99%   |
| Seagate ST9250410AS 250GB             | 1         | 1      | 0.99%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 0.99%   |
| Seagate ST9160821AS 160GB             | 1         | 1      | 0.99%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 0.99%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 27     | 25.74%  |
| WDC                 | 17        | 18     | 16.83%  |
| Hitachi             | 15        | 16     | 14.85%  |
| Toshiba             | 7         | 7      | 6.93%   |
| HGST                | 7         | 7      | 6.93%   |
| Crucial             | 5         | 5      | 4.95%   |
| Intel               | 4         | 5      | 3.96%   |
| Fujitsu             | 3         | 3      | 2.97%   |
| SK hynix            | 2         | 2      | 1.98%   |
| Samsung Electronics | 2         | 10     | 1.98%   |
| LITEON              | 2         | 2      | 1.98%   |
| KingSpec            | 2         | 4      | 1.98%   |
| Transcend           | 1         | 1      | 0.99%   |
| TCSUNBOW            | 1         | 1      | 0.99%   |
| Plextor             | 1         | 1      | 0.99%   |
| OCZ                 | 1         | 1      | 0.99%   |
| NGFF                | 1         | 1      | 0.99%   |
| Kingston            | 1         | 1      | 0.99%   |
| Kingmax             | 1         | 1      | 0.99%   |
| Apacer              | 1         | 1      | 0.99%   |
| A-DATA Technology   | 1         | 1      | 0.99%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 27     | 34.21%  |
| WDC                 | 16        | 17     | 21.05%  |
| Hitachi             | 15        | 16     | 19.74%  |
| Toshiba             | 7         | 7      | 9.21%   |
| HGST                | 7         | 7      | 9.21%   |
| Fujitsu             | 3         | 3      | 3.95%   |
| Samsung Electronics | 2         | 10     | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 76        | 87     | 75.25%  |
| SSD  | 24        | 27     | 23.76%  |
| NVMe | 1         | 1      | 0.99%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 25%     |
| WDC WD1200BEVS-22UST0 120GB       | 1         | 1      | 25%     |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 25%     |
| Samsung Electronics HM320JI 320GB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 4      | 75%     |
| Samsung Electronics | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 484       | 674    | 53.66%  |
| Works    | 313       | 385    | 34.7%   |
| Malfunc  | 101       | 115    | 11.2%   |
| Failed   | 4         | 5      | 0.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 591       | 70.19%  |
| AMD                              | 131       | 15.56%  |
| Samsung Electronics              | 21        | 2.49%   |
| Nvidia                           | 15        | 1.78%   |
| SanDisk                          | 14        | 1.66%   |
| SK hynix                         | 10        | 1.19%   |
| Micron Technology                | 10        | 1.19%   |
| Silicon Integrated Systems [SiS] | 8         | 0.95%   |
| Kingston Technology Company      | 8         | 0.95%   |
| Toshiba America Info Systems     | 5         | 0.59%   |
| KIOXIA                           | 5         | 0.59%   |
| Silicon Motion                   | 4         | 0.48%   |
| Phison Electronics               | 4         | 0.48%   |
| Micron/Crucial Technology        | 4         | 0.48%   |
| VIA Technologies                 | 3         | 0.36%   |
| Union Memory (Shenzhen)          | 2         | 0.24%   |
| Solid State Storage Technology   | 2         | 0.24%   |
| JMicron Technology               | 2         | 0.24%   |
| ASMedia Technology               | 2         | 0.24%   |
| Silicon Image                    | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 83        | 8.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 70        | 7.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 56        | 5.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 47        | 4.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 45        | 4.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 45        | 4.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 41        | 4.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 31        | 3.21%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 29        | 3.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 27        | 2.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 27        | 2.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 26        | 2.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 26        | 2.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 20        | 2.07%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 19        | 1.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 19        | 1.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 16        | 1.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 15        | 1.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 14        | 1.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 12        | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 12        | 1.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 12        | 1.24%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 11        | 1.14%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 10        | 1.04%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 9         | 0.93%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 8         | 0.83%   |
| AMD IXP SB4x0 IDE Controller                                                           | 8         | 0.83%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 7         | 0.73%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 7         | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 7         | 0.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 0.62%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 6         | 0.62%   |
| AMD SB600 IDE                                                                          | 6         | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                  | 5         | 0.52%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 5         | 0.52%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 5         | 0.52%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                          | 5         | 0.52%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 5         | 0.52%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 5         | 0.52%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 4         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 620       | 68.06%  |
| IDE  | 165       | 18.11%  |
| NVMe | 88        | 9.66%   |
| RAID | 38        | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 709       | 82.25%  |
| AMD     | 152       | 17.63%  |
| Unknown | 1         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 16        | 1.86%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 14        | 1.62%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 13        | 1.51%   |
| Intel Atom CPU N270 @ 1.60GHz               | 13        | 1.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 9         | 1.04%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 9         | 1.04%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 9         | 1.04%   |
| Intel Atom CPU N455 @ 1.66GHz               | 9         | 1.04%   |
| Intel Atom CPU N450 @ 1.66GHz               | 9         | 1.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 8         | 0.93%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 8         | 0.93%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 8         | 0.93%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 8         | 0.93%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 8         | 0.93%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 8         | 0.93%   |
| AMD E-450 APU with Radeon HD Graphics       | 8         | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 7         | 0.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 7         | 0.81%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 7         | 0.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 7         | 0.81%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 7         | 0.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 7         | 0.81%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 6         | 0.7%    |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 6         | 0.7%    |
| Intel Pentium CPU N3710 @ 1.60GHz           | 6         | 0.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 6         | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz           | 6         | 0.7%    |
| Intel Core i5-2410M CPU @ 2.30GHz           | 6         | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 6         | 0.7%    |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 6         | 0.7%    |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 6         | 0.7%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 6         | 0.7%    |
| Intel Celeron CPU N3350 @ 1.10GHz           | 6         | 0.7%    |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 5         | 0.58%   |
| Intel Pentium Dual CPU T2310 @ 1.46GHz      | 5         | 0.58%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 5         | 0.58%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 5         | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 5         | 0.58%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 5         | 0.58%   |
| Intel Core 2 CPU T5500 @ 1.66GHz            | 5         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 144       | 16.71%  |
| Intel Celeron           | 113       | 13.11%  |
| Intel Atom              | 94        | 10.9%   |
| Intel Core i7           | 82        | 9.51%   |
| Intel Core i3           | 67        | 7.77%   |
| Intel Core 2 Duo        | 64        | 7.42%   |
| Intel Pentium           | 30        | 3.48%   |
| Other                   | 24        | 2.78%   |
| Intel Pentium Dual      | 23        | 2.67%   |
| Intel Pentium Dual-Core | 18        | 2.09%   |
| AMD A6                  | 18        | 2.09%   |
| AMD E                   | 17        | 1.97%   |
| AMD A4                  | 15        | 1.74%   |
| Intel Core 2            | 13        | 1.51%   |
| AMD E1                  | 12        | 1.39%   |
| AMD Ryzen 7             | 11        | 1.28%   |
| Intel Genuine           | 10        | 1.16%   |
| AMD Ryzen 5             | 10        | 1.16%   |
| AMD E2                  | 10        | 1.16%   |
| Intel Pentium Silver    | 7         | 0.81%   |
| Intel Celeron M         | 6         | 0.7%    |
| Intel Pentium M         | 5         | 0.58%   |
| Intel Celeron Dual-Core | 5         | 0.58%   |
| AMD Turion 64 X2 Mobile | 5         | 0.58%   |
| AMD A8                  | 5         | 0.58%   |
| AMD Mobile Sempron      | 4         | 0.46%   |
| AMD C-50                | 4         | 0.46%   |
| AMD Athlon              | 4         | 0.46%   |
| Intel Pentium 4         | 3         | 0.35%   |
| AMD Ryzen 7 PRO         | 3         | 0.35%   |
| AMD Ryzen 3             | 3         | 0.35%   |
| AMD C-60                | 3         | 0.35%   |
| AMD Athlon X2           | 3         | 0.35%   |
| AMD Athlon 64 X2        | 3         | 0.35%   |
| AMD A10                 | 3         | 0.35%   |
| Intel Core Duo          | 2         | 0.23%   |
| AMD Turion 64 Mobile    | 2         | 0.23%   |
| AMD Phenom II           | 2         | 0.23%   |
| Intel Mobile Pentium 4  | 1         | 0.12%   |
| Intel Core m7           | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 571       | 66.24%  |
| 4      | 188       | 21.81%  |
| 1      | 74        | 8.58%   |
| 8      | 15        | 1.74%   |
| 6      | 8         | 0.93%   |
| 10     | 3         | 0.35%   |
| 14     | 1         | 0.12%   |
| 12     | 1         | 0.12%   |
| 3      | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 861       | 99.88%  |
| 2      | 1         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 463       | 53.71%  |
| 2      | 399       | 46.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 814       | 94.43%  |
| 32-bit         | 47        | 5.45%   |
| Unknown        | 1         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 216       | 24.46%  |
| 0x206a7    | 53        | 6%      |
| 0x306a9    | 45        | 5.1%    |
| 0x6fd      | 41        | 4.64%   |
| 0x1067a    | 30        | 3.4%    |
| 0x40651    | 26        | 2.94%   |
| 0x20655    | 26        | 2.94%   |
| 0x05000119 | 24        | 2.72%   |
| 0x30678    | 22        | 2.49%   |
| 0x106ca    | 22        | 2.49%   |
| 0x406c3    | 20        | 2.27%   |
| 0x406e3    | 19        | 2.15%   |
| 0x406c4    | 19        | 2.15%   |
| 0x106c2    | 17        | 1.93%   |
| 0x806ec    | 15        | 1.7%    |
| 0x706a8    | 13        | 1.47%   |
| 0x706a1    | 13        | 1.47%   |
| 0x20652    | 13        | 1.47%   |
| 0x06006705 | 12        | 1.36%   |
| 0x306c3    | 11        | 1.25%   |
| 0x806ea    | 10        | 1.13%   |
| 0x806e9    | 10        | 1.13%   |
| 0x6f6      | 10        | 1.13%   |
| 0x10676    | 10        | 1.13%   |
| 0x6e8      | 9         | 1.02%   |
| 0x6d8      | 9         | 1.02%   |
| 0x306d4    | 9         | 1.02%   |
| 0x0700010f | 9         | 1.02%   |
| 0x06006704 | 8         | 0.91%   |
| 0x05000029 | 8         | 0.91%   |
| 0x6fb      | 7         | 0.79%   |
| 0x506c9    | 7         | 0.79%   |
| 0x10661    | 7         | 0.79%   |
| 0x806c1    | 6         | 0.68%   |
| 0x30661    | 6         | 0.68%   |
| 0x906ea    | 5         | 0.57%   |
| 0x806eb    | 5         | 0.57%   |
| 0x706e5    | 5         | 0.57%   |
| 0x906c0    | 4         | 0.45%   |
| 0x6ec      | 4         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Silvermont       | 93        | 10.79%  |
| Core             | 79        | 9.16%   |
| SandyBridge      | 70        | 8.12%   |
| KabyLake         | 60        | 6.96%   |
| IvyBridge        | 57        | 6.61%   |
| Penryn           | 55        | 6.38%   |
| Westmere         | 49        | 5.68%   |
| Bonnell          | 49        | 5.68%   |
| Haswell          | 48        | 5.57%   |
| Goldmont plus    | 35        | 4.06%   |
| Bobcat           | 34        | 3.94%   |
| Excavator        | 30        | 3.48%   |
| Skylake          | 28        | 3.25%   |
| P6               | 23        | 2.67%   |
| K8 Hammer        | 15        | 1.74%   |
| Goldmont         | 14        | 1.62%   |
| Broadwell        | 14        | 1.62%   |
| Jaguar           | 12        | 1.39%   |
| TigerLake        | 10        | 1.16%   |
| Puma             | 10        | 1.16%   |
| IceLake          | 10        | 1.16%   |
| Zen 2            | 8         | 0.93%   |
| Zen+             | 7         | 0.81%   |
| Unknown          | 7         | 0.81%   |
| Zen              | 6         | 0.7%    |
| Piledriver       | 6         | 0.7%    |
| K8 & K10 hybrid  | 6         | 0.7%    |
| Zen 3            | 5         | 0.58%   |
| Tremont          | 5         | 0.58%   |
| K10              | 5         | 0.58%   |
| Alderlake Hybrid | 5         | 0.58%   |
| NetBurst         | 4         | 0.46%   |
| K10 Llano        | 2         | 0.23%   |
| Nehalem          | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 626       | 64.47%  |
| AMD                              | 206       | 21.22%  |
| Nvidia                           | 129       | 13.29%  |
| Silicon Integrated Systems [SiS] | 6         | 0.62%   |
| VIA Technologies                 | 3         | 0.31%   |
| S3 Graphics                      | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 65        | 6.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 55        | 5.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 55        | 5.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 49        | 4.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 49        | 4.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 38        | 3.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 38        | 3.58%   |
| Intel Core Processor Integrated Graphics Controller                                      | 36        | 3.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 33        | 3.11%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 29        | 2.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 29        | 2.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 27        | 2.55%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 24        | 2.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 1.98%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 15        | 1.42%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 14        | 1.32%   |
| Intel HD Graphics 500                                                                    | 14        | 1.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 1.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 1.13%   |
| Intel HD Graphics 620                                                                    | 12        | 1.13%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 12        | 1.13%   |
| Intel UHD Graphics 620                                                                   | 11        | 1.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.04%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 1.04%   |
| Intel HD Graphics 5500                                                                   | 10        | 0.94%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 9         | 0.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 0.85%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 8         | 0.75%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 8         | 0.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 0.66%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 7         | 0.66%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                                 | 7         | 0.66%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.57%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 6         | 0.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 0.57%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 6         | 0.57%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 5         | 0.47%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.47%   |
| Intel JasperLake [UHD Graphics]                                                          | 5         | 0.47%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 5         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 512       | 59.33%  |
| 1 x AMD         | 156       | 18.08%  |
| Intel + Nvidia  | 70        | 8.11%   |
| 1 x Nvidia      | 55        | 6.37%   |
| Intel + AMD     | 35        | 4.06%   |
| 2 x AMD         | 11        | 1.27%   |
| Other           | 7         | 0.81%   |
| 1 x SiS         | 6         | 0.7%    |
| AMD + Nvidia    | 4         | 0.46%   |
| 2 x Intel       | 3         | 0.35%   |
| 1 x VIA         | 3         | 0.35%   |
| 1 x S3 Graphics | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 795       | 92.01%  |
| Proprietary | 47        | 5.44%   |
| Unknown     | 22        | 2.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 567       | 65.17%  |
| 0.01-0.5   | 183       | 21.03%  |
| 1.01-2.0   | 62        | 7.13%   |
| 0.51-1.0   | 36        | 4.14%   |
| 3.01-4.0   | 15        | 1.72%   |
| 5.01-6.0   | 4         | 0.46%   |
| 2.01-3.0   | 3         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 169       | 19.58%  |
| LG Display              | 122       | 14.14%  |
| Samsung Electronics     | 116       | 13.44%  |
| BOE                     | 104       | 12.05%  |
| Chimei Innolux          | 94        | 10.89%  |
| Chi Mei Optoelectronics | 38        | 4.4%    |
| LG Philips              | 27        | 3.13%   |
| Apple                   | 21        | 2.43%   |
| HannStar                | 19        | 2.2%    |
| Lenovo                  | 17        | 1.97%   |
| CPT                     | 14        | 1.62%   |
| InfoVision              | 12        | 1.39%   |
| Goldstar                | 12        | 1.39%   |
| Acer                    | 12        | 1.39%   |
| Dell                    | 10        | 1.16%   |
| Sharp                   | 9         | 1.04%   |
| Hewlett-Packard         | 9         | 1.04%   |
| PANDA                   | 6         | 0.7%    |
| Toshiba                 | 4         | 0.46%   |
| AOC                     | 4         | 0.46%   |
| Sony                    | 3         | 0.35%   |
| ViewSonic               | 2         | 0.23%   |
| Philips                 | 2         | 0.23%   |
| Panasonic               | 2         | 0.23%   |
| NEC Computers           | 2         | 0.23%   |
| KDC                     | 2         | 0.23%   |
| InnoLux Display         | 2         | 0.23%   |
| Iiyama                  | 2         | 0.23%   |
| BenQ                    | 2         | 0.23%   |
| ASUSTek Computer        | 2         | 0.23%   |
| Vizio                   | 1         | 0.12%   |
| Videoseven              | 1         | 0.12%   |
| Unknown                 | 1         | 0.12%   |
| Sceptre Tech            | 1         | 0.12%   |
| Quanta Display          | 1         | 0.12%   |
| Nvidia                  | 1         | 0.12%   |
| NCS                     | 1         | 0.12%   |
| LLL                     | 1         | 0.12%   |
| Lenovo Group Limited    | 1         | 0.12%   |
| JVC                     | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 10        | 1.15%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 1.15%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 9         | 1.04%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 8         | 0.92%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 8         | 0.92%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.81%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 7         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.69%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 5         | 0.58%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 5         | 0.58%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.58%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 5         | 0.58%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 5         | 0.58%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 5         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 4         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 4         | 0.46%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                     | 4         | 0.46%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 4         | 0.46%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.46%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 4         | 0.46%   |
| BOE LCD Monitor BOE0635 1920x1080 309x173mm 13.9-inch                    | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 4         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 3         | 0.35%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch            | 3         | 0.35%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 3         | 0.35%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch              | 3         | 0.35%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 3         | 0.35%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 3         | 0.35%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 387       | 45.8%   |
| 1920x1080 (FHD)    | 176       | 20.83%  |
| 1280x800 (WXGA)    | 104       | 12.31%  |
| 1600x900 (HD+)     | 48        | 5.68%   |
| 1024x600           | 32        | 3.79%   |
| 3840x2160 (4K)     | 18        | 2.13%   |
| 1920x1200 (WUXGA)  | 16        | 1.89%   |
| 1440x900 (WXGA+)   | 13        | 1.54%   |
| 1680x1050 (WSXGA+) | 9         | 1.07%   |
| 2560x1440 (QHD)    | 8         | 0.95%   |
| 1280x1024 (SXGA)   | 6         | 0.71%   |
| 3840x2400          | 4         | 0.47%   |
| 3200x1800 (QHD+)   | 3         | 0.36%   |
| 1360x768           | 3         | 0.36%   |
| 2880x1800          | 2         | 0.24%   |
| 2288x1287          | 2         | 0.24%   |
| 2160x1440          | 2         | 0.24%   |
| 1280x720 (HD)      | 2         | 0.24%   |
| 3200x1080          | 1         | 0.12%   |
| 3120x2080          | 1         | 0.12%   |
| 3000x2000          | 1         | 0.12%   |
| 2560x1600          | 1         | 0.12%   |
| 2560x1080          | 1         | 0.12%   |
| 1920x540           | 1         | 0.12%   |
| 1528x1222          | 1         | 0.12%   |
| 1280x768           | 1         | 0.12%   |
| 1024x768 (XGA)     | 1         | 0.12%   |
| Unknown            | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 345       | 40.02%  |
| 14      | 123       | 14.27%  |
| 13      | 113       | 13.11%  |
| 11      | 59        | 6.84%   |
| 17      | 56        | 6.5%    |
| 10      | 35        | 4.06%   |
| 12      | 29        | 3.36%   |
| 27      | 13        | 1.51%   |
| 23      | 11        | 1.28%   |
| 21      | 11        | 1.28%   |
| Unknown | 11        | 1.28%   |
| 24      | 10        | 1.16%   |
| 19      | 7         | 0.81%   |
| 22      | 6         | 0.7%    |
| 72      | 5         | 0.58%   |
| 84      | 4         | 0.46%   |
| 18      | 4         | 0.46%   |
| 9       | 3         | 0.35%   |
| 8       | 3         | 0.35%   |
| 28      | 2         | 0.23%   |
| 16      | 2         | 0.23%   |
| 142     | 1         | 0.12%   |
| 63      | 1         | 0.12%   |
| 54      | 1         | 0.12%   |
| 48      | 1         | 0.12%   |
| 44      | 1         | 0.12%   |
| 33      | 1         | 0.12%   |
| 31      | 1         | 0.12%   |
| 26      | 1         | 0.12%   |
| 25      | 1         | 0.12%   |
| 20      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 521       | 60.72%  |
| 201-300        | 172       | 20.05%  |
| 351-400        | 70        | 8.16%   |
| 501-600        | 35        | 4.08%   |
| 401-500        | 26        | 3.03%   |
| Unknown        | 11        | 1.28%   |
| 1501-2000      | 9         | 1.05%   |
| 601-700        | 4         | 0.47%   |
| 101-200        | 4         | 0.47%   |
| 1001-1500      | 3         | 0.35%   |
| More than 2000 | 1         | 0.12%   |
| 701-800        | 1         | 0.12%   |
| 901-1000       | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 636       | 79.01%  |
| 16/10   | 146       | 18.14%  |
| 3/2     | 6         | 0.75%   |
| Unknown | 6         | 0.75%   |
| 5/4     | 5         | 0.62%   |
| 4/3     | 4         | 0.5%    |
| 21/9    | 1         | 0.12%   |
| 1.00    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 343       | 39.79%  |
| 81-90          | 205       | 23.78%  |
| 51-60          | 59        | 6.84%   |
| 121-130        | 44        | 5.1%    |
| 41-50          | 38        | 4.41%   |
| 71-80          | 32        | 3.71%   |
| 201-250        | 31        | 3.6%    |
| 61-70          | 27        | 3.13%   |
| More than 1000 | 13        | 1.51%   |
| 301-350        | 13        | 1.51%   |
| 131-140        | 11        | 1.28%   |
| Unknown        | 11        | 1.28%   |
| 251-300        | 10        | 1.16%   |
| 151-200        | 8         | 0.93%   |
| 141-150        | 6         | 0.7%    |
| 351-500        | 3         | 0.35%   |
| 1-40           | 3         | 0.35%   |
| 111-120        | 2         | 0.23%   |
| 91-100         | 2         | 0.23%   |
| 501-1000       | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 398       | 46.71%  |
| 121-160       | 240       | 28.17%  |
| 51-100        | 156       | 18.31%  |
| 161-240       | 26        | 3.05%   |
| More than 240 | 12        | 1.41%   |
| Unknown       | 11        | 1.29%   |
| 1-50          | 9         | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 769       | 87.99%  |
| 2     | 82        | 9.38%   |
| 0     | 18        | 2.06%   |
| 3     | 5         | 0.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 440       | 32%     |
| Intel                             | 311       | 22.62%  |
| Qualcomm Atheros                  | 252       | 18.33%  |
| Broadcom                          | 126       | 9.16%   |
| Marvell Technology Group          | 40        | 2.91%   |
| Ralink                            | 30        | 2.18%   |
| Broadcom Limited                  | 30        | 2.18%   |
| TP-Link                           | 13        | 0.95%   |
| Ralink Technology                 | 13        | 0.95%   |
| Nvidia                            | 12        | 0.87%   |
| ASIX Electronics                  | 12        | 0.87%   |
| Attansic Technology               | 11        | 0.8%    |
| Samsung Electronics               | 9         | 0.65%   |
| MediaTek                          | 8         | 0.58%   |
| Xiaomi                            | 6         | 0.44%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.36%   |
| JMicron Technology                | 5         | 0.36%   |
| AMD                               | 4         | 0.29%   |
| VIA Technologies                  | 3         | 0.22%   |
| OPPO Electronics                  | 3         | 0.22%   |
| Micro Star International          | 3         | 0.22%   |
| Hewlett-Packard                   | 3         | 0.22%   |
| Dell                              | 3         | 0.22%   |
| Qualcomm Atheros Communications   | 2         | 0.15%   |
| Qualcomm                          | 2         | 0.15%   |
| NetGear                           | 2         | 0.15%   |
| ICS Advent                        | 2         | 0.15%   |
| Huawei Technologies               | 2         | 0.15%   |
| Fibocom                           | 2         | 0.15%   |
| Ericsson Business Mobile Networks | 2         | 0.15%   |
| Tenda                             | 1         | 0.07%   |
| Spreadtrum Communications         | 1         | 0.07%   |
| Sierra Wireless                   | 1         | 0.07%   |
| Seeed Technology                  | 1         | 0.07%   |
| Research In Motion                | 1         | 0.07%   |
| QinHeng Electronics               | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.07%   |
| Motorola PCS                      | 1         | 0.07%   |
| Microsoft                         | 1         | 0.07%   |
| Microchip Technology              | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 192       | 11.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 135       | 8.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 52        | 3.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 34        | 2.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 34        | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 1.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 31        | 1.91%   |
| Intel Wireless 7260                                                     | 31        | 1.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 30        | 1.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 28        | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 22        | 1.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 22        | 1.35%   |
| Intel Wireless 7265                                                     | 20        | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 16        | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 16        | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 0.98%   |
| Intel 82577LM Gigabit Network Connection                                | 15        | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 14        | 0.86%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 14        | 0.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 13        | 0.8%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 13        | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 0.74%   |
| Intel Wireless 3165                                                     | 12        | 0.74%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 11        | 0.68%   |
| Intel Wireless 8265 / 8275                                              | 11        | 0.68%   |
| Intel Wireless 3160                                                     | 11        | 0.68%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 0.68%   |
| Attansic AR8152 v2.0 Fast Ethernet                                      | 11        | 0.68%   |
| Realtek 802.11n WLAN Adapter                                            | 10        | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 10        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 9         | 0.55%   |
| Intel Wireless 8260                                                     | 9         | 0.55%   |
| Intel Ethernet Connection I218-LM                                       | 9         | 0.55%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 0.55%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 9         | 0.55%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 8         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 8         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 292       | 34.27%  |
| Qualcomm Atheros                  | 218       | 25.59%  |
| Realtek Semiconductor             | 160       | 18.78%  |
| Broadcom                          | 83        | 9.74%   |
| Ralink                            | 30        | 3.52%   |
| Broadcom Limited                  | 19        | 2.23%   |
| Ralink Technology                 | 13        | 1.53%   |
| TP-Link                           | 12        | 1.41%   |
| MediaTek                          | 7         | 0.82%   |
| Micro Star International          | 3         | 0.35%   |
| Qualcomm Atheros Communications   | 2         | 0.23%   |
| NetGear                           | 2         | 0.23%   |
| Fibocom                           | 2         | 0.23%   |
| Dell                              | 2         | 0.23%   |
| Tenda                             | 1         | 0.12%   |
| Sierra Wireless                   | 1         | 0.12%   |
| Microsoft                         | 1         | 0.12%   |
| Linksys                           | 1         | 0.12%   |
| Ericsson Business Mobile Networks | 1         | 0.12%   |
| D-Link                            | 1         | 0.12%   |
| ASUSTek Computer                  | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 52        | 6.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 34        | 3.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 34        | 3.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 3.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 31        | 3.61%   |
| Intel Wireless 7260                                                     | 31        | 3.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 30        | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 28        | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 2.56%   |
| Intel Wireless 7265                                                     | 20        | 2.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 2.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 1.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 16        | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 1.86%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 14        | 1.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 14        | 1.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 13        | 1.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 1.4%    |
| Intel Wireless 3165                                                     | 12        | 1.4%    |
| Intel Wireless 8265 / 8275                                              | 11        | 1.28%   |
| Intel Wireless 3160                                                     | 11        | 1.28%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 1.28%   |
| Realtek 802.11n WLAN Adapter                                            | 10        | 1.16%   |
| Intel Wireless 8260                                                     | 9         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 1.05%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 9         | 1.05%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 8         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 0.93%   |
| Intel WiFi Link 5100                                                    | 8         | 0.93%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 8         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                          | 8         | 0.93%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 8         | 0.93%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.81%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 7         | 0.81%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 7         | 0.81%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 374       | 50.4%   |
| Intel                            | 108       | 14.56%  |
| Qualcomm Atheros                 | 72        | 9.7%    |
| Broadcom                         | 57        | 7.68%   |
| Marvell Technology Group         | 40        | 5.39%   |
| Nvidia                           | 12        | 1.62%   |
| ASIX Electronics                 | 12        | 1.62%   |
| Broadcom Limited                 | 11        | 1.48%   |
| Attansic Technology              | 11        | 1.48%   |
| Xiaomi                           | 6         | 0.81%   |
| Samsung Electronics              | 6         | 0.81%   |
| Silicon Integrated Systems [SiS] | 5         | 0.67%   |
| JMicron Technology               | 5         | 0.67%   |
| VIA Technologies                 | 3         | 0.4%    |
| OPPO Electronics                 | 3         | 0.4%    |
| Qualcomm                         | 2         | 0.27%   |
| ICS Advent                       | 2         | 0.27%   |
| TP-Link                          | 1         | 0.13%   |
| Spreadtrum Communications        | 1         | 0.13%   |
| Research In Motion               | 1         | 0.13%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.13%   |
| Motorola PCS                     | 1         | 0.13%   |
| Microchip Technology             | 1         | 0.13%   |
| MediaTek                         | 1         | 0.13%   |
| LG Electronics                   | 1         | 0.13%   |
| Lab126                           | 1         | 0.13%   |
| Intersil                         | 1         | 0.13%   |
| Huawei Technologies              | 1         | 0.13%   |
| Hewlett-Packard                  | 1         | 0.13%   |
| 3Com                             | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 192       | 25.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 135       | 18.15%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 22        | 2.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 2.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 2.15%   |
| Intel 82577LM Gigabit Network Connection                          | 15        | 2.02%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 13        | 1.75%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 11        | 1.48%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 11        | 1.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 10        | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 1.21%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.21%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 8         | 1.08%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 1.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 1.08%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 7         | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.94%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.94%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 7         | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.94%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.81%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.81%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 6         | 0.81%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 6         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.67%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 5         | 0.67%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.67%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.67%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 5         | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4         | 0.54%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 4         | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.54%   |
| Nvidia MCP67 Ethernet                                             | 4         | 0.54%   |
| Nvidia MCP51 Ethernet Controller                                  | 4         | 0.54%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 0.54%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 4         | 0.54%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 811       | 52.59%  |
| Ethernet | 707       | 45.85%  |
| Modem    | 24        | 1.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 654       | 75.61%  |
| Ethernet | 211       | 24.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 629       | 72.89%  |
| 1     | 165       | 19.12%  |
| 0     | 61        | 7.07%   |
| 3     | 8         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 720       | 82.19%  |
| Yes  | 156       | 17.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 173       | 32.22%  |
| Realtek Semiconductor           | 65        | 12.1%   |
| Qualcomm Atheros Communications | 57        | 10.61%  |
| Broadcom                        | 43        | 8.01%   |
| Lite-On Technology              | 25        | 4.66%   |
| IMC Networks                    | 24        | 4.47%   |
| Cambridge Silicon Radio         | 22        | 4.1%    |
| Foxconn / Hon Hai               | 20        | 3.72%   |
| Hewlett-Packard                 | 19        | 3.54%   |
| Dell                            | 18        | 3.35%   |
| Apple                           | 18        | 3.35%   |
| Ralink                          | 13        | 2.42%   |
| Toshiba                         | 12        | 2.23%   |
| Alps Electric                   | 9         | 1.68%   |
| ASUSTek Computer                | 7         | 1.3%    |
| Ralink Technology               | 2         | 0.37%   |
| Micro Star International        | 2         | 0.37%   |
| MediaTek                        | 2         | 0.37%   |
| Askey Computer                  | 2         | 0.37%   |
| TP-Link                         | 1         | 0.19%   |
| Syntek                          | 1         | 0.19%   |
| Qcom                            | 1         | 0.19%   |
| Chicony Electronics             | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 98        | 18.18%  |
| Realtek Bluetooth Radio                                                             | 40        | 7.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 27        | 5.01%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 25        | 4.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 22        | 4.08%   |
| Intel AX201 Bluetooth                                                               | 14        | 2.6%    |
| Ralink RT3290 Bluetooth                                                             | 13        | 2.41%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 12        | 2.23%   |
| Intel AX200 Bluetooth                                                               | 11        | 2.04%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 11        | 2.04%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 11        | 2.04%   |
| Apple Bluetooth Host Controller                                                     | 11        | 2.04%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 10        | 1.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 9         | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 9         | 1.67%   |
| Realtek RTL8723B Bluetooth                                                          | 8         | 1.48%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 8         | 1.48%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 8         | 1.48%   |
| Realtek 802.11ac WLAN Adapter                                                       | 7         | 1.3%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 7         | 1.3%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 7         | 1.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 1.11%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 6         | 1.11%   |
| IMC Networks Bluetooth Radio                                                        | 6         | 1.11%   |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 0.93%   |
| IMC Networks Bluetooth module                                                       | 5         | 0.93%   |
| IMC Networks Bluetooth Device                                                       | 5         | 0.93%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.93%   |
| Dell Wireless 365 Bluetooth                                                         | 5         | 0.93%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 5         | 0.93%   |
| Apple Bluetooth HCI                                                                 | 5         | 0.93%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 0.74%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 4         | 0.74%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.56%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 3         | 0.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 0.56%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 0.56%   |
| Intel Bluetooth Device                                                              | 3         | 0.56%   |
| Dell Wireless 350 Bluetooth                                                         | 3         | 0.56%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 3         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 642       | 70.94%  |
| AMD                               | 163       | 18.01%  |
| Nvidia                            | 68        | 7.51%   |
| Silicon Integrated Systems [SiS]  | 7         | 0.77%   |
| GN Netcom                         | 4         | 0.44%   |
| C-Media Electronics               | 4         | 0.44%   |
| VIA Technologies                  | 3         | 0.33%   |
| Logitech                          | 3         | 0.33%   |
| Plantronics                       | 2         | 0.22%   |
| Texas Instruments                 | 1         | 0.11%   |
| Realtek Semiconductor             | 1         | 0.11%   |
| QinHeng Electronics               | 1         | 0.11%   |
| MosArt Semiconductor              | 1         | 0.11%   |
| JMTek                             | 1         | 0.11%   |
| Hewlett-Packard                   | 1         | 0.11%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.11%   |
| EGO SYStems                       | 1         | 0.11%   |
| ASUSTek Computer                  | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 78        | 7.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 65        | 6%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 59        | 5.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 50        | 4.62%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 49        | 4.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 49        | 4.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 49        | 4.52%   |
| AMD FCH Azalia Controller                                                                         | 41        | 3.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 36        | 3.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 35        | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 33        | 3.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 32        | 2.95%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 2.77%   |
| AMD Wrestler HDMI Audio                                                                           | 27        | 2.49%   |
| AMD High Definition Audio Controller                                                              | 27        | 2.49%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 27        | 2.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 26        | 2.4%    |
| AMD Kabini HDMI/DP Audio                                                                          | 25        | 2.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 24        | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 1.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 1.29%   |
| Intel Broadwell-U Audio Controller                                                                | 14        | 1.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 1.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 0.92%   |
| Nvidia High Definition Audio Controller                                                           | 9         | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 9         | 0.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 0.74%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 7         | 0.65%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 6         | 0.55%   |
| AMD Trinity HDMI Audio Controller                                                                 | 6         | 0.55%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.46%   |
| Intel Jasper Lake HD Audio                                                                        | 5         | 0.46%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.46%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 5         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 144       | 22.68%  |
| SK hynix            | 128       | 20.16%  |
| Unknown             | 114       | 17.95%  |
| Micron Technology   | 59        | 9.29%   |
| Kingston            | 31        | 4.88%   |
| Unknown (ABCD)      | 21        | 3.31%   |
| A-DATA Technology   | 19        | 2.99%   |
| Nanya Technology    | 17        | 2.68%   |
| Crucial             | 16        | 2.52%   |
| Elpida              | 15        | 2.36%   |
| Corsair             | 12        | 1.89%   |
| Smart               | 7         | 1.1%    |
| Ramaxel Technology  | 7         | 1.1%    |
| Teikon              | 4         | 0.63%   |
| Unknown             | 4         | 0.63%   |
| Transcend           | 3         | 0.47%   |
| Team                | 3         | 0.47%   |
| Apacer              | 3         | 0.47%   |
| Toshiba             | 2         | 0.31%   |
| Qimonda             | 2         | 0.31%   |
| Patriot             | 2         | 0.31%   |
| G.Skill             | 2         | 0.31%   |
| fef5                | 2         | 0.31%   |
| Smart Brazil        | 1         | 0.16%   |
| Sesame              | 1         | 0.16%   |
| PUSKILL             | 1         | 0.16%   |
| PNY                 | 1         | 0.16%   |
| Novatech            | 1         | 0.16%   |
| Neo Forza           | 1         | 0.16%   |
| Multilaser          | 1         | 0.16%   |
| Kllisre             | 1         | 0.16%   |
| Kingmax             | 1         | 0.16%   |
| HMD                 | 1         | 0.16%   |
| High Bridge         | 1         | 0.16%   |
| GOODRAM             | 1         | 0.16%   |
| Goldkey             | 1         | 0.16%   |
| Goldenmars          | 1         | 0.16%   |
| Digiboard           | 1         | 0.16%   |
| Avant               | 1         | 0.16%   |
| ASint Technology    | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 17        | 2.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 12        | 1.74%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 11        | 1.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 10        | 1.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 9         | 1.3%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 9         | 1.3%    |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                     | 8         | 1.16%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s          | 8         | 1.16%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s              | 8         | 1.16%   |
| Unknown RAM Module 1024MB SODIMM DDR2                             | 7         | 1.01%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s             | 7         | 1.01%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                       | 6         | 0.87%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 5         | 0.72%   |
| Unknown RAM Module 1024MB SODIMM DRAM                             | 5         | 0.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 5         | 0.72%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s            | 5         | 0.72%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s             | 5         | 0.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 5         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3                                | 4         | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 4         | 0.58%   |
| Unknown RAM Module 2048MB SODIMM DDR2                             | 4         | 0.58%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                        | 4         | 0.58%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                     | 4         | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 4         | 0.58%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 4         | 0.58%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 0.58%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s            | 4         | 0.58%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 4         | 0.58%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s             | 4         | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 4         | 0.58%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 4         | 0.58%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 4         | 0.58%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 3200MT/s          | 4         | 0.58%   |
| Unknown                                                           | 4         | 0.58%   |
| Unknown RAM Module 512MB SODIMM DDR2                              | 3         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                       | 3         | 0.43%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                        | 3         | 0.43%   |
| Unknown RAM Module 1024MB SODIMM DDR                              | 3         | 0.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 3         | 0.43%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s            | 3         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 262       | 47.46%  |
| DDR4    | 128       | 23.19%  |
| DDR2    | 71        | 12.86%  |
| LPDDR4  | 36        | 6.52%   |
| SDRAM   | 18        | 3.26%   |
| LPDDR3  | 11        | 1.99%   |
| DRAM    | 7         | 1.27%   |
| LPDDR5  | 6         | 1.09%   |
| DDR     | 6         | 1.09%   |
| Unknown | 5         | 0.91%   |
| DDR5    | 2         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 501       | 91.93%  |
| Row Of Chips | 28        | 5.14%   |
| DIMM         | 8         | 1.47%   |
| Unknown      | 7         | 1.28%   |
| Chip         | 1         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 204       | 32.38%  |
| 2048  | 161       | 25.56%  |
| 8192  | 151       | 23.97%  |
| 1024  | 69        | 10.95%  |
| 16384 | 26        | 4.13%   |
| 512   | 9         | 1.43%   |
| 32768 | 8         | 1.27%   |
| 256   | 1         | 0.16%   |
| 128   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 153       | 25.71%  |
| 2400    | 55        | 9.24%   |
| 1334    | 48        | 8.07%   |
| 3200    | 46        | 7.73%   |
| 2667    | 46        | 7.73%   |
| 667     | 40        | 6.72%   |
| 1333    | 37        | 6.22%   |
| Unknown | 35        | 5.88%   |
| 1066    | 20        | 3.36%   |
| 1067    | 17        | 2.86%   |
| 2133    | 16        | 2.69%   |
| 533     | 16        | 2.69%   |
| 3266    | 9         | 1.51%   |
| 800     | 9         | 1.51%   |
| 2048    | 8         | 1.34%   |
| 1867    | 7         | 1.18%   |
| 6400    | 5         | 0.84%   |
| 4267    | 5         | 0.84%   |
| 1866    | 5         | 0.84%   |
| 4199    | 4         | 0.67%   |
| 975     | 4         | 0.67%   |
| 4800    | 2         | 0.34%   |
| 8400    | 1         | 0.17%   |
| 5500    | 1         | 0.17%   |
| 2933    | 1         | 0.17%   |
| 1200    | 1         | 0.17%   |
| 933     | 1         | 0.17%   |
| 400     | 1         | 0.17%   |
| 2       | 1         | 0.17%   |
| 1       | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 4         | 33.33%  |
| Brother Industries    | 3         | 25%     |
| Samsung Electronics   | 2         | 16.67%  |
| STMicroelectronics    | 1         | 8.33%   |
| Lexmark International | 1         | 8.33%   |
| Canon                 | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| STMicroelectronics USB Printing Support | 1         | 8.33%   |
| Samsung SCX-4200 series                 | 1         | 8.33%   |
| Samsung ML-1640 Series Laser Printer    | 1         | 8.33%   |
| Lexmark International MS610de           | 1         | 8.33%   |
| HP LaserJet P1102                       | 1         | 8.33%   |
| HP LaserJet 1200                        | 1         | 8.33%   |
| HP Deskjet 3520 series                  | 1         | 8.33%   |
| HP Deskjet 1050 J410                    | 1         | 8.33%   |
| Canon MF3110                            | 1         | 8.33%   |
| Brother PTUSB Printing                  | 1         | 8.33%   |
| Brother PT-2450DX                       | 1         | 8.33%   |
| Brother DCP-7055W                       | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 50%     |
| Canon CanoScan LiDE 500F                                      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 187       | 27.3%   |
| Realtek Semiconductor                  | 62        | 9.05%   |
| Microdia                               | 51        | 7.45%   |
| IMC Networks                           | 49        | 7.15%   |
| Suyin                                  | 36        | 5.26%   |
| Sunplus Innovation Technology          | 29        | 4.23%   |
| Cheng Uei Precision Industry (Foxlink) | 29        | 4.23%   |
| Bison Electronics                      | 28        | 4.09%   |
| Alcor Micro                            | 28        | 4.09%   |
| Quanta                                 | 25        | 3.65%   |
| Silicon Motion                         | 21        | 3.07%   |
| Apple                                  | 20        | 2.92%   |
| Syntek                                 | 18        | 2.63%   |
| Lite-On Technology                     | 16        | 2.34%   |
| Ricoh                                  | 9         | 1.31%   |
| Lenovo                                 | 9         | 1.31%   |
| ALi                                    | 8         | 1.17%   |
| Acer                                   | 8         | 1.17%   |
| Luxvisions Innotech Limited            | 6         | 0.88%   |
| Z-Star Microelectronics                | 5         | 0.73%   |
| Importek                               | 5         | 0.73%   |
| GEMBIRD                                | 5         | 0.73%   |
| icSpring                               | 4         | 0.58%   |
| Y Media                                | 2         | 0.29%   |
| USB Camera CS                          | 2         | 0.29%   |
| SunplusIT                              | 2         | 0.29%   |
| Samsung Electronics                    | 2         | 0.29%   |
| OmniVision Technologies                | 2         | 0.29%   |
| Logitech                               | 2         | 0.29%   |
| Genesys Logic                          | 2         | 0.29%   |
| WCM_USB                                | 1         | 0.15%   |
| Toshiba                                | 1         | 0.15%   |
| Sonix Technology                       | 1         | 0.15%   |
| Novatek Microelectronics               | 1         | 0.15%   |
| Nintendo                               | 1         | 0.15%   |
| LG Electronics                         | 1         | 0.15%   |
| Hy-UXGA(B5M2)-Camera                   | 1         | 0.15%   |
| HD USB Camera                          | 1         | 0.15%   |
| Generalplus Technology                 | 1         | 0.15%   |
| DigiTech                               | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Alcor Micro USB 2.0 Camera                              | 21        | 3.05%   |
| Chicony Integrated Camera                               | 20        | 2.91%   |
| Realtek Integrated_Webcam_HD                            | 16        | 2.33%   |
| Chicony HP Truevision HD                                | 12        | 1.74%   |
| Realtek USB Camera                                      | 10        | 1.45%   |
| Chicony USB 2.0 Camera                                  | 10        | 1.45%   |
| Chicony HD WebCam                                       | 10        | 1.45%   |
| Sunplus HD WebCam                                       | 9         | 1.31%   |
| Chicony EasyCamera                                      | 9         | 1.31%   |
| Chicony HP TrueVision HD Camera                         | 8         | 1.16%   |
| Chicony HP HD Webcam                                    | 8         | 1.16%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 8         | 1.16%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 7         | 1.02%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 7         | 1.02%   |
| Chicony TOSHIBA Web Camera - HD                         | 7         | 1.02%   |
| Apple FaceTime HD Camera                                | 7         | 1.02%   |
| Microdia Integrated_Webcam_HD                           | 6         | 0.87%   |
| Microdia 1.3 MPixel Integrated Webcam                   | 6         | 0.87%   |
| Lite-On HP HD Camera                                    | 6         | 0.87%   |
| IMC Networks UVC VGA Webcam                             | 6         | 0.87%   |
| Chicony HP Webcam                                       | 6         | 0.87%   |
| Bison Lenovo EasyCamera                                 | 6         | 0.87%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 6         | 0.87%   |
| Suyin Acer CrystalEye Webcam                            | 5         | 0.73%   |
| Silicon Motion WebCam SC-0311139N                       | 5         | 0.73%   |
| Quanta HP HD Camera                                     | 5         | 0.73%   |
| Microdia Integrated Webcam                              | 5         | 0.73%   |
| Lenovo Integrated Webcam [R5U877]                       | 5         | 0.73%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 5         | 0.73%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]       | 5         | 0.73%   |
| Chicony VGA WebCam                                      | 5         | 0.73%   |
| Chicony HP HD Camera                                    | 5         | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101    | 5         | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 5         | 0.73%   |
| ALi WebCam                                              | 5         | 0.73%   |
| Z-Star Webcam                                           | 4         | 0.58%   |
| Syntek Lenovo EasyCamera                                | 4         | 0.58%   |
| Sunplus ASUS Webcam                                     | 4         | 0.58%   |
| Realtek Lenovo EasyCamera                               | 4         | 0.58%   |
| Realtek HD WebCam                                       | 4         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 34        | 40.48%  |
| AuthenTec                  | 16        | 19.05%  |
| Upek                       | 11        | 13.1%   |
| STMicroelectronics         | 7         | 8.33%   |
| Shenzhen Goodix Technology | 7         | 8.33%   |
| Synaptics                  | 5         | 5.95%   |
| LighTuning Technology      | 2         | 2.38%   |
| Samsung Electronics        | 1         | 1.19%   |
| Elan Microelectronics      | 1         | 1.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 10        | 11.9%   |
| Validity Sensors VFS495 Fingerprint Reader               | 9         | 10.71%  |
| STMicroelectronics Fingerprint Reader                    | 7         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader               | 5         | 5.95%   |
| AuthenTec AES2810                                        | 5         | 5.95%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 5         | 5.95%   |
| Shenzhen Goodix  FingerPrint Device                      | 4         | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 3         | 3.57%   |
| Validity Sensors VFS491                                  | 3         | 3.57%   |
| Validity Sensors VFS451 Fingerprint Reader               | 3         | 3.57%   |
| AuthenTec AES1600                                        | 3         | 3.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 2         | 2.38%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 2.38%   |
| Validity Sensors Fingerprint scanner                     | 2         | 2.38%   |
| Synaptics Fingerprint reader [HP G6]                     | 2         | 2.38%   |
| Shenzhen Goodix FingerPrint                              | 2         | 2.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 2         | 2.38%   |
| AuthenTec AES1660 Fingerprint Sensor                     | 2         | 2.38%   |
| Validity Sensors VFS301 Fingerprint Reader               | 1         | 1.19%   |
| Validity Sensors VFS300 Fingerprint Reader               | 1         | 1.19%   |
| Validity Sensors VFS101 Fingerprint Reader               | 1         | 1.19%   |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 1.19%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 1.19%   |
| Upek TCS5B Fingerprint sensor                            | 1         | 1.19%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 1.19%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 1.19%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1.19%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 1.19%   |
| Samsung Fingerprint Device                               | 1         | 1.19%   |
| Elan ELAN:Fingerprint                                    | 1         | 1.19%   |
| AuthenTec Fingerprint Sensor                             | 1         | 1.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 12        | 36.36%  |
| Alcor Micro           | 10        | 30.3%   |
| O2 Micro              | 7         | 21.21%  |
| Upek                  | 1         | 3.03%   |
| Realtek Semiconductor | 1         | 3.03%   |
| Lenovo                | 1         | 3.03%   |
| Gemalto (was Gemplus) | 1         | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 27.27%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 15.15%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 15.15%  |
| Broadcom 5880                                                                | 5         | 15.15%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 6.06%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.03%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 3.03%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.03%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 3.03%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.03%   |
| Broadcom 58200                                                               | 1         | 3.03%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 611       | 70.39%  |
| 1     | 213       | 24.54%  |
| 2     | 35        | 4.03%   |
| 3     | 7         | 0.81%   |
| 4     | 2         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 84        | 27.36%  |
| Fingerprint reader       | 83        | 27.04%  |
| Net/wireless             | 32        | 10.42%  |
| Chipcard                 | 30        | 9.77%   |
| Bluetooth                | 21        | 6.84%   |
| Camera                   | 12        | 3.91%   |
| Storage                  | 8         | 2.61%   |
| Modem                    | 8         | 2.61%   |
| Multimedia controller    | 7         | 2.28%   |
| Net/ethernet             | 5         | 1.63%   |
| Flash memory             | 5         | 1.63%   |
| Sound                    | 3         | 0.98%   |
| Dvb card                 | 3         | 0.98%   |
| Communication controller | 3         | 0.98%   |
| Network                  | 2         | 0.65%   |
| Card reader              | 1         | 0.33%   |

