Lubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 341

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | G405 20239                  | [7afc820794](https://linux-hardware.org/?probe=7afc820794) | Feb 01, 2024 |
| Acer          | Swift SF314-43              | [793c3d3b4c](https://linux-hardware.org/?probe=793c3d3b4c) | Jan 31, 2024 |
| Lenovo        | G575 20081                  | [162e1f81cf](https://linux-hardware.org/?probe=162e1f81cf) | Jan 31, 2024 |
| Lenovo        | V310-15ISK 80SY             | [a72292c97b](https://linux-hardware.org/?probe=a72292c97b) | Jan 31, 2024 |
| Lenovo        | ThinkPad T60p 20078JU       | [6c83cf1141](https://linux-hardware.org/?probe=6c83cf1141) | Jan 25, 2024 |
| Acer          | Aspire E1-572G              | [d94fb0b47b](https://linux-hardware.org/?probe=d94fb0b47b) | Jan 24, 2024 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [82175efff8](https://linux-hardware.org/?probe=82175efff8) | Jan 14, 2024 |
| iRU           | 15TLI                       | [d318923a72](https://linux-hardware.org/?probe=d318923a72) | Jan 09, 2024 |
| ASUSTek       | K53U                        | [df631caaa2](https://linux-hardware.org/?probe=df631caaa2) | Jan 09, 2024 |
| Lenovo        | ThinkPad T430 23477C7       | [db1c43a6a6](https://linux-hardware.org/?probe=db1c43a6a6) | Jan 09, 2024 |
| HP            | 240 G6 Notebook PC          | [52fa49b647](https://linux-hardware.org/?probe=52fa49b647) | Jan 08, 2024 |
| HP            | Notebook                    | [79932769a2](https://linux-hardware.org/?probe=79932769a2) | Jan 08, 2024 |
| Digibras      | NH4CU03                     | [be0eab4038](https://linux-hardware.org/?probe=be0eab4038) | Jan 05, 2024 |
| Google        | Electro                     | [74ed1caffe](https://linux-hardware.org/?probe=74ed1caffe) | Jan 04, 2024 |
| Packard Be... | EasyNote LM85               | [e756bb57ba](https://linux-hardware.org/?probe=e756bb57ba) | Jan 03, 2024 |
| HP            | Notebook                    | [3db48f7d59](https://linux-hardware.org/?probe=3db48f7d59) | Jan 02, 2024 |
| Apple         | MacBook6,1                  | [ba4ad2bc18](https://linux-hardware.org/?probe=ba4ad2bc18) | Dec 31, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | [af69ec2d33](https://linux-hardware.org/?probe=af69ec2d33) | Dec 29, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | [143c6b4161](https://linux-hardware.org/?probe=143c6b4161) | Dec 29, 2023 |
| Chuwi         | GemiBook Plus               | [acb06bb39a](https://linux-hardware.org/?probe=acb06bb39a) | Dec 29, 2023 |
| Google        | Swanky                      | [12fd273db1](https://linux-hardware.org/?probe=12fd273db1) | Dec 27, 2023 |
| Acer          | Extensa 215-55              | [54ca5c9e74](https://linux-hardware.org/?probe=54ca5c9e74) | Dec 25, 2023 |
| Acer          | Aspire 1810TZ               | [0b4e0e5e2b](https://linux-hardware.org/?probe=0b4e0e5e2b) | Dec 24, 2023 |
| Acer          | Aspire 1810TZ               | [3ba98d8db9](https://linux-hardware.org/?probe=3ba98d8db9) | Dec 24, 2023 |
| HP            | ZBook 17                    | [d1269ca08c](https://linux-hardware.org/?probe=d1269ca08c) | Dec 13, 2023 |
| Dell          | Inspiron 3421               | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [5a628a7b0f](https://linux-hardware.org/?probe=5a628a7b0f) | Nov 30, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3b82362902](https://linux-hardware.org/?probe=3b82362902) | Nov 29, 2023 |
| SGIN          | M15                         | [c7fb994367](https://linux-hardware.org/?probe=c7fb994367) | Nov 28, 2023 |
| Dell          | Latitude E6520              | [a03b74a3d3](https://linux-hardware.org/?probe=a03b74a3d3) | Nov 28, 2023 |
| ASUSTek       | X550ZE                      | [dedc54db8f](https://linux-hardware.org/?probe=dedc54db8f) | Nov 27, 2023 |
| Chuwi         | X312B                       | [7f13217449](https://linux-hardware.org/?probe=7f13217449) | Nov 23, 2023 |
| MSI           | Raider GE76 12UE            | [bad07cc00d](https://linux-hardware.org/?probe=bad07cc00d) | Nov 20, 2023 |
| Packard Be... | ENLE11BZ                    | [905ad855b3](https://linux-hardware.org/?probe=905ad855b3) | Nov 19, 2023 |
| ASUSTek       | X201E                       | [3532136698](https://linux-hardware.org/?probe=3532136698) | Nov 18, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [d297e1365c](https://linux-hardware.org/?probe=d297e1365c) | Nov 16, 2023 |
| HP            | 250 G5 Notebook PC          | [dde4f98b29](https://linux-hardware.org/?probe=dde4f98b29) | Nov 16, 2023 |
| Acer          | Extensa 5620                | [3c206e8578](https://linux-hardware.org/?probe=3c206e8578) | Nov 13, 2023 |
| ASUSTek       | T100TAS                     | [ff4068e60a](https://linux-hardware.org/?probe=ff4068e60a) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fa680be8d9](https://linux-hardware.org/?probe=fa680be8d9) | Nov 10, 2023 |
| ASUSTek       | X550ZE                      | [31d4fc8694](https://linux-hardware.org/?probe=31d4fc8694) | Nov 09, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [cf0c02a17a](https://linux-hardware.org/?probe=cf0c02a17a) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [fdb464fed7](https://linux-hardware.org/?probe=fdb464fed7) | Nov 02, 2023 |
| ASUSTek       | K50IJ                       | [115cf0d371](https://linux-hardware.org/?probe=115cf0d371) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | [6fbbd2a061](https://linux-hardware.org/?probe=6fbbd2a061) | Oct 30, 2023 |
| Acer          | Aspire A315-21              | [48785f697c](https://linux-hardware.org/?probe=48785f697c) | Oct 29, 2023 |
| Dixonsxp      | Unknown                     | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| Dell          | XPS 9315                    | [8c9d16e737](https://linux-hardware.org/?probe=8c9d16e737) | Oct 22, 2023 |
| HP            | Compaq Presario CQ40        | [5ddf61741f](https://linux-hardware.org/?probe=5ddf61741f) | Oct 20, 2023 |
| Acer          | Aspire A314-23P             | [99490448ae](https://linux-hardware.org/?probe=99490448ae) | Oct 16, 2023 |
| Acer          | Aspire A314-23P             | [431b672bf5](https://linux-hardware.org/?probe=431b672bf5) | Oct 16, 2023 |
| HP            | Laptop 14-dq0xxx            | [1f161ae269](https://linux-hardware.org/?probe=1f161ae269) | Oct 16, 2023 |
| Google        | Careena                     | [8359c8c3e8](https://linux-hardware.org/?probe=8359c8c3e8) | Oct 15, 2023 |
| Google        | Careena                     | [4292c49150](https://linux-hardware.org/?probe=4292c49150) | Oct 15, 2023 |
| HP            | Notebook                    | [fb39ee7d9d](https://linux-hardware.org/?probe=fb39ee7d9d) | Oct 13, 2023 |
| Thomson       | NEO14-4W64                  | [f68e52a8a1](https://linux-hardware.org/?probe=f68e52a8a1) | Oct 12, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [ee4617fa73](https://linux-hardware.org/?probe=ee4617fa73) | Oct 10, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
| Google        | Sasuke                      | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| Insyde        | Braswell                    | [c4261097f5](https://linux-hardware.org/?probe=c4261097f5) | Oct 07, 2023 |
| Getac         | X500G3                      | [919772eed0](https://linux-hardware.org/?probe=919772eed0) | Oct 02, 2023 |
| Panasonic     | CF-F9KWPZFFE                | [33cf16d622](https://linux-hardware.org/?probe=33cf16d622) | Oct 01, 2023 |
| HP            | Laptop 14-ck0xxx            | [f4326ad956](https://linux-hardware.org/?probe=f4326ad956) | Sep 26, 2023 |
| HP            | Laptop 14-ck0xxx            | [3ff273b73c](https://linux-hardware.org/?probe=3ff273b73c) | Sep 26, 2023 |
| ASUSTek       | X451MA                      | [ed779c5de4](https://linux-hardware.org/?probe=ed779c5de4) | Sep 20, 2023 |
| Mini PC       | Cherry Trail CR             | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| Dell          | Precision 3570              | [fd3441ff1d](https://linux-hardware.org/?probe=fd3441ff1d) | Sep 18, 2023 |
| HP            | 15                          | [03e1207549](https://linux-hardware.org/?probe=03e1207549) | Sep 12, 2023 |
| HP            | 2000                        | [48790bd831](https://linux-hardware.org/?probe=48790bd831) | Sep 09, 2023 |
| HP            | 2000                        | [ce9ba2b7c4](https://linux-hardware.org/?probe=ce9ba2b7c4) | Sep 09, 2023 |
| eMachines     | eM350                       | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Dell          | Latitude 3190               | [60f82737fa](https://linux-hardware.org/?probe=60f82737fa) | Sep 06, 2023 |
| HP            | 255 G2                      | [27b48aa011](https://linux-hardware.org/?probe=27b48aa011) | Sep 02, 2023 |
| ASUSTek       | X75VD                       | [cab1480dc6](https://linux-hardware.org/?probe=cab1480dc6) | Aug 30, 2023 |
| Packard Be... | EasyNote TJ65               | [f37ab96772](https://linux-hardware.org/?probe=f37ab96772) | Aug 28, 2023 |
| Toshiba       | Satellite P770              | [8618c83c93](https://linux-hardware.org/?probe=8618c83c93) | Aug 26, 2023 |
| Google        | Robo                        | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| Compal        | PBL20                       | [ae09076b4e](https://linux-hardware.org/?probe=ae09076b4e) | Aug 22, 2023 |
| HP            | Notebook                    | [11d2993965](https://linux-hardware.org/?probe=11d2993965) | Aug 20, 2023 |
| Google        | Madoo                       | [8eea1017dc](https://linux-hardware.org/?probe=8eea1017dc) | Aug 20, 2023 |
| HP            | Notebook                    | [f6e4865586](https://linux-hardware.org/?probe=f6e4865586) | Aug 19, 2023 |
| Lenovo        | ThinkPad T430 2349TFK       | [390899a281](https://linux-hardware.org/?probe=390899a281) | Aug 17, 2023 |
| HP            | Pavilion g7                 | [43351d6476](https://linux-hardware.org/?probe=43351d6476) | Aug 12, 2023 |
| Samsung       | N150P/N210P/N220P           | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| Toshiba       | Satellite L875D             | [de1a418102](https://linux-hardware.org/?probe=de1a418102) | Aug 08, 2023 |
| Dell          | Inspiron 5720               | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| HP            | Pavilion 15                 | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| Lenovo        | G580 20150                  | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Dell          | Inspiron 1520               | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| Dell          | Inspiron 5576               | [54c338bb01](https://linux-hardware.org/?probe=54c338bb01) | Jul 22, 2023 |
| Dell          | Inspiron 5576               | [6654328e2c](https://linux-hardware.org/?probe=6654328e2c) | Jul 22, 2023 |
| Acer          | Aspire SW3-013              | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| HP            | 255 G2                      | [eaf9befa3a](https://linux-hardware.org/?probe=eaf9befa3a) | Jul 19, 2023 |
| Dell          | Inspiron N5110              | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| HP            | ProBook 4525s               | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| Google        | Pyro                        | [9632e7a77b](https://linux-hardware.org/?probe=9632e7a77b) | Jul 02, 2023 |
| Lenovo        | Z70-80 80FG                 | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| Sony          | VPCEB37FD                   | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| HP            | EliteBook 840 G3            | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Dell          | Vostro 3700                 | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
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
| Google        | Snappy                      | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0145d107e8](https://linux-hardware.org/?probe=0145d107e8) | May 15, 2023 |
| Intel         | W7650                       | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Toshiba       | Satellite Radius P55W-B     | [e2ed5e2135](https://linux-hardware.org/?probe=e2ed5e2135) | May 11, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0b08b7a631](https://linux-hardware.org/?probe=0b08b7a631) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| Dell          | XPS 13 9305                 | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| Apple         | MacBook4,1                  | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Latitude E6520              | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| Google        | Glimmer                     | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| HP            | Laptop 15-bs2xx             | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Toshiba       | Satellite C660              | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| Dell          | Latitude 5290               | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| GPU Compan... | GWTN116-3                   | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| Toshiba       | Satellite P70-A             | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| HP            | Pavilion 15                 | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| HP            | Laptop 17-ak0xx             | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| Dell          | Latitude 5290               | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| Dell          | Latitude 7480               | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| MSI           | S12T 3M/S12 3M              | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| Dell          | Latitude E6230              | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| Intel         | W7650                       | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Google        | Celes                       | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Getac         | V200-X                      | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| HP            | Pavilion 17                 | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Positivo      | Q232A                       | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| HP            | Notebook                    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Getac         | V200-X                      | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| Acer          | Extensa 2540                | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| Acer          | Aspire A515-45              | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Acer          | AO756                       | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| Dell          | Latitude E6410              | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Toshiba       | Satellite Pro S500          | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| Acer          | Aspire ES1-711              | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| ASUSTek       | F50SV                       | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Google        | Celes                       | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Acer          | Aspire SW3-013              | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| Google        | Candy                       | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Acer          | Aspire SW3-013              | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Acer          | Swift SF314-54G             | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| Dell          | Latitude E7470              | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| HP            | 2000                        | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| Apple         | MacBookPro8,1               | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Toshiba       | Satellite Pro S500          | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| GPU Compan... | GWTC116-2                   | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| ASUSTek       | K70IO                       | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| ASUSTek       | K70IO                       | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Unknown       | Unknown                     | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| HP            | Pavilion g6                 | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| HP            | Pavilion g6                 | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Toshiba       | Satellite Pro S500          | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| Lenovo        | G50-45 80E3                 | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| Acer          | Aspire E1-571               | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Lenovo        | G50-70 20351                | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Fujitsu       | LIFEBOOK U904               | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Packard Be... | EasyNote TS44HR             | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Gateway       | NE46R                       | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| Dell          | Inspiron 11-3168            | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Lenovo        | B590 20208                  | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
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
| Google        | Celes                       | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Sony          | VPCEB15FM                   | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| HP            | 245 G2                      | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Lenovo        | G50-30 80G0                 | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Gateway       | Sonic-C                     | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Dell          | Latitude XT                 | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| Intel         | W7650                       | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| HP            | Pavilion g6                 | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Acer          | Aspire V5-573G              | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Google        | Bobba360                    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Dell          | Latitude 7480               | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| Intel         | W7650                       | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Intel         | W7650                       | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-43-generic | 23        | 8.33%   |
| 5.15.0-56-generic | 14        | 5.07%   |
| 5.15.0-25-generic | 12        | 4.35%   |
| 6.2.0-34-generic  | 9         | 3.26%   |
| 6.2.0-26-generic  | 9         | 3.26%   |
| 5.15.0-58-generic | 9         | 3.26%   |
| 6.2.0-39-generic  | 8         | 2.9%    |
| 5.19.0-32-generic | 8         | 2.9%    |
| 5.15.0-60-generic | 8         | 2.9%    |
| 5.15.0-30-generic | 8         | 2.9%    |
| 5.19.0-41-generic | 7         | 2.54%   |
| 5.15.0-47-generic | 7         | 2.54%   |
| 5.15.0-46-generic | 7         | 2.54%   |
| 5.19.0-35-generic | 6         | 2.17%   |
| 5.15.0-52-generic | 6         | 2.17%   |
| 5.15.0-27-generic | 6         | 2.17%   |
| 6.2.0-37-generic  | 5         | 1.81%   |
| 5.19.0-43-generic | 5         | 1.81%   |
| 5.15.0-53-generic | 5         | 1.81%   |
| 6.2.0-36-generic  | 4         | 1.45%   |
| 6.2.0-33-generic  | 4         | 1.45%   |
| 5.19.0-46-generic | 4         | 1.45%   |
| 5.19.0-40-generic | 4         | 1.45%   |
| 5.19.0-38-generic | 4         | 1.45%   |
| 5.15.0-73-generic | 4         | 1.45%   |
| 5.15.0-71-generic | 4         | 1.45%   |
| 5.15.0-57-generic | 4         | 1.45%   |
| 5.15.0-50-generic | 4         | 1.45%   |
| 5.15.0-41-generic | 4         | 1.45%   |
| 6.2.0-35-generic  | 3         | 1.09%   |
| 6.2.0-31-generic  | 3         | 1.09%   |
| 5.19.0-42-generic | 3         | 1.09%   |
| 5.15.0-91-generic | 3         | 1.09%   |
| 5.15.0-79-generic | 3         | 1.09%   |
| 5.15.0-67-generic | 3         | 1.09%   |
| 5.15.0-48-generic | 3         | 1.09%   |
| 5.15.0-40-generic | 3         | 1.09%   |
| 5.15.0-35-generic | 3         | 1.09%   |
| 6.5.0-15-generic  | 2         | 0.72%   |
| 5.19.0-50-generic | 2         | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 154       | 59.46%  |
| 6.2.0   | 47        | 18.15%  |
| 5.19.0  | 47        | 18.15%  |
| 6.5.0   | 4         | 1.54%   |
| 6.4.12  | 1         | 0.39%   |
| 6.1.12  | 1         | 0.39%   |
| 6.0.12  | 1         | 0.39%   |
| 5.4.0   | 1         | 0.39%   |
| 5.19.8  | 1         | 0.39%   |
| 5.18.0  | 1         | 0.39%   |
| 5.14.0  | 1         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 154       | 59.46%  |
| 5.19    | 48        | 18.53%  |
| 6.2     | 47        | 18.15%  |
| 6.5     | 4         | 1.54%   |
| 6.4     | 1         | 0.39%   |
| 6.1     | 1         | 0.39%   |
| 6.0     | 1         | 0.39%   |
| 5.4     | 1         | 0.39%   |
| 5.18    | 1         | 0.39%   |
| 5.14    | 1         | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 254       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXQt       | 246       | 96.85%  |
| LXDE       | 5         | 1.97%   |
| X-Cinnamon | 2         | 0.79%   |
| KDE5       | 1         | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 248       | 97.64%  |
| Tty     | 5         | 1.97%   |
| Wayland | 1         | 0.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 222       | 86.72%  |
| Unknown | 18        | 7.03%   |
| LightDM | 11        | 4.3%    |
| GDM3    | 5         | 1.95%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Notebooks | Percent |
|--------|-----------|---------|
| en_US  | 79        | 30.98%  |
| fr_FR  | 27        | 10.59%  |
| it_IT  | 17        | 6.67%   |
| en_GB  | 17        | 6.67%   |
| C      | 16        | 6.27%   |
| de_DE  | 13        | 5.1%    |
| ru_RU  | 9         | 3.53%   |
| pt_BR  | 9         | 3.53%   |
| pl_PL  | 8         | 3.14%   |
| en_AG  | 8         | 3.14%   |
| es_MX  | 6         | 2.35%   |
| en_CA  | 6         | 2.35%   |
| en_AU  | 4         | 1.57%   |
| nl_BE  | 3         | 1.18%   |
| es_CO  | 3         | 1.18%   |
| es_CL  | 3         | 1.18%   |
| tr_TR  | 2         | 0.78%   |
| sk_SK  | 2         | 0.78%   |
| es_ES  | 2         | 0.78%   |
| es_CR  | 2         | 0.78%   |
| es_AR  | 2         | 0.78%   |
| en_PH  | 2         | 0.78%   |
| vi_VN  | 1         | 0.39%   |
| ro_RO  | 1         | 0.39%   |
| nl_NL  | 1         | 0.39%   |
| lzh_TW | 1         | 0.39%   |
| ja_JP  | 1         | 0.39%   |
| hu_HU  | 1         | 0.39%   |
| fr_CA  | 1         | 0.39%   |
| fi_FI  | 1         | 0.39%   |
| es_EC  | 1         | 0.39%   |
| en_ZA  | 1         | 0.39%   |
| en_DE  | 1         | 0.39%   |
| el_GR  | 1         | 0.39%   |
| de_CH  | 1         | 0.39%   |
| da_DK  | 1         | 0.39%   |
| aa_DJ  | 1         | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 153       | 60%     |
| EFI  | 102       | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 210       | 81.4%   |
| Tmpfs   | 26        | 10.08%  |
| Overlay | 18        | 6.98%   |
| Btrfs   | 2         | 0.78%   |
| Xfs     | 1         | 0.39%   |
| Ext2    | 1         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 143       | 55.64%  |
| MBR     | 75        | 29.18%  |
| Unknown | 39        | 15.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 232       | 90.63%  |
| Yes       | 24        | 9.38%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 188       | 73.44%  |
| Yes       | 68        | 26.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 49        | 19.29%  |
| Hewlett-Packard     | 42        | 16.54%  |
| Dell                | 27        | 10.63%  |
| Acer                | 26        | 10.24%  |
| ASUSTek Computer    | 19        | 7.48%   |
| Google              | 13        | 5.12%   |
| Apple               | 8         | 3.15%   |
| Toshiba             | 7         | 2.76%   |
| Unknown             | 5         | 1.97%   |
| Sony                | 4         | 1.57%   |
| Packard Bell        | 4         | 1.57%   |
| Mediacom            | 4         | 1.57%   |
| Fujitsu             | 4         | 1.57%   |
| Samsung Electronics | 3         | 1.18%   |
| Chuwi               | 3         | 1.18%   |
| Thomson             | 2         | 0.79%   |
| SGIN                | 2         | 0.79%   |
| Positivo            | 2         | 0.79%   |
| MSI                 | 2         | 0.79%   |
| Intel               | 2         | 0.79%   |
| HUAWEI              | 2         | 0.79%   |
| Hampoo              | 2         | 0.79%   |
| GPU Company         | 2         | 0.79%   |
| Getac               | 2         | 0.79%   |
| Gateway             | 2         | 0.79%   |
| TrekStor            | 1         | 0.39%   |
| Pretech             | 1         | 0.39%   |
| Prestigio           | 1         | 0.39%   |
| Panasonic           | 1         | 0.39%   |
| OEM                 | 1         | 0.39%   |
| Mini PC             | 1         | 0.39%   |
| Kiano               | 1         | 0.39%   |
| Insyde              | 1         | 0.39%   |
| IFSA                | 1         | 0.39%   |
| Fujitsu Siemens     | 1         | 0.39%   |
| eMachines           | 1         | 0.39%   |
| Dixonsxp            | 1         | 0.39%   |
| Digibras            | 1         | 0.39%   |
| Compal              | 1         | 0.39%   |
| AXIOO               | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 2.76%   |
| HP Notebook                                | 4         | 1.57%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 3         | 1.18%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 3         | 1.18%   |
| HP Pavilion 15                             | 3         | 1.18%   |
| Apple MacBookPro8,1                        | 3         | 1.18%   |
| Lenovo G50-30 80G0                         | 2         | 0.79%   |
| HP Pavilion g6                             | 2         | 0.79%   |
| HP 255 G2                                  | 2         | 0.79%   |
| HP 2000                                    | 2         | 0.79%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 0.79%   |
| Apple MacBook4,1                           | 2         | 0.79%   |
| Acer Aspire SW3-013                        | 2         | 0.79%   |
| Acer Aspire A314-23P                       | 2         | 0.79%   |
| TrekStor SurfTab wintron 7.0 ST70416-6     | 1         | 0.39%   |
| Toshiba Satellite Radius P55W-B            | 1         | 0.39%   |
| Toshiba Satellite Pro S500                 | 1         | 0.39%   |
| Toshiba Satellite P770                     | 1         | 0.39%   |
| Toshiba Satellite P70-A                    | 1         | 0.39%   |
| Toshiba Satellite L875D                    | 1         | 0.39%   |
| Toshiba Satellite L40                      | 1         | 0.39%   |
| Toshiba Satellite C660                     | 1         | 0.39%   |
| Thomson NEO14-4W64                         | 1         | 0.39%   |
| Thomson N14C4WH64                          | 1         | 0.39%   |
| Sony VPCEH2E1R                             | 1         | 0.39%   |
| Sony VPCEB15FM                             | 1         | 0.39%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.39%   |
| Sony SVE14A2V1EW                           | 1         | 0.39%   |
| SGIN M15                                   | 1         | 0.39%   |
| SGIN laptop                                | 1         | 0.39%   |
| Samsung N150P/N210P/N220P                  | 1         | 0.39%   |
| Samsung N150/N210/N220                     | 1         | 0.39%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.39%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.39%   |
| Prestigio PSB141C01BFH                     | 1         | 0.39%   |
| Positivo Q232A                             | 1         | 0.39%   |
| Positivo i500pro                           | 1         | 0.39%   |
| Panasonic CF-F9KWPZFFE                     | 1         | 0.39%   |
| Packard Bell ENLE11BZ                      | 1         | 0.39%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 18        | 7.09%   |
| Lenovo IdeaPad        | 18        | 7.09%   |
| Acer Aspire           | 18        | 7.09%   |
| Dell Latitude         | 10        | 3.94%   |
| HP Pavilion           | 9         | 3.54%   |
| Toshiba Satellite     | 7         | 2.76%   |
| Unknown               | 7         | 2.76%   |
| Dell Inspiron         | 6         | 2.36%   |
| HP Laptop             | 5         | 1.97%   |
| HP ProBook            | 4         | 1.57%   |
| HP Notebook           | 4         | 1.57%   |
| Fujitsu LIFEBOOK      | 4         | 1.57%   |
| Dell XPS              | 4         | 1.57%   |
| Packard Bell EasyNote | 3         | 1.18%   |
| Mediacom WinPad       | 3         | 1.18%   |
| HP EliteBook          | 3         | 1.18%   |
| Dell Precision        | 3         | 1.18%   |
| Apple MacBookPro8     | 3         | 1.18%   |
| Acer Extensa          | 3         | 1.18%   |
| Lenovo G50-30         | 2         | 0.79%   |
| HP ZBook              | 2         | 0.79%   |
| HP Compaq             | 2         | 0.79%   |
| HP 255                | 2         | 0.79%   |
| HP 250                | 2         | 0.79%   |
| HP 240                | 2         | 0.79%   |
| HP 2000               | 2         | 0.79%   |
| HP 15                 | 2         | 0.79%   |
| Dell Vostro           | 2         | 0.79%   |
| Chuwi GemiBook        | 2         | 0.79%   |
| ASUS VivoBook         | 2         | 0.79%   |
| Apple MacBook4        | 2         | 0.79%   |
| Acer Swift            | 2         | 0.79%   |
| TrekStor SurfTab      | 1         | 0.39%   |
| Thomson NEO14-4W64    | 1         | 0.39%   |
| Thomson N14C4WH64     | 1         | 0.39%   |
| Sony VPCEH2E1R        | 1         | 0.39%   |
| Sony VPCEB15FM        | 1         | 0.39%   |
| Sony VGN-SZ71WN       | 1         | 0.39%   |
| Sony SVE14A2V1EW      | 1         | 0.39%   |
| SGIN M15              | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 27        | 10.63%  |
| 2011    | 26        | 10.24%  |
| 2012    | 24        | 9.45%   |
| 2016    | 19        | 7.48%   |
| 2021    | 18        | 7.09%   |
| 2015    | 17        | 6.69%   |
| 2010    | 17        | 6.69%   |
| 2022    | 16        | 6.3%    |
| 2014    | 15        | 5.91%   |
| 2019    | 12        | 4.72%   |
| 2008    | 11        | 4.33%   |
| 2017    | 10        | 3.94%   |
| 2009    | 10        | 3.94%   |
| 2023    | 8         | 3.15%   |
| 2020    | 8         | 3.15%   |
| 2007    | 8         | 3.15%   |
| 2018    | 6         | 2.36%   |
| 2006    | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 254       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 239       | 93%     |
| Enabled  | 18        | 7%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 240       | 94.49%  |
| Yes  | 14        | 5.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 95        | 37.11%  |
| 4.01-8.0    | 66        | 25.78%  |
| 1.01-2.0    | 36        | 14.06%  |
| 8.01-16.0   | 25        | 9.77%   |
| 16.01-24.0  | 17        | 6.64%   |
| 2.01-3.0    | 9         | 3.52%   |
| 32.01-64.0  | 5         | 1.95%   |
| 24.01-32.0  | 1         | 0.39%   |
| 64.01-256.0 | 1         | 0.39%   |
| 0.51-1.0    | 1         | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 129       | 48.5%   |
| 2.01-3.0  | 57        | 21.43%  |
| 0.51-1.0  | 55        | 20.68%  |
| 4.01-8.0  | 11        | 4.14%   |
| 3.01-4.0  | 11        | 4.14%   |
| 0.01-0.5  | 2         | 0.75%   |
| 8.01-16.0 | 1         | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 207       | 80.54%  |
| 2      | 41        | 15.95%  |
| 3      | 7         | 2.72%   |
| 0      | 2         | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 140       | 55.12%  |
| Yes       | 114       | 44.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 194       | 76.08%  |
| No        | 61        | 23.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 232       | 91.34%  |
| No        | 22        | 8.66%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 168       | 65.37%  |
| No        | 89        | 34.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 41        | 16.14%  |
| France       | 28        | 11.02%  |
| Italy        | 22        | 8.66%   |
| Germany      | 22        | 8.66%   |
| Russia       | 15        | 5.91%   |
| UK           | 10        | 3.94%   |
| Poland       | 10        | 3.94%   |
| Brazil       | 9         | 3.54%   |
| Canada       | 8         | 3.15%   |
| Belgium      | 5         | 1.97%   |
| Ukraine      | 4         | 1.57%   |
| Netherlands  | 4         | 1.57%   |
| Mexico       | 4         | 1.57%   |
| Indonesia    | 4         | 1.57%   |
| Vietnam      | 3         | 1.18%   |
| Turkey       | 3         | 1.18%   |
| Slovakia     | 3         | 1.18%   |
| Hungary      | 3         | 1.18%   |
| Costa Rica   | 3         | 1.18%   |
| Colombia     | 3         | 1.18%   |
| Chile        | 3         | 1.18%   |
| Australia    | 3         | 1.18%   |
| Argentina    | 3         | 1.18%   |
| UAE          | 2         | 0.79%   |
| Sweden       | 2         | 0.79%   |
| Spain        | 2         | 0.79%   |
| South Africa | 2         | 0.79%   |
| Portugal     | 2         | 0.79%   |
| Philippines  | 2         | 0.79%   |
| Pakistan     | 2         | 0.79%   |
| Japan        | 2         | 0.79%   |
| Finland      | 2         | 0.79%   |
| Czechia      | 2         | 0.79%   |
| Thailand     | 1         | 0.39%   |
| Taiwan       | 1         | 0.39%   |
| Switzerland  | 1         | 0.39%   |
| Romania      | 1         | 0.39%   |
| Peru         | 1         | 0.39%   |
| Morocco      | 1         | 0.39%   |
| Malaysia     | 1         | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Paris                  | 8         | 3.04%   |
| Moscow                 | 4         | 1.52%   |
| Milan                  | 4         | 1.52%   |
| Bruhl                  | 4         | 1.52%   |
| Santiago               | 3         | 1.14%   |
| Kyiv                   | 3         | 1.14%   |
| Ghent                  | 3         | 1.14%   |
| Sarospatak             | 2         | 0.76%   |
| Rome                   | 2         | 0.76%   |
| Porto Alegre           | 2         | 0.76%   |
| Munich                 | 2         | 0.76%   |
| Milano                 | 2         | 0.76%   |
| Lyon                   | 2         | 0.76%   |
| Lansing                | 2         | 0.76%   |
| Ho Chi Minh City       | 2         | 0.76%   |
| Heredia                | 2         | 0.76%   |
| Eugene                 | 2         | 0.76%   |
| Dubai                  | 2         | 0.76%   |
| Columbus               | 2         | 0.76%   |
| Bratislava             | 2         | 0.76%   |
| Bogotá                | 2         | 0.76%   |
| Zizur Mayor            | 1         | 0.38%   |
| Zawiercie              | 1         | 0.38%   |
| Zagreb                 | 1         | 0.38%   |
| Yoshkar-Ola            | 1         | 0.38%   |
| Yorkville              | 1         | 0.38%   |
| Yerevan                | 1         | 0.38%   |
| Yekaterinburg          | 1         | 0.38%   |
| Wolfhagen              | 1         | 0.38%   |
| West Stockbridge       | 1         | 0.38%   |
| Wattignies-la-Victoire | 1         | 0.38%   |
| Warsaw                 | 1         | 0.38%   |
| Warren                 | 1         | 0.38%   |
| Warendorf              | 1         | 0.38%   |
| Waipahu                | 1         | 0.38%   |
| Vrbov                  | 1         | 0.38%   |
| Volzhskiy              | 1         | 0.38%   |
| Vesilahti              | 1         | 0.38%   |
| Verona                 | 1         | 0.38%   |
| Valenciennes           | 1         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Unknown                   | 46        | 64     | 16.2%   |
| WDC                       | 38        | 43     | 13.38%  |
| Seagate                   | 30        | 34     | 10.56%  |
| Samsung Electronics       | 25        | 35     | 8.8%    |
| Toshiba                   | 20        | 21     | 7.04%   |
| Hitachi                   | 13        | 17     | 4.58%   |
| Kingston                  | 12        | 12     | 4.23%   |
| SanDisk                   | 10        | 10     | 3.52%   |
| SK hynix                  | 8         | 8      | 2.82%   |
| Micron Technology         | 8         | 9      | 2.82%   |
| HGST                      | 6         | 7      | 2.11%   |
| Unknown                   | 6         | 6      | 2.11%   |
| Crucial                   | 5         | 5      | 1.76%   |
| Transcend                 | 4         | 5      | 1.41%   |
| A-DATA Technology         | 4         | 4      | 1.41%   |
| SPCC                      | 3         | 4      | 1.06%   |
| Intel                     | 3         | 3      | 1.06%   |
| China                     | 3         | 3      | 1.06%   |
| UMIS                      | 2         | 2      | 0.7%    |
| Silicon Motion            | 2         | 2      | 0.7%    |
| Patriot                   | 2         | 2      | 0.7%    |
| NGFF                      | 2         | 2      | 0.7%    |
| LITEON                    | 2         | 2      | 0.7%    |
| GOODRAM                   | 2         | 2      | 0.7%    |
| Fujitsu                   | 2         | 2      | 0.7%    |
| Apacer                    | 2         | 2      | 0.7%    |
| W800S                     | 1         | 1      | 0.35%   |
| USB3.0                    | 1         | 1      | 0.35%   |
| Teclast                   | 1         | 1      | 0.35%   |
| Rogueware                 | 1         | 1      | 0.35%   |
| PNY                       | 1         | 1      | 0.35%   |
| Plextor                   | 1         | 1      | 0.35%   |
| Phison                    | 1         | 1      | 0.35%   |
| Netac                     | 1         | 1      | 0.35%   |
| Neo Forza                 | 1         | 1      | 0.35%   |
| MidasForce                | 1         | 1      | 0.35%   |
| Micron/Crucial Technology | 1         | 1      | 0.35%   |
| Lexar                     | 1         | 1      | 0.35%   |
| Leqixiang                 | 1         | 1      | 0.35%   |
| Lenovo                    | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 8         | 2.67%   |
| Unknown MMC Card  32GB             | 7         | 2.33%   |
| Unknown                            | 6         | 2%      |
| Unknown NCard  32GB                | 5         | 1.67%   |
| Seagate ST9500325AS 500GB          | 5         | 1.67%   |
| SanDisk DF4032  32GB               | 5         | 1.67%   |
| Unknown SD/MMC/MS PRO 256GB        | 4         | 1.33%   |
| Unknown DA4032  32GB               | 4         | 1.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 1.33%   |
| Micron 2450_MTFDKBA512TFK 512GB    | 4         | 1.33%   |
| Kingston SA400S37240G 240GB SSD    | 4         | 1.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 3         | 1%      |
| Unknown MMC Card  16GB             | 3         | 1%      |
| Toshiba MQ01ABF050 500GB           | 3         | 1%      |
| Toshiba MQ01ABD050 500GB           | 3         | 1%      |
| Seagate ST500LT012-1DG142 500GB    | 3         | 1%      |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.67%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 2         | 0.67%   |
| WDC WD10SPZX-24Z10 1TB             | 2         | 0.67%   |
| Unknown SC64G  64GB                | 2         | 0.67%   |
| Unknown SC256  256GB               | 2         | 0.67%   |
| Unknown MMC64G  64GB               | 2         | 0.67%   |
| Unknown DA4064  64GB               | 2         | 0.67%   |
| Toshiba MQ01ABD075 752GB           | 2         | 0.67%   |
| SPCC Solid State Disk 120GB        | 2         | 0.67%   |
| SK hynix HFM001TD3JX013N 1024GB    | 2         | 0.67%   |
| SK hynix HBG4e  32GB               | 2         | 0.67%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 0.67%   |
| Seagate ST1000LM048-2E7172 1TB     | 2         | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.67%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.67%   |
| Samsung HM160HI 160GB              | 2         | 0.67%   |
| Samsung HM121HI 120GB              | 2         | 0.67%   |
| Kingston SV300S37A120G 120GB SSD   | 2         | 0.67%   |
| HGST HTS545050A7E680 500GB         | 2         | 0.67%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.33%   |
| WDC WDS500G2B0A 500GB SSD          | 1         | 0.33%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 0.33%   |
| WDC WDS250G2B0A 250GB SSD          | 1         | 0.33%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 32     | 28.44%  |
| Seagate             | 30        | 34     | 27.52%  |
| Toshiba             | 17        | 18     | 15.6%   |
| Hitachi             | 13        | 17     | 11.93%  |
| Samsung Electronics | 6         | 11     | 5.5%    |
| HGST                | 6         | 7      | 5.5%    |
| Unknown             | 4         | 4      | 3.67%   |
| Fujitsu             | 2         | 2      | 1.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 14     | 14.94%  |
| Kingston            | 10        | 10     | 11.49%  |
| WDC                 | 5         | 7      | 5.75%   |
| SanDisk             | 5         | 5      | 5.75%   |
| Transcend           | 4         | 5      | 4.6%    |
| Crucial             | 4         | 4      | 4.6%    |
| A-DATA Technology   | 4         | 4      | 4.6%    |
| Toshiba             | 3         | 3      | 3.45%   |
| SPCC                | 3         | 4      | 3.45%   |
| Intel               | 3         | 3      | 3.45%   |
| Patriot             | 2         | 2      | 2.3%    |
| NGFF                | 2         | 2      | 2.3%    |
| Micron Technology   | 2         | 2      | 2.3%    |
| LITEON              | 2         | 2      | 2.3%    |
| GOODRAM             | 2         | 2      | 2.3%    |
| Apacer              | 2         | 2      | 2.3%    |
| W800S               | 1         | 1      | 1.15%   |
| USB3.0              | 1         | 1      | 1.15%   |
| Teclast             | 1         | 1      | 1.15%   |
| Rogueware           | 1         | 1      | 1.15%   |
| PNY                 | 1         | 1      | 1.15%   |
| Plextor             | 1         | 1      | 1.15%   |
| Netac               | 1         | 1      | 1.15%   |
| Neo Forza           | 1         | 1      | 1.15%   |
| MidasForce          | 1         | 1      | 1.15%   |
| Lexar               | 1         | 1      | 1.15%   |
| Leqixiang           | 1         | 1      | 1.15%   |
| Lenovo              | 1         | 1      | 1.15%   |
| KingSpec            | 1         | 1      | 1.15%   |
| KINGPOWER           | 1         | 1      | 1.15%   |
| Kingmax             | 1         | 1      | 1.15%   |
| HUSKY               | 1         | 1      | 1.15%   |
| Hewlett-Packard     | 1         | 1      | 1.15%   |
| China               | 1         | 1      | 1.15%   |
| BHT                 | 1         | 1      | 1.15%   |
| AirDisk             | 1         | 1      | 1.15%   |
| Unknown             | 1         | 1      | 1.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 107       | 125    | 38.08%  |
| SSD     | 84        | 92     | 29.89%  |
| MMC     | 55        | 73     | 19.57%  |
| NVMe    | 31        | 37     | 11.03%  |
| Unknown | 4         | 5      | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 182       | 213    | 65.7%   |
| MMC  | 55        | 73     | 19.86%  |
| NVMe | 31        | 37     | 11.19%  |
| SAS  | 9         | 9      | 3.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 143       | 161    | 75.26%  |
| 0.51-1.0   | 43        | 52     | 22.63%  |
| 1.01-2.0   | 4         | 4      | 2.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 89        | 34.5%   |
| 251-500        | 65        | 25.19%  |
| 1-20           | 25        | 9.69%   |
| 501-1000       | 25        | 9.69%   |
| 51-100         | 25        | 9.69%   |
| 21-50          | 21        | 8.14%   |
| More than 3000 | 3         | 1.16%   |
| 1001-2000      | 2         | 0.78%   |
| Unknown        | 2         | 0.78%   |
| 2001-3000      | 1         | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 136       | 51.91%  |
| 21-50          | 57        | 21.76%  |
| 51-100         | 27        | 10.31%  |
| 101-250        | 21        | 8.02%   |
| 251-500        | 10        | 3.82%   |
| 501-1000       | 5         | 1.91%   |
| More than 3000 | 2         | 0.76%   |
| 1001-2000      | 2         | 0.76%   |
| Unknown        | 2         | 0.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 4      | 10.26%  |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 5.13%   |
| Seagate ST9500325AS 500GB          | 2         | 2      | 5.13%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 5.13%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 1      | 2.56%   |
| WDC WD5000BPVT-75HXZT1 500GB       | 1         | 1      | 2.56%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 2.56%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 2.56%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 2.56%   |
| WDC WD10SPCX-21KHST0 1TB           | 1         | 1      | 2.56%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 2.56%   |
| Transcend TS256GSSD720 256GB       | 1         | 1      | 2.56%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 2.56%   |
| Toshiba MK2556GSY 250GB            | 1         | 1      | 2.56%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 2.56%   |
| Seagate ST500LM021-1KJ152 500GB    | 1         | 1      | 2.56%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 2.56%   |
| Seagate ST320LT012-9WS14C 320GB    | 1         | 1      | 2.56%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1      | 2.56%   |
| Seagate ST1000DM003-1SB102 1TB     | 1         | 1      | 2.56%   |
| Samsung Electronics HM121HI 120GB  | 1         | 6      | 2.56%   |
| Plextor PX-128M6M 128GB SSD        | 1         | 1      | 2.56%   |
| NGFF 2280 512GB SSD                | 1         | 1      | 2.56%   |
| Kingmax SSD 120GB                  | 1         | 1      | 2.56%   |
| Intel SSDSC2KW512G8 512GB          | 1         | 1      | 2.56%   |
| Intel SSDSA2M080G2LE 80GB          | 1         | 1      | 2.56%   |
| Hitachi HTS722080K9SA00 80GB       | 1         | 1      | 2.56%   |
| Hitachi HTS545050B9A300 500GB      | 1         | 1      | 2.56%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 2.56%   |
| HGST HTS725032A7E630 320GB         | 1         | 1      | 2.56%   |
| Fujitsu MHY2120BH 120GB            | 1         | 1      | 2.56%   |
| Apacer 16GB SATA Flash Drive SSD   | 1         | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 38.46%  |
| WDC                 | 7         | 7      | 17.95%  |
| Toshiba             | 4         | 4      | 10.26%  |
| Hitachi             | 3         | 3      | 7.69%   |
| Intel               | 2         | 2      | 5.13%   |
| Transcend           | 1         | 1      | 2.56%   |
| Samsung Electronics | 1         | 6      | 2.56%   |
| Plextor             | 1         | 1      | 2.56%   |
| NGFF                | 1         | 1      | 2.56%   |
| Kingmax             | 1         | 1      | 2.56%   |
| HGST                | 1         | 1      | 2.56%   |
| Fujitsu             | 1         | 1      | 2.56%   |
| Apacer              | 1         | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 46.88%  |
| WDC                 | 7         | 7      | 21.88%  |
| Toshiba             | 4         | 4      | 12.5%   |
| Hitachi             | 3         | 3      | 9.38%   |
| Samsung Electronics | 1         | 6      | 3.13%   |
| HGST                | 1         | 1      | 3.13%   |
| Fujitsu             | 1         | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 37     | 82.05%  |
| SSD  | 7         | 7      | 17.95%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 138       | 182    | 51.49%  |
| Works    | 91        | 106    | 33.96%  |
| Malfunc  | 39        | 44     | 14.55%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 169       | 71.31%  |
| AMD                              | 33        | 13.92%  |
| Micron Technology                | 7         | 2.95%   |
| Samsung Electronics              | 6         | 2.53%   |
| SK hynix                         | 5         | 2.11%   |
| SanDisk                          | 3         | 1.27%   |
| Nvidia                           | 3         | 1.27%   |
| Union Memory (Shenzhen)          | 2         | 0.84%   |
| Silicon Motion                   | 2         | 0.84%   |
| Micron/Crucial Technology        | 2         | 0.84%   |
| Kingston Technology Company      | 2         | 0.84%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| Silicon Image                    | 1         | 0.42%   |
| Phison Electronics               | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 29        | 11.24%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 9.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 13        | 5.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 5.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 12        | 4.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 3.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 10        | 3.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 3.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 3.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 2.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 2.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 2.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 2.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 2.33%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 5         | 1.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.94%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 1.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 1.94%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 4         | 1.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.16%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 1.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.16%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.78%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 0.78%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 0.78%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2         | 0.78%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                            | 1         | 0.39%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                  | 1         | 0.39%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.39%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.39%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 190       | 75.7%   |
| NVMe | 30        | 11.95%  |
| IDE  | 22        | 8.76%   |
| RAID | 9         | 3.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 213       | 83.86%  |
| AMD    | 41        | 16.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 8         | 3.15%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 7         | 2.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 1.97%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 5         | 1.97%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 1.97%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 4         | 1.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.57%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 4         | 1.57%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 1.57%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 4         | 1.57%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 3         | 1.18%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 3         | 1.18%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.18%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.18%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.18%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 3         | 1.18%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 1.18%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 3         | 1.18%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.18%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 3         | 1.18%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 3         | 1.18%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.79%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 2         | 0.79%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.79%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.79%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 2         | 0.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.79%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.79%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 0.79%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.79%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.79%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 0.79%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.79%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 2         | 0.79%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.79%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz          | 2         | 0.79%   |
| Intel Celeron N4500 @ 1.10GHz                 | 2         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 51        | 20.08%  |
| Intel Core i5           | 46        | 18.11%  |
| Intel Core i7           | 25        | 9.84%   |
| Intel Atom              | 22        | 8.66%   |
| Intel Core i3           | 20        | 7.87%   |
| Intel Core 2 Duo        | 20        | 7.87%   |
| Intel Pentium           | 10        | 3.94%   |
| Other                   | 8         | 3.15%   |
| AMD A6                  | 7         | 2.76%   |
| AMD Ryzen 7             | 6         | 2.36%   |
| AMD E1                  | 5         | 1.97%   |
| AMD E2                  | 4         | 1.57%   |
| AMD E                   | 4         | 1.57%   |
| Intel Pentium Dual-Core | 3         | 1.18%   |
| Intel Pentium Dual      | 3         | 1.18%   |
| Intel Core 2            | 3         | 1.18%   |
| AMD Ryzen 5             | 3         | 1.18%   |
| AMD C-60                | 2         | 0.79%   |
| AMD A8                  | 2         | 0.79%   |
| AMD A4                  | 2         | 0.79%   |
| Intel Pentium Silver    | 1         | 0.39%   |
| Intel Genuine           | 1         | 0.39%   |
| Intel Celeron Dual-Core | 1         | 0.39%   |
| AMD Ryzen 9             | 1         | 0.39%   |
| AMD Ryzen 7 PRO         | 1         | 0.39%   |
| AMD Athlon II           | 1         | 0.39%   |
| AMD Athlon              | 1         | 0.39%   |
| AMD A10                 | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 165       | 64.96%  |
| 4      | 69        | 27.17%  |
| 8      | 8         | 3.15%   |
| 1      | 7         | 2.76%   |
| 10     | 3         | 1.18%   |
| 14     | 1         | 0.39%   |
| 6      | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 254       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 137       | 53.94%  |
| 2      | 117       | 46.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 254       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 115       | 44.92%  |
| 0x306a9    | 18        | 7.03%   |
| 0x206a7    | 11        | 4.3%    |
| 0x406c3    | 8         | 3.13%   |
| 0x706a8    | 6         | 2.34%   |
| 0x0700010f | 6         | 2.34%   |
| 0x05000119 | 6         | 2.34%   |
| 0x406c4    | 5         | 1.95%   |
| 0x30678    | 5         | 1.95%   |
| 0x20655    | 5         | 1.95%   |
| 0x1067a    | 5         | 1.95%   |
| 0x6fd      | 4         | 1.56%   |
| 0x40651    | 4         | 1.56%   |
| 0x0a50000c | 4         | 1.56%   |
| 0x806ec    | 3         | 1.17%   |
| 0x806ea    | 3         | 1.17%   |
| 0x706a1    | 3         | 1.17%   |
| 0x506c9    | 3         | 1.17%   |
| 0x406e3    | 3         | 1.17%   |
| 0x06006705 | 3         | 1.17%   |
| 0x906c0    | 2         | 0.78%   |
| 0x906a4    | 2         | 0.78%   |
| 0x806c1    | 2         | 0.78%   |
| 0x706e5    | 2         | 0.78%   |
| 0x306c3    | 2         | 0.78%   |
| 0x106ca    | 2         | 0.78%   |
| 0x08a00008 | 2         | 0.78%   |
| 0x06006704 | 2         | 0.78%   |
| 0x06001119 | 2         | 0.78%   |
| 0x906ed    | 1         | 0.39%   |
| 0x806eb    | 1         | 0.39%   |
| 0x806e9    | 1         | 0.39%   |
| 0x6fb      | 1         | 0.39%   |
| 0x6fa      | 1         | 0.39%   |
| 0x6f6      | 1         | 0.39%   |
| 0x506e3    | 1         | 0.39%   |
| 0x306d4    | 1         | 0.39%   |
| 0x20652    | 1         | 0.39%   |
| 0x10676    | 1         | 0.39%   |
| 0x0a50000d | 1         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Silvermont       | 41        | 16.14%  |
| IvyBridge        | 25        | 9.84%   |
| SandyBridge      | 21        | 8.27%   |
| Penryn           | 17        | 6.69%   |
| Goldmont plus    | 17        | 6.69%   |
| Haswell          | 15        | 5.91%   |
| Westmere         | 14        | 5.51%   |
| Core             | 14        | 5.51%   |
| KabyLake         | 12        | 4.72%   |
| Excavator        | 8         | 3.15%   |
| Skylake          | 7         | 2.76%   |
| Jaguar           | 7         | 2.76%   |
| Goldmont         | 7         | 2.76%   |
| Bobcat           | 7         | 2.76%   |
| Zen 3            | 6         | 2.36%   |
| Unknown          | 6         | 2.36%   |
| Broadwell        | 5         | 1.97%   |
| Bonnell          | 5         | 1.97%   |
| Piledriver       | 4         | 1.57%   |
| Alderlake Hybrid | 4         | 1.57%   |
| Tremont          | 3         | 1.18%   |
| IceLake          | 3         | 1.18%   |
| TigerLake        | 2         | 0.79%   |
| Puma             | 2         | 0.79%   |
| K10              | 1         | 0.39%   |
| Gracemont        | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 195       | 67.71%  |
| AMD    | 58        | 20.14%  |
| Nvidia | 35        | 12.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 8.2%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 8.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 6.89%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 5.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 5.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 3.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 3.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 3.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.62%   |
| Intel HD Graphics 500                                                                    | 7         | 2.3%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 2.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.64%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.64%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 1.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.31%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.31%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 3         | 0.98%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.98%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.98%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 0.98%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.98%   |
| AMD Mendocino                                                                            | 3         | 0.98%   |
| AMD Lucienne                                                                             | 3         | 0.98%   |
| AMD Kabini [Radeon HD 8210]                                                              | 3         | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.66%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 0.66%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.66%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.66%   |
| Intel HD Graphics 630                                                                    | 2         | 0.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.66%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 2         | 0.66%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.66%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 0.66%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 0.66%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 2         | 0.66%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 2         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 158       | 62.2%   |
| 1 x AMD        | 39        | 15.35%  |
| Intel + Nvidia | 20        | 7.87%   |
| 1 x Nvidia     | 13        | 5.12%   |
| Intel + AMD    | 11        | 4.33%   |
| 2 x AMD        | 6         | 2.36%   |
| Other          | 5         | 1.97%   |
| AMD + Nvidia   | 2         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 240       | 94.49%  |
| Proprietary | 10        | 3.94%   |
| Unknown     | 4         | 1.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 197       | 77.25%  |
| 0.01-0.5   | 32        | 12.55%  |
| 1.01-2.0   | 15        | 5.88%   |
| 0.51-1.0   | 7         | 2.75%   |
| 3.01-4.0   | 2         | 0.78%   |
| 5.01-6.0   | 1         | 0.39%   |
| 2.01-3.0   | 1         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 56        | 21.46%  |
| LG Display              | 46        | 17.62%  |
| BOE                     | 39        | 14.94%  |
| Chimei Innolux          | 28        | 10.73%  |
| Samsung Electronics     | 27        | 10.34%  |
| Apple                   | 9         | 3.45%   |
| Lenovo                  | 7         | 2.68%   |
| Sharp                   | 5         | 1.92%   |
| CPT                     | 5         | 1.92%   |
| Chi Mei Optoelectronics | 5         | 1.92%   |
| Toshiba                 | 4         | 1.53%   |
| Acer                    | 4         | 1.53%   |
| Hewlett-Packard         | 3         | 1.15%   |
| Goldstar                | 3         | 1.15%   |
| Dell                    | 3         | 1.15%   |
| LG Philips              | 2         | 0.77%   |
| InfoVision              | 2         | 0.77%   |
| ViewSonic               | 1         | 0.38%   |
| Panasonic               | 1         | 0.38%   |
| LLL                     | 1         | 0.38%   |
| JVC                     | 1         | 0.38%   |
| JDI                     | 1         | 0.38%   |
| Insignia                | 1         | 0.38%   |
| InnoLux Display         | 1         | 0.38%   |
| CS_                     | 1         | 0.38%   |
| CMN                     | 1         | 0.38%   |
| BenQ                    | 1         | 0.38%   |
| ASUSTek Computer        | 1         | 0.38%   |
| AOC                     | 1         | 0.38%   |
| Ancor Communications    | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 6         | 2.3%    |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch          | 4         | 1.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 4         | 1.53%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 3         | 1.15%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                 | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 3         | 1.15%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch | 2         | 0.77%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch | 2         | 0.77%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 2         | 0.77%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 2         | 0.77%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch              | 2         | 0.77%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 2         | 0.77%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                 | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 2         | 0.77%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                | 2         | 0.77%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.77%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                 | 2         | 0.77%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.77%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch        | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch        | 2         | 0.77%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 2         | 0.77%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch               | 2         | 0.77%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 2         | 0.77%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch        | 1         | 0.38%   |
| Toshiba TV TSB0212 3840x2160                                         | 1         | 0.38%   |
| Toshiba TV TSB0108 1920x540                                          | 1         | 0.38%   |
| Toshiba LCD Monitor LCD5860 1280x800 261x163mm 12.1-inch             | 1         | 0.38%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch             | 1         | 0.38%   |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch              | 1         | 0.38%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch              | 1         | 0.38%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch              | 1         | 0.38%   |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch              | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 121       | 47.27%  |
| 1920x1080 (FHD)    | 57        | 22.27%  |
| 1280x800 (WXGA)    | 26        | 10.16%  |
| 1600x900 (HD+)     | 21        | 8.2%    |
| 3840x2160 (4K)     | 7         | 2.73%   |
| 2560x1440 (QHD)    | 4         | 1.56%   |
| 1440x900 (WXGA+)   | 3         | 1.17%   |
| 3200x1800 (QHD+)   | 2         | 0.78%   |
| 2160x1440          | 2         | 0.78%   |
| 1920x1200 (WUXGA)  | 2         | 0.78%   |
| 1680x1050 (WSXGA+) | 2         | 0.78%   |
| 1024x600           | 2         | 0.78%   |
| 3000x2000          | 1         | 0.39%   |
| 2560x1080          | 1         | 0.39%   |
| 1920x540           | 1         | 0.39%   |
| 1528x1222          | 1         | 0.39%   |
| 1400x1050          | 1         | 0.39%   |
| 1360x768           | 1         | 0.39%   |
| 1280x1024 (SXGA)   | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 91        | 34.87%  |
| 14      | 41        | 15.71%  |
| 13      | 38        | 14.56%  |
| 11      | 22        | 8.43%   |
| 17      | 21        | 8.05%   |
| 12      | 12        | 4.6%    |
| 27      | 4         | 1.53%   |
| 24      | 4         | 1.53%   |
| 23      | 4         | 1.53%   |
| 10      | 4         | 1.53%   |
| 21      | 3         | 1.15%   |
| 19      | 3         | 1.15%   |
| 84      | 2         | 0.77%   |
| 72      | 2         | 0.77%   |
| 28      | 2         | 0.77%   |
| Unknown | 2         | 0.77%   |
| 54      | 1         | 0.38%   |
| 44      | 1         | 0.38%   |
| 22      | 1         | 0.38%   |
| 18      | 1         | 0.38%   |
| 16      | 1         | 0.38%   |
| 9       | 1         | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 149       | 57.31%  |
| 201-300     | 57        | 21.92%  |
| 351-400     | 24        | 9.23%   |
| 501-600     | 11        | 4.23%   |
| 401-500     | 7         | 2.69%   |
| 1501-2000   | 4         | 1.54%   |
| 601-700     | 3         | 1.15%   |
| Unknown     | 2         | 0.77%   |
| 101-200     | 1         | 0.38%   |
| 1001-1500   | 1         | 0.38%   |
| 901-1000    | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 199       | 82.57%  |
| 16/10   | 32        | 13.28%  |
| 3/2     | 5         | 2.07%   |
| 4/3     | 2         | 0.83%   |
| 5/4     | 1         | 0.41%   |
| 21/9    | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 91        | 34.87%  |
| 81-90          | 71        | 27.2%   |
| 51-60          | 22        | 8.43%   |
| 121-130        | 20        | 7.66%   |
| 61-70          | 12        | 4.6%    |
| 201-250        | 10        | 3.83%   |
| 71-80          | 7         | 2.68%   |
| More than 1000 | 5         | 1.92%   |
| 41-50          | 5         | 1.92%   |
| 301-350        | 4         | 1.53%   |
| 251-300        | 3         | 1.15%   |
| 151-200        | 3         | 1.15%   |
| 131-140        | 2         | 0.77%   |
| Unknown        | 2         | 0.77%   |
| 351-500        | 1         | 0.38%   |
| 141-150        | 1         | 0.38%   |
| 501-1000       | 1         | 0.38%   |
| 91-100         | 1         | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 126       | 49.03%  |
| 121-160       | 81        | 31.52%  |
| 51-100        | 31        | 12.06%  |
| 161-240       | 11        | 4.28%   |
| More than 240 | 3         | 1.17%   |
| 1-50          | 3         | 1.17%   |
| Unknown       | 2         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 226       | 88.63%  |
| 2     | 23        | 9.02%   |
| 0     | 5         | 1.96%   |
| 3     | 1         | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 123       | 32.28%  |
| Intel                             | 96        | 25.2%   |
| Qualcomm Atheros                  | 64        | 16.8%   |
| Broadcom                          | 32        | 8.4%    |
| Marvell Technology Group          | 9         | 2.36%   |
| MediaTek                          | 7         | 1.84%   |
| Samsung Electronics               | 6         | 1.57%   |
| Ralink                            | 6         | 1.57%   |
| Ralink Technology                 | 4         | 1.05%   |
| Broadcom Limited                  | 4         | 1.05%   |
| ASIX Electronics                  | 4         | 1.05%   |
| TP-Link                           | 3         | 0.79%   |
| OPPO Electronics                  | 3         | 0.79%   |
| Xiaomi                            | 2         | 0.52%   |
| Qualcomm Atheros Communications   | 2         | 0.52%   |
| Qualcomm                          | 2         | 0.52%   |
| Nvidia                            | 2         | 0.52%   |
| Spreadtrum Communications         | 1         | 0.26%   |
| Sierra Wireless                   | 1         | 0.26%   |
| NetGear                           | 1         | 0.26%   |
| Motorola PCS                      | 1         | 0.26%   |
| Microsoft                         | 1         | 0.26%   |
| Micro Star International          | 1         | 0.26%   |
| JMicron Technology                | 1         | 0.26%   |
| ICS Advent                        | 1         | 0.26%   |
| Ericsson Business Mobile Networks | 1         | 0.26%   |
| Dresden Elektronik                | 1         | 0.26%   |
| Dell                              | 1         | 0.26%   |
| ASUSTek Computer                  | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 53        | 11.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 34        | 7.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 13        | 2.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 11        | 2.38%   |
| Intel Wireless 7265                                                    | 11        | 2.38%   |
| Intel Wireless 7260                                                    | 11        | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 1.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 7         | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 1.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.3%    |
| Intel 82577LM Gigabit Network Connection                               | 6         | 1.3%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 5         | 1.08%   |
| Realtek 802.11n WLAN Adapter                                           | 5         | 1.08%   |
| Intel Wireless 8265 / 8275                                             | 5         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 5         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 5         | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.87%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 4         | 0.87%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 4         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 4         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 4         | 0.87%   |
| Intel Wireless 3165                                                    | 4         | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 4         | 0.87%   |
| Intel Centrino Wireless-N 2230                                         | 4         | 0.87%   |
| Intel Centrino Advanced-N 6200                                         | 4         | 0.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 3         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 3         | 0.65%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 3         | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.65%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 3         | 0.65%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 3         | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.65%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 3         | 0.65%   |
| Intel Wireless 3160                                                    | 3         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 90        | 36.29%  |
| Qualcomm Atheros                  | 56        | 22.58%  |
| Realtek Semiconductor             | 50        | 20.16%  |
| Broadcom                          | 22        | 8.87%   |
| MediaTek                          | 7         | 2.82%   |
| Ralink                            | 6         | 2.42%   |
| Ralink Technology                 | 4         | 1.61%   |
| TP-Link                           | 2         | 0.81%   |
| Qualcomm Atheros Communications   | 2         | 0.81%   |
| Broadcom Limited                  | 2         | 0.81%   |
| Sierra Wireless                   | 1         | 0.4%    |
| NetGear                           | 1         | 0.4%    |
| Microsoft                         | 1         | 0.4%    |
| Micro Star International          | 1         | 0.4%    |
| Ericsson Business Mobile Networks | 1         | 0.4%    |
| Dell                              | 1         | 0.4%    |
| ASUSTek Computer                  | 1         | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 13        | 5.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 4.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 4.4%    |
| Intel Wireless 7265                                            | 11        | 4.4%    |
| Intel Wireless 7260                                            | 11        | 4.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 3.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 2.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 2.4%    |
| Realtek 802.11n WLAN Adapter                                   | 5         | 2%      |
| Intel Wireless 8265 / 8275                                     | 5         | 2%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 5         | 2%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.6%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 4         | 1.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.6%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 1.6%    |
| Intel Wireless 3165                                            | 4         | 1.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 4         | 1.6%    |
| Intel Centrino Wireless-N 2230                                 | 4         | 1.6%    |
| Intel Centrino Advanced-N 6200                                 | 4         | 1.6%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.2%    |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 3         | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.2%    |
| Intel Wireless 3160                                            | 3         | 1.2%    |
| Intel Wi-Fi 6 AX200                                            | 3         | 1.2%    |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.2%    |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.2%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.2%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.2%    |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.8%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 0.8%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 101       | 48.1%   |
| Intel                     | 37        | 17.62%  |
| Qualcomm Atheros          | 21        | 10%     |
| Broadcom                  | 16        | 7.62%   |
| Marvell Technology Group  | 9         | 4.29%   |
| Samsung Electronics       | 6         | 2.86%   |
| ASIX Electronics          | 4         | 1.9%    |
| OPPO Electronics          | 3         | 1.43%   |
| Xiaomi                    | 2         | 0.95%   |
| Qualcomm                  | 2         | 0.95%   |
| Nvidia                    | 2         | 0.95%   |
| Broadcom Limited          | 2         | 0.95%   |
| TP-Link                   | 1         | 0.48%   |
| Spreadtrum Communications | 1         | 0.48%   |
| Motorola PCS              | 1         | 0.48%   |
| JMicron Technology        | 1         | 0.48%   |
| ICS Advent                | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 53        | 25.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 34        | 16.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 5.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 3.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 2.84%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 2.84%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5         | 2.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 1.9%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 1.9%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 3         | 1.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 1.42%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 3         | 1.42%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 3         | 1.42%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.42%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.42%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 1.42%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 1.42%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.95%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 0.95%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 0.95%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.95%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.95%   |
| Intel 82573L Gigabit Ethernet Controller                               | 2         | 0.95%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 2         | 0.95%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.95%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.47%   |
| Spreadtrum Unisoc Phone                                                | 1         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.47%   |
| Realtek RTL8150 Fast Ethernet Adapter                                  | 1         | 0.47%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.47%   |
| Qualcomm Redmi 9T                                                      | 1         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 0.47%   |
| Qualcomm Android                                                       | 1         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 233       | 54.44%  |
| Ethernet | 194       | 45.33%  |
| Modem    | 1         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 179       | 72.18%  |
| Ethernet | 69        | 27.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 165       | 64.96%  |
| 1     | 61        | 24.02%  |
| 0     | 26        | 10.24%  |
| 3     | 2         | 0.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 191       | 74.61%  |
| Yes  | 65        | 25.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 34.32%  |
| Realtek Semiconductor           | 26        | 15.38%  |
| Qualcomm Atheros Communications | 21        | 12.43%  |
| Broadcom                        | 12        | 7.1%    |
| Lite-On Technology              | 10        | 5.92%   |
| IMC Networks                    | 8         | 4.73%   |
| Apple                           | 7         | 4.14%   |
| Foxconn / Hon Hai               | 5         | 2.96%   |
| Ralink                          | 4         | 2.37%   |
| Hewlett-Packard                 | 4         | 2.37%   |
| Dell                            | 4         | 2.37%   |
| Cambridge Silicon Radio         | 3         | 1.78%   |
| Toshiba                         | 2         | 1.18%   |
| Alps Electric                   | 2         | 1.18%   |
| Syntek                          | 1         | 0.59%   |
| MediaTek                        | 1         | 0.59%   |
| ASUSTek Computer                | 1         | 0.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 36        | 21.18%  |
| Realtek Bluetooth Radio                                                             | 18        | 10.59%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 10        | 5.88%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 3.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 2.94%   |
| Intel AX201 Bluetooth                                                               | 5         | 2.94%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 2.94%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 2.35%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 2.35%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 2.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 2.35%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 2.35%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.35%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.76%   |
| Intel Bluetooth Device                                                              | 3         | 1.76%   |
| Intel AX200 Bluetooth                                                               | 3         | 1.76%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 1.76%   |
| Lite-On Wireless_Device                                                             | 2         | 1.18%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.18%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.18%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.18%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.18%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 1.18%   |
| Apple Bluetooth HCI                                                                 | 2         | 1.18%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.59%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.59%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 0.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.59%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.59%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.59%   |
| MediaTek Wireless_Device                                                            | 1         | 0.59%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.59%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.59%   |
| Lite-On BCM20702A0                                                                  | 1         | 0.59%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.59%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.59%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.59%   |
| IMC Networks Bluetooth                                                              | 1         | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 192       | 73.28%  |
| AMD                  | 45        | 17.18%  |
| Nvidia               | 19        | 7.25%   |
| MosArt Semiconductor | 1         | 0.38%   |
| JMTek                | 1         | 0.38%   |
| GN Netcom            | 1         | 0.38%   |
| EGO SYStems          | 1         | 0.38%   |
| C-Media Electronics  | 1         | 0.38%   |
| ASUSTek Computer     | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32        | 10.13%  |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 17        | 5.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 4.75%   |
| AMD FCH Azalia Controller                                                                         | 15        | 4.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 4.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 4.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 4.11%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 3.48%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 3.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 3.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 3.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 3.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2.85%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 2.53%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7         | 2.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 2.22%   |
| AMD High Definition Audio Controller                                                              | 7         | 2.22%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.58%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.58%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.27%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 1.27%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.95%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.95%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 0.95%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.63%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.63%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.63%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 47        | 23.86%  |
| SK hynix            | 44        | 22.34%  |
| Unknown             | 22        | 11.17%  |
| Micron Technology   | 21        | 10.66%  |
| Kingston            | 9         | 4.57%   |
| Unknown (ABCD)      | 8         | 4.06%   |
| Nanya Technology    | 7         | 3.55%   |
| Elpida              | 7         | 3.55%   |
| Smart               | 3         | 1.52%   |
| Ramaxel Technology  | 3         | 1.52%   |
| A-DATA Technology   | 3         | 1.52%   |
| Unknown             | 3         | 1.52%   |
| G.Skill             | 2         | 1.02%   |
| fef5                | 2         | 1.02%   |
| Crucial             | 2         | 1.02%   |
| Corsair             | 2         | 1.02%   |
| Wilk                | 1         | 0.51%   |
| Transcend           | 1         | 0.51%   |
| Toshiba             | 1         | 0.51%   |
| Teikon              | 1         | 0.51%   |
| TakeMS              | 1         | 0.51%   |
| PUSKILL             | 1         | 0.51%   |
| Novatech            | 1         | 0.51%   |
| Kllisre             | 1         | 0.51%   |
| Kingmax             | 1         | 0.51%   |
| HMD                 | 1         | 0.51%   |
| Apacer              | 1         | 0.51%   |
| AMD                 | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 7         | 3.32%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 2.37%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                         | 4         | 1.9%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 4         | 1.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 1.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 1.9%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 4         | 1.9%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 3         | 1.42%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 3         | 1.42%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.42%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 3         | 1.42%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s                | 3         | 1.42%   |
| Unknown                                                             | 3         | 1.42%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 2         | 0.95%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                        | 2         | 0.95%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                          | 2         | 0.95%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.95%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.95%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 2         | 0.95%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.95%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s          | 2         | 0.95%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 0.95%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.95%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.95%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.95%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                     | 2         | 0.95%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s             | 2         | 0.95%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s         | 2         | 0.95%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 2         | 0.95%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM 1067MT/s                   | 2         | 0.95%   |
| Elpida RAM EBJ20UF8BDU0-GN-F 2048MB SODIMM DDR3 1600MT/s            | 2         | 0.95%   |
| Wilk RAM GR3200S464L22S/8G 8GB SODIMM DDR4 3200MT/s                 | 1         | 0.47%   |
| Unknown RAM Module 512MB SODIMM DDR2                                | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                          | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                          | 1         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR2                                  | 1         | 0.47%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 89        | 51.45%  |
| DDR4    | 37        | 21.39%  |
| LPDDR4  | 17        | 9.83%   |
| DDR2    | 14        | 8.09%   |
| SDRAM   | 5         | 2.89%   |
| LPDDR5  | 5         | 2.89%   |
| LPDDR3  | 2         | 1.16%   |
| DDR5    | 2         | 1.16%   |
| Unknown | 2         | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 149       | 88.17%  |
| Row Of Chips | 12        | 7.1%    |
| Unknown      | 5         | 2.96%   |
| DIMM         | 3         | 1.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 62        | 32.8%   |
| 8192  | 54        | 28.57%  |
| 2048  | 50        | 26.46%  |
| 1024  | 13        | 6.88%   |
| 16384 | 7         | 3.7%    |
| 32768 | 2         | 1.06%   |
| 512   | 1         | 0.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 61        | 33.33%  |
| 2400    | 18        | 9.84%   |
| 3200    | 16        | 8.74%   |
| 1333    | 13        | 7.1%    |
| 1334    | 11        | 6.01%   |
| 667     | 11        | 6.01%   |
| 2667    | 8         | 4.37%   |
| 1066    | 7         | 3.83%   |
| 6400    | 4         | 2.19%   |
| 3266    | 4         | 2.19%   |
| 1067    | 4         | 2.19%   |
| 2048    | 3         | 1.64%   |
| 1866    | 3         | 1.64%   |
| Unknown | 3         | 1.64%   |
| 4800    | 2         | 1.09%   |
| 4267    | 2         | 1.09%   |
| 4266    | 2         | 1.09%   |
| 2133    | 2         | 1.09%   |
| 975     | 2         | 1.09%   |
| 800     | 2         | 1.09%   |
| 5500    | 1         | 0.55%   |
| 4199    | 1         | 0.55%   |
| 2933    | 1         | 0.55%   |
| 1867    | 1         | 0.55%   |
| 533     | 1         | 0.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| HP LaserJet P1102 | 1         | 50%     |
| Canon MF3110      | 1         | 50%     |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 57        | 27.8%   |
| Realtek Semiconductor                  | 21        | 10.24%  |
| Microdia                               | 20        | 9.76%   |
| Sunplus Innovation Technology          | 12        | 5.85%   |
| Syntek                                 | 11        | 5.37%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.9%    |
| Bison Electronics                      | 8         | 3.9%    |
| Alcor Micro                            | 8         | 3.9%    |
| Suyin                                  | 7         | 3.41%   |
| Quanta                                 | 7         | 3.41%   |
| IMC Networks                           | 7         | 3.41%   |
| Apple                                  | 7         | 3.41%   |
| Lite-On Technology                     | 5         | 2.44%   |
| ALi                                    | 4         | 1.95%   |
| Silicon Motion                         | 3         | 1.46%   |
| Lenovo                                 | 3         | 1.46%   |
| Z-Star Microelectronics                | 2         | 0.98%   |
| USB Camera CS                          | 2         | 0.98%   |
| USB Camera                             | 2         | 0.98%   |
| GEMBIRD                                | 2         | 0.98%   |
| Y Media                                | 1         | 0.49%   |
| SunplusIT                              | 1         | 0.49%   |
| Sonix Technology                       | 1         | 0.49%   |
| Ricoh                                  | 1         | 0.49%   |
| Luxvisions Innotech Limited            | 1         | 0.49%   |
| Logitech                               | 1         | 0.49%   |
| Cubeternet                             | 1         | 0.49%   |
| BKX-Usb2.0 2MP Camera                  | 1         | 0.49%   |
| Acer                                   | 1         | 0.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 10        | 4.85%   |
| Chicony HP TrueVision HD Camera                         | 6         | 2.91%   |
| Chicony HD WebCam                                       | 6         | 2.91%   |
| Alcor Micro USB 2.0 Camera                              | 6         | 2.91%   |
| Sunplus HD WebCam                                       | 5         | 2.43%   |
| Realtek Integrated_Webcam_HD                            | 4         | 1.94%   |
| Microdia Integrated Webcam                              | 4         | 1.94%   |
| Syntek USB Camera Device                                | 3         | 1.46%   |
| Syntek Lenovo EasyCamera                                | 3         | 1.46%   |
| Realtek USB Camera                                      | 3         | 1.46%   |
| Microdia Lenovo EasyCamera                              | 3         | 1.46%   |
| Microdia Integrated_Webcam_HD                           | 3         | 1.46%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 3         | 1.46%   |
| Chicony VGA WebCam                                      | 3         | 1.46%   |
| Chicony HP Truevision HD                                | 3         | 1.46%   |
| Chicony EasyCamera                                      | 3         | 1.46%   |
| Chicony ACER HD User Facing                             | 3         | 1.46%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 3         | 1.46%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.46%   |
| Bison Lenovo EasyCamera                                 | 3         | 1.46%   |
| Apple FaceTime HD Camera                                | 3         | 1.46%   |
| ALi WebCam                                              | 3         | 1.46%   |
| Z-Star Webcam                                           | 2         | 0.97%   |
| USB Camera USB Camera                                   | 2         | 0.97%   |
| USB Camera CS USB Camera CS                             | 2         | 0.97%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 0.97%   |
| Silicon Motion 300k Pixel Camera                        | 2         | 0.97%   |
| Realtek Lenovo EasyCamera                               | 2         | 0.97%   |
| Realtek HP Truevision HD                                | 2         | 0.97%   |
| Realtek EasyCamera                                      | 2         | 0.97%   |
| Realtek Asus laptop camera                              | 2         | 0.97%   |
| Quanta HD User Facing                                   | 2         | 0.97%   |
| Microdia HP Webcam-50                                   | 2         | 0.97%   |
| Lenovo Integrated Webcam                                | 2         | 0.97%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]       | 2         | 0.97%   |
| Chicony USB 2.0 Camera                                  | 2         | 0.97%   |
| Chicony HP HD Webcam                                    | 2         | 0.97%   |
| Chicony FJ Camera                                       | 2         | 0.97%   |
| Chicony 720p HD Camera                                  | 2         | 0.97%   |
| Bison Integrated Camera                                 | 2         | 0.97%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 34.78%  |
| Upek                       | 5         | 21.74%  |
| AuthenTec                  | 4         | 17.39%  |
| STMicroelectronics         | 3         | 13.04%  |
| Shenzhen Goodix Technology | 2         | 8.7%    |
| LighTuning Technology      | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 5         | 21.74%  |
| STMicroelectronics Fingerprint Reader                  | 3         | 13.04%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 8.7%    |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 8.7%    |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 8.7%    |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 8.7%    |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 4.35%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.35%   |
| AuthenTec Fingerprint Sensor                           | 1         | 4.35%   |
| AuthenTec AES2810                                      | 1         | 4.35%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4.35%   |
| AuthenTec AES1600                                      | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 40%     |
| Alcor Micro           | 5         | 33.33%  |
| Lenovo                | 2         | 13.33%  |
| O2 Micro              | 1         | 6.67%   |
| Gemalto (was Gemplus) | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader              | 4         | 26.67%  |
| Broadcom 5880                                    | 3         | 20%     |
| Lenovo Integrated Smart Card Reader              | 2         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor   | 2         | 13.33%  |
| O2 Micro OZ776 CCID Smartcard Reader             | 1         | 6.67%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader | 1         | 6.67%   |
| Broadcom 58200                                   | 1         | 6.67%   |
| Alcor Micro Watchdata W 1981                     | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 187       | 73.62%  |
| 1     | 56        | 22.05%  |
| 2     | 9         | 3.54%   |
| 4     | 1         | 0.39%   |
| 3     | 1         | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 22        | 27.85%  |
| Graphics card         | 14        | 17.72%  |
| Chipcard              | 14        | 17.72%  |
| Bluetooth             | 7         | 8.86%   |
| Net/wireless          | 6         | 7.59%   |
| Camera                | 6         | 7.59%   |
| Dvb card              | 3         | 3.8%    |
| Storage               | 2         | 2.53%   |
| Network               | 2         | 2.53%   |
| Multimedia controller | 2         | 2.53%   |
| Net/ethernet          | 1         | 1.27%   |

