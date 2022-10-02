Debian - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 5241

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
| HUAWEI        | KLVL-WXXW                   | [fd8b95bb3b](https://linux-hardware.org/?probe=fd8b95bb3b) | Sep 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | [0453cd781f](https://linux-hardware.org/?probe=0453cd781f) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | [973307d03b](https://linux-hardware.org/?probe=973307d03b) | Sep 28, 2022 |
| Acer          | Aspire A315-23G             | [3eaaf54d1b](https://linux-hardware.org/?probe=3eaaf54d1b) | Sep 28, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [ca9c7bf57b](https://linux-hardware.org/?probe=ca9c7bf57b) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | [730653ea29](https://linux-hardware.org/?probe=730653ea29) | Sep 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fb2de59c3f](https://linux-hardware.org/?probe=fb2de59c3f) | Sep 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [70f86aa587](https://linux-hardware.org/?probe=70f86aa587) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E752               | [f4e2b14498](https://linux-hardware.org/?probe=f4e2b14498) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [4f58ff1174](https://linux-hardware.org/?probe=4f58ff1174) | Sep 26, 2022 |
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
| Lenovo        | ThinkPad T420 4236WS7       | [23f425e425](https://linux-hardware.org/?probe=23f425e425) | Sep 24, 2022 |
| Dell          | Inspiron 14 5425            | [209be443ac](https://linux-hardware.org/?probe=209be443ac) | Sep 24, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [f3527878e5](https://linux-hardware.org/?probe=f3527878e5) | Sep 24, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | [89a019875a](https://linux-hardware.org/?probe=89a019875a) | Sep 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [6cdacdb935](https://linux-hardware.org/?probe=6cdacdb935) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| Dell          | Latitude 3320               | [3296a12784](https://linux-hardware.org/?probe=3296a12784) | Sep 24, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | [0adb7bc0b1](https://linux-hardware.org/?probe=0adb7bc0b1) | Sep 24, 2022 |
| VIT           | P2402                       | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [40b47d9065](https://linux-hardware.org/?probe=40b47d9065) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Google        | Garg360                     | [4772493ae3](https://linux-hardware.org/?probe=4772493ae3) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | [e17fb419bd](https://linux-hardware.org/?probe=e17fb419bd) | Sep 23, 2022 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | [077c05c78d](https://linux-hardware.org/?probe=077c05c78d) | Sep 23, 2022 |
| Acer          | Aspire ES1-732              | [d6ccc5301b](https://linux-hardware.org/?probe=d6ccc5301b) | Sep 23, 2022 |
| Dell          | XPS 15 9520                 | [1a7e610c32](https://linux-hardware.org/?probe=1a7e610c32) | Sep 23, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [f77dda559d](https://linux-hardware.org/?probe=f77dda559d) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [c9457ee571](https://linux-hardware.org/?probe=c9457ee571) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [412296c83f](https://linux-hardware.org/?probe=412296c83f) | Sep 22, 2022 |
| Dell          | Vostro 15 5510              | [5488a2b9ff](https://linux-hardware.org/?probe=5488a2b9ff) | Sep 22, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [db6f733994](https://linux-hardware.org/?probe=db6f733994) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [21ba0d8f46](https://linux-hardware.org/?probe=21ba0d8f46) | Sep 22, 2022 |
| Lenovo        | ThinkPad X220 4291G26       | [33654dfbfa](https://linux-hardware.org/?probe=33654dfbfa) | Sep 22, 2022 |
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
| Framework     | Laptop (12th Gen Intel C... | [69d5dcb9b7](https://linux-hardware.org/?probe=69d5dcb9b7) | Sep 21, 2022 |
| Avell High... | B.ON                        | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| Dell          | Latitude 7530               | [39b655888c](https://linux-hardware.org/?probe=39b655888c) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| Dell          | Precision 7540              | [fb7472fe87](https://linux-hardware.org/?probe=fb7472fe87) | Sep 21, 2022 |
| Dell          | Inspiron MP061              | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [0ada4a5b83](https://linux-hardware.org/?probe=0ada4a5b83) | Sep 20, 2022 |
| HP            | Folio 13                    | [eafa8204e9](https://linux-hardware.org/?probe=eafa8204e9) | Sep 20, 2022 |
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
| MSI           | Prestige 14Evo A11M         | [4b412dd569](https://linux-hardware.org/?probe=4b412dd569) | Sep 19, 2022 |
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
| MSI           | Prestige 14Evo A11M         | [f474823b5a](https://linux-hardware.org/?probe=f474823b5a) | Sep 17, 2022 |
| Dell          | Latitude E7440              | [5194c92c15](https://linux-hardware.org/?probe=5194c92c15) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [6c5b0c0659](https://linux-hardware.org/?probe=6c5b0c0659) | Sep 17, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [1fa176a244](https://linux-hardware.org/?probe=1fa176a244) | Sep 17, 2022 |
| Dell          | Latitude E6330              | [eb58d87a1d](https://linux-hardware.org/?probe=eb58d87a1d) | Sep 17, 2022 |
| Dell          | Latitude E6330              | [a5b11eaaaf](https://linux-hardware.org/?probe=a5b11eaaaf) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [8c355ea88e](https://linux-hardware.org/?probe=8c355ea88e) | Sep 17, 2022 |
| HP            | Notebook                    | [9fcfcab16e](https://linux-hardware.org/?probe=9fcfcab16e) | Sep 17, 2022 |
| HP            | Unknown                     | [e87c925eb0](https://linux-hardware.org/?probe=e87c925eb0) | Sep 16, 2022 |
| Dell          | Latitude E5540              | [8e44a11e6c](https://linux-hardware.org/?probe=8e44a11e6c) | Sep 16, 2022 |
| Dell          | Latitude E5540              | [c2d57deba4](https://linux-hardware.org/?probe=c2d57deba4) | Sep 16, 2022 |
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
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4c33a54701](https://linux-hardware.org/?probe=4c33a54701) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [a1f16914f7](https://linux-hardware.org/?probe=a1f16914f7) | Sep 16, 2022 |
| Aquarius      | NS585                       | [249e3f9a7c](https://linux-hardware.org/?probe=249e3f9a7c) | Sep 16, 2022 |
| Acer          | Aspire A315-23G             | [283a38bb80](https://linux-hardware.org/?probe=283a38bb80) | Sep 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [14cbf91f0c](https://linux-hardware.org/?probe=14cbf91f0c) | Sep 15, 2022 |
| Google        | Stout                       | [82b966b9ad](https://linux-hardware.org/?probe=82b966b9ad) | Sep 15, 2022 |
| Dell          | Precision 3571              | [01f5d7f7f8](https://linux-hardware.org/?probe=01f5d7f7f8) | Sep 15, 2022 |
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
| Valve         | Jupiter                     | [28bed644da](https://linux-hardware.org/?probe=28bed644da) | Sep 14, 2022 |
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
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [5784c0a7e3](https://linux-hardware.org/?probe=5784c0a7e3) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | [b8665b7aed](https://linux-hardware.org/?probe=b8665b7aed) | Sep 14, 2022 |
| ASUSTek       | K54HR                       | [e65b9d439e](https://linux-hardware.org/?probe=e65b9d439e) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | [22c2adf69b](https://linux-hardware.org/?probe=22c2adf69b) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [c8994c7912](https://linux-hardware.org/?probe=c8994c7912) | Sep 14, 2022 |
| Dell          | Inspiron 15-7568            | [c3b834caec](https://linux-hardware.org/?probe=c3b834caec) | Sep 14, 2022 |
| IPASON        | MaxBook P1X                 | [18d0740712](https://linux-hardware.org/?probe=18d0740712) | Sep 13, 2022 |
| Acer          | Aspire 5742                 | [9c37d390a7](https://linux-hardware.org/?probe=9c37d390a7) | Sep 13, 2022 |
| Google        | Terra                       | [a7150f06c7](https://linux-hardware.org/?probe=a7150f06c7) | Sep 13, 2022 |
| MSI           | Prestige 14Evo A11M         | [5a69611620](https://linux-hardware.org/?probe=5a69611620) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [89339e48f1](https://linux-hardware.org/?probe=89339e48f1) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d39dcbc8ed](https://linux-hardware.org/?probe=d39dcbc8ed) | Sep 13, 2022 |
| MSI           | Prestige 14Evo A11M         | [4c5dc2ec7d](https://linux-hardware.org/?probe=4c5dc2ec7d) | Sep 13, 2022 |
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
| Lenovo        | Legion R7000 2020 82B6      | [1d95c5b6ef](https://linux-hardware.org/?probe=1d95c5b6ef) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| Google        | Reks                        | [28f0932e1a](https://linux-hardware.org/?probe=28f0932e1a) | Sep 12, 2022 |
| Lenovo        | ThinkPad X240 20AL00ETGE    | [95a3df06c9](https://linux-hardware.org/?probe=95a3df06c9) | Sep 12, 2022 |
| Unknown       | Unknown                     | [b686d4f2b7](https://linux-hardware.org/?probe=b686d4f2b7) | Sep 12, 2022 |
| Unknown       | Unknown                     | [5b6bbb71d1](https://linux-hardware.org/?probe=5b6bbb71d1) | Sep 12, 2022 |
| MSI           | Modern 15 A11M              | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| MSI           | GS60 2PE                    | [0164cbee91](https://linux-hardware.org/?probe=0164cbee91) | Sep 12, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [3a6e62d846](https://linux-hardware.org/?probe=3a6e62d846) | Sep 12, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [c18f89b2bb](https://linux-hardware.org/?probe=c18f89b2bb) | Sep 11, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| Dell          | Vostro 3400                 | [06c0b65315](https://linux-hardware.org/?probe=06c0b65315) | Sep 11, 2022 |
| Dell          | Vostro 3400                 | [59d8ed6557](https://linux-hardware.org/?probe=59d8ed6557) | Sep 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [cd49377ddf](https://linux-hardware.org/?probe=cd49377ddf) | Sep 11, 2022 |
| HP            | G42                         | [092b9e2c38](https://linux-hardware.org/?probe=092b9e2c38) | Sep 11, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | [c55fef18c3](https://linux-hardware.org/?probe=c55fef18c3) | Sep 11, 2022 |
| HP            | 255 G8 Notebook PC          | [cca78f4488](https://linux-hardware.org/?probe=cca78f4488) | Sep 11, 2022 |
| Lenovo        | ThinkPad L460 20FVS1BC0S    | [e668edf31d](https://linux-hardware.org/?probe=e668edf31d) | Sep 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5a7c8dfacf](https://linux-hardware.org/?probe=5a7c8dfacf) | Sep 10, 2022 |
| Google        | Treeya                      | [d7a00caa63](https://linux-hardware.org/?probe=d7a00caa63) | Sep 10, 2022 |
| Lenovo        | G50-45 80E3                 | [2f4b4e4203](https://linux-hardware.org/?probe=2f4b4e4203) | Sep 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [823dbe2390](https://linux-hardware.org/?probe=823dbe2390) | Sep 10, 2022 |
| ASUSTek       | X200CA                      | [70c2613095](https://linux-hardware.org/?probe=70c2613095) | Sep 09, 2022 |
| Acer          | AO532h                      | [3ea8a4ba38](https://linux-hardware.org/?probe=3ea8a4ba38) | Sep 09, 2022 |
| Toshiba       | Satellite L40               | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Dell          | Latitude E6330              | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| Dell          | Latitude 3320               | [1ab9888966](https://linux-hardware.org/?probe=1ab9888966) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [92ae6811fa](https://linux-hardware.org/?probe=92ae6811fa) | Sep 09, 2022 |
| HP            | Compaq 8510w                | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [d37b0f4483](https://linux-hardware.org/?probe=d37b0f4483) | Sep 08, 2022 |
| ASUSTek       | K46CB                       | [9449630b6a](https://linux-hardware.org/?probe=9449630b6a) | Sep 08, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [c8f2e1da45](https://linux-hardware.org/?probe=c8f2e1da45) | Sep 08, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [87580733cb](https://linux-hardware.org/?probe=87580733cb) | Sep 08, 2022 |
| Google        | Reks                        | [a171b11595](https://linux-hardware.org/?probe=a171b11595) | Sep 08, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [32ab96441e](https://linux-hardware.org/?probe=32ab96441e) | Sep 08, 2022 |
| ASUSTek       | UX430UAR                    | [478d0564a6](https://linux-hardware.org/?probe=478d0564a6) | Sep 08, 2022 |
| HP            | ProBook 440 G7              | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| ASUSTek       | X441NA                      | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| Acer          | Aspire 5738                 | [141712c674](https://linux-hardware.org/?probe=141712c674) | Sep 07, 2022 |
| Lenovo        | B570e 521524G               | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| HP            | Laptop 17-ca0xxx            | [c65eb0b5c8](https://linux-hardware.org/?probe=c65eb0b5c8) | Sep 07, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [044bee5e0c](https://linux-hardware.org/?probe=044bee5e0c) | Sep 07, 2022 |
| Dell          | XPS 17 9720                 | [b85068c001](https://linux-hardware.org/?probe=b85068c001) | Sep 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [c0e98bf9e5](https://linux-hardware.org/?probe=c0e98bf9e5) | Sep 06, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e3d0a2c84c](https://linux-hardware.org/?probe=e3d0a2c84c) | Sep 06, 2022 |
| Aquarius      | NS585                       | [74e50c07d8](https://linux-hardware.org/?probe=74e50c07d8) | Sep 06, 2022 |
| HP            | ENVY 17                     | [63411dc061](https://linux-hardware.org/?probe=63411dc061) | Sep 06, 2022 |
| Lenovo        | ThinkPad P51s 20HB000URT    | [8214e1ba30](https://linux-hardware.org/?probe=8214e1ba30) | Sep 06, 2022 |
| HP            | ZBook Power 15.6 inch G9... | [f4a0990d22](https://linux-hardware.org/?probe=f4a0990d22) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | [fefa3f4935](https://linux-hardware.org/?probe=fefa3f4935) | Sep 06, 2022 |
| HP            | ProBook 640 G4              | [b76e5a62e8](https://linux-hardware.org/?probe=b76e5a62e8) | Sep 06, 2022 |
| Dell          | XPS 9320                    | [54c8e046a1](https://linux-hardware.org/?probe=54c8e046a1) | Sep 06, 2022 |
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
| HUAWEI        | BOHK-WAX9X                  | [c2cd1091cd](https://linux-hardware.org/?probe=c2cd1091cd) | Sep 04, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [ea93dfd855](https://linux-hardware.org/?probe=ea93dfd855) | Sep 04, 2022 |
| Lenovo        | ThinkPad X230 232438J       | [dca0e2fa77](https://linux-hardware.org/?probe=dca0e2fa77) | Sep 04, 2022 |
| Lenovo        | ThinkPad E450 20DCA087CD    | [26928f83da](https://linux-hardware.org/?probe=26928f83da) | Sep 04, 2022 |
| Dell          | XPS 15 9520                 | [9736522a27](https://linux-hardware.org/?probe=9736522a27) | Sep 03, 2022 |
| HP            | Compaq 8510w                | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| PC Special... | 14 Fusion IV                | [dd9ed93b55](https://linux-hardware.org/?probe=dd9ed93b55) | Sep 03, 2022 |
| HP            | Compaq 6910p                | [0165c7d3c6](https://linux-hardware.org/?probe=0165c7d3c6) | Sep 03, 2022 |
| Chuwi         | LarkBook                    | [351478ee65](https://linux-hardware.org/?probe=351478ee65) | Sep 03, 2022 |
| Aquarius      | NS585                       | [b11a34556d](https://linux-hardware.org/?probe=b11a34556d) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Acer          | Aspire A315-23G             | [9a2200f8f8](https://linux-hardware.org/?probe=9a2200f8f8) | Sep 03, 2022 |
| Valve         | Jupiter                     | [b5c7b2be02](https://linux-hardware.org/?probe=b5c7b2be02) | Sep 03, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [1822ab5853](https://linux-hardware.org/?probe=1822ab5853) | Sep 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [2c5c9d2233](https://linux-hardware.org/?probe=2c5c9d2233) | Sep 02, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [c8bf09dd8d](https://linux-hardware.org/?probe=c8bf09dd8d) | Sep 02, 2022 |
| Aquarius      | NS585                       | [86de3c4954](https://linux-hardware.org/?probe=86de3c4954) | Sep 02, 2022 |
| Dell          | XPS 13 9350                 | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Google        | Enguarde                    | [50369de0be](https://linux-hardware.org/?probe=50369de0be) | Sep 01, 2022 |
| Dell          | Latitude E6330              | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| MSI           | Katana GF66 12UC            | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| Google        | Enguarde                    | [b59a9615cd](https://linux-hardware.org/?probe=b59a9615cd) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [f25f0f5499](https://linux-hardware.org/?probe=f25f0f5499) | Sep 01, 2022 |
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
| ASUSTek       | VivoBook_ASUSLaptop M350... | [7ed4b144d7](https://linux-hardware.org/?probe=7ed4b144d7) | Aug 28, 2022 |
| Apple         | MacBookPro14,1              | [31d4a8fc43](https://linux-hardware.org/?probe=31d4a8fc43) | Aug 28, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| Dell          | XPS 15 7590                 | [9158baf2c0](https://linux-hardware.org/?probe=9158baf2c0) | Aug 28, 2022 |
| Dell          | Latitude 5420               | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| BANGHO        | AERO X2 I1002               | [f24ddb9619](https://linux-hardware.org/?probe=f24ddb9619) | Aug 28, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [a10cbdb73b](https://linux-hardware.org/?probe=a10cbdb73b) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [562d827323](https://linux-hardware.org/?probe=562d827323) | Aug 27, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | [3d1138a71c](https://linux-hardware.org/?probe=3d1138a71c) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c155c4b324](https://linux-hardware.org/?probe=c155c4b324) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | [e4cd019582](https://linux-hardware.org/?probe=e4cd019582) | Aug 27, 2022 |
| HP            | Compaq 6910p                | [894b5297c8](https://linux-hardware.org/?probe=894b5297c8) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8231da35ed](https://linux-hardware.org/?probe=8231da35ed) | Aug 27, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2KU0... | [6500c142f5](https://linux-hardware.org/?probe=6500c142f5) | Aug 27, 2022 |
| Lenovo        | ThinkPad X260 20F5A050IG    | [33b5154a7a](https://linux-hardware.org/?probe=33b5154a7a) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | [634c973e53](https://linux-hardware.org/?probe=634c973e53) | Aug 27, 2022 |
| Dell          | Vostro 15 5510              | [c3d134ca75](https://linux-hardware.org/?probe=c3d134ca75) | Aug 27, 2022 |
| Medion        | Akoya P2213T                | [c8d10c3b3f](https://linux-hardware.org/?probe=c8d10c3b3f) | Aug 27, 2022 |
| Google        | Terra                       | [717b3cc17f](https://linux-hardware.org/?probe=717b3cc17f) | Aug 26, 2022 |
| Google        | Terra                       | [f9856d813e](https://linux-hardware.org/?probe=f9856d813e) | Aug 26, 2022 |
| ASUSTek       | X455LD                      | [5351e31366](https://linux-hardware.org/?probe=5351e31366) | Aug 26, 2022 |
| MSI           | Creator 15 A11UH            | [fdd5e2b26a](https://linux-hardware.org/?probe=fdd5e2b26a) | Aug 26, 2022 |
| Lenovo        | ThinkPad T590 20N4001NUS    | [479ef1a89c](https://linux-hardware.org/?probe=479ef1a89c) | Aug 26, 2022 |
| ASUSTek       | M70Vn                       | [2e84d460f5](https://linux-hardware.org/?probe=2e84d460f5) | Aug 26, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [73c598ebe7](https://linux-hardware.org/?probe=73c598ebe7) | Aug 26, 2022 |
| Lenovo        | ThinkPad T400 2768BM2       | [f2d91055c9](https://linux-hardware.org/?probe=f2d91055c9) | Aug 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [a624a45cda](https://linux-hardware.org/?probe=a624a45cda) | Aug 26, 2022 |
| HP            | ProBook 450 G6              | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [843ee79f1b](https://linux-hardware.org/?probe=843ee79f1b) | Aug 25, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [783495e971](https://linux-hardware.org/?probe=783495e971) | Aug 25, 2022 |
| Google        | Terra                       | [72965945d5](https://linux-hardware.org/?probe=72965945d5) | Aug 25, 2022 |
| Google        | Terra                       | [78436fd3bf](https://linux-hardware.org/?probe=78436fd3bf) | Aug 25, 2022 |
| Apple         | MacBookAir7,2               | [b2dc63405c](https://linux-hardware.org/?probe=b2dc63405c) | Aug 25, 2022 |
| Dell          | Inspiron 600m               | [6acc515c79](https://linux-hardware.org/?probe=6acc515c79) | Aug 25, 2022 |
| Dell          | Latitude 3570               | [287cfa2ce8](https://linux-hardware.org/?probe=287cfa2ce8) | Aug 25, 2022 |
| MSI           | GF63 Thin 10SCSR            | [f3facd36da](https://linux-hardware.org/?probe=f3facd36da) | Aug 24, 2022 |
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
| HP            | EliteBook 820 G1            | [1231c2fabe](https://linux-hardware.org/?probe=1231c2fabe) | Aug 23, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [d0b18cffdb](https://linux-hardware.org/?probe=d0b18cffdb) | Aug 23, 2022 |
| Dell          | Vostro 15 5510              | [3224d8bdcc](https://linux-hardware.org/?probe=3224d8bdcc) | Aug 23, 2022 |
| VANT          | MOOVE3-15                   | [854b7f42d4](https://linux-hardware.org/?probe=854b7f42d4) | Aug 22, 2022 |
| Acer          | Aspire 5742                 | [6692313edb](https://linux-hardware.org/?probe=6692313edb) | Aug 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [0e2b064aed](https://linux-hardware.org/?probe=0e2b064aed) | Aug 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [936ce5ca55](https://linux-hardware.org/?probe=936ce5ca55) | Aug 22, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [aacdd42304](https://linux-hardware.org/?probe=aacdd42304) | Aug 22, 2022 |
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
| Samsung       | 935XDB                      | [a8d4f5e6a0](https://linux-hardware.org/?probe=a8d4f5e6a0) | Aug 20, 2022 |
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
| Lenovo        | ThinkPad Edge E431 62774... | [b7d37d0c4c](https://linux-hardware.org/?probe=b7d37d0c4c) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Dell          | Vostro 3405                 | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Acer          | TravelMate 5620             | [cdb6e6d5d6](https://linux-hardware.org/?probe=cdb6e6d5d6) | Aug 17, 2022 |
| ASUSTek       | K70IJ                       | [99bb1459e7](https://linux-hardware.org/?probe=99bb1459e7) | Aug 17, 2022 |
| Shuttle       | DS437                       | [21e0ca6a77](https://linux-hardware.org/?probe=21e0ca6a77) | Aug 17, 2022 |
| Acer          | Nitro AN515-56              | [c62f8ea53b](https://linux-hardware.org/?probe=c62f8ea53b) | Aug 17, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [57732104cd](https://linux-hardware.org/?probe=57732104cd) | Aug 17, 2022 |
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
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [49e3ff7af1](https://linux-hardware.org/?probe=49e3ff7af1) | Aug 14, 2022 |
| Dell          | Latitude 3320               | [b8e1190875](https://linux-hardware.org/?probe=b8e1190875) | Aug 14, 2022 |
| Dell          | Latitude 3320               | [f489cd4f21](https://linux-hardware.org/?probe=f489cd4f21) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | [fcdd677280](https://linux-hardware.org/?probe=fcdd677280) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | [eeed6b3d08](https://linux-hardware.org/?probe=eeed6b3d08) | Aug 14, 2022 |
| HP            | Compaq 6910p                | [97e8467d4d](https://linux-hardware.org/?probe=97e8467d4d) | Aug 13, 2022 |
| Dell          | Latitude E5430 vPro         | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| Acer          | Aspire A315-23G             | [cdba281a27](https://linux-hardware.org/?probe=cdba281a27) | Aug 13, 2022 |
| HP            | Pavilion g7                 | [34a327329a](https://linux-hardware.org/?probe=34a327329a) | Aug 13, 2022 |
| Apple         | MacBookPro12,1              | [8b417889e1](https://linux-hardware.org/?probe=8b417889e1) | Aug 13, 2022 |
| HP            | Presario CQ56               | [48dfc2da91](https://linux-hardware.org/?probe=48dfc2da91) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | [188bfa465d](https://linux-hardware.org/?probe=188bfa465d) | Aug 13, 2022 |
| Dell          | Latitude E6330              | [b48c021700](https://linux-hardware.org/?probe=b48c021700) | Aug 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [94eb72e4ac](https://linux-hardware.org/?probe=94eb72e4ac) | Aug 13, 2022 |
| HP            | Pavilion Notebook           | [3dd4d44be4](https://linux-hardware.org/?probe=3dd4d44be4) | Aug 12, 2022 |
| Acer          | Aspire A114-33              | [471a1ec71e](https://linux-hardware.org/?probe=471a1ec71e) | Aug 12, 2022 |
| Unknown       | Unknown                     | [84771d9750](https://linux-hardware.org/?probe=84771d9750) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | [ed37ad46b6](https://linux-hardware.org/?probe=ed37ad46b6) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | [2fab557514](https://linux-hardware.org/?probe=2fab557514) | Aug 12, 2022 |
| Dell          | XPS 13 9350                 | [6f828c5743](https://linux-hardware.org/?probe=6f828c5743) | Aug 12, 2022 |
| System76      | Oryx Pro                    | [87b38f5a99](https://linux-hardware.org/?probe=87b38f5a99) | Aug 12, 2022 |
| Apple         | MacBookAir7,2               | [c38e80ade4](https://linux-hardware.org/?probe=c38e80ade4) | Aug 11, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [efd4ec3ee7](https://linux-hardware.org/?probe=efd4ec3ee7) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | [4d052b34a7](https://linux-hardware.org/?probe=4d052b34a7) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [d64d35a05d](https://linux-hardware.org/?probe=d64d35a05d) | Aug 11, 2022 |
| Dell          | Latitude 6430U              | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [23b946fc6d](https://linux-hardware.org/?probe=23b946fc6d) | Aug 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3d7e2cfbcb](https://linux-hardware.org/?probe=3d7e2cfbcb) | Aug 11, 2022 |
| Toshiba       | Satellite M645              | [9fa1e00c24](https://linux-hardware.org/?probe=9fa1e00c24) | Aug 10, 2022 |
| Toshiba       | TECRA R950                  | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| HUAWEI        | BDZ-WXX9                    | [d3d3023a41](https://linux-hardware.org/?probe=d3d3023a41) | Aug 10, 2022 |
| ASUSTek       | X751LJ                      | [5c3767ccc2](https://linux-hardware.org/?probe=5c3767ccc2) | Aug 10, 2022 |
| Dell          | Latitude E6420              | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| HP            | Pavilion g6                 | [5b3f1dcc95](https://linux-hardware.org/?probe=5b3f1dcc95) | Aug 10, 2022 |
| GPU Compan... | GWTC116-2                   | [b92ffbefad](https://linux-hardware.org/?probe=b92ffbefad) | Aug 09, 2022 |
| ASUSTek       | X751LJ                      | [e35689c8f1](https://linux-hardware.org/?probe=e35689c8f1) | Aug 09, 2022 |
| Acer          | Aspire A515-56              | [21fdf57c32](https://linux-hardware.org/?probe=21fdf57c32) | Aug 09, 2022 |
| HP            | EliteBook 725 G3            | [7e36a68724](https://linux-hardware.org/?probe=7e36a68724) | Aug 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [66235597aa](https://linux-hardware.org/?probe=66235597aa) | Aug 09, 2022 |
| NVN-ED01      | Unknown                     | [0a677cad6c](https://linux-hardware.org/?probe=0a677cad6c) | Aug 09, 2022 |
| Dell          | Latitude 3320               | [b99f237d17](https://linux-hardware.org/?probe=b99f237d17) | Aug 09, 2022 |
| Alienware     | m15 R6                      | [675208eaec](https://linux-hardware.org/?probe=675208eaec) | Aug 09, 2022 |
| Dell          | Precision 7720              | [e79faaa4c0](https://linux-hardware.org/?probe=e79faaa4c0) | Aug 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [b8ae818291](https://linux-hardware.org/?probe=b8ae818291) | Aug 08, 2022 |
| Alienware     | m15 R4                      | [d134cf97e4](https://linux-hardware.org/?probe=d134cf97e4) | Aug 08, 2022 |
| Dell          | Latitude E7450              | [f2d8a030f4](https://linux-hardware.org/?probe=f2d8a030f4) | Aug 08, 2022 |
| HP            | EliteBook 725 G3            | [e48eff307c](https://linux-hardware.org/?probe=e48eff307c) | Aug 08, 2022 |
| Acer          | Aspire A315-23G             | [46b74e61f0](https://linux-hardware.org/?probe=46b74e61f0) | Aug 08, 2022 |
| Samsung       | 935XDB                      | [fcfe8368c6](https://linux-hardware.org/?probe=fcfe8368c6) | Aug 08, 2022 |
| Dell          | Latitude E6430              | [17d0fce9e5](https://linux-hardware.org/?probe=17d0fce9e5) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | [b1420b630f](https://linux-hardware.org/?probe=b1420b630f) | Aug 07, 2022 |
| Acer          | Aspire 5738                 | [31d08ab231](https://linux-hardware.org/?probe=31d08ab231) | Aug 07, 2022 |
| Toshiba       | Satellite M645              | [a7225934dc](https://linux-hardware.org/?probe=a7225934dc) | Aug 07, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [19b3f7fe4b](https://linux-hardware.org/?probe=19b3f7fe4b) | Aug 07, 2022 |
| Dell          | Precision 7720              | [db2f868372](https://linux-hardware.org/?probe=db2f868372) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0564acfb6c](https://linux-hardware.org/?probe=0564acfb6c) | Aug 07, 2022 |
| SANTECH       | NHx0DB,DE                   | [1eba623e90](https://linux-hardware.org/?probe=1eba623e90) | Aug 06, 2022 |
| Dell          | XPS 9320                    | [358ffe39cd](https://linux-hardware.org/?probe=358ffe39cd) | Aug 06, 2022 |
| Dell          | XPS 13 9300                 | [b139d0b71f](https://linux-hardware.org/?probe=b139d0b71f) | Aug 06, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [53c997fe1f](https://linux-hardware.org/?probe=53c997fe1f) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d5786b75a3](https://linux-hardware.org/?probe=d5786b75a3) | Aug 05, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [24d8a6228c](https://linux-hardware.org/?probe=24d8a6228c) | Aug 05, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [83c6e58e51](https://linux-hardware.org/?probe=83c6e58e51) | Aug 05, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d12e654f35](https://linux-hardware.org/?probe=d12e654f35) | Aug 05, 2022 |
| HP            | ProBook 430 G5              | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| ASUSTek       | X550CC                      | [9d032c38b4](https://linux-hardware.org/?probe=9d032c38b4) | Aug 05, 2022 |
| ASUSTek       | X550CC                      | [433126127b](https://linux-hardware.org/?probe=433126127b) | Aug 05, 2022 |
| Dell          | XPS 9320                    | [ebc62403a7](https://linux-hardware.org/?probe=ebc62403a7) | Aug 05, 2022 |
| Acer          | Aspire 5315                 | [7be46d4930](https://linux-hardware.org/?probe=7be46d4930) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | [87d90381e1](https://linux-hardware.org/?probe=87d90381e1) | Aug 04, 2022 |
| HP            | EliteBook 8460p             | [7948505598](https://linux-hardware.org/?probe=7948505598) | Aug 04, 2022 |
| ASUSTek       | X75VC                       | [f293c53dec](https://linux-hardware.org/?probe=f293c53dec) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e74155922c](https://linux-hardware.org/?probe=e74155922c) | Aug 04, 2022 |
| Acer          | AO532h                      | [9a35f25fba](https://linux-hardware.org/?probe=9a35f25fba) | Aug 04, 2022 |
| Acer          | Aspire A315-23G             | [52e4d5e94f](https://linux-hardware.org/?probe=52e4d5e94f) | Aug 03, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [7fbe005ec3](https://linux-hardware.org/?probe=7fbe005ec3) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | [5ab3e7f74f](https://linux-hardware.org/?probe=5ab3e7f74f) | Aug 03, 2022 |
| Google        | Droid                       | [15d4518ba0](https://linux-hardware.org/?probe=15d4518ba0) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | [02d4876457](https://linux-hardware.org/?probe=02d4876457) | Aug 03, 2022 |
| ASUSTek       | X756UQK                     | [97b2316a06](https://linux-hardware.org/?probe=97b2316a06) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [8754f8caa3](https://linux-hardware.org/?probe=8754f8caa3) | Aug 03, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [94ccc2e14f](https://linux-hardware.org/?probe=94ccc2e14f) | Aug 03, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [eb77f8f852](https://linux-hardware.org/?probe=eb77f8f852) | Aug 03, 2022 |
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
| Dell          | Latitude 3320               | [183ae38016](https://linux-hardware.org/?probe=183ae38016) | Jul 31, 2022 |
| Dell          | Latitude 3320               | [a849c0d90a](https://linux-hardware.org/?probe=a849c0d90a) | Jul 30, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [9b362907fc](https://linux-hardware.org/?probe=9b362907fc) | Jul 30, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [61aed5ab55](https://linux-hardware.org/?probe=61aed5ab55) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | [1b94bd5797](https://linux-hardware.org/?probe=1b94bd5797) | Jul 29, 2022 |
| Acer          | AO756                       | [8203ac54d7](https://linux-hardware.org/?probe=8203ac54d7) | Jul 29, 2022 |
| ASUSTek       | GL553VE                     | [0bbcd152c5](https://linux-hardware.org/?probe=0bbcd152c5) | Jul 29, 2022 |
| Samsung       | R505                        | [4f92cf3c93](https://linux-hardware.org/?probe=4f92cf3c93) | Jul 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [0121efa569](https://linux-hardware.org/?probe=0121efa569) | Jul 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [bc5b132a8d](https://linux-hardware.org/?probe=bc5b132a8d) | Jul 29, 2022 |
| Lenovo        | ThinkPad L480 20LS002CPB    | [35764371d6](https://linux-hardware.org/?probe=35764371d6) | Jul 29, 2022 |
| HP            | EliteBook 820 G2            | [0735a357ee](https://linux-hardware.org/?probe=0735a357ee) | Jul 28, 2022 |
| Dell          | Latitude E5500              | [ba214335da](https://linux-hardware.org/?probe=ba214335da) | Jul 28, 2022 |
| HP            | Compaq 8510p                | [2a005b06da](https://linux-hardware.org/?probe=2a005b06da) | Jul 28, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [a05f5dc510](https://linux-hardware.org/?probe=a05f5dc510) | Jul 28, 2022 |
| Lenovo        | S21e-20 80M4                | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f062c9d4c7](https://linux-hardware.org/?probe=f062c9d4c7) | Jul 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [87f0eb95eb](https://linux-hardware.org/?probe=87f0eb95eb) | Jul 27, 2022 |
| HP            | Stream Notebook PC 11       | [e3c8a52e5b](https://linux-hardware.org/?probe=e3c8a52e5b) | Jul 27, 2022 |
| Acer          | Aspire A515-43              | [d378021961](https://linux-hardware.org/?probe=d378021961) | Jul 26, 2022 |
| HP            | Notebook                    | [9a4fc65b6a](https://linux-hardware.org/?probe=9a4fc65b6a) | Jul 26, 2022 |
| ASUSTek       | ZenBook UX325UA             | [587ea51239](https://linux-hardware.org/?probe=587ea51239) | Jul 26, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [8aa5207a61](https://linux-hardware.org/?probe=8aa5207a61) | Jul 26, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [fc5bf3cb22](https://linux-hardware.org/?probe=fc5bf3cb22) | Jul 26, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [c0b3aa1bea](https://linux-hardware.org/?probe=c0b3aa1bea) | Jul 26, 2022 |
| HONOR         | BBR-WAX9                    | [afe7a4d56a](https://linux-hardware.org/?probe=afe7a4d56a) | Jul 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [c80bf22d79](https://linux-hardware.org/?probe=c80bf22d79) | Jul 26, 2022 |
| Panasonic     | CF-53SJCZYLM                | [188bf4dcb5](https://linux-hardware.org/?probe=188bf4dcb5) | Jul 26, 2022 |
| Lenovo        | G410 20237                  | [c23a040e55](https://linux-hardware.org/?probe=c23a040e55) | Jul 25, 2022 |
| HP            | Notebook                    | [fdc7478b06](https://linux-hardware.org/?probe=fdc7478b06) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bf2cecb453](https://linux-hardware.org/?probe=bf2cecb453) | Jul 25, 2022 |
| Acer          | Aspire A315-23G             | [df57effbc5](https://linux-hardware.org/?probe=df57effbc5) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e2a1804b90](https://linux-hardware.org/?probe=e2a1804b90) | Jul 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [04737cec4e](https://linux-hardware.org/?probe=04737cec4e) | Jul 24, 2022 |
| Dell          | Latitude E5430 non-vPro     | [f8808faaf0](https://linux-hardware.org/?probe=f8808faaf0) | Jul 24, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [45e79d015c](https://linux-hardware.org/?probe=45e79d015c) | Jul 23, 2022 |
| HP            | ProBook 450 G3              | [288db20204](https://linux-hardware.org/?probe=288db20204) | Jul 23, 2022 |
| Lenovo        | B50-30 80ES                 | [086b4a93eb](https://linux-hardware.org/?probe=086b4a93eb) | Jul 22, 2022 |
| ASUSTek       | X541UVK                     | [fb1513d31e](https://linux-hardware.org/?probe=fb1513d31e) | Jul 21, 2022 |
| Dell          | Latitude 5420               | [51cf24b119](https://linux-hardware.org/?probe=51cf24b119) | Jul 21, 2022 |
| Lenovo        | ThinkPad T490 20N2000FIX    | [a68ebe9c0c](https://linux-hardware.org/?probe=a68ebe9c0c) | Jul 21, 2022 |
| HP            | ZBook 15 G3                 | [758ce4f6b4](https://linux-hardware.org/?probe=758ce4f6b4) | Jul 21, 2022 |
| Unknown       | W1415A                      | [3a2f4f9848](https://linux-hardware.org/?probe=3a2f4f9848) | Jul 21, 2022 |
| Acer          | TravelMate 8371             | [4af529e1c4](https://linux-hardware.org/?probe=4af529e1c4) | Jul 20, 2022 |
| Avell High... | A40 LIV                     | [7a685eedd0](https://linux-hardware.org/?probe=7a685eedd0) | Jul 20, 2022 |
| ASUSTek       | 1215P                       | [3bb44d06d1](https://linux-hardware.org/?probe=3bb44d06d1) | Jul 20, 2022 |
| Dell          | Precision 7760              | [742cb747ef](https://linux-hardware.org/?probe=742cb747ef) | Jul 20, 2022 |
| Lenovo        | G550 2958                   | [caeec900b9](https://linux-hardware.org/?probe=caeec900b9) | Jul 19, 2022 |
| Acer          | Aspire A515-45              | [4189e96860](https://linux-hardware.org/?probe=4189e96860) | Jul 19, 2022 |
| HP            | 255 G8 Notebook PC          | [59e9017400](https://linux-hardware.org/?probe=59e9017400) | Jul 19, 2022 |
| Sony          | VPCEH37FJ                   | [1cc39f5c15](https://linux-hardware.org/?probe=1cc39f5c15) | Jul 19, 2022 |
| Lenovo        | G550 2958                   | [ee73634801](https://linux-hardware.org/?probe=ee73634801) | Jul 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [9d756ec471](https://linux-hardware.org/?probe=9d756ec471) | Jul 18, 2022 |
| HP            | Compaq 6910p                | [e6a5ffa902](https://linux-hardware.org/?probe=e6a5ffa902) | Jul 18, 2022 |
| Dell          | Inspiron 3583               | [6f281be47b](https://linux-hardware.org/?probe=6f281be47b) | Jul 18, 2022 |
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
| ASUSTek       | Zephyrus S GX531GS_GX531... | [28257dbd66](https://linux-hardware.org/?probe=28257dbd66) | Jul 15, 2022 |
| HP            | Unknown                     | [e4ccba30f8](https://linux-hardware.org/?probe=e4ccba30f8) | Jul 15, 2022 |
| Dell          | XPS 13 7390                 | [82b077a668](https://linux-hardware.org/?probe=82b077a668) | Jul 15, 2022 |
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
| HP            | Compaq Presario C700        | [46a0239813](https://linux-hardware.org/?probe=46a0239813) | Jul 11, 2022 |
| Lenovo        | ThinkPad T490 20N3SEYA00    | [3370fd5142](https://linux-hardware.org/?probe=3370fd5142) | Jul 11, 2022 |
| Unknown       | Unknown                     | [1b418731e4](https://linux-hardware.org/?probe=1b418731e4) | Jul 11, 2022 |
| Unknown       | Unknown                     | [40a3dfbb11](https://linux-hardware.org/?probe=40a3dfbb11) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [a42efbead1](https://linux-hardware.org/?probe=a42efbead1) | Jul 11, 2022 |
| HP            | Pavilion g4                 | [96ba266748](https://linux-hardware.org/?probe=96ba266748) | Jul 11, 2022 |
| Fujitsu       | FMVNP7HER                   | [e87161bce7](https://linux-hardware.org/?probe=e87161bce7) | Jul 10, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | [6998a6fb37](https://linux-hardware.org/?probe=6998a6fb37) | Jul 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [0e13eaa824](https://linux-hardware.org/?probe=0e13eaa824) | Jul 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [179ad71f6a](https://linux-hardware.org/?probe=179ad71f6a) | Jul 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [7cfc308ed6](https://linux-hardware.org/?probe=7cfc308ed6) | Jul 10, 2022 |
| Acer          | Aspire A315-23G             | [a2ef844aef](https://linux-hardware.org/?probe=a2ef844aef) | Jul 10, 2022 |
| HUAWEI        | WRTB-WXX9                   | [b7efa7907b](https://linux-hardware.org/?probe=b7efa7907b) | Jul 09, 2022 |
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
| Dell          | Latitude 3120               | [361c9c4fa3](https://linux-hardware.org/?probe=361c9c4fa3) | Jul 06, 2022 |
| HP            | EliteBook 2530p             | [a4b4609db8](https://linux-hardware.org/?probe=a4b4609db8) | Jul 05, 2022 |
| ASUSTek       | G55VW                       | [fa0346f5df](https://linux-hardware.org/?probe=fa0346f5df) | Jul 05, 2022 |
| ASUSTek       | G55VW                       | [832ca8cf45](https://linux-hardware.org/?probe=832ca8cf45) | Jul 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | [422a12c217](https://linux-hardware.org/?probe=422a12c217) | Jul 05, 2022 |
| Dell          | Latitude 5421               | [8a40be5ce5](https://linux-hardware.org/?probe=8a40be5ce5) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [b06bcf591e](https://linux-hardware.org/?probe=b06bcf591e) | Jul 04, 2022 |
| Dell          | Inspiron 5570               | [2a161e0d10](https://linux-hardware.org/?probe=2a161e0d10) | Jul 04, 2022 |
| Unknown       | Unknown                     | [78e8133c88](https://linux-hardware.org/?probe=78e8133c88) | Jul 03, 2022 |
| Dell          | Vostro 3549                 | [d23ff685fc](https://linux-hardware.org/?probe=d23ff685fc) | Jul 03, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [75f07cbe46](https://linux-hardware.org/?probe=75f07cbe46) | Jul 02, 2022 |
| Acer          | Nitro AN517-52              | [3920a80387](https://linux-hardware.org/?probe=3920a80387) | Jul 02, 2022 |
| Unknown       | Unknown                     | [72833df63f](https://linux-hardware.org/?probe=72833df63f) | Jul 02, 2022 |
| Acer          | Nitro AN517-52              | [37fbd3a600](https://linux-hardware.org/?probe=37fbd3a600) | Jul 02, 2022 |
| Medion        | E122X                       | [ccc1d37532](https://linux-hardware.org/?probe=ccc1d37532) | Jul 02, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ad993981af](https://linux-hardware.org/?probe=ad993981af) | Jul 02, 2022 |
| Acer          | Aspire A315-23G             | [6fc80d8654](https://linux-hardware.org/?probe=6fc80d8654) | Jul 02, 2022 |
| Dell          | Vostro 3550                 | [d68e2660b7](https://linux-hardware.org/?probe=d68e2660b7) | Jul 02, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [9b8bb07ff0](https://linux-hardware.org/?probe=9b8bb07ff0) | Jul 01, 2022 |
| ASUSTek       | X756UQK                     | [62595fe324](https://linux-hardware.org/?probe=62595fe324) | Jul 01, 2022 |
| Sony          | VPCEH37FJ                   | [509fe56362](https://linux-hardware.org/?probe=509fe56362) | Jul 01, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [75b3bd3b8c](https://linux-hardware.org/?probe=75b3bd3b8c) | Jun 30, 2022 |
| LG Electro... | A410-G.BC48P1               | [41e6b25be5](https://linux-hardware.org/?probe=41e6b25be5) | Jun 30, 2022 |
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
| Razer         | Blade 15 Base Model (Ear... | [93c43f6ee7](https://linux-hardware.org/?probe=93c43f6ee7) | Jun 28, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | [01fbfc98f8](https://linux-hardware.org/?probe=01fbfc98f8) | Jun 27, 2022 |
| BenQ          | Joybook Lite U102           | [49bbad20bd](https://linux-hardware.org/?probe=49bbad20bd) | Jun 27, 2022 |
| Dell          | Vostro 3550                 | [5c998424fb](https://linux-hardware.org/?probe=5c998424fb) | Jun 27, 2022 |
| HP            | EliteBook 840 G1            | [a1bfc8261f](https://linux-hardware.org/?probe=a1bfc8261f) | Jun 27, 2022 |
| Lenovo        | ThinkPad T470 20HES07J00    | [4be29eb5f1](https://linux-hardware.org/?probe=4be29eb5f1) | Jun 27, 2022 |
| HP            | ProBook 440 G0              | [4dbdbb04d3](https://linux-hardware.org/?probe=4dbdbb04d3) | Jun 27, 2022 |
| Aquarius      | NS585                       | [fd6aad4d1b](https://linux-hardware.org/?probe=fd6aad4d1b) | Jun 27, 2022 |
| Aquarius      | NS585                       | [107a5ae472](https://linux-hardware.org/?probe=107a5ae472) | Jun 27, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [e7f9c90280](https://linux-hardware.org/?probe=e7f9c90280) | Jun 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | [b947b14fe4](https://linux-hardware.org/?probe=b947b14fe4) | Jun 27, 2022 |
| Dell          | Inspiron 13-7378            | [cc5a145cac](https://linux-hardware.org/?probe=cc5a145cac) | Jun 27, 2022 |
| Dell          | Inspiron 13-7378            | [a9fdf3f471](https://linux-hardware.org/?probe=a9fdf3f471) | Jun 26, 2022 |
| Dell          | Latitude E6520              | [3cbcb5e5d5](https://linux-hardware.org/?probe=3cbcb5e5d5) | Jun 26, 2022 |
| Dell          | Inspiron 5502               | [c3e90d4ebd](https://linux-hardware.org/?probe=c3e90d4ebd) | Jun 26, 2022 |
| Acer          | Aspire A114-31              | [8fd4467dfd](https://linux-hardware.org/?probe=8fd4467dfd) | Jun 25, 2022 |
| Dell          | Latitude E6520              | [e4aeec08da](https://linux-hardware.org/?probe=e4aeec08da) | Jun 25, 2022 |
| Lenovo        | Edge 15 80K9                | [9399fd58cc](https://linux-hardware.org/?probe=9399fd58cc) | Jun 25, 2022 |
| Medion        | E16402                      | [1e16a44daa](https://linux-hardware.org/?probe=1e16a44daa) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [e91c32dba7](https://linux-hardware.org/?probe=e91c32dba7) | Jun 25, 2022 |
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
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [0fab4a4228](https://linux-hardware.org/?probe=0fab4a4228) | Jun 21, 2022 |
| HP            | 250 G6 Notebook PC          | [30d0a46d81](https://linux-hardware.org/?probe=30d0a46d81) | Jun 21, 2022 |
| Acer          | Nitro AN515-55              | [b3b8a4d0c8](https://linux-hardware.org/?probe=b3b8a4d0c8) | Jun 21, 2022 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [bd4de35624](https://linux-hardware.org/?probe=bd4de35624) | Jun 20, 2022 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [9dd9dbdaa4](https://linux-hardware.org/?probe=9dd9dbdaa4) | Jun 20, 2022 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [0483d0dd9e](https://linux-hardware.org/?probe=0483d0dd9e) | Jun 20, 2022 |
| ASUSTek       | X556UQK                     | [6ce6e1d459](https://linux-hardware.org/?probe=6ce6e1d459) | Jun 20, 2022 |
| Samsung       | 935XDB                      | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| PC Special... | Standard                    | [ab0d32b043](https://linux-hardware.org/?probe=ab0d32b043) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f013ebb91b](https://linux-hardware.org/?probe=f013ebb91b) | Jun 20, 2022 |
| Aquarius      | NS585                       | [b08de59180](https://linux-hardware.org/?probe=b08de59180) | Jun 20, 2022 |
| Aquarius      | NS585                       | [28e0ced692](https://linux-hardware.org/?probe=28e0ced692) | Jun 20, 2022 |
| Aquarius      | NS585                       | [446cb710dc](https://linux-hardware.org/?probe=446cb710dc) | Jun 20, 2022 |
| Notebook      | NL40_50CU                   | [b0b1068b47](https://linux-hardware.org/?probe=b0b1068b47) | Jun 20, 2022 |
| Chuwi         | LarkBook                    | [881773273b](https://linux-hardware.org/?probe=881773273b) | Jun 19, 2022 |
| Lenovo        | ThinkPad T470 20HD000EUK    | [6cc2ca4099](https://linux-hardware.org/?probe=6cc2ca4099) | Jun 19, 2022 |
| Acer          | Aspire V5-571               | [694dbcacc1](https://linux-hardware.org/?probe=694dbcacc1) | Jun 19, 2022 |
| Dell          | Inspiron 3442               | [b71d801e61](https://linux-hardware.org/?probe=b71d801e61) | Jun 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [bfc7b65dee](https://linux-hardware.org/?probe=bfc7b65dee) | Jun 18, 2022 |
| Dell          | Inspiron 7370               | [e8a53b7f1b](https://linux-hardware.org/?probe=e8a53b7f1b) | Jun 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eb60cda77f](https://linux-hardware.org/?probe=eb60cda77f) | Jun 18, 2022 |
| Acer          | Aspire A315-23G             | [2ec41b35a4](https://linux-hardware.org/?probe=2ec41b35a4) | Jun 18, 2022 |
| ASUSTek       | S550CM                      | [43ddcf21fb](https://linux-hardware.org/?probe=43ddcf21fb) | Jun 17, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [8d56f09226](https://linux-hardware.org/?probe=8d56f09226) | Jun 17, 2022 |
| Acer          | Nitro AN515-51              | [51caf7f2a3](https://linux-hardware.org/?probe=51caf7f2a3) | Jun 16, 2022 |
| TUXEDO        | Aura 15 Gen1                | [cc3a77a798](https://linux-hardware.org/?probe=cc3a77a798) | Jun 16, 2022 |
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
| Dell          | Latitude E5470              | [a4533cfbc7](https://linux-hardware.org/?probe=a4533cfbc7) | Jun 14, 2022 |
| Acer          | Aspire A315-23G             | [b7223cfa1f](https://linux-hardware.org/?probe=b7223cfa1f) | Jun 14, 2022 |
| Dell          | Latitude 3120               | [c5c6eed0d9](https://linux-hardware.org/?probe=c5c6eed0d9) | Jun 14, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [67dece9099](https://linux-hardware.org/?probe=67dece9099) | Jun 13, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [0da40dea6c](https://linux-hardware.org/?probe=0da40dea6c) | Jun 12, 2022 |
| Toshiba       | Satellite A300              | [3bfbcd1181](https://linux-hardware.org/?probe=3bfbcd1181) | Jun 12, 2022 |
| Timi          | A7S                         | [a43809f0a8](https://linux-hardware.org/?probe=a43809f0a8) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [537b26aaf0](https://linux-hardware.org/?probe=537b26aaf0) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | [f7d3ee91c6](https://linux-hardware.org/?probe=f7d3ee91c6) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | [4347d50981](https://linux-hardware.org/?probe=4347d50981) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [ca2c0e822c](https://linux-hardware.org/?probe=ca2c0e822c) | Jun 11, 2022 |
| Acer          | Aspire T5000                | [38e164657d](https://linux-hardware.org/?probe=38e164657d) | Jun 11, 2022 |
| HP            | EliteBook 840 G6            | [f2351bb361](https://linux-hardware.org/?probe=f2351bb361) | Jun 11, 2022 |
| ASUSTek       | N550JK                      | [2c4116c1eb](https://linux-hardware.org/?probe=2c4116c1eb) | Jun 10, 2022 |
| Aquarius      | NS585                       | [bec14fe850](https://linux-hardware.org/?probe=bec14fe850) | Jun 10, 2022 |
| Dell          | Latitude 5310               | [fe0ffed6e4](https://linux-hardware.org/?probe=fe0ffed6e4) | Jun 10, 2022 |
| HP            | EliteBook 850 G3            | [e086b31446](https://linux-hardware.org/?probe=e086b31446) | Jun 10, 2022 |
| Dell          | Latitude E6410              | [6e26870ebe](https://linux-hardware.org/?probe=6e26870ebe) | Jun 10, 2022 |
| HP            | 240 G7                      | [bf52288eb2](https://linux-hardware.org/?probe=bf52288eb2) | Jun 10, 2022 |
| HUAWEI        | NBD-WXX9                    | [b8e097f983](https://linux-hardware.org/?probe=b8e097f983) | Jun 10, 2022 |
| Lenovo        | IdeaPad 5-15IIL05 81YK      | [b194866bb7](https://linux-hardware.org/?probe=b194866bb7) | Jun 10, 2022 |
| ASUSTek       | X541UAK                     | [111ebf5004](https://linux-hardware.org/?probe=111ebf5004) | Jun 09, 2022 |
| HP            | Pavilion 17                 | [f4afc30981](https://linux-hardware.org/?probe=f4afc30981) | Jun 09, 2022 |
| Acer          | Aspire R5-471T              | [d621ad4f4a](https://linux-hardware.org/?probe=d621ad4f4a) | Jun 09, 2022 |
| Unknown       | Unknown                     | [1168cffe7b](https://linux-hardware.org/?probe=1168cffe7b) | Jun 09, 2022 |
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
| Google        | Cave                        | [16183f9a77](https://linux-hardware.org/?probe=16183f9a77) | Jun 07, 2022 |
| Toshiba       | Satellite L850              | [809d0bbd73](https://linux-hardware.org/?probe=809d0bbd73) | Jun 07, 2022 |
| Toshiba       | Satellite L850              | [761d37bd31](https://linux-hardware.org/?probe=761d37bd31) | Jun 06, 2022 |
| Dell          | Latitude E5530 non-vPro     | [e4ba25767a](https://linux-hardware.org/?probe=e4ba25767a) | Jun 06, 2022 |
| Aquarius      | NS585                       | [7325c6d9c0](https://linux-hardware.org/?probe=7325c6d9c0) | Jun 06, 2022 |
| Aquarius      | NS585                       | [b2905bee15](https://linux-hardware.org/?probe=b2905bee15) | Jun 06, 2022 |
| Insyde        | GeminiLake                  | [4f2f6240b1](https://linux-hardware.org/?probe=4f2f6240b1) | Jun 06, 2022 |
| Insyde        | GeminiLake                  | [1c308cac35](https://linux-hardware.org/?probe=1c308cac35) | Jun 05, 2022 |
| Unknown       | Unknown                     | [a6ac5e74e9](https://linux-hardware.org/?probe=a6ac5e74e9) | Jun 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [721f0da2de](https://linux-hardware.org/?probe=721f0da2de) | Jun 05, 2022 |
| Dell          | Latitude E6400              | [e4f54892c2](https://linux-hardware.org/?probe=e4f54892c2) | Jun 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f3bdd4cf82](https://linux-hardware.org/?probe=f3bdd4cf82) | Jun 05, 2022 |
| HP            | 250 G7 Notebook PC          | [ab5f939022](https://linux-hardware.org/?probe=ab5f939022) | Jun 04, 2022 |
| HP            | 250 G7 Notebook PC          | [f2ad368041](https://linux-hardware.org/?probe=f2ad368041) | Jun 04, 2022 |
| HP            | 250 G7 Notebook PC          | [1053e6f6d2](https://linux-hardware.org/?probe=1053e6f6d2) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [d147abfc52](https://linux-hardware.org/?probe=d147abfc52) | Jun 04, 2022 |
| Dell          | Vostro 3480                 | [31825ebb84](https://linux-hardware.org/?probe=31825ebb84) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [eaad038fde](https://linux-hardware.org/?probe=eaad038fde) | Jun 03, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9533388943](https://linux-hardware.org/?probe=9533388943) | Jun 03, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [2b704f7e81](https://linux-hardware.org/?probe=2b704f7e81) | Jun 03, 2022 |
| HP            | 250 G7 Notebook PC          | [e6fc1445a0](https://linux-hardware.org/?probe=e6fc1445a0) | Jun 03, 2022 |
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
| HP            | OMEN Laptop 15-ek0xxx       | [5a584e3f70](https://linux-hardware.org/?probe=5a584e3f70) | Jun 01, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [1e3f021750](https://linux-hardware.org/?probe=1e3f021750) | Jun 01, 2022 |
| Dell          | Inspiron 5749               | [408e42beb8](https://linux-hardware.org/?probe=408e42beb8) | Jun 01, 2022 |
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
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e72ac27af1](https://linux-hardware.org/?probe=e72ac27af1) | May 30, 2022 |
| Notebook      | W65_67SJ                    | [2f6d77befb](https://linux-hardware.org/?probe=2f6d77befb) | May 29, 2022 |
| Lenovo        | ThinkPad W500 4061W8H       | [db9160e089](https://linux-hardware.org/?probe=db9160e089) | May 29, 2022 |
| Dell          | Vostro 3546                 | [3acd5d4cb0](https://linux-hardware.org/?probe=3acd5d4cb0) | May 28, 2022 |
| ASUSTek       | 900                         | [e50c30c38d](https://linux-hardware.org/?probe=e50c30c38d) | May 28, 2022 |
| ASUSTek       | 900                         | [dfd6af657c](https://linux-hardware.org/?probe=dfd6af657c) | May 28, 2022 |
| Dell          | Vostro 5490                 | [56ffa50c5b](https://linux-hardware.org/?probe=56ffa50c5b) | May 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [24fc1b394e](https://linux-hardware.org/?probe=24fc1b394e) | May 27, 2022 |
| HP            | Notebook                    | [9900044e89](https://linux-hardware.org/?probe=9900044e89) | May 27, 2022 |
| HP            | 255 G8 Notebook PC          | [9430147fab](https://linux-hardware.org/?probe=9430147fab) | May 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d2581e2c05](https://linux-hardware.org/?probe=d2581e2c05) | May 27, 2022 |
| MSI           | Katana GF66 11UD            | [f3ee20f625](https://linux-hardware.org/?probe=f3ee20f625) | May 27, 2022 |
| HP            | Pavilion g6                 | [0e98027e39](https://linux-hardware.org/?probe=0e98027e39) | May 26, 2022 |
| Dell          | Latitude 3520               | [6c5618416d](https://linux-hardware.org/?probe=6c5618416d) | May 26, 2022 |
| ASUSTek       | K43E                        | [968007a0a9](https://linux-hardware.org/?probe=968007a0a9) | May 26, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [9ebff03a43](https://linux-hardware.org/?probe=9ebff03a43) | May 26, 2022 |
| Dell          | Inspiron 1420               | [4ca4bb715c](https://linux-hardware.org/?probe=4ca4bb715c) | May 26, 2022 |
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
| Acer          | Aspire A715-42G             | [b343d4e9b9](https://linux-hardware.org/?probe=b343d4e9b9) | May 25, 2022 |
| Acer          | Aspire A715-42G             | [89a48429dc](https://linux-hardware.org/?probe=89a48429dc) | May 25, 2022 |
| Acer          | Aspire A315-23              | [dd46d19f05](https://linux-hardware.org/?probe=dd46d19f05) | May 25, 2022 |
| MSI           | GP62MVR 6RF                 | [1dd5741ea8](https://linux-hardware.org/?probe=1dd5741ea8) | May 25, 2022 |
| ASUSTek       | K52F                        | [601b1c4857](https://linux-hardware.org/?probe=601b1c4857) | May 25, 2022 |
| Dell          | Inspiron 3543               | [c48c32ae19](https://linux-hardware.org/?probe=c48c32ae19) | May 25, 2022 |
| Acer          | Nitro AN515-42              | [c755d907ca](https://linux-hardware.org/?probe=c755d907ca) | May 24, 2022 |
| Dell          | Latitude 5310               | [cb40714b3f](https://linux-hardware.org/?probe=cb40714b3f) | May 24, 2022 |
| Dell          | Latitude 5300               | [b2e8f91f15](https://linux-hardware.org/?probe=b2e8f91f15) | May 24, 2022 |
| Dell          | XPS 13 9360                 | [41f966f459](https://linux-hardware.org/?probe=41f966f459) | May 24, 2022 |
| Dell          | Latitude E5570              | [310aadd79a](https://linux-hardware.org/?probe=310aadd79a) | May 24, 2022 |
| HUAWEI        | BOHB-WAX9                   | [64a3f31676](https://linux-hardware.org/?probe=64a3f31676) | May 23, 2022 |
| MSI           | Prestige 14Evo A11M         | [166b6b7ac3](https://linux-hardware.org/?probe=166b6b7ac3) | May 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1d8684d1f5](https://linux-hardware.org/?probe=1d8684d1f5) | May 23, 2022 |
| ASUSTek       | F50SL                       | [7d588b102d](https://linux-hardware.org/?probe=7d588b102d) | May 23, 2022 |
| Dell          | Latitude 3120               | [e97cf58459](https://linux-hardware.org/?probe=e97cf58459) | May 23, 2022 |
| Samsung       | SR70S/SR71S                 | [53642077bd](https://linux-hardware.org/?probe=53642077bd) | May 23, 2022 |
| Google        | Glimmer                     | [f16458e3ea](https://linux-hardware.org/?probe=f16458e3ea) | May 22, 2022 |
| LG Electro... | A410-G.BC48P1               | [fb2344f915](https://linux-hardware.org/?probe=fb2344f915) | May 22, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [c1b20c63e0](https://linux-hardware.org/?probe=c1b20c63e0) | May 22, 2022 |
| TUXEDO        | Unknown                     | [487d75fce7](https://linux-hardware.org/?probe=487d75fce7) | May 21, 2022 |
| Dell          | Inspiron 1545               | [890010e793](https://linux-hardware.org/?probe=890010e793) | May 21, 2022 |
| ASUSTek       | 900                         | [082b51aa29](https://linux-hardware.org/?probe=082b51aa29) | May 21, 2022 |
| Lenovo        | ThinkPad E550 20DF002YUS    | [fe9f7989ef](https://linux-hardware.org/?probe=fe9f7989ef) | May 21, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c273310228](https://linux-hardware.org/?probe=c273310228) | May 20, 2022 |
| HP            | 250 G3                      | [463622ad88](https://linux-hardware.org/?probe=463622ad88) | May 20, 2022 |
| ASUSTek       | UX330UAK                    | [7b50efe523](https://linux-hardware.org/?probe=7b50efe523) | May 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2972e28673](https://linux-hardware.org/?probe=2972e28673) | May 19, 2022 |
| Dell          | Latitude E4310              | [79cda1608c](https://linux-hardware.org/?probe=79cda1608c) | May 19, 2022 |
| System76      | Kudu                        | [78ce5e3b3e](https://linux-hardware.org/?probe=78ce5e3b3e) | May 19, 2022 |
| Acer          | Aspire 5750                 | [4c6bbffcae](https://linux-hardware.org/?probe=4c6bbffcae) | May 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [61e58bea6c](https://linux-hardware.org/?probe=61e58bea6c) | May 17, 2022 |
| HP            | ProBook 4720s               | [887ea9cd89](https://linux-hardware.org/?probe=887ea9cd89) | May 16, 2022 |
| Lenovo        | V145-15AST 81MT             | [486b786e45](https://linux-hardware.org/?probe=486b786e45) | May 16, 2022 |
| HP            | ProBook 4720s               | [09bb5a5088](https://linux-hardware.org/?probe=09bb5a5088) | May 16, 2022 |
| HP            | EliteBook 820 G1            | [f06eee580b](https://linux-hardware.org/?probe=f06eee580b) | May 16, 2022 |
| Dell          | Precision 3551              | [f134f92d00](https://linux-hardware.org/?probe=f134f92d00) | May 16, 2022 |
| HP            | ProBook 6470b               | [9cdf33bcc1](https://linux-hardware.org/?probe=9cdf33bcc1) | May 16, 2022 |
| Dell          | Precision M4400             | [d0d09df553](https://linux-hardware.org/?probe=d0d09df553) | May 15, 2022 |
| ASUSTek       | X550LD                      | [75c6734097](https://linux-hardware.org/?probe=75c6734097) | May 15, 2022 |
| Dell          | Precision M4400             | [96af5a9104](https://linux-hardware.org/?probe=96af5a9104) | May 15, 2022 |
| HP            | Laptop 15-bs0xx             | [9445ab07bf](https://linux-hardware.org/?probe=9445ab07bf) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [f0fef230c2](https://linux-hardware.org/?probe=f0fef230c2) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [2f0e46cc27](https://linux-hardware.org/?probe=2f0e46cc27) | May 15, 2022 |
| Lenovo        | ThinkPad X260 20F5S4C000    | [66fe039d1a](https://linux-hardware.org/?probe=66fe039d1a) | May 14, 2022 |
| Dell          | MXG061                      | [36b09ae01e](https://linux-hardware.org/?probe=36b09ae01e) | May 14, 2022 |
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
| Notebook      | NS50_70MU                   | [40fe0416f5](https://linux-hardware.org/?probe=40fe0416f5) | May 11, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [e6d1749248](https://linux-hardware.org/?probe=e6d1749248) | May 10, 2022 |
| HP            | ENVY TS 17                  | [2423c94072](https://linux-hardware.org/?probe=2423c94072) | May 10, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | [3314cd39d7](https://linux-hardware.org/?probe=3314cd39d7) | May 10, 2022 |
| MSI           | Modern 15 A11M              | [8fe60eb961](https://linux-hardware.org/?probe=8fe60eb961) | May 10, 2022 |
| HP            | EliteBook 840 G3            | [9d0ee854e4](https://linux-hardware.org/?probe=9d0ee854e4) | May 10, 2022 |
| Acer          | Swift SF314-52              | [ee252c0c42](https://linux-hardware.org/?probe=ee252c0c42) | May 10, 2022 |
| Thirdwave     | DX-T7                       | [b90ec1bf3a](https://linux-hardware.org/?probe=b90ec1bf3a) | May 10, 2022 |
| Apple         | MacBook1,1                  | [399e291a66](https://linux-hardware.org/?probe=399e291a66) | May 09, 2022 |
| Acer          | Aspire 5750                 | [200ac122e9](https://linux-hardware.org/?probe=200ac122e9) | May 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [65ef6677b9](https://linux-hardware.org/?probe=65ef6677b9) | May 09, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [019117605e](https://linux-hardware.org/?probe=019117605e) | May 08, 2022 |
| HP            | ProBook x360 11 G1 EE       | [cfe7a62390](https://linux-hardware.org/?probe=cfe7a62390) | May 08, 2022 |
| Panasonic     | CF-AX2LDCZMF                | [0eb2c8ff07](https://linux-hardware.org/?probe=0eb2c8ff07) | May 08, 2022 |
| Acer          | Aspire 5755G                | [634471ce19](https://linux-hardware.org/?probe=634471ce19) | May 08, 2022 |
| ASUSTek       | 900                         | [a4dc643c13](https://linux-hardware.org/?probe=a4dc643c13) | May 08, 2022 |
| Dell          | Inspiron 13-7378            | [7a8fd14c85](https://linux-hardware.org/?probe=7a8fd14c85) | May 08, 2022 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | [8fa9fd80a0](https://linux-hardware.org/?probe=8fa9fd80a0) | May 07, 2022 |
| SLIMBOOK      | Essential15L                | [1a244b5f4a](https://linux-hardware.org/?probe=1a244b5f4a) | May 07, 2022 |
| SLIMBOOK      | Essential15L                | [4f64e62082](https://linux-hardware.org/?probe=4f64e62082) | May 07, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [1d84f1a74a](https://linux-hardware.org/?probe=1d84f1a74a) | May 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [591d3fa922](https://linux-hardware.org/?probe=591d3fa922) | May 07, 2022 |
| Dell          | Latitude E6330              | [cbfc4e6f78](https://linux-hardware.org/?probe=cbfc4e6f78) | May 07, 2022 |
| Lenovo        | ThinkPad W540 20BG0011US    | [1679543d3d](https://linux-hardware.org/?probe=1679543d3d) | May 06, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 2316      | 60.85%  |
| Debian 10                       | 836       | 21.97%  |
| Debian Testing                  | 343       | 9.01%   |
| Debian 9                        | 146       | 3.84%   |
| Debian Unstable                 | 127       | 3.34%   |
| Debian 11-updates               | 22        | 0.58%   |
| Debian 8                        | 10        | 0.26%   |
| Debian Testing/unstable         | 2         | 0.05%   |
| Debian Testing-proposed-updates | 1         | 0.03%   |
| Debian Sid                      | 1         | 0.03%   |
| Debian 99                       | 1         | 0.03%   |
| Debian                          | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Debian | 3714      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.10.0-8-amd64    | 583       | 14.06%  |
| 5.10.0-10-amd64   | 489       | 11.79%  |
| 5.10.0-9-amd64    | 170       | 4.1%    |
| 5.10.0-7-amd64    | 165       | 3.98%   |
| 5.10.0-16-amd64   | 153       | 3.69%   |
| 5.10.0-13-amd64   | 146       | 3.52%   |
| 5.10.0-11-amd64   | 102       | 2.46%   |
| 4.19.0-9-amd64    | 85        | 2.05%   |
| 4.19.0-6-amd64    | 82        | 1.98%   |
| 5.10.0-14-amd64   | 79        | 1.91%   |
| 5.10.0-17-amd64   | 70        | 1.69%   |
| 4.19.0-13-amd64   | 68        | 1.64%   |
| 4.19.0-8-amd64    | 67        | 1.62%   |
| 5.10.0-18-amd64   | 58        | 1.4%    |
| 4.19.0-10-amd64   | 52        | 1.25%   |
| 5.15.0-2-amd64    | 51        | 1.23%   |
| 4.19.0-16-amd64   | 51        | 1.23%   |
| 4.19.0-12-amd64   | 47        | 1.13%   |
| 5.10.0-15-amd64   | 45        | 1.09%   |
| 4.19.0-14-amd64   | 42        | 1.01%   |
| 5.10.0-6-amd64    | 41        | 0.99%   |
| 5.10.0-12-amd64   | 40        | 0.96%   |
| 4.19.0-17-amd64   | 40        | 0.96%   |
| 4.9.0-8-amd64     | 39        | 0.94%   |
| 5.10.0-2-amd64    | 35        | 0.84%   |
| 5.18.0-2-amd64    | 31        | 0.75%   |
| 5.10.0-3-amd64    | 31        | 0.75%   |
| 5.10.0-13-686-pae | 26        | 0.63%   |
| 5.4.0-4-amd64     | 25        | 0.6%    |
| 5.19.0-1-amd64    | 24        | 0.58%   |
| 5.17.0-1-amd64    | 23        | 0.55%   |
| 5.18.0-4-amd64    | 22        | 0.53%   |
| 5.16.0-6-amd64    | 22        | 0.53%   |
| 4.19.0-11-amd64   | 22        | 0.53%   |
| 5.7.0-1-amd64     | 21        | 0.51%   |
| 4.19.0-5-amd64    | 21        | 0.51%   |
| 5.6.0-2-amd64     | 20        | 0.48%   |
| 4.19.0-18-amd64   | 19        | 0.46%   |
| 5.9.0-1-amd64     | 18        | 0.43%   |
| 5.8.0-2-amd64     | 18        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 2250      | 57.53%  |
| 4.19.0   | 640       | 16.36%  |
| 4.9.0    | 120       | 3.07%   |
| 5.18.0   | 92        | 2.35%   |
| 5.15.0   | 91        | 2.33%   |
| 5.9.0    | 73        | 1.87%   |
| 5.16.0   | 65        | 1.66%   |
| 5.4.0    | 64        | 1.64%   |
| 5.7.0    | 59        | 1.51%   |
| 5.8.0    | 56        | 1.43%   |
| 5.14.0   | 52        | 1.33%   |
| 5.6.0    | 45        | 1.15%   |
| 5.17.0   | 38        | 0.97%   |
| 5.19.0   | 31        | 0.79%   |
| 5.3.0    | 19        | 0.49%   |
| 5.5.0    | 16        | 0.41%   |
| 5.2.0    | 12        | 0.31%   |
| 4.18.0   | 12        | 0.31%   |
| 3.16.0   | 8         | 0.2%    |
| 5.12.0   | 6         | 0.15%   |
| 5.17.5   | 3         | 0.08%   |
| 5.13.19  | 3         | 0.08%   |
| 5.13.0   | 3         | 0.08%   |
| 5.11.0   | 3         | 0.08%   |
| 5.10.60  | 3         | 0.08%   |
| 5.10.10  | 3         | 0.08%   |
| 5.0.0    | 3         | 0.08%   |
| 6.0.0    | 2         | 0.05%   |
| 5.8.2    | 2         | 0.05%   |
| 5.8.16   | 2         | 0.05%   |
| 5.4.21   | 2         | 0.05%   |
| 5.3.5    | 2         | 0.05%   |
| 5.18.15  | 2         | 0.05%   |
| 5.17.11  | 2         | 0.05%   |
| 5.15.5   | 2         | 0.05%   |
| 5.15.35  | 2         | 0.05%   |
| 5.15.32  | 2         | 0.05%   |
| 5.13.8   | 2         | 0.05%   |
| 5.10.88  | 2         | 0.05%   |
| 5.10.109 | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2269      | 58.13%  |
| 4.19    | 644       | 16.5%   |
| 4.9     | 123       | 3.15%   |
| 5.15    | 104       | 2.66%   |
| 5.18    | 97        | 2.49%   |
| 5.9     | 79        | 2.02%   |
| 5.4     | 76        | 1.95%   |
| 5.16    | 67        | 1.72%   |
| 5.7     | 62        | 1.59%   |
| 5.8     | 61        | 1.56%   |
| 5.14    | 56        | 1.43%   |
| 5.6     | 49        | 1.26%   |
| 5.17    | 47        | 1.2%    |
| 5.19    | 34        | 0.87%   |
| 5.3     | 23        | 0.59%   |
| 5.5     | 19        | 0.49%   |
| 5.2     | 17        | 0.44%   |
| 5.13    | 12        | 0.31%   |
| 4.18    | 12        | 0.31%   |
| 5.12    | 9         | 0.23%   |
| 5.11    | 9         | 0.23%   |
| 3.16    | 8         | 0.2%    |
| 3.10    | 4         | 0.1%    |
| 5.1     | 3         | 0.08%   |
| 5.0     | 3         | 0.08%   |
| 6.0     | 2         | 0.05%   |
| 4.17    | 2         | 0.05%   |
| 4.15    | 2         | 0.05%   |
| 5.4.104 | 1         | 0.03%   |
| 5.15.6  | 1         | 0.03%   |
| 4.4     | 1         | 0.03%   |
| 4.20    | 1         | 0.03%   |
| 4.14    | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 4.10    | 1         | 0.03%   |
| 3.8     | 1         | 0.03%   |
| 3.0     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3534      | 95.13%  |
| i686    | 170       | 4.58%   |
| armv7l  | 8         | 0.22%   |
| aarch64 | 2         | 0.05%   |
| i586    | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 1098      | 28.88%  |
| GNOME            | 946       | 24.88%  |
| XFCE             | 482       | 12.68%  |
| KDE5             | 440       | 11.57%  |
| MATE             | 160       | 4.21%   |
| X-Cinnamon       | 113       | 2.97%   |
| Cinnamon         | 108       | 2.84%   |
| KDE              | 104       | 2.74%   |
| LXDE             | 103       | 2.71%   |
| i3               | 72        | 1.89%   |
| LXQt             | 47        | 1.24%   |
| GNOME Flashback  | 26        | 0.68%   |
| lightdm-xsession | 22        | 0.58%   |
| Budgie           | 12        | 0.32%   |
| Openbox          | 11        | 0.29%   |
| Trinity          | 10        | 0.26%   |
| GNOME Classic    | 8         | 0.21%   |
| sway             | 4         | 0.11%   |
| ICEWM            | 4         | 0.11%   |
| bspwm            | 4         | 0.11%   |
| awesome          | 4         | 0.11%   |
| Enlightenment    | 3         | 0.08%   |
| DWM              | 3         | 0.08%   |
| Cutefish         | 3         | 0.08%   |
| Unity            | 2         | 0.05%   |
| KDE4             | 2         | 0.05%   |
| Fluxbox          | 2         | 0.05%   |
| default          | 2         | 0.05%   |
| xmonad           | 1         | 0.03%   |
| wmaker-common    | 1         | 0.03%   |
| matchbox         | 1         | 0.03%   |
| jwm              | 1         | 0.03%   |
| i3-gaps          | 1         | 0.03%   |
| GNUstep          | 1         | 0.03%   |
| Deepin           | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2077      | 54.87%  |
| Unknown | 893       | 23.59%  |
| Wayland | 685       | 18.1%   |
| Tty     | 130       | 3.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1672      | 43.94%  |
| GDM     | 717       | 18.84%  |
| LightDM | 482       | 12.67%  |
| SDDM    | 438       | 11.51%  |
| TDM     | 310       | 8.15%   |
| GDM3    | 144       | 3.78%   |
| XDM     | 15        | 0.39%   |
| SLiM    | 13        | 0.34%   |
| NODM    | 7         | 0.18%   |
| KDM     | 6         | 0.16%   |
| WDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1055      | 28%     |
| Unknown | 918       | 24.36%  |
| ru_RU   | 262       | 6.95%   |
| de_DE   | 218       | 5.79%   |
| fr_FR   | 184       | 4.88%   |
| en_GB   | 152       | 4.03%   |
| pt_BR   | 132       | 3.5%    |
| es_ES   | 113       | 3%      |
| it_IT   | 82        | 2.18%   |
| pl_PL   | 70        | 1.86%   |
| en_CA   | 42        | 1.11%   |
| C       | 39        | 1.04%   |
| en_AU   | 35        | 0.93%   |
| es_MX   | 34        | 0.9%    |
| en_IN   | 33        | 0.88%   |
| zh_CN   | 27        | 0.72%   |
| es_CL   | 26        | 0.69%   |
| en_IE   | 21        | 0.56%   |
| hu_HU   | 20        | 0.53%   |
| es_AR   | 20        | 0.53%   |
| pt_PT   | 15        | 0.4%    |
| de_CH   | 14        | 0.37%   |
| fi_FI   | 12        | 0.32%   |
| es_VE   | 12        | 0.32%   |
| de_AT   | 12        | 0.32%   |
| sv_SE   | 11        | 0.29%   |
| nl_NL   | 11        | 0.29%   |
| en_ZA   | 11        | 0.29%   |
| en_NZ   | 11        | 0.29%   |
| cs_CZ   | 11        | 0.29%   |
| es_CO   | 10        | 0.27%   |
| tr_TR   | 9         | 0.24%   |
| ja_JP   | 9         | 0.24%   |
| ru_UA   | 8         | 0.21%   |
| en_SG   | 8         | 0.21%   |
| uk_UA   | 6         | 0.16%   |
| fr_CH   | 6         | 0.16%   |
| fr_BE   | 6         | 0.16%   |
| da_DK   | 6         | 0.16%   |
| ko_KR   | 5         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2264      | 60.31%  |
| BIOS | 1490      | 39.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2546      | 68.22%  |
| Overlay | 920       | 24.65%  |
| Btrfs   | 112       | 3%      |
| Unknown | 78        | 2.09%   |
| Xfs     | 35        | 0.94%   |
| Ext2    | 13        | 0.35%   |
| Zfs     | 9         | 0.24%   |
| Rootfs  | 6         | 0.16%   |
| Ext3    | 5         | 0.13%   |
| Tmpfs   | 4         | 0.11%   |
| Aufs    | 3         | 0.08%   |
| F2fs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2262      | 59.89%  |
| Unknown | 802       | 21.23%  |
| MBR     | 713       | 18.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3018      | 80.33%  |
| Yes       | 739       | 19.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2819      | 75.07%  |
| Yes       | 936       | 24.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 808       | 21.76%  |
| Apple                  | 574       | 15.46%  |
| Hewlett-Packard        | 537       | 14.46%  |
| Dell                   | 522       | 14.05%  |
| ASUSTek Computer       | 330       | 8.89%   |
| Acer                   | 229       | 6.17%   |
| Google                 | 120       | 3.23%   |
| Samsung Electronics    | 57        | 1.53%   |
| MSI                    | 57        | 1.53%   |
| Toshiba                | 55        | 1.48%   |
| Aquarius               | 43        | 1.16%   |
| Sony                   | 36        | 0.97%   |
| HUAWEI                 | 30        | 0.81%   |
| Unknown                | 23        | 0.62%   |
| Notebook               | 21        | 0.57%   |
| Fujitsu                | 14        | 0.38%   |
| Medion                 | 12        | 0.32%   |
| Alienware              | 12        | 0.32%   |
| Timi                   | 10        | 0.27%   |
| Positivo               | 10        | 0.27%   |
| Intel                  | 10        | 0.27%   |
| IBM                    | 10        | 0.27%   |
| TUXEDO                 | 8         | 0.22%   |
| Panasonic              | 8         | 0.22%   |
| LG Electronics         | 8         | 0.22%   |
| Fujitsu Siemens        | 8         | 0.22%   |
| Clevo                  | 8         | 0.22%   |
| Packard Bell           | 7         | 0.19%   |
| Razer                  | 6         | 0.16%   |
| PC Specialist          | 6         | 0.16%   |
| SLIMBOOK               | 5         | 0.13%   |
| Chuwi                  | 5         | 0.13%   |
| Avell High Performance | 5         | 0.13%   |
| System76               | 4         | 0.11%   |
| HONOR                  | 4         | 0.11%   |
| GPU Company            | 4         | 0.11%   |
| Gigabyte Technology    | 4         | 0.11%   |
| eMachines              | 4         | 0.11%   |
| Compal                 | 4         | 0.11%   |
| Schenker               | 3         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 304       | 8.19%   |
| Apple MacBookAir7,1                   | 75        | 2.02%   |
| Google Enguarde                       | 74        | 1.99%   |
| Apple MacBookAir7,2                   | 72        | 1.94%   |
| Apple MacBook2,1                      | 56        | 1.51%   |
| Aquarius NS585                        | 43        | 1.16%   |
| Unknown                               | 35        | 0.94%   |
| Lenovo ThinkPad E475 20H40006US       | 23        | 0.62%   |
| Apple MacBook4,1                      | 23        | 0.62%   |
| HP Notebook                           | 19        | 0.51%   |
| Google Terra                          | 18        | 0.48%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.43%   |
| Acer Aspire A315-23                   | 16        | 0.43%   |
| HP Pavilion g6                        | 14        | 0.38%   |
| ASUS 1005HA                           | 13        | 0.35%   |
| HP EliteBook 8460p                    | 9         | 0.24%   |
| HP 250 G7 Notebook PC                 | 9         | 0.24%   |
| Google Reks                           | 9         | 0.24%   |
| HP Laptop 15-db0xxx                   | 8         | 0.22%   |
| Dell XPS 13 9310                      | 8         | 0.22%   |
| Dell Latitude E7450                   | 8         | 0.22%   |
| Dell Latitude E6420                   | 8         | 0.22%   |
| Dell Inspiron 5570                    | 8         | 0.22%   |
| Lenovo IdeaPad S145-15API 81V7        | 7         | 0.19%   |
| HP Pavilion Notebook                  | 7         | 0.19%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 7         | 0.19%   |
| HP Pavilion dv6                       | 7         | 0.19%   |
| Dell Latitude E6430                   | 7         | 0.19%   |
| Dell Latitude E6330                   | 7         | 0.19%   |
| Dell Latitude 7480                    | 7         | 0.19%   |
| Apple MacBook7,1                      | 7         | 0.19%   |
| HP Stream Notebook PC 13              | 6         | 0.16%   |
| HP Laptop 15s-fq2xxx                  | 6         | 0.16%   |
| HP Laptop 15-db1xxx                   | 6         | 0.16%   |
| HP Laptop 15-bw0xx                    | 6         | 0.16%   |
| HP EliteBook 840 G3                   | 6         | 0.16%   |
| HP EliteBook 840 G1                   | 6         | 0.16%   |
| HP 250 G6 Notebook PC                 | 6         | 0.16%   |
| Dell XPS 13 9360                      | 6         | 0.16%   |
| Dell XPS 13 7390                      | 6         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 541       | 14.57%  |
| Apple MacBook5    | 305       | 8.21%   |
| Dell Latitude     | 189       | 5.09%   |
| Dell Inspiron     | 169       | 4.55%   |
| Acer Aspire       | 149       | 4.01%   |
| Apple MacBookAir7 | 147       | 3.96%   |
| Lenovo IdeaPad    | 144       | 3.88%   |
| HP EliteBook      | 100       | 2.69%   |
| HP Pavilion       | 87        | 2.34%   |
| HP ProBook        | 74        | 1.99%   |
| HP Laptop         | 74        | 1.99%   |
| Google Enguarde   | 74        | 1.99%   |
| Dell XPS          | 59        | 1.59%   |
| Apple MacBook2    | 56        | 1.51%   |
| Dell Vostro       | 48        | 1.29%   |
| Aquarius NS585    | 43        | 1.16%   |
| Toshiba Satellite | 42        | 1.13%   |
| ASUS VivoBook     | 38        | 1.02%   |
| Dell Precision    | 35        | 0.94%   |
| Unknown           | 35        | 0.94%   |
| HP Compaq         | 32        | 0.86%   |
| HP 250            | 27        | 0.73%   |
| Apple MacBook4    | 23        | 0.62%   |
| ASUS ZenBook      | 22        | 0.59%   |
| HP ZBook          | 21        | 0.57%   |
| HP Notebook       | 19        | 0.51%   |
| Lenovo Legion     | 18        | 0.48%   |
| Google Terra      | 18        | 0.48%   |
| Acer TravelMate   | 17        | 0.46%   |
| Acer Swift        | 17        | 0.46%   |
| Lenovo ThinkBook  | 16        | 0.43%   |
| ASUS ASUS         | 16        | 0.43%   |
| Acer Nitro        | 16        | 0.43%   |
| ASUS ROG          | 15        | 0.4%    |
| HP OMEN           | 13        | 0.35%   |
| HP ENVY           | 13        | 0.35%   |
| ASUS 1005HA       | 13        | 0.35%   |
| HP 255            | 12        | 0.32%   |
| Fujitsu LIFEBOOK  | 12        | 0.32%   |
| HP Stream         | 11        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 415       | 11.17%  |
| 2019    | 375       | 10.1%   |
| 2020    | 331       | 8.91%   |
| 2021    | 279       | 7.51%   |
| 2018    | 250       | 6.73%   |
| 2016    | 250       | 6.73%   |
| 2011    | 238       | 6.41%   |
| 2015    | 231       | 6.22%   |
| 2017    | 230       | 6.19%   |
| 2012    | 228       | 6.14%   |
| 2014    | 170       | 4.58%   |
| 2013    | 169       | 4.55%   |
| 2010    | 142       | 3.82%   |
| 2008    | 122       | 3.28%   |
| 2007    | 117       | 3.15%   |
| 2022    | 93        | 2.5%    |
| 2005    | 21        | 0.57%   |
| 2006    | 19        | 0.51%   |
| Unknown | 13        | 0.35%   |
| 2003    | 10        | 0.27%   |
| 2004    | 9         | 0.24%   |
| 2002    | 2         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3714      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3455      | 92.6%   |
| Enabled  | 276       | 7.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3583      | 96.45%  |
| Yes  | 132       | 3.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 958       | 25.57%  |
| 3.01-4.0    | 720       | 19.22%  |
| 16.01-24.0  | 581       | 15.51%  |
| 8.01-16.0   | 561       | 14.97%  |
| 1.01-2.0    | 502       | 13.4%   |
| 32.01-64.0  | 194       | 5.18%   |
| 2.01-3.0    | 76        | 2.03%   |
| 0.51-1.0    | 68        | 1.81%   |
| 64.01-256.0 | 33        | 0.88%   |
| 24.01-32.0  | 32        | 0.85%   |
| 0.01-0.5    | 20        | 0.53%   |
| Unknown     | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1632      | 41.2%   |
| 2.01-3.0   | 765       | 19.31%  |
| 4.01-8.0   | 509       | 12.85%  |
| 0.51-1.0   | 414       | 10.45%  |
| 3.01-4.0   | 388       | 9.8%    |
| 8.01-16.0  | 129       | 3.26%   |
| 0.01-0.5   | 98        | 2.47%   |
| 16.01-24.0 | 12        | 0.3%    |
| Unknown    | 7         | 0.18%   |
| 32.01-64.0 | 3         | 0.08%   |
| 24.01-32.0 | 3         | 0.08%   |
| 0          | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2975      | 78.95%  |
| 2      | 681       | 18.07%  |
| 3      | 75        | 1.99%   |
| 0      | 19        | 0.5%    |
| 4      | 12        | 0.32%   |
| 5      | 4         | 0.11%   |
| 7      | 2         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2366      | 63.47%  |
| Yes       | 1362      | 36.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3033      | 81.42%  |
| No        | 692       | 18.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3648      | 98.14%  |
| No        | 69        | 1.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2997      | 80.13%  |
| No        | 743       | 19.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1077      | 28.79%  |
| Germany      | 319       | 8.53%   |
| Russia       | 303       | 8.1%    |
| France       | 239       | 6.39%   |
| Brazil       | 195       | 5.21%   |
| Spain        | 159       | 4.25%   |
| Italy        | 117       | 3.13%   |
| Poland       | 99        | 2.65%   |
| UK           | 84        | 2.25%   |
| Netherlands  | 60        | 1.6%    |
| Canada       | 60        | 1.6%    |
| Switzerland  | 51        | 1.36%   |
| India        | 50        | 1.34%   |
| Ukraine      | 49        | 1.31%   |
| Mexico       | 49        | 1.31%   |
| China        | 44        | 1.18%   |
| Argentina    | 39        | 1.04%   |
| Australia    | 38        | 1.02%   |
| Sweden       | 34        | 0.91%   |
| Turkey       | 32        | 0.86%   |
| Portugal     | 32        | 0.86%   |
| Chile        | 31        | 0.83%   |
| Hungary      | 30        | 0.8%    |
| Belgium      | 28        | 0.75%   |
| Czechia      | 27        | 0.72%   |
| Austria      | 27        | 0.72%   |
| Greece       | 26        | 0.7%    |
| Finland      | 22        | 0.59%   |
| Norway       | 21        | 0.56%   |
| Ireland      | 20        | 0.53%   |
| Colombia     | 19        | 0.51%   |
| Romania      | 18        | 0.48%   |
| Indonesia    | 18        | 0.48%   |
| Japan        | 16        | 0.43%   |
| Venezuela    | 15        | 0.4%    |
| Thailand     | 15        | 0.4%    |
| New Zealand  | 15        | 0.4%    |
| Denmark      | 14        | 0.37%   |
| South Africa | 12        | 0.32%   |
| Bulgaria     | 12        | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 528       | 13.45%  |
| Dover-Foxcroft    | 229       | 5.83%   |
| Voronezh          | 129       | 3.29%   |
| Paris             | 44        | 1.12%   |
| Moscow            | 44        | 1.12%   |
| St Petersburg     | 40        | 1.02%   |
| Berlin            | 37        | 0.94%   |
| Madrid            | 31        | 0.79%   |
| Seville           | 29        | 0.74%   |
| Sao Paulo         | 29        | 0.74%   |
| Warsaw            | 26        | 0.66%   |
| Munich            | 23        | 0.59%   |
| Amsterdam         | 21        | 0.53%   |
| Vienna            | 20        | 0.51%   |
| Hamburg           | 18        | 0.46%   |
| London            | 17        | 0.43%   |
| Zurich            | 16        | 0.41%   |
| Prague            | 15        | 0.38%   |
| Athens            | 14        | 0.36%   |
| Sydney            | 13        | 0.33%   |
| Milan             | 13        | 0.33%   |
| Dublin            | 13        | 0.33%   |
| Budapest          | 13        | 0.33%   |
| Barcelona         | 13        | 0.33%   |
| Perm              | 11        | 0.28%   |
| Istanbul          | 11        | 0.28%   |
| Helsinki          | 11        | 0.28%   |
| Frankfurt am Main | 11        | 0.28%   |
| Brasília         | 11        | 0.28%   |
| Blizniew          | 11        | 0.28%   |
| Bangkok           | 11        | 0.28%   |
| Toronto           | 10        | 0.25%   |
| Mexico City       | 10        | 0.25%   |
| Lisbon            | 10        | 0.25%   |
| Kyiv              | 10        | 0.25%   |
| Belo Horizonte    | 10        | 0.25%   |
| Zagreb            | 9         | 0.23%   |
| Turin             | 9         | 0.23%   |
| Singapore         | 9         | 0.23%   |
| Melbourne         | 9         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 619       | 789    | 13.95%  |
| WDC                       | 507       | 608    | 11.43%  |
| Seagate                   | 433       | 521    | 9.76%   |
| Toshiba                   | 364       | 407    | 8.21%   |
| Unknown                   | 290       | 386    | 6.54%   |
| Fujitsu                   | 250       | 255    | 5.64%   |
| Kingston                  | 237       | 270    | 5.34%   |
| SanDisk                   | 208       | 247    | 4.69%   |
| Apple                     | 169       | 198    | 3.81%   |
| Crucial                   | 167       | 201    | 3.76%   |
| SK hynix                  | 165       | 201    | 3.72%   |
| Hitachi                   | 136       | 153    | 3.07%   |
| A-DATA Technology         | 105       | 184    | 2.37%   |
| HGST                      | 93        | 103    | 2.1%    |
| Intel                     | 91        | 109    | 2.05%   |
| Micron Technology         | 88        | 91     | 1.98%   |
| KIOXIA                    | 39        | 50     | 0.88%   |
| LITEON                    | 25        | 29     | 0.56%   |
| China                     | 24        | 26     | 0.54%   |
| Transcend                 | 23        | 29     | 0.52%   |
| Silicon Motion            | 20        | 21     | 0.45%   |
| PNY                       | 18        | 20     | 0.41%   |
| Phison                    | 17        | 24     | 0.38%   |
| Intenso                   | 17        | 24     | 0.38%   |
| SABRENT                   | 16        | 17     | 0.36%   |
| Unknown                   | 15        | 16     | 0.34%   |
| Patriot                   | 14        | 16     | 0.32%   |
| SPCC                      | 11        | 14     | 0.25%   |
| LITEONIT                  | 11        | 12     | 0.25%   |
| OCZ                       | 10        | 12     | 0.23%   |
| Micron/Crucial Technology | 10        | 10     | 0.23%   |
| GOODRAM                   | 10        | 12     | 0.23%   |
| Team                      | 9         | 11     | 0.2%    |
| Lenovo                    | 8         | 10     | 0.18%   |
| LDLC                      | 8         | 8      | 0.18%   |
| Union Memory              | 7         | 8      | 0.16%   |
| Plextor                   | 7         | 7      | 0.16%   |
| KingSpec                  | 7         | 7      | 0.16%   |
| JMicron Technology        | 7         | 7      | 0.16%   |
| Hewlett-Packard           | 7         | 7      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 200       | 4.41%   |
| Apple SSD AP0128H 121GB              | 75        | 1.65%   |
| Apple SSD SM0128G 121GB              | 71        | 1.56%   |
| Seagate ST1000LM035-1RK172 1TB       | 59        | 1.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 48        | 1.06%   |
| Kingston SA400S37120G 120GB SSD      | 47        | 1.04%   |
| Toshiba MK1655GSXF 160GB             | 46        | 1.01%   |
| Kingston SA400S37240G 240GB SSD      | 46        | 1.01%   |
| A-DATA SU800 512GB SSD               | 45        | 0.99%   |
| Toshiba MK1653GSX 160GB              | 42        | 0.93%   |
| Unknown AGND3R  16GB                 | 39        | 0.86%   |
| Toshiba MQ01ABD100 1TB               | 35        | 0.77%   |
| HGST HTS721010A9E630 1TB             | 33        | 0.73%   |
| Unknown HAG2e  16GB                  | 31        | 0.68%   |
| Toshiba MQ04ABF100 1TB               | 28        | 0.62%   |
| Toshiba MQ01ABF050 500GB             | 27        | 0.59%   |
| Unknown MMC Card  32GB               | 26        | 0.57%   |
| Crucial CT500MX500SSD1 500GB         | 25        | 0.55%   |
| Samsung SSD 860 EVO 500GB            | 23        | 0.51%   |
| Samsung SSD 850 EVO 250GB            | 23        | 0.51%   |
| Seagate ST1000LM048-2E7172 1TB       | 22        | 0.48%   |
| Unknown SDW16G  16GB                 | 21        | 0.46%   |
| Kingston SA400S37480G 480GB SSD      | 21        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB      | 20        | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB         | 19        | 0.42%   |
| Samsung SSD 860 EVO 1TB              | 19        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB          | 19        | 0.42%   |
| WDC WD10SPZX-24Z10 1TB               | 18        | 0.4%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 18        | 0.4%    |
| Unknown MMC Card  64GB               | 17        | 0.37%   |
| WDC WD1600BUDT-63DPZY0 160GB         | 16        | 0.35%   |
| Seagate ST9500325AS 500GB            | 16        | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 16        | 0.35%   |
| Samsung SSD 860 EVO 250GB            | 16        | 0.35%   |
| SABRENT Disk 1TB                     | 16        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD     | 16        | 0.35%   |
| Crucial CT240BX500SSD1 240GB         | 16        | 0.35%   |
| HGST HTS725050A7E630 500GB           | 15        | 0.33%   |
| Unknown                              | 15        | 0.33%   |
| WDC WD10SPZX-21Z10T0 1TB             | 14        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 419       | 505    | 27.4%   |
| WDC                 | 298       | 335    | 19.49%  |
| Toshiba             | 275       | 302    | 17.99%  |
| Fujitsu             | 250       | 255    | 16.35%  |
| Hitachi             | 136       | 153    | 8.89%   |
| HGST                | 93        | 103    | 6.08%   |
| Samsung Electronics | 29        | 30     | 1.9%    |
| Unknown             | 8         | 11     | 0.52%   |
| IBM/Hitachi         | 5         | 6      | 0.33%   |
| Intenso             | 3         | 4      | 0.2%    |
| SILICONMOTION       | 2         | 2      | 0.13%   |
| ASMT                | 2         | 7      | 0.13%   |
| USB3.0              | 1         | 1      | 0.07%   |
| Unknown (CF)        | 1         | 1      | 0.07%   |
| QNAP                | 1         | 2      | 0.07%   |
| PHD 3.0             | 1         | 1      | 0.07%   |
| Maxone              | 1         | 1      | 0.07%   |
| IBM                 | 1         | 1      | 0.07%   |
| Hewlett-Packard     | 1         | 1      | 0.07%   |
| ASMT109x            | 1         | 1      | 0.07%   |
| Apple               | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 298       | 379    | 20.68%  |
| Kingston            | 188       | 218    | 13.05%  |
| SanDisk             | 163       | 196    | 11.31%  |
| Crucial             | 153       | 185    | 10.62%  |
| Apple               | 85        | 89     | 5.9%    |
| A-DATA Technology   | 81        | 151    | 5.62%   |
| WDC                 | 56        | 71     | 3.89%   |
| Micron Technology   | 44        | 46     | 3.05%   |
| SK hynix            | 38        | 43     | 2.64%   |
| Intel               | 29        | 32     | 2.01%   |
| Toshiba             | 25        | 27     | 1.73%   |
| China               | 24        | 26     | 1.67%   |
| Transcend           | 21        | 27     | 1.46%   |
| LITEON              | 21        | 25     | 1.46%   |
| PNY                 | 14        | 16     | 0.97%   |
| Patriot             | 13        | 15     | 0.9%    |
| Intenso             | 13        | 18     | 0.9%    |
| LITEONIT            | 11        | 12     | 0.76%   |
| OCZ                 | 10        | 12     | 0.69%   |
| Team                | 9         | 11     | 0.62%   |
| SPCC                | 9         | 11     | 0.62%   |
| Goodram             | 8         | 10     | 0.56%   |
| Plextor             | 7         | 7      | 0.49%   |
| LDLC                | 7         | 7      | 0.49%   |
| KingSpec            | 7         | 7      | 0.49%   |
| Netac               | 6         | 8      | 0.42%   |
| Seagate             | 5         | 5      | 0.35%   |
| Lexar               | 5         | 6      | 0.35%   |
| Corsair             | 5         | 5      | 0.35%   |
| KingDian            | 4         | 4      | 0.28%   |
| Hewlett-Packard     | 4         | 4      | 0.28%   |
| BIWIN               | 4         | 4      | 0.28%   |
| ASUS-PHISON         | 4         | 5      | 0.28%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.21%   |
| Gigabyte Technology | 3         | 3      | 0.21%   |
| Apacer              | 3         | 3      | 0.21%   |
| Unknown             | 3         | 3      | 0.21%   |
| ZTC                 | 2         | 6      | 0.14%   |
| Vaseky              | 2         | 3      | 0.14%   |
| Unknown             | 2         | 2      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1494      | 1723   | 35.01%  |
| SSD     | 1352      | 1773   | 31.69%  |
| NVMe    | 1082      | 1397   | 25.36%  |
| MMC     | 303       | 400    | 7.1%    |
| Unknown | 36        | 42     | 0.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2589      | 3399   | 63.53%  |
| NVMe | 1066      | 1371   | 26.16%  |
| MMC  | 303       | 400    | 7.44%   |
| SAS  | 117       | 165    | 2.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2015      | 2465   | 71.63%  |
| 0.51-1.0   | 724       | 932    | 25.74%  |
| 1.01-2.0   | 60        | 79     | 2.13%   |
| 4.01-10.0  | 7         | 12     | 0.25%   |
| 3.01-4.0   | 6         | 7      | 0.21%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1088      | 28.41%  |
| 251-500        | 761       | 19.87%  |
| Unknown        | 669       | 17.47%  |
| 501-1000       | 474       | 12.38%  |
| 51-100         | 233       | 6.09%   |
| 1-20           | 196       | 5.12%   |
| 1001-2000      | 194       | 5.07%   |
| 21-50          | 131       | 3.42%   |
| 2001-3000      | 45        | 1.18%   |
| More than 3000 | 38        | 0.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1344      | 34.05%  |
| Unknown        | 669       | 16.95%  |
| 21-50          | 502       | 12.72%  |
| 101-250        | 492       | 12.47%  |
| 51-100         | 409       | 10.36%  |
| 251-500        | 277       | 7.02%   |
| 501-1000       | 160       | 4.05%   |
| 1001-2000      | 59        | 1.49%   |
| More than 3000 | 15        | 0.38%   |
| 2001-3000      | 11        | 0.28%   |
| 0              | 9         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB        | 20        | 20     | 5.48%   |
| Toshiba MK1653GSX 160GB               | 9         | 9      | 2.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 9         | 11     | 2.47%   |
| Toshiba MK1655GSXF 160GB              | 7         | 7      | 1.92%   |
| Seagate ST9500325AS 500GB             | 7         | 7      | 1.92%   |
| Seagate ST9500420AS 500GB             | 6         | 6      | 1.64%   |
| Hitachi HTS543216L9SA02 160GB         | 6         | 6      | 1.64%   |
| Toshiba MQ01ABD100 1TB                | 5         | 5      | 1.37%   |
| Hitachi HTS545050B9A300 500GB         | 5         | 5      | 1.37%   |
| Hitachi HTS542512K9SA00 120GB         | 5         | 6      | 1.37%   |
| HGST HTS725050A7E630 500GB            | 5         | 5      | 1.37%   |
| WDC WD1600BUDT-63DPZY0 160GB          | 4         | 4      | 1.1%    |
| Seagate ST500LT012-9WS142 500GB       | 4         | 5      | 1.1%    |
| Seagate ST500LM000-SSHD-8GB           | 4         | 4      | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 4      | 1.1%    |
| Toshiba MQ04ABF100 1TB                | 3         | 3      | 0.82%   |
| Toshiba MQ01ABF050 500GB              | 3         | 3      | 0.82%   |
| SK hynix HFS256G39MND-2300A 256GB SSD | 3         | 3      | 0.82%   |
| Seagate ST9250315AS 250GB             | 3         | 4      | 0.82%   |
| Seagate ST500LM021-1KJ152 500GB       | 3         | 3      | 0.82%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 3      | 0.82%   |
| Hitachi HTS547575A9E384 752GB         | 3         | 3      | 0.82%   |
| Hitachi HTS547550A9E384 500GB         | 3         | 3      | 0.82%   |
| Hitachi HTS542516K9SA00 160GB         | 3         | 3      | 0.82%   |
| HGST HTS541010A9E680 1TB              | 3         | 3      | 0.82%   |
| Crucial CT275MX300SSD1 275GB          | 3         | 3      | 0.82%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 2         | 2      | 0.55%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 2         | 2      | 0.55%   |
| WDC WD10SPZX-60Z10T0 1TB              | 2         | 3      | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 2      | 0.55%   |
| Toshiba MQ01ACF050 500GB              | 2         | 2      | 0.55%   |
| Toshiba MQ01ABD050 500GB              | 2         | 2      | 0.55%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 2         | 2      | 0.55%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 2         | 2      | 0.55%   |
| Seagate ST980811AS 80GB               | 2         | 2      | 0.55%   |
| Seagate ST94811A 40GB                 | 2         | 2      | 0.55%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 0.55%   |
| Seagate ST9160412AS 160GB             | 2         | 2      | 0.55%   |
| Seagate ST9160310AS 160GB             | 2         | 2      | 0.55%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 2         | 2      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 80     | 19.78%  |
| Hitachi             | 57        | 62     | 15.66%  |
| Toshiba             | 46        | 46     | 12.64%  |
| WDC                 | 34        | 35     | 9.34%   |
| Fujitsu             | 34        | 34     | 9.34%   |
| HGST                | 20        | 20     | 5.49%   |
| Samsung Electronics | 18        | 20     | 4.95%   |
| SK hynix            | 14        | 14     | 3.85%   |
| Micron Technology   | 10        | 10     | 2.75%   |
| Kingston            | 10        | 11     | 2.75%   |
| SanDisk             | 9         | 11     | 2.47%   |
| Intel               | 7         | 8      | 1.92%   |
| Crucial             | 7         | 8      | 1.92%   |
| A-DATA Technology   | 7         | 8      | 1.92%   |
| LITEON              | 3         | 3      | 0.82%   |
| LITEONIT            | 2         | 2      | 0.55%   |
| IBM/Hitachi         | 2         | 2      | 0.55%   |
| Corsair             | 2         | 2      | 0.55%   |
| Team                | 1         | 1      | 0.27%   |
| ShiJi               | 1         | 1      | 0.27%   |
| Lenovo              | 1         | 1      | 0.27%   |
| KingSpec            | 1         | 1      | 0.27%   |
| KingDian            | 1         | 1      | 0.27%   |
| IBM                 | 1         | 1      | 0.27%   |
| GOODRAM             | 1         | 1      | 0.27%   |
| DGM                 | 1         | 1      | 0.27%   |
| China               | 1         | 1      | 0.27%   |
| Apple               | 1         | 1      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 80     | 26.28%  |
| Hitachi             | 57        | 62     | 20.8%   |
| Toshiba             | 45        | 45     | 16.42%  |
| Fujitsu             | 34        | 34     | 12.41%  |
| WDC                 | 33        | 34     | 12.04%  |
| HGST                | 20        | 20     | 7.3%    |
| Samsung Electronics | 10        | 10     | 3.65%   |
| IBM/Hitachi         | 2         | 2      | 0.73%   |
| IBM                 | 1         | 1      | 0.36%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 271       | 288    | 75.07%  |
| SSD  | 79        | 87     | 21.88%  |
| NVMe | 11        | 11     | 3.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                 | 1         | 1      | 16.67%  |
| Toshiba MK6465GSX 640GB                      | 1         | 1      | 16.67%  |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 16.67%  |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 16.67%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB | 1         | 1      | 16.67%  |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 33.33%  |
| WDC                 | 1         | 1      | 16.67%  |
| Toshiba             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2507      | 3283   | 62.88%  |
| Detected | 1114      | 1659   | 27.94%  |
| Malfunc  | 359       | 386    | 9%      |
| Failed   | 6         | 6      | 0.15%   |
| Limited  | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2242      | 54.98%  |
| Samsung Electronics              | 387       | 9.49%   |
| AMD                              | 354       | 8.68%   |
| Nvidia                           | 322       | 7.9%    |
| SanDisk                          | 185       | 4.54%   |
| SK hynix                         | 120       | 2.94%   |
| Apple                            | 82        | 2.01%   |
| Toshiba America Info Systems     | 72        | 1.77%   |
| Kingston Technology Company      | 49        | 1.2%    |
| Micron Technology                | 44        | 1.08%   |
| KIOXIA                           | 37        | 0.91%   |
| ADATA Technology                 | 31        | 0.76%   |
| Silicon Motion                   | 30        | 0.74%   |
| Phison Electronics               | 30        | 0.74%   |
| Micron/Crucial Technology        | 24        | 0.59%   |
| Silicon Integrated Systems [SiS] | 11        | 0.27%   |
| Union Memory (Shenzhen)          | 10        | 0.25%   |
| Solid State Storage Technology   | 10        | 0.25%   |
| Shenzhen Longsys Electronics     | 5         | 0.12%   |
| Lite-On Technology               | 5         | 0.12%   |
| Lenovo                           | 5         | 0.12%   |
| Realtek Semiconductor            | 4         | 0.1%    |
| Silicon Image                    | 3         | 0.07%   |
| Seagate Technology               | 3         | 0.07%   |
| VIA Technologies                 | 2         | 0.05%   |
| ULi Electronics                  | 2         | 0.05%   |
| ASMedia Technology               | 2         | 0.05%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| Marvell Technology Group         | 1         | 0.02%   |
| JMicron Technology               | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |
| Adaptec                          | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 311       | 7.1%    |
| Nvidia MCP79 AHCI Controller                                                     | 309       | 7.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 308       | 7.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 241       | 5.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 175       | 4%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 162       | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 161       | 3.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 115       | 2.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 95        | 2.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 91        | 2.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 88        | 2.01%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 87        | 1.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 79        | 1.8%    |
| Samsung NVMe SSD Controller 980                                                  | 77        | 1.76%   |
| Samsung Electronics SATA controller                                              | 77        | 1.76%   |
| Apple S1X NVMe Controller                                                        | 76        | 1.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 72        | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 71        | 1.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 71        | 1.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 67        | 1.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 63        | 1.44%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 61        | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                            | 49        | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 48        | 1.1%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 46        | 1.05%   |
| Micron Non-Volatile memory controller                                            | 44        | 1%      |
| SK hynix Gold P31 SSD                                                            | 43        | 0.98%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 43        | 0.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 43        | 0.98%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 41        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 41        | 0.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 39        | 0.89%   |
| Intel Tiger Lake-LP SATA Controller                                              | 37        | 0.84%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 34        | 0.78%   |
| Intel SSD 660P Series                                                            | 32        | 0.73%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 31        | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 28        | 0.64%   |
| SK hynix BC511                                                                   | 27        | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 27        | 0.62%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 26        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2610      | 61.22%  |
| NVMe | 1073      | 25.17%  |
| IDE  | 327       | 7.67%   |
| RAID | 252       | 5.91%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3210      | 86.41%  |
| AMD          | 493       | 13.27%  |
| ARM          | 9         | 0.24%   |
| Unknown      | 2         | 0.05%   |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 305       | 8.21%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 142       | 3.82%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 89        | 2.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 67        | 1.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 64        | 1.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 62        | 1.67%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 60        | 1.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 58        | 1.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 55        | 1.48%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 53        | 1.43%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 50        | 1.35%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 48        | 1.29%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 43        | 1.16%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 43        | 1.16%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 43        | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 40        | 1.08%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 39        | 1.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 38        | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 34        | 0.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 34        | 0.91%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 30        | 0.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 29        | 0.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 27        | 0.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 27        | 0.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 27        | 0.73%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 27        | 0.73%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 26        | 0.7%    |
| Intel Atom CPU N270 @ 1.60GHz                 | 26        | 0.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 24        | 0.65%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 24        | 0.65%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 23        | 0.62%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 22        | 0.59%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.59%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 21        | 0.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 20        | 0.54%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 20        | 0.54%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 19        | 0.51%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 19        | 0.51%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 19        | 0.51%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 19        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 943       | 25.38%  |
| Intel Core i7           | 701       | 18.87%  |
| Intel Core 2 Duo        | 463       | 12.46%  |
| Intel Celeron           | 271       | 7.29%   |
| Intel Core i3           | 243       | 6.54%   |
| Other                   | 237       | 6.38%   |
| AMD Ryzen 5             | 143       | 3.85%   |
| Intel Atom              | 106       | 2.85%   |
| AMD Ryzen 7             | 76        | 2.05%   |
| Intel Pentium           | 72        | 1.94%   |
| Intel Core 2            | 68        | 1.83%   |
| AMD Ryzen 7 PRO         | 32        | 0.86%   |
| Intel Pentium M         | 28        | 0.75%   |
| AMD A6                  | 28        | 0.75%   |
| Intel Pentium Dual-Core | 21        | 0.57%   |
| AMD Ryzen 3             | 20        | 0.54%   |
| AMD A4                  | 20        | 0.54%   |
| Intel Pentium Dual      | 18        | 0.48%   |
| AMD A8                  | 18        | 0.48%   |
| Intel Genuine           | 17        | 0.46%   |
| AMD E1                  | 16        | 0.43%   |
| AMD Ryzen 9             | 12        | 0.32%   |
| AMD Ryzen 5 PRO         | 11        | 0.3%    |
| AMD A10                 | 11        | 0.3%    |
| Intel Celeron M         | 10        | 0.27%   |
| AMD E                   | 10        | 0.27%   |
| AMD E2                  | 9         | 0.24%   |
| Intel Pentium Silver    | 8         | 0.22%   |
| Intel Pentium 4         | 8         | 0.22%   |
| Intel Core i9           | 7         | 0.19%   |
| Intel Core m3           | 6         | 0.16%   |
| AMD Athlon              | 6         | 0.16%   |
| AMD A12                 | 6         | 0.16%   |
| Intel Celeron Dual-Core | 5         | 0.13%   |
| ARM ARMv7               | 5         | 0.13%   |
| AMD Turion 64 X2 Mobile | 5         | 0.13%   |
| Intel Xeon              | 4         | 0.11%   |
| Intel Mobile Pentium 4  | 4         | 0.11%   |
| AMD C-60                | 4         | 0.11%   |
| Intel Pentium III       | 3         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2148      | 57.79%  |
| 4      | 1057      | 28.44%  |
| 6      | 183       | 4.92%   |
| 1      | 170       | 4.57%   |
| 8      | 132       | 3.55%   |
| 14     | 15        | 0.4%    |
| 10     | 6         | 0.16%   |
| 12     | 5         | 0.13%   |
| 3      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3713      | 99.95%  |
| 2      | 2         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2422      | 65.2%   |
| 1      | 1292      | 34.78%  |
| 4      | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3548      | 95.48%  |
| 32-bit         | 96        | 2.58%   |
| Unknown        | 70        | 1.88%   |
| 64-bit         | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 810       | 21.32%  |
| 0x1067a    | 385       | 10.13%  |
| 0x306d4    | 229       | 6.03%   |
| 0x306a9    | 166       | 4.37%   |
| 0x206a7    | 161       | 4.24%   |
| 0x806ec    | 148       | 3.89%   |
| 0x806c1    | 121       | 3.18%   |
| 0x30678    | 109       | 2.87%   |
| 0x806e9    | 106       | 2.79%   |
| 0x806ea    | 105       | 2.76%   |
| 0x40651    | 92        | 2.42%   |
| 0x406e3    | 86        | 2.26%   |
| 0x6f6      | 64        | 1.68%   |
| 0x906ea    | 61        | 1.61%   |
| 0x306c3    | 59        | 1.55%   |
| 0x20655    | 52        | 1.37%   |
| 0xa0652    | 49        | 1.29%   |
| 0x406c4    | 49        | 1.29%   |
| 0x906eb    | 43        | 1.13%   |
| 0x10676    | 40        | 1.05%   |
| 0x08600106 | 40        | 1.05%   |
| 0x0a50000c | 39        | 1.03%   |
| 0x08108109 | 39        | 1.03%   |
| 0x08108102 | 39        | 1.03%   |
| 0x706e5    | 36        | 0.95%   |
| 0x08608103 | 33        | 0.87%   |
| 0x6fd      | 32        | 0.84%   |
| 0x806eb    | 31        | 0.82%   |
| 0x106ca    | 29        | 0.76%   |
| 0x106c2    | 28        | 0.74%   |
| 0x906e9    | 27        | 0.71%   |
| 0x0600611a | 27        | 0.71%   |
| 0x6d8      | 24        | 0.63%   |
| 0x506e3    | 24        | 0.63%   |
| 0x706a8    | 23        | 0.61%   |
| 0x906a3    | 21        | 0.55%   |
| 0x20652    | 21        | 0.55%   |
| 0x06006705 | 21        | 0.55%   |
| 0x506c9    | 19        | 0.5%    |
| 0x406c3    | 17        | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 708       | 19.05%  |
| Penryn           | 455       | 12.24%  |
| Broadwell        | 253       | 6.81%   |
| IvyBridge        | 238       | 6.4%    |
| SandyBridge      | 222       | 5.97%   |
| Haswell          | 208       | 5.6%    |
| Silvermont       | 199       | 5.35%   |
| Skylake          | 164       | 4.41%   |
| TigerLake        | 151       | 4.06%   |
| Core             | 135       | 3.63%   |
| Westmere         | 102       | 2.74%   |
| Zen+             | 98        | 2.64%   |
| Zen 2            | 84        | 2.26%   |
| Bonnell          | 72        | 1.94%   |
| Excavator        | 67        | 1.8%    |
| CometLake        | 67        | 1.8%    |
| Unknown          | 64        | 1.72%   |
| IceLake          | 54        | 1.45%   |
| P6               | 51        | 1.37%   |
| Zen 3            | 48        | 1.29%   |
| Goldmont plus    | 42        | 1.13%   |
| Zen              | 30        | 0.81%   |
| Bobcat           | 28        | 0.75%   |
| Goldmont         | 26        | 0.7%    |
| Puma             | 23        | 0.62%   |
| Alderlake Hybrid | 21        | 0.56%   |
| K8 Hammer        | 16        | 0.43%   |
| Jaguar           | 16        | 0.43%   |
| K10 Llano        | 15        | 0.4%    |
| NetBurst         | 13        | 0.35%   |
| Piledriver       | 11        | 0.3%    |
| Nehalem          | 11        | 0.3%    |
| Tremont          | 7         | 0.19%   |
| K10              | 7         | 0.19%   |
| Steamroller      | 6         | 0.16%   |
| K8 & K10 hybrid  | 5         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2692      | 60.59%  |
| Nvidia                           | 1038      | 23.36%  |
| AMD                              | 701       | 15.78%  |
| Silicon Integrated Systems [SiS] | 7         | 0.16%   |
| VIA Technologies                 | 2         | 0.05%   |
| S3 Graphics                      | 2         | 0.05%   |
| Neomagic                         | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 304       | 6.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 223       | 4.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 199       | 4.27%   |
| Intel UHD Graphics 620                                                                   | 161       | 3.46%   |
| Intel HD Graphics 6000                                                                   | 147       | 3.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 138       | 2.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 123       | 2.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 122       | 2.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 121       | 2.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 120       | 2.58%   |
| Intel HD Graphics 620                                                                    | 113       | 2.43%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 99        | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 99        | 2.13%   |
| Intel HD Graphics 5500                                                                   | 98        | 2.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 97        | 2.08%   |
| AMD Renoir                                                                               | 83        | 1.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 82        | 1.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 77        | 1.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 76        | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 75        | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 72        | 1.55%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 71        | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 70        | 1.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 70        | 1.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 55        | 1.18%   |
| AMD Cezanne                                                                              | 44        | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 43        | 0.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 40        | 0.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 38        | 0.82%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 38        | 0.82%   |
| AMD Lucienne                                                                             | 38        | 0.82%   |
| Intel HD Graphics 630                                                                    | 37        | 0.79%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 36        | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 31        | 0.67%   |
| Intel HD Graphics 530                                                                    | 31        | 0.67%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 29        | 0.62%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 29        | 0.62%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 28        | 0.6%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 28        | 0.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 27        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1998      | 53.7%   |
| Intel + Nvidia     | 562       | 15.1%   |
| 1 x AMD            | 487       | 13.09%  |
| 1 x Nvidia         | 429       | 11.53%  |
| Intel + AMD        | 126       | 3.39%   |
| AMD + Nvidia       | 46        | 1.24%   |
| 2 x AMD            | 42        | 1.13%   |
| Other              | 16        | 0.43%   |
| 1 x SiS            | 7         | 0.19%   |
| 1 x VIA            | 2         | 0.05%   |
| 1 x S3 Graphics    | 2         | 0.05%   |
| Intel + 2 x Nvidia | 2         | 0.05%   |
| 2 x Nvidia         | 1         | 0.03%   |
| 1 x Neomagic       | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3246      | 86.72%  |
| Proprietary | 266       | 7.11%   |
| Unknown     | 231       | 6.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2724      | 72.39%  |
| 0.01-0.5   | 595       | 15.81%  |
| 1.01-2.0   | 199       | 5.29%   |
| 3.01-4.0   | 104       | 2.76%   |
| 0.51-1.0   | 102       | 2.71%   |
| 7.01-8.0   | 17        | 0.45%   |
| 5.01-6.0   | 17        | 0.45%   |
| 2.01-3.0   | 4         | 0.11%   |
| 8.01-16.0  | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 707       | 17.45%  |
| Apple                   | 574       | 14.17%  |
| BOE                     | 513       | 12.66%  |
| LG Display              | 480       | 11.85%  |
| Chimei Innolux          | 433       | 10.69%  |
| Samsung Electronics     | 327       | 8.07%   |
| Dell                    | 110       | 2.72%   |
| Lenovo                  | 99        | 2.44%   |
| Sharp                   | 84        | 2.07%   |
| Goldstar                | 84        | 2.07%   |
| Chi Mei Optoelectronics | 65        | 1.6%    |
| Hewlett-Packard         | 47        | 1.16%   |
| InfoVision              | 43        | 1.06%   |
| BenQ                    | 39        | 0.96%   |
| PANDA                   | 35        | 0.86%   |
| Philips                 | 34        | 0.84%   |
| AOC                     | 31        | 0.77%   |
| HannStar                | 28        | 0.69%   |
| Iiyama                  | 27        | 0.67%   |
| Ancor Communications    | 26        | 0.64%   |
| Acer                    | 25        | 0.62%   |
| LG Philips              | 24        | 0.59%   |
| CSO                     | 20        | 0.49%   |
| Unknown                 | 18        | 0.44%   |
| Sony                    | 16        | 0.39%   |
| ViewSonic               | 14        | 0.35%   |
| CPT                     | 14        | 0.35%   |
| Eizo                    | 10        | 0.25%   |
| Quanta Display          | 8         | 0.2%    |
| ASUSTek Computer        | 7         | 0.17%   |
| Panasonic               | 6         | 0.15%   |
| NEC Computers           | 6         | 0.15%   |
| Pixio                   | 4         | 0.1%    |
| MSI                     | 4         | 0.1%    |
| InnoLux Display         | 4         | 0.1%    |
| AGO                     | 4         | 0.1%    |
| Toshiba                 | 3         | 0.07%   |
| TMX                     | 3         | 0.07%   |
| LGD                     | 3         | 0.07%   |
| Fujitsu Siemens         | 3         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 200       | 4.88%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 151       | 3.68%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 52        | 1.27%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 43        | 1.05%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 40        | 0.98%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 38        | 0.93%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 37        | 0.9%    |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 35        | 0.85%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 28        | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 24        | 0.59%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 24        | 0.59%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 23        | 0.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 23        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 22        | 0.54%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 22        | 0.54%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch | 21        | 0.51%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 21        | 0.51%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 19        | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 16        | 0.39%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 16        | 0.39%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 15        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 14        | 0.34%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 14        | 0.34%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 14        | 0.34%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 14        | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 13        | 0.32%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 13        | 0.32%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 13        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 12        | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 12        | 0.29%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 12        | 0.29%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 12        | 0.29%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 11        | 0.27%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                 | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 11        | 0.27%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 10        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 10        | 0.24%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 10        | 0.24%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 10        | 0.24%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 10        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1389      | 36.31%  |
| 1366x768 (WXGA)    | 1075      | 28.1%   |
| 1280x800 (WXGA)    | 498       | 13.02%  |
| 1600x900 (HD+)     | 168       | 4.39%   |
| 1440x900 (WXGA+)   | 118       | 3.08%   |
| 3840x2160 (4K)     | 112       | 2.93%   |
| 2560x1440 (QHD)    | 84        | 2.2%    |
| 1920x1200 (WUXGA)  | 68        | 1.78%   |
| 1024x600           | 54        | 1.41%   |
| 1280x1024 (SXGA)   | 31        | 0.81%   |
| 2560x1600          | 28        | 0.73%   |
| 1680x1050 (WSXGA+) | 26        | 0.68%   |
| 2560x1080          | 20        | 0.52%   |
| 1360x768           | 19        | 0.5%    |
| 2288x1287          | 15        | 0.39%   |
| 1024x768 (XGA)     | 15        | 0.39%   |
| 2880x1800          | 14        | 0.37%   |
| 3840x2400          | 13        | 0.34%   |
| 3440x1440          | 11        | 0.29%   |
| 3200x1800 (QHD+)   | 9         | 0.24%   |
| 2160x1440          | 8         | 0.21%   |
| 1600x1200          | 6         | 0.16%   |
| 3840x1080          | 5         | 0.13%   |
| Unknown            | 5         | 0.13%   |
| 3840x1100          | 3         | 0.08%   |
| 2256x1504          | 3         | 0.08%   |
| 2240x1400          | 3         | 0.08%   |
| 1400x1050          | 3         | 0.08%   |
| 1280x720 (HD)      | 3         | 0.08%   |
| 2880x1920          | 2         | 0.05%   |
| 2304x1440          | 2         | 0.05%   |
| 800x1280           | 1         | 0.03%   |
| 7680x2160          | 1         | 0.03%   |
| 640x480            | 1         | 0.03%   |
| 3840x1600          | 1         | 0.03%   |
| 3840x1200          | 1         | 0.03%   |
| 2520x1680          | 1         | 0.03%   |
| 2048x1152          | 1         | 0.03%   |
| 1920x540           | 1         | 0.03%   |
| 1920x515           | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1206      | 29.78%  |
| 13      | 969       | 23.93%  |
| 14      | 499       | 12.32%  |
| 11      | 247       | 6.1%    |
| 17      | 212       | 5.23%   |
| 12      | 153       | 3.78%   |
| 24      | 136       | 3.36%   |
| 27      | 107       | 2.64%   |
| 23      | 98        | 2.42%   |
| 21      | 87        | 2.15%   |
| 10      | 52        | 1.28%   |
| Unknown | 36        | 0.89%   |
| 18      | 34        | 0.84%   |
| 19      | 26        | 0.64%   |
| 34      | 25        | 0.62%   |
| 31      | 19        | 0.47%   |
| 16      | 19        | 0.47%   |
| 142     | 15        | 0.37%   |
| 22      | 15        | 0.37%   |
| 25      | 14        | 0.35%   |
| 20      | 12        | 0.3%    |
| 72      | 9         | 0.22%   |
| 32      | 8         | 0.2%    |
| 54      | 6         | 0.15%   |
| 29      | 6         | 0.15%   |
| 8       | 6         | 0.15%   |
| 40      | 5         | 0.12%   |
| 28      | 4         | 0.1%    |
| 84      | 3         | 0.07%   |
| 52      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |
| 46      | 3         | 0.07%   |
| 49      | 2         | 0.05%   |
| 43      | 2         | 0.05%   |
| 33      | 2         | 0.05%   |
| 26      | 2         | 0.05%   |
| 55      | 1         | 0.02%   |
| 47      | 1         | 0.02%   |
| 39      | 1         | 0.02%   |
| 37      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1973      | 49.17%  |
| 201-300        | 1133      | 28.23%  |
| 501-600        | 326       | 8.12%   |
| 351-400        | 249       | 6.2%    |
| 401-500        | 157       | 3.91%   |
| 601-700        | 43        | 1.07%   |
| Unknown        | 36        | 0.9%    |
| 701-800        | 34        | 0.85%   |
| 1001-1500      | 20        | 0.5%    |
| More than 2000 | 15        | 0.37%   |
| 1501-2000      | 12        | 0.3%    |
| 801-900        | 7         | 0.17%   |
| 101-200        | 7         | 0.17%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2681      | 74.27%  |
| 16/10   | 768       | 21.27%  |
| 5/4     | 30        | 0.83%   |
| 4/3     | 30        | 0.83%   |
| 21/9    | 28        | 0.78%   |
| 3/2     | 24        | 0.66%   |
| Unknown | 19        | 0.53%   |
| 1.00    | 15        | 0.42%   |
| 32/9    | 5         | 0.14%   |
| 2.65    | 4         | 0.11%   |
| 3.40    | 3         | 0.08%   |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 1209      | 29.94%  |
| 101-110        | 1205      | 29.84%  |
| 201-250        | 263       | 6.51%   |
| 71-80          | 256       | 6.34%   |
| 51-60          | 250       | 6.19%   |
| 121-130        | 172       | 4.26%   |
| 61-70          | 147       | 3.64%   |
| 301-350        | 108       | 2.67%   |
| 251-300        | 62        | 1.54%   |
| 351-500        | 59        | 1.46%   |
| 151-200        | 59        | 1.46%   |
| 41-50          | 52        | 1.29%   |
| 141-150        | 49        | 1.21%   |
| More than 1000 | 38        | 0.94%   |
| Unknown        | 36        | 0.89%   |
| 131-140        | 22        | 0.54%   |
| 501-1000       | 16        | 0.4%    |
| 91-100         | 15        | 0.37%   |
| 111-120        | 13        | 0.32%   |
| 1-40           | 7         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1627      | 41.11%  |
| 101-120       | 1379      | 34.84%  |
| 51-100        | 558       | 14.1%   |
| 161-240       | 231       | 5.84%   |
| More than 240 | 80        | 2.02%   |
| 1-50          | 47        | 1.19%   |
| Unknown       | 36        | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2955      | 77.91%  |
| 2     | 555       | 14.63%  |
| 0     | 218       | 5.75%   |
| 3     | 63        | 1.66%   |
| 5     | 1         | 0.03%   |
| 4     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1820      | 30.31%  |
| Realtek Semiconductor             | 1585      | 26.4%   |
| Qualcomm Atheros                  | 812       | 13.52%  |
| Broadcom                          | 605       | 10.08%  |
| Nvidia                            | 319       | 5.31%   |
| Broadcom Limited                  | 224       | 3.73%   |
| Marvell Technology Group          | 139       | 2.32%   |
| Ralink                            | 52        | 0.87%   |
| MediaTek                          | 35        | 0.58%   |
| TP-Link                           | 34        | 0.57%   |
| ASIX Electronics                  | 32        | 0.53%   |
| Dell                              | 29        | 0.48%   |
| Lenovo                            | 26        | 0.43%   |
| JMicron Technology                | 25        | 0.42%   |
| Sierra Wireless                   | 23        | 0.38%   |
| Samsung Electronics               | 23        | 0.38%   |
| Ralink Technology                 | 17        | 0.28%   |
| Ericsson Business Mobile Networks | 17        | 0.28%   |
| Qualcomm                          | 14        | 0.23%   |
| Huawei Technologies               | 14        | 0.23%   |
| DisplayLink                       | 14        | 0.23%   |
| FIBOCOM                           | 12        | 0.2%    |
| Xiaomi                            | 11        | 0.18%   |
| Silicon Integrated Systems [SiS]  | 10        | 0.17%   |
| Hewlett-Packard                   | 10        | 0.17%   |
| Qualcomm Atheros Communications   | 8         | 0.13%   |
| Cypress Semiconductor             | 8         | 0.13%   |
| ICS Advent                        | 6         | 0.1%    |
| Attansic Technology               | 6         | 0.1%    |
| NetGear                           | 5         | 0.08%   |
| ASUSTek Computer                  | 5         | 0.08%   |
| Apple                             | 5         | 0.08%   |
| Motorola PCS                      | 4         | 0.07%   |
| Microchip Technology              | 4         | 0.07%   |
| AMD                               | 4         | 0.07%   |
| U-Blox                            | 3         | 0.05%   |
| Edimax Technology                 | 3         | 0.05%   |
| 3Com                              | 3         | 0.05%   |
| Wilocity                          | 2         | 0.03%   |
| ULi Electronics                   | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 981       | 13.81%  |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 310       | 4.36%   |
| Nvidia MCP79 Ethernet                                                                 | 309       | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 291       | 4.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 172       | 2.42%   |
| Intel Wireless 7260                                                                   | 172       | 2.42%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 151       | 2.13%   |
| Intel Wireless 8265 / 8275                                                            | 146       | 2.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 144       | 2.03%   |
| Intel Wi-Fi 6 AX200                                                                   | 143       | 2.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 138       | 1.94%   |
| Intel Wireless 7265                                                                   | 132       | 1.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 124       | 1.75%   |
| Intel Wi-Fi 6 AX201                                                                   | 104       | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 103       | 1.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 98        | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 96        | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 87        | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 84        | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 82        | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 79        | 1.11%   |
| Intel Wireless 8260                                                                   | 79        | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 73        | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 63        | 0.89%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 58        | 0.82%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 55        | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 54        | 0.76%   |
| Intel Ethernet Connection (4) I219-V                                                  | 52        | 0.73%   |
| Intel Wireless 3165                                                                   | 51        | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 48        | 0.68%   |
| Intel Ethernet Connection I219-LM                                                     | 46        | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 45        | 0.63%   |
| Intel Ethernet Connection I218-LM                                                     | 41        | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 41        | 0.58%   |
| Intel 82577LM Gigabit Network Connection                                              | 38        | 0.53%   |
| Intel Ethernet Connection (6) I219-V                                                  | 37        | 0.52%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 37        | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 36        | 0.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 36        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1724      | 45.48%  |
| Qualcomm Atheros                  | 731       | 19.28%  |
| Broadcom                          | 516       | 13.61%  |
| Realtek Semiconductor             | 416       | 10.97%  |
| Broadcom Limited                  | 192       | 5.06%   |
| Ralink                            | 52        | 1.37%   |
| MediaTek                          | 33        | 0.87%   |
| Sierra Wireless                   | 23        | 0.61%   |
| TP-Link                           | 18        | 0.47%   |
| Ralink Technology                 | 17        | 0.45%   |
| Dell                              | 15        | 0.4%    |
| Fibocom                           | 11        | 0.29%   |
| Qualcomm Atheros Communications   | 8         | 0.21%   |
| Qualcomm                          | 5         | 0.13%   |
| NetGear                           | 5         | 0.13%   |
| ASUSTek Computer                  | 5         | 0.13%   |
| Hewlett-Packard                   | 3         | 0.08%   |
| Edimax Technology                 | 3         | 0.08%   |
| Wilocity                          | 2         | 0.05%   |
| Ericsson Business Mobile Networks | 2         | 0.05%   |
| Belkin Components                 | 2         | 0.05%   |
| 3Com                              | 2         | 0.05%   |
| ZyXEL Communications              | 1         | 0.03%   |
| Z-Com                             | 1         | 0.03%   |
| Quectel Wireless Solutions        | 1         | 0.03%   |
| Microsoft                         | 1         | 0.03%   |
| D-Link System                     | 1         | 0.03%   |
| Cinterion                         | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 310       | 8.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 172       | 4.52%   |
| Intel Wireless 7260                                                                   | 172       | 4.52%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 151       | 3.96%   |
| Intel Wireless 8265 / 8275                                                            | 146       | 3.83%   |
| Intel Wi-Fi 6 AX200                                                                   | 143       | 3.75%   |
| Intel Wireless 7265                                                                   | 132       | 3.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 124       | 3.26%   |
| Intel Wi-Fi 6 AX201                                                                   | 104       | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 103       | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 98        | 2.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 96        | 2.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 87        | 2.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 84        | 2.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 82        | 2.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 79        | 2.07%   |
| Intel Wireless 8260                                                                   | 79        | 2.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 73        | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 63        | 1.65%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 55        | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 54        | 1.42%   |
| Intel Wireless 3165                                                                   | 51        | 1.34%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 48        | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 37        | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 36        | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 36        | 0.95%   |
| Intel Wireless-AC 9260                                                                | 34        | 0.89%   |
| Intel Wireless 3160                                                                   | 33        | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 33        | 0.87%   |
| Intel Centrino Ultimate-N 6300                                                        | 31        | 0.81%   |
| Intel Centrino Advanced-N 6200                                                        | 30        | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 29        | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 28        | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 27        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 27        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 26        | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 25        | 0.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 25        | 0.66%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 25        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1442      | 45.65%  |
| Intel                            | 718       | 22.73%  |
| Nvidia                           | 319       | 10.1%   |
| Qualcomm Atheros                 | 169       | 5.35%   |
| Marvell Technology Group         | 139       | 4.4%    |
| Broadcom                         | 114       | 3.61%   |
| Broadcom Limited                 | 33        | 1.04%   |
| ASIX Electronics                 | 32        | 1.01%   |
| Lenovo                           | 26        | 0.82%   |
| JMicron Technology               | 25        | 0.79%   |
| Samsung Electronics              | 23        | 0.73%   |
| TP-Link                          | 16        | 0.51%   |
| DisplayLink                      | 14        | 0.44%   |
| Xiaomi                           | 11        | 0.35%   |
| Silicon Integrated Systems [SiS] | 10        | 0.32%   |
| Huawei Technologies              | 9         | 0.28%   |
| Qualcomm                         | 8         | 0.25%   |
| Cypress Semiconductor            | 8         | 0.25%   |
| ICS Advent                       | 6         | 0.19%   |
| Attansic Technology              | 6         | 0.19%   |
| Apple                            | 5         | 0.16%   |
| Microchip Technology             | 4         | 0.13%   |
| Motorola PCS                     | 3         | 0.09%   |
| Spreadtrum Communications        | 2         | 0.06%   |
| OPPO Electronics                 | 2         | 0.06%   |
| National Semiconductor           | 2         | 0.06%   |
| MediaTek                         | 2         | 0.06%   |
| LG Electronics                   | 2         | 0.06%   |
| Hewlett-Packard                  | 2         | 0.06%   |
| D-Link                           | 2         | 0.06%   |
| VIA Technologies                 | 1         | 0.03%   |
| Google                           | 1         | 0.03%   |
| Foxconn / Hon Hai                | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |
| 3Com                             | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 981       | 30.73%  |
| Nvidia MCP79 Ethernet                                             | 309       | 9.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 291       | 9.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 144       | 4.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 138       | 4.32%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 58        | 1.82%   |
| Intel Ethernet Connection (4) I219-V                              | 52        | 1.63%   |
| Intel Ethernet Connection I219-LM                                 | 46        | 1.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 45        | 1.41%   |
| Intel Ethernet Connection I218-LM                                 | 41        | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 41        | 1.28%   |
| Intel 82577LM Gigabit Network Connection                          | 38        | 1.19%   |
| Intel Ethernet Connection (6) I219-V                              | 37        | 1.16%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 29        | 0.91%   |
| Intel 82567LM Gigabit Network Connection                          | 29        | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 28        | 0.88%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 24        | 0.75%   |
| Intel Ethernet Connection (10) I219-V                             | 23        | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 22        | 0.69%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 21        | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 20        | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 20        | 0.63%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 18        | 0.56%   |
| Intel Ethernet Connection (13) I219-V                             | 18        | 0.56%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 15        | 0.47%   |
| Intel 82579V Gigabit Network Connection                           | 15        | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14        | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 14        | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 13        | 0.41%   |
| Intel 82566MM Gigabit Network Connection                          | 13        | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12        | 0.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 12        | 0.38%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 12        | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 11        | 0.34%   |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 0.34%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 11        | 0.34%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 11        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3650      | 53.8%   |
| Ethernet | 3030      | 44.66%  |
| Modem    | 96        | 1.42%   |
| Unknown  | 8         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2881      | 73.42%  |
| Ethernet | 1042      | 26.55%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2760      | 74.17%  |
| 1     | 880       | 23.65%  |
| 0     | 47        | 1.26%   |
| 3     | 32        | 0.86%   |
| 5     | 1         | 0.03%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3258      | 86.63%  |
| Yes  | 503       | 13.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1290      | 42.7%   |
| Apple                           | 562       | 18.6%   |
| Qualcomm Atheros Communications | 280       | 9.27%   |
| Realtek Semiconductor           | 242       | 8.01%   |
| Broadcom                        | 146       | 4.83%   |
| Lite-On Technology              | 107       | 3.54%   |
| IMC Networks                    | 104       | 3.44%   |
| Foxconn / Hon Hai               | 64        | 2.12%   |
| Dell                            | 51        | 1.69%   |
| Hewlett-Packard                 | 37        | 1.22%   |
| Cambridge Silicon Radio         | 35        | 1.16%   |
| ASUSTek Computer                | 22        | 0.73%   |
| Toshiba                         | 19        | 0.63%   |
| Ralink                          | 18        | 0.6%    |
| Realtek                         | 16        | 0.53%   |
| Foxconn International           | 7         | 0.23%   |
| Alps Electric                   | 5         | 0.17%   |
| Ralink Technology               | 4         | 0.13%   |
| Taiyo Yuden                     | 3         | 0.1%    |
| Unknown                         | 2         | 0.07%   |
| MediaTek                        | 2         | 0.07%   |
| Qcom                            | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 573       | 18.95%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 300       | 9.92%   |
| Intel AX201 Bluetooth                               | 222       | 7.34%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 205       | 6.78%   |
| Qualcomm Atheros  Bluetooth Device                  | 162       | 5.36%   |
| Realtek Bluetooth Radio                             | 152       | 5.03%   |
| Apple Bluetooth USB Host Controller                 | 150       | 4.96%   |
| Intel AX200 Bluetooth                               | 138       | 4.56%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.51%   |
| Realtek  Bluetooth 4.2 Adapter                      | 65        | 2.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 43        | 1.42%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 39        | 1.29%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 35        | 1.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 35        | 1.16%   |
| Broadcom BCM2045B (BDC-2.1)                         | 35        | 1.16%   |
| IMC Networks Bluetooth Radio                        | 31        | 1.03%   |
| IMC Networks Bluetooth Device                       | 31        | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 30        | 0.99%   |
| Apple Bluetooth Host Controller                     | 29        | 0.96%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 27        | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 26        | 0.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 26        | 0.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 25        | 0.83%   |
| Lite-On Bluetooth Device                            | 25        | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 25        | 0.83%   |
| Foxconn / Hon Hai Bluetooth Device                  | 25        | 0.83%   |
| Ralink RT3290 Bluetooth                             | 18        | 0.6%    |
| Intel AX210 Bluetooth                               | 18        | 0.6%    |
| Dell DW375 Bluetooth Module                         | 18        | 0.6%    |
| Intel Bluetooth Device                              | 17        | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 17        | 0.56%   |
| Realtek Bluetooth Radio                             | 16        | 0.53%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.53%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 15        | 0.5%    |
| Dell BCM20702A0 Bluetooth Module                    | 13        | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.4%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 12        | 0.4%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 11        | 0.36%   |
| Foxconn / Hon Hai Wireless_Device                   | 11        | 0.36%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 10        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2844      | 66.36%  |
| Nvidia                               | 643       | 15%     |
| AMD                                  | 552       | 12.88%  |
| C-Media Electronics                  | 28        | 0.65%   |
| Logitech                             | 25        | 0.58%   |
| Lenovo                               | 22        | 0.51%   |
| Realtek Semiconductor                | 21        | 0.49%   |
| Texas Instruments                    | 17        | 0.4%    |
| GN Netcom                            | 13        | 0.3%    |
| Plantronics                          | 12        | 0.28%   |
| Silicon Integrated Systems [SiS]     | 11        | 0.26%   |
| Hewlett-Packard                      | 10        | 0.23%   |
| Generalplus Technology               | 9         | 0.21%   |
| Creative Technology                  | 6         | 0.14%   |
| RODE Microphones                     | 3         | 0.07%   |
| Razer USA                            | 3         | 0.07%   |
| Microsoft                            | 3         | 0.07%   |
| Kingston Technology                  | 3         | 0.07%   |
| JMTek                                | 3         | 0.07%   |
| Focusrite-Novation                   | 3         | 0.07%   |
| Dell                                 | 3         | 0.07%   |
| ASUSTek Computer                     | 3         | 0.07%   |
| VIA Technologies                     | 2         | 0.05%   |
| ULi Electronics                      | 2         | 0.05%   |
| Sennheiser Communications            | 2         | 0.05%   |
| M-Audio                              | 2         | 0.05%   |
| ESS Technology                       | 2         | 0.05%   |
| CMX Systems                          | 2         | 0.05%   |
| Blue Microphones                     | 2         | 0.05%   |
| BEHRINGER International              | 2         | 0.05%   |
| Apple                                | 2         | 0.05%   |
| Yamaha                               | 1         | 0.02%   |
| XMOS                                 | 1         | 0.02%   |
| Veho                                 | 1         | 0.02%   |
| Trust                                | 1         | 0.02%   |
| Toshiba                              | 1         | 0.02%   |
| Thomann                              | 1         | 0.02%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.02%   |
| SteelSeries ApS                      | 1         | 0.02%   |
| Sony                                 | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 439       | 8.49%   |
| Nvidia MCP79 High Definition Audio                                                                | 310       | 6%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 291       | 5.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 276       | 5.34%   |
| Intel Broadwell-U Audio Controller                                                                | 253       | 4.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 251       | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 183       | 3.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 150       | 2.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 146       | 2.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 139       | 2.69%   |
| Intel Cannon Lake PCH cAVS                                                                        | 133       | 2.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 125       | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 125       | 2.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 123       | 2.38%   |
| Intel 8 Series HD Audio Controller                                                                | 123       | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 113       | 2.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 108       | 2.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 106       | 2.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 104       | 2.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 86        | 1.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 83        | 1.61%   |
| AMD FCH Azalia Controller                                                                         | 83        | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 77        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 73        | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 65        | 1.26%   |
| Intel Comet Lake PCH cAVS                                                                         | 62        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 62        | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 51        | 0.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 42        | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 40        | 0.77%   |
| Intel CM238 HD Audio Controller                                                                   | 39        | 0.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 36        | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 35        | 0.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 34        | 0.66%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 31        | 0.6%    |
| AMD High Definition Audio Controller                                                              | 29        | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 28        | 0.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 26        | 0.5%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 26        | 0.5%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 24        | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 1036      | 29.6%   |
| Samsung Electronics          | 923       | 26.37%  |
| Micron Technology            | 356       | 10.17%  |
| Kingston                     | 236       | 6.74%   |
| Unknown                      | 225       | 6.43%   |
| Crucial                      | 183       | 5.23%   |
| Elpida                       | 109       | 3.11%   |
| Ramaxel Technology           | 66        | 1.89%   |
| A-DATA Technology            | 65        | 1.86%   |
| Nanya Technology             | 39        | 1.11%   |
| Corsair                      | 35        | 1%      |
| Smart                        | 26        | 0.74%   |
| Unknown                      | 26        | 0.74%   |
| Unknown (ABCD)               | 20        | 0.57%   |
| GOODRAM                      | 20        | 0.57%   |
| G.Skill                      | 16        | 0.46%   |
| Team                         | 14        | 0.4%    |
| Transcend                    | 13        | 0.37%   |
| Teikon                       | 10        | 0.29%   |
| Apacer                       | 7         | 0.2%    |
| 48spaces                     | 7         | 0.2%    |
| Patriot                      | 6         | 0.17%   |
| Smart Brazil                 | 5         | 0.14%   |
| Silicon Power                | 5         | 0.14%   |
| ASint Technology             | 5         | 0.14%   |
| Wilk                         | 3         | 0.09%   |
| PNY                          | 3         | 0.09%   |
| Neo Forza                    | 3         | 0.09%   |
| Goldkey                      | 3         | 0.09%   |
| Avant                        | 3         | 0.09%   |
| AMD                          | 3         | 0.09%   |
| Unknown (89F7)               | 2         | 0.06%   |
| TEXTORM                      | 2         | 0.06%   |
| Infineon                     | 2         | 0.06%   |
| High Bridge                  | 2         | 0.06%   |
| Essencore                    | 2         | 0.06%   |
| CSX                          | 2         | 0.06%   |
| Unknown (D386)               | 1         | 0.03%   |
| Unknown (0x08A4FFFFFFFFFFFF) | 1         | 0.03%   |
| Unknown (08C8)               | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 256       | 6.95%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.84%   |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s         | 66        | 1.79%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 61        | 1.65%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 43        | 1.17%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 37        | 1%      |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 36        | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 32        | 0.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 32        | 0.87%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 31        | 0.84%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 29        | 0.79%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 29        | 0.79%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 29        | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.73%   |
| Unknown                                                          | 26        | 0.71%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.68%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 24        | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 24        | 0.65%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 23        | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 23        | 0.62%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 22        | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.6%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 22        | 0.6%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 21        | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 0.54%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 20        | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.54%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 18        | 0.49%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 18        | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 16        | 0.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 16        | 0.43%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 16        | 0.43%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s             | 16        | 0.43%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 16        | 0.43%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 15        | 0.41%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.41%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 15        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1151      | 37.71%  |
| DDR3    | 1054      | 34.53%  |
| DDR2    | 512       | 16.78%  |
| LPDDR3  | 104       | 3.41%   |
| LPDDR4  | 97        | 3.18%   |
| SDRAM   | 64        | 2.1%    |
| DDR     | 34        | 1.11%   |
| Unknown | 13        | 0.43%   |
| DDR5    | 9         | 0.29%   |
| DRAM    | 8         | 0.26%   |
| LPDDR5  | 5         | 0.16%   |
| RAM     | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2800      | 91.59%  |
| Row Of Chips | 183       | 5.99%   |
| Unknown      | 41        | 1.34%   |
| Chip         | 27        | 0.88%   |
| DIMM         | 6         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 939       | 28.37%  |
| 4096  | 908       | 27.43%  |
| 2048  | 525       | 15.86%  |
| 1024  | 496       | 14.98%  |
| 16384 | 326       | 9.85%   |
| 32768 | 64        | 1.93%   |
| 512   | 35        | 1.06%   |
| 256   | 15        | 0.45%   |
| 128   | 2         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 804       | 24.63%  |
| 2667    | 578       | 17.71%  |
| 3200    | 409       | 12.53%  |
| 800     | 326       | 9.99%   |
| 2400    | 195       | 5.97%   |
| 667     | 158       | 4.84%   |
| 2133    | 138       | 4.23%   |
| 1334    | 134       | 4.11%   |
| 1333    | 112       | 3.43%   |
| Unknown | 82        | 2.51%   |
| 1067    | 45        | 1.38%   |
| 4267    | 44        | 1.35%   |
| 1867    | 39        | 1.19%   |
| 3266    | 32        | 0.98%   |
| 4199    | 23        | 0.7%    |
| 533     | 19        | 0.58%   |
| 975     | 17        | 0.52%   |
| 2048    | 14        | 0.43%   |
| 8400    | 13        | 0.4%    |
| 1066    | 13        | 0.4%    |
| 4800    | 11        | 0.34%   |
| 400     | 10        | 0.31%   |
| 4266    | 9         | 0.28%   |
| 333     | 9         | 0.28%   |
| 266     | 8         | 0.25%   |
| 1866    | 6         | 0.18%   |
| 6400    | 4         | 0.12%   |
| 3733    | 2         | 0.06%   |
| 2933    | 2         | 0.06%   |
| 1776    | 2         | 0.06%   |
| 933     | 2         | 0.06%   |
| 3000    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1596    | 1         | 0.03%   |
| 200     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 40%     |
| Xerox               | 4         | 16%     |
| Brother Industries  | 3         | 12%     |
| Samsung Electronics | 2         | 8%      |
| Canon               | 2         | 8%      |
| Xiaomi              | 1         | 4%      |
| STMicroelectronics  | 1         | 4%      |
| Pantum              | 1         | 4%      |
| Kyocera             | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 4         | 15.38%  |
| Xiaomi MiMouse 2                                          | 1         | 3.85%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.85%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 3.85%   |
| Samsung CLX-3300 Series                                   | 1         | 3.85%   |
| Pantum P2500W series                                      | 1         | 3.85%   |
| Kyocera ECOSYS P2335d                                     | 1         | 3.85%   |
| HP OfficeJet 3830 series                                  | 1         | 3.85%   |
| HP LaserJet P1102                                         | 1         | 3.85%   |
| HP LaserJet 1200                                          | 1         | 3.85%   |
| HP LaserJet 1160 series                                   | 1         | 3.85%   |
| HP LaserJet 1022                                          | 1         | 3.85%   |
| HP LaserJet 1020                                          | 1         | 3.85%   |
| HP Ink Tank 110 series                                    | 1         | 3.85%   |
| HP EWS UPD                                                | 1         | 3.85%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 3.85%   |
| HP Deskjet 2540 series                                    | 1         | 3.85%   |
| HP DeskJet 2130 series                                    | 1         | 3.85%   |
| Canon PIXMA MX920 Series                                  | 1         | 3.85%   |
| Canon LBP3010/LBP3018/LBP3050                             | 1         | 3.85%   |
| Brother PT-9500PC                                         | 1         | 3.85%   |
| Brother MFC-L2707DW                                       | 1         | 3.85%   |
| Brother HL-L2340D series                                  | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 45.45%  |
| Seiko Epson     | 4         | 36.36%  |
| Mustek Systems  | 1         | 9.09%   |
| Hewlett-Packard | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                           | 2         | 18.18%  |
| Seiko Epson GT-9800F [Perfection 3200]            | 1         | 9.09%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]     | 1         | 9.09%   |
| Seiko Epson GT-7700U [Perfection 1240U]           | 1         | 9.09%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 9.09%   |
| Mustek Systems SNAPSCAN e22                       | 1         | 9.09%   |
| HP Scanjet 200                                    | 1         | 9.09%   |
| Canon CanoScan LIDE 25                            | 1         | 9.09%   |
| Canon CanoScan LiDE 220                           | 1         | 9.09%   |
| Canon CanoScan LiDE 110                           | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 673       | 23.83%  |
| IMC Networks                           | 317       | 11.23%  |
| Acer                                   | 270       | 9.56%   |
| Realtek Semiconductor                  | 244       | 8.64%   |
| Microdia                               | 242       | 8.57%   |
| Quanta                                 | 211       | 7.47%   |
| Sunplus Innovation Technology          | 155       | 5.49%   |
| Suyin                                  | 98        | 3.47%   |
| Cheng Uei Precision Industry (Foxlink) | 90        | 3.19%   |
| Lite-On Technology                     | 71        | 2.51%   |
| Syntek                                 | 59        | 2.09%   |
| Luxvisions Innotech Limited            | 46        | 1.63%   |
| Logitech                               | 44        | 1.56%   |
| Apple                                  | 44        | 1.56%   |
| Silicon Motion                         | 43        | 1.52%   |
| Alcor Micro                            | 29        | 1.03%   |
| Ricoh                                  | 28        | 0.99%   |
| Lenovo                                 | 24        | 0.85%   |
| Z-Star Microelectronics                | 16        | 0.57%   |
| Samsung Electronics                    | 12        | 0.42%   |
| Primax Electronics                     | 11        | 0.39%   |
| ALi                                    | 9         | 0.32%   |
| Sonix Technology                       | 8         | 0.28%   |
| Genesys Logic                          | 6         | 0.21%   |
| Importek                               | 5         | 0.18%   |
| OmniVision Technologies                | 4         | 0.14%   |
| icSpring                               | 4         | 0.14%   |
| SunplusIT                              | 3         | 0.11%   |
| Sunplus Technology                     | 3         | 0.11%   |
| Microsoft                              | 3         | 0.11%   |
| MacroSilicon                           | 3         | 0.11%   |
| Intel                                  | 3         | 0.11%   |
| GEMBIRD                                | 3         | 0.11%   |
| Unknown                                | 2         | 0.07%   |
| Tobii Technology AB                    | 2         | 0.07%   |
| Pixart Imaging                         | 2         | 0.07%   |
| Mimaki Engineering                     | 2         | 0.07%   |
| Generalplus Technology                 | 2         | 0.07%   |
| eMPIA Technology                       | 2         | 0.07%   |
| Cubeternet                             | 2         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 189       | 6.65%   |
| Microdia Integrated_Webcam_HD                       | 115       | 4.05%   |
| IMC Networks Integrated Camera                      | 111       | 3.91%   |
| Realtek Integrated_Webcam_HD                        | 87        | 3.06%   |
| Quanta Chromebook HD Camera                         | 68        | 2.39%   |
| Acer Integrated Camera                              | 67        | 2.36%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 65        | 2.29%   |
| Chicony HD Webcam                                   | 65        | 2.29%   |
| Acer BisonCam, NB Pro                               | 54        | 1.9%    |
| Sunplus Integrated_Webcam_HD                        | 51        | 1.79%   |
| Chicony HP HD Camera                                | 34        | 1.2%    |
| Lite-On Integrated Camera                           | 31        | 1.09%   |
| Chicony USB2.0 HD UVC WebCam                        | 31        | 1.09%   |
| Syntek Integrated Camera                            | 30        | 1.06%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 30        | 1.06%   |
| Quanta HP TrueVision HD Camera                      | 29        | 1.02%   |
| Acer SunplusIT Integrated Camera                    | 27        | 0.95%   |
| Acer Lenovo EasyCamera                              | 24        | 0.84%   |
| Microdia Integrated Webcam                          | 22        | 0.77%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 22        | 0.77%   |
| Quanta VGA WebCam                                   | 21        | 0.74%   |
| Chicony Integrated Camera (1280x720@30)             | 21        | 0.74%   |
| Sunplus HD WebCam                                   | 20        | 0.7%    |
| Realtek USB Camera                                  | 20        | 0.7%    |
| Realtek USB2.0 HD UVC WebCam                        | 19        | 0.67%   |
| Quanta HD User Facing                               | 19        | 0.67%   |
| Quanta HP HD Camera                                 | 18        | 0.63%   |
| Acer Lenovo Integrated Webcam                       | 18        | 0.63%   |
| Realtek Integrated Webcam                           | 17        | 0.6%    |
| Lite-On HP HD Camera                                | 17        | 0.6%    |
| Chicony HD User Facing                              | 17        | 0.6%    |
| Suyin HP Truevision HD                              | 16        | 0.56%   |
| Chicony USB2.0 Camera                               | 16        | 0.56%   |
| Chicony HP Webcam                                   | 16        | 0.56%   |
| Apple iPhone5/5C/5S/6                               | 16        | 0.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 15        | 0.53%   |
| IMC Networks HD Camera                              | 15        | 0.53%   |
| Chicony Lenovo EasyCamera                           | 15        | 0.53%   |
| Chicony HP Truevision HD camera                     | 15        | 0.53%   |
| Chicony Chromebook HD Camera                        | 15        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 202       | 33.28%  |
| Synaptics                  | 184       | 30.31%  |
| Shenzhen Goodix Technology | 79        | 13.01%  |
| AuthenTec                  | 40        | 6.59%   |
| Upek                       | 36        | 5.93%   |
| Elan Microelectronics      | 31        | 5.11%   |
| LighTuning Technology      | 20        | 3.29%   |
| STMicroelectronics         | 13        | 2.14%   |
| Samsung Electronics        | 1         | 0.16%   |
| Microsoft                  | 1         | 0.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 84        | 13.84%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 51        | 8.4%    |
| Shenzhen Goodix  FingerPrint Device                                        | 46        | 7.58%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 41        | 6.75%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 35        | 5.77%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 33        | 5.44%   |
| Unknown                                                                    | 26        | 4.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 25        | 4.12%   |
| Elan ELAN:Fingerprint                                                      | 21        | 3.46%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 3.13%   |
| AuthenTec AES2810                                                          | 16        | 2.64%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 14        | 2.31%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 14        | 2.31%   |
| Shenzhen Goodix FingerPrint                                                | 14        | 2.31%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 2.14%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 1.98%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 1.98%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.81%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 11        | 1.81%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 1.81%   |
| Elan ELAN:ARM-M4                                                           | 10        | 1.65%   |
| Validity Sensors VFS Fingerprint sensor                                    | 9         | 1.48%   |
| Synaptics  WBDI                                                            | 9         | 1.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 1.32%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.32%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.15%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.99%   |
| Validity Sensors VFS491                                                    | 5         | 0.82%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.66%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.66%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.66%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.49%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.49%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.49%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.33%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.33%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.33%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.33%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.16%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 114       | 37.13%  |
| Alcor Micro               | 111       | 36.16%  |
| Upek                      | 24        | 7.82%   |
| Lenovo                    | 22        | 7.17%   |
| O2 Micro                  | 21        | 6.84%   |
| Gemalto (was Gemplus)     | 3         | 0.98%   |
| Clay Logic                | 3         | 0.98%   |
| Yubico.com                | 2         | 0.65%   |
| Aladdin Knowledge Systems | 2         | 0.65%   |
| SCM Microsystems          | 1         | 0.33%   |
| OmniKey                   | 1         | 0.33%   |
| Cherry                    | 1         | 0.33%   |
| C3PO                      | 1         | 0.33%   |
| Advanced Card Systems     | 1         | 0.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 109       | 35.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 39        | 12.7%   |
| Broadcom 5880                                                                | 29        | 9.45%   |
| Broadcom 58200                                                               | 27        | 8.79%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 7.82%   |
| Lenovo Integrated Smart Card Reader                                          | 22        | 7.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 5.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 5.86%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.98%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.65%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.65%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.65%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.65%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.65%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.33%   |
| OmniKey CardMan 4321                                                         | 1         | 0.33%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.33%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.33%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.33%   |
| C3PO LTC31v2                                                                 | 1         | 0.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.33%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2188      | 57.72%  |
| 1     | 1226      | 32.34%  |
| 2     | 297       | 7.83%   |
| 3     | 68        | 1.79%   |
| 4     | 7         | 0.18%   |
| 5     | 4         | 0.11%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 603       | 30.56%  |
| Graphics card            | 483       | 24.48%  |
| Chipcard                 | 278       | 14.09%  |
| Multimedia controller    | 221       | 11.2%   |
| Net/wireless             | 162       | 8.21%   |
| Bluetooth                | 53        | 2.69%   |
| Card reader              | 35        | 1.77%   |
| Camera                   | 34        | 1.72%   |
| Storage                  | 31        | 1.57%   |
| Communication controller | 27        | 1.37%   |
| Sound                    | 11        | 0.56%   |
| Net/ethernet             | 11        | 0.56%   |
| Network                  | 7         | 0.35%   |
| Modem                    | 6         | 0.3%    |
| Flash memory             | 4         | 0.2%    |
| Unassigned class         | 2         | 0.1%    |
| Firewire controller      | 2         | 0.1%    |
| Wireless                 | 1         | 0.05%   |
| Tv card                  | 1         | 0.05%   |
| Storage/ide              | 1         | 0.05%   |

