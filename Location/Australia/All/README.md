Linux in Australia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Australia/Desktop/README.md) and [notebooks](/Location/Australia/Notebook/README.md).

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

Total: 4536

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [cf40d3f30c](https://linux-hardware.org/?probe=cf40d3f30c) | Dec 31, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [8b84042dc6](https://linux-hardware.org/?probe=8b84042dc6) | Dec 30, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [dae09ec15f](https://linux-hardware.org/?probe=dae09ec15f) | Dec 30, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [4e6065532f](https://linux-hardware.org/?probe=4e6065532f) | Dec 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [cc31efb32d](https://linux-hardware.org/?probe=cc31efb32d) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | Notebook    | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| AMI           | F3C2                        | Notebook    | [ed7d4a2a13](https://linux-hardware.org/?probe=ed7d4a2a13) | Dec 30, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [716ba7f970](https://linux-hardware.org/?probe=716ba7f970) | Dec 29, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [7881f027ea](https://linux-hardware.org/?probe=7881f027ea) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1cf63ef1ad](https://linux-hardware.org/?probe=1cf63ef1ad) | Dec 28, 2022 |
| HP            | 1905                        | Desktop     | [5c576316f8](https://linux-hardware.org/?probe=5c576316f8) | Dec 28, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [4929f6a6c9](https://linux-hardware.org/?probe=4929f6a6c9) | Dec 28, 2022 |
| Dell          | Inspiron 7586               | Convertible | [d670af270f](https://linux-hardware.org/?probe=d670af270f) | Dec 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [d1f63174e4](https://linux-hardware.org/?probe=d1f63174e4) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [7aab4546f6](https://linux-hardware.org/?probe=7aab4546f6) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [6eaa690ff2](https://linux-hardware.org/?probe=6eaa690ff2) | Dec 28, 2022 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Raider GE77HX 12UGS         | Notebook    | [9f7185ccd7](https://linux-hardware.org/?probe=9f7185ccd7) | Dec 27, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [d4fff49f31](https://linux-hardware.org/?probe=d4fff49f31) | Dec 27, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [6ad649ad46](https://linux-hardware.org/?probe=6ad649ad46) | Dec 26, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [6ac63aca4f](https://linux-hardware.org/?probe=6ac63aca4f) | Dec 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| MSI           | GP62M 7REX                  | Notebook    | [f49c90b8dc](https://linux-hardware.org/?probe=f49c90b8dc) | Dec 25, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [82de75771e](https://linux-hardware.org/?probe=82de75771e) | Dec 25, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b5eaa2b6aa](https://linux-hardware.org/?probe=b5eaa2b6aa) | Dec 25, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [b95d3d3c7a](https://linux-hardware.org/?probe=b95d3d3c7a) | Dec 25, 2022 |
| Dell          | Latitude E6520              | Notebook    | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [10b9f48473](https://linux-hardware.org/?probe=10b9f48473) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [2a7ce79df8](https://linux-hardware.org/?probe=2a7ce79df8) | Dec 24, 2022 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [d88bd74acf](https://linux-hardware.org/?probe=d88bd74acf) | Dec 24, 2022 |
| Toshiba       | Satellite C50D-C            | Notebook    | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [3073d2d4e1](https://linux-hardware.org/?probe=3073d2d4e1) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [29e02a10bf](https://linux-hardware.org/?probe=29e02a10bf) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [4732443b9e](https://linux-hardware.org/?probe=4732443b9e) | Dec 22, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [36fbefc790](https://linux-hardware.org/?probe=36fbefc790) | Dec 22, 2022 |
| MSI           | B85M-E45                    | Desktop     | [b60edb092f](https://linux-hardware.org/?probe=b60edb092f) | Dec 21, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [354b048898](https://linux-hardware.org/?probe=354b048898) | Dec 21, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| HP            | Pavilion dv6                | Notebook    | [8b0f82599c](https://linux-hardware.org/?probe=8b0f82599c) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [1fec8c22dc](https://linux-hardware.org/?probe=1fec8c22dc) | Dec 20, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [b8b3b4f2bd](https://linux-hardware.org/?probe=b8b3b4f2bd) | Dec 19, 2022 |
| Pegatron      | 2ACB                        | Desktop     | [f77ff3b9b5](https://linux-hardware.org/?probe=f77ff3b9b5) | Dec 19, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d45689035c](https://linux-hardware.org/?probe=d45689035c) | Dec 19, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [2318fda45f](https://linux-hardware.org/?probe=2318fda45f) | Dec 19, 2022 |
| MSI           | Boston                      | Desktop     | [8587c9cf45](https://linux-hardware.org/?probe=8587c9cf45) | Dec 19, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b0a4a9919c](https://linux-hardware.org/?probe=b0a4a9919c) | Dec 18, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [26ecfabc95](https://linux-hardware.org/?probe=26ecfabc95) | Dec 17, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a17338c77a](https://linux-hardware.org/?probe=a17338c77a) | Dec 17, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [50ba321b50](https://linux-hardware.org/?probe=50ba321b50) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [d54bfbf8ff](https://linux-hardware.org/?probe=d54bfbf8ff) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [310076ab4f](https://linux-hardware.org/?probe=310076ab4f) | Dec 16, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [2960bdb195](https://linux-hardware.org/?probe=2960bdb195) | Dec 16, 2022 |
| Intel         | NUC13SBBi9 M58736-302       | Mini pc     | [de15eb8246](https://linux-hardware.org/?probe=de15eb8246) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [aad215d28c](https://linux-hardware.org/?probe=aad215d28c) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [0f506ff34d](https://linux-hardware.org/?probe=0f506ff34d) | Dec 15, 2022 |
| HP            | 212A                        | Desktop     | [c21bb6d20d](https://linux-hardware.org/?probe=c21bb6d20d) | Dec 14, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b1386d66d5](https://linux-hardware.org/?probe=b1386d66d5) | Dec 13, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [e7ad1c21ad](https://linux-hardware.org/?probe=e7ad1c21ad) | Dec 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [265ba7b252](https://linux-hardware.org/?probe=265ba7b252) | Dec 13, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [259f85d65b](https://linux-hardware.org/?probe=259f85d65b) | Dec 12, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [6c3fcfbb13](https://linux-hardware.org/?probe=6c3fcfbb13) | Dec 12, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [8111a18c7c](https://linux-hardware.org/?probe=8111a18c7c) | Dec 12, 2022 |
| Dell          | XPS L521X                   | Notebook    | [c69c906797](https://linux-hardware.org/?probe=c69c906797) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4f1f6fde97](https://linux-hardware.org/?probe=4f1f6fde97) | Dec 10, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [b77b64cc48](https://linux-hardware.org/?probe=b77b64cc48) | Dec 09, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [26f5bfeb45](https://linux-hardware.org/?probe=26f5bfeb45) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [e95599a479](https://linux-hardware.org/?probe=e95599a479) | Dec 09, 2022 |
| Gigabyte      | EP45-DS4P                   | Desktop     | [5acdccf7c0](https://linux-hardware.org/?probe=5acdccf7c0) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b0de030271](https://linux-hardware.org/?probe=b0de030271) | Dec 09, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [3a67010b28](https://linux-hardware.org/?probe=3a67010b28) | Dec 08, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [5e56097f25](https://linux-hardware.org/?probe=5e56097f25) | Dec 08, 2022 |
| MSI           | PRO B650-P WIFI             | Desktop     | [b74866314e](https://linux-hardware.org/?probe=b74866314e) | Dec 08, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [bede7701b9](https://linux-hardware.org/?probe=bede7701b9) | Dec 08, 2022 |
| HP            | 3395                        | All in one  | [daedb871f5](https://linux-hardware.org/?probe=daedb871f5) | Dec 08, 2022 |
| HP            | ProLiant DL380 Gen9         | Server      | [d368f224c8](https://linux-hardware.org/?probe=d368f224c8) | Dec 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [6f715ffe60](https://linux-hardware.org/?probe=6f715ffe60) | Dec 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d1e2a097a9](https://linux-hardware.org/?probe=d1e2a097a9) | Dec 07, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [cfddc4ddef](https://linux-hardware.org/?probe=cfddc4ddef) | Dec 06, 2022 |
| Dell          | G15 5511                    | Notebook    | [999ed53283](https://linux-hardware.org/?probe=999ed53283) | Dec 05, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [36732e2602](https://linux-hardware.org/?probe=36732e2602) | Dec 05, 2022 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [32594286ae](https://linux-hardware.org/?probe=32594286ae) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [e3d7eb48ec](https://linux-hardware.org/?probe=e3d7eb48ec) | Dec 05, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [dd012c9f92](https://linux-hardware.org/?probe=dd012c9f92) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [fb96bd56ad](https://linux-hardware.org/?probe=fb96bd56ad) | Dec 04, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [cbb4692837](https://linux-hardware.org/?probe=cbb4692837) | Dec 04, 2022 |
| Unknown       | Unknown                     | Notebook    | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [c2a68eb192](https://linux-hardware.org/?probe=c2a68eb192) | Dec 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [370356b4a8](https://linux-hardware.org/?probe=370356b4a8) | Dec 02, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [bbdfc25e56](https://linux-hardware.org/?probe=bbdfc25e56) | Dec 02, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [7e188d7537](https://linux-hardware.org/?probe=7e188d7537) | Dec 02, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | Notebook    | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| IBM           | 90Y4784                     | Server      | [a9289ca04c](https://linux-hardware.org/?probe=a9289ca04c) | Dec 02, 2022 |
| Dell          | 01V648 A02                  | Server      | [b8747a97b7](https://linux-hardware.org/?probe=b8747a97b7) | Dec 02, 2022 |
| Intel         | S1200RP G62251-405          | Server      | [28f4ceb8ee](https://linux-hardware.org/?probe=28f4ceb8ee) | Dec 02, 2022 |
| IBM           | 00MV214                     | Server      | [f2d1382390](https://linux-hardware.org/?probe=f2d1382390) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [ca1fab4db1](https://linux-hardware.org/?probe=ca1fab4db1) | Dec 02, 2022 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [85f6854ce5](https://linux-hardware.org/?probe=85f6854ce5) | Dec 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [919c5d80c8](https://linux-hardware.org/?probe=919c5d80c8) | Dec 02, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0949d0916c](https://linux-hardware.org/?probe=0949d0916c) | Dec 02, 2022 |
| Shuttle       | FS81                        | Desktop     | [6352050887](https://linux-hardware.org/?probe=6352050887) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [2adab1a5b2](https://linux-hardware.org/?probe=2adab1a5b2) | Dec 02, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [e902390c9c](https://linux-hardware.org/?probe=e902390c9c) | Dec 02, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f9ff6b9e31](https://linux-hardware.org/?probe=f9ff6b9e31) | Dec 02, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [717d165f0e](https://linux-hardware.org/?probe=717d165f0e) | Dec 02, 2022 |
| ASRock        | AD525PV3                    | Desktop     | [da83c87218](https://linux-hardware.org/?probe=da83c87218) | Dec 01, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [c14e2149eb](https://linux-hardware.org/?probe=c14e2149eb) | Dec 01, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [ba1e414d62](https://linux-hardware.org/?probe=ba1e414d62) | Nov 30, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f4fa3a4e7f](https://linux-hardware.org/?probe=f4fa3a4e7f) | Nov 30, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [bc3188dd75](https://linux-hardware.org/?probe=bc3188dd75) | Nov 29, 2022 |
| AMI           | Intel                       | Notebook    | [3e2e312c6e](https://linux-hardware.org/?probe=3e2e312c6e) | Nov 29, 2022 |
| Razer         | Blade                       | Notebook    | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3433fd5db6](https://linux-hardware.org/?probe=3433fd5db6) | Nov 28, 2022 |
| MSI           | IONA                        | Desktop     | [255f7f8dc4](https://linux-hardware.org/?probe=255f7f8dc4) | Nov 28, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [ed4692d2a7](https://linux-hardware.org/?probe=ed4692d2a7) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| MSI           | IONA                        | Desktop     | [94841f2b61](https://linux-hardware.org/?probe=94841f2b61) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [3709af0366](https://linux-hardware.org/?probe=3709af0366) | Nov 27, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | Notebook    | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2d8e324570](https://linux-hardware.org/?probe=2d8e324570) | Nov 26, 2022 |
| Razer         | Blade Pro                   | Notebook    | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| HP            | 18E9                        | Desktop     | [dab5e242fd](https://linux-hardware.org/?probe=dab5e242fd) | Nov 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Dell          | Inspiron 7586               | Convertible | [91dcb3265a](https://linux-hardware.org/?probe=91dcb3265a) | Nov 24, 2022 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [1d224863f2](https://linux-hardware.org/?probe=1d224863f2) | Nov 24, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [5395a2556c](https://linux-hardware.org/?probe=5395a2556c) | Nov 24, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ac6ad8d54d](https://linux-hardware.org/?probe=ac6ad8d54d) | Nov 24, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [db3ccac179](https://linux-hardware.org/?probe=db3ccac179) | Nov 23, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [8ea3c120c6](https://linux-hardware.org/?probe=8ea3c120c6) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [62c77a0e63](https://linux-hardware.org/?probe=62c77a0e63) | Nov 23, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [f396cc27ff](https://linux-hardware.org/?probe=f396cc27ff) | Nov 23, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [db4e4c9c5b](https://linux-hardware.org/?probe=db4e4c9c5b) | Nov 22, 2022 |
| MSI           | IONA                        | Desktop     | [280083cfa1](https://linux-hardware.org/?probe=280083cfa1) | Nov 22, 2022 |
| MSI           | IONA                        | Desktop     | [39bcd0f2d8](https://linux-hardware.org/?probe=39bcd0f2d8) | Nov 22, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [06c02ff303](https://linux-hardware.org/?probe=06c02ff303) | Nov 21, 2022 |
| Acer          | TravelMate Spin B118-R      | Convertible | [16dc5dd369](https://linux-hardware.org/?probe=16dc5dd369) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | Notebook    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [cb18ed6ab1](https://linux-hardware.org/?probe=cb18ed6ab1) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [06a337fda3](https://linux-hardware.org/?probe=06a337fda3) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [965d9d2f5c](https://linux-hardware.org/?probe=965d9d2f5c) | Nov 20, 2022 |
| HP            | 1495                        | Desktop     | [3ac774a6d6](https://linux-hardware.org/?probe=3ac774a6d6) | Nov 19, 2022 |
| HP            | 1495                        | Desktop     | [659062ad1d](https://linux-hardware.org/?probe=659062ad1d) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | Notebook    | [2125546b68](https://linux-hardware.org/?probe=2125546b68) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | Notebook    | [6ea684de8c](https://linux-hardware.org/?probe=6ea684de8c) | Nov 19, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [806ac66c75](https://linux-hardware.org/?probe=806ac66c75) | Nov 19, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [587db1b08f](https://linux-hardware.org/?probe=587db1b08f) | Nov 19, 2022 |
| ASRock        | AD525PV3                    | Desktop     | [4bba69ecd9](https://linux-hardware.org/?probe=4bba69ecd9) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [884474637c](https://linux-hardware.org/?probe=884474637c) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0b7bd42177](https://linux-hardware.org/?probe=0b7bd42177) | Nov 18, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [dbbfcd826c](https://linux-hardware.org/?probe=dbbfcd826c) | Nov 18, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [2cb56b8c63](https://linux-hardware.org/?probe=2cb56b8c63) | Nov 17, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [e9eb63ca62](https://linux-hardware.org/?probe=e9eb63ca62) | Nov 17, 2022 |
| Dell          | 0D6H9T A01                  | Desktop     | [a50bca5670](https://linux-hardware.org/?probe=a50bca5670) | Nov 17, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [07d80f1783](https://linux-hardware.org/?probe=07d80f1783) | Nov 16, 2022 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [769e7a63d1](https://linux-hardware.org/?probe=769e7a63d1) | Nov 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [5e42accb39](https://linux-hardware.org/?probe=5e42accb39) | Nov 16, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| AMI           | Intel                       | Notebook    | [ac36a02403](https://linux-hardware.org/?probe=ac36a02403) | Nov 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [22b0ad0cb0](https://linux-hardware.org/?probe=22b0ad0cb0) | Nov 15, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [66737bb1cc](https://linux-hardware.org/?probe=66737bb1cc) | Nov 15, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Notebook    | [ccbda507a9](https://linux-hardware.org/?probe=ccbda507a9) | Nov 14, 2022 |
| Acer          | Aspire XC-840               | Desktop     | [fe8db55aac](https://linux-hardware.org/?probe=fe8db55aac) | Nov 14, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [fd017849be](https://linux-hardware.org/?probe=fd017849be) | Nov 13, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [97bfce0a04](https://linux-hardware.org/?probe=97bfce0a04) | Nov 13, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | Desktop     | [a84e5c2107](https://linux-hardware.org/?probe=a84e5c2107) | Nov 13, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [d37b8f7bbd](https://linux-hardware.org/?probe=d37b8f7bbd) | Nov 13, 2022 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [acce4cc1af](https://linux-hardware.org/?probe=acce4cc1af) | Nov 13, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [67c110e0a7](https://linux-hardware.org/?probe=67c110e0a7) | Nov 13, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [2d3a3f4ac8](https://linux-hardware.org/?probe=2d3a3f4ac8) | Nov 13, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [ea94d443c9](https://linux-hardware.org/?probe=ea94d443c9) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [2eacb090ee](https://linux-hardware.org/?probe=2eacb090ee) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [a35ca3673b](https://linux-hardware.org/?probe=a35ca3673b) | Nov 12, 2022 |
| ASRock        | B75M                        | Desktop     | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [755a70132f](https://linux-hardware.org/?probe=755a70132f) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [4371465097](https://linux-hardware.org/?probe=4371465097) | Nov 12, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Toshiba       | TECRA A40-D                 | Notebook    | [ab2d9e2712](https://linux-hardware.org/?probe=ab2d9e2712) | Nov 11, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [01cb4ff120](https://linux-hardware.org/?probe=01cb4ff120) | Nov 10, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [4ff6488cb2](https://linux-hardware.org/?probe=4ff6488cb2) | Nov 10, 2022 |
| Lenovo        | ThinkPad T420 4180PEM       | Notebook    | [ad4d7f338d](https://linux-hardware.org/?probe=ad4d7f338d) | Nov 09, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [3189f08179](https://linux-hardware.org/?probe=3189f08179) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [dbf32417df](https://linux-hardware.org/?probe=dbf32417df) | Nov 09, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | Desktop     | [f2afc66464](https://linux-hardware.org/?probe=f2afc66464) | Nov 09, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [8c775416b9](https://linux-hardware.org/?probe=8c775416b9) | Nov 08, 2022 |
| Microsoft     | Surface Laptop 2            | Tablet      | [43bf170205](https://linux-hardware.org/?probe=43bf170205) | Nov 08, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [638b6a52ff](https://linux-hardware.org/?probe=638b6a52ff) | Nov 08, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [ee895bde1f](https://linux-hardware.org/?probe=ee895bde1f) | Nov 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0e2747c7ab](https://linux-hardware.org/?probe=0e2747c7ab) | Nov 08, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [5f358af327](https://linux-hardware.org/?probe=5f358af327) | Nov 08, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| Dell          | 0DF42J A00                  | Desktop     | [67928f8921](https://linux-hardware.org/?probe=67928f8921) | Nov 07, 2022 |
| Microsoft     | Surface Laptop 2            | Tablet      | [27acb96a8f](https://linux-hardware.org/?probe=27acb96a8f) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a38da64b4f](https://linux-hardware.org/?probe=a38da64b4f) | Nov 07, 2022 |
| Gigabyte      | B660M D3H DDR4              | Desktop     | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | K53E                        | Notebook    | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [7ea9f2df61](https://linux-hardware.org/?probe=7ea9f2df61) | Nov 06, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [dd757fb650](https://linux-hardware.org/?probe=dd757fb650) | Nov 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [0d6bb9cde0](https://linux-hardware.org/?probe=0d6bb9cde0) | Nov 05, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [3d7692d178](https://linux-hardware.org/?probe=3d7692d178) | Nov 05, 2022 |
| HP            | 3396                        | Desktop     | [d6867789ca](https://linux-hardware.org/?probe=d6867789ca) | Nov 04, 2022 |
| MSI           | Katana GF76 12UC            | Notebook    | [3cb05bdb95](https://linux-hardware.org/?probe=3cb05bdb95) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4be0967ca1](https://linux-hardware.org/?probe=4be0967ca1) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [cc28dc5c8b](https://linux-hardware.org/?probe=cc28dc5c8b) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [c4b2b4072b](https://linux-hardware.org/?probe=c4b2b4072b) | Nov 04, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [a473b71b4e](https://linux-hardware.org/?probe=a473b71b4e) | Nov 03, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [921a646464](https://linux-hardware.org/?probe=921a646464) | Nov 03, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [80e0ccbf42](https://linux-hardware.org/?probe=80e0ccbf42) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Cube          | i18-BL                      | Notebook    | [725100a829](https://linux-hardware.org/?probe=725100a829) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| HP            | Notebook                    | Notebook    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| Acer          | Aspire 3000                 | Notebook    | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| ASUSTek       | X501A                       | Notebook    | [d5a34df414](https://linux-hardware.org/?probe=d5a34df414) | Nov 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [722ae37952](https://linux-hardware.org/?probe=722ae37952) | Nov 01, 2022 |
| ASUSTek       | B150M-V PLUS                | Desktop     | [a451844625](https://linux-hardware.org/?probe=a451844625) | Nov 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [a2a8473e4b](https://linux-hardware.org/?probe=a2a8473e4b) | Oct 31, 2022 |
| ASRock        | X670E Pro RS                | Desktop     | [5ebdf73c67](https://linux-hardware.org/?probe=5ebdf73c67) | Oct 31, 2022 |
| HP            | 8653 A                      | Desktop     | [9c19089f51](https://linux-hardware.org/?probe=9c19089f51) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [1c5d979ba1](https://linux-hardware.org/?probe=1c5d979ba1) | Oct 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [883100c74f](https://linux-hardware.org/?probe=883100c74f) | Oct 29, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [1d3ff229c6](https://linux-hardware.org/?probe=1d3ff229c6) | Oct 29, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c3ea4065c4](https://linux-hardware.org/?probe=c3ea4065c4) | Oct 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [629858e96c](https://linux-hardware.org/?probe=629858e96c) | Oct 29, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [af4751bfcf](https://linux-hardware.org/?probe=af4751bfcf) | Oct 28, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [2e4153161f](https://linux-hardware.org/?probe=2e4153161f) | Oct 28, 2022 |
| ASUSTek       | U50Vg                       | Notebook    | [5f2997ec95](https://linux-hardware.org/?probe=5f2997ec95) | Oct 28, 2022 |
| HP            | 829B                        | All in one  | [1f8f75d1c0](https://linux-hardware.org/?probe=1f8f75d1c0) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [b096155d39](https://linux-hardware.org/?probe=b096155d39) | Oct 27, 2022 |
| HP            | 8653 A                      | Desktop     | [92b68870ca](https://linux-hardware.org/?probe=92b68870ca) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | G71                         | Notebook    | [3223e2fcc8](https://linux-hardware.org/?probe=3223e2fcc8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [df069d17c5](https://linux-hardware.org/?probe=df069d17c5) | Oct 26, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [54f6493d11](https://linux-hardware.org/?probe=54f6493d11) | Oct 26, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [3848afd2c8](https://linux-hardware.org/?probe=3848afd2c8) | Oct 26, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [6896f337ab](https://linux-hardware.org/?probe=6896f337ab) | Oct 25, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [82fb357322](https://linux-hardware.org/?probe=82fb357322) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [23be2713d2](https://linux-hardware.org/?probe=23be2713d2) | Oct 24, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [6331b122dc](https://linux-hardware.org/?probe=6331b122dc) | Oct 24, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [6f72d6443c](https://linux-hardware.org/?probe=6f72d6443c) | Oct 23, 2022 |
| HP            | 0B40h                       | Desktop     | [981b4e9553](https://linux-hardware.org/?probe=981b4e9553) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Notebook      | W650EH                      | Notebook    | [6bb1a8b1f1](https://linux-hardware.org/?probe=6bb1a8b1f1) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [32cd9cd246](https://linux-hardware.org/?probe=32cd9cd246) | Oct 22, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3e2bd05f56](https://linux-hardware.org/?probe=3e2bd05f56) | Oct 22, 2022 |
| Purism        | Librem 13 v2                | Notebook    | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [1ab730c85c](https://linux-hardware.org/?probe=1ab730c85c) | Oct 21, 2022 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [bc75d3cc30](https://linux-hardware.org/?probe=bc75d3cc30) | Oct 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60d4787bb7](https://linux-hardware.org/?probe=60d4787bb7) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [502ae94f8f](https://linux-hardware.org/?probe=502ae94f8f) | Oct 20, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [5086e64fed](https://linux-hardware.org/?probe=5086e64fed) | Oct 19, 2022 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [4c9eafcd7f](https://linux-hardware.org/?probe=4c9eafcd7f) | Oct 19, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| HP            | 2B21 A01                    | All in one  | [8a8935ed07](https://linux-hardware.org/?probe=8a8935ed07) | Oct 18, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| HP            | G71                         | Notebook    | [46b6033e1e](https://linux-hardware.org/?probe=46b6033e1e) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [f30aab43b6](https://linux-hardware.org/?probe=f30aab43b6) | Oct 16, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| System76      | Galago Pro                  | Notebook    | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [79eba98b95](https://linux-hardware.org/?probe=79eba98b95) | Oct 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [5f0c4b3acb](https://linux-hardware.org/?probe=5f0c4b3acb) | Oct 13, 2022 |
| Acer          | Aspire XC100A               | Desktop     | [6fade2c77f](https://linux-hardware.org/?probe=6fade2c77f) | Oct 13, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [705e4f406a](https://linux-hardware.org/?probe=705e4f406a) | Oct 13, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cd65876f22](https://linux-hardware.org/?probe=cd65876f22) | Oct 12, 2022 |
| HP            | 1497                        | Desktop     | [ff6d690da4](https://linux-hardware.org/?probe=ff6d690da4) | Oct 12, 2022 |
| Gigabyte      | X570S GAMING X              | Desktop     | [e966aea162](https://linux-hardware.org/?probe=e966aea162) | Oct 12, 2022 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | Desktop     | [1798dba7f1](https://linux-hardware.org/?probe=1798dba7f1) | Oct 12, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [4bc40092b2](https://linux-hardware.org/?probe=4bc40092b2) | Oct 11, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| Dell          | 07WJF3 A00                  | Desktop     | [62f8858433](https://linux-hardware.org/?probe=62f8858433) | Oct 11, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dde4a94108](https://linux-hardware.org/?probe=dde4a94108) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Gigabyte      | H410M DS2V                  | Desktop     | [bd9d9e10c7](https://linux-hardware.org/?probe=bd9d9e10c7) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| Dell          | Inspiron 16 5620            | Notebook    | [72151cd0e8](https://linux-hardware.org/?probe=72151cd0e8) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | Notebook    | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [a7b96649da](https://linux-hardware.org/?probe=a7b96649da) | Oct 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e26fca4929](https://linux-hardware.org/?probe=e26fca4929) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | Notebook    | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | Notebook    | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [027504f861](https://linux-hardware.org/?probe=027504f861) | Oct 08, 2022 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [2ad7a0c296](https://linux-hardware.org/?probe=2ad7a0c296) | Oct 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Shuttle       | FS81                        | Desktop     | [ba7c22e135](https://linux-hardware.org/?probe=ba7c22e135) | Oct 07, 2022 |
| Shuttle       | FS81                        | Desktop     | [63ec5c8971](https://linux-hardware.org/?probe=63ec5c8971) | Oct 07, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e05dbad108](https://linux-hardware.org/?probe=e05dbad108) | Oct 07, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [9dc72dc357](https://linux-hardware.org/?probe=9dc72dc357) | Oct 07, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [3ea8d4d25e](https://linux-hardware.org/?probe=3ea8d4d25e) | Oct 06, 2022 |
| HP            | Presario V4000 (EQ608PA#... | Notebook    | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [9ad9a1c969](https://linux-hardware.org/?probe=9ad9a1c969) | Oct 06, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [2e57f97484](https://linux-hardware.org/?probe=2e57f97484) | Oct 06, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [9232451f1a](https://linux-hardware.org/?probe=9232451f1a) | Oct 06, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b5cf733c51](https://linux-hardware.org/?probe=b5cf733c51) | Oct 06, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [4f3856c8f0](https://linux-hardware.org/?probe=4f3856c8f0) | Oct 06, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [5ff1f9c5c3](https://linux-hardware.org/?probe=5ff1f9c5c3) | Oct 05, 2022 |
| Lenovo        | ThinkStation S30 0569BE3    | Desktop     | [026d1ee25e](https://linux-hardware.org/?probe=026d1ee25e) | Oct 05, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [ca81117136](https://linux-hardware.org/?probe=ca81117136) | Oct 05, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| Dell          | 0WF810                      | Desktop     | [dd24119965](https://linux-hardware.org/?probe=dd24119965) | Oct 04, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [47d31ff25c](https://linux-hardware.org/?probe=47d31ff25c) | Oct 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a7e31149f2](https://linux-hardware.org/?probe=a7e31149f2) | Oct 02, 2022 |
| Dell          | 0XCR8D A00                  | Desktop     | [82e52ab722](https://linux-hardware.org/?probe=82e52ab722) | Oct 02, 2022 |
| Dell          | 0XCR8D A00                  | Desktop     | [a6db1f5075](https://linux-hardware.org/?probe=a6db1f5075) | Oct 02, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [521636075a](https://linux-hardware.org/?probe=521636075a) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FE00... | Convertible | [4eaeb1d5ad](https://linux-hardware.org/?probe=4eaeb1d5ad) | Oct 01, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4275ef3653](https://linux-hardware.org/?probe=4275ef3653) | Oct 01, 2022 |
| MSI           | PRO X670-P WIFI             | Desktop     | [64299c7b4a](https://linux-hardware.org/?probe=64299c7b4a) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [4662cb1d99](https://linux-hardware.org/?probe=4662cb1d99) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [3f01bbaa12](https://linux-hardware.org/?probe=3f01bbaa12) | Sep 30, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [927bf01e34](https://linux-hardware.org/?probe=927bf01e34) | Sep 30, 2022 |
| Gigabyte      | AORUS 17 YE5                | Notebook    | [54b271c3fd](https://linux-hardware.org/?probe=54b271c3fd) | Sep 30, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [cc7ad91815](https://linux-hardware.org/?probe=cc7ad91815) | Sep 29, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | Notebook    | [ac3079df8c](https://linux-hardware.org/?probe=ac3079df8c) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | Notebook    | [144cad649c](https://linux-hardware.org/?probe=144cad649c) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| Dell          | Latitude E7450              | Notebook    | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Acer          | Spin SP314-53               | Convertible | [ce95ade177](https://linux-hardware.org/?probe=ce95ade177) | Sep 27, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [565d46fb85](https://linux-hardware.org/?probe=565d46fb85) | Sep 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2c69225287](https://linux-hardware.org/?probe=2c69225287) | Sep 27, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [1b2f7b8972](https://linux-hardware.org/?probe=1b2f7b8972) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| System76      | Galago Pro                  | Notebook    | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [dce9d30a10](https://linux-hardware.org/?probe=dce9d30a10) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| Dell          | G15 5511                    | Notebook    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [a96f37005a](https://linux-hardware.org/?probe=a96f37005a) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [479dfeae74](https://linux-hardware.org/?probe=479dfeae74) | Sep 25, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6c8a53f608](https://linux-hardware.org/?probe=6c8a53f608) | Sep 25, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [cedbd8909f](https://linux-hardware.org/?probe=cedbd8909f) | Sep 25, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [66b5b65077](https://linux-hardware.org/?probe=66b5b65077) | Sep 25, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [05dc7a54c7](https://linux-hardware.org/?probe=05dc7a54c7) | Sep 25, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [a35dda8c10](https://linux-hardware.org/?probe=a35dda8c10) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [b598ecc4f8](https://linux-hardware.org/?probe=b598ecc4f8) | Sep 24, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [0299e4f7b1](https://linux-hardware.org/?probe=0299e4f7b1) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [cad0f6f375](https://linux-hardware.org/?probe=cad0f6f375) | Sep 24, 2022 |
| MSI           | C236A WORKSTATION           | Desktop     | [67432a461e](https://linux-hardware.org/?probe=67432a461e) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [91d179670c](https://linux-hardware.org/?probe=91d179670c) | Sep 23, 2022 |
| Acer          | TMP645-M                    | Notebook    | [83b27c389c](https://linux-hardware.org/?probe=83b27c389c) | Sep 23, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [d8d21241de](https://linux-hardware.org/?probe=d8d21241de) | Sep 23, 2022 |
| ASUSTek       | P6T                         | Desktop     | [612682c52d](https://linux-hardware.org/?probe=612682c52d) | Sep 23, 2022 |
| Dell          | Precision 7760              | Notebook    | [f47fe0314b](https://linux-hardware.org/?probe=f47fe0314b) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | Notebook    | [a01352810a](https://linux-hardware.org/?probe=a01352810a) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | Notebook    | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d97b8fc0ed](https://linux-hardware.org/?probe=d97b8fc0ed) | Sep 21, 2022 |
| ASRock        | Z690 Pro RS                 | Desktop     | [787589762f](https://linux-hardware.org/?probe=787589762f) | Sep 21, 2022 |
| Shuttle       | FS81                        | Desktop     | [4c1fb942aa](https://linux-hardware.org/?probe=4c1fb942aa) | Sep 20, 2022 |
| ASRock        | HM55-HT                     | Desktop     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [5cf4494f07](https://linux-hardware.org/?probe=5cf4494f07) | Sep 20, 2022 |
| ASRock        | H610M-HDV/M.2               | Desktop     | [02a5a10d7a](https://linux-hardware.org/?probe=02a5a10d7a) | Sep 20, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [7c7043ad0f](https://linux-hardware.org/?probe=7c7043ad0f) | Sep 19, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [48d71b12fc](https://linux-hardware.org/?probe=48d71b12fc) | Sep 19, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [43fbf9fec9](https://linux-hardware.org/?probe=43fbf9fec9) | Sep 19, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [850e17ede5](https://linux-hardware.org/?probe=850e17ede5) | Sep 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [6c63c03b9f](https://linux-hardware.org/?probe=6c63c03b9f) | Sep 19, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [3b5d6a5b1d](https://linux-hardware.org/?probe=3b5d6a5b1d) | Sep 18, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [3b1ce0471e](https://linux-hardware.org/?probe=3b1ce0471e) | Sep 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [126b3ed209](https://linux-hardware.org/?probe=126b3ed209) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [08c270ce3d](https://linux-hardware.org/?probe=08c270ce3d) | Sep 14, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [6121dfd67d](https://linux-hardware.org/?probe=6121dfd67d) | Sep 13, 2022 |
| HP            | ENVY 15                     | Notebook    | [fdb07294df](https://linux-hardware.org/?probe=fdb07294df) | Sep 13, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [ebd7ab6202](https://linux-hardware.org/?probe=ebd7ab6202) | Sep 12, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [613f741235](https://linux-hardware.org/?probe=613f741235) | Sep 12, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [491242ea90](https://linux-hardware.org/?probe=491242ea90) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [21ae14e7a0](https://linux-hardware.org/?probe=21ae14e7a0) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [3ddd0d7aa0](https://linux-hardware.org/?probe=3ddd0d7aa0) | Sep 11, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [c3ceb9c38b](https://linux-hardware.org/?probe=c3ceb9c38b) | Sep 11, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [2cb423c8e7](https://linux-hardware.org/?probe=2cb423c8e7) | Sep 10, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e8c2730c9](https://linux-hardware.org/?probe=1e8c2730c9) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3c454664b0](https://linux-hardware.org/?probe=3c454664b0) | Sep 09, 2022 |
| Dell          | Latitude E7470              | Notebook    | [4a2f647549](https://linux-hardware.org/?probe=4a2f647549) | Sep 08, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [e36022370b](https://linux-hardware.org/?probe=e36022370b) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| ASUSTek       | X99-E WS/USB                | Desktop     | [56357e3cc7](https://linux-hardware.org/?probe=56357e3cc7) | Sep 07, 2022 |
| ASUSTek       | X99-E WS/USB                | Desktop     | [3432790e95](https://linux-hardware.org/?probe=3432790e95) | Sep 07, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [01dbdc3b29](https://linux-hardware.org/?probe=01dbdc3b29) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [ccd383a106](https://linux-hardware.org/?probe=ccd383a106) | Sep 05, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [c37bace401](https://linux-hardware.org/?probe=c37bace401) | Sep 05, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | Desktop     | [0859dbdb1c](https://linux-hardware.org/?probe=0859dbdb1c) | Sep 04, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [a746f6faa6](https://linux-hardware.org/?probe=a746f6faa6) | Sep 04, 2022 |
| HP            | 2AF3                        | Desktop     | [58eae39fe2](https://linux-hardware.org/?probe=58eae39fe2) | Sep 03, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [e03d937610](https://linux-hardware.org/?probe=e03d937610) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [0a1de8a406](https://linux-hardware.org/?probe=0a1de8a406) | Sep 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [888ed47bbe](https://linux-hardware.org/?probe=888ed47bbe) | Sep 02, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [67aeed6eb1](https://linux-hardware.org/?probe=67aeed6eb1) | Sep 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [2cf98644bc](https://linux-hardware.org/?probe=2cf98644bc) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| HP            | Notebook                    | Notebook    | [ee135c3930](https://linux-hardware.org/?probe=ee135c3930) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [53af4f5de7](https://linux-hardware.org/?probe=53af4f5de7) | Aug 30, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [897046248f](https://linux-hardware.org/?probe=897046248f) | Aug 30, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [eaa574481f](https://linux-hardware.org/?probe=eaa574481f) | Aug 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [fd4ab67b77](https://linux-hardware.org/?probe=fd4ab67b77) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| IT Channel... | NH5xAx                      | Notebook    | [66573b4b48](https://linux-hardware.org/?probe=66573b4b48) | Aug 28, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [a0f47aaaa7](https://linux-hardware.org/?probe=a0f47aaaa7) | Aug 28, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [459c7c1eee](https://linux-hardware.org/?probe=459c7c1eee) | Aug 27, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [137641269c](https://linux-hardware.org/?probe=137641269c) | Aug 27, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Acer          | Aspire V5-531               | Notebook    | [75b841b0b8](https://linux-hardware.org/?probe=75b841b0b8) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Dell          | Latitude 5300               | Notebook    | [f336b3aeaf](https://linux-hardware.org/?probe=f336b3aeaf) | Aug 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [f37ee1975e](https://linux-hardware.org/?probe=f37ee1975e) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [e21e07827d](https://linux-hardware.org/?probe=e21e07827d) | Aug 26, 2022 |
| Acer          | Aspire V5-531               | Notebook    | [4ae228e219](https://linux-hardware.org/?probe=4ae228e219) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2388b95ce9](https://linux-hardware.org/?probe=2388b95ce9) | Aug 25, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [a766ce2d5a](https://linux-hardware.org/?probe=a766ce2d5a) | Aug 24, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [fda9abd530](https://linux-hardware.org/?probe=fda9abd530) | Aug 24, 2022 |
| HP            | 1905                        | Desktop     | [6693a2b3c7](https://linux-hardware.org/?probe=6693a2b3c7) | Aug 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [18102e8a9a](https://linux-hardware.org/?probe=18102e8a9a) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [738a69419b](https://linux-hardware.org/?probe=738a69419b) | Aug 24, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [d609bf3253](https://linux-hardware.org/?probe=d609bf3253) | Aug 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [7dae220687](https://linux-hardware.org/?probe=7dae220687) | Aug 23, 2022 |
| Alienware     | 15 R4                       | Notebook    | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [75f94f8fa5](https://linux-hardware.org/?probe=75f94f8fa5) | Aug 21, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4be47e3738](https://linux-hardware.org/?probe=4be47e3738) | Aug 21, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [c369daf6b0](https://linux-hardware.org/?probe=c369daf6b0) | Aug 21, 2022 |
| ASRock        | Z77 Extreme6                | Desktop     | [660091e5bb](https://linux-hardware.org/?probe=660091e5bb) | Aug 20, 2022 |
| Google        | Teemo                       | Desktop     | [4cc9295e6d](https://linux-hardware.org/?probe=4cc9295e6d) | Aug 20, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [7a8fee05aa](https://linux-hardware.org/?probe=7a8fee05aa) | Aug 20, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [c9738d69e9](https://linux-hardware.org/?probe=c9738d69e9) | Aug 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [9bfc03d98e](https://linux-hardware.org/?probe=9bfc03d98e) | Aug 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [ed2076bba5](https://linux-hardware.org/?probe=ed2076bba5) | Aug 20, 2022 |
| ASUSTek       | X756UAK                     | Notebook    | [6db3b2a7bc](https://linux-hardware.org/?probe=6db3b2a7bc) | Aug 20, 2022 |
| Dell          | G3 3779                     | Notebook    | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1e4e125d11](https://linux-hardware.org/?probe=1e4e125d11) | Aug 17, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | Notebook    | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [1efeb7be2c](https://linux-hardware.org/?probe=1efeb7be2c) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [125fdc6af1](https://linux-hardware.org/?probe=125fdc6af1) | Aug 17, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [87ba9f4be1](https://linux-hardware.org/?probe=87ba9f4be1) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [e68748c0f1](https://linux-hardware.org/?probe=e68748c0f1) | Aug 16, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [171a797c22](https://linux-hardware.org/?probe=171a797c22) | Aug 16, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [f882fcbe3a](https://linux-hardware.org/?probe=f882fcbe3a) | Aug 16, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [8072e15459](https://linux-hardware.org/?probe=8072e15459) | Aug 15, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [20d9ba44b5](https://linux-hardware.org/?probe=20d9ba44b5) | Aug 15, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [be0b70efdb](https://linux-hardware.org/?probe=be0b70efdb) | Aug 15, 2022 |
| MSI           | H61M-P20                    | Desktop     | [9adc2fa427](https://linux-hardware.org/?probe=9adc2fa427) | Aug 15, 2022 |
| HP            | 1493                        | Desktop     | [e5d0f16bbc](https://linux-hardware.org/?probe=e5d0f16bbc) | Aug 14, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [dc9013cc44](https://linux-hardware.org/?probe=dc9013cc44) | Aug 14, 2022 |
| ASRock        | AB350 Gaming K4             | Desktop     | [8a6141848a](https://linux-hardware.org/?probe=8a6141848a) | Aug 13, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| MSI           | H61M-P20                    | Desktop     | [acc2520058](https://linux-hardware.org/?probe=acc2520058) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [762d78160d](https://linux-hardware.org/?probe=762d78160d) | Aug 12, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [662f0801b7](https://linux-hardware.org/?probe=662f0801b7) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Dell          | Latitude 6430U              | Notebook    | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| Gigabyte      | Z87M-D3HP                   | Desktop     | [b6612680e2](https://linux-hardware.org/?probe=b6612680e2) | Aug 11, 2022 |
| ASRock        | X58 Extreme3                | Desktop     | [81f68d4fc7](https://linux-hardware.org/?probe=81f68d4fc7) | Aug 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [dc354e0b4f](https://linux-hardware.org/?probe=dc354e0b4f) | Aug 10, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [62d813423e](https://linux-hardware.org/?probe=62d813423e) | Aug 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [e74a95c4d9](https://linux-hardware.org/?probe=e74a95c4d9) | Aug 09, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [42d32cdfda](https://linux-hardware.org/?probe=42d32cdfda) | Aug 09, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7f1e38b57b](https://linux-hardware.org/?probe=7f1e38b57b) | Aug 07, 2022 |
| HP            | 2B21 A01                    | All in one  | [aba1a53f52](https://linux-hardware.org/?probe=aba1a53f52) | Aug 07, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [6a73917b78](https://linux-hardware.org/?probe=6a73917b78) | Aug 07, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [db3d9f24c6](https://linux-hardware.org/?probe=db3d9f24c6) | Aug 07, 2022 |
| ASUSTek       | ET2701I-W8                  | Desktop     | [5f9c4b50db](https://linux-hardware.org/?probe=5f9c4b50db) | Aug 07, 2022 |
| Unknown       | Unknown                     | Soc         | [9efd347024](https://linux-hardware.org/?probe=9efd347024) | Aug 06, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [fd6cf872ae](https://linux-hardware.org/?probe=fd6cf872ae) | Aug 06, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [1798c25088](https://linux-hardware.org/?probe=1798c25088) | Aug 05, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | Notebook    | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | Notebook    | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [209cd4bc66](https://linux-hardware.org/?probe=209cd4bc66) | Aug 05, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [caa404d4c6](https://linux-hardware.org/?probe=caa404d4c6) | Aug 05, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [8b737740c3](https://linux-hardware.org/?probe=8b737740c3) | Aug 05, 2022 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [e477bf9f83](https://linux-hardware.org/?probe=e477bf9f83) | Aug 05, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [3ef0714d78](https://linux-hardware.org/?probe=3ef0714d78) | Aug 04, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [360447806b](https://linux-hardware.org/?probe=360447806b) | Aug 04, 2022 |
| Dell          | 06WXJT A02                  | Server      | [424b1059df](https://linux-hardware.org/?probe=424b1059df) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| Lenovo        | 3102                        | Desktop     | [73e0fee2bc](https://linux-hardware.org/?probe=73e0fee2bc) | Aug 03, 2022 |
| Dell          | 06WXJT A07                  | Server      | [e0b1ede266](https://linux-hardware.org/?probe=e0b1ede266) | Aug 03, 2022 |
| Dell          | 06WXJT A02                  | Server      | [fcf7baab04](https://linux-hardware.org/?probe=fcf7baab04) | Aug 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [713884d2c8](https://linux-hardware.org/?probe=713884d2c8) | Aug 03, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [b81c8578b9](https://linux-hardware.org/?probe=b81c8578b9) | Aug 03, 2022 |
| Dell          | XPS 9320                    | Notebook    | [9b24b29553](https://linux-hardware.org/?probe=9b24b29553) | Aug 03, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [63553d673b](https://linux-hardware.org/?probe=63553d673b) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Hardkernel    | ODROID-C4                   | Soc         | [85ed0f33f0](https://linux-hardware.org/?probe=85ed0f33f0) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | Notebook    | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [b352b7e051](https://linux-hardware.org/?probe=b352b7e051) | Aug 02, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [2de5d5cf8a](https://linux-hardware.org/?probe=2de5d5cf8a) | Aug 02, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [77687a9bac](https://linux-hardware.org/?probe=77687a9bac) | Aug 02, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [6127d6e7a3](https://linux-hardware.org/?probe=6127d6e7a3) | Aug 02, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [9983a0cc64](https://linux-hardware.org/?probe=9983a0cc64) | Aug 02, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [dcccfd1beb](https://linux-hardware.org/?probe=dcccfd1beb) | Aug 01, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [e1fa8ab12b](https://linux-hardware.org/?probe=e1fa8ab12b) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [81c46b891f](https://linux-hardware.org/?probe=81c46b891f) | Aug 01, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [d58be7b6d1](https://linux-hardware.org/?probe=d58be7b6d1) | Aug 01, 2022 |
| Unknown       | Unknown                     | Soc         | [9ebddaa953](https://linux-hardware.org/?probe=9ebddaa953) | Jul 31, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [e8dba6ab7e](https://linux-hardware.org/?probe=e8dba6ab7e) | Jul 31, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f6a106d6df](https://linux-hardware.org/?probe=f6a106d6df) | Jul 31, 2022 |
| Intel         | NUC7i5BNB J31144-302        | Mini pc     | [638275ad97](https://linux-hardware.org/?probe=638275ad97) | Jul 31, 2022 |
| HP            | 82F2                        | Desktop     | [0c2d091c2e](https://linux-hardware.org/?probe=0c2d091c2e) | Jul 31, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [c7ed484a1f](https://linux-hardware.org/?probe=c7ed484a1f) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [51695dd3ea](https://linux-hardware.org/?probe=51695dd3ea) | Jul 29, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [2381ee35c0](https://linux-hardware.org/?probe=2381ee35c0) | Jul 29, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [73c8bc2ae1](https://linux-hardware.org/?probe=73c8bc2ae1) | Jul 28, 2022 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | Desktop     | [757ba0f252](https://linux-hardware.org/?probe=757ba0f252) | Jul 28, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [1357e3b3d3](https://linux-hardware.org/?probe=1357e3b3d3) | Jul 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [e42501aacb](https://linux-hardware.org/?probe=e42501aacb) | Jul 28, 2022 |
| ASUSTek       | X555YA                      | Notebook    | [ddd00fbeea](https://linux-hardware.org/?probe=ddd00fbeea) | Jul 28, 2022 |
| Unknown       | HX90                        | Desktop     | [1594710372](https://linux-hardware.org/?probe=1594710372) | Jul 28, 2022 |
| Dell          | Latitude E7250              | Notebook    | [26a8591f1d](https://linux-hardware.org/?probe=26a8591f1d) | Jul 27, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [761563e485](https://linux-hardware.org/?probe=761563e485) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [331a99ef9a](https://linux-hardware.org/?probe=331a99ef9a) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [1f3433b9e1](https://linux-hardware.org/?probe=1f3433b9e1) | Jul 26, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [876c60188f](https://linux-hardware.org/?probe=876c60188f) | Jul 26, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [050aa57cb4](https://linux-hardware.org/?probe=050aa57cb4) | Jul 26, 2022 |
| Dell          | Latitude 3400               | Notebook    | [3412e8deac](https://linux-hardware.org/?probe=3412e8deac) | Jul 26, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [e4c223e83e](https://linux-hardware.org/?probe=e4c223e83e) | Jul 25, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7af6c5cebe](https://linux-hardware.org/?probe=7af6c5cebe) | Jul 24, 2022 |
| Lenovo        | 3702 SDK0J40700 WIN 3258... | All in one  | [95af4e4f8e](https://linux-hardware.org/?probe=95af4e4f8e) | Jul 23, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [d57e35934f](https://linux-hardware.org/?probe=d57e35934f) | Jul 22, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [2723b19c18](https://linux-hardware.org/?probe=2723b19c18) | Jul 22, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [80dcd8a0f7](https://linux-hardware.org/?probe=80dcd8a0f7) | Jul 22, 2022 |
| Google        | Peppy                       | Notebook    | [3bfdae8e5e](https://linux-hardware.org/?probe=3bfdae8e5e) | Jul 21, 2022 |
| Acer          | Aspire One 753              | Notebook    | [eff74923d7](https://linux-hardware.org/?probe=eff74923d7) | Jul 21, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [89e0889e94](https://linux-hardware.org/?probe=89e0889e94) | Jul 21, 2022 |
| Dell          | Latitude 5430               | Notebook    | [f02c4072c1](https://linux-hardware.org/?probe=f02c4072c1) | Jul 21, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [c3722806fe](https://linux-hardware.org/?probe=c3722806fe) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [2360c35ac1](https://linux-hardware.org/?probe=2360c35ac1) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [5cb9487776](https://linux-hardware.org/?probe=5cb9487776) | Jul 20, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [85df5dd7a2](https://linux-hardware.org/?probe=85df5dd7a2) | Jul 19, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a5082efd70](https://linux-hardware.org/?probe=a5082efd70) | Jul 19, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [54e7b50fc7](https://linux-hardware.org/?probe=54e7b50fc7) | Jul 18, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [870cda5796](https://linux-hardware.org/?probe=870cda5796) | Jul 17, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [662e59e904](https://linux-hardware.org/?probe=662e59e904) | Jul 17, 2022 |
| Alienware     | x17 R1                      | Notebook    | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [713765e224](https://linux-hardware.org/?probe=713765e224) | Jul 16, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [950542a4a3](https://linux-hardware.org/?probe=950542a4a3) | Jul 16, 2022 |
| HP            | 802E                        | Desktop     | [c86ddd647b](https://linux-hardware.org/?probe=c86ddd647b) | Jul 16, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | Notebook    | [5fd8a1dcf4](https://linux-hardware.org/?probe=5fd8a1dcf4) | Jul 15, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f655a34cc1](https://linux-hardware.org/?probe=f655a34cc1) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [de83d4ef43](https://linux-hardware.org/?probe=de83d4ef43) | Jul 15, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [a27d53815e](https://linux-hardware.org/?probe=a27d53815e) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [01e6c30eff](https://linux-hardware.org/?probe=01e6c30eff) | Jul 15, 2022 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [73be4f7864](https://linux-hardware.org/?probe=73be4f7864) | Jul 14, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [2418745195](https://linux-hardware.org/?probe=2418745195) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | Notebook    | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Dell          | 0W2F8G A01                  | Desktop     | [77f2181e08](https://linux-hardware.org/?probe=77f2181e08) | Jul 13, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [ff67056edc](https://linux-hardware.org/?probe=ff67056edc) | Jul 13, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [29602ec66f](https://linux-hardware.org/?probe=29602ec66f) | Jul 13, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [0c70241041](https://linux-hardware.org/?probe=0c70241041) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [4126a95603](https://linux-hardware.org/?probe=4126a95603) | Jul 13, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [0ce6078768](https://linux-hardware.org/?probe=0ce6078768) | Jul 12, 2022 |
| Unknown       | Unknown                     | Soc         | [d3742575fd](https://linux-hardware.org/?probe=d3742575fd) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| MSI           | X99S GAMING 9 AC            | Desktop     | [5f682aadd5](https://linux-hardware.org/?probe=5f682aadd5) | Jul 12, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [4929b942aa](https://linux-hardware.org/?probe=4929b942aa) | Jul 12, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [07a37c99cb](https://linux-hardware.org/?probe=07a37c99cb) | Jul 11, 2022 |
| Acer          | Aspire 1830T                | Notebook    | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [cdf7b9a4d1](https://linux-hardware.org/?probe=cdf7b9a4d1) | Jul 10, 2022 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [2f3e59dc30](https://linux-hardware.org/?probe=2f3e59dc30) | Jul 09, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [60d115ad0c](https://linux-hardware.org/?probe=60d115ad0c) | Jul 09, 2022 |
| ASRock        | Z77 Extreme6                | Desktop     | [fd8bd29c03](https://linux-hardware.org/?probe=fd8bd29c03) | Jul 09, 2022 |
| Acer          | Aspire Z3-710               | All in one  | [5f7d41a8ae](https://linux-hardware.org/?probe=5f7d41a8ae) | Jul 09, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [36fa61e21d](https://linux-hardware.org/?probe=36fa61e21d) | Jul 09, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [4b7c20d75e](https://linux-hardware.org/?probe=4b7c20d75e) | Jul 09, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [fb5a2ac873](https://linux-hardware.org/?probe=fb5a2ac873) | Jul 09, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [48bd0906cf](https://linux-hardware.org/?probe=48bd0906cf) | Jul 08, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [749a597089](https://linux-hardware.org/?probe=749a597089) | Jul 08, 2022 |
| Gigabyte      | B550 AORUS PRO AX           | Desktop     | [9ad45447d4](https://linux-hardware.org/?probe=9ad45447d4) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [4da61d3e61](https://linux-hardware.org/?probe=4da61d3e61) | Jul 07, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [503c38154f](https://linux-hardware.org/?probe=503c38154f) | Jul 07, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [1a2485b399](https://linux-hardware.org/?probe=1a2485b399) | Jul 06, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [ce6d3ec137](https://linux-hardware.org/?probe=ce6d3ec137) | Jul 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [e24a6dd845](https://linux-hardware.org/?probe=e24a6dd845) | Jul 05, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [d6dccd6ed7](https://linux-hardware.org/?probe=d6dccd6ed7) | Jul 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [422a12c217](https://linux-hardware.org/?probe=422a12c217) | Jul 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0cd693879d](https://linux-hardware.org/?probe=0cd693879d) | Jul 05, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [76d6073818](https://linux-hardware.org/?probe=76d6073818) | Jul 05, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [e69b07f3e9](https://linux-hardware.org/?probe=e69b07f3e9) | Jul 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [28b0984086](https://linux-hardware.org/?probe=28b0984086) | Jul 05, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [e795477a20](https://linux-hardware.org/?probe=e795477a20) | Jul 05, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [748f42be21](https://linux-hardware.org/?probe=748f42be21) | Jul 05, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [e165fd805c](https://linux-hardware.org/?probe=e165fd805c) | Jul 04, 2022 |
| HP            | 3646h                       | Desktop     | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [e99c8ae46f](https://linux-hardware.org/?probe=e99c8ae46f) | Jul 04, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [bcc3835be5](https://linux-hardware.org/?probe=bcc3835be5) | Jul 03, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [fc29bb14e9](https://linux-hardware.org/?probe=fc29bb14e9) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [5f3197f581](https://linux-hardware.org/?probe=5f3197f581) | Jul 03, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [f2a1afe8eb](https://linux-hardware.org/?probe=f2a1afe8eb) | Jul 03, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [1295c3de55](https://linux-hardware.org/?probe=1295c3de55) | Jul 03, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [dd9610011c](https://linux-hardware.org/?probe=dd9610011c) | Jul 02, 2022 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [4044d76f9b](https://linux-hardware.org/?probe=4044d76f9b) | Jul 02, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [ef2f004b52](https://linux-hardware.org/?probe=ef2f004b52) | Jul 02, 2022 |
| ASRock        | Z390 Pro4                   | Desktop     | [25bd784ca6](https://linux-hardware.org/?probe=25bd784ca6) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [9b8bb163d3](https://linux-hardware.org/?probe=9b8bb163d3) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d82f88e20c](https://linux-hardware.org/?probe=d82f88e20c) | Jul 01, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [cea6c9ea52](https://linux-hardware.org/?probe=cea6c9ea52) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3a423eae14](https://linux-hardware.org/?probe=3a423eae14) | Jun 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [af29dc9fe1](https://linux-hardware.org/?probe=af29dc9fe1) | Jun 30, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| AMI           | Intel                       | Notebook    | [2b592e2f4a](https://linux-hardware.org/?probe=2b592e2f4a) | Jun 29, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [909e3e3c2e](https://linux-hardware.org/?probe=909e3e3c2e) | Jun 29, 2022 |
| Dell          | Latitude 5430               | Notebook    | [119502eddb](https://linux-hardware.org/?probe=119502eddb) | Jun 29, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [b6cfc5d2df](https://linux-hardware.org/?probe=b6cfc5d2df) | Jun 28, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [20de16a046](https://linux-hardware.org/?probe=20de16a046) | Jun 28, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [d2034a53b8](https://linux-hardware.org/?probe=d2034a53b8) | Jun 28, 2022 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [b7e193f50c](https://linux-hardware.org/?probe=b7e193f50c) | Jun 28, 2022 |
| Dell          | G3 3500                     | Notebook    | [0df1b9607c](https://linux-hardware.org/?probe=0df1b9607c) | Jun 27, 2022 |
| Dell          | 051FJ8 A02                  | Desktop     | [5b997790f1](https://linux-hardware.org/?probe=5b997790f1) | Jun 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [b947b14fe4](https://linux-hardware.org/?probe=b947b14fe4) | Jun 27, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [d703a63932](https://linux-hardware.org/?probe=d703a63932) | Jun 26, 2022 |
| MSI           | PRO Z690-A                  | Desktop     | [34a2f4f726](https://linux-hardware.org/?probe=34a2f4f726) | Jun 26, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [2f4500ddad](https://linux-hardware.org/?probe=2f4500ddad) | Jun 26, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [bd52209b2a](https://linux-hardware.org/?probe=bd52209b2a) | Jun 24, 2022 |
| Alienware     | 14                          | Notebook    | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [015aa87271](https://linux-hardware.org/?probe=015aa87271) | Jun 24, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [e6f1068c91](https://linux-hardware.org/?probe=e6f1068c91) | Jun 24, 2022 |
| HP            | Presario CQ62               | Notebook    | [2f136051c9](https://linux-hardware.org/?probe=2f136051c9) | Jun 24, 2022 |
| HP            | Presario CQ62               | Notebook    | [9beeb6d3c2](https://linux-hardware.org/?probe=9beeb6d3c2) | Jun 23, 2022 |
| Lenovo        | ThinkPad E490s 20NG0002A... | Notebook    | [4cce05dc1c](https://linux-hardware.org/?probe=4cce05dc1c) | Jun 23, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [3656b8227f](https://linux-hardware.org/?probe=3656b8227f) | Jun 23, 2022 |
| Toshiba       | TECRA A40-D                 | Notebook    | [6307594332](https://linux-hardware.org/?probe=6307594332) | Jun 23, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [989b450d8b](https://linux-hardware.org/?probe=989b450d8b) | Jun 23, 2022 |
| Dell          | 0W2F8G A01                  | Desktop     | [4610c38358](https://linux-hardware.org/?probe=4610c38358) | Jun 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ae30cadddf](https://linux-hardware.org/?probe=ae30cadddf) | Jun 22, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [b65a5020db](https://linux-hardware.org/?probe=b65a5020db) | Jun 22, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [bc159b637c](https://linux-hardware.org/?probe=bc159b637c) | Jun 22, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d5098cc011](https://linux-hardware.org/?probe=d5098cc011) | Jun 22, 2022 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [20cf9d2706](https://linux-hardware.org/?probe=20cf9d2706) | Jun 21, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [30d0a46d81](https://linux-hardware.org/?probe=30d0a46d81) | Jun 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ecc6e0f4ef](https://linux-hardware.org/?probe=ecc6e0f4ef) | Jun 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [f013ebb91b](https://linux-hardware.org/?probe=f013ebb91b) | Jun 20, 2022 |
| Acer          | Iconia                      | Notebook    | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [b3da04a3af](https://linux-hardware.org/?probe=b3da04a3af) | Jun 20, 2022 |
| Framework     | Laptop                      | Notebook    | [f5ece7ce85](https://linux-hardware.org/?probe=f5ece7ce85) | Jun 19, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [a59676f7be](https://linux-hardware.org/?probe=a59676f7be) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [66d09f029f](https://linux-hardware.org/?probe=66d09f029f) | Jun 18, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [dfed0867e1](https://linux-hardware.org/?probe=dfed0867e1) | Jun 17, 2022 |
| Dell          | Precision 5540              | Notebook    | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [0d4c3d0c10](https://linux-hardware.org/?probe=0d4c3d0c10) | Jun 17, 2022 |
| Acer          | Aspire TC-230               | Desktop     | [ac205eb1ec](https://linux-hardware.org/?probe=ac205eb1ec) | Jun 17, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [9b162f339b](https://linux-hardware.org/?probe=9b162f339b) | Jun 16, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [17e9f5a71f](https://linux-hardware.org/?probe=17e9f5a71f) | Jun 16, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [527aea0d6e](https://linux-hardware.org/?probe=527aea0d6e) | Jun 16, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [4c97b8cc3a](https://linux-hardware.org/?probe=4c97b8cc3a) | Jun 16, 2022 |
| Alienware     | m15 R7                      | Notebook    | [9775a12e11](https://linux-hardware.org/?probe=9775a12e11) | Jun 16, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [bb631825e3](https://linux-hardware.org/?probe=bb631825e3) | Jun 15, 2022 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [57ad2e9147](https://linux-hardware.org/?probe=57ad2e9147) | Jun 15, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [8ded20d82b](https://linux-hardware.org/?probe=8ded20d82b) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [cc88cec642](https://linux-hardware.org/?probe=cc88cec642) | Jun 14, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bd16d5829c](https://linux-hardware.org/?probe=bd16d5829c) | Jun 14, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [848f1d55c8](https://linux-hardware.org/?probe=848f1d55c8) | Jun 14, 2022 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [aca5883c17](https://linux-hardware.org/?probe=aca5883c17) | Jun 14, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [fb157585e5](https://linux-hardware.org/?probe=fb157585e5) | Jun 14, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [57b90afcda](https://linux-hardware.org/?probe=57b90afcda) | Jun 14, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [8bb84d5aaf](https://linux-hardware.org/?probe=8bb84d5aaf) | Jun 14, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f9e74fdcd3](https://linux-hardware.org/?probe=f9e74fdcd3) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [94abe2c8af](https://linux-hardware.org/?probe=94abe2c8af) | Jun 13, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [0c6a9f5dff](https://linux-hardware.org/?probe=0c6a9f5dff) | Jun 13, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [aeec9e715d](https://linux-hardware.org/?probe=aeec9e715d) | Jun 13, 2022 |
| Dell          | Vostro 1500                 | Notebook    | [748a8a831b](https://linux-hardware.org/?probe=748a8a831b) | Jun 12, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [db209b6bf1](https://linux-hardware.org/?probe=db209b6bf1) | Jun 12, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0c0715a9b2](https://linux-hardware.org/?probe=0c0715a9b2) | Jun 12, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [1e3a9647e9](https://linux-hardware.org/?probe=1e3a9647e9) | Jun 12, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [23fa842567](https://linux-hardware.org/?probe=23fa842567) | Jun 11, 2022 |
| HP            | Compaq 6730b                | Notebook    | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [576fc8e8ed](https://linux-hardware.org/?probe=576fc8e8ed) | Jun 11, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [fd1478145b](https://linux-hardware.org/?probe=fd1478145b) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | Desktop     | [a4277bcba9](https://linux-hardware.org/?probe=a4277bcba9) | Jun 11, 2022 |
| ASUSTek       | TUF B360M-E GAMING          | Desktop     | [b1e492c444](https://linux-hardware.org/?probe=b1e492c444) | Jun 10, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [b771c75e31](https://linux-hardware.org/?probe=b771c75e31) | Jun 10, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [9198e2d64c](https://linux-hardware.org/?probe=9198e2d64c) | Jun 10, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [267db233fa](https://linux-hardware.org/?probe=267db233fa) | Jun 10, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [b33d07af6c](https://linux-hardware.org/?probe=b33d07af6c) | Jun 09, 2022 |
| ASUSTek       | Unknown                     | Notebook    | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| Alienware     | x17 R2                      | Notebook    | [78b867a06e](https://linux-hardware.org/?probe=78b867a06e) | Jun 08, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [75d6b8489b](https://linux-hardware.org/?probe=75d6b8489b) | Jun 08, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [2ac69cc327](https://linux-hardware.org/?probe=2ac69cc327) | Jun 08, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [9342f5c46b](https://linux-hardware.org/?probe=9342f5c46b) | Jun 08, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [fdba6d0041](https://linux-hardware.org/?probe=fdba6d0041) | Jun 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d984f403e9](https://linux-hardware.org/?probe=d984f403e9) | Jun 08, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [73e68df88c](https://linux-hardware.org/?probe=73e68df88c) | Jun 08, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [bfa4e4ff74](https://linux-hardware.org/?probe=bfa4e4ff74) | Jun 07, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [67cfa56623](https://linux-hardware.org/?probe=67cfa56623) | Jun 07, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [1dab354de2](https://linux-hardware.org/?probe=1dab354de2) | Jun 07, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | Desktop     | [1196dd3b41](https://linux-hardware.org/?probe=1196dd3b41) | Jun 06, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | Desktop     | [15efe8a0a2](https://linux-hardware.org/?probe=15efe8a0a2) | Jun 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [4ab9f94abe](https://linux-hardware.org/?probe=4ab9f94abe) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | Notebook    | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [8f496dbb19](https://linux-hardware.org/?probe=8f496dbb19) | Jun 06, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2KW1... | Notebook    | [686fcbebd3](https://linux-hardware.org/?probe=686fcbebd3) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | Notebook    | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| Acer          | Veriton N4670G              | Desktop     | [0b85f95c4c](https://linux-hardware.org/?probe=0b85f95c4c) | Jun 05, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3b4483236d](https://linux-hardware.org/?probe=3b4483236d) | Jun 05, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [9207d2f2d8](https://linux-hardware.org/?probe=9207d2f2d8) | Jun 04, 2022 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [a77acb5d89](https://linux-hardware.org/?probe=a77acb5d89) | Jun 04, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [57e7433cc5](https://linux-hardware.org/?probe=57e7433cc5) | Jun 04, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4bbee9909a](https://linux-hardware.org/?probe=4bbee9909a) | Jun 04, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [f770ece55b](https://linux-hardware.org/?probe=f770ece55b) | Jun 03, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [24c8a035ac](https://linux-hardware.org/?probe=24c8a035ac) | Jun 03, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [b5bb3c0725](https://linux-hardware.org/?probe=b5bb3c0725) | Jun 02, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| Dell          | G15 5515                    | Notebook    | [24ddbd70dc](https://linux-hardware.org/?probe=24ddbd70dc) | Jun 02, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0ddfd77617](https://linux-hardware.org/?probe=0ddfd77617) | Jun 02, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [878274dbce](https://linux-hardware.org/?probe=878274dbce) | Jun 02, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [b63e54900e](https://linux-hardware.org/?probe=b63e54900e) | Jun 02, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9cbdc3f892](https://linux-hardware.org/?probe=9cbdc3f892) | Jun 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ae39e96b1a](https://linux-hardware.org/?probe=ae39e96b1a) | Jun 01, 2022 |
| Alienware     | 0XJKKD A00                  | Desktop     | [ae3a750f2e](https://linux-hardware.org/?probe=ae3a750f2e) | Jun 01, 2022 |
| HP            | 1632                        | Desktop     | [4f7993cf34](https://linux-hardware.org/?probe=4f7993cf34) | Jun 01, 2022 |
| HP            | 1632                        | Desktop     | [9e69c11025](https://linux-hardware.org/?probe=9e69c11025) | Jun 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | Notebook    | [57f540db26](https://linux-hardware.org/?probe=57f540db26) | Jun 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [20de61bf9f](https://linux-hardware.org/?probe=20de61bf9f) | Jun 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0faa61f3a9](https://linux-hardware.org/?probe=0faa61f3a9) | May 31, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [9f5906337b](https://linux-hardware.org/?probe=9f5906337b) | May 31, 2022 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [ec75dd8324](https://linux-hardware.org/?probe=ec75dd8324) | May 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| IT Channel... | PA70Hx                      | Notebook    | [091ad22c2d](https://linux-hardware.org/?probe=091ad22c2d) | May 30, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [33ac99c04e](https://linux-hardware.org/?probe=33ac99c04e) | May 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [3bb74db496](https://linux-hardware.org/?probe=3bb74db496) | May 30, 2022 |
| Dell          | 0C522T A03                  | Desktop     | [b1323f0c11](https://linux-hardware.org/?probe=b1323f0c11) | May 29, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [96cd8abf05](https://linux-hardware.org/?probe=96cd8abf05) | May 29, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [9c69f7b836](https://linux-hardware.org/?probe=9c69f7b836) | May 29, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [6fe2c4a416](https://linux-hardware.org/?probe=6fe2c4a416) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [43144c3166](https://linux-hardware.org/?probe=43144c3166) | May 28, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [b810bd52cc](https://linux-hardware.org/?probe=b810bd52cc) | May 28, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [719fe6db76](https://linux-hardware.org/?probe=719fe6db76) | May 28, 2022 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [31f246f96e](https://linux-hardware.org/?probe=31f246f96e) | May 27, 2022 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [1d381d6ec9](https://linux-hardware.org/?probe=1d381d6ec9) | May 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6e7b6eddea](https://linux-hardware.org/?probe=6e7b6eddea) | May 27, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [37d87b9245](https://linux-hardware.org/?probe=37d87b9245) | May 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3302c5de16](https://linux-hardware.org/?probe=3302c5de16) | May 27, 2022 |
| HP            | 0AECh D                     | Desktop     | [ee3f56c60e](https://linux-hardware.org/?probe=ee3f56c60e) | May 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9011cf0a9b](https://linux-hardware.org/?probe=9011cf0a9b) | May 27, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ac41fb756c](https://linux-hardware.org/?probe=ac41fb756c) | May 26, 2022 |
| Acer          | Seawolf                     | Desktop     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| Toshiba       | Satellite P850              | Notebook    | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [18427eddde](https://linux-hardware.org/?probe=18427eddde) | May 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4738560555](https://linux-hardware.org/?probe=4738560555) | May 25, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [89927eb8f5](https://linux-hardware.org/?probe=89927eb8f5) | May 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [6e45ae9f7c](https://linux-hardware.org/?probe=6e45ae9f7c) | May 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [00baf8a2ff](https://linux-hardware.org/?probe=00baf8a2ff) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [32f7f3aa4b](https://linux-hardware.org/?probe=32f7f3aa4b) | May 24, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [4ea6883bee](https://linux-hardware.org/?probe=4ea6883bee) | May 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [43a374c1d4](https://linux-hardware.org/?probe=43a374c1d4) | May 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [293712cc51](https://linux-hardware.org/?probe=293712cc51) | May 23, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [40d33cea3f](https://linux-hardware.org/?probe=40d33cea3f) | May 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [1d8684d1f5](https://linux-hardware.org/?probe=1d8684d1f5) | May 23, 2022 |
| Gigabyte      | P34V5                       | Notebook    | [6fa844b91e](https://linux-hardware.org/?probe=6fa844b91e) | May 23, 2022 |
| Gigabyte      | P34V5                       | Notebook    | [3ad8e4b239](https://linux-hardware.org/?probe=3ad8e4b239) | May 23, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [192f2ac212](https://linux-hardware.org/?probe=192f2ac212) | May 23, 2022 |
| Toshiba       | TECRA R850                  | Notebook    | [aa0bfd6c6a](https://linux-hardware.org/?probe=aa0bfd6c6a) | May 22, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [0ea1ce7372](https://linux-hardware.org/?probe=0ea1ce7372) | May 22, 2022 |
| Dell          | G3 3500                     | Notebook    | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [eaf9e6332b](https://linux-hardware.org/?probe=eaf9e6332b) | May 21, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [890010e793](https://linux-hardware.org/?probe=890010e793) | May 21, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [81360dffcc](https://linux-hardware.org/?probe=81360dffcc) | May 21, 2022 |
| HP            | 0A08h                       | Desktop     | [86c65b6b1f](https://linux-hardware.org/?probe=86c65b6b1f) | May 21, 2022 |
| HP            | 0A08h                       | Desktop     | [18b2ce1297](https://linux-hardware.org/?probe=18b2ce1297) | May 21, 2022 |
| Unknown       | Unknown                     | Soc         | [3028420085](https://linux-hardware.org/?probe=3028420085) | May 20, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [acbead429c](https://linux-hardware.org/?probe=acbead429c) | May 20, 2022 |
| HP            | 8053                        | Desktop     | [53c0148d64](https://linux-hardware.org/?probe=53c0148d64) | May 20, 2022 |
| ECS           | P67H2-A3                    | Desktop     | [2bc21b9c81](https://linux-hardware.org/?probe=2bc21b9c81) | May 20, 2022 |
| HP            | 8381 1000                   | All in one  | [04684aee01](https://linux-hardware.org/?probe=04684aee01) | May 19, 2022 |
| HP            | 8381 1000                   | All in one  | [57e63582bf](https://linux-hardware.org/?probe=57e63582bf) | May 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [d94f4b0a43](https://linux-hardware.org/?probe=d94f4b0a43) | May 19, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | Notebook    | [5d150789cb](https://linux-hardware.org/?probe=5d150789cb) | May 19, 2022 |
| Dell          | Inspiron 7572               | Notebook    | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [c3438d922b](https://linux-hardware.org/?probe=c3438d922b) | May 19, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [98752f9fb4](https://linux-hardware.org/?probe=98752f9fb4) | May 18, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [c01f14c77f](https://linux-hardware.org/?probe=c01f14c77f) | May 18, 2022 |
| Dell          | Latitude E7450              | Notebook    | [26b07c8dfc](https://linux-hardware.org/?probe=26b07c8dfc) | May 18, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [2f7a99c28b](https://linux-hardware.org/?probe=2f7a99c28b) | May 17, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [5927aac0b7](https://linux-hardware.org/?probe=5927aac0b7) | May 17, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [ee4e4a7bc7](https://linux-hardware.org/?probe=ee4e4a7bc7) | May 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d4f9f894b6](https://linux-hardware.org/?probe=d4f9f894b6) | May 16, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [faf97fa9a0](https://linux-hardware.org/?probe=faf97fa9a0) | May 16, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [c831b3937a](https://linux-hardware.org/?probe=c831b3937a) | May 16, 2022 |
| Gigabyte      | MQLP7AP-00                  | Desktop     | [3c99b8d861](https://linux-hardware.org/?probe=3c99b8d861) | May 16, 2022 |
| Gigabyte      | A7 K1                       | Notebook    | [9cd1ec32e4](https://linux-hardware.org/?probe=9cd1ec32e4) | May 16, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [a58685906f](https://linux-hardware.org/?probe=a58685906f) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [9161d40357](https://linux-hardware.org/?probe=9161d40357) | May 14, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [e34d9464b2](https://linux-hardware.org/?probe=e34d9464b2) | May 14, 2022 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [45a26a9322](https://linux-hardware.org/?probe=45a26a9322) | May 14, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3a07cc7daf](https://linux-hardware.org/?probe=3a07cc7daf) | May 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [91730625e9](https://linux-hardware.org/?probe=91730625e9) | May 14, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [b31c3ee2d6](https://linux-hardware.org/?probe=b31c3ee2d6) | May 14, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [210d27dd90](https://linux-hardware.org/?probe=210d27dd90) | May 14, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [30a7bebcd3](https://linux-hardware.org/?probe=30a7bebcd3) | May 14, 2022 |
| HP            | 82B4                        | Desktop     | [3a1723a2ee](https://linux-hardware.org/?probe=3a1723a2ee) | May 13, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [78c64b498b](https://linux-hardware.org/?probe=78c64b498b) | May 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [6251446c92](https://linux-hardware.org/?probe=6251446c92) | May 13, 2022 |
| Intel         | DH67BL AAG10189-210         | Desktop     | [2340d530cd](https://linux-hardware.org/?probe=2340d530cd) | May 13, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [fca86a854a](https://linux-hardware.org/?probe=fca86a854a) | May 13, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [602289ad13](https://linux-hardware.org/?probe=602289ad13) | May 13, 2022 |
| Dell          | Inspiron 15 3515            | Notebook    | [dd8e112250](https://linux-hardware.org/?probe=dd8e112250) | May 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [05b277774e](https://linux-hardware.org/?probe=05b277774e) | May 12, 2022 |
| HP            | 8526 MVB, A                 | Desktop     | [50b2aa8de2](https://linux-hardware.org/?probe=50b2aa8de2) | May 12, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [d2b843c446](https://linux-hardware.org/?probe=d2b843c446) | May 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5662b515c3](https://linux-hardware.org/?probe=5662b515c3) | May 12, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Acer          | Aspire X3990                | Desktop     | [c6753ff37f](https://linux-hardware.org/?probe=c6753ff37f) | May 11, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | Notebook    | [a22c347eaf](https://linux-hardware.org/?probe=a22c347eaf) | May 11, 2022 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [9797dc24f1](https://linux-hardware.org/?probe=9797dc24f1) | May 11, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [f2f010a36d](https://linux-hardware.org/?probe=f2f010a36d) | May 11, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [0d9616886e](https://linux-hardware.org/?probe=0d9616886e) | May 11, 2022 |
| MSI           | H97M-E35                    | Desktop     | [fdd0f51b46](https://linux-hardware.org/?probe=fdd0f51b46) | May 10, 2022 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [ffc3d3cf27](https://linux-hardware.org/?probe=ffc3d3cf27) | May 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [ce3addb8a4](https://linux-hardware.org/?probe=ce3addb8a4) | May 10, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [7d146e5dec](https://linux-hardware.org/?probe=7d146e5dec) | May 10, 2022 |
| ASRock        | H87M                        | Desktop     | [9c031f1e71](https://linux-hardware.org/?probe=9c031f1e71) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [89f0b017b1](https://linux-hardware.org/?probe=89f0b017b1) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [bd7335e1cd](https://linux-hardware.org/?probe=bd7335e1cd) | May 09, 2022 |
| Acer          | Aspire XC-603               | Desktop     | [3d806cb212](https://linux-hardware.org/?probe=3d806cb212) | May 08, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [7ff6997105](https://linux-hardware.org/?probe=7ff6997105) | May 08, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [0d213120b4](https://linux-hardware.org/?probe=0d213120b4) | May 08, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d27bd494e](https://linux-hardware.org/?probe=9d27bd494e) | May 08, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [e4340f1707](https://linux-hardware.org/?probe=e4340f1707) | May 07, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [3d921b618b](https://linux-hardware.org/?probe=3d921b618b) | May 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [5c5f2f2b5c](https://linux-hardware.org/?probe=5c5f2f2b5c) | May 07, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [79c87fe48c](https://linux-hardware.org/?probe=79c87fe48c) | May 07, 2022 |
| MSI           | C236A WORKSTATION           | Desktop     | [57d0654584](https://linux-hardware.org/?probe=57d0654584) | May 06, 2022 |
| HP            | Folio 13 - 2000             | Notebook    | [e859aed666](https://linux-hardware.org/?probe=e859aed666) | May 06, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [c44c5e8931](https://linux-hardware.org/?probe=c44c5e8931) | May 06, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [f99b5cee66](https://linux-hardware.org/?probe=f99b5cee66) | May 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [3d07e8a45e](https://linux-hardware.org/?probe=3d07e8a45e) | May 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [46adc67882](https://linux-hardware.org/?probe=46adc67882) | May 05, 2022 |
| Dell          | Studio 1555                 | Notebook    | [c02949a388](https://linux-hardware.org/?probe=c02949a388) | May 05, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [3ed5a6d961](https://linux-hardware.org/?probe=3ed5a6d961) | May 04, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [2b6338d755](https://linux-hardware.org/?probe=2b6338d755) | May 04, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [ba7fe58d02](https://linux-hardware.org/?probe=ba7fe58d02) | May 03, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | Notebook    | [43dcfa4094](https://linux-hardware.org/?probe=43dcfa4094) | May 03, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [f05a6e7d31](https://linux-hardware.org/?probe=f05a6e7d31) | May 03, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [9645231d87](https://linux-hardware.org/?probe=9645231d87) | May 03, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [c6da7b776e](https://linux-hardware.org/?probe=c6da7b776e) | May 03, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1d6bcd7320](https://linux-hardware.org/?probe=1d6bcd7320) | May 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [8e220517f5](https://linux-hardware.org/?probe=8e220517f5) | May 02, 2022 |
| Framework     | Laptop                      | Notebook    | [0d35134041](https://linux-hardware.org/?probe=0d35134041) | May 02, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [0e6717d54b](https://linux-hardware.org/?probe=0e6717d54b) | May 02, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [579cadce96](https://linux-hardware.org/?probe=579cadce96) | May 02, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [42067d196a](https://linux-hardware.org/?probe=42067d196a) | May 02, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [ab86c0118b](https://linux-hardware.org/?probe=ab86c0118b) | May 02, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [6203143b59](https://linux-hardware.org/?probe=6203143b59) | May 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [7206b41211](https://linux-hardware.org/?probe=7206b41211) | May 01, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c396021a33](https://linux-hardware.org/?probe=c396021a33) | May 01, 2022 |
| Lenovo        | Legion Y9000X 2020 81TH     | Notebook    | [c335cbb270](https://linux-hardware.org/?probe=c335cbb270) | May 01, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [faa7213f5c](https://linux-hardware.org/?probe=faa7213f5c) | Apr 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [8826e1d451](https://linux-hardware.org/?probe=8826e1d451) | Apr 30, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [f948921cba](https://linux-hardware.org/?probe=f948921cba) | Apr 30, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [71fee7e383](https://linux-hardware.org/?probe=71fee7e383) | Apr 29, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [6755ed2aa6](https://linux-hardware.org/?probe=6755ed2aa6) | Apr 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [64cb392628](https://linux-hardware.org/?probe=64cb392628) | Apr 28, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [1f26415f58](https://linux-hardware.org/?probe=1f26415f58) | Apr 28, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [6165b0554d](https://linux-hardware.org/?probe=6165b0554d) | Apr 28, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [910da71dd2](https://linux-hardware.org/?probe=910da71dd2) | Apr 28, 2022 |
| ASUSTek       | VANGUARD B85                | Desktop     | [d591002039](https://linux-hardware.org/?probe=d591002039) | Apr 27, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [77c2b99e9b](https://linux-hardware.org/?probe=77c2b99e9b) | Apr 27, 2022 |
| Lenovo        | ThinkPad X250 20CLS52P0F    | Notebook    | [a4d291ccda](https://linux-hardware.org/?probe=a4d291ccda) | Apr 27, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [3a96bf8237](https://linux-hardware.org/?probe=3a96bf8237) | Apr 27, 2022 |
| Unknown       | Unknown                     | Soc         | [5937b60f18](https://linux-hardware.org/?probe=5937b60f18) | Apr 26, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [e06fd46729](https://linux-hardware.org/?probe=e06fd46729) | Apr 26, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [93c883ef59](https://linux-hardware.org/?probe=93c883ef59) | Apr 26, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [205ae74d07](https://linux-hardware.org/?probe=205ae74d07) | Apr 26, 2022 |
| HP            | ProBook 4710s               | Notebook    | [03d5c4c5b2](https://linux-hardware.org/?probe=03d5c4c5b2) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [981d5e03b3](https://linux-hardware.org/?probe=981d5e03b3) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b3a1039fb](https://linux-hardware.org/?probe=0b3a1039fb) | Apr 25, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [973e161bd9](https://linux-hardware.org/?probe=973e161bd9) | Apr 25, 2022 |
| HP            | 0AACh                       | Desktop     | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b1b4ea439d](https://linux-hardware.org/?probe=b1b4ea439d) | Apr 25, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [e0def5bddc](https://linux-hardware.org/?probe=e0def5bddc) | Apr 25, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [f0aea29124](https://linux-hardware.org/?probe=f0aea29124) | Apr 25, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a771d771b2](https://linux-hardware.org/?probe=a771d771b2) | Apr 24, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [1a195527a4](https://linux-hardware.org/?probe=1a195527a4) | Apr 24, 2022 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [d076b5c763](https://linux-hardware.org/?probe=d076b5c763) | Apr 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| Dell          | Latitude E5500              | Notebook    | [c954cb4ba4](https://linux-hardware.org/?probe=c954cb4ba4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | Notebook    | [ab88dc2482](https://linux-hardware.org/?probe=ab88dc2482) | Apr 24, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [e686789a94](https://linux-hardware.org/?probe=e686789a94) | Apr 24, 2022 |
| ASRock        | B85M Pro3                   | Desktop     | [551ea1b91f](https://linux-hardware.org/?probe=551ea1b91f) | Apr 23, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [2da43c32a4](https://linux-hardware.org/?probe=2da43c32a4) | Apr 23, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [8ff97fd246](https://linux-hardware.org/?probe=8ff97fd246) | Apr 23, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [bfaeba4483](https://linux-hardware.org/?probe=bfaeba4483) | Apr 22, 2022 |
| Dell          | Latitude 7490               | Notebook    | [2b8d24f8ae](https://linux-hardware.org/?probe=2b8d24f8ae) | Apr 22, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [a68c57ea30](https://linux-hardware.org/?probe=a68c57ea30) | Apr 22, 2022 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [e8e0b5fd5d](https://linux-hardware.org/?probe=e8e0b5fd5d) | Apr 22, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [c32d394b3a](https://linux-hardware.org/?probe=c32d394b3a) | Apr 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 421       | 13.99%  |
| Ubuntu 18.04      | 173       | 5.75%   |
| Ubuntu 22.04      | 82        | 2.73%   |
| Debian 11         | 78        | 2.59%   |
| OpenMandriva 4.3  | 70        | 2.33%   |
| KDE neon 20.04    | 70        | 2.33%   |
| Pop!_OS 21.04     | 64        | 2.13%   |
| Fedora 36         | 64        | 2.13%   |
| Linux Mint 20.3   | 62        | 2.06%   |
| OpenMandriva 4.2  | 56        | 1.86%   |
| Zorin 16          | 54        | 1.79%   |
| Pop!_OS 22.04     | 54        | 1.79%   |
| Pop!_OS 20.04     | 50        | 1.66%   |
| Arch Rolling      | 49        | 1.63%   |
| Pop!_OS 20.10     | 48        | 1.6%    |
| Ubuntu 21.10      | 46        | 1.53%   |
| Linux Mint 20.2   | 46        | 1.53%   |
| Arch              | 44        | 1.46%   |
| Linux Mint 20.1   | 42        | 1.4%    |
| Fedora 35         | 42        | 1.4%    |
| Ubuntu 19.04      | 41        | 1.36%   |
| Fedora 33         | 41        | 1.36%   |
| Ubuntu 20.10      | 39        | 1.3%    |
| Manjaro           | 39        | 1.3%    |
| Fedora 34         | 38        | 1.26%   |
| Ubuntu 21.04      | 37        | 1.23%   |
| Ubuntu 19.10      | 37        | 1.23%   |
| Linux Mint 19.3   | 34        | 1.13%   |
| Linux Mint 20     | 32        | 1.06%   |
| ArcoLinux Rolling | 31        | 1.03%   |
| Pop!_OS 21.10     | 30        | 1%      |
| Xubuntu 20.04     | 29        | 0.96%   |
| Fedora 32         | 29        | 0.96%   |
| Xubuntu 18.04     | 28        | 0.93%   |
| Ubuntu 18.10      | 26        | 0.86%   |
| Linux Mint 21     | 26        | 0.86%   |
| Zorin 15          | 24        | 0.8%    |
| Fedora 37         | 23        | 0.76%   |
| ClearOS 7         | 23        | 0.76%   |
| Debian 10         | 21        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 877       | 31.12%  |
| Linux Mint    | 257       | 9.12%   |
| Pop!_OS       | 233       | 8.27%   |
| Fedora        | 216       | 7.67%   |
| OpenMandriva  | 146       | 5.18%   |
| Debian        | 128       | 4.54%   |
| Arch          | 93        | 3.3%    |
| Zorin         | 87        | 3.09%   |
| Manjaro       | 87        | 3.09%   |
| KDE neon      | 84        | 2.98%   |
| Xubuntu       | 77        | 2.73%   |
| Kubuntu       | 62        | 2.2%    |
| Elementary    | 32        | 1.14%   |
| ArcoLinux     | 32        | 1.14%   |
| Gentoo        | 29        | 1.03%   |
| ROSA          | 28        | 0.99%   |
| Kali          | 26        | 0.92%   |
| Ubuntu MATE   | 23        | 0.82%   |
| ClearOS       | 23        | 0.82%   |
| Clear Linux   | 22        | 0.78%   |
| openSUSE      | 21        | 0.75%   |
| Lubuntu       | 19        | 0.67%   |
| Endless       | 17        | 0.6%    |
| BlackPanther  | 17        | 0.6%    |
| EndeavourOS   | 14        | 0.5%    |
| Ubuntu Unity  | 13        | 0.46%   |
| LMDE          | 12        | 0.43%   |
| CentOS        | 10        | 0.35%   |
| Ubuntu Budgie | 9         | 0.32%   |
| MX            | 9         | 0.32%   |
| Raspbian      | 8         | 0.28%   |
| Parrot        | 8         | 0.28%   |
| LinuxFX       | 7         | 0.25%   |
| Feren OS      | 7         | 0.25%   |
| Rocky Linux   | 6         | 0.21%   |
| Reborn OS     | 6         | 0.21%   |
| Solus         | 5         | 0.18%   |
| Manjaro-ARM   | 5         | 0.18%   |
| Garuda Linux  | 5         | 0.18%   |
| SteamOS       | 4         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 67        | 1.92%   |
| 5.4.0-42-generic         | 64        | 1.83%   |
| 5.10.14-desktop-1omv4002 | 52        | 1.49%   |
| 5.4.0-40-generic         | 30        | 0.86%   |
| 5.11.0-7620-generic      | 30        | 0.86%   |
| 5.4.0-58-generic         | 29        | 0.83%   |
| 5.4.0-48-generic         | 27        | 0.77%   |
| 5.4.0-26-generic         | 24        | 0.69%   |
| 5.3.0-46-generic         | 24        | 0.69%   |
| 5.15.0-52-generic        | 24        | 0.69%   |
| 5.4.0-52-generic         | 23        | 0.66%   |
| 5.11.0-37-generic        | 23        | 0.66%   |
| 5.4.0-29-generic         | 22        | 0.63%   |
| 5.3.0-40-generic         | 22        | 0.63%   |
| 5.3.0-28-generic         | 22        | 0.63%   |
| 5.17.5-76051705-generic  | 21        | 0.6%    |
| 5.15.0-48-generic        | 21        | 0.6%    |
| 5.11.0-27-generic        | 20        | 0.57%   |
| 5.4.0-7634-generic       | 19        | 0.54%   |
| 5.4.0-47-generic         | 18        | 0.52%   |
| 5.15.0-46-generic        | 18        | 0.52%   |
| 5.4.0-74-generic         | 17        | 0.49%   |
| 5.13.0-7620-generic      | 17        | 0.49%   |
| 5.8.0-7630-generic       | 16        | 0.46%   |
| 5.8.0-44-generic         | 16        | 0.46%   |
| 5.4.0-91-generic         | 16        | 0.46%   |
| 5.4.0-65-generic         | 16        | 0.46%   |
| 5.13.0-40-generic        | 16        | 0.46%   |
| 4.15.0-99-generic        | 16        | 0.46%   |
| 5.8.0-7642-generic       | 15        | 0.43%   |
| 5.8.0-63-generic         | 15        | 0.43%   |
| 5.4.0-66-generic         | 15        | 0.43%   |
| 5.4.0-54-generic         | 15        | 0.43%   |
| 5.15.0-56-generic        | 15        | 0.43%   |
| 5.15.0-41-generic        | 15        | 0.43%   |
| 5.8.0-55-generic         | 14        | 0.4%    |
| 5.8.0-50-generic         | 14        | 0.4%    |
| 5.4.0-7642-generic       | 14        | 0.4%    |
| 5.15.0-43-generic        | 14        | 0.4%    |
| 5.13.0-39-generic        | 14        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 551       | 17.14%  |
| 5.11.0  | 228       | 7.09%   |
| 5.13.0  | 183       | 5.69%   |
| 5.8.0   | 181       | 5.63%   |
| 5.15.0  | 181       | 5.63%   |
| 4.15.0  | 160       | 4.98%   |
| 5.3.0   | 128       | 3.98%   |
| 5.0.0   | 86        | 2.67%   |
| 5.10.0  | 77        | 2.4%    |
| 5.16.7  | 68        | 2.12%   |
| 4.18.0  | 62        | 1.93%   |
| 5.10.14 | 52        | 1.62%   |
| 4.19.0  | 35        | 1.09%   |
| 5.19.0  | 33        | 1.03%   |
| 5.17.5  | 31        | 0.96%   |
| 3.10.0  | 29        | 0.9%    |
| 5.18.0  | 14        | 0.44%   |
| 5.16.11 | 14        | 0.44%   |
| 5.18.10 | 13        | 0.4%    |
| 5.16.0  | 13        | 0.4%    |
| 6.0.0   | 12        | 0.37%   |
| 5.14.0  | 12        | 0.37%   |
| 4.4.0   | 12        | 0.37%   |
| 5.17.0  | 11        | 0.34%   |
| 6.0.7   | 10        | 0.31%   |
| 5.9.16  | 10        | 0.31%   |
| 5.6.14  | 10        | 0.31%   |
| 5.18.12 | 10        | 0.31%   |
| 5.15.11 | 10        | 0.31%   |
| 5.13.13 | 10        | 0.31%   |
| 5.11.12 | 10        | 0.31%   |
| 4.9.60  | 10        | 0.31%   |
| 4.18.16 | 10        | 0.31%   |
| 5.19.16 | 9         | 0.28%   |
| 5.16.19 | 9         | 0.28%   |
| 5.13.12 | 9         | 0.28%   |
| 5.12.4  | 9         | 0.28%   |
| 6.0.9   | 8         | 0.25%   |
| 6.0.8   | 8         | 0.25%   |
| 6.0.6   | 8         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 602       | 19.28%  |
| 5.15    | 277       | 8.87%   |
| 5.11    | 267       | 8.55%   |
| 5.13    | 229       | 7.33%   |
| 5.8     | 228       | 7.3%    |
| 5.10    | 190       | 6.08%   |
| 4.15    | 160       | 5.12%   |
| 5.16    | 149       | 4.77%   |
| 5.3     | 143       | 4.58%   |
| 5.0     | 95        | 3.04%   |
| 5.17    | 83        | 2.66%   |
| 5.19    | 79        | 2.53%   |
| 5.18    | 79        | 2.53%   |
| 4.18    | 74        | 2.37%   |
| 6.0     | 70        | 2.24%   |
| 5.12    | 46        | 1.47%   |
| 5.6     | 45        | 1.44%   |
| 4.19    | 45        | 1.44%   |
| 5.14    | 43        | 1.38%   |
| 5.9     | 38        | 1.22%   |
| 4.9     | 30        | 0.96%   |
| 3.10    | 29        | 0.93%   |
| 5.5     | 26        | 0.83%   |
| 5.7     | 25        | 0.8%    |
| 5.2     | 17        | 0.54%   |
| 4.4     | 13        | 0.42%   |
| 5.1     | 9         | 0.29%   |
| 6.1     | 8         | 0.26%   |
| 4.1     | 4         | 0.13%   |
| 4.20    | 3         | 0.1%    |
| 4.14    | 3         | 0.1%    |
| 4.13    | 3         | 0.1%    |
| 3.16    | 2         | 0.06%   |
| 6.2     | 1         | 0.03%   |
| 5       | 1         | 0.03%   |
| 4.8     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.16    | 1         | 0.03%   |
| 4.11    | 1         | 0.03%   |
| 4.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2595      | 96.61%  |
| i686    | 47        | 1.75%   |
| aarch64 | 28        | 1.04%   |
| armv7l  | 12        | 0.45%   |
| i586    | 2         | 0.07%   |
| riscv64 | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1238      | 43.5%   |
| KDE5            | 409       | 14.37%  |
| Unknown         | 375       | 13.18%  |
| X-Cinnamon      | 212       | 7.45%   |
| XFCE            | 199       | 6.99%   |
| KDE             | 100       | 3.51%   |
| MATE            | 81        | 2.85%   |
| Cinnamon        | 54        | 1.9%    |
| Pantheon        | 30        | 1.05%   |
| LXQt            | 21        | 0.74%   |
| Unity           | 18        | 0.63%   |
| KDE4            | 18        | 0.63%   |
| LXDE            | 17        | 0.6%    |
| Budgie          | 17        | 0.6%    |
| i3              | 14        | 0.49%   |
| Deepin          | 7         | 0.25%   |
| awesome         | 7         | 0.25%   |
| Openbox         | 6         | 0.21%   |
| GNOME Flashback | 4         | 0.14%   |
| GNOME Classic   | 4         | 0.14%   |
| xmonad          | 3         | 0.11%   |
| qtile           | 2         | 0.07%   |
| Trinity         | 1         | 0.04%   |
| sway            | 1         | 0.04%   |
| pop             | 1         | 0.04%   |
| Phosh:GNOME     | 1         | 0.04%   |
| LeftWM          | 1         | 0.04%   |
| icewm           | 1         | 0.04%   |
| GNUstep         | 1         | 0.04%   |
| DWM             | 1         | 0.04%   |
| dusk            | 1         | 0.04%   |
| bspwm           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2174      | 78.06%  |
| Wayland | 335       | 12.03%  |
| Unknown | 171       | 6.14%   |
| Tty     | 104       | 3.73%   |
| Web     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1570      | 56.17%  |
| SDDM    | 354       | 12.67%  |
| GDM     | 299       | 10.7%   |
| LightDM | 259       | 9.27%   |
| GDM3    | 193       | 6.91%   |
| TDM     | 85        | 3.04%   |
| KDM     | 17        | 0.61%   |
| SLiM    | 6         | 0.21%   |
| LXDM    | 5         | 0.18%   |
| XDM     | 4         | 0.14%   |
| Ly      | 2         | 0.07%   |
| GREETD  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| en_AU        | 1974      | 71.08%  |
| en_US        | 371       | 13.36%  |
| Unknown      | 319       | 11.49%  |
| C            | 64        | 2.3%    |
| en_GB        | 32        | 1.15%   |
| C.UTF8       | 6         | 0.22%   |
| zh_CN        | 2         | 0.07%   |
| de_DE        | 2         | 0.07%   |
| ru_RU        | 1         | 0.04%   |
| POSIX        | 1         | 0.04%   |
| fr_FR        | 1         | 0.04%   |
| es_ES        | 1         | 0.04%   |
| en_IN        | 1         | 0.04%   |
| en_GB.UTF-12 | 1         | 0.04%   |
| en_CA        | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1428      | 52.04%  |
| EFI  | 1316      | 47.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2096      | 76%     |
| Btrfs   | 229       | 8.3%    |
| Overlay | 187       | 6.78%   |
| Unknown | 100       | 3.63%   |
| Xfs     | 76        | 2.76%   |
| Zfs     | 43        | 1.56%   |
| Ext2    | 8         | 0.29%   |
| Tmpfs   | 5         | 0.18%   |
| Ext3    | 5         | 0.18%   |
| XXXXXXX | 4         | 0.15%   |
| F2fs    | 3         | 0.11%   |
| Jfs     | 1         | 0.04%   |
| Aufs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1633      | 59.4%   |
| GPT     | 834       | 30.34%  |
| MBR     | 282       | 10.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2321      | 84.4%   |
| Yes       | 429       | 15.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2006      | 73.13%  |
| Yes       | 737       | 26.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 388       | 14.48%  |
| Hewlett-Packard         | 354       | 13.21%  |
| Dell                    | 346       | 12.91%  |
| Gigabyte Technology     | 335       | 12.5%   |
| Lenovo                  | 281       | 10.49%  |
| MSI                     | 171       | 6.38%   |
| Acer                    | 132       | 4.93%   |
| Apple                   | 113       | 4.22%   |
| ASRock                  | 108       | 4.03%   |
| Toshiba                 | 91        | 3.4%    |
| Intel                   | 77        | 2.87%   |
| Microsoft               | 28        | 1.04%   |
| Raspberry Pi Foundation | 27        | 1.01%   |
| Alienware               | 19        | 0.71%   |
| Unknown                 | 16        | 0.6%    |
| Samsung Electronics     | 13        | 0.49%   |
| Sony                    | 10        | 0.37%   |
| Notebook                | 10        | 0.37%   |
| AMI                     | 10        | 0.37%   |
| Timi                    | 8         | 0.3%    |
| Pegatron                | 8         | 0.3%    |
| Medion                  | 7         | 0.26%   |
| IT Channel Pty          | 7         | 0.26%   |
| HUAWEI                  | 7         | 0.26%   |
| Razer                   | 6         | 0.22%   |
| Panasonic               | 6         | 0.22%   |
| Metabox                 | 6         | 0.22%   |
| IBM                     | 6         | 0.22%   |
| Google                  | 6         | 0.22%   |
| Supermicro              | 5         | 0.19%   |
| Pine Microsystems       | 5         | 0.19%   |
| Kogan                   | 5         | 0.19%   |
| ECS                     | 5         | 0.19%   |
| System76                | 4         | 0.15%   |
| Shuttle                 | 4         | 0.15%   |
| Hardkernel              | 4         | 0.15%   |
| LG Electronics          | 3         | 0.11%   |
| Intel Client Systems    | 3         | 0.11%   |
| Framework               | 3         | 0.11%   |
| Purism                  | 2         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ASUS All Series              | 29        | 1.08%   |
| Dell OptiPlex 9020           | 22        | 0.82%   |
| Unknown                      | 20        | 0.75%   |
| HP Pavilion dv6              | 14        | 0.52%   |
| HP Pavilion g6               | 11        | 0.41%   |
| RPi Raspberry Pi             | 10        | 0.37%   |
| MSI MS-7B89                  | 10        | 0.37%   |
| Gigabyte 970A-D3P            | 10        | 0.37%   |
| HP Notebook                  | 9         | 0.34%   |
| Apple iMac12,2               | 9         | 0.34%   |
| MSI MS-7817                  | 8         | 0.3%    |
| HP Pavilion 15               | 8         | 0.3%    |
| Dell OptiPlex 780            | 8         | 0.3%    |
| MSI MS-7C37                  | 7         | 0.26%   |
| Gigabyte X58A-UD3R           | 7         | 0.26%   |
| Apple MacBookPro9,2          | 7         | 0.26%   |
| MSI MS-7C84                  | 6         | 0.22%   |
| Gigabyte B75M-D3H            | 6         | 0.22%   |
| Dell OptiPlex 9010           | 6         | 0.22%   |
| Apple MacBookPro8,1          | 6         | 0.22%   |
| Apple MacBookPro10,1         | 6         | 0.22%   |
| Acer ConceptD CN315-71P      | 6         | 0.22%   |
| HP Compaq 8200 Elite SFF PC  | 5         | 0.19%   |
| Gigabyte X570 AORUS PRO WIFI | 5         | 0.19%   |
| Gigabyte GA-870A-UD3         | 5         | 0.19%   |
| Dell XPS 15 9570             | 5         | 0.19%   |
| Dell XPS 15 9560             | 5         | 0.19%   |
| Dell OptiPlex 3010           | 5         | 0.19%   |
| ASUS ROG CROSSHAIR VIII HERO | 5         | 0.19%   |
| Apple MacBookAir7,2          | 5         | 0.19%   |
| Acer Aspire 5750G            | 5         | 0.19%   |
| Toshiba Satellite P750       | 4         | 0.15%   |
| Toshiba Satellite L850       | 4         | 0.15%   |
| Toshiba Satellite L500       | 4         | 0.15%   |
| Toshiba Satellite L50-A      | 4         | 0.15%   |
| MSI MS-7C94                  | 4         | 0.15%   |
| MSI MS-7C02                  | 4         | 0.15%   |
| MSI MS-7B85                  | 4         | 0.15%   |
| MSI MS-7B79                  | 4         | 0.15%   |
| MSI MS-7A38                  | 4         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 130       | 4.85%   |
| Acer Aspire        | 91        | 3.4%    |
| Dell OptiPlex      | 82        | 3.06%   |
| HP Pavilion        | 74        | 2.76%   |
| Toshiba Satellite  | 73        | 2.72%   |
| Dell Latitude      | 69        | 2.57%   |
| Dell Inspiron      | 69        | 2.57%   |
| Dell XPS           | 54        | 2.01%   |
| ASUS PRIME         | 52        | 1.94%   |
| ASUS ROG           | 51        | 1.9%    |
| HP EliteBook       | 46        | 1.72%   |
| HP Compaq          | 39        | 1.46%   |
| Dell Precision     | 34        | 1.27%   |
| Lenovo IdeaPad     | 33        | 1.23%   |
| Lenovo ThinkCentre | 31        | 1.16%   |
| Lenovo Yoga        | 30        | 1.12%   |
| ASUS All           | 29        | 1.08%   |
| Microsoft Surface  | 28        | 1.04%   |
| RPi Raspberry      | 27        | 1.01%   |
| HP ProBook         | 26        | 0.97%   |
| ASUS TUF           | 23        | 0.86%   |
| Gigabyte X570      | 20        | 0.75%   |
| Unknown            | 20        | 0.75%   |
| HP ENVY            | 19        | 0.71%   |
| HP Laptop          | 18        | 0.67%   |
| Gigabyte B450      | 15        | 0.56%   |
| Dell Vostro        | 14        | 0.52%   |
| Gigabyte B450M     | 12        | 0.45%   |
| HP ProDesk         | 11        | 0.41%   |
| ASUS ZenBook       | 11        | 0.41%   |
| Apple iMac12       | 11        | 0.41%   |
| MSI MS-7B89        | 10        | 0.37%   |
| Gigabyte 970A-D3P  | 10        | 0.37%   |
| Toshiba PORTEGE    | 9         | 0.34%   |
| HP Spectre         | 9         | 0.34%   |
| HP Notebook        | 9         | 0.34%   |
| ASUS VivoBook      | 9         | 0.34%   |
| Apple MacBookPro10 | 9         | 0.34%   |
| Acer Swift         | 9         | 0.34%   |
| MSI MS-7817        | 8         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 260       | 9.7%    |
| 2018    | 253       | 9.44%   |
| 2020    | 223       | 8.32%   |
| 2012    | 216       | 8.06%   |
| 2013    | 209       | 7.8%    |
| 2011    | 203       | 7.57%   |
| 2017    | 193       | 7.2%    |
| 2014    | 168       | 6.27%   |
| 2016    | 153       | 5.71%   |
| 2021    | 143       | 5.34%   |
| 2015    | 140       | 5.22%   |
| 2010    | 138       | 5.15%   |
| 2009    | 111       | 4.14%   |
| 2008    | 104       | 3.88%   |
| 2007    | 50        | 1.87%   |
| 2022    | 43        | 1.6%    |
| Unknown | 39        | 1.46%   |
| 2006    | 19        | 0.71%   |
| 2005    | 11        | 0.41%   |
| 2004    | 2         | 0.07%   |
| 2003    | 1         | 0.04%   |
| 2002    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1210      | 45.15%  |
| Notebook       | 1150      | 42.91%  |
| Convertible    | 90        | 3.36%   |
| All in one     | 66        | 2.46%   |
| Mini pc        | 58        | 2.16%   |
| Tablet         | 42        | 1.57%   |
| System on chip | 34        | 1.27%   |
| Server         | 25        | 0.93%   |
| Phone          | 3         | 0.11%   |
| Stick pc       | 2         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2475      | 91.8%   |
| Enabled  | 221       | 8.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2669      | 99.59%  |
| Yes  | 11        | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 671       | 24.47%  |
| 4.01-8.0        | 553       | 20.17%  |
| 8.01-16.0       | 464       | 16.92%  |
| 3.01-4.0        | 452       | 16.48%  |
| 32.01-64.0      | 336       | 12.25%  |
| 1.01-2.0        | 94        | 3.43%   |
| 64.01-256.0     | 89        | 3.25%   |
| 24.01-32.0      | 42        | 1.53%   |
| 2.01-3.0        | 18        | 0.66%   |
| 0.51-1.0        | 13        | 0.47%   |
| 0.01-0.5        | 6         | 0.22%   |
| More than 256.0 | 3         | 0.11%   |
| Unknown         | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1039      | 33.77%  |
| 2.01-3.0    | 776       | 25.22%  |
| 4.01-8.0    | 423       | 13.75%  |
| 3.01-4.0    | 387       | 12.58%  |
| 0.51-1.0    | 217       | 7.05%   |
| 8.01-16.0   | 149       | 4.84%   |
| 0.01-0.5    | 46        | 1.49%   |
| 16.01-24.0  | 24        | 0.78%   |
| 24.01-32.0  | 7         | 0.23%   |
| 64.01-256.0 | 3         | 0.1%    |
| 32.01-64.0  | 2         | 0.06%   |
| 0           | 2         | 0.06%   |
| Unknown     | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1518      | 53.72%  |
| 2       | 670       | 23.71%  |
| 3       | 282       | 9.98%   |
| 4       | 161       | 5.7%    |
| 5       | 71        | 2.51%   |
| 6       | 42        | 1.49%   |
| 0       | 30        | 1.06%   |
| 7       | 21        | 0.74%   |
| 8       | 14        | 0.5%    |
| 9       | 7         | 0.25%   |
| 13      | 3         | 0.11%   |
| 10      | 3         | 0.11%   |
| 36      | 1         | 0.04%   |
| 14      | 1         | 0.04%   |
| 11      | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1591      | 58.64%  |
| Yes       | 1122      | 41.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2338      | 87.04%  |
| No        | 348       | 12.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1968      | 72.62%  |
| No        | 742       | 27.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1513      | 55.56%  |
| No        | 1210      | 44.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 2680      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 745       | 25.77%  |
| Melbourne      | 543       | 18.78%  |
| Brisbane       | 418       | 14.46%  |
| Perth          | 243       | 8.41%   |
| Adelaide       | 173       | 5.98%   |
| Canberra       | 60        | 2.08%   |
| Wahroonga      | 39        | 1.35%   |
| Hobart         | 28        | 0.97%   |
| Launceston     | 22        | 0.76%   |
| Alexandria     | 19        | 0.66%   |
| Surry Hills    | 17        | 0.59%   |
| Lane Cove      | 12        | 0.42%   |
| Mitcham        | 11        | 0.38%   |
| Gold Coast     | 11        | 0.38%   |
| Geelong        | 11        | 0.38%   |
| Woolloongabba  | 10        | 0.35%   |
| Newcastle      | 10        | 0.35%   |
| Richmond       | 9         | 0.31%   |
| Central Coast  | 9         | 0.31%   |
| Brighton       | 9         | 0.31%   |
| Traralgon      | 8         | 0.28%   |
| Southport      | 8         | 0.28%   |
| Wollongong     | 7         | 0.24%   |
| Townsville     | 7         | 0.24%   |
| Parramatta     | 7         | 0.24%   |
| Mandurah       | 7         | 0.24%   |
| Artarmon       | 7         | 0.24%   |
| West End       | 6         | 0.21%   |
| Point Cook     | 6         | 0.21%   |
| North Sydney   | 6         | 0.21%   |
| Mount Waverley | 6         | 0.21%   |
| Macquarie Park | 6         | 0.21%   |
| Spring Field   | 5         | 0.17%   |
| Ringwood East  | 5         | 0.17%   |
| Northcote      | 5         | 0.17%   |
| Mascot         | 5         | 0.17%   |
| Hawthorn       | 5         | 0.17%   |
| Geraldton      | 5         | 0.17%   |
| Doncaster      | 5         | 0.17%   |
| Clifton Hill   | 5         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 757       | 1357   | 18.32%  |
| Seagate                   | 715       | 1340   | 17.3%   |
| WDC                       | 664       | 1256   | 16.07%  |
| Toshiba                   | 223       | 315    | 5.4%    |
| Crucial                   | 210       | 316    | 5.08%   |
| Kingston                  | 182       | 236    | 4.4%    |
| SanDisk                   | 161       | 212    | 3.9%    |
| Intel                     | 159       | 285    | 3.85%   |
| Unknown                   | 152       | 229    | 3.68%   |
| Hitachi                   | 135       | 214    | 3.27%   |
| SK hynix                  | 81        | 98     | 1.96%   |
| HGST                      | 63        | 93     | 1.52%   |
| Apple                     | 63        | 87     | 1.52%   |
| Micron Technology         | 51        | 65     | 1.23%   |
| Micron/Crucial Technology | 38        | 54     | 0.92%   |
| Phison                    | 36        | 54     | 0.87%   |
| OCZ                       | 33        | 49     | 0.8%    |
| KIOXIA                    | 26        | 28     | 0.63%   |
| A-DATA Technology         | 26        | 35     | 0.63%   |
| SPCC                      | 23        | 30     | 0.56%   |
| Corsair                   | 18        | 31     | 0.44%   |
| JMicron Technology        | 17        | 20     | 0.41%   |
| LITEON                    | 16        | 24     | 0.39%   |
| LITEONIT                  | 15        | 20     | 0.36%   |
| KingSpec                  | 14        | 32     | 0.34%   |
| Fujitsu                   | 14        | 18     | 0.34%   |
| Patriot                   | 13        | 18     | 0.31%   |
| Transcend                 | 12        | 19     | 0.29%   |
| LaCie                     | 11        | 18     | 0.27%   |
| Gigabyte Technology       | 10        | 13     | 0.24%   |
| Phison Electronics        | 9         | 11     | 0.22%   |
| Maxtor                    | 9         | 11     | 0.22%   |
| China                     | 9         | 11     | 0.22%   |
| ASMT                      | 9         | 15     | 0.22%   |
| Unknown                   | 9         | 10     | 0.22%   |
| Silicon Motion            | 8         | 18     | 0.19%   |
| Realtek Semiconductor     | 8         | 11     | 0.19%   |
| Hewlett-Packard           | 8         | 12     | 0.19%   |
| XPG                       | 6         | 7      | 0.15%   |
| TO Exter                  | 6         | 6      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 51        | 1.07%   |
| Samsung SSD 850 EVO 250GB                           | 42        | 0.88%   |
| Unknown MMC Card  32GB                              | 35        | 0.73%   |
| Seagate ST500DM002-1BD142 500GB                     | 32        | 0.67%   |
| Seagate Expansion Desk 5TB                          | 32        | 0.67%   |
| Samsung NVMe SSD Drive 1TB                          | 32        | 0.67%   |
| Crucial CT240BX500SSD1 240GB                        | 31        | 0.65%   |
| Samsung SSD 850 EVO 500GB                           | 30        | 0.63%   |
| Unknown MMC Card  64GB                              | 29        | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB                      | 29        | 0.61%   |
| Seagate Expansion 4TB                               | 28        | 0.59%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.59%   |
| Samsung NVMe SSD Drive 500GB                        | 28        | 0.59%   |
| Seagate ST4000DM004-2CV104 4TB                      | 27        | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB                      | 27        | 0.56%   |
| Seagate ST2000DM001-1ER164 2TB                      | 26        | 0.54%   |
| Kingston SA400S37240G 240GB SSD                     | 24        | 0.5%    |
| Seagate ST3500418AS 500GB                           | 23        | 0.48%   |
| Seagate ST2000DM001-1CH164 2TB                      | 23        | 0.48%   |
| Samsung SSD 860 EVO 1TB                             | 23        | 0.48%   |
| Crucial CT500MX500SSD1 500GB                        | 23        | 0.48%   |
| Crucial CT480BX500SSD1 480GB                        | 23        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB                         | 23        | 0.48%   |
| Toshiba MQ01ABD100 1TB                              | 22        | 0.46%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 22        | 0.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 20        | 0.42%   |
| Kingston SV300S37A120G 120GB SSD                    | 20        | 0.42%   |
| Kingston SA400S37120G 120GB SSD                     | 20        | 0.42%   |
| WDC WD20EARX-00PASB0 2TB                            | 19        | 0.4%    |
| Seagate ST1000LM035-1RK172 1TB                      | 19        | 0.4%    |
| Samsung SSD 860 QVO 1TB                             | 19        | 0.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 19        | 0.4%    |
| Seagate ST31000528AS 1TB                            | 18        | 0.38%   |
| Seagate ST2000DM006-2DM164 2TB                      | 18        | 0.38%   |
| Seagate ST2000DL003-9VT166 2TB                      | 18        | 0.38%   |
| Seagate ST1000DM003-1ER162 1TB                      | 18        | 0.38%   |
| SanDisk NVMe SSD Drive 512GB                        | 18        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB                      | 18        | 0.38%   |
| Intel NVMe SSD Drive 512GB                          | 18        | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 16        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 702       | 1299   | 39.77%  |
| WDC                 | 539       | 1038   | 30.54%  |
| Toshiba             | 154       | 228    | 8.73%   |
| Hitachi             | 135       | 214    | 7.65%   |
| Samsung Electronics | 89        | 206    | 5.04%   |
| HGST                | 61        | 91     | 3.46%   |
| Unknown             | 15        | 25     | 0.85%   |
| Apple               | 15        | 20     | 0.85%   |
| Fujitsu             | 13        | 17     | 0.74%   |
| Maxtor              | 9         | 11     | 0.51%   |
| LaCie               | 9         | 15     | 0.51%   |
| ASMT                | 8         | 14     | 0.45%   |
| Hewlett-Packard     | 3         | 4      | 0.17%   |
| USB                 | 2         | 3      | 0.11%   |
| KESU                | 2         | 2      | 0.11%   |
| HGST HUS            | 2         | 2      | 0.11%   |
| USB3.0              | 1         | 2      | 0.06%   |
| MaxDigital          | 1         | 1      | 0.06%   |
| IBM/Hitachi         | 1         | 1      | 0.06%   |
| HPE                 | 1         | 1      | 0.06%   |
| Hajaan              | 1         | 1      | 0.06%   |
| DAS                 | 1         | 1      | 0.06%   |
| AAPL                | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 438       | 719    | 31.26%  |
| Crucial             | 186       | 285    | 13.28%  |
| Kingston            | 137       | 175    | 9.78%   |
| WDC                 | 111       | 146    | 7.92%   |
| SanDisk             | 106       | 135    | 7.57%   |
| Intel               | 80        | 160    | 5.71%   |
| Apple               | 34        | 38     | 2.43%   |
| OCZ                 | 33        | 49     | 2.36%   |
| SK hynix            | 27        | 33     | 1.93%   |
| Toshiba             | 24        | 32     | 1.71%   |
| SPCC                | 22        | 28     | 1.57%   |
| Micron Technology   | 19        | 22     | 1.36%   |
| LITEONIT            | 15        | 20     | 1.07%   |
| A-DATA Technology   | 15        | 20     | 1.07%   |
| LITEON              | 14        | 22     | 1%      |
| Patriot             | 13        | 18     | 0.93%   |
| Transcend           | 12        | 19     | 0.86%   |
| Seagate             | 12        | 18     | 0.86%   |
| KingSpec            | 11        | 28     | 0.79%   |
| Corsair             | 11        | 24     | 0.79%   |
| JMicron Technology  | 9         | 10     | 0.64%   |
| China               | 9         | 11     | 0.64%   |
| TO Exter            | 6         | 6      | 0.43%   |
| OWC                 | 6         | 13     | 0.43%   |
| Gigabyte Technology | 6         | 6      | 0.43%   |
| Plextor             | 5         | 16     | 0.36%   |
| Team                | 3         | 4      | 0.21%   |
| Vaseky              | 2         | 5      | 0.14%   |
| T-CREATE            | 2         | 2      | 0.14%   |
| Lexar               | 2         | 2      | 0.14%   |
| KingFast            | 2         | 2      | 0.14%   |
| Hajaan              | 2         | 2      | 0.14%   |
| FORESEE             | 2         | 2      | 0.14%   |
| Unknown             | 1         | 1      | 0.07%   |
| SATA3 12            | 1         | 1      | 0.07%   |
| SAMSWEET            | 1         | 1      | 0.07%   |
| Radeon              | 1         | 1      | 0.07%   |
| PNY                 | 1         | 1      | 0.07%   |
| OCZ-VERTEX3         | 1         | 1      | 0.07%   |
| Netac               | 1         | 1      | 0.07%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1426      | 3197   | 39.02%  |
| SSD     | 1213      | 2101   | 33.19%  |
| NVMe    | 824       | 1265   | 22.54%  |
| MMC     | 132       | 193    | 3.61%   |
| Unknown | 60        | 84     | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2062      | 5019   | 63.6%   |
| NVMe | 824       | 1258   | 25.42%  |
| SAS  | 224       | 370    | 6.91%   |
| MMC  | 132       | 193    | 4.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1501      | 2802   | 51.92%  |
| 0.51-1.0   | 748       | 1314   | 25.87%  |
| 1.01-2.0   | 323       | 581    | 11.17%  |
| 3.01-4.0   | 136       | 260    | 4.7%    |
| 4.01-10.0  | 105       | 207    | 3.63%   |
| 2.01-3.0   | 70        | 123    | 2.42%   |
| 10.01-20.0 | 7         | 10     | 0.24%   |
| 0          | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 642       | 22.15%  |
| 251-500        | 603       | 20.81%  |
| 501-1000       | 445       | 15.36%  |
| 1001-2000      | 265       | 9.14%   |
| 1-20           | 230       | 7.94%   |
| More than 3000 | 228       | 7.87%   |
| 51-100         | 199       | 6.87%   |
| 2001-3000      | 109       | 3.76%   |
| 21-50          | 89        | 3.07%   |
| Unknown        | 88        | 3.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1150      | 37.79%  |
| 21-50          | 493       | 16.2%   |
| 101-250        | 340       | 11.17%  |
| 51-100         | 304       | 9.99%   |
| 251-500        | 250       | 8.22%   |
| 501-1000       | 164       | 5.39%   |
| 1001-2000      | 115       | 3.78%   |
| More than 3000 | 93        | 3.06%   |
| Unknown        | 88        | 2.89%   |
| 2001-3000      | 45        | 1.48%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Intel SSDSC2CT120A3 120GB               | 7         | 28     | 2.82%   |
| Seagate ST500DM002-1BD142 500GB         | 5         | 8      | 2.02%   |
| Seagate ST3500418AS 500GB               | 5         | 11     | 2.02%   |
| Hitachi HDS721010DLE630 1TB             | 5         | 7      | 2.02%   |
| Kingston SV300S37A120G 120GB SSD        | 4         | 4      | 1.61%   |
| WDC WD20EARX-00PASB0 2TB                | 3         | 3      | 1.21%   |
| Seagate ST9500325AS 500GB               | 3         | 3      | 1.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 1.21%   |
| Maxtor 6Y080L0 81GB                     | 3         | 4      | 1.21%   |
| Maxtor 6L200M0 200GB                    | 3         | 4      | 1.21%   |
| HGST HTS725050A7E630 500GB              | 3         | 3      | 1.21%   |
| WDC WDS500G1X0E-00AFY0 500GB            | 2         | 2      | 0.81%   |
| WDC WD30EZRX-00DC0B0 3TB                | 2         | 2      | 0.81%   |
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 2      | 0.81%   |
| WDC WD2002FAEX-007BA0 2TB               | 2         | 3      | 0.81%   |
| WDC WD1600AVVS-63L2B0 160GB             | 2         | 5      | 0.81%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 3      | 0.81%   |
| WDC WD10EFRX-68FYTN0 1TB                | 2         | 2      | 0.81%   |
| WDC WD1003FZEX-00K3CA0 1TB              | 2         | 2      | 0.81%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 2         | 2      | 0.81%   |
| Seagate ST9320423AS 320GB               | 2         | 3      | 0.81%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 4      | 0.81%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 0.81%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 0.81%   |
| Seagate ST3500413AS 500GB               | 2         | 2      | 0.81%   |
| Seagate ST31000333AS 1TB                | 2         | 4      | 0.81%   |
| Seagate ST2000DM001-9YN164 2TB          | 2         | 2      | 0.81%   |
| Seagate ST2000DM001-1ER164 2TB          | 2         | 2      | 0.81%   |
| Seagate ST2000DM001-1CH164 2TB          | 2         | 2      | 0.81%   |
| Seagate ST1000DX001-1CM162 1TB          | 2         | 2      | 0.81%   |
| Seagate ST1000DM010-2EP102 1TB          | 2         | 2      | 0.81%   |
| Seagate ST1000DM003-1ER162 1TB          | 2         | 6      | 0.81%   |
| Samsung Electronics HD501LJ 500GB       | 2         | 26     | 0.81%   |
| Samsung Electronics HD154UI 1TB         | 2         | 3      | 0.81%   |
| Samsung Electronics HD103UJ 1TB         | 2         | 13     | 0.81%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 2      | 0.81%   |
| Intel SSDSC2KW010T8 1TB                 | 2         | 2      | 0.81%   |
| HGST HTS545050A7E680 500GB              | 2         | 3      | 0.81%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 1      | 0.4%    |
| WDC WD6400BEVT-22A0RT0 640GB            | 1         | 2      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 65        | 97     | 27.9%   |
| WDC                   | 48        | 82     | 20.6%   |
| Samsung Electronics   | 25        | 66     | 10.73%  |
| Intel                 | 19        | 50     | 8.15%   |
| Hitachi               | 16        | 19     | 6.87%   |
| Kingston              | 10        | 10     | 4.29%   |
| Toshiba               | 9         | 12     | 3.86%   |
| HGST                  | 7         | 8      | 3%      |
| Maxtor                | 6         | 8      | 2.58%   |
| Crucial               | 4         | 5      | 1.72%   |
| Corsair               | 4         | 5      | 1.72%   |
| SanDisk               | 3         | 3      | 1.29%   |
| Fujitsu               | 3         | 3      | 1.29%   |
| SK hynix              | 2         | 2      | 0.86%   |
| SPCC                  | 1         | 1      | 0.43%   |
| Realtek Semiconductor | 1         | 2      | 0.43%   |
| OCZ                   | 1         | 1      | 0.43%   |
| Netac                 | 1         | 1      | 0.43%   |
| MaxDigital            | 1         | 1      | 0.43%   |
| KingSpec              | 1         | 3      | 0.43%   |
| KingFast              | 1         | 1      | 0.43%   |
| HPE                   | 1         | 1      | 0.43%   |
| Hewlett-Packard       | 1         | 2      | 0.43%   |
| Gigabyte Technology   | 1         | 1      | 0.43%   |
| Apple                 | 1         | 1      | 0.43%   |
| A-DATA Technology     | 1         | 1      | 0.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 97     | 38.92%  |
| WDC                 | 47        | 79     | 28.14%  |
| Hitachi             | 16        | 19     | 9.58%   |
| Samsung Electronics | 13        | 53     | 7.78%   |
| Toshiba             | 7         | 10     | 4.19%   |
| HGST                | 7         | 8      | 4.19%   |
| Maxtor              | 6         | 8      | 3.59%   |
| Fujitsu             | 3         | 3      | 1.8%    |
| MaxDigital          | 1         | 1      | 0.6%    |
| HPE                 | 1         | 1      | 0.6%    |
| Hewlett-Packard     | 1         | 2      | 0.6%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 149       | 281    | 68.98%  |
| SSD  | 57        | 92     | 26.39%  |
| NVMe | 10        | 13     | 4.63%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200AAJS-40RYA0 320GB | 1         | 1      | 50%     |
| Hitachi HDS721010DLE630 1TB | 1         | 6      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 6      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1760      | 4050   | 60.32%  |
| Works    | 947       | 2397   | 32.45%  |
| Malfunc  | 209       | 386    | 7.16%   |
| Failed   | 2         | 7      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1798      | 51.62%  |
| AMD                              | 532       | 15.27%  |
| Samsung Electronics              | 335       | 9.62%   |
| SanDisk                          | 98        | 2.81%   |
| Marvell Technology Group         | 83        | 2.38%   |
| ASMedia Technology               | 69        | 1.98%   |
| JMicron Technology               | 67        | 1.92%   |
| Micron/Crucial Technology        | 63        | 1.81%   |
| Phison Electronics               | 56        | 1.61%   |
| SK hynix                         | 55        | 1.58%   |
| Kingston Technology Company      | 50        | 1.44%   |
| Toshiba America Info Systems     | 47        | 1.35%   |
| Micron Technology                | 32        | 0.92%   |
| Nvidia                           | 24        | 0.69%   |
| KIOXIA                           | 24        | 0.69%   |
| ADATA Technology                 | 19        | 0.55%   |
| LSI Logic / Symbios Logic        | 17        | 0.49%   |
| Silicon Motion                   | 13        | 0.37%   |
| Apple                            | 13        | 0.37%   |
| VIA Technologies                 | 11        | 0.32%   |
| Realtek Semiconductor            | 10        | 0.29%   |
| Broadcom / LSI                   | 10        | 0.29%   |
| Integrated Technology Express    | 8         | 0.23%   |
| Seagate Technology               | 7         | 0.2%    |
| Silicon Image                    | 6         | 0.17%   |
| Lite-On Technology               | 5         | 0.14%   |
| Hewlett-Packard                  | 5         | 0.14%   |
| Union Memory (Shenzhen)          | 4         | 0.11%   |
| Solid State Storage Technology   | 4         | 0.11%   |
| ULi Electronics                  | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.09%   |
| Adaptec                          | 3         | 0.09%   |
| Shenzhen Longsys Electronics     | 2         | 0.06%   |
| Lenovo                           | 2         | 0.06%   |
| 3ware                            | 2         | 0.06%   |
| Promise Technology               | 1         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 361       | 8.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 187       | 4.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 138       | 3.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 110       | 2.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 98        | 2.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 93        | 2.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 87        | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 79        | 1.93%   |
| Intel SATA Controller [RAID mode]                                                       | 73        | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 70        | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 69        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 67        | 1.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 62        | 1.52%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 62        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 61        | 1.49%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 60        | 1.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 57        | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 56        | 1.37%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 53        | 1.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 48        | 1.18%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 48        | 1.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 46        | 1.13%   |
| AMD 500 Series Chipset SATA Controller                                                  | 44        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 40        | 0.98%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 39        | 0.96%   |
| Samsung NVMe SSD Controller 980                                                         | 34        | 0.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 34        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 34        | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 33        | 0.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 33        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 33        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 32        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 31        | 0.76%   |
| Micron Non-Volatile memory controller                                                   | 31        | 0.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 31        | 0.76%   |
| Intel SSD 660P Series                                                                   | 30        | 0.73%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 30        | 0.73%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 28        | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 27        | 0.66%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 27        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1919      | 55.83%  |
| NVMe | 829       | 24.12%  |
| IDE  | 413       | 12.02%  |
| RAID | 251       | 7.3%    |
| SAS  | 18        | 0.52%   |
| SCSI | 7         | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2041      | 76.16%  |
| AMD          | 597       | 22.28%  |
| ARM          | 40        | 1.49%   |
| CentaurHauls | 1         | 0.04%   |
| Unknown      | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 36        | 1.34%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 33        | 1.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 30        | 1.12%   |
| ARM Processor                           | 28        | 1.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 27        | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 27        | 1.01%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 27        | 1.01%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 24        | 0.89%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 22        | 0.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 22        | 0.82%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 22        | 0.82%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 22        | 0.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 21        | 0.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 21        | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 0.78%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 21        | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 21        | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 20        | 0.74%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 20        | 0.74%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 19        | 0.71%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 18        | 0.67%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 17        | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 17        | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 17        | 0.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 17        | 0.63%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 16        | 0.6%    |
| AMD Ryzen 9 5950X 16-Core Processor     | 16        | 0.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 15        | 0.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 15        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 14        | 0.52%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 13        | 0.48%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 13        | 0.48%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 13        | 0.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 13        | 0.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 13        | 0.48%   |
| AMD Ryzen 7 1700 Eight-Core Processor   | 13        | 0.48%   |
| AMD FX-6300 Six-Core Processor          | 13        | 0.48%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 12        | 0.45%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 12        | 0.45%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 12        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 722       | 26.91%  |
| Intel Core i5           | 606       | 22.59%  |
| Other                   | 150       | 5.59%   |
| AMD Ryzen 5             | 147       | 5.48%   |
| Intel Core 2 Duo        | 118       | 4.4%    |
| Intel Core i3           | 115       | 4.29%   |
| AMD Ryzen 7             | 110       | 4.1%    |
| Intel Celeron           | 91        | 3.39%   |
| Intel Xeon              | 69        | 2.57%   |
| AMD Ryzen 9             | 60        | 2.24%   |
| AMD FX                  | 45        | 1.68%   |
| Intel Pentium           | 43        | 1.6%    |
| Intel Atom              | 32        | 1.19%   |
| AMD A6                  | 27        | 1.01%   |
| AMD Ryzen 3             | 23        | 0.86%   |
| Intel Core 2            | 22        | 0.82%   |
| AMD A4                  | 21        | 0.78%   |
| Intel Core 2 Quad       | 20        | 0.75%   |
| AMD A8                  | 19        | 0.71%   |
| Intel Core i9           | 18        | 0.67%   |
| Intel Pentium Dual-Core | 16        | 0.6%    |
| AMD Phenom II X4        | 14        | 0.52%   |
| AMD E2                  | 14        | 0.52%   |
| AMD A10                 | 13        | 0.48%   |
| ARM BCM                 | 10        | 0.37%   |
| AMD Ryzen Threadripper  | 10        | 0.37%   |
| AMD Phenom II X6        | 10        | 0.37%   |
| AMD Athlon              | 9         | 0.34%   |
| Intel Genuine           | 8         | 0.3%    |
| Intel Core m3           | 8         | 0.3%    |
| AMD E1                  | 8         | 0.3%    |
| Intel Pentium D         | 7         | 0.26%   |
| AMD Ryzen 7 PRO         | 7         | 0.26%   |
| Intel Pentium 4         | 5         | 0.19%   |
| AMD Phenom II X2        | 5         | 0.19%   |
| AMD E                   | 5         | 0.19%   |
| AMD Athlon II X4        | 5         | 0.19%   |
| AMD Athlon II X2        | 5         | 0.19%   |
| AMD Athlon 64 X2        | 5         | 0.19%   |
| Intel Pentium Dual      | 4         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1068      | 39.79%  |
| 2       | 917       | 34.17%  |
| 6       | 318       | 11.85%  |
| 8       | 190       | 7.08%   |
| 12      | 54        | 2.01%   |
| 1       | 51        | 1.9%    |
| 16      | 33        | 1.23%   |
| 3       | 19        | 0.71%   |
| 10      | 12        | 0.45%   |
| 14      | 7         | 0.26%   |
| 24      | 6         | 0.22%   |
| 32      | 3         | 0.11%   |
| Unknown | 3         | 0.11%   |
| 40      | 2         | 0.07%   |
| 128     | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2637      | 98.36%  |
| 2       | 40        | 1.49%   |
| Unknown | 3         | 0.11%   |
| 4       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1824      | 67.98%  |
| 1       | 854       | 31.83%  |
| Unknown | 3         | 0.11%   |
| 8       | 1         | 0.04%   |
| 4       | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2595      | 96.47%  |
| Unknown        | 67        | 2.49%   |
| 32-bit         | 22        | 0.82%   |
| 64-bit         | 6         | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 675       | 24.27%  |
| 0x206a7    | 167       | 6.01%   |
| 0x306a9    | 155       | 5.57%   |
| 0x306c3    | 131       | 4.71%   |
| 0x1067a    | 89        | 3.2%    |
| 0x906ea    | 77        | 2.77%   |
| 0x906e9    | 62        | 2.23%   |
| 0x506e3    | 60        | 2.16%   |
| 0x806e9    | 57        | 2.05%   |
| 0x406e3    | 55        | 1.98%   |
| 0x806ea    | 54        | 1.94%   |
| 0x40651    | 54        | 1.94%   |
| 0x806ec    | 51        | 1.83%   |
| 0x08701021 | 51        | 1.83%   |
| 0x806c1    | 45        | 1.62%   |
| 0x20655    | 42        | 1.51%   |
| 0x306d4    | 38        | 1.37%   |
| 0x08701013 | 33        | 1.19%   |
| 0x106e5    | 29        | 1.04%   |
| 0x0800820d | 29        | 1.04%   |
| 0x10676    | 26        | 0.93%   |
| 0x30678    | 24        | 0.86%   |
| 0x20652    | 24        | 0.86%   |
| 0x06000852 | 22        | 0.79%   |
| 0xa0652    | 21        | 0.76%   |
| 0x906ed    | 19        | 0.68%   |
| 0x106a5    | 19        | 0.68%   |
| 0x706e5    | 18        | 0.65%   |
| 0x0a50000c | 18        | 0.65%   |
| 0x08108109 | 18        | 0.65%   |
| 0x010000c8 | 18        | 0.65%   |
| 0x806eb    | 17        | 0.61%   |
| 0x06001119 | 17        | 0.61%   |
| 0x6fb      | 16        | 0.58%   |
| 0x6f6      | 16        | 0.58%   |
| 0x206c2    | 16        | 0.58%   |
| 0x08001138 | 16        | 0.58%   |
| 0x06006705 | 16        | 0.58%   |
| 0x07030105 | 15        | 0.54%   |
| 0x406c4    | 14        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 440       | 16.39%  |
| Haswell          | 268       | 9.98%   |
| SandyBridge      | 213       | 7.93%   |
| IvyBridge        | 207       | 7.71%   |
| Skylake          | 158       | 5.88%   |
| Zen 2            | 139       | 5.18%   |
| Penryn           | 134       | 4.99%   |
| Westmere         | 102       | 3.8%    |
| Zen 3            | 83        | 3.09%   |
| Unknown          | 79        | 2.94%   |
| Zen+             | 70        | 2.61%   |
| Core             | 63        | 2.35%   |
| CometLake        | 62        | 2.31%   |
| Zen              | 61        | 2.27%   |
| Silvermont       | 59        | 2.2%    |
| Nehalem          | 59        | 2.2%    |
| TigerLake        | 56        | 2.09%   |
| Piledriver       | 53        | 1.97%   |
| Broadwell        | 52        | 1.94%   |
| K10              | 51        | 1.9%    |
| IceLake          | 41        | 1.53%   |
| Excavator        | 33        | 1.23%   |
| Goldmont plus    | 25        | 0.93%   |
| Puma             | 20        | 0.74%   |
| Alderlake Hybrid | 19        | 0.71%   |
| Goldmont         | 18        | 0.67%   |
| Bonnell          | 16        | 0.6%    |
| Steamroller      | 14        | 0.52%   |
| NetBurst         | 14        | 0.52%   |
| Jaguar           | 13        | 0.48%   |
| Bulldozer        | 13        | 0.48%   |
| P6               | 12        | 0.45%   |
| K8 Hammer        | 12        | 0.45%   |
| K10 Llano        | 11        | 0.41%   |
| Bobcat           | 9         | 0.34%   |
| Tremont          | 4         | 0.15%   |
| K8 & K10 hybrid  | 2         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1425      | 45.45%  |
| Nvidia                           | 978       | 31.2%   |
| AMD                              | 702       | 22.39%  |
| Matrox Electronics Systems       | 19        | 0.61%   |
| VIA Technologies                 | 4         | 0.13%   |
| Silicon Integrated Systems [SiS] | 3         | 0.1%    |
| Neomagic                         | 2         | 0.06%   |
| ASPEED Technology                | 2         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 142       | 4.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 92        | 2.84%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 76        | 2.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 69        | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 67        | 2.07%   |
| Intel UHD Graphics 620                                                                   | 66        | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 63        | 1.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 60        | 1.86%   |
| Intel HD Graphics 620                                                                    | 54        | 1.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 53        | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 52        | 1.61%   |
| Intel HD Graphics 530                                                                    | 44        | 1.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 43        | 1.33%   |
| Intel HD Graphics 630                                                                    | 40        | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 40        | 1.24%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 39        | 1.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 38        | 1.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 33        | 1.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 32        | 0.99%   |
| Intel HD Graphics 5500                                                                   | 31        | 0.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 30        | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 28        | 0.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 27        | 0.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 27        | 0.83%   |
| AMD Renoir                                                                               | 26        | 0.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 25        | 0.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 25        | 0.77%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 23        | 0.71%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 23        | 0.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 23        | 0.71%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 23        | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22        | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 21        | 0.65%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 20        | 0.62%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 19        | 0.59%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 19        | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 17        | 0.53%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 17        | 0.53%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 17        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 988       | 36.4%   |
| 1 x Nvidia               | 612       | 22.55%  |
| 1 x AMD                  | 560       | 20.63%  |
| Intel + Nvidia           | 323       | 11.9%   |
| Intel + AMD              | 63        | 2.32%   |
| 2 x AMD                  | 50        | 1.84%   |
| Other                    | 41        | 1.51%   |
| AMD + Nvidia             | 31        | 1.14%   |
| 1 x Matrox               | 16        | 0.59%   |
| 2 x Nvidia               | 10        | 0.37%   |
| 1 x VIA                  | 4         | 0.15%   |
| 1 x SiS                  | 3         | 0.11%   |
| Nvidia + Matrox          | 3         | 0.11%   |
| Intel + AMD + 1 x Nvidia | 3         | 0.11%   |
| 2 x Intel                | 2         | 0.07%   |
| Nvidia + ASPEED          | 2         | 0.07%   |
| 1 x Neomagic             | 2         | 0.07%   |
| Intel + 2 x AMD          | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2055      | 74.78%  |
| Proprietary | 550       | 20.01%  |
| Unknown     | 143       | 5.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1418      | 51.14%  |
| 1.01-2.0   | 357       | 12.87%  |
| 0.01-0.5   | 253       | 9.12%   |
| 0.51-1.0   | 227       | 8.19%   |
| 3.01-4.0   | 206       | 7.43%   |
| 7.01-8.0   | 166       | 5.99%   |
| 5.01-6.0   | 69        | 2.49%   |
| 8.01-16.0  | 40        | 1.44%   |
| 2.01-3.0   | 27        | 0.97%   |
| 16.01-24.0 | 8         | 0.29%   |
| 32.01-64.0 | 1         | 0.04%   |
| 4.01-5.0   | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 378       | 12.41%  |
| AU Optronics            | 295       | 9.68%   |
| Dell                    | 234       | 7.68%   |
| LG Display              | 223       | 7.32%   |
| Chimei Innolux          | 172       | 5.64%   |
| Acer                    | 144       | 4.73%   |
| Goldstar                | 139       | 4.56%   |
| BOE                     | 130       | 4.27%   |
| BenQ                    | 125       | 4.1%    |
| Hewlett-Packard         | 123       | 4.04%   |
| Apple                   | 105       | 3.45%   |
| Philips                 | 95        | 3.12%   |
| Ancor Communications    | 93        | 3.05%   |
| AOC                     | 71        | 2.33%   |
| Sharp                   | 67        | 2.2%    |
| ViewSonic               | 60        | 1.97%   |
| Lenovo                  | 60        | 1.97%   |
| Unknown                 | 53        | 1.74%   |
| Chi Mei Optoelectronics | 42        | 1.38%   |
| Sony                    | 33        | 1.08%   |
| ASUSTek Computer        | 33        | 1.08%   |
| ___                     | 28        | 0.92%   |
| Panasonic               | 25        | 0.82%   |
| LG Electronics          | 25        | 0.82%   |
| Kogan                   | 20        | 0.66%   |
| PANDA                   | 17        | 0.56%   |
| GKK                     | 16        | 0.53%   |
| Toshiba                 | 13        | 0.43%   |
| Hitachi                 | 12        | 0.39%   |
| SAC                     | 11        | 0.36%   |
| Unknown (XXX)           | 10        | 0.33%   |
| MSI                     | 10        | 0.33%   |
| TCL                     | 8         | 0.26%   |
| CVT                     | 8         | 0.26%   |
| MStar                   | 7         | 0.23%   |
| eMachines               | 7         | 0.23%   |
| Eizo                    | 7         | 0.23%   |
| MiTAC                   | 6         | 0.2%    |
| LG Philips              | 6         | 0.2%    |
| InfoVision              | 6         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch      | 21        | 0.65%   |
| ___ LCDTV16 ___0101 1920x1080                                            | 19        | 0.59%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.5%    |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch                | 12        | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.34%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch              | 11        | 0.34%   |
| ___ LCDTV16 ___9000 1360x768                                             | 10        | 0.31%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.31%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                      | 9         | 0.28%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 9         | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 9         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 9         | 0.28%   |
| BenQ G2420HD BNQ7840 1920x1080 530x300mm 24.0-inch                       | 9         | 0.28%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.28%   |
| Samsung Electronics LCD Monitor SAM2C35 1024x768 280x210mm 13.8-inch     | 8         | 0.25%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                        | 8         | 0.25%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 8         | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 0.25%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                         | 8         | 0.25%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch           | 7         | 0.22%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                    | 7         | 0.22%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch             | 7         | 0.22%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                    | 7         | 0.22%   |
| CVT CVTE TV CVT0003 1920x1080 575x323mm 26.0-inch                        | 7         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 7         | 0.22%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 7         | 0.22%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 7         | 0.22%   |
| Ancor Communications MW221 ACI22B1 1680x1050 473x296mm 22.0-inch         | 7         | 0.22%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                       | 6         | 0.19%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 6         | 0.19%   |
| eMachines E190HQV EMA0212 1366x768 409x230mm 18.5-inch                   | 6         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 6         | 0.19%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                     | 6         | 0.19%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 6         | 0.19%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.19%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 6         | 0.19%   |
| Acer ET322QR ACR0568 1920x1080 698x393mm 31.5-inch                       | 6         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1226      | 42.35%  |
| 1366x768 (WXGA)    | 430       | 14.85%  |
| 3840x2160 (4K)     | 252       | 8.7%    |
| 2560x1440 (QHD)    | 151       | 5.22%   |
| 1680x1050 (WSXGA+) | 114       | 3.94%   |
| 1280x1024 (SXGA)   | 106       | 3.66%   |
| 1440x900 (WXGA+)   | 85        | 2.94%   |
| 1920x1200 (WUXGA)  | 83        | 2.87%   |
| 1600x900 (HD+)     | 64        | 2.21%   |
| 1280x800 (WXGA)    | 54        | 1.87%   |
| Unknown            | 46        | 1.59%   |
| 3440x1440          | 35        | 1.21%   |
| 3840x1080          | 25        | 0.86%   |
| 2560x1600          | 24        | 0.83%   |
| 1360x768           | 20        | 0.69%   |
| 2560x1080          | 19        | 0.66%   |
| 2880x1800          | 14        | 0.48%   |
| 3840x2400          | 12        | 0.41%   |
| 2736x1824          | 10        | 0.35%   |
| 1920x540           | 9         | 0.31%   |
| 1280x768           | 9         | 0.31%   |
| 3200x1800 (QHD+)   | 7         | 0.24%   |
| 2160x1440          | 7         | 0.24%   |
| 1280x720 (HD)      | 7         | 0.24%   |
| 1024x600           | 6         | 0.21%   |
| 3840x1600          | 5         | 0.17%   |
| 2256x1504          | 5         | 0.17%   |
| 1920x1280          | 5         | 0.17%   |
| 1024x768 (XGA)     | 5         | 0.17%   |
| 5760x2160          | 4         | 0.14%   |
| 5120x1440          | 4         | 0.14%   |
| 4480x1440          | 4         | 0.14%   |
| 3600x1080          | 4         | 0.14%   |
| 3072x1920          | 4         | 0.14%   |
| 1600x1200          | 4         | 0.14%   |
| 2240x1400          | 3         | 0.1%    |
| 7680x2160          | 2         | 0.07%   |
| 3456x2160          | 2         | 0.07%   |
| 3286x1080          | 2         | 0.07%   |
| 3200x2000          | 2         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 568       | 18.78%  |
| 27      | 300       | 9.92%   |
| 13      | 252       | 8.33%   |
| 24      | 239       | 7.9%    |
| 23      | 222       | 7.34%   |
| Unknown | 201       | 6.64%   |
| 21      | 174       | 5.75%   |
| 14      | 163       | 5.39%   |
| 19      | 123       | 4.07%   |
| 17      | 123       | 4.07%   |
| 31      | 94        | 3.11%   |
| 22      | 82        | 2.71%   |
| 12      | 54        | 1.79%   |
| 34      | 48        | 1.59%   |
| 72      | 47        | 1.55%   |
| 20      | 45        | 1.49%   |
| 11      | 40        | 1.32%   |
| 18      | 32        | 1.06%   |
| 84      | 23        | 0.76%   |
| 26      | 19        | 0.63%   |
| 54      | 18        | 0.6%    |
| 32      | 17        | 0.56%   |
| 52      | 13        | 0.43%   |
| 16      | 13        | 0.43%   |
| 48      | 12        | 0.4%    |
| 40      | 12        | 0.4%    |
| 25      | 9         | 0.3%    |
| 37      | 8         | 0.26%   |
| 10      | 8         | 0.26%   |
| 29      | 7         | 0.23%   |
| 55      | 6         | 0.2%    |
| 42      | 6         | 0.2%    |
| 35      | 6         | 0.2%    |
| 49      | 5         | 0.17%   |
| 46      | 5         | 0.17%   |
| 63      | 4         | 0.13%   |
| 36      | 4         | 0.13%   |
| 75      | 2         | 0.07%   |
| 65      | 2         | 0.07%   |
| 60      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 841       | 28.45%  |
| 501-600     | 689       | 23.31%  |
| 401-500     | 366       | 12.38%  |
| 201-300     | 262       | 8.86%   |
| Unknown     | 201       | 6.8%    |
| 351-400     | 196       | 6.63%   |
| 601-700     | 150       | 5.07%   |
| 1501-2000   | 74        | 2.5%    |
| 1001-1500   | 72        | 2.44%   |
| 701-800     | 67        | 2.27%   |
| 801-900     | 29        | 0.98%   |
| 901-1000    | 7         | 0.24%   |
| 101-200     | 2         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1914      | 71.13%  |
| 16/10   | 368       | 13.68%  |
| Unknown | 168       | 6.24%   |
| 5/4     | 93        | 3.46%   |
| 21/9    | 60        | 2.23%   |
| 3/2     | 37        | 1.37%   |
| 4/3     | 26        | 0.97%   |
| 32/9    | 14        | 0.52%   |
| 6/5     | 10        | 0.37%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 586       | 19.62%  |
| 101-110        | 567       | 18.99%  |
| 301-350        | 313       | 10.48%  |
| 81-90          | 292       | 9.78%   |
| 151-200        | 207       | 6.93%   |
| Unknown        | 201       | 6.73%   |
| 351-500        | 168       | 5.63%   |
| 71-80          | 126       | 4.22%   |
| More than 1000 | 125       | 4.19%   |
| 251-300        | 92        | 3.08%   |
| 121-130        | 86        | 2.88%   |
| 501-1000       | 52        | 1.74%   |
| 141-150        | 44        | 1.47%   |
| 61-70          | 43        | 1.44%   |
| 51-60          | 41        | 1.37%   |
| 111-120        | 13        | 0.44%   |
| 131-140        | 10        | 0.33%   |
| 91-100         | 10        | 0.33%   |
| 41-50          | 8         | 0.27%   |
| 1-40           | 2         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1052      | 36.66%  |
| 101-120       | 666       | 23.21%  |
| 121-160       | 571       | 19.9%   |
| Unknown       | 201       | 7%      |
| 161-240       | 179       | 6.24%   |
| 1-50          | 102       | 3.55%   |
| More than 240 | 99        | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2120      | 75.93%  |
| 2     | 473       | 16.94%  |
| 0     | 133       | 4.76%   |
| 3     | 60        | 2.15%   |
| 4     | 6         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1392      | 33.7%   |
| Realtek Semiconductor           | 1364      | 33.03%  |
| Qualcomm Atheros                | 440       | 10.65%  |
| Broadcom                        | 274       | 6.63%   |
| Broadcom Limited                | 60        | 1.45%   |
| Ralink                          | 54        | 1.31%   |
| Marvell Technology Group        | 54        | 1.31%   |
| TP-Link                         | 39        | 0.94%   |
| Ralink Technology               | 38        | 0.92%   |
| Samsung Electronics             | 30        | 0.73%   |
| NetGear                         | 22        | 0.53%   |
| MediaTek                        | 21        | 0.51%   |
| DisplayLink                     | 20        | 0.48%   |
| D-Link                          | 19        | 0.46%   |
| Sierra Wireless                 | 17        | 0.41%   |
| Nvidia                          | 17        | 0.41%   |
| Huawei Technologies             | 17        | 0.41%   |
| D-Link System                   | 17        | 0.41%   |
| Edimax Technology               | 15        | 0.36%   |
| Dell                            | 15        | 0.36%   |
| Aquantia                        | 15        | 0.36%   |
| Microsoft                       | 14        | 0.34%   |
| ASIX Electronics                | 13        | 0.31%   |
| ZTE WCDMA Technologies MSM      | 11        | 0.27%   |
| Apple                           | 11        | 0.27%   |
| Lenovo                          | 10        | 0.24%   |
| Motorola PCS                    | 9         | 0.22%   |
| ASUSTek Computer                | 9         | 0.22%   |
| VIA Technologies                | 7         | 0.17%   |
| OPPO Electronics                | 7         | 0.17%   |
| Google                          | 7         | 0.17%   |
| Qualcomm Atheros Communications | 6         | 0.15%   |
| Hewlett-Packard                 | 6         | 0.15%   |
| Mellanox Technologies           | 5         | 0.12%   |
| ICS Advent                      | 5         | 0.12%   |
| Arduino SA                      | 5         | 0.12%   |
| Standard Microsystems           | 4         | 0.1%    |
| Qualcomm                        | 4         | 0.1%    |
| JMicron Technology              | 4         | 0.1%    |
| Xiaomi                          | 3         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 934       | 19.29%  |
| Intel Wi-Fi 6 AX200                                               | 133       | 2.75%   |
| Intel I211 Gigabit Network Connection                             | 113       | 2.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 111       | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 109       | 2.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 97        | 2%      |
| Intel Wireless 8265 / 8275                                        | 71        | 1.47%   |
| Intel Wireless 8260                                               | 66        | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 62        | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 58        | 1.2%    |
| Intel Ethernet Connection (2) I219-V                              | 54        | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 51        | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 50        | 1.03%   |
| Intel Wireless 7260                                               | 49        | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 48        | 0.99%   |
| Intel Wireless 7265                                               | 47        | 0.97%   |
| Intel Wi-Fi 6 AX201                                               | 44        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 44        | 0.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 43        | 0.89%   |
| Intel Wireless 3165                                               | 40        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                              | 39        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 39        | 0.81%   |
| Intel Wireless-AC 9260                                            | 37        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 36        | 0.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 34        | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 34        | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 33        | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 33        | 0.68%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 32        | 0.66%   |
| Intel Centrino Ultimate-N 6300                                    | 31        | 0.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 31        | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 28        | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.54%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 26        | 0.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 25        | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 25        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 25        | 0.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 24        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 964       | 45.82%  |
| Qualcomm Atheros                | 328       | 15.59%  |
| Realtek Semiconductor           | 296       | 14.07%  |
| Broadcom                        | 184       | 8.75%   |
| Ralink                          | 54        | 2.57%   |
| Broadcom Limited                | 41        | 1.95%   |
| Ralink Technology               | 38        | 1.81%   |
| TP-Link                         | 37        | 1.76%   |
| NetGear                         | 21        | 1%      |
| Marvell Technology Group        | 19        | 0.9%    |
| Sierra Wireless                 | 17        | 0.81%   |
| MediaTek                        | 17        | 0.81%   |
| Edimax Technology               | 15        | 0.71%   |
| D-Link System                   | 12        | 0.57%   |
| D-Link                          | 11        | 0.52%   |
| Microsoft                       | 10        | 0.48%   |
| ASUSTek Computer                | 9         | 0.43%   |
| Dell                            | 8         | 0.38%   |
| Qualcomm Atheros Communications | 6         | 0.29%   |
| BUFFALO                         | 3         | 0.14%   |
| Belkin Components               | 3         | 0.14%   |
| Wacom                           | 2         | 0.1%    |
| Linksys                         | 2         | 0.1%    |
| Xiaomi                          | 1         | 0.05%   |
| Wilocity                        | 1         | 0.05%   |
| Toshiba                         | 1         | 0.05%   |
| Qualcomm                        | 1         | 0.05%   |
| IMC Networks                    | 1         | 0.05%   |
| Hewlett-Packard                 | 1         | 0.05%   |
| AboCom Systems                  | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 133       | 6.28%   |
| Intel Wireless 8265 / 8275                                     | 71        | 3.35%   |
| Intel Wireless 8260                                            | 66        | 3.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 58        | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 51        | 2.41%   |
| Intel Wireless 7260                                            | 49        | 2.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 48        | 2.27%   |
| Intel Wireless 7265                                            | 47        | 2.22%   |
| Intel Wi-Fi 6 AX201                                            | 44        | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 44        | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 43        | 2.03%   |
| Intel Wireless 3165                                            | 40        | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 39        | 1.84%   |
| Intel Wireless-AC 9260                                         | 37        | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 36        | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 34        | 1.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 34        | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 33        | 1.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 32        | 1.51%   |
| Intel Centrino Ultimate-N 6300                                 | 31        | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 31        | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 28        | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 25        | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 25        | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 24        | 1.13%   |
| Realtek 802.11ac NIC                                           | 23        | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 23        | 1.09%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 22        | 1.04%   |
| Intel Wireless 3160                                            | 20        | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 20        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 19        | 0.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 18        | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 18        | 0.85%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 18        | 0.85%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 18        | 0.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 17        | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 16        | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 16        | 0.76%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 15        | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 15        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1217      | 47.06%  |
| Intel                            | 793       | 30.67%  |
| Qualcomm Atheros                 | 161       | 6.23%   |
| Broadcom                         | 136       | 5.26%   |
| Marvell Technology Group         | 35        | 1.35%   |
| Samsung Electronics              | 30        | 1.16%   |
| DisplayLink                      | 20        | 0.77%   |
| Broadcom Limited                 | 19        | 0.73%   |
| Nvidia                           | 17        | 0.66%   |
| Aquantia                         | 15        | 0.58%   |
| Huawei Technologies              | 13        | 0.5%    |
| ASIX Electronics                 | 13        | 0.5%    |
| ZTE WCDMA Technologies MSM       | 11        | 0.43%   |
| Apple                            | 11        | 0.43%   |
| Lenovo                           | 10        | 0.39%   |
| D-Link                           | 8         | 0.31%   |
| VIA Technologies                 | 7         | 0.27%   |
| OPPO Electronics                 | 7         | 0.27%   |
| Google                           | 7         | 0.27%   |
| Motorola PCS                     | 5         | 0.19%   |
| ICS Advent                       | 5         | 0.19%   |
| D-Link System                    | 5         | 0.19%   |
| Standard Microsystems            | 4         | 0.15%   |
| JMicron Technology               | 4         | 0.15%   |
| Microsoft                        | 3         | 0.12%   |
| Microchip Technology             | 3         | 0.12%   |
| MediaTek                         | 3         | 0.12%   |
| IBM                              | 3         | 0.12%   |
| Xiaomi                           | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| Qualcomm                         | 2         | 0.08%   |
| QLogic                           | 2         | 0.08%   |
| NetGear                          | 2         | 0.08%   |
| Mellanox Technologies            | 2         | 0.08%   |
| Hewlett-Packard                  | 2         | 0.08%   |
| vivo                             | 1         | 0.04%   |
| TP-Link                          | 1         | 0.04%   |
| T & A Mobile Phones              | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |
| Cypress Semiconductor            | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 934       | 35.01%  |
| Intel I211 Gigabit Network Connection                             | 113       | 4.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 111       | 4.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 109       | 4.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 97        | 3.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 62        | 2.32%   |
| Intel Ethernet Connection (2) I219-V                              | 54        | 2.02%   |
| Intel Ethernet Connection I217-LM                                 | 50        | 1.87%   |
| Intel Ethernet Connection (7) I219-V                              | 39        | 1.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 1.27%   |
| Intel Ethernet Controller I225-V                                  | 33        | 1.24%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 0.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 26        | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                             | 25        | 0.94%   |
| Intel 82579V Gigabit Network Connection                           | 24        | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.82%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 22        | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 21        | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 20        | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.71%   |
| Intel 82574L Gigabit Network Connection                           | 17        | 0.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 17        | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16        | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 16        | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 16        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                              | 16        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 14        | 0.52%   |
| Intel Ethernet Connection I219-V                                  | 12        | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.41%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.41%   |
| Intel 82578DM Gigabit Network Connection                          | 11        | 0.41%   |
| Intel 82546EB Gigabit Ethernet Controller (Copper)                | 11        | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.37%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.37%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.37%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 10        | 0.37%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 10        | 0.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 10        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2329      | 53.58%  |
| WiFi     | 1963      | 45.16%  |
| Modem    | 40        | 0.92%   |
| Unknown  | 15        | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1482      | 53.42%  |
| Ethernet | 1291      | 46.54%  |
| Unknown  | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1414      | 52.25%  |
| 1     | 1092      | 40.35%  |
| 3     | 99        | 3.66%   |
| 0     | 71        | 2.62%   |
| 4     | 18        | 0.67%   |
| 5     | 8         | 0.3%    |
| 6     | 3         | 0.11%   |
| 8     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2430      | 88.98%  |
| Yes  | 301       | 11.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 776       | 50.42%  |
| Broadcom                        | 106       | 6.89%   |
| Apple                           | 102       | 6.63%   |
| Cambridge Silicon Radio         | 101       | 6.56%   |
| Qualcomm Atheros Communications | 96        | 6.24%   |
| Realtek Semiconductor           | 91        | 5.91%   |
| Lite-On Technology              | 41        | 2.66%   |
| IMC Networks                    | 37        | 2.4%    |
| Toshiba                         | 36        | 2.34%   |
| Foxconn / Hon Hai               | 33        | 2.14%   |
| ASUSTek Computer                | 23        | 1.49%   |
| Marvell Semiconductor           | 17        | 1.1%    |
| Hewlett-Packard                 | 17        | 1.1%    |
| Ralink                          | 16        | 1.04%   |
| Dell                            | 15        | 0.97%   |
| Alps Electric                   | 6         | 0.39%   |
| Realtek                         | 5         | 0.32%   |
| Edimax Technology               | 4         | 0.26%   |
| Ralink Technology               | 3         | 0.19%   |
| MediaTek                        | 3         | 0.19%   |
| USI                             | 2         | 0.13%   |
| TP-Link                         | 2         | 0.13%   |
| Integrated System Solution      | 2         | 0.13%   |
| Belkin Components               | 2         | 0.13%   |
| Opticis                         | 1         | 0.06%   |
| Logitech                        | 1         | 0.06%   |
| Creative Technology             | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 277       | 17.98%  |
| Intel AX201 Bluetooth                               | 135       | 8.76%   |
| Intel AX200 Bluetooth                               | 129       | 8.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 101       | 6.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 93        | 6.04%   |
| Realtek Bluetooth Radio                             | 52        | 3.37%   |
| Intel Wireless-AC 3168 Bluetooth                    | 39        | 2.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 39        | 2.53%   |
| Qualcomm Atheros  Bluetooth Device                  | 38        | 2.47%   |
| Apple Bluetooth Host Controller                     | 36        | 2.34%   |
| Apple Bluetooth USB Host Controller                 | 35        | 2.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 34        | 2.21%   |
| Realtek  Bluetooth 4.2 Adapter                      | 31        | 2.01%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 26        | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 1.36%   |
| Intel AX210 Bluetooth                               | 21        | 1.36%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 20        | 1.3%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 1.17%   |
| Ralink RT3290 Bluetooth                             | 16        | 1.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 1.04%   |
| Intel Bluetooth Device                              | 16        | 1.04%   |
| Marvell Bluetooth and Wireless LAN Composite        | 14        | 0.91%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.91%   |
| Lite-On Bluetooth Device                            | 13        | 0.84%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.84%   |
| Toshiba Bluetooth Device                            | 12        | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 0.71%   |
| Apple Bluetooth HCI                                 | 11        | 0.71%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.65%   |
| IMC Networks Bluetooth Radio                        | 10        | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.65%   |
| Broadcom HP Portable Bumble Bee                     | 9         | 0.58%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.52%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.52%   |
| IMC Networks Bluetooth Device                       | 7         | 0.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.45%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.45%   |
| Toshiba Askey Bluetooth Module                      | 5         | 0.32%   |
| Realtek RTL8821A Bluetooth                          | 5         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1945      | 49.52%  |
| AMD                                  | 791       | 20.14%  |
| Nvidia                               | 729       | 18.56%  |
| C-Media Electronics                  | 51        | 1.3%    |
| Logitech                             | 42        | 1.07%   |
| Creative Labs                        | 26        | 0.66%   |
| Realtek Semiconductor                | 22        | 0.56%   |
| Texas Instruments                    | 17        | 0.43%   |
| Kingston Technology                  | 16        | 0.41%   |
| Creative Technology                  | 16        | 0.41%   |
| Razer USA                            | 13        | 0.33%   |
| Plantronics                          | 13        | 0.33%   |
| Generalplus Technology               | 13        | 0.33%   |
| GN Netcom                            | 12        | 0.31%   |
| Apple                                | 12        | 0.31%   |
| RODE Microphones                     | 11        | 0.28%   |
| Lenovo                               | 8         | 0.2%    |
| Blue Microphones                     | 8         | 0.2%    |
| VIA Technologies                     | 7         | 0.18%   |
| SteelSeries ApS                      | 7         | 0.18%   |
| Dell                                 | 7         | 0.18%   |
| Corsair                              | 7         | 0.18%   |
| JMTek                                | 6         | 0.15%   |
| Hewlett-Packard                      | 6         | 0.15%   |
| Astro Gaming                         | 6         | 0.15%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.13%   |
| OPPO Electronics                     | 5         | 0.13%   |
| Microsoft                            | 5         | 0.13%   |
| M-Audio                              | 5         | 0.13%   |
| Cambridge Silicon Radio              | 5         | 0.13%   |
| Sennheiser Communications            | 4         | 0.1%    |
| Samson Technologies                  | 4         | 0.1%    |
| PreSonus Audio Electronics           | 4         | 0.1%    |
| Micro Star International             | 4         | 0.1%    |
| Giga-Byte Technology                 | 4         | 0.1%    |
| Chicony Electronics                  | 4         | 0.1%    |
| Audio-Technica                       | 4         | 0.1%    |
| ASUSTek Computer                     | 4         | 0.1%    |
| Unknown                              | 3         | 0.08%   |
| ULi Electronics                      | 3         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 207       | 4.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 201       | 4.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 192       | 4.21%   |
| AMD Starship/Matisse HD Audio Controller                                          | 160       | 3.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 158       | 3.46%   |
| AMD Family 17h/19h HD Audio Controller                                            | 125       | 2.74%   |
| Intel Cannon Lake PCH cAVS                                                        | 115       | 2.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 114       | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 112       | 2.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 89        | 1.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 84        | 1.84%   |
| AMD FCH Azalia Controller                                                         | 81        | 1.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 76        | 1.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 72        | 1.58%   |
| Intel 8 Series HD Audio Controller                                                | 71        | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                             | 70        | 1.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 68        | 1.49%   |
| Intel 200 Series PCH HD Audio                                                     | 64        | 1.4%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 59        | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 58        | 1.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 57        | 1.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 55        | 1.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 53        | 1.16%   |
| Nvidia TU116 High Definition Audio Controller                                     | 50        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 47        | 1.03%   |
| Nvidia GP104 High Definition Audio Controller                                     | 47        | 1.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 46        | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 45        | 0.99%   |
| Intel Broadwell-U Audio Controller                                                | 45        | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 44        | 0.96%   |
| Intel Comet Lake PCH cAVS                                                         | 43        | 0.94%   |
| Nvidia TU106 High Definition Audio Controller                                     | 42        | 0.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 42        | 0.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 41        | 0.9%    |
| AMD Kabini HDMI/DP Audio                                                          | 38        | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 36        | 0.79%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 36        | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                                     | 35        | 0.77%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 33        | 0.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 33        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 303       | 20.9%   |
| SK hynix            | 248       | 17.1%   |
| Kingston            | 164       | 11.31%  |
| Micron Technology   | 138       | 9.52%   |
| Corsair             | 134       | 9.24%   |
| Unknown             | 126       | 8.69%   |
| Crucial             | 86        | 5.93%   |
| G.Skill             | 80        | 5.52%   |
| Team                | 26        | 1.79%   |
| Nanya Technology    | 23        | 1.59%   |
| Elpida              | 22        | 1.52%   |
| Patriot             | 15        | 1.03%   |
| Ramaxel Technology  | 14        | 0.97%   |
| A-DATA Technology   | 9         | 0.62%   |
| Transcend           | 8         | 0.55%   |
| Apacer              | 8         | 0.55%   |
| Unknown             | 6         | 0.41%   |
| Neo Forza           | 4         | 0.28%   |
| GeIL                | 4         | 0.28%   |
| Strontium           | 3         | 0.21%   |
| Silicon Power       | 3         | 0.21%   |
| Unknown (ABCD)      | 2         | 0.14%   |
| Smart               | 2         | 0.14%   |
| pqi                 | 2         | 0.14%   |
| Hewlett-Packard     | 2         | 0.14%   |
| Avant               | 2         | 0.14%   |
| Unknown (0x89AD)    | 1         | 0.07%   |
| Unknown (0x873E)    | 1         | 0.07%   |
| Unknown (0x0562)    | 1         | 0.07%   |
| Undefi              | 1         | 0.07%   |
| Toshiba             | 1         | 0.07%   |
| Qimonda             | 1         | 0.07%   |
| Princeton           | 1         | 0.07%   |
| PNY                 | 1         | 0.07%   |
| Netlist             | 1         | 0.07%   |
| Innodisk            | 1         | 0.07%   |
| GSkill              | 1         | 0.07%   |
| Goldenmars          | 1         | 0.07%   |
| Golden Empire       | 1         | 0.07%   |
| CSX                 | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s      | 17        | 1.08%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s         | 13        | 0.83%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s         | 13        | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 12        | 0.76%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 10        | 0.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 10        | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 10        | 0.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 10        | 0.64%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 10        | 0.64%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s        | 9         | 0.57%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 8         | 0.51%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 8         | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 8         | 0.51%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 8         | 0.51%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                        | 7         | 0.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 7         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 7         | 0.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 7         | 0.44%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s      | 7         | 0.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 7         | 0.44%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.44%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s          | 6         | 0.38%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 6         | 0.38%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 6         | 0.38%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 6         | 0.38%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 6         | 0.38%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 6         | 0.38%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 6         | 0.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 6         | 0.38%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s         | 6         | 0.38%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 6         | 0.38%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 6         | 0.38%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 6         | 0.38%   |
| Unknown                                                       | 6         | 0.38%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 5         | 0.32%   |
| Unknown RAM Module 2GB DIMM 800MT/s                           | 5         | 0.32%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 5         | 0.32%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s         | 5         | 0.32%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s        | 5         | 0.32%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 5         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 583       | 45.76%  |
| DDR3    | 443       | 34.77%  |
| LPDDR3  | 63        | 4.95%   |
| Unknown | 62        | 4.87%   |
| DDR2    | 49        | 3.85%   |
| LPDDR4  | 32        | 2.51%   |
| SDRAM   | 17        | 1.33%   |
| DDR5    | 9         | 0.71%   |
| DDR     | 9         | 0.71%   |
| LPDDR5  | 5         | 0.39%   |
| DRAM    | 2         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 610       | 48.03%  |
| DIMM         | 549       | 43.23%  |
| Row Of Chips | 99        | 7.8%    |
| Chip         | 8         | 0.63%   |
| FB-DIMM      | 2         | 0.16%   |
| Unknown      | 2         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 531       | 39.19%  |
| 4096  | 360       | 26.57%  |
| 16384 | 213       | 15.72%  |
| 2048  | 169       | 12.47%  |
| 32768 | 41        | 3.03%   |
| 1024  | 31        | 2.29%   |
| 512   | 7         | 0.52%   |
| 65536 | 2         | 0.15%   |
| 256   | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 289       | 20.88%  |
| 2667    | 191       | 13.8%   |
| 3200    | 148       | 10.69%  |
| 1333    | 117       | 8.45%   |
| 2133    | 92        | 6.65%   |
| 2400    | 78        | 5.64%   |
| 3600    | 52        | 3.76%   |
| 1334    | 44        | 3.18%   |
| 800     | 42        | 3.03%   |
| 1867    | 36        | 2.6%    |
| 667     | 32        | 2.31%   |
| 1067    | 21        | 1.52%   |
| 4267    | 19        | 1.37%   |
| 3400    | 18        | 1.3%    |
| Unknown | 18        | 1.3%    |
| 3000    | 17        | 1.23%   |
| 3466    | 15        | 1.08%   |
| 1066    | 13        | 0.94%   |
| 4800    | 12        | 0.87%   |
| 1866    | 12        | 0.87%   |
| 3266    | 10        | 0.72%   |
| 3733    | 8         | 0.58%   |
| 2666    | 8         | 0.58%   |
| 8400    | 7         | 0.51%   |
| 2933    | 7         | 0.51%   |
| 3866    | 6         | 0.43%   |
| 6400    | 5         | 0.36%   |
| 3800    | 5         | 0.36%   |
| 3100    | 5         | 0.36%   |
| 2800    | 5         | 0.36%   |
| 2048    | 5         | 0.36%   |
| 400     | 5         | 0.36%   |
| 3500    | 4         | 0.29%   |
| 533     | 4         | 0.29%   |
| 4000    | 3         | 0.22%   |
| 1800    | 3         | 0.22%   |
| 933     | 3         | 0.22%   |
| 333     | 3         | 0.22%   |
| 49926   | 2         | 0.14%   |
| 4266    | 2         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Brother Industries     | 26        | 25.49%  |
| Hewlett-Packard        | 25        | 24.51%  |
| Canon                  | 17        | 16.67%  |
| Fuji Xerox             | 7         | 6.86%   |
| Samsung Electronics    | 6         | 5.88%   |
| Prolific Technology    | 6         | 5.88%   |
| Seiko Epson            | 5         | 4.9%    |
| Lexmark International  | 2         | 1.96%   |
| Dymo-CoStar            | 2         | 1.96%   |
| Zebra                  | 1         | 0.98%   |
| Xerox                  | 1         | 0.98%   |
| Ricoh                  | 1         | 0.98%   |
| Kyocera                | 1         | 0.98%   |
| Custom Engineering SPA | 1         | 0.98%   |
| BIXOLON                | 1         | 0.98%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer           | 8         | 7.69%   |
| Prolific PL2305 Parallel Port                | 6         | 5.77%   |
| Brother HL-2130 series                       | 5         | 4.81%   |
| HP DeskJet 2130 series                       | 4         | 3.85%   |
| Fuji Xerox DocuPrint CM215 fw                | 3         | 2.88%   |
| Brother HL-1110 series                       | 3         | 2.88%   |
| HP ENVY 5000 series                          | 2         | 1.92%   |
| HP DeskJet F2100 Printer series              | 2         | 1.92%   |
| HP DeskJet 3630 series                       | 2         | 1.92%   |
| Canon TS3100 series                          | 2         | 1.92%   |
| Canon TR8500 series                          | 2         | 1.92%   |
| Canon PIXMA MX920 Series                     | 2         | 1.92%   |
| Canon PIXMA MG2500 Series                    | 2         | 1.92%   |
| Canon MG5600 series                          | 2         | 1.92%   |
| Brother MFC-L8690CDW series                  | 2         | 1.92%   |
| Brother HL-L3230CDW series                   | 2         | 1.92%   |
| Zebra ZTC LP2844-Z-200dpi                    | 1         | 0.96%   |
| Xerox Phaser 8400N                           | 1         | 0.96%   |
| Seiko Epson XP-4100 Series                   | 1         | 0.96%   |
| Seiko Epson XP-243 245 247 Series            | 1         | 0.96%   |
| Seiko Epson WF-5190 Series                   | 1         | 0.96%   |
| Seiko Epson TM-T20                           | 1         | 0.96%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.96%   |
| Samsung ML-2010P Mono Laser Printer          | 1         | 0.96%   |
| Samsung ML-1865                              | 1         | 0.96%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 0.96%   |
| Samsung ML-1450                              | 1         | 0.96%   |
| Samsung M267x 287x Series                    | 1         | 0.96%   |
| Samsung M2020 Series                         | 1         | 0.96%   |
| Ricoh Printer                                | 1         | 0.96%   |
| Lexmark International Lexmark E260dn         | 1         | 0.96%   |
| Lexmark International CX410de                | 1         | 0.96%   |
| Kyocera FS-1100                              | 1         | 0.96%   |
| HP OfficeJet 5200 series                     | 1         | 0.96%   |
| HP LaserJet Professional P 1102w             | 1         | 0.96%   |
| HP ENVY Photo 7100 series                    | 1         | 0.96%   |
| HP ENVY 4520 series                          | 1         | 0.96%   |
| HP Deskjet 3520 series                       | 1         | 0.96%   |
| HP DeskJet 2300 series                       | 1         | 0.96%   |
| HP Deskjet 1050 J410                         | 1         | 0.96%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 9         | 60%     |
| Seiko Epson    | 4         | 26.67%  |
| Syscan         | 1         | 6.67%   |
| Mustek Systems | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                  | 2         | 13.33%  |
| Canon CanoScan LiDE 210                                 | 2         | 13.33%  |
| Syscan TravelScan 460/464                               | 1         | 6.67%   |
| Seiko Epson Scanner                                     | 1         | 6.67%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 6.67%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 6.67%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 6.67%   |
| Mustek Systems BearPaw 2448 TA Plus                     | 1         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 6.67%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 6.67%   |
| Canon CanoScan LiDE 220                                 | 1         | 6.67%   |
| Canon CanoScan LiDE 200                                 | 1         | 6.67%   |
| Canon CanoScan LiDE 110                                 | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 320       | 21.59%  |
| Logitech                               | 143       | 9.65%   |
| Microdia                               | 124       | 8.37%   |
| Realtek Semiconductor                  | 118       | 7.96%   |
| Apple                                  | 106       | 7.15%   |
| Sunplus Innovation Technology          | 101       | 6.82%   |
| IMC Networks                           | 97        | 6.55%   |
| Acer                                   | 75        | 5.06%   |
| Quanta                                 | 53        | 3.58%   |
| Suyin                                  | 47        | 3.17%   |
| Cheng Uei Precision Industry (Foxlink) | 47        | 3.17%   |
| Microsoft                              | 36        | 2.43%   |
| Lite-On Technology                     | 26        | 1.75%   |
| Syntek                                 | 20        | 1.35%   |
| Samsung Electronics                    | 20        | 1.35%   |
| Luxvisions Innotech Limited            | 11        | 0.74%   |
| Silicon Motion                         | 10        | 0.67%   |
| Importek                               | 10        | 0.67%   |
| Ricoh                                  | 9         | 0.61%   |
| Lenovo                                 | 9         | 0.61%   |
| Alcor Micro                            | 8         | 0.54%   |
| Primax Electronics                     | 7         | 0.47%   |
| GEMBIRD                                | 7         | 0.47%   |
| Razer USA                              | 6         | 0.4%    |
| LG Electronics                         | 5         | 0.34%   |
| Generalplus Technology                 | 5         | 0.34%   |
| OmniVision Technologies                | 4         | 0.27%   |
| Magic Control Technology               | 4         | 0.27%   |
| Genesys Logic                          | 4         | 0.27%   |
| DigiTech                               | 4         | 0.27%   |
| Cubeternet                             | 4         | 0.27%   |
| Z-Star Microelectronics                | 3         | 0.2%    |
| Sonix Technology                       | 3         | 0.2%    |
| ALi                                    | 3         | 0.2%    |
| USB Camera                             | 2         | 0.13%   |
| Unknown                                | 2         | 0.13%   |
| SunplusIT                              | 2         | 0.13%   |
| HD 2MP WEBCAM                          | 2         | 0.13%   |
| Asuscom Network                        | 2         | 0.13%   |
| Tobii Technology AB                    | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 62        | 4.1%    |
| Chicony Integrated Camera                               | 47        | 3.11%   |
| Realtek Integrated_Webcam_HD                            | 36        | 2.38%   |
| Apple FaceTime HD Camera (Built-in)                     | 32        | 2.12%   |
| Apple iPhone5/5C/5S/6                                   | 29        | 1.92%   |
| IMC Networks Integrated Camera                          | 28        | 1.85%   |
| Chicony TOSHIBA Web Camera - HD                         | 25        | 1.65%   |
| Apple Built-in iSight                                   | 25        | 1.65%   |
| Sunplus Integrated_Webcam_HD                            | 24        | 1.59%   |
| Chicony HD WebCam                                       | 24        | 1.59%   |
| Acer Integrated Camera                                  | 24        | 1.59%   |
| Samsung Galaxy A5 (MTP)                                 | 20        | 1.32%   |
| Logitech HD Pro Webcam C920                             | 20        | 1.32%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 20        | 1.32%   |
| Realtek USB Camera                                      | 19        | 1.26%   |
| Logitech Webcam C270                                    | 18        | 1.19%   |
| Syntek Integrated Camera                                | 15        | 0.99%   |
| Chicony HP TrueVision HD Camera                         | 15        | 0.99%   |
| Chicony USB 2.0 Camera                                  | 14        | 0.93%   |
| Chicony HP HD Camera                                    | 14        | 0.93%   |
| Sunplus HD WebCam                                       | 13        | 0.86%   |
| Chicony HP Truevision HD                                | 13        | 0.86%   |
| Apple FaceTime HD Camera                                | 13        | 0.86%   |
| Logitech C922 Pro Stream Webcam                         | 12        | 0.79%   |
| Chicony HD User Facing                                  | 12        | 0.79%   |
| Quanta HD User Facing                                   | 11        | 0.73%   |
| Microsoft LifeCam HD-3000                               | 11        | 0.73%   |
| Logitech Webcam C930e                                   | 11        | 0.73%   |
| Lite-On Integrated Camera                               | 11        | 0.73%   |
| Chicony USB2.0 Camera                                   | 11        | 0.73%   |
| Acer EasyCamera                                         | 11        | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 10        | 0.66%   |
| Microdia Integrated Webcam                              | 9         | 0.6%    |
| Logitech Webcam C170                                    | 9         | 0.6%    |
| Chicony EasyCamera                                      | 9         | 0.6%    |
| Chicony CNF9055 Toshiba Webcam                          | 9         | 0.6%    |
| Suyin HP Truevision HD                                  | 8         | 0.53%   |
| Quanta HP TrueVision HD Camera                          | 8         | 0.53%   |
| Quanta HD Webcam                                        | 8         | 0.53%   |
| Microdia Integrated_Webcam_FHD                          | 8         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 110       | 39.43%  |
| Synaptics                  | 72        | 25.81%  |
| Shenzhen Goodix Technology | 34        | 12.19%  |
| LighTuning Technology      | 18        | 6.45%   |
| AuthenTec                  | 14        | 5.02%   |
| Upek                       | 12        | 4.3%    |
| Elan Microelectronics      | 12        | 4.3%    |
| STMicroelectronics         | 6         | 2.15%   |
| Focal-systems.Corp         | 1         | 0.36%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 7.53%   |
| Unknown                                                                    | 21        | 7.53%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 6.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 5.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 4.3%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 4.3%    |
| Synaptics  WBDI                                                            | 10        | 3.58%   |
| Shenzhen Goodix  Fingerprint Device                                        | 10        | 3.58%   |
| Validity Sensors VFS491                                                    | 9         | 3.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 3.23%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.23%   |
| Shenzhen Goodix FingerPrint                                                | 9         | 3.23%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 8         | 2.87%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 2.87%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 2.87%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.87%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 7         | 2.51%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.51%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 2.15%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 2.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.15%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.15%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 1.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.79%   |
| Synaptics WBDI Device                                                      | 5         | 1.79%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.79%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.79%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 1.43%   |
| AuthenTec AES1600                                                          | 4         | 1.43%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.08%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.08%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.08%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.08%   |
| AuthenTec AES2810                                                          | 2         | 0.72%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.36%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.36%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.36%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.36%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 31        | 60.78%  |
| Alcor Micro           | 12        | 23.53%  |
| Lenovo                | 3         | 5.88%   |
| Upek                  | 2         | 3.92%   |
| O2 Micro              | 2         | 3.92%   |
| Advanced Card Systems | 1         | 1.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 29.41%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 23.53%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 11.76%  |
| Broadcom 5880                                                                | 5         | 9.8%    |
| Broadcom 58200                                                               | 5         | 9.8%    |
| Lenovo Integrated Smart Card Reader                                          | 3         | 5.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.92%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.92%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1962      | 70.6%   |
| 1     | 676       | 24.33%  |
| 2     | 109       | 3.92%   |
| 3     | 23        | 0.83%   |
| 4     | 8         | 0.29%   |
| 7     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 278       | 29.39%  |
| Graphics card            | 210       | 22.2%   |
| Net/wireless             | 143       | 15.12%  |
| Multimedia controller    | 54        | 5.71%   |
| Chipcard                 | 46        | 4.86%   |
| Communication controller | 44        | 4.65%   |
| Camera                   | 31        | 3.28%   |
| Bluetooth                | 28        | 2.96%   |
| Unassigned class         | 27        | 2.85%   |
| Sound                    | 16        | 1.69%   |
| Net/ethernet             | 16        | 1.69%   |
| Storage                  | 11        | 1.16%   |
| Modem                    | 8         | 0.85%   |
| Dvb card                 | 8         | 0.85%   |
| Network                  | 7         | 0.74%   |
| Card reader              | 7         | 0.74%   |
| Storage/raid             | 3         | 0.32%   |
| Video                    | 2         | 0.21%   |
| Storage/ata              | 2         | 0.21%   |
| Unclassified device      | 1         | 0.11%   |
| Tv card                  | 1         | 0.11%   |
| Storage/nvme             | 1         | 0.11%   |
| Storage/ide              | 1         | 0.11%   |
| Firewire controller      | 1         | 0.11%   |

