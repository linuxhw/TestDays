MX 21 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for MX 21.

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

Total: 374

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 3400                 | [cd1ed35419](https://linux-hardware.org/?probe=cd1ed35419) | May 02, 2024 |
| Lenovo        | ThinkPad E560 20EV0011GE    | [38ab585e58](https://linux-hardware.org/?probe=38ab585e58) | Apr 27, 2024 |
| HP            | 255 G1                      | [edea4d298e](https://linux-hardware.org/?probe=edea4d298e) | Apr 15, 2024 |
| Apple         | MacBook4,1                  | [d6304d794d](https://linux-hardware.org/?probe=d6304d794d) | Apr 11, 2024 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a31a3d60b1](https://linux-hardware.org/?probe=a31a3d60b1) | Apr 01, 2024 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [ce4f787af2](https://linux-hardware.org/?probe=ce4f787af2) | Apr 01, 2024 |
| Acer          | Aspire E5-421G              | [f16af02ed4](https://linux-hardware.org/?probe=f16af02ed4) | Mar 26, 2024 |
| HP            | Laptop 15-db0xxx            | [904ac30154](https://linux-hardware.org/?probe=904ac30154) | Mar 23, 2024 |
| HP            | 255 G1                      | [097c812445](https://linux-hardware.org/?probe=097c812445) | Mar 16, 2024 |
| HP            | 620                         | [b5df7d8db3](https://linux-hardware.org/?probe=b5df7d8db3) | Mar 12, 2024 |
| HP            | 650                         | [96c8acc1a4](https://linux-hardware.org/?probe=96c8acc1a4) | Mar 11, 2024 |
| HP            | Compaq nc6320 (RU397EA#A... | [edd727d30d](https://linux-hardware.org/?probe=edd727d30d) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480 20L6003PFR    | [d6ded6d32a](https://linux-hardware.org/?probe=d6ded6d32a) | Mar 03, 2024 |
| Dell          | System Inspiron N7110       | [6c1eb8d628](https://linux-hardware.org/?probe=6c1eb8d628) | Mar 02, 2024 |
| Dell          | Latitude E5540              | [9103e34326](https://linux-hardware.org/?probe=9103e34326) | Feb 17, 2024 |
| LG Electro... | 17Z90N-V.BJ51P1             | [df1bbe4be6](https://linux-hardware.org/?probe=df1bbe4be6) | Feb 10, 2024 |
| Acer          | Aspire A515-43              | [68a2707c3f](https://linux-hardware.org/?probe=68a2707c3f) | Dec 31, 2023 |
| Lenovo        | ThinkPad T460 20FMS0W32L    | [55200b6aa5](https://linux-hardware.org/?probe=55200b6aa5) | Dec 26, 2023 |
| Lenovo        | ThinkPad T500 20552CU       | [7389e9e37c](https://linux-hardware.org/?probe=7389e9e37c) | Nov 21, 2023 |
| HP            | Compaq 6730s                | [073756d958](https://linux-hardware.org/?probe=073756d958) | Nov 03, 2023 |
| Acer          | Aspire A315-56              | [2de4949247](https://linux-hardware.org/?probe=2de4949247) | Nov 01, 2023 |
| Lenovo        | V17 G2 ITL 82NX             | [d267711f7e](https://linux-hardware.org/?probe=d267711f7e) | Nov 01, 2023 |
| AMI           | Intel                       | [42ebe1755f](https://linux-hardware.org/?probe=42ebe1755f) | Oct 30, 2023 |
| Acer          | Extensa 2519                | [4d8970a1f5](https://linux-hardware.org/?probe=4d8970a1f5) | Oct 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [20c026b8a7](https://linux-hardware.org/?probe=20c026b8a7) | Oct 16, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [da0024090d](https://linux-hardware.org/?probe=da0024090d) | Oct 16, 2023 |
| Apple         | MacBookAir5,1               | [e4f9055fce](https://linux-hardware.org/?probe=e4f9055fce) | Oct 09, 2023 |
| Notebook      | NL5xNU                      | [d5e4f28683](https://linux-hardware.org/?probe=d5e4f28683) | Oct 02, 2023 |
| Fujitsu Si... | AMILO A1650G                | [ec61a60044](https://linux-hardware.org/?probe=ec61a60044) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c00e994c2c](https://linux-hardware.org/?probe=c00e994c2c) | Sep 21, 2023 |
| HP            | 620                         | [6fd1497e1a](https://linux-hardware.org/?probe=6fd1497e1a) | Sep 10, 2023 |
| HP            | EliteBook 840 G2            | [c8cc960675](https://linux-hardware.org/?probe=c8cc960675) | Aug 21, 2023 |
| Notebook      | NL5xNU                      | [768e7b97fc](https://linux-hardware.org/?probe=768e7b97fc) | Aug 19, 2023 |
| Dell          | Latitude E5410              | [4ae8d448a2](https://linux-hardware.org/?probe=4ae8d448a2) | Aug 14, 2023 |
| HP            | 250 G8 Notebook PC          | [64a738d034](https://linux-hardware.org/?probe=64a738d034) | Aug 13, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [482b97d3de](https://linux-hardware.org/?probe=482b97d3de) | Aug 02, 2023 |
| HP            | 620                         | [4c04d9d11e](https://linux-hardware.org/?probe=4c04d9d11e) | Aug 01, 2023 |
| HP            | 620                         | [eafc7ac5c3](https://linux-hardware.org/?probe=eafc7ac5c3) | Aug 01, 2023 |
| Acer          | Aspire E1-532               | [9042ebc249](https://linux-hardware.org/?probe=9042ebc249) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | [f84a39b436](https://linux-hardware.org/?probe=f84a39b436) | Jul 31, 2023 |
| Acer          | Aspire V3-571G              | [88f60930be](https://linux-hardware.org/?probe=88f60930be) | Jul 26, 2023 |
| Dell          | Inspiron 13-5378            | [fd43074149](https://linux-hardware.org/?probe=fd43074149) | Jul 26, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [31c0d94d23](https://linux-hardware.org/?probe=31c0d94d23) | Jul 18, 2023 |
| CONNEX        | L1415-BAY                   | [8f5663e9c8](https://linux-hardware.org/?probe=8f5663e9c8) | Jul 18, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [18f41b2be6](https://linux-hardware.org/?probe=18f41b2be6) | Jul 17, 2023 |
| HP            | Laptop 15-fc0xxx            | [782127b6f6](https://linux-hardware.org/?probe=782127b6f6) | Jul 17, 2023 |
| Acer          | Aspire 4750                 | [d1ef43e488](https://linux-hardware.org/?probe=d1ef43e488) | Jul 16, 2023 |
| Dell          | System XPS L502X            | [e6b4c3cf4e](https://linux-hardware.org/?probe=e6b4c3cf4e) | Jul 12, 2023 |
| Acer          | Aspire ES1-511              | [1e7434d3b0](https://linux-hardware.org/?probe=1e7434d3b0) | Jul 10, 2023 |
| HP            | 620                         | [5f88c564fd](https://linux-hardware.org/?probe=5f88c564fd) | Jul 08, 2023 |
| Acer          | Aspire A515-47              | [ab21b766b6](https://linux-hardware.org/?probe=ab21b766b6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | [5bba6eb442](https://linux-hardware.org/?probe=5bba6eb442) | Jul 07, 2023 |
| ASUSTek       | GL703VD                     | [68235880f7](https://linux-hardware.org/?probe=68235880f7) | Jul 06, 2023 |
| Alienware     | m16 R1 AMD                  | [291c477bd0](https://linux-hardware.org/?probe=291c477bd0) | Jul 01, 2023 |
| ASUSTek       | X201EV                      | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| Acer          | Aspire E5-573               | [cd65c92d12](https://linux-hardware.org/?probe=cd65c92d12) | Jun 27, 2023 |
| Acer          | Aspire E5-573               | [e3b1cdc71c](https://linux-hardware.org/?probe=e3b1cdc71c) | Jun 27, 2023 |
| HP            | ProBook 450 G1              | [cadc656340](https://linux-hardware.org/?probe=cadc656340) | Jun 25, 2023 |
| Dell          | Latitude E6510              | [a85838194d](https://linux-hardware.org/?probe=a85838194d) | Jun 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [ed43d5454c](https://linux-hardware.org/?probe=ed43d5454c) | Jun 18, 2023 |
| Dell          | Latitude 3190               | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| HP            | Laptop 15-dw1xxx            | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| Dell          | Latitude E6540              | [85520c9a0b](https://linux-hardware.org/?probe=85520c9a0b) | Jun 08, 2023 |
| Dell          | Latitude E6540              | [30f20f78ac](https://linux-hardware.org/?probe=30f20f78ac) | Jun 08, 2023 |
| ASUSTek       | X205TA                      | [4c56663011](https://linux-hardware.org/?probe=4c56663011) | Jun 07, 2023 |
| Dell          | Latitude 3190               | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Dell          | Latitude E6510              | [49743c8db7](https://linux-hardware.org/?probe=49743c8db7) | Jun 04, 2023 |
| Dell          | Latitude E6510              | [51c45b0aa7](https://linux-hardware.org/?probe=51c45b0aa7) | Jun 04, 2023 |
| MSI           | U200                        | [01900b8117](https://linux-hardware.org/?probe=01900b8117) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [51d10ac11e](https://linux-hardware.org/?probe=51d10ac11e) | Jun 02, 2023 |
| HP            | EliteBook 8460p             | [c46684adac](https://linux-hardware.org/?probe=c46684adac) | Jun 02, 2023 |
| Dell          | Latitude 5540               | [98ec8ec8bf](https://linux-hardware.org/?probe=98ec8ec8bf) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | [4a2e70149f](https://linux-hardware.org/?probe=4a2e70149f) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | [b8fb5e55bc](https://linux-hardware.org/?probe=b8fb5e55bc) | Jun 01, 2023 |
| Unknown       | Unknown                     | [351ca28b27](https://linux-hardware.org/?probe=351ca28b27) | May 29, 2023 |
| Dell          | Latitude 3190               | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | [d83ee3fda2](https://linux-hardware.org/?probe=d83ee3fda2) | May 28, 2023 |
| Dell          | Latitude E6510              | [9edaeb2ffa](https://linux-hardware.org/?probe=9edaeb2ffa) | May 25, 2023 |
| Sony          | SVE1513Q1ESI                | [422e8954f2](https://linux-hardware.org/?probe=422e8954f2) | May 24, 2023 |
| Casper        | EXCALIBUR G770              | [ef088af2df](https://linux-hardware.org/?probe=ef088af2df) | May 23, 2023 |
| HUAWEI        | HLYL-WXX9                   | [28a8978593](https://linux-hardware.org/?probe=28a8978593) | May 22, 2023 |
| Dell          | Latitude 3190               | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| Dell          | Latitude E6510              | [342b8d094e](https://linux-hardware.org/?probe=342b8d094e) | May 20, 2023 |
| Dell          | Latitude E6510              | [4d606396f8](https://linux-hardware.org/?probe=4d606396f8) | May 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e6746606b4](https://linux-hardware.org/?probe=e6746606b4) | May 19, 2023 |
| Dell          | Latitude 3190               | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Acer          | Aspire A315-59              | [4c33c99aab](https://linux-hardware.org/?probe=4c33c99aab) | May 14, 2023 |
| ASUSTek       | X202E                       | [d6b7617a17](https://linux-hardware.org/?probe=d6b7617a17) | May 14, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [08afd40365](https://linux-hardware.org/?probe=08afd40365) | May 13, 2023 |
| Acer          | Extensa 5220                | [935b52f12c](https://linux-hardware.org/?probe=935b52f12c) | May 12, 2023 |
| Acer          | Aspire 5715Z                | [81c255952d](https://linux-hardware.org/?probe=81c255952d) | May 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0GK0... | [177f30243c](https://linux-hardware.org/?probe=177f30243c) | May 08, 2023 |
| Dell          | Latitude 3190               | [fb4df1325b](https://linux-hardware.org/?probe=fb4df1325b) | May 08, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [af9c3172bc](https://linux-hardware.org/?probe=af9c3172bc) | May 05, 2023 |
| HP            | Pro Tablet 10 EE G1         | [6af53fb237](https://linux-hardware.org/?probe=6af53fb237) | May 05, 2023 |
| Lenovo        | ThinkPad T460s 20F9003GU... | [7a570efe74](https://linux-hardware.org/?probe=7a570efe74) | May 05, 2023 |
| Apple         | MacBookPro7,1               | [8349b363f4](https://linux-hardware.org/?probe=8349b363f4) | May 03, 2023 |
| Apple         | MacBookPro7,1               | [49971d9c29](https://linux-hardware.org/?probe=49971d9c29) | May 03, 2023 |
| Apple         | MacBookAir3,1               | [97d802a5d6](https://linux-hardware.org/?probe=97d802a5d6) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [6d2d5b74d2](https://linux-hardware.org/?probe=6d2d5b74d2) | May 03, 2023 |
| Lenovo        | ThinkPad X260 20F5S89L02    | [4e2f57ccc3](https://linux-hardware.org/?probe=4e2f57ccc3) | May 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [a36c4e671d](https://linux-hardware.org/?probe=a36c4e671d) | May 02, 2023 |
| Dell          | Latitude 3190               | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Apple         | MacBookPro6,2               | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [539369db0e](https://linux-hardware.org/?probe=539369db0e) | Apr 28, 2023 |
| HP            | EliteBook 6930p             | [014215365a](https://linux-hardware.org/?probe=014215365a) | Apr 27, 2023 |
| Dell          | Latitude 3190               | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| HP            | G42                         | [58b0a0981e](https://linux-hardware.org/?probe=58b0a0981e) | Apr 23, 2023 |
| Compal        | HEL81I                      | [426788b00c](https://linux-hardware.org/?probe=426788b00c) | Apr 22, 2023 |
| Google        | Akali 360                   | [2d18714bb2](https://linux-hardware.org/?probe=2d18714bb2) | Apr 20, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1B30... | [c0207e5f9a](https://linux-hardware.org/?probe=c0207e5f9a) | Apr 19, 2023 |
| HP            | Laptop 17-cn0xxx            | [843dd1e105](https://linux-hardware.org/?probe=843dd1e105) | Apr 18, 2023 |
| ASUSTek       | 1015PX                      | [c271ba95b9](https://linux-hardware.org/?probe=c271ba95b9) | Apr 16, 2023 |
| ASUSTek       | 1015PX                      | [494fc3e648](https://linux-hardware.org/?probe=494fc3e648) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [aa571700ad](https://linux-hardware.org/?probe=aa571700ad) | Apr 13, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | [3d53b9ee9e](https://linux-hardware.org/?probe=3d53b9ee9e) | Apr 12, 2023 |
| Dell          | Latitude 3190               | [c2a70674ac](https://linux-hardware.org/?probe=c2a70674ac) | Apr 10, 2023 |
| Lenovo        | ThinkPad X220 4290WC7       | [07ed4faaa0](https://linux-hardware.org/?probe=07ed4faaa0) | Apr 10, 2023 |
| Dell          | Latitude 3190               | [a1fa664431](https://linux-hardware.org/?probe=a1fa664431) | Apr 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9a5c9ee256](https://linux-hardware.org/?probe=9a5c9ee256) | Apr 02, 2023 |
| Sony          | VPCCB32FD                   | [ef684c34bb](https://linux-hardware.org/?probe=ef684c34bb) | Mar 28, 2023 |
| Dell          | Latitude 3190               | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| Sony          | VPCCB32FD                   | [20d8516896](https://linux-hardware.org/?probe=20d8516896) | Mar 26, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [498bb39808](https://linux-hardware.org/?probe=498bb39808) | Mar 24, 2023 |
| Acer          | Aspire F5-573G              | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| Dell          | Latitude 3190               | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [978df2886a](https://linux-hardware.org/?probe=978df2886a) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ac5495bdb4](https://linux-hardware.org/?probe=ac5495bdb4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [45d6f54263](https://linux-hardware.org/?probe=45d6f54263) | Mar 19, 2023 |
| Dell          | Latitude E5570              | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [9f3f315f73](https://linux-hardware.org/?probe=9f3f315f73) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [42653f8c2a](https://linux-hardware.org/?probe=42653f8c2a) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [7ccc0f584e](https://linux-hardware.org/?probe=7ccc0f584e) | Mar 14, 2023 |
| Dell          | Latitude 3190               | [97cc3ffc79](https://linux-hardware.org/?probe=97cc3ffc79) | Mar 13, 2023 |
| HP            | Laptop 17-ak0xx             | [7d35815562](https://linux-hardware.org/?probe=7d35815562) | Mar 13, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| Dell          | Inspiron 15 3511            | [153652da71](https://linux-hardware.org/?probe=153652da71) | Mar 07, 2023 |
| Dell          | Latitude 3190               | [a3a4113ab4](https://linux-hardware.org/?probe=a3a4113ab4) | Mar 06, 2023 |
| HP            | 255 G3                      | [9ccab85062](https://linux-hardware.org/?probe=9ccab85062) | Mar 04, 2023 |
| Dell          | Inspiron 15 3511            | [a84948f124](https://linux-hardware.org/?probe=a84948f124) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 620                         | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | [5718d685e4](https://linux-hardware.org/?probe=5718d685e4) | Mar 02, 2023 |
| Chuwi         | GemiBook Pro                | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | [5fe3c354ff](https://linux-hardware.org/?probe=5fe3c354ff) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | [a15227fc75](https://linux-hardware.org/?probe=a15227fc75) | Mar 02, 2023 |
| Dell          | Latitude 3190               | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | 255 G3                      | [49dccf5753](https://linux-hardware.org/?probe=49dccf5753) | Feb 26, 2023 |
| Dell          | Inspiron 3521               | [b6321ee5a4](https://linux-hardware.org/?probe=b6321ee5a4) | Feb 25, 2023 |
| Dell          | Inspiron 3521               | [efc95d4697](https://linux-hardware.org/?probe=efc95d4697) | Feb 25, 2023 |
| HP            | 250 G7 Notebook PC          | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| ASUSTek       | UX330CAK                    | [419493491e](https://linux-hardware.org/?probe=419493491e) | Feb 23, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [0e9172bdd5](https://linux-hardware.org/?probe=0e9172bdd5) | Feb 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [adc356a0a8](https://linux-hardware.org/?probe=adc356a0a8) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d09dc2494a](https://linux-hardware.org/?probe=d09dc2494a) | Feb 21, 2023 |
| Dell          | Latitude 3190               | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Medion        | E1239T MD60139              | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| HP            | ProBook 445 G1              | [bcd5c952f1](https://linux-hardware.org/?probe=bcd5c952f1) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [aba30bb2d8](https://linux-hardware.org/?probe=aba30bb2d8) | Feb 17, 2023 |
| RTD Embedd... | CMA34CR                     | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| HP            | ProBook 450 G3              | [9d060a9cc6](https://linux-hardware.org/?probe=9d060a9cc6) | Feb 15, 2023 |
| HP            | ProBook 450 G3              | [0cbe95253a](https://linux-hardware.org/?probe=0cbe95253a) | Feb 15, 2023 |
| Linx          | LINX1010B                   | [5ca377461f](https://linux-hardware.org/?probe=5ca377461f) | Feb 14, 2023 |
| Dell          | Latitude 3190               | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| Dell          | Inspiron 5559               | [dcb95dba09](https://linux-hardware.org/?probe=dcb95dba09) | Feb 12, 2023 |
| Insyde        | CherryTrail                 | [86103b5293](https://linux-hardware.org/?probe=86103b5293) | Feb 12, 2023 |
| Medion        | P6634                       | [ec0002869f](https://linux-hardware.org/?probe=ec0002869f) | Feb 11, 2023 |
| Medion        | P6634                       | [15c3260ecf](https://linux-hardware.org/?probe=15c3260ecf) | Feb 11, 2023 |
| Acer          | Nitro AN515-55              | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| HP            | 450                         | [26d3505372](https://linux-hardware.org/?probe=26d3505372) | Feb 06, 2023 |
| Dell          | Latitude 3190               | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| ASUSTek       | GL752VW                     | [48f423dfae](https://linux-hardware.org/?probe=48f423dfae) | Feb 05, 2023 |
| HP            | Laptop 17-ak0xx             | [ed6c6cc366](https://linux-hardware.org/?probe=ed6c6cc366) | Feb 05, 2023 |
| HP            | ZBook 17 G3                 | [7e94a2328d](https://linux-hardware.org/?probe=7e94a2328d) | Feb 05, 2023 |
| Acer          | Aspire 4736Z                | [a2ab102eeb](https://linux-hardware.org/?probe=a2ab102eeb) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ddb7f53b34](https://linux-hardware.org/?probe=ddb7f53b34) | Feb 03, 2023 |
| HP            | EliteBook 2570p             | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
| Dell          | Latitude 3190               | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [1d28352c0f](https://linux-hardware.org/?probe=1d28352c0f) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Dell          | Latitude 3190               | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| AMI           | Intel                       | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Dell          | Latitude 3190               | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Dell          | Latitude 3190               | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge 031925U       | [95feaf21b4](https://linux-hardware.org/?probe=95feaf21b4) | Jan 07, 2023 |
| Toshiba       | Satellite M70               | [616dbdfa63](https://linux-hardware.org/?probe=616dbdfa63) | Jan 05, 2023 |
| Dell          | Latitude 3190               | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| Toshiba       | PORTEGE Z30-C               | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| Dell          | Latitude 3190               | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| Apple         | MacBookPro10,1              | [6c8ec40821](https://linux-hardware.org/?probe=6c8ec40821) | Dec 25, 2022 |
| Dell          | Latitude 3190               | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [916375929d](https://linux-hardware.org/?probe=916375929d) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Gigabyte      | G5 KC                       | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| HP            | 15 Notebook PC              | [06e7a6dfe7](https://linux-hardware.org/?probe=06e7a6dfe7) | Dec 12, 2022 |
| Dell          | Latitude 3190               | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| Dell          | Vostro 15-3568              | [a583a55071](https://linux-hardware.org/?probe=a583a55071) | Dec 10, 2022 |
| Dell          | Vostro 15-3568              | [2e76f24d6a](https://linux-hardware.org/?probe=2e76f24d6a) | Dec 09, 2022 |
| Dell          | Vostro 15-3568              | [36b349ff7f](https://linux-hardware.org/?probe=36b349ff7f) | Dec 08, 2022 |
| Dell          | Latitude 3190               | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| Acer          | Aspire ES1-732              | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| MSI           | GF63 Thin 9SC               | [057b0039b7](https://linux-hardware.org/?probe=057b0039b7) | Dec 01, 2022 |
| Dell          | Latitude 3190               | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| Sony          | VPCYB3V1E                   | [8fc84889a5](https://linux-hardware.org/?probe=8fc84889a5) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | [b47217fa0c](https://linux-hardware.org/?probe=b47217fa0c) | Nov 25, 2022 |
| Apple         | MacBookPro10,1              | [3f08c2fb11](https://linux-hardware.org/?probe=3f08c2fb11) | Nov 25, 2022 |
| Sony          | VGN-TZ3RXN_B                | [5986f007c8](https://linux-hardware.org/?probe=5986f007c8) | Nov 22, 2022 |
| TUXEDO        | N7x0WU                      | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Dell          | Latitude 3190               | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [9884754d7b](https://linux-hardware.org/?probe=9884754d7b) | Nov 14, 2022 |
| Dell          | Latitude 3190               | [0e09796a40](https://linux-hardware.org/?probe=0e09796a40) | Nov 14, 2022 |
| Dell          | Inspiron 3583               | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [cb36e9d15c](https://linux-hardware.org/?probe=cb36e9d15c) | Nov 09, 2022 |
| Dell          | Latitude 3190               | [0459e9f47e](https://linux-hardware.org/?probe=0459e9f47e) | Nov 06, 2022 |
| ASUSTek       | X200CA                      | [91d85f8376](https://linux-hardware.org/?probe=91d85f8376) | Nov 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [9819da96f2](https://linux-hardware.org/?probe=9819da96f2) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| SANTECH       | X170KM-G                    | [073f9a1d24](https://linux-hardware.org/?probe=073f9a1d24) | Nov 01, 2022 |
| Vulcan Ele... | Excursion XB                | [30ceac1216](https://linux-hardware.org/?probe=30ceac1216) | Oct 31, 2022 |
| Dell          | Latitude 3190               | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [423ad57e72](https://linux-hardware.org/?probe=423ad57e72) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [f8b4ce6c3f](https://linux-hardware.org/?probe=f8b4ce6c3f) | Oct 29, 2022 |
| Apple         | MacBookPro14,3              | [6383143b5b](https://linux-hardware.org/?probe=6383143b5b) | Oct 28, 2022 |
| Dell          | Latitude 3190               | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| win elemen... | MoreFine S500+              | [d34df28814](https://linux-hardware.org/?probe=d34df28814) | Oct 22, 2022 |
| Apple         | MacBookPro7,1               | [aa571dded9](https://linux-hardware.org/?probe=aa571dded9) | Oct 22, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e33a95e0b0](https://linux-hardware.org/?probe=e33a95e0b0) | Oct 18, 2022 |
| Dell          | Latitude 3190               | [342d7acb67](https://linux-hardware.org/?probe=342d7acb67) | Oct 17, 2022 |
| Apple         | MacBookPro11,1              | [09af41cbf8](https://linux-hardware.org/?probe=09af41cbf8) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | [b3267ce847](https://linux-hardware.org/?probe=b3267ce847) | Oct 15, 2022 |
| Apple         | MacBookPro11,1              | [209d243342](https://linux-hardware.org/?probe=209d243342) | Oct 15, 2022 |
| HP            | Laptop 17-ak0xx             | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| Medion        | E7424 MD60750               | [7c9ea600ad](https://linux-hardware.org/?probe=7c9ea600ad) | Oct 11, 2022 |
| Dell          | Latitude 3190               | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [f2c440fdf6](https://linux-hardware.org/?probe=f2c440fdf6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [8159009c50](https://linux-hardware.org/?probe=8159009c50) | Oct 05, 2022 |
| Google        | Setzer                      | [6bafaabd48](https://linux-hardware.org/?probe=6bafaabd48) | Oct 04, 2022 |
| Dell          | Vostro 3500                 | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| Dell          | Latitude 3190               | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| Dell          | Latitude 7490               | [872aafeb50](https://linux-hardware.org/?probe=872aafeb50) | Oct 02, 2022 |
| HP            | 250 G6 Notebook PC          | [992cf7d019](https://linux-hardware.org/?probe=992cf7d019) | Sep 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [5b7d4c6b7a](https://linux-hardware.org/?probe=5b7d4c6b7a) | Sep 27, 2022 |
| Dell          | Precision 7520              | [a7b1df0888](https://linux-hardware.org/?probe=a7b1df0888) | Sep 26, 2022 |
| Dell          | Latitude 3190               | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Apple         | MacBookAir7,2               | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| Acer          | Nitro AN515-54              | [6182e4ef84](https://linux-hardware.org/?probe=6182e4ef84) | Sep 25, 2022 |
| HP            | Pavilion g7                 | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| Dell          | Inspiron 5521               | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Dell          | Latitude 3190               | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | [de3a2e822c](https://linux-hardware.org/?probe=de3a2e822c) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Dell          | Latitude 3190               | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [7702adff5d](https://linux-hardware.org/?probe=7702adff5d) | Sep 05, 2022 |
| Dell          | Latitude 3190               | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Dell          | Latitude 3190               | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| win elemen... | MoreFine S500+              | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| win elemen... | MoreFine S500+              | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Dell          | System XPS 15Z              | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Lenovo        | ThinkPad T560 20FJS0EP00    | [dda2c8f199](https://linux-hardware.org/?probe=dda2c8f199) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| Dell          | Precision 7720              | [9f17ade16f](https://linux-hardware.org/?probe=9f17ade16f) | Aug 08, 2022 |
| Dell          | Latitude 3190               | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | [68e632a5f6](https://linux-hardware.org/?probe=68e632a5f6) | Aug 08, 2022 |
| Samsung       | NC210/NC110                 | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Dell          | Latitude 3190               | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Dell          | Vostro 3550                 | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| Dell          | Latitude 3190               | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| Apple         | MacBookAir7,2               | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| Dell          | Latitude 3190               | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Alienware     | 13 R2                       | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| Dell          | Latitude 3190               | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| Dell          | Latitude 3190               | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Dell          | Latitude D520               | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| Sony          | VPCSB1V9R                   | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| Acer          | Aspire A515-56              | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Acer          | Nitro AN515-55              | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| HP            | ProBook 450 G4              | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | G5 KC                       | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| ASUSTek       | 1101HA                      | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| TUXEDO        | N7x0WU                      | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Dell          | Latitude 3190               | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Sony          | SVE1513Q1ESI                | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | X550CC                      | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| Lenovo        | B590 20208                  | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| ASUSTek       | E402MA                      | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.0-21-amd64            | 25        | 9.47%   |
| 6.0.0-6mx-amd64            | 24        | 9.09%   |
| 5.10.0-23-amd64            | 16        | 6.06%   |
| 5.10.0-13-amd64            | 15        | 5.68%   |
| 5.10.0-9-amd64             | 14        | 5.3%    |
| 5.10.0-18-amd64            | 13        | 4.92%   |
| 5.14.0-4mx-amd64           | 9         | 3.41%   |
| 5.10.0-20-amd64            | 9         | 3.41%   |
| 5.10.0-16-amd64            | 9         | 3.41%   |
| 5.16.0-5mx-amd64           | 8         | 3.03%   |
| 5.10.0-19-amd64            | 8         | 3.03%   |
| 5.10.0-14-amd64            | 7         | 2.65%   |
| 5.10.0-28-amd64            | 6         | 2.27%   |
| 5.10.0-11-amd64            | 6         | 2.27%   |
| 6.0.0-4mx-amd64            | 5         | 1.89%   |
| 5.18.0-4mx-amd64           | 5         | 1.89%   |
| 5.10.0-22-amd64            | 5         | 1.89%   |
| 6.1.0-9mx-ahs-amd64        | 3         | 1.14%   |
| 6.0.0-10.1-liquorix-amd64  | 3         | 1.14%   |
| 5.19.0-2mx-amd64           | 3         | 1.14%   |
| 5.10.0-26-amd64            | 3         | 1.14%   |
| 5.10.0-17-amd64            | 3         | 1.14%   |
| 6.1.0-8mx-ahs-amd64        | 2         | 0.76%   |
| 6.1.0-4mx-amd64            | 2         | 0.76%   |
| 6.0.0-3mx-amd64            | 2         | 0.76%   |
| 5.16.0-6mx-amd64           | 2         | 0.76%   |
| 5.16.0-18.1-liquorix-amd64 | 2         | 0.76%   |
| 5.10.0-8-amd64             | 2         | 0.76%   |
| 5.10.0-25-amd64            | 2         | 0.76%   |
| 5.10.0-24-amd64            | 2         | 0.76%   |
| 5.10.0-23-686-pae          | 2         | 0.76%   |
| 5.10.0-20-686-pae          | 2         | 0.76%   |
| 5.10.0-15-amd64            | 2         | 0.76%   |
| 5.10.0-13-686-pae          | 2         | 0.76%   |
| 5.10.0-11-686-pae          | 2         | 0.76%   |
| 5.10.0-10-amd64            | 2         | 0.76%   |
| 6.7.9-1-liquorix-amd64     | 1         | 0.38%   |
| 6.7.12-1-liquorix-amd64    | 1         | 0.38%   |
| 6.5.0-1mx-ahs-amd64        | 1         | 0.38%   |
| 6.4.3-1-liquorix-amd64     | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 150       | 60%     |
| 6.0.0    | 35        | 14%     |
| 5.16.0   | 13        | 5.2%    |
| 6.1.0    | 11        | 4.4%    |
| 5.14.0   | 9         | 3.6%    |
| 5.18.0   | 7         | 2.8%    |
| 5.19.0   | 6         | 2.4%    |
| 5.17.0   | 4         | 1.6%    |
| 6.7.9    | 1         | 0.4%    |
| 6.7.12   | 1         | 0.4%    |
| 6.5.0    | 1         | 0.4%    |
| 6.4.3    | 1         | 0.4%    |
| 6.4.0    | 1         | 0.4%    |
| 6.3.0    | 1         | 0.4%    |
| 6.2.7    | 1         | 0.4%    |
| 6.1.15   | 1         | 0.4%    |
| 6.1.12   | 1         | 0.4%    |
| 5.15.0   | 1         | 0.4%    |
| 5.13.0   | 1         | 0.4%    |
| 5.10.82  | 1         | 0.4%    |
| 5.10.142 | 1         | 0.4%    |
| 4.19.0   | 1         | 0.4%    |
| Unknown  | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 152       | 61.04%  |
| 6.0     | 35        | 14.06%  |
| 6.1     | 13        | 5.22%   |
| 5.16    | 13        | 5.22%   |
| 5.14    | 9         | 3.61%   |
| 5.18    | 7         | 2.81%   |
| 5.19    | 6         | 2.41%   |
| 5.17    | 4         | 1.61%   |
| 6.4     | 2         | 0.8%    |
| 6.7     | 1         | 0.4%    |
| 6.5     | 1         | 0.4%    |
| 6.3     | 1         | 0.4%    |
| 6.2     | 1         | 0.4%    |
| 5.15    | 1         | 0.4%    |
| 5.13    | 1         | 0.4%    |
| 4.19    | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 225       | 94.94%  |
| i686   | 12        | 5.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| XFCE             | 175       | 72.61%  |
| KDE5             | 45        | 18.67%  |
| GNOME            | 4         | 1.66%   |
| Unknown          | 4         | 1.66%   |
| i3               | 3         | 1.24%   |
| Budgie           | 3         | 1.24%   |
| lightdm-xsession | 2         | 0.83%   |
| fluxbox          | 2         | 0.83%   |
| X-Cinnamon       | 1         | 0.41%   |
| LXQt             | 1         | 0.41%   |
| GNOME Classic    | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 233       | 98.31%  |
| Tty     | 3         | 1.27%   |
| Wayland | 1         | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 190       | 79.5%   |
| SDDM    | 43        | 17.99%  |
| SLiM    | 3         | 1.26%   |
| Unknown | 2         | 0.84%   |
| GDM3    | 1         | 0.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 115       | 48.12%  |
| de_DE   | 30        | 12.55%  |
| en_GB   | 14        | 5.86%   |
| it_IT   | 13        | 5.44%   |
| fr_FR   | 9         | 3.77%   |
| ru_RU   | 7         | 2.93%   |
| pl_PL   | 4         | 1.67%   |
| es_ES   | 4         | 1.67%   |
| en_AU   | 4         | 1.67%   |
| Unknown | 4         | 1.67%   |
| pt_BR   | 3         | 1.26%   |
| en_NZ   | 3         | 1.26%   |
| de_CH   | 3         | 1.26%   |
| tr_TR   | 2         | 0.84%   |
| nl_NL   | 2         | 0.84%   |
| fi_FI   | 2         | 0.84%   |
| es_MX   | 2         | 0.84%   |
| es_AR   | 2         | 0.84%   |
| bg_BG   | 2         | 0.84%   |
| sk_SK   | 1         | 0.42%   |
| ro_RO   | 1         | 0.42%   |
| nl_BE   | 1         | 0.42%   |
| nb_NO   | 1         | 0.42%   |
| id_ID   | 1         | 0.42%   |
| hu_HU   | 1         | 0.42%   |
| fr_CA   | 1         | 0.42%   |
| fr_BE   | 1         | 0.42%   |
| es_VE   | 1         | 0.42%   |
| es_UY   | 1         | 0.42%   |
| es_PE   | 1         | 0.42%   |
| es_CO   | 1         | 0.42%   |
| en_IE   | 1         | 0.42%   |
| en_CA   | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 167       | 70.46%  |
| BIOS | 70        | 29.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 201       | 83.75%  |
| Overlay | 27        | 11.25%  |
| Btrfs   | 10        | 4.17%   |
| Xfs     | 1         | 0.42%   |
| F2fs    | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 174       | 73.42%  |
| MBR     | 62        | 26.16%  |
| Unknown | 1         | 0.42%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 181       | 75.73%  |
| Yes       | 58        | 24.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 143       | 60.08%  |
| Yes       | 95        | 39.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo                    | 48        | 20.25%  |
| Hewlett-Packard           | 44        | 18.57%  |
| ASUSTek Computer          | 27        | 11.39%  |
| Dell                      | 24        | 10.13%  |
| Acer                      | 24        | 10.13%  |
| Apple                     | 12        | 5.06%   |
| Sony                      | 8         | 3.38%   |
| MSI                       | 5         | 2.11%   |
| Toshiba                   | 4         | 1.69%   |
| Samsung Electronics       | 4         | 1.69%   |
| Medion                    | 4         | 1.69%   |
| Fujitsu Siemens           | 4         | 1.69%   |
| Alienware                 | 4         | 1.69%   |
| TUXEDO                    | 2         | 0.84%   |
| Notebook                  | 2         | 0.84%   |
| Gigabyte Technology       | 2         | 0.84%   |
| Chuwi                     | 2         | 0.84%   |
| Unknown                   | 2         | 0.84%   |
| win element               | 1         | 0.42%   |
| Vulcan Electronics        | 1         | 0.42%   |
| SANTECH                   | 1         | 0.42%   |
| RTD Embedded Technologies | 1         | 0.42%   |
| Linx                      | 1         | 0.42%   |
| LG Electronics            | 1         | 0.42%   |
| HUAWEI                    | 1         | 0.42%   |
| Google                    | 1         | 0.42%   |
| Framework                 | 1         | 0.42%   |
| F-Plus Mobile             | 1         | 0.42%   |
| efirstview                | 1         | 0.42%   |
| CONNEX                    | 1         | 0.42%   |
| Compal                    | 1         | 0.42%   |
| Casper                    | 1         | 0.42%   |
| AMI                       | 1         | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 3         | 1.27%   |
| HP ProBook 450 G1                   | 2         | 0.84%   |
| HP Pavilion Laptop 15-eh1xxx        | 2         | 0.84%   |
| HP Laptop 17-ak0xx                  | 2         | 0.84%   |
| Chuwi GemiBook Pro                  | 2         | 0.84%   |
| Apple MacBookAir7,2                 | 2         | 0.84%   |
| Acer Nitro AN515-55                 | 2         | 0.84%   |
| win element MoreFine S500+          | 1         | 0.42%   |
| Vulcan Excursion XB                 | 1         | 0.42%   |
| TUXEDO N7x0WU                       | 1         | 0.42%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 1         | 0.42%   |
| Toshiba Satellite M70               | 1         | 0.42%   |
| Toshiba Satellite L650              | 1         | 0.42%   |
| Toshiba Satellite C845              | 1         | 0.42%   |
| Toshiba PORTEGE Z30-C               | 1         | 0.42%   |
| Sony VPCYB3V1E                      | 1         | 0.42%   |
| Sony VPCSB1V9R                      | 1         | 0.42%   |
| Sony VPCF119FX                      | 1         | 0.42%   |
| Sony VPCEH2N1E                      | 1         | 0.42%   |
| Sony VPCEC3S1E                      | 1         | 0.42%   |
| Sony VPCCB32FD                      | 1         | 0.42%   |
| Sony VGN-TZ3RXN_B                   | 1         | 0.42%   |
| Sony SVE1513Q1ESI                   | 1         | 0.42%   |
| SANTECH X170KM-G                    | 1         | 0.42%   |
| Samsung NC210/NC110                 | 1         | 0.42%   |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 0.42%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 1         | 0.42%   |
| Samsung 340XAA/350XAA/550XAA        | 1         | 0.42%   |
| RTD Embedded CMA34CR                | 1         | 0.42%   |
| Notebook PD5x_7xPNP_PNN_PNT         | 1         | 0.42%   |
| Notebook NL5xNU                     | 1         | 0.42%   |
| MSI U200                            | 1         | 0.42%   |
| MSI Modern 14 B11MOL                | 1         | 0.42%   |
| MSI GV62 8RD                        | 1         | 0.42%   |
| MSI GF63 Thin 9SC                   | 1         | 0.42%   |
| MSI Alpha 15 B5EEK                  | 1         | 0.42%   |
| Medion P6634                        | 1         | 0.42%   |
| Medion E7424 MD60750                | 1         | 0.42%   |
| Medion E14304                       | 1         | 0.42%   |
| Medion E1239T MD60139               | 1         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 28        | 11.81%  |
| Acer Aspire           | 16        | 6.75%   |
| Dell Latitude         | 9         | 3.8%    |
| HP EliteBook          | 8         | 3.38%   |
| Lenovo IdeaPad        | 7         | 2.95%   |
| HP Laptop             | 7         | 2.95%   |
| HP ProBook            | 6         | 2.53%   |
| Dell Inspiron         | 6         | 2.53%   |
| ASUS VivoBook         | 6         | 2.53%   |
| HP Pavilion           | 4         | 1.69%   |
| HP Compaq             | 4         | 1.69%   |
| Toshiba Satellite     | 3         | 1.27%   |
| Lenovo ThinkBook      | 3         | 1.27%   |
| HP 250                | 3         | 1.27%   |
| Dell Vostro           | 3         | 1.27%   |
| Dell System           | 3         | 1.27%   |
| Acer Nitro            | 3         | 1.27%   |
| Unknown               | 3         | 1.27%   |
| Lenovo V17            | 2         | 0.84%   |
| Lenovo Legion         | 2         | 0.84%   |
| HP ZBook              | 2         | 0.84%   |
| HP 255                | 2         | 0.84%   |
| Fujitsu Siemens AMILO | 2         | 0.84%   |
| Dell Precision        | 2         | 0.84%   |
| Chuwi GemiBook        | 2         | 0.84%   |
| ASUS TUF              | 2         | 0.84%   |
| ASUS ROG              | 2         | 0.84%   |
| ASUS ASUS             | 2         | 0.84%   |
| Apple MacBookPro11    | 2         | 0.84%   |
| Apple MacBookAir7     | 2         | 0.84%   |
| Alienware m15         | 2         | 0.84%   |
| Acer Swift            | 2         | 0.84%   |
| Acer Extensa          | 2         | 0.84%   |
| win element MoreFine  | 1         | 0.42%   |
| Vulcan Excursion      | 1         | 0.42%   |
| TUXEDO N7x0WU         | 1         | 0.42%   |
| TUXEDO InfinityBook   | 1         | 0.42%   |
| Toshiba PORTEGE       | 1         | 0.42%   |
| Sony VPCYB3V1E        | 1         | 0.42%   |
| Sony VPCSB1V9R        | 1         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 35        | 14.77%  |
| 2015    | 18        | 7.59%   |
| 2011    | 18        | 7.59%   |
| 2019    | 17        | 7.17%   |
| 2020    | 16        | 6.75%   |
| 2016    | 16        | 6.75%   |
| 2013    | 16        | 6.75%   |
| 2012    | 16        | 6.75%   |
| 2010    | 14        | 5.91%   |
| 2022    | 12        | 5.06%   |
| 2018    | 12        | 5.06%   |
| 2017    | 9         | 3.8%    |
| 2014    | 9         | 3.8%    |
| 2008    | 9         | 3.8%    |
| 2007    | 8         | 3.38%   |
| 2009    | 3         | 1.27%   |
| 2006    | 3         | 1.27%   |
| 2005    | 3         | 1.27%   |
| 2023    | 2         | 0.84%   |
| Unknown | 1         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 237       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 235       | 99.16%  |
| Enabled  | 2         | 0.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 236       | 99.58%  |
| Yes  | 1         | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 77        | 32.35%  |
| 8.01-16.0   | 38        | 15.97%  |
| 3.01-4.0    | 36        | 15.13%  |
| 16.01-24.0  | 36        | 15.13%  |
| 1.01-2.0    | 20        | 8.4%    |
| 32.01-64.0  | 18        | 7.56%   |
| 2.01-3.0    | 6         | 2.52%   |
| 64.01-256.0 | 3         | 1.26%   |
| 24.01-32.0  | 2         | 0.84%   |
| 0.51-1.0    | 2         | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 90        | 36%     |
| 2.01-3.0  | 65        | 26%     |
| 3.01-4.0  | 41        | 16.4%   |
| 4.01-8.0  | 30        | 12%     |
| 0.51-1.0  | 17        | 6.8%    |
| 8.01-16.0 | 5         | 2%      |
| 0.01-0.5  | 2         | 0.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 168       | 70%     |
| 2      | 55        | 22.92%  |
| 3      | 13        | 5.42%   |
| 0      | 3         | 1.25%   |
| 4      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 163       | 68.78%  |
| Yes       | 74        | 31.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 80.59%  |
| No        | 46        | 19.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 229       | 95.82%  |
| No        | 10        | 4.18%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 190       | 79.83%  |
| No        | 48        | 20.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 49        | 20.42%  |
| Germany      | 30        | 12.5%   |
| Italy        | 21        | 8.75%   |
| Canada       | 14        | 5.83%   |
| France       | 10        | 4.17%   |
| Russia       | 8         | 3.33%   |
| UK           | 7         | 2.92%   |
| India        | 7         | 2.92%   |
| Spain        | 6         | 2.5%    |
| Poland       | 6         | 2.5%    |
| Australia    | 6         | 2.5%    |
| Brazil       | 5         | 2.08%   |
| Serbia       | 4         | 1.67%   |
| Romania      | 4         | 1.67%   |
| New Zealand  | 4         | 1.67%   |
| Netherlands  | 4         | 1.67%   |
| Belgium      | 4         | 1.67%   |
| Switzerland  | 3         | 1.25%   |
| Indonesia    | 3         | 1.25%   |
| Turkey       | 2         | 0.83%   |
| South Africa | 2         | 0.83%   |
| Hungary      | 2         | 0.83%   |
| Greece       | 2         | 0.83%   |
| Finland      | 2         | 0.83%   |
| Egypt        | 2         | 0.83%   |
| Czechia      | 2         | 0.83%   |
| Bulgaria     | 2         | 0.83%   |
| Bangladesh   | 2         | 0.83%   |
| Austria      | 2         | 0.83%   |
| Vietnam      | 1         | 0.42%   |
| Venezuela    | 1         | 0.42%   |
| Uzbekistan   | 1         | 0.42%   |
| Uruguay      | 1         | 0.42%   |
| Tunisia      | 1         | 0.42%   |
| Sweden       | 1         | 0.42%   |
| Slovakia     | 1         | 0.42%   |
| Peru         | 1         | 0.42%   |
| Norway       | 1         | 0.42%   |
| Nepal        | 1         | 0.42%   |
| Mexico       | 1         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Milan          | 5         | 1.98%   |
| Moscow         | 4         | 1.58%   |
| Berlin         | 4         | 1.58%   |
| Warsaw         | 3         | 1.19%   |
| Rome           | 3         | 1.19%   |
| Belgrade       | 3         | 1.19%   |
| Walled Lake    | 2         | 0.79%   |
| Vienna         | 2         | 0.79%   |
| Toulouse       | 2         | 0.79%   |
| St Petersburg  | 2         | 0.79%   |
| Perth          | 2         | 0.79%   |
| Paris          | 2         | 0.79%   |
| Orange         | 2         | 0.79%   |
| Oakland        | 2         | 0.79%   |
| New York       | 2         | 0.79%   |
| Montreal       | 2         | 0.79%   |
| Manises        | 2         | 0.79%   |
| Hyderabad      | 2         | 0.79%   |
| Florence       | 2         | 0.79%   |
| Doesburg       | 2         | 0.79%   |
| Dhaka          | 2         | 0.79%   |
| Casale Litta   | 2         | 0.79%   |
| Canberra       | 2         | 0.79%   |
| Cambridge      | 2         | 0.79%   |
| Cairo          | 2         | 0.79%   |
| Budapest       | 2         | 0.79%   |
| Amsterdam      | 2         | 0.79%   |
| Zurich         | 1         | 0.4%    |
| Zeven          | 1         | 0.4%    |
| Yekaterinburg  | 1         | 0.4%    |
| Workington     | 1         | 0.4%    |
| Wola           | 1         | 0.4%    |
| Wilmslow       | 1         | 0.4%    |
| Westland       | 1         | 0.4%    |
| Wermelskirchen | 1         | 0.4%    |
| Waycross       | 1         | 0.4%    |
| Vlorë         | 1         | 0.4%    |
| Vasco da Gama  | 1         | 0.4%    |
| Vancouver      | 1         | 0.4%    |
| Uelzen         | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 56     | 14.56%  |
| WDC                 | 38        | 38     | 12.3%   |
| Seagate             | 25        | 31     | 8.09%   |
| Unknown             | 20        | 23     | 6.47%   |
| SK hynix            | 20        | 21     | 6.47%   |
| Kingston            | 18        | 21     | 5.83%   |
| Toshiba             | 16        | 16     | 5.18%   |
| Crucial             | 15        | 32     | 4.85%   |
| Intel               | 12        | 14     | 3.88%   |
| SanDisk             | 8         | 9      | 2.59%   |
| Hitachi             | 8         | 9      | 2.59%   |
| Apple               | 7         | 10     | 2.27%   |
| SPCC                | 6         | 6      | 1.94%   |
| Micron Technology   | 6         | 6      | 1.94%   |
| HGST                | 6         | 6      | 1.94%   |
| LITEON              | 5         | 5      | 1.62%   |
| KIOXIA              | 4         | 6      | 1.29%   |
| Transcend           | 3         | 3      | 0.97%   |
| PNY                 | 3         | 3      | 0.97%   |
| Netac               | 3         | 3      | 0.97%   |
| Dogfish             | 3         | 3      | 0.97%   |
| Unknown             | 3         | 3      | 0.97%   |
| Team                | 2         | 2      | 0.65%   |
| Phison              | 2         | 3      | 0.65%   |
| Patriot             | 2         | 3      | 0.65%   |
| OCZ                 | 2         | 2      | 0.65%   |
| Fujitsu             | 2         | 2      | 0.65%   |
| EYOTA               | 2         | 2      | 0.65%   |
| Corsair             | 2         | 2      | 0.65%   |
| China               | 2         | 2      | 0.65%   |
| UMIS                | 1         | 1      | 0.32%   |
| Teclast             | 1         | 1      | 0.32%   |
| SWORDBILL           | 1         | 2      | 0.32%   |
| SSSTC               | 1         | 1      | 0.32%   |
| Silicon Motion      | 1         | 1      | 0.32%   |
| SABRENT             | 1         | 1      | 0.32%   |
| RENICE              | 1         | 1      | 0.32%   |
| KingSpec            | 1         | 2      | 0.32%   |
| Indilinx            | 1         | 1      | 0.32%   |
| Hewlett-Packard     | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 5         | 1.58%   |
| Unknown SD32G  32GB                    | 3         | 0.95%   |
| SPCC Solid State Disk 1TB              | 3         | 0.95%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 0.95%   |
| SK hynix HFM512GDJTNI-82A0A 512GB      | 3         | 0.95%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 0.95%   |
| Samsung SSD 980 PRO 1TB                | 3         | 0.95%   |
| Kingston SA400S37480G 480GB SSD        | 3         | 0.95%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 0.95%   |
| Intel SSDPEKNU512GZ 512GB              | 3         | 0.95%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.95%   |
| Crucial CT480BX500SSD1 480GB           | 3         | 0.95%   |
| Crucial CT120BX500SSD1 120GB           | 3         | 0.95%   |
| Unknown                                | 3         | 0.95%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.63%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 2         | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.63%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 0.63%   |
| Unknown SDW32G  32GB                   | 2         | 0.63%   |
| Unknown DA4064  64GB                   | 2         | 0.63%   |
| Toshiba MQ01ABD075 752GB               | 2         | 0.63%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 2         | 0.63%   |
| SK hynix HFS128G39TND-N210A 128GB SSD  | 2         | 0.63%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.63%   |
| Seagate ST500LM000-1EJ162 500GB        | 2         | 0.63%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 0.63%   |
| SanDisk NVMe SSD Drive 512GB           | 2         | 0.63%   |
| Samsung SSD 860 250GB                  | 2         | 0.63%   |
| Samsung SSD 850 EVO 250GB              | 2         | 0.63%   |
| Samsung MZVLB512HBJQ-000L7 512GB       | 2         | 0.63%   |
| Samsung MZALQ256HBJD-00BL2 256GB       | 2         | 0.63%   |
| Kingston SA400S37120G 120GB SSD        | 2         | 0.63%   |
| Kingston OM8PCP3512F-AI1 512GB         | 2         | 0.63%   |
| Hitachi HTS54503 320GB                 | 2         | 0.63%   |
| Hitachi HTS543216L9SA00 160GB          | 2         | 0.63%   |
| EYOTA SSD 120GB                        | 2         | 0.63%   |
| Dogfish SSD 128GB                      | 2         | 0.63%   |
| Crucial CT500MX500SSD1 500GB           | 2         | 0.63%   |
| Crucial CT240BX500SSD1 240GB           | 2         | 0.63%   |
| Crucial CT1000P2SSD8 1TB               | 2         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 31     | 31.25%  |
| WDC                 | 24        | 24     | 30%     |
| Toshiba             | 10        | 10     | 12.5%   |
| Hitachi             | 8         | 9      | 10%     |
| HGST                | 6         | 6      | 7.5%    |
| Samsung Electronics | 3         | 3      | 3.75%   |
| Fujitsu             | 2         | 2      | 2.5%    |
| Unknown             | 1         | 1      | 1.25%   |
| SABRENT             | 1         | 1      | 1.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 26     | 17.7%   |
| Crucial             | 12        | 28     | 10.62%  |
| Kingston            | 10        | 12     | 8.85%   |
| SPCC                | 6         | 6      | 5.31%   |
| Apple               | 6         | 9      | 5.31%   |
| WDC                 | 5         | 5      | 4.42%   |
| SanDisk             | 5         | 6      | 4.42%   |
| SK hynix            | 4         | 4      | 3.54%   |
| LITEON              | 4         | 4      | 3.54%   |
| Intel               | 4         | 4      | 3.54%   |
| Transcend           | 3         | 3      | 2.65%   |
| PNY                 | 3         | 3      | 2.65%   |
| Netac               | 3         | 3      | 2.65%   |
| Dogfish             | 3         | 3      | 2.65%   |
| Toshiba             | 2         | 2      | 1.77%   |
| OCZ                 | 2         | 2      | 1.77%   |
| Micron Technology   | 2         | 2      | 1.77%   |
| EYOTA               | 2         | 2      | 1.77%   |
| China               | 2         | 2      | 1.77%   |
| Unknown             | 2         | 2      | 1.77%   |
| Teclast             | 1         | 1      | 0.88%   |
| Team                | 1         | 1      | 0.88%   |
| SWORDBILL           | 1         | 2      | 0.88%   |
| RENICE              | 1         | 1      | 0.88%   |
| Patriot             | 1         | 1      | 0.88%   |
| KingSpec            | 1         | 2      | 0.88%   |
| Indilinx            | 1         | 1      | 0.88%   |
| Hewlett-Packard     | 1         | 1      | 0.88%   |
| Gigabyte Technology | 1         | 1      | 0.88%   |
| GeIL                | 1         | 1      | 0.88%   |
| CT500MX5            | 1         | 1      | 0.88%   |
| Corsair             | 1         | 1      | 0.88%   |
| Apacer              | 1         | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 98        | 143    | 34.27%  |
| NVMe    | 88        | 108    | 30.77%  |
| HDD     | 79        | 87     | 27.62%  |
| MMC     | 20        | 24     | 6.99%   |
| Unknown | 1         | 1      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 155       | 225    | 57.84%  |
| NVMe | 88        | 108    | 32.84%  |
| MMC  | 20        | 24     | 7.46%   |
| SAS  | 5         | 6      | 1.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 129       | 168    | 75%     |
| 0.51-1.0   | 40        | 59     | 23.26%  |
| 1.01-2.0   | 2         | 2      | 1.16%   |
| 3.01-4.0   | 1         | 1      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 63        | 25.71%  |
| 101-250        | 63        | 25.71%  |
| 21-50          | 33        | 13.47%  |
| 501-1000       | 30        | 12.24%  |
| 51-100         | 27        | 11.02%  |
| 1-20           | 12        | 4.9%    |
| 1001-2000      | 11        | 4.49%   |
| More than 3000 | 4         | 1.63%   |
| 2001-3000      | 2         | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 113       | 44.66%  |
| 21-50          | 37        | 14.62%  |
| 51-100         | 34        | 13.44%  |
| 101-250        | 30        | 11.86%  |
| 251-500        | 20        | 7.91%   |
| 501-1000       | 10        | 3.95%   |
| 1001-2000      | 6         | 2.37%   |
| More than 3000 | 2         | 0.79%   |
| 2001-3000      | 1         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 2      | 4.88%   |
| WDC WD5000LPCX-60VHAT1 500GB                        | 1         | 1      | 2.44%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 2.44%   |
| WDC WD3200BPVT-24JJ5T0 320GB                        | 1         | 1      | 2.44%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 1         | 1      | 2.44%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD                | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 2.44%   |
| Toshiba MK5059GSXP 500GB                            | 1         | 1      | 2.44%   |
| SK hynix SC210 2.5 7MM 512GB SSD                    | 1         | 1      | 2.44%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 2.44%   |
| Seagate ST980811AS 80GB                             | 1         | 1      | 2.44%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 2.44%   |
| Seagate ST9320421AS 320GB                           | 1         | 1      | 2.44%   |
| Seagate ST9160821AS 160GB                           | 1         | 1      | 2.44%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 1         | 1      | 2.44%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 2.44%   |
| Seagate ST500LM000-1EJ162 500GB                     | 1         | 1      | 2.44%   |
| Seagate ST320LT007-9ZV142 320GB                     | 1         | 5      | 2.44%   |
| Samsung Electronics SSD 840 PRO Series 256GB        | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 830 Series 128GB            | 1         | 2      | 2.44%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 2.44%   |
| Samsung Electronics HM080HC 80GB                    | 1         | 1      | 2.44%   |
| RENICE X2 64GB SSD                                  | 1         | 1      | 2.44%   |
| OCZ VERTEX2 64GB SSD                                | 1         | 1      | 2.44%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 2.44%   |
| Kingston SA400S37120G 120GB SSD                     | 1         | 1      | 2.44%   |
| Intel SSDSC2BF240A5L 240GB                          | 1         | 1      | 2.44%   |
| Intel SSDSA2M040G2GC 40GB                           | 1         | 1      | 2.44%   |
| Intel SSDPEKKF512G8L 512GB                          | 1         | 2      | 2.44%   |
| Indilinx IND-S325S120G 120GB SSD                    | 1         | 1      | 2.44%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS545032B9A300 320GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS543216L9SA00 160GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS541080G9SA00 80GB                        | 1         | 1      | 2.44%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 2.44%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.44%   |
| HGST HTS541075A9E680 752GB                          | 1         | 1      | 2.44%   |
| Fujitsu MHT2080AT 80GB                              | 1         | 1      | 2.44%   |
| Crucial CT1000MX500SSD4 1TB                         | 1         | 6      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 12     | 19.51%  |
| WDC                 | 6         | 6      | 14.63%  |
| Hitachi             | 5         | 5      | 12.2%   |
| Samsung Electronics | 4         | 5      | 9.76%   |
| Toshiba             | 3         | 3      | 7.32%   |
| Intel               | 3         | 4      | 7.32%   |
| HGST                | 3         | 3      | 7.32%   |
| SK hynix            | 2         | 2      | 4.88%   |
| RENICE              | 1         | 1      | 2.44%   |
| OCZ                 | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| Kingston            | 1         | 1      | 2.44%   |
| Indilinx            | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 1      | 2.44%   |
| Crucial             | 1         | 6      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 12     | 29.63%  |
| WDC                 | 6         | 6      | 22.22%  |
| Hitachi             | 5         | 5      | 18.52%  |
| HGST                | 3         | 3      | 11.11%  |
| Toshiba             | 2         | 2      | 7.41%   |
| Samsung Electronics | 2         | 2      | 7.41%   |
| Fujitsu             | 1         | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 31     | 65.85%  |
| SSD  | 12        | 18     | 29.27%  |
| NVMe | 2         | 3      | 4.88%   |

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
| Works    | 188       | 278    | 72.87%  |
| Malfunc  | 41        | 52     | 15.89%  |
| Detected | 29        | 33     | 11.24%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 156       | 56.12%  |
| Samsung Electronics            | 27        | 9.71%   |
| AMD                            | 27        | 9.71%   |
| SK hynix                       | 15        | 5.4%    |
| SanDisk                        | 11        | 3.96%   |
| Kingston Technology Company    | 8         | 2.88%   |
| KIOXIA                         | 6         | 2.16%   |
| Phison Electronics             | 4         | 1.44%   |
| Nvidia                         | 4         | 1.44%   |
| Micron Technology              | 4         | 1.44%   |
| Silicon Motion                 | 3         | 1.08%   |
| Micron/Crucial Technology      | 3         | 1.08%   |
| Toshiba America Info Systems   | 2         | 0.72%   |
| Union Memory (Shenzhen)        | 1         | 0.36%   |
| Solid State Storage Technology | 1         | 0.36%   |
| Silicon Image                  | 1         | 0.36%   |
| Shenzhen Longsys Electronics   | 1         | 0.36%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.36%   |
| Marvell Technology Group       | 1         | 0.36%   |
| Lite-On Technology             | 1         | 0.36%   |
| ADATA Technology               | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 23        | 7.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 7%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 19        | 6.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 4.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 3.33%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 9         | 3%      |
| Intel Tiger Lake-LP SATA Controller                                            | 9         | 3%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 3%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 2.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 2.33%   |
| SK hynix BC511 NVMe SSD                                                        | 6         | 2%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 2%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 2%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 2%      |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1.67%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.33%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 1.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 1.33%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 1%      |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 1%      |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1%      |
| Phison E12 NVMe Controller                                                     | 3         | 1%      |
| Kingston Company OM3PDP3 NVMe SSD                                              | 3         | 1%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1%      |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 1%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1%      |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.67%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 0.67%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 0.67%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 0.67%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 0.67%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.67%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 2         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 164       | 57.14%  |
| NVMe | 87        | 30.31%  |
| IDE  | 19        | 6.62%   |
| RAID | 17        | 5.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 191       | 80.59%  |
| AMD    | 46        | 19.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 8         | 3.38%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 2.11%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 5         | 2.11%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 5         | 2.11%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 5         | 2.11%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 4         | 1.69%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 4         | 1.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 1.27%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 1.27%   |
| Intel Core 2 CPU T5500 @ 1.66GHz        | 3         | 1.27%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 3         | 1.27%   |
| Intel 12th Gen Core i7-12700H           | 3         | 1.27%   |
| Intel 12th Gen Core i5-1235U            | 3         | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 1.27%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 0.84%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 2         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.84%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 0.84%   |
| Intel Core i5-5350U CPU @ 1.80GHz       | 2         | 0.84%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 2         | 0.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.84%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.84%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 2         | 0.84%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 0.84%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 0.84%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 2         | 0.84%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 2         | 0.84%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 2         | 0.84%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 2         | 0.84%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 0.84%   |
| Intel Celeron N4120 CPU @ 1.10GHz       | 2         | 0.84%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 2         | 0.84%   |
| Intel Celeron CPU N3450 @ 1.10GHz       | 2         | 0.84%   |
| Intel Celeron CPU 1007U @ 1.50GHz       | 2         | 0.84%   |
| Intel Atom CPU N570 @ 1.66GHz           | 2         | 0.84%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 2         | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 47        | 19.83%  |
| Intel Core i7           | 38        | 16.03%  |
| Other                   | 28        | 11.81%  |
| Intel Core i3           | 21        | 8.86%   |
| Intel Celeron           | 18        | 7.59%   |
| AMD Ryzen 5             | 13        | 5.49%   |
| Intel Core 2 Duo        | 11        | 4.64%   |
| AMD Ryzen 7             | 11        | 4.64%   |
| Intel Atom              | 10        | 4.22%   |
| Intel Pentium           | 4         | 1.69%   |
| AMD Ryzen 3             | 4         | 1.69%   |
| Intel Core 2            | 3         | 1.27%   |
| AMD Ryzen 9             | 3         | 1.27%   |
| Intel Pentium M         | 2         | 0.84%   |
| Intel Pentium Dual-Core | 2         | 0.84%   |
| Intel Genuine           | 2         | 0.84%   |
| AMD E1                  | 2         | 0.84%   |
| AMD A6                  | 2         | 0.84%   |
| AMD A4                  | 2         | 0.84%   |
| Intel Xeon              | 1         | 0.42%   |
| Intel Pentium Silver    | 1         | 0.42%   |
| Intel Pentium Gold      | 1         | 0.42%   |
| Intel Pentium Dual      | 1         | 0.42%   |
| Intel Celeron Dual-Core | 1         | 0.42%   |
| AMD Turion 64 X2 Mobile | 1         | 0.42%   |
| AMD Turion 64 Mobile    | 1         | 0.42%   |
| AMD Sempron             | 1         | 0.42%   |
| AMD Phenom II           | 1         | 0.42%   |
| AMD E2                  | 1         | 0.42%   |
| AMD E                   | 1         | 0.42%   |
| AMD A8                  | 1         | 0.42%   |
| AMD A12                 | 1         | 0.42%   |
| AMD A10                 | 1         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 120       | 50.63%  |
| 4      | 64        | 27%     |
| 6      | 18        | 7.59%   |
| 8      | 16        | 6.75%   |
| 1      | 9         | 3.8%    |
| 10     | 4         | 1.69%   |
| 14     | 3         | 1.27%   |
| 12     | 2         | 0.84%   |
| 5      | 1         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 237       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 163       | 68.78%  |
| 1      | 74        | 31.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 233       | 98.31%  |
| 32-bit         | 4         | 1.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 11.16%  |
| 0x206a7    | 18        | 7.44%   |
| 0x406e3    | 13        | 5.37%   |
| 0x306a9    | 13        | 5.37%   |
| 0x806c1    | 12        | 4.96%   |
| 0x0a50000c | 11        | 4.55%   |
| 0x30678    | 8         | 3.31%   |
| 0x1067a    | 8         | 3.31%   |
| 0x506e3    | 7         | 2.89%   |
| 0x806e9    | 6         | 2.48%   |
| 0x306c3    | 6         | 2.48%   |
| 0x20655    | 6         | 2.48%   |
| 0x08608103 | 6         | 2.48%   |
| 0xa0652    | 5         | 2.07%   |
| 0x906ea    | 5         | 2.07%   |
| 0x906a3    | 5         | 2.07%   |
| 0x806ea    | 5         | 2.07%   |
| 0x706a8    | 5         | 2.07%   |
| 0x306d4    | 5         | 2.07%   |
| 0x906a4    | 4         | 1.65%   |
| 0x6fd      | 4         | 1.65%   |
| 0x406c4    | 4         | 1.65%   |
| 0x40651    | 4         | 1.65%   |
| 0x08108102 | 4         | 1.65%   |
| 0x906e9    | 3         | 1.24%   |
| 0x806ec    | 3         | 1.24%   |
| 0x806d1    | 2         | 0.83%   |
| 0x706a1    | 2         | 0.83%   |
| 0x6f6      | 2         | 0.83%   |
| 0x106ca    | 2         | 0.83%   |
| 0x10676    | 2         | 0.83%   |
| 0x08600104 | 2         | 0.83%   |
| 0x07030106 | 2         | 0.83%   |
| 0x0600611a | 2         | 0.83%   |
| 0x06001119 | 2         | 0.83%   |
| 0xb06a3    | 1         | 0.41%   |
| 0xa0671    | 1         | 0.41%   |
| 0x906ed    | 1         | 0.41%   |
| 0x906c0    | 1         | 0.41%   |
| 0x806eb    | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 25        | 10.55%  |
| Skylake          | 21        | 8.86%   |
| SandyBridge      | 20        | 8.44%   |
| TigerLake        | 15        | 6.33%   |
| IvyBridge        | 15        | 6.33%   |
| Unknown          | 15        | 6.33%   |
| Zen 3            | 13        | 5.49%   |
| Silvermont       | 12        | 5.06%   |
| Haswell          | 12        | 5.06%   |
| Penryn           | 11        | 4.64%   |
| Core             | 9         | 3.8%    |
| Westmere         | 8         | 3.38%   |
| Goldmont plus    | 7         | 2.95%   |
| Zen+             | 6         | 2.53%   |
| Icelake          | 6         | 2.53%   |
| CometLake        | 5         | 2.11%   |
| Broadwell        | 5         | 2.11%   |
| Excavator        | 4         | 1.69%   |
| Alderlake Hybrid | 4         | 1.69%   |
| Zen 2            | 3         | 1.27%   |
| Puma             | 3         | 1.27%   |
| P6               | 3         | 1.27%   |
| Bonnell          | 3         | 1.27%   |
| Piledriver       | 2         | 0.84%   |
| K8 Hammer        | 2         | 0.84%   |
| Goldmont         | 2         | 0.84%   |
| Bobcat           | 2         | 0.84%   |
| Tremont          | 1         | 0.42%   |
| Nehalem          | 1         | 0.42%   |
| K8 & K10 hybrid  | 1         | 0.42%   |
| K10              | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 178       | 61.59%  |
| Nvidia | 56        | 19.38%  |
| AMD    | 55        | 19.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 6.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 4.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 4.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 4.28%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 2.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 2.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 2.3%    |
| AMD Lucienne                                                                             | 7         | 2.3%    |
| Intel HD Graphics 530                                                                    | 6         | 1.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.97%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.64%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.64%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 5         | 1.64%   |
| Intel HD Graphics 620                                                                    | 5         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.64%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.32%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.99%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.99%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 0.99%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 3         | 0.99%   |
| AMD Barcelo                                                                              | 3         | 0.99%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.66%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.66%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.66%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.66%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.66%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.66%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 2         | 0.66%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 132       | 55.7%   |
| Intel + Nvidia | 36        | 15.19%  |
| 1 x AMD        | 35        | 14.77%  |
| 1 x Nvidia     | 13        | 5.49%   |
| Intel + AMD    | 9         | 3.8%    |
| AMD + Nvidia   | 6         | 2.53%   |
| 2 x AMD        | 5         | 2.11%   |
| 2 x Intel      | 1         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 209       | 86.72%  |
| Proprietary | 20        | 8.3%    |
| Unknown     | 12        | 4.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 181       | 75.42%  |
| 0.01-0.5   | 32        | 13.33%  |
| 1.01-2.0   | 8         | 3.33%   |
| 3.01-4.0   | 7         | 2.92%   |
| 0.51-1.0   | 7         | 2.92%   |
| 7.01-8.0   | 3         | 1.25%   |
| 5.01-6.0   | 1         | 0.42%   |
| 2.01-3.0   | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 46        | 17.97%  |
| Chimei Innolux          | 45        | 17.58%  |
| BOE                     | 30        | 11.72%  |
| LG Display              | 25        | 9.77%   |
| Samsung Electronics     | 23        | 8.98%   |
| Apple                   | 11        | 4.3%    |
| Chi Mei Optoelectronics | 10        | 3.91%   |
| PANDA                   | 9         | 3.52%   |
| Hewlett-Packard         | 9         | 3.52%   |
| Lenovo                  | 6         | 2.34%   |
| Goldstar                | 5         | 1.95%   |
| Sharp                   | 4         | 1.56%   |
| Ancor Communications    | 4         | 1.56%   |
| Sony                    | 3         | 1.17%   |
| CPT                     | 3         | 1.17%   |
| InfoVision              | 2         | 0.78%   |
| HannStar                | 2         | 0.78%   |
| Dell                    | 2         | 0.78%   |
| ASUSTek Computer        | 2         | 0.78%   |
| TMX                     | 1         | 0.39%   |
| Sunplus                 | 1         | 0.39%   |
| STA                     | 1         | 0.39%   |
| Quanta Display          | 1         | 0.39%   |
| Philips                 | 1         | 0.39%   |
| Panasonic               | 1         | 0.39%   |
| Packard Bell            | 1         | 0.39%   |
| ONN                     | 1         | 0.39%   |
| NEC Computers           | 1         | 0.39%   |
| LTM                     | 1         | 0.39%   |
| LG Philips              | 1         | 0.39%   |
| KDC                     | 1         | 0.39%   |
| HKC                     | 1         | 0.39%   |
| Eizo                    | 1         | 0.39%   |
| Acer                    | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 2.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 1.17%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 3         | 1.17%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 1.17%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 1.17%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                  | 2         | 0.78%   |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch                 | 2         | 0.78%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.78%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.78%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.78%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                     | 2         | 0.78%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 2         | 0.78%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                    | 1         | 0.39%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.39%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.39%   |
| Sony TV SNY3001 1920x1080                                                | 1         | 0.39%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.39%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.39%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP1445 3840x2160 346x194mm 15.6-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM0458 1360x768                          | 1         | 0.39%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 527x296mm 23.8-inch        | 1         | 0.39%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch        | 1         | 0.39%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 0.39%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch        | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 353x198mm 15.9-inch     | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 103       | 42.04%  |
| 1366x768 (WXGA)    | 70        | 28.57%  |
| 1280x800 (WXGA)    | 13        | 5.31%   |
| 3840x2160 (4K)     | 12        | 4.9%    |
| 1600x900 (HD+)     | 10        | 4.08%   |
| 1920x1200 (WUXGA)  | 5         | 2.04%   |
| 2560x1600          | 4         | 1.63%   |
| 2880x1800          | 3         | 1.22%   |
| 1440x900 (WXGA+)   | 3         | 1.22%   |
| 1024x768 (XGA)     | 3         | 1.22%   |
| 2560x1440 (QHD)    | 2         | 0.82%   |
| 2560x1080          | 2         | 0.82%   |
| 2256x1504          | 2         | 0.82%   |
| 2160x1440          | 2         | 0.82%   |
| 1680x1050 (WSXGA+) | 2         | 0.82%   |
| 1280x1024 (SXGA)   | 2         | 0.82%   |
| 1024x600           | 2         | 0.82%   |
| 3840x2400          | 1         | 0.41%   |
| 3200x2000          | 1         | 0.41%   |
| 3200x1800 (QHD+)   | 1         | 0.41%   |
| 1400x1050          | 1         | 0.41%   |
| 1360x768           | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 110       | 42.97%  |
| 13      | 32        | 12.5%   |
| 14      | 23        | 8.98%   |
| 17      | 21        | 8.2%    |
| 24      | 13        | 5.08%   |
| 11      | 12        | 4.69%   |
| 23      | 8         | 3.13%   |
| 16      | 5         | 1.95%   |
| 12      | 5         | 1.95%   |
| 21      | 4         | 1.56%   |
| 10      | 4         | 1.56%   |
| 19      | 3         | 1.17%   |
| Unknown | 3         | 1.17%   |
| 40      | 2         | 0.78%   |
| 34      | 2         | 0.78%   |
| 27      | 2         | 0.78%   |
| 84      | 1         | 0.39%   |
| 46      | 1         | 0.39%   |
| 43      | 1         | 0.39%   |
| 36      | 1         | 0.39%   |
| 32      | 1         | 0.39%   |
| 26      | 1         | 0.39%   |
| 25      | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 151       | 59.22%  |
| 201-300     | 35        | 13.73%  |
| 351-400     | 28        | 10.98%  |
| 501-600     | 24        | 9.41%   |
| 401-500     | 5         | 1.96%   |
| 701-800     | 4         | 1.57%   |
| Unknown     | 3         | 1.18%   |
| 801-900     | 2         | 0.78%   |
| 1501-2000   | 1         | 0.39%   |
| 1001-1500   | 1         | 0.39%   |
| 901-1000    | 1         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 188       | 80.34%  |
| 16/10   | 33        | 14.1%   |
| 4/3     | 4         | 1.71%   |
| 3/2     | 4         | 1.71%   |
| 5/4     | 2         | 0.85%   |
| 21/9    | 2         | 0.85%   |
| Unknown | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 110       | 42.97%  |
| 81-90          | 47        | 18.36%  |
| 121-130        | 22        | 8.59%   |
| 201-250        | 20        | 7.81%   |
| 51-60          | 12        | 4.69%   |
| 71-80          | 7         | 2.73%   |
| 61-70          | 5         | 1.95%   |
| 251-300        | 5         | 1.95%   |
| 501-1000       | 5         | 1.95%   |
| 41-50          | 4         | 1.56%   |
| 151-200        | 4         | 1.56%   |
| 351-500        | 3         | 1.17%   |
| 301-350        | 3         | 1.17%   |
| 111-120        | 3         | 1.17%   |
| Unknown        | 3         | 1.17%   |
| 91-100         | 2         | 0.78%   |
| More than 1000 | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 109       | 43.43%  |
| 101-120       | 63        | 25.1%   |
| 51-100        | 49        | 19.52%  |
| 161-240       | 17        | 6.77%   |
| More than 240 | 8         | 3.19%   |
| Unknown       | 3         | 1.2%    |
| 1-50          | 2         | 0.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 196       | 80.99%  |
| 2     | 31        | 12.81%  |
| 0     | 12        | 4.96%   |
| 3     | 3         | 1.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 122       | 31.44%  |
| Intel                             | 122       | 31.44%  |
| Qualcomm Atheros                  | 48        | 12.37%  |
| Broadcom                          | 25        | 6.44%   |
| Broadcom Limited                  | 10        | 2.58%   |
| MediaTek                          | 9         | 2.32%   |
| Marvell Technology Group          | 7         | 1.8%    |
| TP-Link                           | 6         | 1.55%   |
| Ralink                            | 5         | 1.29%   |
| Samsung Electronics               | 4         | 1.03%   |
| Motorola PCS                      | 4         | 1.03%   |
| ASIX Electronics                  | 4         | 1.03%   |
| OPPO Electronics                  | 3         | 0.77%   |
| Sierra Wireless                   | 2         | 0.52%   |
| Qualcomm Atheros Communications   | 2         | 0.52%   |
| Nvidia                            | 2         | 0.52%   |
| Sweex                             | 1         | 0.26%   |
| Ralink Technology                 | 1         | 0.26%   |
| Qualcomm Technologies             | 1         | 0.26%   |
| NetGear                           | 1         | 0.26%   |
| Lenovo                            | 1         | 0.26%   |
| Foxconn / Hon Hai                 | 1         | 0.26%   |
| FIBOCOM                           | 1         | 0.26%   |
| Ericsson Business Mobile Networks | 1         | 0.26%   |
| Dell                              | 1         | 0.26%   |
| D-Link                            | 1         | 0.26%   |
| Attansic Technology               | 1         | 0.26%   |
| ASUSTek Computer                  | 1         | 0.26%   |
| AMD                               | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 76        | 16.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 15        | 3.26%   |
| Intel Wireless 8260                                                     | 12        | 2.61%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 2.61%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 2.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.52%   |
| Intel Wireless 8265 / 8275                                              | 7         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 1.3%    |
| Intel Wireless 7265                                                     | 6         | 1.3%    |
| Intel Wireless 3165                                                     | 6         | 1.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.3%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.3%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.09%   |
| Intel Wireless 7260                                                     | 5         | 1.09%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 1.09%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 1.09%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 0.87%   |
| Intel 82567LM Gigabit Network Connection                                | 4         | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                           | 4         | 0.87%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.65%   |
| OPPO SM8350-MTP _SN:9338D66C                                            | 3         | 0.65%   |
| Motorola PCS moto g(7) power                                            | 3         | 0.65%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 47.41%  |
| Realtek Semiconductor           | 40        | 15.94%  |
| Qualcomm Atheros                | 37        | 14.74%  |
| Broadcom                        | 17        | 6.77%   |
| MediaTek                        | 9         | 3.59%   |
| Broadcom Limited                | 8         | 3.19%   |
| TP-Link                         | 5         | 1.99%   |
| Ralink                          | 5         | 1.99%   |
| Sierra Wireless                 | 2         | 0.8%    |
| Qualcomm Atheros Communications | 2         | 0.8%    |
| Sweex                           | 1         | 0.4%    |
| Ralink Technology               | 1         | 0.4%    |
| Qualcomm Technologies           | 1         | 0.4%    |
| NetGear                         | 1         | 0.4%    |
| FIBOCOM                         | 1         | 0.4%    |
| D-Link                          | 1         | 0.4%    |
| ASUSTek Computer                | 1         | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 12        | 4.78%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 4.78%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 4.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 3.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 2.79%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.39%   |
| Intel Wireless 7265                                                     | 6         | 2.39%   |
| Intel Wireless 3165                                                     | 6         | 2.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2.39%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 2.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 1.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.99%   |
| Intel Wireless 7260                                                     | 5         | 1.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.59%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 1.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 1.2%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.2%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.2%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 1.2%    |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.2%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 3         | 1.2%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.2%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.8%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.8%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 2         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 106       | 52.48%  |
| Intel                    | 40        | 19.8%   |
| Qualcomm Atheros         | 16        | 7.92%   |
| Broadcom                 | 11        | 5.45%   |
| Marvell Technology Group | 7         | 3.47%   |
| Samsung Electronics      | 4         | 1.98%   |
| ASIX Electronics         | 4         | 1.98%   |
| OPPO Electronics         | 3         | 1.49%   |
| Motorola PCS             | 3         | 1.49%   |
| Nvidia                   | 2         | 0.99%   |
| Broadcom Limited         | 2         | 0.99%   |
| TP-Link                  | 1         | 0.5%    |
| Lenovo                   | 1         | 0.5%    |
| Foxconn / Hon Hai        | 1         | 0.5%    |
| Attansic Technology      | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 76        | 37.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 7.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 3.92%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 2.45%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 2.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1.96%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 1.96%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.96%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 1.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 1.47%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 3         | 1.47%   |
| Motorola PCS moto g(7) power                                           | 3         | 1.47%   |
| Intel Ethernet Connection I219-V                                       | 3         | 1.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.98%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.98%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 0.98%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 0.98%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.98%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.98%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.98%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.98%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 0.98%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 0.98%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.98%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                    | 2         | 0.98%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.49%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.49%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.49%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 229       | 54.01%  |
| Ethernet | 190       | 44.81%  |
| Modem    | 4         | 0.94%   |
| Unknown  | 1         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 181       | 75.73%  |
| Ethernet | 58        | 24.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 172       | 71.97%  |
| 1     | 58        | 24.27%  |
| 0     | 7         | 2.93%   |
| 3     | 2         | 0.84%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 176       | 73.33%  |
| Yes  | 64        | 26.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 88        | 44.67%  |
| Realtek Semiconductor           | 20        | 10.15%  |
| Qualcomm Atheros Communications | 17        | 8.63%   |
| Lite-On Technology              | 11        | 5.58%   |
| Apple                           | 11        | 5.58%   |
| Foxconn / Hon Hai               | 10        | 5.08%   |
| Broadcom                        | 9         | 4.57%   |
| IMC Networks                    | 8         | 4.06%   |
| Cambridge Silicon Radio         | 7         | 3.55%   |
| Hewlett-Packard                 | 5         | 2.54%   |
| Ralink                          | 4         | 2.03%   |
| Dell                            | 2         | 1.02%   |
| Realtek                         | 1         | 0.51%   |
| Ralink Technology               | 1         | 0.51%   |
| MediaTek                        | 1         | 0.51%   |
| ASUSTek Computer                | 1         | 0.51%   |
| Alps Electric                   | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 20        | 10.15%  |
| Realtek Bluetooth Radio                                                             | 17        | 8.63%   |
| Intel Bluetooth Device                                                              | 16        | 8.12%   |
| Intel AX201 Bluetooth                                                               | 16        | 8.12%   |
| Intel AX200 Bluetooth                                                               | 12        | 6.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 5.58%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 4.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 3.55%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.54%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 2.03%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 2.03%   |
| IMC Networks Wireless_Device                                                        | 4         | 2.03%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 2.03%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.52%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.52%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.52%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 1.52%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.52%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.02%   |
| Lite-On Wireless_Device                                                             | 2         | 1.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.02%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.02%   |
| Intel AX211 Bluetooth                                                               | 2         | 1.02%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.02%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 1.02%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.02%   |
| Apple Bluetooth HCI                                                                 | 2         | 1.02%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.51%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.51%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.51%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.51%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.51%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.51%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.51%   |
| MediaTek Wireless_Device                                                            | 1         | 0.51%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.51%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 180       | 63.16%  |
| AMD                     | 46        | 16.14%  |
| Nvidia                  | 42        | 14.74%  |
| Realtek Semiconductor   | 2         | 0.7%    |
| JMTek                   | 2         | 0.7%    |
| VIA Technologies        | 1         | 0.35%   |
| Texas Instruments       | 1         | 0.35%   |
| Plantronics             | 1         | 0.35%   |
| Logitech                | 1         | 0.35%   |
| Lenovo                  | 1         | 0.35%   |
| Guillemot               | 1         | 0.35%   |
| Generalplus Technology  | 1         | 0.35%   |
| Focusrite-Novation      | 1         | 0.35%   |
| FIFINE 683 Microphone   | 1         | 0.35%   |
| Conexant Systems        | 1         | 0.35%   |
| CMX Systems             | 1         | 0.35%   |
| C-Media Electronics     | 1         | 0.35%   |
| BEHRINGER International | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 31        | 9.09%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 7.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 5.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 20        | 5.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 4.11%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 2.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.05%   |
| Nvidia Audio device                                                                               | 6         | 1.76%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.76%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.76%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.47%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.47%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.47%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.47%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 1.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 1.17%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.17%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 1.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.88%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.59%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.59%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.59%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.59%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Samsung Electronics            | 72        | 25.17%  |
| SK hynix                       | 59        | 20.63%  |
| Unknown                        | 31        | 10.84%  |
| Micron Technology              | 29        | 10.14%  |
| Kingston                       | 24        | 8.39%   |
| Crucial                        | 17        | 5.94%   |
| Elpida                         | 7         | 2.45%   |
| Unknown (ABCD)                 | 5         | 1.75%   |
| Corsair                        | 5         | 1.75%   |
| A-DATA Technology              | 5         | 1.75%   |
| Nanya Technology               | 4         | 1.4%    |
| Transcend                      | 3         | 1.05%   |
| Smart                          | 3         | 1.05%   |
| Ramaxel Technology             | 3         | 1.05%   |
| Unknown                        | 3         | 1.05%   |
| G.Skill                        | 2         | 0.7%    |
| Wilk                           | 1         | 0.35%   |
| Unifosa                        | 1         | 0.35%   |
| Team                           | 1         | 0.35%   |
| PNY                            | 1         | 0.35%   |
| Patriot                        | 1         | 0.35%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.35%   |
| Lexar Co Limited               | 1         | 0.35%   |
| Innodisk                       | 1         | 0.35%   |
| Hewlett-Packard                | 1         | 0.35%   |
| Essencore                      | 1         | 0.35%   |
| CSX                            | 1         | 0.35%   |
| Avant                          | 1         | 0.35%   |
| ASint Technology               | 1         | 0.35%   |
| 48spaces                       | 1         | 0.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.97%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 6         | 1.97%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 1.64%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.64%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 1.31%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.31%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.31%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.98%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.98%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.98%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 0.98%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.98%   |
| Unknown                                                          | 3         | 0.98%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.66%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.66%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.66%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.66%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM 1334MT/s             | 2         | 0.66%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.66%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.66%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.66%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.66%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.66%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.66%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 2         | 0.66%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.66%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.66%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 105       | 43.39%  |
| DDR3    | 95        | 39.26%  |
| DDR2    | 13        | 5.37%   |
| LPDDR4  | 9         | 3.72%   |
| SDRAM   | 5         | 2.07%   |
| DDR     | 5         | 2.07%   |
| LPDDR3  | 4         | 1.65%   |
| DRAM    | 2         | 0.83%   |
| DDR5    | 2         | 0.83%   |
| LPDDR5  | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 225       | 92.21%  |
| Row Of Chips | 14        | 5.74%   |
| DIMM         | 2         | 0.82%   |
| Unknown      | 2         | 0.82%   |
| Chip         | 1         | 0.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 98        | 36.84%  |
| 4096  | 79        | 29.7%   |
| 2048  | 39        | 14.66%  |
| 16384 | 30        | 11.28%  |
| 1024  | 13        | 4.89%   |
| 32768 | 6         | 2.26%   |
| 512   | 1         | 0.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 58        | 22.31%  |
| 3200    | 54        | 20.77%  |
| 2667    | 33        | 12.69%  |
| 2400    | 17        | 6.54%   |
| 1334    | 17        | 6.54%   |
| 1333    | 16        | 6.15%   |
| Unknown | 12        | 4.62%   |
| 667     | 11        | 4.23%   |
| 2133    | 10        | 3.85%   |
| 1067    | 8         | 3.08%   |
| 4199    | 3         | 1.15%   |
| 975     | 3         | 1.15%   |
| 4800    | 2         | 0.77%   |
| 4267    | 2         | 0.77%   |
| 3266    | 2         | 0.77%   |
| 1867    | 2         | 0.77%   |
| 533     | 2         | 0.77%   |
| 8400    | 1         | 0.38%   |
| 5500    | 1         | 0.38%   |
| 4266    | 1         | 0.38%   |
| 2933    | 1         | 0.38%   |
| 2048    | 1         | 0.38%   |
| 1866    | 1         | 0.38%   |
| 800     | 1         | 0.38%   |
| 166     | 1         | 0.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Canon              | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 25%     |
| HP LaserJet 1022         | 1         | 25%     |
| Canon LiDE 400           | 1         | 25%     |
| Brother DCP-L2540DW      | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 47        | 23.38%  |
| IMC Networks                           | 21        | 10.45%  |
| Microdia                               | 16        | 7.96%   |
| Realtek Semiconductor                  | 15        | 7.46%   |
| Quanta                                 | 14        | 6.97%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 5.97%   |
| Bison Electronics                      | 12        | 5.97%   |
| Suyin                                  | 8         | 3.98%   |
| Luxvisions Innotech Limited            | 8         | 3.98%   |
| Sunplus Innovation Technology          | 7         | 3.48%   |
| Apple                                  | 7         | 3.48%   |
| Acer                                   | 6         | 2.99%   |
| Lite-On Technology                     | 5         | 2.49%   |
| Ricoh                                  | 4         | 1.99%   |
| Alcor Micro                            | 4         | 1.99%   |
| Silicon Motion                         | 3         | 1.49%   |
| Logitech                               | 3         | 1.49%   |
| Lenovo                                 | 3         | 1.49%   |
| Z-Star Microelectronics                | 1         | 0.5%    |
| Y Media                                | 1         | 0.5%    |
| Primax Electronics                     | 1         | 0.5%    |
| Novatek Microelectronics               | 1         | 0.5%    |
| Hewlett-Packard                        | 1         | 0.5%    |
| Goodong Industry                       | 1         | 0.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 13        | 6.47%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 6         | 2.99%   |
| Quanta HD User Facing                                | 5         | 2.49%   |
| Microdia Integrated_Webcam_HD                        | 5         | 2.49%   |
| IMC Networks Integrated Camera                       | 5         | 2.49%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 4         | 1.99%   |
| Bison BisonCam,NB Pro                                | 4         | 1.99%   |
| Realtek Integrated_Webcam_HD                         | 3         | 1.49%   |
| Quanta HP TrueVision HD Camera                       | 3         | 1.49%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 1.49%   |
| Chicony HD WebCam                                    | 3         | 1.49%   |
| Chicony HD User Facing                               | 3         | 1.49%   |
| Bison Integrated Camera                              | 3         | 1.49%   |
| Suyin HP TrueVision HD Integrated Webcam             | 2         | 1%      |
| Suyin Acer CrystalEye Webcam                         | 2         | 1%      |
| Sunplus Integrated_Webcam_HD                         | 2         | 1%      |
| Sunplus HD WebCam                                    | 2         | 1%      |
| Ricoh USB2.0 Camera                                  | 2         | 1%      |
| Realtek USB2.0 HD UVC WebCam                         | 2         | 1%      |
| Realtek USB Camera                                   | 2         | 1%      |
| Microdia Webcam Vitade AF                            | 2         | 1%      |
| Microdia USB 2.0 Camera                              | 2         | 1%      |
| Luxvisions Innotech Limited Integrated Camera        | 2         | 1%      |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 1%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 1%      |
| Lite-On HP HD Webcam                                 | 2         | 1%      |
| Lite-On HP HD Camera                                 | 2         | 1%      |
| Lenovo Integrated Webcam [R5U877]                    | 2         | 1%      |
| IMC Networks XHC Camera                              | 2         | 1%      |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 1%      |
| IMC Networks USB2.0 UVC HD Webcam                    | 2         | 1%      |
| Chicony Integrated Camera (1280x720@30)              | 2         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 2         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 2         | 1%      |
| Bison HD Webcam                                      | 2         | 1%      |
| Apple FaceTime HD Camera (Built-in)                  | 2         | 1%      |
| Apple Built-in iSight                                | 2         | 1%      |
| Alcor Micro USB 2.0 PC cam                           | 2         | 1%      |
| Acer ThinkPad P50 Integrated Camera                  | 2         | 1%      |
| Acer Integrated Camera                               | 2         | 1%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 14        | 32.56%  |
| Synaptics                          | 8         | 18.6%   |
| Shenzhen Goodix Technology         | 6         | 13.95%  |
| AuthenTec                          | 6         | 13.95%  |
| Elan Microelectronics              | 4         | 9.3%    |
| Upek                               | 3         | 6.98%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.33%   |
| Focal-systems.Corp                 | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 11.63%  |
| Shenzhen Goodix  FingerPrint Device                             | 5         | 11.63%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 4         | 9.3%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 3         | 6.98%   |
| AuthenTec AES2810                                               | 3         | 6.98%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 2         | 4.65%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 4.65%   |
| Elan ELAN:Fingerprint                                           | 2         | 4.65%   |
| Elan ELAN:ARM-M4                                                | 2         | 4.65%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 2         | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 2.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 2.33%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 2.33%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 2.33%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 2.33%   |
| Upek TCS5B Fingerprint sensor                                   | 1         | 2.33%   |
| Synaptics UWP WBDI Device                                       | 1         | 2.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 2.33%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 2.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.33%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 2.33%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 2.33%   |
| Unknown                                                         | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 7         | 43.75%  |
| Broadcom              | 6         | 37.5%   |
| Advanced Card Systems | 2         | 12.5%   |
| O2 Micro              | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 7         | 43.75%  |
| Broadcom 5880                                  | 4         | 25%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor | 1         | 6.25%   |
| Broadcom 58200                                 | 1         | 6.25%   |
| Advanced Card Systems ACR38 SmartCard Reader   | 1         | 6.25%   |
| Advanced Card Systems ACR122U                  | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 144       | 59.02%  |
| 1     | 72        | 29.51%  |
| 2     | 23        | 9.43%   |
| 3     | 5         | 2.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 50        | 40%     |
| Fingerprint reader       | 43        | 34.4%   |
| Chipcard                 | 14        | 11.2%   |
| Net/wireless             | 5         | 4%      |
| Multimedia controller    | 3         | 2.4%    |
| Camera                   | 3         | 2.4%    |
| Bluetooth                | 3         | 2.4%    |
| Communication controller | 2         | 1.6%    |
| Net/ethernet             | 1         | 0.8%    |
| Flash memory             | 1         | 0.8%    |

