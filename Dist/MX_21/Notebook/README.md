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

Total: 358

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.10.0-21-amd64            | 25        | 10%     |
| 6.0.0-6mx-amd64            | 24        | 9.6%    |
| 5.10.0-23-amd64            | 16        | 6.4%    |
| 5.10.0-13-amd64            | 15        | 6%      |
| 5.10.0-9-amd64             | 14        | 5.6%    |
| 5.10.0-18-amd64            | 13        | 5.2%    |
| 5.10.0-20-amd64            | 9         | 3.6%    |
| 5.10.0-16-amd64            | 9         | 3.6%    |
| 5.16.0-5mx-amd64           | 8         | 3.2%    |
| 5.14.0-4mx-amd64           | 8         | 3.2%    |
| 5.10.0-19-amd64            | 8         | 3.2%    |
| 5.10.0-14-amd64            | 7         | 2.8%    |
| 5.10.0-11-amd64            | 6         | 2.4%    |
| 6.0.0-4mx-amd64            | 5         | 2%      |
| 5.18.0-4mx-amd64           | 5         | 2%      |
| 5.10.0-22-amd64            | 5         | 2%      |
| 5.10.0-26-amd64            | 3         | 1.2%    |
| 5.10.0-17-amd64            | 3         | 1.2%    |
| 6.1.0-9mx-ahs-amd64        | 2         | 0.8%    |
| 6.1.0-8mx-ahs-amd64        | 2         | 0.8%    |
| 6.1.0-4mx-amd64            | 2         | 0.8%    |
| 6.0.0-3mx-amd64            | 2         | 0.8%    |
| 6.0.0-10.1-liquorix-amd64  | 2         | 0.8%    |
| 5.19.0-2mx-amd64           | 2         | 0.8%    |
| 5.16.0-6mx-amd64           | 2         | 0.8%    |
| 5.16.0-18.1-liquorix-amd64 | 2         | 0.8%    |
| 5.10.0-8-amd64             | 2         | 0.8%    |
| 5.10.0-25-amd64            | 2         | 0.8%    |
| 5.10.0-23-686-pae          | 2         | 0.8%    |
| 5.10.0-20-686-pae          | 2         | 0.8%    |
| 5.10.0-15-amd64            | 2         | 0.8%    |
| 5.10.0-13-686-pae          | 2         | 0.8%    |
| 5.10.0-11-686-pae          | 2         | 0.8%    |
| 5.10.0-10-amd64            | 2         | 0.8%    |
| 6.4.3-1-liquorix-amd64     | 1         | 0.4%    |
| 6.4.0-3mx-ahs-amd64        | 1         | 0.4%    |
| 6.3.0-2mx-ahs-amd64        | 1         | 0.4%    |
| 6.2.7-x64v4-xanmod1        | 1         | 0.4%    |
| 6.1.15-2-liquorix-amd64    | 1         | 0.4%    |
| 6.1.12-3-liquorix-amd64    | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 144       | 60.76%  |
| 6.0.0    | 34        | 14.35%  |
| 5.16.0   | 13        | 5.49%   |
| 6.1.0    | 10        | 4.22%   |
| 5.14.0   | 8         | 3.38%   |
| 5.18.0   | 7         | 2.95%   |
| 5.19.0   | 5         | 2.11%   |
| 5.17.0   | 4         | 1.69%   |
| 6.4.3    | 1         | 0.42%   |
| 6.4.0    | 1         | 0.42%   |
| 6.3.0    | 1         | 0.42%   |
| 6.2.7    | 1         | 0.42%   |
| 6.1.15   | 1         | 0.42%   |
| 6.1.12   | 1         | 0.42%   |
| 5.15.0   | 1         | 0.42%   |
| 5.13.0   | 1         | 0.42%   |
| 5.10.82  | 1         | 0.42%   |
| 5.10.142 | 1         | 0.42%   |
| 4.19.0   | 1         | 0.42%   |
| Unknown  | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 146       | 61.6%   |
| 6.0     | 34        | 14.35%  |
| 5.16    | 13        | 5.49%   |
| 6.1     | 12        | 5.06%   |
| 5.14    | 8         | 3.38%   |
| 5.18    | 7         | 2.95%   |
| 5.19    | 5         | 2.11%   |
| 5.17    | 4         | 1.69%   |
| 6.4     | 2         | 0.84%   |
| 6.3     | 1         | 0.42%   |
| 6.2     | 1         | 0.42%   |
| 5.15    | 1         | 0.42%   |
| 5.13    | 1         | 0.42%   |
| 4.19    | 1         | 0.42%   |
| Unknown | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 213       | 94.67%  |
| i686   | 12        | 5.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| XFCE             | 165       | 72.05%  |
| KDE5             | 45        | 19.65%  |
| GNOME            | 4         | 1.75%   |
| Unknown          | 4         | 1.75%   |
| Budgie           | 3         | 1.31%   |
| lightdm-xsession | 2         | 0.87%   |
| fluxbox          | 2         | 0.87%   |
| X-Cinnamon       | 1         | 0.44%   |
| LXQt             | 1         | 0.44%   |
| i3               | 1         | 0.44%   |
| GNOME Classic    | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 222       | 98.67%  |
| Tty     | 2         | 0.89%   |
| Wayland | 1         | 0.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 179       | 78.85%  |
| SDDM    | 43        | 18.94%  |
| SLiM    | 3         | 1.32%   |
| GDM3    | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 109       | 48.02%  |
| de_DE   | 30        | 13.22%  |
| en_GB   | 14        | 6.17%   |
| it_IT   | 11        | 4.85%   |
| ru_RU   | 7         | 3.08%   |
| fr_FR   | 7         | 3.08%   |
| pl_PL   | 4         | 1.76%   |
| en_AU   | 4         | 1.76%   |
| Unknown | 4         | 1.76%   |
| es_ES   | 3         | 1.32%   |
| en_NZ   | 3         | 1.32%   |
| de_CH   | 3         | 1.32%   |
| tr_TR   | 2         | 0.88%   |
| pt_BR   | 2         | 0.88%   |
| nl_NL   | 2         | 0.88%   |
| fi_FI   | 2         | 0.88%   |
| es_MX   | 2         | 0.88%   |
| es_AR   | 2         | 0.88%   |
| bg_BG   | 2         | 0.88%   |
| sk_SK   | 1         | 0.44%   |
| ro_RO   | 1         | 0.44%   |
| nl_BE   | 1         | 0.44%   |
| nb_NO   | 1         | 0.44%   |
| id_ID   | 1         | 0.44%   |
| hu_HU   | 1         | 0.44%   |
| fr_CA   | 1         | 0.44%   |
| fr_BE   | 1         | 0.44%   |
| es_VE   | 1         | 0.44%   |
| es_UY   | 1         | 0.44%   |
| es_PE   | 1         | 0.44%   |
| es_CO   | 1         | 0.44%   |
| en_IE   | 1         | 0.44%   |
| en_CA   | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 161       | 71.56%  |
| BIOS | 64        | 28.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 189       | 82.89%  |
| Overlay | 27        | 11.84%  |
| Btrfs   | 10        | 4.39%   |
| Xfs     | 1         | 0.44%   |
| F2fs    | 1         | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 166       | 73.78%  |
| MBR     | 58        | 25.78%  |
| Unknown | 1         | 0.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 175       | 77.09%  |
| Yes       | 52        | 22.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 135       | 59.73%  |
| Yes       | 91        | 40.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo                    | 45        | 20%     |
| Hewlett-Packard           | 40        | 17.78%  |
| ASUSTek Computer          | 27        | 12%     |
| Acer                      | 23        | 10.22%  |
| Dell                      | 22        | 9.78%   |
| Apple                     | 11        | 4.89%   |
| Sony                      | 8         | 3.56%   |
| MSI                       | 5         | 2.22%   |
| Toshiba                   | 4         | 1.78%   |
| Samsung Electronics       | 4         | 1.78%   |
| Medion                    | 4         | 1.78%   |
| Fujitsu Siemens           | 4         | 1.78%   |
| Alienware                 | 4         | 1.78%   |
| TUXEDO                    | 2         | 0.89%   |
| Notebook                  | 2         | 0.89%   |
| Gigabyte Technology       | 2         | 0.89%   |
| Chuwi                     | 2         | 0.89%   |
| Unknown                   | 2         | 0.89%   |
| win element               | 1         | 0.44%   |
| Vulcan Electronics        | 1         | 0.44%   |
| SANTECH                   | 1         | 0.44%   |
| RTD Embedded Technologies | 1         | 0.44%   |
| Linx                      | 1         | 0.44%   |
| HUAWEI                    | 1         | 0.44%   |
| Google                    | 1         | 0.44%   |
| Framework                 | 1         | 0.44%   |
| F-Plus Mobile             | 1         | 0.44%   |
| efirstview                | 1         | 0.44%   |
| CONNEX                    | 1         | 0.44%   |
| Compal                    | 1         | 0.44%   |
| Casper                    | 1         | 0.44%   |
| AMI                       | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 3         | 1.33%   |
| HP ProBook 450 G1                   | 2         | 0.89%   |
| HP Pavilion Laptop 15-eh1xxx        | 2         | 0.89%   |
| HP Laptop 17-ak0xx                  | 2         | 0.89%   |
| Chuwi GemiBook Pro                  | 2         | 0.89%   |
| Apple MacBookAir7,2                 | 2         | 0.89%   |
| Acer Nitro AN515-55                 | 2         | 0.89%   |
| win element MoreFine S500+          | 1         | 0.44%   |
| Vulcan Excursion XB                 | 1         | 0.44%   |
| TUXEDO N7x0WU                       | 1         | 0.44%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 1         | 0.44%   |
| Toshiba Satellite M70               | 1         | 0.44%   |
| Toshiba Satellite L650              | 1         | 0.44%   |
| Toshiba Satellite C845              | 1         | 0.44%   |
| Toshiba PORTEGE Z30-C               | 1         | 0.44%   |
| Sony VPCYB3V1E                      | 1         | 0.44%   |
| Sony VPCSB1V9R                      | 1         | 0.44%   |
| Sony VPCF119FX                      | 1         | 0.44%   |
| Sony VPCEH2N1E                      | 1         | 0.44%   |
| Sony VPCEC3S1E                      | 1         | 0.44%   |
| Sony VPCCB32FD                      | 1         | 0.44%   |
| Sony VGN-TZ3RXN_B                   | 1         | 0.44%   |
| Sony SVE1513Q1ESI                   | 1         | 0.44%   |
| SANTECH X170KM-G                    | 1         | 0.44%   |
| Samsung NC210/NC110                 | 1         | 0.44%   |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 0.44%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 1         | 0.44%   |
| Samsung 340XAA/350XAA/550XAA        | 1         | 0.44%   |
| RTD Embedded CMA34CR                | 1         | 0.44%   |
| Notebook PD5x_7xPNP_PNN_PNT         | 1         | 0.44%   |
| Notebook NL5xNU                     | 1         | 0.44%   |
| MSI U200                            | 1         | 0.44%   |
| MSI Modern 14 B11MOL                | 1         | 0.44%   |
| MSI GV62 8RD                        | 1         | 0.44%   |
| MSI GF63 Thin 9SC                   | 1         | 0.44%   |
| MSI Alpha 15 B5EEK                  | 1         | 0.44%   |
| Medion P6634                        | 1         | 0.44%   |
| Medion E7424 MD60750                | 1         | 0.44%   |
| Medion E14304                       | 1         | 0.44%   |
| Medion E1239T MD60139               | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 26        | 11.56%  |
| Acer Aspire           | 15        | 6.67%   |
| HP EliteBook          | 8         | 3.56%   |
| Dell Latitude         | 8         | 3.56%   |
| Lenovo IdeaPad        | 7         | 3.11%   |
| HP ProBook            | 6         | 2.67%   |
| HP Laptop             | 6         | 2.67%   |
| Dell Inspiron         | 6         | 2.67%   |
| ASUS VivoBook         | 6         | 2.67%   |
| HP Pavilion           | 4         | 1.78%   |
| Toshiba Satellite     | 3         | 1.33%   |
| HP Compaq             | 3         | 1.33%   |
| HP 250                | 3         | 1.33%   |
| Dell Vostro           | 3         | 1.33%   |
| Acer Nitro            | 3         | 1.33%   |
| Unknown               | 3         | 1.33%   |
| Lenovo V17            | 2         | 0.89%   |
| Lenovo ThinkBook      | 2         | 0.89%   |
| Lenovo Legion         | 2         | 0.89%   |
| HP ZBook              | 2         | 0.89%   |
| Fujitsu Siemens AMILO | 2         | 0.89%   |
| Dell System           | 2         | 0.89%   |
| Dell Precision        | 2         | 0.89%   |
| Chuwi GemiBook        | 2         | 0.89%   |
| ASUS TUF              | 2         | 0.89%   |
| ASUS ROG              | 2         | 0.89%   |
| ASUS ASUS             | 2         | 0.89%   |
| Apple MacBookPro11    | 2         | 0.89%   |
| Apple MacBookAir7     | 2         | 0.89%   |
| Alienware m15         | 2         | 0.89%   |
| Acer Swift            | 2         | 0.89%   |
| Acer Extensa          | 2         | 0.89%   |
| win element MoreFine  | 1         | 0.44%   |
| Vulcan Excursion      | 1         | 0.44%   |
| TUXEDO N7x0WU         | 1         | 0.44%   |
| TUXEDO InfinityBook   | 1         | 0.44%   |
| Toshiba PORTEGE       | 1         | 0.44%   |
| Sony VPCYB3V1E        | 1         | 0.44%   |
| Sony VPCSB1V9R        | 1         | 0.44%   |
| Sony VPCF119FX        | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 33        | 14.67%  |
| 2020    | 17        | 7.56%   |
| 2019    | 17        | 7.56%   |
| 2016    | 17        | 7.56%   |
| 2015    | 17        | 7.56%   |
| 2011    | 17        | 7.56%   |
| 2013    | 15        | 6.67%   |
| 2010    | 14        | 6.22%   |
| 2022    | 13        | 5.78%   |
| 2012    | 12        | 5.33%   |
| 2018    | 10        | 4.44%   |
| 2017    | 9         | 4%      |
| 2008    | 8         | 3.56%   |
| 2014    | 7         | 3.11%   |
| 2007    | 7         | 3.11%   |
| 2009    | 3         | 1.33%   |
| 2006    | 3         | 1.33%   |
| 2005    | 3         | 1.33%   |
| 2023    | 2         | 0.89%   |
| Unknown | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 225       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 223       | 99.11%  |
| Enabled  | 2         | 0.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 224       | 99.56%  |
| Yes  | 1         | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 72        | 32%     |
| 8.01-16.0   | 38        | 16.89%  |
| 3.01-4.0    | 35        | 15.56%  |
| 16.01-24.0  | 34        | 15.11%  |
| 1.01-2.0    | 17        | 7.56%   |
| 32.01-64.0  | 16        | 7.11%   |
| 2.01-3.0    | 6         | 2.67%   |
| 64.01-256.0 | 3         | 1.33%   |
| 24.01-32.0  | 2         | 0.89%   |
| 0.51-1.0    | 2         | 0.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 84        | 35.29%  |
| 2.01-3.0  | 64        | 26.89%  |
| 3.01-4.0  | 39        | 16.39%  |
| 4.01-8.0  | 27        | 11.34%  |
| 0.51-1.0  | 17        | 7.14%   |
| 8.01-16.0 | 5         | 2.1%    |
| 0.01-0.5  | 2         | 0.84%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 159       | 69.74%  |
| 2      | 52        | 22.81%  |
| 3      | 13        | 5.7%    |
| 0      | 3         | 1.32%   |
| 4      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 158       | 70.22%  |
| Yes       | 67        | 29.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 80%     |
| No        | 45        | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 217       | 95.59%  |
| No        | 10        | 4.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 179       | 79.2%   |
| No        | 47        | 20.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 48        | 21.05%  |
| Germany      | 30        | 13.16%  |
| Italy        | 20        | 8.77%   |
| Canada       | 13        | 5.7%    |
| UK           | 7         | 3.07%   |
| Russia       | 7         | 3.07%   |
| India        | 7         | 3.07%   |
| France       | 7         | 3.07%   |
| Poland       | 6         | 2.63%   |
| Australia    | 6         | 2.63%   |
| Spain        | 4         | 1.75%   |
| Serbia       | 4         | 1.75%   |
| Romania      | 4         | 1.75%   |
| New Zealand  | 4         | 1.75%   |
| Netherlands  | 4         | 1.75%   |
| Brazil       | 4         | 1.75%   |
| Belgium      | 4         | 1.75%   |
| Switzerland  | 3         | 1.32%   |
| Indonesia    | 3         | 1.32%   |
| Turkey       | 2         | 0.88%   |
| South Africa | 2         | 0.88%   |
| Greece       | 2         | 0.88%   |
| Finland      | 2         | 0.88%   |
| Egypt        | 2         | 0.88%   |
| Czechia      | 2         | 0.88%   |
| Bulgaria     | 2         | 0.88%   |
| Bangladesh   | 2         | 0.88%   |
| Austria      | 2         | 0.88%   |
| Vietnam      | 1         | 0.44%   |
| Venezuela    | 1         | 0.44%   |
| Uzbekistan   | 1         | 0.44%   |
| Uruguay      | 1         | 0.44%   |
| Tunisia      | 1         | 0.44%   |
| Sweden       | 1         | 0.44%   |
| Slovakia     | 1         | 0.44%   |
| Peru         | 1         | 0.44%   |
| Norway       | 1         | 0.44%   |
| Nepal        | 1         | 0.44%   |
| Mexico       | 1         | 0.44%   |
| Malaysia     | 1         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Milan          | 5         | 2.07%   |
| Berlin         | 4         | 1.66%   |
| Warsaw         | 3         | 1.24%   |
| Rome           | 3         | 1.24%   |
| Moscow         | 3         | 1.24%   |
| Belgrade       | 3         | 1.24%   |
| Walled Lake    | 2         | 0.83%   |
| Vienna         | 2         | 0.83%   |
| St Petersburg  | 2         | 0.83%   |
| Perth          | 2         | 0.83%   |
| Orange         | 2         | 0.83%   |
| Oakland        | 2         | 0.83%   |
| New York       | 2         | 0.83%   |
| Montreal       | 2         | 0.83%   |
| Hyderabad      | 2         | 0.83%   |
| Florence       | 2         | 0.83%   |
| Doesburg       | 2         | 0.83%   |
| Dhaka          | 2         | 0.83%   |
| Casale Litta   | 2         | 0.83%   |
| Canberra       | 2         | 0.83%   |
| Cambridge      | 2         | 0.83%   |
| Cairo          | 2         | 0.83%   |
| Amsterdam      | 2         | 0.83%   |
| Zurich         | 1         | 0.41%   |
| Zeven          | 1         | 0.41%   |
| Yekaterinburg  | 1         | 0.41%   |
| Workington     | 1         | 0.41%   |
| Wola           | 1         | 0.41%   |
| Wilmslow       | 1         | 0.41%   |
| Westland       | 1         | 0.41%   |
| Wermelskirchen | 1         | 0.41%   |
| Waycross       | 1         | 0.41%   |
| Vasco da Gama  | 1         | 0.41%   |
| Vancouver      | 1         | 0.41%   |
| Uelzen         | 1         | 0.41%   |
| Turku          | 1         | 0.41%   |
| Tunis          | 1         | 0.41%   |
| Tulsa          | 1         | 0.41%   |
| Tucson         | 1         | 0.41%   |
| Traunstein     | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 54     | 14.58%  |
| WDC                 | 35        | 35     | 11.86%  |
| Seagate             | 23        | 28     | 7.8%    |
| Unknown             | 19        | 22     | 6.44%   |
| SK hynix            | 19        | 20     | 6.44%   |
| Kingston            | 18        | 21     | 6.1%    |
| Toshiba             | 16        | 16     | 5.42%   |
| Crucial             | 15        | 32     | 5.08%   |
| Intel               | 12        | 14     | 4.07%   |
| SanDisk             | 8         | 9      | 2.71%   |
| Apple               | 7         | 10     | 2.37%   |
| Micron Technology   | 6         | 6      | 2.03%   |
| Hitachi             | 6         | 7      | 2.03%   |
| HGST                | 6         | 6      | 2.03%   |
| SPCC                | 5         | 5      | 1.69%   |
| LITEON              | 5         | 5      | 1.69%   |
| KIOXIA              | 4         | 6      | 1.36%   |
| Transcend           | 3         | 3      | 1.02%   |
| PNY                 | 3         | 3      | 1.02%   |
| Netac               | 3         | 3      | 1.02%   |
| Dogfish             | 3         | 3      | 1.02%   |
| Unknown             | 3         | 3      | 1.02%   |
| Team                | 2         | 2      | 0.68%   |
| Phison              | 2         | 3      | 0.68%   |
| Patriot             | 2         | 3      | 0.68%   |
| OCZ                 | 2         | 2      | 0.68%   |
| Fujitsu             | 2         | 2      | 0.68%   |
| EYOTA               | 2         | 2      | 0.68%   |
| Corsair             | 2         | 2      | 0.68%   |
| China               | 2         | 2      | 0.68%   |
| UMIS                | 1         | 1      | 0.34%   |
| Teclast             | 1         | 1      | 0.34%   |
| SWORDBILL           | 1         | 2      | 0.34%   |
| Silicon Motion      | 1         | 1      | 0.34%   |
| SABRENT             | 1         | 1      | 0.34%   |
| RENICE              | 1         | 1      | 0.34%   |
| Indilinx            | 1         | 1      | 0.34%   |
| Hewlett-Packard     | 1         | 1      | 0.34%   |
| Gigabyte Technology | 1         | 1      | 0.34%   |
| GeIL                | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 5         | 1.65%   |
| Unknown SD32G  32GB                    | 3         | 0.99%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 0.99%   |
| SK hynix HFM512GDJTNI-82A0A 512GB      | 3         | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 0.99%   |
| Samsung SSD 980 PRO 1TB                | 3         | 0.99%   |
| Kingston SA400S37480G 480GB SSD        | 3         | 0.99%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 0.99%   |
| Intel SSDPEKNU512GZ 512GB              | 3         | 0.99%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.99%   |
| Crucial CT480BX500SSD1 480GB           | 3         | 0.99%   |
| Crucial CT120BX500SSD1 120GB           | 3         | 0.99%   |
| Unknown                                | 3         | 0.99%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.66%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 2         | 0.66%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.66%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 0.66%   |
| Unknown SDW32G  32GB                   | 2         | 0.66%   |
| Unknown DA4064  64GB                   | 2         | 0.66%   |
| Toshiba MQ01ABD075 752GB               | 2         | 0.66%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 2         | 0.66%   |
| SPCC Solid State Disk 1TB              | 2         | 0.66%   |
| SK hynix HFS128G39TND-N210A 128GB SSD  | 2         | 0.66%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.66%   |
| Seagate ST500LM000-1EJ162 500GB        | 2         | 0.66%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 0.66%   |
| SanDisk NVMe SSD Drive 512GB           | 2         | 0.66%   |
| Samsung SSD 860 250GB                  | 2         | 0.66%   |
| Samsung SSD 850 EVO 250GB              | 2         | 0.66%   |
| Samsung MZVLB512HBJQ-000L7 512GB       | 2         | 0.66%   |
| Samsung MZALQ256HBJD-00BL2 256GB       | 2         | 0.66%   |
| Kingston SA400S37120G 120GB SSD        | 2         | 0.66%   |
| Kingston OM8PCP3512F-AI1 512GB         | 2         | 0.66%   |
| Hitachi HTS54503 320GB                 | 2         | 0.66%   |
| Hitachi HTS543216L9SA00 160GB          | 2         | 0.66%   |
| EYOTA SSD 120GB                        | 2         | 0.66%   |
| Dogfish SSD 128GB                      | 2         | 0.66%   |
| Crucial CT500MX500SSD1 500GB           | 2         | 0.66%   |
| Crucial CT240BX500SSD1 240GB           | 2         | 0.66%   |
| Crucial CT1000P2SSD8 1TB               | 2         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 28     | 31.51%  |
| WDC                 | 22        | 22     | 30.14%  |
| Toshiba             | 10        | 10     | 13.7%   |
| Hitachi             | 6         | 7      | 8.22%   |
| HGST                | 6         | 6      | 8.22%   |
| Samsung Electronics | 3         | 3      | 4.11%   |
| Fujitsu             | 2         | 2      | 2.74%   |
| Unknown             | 1         | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 26     | 18.18%  |
| Crucial             | 12        | 28     | 10.91%  |
| Kingston            | 10        | 12     | 9.09%   |
| Apple               | 6         | 9      | 5.45%   |
| SPCC                | 5         | 5      | 4.55%   |
| SanDisk             | 5         | 6      | 4.55%   |
| WDC                 | 4         | 4      | 3.64%   |
| LITEON              | 4         | 4      | 3.64%   |
| Intel               | 4         | 4      | 3.64%   |
| Transcend           | 3         | 3      | 2.73%   |
| SK hynix            | 3         | 3      | 2.73%   |
| PNY                 | 3         | 3      | 2.73%   |
| Netac               | 3         | 3      | 2.73%   |
| Dogfish             | 3         | 3      | 2.73%   |
| Toshiba             | 2         | 2      | 1.82%   |
| OCZ                 | 2         | 2      | 1.82%   |
| Micron Technology   | 2         | 2      | 1.82%   |
| EYOTA               | 2         | 2      | 1.82%   |
| China               | 2         | 2      | 1.82%   |
| Unknown             | 2         | 2      | 1.82%   |
| Teclast             | 1         | 1      | 0.91%   |
| Team                | 1         | 1      | 0.91%   |
| SWORDBILL           | 1         | 2      | 0.91%   |
| SABRENT             | 1         | 1      | 0.91%   |
| RENICE              | 1         | 1      | 0.91%   |
| Patriot             | 1         | 1      | 0.91%   |
| Indilinx            | 1         | 1      | 0.91%   |
| Hewlett-Packard     | 1         | 1      | 0.91%   |
| Gigabyte Technology | 1         | 1      | 0.91%   |
| GeIL                | 1         | 1      | 0.91%   |
| CT500MX5            | 1         | 1      | 0.91%   |
| Corsair             | 1         | 1      | 0.91%   |
| Apacer              | 1         | 1      | 0.91%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 95        | 139    | 34.93%  |
| NVMe    | 85        | 105    | 31.25%  |
| HDD     | 72        | 79     | 26.47%  |
| MMC     | 19        | 23     | 6.99%   |
| Unknown | 1         | 1      | 0.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 145       | 213    | 57.09%  |
| NVMe | 85        | 105    | 33.46%  |
| MMC  | 19        | 23     | 7.48%   |
| SAS  | 5         | 6      | 1.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 124       | 161    | 76.07%  |
| 0.51-1.0   | 35        | 53     | 21.47%  |
| 1.01-2.0   | 3         | 3      | 1.84%   |
| 3.01-4.0   | 1         | 1      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 60        | 25.75%  |
| 101-250        | 59        | 25.32%  |
| 21-50          | 32        | 13.73%  |
| 501-1000       | 28        | 12.02%  |
| 51-100         | 25        | 10.73%  |
| 1-20           | 12        | 5.15%   |
| 1001-2000      | 11        | 4.72%   |
| More than 3000 | 4         | 1.72%   |
| 2001-3000      | 2         | 0.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 112       | 46.47%  |
| 21-50          | 33        | 13.69%  |
| 51-100         | 32        | 13.28%  |
| 101-250        | 28        | 11.62%  |
| 251-500        | 17        | 7.05%   |
| 501-1000       | 10        | 4.15%   |
| 1001-2000      | 6         | 2.49%   |
| More than 3000 | 2         | 0.83%   |
| 2001-3000      | 1         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 2      | 5.56%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 2.78%   |
| WDC WD3200BPVT-24JJ5T0 320GB                        | 1         | 1      | 2.78%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 1         | 1      | 2.78%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD                | 1         | 1      | 2.78%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 2.78%   |
| Toshiba MK5059GSXP 500GB                            | 1         | 1      | 2.78%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 2.78%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 2.78%   |
| Seagate ST9320421AS 320GB                           | 1         | 1      | 2.78%   |
| Seagate ST9160821AS 160GB                           | 1         | 1      | 2.78%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 1         | 1      | 2.78%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 2.78%   |
| Seagate ST500LM000-1EJ162 500GB                     | 1         | 1      | 2.78%   |
| Seagate ST320LT007-9ZV142 320GB                     | 1         | 4      | 2.78%   |
| Samsung Electronics SSD 840 PRO Series 256GB        | 1         | 1      | 2.78%   |
| Samsung Electronics SSD 830 Series 128GB            | 1         | 2      | 2.78%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 2.78%   |
| Samsung Electronics HM080HC 80GB                    | 1         | 1      | 2.78%   |
| RENICE X2 64GB SSD                                  | 1         | 1      | 2.78%   |
| OCZ VERTEX2 64GB SSD                                | 1         | 1      | 2.78%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 2.78%   |
| Kingston SA400S37120G 120GB SSD                     | 1         | 1      | 2.78%   |
| Intel SSDSC2BF240A5L 240GB                          | 1         | 1      | 2.78%   |
| Intel SSDSA2M040G2GC 40GB                           | 1         | 1      | 2.78%   |
| Intel SSDPEKKF512G8L 512GB                          | 1         | 2      | 2.78%   |
| Indilinx IND-S325S120G 120GB SSD                    | 1         | 1      | 2.78%   |
| Hitachi HTS545032B9A300 320GB                       | 1         | 1      | 2.78%   |
| Hitachi HTS543216L9SA00 160GB                       | 1         | 1      | 2.78%   |
| Hitachi HTS541080G9SA00 80GB                        | 1         | 1      | 2.78%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 2.78%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.78%   |
| HGST HTS541075A9E680 752GB                          | 1         | 1      | 2.78%   |
| Fujitsu MHT2080AT 80GB                              | 1         | 1      | 2.78%   |
| Crucial CT1000MX500SSD4 1TB                         | 1         | 6      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 10     | 19.44%  |
| WDC                 | 5         | 5      | 13.89%  |
| Samsung Electronics | 4         | 5      | 11.11%  |
| Toshiba             | 3         | 3      | 8.33%   |
| Intel               | 3         | 4      | 8.33%   |
| Hitachi             | 3         | 3      | 8.33%   |
| HGST                | 3         | 3      | 8.33%   |
| SK hynix            | 1         | 1      | 2.78%   |
| RENICE              | 1         | 1      | 2.78%   |
| OCZ                 | 1         | 1      | 2.78%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| Kingston            | 1         | 1      | 2.78%   |
| Indilinx            | 1         | 1      | 2.78%   |
| Fujitsu             | 1         | 1      | 2.78%   |
| Crucial             | 1         | 6      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 10     | 30.43%  |
| WDC                 | 5         | 5      | 21.74%  |
| Hitachi             | 3         | 3      | 13.04%  |
| HGST                | 3         | 3      | 13.04%  |
| Toshiba             | 2         | 2      | 8.7%    |
| Samsung Electronics | 2         | 2      | 8.7%    |
| Fujitsu             | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 26     | 63.89%  |
| SSD  | 11        | 17     | 30.56%  |
| NVMe | 2         | 3      | 5.56%   |

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
| Works    | 181       | 269    | 73.88%  |
| Malfunc  | 36        | 46     | 14.69%  |
| Detected | 28        | 32     | 11.43%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 149       | 56.23%  |
| Samsung Electronics          | 25        | 9.43%   |
| AMD                          | 24        | 9.06%   |
| SK hynix                     | 15        | 5.66%   |
| SanDisk                      | 11        | 4.15%   |
| Kingston Technology Company  | 8         | 3.02%   |
| KIOXIA                       | 6         | 2.26%   |
| Phison Electronics           | 4         | 1.51%   |
| Nvidia                       | 4         | 1.51%   |
| Micron Technology            | 4         | 1.51%   |
| Silicon Motion               | 3         | 1.13%   |
| Micron/Crucial Technology    | 3         | 1.13%   |
| Toshiba America Info Systems | 2         | 0.75%   |
| Union Memory (Shenzhen)      | 1         | 0.38%   |
| Silicon Image                | 1         | 0.38%   |
| Shenzhen Longsys Electronics | 1         | 0.38%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.38%   |
| Marvell Technology Group     | 1         | 0.38%   |
| Lite-On Technology           | 1         | 0.38%   |
| ADATA Technology             | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 20        | 7.04%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 20        | 7.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 6.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 4.23%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 3.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 3.17%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 8         | 2.82%   |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 2.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 2.46%   |
| SK hynix BC511 NVMe SSD                                                        | 6         | 2.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 2.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 2.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 2.11%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1.76%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.41%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 1.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.41%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 1.41%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 1.06%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 1.06%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.06%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.06%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 3         | 1.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.06%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 1.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.06%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.7%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 0.7%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 0.7%    |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 0.7%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 0.7%    |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.7%    |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 2         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 156       | 57.35%  |
| NVMe | 84        | 30.88%  |
| IDE  | 17        | 6.25%   |
| RAID | 15        | 5.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 182       | 80.89%  |
| AMD    | 43        | 19.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 8         | 3.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 2.22%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 5         | 2.22%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 5         | 2.22%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 4         | 1.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 1.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 1.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 1.33%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 1.33%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 3         | 1.33%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 3         | 1.33%   |
| Intel 12th Gen Core i7-12700H           | 3         | 1.33%   |
| Intel 12th Gen Core i5-1235U            | 3         | 1.33%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 1.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 0.89%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 2         | 0.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 0.89%   |
| Intel Core i5-5350U CPU @ 1.80GHz       | 2         | 0.89%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 2         | 0.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.89%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.89%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 2         | 0.89%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 0.89%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 0.89%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 2         | 0.89%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 2         | 0.89%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 2         | 0.89%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 2         | 0.89%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 0.89%   |
| Intel Core 2 CPU T5500 @ 1.66GHz        | 2         | 0.89%   |
| Intel Celeron N4120 CPU @ 1.10GHz       | 2         | 0.89%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 2         | 0.89%   |
| Intel Celeron CPU N3450 @ 1.10GHz       | 2         | 0.89%   |
| Intel Celeron CPU 1007U @ 1.50GHz       | 2         | 0.89%   |
| Intel Atom CPU N570 @ 1.66GHz           | 2         | 0.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 0.89%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 2         | 0.89%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 2         | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 19.11%  |
| Intel Core i7           | 37        | 16.44%  |
| Other                   | 27        | 12%     |
| Intel Core i3           | 20        | 8.89%   |
| Intel Celeron           | 18        | 8%      |
| AMD Ryzen 5             | 13        | 5.78%   |
| AMD Ryzen 7             | 11        | 4.89%   |
| Intel Core 2 Duo        | 10        | 4.44%   |
| Intel Atom              | 10        | 4.44%   |
| Intel Pentium           | 4         | 1.78%   |
| AMD Ryzen 3             | 4         | 1.78%   |
| AMD Ryzen 9             | 3         | 1.33%   |
| Intel Pentium M         | 2         | 0.89%   |
| Intel Pentium Dual-Core | 2         | 0.89%   |
| Intel Genuine           | 2         | 0.89%   |
| Intel Core 2            | 2         | 0.89%   |
| AMD A6                  | 2         | 0.89%   |
| Intel Xeon              | 1         | 0.44%   |
| Intel Pentium Silver    | 1         | 0.44%   |
| Intel Pentium Gold      | 1         | 0.44%   |
| Intel Pentium Dual      | 1         | 0.44%   |
| Intel Celeron Dual-Core | 1         | 0.44%   |
| AMD Turion 64 X2 Mobile | 1         | 0.44%   |
| AMD Turion 64 Mobile    | 1         | 0.44%   |
| AMD Sempron             | 1         | 0.44%   |
| AMD Phenom II           | 1         | 0.44%   |
| AMD E2                  | 1         | 0.44%   |
| AMD E1                  | 1         | 0.44%   |
| AMD E                   | 1         | 0.44%   |
| AMD A8                  | 1         | 0.44%   |
| AMD A12                 | 1         | 0.44%   |
| AMD A10                 | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 112       | 49.78%  |
| 4      | 60        | 26.67%  |
| 6      | 18        | 8%      |
| 8      | 16        | 7.11%   |
| 1      | 9         | 4%      |
| 10     | 4         | 1.78%   |
| 14     | 3         | 1.33%   |
| 12     | 2         | 0.89%   |
| 5      | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 225       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 156       | 69.33%  |
| 1      | 69        | 30.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 221       | 98.22%  |
| 32-bit         | 4         | 1.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 9.57%   |
| 0x206a7    | 17        | 7.39%   |
| 0x306a9    | 13        | 5.65%   |
| 0x806c1    | 12        | 5.22%   |
| 0x406e3    | 12        | 5.22%   |
| 0x0a50000c | 11        | 4.78%   |
| 0x30678    | 8         | 3.48%   |
| 0x1067a    | 8         | 3.48%   |
| 0x506e3    | 7         | 3.04%   |
| 0x806e9    | 6         | 2.61%   |
| 0x306c3    | 6         | 2.61%   |
| 0x20655    | 6         | 2.61%   |
| 0x08608103 | 6         | 2.61%   |
| 0xa0652    | 5         | 2.17%   |
| 0x906ea    | 5         | 2.17%   |
| 0x906a3    | 5         | 2.17%   |
| 0x706a8    | 5         | 2.17%   |
| 0x306d4    | 5         | 2.17%   |
| 0x906a4    | 4         | 1.74%   |
| 0x806ea    | 4         | 1.74%   |
| 0x6fd      | 4         | 1.74%   |
| 0x406c4    | 4         | 1.74%   |
| 0x08108102 | 4         | 1.74%   |
| 0x906e9    | 3         | 1.3%    |
| 0x806ec    | 3         | 1.3%    |
| 0x40651    | 3         | 1.3%    |
| 0x806d1    | 2         | 0.87%   |
| 0x706a1    | 2         | 0.87%   |
| 0x106ca    | 2         | 0.87%   |
| 0x08600104 | 2         | 0.87%   |
| 0x07030106 | 2         | 0.87%   |
| 0x0600611a | 2         | 0.87%   |
| 0x06001119 | 2         | 0.87%   |
| 0xb06a3    | 1         | 0.43%   |
| 0xa0671    | 1         | 0.43%   |
| 0x906ed    | 1         | 0.43%   |
| 0x906c0    | 1         | 0.43%   |
| 0x806eb    | 1         | 0.43%   |
| 0x6fb      | 1         | 0.43%   |
| 0x6f6      | 1         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 24        | 10.67%  |
| Skylake          | 20        | 8.89%   |
| SandyBridge      | 18        | 8%      |
| IvyBridge        | 15        | 6.67%   |
| Unknown          | 15        | 6.67%   |
| TigerLake        | 14        | 6.22%   |
| Zen 3            | 13        | 5.78%   |
| Silvermont       | 12        | 5.33%   |
| Haswell          | 11        | 4.89%   |
| Penryn           | 10        | 4.44%   |
| Westmere         | 8         | 3.56%   |
| Core             | 8         | 3.56%   |
| Goldmont plus    | 7         | 3.11%   |
| Zen+             | 6         | 2.67%   |
| IceLake          | 5         | 2.22%   |
| CometLake        | 5         | 2.22%   |
| Broadwell        | 5         | 2.22%   |
| Alderlake Hybrid | 4         | 1.78%   |
| Zen 2            | 3         | 1.33%   |
| P6               | 3         | 1.33%   |
| Excavator        | 3         | 1.33%   |
| Bonnell          | 3         | 1.33%   |
| Puma             | 2         | 0.89%   |
| Piledriver       | 2         | 0.89%   |
| K8 Hammer        | 2         | 0.89%   |
| Goldmont         | 2         | 0.89%   |
| Tremont          | 1         | 0.44%   |
| Nehalem          | 1         | 0.44%   |
| K8 & K10 hybrid  | 1         | 0.44%   |
| K10              | 1         | 0.44%   |
| Bobcat           | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 169       | 61.45%  |
| Nvidia | 55        | 20%     |
| AMD    | 51        | 18.55%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 5.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 5.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 4.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 4.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 3.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 2.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 2.44%   |
| AMD Lucienne                                                                             | 7         | 2.44%   |
| Intel HD Graphics 530                                                                    | 6         | 2.09%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.09%   |
| Intel HD Graphics 620                                                                    | 5         | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.74%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.39%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.39%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.39%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.39%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 1.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.05%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 1.05%   |
| AMD Barcelo                                                                              | 3         | 1.05%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.7%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.7%    |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.7%    |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.7%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.7%    |
| Nvidia GF108M [GeForce GT 525M]                                                          | 2         | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 125       | 55.56%  |
| Intel + Nvidia | 35        | 15.56%  |
| 1 x AMD        | 33        | 14.67%  |
| 1 x Nvidia     | 13        | 5.78%   |
| Intel + AMD    | 8         | 3.56%   |
| AMD + Nvidia   | 6         | 2.67%   |
| 2 x AMD        | 4         | 1.78%   |
| 2 x Intel      | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 197       | 86.03%  |
| Proprietary | 20        | 8.73%   |
| Unknown     | 12        | 5.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 172       | 75.44%  |
| 0.01-0.5   | 30        | 13.16%  |
| 3.01-4.0   | 7         | 3.07%   |
| 1.01-2.0   | 7         | 3.07%   |
| 0.51-1.0   | 7         | 3.07%   |
| 7.01-8.0   | 3         | 1.32%   |
| 5.01-6.0   | 1         | 0.44%   |
| 2.01-3.0   | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 45        | 18.6%   |
| Chimei Innolux          | 42        | 17.36%  |
| BOE                     | 30        | 12.4%   |
| Samsung Electronics     | 22        | 9.09%   |
| LG Display              | 21        | 8.68%   |
| Apple                   | 10        | 4.13%   |
| PANDA                   | 9         | 3.72%   |
| Chi Mei Optoelectronics | 9         | 3.72%   |
| Hewlett-Packard         | 8         | 3.31%   |
| Lenovo                  | 6         | 2.48%   |
| Goldstar                | 5         | 2.07%   |
| Sharp                   | 4         | 1.65%   |
| Ancor Communications    | 4         | 1.65%   |
| Sony                    | 3         | 1.24%   |
| CPT                     | 3         | 1.24%   |
| InfoVision              | 2         | 0.83%   |
| HannStar                | 2         | 0.83%   |
| Dell                    | 2         | 0.83%   |
| TMX                     | 1         | 0.41%   |
| Sunplus                 | 1         | 0.41%   |
| STA                     | 1         | 0.41%   |
| Philips                 | 1         | 0.41%   |
| Panasonic               | 1         | 0.41%   |
| Packard Bell            | 1         | 0.41%   |
| ONN                     | 1         | 0.41%   |
| NEC Computers           | 1         | 0.41%   |
| LTM                     | 1         | 0.41%   |
| LG Philips              | 1         | 0.41%   |
| KDC                     | 1         | 0.41%   |
| HKC                     | 1         | 0.41%   |
| Eizo                    | 1         | 0.41%   |
| ASUSTek Computer        | 1         | 0.41%   |
| Acer                    | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 2.07%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 1.24%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 1.24%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.83%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 2         | 0.83%   |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch                 | 2         | 0.83%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.83%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.83%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.83%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.83%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.83%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                     | 2         | 0.83%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 2         | 0.83%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch                  | 1         | 0.41%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.41%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.41%   |
| Sony TV SNY3001 1920x1080                                                | 1         | 0.41%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.41%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.41%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.41%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.41%   |
| Sharp LCD Monitor SHP1445 3840x2160 346x194mm 15.6-inch                  | 1         | 0.41%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM0458 1360x768                          | 1         | 0.41%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 527x296mm 23.8-inch        | 1         | 0.41%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch        | 1         | 0.41%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 0.41%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch        | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 353x198mm 15.9-inch     | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 98        | 42.42%  |
| 1366x768 (WXGA)    | 66        | 28.57%  |
| 3840x2160 (4K)     | 12        | 5.19%   |
| 1280x800 (WXGA)    | 12        | 5.19%   |
| 1600x900 (HD+)     | 9         | 3.9%    |
| 1920x1200 (WUXGA)  | 4         | 1.73%   |
| 2880x1800          | 3         | 1.3%    |
| 2560x1600          | 3         | 1.3%    |
| 1440x900 (WXGA+)   | 3         | 1.3%    |
| 2560x1440 (QHD)    | 2         | 0.87%   |
| 2560x1080          | 2         | 0.87%   |
| 2256x1504          | 2         | 0.87%   |
| 2160x1440          | 2         | 0.87%   |
| 1680x1050 (WSXGA+) | 2         | 0.87%   |
| 1280x1024 (SXGA)   | 2         | 0.87%   |
| 1024x768 (XGA)     | 2         | 0.87%   |
| 1024x600           | 2         | 0.87%   |
| 3840x2400          | 1         | 0.43%   |
| 3200x2000          | 1         | 0.43%   |
| 3200x1800 (QHD+)   | 1         | 0.43%   |
| 1400x1050          | 1         | 0.43%   |
| 1360x768           | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 104       | 42.98%  |
| 13      | 29        | 11.98%  |
| 14      | 22        | 9.09%   |
| 17      | 19        | 7.85%   |
| 11      | 12        | 4.96%   |
| 24      | 11        | 4.55%   |
| 23      | 8         | 3.31%   |
| 16      | 5         | 2.07%   |
| 12      | 5         | 2.07%   |
| 21      | 4         | 1.65%   |
| 10      | 4         | 1.65%   |
| 19      | 3         | 1.24%   |
| Unknown | 3         | 1.24%   |
| 40      | 2         | 0.83%   |
| 34      | 2         | 0.83%   |
| 27      | 2         | 0.83%   |
| 84      | 1         | 0.41%   |
| 46      | 1         | 0.41%   |
| 43      | 1         | 0.41%   |
| 36      | 1         | 0.41%   |
| 32      | 1         | 0.41%   |
| 26      | 1         | 0.41%   |
| 25      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 142       | 58.92%  |
| 201-300     | 34        | 14.11%  |
| 351-400     | 26        | 10.79%  |
| 501-600     | 22        | 9.13%   |
| 401-500     | 5         | 2.07%   |
| 701-800     | 4         | 1.66%   |
| Unknown     | 3         | 1.24%   |
| 801-900     | 2         | 0.83%   |
| 1501-2000   | 1         | 0.41%   |
| 1001-1500   | 1         | 0.41%   |
| 901-1000    | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 179       | 81%     |
| 16/10   | 30        | 13.57%  |
| 3/2     | 4         | 1.81%   |
| 4/3     | 3         | 1.36%   |
| 5/4     | 2         | 0.9%    |
| 21/9    | 2         | 0.9%    |
| Unknown | 1         | 0.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 104       | 42.98%  |
| 81-90          | 43        | 17.77%  |
| 121-130        | 20        | 8.26%   |
| 201-250        | 19        | 7.85%   |
| 51-60          | 12        | 4.96%   |
| 71-80          | 7         | 2.89%   |
| 61-70          | 5         | 2.07%   |
| 501-1000       | 5         | 2.07%   |
| 41-50          | 4         | 1.65%   |
| 251-300        | 4         | 1.65%   |
| 151-200        | 4         | 1.65%   |
| 351-500        | 3         | 1.24%   |
| 301-350        | 3         | 1.24%   |
| 111-120        | 3         | 1.24%   |
| Unknown        | 3         | 1.24%   |
| 91-100         | 2         | 0.83%   |
| More than 1000 | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 105       | 44.3%   |
| 101-120       | 57        | 24.05%  |
| 51-100        | 46        | 19.41%  |
| 161-240       | 16        | 6.75%   |
| More than 240 | 8         | 3.38%   |
| Unknown       | 3         | 1.27%   |
| 1-50          | 2         | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 186       | 80.87%  |
| 2     | 29        | 12.61%  |
| 0     | 12        | 5.22%   |
| 3     | 3         | 1.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 115       | 31.34%  |
| Intel                             | 115       | 31.34%  |
| Qualcomm Atheros                  | 47        | 12.81%  |
| Broadcom                          | 23        | 6.27%   |
| MediaTek                          | 9         | 2.45%   |
| Broadcom Limited                  | 9         | 2.45%   |
| TP-Link                           | 6         | 1.63%   |
| Marvell Technology Group          | 6         | 1.63%   |
| Samsung Electronics               | 4         | 1.09%   |
| Motorola PCS                      | 4         | 1.09%   |
| ASIX Electronics                  | 4         | 1.09%   |
| Ralink                            | 3         | 0.82%   |
| OPPO Electronics                  | 3         | 0.82%   |
| Sierra Wireless                   | 2         | 0.54%   |
| Qualcomm Atheros Communications   | 2         | 0.54%   |
| Nvidia                            | 2         | 0.54%   |
| Sweex                             | 1         | 0.27%   |
| Ralink Technology                 | 1         | 0.27%   |
| Qualcomm Technologies             | 1         | 0.27%   |
| NetGear                           | 1         | 0.27%   |
| Lenovo                            | 1         | 0.27%   |
| Foxconn / Hon Hai                 | 1         | 0.27%   |
| Fibocom                           | 1         | 0.27%   |
| Ericsson Business Mobile Networks | 1         | 0.27%   |
| Dell                              | 1         | 0.27%   |
| D-Link                            | 1         | 0.27%   |
| Attansic Technology               | 1         | 0.27%   |
| ASUSTek Computer                  | 1         | 0.27%   |
| AMD                               | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 71        | 16.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 14        | 3.23%   |
| Intel Wireless 8260                                                     | 12        | 2.76%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 2.76%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 2.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 1.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 1.38%   |
| Intel Wireless 8265 / 8275                                              | 6         | 1.38%   |
| Intel Wireless 7265                                                     | 6         | 1.38%   |
| Intel Wireless 3165                                                     | 6         | 1.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.15%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 1.15%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.92%   |
| Intel Wireless 7260                                                     | 4         | 0.92%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 0.92%   |
| Intel 82567LM Gigabit Network Connection                                | 4         | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                           | 4         | 0.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.69%   |
| OPPO SM8350-IDP _SN:361A1B3C                                            | 3         | 0.69%   |
| Motorola PCS moto g52                                                   | 3         | 0.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.69%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 112       | 47.46%  |
| Realtek Semiconductor           | 37        | 15.68%  |
| Qualcomm Atheros                | 36        | 15.25%  |
| Broadcom                        | 15        | 6.36%   |
| MediaTek                        | 9         | 3.81%   |
| Broadcom Limited                | 8         | 3.39%   |
| TP-Link                         | 5         | 2.12%   |
| Ralink                          | 3         | 1.27%   |
| Sierra Wireless                 | 2         | 0.85%   |
| Qualcomm Atheros Communications | 2         | 0.85%   |
| Sweex                           | 1         | 0.42%   |
| Ralink Technology               | 1         | 0.42%   |
| Qualcomm Technologies           | 1         | 0.42%   |
| NetGear                         | 1         | 0.42%   |
| Fibocom                         | 1         | 0.42%   |
| D-Link                          | 1         | 0.42%   |
| ASUSTek Computer                | 1         | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 12        | 5.08%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 5.08%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 4.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 3.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 2.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.54%   |
| Intel Wireless 8265 / 8275                                              | 6         | 2.54%   |
| Intel Wireless 7265                                                     | 6         | 2.54%   |
| Intel Wireless 3165                                                     | 6         | 2.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 2.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.69%   |
| Intel Wireless 7260                                                     | 4         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 1.27%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.27%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.27%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.27%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 3         | 1.27%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.27%   |
| TP-Link 802.11ac NIC                                                    | 2         | 0.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.85%   |
| Intel Wireless 3160                                                     | 2         | 0.85%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 100       | 52.36%  |
| Intel                    | 37        | 19.37%  |
| Qualcomm Atheros         | 16        | 8.38%   |
| Broadcom                 | 11        | 5.76%   |
| Marvell Technology Group | 6         | 3.14%   |
| Samsung Electronics      | 4         | 2.09%   |
| ASIX Electronics         | 4         | 2.09%   |
| OPPO Electronics         | 3         | 1.57%   |
| Motorola PCS             | 3         | 1.57%   |
| Nvidia                   | 2         | 1.05%   |
| TP-Link                  | 1         | 0.52%   |
| Lenovo                   | 1         | 0.52%   |
| Foxconn / Hon Hai        | 1         | 0.52%   |
| Broadcom Limited         | 1         | 0.52%   |
| Attansic Technology      | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 71        | 36.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 14        | 7.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 4.15%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 2.59%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 2.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 2.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 2.07%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 2.07%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 2.07%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 1.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 1.55%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 3         | 1.55%   |
| Motorola PCS moto g52                                                  | 3         | 1.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 1.04%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 1.04%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 1.04%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 1.04%   |
| Intel Ethernet Connection I219-V                                       | 2         | 1.04%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 1.04%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 1.04%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.04%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 1.04%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.04%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.52%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.52%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.52%   |
| Nvidia MCP77 Ethernet                                                  | 1         | 0.52%   |
| Nvidia MCP67 Ethernet                                                  | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 217       | 54.11%  |
| Ethernet | 179       | 44.64%  |
| Modem    | 4         | 1%      |
| Unknown  | 1         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 173       | 76.55%  |
| Ethernet | 53        | 23.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 161       | 70.93%  |
| 1     | 57        | 25.11%  |
| 0     | 7         | 3.08%   |
| 3     | 2         | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 169       | 74.12%  |
| Yes  | 59        | 25.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 82        | 44.32%  |
| Realtek Semiconductor           | 19        | 10.27%  |
| Qualcomm Atheros Communications | 16        | 8.65%   |
| Lite-On Technology              | 10        | 5.41%   |
| Foxconn / Hon Hai               | 10        | 5.41%   |
| Apple                           | 10        | 5.41%   |
| Broadcom                        | 9         | 4.86%   |
| IMC Networks                    | 8         | 4.32%   |
| Cambridge Silicon Radio         | 7         | 3.78%   |
| Hewlett-Packard                 | 5         | 2.7%    |
| Ralink                          | 2         | 1.08%   |
| Dell                            | 2         | 1.08%   |
| Realtek                         | 1         | 0.54%   |
| Ralink Technology               | 1         | 0.54%   |
| MediaTek                        | 1         | 0.54%   |
| ASUSTek Computer                | 1         | 0.54%   |
| Alps Electric                   | 1         | 0.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 33        | 17.84%  |
| Realtek Bluetooth Radio                                                             | 17        | 9.19%   |
| Intel AX201 Bluetooth                                                               | 14        | 7.57%   |
| Intel AX200 Bluetooth                                                               | 12        | 6.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 5.95%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 4.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 3.78%   |
| Intel Bluetooth Device                                                              | 5         | 2.7%    |
| Apple Bluetooth Host Controller                                                     | 5         | 2.7%    |
| IMC Networks Wireless_Device                                                        | 4         | 2.16%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 2.16%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.62%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.62%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.62%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.62%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 1.62%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.62%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.08%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.08%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.08%   |
| Lite-On Wireless_Device                                                             | 2         | 1.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.08%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.08%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.08%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.08%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 1.08%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.08%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.54%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.54%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.54%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.54%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.54%   |
| MediaTek Wireless_Device                                                            | 1         | 0.54%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.54%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.54%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.54%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 171       | 62.64%  |
| AMD                     | 43        | 15.75%  |
| Nvidia                  | 42        | 15.38%  |
| Realtek Semiconductor   | 2         | 0.73%   |
| JMTek                   | 2         | 0.73%   |
| VIA Technologies        | 1         | 0.37%   |
| Texas Instruments       | 1         | 0.37%   |
| Plantronics             | 1         | 0.37%   |
| Logitech                | 1         | 0.37%   |
| Lenovo                  | 1         | 0.37%   |
| Guillemot               | 1         | 0.37%   |
| Generalplus Technology  | 1         | 0.37%   |
| Focusrite-Novation      | 1         | 0.37%   |
| FIFINE 683 Microphone   | 1         | 0.37%   |
| Conexant Systems        | 1         | 0.37%   |
| CMX Systems             | 1         | 0.37%   |
| C-Media Electronics     | 1         | 0.37%   |
| BEHRINGER International | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 31        | 9.54%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 7.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 20        | 6.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 5.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 4%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 2.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.46%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.15%   |
| Nvidia Audio device                                                                               | 6         | 1.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 1.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.54%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.54%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.54%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 1.23%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.23%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.92%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 0.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.92%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 0.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.92%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.62%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.62%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.62%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.62%   |
| JMTek USB PnP Audio Device                                                                        | 2         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Samsung Electronics            | 67        | 25%     |
| SK hynix                       | 56        | 20.9%   |
| Unknown                        | 31        | 11.57%  |
| Micron Technology              | 27        | 10.07%  |
| Kingston                       | 22        | 8.21%   |
| Crucial                        | 16        | 5.97%   |
| Elpida                         | 7         | 2.61%   |
| Unknown (ABCD)                 | 5         | 1.87%   |
| Corsair                        | 5         | 1.87%   |
| A-DATA Technology              | 5         | 1.87%   |
| Transcend                      | 3         | 1.12%   |
| Ramaxel Technology             | 3         | 1.12%   |
| Unknown                        | 3         | 1.12%   |
| Smart                          | 2         | 0.75%   |
| G.Skill                        | 2         | 0.75%   |
| Wilk                           | 1         | 0.37%   |
| Team                           | 1         | 0.37%   |
| PNY                            | 1         | 0.37%   |
| Patriot                        | 1         | 0.37%   |
| Nanya Technology               | 1         | 0.37%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.37%   |
| Lexar Co Limited               | 1         | 0.37%   |
| Innodisk                       | 1         | 0.37%   |
| Hewlett-Packard                | 1         | 0.37%   |
| Essencore                      | 1         | 0.37%   |
| CSX                            | 1         | 0.37%   |
| Avant                          | 1         | 0.37%   |
| ASint Technology               | 1         | 0.37%   |
| 48spaces                       | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 6         | 2.1%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 2.1%    |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 5         | 1.75%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 5         | 1.75%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 1.75%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 4         | 1.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 1.4%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 1.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.05%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 1.05%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s               | 3         | 1.05%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 3         | 1.05%   |
| Unknown                                                             | 3         | 1.05%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 2         | 0.7%    |
| Unknown RAM Module 8GB SODIMM DDR3                                  | 2         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 2         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 2         | 0.7%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 2         | 0.7%    |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 2         | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 2         | 0.7%    |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 2         | 0.7%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 0.7%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 2         | 0.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.7%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 2         | 0.7%    |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 2         | 0.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 0.7%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 2         | 0.7%    |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                          | 2         | 0.7%    |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.7%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 2         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 2         | 0.7%    |
| Crucial RAM CT16G4SFRA32A.C16FR 16GB SODIMM DDR4 3200MT/s           | 2         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 101       | 43.91%  |
| DDR3    | 89        | 38.7%   |
| DDR2    | 11        | 4.78%   |
| LPDDR4  | 9         | 3.91%   |
| SDRAM   | 5         | 2.17%   |
| DDR     | 5         | 2.17%   |
| LPDDR3  | 4         | 1.74%   |
| DRAM    | 2         | 0.87%   |
| DDR5    | 2         | 0.87%   |
| LPDDR5  | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 213       | 92.21%  |
| Row Of Chips | 13        | 5.63%   |
| DIMM         | 2         | 0.87%   |
| Unknown      | 2         | 0.87%   |
| Chip         | 1         | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 93        | 36.9%   |
| 4096  | 76        | 30.16%  |
| 2048  | 37        | 14.68%  |
| 16384 | 30        | 11.9%   |
| 1024  | 11        | 4.37%   |
| 32768 | 4         | 1.59%   |
| 512   | 1         | 0.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 53        | 21.63%  |
| 3200    | 52        | 21.22%  |
| 2667    | 32        | 13.06%  |
| 2400    | 17        | 6.94%   |
| 1333    | 16        | 6.53%   |
| 1334    | 15        | 6.12%   |
| Unknown | 12        | 4.9%    |
| 2133    | 10        | 4.08%   |
| 667     | 9         | 3.67%   |
| 1067    | 7         | 2.86%   |
| 4199    | 3         | 1.22%   |
| 4800    | 2         | 0.82%   |
| 4267    | 2         | 0.82%   |
| 3266    | 2         | 0.82%   |
| 1867    | 2         | 0.82%   |
| 975     | 2         | 0.82%   |
| 533     | 2         | 0.82%   |
| 8400    | 1         | 0.41%   |
| 5500    | 1         | 0.41%   |
| 4266    | 1         | 0.41%   |
| 2933    | 1         | 0.41%   |
| 2048    | 1         | 0.41%   |
| 800     | 1         | 0.41%   |
| 166     | 1         | 0.41%   |

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
| Chicony Electronics                    | 43        | 22.51%  |
| IMC Networks                           | 20        | 10.47%  |
| Realtek Semiconductor                  | 15        | 7.85%   |
| Microdia                               | 15        | 7.85%   |
| Bison Electronics                      | 15        | 7.85%   |
| Quanta                                 | 14        | 7.33%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 5.76%   |
| Luxvisions Innotech Limited            | 7         | 3.66%   |
| Apple                                  | 7         | 3.66%   |
| Suyin                                  | 6         | 3.14%   |
| Sunplus Innovation Technology          | 6         | 3.14%   |
| Lite-On Technology                     | 5         | 2.62%   |
| Ricoh                                  | 4         | 2.09%   |
| Alcor Micro                            | 4         | 2.09%   |
| Silicon Motion                         | 3         | 1.57%   |
| Logitech                               | 3         | 1.57%   |
| Lenovo                                 | 3         | 1.57%   |
| Acer                                   | 3         | 1.57%   |
| Z-Star Microelectronics                | 1         | 0.52%   |
| Y Media                                | 1         | 0.52%   |
| Primax Electronics                     | 1         | 0.52%   |
| Novatek Microelectronics               | 1         | 0.52%   |
| Hewlett-Packard                        | 1         | 0.52%   |
| Goodong Industry                       | 1         | 0.52%   |
| 8SSC20F27114V1SR0BK1X4S                | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 12        | 6.28%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 6         | 3.14%   |
| Quanta HD User Facing                                | 5         | 2.62%   |
| Microdia Integrated_Webcam_HD                        | 5         | 2.62%   |
| Realtek Integrated_Webcam_HD                         | 4         | 2.09%   |
| IMC Networks Integrated Camera                       | 4         | 2.09%   |
| Bison BisonCam,NB Pro                                | 4         | 2.09%   |
| Quanta HP TrueVision HD Camera                       | 3         | 1.57%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 1.57%   |
| Chicony HD User Facing                               | 3         | 1.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 3         | 1.57%   |
| Bison Integrated Camera                              | 3         | 1.57%   |
| Alcor Micro USB 2.0 Camera                           | 3         | 1.57%   |
| Suyin Acer CrystalEye Webcam                         | 2         | 1.05%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 1.05%   |
| Sunplus HD WebCam                                    | 2         | 1.05%   |
| Ricoh USB2.0 Camera                                  | 2         | 1.05%   |
| Realtek USB2.0 HD UVC WebCam                         | 2         | 1.05%   |
| Realtek USB Camera                                   | 2         | 1.05%   |
| Microdia Webcam Vitade AF                            | 2         | 1.05%   |
| Microdia USB 2.0 Camera                              | 2         | 1.05%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 1.05%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 1.05%   |
| Lite-On HP HD Webcam                                 | 2         | 1.05%   |
| Lite-On HP HD Camera                                 | 2         | 1.05%   |
| Lenovo Integrated Webcam [R5U877]                    | 2         | 1.05%   |
| IMC Networks XHC Camera                              | 2         | 1.05%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 1.05%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 2         | 1.05%   |
| Chicony HD WebCam                                    | 2         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 2         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 2         | 1.05%   |
| Bison ThinkPad P50 Integrated Camera                 | 2         | 1.05%   |
| Bison BisonCam, NB Pro                               | 2         | 1.05%   |
| Apple FaceTime HD Camera (Built-in)                  | 2         | 1.05%   |
| Apple Built-in iSight                                | 2         | 1.05%   |
| Z-Star Venus USB2.0 Camera                           | 1         | 0.52%   |
| Y Media USB Camera                                   | 1         | 0.52%   |
| Suyin Sony Visual Communication Camera               | 1         | 0.52%   |
| Suyin Integrated_Webcam_HD                           | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 13        | 32.5%   |
| Synaptics                          | 7         | 17.5%   |
| Shenzhen Goodix Technology         | 6         | 15%     |
| AuthenTec                          | 5         | 12.5%   |
| Elan Microelectronics              | 4         | 10%     |
| Upek                               | 3         | 7.5%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.5%    |
| Focal-systems.Corp                 | 1         | 2.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device                             | 5         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 4         | 10%     |
| AuthenTec AES2810                                               | 3         | 7.5%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 2         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 5%      |
| Elan ELAN:Fingerprint                                           | 2         | 5%      |
| Elan ELAN:ARM-M4                                                | 2         | 5%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 2.5%    |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 2.5%    |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 2.5%    |
| Validity Sensors Synaptics WBDI                                 | 1         | 2.5%    |
| Upek TCS5B Fingerprint sensor                                   | 1         | 2.5%    |
| Synaptics UWP WBDI Device                                       | 1         | 2.5%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 2.5%    |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 2.5%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.5%    |
| Focal-systems.Corp FT9201Fingerprint.Ì                       | 1         | 2.5%    |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 2.5%    |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 2.5%    |
| Unknown                                                         | 1         | 2.5%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 42.86%  |
| Alcor Micro           | 6         | 42.86%  |
| Advanced Card Systems | 2         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 6         | 42.86%  |
| Broadcom 5880                                  | 4         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 7.14%   |
| Broadcom 58200                                 | 1         | 7.14%   |
| Advanced Card Systems ACR38 SmartCard Reader   | 1         | 7.14%   |
| Advanced Card Systems ACR122U                  | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 135       | 58.44%  |
| 1     | 71        | 30.74%  |
| 2     | 22        | 9.52%   |
| 3     | 3         | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 49        | 42.61%  |
| Fingerprint reader       | 40        | 34.78%  |
| Chipcard                 | 12        | 10.43%  |
| Net/wireless             | 4         | 3.48%   |
| Multimedia controller    | 3         | 2.61%   |
| Camera                   | 3         | 2.61%   |
| Net/ethernet             | 1         | 0.87%   |
| Flash memory             | 1         | 0.87%   |
| Communication controller | 1         | 0.87%   |
| Bluetooth                | 1         | 0.87%   |

