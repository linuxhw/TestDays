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

Total: 491

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| MX 21 | 190       | 56.38%  |
| MX 19 | 87        | 25.82%  |
| MX 20 | 43        | 12.76%  |
| MX 18 | 13        | 3.86%   |
| MX 17 | 2         | 0.59%   |
| MX 23 | 1         | 0.3%    |
| MX 16 | 1         | 0.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MX   | 329       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 4.19.0-6-amd64            | 34        | 9.29%   |
| 5.10.0-21-amd64           | 25        | 6.83%   |
| 6.0.0-6mx-amd64           | 18        | 4.92%   |
| 5.10.0-13-amd64           | 15        | 4.1%    |
| 5.10.0-9-amd64            | 14        | 3.83%   |
| 5.10.0-5mx-amd64          | 13        | 3.55%   |
| 5.10.0-18-amd64           | 13        | 3.55%   |
| 5.8.0-3-amd64             | 9         | 2.46%   |
| 5.10.0-16-amd64           | 9         | 2.46%   |
| 5.14.0-4mx-amd64          | 8         | 2.19%   |
| 5.10.0-19-amd64           | 8         | 2.19%   |
| 5.16.0-5mx-amd64          | 7         | 1.91%   |
| 5.10.0-23-amd64           | 7         | 1.91%   |
| 4.19.0-13-amd64           | 7         | 1.91%   |
| 5.10.0-14-amd64           | 6         | 1.64%   |
| 5.10.0-11-amd64           | 6         | 1.64%   |
| 4.19.0-16-amd64           | 6         | 1.64%   |
| 4.19.0-14-amd64           | 6         | 1.64%   |
| 6.0.0-4mx-amd64           | 5         | 1.37%   |
| 5.6.0-2-amd64             | 5         | 1.37%   |
| 5.18.0-4mx-amd64          | 5         | 1.37%   |
| 5.10.0-22-amd64           | 5         | 1.37%   |
| 5.10.0-20-amd64           | 5         | 1.37%   |
| 4.19.0-5-amd64            | 4         | 1.09%   |
| 4.19.0-17-amd64           | 4         | 1.09%   |
| 4.19.0-11-amd64           | 4         | 1.09%   |
| 5.10.0-8mx-amd64          | 3         | 0.82%   |
| 5.10.0-17-amd64           | 3         | 0.82%   |
| 4.19.0-9-amd64            | 3         | 0.82%   |
| 4.19.0-12-amd64           | 3         | 0.82%   |
| 4.19.0-1-amd64            | 3         | 0.82%   |
| 6.1.0-8mx-ahs-amd64       | 2         | 0.55%   |
| 6.1.0-4mx-amd64           | 2         | 0.55%   |
| 6.0.0-3mx-amd64           | 2         | 0.55%   |
| 6.0.0-10.1-liquorix-amd64 | 2         | 0.55%   |
| 5.8.16-antix.1-amd64-smp  | 2         | 0.55%   |
| 5.6.10-antix.1-amd64-smp  | 2         | 0.55%   |
| 5.4.0-3-amd64             | 2         | 0.55%   |
| 5.19.0-2mx-amd64          | 2         | 0.55%   |
| 5.16.0-6mx-amd64          | 2         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 139       | 39.71%  |
| 4.19.0   | 83        | 23.71%  |
| 6.0.0    | 28        | 8%      |
| 5.16.0   | 11        | 3.14%   |
| 5.8.0    | 9         | 2.57%   |
| 5.14.0   | 8         | 2.29%   |
| 6.1.0    | 7         | 2%      |
| 5.6.0    | 7         | 2%      |
| 5.18.0   | 7         | 2%      |
| 5.4.0    | 6         | 1.71%   |
| 5.19.0   | 5         | 1.43%   |
| 5.17.0   | 4         | 1.14%   |
| 5.8.16   | 2         | 0.57%   |
| 5.6.10   | 2         | 0.57%   |
| 5.3.0    | 2         | 0.57%   |
| 5.2.21   | 2         | 0.57%   |
| 5.15.0   | 2         | 0.57%   |
| 4.9.193  | 2         | 0.57%   |
| 4.15.0   | 2         | 0.57%   |
| 6.2.7    | 1         | 0.29%   |
| 6.2.14   | 1         | 0.29%   |
| 6.1.15   | 1         | 0.29%   |
| 6.1.12   | 1         | 0.29%   |
| 5.9.1    | 1         | 0.29%   |
| 5.7.0    | 1         | 0.29%   |
| 5.5.0    | 1         | 0.29%   |
| 5.3.10   | 1         | 0.29%   |
| 5.2.8    | 1         | 0.29%   |
| 5.2.0    | 1         | 0.29%   |
| 5.13.0   | 1         | 0.29%   |
| 5.11.0   | 1         | 0.29%   |
| 5.10.82  | 1         | 0.29%   |
| 5.10.142 | 1         | 0.29%   |
| 5.10.1   | 1         | 0.29%   |
| 5.1.2    | 1         | 0.29%   |
| 5.0.0    | 1         | 0.29%   |
| 4.9.246  | 1         | 0.29%   |
| 4.19.174 | 1         | 0.29%   |
| 4.18.0   | 1         | 0.29%   |
| 3.16.0   | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 142       | 40.57%  |
| 4.19    | 84        | 24%     |
| 6.0     | 28        | 8%      |
| 5.8     | 11        | 3.14%   |
| 5.16    | 11        | 3.14%   |
| 6.1     | 9         | 2.57%   |
| 5.6     | 9         | 2.57%   |
| 5.14    | 8         | 2.29%   |
| 5.18    | 7         | 2%      |
| 5.4     | 6         | 1.71%   |
| 5.19    | 5         | 1.43%   |
| 5.2     | 4         | 1.14%   |
| 5.17    | 4         | 1.14%   |
| 5.3     | 3         | 0.86%   |
| 4.9     | 3         | 0.86%   |
| 6.2     | 2         | 0.57%   |
| 5.15    | 2         | 0.57%   |
| 4.15    | 2         | 0.57%   |
| 5.9     | 1         | 0.29%   |
| 5.7     | 1         | 0.29%   |
| 5.5     | 1         | 0.29%   |
| 5.13    | 1         | 0.29%   |
| 5.11    | 1         | 0.29%   |
| 5.1     | 1         | 0.29%   |
| 5.0     | 1         | 0.29%   |
| 4.18    | 1         | 0.29%   |
| 3.16    | 1         | 0.29%   |
| Unknown | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 311       | 94.24%  |
| i686   | 19        | 5.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| XFCE             | 239       | 71.13%  |
| KDE5             | 57        | 16.96%  |
| Budgie           | 7         | 2.08%   |
| Unknown          | 7         | 2.08%   |
| i3               | 5         | 1.49%   |
| GNOME            | 4         | 1.19%   |
| X-Cinnamon       | 2         | 0.6%    |
| MATE             | 2         | 0.6%    |
| LXQt             | 2         | 0.6%    |
| lightdm-xsession | 2         | 0.6%    |
| fluxbox          | 2         | 0.6%    |
| Cinnamon         | 2         | 0.6%    |
| Trinity          | 1         | 0.3%    |
| spectrwm         | 1         | 0.3%    |
| LXDE             | 1         | 0.3%    |
| GNOME Flashback  | 1         | 0.3%    |
| GNOME Classic    | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 325       | 98.78%  |
| Tty     | 3         | 0.91%   |
| Wayland | 1         | 0.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 265       | 79.58%  |
| SDDM    | 51        | 15.32%  |
| TDM     | 9         | 2.7%    |
| SLiM    | 7         | 2.1%    |
| Unknown | 1         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 135       | 40.06%  |
| Unknown | 57        | 16.91%  |
| de_DE   | 34        | 10.09%  |
| en_GB   | 20        | 5.93%   |
| it_IT   | 12        | 3.56%   |
| ru_RU   | 11        | 3.26%   |
| fr_FR   | 9         | 2.67%   |
| sk_SK   | 6         | 1.78%   |
| pt_BR   | 5         | 1.48%   |
| pl_PL   | 5         | 1.48%   |
| es_ES   | 4         | 1.19%   |
| en_AU   | 4         | 1.19%   |
| tr_TR   | 3         | 0.89%   |
| de_CH   | 3         | 0.89%   |
| nl_NL   | 2         | 0.59%   |
| fr_BE   | 2         | 0.59%   |
| es_MX   | 2         | 0.59%   |
| es_CO   | 2         | 0.59%   |
| es_AR   | 2         | 0.59%   |
| en_NZ   | 2         | 0.59%   |
| en_IE   | 2         | 0.59%   |
| bg_BG   | 2         | 0.59%   |
| zh_CN   | 1         | 0.3%    |
| uk_UA   | 1         | 0.3%    |
| ro_RO   | 1         | 0.3%    |
| nb_NO   | 1         | 0.3%    |
| id_ID   | 1         | 0.3%    |
| hu_HU   | 1         | 0.3%    |
| fr_CA   | 1         | 0.3%    |
| fi_FI   | 1         | 0.3%    |
| es_VE   | 1         | 0.3%    |
| es_UY   | 1         | 0.3%    |
| es_PE   | 1         | 0.3%    |
| en_CA   | 1         | 0.3%    |
| cs_CZ   | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 200       | 60.79%  |
| BIOS | 129       | 39.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 282       | 84.94%  |
| Overlay | 37        | 11.14%  |
| Btrfs   | 9         | 2.71%   |
| Xfs     | 2         | 0.6%    |
| F2fs    | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 219       | 66.36%  |
| MBR     | 107       | 32.42%  |
| Unknown | 4         | 1.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 268       | 80.48%  |
| Yes       | 65        | 19.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 200       | 60.61%  |
| Yes       | 130       | 39.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo                    | 71        | 21.58%  |
| Hewlett-Packard           | 60        | 18.24%  |
| ASUSTek Computer          | 38        | 11.55%  |
| Dell                      | 36        | 10.94%  |
| Acer                      | 31        | 9.42%   |
| Toshiba                   | 11        | 3.34%   |
| Sony                      | 11        | 3.34%   |
| Apple                     | 11        | 3.34%   |
| MSI                       | 7         | 2.13%   |
| Medion                    | 7         | 2.13%   |
| Samsung Electronics       | 5         | 1.52%   |
| Google                    | 3         | 0.91%   |
| Fujitsu Siemens           | 3         | 0.91%   |
| Alienware                 | 3         | 0.91%   |
| Unknown                   | 3         | 0.91%   |
| TUXEDO                    | 2         | 0.61%   |
| Notebook                  | 2         | 0.61%   |
| Gigabyte Technology       | 2         | 0.61%   |
| Clevo                     | 2         | 0.61%   |
| Chuwi                     | 2         | 0.61%   |
| win element               | 1         | 0.3%    |
| Vulcan Electronics        | 1         | 0.3%    |
| UMAX                      | 1         | 0.3%    |
| SANTECH                   | 1         | 0.3%    |
| RTD Embedded Technologies | 1         | 0.3%    |
| Pixus                     | 1         | 0.3%    |
| Panasonic                 | 1         | 0.3%    |
| Packard Bell              | 1         | 0.3%    |
| Linx                      | 1         | 0.3%    |
| Irbis                     | 1         | 0.3%    |
| Intel                     | 1         | 0.3%    |
| HUAWEI                    | 1         | 0.3%    |
| Framework                 | 1         | 0.3%    |
| F-Plus Mobile             | 1         | 0.3%    |
| eMachines                 | 1         | 0.3%    |
| efirstview                | 1         | 0.3%    |
| Compal                    | 1         | 0.3%    |
| Casper                    | 1         | 0.3%    |
| AMI                       | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 5         | 1.52%   |
| HP Stream Laptop 14-cb0XX           | 2         | 0.61%   |
| HP ProBook 650 G1                   | 2         | 0.61%   |
| HP Pavilion Laptop 15-eh1xxx        | 2         | 0.61%   |
| HP Laptop 17-ak0xx                  | 2         | 0.61%   |
| Chuwi GemiBook Pro                  | 2         | 0.61%   |
| ASUS X200CA                         | 2         | 0.61%   |
| Apple MacBookAir7,2                 | 2         | 0.61%   |
| Acer Nitro AN515-55                 | 2         | 0.61%   |
| win element MoreFine S500+          | 1         | 0.3%    |
| Vulcan Excursion XB                 | 1         | 0.3%    |
| UMAX VisionBook-N12R                | 1         | 0.3%    |
| TUXEDO N7x0WU                       | 1         | 0.3%    |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 1         | 0.3%    |
| Toshiba Satellite P875              | 1         | 0.3%    |
| Toshiba Satellite M70               | 1         | 0.3%    |
| Toshiba Satellite L850-CJK          | 1         | 0.3%    |
| Toshiba Satellite L650              | 1         | 0.3%    |
| Toshiba Satellite C845              | 1         | 0.3%    |
| Toshiba Satellite C70-B             | 1         | 0.3%    |
| Toshiba Satellite C660              | 1         | 0.3%    |
| Toshiba Satellite C50-A-12K         | 1         | 0.3%    |
| Toshiba Satellite A300              | 1         | 0.3%    |
| Toshiba PORTEGE Z30-C               | 1         | 0.3%    |
| Toshiba PORTEGE R705                | 1         | 0.3%    |
| Sony VPCYB3V1E                      | 1         | 0.3%    |
| Sony VPCSB1V9R                      | 1         | 0.3%    |
| Sony VPCF23P1E                      | 1         | 0.3%    |
| Sony VPCF119FX                      | 1         | 0.3%    |
| Sony VPCEH2N1E                      | 1         | 0.3%    |
| Sony VPCEC3S1E                      | 1         | 0.3%    |
| Sony VPCCB32FD                      | 1         | 0.3%    |
| Sony VGN-TZ3RXN_B                   | 1         | 0.3%    |
| Sony VGN-NR310FH                    | 1         | 0.3%    |
| Sony SVT13115FBS                    | 1         | 0.3%    |
| Sony SVE1513Q1ESI                   | 1         | 0.3%    |
| SANTECH X170KM-G                    | 1         | 0.3%    |
| Samsung R780/R778                   | 1         | 0.3%    |
| Samsung NC210/NC110                 | 1         | 0.3%    |
| Samsung 350V5C/351V5C/3540VC/3440VC | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 49        | 14.89%  |
| Acer Aspire          | 19        | 5.78%   |
| Dell Latitude        | 15        | 4.56%   |
| HP Pavilion          | 10        | 3.04%   |
| Dell Inspiron        | 10        | 3.04%   |
| Toshiba Satellite    | 9         | 2.74%   |
| HP ProBook           | 9         | 2.74%   |
| HP EliteBook         | 9         | 2.74%   |
| Lenovo IdeaPad       | 8         | 2.43%   |
| HP Laptop            | 7         | 2.13%   |
| ASUS VivoBook        | 6         | 1.82%   |
| Dell Vostro          | 5         | 1.52%   |
| Unknown              | 5         | 1.52%   |
| HP ZBook             | 4         | 1.22%   |
| ASUS TUF             | 4         | 1.22%   |
| HP Compaq            | 3         | 0.91%   |
| Acer Swift           | 3         | 0.91%   |
| Acer Nitro           | 3         | 0.91%   |
| Acer Extensa         | 3         | 0.91%   |
| Toshiba PORTEGE      | 2         | 0.61%   |
| Lenovo ThinkBook     | 2         | 0.61%   |
| Lenovo B590          | 2         | 0.61%   |
| HP Stream            | 2         | 0.61%   |
| HP 250               | 2         | 0.61%   |
| HP 15                | 2         | 0.61%   |
| Dell Precision       | 2         | 0.61%   |
| Chuwi GemiBook       | 2         | 0.61%   |
| ASUS X200CA          | 2         | 0.61%   |
| ASUS ROG             | 2         | 0.61%   |
| ASUS ASUS            | 2         | 0.61%   |
| Apple MacBookPro11   | 2         | 0.61%   |
| Apple MacBookAir7    | 2         | 0.61%   |
| Alienware m15        | 2         | 0.61%   |
| win element MoreFine | 1         | 0.3%    |
| Vulcan Excursion     | 1         | 0.3%    |
| UMAX VisionBook-N12R | 1         | 0.3%    |
| TUXEDO N7x0WU        | 1         | 0.3%    |
| TUXEDO InfinityBook  | 1         | 0.3%    |
| Sony VPCYB3V1E       | 1         | 0.3%    |
| Sony VPCSB1V9R       | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 36        | 10.94%  |
| 2011    | 32        | 9.73%   |
| 2010    | 28        | 8.51%   |
| 2018    | 25        | 7.6%    |
| 2012    | 25        | 7.6%    |
| 2013    | 24        | 7.29%   |
| 2016    | 23        | 6.99%   |
| 2015    | 20        | 6.08%   |
| 2020    | 18        | 5.47%   |
| 2019    | 18        | 5.47%   |
| 2014    | 16        | 4.86%   |
| 2017    | 14        | 4.26%   |
| 2022    | 12        | 3.65%   |
| 2008    | 11        | 3.34%   |
| 2009    | 9         | 2.74%   |
| 2007    | 8         | 2.43%   |
| 2006    | 5         | 1.52%   |
| 2005    | 3         | 0.91%   |
| 2023    | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 329       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 327       | 99.39%  |
| Enabled  | 2         | 0.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 324       | 98.48%  |
| Yes  | 5         | 1.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 94        | 28.48%  |
| 8.01-16.0   | 63        | 19.09%  |
| 3.01-4.0    | 60        | 18.18%  |
| 16.01-24.0  | 44        | 13.33%  |
| 1.01-2.0    | 29        | 8.79%   |
| 32.01-64.0  | 19        | 5.76%   |
| 2.01-3.0    | 11        | 3.33%   |
| 0.51-1.0    | 5         | 1.52%   |
| 24.01-32.0  | 3         | 0.91%   |
| 64.01-256.0 | 2         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 134       | 38.07%  |
| 2.01-3.0  | 84        | 23.86%  |
| 3.01-4.0  | 54        | 15.34%  |
| 0.51-1.0  | 36        | 10.23%  |
| 4.01-8.0  | 32        | 9.09%   |
| 8.01-16.0 | 8         | 2.27%   |
| 0.01-0.5  | 4         | 1.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 244       | 73.05%  |
| 2      | 68        | 20.36%  |
| 3      | 17        | 5.09%   |
| 0      | 3         | 0.9%    |
| 4      | 2         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 217       | 65.76%  |
| Yes       | 113       | 34.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 275       | 83.59%  |
| No        | 54        | 16.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 319       | 96.67%  |
| No        | 11        | 3.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 247       | 74.85%  |
| No        | 83        | 25.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 67        | 20.24%  |
| Germany     | 39        | 11.78%  |
| Italy       | 21        | 6.34%   |
| UK          | 15        | 4.53%   |
| Canada      | 14        | 4.23%   |
| Russia      | 13        | 3.93%   |
| France      | 11        | 3.32%   |
| India       | 10        | 3.02%   |
| Netherlands | 9         | 2.72%   |
| Poland      | 8         | 2.42%   |
| Brazil      | 8         | 2.42%   |
| Spain       | 7         | 2.11%   |
| Slovakia    | 7         | 2.11%   |
| Australia   | 7         | 2.11%   |
| Austria     | 6         | 1.81%   |
| Romania     | 5         | 1.51%   |
| Ukraine     | 4         | 1.21%   |
| Mexico      | 4         | 1.21%   |
| Czechia     | 4         | 1.21%   |
| Belgium     | 4         | 1.21%   |
| Turkey      | 3         | 0.91%   |
| Thailand    | 3         | 0.91%   |
| Switzerland | 3         | 0.91%   |
| Serbia      | 3         | 0.91%   |
| Portugal    | 3         | 0.91%   |
| New Zealand | 3         | 0.91%   |
| Finland     | 3         | 0.91%   |
| Colombia    | 3         | 0.91%   |
| Vietnam     | 2         | 0.6%    |
| Sweden      | 2         | 0.6%    |
| Norway      | 2         | 0.6%    |
| Indonesia   | 2         | 0.6%    |
| Hungary     | 2         | 0.6%    |
| Greece      | 2         | 0.6%    |
| Egypt       | 2         | 0.6%    |
| China       | 2         | 0.6%    |
| Chile       | 2         | 0.6%    |
| Bulgaria    | 2         | 0.6%    |
| Belarus     | 2         | 0.6%    |
| Bangladesh  | 2         | 0.6%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vienna           | 6         | 1.73%   |
| Bratislava       | 6         | 1.73%   |
| Berlin           | 5         | 1.44%   |
| Rome             | 4         | 1.15%   |
| Moscow           | 4         | 1.15%   |
| Warsaw           | 3         | 0.86%   |
| St Petersburg    | 3         | 0.86%   |
| Munich           | 3         | 0.86%   |
| Montreal         | 3         | 0.86%   |
| Milan            | 3         | 0.86%   |
| Los Angeles      | 3         | 0.86%   |
| Amsterdam        | 3         | 0.86%   |
| Walled Lake      | 2         | 0.58%   |
| Prague           | 2         | 0.58%   |
| Porto            | 2         | 0.58%   |
| Perth            | 2         | 0.58%   |
| Patna            | 2         | 0.58%   |
| Oxford           | 2         | 0.58%   |
| Orange           | 2         | 0.58%   |
| New York         | 2         | 0.58%   |
| Minsk            | 2         | 0.58%   |
| Melbourne        | 2         | 0.58%   |
| Madrid           | 2         | 0.58%   |
| Istanbul         | 2         | 0.58%   |
| Ho Chi Minh City | 2         | 0.58%   |
| Florence         | 2         | 0.58%   |
| Doesburg         | 2         | 0.58%   |
| Dnipro           | 2         | 0.58%   |
| Dhaka            | 2         | 0.58%   |
| Catania          | 2         | 0.58%   |
| Casale Litta     | 2         | 0.58%   |
| Canberra         | 2         | 0.58%   |
| Cambridge        | 2         | 0.58%   |
| Calgary          | 2         | 0.58%   |
| Cairo            | 2         | 0.58%   |
| Buffalo          | 2         | 0.58%   |
| Budapest         | 2         | 0.58%   |
| Bogotá          | 2         | 0.58%   |
| Belgrade         | 2         | 0.58%   |
| Zurich           | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 57        | 74     | 13.44%  |
| WDC                 | 52        | 53     | 12.26%  |
| Seagate             | 35        | 38     | 8.25%   |
| Kingston            | 30        | 32     | 7.08%   |
| Unknown             | 27        | 32     | 6.37%   |
| Toshiba             | 25        | 26     | 5.9%    |
| Crucial             | 24        | 44     | 5.66%   |
| SanDisk             | 20        | 22     | 4.72%   |
| SK hynix            | 18        | 19     | 4.25%   |
| Intel               | 13        | 18     | 3.07%   |
| Hitachi             | 13        | 14     | 3.07%   |
| HGST                | 13        | 18     | 3.07%   |
| Micron Technology   | 8         | 12     | 1.89%   |
| Apple               | 7         | 10     | 1.65%   |
| SPCC                | 5         | 5      | 1.18%   |
| PNY                 | 5         | 5      | 1.18%   |
| LITEON              | 5         | 5      | 1.18%   |
| Transcend           | 4         | 4      | 0.94%   |
| KIOXIA              | 4         | 6      | 0.94%   |
| Unknown             | 4         | 4      | 0.94%   |
| Team                | 3         | 3      | 0.71%   |
| Phison              | 3         | 4      | 0.71%   |
| Netac               | 3         | 3      | 0.71%   |
| Dogfish             | 3         | 3      | 0.71%   |
| Corsair             | 3         | 3      | 0.71%   |
| A-DATA Technology   | 3         | 5      | 0.71%   |
| Patriot             | 2         | 2      | 0.47%   |
| OCZ                 | 2         | 2      | 0.47%   |
| KingSpec            | 2         | 2      | 0.47%   |
| KingDian            | 2         | 2      | 0.47%   |
| Indilinx            | 2         | 4      | 0.47%   |
| Fujitsu             | 2         | 2      | 0.47%   |
| ZTC                 | 1         | 1      | 0.24%   |
| Yeyian              | 1         | 1      | 0.24%   |
| Teclast             | 1         | 1      | 0.24%   |
| SWORDBILL           | 1         | 2      | 0.24%   |
| Smart               | 1         | 1      | 0.24%   |
| SABRENT             | 1         | 1      | 0.24%   |
| RENICE              | 1         | 1      | 0.24%   |
| Phison Electronics  | 1         | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 6         | 1.38%   |
| Samsung SSD 860 EVO 500GB              | 6         | 1.38%   |
| Kingston SA400S37240G 240GB SSD        | 6         | 1.38%   |
| HGST HTS721010A9E630 1TB               | 5         | 1.15%   |
| Seagate ST1000LM048-2E7172 1TB         | 4         | 0.92%   |
| Kingston SV300S37A120G 120GB SSD       | 4         | 0.92%   |
| Kingston SA400S37480G 480GB SSD        | 4         | 0.92%   |
| Kingston SA400S37120G 120GB SSD        | 4         | 0.92%   |
| Crucial CT500MX500SSD1 500GB           | 4         | 0.92%   |
| Crucial CT120BX500SSD1 120GB           | 4         | 0.92%   |
| Unknown                                | 4         | 0.92%   |
| Unknown SD32G  32GB                    | 3         | 0.69%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.69%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 0.69%   |
| Samsung SSD 980 PRO 1TB                | 3         | 0.69%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.69%   |
| Intel SSDPEKNW512G8 512GB              | 3         | 0.69%   |
| HGST HTS541010A9E680 1TB               | 3         | 0.69%   |
| Crucial CT480BX500SSD1 480GB           | 3         | 0.69%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.46%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 2         | 0.46%   |
| WDC WD5000LPCX-24VHAT0 500GB           | 2         | 0.46%   |
| WDC WD3200BEKT-60PVMT0 320GB           | 2         | 0.46%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 2         | 0.46%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.46%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 0.46%   |
| Unknown SDW32G  32GB                   | 2         | 0.46%   |
| Unknown DA4064  64GB                   | 2         | 0.46%   |
| Unknown BJTD4R  32GB                   | 2         | 0.46%   |
| Toshiba MQ01ABD075 752GB               | 2         | 0.46%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 2         | 0.46%   |
| SPCC Solid State Disk 1TB              | 2         | 0.46%   |
| SK hynix HFS128G39TND-N210A 128GB SSD  | 2         | 0.46%   |
| SK hynix HFM512GDJTNI-82A0A 512GB      | 2         | 0.46%   |
| SK hynix HBG4e  32GB                   | 2         | 0.46%   |
| Seagate ST9500325AS 500GB              | 2         | 0.46%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.46%   |
| Seagate ST500LM000-1EJ162 500GB        | 2         | 0.46%   |
| Seagate ST2000LM003 HN-M201RAD 2TB     | 2         | 0.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 35     | 30.17%  |
| Seagate             | 35        | 38     | 30.17%  |
| Toshiba             | 14        | 15     | 12.07%  |
| Hitachi             | 13        | 14     | 11.21%  |
| HGST                | 13        | 18     | 11.21%  |
| Samsung Electronics | 4         | 5      | 3.45%   |
| Fujitsu             | 2         | 2      | 1.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 40     | 16.67%  |
| Kingston            | 22        | 23     | 12.22%  |
| Crucial             | 21        | 40     | 11.67%  |
| SanDisk             | 16        | 18     | 8.89%   |
| WDC                 | 6         | 6      | 3.33%   |
| Apple               | 6         | 9      | 3.33%   |
| SPCC                | 5         | 5      | 2.78%   |
| SK hynix            | 5         | 5      | 2.78%   |
| PNY                 | 5         | 5      | 2.78%   |
| Transcend           | 4         | 4      | 2.22%   |
| Toshiba             | 4         | 4      | 2.22%   |
| Micron Technology   | 4         | 8      | 2.22%   |
| LITEON              | 4         | 4      | 2.22%   |
| Intel               | 4         | 7      | 2.22%   |
| Netac               | 3         | 3      | 1.67%   |
| Dogfish             | 3         | 3      | 1.67%   |
| A-DATA Technology   | 3         | 5      | 1.67%   |
| Team                | 2         | 2      | 1.11%   |
| Patriot             | 2         | 2      | 1.11%   |
| OCZ                 | 2         | 2      | 1.11%   |
| KingSpec            | 2         | 2      | 1.11%   |
| KingDian            | 2         | 2      | 1.11%   |
| Indilinx            | 2         | 4      | 1.11%   |
| Corsair             | 2         | 2      | 1.11%   |
| Unknown             | 2         | 2      | 1.11%   |
| ZTC                 | 1         | 1      | 0.56%   |
| Yeyian              | 1         | 1      | 0.56%   |
| Teclast             | 1         | 1      | 0.56%   |
| SWORDBILL           | 1         | 2      | 0.56%   |
| Smart               | 1         | 1      | 0.56%   |
| SABRENT             | 1         | 1      | 0.56%   |
| RENICE              | 1         | 1      | 0.56%   |
| Phison              | 1         | 1      | 0.56%   |
| LITEONIT            | 1         | 1      | 0.56%   |
| KingFast            | 1         | 1      | 0.56%   |
| Intenso             | 1         | 1      | 0.56%   |
| Hewlett-Packard     | 1         | 1      | 0.56%   |
| GOODRAM             | 1         | 1      | 0.56%   |
| Gigabyte Technology | 1         | 1      | 0.56%   |
| GeIL                | 1         | 1      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 158       | 227    | 40.1%   |
| HDD     | 114       | 127    | 28.93%  |
| NVMe    | 89        | 110    | 22.59%  |
| MMC     | 31        | 37     | 7.87%   |
| Unknown | 2         | 2      | 0.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 235       | 349    | 65.1%   |
| NVMe | 89        | 110    | 24.65%  |
| MMC  | 31        | 37     | 8.59%   |
| SAS  | 6         | 7      | 1.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 199       | 262    | 75.09%  |
| 0.51-1.0   | 58        | 84     | 21.89%  |
| 1.01-2.0   | 5         | 5      | 1.89%   |
| 3.01-4.0   | 1         | 1      | 0.38%   |
| 10.01-20.0 | 1         | 1      | 0.38%   |
| 4.01-10.0  | 1         | 1      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 102       | 29.91%  |
| 251-500        | 71        | 20.82%  |
| 51-100         | 45        | 13.2%   |
| 501-1000       | 44        | 12.9%   |
| 21-50          | 36        | 10.56%  |
| 1-20           | 20        | 5.87%   |
| 1001-2000      | 13        | 3.81%   |
| More than 3000 | 5         | 1.47%   |
| 2001-3000      | 3         | 0.88%   |
| Unknown        | 2         | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 156       | 44.57%  |
| 21-50          | 53        | 15.14%  |
| 51-100         | 49        | 14%     |
| 101-250        | 39        | 11.14%  |
| 251-500        | 27        | 7.71%   |
| 501-1000       | 14        | 4%      |
| 1001-2000      | 6         | 1.71%   |
| More than 3000 | 3         | 0.86%   |
| Unknown        | 2         | 0.57%   |
| 2001-3000      | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 3         | 3      | 5.56%   |
| Seagate ST9500325AS 500GB                    | 2         | 2      | 3.7%    |
| Indilinx IND-S325S120G 120GB SSD             | 2         | 4      | 3.7%    |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 1.85%   |
| WDC WD5000BPVT-60HXZT3 500GB                 | 1         | 1      | 1.85%   |
| WDC WD3200LPVX-22V0TT0 320GB                 | 1         | 1      | 1.85%   |
| WDC WD3200BPVT-80ZEST0 320GB                 | 1         | 1      | 1.85%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 1.85%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 1.85%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1         | 1      | 1.85%   |
| WDC WD1600BEVT-22A23T0 160GB                 | 1         | 1      | 1.85%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD         | 1         | 1      | 1.85%   |
| Toshiba MK7575GSX 752GB                      | 1         | 2      | 1.85%   |
| Toshiba MK5059GSXP 500GB                     | 1         | 1      | 1.85%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 1.85%   |
| SK hynix BC711 HFM512GD3JX013N 512GB         | 1         | 1      | 1.85%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 1.85%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 1.85%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 1.85%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 1.85%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 1.85%   |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 1.85%   |
| Seagate ST320LT007-9ZV142 320GB              | 1         | 1      | 1.85%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 2      | 1.85%   |
| Samsung Electronics HS122JC 120GB            | 1         | 2      | 1.85%   |
| Samsung Electronics HM080HC 80GB             | 1         | 1      | 1.85%   |
| RENICE X2 64GB SSD                           | 1         | 1      | 1.85%   |
| OCZ VERTEX2 64GB SSD                         | 1         | 1      | 1.85%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 1.85%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 1      | 1.85%   |
| Intel SSDPEKKF512G8L 512GB                   | 1         | 2      | 1.85%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 1.85%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 1.85%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 1.85%   |
| Hitachi HTS543216L9SA02 160GB                | 1         | 1      | 1.85%   |
| Hitachi HTS543216L9SA00 160GB                | 1         | 1      | 1.85%   |
| Hitachi HTS542516K9SA00 160GB                | 1         | 1      | 1.85%   |
| Hitachi HTS541080G9SA00 80GB                 | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 22.22%  |
| WDC                 | 8         | 8      | 14.81%  |
| Hitachi             | 7         | 7      | 12.96%  |
| HGST                | 6         | 7      | 11.11%  |
| Toshiba             | 4         | 5      | 7.41%   |
| Samsung Electronics | 4         | 6      | 7.41%   |
| Kingston            | 2         | 2      | 3.7%    |
| Indilinx            | 2         | 4      | 3.7%    |
| Crucial             | 2         | 8      | 3.7%    |
| SK hynix            | 1         | 1      | 1.85%   |
| SanDisk             | 1         | 1      | 1.85%   |
| RENICE              | 1         | 1      | 1.85%   |
| OCZ                 | 1         | 1      | 1.85%   |
| Intel               | 1         | 2      | 1.85%   |
| Fujitsu             | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 30.77%  |
| WDC                 | 8         | 8      | 20.51%  |
| Hitachi             | 7         | 7      | 17.95%  |
| HGST                | 6         | 7      | 15.38%  |
| Toshiba             | 3         | 4      | 7.69%   |
| Samsung Electronics | 2         | 3      | 5.13%   |
| Fujitsu             | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 42     | 72.22%  |
| SSD  | 13        | 22     | 24.07%  |
| NVMe | 2         | 3      | 3.7%    |

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
| Works    | 264       | 388    | 73.33%  |
| Malfunc  | 53        | 67     | 14.72%  |
| Detected | 43        | 48     | 11.94%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 232       | 63.39%  |
| AMD                          | 36        | 9.84%   |
| Samsung Electronics          | 28        | 7.65%   |
| SanDisk                      | 14        | 3.83%   |
| SK hynix                     | 11        | 3.01%   |
| Kingston Technology Company  | 8         | 2.19%   |
| Nvidia                       | 7         | 1.91%   |
| KIOXIA                       | 7         | 1.91%   |
| Phison Electronics           | 5         | 1.37%   |
| Toshiba America Info Systems | 4         | 1.09%   |
| Micron Technology            | 4         | 1.09%   |
| Micron/Crucial Technology    | 3         | 0.82%   |
| Silicon Motion               | 2         | 0.55%   |
| Silicon Image                | 1         | 0.27%   |
| Shenzhen Longsys Electronics | 1         | 0.27%   |
| Marvell Technology Group     | 1         | 0.27%   |
| Lite-On Technology           | 1         | 0.27%   |
| Lenovo                       | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 31        | 7.91%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 31        | 7.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 24        | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 23        | 5.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 15        | 3.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 2.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 2.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 2.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 2.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 2.04%   |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 2.04%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 1.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 1.79%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 6         | 1.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.53%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 1.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 1.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 1.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 1.28%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 5         | 1.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.28%   |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 1.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 1.28%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 1.28%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 1.02%   |
| Phison E12 NVMe Controller                                                       | 4         | 1.02%   |
| Micron NVMe Storage Controller                                                   | 4         | 1.02%   |
| Intel SSD 660P Series                                                            | 4         | 1.02%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 1.02%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.77%   |
| SK hynix BC511                                                                   | 3         | 0.77%   |
| SanDisk NVMe Controller                                                          | 3         | 0.77%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 3         | 0.77%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 3         | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 238       | 62.96%  |
| NVMe | 88        | 23.28%  |
| IDE  | 28        | 7.41%   |
| RAID | 24        | 6.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 275       | 83.59%  |
| AMD    | 54        | 16.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 8         | 2.43%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 7         | 2.13%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 6         | 1.82%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 6         | 1.82%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 6         | 1.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.52%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 5         | 1.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 4         | 1.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 1.22%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 1.22%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 4         | 1.22%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 1.22%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 4         | 1.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.22%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 0.91%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 3         | 0.91%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 3         | 0.91%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 3         | 0.91%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 0.91%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 0.91%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.91%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 0.91%   |
| Intel Core i3-4000M CPU @ 2.40GHz           | 3         | 0.91%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 3         | 0.91%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 0.91%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 3         | 0.91%   |
| Intel 12th Gen Core i7-12700H               | 3         | 0.91%   |
| Intel 12th Gen Core i5-1235U                | 3         | 0.91%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 3         | 0.91%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.61%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 2         | 0.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 0.61%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 0.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 0.61%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 2         | 0.61%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 2         | 0.61%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 2         | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 0.61%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 2         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 73        | 22.19%  |
| Intel Core i7           | 68        | 20.67%  |
| Intel Celeron           | 29        | 8.81%   |
| Other                   | 26        | 7.9%    |
| Intel Core i3           | 25        | 7.6%    |
| Intel Atom              | 18        | 5.47%   |
| Intel Core 2 Duo        | 15        | 4.56%   |
| AMD Ryzen 7             | 13        | 3.95%   |
| AMD Ryzen 5             | 12        | 3.65%   |
| Intel Pentium           | 6         | 1.82%   |
| AMD A6                  | 4         | 1.22%   |
| Intel Pentium Dual-Core | 3         | 0.91%   |
| Intel Core 2            | 3         | 0.91%   |
| AMD Turion 64 X2 Mobile | 3         | 0.91%   |
| AMD Ryzen 3             | 3         | 0.91%   |
| AMD E1                  | 3         | 0.91%   |
| AMD E                   | 3         | 0.91%   |
| AMD A8                  | 3         | 0.91%   |
| Intel Pentium M         | 2         | 0.61%   |
| Intel Genuine           | 2         | 0.61%   |
| AMD Ryzen 9             | 2         | 0.61%   |
| AMD A4                  | 2         | 0.61%   |
| Intel Pentium Silver    | 1         | 0.3%    |
| Intel Pentium Gold      | 1         | 0.3%    |
| Intel Pentium Dual      | 1         | 0.3%    |
| Intel Core Duo          | 1         | 0.3%    |
| Intel Celeron M         | 1         | 0.3%    |
| AMD Sempron             | 1         | 0.3%    |
| AMD Phenom II           | 1         | 0.3%    |
| AMD E2                  | 1         | 0.3%    |
| AMD Athlon 64 X2        | 1         | 0.3%    |
| AMD A12                 | 1         | 0.3%    |
| AMD A10                 | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 180       | 54.71%  |
| 4      | 90        | 27.36%  |
| 6      | 19        | 5.78%   |
| 8      | 17        | 5.17%   |
| 1      | 14        | 4.26%   |
| 10     | 4         | 1.22%   |
| 14     | 3         | 0.91%   |
| 12     | 1         | 0.3%    |
| 5      | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 329       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 225       | 68.39%  |
| 1      | 104       | 31.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 319       | 96.67%  |
| 32-bit         | 11        | 3.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 10.45%  |
| 0x206a7    | 27        | 8.06%   |
| 0x306a9    | 23        | 6.87%   |
| 0x406e3    | 17        | 5.07%   |
| 0x806c1    | 12        | 3.58%   |
| 0x20655    | 11        | 3.28%   |
| 0x306c3    | 10        | 2.99%   |
| 0x1067a    | 10        | 2.99%   |
| 0x0a50000c | 9         | 2.69%   |
| 0x906ea    | 8         | 2.39%   |
| 0x806e9    | 8         | 2.39%   |
| 0x40651    | 8         | 2.39%   |
| 0x306d4    | 8         | 2.39%   |
| 0x30678    | 8         | 2.39%   |
| 0x806ea    | 7         | 2.09%   |
| 0x506e3    | 7         | 2.09%   |
| 0x08608103 | 7         | 2.09%   |
| 0x806ec    | 6         | 1.79%   |
| 0x706a8    | 6         | 1.79%   |
| 0x406c4    | 6         | 1.79%   |
| 0x906a3    | 5         | 1.49%   |
| 0x20652    | 5         | 1.49%   |
| 0xa0652    | 4         | 1.19%   |
| 0x906e9    | 4         | 1.19%   |
| 0x906a4    | 4         | 1.19%   |
| 0x706a1    | 4         | 1.19%   |
| 0x6fd      | 4         | 1.19%   |
| 0x106ca    | 4         | 1.19%   |
| 0x106c2    | 4         | 1.19%   |
| 0x10676    | 3         | 0.9%    |
| 0x08108102 | 3         | 0.9%    |
| 0x03000027 | 3         | 0.9%    |
| 0x906ed    | 2         | 0.6%    |
| 0x806d1    | 2         | 0.6%    |
| 0x706e5    | 2         | 0.6%    |
| 0x6d8      | 2         | 0.6%    |
| 0x506c9    | 2         | 0.6%    |
| 0x30661    | 2         | 0.6%    |
| 0x106e5    | 2         | 0.6%    |
| 0x10661    | 2         | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 40        | 12.16%  |
| SandyBridge      | 32        | 9.73%   |
| IvyBridge        | 27        | 8.21%   |
| Skylake          | 25        | 7.6%    |
| Haswell          | 20        | 6.08%   |
| Westmere         | 17        | 5.17%   |
| Silvermont       | 17        | 5.17%   |
| Penryn           | 15        | 4.56%   |
| Unknown          | 14        | 4.26%   |
| TigerLake        | 13        | 3.95%   |
| Zen 3            | 11        | 3.34%   |
| Goldmont plus    | 10        | 3.04%   |
| Core             | 10        | 3.04%   |
| Bonnell          | 10        | 3.04%   |
| Broadwell        | 8         | 2.43%   |
| IceLake          | 6         | 1.82%   |
| Zen+             | 5         | 1.52%   |
| Puma             | 5         | 1.52%   |
| P6               | 5         | 1.52%   |
| K8 Hammer        | 4         | 1.22%   |
| Excavator        | 4         | 1.22%   |
| CometLake        | 4         | 1.22%   |
| Alderlake Hybrid | 4         | 1.22%   |
| Zen 2            | 3         | 0.91%   |
| Zen              | 3         | 0.91%   |
| K10 Llano        | 3         | 0.91%   |
| Goldmont         | 3         | 0.91%   |
| Bobcat           | 3         | 0.91%   |
| Nehalem          | 2         | 0.61%   |
| Jaguar           | 2         | 0.61%   |
| Tremont          | 1         | 0.3%    |
| Piledriver       | 1         | 0.3%    |
| K8 & K10 hybrid  | 1         | 0.3%    |
| K10              | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 248       | 62.47%  |
| Nvidia | 75        | 18.89%  |
| AMD    | 74        | 18.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 28        | 6.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 26        | 6.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 4.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 3.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 2.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 2.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 2.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 2.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 2.15%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.91%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 1.91%   |
| Intel HD Graphics 620                                                                    | 8         | 1.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.91%   |
| AMD Lucienne                                                                             | 8         | 1.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.91%   |
| Intel HD Graphics 530                                                                    | 7         | 1.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 1.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.2%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 5         | 1.2%    |
| Intel HD Graphics 5500                                                                   | 5         | 1.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.96%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.96%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 0.96%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 0.96%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.96%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 3         | 0.72%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 3         | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.72%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 3         | 0.72%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 0.72%   |
| Intel HD Graphics 630                                                                    | 3         | 0.72%   |
| Intel HD Graphics 500                                                                    | 3         | 0.72%   |
| AMD Renoir                                                                               | 3         | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 185       | 56.23%  |
| Intel + Nvidia | 49        | 14.89%  |
| 1 x AMD        | 48        | 14.59%  |
| 1 x Nvidia     | 20        | 6.08%   |
| Intel + AMD    | 13        | 3.95%   |
| 2 x AMD        | 8         | 2.43%   |
| AMD + Nvidia   | 5         | 1.52%   |
| 2 x Intel      | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 298       | 89.22%  |
| Proprietary | 22        | 6.59%   |
| Unknown     | 14        | 4.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 246       | 73.87%  |
| 0.01-0.5   | 43        | 12.91%  |
| 1.01-2.0   | 17        | 5.11%   |
| 0.51-1.0   | 16        | 4.8%    |
| 3.01-4.0   | 7         | 2.1%    |
| 7.01-8.0   | 3         | 0.9%    |
| 2.01-3.0   | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 67        | 18.93%  |
| Chimei Innolux          | 54        | 15.25%  |
| LG Display              | 42        | 11.86%  |
| Samsung Electronics     | 36        | 10.17%  |
| BOE                     | 36        | 10.17%  |
| Chi Mei Optoelectronics | 16        | 4.52%   |
| Lenovo                  | 14        | 3.95%   |
| PANDA                   | 10        | 2.82%   |
| Apple                   | 10        | 2.82%   |
| Hewlett-Packard         | 9         | 2.54%   |
| Goldstar                | 7         | 1.98%   |
| HannStar                | 6         | 1.69%   |
| InfoVision              | 5         | 1.41%   |
| Dell                    | 5         | 1.41%   |
| Ancor Communications    | 5         | 1.41%   |
| Sharp                   | 4         | 1.13%   |
| LG Philips              | 4         | 1.13%   |
| Sony                    | 3         | 0.85%   |
| CPT                     | 3         | 0.85%   |
| Philips                 | 2         | 0.56%   |
| Vizio                   | 1         | 0.28%   |
| TMX                     | 1         | 0.28%   |
| Sunplus                 | 1         | 0.28%   |
| STA                     | 1         | 0.28%   |
| Panasonic               | 1         | 0.28%   |
| Packard Bell            | 1         | 0.28%   |
| ONN                     | 1         | 0.28%   |
| NEC Computers           | 1         | 0.28%   |
| LTM                     | 1         | 0.28%   |
| KDC                     | 1         | 0.28%   |
| InnoLux Display         | 1         | 0.28%   |
| HKC                     | 1         | 0.28%   |
| Eizo                    | 1         | 0.28%   |
| ASUSTek Computer        | 1         | 0.28%   |
| AOC                     | 1         | 0.28%   |
| Acer                    | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 1.69%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 1.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 1.13%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 3         | 0.85%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 3         | 0.85%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.85%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 3         | 0.85%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 3         | 0.85%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 0.85%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.56%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.56%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 2         | 0.56%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.56%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.56%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.56%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.56%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 2         | 0.56%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 2         | 0.56%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                    | 2         | 0.56%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch           | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO01EE 1600x900 344x193mm 15.5-inch            | 2         | 0.56%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 2         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 136       | 40%     |
| 1366x768 (WXGA)    | 107       | 31.47%  |
| 1600x900 (HD+)     | 18        | 5.29%   |
| 1280x800 (WXGA)    | 17        | 5%      |
| 3840x2160 (4K)     | 12        | 3.53%   |
| 1024x600           | 8         | 2.35%   |
| 1440x900 (WXGA+)   | 6         | 1.76%   |
| 1920x1200 (WUXGA)  | 5         | 1.47%   |
| 2560x1440 (QHD)    | 4         | 1.18%   |
| 1680x1050 (WSXGA+) | 4         | 1.18%   |
| 1280x1024 (SXGA)   | 4         | 1.18%   |
| 2880x1800          | 3         | 0.88%   |
| 2560x1080          | 3         | 0.88%   |
| 2560x1600          | 2         | 0.59%   |
| 2256x1504          | 2         | 0.59%   |
| 2160x1440          | 2         | 0.59%   |
| 1400x1050          | 2         | 0.59%   |
| 3840x2400          | 1         | 0.29%   |
| 3200x2000          | 1         | 0.29%   |
| 3200x1800 (QHD+)   | 1         | 0.29%   |
| 1360x768           | 1         | 0.29%   |
| 1024x768 (XGA)     | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 144       | 40.79%  |
| 13      | 47        | 13.31%  |
| 14      | 39        | 11.05%  |
| 17      | 26        | 7.37%   |
| 24      | 13        | 3.68%   |
| 11      | 13        | 3.68%   |
| 12      | 11        | 3.12%   |
| 10      | 11        | 3.12%   |
| 23      | 9         | 2.55%   |
| 19      | 5         | 1.42%   |
| 27      | 4         | 1.13%   |
| 21      | 4         | 1.13%   |
| 16      | 4         | 1.13%   |
| 34      | 3         | 0.85%   |
| 20      | 3         | 0.85%   |
| Unknown | 3         | 0.85%   |
| 43      | 2         | 0.57%   |
| 40      | 2         | 0.57%   |
| 32      | 2         | 0.57%   |
| 18      | 2         | 0.57%   |
| 84      | 1         | 0.28%   |
| 46      | 1         | 0.28%   |
| 37      | 1         | 0.28%   |
| 36      | 1         | 0.28%   |
| 26      | 1         | 0.28%   |
| 25      | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 204       | 57.95%  |
| 201-300     | 56        | 15.91%  |
| 351-400     | 39        | 11.08%  |
| 501-600     | 27        | 7.67%   |
| 401-500     | 10        | 2.84%   |
| 701-800     | 6         | 1.7%    |
| 801-900     | 3         | 0.85%   |
| Unknown     | 3         | 0.85%   |
| 901-1000    | 2         | 0.57%   |
| 1501-2000   | 1         | 0.28%   |
| 1001-1500   | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 266       | 82.61%  |
| 16/10   | 39        | 12.11%  |
| 3/2     | 6         | 1.86%   |
| 5/4     | 4         | 1.24%   |
| 4/3     | 3         | 0.93%   |
| 21/9    | 3         | 0.93%   |
| Unknown | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 145       | 41.08%  |
| 81-90          | 71        | 20.11%  |
| 121-130        | 25        | 7.08%   |
| 201-250        | 21        | 5.95%   |
| 71-80          | 14        | 3.97%   |
| 51-60          | 13        | 3.68%   |
| 61-70          | 11        | 3.12%   |
| 41-50          | 11        | 3.12%   |
| 151-200        | 9         | 2.55%   |
| 501-1000       | 7         | 1.98%   |
| 251-300        | 6         | 1.7%    |
| 351-500        | 5         | 1.42%   |
| 301-350        | 4         | 1.13%   |
| 111-120        | 3         | 0.85%   |
| Unknown        | 3         | 0.85%   |
| 141-150        | 2         | 0.57%   |
| More than 1000 | 1         | 0.28%   |
| 131-140        | 1         | 0.28%   |
| 91-100         | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 140       | 40.46%  |
| 101-120       | 105       | 30.35%  |
| 51-100        | 69        | 19.94%  |
| 161-240       | 19        | 5.49%   |
| More than 240 | 8         | 2.31%   |
| Unknown       | 3         | 0.87%   |
| 1-50          | 2         | 0.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 270       | 80.84%  |
| 2     | 48        | 14.37%  |
| 0     | 13        | 3.89%   |
| 3     | 3         | 0.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 174       | 32.83%  |
| Realtek Semiconductor             | 161       | 30.38%  |
| Qualcomm Atheros                  | 78        | 14.72%  |
| Broadcom                          | 34        | 6.42%   |
| Broadcom Limited                  | 10        | 1.89%   |
| MediaTek                          | 9         | 1.7%    |
| TP-Link                           | 7         | 1.32%   |
| Marvell Technology Group          | 7         | 1.32%   |
| Ralink                            | 5         | 0.94%   |
| Nvidia                            | 5         | 0.94%   |
| ASIX Electronics                  | 5         | 0.94%   |
| Sierra Wireless                   | 4         | 0.75%   |
| Samsung Electronics               | 4         | 0.75%   |
| Motorola PCS                      | 3         | 0.57%   |
| Huawei Technologies               | 3         | 0.57%   |
| Ericsson Business Mobile Networks | 3         | 0.57%   |
| Attansic Technology               | 3         | 0.57%   |
| Ralink Technology                 | 2         | 0.38%   |
| Qualcomm Atheros Communications   | 2         | 0.38%   |
| Sweex                             | 1         | 0.19%   |
| Qualcomm                          | 1         | 0.19%   |
| OPPO Electronics                  | 1         | 0.19%   |
| NetGear                           | 1         | 0.19%   |
| Lenovo                            | 1         | 0.19%   |
| JMicron Technology                | 1         | 0.19%   |
| Hewlett-Packard                   | 1         | 0.19%   |
| Google                            | 1         | 0.19%   |
| Dell                              | 1         | 0.19%   |
| D-Link                            | 1         | 0.19%   |
| ASUSTek Computer                  | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 98        | 15.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 27        | 4.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 18        | 2.8%    |
| Intel Wireless 8260                                                     | 13        | 2.02%   |
| Intel Wireless 7260                                                     | 12        | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 12        | 1.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 1.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 1.71%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 1.71%   |
| Intel Wireless 8265 / 8275                                              | 10        | 1.55%   |
| Intel Wireless 3165                                                     | 10        | 1.55%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 1.4%    |
| Intel Wireless 7265                                                     | 8         | 1.24%   |
| Intel Ethernet Connection I217-LM                                       | 8         | 1.24%   |
| Intel 82577LM Gigabit Network Connection                                | 8         | 1.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.09%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.93%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.78%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.78%   |
| Intel 82567LM Gigabit Network Connection                                | 5         | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                           | 5         | 0.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 4         | 0.62%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.62%   |
| Intel Ethernet Connection I219-V                                        | 4         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 166       | 48.26%  |
| Qualcomm Atheros                | 59        | 17.15%  |
| Realtek Semiconductor           | 55        | 15.99%  |
| Broadcom                        | 24        | 6.98%   |
| MediaTek                        | 8         | 2.33%   |
| Broadcom Limited                | 8         | 2.33%   |
| TP-Link                         | 6         | 1.74%   |
| Ralink                          | 5         | 1.45%   |
| Sierra Wireless                 | 4         | 1.16%   |
| Ralink Technology               | 2         | 0.58%   |
| Qualcomm Atheros Communications | 2         | 0.58%   |
| Sweex                           | 1         | 0.29%   |
| NetGear                         | 1         | 0.29%   |
| Hewlett-Packard                 | 1         | 0.29%   |
| D-Link                          | 1         | 0.29%   |
| ASUSTek Computer                | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 18        | 5.22%   |
| Intel Wireless 8260                                                     | 13        | 3.77%   |
| Intel Wireless 7260                                                     | 12        | 3.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 3.19%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 3.19%   |
| Intel Wireless 8265 / 8275                                              | 10        | 2.9%    |
| Intel Wireless 3165                                                     | 10        | 2.9%    |
| Intel Wi-Fi 6 AX201                                                     | 10        | 2.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.61%   |
| Intel Wireless 7265                                                     | 8         | 2.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 2.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 2.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2.03%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.74%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 1.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 1.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.16%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 1.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.87%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.87%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.87%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 0.87%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 139       | 48.6%   |
| Intel                    | 70        | 24.48%  |
| Qualcomm Atheros         | 30        | 10.49%  |
| Broadcom                 | 13        | 4.55%   |
| Marvell Technology Group | 7         | 2.45%   |
| Nvidia                   | 5         | 1.75%   |
| ASIX Electronics         | 5         | 1.75%   |
| Samsung Electronics      | 3         | 1.05%   |
| Attansic Technology      | 3         | 1.05%   |
| Motorola PCS             | 2         | 0.7%    |
| Broadcom Limited         | 2         | 0.7%    |
| TP-Link                  | 1         | 0.35%   |
| Qualcomm                 | 1         | 0.35%   |
| OPPO Electronics         | 1         | 0.35%   |
| MediaTek                 | 1         | 0.35%   |
| Lenovo                   | 1         | 0.35%   |
| JMicron Technology       | 1         | 0.35%   |
| Huawei Technologies      | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 98        | 33.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 27        | 9.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 4.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 11        | 3.81%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 2.77%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 2.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.73%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 1.73%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 1.73%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 5         | 1.73%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4         | 1.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.38%   |
| Intel Ethernet Connection I219-V                                               | 4         | 1.38%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.38%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 1.04%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 1.04%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 1.04%   |
| Intel Ethernet Connection (5) I219-LM                                          | 3         | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.04%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 1.04%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 3         | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.69%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.69%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.69%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.69%   |
| Motorola PCS moto g(40) fusion                                                 | 2         | 0.69%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.69%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.69%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.69%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 2         | 0.69%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.69%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.35%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 319       | 52.9%   |
| Ethernet | 274       | 45.44%  |
| Modem    | 8         | 1.33%   |
| Unknown  | 2         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 256       | 76.42%  |
| Ethernet | 78        | 23.28%  |
| Unknown  | 1         | 0.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 252       | 76.36%  |
| 1     | 67        | 20.3%   |
| 0     | 9         | 2.73%   |
| 3     | 2         | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 267       | 80.18%  |
| Yes  | 66        | 19.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 113       | 44.49%  |
| Realtek Semiconductor           | 27        | 10.63%  |
| Qualcomm Atheros Communications | 22        | 8.66%   |
| Broadcom                        | 20        | 7.87%   |
| IMC Networks                    | 12        | 4.72%   |
| Lite-On Technology              | 10        | 3.94%   |
| Cambridge Silicon Radio         | 10        | 3.94%   |
| Apple                           | 10        | 3.94%   |
| Hewlett-Packard                 | 8         | 3.15%   |
| Foxconn / Hon Hai               | 8         | 3.15%   |
| Toshiba                         | 3         | 1.18%   |
| Ralink                          | 3         | 1.18%   |
| Dell                            | 3         | 1.18%   |
| Alps Electric                   | 2         | 0.79%   |
| Realtek                         | 1         | 0.39%   |
| MediaTek                        | 1         | 0.39%   |
| ASUSTek Computer                | 1         | 0.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 53        | 20.87%  |
| Realtek Bluetooth Radio                                                             | 19        | 7.48%   |
| Intel AX201 Bluetooth                                                               | 17        | 6.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 13        | 5.12%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 4.33%   |
| Intel AX200 Bluetooth                                                               | 11        | 4.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 3.94%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.36%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 2.36%   |
| IMC Networks Bluetooth Radio                                                        | 6         | 2.36%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 2.36%   |
| Apple Bluetooth Host Controller                                                     | 6         | 2.36%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.97%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 1.57%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.57%   |
| Intel Bluetooth Device                                                              | 4         | 1.57%   |
| IMC Networks Wireless_Device                                                        | 4         | 1.57%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 1.57%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 4         | 1.57%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.18%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.18%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.18%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.79%   |
| Lite-On Wireless_Device                                                             | 2         | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.79%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.79%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.79%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.79%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.39%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.39%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.39%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.39%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.39%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.39%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.39%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.39%   |
| MediaTek Wireless_Device                                                            | 1         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 262       | 65.99%  |
| AMD                     | 59        | 14.86%  |
| Nvidia                  | 54        | 13.6%   |
| Realtek Semiconductor   | 2         | 0.5%    |
| JMTek                   | 2         | 0.5%    |
| GN Netcom               | 2         | 0.5%    |
| C-Media Electronics     | 2         | 0.5%    |
| VIA Technologies        | 1         | 0.25%   |
| Texas Instruments       | 1         | 0.25%   |
| SteelSeries ApS         | 1         | 0.25%   |
| Plantronics             | 1         | 0.25%   |
| Mark of the Unicorn     | 1         | 0.25%   |
| Logitech                | 1         | 0.25%   |
| Lenovo                  | 1         | 0.25%   |
| Guillemot               | 1         | 0.25%   |
| Generalplus Technology  | 1         | 0.25%   |
| Focusrite-Novation      | 1         | 0.25%   |
| FIFINE 683 Microphone   | 1         | 0.25%   |
| Conexant Systems        | 1         | 0.25%   |
| CMX Systems             | 1         | 0.25%   |
| BEHRINGER International | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 35        | 7.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 33        | 7.01%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 6.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 5.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 20        | 4.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 4.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 15        | 3.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 2.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 2.55%   |
| AMD FCH Azalia Controller                                                                         | 12        | 2.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 2.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 2.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.12%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 1.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 1.7%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.7%    |
| Intel Broadwell-U Audio Controller                                                                | 8         | 1.7%    |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.27%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 1.06%   |
| Nvidia Audio device                                                                               | 5         | 1.06%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 1.06%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.64%   |
| Nvidia MCP89 High Definition Audio                                                                | 3         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.64%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 95        | 23.69%  |
| SK hynix            | 86        | 21.45%  |
| Unknown             | 45        | 11.22%  |
| Micron Technology   | 41        | 10.22%  |
| Kingston            | 35        | 8.73%   |
| Crucial             | 19        | 4.74%   |
| Elpida              | 10        | 2.49%   |
| A-DATA Technology   | 10        | 2.49%   |
| Ramaxel Technology  | 9         | 2.24%   |
| Unknown (ABCD)      | 8         | 2%      |
| Corsair             | 6         | 1.5%    |
| Transcend           | 5         | 1.25%   |
| Smart               | 4         | 1%      |
| Nanya Technology    | 3         | 0.75%   |
| Unknown             | 3         | 0.75%   |
| Teikon              | 2         | 0.5%    |
| Team                | 2         | 0.5%    |
| Patriot             | 2         | 0.5%    |
| G.Skill             | 2         | 0.5%    |
| Wilk                | 1         | 0.25%   |
| Unknown (F301)      | 1         | 0.25%   |
| TRS STAR            | 1         | 0.25%   |
| PNY                 | 1         | 0.25%   |
| Lexar Co Limited    | 1         | 0.25%   |
| Innodisk            | 1         | 0.25%   |
| High Bridge         | 1         | 0.25%   |
| Hewlett-Packard     | 1         | 0.25%   |
| Essencore           | 1         | 0.25%   |
| CSX                 | 1         | 0.25%   |
| Avant               | 1         | 0.25%   |
| ASint Technology    | 1         | 0.25%   |
| Apacer              | 1         | 0.25%   |
| 48spaces            | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 1.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.4%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.4%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 1.16%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 1.16%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.93%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.93%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.93%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.93%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 4         | 0.93%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 4         | 0.93%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 0.93%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 0.7%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 0.7%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 3         | 0.7%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.7%    |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s            | 3         | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.7%    |
| Unknown                                                          | 3         | 0.7%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.47%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.47%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM 1334MT/s                   | 2         | 0.47%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 2         | 0.47%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.47%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.47%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 2         | 0.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 2         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 154       | 46.11%  |
| DDR4    | 121       | 36.23%  |
| DDR2    | 20        | 5.99%   |
| LPDDR4  | 13        | 3.89%   |
| SDRAM   | 7         | 2.1%    |
| DDR     | 7         | 2.1%    |
| LPDDR3  | 6         | 1.8%    |
| DRAM    | 3         | 0.9%    |
| Unknown | 2         | 0.6%    |
| DDR5    | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 311       | 92.84%  |
| Row Of Chips | 15        | 4.48%   |
| Chip         | 4         | 1.19%   |
| DIMM         | 3         | 0.9%    |
| Unknown      | 2         | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 133       | 35.95%  |
| 8192  | 114       | 30.81%  |
| 2048  | 62        | 16.76%  |
| 16384 | 38        | 10.27%  |
| 1024  | 19        | 5.14%   |
| 32768 | 3         | 0.81%   |
| 512   | 1         | 0.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 96        | 26.3%   |
| 3200    | 50        | 13.7%   |
| 2667    | 46        | 12.6%   |
| 1334    | 33        | 9.04%   |
| 2400    | 28        | 7.67%   |
| 1333    | 21        | 5.75%   |
| Unknown | 19        | 5.21%   |
| 2133    | 13        | 3.56%   |
| 667     | 13        | 3.56%   |
| 1067    | 11        | 3.01%   |
| 4199    | 5         | 1.37%   |
| 1867    | 5         | 1.37%   |
| 533     | 5         | 1.37%   |
| 3266    | 4         | 1.1%    |
| 800     | 4         | 1.1%    |
| 4267    | 3         | 0.82%   |
| 8400    | 2         | 0.55%   |
| 975     | 2         | 0.55%   |
| 4800    | 1         | 0.27%   |
| 4266    | 1         | 0.27%   |
| 2933    | 1         | 0.27%   |
| 666     | 1         | 0.27%   |
| 166     | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Canon               | 1         | 20%     |
| Brother Industries  | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 20%     |
| HP LaserJet P2055 series           | 1         | 20%     |
| HP LaserJet 1022                   | 1         | 20%     |
| Canon LiDE 400                     | 1         | 20%     |
| Brother DCP-L2540DW                | 1         | 20%     |

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
| Chicony Electronics                    | 69        | 25%     |
| Realtek Semiconductor                  | 23        | 8.33%   |
| IMC Networks                           | 21        | 7.61%   |
| Microdia                               | 20        | 7.25%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 6.16%   |
| Quanta                                 | 15        | 5.43%   |
| Acer                                   | 15        | 5.43%   |
| Sunplus Innovation Technology          | 14        | 5.07%   |
| Suyin                                  | 11        | 3.99%   |
| Bison Electronics                      | 11        | 3.99%   |
| Lite-On Technology                     | 9         | 3.26%   |
| Lenovo                                 | 8         | 2.9%    |
| Apple                                  | 7         | 2.54%   |
| Luxvisions Innotech Limited            | 6         | 2.17%   |
| Ricoh                                  | 5         | 1.81%   |
| Z-Star Microelectronics                | 3         | 1.09%   |
| Syntek                                 | 3         | 1.09%   |
| Silicon Motion                         | 3         | 1.09%   |
| Alcor Micro                            | 3         | 1.09%   |
| Logitech                               | 2         | 0.72%   |
| Y Media                                | 1         | 0.36%   |
| Xiongmai                               | 1         | 0.36%   |
| WaveRider Communications               | 1         | 0.36%   |
| Samsung Electronics                    | 1         | 0.36%   |
| Primax Electronics                     | 1         | 0.36%   |
| Novatek Microelectronics               | 1         | 0.36%   |
| Importek                               | 1         | 0.36%   |
| icSpring                               | 1         | 0.36%   |
| Hewlett-Packard                        | 1         | 0.36%   |
| Goodong Industry                       | 1         | 0.36%   |
| Cubeternet                             | 1         | 0.36%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 17        | 6.16%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 8         | 2.9%    |
| Microdia Integrated_Webcam_HD                               | 6         | 2.17%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 1.81%   |
| Realtek Integrated_Webcam_HD                                | 5         | 1.81%   |
| Lite-On Integrated Camera                                   | 5         | 1.81%   |
| Quanta HD User Facing                                       | 4         | 1.45%   |
| Lenovo Integrated Webcam [R5U877]                           | 4         | 1.45%   |
| Chicony USB 2.0 Camera                                      | 4         | 1.45%   |
| Chicony TOSHIBA Web Camera - HD                             | 4         | 1.45%   |
| Chicony HP TrueVision HD Camera                             | 4         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 4         | 1.45%   |
| Syntek EasyCamera                                           | 3         | 1.09%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 3         | 1.09%   |
| Sunplus ASUS Webcam                                         | 3         | 1.09%   |
| Ricoh USB2.0 Camera                                         | 3         | 1.09%   |
| Realtek USB2.0 HD UVC WebCam                                | 3         | 1.09%   |
| Realtek USB Camera                                          | 3         | 1.09%   |
| Quanta HP TrueVision HD Camera                              | 3         | 1.09%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera        | 3         | 1.09%   |
| Lite-On HP HD Camera                                        | 3         | 1.09%   |
| Lenovo Integrated Webcam                                    | 3         | 1.09%   |
| IMC Networks Integrated Camera                              | 3         | 1.09%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 1.09%   |
| Chicony HD WebCam                                           | 3         | 1.09%   |
| Chicony HD User Facing                                      | 3         | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 3         | 1.09%   |
| Bison Integrated Camera                                     | 3         | 1.09%   |
| Apple Built-in iSight                                       | 3         | 1.09%   |
| Alcor Micro USB 2.0 Camera                                  | 3         | 1.09%   |
| Acer HD Webcam                                              | 3         | 1.09%   |
| Acer BisonCam,NB Pro                                        | 3         | 1.09%   |
| Acer BisonCam, NB Pro                                       | 3         | 1.09%   |
| Suyin Acer CrystalEye Webcam                                | 2         | 0.72%   |
| Sunplus HD WebCam                                           | 2         | 0.72%   |
| Realtek Integrated Webcam HD                                | 2         | 0.72%   |
| Quanta VGA WebCam                                           | 2         | 0.72%   |
| Quanta HP Wide Vision HD Camera                             | 2         | 0.72%   |
| Microdia Webcam Vitade AF                                   | 2         | 0.72%   |
| Microdia USB 2.0 Camera                                     | 2         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 20        | 32.79%  |
| Synaptics                          | 10        | 16.39%  |
| Upek                               | 8         | 13.11%  |
| Shenzhen Goodix Technology         | 7         | 11.48%  |
| AuthenTec                          | 7         | 11.48%  |
| Elan Microelectronics              | 4         | 6.56%   |
| LighTuning Technology              | 2         | 3.28%   |
| STMicroelectronics                 | 1         | 1.64%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.64%   |
| Focal-systems.Corp                 | 1         | 1.64%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 6         | 9.84%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 8.2%    |
| Shenzhen Goodix  FingerPrint Device                             | 5         | 8.2%    |
| Validity Sensors VFS495 Fingerprint Reader                      | 4         | 6.56%   |
| AuthenTec AES2810                                               | 4         | 6.56%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 4.92%   |
| Validity Sensors Synaptics WBDI                                 | 3         | 4.92%   |
| Upek TCS5B Fingerprint sensor                                   | 2         | 3.28%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 2         | 3.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 3.28%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 3.28%   |
| Elan ELAN:Fingerprint                                           | 2         | 3.28%   |
| Elan ELAN:ARM-M4                                                | 2         | 3.28%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 2         | 3.28%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 1.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.64%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 1.64%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 1.64%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.64%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.64%   |
| Synaptics UWP WBDI                                              | 1         | 1.64%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 1         | 1.64%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 1.64%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.64%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 1.64%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.64%   |
| LighTuning Fingerprint Reader                                   | 1         | 1.64%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 1.64%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 1.64%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 1.64%   |
| Unknown                                                         | 1         | 1.64%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 9         | 37.5%   |
| Alcor Micro           | 9         | 37.5%   |
| Lenovo                | 3         | 12.5%   |
| Advanced Card Systems | 2         | 8.33%   |
| O2 Micro              | 1         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 37.5%   |
| Broadcom 5880                                                                | 5         | 20.83%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 8.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.17%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.17%   |
| Broadcom 58200                                                               | 1         | 4.17%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 4.17%   |
| Advanced Card Systems ACR122U                                                | 1         | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 197       | 58.46%  |
| 1     | 108       | 32.05%  |
| 2     | 30        | 8.9%    |
| 3     | 2         | 0.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 65        | 38.46%  |
| Fingerprint reader       | 61        | 36.09%  |
| Chipcard                 | 21        | 12.43%  |
| Net/wireless             | 5         | 2.96%   |
| Multimedia controller    | 5         | 2.96%   |
| Storage                  | 3         | 1.78%   |
| Camera                   | 3         | 1.78%   |
| Communication controller | 2         | 1.18%   |
| Bluetooth                | 2         | 1.18%   |
| Net/ethernet             | 1         | 0.59%   |
| Flash memory             | 1         | 0.59%   |

