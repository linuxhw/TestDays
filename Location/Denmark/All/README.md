Linux in Denmark - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Denmark.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Denmark/Desktop/README.md) and [notebooks](/Location/Denmark/Notebook/README.md).

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

Total: 1536

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Notebook      | N14xWU                      | Notebook    | [0460984dea](https://linux-hardware.org/?probe=0460984dea) | Jan 02, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | Notebook    | [095d9cbf7e](https://linux-hardware.org/?probe=095d9cbf7e) | Jan 01, 2024 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | Desktop     | [080172526c](https://linux-hardware.org/?probe=080172526c) | Dec 31, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [e456132635](https://linux-hardware.org/?probe=e456132635) | Dec 28, 2023 |
| HP            | Compaq 2510p                | Notebook    | [b7b88f9c1c](https://linux-hardware.org/?probe=b7b88f9c1c) | Dec 27, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [344f1c919a](https://linux-hardware.org/?probe=344f1c919a) | Dec 27, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [c55e7a4304](https://linux-hardware.org/?probe=c55e7a4304) | Dec 26, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [fa299ed27d](https://linux-hardware.org/?probe=fa299ed27d) | Dec 26, 2023 |
| MSI           | MS-B090                     | All in one  | [0f3dce1bfb](https://linux-hardware.org/?probe=0f3dce1bfb) | Dec 26, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [fb78f052e1](https://linux-hardware.org/?probe=fb78f052e1) | Dec 25, 2023 |
| Toshiba       | Satellite P850              | Notebook    | [e16f04d074](https://linux-hardware.org/?probe=e16f04d074) | Dec 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [2feb704b34](https://linux-hardware.org/?probe=2feb704b34) | Dec 19, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [31b0444771](https://linux-hardware.org/?probe=31b0444771) | Dec 18, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [987ab63f96](https://linux-hardware.org/?probe=987ab63f96) | Dec 17, 2023 |
| HP            | 829A                        | Mini pc     | [f7866b4175](https://linux-hardware.org/?probe=f7866b4175) | Dec 16, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [2167a2f148](https://linux-hardware.org/?probe=2167a2f148) | Dec 16, 2023 |
| Acer          | Nitro AN715-51              | Notebook    | [279ade4fb0](https://linux-hardware.org/?probe=279ade4fb0) | Dec 16, 2023 |
| Medion        | P7624                       | Notebook    | [4828985ec0](https://linux-hardware.org/?probe=4828985ec0) | Dec 15, 2023 |
| Medion        | P7624                       | Notebook    | [050fbbd613](https://linux-hardware.org/?probe=050fbbd613) | Dec 15, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [a80537094f](https://linux-hardware.org/?probe=a80537094f) | Dec 15, 2023 |
| HP            | 1497                        | Desktop     | [f2951d81c8](https://linux-hardware.org/?probe=f2951d81c8) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [9200b90a95](https://linux-hardware.org/?probe=9200b90a95) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [917471b136](https://linux-hardware.org/?probe=917471b136) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [6c3498a025](https://linux-hardware.org/?probe=6c3498a025) | Dec 12, 2023 |
| Dell          | Latitude E6540              | Notebook    | [0d56fcda0e](https://linux-hardware.org/?probe=0d56fcda0e) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [332492b0c4](https://linux-hardware.org/?probe=332492b0c4) | Dec 11, 2023 |
| Unknown       | TK23D                       | Notebook    | [27c0f3c1f6](https://linux-hardware.org/?probe=27c0f3c1f6) | Dec 07, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [f47146cdb9](https://linux-hardware.org/?probe=f47146cdb9) | Dec 07, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [ff40966f37](https://linux-hardware.org/?probe=ff40966f37) | Dec 04, 2023 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | Notebook    | [151a3ceaf0](https://linux-hardware.org/?probe=151a3ceaf0) | Dec 03, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [a24f117537](https://linux-hardware.org/?probe=a24f117537) | Dec 02, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [109cecbcba](https://linux-hardware.org/?probe=109cecbcba) | Dec 01, 2023 |
| Acer          | Aspire V5-573               | Notebook    | [8a76c8baac](https://linux-hardware.org/?probe=8a76c8baac) | Nov 30, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BE09    | Notebook    | [33b3b8ed10](https://linux-hardware.org/?probe=33b3b8ed10) | Nov 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4c55de5adb](https://linux-hardware.org/?probe=4c55de5adb) | Nov 28, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [760cc39516](https://linux-hardware.org/?probe=760cc39516) | Nov 27, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b305057bc5](https://linux-hardware.org/?probe=b305057bc5) | Nov 27, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [c166853e23](https://linux-hardware.org/?probe=c166853e23) | Nov 26, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [a8e3339ba9](https://linux-hardware.org/?probe=a8e3339ba9) | Nov 26, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [5c10f3d5a1](https://linux-hardware.org/?probe=5c10f3d5a1) | Nov 25, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [05ba5178cb](https://linux-hardware.org/?probe=05ba5178cb) | Nov 25, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [d1e2c905e1](https://linux-hardware.org/?probe=d1e2c905e1) | Nov 25, 2023 |
| Dell          | Studio XPS 1640             | Notebook    | [3b9a32eb3f](https://linux-hardware.org/?probe=3b9a32eb3f) | Nov 24, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [3b995f6b47](https://linux-hardware.org/?probe=3b995f6b47) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | Notebook    | [37a1e3b979](https://linux-hardware.org/?probe=37a1e3b979) | Nov 23, 2023 |
| Gigabyte      | B650M DS3H                  | Notebook    | [dfcb329b5a](https://linux-hardware.org/?probe=dfcb329b5a) | Nov 23, 2023 |
| MSI           | IONA                        | Desktop     | [ccadf6afaf](https://linux-hardware.org/?probe=ccadf6afaf) | Nov 21, 2023 |
| ADLINK Tec... | MXE5400                     | Desktop     | [ae09533003](https://linux-hardware.org/?probe=ae09533003) | Nov 20, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [0d4fe4c2b9](https://linux-hardware.org/?probe=0d4fe4c2b9) | Nov 19, 2023 |
| Sony          | SVE14A2M6EW                 | Notebook    | [9f444d1508](https://linux-hardware.org/?probe=9f444d1508) | Nov 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [049356e4bc](https://linux-hardware.org/?probe=049356e4bc) | Nov 15, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [64cfcced5b](https://linux-hardware.org/?probe=64cfcced5b) | Nov 14, 2023 |
| Intel         | STK2MV64CC H89290-502       | Desktop     | [041670b7d8](https://linux-hardware.org/?probe=041670b7d8) | Nov 13, 2023 |
| HP            | 829A                        | Mini pc     | [54421db755](https://linux-hardware.org/?probe=54421db755) | Nov 12, 2023 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [bdba8f221d](https://linux-hardware.org/?probe=bdba8f221d) | Nov 12, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | Notebook    | [f5f9243038](https://linux-hardware.org/?probe=f5f9243038) | Nov 11, 2023 |
| HP            | Pavilion g7                 | Notebook    | [f963761c30](https://linux-hardware.org/?probe=f963761c30) | Nov 10, 2023 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [5d950043f1](https://linux-hardware.org/?probe=5d950043f1) | Nov 10, 2023 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [0940fc528f](https://linux-hardware.org/?probe=0940fc528f) | Nov 09, 2023 |
| Dell          | Precision M4600             | Notebook    | [0aabbcfa0b](https://linux-hardware.org/?probe=0aabbcfa0b) | Nov 06, 2023 |
| HP            | 1495                        | Desktop     | [fe18b89530](https://linux-hardware.org/?probe=fe18b89530) | Nov 05, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [95f3002643](https://linux-hardware.org/?probe=95f3002643) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [17acb71f9d](https://linux-hardware.org/?probe=17acb71f9d) | Nov 05, 2023 |
| Lenovo        | ThinkPad W550s 20E2000PM... | Notebook    | [1294d54c1a](https://linux-hardware.org/?probe=1294d54c1a) | Nov 04, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | Notebook    | [1d51aba71e](https://linux-hardware.org/?probe=1d51aba71e) | Nov 04, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | Notebook    | [585906fa27](https://linux-hardware.org/?probe=585906fa27) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [bc3444ed2f](https://linux-hardware.org/?probe=bc3444ed2f) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3c1e4ea8bf](https://linux-hardware.org/?probe=3c1e4ea8bf) | Nov 04, 2023 |
| Dell          | Precision 5750              | Notebook    | [00e8468779](https://linux-hardware.org/?probe=00e8468779) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [00a8b74f46](https://linux-hardware.org/?probe=00a8b74f46) | Nov 03, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f54d8e7dea](https://linux-hardware.org/?probe=f54d8e7dea) | Nov 01, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [9a2f1f7750](https://linux-hardware.org/?probe=9a2f1f7750) | Nov 01, 2023 |
| Intel         | NUC11ATBPE M49844-400       | Mini pc     | [78fabfef55](https://linux-hardware.org/?probe=78fabfef55) | Oct 31, 2023 |
| Intel         | NUC11ATBPE M49844-400       | Mini pc     | [623c5e86d7](https://linux-hardware.org/?probe=623c5e86d7) | Oct 31, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [b367027f2a](https://linux-hardware.org/?probe=b367027f2a) | Oct 30, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [949a1ab2bb](https://linux-hardware.org/?probe=949a1ab2bb) | Oct 30, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [e8252549f4](https://linux-hardware.org/?probe=e8252549f4) | Oct 29, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [783a3b6555](https://linux-hardware.org/?probe=783a3b6555) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3b8a5a44c7](https://linux-hardware.org/?probe=3b8a5a44c7) | Oct 21, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [5795100325](https://linux-hardware.org/?probe=5795100325) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a2756e1d2b](https://linux-hardware.org/?probe=a2756e1d2b) | Oct 21, 2023 |
| Packard Be... | IMEDIA S2380                | Desktop     | [905b7ea7f0](https://linux-hardware.org/?probe=905b7ea7f0) | Oct 20, 2023 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | Desktop     | [f824921cbb](https://linux-hardware.org/?probe=f824921cbb) | Oct 17, 2023 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [999de2ca37](https://linux-hardware.org/?probe=999de2ca37) | Oct 16, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [1215db6b88](https://linux-hardware.org/?probe=1215db6b88) | Oct 13, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [e5e897e96a](https://linux-hardware.org/?probe=e5e897e96a) | Oct 09, 2023 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [95ef83d6fd](https://linux-hardware.org/?probe=95ef83d6fd) | Oct 08, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [69383bf7da](https://linux-hardware.org/?probe=69383bf7da) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [81ece14527](https://linux-hardware.org/?probe=81ece14527) | Oct 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b04266e656](https://linux-hardware.org/?probe=b04266e656) | Oct 08, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [c9d4efa819](https://linux-hardware.org/?probe=c9d4efa819) | Oct 07, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [50fc69b25f](https://linux-hardware.org/?probe=50fc69b25f) | Oct 06, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [f68374e7cd](https://linux-hardware.org/?probe=f68374e7cd) | Oct 05, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [8311d775a9](https://linux-hardware.org/?probe=8311d775a9) | Oct 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [1323f200dd](https://linux-hardware.org/?probe=1323f200dd) | Oct 01, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [9c2ba935b9](https://linux-hardware.org/?probe=9c2ba935b9) | Sep 29, 2023 |
| Google        | Lindar                      | Notebook    | [f8f947a025](https://linux-hardware.org/?probe=f8f947a025) | Sep 28, 2023 |
| Google        | Lindar                      | Notebook    | [9ddbc21f0d](https://linux-hardware.org/?probe=9ddbc21f0d) | Sep 28, 2023 |
| Dell          | Latitude 5480               | Notebook    | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| Google        | Droid                       | Notebook    | [fa5f650f3a](https://linux-hardware.org/?probe=fa5f650f3a) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf4e6d50dd](https://linux-hardware.org/?probe=cf4e6d50dd) | Sep 26, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0YE0... | Notebook    | [20c9a90aca](https://linux-hardware.org/?probe=20c9a90aca) | Sep 24, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [726a5f4cf5](https://linux-hardware.org/?probe=726a5f4cf5) | Sep 22, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [d663285ae0](https://linux-hardware.org/?probe=d663285ae0) | Sep 19, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [ad66bafcae](https://linux-hardware.org/?probe=ad66bafcae) | Sep 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [72c4bdf239](https://linux-hardware.org/?probe=72c4bdf239) | Sep 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [fd9d93d90d](https://linux-hardware.org/?probe=fd9d93d90d) | Sep 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [72fe934225](https://linux-hardware.org/?probe=72fe934225) | Sep 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0918609cf3](https://linux-hardware.org/?probe=0918609cf3) | Sep 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [f6467570d4](https://linux-hardware.org/?probe=f6467570d4) | Sep 11, 2023 |
| ASUSTek       | S550CB                      | Notebook    | [dbf2770e09](https://linux-hardware.org/?probe=dbf2770e09) | Sep 10, 2023 |
| ASUSTek       | Strix GL504GM_GL504GM       | Notebook    | [3297d8f0aa](https://linux-hardware.org/?probe=3297d8f0aa) | Sep 10, 2023 |
| Acer          | Aspire X1470                | Desktop     | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | Desktop     | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HH0... | Notebook    | [94c99c8274](https://linux-hardware.org/?probe=94c99c8274) | Sep 06, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [0874ee1444](https://linux-hardware.org/?probe=0874ee1444) | Sep 05, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [1e0b979775](https://linux-hardware.org/?probe=1e0b979775) | Sep 04, 2023 |
| HP            | Pavilion dv9500             | Notebook    | [653fbbb509](https://linux-hardware.org/?probe=653fbbb509) | Sep 04, 2023 |
| ASUSTek       | P5GC-MX                     | Desktop     | [7d13cd846d](https://linux-hardware.org/?probe=7d13cd846d) | Sep 04, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [64026d5e6d](https://linux-hardware.org/?probe=64026d5e6d) | Sep 04, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [0faa734044](https://linux-hardware.org/?probe=0faa734044) | Sep 04, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [b423b914f7](https://linux-hardware.org/?probe=b423b914f7) | Aug 30, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [75ef08524c](https://linux-hardware.org/?probe=75ef08524c) | Aug 30, 2023 |
| Acidanther... | Mac-4B682C642B45593E iMa... | All in one  | [8bd315f814](https://linux-hardware.org/?probe=8bd315f814) | Aug 30, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [52306fce15](https://linux-hardware.org/?probe=52306fce15) | Aug 29, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8b3456ba84](https://linux-hardware.org/?probe=8b3456ba84) | Aug 28, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [484e6e6997](https://linux-hardware.org/?probe=484e6e6997) | Aug 27, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [3f7455be45](https://linux-hardware.org/?probe=3f7455be45) | Aug 27, 2023 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | Desktop     | [595afb8cf0](https://linux-hardware.org/?probe=595afb8cf0) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [569d6b6121](https://linux-hardware.org/?probe=569d6b6121) | Aug 27, 2023 |
| HP            | 1905                        | Desktop     | [f680d1c561](https://linux-hardware.org/?probe=f680d1c561) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [a0c3124b6a](https://linux-hardware.org/?probe=a0c3124b6a) | Aug 27, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [1f5f734faa](https://linux-hardware.org/?probe=1f5f734faa) | Aug 26, 2023 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | Desktop     | [7a89f9b5a7](https://linux-hardware.org/?probe=7a89f9b5a7) | Aug 26, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [c2e1396370](https://linux-hardware.org/?probe=c2e1396370) | Aug 23, 2023 |
| Lenovo        | ThinkPad T460s 20F9003VM... | Notebook    | [e6e076d380](https://linux-hardware.org/?probe=e6e076d380) | Aug 23, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [d68939adcf](https://linux-hardware.org/?probe=d68939adcf) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| HP            | Pavilion dv9500             | Notebook    | [d5cc7639c3](https://linux-hardware.org/?probe=d5cc7639c3) | Aug 21, 2023 |
| Dell          | Latitude E6410              | Notebook    | [5ae66b0d4a](https://linux-hardware.org/?probe=5ae66b0d4a) | Aug 18, 2023 |
| Dell          | Latitude 5540               | Notebook    | [d1f00897b3](https://linux-hardware.org/?probe=d1f00897b3) | Aug 18, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | Notebook    | [0c47627604](https://linux-hardware.org/?probe=0c47627604) | Aug 18, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [70eda3a12d](https://linux-hardware.org/?probe=70eda3a12d) | Aug 18, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a77f908bb5](https://linux-hardware.org/?probe=a77f908bb5) | Aug 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [2cd51b6fce](https://linux-hardware.org/?probe=2cd51b6fce) | Aug 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b326fccb63](https://linux-hardware.org/?probe=b326fccb63) | Aug 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [508611b16c](https://linux-hardware.org/?probe=508611b16c) | Aug 16, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [12e0dbd72c](https://linux-hardware.org/?probe=12e0dbd72c) | Aug 09, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [1aa926149a](https://linux-hardware.org/?probe=1aa926149a) | Aug 09, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [3474fa639e](https://linux-hardware.org/?probe=3474fa639e) | Aug 08, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [150d68269d](https://linux-hardware.org/?probe=150d68269d) | Aug 08, 2023 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [a5eb82b4f9](https://linux-hardware.org/?probe=a5eb82b4f9) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [eb92759c2a](https://linux-hardware.org/?probe=eb92759c2a) | Aug 05, 2023 |
| Dell          | G3 3590                     | Notebook    | [56d5cdc390](https://linux-hardware.org/?probe=56d5cdc390) | Aug 04, 2023 |
| Sony          | SVF1521G1EW                 | Notebook    | [b46b664a9e](https://linux-hardware.org/?probe=b46b664a9e) | Aug 03, 2023 |
| HP            | 844C                        | Desktop     | [36185008dc](https://linux-hardware.org/?probe=36185008dc) | Aug 03, 2023 |
| ASUSTek       | K95VM                       | Notebook    | [1ec08c4cf9](https://linux-hardware.org/?probe=1ec08c4cf9) | Jul 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [3f09ac4cae](https://linux-hardware.org/?probe=3f09ac4cae) | Jul 29, 2023 |
| MSI           | Raider GE78HX 13VI          | Notebook    | [0b179ca997](https://linux-hardware.org/?probe=0b179ca997) | Jul 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS22905    | Notebook    | [f95fe4ced5](https://linux-hardware.org/?probe=f95fe4ced5) | Jul 28, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [8cf3728f9b](https://linux-hardware.org/?probe=8cf3728f9b) | Jul 25, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | Notebook    | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [0a3cc7970c](https://linux-hardware.org/?probe=0a3cc7970c) | Jul 23, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [a3ccd7aece](https://linux-hardware.org/?probe=a3ccd7aece) | Jul 23, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [8744428bf6](https://linux-hardware.org/?probe=8744428bf6) | Jul 23, 2023 |
| Lenovo        | ThinkCentre M58 7360W1J     | Desktop     | [1e1e565ac4](https://linux-hardware.org/?probe=1e1e565ac4) | Jul 23, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [1321d9a034](https://linux-hardware.org/?probe=1321d9a034) | Jul 21, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [7ef01e963d](https://linux-hardware.org/?probe=7ef01e963d) | Jul 21, 2023 |
| Dell          | Precision 7530              | Notebook    | [0d2e753768](https://linux-hardware.org/?probe=0d2e753768) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [26a2238069](https://linux-hardware.org/?probe=26a2238069) | Jul 19, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [9672a393c9](https://linux-hardware.org/?probe=9672a393c9) | Jul 19, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [ea47e53a45](https://linux-hardware.org/?probe=ea47e53a45) | Jul 18, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [14defb538e](https://linux-hardware.org/?probe=14defb538e) | Jul 17, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [ad2c07dc8e](https://linux-hardware.org/?probe=ad2c07dc8e) | Jul 17, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [f440759b5b](https://linux-hardware.org/?probe=f440759b5b) | Jul 17, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [2e7199aa1a](https://linux-hardware.org/?probe=2e7199aa1a) | Jul 17, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [9a14a53c9c](https://linux-hardware.org/?probe=9a14a53c9c) | Jul 16, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [0c4b8e49f8](https://linux-hardware.org/?probe=0c4b8e49f8) | Jul 15, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [1c43d30f02](https://linux-hardware.org/?probe=1c43d30f02) | Jul 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [7573efcc6c](https://linux-hardware.org/?probe=7573efcc6c) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [30d6b8bfde](https://linux-hardware.org/?probe=30d6b8bfde) | Jul 11, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [72af2d01c0](https://linux-hardware.org/?probe=72af2d01c0) | Jul 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [e87ea192ea](https://linux-hardware.org/?probe=e87ea192ea) | Jul 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [4e47f48ca8](https://linux-hardware.org/?probe=4e47f48ca8) | Jul 07, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [382fff8a04](https://linux-hardware.org/?probe=382fff8a04) | Jul 06, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [a8c3d57d88](https://linux-hardware.org/?probe=a8c3d57d88) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [4b2cf13c22](https://linux-hardware.org/?probe=4b2cf13c22) | Jul 03, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [81a034858f](https://linux-hardware.org/?probe=81a034858f) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [a3c2f0155c](https://linux-hardware.org/?probe=a3c2f0155c) | Jun 30, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [ed171ca808](https://linux-hardware.org/?probe=ed171ca808) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c9cbb8f947](https://linux-hardware.org/?probe=c9cbb8f947) | Jun 27, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [46e3ea33a3](https://linux-hardware.org/?probe=46e3ea33a3) | Jun 27, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | Notebook    | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [07d9cc6d71](https://linux-hardware.org/?probe=07d9cc6d71) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [62dd78e250](https://linux-hardware.org/?probe=62dd78e250) | Jun 25, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [5298e132fc](https://linux-hardware.org/?probe=5298e132fc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L480 20LS002YMX    | Notebook    | [9c9702483c](https://linux-hardware.org/?probe=9c9702483c) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fd367d0725](https://linux-hardware.org/?probe=fd367d0725) | Jun 21, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [edf3326608](https://linux-hardware.org/?probe=edf3326608) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [5314aeb7e0](https://linux-hardware.org/?probe=5314aeb7e0) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [fc06bc7209](https://linux-hardware.org/?probe=fc06bc7209) | Jun 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [5bd2521f5c](https://linux-hardware.org/?probe=5bd2521f5c) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | Notebook    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [4d0efefd7c](https://linux-hardware.org/?probe=4d0efefd7c) | Jun 17, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [9ef5114c59](https://linux-hardware.org/?probe=9ef5114c59) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [859f1b3a88](https://linux-hardware.org/?probe=859f1b3a88) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [2aaa4324d0](https://linux-hardware.org/?probe=2aaa4324d0) | Jun 12, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | Notebook    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | Notebook    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [76ca69b8cc](https://linux-hardware.org/?probe=76ca69b8cc) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [3932ac5190](https://linux-hardware.org/?probe=3932ac5190) | Jun 07, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [8f55e469c8](https://linux-hardware.org/?probe=8f55e469c8) | Jun 06, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [933aa24820](https://linux-hardware.org/?probe=933aa24820) | Jun 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [525601c31e](https://linux-hardware.org/?probe=525601c31e) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [72fc2eea56](https://linux-hardware.org/?probe=72fc2eea56) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | Notebook    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [b27125a1e2](https://linux-hardware.org/?probe=b27125a1e2) | Jun 02, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [24ccc7665f](https://linux-hardware.org/?probe=24ccc7665f) | Jun 01, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [af6c8f3355](https://linux-hardware.org/?probe=af6c8f3355) | Jun 01, 2023 |
| ASUSTek       | 1225B                       | Notebook    | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [9131b2b568](https://linux-hardware.org/?probe=9131b2b568) | May 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [742ae62ba6](https://linux-hardware.org/?probe=742ae62ba6) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [c507b25480](https://linux-hardware.org/?probe=c507b25480) | May 30, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [227930e25d](https://linux-hardware.org/?probe=227930e25d) | May 29, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [807dd44df4](https://linux-hardware.org/?probe=807dd44df4) | May 28, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | Notebook    | [4147fc8cb7](https://linux-hardware.org/?probe=4147fc8cb7) | May 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | Notebook    | [d9295f37bc](https://linux-hardware.org/?probe=d9295f37bc) | May 27, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [c2b6ba6654](https://linux-hardware.org/?probe=c2b6ba6654) | May 23, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [3740264eb0](https://linux-hardware.org/?probe=3740264eb0) | May 23, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [bc2b7d421d](https://linux-hardware.org/?probe=bc2b7d421d) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [97687a73c3](https://linux-hardware.org/?probe=97687a73c3) | May 22, 2023 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [848d0db1b2](https://linux-hardware.org/?probe=848d0db1b2) | May 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [9419d4d25c](https://linux-hardware.org/?probe=9419d4d25c) | May 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [f48dba1e04](https://linux-hardware.org/?probe=f48dba1e04) | May 16, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [72ba449391](https://linux-hardware.org/?probe=72ba449391) | May 13, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a712c6b44a](https://linux-hardware.org/?probe=a712c6b44a) | May 13, 2023 |
| Lenovo        | ThinkPad P50 20EN0037MD     | Notebook    | [f1a58d3a7f](https://linux-hardware.org/?probe=f1a58d3a7f) | May 11, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [d21ea25d7a](https://linux-hardware.org/?probe=d21ea25d7a) | May 10, 2023 |
| Lenovo        | ThinkPad T550 20CJS0AP00    | Notebook    | [f628b12917](https://linux-hardware.org/?probe=f628b12917) | May 10, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [b65333ae05](https://linux-hardware.org/?probe=b65333ae05) | May 10, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [9caca8f4cc](https://linux-hardware.org/?probe=9caca8f4cc) | May 10, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c8ab230418](https://linux-hardware.org/?probe=c8ab230418) | May 08, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [d4b401ef3f](https://linux-hardware.org/?probe=d4b401ef3f) | May 06, 2023 |
| HP            | ProBook 6570b               | Notebook    | [d240b443c4](https://linux-hardware.org/?probe=d240b443c4) | May 06, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [ecdd99c704](https://linux-hardware.org/?probe=ecdd99c704) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | Notebook    | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Acidanther... | Mac-4B682C642B45593E iMa... | All in one  | [5ff8444666](https://linux-hardware.org/?probe=5ff8444666) | May 04, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [6cb7429ec6](https://linux-hardware.org/?probe=6cb7429ec6) | May 02, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [11e8fb1ecd](https://linux-hardware.org/?probe=11e8fb1ecd) | May 02, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [2675aa56c4](https://linux-hardware.org/?probe=2675aa56c4) | May 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [ff448e32c3](https://linux-hardware.org/?probe=ff448e32c3) | Apr 29, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| Lenovo        | ThinkPad X250 20CLA003TA    | Notebook    | [ea8109c2a7](https://linux-hardware.org/?probe=ea8109c2a7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | Notebook    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| Lenovo        | ThinkPad T520 4243W4L       | Notebook    | [bcdd9e5f74](https://linux-hardware.org/?probe=bcdd9e5f74) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | Notebook    | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [b003b5c775](https://linux-hardware.org/?probe=b003b5c775) | Apr 22, 2023 |
| HP            | 339A                        | Desktop     | [1be48a395d](https://linux-hardware.org/?probe=1be48a395d) | Apr 21, 2023 |
| Acer          | Aspire XC-230               | Desktop     | [d31e8d7c7d](https://linux-hardware.org/?probe=d31e8d7c7d) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ebdd0f2a6a](https://linux-hardware.org/?probe=ebdd0f2a6a) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [1e8a2bbf1d](https://linux-hardware.org/?probe=1e8a2bbf1d) | Apr 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [0ec2388253](https://linux-hardware.org/?probe=0ec2388253) | Apr 18, 2023 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | Desktop     | [878d249691](https://linux-hardware.org/?probe=878d249691) | Apr 18, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [245db62c73](https://linux-hardware.org/?probe=245db62c73) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [a196246f09](https://linux-hardware.org/?probe=a196246f09) | Apr 17, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [ad23efbf03](https://linux-hardware.org/?probe=ad23efbf03) | Apr 14, 2023 |
| HP            | 339A                        | Desktop     | [57e1af32cd](https://linux-hardware.org/?probe=57e1af32cd) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1bf207dfca](https://linux-hardware.org/?probe=1bf207dfca) | Apr 13, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [4d84f3549a](https://linux-hardware.org/?probe=4d84f3549a) | Apr 13, 2023 |
| Lenovo        | ThinkPad W541 20EGS03800    | Notebook    | [4be9d98954](https://linux-hardware.org/?probe=4be9d98954) | Apr 11, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [51b13ad2b6](https://linux-hardware.org/?probe=51b13ad2b6) | Apr 11, 2023 |
| eMachines     | E725                        | Notebook    | [758d0c86b2](https://linux-hardware.org/?probe=758d0c86b2) | Apr 06, 2023 |
| Acer          | Aspire E5-771               | Notebook    | [2ef87c5f77](https://linux-hardware.org/?probe=2ef87c5f77) | Apr 06, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [d12cbc4044](https://linux-hardware.org/?probe=d12cbc4044) | Apr 06, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [87b536f504](https://linux-hardware.org/?probe=87b536f504) | Apr 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [3f9238067d](https://linux-hardware.org/?probe=3f9238067d) | Apr 04, 2023 |
| Dell          | Latitude 7480               | Notebook    | [f1ca485181](https://linux-hardware.org/?probe=f1ca485181) | Apr 02, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [d873632b2b](https://linux-hardware.org/?probe=d873632b2b) | Apr 01, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [32c138c982](https://linux-hardware.org/?probe=32c138c982) | Mar 31, 2023 |
| HP            | 3398                        | Desktop     | [ed9f84a231](https://linux-hardware.org/?probe=ed9f84a231) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d1e1b40549](https://linux-hardware.org/?probe=d1e1b40549) | Mar 28, 2023 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [21cf1ad0bb](https://linux-hardware.org/?probe=21cf1ad0bb) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4236W1K       | Notebook    | [e093aace6e](https://linux-hardware.org/?probe=e093aace6e) | Mar 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bcd49e85cb](https://linux-hardware.org/?probe=bcd49e85cb) | Mar 27, 2023 |
| Lenovo        | ThinkPad L530 24812SG       | Notebook    | [163d4e376e](https://linux-hardware.org/?probe=163d4e376e) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | Desktop     | [479aff4877](https://linux-hardware.org/?probe=479aff4877) | Mar 26, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [438f4cb9d9](https://linux-hardware.org/?probe=438f4cb9d9) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | Desktop     | [67ddc813cf](https://linux-hardware.org/?probe=67ddc813cf) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [c722a5f7b2](https://linux-hardware.org/?probe=c722a5f7b2) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [56854770ba](https://linux-hardware.org/?probe=56854770ba) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [62a95efc48](https://linux-hardware.org/?probe=62a95efc48) | Mar 23, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [3d591cd190](https://linux-hardware.org/?probe=3d591cd190) | Mar 21, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [b133c68356](https://linux-hardware.org/?probe=b133c68356) | Mar 20, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| Acer          | Extensa 7620                | Notebook    | [59bb9967c2](https://linux-hardware.org/?probe=59bb9967c2) | Mar 19, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8681f176da](https://linux-hardware.org/?probe=8681f176da) | Mar 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [ccfa4fb30e](https://linux-hardware.org/?probe=ccfa4fb30e) | Mar 17, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | Notebook    | [4012d2fb1f](https://linux-hardware.org/?probe=4012d2fb1f) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [f3bb3c5ef1](https://linux-hardware.org/?probe=f3bb3c5ef1) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fc7d8aee1f](https://linux-hardware.org/?probe=fc7d8aee1f) | Mar 16, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | Notebook    | [f2f8796262](https://linux-hardware.org/?probe=f2f8796262) | Mar 16, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0AF00    | Notebook    | [fe02ac3290](https://linux-hardware.org/?probe=fe02ac3290) | Mar 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [b3ac863457](https://linux-hardware.org/?probe=b3ac863457) | Mar 15, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [e41f3ed4ab](https://linux-hardware.org/?probe=e41f3ed4ab) | Mar 13, 2023 |
| Samsung       | NP770                       | Notebook    | [ab2677e28e](https://linux-hardware.org/?probe=ab2677e28e) | Mar 12, 2023 |
| Acer          | Aspire X1935                | Desktop     | [6846ecd490](https://linux-hardware.org/?probe=6846ecd490) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [e5f5d4a3d5](https://linux-hardware.org/?probe=e5f5d4a3d5) | Mar 11, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [d3ac8dd45f](https://linux-hardware.org/?probe=d3ac8dd45f) | Mar 11, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a3a369de93](https://linux-hardware.org/?probe=a3a369de93) | Mar 08, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [8995f4a3b0](https://linux-hardware.org/?probe=8995f4a3b0) | Mar 08, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [fd33b65218](https://linux-hardware.org/?probe=fd33b65218) | Mar 04, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [80720d46a2](https://linux-hardware.org/?probe=80720d46a2) | Mar 03, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [dd01af3afe](https://linux-hardware.org/?probe=dd01af3afe) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | Notebook    | [38623506fd](https://linux-hardware.org/?probe=38623506fd) | Mar 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [05e7af9004](https://linux-hardware.org/?probe=05e7af9004) | Mar 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [63863d9f0c](https://linux-hardware.org/?probe=63863d9f0c) | Feb 27, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3d8c3db030](https://linux-hardware.org/?probe=3d8c3db030) | Feb 26, 2023 |
| HP            | 3032h                       | Desktop     | [007bbeffa0](https://linux-hardware.org/?probe=007bbeffa0) | Feb 26, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [ea6777bf2d](https://linux-hardware.org/?probe=ea6777bf2d) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [7380033a44](https://linux-hardware.org/?probe=7380033a44) | Feb 22, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [ce7bdb1ddf](https://linux-hardware.org/?probe=ce7bdb1ddf) | Feb 21, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [0dd1f15a92](https://linux-hardware.org/?probe=0dd1f15a92) | Feb 21, 2023 |
| HP            | 1497                        | Desktop     | [47ffeac7cf](https://linux-hardware.org/?probe=47ffeac7cf) | Feb 20, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [9f6834d4a9](https://linux-hardware.org/?probe=9f6834d4a9) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [131f8f99a2](https://linux-hardware.org/?probe=131f8f99a2) | Feb 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [5fd9a2f9c5](https://linux-hardware.org/?probe=5fd9a2f9c5) | Feb 17, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [01355a0714](https://linux-hardware.org/?probe=01355a0714) | Feb 17, 2023 |
| HP            | Notebook                    | Notebook    | [682935bcda](https://linux-hardware.org/?probe=682935bcda) | Feb 16, 2023 |
| HP            | Notebook                    | Notebook    | [1ea98ae976](https://linux-hardware.org/?probe=1ea98ae976) | Feb 16, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [aa3655a17e](https://linux-hardware.org/?probe=aa3655a17e) | Feb 15, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [36f57d56f8](https://linux-hardware.org/?probe=36f57d56f8) | Feb 15, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [b744809cc2](https://linux-hardware.org/?probe=b744809cc2) | Feb 14, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [20c0b96948](https://linux-hardware.org/?probe=20c0b96948) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [92cbb2e876](https://linux-hardware.org/?probe=92cbb2e876) | Feb 11, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [dea7831935](https://linux-hardware.org/?probe=dea7831935) | Feb 10, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a55211363f](https://linux-hardware.org/?probe=a55211363f) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| HP            | Notebook                    | Notebook    | [eb0699bb89](https://linux-hardware.org/?probe=eb0699bb89) | Feb 07, 2023 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [a527005a2a](https://linux-hardware.org/?probe=a527005a2a) | Feb 06, 2023 |
| HP            | Pavilion g7                 | Notebook    | [e64e08ebd4](https://linux-hardware.org/?probe=e64e08ebd4) | Feb 05, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [4d007a868e](https://linux-hardware.org/?probe=4d007a868e) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [29dc75351d](https://linux-hardware.org/?probe=29dc75351d) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [54d35f2b7f](https://linux-hardware.org/?probe=54d35f2b7f) | Feb 03, 2023 |
| Lenovo        | ThinkPad L380 20M5S09Y00    | Notebook    | [5a7e90c12d](https://linux-hardware.org/?probe=5a7e90c12d) | Feb 03, 2023 |
| HP            | 1905                        | Desktop     | [9ddf75323e](https://linux-hardware.org/?probe=9ddf75323e) | Feb 03, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5ce1aa97c6](https://linux-hardware.org/?probe=5ce1aa97c6) | Feb 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [28f4fb8e15](https://linux-hardware.org/?probe=28f4fb8e15) | Feb 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [ab57658c86](https://linux-hardware.org/?probe=ab57658c86) | Jan 31, 2023 |
| Lenovo        | ThinkPad L380 20M5S09Y00    | Notebook    | [2326ffc032](https://linux-hardware.org/?probe=2326ffc032) | Jan 31, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [ef9c1299e6](https://linux-hardware.org/?probe=ef9c1299e6) | Jan 30, 2023 |
| HP            | Laptop 14-bp0xx             | Notebook    | [68d8a60823](https://linux-hardware.org/?probe=68d8a60823) | Jan 27, 2023 |
| Standard      | Unknown                     | Notebook    | [d9a5e68741](https://linux-hardware.org/?probe=d9a5e68741) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [78b817b650](https://linux-hardware.org/?probe=78b817b650) | Jan 24, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [f9882955cb](https://linux-hardware.org/?probe=f9882955cb) | Jan 24, 2023 |
| Lenovo        | ThinkPad W541 20EF0020MD    | Notebook    | [fca73ad2a9](https://linux-hardware.org/?probe=fca73ad2a9) | Jan 24, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [96a5ca6b92](https://linux-hardware.org/?probe=96a5ca6b92) | Jan 23, 2023 |
| System76      | Darter UltraThin            | Notebook    | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Google        | Phaser                      | Notebook    | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| Lenovo        | ThinkPad X230 2325AS7       | Notebook    | [71a521018d](https://linux-hardware.org/?probe=71a521018d) | Jan 19, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [a7ac9067b0](https://linux-hardware.org/?probe=a7ac9067b0) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [fd99b07929](https://linux-hardware.org/?probe=fd99b07929) | Jan 18, 2023 |
| ASUSTek       | S301LA                      | Notebook    | [c45b4758ed](https://linux-hardware.org/?probe=c45b4758ed) | Jan 18, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [ef2fdd351c](https://linux-hardware.org/?probe=ef2fdd351c) | Jan 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [138f888e23](https://linux-hardware.org/?probe=138f888e23) | Jan 15, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [286de51ef8](https://linux-hardware.org/?probe=286de51ef8) | Jan 13, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [fcda893618](https://linux-hardware.org/?probe=fcda893618) | Jan 13, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [a39184ad9b](https://linux-hardware.org/?probe=a39184ad9b) | Jan 13, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [ccc420a65a](https://linux-hardware.org/?probe=ccc420a65a) | Jan 13, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [2f95543d62](https://linux-hardware.org/?probe=2f95543d62) | Jan 11, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | Desktop     | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [e68c76cbee](https://linux-hardware.org/?probe=e68c76cbee) | Jan 07, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [26826e3c23](https://linux-hardware.org/?probe=26826e3c23) | Jan 04, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [bc17e3a0f4](https://linux-hardware.org/?probe=bc17e3a0f4) | Jan 04, 2023 |
| Medion        | P7621                       | Notebook    | [6ce2ef1abc](https://linux-hardware.org/?probe=6ce2ef1abc) | Jan 03, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [65c34944ec](https://linux-hardware.org/?probe=65c34944ec) | Jan 03, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [8d017ea6af](https://linux-hardware.org/?probe=8d017ea6af) | Jan 01, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [aebeaf8b5e](https://linux-hardware.org/?probe=aebeaf8b5e) | Jan 01, 2023 |
| Notebook      | P17SM                       | Notebook    | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [a01c19a34d](https://linux-hardware.org/?probe=a01c19a34d) | Dec 29, 2022 |
| GPD           | WIN2                        | Notebook    | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [5a5ee8db71](https://linux-hardware.org/?probe=5a5ee8db71) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [196d570869](https://linux-hardware.org/?probe=196d570869) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [148add29a4](https://linux-hardware.org/?probe=148add29a4) | Dec 24, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [da48bed048](https://linux-hardware.org/?probe=da48bed048) | Dec 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [5c07d82410](https://linux-hardware.org/?probe=5c07d82410) | Dec 23, 2022 |
| MSI           | GP65 Leopard 9SE            | Notebook    | [7b980fbd8f](https://linux-hardware.org/?probe=7b980fbd8f) | Dec 21, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [97d8552a67](https://linux-hardware.org/?probe=97d8552a67) | Dec 21, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [c4719bd0ac](https://linux-hardware.org/?probe=c4719bd0ac) | Dec 21, 2022 |
| Medion        | P7621                       | Notebook    | [eced009b2a](https://linux-hardware.org/?probe=eced009b2a) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | Notebook    | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e964534175](https://linux-hardware.org/?probe=e964534175) | Dec 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [d367461182](https://linux-hardware.org/?probe=d367461182) | Dec 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [95aca2679a](https://linux-hardware.org/?probe=95aca2679a) | Dec 14, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ea3dbee733](https://linux-hardware.org/?probe=ea3dbee733) | Dec 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [441dc6d8a0](https://linux-hardware.org/?probe=441dc6d8a0) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [be36edb132](https://linux-hardware.org/?probe=be36edb132) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [491b8d0b8f](https://linux-hardware.org/?probe=491b8d0b8f) | Dec 11, 2022 |
| Lenovo        | ThinkPad Z61m 94503HG       | Notebook    | [4131ed9268](https://linux-hardware.org/?probe=4131ed9268) | Dec 11, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [4686ea3469](https://linux-hardware.org/?probe=4686ea3469) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | Notebook    | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [2473215632](https://linux-hardware.org/?probe=2473215632) | Dec 10, 2022 |
| ASUSTek       | M80CJ-O                     | Desktop     | [2375dfe19f](https://linux-hardware.org/?probe=2375dfe19f) | Dec 10, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [7abcfecd34](https://linux-hardware.org/?probe=7abcfecd34) | Dec 07, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [e5291ae74e](https://linux-hardware.org/?probe=e5291ae74e) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [7a802a74b7](https://linux-hardware.org/?probe=7a802a74b7) | Dec 04, 2022 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [cc6834a359](https://linux-hardware.org/?probe=cc6834a359) | Dec 04, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [6b2389329d](https://linux-hardware.org/?probe=6b2389329d) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [dddc2b5f29](https://linux-hardware.org/?probe=dddc2b5f29) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| Standard      | Unknown                     | Notebook    | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [9282404406](https://linux-hardware.org/?probe=9282404406) | Nov 30, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [687d4d78a4](https://linux-hardware.org/?probe=687d4d78a4) | Nov 29, 2022 |
| Dell          | Inspiron 15 3520            | Notebook    | [7c53fcc73b](https://linux-hardware.org/?probe=7c53fcc73b) | Nov 24, 2022 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [dee6d2a740](https://linux-hardware.org/?probe=dee6d2a740) | Nov 23, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [ec837e35d6](https://linux-hardware.org/?probe=ec837e35d6) | Nov 22, 2022 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [ecafbb7acb](https://linux-hardware.org/?probe=ecafbb7acb) | Nov 20, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9b0f3f926d](https://linux-hardware.org/?probe=9b0f3f926d) | Nov 20, 2022 |
| Lenovo        | ThinkPad T460 20FN004CMD    | Notebook    | [1b7140151d](https://linux-hardware.org/?probe=1b7140151d) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [1cc37489d5](https://linux-hardware.org/?probe=1cc37489d5) | Nov 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ea05374336](https://linux-hardware.org/?probe=ea05374336) | Nov 19, 2022 |
| Acer          | Aspire 5810T                | Notebook    | [2c671f2494](https://linux-hardware.org/?probe=2c671f2494) | Nov 18, 2022 |
| Timi          | TM1607                      | Notebook    | [a93d1611bb](https://linux-hardware.org/?probe=a93d1611bb) | Nov 18, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [de3eac26e1](https://linux-hardware.org/?probe=de3eac26e1) | Nov 18, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [7352c1f1ed](https://linux-hardware.org/?probe=7352c1f1ed) | Nov 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [07b8a83017](https://linux-hardware.org/?probe=07b8a83017) | Nov 17, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [e4401c7591](https://linux-hardware.org/?probe=e4401c7591) | Nov 17, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6af7c2ad85](https://linux-hardware.org/?probe=6af7c2ad85) | Nov 15, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [4c031f5f3b](https://linux-hardware.org/?probe=4c031f5f3b) | Nov 15, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a35952fc68](https://linux-hardware.org/?probe=a35952fc68) | Nov 14, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [48916ecbfa](https://linux-hardware.org/?probe=48916ecbfa) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [270045ffa3](https://linux-hardware.org/?probe=270045ffa3) | Nov 11, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [75ffcfaf88](https://linux-hardware.org/?probe=75ffcfaf88) | Nov 11, 2022 |
| Komplett      | LAPQC71B                    | Notebook    | [b5ee8960c6](https://linux-hardware.org/?probe=b5ee8960c6) | Nov 11, 2022 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [38763f3628](https://linux-hardware.org/?probe=38763f3628) | Nov 11, 2022 |
| MSI           | GV62 8RC                    | Notebook    | [859227b2bb](https://linux-hardware.org/?probe=859227b2bb) | Nov 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7afd10a1a7](https://linux-hardware.org/?probe=7afd10a1a7) | Nov 09, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [a62bf9ed3b](https://linux-hardware.org/?probe=a62bf9ed3b) | Nov 08, 2022 |
| HP            | Notebook                    | Notebook    | [0868a7d110](https://linux-hardware.org/?probe=0868a7d110) | Nov 08, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [de347eb300](https://linux-hardware.org/?probe=de347eb300) | Nov 06, 2022 |
| Lenovo        | ThinkPad T460s 20FAS3CF0... | Notebook    | [2c52a84e7c](https://linux-hardware.org/?probe=2c52a84e7c) | Nov 06, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [9a7d0e6d37](https://linux-hardware.org/?probe=9a7d0e6d37) | Nov 03, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [81a04d40a3](https://linux-hardware.org/?probe=81a04d40a3) | Nov 03, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | Latitude 5280               | Notebook    | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | Notebook    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [f64d3223c5](https://linux-hardware.org/?probe=f64d3223c5) | Oct 24, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [c4fddde4b6](https://linux-hardware.org/?probe=c4fddde4b6) | Oct 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [e21d202e50](https://linux-hardware.org/?probe=e21d202e50) | Oct 22, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| Tactus        | GeoFlex 110                 | Convertible | [42fb435775](https://linux-hardware.org/?probe=42fb435775) | Oct 18, 2022 |
| Acer          | Aspire E5-551               | Notebook    | [9d281c015c](https://linux-hardware.org/?probe=9d281c015c) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | Notebook    | [6c351b94ff](https://linux-hardware.org/?probe=6c351b94ff) | Oct 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [17f73f4f28](https://linux-hardware.org/?probe=17f73f4f28) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [e3f9c7a4f1](https://linux-hardware.org/?probe=e3f9c7a4f1) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Notebook    | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [7221bbf8e7](https://linux-hardware.org/?probe=7221bbf8e7) | Oct 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [87c9436154](https://linux-hardware.org/?probe=87c9436154) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [d3047f6963](https://linux-hardware.org/?probe=d3047f6963) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [6ea648bc51](https://linux-hardware.org/?probe=6ea648bc51) | Sep 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [7c8d5609e0](https://linux-hardware.org/?probe=7c8d5609e0) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [0be5b29760](https://linux-hardware.org/?probe=0be5b29760) | Sep 21, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [5db637f345](https://linux-hardware.org/?probe=5db637f345) | Sep 19, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [f0bbe89fe8](https://linux-hardware.org/?probe=f0bbe89fe8) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [af2f12093c](https://linux-hardware.org/?probe=af2f12093c) | Sep 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e55484acd4](https://linux-hardware.org/?probe=e55484acd4) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | Notebook    | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [865455aae7](https://linux-hardware.org/?probe=865455aae7) | Sep 05, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [de2cfb43d7](https://linux-hardware.org/?probe=de2cfb43d7) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [e5364d8761](https://linux-hardware.org/?probe=e5364d8761) | Sep 01, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [8f7f2e486a](https://linux-hardware.org/?probe=8f7f2e486a) | Aug 30, 2022 |
| HP            | ProBook 6550b               | Notebook    | [662065bfe2](https://linux-hardware.org/?probe=662065bfe2) | Aug 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Gigabyte      | P85-D3                      | Desktop     | [06b934d14f](https://linux-hardware.org/?probe=06b934d14f) | Aug 26, 2022 |
| Unknown       | TB-4000                     | Desktop     | [a3cfbd4659](https://linux-hardware.org/?probe=a3cfbd4659) | Aug 25, 2022 |
| Lenovo        | B50-50 80S2                 | Notebook    | [45f5a72c59](https://linux-hardware.org/?probe=45f5a72c59) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [115ca42bb8](https://linux-hardware.org/?probe=115ca42bb8) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [0ab380f8ac](https://linux-hardware.org/?probe=0ab380f8ac) | Aug 23, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [e5e74eea07](https://linux-hardware.org/?probe=e5e74eea07) | Aug 19, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | Notebook    | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | Desktop     | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| Unknown       | TB-4000                     | Desktop     | [906699e408](https://linux-hardware.org/?probe=906699e408) | Aug 14, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [0009de2dbb](https://linux-hardware.org/?probe=0009de2dbb) | Aug 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [1d97fa15fb](https://linux-hardware.org/?probe=1d97fa15fb) | Aug 08, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | Desktop     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Acer          | Aspire M3-581TG             | Notebook    | [5c73e4c75b](https://linux-hardware.org/?probe=5c73e4c75b) | Aug 05, 2022 |
| Dell          | 0V0D45 A01                  | All in one  | [7d2f0e045d](https://linux-hardware.org/?probe=7d2f0e045d) | Aug 05, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [41189cd175](https://linux-hardware.org/?probe=41189cd175) | Aug 03, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [e6ccfdf23c](https://linux-hardware.org/?probe=e6ccfdf23c) | Jul 31, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | Desktop     | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Packard Be... | H57M01                      | Desktop     | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [83e5824a05](https://linux-hardware.org/?probe=83e5824a05) | Jul 24, 2022 |
| Gigabyte      | MJPLNAB-00                  | Desktop     | [d414e51a0c](https://linux-hardware.org/?probe=d414e51a0c) | Jul 23, 2022 |
| Gigabyte      | MJPLNAB-00                  | Desktop     | [9dcb499f3e](https://linux-hardware.org/?probe=9dcb499f3e) | Jul 23, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [03839f9fef](https://linux-hardware.org/?probe=03839f9fef) | Jul 17, 2022 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [a7f15d1696](https://linux-hardware.org/?probe=a7f15d1696) | Jul 16, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [4d9388058d](https://linux-hardware.org/?probe=4d9388058d) | Jul 12, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [e7cdc97a90](https://linux-hardware.org/?probe=e7cdc97a90) | Jul 11, 2022 |
| MSI           | MS-AF151 100                | All in one  | [cd5a32135a](https://linux-hardware.org/?probe=cd5a32135a) | Jul 07, 2022 |
| MSI           | MS-AF151 100                | All in one  | [55deb5fb81](https://linux-hardware.org/?probe=55deb5fb81) | Jul 07, 2022 |
| Medion        | Iron238KR                   | All in one  | [ff6bf1bc47](https://linux-hardware.org/?probe=ff6bf1bc47) | Jul 07, 2022 |
| Dell          | Latitude 7490               | Notebook    | [b456bca385](https://linux-hardware.org/?probe=b456bca385) | Jul 06, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [a74834b383](https://linux-hardware.org/?probe=a74834b383) | Jul 04, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [0e23c1fc2b](https://linux-hardware.org/?probe=0e23c1fc2b) | Jul 02, 2022 |
| HP            | 805D                        | Desktop     | [3610332b9c](https://linux-hardware.org/?probe=3610332b9c) | Jul 01, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [c12aa3088a](https://linux-hardware.org/?probe=c12aa3088a) | Jun 30, 2022 |
| Lenovo        | ThinkPad T530 24295L4       | Notebook    | [1bdf25550e](https://linux-hardware.org/?probe=1bdf25550e) | Jun 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [b0c272ff93](https://linux-hardware.org/?probe=b0c272ff93) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [6dfa236f76](https://linux-hardware.org/?probe=6dfa236f76) | Jun 18, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| Notebook      | PB50_70DFx,DDx              | Notebook    | [21206dd6bf](https://linux-hardware.org/?probe=21206dd6bf) | Jun 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [527587d2b9](https://linux-hardware.org/?probe=527587d2b9) | Jun 14, 2022 |
| Lenovo        | ThinkPad T550 20CK003HMD    | Notebook    | [ea8155f580](https://linux-hardware.org/?probe=ea8155f580) | Jun 14, 2022 |
| Dell          | Latitude E7440              | Notebook    | [6bbb1944af](https://linux-hardware.org/?probe=6bbb1944af) | Jun 12, 2022 |
| Google        | Babytiger                   | Notebook    | [18f6f97122](https://linux-hardware.org/?probe=18f6f97122) | Jun 12, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [36389b33b6](https://linux-hardware.org/?probe=36389b33b6) | Jun 12, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [d3fdbc7413](https://linux-hardware.org/?probe=d3fdbc7413) | Jun 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [5f1e0dfee7](https://linux-hardware.org/?probe=5f1e0dfee7) | Jun 09, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [bd545aec1b](https://linux-hardware.org/?probe=bd545aec1b) | Jun 09, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [242fc61e3a](https://linux-hardware.org/?probe=242fc61e3a) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [b9a30cba65](https://linux-hardware.org/?probe=b9a30cba65) | Jun 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [a307c95089](https://linux-hardware.org/?probe=a307c95089) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [3c14a5bf10](https://linux-hardware.org/?probe=3c14a5bf10) | Jun 08, 2022 |
| Unknown       | TB-4000                     | Desktop     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [5272429aa9](https://linux-hardware.org/?probe=5272429aa9) | Jun 04, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [dad2acbf49](https://linux-hardware.org/?probe=dad2acbf49) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [af42d8d0b4](https://linux-hardware.org/?probe=af42d8d0b4) | May 27, 2022 |
| Dell          | 09CGW2 A11                  | Server      | [27b873f279](https://linux-hardware.org/?probe=27b873f279) | May 27, 2022 |
| HP            | ProBook 6450b               | Notebook    | [8c35a4c278](https://linux-hardware.org/?probe=8c35a4c278) | May 26, 2022 |
| Dell          | Latitude E7440              | Notebook    | [975715a96b](https://linux-hardware.org/?probe=975715a96b) | May 26, 2022 |
| HP            | ProBook 6450b               | Notebook    | [863987eb13](https://linux-hardware.org/?probe=863987eb13) | May 26, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [94796b9e96](https://linux-hardware.org/?probe=94796b9e96) | May 26, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [60a16a0a17](https://linux-hardware.org/?probe=60a16a0a17) | May 26, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8e0addf4d3](https://linux-hardware.org/?probe=8e0addf4d3) | May 24, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| MSI           | 970A-G43                    | Desktop     | [92dd93dd78](https://linux-hardware.org/?probe=92dd93dd78) | May 24, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [62486fe8d6](https://linux-hardware.org/?probe=62486fe8d6) | May 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f0f481f187](https://linux-hardware.org/?probe=f0f481f187) | May 21, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [49df794b0b](https://linux-hardware.org/?probe=49df794b0b) | May 20, 2022 |
| SLIMBOOK      | PROX14-10                   | Notebook    | [b0d5e9b290](https://linux-hardware.org/?probe=b0d5e9b290) | May 19, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [6efbcdabfc](https://linux-hardware.org/?probe=6efbcdabfc) | May 17, 2022 |
| Lenovo        | ThinkPad T480 20L6S14Y01    | Notebook    | [d3f3fff089](https://linux-hardware.org/?probe=d3f3fff089) | May 16, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [bc9270aeff](https://linux-hardware.org/?probe=bc9270aeff) | May 13, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [f0e5f896a4](https://linux-hardware.org/?probe=f0e5f896a4) | May 11, 2022 |
| Dell          | Precision 5750              | Notebook    | [11e888b7d9](https://linux-hardware.org/?probe=11e888b7d9) | May 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [21486c437b](https://linux-hardware.org/?probe=21486c437b) | May 08, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [591d3fa922](https://linux-hardware.org/?probe=591d3fa922) | May 07, 2022 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [ed538d5b79](https://linux-hardware.org/?probe=ed538d5b79) | May 07, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Dell          | Inspiron 7786               | Convertible | [0ef12447d9](https://linux-hardware.org/?probe=0ef12447d9) | May 02, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [ac5b1123ad](https://linux-hardware.org/?probe=ac5b1123ad) | Apr 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [8694f28b60](https://linux-hardware.org/?probe=8694f28b60) | Apr 25, 2022 |
| MSI           | MS-1T11                     | Desktop     | [9c16a631ef](https://linux-hardware.org/?probe=9c16a631ef) | Apr 23, 2022 |
| MSI           | MS-1T11                     | Desktop     | [e263cd80f5](https://linux-hardware.org/?probe=e263cd80f5) | Apr 23, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [0cd6fe25ec](https://linux-hardware.org/?probe=0cd6fe25ec) | Apr 22, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [1c736596fa](https://linux-hardware.org/?probe=1c736596fa) | Apr 21, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | Desktop     | [91aa85fff9](https://linux-hardware.org/?probe=91aa85fff9) | Apr 21, 2022 |
| Lenovo        | B575e 36852EG               | Notebook    | [8f5e5f427a](https://linux-hardware.org/?probe=8f5e5f427a) | Apr 18, 2022 |
| Lenovo        | B575e 36852EG               | Notebook    | [4731516b58](https://linux-hardware.org/?probe=4731516b58) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440 20B7S1EV00    | Notebook    | [b035e7ae3e](https://linux-hardware.org/?probe=b035e7ae3e) | Apr 16, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5e48e9d93d](https://linux-hardware.org/?probe=5e48e9d93d) | Apr 12, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [27825828c9](https://linux-hardware.org/?probe=27825828c9) | Apr 05, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [2b608bcde8](https://linux-hardware.org/?probe=2b608bcde8) | Apr 04, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ddc3550f6b](https://linux-hardware.org/?probe=ddc3550f6b) | Apr 04, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [e29b4c30f1](https://linux-hardware.org/?probe=e29b4c30f1) | Apr 04, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [67b9d43387](https://linux-hardware.org/?probe=67b9d43387) | Apr 03, 2022 |
| Lenovo        | ThinkPad X390 20Q0002LMX    | Notebook    | [22aaabe433](https://linux-hardware.org/?probe=22aaabe433) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [a5c5028fde](https://linux-hardware.org/?probe=a5c5028fde) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [d978436f5f](https://linux-hardware.org/?probe=d978436f5f) | Apr 03, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [0ba5fd01fa](https://linux-hardware.org/?probe=0ba5fd01fa) | Mar 30, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b9a21aea35](https://linux-hardware.org/?probe=b9a21aea35) | Mar 29, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| Lenovo        | E31-80 80MX                 | Notebook    | [8dc93e34e9](https://linux-hardware.org/?probe=8dc93e34e9) | Mar 25, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [4ce05dd1e2](https://linux-hardware.org/?probe=4ce05dd1e2) | Mar 24, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [3bf42ed5a6](https://linux-hardware.org/?probe=3bf42ed5a6) | Mar 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [72da14a2b2](https://linux-hardware.org/?probe=72da14a2b2) | Mar 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | Notebook    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f3b52d9201](https://linux-hardware.org/?probe=f3b52d9201) | Mar 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5c40bf9192](https://linux-hardware.org/?probe=5c40bf9192) | Mar 21, 2022 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [8be4c394f1](https://linux-hardware.org/?probe=8be4c394f1) | Mar 18, 2022 |
| Gigabyte      | MFLP7IP-00                  | Desktop     | [304c5939e7](https://linux-hardware.org/?probe=304c5939e7) | Mar 18, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [abc4597fe1](https://linux-hardware.org/?probe=abc4597fe1) | Mar 18, 2022 |
| Notebook      | P65xHP                      | Notebook    | [3222aab43a](https://linux-hardware.org/?probe=3222aab43a) | Mar 16, 2022 |
| Shuttle       | X50V2PLUS V1.00             | Desktop     | [0bd650dfff](https://linux-hardware.org/?probe=0bd650dfff) | Mar 16, 2022 |
| Acer          | Aspire 3830T                | Notebook    | [bad3a5c2d7](https://linux-hardware.org/?probe=bad3a5c2d7) | Mar 15, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [ab88a095ac](https://linux-hardware.org/?probe=ab88a095ac) | Mar 10, 2022 |
| Dell          | Latitude E6410              | Notebook    | [d4fa7879a4](https://linux-hardware.org/?probe=d4fa7879a4) | Mar 09, 2022 |
| Dell          | Precision M4800             | Notebook    | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| Dell          | Latitude E6410              | Notebook    | [6748e5a7aa](https://linux-hardware.org/?probe=6748e5a7aa) | Feb 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [30879c05cc](https://linux-hardware.org/?probe=30879c05cc) | Feb 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [500a30847d](https://linux-hardware.org/?probe=500a30847d) | Feb 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [04e8e7704e](https://linux-hardware.org/?probe=04e8e7704e) | Feb 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [505e1dc8cc](https://linux-hardware.org/?probe=505e1dc8cc) | Feb 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c1929d8540](https://linux-hardware.org/?probe=c1929d8540) | Feb 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [bdc86d995a](https://linux-hardware.org/?probe=bdc86d995a) | Feb 21, 2022 |
| Lenovo        | ThinkPad L530 24812SG       | Notebook    | [6eb3e0ed53](https://linux-hardware.org/?probe=6eb3e0ed53) | Feb 19, 2022 |
| Dell          | 0KC9NP A01                  | Desktop     | [f9a0fa24f8](https://linux-hardware.org/?probe=f9a0fa24f8) | Feb 18, 2022 |
| ASRock        | FM2A55M-DGS                 | Desktop     | [efe38992bd](https://linux-hardware.org/?probe=efe38992bd) | Feb 15, 2022 |
| Dell          | 0GTK4K A02                  | Desktop     | [466029e620](https://linux-hardware.org/?probe=466029e620) | Feb 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3971fd709d](https://linux-hardware.org/?probe=3971fd709d) | Feb 13, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [3e75911df8](https://linux-hardware.org/?probe=3e75911df8) | Feb 12, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [b059819620](https://linux-hardware.org/?probe=b059819620) | Feb 11, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [87f4740598](https://linux-hardware.org/?probe=87f4740598) | Feb 11, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [ba6d18935b](https://linux-hardware.org/?probe=ba6d18935b) | Feb 08, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e63f72d407](https://linux-hardware.org/?probe=e63f72d407) | Feb 07, 2022 |
| Medion        | MS-7800                     | Desktop     | [9693a4d35c](https://linux-hardware.org/?probe=9693a4d35c) | Feb 05, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | Notebook    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [23c6243856](https://linux-hardware.org/?probe=23c6243856) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [40ed6ce0c5](https://linux-hardware.org/?probe=40ed6ce0c5) | Feb 04, 2022 |
| Unknown       | TB-4000                     | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Medion        | P7612                       | Notebook    | [e1c076ee06](https://linux-hardware.org/?probe=e1c076ee06) | Feb 03, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [436407f045](https://linux-hardware.org/?probe=436407f045) | Feb 01, 2022 |
| Lenovo        | B50-50 80S2                 | Notebook    | [7602963c65](https://linux-hardware.org/?probe=7602963c65) | Feb 01, 2022 |
| Dell          | Latitude E6540              | Notebook    | [fe6720f0de](https://linux-hardware.org/?probe=fe6720f0de) | Jan 30, 2022 |
| Dell          | Latitude E6540              | Notebook    | [7c972de545](https://linux-hardware.org/?probe=7c972de545) | Jan 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [478d5281bd](https://linux-hardware.org/?probe=478d5281bd) | Jan 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e6ec9b5f6a](https://linux-hardware.org/?probe=e6ec9b5f6a) | Jan 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b8f4a15736](https://linux-hardware.org/?probe=b8f4a15736) | Jan 25, 2022 |
| Medion        | P7612                       | Notebook    | [50be4d531e](https://linux-hardware.org/?probe=50be4d531e) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [82cce77f87](https://linux-hardware.org/?probe=82cce77f87) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| DukaPC        | Notebook                    | Notebook    | [21b4827b4b](https://linux-hardware.org/?probe=21b4827b4b) | Jan 21, 2022 |
| ASUSTek       | P8H67-M                     | Desktop     | [a69dd56657](https://linux-hardware.org/?probe=a69dd56657) | Jan 21, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [221a91f679](https://linux-hardware.org/?probe=221a91f679) | Jan 19, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [1e301a4129](https://linux-hardware.org/?probe=1e301a4129) | Jan 19, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [cc39f1fd96](https://linux-hardware.org/?probe=cc39f1fd96) | Jan 18, 2022 |
| Acer          | Predator G6-710             | Desktop     | [29bdcc72c9](https://linux-hardware.org/?probe=29bdcc72c9) | Jan 18, 2022 |
| ASUSTek       | P8H67-M                     | Desktop     | [1568252a07](https://linux-hardware.org/?probe=1568252a07) | Jan 17, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [4ebb815948](https://linux-hardware.org/?probe=4ebb815948) | Jan 15, 2022 |
| HP            | Pavilion g7                 | Notebook    | [6efd331acf](https://linux-hardware.org/?probe=6efd331acf) | Jan 14, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [4cefa23802](https://linux-hardware.org/?probe=4cefa23802) | Jan 14, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [149c0538ca](https://linux-hardware.org/?probe=149c0538ca) | Jan 13, 2022 |
| Lenovo        | M30-70 80H8                 | Notebook    | [2f61d772a4](https://linux-hardware.org/?probe=2f61d772a4) | Jan 12, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [ab93bc517a](https://linux-hardware.org/?probe=ab93bc517a) | Jan 12, 2022 |
| Razer         | Blade                       | Notebook    | [afad6aaa95](https://linux-hardware.org/?probe=afad6aaa95) | Jan 08, 2022 |
| Gigabyte      | Z68X-UD3-B3                 | Desktop     | [46932917d4](https://linux-hardware.org/?probe=46932917d4) | Jan 08, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [39affa759d](https://linux-hardware.org/?probe=39affa759d) | Jan 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [1f327abc43](https://linux-hardware.org/?probe=1f327abc43) | Jan 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [53a3989606](https://linux-hardware.org/?probe=53a3989606) | Jan 03, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [a7e3940936](https://linux-hardware.org/?probe=a7e3940936) | Jan 02, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [4e1ebc00ff](https://linux-hardware.org/?probe=4e1ebc00ff) | Jan 02, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [8ff352de01](https://linux-hardware.org/?probe=8ff352de01) | Dec 31, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [6246bb8ef6](https://linux-hardware.org/?probe=6246bb8ef6) | Dec 31, 2021 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [290d6b4ad5](https://linux-hardware.org/?probe=290d6b4ad5) | Dec 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c38d256cab](https://linux-hardware.org/?probe=c38d256cab) | Dec 29, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| MSI           | A68HM GRENADE               | Desktop     | [18ca0bdd91](https://linux-hardware.org/?probe=18ca0bdd91) | Dec 27, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [13f35d1d12](https://linux-hardware.org/?probe=13f35d1d12) | Dec 26, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [369d18645c](https://linux-hardware.org/?probe=369d18645c) | Dec 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [e68ec90909](https://linux-hardware.org/?probe=e68ec90909) | Dec 24, 2021 |
| Medion        | P6630                       | Notebook    | [de245dfdb6](https://linux-hardware.org/?probe=de245dfdb6) | Dec 23, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [d683987eea](https://linux-hardware.org/?probe=d683987eea) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [32e8c7ccb2](https://linux-hardware.org/?probe=32e8c7ccb2) | Dec 22, 2021 |
| Notebook      | N24_25JU                    | Notebook    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [1e14543dfd](https://linux-hardware.org/?probe=1e14543dfd) | Dec 18, 2021 |
| Quanta        | MW1/HW1                     | Notebook    | [06bcb3603d](https://linux-hardware.org/?probe=06bcb3603d) | Dec 17, 2021 |
| ASUSTek       | K53SV                       | Notebook    | [be7844ea44](https://linux-hardware.org/?probe=be7844ea44) | Dec 17, 2021 |
| HP            | 3031h                       | Desktop     | [8a8888c824](https://linux-hardware.org/?probe=8a8888c824) | Dec 17, 2021 |
| ABIT          | I-G31                       | Desktop     | [048b7bcf6a](https://linux-hardware.org/?probe=048b7bcf6a) | Dec 13, 2021 |
| Lenovo        | ThinkPad T460s 20FAS05Q0... | Notebook    | [3a4b9beb1d](https://linux-hardware.org/?probe=3a4b9beb1d) | Dec 12, 2021 |
| Dell          | 0YXT71 A01                  | Desktop     | [fbe4f7fdb9](https://linux-hardware.org/?probe=fbe4f7fdb9) | Dec 12, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [99c299c85b](https://linux-hardware.org/?probe=99c299c85b) | Dec 11, 2021 |
| Toshiba       | Satellite P850              | Notebook    | [bfc37f531a](https://linux-hardware.org/?probe=bfc37f531a) | Dec 11, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [6e857bc210](https://linux-hardware.org/?probe=6e857bc210) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [e7144e5f86](https://linux-hardware.org/?probe=e7144e5f86) | Dec 09, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [ac173fd5ba](https://linux-hardware.org/?probe=ac173fd5ba) | Dec 09, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e884cd44db](https://linux-hardware.org/?probe=e884cd44db) | Dec 08, 2021 |
| Fujitsu Si... | LIFEBOOK E8420              | Notebook    | [7ff3493cfe](https://linux-hardware.org/?probe=7ff3493cfe) | Dec 08, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [22f7fc3dbe](https://linux-hardware.org/?probe=22f7fc3dbe) | Dec 04, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [26541caf1e](https://linux-hardware.org/?probe=26541caf1e) | Dec 03, 2021 |
| HP            | 3031h                       | Desktop     | [68cf960e7f](https://linux-hardware.org/?probe=68cf960e7f) | Dec 02, 2021 |
| HP            | 3031h                       | Desktop     | [1c49cd6404](https://linux-hardware.org/?probe=1c49cd6404) | Dec 02, 2021 |
| DukaPC        | Notebook                    | Notebook    | [cfb399153a](https://linux-hardware.org/?probe=cfb399153a) | Dec 01, 2021 |
| HP            | 8299                        | Desktop     | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| HP            | 8299                        | Desktop     | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [0574fefb71](https://linux-hardware.org/?probe=0574fefb71) | Nov 29, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6071fde7dd](https://linux-hardware.org/?probe=6071fde7dd) | Nov 28, 2021 |
| Razer         | Blade Stealth               | Notebook    | [54acf9844b](https://linux-hardware.org/?probe=54acf9844b) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [c224ffa45a](https://linux-hardware.org/?probe=c224ffa45a) | Nov 23, 2021 |
| Acer          | Aspire X3995                | Desktop     | [cde003006d](https://linux-hardware.org/?probe=cde003006d) | Nov 22, 2021 |
| Acer          | Aspire X3995                | Desktop     | [2e97d6ef1c](https://linux-hardware.org/?probe=2e97d6ef1c) | Nov 22, 2021 |
| Toshiba       | Satellite U300              | Notebook    | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ea4842466c](https://linux-hardware.org/?probe=ea4842466c) | Nov 20, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [faf9e68f7a](https://linux-hardware.org/?probe=faf9e68f7a) | Nov 20, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [2b2ea53377](https://linux-hardware.org/?probe=2b2ea53377) | Nov 20, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [b4512f4b54](https://linux-hardware.org/?probe=b4512f4b54) | Nov 18, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [c80aeaf7b0](https://linux-hardware.org/?probe=c80aeaf7b0) | Nov 17, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [53281d6c95](https://linux-hardware.org/?probe=53281d6c95) | Nov 17, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [52eef25506](https://linux-hardware.org/?probe=52eef25506) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [7252f23e5f](https://linux-hardware.org/?probe=7252f23e5f) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [1a20afde4b](https://linux-hardware.org/?probe=1a20afde4b) | Nov 15, 2021 |
| Acer          | Aspire 5810T                | Notebook    | [c41d1671bc](https://linux-hardware.org/?probe=c41d1671bc) | Nov 14, 2021 |
| Lenovo        | ThinkPad R61 8935W7T        | Notebook    | [bef030b1ef](https://linux-hardware.org/?probe=bef030b1ef) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [e03bf03f1d](https://linux-hardware.org/?probe=e03bf03f1d) | Nov 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [1def6bd5d8](https://linux-hardware.org/?probe=1def6bd5d8) | Nov 10, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [10262b5305](https://linux-hardware.org/?probe=10262b5305) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2d7b8c665b](https://linux-hardware.org/?probe=2d7b8c665b) | Nov 09, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [47d8931073](https://linux-hardware.org/?probe=47d8931073) | Nov 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [d2a33ad9d9](https://linux-hardware.org/?probe=d2a33ad9d9) | Nov 07, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Dell          | 0YXT71 A01                  | Desktop     | [6f599a0889](https://linux-hardware.org/?probe=6f599a0889) | Nov 03, 2021 |
| T-bao         | MINI PC V1.0                | Desktop     | [72ce248d0c](https://linux-hardware.org/?probe=72ce248d0c) | Oct 28, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [68ebc1af79](https://linux-hardware.org/?probe=68ebc1af79) | Oct 28, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [be8c7e44de](https://linux-hardware.org/?probe=be8c7e44de) | Oct 23, 2021 |
| MSI           | Z77A-G45                    | Desktop     | [7a31ca9e22](https://linux-hardware.org/?probe=7a31ca9e22) | Oct 23, 2021 |
| Lenovo        | ThinkPad T430s 23561R0      | Notebook    | [bef1593d06](https://linux-hardware.org/?probe=bef1593d06) | Oct 22, 2021 |
| HP            | 1589                        | Desktop     | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | Desktop     | [e1ddc26c5e](https://linux-hardware.org/?probe=e1ddc26c5e) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [14d159c564](https://linux-hardware.org/?probe=14d159c564) | Oct 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [a6e5e7b6ef](https://linux-hardware.org/?probe=a6e5e7b6ef) | Oct 18, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [c0c2de7d52](https://linux-hardware.org/?probe=c0c2de7d52) | Oct 17, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [56f27fef6e](https://linux-hardware.org/?probe=56f27fef6e) | Oct 16, 2021 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [8add857c1a](https://linux-hardware.org/?probe=8add857c1a) | Oct 15, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | Notebook    | [a7fa6a8110](https://linux-hardware.org/?probe=a7fa6a8110) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [df32df0b62](https://linux-hardware.org/?probe=df32df0b62) | Oct 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [c7239a1379](https://linux-hardware.org/?probe=c7239a1379) | Oct 13, 2021 |
| Toshiba       | Satellite P55W-C            | Notebook    | [f16be2ec1b](https://linux-hardware.org/?probe=f16be2ec1b) | Oct 13, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [70d8ac443f](https://linux-hardware.org/?probe=70d8ac443f) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [3d5d3ddf84](https://linux-hardware.org/?probe=3d5d3ddf84) | Oct 09, 2021 |
| Lenovo        | ThinkPad X201T 3113CC7      | Notebook    | [47f63d40d5](https://linux-hardware.org/?probe=47f63d40d5) | Oct 09, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [93c695e5ba](https://linux-hardware.org/?probe=93c695e5ba) | Oct 08, 2021 |
| Microsoft     | Surface Book 3              | Tablet      | [5fdb7aebb9](https://linux-hardware.org/?probe=5fdb7aebb9) | Oct 08, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | Notebook    | [85a242883c](https://linux-hardware.org/?probe=85a242883c) | Oct 05, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [a36474b9ff](https://linux-hardware.org/?probe=a36474b9ff) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [56ce2c44cb](https://linux-hardware.org/?probe=56ce2c44cb) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [4d0eb4ccf2](https://linux-hardware.org/?probe=4d0eb4ccf2) | Oct 04, 2021 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [c8a0e5de69](https://linux-hardware.org/?probe=c8a0e5de69) | Oct 04, 2021 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| HUAWEI        | EUL-WX9                     | Notebook    | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| Lenovo        | ThinkPad X260 20F5S31G00    | Notebook    | [575dd64064](https://linux-hardware.org/?probe=575dd64064) | Oct 01, 2021 |
| HP            | Pavilion dv7                | Notebook    | [31b035faec](https://linux-hardware.org/?probe=31b035faec) | Sep 28, 2021 |
| Acer          | Aspire 5810T                | Notebook    | [be3f4d5a01](https://linux-hardware.org/?probe=be3f4d5a01) | Sep 26, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [edfae5b796](https://linux-hardware.org/?probe=edfae5b796) | Sep 25, 2021 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [e2fc9d2585](https://linux-hardware.org/?probe=e2fc9d2585) | Sep 23, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [5df047615c](https://linux-hardware.org/?probe=5df047615c) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [d7ccece3d4](https://linux-hardware.org/?probe=d7ccece3d4) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [466841a201](https://linux-hardware.org/?probe=466841a201) | Sep 22, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [201176552b](https://linux-hardware.org/?probe=201176552b) | Sep 21, 2021 |
| HP            | ZBook 15                    | Notebook    | [206882306c](https://linux-hardware.org/?probe=206882306c) | Sep 20, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1985156471](https://linux-hardware.org/?probe=1985156471) | Sep 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [f427b869d9](https://linux-hardware.org/?probe=f427b869d9) | Sep 17, 2021 |
| Lenovo        | ThinkPad X220 4291WAY       | Notebook    | [ca0ab89977](https://linux-hardware.org/?probe=ca0ab89977) | Sep 16, 2021 |
| Lenovo        | ThinkPad W541 20EFS01B09    | Notebook    | [8dd2c7497e](https://linux-hardware.org/?probe=8dd2c7497e) | Sep 13, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| HP            | Pavilion dv7                | Notebook    | [2fd3b811f6](https://linux-hardware.org/?probe=2fd3b811f6) | Sep 12, 2021 |
| Dell          | 0XCR8D A02                  | Desktop     | [9cb5ea4f4a](https://linux-hardware.org/?probe=9cb5ea4f4a) | Sep 11, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [1b80533734](https://linux-hardware.org/?probe=1b80533734) | Sep 11, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [4befd2306c](https://linux-hardware.org/?probe=4befd2306c) | Sep 11, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5d7c3904aa](https://linux-hardware.org/?probe=5d7c3904aa) | Sep 09, 2021 |
| ASRock        | P55M Pro                    | Desktop     | [b6408718ee](https://linux-hardware.org/?probe=b6408718ee) | Sep 02, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5cf3ed1411](https://linux-hardware.org/?probe=5cf3ed1411) | Aug 31, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [70585e2360](https://linux-hardware.org/?probe=70585e2360) | Aug 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [9c0457479f](https://linux-hardware.org/?probe=9c0457479f) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [23b7937411](https://linux-hardware.org/?probe=23b7937411) | Aug 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | Notebook    | [9382443dc7](https://linux-hardware.org/?probe=9382443dc7) | Aug 27, 2021 |
| Google        | Relm                        | Notebook    | [12475037ed](https://linux-hardware.org/?probe=12475037ed) | Aug 27, 2021 |
| Google        | Relm                        | Notebook    | [36e7a1d7a1](https://linux-hardware.org/?probe=36e7a1d7a1) | Aug 26, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [61f6289d2c](https://linux-hardware.org/?probe=61f6289d2c) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 2325AN3       | Notebook    | [d6b5ef49af](https://linux-hardware.org/?probe=d6b5ef49af) | Aug 24, 2021 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [900b0ce643](https://linux-hardware.org/?probe=900b0ce643) | Aug 24, 2021 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [e8aadc0af0](https://linux-hardware.org/?probe=e8aadc0af0) | Aug 24, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [93ec0ceb52](https://linux-hardware.org/?probe=93ec0ceb52) | Aug 23, 2021 |
| Medion        | MS-7616                     | Desktop     | [cbd20c24d8](https://linux-hardware.org/?probe=cbd20c24d8) | Aug 20, 2021 |
| Lenovo        | ThinkPad E595 20NF001HMX    | Notebook    | [8e75269d33](https://linux-hardware.org/?probe=8e75269d33) | Aug 20, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [5207c5584c](https://linux-hardware.org/?probe=5207c5584c) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [b7b363db20](https://linux-hardware.org/?probe=b7b363db20) | Aug 15, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [e42e169a72](https://linux-hardware.org/?probe=e42e169a72) | Aug 15, 2021 |
| HP            | Notebook                    | Notebook    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| HP            | 212B                        | Desktop     | [ee483c7463](https://linux-hardware.org/?probe=ee483c7463) | Aug 08, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [4d29ffa0f7](https://linux-hardware.org/?probe=4d29ffa0f7) | Aug 03, 2021 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | Desktop     | [4135f29492](https://linux-hardware.org/?probe=4135f29492) | Aug 02, 2021 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [59cd9e3edd](https://linux-hardware.org/?probe=59cd9e3edd) | Aug 01, 2021 |
| Pegatron      | 2AB6                        | Desktop     | [79dffb5346](https://linux-hardware.org/?probe=79dffb5346) | Jul 31, 2021 |
| GPD           | P2 MAX                      | Notebook    | [78f79b2790](https://linux-hardware.org/?probe=78f79b2790) | Jul 31, 2021 |
| Gigabyte      | P85-D3                      | Desktop     | [51f83ebd4a](https://linux-hardware.org/?probe=51f83ebd4a) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| ASUSTek       | GL702VM                     | Notebook    | [bb9d228646](https://linux-hardware.org/?probe=bb9d228646) | Jul 29, 2021 |
| Lenovo        | ThinkCentre Edge71 1577G... | Desktop     | [cf7f13e31c](https://linux-hardware.org/?probe=cf7f13e31c) | Jul 29, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [5ae2994458](https://linux-hardware.org/?probe=5ae2994458) | Jul 28, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c94593c3bd](https://linux-hardware.org/?probe=c94593c3bd) | Jul 25, 2021 |
| Medion        | Z370H4-EM                   | Desktop     | [f19570a630](https://linux-hardware.org/?probe=f19570a630) | Jul 24, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [a02dac8dff](https://linux-hardware.org/?probe=a02dac8dff) | Jul 23, 2021 |
| Shuttle       | FH67                        | Desktop     | [611a7c28dc](https://linux-hardware.org/?probe=611a7c28dc) | Jul 22, 2021 |
| Shuttle       | FH67                        | Desktop     | [3d3fb6c381](https://linux-hardware.org/?probe=3d3fb6c381) | Jul 22, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | Notebook    | [e52365f866](https://linux-hardware.org/?probe=e52365f866) | Jul 21, 2021 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [9ca97016e0](https://linux-hardware.org/?probe=9ca97016e0) | Jul 21, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | Notebook    | [704fb2e1d1](https://linux-hardware.org/?probe=704fb2e1d1) | Jul 21, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5fcfefa75a](https://linux-hardware.org/?probe=5fcfefa75a) | Jul 19, 2021 |
| Dell          | Latitude 7370               | Notebook    | [b10d4c18f2](https://linux-hardware.org/?probe=b10d4c18f2) | Jul 19, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | Notebook    | [7a03dbd869](https://linux-hardware.org/?probe=7a03dbd869) | Jul 17, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | Notebook    | [ce58f3f770](https://linux-hardware.org/?probe=ce58f3f770) | Jul 16, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f0241430cc](https://linux-hardware.org/?probe=f0241430cc) | Jul 16, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | Desktop     | [0c0d9cc784](https://linux-hardware.org/?probe=0c0d9cc784) | Jul 15, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [a56195f1f1](https://linux-hardware.org/?probe=a56195f1f1) | Jul 13, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [440841d04a](https://linux-hardware.org/?probe=440841d04a) | Jul 12, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [3b106f1da0](https://linux-hardware.org/?probe=3b106f1da0) | Jul 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | Notebook    | [f8872c9e84](https://linux-hardware.org/?probe=f8872c9e84) | Jul 05, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [4e6f9ccc6c](https://linux-hardware.org/?probe=4e6f9ccc6c) | Jul 05, 2021 |
| DukaPC        | Notebook                    | Notebook    | [6d87054512](https://linux-hardware.org/?probe=6d87054512) | Jul 02, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [cca3e863f7](https://linux-hardware.org/?probe=cca3e863f7) | Jul 01, 2021 |
| HP            | ProBook 640 G3              | Notebook    | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| Timi          | TM1703                      | Notebook    | [bd3756811d](https://linux-hardware.org/?probe=bd3756811d) | Jun 26, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [2c4a16ea24](https://linux-hardware.org/?probe=2c4a16ea24) | Jun 25, 2021 |
| DukaPC        | Notebook                    | Notebook    | [c29d208cdf](https://linux-hardware.org/?probe=c29d208cdf) | Jun 24, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [208a9ee715](https://linux-hardware.org/?probe=208a9ee715) | Jun 23, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [86fce52939](https://linux-hardware.org/?probe=86fce52939) | Jun 23, 2021 |
| Lenovo        | ThinkPad T420 4236Y19       | Notebook    | [48927432b4](https://linux-hardware.org/?probe=48927432b4) | Jun 20, 2021 |
| Lenovo        | 3714 SDK0J40700 WIN 3258... | Desktop     | [ca43a33e1d](https://linux-hardware.org/?probe=ca43a33e1d) | Jun 18, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d8ad69d368](https://linux-hardware.org/?probe=d8ad69d368) | Jun 15, 2021 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | Desktop     | [4a0a83693b](https://linux-hardware.org/?probe=4a0a83693b) | Jun 14, 2021 |
| ASRock        | P55M Pro                    | Desktop     | [cac3198045](https://linux-hardware.org/?probe=cac3198045) | Jun 14, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0Y70... | Notebook    | [5e57af6782](https://linux-hardware.org/?probe=5e57af6782) | Jun 11, 2021 |
| HP            | 212B                        | Desktop     | [b72ab2aea5](https://linux-hardware.org/?probe=b72ab2aea5) | Jun 09, 2021 |
| Lenovo        | ThinkPad T420 4236PFG       | Notebook    | [fa5abfccf8](https://linux-hardware.org/?probe=fa5abfccf8) | Jun 04, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [2927765712](https://linux-hardware.org/?probe=2927765712) | Jun 04, 2021 |
| ASRock        | P55M Pro                    | Desktop     | [b994c1917a](https://linux-hardware.org/?probe=b994c1917a) | Jun 03, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [d4deb2b08d](https://linux-hardware.org/?probe=d4deb2b08d) | Jun 01, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| Dell          | Latitude E6520              | Notebook    | [d1d0976880](https://linux-hardware.org/?probe=d1d0976880) | May 31, 2021 |
| Lenovo        | ThinkPad T400 647358G       | Notebook    | [b4f44d7932](https://linux-hardware.org/?probe=b4f44d7932) | May 29, 2021 |
| MSI           | Z87 MPOWER                  | Desktop     | [848def4822](https://linux-hardware.org/?probe=848def4822) | May 29, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [58d3740c30](https://linux-hardware.org/?probe=58d3740c30) | May 28, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e0217f85a6](https://linux-hardware.org/?probe=e0217f85a6) | May 28, 2021 |
| Acer          | Aspire E5-553               | Notebook    | [70037bddcb](https://linux-hardware.org/?probe=70037bddcb) | May 27, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [f9358acedf](https://linux-hardware.org/?probe=f9358acedf) | May 27, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [787c1b3a8c](https://linux-hardware.org/?probe=787c1b3a8c) | May 26, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [92f19ca1e6](https://linux-hardware.org/?probe=92f19ca1e6) | May 25, 2021 |
| LAMINA        | T-1012B NORD                | Notebook    | [71e70e946a](https://linux-hardware.org/?probe=71e70e946a) | May 25, 2021 |
| ASUSTek       | NARRA2                      | Desktop     | [0b2cf24d70](https://linux-hardware.org/?probe=0b2cf24d70) | May 25, 2021 |
| LAMINA        | T-1012B NORD                | Notebook    | [9dc2932064](https://linux-hardware.org/?probe=9dc2932064) | May 24, 2021 |
| ASUSTek       | X553SA                      | Notebook    | [c470382d2a](https://linux-hardware.org/?probe=c470382d2a) | May 24, 2021 |
| ASUSTek       | X553SA                      | Notebook    | [31d6a914fd](https://linux-hardware.org/?probe=31d6a914fd) | May 24, 2021 |
| Acer          | Aspire E5-511               | Notebook    | [9edec55620](https://linux-hardware.org/?probe=9edec55620) | May 23, 2021 |
| Acer          | Aspire E5-511               | Notebook    | [e20c93a2c1](https://linux-hardware.org/?probe=e20c93a2c1) | May 23, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | Notebook    | [a9e4c7793b](https://linux-hardware.org/?probe=a9e4c7793b) | May 18, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [c5621d630d](https://linux-hardware.org/?probe=c5621d630d) | May 15, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [53e6447416](https://linux-hardware.org/?probe=53e6447416) | May 15, 2021 |
| eMachines     | E725                        | Notebook    | [329f8f580e](https://linux-hardware.org/?probe=329f8f580e) | May 14, 2021 |
| Medion        | MS-7646                     | Desktop     | [799be90f9c](https://linux-hardware.org/?probe=799be90f9c) | May 11, 2021 |
| ASUSTek       | K95VM                       | Notebook    | [58d4ed3c2b](https://linux-hardware.org/?probe=58d4ed3c2b) | May 10, 2021 |
| HP            | 15                          | Notebook    | [a13c097d59](https://linux-hardware.org/?probe=a13c097d59) | May 09, 2021 |
| HP            | 15                          | Notebook    | [c3cdcdab60](https://linux-hardware.org/?probe=c3cdcdab60) | May 09, 2021 |
| ASRock        | J4105-ITX                   | Desktop     | [2cb8135a58](https://linux-hardware.org/?probe=2cb8135a58) | May 08, 2021 |
| Alienware     | 17 R2                       | Notebook    | [a8470edc65](https://linux-hardware.org/?probe=a8470edc65) | May 06, 2021 |
| Intel         | NUC8i5INB K29935-404        | Mini pc     | [45b14891d4](https://linux-hardware.org/?probe=45b14891d4) | May 06, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [a8271c73ee](https://linux-hardware.org/?probe=a8271c73ee) | May 02, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [73c1eaa647](https://linux-hardware.org/?probe=73c1eaa647) | Apr 29, 2021 |
| Lenovo        | ThinkPad T520 4243PC2       | Notebook    | [915d41f361](https://linux-hardware.org/?probe=915d41f361) | Apr 29, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [e259d34a4c](https://linux-hardware.org/?probe=e259d34a4c) | Apr 28, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [9e0202e76a](https://linux-hardware.org/?probe=9e0202e76a) | Apr 27, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | Notebook    | [e2f8b2beda](https://linux-hardware.org/?probe=e2f8b2beda) | Apr 25, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | Notebook    | [684f1471b1](https://linux-hardware.org/?probe=684f1471b1) | Apr 23, 2021 |
| MiTAC         | PH10SI AAPH11SI-CI-700      | All in one  | [f27aee762c](https://linux-hardware.org/?probe=f27aee762c) | Apr 21, 2021 |
| Lenovo        | E31-80 80MX                 | Notebook    | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [bd14a696eb](https://linux-hardware.org/?probe=bd14a696eb) | Apr 20, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [c0bd3fe537](https://linux-hardware.org/?probe=c0bd3fe537) | Apr 20, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [31cb6e83ed](https://linux-hardware.org/?probe=31cb6e83ed) | Apr 19, 2021 |
| Acer          | Veriton M275                | Desktop     | [246a662951](https://linux-hardware.org/?probe=246a662951) | Apr 17, 2021 |
| Lenovo        | ThinkPad T520 42434YG       | Notebook    | [8e0b4ee3a1](https://linux-hardware.org/?probe=8e0b4ee3a1) | Apr 17, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | Notebook    | [49e1959064](https://linux-hardware.org/?probe=49e1959064) | Apr 16, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | Notebook    | [b2853266e8](https://linux-hardware.org/?probe=b2853266e8) | Apr 15, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [cd772af567](https://linux-hardware.org/?probe=cd772af567) | Apr 14, 2021 |
| Gigabyte      | EP35-DS4                    | Desktop     | [e37cf6fc8d](https://linux-hardware.org/?probe=e37cf6fc8d) | Apr 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [4b127c0ba4](https://linux-hardware.org/?probe=4b127c0ba4) | Apr 11, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [a844e710cc](https://linux-hardware.org/?probe=a844e710cc) | Apr 09, 2021 |
| Lenovo        | ThinkPad T60 20076RG        | Notebook    | [aa3ea77acf](https://linux-hardware.org/?probe=aa3ea77acf) | Apr 08, 2021 |
| MSI           | Z87 MPOWER                  | Desktop     | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [09cf1ed052](https://linux-hardware.org/?probe=09cf1ed052) | Apr 08, 2021 |
| HP            | G72                         | Notebook    | [2ab4eb5fcd](https://linux-hardware.org/?probe=2ab4eb5fcd) | Apr 05, 2021 |
| Dell          | Latitude 5175               | Tablet      | [36ce9ad0c9](https://linux-hardware.org/?probe=36ce9ad0c9) | Apr 02, 2021 |
| Dell          | Latitude 5175               | Tablet      | [4fa01ccee6](https://linux-hardware.org/?probe=4fa01ccee6) | Apr 02, 2021 |
| ASRock        | Z270 Pro4                   | Desktop     | [b90dd1b4d2](https://linux-hardware.org/?probe=b90dd1b4d2) | Apr 02, 2021 |
| Medion        | MS-7797                     | Desktop     | [947bc894eb](https://linux-hardware.org/?probe=947bc894eb) | Apr 01, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [757d1d0707](https://linux-hardware.org/?probe=757d1d0707) | Mar 31, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [eb1782ad49](https://linux-hardware.org/?probe=eb1782ad49) | Mar 31, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [4c3dd6a28b](https://linux-hardware.org/?probe=4c3dd6a28b) | Mar 25, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [344f718da0](https://linux-hardware.org/?probe=344f718da0) | Mar 25, 2021 |
| ASUSTek       | K95VM                       | Notebook    | [81a01884d2](https://linux-hardware.org/?probe=81a01884d2) | Mar 24, 2021 |
| Dell          | 0CU409                      | Desktop     | [53a8c28aed](https://linux-hardware.org/?probe=53a8c28aed) | Mar 24, 2021 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [8d564e495b](https://linux-hardware.org/?probe=8d564e495b) | Mar 23, 2021 |
| Toshiba       | Satellite L350D             | Notebook    | [b083513b72](https://linux-hardware.org/?probe=b083513b72) | Mar 23, 2021 |
| Acer          | Aspire E5-553               | Notebook    | [0c21dc1b96](https://linux-hardware.org/?probe=0c21dc1b96) | Mar 19, 2021 |
| Acer          | Aspire XC-605               | Desktop     | [f8ad366bd9](https://linux-hardware.org/?probe=f8ad366bd9) | Mar 19, 2021 |
| HP            | Pavilion dm1                | Notebook    | [438cf03315](https://linux-hardware.org/?probe=438cf03315) | Mar 18, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [7e7a4bc992](https://linux-hardware.org/?probe=7e7a4bc992) | Mar 18, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [54288c23c9](https://linux-hardware.org/?probe=54288c23c9) | Mar 18, 2021 |
| ECS           | Nettle3                     | Desktop     | [f7ec16d7e7](https://linux-hardware.org/?probe=f7ec16d7e7) | Mar 16, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | Notebook    | [1b8a078a19](https://linux-hardware.org/?probe=1b8a078a19) | Mar 16, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [248eb896a0](https://linux-hardware.org/?probe=248eb896a0) | Mar 15, 2021 |
| HP            | 3032h                       | Desktop     | [79b0bf2416](https://linux-hardware.org/?probe=79b0bf2416) | Mar 15, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [e4613a6f75](https://linux-hardware.org/?probe=e4613a6f75) | Mar 15, 2021 |
| Dell          | Latitude E5250              | Notebook    | [22067e0909](https://linux-hardware.org/?probe=22067e0909) | Mar 13, 2021 |
| Dell          | Latitude E5250              | Notebook    | [df9d913f0f](https://linux-hardware.org/?probe=df9d913f0f) | Mar 13, 2021 |
| HP            | Pavilion dv9700             | Notebook    | [f55ec4dd18](https://linux-hardware.org/?probe=f55ec4dd18) | Mar 11, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [865e070587](https://linux-hardware.org/?probe=865e070587) | Mar 10, 2021 |
| Dell          | Latitude E5250              | Notebook    | [78f0a24d9a](https://linux-hardware.org/?probe=78f0a24d9a) | Mar 07, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [18240d24d8](https://linux-hardware.org/?probe=18240d24d8) | Mar 06, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [9ebf280981](https://linux-hardware.org/?probe=9ebf280981) | Mar 05, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [efa91095ab](https://linux-hardware.org/?probe=efa91095ab) | Mar 05, 2021 |
| Toshiba       | Satellite L350D             | Notebook    | [ef8a29af20](https://linux-hardware.org/?probe=ef8a29af20) | Mar 05, 2021 |
| ASUSTek       | M4N75TD                     | Desktop     | [9daf1b6529](https://linux-hardware.org/?probe=9daf1b6529) | Feb 28, 2021 |
| Acer          | Aspire E5-553               | Notebook    | [74e6da0017](https://linux-hardware.org/?probe=74e6da0017) | Feb 27, 2021 |
| ASUSTek       | P5P43TD                     | Desktop     | [3a2604a18a](https://linux-hardware.org/?probe=3a2604a18a) | Feb 27, 2021 |
| HP            | 1998                        | Desktop     | [43bd925171](https://linux-hardware.org/?probe=43bd925171) | Feb 27, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [66ce820cff](https://linux-hardware.org/?probe=66ce820cff) | Feb 25, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Denmark/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 148       | 13.03%  |
| Ubuntu 18.04       | 84        | 7.39%   |
| Ubuntu 22.04       | 65        | 5.72%   |
| Arch Rolling       | 40        | 3.52%   |
| Pop!_OS 22.04      | 31        | 2.73%   |
| Ubuntu 21.10       | 25        | 2.2%    |
| OpenMandriva 4.2   | 25        | 2.2%    |
| Debian 11          | 24        | 2.11%   |
| Zorin 16           | 23        | 2.02%   |
| Fedora 38          | 22        | 1.94%   |
| Manjaro            | 19        | 1.67%   |
| Fedora 34          | 16        | 1.41%   |
| Ubuntu 20.10       | 15        | 1.32%   |
| Linux Mint 21.1    | 15        | 1.32%   |
| Ubuntu 19.04       | 14        | 1.23%   |
| Pop!_OS 21.04      | 14        | 1.23%   |
| OpenMandriva 23.03 | 14        | 1.23%   |
| Linux Mint 20.2    | 14        | 1.23%   |
| OpenMandriva 4.3   | 13        | 1.14%   |
| Linux Mint 21.2    | 13        | 1.14%   |
| Linux Mint 20.3    | 13        | 1.14%   |
| Arch               | 13        | 1.14%   |
| Ubuntu 22.10       | 12        | 1.06%   |
| Linux Mint 20.1    | 12        | 1.06%   |
| Fedora 36          | 12        | 1.06%   |
| Fedora 32          | 12        | 1.06%   |
| ArcoLinux Rolling  | 12        | 1.06%   |
| Zorin 15           | 11        | 0.97%   |
| KDE neon 20.04     | 11        | 0.97%   |
| Ubuntu 19.10       | 10        | 0.88%   |
| Pop!_OS 20.04      | 10        | 0.88%   |
| Debian 10          | 10        | 0.88%   |
| Pop!_OS 21.10      | 9         | 0.79%   |
| Pop!_OS 20.10      | 9         | 0.79%   |
| Fedora 37          | 9         | 0.79%   |
| Debian 12          | 9         | 0.79%   |
| Linux Mint 20      | 8         | 0.7%    |
| Fedora 35          | 8         | 0.7%    |
| Fedora 33          | 8         | 0.7%    |
| Ubuntu 23.04       | 7         | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 373       | 34.93%  |
| Linux Mint   | 93        | 8.71%   |
| Fedora       | 93        | 8.71%   |
| Pop!_OS      | 72        | 6.74%   |
| OpenMandriva | 65        | 6.09%   |
| Arch         | 52        | 4.87%   |
| Debian       | 48        | 4.49%   |
| Manjaro      | 44        | 4.12%   |
| Zorin        | 37        | 3.46%   |
| Kubuntu      | 23        | 2.15%   |
| KDE neon     | 18        | 1.69%   |
| ArcoLinux    | 15        | 1.4%    |
| Xubuntu      | 14        | 1.31%   |
| Ubuntu MATE  | 9         | 0.84%   |
| ROSA         | 9         | 0.84%   |
| SteamOS      | 8         | 0.75%   |
| EndeavourOS  | 8         | 0.75%   |
| Elementary   | 7         | 0.66%   |
| openSUSE     | 6         | 0.56%   |
| Kali         | 6         | 0.56%   |
| Garuda Linux | 6         | 0.56%   |
| Void Linux   | 5         | 0.47%   |
| Ubuntu Unity | 5         | 0.47%   |
| Parrot       | 5         | 0.47%   |
| Gentoo       | 5         | 0.47%   |
| Lubuntu      | 4         | 0.37%   |
| Clear Linux  | 4         | 0.37%   |
| Xero         | 3         | 0.28%   |
| Raspbian     | 3         | 0.28%   |
| NixOS        | 3         | 0.28%   |
| MX           | 3         | 0.28%   |
| LMDE         | 3         | 0.28%   |
| Endless      | 3         | 0.28%   |
| BlackPanther | 3         | 0.28%   |
| Nobara       | 2         | 0.19%   |
| antiX        | 2         | 0.19%   |
| TUXEDO OS    | 1         | 0.09%   |
| Solus        | 1         | 0.09%   |
| Manjaro-ARM  | 1         | 0.09%   |
| LinuxFX      | 1         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 23        | 1.85%   |
| 5.4.0-42-generic         | 19        | 1.53%   |
| 6.2.6-desktop-1omv2390   | 14        | 1.13%   |
| 5.16.7-desktop-1omv4003  | 13        | 1.05%   |
| 5.4.0-52-generic         | 12        | 0.97%   |
| 5.15.0-56-generic        | 12        | 0.97%   |
| 5.4.0-26-generic         | 10        | 0.8%    |
| 6.2.6-76060206-generic   | 8         | 0.64%   |
| 5.4.0-58-generic         | 8         | 0.64%   |
| 5.4.0-48-generic         | 8         | 0.64%   |
| 5.3.0-28-generic         | 8         | 0.64%   |
| 5.19.0-35-generic        | 8         | 0.64%   |
| 5.15.0-58-generic        | 8         | 0.64%   |
| 5.8.0-43-generic         | 7         | 0.56%   |
| 5.4.0-29-generic         | 7         | 0.56%   |
| 5.15.0-46-generic        | 7         | 0.56%   |
| 5.15.0-43-generic        | 7         | 0.56%   |
| 5.11.0-41-generic        | 7         | 0.56%   |
| 5.11.0-27-generic        | 7         | 0.56%   |
| 5.4.0-91-generic         | 6         | 0.48%   |
| 5.4.0-7634-generic       | 6         | 0.48%   |
| 5.3.0-40-generic         | 6         | 0.48%   |
| 5.19.0-76051900-generic  | 6         | 0.48%   |
| 5.19.0-38-generic        | 6         | 0.48%   |
| 5.15.0-53-generic        | 6         | 0.48%   |
| 5.11.0-7620-generic      | 6         | 0.48%   |
| 5.11.0-40-generic        | 6         | 0.48%   |
| 6.4.6-76060406-generic   | 5         | 0.4%    |
| 5.8.0-41-generic         | 5         | 0.4%    |
| 5.4.0-47-generic         | 5         | 0.4%    |
| 5.15.0-88-generic        | 5         | 0.4%    |
| 5.15.0-52-generic        | 5         | 0.4%    |
| 5.13.12-200.fc34.x86_64  | 5         | 0.4%    |
| 5.13.0-39-generic        | 5         | 0.4%    |
| 5.11.0-37-generic        | 5         | 0.4%    |
| 5.10.0-19-amd64          | 5         | 0.4%    |
| 5.0.0-23-generic         | 5         | 0.4%    |
| 5.0.0-13-generic         | 5         | 0.4%    |
| 4.15.0-55-generic        | 5         | 0.4%    |
| 4.15.0-45-generic        | 5         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 155       | 13.21%  |
| 5.15.0  | 100       | 8.53%   |
| 4.15.0  | 66        | 5.63%   |
| 5.13.0  | 59        | 5.03%   |
| 5.11.0  | 59        | 5.03%   |
| 5.8.0   | 56        | 4.77%   |
| 5.19.0  | 46        | 3.92%   |
| 5.3.0   | 37        | 3.15%   |
| 5.0.0   | 27        | 2.3%    |
| 6.2.6   | 26        | 2.22%   |
| 6.2.0   | 26        | 2.22%   |
| 5.10.0  | 24        | 2.05%   |
| 5.10.14 | 23        | 1.96%   |
| 4.18.0  | 18        | 1.53%   |
| 6.1.0   | 14        | 1.19%   |
| 5.16.7  | 13        | 1.11%   |
| 4.19.0  | 11        | 0.94%   |
| 6.5.5   | 6         | 0.51%   |
| 6.5.0   | 6         | 0.51%   |
| 6.4.6   | 6         | 0.51%   |
| 6.1.1   | 6         | 0.51%   |
| 5.4.18  | 5         | 0.43%   |
| 5.16.0  | 5         | 0.43%   |
| 5.13.12 | 5         | 0.43%   |
| 6.6.8   | 4         | 0.34%   |
| 6.5.9   | 4         | 0.34%   |
| 6.5.6   | 4         | 0.34%   |
| 6.5.3   | 4         | 0.34%   |
| 6.4.8   | 4         | 0.34%   |
| 6.4.11  | 4         | 0.34%   |
| 6.3.9   | 4         | 0.34%   |
| 6.3.8   | 4         | 0.34%   |
| 6.1.7   | 4         | 0.34%   |
| 6.0.6   | 4         | 0.34%   |
| 6.0.0   | 4         | 0.34%   |
| 5.9.0   | 4         | 0.34%   |
| 5.8.5   | 4         | 0.34%   |
| 5.7.15  | 4         | 0.34%   |
| 5.6.7   | 4         | 0.34%   |
| 5.16.18 | 4         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 171       | 14.79%  |
| 5.15    | 131       | 11.33%  |
| 5.8     | 76        | 6.57%   |
| 5.11    | 72        | 6.23%   |
| 5.13    | 69        | 5.97%   |
| 4.15    | 66        | 5.71%   |
| 5.19    | 61        | 5.28%   |
| 6.2     | 60        | 5.19%   |
| 5.10    | 58        | 5.02%   |
| 6.1     | 45        | 3.89%   |
| 5.3     | 37        | 3.2%    |
| 5.16    | 34        | 2.94%   |
| 6.5     | 30        | 2.6%    |
| 5.0     | 28        | 2.42%   |
| 6.4     | 22        | 1.9%    |
| 6.0     | 20        | 1.73%   |
| 4.18    | 20        | 1.73%   |
| 6.3     | 18        | 1.56%   |
| 5.6     | 17        | 1.47%   |
| 5.14    | 16        | 1.38%   |
| 6.6     | 14        | 1.21%   |
| 4.19    | 13        | 1.12%   |
| 5.9     | 12        | 1.04%   |
| 5.7     | 12        | 1.04%   |
| 5.17    | 12        | 1.04%   |
| 5.18    | 9         | 0.78%   |
| 5.12    | 9         | 0.78%   |
| 5.1     | 6         | 0.52%   |
| 4.9     | 6         | 0.52%   |
| 4.4     | 3         | 0.26%   |
| 5.2     | 2         | 0.17%   |
| 4.14    | 2         | 0.17%   |
| 4.17    | 1         | 0.09%   |
| 4.16    | 1         | 0.09%   |
| 4.13    | 1         | 0.09%   |
| 4.10    | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 990       | 96.3%   |
| i686    | 24        | 2.33%   |
| aarch64 | 11        | 1.07%   |
| armv7l  | 3         | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 508       | 47.21%  |
| KDE5            | 180       | 16.73%  |
| Unknown         | 148       | 13.75%  |
| X-Cinnamon      | 71        | 6.6%    |
| XFCE            | 70        | 6.51%   |
| MATE            | 25        | 2.32%   |
| KDE             | 21        | 1.95%   |
| i3              | 9         | 0.84%   |
| LXQt            | 7         | 0.65%   |
| Cinnamon        | 7         | 0.65%   |
| Pantheon        | 6         | 0.56%   |
| Unity           | 5         | 0.46%   |
| GNOME Flashback | 3         | 0.28%   |
| sway            | 2         | 0.19%   |
| LXDE            | 2         | 0.19%   |
| KDE4            | 2         | 0.19%   |
| icewm           | 2         | 0.19%   |
| qtile-default   | 1         | 0.09%   |
| openbox         | 1         | 0.09%   |
| LeftWM          | 1         | 0.09%   |
| Hyprland        | 1         | 0.09%   |
| enlightenment   | 1         | 0.09%   |
| Deepin          | 1         | 0.09%   |
| bspwm           | 1         | 0.09%   |
| awesome         | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 769       | 71.8%   |
| Wayland | 209       | 19.51%  |
| Unknown | 69        | 6.44%   |
| Tty     | 24        | 2.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 569       | 53.43%  |
| SDDM    | 144       | 13.52%  |
| GDM3    | 133       | 12.49%  |
| GDM     | 113       | 10.61%  |
| LightDM | 67        | 6.29%   |
| TDM     | 29        | 2.72%   |
| KDM     | 2         | 0.19%   |
| GREETD  | 2         | 0.19%   |
| XDM     | 1         | 0.09%   |
| SLIMSKI | 1         | 0.09%   |
| SLiM    | 1         | 0.09%   |
| LY-DM   | 1         | 0.09%   |
| Ly      | 1         | 0.09%   |
| LXDM    | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 383       | 36%     |
| da_DK      | 319       | 29.98%  |
| en_DK      | 135       | 12.69%  |
| Unknown    | 113       | 10.62%  |
| en_GB      | 54        | 5.08%   |
| C          | 17        | 1.6%    |
| de_DE      | 15        | 1.41%   |
| pl_PL      | 5         | 0.47%   |
| sv_SE      | 2         | 0.19%   |
| ru_RU      | 2         | 0.19%   |
| it_IT      | 2         | 0.19%   |
| es_ES      | 2         | 0.19%   |
| en_AG      | 2         | 0.19%   |
| de_CH      | 2         | 0.19%   |
| zh_TW      | 1         | 0.09%   |
| pt_BR      | 1         | 0.09%   |
| nl_NL      | 1         | 0.09%   |
| is_IS      | 1         | 0.09%   |
| io_001     | 1         | 0.09%   |
| fr_FR      | 1         | 0.09%   |
| en_US.UTF8 | 1         | 0.09%   |
| en_IE      | 1         | 0.09%   |
| en_CA      | 1         | 0.09%   |
| en_AU      | 1         | 0.09%   |
| de_AT      | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 526       | 50.1%   |
| EFI  | 524       | 49.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 793       | 74.39%  |
| Btrfs   | 130       | 12.2%   |
| Overlay | 61        | 5.72%   |
| Unknown | 37        | 3.47%   |
| Tmpfs   | 25        | 2.35%   |
| Zfs     | 11        | 1.03%   |
| Xfs     | 5         | 0.47%   |
| Ext2    | 3         | 0.28%   |
| F2fs    | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 592       | 55.85%  |
| GPT     | 379       | 35.75%  |
| MBR     | 89        | 8.4%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 896       | 85.33%  |
| Yes       | 154       | 14.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 794       | 75.98%  |
| Yes       | 251       | 24.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 268       | 26.1%   |
| ASUSTek Computer        | 181       | 17.62%  |
| Hewlett-Packard         | 129       | 12.56%  |
| Dell                    | 72        | 7.01%   |
| Acer                    | 55        | 5.36%   |
| Gigabyte Technology     | 50        | 4.87%   |
| MSI                     | 48        | 4.67%   |
| Apple                   | 34        | 3.31%   |
| ASRock                  | 32        | 3.12%   |
| Medion                  | 17        | 1.66%   |
| Intel                   | 13        | 1.27%   |
| Raspberry Pi Foundation | 12        | 1.17%   |
| Toshiba                 | 11        | 1.07%   |
| Notebook                | 10        | 0.97%   |
| HUAWEI                  | 6         | 0.58%   |
| Google                  | 6         | 0.58%   |
| Valve                   | 5         | 0.49%   |
| Unknown                 | 5         | 0.49%   |
| Shuttle                 | 4         | 0.39%   |
| Samsung Electronics     | 4         | 0.39%   |
| Pegatron                | 4         | 0.39%   |
| Packard Bell            | 4         | 0.39%   |
| Microsoft               | 4         | 0.39%   |
| Fujitsu                 | 4         | 0.39%   |
| AMI                     | 4         | 0.39%   |
| Razer                   | 3         | 0.29%   |
| eMachines               | 3         | 0.29%   |
| TUXEDO                  | 2         | 0.19%   |
| Timi                    | 2         | 0.19%   |
| Sony                    | 2         | 0.19%   |
| Quanta                  | 2         | 0.19%   |
| GPD                     | 2         | 0.19%   |
| Fujitsu Siemens         | 2         | 0.19%   |
| BESSTAR Tech            | 2         | 0.19%   |
| Alienware               | 2         | 0.19%   |
| Tactus                  | 1         | 0.1%    |
| T-bao                   | 1         | 0.1%    |
| System76                | 1         | 0.1%    |
| Supermicro              | 1         | 0.1%    |
| Standard                | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 12        | 1.17%   |
| ASUS All Series                         | 6         | 0.58%   |
| Valve Jupiter                           | 5         | 0.49%   |
| RPi Raspberry Pi                        | 5         | 0.49%   |
| HP Pavilion dv7                         | 5         | 0.49%   |
| ASUS ROG STRIX B450-E GAMING            | 5         | 0.49%   |
| RPi Raspberry Pi 4 Model B Rev 1.1      | 4         | 0.39%   |
| Dell XPS 15 9570                        | 4         | 0.39%   |
| Dell XPS 13 9370                        | 4         | 0.39%   |
| ASUS Z170 PRO GAMING                    | 4         | 0.39%   |
| ASUS TUF Gaming X570-PLUS               | 4         | 0.39%   |
| ASUS ROG STRIX B550-F GAMING            | 4         | 0.39%   |
| MSI MS-7C37                             | 3         | 0.29%   |
| MSI MS-7C02                             | 3         | 0.29%   |
| HP Pavilion g7                          | 3         | 0.29%   |
| HP OMEN by Laptop                       | 3         | 0.29%   |
| HP Notebook                             | 3         | 0.29%   |
| HP EliteBook 820 G3                     | 3         | 0.29%   |
| Gigabyte X570 AORUS MASTER              | 3         | 0.29%   |
| Dell OptiPlex 9020                      | 3         | 0.29%   |
| Dell Latitude 7480                      | 3         | 0.29%   |
| ASUS ROG Zephyrus G14 GA402RK_GA402RK   | 3         | 0.29%   |
| ASUS ROG STRIX X570-E GAMING            | 3         | 0.29%   |
| ASUS PRIME Z390-A                       | 3         | 0.29%   |
| Apple MacBookPro9,2                     | 3         | 0.29%   |
| Apple MacBookPro5,5                     | 3         | 0.29%   |
| Apple iMac12,1                          | 3         | 0.29%   |
| Toshiba Satellite P850                  | 2         | 0.19%   |
| Toshiba Satellite L40                   | 2         | 0.19%   |
| RPi Raspberry Pi 3 Model B Plus Rev 1.3 | 2         | 0.19%   |
| Quanta MW1/HW1                          | 2         | 0.19%   |
| Notebook W54_55SU1,SUW                  | 2         | 0.19%   |
| MSI MS-7B79                             | 2         | 0.19%   |
| MSI MS-7A34                             | 2         | 0.19%   |
| MSI MS-7693                             | 2         | 0.19%   |
| Medion MS-7797                          | 2         | 0.19%   |
| Medion MS-7646                          | 2         | 0.19%   |
| Lenovo Yoga C740-14IML 81TC             | 2         | 0.19%   |
| Lenovo V110-15IAP 80TG                  | 2         | 0.19%   |
| Lenovo ThinkPad T530 24295L4            | 2         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 160       | 15.58%  |
| ASUS ROG            | 41        | 3.99%   |
| Acer Aspire         | 38        | 3.7%    |
| ASUS PRIME          | 30        | 2.92%   |
| HP Pavilion         | 28        | 2.73%   |
| HP EliteBook        | 24        | 2.34%   |
| Dell Latitude       | 24        | 2.34%   |
| Lenovo IdeaPad      | 21        | 2.04%   |
| Lenovo ThinkCentre  | 17        | 1.66%   |
| Lenovo Yoga         | 16        | 1.56%   |
| HP Compaq           | 16        | 1.56%   |
| Dell XPS            | 16        | 1.56%   |
| ASUS TUF            | 16        | 1.56%   |
| RPi Raspberry       | 12        | 1.17%   |
| HP ProBook          | 12        | 1.17%   |
| Unknown             | 12        | 1.17%   |
| Toshiba Satellite   | 11        | 1.07%   |
| HP Laptop           | 10        | 0.97%   |
| Dell Inspiron       | 10        | 0.97%   |
| ASUS ZenBook        | 9         | 0.88%   |
| Gigabyte X570       | 8         | 0.78%   |
| Lenovo Legion       | 7         | 0.68%   |
| Dell Precision      | 7         | 0.68%   |
| Dell OptiPlex       | 7         | 0.68%   |
| Lenovo ThinkStation | 6         | 0.58%   |
| ASUS All            | 6         | 0.58%   |
| Valve Jupiter       | 5         | 0.49%   |
| Lenovo ThinkBook    | 5         | 0.49%   |
| HP OMEN             | 5         | 0.49%   |
| HP ENVY             | 5         | 0.49%   |
| ASUS VivoBook       | 5         | 0.49%   |
| Acer Swift          | 5         | 0.49%   |
| Microsoft Surface   | 4         | 0.39%   |
| Lenovo IdeaCentre   | 4         | 0.39%   |
| HP Spectre          | 4         | 0.39%   |
| HP ProLiant         | 4         | 0.39%   |
| ASUS Z170           | 4         | 0.39%   |
| ASUS STRIX          | 4         | 0.39%   |
| ASUS SABERTOOTH     | 4         | 0.39%   |
| ASUS M5A78L-M       | 4         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 99        | 9.64%   |
| 2020    | 94        | 9.15%   |
| 2019    | 94        | 9.15%   |
| 2017    | 79        | 7.69%   |
| 2021    | 77        | 7.5%    |
| 2013    | 75        | 7.3%    |
| 2012    | 71        | 6.91%   |
| 2015    | 69        | 6.72%   |
| 2011    | 65        | 6.33%   |
| 2016    | 62        | 6.04%   |
| 2014    | 45        | 4.38%   |
| 2022    | 39        | 3.8%    |
| 2010    | 39        | 3.8%    |
| 2009    | 34        | 3.31%   |
| 2008    | 29        | 2.82%   |
| 2007    | 26        | 2.53%   |
| Unknown | 12        | 1.17%   |
| 2023    | 10        | 0.97%   |
| 2006    | 7         | 0.68%   |
| 2003    | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 582       | 56.67%  |
| Desktop        | 354       | 34.47%  |
| Convertible    | 29        | 2.82%   |
| Mini pc        | 20        | 1.95%   |
| All in one     | 18        | 1.75%   |
| System on chip | 12        | 1.17%   |
| Tablet         | 7         | 0.68%   |
| Server         | 3         | 0.29%   |
| Phone          | 2         | 0.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 944       | 91.38%  |
| Enabled  | 89        | 8.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1020      | 99.32%  |
| Yes  | 7         | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 235       | 22.4%   |
| 16.01-24.0      | 231       | 22.02%  |
| 8.01-16.0       | 196       | 18.68%  |
| 3.01-4.0        | 144       | 13.73%  |
| 32.01-64.0      | 135       | 12.87%  |
| 64.01-256.0     | 38        | 3.62%   |
| 24.01-32.0      | 26        | 2.48%   |
| 1.01-2.0        | 22        | 2.1%    |
| 2.01-3.0        | 14        | 1.33%   |
| 0.51-1.0        | 6         | 0.57%   |
| More than 256.0 | 1         | 0.1%    |
| 0.01-0.5        | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 351       | 30.74%  |
| 2.01-3.0   | 304       | 26.62%  |
| 4.01-8.0   | 207       | 18.13%  |
| 3.01-4.0   | 164       | 14.36%  |
| 0.51-1.0   | 44        | 3.85%   |
| 8.01-16.0  | 42        | 3.68%   |
| 0.01-0.5   | 15        | 1.31%   |
| 24.01-32.0 | 7         | 0.61%   |
| 16.01-24.0 | 5         | 0.44%   |
| 32.01-64.0 | 3         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 666       | 63.01%  |
| 2      | 216       | 20.44%  |
| 3      | 91        | 8.61%   |
| 4      | 38        | 3.6%    |
| 5      | 23        | 2.18%   |
| 0      | 10        | 0.95%   |
| 6      | 7         | 0.66%   |
| 8      | 3         | 0.28%   |
| 7      | 2         | 0.19%   |
| 9      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 689       | 66.51%  |
| Yes       | 347       | 33.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 898       | 87.02%  |
| No        | 134       | 12.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 818       | 79.19%  |
| No        | 215       | 20.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 682       | 65.45%  |
| No        | 360       | 34.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Denmark | 1027      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Copenhagen               | 237       | 21.82%  |
| Frederiksberg            | 69        | 6.35%   |
| Odense                   | 57        | 5.25%   |
| Aarhus                   | 36        | 3.31%   |
| Bronshoj                 | 25        | 2.3%    |
| Silkeborg                | 23        | 2.12%   |
| Aalborg                  | 23        | 2.12%   |
| Slagelse                 | 22        | 2.03%   |
| Horsens                  | 22        | 2.03%   |
| Valby                    | 19        | 1.75%   |
| Esbjerg                  | 19        | 1.75%   |
| Glostrup Municipality    | 15        | 1.38%   |
| Aabenraa                 | 15        | 1.38%   |
| Holstebro                | 13        | 1.2%    |
| Roskilde                 | 12        | 1.1%    |
| Kongens Lyngby           | 12        | 1.1%    |
| Taastrup                 | 10        | 0.92%   |
| Nyborg                   | 10        | 0.92%   |
| Norresundby              | 10        | 0.92%   |
| Hvidovre                 | 10        | 0.92%   |
| Gentofte Municipality    | 10        | 0.92%   |
| Skanderborg              | 9         | 0.83%   |
| Herlev                   | 9         | 0.83%   |
| Vejle                    | 8         | 0.74%   |
| Risskov                  | 8         | 0.74%   |
| Naestved                 | 7         | 0.64%   |
| Køge                    | 7         | 0.64%   |
| Kastrup                  | 7         | 0.64%   |
| Viby J                   | 6         | 0.55%   |
| Vanlose                  | 6         | 0.55%   |
| Vaerlose                 | 6         | 0.55%   |
| Tilst                    | 6         | 0.55%   |
| Svendborg                | 6         | 0.55%   |
| Kolding                  | 6         | 0.55%   |
| Elsinore                 | 6         | 0.55%   |
| Albertslund Municipality | 6         | 0.55%   |
| Viborg                   | 5         | 0.46%   |
| Thisted                  | 5         | 0.46%   |
| Sindal                   | 5         | 0.46%   |
| Hojbjerg                 | 5         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 341       | 526    | 23.12%  |
| WDC                         | 179       | 262    | 12.14%  |
| Seagate                     | 175       | 246    | 11.86%  |
| Kingston                    | 122       | 175    | 8.27%   |
| Toshiba                     | 79        | 108    | 5.36%   |
| SanDisk                     | 67        | 89     | 4.54%   |
| Unknown                     | 53        | 60     | 3.59%   |
| SK hynix                    | 52        | 67     | 3.53%   |
| Intel                       | 52        | 64     | 3.53%   |
| Hitachi                     | 42        | 56     | 2.85%   |
| Crucial                     | 40        | 50     | 2.71%   |
| Micron Technology           | 27        | 32     | 1.83%   |
| HGST                        | 23        | 32     | 1.56%   |
| Intenso                     | 18        | 23     | 1.22%   |
| LITEON                      | 15        | 29     | 1.02%   |
| A-DATA Technology           | 15        | 16     | 1.02%   |
| PNY                         | 14        | 16     | 0.95%   |
| Apple                       | 14        | 20     | 0.95%   |
| Phison Electronics          | 11        | 16     | 0.75%   |
| Corsair                     | 11        | 14     | 0.75%   |
| OCZ                         | 10        | 10     | 0.68%   |
| Phison                      | 9         | 13     | 0.61%   |
| Kingston Technology Company | 7         | 7      | 0.47%   |
| LITEONIT                    | 6         | 7      | 0.41%   |
| KIOXIA                      | 5         | 6      | 0.34%   |
| Fujitsu                     | 5         | 10     | 0.34%   |
| China                       | 5         | 6      | 0.34%   |
| Micron/Crucial Technology   | 4         | 4      | 0.27%   |
| Lenovo                      | 4         | 5      | 0.27%   |
| JMicron Technology          | 4         | 4      | 0.27%   |
| XPG                         | 3         | 3      | 0.2%    |
| Verbatim                    | 3         | 6      | 0.2%    |
| USB3.0                      | 3         | 3      | 0.2%    |
| Transcend                   | 3         | 3      | 0.2%    |
| Silicon Motion              | 3         | 3      | 0.2%    |
| Team                        | 2         | 2      | 0.14%   |
| Solid State Storage         | 2         | 2      | 0.14%   |
| Realtek Semiconductor       | 2         | 3      | 0.14%   |
| Patriot                     | 2         | 3      | 0.14%   |
| Maxtor                      | 2         | 2      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 22        | 1.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 21        | 1.28%   |
| Samsung SSD 850 EVO 250GB                           | 19        | 1.16%   |
| Kingston SA400S37480G 480GB SSD                     | 18        | 1.1%    |
| Samsung SSD 850 EVO 500GB                           | 16        | 0.98%   |
| Kingston SA400S37240G 240GB SSD                     | 16        | 0.98%   |
| Kingston SV300S37A120G 120GB SSD                    | 14        | 0.85%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 13        | 0.79%   |
| Samsung SSD 860 EVO 500GB                           | 12        | 0.73%   |
| Samsung SSD 860 QVO 1TB                             | 11        | 0.67%   |
| Samsung SSD 860 EVO 1TB                             | 11        | 0.67%   |
| Unknown MMC Card  64GB                              | 10        | 0.61%   |
| Samsung SSD 840 EVO 250GB                           | 10        | 0.61%   |
| Samsung NVMe SSD Drive 512GB                        | 10        | 0.61%   |
| Samsung NVMe SSD Drive 500GB                        | 10        | 0.61%   |
| Samsung NVMe SSD Drive 1TB                          | 10        | 0.61%   |
| Unknown MMC Card  32GB                              | 9         | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB                      | 9         | 0.55%   |
| Kingston SA400S37120G 120GB SSD                     | 9         | 0.55%   |
| HGST HTS721010A9E630 1TB                            | 8         | 0.49%   |
| Toshiba NVMe SSD Drive 256GB                        | 7         | 0.43%   |
| SK hynix NVMe SSD Drive 512GB                       | 7         | 0.43%   |
| Seagate ST500DM002-1BD142 500GB                     | 7         | 0.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB | 7         | 0.43%   |
| PNY CS900 120GB SSD                                 | 7         | 0.43%   |
| Kingston SV300S37A240G 240GB SSD                    | 7         | 0.43%   |
| Toshiba NVMe SSD Drive 512GB                        | 6         | 0.37%   |
| Seagate ST1000DM010-2EP102 1TB                      | 6         | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6         | 0.37%   |
| Phison E12 NVMe Controller 1TB                      | 6         | 0.37%   |
| Kingston SUV400S37240G 240GB SSD                    | 6         | 0.37%   |
| Kingston SUV400S37120G 120GB SSD                    | 6         | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                         | 6         | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 5         | 0.3%    |
| Toshiba XG6 NVMe SSD Controller 512GB               | 5         | 0.3%    |
| Toshiba MQ01ABD100 1TB                              | 5         | 0.3%    |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 5         | 0.3%    |
| Seagate ST2000LM015-2E8174 2TB                      | 5         | 0.3%    |
| Seagate ST1000DM003-1SB10C 1TB                      | 5         | 0.3%    |
| Seagate ST1000DM003-1SB102 1TB                      | 5         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 169       | 237    | 38.32%  |
| WDC                 | 129       | 205    | 29.25%  |
| Hitachi             | 42        | 56     | 9.52%   |
| Toshiba             | 40        | 51     | 9.07%   |
| HGST                | 23        | 32     | 5.22%   |
| Samsung Electronics | 14        | 21     | 3.17%   |
| Fujitsu             | 5         | 10     | 1.13%   |
| Unknown             | 4         | 5      | 0.91%   |
| USB3.0              | 3         | 3      | 0.68%   |
| Apple               | 3         | 7      | 0.68%   |
| Maxtor              | 2         | 2      | 0.45%   |
| Unknown             | 2         | 4      | 0.45%   |
| USB                 | 1         | 1      | 0.23%   |
| Intenso             | 1         | 2      | 0.23%   |
| Hewlett-Packard     | 1         | 3      | 0.23%   |
| ASMT109x            | 1         | 1      | 0.23%   |
| Apricorn            | 1         | 2      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 181       | 266    | 32.67%  |
| Kingston            | 101       | 140    | 18.23%  |
| Crucial             | 34        | 44     | 6.14%   |
| SanDisk             | 31        | 36     | 5.6%    |
| WDC                 | 22        | 25     | 3.97%   |
| Intel               | 22        | 29     | 3.97%   |
| Toshiba             | 14        | 16     | 2.53%   |
| PNY                 | 14        | 16     | 2.53%   |
| LITEON              | 14        | 28     | 2.53%   |
| Intenso             | 13        | 15     | 2.35%   |
| SK hynix            | 12        | 14     | 2.17%   |
| Micron Technology   | 12        | 14     | 2.17%   |
| A-DATA Technology   | 12        | 12     | 2.17%   |
| OCZ                 | 10        | 10     | 1.81%   |
| Apple               | 9         | 9      | 1.62%   |
| LITEONIT            | 6         | 7      | 1.08%   |
| Corsair             | 6         | 7      | 1.08%   |
| China               | 5         | 6      | 0.9%    |
| JMicron Technology  | 4         | 4      | 0.72%   |
| Verbatim            | 3         | 6      | 0.54%   |
| Transcend           | 2         | 2      | 0.36%   |
| Team                | 2         | 2      | 0.36%   |
| Patriot             | 2         | 3      | 0.36%   |
| Leven               | 2         | 2      | 0.36%   |
| AFOX                | 2         | 2      | 0.36%   |
| Unknown (CF)        | 1         | 1      | 0.18%   |
| Teclast             | 1         | 1      | 0.18%   |
| Supersonic          | 1         | 1      | 0.18%   |
| SPCC                | 1         | 1      | 0.18%   |
| Shark               | 1         | 1      | 0.18%   |
| Ramaxel Technology  | 1         | 1      | 0.18%   |
| Plextor             | 1         | 1      | 0.18%   |
| OCZ-VERTEX3         | 1         | 3      | 0.18%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.18%   |
| KingFast            | 1         | 1      | 0.18%   |
| KingDian            | 1         | 1      | 0.18%   |
| Kingchuxing         | 1         | 1      | 0.18%   |
| INDMEM              | 1         | 1      | 0.18%   |
| GOODRAM             | 1         | 5      | 0.18%   |
| FORESEE             | 1         | 1      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 488       | 741    | 36.97%  |
| NVMe    | 405       | 604    | 30.68%  |
| HDD     | 363       | 642    | 27.5%   |
| MMC     | 50        | 56     | 3.79%   |
| Unknown | 14        | 15     | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 704       | 1331   | 57.94%  |
| NVMe | 404       | 602    | 33.25%  |
| SAS  | 57        | 69     | 4.69%   |
| MMC  | 50        | 56     | 4.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 539       | 835    | 59.43%  |
| 0.51-1.0   | 215       | 298    | 23.7%   |
| 1.01-2.0   | 81        | 126    | 8.93%   |
| 4.01-10.0  | 26        | 51     | 2.87%   |
| 2.01-3.0   | 21        | 34     | 2.32%   |
| 3.01-4.0   | 18        | 26     | 1.98%   |
| 10.01-20.0 | 7         | 13     | 0.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 281       | 25.66%  |
| 251-500        | 216       | 19.73%  |
| 501-1000       | 177       | 16.16%  |
| 1001-2000      | 86        | 7.85%   |
| 1-20           | 78        | 7.12%   |
| More than 3000 | 64        | 5.84%   |
| 51-100         | 62        | 5.66%   |
| Unknown        | 52        | 4.75%   |
| 21-50          | 40        | 3.65%   |
| 2001-3000      | 39        | 3.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 419       | 37.51%  |
| 21-50          | 186       | 16.65%  |
| 101-250        | 131       | 11.73%  |
| 51-100         | 110       | 9.85%   |
| 251-500        | 92        | 8.24%   |
| 501-1000       | 67        | 6%      |
| Unknown        | 52        | 4.66%   |
| 1001-2000      | 30        | 2.69%   |
| More than 3000 | 21        | 1.88%   |
| 2001-3000      | 9         | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD      | 3         | 5      | 4.41%   |
| Kingston SHPM2280P2H 480G SSD         | 3         | 3      | 4.41%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 2.94%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 2      | 2.94%   |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 2.94%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 1.47%   |
| WDC WD5000BPVT-80HXZT3 500GB          | 1         | 1      | 1.47%   |
| WDC WD5000BEVT-35ZAT0 500GB           | 1         | 1      | 1.47%   |
| WDC WD5000AAKX-001CA0 500GB           | 1         | 1      | 1.47%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 1.47%   |
| WDC WD1600BEVT-00M9YT0 160GB          | 1         | 1      | 1.47%   |
| WDC WD10EZRX-00A8LB0 1TB              | 1         | 1      | 1.47%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 1      | 1.47%   |
| WDC WD10EURX-73FH1Y0 1TB              | 1         | 1      | 1.47%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 1.47%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 1.47%   |
| Toshiba MQ02ABD100H 1TB               | 1         | 1      | 1.47%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.47%   |
| Toshiba KSG60ZSE256G SATA 256GB SSD   | 1         | 1      | 1.47%   |
| Toshiba DT01ACA050 500GB              | 1         | 1      | 1.47%   |
| SK hynix SC308 SATA 256GB SSD         | 1         | 1      | 1.47%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 1.47%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 1.47%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.47%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 1.47%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 1.47%   |
| Seagate ST380013AS 80GB               | 1         | 1      | 1.47%   |
| Seagate ST3400633AS 400GB             | 1         | 1      | 1.47%   |
| Seagate ST3250318AS 250GB             | 1         | 1      | 1.47%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 1.47%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 1.47%   |
| Seagate ST3200822AS 200GB             | 1         | 1      | 1.47%   |
| Seagate ST31500341AS 1TB              | 1         | 1      | 1.47%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 1.47%   |
| Seagate ST2000DX002-2DV164 2TB        | 1         | 1      | 1.47%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 1      | 1.47%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB        | 1         | 1      | 1.47%   |
| SanDisk SSD U100 24GB                 | 1         | 1      | 1.47%   |
| SanDisk SDSSDX240GG25 240GB           | 1         | 1      | 1.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 23.81%  |
| Kingston            | 10        | 12     | 15.87%  |
| WDC                 | 9         | 10     | 14.29%  |
| Toshiba             | 5         | 5      | 7.94%   |
| Samsung Electronics | 4         | 5      | 6.35%   |
| HGST                | 4         | 4      | 6.35%   |
| SK hynix            | 3         | 3      | 4.76%   |
| SanDisk             | 2         | 2      | 3.17%   |
| OCZ                 | 2         | 2      | 3.17%   |
| Intel               | 2         | 2      | 3.17%   |
| Hitachi             | 2         | 4      | 3.17%   |
| Micron Technology   | 1         | 1      | 1.59%   |
| Leven               | 1         | 1      | 1.59%   |
| Crucial             | 1         | 1      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |
| Unknown             | 1         | 2      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 41.67%  |
| WDC                 | 8         | 9      | 22.22%  |
| HGST                | 4         | 4      | 11.11%  |
| Toshiba             | 3         | 3      | 8.33%   |
| Samsung Electronics | 2         | 3      | 5.56%   |
| Hitachi             | 2         | 4      | 5.56%   |
| Apple               | 1         | 1      | 2.78%   |
| Unknown             | 1         | 2      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 43     | 55.17%  |
| SSD  | 24        | 27     | 41.38%  |
| NVMe | 2         | 2      | 3.45%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 685       | 1319   | 61.16%  |
| Works    | 377       | 667    | 33.66%  |
| Malfunc  | 58        | 72     | 5.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 638       | 47.83%  |
| AMD                              | 189       | 14.17%  |
| Samsung Electronics              | 180       | 13.49%  |
| SanDisk                          | 61        | 4.57%   |
| SK hynix                         | 39        | 2.92%   |
| Kingston Technology Company      | 36        | 2.7%    |
| ASMedia Technology               | 26        | 1.95%   |
| Phison Electronics               | 25        | 1.87%   |
| Toshiba America Info Systems     | 24        | 1.8%    |
| Nvidia                           | 20        | 1.5%    |
| Micron Technology                | 16        | 1.2%    |
| JMicron Technology               | 14        | 1.05%   |
| Marvell Technology Group         | 12        | 0.9%    |
| Micron/Crucial Technology        | 9         | 0.67%   |
| Silicon Motion                   | 7         | 0.52%   |
| ADATA Technology                 | 7         | 0.52%   |
| Seagate Technology               | 5         | 0.37%   |
| KIOXIA                           | 5         | 0.37%   |
| Lenovo                           | 4         | 0.3%    |
| VIA Technologies                 | 2         | 0.15%   |
| Union Memory (Shenzhen)          | 2         | 0.15%   |
| Solid State Storage Technology   | 2         | 0.15%   |
| Realtek Semiconductor            | 2         | 0.15%   |
| Hewlett-Packard                  | 2         | 0.15%   |
| Apple                            | 2         | 0.15%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| LSI Logic / Symbios Logic        | 1         | 0.07%   |
| Lite-On Technology               | 1         | 0.07%   |
| HighPoint Technologies           | 1         | 0.07%   |
| Broadcom / LSI                   | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 143       | 9.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 94        | 6.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 58        | 3.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 47        | 3.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 43        | 2.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 37        | 2.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 36        | 2.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 31        | 2.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 30        | 1.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 28        | 1.85%   |
| AMD 400 Series Chipset SATA Controller                                         | 28        | 1.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 27        | 1.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 24        | 1.59%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 24        | 1.59%   |
| Intel Volume Management Device NVMe RAID Controller                            | 21        | 1.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 21        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 20        | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 19        | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 19        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 19        | 1.26%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 18        | 1.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 18        | 1.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 18        | 1.19%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 16        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 16        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 16        | 1.06%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 15        | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 14        | 0.93%   |
| AMD 500 Series Chipset SATA Controller                                         | 14        | 0.93%   |
| Phison E12 NVMe Controller                                                     | 13        | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 13        | 0.86%   |
| Intel SSD 660P Series                                                          | 13        | 0.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 12        | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 12        | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 11        | 0.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 10        | 0.66%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 10        | 0.66%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 10        | 0.66%   |
| Intel Comet Lake SATA AHCI Controller                                          | 10        | 0.66%   |
| Phison E16 PCIe4 NVMe Controller                                               | 9         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 748       | 56.33%  |
| NVMe | 407       | 30.65%  |
| IDE  | 110       | 8.28%   |
| RAID | 62        | 4.67%   |
| SAS  | 1         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 756       | 73.61%  |
| AMD      | 257       | 25.02%  |
| ARM      | 13        | 1.27%   |
| QUALCOMM | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 15        | 1.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 14        | 1.36%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 14        | 1.36%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 11        | 1.07%   |
| AMD Ryzen 5 3600 6-Core Processor          | 11        | 1.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 10        | 0.97%   |
| Intel Core i5-4300U CPU @ 1.90GHz          | 10        | 0.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 9         | 0.87%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 9         | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 9         | 0.87%   |
| ARM Processor                              | 9         | 0.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 8         | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 8         | 0.78%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 8         | 0.78%   |
| AMD Ryzen 7 5700U with Radeon Graphics     | 8         | 0.78%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 8         | 0.78%   |
| AMD Ryzen 7 2700X Eight-Core Processor     | 8         | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 7         | 0.68%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 7         | 0.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 7         | 0.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 7         | 0.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz          | 7         | 0.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 7         | 0.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 7         | 0.68%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 7         | 0.68%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 6         | 0.58%   |
| Intel Core i7-3610QM CPU @ 2.30GHz         | 6         | 0.58%   |
| Intel Core i5-7500 CPU @ 3.40GHz           | 6         | 0.58%   |
| Intel Core i5-6600K CPU @ 3.50GHz          | 6         | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 6         | 0.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 6         | 0.58%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 6         | 0.58%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 5         | 0.49%   |
| Intel Core i7-8665U CPU @ 1.90GHz          | 5         | 0.49%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 5         | 0.49%   |
| Intel Core i7-7600U CPU @ 2.80GHz          | 5         | 0.49%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 5         | 0.49%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 5         | 0.49%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 5         | 0.49%   |
| Intel Core i5-8300H CPU @ 2.30GHz          | 5         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 255       | 24.81%  |
| Intel Core i7           | 238       | 23.15%  |
| Other                   | 65        | 6.32%   |
| AMD Ryzen 7             | 64        | 6.23%   |
| AMD Ryzen 5             | 51        | 4.96%   |
| Intel Core i3           | 49        | 4.77%   |
| Intel Core 2 Duo        | 41        | 3.99%   |
| AMD Ryzen 9             | 34        | 3.31%   |
| Intel Celeron           | 30        | 2.92%   |
| Intel Xeon              | 16        | 1.56%   |
| Intel Pentium           | 13        | 1.26%   |
| Intel Core i9           | 13        | 1.26%   |
| AMD Ryzen 7 PRO         | 13        | 1.26%   |
| AMD FX                  | 11        | 1.07%   |
| Intel Atom              | 10        | 0.97%   |
| AMD A6                  | 10        | 0.97%   |
| Intel Pentium Dual-Core | 9         | 0.88%   |
| AMD Ryzen 3             | 9         | 0.88%   |
| AMD A8                  | 8         | 0.78%   |
| Intel Pentium Silver    | 6         | 0.58%   |
| Intel Core 2 Quad       | 5         | 0.49%   |
| AMD A10                 | 5         | 0.49%   |
| Intel Core 2            | 4         | 0.39%   |
| ARM BCM                 | 4         | 0.39%   |
| AMD Ryzen Threadripper  | 4         | 0.39%   |
| AMD Ryzen 5 PRO         | 4         | 0.39%   |
| AMD Phenom II X4        | 4         | 0.39%   |
| AMD E1                  | 4         | 0.39%   |
| AMD E                   | 4         | 0.39%   |
| AMD Athlon 64 X2        | 4         | 0.39%   |
| AMD A4                  | 4         | 0.39%   |
| Intel Pentium M         | 3         | 0.29%   |
| Intel Pentium Dual      | 3         | 0.29%   |
| Intel Core m5           | 3         | 0.29%   |
| AMD Turion 64 X2 Mobile | 3         | 0.29%   |
| AMD Athlon II X4        | 3         | 0.29%   |
| AMD Athlon              | 3         | 0.29%   |
| Intel Genuine           | 2         | 0.19%   |
| Intel Core m3           | 2         | 0.19%   |
| AMD Athlon II Neo       | 2         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 376       | 36.54%  |
| 4       | 363       | 35.28%  |
| 8       | 107       | 10.4%   |
| 6       | 106       | 10.3%   |
| 12      | 26        | 2.53%   |
| 1       | 19        | 1.85%   |
| 16      | 14        | 1.36%   |
| 10      | 6         | 0.58%   |
| 24      | 3         | 0.29%   |
| 14      | 3         | 0.29%   |
| Unknown | 3         | 0.29%   |
| 64      | 1         | 0.1%    |
| 32      | 1         | 0.1%    |
| 3       | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1020      | 99.32%  |
| 2       | 4         | 0.39%   |
| Unknown | 3         | 0.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 735       | 71.57%  |
| 1       | 288       | 28.04%  |
| Unknown | 3         | 0.29%   |
| 4       | 1         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 995       | 96.41%  |
| Unknown        | 30        | 2.91%   |
| 32-bit         | 6         | 0.58%   |
| 64-bit         | 1         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 328       | 30.68%  |
| 0x306a9    | 47        | 4.4%    |
| 0x206a7    | 43        | 4.02%   |
| 0x306c3    | 42        | 3.93%   |
| 0x40651    | 30        | 2.81%   |
| 0x1067a    | 29        | 2.71%   |
| 0x906ea    | 28        | 2.62%   |
| 0x406e3    | 28        | 2.62%   |
| 0x806e9    | 24        | 2.25%   |
| 0x506e3    | 24        | 2.25%   |
| 0x806ea    | 23        | 2.15%   |
| 0x906e9    | 18        | 1.68%   |
| 0x806ec    | 18        | 1.68%   |
| 0x20655    | 15        | 1.4%    |
| 0x08600106 | 15        | 1.4%    |
| 0x0a50000c | 14        | 1.31%   |
| 0x806c1    | 12        | 1.12%   |
| 0x08701021 | 12        | 1.12%   |
| 0x906ed    | 11        | 1.03%   |
| 0x0800820d | 11        | 1.03%   |
| 0x6fd      | 9         | 0.84%   |
| 0x08001138 | 9         | 0.84%   |
| 0x90672    | 8         | 0.75%   |
| 0x806eb    | 8         | 0.75%   |
| 0x20652    | 8         | 0.75%   |
| 0x706e5    | 7         | 0.65%   |
| 0x306d4    | 7         | 0.65%   |
| 0x10676    | 7         | 0.65%   |
| 0x0a601203 | 7         | 0.65%   |
| 0x08701013 | 7         | 0.65%   |
| 0x0810100b | 7         | 0.65%   |
| 0x010000c8 | 7         | 0.65%   |
| 0x406c3    | 6         | 0.56%   |
| 0x0a404102 | 6         | 0.56%   |
| 0x0a201009 | 6         | 0.56%   |
| 0x08608103 | 6         | 0.56%   |
| 0x08600104 | 6         | 0.56%   |
| 0x07030105 | 6         | 0.56%   |
| 0x08108109 | 5         | 0.47%   |
| 0x08108102 | 5         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 194       | 18.85%  |
| Haswell          | 102       | 9.91%   |
| Skylake          | 82        | 7.97%   |
| SandyBridge      | 67        | 6.51%   |
| IvyBridge        | 65        | 6.32%   |
| Unknown          | 61        | 5.93%   |
| Zen 2            | 59        | 5.73%   |
| Penryn           | 48        | 4.66%   |
| Zen 3            | 44        | 4.28%   |
| Westmere         | 28        | 2.72%   |
| Zen+             | 26        | 2.53%   |
| Broadwell        | 23        | 2.24%   |
| Core             | 22        | 2.14%   |
| Zen              | 21        | 2.04%   |
| TigerLake        | 21        | 2.04%   |
| Silvermont       | 17        | 1.65%   |
| CometLake        | 17        | 1.65%   |
| Alderlake Hybrid | 16        | 1.55%   |
| Piledriver       | 12        | 1.17%   |
| K10              | 12        | 1.17%   |
| IceLake          | 12        | 1.17%   |
| Puma             | 9         | 0.87%   |
| Goldmont plus    | 9         | 0.87%   |
| Nehalem          | 8         | 0.78%   |
| K8 Hammer        | 8         | 0.78%   |
| Excavator        | 7         | 0.68%   |
| Bobcat           | 6         | 0.58%   |
| Steamroller      | 5         | 0.49%   |
| P6               | 5         | 0.49%   |
| Goldmont         | 5         | 0.49%   |
| Bonnell          | 5         | 0.49%   |
| Jaguar           | 4         | 0.39%   |
| K8 & K10 hybrid  | 3         | 0.29%   |
| K10 Llano        | 3         | 0.29%   |
| Bulldozer        | 3         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 562       | 46.76%  |
| Nvidia                           | 372       | 30.95%  |
| AMD                              | 263       | 21.88%  |
| Matrox Electronics Systems       | 2         | 0.17%   |
| ASPEED Technology                | 2         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 50        | 4.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 40        | 3.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 39        | 3.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 34        | 2.75%   |
| Intel UHD Graphics 620                                                                   | 32        | 2.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 30        | 2.43%   |
| Intel HD Graphics 620                                                                    | 29        | 2.35%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 25        | 2.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 24        | 1.94%   |
| Intel HD Graphics 630                                                                    | 22        | 1.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 1.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 1.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 1.54%   |
| Intel HD Graphics 530                                                                    | 17        | 1.38%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 16        | 1.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 15        | 1.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 1.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 0.97%   |
| Intel HD Graphics 5500                                                                   | 12        | 0.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 0.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 0.89%   |
| AMD Lucienne                                                                             | 11        | 0.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 9         | 0.73%   |
| AMD Rembrandt [Radeon 680M]                                                              | 9         | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 8         | 0.65%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 8         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.57%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.57%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 7         | 0.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 0.57%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.57%   |
| AMD Raphael                                                                              | 7         | 0.57%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 398       | 38.53%  |
| 1 x Nvidia      | 222       | 21.49%  |
| 1 x AMD         | 198       | 19.17%  |
| Intel + Nvidia  | 125       | 12.1%   |
| Intel + AMD     | 22        | 2.13%   |
| 2 x AMD         | 21        | 2.03%   |
| AMD + Nvidia    | 21        | 2.03%   |
| Other           | 16        | 1.55%   |
| 2 x Intel       | 3         | 0.29%   |
| 2 x Nvidia      | 2         | 0.19%   |
| 1 x Matrox      | 2         | 0.19%   |
| 1 x SiS         | 1         | 0.1%    |
| Nvidia + ASPEED | 1         | 0.1%    |
| 1 x ASPEED      | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 792       | 75.64%  |
| Proprietary | 212       | 20.25%  |
| Unknown     | 43        | 4.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 590       | 56.19%  |
| 1.01-2.0   | 128       | 12.19%  |
| 0.01-0.5   | 110       | 10.48%  |
| 7.01-8.0   | 62        | 5.9%    |
| 3.01-4.0   | 52        | 4.95%   |
| 0.51-1.0   | 46        | 4.38%   |
| 5.01-6.0   | 32        | 3.05%   |
| 8.01-16.0  | 18        | 1.71%   |
| 2.01-3.0   | 7         | 0.67%   |
| 16.01-24.0 | 4         | 0.38%   |
| 4.01-5.0   | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 164       | 14.16%  |
| AU Optronics            | 148       | 12.78%  |
| LG Display              | 111       | 9.59%   |
| Chimei Innolux          | 79        | 6.82%   |
| BOE                     | 78        | 6.74%   |
| Dell                    | 67        | 5.79%   |
| Lenovo                  | 60        | 5.18%   |
| Philips                 | 38        | 3.28%   |
| AOC                     | 38        | 3.28%   |
| Hewlett-Packard         | 35        | 3.02%   |
| Apple                   | 32        | 2.76%   |
| Acer                    | 27        | 2.33%   |
| BenQ                    | 26        | 2.25%   |
| Ancor Communications    | 26        | 2.25%   |
| ASUSTek Computer        | 23        | 1.99%   |
| Goldstar                | 21        | 1.81%   |
| Sharp                   | 19        | 1.64%   |
| Sony                    | 15        | 1.3%    |
| Chi Mei Optoelectronics | 15        | 1.3%    |
| InfoVision              | 9         | 0.78%   |
| PANDA                   | 8         | 0.69%   |
| Panasonic               | 8         | 0.69%   |
| Medion                  | 8         | 0.69%   |
| Unknown                 | 6         | 0.52%   |
| MSI                     | 6         | 0.52%   |
| Lenovo Group Limited    | 6         | 0.52%   |
| Valve                   | 5         | 0.43%   |
| Packard Bell            | 5         | 0.43%   |
| IBM                     | 5         | 0.43%   |
| ViewSonic               | 4         | 0.35%   |
| LG Electronics          | 4         | 0.35%   |
| Gigabyte Technology     | 4         | 0.35%   |
| Fujitsu Siemens         | 4         | 0.35%   |
| Vestel Elektronik       | 3         | 0.26%   |
| LG Philips              | 3         | 0.26%   |
| CSO                     | 3         | 0.26%   |
| TMX                     | 2         | 0.17%   |
| Tech Concepts           | 2         | 0.17%   |
| Seiko/Epson             | 2         | 0.17%   |
| LGD                     | 2         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 8         | 0.65%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 7         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.49%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 6         | 0.49%   |
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch             | 6         | 0.49%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                 | 5         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 5         | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.41%   |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                          | 5         | 0.41%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 4         | 0.33%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 4         | 0.33%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 4         | 0.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.33%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                      | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 4         | 0.33%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                       | 4         | 0.33%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                         | 4         | 0.33%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 4         | 0.33%   |
| Acer KG241Q ACR0604 1920x1080 521x293mm 23.5-inch                        | 4         | 0.33%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 3         | 0.25%   |
| Sony TV SNYEE01 1920x1080                                                | 3         | 0.25%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 3         | 0.25%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                        | 3         | 0.25%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch                 | 3         | 0.25%   |
| Packard Bell Maestro223DXL PKB01B2 1920x1080 477x268mm 21.5-inch         | 3         | 0.25%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.25%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 3         | 0.25%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch               | 3         | 0.25%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch                 | 3         | 0.25%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 3         | 0.25%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 3         | 0.25%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch          | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch         | 3         | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 3         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 506       | 45.63%  |
| 1366x768 (WXGA)    | 113       | 10.19%  |
| 3840x2160 (4K)     | 98        | 8.84%   |
| 2560x1440 (QHD)    | 92        | 8.3%    |
| 1600x900 (HD+)     | 60        | 5.41%   |
| 1680x1050 (WSXGA+) | 32        | 2.89%   |
| 1920x1200 (WUXGA)  | 25        | 2.25%   |
| 1280x800 (WXGA)    | 22        | 1.98%   |
| 1280x1024 (SXGA)   | 21        | 1.89%   |
| 1440x900 (WXGA+)   | 19        | 1.71%   |
| Unknown            | 19        | 1.71%   |
| 3440x1440          | 16        | 1.44%   |
| 2560x1600          | 13        | 1.17%   |
| 2880x1800          | 9         | 0.81%   |
| 3840x1080          | 8         | 0.72%   |
| 800x1280           | 5         | 0.45%   |
| 1360x768           | 5         | 0.45%   |
| 1920x540           | 4         | 0.36%   |
| 3840x1200          | 3         | 0.27%   |
| 3200x1800 (QHD+)   | 3         | 0.27%   |
| 2160x1440          | 3         | 0.27%   |
| 1400x1050          | 3         | 0.27%   |
| 3840x2400          | 2         | 0.18%   |
| 3840x1600          | 2         | 0.18%   |
| 3000x2000          | 2         | 0.18%   |
| 2560x1080          | 2         | 0.18%   |
| 1024x600           | 2         | 0.18%   |
| 9840x3840          | 1         | 0.09%   |
| 6400x2160          | 1         | 0.09%   |
| 5760x1440          | 1         | 0.09%   |
| 5760x1080          | 1         | 0.09%   |
| 5120x1440          | 1         | 0.09%   |
| 4608x1440          | 1         | 0.09%   |
| 4480x1440          | 1         | 0.09%   |
| 3840x1100          | 1         | 0.09%   |
| 3280x1080          | 1         | 0.09%   |
| 3200x1200          | 1         | 0.09%   |
| 3200x1080          | 1         | 0.09%   |
| 3072x1920          | 1         | 0.09%   |
| 2736x1824          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 247       | 21.33%  |
| 27      | 125       | 10.79%  |
| 14      | 123       | 10.62%  |
| 13      | 111       | 9.59%   |
| 24      | 97        | 8.38%   |
| Unknown | 66        | 5.7%    |
| 23      | 59        | 5.09%   |
| 17      | 58        | 5.01%   |
| 31      | 39        | 3.37%   |
| 21      | 37        | 3.2%    |
| 12      | 28        | 2.42%   |
| 22      | 22        | 1.9%    |
| 19      | 21        | 1.81%   |
| 34      | 15        | 1.3%    |
| 20      | 15        | 1.3%    |
| 84      | 12        | 1.04%   |
| 72      | 12        | 1.04%   |
| 11      | 8         | 0.69%   |
| 18      | 6         | 0.52%   |
| 16      | 6         | 0.52%   |
| 32      | 5         | 0.43%   |
| 25      | 5         | 0.43%   |
| 40      | 4         | 0.35%   |
| 7       | 4         | 0.35%   |
| 10      | 3         | 0.26%   |
| 65      | 2         | 0.17%   |
| 55      | 2         | 0.17%   |
| 54      | 2         | 0.17%   |
| 48      | 2         | 0.17%   |
| 38      | 2         | 0.17%   |
| 37      | 2         | 0.17%   |
| 35      | 2         | 0.17%   |
| 33      | 2         | 0.17%   |
| 29      | 2         | 0.17%   |
| 28      | 2         | 0.17%   |
| 75      | 1         | 0.09%   |
| 74      | 1         | 0.09%   |
| 60      | 1         | 0.09%   |
| 57      | 1         | 0.09%   |
| 43      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 417       | 36.87%  |
| 501-600     | 249       | 22.02%  |
| 201-300     | 102       | 9.02%   |
| 401-500     | 85        | 7.52%   |
| 351-400     | 78        | 6.9%    |
| Unknown     | 66        | 5.84%   |
| 601-700     | 58        | 5.13%   |
| 1501-2000   | 26        | 2.3%    |
| 701-800     | 22        | 1.95%   |
| 801-900     | 11        | 0.97%   |
| 1001-1500   | 11        | 0.97%   |
| 1-100       | 5         | 0.44%   |
| 901-1000    | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 777       | 75.15%  |
| 16/10   | 135       | 13.06%  |
| Unknown | 55        | 5.32%   |
| 21/9    | 20        | 1.93%   |
| 5/4     | 19        | 1.84%   |
| 3/2     | 12        | 1.16%   |
| 4/3     | 5         | 0.48%   |
| 32/9    | 4         | 0.39%   |
| 0.67    | 4         | 0.39%   |
| 6/5     | 1         | 0.1%    |
| 3.40    | 1         | 0.1%    |
| 3.20    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 244       | 21.24%  |
| 81-90          | 185       | 16.1%   |
| 201-250        | 169       | 14.71%  |
| 301-350        | 125       | 10.88%  |
| Unknown        | 66        | 5.74%   |
| 351-500        | 65        | 5.66%   |
| 71-80          | 50        | 4.35%   |
| 121-130        | 44        | 3.83%   |
| 151-200        | 42        | 3.66%   |
| 251-300        | 41        | 3.57%   |
| More than 1000 | 34        | 2.96%   |
| 61-70          | 24        | 2.09%   |
| 501-1000       | 13        | 1.13%   |
| 131-140        | 11        | 0.96%   |
| 51-60          | 9         | 0.78%   |
| 141-150        | 9         | 0.78%   |
| 111-120        | 7         | 0.61%   |
| 1-40           | 5         | 0.44%   |
| 41-50          | 3         | 0.26%   |
| 91-100         | 3         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 332       | 30.02%  |
| 51-100        | 326       | 29.48%  |
| 101-120       | 240       | 21.7%   |
| 161-240       | 81        | 7.32%   |
| Unknown       | 66        | 5.97%   |
| More than 240 | 42        | 3.8%    |
| 1-50          | 19        | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 798       | 75.86%  |
| 2     | 181       | 17.21%  |
| 0     | 42        | 3.99%   |
| 3     | 29        | 2.76%   |
| 4     | 2         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 587       | 38.14%  |
| Realtek Semiconductor             | 474       | 30.8%   |
| Qualcomm Atheros                  | 130       | 8.45%   |
| Broadcom                          | 81        | 5.26%   |
| MediaTek                          | 28        | 1.82%   |
| Broadcom Limited                  | 20        | 1.3%    |
| Lenovo                            | 19        | 1.23%   |
| Nvidia                            | 18        | 1.17%   |
| Ralink                            | 16        | 1.04%   |
| Ralink Technology                 | 14        | 0.91%   |
| Sierra Wireless                   | 13        | 0.84%   |
| Ericsson Business Mobile Networks | 12        | 0.78%   |
| TP-Link                           | 10        | 0.65%   |
| Marvell Technology Group          | 8         | 0.52%   |
| DisplayLink                       | 8         | 0.52%   |
| Aquantia                          | 8         | 0.52%   |
| ASUSTek Computer                  | 7         | 0.45%   |
| ASIX Electronics                  | 7         | 0.45%   |
| Samsung Electronics               | 5         | 0.32%   |
| Qualcomm                          | 5         | 0.32%   |
| NetGear                           | 5         | 0.32%   |
| Microsoft                         | 5         | 0.32%   |
| Huawei Technologies               | 5         | 0.32%   |
| Dell                              | 5         | 0.32%   |
| Qualcomm Atheros Communications   | 4         | 0.26%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.26%   |
| IMC Networks                      | 4         | 0.26%   |
| D-Link System                     | 4         | 0.26%   |
| Xiaomi                            | 3         | 0.19%   |
| ICS Advent                        | 3         | 0.19%   |
| Edimax Technology                 | 3         | 0.19%   |
| D-Link                            | 3         | 0.19%   |
| Standard Microsystems             | 2         | 0.13%   |
| Microchip Technology              | 2         | 0.13%   |
| Linksys                           | 2         | 0.13%   |
| Hewlett-Packard                   | 2         | 0.13%   |
| ZyXEL Communications              | 1         | 0.06%   |
| Unknown                           | 1         | 0.06%   |
| Texas Instruments                 | 1         | 0.06%   |
| Solarflare Communications         | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 334       | 17.77%  |
| Intel Wi-Fi 6 AX200                                               | 58        | 3.09%   |
| Intel Wireless 8265 / 8275                                        | 50        | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 46        | 2.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 38        | 2.02%   |
| Intel Wireless 7260                                               | 37        | 1.97%   |
| Intel Wireless 8260                                               | 32        | 1.7%    |
| Intel I211 Gigabit Network Connection                             | 32        | 1.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 29        | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 28        | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 1.44%   |
| Intel Wireless 7265                                               | 25        | 1.33%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 24        | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 22        | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 18        | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 17        | 0.9%    |
| Intel Wireless-AC 9260                                            | 17        | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 17        | 0.9%    |
| Intel Wi-Fi 6 AX201                                               | 16        | 0.85%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 0.85%   |
| Intel Ethernet Controller I225-V                                  | 15        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 14        | 0.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 13        | 0.69%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 13        | 0.69%   |
| Intel Centrino Wireless-N 2230                                    | 13        | 0.69%   |
| Intel Centrino Ultimate-N 6300                                    | 13        | 0.69%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 0.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 0.59%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 11        | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 10        | 0.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 0.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 10        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 462       | 53.16%  |
| Realtek Semiconductor             | 102       | 11.74%  |
| Qualcomm Atheros                  | 101       | 11.62%  |
| Broadcom                          | 57        | 6.56%   |
| MediaTek                          | 27        | 3.11%   |
| Ralink                            | 16        | 1.84%   |
| Ralink Technology                 | 14        | 1.61%   |
| Broadcom Limited                  | 14        | 1.61%   |
| Sierra Wireless                   | 13        | 1.5%    |
| TP-Link                           | 10        | 1.15%   |
| ASUSTek Computer                  | 7         | 0.81%   |
| NetGear                           | 5         | 0.58%   |
| Microsoft                         | 5         | 0.58%   |
| Qualcomm Atheros Communications   | 4         | 0.46%   |
| Qualcomm                          | 4         | 0.46%   |
| IMC Networks                      | 4         | 0.46%   |
| Ericsson Business Mobile Networks | 4         | 0.46%   |
| Dell                              | 4         | 0.46%   |
| D-Link System                     | 4         | 0.46%   |
| Edimax Technology                 | 3         | 0.35%   |
| D-Link                            | 3         | 0.35%   |
| Marvell Technology Group          | 2         | 0.23%   |
| ZyXEL Communications              | 1         | 0.12%   |
| Philips (or NXP)                  | 1         | 0.12%   |
| Linksys                           | 1         | 0.12%   |
| Fibocom                           | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 58        | 6.64%   |
| Intel Wireless 8265 / 8275                                     | 50        | 5.73%   |
| Intel Wireless 7260                                            | 37        | 4.24%   |
| Intel Wireless 8260                                            | 32        | 3.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 28        | 3.21%   |
| Intel Wireless 7265                                            | 25        | 2.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 24        | 2.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 18        | 2.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 1.95%   |
| Intel Wireless-AC 9260                                         | 17        | 1.95%   |
| Intel Wi-Fi 6 AX201                                            | 16        | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 15        | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 14        | 1.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 13        | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 13        | 1.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 1.49%   |
| Intel Centrino Wireless-N 2230                                 | 13        | 1.49%   |
| Intel Centrino Ultimate-N 6300                                 | 13        | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 11        | 1.26%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 11        | 1.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 10        | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 10        | 1.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 9         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 8         | 0.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 8         | 0.92%   |
| Intel Wireless 3165                                            | 8         | 0.92%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A            | 7         | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 7         | 0.8%    |
| Ralink RT5370 Wireless Adapter                                 | 7         | 0.8%    |
| Intel Wireless 3160                                            | 7         | 0.8%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 7         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 6         | 0.69%   |
| Realtek 802.11ac NIC                                           | 6         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 432       | 44.77%  |
| Intel                            | 357       | 36.99%  |
| Qualcomm Atheros                 | 41        | 4.25%   |
| Broadcom                         | 35        | 3.63%   |
| Lenovo                           | 19        | 1.97%   |
| Nvidia                           | 18        | 1.87%   |
| DisplayLink                      | 8         | 0.83%   |
| Aquantia                         | 8         | 0.83%   |
| ASIX Electronics                 | 7         | 0.73%   |
| Marvell Technology Group         | 6         | 0.62%   |
| Broadcom Limited                 | 6         | 0.62%   |
| Samsung Electronics              | 4         | 0.41%   |
| Xiaomi                           | 3         | 0.31%   |
| OnePlus Technology (Shenzhen)    | 3         | 0.31%   |
| ICS Advent                       | 3         | 0.31%   |
| Standard Microsystems            | 2         | 0.21%   |
| Microchip Technology             | 2         | 0.21%   |
| Huawei Technologies              | 2         | 0.21%   |
| Solarflare Communications        | 1         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |
| Qualcomm                         | 1         | 0.1%    |
| MediaTek                         | 1         | 0.1%    |
| Linksys                          | 1         | 0.1%    |
| JMicron Technology               | 1         | 0.1%    |
| HMD Global                       | 1         | 0.1%    |
| Hewlett-Packard                  | 1         | 0.1%    |
| Google                           | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 334       | 33.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 46        | 4.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 38        | 3.85%   |
| Intel I211 Gigabit Network Connection                             | 32        | 3.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 29        | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 2.74%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 2.54%   |
| Intel Ethernet Connection I217-LM                                 | 22        | 2.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 1.93%   |
| Intel Ethernet Connection (7) I219-V                              | 17        | 1.72%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 1.62%   |
| Intel Ethernet Controller I225-V                                  | 15        | 1.52%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 1.32%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 1.22%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 1.01%   |
| Intel Ethernet Connection I219-V                                  | 9         | 0.91%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.81%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.81%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.71%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.71%   |
| Intel Ethernet Connection (5) I219-LM                             | 7         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.61%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 0.61%   |
| Intel 82566MM Gigabit Network Connection                          | 6         | 0.61%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.51%   |
| Lenovo USB-C Dock Ethernet                                        | 5         | 0.51%   |
| Lenovo ThinkPad Lan                                               | 5         | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                             | 5         | 0.51%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5         | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 896       | 51.67%  |
| WiFi     | 817       | 47.12%  |
| Modem    | 17        | 0.98%   |
| Unknown  | 4         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 625       | 57.92%  |
| Ethernet | 454       | 42.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 613       | 59.4%   |
| 1     | 364       | 35.27%  |
| 3     | 29        | 2.81%   |
| 0     | 22        | 2.13%   |
| 4     | 3         | 0.29%   |
| 5     | 1         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 979       | 94.86%  |
| Yes  | 53        | 5.14%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 369       | 53.32%  |
| Broadcom                        | 51        | 7.37%   |
| Realtek Semiconductor           | 45        | 6.5%    |
| Cambridge Silicon Radio         | 37        | 5.35%   |
| Qualcomm Atheros Communications | 33        | 4.77%   |
| Apple                           | 30        | 4.34%   |
| IMC Networks                    | 29        | 4.19%   |
| Foxconn / Hon Hai               | 22        | 3.18%   |
| Lite-On Technology              | 21        | 3.03%   |
| ASUSTek Computer                | 12        | 1.73%   |
| Hewlett-Packard                 | 10        | 1.45%   |
| MediaTek                        | 8         | 1.16%   |
| USI                             | 3         | 0.43%   |
| Marvell Semiconductor           | 3         | 0.43%   |
| Dell                            | 3         | 0.43%   |
| Realtek                         | 2         | 0.29%   |
| Ralink Technology               | 2         | 0.29%   |
| Ralink                          | 2         | 0.29%   |
| Belkin Components               | 2         | 0.29%   |
| Toshiba                         | 1         | 0.14%   |
| Taiyo Yuden                     | 1         | 0.14%   |
| Integrated System Solution      | 1         | 0.14%   |
| HTC (High Tech Computer)        | 1         | 0.14%   |
| Foxconn International           | 1         | 0.14%   |
| Edimax Technology               | 1         | 0.14%   |
| D-Link System                   | 1         | 0.14%   |
| Chicony Electronics             | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 162       | 23.41%  |
| Intel AX200 Bluetooth                               | 53        | 7.66%   |
| Intel Bluetooth Device                              | 50        | 7.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 42        | 6.07%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 37        | 5.35%   |
| Realtek Bluetooth Radio                             | 26        | 3.76%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 2.89%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 2.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 2.17%   |
| Apple Bluetooth Host Controller                     | 15        | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 1.88%   |
| Intel AX210 Bluetooth                               | 13        | 1.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 1.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 11        | 1.59%   |
| IMC Networks Wireless_Device                        | 10        | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 1.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 1.16%   |
| MediaTek Wireless_Device                            | 8         | 1.16%   |
| IMC Networks Bluetooth Radio                        | 8         | 1.16%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 7         | 1.01%   |
| Apple Bluetooth USB Host Controller                 | 7         | 1.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.87%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.87%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.87%   |
| ASUS Bluetooth Device                               | 6         | 0.87%   |
| IMC Networks 802.11ac WLAN Adapter                  | 5         | 0.72%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 5         | 0.72%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.58%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.58%   |
| Lite-On Bluetooth Device                            | 4         | 0.58%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.58%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.58%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.58%   |
| USI Bluetooth Device                                | 3         | 0.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.43%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 3         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 721       | 47.43%  |
| Nvidia                               | 298       | 19.61%  |
| AMD                                  | 295       | 19.41%  |
| C-Media Electronics                  | 19        | 1.25%   |
| SteelSeries ApS                      | 16        | 1.05%   |
| Lenovo                               | 16        | 1.05%   |
| Kingston Technology                  | 16        | 1.05%   |
| Logitech                             | 13        | 0.86%   |
| GN Netcom                            | 13        | 0.86%   |
| Creative Technology                  | 11        | 0.72%   |
| ASUSTek Computer                     | 10        | 0.66%   |
| Creative Labs                        | 9         | 0.59%   |
| XMOS                                 | 5         | 0.33%   |
| Hewlett-Packard                      | 5         | 0.33%   |
| RODE Microphones                     | 4         | 0.26%   |
| Realtek Semiconductor                | 4         | 0.26%   |
| Razer USA                            | 4         | 0.26%   |
| Corsair                              | 4         | 0.26%   |
| VIA Technologies                     | 3         | 0.2%    |
| Texas Instruments                    | 3         | 0.2%    |
| Plantronics                          | 3         | 0.2%    |
| JMTek                                | 3         | 0.2%    |
| Focusrite-Novation                   | 3         | 0.2%    |
| DSEA A/S                             | 3         | 0.2%    |
| Yamaha                               | 2         | 0.13%   |
| Sony                                 | 2         | 0.13%   |
| BEHRINGER International              | 2         | 0.13%   |
| Valve Software                       | 1         | 0.07%   |
| Turtle Beach                         | 1         | 0.07%   |
| Trust                                | 1         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.07%   |
| TerraTec Electronic                  | 1         | 0.07%   |
| Tenx Technology                      | 1         | 0.07%   |
| Syntek                               | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.07%   |
| Shure                                | 1         | 0.07%   |
| Setek Elektronik                     | 1         | 0.07%   |
| Samsung Electronics                  | 1         | 0.07%   |
| Samson Technologies                  | 1         | 0.07%   |
| ROCCAT                               | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 109       | 6.03%   |
| AMD Family 17h/19h HD Audio Controller                                     | 99        | 5.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 67        | 3.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 60        | 3.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 59        | 3.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 53        | 2.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 50        | 2.77%   |
| AMD Starship/Matisse HD Audio Controller                                   | 49        | 2.71%   |
| Intel 8 Series HD Audio Controller                                         | 40        | 2.21%   |
| Intel Haswell-ULT HD Audio Controller                                      | 39        | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 38        | 2.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 38        | 2.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 31        | 1.72%   |
| Intel 200 Series PCH HD Audio                                              | 27        | 1.49%   |
| AMD FCH Azalia Controller                                                  | 27        | 1.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 26        | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 25        | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 25        | 1.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 25        | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 23        | 1.27%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 22        | 1.22%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 21        | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                              | 20        | 1.11%   |
| Intel Broadwell-U Audio Controller                                         | 20        | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 19        | 1.05%   |
| Nvidia GP104 High Definition Audio Controller                              | 18        | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 18        | 1%      |
| AMD Navi 10 HDMI Audio                                                     | 18        | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 17        | 0.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 17        | 0.94%   |
| Nvidia GA104 High Definition Audio Controller                              | 16        | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 16        | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                   | 16        | 0.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 16        | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 15        | 0.83%   |
| Nvidia TU104 HD Audio Controller                                           | 15        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 15        | 0.83%   |
| Intel CM238 HD Audio Controller                                            | 14        | 0.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 0.72%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 13        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 134       | 23.18%  |
| SK hynix            | 101       | 17.47%  |
| Kingston            | 74        | 12.8%   |
| Micron Technology   | 63        | 10.9%   |
| Corsair             | 56        | 9.69%   |
| Unknown             | 43        | 7.44%   |
| G.Skill             | 35        | 6.06%   |
| Crucial             | 26        | 4.5%    |
| Elpida              | 11        | 1.9%    |
| Ramaxel Technology  | 9         | 1.56%   |
| Nanya Technology    | 6         | 1.04%   |
| A-DATA Technology   | 3         | 0.52%   |
| Unknown (ABCD)      | 2         | 0.35%   |
| ff                  | 2         | 0.35%   |
| 4ea5                | 2         | 0.35%   |
| Unknown             | 2         | 0.35%   |
| Unifosa             | 1         | 0.17%   |
| Transcend           | 1         | 0.17%   |
| SHARETRONIC         | 1         | 0.17%   |
| Patriot             | 1         | 0.17%   |
| Neo Forza           | 1         | 0.17%   |
| GOODRAM             | 1         | 0.17%   |
| fef5                | 1         | 0.17%   |
| Avant               | 1         | 0.17%   |
| Apacer              | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 9         | 1.48%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 9         | 1.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 8         | 1.32%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 7         | 1.15%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 6         | 0.99%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 0.99%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 6         | 0.99%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 4         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 4         | 0.66%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 4         | 0.66%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 4         | 0.66%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s       | 4         | 0.66%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 4         | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 4         | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 4         | 0.66%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 4         | 0.66%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s        | 4         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 3         | 0.49%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s   | 3         | 0.49%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 3         | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s     | 3         | 0.49%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 3         | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s     | 3         | 0.49%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 3         | 0.49%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s | 3         | 0.49%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 3         | 0.49%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 3         | 0.49%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 3         | 0.49%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s            | 3         | 0.49%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s       | 3         | 0.49%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 3         | 0.49%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s       | 3         | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 2         | 0.33%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                      | 2         | 0.33%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 2         | 0.33%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 2         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                  | 2         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 0.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 2         | 0.33%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                 | 2         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 264       | 51.97%  |
| DDR3    | 143       | 28.15%  |
| LPDDR3  | 23        | 4.53%   |
| LPDDR4  | 18        | 3.54%   |
| DDR5    | 17        | 3.35%   |
| DDR2    | 13        | 2.56%   |
| Unknown | 12        | 2.36%   |
| SDRAM   | 10        | 1.97%   |
| LPDDR5  | 4         | 0.79%   |
| DDR     | 3         | 0.59%   |
| DRAM    | 1         | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 283       | 55.6%   |
| DIMM         | 178       | 34.97%  |
| Row Of Chips | 36        | 7.07%   |
| Chip         | 6         | 1.18%   |
| Unknown      | 5         | 0.98%   |
| FB-DIMM      | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 232       | 43.04%  |
| 4096  | 116       | 21.52%  |
| 16384 | 105       | 19.48%  |
| 2048  | 50        | 9.28%   |
| 32768 | 23        | 4.27%   |
| 1024  | 10        | 1.86%   |
| 512   | 3         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 99        | 18.4%   |
| 3200    | 79        | 14.68%  |
| 2667    | 77        | 14.31%  |
| 2400    | 34        | 6.32%   |
| 2133    | 33        | 6.13%   |
| 1333    | 27        | 5.02%   |
| 3600    | 20        | 3.72%   |
| 1867    | 17        | 3.16%   |
| 1334    | 13        | 2.42%   |
| 667     | 12        | 2.23%   |
| 3400    | 9         | 1.67%   |
| 1067    | 9         | 1.67%   |
| 4267    | 8         | 1.49%   |
| Unknown | 7         | 1.3%    |
| 6400    | 6         | 1.12%   |
| 4800    | 6         | 1.12%   |
| 3000    | 5         | 0.93%   |
| 2933    | 5         | 0.93%   |
| 1800    | 5         | 0.93%   |
| 5600    | 4         | 0.74%   |
| 4266    | 4         | 0.74%   |
| 3800    | 4         | 0.74%   |
| 3733    | 4         | 0.74%   |
| 3666    | 4         | 0.74%   |
| 3533    | 4         | 0.74%   |
| 3266    | 4         | 0.74%   |
| 5200    | 3         | 0.56%   |
| 3866    | 3         | 0.56%   |
| 3534    | 3         | 0.56%   |
| 2666    | 3         | 0.56%   |
| 3500    | 2         | 0.37%   |
| 3466    | 2         | 0.37%   |
| 2800    | 2         | 0.37%   |
| 2048    | 2         | 0.37%   |
| 1639    | 2         | 0.37%   |
| 800     | 2         | 0.37%   |
| 20306   | 1         | 0.19%   |
| 8400    | 1         | 0.19%   |
| 6000    | 1         | 0.19%   |
| 4400    | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 45.45%  |
| Brother Industries  | 6         | 27.27%  |
| Canon               | 3         | 13.64%  |
| Xerox               | 1         | 4.55%   |
| Samsung Electronics | 1         | 4.55%   |
| Prolific Technology | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Brother DCP-J140W             | 2         | 9.09%   |
| Xerox Phaser 6125N            | 1         | 4.55%   |
| Samsung M2020 Series          | 1         | 4.55%   |
| Prolific PL2305 Parallel Port | 1         | 4.55%   |
| HP Officejet Pro 6230         | 1         | 4.55%   |
| HP LaserJet 1020              | 1         | 4.55%   |
| HP ENVY Photo 6200 series     | 1         | 4.55%   |
| HP ENVY 4520 series           | 1         | 4.55%   |
| HP Deskjet D4300 series       | 1         | 4.55%   |
| HP DeskJet 990c               | 1         | 4.55%   |
| HP DeskJet 5940               | 1         | 4.55%   |
| HP DeskJet 5550               | 1         | 4.55%   |
| HP DeskJet 3700 series        | 1         | 4.55%   |
| HP DeskJet 2600 series        | 1         | 4.55%   |
| Canon PIXMA MX370 Series      | 1         | 4.55%   |
| Canon PIXMA MP280             | 1         | 4.55%   |
| Canon iP7200 series           | 1         | 4.55%   |
| Brother HL-5250DN Printer     | 1         | 4.55%   |
| Brother HL-2240D series       | 1         | 4.55%   |
| Brother HL-2030 Laser Printer | 1         | 4.55%   |
| Brother HL-1210W series       | 1         | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 50%     |
| Seiko Epson     | 1         | 25%     |
| Canon           | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 25%     |
| HP ScanJet 5470c/5490c                           | 1         | 25%     |
| HP PSC 1200                                      | 1         | 25%     |
| Canon CanoScan LiDE 60                           | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 157       | 25.95%  |
| Bison Electronics                      | 59        | 9.75%   |
| IMC Networks                           | 57        | 9.42%   |
| Realtek Semiconductor                  | 41        | 6.78%   |
| Logitech                               | 38        | 6.28%   |
| Apple                                  | 26        | 4.3%    |
| Quanta                                 | 25        | 4.13%   |
| Microdia                               | 25        | 4.13%   |
| Syntek                                 | 24        | 3.97%   |
| Sunplus Innovation Technology          | 21        | 3.47%   |
| Lite-On Technology                     | 21        | 3.47%   |
| Suyin                                  | 19        | 3.14%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 2.98%   |
| Acer                                   | 14        | 2.31%   |
| Lenovo                                 | 8         | 1.32%   |
| Luxvisions Innotech Limited            | 7         | 1.16%   |
| Microsoft                              | 6         | 0.99%   |
| Silicon Motion                         | 5         | 0.83%   |
| Samsung Electronics                    | 5         | 0.83%   |
| Trust                                  | 3         | 0.5%    |
| Primax Electronics                     | 3         | 0.5%    |
| Creative Technology                    | 3         | 0.5%    |
| Sonix Technology                       | 2         | 0.33%   |
| GEMBIRD                                | 2         | 0.33%   |
| Alcor Micro                            | 2         | 0.33%   |
| Z-Star Microelectronics                | 1         | 0.17%   |
| Valve Software                         | 1         | 0.17%   |
| Tripath Technology                     | 1         | 0.17%   |
| Ricoh                                  | 1         | 0.17%   |
| Oculus VR                              | 1         | 0.17%   |
| MacroSilicon                           | 1         | 0.17%   |
| Jieli Technology                       | 1         | 0.17%   |
| Intel                                  | 1         | 0.17%   |
| Hewlett-Packard                        | 1         | 0.17%   |
| GenesysLogic Technology                | 1         | 0.17%   |
| Genesys Logic                          | 1         | 0.17%   |
| Foxconn / Hon Hai                      | 1         | 0.17%   |
| Cubeternet                             | 1         | 0.17%   |
| ALi                                    | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 50        | 8.21%   |
| IMC Networks Integrated Camera           | 22        | 3.61%   |
| Realtek Integrated_Webcam_HD             | 17        | 2.79%   |
| Chicony HD WebCam                        | 17        | 2.79%   |
| IMC Networks USB2.0 HD UVC WebCam        | 16        | 2.63%   |
| Lite-On Integrated Camera                | 13        | 2.13%   |
| Bison Integrated Camera                  | 13        | 2.13%   |
| Syntek Integrated Camera                 | 12        | 1.97%   |
| Microdia Integrated_Webcam_HD            | 12        | 1.97%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 10        | 1.64%   |
| Apple Built-in iSight                    | 10        | 1.64%   |
| Syntek Lenovo EasyCamera                 | 8         | 1.31%   |
| Bison SunplusIT Integrated Camera        | 8         | 1.31%   |
| Apple FaceTime HD Camera (Built-in)      | 8         | 1.31%   |
| Quanta HD User Facing                    | 6         | 0.99%   |
| Chicony USB 2.0 Camera                   | 6         | 0.99%   |
| Chicony HP HD Camera                     | 6         | 0.99%   |
| Bison ThinkPad P50 Integrated Camera     | 6         | 0.99%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 5         | 0.82%   |
| Samsung Galaxy series, misc. (MTP mode)  | 5         | 0.82%   |
| Luxvisions Innotech Limited HP HD Camera | 5         | 0.82%   |
| Logitech StreamCam                       | 5         | 0.82%   |
| Logitech HD Pro Webcam C920              | 5         | 0.82%   |
| Chicony Integrated Camera (1280x720@30)  | 5         | 0.82%   |
| Chicony HP Truevision HD                 | 5         | 0.82%   |
| Chicony EasyCamera                       | 5         | 0.82%   |
| Bison SunplusIT INC. Integrated Camera   | 5         | 0.82%   |
| Bison Lenovo EasyCamera                  | 5         | 0.82%   |
| Apple iPhone 5/5C/5S/6/SE                | 5         | 0.82%   |
| Realtek Integrated Webcam HD             | 4         | 0.66%   |
| Quanta USB2.0 HD UVC WebCam              | 4         | 0.66%   |
| Quanta HP Webcam                         | 4         | 0.66%   |
| Quanta HD Webcam                         | 4         | 0.66%   |
| Microdia Integrated Webcam               | 4         | 0.66%   |
| Logitech Webcam C270                     | 4         | 0.66%   |
| Lenovo Integrated Webcam                 | 4         | 0.66%   |
| Chicony Lenovo EasyCamera                | 4         | 0.66%   |
| Chicony Integrated Camera [ThinkPad]     | 4         | 0.66%   |
| Bison ThinkPad Integrated Camera         | 4         | 0.66%   |
| Bison HD Webcam                          | 4         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 61        | 35.06%  |
| Validity Sensors           | 60        | 34.48%  |
| Upek                       | 17        | 9.77%   |
| Shenzhen Goodix Technology | 14        | 8.05%   |
| AuthenTec                  | 11        | 6.32%   |
| Elan Microelectronics      | 6         | 3.45%   |
| STMicroelectronics         | 3         | 1.72%   |
| LighTuning Technology      | 2         | 1.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 29        | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 10.92%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 9.77%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 6.32%   |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 5.17%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 3.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 2.87%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.87%   |
| Synaptics UWP WBDI Device                                                  | 5         | 2.87%   |
| Synaptics  WBDI                                                            | 5         | 2.87%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 2.87%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 2.3%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 2.3%    |
| Elan ELAN:ARM-M4                                                           | 4         | 2.3%    |
| AuthenTec AES2810                                                          | 4         | 2.3%    |
| Synaptics WBDI                                                             | 3         | 1.72%   |
| Synaptics UWP WBDI                                                         | 3         | 1.72%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.72%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 1.72%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 1.72%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.72%   |
| Validity Sensors VFS491                                                    | 2         | 1.15%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.15%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.15%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.15%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.15%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.15%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.15%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.57%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.57%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.57%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.57%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.57%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.57%   |
| Synaptics TouchPad                                                         | 1         | 0.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.57%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.57%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 50        | 61.73%  |
| Broadcom              | 21        | 25.93%  |
| Upek                  | 6         | 7.41%   |
| Lenovo                | 3         | 3.7%    |
| Advanced Card Systems | 1         | 1.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 50        | 61.73%  |
| Broadcom 5880                                                                | 10        | 12.35%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 7.41%   |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 7.41%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 3.7%    |
| Broadcom 58200                                                               | 2         | 2.47%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 1.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 675       | 64.22%  |
| 1     | 276       | 26.26%  |
| 2     | 79        | 7.52%   |
| 3     | 12        | 1.14%   |
| 4     | 5         | 0.48%   |
| 6     | 3         | 0.29%   |
| 10    | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 172       | 35.46%  |
| Graphics card            | 86        | 17.73%  |
| Chipcard                 | 73        | 15.05%  |
| Net/wireless             | 45        | 9.28%   |
| Multimedia controller    | 32        | 6.6%    |
| Communication controller | 14        | 2.89%   |
| Card reader              | 12        | 2.47%   |
| Camera                   | 11        | 2.27%   |
| Sound                    | 10        | 2.06%   |
| Bluetooth                | 8         | 1.65%   |
| Unassigned class         | 6         | 1.24%   |
| Net/ethernet             | 6         | 1.24%   |
| Storage                  | 5         | 1.03%   |
| Storage/raid             | 2         | 0.41%   |
| Wireless                 | 1         | 0.21%   |
| Network                  | 1         | 0.21%   |
| Modem                    | 1         | 0.21%   |

