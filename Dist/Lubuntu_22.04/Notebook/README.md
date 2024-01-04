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

Total: 326

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.0-43-generic | 23        | 8.75%   |
| 5.15.0-56-generic | 14        | 5.32%   |
| 5.15.0-25-generic | 12        | 4.56%   |
| 6.2.0-34-generic  | 9         | 3.42%   |
| 5.15.0-58-generic | 9         | 3.42%   |
| 6.2.0-26-generic  | 8         | 3.04%   |
| 5.15.0-60-generic | 8         | 3.04%   |
| 5.15.0-30-generic | 8         | 3.04%   |
| 5.19.0-41-generic | 7         | 2.66%   |
| 5.19.0-32-generic | 7         | 2.66%   |
| 5.15.0-47-generic | 7         | 2.66%   |
| 5.15.0-46-generic | 7         | 2.66%   |
| 5.19.0-35-generic | 6         | 2.28%   |
| 5.15.0-52-generic | 6         | 2.28%   |
| 5.15.0-27-generic | 6         | 2.28%   |
| 6.2.0-39-generic  | 5         | 1.9%    |
| 6.2.0-37-generic  | 5         | 1.9%    |
| 5.19.0-43-generic | 5         | 1.9%    |
| 5.15.0-53-generic | 5         | 1.9%    |
| 6.2.0-36-generic  | 4         | 1.52%   |
| 6.2.0-33-generic  | 4         | 1.52%   |
| 5.19.0-46-generic | 4         | 1.52%   |
| 5.19.0-40-generic | 4         | 1.52%   |
| 5.19.0-38-generic | 4         | 1.52%   |
| 5.15.0-73-generic | 4         | 1.52%   |
| 5.15.0-71-generic | 4         | 1.52%   |
| 5.15.0-57-generic | 4         | 1.52%   |
| 5.15.0-50-generic | 4         | 1.52%   |
| 5.15.0-41-generic | 4         | 1.52%   |
| 6.2.0-35-generic  | 3         | 1.14%   |
| 6.2.0-31-generic  | 3         | 1.14%   |
| 5.19.0-42-generic | 3         | 1.14%   |
| 5.15.0-79-generic | 3         | 1.14%   |
| 5.15.0-67-generic | 3         | 1.14%   |
| 5.15.0-48-generic | 3         | 1.14%   |
| 5.15.0-40-generic | 3         | 1.14%   |
| 5.15.0-35-generic | 3         | 1.14%   |
| 5.19.0-50-generic | 2         | 0.76%   |
| 5.19.0-45-generic | 2         | 0.76%   |
| 5.15.0-89-generic | 2         | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 151       | 61.38%  |
| 5.19.0  | 45        | 18.29%  |
| 6.2.0   | 42        | 17.07%  |
| 6.5.0   | 1         | 0.41%   |
| 6.4.12  | 1         | 0.41%   |
| 6.1.12  | 1         | 0.41%   |
| 6.0.12  | 1         | 0.41%   |
| 5.4.0   | 1         | 0.41%   |
| 5.19.8  | 1         | 0.41%   |
| 5.18.0  | 1         | 0.41%   |
| 5.14.0  | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 151       | 61.38%  |
| 5.19    | 46        | 18.7%   |
| 6.2     | 42        | 17.07%  |
| 6.5     | 1         | 0.41%   |
| 6.4     | 1         | 0.41%   |
| 6.1     | 1         | 0.41%   |
| 6.0     | 1         | 0.41%   |
| 5.4     | 1         | 0.41%   |
| 5.18    | 1         | 0.41%   |
| 5.14    | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 241       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXQt       | 233       | 96.68%  |
| LXDE       | 5         | 2.07%   |
| X-Cinnamon | 2         | 0.83%   |
| KDE5       | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 236       | 97.93%  |
| Tty     | 4         | 1.66%   |
| Wayland | 1         | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 213       | 87.65%  |
| Unknown | 16        | 6.58%   |
| LightDM | 10        | 4.12%   |
| GDM3    | 4         | 1.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Notebooks | Percent |
|--------|-----------|---------|
| en_US  | 73        | 30.17%  |
| fr_FR  | 26        | 10.74%  |
| it_IT  | 17        | 7.02%   |
| en_GB  | 16        | 6.61%   |
| C      | 15        | 6.2%    |
| de_DE  | 13        | 5.37%   |
| ru_RU  | 9         | 3.72%   |
| pt_BR  | 8         | 3.31%   |
| pl_PL  | 8         | 3.31%   |
| en_AG  | 8         | 3.31%   |
| en_CA  | 6         | 2.48%   |
| es_MX  | 5         | 2.07%   |
| en_AU  | 4         | 1.65%   |
| nl_BE  | 3         | 1.24%   |
| es_CO  | 3         | 1.24%   |
| tr_TR  | 2         | 0.83%   |
| sk_SK  | 2         | 0.83%   |
| es_ES  | 2         | 0.83%   |
| es_CR  | 2         | 0.83%   |
| es_CL  | 2         | 0.83%   |
| es_AR  | 2         | 0.83%   |
| en_PH  | 2         | 0.83%   |
| vi_VN  | 1         | 0.41%   |
| nl_NL  | 1         | 0.41%   |
| lzh_TW | 1         | 0.41%   |
| ja_JP  | 1         | 0.41%   |
| hu_HU  | 1         | 0.41%   |
| fr_CA  | 1         | 0.41%   |
| fi_FI  | 1         | 0.41%   |
| es_EC  | 1         | 0.41%   |
| en_ZA  | 1         | 0.41%   |
| en_DE  | 1         | 0.41%   |
| el_GR  | 1         | 0.41%   |
| de_CH  | 1         | 0.41%   |
| da_DK  | 1         | 0.41%   |
| aa_DJ  | 1         | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 144       | 59.5%   |
| EFI  | 98        | 40.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 204       | 83.27%  |
| Tmpfs   | 20        | 8.16%   |
| Overlay | 17        | 6.94%   |
| Btrfs   | 2         | 0.82%   |
| Xfs     | 1         | 0.41%   |
| Ext2    | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 136       | 55.74%  |
| MBR     | 71        | 29.1%   |
| Unknown | 37        | 15.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 220       | 90.53%  |
| Yes       | 23        | 9.47%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 177       | 72.84%  |
| Yes       | 66        | 27.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 44        | 18.26%  |
| Hewlett-Packard     | 41        | 17.01%  |
| Dell                | 27        | 11.2%   |
| Acer                | 24        | 9.96%   |
| ASUSTek Computer    | 17        | 7.05%   |
| Google              | 12        | 4.98%   |
| Apple               | 8         | 3.32%   |
| Toshiba             | 7         | 2.9%    |
| Unknown             | 5         | 2.07%   |
| Sony                | 4         | 1.66%   |
| Mediacom            | 4         | 1.66%   |
| Fujitsu             | 4         | 1.66%   |
| Samsung Electronics | 3         | 1.24%   |
| Packard Bell        | 3         | 1.24%   |
| Chuwi               | 3         | 1.24%   |
| Thomson             | 2         | 0.83%   |
| SGIN                | 2         | 0.83%   |
| Positivo            | 2         | 0.83%   |
| MSI                 | 2         | 0.83%   |
| Intel               | 2         | 0.83%   |
| HUAWEI              | 2         | 0.83%   |
| Hampoo              | 2         | 0.83%   |
| GPU Company         | 2         | 0.83%   |
| Getac               | 2         | 0.83%   |
| Gateway             | 2         | 0.83%   |
| TrekStor            | 1         | 0.41%   |
| Pretech             | 1         | 0.41%   |
| Prestigio           | 1         | 0.41%   |
| Panasonic           | 1         | 0.41%   |
| OEM                 | 1         | 0.41%   |
| Mini PC             | 1         | 0.41%   |
| Kiano               | 1         | 0.41%   |
| Insyde              | 1         | 0.41%   |
| IFSA                | 1         | 0.41%   |
| Fujitsu Siemens     | 1         | 0.41%   |
| eMachines           | 1         | 0.41%   |
| Dixonsxp            | 1         | 0.41%   |
| Compal              | 1         | 0.41%   |
| AXIOO               | 1         | 0.41%   |
| Alienware           | 1         | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 2.9%    |
| HP Notebook                                | 4         | 1.66%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 3         | 1.24%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 3         | 1.24%   |
| HP Pavilion 15                             | 3         | 1.24%   |
| Apple MacBookPro8,1                        | 3         | 1.24%   |
| Lenovo G50-30 80G0                         | 2         | 0.83%   |
| HP Pavilion g6                             | 2         | 0.83%   |
| HP 255 G2                                  | 2         | 0.83%   |
| HP 2000                                    | 2         | 0.83%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 0.83%   |
| Apple MacBook4,1                           | 2         | 0.83%   |
| Acer Aspire SW3-013                        | 2         | 0.83%   |
| Acer Aspire A314-23P                       | 2         | 0.83%   |
| TrekStor SurfTab wintron 7.0 ST70416-6     | 1         | 0.41%   |
| Toshiba Satellite Radius P55W-B            | 1         | 0.41%   |
| Toshiba Satellite Pro S500                 | 1         | 0.41%   |
| Toshiba Satellite P770                     | 1         | 0.41%   |
| Toshiba Satellite P70-A                    | 1         | 0.41%   |
| Toshiba Satellite L875D                    | 1         | 0.41%   |
| Toshiba Satellite L40                      | 1         | 0.41%   |
| Toshiba Satellite C660                     | 1         | 0.41%   |
| Thomson NEO14-4W64                         | 1         | 0.41%   |
| Thomson N14C4WH64                          | 1         | 0.41%   |
| Sony VPCEH2E1R                             | 1         | 0.41%   |
| Sony VPCEB15FM                             | 1         | 0.41%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.41%   |
| Sony SVE14A2V1EW                           | 1         | 0.41%   |
| SGIN M15                                   | 1         | 0.41%   |
| SGIN laptop                                | 1         | 0.41%   |
| Samsung N150P/N210P/N220P                  | 1         | 0.41%   |
| Samsung N150/N210/N220                     | 1         | 0.41%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.41%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.41%   |
| Prestigio PSB141C01BFH                     | 1         | 0.41%   |
| Positivo Q232A                             | 1         | 0.41%   |
| Positivo i500pro                           | 1         | 0.41%   |
| Panasonic CF-F9KWPZFFE                     | 1         | 0.41%   |
| Packard Bell ENLE11BZ                      | 1         | 0.41%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 18        | 7.47%   |
| Acer Aspire           | 17        | 7.05%   |
| Lenovo ThinkPad       | 16        | 6.64%   |
| Dell Latitude         | 10        | 4.15%   |
| HP Pavilion           | 9         | 3.73%   |
| Toshiba Satellite     | 7         | 2.9%    |
| Unknown               | 7         | 2.9%    |
| Dell Inspiron         | 6         | 2.49%   |
| HP Laptop             | 5         | 2.07%   |
| HP ProBook            | 4         | 1.66%   |
| HP Notebook           | 4         | 1.66%   |
| Fujitsu LIFEBOOK      | 4         | 1.66%   |
| Dell XPS              | 4         | 1.66%   |
| Mediacom WinPad       | 3         | 1.24%   |
| HP EliteBook          | 3         | 1.24%   |
| Dell Precision        | 3         | 1.24%   |
| Apple MacBookPro8     | 3         | 1.24%   |
| Acer Extensa          | 3         | 1.24%   |
| Packard Bell EasyNote | 2         | 0.83%   |
| Lenovo G50-30         | 2         | 0.83%   |
| HP ZBook              | 2         | 0.83%   |
| HP Compaq             | 2         | 0.83%   |
| HP 255                | 2         | 0.83%   |
| HP 250                | 2         | 0.83%   |
| HP 2000               | 2         | 0.83%   |
| HP 15                 | 2         | 0.83%   |
| Dell Vostro           | 2         | 0.83%   |
| Chuwi GemiBook        | 2         | 0.83%   |
| ASUS VivoBook         | 2         | 0.83%   |
| Apple MacBook4        | 2         | 0.83%   |
| TrekStor SurfTab      | 1         | 0.41%   |
| Thomson NEO14-4W64    | 1         | 0.41%   |
| Thomson N14C4WH64     | 1         | 0.41%   |
| Sony VPCEH2E1R        | 1         | 0.41%   |
| Sony VPCEB15FM        | 1         | 0.41%   |
| Sony VGN-SZ71WN       | 1         | 0.41%   |
| Sony SVE14A2V1EW      | 1         | 0.41%   |
| SGIN M15              | 1         | 0.41%   |
| SGIN laptop           | 1         | 0.41%   |
| Samsung N150P         | 1         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 24        | 9.96%   |
| 2011 | 24        | 9.96%   |
| 2012 | 23        | 9.54%   |
| 2016 | 19        | 7.88%   |
| 2015 | 17        | 7.05%   |
| 2022 | 16        | 6.64%   |
| 2021 | 16        | 6.64%   |
| 2010 | 16        | 6.64%   |
| 2014 | 15        | 6.22%   |
| 2019 | 12        | 4.98%   |
| 2008 | 11        | 4.56%   |
| 2009 | 10        | 4.15%   |
| 2017 | 9         | 3.73%   |
| 2020 | 8         | 3.32%   |
| 2007 | 8         | 3.32%   |
| 2023 | 7         | 2.9%    |
| 2018 | 6         | 2.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 241       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 226       | 92.62%  |
| Enabled  | 18        | 7.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 228       | 94.61%  |
| Yes  | 13        | 5.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 92        | 37.86%  |
| 4.01-8.0    | 62        | 25.51%  |
| 1.01-2.0    | 35        | 14.4%   |
| 8.01-16.0   | 21        | 8.64%   |
| 16.01-24.0  | 17        | 7%      |
| 2.01-3.0    | 8         | 3.29%   |
| 32.01-64.0  | 5         | 2.06%   |
| 24.01-32.0  | 1         | 0.41%   |
| 64.01-256.0 | 1         | 0.41%   |
| 0.51-1.0    | 1         | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 124       | 49.01%  |
| 2.01-3.0  | 53        | 20.95%  |
| 0.51-1.0  | 53        | 20.95%  |
| 4.01-8.0  | 11        | 4.35%   |
| 3.01-4.0  | 9         | 3.56%   |
| 0.01-0.5  | 2         | 0.79%   |
| 8.01-16.0 | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 195       | 79.92%  |
| 2      | 40        | 16.39%  |
| 3      | 7         | 2.87%   |
| 0      | 2         | 0.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 135       | 56.02%  |
| Yes       | 106       | 43.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 184       | 76.03%  |
| No        | 58        | 23.97%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 219       | 90.87%  |
| No        | 22        | 9.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 160       | 65.57%  |
| No        | 84        | 34.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 40        | 16.6%   |
| France       | 27        | 11.2%   |
| Germany      | 22        | 9.13%   |
| Italy        | 21        | 8.71%   |
| Russia       | 14        | 5.81%   |
| Poland       | 10        | 4.15%   |
| UK           | 9         | 3.73%   |
| Brazil       | 8         | 3.32%   |
| Canada       | 7         | 2.9%    |
| Belgium      | 5         | 2.07%   |
| Ukraine      | 4         | 1.66%   |
| Netherlands  | 4         | 1.66%   |
| Mexico       | 4         | 1.66%   |
| Vietnam      | 3         | 1.24%   |
| Turkey       | 3         | 1.24%   |
| Slovakia     | 3         | 1.24%   |
| Indonesia    | 3         | 1.24%   |
| Hungary      | 3         | 1.24%   |
| Costa Rica   | 3         | 1.24%   |
| Colombia     | 3         | 1.24%   |
| Australia    | 3         | 1.24%   |
| UAE          | 2         | 0.83%   |
| Sweden       | 2         | 0.83%   |
| Spain        | 2         | 0.83%   |
| South Africa | 2         | 0.83%   |
| Portugal     | 2         | 0.83%   |
| Philippines  | 2         | 0.83%   |
| Japan        | 2         | 0.83%   |
| Finland      | 2         | 0.83%   |
| Czechia      | 2         | 0.83%   |
| Chile        | 2         | 0.83%   |
| Argentina    | 2         | 0.83%   |
| Thailand     | 1         | 0.41%   |
| Taiwan       | 1         | 0.41%   |
| Switzerland  | 1         | 0.41%   |
| Peru         | 1         | 0.41%   |
| Pakistan     | 1         | 0.41%   |
| Morocco      | 1         | 0.41%   |
| Malaysia     | 1         | 0.41%   |
| Lithuania    | 1         | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Paris                  | 7         | 2.8%    |
| Moscow                 | 4         | 1.6%    |
| Bruhl                  | 4         | 1.6%    |
| Milan                  | 3         | 1.2%    |
| Kyiv                   | 3         | 1.2%    |
| Ghent                  | 3         | 1.2%    |
| Sarospatak             | 2         | 0.8%    |
| Santiago               | 2         | 0.8%    |
| Rome                   | 2         | 0.8%    |
| Porto Alegre           | 2         | 0.8%    |
| Munich                 | 2         | 0.8%    |
| Milano                 | 2         | 0.8%    |
| Lyon                   | 2         | 0.8%    |
| Lansing                | 2         | 0.8%    |
| Ho Chi Minh City       | 2         | 0.8%    |
| Heredia                | 2         | 0.8%    |
| Eugene                 | 2         | 0.8%    |
| Dubai                  | 2         | 0.8%    |
| Columbus               | 2         | 0.8%    |
| Bratislava             | 2         | 0.8%    |
| Bogotá                | 2         | 0.8%    |
| Zizur Mayor            | 1         | 0.4%    |
| Zawiercie              | 1         | 0.4%    |
| Zagreb                 | 1         | 0.4%    |
| Yoshkar-Ola            | 1         | 0.4%    |
| Yorkville              | 1         | 0.4%    |
| Yerevan                | 1         | 0.4%    |
| Yekaterinburg          | 1         | 0.4%    |
| Wolfhagen              | 1         | 0.4%    |
| West Stockbridge       | 1         | 0.4%    |
| Wattignies-la-Victoire | 1         | 0.4%    |
| Warsaw                 | 1         | 0.4%    |
| Warren                 | 1         | 0.4%    |
| Warendorf              | 1         | 0.4%    |
| Waipahu                | 1         | 0.4%    |
| Vrbov                  | 1         | 0.4%    |
| Volzhskiy              | 1         | 0.4%    |
| Vesilahti              | 1         | 0.4%    |
| Verona                 | 1         | 0.4%    |
| Valenciennes           | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Unknown                   | 45        | 63     | 16.67%  |
| WDC                       | 38        | 43     | 14.07%  |
| Seagate                   | 29        | 33     | 10.74%  |
| Samsung Electronics       | 22        | 32     | 8.15%   |
| Toshiba                   | 18        | 19     | 6.67%   |
| Hitachi                   | 12        | 16     | 4.44%   |
| SanDisk                   | 10        | 10     | 3.7%    |
| Kingston                  | 9         | 9      | 3.33%   |
| Micron Technology         | 8         | 9      | 2.96%   |
| SK hynix                  | 7         | 7      | 2.59%   |
| HGST                      | 6         | 7      | 2.22%   |
| Crucial                   | 5         | 5      | 1.85%   |
| Unknown                   | 5         | 5      | 1.85%   |
| Transcend                 | 4         | 5      | 1.48%   |
| A-DATA Technology         | 4         | 4      | 1.48%   |
| SPCC                      | 3         | 4      | 1.11%   |
| Intel                     | 3         | 3      | 1.11%   |
| China                     | 3         | 3      | 1.11%   |
| UMIS                      | 2         | 2      | 0.74%   |
| Silicon Motion            | 2         | 2      | 0.74%   |
| Patriot                   | 2         | 2      | 0.74%   |
| NGFF                      | 2         | 2      | 0.74%   |
| LITEON                    | 2         | 2      | 0.74%   |
| GOODRAM                   | 2         | 2      | 0.74%   |
| Fujitsu                   | 2         | 2      | 0.74%   |
| Apacer                    | 2         | 2      | 0.74%   |
| W800S                     | 1         | 1      | 0.37%   |
| USB3.0                    | 1         | 1      | 0.37%   |
| Teclast                   | 1         | 1      | 0.37%   |
| Rogueware                 | 1         | 1      | 0.37%   |
| PNY                       | 1         | 1      | 0.37%   |
| Plextor                   | 1         | 1      | 0.37%   |
| Phison                    | 1         | 1      | 0.37%   |
| Netac                     | 1         | 1      | 0.37%   |
| Neo Forza                 | 1         | 1      | 0.37%   |
| Micron/Crucial Technology | 1         | 1      | 0.37%   |
| Lexar                     | 1         | 1      | 0.37%   |
| Leqixiang                 | 1         | 1      | 0.37%   |
| Lenovo                    | 1         | 1      | 0.37%   |
| LDLC                      | 1         | 2      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 8         | 2.8%    |
| Unknown MMC Card  32GB             | 6         | 2.1%    |
| Unknown NCard  32GB                | 5         | 1.75%   |
| Seagate ST9500325AS 500GB          | 5         | 1.75%   |
| SanDisk DF4032  32GB               | 5         | 1.75%   |
| Unknown                            | 5         | 1.75%   |
| Unknown SD/MMC/MS PRO 512GB        | 4         | 1.4%    |
| Unknown DA4032  32GB               | 4         | 1.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 1.4%    |
| Micron 2450_MTFDKBA512TFK 512GB    | 4         | 1.4%    |
| WDC WD3200BPVT-22JJ5T0 320GB       | 3         | 1.05%   |
| Unknown MMC Card  16GB             | 3         | 1.05%   |
| Toshiba MQ01ABF050 500GB           | 3         | 1.05%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 1.05%   |
| Kingston SA400S37240G 240GB SSD    | 3         | 1.05%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.7%    |
| WDC WD3200BEKT-75PVMT1 320GB       | 2         | 0.7%    |
| WDC WD10SPZX-24Z10 1TB             | 2         | 0.7%    |
| Unknown SC64G  64GB                | 2         | 0.7%    |
| Unknown SC256  256GB               | 2         | 0.7%    |
| Unknown MMC64G  64GB               | 2         | 0.7%    |
| Unknown DA4064  64GB               | 2         | 0.7%    |
| Toshiba MQ01ABD075 752GB           | 2         | 0.7%    |
| Toshiba MQ01ABD050 500GB           | 2         | 0.7%    |
| SPCC Solid State Disk 120GB        | 2         | 0.7%    |
| SK hynix HFM001TD3JX013N 1024GB    | 2         | 0.7%    |
| SK hynix HBG4e  32GB               | 2         | 0.7%    |
| Seagate ST1000LM048-2E7172 1TB     | 2         | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.7%    |
| Samsung SSD 850 EVO 250GB          | 2         | 0.7%    |
| Samsung HM160HI 160GB              | 2         | 0.7%    |
| Samsung HM121HI 120GB              | 2         | 0.7%    |
| HGST HTS545050A7E680 500GB         | 2         | 0.7%    |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.35%   |
| WDC WDS500G2B0A 500GB SSD          | 1         | 0.35%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 0.35%   |
| WDC WDS250G2B0A 250GB SSD          | 1         | 0.35%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.35%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 1         | 0.35%   |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 32     | 29.81%  |
| Seagate             | 29        | 33     | 27.88%  |
| Toshiba             | 15        | 16     | 14.42%  |
| Hitachi             | 12        | 16     | 11.54%  |
| HGST                | 6         | 7      | 5.77%   |
| Unknown             | 4         | 4      | 3.85%   |
| Samsung Electronics | 4         | 9      | 3.85%   |
| Fujitsu             | 2         | 2      | 1.92%   |
| USB3.0              | 1         | 1      | 0.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 13     | 14.81%  |
| Kingston            | 8         | 8      | 9.88%   |
| WDC                 | 5         | 7      | 6.17%   |
| SanDisk             | 5         | 5      | 6.17%   |
| Transcend           | 4         | 5      | 4.94%   |
| Crucial             | 4         | 4      | 4.94%   |
| A-DATA Technology   | 4         | 4      | 4.94%   |
| Toshiba             | 3         | 3      | 3.7%    |
| SPCC                | 3         | 4      | 3.7%    |
| Intel               | 3         | 3      | 3.7%    |
| Patriot             | 2         | 2      | 2.47%   |
| NGFF                | 2         | 2      | 2.47%   |
| Micron Technology   | 2         | 2      | 2.47%   |
| LITEON              | 2         | 2      | 2.47%   |
| GOODRAM             | 2         | 2      | 2.47%   |
| Apacer              | 2         | 2      | 2.47%   |
| W800S               | 1         | 1      | 1.23%   |
| Teclast             | 1         | 1      | 1.23%   |
| Rogueware           | 1         | 1      | 1.23%   |
| PNY                 | 1         | 1      | 1.23%   |
| Plextor             | 1         | 1      | 1.23%   |
| Netac               | 1         | 1      | 1.23%   |
| Neo Forza           | 1         | 1      | 1.23%   |
| Lexar               | 1         | 1      | 1.23%   |
| Leqixiang           | 1         | 1      | 1.23%   |
| Lenovo              | 1         | 1      | 1.23%   |
| KingSpec            | 1         | 1      | 1.23%   |
| KINGPOWER           | 1         | 1      | 1.23%   |
| Kingmax             | 1         | 1      | 1.23%   |
| HUSKY               | 1         | 1      | 1.23%   |
| Hewlett-Packard     | 1         | 1      | 1.23%   |
| China               | 1         | 1      | 1.23%   |
| BHT                 | 1         | 1      | 1.23%   |
| AirDisk             | 1         | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 102       | 120    | 38.06%  |
| SSD     | 79        | 86     | 29.48%  |
| MMC     | 54        | 72     | 20.15%  |
| NVMe    | 29        | 35     | 10.82%  |
| Unknown | 4         | 5      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 171       | 202    | 65.02%  |
| MMC  | 54        | 72     | 20.53%  |
| NVMe | 29        | 35     | 11.03%  |
| SAS  | 9         | 9      | 3.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 131       | 148    | 72.38%  |
| 0.51-1.0   | 45        | 53     | 24.86%  |
| 1.01-2.0   | 4         | 4      | 2.21%   |
| 3.01-4.0   | 1         | 1      | 0.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 84        | 34.29%  |
| 251-500        | 61        | 24.9%   |
| 501-1000       | 25        | 10.2%   |
| 1-20           | 24        | 9.8%    |
| 51-100         | 24        | 9.8%    |
| 21-50          | 20        | 8.16%   |
| More than 3000 | 3         | 1.22%   |
| 1001-2000      | 2         | 0.82%   |
| 2001-3000      | 1         | 0.41%   |
| Unknown        | 1         | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 131       | 52.61%  |
| 21-50          | 53        | 21.29%  |
| 51-100         | 26        | 10.44%  |
| 101-250        | 20        | 8.03%   |
| 251-500        | 9         | 3.61%   |
| 501-1000       | 5         | 2.01%   |
| More than 3000 | 2         | 0.8%    |
| 1001-2000      | 2         | 0.8%    |
| Unknown        | 1         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 4      | 10.53%  |
| Seagate ST9500325AS 500GB          | 2         | 2      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 5.26%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 1      | 2.63%   |
| WDC WD5000BPVT-75HXZT1 500GB       | 1         | 1      | 2.63%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 2.63%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 2.63%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 2.63%   |
| WDC WD10SPCX-21KHST0 1TB           | 1         | 1      | 2.63%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 2.63%   |
| Transcend TS256GSSD720 256GB       | 1         | 1      | 2.63%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD050 500GB           | 1         | 1      | 2.63%   |
| Toshiba MK2556GSY 250GB            | 1         | 1      | 2.63%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 2.63%   |
| Seagate ST500LM021-1KJ152 500GB    | 1         | 1      | 2.63%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 2.63%   |
| Seagate ST320LT012-9WS14C 320GB    | 1         | 1      | 2.63%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 2.63%   |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1      | 2.63%   |
| Seagate ST1000DM003-1SB102 1TB     | 1         | 1      | 2.63%   |
| Samsung Electronics HM121HI 120GB  | 1         | 6      | 2.63%   |
| Plextor PX-128M6M 128GB SSD        | 1         | 1      | 2.63%   |
| NGFF 2280 512GB SSD                | 1         | 1      | 2.63%   |
| Kingmax SSD 120GB                  | 1         | 1      | 2.63%   |
| Intel SSDSC2KW512G8 512GB          | 1         | 1      | 2.63%   |
| Intel SSDSA2M080G2LE 80GB          | 1         | 1      | 2.63%   |
| Hitachi HTS722080K9SA00 80GB       | 1         | 1      | 2.63%   |
| Hitachi HTS545050B9A300 500GB      | 1         | 1      | 2.63%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 2.63%   |
| HGST HTS725032A7E630 320GB         | 1         | 1      | 2.63%   |
| Fujitsu MHY2120BH 120GB            | 1         | 1      | 2.63%   |
| Apacer 16GB SATA Flash Drive SSD   | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 39.47%  |
| WDC                 | 7         | 7      | 18.42%  |
| Toshiba             | 3         | 3      | 7.89%   |
| Hitachi             | 3         | 3      | 7.89%   |
| Intel               | 2         | 2      | 5.26%   |
| Transcend           | 1         | 1      | 2.63%   |
| Samsung Electronics | 1         | 6      | 2.63%   |
| Plextor             | 1         | 1      | 2.63%   |
| NGFF                | 1         | 1      | 2.63%   |
| Kingmax             | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |
| Fujitsu             | 1         | 1      | 2.63%   |
| Apacer              | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 48.39%  |
| WDC                 | 7         | 7      | 22.58%  |
| Toshiba             | 3         | 3      | 9.68%   |
| Hitachi             | 3         | 3      | 9.68%   |
| Samsung Electronics | 1         | 6      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |
| Fujitsu             | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 36     | 81.58%  |
| SSD  | 7         | 7      | 18.42%  |

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
| Detected | 131       | 175    | 51.57%  |
| Works    | 85        | 100    | 33.46%  |
| Malfunc  | 38        | 43     | 14.96%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 162       | 72.32%  |
| AMD                              | 29        | 12.95%  |
| Micron Technology                | 7         | 3.13%   |
| Samsung Electronics              | 6         | 2.68%   |
| SK hynix                         | 4         | 1.79%   |
| SanDisk                          | 3         | 1.34%   |
| Nvidia                           | 3         | 1.34%   |
| Union Memory (Shenzhen)          | 2         | 0.89%   |
| Silicon Motion                   | 2         | 0.89%   |
| Micron/Crucial Technology        | 2         | 0.89%   |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Silicon Image                    | 1         | 0.45%   |
| Phison Electronics               | 1         | 0.45%   |
| Kingston Technology Company      | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 27        | 11.11%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 9.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 5.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 12        | 4.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 12        | 4.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 10        | 4.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 3.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 3.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 2.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 2.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 2.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 2.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.47%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 5         | 2.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 2.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 2.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 2.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.65%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 1.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.23%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.82%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 0.82%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 0.82%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.82%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                            | 1         | 0.41%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                  | 1         | 0.41%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.41%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.41%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 179       | 75.85%  |
| NVMe | 28        | 11.86%  |
| IDE  | 20        | 8.47%   |
| RAID | 9         | 3.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 205       | 85.06%  |
| AMD    | 36        | 14.94%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 8         | 3.32%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 7         | 2.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 2.07%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 5         | 2.07%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 4         | 1.66%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.66%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 1.66%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 1.66%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 4         | 1.66%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 3         | 1.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.24%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.24%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 3         | 1.24%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 1.24%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 1.24%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 3         | 1.24%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 3         | 1.24%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.83%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.83%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.83%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.83%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 2         | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.83%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.83%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.83%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.83%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.83%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 0.83%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.83%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 0.83%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.83%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 2         | 0.83%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.83%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz          | 2         | 0.83%   |
| Intel Celeron N4500 @ 1.10GHz                 | 2         | 0.83%   |
| Intel Celeron N4120 CPU @ 1.10GHz             | 2         | 0.83%   |
| Intel Celeron N4020C CPU @ 1.10GHz            | 2         | 0.83%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 2         | 0.83%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 49        | 20.33%  |
| Intel Core i5           | 45        | 18.67%  |
| Intel Core i7           | 24        | 9.96%   |
| Intel Atom              | 22        | 9.13%   |
| Intel Core 2 Duo        | 20        | 8.3%    |
| Intel Core i3           | 18        | 7.47%   |
| Intel Pentium           | 9         | 3.73%   |
| Other                   | 8         | 3.32%   |
| AMD A6                  | 7         | 2.9%    |
| AMD Ryzen 7             | 4         | 1.66%   |
| AMD E2                  | 4         | 1.66%   |
| AMD E1                  | 4         | 1.66%   |
| Intel Pentium Dual-Core | 3         | 1.24%   |
| Intel Pentium Dual      | 3         | 1.24%   |
| AMD Ryzen 5             | 3         | 1.24%   |
| AMD E                   | 3         | 1.24%   |
| Intel Core 2            | 2         | 0.83%   |
| AMD A8                  | 2         | 0.83%   |
| AMD A4                  | 2         | 0.83%   |
| Intel Pentium Silver    | 1         | 0.41%   |
| Intel Genuine           | 1         | 0.41%   |
| Intel Celeron Dual-Core | 1         | 0.41%   |
| AMD Ryzen 9             | 1         | 0.41%   |
| AMD Ryzen 7 PRO         | 1         | 0.41%   |
| AMD C-60                | 1         | 0.41%   |
| AMD Athlon II           | 1         | 0.41%   |
| AMD Athlon              | 1         | 0.41%   |
| AMD A10                 | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 155       | 64.32%  |
| 4      | 68        | 28.22%  |
| 1      | 7         | 2.9%    |
| 8      | 6         | 2.49%   |
| 10     | 3         | 1.24%   |
| 14     | 1         | 0.41%   |
| 6      | 1         | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 241       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 130       | 53.94%  |
| 2      | 111       | 46.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 241       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 44.44%  |
| 0x306a9    | 16        | 6.58%   |
| 0x206a7    | 11        | 4.53%   |
| 0x406c3    | 8         | 3.29%   |
| 0x706a8    | 6         | 2.47%   |
| 0x406c4    | 5         | 2.06%   |
| 0x30678    | 5         | 2.06%   |
| 0x20655    | 5         | 2.06%   |
| 0x1067a    | 5         | 2.06%   |
| 0x0700010f | 5         | 2.06%   |
| 0x05000119 | 5         | 2.06%   |
| 0x6fd      | 4         | 1.65%   |
| 0x40651    | 4         | 1.65%   |
| 0x806ec    | 3         | 1.23%   |
| 0x806ea    | 3         | 1.23%   |
| 0x706a1    | 3         | 1.23%   |
| 0x506c9    | 3         | 1.23%   |
| 0x406e3    | 3         | 1.23%   |
| 0x0a50000c | 3         | 1.23%   |
| 0x06006705 | 3         | 1.23%   |
| 0x906c0    | 2         | 0.82%   |
| 0x906a4    | 2         | 0.82%   |
| 0x806c1    | 2         | 0.82%   |
| 0x706e5    | 2         | 0.82%   |
| 0x306c3    | 2         | 0.82%   |
| 0x106ca    | 2         | 0.82%   |
| 0x08a00008 | 2         | 0.82%   |
| 0x06006704 | 2         | 0.82%   |
| 0x06001119 | 2         | 0.82%   |
| 0x906ed    | 1         | 0.41%   |
| 0x806eb    | 1         | 0.41%   |
| 0x806e9    | 1         | 0.41%   |
| 0x6fb      | 1         | 0.41%   |
| 0x6fa      | 1         | 0.41%   |
| 0x6f6      | 1         | 0.41%   |
| 0x506e3    | 1         | 0.41%   |
| 0x306d4    | 1         | 0.41%   |
| 0x20652    | 1         | 0.41%   |
| 0x10676    | 1         | 0.41%   |
| 0x0a50000d | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Silvermont       | 41        | 17.01%  |
| IvyBridge        | 23        | 9.54%   |
| SandyBridge      | 21        | 8.71%   |
| Penryn           | 17        | 7.05%   |
| Goldmont plus    | 16        | 6.64%   |
| Haswell          | 14        | 5.81%   |
| Westmere         | 13        | 5.39%   |
| Core             | 13        | 5.39%   |
| KabyLake         | 12        | 4.98%   |
| Excavator        | 8         | 3.32%   |
| Skylake          | 6         | 2.49%   |
| Jaguar           | 6         | 2.49%   |
| Goldmont         | 6         | 2.49%   |
| Zen 3            | 5         | 2.07%   |
| Broadwell        | 5         | 2.07%   |
| Bonnell          | 5         | 2.07%   |
| Bobcat           | 5         | 2.07%   |
| Unknown          | 5         | 2.07%   |
| Piledriver       | 4         | 1.66%   |
| Alderlake Hybrid | 4         | 1.66%   |
| Tremont          | 3         | 1.24%   |
| IceLake          | 3         | 1.24%   |
| TigerLake        | 2         | 0.83%   |
| Puma             | 2         | 0.83%   |
| K10              | 1         | 0.41%   |
| Gracemont        | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 189       | 68.98%  |
| AMD    | 50        | 18.25%  |
| Nvidia | 35        | 12.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 8.59%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 7.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 7.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 5.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 15        | 5.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 3.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 3.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 3.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 2.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 2.41%   |
| Intel HD Graphics 500                                                                    | 6         | 2.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.37%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.37%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.37%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 3         | 1.03%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.03%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 1.03%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.03%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.03%   |
| AMD Mendocino                                                                            | 3         | 1.03%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.69%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 0.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.69%   |
| Intel HD Graphics 630                                                                    | 2         | 0.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.69%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 2         | 0.69%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.69%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 2         | 0.69%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 2         | 0.69%   |
| AMD Lucienne                                                                             | 2         | 0.69%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 2         | 0.69%   |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 0.69%   |
| AMD Barcelo                                                                              | 2         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 154       | 63.9%   |
| 1 x AMD        | 32        | 13.28%  |
| Intel + Nvidia | 20        | 8.3%    |
| 1 x Nvidia     | 13        | 5.39%   |
| Intel + AMD    | 10        | 4.15%   |
| 2 x AMD        | 6         | 2.49%   |
| Other          | 4         | 1.66%   |
| AMD + Nvidia   | 2         | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 227       | 94.19%  |
| Proprietary | 10        | 4.15%   |
| Unknown     | 4         | 1.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 189       | 78.1%   |
| 0.01-0.5   | 28        | 11.57%  |
| 1.01-2.0   | 15        | 6.2%    |
| 0.51-1.0   | 6         | 2.48%   |
| 3.01-4.0   | 2         | 0.83%   |
| 5.01-6.0   | 1         | 0.41%   |
| 2.01-3.0   | 1         | 0.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 52        | 21.05%  |
| LG Display              | 43        | 17.41%  |
| BOE                     | 38        | 15.38%  |
| Chimei Innolux          | 26        | 10.53%  |
| Samsung Electronics     | 25        | 10.12%  |
| Apple                   | 9         | 3.64%   |
| Lenovo                  | 6         | 2.43%   |
| Sharp                   | 5         | 2.02%   |
| CPT                     | 5         | 2.02%   |
| Chi Mei Optoelectronics | 5         | 2.02%   |
| Toshiba                 | 4         | 1.62%   |
| Acer                    | 4         | 1.62%   |
| Hewlett-Packard         | 3         | 1.21%   |
| Goldstar                | 3         | 1.21%   |
| LG Philips              | 2         | 0.81%   |
| InfoVision              | 2         | 0.81%   |
| Dell                    | 2         | 0.81%   |
| ViewSonic               | 1         | 0.4%    |
| Panasonic               | 1         | 0.4%    |
| LLL                     | 1         | 0.4%    |
| JVC                     | 1         | 0.4%    |
| JDI                     | 1         | 0.4%    |
| Insignia                | 1         | 0.4%    |
| InnoLux Display         | 1         | 0.4%    |
| CS_                     | 1         | 0.4%    |
| CMN                     | 1         | 0.4%    |
| BenQ                    | 1         | 0.4%    |
| ASUSTek Computer        | 1         | 0.4%    |
| AOC                     | 1         | 0.4%    |
| Ancor Communications    | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 6         | 2.43%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch          | 4         | 1.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 3         | 1.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 3         | 1.21%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                 | 3         | 1.21%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 3         | 1.21%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 3         | 1.21%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 2         | 0.81%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 2         | 0.81%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch              | 2         | 0.81%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 2         | 0.81%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                 | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 2         | 0.81%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                | 2         | 0.81%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.81%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                 | 2         | 0.81%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.81%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch        | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch        | 2         | 0.81%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 2         | 0.81%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch               | 2         | 0.81%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 2         | 0.81%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch        | 1         | 0.4%    |
| Toshiba TV TSB0212 3840x2160                                         | 1         | 0.4%    |
| Toshiba TV TSB0108 1280x1024 708x398mm 32.0-inch                     | 1         | 0.4%    |
| Toshiba LCD Monitor LCD5860 1280x800 261x163mm 12.1-inch             | 1         | 0.4%    |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch             | 1         | 0.4%    |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch              | 1         | 0.4%    |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch              | 1         | 0.4%    |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch              | 1         | 0.4%    |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch              | 1         | 0.4%    |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch              | 1         | 0.4%    |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 113       | 46.5%   |
| 1920x1080 (FHD)    | 54        | 22.22%  |
| 1280x800 (WXGA)    | 26        | 10.7%   |
| 1600x900 (HD+)     | 20        | 8.23%   |
| 3840x2160 (4K)     | 7         | 2.88%   |
| 2560x1440 (QHD)    | 4         | 1.65%   |
| 1440x900 (WXGA+)   | 3         | 1.23%   |
| 3200x1800 (QHD+)   | 2         | 0.82%   |
| 2160x1440          | 2         | 0.82%   |
| 1920x1200 (WUXGA)  | 2         | 0.82%   |
| 1680x1050 (WSXGA+) | 2         | 0.82%   |
| 1024x600           | 2         | 0.82%   |
| 3000x2000          | 1         | 0.41%   |
| 2560x1080          | 1         | 0.41%   |
| 1920x540           | 1         | 0.41%   |
| 1528x1222          | 1         | 0.41%   |
| 1360x768           | 1         | 0.41%   |
| 1280x1024 (SXGA)   | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 85        | 34.41%  |
| 14      | 38        | 15.38%  |
| 13      | 35        | 14.17%  |
| 17      | 21        | 8.5%    |
| 11      | 21        | 8.5%    |
| 12      | 12        | 4.86%   |
| 27      | 4         | 1.62%   |
| 24      | 4         | 1.62%   |
| 10      | 4         | 1.62%   |
| 23      | 3         | 1.21%   |
| 21      | 3         | 1.21%   |
| 19      | 3         | 1.21%   |
| 84      | 2         | 0.81%   |
| 72      | 2         | 0.81%   |
| 28      | 2         | 0.81%   |
| Unknown | 2         | 0.81%   |
| 54      | 1         | 0.4%    |
| 44      | 1         | 0.4%    |
| 22      | 1         | 0.4%    |
| 18      | 1         | 0.4%    |
| 16      | 1         | 0.4%    |
| 9       | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 140       | 56.91%  |
| 201-300     | 54        | 21.95%  |
| 351-400     | 23        | 9.35%   |
| 501-600     | 10        | 4.07%   |
| 401-500     | 7         | 2.85%   |
| 1501-2000   | 4         | 1.63%   |
| 601-700     | 3         | 1.22%   |
| Unknown     | 2         | 0.81%   |
| 101-200     | 1         | 0.41%   |
| 1001-1500   | 1         | 0.41%   |
| 901-1000    | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 187       | 82.02%  |
| 16/10   | 32        | 14.04%  |
| 3/2     | 5         | 2.19%   |
| 5/4     | 1         | 0.44%   |
| 4/3     | 1         | 0.44%   |
| 21/9    | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 85        | 34.41%  |
| 81-90          | 67        | 27.13%  |
| 51-60          | 21        | 8.5%    |
| 121-130        | 20        | 8.1%    |
| 61-70          | 12        | 4.86%   |
| 201-250        | 9         | 3.64%   |
| 71-80          | 6         | 2.43%   |
| More than 1000 | 5         | 2.02%   |
| 41-50          | 5         | 2.02%   |
| 301-350        | 4         | 1.62%   |
| 251-300        | 3         | 1.21%   |
| 151-200        | 3         | 1.21%   |
| 131-140        | 2         | 0.81%   |
| Unknown        | 2         | 0.81%   |
| 351-500        | 1         | 0.4%    |
| 141-150        | 1         | 0.4%    |
| 501-1000       | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 119       | 48.97%  |
| 121-160       | 77        | 31.69%  |
| 51-100        | 29        | 11.93%  |
| 161-240       | 10        | 4.12%   |
| More than 240 | 3         | 1.23%   |
| 1-50          | 3         | 1.23%   |
| Unknown       | 2         | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 214       | 88.43%  |
| 2     | 22        | 9.09%   |
| 0     | 5         | 2.07%   |
| 3     | 1         | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 119       | 32.6%   |
| Intel                             | 92        | 25.21%  |
| Qualcomm Atheros                  | 59        | 16.16%  |
| Broadcom                          | 30        | 8.22%   |
| Marvell Technology Group          | 9         | 2.47%   |
| Samsung Electronics               | 6         | 1.64%   |
| Ralink                            | 6         | 1.64%   |
| MediaTek                          | 6         | 1.64%   |
| Ralink Technology                 | 4         | 1.1%    |
| Broadcom Limited                  | 4         | 1.1%    |
| ASIX Electronics                  | 4         | 1.1%    |
| TP-Link                           | 3         | 0.82%   |
| OPPO Electronics                  | 3         | 0.82%   |
| Xiaomi                            | 2         | 0.55%   |
| Qualcomm Atheros Communications   | 2         | 0.55%   |
| Qualcomm                          | 2         | 0.55%   |
| Nvidia                            | 2         | 0.55%   |
| Spreadtrum Communications         | 1         | 0.27%   |
| Sierra Wireless                   | 1         | 0.27%   |
| NetGear                           | 1         | 0.27%   |
| Motorola PCS                      | 1         | 0.27%   |
| Microsoft                         | 1         | 0.27%   |
| Micro Star International          | 1         | 0.27%   |
| JMicron Technology                | 1         | 0.27%   |
| ICS Advent                        | 1         | 0.27%   |
| Ericsson Business Mobile Networks | 1         | 0.27%   |
| Dresden Elektronik                | 1         | 0.27%   |
| Dell                              | 1         | 0.27%   |
| ASUSTek Computer                  | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49        | 11.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 7.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 2.51%   |
| Intel Wireless 7260                                               | 11        | 2.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 2.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 2.28%   |
| Intel Wireless 7265                                               | 10        | 2.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 1.37%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 1.14%   |
| Realtek 802.11n WLAN Adapter                                      | 5         | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.91%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4         | 0.91%   |
| Intel Wireless 8265 / 8275                                        | 4         | 0.91%   |
| Intel Wireless 3165                                               | 4         | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 4         | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.91%   |
| Intel Centrino Wireless-N 2230                                    | 4         | 0.91%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 0.91%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.68%   |
| OPPO SM8350-IDP _SN:27BAACC8                                      | 3         | 0.68%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                 | 3         | 0.68%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.68%   |
| Intel Wireless 3160                                               | 3         | 0.68%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.68%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.68%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 86        | 36.6%   |
| Qualcomm Atheros                  | 51        | 21.7%   |
| Realtek Semiconductor             | 48        | 20.43%  |
| Broadcom                          | 21        | 8.94%   |
| Ralink                            | 6         | 2.55%   |
| MediaTek                          | 6         | 2.55%   |
| Ralink Technology                 | 4         | 1.7%    |
| TP-Link                           | 2         | 0.85%   |
| Qualcomm Atheros Communications   | 2         | 0.85%   |
| Broadcom Limited                  | 2         | 0.85%   |
| Sierra Wireless                   | 1         | 0.43%   |
| NetGear                           | 1         | 0.43%   |
| Microsoft                         | 1         | 0.43%   |
| Micro Star International          | 1         | 0.43%   |
| Ericsson Business Mobile Networks | 1         | 0.43%   |
| Dell                              | 1         | 0.43%   |
| ASUSTek Computer                  | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 4.64%   |
| Intel Wireless 7260                                            | 11        | 4.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 4.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 4.22%   |
| Intel Wireless 7265                                            | 10        | 4.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 3.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 2.95%   |
| Realtek 802.11n WLAN Adapter                                   | 5         | 2.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 2.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 1.69%   |
| Intel Wireless 8265 / 8275                                     | 4         | 1.69%   |
| Intel Wireless 3165                                            | 4         | 1.69%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 4         | 1.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 1.69%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 1.69%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 1.69%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.27%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 3         | 1.27%   |
| Intel Wireless 3160                                            | 3         | 1.27%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.27%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.27%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.27%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.84%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.84%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.84%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 0.84%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.84%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 97        | 48.74%  |
| Intel                     | 35        | 17.59%  |
| Qualcomm Atheros          | 19        | 9.55%   |
| Broadcom                  | 14        | 7.04%   |
| Marvell Technology Group  | 9         | 4.52%   |
| Samsung Electronics       | 5         | 2.51%   |
| ASIX Electronics          | 4         | 2.01%   |
| OPPO Electronics          | 3         | 1.51%   |
| Xiaomi                    | 2         | 1.01%   |
| Qualcomm                  | 2         | 1.01%   |
| Nvidia                    | 2         | 1.01%   |
| Broadcom Limited          | 2         | 1.01%   |
| TP-Link                   | 1         | 0.5%    |
| Spreadtrum Communications | 1         | 0.5%    |
| Motorola PCS              | 1         | 0.5%    |
| JMicron Technology        | 1         | 0.5%    |
| ICS Advent                | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49        | 24.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 17%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 3%      |
| Intel 82577LM Gigabit Network Connection                          | 6         | 3%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 2.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 2%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 2%      |
| OPPO SM8350-IDP _SN:27BAACC8                                      | 3         | 1.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 1.5%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.5%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1%      |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1%      |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1%      |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1%      |
| Intel Ethernet Connection I219-LM                                 | 2         | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1%      |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1%      |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 1%      |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.5%    |
| Spreadtrum Unisoc Phone                                           | 1         | 0.5%    |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.5%    |
| Qualcomm FP3                                                      | 1         | 0.5%    |
| Qualcomm CAPE-MTP _SN:14677F87                                    | 1         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.5%    |
| Nvidia MCP89 Ethernet                                             | 1         | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.5%    |
| Motorola PCS motorola edge 40                                     | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 220       | 54.19%  |
| Ethernet | 184       | 45.32%  |
| Modem    | 2         | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 167       | 71.06%  |
| Ethernet | 68        | 28.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 155       | 64.32%  |
| 1     | 58        | 24.07%  |
| 0     | 26        | 10.79%  |
| 3     | 2         | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 183       | 75.31%  |
| Yes  | 60        | 24.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 34.78%  |
| Realtek Semiconductor           | 25        | 15.53%  |
| Qualcomm Atheros Communications | 19        | 11.8%   |
| Broadcom                        | 11        | 6.83%   |
| Lite-On Technology              | 8         | 4.97%   |
| IMC Networks                    | 8         | 4.97%   |
| Apple                           | 7         | 4.35%   |
| Foxconn / Hon Hai               | 5         | 3.11%   |
| Ralink                          | 4         | 2.48%   |
| Hewlett-Packard                 | 4         | 2.48%   |
| Dell                            | 4         | 2.48%   |
| Cambridge Silicon Radio         | 3         | 1.86%   |
| Toshiba                         | 2         | 1.24%   |
| Alps Electric                   | 2         | 1.24%   |
| Syntek                          | 1         | 0.62%   |
| MediaTek                        | 1         | 0.62%   |
| ASUSTek Computer                | 1         | 0.62%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 34        | 20.99%  |
| Realtek Bluetooth Radio                                                             | 17        | 10.49%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 5.56%   |
| Intel Bluetooth Device                                                              | 7         | 4.32%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 3.09%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 3.09%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 2.47%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 2.47%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 2.47%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.47%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.85%   |
| Intel AX200 Bluetooth                                                               | 3         | 1.85%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 1.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.23%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.23%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.23%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.23%   |
| Apple Bluetooth HCI                                                                 | 2         | 1.23%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.62%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.62%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 0.62%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.62%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.62%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.62%   |
| MediaTek Wireless_Device                                                            | 1         | 0.62%   |
| Lite-On Wireless_Device                                                             | 1         | 0.62%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.62%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.62%   |
| Lite-On BCM20702A0                                                                  | 1         | 0.62%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.62%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.62%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.62%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.62%   |
| IMC Networks Bluetooth                                                              | 1         | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 184       | 74.19%  |
| AMD                  | 39        | 15.73%  |
| Nvidia               | 19        | 7.66%   |
| MosArt Semiconductor | 1         | 0.4%    |
| JMTek                | 1         | 0.4%    |
| GN Netcom            | 1         | 0.4%    |
| EGO SYStems          | 1         | 0.4%    |
| C-Media Electronics  | 1         | 0.4%    |
| ASUSTek Computer     | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 30        | 10.1%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 16        | 5.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 5.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 4.71%   |
| AMD FCH Azalia Controller                                                                         | 14        | 4.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 4.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 4.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 3.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 3.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 3.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 3.03%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 3.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.69%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.36%   |
| AMD High Definition Audio Controller                                                              | 7         | 2.36%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 2.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 2.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.68%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.35%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 1.35%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 1.35%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.01%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 1.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.01%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.01%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 1.01%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.67%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.67%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 24.06%  |
| SK hynix            | 42        | 22.46%  |
| Unknown             | 21        | 11.23%  |
| Micron Technology   | 20        | 10.7%   |
| Unknown (ABCD)      | 8         | 4.28%   |
| Kingston            | 8         | 4.28%   |
| Nanya Technology    | 7         | 3.74%   |
| Elpida              | 7         | 3.74%   |
| Ramaxel Technology  | 3         | 1.6%    |
| A-DATA Technology   | 3         | 1.6%    |
| Unknown             | 3         | 1.6%    |
| Smart               | 2         | 1.07%   |
| fef5                | 2         | 1.07%   |
| Crucial             | 2         | 1.07%   |
| Corsair             | 2         | 1.07%   |
| Wilk                | 1         | 0.53%   |
| Transcend           | 1         | 0.53%   |
| Toshiba             | 1         | 0.53%   |
| TakeMS              | 1         | 0.53%   |
| PUSKILL             | 1         | 0.53%   |
| Novatech            | 1         | 0.53%   |
| Kllisre             | 1         | 0.53%   |
| Kingmax             | 1         | 0.53%   |
| HMD                 | 1         | 0.53%   |
| G.Skill             | 1         | 0.53%   |
| Apacer              | 1         | 0.53%   |
| AMD                 | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 3.48%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 2.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 4         | 1.99%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 1.99%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.99%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 4         | 1.99%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.99%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 3         | 1.49%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 1.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.49%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4096MB SODIMM DDR3 1600MT/s          | 3         | 1.49%   |
| Unknown                                                          | 3         | 1.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 1%      |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 1%      |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1%      |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 2         | 1%      |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 1%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1%      |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 2         | 1%      |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 2         | 1%      |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 1%      |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 1%      |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 1%      |
| Elpida RAM EBJ20UF8BDU0-GN-F 2048MB SODIMM DDR3 1600MT/s         | 2         | 1%      |
| Wilk RAM GR3200S464L22S/8G 8GB SODIMM DDR4 3200MT/s              | 1         | 0.5%    |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.5%    |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.5%    |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2                        | 1         | 0.5%    |
| Toshiba RAM 8HTF12864HDY-800G1 1GB SODIMM 1066MT/s               | 1         | 0.5%    |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 0.5%    |
| TakeMS RAM TMS2GS264D081665EE 2GB SODIMM DDR2 667MT/s            | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 84        | 50.6%   |
| DDR4    | 37        | 22.29%  |
| LPDDR4  | 15        | 9.04%   |
| DDR2    | 14        | 8.43%   |
| SDRAM   | 5         | 3.01%   |
| LPDDR5  | 5         | 3.01%   |
| LPDDR3  | 2         | 1.2%    |
| DDR5    | 2         | 1.2%    |
| Unknown | 2         | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 142       | 87.65%  |
| Row Of Chips | 12        | 7.41%   |
| Unknown      | 5         | 3.09%   |
| DIMM         | 3         | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 58        | 32.22%  |
| 8192  | 51        | 28.33%  |
| 2048  | 48        | 26.67%  |
| 1024  | 13        | 7.22%   |
| 16384 | 7         | 3.89%   |
| 32768 | 2         | 1.11%   |
| 512   | 1         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 56        | 32.18%  |
| 2400    | 18        | 10.34%  |
| 3200    | 16        | 9.2%    |
| 1333    | 13        | 7.47%   |
| 667     | 11        | 6.32%   |
| 1334    | 10        | 5.75%   |
| 2667    | 8         | 4.6%    |
| 1066    | 7         | 4.02%   |
| 6400    | 4         | 2.3%    |
| 3266    | 4         | 2.3%    |
| 1067    | 4         | 2.3%    |
| 2048    | 3         | 1.72%   |
| 1866    | 3         | 1.72%   |
| Unknown | 3         | 1.72%   |
| 4800    | 2         | 1.15%   |
| 4267    | 2         | 1.15%   |
| 2133    | 2         | 1.15%   |
| 975     | 2         | 1.15%   |
| 5500    | 1         | 0.57%   |
| 4199    | 1         | 0.57%   |
| 2933    | 1         | 0.57%   |
| 1867    | 1         | 0.57%   |
| 800     | 1         | 0.57%   |
| 533     | 1         | 0.57%   |

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
| Chicony Electronics                    | 53        | 27.46%  |
| Realtek Semiconductor                  | 20        | 10.36%  |
| Microdia                               | 19        | 9.84%   |
| Sunplus Innovation Technology          | 12        | 6.22%   |
| Syntek                                 | 11        | 5.7%    |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.15%   |
| Suyin                                  | 7         | 3.63%   |
| Apple                                  | 7         | 3.63%   |
| IMC Networks                           | 6         | 3.11%   |
| Bison Electronics                      | 6         | 3.11%   |
| Alcor Micro                            | 6         | 3.11%   |
| Quanta                                 | 5         | 2.59%   |
| Lite-On Technology                     | 5         | 2.59%   |
| ALi                                    | 4         | 2.07%   |
| Silicon Motion                         | 3         | 1.55%   |
| Lenovo                                 | 3         | 1.55%   |
| Z-Star Microelectronics                | 2         | 1.04%   |
| USB Camera CS                          | 2         | 1.04%   |
| icSpring                               | 2         | 1.04%   |
| GEMBIRD                                | 2         | 1.04%   |
| Acer                                   | 2         | 1.04%   |
| Y Media                                | 1         | 0.52%   |
| SunplusIT                              | 1         | 0.52%   |
| Sonix Technology                       | 1         | 0.52%   |
| Ricoh                                  | 1         | 0.52%   |
| Luxvisions Innotech Limited            | 1         | 0.52%   |
| Logitech                               | 1         | 0.52%   |
| Cubeternet                             | 1         | 0.52%   |
| BKX-Usb2.0 2MP Camera                  | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 10        | 5.15%   |
| Chicony HP TrueVision HD Camera                         | 6         | 3.09%   |
| Alcor Micro USB 2.0 Camera                              | 6         | 3.09%   |
| Sunplus HD WebCam                                       | 5         | 2.58%   |
| Microdia Integrated Webcam                              | 4         | 2.06%   |
| Chicony HD WebCam                                       | 4         | 2.06%   |
| Syntek USB Camera Device                                | 3         | 1.55%   |
| Syntek Lenovo EasyCamera                                | 3         | 1.55%   |
| Realtek USB Camera                                      | 3         | 1.55%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.55%   |
| Microdia Integrated_Webcam_HD                           | 3         | 1.55%   |
| Chicony VGA WebCam                                      | 3         | 1.55%   |
| Chicony HP Truevision HD                                | 3         | 1.55%   |
| Chicony ACER HD User Facing                             | 3         | 1.55%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 3         | 1.55%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.55%   |
| Apple FaceTime HD Camera                                | 3         | 1.55%   |
| ALi WebCam                                              | 3         | 1.55%   |
| Z-Star Webcam                                           | 2         | 1.03%   |
| USB Camera CS USB Camera CS                             | 2         | 1.03%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.03%   |
| Silicon Motion 300k Pixel Camera                        | 2         | 1.03%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.03%   |
| Realtek Integrated Webcam HD                            | 2         | 1.03%   |
| Realtek HP Truevision HD                                | 2         | 1.03%   |
| Realtek EasyCamera                                      | 2         | 1.03%   |
| Realtek Asus laptop camera                              | 2         | 1.03%   |
| Microdia Lenovo EasyCamera                              | 2         | 1.03%   |
| Microdia HP Webcam-50                                   | 2         | 1.03%   |
| Lenovo Integrated Webcam                                | 2         | 1.03%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 2         | 1.03%   |
| icSpring camera                                         | 2         | 1.03%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]       | 2         | 1.03%   |
| Chicony HP HD Webcam                                    | 2         | 1.03%   |
| Chicony FJ Camera                                       | 2         | 1.03%   |
| Chicony EasyCamera                                      | 2         | 1.03%   |
| Chicony 720p HD Camera                                  | 2         | 1.03%   |
| Bison Lenovo EasyCamera                                 | 2         | 1.03%   |
| Apple iPhone 5/5C/5S/6/SE                               | 2         | 1.03%   |
| Y Media USB Camera                                      | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 33.33%  |
| Upek                       | 5         | 23.81%  |
| AuthenTec                  | 4         | 19.05%  |
| STMicroelectronics         | 2         | 9.52%   |
| Shenzhen Goodix Technology | 2         | 9.52%   |
| LighTuning Technology      | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 5         | 23.81%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 9.52%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 9.52%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 9.52%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 9.52%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 4.76%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.76%   |
| AuthenTec Fingerprint Sensor                           | 1         | 4.76%   |
| AuthenTec AES2810                                      | 1         | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4.76%   |
| AuthenTec AES1600                                      | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 42.86%  |
| Alcor Micro           | 5         | 35.71%  |
| O2 Micro              | 1         | 7.14%   |
| Lenovo                | 1         | 7.14%   |
| Gemalto (was Gemplus) | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader              | 4         | 28.57%  |
| Broadcom 5880                                    | 3         | 21.43%  |
| Broadcom BCM5880 Secure Applications Processor   | 2         | 14.29%  |
| O2 Micro OZ776 CCID Smartcard Reader             | 1         | 7.14%   |
| Lenovo Integrated Smart Card Reader              | 1         | 7.14%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader | 1         | 7.14%   |
| Broadcom 58200                                   | 1         | 7.14%   |
| Alcor Micro Watchdata W 1981                     | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 178       | 73.86%  |
| 1     | 53        | 21.99%  |
| 2     | 8         | 3.32%   |
| 4     | 1         | 0.41%   |
| 3     | 1         | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 20        | 27.03%  |
| Chipcard              | 13        | 17.57%  |
| Graphics card         | 12        | 16.22%  |
| Bluetooth             | 7         | 9.46%   |
| Net/wireless          | 6         | 8.11%   |
| Camera                | 6         | 8.11%   |
| Dvb card              | 3         | 4.05%   |
| Storage               | 2         | 2.7%    |
| Network               | 2         | 2.7%    |
| Multimedia controller | 2         | 2.7%    |
| Net/ethernet          | 1         | 1.35%   |

