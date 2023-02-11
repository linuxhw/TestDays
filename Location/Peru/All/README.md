Linux in Peru - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Linux in Peru.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Peru/Desktop/README.md) and [notebooks](/Location/Peru/Notebook/README.md).

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

Total: 498

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550M-A               | Desktop     | [2e458676e4](https://linux-hardware.org/?probe=2e458676e4) | Feb 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5dbc5260b2](https://linux-hardware.org/?probe=5dbc5260b2) | Jan 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [7c0c804a3e](https://linux-hardware.org/?probe=7c0c804a3e) | Jan 29, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [7b08eeb50c](https://linux-hardware.org/?probe=7b08eeb50c) | Jan 29, 2023 |
| HP            | ProLiant DL380e Gen8        | Server      | [72b9753b42](https://linux-hardware.org/?probe=72b9753b42) | Jan 26, 2023 |
| HP            | ProLiant DL380e Gen8        | Server      | [2bc6c62201](https://linux-hardware.org/?probe=2bc6c62201) | Jan 26, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [d2ec58874c](https://linux-hardware.org/?probe=d2ec58874c) | Jan 21, 2023 |
| HP            | 1850                        | Desktop     | [ccad003ff4](https://linux-hardware.org/?probe=ccad003ff4) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [07b3eb6453](https://linux-hardware.org/?probe=07b3eb6453) | Jan 20, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [16f5bae11f](https://linux-hardware.org/?probe=16f5bae11f) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c16356f056](https://linux-hardware.org/?probe=c16356f056) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [70b8007dcc](https://linux-hardware.org/?probe=70b8007dcc) | Jan 17, 2023 |
| MSI           | B350M GAMING PRO            | Desktop     | [df317ef3c8](https://linux-hardware.org/?probe=df317ef3c8) | Jan 11, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [1e3f42b7d1](https://linux-hardware.org/?probe=1e3f42b7d1) | Jan 10, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [d35d765c2f](https://linux-hardware.org/?probe=d35d765c2f) | Jan 09, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [afd3f452a1](https://linux-hardware.org/?probe=afd3f452a1) | Jan 07, 2023 |
| Acer          | Aspire VN7-571G             | Notebook    | [88e5718807](https://linux-hardware.org/?probe=88e5718807) | Jan 03, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a30f96dea4](https://linux-hardware.org/?probe=a30f96dea4) | Dec 31, 2022 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [d7daff3ed1](https://linux-hardware.org/?probe=d7daff3ed1) | Dec 27, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [8b34b357bb](https://linux-hardware.org/?probe=8b34b357bb) | Dec 27, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [08800ce691](https://linux-hardware.org/?probe=08800ce691) | Dec 19, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [36a0b6f8d9](https://linux-hardware.org/?probe=36a0b6f8d9) | Dec 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [61dd034d23](https://linux-hardware.org/?probe=61dd034d23) | Dec 16, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [8525777743](https://linux-hardware.org/?probe=8525777743) | Dec 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [951b5a453d](https://linux-hardware.org/?probe=951b5a453d) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [17cbc91488](https://linux-hardware.org/?probe=17cbc91488) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [4b9eb9fcab](https://linux-hardware.org/?probe=4b9eb9fcab) | Dec 10, 2022 |
| Lenovo        | IdeaPad U400 099342G        | Notebook    | [9ecbde32ab](https://linux-hardware.org/?probe=9ecbde32ab) | Dec 06, 2022 |
| HP            | 8767 A                      | Desktop     | [1d4dc77fa3](https://linux-hardware.org/?probe=1d4dc77fa3) | Dec 06, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2436f4cf5e](https://linux-hardware.org/?probe=2436f4cf5e) | Nov 30, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0bd83a29f4](https://linux-hardware.org/?probe=0bd83a29f4) | Nov 29, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [763f309094](https://linux-hardware.org/?probe=763f309094) | Nov 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [10b5bb5eab](https://linux-hardware.org/?probe=10b5bb5eab) | Nov 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c765249482](https://linux-hardware.org/?probe=c765249482) | Nov 17, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8600d864a4](https://linux-hardware.org/?probe=8600d864a4) | Nov 13, 2022 |
| Deltron       | H81H3-M4                    | Desktop     | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [eebc3537d1](https://linux-hardware.org/?probe=eebc3537d1) | Nov 09, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [b4d22497e8](https://linux-hardware.org/?probe=b4d22497e8) | Nov 08, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [b97ba1d3f0](https://linux-hardware.org/?probe=b97ba1d3f0) | Nov 07, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [e8a62297a5](https://linux-hardware.org/?probe=e8a62297a5) | Nov 05, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [88a69a9a20](https://linux-hardware.org/?probe=88a69a9a20) | Nov 05, 2022 |
| Dell          | Latitude E5470              | Notebook    | [4de6b7bdb8](https://linux-hardware.org/?probe=4de6b7bdb8) | Nov 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [717e0e6d40](https://linux-hardware.org/?probe=717e0e6d40) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [209e99f964](https://linux-hardware.org/?probe=209e99f964) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [f12fc289fa](https://linux-hardware.org/?probe=f12fc289fa) | Nov 02, 2022 |
| HP            | 2B3B                        | All in one  | [a42ac6f6c7](https://linux-hardware.org/?probe=a42ac6f6c7) | Nov 01, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dca18dced0](https://linux-hardware.org/?probe=dca18dced0) | Oct 30, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [2f79de6974](https://linux-hardware.org/?probe=2f79de6974) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a977f9c3e9](https://linux-hardware.org/?probe=a977f9c3e9) | Oct 26, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| ADVANCE       | PS5077                      | Notebook    | [998e544711](https://linux-hardware.org/?probe=998e544711) | Oct 22, 2022 |
| ADVANCE       | PS5077                      | Notebook    | [97bfff0fc6](https://linux-hardware.org/?probe=97bfff0fc6) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [07acd27a70](https://linux-hardware.org/?probe=07acd27a70) | Oct 21, 2022 |
| Dell          | Latitude E5470              | Notebook    | [11ad7cd084](https://linux-hardware.org/?probe=11ad7cd084) | Oct 20, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [ee436e327b](https://linux-hardware.org/?probe=ee436e327b) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [86e01f1479](https://linux-hardware.org/?probe=86e01f1479) | Oct 16, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [0dd7c3989e](https://linux-hardware.org/?probe=0dd7c3989e) | Oct 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [744091dcaa](https://linux-hardware.org/?probe=744091dcaa) | Oct 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7dce56f55d](https://linux-hardware.org/?probe=7dce56f55d) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [f15acdf9d4](https://linux-hardware.org/?probe=f15acdf9d4) | Oct 09, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [5e33c2b674](https://linux-hardware.org/?probe=5e33c2b674) | Oct 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [6fec6456bc](https://linux-hardware.org/?probe=6fec6456bc) | Oct 07, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fb954f84b4](https://linux-hardware.org/?probe=fb954f84b4) | Oct 07, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d56cf9868c](https://linux-hardware.org/?probe=d56cf9868c) | Oct 07, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [acf2f9d381](https://linux-hardware.org/?probe=acf2f9d381) | Sep 25, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [21407ce4a8](https://linux-hardware.org/?probe=21407ce4a8) | Sep 21, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [44afa82c4a](https://linux-hardware.org/?probe=44afa82c4a) | Sep 19, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0a91582802](https://linux-hardware.org/?probe=0a91582802) | Sep 14, 2022 |
| Intel         | D945GCNL AAD97184-106       | Desktop     | [a2bdc2d18c](https://linux-hardware.org/?probe=a2bdc2d18c) | Sep 11, 2022 |
| AZW           | GK mini                     | Mini pc     | [b2d573f8e2](https://linux-hardware.org/?probe=b2d573f8e2) | Sep 10, 2022 |
| AZW           | GK mini                     | Mini pc     | [58c74cb934](https://linux-hardware.org/?probe=58c74cb934) | Sep 09, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2267f01dee](https://linux-hardware.org/?probe=2267f01dee) | Aug 27, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [7bea18122c](https://linux-hardware.org/?probe=7bea18122c) | Aug 27, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [c001653a5a](https://linux-hardware.org/?probe=c001653a5a) | Aug 20, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [e6a9f975ae](https://linux-hardware.org/?probe=e6a9f975ae) | Aug 18, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [c1e007def0](https://linux-hardware.org/?probe=c1e007def0) | Aug 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [91a44f9b39](https://linux-hardware.org/?probe=91a44f9b39) | Aug 13, 2022 |
| Dell          | Latitude E6430              | Notebook    | [864ad41c22](https://linux-hardware.org/?probe=864ad41c22) | Aug 13, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ca185c2301](https://linux-hardware.org/?probe=ca185c2301) | Aug 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [49390f2f0e](https://linux-hardware.org/?probe=49390f2f0e) | Aug 06, 2022 |
| HP            | 1493                        | Desktop     | [2ac16ddc1f](https://linux-hardware.org/?probe=2ac16ddc1f) | Aug 03, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [e5b05f8e39](https://linux-hardware.org/?probe=e5b05f8e39) | Aug 02, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [1c92a49cd4](https://linux-hardware.org/?probe=1c92a49cd4) | Aug 01, 2022 |
| Lenovo        | ThinkPad T60 1953D9U        | Notebook    | [1c31cb6b44](https://linux-hardware.org/?probe=1c31cb6b44) | Jul 21, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [27bf18a32e](https://linux-hardware.org/?probe=27bf18a32e) | Jul 20, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [8d52662820](https://linux-hardware.org/?probe=8d52662820) | Jul 19, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [4414dd4c1b](https://linux-hardware.org/?probe=4414dd4c1b) | Jul 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b511d2883b](https://linux-hardware.org/?probe=b511d2883b) | Jul 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f0952d8c25](https://linux-hardware.org/?probe=f0952d8c25) | Jul 13, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [8c160ae192](https://linux-hardware.org/?probe=8c160ae192) | Jul 12, 2022 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [0ebf0eb484](https://linux-hardware.org/?probe=0ebf0eb484) | Jul 08, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [aa2ad87835](https://linux-hardware.org/?probe=aa2ad87835) | Jul 08, 2022 |
| Acer          | Aspire V3-471               | Notebook    | [75664ddf0f](https://linux-hardware.org/?probe=75664ddf0f) | Jul 07, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| MSI           | GL65 Leopard 10SEK          | Notebook    | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [01fbfc98f8](https://linux-hardware.org/?probe=01fbfc98f8) | Jun 27, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [fac01563a9](https://linux-hardware.org/?probe=fac01563a9) | Jun 24, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| Intel         | D102GGC2 AAD42789-204       | Desktop     | [3ed07edb6a](https://linux-hardware.org/?probe=3ed07edb6a) | Jun 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [67c7179045](https://linux-hardware.org/?probe=67c7179045) | Jun 15, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e24239a843](https://linux-hardware.org/?probe=e24239a843) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| Dell          | Latitude E7450              | Notebook    | [29219339b2](https://linux-hardware.org/?probe=29219339b2) | Jun 05, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [49c400d1f7](https://linux-hardware.org/?probe=49c400d1f7) | May 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c1db97e482](https://linux-hardware.org/?probe=c1db97e482) | May 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c274a43a82](https://linux-hardware.org/?probe=c274a43a82) | May 30, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [be0f84abb3](https://linux-hardware.org/?probe=be0f84abb3) | May 30, 2022 |
| ASUSTek       | X555UQ                      | Notebook    | [c266f3d070](https://linux-hardware.org/?probe=c266f3d070) | May 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2ce35a0cba](https://linux-hardware.org/?probe=2ce35a0cba) | May 30, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | Notebook    | [da2a67f904](https://linux-hardware.org/?probe=da2a67f904) | May 28, 2022 |
| Intel         | DP67BA AAG10219-300         | Desktop     | [005b9cdb8e](https://linux-hardware.org/?probe=005b9cdb8e) | May 26, 2022 |
| Acer          | TravelMate 5320             | Notebook    | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | Notebook    | [7f0fc0c72e](https://linux-hardware.org/?probe=7f0fc0c72e) | May 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [2ee4916960](https://linux-hardware.org/?probe=2ee4916960) | May 18, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [fcec5f1cdd](https://linux-hardware.org/?probe=fcec5f1cdd) | May 17, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [21f3f7368f](https://linux-hardware.org/?probe=21f3f7368f) | May 17, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [3bf7390ce3](https://linux-hardware.org/?probe=3bf7390ce3) | May 16, 2022 |
| HP            | 8056                        | Desktop     | [e9d15128a7](https://linux-hardware.org/?probe=e9d15128a7) | May 16, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [03581837bc](https://linux-hardware.org/?probe=03581837bc) | May 14, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e436a62479](https://linux-hardware.org/?probe=e436a62479) | May 13, 2022 |
| Dell          | 0773VG A02                  | Desktop     | [0743f4573d](https://linux-hardware.org/?probe=0743f4573d) | May 12, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [3c8e334d43](https://linux-hardware.org/?probe=3c8e334d43) | May 12, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [358cadc7df](https://linux-hardware.org/?probe=358cadc7df) | May 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [9b0f684d99](https://linux-hardware.org/?probe=9b0f684d99) | May 09, 2022 |
| Lenovo        | Legion 5 17ITH6H 82JM       | Notebook    | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| Lenovo        | ThinkPad T530 24296G9       | Notebook    | [934e13a24c](https://linux-hardware.org/?probe=934e13a24c) | May 08, 2022 |
| HP            | ZBook 15                    | Notebook    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| SZMZ          | X99 DUAL Z8                 | Desktop     | [f68946f3d4](https://linux-hardware.org/?probe=f68946f3d4) | May 06, 2022 |
| Compal        | QAQXX                       | Notebook    | [d3211e6bc6](https://linux-hardware.org/?probe=d3211e6bc6) | May 05, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d2eb5ae290](https://linux-hardware.org/?probe=d2eb5ae290) | May 05, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [7b488333bb](https://linux-hardware.org/?probe=7b488333bb) | May 05, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cbe76ee3d3](https://linux-hardware.org/?probe=cbe76ee3d3) | May 04, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [1a791b0fd5](https://linux-hardware.org/?probe=1a791b0fd5) | May 04, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [3846d07c7f](https://linux-hardware.org/?probe=3846d07c7f) | May 04, 2022 |
| HP            | ENVY dv6                    | Notebook    | [23ad3290c2](https://linux-hardware.org/?probe=23ad3290c2) | May 03, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [80f3ccadb9](https://linux-hardware.org/?probe=80f3ccadb9) | May 02, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U3S... | Notebook    | [74eec8c684](https://linux-hardware.org/?probe=74eec8c684) | May 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [05db30a69b](https://linux-hardware.org/?probe=05db30a69b) | Apr 30, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [ebdc8b1380](https://linux-hardware.org/?probe=ebdc8b1380) | Apr 30, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [865091bbc1](https://linux-hardware.org/?probe=865091bbc1) | Apr 30, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [5ee29c3982](https://linux-hardware.org/?probe=5ee29c3982) | Apr 30, 2022 |
| ASUSTek       | X556UR                      | Notebook    | [3f920954f7](https://linux-hardware.org/?probe=3f920954f7) | Apr 30, 2022 |
| MSI           | A88XM-E45 V2                | Desktop     | [a50ad068b1](https://linux-hardware.org/?probe=a50ad068b1) | Apr 30, 2022 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [0003f9342e](https://linux-hardware.org/?probe=0003f9342e) | Apr 30, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [7c9e2f4d8f](https://linux-hardware.org/?probe=7c9e2f4d8f) | Apr 30, 2022 |
| Foxconn       | H61MXE                      | Desktop     | [d8168e72e7](https://linux-hardware.org/?probe=d8168e72e7) | Apr 27, 2022 |
| HP            | Notebook                    | Notebook    | [94f0ce7610](https://linux-hardware.org/?probe=94f0ce7610) | Apr 26, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [2d5bae0eeb](https://linux-hardware.org/?probe=2d5bae0eeb) | Apr 24, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0e448efcb](https://linux-hardware.org/?probe=e0e448efcb) | Apr 24, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [ed62d97841](https://linux-hardware.org/?probe=ed62d97841) | Apr 18, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [a33d067e62](https://linux-hardware.org/?probe=a33d067e62) | Apr 18, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [89c92e2cf7](https://linux-hardware.org/?probe=89c92e2cf7) | Apr 15, 2022 |
| Dell          | Latitude 3410               | Notebook    | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [0e9e99acae](https://linux-hardware.org/?probe=0e9e99acae) | Apr 13, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [a00c0b503b](https://linux-hardware.org/?probe=a00c0b503b) | Apr 06, 2022 |
| ASUSTek       | A68HM-E                     | Desktop     | [af6b7df94c](https://linux-hardware.org/?probe=af6b7df94c) | Apr 06, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [9cad677222](https://linux-hardware.org/?probe=9cad677222) | Mar 24, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [9b99145008](https://linux-hardware.org/?probe=9b99145008) | Mar 21, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [53ca03e8ec](https://linux-hardware.org/?probe=53ca03e8ec) | Mar 17, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [80e5e3a26c](https://linux-hardware.org/?probe=80e5e3a26c) | Mar 15, 2022 |
| Intel         | DX79SR AAG57199-200         | Desktop     | [1ab5b833d9](https://linux-hardware.org/?probe=1ab5b833d9) | Mar 12, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [92c7141f37](https://linux-hardware.org/?probe=92c7141f37) | Mar 12, 2022 |
| HP            | 340 G2                      | Notebook    | [c4f663b37b](https://linux-hardware.org/?probe=c4f663b37b) | Mar 04, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [b8f02b07fb](https://linux-hardware.org/?probe=b8f02b07fb) | Feb 18, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [3269f565c4](https://linux-hardware.org/?probe=3269f565c4) | Feb 18, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [91e577540a](https://linux-hardware.org/?probe=91e577540a) | Feb 11, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [03f63a3789](https://linux-hardware.org/?probe=03f63a3789) | Feb 09, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [15dd0e4767](https://linux-hardware.org/?probe=15dd0e4767) | Feb 08, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Toshiba       | Satellite C645              | Notebook    | [d552c9b132](https://linux-hardware.org/?probe=d552c9b132) | Feb 04, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [50fae55964](https://linux-hardware.org/?probe=50fae55964) | Jan 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5f679efaa1](https://linux-hardware.org/?probe=5f679efaa1) | Jan 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b7cb93aff2](https://linux-hardware.org/?probe=b7cb93aff2) | Jan 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f36cdb65e7](https://linux-hardware.org/?probe=f36cdb65e7) | Jan 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f6a7e71141](https://linux-hardware.org/?probe=f6a7e71141) | Jan 18, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [1f065ea4dd](https://linux-hardware.org/?probe=1f065ea4dd) | Jan 12, 2022 |
| Sony          | VGN-FW56M                   | Notebook    | [9fb3fa0f32](https://linux-hardware.org/?probe=9fb3fa0f32) | Jan 09, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [eb23bd590c](https://linux-hardware.org/?probe=eb23bd590c) | Jan 07, 2022 |
| Toshiba       | Satellite E205              | Notebook    | [92431da366](https://linux-hardware.org/?probe=92431da366) | Dec 24, 2021 |
| Lenovo        | G400 20235                  | Notebook    | [c2bb5d0010](https://linux-hardware.org/?probe=c2bb5d0010) | Dec 18, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a3c85ddcb3](https://linux-hardware.org/?probe=a3c85ddcb3) | Dec 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [020b7460a1](https://linux-hardware.org/?probe=020b7460a1) | Dec 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fefa594281](https://linux-hardware.org/?probe=fefa594281) | Dec 10, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [3cd230924a](https://linux-hardware.org/?probe=3cd230924a) | Dec 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [54f954491a](https://linux-hardware.org/?probe=54f954491a) | Nov 21, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [9dccdb1f45](https://linux-hardware.org/?probe=9dccdb1f45) | Nov 17, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [180b98585e](https://linux-hardware.org/?probe=180b98585e) | Nov 11, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [e995b26637](https://linux-hardware.org/?probe=e995b26637) | Nov 11, 2021 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [83ce5b471d](https://linux-hardware.org/?probe=83ce5b471d) | Nov 10, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [140cf1defc](https://linux-hardware.org/?probe=140cf1defc) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [e085c7e42a](https://linux-hardware.org/?probe=e085c7e42a) | Nov 09, 2021 |
| ASRock        | B460M-HDV                   | Desktop     | [f343673932](https://linux-hardware.org/?probe=f343673932) | Nov 08, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [90fbcc38c3](https://linux-hardware.org/?probe=90fbcc38c3) | Nov 08, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [61db5bc9b5](https://linux-hardware.org/?probe=61db5bc9b5) | Nov 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [df2d173d7c](https://linux-hardware.org/?probe=df2d173d7c) | Nov 01, 2021 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [8948989999](https://linux-hardware.org/?probe=8948989999) | Oct 31, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f4d2f1104e](https://linux-hardware.org/?probe=f4d2f1104e) | Oct 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e071387ed6](https://linux-hardware.org/?probe=e071387ed6) | Oct 22, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [849c03d63c](https://linux-hardware.org/?probe=849c03d63c) | Oct 21, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [87d959803d](https://linux-hardware.org/?probe=87d959803d) | Oct 15, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [9343a7aac0](https://linux-hardware.org/?probe=9343a7aac0) | Oct 13, 2021 |
| MSI           | H170A GAMING PRO            | Desktop     | [2a068afc0c](https://linux-hardware.org/?probe=2a068afc0c) | Oct 11, 2021 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [57fb928b65](https://linux-hardware.org/?probe=57fb928b65) | Oct 03, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [8bb0307157](https://linux-hardware.org/?probe=8bb0307157) | Sep 25, 2021 |
| HP            | Notebook                    | Notebook    | [36fd24364d](https://linux-hardware.org/?probe=36fd24364d) | Sep 24, 2021 |
| ASUSTek       | A88XM-A                     | Desktop     | [72114a075d](https://linux-hardware.org/?probe=72114a075d) | Sep 24, 2021 |
| Dell          | 0773VG A02                  | Desktop     | [5b63f0fc0a](https://linux-hardware.org/?probe=5b63f0fc0a) | Sep 16, 2021 |
| Advance       | AN-5431                     | Notebook    | [d48465a943](https://linux-hardware.org/?probe=d48465a943) | Sep 14, 2021 |
| HP            | Notebook                    | Notebook    | [2a564798fd](https://linux-hardware.org/?probe=2a564798fd) | Sep 11, 2021 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [e5f7233230](https://linux-hardware.org/?probe=e5f7233230) | Sep 04, 2021 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [72a24d0b34](https://linux-hardware.org/?probe=72a24d0b34) | Sep 01, 2021 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [92fb750c2f](https://linux-hardware.org/?probe=92fb750c2f) | Sep 01, 2021 |
| Lenovo        | ThinkPad T440 20B7A08500    | Notebook    | [b7e859020c](https://linux-hardware.org/?probe=b7e859020c) | Aug 26, 2021 |
| HP            | 450                         | Notebook    | [9f5d03c478](https://linux-hardware.org/?probe=9f5d03c478) | Aug 19, 2021 |
| Intel         | DG33BU AAD79951-413         | Desktop     | [9824fedcc4](https://linux-hardware.org/?probe=9824fedcc4) | Aug 16, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [392df1ef2b](https://linux-hardware.org/?probe=392df1ef2b) | Aug 13, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [46cd16e708](https://linux-hardware.org/?probe=46cd16e708) | Aug 13, 2021 |
| ASUSTek       | X542UQ                      | Notebook    | [63d2276d55](https://linux-hardware.org/?probe=63d2276d55) | Aug 03, 2021 |
| Gigabyte      | B550M H                     | Desktop     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| Advance       | AN-5431                     | Notebook    | [06409d8637](https://linux-hardware.org/?probe=06409d8637) | Aug 01, 2021 |
| Lenovo        | ThinkPad T580 20LAS0XD00    | Notebook    | [36f1b3eb94](https://linux-hardware.org/?probe=36f1b3eb94) | Jul 31, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [5b80d3040f](https://linux-hardware.org/?probe=5b80d3040f) | Jul 25, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [771ef872d9](https://linux-hardware.org/?probe=771ef872d9) | Jul 25, 2021 |
| Dell          | Latitude E5540              | Notebook    | [44b8f3a781](https://linux-hardware.org/?probe=44b8f3a781) | Jul 23, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [da8382cb33](https://linux-hardware.org/?probe=da8382cb33) | Jul 15, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [146ce74ec9](https://linux-hardware.org/?probe=146ce74ec9) | Jul 15, 2021 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [6001052e23](https://linux-hardware.org/?probe=6001052e23) | Jul 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [3e69858907](https://linux-hardware.org/?probe=3e69858907) | Jul 09, 2021 |
| Lenovo        | ThinkPad L460 20FVA0G400    | Notebook    | [378021c178](https://linux-hardware.org/?probe=378021c178) | Jul 06, 2021 |
| ASUSTek       | ROG Strix G532LW_G532LWI    | Notebook    | [b36be47753](https://linux-hardware.org/?probe=b36be47753) | Jun 27, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [95fcf3868f](https://linux-hardware.org/?probe=95fcf3868f) | Jun 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [003f0d1c2a](https://linux-hardware.org/?probe=003f0d1c2a) | Jun 21, 2021 |
| ASUSTek       | ROG Strix G532LW_G532LWI    | Notebook    | [1344b72b26](https://linux-hardware.org/?probe=1344b72b26) | Jun 20, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cebf94c181](https://linux-hardware.org/?probe=cebf94c181) | Jun 15, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [6670e1c145](https://linux-hardware.org/?probe=6670e1c145) | Jun 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [af8045a7b3](https://linux-hardware.org/?probe=af8045a7b3) | May 31, 2021 |
| HP            | 8054                        | Desktop     | [b0662fd84b](https://linux-hardware.org/?probe=b0662fd84b) | May 30, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [89bed4ca0a](https://linux-hardware.org/?probe=89bed4ca0a) | May 28, 2021 |
| HP            | 8054                        | Desktop     | [37f65c4171](https://linux-hardware.org/?probe=37f65c4171) | May 27, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [ee9233be38](https://linux-hardware.org/?probe=ee9233be38) | May 26, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [6d64546949](https://linux-hardware.org/?probe=6d64546949) | May 23, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [1b52ac3979](https://linux-hardware.org/?probe=1b52ac3979) | May 23, 2021 |
| HP            | 2B2F MVB,A                  | All in one  | [093f49b44c](https://linux-hardware.org/?probe=093f49b44c) | May 20, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a1959c22e0](https://linux-hardware.org/?probe=a1959c22e0) | May 20, 2021 |
| HP            | 240 G7                      | Notebook    | [9fff9c48ab](https://linux-hardware.org/?probe=9fff9c48ab) | May 16, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [930993fd14](https://linux-hardware.org/?probe=930993fd14) | May 16, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [f7a3ab5c2f](https://linux-hardware.org/?probe=f7a3ab5c2f) | May 16, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [57b918a36e](https://linux-hardware.org/?probe=57b918a36e) | May 15, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [23a000c11b](https://linux-hardware.org/?probe=23a000c11b) | May 05, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [d50b1f77d7](https://linux-hardware.org/?probe=d50b1f77d7) | May 05, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [6eb605ae36](https://linux-hardware.org/?probe=6eb605ae36) | Apr 21, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [642a8e122e](https://linux-hardware.org/?probe=642a8e122e) | Apr 18, 2021 |
| Toshiba       | Satellite L35               | Notebook    | [1abffa2c4c](https://linux-hardware.org/?probe=1abffa2c4c) | Apr 16, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [4bd5425a6b](https://linux-hardware.org/?probe=4bd5425a6b) | Apr 11, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [59cb82d24c](https://linux-hardware.org/?probe=59cb82d24c) | Apr 09, 2021 |
| HP            | 14                          | Notebook    | [9d65301476](https://linux-hardware.org/?probe=9d65301476) | Apr 09, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [14e58f968d](https://linux-hardware.org/?probe=14e58f968d) | Apr 07, 2021 |
| MSI           | B75A-G43                    | Desktop     | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [b02d3fa1c0](https://linux-hardware.org/?probe=b02d3fa1c0) | Apr 04, 2021 |
| Lenovo        | ThinkCentre M91 7516AD1     | Desktop     | [91ae7f221c](https://linux-hardware.org/?probe=91ae7f221c) | Apr 01, 2021 |
| Toshiba       | Satellite C655D             | Notebook    | [1959880e8f](https://linux-hardware.org/?probe=1959880e8f) | Mar 28, 2021 |
| Dell          | Latitude E5470              | Notebook    | [6ade45ee37](https://linux-hardware.org/?probe=6ade45ee37) | Mar 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [860e86fde0](https://linux-hardware.org/?probe=860e86fde0) | Mar 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [4d1099b04c](https://linux-hardware.org/?probe=4d1099b04c) | Mar 18, 2021 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [529bb59872](https://linux-hardware.org/?probe=529bb59872) | Mar 12, 2021 |
| Toshiba       | Satellite A665              | Notebook    | [23143ad7ae](https://linux-hardware.org/?probe=23143ad7ae) | Mar 07, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [96dd155871](https://linux-hardware.org/?probe=96dd155871) | Mar 07, 2021 |
| Intel         | H61                         | Desktop     | [77b62ac54a](https://linux-hardware.org/?probe=77b62ac54a) | Mar 05, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [b2e0735680](https://linux-hardware.org/?probe=b2e0735680) | Feb 28, 2021 |
| MSI           | Prestige 14 A10SC           | Notebook    | [26f40cdcba](https://linux-hardware.org/?probe=26f40cdcba) | Feb 25, 2021 |
| HP            | Stream x360 Convertible ... | Convertible | [ccb97bb311](https://linux-hardware.org/?probe=ccb97bb311) | Feb 23, 2021 |
| HP            | ProBook 5330m               | Notebook    | [4a66a57a41](https://linux-hardware.org/?probe=4a66a57a41) | Feb 23, 2021 |
| Razer         | Blade                       | Notebook    | [58fcda1ac4](https://linux-hardware.org/?probe=58fcda1ac4) | Feb 18, 2021 |
| PCChips       | P49G                        | Desktop     | [a2f19ae622](https://linux-hardware.org/?probe=a2f19ae622) | Feb 17, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [05d5a888d4](https://linux-hardware.org/?probe=05d5a888d4) | Feb 16, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c4f6a52387](https://linux-hardware.org/?probe=c4f6a52387) | Feb 13, 2021 |
| Intel         | D945GTP AAC97834-305        | Desktop     | [fa876f7290](https://linux-hardware.org/?probe=fa876f7290) | Feb 10, 2021 |
| ASUSTek       | N56JN                       | Notebook    | [02008fdd48](https://linux-hardware.org/?probe=02008fdd48) | Jan 31, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [3c0bc82dde](https://linux-hardware.org/?probe=3c0bc82dde) | Jan 16, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [48d877b127](https://linux-hardware.org/?probe=48d877b127) | Jan 07, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7591424ea2](https://linux-hardware.org/?probe=7591424ea2) | Jan 06, 2021 |
| HP            | Pavilion dv7                | Notebook    | [d660b968a4](https://linux-hardware.org/?probe=d660b968a4) | Jan 06, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [fe678ae6f5](https://linux-hardware.org/?probe=fe678ae6f5) | Jan 04, 2021 |
| Intel         | DP965LT AAD41694-209        | Desktop     | [c577103201](https://linux-hardware.org/?probe=c577103201) | Jan 02, 2021 |
| Dell          | G5 5505                     | Notebook    | [156236cc47](https://linux-hardware.org/?probe=156236cc47) | Dec 30, 2020 |
| Dell          | Latitude E5470              | Notebook    | [f6a3bc1097](https://linux-hardware.org/?probe=f6a3bc1097) | Dec 28, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [033a1ff3cd](https://linux-hardware.org/?probe=033a1ff3cd) | Dec 07, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [35757b1c8c](https://linux-hardware.org/?probe=35757b1c8c) | Dec 06, 2020 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [228dc321d9](https://linux-hardware.org/?probe=228dc321d9) | Dec 05, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [f0c3c358a0](https://linux-hardware.org/?probe=f0c3c358a0) | Dec 03, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [5837b78f0c](https://linux-hardware.org/?probe=5837b78f0c) | Nov 26, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [776cb81132](https://linux-hardware.org/?probe=776cb81132) | Nov 25, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [e14774acd5](https://linux-hardware.org/?probe=e14774acd5) | Nov 25, 2020 |
| HP            | 14                          | Notebook    | [918fb071c2](https://linux-hardware.org/?probe=918fb071c2) | Nov 22, 2020 |
| Dell          | Latitude 3440               | Notebook    | [17db1f31f6](https://linux-hardware.org/?probe=17db1f31f6) | Nov 13, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [751f746aaf](https://linux-hardware.org/?probe=751f746aaf) | Nov 09, 2020 |
| Lenovo        | Larne CRB SDK0J40679 WIN... | All in one  | [9a0e5bd73b](https://linux-hardware.org/?probe=9a0e5bd73b) | Oct 31, 2020 |
| Lenovo        | Larne CRB SDK0J40679 WIN... | All in one  | [8d1e7af345](https://linux-hardware.org/?probe=8d1e7af345) | Oct 31, 2020 |
| Dell          | 0DR845                      | Desktop     | [80aa8797b0](https://linux-hardware.org/?probe=80aa8797b0) | Oct 29, 2020 |
| MSI           | B360M PRO-VH                | Desktop     | [d8eb2de621](https://linux-hardware.org/?probe=d8eb2de621) | Oct 21, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [943240cc2a](https://linux-hardware.org/?probe=943240cc2a) | Oct 09, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [07ac3c5495](https://linux-hardware.org/?probe=07ac3c5495) | Oct 07, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [123eb500e2](https://linux-hardware.org/?probe=123eb500e2) | Oct 06, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [735aea26c5](https://linux-hardware.org/?probe=735aea26c5) | Sep 28, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [8987176239](https://linux-hardware.org/?probe=8987176239) | Sep 28, 2020 |
| HP            | 240 G7                      | Notebook    | [2507cc1bc7](https://linux-hardware.org/?probe=2507cc1bc7) | Sep 28, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [c00c60e193](https://linux-hardware.org/?probe=c00c60e193) | Sep 26, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [f714eaf1b2](https://linux-hardware.org/?probe=f714eaf1b2) | Sep 26, 2020 |
| Lenovo        | ThinkPad T470 20HES0JQ00    | Notebook    | [4235f1fc42](https://linux-hardware.org/?probe=4235f1fc42) | Sep 20, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [60efe004ff](https://linux-hardware.org/?probe=60efe004ff) | Sep 19, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [123ba2dd21](https://linux-hardware.org/?probe=123ba2dd21) | Sep 15, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [e193207a8f](https://linux-hardware.org/?probe=e193207a8f) | Sep 14, 2020 |
| MSI           | H81M-E33                    | Desktop     | [313883253c](https://linux-hardware.org/?probe=313883253c) | Sep 07, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [d043bf1b42](https://linux-hardware.org/?probe=d043bf1b42) | Sep 06, 2020 |
| Lenovo        | ThinkPad T430 2349LRS       | Notebook    | [d886cd5c31](https://linux-hardware.org/?probe=d886cd5c31) | Sep 05, 2020 |
| Lenovo        | ThinkPad T430 2349LRS       | Notebook    | [38284d9848](https://linux-hardware.org/?probe=38284d9848) | Sep 05, 2020 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [fc06b19016](https://linux-hardware.org/?probe=fc06b19016) | Sep 05, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [395b3e9836](https://linux-hardware.org/?probe=395b3e9836) | Sep 05, 2020 |
| Lenovo        | ThinkPad T430s 23539KU      | Notebook    | [2f700d4f41](https://linux-hardware.org/?probe=2f700d4f41) | Sep 03, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [47c7bf1c93](https://linux-hardware.org/?probe=47c7bf1c93) | Aug 30, 2020 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [3ac15dbee9](https://linux-hardware.org/?probe=3ac15dbee9) | Aug 28, 2020 |
| Lenovo        | G475 20080                  | Notebook    | [c97ad59308](https://linux-hardware.org/?probe=c97ad59308) | Aug 26, 2020 |
| Acer          | Aspire A515-52G             | Notebook    | [86a890eb18](https://linux-hardware.org/?probe=86a890eb18) | Aug 23, 2020 |
| Acer          | Aspire A515-52G             | Notebook    | [5034bf6bc3](https://linux-hardware.org/?probe=5034bf6bc3) | Aug 23, 2020 |
| Toshiba       | Satellite C845              | Notebook    | [7e218cb089](https://linux-hardware.org/?probe=7e218cb089) | Aug 22, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [31a8ca3766](https://linux-hardware.org/?probe=31a8ca3766) | Aug 18, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2098b09526](https://linux-hardware.org/?probe=2098b09526) | Aug 17, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [39ccf30487](https://linux-hardware.org/?probe=39ccf30487) | Aug 17, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [26fe839699](https://linux-hardware.org/?probe=26fe839699) | Aug 14, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [55d2d92173](https://linux-hardware.org/?probe=55d2d92173) | Aug 14, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [2adefb78ad](https://linux-hardware.org/?probe=2adefb78ad) | Aug 13, 2020 |
| Lenovo        | ThinkPad P50 20EQA09900     | Notebook    | [4360f8c6a6](https://linux-hardware.org/?probe=4360f8c6a6) | Aug 12, 2020 |
| Lenovo        | ThinkPad P50 20EQA09900     | Notebook    | [76f4cf6487](https://linux-hardware.org/?probe=76f4cf6487) | Aug 12, 2020 |
| Toshiba       | Satellite L45-B             | Notebook    | [ce51a04f5d](https://linux-hardware.org/?probe=ce51a04f5d) | Aug 01, 2020 |
| Lenovo        | ThinkPad T60 1953D9U        | Notebook    | [45c01e0aca](https://linux-hardware.org/?probe=45c01e0aca) | Jul 30, 2020 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [02c231ca67](https://linux-hardware.org/?probe=02c231ca67) | Jul 27, 2020 |
| HP            | 245 G3                      | Notebook    | [044b206096](https://linux-hardware.org/?probe=044b206096) | Jul 26, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fda411a3d7](https://linux-hardware.org/?probe=fda411a3d7) | Jul 24, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [4e0fee8549](https://linux-hardware.org/?probe=4e0fee8549) | Jul 20, 2020 |
| Intel         | DG31PR AAD97573-305         | Desktop     | [e3bd0984ee](https://linux-hardware.org/?probe=e3bd0984ee) | Jul 17, 2020 |
| Intel         | H61M-DS2                    | Desktop     | [2e847ac1d0](https://linux-hardware.org/?probe=2e847ac1d0) | Jul 16, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [7fdfad1fc4](https://linux-hardware.org/?probe=7fdfad1fc4) | Jul 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f0ed82358a](https://linux-hardware.org/?probe=f0ed82358a) | Jul 05, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b0f11672bb](https://linux-hardware.org/?probe=b0f11672bb) | Jul 05, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [4716a84af9](https://linux-hardware.org/?probe=4716a84af9) | Jul 03, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [c9d75e29d3](https://linux-hardware.org/?probe=c9d75e29d3) | Jun 30, 2020 |
| HP            | 09E8h                       | Desktop     | [d9b1f1bf60](https://linux-hardware.org/?probe=d9b1f1bf60) | Jun 28, 2020 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [f073723231](https://linux-hardware.org/?probe=f073723231) | Jun 27, 2020 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [7f8abda42c](https://linux-hardware.org/?probe=7f8abda42c) | Jun 27, 2020 |
| Intel         | H61M-DS2                    | Desktop     | [aef4861ab1](https://linux-hardware.org/?probe=aef4861ab1) | Jun 25, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [2fb2b6ad63](https://linux-hardware.org/?probe=2fb2b6ad63) | Jun 22, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [844f7b115e](https://linux-hardware.org/?probe=844f7b115e) | Jun 21, 2020 |
| HP            | 3397                        | Desktop     | [3421ad000d](https://linux-hardware.org/?probe=3421ad000d) | Jun 21, 2020 |
| HP            | 09E8h                       | Desktop     | [14e6514858](https://linux-hardware.org/?probe=14e6514858) | Jun 20, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [3b021c1b62](https://linux-hardware.org/?probe=3b021c1b62) | Jun 17, 2020 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [821a7a7b85](https://linux-hardware.org/?probe=821a7a7b85) | Jun 17, 2020 |
| ASUSTek       | X540LA                      | Notebook    | [333139a886](https://linux-hardware.org/?probe=333139a886) | Jun 17, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| Dell          | 0DR845                      | Desktop     | [cb4b80e381](https://linux-hardware.org/?probe=cb4b80e381) | Jun 14, 2020 |
| Dell          | 0DR845                      | Desktop     | [107ec57e94](https://linux-hardware.org/?probe=107ec57e94) | Jun 13, 2020 |
| Toshiba       | Satellite L855              | Notebook    | [adbdc1e191](https://linux-hardware.org/?probe=adbdc1e191) | Jun 13, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [89182244dc](https://linux-hardware.org/?probe=89182244dc) | Jun 12, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [97237c08ac](https://linux-hardware.org/?probe=97237c08ac) | Jun 11, 2020 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [615d9bbafb](https://linux-hardware.org/?probe=615d9bbafb) | Jun 07, 2020 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [db6aa4b6fa](https://linux-hardware.org/?probe=db6aa4b6fa) | Jun 07, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [371c5ccd5a](https://linux-hardware.org/?probe=371c5ccd5a) | May 31, 2020 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b803424e29](https://linux-hardware.org/?probe=b803424e29) | May 31, 2020 |
| HP            | ENVY 15                     | Notebook    | [9075368552](https://linux-hardware.org/?probe=9075368552) | May 29, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [ea48f46d27](https://linux-hardware.org/?probe=ea48f46d27) | May 27, 2020 |
| Foxconn       | H61MXE/-S/-V/-K             | Desktop     | [3d5fc4df20](https://linux-hardware.org/?probe=3d5fc4df20) | May 27, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [fb33cd7cef](https://linux-hardware.org/?probe=fb33cd7cef) | May 26, 2020 |
| Biostar       | GF7025-M2                   | Desktop     | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [07829f089a](https://linux-hardware.org/?probe=07829f089a) | May 24, 2020 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4c93d3634b](https://linux-hardware.org/?probe=4c93d3634b) | May 24, 2020 |
| HP            | ENVY 15                     | Notebook    | [afcc7af453](https://linux-hardware.org/?probe=afcc7af453) | May 23, 2020 |
| Gigabyte      | G41MT-S2                    | Desktop     | [f8702707c6](https://linux-hardware.org/?probe=f8702707c6) | May 22, 2020 |
| Unknown       | Unknown                     | Notebook    | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Intel         | D945GCNL AAD97184-102       | Desktop     | [72691e43eb](https://linux-hardware.org/?probe=72691e43eb) | May 14, 2020 |
| Gigabyte      | B450 GAMING X               | Desktop     | [404ef9032e](https://linux-hardware.org/?probe=404ef9032e) | May 12, 2020 |
| Dell          | Precision M4600             | Notebook    | [7060267281](https://linux-hardware.org/?probe=7060267281) | May 08, 2020 |
| HP            | 0A58h                       | Desktop     | [a3a4679ef9](https://linux-hardware.org/?probe=a3a4679ef9) | May 05, 2020 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [c513103ac9](https://linux-hardware.org/?probe=c513103ac9) | May 05, 2020 |
| Intel         | DX58SO AAE29331-703         | Desktop     | [08c0779e95](https://linux-hardware.org/?probe=08c0779e95) | May 02, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [d5880c1076](https://linux-hardware.org/?probe=d5880c1076) | May 02, 2020 |
| HP            | 450                         | Notebook    | [22b90eb634](https://linux-hardware.org/?probe=22b90eb634) | May 02, 2020 |
| HP            | 450                         | Notebook    | [0da93b6fce](https://linux-hardware.org/?probe=0da93b6fce) | May 02, 2020 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [eb77b46e2f](https://linux-hardware.org/?probe=eb77b46e2f) | Apr 30, 2020 |
| Dell          | System XPS L502X            | Notebook    | [939683d725](https://linux-hardware.org/?probe=939683d725) | Apr 27, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [e2ab73d9cf](https://linux-hardware.org/?probe=e2ab73d9cf) | Apr 26, 2020 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [32546cbd9d](https://linux-hardware.org/?probe=32546cbd9d) | Apr 26, 2020 |
| Dell          | System XPS L502X            | Notebook    | [c893f3f105](https://linux-hardware.org/?probe=c893f3f105) | Apr 24, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [97261529e7](https://linux-hardware.org/?probe=97261529e7) | Apr 21, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [babdfebf40](https://linux-hardware.org/?probe=babdfebf40) | Apr 17, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [d88e072663](https://linux-hardware.org/?probe=d88e072663) | Apr 15, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [71673b2f86](https://linux-hardware.org/?probe=71673b2f86) | Apr 09, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [6277a6ec0b](https://linux-hardware.org/?probe=6277a6ec0b) | Apr 08, 2020 |
| HP            | 0A60h                       | Desktop     | [e929430fd0](https://linux-hardware.org/?probe=e929430fd0) | Apr 08, 2020 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [bbd3b573e1](https://linux-hardware.org/?probe=bbd3b573e1) | Apr 05, 2020 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [51c0fd8c5c](https://linux-hardware.org/?probe=51c0fd8c5c) | Apr 05, 2020 |
| Toshiba       | NB505                       | Notebook    | [934ebfe06b](https://linux-hardware.org/?probe=934ebfe06b) | Apr 05, 2020 |
| PCChips       | P49G                        | Desktop     | [57f11f5c76](https://linux-hardware.org/?probe=57f11f5c76) | Apr 04, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [b112c2d6c6](https://linux-hardware.org/?probe=b112c2d6c6) | Mar 30, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [7dee8ed61e](https://linux-hardware.org/?probe=7dee8ed61e) | Mar 26, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e274c73209](https://linux-hardware.org/?probe=e274c73209) | Mar 23, 2020 |
| Sony          | SVF15A17CLB                 | Notebook    | [6f9e42f276](https://linux-hardware.org/?probe=6f9e42f276) | Mar 22, 2020 |
| HP            | 3397                        | Desktop     | [71764f18dd](https://linux-hardware.org/?probe=71764f18dd) | Mar 21, 2020 |
| HP            | 09E8h                       | Desktop     | [57904c47e1](https://linux-hardware.org/?probe=57904c47e1) | Mar 21, 2020 |
| HP            | 09E8h                       | Desktop     | [4c44586ba9](https://linux-hardware.org/?probe=4c44586ba9) | Mar 21, 2020 |
| PCChips       | P49G                        | Desktop     | [1cedc0a4f7](https://linux-hardware.org/?probe=1cedc0a4f7) | Mar 17, 2020 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [88cf0450ac](https://linux-hardware.org/?probe=88cf0450ac) | Mar 15, 2020 |
| Gigabyte      | B450 GAMING X               | Desktop     | [145e6998fc](https://linux-hardware.org/?probe=145e6998fc) | Mar 06, 2020 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [baaf155c68](https://linux-hardware.org/?probe=baaf155c68) | Mar 04, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [651d7ac7be](https://linux-hardware.org/?probe=651d7ac7be) | Feb 28, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [5b33f9565a](https://linux-hardware.org/?probe=5b33f9565a) | Feb 28, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [e598212cee](https://linux-hardware.org/?probe=e598212cee) | Feb 28, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2eebfcd5e9](https://linux-hardware.org/?probe=2eebfcd5e9) | Feb 27, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1335c3693b](https://linux-hardware.org/?probe=1335c3693b) | Feb 27, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [9344a74aa9](https://linux-hardware.org/?probe=9344a74aa9) | Feb 26, 2020 |
| Gigabyte      | M68MT-S2                    | Desktop     | [6a5c6cf0dc](https://linux-hardware.org/?probe=6a5c6cf0dc) | Feb 23, 2020 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [8a4a2a6066](https://linux-hardware.org/?probe=8a4a2a6066) | Feb 21, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b253180703](https://linux-hardware.org/?probe=b253180703) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [ad43873fae](https://linux-hardware.org/?probe=ad43873fae) | Feb 19, 2020 |
| Intel         | CM8V5CB8N K53774-201        | Desktop     | [4ba8cd9ca2](https://linux-hardware.org/?probe=4ba8cd9ca2) | Feb 16, 2020 |
| Intel         | CM8V5CB8N K53774-201        | Desktop     | [19086b2ac2](https://linux-hardware.org/?probe=19086b2ac2) | Feb 16, 2020 |
| Toshiba       | QOSMIO X775                 | Notebook    | [6abcb623e3](https://linux-hardware.org/?probe=6abcb623e3) | Feb 02, 2020 |
| Toshiba       | QOSMIO X775                 | Notebook    | [a2cf60ec44](https://linux-hardware.org/?probe=a2cf60ec44) | Feb 02, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [7ae91dcf15](https://linux-hardware.org/?probe=7ae91dcf15) | Jan 21, 2020 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [12b760b696](https://linux-hardware.org/?probe=12b760b696) | Jan 20, 2020 |
| ASUSTek       | M5A97                       | Desktop     | [a381f0be23](https://linux-hardware.org/?probe=a381f0be23) | Jan 17, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5b67f6ed83](https://linux-hardware.org/?probe=5b67f6ed83) | Dec 26, 2019 |
| Acer          | Aspire ES1-572              | Notebook    | [8bc74bd7fb](https://linux-hardware.org/?probe=8bc74bd7fb) | Dec 06, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [c05b5b48de](https://linux-hardware.org/?probe=c05b5b48de) | Dec 05, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [3862b040a2](https://linux-hardware.org/?probe=3862b040a2) | Dec 04, 2019 |
| Unknown       | Unknown                     | Notebook    | [cd4af41624](https://linux-hardware.org/?probe=cd4af41624) | Nov 30, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [50ef5c54ef](https://linux-hardware.org/?probe=50ef5c54ef) | Nov 29, 2019 |
| HP            | Pavilion g4                 | Notebook    | [cb1f2e06e7](https://linux-hardware.org/?probe=cb1f2e06e7) | Nov 28, 2019 |
| Dell          | Latitude 5580               | Notebook    | [7abf5fbce7](https://linux-hardware.org/?probe=7abf5fbce7) | Nov 21, 2019 |
| Dell          | Latitude 5580               | Notebook    | [521a1d30b6](https://linux-hardware.org/?probe=521a1d30b6) | Nov 21, 2019 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [dfa431bef9](https://linux-hardware.org/?probe=dfa431bef9) | Nov 13, 2019 |
| Toshiba       | Satellite C55-B             | Notebook    | [ef97116a29](https://linux-hardware.org/?probe=ef97116a29) | Nov 12, 2019 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [d0612d575f](https://linux-hardware.org/?probe=d0612d575f) | Nov 04, 2019 |
| Foxconn       | A76GMV                      | Desktop     | [ddfa1ad143](https://linux-hardware.org/?probe=ddfa1ad143) | Oct 22, 2019 |
| Dell          | Inspiron 3443               | Notebook    | [daa04d519c](https://linux-hardware.org/?probe=daa04d519c) | Oct 15, 2019 |
| Sony          | VPCEC2JFX                   | Notebook    | [ad30a52539](https://linux-hardware.org/?probe=ad30a52539) | Oct 03, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [e486c2c05f](https://linux-hardware.org/?probe=e486c2c05f) | Sep 12, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b09160e7cf](https://linux-hardware.org/?probe=b09160e7cf) | Sep 10, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [333fbc5a3b](https://linux-hardware.org/?probe=333fbc5a3b) | Aug 16, 2019 |
| Sony          | VPCEC2JFX                   | Notebook    | [f28ba85f16](https://linux-hardware.org/?probe=f28ba85f16) | Aug 04, 2019 |
| Acer          | Aspire ES1-572              | Notebook    | [432212e4c9](https://linux-hardware.org/?probe=432212e4c9) | Jul 31, 2019 |
| Acer          | Aspire ES1-572              | Notebook    | [8783b0d26c](https://linux-hardware.org/?probe=8783b0d26c) | Jul 31, 2019 |
| HP            | ProBook 440 G4              | Notebook    | [b0ae12ca81](https://linux-hardware.org/?probe=b0ae12ca81) | Jun 27, 2019 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [048c1a4f90](https://linux-hardware.org/?probe=048c1a4f90) | Jun 25, 2019 |
| Gigabyte      | A55M-DS2                    | Desktop     | [9e2c603e49](https://linux-hardware.org/?probe=9e2c603e49) | Jun 23, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [07dd5b8424](https://linux-hardware.org/?probe=07dd5b8424) | Jun 14, 2019 |
| Toshiba       | Satellite P755              | Notebook    | [8eaca3c3df](https://linux-hardware.org/?probe=8eaca3c3df) | Jun 13, 2019 |
| HP            | ProBook 645 G4              | Notebook    | [f2f88aaa9d](https://linux-hardware.org/?probe=f2f88aaa9d) | May 24, 2019 |
| HP            | ProBook 645 G4              | Notebook    | [049bd45822](https://linux-hardware.org/?probe=049bd45822) | May 24, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [cdf8203e8f](https://linux-hardware.org/?probe=cdf8203e8f) | Apr 24, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [5ca60ce3ac](https://linux-hardware.org/?probe=5ca60ce3ac) | Apr 06, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [c7dd2b6e26](https://linux-hardware.org/?probe=c7dd2b6e26) | Mar 26, 2019 |
| Lenovo        | B50-80 80EW                 | Notebook    | [275d0c887d](https://linux-hardware.org/?probe=275d0c887d) | Dec 28, 2018 |
| Lenovo        | B50-80 80EW                 | Notebook    | [603e6d3da4](https://linux-hardware.org/?probe=603e6d3da4) | Dec 28, 2018 |
| AMI           | Cherry Trail CR             | Desktop     | [e248592999](https://linux-hardware.org/?probe=e248592999) | Nov 03, 2018 |
| HP            | 1000                        | Notebook    | [9bf9fc957a](https://linux-hardware.org/?probe=9bf9fc957a) | Sep 04, 2018 |
| MSI           | A68HM-E33 V2                | Desktop     | [765c79328e](https://linux-hardware.org/?probe=765c79328e) | Jun 26, 2018 |
| ECS           | MCP61M-M3                   | Desktop     | [a51a8c96df](https://linux-hardware.org/?probe=a51a8c96df) | Apr 08, 2018 |
| HP            | Stream x360 Convertible ... | Convertible | [be4128010b](https://linux-hardware.org/?probe=be4128010b) | Feb 12, 2018 |
| HP            | 1000                        | Notebook    | [684f6b1db8](https://linux-hardware.org/?probe=684f6b1db8) | Jan 30, 2018 |
| Sony          | VGN-FW170J                  | Notebook    | [2ac505bc7b](https://linux-hardware.org/?probe=2ac505bc7b) | Jan 04, 2018 |
| HP            | 1000                        | Notebook    | [0e00b75fea](https://linux-hardware.org/?probe=0e00b75fea) | Dec 19, 2017 |
| Sony          | VGN-FW170J                  | Notebook    | [d2b4cdb291](https://linux-hardware.org/?probe=d2b4cdb291) | Nov 21, 2017 |
| Acer          | Aspire S3                   | Notebook    | [db53fb01bd](https://linux-hardware.org/?probe=db53fb01bd) | May 26, 2017 |
| Acer          | Aspire S3                   | Notebook    | [a3cfad5de1](https://linux-hardware.org/?probe=a3cfad5de1) | May 26, 2017 |
| HP            | Stream x360 Convertible ... | Convertible | [e721d571fe](https://linux-hardware.org/?probe=e721d571fe) | May 15, 2017 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [4d498130d3](https://linux-hardware.org/?probe=4d498130d3) | Dec 24, 2016 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [58bc94c592](https://linux-hardware.org/?probe=58bc94c592) | Dec 24, 2016 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [7201ee94b8](https://linux-hardware.org/?probe=7201ee94b8) | Nov 07, 2016 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [4567d9bca4](https://linux-hardware.org/?probe=4567d9bca4) | Nov 02, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 57        | 15.83%  |
| Ubuntu 18.04                 | 22        | 6.11%   |
| OpenMandriva 4.3             | 19        | 5.28%   |
| Ubuntu 22.04                 | 17        | 4.72%   |
| OpenMandriva 4.2             | 12        | 3.33%   |
| Zorin 15                     | 10        | 2.78%   |
| Ubuntu 19.10                 | 9         | 2.5%    |
| Manjaro                      | 9         | 2.5%    |
| Debian 11                    | 8         | 2.22%   |
| KDE neon 20.04               | 6         | 1.67%   |
| Arch Rolling                 | 6         | 1.67%   |
| Arch                         | 6         | 1.67%   |
| Xubuntu 20.04                | 5         | 1.39%   |
| ROSA R9                      | 5         | 1.39%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 1.39%   |
| Linux Mint 20.3              | 5         | 1.39%   |
| Kubuntu 20.04                | 5         | 1.39%   |
| Debian 10                    | 5         | 1.39%   |
| Ubuntu 21.10                 | 4         | 1.11%   |
| Ubuntu 21.04                 | 4         | 1.11%   |
| Pop!_OS 21.10                | 4         | 1.11%   |
| Linux Mint 20.1              | 4         | 1.11%   |
| Linux Mint 19.3              | 4         | 1.11%   |
| Fedora 37                    | 4         | 1.11%   |
| CentOS 8                     | 4         | 1.11%   |
| Zorin 16                     | 3         | 0.83%   |
| Ubuntu 19.04                 | 3         | 0.83%   |
| ROSA R11.1                   | 3         | 0.83%   |
| ROSA R10                     | 3         | 0.83%   |
| Pop!_OS 20.10                | 3         | 0.83%   |
| OpenMandriva 4.90            | 3         | 0.83%   |
| OpenMandriva 23.01           | 3         | 0.83%   |
| Manjaro 21.2.6               | 3         | 0.83%   |
| Manjaro 20.1                 | 3         | 0.83%   |
| Linux Mint 21.1              | 3         | 0.83%   |
| Fedora 32                    | 3         | 0.83%   |
| Elementary 5.1.7             | 3         | 0.83%   |
| Ubuntu MATE 18.04            | 2         | 0.56%   |
| ROSA R8                      | 2         | 0.56%   |
| ROSA R11                     | 2         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 111       | 31.81%  |
| OpenMandriva  | 39        | 11.17%  |
| Linux Mint    | 25        | 7.16%   |
| Manjaro       | 17        | 4.87%   |
| Debian        | 16        | 4.58%   |
| ROSA          | 15        | 4.3%    |
| Fedora        | 15        | 4.3%    |
| Zorin         | 13        | 3.72%   |
| Arch          | 13        | 3.72%   |
| Pop!_OS       | 12        | 3.44%   |
| Ubuntu MATE   | 7         | 2.01%   |
| openSUSE      | 7         | 2.01%   |
| KDE neon      | 7         | 2.01%   |
| Xubuntu       | 6         | 1.72%   |
| Kubuntu       | 5         | 1.43%   |
| Endless       | 5         | 1.43%   |
| Lubuntu       | 4         | 1.15%   |
| Elementary    | 4         | 1.15%   |
| CentOS        | 4         | 1.15%   |
| Linux Lite    | 3         | 0.86%   |
| Ubuntu Unity  | 2         | 0.57%   |
| Peppermint    | 2         | 0.57%   |
| Kali          | 2         | 0.57%   |
| ArcoLinux     | 2         | 0.57%   |
| Void Linux    | 1         | 0.29%   |
| Ubuntu Budgie | 1         | 0.29%   |
| SteamOS       | 1         | 0.29%   |
| Solus         | 1         | 0.29%   |
| Q4OS          | 1         | 0.29%   |
| Parrot        | 1         | 0.29%   |
| MX            | 1         | 0.29%   |
| Manjaro-ARM   | 1         | 0.29%   |
| LMDE          | 1         | 0.29%   |
| Laxer OS      | 1         | 0.29%   |
| Feren OS      | 1         | 0.29%   |
| Clear Linux   | 1         | 0.29%   |
| Artix         | 1         | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 18        | 4.56%   |
| 5.10.14-desktop-1omv4002        | 10        | 2.53%   |
| 5.3.0-40-generic                | 8         | 2.03%   |
| 5.4.0-66-generic                | 5         | 1.27%   |
| 5.4.0-28-generic                | 5         | 1.27%   |
| 5.13.0-40-generic               | 5         | 1.27%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 5         | 1.27%   |
| 5.4.0-70-generic                | 4         | 1.01%   |
| 5.4.0-58-generic                | 4         | 1.01%   |
| 5.4.0-52-generic                | 4         | 1.01%   |
| 5.4.0-42-generic                | 4         | 1.01%   |
| 5.4.0-37-generic                | 4         | 1.01%   |
| 5.4.0-31-generic                | 4         | 1.01%   |
| 5.4.0-26-generic                | 4         | 1.01%   |
| 5.15.0-52-generic               | 4         | 1.01%   |
| 5.11.0-40-generic               | 4         | 1.01%   |
| 5.10.0-13-amd64                 | 4         | 1.01%   |
| 6.1.1-desktop-1omv2290          | 3         | 0.76%   |
| 5.4.0-73-generic                | 3         | 0.76%   |
| 5.4.0-40-generic                | 3         | 0.76%   |
| 5.4.0-39-generic                | 3         | 0.76%   |
| 5.4.0-33-generic                | 3         | 0.76%   |
| 5.3.0-46-generic                | 3         | 0.76%   |
| 5.3.0-42-generic                | 3         | 0.76%   |
| 5.3.0-26-generic                | 3         | 0.76%   |
| 5.18.12-desktop-3omv4090        | 3         | 0.76%   |
| 5.17.5-arch1-1                  | 3         | 0.76%   |
| 5.15.0-57-generic               | 3         | 0.76%   |
| 5.15.0-48-generic               | 3         | 0.76%   |
| 5.15.0-25-generic               | 3         | 0.76%   |
| 5.13.0-51-generic               | 3         | 0.76%   |
| 5.13.0-30-generic               | 3         | 0.76%   |
| 5.11.0-27-generic               | 3         | 0.76%   |
| 5.11.0-25-generic               | 3         | 0.76%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3         | 0.76%   |
| 4.18.0-15-generic               | 3         | 0.76%   |
| 6.0.10-300.fc37.x86_64          | 2         | 0.51%   |
| 5.9.11-3-MANJARO                | 2         | 0.51%   |
| 5.8.0-63-generic                | 2         | 0.51%   |
| 5.8.0-48-generic                | 2         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 69        | 18.55%  |
| 5.15.0  | 30        | 8.06%   |
| 5.3.0   | 23        | 6.18%   |
| 5.11.0  | 20        | 5.38%   |
| 5.13.0  | 19        | 5.11%   |
| 4.15.0  | 19        | 5.11%   |
| 5.16.7  | 18        | 4.84%   |
| 5.8.0   | 13        | 3.49%   |
| 4.18.0  | 12        | 3.23%   |
| 5.10.14 | 10        | 2.69%   |
| 5.10.0  | 10        | 2.69%   |
| 5.0.0   | 8         | 2.15%   |
| 4.9.20  | 5         | 1.34%   |
| 6.1.1   | 4         | 1.08%   |
| 5.17.5  | 4         | 1.08%   |
| 4.9.60  | 4         | 1.08%   |
| 6.0.0   | 3         | 0.81%   |
| 5.19.0  | 3         | 0.81%   |
| 5.18.12 | 3         | 0.81%   |
| 5.17.1  | 3         | 0.81%   |
| 6.0.15  | 2         | 0.54%   |
| 6.0.10  | 2         | 0.54%   |
| 5.9.11  | 2         | 0.54%   |
| 5.4.83  | 2         | 0.54%   |
| 5.3.18  | 2         | 0.54%   |
| 5.19.5  | 2         | 0.54%   |
| 5.16.19 | 2         | 0.54%   |
| 5.16.0  | 2         | 0.54%   |
| 5.15.49 | 2         | 0.54%   |
| 5.12.10 | 2         | 0.54%   |
| 5.11.12 | 2         | 0.54%   |
| 5.10.74 | 2         | 0.54%   |
| 4.19.0  | 2         | 0.54%   |
| 6.1.8   | 1         | 0.27%   |
| 6.0.8   | 1         | 0.27%   |
| 6.0.7   | 1         | 0.27%   |
| 6.0.6   | 1         | 0.27%   |
| 6.0.5   | 1         | 0.27%   |
| 6.0.2   | 1         | 0.27%   |
| 6.0.11  | 1         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 75        | 20.44%  |
| 5.15    | 42        | 11.44%  |
| 5.10    | 27        | 7.36%   |
| 5.3     | 25        | 6.81%   |
| 5.16    | 24        | 6.54%   |
| 5.11    | 24        | 6.54%   |
| 5.13    | 20        | 5.45%   |
| 4.15    | 19        | 5.18%   |
| 5.8     | 17        | 4.63%   |
| 6.0     | 12        | 3.27%   |
| 4.18    | 12        | 3.27%   |
| 5.17    | 10        | 2.72%   |
| 5.0     | 8         | 2.18%   |
| 4.9     | 8         | 2.18%   |
| 5.19    | 7         | 1.91%   |
| 6.1     | 5         | 1.36%   |
| 5.6     | 5         | 1.36%   |
| 5.18    | 5         | 1.36%   |
| 5.7     | 4         | 1.09%   |
| 5.12    | 4         | 1.09%   |
| 5.9     | 3         | 0.82%   |
| 5.14    | 3         | 0.82%   |
| 4.19    | 2         | 0.54%   |
| 4.1     | 2         | 0.54%   |
| 5.1     | 1         | 0.27%   |
| 4.8     | 1         | 0.27%   |
| 4.4     | 1         | 0.27%   |
| 4.16    | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 315       | 94.59%  |
| i686    | 16        | 4.8%    |
| aarch64 | 2         | 0.6%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 153       | 44.22%  |
| KDE5            | 64        | 18.5%   |
| XFCE            | 30        | 8.67%   |
| Unknown         | 25        | 7.23%   |
| X-Cinnamon      | 20        | 5.78%   |
| MATE            | 13        | 3.76%   |
| KDE4            | 9         | 2.6%    |
| KDE             | 8         | 2.31%   |
| Pantheon        | 4         | 1.16%   |
| LXQt            | 4         | 1.16%   |
| LXDE            | 4         | 1.16%   |
| i3              | 3         | 0.87%   |
| Budgie          | 3         | 0.87%   |
| Unity           | 2         | 0.58%   |
| GNOME Flashback | 2         | 0.58%   |
| spectrwm        | 1         | 0.29%   |
| awesome         | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 272       | 78.84%  |
| Wayland | 50        | 14.49%  |
| Unknown | 22        | 6.38%   |
| Tty     | 1         | 0.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 165       | 47.55%  |
| SDDM    | 57        | 16.43%  |
| GDM     | 47        | 13.54%  |
| LightDM | 31        | 8.93%   |
| GDM3    | 31        | 8.93%   |
| KDM     | 9         | 2.59%   |
| TDM     | 6         | 1.73%   |
| XDM     | 1         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_PE   | 174       | 50.88%  |
| en_US   | 84        | 24.56%  |
| es_ES   | 30        | 8.77%   |
| Unknown | 28        | 8.19%   |
| es_MX   | 5         | 1.46%   |
| en_GB   | 4         | 1.17%   |
| C       | 4         | 1.17%   |
| it_IT   | 2         | 0.58%   |
| fr_FR   | 2         | 0.58%   |
| en_CA   | 2         | 0.58%   |
| ca_ES   | 2         | 0.58%   |
| es_US   | 1         | 0.29%   |
| es_CO   | 1         | 0.29%   |
| en_NZ   | 1         | 0.29%   |
| de_DE   | 1         | 0.29%   |
| Default | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 176       | 52.07%  |
| EFI  | 162       | 47.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 260       | 76.02%  |
| Overlay | 37        | 10.82%  |
| Btrfs   | 17        | 4.97%   |
| Unknown | 15        | 4.39%   |
| Xfs     | 10        | 2.92%   |
| Ext3    | 3         | 0.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 194       | 56.89%  |
| GPT     | 110       | 32.26%  |
| MBR     | 37        | 10.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 289       | 84.5%   |
| Yes       | 53        | 15.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 199       | 58.7%   |
| Yes       | 140       | 41.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 66        | 19.88%  |
| Lenovo                  | 61        | 18.37%  |
| ASUSTek Computer        | 40        | 12.05%  |
| Gigabyte Technology     | 31        | 9.34%   |
| Dell                    | 26        | 7.83%   |
| Intel                   | 23        | 6.93%   |
| MSI                     | 17        | 5.12%   |
| Toshiba                 | 14        | 4.22%   |
| Acer                    | 14        | 4.22%   |
| Foxconn                 | 6         | 1.81%   |
| Sony                    | 4         | 1.2%    |
| ASRock                  | 4         | 1.2%    |
| HUAWEI                  | 3         | 0.9%    |
| Unknown                 | 3         | 0.9%    |
| Raspberry Pi Foundation | 2         | 0.6%    |
| ECS                     | 2         | 0.6%    |
| Chuwi                   | 2         | 0.6%    |
| Advance                 | 2         | 0.6%    |
| SZMZ                    | 1         | 0.3%    |
| Samsung Electronics     | 1         | 0.3%    |
| Razer                   | 1         | 0.3%    |
| PCChips                 | 1         | 0.3%    |
| Microsoft               | 1         | 0.3%    |
| efirstview              | 1         | 0.3%    |
| Deltron                 | 1         | 0.3%    |
| Compal                  | 1         | 0.3%    |
| Biostar                 | 1         | 0.3%    |
| AZW                     | 1         | 0.3%    |
| Apple                   | 1         | 0.3%    |
| AMI                     | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo V330-15IKB 81AX                   | 4         | 1.2%    |
| HP Pavilion Laptop 15-cw1xxx             | 4         | 1.2%    |
| Gigabyte 970A-DS3P                       | 4         | 1.2%    |
| MSI MS-7721                              | 3         | 0.9%    |
| Lenovo V310-15ISK 80SY                   | 3         | 0.9%    |
| Unknown                                  | 3         | 0.9%    |
| Lenovo IdeaPad S540-14API 81NH           | 2         | 0.6%    |
| Lenovo IdeaPad S145-15IWL 81MV           | 2         | 0.6%    |
| Lenovo IdeaPad 330S-14IKB 81F4           | 2         | 0.6%    |
| Lenovo IdeaPad 3 14ADA05 81W0            | 2         | 0.6%    |
| Intel DH55PJ AAE93812-303                | 2         | 0.6%    |
| HP ProBook 645 G4                        | 2         | 0.6%    |
| HP Laptop 15-ef1xxx                      | 2         | 0.6%    |
| HP 450                                   | 2         | 0.6%    |
| HP 14                                    | 2         | 0.6%    |
| Gigabyte Z77X-UD5H                       | 2         | 0.6%    |
| Gigabyte B75M-D3H                        | 2         | 0.6%    |
| Gigabyte A520M H                         | 2         | 0.6%    |
| Foxconn 500B Microtower                  | 2         | 0.6%    |
| Dell XPS 13 9360                         | 2         | 0.6%    |
| Dell OptiPlex 7010                       | 2         | 0.6%    |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA   | 2         | 0.6%    |
| ASUS VivoBook 15_ASUS Laptop X507UBR     | 2         | 0.6%    |
| ASUS TUF Gaming B550M-PLUS               | 2         | 0.6%    |
| ASUS PRIME X570-P                        | 2         | 0.6%    |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV | 2         | 0.6%    |
| ASUS All Series                          | 2         | 0.6%    |
| Toshiba Satellite P755                   | 1         | 0.3%    |
| Toshiba Satellite P300                   | 1         | 0.3%    |
| Toshiba Satellite L855                   | 1         | 0.3%    |
| Toshiba Satellite L45-B                  | 1         | 0.3%    |
| Toshiba Satellite L35                    | 1         | 0.3%    |
| Toshiba Satellite E205                   | 1         | 0.3%    |
| Toshiba Satellite C845                   | 1         | 0.3%    |
| Toshiba Satellite C655D                  | 1         | 0.3%    |
| Toshiba Satellite C645                   | 1         | 0.3%    |
| Toshiba Satellite C55-B                  | 1         | 0.3%    |
| Toshiba Satellite C45-A                  | 1         | 0.3%    |
| Toshiba Satellite A665                   | 1         | 0.3%    |
| Toshiba QOSMIO X775                      | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 17        | 5.12%   |
| HP Pavilion        | 17        | 5.12%   |
| Lenovo ThinkPad    | 14        | 4.22%   |
| Toshiba Satellite  | 12        | 3.61%   |
| Acer Aspire        | 12        | 3.61%   |
| ASUS VivoBook      | 9         | 2.71%   |
| HP ProBook         | 8         | 2.41%   |
| HP Compaq          | 8         | 2.41%   |
| Dell Latitude      | 8         | 2.41%   |
| ASUS PRIME         | 7         | 2.11%   |
| HP Laptop          | 6         | 1.81%   |
| Dell OptiPlex      | 6         | 1.81%   |
| Dell Inspiron      | 6         | 1.81%   |
| Lenovo V330-15IKB  | 4         | 1.2%    |
| Lenovo ThinkCentre | 4         | 1.2%    |
| Lenovo Legion      | 4         | 1.2%    |
| Gigabyte 970A-DS3P | 4         | 1.2%    |
| MSI MS-7721        | 3         | 0.9%    |
| Lenovo V310-15ISK  | 3         | 0.9%    |
| HP ENVY            | 3         | 0.9%    |
| ASUS TUF           | 3         | 0.9%    |
| ASUS ASUS          | 3         | 0.9%    |
| Unknown            | 3         | 0.9%    |
| RPi Raspberry      | 2         | 0.6%    |
| Lenovo Yoga        | 2         | 0.6%    |
| Intel DH61WW       | 2         | 0.6%    |
| Intel DH55PJ       | 2         | 0.6%    |
| Intel DG31PR       | 2         | 0.6%    |
| Intel D945GCNL     | 2         | 0.6%    |
| HP ZBook           | 2         | 0.6%    |
| HP Stream          | 2         | 0.6%    |
| HP EliteDesk       | 2         | 0.6%    |
| HP 450             | 2         | 0.6%    |
| HP 255             | 2         | 0.6%    |
| HP 250             | 2         | 0.6%    |
| HP 240             | 2         | 0.6%    |
| HP 14              | 2         | 0.6%    |
| Gigabyte Z77X-UD5H | 2         | 0.6%    |
| Gigabyte B75M-D3H  | 2         | 0.6%    |
| Gigabyte A520M     | 2         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 43        | 12.95%  |
| 2019    | 33        | 9.94%   |
| 2012    | 33        | 9.94%   |
| 2018    | 29        | 8.73%   |
| 2016    | 24        | 7.23%   |
| 2017    | 23        | 6.93%   |
| 2011    | 23        | 6.93%   |
| 2014    | 22        | 6.63%   |
| 2013    | 22        | 6.63%   |
| 2010    | 17        | 5.12%   |
| 2021    | 15        | 4.52%   |
| 2015    | 14        | 4.22%   |
| 2008    | 10        | 3.01%   |
| 2007    | 10        | 3.01%   |
| 2009    | 7         | 2.11%   |
| 2006    | 3         | 0.9%    |
| Unknown | 2         | 0.6%    |
| 2022    | 1         | 0.3%    |
| 2004    | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 193       | 58.13%  |
| Desktop        | 124       | 37.35%  |
| Convertible    | 5         | 1.51%   |
| All in one     | 3         | 0.9%    |
| System on chip | 2         | 0.6%    |
| Tablet         | 2         | 0.6%    |
| Mini pc        | 2         | 0.6%    |
| Server         | 1         | 0.3%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 311       | 93.39%  |
| Enabled  | 22        | 6.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 332       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 86        | 25.15%  |
| 8.01-16.0   | 82        | 23.98%  |
| 3.01-4.0    | 73        | 21.35%  |
| 16.01-24.0  | 54        | 15.79%  |
| 1.01-2.0    | 14        | 4.09%   |
| 32.01-64.0  | 13        | 3.8%    |
| 2.01-3.0    | 7         | 2.05%   |
| 24.01-32.0  | 6         | 1.75%   |
| 64.01-256.0 | 4         | 1.17%   |
| 0.51-1.0    | 3         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 130       | 35.23%  |
| 2.01-3.0   | 104       | 28.18%  |
| 4.01-8.0   | 49        | 13.28%  |
| 3.01-4.0   | 40        | 10.84%  |
| 0.51-1.0   | 32        | 8.67%   |
| 8.01-16.0  | 12        | 3.25%   |
| 16.01-24.0 | 1         | 0.27%   |
| 0.01-0.5   | 1         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 218       | 64.31%  |
| 2      | 91        | 26.84%  |
| 3      | 18        | 5.31%   |
| 4      | 9         | 2.65%   |
| 9      | 1         | 0.29%   |
| 5      | 1         | 0.29%   |
| 0      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 197       | 59.34%  |
| Yes       | 135       | 40.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 297       | 88.92%  |
| No        | 37        | 11.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 243       | 72.11%  |
| No        | 94        | 27.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 58.51%  |
| No        | 139       | 41.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Peru    | 332       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lima                  | 228       | 66.47%  |
| Arequipa              | 28        | 8.16%   |
| Trujillo              | 22        | 6.41%   |
| Tacna                 | 6         | 1.75%   |
| Piura                 | 6         | 1.75%   |
| Huancayo              | 6         | 1.75%   |
| Cusco                 | 6         | 1.75%   |
| Chiclayo              | 5         | 1.46%   |
| Moquegua              | 4         | 1.17%   |
| Ica                   | 3         | 0.87%   |
| Villa                 | 2         | 0.58%   |
| Junin                 | 2         | 0.58%   |
| Distrito de Lima      | 2         | 0.58%   |
| Callao                | 2         | 0.58%   |
| Barranco              | 2         | 0.58%   |
| Abancay               | 2         | 0.58%   |
| Sullana               | 1         | 0.29%   |
| Santiago de Surco     | 1         | 0.29%   |
| San Vicente de Canete | 1         | 0.29%   |
| San Isidro            | 1         | 0.29%   |
| San Borja             | 1         | 0.29%   |
| Punta Colorada        | 1         | 0.29%   |
| Puno                  | 1         | 0.29%   |
| Pucallpa              | 1         | 0.29%   |
| Pisco                 | 1         | 0.29%   |
| Oxapampa              | 1         | 0.29%   |
| La Victoria           | 1         | 0.29%   |
| La Libertad           | 1         | 0.29%   |
| Juliaca               | 1         | 0.29%   |
| Iquitos               | 1         | 0.29%   |
| Cajamarca             | 1         | 0.29%   |
| Bellavista            | 1         | 0.29%   |
| Ayacucho              | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 96        | 144    | 21.82%  |
| WDC                            | 82        | 116    | 18.64%  |
| Toshiba                        | 54        | 64     | 12.27%  |
| Kingston                       | 48        | 60     | 10.91%  |
| Samsung Electronics            | 36        | 48     | 8.18%   |
| SanDisk                        | 15        | 19     | 3.41%   |
| Crucial                        | 13        | 18     | 2.95%   |
| Unknown                        | 9         | 15     | 2.05%   |
| Intel                          | 7         | 8      | 1.59%   |
| Hitachi                        | 7         | 11     | 1.59%   |
| Hewlett-Packard                | 7         | 8      | 1.59%   |
| SK hynix                       | 6         | 10     | 1.36%   |
| Micron Technology              | 5         | 5      | 1.14%   |
| LITEON                         | 4         | 4      | 0.91%   |
| KIOXIA                         | 4         | 5      | 0.91%   |
| HGST                           | 4         | 4      | 0.91%   |
| A-DATA Technology              | 4         | 4      | 0.91%   |
| Silicon Motion                 | 3         | 3      | 0.68%   |
| PNY                            | 3         | 3      | 0.68%   |
| Micron/Crucial Technology      | 3         | 3      | 0.68%   |
| TO Exter                       | 2         | 4      | 0.45%   |
| Team                           | 2         | 2      | 0.45%   |
| Gigabyte Technology            | 2         | 2      | 0.45%   |
| China                          | 2         | 2      | 0.45%   |
| Unknown                        | 2         | 2      | 0.45%   |
| WD MediaMax                    | 1         | 1      | 0.23%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.23%   |
| UMIS                           | 1         | 1      | 0.23%   |
| SSSTC                          | 1         | 1      | 0.23%   |
| Solid State Storage Technology | 1         | 1      | 0.23%   |
| Phison Electronics             | 1         | 1      | 0.23%   |
| Phison                         | 1         | 1      | 0.23%   |
| NGFF                           | 1         | 1      | 0.23%   |
| Netac                          | 1         | 1      | 0.23%   |
| Mushkin                        | 1         | 2      | 0.23%   |
| Maxone                         | 1         | 2      | 0.23%   |
| KingSpec                       | 1         | 1      | 0.23%   |
| KESU                           | 1         | 1      | 0.23%   |
| ITHOO                          | 1         | 1      | 0.23%   |
| GLOWAY                         | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 19        | 3.9%    |
| Seagate ST500DM002-1BD142 500GB      | 14        | 2.87%   |
| Kingston SA400S37240G 240GB SSD      | 14        | 2.87%   |
| Toshiba MQ04ABF100 1TB               | 10        | 2.05%   |
| Toshiba MQ01ABD100 1TB               | 10        | 2.05%   |
| Kingston SA400S37480G 480GB SSD      | 9         | 1.85%   |
| Seagate ST1000DM010-2EP102 1TB       | 8         | 1.64%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 7         | 1.44%   |
| Kingston SA400S37120G 120GB SSD      | 7         | 1.44%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.03%   |
| Seagate ST3500418AS 500GB            | 5         | 1.03%   |
| HP SSD S700 500GB                    | 5         | 1.03%   |
| WDC WD10SPZX-24Z10 1TB               | 4         | 0.82%   |
| WDC WD10JPCX-24UE4T0 1TB             | 4         | 0.82%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 0.82%   |
| Toshiba DT01ACA100 1TB               | 4         | 0.82%   |
| Seagate ST3500413AS 500GB            | 4         | 0.82%   |
| Seagate ST2000DM001-1ER164 2TB       | 4         | 0.82%   |
| Intel SSDPEKNU512GZ 512GB            | 4         | 0.82%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 0.62%   |
| Seagate ST9500325AS 500GB            | 3         | 0.62%   |
| Seagate ST3500312CS 500GB            | 3         | 0.62%   |
| Seagate ST2000DM006-2DM164 2TB       | 3         | 0.62%   |
| Seagate ST2000DL003-9VT166 2TB       | 3         | 0.62%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.62%   |
| Seagate ST1000DM003-9YN162 1TB       | 3         | 0.62%   |
| Seagate ST1000DM003-1ER162 1TB       | 3         | 0.62%   |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 0.62%   |
| Kingston SNVS250G 250GB              | 3         | 0.62%   |
| Kingston NVMe SSD Drive 500GB        | 3         | 0.62%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.41%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 2         | 0.41%   |
| WDC WD80EFAX-68KNBN0 8TB             | 2         | 0.41%   |
| WDC WD3200BPVT-22ZEST0 320GB         | 2         | 0.41%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.41%   |
| WDC WD10EZEX-08M2NA0 1TB             | 2         | 0.41%   |
| WDC WD10EZEX-00WN4A0 1TB             | 2         | 0.41%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 94        | 137    | 40.87%  |
| WDC                 | 57        | 75     | 24.78%  |
| Toshiba             | 52        | 62     | 22.61%  |
| Samsung Electronics | 12        | 16     | 5.22%   |
| Hitachi             | 7         | 11     | 3.04%   |
| HGST                | 4         | 4      | 1.74%   |
| KESU                | 1         | 1      | 0.43%   |
| Fujitsu             | 1         | 1      | 0.43%   |
| Apple               | 1         | 1      | 0.43%   |
| ACASIS              | 1         | 1      | 0.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 38        | 43     | 30.89%  |
| WDC                 | 24        | 31     | 19.51%  |
| Crucial             | 10        | 13     | 8.13%   |
| Samsung Electronics | 7         | 7      | 5.69%   |
| Hewlett-Packard     | 7         | 7      | 5.69%   |
| SanDisk             | 6         | 8      | 4.88%   |
| LITEON              | 4         | 4      | 3.25%   |
| A-DATA Technology   | 4         | 4      | 3.25%   |
| Seagate             | 3         | 7      | 2.44%   |
| PNY                 | 3         | 3      | 2.44%   |
| TO Exter            | 2         | 4      | 1.63%   |
| Team                | 2         | 2      | 1.63%   |
| China               | 2         | 2      | 1.63%   |
| Toshiba             | 1         | 1      | 0.81%   |
| SSSTC               | 1         | 1      | 0.81%   |
| SK hynix            | 1         | 4      | 0.81%   |
| NGFF                | 1         | 1      | 0.81%   |
| Netac               | 1         | 1      | 0.81%   |
| Maxone              | 1         | 2      | 0.81%   |
| KingSpec            | 1         | 1      | 0.81%   |
| Intel               | 1         | 1      | 0.81%   |
| GLOWAY              | 1         | 1      | 0.81%   |
| Gigabyte Technology | 1         | 1      | 0.81%   |
| Dogfish             | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 210       | 309    | 50.6%   |
| SSD     | 111       | 150    | 26.75%  |
| NVMe    | 81        | 109    | 19.52%  |
| MMC     | 9         | 13     | 2.17%   |
| Unknown | 4         | 6      | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 271       | 452    | 73.24%  |
| NVMe | 81        | 109    | 21.89%  |
| SAS  | 9         | 13     | 2.43%   |
| MMC  | 9         | 13     | 2.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 180       | 273    | 55.38%  |
| 0.51-1.0   | 123       | 150    | 37.85%  |
| 1.01-2.0   | 15        | 24     | 4.62%   |
| 3.01-4.0   | 3         | 5      | 0.92%   |
| 4.01-10.0  | 3         | 6      | 0.92%   |
| 2.01-3.0   | 1         | 1      | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 83        | 23.51%  |
| 251-500        | 82        | 23.23%  |
| 501-1000       | 67        | 18.98%  |
| 51-100         | 27        | 7.65%   |
| 21-50          | 23        | 6.52%   |
| 1-20           | 23        | 6.52%   |
| 1001-2000      | 20        | 5.67%   |
| 2001-3000      | 12        | 3.4%    |
| More than 3000 | 10        | 2.83%   |
| Unknown        | 6         | 1.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 138       | 38.44%  |
| 21-50          | 74        | 20.61%  |
| 101-250        | 39        | 10.86%  |
| 51-100         | 35        | 9.75%   |
| 251-500        | 33        | 9.19%   |
| 501-1000       | 17        | 4.74%   |
| 1001-2000      | 10        | 2.79%   |
| Unknown        | 6         | 1.67%   |
| More than 3000 | 5         | 1.39%   |
| 2001-3000      | 2         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB    | 3         | 3      | 6.98%   |
| WDC WD10JPCX-24UE4T0 1TB          | 2         | 2      | 4.65%   |
| Seagate ST500DM002-1BD142 500GB   | 2         | 2      | 4.65%   |
| Seagate ST3500418AS 500GB         | 2         | 2      | 4.65%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1         | 1      | 2.33%   |
| WDC WDS100T2G0A-00JH30 1TB SSD    | 1         | 1      | 2.33%   |
| WDC WD800BD-00MRA1 80GB           | 1         | 1      | 2.33%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1         | 1      | 2.33%   |
| WDC WD3200AAJS-56M0A0 320GB       | 1         | 1      | 2.33%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1         | 1      | 2.33%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 2.33%   |
| Toshiba MQ04ABF100 1TB            | 1         | 1      | 2.33%   |
| Toshiba MQ01ABF050 500GB          | 1         | 1      | 2.33%   |
| Toshiba MK5065GSXN 500GB          | 1         | 1      | 2.33%   |
| Toshiba MK4058GSX 400GB           | 1         | 1      | 2.33%   |
| Toshiba MK2035GSS 200GB           | 1         | 1      | 2.33%   |
| Toshiba HDWJ110 1TB               | 1         | 1      | 2.33%   |
| SSSTC CVB-8D128-HP 128GB          | 1         | 1      | 2.33%   |
| Seagate ST980811AS 80GB           | 1         | 1      | 2.33%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 2.33%   |
| Seagate ST9250315AS 250GB         | 1         | 1      | 2.33%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 2.33%   |
| Seagate ST500DM002-9YN14C 500GB   | 1         | 1      | 2.33%   |
| Seagate ST3320820SCE 320GB        | 1         | 1      | 2.33%   |
| Seagate ST3250820AS 250GB         | 1         | 1      | 2.33%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 2.33%   |
| Seagate ST1000LM014-1EJ164 1TB    | 1         | 1      | 2.33%   |
| Seagate ST1000DM003-1CH162 1TB    | 1         | 1      | 2.33%   |
| Samsung Electronics SP1644N 160GB | 1         | 1      | 2.33%   |
| Samsung Electronics HD161HJ 160GB | 1         | 2      | 2.33%   |
| Kingston SA400S37480G 480GB SSD   | 1         | 1      | 2.33%   |
| Hitachi HTS725050A7E630 500GB     | 1         | 1      | 2.33%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 2.33%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 3      | 2.33%   |
| Hitachi HTS545032B9A302 320GB     | 1         | 1      | 2.33%   |
| Hitachi HTS545032B9A300 320GB     | 1         | 1      | 2.33%   |
| HGST HTS721010A9E630 1TB          | 1         | 1      | 2.33%   |
| A-DATA Technology SP550 240GB SSD | 1         | 1      | 2.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 17     | 40.48%  |
| WDC                 | 9         | 9      | 21.43%  |
| Toshiba             | 5         | 6      | 11.9%   |
| Hitachi             | 5         | 7      | 11.9%   |
| Samsung Electronics | 2         | 3      | 4.76%   |
| SSSTC               | 1         | 1      | 2.38%   |
| Kingston            | 1         | 1      | 2.38%   |
| HGST                | 1         | 1      | 2.38%   |
| A-DATA Technology   | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 17     | 45.95%  |
| WDC                 | 7         | 7      | 18.92%  |
| Toshiba             | 5         | 6      | 13.51%  |
| Hitachi             | 5         | 7      | 13.51%  |
| Samsung Electronics | 2         | 3      | 5.41%   |
| HGST                | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 41     | 86.84%  |
| SSD  | 5         | 5      | 13.16%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK3252GSX 320GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 202       | 350    | 55.8%   |
| Works    | 122       | 189    | 33.7%   |
| Malfunc  | 37        | 46     | 10.22%  |
| Failed   | 1         | 2      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 222       | 56.35%  |
| AMD                              | 77        | 19.54%  |
| SanDisk                          | 17        | 4.31%   |
| Samsung Electronics              | 17        | 4.31%   |
| Kingston Technology Company      | 12        | 3.05%   |
| Micron/Crucial Technology        | 6         | 1.52%   |
| Marvell Technology Group         | 6         | 1.52%   |
| SK hynix                         | 5         | 1.27%   |
| Silicon Motion                   | 5         | 1.27%   |
| Micron Technology                | 5         | 1.27%   |
| Nvidia                           | 4         | 1.02%   |
| KIOXIA                           | 4         | 1.02%   |
| JMicron Technology               | 3         | 0.76%   |
| Phison Electronics               | 2         | 0.51%   |
| Union Memory (Shenzhen)          | 1         | 0.25%   |
| Toshiba America Info Systems     | 1         | 0.25%   |
| Solid State Storage Technology   | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| LSI Logic / Symbios Logic        | 1         | 0.25%   |
| INNOGRIT                         | 1         | 0.25%   |
| Hewlett-Packard                  | 1         | 0.25%   |
| Broadcom / LSI                   | 1         | 0.25%   |
| Biwin Storage Technology         | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 54        | 11.84%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 29        | 6.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 17        | 3.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 16        | 3.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 12        | 2.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 2.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 10        | 2.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 2.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8         | 1.75%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 8         | 1.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8         | 1.75%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8         | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 1.54%   |
| Kingston Company Company Non-Volatile memory controller                                 | 6         | 1.32%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6         | 1.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5         | 1.1%    |
| SanDisk Non-Volatile memory controller                                                  | 5         | 1.1%    |
| Samsung NVMe SSD Controller 980                                                         | 5         | 1.1%    |
| Micron Non-Volatile memory controller                                                   | 5         | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 5         | 1.1%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 0.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4         | 0.88%   |
| Micron/Crucial NVMe Controller                                                          | 4         | 0.88%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 4         | 0.88%   |
| Intel Non-Volatile memory controller                                                    | 4         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4         | 0.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 0.88%   |
| SK hynix BC511                                                                          | 3         | 0.66%   |
| Nvidia MCP61 SATA Controller                                                            | 3         | 0.66%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 244       | 60.25%  |
| NVMe | 81        | 20%     |
| IDE  | 49        | 12.1%   |
| RAID | 28        | 6.91%   |
| SAS  | 2         | 0.49%   |
| SCSI | 1         | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 240       | 72.29%  |
| AMD    | 90        | 27.11%  |
| ARM    | 2         | 0.6%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 3%      |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 6         | 1.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.8%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 1.5%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 1.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.2%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 1.2%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 1.2%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 3         | 0.9%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.9%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.9%    |
| Intel Core i5-6500 CPU @ 3.20GHz              | 3         | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.9%    |
| Intel Core i5-3330 CPU @ 3.00GHz              | 3         | 0.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.9%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 0.9%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.9%    |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 0.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.6%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.6%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.6%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.6%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.6%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.6%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.6%    |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.6%    |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 0.6%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 0.6%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.6%    |
| Intel Core i3-3220 CPU @ 3.30GHz              | 2         | 0.6%    |
| Intel Core i3-3120M CPU @ 2.50GHz             | 2         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 74        | 22.29%  |
| Intel Core i5           | 70        | 21.08%  |
| Intel Core i3           | 33        | 9.94%   |
| AMD Ryzen 5             | 20        | 6.02%   |
| AMD Ryzen 7             | 18        | 5.42%   |
| Other                   | 13        | 3.92%   |
| Intel Core 2 Duo        | 10        | 3.01%   |
| Intel Celeron           | 10        | 3.01%   |
| Intel Pentium           | 7         | 2.11%   |
| AMD Ryzen 3             | 7         | 2.11%   |
| Intel Atom              | 6         | 1.81%   |
| AMD FX                  | 6         | 1.81%   |
| Intel Xeon              | 5         | 1.51%   |
| Intel Pentium Dual      | 5         | 1.51%   |
| AMD A8                  | 5         | 1.51%   |
| AMD Ryzen 9             | 4         | 1.2%    |
| AMD E1                  | 3         | 0.9%    |
| AMD Athlon              | 3         | 0.9%    |
| AMD A6                  | 3         | 0.9%    |
| AMD A10                 | 3         | 0.9%    |
| Intel Pentium Dual-Core | 2         | 0.6%    |
| Intel Pentium 4         | 2         | 0.6%    |
| Intel Core 2 Quad       | 2         | 0.6%    |
| Intel Core 2            | 2         | 0.6%    |
| AMD Sempron             | 2         | 0.6%    |
| AMD Ryzen 7 PRO         | 2         | 0.6%    |
| AMD Phenom II X4        | 2         | 0.6%    |
| AMD A4                  | 2         | 0.6%    |
| Intel Pentium D         | 1         | 0.3%    |
| Intel Genuine           | 1         | 0.3%    |
| Intel Celeron M         | 1         | 0.3%    |
| AMD Phenom II X3        | 1         | 0.3%    |
| AMD E                   | 1         | 0.3%    |
| AMD C-50                | 1         | 0.3%    |
| AMD Athlon X4           | 1         | 0.3%    |
| AMD Athlon II X3        | 1         | 0.3%    |
| AMD Athlon II X2        | 1         | 0.3%    |
| AMD Athlon 64 X2        | 1         | 0.3%    |
| AMD A12                 | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 136       | 40.96%  |
| 4       | 128       | 38.55%  |
| 6       | 22        | 6.63%   |
| 8       | 21        | 6.33%   |
| 1       | 13        | 3.92%   |
| 3       | 4         | 1.2%    |
| 16      | 2         | 0.6%    |
| 12      | 2         | 0.6%    |
| Unknown | 2         | 0.6%    |
| 20      | 1         | 0.3%    |
| 10      | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 331       | 99.7%   |
| 2      | 1         | 0.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 236       | 71.08%  |
| 1       | 94        | 28.31%  |
| Unknown | 2         | 0.6%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 321       | 95.54%  |
| 64-bit         | 6         | 1.79%   |
| Unknown        | 6         | 1.79%   |
| 32-bit         | 3         | 0.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 16.13%  |
| 0x306a9    | 25        | 7.33%   |
| 0x206a7    | 22        | 6.45%   |
| 0x306c3    | 13        | 3.81%   |
| 0x806ec    | 12        | 3.52%   |
| 0x806ea    | 11        | 3.23%   |
| 0x406e3    | 10        | 2.93%   |
| 0x40651    | 10        | 2.93%   |
| 0x806e9    | 9         | 2.64%   |
| 0x08108109 | 9         | 2.64%   |
| 0x1067a    | 8         | 2.35%   |
| 0x506e3    | 7         | 2.05%   |
| 0x306d4    | 7         | 2.05%   |
| 0x08701021 | 7         | 2.05%   |
| 0x906ea    | 6         | 1.76%   |
| 0x6fd      | 6         | 1.76%   |
| 0x20655    | 6         | 1.76%   |
| 0x08108102 | 6         | 1.76%   |
| 0x0a50000c | 5         | 1.47%   |
| 0x906e9    | 4         | 1.17%   |
| 0x806c1    | 4         | 1.17%   |
| 0x706e5    | 4         | 1.17%   |
| 0x406c4    | 4         | 1.17%   |
| 0x07030105 | 4         | 1.17%   |
| 0x06003106 | 4         | 1.17%   |
| 0x06000852 | 4         | 1.17%   |
| 0x010000c8 | 4         | 1.17%   |
| 0xa0652    | 3         | 0.88%   |
| 0x806eb    | 3         | 0.88%   |
| 0x6fb      | 3         | 0.88%   |
| 0x30678    | 3         | 0.88%   |
| 0x10676    | 3         | 0.88%   |
| 0x0810100b | 3         | 0.88%   |
| 0x06001119 | 3         | 0.88%   |
| 0xf64      | 2         | 0.59%   |
| 0xa0655    | 2         | 0.59%   |
| 0x706a8    | 2         | 0.59%   |
| 0x20652    | 2         | 0.59%   |
| 0x10661    | 2         | 0.59%   |
| 0x08701013 | 2         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 60        | 18.07%  |
| IvyBridge        | 29        | 8.73%   |
| SandyBridge      | 25        | 7.53%   |
| Haswell          | 24        | 7.23%   |
| Zen+             | 20        | 6.02%   |
| Zen 2            | 18        | 5.42%   |
| Skylake          | 18        | 5.42%   |
| Core             | 13        | 3.92%   |
| Penryn           | 12        | 3.61%   |
| Westmere         | 10        | 3.01%   |
| Piledriver       | 10        | 3.01%   |
| Zen              | 8         | 2.41%   |
| Silvermont       | 8         | 2.41%   |
| K10              | 8         | 2.41%   |
| Broadwell        | 8         | 2.41%   |
| IceLake          | 7         | 2.11%   |
| CometLake        | 7         | 2.11%   |
| Zen 3            | 6         | 1.81%   |
| Steamroller      | 5         | 1.51%   |
| Puma             | 5         | 1.51%   |
| Unknown          | 5         | 1.51%   |
| TigerLake        | 4         | 1.2%    |
| NetBurst         | 3         | 0.9%    |
| Goldmont plus    | 3         | 0.9%    |
| Excavator        | 3         | 0.9%    |
| P6               | 2         | 0.6%    |
| Nehalem          | 2         | 0.6%    |
| Bonnell          | 2         | 0.6%    |
| Bobcat           | 2         | 0.6%    |
| K8 Hammer        | 1         | 0.3%    |
| K10 Llano        | 1         | 0.3%    |
| Jaguar           | 1         | 0.3%    |
| Bulldozer        | 1         | 0.3%    |
| Alderlake Hybrid | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 197       | 49.37%  |
| AMD                              | 107       | 26.82%  |
| Nvidia                           | 93        | 23.31%  |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| Matrox Electronics Systems       | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 5.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 4.13%   |
| Intel UHD Graphics 620                                                                   | 15        | 3.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 3.4%    |
| Intel HD Graphics 620                                                                    | 11        | 2.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 2.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 2.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.43%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 2.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.7%    |
| Intel HD Graphics 5500                                                                   | 7         | 1.7%    |
| AMD Renoir                                                                               | 7         | 1.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 1.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 1.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.46%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.46%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 1.46%   |
| Intel HD Graphics 530                                                                    | 5         | 1.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.21%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 0.97%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 0.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.73%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.73%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.73%   |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 0.73%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 0.73%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 0.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.73%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.73%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 131       | 39.34%  |
| 1 x AMD        | 76        | 22.82%  |
| 1 x Nvidia     | 47        | 14.11%  |
| Intel + Nvidia | 42        | 12.61%  |
| Intel + AMD    | 19        | 5.71%   |
| 2 x AMD        | 8         | 2.4%    |
| AMD + Nvidia   | 4         | 1.2%    |
| Other          | 2         | 0.6%    |
| 2 x Intel      | 2         | 0.6%    |
| 1 x SiS        | 1         | 0.3%    |
| 1 x Matrox     | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 282       | 83.68%  |
| Proprietary | 46        | 13.65%  |
| Unknown     | 9         | 2.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 172       | 50.29%  |
| 1.01-2.0   | 63        | 18.42%  |
| 0.01-0.5   | 39        | 11.4%   |
| 0.51-1.0   | 27        | 7.89%   |
| 3.01-4.0   | 21        | 6.14%   |
| 5.01-6.0   | 10        | 2.92%   |
| 7.01-8.0   | 8         | 2.34%   |
| 8.01-16.0  | 2         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 60        | 17.05%  |
| Chimei Innolux       | 47        | 13.35%  |
| BOE                  | 43        | 12.22%  |
| AU Optronics         | 37        | 10.51%  |
| Goldstar             | 35        | 9.94%   |
| LG Display           | 25        | 7.1%    |
| Hewlett-Packard      | 14        | 3.98%   |
| AOC                  | 14        | 3.98%   |
| ViewSonic            | 7         | 1.99%   |
| Lenovo               | 7         | 1.99%   |
| Dell                 | 7         | 1.99%   |
| Sony                 | 5         | 1.42%   |
| Unknown              | 4         | 1.14%   |
| PANDA                | 4         | 1.14%   |
| Sharp                | 3         | 0.85%   |
| JRY                  | 3         | 0.85%   |
| BenQ                 | 3         | 0.85%   |
| ASUSTek Computer     | 3         | 0.85%   |
| Panasonic            | 2         | 0.57%   |
| LG Electronics       | 2         | 0.57%   |
| Lenovo Group Limited | 2         | 0.57%   |
| HannStar             | 2         | 0.57%   |
| Unknown              | 2         | 0.57%   |
| Viotek               | 1         | 0.28%   |
| Unknown (XXX)        | 1         | 0.28%   |
| TMX                  | 1         | 0.28%   |
| NEW                  | 1         | 0.28%   |
| Mi                   | 1         | 0.28%   |
| LGD                  | 1         | 0.28%   |
| LG Philips           | 1         | 0.28%   |
| InnoLux Display      | 1         | 0.28%   |
| InfoVision           | 1         | 0.28%   |
| Hyundai ImageQuest   | 1         | 0.28%   |
| Huion                | 1         | 0.28%   |
| Hitachi              | 1         | 0.28%   |
| Gigabyte Technology  | 1         | 0.28%   |
| EXP                  | 1         | 0.28%   |
| Eizo                 | 1         | 0.28%   |
| DZX                  | 1         | 0.28%   |
| DMT                  | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 11        | 3.07%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 7         | 1.96%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5         | 1.4%    |
| Samsung Electronics SA300/SA350 SAM078D 1600x900 443x249mm 20.0-inch   | 4         | 1.12%   |
| JRY 236 FHD 165Hz JRY2380 1920x1080 522x294mm 23.6-inch                | 3         | 0.84%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 3         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch        | 3         | 0.84%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch        | 3         | 0.84%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                   | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 3         | 0.84%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch          | 2         | 0.56%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch   | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch   | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SAM04FD 1280x720                       | 2         | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2         | 0.56%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.56%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch           | 2         | 0.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 0.56%   |
| Hewlett-Packard LA2306 HWP294B 1920x1080 509x286mm 23.0-inch           | 2         | 0.56%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch           | 2         | 0.56%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                   | 2         | 0.56%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 2         | 0.56%   |
| Goldstar E1951 GSM4BFD 1366x768 410x230mm 18.5-inch                    | 2         | 0.56%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                    | 2         | 0.56%   |
| Dell 3008WFP DEL4036 2560x1600 641x400mm 29.7-inch                     | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch        | 2         | 0.56%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 2         | 0.56%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                   | 2         | 0.56%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                   | 2         | 0.56%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                   | 2         | 0.56%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                  | 2         | 0.56%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                   | 2         | 0.56%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                   | 2         | 0.56%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                   | 2         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 127       | 37.24%  |
| 1920x1080 (FHD)   | 121       | 35.48%  |
| 1600x900 (HD+)    | 21        | 6.16%   |
| 1360x768          | 13        | 3.81%   |
| 3840x2160 (4K)    | 10        | 2.93%   |
| 1440x900 (WXGA+)  | 8         | 2.35%   |
| 2560x1440 (QHD)   | 5         | 1.47%   |
| 1024x768 (XGA)    | 5         | 1.47%   |
| 1280x800 (WXGA)   | 4         | 1.17%   |
| 1280x1024 (SXGA)  | 4         | 1.17%   |
| Unknown           | 4         | 1.17%   |
| 3840x1080         | 3         | 0.88%   |
| 3200x1800 (QHD+)  | 2         | 0.59%   |
| 2560x1600         | 2         | 0.59%   |
| 1920x1200 (WUXGA) | 2         | 0.59%   |
| 1024x600          | 2         | 0.59%   |
| 640x480           | 1         | 0.29%   |
| 3440x1440         | 1         | 0.29%   |
| 3200x2000         | 1         | 0.29%   |
| 2736x1824         | 1         | 0.29%   |
| 2560x1080         | 1         | 0.29%   |
| 2520x1680         | 1         | 0.29%   |
| 2160x1440         | 1         | 0.29%   |
| 1280x720 (HD)     | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 113       | 32.29%  |
| 13      | 40        | 11.43%  |
| 21      | 34        | 9.71%   |
| 14      | 28        | 8%      |
| 23      | 26        | 7.43%   |
| 18      | 15        | 4.29%   |
| Unknown | 13        | 3.71%   |
| 20      | 12        | 3.43%   |
| 17      | 11        | 3.14%   |
| 27      | 10        | 2.86%   |
| 19      | 8         | 2.29%   |
| 24      | 6         | 1.71%   |
| 31      | 5         | 1.43%   |
| 48      | 4         | 1.14%   |
| 11      | 4         | 1.14%   |
| 32      | 3         | 0.86%   |
| 12      | 3         | 0.86%   |
| 84      | 2         | 0.57%   |
| 72      | 2         | 0.57%   |
| 30      | 2         | 0.57%   |
| 10      | 2         | 0.57%   |
| 60      | 1         | 0.29%   |
| 54      | 1         | 0.29%   |
| 46      | 1         | 0.29%   |
| 43      | 1         | 0.29%   |
| 39      | 1         | 0.29%   |
| 34      | 1         | 0.29%   |
| 16      | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 174       | 50.29%  |
| 401-500     | 66        | 19.08%  |
| 501-600     | 41        | 11.85%  |
| 201-300     | 17        | 4.91%   |
| Unknown     | 13        | 3.76%   |
| 351-400     | 11        | 3.18%   |
| 601-700     | 7         | 2.02%   |
| 1001-1500   | 7         | 2.02%   |
| 701-800     | 4         | 1.16%   |
| 1501-2000   | 4         | 1.16%   |
| 801-900     | 1         | 0.29%   |
| 901-1000    | 1         | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 266       | 84.44%  |
| 16/10   | 19        | 6.03%   |
| Unknown | 13        | 4.13%   |
| 4/3     | 7         | 2.22%   |
| 5/4     | 6         | 1.9%    |
| 3/2     | 3         | 0.95%   |
| 21/9    | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 113       | 32.56%  |
| 81-90          | 61        | 17.58%  |
| 201-250        | 52        | 14.99%  |
| 151-200        | 31        | 8.93%   |
| 141-150        | 18        | 5.19%   |
| Unknown        | 13        | 3.75%   |
| 351-500        | 11        | 3.17%   |
| More than 1000 | 10        | 2.88%   |
| 301-350        | 10        | 2.88%   |
| 71-80          | 8         | 2.31%   |
| 51-60          | 4         | 1.15%   |
| 121-130        | 4         | 1.15%   |
| 131-140        | 3         | 0.86%   |
| 501-1000       | 3         | 0.86%   |
| 41-50          | 2         | 0.58%   |
| 61-70          | 1         | 0.29%   |
| 251-300        | 1         | 0.29%   |
| 111-120        | 1         | 0.29%   |
| 91-100         | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 154       | 45.29%  |
| 51-100        | 89        | 26.18%  |
| 121-160       | 59        | 17.35%  |
| 1-50          | 15        | 4.41%   |
| Unknown       | 13        | 3.82%   |
| 161-240       | 6         | 1.76%   |
| More than 240 | 4         | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 283       | 83.24%  |
| 2     | 46        | 13.53%  |
| 0     | 9         | 2.65%   |
| 3     | 2         | 0.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 212       | 43.53%  |
| Intel                            | 118       | 24.23%  |
| Qualcomm Atheros                 | 71        | 14.58%  |
| Broadcom                         | 15        | 3.08%   |
| TP-Link                          | 14        | 2.87%   |
| Ralink Technology                | 6         | 1.23%   |
| Ralink                           | 5         | 1.03%   |
| Marvell Technology Group         | 5         | 1.03%   |
| Qualcomm Atheros Communications  | 4         | 0.82%   |
| Nvidia                           | 4         | 0.82%   |
| Broadcom Limited                 | 4         | 0.82%   |
| ASIX Electronics                 | 4         | 0.82%   |
| Xiaomi                           | 3         | 0.62%   |
| MediaTek                         | 3         | 0.62%   |
| ICS Advent                       | 3         | 0.62%   |
| Samsung Electronics              | 2         | 0.41%   |
| Motorola PCS                     | 2         | 0.41%   |
| Microsoft                        | 2         | 0.41%   |
| Huawei Technologies              | 2         | 0.41%   |
| D-Link System                    | 2         | 0.41%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.21%   |
| T & A Mobile Phones              | 1         | 0.21%   |
| Silicon Integrated Systems [SiS] | 1         | 0.21%   |
| Lenovo                           | 1         | 0.21%   |
| D-Link                           | 1         | 0.21%   |
| Apple                            | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 152       | 26.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 5.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 24        | 4.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 2.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 1.41%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.06%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.06%   |
| Intel Wireless 8265 / 8275                                        | 5         | 0.88%   |
| Intel Wireless 8260                                               | 5         | 0.88%   |
| Intel Wireless 7265                                               | 5         | 0.88%   |
| Intel Wireless 7260                                               | 5         | 0.88%   |
| Intel I211 Gigabit Network Connection                             | 5         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 4         | 0.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.7%    |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.7%    |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 0.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.53%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 3         | 0.53%   |
| TP-Link 802.11n NIC                                               | 3         | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.53%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 83        | 32.94%  |
| Qualcomm Atheros                | 61        | 24.21%  |
| Realtek Semiconductor           | 60        | 23.81%  |
| Broadcom                        | 13        | 5.16%   |
| TP-Link                         | 12        | 4.76%   |
| Ralink Technology               | 6         | 2.38%   |
| Ralink                          | 5         | 1.98%   |
| Qualcomm Atheros Communications | 4         | 1.59%   |
| MediaTek                        | 3         | 1.19%   |
| Microsoft                       | 1         | 0.4%    |
| Marvell Technology Group        | 1         | 0.4%    |
| D-Link System                   | 1         | 0.4%    |
| D-Link                          | 1         | 0.4%    |
| Broadcom Limited                | 1         | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 9.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 5.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 5.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 3.17%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 3.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 2.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.78%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.38%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.98%   |
| Intel Wireless 8260                                                     | 5         | 1.98%   |
| Intel Wireless 7265                                                     | 5         | 1.98%   |
| Intel Wireless 7260                                                     | 5         | 1.98%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 1.59%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.59%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.59%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 3         | 1.19%   |
| TP-Link 802.11n NIC                                                     | 3         | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.19%   |
| Intel WiFi Link 5100                                                    | 3         | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.19%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                 | 2         | 0.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.79%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.79%   |
| Intel Wireless 3165                                                     | 2         | 0.79%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 193       | 61.86%  |
| Intel                            | 63        | 20.19%  |
| Qualcomm Atheros                 | 17        | 5.45%   |
| Nvidia                           | 4         | 1.28%   |
| Marvell Technology Group         | 4         | 1.28%   |
| ASIX Electronics                 | 4         | 1.28%   |
| Xiaomi                           | 3         | 0.96%   |
| ICS Advent                       | 3         | 0.96%   |
| Broadcom Limited                 | 3         | 0.96%   |
| Broadcom                         | 3         | 0.96%   |
| TP-Link                          | 2         | 0.64%   |
| Samsung Electronics              | 2         | 0.64%   |
| Motorola PCS                     | 2         | 0.64%   |
| Huawei Technologies              | 2         | 0.64%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.32%   |
| T & A Mobile Phones              | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| Microsoft                        | 1         | 0.32%   |
| Lenovo                           | 1         | 0.32%   |
| D-Link System                    | 1         | 0.32%   |
| Apple                            | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 152       | 48.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 29        | 9.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 3.8%    |
| Intel 82579V Gigabit Network Connection                                        | 7         | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 1.9%    |
| Intel I211 Gigabit Network Connection                                          | 5         | 1.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 1.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 0.95%   |
| Nvidia MCP61 Ethernet                                                          | 3         | 0.95%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 0.95%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.95%   |
| Intel 82578DC Gigabit Network Connection                                       | 3         | 0.95%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 3         | 0.95%   |
| TP-Link USB 10/100 LAN                                                         | 2         | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.63%   |
| Motorola PCS motorola one 5G ace                                               | 2         | 0.63%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.63%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.63%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.63%   |
| Huawei ELS-NX9                                                                 | 2         | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.63%   |
| ZTE WCDMA MSM Spreadtrum Phone                                                 | 1         | 0.32%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                                   | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.32%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.32%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.32%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.32%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.32%   |
| Microsoft Ethernet Adapter                                                     | 1         | 0.32%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 297       | 55%     |
| WiFi     | 243       | 45%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 184       | 52.72%  |
| Ethernet | 165       | 47.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 182       | 54.65%  |
| 1     | 143       | 42.94%  |
| 0     | 5         | 1.5%    |
| 3     | 2         | 0.6%    |
| 4     | 1         | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 276       | 81.9%   |
| Yes  | 61        | 18.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 33.16%  |
| Realtek Semiconductor           | 38        | 19.39%  |
| Qualcomm Atheros Communications | 31        | 15.82%  |
| IMC Networks                    | 11        | 5.61%   |
| Cambridge Silicon Radio         | 11        | 5.61%   |
| Lite-On Technology              | 10        | 5.1%    |
| Broadcom                        | 6         | 3.06%   |
| Toshiba                         | 5         | 2.55%   |
| Ralink                          | 4         | 2.04%   |
| Foxconn / Hon Hai               | 3         | 1.53%   |
| TP-Link                         | 2         | 1.02%   |
| Hewlett-Packard                 | 2         | 1.02%   |
| Dell                            | 2         | 1.02%   |
| TRENDnet                        | 1         | 0.51%   |
| Realtek                         | 1         | 0.51%   |
| Integrated System Solution      | 1         | 0.51%   |
| Foxconn International           | 1         | 0.51%   |
| Apple                           | 1         | 0.51%   |
| Alps Electric                   | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 23        | 11.73%  |
| Realtek  Bluetooth 4.2 Adapter                        | 20        | 10.2%   |
| Qualcomm Atheros  Bluetooth Device                    | 18        | 9.18%   |
| Realtek Bluetooth Radio                               | 15        | 7.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 13        | 6.63%   |
| Intel Bluetooth Device                                | 12        | 6.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 11        | 5.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 3.06%   |
| Intel AX200 Bluetooth                                 | 6         | 3.06%   |
| Lite-On Bluetooth Device                              | 5         | 2.55%   |
| Ralink RT3290 Bluetooth                               | 4         | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                      | 4         | 2.04%   |
| IMC Networks Bluetooth Radio                          | 4         | 2.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 3         | 1.53%   |
| Lite-On Bluetooth Radio                               | 3         | 1.53%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 1.53%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 3         | 1.53%   |
| IMC Networks Wireless_Device                          | 3         | 1.53%   |
| IMC Networks Bluetooth Device                         | 3         | 1.53%   |
| TP-Link TPuLink UB500 Adapter                         | 2         | 1.02%   |
| Toshiba Bluetooth Device                              | 2         | 1.02%   |
| Realtek RTL8723B Bluetooth                            | 2         | 1.02%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 2         | 1.02%   |
| HP Broadcom 2070 Bluetooth Combo                      | 2         | 1.02%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2         | 1.02%   |
| Broadcom BCM43142A0 Bluetooth Device                  | 2         | 1.02%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 2         | 1.02%   |
| TRENDnet TBW-108UB USB Adapter                        | 1         | 0.51%   |
| Toshiba RT Bluetooth Radio                            | 1         | 0.51%   |
| Toshiba BCM43142A0                                    | 1         | 0.51%   |
| Toshiba Askey Bluetooth Module                        | 1         | 0.51%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.51%   |
| Realtek Bluetooth Radio                               | 1         | 0.51%   |
| Qualcomm Atheros AR3012 Bluetooth                     | 1         | 0.51%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 1         | 0.51%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device          | 1         | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                      | 1         | 0.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 0.51%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.51%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 230       | 54.89%  |
| AMD                              | 104       | 24.82%  |
| Nvidia                           | 65        | 15.51%  |
| C-Media Electronics              | 4         | 0.95%   |
| Texas Instruments                | 2         | 0.48%   |
| Microsoft                        | 2         | 0.48%   |
| Generalplus Technology           | 2         | 0.48%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| Samson Technologies              | 1         | 0.24%   |
| Razer USA                        | 1         | 0.24%   |
| Pixart Imaging                   | 1         | 0.24%   |
| Logitech                         | 1         | 0.24%   |
| Kingston Technology              | 1         | 0.24%   |
| Hewlett-Packard                  | 1         | 0.24%   |
| Creative Labs                    | 1         | 0.24%   |
| Chicony Electronics              | 1         | 0.24%   |
| BEHRINGER International          | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 38        | 7.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 38        | 7.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 28        | 5.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 24        | 4.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 22        | 4.27%   |
| AMD FCH Azalia Controller                                                  | 17        | 3.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15        | 2.91%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 2.72%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13        | 2.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 2.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 2.14%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 2.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 2.14%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 2.14%   |
| Nvidia GF108 High Definition Audio Controller                              | 10        | 1.94%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 1.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 1.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.36%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                   | 7         | 1.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 1.36%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 1.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 1.17%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 0.97%   |
| Nvidia High Definition Audio Controller                                    | 4         | 0.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 0.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 0.78%   |
| AMD Trinity HDMI Audio Controller                                          | 4         | 0.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.78%   |
| AMD Navi 10 HDMI Audio                                                     | 4         | 0.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 4         | 0.78%   |
| Nvidia MCP61 High Definition Audio                                         | 3         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 58        | 25.55%  |
| Kingston                     | 50        | 22.03%  |
| SK hynix                     | 34        | 14.98%  |
| Micron Technology            | 30        | 13.22%  |
| Unknown                      | 14        | 6.17%   |
| Ramaxel Technology           | 7         | 3.08%   |
| Crucial                      | 6         | 2.64%   |
| Corsair                      | 6         | 2.64%   |
| Team                         | 5         | 2.2%    |
| Hewlett-Packard              | 3         | 1.32%   |
| Unknown (ABCD)               | 2         | 0.88%   |
| Unknown (0x7FA8000000000000) | 1         | 0.44%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 0.44%   |
| S                            | 1         | 0.44%   |
| Qumo                         | 1         | 0.44%   |
| Princeton                    | 1         | 0.44%   |
| Patriot                      | 1         | 0.44%   |
| Nanya Technology             | 1         | 0.44%   |
| M                            | 1         | 0.44%   |
| Goldkey                      | 1         | 0.44%   |
| GeIL                         | 1         | 0.44%   |
| CSX                          | 1         | 0.44%   |
| A-DATA Technology            | 1         | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 6         | 2.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 5         | 2.06%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 5         | 2.06%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 5         | 2.06%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 1.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s   | 3         | 1.23%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 3         | 1.23%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 1.23%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s       | 3         | 1.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 3         | 1.23%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 3         | 1.23%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 3         | 1.23%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 3         | 1.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 3         | 1.23%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s           | 3         | 1.23%   |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 2         | 0.82%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s       | 2         | 0.82%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 0.82%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s        | 2         | 0.82%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 0.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 2         | 0.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s | 2         | 0.82%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 0.82%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s       | 2         | 0.82%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 2         | 0.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 0.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 0.82%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 2         | 0.82%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s        | 2         | 0.82%   |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 2133MT/s      | 2         | 0.82%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s     | 2         | 0.82%   |
| Kingston RAM CL16-18-18 D4-3200 8192MB DIMM DDR4 3200MT/s   | 2         | 0.82%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s     | 2         | 0.82%   |
| Kingston RAM 99U5403-436.A00LF 8GB DIMM DDR3 1333MT/s       | 2         | 0.82%   |
| Kingston RAM 9905471-017.A00LF 4GB DIMM DDR3 1333MT/s       | 2         | 0.82%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s              | 1         | 0.41%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1         | 0.41%   |
| Unknown RAM Module 512MB SODIMM DDR2                        | 1         | 0.41%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s                  | 1         | 0.41%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s              | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 85        | 47.75%  |
| DDR3    | 66        | 37.08%  |
| DDR2    | 9         | 5.06%   |
| LPDDR4  | 7         | 3.93%   |
| LPDDR3  | 5         | 2.81%   |
| SDRAM   | 3         | 1.69%   |
| Unknown | 3         | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 110       | 61.8%   |
| DIMM         | 60        | 33.71%  |
| Row Of Chips | 8         | 4.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 81        | 39.32%  |
| 4096  | 70        | 33.98%  |
| 2048  | 24        | 11.65%  |
| 16384 | 19        | 9.22%   |
| 1024  | 5         | 2.43%   |
| 32768 | 4         | 1.94%   |
| 512   | 3         | 1.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 47        | 22.82%  |
| 1600    | 40        | 19.42%  |
| 3200    | 29        | 14.08%  |
| 1333    | 20        | 9.71%   |
| 2400    | 10        | 4.85%   |
| 2133    | 10        | 4.85%   |
| 3266    | 6         | 2.91%   |
| Unknown | 5         | 2.43%   |
| 1867    | 4         | 1.94%   |
| 1334    | 4         | 1.94%   |
| 3600    | 3         | 1.46%   |
| 3466    | 3         | 1.46%   |
| 1067    | 3         | 1.46%   |
| 800     | 3         | 1.46%   |
| 533     | 3         | 1.46%   |
| 1800    | 2         | 0.97%   |
| 4199    | 1         | 0.49%   |
| 3800    | 1         | 0.49%   |
| 3733    | 1         | 0.49%   |
| 3400    | 1         | 0.49%   |
| 3151    | 1         | 0.49%   |
| 3100    | 1         | 0.49%   |
| 2933    | 1         | 0.49%   |
| 2733    | 1         | 0.49%   |
| 2448    | 1         | 0.49%   |
| 2200    | 1         | 0.49%   |
| 2134    | 1         | 0.49%   |
| 1866    | 1         | 0.49%   |
| 667     | 1         | 0.49%   |
| 400     | 1         | 0.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 3         | 25%     |
| Brother Industries  | 3         | 25%     |
| Seiko Epson         | 2         | 16.67%  |
| Hewlett-Packard     | 2         | 16.67%  |
| Star Micronics      | 1         | 8.33%   |
| Prolific Technology | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Brother DCP-T310                  | 2         | 16.67%  |
| Star Micronics TUP592 (STR_T-001) | 1         | 8.33%   |
| Seiko Epson L3250 Series          | 1         | 8.33%   |
| Seiko Epson ET-2710 Series        | 1         | 8.33%   |
| Prolific PL2305 Parallel Port     | 1         | 8.33%   |
| HP PSC 1400                       | 1         | 8.33%   |
| HP LaserJet Professional P 1102w  | 1         | 8.33%   |
| Canon PIXMA MG3600 Series         | 1         | 8.33%   |
| Canon G2010 series                | 1         | 8.33%   |
| Canon E400 series                 | 1         | 8.33%   |
| Brother DCP-T300                  | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP ScanJet 2400c       | 1         | 50%     |
| Canon CanoScan LIDE 25 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 44        | 19.56%  |
| IMC Networks                           | 21        | 9.33%   |
| Acer                                   | 20        | 8.89%   |
| Microdia                               | 19        | 8.44%   |
| Realtek Semiconductor                  | 16        | 7.11%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 5.78%   |
| Syntek                                 | 12        | 5.33%   |
| Lite-On Technology                     | 11        | 4.89%   |
| Sunplus Innovation Technology          | 10        | 4.44%   |
| Quanta                                 | 10        | 4.44%   |
| Suyin                                  | 9         | 4%      |
| Logitech                               | 6         | 2.67%   |
| Z-Star Microelectronics                | 4         | 1.78%   |
| Microsoft                              | 4         | 1.78%   |
| Importek                               | 4         | 1.78%   |
| Sonix Technology                       | 3         | 1.33%   |
| Samsung Electronics                    | 3         | 1.33%   |
| Generalplus Technology                 | 3         | 1.33%   |
| Ricoh                                  | 2         | 0.89%   |
| Luxvisions Innotech Limited            | 2         | 0.89%   |
| Cubeternet                             | 2         | 0.89%   |
| Apple                                  | 2         | 0.89%   |
| Alcor Micro                            | 2         | 0.89%   |
| Xiongmai                               | 1         | 0.44%   |
| Aveo Technology                        | 1         | 0.44%   |
| ANYKA                                  | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 8         | 3.52%   |
| Acer Integrated Camera                                                     | 8         | 3.52%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 7         | 3.08%   |
| Microdia Integrated_Webcam_HD                                              | 5         | 2.2%    |
| Chicony Integrated Camera                                                  | 5         | 2.2%    |
| Chicony EasyCamera                                                         | 5         | 2.2%    |
| Lite-On Integrated Camera                                                  | 4         | 1.76%   |
| IMC Networks Integrated Camera                                             | 4         | 1.76%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.76%   |
| Chicony HD WebCam                                                          | 4         | 1.76%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 1.32%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 3         | 1.32%   |
| Samsung Galaxy A5 (MTP)                                                    | 3         | 1.32%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 1.32%   |
| Microdia USB 2.0 Camera                                                    | 3         | 1.32%   |
| Lite-On HP HD Camera                                                       | 3         | 1.32%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 1.32%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.32%   |
| Chicony HP Truevision HD                                                   | 3         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 1.32%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 0.88%   |
| Sunplus Integrated Webcam                                                  | 2         | 0.88%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 0.88%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 0.88%   |
| Realtek Integrated Webcam                                                  | 2         | 0.88%   |
| Realtek HP Wide Vision HD Camera                                           | 2         | 0.88%   |
| Quanta HP Webcam                                                           | 2         | 0.88%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 0.88%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks                        | 2         | 0.88%   |
| Microdia Webcam Vitade AF                                                  | 2         | 0.88%   |
| Microdia Camera                                                            | 2         | 0.88%   |
| Logitech C920 PRO HD Webcam                                                | 2         | 0.88%   |
| Lite-On HP Wide Vision HD Camera                                           | 2         | 0.88%   |
| IMC Networks HP TrueVision HD Camera                                       | 2         | 0.88%   |
| IMC Networks HD Camera                                                     | 2         | 0.88%   |
| Generalplus GENERAL WEBCAM                                                 | 2         | 0.88%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101]        | 2         | 0.88%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.88%   |
| Chicony USB2.0 HD UVC WebCam                                               | 2         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 46.51%  |
| Synaptics                  | 12        | 27.91%  |
| Shenzhen Goodix Technology | 6         | 13.95%  |
| Elan Microelectronics      | 3         | 6.98%   |
| STMicroelectronics         | 1         | 2.33%   |
| AuthenTec                  | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 7         | 16.28%  |
| Validity Sensors VFS5011 Fingerprint Reader                | 6         | 13.95%  |
| Synaptics  WBDI                                            | 4         | 9.3%    |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 6.98%   |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 6.98%   |
| Unknown                                                    | 3         | 6.98%   |
| Validity Sensors Fingerprint scanner                       | 2         | 4.65%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4.65%   |
| Elan ELAN:Fingerprint                                      | 2         | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.33%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.33%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.33%   |
| Validity Sensors Synaptics WBDI                            | 1         | 2.33%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 2.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.33%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.33%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.33%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Upek        | 3         | 30%     |
| Broadcom    | 3         | 30%     |
| Alcor Micro | 2         | 20%     |
| Yubico.com  | 1         | 10%     |
| O2 Micro    | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 30%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 241       | 70.88%  |
| 1     | 81        | 23.82%  |
| 2     | 13        | 3.82%   |
| 3     | 4         | 1.18%   |
| 5     | 1         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 43        | 37.39%  |
| Graphics card            | 25        | 21.74%  |
| Net/wireless             | 14        | 12.17%  |
| Chipcard                 | 9         | 7.83%   |
| Bluetooth                | 6         | 5.22%   |
| Card reader              | 3         | 2.61%   |
| Camera                   | 3         | 2.61%   |
| Storage                  | 2         | 1.74%   |
| Sound                    | 2         | 1.74%   |
| Multimedia controller    | 2         | 1.74%   |
| Communication controller | 2         | 1.74%   |
| Unassigned class         | 1         | 0.87%   |
| Network                  | 1         | 0.87%   |
| Net/ethernet             | 1         | 0.87%   |
| Firewire controller      | 1         | 0.87%   |

