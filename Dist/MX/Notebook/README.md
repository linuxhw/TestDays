MX - Tested Hardware & Statistics (Notebooks)
---------------------------------------------

A project to collect tested hardware configurations for MX.

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

Total: 557

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3190               | [7be68f9c9a](https://linux-hardware.org/?probe=7be68f9c9a) | Sep 06, 2023 |
| Apple         | MacBookPro8,1               | [2e3c70287a](https://linux-hardware.org/?probe=2e3c70287a) | Aug 30, 2023 |
| Dell          | Latitude 3190               | [6e16da127a](https://linux-hardware.org/?probe=6e16da127a) | Aug 29, 2023 |
| Dell          | Latitude 3190               | [61ddf042df](https://linux-hardware.org/?probe=61ddf042df) | Aug 22, 2023 |
| HP            | EliteBook 840 G2            | [c8cc960675](https://linux-hardware.org/?probe=c8cc960675) | Aug 21, 2023 |
| Notebook      | NL5xNU                      | [768e7b97fc](https://linux-hardware.org/?probe=768e7b97fc) | Aug 19, 2023 |
| Dell          | Latitude E6430              | [27d598d911](https://linux-hardware.org/?probe=27d598d911) | Aug 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [b9134a5ee3](https://linux-hardware.org/?probe=b9134a5ee3) | Aug 16, 2023 |
| Beelink       | Gemini X                    | [d5c4e54794](https://linux-hardware.org/?probe=d5c4e54794) | Aug 14, 2023 |
| Dell          | Latitude E5410              | [4ae8d448a2](https://linux-hardware.org/?probe=4ae8d448a2) | Aug 14, 2023 |
| HP            | 250 G8 Notebook PC          | [64a738d034](https://linux-hardware.org/?probe=64a738d034) | Aug 13, 2023 |
| Dell          | Vostro 15-3568              | [b422d7c8cc](https://linux-hardware.org/?probe=b422d7c8cc) | Aug 12, 2023 |
| Toshiba       | Satellite T110              | [8180105119](https://linux-hardware.org/?probe=8180105119) | Aug 11, 2023 |
| Dell          | Inspiron 5415               | [69123aa283](https://linux-hardware.org/?probe=69123aa283) | Aug 10, 2023 |
| Dell          | Inspiron 5415               | [9c28979b9d](https://linux-hardware.org/?probe=9c28979b9d) | Aug 10, 2023 |
| Dell          | Latitude E6540              | [758d587fbb](https://linux-hardware.org/?probe=758d587fbb) | Aug 10, 2023 |
| ASUSTek       | UL30A                       | [11f3b9cfad](https://linux-hardware.org/?probe=11f3b9cfad) | Aug 08, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [f30c6c7bb5](https://linux-hardware.org/?probe=f30c6c7bb5) | Aug 08, 2023 |
| HP            | Laptop 15-dy2xxx            | [5777798e8f](https://linux-hardware.org/?probe=5777798e8f) | Aug 07, 2023 |
| ASUSTek       | ProArt StudioBook W5600Q... | [96211a5c87](https://linux-hardware.org/?probe=96211a5c87) | Aug 05, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [482b97d3de](https://linux-hardware.org/?probe=482b97d3de) | Aug 02, 2023 |
| Dell          | Latitude E6320              | [9b42be4945](https://linux-hardware.org/?probe=9b42be4945) | Aug 02, 2023 |
| HP            | 620                         | [4c04d9d11e](https://linux-hardware.org/?probe=4c04d9d11e) | Aug 01, 2023 |
| HP            | 620                         | [eafc7ac5c3](https://linux-hardware.org/?probe=eafc7ac5c3) | Aug 01, 2023 |
| Acer          | Aspire E1-532               | [9042ebc249](https://linux-hardware.org/?probe=9042ebc249) | Aug 01, 2023 |
| Dell          | Latitude 3190               | [c88a2ad597](https://linux-hardware.org/?probe=c88a2ad597) | Aug 01, 2023 |
| Lenovo        | 3000 C100 07612GU           | [3941ecc4f2](https://linux-hardware.org/?probe=3941ecc4f2) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | [f84a39b436](https://linux-hardware.org/?probe=f84a39b436) | Jul 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [095890a440](https://linux-hardware.org/?probe=095890a440) | Jul 31, 2023 |
| Dell          | Latitude 5340               | [5ab5c25167](https://linux-hardware.org/?probe=5ab5c25167) | Jul 28, 2023 |
| Acer          | Aspire V3-571G              | [88f60930be](https://linux-hardware.org/?probe=88f60930be) | Jul 26, 2023 |
| Dell          | Inspiron 3583               | [e235fb3a23](https://linux-hardware.org/?probe=e235fb3a23) | Jul 26, 2023 |
| Dell          | Inspiron 13-5378            | [fd43074149](https://linux-hardware.org/?probe=fd43074149) | Jul 26, 2023 |
| Dell          | Latitude 3190               | [b1730d834d](https://linux-hardware.org/?probe=b1730d834d) | Jul 25, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d10701a88b](https://linux-hardware.org/?probe=d10701a88b) | Jul 22, 2023 |
| Dell          | Latitude 3510               | [e1eb8b885c](https://linux-hardware.org/?probe=e1eb8b885c) | Jul 21, 2023 |
| Dell          | Latitude 5530               | [235731a6f1](https://linux-hardware.org/?probe=235731a6f1) | Jul 20, 2023 |
| Dell          | Latitude 5310               | [5b81040709](https://linux-hardware.org/?probe=5b81040709) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [31c0d94d23](https://linux-hardware.org/?probe=31c0d94d23) | Jul 18, 2023 |
| CONNEX        | L1415-BAY                   | [8f5663e9c8](https://linux-hardware.org/?probe=8f5663e9c8) | Jul 18, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [18f41b2be6](https://linux-hardware.org/?probe=18f41b2be6) | Jul 17, 2023 |
| Dell          | Precision 5510              | [ff4ea6ba94](https://linux-hardware.org/?probe=ff4ea6ba94) | Jul 17, 2023 |
| Sony          | VGN-S3HP                    | [6e2c92c447](https://linux-hardware.org/?probe=6e2c92c447) | Jul 17, 2023 |
| Dell          | Latitude 5530               | [37681b3327](https://linux-hardware.org/?probe=37681b3327) | Jul 17, 2023 |
| HP            | Laptop 15-fc0xxx            | [782127b6f6](https://linux-hardware.org/?probe=782127b6f6) | Jul 17, 2023 |
| Acer          | Aspire 4750                 | [d1ef43e488](https://linux-hardware.org/?probe=d1ef43e488) | Jul 16, 2023 |
| Dell          | Precision 3571              | [2123567cb0](https://linux-hardware.org/?probe=2123567cb0) | Jul 16, 2023 |
| Dell          | System XPS L502X            | [e6b4c3cf4e](https://linux-hardware.org/?probe=e6b4c3cf4e) | Jul 12, 2023 |
| Dell          | Latitude 3190               | [f067ca0dbf](https://linux-hardware.org/?probe=f067ca0dbf) | Jul 11, 2023 |
| Acer          | Aspire ES1-511              | [1e7434d3b0](https://linux-hardware.org/?probe=1e7434d3b0) | Jul 10, 2023 |
| HP            | 620                         | [5f88c564fd](https://linux-hardware.org/?probe=5f88c564fd) | Jul 08, 2023 |
| Acer          | Aspire A515-47              | [ab21b766b6](https://linux-hardware.org/?probe=ab21b766b6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | [5bba6eb442](https://linux-hardware.org/?probe=5bba6eb442) | Jul 07, 2023 |
| ASUSTek       | GL703VD                     | [68235880f7](https://linux-hardware.org/?probe=68235880f7) | Jul 06, 2023 |
| Dell          | Latitude 3190               | [b895b6dced](https://linux-hardware.org/?probe=b895b6dced) | Jul 04, 2023 |
| Alienware     | m16 R1 AMD                  | [291c477bd0](https://linux-hardware.org/?probe=291c477bd0) | Jul 01, 2023 |
| ASUSTek       | X201EV                      | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| Acer          | Aspire E5-573               | [cd65c92d12](https://linux-hardware.org/?probe=cd65c92d12) | Jun 27, 2023 |
| Acer          | Aspire E5-573               | [e3b1cdc71c](https://linux-hardware.org/?probe=e3b1cdc71c) | Jun 27, 2023 |
| Dell          | Latitude 3190               | [5f68b5235f](https://linux-hardware.org/?probe=5f68b5235f) | Jun 27, 2023 |
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
| ASUSTek       | N56VB                       | [f47c68a2a7](https://linux-hardware.org/?probe=f47c68a2a7) | Jun 04, 2023 |
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
| Dell          | Latitude 7480               | [2e485b361c](https://linux-hardware.org/?probe=2e485b361c) | Nov 14, 2022 |
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
| Lenovo        | ThinkPad T420 4236TL7       | [8a639f4457](https://linux-hardware.org/?probe=8a639f4457) | Oct 10, 2022 |
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
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | [f8f2a6263a](https://linux-hardware.org/?probe=f8f2a6263a) | Sep 04, 2022 |
| Dell          | Latitude 3190               | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| win elemen... | MoreFine S500+              | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| win elemen... | MoreFine S500+              | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Acer          | Extensa 5630                | [9ea053d8e8](https://linux-hardware.org/?probe=9ea053d8e8) | Aug 12, 2022 |
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
| UMAX          | VisionBook-N12R             | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
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
| Acer          | Extensa 5630                | [32cab1f9fc](https://linux-hardware.org/?probe=32cab1f9fc) | Mar 14, 2022 |
| Dell          | Latitude 3190               | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Sony          | SVE1513Q1ESI                | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| HP            | ProBook 6460b               | [5f936a65be](https://linux-hardware.org/?probe=5f936a65be) | Feb 02, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | 2000                        | [5d64fe5b92](https://linux-hardware.org/?probe=5d64fe5b92) | Jan 01, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | X550CC                      | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | [63d7055c5e](https://linux-hardware.org/?probe=63d7055c5e) | Dec 18, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Toshiba       | Satellite L850-CJK          | [0dc076ad15](https://linux-hardware.org/?probe=0dc076ad15) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| Lenovo        | B590 20208                  | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | Unknown                     | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Unknown       | Unknown                     | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| Dell          | Inspiron 3576               | [ad9fb758a6](https://linux-hardware.org/?probe=ad9fb758a6) | Nov 09, 2021 |
| Apple         | MacBook3,1                  | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| Google        | Akemi                       | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| HP            | EliteBook 850 G3            | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| ASUSTek       | E402MA                      | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Dell          | Latitude E7450              | [91837758ac](https://linux-hardware.org/?probe=91837758ac) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Dell          | Latitude 3190               | [d08efa2ef3](https://linux-hardware.org/?probe=d08efa2ef3) | Oct 25, 2021 |
| Lenovo        | ThinkPad L520 78595VG       | [4aff5a6a0c](https://linux-hardware.org/?probe=4aff5a6a0c) | Oct 24, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| Sony          | SVT13115FBS                 | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| Lenovo        | ThinkPad T530 2394CJ9       | [b36a94241d](https://linux-hardware.org/?probe=b36a94241d) | Oct 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Lenovo        | ThinkPad L490 20Q5S0PR00    | [bbf6b89f02](https://linux-hardware.org/?probe=bbf6b89f02) | Oct 01, 2021 |
| Acer          | Aspire 4820T                | [a91911ca90](https://linux-hardware.org/?probe=a91911ca90) | Oct 01, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [8c1a085f29](https://linux-hardware.org/?probe=8c1a085f29) | Sep 20, 2021 |
| Lenovo        | ThinkPad P51 20HJS0TP00     | [2774c819ea](https://linux-hardware.org/?probe=2774c819ea) | Sep 18, 2021 |
| Lenovo        | B40-45 20394                | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [e76ffa7805](https://linux-hardware.org/?probe=e76ffa7805) | Sep 06, 2021 |
| GTZS          | Unknown                     | [3df799f341](https://linux-hardware.org/?probe=3df799f341) | Sep 05, 2021 |
| Acer          | Aspire V3-371               | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Pixus         | Rise                        | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| Lenovo        | ThinkPad T420 4236MBU       | [7e0b868c64](https://linux-hardware.org/?probe=7e0b868c64) | Jul 29, 2021 |
| Acer          | Aspire E5-574G              | [b09280946d](https://linux-hardware.org/?probe=b09280946d) | Jul 21, 2021 |
| Dell          | Vostro 5515                 | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Dell          | Latitude 3340               | [c47b83476b](https://linux-hardware.org/?probe=c47b83476b) | Jul 12, 2021 |
| Acer          | Aspire one                  | [2c266e91ae](https://linux-hardware.org/?probe=2c266e91ae) | Jul 09, 2021 |
| Medion        | P6669 MD60147               | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |
| Dell          | Vostro 3460                 | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Medion        | E6234                       | [313ec752ab](https://linux-hardware.org/?probe=313ec752ab) | May 24, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [4ed89e1092](https://linux-hardware.org/?probe=4ed89e1092) | May 22, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [57a69c7c0d](https://linux-hardware.org/?probe=57a69c7c0d) | May 20, 2021 |
| HP            | Mini 110-3500               | [f94c828225](https://linux-hardware.org/?probe=f94c828225) | May 19, 2021 |
| ASUSTek       | N56VZ                       | [c69cd5aceb](https://linux-hardware.org/?probe=c69cd5aceb) | May 18, 2021 |
| Irbis         | TW94                        | [dc56e23810](https://linux-hardware.org/?probe=dc56e23810) | May 15, 2021 |
| Dell          | Latitude E6320              | [fa8bcef5a9](https://linux-hardware.org/?probe=fa8bcef5a9) | May 09, 2021 |
| Acer          | Extensa 5620                | [a06636ba79](https://linux-hardware.org/?probe=a06636ba79) | Apr 24, 2021 |
| Dell          | 0UW744??????                | [32c3521a2e](https://linux-hardware.org/?probe=32c3521a2e) | Apr 22, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | [73f2bd0075](https://linux-hardware.org/?probe=73f2bd0075) | Apr 16, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | [75e60ebdf4](https://linux-hardware.org/?probe=75e60ebdf4) | Apr 16, 2021 |
| Intel         | ChiefRiver                  | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| eMachines     | E727                        | [048da4f23b](https://linux-hardware.org/?probe=048da4f23b) | Apr 12, 2021 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [7159579bb8](https://linux-hardware.org/?probe=7159579bb8) | Apr 12, 2021 |
| ASUSTek       | G751JT                      | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| HP            | Falco                       | [9bb0bf9ac8](https://linux-hardware.org/?probe=9bb0bf9ac8) | Apr 07, 2021 |
| ASUSTek       | 1025C                       | [33d6531353](https://linux-hardware.org/?probe=33d6531353) | Apr 06, 2021 |
| HP            | ZBook 17 G6                 | [046176e590](https://linux-hardware.org/?probe=046176e590) | Mar 16, 2021 |
| Dell          | Latitude E5470              | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| HP            | Notebook                    | [113644885d](https://linux-hardware.org/?probe=113644885d) | Mar 04, 2021 |
| Acer          | AOD255                      | [f8501e519f](https://linux-hardware.org/?probe=f8501e519f) | Mar 03, 2021 |
| Google        | Gnawty                      | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Latitude D430               | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| HP            | Pavilion g6                 | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Lenovo        | ThinkPad E425 1198CTO       | [67304f1ffa](https://linux-hardware.org/?probe=67304f1ffa) | Feb 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [6f34bc4f67](https://linux-hardware.org/?probe=6f34bc4f67) | Feb 19, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [7552dacfb9](https://linux-hardware.org/?probe=7552dacfb9) | Feb 17, 2021 |
| HP            | Mini 110-3500               | [bb5cf4031b](https://linux-hardware.org/?probe=bb5cf4031b) | Feb 13, 2021 |
| HP            | Notebook                    | [69f70d7a09](https://linux-hardware.org/?probe=69f70d7a09) | Feb 10, 2021 |
| HP            | 15                          | [437cb08f68](https://linux-hardware.org/?probe=437cb08f68) | Feb 08, 2021 |
| Apple         | MacBook7,1                  | [a6324a9e06](https://linux-hardware.org/?probe=a6324a9e06) | Feb 05, 2021 |
| Clevo         | P170EM                      | [eff7a04dad](https://linux-hardware.org/?probe=eff7a04dad) | Feb 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [b6ebe98655](https://linux-hardware.org/?probe=b6ebe98655) | Feb 01, 2021 |
| HP            | ProBook 650 G1              | [9021b90504](https://linux-hardware.org/?probe=9021b90504) | Jan 22, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a147ddbe9d](https://linux-hardware.org/?probe=a147ddbe9d) | Jan 20, 2021 |
| HP            | Mini 110-3500               | [3c2a01636e](https://linux-hardware.org/?probe=3c2a01636e) | Jan 19, 2021 |
| HP            | Pavilion g6                 | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASUSTek       | X101CH                      | [3dfb714393](https://linux-hardware.org/?probe=3dfb714393) | Jan 15, 2021 |
| Dell          | Latitude D430               | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| Dell          | Latitude E5520              | [1d46b26326](https://linux-hardware.org/?probe=1d46b26326) | Jan 03, 2021 |
| HP            | Presario CQ57               | [351ae067b6](https://linux-hardware.org/?probe=351ae067b6) | Dec 31, 2020 |
| HP            | Presario CQ57               | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | Aspire ES1-511              | [7f351d7c49](https://linux-hardware.org/?probe=7f351d7c49) | Dec 30, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5de3914984](https://linux-hardware.org/?probe=5de3914984) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | [ebb2dc7bff](https://linux-hardware.org/?probe=ebb2dc7bff) | Dec 15, 2020 |
| Lenovo        | ThinkPad X220 4291WMQ       | [165b895e27](https://linux-hardware.org/?probe=165b895e27) | Dec 01, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| Acer          | Aspire E5-571G              | [7f5f7e9fff](https://linux-hardware.org/?probe=7f5f7e9fff) | Nov 17, 2020 |
| Toshiba       | Satellite A300              | [309a3f69e8](https://linux-hardware.org/?probe=309a3f69e8) | Nov 16, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | [554dfc3cfe](https://linux-hardware.org/?probe=554dfc3cfe) | Nov 12, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | [2dc30b7928](https://linux-hardware.org/?probe=2dc30b7928) | Nov 12, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [fe6cbf555a](https://linux-hardware.org/?probe=fe6cbf555a) | Nov 08, 2020 |
| Dell          | Inspiron 14-3452            | [96e87a665b](https://linux-hardware.org/?probe=96e87a665b) | Nov 01, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [470c0ca72b](https://linux-hardware.org/?probe=470c0ca72b) | Oct 23, 2020 |
| HP            | Compaq 8510p (KM229AV)      | [30634ffde6](https://linux-hardware.org/?probe=30634ffde6) | Oct 12, 2020 |
| Acer          | Aspire SW5-015              | [b125bdb89e](https://linux-hardware.org/?probe=b125bdb89e) | Oct 07, 2020 |
| HP            | Pavilion 15                 | [8e6632f1a3](https://linux-hardware.org/?probe=8e6632f1a3) | Oct 06, 2020 |
| Lenovo        | V145-15AST 81MT             | [7155397289](https://linux-hardware.org/?probe=7155397289) | Oct 03, 2020 |
| Lenovo        | ThinkPad T400 2768WGB       | [995b1a3a3d](https://linux-hardware.org/?probe=995b1a3a3d) | Sep 29, 2020 |
| Toshiba       | Satellite C660              | [a5f308c899](https://linux-hardware.org/?probe=a5f308c899) | Sep 21, 2020 |
| Lenovo        | ThinkPad T60 20085TG        | [31cd0f06c2](https://linux-hardware.org/?probe=31cd0f06c2) | Sep 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [356bacc97a](https://linux-hardware.org/?probe=356bacc97a) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Acer          | Aspire A114-32              | [7f178a7089](https://linux-hardware.org/?probe=7f178a7089) | Aug 20, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [9b4d2c057e](https://linux-hardware.org/?probe=9b4d2c057e) | Aug 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [57e274292b](https://linux-hardware.org/?probe=57e274292b) | Aug 16, 2020 |
| Acer          | Aspire 7520                 | [d878dbb71e](https://linux-hardware.org/?probe=d878dbb71e) | Aug 13, 2020 |
| HP            | Pavilion dv7                | [3494105666](https://linux-hardware.org/?probe=3494105666) | Jul 28, 2020 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | [c0d166e020](https://linux-hardware.org/?probe=c0d166e020) | Jul 27, 2020 |
| HP            | ProBook 650 G1              | [9a488079c3](https://linux-hardware.org/?probe=9a488079c3) | Jul 23, 2020 |
| Sony          | VPCF23P1E                   | [2e0915f8a9](https://linux-hardware.org/?probe=2e0915f8a9) | Jun 18, 2020 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [54a69351ae](https://linux-hardware.org/?probe=54a69351ae) | Jun 17, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [b93dafce99](https://linux-hardware.org/?probe=b93dafce99) | Jun 09, 2020 |
| Lenovo        | ThinkPad X250 20CLS4YA00    | [72150af905](https://linux-hardware.org/?probe=72150af905) | Jun 06, 2020 |
| ASUSTek       | X540UP                      | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Sony          | VGN-NR310FH                 | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| Acer          | Aspire A315-41              | [665b2837c7](https://linux-hardware.org/?probe=665b2837c7) | May 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c85746245d](https://linux-hardware.org/?probe=c85746245d) | May 26, 2020 |
| Lenovo        | B590 20206                  | [8f4a7e2b6e](https://linux-hardware.org/?probe=8f4a7e2b6e) | May 26, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| Samsung       | R780/R778                   | [eb0bb63c6d](https://linux-hardware.org/?probe=eb0bb63c6d) | Apr 09, 2020 |
| Clevo         | P150HMx                     | [196b689717](https://linux-hardware.org/?probe=196b689717) | Mar 27, 2020 |
| Dell          | Latitude E7440              | [c6fe81343e](https://linux-hardware.org/?probe=c6fe81343e) | Mar 26, 2020 |
| ASUSTek       | X455LAB                     | [4a5174a726](https://linux-hardware.org/?probe=4a5174a726) | Mar 24, 2020 |
| Notebook      | W65_W67RZ1                  | [aaffd10ebf](https://linux-hardware.org/?probe=aaffd10ebf) | Mar 24, 2020 |
| Dell          | Inspiron 13-5378            | [242a7e4fdc](https://linux-hardware.org/?probe=242a7e4fdc) | Mar 24, 2020 |
| Clevo         | P150HMx                     | [8f9823569b](https://linux-hardware.org/?probe=8f9823569b) | Mar 24, 2020 |
| Dell          | Inspiron N5010              | [8654fde26b](https://linux-hardware.org/?probe=8654fde26b) | Mar 24, 2020 |
| Medion        | Akoya E1318T                | [d6be35c8af](https://linux-hardware.org/?probe=d6be35c8af) | Mar 20, 2020 |
| Dell          | Latitude 3190               | [1bab98d664](https://linux-hardware.org/?probe=1bab98d664) | Mar 20, 2020 |
| HP            | EliteBook 8560p             | [e5925f1349](https://linux-hardware.org/?probe=e5925f1349) | Mar 07, 2020 |
| Acer          | Aspire 8943G                | [f8e194e907](https://linux-hardware.org/?probe=f8e194e907) | Mar 01, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [370f5d5063](https://linux-hardware.org/?probe=370f5d5063) | Feb 26, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T11... | [9c888bfdde](https://linux-hardware.org/?probe=9c888bfdde) | Feb 11, 2020 |
| Lenovo        | ThinkPad X201 3680MY9       | [26a7c0e493](https://linux-hardware.org/?probe=26a7c0e493) | Feb 09, 2020 |
| Google        | Gnawty                      | [4a2e211ce1](https://linux-hardware.org/?probe=4a2e211ce1) | Feb 08, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | [8865e9546b](https://linux-hardware.org/?probe=8865e9546b) | Feb 03, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | [f4779c95ce](https://linux-hardware.org/?probe=f4779c95ce) | Feb 03, 2020 |
| Acer          | Swift SF314-54G             | [48912b8dc6](https://linux-hardware.org/?probe=48912b8dc6) | Jan 19, 2020 |
| ASUSTek       | TUF Gaming FX505GT_TUF50... | [0abd5b1d73](https://linux-hardware.org/?probe=0abd5b1d73) | Jan 18, 2020 |
| Toshiba       | Satellite P875              | [b267e93d40](https://linux-hardware.org/?probe=b267e93d40) | Jan 15, 2020 |
| Toshiba       | Satellite P875              | [7e579fcba2](https://linux-hardware.org/?probe=7e579fcba2) | Jan 15, 2020 |
| MSI           | GP63 Leopard 8RD            | [0a8865c437](https://linux-hardware.org/?probe=0a8865c437) | Jan 13, 2020 |
| Packard Be... | EasyNote TE11HC             | [aa52528043](https://linux-hardware.org/?probe=aa52528043) | Jan 13, 2020 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [ba3b839fa4](https://linux-hardware.org/?probe=ba3b839fa4) | Jan 12, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [7f8e86e96b](https://linux-hardware.org/?probe=7f8e86e96b) | Jan 12, 2020 |
| HP            | Pavilion g6                 | [9c722b6763](https://linux-hardware.org/?probe=9c722b6763) | Dec 21, 2019 |
| Toshiba       | Satellite C50-A-12K         | [a413f419ef](https://linux-hardware.org/?probe=a413f419ef) | Dec 17, 2019 |
| Dell          | G3 3579                     | [c4fe97cca2](https://linux-hardware.org/?probe=c4fe97cca2) | Dec 04, 2019 |
| Dell          | G3 3579                     | [ada421696a](https://linux-hardware.org/?probe=ada421696a) | Dec 04, 2019 |
| HP            | Laptop 14-ck0xxx            | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| MSI           | MS-N033                     | [a5ee4c1dc1](https://linux-hardware.org/?probe=a5ee4c1dc1) | Nov 17, 2019 |
| ASUSTek       | 1005HA                      | [bd953e0701](https://linux-hardware.org/?probe=bd953e0701) | Nov 17, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Lenovo        | ThinkPad X301 2776LBU       | [993b5f104a](https://linux-hardware.org/?probe=993b5f104a) | Nov 17, 2019 |
| ASUSTek       | X101CH                      | [b17de4dbad](https://linux-hardware.org/?probe=b17de4dbad) | Nov 04, 2019 |
| HP            | Pavilion g6                 | [2cb09606ed](https://linux-hardware.org/?probe=2cb09606ed) | Nov 01, 2019 |
| HP            | ProBook 4440s               | [fc67acaa63](https://linux-hardware.org/?probe=fc67acaa63) | Oct 29, 2019 |
| HP            | Laptop 14-cm0xxx            | [6a706da421](https://linux-hardware.org/?probe=6a706da421) | Oct 23, 2019 |
| MSI           | GP63 Leopard 8RD            | [df3af7b333](https://linux-hardware.org/?probe=df3af7b333) | Oct 23, 2019 |
| HP            | EliteBook 8540w             | [ea8ef5afc7](https://linux-hardware.org/?probe=ea8ef5afc7) | Oct 23, 2019 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [cb80682975](https://linux-hardware.org/?probe=cb80682975) | Oct 20, 2019 |
| HP            | Pavilion g6                 | [6bde777445](https://linux-hardware.org/?probe=6bde777445) | Oct 20, 2019 |
| Lenovo        | ThinkPad X220 4291F52       | [e024139431](https://linux-hardware.org/?probe=e024139431) | Aug 29, 2019 |
| Lenovo        | ThinkPad X201s 5413A19      | [673c3629dc](https://linux-hardware.org/?probe=673c3629dc) | Aug 22, 2019 |
| Panasonic     | CF-C1BT02EGE                | [acbec08287](https://linux-hardware.org/?probe=acbec08287) | Aug 15, 2019 |
| MSI           | GP63 Leopard 8RD            | [bf82fba8fd](https://linux-hardware.org/?probe=bf82fba8fd) | Apr 29, 2019 |
| ASUSTek       | K55VM                       | [e967dd6404](https://linux-hardware.org/?probe=e967dd6404) | Mar 27, 2019 |
| MSI           | GP63 Leopard 8RD            | [67b484c4a0](https://linux-hardware.org/?probe=67b484c4a0) | Jan 19, 2019 |
| Toshiba       | Satellite C70-B             | [9b54677f2e](https://linux-hardware.org/?probe=9b54677f2e) | Oct 27, 2018 |
| MSI           | GP63 Leopard 8RD            | [ec89febb0c](https://linux-hardware.org/?probe=ec89febb0c) | Oct 27, 2018 |
| Dell          | Inspiron ME051              | [f789720dc4](https://linux-hardware.org/?probe=f789720dc4) | Nov 26, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/MX/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| MX 21 | 214       | 55.58%  |
| MX 19 | 87        | 22.6%   |
| MX 20 | 43        | 11.17%  |
| MX 23 | 25        | 6.49%   |
| MX 18 | 13        | 3.38%   |
| MX 17 | 2         | 0.52%   |
| MX 16 | 1         | 0.26%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MX   | 374       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 4.19.0-6-amd64      | 34        | 8.15%   |
| 5.10.0-21-amd64     | 25        | 6%      |
| 6.0.0-6mx-amd64     | 22        | 5.28%   |
| 5.10.0-23-amd64     | 16        | 3.84%   |
| 5.10.0-13-amd64     | 15        | 3.6%    |
| 5.10.0-9-amd64      | 14        | 3.36%   |
| 5.10.0-5mx-amd64    | 13        | 3.12%   |
| 5.10.0-18-amd64     | 13        | 3.12%   |
| 5.8.0-3-amd64       | 9         | 2.16%   |
| 5.10.0-16-amd64     | 9         | 2.16%   |
| 6.1.0-9-amd64       | 8         | 1.92%   |
| 6.1.0-10-amd64      | 8         | 1.92%   |
| 5.16.0-5mx-amd64    | 8         | 1.92%   |
| 5.14.0-4mx-amd64    | 8         | 1.92%   |
| 5.10.0-20-amd64     | 8         | 1.92%   |
| 5.10.0-19-amd64     | 8         | 1.92%   |
| 4.19.0-13-amd64     | 7         | 1.68%   |
| 5.10.0-14-amd64     | 6         | 1.44%   |
| 5.10.0-11-amd64     | 6         | 1.44%   |
| 4.19.0-16-amd64     | 6         | 1.44%   |
| 4.19.0-14-amd64     | 6         | 1.44%   |
| 6.0.0-4mx-amd64     | 5         | 1.2%    |
| 5.6.0-2-amd64       | 5         | 1.2%    |
| 5.18.0-4mx-amd64    | 5         | 1.2%    |
| 5.10.0-22-amd64     | 5         | 1.2%    |
| 4.19.0-5-amd64      | 4         | 0.96%   |
| 4.19.0-17-amd64     | 4         | 0.96%   |
| 4.19.0-11-amd64     | 4         | 0.96%   |
| 6.4.0-1mx-ahs-amd64 | 3         | 0.72%   |
| 6.1.0-9mx-ahs-amd64 | 3         | 0.72%   |
| 6.1.0-11-amd64      | 3         | 0.72%   |
| 5.10.0-8mx-amd64    | 3         | 0.72%   |
| 5.10.0-17-amd64     | 3         | 0.72%   |
| 4.19.0-9-amd64      | 3         | 0.72%   |
| 4.19.0-12-amd64     | 3         | 0.72%   |
| 4.19.0-1-amd64      | 3         | 0.72%   |
| 6.3.0-2mx-ahs-amd64 | 2         | 0.48%   |
| 6.1.0-8mx-ahs-amd64 | 2         | 0.48%   |
| 6.1.0-4mx-amd64     | 2         | 0.48%   |
| 6.1.0-10-686-pae    | 2         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 153       | 38.54%  |
| 4.19.0   | 83        | 20.91%  |
| 6.0.0    | 32        | 8.06%   |
| 6.1.0    | 27        | 6.8%    |
| 5.16.0   | 13        | 3.27%   |
| 5.8.0    | 9         | 2.27%   |
| 5.14.0   | 8         | 2.02%   |
| 5.6.0    | 7         | 1.76%   |
| 5.18.0   | 7         | 1.76%   |
| 5.4.0    | 6         | 1.51%   |
| 5.19.0   | 5         | 1.26%   |
| 6.4.0    | 4         | 1.01%   |
| 5.17.0   | 4         | 1.01%   |
| 6.3.0    | 2         | 0.5%    |
| 5.8.16   | 2         | 0.5%    |
| 5.6.10   | 2         | 0.5%    |
| 5.3.0    | 2         | 0.5%    |
| 5.2.21   | 2         | 0.5%    |
| 5.15.0   | 2         | 0.5%    |
| 4.9.193  | 2         | 0.5%    |
| 4.15.0   | 2         | 0.5%    |
| 6.4.3    | 1         | 0.25%   |
| 6.2.7    | 1         | 0.25%   |
| 6.2.14   | 1         | 0.25%   |
| 6.1.15   | 1         | 0.25%   |
| 6.1.12   | 1         | 0.25%   |
| 5.9.1    | 1         | 0.25%   |
| 5.7.0    | 1         | 0.25%   |
| 5.5.0    | 1         | 0.25%   |
| 5.3.10   | 1         | 0.25%   |
| 5.2.8    | 1         | 0.25%   |
| 5.2.0    | 1         | 0.25%   |
| 5.13.0   | 1         | 0.25%   |
| 5.11.0   | 1         | 0.25%   |
| 5.10.82  | 1         | 0.25%   |
| 5.10.142 | 1         | 0.25%   |
| 5.10.1   | 1         | 0.25%   |
| 5.1.2    | 1         | 0.25%   |
| 5.0.0    | 1         | 0.25%   |
| 4.9.246  | 1         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 156       | 39.29%  |
| 4.19    | 84        | 21.16%  |
| 6.0     | 32        | 8.06%   |
| 6.1     | 29        | 7.3%    |
| 5.16    | 13        | 3.27%   |
| 5.8     | 11        | 2.77%   |
| 5.6     | 9         | 2.27%   |
| 5.14    | 8         | 2.02%   |
| 5.18    | 7         | 1.76%   |
| 5.4     | 6         | 1.51%   |
| 6.4     | 5         | 1.26%   |
| 5.19    | 5         | 1.26%   |
| 5.2     | 4         | 1.01%   |
| 5.17    | 4         | 1.01%   |
| 5.3     | 3         | 0.76%   |
| 4.9     | 3         | 0.76%   |
| 6.3     | 2         | 0.5%    |
| 6.2     | 2         | 0.5%    |
| 5.15    | 2         | 0.5%    |
| 4.15    | 2         | 0.5%    |
| 5.9     | 1         | 0.25%   |
| 5.7     | 1         | 0.25%   |
| 5.5     | 1         | 0.25%   |
| 5.13    | 1         | 0.25%   |
| 5.11    | 1         | 0.25%   |
| 5.1     | 1         | 0.25%   |
| 5.0     | 1         | 0.25%   |
| 4.18    | 1         | 0.25%   |
| 3.16    | 1         | 0.25%   |
| Unknown | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 352       | 93.87%  |
| i686   | 23        | 6.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| XFCE             | 274       | 71.92%  |
| KDE5             | 64        | 16.8%   |
| Unknown          | 8         | 2.1%    |
| Budgie           | 7         | 1.84%   |
| i3               | 5         | 1.31%   |
| GNOME            | 4         | 1.05%   |
| fluxbox          | 3         | 0.79%   |
| X-Cinnamon       | 2         | 0.52%   |
| MATE             | 2         | 0.52%   |
| LXQt             | 2         | 0.52%   |
| lightdm-xsession | 2         | 0.52%   |
| GNOME Flashback  | 2         | 0.52%   |
| Cinnamon         | 2         | 0.52%   |
| Trinity          | 1         | 0.26%   |
| spectrwm         | 1         | 0.26%   |
| LXDE             | 1         | 0.26%   |
| GNOME Classic    | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 370       | 98.93%  |
| Tty     | 3         | 0.8%    |
| Wayland | 1         | 0.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 302       | 79.89%  |
| SDDM    | 58        | 15.34%  |
| TDM     | 9         | 2.38%   |
| SLiM    | 8         | 2.12%   |
| Unknown | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 158       | 41.36%  |
| Unknown | 57        | 14.92%  |
| de_DE   | 38        | 9.95%   |
| en_GB   | 23        | 6.02%   |
| it_IT   | 13        | 3.4%    |
| ru_RU   | 12        | 3.14%   |
| fr_FR   | 9         | 2.36%   |
| pl_PL   | 8         | 2.09%   |
| sk_SK   | 6         | 1.57%   |
| pt_BR   | 5         | 1.31%   |
| es_ES   | 5         | 1.31%   |
| es_MX   | 4         | 1.05%   |
| en_AU   | 4         | 1.05%   |
| tr_TR   | 3         | 0.79%   |
| nl_NL   | 3         | 0.79%   |
| en_NZ   | 3         | 0.79%   |
| de_CH   | 3         | 0.79%   |
| fr_BE   | 2         | 0.52%   |
| fi_FI   | 2         | 0.52%   |
| es_VE   | 2         | 0.52%   |
| es_CO   | 2         | 0.52%   |
| es_AR   | 2         | 0.52%   |
| en_IE   | 2         | 0.52%   |
| en_CA   | 2         | 0.52%   |
| bg_BG   | 2         | 0.52%   |
| zh_CN   | 1         | 0.26%   |
| uk_UA   | 1         | 0.26%   |
| ro_RO   | 1         | 0.26%   |
| nl_BE   | 1         | 0.26%   |
| nb_NO   | 1         | 0.26%   |
| id_ID   | 1         | 0.26%   |
| hu_HU   | 1         | 0.26%   |
| fr_CA   | 1         | 0.26%   |
| es_UY   | 1         | 0.26%   |
| es_PE   | 1         | 0.26%   |
| en_IL   | 1         | 0.26%   |
| cs_CZ   | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 231       | 61.76%  |
| BIOS | 143       | 38.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 315       | 83.33%  |
| Overlay | 47        | 12.43%  |
| Btrfs   | 12        | 3.17%   |
| Xfs     | 2         | 0.53%   |
| F2fs    | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 248       | 66.13%  |
| MBR     | 123       | 32.8%   |
| Unknown | 4         | 1.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 308       | 81.27%  |
| Yes       | 71        | 18.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 229       | 61.07%  |
| Yes       | 146       | 38.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo                    | 77        | 20.59%  |
| Hewlett-Packard           | 66        | 17.65%  |
| Dell                      | 50        | 13.37%  |
| ASUSTek Computer          | 43        | 11.5%   |
| Acer                      | 36        | 9.63%   |
| Sony                      | 12        | 3.21%   |
| Apple                     | 12        | 3.21%   |
| Toshiba                   | 11        | 2.94%   |
| Samsung Electronics       | 7         | 1.87%   |
| MSI                       | 7         | 1.87%   |
| Medion                    | 7         | 1.87%   |
| Fujitsu Siemens           | 4         | 1.07%   |
| Alienware                 | 4         | 1.07%   |
| Notebook                  | 3         | 0.8%    |
| Google                    | 3         | 0.8%    |
| Unknown                   | 3         | 0.8%    |
| TUXEDO                    | 2         | 0.53%   |
| Gigabyte Technology       | 2         | 0.53%   |
| Clevo                     | 2         | 0.53%   |
| Chuwi                     | 2         | 0.53%   |
| win element               | 1         | 0.27%   |
| Vulcan Electronics        | 1         | 0.27%   |
| UMAX                      | 1         | 0.27%   |
| SANTECH                   | 1         | 0.27%   |
| RTD Embedded Technologies | 1         | 0.27%   |
| Pixus                     | 1         | 0.27%   |
| Panasonic                 | 1         | 0.27%   |
| Packard Bell              | 1         | 0.27%   |
| Linx                      | 1         | 0.27%   |
| Irbis                     | 1         | 0.27%   |
| Intel                     | 1         | 0.27%   |
| HUAWEI                    | 1         | 0.27%   |
| Framework                 | 1         | 0.27%   |
| F-Plus Mobile             | 1         | 0.27%   |
| eMachines                 | 1         | 0.27%   |
| efirstview                | 1         | 0.27%   |
| CONNEX                    | 1         | 0.27%   |
| Compal                    | 1         | 0.27%   |
| Casper                    | 1         | 0.27%   |
| Beelink                   | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 5         | 1.34%   |
| HP Pavilion Laptop 15-eh1xxx       | 3         | 0.8%    |
| Samsung 305E4A/305E5A/305E7A       | 2         | 0.53%   |
| Lenovo ThinkBook 15 G3 ACL 21A4    | 2         | 0.53%   |
| HP Stream Laptop 14-cb0XX          | 2         | 0.53%   |
| HP ProBook 650 G1                  | 2         | 0.53%   |
| HP ProBook 450 G1                  | 2         | 0.53%   |
| HP Laptop 17-ak0xx                 | 2         | 0.53%   |
| Dell Latitude E6540                | 2         | 0.53%   |
| Dell Latitude E6320                | 2         | 0.53%   |
| Dell Latitude 5530                 | 2         | 0.53%   |
| Dell Inspiron 13-5378              | 2         | 0.53%   |
| Chuwi GemiBook Pro                 | 2         | 0.53%   |
| ASUS X200CA                        | 2         | 0.53%   |
| Apple MacBookAir7,2                | 2         | 0.53%   |
| Acer Nitro AN515-55                | 2         | 0.53%   |
| Acer Aspire ES1-511                | 2         | 0.53%   |
| win element MoreFine S500+         | 1         | 0.27%   |
| Vulcan Excursion XB                | 1         | 0.27%   |
| UMAX VisionBook-N12R               | 1         | 0.27%   |
| TUXEDO N7x0WU                      | 1         | 0.27%   |
| TUXEDO InfinityBook Pro Gen7 (MK1) | 1         | 0.27%   |
| Toshiba Satellite P875             | 1         | 0.27%   |
| Toshiba Satellite M70              | 1         | 0.27%   |
| Toshiba Satellite L850-CJK         | 1         | 0.27%   |
| Toshiba Satellite L650             | 1         | 0.27%   |
| Toshiba Satellite C845             | 1         | 0.27%   |
| Toshiba Satellite C70-B            | 1         | 0.27%   |
| Toshiba Satellite C660             | 1         | 0.27%   |
| Toshiba Satellite C50-A-12K        | 1         | 0.27%   |
| Toshiba Satellite A300             | 1         | 0.27%   |
| Toshiba PORTEGE Z30-C              | 1         | 0.27%   |
| Toshiba PORTEGE R705               | 1         | 0.27%   |
| Sony VPCYB3V1E                     | 1         | 0.27%   |
| Sony VPCSB1V9R                     | 1         | 0.27%   |
| Sony VPCF23P1E                     | 1         | 0.27%   |
| Sony VPCF119FX                     | 1         | 0.27%   |
| Sony VPCEH2N1E                     | 1         | 0.27%   |
| Sony VPCEC3S1E                     | 1         | 0.27%   |
| Sony VPCCB32FD                     | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 50        | 13.37%  |
| Dell Latitude         | 24        | 6.42%   |
| Acer Aspire           | 24        | 6.42%   |
| Dell Inspiron         | 12        | 3.21%   |
| HP Pavilion           | 11        | 2.94%   |
| Lenovo IdeaPad        | 10        | 2.67%   |
| HP ProBook            | 10        | 2.67%   |
| HP EliteBook          | 10        | 2.67%   |
| Toshiba Satellite     | 9         | 2.41%   |
| HP Laptop             | 9         | 2.41%   |
| ASUS VivoBook         | 7         | 1.87%   |
| Dell Vostro           | 5         | 1.34%   |
| Unknown               | 5         | 1.34%   |
| HP ZBook              | 4         | 1.07%   |
| Dell Precision        | 4         | 1.07%   |
| ASUS TUF              | 4         | 1.07%   |
| Lenovo ThinkBook      | 3         | 0.8%    |
| HP Compaq             | 3         | 0.8%    |
| HP 250                | 3         | 0.8%    |
| Acer Swift            | 3         | 0.8%    |
| Acer Nitro            | 3         | 0.8%    |
| Acer Extensa          | 3         | 0.8%    |
| Toshiba PORTEGE       | 2         | 0.53%   |
| Samsung 305E4A        | 2         | 0.53%   |
| Lenovo Legion         | 2         | 0.53%   |
| Lenovo B590           | 2         | 0.53%   |
| HP Stream             | 2         | 0.53%   |
| HP 15                 | 2         | 0.53%   |
| Fujitsu Siemens AMILO | 2         | 0.53%   |
| Dell System           | 2         | 0.53%   |
| Chuwi GemiBook        | 2         | 0.53%   |
| ASUS X200CA           | 2         | 0.53%   |
| ASUS ROG              | 2         | 0.53%   |
| ASUS ASUS             | 2         | 0.53%   |
| Apple MacBookPro11    | 2         | 0.53%   |
| Apple MacBookAir7     | 2         | 0.53%   |
| Alienware m15         | 2         | 0.53%   |
| win element MoreFine  | 1         | 0.27%   |
| Vulcan Excursion      | 1         | 0.27%   |
| UMAX VisionBook-N12R  | 1         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 39        | 10.43%  |
| 2011    | 38        | 10.16%  |
| 2010    | 29        | 7.75%   |
| 2013    | 28        | 7.49%   |
| 2012    | 27        | 7.22%   |
| 2018    | 26        | 6.95%   |
| 2020    | 25        | 6.68%   |
| 2016    | 25        | 6.68%   |
| 2019    | 22        | 5.88%   |
| 2015    | 22        | 5.88%   |
| 2022    | 17        | 4.55%   |
| 2014    | 17        | 4.55%   |
| 2017    | 15        | 4.01%   |
| 2008    | 12        | 3.21%   |
| 2009    | 10        | 2.67%   |
| 2007    | 8         | 2.14%   |
| 2006    | 6         | 1.6%    |
| 2005    | 4         | 1.07%   |
| 2023    | 3         | 0.8%    |
| Unknown | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 374       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 366       | 97.86%  |
| Enabled  | 8         | 2.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 369       | 98.66%  |
| Yes  | 5         | 1.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 109       | 29.07%  |
| 8.01-16.0   | 68        | 18.13%  |
| 3.01-4.0    | 67        | 17.87%  |
| 16.01-24.0  | 53        | 14.13%  |
| 1.01-2.0    | 32        | 8.53%   |
| 32.01-64.0  | 23        | 6.13%   |
| 2.01-3.0    | 11        | 2.93%   |
| 0.51-1.0    | 5         | 1.33%   |
| 64.01-256.0 | 4         | 1.07%   |
| 24.01-32.0  | 3         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 151       | 37.94%  |
| 2.01-3.0   | 99        | 24.87%  |
| 3.01-4.0   | 60        | 15.08%  |
| 0.51-1.0   | 40        | 10.05%  |
| 4.01-8.0   | 35        | 8.79%   |
| 8.01-16.0  | 8         | 2.01%   |
| 0.01-0.5   | 4         | 1.01%   |
| 16.01-24.0 | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 277       | 73.09%  |
| 2      | 78        | 20.58%  |
| 3      | 18        | 4.75%   |
| 0      | 4         | 1.06%   |
| 4      | 2         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 248       | 66.13%  |
| Yes       | 127       | 33.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 313       | 83.69%  |
| No        | 61        | 16.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 363       | 96.8%   |
| No        | 12        | 3.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 288       | 76.6%   |
| No        | 88        | 23.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 72        | 19.05%  |
| Germany      | 43        | 11.38%  |
| Italy        | 22        | 5.82%   |
| Canada       | 19        | 5.03%   |
| UK           | 18        | 4.76%   |
| Russia       | 13        | 3.44%   |
| Poland       | 11        | 2.91%   |
| India        | 11        | 2.91%   |
| France       | 11        | 2.91%   |
| Netherlands  | 9         | 2.38%   |
| Greece       | 9         | 2.38%   |
| Spain        | 8         | 2.12%   |
| Brazil       | 8         | 2.12%   |
| Slovakia     | 7         | 1.85%   |
| Australia    | 7         | 1.85%   |
| Mexico       | 6         | 1.59%   |
| Austria      | 6         | 1.59%   |
| Romania      | 5         | 1.32%   |
| Belgium      | 5         | 1.32%   |
| Ukraine      | 4         | 1.06%   |
| Turkey       | 4         | 1.06%   |
| Serbia       | 4         | 1.06%   |
| New Zealand  | 4         | 1.06%   |
| Indonesia    | 4         | 1.06%   |
| Finland      | 4         | 1.06%   |
| Czechia      | 4         | 1.06%   |
| Thailand     | 3         | 0.79%   |
| Switzerland  | 3         | 0.79%   |
| Sweden       | 3         | 0.79%   |
| Portugal     | 3         | 0.79%   |
| Colombia     | 3         | 0.79%   |
| Belarus      | 3         | 0.79%   |
| Vietnam      | 2         | 0.53%   |
| Venezuela    | 2         | 0.53%   |
| South Africa | 2         | 0.53%   |
| Norway       | 2         | 0.53%   |
| Hungary      | 2         | 0.53%   |
| Egypt        | 2         | 0.53%   |
| China        | 2         | 0.53%   |
| Chile        | 2         | 0.53%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vienna           | 6         | 1.52%   |
| Bratislava       | 6         | 1.52%   |
| Berlin           | 6         | 1.52%   |
| Athens           | 5         | 1.26%   |
| Warsaw           | 4         | 1.01%   |
| Rome             | 4         | 1.01%   |
| Moscow           | 4         | 1.01%   |
| Milan            | 4         | 1.01%   |
| St Petersburg    | 3         | 0.76%   |
| Munich           | 3         | 0.76%   |
| Montreal         | 3         | 0.76%   |
| Los Angeles      | 3         | 0.76%   |
| Belgrade         | 3         | 0.76%   |
| Amsterdam        | 3         | 0.76%   |
| Walled Lake      | 2         | 0.51%   |
| Salamina         | 2         | 0.51%   |
| Prague           | 2         | 0.51%   |
| Porto            | 2         | 0.51%   |
| Perth            | 2         | 0.51%   |
| Patna            | 2         | 0.51%   |
| Oxford           | 2         | 0.51%   |
| Otwock           | 2         | 0.51%   |
| Orange           | 2         | 0.51%   |
| Oakland          | 2         | 0.51%   |
| New York         | 2         | 0.51%   |
| Minsk            | 2         | 0.51%   |
| Melbourne        | 2         | 0.51%   |
| Madrid           | 2         | 0.51%   |
| Istanbul         | 2         | 0.51%   |
| Hyderabad        | 2         | 0.51%   |
| Ho Chi Minh City | 2         | 0.51%   |
| Hamburg          | 2         | 0.51%   |
| Florence         | 2         | 0.51%   |
| Doesburg         | 2         | 0.51%   |
| Dnipro           | 2         | 0.51%   |
| Dhaka            | 2         | 0.51%   |
| Catania          | 2         | 0.51%   |
| Casale Litta     | 2         | 0.51%   |
| Canberra         | 2         | 0.51%   |
| Cambridge        | 2         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 63        | 81     | 13.21%  |
| WDC                 | 58        | 60     | 12.16%  |
| Seagate             | 39        | 44     | 8.18%   |
| Toshiba             | 31        | 33     | 6.5%    |
| Unknown             | 30        | 36     | 6.29%   |
| Kingston            | 30        | 32     | 6.29%   |
| SK hynix            | 24        | 25     | 5.03%   |
| Crucial             | 24        | 47     | 5.03%   |
| SanDisk             | 20        | 22     | 4.19%   |
| Intel               | 15        | 20     | 3.14%   |
| Hitachi             | 14        | 15     | 2.94%   |
| HGST                | 14        | 19     | 2.94%   |
| Micron Technology   | 9         | 13     | 1.89%   |
| Apple               | 7         | 10     | 1.47%   |
| LITEON              | 6         | 6      | 1.26%   |
| KIOXIA              | 6         | 8      | 1.26%   |
| SPCC                | 5         | 5      | 1.05%   |
| PNY                 | 5         | 5      | 1.05%   |
| A-DATA Technology   | 5         | 7      | 1.05%   |
| Transcend           | 4         | 4      | 0.84%   |
| Unknown             | 4         | 4      | 0.84%   |
| Team                | 3         | 3      | 0.63%   |
| Phison              | 3         | 4      | 0.63%   |
| Patriot             | 3         | 3      | 0.63%   |
| Netac               | 3         | 3      | 0.63%   |
| Fujitsu             | 3         | 3      | 0.63%   |
| Dogfish             | 3         | 3      | 0.63%   |
| Corsair             | 3         | 3      | 0.63%   |
| China               | 3         | 3      | 0.63%   |
| OCZ                 | 2         | 2      | 0.42%   |
| KingSpec            | 2         | 2      | 0.42%   |
| KingDian            | 2         | 2      | 0.42%   |
| Indilinx            | 2         | 4      | 0.42%   |
| FORESEE             | 2         | 2      | 0.42%   |
| EYOTA               | 2         | 2      | 0.42%   |
| ZTC                 | 1         | 1      | 0.21%   |
| Yeyian              | 1         | 1      | 0.21%   |
| UMIS                | 1         | 1      | 0.21%   |
| Timetec             | 1         | 1      | 0.21%   |
| Teclast             | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 7         | 1.42%   |
| Seagate ST1000LM035-1RK172 1TB         | 6         | 1.22%   |
| Kingston SA400S37240G 240GB SSD        | 6         | 1.22%   |
| HGST HTS721010A9E630 1TB               | 5         | 1.02%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 4         | 0.81%   |
| Seagate ST1000LM048-2E7172 1TB         | 4         | 0.81%   |
| Kingston SV300S37A120G 120GB SSD       | 4         | 0.81%   |
| Kingston SA400S37480G 480GB SSD        | 4         | 0.81%   |
| Kingston SA400S37120G 120GB SSD        | 4         | 0.81%   |
| Crucial CT500MX500SSD1 500GB           | 4         | 0.81%   |
| Crucial CT120BX500SSD1 120GB           | 4         | 0.81%   |
| Unknown                                | 4         | 0.81%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 3         | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 0.61%   |
| Unknown SD32G  32GB                    | 3         | 0.61%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.61%   |
| Toshiba MQ01ABD075 752GB               | 3         | 0.61%   |
| Samsung SSD 980 PRO 1TB                | 3         | 0.61%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.61%   |
| Intel SSDPEKNW512G8 512GB              | 3         | 0.61%   |
| HGST HTS541010A9E680 1TB               | 3         | 0.61%   |
| Crucial CT480BX500SSD1 480GB           | 3         | 0.61%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.41%   |
| WDC WD5000LPCX-24VHAT0 500GB           | 2         | 0.41%   |
| WDC WD3200BEKT-60PVMT0 320GB           | 2         | 0.41%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 2         | 0.41%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 0.41%   |
| Unknown SS08G  8GB                     | 2         | 0.41%   |
| Unknown SDW32G  32GB                   | 2         | 0.41%   |
| Unknown DA4064  64GB                   | 2         | 0.41%   |
| Unknown BJTD4R  32GB                   | 2         | 0.41%   |
| Toshiba MQ02ABD100H 1TB                | 2         | 0.41%   |
| Toshiba MK5059GSXP 500GB               | 2         | 0.41%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 2         | 0.41%   |
| SPCC Solid State Disk 1TB              | 2         | 0.41%   |
| SK hynix HFS128G39TND-N210A 128GB SSD  | 2         | 0.41%   |
| SK hynix HFM512GDJTNI-82A0A 512GB      | 2         | 0.41%   |
| SK hynix HBG4e  32GB                   | 2         | 0.41%   |
| Seagate ST9500325AS 500GB              | 2         | 0.41%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 44     | 29.32%  |
| WDC                 | 38        | 38     | 28.57%  |
| Toshiba             | 19        | 20     | 14.29%  |
| Hitachi             | 14        | 15     | 10.53%  |
| HGST                | 14        | 19     | 10.53%  |
| Samsung Electronics | 4         | 5      | 3.01%   |
| Fujitsu             | 3         | 3      | 2.26%   |
| Unknown             | 1         | 1      | 0.75%   |
| SABRENT             | 1         | 1      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 45     | 17.62%  |
| Kingston            | 22        | 23     | 11.4%   |
| Crucial             | 21        | 43     | 10.88%  |
| SanDisk             | 16        | 18     | 8.29%   |
| WDC                 | 7         | 7      | 3.63%   |
| SK hynix            | 6         | 6      | 3.11%   |
| Apple               | 6         | 9      | 3.11%   |
| SPCC                | 5         | 5      | 2.59%   |
| PNY                 | 5         | 5      | 2.59%   |
| LITEON              | 5         | 5      | 2.59%   |
| Transcend           | 4         | 4      | 2.07%   |
| Toshiba             | 4         | 4      | 2.07%   |
| Micron Technology   | 4         | 8      | 2.07%   |
| Intel               | 4         | 7      | 2.07%   |
| A-DATA Technology   | 4         | 6      | 2.07%   |
| Netac               | 3         | 3      | 1.55%   |
| Dogfish             | 3         | 3      | 1.55%   |
| China               | 3         | 3      | 1.55%   |
| Team                | 2         | 2      | 1.04%   |
| Patriot             | 2         | 2      | 1.04%   |
| OCZ                 | 2         | 2      | 1.04%   |
| KingSpec            | 2         | 2      | 1.04%   |
| KingDian            | 2         | 2      | 1.04%   |
| Indilinx            | 2         | 4      | 1.04%   |
| EYOTA               | 2         | 2      | 1.04%   |
| Corsair             | 2         | 2      | 1.04%   |
| Unknown             | 2         | 2      | 1.04%   |
| ZTC                 | 1         | 1      | 0.52%   |
| Yeyian              | 1         | 1      | 0.52%   |
| Teclast             | 1         | 1      | 0.52%   |
| SWORDBILL           | 1         | 2      | 0.52%   |
| Smart               | 1         | 1      | 0.52%   |
| RENICE              | 1         | 1      | 0.52%   |
| Phison              | 1         | 1      | 0.52%   |
| LITEONIT            | 1         | 1      | 0.52%   |
| KingFast            | 1         | 1      | 0.52%   |
| Intenso             | 1         | 1      | 0.52%   |
| Hewlett-Packard     | 1         | 1      | 0.52%   |
| GOODRAM             | 1         | 1      | 0.52%   |
| Gigabyte Technology | 1         | 1      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 168       | 244    | 37.92%  |
| HDD     | 131       | 146    | 29.57%  |
| NVMe    | 109       | 133    | 24.6%   |
| MMC     | 33        | 40     | 7.45%   |
| Unknown | 2         | 2      | 0.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 261       | 384    | 63.66%  |
| NVMe | 109       | 133    | 26.59%  |
| MMC  | 33        | 40     | 8.05%   |
| SAS  | 7         | 8      | 1.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 219       | 288    | 75.26%  |
| 0.51-1.0   | 66        | 96     | 22.68%  |
| 1.01-2.0   | 4         | 4      | 1.37%   |
| 3.01-4.0   | 2         | 2      | 0.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 112       | 28.87%  |
| 251-500        | 83        | 21.39%  |
| 51-100         | 50        | 12.89%  |
| 501-1000       | 48        | 12.37%  |
| 21-50          | 42        | 10.82%  |
| 1-20           | 27        | 6.96%   |
| 1001-2000      | 16        | 4.12%   |
| More than 3000 | 5         | 1.29%   |
| 2001-3000      | 3         | 0.77%   |
| Unknown        | 2         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 185       | 46.6%   |
| 21-50          | 57        | 14.36%  |
| 51-100         | 54        | 13.6%   |
| 101-250        | 44        | 11.08%  |
| 251-500        | 27        | 6.8%    |
| 501-1000       | 17        | 4.28%   |
| 1001-2000      | 7         | 1.76%   |
| More than 3000 | 3         | 0.76%   |
| Unknown        | 2         | 0.5%    |
| 2001-3000      | 1         | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 3         | 3      | 4.92%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 2         | 2      | 3.28%   |
| Toshiba MK5059GSXP 500GB                     | 2         | 2      | 3.28%   |
| Seagate ST9500325AS 500GB                    | 2         | 2      | 3.28%   |
| Indilinx IND-S325S120G 120GB SSD             | 2         | 4      | 3.28%   |
| WDC WD5000BPVT-60HXZT3 500GB                 | 1         | 1      | 1.64%   |
| WDC WD3200LPVX-22V0TT0 320GB                 | 1         | 1      | 1.64%   |
| WDC WD3200BPVT-80ZEST0 320GB                 | 1         | 1      | 1.64%   |
| WDC WD3200BPVT-24JJ5T0 320GB                 | 1         | 1      | 1.64%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 1.64%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 1.64%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1         | 1      | 1.64%   |
| WDC WD1600BEVT-22A23T0 160GB                 | 1         | 1      | 1.64%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD         | 1         | 1      | 1.64%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 1.64%   |
| Toshiba MK7575GSX 752GB                      | 1         | 2      | 1.64%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 1.64%   |
| SK hynix BC711 HFM512GD3JX013N 512GB         | 1         | 1      | 1.64%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 1.64%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 1.64%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 1.64%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 1.64%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 1.64%   |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 1.64%   |
| Seagate ST320LT012-9WS14C 320GB              | 1         | 1      | 1.64%   |
| Seagate ST320LT009-9WC142 320GB              | 1         | 1      | 1.64%   |
| Seagate ST320LT007-9ZV142 320GB              | 1         | 3      | 1.64%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 2      | 1.64%   |
| Samsung Electronics HS122JC 120GB            | 1         | 2      | 1.64%   |
| Samsung Electronics HM080HC 80GB             | 1         | 1      | 1.64%   |
| RENICE X2 64GB SSD                           | 1         | 1      | 1.64%   |
| OCZ VERTEX2 64GB SSD                         | 1         | 1      | 1.64%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 1.64%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 1      | 1.64%   |
| Intel SSDPEKKF512G8L 512GB                   | 1         | 2      | 1.64%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 1.64%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 1.64%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 16     | 22.95%  |
| WDC                 | 10        | 10     | 16.39%  |
| Hitachi             | 8         | 8      | 13.11%  |
| Toshiba             | 6         | 7      | 9.84%   |
| HGST                | 6         | 7      | 9.84%   |
| Samsung Electronics | 4         | 6      | 6.56%   |
| Kingston            | 2         | 2      | 3.28%   |
| Indilinx            | 2         | 4      | 3.28%   |
| Crucial             | 2         | 11     | 3.28%   |
| SK hynix            | 1         | 1      | 1.64%   |
| SanDisk             | 1         | 1      | 1.64%   |
| RENICE              | 1         | 1      | 1.64%   |
| OCZ                 | 1         | 1      | 1.64%   |
| Intel               | 1         | 2      | 1.64%   |
| Fujitsu             | 1         | 1      | 1.64%   |
| A-DATA Technology   | 1         | 1      | 1.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 16     | 30.43%  |
| WDC                 | 10        | 10     | 21.74%  |
| Hitachi             | 8         | 8      | 17.39%  |
| HGST                | 6         | 7      | 13.04%  |
| Toshiba             | 5         | 6      | 10.87%  |
| Samsung Electronics | 2         | 3      | 4.35%   |
| Fujitsu             | 1         | 1      | 2.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 46        | 51     | 75.41%  |
| SSD  | 13        | 25     | 21.31%  |
| NVMe | 2         | 3      | 3.28%   |

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
| Works    | 300       | 433    | 73.71%  |
| Malfunc  | 60        | 79     | 14.74%  |
| Detected | 47        | 53     | 11.55%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 262       | 62.23%  |
| AMD                          | 43        | 10.21%  |
| Samsung Electronics          | 30        | 7.13%   |
| SK hynix                     | 16        | 3.8%    |
| SanDisk                      | 16        | 3.8%    |
| KIOXIA                       | 9         | 2.14%   |
| Kingston Technology Company  | 8         | 1.9%    |
| Nvidia                       | 7         | 1.66%   |
| Toshiba America Info Systems | 5         | 1.19%   |
| Phison Electronics           | 5         | 1.19%   |
| Micron Technology            | 5         | 1.19%   |
| Silicon Motion               | 4         | 0.95%   |
| Micron/Crucial Technology    | 3         | 0.71%   |
| Union Memory (Shenzhen)      | 1         | 0.24%   |
| Silicon Image                | 1         | 0.24%   |
| Shenzhen Longsys Electronics | 1         | 0.24%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.24%   |
| Marvell Technology Group     | 1         | 0.24%   |
| Lite-On Technology           | 1         | 0.24%   |
| Lenovo                       | 1         | 0.24%   |
| ADATA Technology             | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 38        | 8.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 34        | 7.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 27        | 6%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 26        | 5.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 17        | 3.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 12        | 2.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 2.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 2.44%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 2.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 2%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 9         | 2%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 9         | 2%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 1.78%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 1.56%   |
| Samsung NVMe SSD Controller 980                                                | 7         | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 7         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 1.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.33%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 1.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.33%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 1.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.33%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 6         | 1.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 1.33%   |
| SK hynix BC511 NVMe SSD                                                        | 5         | 1.11%   |
| Intel SSD 660P Series                                                          | 5         | 1.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.11%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4         | 0.89%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 0.89%   |
| Phison E12 NVMe Controller                                                     | 4         | 0.89%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 4         | 0.89%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 4         | 0.89%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 4         | 0.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.67%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 0.67%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 3         | 0.67%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 3         | 0.67%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 3         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 268       | 61.89%  |
| NVMe | 108       | 24.94%  |
| IDE  | 30        | 6.93%   |
| RAID | 27        | 6.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 309       | 82.62%  |
| AMD    | 65        | 17.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 8         | 2.14%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 8         | 2.14%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 8         | 2.14%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 7         | 1.87%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 6         | 1.6%    |
| Intel Atom CPU Z3735F @ 1.33GHz             | 6         | 1.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.34%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 5         | 1.34%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 5         | 1.34%   |
| Intel 12th Gen Core i5-1235U                | 5         | 1.34%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 4         | 1.07%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 4         | 1.07%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 1.07%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 1.07%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 4         | 1.07%   |
| Intel 12th Gen Core i7-12700H               | 4         | 1.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.07%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 0.8%    |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 3         | 0.8%    |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 3         | 0.8%    |
| Intel Core i5-4300M CPU @ 2.60GHz           | 3         | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 0.8%    |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 0.8%    |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 0.8%    |
| Intel Core i5-2430M CPU @ 2.40GHz           | 3         | 0.8%    |
| Intel Core i3-4000M CPU @ 2.40GHz           | 3         | 0.8%    |
| Intel Core i3-2350M CPU @ 2.30GHz           | 3         | 0.8%    |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 0.8%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 3         | 0.8%    |
| Intel Celeron CPU 1007U @ 1.50GHz           | 3         | 0.8%    |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 3         | 0.8%    |
| AMD Ryzen 7 5800H with Radeon Graphics      | 3         | 0.8%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.53%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 2         | 0.53%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 0.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 0.53%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 2         | 0.53%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 2         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 80        | 21.39%  |
| Intel Core i7           | 76        | 20.32%  |
| Other                   | 32        | 8.56%   |
| Intel Celeron           | 32        | 8.56%   |
| Intel Core i3           | 28        | 7.49%   |
| Intel Atom              | 19        | 5.08%   |
| AMD Ryzen 7             | 16        | 4.28%   |
| Intel Core 2 Duo        | 15        | 4.01%   |
| AMD Ryzen 5             | 15        | 4.01%   |
| Intel Pentium           | 7         | 1.87%   |
| AMD Ryzen 3             | 5         | 1.34%   |
| AMD A6                  | 5         | 1.34%   |
| AMD Ryzen 9             | 4         | 1.07%   |
| Intel Pentium M         | 3         | 0.8%    |
| Intel Pentium Dual-Core | 3         | 0.8%    |
| Intel Genuine           | 3         | 0.8%    |
| Intel Core 2            | 3         | 0.8%    |
| AMD Turion 64 X2 Mobile | 3         | 0.8%    |
| AMD E1                  | 3         | 0.8%    |
| AMD E                   | 3         | 0.8%    |
| AMD A8                  | 3         | 0.8%    |
| Intel Celeron M         | 2         | 0.53%   |
| AMD A4                  | 2         | 0.53%   |
| Intel Xeon              | 1         | 0.27%   |
| Intel Pentium Silver    | 1         | 0.27%   |
| Intel Pentium Gold      | 1         | 0.27%   |
| Intel Pentium Dual      | 1         | 0.27%   |
| Intel Core Duo          | 1         | 0.27%   |
| Intel Celeron Dual-Core | 1         | 0.27%   |
| AMD Sempron             | 1         | 0.27%   |
| AMD Phenom II           | 1         | 0.27%   |
| AMD E2                  | 1         | 0.27%   |
| AMD Athlon 64 X2        | 1         | 0.27%   |
| AMD A12                 | 1         | 0.27%   |
| AMD A10                 | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 198       | 52.94%  |
| 4      | 103       | 27.54%  |
| 6      | 22        | 5.88%   |
| 8      | 21        | 5.61%   |
| 1      | 16        | 4.28%   |
| 10     | 7         | 1.87%   |
| 14     | 4         | 1.07%   |
| 12     | 2         | 0.53%   |
| 5      | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 374       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 260       | 69.52%  |
| 1      | 114       | 30.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 362       | 96.53%  |
| 32-bit         | 13        | 3.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 9.95%   |
| 0x206a7    | 32        | 8.38%   |
| 0x306a9    | 25        | 6.54%   |
| 0x406e3    | 18        | 4.71%   |
| 0x806c1    | 13        | 3.4%    |
| 0x306c3    | 12        | 3.14%   |
| 0x20655    | 12        | 3.14%   |
| 0x1067a    | 12        | 3.14%   |
| 0x0a50000c | 12        | 3.14%   |
| 0x40651    | 10        | 2.62%   |
| 0x30678    | 10        | 2.62%   |
| 0x806e9    | 9         | 2.36%   |
| 0x306d4    | 9         | 2.36%   |
| 0x08608103 | 9         | 2.36%   |
| 0x906ea    | 8         | 2.09%   |
| 0x806ec    | 8         | 2.09%   |
| 0x506e3    | 8         | 2.09%   |
| 0x806ea    | 7         | 1.83%   |
| 0x906a4    | 6         | 1.57%   |
| 0x906a3    | 6         | 1.57%   |
| 0x706a8    | 6         | 1.57%   |
| 0x406c4    | 6         | 1.57%   |
| 0xa0652    | 5         | 1.31%   |
| 0x906e9    | 5         | 1.31%   |
| 0x706a1    | 5         | 1.31%   |
| 0x20652    | 5         | 1.31%   |
| 0x6fd      | 4         | 1.05%   |
| 0x6d8      | 4         | 1.05%   |
| 0x106ca    | 4         | 1.05%   |
| 0x106c2    | 4         | 1.05%   |
| 0x08108102 | 4         | 1.05%   |
| 0x03000027 | 4         | 1.05%   |
| 0x10676    | 3         | 0.79%   |
| 0x08600104 | 3         | 0.79%   |
| 0xb06a3    | 2         | 0.52%   |
| 0x906ed    | 2         | 0.52%   |
| 0x806d1    | 2         | 0.52%   |
| 0x706e5    | 2         | 0.52%   |
| 0x506c9    | 2         | 0.52%   |
| 0x30661    | 2         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 44        | 11.76%  |
| SandyBridge      | 37        | 9.89%   |
| IvyBridge        | 30        | 8.02%   |
| Skylake          | 27        | 7.22%   |
| Haswell          | 24        | 6.42%   |
| Silvermont       | 19        | 5.08%   |
| Unknown          | 19        | 5.08%   |
| Westmere         | 18        | 4.81%   |
| Penryn           | 17        | 4.55%   |
| TigerLake        | 15        | 4.01%   |
| Zen 3            | 14        | 3.74%   |
| Goldmont plus    | 11        | 2.94%   |
| Core             | 10        | 2.67%   |
| Bonnell          | 10        | 2.67%   |
| Broadwell        | 9         | 2.41%   |
| Alderlake Hybrid | 8         | 2.14%   |
| P6               | 7         | 1.87%   |
| Zen+             | 6         | 1.6%    |
| IceLake          | 6         | 1.6%    |
| Puma             | 5         | 1.34%   |
| CometLake        | 5         | 1.34%   |
| Zen 2            | 4         | 1.07%   |
| K8 Hammer        | 4         | 1.07%   |
| K10 Llano        | 4         | 1.07%   |
| Excavator        | 4         | 1.07%   |
| Zen              | 3         | 0.8%    |
| Goldmont         | 3         | 0.8%    |
| Bobcat           | 3         | 0.8%    |
| Nehalem          | 2         | 0.53%   |
| Jaguar           | 2         | 0.53%   |
| Tremont          | 1         | 0.27%   |
| Piledriver       | 1         | 0.27%   |
| K8 & K10 hybrid  | 1         | 0.27%   |
| K10              | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 281       | 61.62%  |
| Nvidia | 89        | 19.52%  |
| AMD    | 86        | 18.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 6.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 29        | 6.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 3.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 2.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 2.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 2.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 2.31%   |
| AMD Lucienne                                                                             | 11        | 2.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 2.1%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 2.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 2.1%    |
| Intel HD Graphics 620                                                                    | 9         | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 1.89%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.68%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 1.68%   |
| Intel HD Graphics 530                                                                    | 8         | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 1.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.26%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.05%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 5         | 1.05%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 5         | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.84%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 4         | 0.84%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.84%   |
| Intel HD Graphics 630                                                                    | 4         | 0.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.84%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 0.84%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 4         | 0.84%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.84%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.63%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 3         | 0.63%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 3         | 0.63%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.63%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 205       | 54.81%  |
| Intel + Nvidia | 58        | 15.51%  |
| 1 x AMD        | 55        | 14.71%  |
| 1 x Nvidia     | 22        | 5.88%   |
| Intel + AMD    | 15        | 4.01%   |
| 2 x AMD        | 8         | 2.14%   |
| AMD + Nvidia   | 8         | 2.14%   |
| 2 x Intel      | 3         | 0.8%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 341       | 89.97%  |
| Proprietary | 23        | 6.07%   |
| Unknown     | 15        | 3.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 278       | 73.54%  |
| 0.01-0.5   | 53        | 14.02%  |
| 1.01-2.0   | 19        | 5.03%   |
| 0.51-1.0   | 16        | 4.23%   |
| 3.01-4.0   | 7         | 1.85%   |
| 7.01-8.0   | 3         | 0.79%   |
| 5.01-6.0   | 1         | 0.26%   |
| 2.01-3.0   | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 78        | 19.45%  |
| Chimei Innolux          | 61        | 15.21%  |
| LG Display              | 50        | 12.47%  |
| Samsung Electronics     | 44        | 10.97%  |
| BOE                     | 42        | 10.47%  |
| Chi Mei Optoelectronics | 17        | 4.24%   |
| Lenovo                  | 14        | 3.49%   |
| Apple                   | 11        | 2.74%   |
| PANDA                   | 10        | 2.49%   |
| Hewlett-Packard         | 10        | 2.49%   |
| Goldstar                | 7         | 1.75%   |
| HannStar                | 6         | 1.5%    |
| Ancor Communications    | 6         | 1.5%    |
| Sharp                   | 5         | 1.25%   |
| InfoVision              | 5         | 1.25%   |
| Dell                    | 5         | 1.25%   |
| LG Philips              | 4         | 1%      |
| Sony                    | 3         | 0.75%   |
| CPT                     | 3         | 0.75%   |
| Philips                 | 2         | 0.5%    |
| Acer                    | 2         | 0.5%    |
| Vizio                   | 1         | 0.25%   |
| TMX                     | 1         | 0.25%   |
| Sunplus                 | 1         | 0.25%   |
| STA                     | 1         | 0.25%   |
| Panasonic               | 1         | 0.25%   |
| Packard Bell            | 1         | 0.25%   |
| ONN                     | 1         | 0.25%   |
| NEC Computers           | 1         | 0.25%   |
| LTM                     | 1         | 0.25%   |
| KDC                     | 1         | 0.25%   |
| InnoLux Display         | 1         | 0.25%   |
| HKC                     | 1         | 0.25%   |
| Eizo                    | 1         | 0.25%   |
| BenQ                    | 1         | 0.25%   |
| ASUSTek Computer        | 1         | 0.25%   |
| AOC                     | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 7         | 1.75%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 5         | 1.25%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 1%      |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 1%      |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 4         | 1%      |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 3         | 0.75%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.75%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 3         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 3         | 0.75%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 3         | 0.75%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 2         | 0.5%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.5%    |
| LG Display LCD Monitor LGD0709 1920x1080 344x194mm 15.5-inch             | 2         | 0.5%    |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 2         | 0.5%    |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.5%    |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.5%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.5%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN152E 1920x1080 344x193mm 15.5-inch         | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.5%    |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 2         | 0.5%    |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 2         | 0.5%    |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                    | 2         | 0.5%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.5%    |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch           | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 157       | 40.57%  |
| 1366x768 (WXGA)    | 124       | 32.04%  |
| 1280x800 (WXGA)    | 19        | 4.91%   |
| 1600x900 (HD+)     | 18        | 4.65%   |
| 3840x2160 (4K)     | 13        | 3.36%   |
| 1024x600           | 8         | 2.07%   |
| 1440x900 (WXGA+)   | 6         | 1.55%   |
| 2560x1440 (QHD)    | 5         | 1.29%   |
| 1920x1200 (WUXGA)  | 5         | 1.29%   |
| 1680x1050 (WSXGA+) | 5         | 1.29%   |
| 1280x1024 (SXGA)   | 4         | 1.03%   |
| 2880x1800          | 3         | 0.78%   |
| 2560x1600          | 3         | 0.78%   |
| 2560x1080          | 3         | 0.78%   |
| 1024x768 (XGA)     | 3         | 0.78%   |
| 3840x2400          | 2         | 0.52%   |
| 2256x1504          | 2         | 0.52%   |
| 2160x1440          | 2         | 0.52%   |
| 1400x1050          | 2         | 0.52%   |
| 3200x2000          | 1         | 0.26%   |
| 3200x1800 (QHD+)   | 1         | 0.26%   |
| 1360x768           | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 169       | 42.25%  |
| 13      | 55        | 13.75%  |
| 14      | 43        | 10.75%  |
| 17      | 27        | 6.75%   |
| 11      | 14        | 3.5%    |
| 24      | 13        | 3.25%   |
| 23      | 11        | 2.75%   |
| 12      | 11        | 2.75%   |
| 10      | 11        | 2.75%   |
| 16      | 6         | 1.5%    |
| 27      | 5         | 1.25%   |
| 21      | 5         | 1.25%   |
| 19      | 5         | 1.25%   |
| 34      | 3         | 0.75%   |
| 20      | 3         | 0.75%   |
| 18      | 3         | 0.75%   |
| Unknown | 3         | 0.75%   |
| 43      | 2         | 0.5%    |
| 40      | 2         | 0.5%    |
| 32      | 2         | 0.5%    |
| 26      | 2         | 0.5%    |
| 84      | 1         | 0.25%   |
| 46      | 1         | 0.25%   |
| 37      | 1         | 0.25%   |
| 36      | 1         | 0.25%   |
| 25      | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 236       | 59.15%  |
| 201-300     | 61        | 15.29%  |
| 351-400     | 43        | 10.78%  |
| 501-600     | 31        | 7.77%   |
| 401-500     | 12        | 3.01%   |
| 701-800     | 6         | 1.5%    |
| 801-900     | 3         | 0.75%   |
| Unknown     | 3         | 0.75%   |
| 901-1000    | 2         | 0.5%    |
| 1501-2000   | 1         | 0.25%   |
| 1001-1500   | 1         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 304       | 82.83%  |
| 16/10   | 44        | 11.99%  |
| 3/2     | 6         | 1.63%   |
| 4/3     | 5         | 1.36%   |
| 5/4     | 4         | 1.09%   |
| 21/9    | 3         | 0.82%   |
| Unknown | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 169       | 42.25%  |
| 81-90          | 80        | 20%     |
| 121-130        | 26        | 6.5%    |
| 201-250        | 24        | 6%      |
| 71-80          | 17        | 4.25%   |
| 51-60          | 14        | 3.5%    |
| 61-70          | 11        | 2.75%   |
| 41-50          | 11        | 2.75%   |
| 151-200        | 9         | 2.25%   |
| 501-1000       | 7         | 1.75%   |
| 301-350        | 6         | 1.5%    |
| 251-300        | 6         | 1.5%    |
| 351-500        | 5         | 1.25%   |
| 111-120        | 5         | 1.25%   |
| 141-150        | 3         | 0.75%   |
| Unknown        | 3         | 0.75%   |
| 91-100         | 2         | 0.5%    |
| More than 1000 | 1         | 0.25%   |
| 131-140        | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 157       | 39.95%  |
| 101-120       | 122       | 31.04%  |
| 51-100        | 77        | 19.59%  |
| 161-240       | 23        | 5.85%   |
| More than 240 | 9         | 2.29%   |
| Unknown       | 3         | 0.76%   |
| 1-50          | 2         | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 313       | 82.59%  |
| 2     | 50        | 13.19%  |
| 0     | 13        | 3.43%   |
| 3     | 3         | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 195       | 32.34%  |
| Realtek Semiconductor             | 183       | 30.35%  |
| Qualcomm Atheros                  | 90        | 14.93%  |
| Broadcom                          | 44        | 7.3%    |
| MediaTek                          | 11        | 1.82%   |
| Broadcom Limited                  | 10        | 1.66%   |
| TP-Link                           | 7         | 1.16%   |
| Marvell Technology Group          | 7         | 1.16%   |
| Ralink                            | 5         | 0.83%   |
| Nvidia                            | 5         | 0.83%   |
| ASIX Electronics                  | 5         | 0.83%   |
| Sierra Wireless                   | 4         | 0.66%   |
| Samsung Electronics               | 4         | 0.66%   |
| Motorola PCS                      | 4         | 0.66%   |
| OPPO Electronics                  | 3         | 0.5%    |
| Huawei Technologies               | 3         | 0.5%    |
| Ericsson Business Mobile Networks | 3         | 0.5%    |
| Attansic Technology               | 3         | 0.5%    |
| Ralink Technology                 | 2         | 0.33%   |
| Qualcomm Atheros Communications   | 2         | 0.33%   |
| Dell                              | 2         | 0.33%   |
| Sweex                             | 1         | 0.17%   |
| Qualcomm Technologies             | 1         | 0.17%   |
| Qualcomm                          | 1         | 0.17%   |
| NetGear                           | 1         | 0.17%   |
| Lenovo                            | 1         | 0.17%   |
| JMicron Technology                | 1         | 0.17%   |
| Hewlett-Packard                   | 1         | 0.17%   |
| Google                            | 1         | 0.17%   |
| Foxconn / Hon Hai                 | 1         | 0.17%   |
| D-Link                            | 1         | 0.17%   |
| ASUSTek Computer                  | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 113       | 15.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 29        | 3.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 2.6%    |
| Intel Wireless 8260                                                     | 14        | 1.92%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 14        | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 12        | 1.64%   |
| Intel Wireless 7260                                                     | 12        | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 1.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 1.5%    |
| Intel Wireless 8265 / 8275                                              | 11        | 1.5%    |
| Intel Wireless 3165                                                     | 11        | 1.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.37%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 1.37%   |
| Intel Wireless 7265                                                     | 9         | 1.23%   |
| Intel Ethernet Connection I217-LM                                       | 9         | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                                | 8         | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.96%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 0.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 0.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.82%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 0.68%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                                | 5         | 0.68%   |
| ASIX AX88179 Gigabit Ethernet                                           | 5         | 0.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 4         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 184       | 47.42%  |
| Qualcomm Atheros                | 70        | 18.04%  |
| Realtek Semiconductor           | 60        | 15.46%  |
| Broadcom                        | 31        | 7.99%   |
| MediaTek                        | 10        | 2.58%   |
| Broadcom Limited                | 8         | 2.06%   |
| TP-Link                         | 6         | 1.55%   |
| Ralink                          | 5         | 1.29%   |
| Sierra Wireless                 | 4         | 1.03%   |
| Ralink Technology               | 2         | 0.52%   |
| Qualcomm Atheros Communications | 2         | 0.52%   |
| Sweex                           | 1         | 0.26%   |
| Qualcomm Technologies           | 1         | 0.26%   |
| NetGear                         | 1         | 0.26%   |
| Hewlett-Packard                 | 1         | 0.26%   |
| D-Link                          | 1         | 0.26%   |
| ASUSTek Computer                | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 4.88%   |
| Intel Wireless 8260                                                     | 14        | 3.6%    |
| Intel Wi-Fi 6 AX200                                                     | 14        | 3.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 12        | 3.08%   |
| Intel Wireless 7260                                                     | 12        | 3.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 2.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 2.83%   |
| Intel Wireless 8265 / 8275                                              | 11        | 2.83%   |
| Intel Wireless 3165                                                     | 11        | 2.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 2.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.57%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 2.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 2.57%   |
| Intel Wireless 7265                                                     | 9         | 2.31%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 2.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 2.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 1.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.8%    |
| Intel Centrino Advanced-N 6200                                          | 7         | 1.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 1.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.54%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.03%   |
| Intel Wireless-AC 9260                                                  | 4         | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.03%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 1.03%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.77%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.77%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.77%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.77%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 159       | 48.48%  |
| Intel                    | 80        | 24.39%  |
| Qualcomm Atheros         | 32        | 9.76%   |
| Broadcom                 | 18        | 5.49%   |
| Marvell Technology Group | 7         | 2.13%   |
| Nvidia                   | 5         | 1.52%   |
| ASIX Electronics         | 5         | 1.52%   |
| Samsung Electronics      | 4         | 1.22%   |
| OPPO Electronics         | 3         | 0.91%   |
| Motorola PCS             | 3         | 0.91%   |
| Attansic Technology      | 3         | 0.91%   |
| Broadcom Limited         | 2         | 0.61%   |
| TP-Link                  | 1         | 0.3%    |
| Qualcomm                 | 1         | 0.3%    |
| MediaTek                 | 1         | 0.3%    |
| Lenovo                   | 1         | 0.3%    |
| JMicron Technology       | 1         | 0.3%    |
| Huawei Technologies      | 1         | 0.3%    |
| Foxconn / Hon Hai        | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 113       | 34.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 29        | 8.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 14        | 4.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 11        | 3.32%   |
| Intel Ethernet Connection I217-LM                                              | 9         | 2.72%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 2.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 1.51%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 1.51%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 1.51%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 5         | 1.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 1.21%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4         | 1.21%   |
| Intel Ethernet Connection I219-V                                               | 4         | 1.21%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.21%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.91%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 0.91%   |
| OPPO OnePlus Nord                                                              | 3         | 0.91%   |
| Motorola PCS motorola edge 20 lite                                             | 3         | 0.91%   |
| Intel Ethernet Connection (5) I219-LM                                          | 3         | 0.91%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.91%   |
| Intel Ethernet Connection (16) I219-LM                                         | 3         | 0.91%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.91%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.91%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 3         | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.6%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.6%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.6%    |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.6%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.6%    |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.6%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 363       | 52.92%  |
| Ethernet | 312       | 45.48%  |
| Modem    | 9         | 1.31%   |
| Unknown  | 2         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 290       | 76.52%  |
| Ethernet | 88        | 23.22%  |
| Unknown  | 1         | 0.26%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 287       | 76.53%  |
| 1     | 76        | 20.27%  |
| 0     | 10        | 2.67%   |
| 3     | 2         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 304       | 80.21%  |
| Yes  | 75        | 19.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 129       | 43.29%  |
| Realtek Semiconductor           | 31        | 10.4%   |
| Qualcomm Atheros Communications | 26        | 8.72%   |
| Broadcom                        | 22        | 7.38%   |
| Lite-On Technology              | 14        | 4.7%    |
| IMC Networks                    | 14        | 4.7%    |
| Foxconn / Hon Hai               | 11        | 3.69%   |
| Cambridge Silicon Radio         | 11        | 3.69%   |
| Apple                           | 11        | 3.69%   |
| Hewlett-Packard                 | 8         | 2.68%   |
| Dell                            | 6         | 2.01%   |
| Toshiba                         | 4         | 1.34%   |
| Ralink                          | 3         | 1.01%   |
| Alps Electric                   | 3         | 1.01%   |
| ASUSTek Computer                | 2         | 0.67%   |
| Realtek                         | 1         | 0.34%   |
| Ralink Technology               | 1         | 0.34%   |
| MediaTek                        | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 58        | 19.46%  |
| Realtek Bluetooth Radio                                                             | 24        | 8.05%   |
| Intel AX201 Bluetooth                                                               | 19        | 6.38%   |
| Intel AX200 Bluetooth                                                               | 14        | 4.7%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 4.36%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 13        | 4.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 11        | 3.69%   |
| Intel Bluetooth Device                                                              | 10        | 3.36%   |
| Apple Bluetooth Host Controller                                                     | 7         | 2.35%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.01%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 2.01%   |
| IMC Networks Bluetooth Radio                                                        | 6         | 2.01%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 2.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.68%   |
| IMC Networks Wireless_Device                                                        | 5         | 1.68%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.68%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.34%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.34%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 1.34%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 1.34%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 1.34%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 4         | 1.34%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.01%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.01%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 1.01%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.01%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.01%   |
| Lite-On Wireless_Device                                                             | 2         | 0.67%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.67%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 0.67%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.67%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.67%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.67%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.34%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.34%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.34%   |
| Toshiba Askey for                                                                   | 1         | 0.34%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.34%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 295       | 65.41%  |
| AMD                     | 70        | 15.52%  |
| Nvidia                  | 61        | 13.53%  |
| Realtek Semiconductor   | 3         | 0.67%   |
| Texas Instruments       | 2         | 0.44%   |
| JMTek                   | 2         | 0.44%   |
| GN Netcom               | 2         | 0.44%   |
| C-Media Electronics     | 2         | 0.44%   |
| VIA Technologies        | 1         | 0.22%   |
| SteelSeries ApS         | 1         | 0.22%   |
| Plantronics             | 1         | 0.22%   |
| Mark of the Unicorn     | 1         | 0.22%   |
| Logitech                | 1         | 0.22%   |
| Lenovo                  | 1         | 0.22%   |
| Jieli Technology        | 1         | 0.22%   |
| Guillemot               | 1         | 0.22%   |
| Generalplus Technology  | 1         | 0.22%   |
| Focusrite-Novation      | 1         | 0.22%   |
| FIFINE 683 Microphone   | 1         | 0.22%   |
| Conexant Systems        | 1         | 0.22%   |
| CMX Systems             | 1         | 0.22%   |
| BEHRINGER International | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 40        | 7.43%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 37        | 6.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 36        | 6.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 30        | 5.58%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 25        | 4.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 20        | 3.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 15        | 2.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 2.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 2.42%   |
| AMD FCH Azalia Controller                                                                         | 13        | 2.42%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 12        | 2.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 1.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.86%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 1.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.67%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 1.49%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.49%   |
| Nvidia Audio device                                                                               | 7         | 1.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 1.3%    |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.12%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.93%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.74%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 0.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.74%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 4         | 0.74%   |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.56%   |
| Nvidia MCP89 High Definition Audio                                                                | 3         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Samsung Electronics            | 111       | 24.61%  |
| SK hynix                       | 98        | 21.73%  |
| Unknown                        | 50        | 11.09%  |
| Micron Technology              | 46        | 10.2%   |
| Kingston                       | 38        | 8.43%   |
| Crucial                        | 22        | 4.88%   |
| Elpida                         | 10        | 2.22%   |
| A-DATA Technology              | 10        | 2.22%   |
| Unknown (ABCD)                 | 9         | 2%      |
| Ramaxel Technology             | 9         | 2%      |
| Unknown                        | 7         | 1.55%   |
| Corsair                        | 6         | 1.33%   |
| Transcend                      | 5         | 1.11%   |
| Smart                          | 4         | 0.89%   |
| Nanya Technology               | 3         | 0.67%   |
| Teikon                         | 2         | 0.44%   |
| Team                           | 2         | 0.44%   |
| Patriot                        | 2         | 0.44%   |
| G.Skill                        | 2         | 0.44%   |
| Wilk                           | 1         | 0.22%   |
| Unknown (F301)                 | 1         | 0.22%   |
| TRS STAR                       | 1         | 0.22%   |
| PNY                            | 1         | 0.22%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.22%   |
| Lexar Co Limited               | 1         | 0.22%   |
| Innodisk                       | 1         | 0.22%   |
| High Bridge                    | 1         | 0.22%   |
| Hewlett-Packard                | 1         | 0.22%   |
| Essencore                      | 1         | 0.22%   |
| CSX                            | 1         | 0.22%   |
| Avant                          | 1         | 0.22%   |
| ASint Technology               | 1         | 0.22%   |
| Apacer                         | 1         | 0.22%   |
| 48spaces                       | 1         | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 8         | 1.65%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 1.65%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 1.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.45%   |
| Unknown                                                          | 7         | 1.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.24%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.24%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 1.03%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.03%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 5         | 1.03%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 0.83%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.83%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.83%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.83%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.83%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.83%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.83%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.83%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 4         | 0.83%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 4         | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.62%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 3         | 0.62%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 3         | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.62%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 0.62%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.62%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 0.62%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 3         | 0.62%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s            | 3         | 0.62%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.62%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.62%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.62%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.41%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.41%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 170       | 44.97%  |
| DDR4    | 140       | 37.04%  |
| DDR2    | 21        | 5.56%   |
| LPDDR4  | 14        | 3.7%    |
| DDR     | 9         | 2.38%   |
| SDRAM   | 7         | 1.85%   |
| LPDDR3  | 6         | 1.59%   |
| DRAM    | 3         | 0.79%   |
| DDR5    | 3         | 0.79%   |
| Unknown | 3         | 0.79%   |
| LPDDR5  | 2         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 353       | 92.89%  |
| Row Of Chips | 17        | 4.47%   |
| Chip         | 4         | 1.05%   |
| DIMM         | 3         | 0.79%   |
| Unknown      | 3         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 146       | 34.35%  |
| 4096  | 140       | 32.94%  |
| 2048  | 67        | 15.76%  |
| 16384 | 42        | 9.88%   |
| 1024  | 21        | 4.94%   |
| 32768 | 6         | 1.41%   |
| 512   | 3         | 0.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 104       | 25.24%  |
| 3200    | 64        | 15.53%  |
| 2667    | 52        | 12.62%  |
| 1334    | 36        | 8.74%   |
| 2400    | 29        | 7.04%   |
| 1333    | 26        | 6.31%   |
| Unknown | 19        | 4.61%   |
| 667     | 14        | 3.4%    |
| 2133    | 13        | 3.16%   |
| 1067    | 12        | 2.91%   |
| 4199    | 5         | 1.21%   |
| 3266    | 5         | 1.21%   |
| 1867    | 5         | 1.21%   |
| 800     | 5         | 1.21%   |
| 533     | 5         | 1.21%   |
| 4800    | 3         | 0.73%   |
| 4267    | 3         | 0.73%   |
| 8400    | 2         | 0.49%   |
| 975     | 2         | 0.49%   |
| 6400    | 1         | 0.24%   |
| 5500    | 1         | 0.24%   |
| 4266    | 1         | 0.24%   |
| 2933    | 1         | 0.24%   |
| 666     | 1         | 0.24%   |
| 400     | 1         | 0.24%   |
| 166     | 1         | 0.24%   |
| 100     | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 33.33%  |
| Samsung Electronics | 1         | 16.67%  |
| Dymo-CoStar         | 1         | 16.67%  |
| Canon               | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 16.67%  |
| HP LaserJet P2055 series           | 1         | 16.67%  |
| HP LaserJet 1022                   | 1         | 16.67%  |
| Dymo-CoStar LabelWriter 450        | 1         | 16.67%  |
| Canon LiDE 400                     | 1         | 16.67%  |
| Brother DCP-L2540DW                | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 50%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 72        | 22.86%  |
| IMC Networks                           | 28        | 8.89%   |
| Microdia                               | 26        | 8.25%   |
| Realtek Semiconductor                  | 25        | 7.94%   |
| Bison Electronics                      | 19        | 6.03%   |
| Sunplus Innovation Technology          | 18        | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 5.71%   |
| Quanta                                 | 16        | 5.08%   |
| Suyin                                  | 12        | 3.81%   |
| Luxvisions Innotech Limited            | 11        | 3.49%   |
| Lite-On Technology                     | 10        | 3.17%   |
| Lenovo                                 | 8         | 2.54%   |
| Apple                                  | 8         | 2.54%   |
| Acer                                   | 8         | 2.54%   |
| Silicon Motion                         | 5         | 1.59%   |
| Ricoh                                  | 5         | 1.59%   |
| Alcor Micro                            | 5         | 1.59%   |
| Logitech                               | 4         | 1.27%   |
| Z-Star Microelectronics                | 3         | 0.95%   |
| Syntek                                 | 3         | 0.95%   |
| Y Media                                | 1         | 0.32%   |
| Xiongmai                               | 1         | 0.32%   |
| WaveRider Communications               | 1         | 0.32%   |
| Samsung Electronics                    | 1         | 0.32%   |
| Primax Electronics                     | 1         | 0.32%   |
| Novatek Microelectronics               | 1         | 0.32%   |
| Importek                               | 1         | 0.32%   |
| icSpring                               | 1         | 0.32%   |
| Hewlett-Packard                        | 1         | 0.32%   |
| Goodong Industry                       | 1         | 0.32%   |
| Cubeternet                             | 1         | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 19        | 6.03%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 10        | 3.17%   |
| Microdia Integrated_Webcam_HD                               | 8         | 2.54%   |
| Realtek Integrated_Webcam_HD                                | 7         | 2.22%   |
| Sunplus Integrated_Webcam_HD                                | 6         | 1.9%    |
| Lite-On Integrated Camera                                   | 5         | 1.59%   |
| IMC Networks Integrated Camera                              | 5         | 1.59%   |
| Sunplus HD WebCam                                           | 4         | 1.27%   |
| Quanta HD User Facing                                       | 4         | 1.27%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera        | 4         | 1.27%   |
| Lenovo Integrated Webcam [R5U877]                           | 4         | 1.27%   |
| Chicony USB 2.0 Camera                                      | 4         | 1.27%   |
| Chicony TOSHIBA Web Camera - HD                             | 4         | 1.27%   |
| Chicony HP TrueVision HD Camera                             | 4         | 1.27%   |
| Chicony HD WebCam                                           | 4         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 4         | 1.27%   |
| Syntek EasyCamera                                           | 3         | 0.95%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 3         | 0.95%   |
| Sunplus ASUS Webcam                                         | 3         | 0.95%   |
| Ricoh USB2.0 Camera                                         | 3         | 0.95%   |
| Realtek USB2.0 HD UVC WebCam                                | 3         | 0.95%   |
| Realtek USB Camera                                          | 3         | 0.95%   |
| Quanta HP TrueVision HD Camera                              | 3         | 0.95%   |
| Microdia Integrated_Webcam_FHD                              | 3         | 0.95%   |
| Microdia Integrated Webcam                                  | 3         | 0.95%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 3         | 0.95%   |
| Lenovo Integrated Webcam                                    | 3         | 0.95%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 0.95%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 0.95%   |
| Chicony HD User Facing                                      | 3         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 3         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 3         | 0.95%   |
| Bison Integrated Camera                                     | 3         | 0.95%   |
| Bison HD Webcam                                             | 3         | 0.95%   |
| Bison BisonCam,NB Pro                                       | 3         | 0.95%   |
| Apple Built-in iSight                                       | 3         | 0.95%   |
| Alcor Micro USB 2.0 PC cam                                  | 3         | 0.95%   |
| Suyin Acer CrystalEye Webcam                                | 2         | 0.63%   |
| Sunplus Integrated_Webcam_FHD                               | 2         | 0.63%   |
| Realtek Integrated Webcam HD                                | 2         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 22        | 33.85%  |
| Synaptics                          | 11        | 16.92%  |
| Upek                               | 8         | 12.31%  |
| Shenzhen Goodix Technology         | 8         | 12.31%  |
| AuthenTec                          | 7         | 10.77%  |
| Elan Microelectronics              | 4         | 6.15%   |
| LighTuning Technology              | 2         | 3.08%   |
| STMicroelectronics                 | 1         | 1.54%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.54%   |
| Focal-systems.Corp                 | 1         | 1.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 9.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 6         | 9.23%   |
| Shenzhen Goodix  FingerPrint Device                             | 6         | 9.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 7.69%   |
| AuthenTec AES2810                                               | 4         | 6.15%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 4.62%   |
| Validity Sensors Synaptics WBDI                                 | 3         | 4.62%   |
| Upek TCS5B Fingerprint sensor                                   | 2         | 3.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 3.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 2         | 3.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 3.08%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 3.08%   |
| Elan ELAN:Fingerprint                                           | 2         | 3.08%   |
| Elan ELAN:ARM-M4                                                | 2         | 3.08%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 2         | 3.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 1.54%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.54%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 1.54%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 1.54%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.54%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.54%   |
| Synaptics UWP WBDI                                              | 1         | 1.54%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.54%   |
| Synaptics Fingerprint reader [HP G6]                            | 1         | 1.54%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 1.54%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.54%   |
| LighTuning Fingerprint Reader                                   | 1         | 1.54%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 1.54%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 1.54%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 1.54%   |
| Unknown                                                         | 1         | 1.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 15        | 48.39%  |
| Alcor Micro           | 10        | 32.26%  |
| Lenovo                | 3         | 9.68%   |
| Advanced Card Systems | 2         | 6.45%   |
| O2 Micro              | 1         | 3.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 32.26%  |
| Broadcom 58200                                                               | 6         | 19.35%  |
| Broadcom 5880                                                                | 5         | 16.13%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 9.68%   |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 9.68%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.23%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.23%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 3.23%   |
| Advanced Card Systems ACR122U                                                | 1         | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 219       | 57.33%  |
| 1     | 121       | 31.68%  |
| 2     | 39        | 10.21%  |
| 3     | 3         | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 84        | 42%     |
| Fingerprint reader       | 65        | 32.5%   |
| Chipcard                 | 28        | 14%     |
| Net/wireless             | 5         | 2.5%    |
| Multimedia controller    | 5         | 2.5%    |
| Storage                  | 3         | 1.5%    |
| Camera                   | 3         | 1.5%    |
| Flash memory             | 2         | 1%      |
| Communication controller | 2         | 1%      |
| Bluetooth                | 2         | 1%      |
| Net/ethernet             | 1         | 0.5%    |

