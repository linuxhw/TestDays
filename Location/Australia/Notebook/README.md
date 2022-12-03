Linux in Australia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

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

Total: 1871

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| AMI           | Intel                       | [3e2e312c6e](https://linux-hardware.org/?probe=3e2e312c6e) | Nov 29, 2022 |
| Razer         | Blade                       | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3433fd5db6](https://linux-hardware.org/?probe=3433fd5db6) | Nov 28, 2022 |
| Apple         | MacBookAir6,2               | [ed4692d2a7](https://linux-hardware.org/?probe=ed4692d2a7) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Latitude E7440              | [3709af0366](https://linux-hardware.org/?probe=3709af0366) | Nov 27, 2022 |
| Apple         | MacBookPro15,2              | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| Kogan         | KAL11C250SB                 | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| Razer         | Blade Pro                   | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Acer          | Aspire R3-131T              | [5395a2556c](https://linux-hardware.org/?probe=5395a2556c) | Nov 24, 2022 |
| Acer          | ConceptD CN315-71P          | [db3ccac179](https://linux-hardware.org/?probe=db3ccac179) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | [62c77a0e63](https://linux-hardware.org/?probe=62c77a0e63) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | [06c02ff303](https://linux-hardware.org/?probe=06c02ff303) | Nov 21, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [06a337fda3](https://linux-hardware.org/?probe=06a337fda3) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [965d9d2f5c](https://linux-hardware.org/?probe=965d9d2f5c) | Nov 20, 2022 |
| MSI           | GP62M 7REX                  | [2125546b68](https://linux-hardware.org/?probe=2125546b68) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | [6ea684de8c](https://linux-hardware.org/?probe=6ea684de8c) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [2cb56b8c63](https://linux-hardware.org/?probe=2cb56b8c63) | Nov 17, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| AMI           | Intel                       | [ac36a02403](https://linux-hardware.org/?probe=ac36a02403) | Nov 16, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [66737bb1cc](https://linux-hardware.org/?probe=66737bb1cc) | Nov 15, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [ccbda507a9](https://linux-hardware.org/?probe=ccbda507a9) | Nov 14, 2022 |
| ASUSTek       | X550CC                      | [d37b8f7bbd](https://linux-hardware.org/?probe=d37b8f7bbd) | Nov 13, 2022 |
| Acer          | ConceptD CN315-71P          | [2d3a3f4ac8](https://linux-hardware.org/?probe=2d3a3f4ac8) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [755a70132f](https://linux-hardware.org/?probe=755a70132f) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [4371465097](https://linux-hardware.org/?probe=4371465097) | Nov 12, 2022 |
| HP            | Pavilion Notebook           | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| MSI           | GS60 6QE                    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Toshiba       | TECRA A40-D                 | [ab2d9e2712](https://linux-hardware.org/?probe=ab2d9e2712) | Nov 11, 2022 |
| Acer          | Aspire A315-22              | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad T420 4180PEM       | [ad4d7f338d](https://linux-hardware.org/?probe=ad4d7f338d) | Nov 09, 2022 |
| HP            | ProBook 640 G1              | [3189f08179](https://linux-hardware.org/?probe=3189f08179) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| Dell          | XPS 13 9310                 | [5f358af327](https://linux-hardware.org/?probe=5f358af327) | Nov 08, 2022 |
| MSI           | GS60 6QE                    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| ASUSTek       | K53E                        | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| Dell          | Latitude E6430              | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Toshiba       | Satellite L500              | [0d6bb9cde0](https://linux-hardware.org/?probe=0d6bb9cde0) | Nov 05, 2022 |
| Toshiba       | Satellite L500              | [3d7692d178](https://linux-hardware.org/?probe=3d7692d178) | Nov 05, 2022 |
| MSI           | Katana GF76 12UC            | [3cb05bdb95](https://linux-hardware.org/?probe=3cb05bdb95) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [cc28dc5c8b](https://linux-hardware.org/?probe=cc28dc5c8b) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| ASUSTek       | 1005HA                      | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Cube          | i18-BL                      | [725100a829](https://linux-hardware.org/?probe=725100a829) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| HP            | Notebook                    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| Acer          | Aspire 3000                 | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| ASUSTek       | X501A                       | [d5a34df414](https://linux-hardware.org/?probe=d5a34df414) | Nov 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [c3ea4065c4](https://linux-hardware.org/?probe=c3ea4065c4) | Oct 29, 2022 |
| ASUSTek       | U50Vg                       | [5f2997ec95](https://linux-hardware.org/?probe=5f2997ec95) | Oct 28, 2022 |
| HP            | ProBook 640 G1              | [b096155d39](https://linux-hardware.org/?probe=b096155d39) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | G71                         | [3223e2fcc8](https://linux-hardware.org/?probe=3223e2fcc8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| Apple         | MacBookAir7,2               | [6f72d6443c](https://linux-hardware.org/?probe=6f72d6443c) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Notebook      | W650EH                      | [6bb1a8b1f1](https://linux-hardware.org/?probe=6bb1a8b1f1) | Oct 23, 2022 |
| Purism        | Librem 13 v2                | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire 5600                 | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5086e64fed](https://linux-hardware.org/?probe=5086e64fed) | Oct 19, 2022 |
| Dell          | Inspiron M5010              | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| HP            | G71                         | [46b6033e1e](https://linux-hardware.org/?probe=46b6033e1e) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Dell          | Inspiron 1545               | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| System76      | Galago Pro                  | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5f0c4b3acb](https://linux-hardware.org/?probe=5f0c4b3acb) | Oct 13, 2022 |
| Apple         | MacBookPro15,2              | [705e4f406a](https://linux-hardware.org/?probe=705e4f406a) | Oct 13, 2022 |
| HP            | EliteBook 8540p             | [cd65876f22](https://linux-hardware.org/?probe=cd65876f22) | Oct 12, 2022 |
| Apple         | MacBookPro15,2              | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| Dell          | Inspiron 16 5620            | [72151cd0e8](https://linux-hardware.org/?probe=72151cd0e8) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| HP            | ProBook 470 G5              | [a7b96649da](https://linux-hardware.org/?probe=a7b96649da) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| Apple         | MacBookAir7,2               | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| HP            | Presario V4000 (EQ608PA#... | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| Dell          | XPS 15 9510                 | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Gigabyte      | AORUS 7 SB                  | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| Acer          | TravelMate 8572T            | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |
| Dell          | Inspiron 15 7510            | [521636075a](https://linux-hardware.org/?probe=521636075a) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Acer          | TravelMate 8572T            | [927bf01e34](https://linux-hardware.org/?probe=927bf01e34) | Sep 30, 2022 |
| Gigabyte      | AORUS 17 YE5                | [54b271c3fd](https://linux-hardware.org/?probe=54b271c3fd) | Sep 30, 2022 |
| Acer          | Aspire 5742G                | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [ac3079df8c](https://linux-hardware.org/?probe=ac3079df8c) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [144cad649c](https://linux-hardware.org/?probe=144cad649c) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| Dell          | Latitude E7450              | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| Gigabyte      | P34V7                       | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| System76      | Galago Pro                  | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| Dell          | G15 5511                    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| HP            | Pavilion dv6                | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| Acer          | TMP645-M                    | [83b27c389c](https://linux-hardware.org/?probe=83b27c389c) | Sep 23, 2022 |
| Dell          | Precision 7760              | [f47fe0314b](https://linux-hardware.org/?probe=f47fe0314b) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [a01352810a](https://linux-hardware.org/?probe=a01352810a) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Apple         | MacBookPro8,1               | [d97b8fc0ed](https://linux-hardware.org/?probe=d97b8fc0ed) | Sep 21, 2022 |
| Apple         | MacBookPro10,2              | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| ASUSTek       | 1005HA                      | [3b5d6a5b1d](https://linux-hardware.org/?probe=3b5d6a5b1d) | Sep 18, 2022 |
| ASUSTek       | 1005HA                      | [3b1ce0471e](https://linux-hardware.org/?probe=3b1ce0471e) | Sep 18, 2022 |
| Lenovo        | V310-15ISK 80SY             | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Acer          | Aspire A315-42              | [6121dfd67d](https://linux-hardware.org/?probe=6121dfd67d) | Sep 13, 2022 |
| HP            | ENVY 15                     | [fdb07294df](https://linux-hardware.org/?probe=fdb07294df) | Sep 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Dell          | Latitude E7470              | [4a2f647549](https://linux-hardware.org/?probe=4a2f647549) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| HP            | Pavilion dv6500             | [c37bace401](https://linux-hardware.org/?probe=c37bace401) | Sep 05, 2022 |
| Dell          | XPS 13 9350                 | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Lenovo        | Z50-70 20354                | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| HP            | Notebook                    | [ee135c3930](https://linux-hardware.org/?probe=ee135c3930) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| HP            | EliteBook 830 G6            | [897046248f](https://linux-hardware.org/?probe=897046248f) | Aug 30, 2022 |
| Lenovo        | V14-ADA 82C6                | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| IT Channel... | NH5xAx                      | [66573b4b48](https://linux-hardware.org/?probe=66573b4b48) | Aug 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Acer          | Aspire V5-531               | [75b841b0b8](https://linux-hardware.org/?probe=75b841b0b8) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Dell          | Latitude 5300               | [f336b3aeaf](https://linux-hardware.org/?probe=f336b3aeaf) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Acer          | Aspire V5-531               | [4ae228e219](https://linux-hardware.org/?probe=4ae228e219) | Aug 25, 2022 |
| Dell          | XPS 13 7390                 | [d609bf3253](https://linux-hardware.org/?probe=d609bf3253) | Aug 24, 2022 |
| Alienware     | 15 R4                       | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Apple         | MacBook9,1                  | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Samsung       | 550P5C/550P7C               | [75f94f8fa5](https://linux-hardware.org/?probe=75f94f8fa5) | Aug 21, 2022 |
| Samsung       | 550P5C/550P7C               | [c369daf6b0](https://linux-hardware.org/?probe=c369daf6b0) | Aug 21, 2022 |
| ASUSTek       | X756UAK                     | [6db3b2a7bc](https://linux-hardware.org/?probe=6db3b2a7bc) | Aug 20, 2022 |
| Dell          | G3 3779                     | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Dell          | Inspiron M5010              | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Apple         | MacBookAir6,2               | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Toshiba       | Satellite L500              | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [662f0801b7](https://linux-hardware.org/?probe=662f0801b7) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Dell          | Latitude 6430U              | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| HP            | ProBook 430 G5              | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [209cd4bc66](https://linux-hardware.org/?probe=209cd4bc66) | Aug 05, 2022 |
| Acer          | Nitro AN515-52              | [8b737740c3](https://linux-hardware.org/?probe=8b737740c3) | Aug 05, 2022 |
| Acer          | Aspire A515-55              | [3ef0714d78](https://linux-hardware.org/?probe=3ef0714d78) | Aug 04, 2022 |
| Toshiba       | Satellite Pro L670          | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| Dell          | XPS 9320                    | [9b24b29553](https://linux-hardware.org/?probe=9b24b29553) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | EliteBook 2570p             | [b352b7e051](https://linux-hardware.org/?probe=b352b7e051) | Aug 02, 2022 |
| Apple         | MacBook9,1                  | [77687a9bac](https://linux-hardware.org/?probe=77687a9bac) | Aug 02, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| Acer          | ConceptD CN315-71P          | [c7ed484a1f](https://linux-hardware.org/?probe=c7ed484a1f) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire 5742G                | [e42501aacb](https://linux-hardware.org/?probe=e42501aacb) | Jul 28, 2022 |
| ASUSTek       | X555YA                      | [ddd00fbeea](https://linux-hardware.org/?probe=ddd00fbeea) | Jul 28, 2022 |
| Dell          | Latitude E7250              | [26a8591f1d](https://linux-hardware.org/?probe=26a8591f1d) | Jul 27, 2022 |
| HP            | Laptop 17-cp0xxx            | [761563e485](https://linux-hardware.org/?probe=761563e485) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3400               | [3412e8deac](https://linux-hardware.org/?probe=3412e8deac) | Jul 26, 2022 |
| Lenovo        | G570 4334                   | [e4c223e83e](https://linux-hardware.org/?probe=e4c223e83e) | Jul 25, 2022 |
| Apple         | MacBookAir6,1               | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| Acer          | Nitro AN515-55              | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Acer          | ConceptD CN315-71P          | [2723b19c18](https://linux-hardware.org/?probe=2723b19c18) | Jul 22, 2022 |
| Google        | Peppy                       | [3bfdae8e5e](https://linux-hardware.org/?probe=3bfdae8e5e) | Jul 21, 2022 |
| Acer          | Aspire One 753              | [eff74923d7](https://linux-hardware.org/?probe=eff74923d7) | Jul 21, 2022 |
| Dell          | Latitude 5430               | [f02c4072c1](https://linux-hardware.org/?probe=f02c4072c1) | Jul 21, 2022 |
| Acer          | Aspire R3-131T              | [c3722806fe](https://linux-hardware.org/?probe=c3722806fe) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | [2360c35ac1](https://linux-hardware.org/?probe=2360c35ac1) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | [5cb9487776](https://linux-hardware.org/?probe=5cb9487776) | Jul 20, 2022 |
| Dell          | Inspiron 1545               | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Acer          | TravelMate 8572T            | [54e7b50fc7](https://linux-hardware.org/?probe=54e7b50fc7) | Jul 18, 2022 |
| Alienware     | x17 R1                      | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| Apple         | MacBookAir7,2               | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | [5fd8a1dcf4](https://linux-hardware.org/?probe=5fd8a1dcf4) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | [de83d4ef43](https://linux-hardware.org/?probe=de83d4ef43) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | [01e6c30eff](https://linux-hardware.org/?probe=01e6c30eff) | Jul 15, 2022 |
| Dell          | Inspiron 16 Plus 7620       | [73be4f7864](https://linux-hardware.org/?probe=73be4f7864) | Jul 14, 2022 |
| Acer          | Nitro AN515-56              | [2418745195](https://linux-hardware.org/?probe=2418745195) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Dell          | XPS 13 9360                 | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | [4126a95603](https://linux-hardware.org/?probe=4126a95603) | Jul 13, 2022 |
| Apple         | MacBook9,1                  | [0ce6078768](https://linux-hardware.org/?probe=0ce6078768) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| Acer          | Aspire 1830T                | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| HP            | EliteBook 8470p             | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| Apple         | MacBookPro9,2               | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| Acer          | Aspire R3-131T              | [749a597089](https://linux-hardware.org/?probe=749a597089) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| HP            | EliteBook 850 G1            | [1a2485b399](https://linux-hardware.org/?probe=1a2485b399) | Jul 06, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ce6d3ec137](https://linux-hardware.org/?probe=ce6d3ec137) | Jul 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [e24a6dd845](https://linux-hardware.org/?probe=e24a6dd845) | Jul 05, 2022 |
| HP            | EliteBook 840 G6            | [d6dccd6ed7](https://linux-hardware.org/?probe=d6dccd6ed7) | Jul 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | [422a12c217](https://linux-hardware.org/?probe=422a12c217) | Jul 05, 2022 |
| HP            | Pavilion g6                 | [0cd693879d](https://linux-hardware.org/?probe=0cd693879d) | Jul 05, 2022 |
| Acer          | ConceptD CN315-71P          | [76d6073818](https://linux-hardware.org/?probe=76d6073818) | Jul 05, 2022 |
| Dell          | Precision M4700             | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| Acer          | Aspire R3-131T              | [748f42be21](https://linux-hardware.org/?probe=748f42be21) | Jul 05, 2022 |
| Apple         | MacBookPro10,2              | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| HP            | EliteBook 8470p             | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | [bcc3835be5](https://linux-hardware.org/?probe=bcc3835be5) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | [5f3197f581](https://linux-hardware.org/?probe=5f3197f581) | Jul 03, 2022 |
| Acer          | Swift SF114-34              | [dd9610011c](https://linux-hardware.org/?probe=dd9610011c) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| Dell          | Inspiron M5010              | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| HP            | EliteBook 8470p             | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3a423eae14](https://linux-hardware.org/?probe=3a423eae14) | Jun 30, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| AMI           | Intel                       | [2b592e2f4a](https://linux-hardware.org/?probe=2b592e2f4a) | Jun 29, 2022 |
| Dell          | Latitude 5430               | [119502eddb](https://linux-hardware.org/?probe=119502eddb) | Jun 29, 2022 |
| Dell          | G3 3500                     | [0df1b9607c](https://linux-hardware.org/?probe=0df1b9607c) | Jun 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | [b947b14fe4](https://linux-hardware.org/?probe=b947b14fe4) | Jun 27, 2022 |
| Alienware     | 14                          | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Apple         | MacBook9,1                  | [e6f1068c91](https://linux-hardware.org/?probe=e6f1068c91) | Jun 24, 2022 |
| HP            | Presario CQ62               | [2f136051c9](https://linux-hardware.org/?probe=2f136051c9) | Jun 24, 2022 |
| HP            | Presario CQ62               | [9beeb6d3c2](https://linux-hardware.org/?probe=9beeb6d3c2) | Jun 23, 2022 |
| Lenovo        | ThinkPad E490s 20NG0002A... | [4cce05dc1c](https://linux-hardware.org/?probe=4cce05dc1c) | Jun 23, 2022 |
| Apple         | MacBook9,1                  | [3656b8227f](https://linux-hardware.org/?probe=3656b8227f) | Jun 23, 2022 |
| Toshiba       | TECRA A40-D                 | [6307594332](https://linux-hardware.org/?probe=6307594332) | Jun 23, 2022 |
| Acer          | Nitro AN515-55              | [bc159b637c](https://linux-hardware.org/?probe=bc159b637c) | Jun 22, 2022 |
| HP            | 250 G6 Notebook PC          | [30d0a46d81](https://linux-hardware.org/?probe=30d0a46d81) | Jun 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f013ebb91b](https://linux-hardware.org/?probe=f013ebb91b) | Jun 20, 2022 |
| Acer          | Iconia                      | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b3da04a3af](https://linux-hardware.org/?probe=b3da04a3af) | Jun 20, 2022 |
| Framework     | Laptop                      | [f5ece7ce85](https://linux-hardware.org/?probe=f5ece7ce85) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Acer          | ConceptD CN315-71P          | [66d09f029f](https://linux-hardware.org/?probe=66d09f029f) | Jun 18, 2022 |
| Dell          | Precision 5540              | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| Acer          | ConceptD CN315-71P          | [9b162f339b](https://linux-hardware.org/?probe=9b162f339b) | Jun 16, 2022 |
| HUAWEI        | KLVD-WXX9                   | [4c97b8cc3a](https://linux-hardware.org/?probe=4c97b8cc3a) | Jun 16, 2022 |
| Alienware     | m15 R7                      | [9775a12e11](https://linux-hardware.org/?probe=9775a12e11) | Jun 16, 2022 |
| Acer          | Nitro AN515-55              | [bb631825e3](https://linux-hardware.org/?probe=bb631825e3) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| MSI           | Modern 15 A5M               | [bd16d5829c](https://linux-hardware.org/?probe=bd16d5829c) | Jun 14, 2022 |
| Apple         | MacBookPro11,1              | [57b90afcda](https://linux-hardware.org/?probe=57b90afcda) | Jun 14, 2022 |
| Dell          | Vostro 1500                 | [748a8a831b](https://linux-hardware.org/?probe=748a8a831b) | Jun 12, 2022 |
| HP            | Compaq 6730b                | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| ASUSTek       | Unknown                     | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| Alienware     | x17 R2                      | [78b867a06e](https://linux-hardware.org/?probe=78b867a06e) | Jun 08, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [75d6b8489b](https://linux-hardware.org/?probe=75d6b8489b) | Jun 08, 2022 |
| Acer          | Aspire R3-131T              | [1dab354de2](https://linux-hardware.org/?probe=1dab354de2) | Jun 07, 2022 |
| Acer          | Nitro AN515-55              | [4ab9f94abe](https://linux-hardware.org/?probe=4ab9f94abe) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2KW1... | [686fcbebd3](https://linux-hardware.org/?probe=686fcbebd3) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [57e7433cc5](https://linux-hardware.org/?probe=57e7433cc5) | Jun 04, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [b5bb3c0725](https://linux-hardware.org/?probe=b5bb3c0725) | Jun 02, 2022 |
| Apple         | MacBookAir4,2               | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| Dell          | G15 5515                    | [24ddbd70dc](https://linux-hardware.org/?probe=24ddbd70dc) | Jun 02, 2022 |
| HP            | 250 G6 Notebook PC          | [878274dbce](https://linux-hardware.org/?probe=878274dbce) | Jun 02, 2022 |
| Acer          | Aspire A315-58              | [b63e54900e](https://linux-hardware.org/?probe=b63e54900e) | Jun 02, 2022 |
| Dell          | Latitude E6540              | [9cbdc3f892](https://linux-hardware.org/?probe=9cbdc3f892) | Jun 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ae39e96b1a](https://linux-hardware.org/?probe=ae39e96b1a) | Jun 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [57f540db26](https://linux-hardware.org/?probe=57f540db26) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Dell          | Inspiron 5770               | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| IT Channel... | PA70Hx                      | [091ad22c2d](https://linux-hardware.org/?probe=091ad22c2d) | May 30, 2022 |
| Apple         | MacBookPro9,1               | [6fe2c4a416](https://linux-hardware.org/?probe=6fe2c4a416) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| MSI           | GT70 2OC/2OD                | [43144c3166](https://linux-hardware.org/?probe=43144c3166) | May 28, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [37d87b9245](https://linux-hardware.org/?probe=37d87b9245) | May 27, 2022 |
| Toshiba       | Satellite P850              | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [00baf8a2ff](https://linux-hardware.org/?probe=00baf8a2ff) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [32f7f3aa4b](https://linux-hardware.org/?probe=32f7f3aa4b) | May 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [43a374c1d4](https://linux-hardware.org/?probe=43a374c1d4) | May 23, 2022 |
| Acer          | Nitro AN515-45              | [293712cc51](https://linux-hardware.org/?probe=293712cc51) | May 23, 2022 |
| Apple         | MacBookPro6,1               | [40d33cea3f](https://linux-hardware.org/?probe=40d33cea3f) | May 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1d8684d1f5](https://linux-hardware.org/?probe=1d8684d1f5) | May 23, 2022 |
| Gigabyte      | P34V5                       | [6fa844b91e](https://linux-hardware.org/?probe=6fa844b91e) | May 23, 2022 |
| Gigabyte      | P34V5                       | [3ad8e4b239](https://linux-hardware.org/?probe=3ad8e4b239) | May 23, 2022 |
| Toshiba       | TECRA R850                  | [aa0bfd6c6a](https://linux-hardware.org/?probe=aa0bfd6c6a) | May 22, 2022 |
| Dell          | G3 3500                     | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| Dell          | Inspiron 1545               | [890010e793](https://linux-hardware.org/?probe=890010e793) | May 21, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [5d150789cb](https://linux-hardware.org/?probe=5d150789cb) | May 19, 2022 |
| Dell          | Inspiron 7572               | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| Dell          | XPS 13 7390                 | [98752f9fb4](https://linux-hardware.org/?probe=98752f9fb4) | May 18, 2022 |
| Acer          | Aspire A515-55              | [c01f14c77f](https://linux-hardware.org/?probe=c01f14c77f) | May 18, 2022 |
| Dell          | Latitude E7450              | [26b07c8dfc](https://linux-hardware.org/?probe=26b07c8dfc) | May 18, 2022 |
| Toshiba       | Satellite C850              | [5927aac0b7](https://linux-hardware.org/?probe=5927aac0b7) | May 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d4f9f894b6](https://linux-hardware.org/?probe=d4f9f894b6) | May 16, 2022 |
| Dell          | Inspiron 5570               | [faf97fa9a0](https://linux-hardware.org/?probe=faf97fa9a0) | May 16, 2022 |
| Gigabyte      | A7 K1                       | [9cd1ec32e4](https://linux-hardware.org/?probe=9cd1ec32e4) | May 16, 2022 |
| Dell          | XPS 15 9560                 | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| Toshiba       | Satellite L50-A             | [30a7bebcd3](https://linux-hardware.org/?probe=30a7bebcd3) | May 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [6251446c92](https://linux-hardware.org/?probe=6251446c92) | May 13, 2022 |
| Dell          | Inspiron 15 3515            | [dd8e112250](https://linux-hardware.org/?probe=dd8e112250) | May 12, 2022 |
| HP            | Pavilion g6                 | [5662b515c3](https://linux-hardware.org/?probe=5662b515c3) | May 12, 2022 |
| Acer          | Aspire V5-573G              | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [a22c347eaf](https://linux-hardware.org/?probe=a22c347eaf) | May 11, 2022 |
| HP            | 250 G6 Notebook PC          | [f2f010a36d](https://linux-hardware.org/?probe=f2f010a36d) | May 11, 2022 |
| Apple         | MacBookPro12,1              | [0d9616886e](https://linux-hardware.org/?probe=0d9616886e) | May 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [ce3addb8a4](https://linux-hardware.org/?probe=ce3addb8a4) | May 10, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [7d146e5dec](https://linux-hardware.org/?probe=7d146e5dec) | May 10, 2022 |
| Apple         | MacBookPro7,1               | [7ff6997105](https://linux-hardware.org/?probe=7ff6997105) | May 08, 2022 |
| Dell          | Studio XPS 1645             | [0d213120b4](https://linux-hardware.org/?probe=0d213120b4) | May 08, 2022 |
| HP            | Compaq Presario CQ60        | [9d27bd494e](https://linux-hardware.org/?probe=9d27bd494e) | May 08, 2022 |
| HP            | Folio 13 - 2000             | [e859aed666](https://linux-hardware.org/?probe=e859aed666) | May 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [3d07e8a45e](https://linux-hardware.org/?probe=3d07e8a45e) | May 05, 2022 |
| Dell          | Studio 1555                 | [c02949a388](https://linux-hardware.org/?probe=c02949a388) | May 05, 2022 |
| Acer          | Aspire A315-34              | [3ed5a6d961](https://linux-hardware.org/?probe=3ed5a6d961) | May 04, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [43dcfa4094](https://linux-hardware.org/?probe=43dcfa4094) | May 03, 2022 |
| Framework     | Laptop                      | [0d35134041](https://linux-hardware.org/?probe=0d35134041) | May 02, 2022 |
| HP            | 250 G5 Notebook PC          | [0e6717d54b](https://linux-hardware.org/?probe=0e6717d54b) | May 02, 2022 |
| HP            | EliteBook 850 G3            | [ab86c0118b](https://linux-hardware.org/?probe=ab86c0118b) | May 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7206b41211](https://linux-hardware.org/?probe=7206b41211) | May 01, 2022 |
| Lenovo        | Legion Y9000X 2020 81TH     | [c335cbb270](https://linux-hardware.org/?probe=c335cbb270) | May 01, 2022 |
| HUAWEI        | BOM-WXX9                    | [faa7213f5c](https://linux-hardware.org/?probe=faa7213f5c) | Apr 30, 2022 |
| Apple         | MacBookPro8,1               | [8826e1d451](https://linux-hardware.org/?probe=8826e1d451) | Apr 30, 2022 |
| HP            | ZBook 15 G6                 | [f948921cba](https://linux-hardware.org/?probe=f948921cba) | Apr 30, 2022 |
| Dell          | Inspiron 3543               | [6165b0554d](https://linux-hardware.org/?probe=6165b0554d) | Apr 28, 2022 |
| Lenovo        | ThinkPad X250 20CLS52P0F    | [a4d291ccda](https://linux-hardware.org/?probe=a4d291ccda) | Apr 27, 2022 |
| Acer          | Aspire 5750G                | [3a96bf8237](https://linux-hardware.org/?probe=3a96bf8237) | Apr 27, 2022 |
| HP            | ProBook 4710s               | [03d5c4c5b2](https://linux-hardware.org/?probe=03d5c4c5b2) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [981d5e03b3](https://linux-hardware.org/?probe=981d5e03b3) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0b3a1039fb](https://linux-hardware.org/?probe=0b3a1039fb) | Apr 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b1b4ea439d](https://linux-hardware.org/?probe=b1b4ea439d) | Apr 25, 2022 |
| HP            | ProBook 470 G5              | [e0def5bddc](https://linux-hardware.org/?probe=e0def5bddc) | Apr 25, 2022 |
| HUAWEI        | BOM-WXX9                    | [a771d771b2](https://linux-hardware.org/?probe=a771d771b2) | Apr 24, 2022 |
| HUAWEI        | BOM-WXX9                    | [1a195527a4](https://linux-hardware.org/?probe=1a195527a4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [c954cb4ba4](https://linux-hardware.org/?probe=c954cb4ba4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [ab88dc2482](https://linux-hardware.org/?probe=ab88dc2482) | Apr 24, 2022 |
| HP            | EliteBook 2530p             | [bfaeba4483](https://linux-hardware.org/?probe=bfaeba4483) | Apr 22, 2022 |
| Dell          | Latitude 7490               | [2b8d24f8ae](https://linux-hardware.org/?probe=2b8d24f8ae) | Apr 22, 2022 |
| HP            | EliteBook 2530p             | [a68c57ea30](https://linux-hardware.org/?probe=a68c57ea30) | Apr 22, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | [cbb3f353a5](https://linux-hardware.org/?probe=cbb3f353a5) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell          | XPS 13 7390                 | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Timi          | A35S                        | [e7d8adf61f](https://linux-hardware.org/?probe=e7d8adf61f) | Apr 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [4c845dc459](https://linux-hardware.org/?probe=4c845dc459) | Apr 19, 2022 |
| HP            | 250 G5 Notebook PC          | [5cb8325ed4](https://linux-hardware.org/?probe=5cb8325ed4) | Apr 18, 2022 |
| Acer          | Aspire R3-131T              | [48f584f713](https://linux-hardware.org/?probe=48f584f713) | Apr 17, 2022 |
| Apple         | MacBookPro5,4               | [918fef81c3](https://linux-hardware.org/?probe=918fef81c3) | Apr 17, 2022 |
| Dell          | Studio XPS 1645             | [6e722019b4](https://linux-hardware.org/?probe=6e722019b4) | Apr 16, 2022 |
| Dell          | Inspiron 1012               | [4659a757bf](https://linux-hardware.org/?probe=4659a757bf) | Apr 15, 2022 |
| Dell          | Inspiron 1012               | [ebfcf670fc](https://linux-hardware.org/?probe=ebfcf670fc) | Apr 15, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [c43bc1fcba](https://linux-hardware.org/?probe=c43bc1fcba) | Apr 15, 2022 |
| Dell          | Latitude E6530              | [d6f985e2ca](https://linux-hardware.org/?probe=d6f985e2ca) | Apr 15, 2022 |
| Dell          | Latitude E6230              | [19e2fe3c97](https://linux-hardware.org/?probe=19e2fe3c97) | Apr 14, 2022 |
| Dell          | Latitude 5590               | [c306b97fcd](https://linux-hardware.org/?probe=c306b97fcd) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291IU6       | [a4c2a2bff9](https://linux-hardware.org/?probe=a4c2a2bff9) | Apr 14, 2022 |
| Lenovo        | ThinkPad T430 2350BC6       | [c2ffb2a421](https://linux-hardware.org/?probe=c2ffb2a421) | Apr 14, 2022 |
| ASUSTek       | X580VD                      | [4c5ccfbe60](https://linux-hardware.org/?probe=4c5ccfbe60) | Apr 12, 2022 |
| Toshiba       | Satellite L50-A             | [9a4f7c7381](https://linux-hardware.org/?probe=9a4f7c7381) | Apr 09, 2022 |
| Toshiba       | Satellite L50-A             | [ce1ec01972](https://linux-hardware.org/?probe=ce1ec01972) | Apr 09, 2022 |
| Apple         | MacBookPro9,2               | [8ae799c372](https://linux-hardware.org/?probe=8ae799c372) | Apr 08, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | [c8a1f60191](https://linux-hardware.org/?probe=c8a1f60191) | Apr 05, 2022 |
| HP            | Pavilion g6                 | [a2d8dcb1bf](https://linux-hardware.org/?probe=a2d8dcb1bf) | Apr 05, 2022 |
| Toshiba       | Satellite L50-A             | [b51d99ad47](https://linux-hardware.org/?probe=b51d99ad47) | Apr 04, 2022 |
| Kogan         | KAL11C250SB                 | [ea426eda5e](https://linux-hardware.org/?probe=ea426eda5e) | Apr 03, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6154972f18](https://linux-hardware.org/?probe=6154972f18) | Apr 03, 2022 |
| ASUSTek       | P552LA                      | [94ef2678d5](https://linux-hardware.org/?probe=94ef2678d5) | Apr 03, 2022 |
| ASUSTek       | P552LA                      | [9166f15878](https://linux-hardware.org/?probe=9166f15878) | Apr 03, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Toshiba       | TECRA M11                   | [c81e18c0f3](https://linux-hardware.org/?probe=c81e18c0f3) | Apr 01, 2022 |
| Dell          | Precision 5540              | [d923ae2736](https://linux-hardware.org/?probe=d923ae2736) | Apr 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [39b70e2f99](https://linux-hardware.org/?probe=39b70e2f99) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | [339d70da8c](https://linux-hardware.org/?probe=339d70da8c) | Mar 30, 2022 |
| Dell          | Studio 1555                 | [db9f06343c](https://linux-hardware.org/?probe=db9f06343c) | Mar 30, 2022 |
| Toshiba       | Satellite Radius L10W-C     | [fc18e171f3](https://linux-hardware.org/?probe=fc18e171f3) | Mar 29, 2022 |
| HP            | Notebook                    | [c53a6a41a2](https://linux-hardware.org/?probe=c53a6a41a2) | Mar 29, 2022 |
| ASUSTek       | K55VD                       | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| Dell          | Inspiron 1545               | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Apple         | MacBook7,1                  | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| Apple         | MacBookPro10,1              | [a9caf3d428](https://linux-hardware.org/?probe=a9caf3d428) | Mar 25, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [20f2d24112](https://linux-hardware.org/?probe=20f2d24112) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | [64718709d1](https://linux-hardware.org/?probe=64718709d1) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | [f123e292b9](https://linux-hardware.org/?probe=f123e292b9) | Mar 23, 2022 |
| HP            | ProBook 430 G2              | [57038c6fd7](https://linux-hardware.org/?probe=57038c6fd7) | Mar 21, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [fef247389a](https://linux-hardware.org/?probe=fef247389a) | Mar 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7dcf73063d](https://linux-hardware.org/?probe=7dcf73063d) | Mar 19, 2022 |
| HP            | ZBook Firefly 14 inch G8... | [207eca584c](https://linux-hardware.org/?probe=207eca584c) | Mar 17, 2022 |
| Toshiba       | TECRA M11                   | [34167a6878](https://linux-hardware.org/?probe=34167a6878) | Mar 17, 2022 |
| Dell          | XPS 17 9710                 | [34da0f3cdb](https://linux-hardware.org/?probe=34da0f3cdb) | Mar 16, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [f1f12206d5](https://linux-hardware.org/?probe=f1f12206d5) | Mar 15, 2022 |
| HP            | Pavilion g6                 | [378424911d](https://linux-hardware.org/?probe=378424911d) | Mar 15, 2022 |
| Dell          | XPS 15 7590                 | [527b0d7066](https://linux-hardware.org/?probe=527b0d7066) | Mar 14, 2022 |
| Toshiba       | Satellite P850              | [0cd9132f27](https://linux-hardware.org/?probe=0cd9132f27) | Mar 14, 2022 |
| Lenovo        | G40-30 80FY                 | [7b54425ba2](https://linux-hardware.org/?probe=7b54425ba2) | Mar 13, 2022 |
| Acer          | Aspire A315-21G             | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| HP            | 250 G5 Notebook PC          | [3e67ab27db](https://linux-hardware.org/?probe=3e67ab27db) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [ab25401c99](https://linux-hardware.org/?probe=ab25401c99) | Mar 12, 2022 |
| Dell          | Latitude E5450              | [3d2d8b93fe](https://linux-hardware.org/?probe=3d2d8b93fe) | Mar 12, 2022 |
| Metabox       | Edge-Pro NS50MU             | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Lenovo        | ThinkPad T480 20L5A07TAU    | [755854f7d4](https://linux-hardware.org/?probe=755854f7d4) | Mar 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | [a83a1ffe1a](https://linux-hardware.org/?probe=a83a1ffe1a) | Mar 09, 2022 |
| Apple         | MacBookPro6,1               | [b227e92b83](https://linux-hardware.org/?probe=b227e92b83) | Mar 07, 2022 |
| Apple         | MacBookPro6,1               | [ef72c023ac](https://linux-hardware.org/?probe=ef72c023ac) | Mar 07, 2022 |
| Toshiba       | Satellite Radius L10W-C     | [db90921ddd](https://linux-hardware.org/?probe=db90921ddd) | Mar 07, 2022 |
| HP            | ENVY TS 15                  | [c2305ed449](https://linux-hardware.org/?probe=c2305ed449) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2d5c05af33](https://linux-hardware.org/?probe=2d5c05af33) | Mar 06, 2022 |
| HP            | Notebook                    | [d8b2e4567e](https://linux-hardware.org/?probe=d8b2e4567e) | Mar 05, 2022 |
| HP            | Notebook                    | [cafa2c6f1a](https://linux-hardware.org/?probe=cafa2c6f1a) | Mar 05, 2022 |
| HP            | ProBook 430 G5              | [9b130dbcb5](https://linux-hardware.org/?probe=9b130dbcb5) | Mar 04, 2022 |
| Acer          | Aspire R3-131T              | [98d5649b75](https://linux-hardware.org/?probe=98d5649b75) | Mar 03, 2022 |
| Acer          | Aspire V3-371               | [038cc99ead](https://linux-hardware.org/?probe=038cc99ead) | Mar 02, 2022 |
| Apple         | MacBookPro5,5               | [678e1eb19b](https://linux-hardware.org/?probe=678e1eb19b) | Feb 26, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [f3ec55a392](https://linux-hardware.org/?probe=f3ec55a392) | Feb 25, 2022 |
| HP            | ProBook 450 G1              | [1f26dfd88f](https://linux-hardware.org/?probe=1f26dfd88f) | Feb 22, 2022 |
| HP            | ProBook 430 G5              | [b9cb7cad60](https://linux-hardware.org/?probe=b9cb7cad60) | Feb 22, 2022 |
| HP            | ZBook 15 G6                 | [c5079e020e](https://linux-hardware.org/?probe=c5079e020e) | Feb 21, 2022 |
| Dell          | Precision 3561              | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [8a6f28fc9d](https://linux-hardware.org/?probe=8a6f28fc9d) | Feb 21, 2022 |
| Toshiba       | Satellite Pro C850          | [132557a51b](https://linux-hardware.org/?probe=132557a51b) | Feb 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [fb981fe5b0](https://linux-hardware.org/?probe=fb981fe5b0) | Feb 20, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [f08a9db4fb](https://linux-hardware.org/?probe=f08a9db4fb) | Feb 20, 2022 |
| HP            | Notebook                    | [1e57c317b4](https://linux-hardware.org/?probe=1e57c317b4) | Feb 19, 2022 |
| HP            | Notebook                    | [583b61ead6](https://linux-hardware.org/?probe=583b61ead6) | Feb 19, 2022 |
| IT Channel... | P95xER                      | [c8add471fb](https://linux-hardware.org/?probe=c8add471fb) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [f7e1ab4276](https://linux-hardware.org/?probe=f7e1ab4276) | Feb 18, 2022 |
| HP            | ProBook 470 G2              | [0ef953e74d](https://linux-hardware.org/?probe=0ef953e74d) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [8791991562](https://linux-hardware.org/?probe=8791991562) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | [983c62bf72](https://linux-hardware.org/?probe=983c62bf72) | Feb 17, 2022 |
| Apple         | MacBookPro16,1              | [3e35c49d6c](https://linux-hardware.org/?probe=3e35c49d6c) | Feb 16, 2022 |
| Dell          | Inspiron 7591               | [f5cc709342](https://linux-hardware.org/?probe=f5cc709342) | Feb 16, 2022 |
| Toshiba       | Satellite C50-A             | [e88fd90806](https://linux-hardware.org/?probe=e88fd90806) | Feb 15, 2022 |
| HP            | ProBook 450 G6              | [e54664c1be](https://linux-hardware.org/?probe=e54664c1be) | Feb 15, 2022 |
| Dell          | System Vostro 3750          | [4a5289bfbe](https://linux-hardware.org/?probe=4a5289bfbe) | Feb 14, 2022 |
| Toshiba       | QOSMIO X70-A                | [c3c921f8e2](https://linux-hardware.org/?probe=c3c921f8e2) | Feb 14, 2022 |
| Lenovo        | ThinkPad T420 4178A47       | [cda9da09dc](https://linux-hardware.org/?probe=cda9da09dc) | Feb 14, 2022 |
| ASUSTek       | UX330UAK                    | [8731a73bfa](https://linux-hardware.org/?probe=8731a73bfa) | Feb 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2afbdea066](https://linux-hardware.org/?probe=2afbdea066) | Feb 13, 2022 |
| Toshiba       | Satellite C50-A283          | [66f810c5f5](https://linux-hardware.org/?probe=66f810c5f5) | Feb 13, 2022 |
| Kogan         | KAL11C250SB                 | [600104b8e2](https://linux-hardware.org/?probe=600104b8e2) | Feb 12, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | [9ce361abd3](https://linux-hardware.org/?probe=9ce361abd3) | Feb 12, 2022 |
| Samsung       | 700T                        | [076ad3b906](https://linux-hardware.org/?probe=076ad3b906) | Feb 11, 2022 |
| Acer          | Aspire 5600                 | [4b2259f040](https://linux-hardware.org/?probe=4b2259f040) | Feb 10, 2022 |
| HP            | Compaq CQ45                 | [3c75fd14fb](https://linux-hardware.org/?probe=3c75fd14fb) | Feb 09, 2022 |
| HP            | Pavilion dv6                | [efb945cc4f](https://linux-hardware.org/?probe=efb945cc4f) | Feb 09, 2022 |
| ASUSTek       | G74Sx                       | [d0f48fef55](https://linux-hardware.org/?probe=d0f48fef55) | Feb 08, 2022 |
| Samsung       | R580                        | [f822930ecf](https://linux-hardware.org/?probe=f822930ecf) | Feb 08, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | [1110112a7f](https://linux-hardware.org/?probe=1110112a7f) | Feb 06, 2022 |
| Star Labs     | StarBook                    | [e53bcff920](https://linux-hardware.org/?probe=e53bcff920) | Feb 06, 2022 |
| Unknown       | Unknown                     | [7848918b1d](https://linux-hardware.org/?probe=7848918b1d) | Feb 05, 2022 |
| Acer          | Aspire A515-43              | [6bc39a1855](https://linux-hardware.org/?probe=6bc39a1855) | Feb 04, 2022 |
| Lenovo        | ThinkPad Mini10 3507A31     | [f49f0801c0](https://linux-hardware.org/?probe=f49f0801c0) | Feb 03, 2022 |
| Acer          | Aspire 5741                 | [175d1e66d3](https://linux-hardware.org/?probe=175d1e66d3) | Feb 02, 2022 |
| Toshiba       | Satellite P500              | [2403a2d0f9](https://linux-hardware.org/?probe=2403a2d0f9) | Feb 02, 2022 |
| HP            | ProBook 450 G6              | [1de51c3e3b](https://linux-hardware.org/?probe=1de51c3e3b) | Feb 01, 2022 |
| HP            | ProBook 450 G6              | [e6dfa0f8ec](https://linux-hardware.org/?probe=e6dfa0f8ec) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | [1615c253fc](https://linux-hardware.org/?probe=1615c253fc) | Feb 01, 2022 |
| Dell          | XPS 15 9550                 | [e8acac784c](https://linux-hardware.org/?probe=e8acac784c) | Jan 31, 2022 |
| Dell          | XPS 15 9550                 | [33a9d5357e](https://linux-hardware.org/?probe=33a9d5357e) | Jan 31, 2022 |
| Apple         | MacBookPro8,1               | [0591806d5c](https://linux-hardware.org/?probe=0591806d5c) | Jan 31, 2022 |
| HP            | EliteBook 840 G5            | [01c1515f57](https://linux-hardware.org/?probe=01c1515f57) | Jan 28, 2022 |
| ASUSTek       | X550WA                      | [e146d6a0f8](https://linux-hardware.org/?probe=e146d6a0f8) | Jan 27, 2022 |
| Toshiba       | Satellite P850              | [9fed64bb7e](https://linux-hardware.org/?probe=9fed64bb7e) | Jan 27, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f7c5fb7450](https://linux-hardware.org/?probe=f7c5fb7450) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [36a39bf7eb](https://linux-hardware.org/?probe=36a39bf7eb) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [9d12ae4f9a](https://linux-hardware.org/?probe=9d12ae4f9a) | Jan 26, 2022 |
| Intel Clie... | LAPBC710                    | [586a7bef92](https://linux-hardware.org/?probe=586a7bef92) | Jan 25, 2022 |
| Kogan         | KAL11C250SB                 | [ba3fd61313](https://linux-hardware.org/?probe=ba3fd61313) | Jan 23, 2022 |
| Toshiba       | Satellite L640              | [280b5d9630](https://linux-hardware.org/?probe=280b5d9630) | Jan 22, 2022 |
| Lenovo        | ThinkPad W530 2463B87       | [bb1640db6c](https://linux-hardware.org/?probe=bb1640db6c) | Jan 21, 2022 |
| HP            | ProBook 6560b               | [d5dc02b800](https://linux-hardware.org/?probe=d5dc02b800) | Jan 21, 2022 |
| Dell          | Inspiron 7591               | [2f1c294587](https://linux-hardware.org/?probe=2f1c294587) | Jan 21, 2022 |
| HP            | ProBook 470 G5              | [b4c6ea0b27](https://linux-hardware.org/?probe=b4c6ea0b27) | Jan 18, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [a61f1b9d56](https://linux-hardware.org/?probe=a61f1b9d56) | Jan 16, 2022 |
| Dell          | Latitude 7280               | [d05eb9657d](https://linux-hardware.org/?probe=d05eb9657d) | Jan 16, 2022 |
| ASUSTek       | Unknown                     | [0baed0f9c8](https://linux-hardware.org/?probe=0baed0f9c8) | Jan 16, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6bda3e5854](https://linux-hardware.org/?probe=6bda3e5854) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [d62f3c4bf5](https://linux-hardware.org/?probe=d62f3c4bf5) | Jan 14, 2022 |
| ASUSTek       | TP500LNG                    | [85762ec0a0](https://linux-hardware.org/?probe=85762ec0a0) | Jan 14, 2022 |
| Dell          | Inspiron M5010              | [21dddfe6a8](https://linux-hardware.org/?probe=21dddfe6a8) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | [dffa1b1708](https://linux-hardware.org/?probe=dffa1b1708) | Jan 14, 2022 |
| Apple         | MacBookPro16,1              | [ca163c9952](https://linux-hardware.org/?probe=ca163c9952) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | [cf529c7ad0](https://linux-hardware.org/?probe=cf529c7ad0) | Jan 14, 2022 |
| HP            | EliteBook 8770w             | [d78d315a83](https://linux-hardware.org/?probe=d78d315a83) | Jan 13, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [f7ea85c311](https://linux-hardware.org/?probe=f7ea85c311) | Jan 13, 2022 |
| HP            | Pavilion g6                 | [e14f742bb9](https://linux-hardware.org/?probe=e14f742bb9) | Jan 12, 2022 |
| HP            | Pavilion g6                 | [62f049acf1](https://linux-hardware.org/?probe=62f049acf1) | Jan 12, 2022 |
| Apple         | MacBookPro8,1               | [a462f4b26f](https://linux-hardware.org/?probe=a462f4b26f) | Jan 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c781a61663](https://linux-hardware.org/?probe=c781a61663) | Jan 11, 2022 |
| Dell          | Precision 7550              | [0b72e489be](https://linux-hardware.org/?probe=0b72e489be) | Jan 10, 2022 |
| Dell          | Latitude E7440              | [9d89ac124e](https://linux-hardware.org/?probe=9d89ac124e) | Jan 08, 2022 |
| Acer          | Aspire A315-35              | [1e6abae11a](https://linux-hardware.org/?probe=1e6abae11a) | Jan 08, 2022 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [7ba01d7327](https://linux-hardware.org/?probe=7ba01d7327) | Jan 07, 2022 |
| Kogan         | KAL11C250SB                 | [a153354498](https://linux-hardware.org/?probe=a153354498) | Jan 07, 2022 |
| MSI           | GE62 2QD                    | [5f35b0b1ab](https://linux-hardware.org/?probe=5f35b0b1ab) | Jan 07, 2022 |
| Lenovo        | ThinkPad T560 20FJS4FV00    | [4bd9bb5f20](https://linux-hardware.org/?probe=4bd9bb5f20) | Jan 05, 2022 |
| HP            | EliteBook 8570p             | [f49baae9b5](https://linux-hardware.org/?probe=f49baae9b5) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Apple         | MacBookAir6,2               | [faaaf3cc89](https://linux-hardware.org/?probe=faaaf3cc89) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| Alienware     | m17                         | [13da9fa1b3](https://linux-hardware.org/?probe=13da9fa1b3) | Jan 02, 2022 |
| HP            | ENVY 17                     | [bd8db07a0a](https://linux-hardware.org/?probe=bd8db07a0a) | Jan 02, 2022 |
| Dell          | Inspiron 5770               | [0e81199f2c](https://linux-hardware.org/?probe=0e81199f2c) | Jan 02, 2022 |
| Apple         | MacBookPro11,5              | [1c88a2bad0](https://linux-hardware.org/?probe=1c88a2bad0) | Jan 02, 2022 |
| HP            | ENVY 17                     | [a140a1a272](https://linux-hardware.org/?probe=a140a1a272) | Jan 02, 2022 |
| Dell          | Latitude E5430 vPro         | [a073f421c1](https://linux-hardware.org/?probe=a073f421c1) | Jan 01, 2022 |
| Notebook      | P65xHP                      | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Apple         | MacBookPro9,2               | [601fb323dc](https://linux-hardware.org/?probe=601fb323dc) | Dec 30, 2021 |
| Dell          | Latitude E5420              | [dc28d41913](https://linux-hardware.org/?probe=dc28d41913) | Dec 30, 2021 |
| HP            | 250 G7 Notebook PC          | [9ee8c0f205](https://linux-hardware.org/?probe=9ee8c0f205) | Dec 29, 2021 |
| HP            | EliteBook 2760p             | [1cd129ee35](https://linux-hardware.org/?probe=1cd129ee35) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | [f2deb9ec59](https://linux-hardware.org/?probe=f2deb9ec59) | Dec 27, 2021 |
| Dell          | Inspiron M5010              | [e576e17ed7](https://linux-hardware.org/?probe=e576e17ed7) | Dec 26, 2021 |
| Lenovo        | ThinkPad W530 2463B87       | [e82b5e9a8a](https://linux-hardware.org/?probe=e82b5e9a8a) | Dec 26, 2021 |
| Dell          | XPS 15 9550                 | [fc814dc489](https://linux-hardware.org/?probe=fc814dc489) | Dec 25, 2021 |
| LEADER        | NH5BT11                     | [763efa7eb2](https://linux-hardware.org/?probe=763efa7eb2) | Dec 25, 2021 |
| Toshiba       | Satellite C660              | [b13c6ceb2c](https://linux-hardware.org/?probe=b13c6ceb2c) | Dec 25, 2021 |
| HP            | EliteBook 2560p             | [4081d9b42b](https://linux-hardware.org/?probe=4081d9b42b) | Dec 24, 2021 |
| Acer          | Aspire 5740                 | [baf5d23f31](https://linux-hardware.org/?probe=baf5d23f31) | Dec 24, 2021 |
| Samsung       | 700T                        | [dcd96a051e](https://linux-hardware.org/?probe=dcd96a051e) | Dec 23, 2021 |
| Dell          | XPS 15 7590                 | [5cbe59259b](https://linux-hardware.org/?probe=5cbe59259b) | Dec 23, 2021 |
| Dell          | Latitude E6400              | [46422c0062](https://linux-hardware.org/?probe=46422c0062) | Dec 22, 2021 |
| Google        | Edgar                       | [dc1b8b8c81](https://linux-hardware.org/?probe=dc1b8b8c81) | Dec 20, 2021 |
| Google        | Edgar                       | [96597eb5fd](https://linux-hardware.org/?probe=96597eb5fd) | Dec 20, 2021 |
| Apple         | MacBookPro8,1               | [70ebf43f36](https://linux-hardware.org/?probe=70ebf43f36) | Dec 20, 2021 |
| Dell          | XPS 15 9500                 | [e5592dfde0](https://linux-hardware.org/?probe=e5592dfde0) | Dec 20, 2021 |
| Toshiba       | Satellite C660              | [6f860db242](https://linux-hardware.org/?probe=6f860db242) | Dec 18, 2021 |
| Apple         | MacBookPro8,1               | [08df885431](https://linux-hardware.org/?probe=08df885431) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | [4d52a02213](https://linux-hardware.org/?probe=4d52a02213) | Dec 16, 2021 |
| Apple         | MacBookPro9,2               | [ef78b011ef](https://linux-hardware.org/?probe=ef78b011ef) | Dec 16, 2021 |
| Lenovo        | ThinkPad W540 20BG0011US    | [ead3a18508](https://linux-hardware.org/?probe=ead3a18508) | Dec 15, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [ba92d0772e](https://linux-hardware.org/?probe=ba92d0772e) | Dec 14, 2021 |
| MSI           | PS42 Modern 8RC             | [2686d73cb8](https://linux-hardware.org/?probe=2686d73cb8) | Dec 13, 2021 |
| Lenovo        | ThinkPad T440 20B7S02A00    | [5b3ec8682e](https://linux-hardware.org/?probe=5b3ec8682e) | Dec 13, 2021 |
| Acer          | Aspire 5600                 | [25b1e50c64](https://linux-hardware.org/?probe=25b1e50c64) | Dec 12, 2021 |
| Acer          | ConceptD CN315-71P          | [ac834a5768](https://linux-hardware.org/?probe=ac834a5768) | Dec 11, 2021 |
| Dell          | Latitude 7370               | [d2bbf57105](https://linux-hardware.org/?probe=d2bbf57105) | Dec 11, 2021 |
| HP            | ProBook 470 G5              | [3a17215293](https://linux-hardware.org/?probe=3a17215293) | Dec 11, 2021 |
| HP            | ProBook 470 G5              | [36e4d31312](https://linux-hardware.org/?probe=36e4d31312) | Dec 10, 2021 |
| HP            | Pavilion g6                 | [a50dca2bf2](https://linux-hardware.org/?probe=a50dca2bf2) | Dec 10, 2021 |
| ASUSTek       | X550JX                      | [818c536fda](https://linux-hardware.org/?probe=818c536fda) | Dec 10, 2021 |
| HP            | 250 G6 Notebook PC          | [3b955f362a](https://linux-hardware.org/?probe=3b955f362a) | Dec 10, 2021 |
| HP            | ZBook 14u G5                | [21df45023e](https://linux-hardware.org/?probe=21df45023e) | Dec 09, 2021 |
| HP            | ZBook 14u G5                | [b01068d8cc](https://linux-hardware.org/?probe=b01068d8cc) | Dec 09, 2021 |
| Apple         | MacBookPro14,3              | [6e7dbbfd7a](https://linux-hardware.org/?probe=6e7dbbfd7a) | Dec 08, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| MSI           | GE62 2QD                    | [f37c114570](https://linux-hardware.org/?probe=f37c114570) | Dec 05, 2021 |
| HUAWEI        | HN-WX9X                     | [a4266720ec](https://linux-hardware.org/?probe=a4266720ec) | Dec 05, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | [fbe30211c6](https://linux-hardware.org/?probe=fbe30211c6) | Dec 05, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [ee5c6147f7](https://linux-hardware.org/?probe=ee5c6147f7) | Dec 04, 2021 |
| Toshiba       | Satellite C660              | [47b40007ee](https://linux-hardware.org/?probe=47b40007ee) | Dec 04, 2021 |
| Toshiba       | Satellite C660              | [4d64247a8a](https://linux-hardware.org/?probe=4d64247a8a) | Dec 04, 2021 |
| Acer          | Aspire R3-131T              | [3fd499b264](https://linux-hardware.org/?probe=3fd499b264) | Dec 04, 2021 |
| Gigabyte      | AERO 15 KB                  | [a7d3041cd2](https://linux-hardware.org/?probe=a7d3041cd2) | Dec 03, 2021 |
| Panasonic     | CF-19RDRAMGA                | [5aaebfbf19](https://linux-hardware.org/?probe=5aaebfbf19) | Nov 29, 2021 |
| Toshiba       | Satellite C660              | [2799629c61](https://linux-hardware.org/?probe=2799629c61) | Nov 28, 2021 |
| Toshiba       | Satellite C660              | [1e80d1c181](https://linux-hardware.org/?probe=1e80d1c181) | Nov 28, 2021 |
| Apple         | MacBook7,1                  | [22e54de439](https://linux-hardware.org/?probe=22e54de439) | Nov 27, 2021 |
| HP            | Pavilion Notebook           | [092ae35663](https://linux-hardware.org/?probe=092ae35663) | Nov 27, 2021 |
| Apple         | MacBookPro8,1               | [a0b9aec393](https://linux-hardware.org/?probe=a0b9aec393) | Nov 26, 2021 |
| Apple         | MacBookPro8,1               | [62a1aeadc4](https://linux-hardware.org/?probe=62a1aeadc4) | Nov 26, 2021 |
| ASUSTek       | Unknown                     | [1627a50b96](https://linux-hardware.org/?probe=1627a50b96) | Nov 25, 2021 |
| Toshiba       | Satellite L640              | [0a00178792](https://linux-hardware.org/?probe=0a00178792) | Nov 25, 2021 |
| Toshiba       | Satellite P50t-A            | [33add9e294](https://linux-hardware.org/?probe=33add9e294) | Nov 25, 2021 |
| Apple         | MacBookPro9,2               | [ab60997b9e](https://linux-hardware.org/?probe=ab60997b9e) | Nov 24, 2021 |
| LG Electro... | 14Z960-GR3HK                | [7dd0d53cef](https://linux-hardware.org/?probe=7dd0d53cef) | Nov 24, 2021 |
| HP            | Pavilion g6                 | [f7da6c6d2d](https://linux-hardware.org/?probe=f7da6c6d2d) | Nov 23, 2021 |
| Dell          | G5 5590                     | [3a149ffc5e](https://linux-hardware.org/?probe=3a149ffc5e) | Nov 23, 2021 |
| Apple         | MacBookPro16,1              | [9d02768642](https://linux-hardware.org/?probe=9d02768642) | Nov 23, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | [19ce916e45](https://linux-hardware.org/?probe=19ce916e45) | Nov 22, 2021 |
| Dell          | Latitude 3400               | [62dd7a6ea2](https://linux-hardware.org/?probe=62dd7a6ea2) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | [024686087f](https://linux-hardware.org/?probe=024686087f) | Nov 20, 2021 |
| Acer          | Aspire 5560                 | [5725ae4593](https://linux-hardware.org/?probe=5725ae4593) | Nov 20, 2021 |
| AFTERSHOCK... | VAPOR 15X                   | [6433612bed](https://linux-hardware.org/?probe=6433612bed) | Nov 18, 2021 |
| ASUSTek       | K50IJ                       | [9e28f131eb](https://linux-hardware.org/?probe=9e28f131eb) | Nov 18, 2021 |
| Dell          | Inspiron 7586               | [188923fc9c](https://linux-hardware.org/?probe=188923fc9c) | Nov 17, 2021 |
| Toshiba       | Satellite L50-B             | [867287fb63](https://linux-hardware.org/?probe=867287fb63) | Nov 16, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [d8acfef1ef](https://linux-hardware.org/?probe=d8acfef1ef) | Nov 16, 2021 |
| Dell          | Inspiron 7566               | [b868de3306](https://linux-hardware.org/?probe=b868de3306) | Nov 16, 2021 |
| Lenovo        | V110-15IAP 80TG             | [c6aebae4da](https://linux-hardware.org/?probe=c6aebae4da) | Nov 16, 2021 |
| HP            | Pavilion dv5                | [ec4890a33b](https://linux-hardware.org/?probe=ec4890a33b) | Nov 15, 2021 |
| HP            | Pavilion dv5                | [4ddaeca48c](https://linux-hardware.org/?probe=4ddaeca48c) | Nov 15, 2021 |
| LG Electro... | 16Z90P-G.AA75A              | [d15e199bb4](https://linux-hardware.org/?probe=d15e199bb4) | Nov 14, 2021 |
| Apple         | MacBookPro8,1               | [ea402fa75e](https://linux-hardware.org/?probe=ea402fa75e) | Nov 14, 2021 |
| HP            | Pavilion 15                 | [6b4486db02](https://linux-hardware.org/?probe=6b4486db02) | Nov 13, 2021 |
| HP            | Pavilion 15                 | [d0e343d3b7](https://linux-hardware.org/?probe=d0e343d3b7) | Nov 13, 2021 |
| ASUSTek       | K55A                        | [60377bce60](https://linux-hardware.org/?probe=60377bce60) | Nov 13, 2021 |
| HP            | Pavilion dv6                | [30c1df8961](https://linux-hardware.org/?probe=30c1df8961) | Nov 13, 2021 |
| Apple         | MacBook7,1                  | [b898d5a09c](https://linux-hardware.org/?probe=b898d5a09c) | Nov 13, 2021 |
| Toshiba       | Satellite Pro L50-A         | [36bc6d2ebd](https://linux-hardware.org/?probe=36bc6d2ebd) | Nov 12, 2021 |
| Acer          | Aspire 5720Z                | [ba74c7653a](https://linux-hardware.org/?probe=ba74c7653a) | Nov 12, 2021 |
| Acer          | Aspire 5720Z                | [d11d9b16b0](https://linux-hardware.org/?probe=d11d9b16b0) | Nov 12, 2021 |
| COM1          | NBINF-O5-4R5G5              | [b8a99864aa](https://linux-hardware.org/?probe=b8a99864aa) | Nov 12, 2021 |
| Acer          | Aspire 3000                 | [86d2f89f59](https://linux-hardware.org/?probe=86d2f89f59) | Nov 12, 2021 |
| Acer          | Aspire 3000                 | [dad287d5a1](https://linux-hardware.org/?probe=dad287d5a1) | Nov 11, 2021 |
| Apple         | MacBookAir6,1               | [588c351d40](https://linux-hardware.org/?probe=588c351d40) | Nov 10, 2021 |
| LG Electro... | 14Z90P-G.AR53A              | [a1fb8771db](https://linux-hardware.org/?probe=a1fb8771db) | Nov 10, 2021 |
| COM1          | NBINF-O5-4R5G5              | [e1cd2bd1cc](https://linux-hardware.org/?probe=e1cd2bd1cc) | Nov 10, 2021 |
| Apple         | MacBookPro8,1               | [d499b22b03](https://linux-hardware.org/?probe=d499b22b03) | Nov 09, 2021 |
| Toshiba       | Satellite Pro L50-A         | [6212422e34](https://linux-hardware.org/?probe=6212422e34) | Nov 09, 2021 |
| Unknown       | D15D                        | [5b15ae8ff3](https://linux-hardware.org/?probe=5b15ae8ff3) | Nov 07, 2021 |
| AFTERSHOCK... | VAPOR 15X                   | [cc21cf13c8](https://linux-hardware.org/?probe=cc21cf13c8) | Nov 07, 2021 |
| Samsung       | RF511/RF411/RF711           | [899657b967](https://linux-hardware.org/?probe=899657b967) | Nov 07, 2021 |
| HP            | Pavilion dv6                | [bd084f3ccd](https://linux-hardware.org/?probe=bd084f3ccd) | Nov 07, 2021 |
| Acer          | Aspire ES1-521              | [5ef4af5924](https://linux-hardware.org/?probe=5ef4af5924) | Nov 06, 2021 |
| MSI           | GT72 2QD                    | [d558e0270e](https://linux-hardware.org/?probe=d558e0270e) | Nov 06, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [e2180a6c85](https://linux-hardware.org/?probe=e2180a6c85) | Nov 04, 2021 |
| HP            | Pavilion g6                 | [c289308c14](https://linux-hardware.org/?probe=c289308c14) | Nov 04, 2021 |
| ASUSTek       | BU403UA                     | [acb1038124](https://linux-hardware.org/?probe=acb1038124) | Nov 03, 2021 |
| HP            | EliteBook 840 G3            | [a2ddc44da4](https://linux-hardware.org/?probe=a2ddc44da4) | Nov 02, 2021 |
| Toshiba       | Satellite L750D             | [143e009499](https://linux-hardware.org/?probe=143e009499) | Nov 02, 2021 |
| Toshiba       | Satellite P500              | [e69f994b81](https://linux-hardware.org/?probe=e69f994b81) | Nov 02, 2021 |
| MSI           | GT72VR 6RE                  | [4e8a3e6a15](https://linux-hardware.org/?probe=4e8a3e6a15) | Nov 01, 2021 |
| MSI           | GT72VR 6RE                  | [343f246595](https://linux-hardware.org/?probe=343f246595) | Nov 01, 2021 |
| COM1          | NBINF-O5-4R5G5              | [a3b154116b](https://linux-hardware.org/?probe=a3b154116b) | Oct 31, 2021 |
| Lenovo        | ThinkPad R400 7439CTO       | [9a7be426f5](https://linux-hardware.org/?probe=9a7be426f5) | Oct 30, 2021 |
| Toshiba       | Satellite Pro L50-A         | [a817ed896e](https://linux-hardware.org/?probe=a817ed896e) | Oct 29, 2021 |
| Toshiba       | Satellite Pro L50-A         | [5c23460bb8](https://linux-hardware.org/?probe=5c23460bb8) | Oct 27, 2021 |
| Acer          | Aspire 5600                 | [7e2da6d3e9](https://linux-hardware.org/?probe=7e2da6d3e9) | Oct 26, 2021 |
| HP            | Laptop 15s-du1xxx           | [23c770232c](https://linux-hardware.org/?probe=23c770232c) | Oct 25, 2021 |
| Dell          | Inspiron 3505               | [fe09832e42](https://linux-hardware.org/?probe=fe09832e42) | Oct 25, 2021 |
| Toshiba       | Satellite L850              | [066f99ecbc](https://linux-hardware.org/?probe=066f99ecbc) | Oct 25, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | [98720c7a44](https://linux-hardware.org/?probe=98720c7a44) | Oct 24, 2021 |
| Acer          | Aspire ES1-521              | [248ab157b8](https://linux-hardware.org/?probe=248ab157b8) | Oct 23, 2021 |
| HP            | 250 G3                      | [820dcd95a7](https://linux-hardware.org/?probe=820dcd95a7) | Oct 23, 2021 |
| Dell          | Latitude E7450              | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| HP            | Stream Laptop               | [95df1a4e45](https://linux-hardware.org/?probe=95df1a4e45) | Oct 22, 2021 |
| IT Channel... | PCX0DX                      | [fb1bf80085](https://linux-hardware.org/?probe=fb1bf80085) | Oct 22, 2021 |
| Lenovo        | ThinkPad E490s 20NGA000A... | [c2a180845c](https://linux-hardware.org/?probe=c2a180845c) | Oct 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [463b15301d](https://linux-hardware.org/?probe=463b15301d) | Oct 21, 2021 |
| Notebook      | W840SN Series               | [4baeb2cafc](https://linux-hardware.org/?probe=4baeb2cafc) | Oct 20, 2021 |
| Apple         | MacBookPro8,1               | [e72b8e6ba0](https://linux-hardware.org/?probe=e72b8e6ba0) | Oct 20, 2021 |
| HP            | Pavilion Notebook           | [fe8dbfde1b](https://linux-hardware.org/?probe=fe8dbfde1b) | Oct 19, 2021 |
| Acer          | Aspire E5-571               | [aec49e7b35](https://linux-hardware.org/?probe=aec49e7b35) | Oct 19, 2021 |
| HP            | Pavilion Notebook           | [4b53959f48](https://linux-hardware.org/?probe=4b53959f48) | Oct 19, 2021 |
| MSI           | CX70 2QF                    | [f91a0f1380](https://linux-hardware.org/?probe=f91a0f1380) | Oct 19, 2021 |
| MSI           | CX70 2QF                    | [9d4c9ccf89](https://linux-hardware.org/?probe=9d4c9ccf89) | Oct 18, 2021 |
| ASUSTek       | X501A                       | [b3e4d8035d](https://linux-hardware.org/?probe=b3e4d8035d) | Oct 17, 2021 |
| Acer          | ConceptD CN315-71P          | [50385dde8b](https://linux-hardware.org/?probe=50385dde8b) | Oct 16, 2021 |
| Apple         | MacBookAir7,2               | [370b129f3f](https://linux-hardware.org/?probe=370b129f3f) | Oct 16, 2021 |
| Dell          | G7 7700                     | [273e51402c](https://linux-hardware.org/?probe=273e51402c) | Oct 15, 2021 |
| Alienware     | M17xR4                      | [98464fe67b](https://linux-hardware.org/?probe=98464fe67b) | Oct 15, 2021 |
| Alienware     | M17xR4                      | [ea79d2496d](https://linux-hardware.org/?probe=ea79d2496d) | Oct 15, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | [b2214c65d5](https://linux-hardware.org/?probe=b2214c65d5) | Oct 15, 2021 |
| Samsung       | RF511/RF411/RF711           | [ebd0874d7c](https://linux-hardware.org/?probe=ebd0874d7c) | Oct 13, 2021 |
| Samsung       | RF511/RF411/RF711           | [7a4ede4a67](https://linux-hardware.org/?probe=7a4ede4a67) | Oct 13, 2021 |
| HP            | Laptop 15s-du1xxx           | [6b3505b5f2](https://linux-hardware.org/?probe=6b3505b5f2) | Oct 13, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [471414140c](https://linux-hardware.org/?probe=471414140c) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| Dell          | Inspiron 3505               | [8628621ed3](https://linux-hardware.org/?probe=8628621ed3) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| Lenovo        | ThinkPad T410 2522ED2       | [c8c010b75c](https://linux-hardware.org/?probe=c8c010b75c) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0011AU     | [85c8487ca5](https://linux-hardware.org/?probe=85c8487ca5) | Oct 11, 2021 |
| Toshiba       | Satellite L830              | [e8652672c3](https://linux-hardware.org/?probe=e8652672c3) | Oct 10, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Lenovo        | ThinkPad E14 20RA0020AU     | [f8efee6741](https://linux-hardware.org/?probe=f8efee6741) | Oct 09, 2021 |
| Dell          | Latitude 5400               | [77c9ee3548](https://linux-hardware.org/?probe=77c9ee3548) | Oct 07, 2021 |
| Dell          | Inspiron 7586               | [2ecf794b47](https://linux-hardware.org/?probe=2ecf794b47) | Oct 07, 2021 |
| Acer          | Aspire E5-571               | [8e65153ce2](https://linux-hardware.org/?probe=8e65153ce2) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Toshiba       | Satellite C55t-C            | [a6f33aa565](https://linux-hardware.org/?probe=a6f33aa565) | Oct 03, 2021 |
| Dell          | Latitude 5410               | [6928f4237f](https://linux-hardware.org/?probe=6928f4237f) | Oct 01, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [00b95678dd](https://linux-hardware.org/?probe=00b95678dd) | Sep 27, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [55c08d7759](https://linux-hardware.org/?probe=55c08d7759) | Sep 27, 2021 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [23dbed3ab1](https://linux-hardware.org/?probe=23dbed3ab1) | Sep 26, 2021 |
| Lenovo        | ThinkPad X61s 7667DE3       | [9d3daab4b3](https://linux-hardware.org/?probe=9d3daab4b3) | Sep 25, 2021 |
| Dell          | Inspiron 11-3168            | [4c7c72b321](https://linux-hardware.org/?probe=4c7c72b321) | Sep 25, 2021 |
| Kogan         | KAL11C250SB                 | [b76a44f6d5](https://linux-hardware.org/?probe=b76a44f6d5) | Sep 24, 2021 |
| Notebook      | W840SN Series               | [15f25a62a8](https://linux-hardware.org/?probe=15f25a62a8) | Sep 23, 2021 |
| Lenovo        | Mixx-700-12ISK 80QL         | [090e25b77c](https://linux-hardware.org/?probe=090e25b77c) | Sep 22, 2021 |
| Dell          | Precision 5560              | [c31c2d637b](https://linux-hardware.org/?probe=c31c2d637b) | Sep 21, 2021 |
| Dell          | Precision 5560              | [7b8db74bd5](https://linux-hardware.org/?probe=7b8db74bd5) | Sep 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3C... | [4698844ec0](https://linux-hardware.org/?probe=4698844ec0) | Sep 20, 2021 |
| Toshiba       | Satellite L20               | [654c60e971](https://linux-hardware.org/?probe=654c60e971) | Sep 20, 2021 |
| Acer          | Aspire 5600                 | [6d6b90c8e8](https://linux-hardware.org/?probe=6d6b90c8e8) | Sep 19, 2021 |
| ASUSTek       | U31F                        | [908a7184ae](https://linux-hardware.org/?probe=908a7184ae) | Sep 19, 2021 |
| ASUSTek       | U31F                        | [7cf4ac39de](https://linux-hardware.org/?probe=7cf4ac39de) | Sep 18, 2021 |
| Unknown       | Unknown                     | [f620b10ff0](https://linux-hardware.org/?probe=f620b10ff0) | Sep 14, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [d238092077](https://linux-hardware.org/?probe=d238092077) | Sep 14, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [68eacd0e30](https://linux-hardware.org/?probe=68eacd0e30) | Sep 13, 2021 |
| HP            | Pavilion dv6                | [b0e257ccca](https://linux-hardware.org/?probe=b0e257ccca) | Sep 13, 2021 |
| Acer          | Aspire R3-131T              | [e872ba288e](https://linux-hardware.org/?probe=e872ba288e) | Sep 12, 2021 |
| ASUSTek       | N750JV                      | [e24cb69cc0](https://linux-hardware.org/?probe=e24cb69cc0) | Sep 11, 2021 |
| Metabox       | Alpha-X NH77DC              | [0b6122c2ce](https://linux-hardware.org/?probe=0b6122c2ce) | Sep 10, 2021 |
| Metabox       | Alpha-X NH77DC              | [98364c4883](https://linux-hardware.org/?probe=98364c4883) | Sep 10, 2021 |
| Dell          | XPS 13 9370                 | [db0606cb42](https://linux-hardware.org/?probe=db0606cb42) | Sep 10, 2021 |
| Dell          | XPS 15 9560                 | [b33af6d329](https://linux-hardware.org/?probe=b33af6d329) | Sep 10, 2021 |
| Lenovo        | ThinkPad R400 7439CTO       | [5b2fb97960](https://linux-hardware.org/?probe=5b2fb97960) | Sep 10, 2021 |
| Alienware     | 17                          | [49c757651f](https://linux-hardware.org/?probe=49c757651f) | Sep 09, 2021 |
| Apple         | MacBookPro8,1               | [5be67e3cb8](https://linux-hardware.org/?probe=5be67e3cb8) | Sep 07, 2021 |
| Dell          | Latitude E6430s             | [0995d2317b](https://linux-hardware.org/?probe=0995d2317b) | Sep 06, 2021 |
| Timi          | TM1613                      | [530a9daa43](https://linux-hardware.org/?probe=530a9daa43) | Sep 06, 2021 |
| Toshiba       | Satellite P750              | [ee2674ad2e](https://linux-hardware.org/?probe=ee2674ad2e) | Sep 06, 2021 |
| Dell          | Latitude E5430 non-vPro     | [e26b6d083b](https://linux-hardware.org/?probe=e26b6d083b) | Sep 06, 2021 |
| Dell          | Latitude E5430 non-vPro     | [f4d430c0f9](https://linux-hardware.org/?probe=f4d430c0f9) | Sep 06, 2021 |
| Apple         | MacBookPro8,1               | [a865b060fa](https://linux-hardware.org/?probe=a865b060fa) | Sep 06, 2021 |
| Metabox       | NP50DE                      | [355939bc8d](https://linux-hardware.org/?probe=355939bc8d) | Sep 05, 2021 |
| ASUSTek       | K72F                        | [718b264baf](https://linux-hardware.org/?probe=718b264baf) | Sep 05, 2021 |
| ASUSTek       | K72F                        | [68b6deb2e1](https://linux-hardware.org/?probe=68b6deb2e1) | Sep 05, 2021 |
| Toshiba       | Satellite L50-B             | [e8f5eb9453](https://linux-hardware.org/?probe=e8f5eb9453) | Sep 04, 2021 |
| HP            | Presario CQ62               | [4cdec89015](https://linux-hardware.org/?probe=4cdec89015) | Sep 04, 2021 |
| Metabox       | Alpha-S NP70HJ              | [7b477b4fae](https://linux-hardware.org/?probe=7b477b4fae) | Sep 04, 2021 |
| Metabox       | Alpha-S NP70HJ              | [a72cca0cf9](https://linux-hardware.org/?probe=a72cca0cf9) | Sep 04, 2021 |
| Toshiba       | Satellite L50-B             | [696718d602](https://linux-hardware.org/?probe=696718d602) | Sep 03, 2021 |
| Dell          | XPS 15 9510                 | [d606dd2010](https://linux-hardware.org/?probe=d606dd2010) | Sep 03, 2021 |
| Dell          | Latitude E6430s             | [92a767fd0b](https://linux-hardware.org/?probe=92a767fd0b) | Sep 03, 2021 |
| Toshiba       | TECRA A40-D                 | [5afac0ef07](https://linux-hardware.org/?probe=5afac0ef07) | Sep 02, 2021 |
| Dell          | XPS 15 9500                 | [bf06fd5933](https://linux-hardware.org/?probe=bf06fd5933) | Sep 02, 2021 |
| Dell          | XPS 15 9500                 | [740118101a](https://linux-hardware.org/?probe=740118101a) | Sep 02, 2021 |
| HP            | Pavilion dv6                | [20e136bd56](https://linux-hardware.org/?probe=20e136bd56) | Aug 31, 2021 |
| Toshiba       | Satellite L670              | [4610a7f835](https://linux-hardware.org/?probe=4610a7f835) | Aug 31, 2021 |
| HP            | Presario CQ62               | [da35a133c7](https://linux-hardware.org/?probe=da35a133c7) | Aug 31, 2021 |
| HP            | Pavilion Notebook           | [846b2e2a87](https://linux-hardware.org/?probe=846b2e2a87) | Aug 30, 2021 |
| Dell          | Latitude E6230              | [055cc1b72a](https://linux-hardware.org/?probe=055cc1b72a) | Aug 30, 2021 |
| Dell          | G5 5590                     | [268f4cffb4](https://linux-hardware.org/?probe=268f4cffb4) | Aug 30, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [a900c9c170](https://linux-hardware.org/?probe=a900c9c170) | Aug 30, 2021 |
| ASUSTek       | BU403UA                     | [685da500ca](https://linux-hardware.org/?probe=685da500ca) | Aug 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [b7c59b9453](https://linux-hardware.org/?probe=b7c59b9453) | Aug 30, 2021 |
| Timi          | TM1607                      | [0dcb7e6611](https://linux-hardware.org/?probe=0dcb7e6611) | Aug 30, 2021 |
| Toshiba       | Satellite C55t-C            | [2bf7dba42f](https://linux-hardware.org/?probe=2bf7dba42f) | Aug 30, 2021 |
| Dell          | Latitude E7470              | [e047247ab4](https://linux-hardware.org/?probe=e047247ab4) | Aug 29, 2021 |
| Toshiba       | PORTEGE M780                | [3062a1ac2f](https://linux-hardware.org/?probe=3062a1ac2f) | Aug 28, 2021 |
| Lenovo        | ThinkPad SL 27464RM         | [612cb5f7a2](https://linux-hardware.org/?probe=612cb5f7a2) | Aug 28, 2021 |
| Apple         | MacBookPro5,5               | [97ed1ed910](https://linux-hardware.org/?probe=97ed1ed910) | Aug 28, 2021 |
| Apple         | MacBookPro5,5               | [e035ede092](https://linux-hardware.org/?probe=e035ede092) | Aug 27, 2021 |
| Kogan         | KAL11C250SB                 | [1c38937a42](https://linux-hardware.org/?probe=1c38937a42) | Aug 24, 2021 |
| Apple         | MacBookPro8,1               | [7b296604b3](https://linux-hardware.org/?probe=7b296604b3) | Aug 24, 2021 |
| Dell          | Latitude E5500              | [5af91644f4](https://linux-hardware.org/?probe=5af91644f4) | Aug 22, 2021 |
| HP            | Notebook                    | [5ac3618644](https://linux-hardware.org/?probe=5ac3618644) | Aug 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ff1e83e570](https://linux-hardware.org/?probe=ff1e83e570) | Aug 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [4128c360ba](https://linux-hardware.org/?probe=4128c360ba) | Aug 22, 2021 |
| HP            | Laptop 15s-du1xxx           | [0db32c3e7e](https://linux-hardware.org/?probe=0db32c3e7e) | Aug 21, 2021 |
| Dell          | XPS 15 9570                 | [1114f42cd0](https://linux-hardware.org/?probe=1114f42cd0) | Aug 21, 2021 |
| Dell          | XPS 15 9570                 | [44188d0e94](https://linux-hardware.org/?probe=44188d0e94) | Aug 21, 2021 |
| ASUSTek       | G60JX                       | [d3844a2f0d](https://linux-hardware.org/?probe=d3844a2f0d) | Aug 19, 2021 |
| ASUSTek       | G60JX                       | [9cbac37f77](https://linux-hardware.org/?probe=9cbac37f77) | Aug 19, 2021 |
| HP            | 245 G7 Notebook PC          | [5f26581582](https://linux-hardware.org/?probe=5f26581582) | Aug 19, 2021 |
| Apple         | MacBookPro8,1               | [4678cd0f57](https://linux-hardware.org/?probe=4678cd0f57) | Aug 19, 2021 |
| Panasonic     | CF-19RDRAMGA                | [b11b688d14](https://linux-hardware.org/?probe=b11b688d14) | Aug 18, 2021 |
| Lenovo        | G560 0679                   | [897bce191e](https://linux-hardware.org/?probe=897bce191e) | Aug 18, 2021 |
| HP            | EliteBook 745 G5            | [7154f86bd2](https://linux-hardware.org/?probe=7154f86bd2) | Aug 15, 2021 |
| HP            | EliteBook 820 G3            | [9e40c4d015](https://linux-hardware.org/?probe=9e40c4d015) | Aug 15, 2021 |
| Panasonic     | CF-19RDRAMGA                | [3d6f06387e](https://linux-hardware.org/?probe=3d6f06387e) | Aug 14, 2021 |
| ASUSTek       | N550JV                      | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| ASUSTek       | UX21E                       | [d334eaddee](https://linux-hardware.org/?probe=d334eaddee) | Aug 13, 2021 |
| ASUSTek       | N550JV                      | [631e697061](https://linux-hardware.org/?probe=631e697061) | Aug 13, 2021 |
| ASUSTek       | N550JV                      | [191ce05579](https://linux-hardware.org/?probe=191ce05579) | Aug 13, 2021 |
| Dell          | G7 7790                     | [99dd172940](https://linux-hardware.org/?probe=99dd172940) | Aug 12, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c1fe9dc989](https://linux-hardware.org/?probe=c1fe9dc989) | Aug 12, 2021 |
| Lenovo        | G50-45 80E3                 | [deb2b65c2b](https://linux-hardware.org/?probe=deb2b65c2b) | Aug 12, 2021 |
| HP            | Laptop 15s-du1xxx           | [19412614ef](https://linux-hardware.org/?probe=19412614ef) | Aug 11, 2021 |
| Dell          | Latitude E7470              | [d9dfcc1b21](https://linux-hardware.org/?probe=d9dfcc1b21) | Aug 10, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [52118232ff](https://linux-hardware.org/?probe=52118232ff) | Aug 10, 2021 |
| Acer          | Swift SF314-57              | [215a6c3074](https://linux-hardware.org/?probe=215a6c3074) | Aug 10, 2021 |
| Dell          | Inspiron 5547               | [b0404fbe46](https://linux-hardware.org/?probe=b0404fbe46) | Aug 07, 2021 |
| HP            | Compaq Presario CQ60        | [4f08d66d45](https://linux-hardware.org/?probe=4f08d66d45) | Aug 06, 2021 |
| Acer          | Aspire 5600                 | [0f2143b2b8](https://linux-hardware.org/?probe=0f2143b2b8) | Aug 06, 2021 |
| Acer          | Aspire 5750G                | [1309d808df](https://linux-hardware.org/?probe=1309d808df) | Aug 06, 2021 |
| Acer          | Aspire 5750G                | [d8031b12b6](https://linux-hardware.org/?probe=d8031b12b6) | Aug 06, 2021 |
| HP            | Compaq Presario CQ60        | [78e707b9f9](https://linux-hardware.org/?probe=78e707b9f9) | Aug 06, 2021 |
| Dell          | Precision 5540              | [f0e5719b08](https://linux-hardware.org/?probe=f0e5719b08) | Aug 06, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [1b40831803](https://linux-hardware.org/?probe=1b40831803) | Aug 04, 2021 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [8f5a4ed54c](https://linux-hardware.org/?probe=8f5a4ed54c) | Aug 04, 2021 |
| Toshiba       | PORTEGE R30-A               | [084f842b96](https://linux-hardware.org/?probe=084f842b96) | Aug 03, 2021 |
| Toshiba       | PORTEGE R30-A               | [6f6ac5daf9](https://linux-hardware.org/?probe=6f6ac5daf9) | Aug 03, 2021 |
| Toshiba       | PORTEGE M780                | [0b4712cca4](https://linux-hardware.org/?probe=0b4712cca4) | Aug 03, 2021 |
| ASUSTek       | E205SA                      | [43c5f73997](https://linux-hardware.org/?probe=43c5f73997) | Aug 03, 2021 |
| Acer          | Swift SF314-41              | [b4e22213f2](https://linux-hardware.org/?probe=b4e22213f2) | Aug 03, 2021 |
| Toshiba       | Satellite C665D             | [d59b8d5f1d](https://linux-hardware.org/?probe=d59b8d5f1d) | Aug 03, 2021 |
| HP            | ENVY 17                     | [062df6e72a](https://linux-hardware.org/?probe=062df6e72a) | Aug 03, 2021 |
| Dell          | Precision 5540              | [beac3a4550](https://linux-hardware.org/?probe=beac3a4550) | Aug 02, 2021 |
| HP            | Pavilion 13 x360 PC         | [a58c2624f5](https://linux-hardware.org/?probe=a58c2624f5) | Aug 02, 2021 |
| HP            | Pavilion 13 x360 PC         | [6500790c35](https://linux-hardware.org/?probe=6500790c35) | Aug 02, 2021 |
| Acer          | Aspire 5750G                | [0be9e70a0e](https://linux-hardware.org/?probe=0be9e70a0e) | Jul 29, 2021 |
| Acer          | Aspire 5750G                | [f99d763e4e](https://linux-hardware.org/?probe=f99d763e4e) | Jul 29, 2021 |
| Acer          | Aspire ES1-523              | [8c4ca90fbe](https://linux-hardware.org/?probe=8c4ca90fbe) | Jul 28, 2021 |
| Acer          | Aspire 5600                 | [10fca9ad05](https://linux-hardware.org/?probe=10fca9ad05) | Jul 28, 2021 |
| Dell          | Latitude 7370               | [8844c61431](https://linux-hardware.org/?probe=8844c61431) | Jul 27, 2021 |
| Dell          | Latitude 7370               | [65b034f3f3](https://linux-hardware.org/?probe=65b034f3f3) | Jul 27, 2021 |
| Alienware     | M17xR4                      | [bd3bf6b728](https://linux-hardware.org/?probe=bd3bf6b728) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Acer          | Predator G3-571             | [8391b40344](https://linux-hardware.org/?probe=8391b40344) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [7757049c0f](https://linux-hardware.org/?probe=7757049c0f) | Jul 24, 2021 |
| ASUSTek       | G74Sx                       | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| HP            | Pavilion 15                 | [7a0695e6bb](https://linux-hardware.org/?probe=7a0695e6bb) | Jul 23, 2021 |
| Dell          | XPS 17 9700                 | [400d8e67ef](https://linux-hardware.org/?probe=400d8e67ef) | Jul 23, 2021 |
| Acer          | Aspire ES1-523              | [b7b78a52d1](https://linux-hardware.org/?probe=b7b78a52d1) | Jul 22, 2021 |
| HP            | ENVY TS 15                  | [345c92d5c3](https://linux-hardware.org/?probe=345c92d5c3) | Jul 21, 2021 |
| System76      | Gazelle                     | [a6df2bb1a8](https://linux-hardware.org/?probe=a6df2bb1a8) | Jul 21, 2021 |
| Dell          | Inspiron 15 5510            | [49660ef55a](https://linux-hardware.org/?probe=49660ef55a) | Jul 21, 2021 |
| Toshiba       | Satellite L500              | [8a51f94bcc](https://linux-hardware.org/?probe=8a51f94bcc) | Jul 21, 2021 |
| Acer          | Aspire ES1-523              | [cbbd57725a](https://linux-hardware.org/?probe=cbbd57725a) | Jul 20, 2021 |
| Toshiba       | TECRA A40-D                 | [76816bad4a](https://linux-hardware.org/?probe=76816bad4a) | Jul 20, 2021 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [570d86d845](https://linux-hardware.org/?probe=570d86d845) | Jul 20, 2021 |
| HP            | 250 G6 Notebook PC          | [14945dd66b](https://linux-hardware.org/?probe=14945dd66b) | Jul 19, 2021 |
| Dynabook      | Satellite Pro C50-H         | [593e35f7de](https://linux-hardware.org/?probe=593e35f7de) | Jul 18, 2021 |
| Dynabook      | Satellite Pro C50-H         | [30760fd197](https://linux-hardware.org/?probe=30760fd197) | Jul 18, 2021 |
| ONE-NETBOO... | A1                          | [9b9734f000](https://linux-hardware.org/?probe=9b9734f000) | Jul 17, 2021 |
| Notebook      | W840SN Series               | [4414afdecf](https://linux-hardware.org/?probe=4414afdecf) | Jul 16, 2021 |
| Acer          | Predator G3-571             | [99c16ec7fb](https://linux-hardware.org/?probe=99c16ec7fb) | Jul 15, 2021 |
| HP            | Laptop 15-bs1xx             | [3d1c92e425](https://linux-hardware.org/?probe=3d1c92e425) | Jul 15, 2021 |
| One Educat... | Infinity:One                | [2f6016cb80](https://linux-hardware.org/?probe=2f6016cb80) | Jul 12, 2021 |
| Toshiba       | Satellite L750              | [6e7debda59](https://linux-hardware.org/?probe=6e7debda59) | Jul 12, 2021 |
| Dell          | Precision 5540              | [29bcf08396](https://linux-hardware.org/?probe=29bcf08396) | Jul 11, 2021 |
| Lenovo        | ThinkPad X1 Titanium Gen... | [6279f113cf](https://linux-hardware.org/?probe=6279f113cf) | Jul 10, 2021 |
| Lenovo        | ThinkPad X1 Titanium Gen... | [577f7a44f7](https://linux-hardware.org/?probe=577f7a44f7) | Jul 10, 2021 |
| Gigabyte      | AERO 15 KB                  | [e689bf94fe](https://linux-hardware.org/?probe=e689bf94fe) | Jul 09, 2021 |
| Google        | Cave                        | [80261a92eb](https://linux-hardware.org/?probe=80261a92eb) | Jul 08, 2021 |
| Google        | Cave                        | [4a7d6ffd00](https://linux-hardware.org/?probe=4a7d6ffd00) | Jul 08, 2021 |
| Sony          | SVF15A16CGS                 | [93408236cc](https://linux-hardware.org/?probe=93408236cc) | Jul 07, 2021 |
| Sony          | SVF15A16CGS                 | [afe44e2c41](https://linux-hardware.org/?probe=afe44e2c41) | Jul 07, 2021 |
| HP            | Pavilion dv6                | [9f8f5b0ce9](https://linux-hardware.org/?probe=9f8f5b0ce9) | Jul 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [9fb071c117](https://linux-hardware.org/?probe=9fb071c117) | Jul 06, 2021 |
| Dell          | Latitude E5520              | [11a20a01eb](https://linux-hardware.org/?probe=11a20a01eb) | Jul 05, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [afe362114a](https://linux-hardware.org/?probe=afe362114a) | Jul 05, 2021 |
| HP            | EliteBook 8540w             | [6130e48df9](https://linux-hardware.org/?probe=6130e48df9) | Jul 05, 2021 |
| HP            | EliteBook 8540w             | [8fcf62f37c](https://linux-hardware.org/?probe=8fcf62f37c) | Jul 05, 2021 |
| Dell          | Inspiron 5567               | [1387eb5740](https://linux-hardware.org/?probe=1387eb5740) | Jul 03, 2021 |
| Notebook      | P95_HP                      | [8aa8037e16](https://linux-hardware.org/?probe=8aa8037e16) | Jul 03, 2021 |
| Dell          | Latitude 3440               | [6139da799f](https://linux-hardware.org/?probe=6139da799f) | Jun 30, 2021 |
| Sony          | VGN-FW47GY_H                | [d66a6e2b5d](https://linux-hardware.org/?probe=d66a6e2b5d) | Jun 25, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [663b4e4994](https://linux-hardware.org/?probe=663b4e4994) | Jun 22, 2021 |
| Dell          | Latitude 3440               | [abc3010962](https://linux-hardware.org/?probe=abc3010962) | Jun 22, 2021 |
| Dell          | Inspiron M5010              | [1776eab993](https://linux-hardware.org/?probe=1776eab993) | Jun 22, 2021 |
| Dell          | Inspiron 3531               | [afe609b492](https://linux-hardware.org/?probe=afe609b492) | Jun 22, 2021 |
| Dell          | Latitude E7450              | [0bb4d0ad6d](https://linux-hardware.org/?probe=0bb4d0ad6d) | Jun 22, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | [4d638e6ba4](https://linux-hardware.org/?probe=4d638e6ba4) | Jun 21, 2021 |
| Dell          | XPS 13 7390                 | [ffd6111ce0](https://linux-hardware.org/?probe=ffd6111ce0) | Jun 21, 2021 |
| Acer          | A515-52-572L                | [50624d3e67](https://linux-hardware.org/?probe=50624d3e67) | Jun 21, 2021 |
| HP            | ProBook 430 G2              | [477a2d94ef](https://linux-hardware.org/?probe=477a2d94ef) | Jun 18, 2021 |
| HP            | ProBook 430 G2              | [f2e2545c0a](https://linux-hardware.org/?probe=f2e2545c0a) | Jun 17, 2021 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [32538ae4b8](https://linux-hardware.org/?probe=32538ae4b8) | Jun 17, 2021 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [882855d037](https://linux-hardware.org/?probe=882855d037) | Jun 17, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | [0f830d98f5](https://linux-hardware.org/?probe=0f830d98f5) | Jun 15, 2021 |
| Lenovo        | Yoga S730-13IML 81U4        | [a357c549d3](https://linux-hardware.org/?probe=a357c549d3) | Jun 15, 2021 |
| ASUSTek       | N550JV                      | [0379830a1b](https://linux-hardware.org/?probe=0379830a1b) | Jun 15, 2021 |
| HP            | EliteBook 2560p             | [b8cf45e412](https://linux-hardware.org/?probe=b8cf45e412) | Jun 15, 2021 |
| Toshiba       | Satellite L750              | [572807c3ac](https://linux-hardware.org/?probe=572807c3ac) | Jun 14, 2021 |
| Lenovo        | ThinkPad T460s 20FAS5ML0... | [6ea1914144](https://linux-hardware.org/?probe=6ea1914144) | Jun 14, 2021 |
| Toshiba       | Satellite L750              | [df0e59887e](https://linux-hardware.org/?probe=df0e59887e) | Jun 14, 2021 |
| Toshiba       | Satellite C55t-C            | [0519b9a79c](https://linux-hardware.org/?probe=0519b9a79c) | Jun 13, 2021 |
| LEADER        | NH5BT11                     | [572655ab08](https://linux-hardware.org/?probe=572655ab08) | Jun 12, 2021 |
| LEADER        | NH5BT11                     | [5a6ffecdb6](https://linux-hardware.org/?probe=5a6ffecdb6) | Jun 12, 2021 |
| Dell          | Inspiron 5447               | [0a7b01f59f](https://linux-hardware.org/?probe=0a7b01f59f) | Jun 11, 2021 |
| Dell          | Inspiron M5010              | [a3931de055](https://linux-hardware.org/?probe=a3931de055) | Jun 10, 2021 |
| Lenovo        | ThinkPad T420 4180BJ7       | [4291003ff9](https://linux-hardware.org/?probe=4291003ff9) | Jun 10, 2021 |
| Acer          | AS E5-523G                  | [72c24f6db7](https://linux-hardware.org/?probe=72c24f6db7) | Jun 10, 2021 |
| Acer          | AS E5-523G                  | [302cf7c629](https://linux-hardware.org/?probe=302cf7c629) | Jun 10, 2021 |
| LEADER        | NH5BT11                     | [14e4c44337](https://linux-hardware.org/?probe=14e4c44337) | Jun 09, 2021 |
| LEADER        | NH5BT11                     | [45fb29e07f](https://linux-hardware.org/?probe=45fb29e07f) | Jun 09, 2021 |
| Dell          | Inspiron 5559               | [3ee94aa452](https://linux-hardware.org/?probe=3ee94aa452) | Jun 08, 2021 |
| IBM           | 264070A                     | [c057e54603](https://linux-hardware.org/?probe=c057e54603) | Jun 08, 2021 |
| Lenovo        | ThinkPad T460s 20FAS5ML0... | [808e20707f](https://linux-hardware.org/?probe=808e20707f) | Jun 08, 2021 |
| Dell          | Latitude E6400              | [1b6485896d](https://linux-hardware.org/?probe=1b6485896d) | Jun 07, 2021 |
| Dell          | Inspiron 5559               | [21879d77bc](https://linux-hardware.org/?probe=21879d77bc) | Jun 05, 2021 |
| Apple         | MacBookAir5,2               | [f0b2632ba4](https://linux-hardware.org/?probe=f0b2632ba4) | Jun 05, 2021 |
| Apple         | MacBookAir5,2               | [5b087dd571](https://linux-hardware.org/?probe=5b087dd571) | Jun 05, 2021 |
| Dell          | XPS 15 9500                 | [d9848a2007](https://linux-hardware.org/?probe=d9848a2007) | Jun 05, 2021 |
| Dell          | XPS 15 9550                 | [a06f0af7cd](https://linux-hardware.org/?probe=a06f0af7cd) | Jun 04, 2021 |
| HP            | ENVY Laptop 13-ba1xxx       | [645e867e65](https://linux-hardware.org/?probe=645e867e65) | Jun 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [9bf0354917](https://linux-hardware.org/?probe=9bf0354917) | Jun 02, 2021 |
| Dell          | XPS 15 9560                 | [f788fd5e9d](https://linux-hardware.org/?probe=f788fd5e9d) | Jun 02, 2021 |
| HP            | EliteBook Folio 9470m       | [48a10324d0](https://linux-hardware.org/?probe=48a10324d0) | Jun 02, 2021 |
| HP            | ENVY Laptop 13-ba1xxx       | [70fe8a9832](https://linux-hardware.org/?probe=70fe8a9832) | Jun 01, 2021 |
| HP            | Presario CQ56               | [70a720b401](https://linux-hardware.org/?probe=70a720b401) | May 31, 2021 |
| Dell          | XPS 13 9310                 | [f94ced9a41](https://linux-hardware.org/?probe=f94ced9a41) | May 31, 2021 |
| ASUSTek       | G73Jh                       | [fbc93a495c](https://linux-hardware.org/?probe=fbc93a495c) | May 30, 2021 |
| HP            | Notebook                    | [d6508e6e5d](https://linux-hardware.org/?probe=d6508e6e5d) | May 30, 2021 |
| ASUSTek       | K43TA                       | [bed31dbcef](https://linux-hardware.org/?probe=bed31dbcef) | May 30, 2021 |
| ASUSTek       | X555UA                      | [163fd0376e](https://linux-hardware.org/?probe=163fd0376e) | May 29, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [1268e75895](https://linux-hardware.org/?probe=1268e75895) | May 29, 2021 |
| HP            | Stream Laptop               | [f8e609a883](https://linux-hardware.org/?probe=f8e609a883) | May 28, 2021 |
| HP            | Pavilion g6                 | [1dbb8065d8](https://linux-hardware.org/?probe=1dbb8065d8) | May 28, 2021 |
| Acer          | Aspire A515-55              | [09499164b9](https://linux-hardware.org/?probe=09499164b9) | May 28, 2021 |
| Acer          | Aspire A515-55              | [3cfa12f511](https://linux-hardware.org/?probe=3cfa12f511) | May 27, 2021 |
| HP            | Stream Laptop               | [8bde0490c1](https://linux-hardware.org/?probe=8bde0490c1) | May 26, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | [c332c85dcf](https://linux-hardware.org/?probe=c332c85dcf) | May 26, 2021 |
| HP            | ProBook 650 G2              | [896cc06116](https://linux-hardware.org/?probe=896cc06116) | May 26, 2021 |
| HP            | Pavilion dv6                | [b9fd7914e2](https://linux-hardware.org/?probe=b9fd7914e2) | May 25, 2021 |
| ASUSTek       | X550LB                      | [435091e995](https://linux-hardware.org/?probe=435091e995) | May 24, 2021 |
| ASUSTek       | X550LB                      | [fb64646c9b](https://linux-hardware.org/?probe=fb64646c9b) | May 24, 2021 |
| ASUSTek       | S400CA                      | [89061a323a](https://linux-hardware.org/?probe=89061a323a) | May 22, 2021 |
| Toshiba       | Satellite L50-A             | [e93fda84e6](https://linux-hardware.org/?probe=e93fda84e6) | May 21, 2021 |
| Toshiba       | Satellite C55t-C            | [ee59c663f5](https://linux-hardware.org/?probe=ee59c663f5) | May 20, 2021 |
| Acer          | Aspire A515-52              | [d2e4a69c16](https://linux-hardware.org/?probe=d2e4a69c16) | May 18, 2021 |
| HP            | Laptop 15-bw0xx             | [30c73729a4](https://linux-hardware.org/?probe=30c73729a4) | May 17, 2021 |
| Alienware     | 14                          | [b8ff373a37](https://linux-hardware.org/?probe=b8ff373a37) | May 16, 2021 |
| Metabox       | Alpha-X NH58RHQ             | [bae61addd8](https://linux-hardware.org/?probe=bae61addd8) | May 16, 2021 |
| Acer          | ConceptD CN315-71P          | [5ecea84320](https://linux-hardware.org/?probe=5ecea84320) | May 15, 2021 |
| Notebook      | P65_67HSHP                  | [37da45fe3f](https://linux-hardware.org/?probe=37da45fe3f) | May 14, 2021 |
| ASUSTek       | K43TA                       | [1fdd91dbde](https://linux-hardware.org/?probe=1fdd91dbde) | May 14, 2021 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [79fa3f7509](https://linux-hardware.org/?probe=79fa3f7509) | May 12, 2021 |
| Gigabyte      | AERO 15 KB                  | [dceb3210ff](https://linux-hardware.org/?probe=dceb3210ff) | May 12, 2021 |
| HP            | Laptop 15-bw0xx             | [c984136679](https://linux-hardware.org/?probe=c984136679) | May 11, 2021 |
| HP            | Laptop 15-bw0xx             | [35322060c7](https://linux-hardware.org/?probe=35322060c7) | May 11, 2021 |
| Dell          | Inspiron M5010              | [4121360b58](https://linux-hardware.org/?probe=4121360b58) | May 10, 2021 |
| Apple         | MacBookPro8,1               | [8afdfe2827](https://linux-hardware.org/?probe=8afdfe2827) | May 10, 2021 |
| Apple         | MacBookPro8,1               | [5da4e125b2](https://linux-hardware.org/?probe=5da4e125b2) | May 09, 2021 |
| Acer          | Aspire One 753              | [78e58cd9e7](https://linux-hardware.org/?probe=78e58cd9e7) | May 09, 2021 |
| Acer          | Aspire E5-571               | [2c91167099](https://linux-hardware.org/?probe=2c91167099) | May 07, 2021 |
| Acer          | Aspire E5-571               | [c0b2f54ba4](https://linux-hardware.org/?probe=c0b2f54ba4) | May 07, 2021 |
| Dell          | Precision 5530              | [ec979f10db](https://linux-hardware.org/?probe=ec979f10db) | May 06, 2021 |
| ASUSTek       | S400CA                      | [15f5f5c525](https://linux-hardware.org/?probe=15f5f5c525) | May 05, 2021 |
| Acer          | Aspire R3-471TG             | [7fff1e0b4e](https://linux-hardware.org/?probe=7fff1e0b4e) | May 05, 2021 |
| AMI           | T3 MRD                      | [5be7ed690e](https://linux-hardware.org/?probe=5be7ed690e) | May 05, 2021 |
| AMI           | T3 MRD                      | [e7942d97e3](https://linux-hardware.org/?probe=e7942d97e3) | May 05, 2021 |
| ASUSTek       | S400CA                      | [759a043b60](https://linux-hardware.org/?probe=759a043b60) | May 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [49d47a37d7](https://linux-hardware.org/?probe=49d47a37d7) | May 03, 2021 |
| Apple         | MacBookPro10,2              | [ff18f266ee](https://linux-hardware.org/?probe=ff18f266ee) | May 03, 2021 |
| Acer          | Aspire R3-471TG             | [302e5f483d](https://linux-hardware.org/?probe=302e5f483d) | May 02, 2021 |
| Dell          | Precision 5530              | [0fe92c8a70](https://linux-hardware.org/?probe=0fe92c8a70) | May 02, 2021 |
| Dell          | Latitude E6400              | [fbe4173413](https://linux-hardware.org/?probe=fbe4173413) | May 01, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ed31cafb3f](https://linux-hardware.org/?probe=ed31cafb3f) | Apr 30, 2021 |
| Dell          | G3 3590                     | [1e15ce5e51](https://linux-hardware.org/?probe=1e15ce5e51) | Apr 29, 2021 |
| Dell          | G3 3590                     | [8c3a77febc](https://linux-hardware.org/?probe=8c3a77febc) | Apr 29, 2021 |
| Gigabyte      | AORUS 5 SB                  | [ace32de58d](https://linux-hardware.org/?probe=ace32de58d) | Apr 29, 2021 |
| Dell          | Inspiron M5010              | [7a3c6ec0cb](https://linux-hardware.org/?probe=7a3c6ec0cb) | Apr 29, 2021 |
| HP            | ENVY Notebook               | [61cb15af98](https://linux-hardware.org/?probe=61cb15af98) | Apr 28, 2021 |
| Apple         | MacBookPro12,1              | [f96442f3e2](https://linux-hardware.org/?probe=f96442f3e2) | Apr 27, 2021 |
| Apple         | MacBookPro12,1              | [36d9c14fcd](https://linux-hardware.org/?probe=36d9c14fcd) | Apr 27, 2021 |
| Gigabyte      | AORUS 5 SB                  | [186fd87862](https://linux-hardware.org/?probe=186fd87862) | Apr 26, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [2338b3504c](https://linux-hardware.org/?probe=2338b3504c) | Apr 26, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [6cea24fbd6](https://linux-hardware.org/?probe=6cea24fbd6) | Apr 26, 2021 |
| ASUSTek       | K55VM                       | [cc3271f828](https://linux-hardware.org/?probe=cc3271f828) | Apr 24, 2021 |
| Dell          | Vostro 5402                 | [bd53dff836](https://linux-hardware.org/?probe=bd53dff836) | Apr 23, 2021 |
| ASUSTek       | X550ZE                      | [a9699f83eb](https://linux-hardware.org/?probe=a9699f83eb) | Apr 23, 2021 |
| HP            | Pavilion dv6                | [482481e697](https://linux-hardware.org/?probe=482481e697) | Apr 23, 2021 |
| Acer          | Aspire R3-131T              | [1d52101f3a](https://linux-hardware.org/?probe=1d52101f3a) | Apr 23, 2021 |
| ASUSTek       | N550JV                      | [1a2e40a1a3](https://linux-hardware.org/?probe=1a2e40a1a3) | Apr 22, 2021 |
| HP            | Pavilion dv6                | [5c28876cd8](https://linux-hardware.org/?probe=5c28876cd8) | Apr 21, 2021 |
| Notebook      | P570WM                      | [de166d9bf2](https://linux-hardware.org/?probe=de166d9bf2) | Apr 21, 2021 |
| ASUSTek       | N53SV                       | [f17ed783f4](https://linux-hardware.org/?probe=f17ed783f4) | Apr 21, 2021 |
| Dell          | Inspiron 3593               | [caffbbc328](https://linux-hardware.org/?probe=caffbbc328) | Apr 20, 2021 |
| Dell          | G3 3500                     | [d1a4723065](https://linux-hardware.org/?probe=d1a4723065) | Apr 20, 2021 |
| Dell          | G3 3500                     | [3295e38ea9](https://linux-hardware.org/?probe=3295e38ea9) | Apr 20, 2021 |
| ASUSTek       | ZenBook UX434FLC_UX434FL... | [66c0c59e60](https://linux-hardware.org/?probe=66c0c59e60) | Apr 20, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [b15e3f2469](https://linux-hardware.org/?probe=b15e3f2469) | Apr 19, 2021 |
| ASUSTek       | N550JV                      | [28ca0db888](https://linux-hardware.org/?probe=28ca0db888) | Apr 19, 2021 |
| MSI           | GS65 Stealth Thin 8RF       | [91bed95d04](https://linux-hardware.org/?probe=91bed95d04) | Apr 19, 2021 |
| ASUSTek       | G74Sx                       | [e7a0651458](https://linux-hardware.org/?probe=e7a0651458) | Apr 18, 2021 |
| ASUSTek       | G74Sx                       | [59569e3bcd](https://linux-hardware.org/?probe=59569e3bcd) | Apr 18, 2021 |
| MSI           | GL75 9SD                    | [0d103513e8](https://linux-hardware.org/?probe=0d103513e8) | Apr 16, 2021 |
| Dell          | Inspiron N5010              | [48e6d0cfc8](https://linux-hardware.org/?probe=48e6d0cfc8) | Apr 15, 2021 |
| Gigabyte      | P55V5                       | [d1ae3cbd0a](https://linux-hardware.org/?probe=d1ae3cbd0a) | Apr 15, 2021 |
| Lenovo        | ThinkPad P53 20QQS2KB00     | [9f7d3fce4b](https://linux-hardware.org/?probe=9f7d3fce4b) | Apr 14, 2021 |
| MSI           | GX60 3CC                    | [0725dd67d5](https://linux-hardware.org/?probe=0725dd67d5) | Apr 14, 2021 |
| Lenovo        | ThinkPad P53 20QQS2KB00     | [33efde8314](https://linux-hardware.org/?probe=33efde8314) | Apr 14, 2021 |
| Acer          | Aspire A515-52              | [7df51d92eb](https://linux-hardware.org/?probe=7df51d92eb) | Apr 13, 2021 |
| HP            | ProBook 450 G3              | [37502c4abe](https://linux-hardware.org/?probe=37502c4abe) | Apr 12, 2021 |
| HP            | ProBook 450 G3              | [416997431c](https://linux-hardware.org/?probe=416997431c) | Apr 11, 2021 |
| Dell          | Precision 5530              | [d49ad63dc7](https://linux-hardware.org/?probe=d49ad63dc7) | Apr 11, 2021 |
| MSI           | GS65 Stealth Thin 8RF       | [68a28aad12](https://linux-hardware.org/?probe=68a28aad12) | Apr 11, 2021 |
| MSI           | GX60 3CC                    | [9db9934ac7](https://linux-hardware.org/?probe=9db9934ac7) | Apr 11, 2021 |
| Toshiba       | Satellite P750              | [d248a5f049](https://linux-hardware.org/?probe=d248a5f049) | Apr 11, 2021 |
| Toshiba       | PORTEGE Z30t-C              | [39dd5ca43b](https://linux-hardware.org/?probe=39dd5ca43b) | Apr 11, 2021 |
| ASUSTek       | K53SV                       | [1598c6ea75](https://linux-hardware.org/?probe=1598c6ea75) | Apr 09, 2021 |
| Dell          | Precision 5540              | [35b7cbfdb5](https://linux-hardware.org/?probe=35b7cbfdb5) | Apr 08, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 191       | 15.02%  |
| Ubuntu 18.04                 | 82        | 6.45%   |
| Ubuntu 22.04                 | 30        | 2.36%   |
| KDE neon 20.04               | 30        | 2.36%   |
| Fedora 36                    | 29        | 2.28%   |
| Pop!_OS 21.04                | 27        | 2.12%   |
| Linux Mint 20.2              | 27        | 2.12%   |
| Pop!_OS 22.04                | 26        | 2.04%   |
| Pop!_OS 20.04                | 24        | 1.89%   |
| Debian 11                    | 24        | 1.89%   |
| Arch                         | 24        | 1.89%   |
| OpenMandriva 4.3             | 23        | 1.81%   |
| Linux Mint 20.3              | 23        | 1.81%   |
| Zorin 16                     | 22        | 1.73%   |
| Linux Mint 20                | 22        | 1.73%   |
| Ubuntu 20.10                 | 21        | 1.65%   |
| OpenMandriva 4.2             | 20        | 1.57%   |
| Pop!_OS 20.10                | 19        | 1.49%   |
| Linux Mint 20.1              | 19        | 1.49%   |
| Ubuntu 21.10                 | 18        | 1.42%   |
| Ubuntu 19.04                 | 18        | 1.42%   |
| Manjaro                      | 18        | 1.42%   |
| Ubuntu 19.10                 | 17        | 1.34%   |
| Fedora 33                    | 16        | 1.26%   |
| Arch Rolling                 | 16        | 1.26%   |
| Zorin 15                     | 15        | 1.18%   |
| Ubuntu 21.04                 | 14        | 1.1%    |
| Fedora 35                    | 14        | 1.1%    |
| Xubuntu 18.04                | 12        | 0.94%   |
| Linux Mint 21                | 12        | 0.94%   |
| Fedora 32                    | 12        | 0.94%   |
| ArcoLinux Rolling            | 12        | 0.94%   |
| Xubuntu 20.04                | 10        | 0.79%   |
| Linux Mint 19.3              | 9         | 0.71%   |
| Kubuntu 20.04                | 9         | 0.71%   |
| Fedora 34                    | 9         | 0.71%   |
| Ubuntu 18.10                 | 8         | 0.63%   |
| Pop!_OS 21.10                | 8         | 0.63%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 0.63%   |
| Elementary 6.1               | 8         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 383       | 32.1%   |
| Linux Mint    | 116       | 9.72%   |
| Pop!_OS       | 98        | 8.21%   |
| Fedora        | 83        | 6.96%   |
| OpenMandriva  | 54        | 4.53%   |
| Zorin         | 44        | 3.69%   |
| Manjaro       | 42        | 3.52%   |
| Debian        | 41        | 3.44%   |
| Arch          | 40        | 3.35%   |
| KDE neon      | 33        | 2.77%   |
| Xubuntu       | 31        | 2.6%    |
| Kubuntu       | 22        | 1.84%   |
| Elementary    | 20        | 1.68%   |
| Kali          | 16        | 1.34%   |
| Gentoo        | 15        | 1.26%   |
| ArcoLinux     | 12        | 1.01%   |
| Endless       | 11        | 0.92%   |
| Clear Linux   | 11        | 0.92%   |
| Ubuntu Unity  | 10        | 0.84%   |
| ROSA          | 10        | 0.84%   |
| Lubuntu       | 10        | 0.84%   |
| openSUSE      | 9         | 0.75%   |
| LMDE          | 7         | 0.59%   |
| LinuxFX       | 6         | 0.5%    |
| EndeavourOS   | 6         | 0.5%    |
| Ubuntu MATE   | 5         | 0.42%   |
| Parrot        | 5         | 0.42%   |
| Reborn OS     | 4         | 0.34%   |
| MX            | 4         | 0.34%   |
| BlackPanther  | 4         | 0.34%   |
| Ubuntu Budgie | 3         | 0.25%   |
| Solus         | 3         | 0.25%   |
| Xero          | 2         | 0.17%   |
| RHEL          | 2         | 0.17%   |
| PureOS        | 2         | 0.17%   |
| Oracle Linux  | 2         | 0.17%   |
| Linux Lite    | 2         | 0.17%   |
| CentOS        | 2         | 0.17%   |
| Calculate     | 2         | 0.17%   |
| antiX         | 2         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 33        | 2.33%   |
| 5.16.7-desktop-1omv4003  | 22        | 1.55%   |
| 5.10.14-desktop-1omv4002 | 20        | 1.41%   |
| 5.4.0-58-generic         | 18        | 1.27%   |
| 5.4.0-26-generic         | 15        | 1.06%   |
| 5.4.0-40-generic         | 14        | 0.99%   |
| 5.11.0-7620-generic      | 14        | 0.99%   |
| 5.4.0-29-generic         | 13        | 0.92%   |
| 5.4.0-48-generic         | 12        | 0.85%   |
| 5.11.0-38-generic        | 12        | 0.85%   |
| 5.17.5-76051705-generic  | 11        | 0.78%   |
| 5.11.0-37-generic        | 11        | 0.78%   |
| 5.11.0-27-generic        | 11        | 0.78%   |
| 5.4.0-52-generic         | 10        | 0.71%   |
| 5.8.0-63-generic         | 9         | 0.63%   |
| 5.4.0-81-generic         | 9         | 0.63%   |
| 5.4.0-74-generic         | 9         | 0.63%   |
| 5.3.0-40-generic         | 9         | 0.63%   |
| 5.8.0-7630-generic       | 8         | 0.56%   |
| 5.8.0-59-generic         | 8         | 0.56%   |
| 5.4.0-7634-generic       | 8         | 0.56%   |
| 5.4.0-65-generic         | 8         | 0.56%   |
| 5.4.0-54-generic         | 8         | 0.56%   |
| 5.3.0-28-generic         | 8         | 0.56%   |
| 5.13.0-7620-generic      | 8         | 0.56%   |
| 5.13.0-40-generic        | 8         | 0.56%   |
| 5.11.0-40-generic        | 8         | 0.56%   |
| 5.0.0-13-generic         | 8         | 0.56%   |
| 5.8.0-7642-generic       | 7         | 0.49%   |
| 5.8.0-53-generic         | 7         | 0.49%   |
| 5.8.0-50-generic         | 7         | 0.49%   |
| 5.4.0-91-generic         | 7         | 0.49%   |
| 5.4.0-7642-generic       | 7         | 0.49%   |
| 5.4.0-47-generic         | 7         | 0.49%   |
| 5.4.0-31-generic         | 7         | 0.49%   |
| 5.3.0-46-generic         | 7         | 0.49%   |
| 5.15.0-48-generic        | 7         | 0.49%   |
| 5.15.0-46-generic        | 7         | 0.49%   |
| 4.18.0-17-generic        | 7         | 0.49%   |
| 5.8.0-55-generic         | 6         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 260       | 19.85%  |
| 5.11.0  | 101       | 7.71%   |
| 5.8.0   | 84        | 6.41%   |
| 5.13.0  | 78        | 5.95%   |
| 4.15.0  | 68        | 5.19%   |
| 5.15.0  | 63        | 4.81%   |
| 5.3.0   | 52        | 3.97%   |
| 5.0.0   | 41        | 3.13%   |
| 5.10.0  | 33        | 2.52%   |
| 4.18.0  | 30        | 2.29%   |
| 5.16.7  | 23        | 1.76%   |
| 5.10.14 | 20        | 1.53%   |
| 5.17.5  | 17        | 1.3%    |
| 5.19.0  | 12        | 0.92%   |
| 4.19.0  | 11        | 0.84%   |
| 5.18.10 | 8         | 0.61%   |
| 5.18.0  | 8         | 0.61%   |
| 5.18.12 | 6         | 0.46%   |
| 5.17.15 | 6         | 0.46%   |
| 6.0.9   | 5         | 0.38%   |
| 6.0.0   | 5         | 0.38%   |
| 5.8.16  | 5         | 0.38%   |
| 5.16.11 | 5         | 0.38%   |
| 5.16.0  | 5         | 0.38%   |
| 5.14.0  | 5         | 0.38%   |
| 5.12.4  | 5         | 0.38%   |
| 4.9.60  | 5         | 0.38%   |
| 6.0.7   | 4         | 0.31%   |
| 5.9.16  | 4         | 0.31%   |
| 5.18.7  | 4         | 0.31%   |
| 5.16.2  | 4         | 0.31%   |
| 5.16.19 | 4         | 0.31%   |
| 5.15.72 | 4         | 0.31%   |
| 5.15.11 | 4         | 0.31%   |
| 5.13.12 | 4         | 0.31%   |
| 4.4.0   | 4         | 0.31%   |
| 6.0.8   | 3         | 0.23%   |
| 5.9.10  | 3         | 0.23%   |
| 5.9.0   | 3         | 0.23%   |
| 5.8.12  | 3         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 283       | 22.02%  |
| 5.11    | 115       | 8.95%   |
| 5.8     | 101       | 7.86%   |
| 5.15    | 99        | 7.7%    |
| 5.13    | 92        | 7.16%   |
| 5.10    | 77        | 5.99%   |
| 4.15    | 68        | 5.29%   |
| 5.3     | 56        | 4.36%   |
| 5.16    | 56        | 4.36%   |
| 5.0     | 45        | 3.5%    |
| 5.17    | 38        | 2.96%   |
| 5.18    | 35        | 2.72%   |
| 4.18    | 34        | 2.65%   |
| 5.19    | 27        | 2.1%    |
| 6.0     | 22        | 1.71%   |
| 5.6     | 18        | 1.4%    |
| 5.9     | 17        | 1.32%   |
| 5.12    | 15        | 1.17%   |
| 5.14    | 14        | 1.09%   |
| 4.19    | 14        | 1.09%   |
| 5.5     | 12        | 0.93%   |
| 5.7     | 11        | 0.86%   |
| 4.9     | 11        | 0.86%   |
| 5.2     | 5         | 0.39%   |
| 4.4     | 4         | 0.31%   |
| 4.1     | 3         | 0.23%   |
| 5.1     | 2         | 0.16%   |
| 4.20    | 2         | 0.16%   |
| 3.16    | 2         | 0.16%   |
| 3.10    | 2         | 0.16%   |
| 6.1     | 1         | 0.08%   |
| 4.8     | 1         | 0.08%   |
| 4.14    | 1         | 0.08%   |
| 4.13    | 1         | 0.08%   |
| 4.11    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1089      | 97.06%  |
| i686    | 29        | 2.58%   |
| i586    | 2         | 0.18%   |
| aarch64 | 2         | 0.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 543       | 45.17%  |
| KDE5            | 163       | 13.56%  |
| Unknown         | 146       | 12.15%  |
| X-Cinnamon      | 101       | 8.4%    |
| XFCE            | 86        | 7.15%   |
| KDE             | 32        | 2.66%   |
| MATE            | 25        | 2.08%   |
| Pantheon        | 18        | 1.5%    |
| Cinnamon        | 18        | 1.5%    |
| Unity           | 12        | 1%      |
| i3              | 11        | 0.92%   |
| LXQt            | 8         | 0.67%   |
| LXDE            | 8         | 0.67%   |
| KDE4            | 8         | 0.67%   |
| Deepin          | 6         | 0.5%    |
| Budgie          | 6         | 0.5%    |
| awesome         | 3         | 0.25%   |
| openbox         | 2         | 0.17%   |
| GNOME Flashback | 2         | 0.17%   |
| sway            | 1         | 0.08%   |
| qtile           | 1         | 0.08%   |
| icewm           | 1         | 0.08%   |
| dusk            | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 915       | 78.61%  |
| Wayland | 145       | 12.46%  |
| Unknown | 80        | 6.87%   |
| Tty     | 24        | 2.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 669       | 56.94%  |
| GDM     | 144       | 12.26%  |
| SDDM    | 129       | 10.98%  |
| LightDM | 101       | 8.6%    |
| GDM3    | 79        | 6.72%   |
| TDM     | 39        | 3.32%   |
| KDM     | 8         | 0.68%   |
| SLiM    | 2         | 0.17%   |
| LXDM    | 2         | 0.17%   |
| XDM     | 1         | 0.09%   |
| GREETD  | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_AU        | 828       | 70.95%  |
| en_US        | 157       | 13.45%  |
| Unknown      | 130       | 11.14%  |
| C            | 26        | 2.23%   |
| en_GB        | 14        | 1.2%    |
| C.UTF8       | 4         | 0.34%   |
| zh_CN        | 1         | 0.09%   |
| ru_RU        | 1         | 0.09%   |
| fr_FR        | 1         | 0.09%   |
| es_ES        | 1         | 0.09%   |
| en_IN        | 1         | 0.09%   |
| en_GB.UTF-12 | 1         | 0.09%   |
| en_CA        | 1         | 0.09%   |
| de_DE        | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 583       | 50.56%  |
| BIOS | 570       | 49.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 911       | 78.53%  |
| Btrfs   | 92        | 7.93%   |
| Overlay | 76        | 6.55%   |
| Unknown | 39        | 3.36%   |
| Xfs     | 15        | 1.29%   |
| Zfs     | 13        | 1.12%   |
| Tmpfs   | 4         | 0.34%   |
| Ext2    | 4         | 0.34%   |
| XXXXXXX | 3         | 0.26%   |
| Ext3    | 3         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 713       | 62.33%  |
| GPT     | 327       | 28.58%  |
| MBR     | 104       | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1012      | 88.69%  |
| Yes       | 129       | 11.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 882       | 77.1%   |
| Yes       | 262       | 22.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 204       | 18.21%  |
| Dell                           | 194       | 17.32%  |
| Lenovo                         | 182       | 16.25%  |
| ASUSTek Computer               | 106       | 9.46%   |
| Acer                           | 102       | 9.11%   |
| Toshiba                        | 87        | 7.77%   |
| Apple                          | 72        | 6.43%   |
| MSI                            | 26        | 2.32%   |
| Alienware                      | 14        | 1.25%   |
| Samsung Electronics            | 12        | 1.07%   |
| Sony                           | 10        | 0.89%   |
| Notebook                       | 10        | 0.89%   |
| Gigabyte Technology            | 9         | 0.8%    |
| Timi                           | 8         | 0.71%   |
| IT Channel Pty                 | 7         | 0.63%   |
| Razer                          | 6         | 0.54%   |
| Panasonic                      | 6         | 0.54%   |
| Metabox                        | 6         | 0.54%   |
| HUAWEI                         | 6         | 0.54%   |
| Unknown                        | 5         | 0.45%   |
| System76                       | 4         | 0.36%   |
| Medion                         | 3         | 0.27%   |
| LG Electronics                 | 3         | 0.27%   |
| Intel Client Systems           | 3         | 0.27%   |
| Google                         | 3         | 0.27%   |
| Framework                      | 3         | 0.27%   |
| AMI                            | 3         | 0.27%   |
| Purism                         | 2         | 0.18%   |
| Pine Microsystems              | 2         | 0.18%   |
| Kogan                          | 2         | 0.18%   |
| IBM                            | 2         | 0.18%   |
| Star Labs                      | 1         | 0.09%   |
| Pendo Industries               | 1         | 0.09%   |
| ONE-NETBOOK TECHNOLOGY         | 1         | 0.09%   |
| One Education                  | 1         | 0.09%   |
| OEM                            | 1         | 0.09%   |
| Matsushita Electric Industrial | 1         | 0.09%   |
| LEADER                         | 1         | 0.09%   |
| Intel                          | 1         | 0.09%   |
| Insyde                         | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| HP Pavilion dv6                                    | 14        | 1.25%   |
| HP Pavilion g6                                     | 11        | 0.98%   |
| HP Notebook                                        | 9         | 0.8%    |
| HP Pavilion 15                                     | 8         | 0.71%   |
| Unknown                                            | 8         | 0.71%   |
| Apple MacBookPro9,2                                | 7         | 0.63%   |
| Apple MacBookPro10,1                               | 6         | 0.54%   |
| Acer ConceptD CN315-71P                            | 6         | 0.54%   |
| Dell XPS 15 9560                                   | 5         | 0.45%   |
| Apple MacBookPro8,1                                | 5         | 0.45%   |
| Acer Aspire 5750G                                  | 5         | 0.45%   |
| Toshiba Satellite P750                             | 4         | 0.36%   |
| Toshiba Satellite L850                             | 4         | 0.36%   |
| Toshiba Satellite L500                             | 4         | 0.36%   |
| Toshiba Satellite L50-A                            | 4         | 0.36%   |
| Lenovo IdeaPad 1 14IGL05 81VU                      | 4         | 0.36%   |
| Lenovo G50-45 80E3                                 | 4         | 0.36%   |
| Dell XPS 15 9570                                   | 4         | 0.36%   |
| Dell XPS 15 9500                                   | 4         | 0.36%   |
| Dell XPS 13 9370                                   | 4         | 0.36%   |
| Dell XPS 13 9360                                   | 4         | 0.36%   |
| Dell XPS 13 7390                                   | 4         | 0.36%   |
| Dell Precision 5530                                | 4         | 0.36%   |
| Dell Latitude E7450                                | 4         | 0.36%   |
| Dell Latitude E7440                                | 4         | 0.36%   |
| Dell Latitude E6430                                | 4         | 0.36%   |
| Dell Inspiron 1545                                 | 4         | 0.36%   |
| Apple MacBookAir7,2                                | 4         | 0.36%   |
| Apple MacBookAir6,2                                | 4         | 0.36%   |
| Toshiba Satellite P850                             | 3         | 0.27%   |
| Toshiba Satellite L750                             | 3         | 0.27%   |
| Toshiba Satellite L50-B                            | 3         | 0.27%   |
| Toshiba Satellite C660                             | 3         | 0.27%   |
| Toshiba Satellite C50D-A                           | 3         | 0.27%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 3         | 0.27%   |
| Lenovo Yoga 3 Pro-1370 80HE                        | 3         | 0.27%   |
| HP ProBook 430 G2                                  | 3         | 0.27%   |
| HP Presario CQ62                                   | 3         | 0.27%   |
| HP Pavilion Notebook                               | 3         | 0.27%   |
| HP Pavilion dv7                                    | 3         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 118       | 10.54%  |
| Acer Aspire        | 73        | 6.52%   |
| Toshiba Satellite  | 72        | 6.43%   |
| Dell Latitude      | 65        | 5.8%    |
| HP Pavilion        | 58        | 5.18%   |
| Dell Inspiron      | 48        | 4.29%   |
| Dell XPS           | 44        | 3.93%   |
| HP EliteBook       | 39        | 3.48%   |
| Lenovo IdeaPad     | 28        | 2.5%    |
| HP ProBook         | 25        | 2.23%   |
| Dell Precision     | 18        | 1.61%   |
| HP Laptop          | 17        | 1.52%   |
| HP ENVY            | 12        | 1.07%   |
| Lenovo Yoga        | 10        | 0.89%   |
| ASUS ZenBook       | 10        | 0.89%   |
| HP Notebook        | 9         | 0.8%    |
| Apple MacBookPro10 | 9         | 0.8%    |
| Acer Swift         | 9         | 0.8%    |
| HP 250             | 8         | 0.71%   |
| ASUS VivoBook      | 8         | 0.71%   |
| Apple MacBookPro9  | 8         | 0.71%   |
| Unknown            | 8         | 0.71%   |
| Toshiba PORTEGE    | 7         | 0.63%   |
| ASUS ROG           | 7         | 0.63%   |
| Apple MacBookAir6  | 7         | 0.63%   |
| Toshiba TECRA      | 6         | 0.54%   |
| Razer Blade        | 6         | 0.54%   |
| Lenovo Legion      | 6         | 0.54%   |
| HP ZBook           | 6         | 0.54%   |
| ASUS TUF           | 6         | 0.54%   |
| Acer ConceptD      | 6         | 0.54%   |
| HP Presario        | 5         | 0.45%   |
| HP Compaq          | 5         | 0.45%   |
| Dell G3            | 5         | 0.45%   |
| Apple MacBookPro8  | 5         | 0.45%   |
| Apple MacBookPro6  | 5         | 0.45%   |
| Apple MacBookPro11 | 5         | 0.45%   |
| Acer Nitro         | 5         | 0.45%   |
| Lenovo G50-45      | 4         | 0.36%   |
| HP OMEN            | 4         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 109       | 9.73%   |
| 2020    | 98        | 8.75%   |
| 2011    | 93        | 8.3%    |
| 2013    | 88        | 7.86%   |
| 2018    | 86        | 7.68%   |
| 2012    | 86        | 7.68%   |
| 2014    | 81        | 7.23%   |
| 2010    | 70        | 6.25%   |
| 2017    | 69        | 6.16%   |
| 2015    | 69        | 6.16%   |
| 2021    | 68        | 6.07%   |
| 2016    | 66        | 5.89%   |
| 2008    | 46        | 4.11%   |
| 2009    | 38        | 3.39%   |
| 2022    | 20        | 1.79%   |
| 2007    | 17        | 1.52%   |
| 2006    | 5         | 0.45%   |
| 2005    | 5         | 0.45%   |
| Unknown | 5         | 0.45%   |
| 2003    | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1120      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 995       | 87.98%  |
| Enabled  | 136       | 12.02%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1112      | 99.29%  |
| Yes  | 8         | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 315       | 27.73%  |
| 16.01-24.0  | 243       | 21.39%  |
| 3.01-4.0    | 240       | 21.13%  |
| 8.01-16.0   | 164       | 14.44%  |
| 32.01-64.0  | 92        | 8.1%    |
| 1.01-2.0    | 47        | 4.14%   |
| 64.01-256.0 | 10        | 0.88%   |
| 24.01-32.0  | 9         | 0.79%   |
| 2.01-3.0    | 9         | 0.79%   |
| 0.51-1.0    | 4         | 0.35%   |
| 0.01-0.5    | 3         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 460       | 35.69%  |
| 2.01-3.0   | 364       | 28.24%  |
| 4.01-8.0   | 158       | 12.26%  |
| 3.01-4.0   | 144       | 11.17%  |
| 0.51-1.0   | 84        | 6.52%   |
| 8.01-16.0  | 56        | 4.34%   |
| 0.01-0.5   | 15        | 1.16%   |
| 16.01-24.0 | 4         | 0.31%   |
| 24.01-32.0 | 2         | 0.16%   |
| 0          | 2         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 828       | 70.89%  |
| 2      | 263       | 22.52%  |
| 3      | 51        | 4.37%   |
| 0      | 15        | 1.28%   |
| 4      | 8         | 0.68%   |
| 5      | 2         | 0.17%   |
| 7      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 692       | 61.29%  |
| Yes       | 437       | 38.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 926       | 82.53%  |
| No        | 196       | 17.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1099      | 97.95%  |
| No        | 23        | 2.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 867       | 76.19%  |
| No        | 271       | 23.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 1120      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sydney         | 309       | 25.77%  |
| Melbourne      | 242       | 20.18%  |
| Brisbane       | 189       | 15.76%  |
| Perth          | 90        | 7.51%   |
| Adelaide       | 64        | 5.34%   |
| Canberra       | 21        | 1.75%   |
| Hobart         | 17        | 1.42%   |
| Launceston     | 6         | 0.5%    |
| Central Coast  | 6         | 0.5%    |
| Woolloongabba  | 5         | 0.42%   |
| Southport      | 5         | 0.42%   |
| Parramatta     | 5         | 0.42%   |
| Newcastle      | 5         | 0.42%   |
| Mitcham        | 5         | 0.42%   |
| Gold Coast     | 5         | 0.42%   |
| Wollongong     | 4         | 0.33%   |
| West End       | 4         | 0.33%   |
| Wahroonga      | 4         | 0.33%   |
| Traralgon      | 4         | 0.33%   |
| Point Cook     | 4         | 0.33%   |
| Mandurah       | 4         | 0.33%   |
| Artarmon       | 4         | 0.33%   |
| Alexandria     | 4         | 0.33%   |
| Townsville     | 3         | 0.25%   |
| Surry Hills    | 3         | 0.25%   |
| Spring Field   | 3         | 0.25%   |
| Richmond       | 3         | 0.25%   |
| Parkdale       | 3         | 0.25%   |
| Mount Waverley | 3         | 0.25%   |
| Hawthorn       | 3         | 0.25%   |
| Geraldton      | 3         | 0.25%   |
| Geelong        | 3         | 0.25%   |
| Doncaster      | 3         | 0.25%   |
| Clifton Hill   | 3         | 0.25%   |
| Brighton       | 3         | 0.25%   |
| Warragul       | 2         | 0.17%   |
| Sandy Bay      | 2         | 0.17%   |
| Ryde           | 2         | 0.17%   |
| Redfern        | 2         | 0.17%   |
| Quinns Rocks   | 2         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 251       | 315    | 18.02%  |
| WDC                       | 161       | 230    | 11.56%  |
| Seagate                   | 158       | 234    | 11.34%  |
| Toshiba                   | 129       | 191    | 9.26%   |
| Unknown                   | 65        | 87     | 4.67%   |
| SanDisk                   | 63        | 81     | 4.52%   |
| Intel                     | 59        | 89     | 4.24%   |
| Kingston                  | 55        | 70     | 3.95%   |
| SK hynix                  | 54        | 71     | 3.88%   |
| Hitachi                   | 52        | 64     | 3.73%   |
| Crucial                   | 49        | 65     | 3.52%   |
| Apple                     | 43        | 58     | 3.09%   |
| HGST                      | 41        | 59     | 2.94%   |
| Micron Technology         | 34        | 41     | 2.44%   |
| KIOXIA                    | 17        | 19     | 1.22%   |
| Phison                    | 12        | 15     | 0.86%   |
| Fujitsu                   | 12        | 16     | 0.86%   |
| LITEON                    | 11        | 14     | 0.79%   |
| A-DATA Technology         | 10        | 13     | 0.72%   |
| LITEONIT                  | 7         | 9      | 0.5%    |
| OCZ                       | 6         | 8      | 0.43%   |
| JMicron Technology        | 6         | 8      | 0.43%   |
| SPCC                      | 5         | 6      | 0.36%   |
| Micron/Crucial Technology | 5         | 5      | 0.36%   |
| Transcend                 | 4         | 5      | 0.29%   |
| Phison Electronics        | 4         | 4      | 0.29%   |
| Patriot                   | 4         | 5      | 0.29%   |
| KingSpec                  | 4         | 7      | 0.29%   |
| China                     | 4         | 4      | 0.29%   |
| XPG                       | 3         | 3      | 0.22%   |
| OWC                       | 3         | 6      | 0.22%   |
| Lite-On                   | 3         | 3      | 0.22%   |
| LaCie                     | 3         | 7      | 0.22%   |
| ASMT                      | 3         | 4      | 0.22%   |
| TO Exter                  | 2         | 2      | 0.14%   |
| Realtek Semiconductor     | 2         | 3      | 0.14%   |
| Plextor                   | 2         | 6      | 0.14%   |
| Lenovo                    | 2         | 3      | 0.14%   |
| KingFast                  | 2         | 2      | 0.14%   |
| KESU                      | 2         | 2      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                 | 17        | 1.17%   |
| Unknown MMC Card  64GB                 | 16        | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 15        | 1.03%   |
| SanDisk NVMe SSD Drive 512GB           | 14        | 0.96%   |
| Seagate ST500LT012-1DG142 500GB        | 13        | 0.9%    |
| Seagate Expansion 1TB                  | 13        | 0.9%    |
| Samsung NVMe SSD Drive 512GB           | 13        | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB         | 12        | 0.83%   |
| Toshiba MQ01ABF050 500GB               | 11        | 0.76%   |
| Samsung SSD 860 EVO 500GB              | 11        | 0.76%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 10        | 0.69%   |
| HGST HTS721010A9E630 1TB               | 10        | 0.69%   |
| Unknown MMC Card  32GB                 | 9         | 0.62%   |
| SK hynix NVMe SSD Drive 256GB          | 9         | 0.62%   |
| Samsung SSD 850 EVO 250GB              | 9         | 0.62%   |
| Unknown MMC Card  128GB                | 8         | 0.55%   |
| Toshiba NVMe SSD Drive 512GB           | 8         | 0.55%   |
| Toshiba MQ01ABD075 752GB               | 8         | 0.55%   |
| Seagate ST9500325AS 500GB              | 8         | 0.55%   |
| SanDisk NVMe SSD Drive 256GB           | 8         | 0.55%   |
| Kingston SA400S37240G 240GB SSD        | 8         | 0.55%   |
| Intel NVMe SSD Drive 512GB             | 8         | 0.55%   |
| HGST HTS545050A7E680 500GB             | 8         | 0.55%   |
| Crucial CT500MX500SSD1 500GB           | 8         | 0.55%   |
| Crucial CT1000MX500SSD1 1TB            | 8         | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB               | 7         | 0.48%   |
| Toshiba MQ04ABF100 1TB                 | 7         | 0.48%   |
| Seagate ST2000LM007-1R8174 2TB         | 7         | 0.48%   |
| Samsung NVMe SSD Drive 500GB           | 7         | 0.48%   |
| Micron NVMe SSD Drive 512GB            | 7         | 0.48%   |
| Kingston SA400S37120G 120GB SSD        | 7         | 0.48%   |
| Hitachi HTS547575A9E384 752GB          | 7         | 0.48%   |
| Hitachi HTS545050B9A300 500GB          | 7         | 0.48%   |
| HGST HTS725050A7E630 500GB             | 7         | 0.48%   |
| HGST HTS541010A9E680 1TB               | 7         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 6         | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 6         | 0.41%   |
| Unknown MMC Card  16GB                 | 6         | 0.41%   |
| Seagate ST750LM022 HN-M750MBB 752GB    | 6         | 0.41%   |
| Seagate ST500LM021-1KJ152 500GB        | 6         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 153       | 227    | 31.55%  |
| WDC                 | 111       | 159    | 22.89%  |
| Toshiba             | 83        | 130    | 17.11%  |
| Hitachi             | 52        | 64     | 10.72%  |
| HGST                | 41        | 59     | 8.45%   |
| Samsung Electronics | 12        | 14     | 2.47%   |
| Fujitsu             | 12        | 16     | 2.47%   |
| Apple               | 5         | 6      | 1.03%   |
| Unknown             | 4         | 4      | 0.82%   |
| LaCie               | 3         | 6      | 0.62%   |
| KESU                | 2         | 2      | 0.41%   |
| HGST HUS            | 2         | 2      | 0.41%   |
| ASMT                | 2         | 3      | 0.41%   |
| USB                 | 1         | 2      | 0.21%   |
| IBM/Hitachi         | 1         | 1      | 0.21%   |
| AAPL                | 1         | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 136       | 170    | 30.16%  |
| Crucial             | 45        | 61     | 9.98%   |
| Kingston            | 39        | 51     | 8.65%   |
| SanDisk             | 31        | 39     | 6.87%   |
| Apple               | 29        | 32     | 6.43%   |
| WDC                 | 23        | 28     | 5.1%    |
| Intel               | 22        | 39     | 4.88%   |
| Toshiba             | 19        | 26     | 4.21%   |
| SK hynix            | 18        | 24     | 3.99%   |
| Micron Technology   | 12        | 12     | 2.66%   |
| LITEON              | 10        | 13     | 2.22%   |
| LITEONIT            | 7         | 9      | 1.55%   |
| OCZ                 | 6         | 8      | 1.33%   |
| A-DATA Technology   | 6         | 8      | 1.33%   |
| SPCC                | 5         | 6      | 1.11%   |
| JMicron Technology  | 5         | 6      | 1.11%   |
| Transcend           | 4         | 5      | 0.89%   |
| Patriot             | 4         | 5      | 0.89%   |
| China               | 4         | 4      | 0.89%   |
| Seagate             | 3         | 4      | 0.67%   |
| OWC                 | 3         | 6      | 0.67%   |
| TO Exter            | 2         | 2      | 0.44%   |
| Plextor             | 2         | 6      | 0.44%   |
| KingSpec            | 2         | 4      | 0.44%   |
| FORESEE             | 2         | 2      | 0.44%   |
| T-CREATE            | 1         | 1      | 0.22%   |
| SAMSWEET            | 1         | 1      | 0.22%   |
| Mushkin             | 1         | 1      | 0.22%   |
| Kston               | 1         | 1      | 0.22%   |
| KingFast            | 1         | 1      | 0.22%   |
| KingDian            | 1         | 1      | 0.22%   |
| Gigabyte Technology | 1         | 1      | 0.22%   |
| Drevo               | 1         | 1      | 0.22%   |
| Corsair             | 1         | 1      | 0.22%   |
| Colorful            | 1         | 1      | 0.22%   |
| BP4e                | 1         | 2      | 0.22%   |
| BIWIN               | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 456       | 696    | 34.73%  |
| SSD     | 421       | 583    | 32.06%  |
| NVMe    | 355       | 500    | 27.04%  |
| MMC     | 60        | 80     | 4.57%   |
| Unknown | 21        | 24     | 1.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 778       | 1196   | 61.36%  |
| NVMe | 355       | 497    | 28%     |
| SAS  | 75        | 110    | 5.91%   |
| MMC  | 60        | 80     | 4.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 566       | 809    | 64.39%  |
| 0.51-1.0   | 258       | 381    | 29.35%  |
| 1.01-2.0   | 38        | 62     | 4.32%   |
| 4.01-10.0  | 11        | 20     | 1.25%   |
| 3.01-4.0   | 6         | 7      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 312       | 25.89%  |
| 251-500        | 298       | 24.73%  |
| 501-1000       | 195       | 16.18%  |
| 1-20           | 105       | 8.71%   |
| 51-100         | 91        | 7.55%   |
| 1001-2000      | 83        | 6.89%   |
| More than 3000 | 35        | 2.9%    |
| 21-50          | 32        | 2.66%   |
| Unknown        | 28        | 2.32%   |
| 2001-3000      | 26        | 2.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 532       | 41.66%  |
| 21-50          | 239       | 18.72%  |
| 51-100         | 142       | 11.12%  |
| 101-250        | 138       | 10.81%  |
| 251-500        | 96        | 7.52%   |
| 501-1000       | 56        | 4.39%   |
| Unknown        | 28        | 2.19%   |
| 1001-2000      | 26        | 2.04%   |
| More than 3000 | 10        | 0.78%   |
| 2001-3000      | 9         | 0.7%    |
| 0              | 1         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 5.17%   |
| Seagate ST9500325AS 500GB               | 2         | 2      | 3.45%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 3.45%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 3.45%   |
| HGST HTS545050A7E680 500GB              | 2         | 3      | 3.45%   |
| WDC WD6400BEVT-22A0RT0 640GB            | 1         | 1      | 1.72%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 1      | 1.72%   |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 3      | 1.72%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1         | 1      | 1.72%   |
| WDC WD2500BEVT-35A23T0 250GB            | 1         | 1      | 1.72%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 2      | 1.72%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 2      | 1.72%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 1         | 1      | 1.72%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1      | 1.72%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 1.72%   |
| Toshiba MK5055GSX 500GB                 | 1         | 4      | 1.72%   |
| Toshiba MK3265GSX 320GB                 | 1         | 1      | 1.72%   |
| Seagate ST9500423AS 500GB               | 1         | 2      | 1.72%   |
| Seagate ST9320423AS 320GB               | 1         | 2      | 1.72%   |
| Seagate ST9250410AS 250GB               | 1         | 1      | 1.72%   |
| Seagate ST9250315AS 250GB               | 1         | 1      | 1.72%   |
| Seagate ST9160821AS 160GB               | 1         | 4      | 1.72%   |
| Seagate ST9160310AS 160GB               | 1         | 1      | 1.72%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 2      | 1.72%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 2      | 1.72%   |
| Seagate ST320LT007-9ZV142 320GB         | 1         | 1      | 1.72%   |
| Samsung Electronics SSD 970 EVO 2TB     | 1         | 1      | 1.72%   |
| Samsung Electronics SSD 850 EVO 1TB     | 1         | 1      | 1.72%   |
| Samsung Electronics SSD 750 EVO 250GB   | 1         | 1      | 1.72%   |
| Samsung Electronics PM961 NVMe 512GB    | 1         | 1      | 1.72%   |
| Samsung Electronics HM641JI 640GB       | 1         | 1      | 1.72%   |
| Kingston SV300S37A240G 240GB SSD        | 1         | 1      | 1.72%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1      | 1.72%   |
| KingSpec PA25-128 128GB SSD             | 1         | 3      | 1.72%   |
| Intel SSDSC2CW060A3 64GB                | 1         | 2      | 1.72%   |
| Hitachi HTS725050A7E630 500GB           | 1         | 1      | 1.72%   |
| Hitachi HTS547564A9E384 640GB           | 1         | 1      | 1.72%   |
| Hitachi HTS547550A9E384 500GB           | 1         | 1      | 1.72%   |
| Hitachi HTS545050A7E380 500GB           | 1         | 1      | 1.72%   |
| Hitachi HTS543232A7A384 320GB           | 1         | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 26     | 31.03%  |
| Hitachi             | 8         | 8      | 13.79%  |
| WDC                 | 7         | 11     | 12.07%  |
| Toshiba             | 5         | 8      | 8.62%   |
| Samsung Electronics | 5         | 5      | 8.62%   |
| HGST                | 4         | 5      | 6.9%    |
| Fujitsu             | 3         | 3      | 5.17%   |
| Kingston            | 2         | 2      | 3.45%   |
| Crucial             | 2         | 2      | 3.45%   |
| KingSpec            | 1         | 3      | 1.72%   |
| Intel               | 1         | 2      | 1.72%   |
| Apple               | 1         | 1      | 1.72%   |
| A-DATA Technology   | 1         | 1      | 1.72%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 26     | 40%     |
| Hitachi             | 8         | 8      | 17.78%  |
| WDC                 | 7         | 11     | 15.56%  |
| Toshiba             | 4         | 7      | 8.89%   |
| HGST                | 4         | 5      | 8.89%   |
| Fujitsu             | 3         | 3      | 6.67%   |
| Samsung Electronics | 1         | 1      | 2.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 61     | 77.19%  |
| SSD  | 11        | 14     | 19.3%   |
| NVMe | 2         | 2      | 3.51%   |

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
| Detected | 751       | 1252   | 64.02%  |
| Works    | 365       | 554    | 31.12%  |
| Malfunc  | 57        | 77     | 4.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 808       | 62.2%   |
| Samsung Electronics              | 124       | 9.55%   |
| AMD                              | 108       | 8.31%   |
| SanDisk                          | 59        | 4.54%   |
| SK hynix                         | 36        | 2.77%   |
| Toshiba America Info Systems     | 28        | 2.16%   |
| Micron Technology                | 22        | 1.69%   |
| Phison Electronics               | 18        | 1.39%   |
| Kingston Technology Company      | 17        | 1.31%   |
| KIOXIA                           | 14        | 1.08%   |
| Nvidia                           | 13        | 1%      |
| Micron/Crucial Technology        | 9         | 0.69%   |
| Apple                            | 9         | 0.69%   |
| ADATA Technology                 | 8         | 0.62%   |
| Marvell Technology Group         | 7         | 0.54%   |
| Lite-On Technology               | 4         | 0.31%   |
| Union Memory (Shenzhen)          | 2         | 0.15%   |
| Solid State Storage Technology   | 2         | 0.15%   |
| Silicon Motion                   | 2         | 0.15%   |
| Silicon Integrated Systems [SiS] | 2         | 0.15%   |
| Realtek Semiconductor            | 2         | 0.15%   |
| Lenovo                           | 2         | 0.15%   |
| ULi Electronics                  | 1         | 0.08%   |
| Shenzhen Longsys Electronics     | 1         | 0.08%   |
| JMicron Technology               | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 95        | 6.86%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 94        | 6.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 87        | 6.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 80        | 5.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 73        | 5.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 70        | 5.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 46        | 3.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 45        | 3.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 45        | 3.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 39        | 2.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 33        | 2.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 30        | 2.17%   |
| Intel Volume Management Device NVMe RAID Controller                            | 28        | 2.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 1.66%   |
| Micron Non-Volatile memory controller                                          | 22        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 22        | 1.59%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 17        | 1.23%   |
| Samsung NVMe SSD Controller 980                                                | 17        | 1.23%   |
| Intel SSD 660P Series                                                          | 17        | 1.23%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 16        | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 15        | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 14        | 1.01%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 14        | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 14        | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 14        | 1.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 12        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 11        | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 11        | 0.79%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 10        | 0.72%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 10        | 0.72%   |
| Phison E12 NVMe Controller                                                     | 10        | 0.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 0.65%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 9         | 0.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 9         | 0.65%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 8         | 0.58%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 8         | 0.58%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 8         | 0.58%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 8         | 0.58%   |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 784       | 58.9%   |
| NVMe | 358       | 26.9%   |
| RAID | 119       | 8.94%   |
| IDE  | 70        | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 969       | 86.52%  |
| AMD    | 149       | 13.3%   |
| ARM    | 2         | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 28        | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 23        | 2.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 21        | 1.87%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 19        | 1.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 17        | 1.52%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 16        | 1.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 15        | 1.34%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 15        | 1.34%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 14        | 1.25%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 13        | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 13        | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 13        | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 13        | 1.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 13        | 1.16%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 12        | 1.07%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 11        | 0.98%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 11        | 0.98%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 11        | 0.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 11        | 0.98%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 10        | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 10        | 0.89%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 10        | 0.89%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 10        | 0.89%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 9         | 0.8%    |
| Intel Core i7-3740QM CPU @ 2.70GHz      | 9         | 0.8%    |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 9         | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz       | 9         | 0.8%    |
| Intel Core i5-4200U CPU @ 1.60GHz       | 9         | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 9         | 0.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 9         | 0.8%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 8         | 0.71%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 8         | 0.71%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 8         | 0.71%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 8         | 0.71%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 7         | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 7         | 0.62%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 7         | 0.62%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 7         | 0.62%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 7         | 0.62%   |
| Intel Core i5 CPU M 540 @ 2.53GHz       | 7         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 392       | 34.97%  |
| Intel Core i5                  | 283       | 25.25%  |
| Other                          | 71        | 6.33%   |
| Intel Core 2 Duo               | 54        | 4.82%   |
| Intel Core i3                  | 49        | 4.37%   |
| Intel Celeron                  | 42        | 3.75%   |
| AMD Ryzen 7                    | 26        | 2.32%   |
| Intel Pentium                  | 24        | 2.14%   |
| AMD Ryzen 5                    | 22        | 1.96%   |
| AMD A6                         | 17        | 1.52%   |
| AMD A4                         | 15        | 1.34%   |
| Intel Atom                     | 14        | 1.25%   |
| AMD Ryzen 9                    | 7         | 0.62%   |
| AMD E2                         | 7         | 0.62%   |
| Intel Pentium Dual-Core        | 6         | 0.54%   |
| Intel Genuine                  | 6         | 0.54%   |
| Intel Core 2                   | 6         | 0.54%   |
| AMD Ryzen 7 PRO                | 6         | 0.54%   |
| AMD E1                         | 6         | 0.54%   |
| AMD A8                         | 6         | 0.54%   |
| AMD A10                        | 6         | 0.54%   |
| Intel Core m3                  | 5         | 0.45%   |
| Intel Core i9                  | 5         | 0.45%   |
| Intel Xeon                     | 4         | 0.36%   |
| Intel Core M                   | 4         | 0.36%   |
| Intel Celeron Dual-Core        | 4         | 0.36%   |
| AMD Ryzen 3                    | 4         | 0.36%   |
| AMD E                          | 4         | 0.36%   |
| Intel Pentium M                | 2         | 0.18%   |
| Intel Pentium Dual             | 2         | 0.18%   |
| Intel Core m7                  | 2         | 0.18%   |
| Intel Core Duo                 | 2         | 0.18%   |
| Intel Celeron M                | 2         | 0.18%   |
| AMD V120                       | 2         | 0.18%   |
| AMD FX                         | 2         | 0.18%   |
| AMD A12                        | 2         | 0.18%   |
| Intel Mobile Pentium 4         | 1         | 0.09%   |
| Intel Core m5                  | 1         | 0.09%   |
| AMD V140                       | 1         | 0.09%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 544       | 48.57%  |
| 4      | 389       | 34.73%  |
| 6      | 94        | 8.39%   |
| 8      | 53        | 4.73%   |
| 1      | 29        | 2.59%   |
| 14     | 5         | 0.45%   |
| 12     | 4         | 0.36%   |
| 10     | 2         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1118      | 99.82%  |
| 2      | 2         | 0.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 883       | 78.77%  |
| 1      | 237       | 21.14%  |
| 4      | 1         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1094      | 96.99%  |
| 32-bit         | 17        | 1.51%   |
| Unknown        | 16        | 1.42%   |
| 64-bit         | 1         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 277       | 23.72%  |
| 0x206a7    | 78        | 6.68%   |
| 0x306a9    | 73        | 6.25%   |
| 0x40651    | 47        | 4.02%   |
| 0x906ea    | 45        | 3.85%   |
| 0x406e3    | 41        | 3.51%   |
| 0x806ec    | 39        | 3.34%   |
| 0x1067a    | 38        | 3.25%   |
| 0x806ea    | 36        | 3.08%   |
| 0x306d4    | 35        | 3%      |
| 0x20655    | 35        | 3%      |
| 0x306c3    | 34        | 2.91%   |
| 0x806e9    | 27        | 2.31%   |
| 0x806c1    | 27        | 2.31%   |
| 0xa0652    | 21        | 1.8%    |
| 0x906e9    | 19        | 1.63%   |
| 0x20652    | 19        | 1.63%   |
| 0x806eb    | 14        | 1.2%    |
| 0x0a50000c | 13        | 1.11%   |
| 0x506e3    | 12        | 1.03%   |
| 0x30678    | 12        | 1.03%   |
| 0x07030105 | 12        | 1.03%   |
| 0x106e5    | 11        | 0.94%   |
| 0x0700010f | 11        | 0.94%   |
| 0x06006705 | 11        | 0.94%   |
| 0x806d1    | 10        | 0.86%   |
| 0x706e5    | 10        | 0.86%   |
| 0x10676    | 9         | 0.77%   |
| 0x906a3    | 8         | 0.68%   |
| 0x08108109 | 8         | 0.68%   |
| 0x08108102 | 8         | 0.68%   |
| 0x406c3    | 7         | 0.6%    |
| 0x06001119 | 7         | 0.6%    |
| 0x6fd      | 6         | 0.51%   |
| 0x6f6      | 6         | 0.51%   |
| 0x406c4    | 6         | 0.51%   |
| 0x506c9    | 5         | 0.43%   |
| 0x08608103 | 5         | 0.43%   |
| 0x08600103 | 5         | 0.43%   |
| 0x03000027 | 5         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 230       | 20.52%  |
| Haswell          | 105       | 9.37%   |
| IvyBridge        | 102       | 9.1%    |
| SandyBridge      | 95        | 8.47%   |
| Skylake          | 72        | 6.42%   |
| Westmere         | 62        | 5.53%   |
| Penryn           | 58        | 5.17%   |
| Broadwell        | 40        | 3.57%   |
| CometLake        | 36        | 3.21%   |
| TigerLake        | 34        | 3.03%   |
| Silvermont       | 28        | 2.5%    |
| Icelake          | 24        | 2.14%   |
| Excavator        | 21        | 1.87%   |
| Unknown          | 19        | 1.69%   |
| Zen+             | 18        | 1.61%   |
| Core             | 18        | 1.61%   |
| Zen 3            | 16        | 1.43%   |
| Puma             | 16        | 1.43%   |
| Zen 2            | 15        | 1.34%   |
| Nehalem          | 12        | 1.07%   |
| Jaguar           | 12        | 1.07%   |
| P6               | 11        | 0.98%   |
| Zen              | 9         | 0.8%    |
| Piledriver       | 9         | 0.8%    |
| Goldmont plus    | 9         | 0.8%    |
| Bonnell          | 8         | 0.71%   |
| Alderlake Hybrid | 8         | 0.71%   |
| Goldmont         | 7         | 0.62%   |
| K10 Llano        | 6         | 0.54%   |
| K10              | 6         | 0.54%   |
| Bobcat           | 5         | 0.45%   |
| Tremont          | 3         | 0.27%   |
| Steamroller      | 3         | 0.27%   |
| K8 & K10 hybrid  | 2         | 0.18%   |
| NetBurst         | 1         | 0.09%   |
| K8 Hammer        | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 843       | 57.82%  |
| Nvidia                           | 372       | 25.51%  |
| AMD                              | 239       | 16.39%  |
| Silicon Integrated Systems [SiS] | 2         | 0.14%   |
| Neomagic                         | 2         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 88        | 5.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 84        | 5.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 57        | 3.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 54        | 3.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 52        | 3.44%   |
| Intel UHD Graphics 620                                                                   | 47        | 3.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 43        | 2.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 42        | 2.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 33        | 2.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 32        | 2.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 2.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 1.99%   |
| Intel HD Graphics 5500                                                                   | 29        | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 1.79%   |
| Intel HD Graphics 620                                                                    | 25        | 1.65%   |
| Intel HD Graphics 630                                                                    | 20        | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 20        | 1.32%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 17        | 1.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 17        | 1.13%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 14        | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 0.93%   |
| AMD Renoir                                                                               | 14        | 0.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 0.93%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 13        | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 0.86%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 13        | 0.86%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 13        | 0.86%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 12        | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 12        | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 11        | 0.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 11        | 0.73%   |
| Intel HD Graphics 530                                                                    | 11        | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 10        | 0.66%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 9         | 0.6%    |
| Nvidia GM108M [GeForce 840M]                                                             | 9         | 0.6%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 9         | 0.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 0.6%    |
| Nvidia GT216M [GeForce GT 330M]                                                          | 8         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 524       | 46.41%  |
| Intel + Nvidia           | 268       | 23.74%  |
| 1 x AMD                  | 141       | 12.49%  |
| 1 x Nvidia               | 87        | 7.71%   |
| Intel + AMD              | 46        | 4.07%   |
| 2 x AMD                  | 35        | 3.1%    |
| AMD + Nvidia             | 17        | 1.51%   |
| Other                    | 2         | 0.18%   |
| 2 x Intel                | 2         | 0.18%   |
| 1 x SiS                  | 2         | 0.18%   |
| 1 x Neomagic             | 2         | 0.18%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.18%   |
| 2 x Nvidia               | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 934       | 81.01%  |
| Proprietary | 180       | 15.61%  |
| Unknown     | 39        | 3.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 700       | 60.55%  |
| 1.01-2.0   | 138       | 11.94%  |
| 0.01-0.5   | 120       | 10.38%  |
| 3.01-4.0   | 75        | 6.49%   |
| 0.51-1.0   | 73        | 6.31%   |
| 5.01-6.0   | 23        | 1.99%   |
| 7.01-8.0   | 17        | 1.47%   |
| 2.01-3.0   | 7         | 0.61%   |
| 8.01-16.0  | 3         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 261       | 20.02%  |
| LG Display              | 193       | 14.8%   |
| Chimei Innolux          | 144       | 11.04%  |
| Samsung Electronics     | 128       | 9.82%   |
| BOE                     | 108       | 8.28%   |
| Apple                   | 72        | 5.52%   |
| Sharp                   | 54        | 4.14%   |
| Dell                    | 38        | 2.91%   |
| Chi Mei Optoelectronics | 38        | 2.91%   |
| Lenovo                  | 27        | 2.07%   |
| Hewlett-Packard         | 22        | 1.69%   |
| Goldstar                | 21        | 1.61%   |
| BenQ                    | 18        | 1.38%   |
| Acer                    | 17        | 1.3%    |
| Philips                 | 15        | 1.15%   |
| PANDA                   | 15        | 1.15%   |
| Sony                    | 11        | 0.84%   |
| Ancor Communications    | 7         | 0.54%   |
| ViewSonic               | 6         | 0.46%   |
| Toshiba                 | 6         | 0.46%   |
| LG Philips              | 6         | 0.46%   |
| CPT                     | 6         | 0.46%   |
| AOC                     | 6         | 0.46%   |
| Panasonic               | 5         | 0.38%   |
| LGD                     | 5         | 0.38%   |
| Unknown                 | 4         | 0.31%   |
| SAC                     | 4         | 0.31%   |
| InfoVision              | 4         | 0.31%   |
| HannStar                | 4         | 0.31%   |
| GKK                     | 4         | 0.31%   |
| eMachines               | 4         | 0.31%   |
| ASUSTek Computer        | 4         | 0.31%   |
| Kogan                   | 3         | 0.23%   |
| InnoLux Display         | 3         | 0.23%   |
| Hitachi                 | 3         | 0.23%   |
| GDH                     | 3         | 0.23%   |
| CSO                     | 3         | 0.23%   |
| Unknown (XXX)           | 2         | 0.15%   |
| TMX                     | 2         | 0.15%   |
| TCL                     | 2         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 1.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 10        | 0.75%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.68%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 8         | 0.6%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 7         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 6         | 0.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 6         | 0.45%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                     | 6         | 0.45%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 6         | 0.45%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 6         | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.45%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 6         | 0.45%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 6         | 0.45%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 5         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 5         | 0.38%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 0.38%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 5         | 0.38%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 5         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 5         | 0.38%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 5         | 0.38%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 4         | 0.3%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 4         | 0.3%    |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 4         | 0.3%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 4         | 0.3%    |
| eMachines E190HQV EMA0212 1366x768 409x230mm 18.5-inch                   | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 4         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch | 4         | 0.3%    |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 4         | 0.3%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 459       | 38%     |
| 1366x768 (WXGA)    | 389       | 32.2%   |
| 3840x2160 (4K)     | 73        | 6.04%   |
| 1280x800 (WXGA)    | 52        | 4.3%    |
| 1600x900 (HD+)     | 42        | 3.48%   |
| 1440x900 (WXGA+)   | 28        | 2.32%   |
| 2560x1440 (QHD)    | 22        | 1.82%   |
| 1920x1200 (WUXGA)  | 19        | 1.57%   |
| 2560x1600          | 17        | 1.41%   |
| 2880x1800          | 12        | 0.99%   |
| 1680x1050 (WSXGA+) | 11        | 0.91%   |
| 1280x1024 (SXGA)   | 10        | 0.83%   |
| 3840x2400          | 9         | 0.75%   |
| 3440x1440          | 7         | 0.58%   |
| 3200x1800 (QHD+)   | 7         | 0.58%   |
| 1024x600           | 6         | 0.5%    |
| 1360x768           | 5         | 0.41%   |
| Unknown            | 5         | 0.41%   |
| 3072x1920          | 4         | 0.33%   |
| 2160x1440          | 4         | 0.33%   |
| 3840x1080          | 3         | 0.25%   |
| 2256x1504          | 3         | 0.25%   |
| 5760x2160          | 2         | 0.17%   |
| 3456x2160          | 2         | 0.17%   |
| 3286x1080          | 2         | 0.17%   |
| 3200x2000          | 2         | 0.17%   |
| 2240x1400          | 2         | 0.17%   |
| 1280x720 (HD)      | 2         | 0.17%   |
| 1024x768 (XGA)     | 2         | 0.17%   |
| 3840x1600          | 1         | 0.08%   |
| 3000x2000          | 1         | 0.08%   |
| 2726x768           | 1         | 0.08%   |
| 2304x1440          | 1         | 0.08%   |
| 1920x540           | 1         | 0.08%   |
| 1720x1440          | 1         | 0.08%   |
| 1680x945           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 527       | 40.57%  |
| 13      | 185       | 14.24%  |
| 14      | 133       | 10.24%  |
| 17      | 86        | 6.62%   |
| 27      | 56        | 4.31%   |
| 24      | 39        | 3%      |
| 12      | 37        | 2.85%   |
| 23      | 33        | 2.54%   |
| 11      | 32        | 2.46%   |
| Unknown | 24        | 1.85%   |
| 21      | 23        | 1.77%   |
| 31      | 16        | 1.23%   |
| 16      | 13        | 1%      |
| 19      | 9         | 0.69%   |
| 18      | 9         | 0.69%   |
| 84      | 8         | 0.62%   |
| 72      | 8         | 0.62%   |
| 10      | 7         | 0.54%   |
| 22      | 6         | 0.46%   |
| 20      | 6         | 0.46%   |
| 52      | 5         | 0.38%   |
| 40      | 5         | 0.38%   |
| 34      | 5         | 0.38%   |
| 54      | 4         | 0.31%   |
| 26      | 3         | 0.23%   |
| 48      | 2         | 0.15%   |
| 46      | 2         | 0.15%   |
| 37      | 2         | 0.15%   |
| 35      | 2         | 0.15%   |
| 32      | 2         | 0.15%   |
| 8       | 2         | 0.15%   |
| 78      | 1         | 0.08%   |
| 63      | 1         | 0.08%   |
| 55      | 1         | 0.08%   |
| 49      | 1         | 0.08%   |
| 38      | 1         | 0.08%   |
| 29      | 1         | 0.08%   |
| 25      | 1         | 0.08%   |
| 9       | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 730       | 56.63%  |
| 201-300     | 185       | 14.35%  |
| 501-600     | 113       | 8.77%   |
| 351-400     | 110       | 8.53%   |
| 401-500     | 48        | 3.72%   |
| 601-700     | 27        | 2.09%   |
| Unknown     | 24        | 1.86%   |
| 1501-2000   | 17        | 1.32%   |
| 1001-1500   | 16        | 1.24%   |
| 801-900     | 10        | 0.78%   |
| 701-800     | 7         | 0.54%   |
| 101-200     | 2         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 909       | 81.23%  |
| 16/10   | 151       | 13.49%  |
| Unknown | 18        | 1.61%   |
| 3/2     | 14        | 1.25%   |
| 21/9    | 8         | 0.71%   |
| 5/4     | 7         | 0.63%   |
| 4/3     | 6         | 0.54%   |
| 32/9    | 4         | 0.36%   |
| 6/5     | 1         | 0.09%   |
| 0.62    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 527       | 40.69%  |
| 81-90          | 239       | 18.46%  |
| 201-250        | 87        | 6.72%   |
| 71-80          | 83        | 6.41%   |
| 121-130        | 75        | 5.79%   |
| 301-350        | 58        | 4.48%   |
| 61-70          | 33        | 2.55%   |
| 51-60          | 32        | 2.47%   |
| More than 1000 | 27        | 2.08%   |
| 351-500        | 26        | 2.01%   |
| Unknown        | 24        | 1.85%   |
| 151-200        | 21        | 1.62%   |
| 501-1000       | 13        | 1%      |
| 111-120        | 12        | 0.93%   |
| 251-300        | 9         | 0.69%   |
| 141-150        | 9         | 0.69%   |
| 41-50          | 8         | 0.62%   |
| 131-140        | 8         | 0.62%   |
| 1-40           | 2         | 0.15%   |
| 91-100         | 2         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 448       | 35.61%  |
| 101-120       | 384       | 30.52%  |
| 51-100        | 214       | 17.01%  |
| 161-240       | 94        | 7.47%   |
| More than 240 | 70        | 5.56%   |
| 1-50          | 24        | 1.91%   |
| Unknown       | 24        | 1.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 905       | 77.62%  |
| 2     | 191       | 16.38%  |
| 0     | 38        | 3.26%   |
| 3     | 28        | 2.4%    |
| 4     | 4         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 618       | 33.57%  |
| Realtek Semiconductor             | 562       | 30.53%  |
| Qualcomm Atheros                  | 258       | 14.01%  |
| Broadcom                          | 138       | 7.5%    |
| Broadcom Limited                  | 43        | 2.34%   |
| Ralink                            | 25        | 1.36%   |
| Marvell Technology Group          | 16        | 0.87%   |
| Sierra Wireless                   | 13        | 0.71%   |
| MediaTek                          | 13        | 0.71%   |
| Samsung Electronics               | 11        | 0.6%    |
| DisplayLink                       | 11        | 0.6%    |
| Dell                              | 11        | 0.6%    |
| Huawei Technologies               | 9         | 0.49%   |
| Apple                             | 9         | 0.49%   |
| Nvidia                            | 8         | 0.43%   |
| NetGear                           | 8         | 0.43%   |
| TP-Link                           | 7         | 0.38%   |
| Ralink Technology                 | 7         | 0.38%   |
| Lenovo                            | 7         | 0.38%   |
| Hewlett-Packard                   | 6         | 0.33%   |
| ASIX Electronics                  | 6         | 0.33%   |
| ZTE WCDMA Technologies MSM        | 5         | 0.27%   |
| Edimax Technology                 | 5         | 0.27%   |
| OPPO Electronics                  | 4         | 0.22%   |
| ASUSTek Computer                  | 4         | 0.22%   |
| JMicron Technology                | 3         | 0.16%   |
| Google                            | 3         | 0.16%   |
| Xiaomi                            | 2         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.11%   |
| Qualcomm Atheros Communications   | 2         | 0.11%   |
| Qualcomm                          | 2         | 0.11%   |
| Motorola PCS                      | 2         | 0.11%   |
| ICS Advent                        | 2         | 0.11%   |
| Ericsson Business Mobile Networks | 2         | 0.11%   |
| D-Link                            | 2         | 0.11%   |
| Arduino SA                        | 2         | 0.11%   |
| Wilocity                          | 1         | 0.05%   |
| ULi Electronics                   | 1         | 0.05%   |
| Toshiba                           | 1         | 0.05%   |
| T & A Mobile Phones               | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 342       | 15.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 104       | 4.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 60        | 2.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 53        | 2.39%   |
| Intel Wi-Fi 6 AX200                                               | 46        | 2.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 43        | 1.94%   |
| Intel Wireless 8260                                               | 42        | 1.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 40        | 1.81%   |
| Intel Wireless 8265 / 8275                                        | 40        | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 35        | 1.58%   |
| Intel Wireless 7260                                               | 35        | 1.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 34        | 1.53%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 32        | 1.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 31        | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 29        | 1.31%   |
| Intel Centrino Ultimate-N 6300                                    | 29        | 1.31%   |
| Intel Wireless 3165                                               | 28        | 1.26%   |
| Intel Wi-Fi 6 AX201                                               | 27        | 1.22%   |
| Intel Wireless 7265                                               | 25        | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 24        | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 22        | 0.99%   |
| Intel Ethernet Connection I219-LM                                 | 21        | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 0.9%    |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 18        | 0.81%   |
| Intel Wireless-AC 9260                                            | 18        | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 17        | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 16        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 16        | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 16        | 0.72%   |
| Intel Wireless 3160                                               | 15        | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 0.68%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 15        | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 14        | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 14        | 0.63%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 14        | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 13        | 0.59%   |
| Intel Centrino Advanced-N 6200                                    | 13        | 0.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 597       | 50.81%  |
| Qualcomm Atheros                | 215       | 18.3%   |
| Realtek Semiconductor           | 119       | 10.13%  |
| Broadcom                        | 112       | 9.53%   |
| Broadcom Limited                | 34        | 2.89%   |
| Ralink                          | 25        | 2.13%   |
| Sierra Wireless                 | 13        | 1.11%   |
| MediaTek                        | 12        | 1.02%   |
| NetGear                         | 8         | 0.68%   |
| Ralink Technology               | 7         | 0.6%    |
| Dell                            | 7         | 0.6%    |
| TP-Link                         | 6         | 0.51%   |
| Edimax Technology               | 5         | 0.43%   |
| ASUSTek Computer                | 4         | 0.34%   |
| Hewlett-Packard                 | 3         | 0.26%   |
| Qualcomm Atheros Communications | 2         | 0.17%   |
| D-Link                          | 2         | 0.17%   |
| Xiaomi                          | 1         | 0.09%   |
| Wilocity                        | 1         | 0.09%   |
| Qualcomm                        | 1         | 0.09%   |
| Belkin Components               | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 46        | 3.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 43        | 3.64%   |
| Intel Wireless 8260                                            | 42        | 3.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 40        | 3.38%   |
| Intel Wireless 8265 / 8275                                     | 40        | 3.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 35        | 2.96%   |
| Intel Wireless 7260                                            | 35        | 2.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 34        | 2.88%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 32        | 2.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 31        | 2.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 29        | 2.45%   |
| Intel Centrino Ultimate-N 6300                                 | 29        | 2.45%   |
| Intel Wireless 3165                                            | 28        | 2.37%   |
| Intel Wi-Fi 6 AX201                                            | 27        | 2.28%   |
| Intel Wireless 7265                                            | 25        | 2.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 24        | 2.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 22        | 1.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 20        | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 18        | 1.52%   |
| Intel Wireless-AC 9260                                         | 18        | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 17        | 1.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 16        | 1.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 16        | 1.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 16        | 1.35%   |
| Intel Wireless 3160                                            | 15        | 1.27%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 15        | 1.27%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 14        | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 14        | 1.18%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 14        | 1.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 13        | 1.1%    |
| Intel Centrino Advanced-N 6200                                 | 13        | 1.1%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 12        | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 12        | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 1.02%   |
| Intel WiFi Link 5100                                           | 11        | 0.93%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 10        | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10        | 0.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 10        | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                  | 10        | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 9         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 516       | 52.39%  |
| Intel                            | 219       | 22.23%  |
| Qualcomm Atheros                 | 83        | 8.43%   |
| Broadcom                         | 60        | 6.09%   |
| Marvell Technology Group         | 16        | 1.62%   |
| Samsung Electronics              | 11        | 1.12%   |
| DisplayLink                      | 11        | 1.12%   |
| Broadcom Limited                 | 9         | 0.91%   |
| Apple                            | 9         | 0.91%   |
| Nvidia                           | 8         | 0.81%   |
| Lenovo                           | 7         | 0.71%   |
| Huawei Technologies              | 6         | 0.61%   |
| ASIX Electronics                 | 6         | 0.61%   |
| ZTE WCDMA Technologies MSM       | 5         | 0.51%   |
| OPPO Electronics                 | 4         | 0.41%   |
| JMicron Technology               | 3         | 0.3%    |
| Google                           | 3         | 0.3%    |
| Silicon Integrated Systems [SiS] | 2         | 0.2%    |
| ICS Advent                       | 2         | 0.2%    |
| Xiaomi                           | 1         | 0.1%    |
| T & A Mobile Phones              | 1         | 0.1%    |
| Qualcomm                         | 1         | 0.1%    |
| Microsoft                        | 1         | 0.1%    |
| Attansic Technology              | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 342       | 34.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 104       | 10.38%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 60        | 5.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 53        | 5.29%   |
| Intel Ethernet Connection I219-LM                                 | 21        | 2.1%    |
| Intel 82577LM Gigabit Network Connection                          | 19        | 1.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 1.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 1.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 1.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 1.1%    |
| Intel Ethernet Connection I218-LM                                 | 11        | 1.1%    |
| Intel Ethernet Connection (4) I219-V                              | 10        | 1%      |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 1%      |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 10        | 1%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.9%    |
| Intel Ethernet Connection I219-V                                  | 9         | 0.9%    |
| Intel 82567LM Gigabit Network Connection                          | 9         | 0.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 9         | 0.9%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 9         | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.6%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.6%    |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 5         | 0.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.4%    |
| OPPO SDM665-IDP _SN:18689828                                      | 4         | 0.4%    |
| Nvidia MCP79 Ethernet                                             | 4         | 0.4%    |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.4%    |
| Intel 82573L Gigabit Ethernet Controller                          | 4         | 0.4%    |
| DisplayLink Dell Universal Dock D6000                             | 4         | 0.4%    |
| Apple iBridge                                                     | 4         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1099      | 53.58%  |
| Ethernet | 922       | 44.95%  |
| Modem    | 27        | 1.32%   |
| Unknown  | 3         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 914       | 78.19%  |
| Ethernet | 255       | 21.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 844       | 75.09%  |
| 1     | 262       | 23.31%  |
| 0     | 11        | 0.98%   |
| 3     | 7         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1013      | 88.94%  |
| Yes  | 126       | 11.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 439       | 50%     |
| Qualcomm Atheros Communications | 73        | 8.31%   |
| Apple                           | 62        | 7.06%   |
| Broadcom                        | 60        | 6.83%   |
| Realtek Semiconductor           | 41        | 4.67%   |
| Toshiba                         | 33        | 3.76%   |
| Lite-On Technology              | 33        | 3.76%   |
| IMC Networks                    | 32        | 3.64%   |
| Foxconn / Hon Hai               | 32        | 3.64%   |
| Hewlett-Packard                 | 16        | 1.82%   |
| Dell                            | 15        | 1.71%   |
| Ralink                          | 14        | 1.59%   |
| Alps Electric                   | 6         | 0.68%   |
| Realtek                         | 5         | 0.57%   |
| Cambridge Silicon Radio         | 5         | 0.57%   |
| ASUSTek Computer                | 5         | 0.57%   |
| Ralink Technology               | 3         | 0.34%   |
| USI                             | 1         | 0.11%   |
| Opticis                         | 1         | 0.11%   |
| MediaTek                        | 1         | 0.11%   |
| Belkin Components               | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 174       | 19.82%  |
| Intel AX201 Bluetooth                               | 90        | 10.25%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 56        | 6.38%   |
| Intel AX200 Bluetooth                               | 47        | 5.35%   |
| Apple Bluetooth Host Controller                     | 32        | 3.64%   |
| Qualcomm Atheros  Bluetooth Device                  | 28        | 3.19%   |
| Realtek Bluetooth Radio                             | 26        | 2.96%   |
| Apple Bluetooth USB Host Controller                 | 24        | 2.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 18        | 2.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 17        | 1.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 15        | 1.71%   |
| Ralink RT3290 Bluetooth                             | 14        | 1.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 1.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 1.48%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 1.48%   |
| Toshiba Bluetooth Device                            | 12        | 1.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 1.37%   |
| Intel AX210 Bluetooth                               | 12        | 1.37%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 1.14%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 1.14%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 10        | 1.14%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 1.14%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.91%   |
| Lite-On Bluetooth Device                            | 8         | 0.91%   |
| Intel Bluetooth Device                              | 8         | 0.91%   |
| IMC Networks Bluetooth Radio                        | 8         | 0.91%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.8%    |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.8%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.68%   |
| Realtek Bluetooth Radio                             | 5         | 0.57%   |
| IMC Networks Wireless_Device                        | 5         | 0.57%   |
| IMC Networks Bluetooth                              | 5         | 0.57%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.57%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 0.57%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5         | 0.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 0.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 5         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 942       | 64.56%  |
| Nvidia                                       | 203       | 13.91%  |
| AMD                                          | 193       | 13.23%  |
| Realtek Semiconductor                        | 17        | 1.17%   |
| Apple                                        | 7         | 0.48%   |
| Lenovo                                       | 6         | 0.41%   |
| GN Netcom                                    | 6         | 0.41%   |
| Creative Technology                          | 6         | 0.41%   |
| C-Media Electronics                          | 6         | 0.41%   |
| Razer USA                                    | 5         | 0.34%   |
| Logitech                                     | 5         | 0.34%   |
| Hewlett-Packard                              | 4         | 0.27%   |
| Generalplus Technology                       | 4         | 0.27%   |
| Texas Instruments                            | 3         | 0.21%   |
| Plantronics                                  | 3         | 0.21%   |
| OPPO Electronics                             | 3         | 0.21%   |
| Microsoft                                    | 3         | 0.21%   |
| Kingston Technology                          | 3         | 0.21%   |
| JMTek                                        | 3         | 0.21%   |
| Thermaltake                                  | 2         | 0.14%   |
| SteelSeries ApS                              | 2         | 0.14%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.14%   |
| Samsung Electronics                          | 2         | 0.14%   |
| Native Instruments                           | 2         | 0.14%   |
| Micro Star International                     | 2         | 0.14%   |
| M-Audio                                      | 2         | 0.14%   |
| Dell                                         | 2         | 0.14%   |
| Conexant Systems                             | 2         | 0.14%   |
| Chicony Electronics                          | 2         | 0.14%   |
| Blue Microphones                             | 2         | 0.14%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.07%   |
| ZOOM                                         | 1         | 0.07%   |
| XMOS                                         | 1         | 0.07%   |
| ULi Electronics                              | 1         | 0.07%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.07%   |
| Sony                                         | 1         | 0.07%   |
| Sennheiser electronic                        | 1         | 0.07%   |
| RODE Microphones                             | 1         | 0.07%   |
| LG Electronics                               | 1         | 0.07%   |
| DSEA A/S                                     | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 135       | 7.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 114       | 6.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 82        | 4.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 74        | 4.26%   |
| AMD Family 17h/19h HD Audio Controller                                     | 65        | 3.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 59        | 3.4%    |
| Intel 8 Series HD Audio Controller                                         | 59        | 3.4%    |
| Intel Haswell-ULT HD Audio Controller                                      | 58        | 3.34%   |
| AMD FCH Azalia Controller                                                  | 47        | 2.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 46        | 2.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 43        | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 40        | 2.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 40        | 2.3%    |
| Intel Broadwell-U Audio Controller                                         | 40        | 2.3%    |
| Intel Comet Lake PCH cAVS                                                  | 35        | 2.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 35        | 2.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 34        | 1.96%   |
| AMD Kabini HDMI/DP Audio                                                   | 32        | 1.84%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 31        | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                               | 30        | 1.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 25        | 1.44%   |
| Intel CM238 HD Audio Controller                                            | 24        | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 22        | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                              | 21        | 1.21%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 21        | 1.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 20        | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 17        | 0.98%   |
| AMD High Definition Audio Controller                                       | 17        | 0.98%   |
| Realtek Semiconductor USB Audio                                            | 15        | 0.86%   |
| Nvidia GT216 HDMI Audio Controller                                         | 15        | 0.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 15        | 0.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15        | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 14        | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 14        | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 13        | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 13        | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 12        | 0.69%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 12        | 0.69%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11        | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 200       | 32.73%  |
| SK hynix                   | 159       | 26.02%  |
| Micron Technology          | 80        | 13.09%  |
| Kingston                   | 51        | 8.35%   |
| Crucial                    | 26        | 4.26%   |
| Unknown                    | 21        | 3.44%   |
| Elpida                     | 16        | 2.62%   |
| Ramaxel Technology         | 11        | 1.8%    |
| Nanya Technology           | 8         | 1.31%   |
| Team                       | 7         | 1.15%   |
| Corsair                    | 4         | 0.65%   |
| A-DATA Technology          | 4         | 0.65%   |
| Apacer                     | 3         | 0.49%   |
| Unknown                    | 3         | 0.49%   |
| Smart                      | 2         | 0.33%   |
| G.Skill                    | 2         | 0.33%   |
| Unknown (0x89AD)           | 1         | 0.16%   |
| Unknown (0x873E)           | 1         | 0.16%   |
| Transcend                  | 1         | 0.16%   |
| Toshiba                    | 1         | 0.16%   |
| Silicon Power              | 1         | 0.16%   |
| Qimonda                    | 1         | 0.16%   |
| pqi                        | 1         | 0.16%   |
| Patriot                    | 1         | 0.16%   |
| Netlist                    | 1         | 0.16%   |
| Neo Forza                  | 1         | 0.16%   |
| GSkill                     | 1         | 0.16%   |
| Avant                      | 1         | 0.16%   |
| ASint Technology           | 1         | 0.16%   |
| Anucell Technology Holding | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 2.43%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 12        | 1.82%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 1.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 1.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.22%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 8         | 1.22%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.06%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.06%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.06%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.91%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.91%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.76%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.76%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 5         | 0.76%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.76%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 5         | 0.76%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 5         | 0.76%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.76%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.61%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.61%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.61%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.61%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.61%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.61%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.61%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 4         | 0.61%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 4         | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.61%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 4         | 0.61%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s         | 4         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.46%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.46%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.46%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 3         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 229       | 43.05%  |
| DDR3    | 210       | 39.47%  |
| LPDDR3  | 40        | 7.52%   |
| DDR2    | 18        | 3.38%   |
| LPDDR4  | 17        | 3.2%    |
| SDRAM   | 8         | 1.5%    |
| LPDDR5  | 3         | 0.56%   |
| DDR5    | 3         | 0.56%   |
| Unknown | 2         | 0.38%   |
| DRAM    | 1         | 0.19%   |
| DDR     | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 465       | 87.08%  |
| Row Of Chips | 59        | 11.05%  |
| Chip         | 7         | 1.31%   |
| Unknown      | 2         | 0.37%   |
| DIMM         | 1         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 206       | 36.59%  |
| 4096  | 175       | 31.08%  |
| 16384 | 87        | 15.45%  |
| 2048  | 67        | 11.9%   |
| 32768 | 16        | 2.84%   |
| 1024  | 9         | 1.6%    |
| 512   | 2         | 0.36%   |
| 256   | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 149       | 25.91%  |
| 2667    | 121       | 21.04%  |
| 3200    | 78        | 13.57%  |
| 1334    | 41        | 7.13%   |
| 2133    | 38        | 6.61%   |
| 2400    | 28        | 4.87%   |
| 1067    | 17        | 2.96%   |
| 1867    | 14        | 2.43%   |
| 1333    | 13        | 2.26%   |
| 4267    | 9         | 1.57%   |
| 667     | 9         | 1.57%   |
| Unknown | 9         | 1.57%   |
| 8400    | 7         | 1.22%   |
| 4800    | 7         | 1.22%   |
| 3266    | 7         | 1.22%   |
| 1066    | 6         | 1.04%   |
| 800     | 6         | 1.04%   |
| 2048    | 4         | 0.7%    |
| 6400    | 3         | 0.52%   |
| 4266    | 2         | 0.35%   |
| 4199    | 2         | 0.35%   |
| 3733    | 2         | 0.35%   |
| 975     | 2         | 0.35%   |
| 533     | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 50%     |
| Samsung Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung ML-1865        | 1         | 25%     |
| HP DeskJet 2300 series | 1         | 25%     |
| Brother HL-2140 series | 1         | 25%     |
| Brother HL-1110 series | 1         | 25%     |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 270       | 25.84%  |
| Microdia                               | 100       | 9.57%   |
| Realtek Semiconductor                  | 94        | 9%      |
| Sunplus Innovation Technology          | 86        | 8.23%   |
| IMC Networks                           | 84        | 8.04%   |
| Apple                                  | 60        | 5.74%   |
| Acer                                   | 59        | 5.65%   |
| Suyin                                  | 42        | 4.02%   |
| Quanta                                 | 41        | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 41        | 3.92%   |
| Logitech                               | 26        | 2.49%   |
| Lite-On Technology                     | 20        | 1.91%   |
| Syntek                                 | 12        | 1.15%   |
| Samsung Electronics                    | 11        | 1.05%   |
| Luxvisions Innotech Limited            | 10        | 0.96%   |
| Importek                               | 10        | 0.96%   |
| Silicon Motion                         | 9         | 0.86%   |
| Ricoh                                  | 9         | 0.86%   |
| Primax Electronics                     | 7         | 0.67%   |
| Lenovo                                 | 7         | 0.67%   |
| Alcor Micro                            | 6         | 0.57%   |
| Magic Control Technology               | 4         | 0.38%   |
| DigiTech                               | 4         | 0.38%   |
| Razer USA                              | 3         | 0.29%   |
| OmniVision Technologies                | 3         | 0.29%   |
| LG Electronics                         | 3         | 0.29%   |
| ALi                                    | 3         | 0.29%   |
| Z-Star Microelectronics                | 2         | 0.19%   |
| SunplusIT                              | 2         | 0.19%   |
| Sonix Technology                       | 2         | 0.19%   |
| Genesys Logic                          | 2         | 0.19%   |
| GEMBIRD                                | 2         | 0.19%   |
| Tobii Technology AB                    | 1         | 0.1%    |
| Sunplus Technology                     | 1         | 0.1%    |
| Solid Year                             | 1         | 0.1%    |
| Mimaki Engineering                     | 1         | 0.1%    |
| Microsoft                              | 1         | 0.1%    |
| lihappe8                               | 1         | 0.1%    |
| Intel                                  | 1         | 0.1%    |
| Goodong                                | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 54        | 5.11%   |
| Chicony Integrated Camera                               | 40        | 3.78%   |
| Realtek Integrated_Webcam_HD                            | 26        | 2.46%   |
| Chicony HD WebCam                                       | 24        | 2.27%   |
| Sunplus Integrated_Webcam_HD                            | 23        | 2.18%   |
| IMC Networks Integrated Camera                          | 23        | 2.18%   |
| Chicony TOSHIBA Web Camera - HD                         | 23        | 2.18%   |
| Realtek USB Camera                                      | 18        | 1.7%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 17        | 1.61%   |
| Apple Built-in iSight                                   | 16        | 1.51%   |
| Apple FaceTime HD Camera (Built-in)                     | 15        | 1.42%   |
| Chicony HP TrueVision HD Camera                         | 14        | 1.32%   |
| Chicony HP Truevision HD                                | 13        | 1.23%   |
| Apple FaceTime HD Camera                                | 13        | 1.23%   |
| Acer Integrated Camera                                  | 13        | 1.23%   |
| Sunplus HD WebCam                                       | 12        | 1.14%   |
| Chicony USB 2.0 Camera                                  | 12        | 1.14%   |
| Apple iPhone 5/5C/5S/6/SE                               | 12        | 1.14%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 11        | 1.04%   |
| Chicony USB2.0 Camera                                   | 11        | 1.04%   |
| Chicony HD User Facing                                  | 11        | 1.04%   |
| Lite-On Integrated Camera                               | 10        | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 10        | 0.95%   |
| Quanta HD User Facing                                   | 9         | 0.85%   |
| Microdia Integrated Webcam                              | 9         | 0.85%   |
| Chicony HP HD Camera                                    | 9         | 0.85%   |
| Chicony CNF9055 Toshiba Webcam                          | 9         | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 9         | 0.85%   |
| Syntek Integrated Camera                                | 8         | 0.76%   |
| Suyin HP Truevision HD                                  | 8         | 0.76%   |
| Quanta HP TrueVision HD Camera                          | 8         | 0.76%   |
| Acer HD Webcam                                          | 8         | 0.76%   |
| Quanta HD Webcam                                        | 7         | 0.66%   |
| Chicony Integrated Camera (1280x720@30)                 | 7         | 0.66%   |
| Sunplus Asus Webcam                                     | 6         | 0.57%   |
| Realtek USB2.0 HD UVC WebCam                            | 6         | 0.57%   |
| Quanta HP Webcam                                        | 6         | 0.57%   |
| Logitech Webcam C270                                    | 6         | 0.57%   |
| IMC Networks UVC VGA Webcam                             | 6         | 0.57%   |
| Acer EasyCamera                                         | 6         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 94        | 41.23%  |
| Synaptics                  | 48        | 21.05%  |
| Shenzhen Goodix Technology | 27        | 11.84%  |
| LighTuning Technology      | 18        | 7.89%   |
| AuthenTec                  | 14        | 6.14%   |
| Upek                       | 12        | 5.26%   |
| Elan Microelectronics      | 9         | 3.95%   |
| STMicroelectronics         | 6         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 8.77%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 7.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 5.26%   |
| Validity Sensors VFS491                                                    | 9         | 3.95%   |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 3.95%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.95%   |
| Shenzhen Goodix FingerPrint                                                | 9         | 3.95%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 3.51%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 3.51%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 3.51%   |
| Unknown                                                                    | 8         | 3.51%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 3.07%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 2.63%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 2.63%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.63%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.63%   |
| Elan ELAN:Fingerprint                                                      | 6         | 2.63%   |
| Synaptics WBDI Device                                                      | 5         | 2.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 2.19%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.75%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 1.75%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.75%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 1.75%   |
| AuthenTec AES1600                                                          | 4         | 1.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.32%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.32%   |
| Synaptics  WBDI                                                            | 3         | 1.32%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.32%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.32%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.32%   |
| AuthenTec AES2810                                                          | 2         | 0.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.44%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.44%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 30        | 62.5%   |
| Alcor Micro           | 11        | 22.92%  |
| Upek                  | 2         | 4.17%   |
| O2 Micro              | 2         | 4.17%   |
| Lenovo                | 2         | 4.17%   |
| Advanced Card Systems | 1         | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 29.17%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 22.92%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 12.5%   |
| Broadcom 5880                                                                | 5         | 10.42%  |
| Broadcom 58200                                                               | 5         | 10.42%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.17%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.17%   |
| Advanced Card Systems ACR122U                                                | 1         | 2.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 691       | 59.26%  |
| 1     | 388       | 33.28%  |
| 2     | 71        | 6.09%   |
| 3     | 12        | 1.03%   |
| 4     | 4         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 227       | 41.35%  |
| Graphics card            | 116       | 21.13%  |
| Net/wireless             | 49        | 8.93%   |
| Chipcard                 | 43        | 7.83%   |
| Multimedia controller    | 32        | 5.83%   |
| Bluetooth                | 18        | 3.28%   |
| Camera                   | 17        | 3.1%    |
| Net/ethernet             | 9         | 1.64%   |
| Communication controller | 9         | 1.64%   |
| Storage                  | 8         | 1.46%   |
| Modem                    | 7         | 1.28%   |
| Card reader              | 6         | 1.09%   |
| Sound                    | 5         | 0.91%   |
| Unassigned class         | 1         | 0.18%   |
| Storage/ide              | 1         | 0.18%   |
| Storage/ata              | 1         | 0.18%   |

