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

Total: 269

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.10.0-21-amd64            | 22        | 11.96%  |
| 5.10.0-13-amd64            | 15        | 8.15%   |
| 5.10.0-9-amd64             | 14        | 7.61%   |
| 6.0.0-6mx-amd64            | 12        | 6.52%   |
| 5.10.0-18-amd64            | 12        | 6.52%   |
| 5.10.0-16-amd64            | 9         | 4.89%   |
| 5.14.0-4mx-amd64           | 8         | 4.35%   |
| 5.10.0-19-amd64            | 8         | 4.35%   |
| 5.16.0-5mx-amd64           | 7         | 3.8%    |
| 5.10.0-14-amd64            | 6         | 3.26%   |
| 5.10.0-11-amd64            | 6         | 3.26%   |
| 6.0.0-4mx-amd64            | 5         | 2.72%   |
| 5.18.0-4mx-amd64           | 5         | 2.72%   |
| 5.10.0-20-amd64            | 4         | 2.17%   |
| 5.10.0-17-amd64            | 3         | 1.63%   |
| 6.1.0-4mx-amd64            | 2         | 1.09%   |
| 6.0.0-3mx-amd64            | 2         | 1.09%   |
| 5.19.0-2mx-amd64           | 2         | 1.09%   |
| 5.16.0-6mx-amd64           | 2         | 1.09%   |
| 5.10.0-8-amd64             | 2         | 1.09%   |
| 5.10.0-15-amd64            | 2         | 1.09%   |
| 5.10.0-13-686-pae          | 2         | 1.09%   |
| 5.10.0-11-686-pae          | 2         | 1.09%   |
| 5.10.0-10-amd64            | 2         | 1.09%   |
| 6.2.7-x64v4-xanmod1        | 1         | 0.54%   |
| 6.1.15-2-liquorix-amd64    | 1         | 0.54%   |
| 6.1.12-3-liquorix-amd64    | 1         | 0.54%   |
| 6.1.0-8mx-ahs-amd64        | 1         | 0.54%   |
| 6.1.0-7mx-ahs-amd64        | 1         | 0.54%   |
| 6.1.0-2mx-amd64            | 1         | 0.54%   |
| 6.0.0-11.2-liquorix-amd64  | 1         | 0.54%   |
| 6.0.0-10.1-liquorix-amd64  | 1         | 0.54%   |
| 5.19.0-2mx-rt-amd64        | 1         | 0.54%   |
| 5.19.0-12.1-liquorix-amd64 | 1         | 0.54%   |
| 5.18.0-3-amd64             | 1         | 0.54%   |
| 5.18.0-0.deb11.4-amd64     | 1         | 0.54%   |
| 5.17.0-5.2-liquorix-amd64  | 1         | 0.54%   |
| 5.17.0-3mx-amd64           | 1         | 0.54%   |
| 5.17.0-2mx-amd64           | 1         | 0.54%   |
| 5.17.0-1-amd64             | 1         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 107       | 61.14%  |
| 6.0.0    | 21        | 12%     |
| 5.16.0   | 11        | 6.29%   |
| 5.14.0   | 8         | 4.57%   |
| 5.18.0   | 7         | 4%      |
| 6.1.0    | 5         | 2.86%   |
| 5.19.0   | 4         | 2.29%   |
| 5.17.0   | 4         | 2.29%   |
| 6.2.7    | 1         | 0.57%   |
| 6.1.15   | 1         | 0.57%   |
| 6.1.12   | 1         | 0.57%   |
| 5.15.0   | 1         | 0.57%   |
| 5.10.82  | 1         | 0.57%   |
| 5.10.142 | 1         | 0.57%   |
| 4.19.0   | 1         | 0.57%   |
| Unknown  | 1         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 109       | 62.29%  |
| 6.0     | 21        | 12%     |
| 5.16    | 11        | 6.29%   |
| 5.14    | 8         | 4.57%   |
| 6.1     | 7         | 4%      |
| 5.18    | 7         | 4%      |
| 5.19    | 4         | 2.29%   |
| 5.17    | 4         | 2.29%   |
| 6.2     | 1         | 0.57%   |
| 5.15    | 1         | 0.57%   |
| 4.19    | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 156       | 95.12%  |
| i686   | 8         | 4.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| XFCE             | 117       | 69.64%  |
| KDE5             | 36        | 21.43%  |
| GNOME            | 4         | 2.38%   |
| Budgie           | 3         | 1.79%   |
| Unknown          | 2         | 1.19%   |
| X-Cinnamon       | 1         | 0.6%    |
| LXQt             | 1         | 0.6%    |
| lightdm-xsession | 1         | 0.6%    |
| i3               | 1         | 0.6%    |
| GNOME Classic    | 1         | 0.6%    |
| fluxbox          | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 161       | 98.17%  |
| Tty     | 2         | 1.22%   |
| Wayland | 1         | 0.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 129       | 77.71%  |
| SDDM    | 34        | 20.48%  |
| SLiM    | 2         | 1.2%    |
| Unknown | 1         | 0.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 79        | 47.59%  |
| de_DE   | 23        | 13.86%  |
| en_GB   | 11        | 6.63%   |
| it_IT   | 8         | 4.82%   |
| fr_FR   | 6         | 3.61%   |
| ru_RU   | 5         | 3.01%   |
| Unknown | 4         | 2.41%   |
| en_AU   | 3         | 1.81%   |
| de_CH   | 3         | 1.81%   |
| pt_BR   | 2         | 1.2%    |
| pl_PL   | 2         | 1.2%    |
| es_ES   | 2         | 1.2%    |
| en_NZ   | 2         | 1.2%    |
| bg_BG   | 2         | 1.2%    |
| tr_TR   | 1         | 0.6%    |
| sk_SK   | 1         | 0.6%    |
| nl_NL   | 1         | 0.6%    |
| nb_NO   | 1         | 0.6%    |
| id_ID   | 1         | 0.6%    |
| hu_HU   | 1         | 0.6%    |
| fr_CA   | 1         | 0.6%    |
| fr_BE   | 1         | 0.6%    |
| fi_FI   | 1         | 0.6%    |
| es_UY   | 1         | 0.6%    |
| es_PE   | 1         | 0.6%    |
| es_CO   | 1         | 0.6%    |
| es_AR   | 1         | 0.6%    |
| en_CA   | 1         | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 121       | 73.78%  |
| BIOS | 43        | 26.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 138       | 83.13%  |
| Overlay | 20        | 12.05%  |
| Btrfs   | 6         | 3.61%   |
| Xfs     | 1         | 0.6%    |
| F2fs    | 1         | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 123       | 75%     |
| MBR     | 40        | 24.39%  |
| Unknown | 1         | 0.61%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 125       | 75.3%   |
| Yes       | 41        | 24.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 96        | 58.18%  |
| Yes       | 69        | 41.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo                    | 32        | 19.51%  |
| Hewlett-Packard           | 29        | 17.68%  |
| ASUSTek Computer          | 18        | 10.98%  |
| Dell                      | 17        | 10.37%  |
| Acer                      | 12        | 7.32%   |
| Apple                     | 9         | 5.49%   |
| Sony                      | 8         | 4.88%   |
| Toshiba                   | 4         | 2.44%   |
| MSI                       | 4         | 2.44%   |
| Medion                    | 4         | 2.44%   |
| Samsung Electronics       | 3         | 1.83%   |
| Alienware                 | 3         | 1.83%   |
| TUXEDO                    | 2         | 1.22%   |
| Gigabyte Technology       | 2         | 1.22%   |
| Fujitsu Siemens           | 2         | 1.22%   |
| Chuwi                     | 2         | 1.22%   |
| win element               | 1         | 0.61%   |
| Vulcan Electronics        | 1         | 0.61%   |
| SANTECH                   | 1         | 0.61%   |
| RTD Embedded Technologies | 1         | 0.61%   |
| Notebook                  | 1         | 0.61%   |
| Linx                      | 1         | 0.61%   |
| Google                    | 1         | 0.61%   |
| Framework                 | 1         | 0.61%   |
| F-Plus Mobile             | 1         | 0.61%   |
| efirstview                | 1         | 0.61%   |
| Compal                    | 1         | 0.61%   |
| AMI                       | 1         | 0.61%   |
| Unknown                   | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Laptop 17-ak0xx                  | 2         | 1.22%   |
| Chuwi GemiBook Pro                  | 2         | 1.22%   |
| Apple MacBookAir7,2                 | 2         | 1.22%   |
| Acer Nitro AN515-55                 | 2         | 1.22%   |
| Unknown                             | 2         | 1.22%   |
| win element MoreFine S500+          | 1         | 0.61%   |
| Vulcan Excursion XB                 | 1         | 0.61%   |
| TUXEDO N7x0WU                       | 1         | 0.61%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 1         | 0.61%   |
| Toshiba Satellite M70               | 1         | 0.61%   |
| Toshiba Satellite L650              | 1         | 0.61%   |
| Toshiba Satellite C845              | 1         | 0.61%   |
| Toshiba PORTEGE Z30-C               | 1         | 0.61%   |
| Sony VPCYB3V1E                      | 1         | 0.61%   |
| Sony VPCSB1V9R                      | 1         | 0.61%   |
| Sony VPCF119FX                      | 1         | 0.61%   |
| Sony VPCEH2N1E                      | 1         | 0.61%   |
| Sony VPCEC3S1E                      | 1         | 0.61%   |
| Sony VPCCB32FD                      | 1         | 0.61%   |
| Sony VGN-TZ3RXN_B                   | 1         | 0.61%   |
| Sony SVE1513Q1ESI                   | 1         | 0.61%   |
| SANTECH X170KM-G                    | 1         | 0.61%   |
| Samsung NC210/NC110                 | 1         | 0.61%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 1         | 0.61%   |
| Samsung 340XAA/350XAA/550XAA        | 1         | 0.61%   |
| RTD Embedded CMA34CR                | 1         | 0.61%   |
| Notebook PD5x_7xPNP_PNN_PNT         | 1         | 0.61%   |
| MSI Modern 14 B11MOL                | 1         | 0.61%   |
| MSI GV62 8RD                        | 1         | 0.61%   |
| MSI GF63 Thin 9SC                   | 1         | 0.61%   |
| MSI Alpha 15 B5EEK                  | 1         | 0.61%   |
| Medion P6634                        | 1         | 0.61%   |
| Medion E7424 MD60750                | 1         | 0.61%   |
| Medion E14304                       | 1         | 0.61%   |
| Medion E1239T MD60139               | 1         | 0.61%   |
| Linx LINX1010B                      | 1         | 0.61%   |
| Lenovo V17 G3 IAP 82U1              | 1         | 0.61%   |
| Lenovo V15-IGL 82C3                 | 1         | 0.61%   |
| Lenovo ThinkPad X220 4290WC7        | 1         | 0.61%   |
| Lenovo ThinkPad X200s 74695XG       | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 19        | 11.59%  |
| HP EliteBook         | 6         | 3.66%   |
| Acer Aspire          | 6         | 3.66%   |
| HP ProBook           | 5         | 3.05%   |
| Dell Latitude        | 5         | 3.05%   |
| Dell Inspiron        | 5         | 3.05%   |
| Lenovo IdeaPad       | 4         | 2.44%   |
| HP Laptop            | 4         | 2.44%   |
| Toshiba Satellite    | 3         | 1.83%   |
| Dell Vostro          | 3         | 1.83%   |
| Acer Nitro           | 3         | 1.83%   |
| Lenovo ThinkBook     | 2         | 1.22%   |
| HP ZBook             | 2         | 1.22%   |
| HP Pavilion          | 2         | 1.22%   |
| HP Compaq            | 2         | 1.22%   |
| Dell Precision       | 2         | 1.22%   |
| Chuwi GemiBook       | 2         | 1.22%   |
| ASUS VivoBook        | 2         | 1.22%   |
| ASUS TUF             | 2         | 1.22%   |
| ASUS ROG             | 2         | 1.22%   |
| ASUS ASUS            | 2         | 1.22%   |
| Apple MacBookPro11   | 2         | 1.22%   |
| Apple MacBookAir7    | 2         | 1.22%   |
| Alienware m15        | 2         | 1.22%   |
| Acer Swift           | 2         | 1.22%   |
| Unknown              | 2         | 1.22%   |
| win element MoreFine | 1         | 0.61%   |
| Vulcan Excursion     | 1         | 0.61%   |
| TUXEDO N7x0WU        | 1         | 0.61%   |
| TUXEDO InfinityBook  | 1         | 0.61%   |
| Toshiba PORTEGE      | 1         | 0.61%   |
| Sony VPCYB3V1E       | 1         | 0.61%   |
| Sony VPCSB1V9R       | 1         | 0.61%   |
| Sony VPCF119FX       | 1         | 0.61%   |
| Sony VPCEH2N1E       | 1         | 0.61%   |
| Sony VPCEC3S1E       | 1         | 0.61%   |
| Sony VPCCB32FD       | 1         | 0.61%   |
| Sony VGN-TZ3RXN      | 1         | 0.61%   |
| Sony SVE1513Q1ESI    | 1         | 0.61%   |
| SANTECH X170KM-G     | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 29        | 17.68%  |
| 2015    | 15        | 9.15%   |
| 2011    | 14        | 8.54%   |
| 2016    | 12        | 7.32%   |
| 2010    | 12        | 7.32%   |
| 2020    | 10        | 6.1%    |
| 2019    | 10        | 6.1%    |
| 2018    | 10        | 6.1%    |
| 2013    | 9         | 5.49%   |
| 2012    | 9         | 5.49%   |
| 2022    | 8         | 4.88%   |
| 2017    | 6         | 3.66%   |
| 2014    | 4         | 2.44%   |
| 2008    | 4         | 2.44%   |
| 2009    | 3         | 1.83%   |
| 2007    | 3         | 1.83%   |
| 2006    | 3         | 1.83%   |
| 2005    | 2         | 1.22%   |
| Unknown | 1         | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 164       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 163       | 99.39%  |
| Enabled  | 1         | 0.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 163       | 99.39%  |
| Yes  | 1         | 0.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 52        | 31.71%  |
| 16.01-24.0  | 27        | 16.46%  |
| 8.01-16.0   | 27        | 16.46%  |
| 3.01-4.0    | 23        | 14.02%  |
| 32.01-64.0  | 13        | 7.93%   |
| 1.01-2.0    | 10        | 6.1%    |
| 2.01-3.0    | 6         | 3.66%   |
| 24.01-32.0  | 2         | 1.22%   |
| 64.01-256.0 | 2         | 1.22%   |
| 0.51-1.0    | 2         | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 55        | 31.25%  |
| 2.01-3.0  | 50        | 28.41%  |
| 3.01-4.0  | 33        | 18.75%  |
| 4.01-8.0  | 22        | 12.5%   |
| 0.51-1.0  | 11        | 6.25%   |
| 8.01-16.0 | 3         | 1.7%    |
| 0.01-0.5  | 2         | 1.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 113       | 67.66%  |
| 2      | 39        | 23.35%  |
| 3      | 12        | 7.19%   |
| 0      | 2         | 1.2%    |
| 4      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 68.29%  |
| Yes       | 52        | 31.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 79.88%  |
| No        | 33        | 20.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 96.36%  |
| No        | 6         | 3.64%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 79.27%  |
| No        | 34        | 20.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 35        | 21.08%  |
| Germany     | 24        | 14.46%  |
| Italy       | 16        | 9.64%   |
| Canada      | 9         | 5.42%   |
| Russia      | 6         | 3.61%   |
| France      | 6         | 3.61%   |
| India       | 5         | 3.01%   |
| UK          | 4         | 2.41%   |
| Poland      | 4         | 2.41%   |
| Netherlands | 4         | 2.41%   |
| Brazil      | 4         | 2.41%   |
| Australia   | 4         | 2.41%   |
| Switzerland | 3         | 1.81%   |
| Serbia      | 3         | 1.81%   |
| New Zealand | 3         | 1.81%   |
| Belgium     | 3         | 1.81%   |
| Spain       | 2         | 1.2%    |
| Romania     | 2         | 1.2%    |
| Egypt       | 2         | 1.2%    |
| Bulgaria    | 2         | 1.2%    |
| Bangladesh  | 2         | 1.2%    |
| Austria     | 2         | 1.2%    |
| Vietnam     | 1         | 0.6%    |
| Uruguay     | 1         | 0.6%    |
| Turkey      | 1         | 0.6%    |
| Tunisia     | 1         | 0.6%    |
| Sweden      | 1         | 0.6%    |
| Slovakia    | 1         | 0.6%    |
| Peru        | 1         | 0.6%    |
| Norway      | 1         | 0.6%    |
| Malaysia    | 1         | 0.6%    |
| Ireland     | 1         | 0.6%    |
| Indonesia   | 1         | 0.6%    |
| Hungary     | 1         | 0.6%    |
| Greece      | 1         | 0.6%    |
| Ghana       | 1         | 0.6%    |
| Finland     | 1         | 0.6%    |
| Czechia     | 1         | 0.6%    |
| Croatia     | 1         | 0.6%    |
| Colombia    | 1         | 0.6%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Rome           | 3         | 1.72%   |
| Milan          | 3         | 1.72%   |
| Warsaw         | 2         | 1.15%   |
| Walled Lake    | 2         | 1.15%   |
| Vienna         | 2         | 1.15%   |
| St Petersburg  | 2         | 1.15%   |
| Orange         | 2         | 1.15%   |
| New York       | 2         | 1.15%   |
| Moscow         | 2         | 1.15%   |
| Montreal       | 2         | 1.15%   |
| Florence       | 2         | 1.15%   |
| Doesburg       | 2         | 1.15%   |
| Dhaka          | 2         | 1.15%   |
| Delhi          | 2         | 1.15%   |
| Casale Litta   | 2         | 1.15%   |
| Canberra       | 2         | 1.15%   |
| Cambridge      | 2         | 1.15%   |
| Cairo          | 2         | 1.15%   |
| Berlin         | 2         | 1.15%   |
| Belgrade       | 2         | 1.15%   |
| Amsterdam      | 2         | 1.15%   |
| Zurich         | 1         | 0.57%   |
| Zeven          | 1         | 0.57%   |
| Yekaterinburg  | 1         | 0.57%   |
| Wermelskirchen | 1         | 0.57%   |
| Waycross       | 1         | 0.57%   |
| Vasco da Gama  | 1         | 0.57%   |
| Vancouver      | 1         | 0.57%   |
| Uelzen         | 1         | 0.57%   |
| Ubstadt-Weiher | 1         | 0.57%   |
| Tunis          | 1         | 0.57%   |
| Tulsa          | 1         | 0.57%   |
| Tucson         | 1         | 0.57%   |
| Trausse        | 1         | 0.57%   |
| Toulouse       | 1         | 0.57%   |
| Thessaloniki   | 1         | 0.57%   |
| The Dalles     | 1         | 0.57%   |
| Temuco         | 1         | 0.57%   |
| Taggia         | 1         | 0.57%   |
| Tacoma         | 1         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 42     | 14.86%  |
| WDC                 | 26        | 26     | 11.71%  |
| Seagate             | 19        | 21     | 8.56%   |
| Kingston            | 16        | 18     | 7.21%   |
| Unknown             | 15        | 17     | 6.76%   |
| Crucial             | 14        | 30     | 6.31%   |
| SK hynix            | 12        | 13     | 5.41%   |
| Toshiba             | 11        | 11     | 4.95%   |
| Intel               | 7         | 9      | 3.15%   |
| Apple               | 6         | 9      | 2.7%    |
| LITEON              | 5         | 5      | 2.25%   |
| Hitachi             | 5         | 6      | 2.25%   |
| SPCC                | 4         | 4      | 1.8%    |
| SanDisk             | 4         | 5      | 1.8%    |
| Micron Technology   | 4         | 4      | 1.8%    |
| Transcend           | 3         | 3      | 1.35%   |
| PNY                 | 3         | 3      | 1.35%   |
| Netac               | 3         | 3      | 1.35%   |
| KIOXIA              | 3         | 5      | 1.35%   |
| HGST                | 3         | 3      | 1.35%   |
| Dogfish             | 3         | 3      | 1.35%   |
| Unknown             | 3         | 3      | 1.35%   |
| Phison              | 2         | 3      | 0.9%    |
| Corsair             | 2         | 2      | 0.9%    |
| Team                | 1         | 1      | 0.45%   |
| SWORDBILL           | 1         | 2      | 0.45%   |
| SABRENT             | 1         | 1      | 0.45%   |
| RENICE              | 1         | 1      | 0.45%   |
| Patriot             | 1         | 1      | 0.45%   |
| OCZ                 | 1         | 1      | 0.45%   |
| Indilinx            | 1         | 1      | 0.45%   |
| Hewlett-Packard     | 1         | 1      | 0.45%   |
| Gigabyte Technology | 1         | 1      | 0.45%   |
| GeIL                | 1         | 1      | 0.45%   |
| G-TECH              | 1         | 1      | 0.45%   |
| Fujitsu             | 1         | 1      | 0.45%   |
| FORESEE             | 1         | 1      | 0.45%   |
| CT500MX5            | 1         | 1      | 0.45%   |
| Apacer              | 1         | 1      | 0.45%   |
| AGI                 | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 4         | 1.75%   |
| Unknown SD32G  32GB                    | 3         | 1.31%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 1.31%   |
| Samsung SSD 980 PRO 1TB                | 3         | 1.31%   |
| Kingston SA400S37480G 480GB SSD        | 3         | 1.31%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 1.31%   |
| Crucial CT480BX500SSD1 480GB           | 3         | 1.31%   |
| Crucial CT120BX500SSD1 120GB           | 3         | 1.31%   |
| Unknown                                | 3         | 1.31%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.87%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 0.87%   |
| Unknown DA4064  64GB                   | 2         | 0.87%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 2         | 0.87%   |
| SPCC Solid State Disk 1TB              | 2         | 0.87%   |
| SK hynix HFS128G39TND-N210A 128GB SSD  | 2         | 0.87%   |
| SK hynix HFM512GDJTNI-82A0A 512GB      | 2         | 0.87%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.87%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 0.87%   |
| Seagate ST1000LM035-1RK172 970GB       | 2         | 0.87%   |
| Samsung SSD 860 250GB                  | 2         | 0.87%   |
| Samsung SSD 850 EVO 250GB              | 2         | 0.87%   |
| Samsung MZVLB512HBJQ-000L7 512GB       | 2         | 0.87%   |
| Kingston SA400S37120G 120GB SSD        | 2         | 0.87%   |
| Kingston OM8PCP3512F-AI1 512GB         | 2         | 0.87%   |
| Intel SSDPEKNU512GZ 512GB              | 2         | 0.87%   |
| Hitachi HTS54503 320GB                 | 2         | 0.87%   |
| HGST HTS721010A9E630 1TB               | 2         | 0.87%   |
| Dogfish SSD 128GB                      | 2         | 0.87%   |
| Crucial CT500MX500SSD1 500GB           | 2         | 0.87%   |
| Crucial CT240BX500SSD1 240GB           | 2         | 0.87%   |
| Crucial CT1000P2SSD8 1TB               | 2         | 0.87%   |
| Apple SSD SM0128G 121GB                | 2         | 0.87%   |
| WDC WDS120G1G0A-00SS50 120GB SSD       | 1         | 0.44%   |
| WDC WDS100T1X0E-00AFY0 1TB             | 1         | 0.44%   |
| WDC WD7500BPVT-75HXZT3 752GB           | 1         | 0.44%   |
| WDC WD5000LPVX-75V0TT0 500GB           | 1         | 0.44%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.44%   |
| WDC WD5000LPVX-08V0TT5 500GB           | 1         | 0.44%   |
| WDC WD5000LPLX-08ZNTT0 500GB           | 1         | 0.44%   |
| WDC WD5000LPLX-0 500GB                 | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 38.78%  |
| WDC                 | 14        | 14     | 28.57%  |
| Toshiba             | 5         | 5      | 10.2%   |
| Hitachi             | 5         | 6      | 10.2%   |
| HGST                | 3         | 3      | 6.12%   |
| Samsung Electronics | 2         | 2      | 4.08%   |
| Fujitsu             | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 21     | 19.1%   |
| Crucial             | 12        | 27     | 13.48%  |
| Kingston            | 9         | 10     | 10.11%  |
| Apple               | 5         | 8      | 5.62%   |
| WDC                 | 4         | 4      | 4.49%   |
| SPCC                | 4         | 4      | 4.49%   |
| LITEON              | 4         | 4      | 4.49%   |
| Transcend           | 3         | 3      | 3.37%   |
| SanDisk             | 3         | 4      | 3.37%   |
| PNY                 | 3         | 3      | 3.37%   |
| Netac               | 3         | 3      | 3.37%   |
| Dogfish             | 3         | 3      | 3.37%   |
| Toshiba             | 2         | 2      | 2.25%   |
| SK hynix            | 2         | 2      | 2.25%   |
| Unknown             | 2         | 2      | 2.25%   |
| SWORDBILL           | 1         | 2      | 1.12%   |
| RENICE              | 1         | 1      | 1.12%   |
| Patriot             | 1         | 1      | 1.12%   |
| OCZ                 | 1         | 1      | 1.12%   |
| Micron Technology   | 1         | 1      | 1.12%   |
| Intel               | 1         | 1      | 1.12%   |
| Indilinx            | 1         | 1      | 1.12%   |
| Hewlett-Packard     | 1         | 1      | 1.12%   |
| Gigabyte Technology | 1         | 1      | 1.12%   |
| GeIL                | 1         | 1      | 1.12%   |
| CT500MX5            | 1         | 1      | 1.12%   |
| Corsair             | 1         | 1      | 1.12%   |
| Apacer              | 1         | 1      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 76        | 114    | 37.81%  |
| NVMe    | 60        | 79     | 29.85%  |
| HDD     | 48        | 52     | 23.88%  |
| MMC     | 16        | 19     | 7.96%   |
| Unknown | 1         | 1      | 0.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 108       | 165    | 57.75%  |
| NVMe | 60        | 78     | 32.09%  |
| MMC  | 16        | 19     | 8.56%   |
| SAS  | 3         | 3      | 1.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 94        | 122    | 77.69%  |
| 0.51-1.0   | 25        | 42     | 20.66%  |
| 1.01-2.0   | 2         | 2      | 1.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 46        | 26.9%   |
| 251-500        | 43        | 25.15%  |
| 501-1000       | 23        | 13.45%  |
| 21-50          | 19        | 11.11%  |
| 51-100         | 17        | 9.94%   |
| 1-20           | 10        | 5.85%   |
| 1001-2000      | 8         | 4.68%   |
| More than 3000 | 3         | 1.75%   |
| 2001-3000      | 2         | 1.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 76        | 43.18%  |
| 21-50          | 29        | 16.48%  |
| 51-100         | 23        | 13.07%  |
| 101-250        | 21        | 11.93%  |
| 251-500        | 14        | 7.95%   |
| 501-1000       | 7         | 3.98%   |
| 1001-2000      | 4         | 2.27%   |
| More than 3000 | 1         | 0.57%   |
| 2001-3000      | 1         | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 4.35%   |
| WDC WD3200BPVT-80ZEST0 320GB                 | 1         | 1      | 4.35%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 4.35%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD         | 1         | 1      | 4.35%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 4.35%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 4.35%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 4.35%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 4.35%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 4.35%   |
| Seagate ST320LT007-9ZV142 320GB              | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 1      | 4.35%   |
| Samsung Electronics HM080HC 80GB             | 1         | 1      | 4.35%   |
| RENICE X2 64GB SSD                           | 1         | 1      | 4.35%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 1      | 4.35%   |
| Intel SSDPEKKF512G8L 512GB                   | 1         | 2      | 4.35%   |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 1      | 4.35%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 4.35%   |
| Hitachi HTS543216L9SA00 160GB                | 1         | 1      | 4.35%   |
| Hitachi HTS541080G9SA00 80GB                 | 1         | 1      | 4.35%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 4.35%   |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 4.35%   |
| Crucial CT1000MX500SSD4 1TB                  | 1         | 6      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 26.09%  |
| WDC                 | 3         | 3      | 13.04%  |
| Samsung Electronics | 3         | 3      | 13.04%  |
| Hitachi             | 3         | 3      | 13.04%  |
| HGST                | 2         | 2      | 8.7%    |
| Toshiba             | 1         | 1      | 4.35%   |
| RENICE              | 1         | 1      | 4.35%   |
| Kingston            | 1         | 1      | 4.35%   |
| Intel               | 1         | 2      | 4.35%   |
| Indilinx            | 1         | 1      | 4.35%   |
| Crucial             | 1         | 6      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 40%     |
| WDC                 | 3         | 3      | 20%     |
| Hitachi             | 3         | 3      | 20%     |
| HGST                | 2         | 2      | 13.33%  |
| Samsung Electronics | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 15     | 65.22%  |
| SSD  | 7         | 12     | 30.43%  |
| NVMe | 1         | 2      | 4.35%   |

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
| Works    | 137       | 211    | 75.27%  |
| Malfunc  | 23        | 29     | 12.64%  |
| Detected | 22        | 25     | 12.09%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 110       | 57.29%  |
| Samsung Electronics          | 19        | 9.9%    |
| AMD                          | 15        | 7.81%   |
| SK hynix                     | 9         | 4.69%   |
| SanDisk                      | 8         | 4.17%   |
| Kingston Technology Company  | 7         | 3.65%   |
| KIOXIA                       | 5         | 2.6%    |
| Phison Electronics           | 4         | 2.08%   |
| Nvidia                       | 3         | 1.56%   |
| Micron Technology            | 3         | 1.56%   |
| Toshiba America Info Systems | 2         | 1.04%   |
| Micron/Crucial Technology    | 2         | 1.04%   |
| Silicon Motion               | 1         | 0.52%   |
| Silicon Image                | 1         | 0.52%   |
| Shenzhen Longsys Electronics | 1         | 0.52%   |
| Marvell Technology Group     | 1         | 0.52%   |
| Lite-On Technology           | 1         | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 7.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 6.83%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 5.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 4.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 2.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 2.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 2.44%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 2.44%   |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 2.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 2.44%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 1.95%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.95%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 1.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.95%   |
| SK hynix BC511                                                                 | 3         | 1.46%   |
| SanDisk NVMe Controller                                                        | 3         | 1.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.46%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.46%   |
| Micron NVMe Storage Controller                                                 | 3         | 1.46%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.46%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.46%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.98%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.98%   |
| Samsung Electronics SATA controller                                            | 2         | 0.98%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 0.98%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 0.98%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.98%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.98%   |
| Intel Non-Volatile memory controller                                           | 2         | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 0.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 113       | 58.25%  |
| NVMe | 59        | 30.41%  |
| IDE  | 14        | 7.22%   |
| RAID | 8         | 4.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 135       | 82.32%  |
| AMD    | 29        | 17.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 7         | 4.27%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 2.44%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 2.44%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 4         | 2.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 1.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 3         | 1.83%   |
| Intel 12th Gen Core i7-12700H               | 3         | 1.83%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 3         | 1.83%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 2         | 1.22%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.22%   |
| Intel Core i5-5350U CPU @ 1.80GHz           | 2         | 1.22%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.22%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.22%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 1.22%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.22%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 1.22%   |
| Intel Core 2 CPU T5500 @ 1.66GHz            | 2         | 1.22%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2         | 1.22%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 2         | 1.22%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.22%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 1.22%   |
| Intel Atom CPU N570 @ 1.66GHz               | 2         | 1.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.22%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 1.22%   |
| AMD Ryzen 5 5600U with Radeon Graphics      | 2         | 1.22%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 1.22%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.61%   |
| Intel Pentium M processor 1.80GHz           | 1         | 0.61%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.61%   |
| Intel Pentium Gold 8505                     | 1         | 0.61%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.61%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.61%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 0.61%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 1         | 0.61%   |
| Intel Pentium CPU 2127U @ 1.90GHz           | 1         | 0.61%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 0.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 33        | 20.12%  |
| Intel Core i5           | 31        | 18.9%   |
| Other                   | 18        | 10.98%  |
| Intel Core i3           | 14        | 8.54%   |
| Intel Celeron           | 13        | 7.93%   |
| AMD Ryzen 7             | 9         | 5.49%   |
| Intel Core 2 Duo        | 7         | 4.27%   |
| Intel Atom              | 7         | 4.27%   |
| AMD Ryzen 5             | 7         | 4.27%   |
| Intel Pentium           | 3         | 1.83%   |
| Intel Pentium M         | 2         | 1.22%   |
| Intel Pentium Dual-Core | 2         | 1.22%   |
| Intel Core 2            | 2         | 1.22%   |
| AMD Ryzen 9             | 2         | 1.22%   |
| AMD Ryzen 3             | 2         | 1.22%   |
| Intel Pentium Silver    | 1         | 0.61%   |
| Intel Pentium Gold      | 1         | 0.61%   |
| Intel Genuine           | 1         | 0.61%   |
| AMD Turion 64 X2 Mobile | 1         | 0.61%   |
| AMD Sempron             | 1         | 0.61%   |
| AMD Phenom II           | 1         | 0.61%   |
| AMD E2                  | 1         | 0.61%   |
| AMD E1                  | 1         | 0.61%   |
| AMD E                   | 1         | 0.61%   |
| AMD A8                  | 1         | 0.61%   |
| AMD A6                  | 1         | 0.61%   |
| AMD A10                 | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 78        | 47.56%  |
| 4      | 51        | 31.1%   |
| 8      | 13        | 7.93%   |
| 6      | 12        | 7.32%   |
| 1      | 5         | 3.05%   |
| 14     | 3         | 1.83%   |
| 10     | 1         | 0.61%   |
| 5      | 1         | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 164       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 117       | 71.34%  |
| 1      | 47        | 28.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 160       | 97.56%  |
| 32-bit         | 4         | 2.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 8.93%   |
| 0x206a7    | 14        | 8.33%   |
| 0x806c1    | 10        | 5.95%   |
| 0x306a9    | 10        | 5.95%   |
| 0x406e3    | 8         | 4.76%   |
| 0x0a50000c | 8         | 4.76%   |
| 0x506e3    | 7         | 4.17%   |
| 0x1067a    | 6         | 3.57%   |
| 0x906ea    | 5         | 2.98%   |
| 0x806e9    | 5         | 2.98%   |
| 0x20655    | 5         | 2.98%   |
| 0x08608103 | 5         | 2.98%   |
| 0xa0652    | 4         | 2.38%   |
| 0x806ea    | 4         | 2.38%   |
| 0x706a8    | 4         | 2.38%   |
| 0x30678    | 4         | 2.38%   |
| 0x906a3    | 3         | 1.79%   |
| 0x406c4    | 3         | 1.79%   |
| 0x306d4    | 3         | 1.79%   |
| 0x306c3    | 3         | 1.79%   |
| 0x906a4    | 2         | 1.19%   |
| 0x806ec    | 2         | 1.19%   |
| 0x806d1    | 2         | 1.19%   |
| 0x706a1    | 2         | 1.19%   |
| 0x6fd      | 2         | 1.19%   |
| 0x106ca    | 2         | 1.19%   |
| 0x08108102 | 2         | 1.19%   |
| 0x07030106 | 2         | 1.19%   |
| 0xa0671    | 1         | 0.6%    |
| 0x906ed    | 1         | 0.6%    |
| 0x906e9    | 1         | 0.6%    |
| 0x906c0    | 1         | 0.6%    |
| 0x806eb    | 1         | 0.6%    |
| 0x6fb      | 1         | 0.6%    |
| 0x6f6      | 1         | 0.6%    |
| 0x6e8      | 1         | 0.6%    |
| 0x6d8      | 1         | 0.6%    |
| 0x6d6      | 1         | 0.6%    |
| 0x506c9    | 1         | 0.6%    |
| 0x40661    | 1         | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 12.2%   |
| Skylake          | 15        | 9.15%   |
| SandyBridge      | 15        | 9.15%   |
| TigerLake        | 11        | 6.71%   |
| IvyBridge        | 11        | 6.71%   |
| Zen 3            | 9         | 5.49%   |
| Unknown          | 8         | 4.88%   |
| Westmere         | 7         | 4.27%   |
| Silvermont       | 7         | 4.27%   |
| Penryn           | 6         | 3.66%   |
| Haswell          | 6         | 3.66%   |
| Goldmont plus    | 6         | 3.66%   |
| Core             | 5         | 3.05%   |
| Zen+             | 4         | 2.44%   |
| Icelake          | 4         | 2.44%   |
| CometLake        | 4         | 2.44%   |
| P6               | 3         | 1.83%   |
| Broadwell        | 3         | 1.83%   |
| Bonnell          | 3         | 1.83%   |
| Alderlake Hybrid | 3         | 1.83%   |
| Puma             | 2         | 1.22%   |
| Goldmont         | 2         | 1.22%   |
| Excavator        | 2         | 1.22%   |
| Zen 2            | 1         | 0.61%   |
| Tremont          | 1         | 0.61%   |
| Piledriver       | 1         | 0.61%   |
| Nehalem          | 1         | 0.61%   |
| K8 Hammer        | 1         | 0.61%   |
| K8 & K10 hybrid  | 1         | 0.61%   |
| K10              | 1         | 0.61%   |
| Bobcat           | 1         | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 123       | 60.89%  |
| Nvidia | 43        | 21.29%  |
| AMD    | 36        | 17.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 6.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 5.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 5.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 3.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 3.3%    |
| Intel HD Graphics 530                                                                    | 6         | 2.83%   |
| AMD Lucienne                                                                             | 6         | 2.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 2.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 2.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.89%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.89%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.89%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.89%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.89%   |
| Intel HD Graphics 620                                                                    | 4         | 1.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.89%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 1.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.42%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 1.42%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.94%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.94%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.94%   |
| Intel HD Graphics 500                                                                    | 2         | 0.94%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.94%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 0.94%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.94%   |
| Nvidia TU117M                                                                            | 1         | 0.47%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.47%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.47%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 88        | 53.66%  |
| Intel + Nvidia | 28        | 17.07%  |
| 1 x AMD        | 23        | 14.02%  |
| 1 x Nvidia     | 11        | 6.71%   |
| Intel + AMD    | 6         | 3.66%   |
| 2 x AMD        | 4         | 2.44%   |
| AMD + Nvidia   | 3         | 1.83%   |
| 2 x Intel      | 1         | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 143       | 85.12%  |
| Proprietary | 18        | 10.71%  |
| Unknown     | 7         | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 75.45%  |
| 0.01-0.5   | 19        | 11.38%  |
| 0.51-1.0   | 7         | 4.19%   |
| 3.01-4.0   | 6         | 3.59%   |
| 1.01-2.0   | 5         | 2.99%   |
| 7.01-8.0   | 3         | 1.8%    |
| 2.01-3.0   | 1         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 32        | 17.68%  |
| AU Optronics            | 30        | 16.57%  |
| Samsung Electronics     | 18        | 9.94%   |
| LG Display              | 18        | 9.94%   |
| BOE                     | 15        | 8.29%   |
| PANDA                   | 8         | 4.42%   |
| Chi Mei Optoelectronics | 8         | 4.42%   |
| Apple                   | 8         | 4.42%   |
| Hewlett-Packard         | 7         | 3.87%   |
| Lenovo                  | 5         | 2.76%   |
| Sharp                   | 4         | 2.21%   |
| Ancor Communications    | 4         | 2.21%   |
| Sony                    | 3         | 1.66%   |
| Goldstar                | 3         | 1.66%   |
| Dell                    | 2         | 1.1%    |
| CPT                     | 2         | 1.1%    |
| Sunplus                 | 1         | 0.55%   |
| STA                     | 1         | 0.55%   |
| Philips                 | 1         | 0.55%   |
| Panasonic               | 1         | 0.55%   |
| Packard Bell            | 1         | 0.55%   |
| ONN                     | 1         | 0.55%   |
| NEC Computers           | 1         | 0.55%   |
| LTM                     | 1         | 0.55%   |
| LG Philips              | 1         | 0.55%   |
| KDC                     | 1         | 0.55%   |
| InfoVision              | 1         | 0.55%   |
| HKC                     | 1         | 0.55%   |
| HannStar                | 1         | 0.55%   |
| Eizo                    | 1         | 0.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 2.21%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 1.66%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 1.1%    |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 2         | 1.1%    |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 1.1%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 1.1%    |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 1.1%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 1.1%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 1.1%    |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 2         | 1.1%    |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.55%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.55%   |
| Sony TV SNY3001 1920x1080                                                | 1         | 0.55%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.55%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 1         | 0.55%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.55%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.55%   |
| Sharp LCD Monitor SHP1445 3840x2160 346x194mm 15.6-inch                  | 1         | 0.55%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM0458 1360x768                          | 1         | 0.55%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 527x296mm 23.8-inch        | 1         | 0.55%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch        | 1         | 0.55%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 0.55%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch        | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch     | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch     | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch     | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC3854 1920x1080 382x215mm 17.3-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080                        | 1         | 0.55%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 0.55%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 75        | 44.12%  |
| 1366x768 (WXGA)    | 43        | 25.29%  |
| 3840x2160 (4K)     | 10        | 5.88%   |
| 1600x900 (HD+)     | 8         | 4.71%   |
| 1280x800 (WXGA)    | 6         | 3.53%   |
| 1920x1200 (WUXGA)  | 4         | 2.35%   |
| 2880x1800          | 3         | 1.76%   |
| 1440x900 (WXGA+)   | 3         | 1.76%   |
| 2560x1600          | 2         | 1.18%   |
| 2560x1080          | 2         | 1.18%   |
| 2256x1504          | 2         | 1.18%   |
| 2160x1440          | 2         | 1.18%   |
| 1280x1024 (SXGA)   | 2         | 1.18%   |
| 1024x600           | 2         | 1.18%   |
| 3840x2400          | 1         | 0.59%   |
| 2560x1440 (QHD)    | 1         | 0.59%   |
| 1680x1050 (WSXGA+) | 1         | 0.59%   |
| 1400x1050          | 1         | 0.59%   |
| 1360x768           | 1         | 0.59%   |
| 1024x768 (XGA)     | 1         | 0.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 75        | 41.44%  |
| 13      | 21        | 11.6%   |
| 17      | 17        | 9.39%   |
| 14      | 16        | 8.84%   |
| 24      | 11        | 6.08%   |
| 11      | 7         | 3.87%   |
| 23      | 6         | 3.31%   |
| 21      | 3         | 1.66%   |
| 19      | 3         | 1.66%   |
| 12      | 3         | 1.66%   |
| 10      | 3         | 1.66%   |
| Unknown | 3         | 1.66%   |
| 40      | 2         | 1.1%    |
| 34      | 2         | 1.1%    |
| 16      | 2         | 1.1%    |
| 84      | 1         | 0.55%   |
| 46      | 1         | 0.55%   |
| 43      | 1         | 0.55%   |
| 36      | 1         | 0.55%   |
| 32      | 1         | 0.55%   |
| 27      | 1         | 0.55%   |
| 25      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 100       | 55.56%  |
| 201-300     | 25        | 13.89%  |
| 351-400     | 21        | 11.67%  |
| 501-600     | 18        | 10%     |
| 701-800     | 4         | 2.22%   |
| 401-500     | 4         | 2.22%   |
| Unknown     | 3         | 1.67%   |
| 801-900     | 2         | 1.11%   |
| 1501-2000   | 1         | 0.56%   |
| 1001-1500   | 1         | 0.56%   |
| 901-1000    | 1         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 130       | 80.25%  |
| 16/10   | 21        | 12.96%  |
| 3/2     | 4         | 2.47%   |
| 5/4     | 2         | 1.23%   |
| 4/3     | 2         | 1.23%   |
| 21/9    | 2         | 1.23%   |
| Unknown | 1         | 0.62%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 76        | 41.99%  |
| 81-90          | 30        | 16.57%  |
| 121-130        | 17        | 9.39%   |
| 201-250        | 16        | 8.84%   |
| 51-60          | 7         | 3.87%   |
| 71-80          | 6         | 3.31%   |
| 501-1000       | 5         | 2.76%   |
| 251-300        | 4         | 2.21%   |
| 151-200        | 4         | 2.21%   |
| 61-70          | 3         | 1.66%   |
| 351-500        | 3         | 1.66%   |
| 41-50          | 3         | 1.66%   |
| Unknown        | 3         | 1.66%   |
| More than 1000 | 1         | 0.55%   |
| 301-350        | 1         | 0.55%   |
| 111-120        | 1         | 0.55%   |
| 91-100         | 1         | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 75        | 42.37%  |
| 101-120       | 40        | 22.6%   |
| 51-100        | 37        | 20.9%   |
| 161-240       | 14        | 7.91%   |
| More than 240 | 6         | 3.39%   |
| Unknown       | 3         | 1.69%   |
| 1-50          | 2         | 1.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 131       | 77.98%  |
| 2     | 26        | 15.48%  |
| 0     | 8         | 4.76%   |
| 3     | 3         | 1.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 89        | 33.09%  |
| Realtek Semiconductor             | 86        | 31.97%  |
| Qualcomm Atheros                  | 33        | 12.27%  |
| Broadcom                          | 14        | 5.2%    |
| MediaTek                          | 7         | 2.6%    |
| TP-Link                           | 6         | 2.23%   |
| Broadcom Limited                  | 6         | 2.23%   |
| Marvell Technology Group          | 5         | 1.86%   |
| Ralink                            | 3         | 1.12%   |
| Sierra Wireless                   | 2         | 0.74%   |
| Qualcomm Atheros Communications   | 2         | 0.74%   |
| Nvidia                            | 2         | 0.74%   |
| Motorola PCS                      | 2         | 0.74%   |
| ASIX Electronics                  | 2         | 0.74%   |
| Sweex                             | 1         | 0.37%   |
| Samsung Electronics               | 1         | 0.37%   |
| Ralink Technology                 | 1         | 0.37%   |
| NetGear                           | 1         | 0.37%   |
| Lenovo                            | 1         | 0.37%   |
| Ericsson Business Mobile Networks | 1         | 0.37%   |
| Dell                              | 1         | 0.37%   |
| D-Link                            | 1         | 0.37%   |
| Attansic Technology               | 1         | 0.37%   |
| ASUSTek Computer                  | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 16.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.77%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 3.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.52%   |
| Intel Wireless 8260                                               | 8         | 2.52%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 2.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.57%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 5         | 1.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.26%   |
| Intel Wireless 7265                                               | 4         | 1.26%   |
| Intel Wireless 3165                                               | 4         | 1.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 1.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.94%   |
| Intel Wireless 7260                                               | 3         | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 0.94%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.94%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.94%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 2         | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 49.43%  |
| Realtek Semiconductor           | 26        | 14.77%  |
| Qualcomm Atheros                | 23        | 13.07%  |
| Broadcom                        | 11        | 6.25%   |
| MediaTek                        | 7         | 3.98%   |
| TP-Link                         | 5         | 2.84%   |
| Broadcom Limited                | 5         | 2.84%   |
| Ralink                          | 3         | 1.7%    |
| Sierra Wireless                 | 2         | 1.14%   |
| Qualcomm Atheros Communications | 2         | 1.14%   |
| Sweex                           | 1         | 0.57%   |
| Ralink Technology               | 1         | 0.57%   |
| NetGear                         | 1         | 0.57%   |
| D-Link                          | 1         | 0.57%   |
| ASUSTek Computer                | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 10        | 5.68%   |
| Intel Wireless 8260                                                     | 8         | 4.55%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 4.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 3.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.84%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.27%   |
| Intel Wireless 7265                                                     | 4         | 2.27%   |
| Intel Wireless 3165                                                     | 4         | 2.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 2.27%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 1.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.7%    |
| Intel Wireless 7260                                                     | 3         | 1.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.7%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.7%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 1.7%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 1.14%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 1.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.14%   |
| Intel Wireless 3160                                                     | 2         | 1.14%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 1.14%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.14%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 1.14%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.14%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.14%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.14%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 76        | 55.88%  |
| Intel                    | 26        | 19.12%  |
| Qualcomm Atheros         | 14        | 10.29%  |
| Marvell Technology Group | 5         | 3.68%   |
| Broadcom                 | 5         | 3.68%   |
| Nvidia                   | 2         | 1.47%   |
| ASIX Electronics         | 2         | 1.47%   |
| TP-Link                  | 1         | 0.74%   |
| Samsung Electronics      | 1         | 0.74%   |
| Motorola PCS             | 1         | 0.74%   |
| Lenovo                   | 1         | 0.74%   |
| Broadcom Limited         | 1         | 0.74%   |
| Attansic Technology      | 1         | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 52        | 37.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12        | 8.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 5.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4         | 2.9%    |
| Intel Ethernet Connection I217-LM                                              | 3         | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 2.17%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 1.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 1.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.45%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.45%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.45%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 1.45%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.45%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.45%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 1.45%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.45%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.72%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.72%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.72%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.72%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.72%   |
| Motorola PCS motorola razr 2022                                                | 1         | 0.72%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.72%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.72%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.72%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 159       | 54.27%  |
| Ethernet | 130       | 44.37%  |
| Modem    | 3         | 1.02%   |
| Unknown  | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 133       | 78.7%   |
| Ethernet | 36        | 21.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 118       | 71.52%  |
| 1     | 41        | 24.85%  |
| 0     | 4         | 2.42%   |
| 3     | 2         | 1.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 119       | 71.69%  |
| Yes  | 47        | 28.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 48.12%  |
| Qualcomm Atheros Communications | 13        | 9.77%   |
| Realtek Semiconductor           | 12        | 9.02%   |
| Apple                           | 8         | 6.02%   |
| Broadcom                        | 7         | 5.26%   |
| Foxconn / Hon Hai               | 6         | 4.51%   |
| IMC Networks                    | 5         | 3.76%   |
| Cambridge Silicon Radio         | 5         | 3.76%   |
| Lite-On Technology              | 4         | 3.01%   |
| Hewlett-Packard                 | 3         | 2.26%   |
| Ralink                          | 2         | 1.5%    |
| MediaTek                        | 1         | 0.75%   |
| Dell                            | 1         | 0.75%   |
| ASUSTek Computer                | 1         | 0.75%   |
| Alps Electric                   | 1         | 0.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 24        | 18.05%  |
| Intel AX201 Bluetooth                                                               | 12        | 9.02%   |
| Realtek Bluetooth Radio                                                             | 10        | 7.52%   |
| Intel AX200 Bluetooth                                                               | 10        | 7.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 6.77%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 5.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 3.76%   |
| Apple Bluetooth Host Controller                                                     | 5         | 3.76%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 3.01%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.26%   |
| IMC Networks Wireless_Device                                                        | 3         | 2.26%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.5%    |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.5%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.5%    |
| Lite-On Wireless_Device                                                             | 2         | 1.5%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.5%    |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.5%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.5%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.5%    |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.5%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.75%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.75%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.75%   |
| MediaTek Wireless_Device                                                            | 1         | 0.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.75%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.75%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.75%   |
| Intel Bluetooth Device                                                              | 1         | 0.75%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.75%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.75%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.75%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.75%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.75%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.75%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.75%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 128       | 61.84%  |
| Nvidia                  | 34        | 16.43%  |
| AMD                     | 29        | 14.01%  |
| Realtek Semiconductor   | 2         | 0.97%   |
| VIA Technologies        | 1         | 0.48%   |
| Texas Instruments       | 1         | 0.48%   |
| Plantronics             | 1         | 0.48%   |
| Logitech                | 1         | 0.48%   |
| Lenovo                  | 1         | 0.48%   |
| JMTek                   | 1         | 0.48%   |
| Guillemot               | 1         | 0.48%   |
| Generalplus Technology  | 1         | 0.48%   |
| Focusrite-Novation      | 1         | 0.48%   |
| FIFINE 683 Microphone   | 1         | 0.48%   |
| Conexant Systems        | 1         | 0.48%   |
| CMX Systems             | 1         | 0.48%   |
| C-Media Electronics     | 1         | 0.48%   |
| BEHRINGER International | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 8.26%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 7.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 6.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 6.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 4.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 4.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 3.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 2.48%   |
| Nvidia Audio device                                                                               | 5         | 2.07%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 2.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.65%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 1.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.65%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.24%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.24%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.24%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.24%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.83%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.83%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.83%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 0.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.83%   |
| VIA Technologies USB Audio Device                                                                 | 1         | 0.41%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 48        | 24%     |
| Samsung Electronics | 45        | 22.5%   |
| Unknown             | 22        | 11%     |
| Micron Technology   | 19        | 9.5%    |
| Kingston            | 17        | 8.5%    |
| Crucial             | 10        | 5%      |
| Elpida              | 5         | 2.5%    |
| Unknown (ABCD)      | 4         | 2%      |
| Corsair             | 4         | 2%      |
| A-DATA Technology   | 4         | 2%      |
| Ramaxel Technology  | 3         | 1.5%    |
| Transcend           | 2         | 1%      |
| Smart               | 2         | 1%      |
| G.Skill             | 2         | 1%      |
| Unknown             | 2         | 1%      |
| Wilk                | 1         | 0.5%    |
| Team                | 1         | 0.5%    |
| PNY                 | 1         | 0.5%    |
| Nanya Technology    | 1         | 0.5%    |
| Innodisk            | 1         | 0.5%    |
| Hewlett-Packard     | 1         | 0.5%    |
| Essencore           | 1         | 0.5%    |
| CSX                 | 1         | 0.5%    |
| Avant               | 1         | 0.5%    |
| ASint Technology    | 1         | 0.5%    |
| 48spaces            | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 2.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 2.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 2.34%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 4         | 1.87%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.4%    |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.93%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.93%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.93%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.93%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.93%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.93%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.93%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.93%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.93%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.93%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 0.93%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.93%   |
| A-DATA RAM Module 4GB SODIMM DDR3 1333MT/s                       | 2         | 0.93%   |
| Unknown                                                          | 2         | 0.93%   |
| Wilk RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s             | 1         | 0.47%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                            | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 72        | 42.6%   |
| DDR3    | 68        | 40.24%  |
| LPDDR4  | 8         | 4.73%   |
| DDR2    | 7         | 4.14%   |
| DDR     | 5         | 2.96%   |
| SDRAM   | 3         | 1.78%   |
| LPDDR3  | 3         | 1.78%   |
| DRAM    | 1         | 0.59%   |
| DDR5    | 1         | 0.59%   |
| Unknown | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 158       | 92.94%  |
| Row Of Chips | 10        | 5.88%   |
| DIMM         | 1         | 0.59%   |
| Unknown      | 1         | 0.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 66        | 35.87%  |
| 4096  | 58        | 31.52%  |
| 2048  | 28        | 15.22%  |
| 16384 | 21        | 11.41%  |
| 1024  | 7         | 3.8%    |
| 32768 | 3         | 1.63%   |
| 512   | 1         | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 42        | 23.08%  |
| 3200    | 36        | 19.78%  |
| 2667    | 22        | 12.09%  |
| 2400    | 16        | 8.79%   |
| 1334    | 11        | 6.04%   |
| 1333    | 11        | 6.04%   |
| Unknown | 11        | 6.04%   |
| 2133    | 7         | 3.85%   |
| 667     | 7         | 3.85%   |
| 1067    | 5         | 2.75%   |
| 4199    | 3         | 1.65%   |
| 4267    | 2         | 1.1%    |
| 1867    | 2         | 1.1%    |
| 8400    | 1         | 0.55%   |
| 4800    | 1         | 0.55%   |
| 4266    | 1         | 0.55%   |
| 2933    | 1         | 0.55%   |
| 975     | 1         | 0.55%   |
| 533     | 1         | 0.55%   |
| 166     | 1         | 0.55%   |

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
| Chicony Electronics                    | 34        | 24.64%  |
| Microdia                               | 14        | 10.14%  |
| Realtek Semiconductor                  | 11        | 7.97%   |
| IMC Networks                           | 10        | 7.25%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 6.52%   |
| Quanta                                 | 8         | 5.8%    |
| Acer                                   | 7         | 5.07%   |
| Bison Electronics                      | 6         | 4.35%   |
| Suyin                                  | 5         | 3.62%   |
| Apple                                  | 5         | 3.62%   |
| Sunplus Innovation Technology          | 4         | 2.9%    |
| Ricoh                                  | 4         | 2.9%    |
| Lite-On Technology                     | 4         | 2.9%    |
| Luxvisions Innotech Limited            | 3         | 2.17%   |
| Lenovo                                 | 3         | 2.17%   |
| Silicon Motion                         | 2         | 1.45%   |
| Alcor Micro                            | 2         | 1.45%   |
| Z-Star Microelectronics                | 1         | 0.72%   |
| Y Media                                | 1         | 0.72%   |
| Primax Electronics                     | 1         | 0.72%   |
| Novatek Microelectronics               | 1         | 0.72%   |
| Logitech                               | 1         | 0.72%   |
| Hewlett-Packard                        | 1         | 0.72%   |
| Goodong Industry                       | 1         | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 7         | 5.07%   |
| Microdia Integrated_Webcam_HD                       | 5         | 3.62%   |
| Quanta HD User Facing                               | 4         | 2.9%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.9%    |
| Realtek Integrated_Webcam_HD                        | 3         | 2.17%   |
| IMC Networks Integrated Camera                      | 3         | 2.17%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 2.17%   |
| Chicony HD User Facing                              | 3         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 2.17%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.45%   |
| Ricoh USB2.0 Camera                                 | 2         | 1.45%   |
| Realtek USB Camera                                  | 2         | 1.45%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.45%   |
| Microdia Webcam Vitade AF                           | 2         | 1.45%   |
| Lite-On HP HD Camera                                | 2         | 1.45%   |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 1.45%   |
| Bison HD Webcam                                     | 2         | 1.45%   |
| Bison BisonCam,NB Pro                               | 2         | 1.45%   |
| Apple Built-in iSight                               | 2         | 1.45%   |
| Acer Integrated Camera                              | 2         | 1.45%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 0.72%   |
| Y Media USB Camera                                  | 1         | 0.72%   |
| Suyin Sony Visual Communication Camera              | 1         | 0.72%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.72%   |
| Suyin HP Webcam-101                                 | 1         | 0.72%   |
| Suyin HP Webcam                                     | 1         | 0.72%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.72%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 0.72%   |
| Sunplus ASUS Webcam                                 | 1         | 0.72%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.72%   |
| Silicon Motion Web Camera                           | 1         | 0.72%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 0.72%   |
| Ricoh Integrated Webcam                             | 1         | 0.72%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.72%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.72%   |
| Realtek Integrated Webcam HD                        | 1         | 0.72%   |
| Realtek Integrated Webcam                           | 1         | 0.72%   |
| Realtek EasyCamera                                  | 1         | 0.72%   |
| Realtek Built-In Video Camera                       | 1         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 24.14%  |
| Synaptics                  | 6         | 20.69%  |
| Shenzhen Goodix Technology | 5         | 17.24%  |
| AuthenTec                  | 5         | 17.24%  |
| Upek                       | 3         | 10.34%  |
| Elan Microelectronics      | 2         | 6.9%    |
| Focal-systems.Corp         | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                      | 5         | 17.24%  |
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 10.34%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 3         | 10.34%  |
| AuthenTec AES2810                                        | 3         | 10.34%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 2         | 6.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 2         | 6.9%    |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 3.45%   |
| Upek TCS5B Fingerprint sensor                            | 1         | 3.45%   |
| Synaptics UWP WBDI Device                                | 1         | 3.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 3.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.45%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 3.45%   |
| Elan ELAN:Fingerprint                                    | 1         | 3.45%   |
| Elan ELAN:ARM-M4                                         | 1         | 3.45%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 3.45%   |
| AuthenTec AES1660 Fingerprint Sensor                     | 1         | 3.45%   |
| Unknown                                                  | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 41.67%  |
| Alcor Micro           | 5         | 41.67%  |
| Advanced Card Systems | 2         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 5         | 41.67%  |
| Broadcom 5880                                  | 4         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 8.33%   |
| Advanced Card Systems ACR38 SmartCard Reader   | 1         | 8.33%   |
| Advanced Card Systems ACR122U                  | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 101       | 59.41%  |
| 1     | 53        | 31.18%  |
| 2     | 14        | 8.24%   |
| 3     | 2         | 1.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 32        | 39.02%  |
| Fingerprint reader       | 29        | 35.37%  |
| Chipcard                 | 10        | 12.2%   |
| Multimedia controller    | 3         | 3.66%   |
| Net/wireless             | 2         | 2.44%   |
| Camera                   | 2         | 2.44%   |
| Net/ethernet             | 1         | 1.22%   |
| Flash memory             | 1         | 1.22%   |
| Communication controller | 1         | 1.22%   |
| Bluetooth                | 1         | 1.22%   |

