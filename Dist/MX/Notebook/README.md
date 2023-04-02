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

Total: 429

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MX 21 | 151       | 50.84%  |
| MX 19 | 87        | 29.29%  |
| MX 20 | 43        | 14.48%  |
| MX 18 | 13        | 4.38%   |
| MX 17 | 2         | 0.67%   |
| MX 16 | 1         | 0.34%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MX   | 289       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 4.19.0-6-amd64           | 34        | 10.49%  |
| 5.10.0-21-amd64          | 16        | 4.94%   |
| 5.10.0-13-amd64          | 15        | 4.63%   |
| 5.10.0-9-amd64           | 14        | 4.32%   |
| 5.10.0-5mx-amd64         | 13        | 4.01%   |
| 5.10.0-18-amd64          | 12        | 3.7%    |
| 6.0.0-6mx-amd64          | 10        | 3.09%   |
| 5.8.0-3-amd64            | 9         | 2.78%   |
| 5.10.0-16-amd64          | 9         | 2.78%   |
| 5.14.0-4mx-amd64         | 8         | 2.47%   |
| 5.10.0-19-amd64          | 8         | 2.47%   |
| 5.16.0-5mx-amd64         | 7         | 2.16%   |
| 4.19.0-13-amd64          | 7         | 2.16%   |
| 5.10.0-14-amd64          | 6         | 1.85%   |
| 5.10.0-11-amd64          | 6         | 1.85%   |
| 4.19.0-16-amd64          | 6         | 1.85%   |
| 4.19.0-14-amd64          | 6         | 1.85%   |
| 5.6.0-2-amd64            | 5         | 1.54%   |
| 5.18.0-4mx-amd64         | 5         | 1.54%   |
| 6.0.0-4mx-amd64          | 4         | 1.23%   |
| 5.10.0-20-amd64          | 4         | 1.23%   |
| 4.19.0-5-amd64           | 4         | 1.23%   |
| 4.19.0-17-amd64          | 4         | 1.23%   |
| 4.19.0-11-amd64          | 4         | 1.23%   |
| 5.10.0-8mx-amd64         | 3         | 0.93%   |
| 5.10.0-17-amd64          | 3         | 0.93%   |
| 4.19.0-9-amd64           | 3         | 0.93%   |
| 4.19.0-12-amd64          | 3         | 0.93%   |
| 4.19.0-1-amd64           | 3         | 0.93%   |
| 6.1.0-4mx-amd64          | 2         | 0.62%   |
| 6.0.0-3mx-amd64          | 2         | 0.62%   |
| 5.8.16-antix.1-amd64-smp | 2         | 0.62%   |
| 5.6.10-antix.1-amd64-smp | 2         | 0.62%   |
| 5.4.0-3-amd64            | 2         | 0.62%   |
| 5.19.0-2mx-amd64         | 2         | 0.62%   |
| 5.16.0-6mx-amd64         | 2         | 0.62%   |
| 5.10.0-8-amd64           | 2         | 0.62%   |
| 5.10.0-15-amd64          | 2         | 0.62%   |
| 5.10.0-13-686-pae        | 2         | 0.62%   |
| 5.10.0-11-686-pae        | 2         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 116       | 37.42%  |
| 4.19.0   | 83        | 26.77%  |
| 6.0.0    | 18        | 5.81%   |
| 5.16.0   | 11        | 3.55%   |
| 5.8.0    | 9         | 2.9%    |
| 5.14.0   | 8         | 2.58%   |
| 5.6.0    | 7         | 2.26%   |
| 5.18.0   | 7         | 2.26%   |
| 5.4.0    | 6         | 1.94%   |
| 5.19.0   | 4         | 1.29%   |
| 5.17.0   | 4         | 1.29%   |
| 6.1.0    | 3         | 0.97%   |
| 5.8.16   | 2         | 0.65%   |
| 5.6.10   | 2         | 0.65%   |
| 5.3.0    | 2         | 0.65%   |
| 5.2.21   | 2         | 0.65%   |
| 5.15.0   | 2         | 0.65%   |
| 4.9.193  | 2         | 0.65%   |
| 4.15.0   | 2         | 0.65%   |
| 6.1.15   | 1         | 0.32%   |
| 6.1.12   | 1         | 0.32%   |
| 5.9.1    | 1         | 0.32%   |
| 5.7.0    | 1         | 0.32%   |
| 5.5.0    | 1         | 0.32%   |
| 5.3.10   | 1         | 0.32%   |
| 5.2.8    | 1         | 0.32%   |
| 5.2.0    | 1         | 0.32%   |
| 5.13.0   | 1         | 0.32%   |
| 5.11.0   | 1         | 0.32%   |
| 5.10.82  | 1         | 0.32%   |
| 5.10.142 | 1         | 0.32%   |
| 5.10.1   | 1         | 0.32%   |
| 5.1.2    | 1         | 0.32%   |
| 5.0.0    | 1         | 0.32%   |
| 4.9.246  | 1         | 0.32%   |
| 4.19.174 | 1         | 0.32%   |
| 4.18.0   | 1         | 0.32%   |
| 3.16.0   | 1         | 0.32%   |
| Unknown  | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 119       | 38.39%  |
| 4.19    | 84        | 27.1%   |
| 6.0     | 18        | 5.81%   |
| 5.8     | 11        | 3.55%   |
| 5.16    | 11        | 3.55%   |
| 5.6     | 9         | 2.9%    |
| 5.14    | 8         | 2.58%   |
| 5.18    | 7         | 2.26%   |
| 5.4     | 6         | 1.94%   |
| 6.1     | 5         | 1.61%   |
| 5.2     | 4         | 1.29%   |
| 5.19    | 4         | 1.29%   |
| 5.17    | 4         | 1.29%   |
| 5.3     | 3         | 0.97%   |
| 4.9     | 3         | 0.97%   |
| 5.15    | 2         | 0.65%   |
| 4.15    | 2         | 0.65%   |
| 5.9     | 1         | 0.32%   |
| 5.7     | 1         | 0.32%   |
| 5.5     | 1         | 0.32%   |
| 5.13    | 1         | 0.32%   |
| 5.11    | 1         | 0.32%   |
| 5.1     | 1         | 0.32%   |
| 5.0     | 1         | 0.32%   |
| 4.18    | 1         | 0.32%   |
| 3.16    | 1         | 0.32%   |
| Unknown | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 273       | 94.14%  |
| i686   | 17        | 5.86%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| XFCE             | 209       | 70.61%  |
| KDE5             | 49        | 16.55%  |
| Budgie           | 7         | 2.36%   |
| Unknown          | 6         | 2.03%   |
| i3               | 5         | 1.69%   |
| GNOME            | 4         | 1.35%   |
| X-Cinnamon       | 2         | 0.68%   |
| MATE             | 2         | 0.68%   |
| LXQt             | 2         | 0.68%   |
| fluxbox          | 2         | 0.68%   |
| Cinnamon         | 2         | 0.68%   |
| Trinity          | 1         | 0.34%   |
| spectrwm         | 1         | 0.34%   |
| LXDE             | 1         | 0.34%   |
| lightdm-xsession | 1         | 0.34%   |
| GNOME Flashback  | 1         | 0.34%   |
| GNOME Classic    | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 285       | 98.62%  |
| Tty     | 3         | 1.04%   |
| Wayland | 1         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 233       | 79.52%  |
| SDDM    | 43        | 14.68%  |
| TDM     | 9         | 3.07%   |
| SLiM    | 7         | 2.39%   |
| Unknown | 1         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 113       | 38.05%  |
| Unknown | 57        | 19.19%  |
| de_DE   | 29        | 9.76%   |
| en_GB   | 19        | 6.4%    |
| it_IT   | 11        | 3.7%    |
| ru_RU   | 9         | 3.03%   |
| sk_SK   | 6         | 2.02%   |
| fr_FR   | 6         | 2.02%   |
| pt_BR   | 5         | 1.68%   |
| pl_PL   | 4         | 1.35%   |
| es_ES   | 4         | 1.35%   |
| en_AU   | 4         | 1.35%   |
| de_CH   | 3         | 1.01%   |
| tr_TR   | 2         | 0.67%   |
| nl_NL   | 2         | 0.67%   |
| fr_BE   | 2         | 0.67%   |
| es_CO   | 2         | 0.67%   |
| en_NZ   | 2         | 0.67%   |
| en_IE   | 2         | 0.67%   |
| bg_BG   | 2         | 0.67%   |
| zh_CN   | 1         | 0.34%   |
| uk_UA   | 1         | 0.34%   |
| nb_NO   | 1         | 0.34%   |
| id_ID   | 1         | 0.34%   |
| hu_HU   | 1         | 0.34%   |
| fr_CA   | 1         | 0.34%   |
| fi_FI   | 1         | 0.34%   |
| es_VE   | 1         | 0.34%   |
| es_UY   | 1         | 0.34%   |
| es_PE   | 1         | 0.34%   |
| es_MX   | 1         | 0.34%   |
| en_CA   | 1         | 0.34%   |
| cs_CZ   | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 171       | 59.17%  |
| BIOS | 118       | 40.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 248       | 85.22%  |
| Overlay | 32        | 11%     |
| Btrfs   | 7         | 2.41%   |
| Xfs     | 2         | 0.69%   |
| F2fs    | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 189       | 65.17%  |
| MBR     | 97        | 33.45%  |
| Unknown | 4         | 1.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 233       | 79.52%  |
| Yes       | 60        | 20.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 174       | 60%     |
| Yes       | 116       | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo                    | 63        | 21.8%   |
| Hewlett-Packard           | 50        | 17.3%   |
| Dell                      | 34        | 11.76%  |
| ASUSTek Computer          | 30        | 10.38%  |
| Acer                      | 28        | 9.69%   |
| Toshiba                   | 11        | 3.81%   |
| Sony                      | 11        | 3.81%   |
| Apple                     | 9         | 3.11%   |
| Medion                    | 7         | 2.42%   |
| MSI                       | 6         | 2.08%   |
| Samsung Electronics       | 5         | 1.73%   |
| Fujitsu Siemens           | 3         | 1.04%   |
| Alienware                 | 3         | 1.04%   |
| TUXEDO                    | 2         | 0.69%   |
| Notebook                  | 2         | 0.69%   |
| Google                    | 2         | 0.69%   |
| Gigabyte Technology       | 2         | 0.69%   |
| Clevo                     | 2         | 0.69%   |
| Chuwi                     | 2         | 0.69%   |
| Unknown                   | 2         | 0.69%   |
| win element               | 1         | 0.35%   |
| Vulcan Electronics        | 1         | 0.35%   |
| UMAX                      | 1         | 0.35%   |
| SANTECH                   | 1         | 0.35%   |
| RTD Embedded Technologies | 1         | 0.35%   |
| Pixus                     | 1         | 0.35%   |
| Panasonic                 | 1         | 0.35%   |
| Packard Bell              | 1         | 0.35%   |
| Linx                      | 1         | 0.35%   |
| Irbis                     | 1         | 0.35%   |
| Intel                     | 1         | 0.35%   |
| Framework                 | 1         | 0.35%   |
| eMachines                 | 1         | 0.35%   |
| efirstview                | 1         | 0.35%   |
| AMI                       | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 4         | 1.38%   |
| HP Stream Laptop 14-cb0XX           | 2         | 0.69%   |
| HP ProBook 650 G1                   | 2         | 0.69%   |
| HP Laptop 17-ak0xx                  | 2         | 0.69%   |
| Chuwi GemiBook Pro                  | 2         | 0.69%   |
| ASUS X200CA                         | 2         | 0.69%   |
| Apple MacBookAir7,2                 | 2         | 0.69%   |
| Acer Nitro AN515-55                 | 2         | 0.69%   |
| win element MoreFine S500+          | 1         | 0.35%   |
| Vulcan Excursion XB                 | 1         | 0.35%   |
| UMAX VisionBook-N12R                | 1         | 0.35%   |
| TUXEDO N7x0WU                       | 1         | 0.35%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 1         | 0.35%   |
| Toshiba Satellite P875              | 1         | 0.35%   |
| Toshiba Satellite M70               | 1         | 0.35%   |
| Toshiba Satellite L850-CJK          | 1         | 0.35%   |
| Toshiba Satellite L650              | 1         | 0.35%   |
| Toshiba Satellite C845              | 1         | 0.35%   |
| Toshiba Satellite C70-B             | 1         | 0.35%   |
| Toshiba Satellite C660              | 1         | 0.35%   |
| Toshiba Satellite C50-A-12K         | 1         | 0.35%   |
| Toshiba Satellite A300              | 1         | 0.35%   |
| Toshiba PORTEGE Z30-C               | 1         | 0.35%   |
| Toshiba PORTEGE R705                | 1         | 0.35%   |
| Sony VPCYB3V1E                      | 1         | 0.35%   |
| Sony VPCSB1V9R                      | 1         | 0.35%   |
| Sony VPCF23P1E                      | 1         | 0.35%   |
| Sony VPCF119FX                      | 1         | 0.35%   |
| Sony VPCEH2N1E                      | 1         | 0.35%   |
| Sony VPCEC3S1E                      | 1         | 0.35%   |
| Sony VPCCB32FD                      | 1         | 0.35%   |
| Sony VGN-TZ3RXN_B                   | 1         | 0.35%   |
| Sony VGN-NR310FH                    | 1         | 0.35%   |
| Sony SVT13115FBS                    | 1         | 0.35%   |
| Sony SVE1513Q1ESI                   | 1         | 0.35%   |
| SANTECH X170KM-G                    | 1         | 0.35%   |
| Samsung R780/R778                   | 1         | 0.35%   |
| Samsung NC210/NC110                 | 1         | 0.35%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 1         | 0.35%   |
| Samsung 340XAA/350XAA/550XAA        | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 44        | 15.22%  |
| Acer Aspire          | 17        | 5.88%   |
| Dell Latitude        | 13        | 4.5%    |
| Dell Inspiron        | 10        | 3.46%   |
| Toshiba Satellite    | 9         | 3.11%   |
| HP ProBook           | 9         | 3.11%   |
| Lenovo IdeaPad       | 7         | 2.42%   |
| HP Pavilion          | 7         | 2.42%   |
| HP EliteBook         | 7         | 2.42%   |
| HP Laptop            | 5         | 1.73%   |
| Dell Vostro          | 5         | 1.73%   |
| HP ZBook             | 4         | 1.38%   |
| ASUS VivoBook        | 4         | 1.38%   |
| Unknown              | 4         | 1.38%   |
| HP Compaq            | 3         | 1.04%   |
| ASUS TUF             | 3         | 1.04%   |
| Acer Swift           | 3         | 1.04%   |
| Acer Nitro           | 3         | 1.04%   |
| Toshiba PORTEGE      | 2         | 0.69%   |
| Lenovo ThinkBook     | 2         | 0.69%   |
| Lenovo B590          | 2         | 0.69%   |
| HP Stream            | 2         | 0.69%   |
| HP 15                | 2         | 0.69%   |
| Dell Precision       | 2         | 0.69%   |
| Chuwi GemiBook       | 2         | 0.69%   |
| ASUS X200CA          | 2         | 0.69%   |
| ASUS ROG             | 2         | 0.69%   |
| ASUS ASUS            | 2         | 0.69%   |
| Apple MacBookPro11   | 2         | 0.69%   |
| Apple MacBookAir7    | 2         | 0.69%   |
| Alienware m15        | 2         | 0.69%   |
| Acer Extensa         | 2         | 0.69%   |
| win element MoreFine | 1         | 0.35%   |
| Vulcan Excursion     | 1         | 0.35%   |
| UMAX VisionBook-N12R | 1         | 0.35%   |
| TUXEDO N7x0WU        | 1         | 0.35%   |
| TUXEDO InfinityBook  | 1         | 0.35%   |
| Sony VPCYB3V1E       | 1         | 0.35%   |
| Sony VPCSB1V9R       | 1         | 0.35%   |
| Sony VPCF23P1E       | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 30        | 10.38%  |
| 2011    | 29        | 10.03%  |
| 2018    | 25        | 8.65%   |
| 2010    | 25        | 8.65%   |
| 2012    | 24        | 8.3%    |
| 2016    | 20        | 6.92%   |
| 2015    | 20        | 6.92%   |
| 2013    | 20        | 6.92%   |
| 2019    | 16        | 5.54%   |
| 2020    | 15        | 5.19%   |
| 2014    | 14        | 4.84%   |
| 2017    | 13        | 4.5%    |
| 2008    | 10        | 3.46%   |
| 2009    | 8         | 2.77%   |
| 2022    | 6         | 2.08%   |
| 2007    | 6         | 2.08%   |
| 2006    | 4         | 1.38%   |
| 2005    | 3         | 1.04%   |
| Unknown | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 289       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 288       | 99.65%  |
| Enabled  | 1         | 0.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 285       | 98.62%  |
| Yes  | 4         | 1.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 81        | 27.93%  |
| 3.01-4.0    | 56        | 19.31%  |
| 8.01-16.0   | 54        | 18.62%  |
| 16.01-24.0  | 41        | 14.14%  |
| 1.01-2.0    | 23        | 7.93%   |
| 32.01-64.0  | 16        | 5.52%   |
| 2.01-3.0    | 10        | 3.45%   |
| 0.51-1.0    | 5         | 1.72%   |
| 24.01-32.0  | 2         | 0.69%   |
| 64.01-256.0 | 2         | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 114       | 36.66%  |
| 2.01-3.0  | 75        | 24.12%  |
| 3.01-4.0  | 49        | 15.76%  |
| 0.51-1.0  | 33        | 10.61%  |
| 4.01-8.0  | 31        | 9.97%   |
| 8.01-16.0 | 6         | 1.93%   |
| 0.01-0.5  | 3         | 0.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 211       | 71.77%  |
| 2      | 63        | 21.43%  |
| 3      | 15        | 5.1%    |
| 0      | 3         | 1.02%   |
| 4      | 2         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 188       | 64.83%  |
| Yes       | 102       | 35.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 245       | 84.78%  |
| No        | 44        | 15.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 281       | 96.9%   |
| No        | 9         | 3.1%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 220       | 75.86%  |
| No        | 70        | 24.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 56        | 19.24%  |
| Germany     | 34        | 11.68%  |
| Italy       | 19        | 6.53%   |
| UK          | 14        | 4.81%   |
| Canada      | 13        | 4.47%   |
| Russia      | 11        | 3.78%   |
| Netherlands | 9         | 3.09%   |
| India       | 9         | 3.09%   |
| France      | 8         | 2.75%   |
| Brazil      | 8         | 2.75%   |
| Spain       | 7         | 2.41%   |
| Slovakia    | 7         | 2.41%   |
| Poland      | 7         | 2.41%   |
| Austria     | 6         | 2.06%   |
| Australia   | 6         | 2.06%   |
| Ukraine     | 4         | 1.37%   |
| Mexico      | 4         | 1.37%   |
| Belgium     | 4         | 1.37%   |
| Thailand    | 3         | 1.03%   |
| Switzerland | 3         | 1.03%   |
| Romania     | 3         | 1.03%   |
| New Zealand | 3         | 1.03%   |
| Finland     | 3         | 1.03%   |
| Czechia     | 3         | 1.03%   |
| Colombia    | 3         | 1.03%   |
| Vietnam     | 2         | 0.69%   |
| Turkey      | 2         | 0.69%   |
| Sweden      | 2         | 0.69%   |
| Serbia      | 2         | 0.69%   |
| Portugal    | 2         | 0.69%   |
| Norway      | 2         | 0.69%   |
| Indonesia   | 2         | 0.69%   |
| Hungary     | 2         | 0.69%   |
| Greece      | 2         | 0.69%   |
| Egypt       | 2         | 0.69%   |
| China       | 2         | 0.69%   |
| Bulgaria    | 2         | 0.69%   |
| Belarus     | 2         | 0.69%   |
| Bangladesh  | 2         | 0.69%   |
| Venezuela   | 1         | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vienna           | 6         | 1.98%   |
| Bratislava       | 6         | 1.98%   |
| Rome             | 4         | 1.32%   |
| Berlin           | 4         | 1.32%   |
| Warsaw           | 3         | 0.99%   |
| St Petersburg    | 3         | 0.99%   |
| Munich           | 3         | 0.99%   |
| Moscow           | 3         | 0.99%   |
| Montreal         | 3         | 0.99%   |
| Milan            | 3         | 0.99%   |
| Los Angeles      | 3         | 0.99%   |
| Amsterdam        | 3         | 0.99%   |
| Walled Lake      | 2         | 0.66%   |
| Prague           | 2         | 0.66%   |
| Patna            | 2         | 0.66%   |
| Oxford           | 2         | 0.66%   |
| Orange           | 2         | 0.66%   |
| New York         | 2         | 0.66%   |
| Minsk            | 2         | 0.66%   |
| Melbourne        | 2         | 0.66%   |
| Madrid           | 2         | 0.66%   |
| Istanbul         | 2         | 0.66%   |
| Ho Chi Minh City | 2         | 0.66%   |
| Florence         | 2         | 0.66%   |
| Doesburg         | 2         | 0.66%   |
| Dnipro           | 2         | 0.66%   |
| Dhaka            | 2         | 0.66%   |
| Casale Litta     | 2         | 0.66%   |
| Canberra         | 2         | 0.66%   |
| Cambridge        | 2         | 0.66%   |
| Calgary          | 2         | 0.66%   |
| Cairo            | 2         | 0.66%   |
| Buffalo          | 2         | 0.66%   |
| Budapest         | 2         | 0.66%   |
| Bogotá          | 2         | 0.66%   |
| Zurich           | 1         | 0.33%   |
| Zeven            | 1         | 0.33%   |
| Yekaterinburg    | 1         | 0.33%   |
| Xalapa           | 1         | 0.33%   |
| Wermelskirchen   | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 49        | 64     | 13.07%  |
| WDC                 | 44        | 45     | 11.73%  |
| Seagate             | 34        | 37     | 9.07%   |
| Kingston            | 27        | 29     | 7.2%    |
| Toshiba             | 24        | 25     | 6.4%    |
| Unknown             | 23        | 28     | 6.13%   |
| Crucial             | 23        | 39     | 6.13%   |
| SK hynix            | 17        | 18     | 4.53%   |
| SanDisk             | 16        | 18     | 4.27%   |
| Hitachi             | 13        | 14     | 3.47%   |
| Intel               | 12        | 17     | 3.2%    |
| HGST                | 11        | 16     | 2.93%   |
| Micron Technology   | 6         | 10     | 1.6%    |
| Apple               | 6         | 9      | 1.6%    |
| SPCC                | 5         | 5      | 1.33%   |
| PNY                 | 5         | 5      | 1.33%   |
| Transcend           | 4         | 4      | 1.07%   |
| LITEON              | 4         | 4      | 1.07%   |
| Phison              | 3         | 4      | 0.8%    |
| Netac               | 3         | 3      | 0.8%    |
| KIOXIA              | 3         | 5      | 0.8%    |
| Dogfish             | 3         | 3      | 0.8%    |
| A-DATA Technology   | 3         | 5      | 0.8%    |
| Unknown             | 3         | 3      | 0.8%    |
| Team                | 2         | 2      | 0.53%   |
| Patriot             | 2         | 2      | 0.53%   |
| KingSpec            | 2         | 2      | 0.53%   |
| KingDian            | 2         | 2      | 0.53%   |
| Indilinx            | 2         | 4      | 0.53%   |
| Fujitsu             | 2         | 2      | 0.53%   |
| Corsair             | 2         | 2      | 0.53%   |
| ZTC                 | 1         | 1      | 0.27%   |
| Yeyian              | 1         | 1      | 0.27%   |
| SWORDBILL           | 1         | 2      | 0.27%   |
| Smart               | 1         | 1      | 0.27%   |
| SABRENT             | 1         | 1      | 0.27%   |
| RENICE              | 1         | 1      | 0.27%   |
| Phison Electronics  | 1         | 2      | 0.27%   |
| OCZ                 | 1         | 1      | 0.27%   |
| LITEONIT            | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 6         | 1.55%   |
| Samsung SSD 860 EVO 500GB              | 6         | 1.55%   |
| Kingston SA400S37240G 240GB SSD        | 6         | 1.55%   |
| Seagate ST1000LM048-2E7172 1TB         | 4         | 1.03%   |
| Kingston SA400S37480G 480GB SSD        | 4         | 1.03%   |
| Kingston SA400S37120G 120GB SSD        | 4         | 1.03%   |
| HGST HTS721010A9E630 1TB               | 4         | 1.03%   |
| Crucial CT500MX500SSD1 500GB           | 4         | 1.03%   |
| Crucial CT120BX500SSD1 120GB           | 4         | 1.03%   |
| Unknown SD32G  32GB                    | 3         | 0.78%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.78%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 0.78%   |
| Samsung SSD 980 PRO 1TB                | 3         | 0.78%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.78%   |
| Kingston SV300S37A120G 120GB SSD       | 3         | 0.78%   |
| Intel SSDPEKNW512G8 512GB              | 3         | 0.78%   |
| HGST HTS541010A9E680 1TB               | 3         | 0.78%   |
| Crucial CT480BX500SSD1 480GB           | 3         | 0.78%   |
| Unknown                                | 3         | 0.78%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.52%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 2         | 0.52%   |
| WDC WD5000LPCX-24VHAT0 500GB           | 2         | 0.52%   |
| WDC WD3200BEKT-60PVMT0 320GB           | 2         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.52%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 0.52%   |
| Unknown BJTD4R  32GB                   | 2         | 0.52%   |
| Toshiba MQ01ABD075 752GB               | 2         | 0.52%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 2         | 0.52%   |
| SPCC Solid State Disk 1TB              | 2         | 0.52%   |
| SK hynix HFS128G39TND-N210A 128GB SSD  | 2         | 0.52%   |
| SK hynix HFM512GDJTNI-82A0A 512GB      | 2         | 0.52%   |
| SK hynix HBG4e  32GB                   | 2         | 0.52%   |
| Seagate ST9500325AS 500GB              | 2         | 0.52%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.52%   |
| Seagate ST2000LM003 HN-M201RAD 2TB     | 2         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 0.52%   |
| SanDisk SDSSDA120G 120GB               | 2         | 0.52%   |
| Samsung SSD 860 250GB                  | 2         | 0.52%   |
| Samsung MZVLB512HBJQ-000L7 512GB       | 2         | 0.52%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD    | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 37     | 31.78%  |
| WDC                 | 30        | 30     | 28.04%  |
| Toshiba             | 13        | 14     | 12.15%  |
| Hitachi             | 13        | 14     | 12.15%  |
| HGST                | 11        | 16     | 10.28%  |
| Samsung Electronics | 3         | 4      | 2.8%    |
| Fujitsu             | 2         | 2      | 1.87%   |
| SABRENT             | 1         | 1      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 36     | 17.28%  |
| Kingston            | 21        | 22     | 12.96%  |
| Crucial             | 21        | 36     | 12.96%  |
| SanDisk             | 14        | 16     | 8.64%   |
| SPCC                | 5         | 5      | 3.09%   |
| SK hynix            | 5         | 5      | 3.09%   |
| PNY                 | 5         | 5      | 3.09%   |
| Apple               | 5         | 8      | 3.09%   |
| WDC                 | 4         | 4      | 2.47%   |
| Transcend           | 4         | 4      | 2.47%   |
| Toshiba             | 4         | 4      | 2.47%   |
| Netac               | 3         | 3      | 1.85%   |
| Micron Technology   | 3         | 7      | 1.85%   |
| LITEON              | 3         | 3      | 1.85%   |
| Intel               | 3         | 6      | 1.85%   |
| Dogfish             | 3         | 3      | 1.85%   |
| A-DATA Technology   | 3         | 5      | 1.85%   |
| Patriot             | 2         | 2      | 1.23%   |
| KingSpec            | 2         | 2      | 1.23%   |
| KingDian            | 2         | 2      | 1.23%   |
| Indilinx            | 2         | 4      | 1.23%   |
| Corsair             | 2         | 2      | 1.23%   |
| ZTC                 | 1         | 1      | 0.62%   |
| Yeyian              | 1         | 1      | 0.62%   |
| Team                | 1         | 1      | 0.62%   |
| SWORDBILL           | 1         | 2      | 0.62%   |
| Smart               | 1         | 1      | 0.62%   |
| RENICE              | 1         | 1      | 0.62%   |
| Phison              | 1         | 1      | 0.62%   |
| OCZ                 | 1         | 1      | 0.62%   |
| LITEONIT            | 1         | 1      | 0.62%   |
| KingFast            | 1         | 1      | 0.62%   |
| Intenso             | 1         | 1      | 0.62%   |
| Hewlett-Packard     | 1         | 1      | 0.62%   |
| GOODRAM             | 1         | 1      | 0.62%   |
| Gigabyte Technology | 1         | 1      | 0.62%   |
| GeIL                | 1         | 1      | 0.62%   |
| CT500MX5            | 1         | 1      | 0.62%   |
| Apacer              | 1         | 1      | 0.62%   |
| Unknown             | 1         | 1      | 0.62%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 142       | 203    | 40.92%  |
| HDD     | 105       | 118    | 30.26%  |
| NVMe    | 72        | 93     | 20.75%  |
| MMC     | 27        | 33     | 7.78%   |
| Unknown | 1         | 1      | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 213       | 318    | 67.41%  |
| NVMe | 72        | 93     | 22.78%  |
| MMC  | 27        | 33     | 8.54%   |
| SAS  | 4         | 4      | 1.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 182       | 241    | 75.83%  |
| 0.51-1.0   | 54        | 76     | 22.5%   |
| 1.01-2.0   | 3         | 3      | 1.25%   |
| 3.01-4.0   | 1         | 1      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 93        | 31%     |
| 251-500        | 59        | 19.67%  |
| 501-1000       | 42        | 14%     |
| 51-100         | 37        | 12.33%  |
| 21-50          | 29        | 9.67%   |
| 1-20           | 18        | 6%      |
| 1001-2000      | 13        | 4.33%   |
| More than 3000 | 4         | 1.33%   |
| 2001-3000      | 3         | 1%      |
| Unknown        | 2         | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 130       | 42.21%  |
| 21-50          | 48        | 15.58%  |
| 51-100         | 46        | 14.94%  |
| 101-250        | 36        | 11.69%  |
| 251-500        | 25        | 8.12%   |
| 501-1000       | 13        | 4.22%   |
| 1001-2000      | 5         | 1.62%   |
| More than 3000 | 2         | 0.65%   |
| Unknown        | 2         | 0.65%   |
| 2001-3000      | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 3         | 3      | 6.25%   |
| Seagate ST9500325AS 500GB                    | 2         | 2      | 4.17%   |
| Indilinx IND-S325S120G 120GB SSD             | 2         | 4      | 4.17%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 2.08%   |
| WDC WD5000BPVT-60HXZT3 500GB                 | 1         | 1      | 2.08%   |
| WDC WD3200LPVX-22V0TT0 320GB                 | 1         | 1      | 2.08%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 2.08%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 2.08%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1         | 1      | 2.08%   |
| WDC WD1600BEVT-22A23T0 160GB                 | 1         | 1      | 2.08%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD         | 1         | 1      | 2.08%   |
| Toshiba MK7575GSX 752GB                      | 1         | 2      | 2.08%   |
| Toshiba MK5059GSXP 500GB                     | 1         | 1      | 2.08%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 2.08%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 2.08%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 2.08%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 2.08%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 2.08%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 2.08%   |
| Seagate ST320LT007-9ZV142 320GB              | 1         | 1      | 2.08%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 1         | 1      | 2.08%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 2.08%   |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 1      | 2.08%   |
| Samsung Electronics HS122JC 120GB            | 1         | 2      | 2.08%   |
| RENICE X2 64GB SSD                           | 1         | 1      | 2.08%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 2.08%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 1      | 2.08%   |
| Intel SSDPEKKF512G8L 512GB                   | 1         | 2      | 2.08%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 2.08%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 2.08%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 2.08%   |
| Hitachi HTS543216L9SA02 160GB                | 1         | 1      | 2.08%   |
| Hitachi HTS543216L9SA00 160GB                | 1         | 1      | 2.08%   |
| Hitachi HTS542516K9SA00 160GB                | 1         | 1      | 2.08%   |
| Hitachi HTS541080G9SA00 80GB                 | 1         | 1      | 2.08%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 2.08%   |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 2.08%   |
| HGST HTS545050A7E680 500GB                   | 1         | 2      | 2.08%   |
| HGST HTS545032A7E380 320GB                   | 1         | 1      | 2.08%   |
| HGST HTS541010A9E680 1TB                     | 1         | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 22.92%  |
| WDC                 | 7         | 7      | 14.58%  |
| Hitachi             | 7         | 7      | 14.58%  |
| HGST                | 5         | 6      | 10.42%  |
| Toshiba             | 4         | 5      | 8.33%   |
| Samsung Electronics | 3         | 4      | 6.25%   |
| Kingston            | 2         | 2      | 4.17%   |
| Indilinx            | 2         | 4      | 4.17%   |
| Crucial             | 2         | 5      | 4.17%   |
| SanDisk             | 1         | 1      | 2.08%   |
| RENICE              | 1         | 1      | 2.08%   |
| Intel               | 1         | 2      | 2.08%   |
| Fujitsu             | 1         | 1      | 2.08%   |
| A-DATA Technology   | 1         | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 31.43%  |
| WDC                 | 7         | 7      | 20%     |
| Hitachi             | 7         | 7      | 20%     |
| HGST                | 5         | 6      | 14.29%  |
| Toshiba             | 3         | 4      | 8.57%   |
| Samsung Electronics | 1         | 2      | 2.86%   |
| Fujitsu             | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 38     | 72.92%  |
| SSD  | 12        | 17     | 25%     |
| NVMe | 1         | 2      | 2.08%   |

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
| Works    | 234       | 350    | 73.82%  |
| Malfunc  | 47        | 57     | 14.83%  |
| Detected | 36        | 41     | 11.36%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 208       | 65.2%   |
| AMD                          | 31        | 9.72%   |
| Samsung Electronics          | 23        | 7.21%   |
| SanDisk                      | 11        | 3.45%   |
| SK hynix                     | 10        | 3.13%   |
| Nvidia                       | 6         | 1.88%   |
| KIOXIA                       | 6         | 1.88%   |
| Kingston Technology Company  | 6         | 1.88%   |
| Toshiba America Info Systems | 4         | 1.25%   |
| Phison Electronics           | 4         | 1.25%   |
| Micron Technology            | 3         | 0.94%   |
| Micron/Crucial Technology    | 2         | 0.63%   |
| Silicon Motion               | 1         | 0.31%   |
| Silicon Image                | 1         | 0.31%   |
| Marvell Technology Group     | 1         | 0.31%   |
| Lite-On Technology           | 1         | 0.31%   |
| Lenovo                       | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 29        | 8.5%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 7.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 23        | 6.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 21        | 6.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 13        | 3.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9         | 2.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 2.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 2.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 2.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 2.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 2.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 2.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.76%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 1.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 1.76%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 5         | 1.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 1.47%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 5         | 1.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 1.47%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 1.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.17%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 1.17%   |
| Intel SSD 660P Series                                                            | 4         | 1.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 1.17%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.88%   |
| SK hynix BC511                                                                   | 3         | 0.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 0.88%   |
| SanDisk NVMe Controller                                                          | 3         | 0.88%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 0.88%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.88%   |
| Micron NVMe Storage Controller                                                   | 3         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 213       | 65.14%  |
| NVMe | 71        | 21.71%  |
| IDE  | 23        | 7.03%   |
| RAID | 20        | 6.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 244       | 84.43%  |
| AMD    | 45        | 15.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 8         | 2.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 2.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.73%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 1.73%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 5         | 1.73%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 4         | 1.38%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 1.38%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 1.38%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 4         | 1.38%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 4         | 1.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.38%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 4         | 1.38%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 1.04%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 3         | 1.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 1.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.04%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 1.04%   |
| Intel Core i3-4000M CPU @ 2.40GHz           | 3         | 1.04%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 3         | 1.04%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 1.04%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 3         | 1.04%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 1.04%   |
| Intel 12th Gen Core i7-12700H               | 3         | 1.04%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 3         | 1.04%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.69%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 2         | 0.69%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 0.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 0.69%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 2         | 0.69%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 0.69%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 2         | 0.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 0.69%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 2         | 0.69%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 2         | 0.69%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 2         | 0.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.69%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 67        | 23.18%  |
| Intel Core i7           | 64        | 22.15%  |
| Intel Celeron           | 27        | 9.34%   |
| Intel Core i3           | 23        | 7.96%   |
| Other                   | 19        | 6.57%   |
| Intel Atom              | 15        | 5.19%   |
| Intel Core 2 Duo        | 13        | 4.5%    |
| AMD Ryzen 7             | 11        | 3.81%   |
| AMD Ryzen 5             | 7         | 2.42%   |
| Intel Pentium           | 5         | 1.73%   |
| AMD A6                  | 4         | 1.38%   |
| Intel Pentium Dual-Core | 3         | 1.04%   |
| AMD Turion 64 X2 Mobile | 3         | 1.04%   |
| AMD Ryzen 3             | 3         | 1.04%   |
| AMD E1                  | 3         | 1.04%   |
| AMD E                   | 3         | 1.04%   |
| AMD A8                  | 3         | 1.04%   |
| Intel Pentium M         | 2         | 0.69%   |
| Intel Core 2            | 2         | 0.69%   |
| AMD Ryzen 9             | 2         | 0.69%   |
| AMD A4                  | 2         | 0.69%   |
| Intel Pentium Silver    | 1         | 0.35%   |
| Intel Genuine           | 1         | 0.35%   |
| Intel Core Duo          | 1         | 0.35%   |
| Intel Celeron M         | 1         | 0.35%   |
| AMD Sempron             | 1         | 0.35%   |
| AMD E2                  | 1         | 0.35%   |
| AMD Athlon 64 X2        | 1         | 0.35%   |
| AMD A10                 | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 161       | 55.71%  |
| 4      | 83        | 28.72%  |
| 6      | 15        | 5.19%   |
| 8      | 14        | 4.84%   |
| 1      | 12        | 4.15%   |
| 14     | 3         | 1.04%   |
| 10     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 289       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 201       | 69.55%  |
| 1      | 88        | 30.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 279       | 96.21%  |
| 32-bit         | 11        | 3.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 10.85%  |
| 0x206a7    | 25        | 8.47%   |
| 0x306a9    | 22        | 7.46%   |
| 0x406e3    | 15        | 5.08%   |
| 0x806c1    | 11        | 3.73%   |
| 0x20655    | 10        | 3.39%   |
| 0x906ea    | 8         | 2.71%   |
| 0x40651    | 8         | 2.71%   |
| 0x306c3    | 8         | 2.71%   |
| 0x1067a    | 8         | 2.71%   |
| 0x806ea    | 7         | 2.37%   |
| 0x806e9    | 7         | 2.37%   |
| 0x506e3    | 7         | 2.37%   |
| 0x306d4    | 7         | 2.37%   |
| 0x0a50000c | 7         | 2.37%   |
| 0x406c4    | 6         | 2.03%   |
| 0x30678    | 6         | 2.03%   |
| 0x806ec    | 5         | 1.69%   |
| 0x706a8    | 5         | 1.69%   |
| 0x20652    | 5         | 1.69%   |
| 0x08608103 | 5         | 1.69%   |
| 0xa0652    | 4         | 1.36%   |
| 0x706a1    | 4         | 1.36%   |
| 0x106c2    | 4         | 1.36%   |
| 0x906e9    | 3         | 1.02%   |
| 0x906a3    | 3         | 1.02%   |
| 0x6fd      | 3         | 1.02%   |
| 0x106ca    | 3         | 1.02%   |
| 0x10676    | 3         | 1.02%   |
| 0x03000027 | 3         | 1.02%   |
| 0x906ed    | 2         | 0.68%   |
| 0x806d1    | 2         | 0.68%   |
| 0x706e5    | 2         | 0.68%   |
| 0x6d8      | 2         | 0.68%   |
| 0x506c9    | 2         | 0.68%   |
| 0x30661    | 2         | 0.68%   |
| 0x106e5    | 2         | 0.68%   |
| 0x08108102 | 2         | 0.68%   |
| 0x0810100b | 2         | 0.68%   |
| 0x07030106 | 2         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 12.8%   |
| SandyBridge      | 30        | 10.38%  |
| IvyBridge        | 25        | 8.65%   |
| Skylake          | 23        | 7.96%   |
| Haswell          | 17        | 5.88%   |
| Westmere         | 16        | 5.54%   |
| Silvermont       | 15        | 5.19%   |
| TigerLake        | 12        | 4.15%   |
| Penryn           | 12        | 4.15%   |
| Goldmont plus    | 9         | 3.11%   |
| Bonnell          | 9         | 3.11%   |
| Zen 3            | 8         | 2.77%   |
| Core             | 7         | 2.42%   |
| Broadwell        | 7         | 2.42%   |
| Unknown          | 7         | 2.42%   |
| Icelake          | 6         | 2.08%   |
| Puma             | 5         | 1.73%   |
| P6               | 5         | 1.73%   |
| Zen+             | 4         | 1.38%   |
| K8 Hammer        | 4         | 1.38%   |
| CometLake        | 4         | 1.38%   |
| Zen              | 3         | 1.04%   |
| K10 Llano        | 3         | 1.04%   |
| Goldmont         | 3         | 1.04%   |
| Excavator        | 3         | 1.04%   |
| Bobcat           | 3         | 1.04%   |
| Alderlake Hybrid | 3         | 1.04%   |
| Zen 2            | 2         | 0.69%   |
| Nehalem          | 2         | 0.69%   |
| Jaguar           | 2         | 0.69%   |
| Tremont          | 1         | 0.35%   |
| Piledriver       | 1         | 0.35%   |
| K8 & K10 hybrid  | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 220       | 62.5%   |
| Nvidia | 69        | 19.6%   |
| AMD    | 63        | 17.9%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 7.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 6.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 4.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 3.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 2.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.44%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.17%   |
| Intel HD Graphics 620                                                                    | 8         | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 2.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 2.17%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 1.9%    |
| Intel HD Graphics 530                                                                    | 7         | 1.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.63%   |
| AMD Lucienne                                                                             | 6         | 1.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.36%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.36%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.08%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.08%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.81%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 3         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.81%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 0.81%   |
| Intel HD Graphics 500                                                                    | 3         | 0.81%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.81%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.81%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.81%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 3         | 0.81%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.54%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 161       | 55.71%  |
| Intel + Nvidia | 46        | 15.92%  |
| 1 x AMD        | 40        | 13.84%  |
| 1 x Nvidia     | 18        | 6.23%   |
| Intel + AMD    | 12        | 4.15%   |
| 2 x AMD        | 7         | 2.42%   |
| AMD + Nvidia   | 4         | 1.38%   |
| 2 x Intel      | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 265       | 90.14%  |
| Proprietary | 20        | 6.8%    |
| Unknown     | 9         | 3.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 218       | 74.4%   |
| 0.01-0.5   | 34        | 11.6%   |
| 1.01-2.0   | 16        | 5.46%   |
| 0.51-1.0   | 16        | 5.46%   |
| 3.01-4.0   | 5         | 1.71%   |
| 7.01-8.0   | 3         | 1.02%   |
| 2.01-3.0   | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 60        | 18.99%  |
| Chimei Innolux          | 49        | 15.51%  |
| LG Display              | 41        | 12.97%  |
| Samsung Electronics     | 33        | 10.44%  |
| BOE                     | 30        | 9.49%   |
| Lenovo                  | 14        | 4.43%   |
| Chi Mei Optoelectronics | 14        | 4.43%   |
| Hewlett-Packard         | 9         | 2.85%   |
| PANDA                   | 8         | 2.53%   |
| Apple                   | 8         | 2.53%   |
| Goldstar                | 5         | 1.58%   |
| Dell                    | 5         | 1.58%   |
| Sharp                   | 4         | 1.27%   |
| LG Philips              | 4         | 1.27%   |
| InfoVision              | 4         | 1.27%   |
| HannStar                | 4         | 1.27%   |
| Ancor Communications    | 4         | 1.27%   |
| Sony                    | 3         | 0.95%   |
| CPT                     | 3         | 0.95%   |
| Philips                 | 2         | 0.63%   |
| Vizio                   | 1         | 0.32%   |
| Sunplus                 | 1         | 0.32%   |
| STA                     | 1         | 0.32%   |
| Panasonic               | 1         | 0.32%   |
| Packard Bell            | 1         | 0.32%   |
| ONN                     | 1         | 0.32%   |
| NEC Computers           | 1         | 0.32%   |
| LTM                     | 1         | 0.32%   |
| InnoLux Display         | 1         | 0.32%   |
| Eizo                    | 1         | 0.32%   |
| AOC                     | 1         | 0.32%   |
| Acer                    | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 1.9%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 1.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 1.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.95%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.95%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.63%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.63%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 2         | 0.63%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.63%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.63%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.63%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.63%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 2         | 0.63%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 2         | 0.63%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                    | 2         | 0.63%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch           | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO01EE 1600x900 344x193mm 15.5-inch            | 2         | 0.63%   |
| Vizio E320VA VIZ0071 1360x768 697x392mm 31.5-inch                        | 1         | 0.32%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 122       | 40.26%  |
| 1366x768 (WXGA)    | 97        | 32.01%  |
| 1600x900 (HD+)     | 16        | 5.28%   |
| 1280x800 (WXGA)    | 13        | 4.29%   |
| 3840x2160 (4K)     | 11        | 3.63%   |
| 1024x600           | 7         | 2.31%   |
| 1920x1200 (WUXGA)  | 5         | 1.65%   |
| 1440x900 (WXGA+)   | 5         | 1.65%   |
| 1680x1050 (WSXGA+) | 4         | 1.32%   |
| 1280x1024 (SXGA)   | 4         | 1.32%   |
| 2880x1800          | 3         | 0.99%   |
| 2560x1440 (QHD)    | 3         | 0.99%   |
| 2560x1080          | 3         | 0.99%   |
| 2560x1600          | 2         | 0.66%   |
| 2160x1440          | 2         | 0.66%   |
| 1400x1050          | 2         | 0.66%   |
| 3840x2400          | 1         | 0.33%   |
| 2256x1504          | 1         | 0.33%   |
| 1360x768           | 1         | 0.33%   |
| 1024x768 (XGA)     | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 130       | 41.27%  |
| 13      | 42        | 13.33%  |
| 14      | 35        | 11.11%  |
| 17      | 25        | 7.94%   |
| 24      | 12        | 3.81%   |
| 11      | 10        | 3.17%   |
| 10      | 9         | 2.86%   |
| 23      | 8         | 2.54%   |
| 12      | 8         | 2.54%   |
| 19      | 5         | 1.59%   |
| 34      | 3         | 0.95%   |
| 27      | 3         | 0.95%   |
| 21      | 3         | 0.95%   |
| 20      | 3         | 0.95%   |
| 16      | 3         | 0.95%   |
| 43      | 2         | 0.63%   |
| 40      | 2         | 0.63%   |
| 32      | 2         | 0.63%   |
| 18      | 2         | 0.63%   |
| Unknown | 2         | 0.63%   |
| 84      | 1         | 0.32%   |
| 46      | 1         | 0.32%   |
| 37      | 1         | 0.32%   |
| 36      | 1         | 0.32%   |
| 26      | 1         | 0.32%   |
| 25      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 184       | 58.6%   |
| 201-300     | 46        | 14.65%  |
| 351-400     | 36        | 11.46%  |
| 501-600     | 24        | 7.64%   |
| 401-500     | 9         | 2.87%   |
| 701-800     | 6         | 1.91%   |
| 801-900     | 3         | 0.96%   |
| 901-1000    | 2         | 0.64%   |
| Unknown     | 2         | 0.64%   |
| 1501-2000   | 1         | 0.32%   |
| 1001-1500   | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 238       | 82.93%  |
| 16/10 | 34        | 11.85%  |
| 3/2   | 5         | 1.74%   |
| 5/4   | 4         | 1.39%   |
| 4/3   | 3         | 1.05%   |
| 21/9  | 3         | 1.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 131       | 41.59%  |
| 81-90          | 63        | 20%     |
| 121-130        | 24        | 7.62%   |
| 201-250        | 18        | 5.71%   |
| 71-80          | 13        | 4.13%   |
| 51-60          | 10        | 3.17%   |
| 41-50          | 9         | 2.86%   |
| 151-200        | 9         | 2.86%   |
| 61-70          | 8         | 2.54%   |
| 501-1000       | 7         | 2.22%   |
| 251-300        | 6         | 1.9%    |
| 351-500        | 5         | 1.59%   |
| 301-350        | 3         | 0.95%   |
| 141-150        | 2         | 0.63%   |
| 111-120        | 2         | 0.63%   |
| Unknown        | 2         | 0.63%   |
| More than 1000 | 1         | 0.32%   |
| 131-140        | 1         | 0.32%   |
| 91-100         | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 120       | 38.83%  |
| 101-120       | 98        | 31.72%  |
| 51-100        | 63        | 20.39%  |
| 161-240       | 18        | 5.83%   |
| More than 240 | 6         | 1.94%   |
| 1-50          | 2         | 0.65%   |
| Unknown       | 2         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 238       | 81.23%  |
| 2     | 44        | 15.02%  |
| 0     | 8         | 2.73%   |
| 3     | 3         | 1.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 156       | 32.91%  |
| Realtek Semiconductor             | 146       | 30.8%   |
| Qualcomm Atheros                  | 75        | 15.82%  |
| Broadcom                          | 28        | 5.91%   |
| MediaTek                          | 8         | 1.69%   |
| TP-Link                           | 7         | 1.48%   |
| Marvell Technology Group          | 7         | 1.48%   |
| Broadcom Limited                  | 7         | 1.48%   |
| Ralink                            | 5         | 1.05%   |
| Nvidia                            | 5         | 1.05%   |
| Sierra Wireless                   | 4         | 0.84%   |
| Huawei Technologies               | 3         | 0.63%   |
| Ericsson Business Mobile Networks | 3         | 0.63%   |
| Ralink Technology                 | 2         | 0.42%   |
| Motorola PCS                      | 2         | 0.42%   |
| Attansic Technology               | 2         | 0.42%   |
| ASIX Electronics                  | 2         | 0.42%   |
| Sweex                             | 1         | 0.21%   |
| Samsung Electronics               | 1         | 0.21%   |
| Qualcomm Atheros Communications   | 1         | 0.21%   |
| Qualcomm                          | 1         | 0.21%   |
| NetGear                           | 1         | 0.21%   |
| Lenovo                            | 1         | 0.21%   |
| JMicron Technology                | 1         | 0.21%   |
| Hewlett-Packard                   | 1         | 0.21%   |
| Google                            | 1         | 0.21%   |
| Dell                              | 1         | 0.21%   |
| D-Link                            | 1         | 0.21%   |
| ASUSTek Computer                  | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 90        | 15.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 26        | 4.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 2.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 1.92%   |
| Intel Wireless 8260                                                     | 11        | 1.92%   |
| Intel Wireless 7260                                                     | 11        | 1.92%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 10        | 1.75%   |
| Intel Wireless 8265 / 8275                                              | 10        | 1.75%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 10        | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 1.57%   |
| Intel Wireless 3165                                                     | 9         | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 1.57%   |
| Intel 82577LM Gigabit Network Connection                                | 8         | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.22%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.05%   |
| Intel Wireless 7265                                                     | 6         | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.87%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.87%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.7%    |
| Intel Ethernet Connection I219-V                                        | 4         | 0.7%    |
| Intel Ethernet Connection I218-LM                                       | 4         | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.7%    |
| Intel Centrino Advanced-N 6235                                          | 4         | 0.7%    |
| Intel 82567LM Gigabit Network Connection                                | 4         | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 3         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 149       | 48.85%  |
| Qualcomm Atheros                | 57        | 18.69%  |
| Realtek Semiconductor           | 44        | 14.43%  |
| Broadcom                        | 20        | 6.56%   |
| MediaTek                        | 7         | 2.3%    |
| TP-Link                         | 6         | 1.97%   |
| Ralink                          | 5         | 1.64%   |
| Broadcom Limited                | 5         | 1.64%   |
| Sierra Wireless                 | 4         | 1.31%   |
| Ralink Technology               | 2         | 0.66%   |
| Sweex                           | 1         | 0.33%   |
| Qualcomm Atheros Communications | 1         | 0.33%   |
| NetGear                         | 1         | 0.33%   |
| Hewlett-Packard                 | 1         | 0.33%   |
| D-Link                          | 1         | 0.33%   |
| ASUSTek Computer                | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 5.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 3.59%   |
| Intel Wireless 8260                                                     | 11        | 3.59%   |
| Intel Wireless 7260                                                     | 11        | 3.59%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 3.59%   |
| Intel Wireless 8265 / 8275                                              | 10        | 3.27%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 3.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.94%   |
| Intel Wireless 3165                                                     | 9         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2.29%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 2.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.96%   |
| Intel Wireless 7265                                                     | 6         | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.31%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.31%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 1.31%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.98%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.98%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.98%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 0.98%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.98%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 129       | 50.79%  |
| Intel                    | 61        | 24.02%  |
| Qualcomm Atheros         | 28        | 11.02%  |
| Broadcom                 | 10        | 3.94%   |
| Marvell Technology Group | 7         | 2.76%   |
| Nvidia                   | 5         | 1.97%   |
| Broadcom Limited         | 2         | 0.79%   |
| Attansic Technology      | 2         | 0.79%   |
| ASIX Electronics         | 2         | 0.79%   |
| TP-Link                  | 1         | 0.39%   |
| Samsung Electronics      | 1         | 0.39%   |
| Qualcomm                 | 1         | 0.39%   |
| Motorola PCS             | 1         | 0.39%   |
| MediaTek                 | 1         | 0.39%   |
| Lenovo                   | 1         | 0.39%   |
| JMicron Technology       | 1         | 0.39%   |
| Huawei Technologies      | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 90        | 35.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 26        | 10.12%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 3.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 3.89%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 3.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.95%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.95%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.56%   |
| Intel Ethernet Connection I219-V                                               | 4         | 1.56%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.56%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 1.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 1.17%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 1.17%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.17%   |
| Intel Ethernet Connection (5) I219-LM                                          | 3         | 1.17%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.17%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.78%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.78%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.78%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.78%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.78%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.78%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 0.78%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.78%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.78%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.39%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.39%   |
| Qualcomm Fairphone 4 5G                                                        | 1         | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 281       | 52.62%  |
| Ethernet | 244       | 45.69%  |
| Modem    | 7         | 1.31%   |
| Unknown  | 2         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 230       | 77.44%  |
| Ethernet | 66        | 22.22%  |
| Unknown  | 1         | 0.34%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 228       | 78.62%  |
| 1     | 53        | 18.28%  |
| 0     | 7         | 2.41%   |
| 3     | 2         | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 238       | 81.51%  |
| Yes  | 54        | 18.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 45.58%  |
| Qualcomm Atheros Communications | 22        | 9.73%   |
| Realtek Semiconductor           | 20        | 8.85%   |
| Broadcom                        | 20        | 8.85%   |
| Lite-On Technology              | 9         | 3.98%   |
| IMC Networks                    | 9         | 3.98%   |
| Cambridge Silicon Radio         | 9         | 3.98%   |
| Apple                           | 8         | 3.54%   |
| Foxconn / Hon Hai               | 7         | 3.1%    |
| Hewlett-Packard                 | 6         | 2.65%   |
| Toshiba                         | 3         | 1.33%   |
| Ralink                          | 3         | 1.33%   |
| Dell                            | 3         | 1.33%   |
| Alps Electric                   | 2         | 0.88%   |
| MediaTek                        | 1         | 0.44%   |
| ASUSTek Computer                | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 47        | 20.8%   |
| Intel AX201 Bluetooth                                                               | 17        | 7.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 13        | 5.75%   |
| Realtek Bluetooth Radio                                                             | 12        | 5.31%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 4.87%   |
| Intel AX200 Bluetooth                                                               | 11        | 4.87%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 3.98%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.65%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 2.65%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.21%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.77%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 1.77%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.77%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 1.77%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 1.77%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 1.77%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 4         | 1.77%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.33%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 1.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.33%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.33%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.88%   |
| Lite-On Wireless_Device                                                             | 2         | 0.88%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.88%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.88%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.88%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.88%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.88%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 0.88%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.44%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.44%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.44%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.44%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.44%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.44%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.44%   |
| MediaTek Wireless_Device                                                            | 1         | 0.44%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 234       | 66.29%  |
| AMD                     | 50        | 14.16%  |
| Nvidia                  | 49        | 13.88%  |
| Realtek Semiconductor   | 2         | 0.57%   |
| GN Netcom               | 2         | 0.57%   |
| C-Media Electronics     | 2         | 0.57%   |
| VIA Technologies        | 1         | 0.28%   |
| Texas Instruments       | 1         | 0.28%   |
| SteelSeries ApS         | 1         | 0.28%   |
| Plantronics             | 1         | 0.28%   |
| Mark of the Unicorn     | 1         | 0.28%   |
| Logitech                | 1         | 0.28%   |
| Lenovo                  | 1         | 0.28%   |
| Guillemot               | 1         | 0.28%   |
| Generalplus Technology  | 1         | 0.28%   |
| Focusrite-Novation      | 1         | 0.28%   |
| FIFINE 683 Microphone   | 1         | 0.28%   |
| Conexant Systems        | 1         | 0.28%   |
| CMX Systems             | 1         | 0.28%   |
| BEHRINGER International | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 32        | 7.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 7.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 5.54%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 23        | 5.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 18        | 4.34%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 3.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 3.13%   |
| AMD FCH Azalia Controller                                                                         | 12        | 2.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 2.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 2.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 1.93%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.93%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.69%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 1.2%    |
| Nvidia Audio device                                                                               | 5         | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.2%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.96%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.96%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 0.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.72%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 84        | 23.86%  |
| SK hynix            | 81        | 23.01%  |
| Unknown             | 37        | 10.51%  |
| Micron Technology   | 37        | 10.51%  |
| Kingston            | 33        | 9.38%   |
| Crucial             | 17        | 4.83%   |
| Ramaxel Technology  | 9         | 2.56%   |
| A-DATA Technology   | 8         | 2.27%   |
| Unknown (ABCD)      | 7         | 1.99%   |
| Elpida              | 7         | 1.99%   |
| Transcend           | 4         | 1.14%   |
| Smart               | 4         | 1.14%   |
| Corsair             | 4         | 1.14%   |
| Nanya Technology    | 3         | 0.85%   |
| Teikon              | 2         | 0.57%   |
| Team                | 2         | 0.57%   |
| Unknown             | 2         | 0.57%   |
| Unknown (F301)      | 1         | 0.28%   |
| TRS STAR            | 1         | 0.28%   |
| PNY                 | 1         | 0.28%   |
| Patriot             | 1         | 0.28%   |
| Innodisk            | 1         | 0.28%   |
| High Bridge         | 1         | 0.28%   |
| Hewlett-Packard     | 1         | 0.28%   |
| Avant               | 1         | 0.28%   |
| ASint Technology    | 1         | 0.28%   |
| Apacer              | 1         | 0.28%   |
| 48spaces            | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 1.58%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.58%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.58%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 1.32%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.32%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 1.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.32%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.32%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.05%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.05%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 4         | 1.05%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 1.05%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.79%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 3         | 0.79%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 0.79%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 3         | 0.79%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.79%   |
| Samsung RAM M471B5273BH1-CF8 4096MB SODIMM DDR3 1067MT/s         | 3         | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.79%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 0.79%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.53%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.53%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 2         | 0.53%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 2         | 0.53%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.53%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.53%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 2         | 0.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.53%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 2         | 0.53%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 142       | 48.3%   |
| DDR4    | 102       | 34.69%  |
| DDR2    | 17        | 5.78%   |
| LPDDR4  | 12        | 4.08%   |
| SDRAM   | 6         | 2.04%   |
| DDR     | 6         | 2.04%   |
| LPDDR3  | 4         | 1.36%   |
| DRAM    | 3         | 1.02%   |
| DDR5    | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 275       | 93.86%  |
| Row Of Chips | 12        | 4.1%    |
| Chip         | 3         | 1.02%   |
| DIMM         | 2         | 0.68%   |
| Unknown      | 1         | 0.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 120       | 37.04%  |
| 8192  | 99        | 30.56%  |
| 2048  | 56        | 17.28%  |
| 16384 | 30        | 9.26%   |
| 1024  | 15        | 4.63%   |
| 32768 | 3         | 0.93%   |
| 512   | 1         | 0.31%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 89        | 27.64%  |
| 2667    | 40        | 12.42%  |
| 3200    | 38        | 11.8%   |
| 1334    | 30        | 9.32%   |
| 2400    | 27        | 8.39%   |
| 1333    | 19        | 5.9%    |
| Unknown | 18        | 5.59%   |
| 667     | 12        | 3.73%   |
| 2133    | 11        | 3.42%   |
| 1067    | 9         | 2.8%    |
| 4199    | 5         | 1.55%   |
| 1867    | 4         | 1.24%   |
| 800     | 4         | 1.24%   |
| 4267    | 3         | 0.93%   |
| 3266    | 3         | 0.93%   |
| 533     | 3         | 0.93%   |
| 8400    | 2         | 0.62%   |
| 4800    | 1         | 0.31%   |
| 4266    | 1         | 0.31%   |
| 2933    | 1         | 0.31%   |
| 666     | 1         | 0.31%   |
| 166     | 1         | 0.31%   |

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
| Chicony Electronics                    | 61        | 25.42%  |
| Acer                                   | 22        | 9.17%   |
| Realtek Semiconductor                  | 21        | 8.75%   |
| Microdia                               | 19        | 7.92%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 6.67%   |
| Sunplus Innovation Technology          | 14        | 5.83%   |
| IMC Networks                           | 14        | 5.83%   |
| Quanta                                 | 10        | 4.17%   |
| Suyin                                  | 9         | 3.75%   |
| Lite-On Technology                     | 9         | 3.75%   |
| Lenovo                                 | 8         | 3.33%   |
| Ricoh                                  | 5         | 2.08%   |
| Apple                                  | 5         | 2.08%   |
| Z-Star Microelectronics                | 3         | 1.25%   |
| Syntek                                 | 3         | 1.25%   |
| Silicon Motion                         | 3         | 1.25%   |
| Luxvisions Innotech Limited            | 3         | 1.25%   |
| Alcor Micro                            | 3         | 1.25%   |
| Y Media                                | 1         | 0.42%   |
| Xiongmai                               | 1         | 0.42%   |
| WaveRider Communications               | 1         | 0.42%   |
| USB Camera                             | 1         | 0.42%   |
| Samsung Electronics                    | 1         | 0.42%   |
| Primax Electronics                     | 1         | 0.42%   |
| Novatek Microelectronics               | 1         | 0.42%   |
| Logitech                               | 1         | 0.42%   |
| Importek                               | 1         | 0.42%   |
| Goodong Industry                       | 1         | 0.42%   |
| Cubeternet                             | 1         | 0.42%   |
| Bison Electronics                      | 1         | 0.42%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 14        | 5.81%   |
| Realtek Integrated_Webcam_HD                                | 7         | 2.9%    |
| Microdia Integrated_Webcam_HD                               | 6         | 2.49%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 2.49%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 2.07%   |
| Lite-On Integrated Camera                                   | 5         | 2.07%   |
| Lenovo Integrated Webcam [R5U877]                           | 4         | 1.66%   |
| Chicony USB 2.0 Camera                                      | 4         | 1.66%   |
| Chicony TOSHIBA Web Camera - HD                             | 4         | 1.66%   |
| Chicony HP TrueVision HD Camera                             | 4         | 1.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 4         | 1.66%   |
| Acer Integrated Camera                                      | 4         | 1.66%   |
| Syntek EasyCamera                                           | 3         | 1.24%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 3         | 1.24%   |
| Sunplus ASUS Webcam                                         | 3         | 1.24%   |
| Ricoh USB2.0 Camera                                         | 3         | 1.24%   |
| Realtek USB Camera                                          | 3         | 1.24%   |
| Quanta HD User Facing                                       | 3         | 1.24%   |
| Lenovo Integrated Webcam                                    | 3         | 1.24%   |
| IMC Networks Integrated Camera                              | 3         | 1.24%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 1.24%   |
| Chicony HD WebCam                                           | 3         | 1.24%   |
| Chicony HD User Facing                                      | 3         | 1.24%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 3         | 1.24%   |
| Acer HD Webcam                                              | 3         | 1.24%   |
| Acer BisonCam,NB Pro                                        | 3         | 1.24%   |
| Acer BisonCam, NB Pro                                       | 3         | 1.24%   |
| Sunplus HD WebCam                                           | 2         | 0.83%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 0.83%   |
| Quanta VGA WebCam                                           | 2         | 0.83%   |
| Quanta HP Wide Vision HD Camera                             | 2         | 0.83%   |
| Microdia Webcam Vitade AF                                   | 2         | 0.83%   |
| Microdia USB 2.0 Camera                                     | 2         | 0.83%   |
| Microdia Integrated Webcam                                  | 2         | 0.83%   |
| Lite-On HP HD Camera                                        | 2         | 0.83%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 0.83%   |
| Chicony VGA Webcam                                          | 2         | 0.83%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 0.83%   |
| Chicony HP Webcam [2 MP Macro]                              | 2         | 0.83%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 34%     |
| Synaptics                  | 10        | 20%     |
| Upek                       | 7         | 14%     |
| Shenzhen Goodix Technology | 6         | 12%     |
| AuthenTec                  | 6         | 12%     |
| LighTuning Technology      | 2         | 4%      |
| STMicroelectronics         | 1         | 2%      |
| Elan Microelectronics      | 1         | 2%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 5         | 10%     |
| Shenzhen Goodix  FingerPrint Device                        | 5         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 8%      |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 8%      |
| Validity Sensors Synaptics WBDI                            | 3         | 6%      |
| AuthenTec AES2810                                          | 3         | 6%      |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 4%      |
| Upek TCS5B Fingerprint sensor                              | 2         | 4%      |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4%      |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 4%      |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 2%      |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 2%      |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 2%      |
| Validity Sensors Fingerprint scanner                       | 1         | 2%      |
| Synaptics UWP WBDI Device                                  | 1         | 2%      |
| Synaptics UWP WBDI                                         | 1         | 2%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 2%      |
| STMicroelectronics Fingerprint Reader                      | 1         | 2%      |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 2%      |
| LighTuning Fingerprint Reader                              | 1         | 2%      |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 2%      |
| Elan ELAN:Fingerprint                                      | 1         | 2%      |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2%      |
| Unknown                                                    | 1         | 2%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 9         | 39.13%  |
| Broadcom              | 8         | 34.78%  |
| Lenovo                | 3         | 13.04%  |
| Advanced Card Systems | 2         | 8.7%    |
| O2 Micro              | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 39.13%  |
| Broadcom 5880                                                                | 5         | 21.74%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 13.04%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 8.7%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.35%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 4.35%   |
| Advanced Card Systems ACR122U                                                | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 180       | 60.61%  |
| 1     | 86        | 28.96%  |
| 2     | 29        | 9.76%   |
| 3     | 2         | 0.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 59        | 40.41%  |
| Fingerprint reader       | 50        | 34.25%  |
| Chipcard                 | 20        | 13.7%   |
| Multimedia controller    | 5         | 3.42%   |
| Storage                  | 3         | 2.05%   |
| Net/wireless             | 2         | 1.37%   |
| Communication controller | 2         | 1.37%   |
| Camera                   | 2         | 1.37%   |
| Bluetooth                | 2         | 1.37%   |
| Net/ethernet             | 1         | 0.68%   |

