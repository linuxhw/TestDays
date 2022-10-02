Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

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

Total: 3120

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A715-41G             | [1a473e9809](https://linux-hardware.org/?probe=1a473e9809) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [5bc67115db](https://linux-hardware.org/?probe=5bc67115db) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [9b59ddb3b2](https://linux-hardware.org/?probe=9b59ddb3b2) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [4758af490a](https://linux-hardware.org/?probe=4758af490a) | Oct 01, 2022 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | [fbe1e53387](https://linux-hardware.org/?probe=fbe1e53387) | Oct 01, 2022 |
| SANTECH       | NHx0DB,DE                   | [6dc0730b6a](https://linux-hardware.org/?probe=6dc0730b6a) | Oct 01, 2022 |
| Lenovo        | ThinkPad L380 20M5SSIN11    | [0cad79b1f7](https://linux-hardware.org/?probe=0cad79b1f7) | Sep 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [786e0c1f5d](https://linux-hardware.org/?probe=786e0c1f5d) | Sep 30, 2022 |
| HP            | Pavilion Notebook           | [ee72cbd627](https://linux-hardware.org/?probe=ee72cbd627) | Sep 29, 2022 |
| HP            | Compaq nx6325 (EY344EA#A... | [8808f98c62](https://linux-hardware.org/?probe=8808f98c62) | Sep 29, 2022 |
| ASUSTek       | N53SV                       | [6652e85ddd](https://linux-hardware.org/?probe=6652e85ddd) | Sep 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | [0453cd781f](https://linux-hardware.org/?probe=0453cd781f) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | [973307d03b](https://linux-hardware.org/?probe=973307d03b) | Sep 28, 2022 |
| Acer          | Aspire A315-23G             | [3eaaf54d1b](https://linux-hardware.org/?probe=3eaaf54d1b) | Sep 28, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [ca9c7bf57b](https://linux-hardware.org/?probe=ca9c7bf57b) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | [730653ea29](https://linux-hardware.org/?probe=730653ea29) | Sep 27, 2022 |
| Lenovo        | G50-70 20351                | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [56e06deea2](https://linux-hardware.org/?probe=56e06deea2) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [2d7ce63bce](https://linux-hardware.org/?probe=2d7ce63bce) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Dell          | Inspiron 15-3567            | [9ae6efbc0f](https://linux-hardware.org/?probe=9ae6efbc0f) | Sep 25, 2022 |
| HUAWEI        | RLEF-XX                     | [7bab2cbc57](https://linux-hardware.org/?probe=7bab2cbc57) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| Dell          | Inspiron 14 5425            | [209be443ac](https://linux-hardware.org/?probe=209be443ac) | Sep 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [6cdacdb935](https://linux-hardware.org/?probe=6cdacdb935) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | [0adb7bc0b1](https://linux-hardware.org/?probe=0adb7bc0b1) | Sep 24, 2022 |
| VIT           | P2402                       | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [40b47d9065](https://linux-hardware.org/?probe=40b47d9065) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Google        | Garg360                     | [4772493ae3](https://linux-hardware.org/?probe=4772493ae3) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | [e17fb419bd](https://linux-hardware.org/?probe=e17fb419bd) | Sep 23, 2022 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | [077c05c78d](https://linux-hardware.org/?probe=077c05c78d) | Sep 23, 2022 |
| Acer          | Aspire ES1-732              | [d6ccc5301b](https://linux-hardware.org/?probe=d6ccc5301b) | Sep 23, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [f77dda559d](https://linux-hardware.org/?probe=f77dda559d) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [412296c83f](https://linux-hardware.org/?probe=412296c83f) | Sep 22, 2022 |
| Dell          | Vostro 15 5510              | [5488a2b9ff](https://linux-hardware.org/?probe=5488a2b9ff) | Sep 22, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [db6f733994](https://linux-hardware.org/?probe=db6f733994) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [21ba0d8f46](https://linux-hardware.org/?probe=21ba0d8f46) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [0c4627555a](https://linux-hardware.org/?probe=0c4627555a) | Sep 22, 2022 |
| Dell          | Inspiron 5537               | [7e3170527c](https://linux-hardware.org/?probe=7e3170527c) | Sep 22, 2022 |
| HP            | Notebook                    | [18b9221add](https://linux-hardware.org/?probe=18b9221add) | Sep 22, 2022 |
| Toshiba       | Satellite P745              | [963d04c729](https://linux-hardware.org/?probe=963d04c729) | Sep 22, 2022 |
| Dell          | Vostro 15 5510              | [630b3877c4](https://linux-hardware.org/?probe=630b3877c4) | Sep 22, 2022 |
| MSI           | GS60 2PE                    | [1aaaa99706](https://linux-hardware.org/?probe=1aaaa99706) | Sep 22, 2022 |
| HP            | Presario CQ57               | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Avell High... | B.ON                        | [95c7e35ef3](https://linux-hardware.org/?probe=95c7e35ef3) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | [41af175db4](https://linux-hardware.org/?probe=41af175db4) | Sep 21, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| Avell High... | B.ON                        | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| Dell          | Precision 7540              | [fb7472fe87](https://linux-hardware.org/?probe=fb7472fe87) | Sep 21, 2022 |
| Dell          | Inspiron MP061              | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [0ada4a5b83](https://linux-hardware.org/?probe=0ada4a5b83) | Sep 20, 2022 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [5861c90514](https://linux-hardware.org/?probe=5861c90514) | Sep 20, 2022 |
| HP            | EliteBook 840 14 inch G9... | [450a86c900](https://linux-hardware.org/?probe=450a86c900) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad X260 20F5003EMB    | [302eacc4ff](https://linux-hardware.org/?probe=302eacc4ff) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad SL400 2743AQC      | [beb74c65cc](https://linux-hardware.org/?probe=beb74c65cc) | Sep 19, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [ae4e13ddc1](https://linux-hardware.org/?probe=ae4e13ddc1) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HP            | 15                          | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [0f049ae5d6](https://linux-hardware.org/?probe=0f049ae5d6) | Sep 19, 2022 |
| HP            | 15                          | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| HP            | G42                         | [3f584eb1af](https://linux-hardware.org/?probe=3f584eb1af) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Panasonic     | CF-53JAWZYDE                | [f8b1ca10d1](https://linux-hardware.org/?probe=f8b1ca10d1) | Sep 19, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [1fa9b05720](https://linux-hardware.org/?probe=1fa9b05720) | Sep 18, 2022 |
| Acer          | Aspire A315-23G             | [9e3edc5b61](https://linux-hardware.org/?probe=9e3edc5b61) | Sep 18, 2022 |
| Lenovo        | IdeaPad 720s-13ARR 81BR     | [fa45602fc5](https://linux-hardware.org/?probe=fa45602fc5) | Sep 18, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [b94564300a](https://linux-hardware.org/?probe=b94564300a) | Sep 18, 2022 |
| Dell          | Latitude E6330              | [bbb0a5f1a1](https://linux-hardware.org/?probe=bbb0a5f1a1) | Sep 18, 2022 |
| Dell          | Latitude E6330              | [8ddda1480b](https://linux-hardware.org/?probe=8ddda1480b) | Sep 18, 2022 |
| Dell          | Latitude 3310               | [4de8502362](https://linux-hardware.org/?probe=4de8502362) | Sep 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [87c3b99589](https://linux-hardware.org/?probe=87c3b99589) | Sep 18, 2022 |
| Acer          | Aspire A315-23G             | [3de0a6e725](https://linux-hardware.org/?probe=3de0a6e725) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [6c5b0c0659](https://linux-hardware.org/?probe=6c5b0c0659) | Sep 17, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [1fa176a244](https://linux-hardware.org/?probe=1fa176a244) | Sep 17, 2022 |
| Dell          | Latitude E6330              | [eb58d87a1d](https://linux-hardware.org/?probe=eb58d87a1d) | Sep 17, 2022 |
| Dell          | Latitude E6330              | [a5b11eaaaf](https://linux-hardware.org/?probe=a5b11eaaaf) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [8c355ea88e](https://linux-hardware.org/?probe=8c355ea88e) | Sep 17, 2022 |
| HP            | Notebook                    | [9fcfcab16e](https://linux-hardware.org/?probe=9fcfcab16e) | Sep 17, 2022 |
| HP            | Unknown                     | [e87c925eb0](https://linux-hardware.org/?probe=e87c925eb0) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7e865e8b3f](https://linux-hardware.org/?probe=7e865e8b3f) | Sep 16, 2022 |
| Aquarius      | NS585                       | [84054aaa40](https://linux-hardware.org/?probe=84054aaa40) | Sep 16, 2022 |
| HP            | Stream Laptop 11-y0XX       | [b030fff6bb](https://linux-hardware.org/?probe=b030fff6bb) | Sep 16, 2022 |
| Aquarius      | NS585                       | [c4ad74720a](https://linux-hardware.org/?probe=c4ad74720a) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Aquarius      | NS585                       | [400485718e](https://linux-hardware.org/?probe=400485718e) | Sep 16, 2022 |
| Lenovo        | G50-45 80E3                 | [59c06bcd6f](https://linux-hardware.org/?probe=59c06bcd6f) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [382325db11](https://linux-hardware.org/?probe=382325db11) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [a1f16914f7](https://linux-hardware.org/?probe=a1f16914f7) | Sep 16, 2022 |
| Aquarius      | NS585                       | [249e3f9a7c](https://linux-hardware.org/?probe=249e3f9a7c) | Sep 16, 2022 |
| Acer          | Aspire A315-23G             | [283a38bb80](https://linux-hardware.org/?probe=283a38bb80) | Sep 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [14cbf91f0c](https://linux-hardware.org/?probe=14cbf91f0c) | Sep 15, 2022 |
| Google        | Stout                       | [82b966b9ad](https://linux-hardware.org/?probe=82b966b9ad) | Sep 15, 2022 |
| Aquarius      | NS585                       | [e86929e9a3](https://linux-hardware.org/?probe=e86929e9a3) | Sep 15, 2022 |
| Aquarius      | NS585                       | [a1568949cd](https://linux-hardware.org/?probe=a1568949cd) | Sep 15, 2022 |
| Aquarius      | NS585                       | [feedc8a0ba](https://linux-hardware.org/?probe=feedc8a0ba) | Sep 15, 2022 |
| Aquarius      | NS585                       | [eb2906fdc5](https://linux-hardware.org/?probe=eb2906fdc5) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3bf32bc004](https://linux-hardware.org/?probe=3bf32bc004) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | [aa5d8a2fc6](https://linux-hardware.org/?probe=aa5d8a2fc6) | Sep 15, 2022 |
| Positivo      | Mobile                      | [f0f7335929](https://linux-hardware.org/?probe=f0f7335929) | Sep 15, 2022 |
| Positivo      | Mobile                      | [ef02cc05aa](https://linux-hardware.org/?probe=ef02cc05aa) | Sep 15, 2022 |
| INFINITY      | Unknown                     | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [5bdc2b7041](https://linux-hardware.org/?probe=5bdc2b7041) | Sep 14, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| Google        | Terra                       | [9dae30736d](https://linux-hardware.org/?probe=9dae30736d) | Sep 14, 2022 |
| Aquarius      | NS585                       | [8fb883495e](https://linux-hardware.org/?probe=8fb883495e) | Sep 14, 2022 |
| Aquarius      | NS585                       | [2c51e9e9c2](https://linux-hardware.org/?probe=2c51e9e9c2) | Sep 14, 2022 |
| Aquarius      | NS585                       | [54a3f9eec9](https://linux-hardware.org/?probe=54a3f9eec9) | Sep 14, 2022 |
| Aquarius      | NS585                       | [3760a35f01](https://linux-hardware.org/?probe=3760a35f01) | Sep 14, 2022 |
| Dell          | Precision 3571              | [72e1a27ea7](https://linux-hardware.org/?probe=72e1a27ea7) | Sep 14, 2022 |
| Aquarius      | NS585                       | [7927c44ef0](https://linux-hardware.org/?probe=7927c44ef0) | Sep 14, 2022 |
| Aquarius      | NS585                       | [eaa0e46c9f](https://linux-hardware.org/?probe=eaa0e46c9f) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8935b3f204](https://linux-hardware.org/?probe=8935b3f204) | Sep 14, 2022 |
| Aquarius      | NS585                       | [a904acc9e9](https://linux-hardware.org/?probe=a904acc9e9) | Sep 14, 2022 |
| Aquarius      | NS585                       | [7f883700cf](https://linux-hardware.org/?probe=7f883700cf) | Sep 14, 2022 |
| Aquarius      | NS585                       | [8ef03a6208](https://linux-hardware.org/?probe=8ef03a6208) | Sep 14, 2022 |
| Aquarius      | NS585                       | [c3f844b853](https://linux-hardware.org/?probe=c3f844b853) | Sep 14, 2022 |
| Aquarius      | NS585                       | [0a77a87395](https://linux-hardware.org/?probe=0a77a87395) | Sep 14, 2022 |
| Aquarius      | NS585                       | [344bf802ef](https://linux-hardware.org/?probe=344bf802ef) | Sep 14, 2022 |
| ASUSTek       | K54HR                       | [6be4965b4d](https://linux-hardware.org/?probe=6be4965b4d) | Sep 14, 2022 |
| Aquarius      | NS585                       | [f627c1d051](https://linux-hardware.org/?probe=f627c1d051) | Sep 14, 2022 |
| Aquarius      | NS585                       | [67eca2e394](https://linux-hardware.org/?probe=67eca2e394) | Sep 14, 2022 |
| Aquarius      | NS585                       | [8c8644f284](https://linux-hardware.org/?probe=8c8644f284) | Sep 14, 2022 |
| Aquarius      | NS585                       | [09ca233ab5](https://linux-hardware.org/?probe=09ca233ab5) | Sep 14, 2022 |
| Dell          | Latitude E7250              | [80a2e50cfc](https://linux-hardware.org/?probe=80a2e50cfc) | Sep 14, 2022 |
| Aquarius      | NS585                       | [df1a5c5ca1](https://linux-hardware.org/?probe=df1a5c5ca1) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | [b8665b7aed](https://linux-hardware.org/?probe=b8665b7aed) | Sep 14, 2022 |
| ASUSTek       | K54HR                       | [e65b9d439e](https://linux-hardware.org/?probe=e65b9d439e) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | [22c2adf69b](https://linux-hardware.org/?probe=22c2adf69b) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [c8994c7912](https://linux-hardware.org/?probe=c8994c7912) | Sep 14, 2022 |
| Dell          | Inspiron 15-7568            | [c3b834caec](https://linux-hardware.org/?probe=c3b834caec) | Sep 14, 2022 |
| Google        | Terra                       | [a7150f06c7](https://linux-hardware.org/?probe=a7150f06c7) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [89339e48f1](https://linux-hardware.org/?probe=89339e48f1) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d39dcbc8ed](https://linux-hardware.org/?probe=d39dcbc8ed) | Sep 13, 2022 |
| Aquarius      | NS585                       | [f76497447f](https://linux-hardware.org/?probe=f76497447f) | Sep 13, 2022 |
| Aquarius      | NS585                       | [0adf35b80f](https://linux-hardware.org/?probe=0adf35b80f) | Sep 13, 2022 |
| Aquarius      | NS585                       | [042a81998b](https://linux-hardware.org/?probe=042a81998b) | Sep 13, 2022 |
| Aquarius      | NS585                       | [e5078cd5f4](https://linux-hardware.org/?probe=e5078cd5f4) | Sep 13, 2022 |
| Dell          | Vostro 15 5510              | [e63dd14c21](https://linux-hardware.org/?probe=e63dd14c21) | Sep 13, 2022 |
| Dell          | Vostro 15 5510              | [16942cfd78](https://linux-hardware.org/?probe=16942cfd78) | Sep 13, 2022 |
| Aquarius      | NS585                       | [adb7dadad9](https://linux-hardware.org/?probe=adb7dadad9) | Sep 13, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7acd0e62aa](https://linux-hardware.org/?probe=7acd0e62aa) | Sep 12, 2022 |
| Google        | Terra                       | [6b591d8c39](https://linux-hardware.org/?probe=6b591d8c39) | Sep 12, 2022 |
| Google        | Terra                       | [b3993f460f](https://linux-hardware.org/?probe=b3993f460f) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| Google        | Reks                        | [28f0932e1a](https://linux-hardware.org/?probe=28f0932e1a) | Sep 12, 2022 |
| Lenovo        | ThinkPad X240 20AL00ETGE    | [95a3df06c9](https://linux-hardware.org/?probe=95a3df06c9) | Sep 12, 2022 |
| MSI           | Modern 15 A11M              | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| MSI           | GS60 2PE                    | [0164cbee91](https://linux-hardware.org/?probe=0164cbee91) | Sep 12, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [3a6e62d846](https://linux-hardware.org/?probe=3a6e62d846) | Sep 12, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [c18f89b2bb](https://linux-hardware.org/?probe=c18f89b2bb) | Sep 11, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [cd49377ddf](https://linux-hardware.org/?probe=cd49377ddf) | Sep 11, 2022 |
| HP            | G42                         | [092b9e2c38](https://linux-hardware.org/?probe=092b9e2c38) | Sep 11, 2022 |
| HP            | 255 G8 Notebook PC          | [cca78f4488](https://linux-hardware.org/?probe=cca78f4488) | Sep 11, 2022 |
| Lenovo        | ThinkPad L460 20FVS1BC0S    | [e668edf31d](https://linux-hardware.org/?probe=e668edf31d) | Sep 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5a7c8dfacf](https://linux-hardware.org/?probe=5a7c8dfacf) | Sep 10, 2022 |
| Google        | Treeya                      | [d7a00caa63](https://linux-hardware.org/?probe=d7a00caa63) | Sep 10, 2022 |
| Lenovo        | G50-45 80E3                 | [2f4b4e4203](https://linux-hardware.org/?probe=2f4b4e4203) | Sep 10, 2022 |
| ASUSTek       | X200CA                      | [70c2613095](https://linux-hardware.org/?probe=70c2613095) | Sep 09, 2022 |
| Acer          | AO532h                      | [3ea8a4ba38](https://linux-hardware.org/?probe=3ea8a4ba38) | Sep 09, 2022 |
| Toshiba       | Satellite L40               | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Dell          | Latitude E6330              | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [92ae6811fa](https://linux-hardware.org/?probe=92ae6811fa) | Sep 09, 2022 |
| HP            | Compaq 8510w                | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [d37b0f4483](https://linux-hardware.org/?probe=d37b0f4483) | Sep 08, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [c8f2e1da45](https://linux-hardware.org/?probe=c8f2e1da45) | Sep 08, 2022 |
| Google        | Reks                        | [a171b11595](https://linux-hardware.org/?probe=a171b11595) | Sep 08, 2022 |
| ASUSTek       | UX430UAR                    | [478d0564a6](https://linux-hardware.org/?probe=478d0564a6) | Sep 08, 2022 |
| HP            | ProBook 440 G7              | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| ASUSTek       | X441NA                      | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| Acer          | Aspire 5738                 | [141712c674](https://linux-hardware.org/?probe=141712c674) | Sep 07, 2022 |
| Lenovo        | B570e 521524G               | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| HP            | Laptop 17-ca0xxx            | [c65eb0b5c8](https://linux-hardware.org/?probe=c65eb0b5c8) | Sep 07, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [044bee5e0c](https://linux-hardware.org/?probe=044bee5e0c) | Sep 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [c0e98bf9e5](https://linux-hardware.org/?probe=c0e98bf9e5) | Sep 06, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e3d0a2c84c](https://linux-hardware.org/?probe=e3d0a2c84c) | Sep 06, 2022 |
| Aquarius      | NS585                       | [74e50c07d8](https://linux-hardware.org/?probe=74e50c07d8) | Sep 06, 2022 |
| HP            | ENVY 17                     | [63411dc061](https://linux-hardware.org/?probe=63411dc061) | Sep 06, 2022 |
| Lenovo        | ThinkPad P51s 20HB000URT    | [8214e1ba30](https://linux-hardware.org/?probe=8214e1ba30) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | [fefa3f4935](https://linux-hardware.org/?probe=fefa3f4935) | Sep 06, 2022 |
| HP            | ProBook 640 G4              | [b76e5a62e8](https://linux-hardware.org/?probe=b76e5a62e8) | Sep 06, 2022 |
| Dell          | Latitude 5530               | [4a2fb0c4c2](https://linux-hardware.org/?probe=4a2fb0c4c2) | Sep 06, 2022 |
| Dell          | Latitude 5530               | [a0896a063c](https://linux-hardware.org/?probe=a0896a063c) | Sep 06, 2022 |
| ASUSTek       | X555LAB                     | [b10937286d](https://linux-hardware.org/?probe=b10937286d) | Sep 06, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [6bd37547d3](https://linux-hardware.org/?probe=6bd37547d3) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [5df6bc21c7](https://linux-hardware.org/?probe=5df6bc21c7) | Sep 05, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [4c68e17f1a](https://linux-hardware.org/?probe=4c68e17f1a) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e6117fb016](https://linux-hardware.org/?probe=e6117fb016) | Sep 05, 2022 |
| Dell          | Vostro 15 5510              | [beb1aeb4ad](https://linux-hardware.org/?probe=beb1aeb4ad) | Sep 05, 2022 |
| Acer          | Aspire A517-52G             | [c1709e40b7](https://linux-hardware.org/?probe=c1709e40b7) | Sep 05, 2022 |
| Unknown       | Unknown                     | [efb1e9883d](https://linux-hardware.org/?probe=efb1e9883d) | Sep 05, 2022 |
| Unknown       | Unknown                     | [20178af23f](https://linux-hardware.org/?probe=20178af23f) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [f85aa66b33](https://linux-hardware.org/?probe=f85aa66b33) | Sep 04, 2022 |
| Dell          | Latitude E6330              | [e4dcf51a84](https://linux-hardware.org/?probe=e4dcf51a84) | Sep 04, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [ea93dfd855](https://linux-hardware.org/?probe=ea93dfd855) | Sep 04, 2022 |
| Lenovo        | ThinkPad X230 232438J       | [dca0e2fa77](https://linux-hardware.org/?probe=dca0e2fa77) | Sep 04, 2022 |
| HP            | Compaq 8510w                | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| PC Special... | 14 Fusion IV                | [dd9ed93b55](https://linux-hardware.org/?probe=dd9ed93b55) | Sep 03, 2022 |
| HP            | Compaq 6910p                | [0165c7d3c6](https://linux-hardware.org/?probe=0165c7d3c6) | Sep 03, 2022 |
| Aquarius      | NS585                       | [b11a34556d](https://linux-hardware.org/?probe=b11a34556d) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Acer          | Aspire A315-23G             | [9a2200f8f8](https://linux-hardware.org/?probe=9a2200f8f8) | Sep 03, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [c8bf09dd8d](https://linux-hardware.org/?probe=c8bf09dd8d) | Sep 02, 2022 |
| Aquarius      | NS585                       | [86de3c4954](https://linux-hardware.org/?probe=86de3c4954) | Sep 02, 2022 |
| Dell          | XPS 13 9350                 | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Google        | Enguarde                    | [50369de0be](https://linux-hardware.org/?probe=50369de0be) | Sep 01, 2022 |
| Dell          | Latitude E6330              | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| MSI           | Katana GF66 12UC            | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| Google        | Enguarde                    | [b59a9615cd](https://linux-hardware.org/?probe=b59a9615cd) | Sep 01, 2022 |
| Google        | Enguarde                    | [7acc7436b0](https://linux-hardware.org/?probe=7acc7436b0) | Sep 01, 2022 |
| Google        | Enguarde                    | [671a062f6e](https://linux-hardware.org/?probe=671a062f6e) | Sep 01, 2022 |
| Google        | Enguarde                    | [baabafd42b](https://linux-hardware.org/?probe=baabafd42b) | Sep 01, 2022 |
| Google        | Enguarde                    | [4c1595c83e](https://linux-hardware.org/?probe=4c1595c83e) | Sep 01, 2022 |
| Google        | Enguarde                    | [bb6b28b279](https://linux-hardware.org/?probe=bb6b28b279) | Sep 01, 2022 |
| Google        | Terra                       | [b7940ab738](https://linux-hardware.org/?probe=b7940ab738) | Sep 01, 2022 |
| Google        | Enguarde                    | [0cbe57b975](https://linux-hardware.org/?probe=0cbe57b975) | Sep 01, 2022 |
| Google        | Enguarde                    | [9f20842cc5](https://linux-hardware.org/?probe=9f20842cc5) | Sep 01, 2022 |
| Google        | Enguarde                    | [06969489cc](https://linux-hardware.org/?probe=06969489cc) | Sep 01, 2022 |
| Google        | Enguarde                    | [2b4231258e](https://linux-hardware.org/?probe=2b4231258e) | Sep 01, 2022 |
| Google        | Enguarde                    | [1a0596c60d](https://linux-hardware.org/?probe=1a0596c60d) | Sep 01, 2022 |
| Google        | Enguarde                    | [4dfdb5e364](https://linux-hardware.org/?probe=4dfdb5e364) | Sep 01, 2022 |
| Google        | Enguarde                    | [c6db81251c](https://linux-hardware.org/?probe=c6db81251c) | Sep 01, 2022 |
| Google        | Enguarde                    | [05f112ddb7](https://linux-hardware.org/?probe=05f112ddb7) | Sep 01, 2022 |
| Dell          | Vostro 15 5510              | [1c58d69316](https://linux-hardware.org/?probe=1c58d69316) | Sep 01, 2022 |
| Dell          | Vostro 15 5510              | [e14cc69370](https://linux-hardware.org/?probe=e14cc69370) | Sep 01, 2022 |
| ASUSTek       | K50IJ                       | [10dd5d1e15](https://linux-hardware.org/?probe=10dd5d1e15) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| ASUSTek       | UX550VD                     | [a43d53b3b7](https://linux-hardware.org/?probe=a43d53b3b7) | Sep 01, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [7277e72eb4](https://linux-hardware.org/?probe=7277e72eb4) | Aug 31, 2022 |
| Google        | Enguarde                    | [4a240c438e](https://linux-hardware.org/?probe=4a240c438e) | Aug 31, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [0c62d097f0](https://linux-hardware.org/?probe=0c62d097f0) | Aug 31, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [7931f65300](https://linux-hardware.org/?probe=7931f65300) | Aug 31, 2022 |
| Dell          | Latitude E6330              | [b5766d41fa](https://linux-hardware.org/?probe=b5766d41fa) | Aug 31, 2022 |
| HP            | 250 G8 Notebook PC          | [c0a39342c3](https://linux-hardware.org/?probe=c0a39342c3) | Aug 31, 2022 |
| HP            | Compaq 8510w                | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| Google        | Enguarde                    | [7aa44db561](https://linux-hardware.org/?probe=7aa44db561) | Aug 30, 2022 |
| HP            | Compaq nc6400 (RU626ET#A... | [e94cb8e943](https://linux-hardware.org/?probe=e94cb8e943) | Aug 30, 2022 |
| Dell          | Vostro 15 5510              | [c89b1e69f4](https://linux-hardware.org/?probe=c89b1e69f4) | Aug 30, 2022 |
| Google        | Reks                        | [71f6228c3d](https://linux-hardware.org/?probe=71f6228c3d) | Aug 30, 2022 |
| Google        | Reks                        | [48174b01b3](https://linux-hardware.org/?probe=48174b01b3) | Aug 30, 2022 |
| ASUSTek       | X550CC                      | [f9a9be3a35](https://linux-hardware.org/?probe=f9a9be3a35) | Aug 30, 2022 |
| Google        | Terra                       | [25f50ae6d9](https://linux-hardware.org/?probe=25f50ae6d9) | Aug 30, 2022 |
| Google        | Reks                        | [e768a1940e](https://linux-hardware.org/?probe=e768a1940e) | Aug 30, 2022 |
| Lenovo        | ThinkPad L490 20Q5001YPB    | [daae538154](https://linux-hardware.org/?probe=daae538154) | Aug 30, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [ca01260ab8](https://linux-hardware.org/?probe=ca01260ab8) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [30b240a3fe](https://linux-hardware.org/?probe=30b240a3fe) | Aug 29, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [ddc175428b](https://linux-hardware.org/?probe=ddc175428b) | Aug 29, 2022 |
| Dell          | Latitude 5590               | [e06f40dae9](https://linux-hardware.org/?probe=e06f40dae9) | Aug 29, 2022 |
| Acer          | TravelMate P215-53          | [4ba2e9fbba](https://linux-hardware.org/?probe=4ba2e9fbba) | Aug 29, 2022 |
| ASUSTek       | K55VM                       | [ec5806d544](https://linux-hardware.org/?probe=ec5806d544) | Aug 29, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| Dell          | Latitude 5420               | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [a10cbdb73b](https://linux-hardware.org/?probe=a10cbdb73b) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [562d827323](https://linux-hardware.org/?probe=562d827323) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c155c4b324](https://linux-hardware.org/?probe=c155c4b324) | Aug 27, 2022 |
| HP            | Compaq 6910p                | [894b5297c8](https://linux-hardware.org/?probe=894b5297c8) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8231da35ed](https://linux-hardware.org/?probe=8231da35ed) | Aug 27, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2KU0... | [6500c142f5](https://linux-hardware.org/?probe=6500c142f5) | Aug 27, 2022 |
| Dell          | Vostro 15 5510              | [c3d134ca75](https://linux-hardware.org/?probe=c3d134ca75) | Aug 27, 2022 |
| Medion        | Akoya P2213T                | [c8d10c3b3f](https://linux-hardware.org/?probe=c8d10c3b3f) | Aug 27, 2022 |
| Google        | Terra                       | [717b3cc17f](https://linux-hardware.org/?probe=717b3cc17f) | Aug 26, 2022 |
| Google        | Terra                       | [f9856d813e](https://linux-hardware.org/?probe=f9856d813e) | Aug 26, 2022 |
| ASUSTek       | X455LD                      | [5351e31366](https://linux-hardware.org/?probe=5351e31366) | Aug 26, 2022 |
| Lenovo        | ThinkPad T590 20N4001NUS    | [479ef1a89c](https://linux-hardware.org/?probe=479ef1a89c) | Aug 26, 2022 |
| ASUSTek       | M70Vn                       | [2e84d460f5](https://linux-hardware.org/?probe=2e84d460f5) | Aug 26, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [73c598ebe7](https://linux-hardware.org/?probe=73c598ebe7) | Aug 26, 2022 |
| Lenovo        | ThinkPad T400 2768BM2       | [f2d91055c9](https://linux-hardware.org/?probe=f2d91055c9) | Aug 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [a624a45cda](https://linux-hardware.org/?probe=a624a45cda) | Aug 26, 2022 |
| HP            | ProBook 450 G6              | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [843ee79f1b](https://linux-hardware.org/?probe=843ee79f1b) | Aug 25, 2022 |
| Google        | Terra                       | [72965945d5](https://linux-hardware.org/?probe=72965945d5) | Aug 25, 2022 |
| Google        | Terra                       | [78436fd3bf](https://linux-hardware.org/?probe=78436fd3bf) | Aug 25, 2022 |
| Apple         | MacBookAir7,2               | [b2dc63405c](https://linux-hardware.org/?probe=b2dc63405c) | Aug 25, 2022 |
| Dell          | Inspiron 600m               | [6acc515c79](https://linux-hardware.org/?probe=6acc515c79) | Aug 25, 2022 |
| Dell          | Latitude 3570               | [287cfa2ce8](https://linux-hardware.org/?probe=287cfa2ce8) | Aug 25, 2022 |
| Lenovo        | ThinkPad E490 20N8001EUS    | [1620f0e5ff](https://linux-hardware.org/?probe=1620f0e5ff) | Aug 24, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| Dell          | XPS 15 9500                 | [b3a7cd094e](https://linux-hardware.org/?probe=b3a7cd094e) | Aug 24, 2022 |
| HP            | Laptop 14-dq2xxx            | [bc4f5f8811](https://linux-hardware.org/?probe=bc4f5f8811) | Aug 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [8b346ab142](https://linux-hardware.org/?probe=8b346ab142) | Aug 24, 2022 |
| Google        | Reks                        | [043b648dc5](https://linux-hardware.org/?probe=043b648dc5) | Aug 23, 2022 |
| Google        | Terra                       | [b720f3ca23](https://linux-hardware.org/?probe=b720f3ca23) | Aug 23, 2022 |
| Google        | Terra                       | [0fd5baced8](https://linux-hardware.org/?probe=0fd5baced8) | Aug 23, 2022 |
| Dell          | Inspiron 3583               | [dfbced302f](https://linux-hardware.org/?probe=dfbced302f) | Aug 23, 2022 |
| Google        | Terra                       | [92efdef775](https://linux-hardware.org/?probe=92efdef775) | Aug 23, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [e5d3453caa](https://linux-hardware.org/?probe=e5d3453caa) | Aug 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | [91f1311a5f](https://linux-hardware.org/?probe=91f1311a5f) | Aug 23, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [351d3809aa](https://linux-hardware.org/?probe=351d3809aa) | Aug 23, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [801a4be04d](https://linux-hardware.org/?probe=801a4be04d) | Aug 23, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | [2ac415ca87](https://linux-hardware.org/?probe=2ac415ca87) | Aug 23, 2022 |
| Dell          | Vostro 15 5510              | [3224d8bdcc](https://linux-hardware.org/?probe=3224d8bdcc) | Aug 23, 2022 |
| VANT          | MOOVE3-15                   | [854b7f42d4](https://linux-hardware.org/?probe=854b7f42d4) | Aug 22, 2022 |
| Acer          | Aspire 5742                 | [6692313edb](https://linux-hardware.org/?probe=6692313edb) | Aug 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [0e2b064aed](https://linux-hardware.org/?probe=0e2b064aed) | Aug 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [2431fa78d1](https://linux-hardware.org/?probe=2431fa78d1) | Aug 21, 2022 |
| HP            | Laptop 15-dy2xxx            | [532e1358b6](https://linux-hardware.org/?probe=532e1358b6) | Aug 21, 2022 |
| Dell          | XPS 15 9550                 | [8ab7fcb6ff](https://linux-hardware.org/?probe=8ab7fcb6ff) | Aug 21, 2022 |
| Dell          | Precision 7720              | [60ad0b7b3d](https://linux-hardware.org/?probe=60ad0b7b3d) | Aug 21, 2022 |
| Positivo      | Mobile                      | [8678ddf7ac](https://linux-hardware.org/?probe=8678ddf7ac) | Aug 20, 2022 |
| Positivo      | Mobile                      | [d1cf6b8c9e](https://linux-hardware.org/?probe=d1cf6b8c9e) | Aug 20, 2022 |
| VANT          | MOOVE3-15                   | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| Dell          | Vostro 15 5510              | [9f5e59e0b9](https://linux-hardware.org/?probe=9f5e59e0b9) | Aug 20, 2022 |
| MSI           | GF75 Thin 10SCSXR           | [095c130069](https://linux-hardware.org/?probe=095c130069) | Aug 20, 2022 |
| HP            | 620                         | [d3b1eb8b4e](https://linux-hardware.org/?probe=d3b1eb8b4e) | Aug 20, 2022 |
| HP            | Laptop 17-cp0xxx            | [6ba8616656](https://linux-hardware.org/?probe=6ba8616656) | Aug 20, 2022 |
| Google        | Reks                        | [e5cde69ff7](https://linux-hardware.org/?probe=e5cde69ff7) | Aug 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [9e72f598eb](https://linux-hardware.org/?probe=9e72f598eb) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [45bfdfa985](https://linux-hardware.org/?probe=45bfdfa985) | Aug 19, 2022 |
| HP            | 620                         | [259635c419](https://linux-hardware.org/?probe=259635c419) | Aug 19, 2022 |
| ICL           | N7x0WU                      | [7b9c4ad6b1](https://linux-hardware.org/?probe=7b9c4ad6b1) | Aug 19, 2022 |
| HP            | Compaq nx7300 (RH678EA#A... | [6fc01cef23](https://linux-hardware.org/?probe=6fc01cef23) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [e6003f393e](https://linux-hardware.org/?probe=e6003f393e) | Aug 19, 2022 |
| Dell          | Latitude 5500               | [1c7c8639aa](https://linux-hardware.org/?probe=1c7c8639aa) | Aug 19, 2022 |
| Google        | Reks                        | [d09d250717](https://linux-hardware.org/?probe=d09d250717) | Aug 18, 2022 |
| Google        | Terra                       | [4eca7693ab](https://linux-hardware.org/?probe=4eca7693ab) | Aug 18, 2022 |
| Google        | Reks                        | [9fc034e8a0](https://linux-hardware.org/?probe=9fc034e8a0) | Aug 18, 2022 |
| Google        | Terra                       | [aabdca917b](https://linux-hardware.org/?probe=aabdca917b) | Aug 18, 2022 |
| Acer          | TravelMate 5620             | [5b1df1054c](https://linux-hardware.org/?probe=5b1df1054c) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Dell          | Vostro 3405                 | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Acer          | TravelMate 5620             | [cdb6e6d5d6](https://linux-hardware.org/?probe=cdb6e6d5d6) | Aug 17, 2022 |
| ASUSTek       | K70IJ                       | [99bb1459e7](https://linux-hardware.org/?probe=99bb1459e7) | Aug 17, 2022 |
| Shuttle       | DS437                       | [21e0ca6a77](https://linux-hardware.org/?probe=21e0ca6a77) | Aug 17, 2022 |
| Dell          | Precision M6600             | [2e1eaedbc4](https://linux-hardware.org/?probe=2e1eaedbc4) | Aug 17, 2022 |
| HP            | Laptop 14-dq2xxx            | [9cefc23bb3](https://linux-hardware.org/?probe=9cefc23bb3) | Aug 17, 2022 |
| HP            | 255 G5 Notebook PC          | [fdeea5b020](https://linux-hardware.org/?probe=fdeea5b020) | Aug 16, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [74e8d1be5b](https://linux-hardware.org/?probe=74e8d1be5b) | Aug 16, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [d04d18b241](https://linux-hardware.org/?probe=d04d18b241) | Aug 16, 2022 |
| Dell          | Inspiron 5547               | [84a3ba511d](https://linux-hardware.org/?probe=84a3ba511d) | Aug 16, 2022 |
| PCBOX         | Kant                        | [1b5c160d93](https://linux-hardware.org/?probe=1b5c160d93) | Aug 16, 2022 |
| Google        | Terra                       | [8c5b7a9814](https://linux-hardware.org/?probe=8c5b7a9814) | Aug 15, 2022 |
| Google        | Terra                       | [43c28dadff](https://linux-hardware.org/?probe=43c28dadff) | Aug 15, 2022 |
| Google        | Terra                       | [98b7a9a377](https://linux-hardware.org/?probe=98b7a9a377) | Aug 15, 2022 |
| Google        | Terra                       | [3bfcb2b1b4](https://linux-hardware.org/?probe=3bfcb2b1b4) | Aug 15, 2022 |
| Toshiba       | Satellite P50-B-103         | [26811058c5](https://linux-hardware.org/?probe=26811058c5) | Aug 15, 2022 |
| Dell          | Latitude 5420               | [0dec3e9676](https://linux-hardware.org/?probe=0dec3e9676) | Aug 15, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [2c02d907a6](https://linux-hardware.org/?probe=2c02d907a6) | Aug 15, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [8a91001294](https://linux-hardware.org/?probe=8a91001294) | Aug 15, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Toshiba       | Satellite P50-B-103         | [39da8f51fe](https://linux-hardware.org/?probe=39da8f51fe) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | [fcdd677280](https://linux-hardware.org/?probe=fcdd677280) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | [eeed6b3d08](https://linux-hardware.org/?probe=eeed6b3d08) | Aug 14, 2022 |
| HP            | Compaq 6910p                | [97e8467d4d](https://linux-hardware.org/?probe=97e8467d4d) | Aug 13, 2022 |
| Dell          | Latitude E5430 vPro         | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| Acer          | Aspire A315-23G             | [cdba281a27](https://linux-hardware.org/?probe=cdba281a27) | Aug 13, 2022 |
| Apple         | MacBookPro12,1              | [8b417889e1](https://linux-hardware.org/?probe=8b417889e1) | Aug 13, 2022 |
| HP            | Presario CQ56               | [48dfc2da91](https://linux-hardware.org/?probe=48dfc2da91) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | [188bfa465d](https://linux-hardware.org/?probe=188bfa465d) | Aug 13, 2022 |
| Dell          | Latitude E6330              | [b48c021700](https://linux-hardware.org/?probe=b48c021700) | Aug 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [94eb72e4ac](https://linux-hardware.org/?probe=94eb72e4ac) | Aug 13, 2022 |
| HP            | Pavilion Notebook           | [3dd4d44be4](https://linux-hardware.org/?probe=3dd4d44be4) | Aug 12, 2022 |
| Acer          | Aspire A114-33              | [471a1ec71e](https://linux-hardware.org/?probe=471a1ec71e) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | [ed37ad46b6](https://linux-hardware.org/?probe=ed37ad46b6) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | [2fab557514](https://linux-hardware.org/?probe=2fab557514) | Aug 12, 2022 |
| Dell          | XPS 13 9350                 | [6f828c5743](https://linux-hardware.org/?probe=6f828c5743) | Aug 12, 2022 |
| Apple         | MacBookAir7,2               | [c38e80ade4](https://linux-hardware.org/?probe=c38e80ade4) | Aug 11, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [efd4ec3ee7](https://linux-hardware.org/?probe=efd4ec3ee7) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | [4d052b34a7](https://linux-hardware.org/?probe=4d052b34a7) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [d64d35a05d](https://linux-hardware.org/?probe=d64d35a05d) | Aug 11, 2022 |
| Dell          | Latitude 6430U              | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [23b946fc6d](https://linux-hardware.org/?probe=23b946fc6d) | Aug 11, 2022 |
| Toshiba       | Satellite M645              | [9fa1e00c24](https://linux-hardware.org/?probe=9fa1e00c24) | Aug 10, 2022 |
| Toshiba       | TECRA R950                  | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| ASUSTek       | X751LJ                      | [5c3767ccc2](https://linux-hardware.org/?probe=5c3767ccc2) | Aug 10, 2022 |
| Dell          | Latitude E6420              | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| GPU Compan... | GWTC116-2                   | [b92ffbefad](https://linux-hardware.org/?probe=b92ffbefad) | Aug 09, 2022 |
| ASUSTek       | X751LJ                      | [e35689c8f1](https://linux-hardware.org/?probe=e35689c8f1) | Aug 09, 2022 |
| Acer          | Aspire A515-56              | [21fdf57c32](https://linux-hardware.org/?probe=21fdf57c32) | Aug 09, 2022 |
| HP            | EliteBook 725 G3            | [7e36a68724](https://linux-hardware.org/?probe=7e36a68724) | Aug 09, 2022 |
| NVN-ED01      | Unknown                     | [0a677cad6c](https://linux-hardware.org/?probe=0a677cad6c) | Aug 09, 2022 |
| Alienware     | m15 R6                      | [675208eaec](https://linux-hardware.org/?probe=675208eaec) | Aug 09, 2022 |
| Dell          | Precision 7720              | [e79faaa4c0](https://linux-hardware.org/?probe=e79faaa4c0) | Aug 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [b8ae818291](https://linux-hardware.org/?probe=b8ae818291) | Aug 08, 2022 |
| Dell          | Latitude E7450              | [f2d8a030f4](https://linux-hardware.org/?probe=f2d8a030f4) | Aug 08, 2022 |
| HP            | EliteBook 725 G3            | [e48eff307c](https://linux-hardware.org/?probe=e48eff307c) | Aug 08, 2022 |
| Acer          | Aspire A315-23G             | [46b74e61f0](https://linux-hardware.org/?probe=46b74e61f0) | Aug 08, 2022 |
| Dell          | Latitude E6430              | [17d0fce9e5](https://linux-hardware.org/?probe=17d0fce9e5) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | [b1420b630f](https://linux-hardware.org/?probe=b1420b630f) | Aug 07, 2022 |
| Acer          | Aspire 5738                 | [31d08ab231](https://linux-hardware.org/?probe=31d08ab231) | Aug 07, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [19b3f7fe4b](https://linux-hardware.org/?probe=19b3f7fe4b) | Aug 07, 2022 |
| Dell          | Precision 7720              | [db2f868372](https://linux-hardware.org/?probe=db2f868372) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0564acfb6c](https://linux-hardware.org/?probe=0564acfb6c) | Aug 07, 2022 |
| SANTECH       | NHx0DB,DE                   | [1eba623e90](https://linux-hardware.org/?probe=1eba623e90) | Aug 06, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [53c997fe1f](https://linux-hardware.org/?probe=53c997fe1f) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d5786b75a3](https://linux-hardware.org/?probe=d5786b75a3) | Aug 05, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [24d8a6228c](https://linux-hardware.org/?probe=24d8a6228c) | Aug 05, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [83c6e58e51](https://linux-hardware.org/?probe=83c6e58e51) | Aug 05, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d12e654f35](https://linux-hardware.org/?probe=d12e654f35) | Aug 05, 2022 |
| HP            | ProBook 430 G5              | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| ASUSTek       | X550CC                      | [9d032c38b4](https://linux-hardware.org/?probe=9d032c38b4) | Aug 05, 2022 |
| ASUSTek       | X550CC                      | [433126127b](https://linux-hardware.org/?probe=433126127b) | Aug 05, 2022 |
| Acer          | Aspire 5315                 | [7be46d4930](https://linux-hardware.org/?probe=7be46d4930) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | [87d90381e1](https://linux-hardware.org/?probe=87d90381e1) | Aug 04, 2022 |
| HP            | EliteBook 8460p             | [7948505598](https://linux-hardware.org/?probe=7948505598) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e74155922c](https://linux-hardware.org/?probe=e74155922c) | Aug 04, 2022 |
| Acer          | AO532h                      | [9a35f25fba](https://linux-hardware.org/?probe=9a35f25fba) | Aug 04, 2022 |
| Acer          | Aspire A315-23G             | [52e4d5e94f](https://linux-hardware.org/?probe=52e4d5e94f) | Aug 03, 2022 |
| Google        | Droid                       | [15d4518ba0](https://linux-hardware.org/?probe=15d4518ba0) | Aug 03, 2022 |
| ASUSTek       | X756UQK                     | [97b2316a06](https://linux-hardware.org/?probe=97b2316a06) | Aug 03, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [94ccc2e14f](https://linux-hardware.org/?probe=94ccc2e14f) | Aug 03, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [0bf365f767](https://linux-hardware.org/?probe=0bf365f767) | Aug 02, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [e586e6ee53](https://linux-hardware.org/?probe=e586e6ee53) | Aug 02, 2022 |
| HP            | 255 G3                      | [46ad188006](https://linux-hardware.org/?probe=46ad188006) | Aug 02, 2022 |
| HUAWEI        | CREM-WXX9                   | [9e48213e39](https://linux-hardware.org/?probe=9e48213e39) | Aug 02, 2022 |
| HUAWEI        | CREM-WXX9                   | [2efb41280c](https://linux-hardware.org/?probe=2efb41280c) | Aug 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5d4fdde00](https://linux-hardware.org/?probe=f5d4fdde00) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [743422e837](https://linux-hardware.org/?probe=743422e837) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [78bde5c7cc](https://linux-hardware.org/?probe=78bde5c7cc) | Aug 02, 2022 |
| Dell          | Inspiron 13-7378            | [c08447d945](https://linux-hardware.org/?probe=c08447d945) | Aug 01, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [ae2fa8b811](https://linux-hardware.org/?probe=ae2fa8b811) | Aug 01, 2022 |
| Dell          | Latitude 7420               | [d498af2db5](https://linux-hardware.org/?probe=d498af2db5) | Aug 01, 2022 |
| Toshiba       | TECRA Z40-C                 | [9612659f60](https://linux-hardware.org/?probe=9612659f60) | Aug 01, 2022 |
| Apple         | MacBookPro11,5              | [24ccaddbf8](https://linux-hardware.org/?probe=24ccaddbf8) | Jul 31, 2022 |
| HP            | ProBook 4310s               | [d15b493637](https://linux-hardware.org/?probe=d15b493637) | Jul 31, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [9b362907fc](https://linux-hardware.org/?probe=9b362907fc) | Jul 30, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [61aed5ab55](https://linux-hardware.org/?probe=61aed5ab55) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | [1b94bd5797](https://linux-hardware.org/?probe=1b94bd5797) | Jul 29, 2022 |
| Acer          | AO756                       | [8203ac54d7](https://linux-hardware.org/?probe=8203ac54d7) | Jul 29, 2022 |
| ASUSTek       | GL553VE                     | [0bbcd152c5](https://linux-hardware.org/?probe=0bbcd152c5) | Jul 29, 2022 |
| Samsung       | R505                        | [4f92cf3c93](https://linux-hardware.org/?probe=4f92cf3c93) | Jul 29, 2022 |
| Lenovo        | ThinkPad L480 20LS002CPB    | [35764371d6](https://linux-hardware.org/?probe=35764371d6) | Jul 29, 2022 |
| Dell          | Latitude E5500              | [ba214335da](https://linux-hardware.org/?probe=ba214335da) | Jul 28, 2022 |
| HP            | Compaq 8510p                | [2a005b06da](https://linux-hardware.org/?probe=2a005b06da) | Jul 28, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [a05f5dc510](https://linux-hardware.org/?probe=a05f5dc510) | Jul 28, 2022 |
| Lenovo        | S21e-20 80M4                | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [87f0eb95eb](https://linux-hardware.org/?probe=87f0eb95eb) | Jul 27, 2022 |
| HP            | Stream Notebook PC 11       | [e3c8a52e5b](https://linux-hardware.org/?probe=e3c8a52e5b) | Jul 27, 2022 |
| Acer          | Aspire A515-43              | [d378021961](https://linux-hardware.org/?probe=d378021961) | Jul 26, 2022 |
| ASUSTek       | ZenBook UX325UA             | [587ea51239](https://linux-hardware.org/?probe=587ea51239) | Jul 26, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [8aa5207a61](https://linux-hardware.org/?probe=8aa5207a61) | Jul 26, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [fc5bf3cb22](https://linux-hardware.org/?probe=fc5bf3cb22) | Jul 26, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [c0b3aa1bea](https://linux-hardware.org/?probe=c0b3aa1bea) | Jul 26, 2022 |
| HONOR         | BBR-WAX9                    | [afe7a4d56a](https://linux-hardware.org/?probe=afe7a4d56a) | Jul 26, 2022 |
| Lenovo        | G410 20237                  | [c23a040e55](https://linux-hardware.org/?probe=c23a040e55) | Jul 25, 2022 |
| HP            | Notebook                    | [fdc7478b06](https://linux-hardware.org/?probe=fdc7478b06) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bf2cecb453](https://linux-hardware.org/?probe=bf2cecb453) | Jul 25, 2022 |
| Acer          | Aspire A315-23G             | [df57effbc5](https://linux-hardware.org/?probe=df57effbc5) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e2a1804b90](https://linux-hardware.org/?probe=e2a1804b90) | Jul 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [04737cec4e](https://linux-hardware.org/?probe=04737cec4e) | Jul 24, 2022 |
| Dell          | Latitude E5430 non-vPro     | [f8808faaf0](https://linux-hardware.org/?probe=f8808faaf0) | Jul 24, 2022 |
| HP            | ProBook 450 G3              | [288db20204](https://linux-hardware.org/?probe=288db20204) | Jul 23, 2022 |
| ASUSTek       | X541UVK                     | [fb1513d31e](https://linux-hardware.org/?probe=fb1513d31e) | Jul 21, 2022 |
| Dell          | Latitude 5420               | [51cf24b119](https://linux-hardware.org/?probe=51cf24b119) | Jul 21, 2022 |
| HP            | ZBook 15 G3                 | [758ce4f6b4](https://linux-hardware.org/?probe=758ce4f6b4) | Jul 21, 2022 |
| Unknown       | W1415A                      | [3a2f4f9848](https://linux-hardware.org/?probe=3a2f4f9848) | Jul 21, 2022 |
| Acer          | TravelMate 8371             | [4af529e1c4](https://linux-hardware.org/?probe=4af529e1c4) | Jul 20, 2022 |
| Avell High... | A40 LIV                     | [7a685eedd0](https://linux-hardware.org/?probe=7a685eedd0) | Jul 20, 2022 |
| Lenovo        | G550 2958                   | [caeec900b9](https://linux-hardware.org/?probe=caeec900b9) | Jul 19, 2022 |
| Acer          | Aspire A515-45              | [4189e96860](https://linux-hardware.org/?probe=4189e96860) | Jul 19, 2022 |
| HP            | 255 G8 Notebook PC          | [59e9017400](https://linux-hardware.org/?probe=59e9017400) | Jul 19, 2022 |
| Sony          | VPCEH37FJ                   | [1cc39f5c15](https://linux-hardware.org/?probe=1cc39f5c15) | Jul 19, 2022 |
| Lenovo        | G550 2958                   | [ee73634801](https://linux-hardware.org/?probe=ee73634801) | Jul 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [9d756ec471](https://linux-hardware.org/?probe=9d756ec471) | Jul 18, 2022 |
| HP            | Compaq 6910p                | [e6a5ffa902](https://linux-hardware.org/?probe=e6a5ffa902) | Jul 18, 2022 |
| Razer         | Blade 15 Advanced Model ... | [8f3842495f](https://linux-hardware.org/?probe=8f3842495f) | Jul 18, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [92136ca850](https://linux-hardware.org/?probe=92136ca850) | Jul 18, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [56fbc3bbaa](https://linux-hardware.org/?probe=56fbc3bbaa) | Jul 18, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [aa5bdf4dd0](https://linux-hardware.org/?probe=aa5bdf4dd0) | Jul 18, 2022 |
| Acer          | Aspire A315-23G             | [268d2145ff](https://linux-hardware.org/?probe=268d2145ff) | Jul 17, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [42d7df651d](https://linux-hardware.org/?probe=42d7df651d) | Jul 17, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [9fd4b3dd50](https://linux-hardware.org/?probe=9fd4b3dd50) | Jul 17, 2022 |
| Lenovo        | ThinkPad P51s 20HB000URT    | [7f9c1a586d](https://linux-hardware.org/?probe=7f9c1a586d) | Jul 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [41fd0bf728](https://linux-hardware.org/?probe=41fd0bf728) | Jul 16, 2022 |
| Dell          | Vostro 3550                 | [9bd81d608a](https://linux-hardware.org/?probe=9bd81d608a) | Jul 15, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [e442e954fb](https://linux-hardware.org/?probe=e442e954fb) | Jul 15, 2022 |
| HP            | Unknown                     | [e4ccba30f8](https://linux-hardware.org/?probe=e4ccba30f8) | Jul 15, 2022 |
| GPU Compan... | GWTN156-9                   | [df5c4b480d](https://linux-hardware.org/?probe=df5c4b480d) | Jul 15, 2022 |
| Acer          | Aspire 7741                 | [c243e256b8](https://linux-hardware.org/?probe=c243e256b8) | Jul 14, 2022 |
| Acer          | Aspire 7741                 | [0578837b28](https://linux-hardware.org/?probe=0578837b28) | Jul 14, 2022 |
| Acer          | AOD257                      | [ba11099c7f](https://linux-hardware.org/?probe=ba11099c7f) | Jul 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [63c4a7a0bd](https://linux-hardware.org/?probe=63c4a7a0bd) | Jul 14, 2022 |
| HP            | Pavilion g4                 | [40067cace0](https://linux-hardware.org/?probe=40067cace0) | Jul 14, 2022 |
| HP            | Pavilion g4                 | [26859467e9](https://linux-hardware.org/?probe=26859467e9) | Jul 14, 2022 |
| Acer          | Aspire A315-23G             | [09f86c23ae](https://linux-hardware.org/?probe=09f86c23ae) | Jul 14, 2022 |
| Dell          | Latitude 5310               | [bc161b95e9](https://linux-hardware.org/?probe=bc161b95e9) | Jul 13, 2022 |
| HP            | Laptop 15-ef2xxx            | [77bf0433d1](https://linux-hardware.org/?probe=77bf0433d1) | Jul 13, 2022 |
| HP            | Laptop 15-ef2xxx            | [6b488ff0fd](https://linux-hardware.org/?probe=6b488ff0fd) | Jul 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [3a612ba2bd](https://linux-hardware.org/?probe=3a612ba2bd) | Jul 12, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | [8c160ae192](https://linux-hardware.org/?probe=8c160ae192) | Jul 12, 2022 |
| HP            | 250 G8 Notebook PC          | [17cdd0291e](https://linux-hardware.org/?probe=17cdd0291e) | Jul 12, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [7cab42adeb](https://linux-hardware.org/?probe=7cab42adeb) | Jul 12, 2022 |
| ASUSTek       | X541UJ                      | [1725714269](https://linux-hardware.org/?probe=1725714269) | Jul 11, 2022 |
| ASUSTek       | X541UJ                      | [cc10e6800a](https://linux-hardware.org/?probe=cc10e6800a) | Jul 11, 2022 |
| Dell          | Latitude 5510               | [5f1abb9d12](https://linux-hardware.org/?probe=5f1abb9d12) | Jul 11, 2022 |
| Lenovo        | ThinkPad T490 20N3SEYA00    | [3370fd5142](https://linux-hardware.org/?probe=3370fd5142) | Jul 11, 2022 |
| HP            | Pavilion g4                 | [96ba266748](https://linux-hardware.org/?probe=96ba266748) | Jul 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [7cfc308ed6](https://linux-hardware.org/?probe=7cfc308ed6) | Jul 10, 2022 |
| Acer          | Aspire A315-23G             | [a2ef844aef](https://linux-hardware.org/?probe=a2ef844aef) | Jul 10, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [6f45ac99b1](https://linux-hardware.org/?probe=6f45ac99b1) | Jul 08, 2022 |
| Acer          | Aspire A715-75G             | [4a6cc98dd6](https://linux-hardware.org/?probe=4a6cc98dd6) | Jul 08, 2022 |
| Dell          | Latitude D620               | [70be0d553e](https://linux-hardware.org/?probe=70be0d553e) | Jul 08, 2022 |
| Google        | Terra                       | [7623f51d7a](https://linux-hardware.org/?probe=7623f51d7a) | Jul 08, 2022 |
| HUAWEI        | BOD-WXX9                    | [f4d2c6bb1e](https://linux-hardware.org/?probe=f4d2c6bb1e) | Jul 08, 2022 |
| AZW           | T3 MRD                      | [7f8d8245e1](https://linux-hardware.org/?probe=7f8d8245e1) | Jul 08, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6a78826e86](https://linux-hardware.org/?probe=6a78826e86) | Jul 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [f4a2814329](https://linux-hardware.org/?probe=f4a2814329) | Jul 07, 2022 |
| Dell          | Latitude 5285               | [1faeae7b00](https://linux-hardware.org/?probe=1faeae7b00) | Jul 07, 2022 |
| HP            | Laptop 15-bw0xx             | [c5cc2b52bb](https://linux-hardware.org/?probe=c5cc2b52bb) | Jul 07, 2022 |
| Dell          | Vostro 15 3510              | [bb44d4f6ba](https://linux-hardware.org/?probe=bb44d4f6ba) | Jul 07, 2022 |
| Google        | Enguarde                    | [bd97b057e3](https://linux-hardware.org/?probe=bd97b057e3) | Jul 06, 2022 |
| Google        | Peppy                       | [fe053f74c7](https://linux-hardware.org/?probe=fe053f74c7) | Jul 06, 2022 |
| Google        | Coral                       | [47442944de](https://linux-hardware.org/?probe=47442944de) | Jul 06, 2022 |
| HP            | EliteBook 2530p             | [a4b4609db8](https://linux-hardware.org/?probe=a4b4609db8) | Jul 05, 2022 |
| ASUSTek       | G55VW                       | [fa0346f5df](https://linux-hardware.org/?probe=fa0346f5df) | Jul 05, 2022 |
| ASUSTek       | G55VW                       | [832ca8cf45](https://linux-hardware.org/?probe=832ca8cf45) | Jul 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | [422a12c217](https://linux-hardware.org/?probe=422a12c217) | Jul 05, 2022 |
| Dell          | Latitude 5421               | [8a40be5ce5](https://linux-hardware.org/?probe=8a40be5ce5) | Jul 05, 2022 |
| Unknown       | Unknown                     | [78e8133c88](https://linux-hardware.org/?probe=78e8133c88) | Jul 03, 2022 |
| Dell          | Vostro 3549                 | [d23ff685fc](https://linux-hardware.org/?probe=d23ff685fc) | Jul 03, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [75f07cbe46](https://linux-hardware.org/?probe=75f07cbe46) | Jul 02, 2022 |
| Acer          | Nitro AN517-52              | [3920a80387](https://linux-hardware.org/?probe=3920a80387) | Jul 02, 2022 |
| Unknown       | Unknown                     | [72833df63f](https://linux-hardware.org/?probe=72833df63f) | Jul 02, 2022 |
| Acer          | Nitro AN517-52              | [37fbd3a600](https://linux-hardware.org/?probe=37fbd3a600) | Jul 02, 2022 |
| Acer          | Aspire A315-23G             | [6fc80d8654](https://linux-hardware.org/?probe=6fc80d8654) | Jul 02, 2022 |
| Dell          | Vostro 3550                 | [d68e2660b7](https://linux-hardware.org/?probe=d68e2660b7) | Jul 02, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [9b8bb07ff0](https://linux-hardware.org/?probe=9b8bb07ff0) | Jul 01, 2022 |
| ASUSTek       | X756UQK                     | [62595fe324](https://linux-hardware.org/?probe=62595fe324) | Jul 01, 2022 |
| Sony          | VPCEH37FJ                   | [509fe56362](https://linux-hardware.org/?probe=509fe56362) | Jul 01, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [75b3bd3b8c](https://linux-hardware.org/?probe=75b3bd3b8c) | Jun 30, 2022 |
| Acer          | Aspire V3-571G              | [e5283c0142](https://linux-hardware.org/?probe=e5283c0142) | Jun 30, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [980925115f](https://linux-hardware.org/?probe=980925115f) | Jun 30, 2022 |
| Acer          | Aspire V3-571G              | [5e795f7aa1](https://linux-hardware.org/?probe=5e795f7aa1) | Jun 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3a423eae14](https://linux-hardware.org/?probe=3a423eae14) | Jun 30, 2022 |
| Acer          | Aspire A315-23G             | [f5ca75e65b](https://linux-hardware.org/?probe=f5ca75e65b) | Jun 30, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [91c5f849c5](https://linux-hardware.org/?probe=91c5f849c5) | Jun 29, 2022 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [4b2106c800](https://linux-hardware.org/?probe=4b2106c800) | Jun 29, 2022 |
| Dell          | Latitude D610               | [0d55e1e388](https://linux-hardware.org/?probe=0d55e1e388) | Jun 29, 2022 |
| Lenovo        | ThinkPad X230 2325AEG       | [eaa3a2096e](https://linux-hardware.org/?probe=eaa3a2096e) | Jun 29, 2022 |
| Dell          | Latitude 5430               | [119502eddb](https://linux-hardware.org/?probe=119502eddb) | Jun 29, 2022 |
| HP            | EliteBook 840 G3            | [d7282a0f61](https://linux-hardware.org/?probe=d7282a0f61) | Jun 29, 2022 |
| HP            | EliteBook 840 G3            | [e4dd9b130e](https://linux-hardware.org/?probe=e4dd9b130e) | Jun 29, 2022 |
| ASUSTek       | G752VT                      | [d51730ccbf](https://linux-hardware.org/?probe=d51730ccbf) | Jun 29, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [c4dea8fa5d](https://linux-hardware.org/?probe=c4dea8fa5d) | Jun 28, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | [01fbfc98f8](https://linux-hardware.org/?probe=01fbfc98f8) | Jun 27, 2022 |
| BenQ          | Joybook Lite U102           | [49bbad20bd](https://linux-hardware.org/?probe=49bbad20bd) | Jun 27, 2022 |
| Dell          | Vostro 3550                 | [5c998424fb](https://linux-hardware.org/?probe=5c998424fb) | Jun 27, 2022 |
| HP            | EliteBook 840 G1            | [a1bfc8261f](https://linux-hardware.org/?probe=a1bfc8261f) | Jun 27, 2022 |
| Lenovo        | ThinkPad T470 20HES07J00    | [4be29eb5f1](https://linux-hardware.org/?probe=4be29eb5f1) | Jun 27, 2022 |
| HP            | ProBook 440 G0              | [4dbdbb04d3](https://linux-hardware.org/?probe=4dbdbb04d3) | Jun 27, 2022 |
| Aquarius      | NS585                       | [fd6aad4d1b](https://linux-hardware.org/?probe=fd6aad4d1b) | Jun 27, 2022 |
| Aquarius      | NS585                       | [107a5ae472](https://linux-hardware.org/?probe=107a5ae472) | Jun 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | [b947b14fe4](https://linux-hardware.org/?probe=b947b14fe4) | Jun 27, 2022 |
| Dell          | Latitude E6520              | [3cbcb5e5d5](https://linux-hardware.org/?probe=3cbcb5e5d5) | Jun 26, 2022 |
| Dell          | Inspiron 5502               | [c3e90d4ebd](https://linux-hardware.org/?probe=c3e90d4ebd) | Jun 26, 2022 |
| Acer          | Aspire A114-31              | [8fd4467dfd](https://linux-hardware.org/?probe=8fd4467dfd) | Jun 25, 2022 |
| Dell          | Latitude E6520              | [e4aeec08da](https://linux-hardware.org/?probe=e4aeec08da) | Jun 25, 2022 |
| Lenovo        | Edge 15 80K9                | [9399fd58cc](https://linux-hardware.org/?probe=9399fd58cc) | Jun 25, 2022 |
| Medion        | E16402                      | [1e16a44daa](https://linux-hardware.org/?probe=1e16a44daa) | Jun 25, 2022 |
| Dell          | Latitude E6330              | [969981b8cb](https://linux-hardware.org/?probe=969981b8cb) | Jun 25, 2022 |
| Lenovo        | ThinkPad T61 7659CA1        | [adce1c6762](https://linux-hardware.org/?probe=adce1c6762) | Jun 25, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [ba9c4d7141](https://linux-hardware.org/?probe=ba9c4d7141) | Jun 25, 2022 |
| ASUSTek       | X751LK                      | [e864b5e674](https://linux-hardware.org/?probe=e864b5e674) | Jun 24, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [eaf51fc79f](https://linux-hardware.org/?probe=eaf51fc79f) | Jun 24, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d742e624c6](https://linux-hardware.org/?probe=d742e624c6) | Jun 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [8df3dc4de2](https://linux-hardware.org/?probe=8df3dc4de2) | Jun 23, 2022 |
| Aquarius      | NS585                       | [1e0b20db82](https://linux-hardware.org/?probe=1e0b20db82) | Jun 23, 2022 |
| Dell          | Latitude 5490               | [f0726860d4](https://linux-hardware.org/?probe=f0726860d4) | Jun 23, 2022 |
| Dell          | Precision 7560              | [760bb908b9](https://linux-hardware.org/?probe=760bb908b9) | Jun 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [a2a6f48fe2](https://linux-hardware.org/?probe=a2a6f48fe2) | Jun 22, 2022 |
| Dell          | Latitude E6440              | [ea3bfb384f](https://linux-hardware.org/?probe=ea3bfb384f) | Jun 22, 2022 |
| HP            | 255 G3                      | [def96ad707](https://linux-hardware.org/?probe=def96ad707) | Jun 21, 2022 |
| Dell          | G15 5510                    | [cfd6e8f4d6](https://linux-hardware.org/?probe=cfd6e8f4d6) | Jun 21, 2022 |
| Fujitsu       | LIFEBOOK E744               | [093dfd12e4](https://linux-hardware.org/?probe=093dfd12e4) | Jun 21, 2022 |
| Fujitsu       | LIFEBOOK E744               | [b741aac903](https://linux-hardware.org/?probe=b741aac903) | Jun 21, 2022 |
| HP            | 250 G6 Notebook PC          | [30d0a46d81](https://linux-hardware.org/?probe=30d0a46d81) | Jun 21, 2022 |
| Acer          | Nitro AN515-55              | [b3b8a4d0c8](https://linux-hardware.org/?probe=b3b8a4d0c8) | Jun 21, 2022 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [bd4de35624](https://linux-hardware.org/?probe=bd4de35624) | Jun 20, 2022 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [9dd9dbdaa4](https://linux-hardware.org/?probe=9dd9dbdaa4) | Jun 20, 2022 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [0483d0dd9e](https://linux-hardware.org/?probe=0483d0dd9e) | Jun 20, 2022 |
| ASUSTek       | X556UQK                     | [6ce6e1d459](https://linux-hardware.org/?probe=6ce6e1d459) | Jun 20, 2022 |
| Samsung       | 935XDB                      | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f013ebb91b](https://linux-hardware.org/?probe=f013ebb91b) | Jun 20, 2022 |
| Aquarius      | NS585                       | [b08de59180](https://linux-hardware.org/?probe=b08de59180) | Jun 20, 2022 |
| Aquarius      | NS585                       | [28e0ced692](https://linux-hardware.org/?probe=28e0ced692) | Jun 20, 2022 |
| Aquarius      | NS585                       | [446cb710dc](https://linux-hardware.org/?probe=446cb710dc) | Jun 20, 2022 |
| Lenovo        | ThinkPad T470 20HD000EUK    | [6cc2ca4099](https://linux-hardware.org/?probe=6cc2ca4099) | Jun 19, 2022 |
| Acer          | Aspire V5-571               | [694dbcacc1](https://linux-hardware.org/?probe=694dbcacc1) | Jun 19, 2022 |
| Dell          | Inspiron 7370               | [e8a53b7f1b](https://linux-hardware.org/?probe=e8a53b7f1b) | Jun 18, 2022 |
| Acer          | Aspire A315-23G             | [2ec41b35a4](https://linux-hardware.org/?probe=2ec41b35a4) | Jun 18, 2022 |
| ASUSTek       | S550CM                      | [43ddcf21fb](https://linux-hardware.org/?probe=43ddcf21fb) | Jun 17, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [8d56f09226](https://linux-hardware.org/?probe=8d56f09226) | Jun 17, 2022 |
| Acer          | Nitro AN515-51              | [51caf7f2a3](https://linux-hardware.org/?probe=51caf7f2a3) | Jun 16, 2022 |
| Aquarius      | NS585                       | [e569242ae1](https://linux-hardware.org/?probe=e569242ae1) | Jun 16, 2022 |
| Aquarius      | NS585                       | [955b8f0fb2](https://linux-hardware.org/?probe=955b8f0fb2) | Jun 16, 2022 |
| Aquarius      | NS585                       | [815d2fd86a](https://linux-hardware.org/?probe=815d2fd86a) | Jun 16, 2022 |
| Aquarius      | NS585                       | [95b4800d70](https://linux-hardware.org/?probe=95b4800d70) | Jun 16, 2022 |
| Aquarius      | NS585                       | [944dcbf099](https://linux-hardware.org/?probe=944dcbf099) | Jun 16, 2022 |
| HUAWEI        | KLVD-WXX9                   | [4c97b8cc3a](https://linux-hardware.org/?probe=4c97b8cc3a) | Jun 16, 2022 |
| HP            | Stream Laptop 11-y0XX       | [5a762627ab](https://linux-hardware.org/?probe=5a762627ab) | Jun 16, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [b61e91e363](https://linux-hardware.org/?probe=b61e91e363) | Jun 15, 2022 |
| Aquarius      | NS585                       | [bf740af11c](https://linux-hardware.org/?probe=bf740af11c) | Jun 15, 2022 |
| Aquarius      | NS585                       | [e2906f745c](https://linux-hardware.org/?probe=e2906f745c) | Jun 15, 2022 |
| Aquarius      | NS585                       | [ced17caa07](https://linux-hardware.org/?probe=ced17caa07) | Jun 15, 2022 |
| Aquarius      | NS585                       | [08614740a5](https://linux-hardware.org/?probe=08614740a5) | Jun 15, 2022 |
| Aquarius      | NS585                       | [ba7a3660fb](https://linux-hardware.org/?probe=ba7a3660fb) | Jun 15, 2022 |
| Aquarius      | NS585                       | [a2cfae14e3](https://linux-hardware.org/?probe=a2cfae14e3) | Jun 15, 2022 |
| Aquarius      | NS585                       | [ea1cdaa121](https://linux-hardware.org/?probe=ea1cdaa121) | Jun 15, 2022 |
| Aquarius      | NS585                       | [358e315ac6](https://linux-hardware.org/?probe=358e315ac6) | Jun 15, 2022 |
| Aquarius      | NS585                       | [906c1b911b](https://linux-hardware.org/?probe=906c1b911b) | Jun 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ce37872e58](https://linux-hardware.org/?probe=ce37872e58) | Jun 15, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [60969fcd9a](https://linux-hardware.org/?probe=60969fcd9a) | Jun 15, 2022 |
| Google        | Celes                       | [7f6beef1e7](https://linux-hardware.org/?probe=7f6beef1e7) | Jun 15, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [8f42361336](https://linux-hardware.org/?probe=8f42361336) | Jun 14, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [e06841340d](https://linux-hardware.org/?probe=e06841340d) | Jun 14, 2022 |
| Acer          | Aspire A315-23G             | [b7223cfa1f](https://linux-hardware.org/?probe=b7223cfa1f) | Jun 14, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [67dece9099](https://linux-hardware.org/?probe=67dece9099) | Jun 13, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [0da40dea6c](https://linux-hardware.org/?probe=0da40dea6c) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [537b26aaf0](https://linux-hardware.org/?probe=537b26aaf0) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | [f7d3ee91c6](https://linux-hardware.org/?probe=f7d3ee91c6) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | [4347d50981](https://linux-hardware.org/?probe=4347d50981) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [ca2c0e822c](https://linux-hardware.org/?probe=ca2c0e822c) | Jun 11, 2022 |
| Acer          | Aspire T5000                | [38e164657d](https://linux-hardware.org/?probe=38e164657d) | Jun 11, 2022 |
| HP            | EliteBook 840 G6            | [f2351bb361](https://linux-hardware.org/?probe=f2351bb361) | Jun 11, 2022 |
| ASUSTek       | N550JK                      | [2c4116c1eb](https://linux-hardware.org/?probe=2c4116c1eb) | Jun 10, 2022 |
| Aquarius      | NS585                       | [bec14fe850](https://linux-hardware.org/?probe=bec14fe850) | Jun 10, 2022 |
| Dell          | Latitude 5310               | [fe0ffed6e4](https://linux-hardware.org/?probe=fe0ffed6e4) | Jun 10, 2022 |
| Dell          | Latitude E6410              | [6e26870ebe](https://linux-hardware.org/?probe=6e26870ebe) | Jun 10, 2022 |
| HP            | 240 G7                      | [bf52288eb2](https://linux-hardware.org/?probe=bf52288eb2) | Jun 10, 2022 |
| HUAWEI        | NBD-WXX9                    | [b8e097f983](https://linux-hardware.org/?probe=b8e097f983) | Jun 10, 2022 |
| Lenovo        | IdeaPad 5-15IIL05 81YK      | [b194866bb7](https://linux-hardware.org/?probe=b194866bb7) | Jun 10, 2022 |
| ASUSTek       | X541UAK                     | [111ebf5004](https://linux-hardware.org/?probe=111ebf5004) | Jun 09, 2022 |
| HP            | Pavilion 17                 | [f4afc30981](https://linux-hardware.org/?probe=f4afc30981) | Jun 09, 2022 |
| Acer          | Aspire R5-471T              | [d621ad4f4a](https://linux-hardware.org/?probe=d621ad4f4a) | Jun 09, 2022 |
| Aquarius      | NS585                       | [43bdbb4f7c](https://linux-hardware.org/?probe=43bdbb4f7c) | Jun 09, 2022 |
| Fujitsu       | LIFEBOOK E752               | [6047335005](https://linux-hardware.org/?probe=6047335005) | Jun 09, 2022 |
| ASUSTek       | X541UAK                     | [6903499468](https://linux-hardware.org/?probe=6903499468) | Jun 08, 2022 |
| Aquarius      | NS585                       | [5b578cce47](https://linux-hardware.org/?probe=5b578cce47) | Jun 08, 2022 |
| Aquarius      | NS585                       | [c621cccd03](https://linux-hardware.org/?probe=c621cccd03) | Jun 08, 2022 |
| Aquarius      | NS585                       | [901fd6aaa4](https://linux-hardware.org/?probe=901fd6aaa4) | Jun 08, 2022 |
| HP            | Pavilion 15                 | [08a042a74a](https://linux-hardware.org/?probe=08a042a74a) | Jun 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| ASUSTek       | G752VT                      | [bb5bb68126](https://linux-hardware.org/?probe=bb5bb68126) | Jun 08, 2022 |
| SANTECH       | NHx0DB,DE                   | [17b16800ba](https://linux-hardware.org/?probe=17b16800ba) | Jun 08, 2022 |
| Dell          | Vostro 15 3510              | [471dc7f2db](https://linux-hardware.org/?probe=471dc7f2db) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [ea589a3279](https://linux-hardware.org/?probe=ea589a3279) | Jun 07, 2022 |
| Flipkart I... | NKi510TL85S                 | [6e1326c27f](https://linux-hardware.org/?probe=6e1326c27f) | Jun 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [b2f7663fc9](https://linux-hardware.org/?probe=b2f7663fc9) | Jun 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [39bb0fa0c5](https://linux-hardware.org/?probe=39bb0fa0c5) | Jun 07, 2022 |
| Apple         | MacBookPro11,4              | [d6662c5acf](https://linux-hardware.org/?probe=d6662c5acf) | Jun 07, 2022 |
| Toshiba       | Satellite L850              | [809d0bbd73](https://linux-hardware.org/?probe=809d0bbd73) | Jun 07, 2022 |
| Toshiba       | Satellite L850              | [761d37bd31](https://linux-hardware.org/?probe=761d37bd31) | Jun 06, 2022 |
| Aquarius      | NS585                       | [7325c6d9c0](https://linux-hardware.org/?probe=7325c6d9c0) | Jun 06, 2022 |
| Aquarius      | NS585                       | [b2905bee15](https://linux-hardware.org/?probe=b2905bee15) | Jun 06, 2022 |
| Insyde        | GeminiLake                  | [4f2f6240b1](https://linux-hardware.org/?probe=4f2f6240b1) | Jun 06, 2022 |
| Insyde        | GeminiLake                  | [1c308cac35](https://linux-hardware.org/?probe=1c308cac35) | Jun 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [721f0da2de](https://linux-hardware.org/?probe=721f0da2de) | Jun 05, 2022 |
| Dell          | Latitude E6400              | [e4f54892c2](https://linux-hardware.org/?probe=e4f54892c2) | Jun 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f3bdd4cf82](https://linux-hardware.org/?probe=f3bdd4cf82) | Jun 05, 2022 |
| HP            | 250 G7 Notebook PC          | [ab5f939022](https://linux-hardware.org/?probe=ab5f939022) | Jun 04, 2022 |
| HP            | 250 G7 Notebook PC          | [f2ad368041](https://linux-hardware.org/?probe=f2ad368041) | Jun 04, 2022 |
| HP            | 250 G7 Notebook PC          | [1053e6f6d2](https://linux-hardware.org/?probe=1053e6f6d2) | Jun 04, 2022 |
| Dell          | Vostro 3480                 | [31825ebb84](https://linux-hardware.org/?probe=31825ebb84) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [eaad038fde](https://linux-hardware.org/?probe=eaad038fde) | Jun 03, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9533388943](https://linux-hardware.org/?probe=9533388943) | Jun 03, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [2b704f7e81](https://linux-hardware.org/?probe=2b704f7e81) | Jun 03, 2022 |
| Aquarius      | NS585                       | [1747344540](https://linux-hardware.org/?probe=1747344540) | Jun 03, 2022 |
| Aquarius      | NS585                       | [1cf86cb83b](https://linux-hardware.org/?probe=1cf86cb83b) | Jun 03, 2022 |
| Aquarius      | NS585                       | [27744ecba9](https://linux-hardware.org/?probe=27744ecba9) | Jun 03, 2022 |
| Acer          | Aspire A315-23G             | [7b3b8ff142](https://linux-hardware.org/?probe=7b3b8ff142) | Jun 03, 2022 |
| Acer          | Aspire A315-23G             | [cfb73d2727](https://linux-hardware.org/?probe=cfb73d2727) | Jun 02, 2022 |
| Apple         | MacBookPro11,1              | [b12802bc7a](https://linux-hardware.org/?probe=b12802bc7a) | Jun 02, 2022 |
| HP            | 250 G6 Notebook PC          | [878274dbce](https://linux-hardware.org/?probe=878274dbce) | Jun 02, 2022 |
| HP            | Pavilion g6                 | [7840b394d3](https://linux-hardware.org/?probe=7840b394d3) | Jun 02, 2022 |
| TEKNOSERVI... | PORTATIL TTL 14             | [7af14493e8](https://linux-hardware.org/?probe=7af14493e8) | Jun 01, 2022 |
| HP            | Pavilion g4                 | [321300f927](https://linux-hardware.org/?probe=321300f927) | Jun 01, 2022 |
| Lenovo        | ThinkPad T440s 20AQ008FU... | [3b5255ec2c](https://linux-hardware.org/?probe=3b5255ec2c) | Jun 01, 2022 |
| Dell          | Latitude E6400              | [85d314bfd8](https://linux-hardware.org/?probe=85d314bfd8) | May 31, 2022 |
| Aquarius      | NS585                       | [44bd30c95d](https://linux-hardware.org/?probe=44bd30c95d) | May 31, 2022 |
| Aquarius      | NS585                       | [2a7545f0f9](https://linux-hardware.org/?probe=2a7545f0f9) | May 31, 2022 |
| Aquarius      | NS585                       | [12e45f7665](https://linux-hardware.org/?probe=12e45f7665) | May 31, 2022 |
| Aquarius      | NS585                       | [c420e4cafb](https://linux-hardware.org/?probe=c420e4cafb) | May 31, 2022 |
| Aquarius      | NS585                       | [e562931a35](https://linux-hardware.org/?probe=e562931a35) | May 31, 2022 |
| Aquarius      | NS585                       | [26a3362040](https://linux-hardware.org/?probe=26a3362040) | May 31, 2022 |
| Aquarius      | NS585                       | [51595712dd](https://linux-hardware.org/?probe=51595712dd) | May 31, 2022 |
| Aquarius      | NS585                       | [0d31fa737e](https://linux-hardware.org/?probe=0d31fa737e) | May 31, 2022 |
| Aquarius      | NS585                       | [6e5a613444](https://linux-hardware.org/?probe=6e5a613444) | May 31, 2022 |
| Aquarius      | NS585                       | [7744e6a785](https://linux-hardware.org/?probe=7744e6a785) | May 31, 2022 |
| Aquarius      | NS585                       | [828c791c7c](https://linux-hardware.org/?probe=828c791c7c) | May 31, 2022 |
| Aquarius      | NS585                       | [ff8ca3e68b](https://linux-hardware.org/?probe=ff8ca3e68b) | May 31, 2022 |
| Aquarius      | NS585                       | [dbbe2e1b71](https://linux-hardware.org/?probe=dbbe2e1b71) | May 31, 2022 |
| Aquarius      | NS585                       | [099918e5b2](https://linux-hardware.org/?probe=099918e5b2) | May 31, 2022 |
| Aquarius      | NS585                       | [bdcf61dc44](https://linux-hardware.org/?probe=bdcf61dc44) | May 31, 2022 |
| Aquarius      | NS585                       | [3693e77fee](https://linux-hardware.org/?probe=3693e77fee) | May 31, 2022 |
| Aquarius      | NS585                       | [e41a23ba31](https://linux-hardware.org/?probe=e41a23ba31) | May 31, 2022 |
| Aquarius      | NS585                       | [a8aa698844](https://linux-hardware.org/?probe=a8aa698844) | May 31, 2022 |
| Dell          | Latitude E6400              | [f5ae9fef9c](https://linux-hardware.org/?probe=f5ae9fef9c) | May 31, 2022 |
| Aquarius      | NS585                       | [f0c6dbeb87](https://linux-hardware.org/?probe=f0c6dbeb87) | May 31, 2022 |
| Aquarius      | NS585                       | [ff453a32b6](https://linux-hardware.org/?probe=ff453a32b6) | May 31, 2022 |
| Aquarius      | NS585                       | [1ed72b7951](https://linux-hardware.org/?probe=1ed72b7951) | May 31, 2022 |
| Aquarius      | NS585                       | [222ff0011e](https://linux-hardware.org/?probe=222ff0011e) | May 31, 2022 |
| Acer          | Aspire T5000                | [55aaebdab5](https://linux-hardware.org/?probe=55aaebdab5) | May 31, 2022 |
| Acer          | Aspire T5000                | [7bdeb5fb3b](https://linux-hardware.org/?probe=7bdeb5fb3b) | May 31, 2022 |
| Alienware     | 15 R2                       | [776abe61ea](https://linux-hardware.org/?probe=776abe61ea) | May 31, 2022 |
| Acer          | Aspire E5-575G              | [7c44163245](https://linux-hardware.org/?probe=7c44163245) | May 31, 2022 |
| SANTECH       | NHx0DB,DE                   | [f3444e62bb](https://linux-hardware.org/?probe=f3444e62bb) | May 30, 2022 |
| SANTECH       | NHx0DB,DE                   | [4fbdcfe44b](https://linux-hardware.org/?probe=4fbdcfe44b) | May 30, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [883f055fb1](https://linux-hardware.org/?probe=883f055fb1) | May 30, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [e475b560cf](https://linux-hardware.org/?probe=e475b560cf) | May 30, 2022 |
| Notebook      | W65_67SJ                    | [2f6d77befb](https://linux-hardware.org/?probe=2f6d77befb) | May 29, 2022 |
| Lenovo        | ThinkPad W500 4061W8H       | [db9160e089](https://linux-hardware.org/?probe=db9160e089) | May 29, 2022 |
| Dell          | Vostro 3546                 | [3acd5d4cb0](https://linux-hardware.org/?probe=3acd5d4cb0) | May 28, 2022 |
| ASUSTek       | 900                         | [e50c30c38d](https://linux-hardware.org/?probe=e50c30c38d) | May 28, 2022 |
| ASUSTek       | 900                         | [dfd6af657c](https://linux-hardware.org/?probe=dfd6af657c) | May 28, 2022 |
| HP            | Notebook                    | [9900044e89](https://linux-hardware.org/?probe=9900044e89) | May 27, 2022 |
| HP            | 255 G8 Notebook PC          | [9430147fab](https://linux-hardware.org/?probe=9430147fab) | May 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d2581e2c05](https://linux-hardware.org/?probe=d2581e2c05) | May 27, 2022 |
| MSI           | Katana GF66 11UD            | [f3ee20f625](https://linux-hardware.org/?probe=f3ee20f625) | May 27, 2022 |
| HP            | Pavilion g6                 | [0e98027e39](https://linux-hardware.org/?probe=0e98027e39) | May 26, 2022 |
| ASUSTek       | K43E                        | [968007a0a9](https://linux-hardware.org/?probe=968007a0a9) | May 26, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [9ebff03a43](https://linux-hardware.org/?probe=9ebff03a43) | May 26, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [cc80808aea](https://linux-hardware.org/?probe=cc80808aea) | May 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [f5488ccb22](https://linux-hardware.org/?probe=f5488ccb22) | May 26, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [75063d8f18](https://linux-hardware.org/?probe=75063d8f18) | May 26, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [0d1ba4ee73](https://linux-hardware.org/?probe=0d1ba4ee73) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [86f00d534a](https://linux-hardware.org/?probe=86f00d534a) | May 26, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [0f450fb6e0](https://linux-hardware.org/?probe=0f450fb6e0) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [3929f17532](https://linux-hardware.org/?probe=3929f17532) | May 26, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [29b8def5b3](https://linux-hardware.org/?probe=29b8def5b3) | May 25, 2022 |
| Apple         | MacBookPro15,2              | [c0fe1740e0](https://linux-hardware.org/?probe=c0fe1740e0) | May 25, 2022 |
| Dell          | Latitude 5310               | [2117fbfccb](https://linux-hardware.org/?probe=2117fbfccb) | May 25, 2022 |
| Acer          | Aspire A315-23              | [dd46d19f05](https://linux-hardware.org/?probe=dd46d19f05) | May 25, 2022 |
| MSI           | GP62MVR 6RF                 | [1dd5741ea8](https://linux-hardware.org/?probe=1dd5741ea8) | May 25, 2022 |
| Dell          | Inspiron 3543               | [c48c32ae19](https://linux-hardware.org/?probe=c48c32ae19) | May 25, 2022 |
| Acer          | Nitro AN515-42              | [c755d907ca](https://linux-hardware.org/?probe=c755d907ca) | May 24, 2022 |
| Dell          | Latitude 5310               | [cb40714b3f](https://linux-hardware.org/?probe=cb40714b3f) | May 24, 2022 |
| Dell          | Latitude 5300               | [b2e8f91f15](https://linux-hardware.org/?probe=b2e8f91f15) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1d8684d1f5](https://linux-hardware.org/?probe=1d8684d1f5) | May 23, 2022 |
| Samsung       | SR70S/SR71S                 | [53642077bd](https://linux-hardware.org/?probe=53642077bd) | May 23, 2022 |
| Google        | Glimmer                     | [f16458e3ea](https://linux-hardware.org/?probe=f16458e3ea) | May 22, 2022 |
| LG Electro... | A410-G.BC48P1               | [fb2344f915](https://linux-hardware.org/?probe=fb2344f915) | May 22, 2022 |
| Dell          | Inspiron 1545               | [890010e793](https://linux-hardware.org/?probe=890010e793) | May 21, 2022 |
| ASUSTek       | 900                         | [082b51aa29](https://linux-hardware.org/?probe=082b51aa29) | May 21, 2022 |
| Lenovo        | ThinkPad E550 20DF002YUS    | [fe9f7989ef](https://linux-hardware.org/?probe=fe9f7989ef) | May 21, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c273310228](https://linux-hardware.org/?probe=c273310228) | May 20, 2022 |
| HP            | 250 G3                      | [463622ad88](https://linux-hardware.org/?probe=463622ad88) | May 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2972e28673](https://linux-hardware.org/?probe=2972e28673) | May 19, 2022 |
| Dell          | Latitude E4310              | [79cda1608c](https://linux-hardware.org/?probe=79cda1608c) | May 19, 2022 |
| System76      | Kudu                        | [78ce5e3b3e](https://linux-hardware.org/?probe=78ce5e3b3e) | May 19, 2022 |
| Acer          | Aspire 5750                 | [4c6bbffcae](https://linux-hardware.org/?probe=4c6bbffcae) | May 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [61e58bea6c](https://linux-hardware.org/?probe=61e58bea6c) | May 17, 2022 |
| HP            | ProBook 4720s               | [887ea9cd89](https://linux-hardware.org/?probe=887ea9cd89) | May 16, 2022 |
| Lenovo        | V145-15AST 81MT             | [486b786e45](https://linux-hardware.org/?probe=486b786e45) | May 16, 2022 |
| HP            | ProBook 4720s               | [09bb5a5088](https://linux-hardware.org/?probe=09bb5a5088) | May 16, 2022 |
| Dell          | Precision 3551              | [f134f92d00](https://linux-hardware.org/?probe=f134f92d00) | May 16, 2022 |
| ASUSTek       | X550LD                      | [75c6734097](https://linux-hardware.org/?probe=75c6734097) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [f0fef230c2](https://linux-hardware.org/?probe=f0fef230c2) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [2f0e46cc27](https://linux-hardware.org/?probe=2f0e46cc27) | May 15, 2022 |
| Lenovo        | ThinkPad X260 20F5S4C000    | [66fe039d1a](https://linux-hardware.org/?probe=66fe039d1a) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3f84f4220e](https://linux-hardware.org/?probe=3f84f4220e) | May 14, 2022 |
| Lenovo        | ThinkPad X260 20F5S4C000    | [96693754dd](https://linux-hardware.org/?probe=96693754dd) | May 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [d8cfc5384f](https://linux-hardware.org/?probe=d8cfc5384f) | May 13, 2022 |
| Dell          | System Inspiron N7110       | [f397801c5f](https://linux-hardware.org/?probe=f397801c5f) | May 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [8866f1fd7c](https://linux-hardware.org/?probe=8866f1fd7c) | May 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [76a04f4e4e](https://linux-hardware.org/?probe=76a04f4e4e) | May 13, 2022 |
| HP            | EliteBook 820 G1            | [dd51bb3592](https://linux-hardware.org/?probe=dd51bb3592) | May 12, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [8431edf013](https://linux-hardware.org/?probe=8431edf013) | May 12, 2022 |
| Acer          | Aspire 5750                 | [008e256981](https://linux-hardware.org/?probe=008e256981) | May 12, 2022 |
| HP            | Notebook                    | [3b4cd7fe5a](https://linux-hardware.org/?probe=3b4cd7fe5a) | May 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [53aed63d64](https://linux-hardware.org/?probe=53aed63d64) | May 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7d03983e37](https://linux-hardware.org/?probe=7d03983e37) | May 11, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| HP            | 250 G6 Notebook PC          | [f2f010a36d](https://linux-hardware.org/?probe=f2f010a36d) | May 11, 2022 |
| HP            | ENVY TS 17                  | [2423c94072](https://linux-hardware.org/?probe=2423c94072) | May 10, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | [3314cd39d7](https://linux-hardware.org/?probe=3314cd39d7) | May 10, 2022 |
| HP            | EliteBook 840 G3            | [9d0ee854e4](https://linux-hardware.org/?probe=9d0ee854e4) | May 10, 2022 |
| Acer          | Swift SF314-52              | [ee252c0c42](https://linux-hardware.org/?probe=ee252c0c42) | May 10, 2022 |
| Thirdwave     | DX-T7                       | [b90ec1bf3a](https://linux-hardware.org/?probe=b90ec1bf3a) | May 10, 2022 |
| Apple         | MacBook1,1                  | [399e291a66](https://linux-hardware.org/?probe=399e291a66) | May 09, 2022 |
| Acer          | Aspire 5750                 | [200ac122e9](https://linux-hardware.org/?probe=200ac122e9) | May 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [65ef6677b9](https://linux-hardware.org/?probe=65ef6677b9) | May 09, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [019117605e](https://linux-hardware.org/?probe=019117605e) | May 08, 2022 |
| Acer          | Aspire 5755G                | [634471ce19](https://linux-hardware.org/?probe=634471ce19) | May 08, 2022 |
| ASUSTek       | 900                         | [a4dc643c13](https://linux-hardware.org/?probe=a4dc643c13) | May 08, 2022 |
| Dell          | Inspiron 13-7378            | [7a8fd14c85](https://linux-hardware.org/?probe=7a8fd14c85) | May 08, 2022 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | [8fa9fd80a0](https://linux-hardware.org/?probe=8fa9fd80a0) | May 07, 2022 |
| SLIMBOOK      | Essential15L                | [1a244b5f4a](https://linux-hardware.org/?probe=1a244b5f4a) | May 07, 2022 |
| SLIMBOOK      | Essential15L                | [4f64e62082](https://linux-hardware.org/?probe=4f64e62082) | May 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [591d3fa922](https://linux-hardware.org/?probe=591d3fa922) | May 07, 2022 |
| Dell          | Latitude E6330              | [cbfc4e6f78](https://linux-hardware.org/?probe=cbfc4e6f78) | May 07, 2022 |
| Lenovo        | ThinkPad W540 20BG0011US    | [1679543d3d](https://linux-hardware.org/?probe=1679543d3d) | May 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS1U60... | [ffafca2b97](https://linux-hardware.org/?probe=ffafca2b97) | May 06, 2022 |
| Lenovo        | Z710 20250                  | [955a89377b](https://linux-hardware.org/?probe=955a89377b) | May 06, 2022 |
| ASUSTek       | UX430UAR                    | [6d471de246](https://linux-hardware.org/?probe=6d471de246) | May 05, 2022 |
| ASUSTek       | UX430UAR                    | [4aea04443a](https://linux-hardware.org/?probe=4aea04443a) | May 05, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [5cba3c93ba](https://linux-hardware.org/?probe=5cba3c93ba) | May 05, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [4208da52ad](https://linux-hardware.org/?probe=4208da52ad) | May 04, 2022 |
| HP            | Pavilion g7                 | [e213ff845c](https://linux-hardware.org/?probe=e213ff845c) | May 04, 2022 |
| Dell          | Latitude 5300               | [fa0246b764](https://linux-hardware.org/?probe=fa0246b764) | May 04, 2022 |
| Dell          | Latitude 3520               | [586dc3475e](https://linux-hardware.org/?probe=586dc3475e) | May 04, 2022 |
| HP            | ProBook 4330s               | [7cad0acb2c](https://linux-hardware.org/?probe=7cad0acb2c) | May 04, 2022 |
| HP            | ProBook 4330s               | [ca6474fbfc](https://linux-hardware.org/?probe=ca6474fbfc) | May 04, 2022 |
| Acer          | Aspire A315-23G             | [f749343aee](https://linux-hardware.org/?probe=f749343aee) | May 03, 2022 |
| ASUSTek       | E403SA                      | [c59815fc46](https://linux-hardware.org/?probe=c59815fc46) | May 02, 2022 |
| ASUSTek       | A6G                         | [a873db0112](https://linux-hardware.org/?probe=a873db0112) | May 02, 2022 |
| ASUSTek       | E403SA                      | [1036fd29cb](https://linux-hardware.org/?probe=1036fd29cb) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [20420f0426](https://linux-hardware.org/?probe=20420f0426) | May 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [414334d8e3](https://linux-hardware.org/?probe=414334d8e3) | May 01, 2022 |
| Acer          | Aspire E1-532               | [38d01733a6](https://linux-hardware.org/?probe=38d01733a6) | May 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [acdc37bb16](https://linux-hardware.org/?probe=acdc37bb16) | May 01, 2022 |
| Dell          | Precision M6500             | [a3d82a4f1a](https://linux-hardware.org/?probe=a3d82a4f1a) | Apr 30, 2022 |
| Dell          | Precision M6500             | [cb7e68eb50](https://linux-hardware.org/?probe=cb7e68eb50) | Apr 30, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [e14a2c047d](https://linux-hardware.org/?probe=e14a2c047d) | Apr 30, 2022 |
| HP            | Stream Notebook PC 13       | [f4eb2d351c](https://linux-hardware.org/?probe=f4eb2d351c) | Apr 30, 2022 |
| Dell          | Inspiron 15-3565            | [a26578c0fc](https://linux-hardware.org/?probe=a26578c0fc) | Apr 30, 2022 |
| Dell          | Inspiron N5050              | [7d3cb853e6](https://linux-hardware.org/?probe=7d3cb853e6) | Apr 29, 2022 |
| Google        | Enguarde                    | [878203f099](https://linux-hardware.org/?probe=878203f099) | Apr 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [df82c076b8](https://linux-hardware.org/?probe=df82c076b8) | Apr 29, 2022 |
| Google        | Enguarde                    | [194e2eb81b](https://linux-hardware.org/?probe=194e2eb81b) | Apr 28, 2022 |
| Acer          | Aspire A315-42G             | [03c0f64a6e](https://linux-hardware.org/?probe=03c0f64a6e) | Apr 28, 2022 |
| Google        | Enguarde                    | [37794c3d3a](https://linux-hardware.org/?probe=37794c3d3a) | Apr 28, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [f98b9b686e](https://linux-hardware.org/?probe=f98b9b686e) | Apr 28, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [674c8c1bf3](https://linux-hardware.org/?probe=674c8c1bf3) | Apr 28, 2022 |
| Dell          | Inspiron 15-3565            | [66d159169f](https://linux-hardware.org/?probe=66d159169f) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [73de8fd9f4](https://linux-hardware.org/?probe=73de8fd9f4) | Apr 26, 2022 |
| Dell          | XPS 17 9710                 | [c7dfc69b32](https://linux-hardware.org/?probe=c7dfc69b32) | Apr 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [5c309ec35d](https://linux-hardware.org/?probe=5c309ec35d) | Apr 26, 2022 |
| Intel         | Crestline & ICH8M Chipse... | [b410b890ef](https://linux-hardware.org/?probe=b410b890ef) | Apr 26, 2022 |
| Intel         | Crestline & ICH8M Chipse... | [4435386574](https://linux-hardware.org/?probe=4435386574) | Apr 26, 2022 |
| HP            | Notebook                    | [94f0ce7610](https://linux-hardware.org/?probe=94f0ce7610) | Apr 26, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [2d1a1334c6](https://linux-hardware.org/?probe=2d1a1334c6) | Apr 25, 2022 |
| Google        | Enguarde                    | [9b28418435](https://linux-hardware.org/?probe=9b28418435) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a33d02fb0e](https://linux-hardware.org/?probe=a33d02fb0e) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [710ddc650e](https://linux-hardware.org/?probe=710ddc650e) | Apr 25, 2022 |
| Dell          | Vostro 3405                 | [2d5bae0eeb](https://linux-hardware.org/?probe=2d5bae0eeb) | Apr 24, 2022 |
| ASUSTek       | S551LN                      | [779fe5a429](https://linux-hardware.org/?probe=779fe5a429) | Apr 24, 2022 |
| HP            | Laptop 15-bw0xx             | [e83ffcb04f](https://linux-hardware.org/?probe=e83ffcb04f) | Apr 24, 2022 |
| HP            | Laptop 15-bw0xx             | [25e6181500](https://linux-hardware.org/?probe=25e6181500) | Apr 24, 2022 |
| MSI           | GX700                       | [b2cc52d381](https://linux-hardware.org/?probe=b2cc52d381) | Apr 24, 2022 |
| ASUSTek       | K55A                        | [079c627411](https://linux-hardware.org/?probe=079c627411) | Apr 24, 2022 |
| Dell          | Inspiron 11-3168            | [79460e1288](https://linux-hardware.org/?probe=79460e1288) | Apr 24, 2022 |
| HP            | Laptop 17-bs0xx             | [8a4835680a](https://linux-hardware.org/?probe=8a4835680a) | Apr 24, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | [41276f12db](https://linux-hardware.org/?probe=41276f12db) | Apr 23, 2022 |
| Dell          | XPS 17 9700                 | [2d275ba888](https://linux-hardware.org/?probe=2d275ba888) | Apr 23, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | [55733b5ae3](https://linux-hardware.org/?probe=55733b5ae3) | Apr 23, 2022 |
| Dell          | Precision 3551              | [e1921eba79](https://linux-hardware.org/?probe=e1921eba79) | Apr 23, 2022 |
| HP            | Unknown                     | [0a47967da0](https://linux-hardware.org/?probe=0a47967da0) | Apr 23, 2022 |
| Dell          | Latitude 3120               | [632ba0bee8](https://linux-hardware.org/?probe=632ba0bee8) | Apr 23, 2022 |
| HP            | Unknown                     | [fa5bba3e33](https://linux-hardware.org/?probe=fa5bba3e33) | Apr 22, 2022 |
| Lenovo        | E31-70 80KX                 | [21f5bdfbc7](https://linux-hardware.org/?probe=21f5bdfbc7) | Apr 22, 2022 |
| Google        | Enguarde                    | [d23e0dd7ea](https://linux-hardware.org/?probe=d23e0dd7ea) | Apr 22, 2022 |
| Lenovo        | E31-70 80KX                 | [6910bac4f7](https://linux-hardware.org/?probe=6910bac4f7) | Apr 22, 2022 |
| ASUSTek       | K54HR                       | [9d42053630](https://linux-hardware.org/?probe=9d42053630) | Apr 22, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [0cd6fe25ec](https://linux-hardware.org/?probe=0cd6fe25ec) | Apr 22, 2022 |
| MSI           | GE60 2PC                    | [0614a4172b](https://linux-hardware.org/?probe=0614a4172b) | Apr 22, 2022 |
| ASUSTek       | K53E                        | [14e628cbba](https://linux-hardware.org/?probe=14e628cbba) | Apr 22, 2022 |
| ASUSTek       | UX31E                       | [ca406cf975](https://linux-hardware.org/?probe=ca406cf975) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | [32d9d8c8df](https://linux-hardware.org/?probe=32d9d8c8df) | Apr 21, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | [1a7a85a6ca](https://linux-hardware.org/?probe=1a7a85a6ca) | Apr 21, 2022 |
| HP            | Laptop 15s-fq2xxx           | [cba42e1765](https://linux-hardware.org/?probe=cba42e1765) | Apr 21, 2022 |
| Lenovo        | ThinkPad E580 20KS006EMZ    | [4d54c594ff](https://linux-hardware.org/?probe=4d54c594ff) | Apr 20, 2022 |
| Google        | Enguarde                    | [2bad463aa0](https://linux-hardware.org/?probe=2bad463aa0) | Apr 20, 2022 |
| Google        | Enguarde                    | [d39dbe919e](https://linux-hardware.org/?probe=d39dbe919e) | Apr 20, 2022 |
| Google        | Enguarde                    | [63afa83513](https://linux-hardware.org/?probe=63afa83513) | Apr 20, 2022 |
| Google        | Enguarde                    | [75c049c0a1](https://linux-hardware.org/?probe=75c049c0a1) | Apr 20, 2022 |
| Google        | Enguarde                    | [181bb3b047](https://linux-hardware.org/?probe=181bb3b047) | Apr 20, 2022 |
| Google        | Enguarde                    | [9b62ce9d7f](https://linux-hardware.org/?probe=9b62ce9d7f) | Apr 20, 2022 |
| Google        | Enguarde                    | [3e6dd7d3ee](https://linux-hardware.org/?probe=3e6dd7d3ee) | Apr 20, 2022 |
| Dell          | Latitude E6430              | [91bbf4068b](https://linux-hardware.org/?probe=91bbf4068b) | Apr 20, 2022 |
| Lenovo        | ThinkPad T400 64754B9       | [443f31afef](https://linux-hardware.org/?probe=443f31afef) | Apr 20, 2022 |
| Lenovo        | ThinkPad T400 64754B9       | [11ed3cef75](https://linux-hardware.org/?probe=11ed3cef75) | Apr 20, 2022 |
| Google        | Enguarde                    | [ad9cda8c65](https://linux-hardware.org/?probe=ad9cda8c65) | Apr 19, 2022 |
| Google        | Enguarde                    | [8a92222bf2](https://linux-hardware.org/?probe=8a92222bf2) | Apr 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ee565a2f35](https://linux-hardware.org/?probe=ee565a2f35) | Apr 19, 2022 |
| Dell          | Latitude E6230              | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Lenovo        | ThinkPad SL 2743X12         | [ad56efc5ff](https://linux-hardware.org/?probe=ad56efc5ff) | Apr 19, 2022 |
| Dell          | Latitude E6230              | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4047b55bcf](https://linux-hardware.org/?probe=4047b55bcf) | Apr 19, 2022 |
| ASUSTek       | 1101HA                      | [fc482cbbe1](https://linux-hardware.org/?probe=fc482cbbe1) | Apr 18, 2022 |
| Packard Be... | DOTM                        | [fc12f3ef5e](https://linux-hardware.org/?probe=fc12f3ef5e) | Apr 18, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [094918a3ca](https://linux-hardware.org/?probe=094918a3ca) | Apr 18, 2022 |
| Google        | Cave                        | [c762019e08](https://linux-hardware.org/?probe=c762019e08) | Apr 18, 2022 |
| Unknown       | Unknown                     | [cfd3bd53a8](https://linux-hardware.org/?probe=cfd3bd53a8) | Apr 18, 2022 |
| HP            | Laptop 14-dq4xxx            | [4d29f7d8eb](https://linux-hardware.org/?probe=4d29f7d8eb) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | [4058d0c1ca](https://linux-hardware.org/?probe=4058d0c1ca) | Apr 17, 2022 |
| Samsung       | RV415/RV515                 | [e2462a2328](https://linux-hardware.org/?probe=e2462a2328) | Apr 17, 2022 |
| Toshiba       | Satellite L50D-B            | [c5d02ba256](https://linux-hardware.org/?probe=c5d02ba256) | Apr 17, 2022 |
| HP            | EliteBook 830 G5            | [601cc73b24](https://linux-hardware.org/?probe=601cc73b24) | Apr 17, 2022 |
| Dell          | Inspiron 5555               | [9123d206b0](https://linux-hardware.org/?probe=9123d206b0) | Apr 16, 2022 |
| HP            | ENVY TS 17                  | [83c35e58d5](https://linux-hardware.org/?probe=83c35e58d5) | Apr 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c5e6eae8d7](https://linux-hardware.org/?probe=c5e6eae8d7) | Apr 16, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [fccfb454e4](https://linux-hardware.org/?probe=fccfb454e4) | Apr 16, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [ca0b0f6a8a](https://linux-hardware.org/?probe=ca0b0f6a8a) | Apr 16, 2022 |
| Thirdwave     | DX-T7                       | [b03707283b](https://linux-hardware.org/?probe=b03707283b) | Apr 16, 2022 |
| HP            | Pavilion dv5                | [22aa828b2f](https://linux-hardware.org/?probe=22aa828b2f) | Apr 16, 2022 |
| Google        | Enguarde                    | [6e1d5488f8](https://linux-hardware.org/?probe=6e1d5488f8) | Apr 15, 2022 |
| Toshiba       | Satellite L50D-B            | [912c61bb9b](https://linux-hardware.org/?probe=912c61bb9b) | Apr 15, 2022 |
| Google        | Enguarde                    | [7c4a4092d5](https://linux-hardware.org/?probe=7c4a4092d5) | Apr 15, 2022 |
| Google        | Enguarde                    | [26c2f26771](https://linux-hardware.org/?probe=26c2f26771) | Apr 15, 2022 |
| Google        | Enguarde                    | [f0ec477b78](https://linux-hardware.org/?probe=f0ec477b78) | Apr 15, 2022 |
| ASUSTek       | 1001PX                      | [520db05629](https://linux-hardware.org/?probe=520db05629) | Apr 15, 2022 |
| Acer          | TMP455-M                    | [451dbf0a20](https://linux-hardware.org/?probe=451dbf0a20) | Apr 15, 2022 |
| Acer          | TMP455-M                    | [b7b9924190](https://linux-hardware.org/?probe=b7b9924190) | Apr 15, 2022 |
| Lenovo        | ThinkPad T440 20B7S1970B    | [055812a1f1](https://linux-hardware.org/?probe=055812a1f1) | Apr 14, 2022 |
| Dell          | XPS L322X                   | [eee5065a27](https://linux-hardware.org/?probe=eee5065a27) | Apr 14, 2022 |
| Google        | Enguarde                    | [d8235b139b](https://linux-hardware.org/?probe=d8235b139b) | Apr 14, 2022 |
| Google        | Enguarde                    | [3f5020068f](https://linux-hardware.org/?probe=3f5020068f) | Apr 14, 2022 |
| HP            | Laptop 15-db0xxx            | [ffe2d9db36](https://linux-hardware.org/?probe=ffe2d9db36) | Apr 14, 2022 |
| Google        | Enguarde                    | [c54f344fdb](https://linux-hardware.org/?probe=c54f344fdb) | Apr 14, 2022 |
| HP            | ENVY 6                      | [deb09d7d7c](https://linux-hardware.org/?probe=deb09d7d7c) | Apr 14, 2022 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [799b4d2e08](https://linux-hardware.org/?probe=799b4d2e08) | Apr 14, 2022 |
| HP            | ENVY 6                      | [6cde3d35d8](https://linux-hardware.org/?probe=6cde3d35d8) | Apr 14, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [4838334e73](https://linux-hardware.org/?probe=4838334e73) | Apr 14, 2022 |
| Google        | Enguarde                    | [089fb5aac7](https://linux-hardware.org/?probe=089fb5aac7) | Apr 14, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [4b3cedca6f](https://linux-hardware.org/?probe=4b3cedca6f) | Apr 14, 2022 |
| Google        | Enguarde                    | [f0cbf88366](https://linux-hardware.org/?probe=f0cbf88366) | Apr 14, 2022 |
| Google        | Enguarde                    | [411f63de57](https://linux-hardware.org/?probe=411f63de57) | Apr 14, 2022 |
| Google        | Enguarde                    | [3fd74b2f86](https://linux-hardware.org/?probe=3fd74b2f86) | Apr 14, 2022 |
| Google        | Enguarde                    | [b06b81bc8f](https://linux-hardware.org/?probe=b06b81bc8f) | Apr 14, 2022 |
| Sony          | SVE1712S1EB                 | [546692479d](https://linux-hardware.org/?probe=546692479d) | Apr 14, 2022 |
| Lenovo        | ThinkPad X230 2306CTO       | [7a0b2570f3](https://linux-hardware.org/?probe=7a0b2570f3) | Apr 14, 2022 |
| Dell          | Latitude 3520               | [8003f0258a](https://linux-hardware.org/?probe=8003f0258a) | Apr 14, 2022 |
| Lenovo        | ThinkPad W510 4391DK3       | [d73ef83ae7](https://linux-hardware.org/?probe=d73ef83ae7) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [848f50a317](https://linux-hardware.org/?probe=848f50a317) | Apr 13, 2022 |
| Google        | Enguarde                    | [7accbcbfdb](https://linux-hardware.org/?probe=7accbcbfdb) | Apr 13, 2022 |
| Dell          | Inspiron 3521               | [b7043f3712](https://linux-hardware.org/?probe=b7043f3712) | Apr 13, 2022 |
| Toshiba       | TECRA X40-D                 | [d18cfd17bb](https://linux-hardware.org/?probe=d18cfd17bb) | Apr 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [080a434f1e](https://linux-hardware.org/?probe=080a434f1e) | Apr 13, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7f3347b13e](https://linux-hardware.org/?probe=7f3347b13e) | Apr 13, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [dbe88a4373](https://linux-hardware.org/?probe=dbe88a4373) | Apr 13, 2022 |
| Toshiba       | Satellite A300              | [1773d841d4](https://linux-hardware.org/?probe=1773d841d4) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [5584985b1e](https://linux-hardware.org/?probe=5584985b1e) | Apr 13, 2022 |
| Unknown       | Z37S                        | [25d5118843](https://linux-hardware.org/?probe=25d5118843) | Apr 13, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [0357e04d4f](https://linux-hardware.org/?probe=0357e04d4f) | Apr 13, 2022 |
| HP            | Compaq Mini CQ10-100        | [1acc227c33](https://linux-hardware.org/?probe=1acc227c33) | Apr 13, 2022 |
| Lenovo        | ThinkPad Z61m 94528QG       | [0da32925f1](https://linux-hardware.org/?probe=0da32925f1) | Apr 12, 2022 |
| Acer          | Swift SF314-54              | [c40cfcc7fe](https://linux-hardware.org/?probe=c40cfcc7fe) | Apr 12, 2022 |
| Lenovo        | ThinkPad E570 20H500B5IX    | [28ab9096ba](https://linux-hardware.org/?probe=28ab9096ba) | Apr 11, 2022 |
| HP            | EliteBook 840 G3            | [659999d04a](https://linux-hardware.org/?probe=659999d04a) | Apr 11, 2022 |
| Dell          | Latitude D400               | [46981d939b](https://linux-hardware.org/?probe=46981d939b) | Apr 11, 2022 |
| Intel         | powered classmate PC        | [39f9a3dcac](https://linux-hardware.org/?probe=39f9a3dcac) | Apr 11, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [8a0974e971](https://linux-hardware.org/?probe=8a0974e971) | Apr 10, 2022 |
| HP            | OMEN by Laptop              | [f83f7f076a](https://linux-hardware.org/?probe=f83f7f076a) | Apr 10, 2022 |
| HP            | Laptop 15-da1xxx            | [8d9c212045](https://linux-hardware.org/?probe=8d9c212045) | Apr 10, 2022 |
| Sony          | VGN-NR31ZR_S                | [aa9e4ae485](https://linux-hardware.org/?probe=aa9e4ae485) | Apr 09, 2022 |
| HP            | Laptop 15s-fq2xxx           | [a0001e2492](https://linux-hardware.org/?probe=a0001e2492) | Apr 09, 2022 |
| HP            | EliteBook 840 G3            | [227c3936b8](https://linux-hardware.org/?probe=227c3936b8) | Apr 09, 2022 |
| Advent        | Tacto Purple                | [5ad7851c7a](https://linux-hardware.org/?probe=5ad7851c7a) | Apr 09, 2022 |
| HP            | EliteBook 840 G3            | [a78a4e608e](https://linux-hardware.org/?probe=a78a4e608e) | Apr 09, 2022 |
| HP            | 250 G7 Notebook PC          | [6271f39c13](https://linux-hardware.org/?probe=6271f39c13) | Apr 08, 2022 |
| Acer          | Aspire 7720G                | [8cdee656da](https://linux-hardware.org/?probe=8cdee656da) | Apr 08, 2022 |
| Getac         | S400                        | [7f8a76a614](https://linux-hardware.org/?probe=7f8a76a614) | Apr 08, 2022 |
| Acer          | Aspire E5-553G              | [cdc96ed221](https://linux-hardware.org/?probe=cdc96ed221) | Apr 08, 2022 |
| HP            | ProBook 430 G1              | [8bcbe236a7](https://linux-hardware.org/?probe=8bcbe236a7) | Apr 07, 2022 |
| ASUSTek       | 1005HA                      | [6af126abbf](https://linux-hardware.org/?probe=6af126abbf) | Apr 07, 2022 |
| Lenovo        | ThinkPad L440 20ASS34K00    | [357d9151c6](https://linux-hardware.org/?probe=357d9151c6) | Apr 07, 2022 |
| Dell          | Vostro 5402                 | [6cb82accd9](https://linux-hardware.org/?probe=6cb82accd9) | Apr 07, 2022 |
| Clevo         | M1110M                      | [6094ad097f](https://linux-hardware.org/?probe=6094ad097f) | Apr 07, 2022 |
| HP            | Pavilion g6                 | [24ebf3af72](https://linux-hardware.org/?probe=24ebf3af72) | Apr 06, 2022 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | [4aaa2a3959](https://linux-hardware.org/?probe=4aaa2a3959) | Apr 06, 2022 |
| HP            | Laptop 14-df0xxx            | [11e5440dde](https://linux-hardware.org/?probe=11e5440dde) | Apr 06, 2022 |
| HP            | Laptop 14-df0xxx            | [509c236d89](https://linux-hardware.org/?probe=509c236d89) | Apr 06, 2022 |
| ASUSTek       | X756UQK                     | [136b45b510](https://linux-hardware.org/?probe=136b45b510) | Apr 06, 2022 |
| TrekStor      | Notebook Slim S130          | [e941163105](https://linux-hardware.org/?probe=e941163105) | Apr 06, 2022 |
| Dell          | Inspiron 5458               | [6caf8b778d](https://linux-hardware.org/?probe=6caf8b778d) | Apr 06, 2022 |
| Dell          | Inspiron 5458               | [d430c4bae4](https://linux-hardware.org/?probe=d430c4bae4) | Apr 06, 2022 |
| ASUSTek       | 1005HA                      | [93cd6f380c](https://linux-hardware.org/?probe=93cd6f380c) | Apr 05, 2022 |
| ASUSTek       | 1005HA                      | [aedb38f5de](https://linux-hardware.org/?probe=aedb38f5de) | Apr 05, 2022 |
| ASUSTek       | 1005HA                      | [95ffbe83e4](https://linux-hardware.org/?probe=95ffbe83e4) | Apr 05, 2022 |
| ASUSTek       | 1005HA                      | [13e25ee6db](https://linux-hardware.org/?probe=13e25ee6db) | Apr 05, 2022 |
| ASUSTek       | 1005HA                      | [f5f6f27478](https://linux-hardware.org/?probe=f5f6f27478) | Apr 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 578       | 23.19%  |
| 5.10.0-10-amd64        | 488       | 19.58%  |
| 5.10.0-9-amd64         | 169       | 6.78%   |
| 5.10.0-7-amd64         | 165       | 6.62%   |
| 5.10.0-16-amd64        | 153       | 6.14%   |
| 5.10.0-13-amd64        | 146       | 5.86%   |
| 5.10.0-11-amd64        | 102       | 4.09%   |
| 5.10.0-14-amd64        | 78        | 3.13%   |
| 5.10.0-17-amd64        | 70        | 2.81%   |
| 5.10.0-18-amd64        | 57        | 2.29%   |
| 5.10.0-15-amd64        | 44        | 1.77%   |
| 5.10.0-12-amd64        | 40        | 1.61%   |
| 5.10.0-6-amd64         | 28        | 1.12%   |
| 5.10.0-2-amd64         | 28        | 1.12%   |
| 5.10.0-13-686-pae      | 26        | 1.04%   |
| 5.14.0-0.bpo.2-amd64   | 16        | 0.64%   |
| 5.15.0-2-amd64         | 14        | 0.56%   |
| 5.10.0-3-amd64         | 13        | 0.52%   |
| 5.16.0-0.bpo.4-amd64   | 12        | 0.48%   |
| 5.18.0-0.bpo.1-amd64   | 9         | 0.36%   |
| 5.10.0-9-686-pae       | 9         | 0.36%   |
| 5.10.0-8-686-pae       | 9         | 0.36%   |
| 5.10.0-13-686          | 9         | 0.36%   |
| 5.15.0-0.bpo.2-amd64   | 8         | 0.32%   |
| 5.18.0-0.deb11.4-amd64 | 7         | 0.28%   |
| 5.10.0-9-686           | 7         | 0.28%   |
| 5.18.0-2-amd64         | 6         | 0.24%   |
| 5.19.0-1-amd64         | 5         | 0.2%    |
| 5.10.0-5-amd64         | 5         | 0.2%    |
| 5.10.0-4-amd64         | 5         | 0.2%    |
| 5.10.0-1-amd64         | 5         | 0.2%    |
| 5.17.0-1-amd64         | 4         | 0.16%   |
| 5.16.0-5-amd64         | 4         | 0.16%   |
| 5.16.0-3-amd64         | 4         | 0.16%   |
| 5.16.0-1-amd64         | 4         | 0.16%   |
| 5.15.0-1-amd64         | 4         | 0.16%   |
| 5.15.0-0.bpo.3-amd64   | 4         | 0.16%   |
| 5.10.0-8-686           | 4         | 0.16%   |
| 5.10.0-11-686-pae      | 4         | 0.16%   |
| 5.10.0-10-686-pae      | 4         | 0.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 2138      | 90.82%  |
| 5.15.0   | 36        | 1.53%   |
| 5.16.0   | 31        | 1.32%   |
| 5.18.0   | 27        | 1.15%   |
| 5.14.0   | 23        | 0.98%   |
| 5.17.0   | 12        | 0.51%   |
| 5.19.0   | 9         | 0.38%   |
| 4.19.0   | 7         | 0.3%    |
| 5.13.19  | 3         | 0.13%   |
| 5.12.0   | 3         | 0.13%   |
| 5.10.60  | 3         | 0.13%   |
| 5.17.5   | 2         | 0.08%   |
| 5.17.11  | 2         | 0.08%   |
| 5.15.35  | 2         | 0.08%   |
| 5.13.8   | 2         | 0.08%   |
| 5.11.0   | 2         | 0.08%   |
| 5.10.109 | 2         | 0.08%   |
| 4.9.0    | 2         | 0.08%   |
| 5.4.157  | 1         | 0.04%   |
| 5.19.9   | 1         | 0.04%   |
| 5.19.10  | 1         | 0.04%   |
| 5.19.1   | 1         | 0.04%   |
| 5.18.6   | 1         | 0.04%   |
| 5.18.15  | 1         | 0.04%   |
| 5.17.4   | 1         | 0.04%   |
| 5.17.14  | 1         | 0.04%   |
| 5.16.5   | 1         | 0.04%   |
| 5.15.8   | 1         | 0.04%   |
| 5.15.7   | 1         | 0.04%   |
| 5.15.6.1 | 1         | 0.04%   |
| 5.15.34  | 1         | 0.04%   |
| 5.15.32  | 1         | 0.04%   |
| 5.15.30  | 1         | 0.04%   |
| 5.15.3   | 1         | 0.04%   |
| 5.15.17  | 1         | 0.04%   |
| 5.15.13  | 1         | 0.04%   |
| 5.15.11  | 1         | 0.04%   |
| 5.14.9   | 1         | 0.04%   |
| 5.14.7   | 1         | 0.04%   |
| 5.14.6   | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2150      | 91.41%  |
| 5.15    | 46        | 1.96%   |
| 5.16    | 32        | 1.36%   |
| 5.18    | 29        | 1.23%   |
| 5.14    | 27        | 1.15%   |
| 5.17    | 18        | 0.77%   |
| 5.19    | 12        | 0.51%   |
| 5.13    | 9         | 0.38%   |
| 4.19    | 9         | 0.38%   |
| 5.12    | 6         | 0.26%   |
| 5.11    | 6         | 0.26%   |
| 5.1     | 2         | 0.09%   |
| 4.9     | 2         | 0.09%   |
| 5.4     | 1         | 0.04%   |
| 5.15.6  | 1         | 0.04%   |
| 3.8     | 1         | 0.04%   |
| 3.10    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2226      | 96.07%  |
| i686   | 89        | 3.84%   |
| armv7l | 2         | 0.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 911       | 38.82%  |
| GNOME            | 543       | 23.14%  |
| KDE5             | 264       | 11.25%  |
| XFCE             | 242       | 10.31%  |
| MATE             | 78        | 3.32%   |
| LXDE             | 56        | 2.39%   |
| X-Cinnamon       | 53        | 2.26%   |
| Cinnamon         | 51        | 2.17%   |
| i3               | 28        | 1.19%   |
| KDE              | 26        | 1.11%   |
| LXQt             | 25        | 1.07%   |
| GNOME Flashback  | 18        | 0.77%   |
| lightdm-xsession | 13        | 0.55%   |
| openbox          | 8         | 0.34%   |
| trinity          | 5         | 0.21%   |
| GNOME Classic    | 5         | 0.21%   |
| Cutefish         | 3         | 0.13%   |
| sway             | 2         | 0.09%   |
| ICEWM            | 2         | 0.09%   |
| Enlightenment    | 2         | 0.09%   |
| DWM              | 2         | 0.09%   |
| Budgie           | 2         | 0.09%   |
| awesome          | 2         | 0.09%   |
| xmonad           | 1         | 0.04%   |
| wmaker-common    | 1         | 0.04%   |
| matchbox         | 1         | 0.04%   |
| jwm              | 1         | 0.04%   |
| default          | 1         | 0.04%   |
| Deepin           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1007      | 42.91%  |
| Unknown | 856       | 36.47%  |
| Wayland | 420       | 17.9%   |
| Tty     | 64        | 2.73%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1174      | 50.11%  |
| GDM     | 460       | 19.63%  |
| LightDM | 346       | 14.77%  |
| SDDM    | 249       | 10.63%  |
| TDM     | 70        | 2.99%   |
| GDM3    | 37        | 1.58%   |
| XDM     | 3         | 0.13%   |
| SLiM    | 3         | 0.13%   |
| KDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 683       | 29.26%  |
| en_US   | 623       | 26.69%  |
| ru_RU   | 203       | 8.7%    |
| de_DE   | 114       | 4.88%   |
| fr_FR   | 98        | 4.2%    |
| en_GB   | 92        | 3.94%   |
| es_ES   | 80        | 3.43%   |
| pt_BR   | 50        | 2.14%   |
| pl_PL   | 46        | 1.97%   |
| it_IT   | 46        | 1.97%   |
| en_CA   | 23        | 0.99%   |
| es_MX   | 21        | 0.9%    |
| en_AU   | 21        | 0.9%    |
| en_IN   | 14        | 0.6%    |
| zh_CN   | 13        | 0.56%   |
| es_AR   | 11        | 0.47%   |
| C       | 11        | 0.47%   |
| hu_HU   | 10        | 0.43%   |
| es_CL   | 10        | 0.43%   |
| sv_SE   | 8         | 0.34%   |
| es_VE   | 8         | 0.34%   |
| en_IE   | 8         | 0.34%   |
| de_AT   | 8         | 0.34%   |
| nl_NL   | 7         | 0.3%    |
| ja_JP   | 7         | 0.3%    |
| fi_FI   | 7         | 0.3%    |
| tr_TR   | 6         | 0.26%   |
| pt_PT   | 6         | 0.26%   |
| de_CH   | 6         | 0.26%   |
| es_CO   | 5         | 0.21%   |
| en_ZA   | 5         | 0.21%   |
| en_NZ   | 5         | 0.21%   |
| cs_CZ   | 5         | 0.21%   |
| uk_UA   | 4         | 0.17%   |
| es_PE   | 4         | 0.17%   |
| en_SG   | 4         | 0.17%   |
| zh_TW   | 3         | 0.13%   |
| nn_NO   | 3         | 0.13%   |
| nb_NO   | 3         | 0.13%   |
| hr_HR   | 3         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1609      | 68.97%  |
| BIOS | 724       | 31.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1318      | 56.79%  |
| Overlay | 904       | 38.95%  |
| Btrfs   | 59        | 2.54%   |
| Xfs     | 23        | 0.99%   |
| Zfs     | 7         | 0.3%    |
| Tmpfs   | 3         | 0.13%   |
| Unknown | 3         | 0.13%   |
| Ext2    | 2         | 0.09%   |
| Rootfs  | 1         | 0.04%   |
| Ext3    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1615      | 68.96%  |
| MBR     | 399       | 17.04%  |
| Unknown | 328       | 14.01%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1774      | 76.04%  |
| Yes       | 559       | 23.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1759      | 75.3%   |
| Yes       | 577       | 24.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Apple                  | 554       | 23.92%  |
| Lenovo                 | 460       | 19.86%  |
| Hewlett-Packard        | 309       | 13.34%  |
| Dell                   | 251       | 10.84%  |
| ASUSTek Computer       | 186       | 8.03%   |
| Acer                   | 125       | 5.4%    |
| Google                 | 113       | 4.88%   |
| Aquarius               | 43        | 1.86%   |
| MSI                    | 32        | 1.38%   |
| Samsung Electronics    | 26        | 1.12%   |
| Toshiba                | 23        | 0.99%   |
| HUAWEI                 | 21        | 0.91%   |
| Sony                   | 16        | 0.69%   |
| Notebook               | 11        | 0.47%   |
| Unknown                | 11        | 0.47%   |
| Fujitsu                | 8         | 0.35%   |
| Packard Bell           | 7         | 0.3%    |
| Clevo                  | 6         | 0.26%   |
| Timi                   | 5         | 0.22%   |
| TUXEDO                 | 4         | 0.17%   |
| SLIMBOOK               | 4         | 0.17%   |
| Medion                 | 4         | 0.17%   |
| LG Electronics         | 4         | 0.17%   |
| IBM                    | 4         | 0.17%   |
| HONOR                  | 4         | 0.17%   |
| GPU Company            | 4         | 0.17%   |
| Fujitsu Siemens        | 4         | 0.17%   |
| System76               | 3         | 0.13%   |
| Positivo               | 3         | 0.13%   |
| PC Specialist          | 3         | 0.13%   |
| Panasonic              | 3         | 0.13%   |
| Intel                  | 3         | 0.13%   |
| Gigabyte Technology    | 3         | 0.13%   |
| Avell High Performance | 3         | 0.13%   |
| Alienware              | 3         | 0.13%   |
| Razer                  | 2         | 0.09%   |
| Jumper                 | 2         | 0.09%   |
| Getac                  | 2         | 0.09%   |
| Compal                 | 2         | 0.09%   |
| Chuwi                  | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 303       | 13.08%  |
| Apple MacBookAir7,1                   | 75        | 3.24%   |
| Google Enguarde                       | 74        | 3.2%    |
| Apple MacBookAir7,2                   | 71        | 3.07%   |
| Apple MacBook2,1                      | 55        | 2.37%   |
| Aquarius NS585                        | 43        | 1.86%   |
| Lenovo ThinkPad E475 20H40006US       | 23        | 0.99%   |
| Apple MacBook4,1                      | 21        | 0.91%   |
| Google Terra                          | 18        | 0.78%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.69%   |
| Unknown                               | 16        | 0.69%   |
| Acer Aspire A315-23                   | 15        | 0.65%   |
| ASUS 1005HA                           | 12        | 0.52%   |
| HP Notebook                           | 11        | 0.47%   |
| HP Pavilion g6                        | 10        | 0.43%   |
| Google Reks                           | 9         | 0.39%   |
| HP EliteBook 8460p                    | 7         | 0.3%    |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 6         | 0.26%   |
| HP Laptop 15-db1xxx                   | 6         | 0.26%   |
| HP Laptop 15-db0xxx                   | 6         | 0.26%   |
| HP Laptop 15-bw0xx                    | 6         | 0.26%   |
| HP 250 G7 Notebook PC                 | 6         | 0.26%   |
| Dell XPS 13 9310                      | 6         | 0.26%   |
| Dell Latitude E6330                   | 6         | 0.26%   |
| Dell Inspiron 5100                    | 6         | 0.26%   |
| Apple MacBook7,1                      | 6         | 0.26%   |
| HP Pavilion Gaming Laptop 15-ec2xxx   | 5         | 0.22%   |
| Dell Latitude E6420                   | 5         | 0.22%   |
| Dell Latitude 7480                    | 5         | 0.22%   |
| Acer Aspire A515-56                   | 5         | 0.22%   |
| Samsung 300E4C/300E5C/300E7C          | 4         | 0.17%   |
| Lenovo IdeaPad S145-15API 81V7        | 4         | 0.17%   |
| Lenovo IdeaPad L340-15API 81LW        | 4         | 0.17%   |
| Lenovo B50-30 20382                   | 4         | 0.17%   |
| HP Laptop 15s-fq2xxx                  | 4         | 0.17%   |
| HP EliteBook 840 G3                   | 4         | 0.17%   |
| HP Compaq nx6110 (PZ065UA#ABA)        | 4         | 0.17%   |
| HP 255 G8 Notebook PC                 | 4         | 0.17%   |
| Dell Latitude 5420                    | 4         | 0.17%   |
| ASUS X555LD                           | 4         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 315       | 13.6%   |
| Apple MacBook5        | 303       | 13.08%  |
| Apple MacBookAir7     | 146       | 6.3%    |
| Dell Latitude         | 90        | 3.89%   |
| Acer Aspire           | 84        | 3.63%   |
| Dell Inspiron         | 81        | 3.5%    |
| Lenovo IdeaPad        | 77        | 3.32%   |
| Google Enguarde       | 74        | 3.2%    |
| Apple MacBook2        | 55        | 2.37%   |
| HP Laptop             | 52        | 2.25%   |
| HP Pavilion           | 50        | 2.16%   |
| HP EliteBook          | 47        | 2.03%   |
| HP ProBook            | 43        | 1.86%   |
| Aquarius NS585        | 43        | 1.86%   |
| Dell XPS              | 32        | 1.38%   |
| ASUS VivoBook         | 26        | 1.12%   |
| Dell Vostro           | 23        | 0.99%   |
| Apple MacBook4        | 21        | 0.91%   |
| HP Compaq             | 20        | 0.86%   |
| Toshiba Satellite     | 19        | 0.82%   |
| Google Terra          | 18        | 0.78%   |
| ASUS ZenBook          | 18        | 0.78%   |
| HP 250                | 17        | 0.73%   |
| Dell Precision        | 17        | 0.73%   |
| Unknown               | 16        | 0.69%   |
| HP ZBook              | 14        | 0.6%    |
| ASUS ASUS             | 14        | 0.6%    |
| ASUS 1005HA           | 12        | 0.52%   |
| Acer TravelMate       | 12        | 0.52%   |
| HP Notebook           | 11        | 0.47%   |
| ASUS ROG              | 10        | 0.43%   |
| Google Reks           | 9         | 0.39%   |
| Acer Swift            | 9         | 0.39%   |
| Acer Nitro            | 9         | 0.39%   |
| Lenovo ThinkBook      | 8         | 0.35%   |
| HP Stream             | 8         | 0.35%   |
| HP ENVY               | 8         | 0.35%   |
| HP 255                | 8         | 0.35%   |
| Fujitsu LIFEBOOK      | 7         | 0.3%    |
| Packard Bell EasyNote | 6         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 353       | 15.24%  |
| 2020    | 228       | 9.84%   |
| 2021    | 226       | 9.76%   |
| 2019    | 222       | 9.59%   |
| 2016    | 157       | 6.78%   |
| 2015    | 155       | 6.69%   |
| 2018    | 131       | 5.66%   |
| 2012    | 122       | 5.27%   |
| 2017    | 113       | 4.88%   |
| 2011    | 107       | 4.62%   |
| 2013    | 90        | 3.89%   |
| 2007    | 89        | 3.84%   |
| 2014    | 85        | 3.67%   |
| 2022    | 70        | 3.02%   |
| 2010    | 63        | 2.72%   |
| 2008    | 63        | 2.72%   |
| 2005    | 16        | 0.69%   |
| 2006    | 11        | 0.47%   |
| 2003    | 8         | 0.35%   |
| 2004    | 4         | 0.17%   |
| Unknown | 2         | 0.09%   |
| 2002    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2316      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2142      | 92.17%  |
| Enabled  | 182       | 7.83%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2202      | 95.04%  |
| Yes  | 115       | 4.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 624       | 26.8%   |
| 3.01-4.0    | 462       | 19.85%  |
| 1.01-2.0    | 420       | 18.04%  |
| 16.01-24.0  | 316       | 13.57%  |
| 8.01-16.0   | 262       | 11.25%  |
| 32.01-64.0  | 104       | 4.47%   |
| 2.01-3.0    | 45        | 1.93%   |
| 0.51-1.0    | 44        | 1.89%   |
| 64.01-256.0 | 21        | 0.9%    |
| 24.01-32.0  | 19        | 0.82%   |
| 0.01-0.5    | 10        | 0.43%   |
| Unknown     | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1157      | 48.05%  |
| 2.01-3.0   | 411       | 17.07%  |
| 0.51-1.0   | 267       | 11.09%  |
| 4.01-8.0   | 248       | 10.3%   |
| 3.01-4.0   | 194       | 8.06%   |
| 0.01-0.5   | 61        | 2.53%   |
| 8.01-16.0  | 60        | 2.49%   |
| 16.01-24.0 | 4         | 0.17%   |
| 32.01-64.0 | 2         | 0.08%   |
| 24.01-32.0 | 2         | 0.08%   |
| Unknown    | 2         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1957      | 83.7%   |
| 2      | 329       | 14.07%  |
| 3      | 30        | 1.28%   |
| 0      | 12        | 0.51%   |
| 4      | 7         | 0.3%    |
| 5      | 2         | 0.09%   |
| 7      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1438      | 61.98%  |
| Yes       | 882       | 38.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1824      | 78.62%  |
| No        | 496       | 21.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2287      | 98.71%  |
| No        | 30        | 1.29%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1950      | 83.83%  |
| No        | 376       | 16.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 906       | 38.98%  |
| Russia       | 209       | 8.99%   |
| Germany      | 157       | 6.76%   |
| France       | 120       | 5.16%   |
| Spain        | 100       | 4.3%    |
| Brazil       | 69        | 2.97%   |
| Poland       | 61        | 2.62%   |
| Italy        | 52        | 2.24%   |
| UK           | 50        | 2.15%   |
| Netherlands  | 34        | 1.46%   |
| Canada       | 34        | 1.46%   |
| Mexico       | 28        | 1.2%    |
| Sweden       | 24        | 1.03%   |
| China        | 24        | 1.03%   |
| Australia    | 22        | 0.95%   |
| Ukraine      | 21        | 0.9%    |
| Switzerland  | 21        | 0.9%    |
| Argentina    | 21        | 0.9%    |
| India        | 19        | 0.82%   |
| Turkey       | 18        | 0.77%   |
| Austria      | 16        | 0.69%   |
| Czechia      | 14        | 0.6%    |
| Hungary      | 13        | 0.56%   |
| Greece       | 13        | 0.56%   |
| Portugal     | 12        | 0.52%   |
| Norway       | 12        | 0.52%   |
| Finland      | 12        | 0.52%   |
| Chile        | 12        | 0.52%   |
| Japan        | 11        | 0.47%   |
| Colombia     | 11        | 0.47%   |
| Belgium      | 11        | 0.47%   |
| Venezuela    | 10        | 0.43%   |
| Romania      | 9         | 0.39%   |
| Ireland      | 9         | 0.39%   |
| Indonesia    | 9         | 0.39%   |
| Croatia      | 8         | 0.34%   |
| Bulgaria     | 8         | 0.34%   |
| Thailand     | 7         | 0.3%    |
| New Zealand  | 7         | 0.3%    |
| South Africa | 6         | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Bangor         | 528       | 21.93%  |
| Dover-Foxcroft | 229       | 9.51%   |
| Voronezh       | 126       | 5.23%   |
| Seville        | 29        | 1.2%    |
| Paris          | 24        | 1%      |
| St Petersburg  | 20        | 0.83%   |
| Madrid         | 19        | 0.79%   |
| Berlin         | 19        | 0.79%   |
| Warsaw         | 15        | 0.62%   |
| Amsterdam      | 14        | 0.58%   |
| Moscow         | 13        | 0.54%   |
| Vienna         | 12        | 0.5%    |
| Munich         | 12        | 0.5%    |
| London         | 12        | 0.5%    |
| Blizniew       | 11        | 0.46%   |
| Barcelona      | 10        | 0.42%   |
| Toronto        | 8         | 0.33%   |
| Sydney         | 8         | 0.33%   |
| Milan          | 8         | 0.33%   |
| Lyon           | 8         | 0.33%   |
| Athens         | 8         | 0.33%   |
| Zagreb         | 7         | 0.29%   |
| Prague         | 7         | 0.29%   |
| Perm           | 7         | 0.29%   |
| Natal          | 7         | 0.29%   |
| Mesa           | 7         | 0.29%   |
| Dublin         | 7         | 0.29%   |
| Sao Paulo      | 6         | 0.25%   |
| Manchester     | 6         | 0.25%   |
| Istanbul       | 6         | 0.25%   |
| Helsinki       | 6         | 0.25%   |
| Brisbane       | 6         | 0.25%   |
| Bengaluru      | 6         | 0.25%   |
| Bangkok        | 6         | 0.25%   |
| Yekaterinburg  | 5         | 0.21%   |
| Turin          | 5         | 0.21%   |
| San Jose       | 5         | 0.21%   |
| Leimen         | 5         | 0.21%   |
| Caracas        | 5         | 0.21%   |
| Thermopolis    | 4         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 334       | 401    | 12.54%  |
| WDC                       | 267       | 315    | 10.02%  |
| Fujitsu                   | 237       | 240    | 8.9%    |
| Toshiba                   | 224       | 238    | 8.41%   |
| Seagate                   | 211       | 250    | 7.92%   |
| Unknown                   | 186       | 238    | 6.98%   |
| Apple                     | 159       | 184    | 5.97%   |
| Kingston                  | 137       | 150    | 5.14%   |
| SanDisk                   | 111       | 131    | 4.17%   |
| SK hynix                  | 98        | 110    | 3.68%   |
| Crucial                   | 96        | 110    | 3.6%    |
| Hitachi                   | 81        | 91     | 3.04%   |
| A-DATA Technology         | 77        | 150    | 2.89%   |
| Intel                     | 54        | 58     | 2.03%   |
| Micron Technology         | 51        | 51     | 1.91%   |
| HGST                      | 39        | 44     | 1.46%   |
| KIOXIA                    | 29        | 33     | 1.09%   |
| China                     | 19        | 19     | 0.71%   |
| SABRENT                   | 16        | 17     | 0.6%    |
| LITEON                    | 15        | 17     | 0.56%   |
| Transcend                 | 13        | 18     | 0.49%   |
| Silicon Motion            | 12        | 13     | 0.45%   |
| Phison                    | 11        | 15     | 0.41%   |
| Intenso                   | 10        | 13     | 0.38%   |
| Unknown                   | 10        | 10     | 0.38%   |
| PNY                       | 9         | 9      | 0.34%   |
| LITEONIT                  | 8         | 9      | 0.3%    |
| Goodram                   | 8         | 9      | 0.3%    |
| SPCC                      | 6         | 6      | 0.23%   |
| Patriot                   | 6         | 6      | 0.23%   |
| Lenovo                    | 6         | 7      | 0.23%   |
| KIOXIA-EXCERIA            | 5         | 6      | 0.19%   |
| JMicron Technology        | 5         | 5      | 0.19%   |
| Union Memory              | 4         | 4      | 0.15%   |
| Team                      | 4         | 4      | 0.15%   |
| SSSTC                     | 4         | 4      | 0.15%   |
| Netac                     | 4         | 4      | 0.15%   |
| Micron/Crucial Technology | 4         | 4      | 0.15%   |
| Lexar                     | 4         | 5      | 0.15%   |
| Apacer                    | 4         | 4      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 200       | 7.35%   |
| Apple SSD AP0128H 121GB              | 75        | 2.76%   |
| Apple SSD SM0128G 121GB              | 70        | 2.57%   |
| Toshiba MK1655GSXF 160GB             | 46        | 1.69%   |
| A-DATA SU800 512GB SSD               | 43        | 1.58%   |
| Toshiba MK1653GSX 160GB              | 42        | 1.54%   |
| Unknown AGND3R  16GB                 | 39        | 1.43%   |
| Seagate ST1000LM035-1RK172 1TB       | 35        | 1.29%   |
| Unknown HAG2e  16GB                  | 30        | 1.1%    |
| Kingston SA400S37120G 120GB SSD      | 30        | 1.1%    |
| Kingston SA400S37240G 240GB SSD      | 25        | 0.92%   |
| Unknown SDW16G  16GB                 | 21        | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 20        | 0.74%   |
| Toshiba MQ01ABF050 500GB             | 19        | 0.7%    |
| Toshiba MQ04ABF100 1TB               | 18        | 0.66%   |
| WDC WD1600BUDT-63DPZY0 160GB         | 16        | 0.59%   |
| Samsung SSD 860 EVO 500GB            | 16        | 0.59%   |
| SABRENT Disk 1TB                     | 16        | 0.59%   |
| Crucial CT1000MX500SSD1 1TB          | 14        | 0.51%   |
| SanDisk SD8SBAT128G1122 128GB SSD    | 13        | 0.48%   |
| HGST HTS721010A9E630 1TB             | 13        | 0.48%   |
| Crucial CT500MX500SSD1 500GB         | 13        | 0.48%   |
| Unknown MMC Card  32GB               | 12        | 0.44%   |
| Seagate ST500LT012-1DG142 500GB      | 12        | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB         | 12        | 0.44%   |
| Toshiba MQ01ABD100 1TB               | 11        | 0.4%    |
| Kingston SV300S37A120G 120GB SSD     | 11        | 0.4%    |
| Fujitsu MHY2120BH 120GB              | 11        | 0.4%    |
| WDC WD10SPZX-24Z10 1TB               | 10        | 0.37%   |
| Seagate ST980811AS 80GB              | 10        | 0.37%   |
| Kingston SA400S37480G 480GB SSD      | 10        | 0.37%   |
| Unknown                              | 10        | 0.37%   |
| Toshiba MK5065GSXF 500GB             | 9         | 0.33%   |
| SanDisk SD8SN8U128G1001 128GB SSD    | 9         | 0.33%   |
| Samsung MZNTY128HDHP-000L1 128GB SSD | 9         | 0.33%   |
| Intel SSDPEKNW512G8 512GB            | 9         | 0.33%   |
| Fujitsu MHY2080BH 80GB               | 9         | 0.33%   |
| Crucial CT120BX500SSD1 120GB         | 9         | 0.33%   |
| SanDisk SSD PLUS 240GB               | 8         | 0.29%   |
| Samsung SSD 860 EVO M.2 1TB          | 8         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Fujitsu             | 237       | 240    | 25.96%  |
| Seagate             | 204       | 242    | 22.34%  |
| Toshiba             | 186       | 196    | 20.37%  |
| WDC                 | 143       | 157    | 15.66%  |
| Hitachi             | 81        | 91     | 8.87%   |
| HGST                | 39        | 44     | 4.27%   |
| Samsung Electronics | 10        | 10     | 1.1%    |
| Unknown             | 5         | 8      | 0.55%   |
| USB3.0              | 1         | 1      | 0.11%   |
| Unknown (CF)        | 1         | 1      | 0.11%   |
| SILICONMOTION       | 1         | 1      | 0.11%   |
| Maxone              | 1         | 1      | 0.11%   |
| Intenso             | 1         | 1      | 0.11%   |
| IBM/Hitachi         | 1         | 1      | 0.11%   |
| ASMT109x            | 1         | 1      | 0.11%   |
| ASMT                | 1         | 2      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 157       | 186    | 19.22%  |
| Kingston            | 106       | 118    | 12.97%  |
| Crucial             | 84        | 96     | 10.28%  |
| SanDisk             | 83        | 100    | 10.16%  |
| Apple               | 79        | 83     | 9.67%   |
| A-DATA Technology   | 60        | 124    | 7.34%   |
| WDC                 | 27        | 37     | 3.3%    |
| Micron Technology   | 22        | 22     | 2.69%   |
| SK hynix            | 19        | 22     | 2.33%   |
| China               | 19        | 19     | 2.33%   |
| Intel               | 14        | 15     | 1.71%   |
| LITEON              | 13        | 15     | 1.59%   |
| Transcend           | 12        | 17     | 1.47%   |
| Toshiba             | 12        | 12     | 1.47%   |
| Intenso             | 9         | 12     | 1.1%    |
| PNY                 | 8         | 8      | 0.98%   |
| LITEONIT            | 8         | 9      | 0.98%   |
| Patriot             | 6         | 6      | 0.73%   |
| GOODRAM             | 6         | 7      | 0.73%   |
| SPCC                | 5         | 5      | 0.61%   |
| Team                | 4         | 4      | 0.49%   |
| Netac               | 4         | 4      | 0.49%   |
| Lexar               | 4         | 5      | 0.49%   |
| Seagate             | 3         | 3      | 0.37%   |
| Plextor             | 3         | 3      | 0.37%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.37%   |
| Apacer              | 3         | 3      | 0.37%   |
| ZTC                 | 2         | 3      | 0.24%   |
| Unknown             | 2         | 2      | 0.24%   |
| OCZ                 | 2         | 2      | 0.24%   |
| Corsair             | 2         | 2      | 0.24%   |
| ASUS-PHISON         | 2         | 2      | 0.24%   |
| Unknown             | 2         | 2      | 0.24%   |
| Win Memory          | 1         | 1      | 0.12%   |
| W800SH              | 1         | 1      | 0.12%   |
| Vaseky              | 1         | 2      | 0.12%   |
| Union Memory        | 1         | 1      | 0.12%   |
| TrekStor            | 1         | 1      | 0.12%   |
| Teclast             | 1         | 2      | 0.12%   |
| S3+                 | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 897       | 997    | 34.73%  |
| SSD     | 780       | 991    | 30.2%   |
| NVMe    | 694       | 850    | 26.87%  |
| MMC     | 193       | 242    | 7.47%   |
| Unknown | 19        | 21     | 0.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1562      | 1935   | 62.38%  |
| NVMe | 679       | 828    | 27.12%  |
| MMC  | 193       | 242    | 7.71%   |
| SAS  | 70        | 96     | 2.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1255      | 1457   | 75.47%  |
| 0.51-1.0   | 370       | 485    | 22.25%  |
| 1.01-2.0   | 29        | 35     | 1.74%   |
| 3.01-4.0   | 4         | 5      | 0.24%   |
| 4.01-10.0  | 4         | 5      | 0.24%   |
| 2.01-3.0   | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 661       | 27.86%  |
| Unknown        | 622       | 26.21%  |
| 251-500        | 385       | 16.22%  |
| 501-1000       | 232       | 9.78%   |
| 1-20           | 159       | 6.7%    |
| 51-100         | 115       | 4.85%   |
| 1001-2000      | 94        | 3.96%   |
| 21-50          | 60        | 2.53%   |
| 2001-3000      | 25        | 1.05%   |
| More than 3000 | 20        | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 864       | 35.81%  |
| Unknown        | 622       | 25.78%  |
| 21-50          | 254       | 10.53%  |
| 51-100         | 214       | 8.87%   |
| 101-250        | 209       | 8.66%   |
| 251-500        | 130       | 5.39%   |
| 501-1000       | 74        | 3.07%   |
| 1001-2000      | 27        | 1.12%   |
| More than 3000 | 8         | 0.33%   |
| 0              | 8         | 0.33%   |
| 2001-3000      | 3         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                      | 20        | 20     | 8.89%   |
| Toshiba MK1653GSX 160GB                             | 9         | 9      | 4%      |
| Toshiba MK1655GSXF 160GB                            | 7         | 7      | 3.11%   |
| Hitachi HTS543216L9SA02 160GB                       | 6         | 6      | 2.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 6      | 2.22%   |
| Hitachi HTS542512K9SA00 120GB                       | 5         | 6      | 2.22%   |
| WDC WD1600BUDT-63DPZY0 160GB                        | 4         | 4      | 1.78%   |
| Seagate ST9500420AS 500GB                           | 4         | 4      | 1.78%   |
| Seagate ST9500325AS 500GB                           | 4         | 4      | 1.78%   |
| Seagate ST500LM000-SSHD-8GB                         | 3         | 3      | 1.33%   |
| Hitachi HTS545050B9A300 500GB                       | 3         | 3      | 1.33%   |
| HGST HTS725050A7E630 500GB                          | 3         | 3      | 1.33%   |
| HGST HTS541010A9E680 1TB                            | 3         | 3      | 1.33%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 2         | 3      | 0.89%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 2      | 0.89%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 2      | 0.89%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 2      | 0.89%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 2         | 2      | 0.89%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 2         | 2      | 0.89%   |
| SK hynix HFS256G39MND-2300A 256GB SSD               | 2         | 2      | 0.89%   |
| Seagate ST980811AS 80GB                             | 2         | 2      | 0.89%   |
| Seagate ST94811A 40GB                               | 2         | 2      | 0.89%   |
| Seagate ST500LT012-9WS142 500GB                     | 2         | 2      | 0.89%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 2      | 0.89%   |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 2      | 0.89%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.89%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 2      | 0.89%   |
| Hitachi HTS547575A9E384 752GB                       | 2         | 2      | 0.89%   |
| Hitachi HTS545032B9A300 320GB                       | 2         | 4      | 0.89%   |
| Hitachi HTS542516K9SA00 160GB                       | 2         | 2      | 0.89%   |
| Hitachi HTS541060G9AT00 64GB                        | 2         | 3      | 0.89%   |
| Crucial CT275MX300SSD1 275GB                        | 2         | 2      | 0.89%   |
| WDC WD7500BPVX-22JC3T0 752GB                        | 1         | 1      | 0.44%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1         | 1      | 0.44%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 0.44%   |
| WDC WD5000BPVT-22HXZT1 500GB                        | 1         | 1      | 0.44%   |
| WDC WD5000BPVT-08HXZT1 500GB                        | 1         | 1      | 0.44%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 0.44%   |
| WDC WD1600BUDT-73DPZY0 160GB                        | 1         | 1      | 0.44%   |
| WDC WD1600BJKT-75F4T0 160GB                         | 1         | 1      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 44     | 17.86%  |
| Hitachi             | 38        | 43     | 16.96%  |
| Fujitsu             | 28        | 28     | 12.5%   |
| Toshiba             | 27        | 27     | 12.05%  |
| WDC                 | 19        | 20     | 8.48%   |
| SK hynix            | 12        | 12     | 5.36%   |
| HGST                | 12        | 12     | 5.36%   |
| Samsung Electronics | 9         | 10     | 4.02%   |
| Micron Technology   | 7         | 7      | 3.13%   |
| Kingston            | 7         | 7      | 3.13%   |
| Intel               | 5         | 6      | 2.23%   |
| SanDisk             | 4         | 5      | 1.79%   |
| Crucial             | 4         | 4      | 1.79%   |
| LITEON              | 3         | 3      | 1.34%   |
| LITEONIT            | 2         | 2      | 0.89%   |
| A-DATA Technology   | 2         | 2      | 0.89%   |
| ShiJi               | 1         | 1      | 0.45%   |
| Lenovo              | 1         | 1      | 0.45%   |
| IBM/Hitachi         | 1         | 1      | 0.45%   |
| GOODRAM             | 1         | 1      | 0.45%   |
| DGM                 | 1         | 1      | 0.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 44     | 23.81%  |
| Hitachi             | 38        | 43     | 22.62%  |
| Fujitsu             | 28        | 28     | 16.67%  |
| Toshiba             | 27        | 27     | 16.07%  |
| WDC                 | 19        | 20     | 11.31%  |
| HGST                | 12        | 12     | 7.14%   |
| Samsung Electronics | 3         | 3      | 1.79%   |
| IBM/Hitachi         | 1         | 1      | 0.6%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 168       | 178    | 75%     |
| SSD  | 46        | 49     | 20.54%  |
| NVMe | 10        | 10     | 4.46%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                 | 1         | 1      | 20%     |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 20%     |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 20%     |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB | 1         | 1      | 20%     |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 40%     |
| WDC                 | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1691      | 2100   | 69.02%  |
| Detected | 530       | 758    | 21.63%  |
| Malfunc  | 223       | 237    | 9.1%    |
| Failed   | 5         | 5      | 0.2%    |
| Limited  | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1220      | 48.51%  |
| Nvidia                           | 313       | 12.45%  |
| Samsung Electronics              | 250       | 9.94%   |
| AMD                              | 228       | 9.07%   |
| SanDisk                          | 118       | 4.69%   |
| Apple                            | 80        | 3.18%   |
| SK hynix                         | 77        | 3.06%   |
| Toshiba America Info Systems     | 31        | 1.23%   |
| Kingston Technology Company      | 31        | 1.23%   |
| Micron Technology                | 29        | 1.15%   |
| KIOXIA                           | 28        | 1.11%   |
| Silicon Motion                   | 20        | 0.8%    |
| ADATA Technology                 | 20        | 0.8%    |
| Phison Electronics               | 15        | 0.6%    |
| Micron/Crucial Technology        | 15        | 0.6%    |
| Solid State Storage Technology   | 8         | 0.32%   |
| Union Memory (Shenzhen)          | 6         | 0.24%   |
| Shenzhen Longsys Electronics     | 4         | 0.16%   |
| Lenovo                           | 4         | 0.16%   |
| Realtek Semiconductor            | 3         | 0.12%   |
| ULi Electronics                  | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| Lite-On Technology               | 2         | 0.08%   |
| ASMedia Technology               | 2         | 0.08%   |
| Yangtze Memory Technologies      | 1         | 0.04%   |
| VIA Technologies                 | 1         | 0.04%   |
| Silicon Image                    | 1         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.04%   |
| Marvell Technology Group         | 1         | 0.04%   |
| JMicron Technology               | 1         | 0.04%   |
| Unknown                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 AHCI Controller                                                   | 306       | 11.25%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 211       | 7.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 154       | 5.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 126       | 4.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 101       | 3.71%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 79        | 2.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 79        | 2.91%   |
| Apple S1X NVMe Controller                                                      | 76        | 2.8%    |
| Samsung Electronics SATA controller                                            | 74        | 2.72%   |
| Intel Volume Management Device NVMe RAID Controller                            | 74        | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 70        | 2.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 65        | 2.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 56        | 2.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 53        | 1.95%   |
| Samsung NVMe SSD Controller 980                                                | 50        | 1.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 49        | 1.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 47        | 1.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 43        | 1.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 42        | 1.54%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 37        | 1.36%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 36        | 1.32%   |
| SK hynix Gold P31 SSD                                                          | 35        | 1.29%   |
| Intel Tiger Lake-LP SATA Controller                                            | 32        | 1.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 32        | 1.18%   |
| Micron Non-Volatile memory controller                                          | 29        | 1.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 27        | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 26        | 0.96%   |
| Intel SSD 660P Series                                                          | 25        | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 25        | 0.92%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 24        | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 24        | 0.88%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 23        | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 23        | 0.85%   |
| SanDisk Non-Volatile memory controller                                         | 21        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 21        | 0.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 0.74%   |
| SK hynix BC511                                                                 | 17        | 0.63%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 16        | 0.59%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 15        | 0.55%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 15        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1613      | 60.8%   |
| NVMe | 679       | 25.59%  |
| IDE  | 206       | 7.76%   |
| RAID | 155       | 5.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1995      | 86.1%   |
| AMD    | 320       | 13.81%  |
| ARM    | 2         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 304       | 13.11%  |
| Intel Core i5-5250U CPU @ 1.60GHz             | 142       | 6.13%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 85        | 3.67%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 58        | 2.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 51        | 2.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 44        | 1.9%    |
| Intel Core i3-9100 CPU @ 3.60GHz              | 43        | 1.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 43        | 1.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 32        | 1.38%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 31        | 1.34%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 26        | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 25        | 1.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 1.08%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 23        | 0.99%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 23        | 0.99%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 23        | 0.99%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 23        | 0.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 22        | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 22        | 0.95%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 20        | 0.86%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 18        | 0.78%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 18        | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 17        | 0.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 17        | 0.73%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 16        | 0.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 16        | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 14        | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 14        | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 14        | 0.6%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 14        | 0.6%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 13        | 0.56%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 13        | 0.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 12        | 0.52%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 0.52%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 12        | 0.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 11        | 0.47%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 11        | 0.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.47%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 11        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 563       | 24.3%   |
| Intel Core 2 Duo               | 390       | 16.83%  |
| Intel Core i7                  | 313       | 13.51%  |
| Intel Celeron                  | 212       | 9.15%   |
| Other                          | 177       | 7.64%   |
| Intel Core i3                  | 137       | 5.91%   |
| AMD Ryzen 5                    | 110       | 4.75%   |
| Intel Core 2                   | 60        | 2.59%   |
| Intel Atom                     | 50        | 2.16%   |
| Intel Pentium                  | 45        | 1.94%   |
| AMD Ryzen 7                    | 44        | 1.9%    |
| AMD A6                         | 21        | 0.91%   |
| AMD Ryzen 7 PRO                | 19        | 0.82%   |
| Intel Pentium M                | 17        | 0.73%   |
| AMD Ryzen 3                    | 12        | 0.52%   |
| Intel Genuine                  | 11        | 0.47%   |
| AMD A4                         | 11        | 0.47%   |
| AMD Ryzen 9                    | 10        | 0.43%   |
| AMD E1                         | 8         | 0.35%   |
| AMD A8                         | 8         | 0.35%   |
| Intel Pentium Dual-Core        | 7         | 0.3%    |
| Intel Pentium Dual             | 7         | 0.3%    |
| Intel Celeron M                | 7         | 0.3%    |
| AMD Ryzen 5 PRO                | 7         | 0.3%    |
| AMD A10                        | 7         | 0.3%    |
| Intel Pentium 4                | 6         | 0.26%   |
| Intel Core i9                  | 5         | 0.22%   |
| AMD A12                        | 5         | 0.22%   |
| Intel Pentium Silver           | 4         | 0.17%   |
| AMD E2                         | 4         | 0.17%   |
| Intel Xeon                     | 3         | 0.13%   |
| Intel Pentium Gold             | 3         | 0.13%   |
| Intel Mobile Pentium 4         | 3         | 0.13%   |
| AMD E                          | 3         | 0.13%   |
| AMD Athlon                     | 3         | 0.13%   |
| Intel Core m3                  | 2         | 0.09%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.09%   |
| AMD Turion 64 Mobile           | 2         | 0.09%   |
| AMD C-60                       | 2         | 0.09%   |
| AMD C-50                       | 2         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1403      | 60.55%  |
| 4      | 600       | 25.9%   |
| 6      | 108       | 4.66%   |
| 1      | 108       | 4.66%   |
| 8      | 90        | 3.88%   |
| 14     | 3         | 0.13%   |
| 10     | 3         | 0.13%   |
| 12     | 2         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2316      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1377      | 59.46%  |
| 1      | 938       | 40.5%   |
| 4      | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2249      | 97.11%  |
| 32-bit         | 63        | 2.72%   |
| Unknown        | 4         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 358       | 15.27%  |
| 0x1067a    | 342       | 14.59%  |
| 0x306d4    | 189       | 8.06%   |
| 0x806c1    | 97        | 4.14%   |
| 0x30678    | 92        | 3.92%   |
| 0x306a9    | 91        | 3.88%   |
| 0x206a7    | 79        | 3.37%   |
| 0x806ec    | 70        | 2.99%   |
| 0x806e9    | 64        | 2.73%   |
| 0x6f6      | 60        | 2.56%   |
| 0x806ea    | 54        | 2.3%    |
| 0x406e3    | 49        | 2.09%   |
| 0x40651    | 46        | 1.96%   |
| 0x906eb    | 43        | 1.83%   |
| 0x406c4    | 38        | 1.62%   |
| 0xa0652    | 35        | 1.49%   |
| 0x306c3    | 35        | 1.49%   |
| 0x08108109 | 34        | 1.45%   |
| 0x10676    | 29        | 1.24%   |
| 0x08600106 | 29        | 1.24%   |
| 0x20655    | 28        | 1.19%   |
| 0x08608103 | 28        | 1.19%   |
| 0x0600611a | 27        | 1.15%   |
| 0x906ea    | 26        | 1.11%   |
| 0x0a50000c | 24        | 1.02%   |
| 0x706e5    | 22        | 0.94%   |
| 0x106c2    | 21        | 0.9%    |
| 0x706a8    | 18        | 0.77%   |
| 0x806eb    | 17        | 0.73%   |
| 0x6fd      | 17        | 0.73%   |
| 0x06006705 | 17        | 0.73%   |
| 0x6d8      | 16        | 0.68%   |
| 0x08108102 | 16        | 0.68%   |
| 0x506e3    | 15        | 0.64%   |
| 0x506c9    | 14        | 0.6%    |
| 0x906e9    | 13        | 0.55%   |
| 0x806d1    | 12        | 0.51%   |
| 0x106ca    | 12        | 0.51%   |
| 0xf29      | 9         | 0.38%   |
| 0x6e8      | 8         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Penryn           | 378       | 16.3%   |
| KabyLake         | 359       | 15.48%  |
| Broadwell        | 200       | 8.62%   |
| Silvermont       | 149       | 6.43%   |
| IvyBridge        | 126       | 5.43%   |
| TigerLake        | 125       | 5.39%   |
| Haswell          | 107       | 4.61%   |
| SandyBridge      | 102       | 4.4%    |
| Core             | 97        | 4.18%   |
| Skylake          | 85        | 3.67%   |
| Zen+             | 68        | 2.93%   |
| Zen 2            | 60        | 2.59%   |
| Excavator        | 56        | 2.41%   |
| Westmere         | 51        | 2.2%    |
| Unknown          | 44        | 1.9%    |
| CometLake        | 42        | 1.81%   |
| IceLake          | 37        | 1.6%    |
| Bonnell          | 37        | 1.6%    |
| Zen 3            | 31        | 1.34%   |
| P6               | 31        | 1.34%   |
| Goldmont plus    | 27        | 1.16%   |
| Goldmont         | 16        | 0.69%   |
| Zen              | 15        | 0.65%   |
| Puma             | 13        | 0.56%   |
| Bobcat           | 13        | 0.56%   |
| NetBurst         | 9         | 0.39%   |
| K10 Llano        | 9         | 0.39%   |
| Jaguar           | 7         | 0.3%    |
| Piledriver       | 6         | 0.26%   |
| K8 Hammer        | 5         | 0.22%   |
| Tremont          | 4         | 0.17%   |
| Alderlake Hybrid | 3         | 0.13%   |
| Nehalem          | 2         | 0.09%   |
| K8 & K10 hybrid  | 2         | 0.09%   |
| K10              | 2         | 0.09%   |
| Steamroller      | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1590      | 58.95%  |
| Nvidia                           | 683       | 25.32%  |
| AMD                              | 420       | 15.57%  |
| Silicon Integrated Systems [SiS] | 2         | 0.07%   |
| VIA Technologies                 | 1         | 0.04%   |
| S3 Graphics                      | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 303       | 10.61%  |
| Intel HD Graphics 6000                                                                   | 146       | 5.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 119       | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 113       | 3.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 101       | 3.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 90        | 3.15%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 85        | 2.98%   |
| Intel UHD Graphics 620                                                                   | 72        | 2.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 69        | 2.42%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 64        | 2.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 61        | 2.14%   |
| AMD Renoir                                                                               | 60        | 2.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 57        | 2%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 55        | 1.93%   |
| Intel HD Graphics 620                                                                    | 51        | 1.79%   |
| Intel HD Graphics 5500                                                                   | 49        | 1.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 48        | 1.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 48        | 1.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 48        | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 47        | 1.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 43        | 1.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 43        | 1.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 39        | 1.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 36        | 1.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 36        | 1.26%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 35        | 1.23%   |
| AMD Lucienne                                                                             | 32        | 1.12%   |
| AMD Cezanne                                                                              | 29        | 1.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 0.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 24        | 0.84%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 22        | 0.77%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 21        | 0.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 21        | 0.74%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 20        | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 19        | 0.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 19        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 17        | 0.6%    |
| Intel HD Graphics 530                                                                    | 17        | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 16        | 0.56%   |
| Nvidia TU117M                                                                            | 16        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1243      | 53.6%   |
| 1 x Nvidia      | 356       | 15.35%  |
| 1 x AMD         | 301       | 12.98%  |
| Intel + Nvidia  | 289       | 12.46%  |
| Intel + AMD     | 55        | 2.37%   |
| AMD + Nvidia    | 39        | 1.68%   |
| 2 x AMD         | 25        | 1.08%   |
| Other           | 7         | 0.3%    |
| 1 x SiS         | 2         | 0.09%   |
| 1 x VIA         | 1         | 0.04%   |
| 1 x S3 Graphics | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2015      | 86.55%  |
| Unknown     | 183       | 7.86%   |
| Proprietary | 130       | 5.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1649      | 70.59%  |
| 0.01-0.5   | 477       | 20.42%  |
| 1.01-2.0   | 83        | 3.55%   |
| 3.01-4.0   | 59        | 2.53%   |
| 0.51-1.0   | 51        | 2.18%   |
| 7.01-8.0   | 7         | 0.3%    |
| 5.01-6.0   | 7         | 0.3%    |
| 2.01-3.0   | 2         | 0.09%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Apple                   | 555       | 22.79%  |
| AU Optronics            | 364       | 14.95%  |
| BOE                     | 319       | 13.1%   |
| LG Display              | 247       | 10.14%  |
| Chimei Innolux          | 247       | 10.14%  |
| Samsung Electronics     | 160       | 6.57%   |
| Lenovo                  | 53        | 2.18%   |
| Sharp                   | 49        | 2.01%   |
| Dell                    | 42        | 1.72%   |
| Goldstar                | 40        | 1.64%   |
| Chi Mei Optoelectronics | 36        | 1.48%   |
| BenQ                    | 28        | 1.15%   |
| InfoVision              | 24        | 0.99%   |
| Hewlett-Packard         | 24        | 0.99%   |
| PANDA                   | 21        | 0.86%   |
| HannStar                | 19        | 0.78%   |
| Unknown                 | 17        | 0.7%    |
| Philips                 | 16        | 0.66%   |
| Ancor Communications    | 16        | 0.66%   |
| AOC                     | 15        | 0.62%   |
| LG Philips              | 14        | 0.57%   |
| Iiyama                  | 12        | 0.49%   |
| ViewSonic               | 11        | 0.45%   |
| Acer                    | 11        | 0.45%   |
| CSO                     | 10        | 0.41%   |
| Sony                    | 6         | 0.25%   |
| CPT                     | 5         | 0.21%   |
| Quanta Display          | 4         | 0.16%   |
| Pixio                   | 4         | 0.16%   |
| Panasonic               | 4         | 0.16%   |
| NEC Computers           | 4         | 0.16%   |
| Eizo                    | 4         | 0.16%   |
| Toshiba                 | 3         | 0.12%   |
| TMX                     | 3         | 0.12%   |
| MSI                     | 3         | 0.12%   |
| AGO                     | 3         | 0.12%   |
| ___                     | 2         | 0.08%   |
| SLD                     | 2         | 0.08%   |
| Mi                      | 2         | 0.08%   |
| InnoLux Display         | 2         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                      | 199       | 8.11%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 149       | 6.07%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 52        | 2.12%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 41        | 1.67%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 40        | 1.63%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                      | 35        | 1.43%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 34        | 1.39%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 24        | 0.98%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 23        | 0.94%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 21        | 0.86%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                      | 21        | 0.86%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 20        | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 16        | 0.65%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 15        | 0.61%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 15        | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 14        | 0.57%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 13        | 0.53%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                      | 13        | 0.53%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 11        | 0.45%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 11        | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch      | 10        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 10        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 10        | 0.41%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 9         | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 9         | 0.37%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch               | 8         | 0.33%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                     | 8         | 0.33%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 8         | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 7         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 7         | 0.29%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                      | 7         | 0.29%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 6         | 0.24%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch               | 6         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 765       | 33.05%  |
| 1366x768 (WXGA)    | 617       | 26.65%  |
| 1280x800 (WXGA)    | 442       | 19.09%  |
| 1440x900 (WXGA+)   | 97        | 4.19%   |
| 1600x900 (HD+)     | 90        | 3.89%   |
| 3840x2160 (4K)     | 56        | 2.42%   |
| 2560x1440 (QHD)    | 44        | 1.9%    |
| 1920x1200 (WUXGA)  | 36        | 1.56%   |
| 1024x600           | 32        | 1.38%   |
| 1280x1024 (SXGA)   | 17        | 0.73%   |
| 2560x1600          | 15        | 0.65%   |
| 2288x1287          | 15        | 0.65%   |
| 1024x768 (XGA)     | 11        | 0.48%   |
| 1680x1050 (WSXGA+) | 10        | 0.43%   |
| 1360x768           | 10        | 0.43%   |
| 2880x1800          | 8         | 0.35%   |
| 2560x1080          | 8         | 0.35%   |
| 3840x2400          | 7         | 0.3%    |
| 2160x1440          | 6         | 0.26%   |
| 3440x1440          | 5         | 0.22%   |
| 3840x1100          | 2         | 0.09%   |
| 3840x1080          | 2         | 0.09%   |
| 3200x1800 (QHD+)   | 2         | 0.09%   |
| 2256x1504          | 2         | 0.09%   |
| 1600x1200          | 2         | 0.09%   |
| 1400x1050          | 2         | 0.09%   |
| Unknown            | 2         | 0.09%   |
| 3840x1600          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 2880x1920          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2048x1152          | 1         | 0.04%   |
| 1920x515           | 1         | 0.04%   |
| 1920x1280          | 1         | 0.04%   |
| 1792x768           | 1         | 0.04%   |
| 1024x576           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 741       | 30.49%  |
| 15      | 639       | 26.3%   |
| 14      | 256       | 10.53%  |
| 11      | 217       | 8.93%   |
| 17      | 103       | 4.24%   |
| 12      | 78        | 3.21%   |
| 24      | 73        | 3%      |
| 27      | 50        | 2.06%   |
| 23      | 50        | 2.06%   |
| 21      | 45        | 1.85%   |
| 10      | 31        | 1.28%   |
| 19      | 19        | 0.78%   |
| 18      | 17        | 0.7%    |
| 142     | 15        | 0.62%   |
| Unknown | 13        | 0.53%   |
| 31      | 12        | 0.49%   |
| 16      | 10        | 0.41%   |
| 34      | 7         | 0.29%   |
| 25      | 7         | 0.29%   |
| 32      | 6         | 0.25%   |
| 22      | 6         | 0.25%   |
| 29      | 5         | 0.21%   |
| 20      | 5         | 0.21%   |
| 72      | 4         | 0.16%   |
| 40      | 3         | 0.12%   |
| 84      | 2         | 0.08%   |
| 54      | 2         | 0.08%   |
| 52      | 2         | 0.08%   |
| 28      | 2         | 0.08%   |
| 8       | 2         | 0.08%   |
| 55      | 1         | 0.04%   |
| 49      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |
| 43      | 1         | 0.04%   |
| 37      | 1         | 0.04%   |
| 33      | 1         | 0.04%   |
| 26      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1053      | 43.66%  |
| 201-300        | 902       | 37.4%   |
| 501-600        | 163       | 6.76%   |
| 351-400        | 120       | 4.98%   |
| 401-500        | 84        | 3.48%   |
| 601-700        | 28        | 1.16%   |
| More than 2000 | 15        | 0.62%   |
| 701-800        | 13        | 0.54%   |
| Unknown        | 13        | 0.54%   |
| 1001-1500      | 9         | 0.37%   |
| 1501-2000      | 6         | 0.25%   |
| 801-900        | 4         | 0.17%   |
| 101-200        | 2         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1495      | 67.86%  |
| 16/10   | 621       | 28.19%  |
| 5/4     | 17        | 0.77%   |
| 4/3     | 17        | 0.77%   |
| 1.00    | 15        | 0.68%   |
| 3/2     | 14        | 0.64%   |
| 21/9    | 10        | 0.45%   |
| Unknown | 5         | 0.23%   |
| 2.65    | 4         | 0.18%   |
| 3.40    | 2         | 0.09%   |
| 32/9    | 1         | 0.05%   |
| 3.73    | 1         | 0.05%   |
| 3.20    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 833       | 34.38%  |
| 101-110        | 642       | 26.5%   |
| 51-60          | 219       | 9.04%   |
| 71-80          | 161       | 6.64%   |
| 201-250        | 138       | 5.7%    |
| 121-130        | 83        | 3.43%   |
| 61-70          | 74        | 3.05%   |
| 301-350        | 50        | 2.06%   |
| 251-300        | 35        | 1.44%   |
| 151-200        | 33        | 1.36%   |
| 41-50          | 31        | 1.28%   |
| 351-500        | 28        | 1.16%   |
| More than 1000 | 26        | 1.07%   |
| 141-150        | 26        | 1.07%   |
| Unknown        | 13        | 0.54%   |
| 131-140        | 10        | 0.41%   |
| 501-1000       | 7         | 0.29%   |
| 91-100         | 7         | 0.29%   |
| 111-120        | 5         | 0.21%   |
| 1-40           | 2         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1015      | 42.58%  |
| 101-120       | 878       | 36.83%  |
| 51-100        | 289       | 12.12%  |
| 161-240       | 117       | 4.91%   |
| More than 240 | 42        | 1.76%   |
| 1-50          | 30        | 1.26%   |
| Unknown       | 13        | 0.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1841      | 78.61%  |
| 2     | 289       | 12.34%  |
| 0     | 181       | 7.73%   |
| 3     | 30        | 1.28%   |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1042      | 27.83%  |
| Realtek Semiconductor             | 917       | 24.49%  |
| Broadcom                          | 479       | 12.79%  |
| Qualcomm Atheros                  | 433       | 11.57%  |
| Nvidia                            | 312       | 8.33%   |
| Broadcom Limited                  | 188       | 5.02%   |
| Marvell Technology Group          | 101       | 2.7%    |
| Ralink                            | 27        | 0.72%   |
| MediaTek                          | 25        | 0.67%   |
| TP-Link                           | 21        | 0.56%   |
| ASIX Electronics                  | 19        | 0.51%   |
| Dell                              | 16        | 0.43%   |
| Samsung Electronics               | 15        | 0.4%    |
| Sierra Wireless                   | 14        | 0.37%   |
| Ralink Technology                 | 11        | 0.29%   |
| Qualcomm                          | 11        | 0.29%   |
| DisplayLink                       | 11        | 0.29%   |
| Lenovo                            | 8         | 0.21%   |
| JMicron Technology                | 8         | 0.21%   |
| Xiaomi                            | 6         | 0.16%   |
| Cypress Semiconductor             | 6         | 0.16%   |
| ICS Advent                        | 5         | 0.13%   |
| Huawei Technologies               | 5         | 0.13%   |
| Hewlett-Packard                   | 5         | 0.13%   |
| FIBOCOM                           | 5         | 0.13%   |
| Ericsson Business Mobile Networks | 5         | 0.13%   |
| Qualcomm Atheros Communications   | 4         | 0.11%   |
| NetGear                           | 4         | 0.11%   |
| Attansic Technology               | 4         | 0.11%   |
| ASUSTek Computer                  | 4         | 0.11%   |
| AMD                               | 4         | 0.11%   |
| Microchip Technology              | 3         | 0.08%   |
| Apple                             | 3         | 0.08%   |
| ULi Electronics                   | 2         | 0.05%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.05%   |
| National Semiconductor            | 2         | 0.05%   |
| Motorola PCS                      | 2         | 0.05%   |
| D-Link                            | 2         | 0.05%   |
| Z-Com                             | 1         | 0.03%   |
| Winbond Electronics               | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 583       | 13.44%  |
| Nvidia MCP79 Ethernet                                                                 | 306       | 7.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 304       | 7.01%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 149       | 3.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 146       | 3.36%   |
| Intel Wireless 7260                                                                   | 116       | 2.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 111       | 2.56%   |
| Intel Wireless 8265 / 8275                                                            | 91        | 2.1%    |
| Intel Wi-Fi 6 AX201                                                                   | 85        | 1.96%   |
| Intel Wi-Fi 6 AX200                                                                   | 81        | 1.87%   |
| Intel Wireless 7265                                                                   | 79        | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 75        | 1.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 69        | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 62        | 1.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 58        | 1.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 56        | 1.29%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 56        | 1.29%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 55        | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 52        | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 52        | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 46        | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 45        | 1.04%   |
| Intel Wireless 8260                                                                   | 43        | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 42        | 0.97%   |
| Intel Ethernet Connection (4) I219-V                                                  | 39        | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                                        | 34        | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 31        | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 31        | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 28        | 0.65%   |
| Intel Wireless 3165                                                                   | 24        | 0.55%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 24        | 0.55%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 23        | 0.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 22        | 0.51%   |
| Intel Ethernet Connection I219-LM                                                     | 22        | 0.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 21        | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 21        | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 21        | 0.48%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 20        | 0.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 19        | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                 | 19        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 995       | 42.02%  |
| Broadcom                          | 423       | 17.86%  |
| Qualcomm Atheros                  | 400       | 16.89%  |
| Realtek Semiconductor             | 259       | 10.94%  |
| Broadcom Limited                  | 171       | 7.22%   |
| Ralink                            | 27        | 1.14%   |
| MediaTek                          | 24        | 1.01%   |
| Sierra Wireless                   | 14        | 0.59%   |
| Ralink Technology                 | 11        | 0.46%   |
| TP-Link                           | 9         | 0.38%   |
| Dell                              | 8         | 0.34%   |
| Fibocom                           | 5         | 0.21%   |
| Qualcomm Atheros Communications   | 4         | 0.17%   |
| Qualcomm                          | 4         | 0.17%   |
| NetGear                           | 4         | 0.17%   |
| ASUSTek Computer                  | 4         | 0.17%   |
| Z-Com                             | 1         | 0.04%   |
| Wilocity                          | 1         | 0.04%   |
| Ericsson Business Mobile Networks | 1         | 0.04%   |
| Edimax Technology                 | 1         | 0.04%   |
| Belkin Components                 | 1         | 0.04%   |
| 3Com                              | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 304       | 12.79%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 149       | 6.27%   |
| Intel Wireless 7260                                                                   | 116       | 4.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 111       | 4.67%   |
| Intel Wireless 8265 / 8275                                                            | 91        | 3.83%   |
| Intel Wi-Fi 6 AX201                                                                   | 85        | 3.58%   |
| Intel Wi-Fi 6 AX200                                                                   | 81        | 3.41%   |
| Intel Wireless 7265                                                                   | 79        | 3.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 62        | 2.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 58        | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 56        | 2.36%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 55        | 2.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 52        | 2.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 52        | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 46        | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 45        | 1.89%   |
| Intel Wireless 8260                                                                   | 43        | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 42        | 1.77%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 34        | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 31        | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 31        | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 28        | 1.18%   |
| Intel Wireless 3165                                                                   | 24        | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 24        | 1.01%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 23        | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 21        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 20        | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 19        | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 19        | 0.8%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 19        | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 19        | 0.8%    |
| Intel Wireless 3160                                                                   | 18        | 0.76%   |
| Intel Centrino Advanced-N 6200                                                        | 18        | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 17        | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 17        | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 15        | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 14        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                                        | 14        | 0.59%   |
| Intel Wireless-AC 9260                                                                | 13        | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 13        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 820       | 43.29%  |
| Intel                            | 376       | 19.85%  |
| Nvidia                           | 312       | 16.47%  |
| Marvell Technology Group         | 101       | 5.33%   |
| Qualcomm Atheros                 | 73        | 3.85%   |
| Broadcom                         | 68        | 3.59%   |
| ASIX Electronics                 | 19        | 1%      |
| Broadcom Limited                 | 18        | 0.95%   |
| Samsung Electronics              | 15        | 0.79%   |
| TP-Link                          | 12        | 0.63%   |
| DisplayLink                      | 11        | 0.58%   |
| Lenovo                           | 8         | 0.42%   |
| JMicron Technology               | 8         | 0.42%   |
| Qualcomm                         | 7         | 0.37%   |
| Xiaomi                           | 6         | 0.32%   |
| Cypress Semiconductor            | 6         | 0.32%   |
| ICS Advent                       | 5         | 0.26%   |
| Attansic Technology              | 4         | 0.21%   |
| Microchip Technology             | 3         | 0.16%   |
| Huawei Technologies              | 3         | 0.16%   |
| Apple                            | 3         | 0.16%   |
| Silicon Integrated Systems [SiS] | 2         | 0.11%   |
| National Semiconductor           | 2         | 0.11%   |
| Motorola PCS                     | 2         | 0.11%   |
| D-Link                           | 2         | 0.11%   |
| VIA Technologies                 | 1         | 0.05%   |
| Spreadtrum Communications        | 1         | 0.05%   |
| OPPO Electronics                 | 1         | 0.05%   |
| MediaTek                         | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Google                           | 1         | 0.05%   |
| Davicom Semiconductor            | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 583       | 30.49%  |
| Nvidia MCP79 Ethernet                                             | 306       | 16%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 146       | 7.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75        | 3.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 69        | 3.61%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 56        | 2.93%   |
| Intel Ethernet Connection (4) I219-V                              | 39        | 2.04%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 22        | 1.15%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 1.1%    |
| Intel Ethernet Connection (3) I218-LM                             | 21        | 1.1%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 19        | 0.99%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.99%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.99%   |
| Intel Ethernet Connection (6) I219-V                              | 18        | 0.94%   |
| Intel Ethernet Connection (13) I219-V                             | 16        | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                     | 14        | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 0.63%   |
| Intel Ethernet Connection (10) I219-V                             | 12        | 0.63%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 11        | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 11        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.58%   |
| Intel Ethernet Connection I219-V                                  | 11        | 0.58%   |
| Intel 82567LM Gigabit Network Connection                          | 11        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 10        | 0.52%   |
| Intel 82566MM Gigabit Network Connection                          | 9         | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.42%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 0.42%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 8         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.37%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 7         | 0.37%   |
| Broadcom BCM4401 100Base-T                                        | 7         | 0.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 0.31%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 6         | 0.31%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.31%   |
| Nvidia MCP89 Ethernet                                             | 6         | 0.31%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 6         | 0.31%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 0.31%   |
| Intel Ethernet Connection (14) I219-LM                            | 6         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2289      | 55%     |
| Ethernet | 1822      | 43.78%  |
| Modem    | 48        | 1.15%   |
| Unknown  | 3         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1808      | 74.22%  |
| Ethernet | 628       | 25.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1668      | 71.96%  |
| 1     | 609       | 26.27%  |
| 3     | 21        | 0.91%   |
| 0     | 19        | 0.82%   |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1976      | 84.77%  |
| Yes  | 355       | 15.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 763       | 38.91%  |
| Apple                           | 544       | 27.74%  |
| Realtek Semiconductor           | 154       | 7.85%   |
| Qualcomm Atheros Communications | 149       | 7.6%    |
| Broadcom                        | 71        | 3.62%   |
| Lite-On Technology              | 67        | 3.42%   |
| IMC Networks                    | 65        | 3.31%   |
| Foxconn / Hon Hai               | 33        | 1.68%   |
| Dell                            | 24        | 1.22%   |
| Cambridge Silicon Radio         | 22        | 1.12%   |
| Hewlett-Packard                 | 18        | 0.92%   |
| Realtek                         | 10        | 0.51%   |
| Ralink                          | 10        | 0.51%   |
| Toshiba                         | 8         | 0.41%   |
| ASUSTek Computer                | 8         | 0.41%   |
| Taiyo Yuden                     | 3         | 0.15%   |
| Ralink Technology               | 3         | 0.15%   |
| Foxconn International           | 3         | 0.15%   |
| MediaTek                        | 2         | 0.1%    |
| Alps Electric                   | 2         | 0.1%    |
| Qcom                            | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 350       | 17.85%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 298       | 15.2%   |
| Apple Bluetooth USB Host Controller                 | 148       | 7.55%   |
| Intel AX201 Bluetooth                               | 147       | 7.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 116       | 5.92%   |
| Realtek Bluetooth Radio                             | 100       | 5.1%    |
| Qualcomm Atheros  Bluetooth Device                  | 96        | 4.9%    |
| Intel AX200 Bluetooth                               | 82        | 4.18%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 3.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 38        | 1.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 28        | 1.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 22        | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 21        | 1.07%   |
| IMC Networks Bluetooth Radio                        | 21        | 1.07%   |
| Apple Bluetooth Host Controller                     | 19        | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 0.87%   |
| Lite-On Bluetooth Device                            | 16        | 0.82%   |
| IMC Networks Bluetooth Device                       | 15        | 0.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 15        | 0.76%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 0.76%   |
| Intel AX210 Bluetooth                               | 13        | 0.66%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.66%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 12        | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 12        | 0.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 11        | 0.56%   |
| Realtek Bluetooth Radio                             | 10        | 0.51%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 0.51%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 9         | 0.46%   |
| IMC Networks Wireless_Device                        | 9         | 0.46%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.46%   |
| Dell BCM20702A0 Bluetooth Module                    | 9         | 0.46%   |
| Lite-On Wireless_Device                             | 7         | 0.36%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 7         | 0.36%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 6         | 0.31%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.31%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 0.31%   |
| Dell DW375 Bluetooth Module                         | 6         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1663      | 63.81%  |
| Nvidia                           | 487       | 18.69%  |
| AMD                              | 344       | 13.2%   |
| C-Media Electronics              | 16        | 0.61%   |
| Logitech                         | 12        | 0.46%   |
| Generalplus Technology           | 9         | 0.35%   |
| Texas Instruments                | 8         | 0.31%   |
| Realtek Semiconductor            | 8         | 0.31%   |
| Plantronics                      | 7         | 0.27%   |
| Lenovo                           | 7         | 0.27%   |
| GN Netcom                        | 6         | 0.23%   |
| Hewlett-Packard                  | 5         | 0.19%   |
| Creative Technology              | 5         | 0.19%   |
| ULi Electronics                  | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| Microsoft                        | 2         | 0.08%   |
| JMTek                            | 2         | 0.08%   |
| CMX Systems                      | 2         | 0.08%   |
| VIA Technologies                 | 1         | 0.04%   |
| Toshiba                          | 1         | 0.04%   |
| Thomann                          | 1         | 0.04%   |
| SteelSeries ApS                  | 1         | 0.04%   |
| Sennheiser Communications        | 1         | 0.04%   |
| SAVITECH                         | 1         | 0.04%   |
| Samsung Electronics              | 1         | 0.04%   |
| RODE Microphones                 | 1         | 0.04%   |
| Razer USA                        | 1         | 0.04%   |
| Pixart Imaging                   | 1         | 0.04%   |
| Microdia                         | 1         | 0.04%   |
| M-Audio                          | 1         | 0.04%   |
| Kingston Technology              | 1         | 0.04%   |
| ESS Technology                   | 1         | 0.04%   |
| Elite Silicon                    | 1         | 0.04%   |
| Elgato Systems                   | 1         | 0.04%   |
| Corsair                          | 1         | 0.04%   |
| ASUSTek Computer                 | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 High Definition Audio                                                                | 307       | 9.6%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 217       | 6.79%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 203       | 6.35%   |
| Intel Broadwell-U Audio Controller                                                                | 200       | 6.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 198       | 6.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 148       | 4.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 124       | 3.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 104       | 3.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 98        | 3.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 96        | 3%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 82        | 2.56%   |
| Intel Cannon Lake PCH cAVS                                                                        | 81        | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 80        | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 59        | 1.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 59        | 1.85%   |
| Intel 8 Series HD Audio Controller                                                                | 59        | 1.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 58        | 1.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 55        | 1.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 55        | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 53        | 1.66%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 51        | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 47        | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 45        | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 42        | 1.31%   |
| AMD FCH Azalia Controller                                                                         | 42        | 1.31%   |
| Intel Comet Lake PCH cAVS                                                                         | 41        | 1.28%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 40        | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 40        | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 27        | 0.84%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 25        | 0.78%   |
| AMD High Definition Audio Controller                                                              | 21        | 0.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 19        | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 17        | 0.53%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 0.53%   |
| Intel CM238 HD Audio Controller                                                                   | 17        | 0.53%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 16        | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 0.5%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 15        | 0.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 0.38%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 11        | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 752       | 32.61%  |
| Samsung Electronics | 597       | 25.89%  |
| Micron Technology   | 220       | 9.54%   |
| Kingston            | 138       | 5.98%   |
| Crucial             | 133       | 5.77%   |
| Unknown             | 119       | 5.16%   |
| Elpida              | 79        | 3.43%   |
| Ramaxel Technology  | 39        | 1.69%   |
| A-DATA Technology   | 39        | 1.69%   |
| Nanya Technology    | 26        | 1.13%   |
| Corsair             | 25        | 1.08%   |
| Unknown             | 23        | 1%      |
| Goodram             | 18        | 0.78%   |
| Team                | 12        | 0.52%   |
| Unknown (ABCD)      | 11        | 0.48%   |
| Smart               | 10        | 0.43%   |
| G.Skill             | 8         | 0.35%   |
| Transcend           | 7         | 0.3%    |
| Patriot             | 5         | 0.22%   |
| ASint Technology    | 4         | 0.17%   |
| Apacer              | 4         | 0.17%   |
| Wilk                | 3         | 0.13%   |
| Unknown (89F7)      | 2         | 0.09%   |
| Teikon              | 2         | 0.09%   |
| Smart Brazil        | 2         | 0.09%   |
| Silicon Power       | 2         | 0.09%   |
| PNY                 | 2         | 0.09%   |
| Neo Forza           | 2         | 0.09%   |
| Infineon            | 2         | 0.09%   |
| Goldkey             | 2         | 0.09%   |
| Avant               | 2         | 0.09%   |
| AMD                 | 2         | 0.09%   |
| 48spaces            | 2         | 0.09%   |
| Unknown (D386)      | 1         | 0.04%   |
| Unknown (08C8)      | 1         | 0.04%   |
| Unifosa             | 1         | 0.04%   |
| SHARETRONIC         | 1         | 0.04%   |
| Sesame              | 1         | 0.04%   |
| Novatech            | 1         | 0.04%   |
| Magnum Tech         | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 256       | 10.68%  |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 2.84%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 61        | 2.54%   |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s         | 60        | 2.5%    |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 43        | 1.79%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 35        | 1.46%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 1.21%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 27        | 1.13%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 1.04%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 24        | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 24        | 1%      |
| Unknown                                                          | 23        | 0.96%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 22        | 0.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 22        | 0.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.83%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 20        | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 18        | 0.75%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.67%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.67%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s             | 16        | 0.67%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 15        | 0.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.63%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 15        | 0.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 13        | 0.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 13        | 0.54%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 0.5%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.5%    |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 12        | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 11        | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.46%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 11        | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 11        | 0.46%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 10        | 0.42%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 10        | 0.42%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 719       | 35.18%  |
| DDR3    | 676       | 33.07%  |
| DDR2    | 446       | 21.82%  |
| LPDDR3  | 69        | 3.38%   |
| LPDDR4  | 57        | 2.79%   |
| SDRAM   | 40        | 1.96%   |
| DDR     | 26        | 1.27%   |
| Unknown | 6         | 0.29%   |
| DRAM    | 4         | 0.2%    |
| DDR5    | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1892      | 92.16%  |
| Row Of Chips | 103       | 5.02%   |
| Unknown      | 33        | 1.61%   |
| Chip         | 21        | 1.02%   |
| DIMM         | 4         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 562       | 25.71%  |
| 8192  | 552       | 25.25%  |
| 1024  | 439       | 20.08%  |
| 2048  | 370       | 16.93%  |
| 16384 | 186       | 8.51%   |
| 32768 | 42        | 1.92%   |
| 512   | 25        | 1.14%   |
| 256   | 10        | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 536       | 24.81%  |
| 2667    | 341       | 15.79%  |
| 800     | 309       | 14.31%  |
| 3200    | 295       | 13.66%  |
| 667     | 120       | 5.56%   |
| 2400    | 110       | 5.09%   |
| 1334    | 76        | 3.52%   |
| 2133    | 69        | 3.19%   |
| 1333    | 65        | 3.01%   |
| Unknown | 46        | 2.13%   |
| 1867    | 29        | 1.34%   |
| 4267    | 27        | 1.25%   |
| 1067    | 27        | 1.25%   |
| 3266    | 22        | 1.02%   |
| 4199    | 14        | 0.65%   |
| 533     | 12        | 0.56%   |
| 333     | 8         | 0.37%   |
| 2048    | 7         | 0.32%   |
| 975     | 7         | 0.32%   |
| 266     | 7         | 0.32%   |
| 8400    | 6         | 0.28%   |
| 4266    | 5         | 0.23%   |
| 1066    | 5         | 0.23%   |
| 1866    | 4         | 0.19%   |
| 400     | 4         | 0.19%   |
| 4800    | 2         | 0.09%   |
| 3733    | 1         | 0.05%   |
| 3000    | 1         | 0.05%   |
| 2933    | 1         | 0.05%   |
| 1639    | 1         | 0.05%   |
| 1596    | 1         | 0.05%   |
| 933     | 1         | 0.05%   |
| 200     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 33.33%  |
| Xerox               | 4         | 26.67%  |
| Brother Industries  | 3         | 20%     |
| Canon               | 2         | 13.33%  |
| Samsung Electronics | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Xerox B205                          | 4         | 26.67%  |
| Samsung ML-2010P Mono Laser Printer | 1         | 6.67%   |
| HP LaserJet 1160 series             | 1         | 6.67%   |
| HP LaserJet 1022                    | 1         | 6.67%   |
| HP Ink Tank 110 series              | 1         | 6.67%   |
| HP DeskJet 2620 All-in-One Printer  | 1         | 6.67%   |
| HP DeskJet 2130 series              | 1         | 6.67%   |
| Canon PIXMA MX920 Series            | 1         | 6.67%   |
| Canon LBP3010/LBP3018/LBP3050       | 1         | 6.67%   |
| Brother PT-9500PC                   | 1         | 6.67%   |
| Brother MFC-L2707DW                 | 1         | 6.67%   |
| Brother HL-L2340D series            | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 4         | 66.67%  |
| Seiko Epson | 2         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                       | 2         | 33.33%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 16.67%  |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 16.67%  |
| Canon CanoScan LIDE 25                        | 1         | 16.67%  |
| Canon CanoScan LiDE 220                       | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 375       | 23.44%  |
| IMC Networks                           | 190       | 11.88%  |
| Acer                                   | 172       | 10.75%  |
| Quanta                                 | 169       | 10.56%  |
| Microdia                               | 124       | 7.75%   |
| Realtek Semiconductor                  | 117       | 7.31%   |
| Sunplus Innovation Technology          | 65        | 4.06%   |
| Cheng Uei Precision Industry (Foxlink) | 57        | 3.56%   |
| Suyin                                  | 48        | 3%      |
| Lite-On Technology                     | 40        | 2.5%    |
| Syntek                                 | 38        | 2.38%   |
| Luxvisions Innotech Limited            | 37        | 2.31%   |
| Apple                                  | 27        | 1.69%   |
| Logitech                               | 21        | 1.31%   |
| Silicon Motion                         | 17        | 1.06%   |
| Alcor Micro                            | 13        | 0.81%   |
| Lenovo                                 | 12        | 0.75%   |
| Ricoh                                  | 10        | 0.63%   |
| Z-Star Microelectronics                | 7         | 0.44%   |
| Sonix Technology                       | 7         | 0.44%   |
| Primax Electronics                     | 5         | 0.31%   |
| ALi                                    | 4         | 0.25%   |
| SunplusIT                              | 3         | 0.19%   |
| Intel                                  | 3         | 0.19%   |
| Importek                               | 3         | 0.19%   |
| Genesys Logic                          | 3         | 0.19%   |
| Sunplus Technology                     | 2         | 0.13%   |
| Samsung Electronics                    | 2         | 0.13%   |
| OmniVision Technologies                | 2         | 0.13%   |
| Mimaki Engineering                     | 2         | 0.13%   |
| Microsoft                              | 2         | 0.13%   |
| Y Media                                | 1         | 0.06%   |
| Unknown                                | 1         | 0.06%   |
| U0AS01A-0                              | 1         | 0.06%   |
| ShineTech                              | 1         | 0.06%   |
| Pixart Imaging                         | 1         | 0.06%   |
| MacroSilicon                           | 1         | 0.06%   |
| LG Electronics                         | 1         | 0.06%   |
| Leap Motion                            | 1         | 0.06%   |
| KYE Systems (Mouse Systems)            | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 120       | 7.45%   |
| Microdia Integrated_Webcam_HD                                  | 69        | 4.29%   |
| Quanta Chromebook HD Camera                                    | 67        | 4.16%   |
| IMC Networks Integrated Camera                                 | 60        | 3.73%   |
| Acer BisonCam, NB Pro                                          | 49        | 3.04%   |
| Acer Integrated Camera                                         | 45        | 2.8%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 42        | 2.61%   |
| Realtek Integrated_Webcam_HD                                   | 35        | 2.17%   |
| Chicony HD Webcam                                              | 35        | 2.17%   |
| Chicony USB2.0 HD UVC WebCam                                   | 23        | 1.43%   |
| Quanta HP TrueVision HD Camera                                 | 21        | 1.3%    |
| IMC Networks USB2.0 VGA UVC WebCam                             | 21        | 1.3%    |
| Syntek Integrated Camera                                       | 20        | 1.24%   |
| Sunplus Integrated_Webcam_HD                                   | 20        | 1.24%   |
| Quanta VGA WebCam                                              | 19        | 1.18%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 18        | 1.12%   |
| Chicony HP HD Camera                                           | 18        | 1.12%   |
| Quanta HD User Facing                                          | 16        | 0.99%   |
| Lite-On Integrated Camera                                      | 16        | 0.99%   |
| Acer SunplusIT Integrated Camera                               | 16        | 0.99%   |
| Realtek USB Camera                                             | 15        | 0.93%   |
| Chicony Chromebook HD Camera                                   | 15        | 0.93%   |
| Chicony HP Webcam                                              | 12        | 0.75%   |
| Acer Lenovo Integrated Webcam                                  | 12        | 0.75%   |
| Luxvisions Innotech Limited HP HD Camera                       | 11        | 0.68%   |
| Lite-On HP HD Camera                                           | 11        | 0.68%   |
| IMC Networks USB 2.0 Camera                                    | 11        | 0.68%   |
| IMC Networks HD Camera                                         | 11        | 0.68%   |
| Chicony Integrated Camera (1280x720@30)                        | 11        | 0.68%   |
| Chicony HD User Facing                                         | 11        | 0.68%   |
| Suyin HP Truevision HD                                         | 10        | 0.62%   |
| Acer Lenovo EasyCamera                                         | 10        | 0.62%   |
| Sunplus HD WebCam                                              | 9         | 0.56%   |
| Realtek USB2.0 HD UVC WebCam                                   | 9         | 0.56%   |
| Quanta HP Webcam                                               | 9         | 0.56%   |
| Quanta HP HD Camera                                            | 9         | 0.56%   |
| Quanta HD WebCam                                               | 9         | 0.56%   |
| Microdia Integrated Webcam                                     | 9         | 0.56%   |
| Chicony Lenovo EasyCamera                                      | 9         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 9         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 118       | 34.71%  |
| Synaptics                  | 103       | 30.29%  |
| Shenzhen Goodix Technology | 50        | 14.71%  |
| AuthenTec                  | 18        | 5.29%   |
| Upek                       | 17        | 5%      |
| Elan Microelectronics      | 15        | 4.41%   |
| LighTuning Technology      | 12        | 3.53%   |
| STMicroelectronics         | 7         | 2.06%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 45        | 13.24%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 35        | 10.29%  |
| Shenzhen Goodix  FingerPrint Device                                        | 28        | 8.24%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 24        | 7.06%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 5.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 5.59%   |
| Unknown                                                                    | 18        | 5.29%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 4.71%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 3.24%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 3.24%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 2.94%   |
| Elan ELAN:Fingerprint                                                      | 10        | 2.94%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 10        | 2.94%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.65%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.47%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.47%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.47%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.47%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.18%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.18%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 1.18%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.88%   |
| Synaptics  WBDI                                                            | 3         | 0.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.59%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.59%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.59%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.59%   |
| AuthenTec AES2810                                                          | 2         | 0.59%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.59%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.59%   |
| Validity Sensors VFS491                                                    | 1         | 0.29%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.29%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.29%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.29%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.29%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.29%   |
| AuthenTec AES1600                                                          | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 58        | 35.15%  |
| Broadcom                  | 55        | 33.33%  |
| Upek                      | 17        | 10.3%   |
| O2 Micro                  | 13        | 7.88%   |
| Lenovo                    | 11        | 6.67%   |
| Yubico.com                | 2         | 1.21%   |
| Gemalto (was Gemplus)     | 2         | 1.21%   |
| Aladdin Knowledge Systems | 2         | 1.21%   |
| SCM Microsystems          | 1         | 0.61%   |
| OmniKey                   | 1         | 0.61%   |
| Clay Logic                | 1         | 0.61%   |
| Cherry                    | 1         | 0.61%   |
| C3PO                      | 1         | 0.61%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 57        | 34.55%  |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 10.91%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 10.3%   |
| Broadcom 58200                                                               | 17        | 10.3%   |
| Broadcom 5880                                                                | 12        | 7.27%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 6.67%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 4.24%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.21%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.21%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.21%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.61%   |
| OmniKey CardMan 4321                                                         | 1         | 0.61%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.61%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.61%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.61%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.61%   |
| C3PO LTC31v2                                                                 | 1         | 0.61%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.61%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.61%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1362      | 58.18%  |
| 1     | 774       | 33.06%  |
| 2     | 163       | 6.96%   |
| 3     | 37        | 1.58%   |
| 4     | 3         | 0.13%   |
| 6     | 1         | 0.04%   |
| 5     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 338       | 28.55%  |
| Graphics card            | 324       | 27.36%  |
| Multimedia controller    | 182       | 15.37%  |
| Chipcard                 | 148       | 12.5%   |
| Net/wireless             | 94        | 7.94%   |
| Bluetooth                | 25        | 2.11%   |
| Storage                  | 16        | 1.35%   |
| Communication controller | 16        | 1.35%   |
| Card reader              | 14        | 1.18%   |
| Camera                   | 9         | 0.76%   |
| Network                  | 4         | 0.34%   |
| Net/ethernet             | 3         | 0.25%   |
| Modem                    | 3         | 0.25%   |
| Unassigned class         | 2         | 0.17%   |
| Sound                    | 2         | 0.17%   |
| Flash memory             | 2         | 0.17%   |
| Tv card                  | 1         | 0.08%   |
| Firewire controller      | 1         | 0.08%   |

