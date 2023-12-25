Linux in Denmark - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Denmark.

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

Total: 856

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite P850              | [e16f04d074](https://linux-hardware.org/?probe=e16f04d074) | Dec 23, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [987ab63f96](https://linux-hardware.org/?probe=987ab63f96) | Dec 17, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [2167a2f148](https://linux-hardware.org/?probe=2167a2f148) | Dec 16, 2023 |
| Acer          | Nitro AN715-51              | [279ade4fb0](https://linux-hardware.org/?probe=279ade4fb0) | Dec 16, 2023 |
| Medion        | P7624                       | [4828985ec0](https://linux-hardware.org/?probe=4828985ec0) | Dec 15, 2023 |
| Medion        | P7624                       | [050fbbd613](https://linux-hardware.org/?probe=050fbbd613) | Dec 15, 2023 |
| Apple         | MacBookPro13,2              | [9200b90a95](https://linux-hardware.org/?probe=9200b90a95) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | [917471b136](https://linux-hardware.org/?probe=917471b136) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | [6c3498a025](https://linux-hardware.org/?probe=6c3498a025) | Dec 12, 2023 |
| Dell          | Latitude E6540              | [0d56fcda0e](https://linux-hardware.org/?probe=0d56fcda0e) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [332492b0c4](https://linux-hardware.org/?probe=332492b0c4) | Dec 11, 2023 |
| Unknown       | TK23D                       | [27c0f3c1f6](https://linux-hardware.org/?probe=27c0f3c1f6) | Dec 07, 2023 |
| Lenovo        | V110-15IAP 80TG             | [ff40966f37](https://linux-hardware.org/?probe=ff40966f37) | Dec 04, 2023 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | [151a3ceaf0](https://linux-hardware.org/?probe=151a3ceaf0) | Dec 03, 2023 |
| Acer          | Aspire V5-573               | [8a76c8baac](https://linux-hardware.org/?probe=8a76c8baac) | Nov 30, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BE09    | [33b3b8ed10](https://linux-hardware.org/?probe=33b3b8ed10) | Nov 29, 2023 |
| Apple         | MacBookPro8,1               | [b305057bc5](https://linux-hardware.org/?probe=b305057bc5) | Nov 27, 2023 |
| Acer          | Aspire 7741                 | [d1e2c905e1](https://linux-hardware.org/?probe=d1e2c905e1) | Nov 25, 2023 |
| Dell          | Studio XPS 1640             | [3b9a32eb3f](https://linux-hardware.org/?probe=3b9a32eb3f) | Nov 24, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [3b995f6b47](https://linux-hardware.org/?probe=3b995f6b47) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [37a1e3b979](https://linux-hardware.org/?probe=37a1e3b979) | Nov 23, 2023 |
| Gigabyte      | B650M DS3H                  | [dfcb329b5a](https://linux-hardware.org/?probe=dfcb329b5a) | Nov 23, 2023 |
| Sony          | SVE14A2M6EW                 | [9f444d1508](https://linux-hardware.org/?probe=9f444d1508) | Nov 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [049356e4bc](https://linux-hardware.org/?probe=049356e4bc) | Nov 15, 2023 |
| HP            | EliteBook 840 G2            | [64cfcced5b](https://linux-hardware.org/?probe=64cfcced5b) | Nov 14, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | [f5f9243038](https://linux-hardware.org/?probe=f5f9243038) | Nov 11, 2023 |
| HP            | Pavilion g7                 | [f963761c30](https://linux-hardware.org/?probe=f963761c30) | Nov 10, 2023 |
| Dell          | Precision M4600             | [0aabbcfa0b](https://linux-hardware.org/?probe=0aabbcfa0b) | Nov 06, 2023 |
| Acer          | Aspire A315-58              | [95f3002643](https://linux-hardware.org/?probe=95f3002643) | Nov 05, 2023 |
| Lenovo        | ThinkPad W550s 20E2000PM... | [1294d54c1a](https://linux-hardware.org/?probe=1294d54c1a) | Nov 04, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | [1d51aba71e](https://linux-hardware.org/?probe=1d51aba71e) | Nov 04, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | [585906fa27](https://linux-hardware.org/?probe=585906fa27) | Nov 04, 2023 |
| Dell          | Precision 5750              | [00e8468779](https://linux-hardware.org/?probe=00e8468779) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [00a8b74f46](https://linux-hardware.org/?probe=00a8b74f46) | Nov 03, 2023 |
| Acer          | Aspire A515-45              | [b367027f2a](https://linux-hardware.org/?probe=b367027f2a) | Oct 30, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | [e8252549f4](https://linux-hardware.org/?probe=e8252549f4) | Oct 29, 2023 |
| ASUSTek       | X555LN                      | [783a3b6555](https://linux-hardware.org/?probe=783a3b6555) | Oct 24, 2023 |
| HP            | Laptop 15s-eq1xxx           | [5795100325](https://linux-hardware.org/?probe=5795100325) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a2756e1d2b](https://linux-hardware.org/?probe=a2756e1d2b) | Oct 21, 2023 |
| Lenovo        | IdeaPad Y500 9541           | [999de2ca37](https://linux-hardware.org/?probe=999de2ca37) | Oct 16, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [1215db6b88](https://linux-hardware.org/?probe=1215db6b88) | Oct 13, 2023 |
| ASUSTek       | Strix 15 GL503GE            | [95ef83d6fd](https://linux-hardware.org/?probe=95ef83d6fd) | Oct 08, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [69383bf7da](https://linux-hardware.org/?probe=69383bf7da) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [81ece14527](https://linux-hardware.org/?probe=81ece14527) | Oct 08, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [c9d4efa819](https://linux-hardware.org/?probe=c9d4efa819) | Oct 07, 2023 |
| Apple         | MacBookPro12,1              | [50fc69b25f](https://linux-hardware.org/?probe=50fc69b25f) | Oct 06, 2023 |
| Valve         | Jupiter                     | [1323f200dd](https://linux-hardware.org/?probe=1323f200dd) | Oct 01, 2023 |
| Dell          | XPS 13 9380                 | [9c2ba935b9](https://linux-hardware.org/?probe=9c2ba935b9) | Sep 29, 2023 |
| Google        | Lindar                      | [f8f947a025](https://linux-hardware.org/?probe=f8f947a025) | Sep 28, 2023 |
| Google        | Lindar                      | [9ddbc21f0d](https://linux-hardware.org/?probe=9ddbc21f0d) | Sep 28, 2023 |
| Dell          | Latitude 5480               | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| Google        | Droid                       | [fa5f650f3a](https://linux-hardware.org/?probe=fa5f650f3a) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0YE0... | [20c9a90aca](https://linux-hardware.org/?probe=20c9a90aca) | Sep 24, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [726a5f4cf5](https://linux-hardware.org/?probe=726a5f4cf5) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [72c4bdf239](https://linux-hardware.org/?probe=72c4bdf239) | Sep 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [fd9d93d90d](https://linux-hardware.org/?probe=fd9d93d90d) | Sep 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [72fe934225](https://linux-hardware.org/?probe=72fe934225) | Sep 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0918609cf3](https://linux-hardware.org/?probe=0918609cf3) | Sep 13, 2023 |
| Valve         | Jupiter                     | [f6467570d4](https://linux-hardware.org/?probe=f6467570d4) | Sep 11, 2023 |
| ASUSTek       | S550CB                      | [dbf2770e09](https://linux-hardware.org/?probe=dbf2770e09) | Sep 10, 2023 |
| ASUSTek       | Strix GL504GM_GL504GM       | [3297d8f0aa](https://linux-hardware.org/?probe=3297d8f0aa) | Sep 10, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HH0... | [94c99c8274](https://linux-hardware.org/?probe=94c99c8274) | Sep 06, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| ASUSTek       | N73SV                       | [1e0b979775](https://linux-hardware.org/?probe=1e0b979775) | Sep 04, 2023 |
| HP            | Pavilion dv9500             | [653fbbb509](https://linux-hardware.org/?probe=653fbbb509) | Sep 04, 2023 |
| HP            | ProBook 650 G2              | [64026d5e6d](https://linux-hardware.org/?probe=64026d5e6d) | Sep 04, 2023 |
| Dell          | XPS 15 7590                 | [b423b914f7](https://linux-hardware.org/?probe=b423b914f7) | Aug 30, 2023 |
| Acer          | Aspire A315-58              | [75ef08524c](https://linux-hardware.org/?probe=75ef08524c) | Aug 30, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [3f7455be45](https://linux-hardware.org/?probe=3f7455be45) | Aug 27, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| Lenovo        | ThinkPad T460s 20F9003VM... | [e6e076d380](https://linux-hardware.org/?probe=e6e076d380) | Aug 23, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [d68939adcf](https://linux-hardware.org/?probe=d68939adcf) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| HP            | Pavilion dv9500             | [d5cc7639c3](https://linux-hardware.org/?probe=d5cc7639c3) | Aug 21, 2023 |
| Dell          | Latitude E6410              | [5ae66b0d4a](https://linux-hardware.org/?probe=5ae66b0d4a) | Aug 18, 2023 |
| Dell          | Latitude 5540               | [d1f00897b3](https://linux-hardware.org/?probe=d1f00897b3) | Aug 18, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | [0c47627604](https://linux-hardware.org/?probe=0c47627604) | Aug 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [2cd51b6fce](https://linux-hardware.org/?probe=2cd51b6fce) | Aug 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b326fccb63](https://linux-hardware.org/?probe=b326fccb63) | Aug 16, 2023 |
| Valve         | Jupiter                     | [508611b16c](https://linux-hardware.org/?probe=508611b16c) | Aug 16, 2023 |
| Apple         | MacBookPro12,1              | [12e0dbd72c](https://linux-hardware.org/?probe=12e0dbd72c) | Aug 09, 2023 |
| Acer          | Swift SF114-32              | [3474fa639e](https://linux-hardware.org/?probe=3474fa639e) | Aug 08, 2023 |
| Dell          | G3 3590                     | [56d5cdc390](https://linux-hardware.org/?probe=56d5cdc390) | Aug 04, 2023 |
| Sony          | SVF1521G1EW                 | [b46b664a9e](https://linux-hardware.org/?probe=b46b664a9e) | Aug 03, 2023 |
| ASUSTek       | K95VM                       | [1ec08c4cf9](https://linux-hardware.org/?probe=1ec08c4cf9) | Jul 30, 2023 |
| MSI           | Raider GE78HX 13VI          | [0b179ca997](https://linux-hardware.org/?probe=0b179ca997) | Jul 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS22905    | [f95fe4ced5](https://linux-hardware.org/?probe=f95fe4ced5) | Jul 28, 2023 |
| Dell          | XPS 13 9370                 | [8cf3728f9b](https://linux-hardware.org/?probe=8cf3728f9b) | Jul 25, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| Acer          | Aspire E5-553               | [1321d9a034](https://linux-hardware.org/?probe=1321d9a034) | Jul 21, 2023 |
| Acer          | Aspire E5-553               | [7ef01e963d](https://linux-hardware.org/?probe=7ef01e963d) | Jul 21, 2023 |
| Dell          | Precision 7530              | [0d2e753768](https://linux-hardware.org/?probe=0d2e753768) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [26a2238069](https://linux-hardware.org/?probe=26a2238069) | Jul 19, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [9672a393c9](https://linux-hardware.org/?probe=9672a393c9) | Jul 19, 2023 |
| Dell          | XPS 13 9370                 | [ea47e53a45](https://linux-hardware.org/?probe=ea47e53a45) | Jul 18, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [14defb538e](https://linux-hardware.org/?probe=14defb538e) | Jul 17, 2023 |
| Acer          | Aspire A315-43              | [f440759b5b](https://linux-hardware.org/?probe=f440759b5b) | Jul 17, 2023 |
| Acer          | Aspire A315-43              | [2e7199aa1a](https://linux-hardware.org/?probe=2e7199aa1a) | Jul 17, 2023 |
| Acer          | Aspire A315-43              | [9a14a53c9c](https://linux-hardware.org/?probe=9a14a53c9c) | Jul 16, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [0c4b8e49f8](https://linux-hardware.org/?probe=0c4b8e49f8) | Jul 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [72af2d01c0](https://linux-hardware.org/?probe=72af2d01c0) | Jul 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [e87ea192ea](https://linux-hardware.org/?probe=e87ea192ea) | Jul 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [4e47f48ca8](https://linux-hardware.org/?probe=4e47f48ca8) | Jul 07, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [382fff8a04](https://linux-hardware.org/?probe=382fff8a04) | Jul 06, 2023 |
| Dell          | XPS 15 7590                 | [81a034858f](https://linux-hardware.org/?probe=81a034858f) | Jul 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c9cbb8f947](https://linux-hardware.org/?probe=c9cbb8f947) | Jun 27, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [46e3ea33a3](https://linux-hardware.org/?probe=46e3ea33a3) | Jun 27, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| HP            | OMEN by Laptop              | [07d9cc6d71](https://linux-hardware.org/?probe=07d9cc6d71) | Jun 26, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [5298e132fc](https://linux-hardware.org/?probe=5298e132fc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L480 20LS002YMX    | [9c9702483c](https://linux-hardware.org/?probe=9c9702483c) | Jun 22, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [5314aeb7e0](https://linux-hardware.org/?probe=5314aeb7e0) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [fc06bc7209](https://linux-hardware.org/?probe=fc06bc7209) | Jun 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [5bd2521f5c](https://linux-hardware.org/?probe=5bd2521f5c) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| Dell          | Inspiron 15-7568            | [4d0efefd7c](https://linux-hardware.org/?probe=4d0efefd7c) | Jun 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [2aaa4324d0](https://linux-hardware.org/?probe=2aaa4324d0) | Jun 12, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| Acer          | Aspire E5-553               | [76ca69b8cc](https://linux-hardware.org/?probe=76ca69b8cc) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | [3932ac5190](https://linux-hardware.org/?probe=3932ac5190) | Jun 07, 2023 |
| Razer         | Blade 15 Advanced Model ... | [8f55e469c8](https://linux-hardware.org/?probe=8f55e469c8) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [525601c31e](https://linux-hardware.org/?probe=525601c31e) | Jun 04, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | 1225B                       | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [742ae62ba6](https://linux-hardware.org/?probe=742ae62ba6) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [c507b25480](https://linux-hardware.org/?probe=c507b25480) | May 30, 2023 |
| Dell          | Inspiron 15-7568            | [227930e25d](https://linux-hardware.org/?probe=227930e25d) | May 29, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | [4147fc8cb7](https://linux-hardware.org/?probe=4147fc8cb7) | May 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | [d9295f37bc](https://linux-hardware.org/?probe=d9295f37bc) | May 27, 2023 |
| Acer          | Aspire E5-553               | [3740264eb0](https://linux-hardware.org/?probe=3740264eb0) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [97687a73c3](https://linux-hardware.org/?probe=97687a73c3) | May 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0037MD     | [f1a58d3a7f](https://linux-hardware.org/?probe=f1a58d3a7f) | May 11, 2023 |
| Acer          | Aspire 5810T                | [d21ea25d7a](https://linux-hardware.org/?probe=d21ea25d7a) | May 10, 2023 |
| Lenovo        | ThinkPad T550 20CJS0AP00    | [f628b12917](https://linux-hardware.org/?probe=f628b12917) | May 10, 2023 |
| Acer          | Aspire 5810T                | [d4b401ef3f](https://linux-hardware.org/?probe=d4b401ef3f) | May 06, 2023 |
| HP            | ProBook 6570b               | [d240b443c4](https://linux-hardware.org/?probe=d240b443c4) | May 06, 2023 |
| Acer          | Aspire 5810T                | [ecdd99c704](https://linux-hardware.org/?probe=ecdd99c704) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6cb7429ec6](https://linux-hardware.org/?probe=6cb7429ec6) | May 02, 2023 |
| Acer          | Aspire E5-553               | [ff448e32c3](https://linux-hardware.org/?probe=ff448e32c3) | Apr 29, 2023 |
| HUAWEI        | BOD-WXX9                    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| Lenovo        | ThinkPad X250 20CLA003TA    | [ea8109c2a7](https://linux-hardware.org/?probe=ea8109c2a7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| Lenovo        | ThinkPad T520 4243W4L       | [bcdd9e5f74](https://linux-hardware.org/?probe=bcdd9e5f74) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [0ec2388253](https://linux-hardware.org/?probe=0ec2388253) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [a196246f09](https://linux-hardware.org/?probe=a196246f09) | Apr 17, 2023 |
| Lenovo        | ThinkPad W541 20EGS03800    | [4be9d98954](https://linux-hardware.org/?probe=4be9d98954) | Apr 11, 2023 |
| eMachines     | E725                        | [758d0c86b2](https://linux-hardware.org/?probe=758d0c86b2) | Apr 06, 2023 |
| Acer          | Aspire E5-771               | [2ef87c5f77](https://linux-hardware.org/?probe=2ef87c5f77) | Apr 06, 2023 |
| Acer          | Swift SF314-59              | [d12cbc4044](https://linux-hardware.org/?probe=d12cbc4044) | Apr 06, 2023 |
| HUAWEI        | BOD-WXX9                    | [3f9238067d](https://linux-hardware.org/?probe=3f9238067d) | Apr 04, 2023 |
| Dell          | Latitude 7480               | [f1ca485181](https://linux-hardware.org/?probe=f1ca485181) | Apr 02, 2023 |
| Lenovo        | G505 20240                  | [d873632b2b](https://linux-hardware.org/?probe=d873632b2b) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420 4236W1K       | [e093aace6e](https://linux-hardware.org/?probe=e093aace6e) | Mar 27, 2023 |
| Lenovo        | ThinkPad L530 24812SG       | [163d4e376e](https://linux-hardware.org/?probe=163d4e376e) | Mar 26, 2023 |
| MSI           | GT72 2QE                    | [438f4cb9d9](https://linux-hardware.org/?probe=438f4cb9d9) | Mar 26, 2023 |
| Acer          | Aspire E5-553               | [3d591cd190](https://linux-hardware.org/?probe=3d591cd190) | Mar 21, 2023 |
| Acer          | Extensa 7620                | [59bb9967c2](https://linux-hardware.org/?probe=59bb9967c2) | Mar 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [ccfa4fb30e](https://linux-hardware.org/?probe=ccfa4fb30e) | Mar 17, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | [4012d2fb1f](https://linux-hardware.org/?probe=4012d2fb1f) | Mar 16, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | [f2f8796262](https://linux-hardware.org/?probe=f2f8796262) | Mar 16, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0AF00    | [fe02ac3290](https://linux-hardware.org/?probe=fe02ac3290) | Mar 15, 2023 |
| Samsung       | NP770                       | [ab2677e28e](https://linux-hardware.org/?probe=ab2677e28e) | Mar 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [e5f5d4a3d5](https://linux-hardware.org/?probe=e5f5d4a3d5) | Mar 11, 2023 |
| HP            | OMEN by Laptop              | [a3a369de93](https://linux-hardware.org/?probe=a3a369de93) | Mar 08, 2023 |
| Apple         | MacBookPro9,2               | [8995f4a3b0](https://linux-hardware.org/?probe=8995f4a3b0) | Mar 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | [38623506fd](https://linux-hardware.org/?probe=38623506fd) | Mar 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [05e7af9004](https://linux-hardware.org/?probe=05e7af9004) | Mar 02, 2023 |
| HP            | Pavilion dv7                | [3d8c3db030](https://linux-hardware.org/?probe=3d8c3db030) | Feb 26, 2023 |
| HP            | EliteBook 840 G6            | [ea6777bf2d](https://linux-hardware.org/?probe=ea6777bf2d) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [7380033a44](https://linux-hardware.org/?probe=7380033a44) | Feb 22, 2023 |
| HP            | Pavilion dv7                | [5fd9a2f9c5](https://linux-hardware.org/?probe=5fd9a2f9c5) | Feb 17, 2023 |
| HP            | Notebook                    | [682935bcda](https://linux-hardware.org/?probe=682935bcda) | Feb 16, 2023 |
| HP            | Notebook                    | [1ea98ae976](https://linux-hardware.org/?probe=1ea98ae976) | Feb 16, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [aa3655a17e](https://linux-hardware.org/?probe=aa3655a17e) | Feb 15, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [36f57d56f8](https://linux-hardware.org/?probe=36f57d56f8) | Feb 15, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [92cbb2e876](https://linux-hardware.org/?probe=92cbb2e876) | Feb 11, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a55211363f](https://linux-hardware.org/?probe=a55211363f) | Feb 09, 2023 |
| HP            | Notebook                    | [eb0699bb89](https://linux-hardware.org/?probe=eb0699bb89) | Feb 07, 2023 |
| HP            | Pavilion g7                 | [e64e08ebd4](https://linux-hardware.org/?probe=e64e08ebd4) | Feb 05, 2023 |
| Lenovo        | ThinkPad L380 20M5S09Y00    | [5a7e90c12d](https://linux-hardware.org/?probe=5a7e90c12d) | Feb 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ab57658c86](https://linux-hardware.org/?probe=ab57658c86) | Jan 31, 2023 |
| Lenovo        | ThinkPad L380 20M5S09Y00    | [2326ffc032](https://linux-hardware.org/?probe=2326ffc032) | Jan 31, 2023 |
| HP            | Laptop 14-bp0xx             | [68d8a60823](https://linux-hardware.org/?probe=68d8a60823) | Jan 27, 2023 |
| Standard      | Unknown                     | [d9a5e68741](https://linux-hardware.org/?probe=d9a5e68741) | Jan 25, 2023 |
| HP            | ProBook 650 G1              | [f9882955cb](https://linux-hardware.org/?probe=f9882955cb) | Jan 24, 2023 |
| Lenovo        | ThinkPad W541 20EF0020MD    | [fca73ad2a9](https://linux-hardware.org/?probe=fca73ad2a9) | Jan 24, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [96a5ca6b92](https://linux-hardware.org/?probe=96a5ca6b92) | Jan 23, 2023 |
| System76      | Darter UltraThin            | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Google        | Phaser                      | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| Lenovo        | ThinkPad X230 2325AS7       | [71a521018d](https://linux-hardware.org/?probe=71a521018d) | Jan 19, 2023 |
| ASUSTek       | S301LA                      | [c45b4758ed](https://linux-hardware.org/?probe=c45b4758ed) | Jan 18, 2023 |
| Lenovo        | G505 20240                  | [ef2fdd351c](https://linux-hardware.org/?probe=ef2fdd351c) | Jan 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [138f888e23](https://linux-hardware.org/?probe=138f888e23) | Jan 15, 2023 |
| Acer          | Aspire 5810T                | [a39184ad9b](https://linux-hardware.org/?probe=a39184ad9b) | Jan 13, 2023 |
| Acer          | Aspire 5810T                | [ccc420a65a](https://linux-hardware.org/?probe=ccc420a65a) | Jan 13, 2023 |
| Acer          | Aspire A515-56              | [2f95543d62](https://linux-hardware.org/?probe=2f95543d62) | Jan 11, 2023 |
| Acer          | Aspire E5-553               | [e68c76cbee](https://linux-hardware.org/?probe=e68c76cbee) | Jan 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | [26826e3c23](https://linux-hardware.org/?probe=26826e3c23) | Jan 04, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [bc17e3a0f4](https://linux-hardware.org/?probe=bc17e3a0f4) | Jan 04, 2023 |
| Medion        | P7621                       | [6ce2ef1abc](https://linux-hardware.org/?probe=6ce2ef1abc) | Jan 03, 2023 |
| HP            | EliteBook 845 14 inch G9... | [65c34944ec](https://linux-hardware.org/?probe=65c34944ec) | Jan 03, 2023 |
| Notebook      | P17SM                       | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Apple         | MacBookPro10,2              | [a01c19a34d](https://linux-hardware.org/?probe=a01c19a34d) | Dec 29, 2022 |
| GPD           | WIN2                        | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| ASUSTek       | X75A1                       | [5a5ee8db71](https://linux-hardware.org/?probe=5a5ee8db71) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [196d570869](https://linux-hardware.org/?probe=196d570869) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| Valve         | Jupiter                     | [5c07d82410](https://linux-hardware.org/?probe=5c07d82410) | Dec 23, 2022 |
| MSI           | GP65 Leopard 9SE            | [7b980fbd8f](https://linux-hardware.org/?probe=7b980fbd8f) | Dec 21, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [97d8552a67](https://linux-hardware.org/?probe=97d8552a67) | Dec 21, 2022 |
| Medion        | P7621                       | [eced009b2a](https://linux-hardware.org/?probe=eced009b2a) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [95aca2679a](https://linux-hardware.org/?probe=95aca2679a) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [be36edb132](https://linux-hardware.org/?probe=be36edb132) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [491b8d0b8f](https://linux-hardware.org/?probe=491b8d0b8f) | Dec 11, 2022 |
| Lenovo        | ThinkPad Z61m 94503HG       | [4131ed9268](https://linux-hardware.org/?probe=4131ed9268) | Dec 11, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [4686ea3469](https://linux-hardware.org/?probe=4686ea3469) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Dell          | XPS 13 9370                 | [e5291ae74e](https://linux-hardware.org/?probe=e5291ae74e) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7a802a74b7](https://linux-hardware.org/?probe=7a802a74b7) | Dec 04, 2022 |
| Acer          | Aspire E5-575G              | [dddc2b5f29](https://linux-hardware.org/?probe=dddc2b5f29) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| Standard      | Unknown                     | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [687d4d78a4](https://linux-hardware.org/?probe=687d4d78a4) | Nov 29, 2022 |
| Dell          | Inspiron 15 3520            | [7c53fcc73b](https://linux-hardware.org/?probe=7c53fcc73b) | Nov 24, 2022 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [dee6d2a740](https://linux-hardware.org/?probe=dee6d2a740) | Nov 23, 2022 |
| Lenovo        | ThinkPad T460 20FN004CMD    | [1b7140151d](https://linux-hardware.org/?probe=1b7140151d) | Nov 20, 2022 |
| Acer          | Aspire 5810T                | [2c671f2494](https://linux-hardware.org/?probe=2c671f2494) | Nov 18, 2022 |
| Timi          | TM1607                      | [a93d1611bb](https://linux-hardware.org/?probe=a93d1611bb) | Nov 18, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [7352c1f1ed](https://linux-hardware.org/?probe=7352c1f1ed) | Nov 17, 2022 |
| HP            | Pavilion 15                 | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6af7c2ad85](https://linux-hardware.org/?probe=6af7c2ad85) | Nov 15, 2022 |
| Acer          | Aspire E5-553               | [4c031f5f3b](https://linux-hardware.org/?probe=4c031f5f3b) | Nov 15, 2022 |
| Apple         | MacBookPro5,5               | [a35952fc68](https://linux-hardware.org/?probe=a35952fc68) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [270045ffa3](https://linux-hardware.org/?probe=270045ffa3) | Nov 11, 2022 |
| Komplett      | LAPQC71B                    | [b5ee8960c6](https://linux-hardware.org/?probe=b5ee8960c6) | Nov 11, 2022 |
| MSI           | GV62 8RC                    | [859227b2bb](https://linux-hardware.org/?probe=859227b2bb) | Nov 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [a62bf9ed3b](https://linux-hardware.org/?probe=a62bf9ed3b) | Nov 08, 2022 |
| HP            | Notebook                    | [0868a7d110](https://linux-hardware.org/?probe=0868a7d110) | Nov 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS3CF0... | [2c52a84e7c](https://linux-hardware.org/?probe=2c52a84e7c) | Nov 06, 2022 |
| ASUSTek       | N55SF                       | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | Latitude 5280               | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Unknown       | Unknown                     | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [e21d202e50](https://linux-hardware.org/?probe=e21d202e50) | Oct 22, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| Acer          | Aspire E5-551               | [9d281c015c](https://linux-hardware.org/?probe=9d281c015c) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | [6c351b94ff](https://linux-hardware.org/?probe=6c351b94ff) | Oct 11, 2022 |
| Dell          | XPS 13 9370                 | [17f73f4f28](https://linux-hardware.org/?probe=17f73f4f28) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| Lenovo        | Z50-75 80EC                 | [e3f9c7a4f1](https://linux-hardware.org/?probe=e3f9c7a4f1) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| Unknown       | Unknown                     | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | XPS 15 9570                 | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | [87c9436154](https://linux-hardware.org/?probe=87c9436154) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d3047f6963](https://linux-hardware.org/?probe=d3047f6963) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | [6ea648bc51](https://linux-hardware.org/?probe=6ea648bc51) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [0be5b29760](https://linux-hardware.org/?probe=0be5b29760) | Sep 21, 2022 |
| Acer          | Aspire E5-553               | [5db637f345](https://linux-hardware.org/?probe=5db637f345) | Sep 19, 2022 |
| Acer          | Aspire E5-553               | [f0bbe89fe8](https://linux-hardware.org/?probe=f0bbe89fe8) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Dell          | XPS 13 9360                 | [af2f12093c](https://linux-hardware.org/?probe=af2f12093c) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| Valve         | Jupiter                     | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [865455aae7](https://linux-hardware.org/?probe=865455aae7) | Sep 05, 2022 |
| Acer          | Aspire E5-553               | [de2cfb43d7](https://linux-hardware.org/?probe=de2cfb43d7) | Sep 03, 2022 |
| Apple         | MacBookPro9,2               | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| HP            | ProBook 6550b               | [662065bfe2](https://linux-hardware.org/?probe=662065bfe2) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Lenovo        | B50-50 80S2                 | [45f5a72c59](https://linux-hardware.org/?probe=45f5a72c59) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | [115ca42bb8](https://linux-hardware.org/?probe=115ca42bb8) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | [0ab380f8ac](https://linux-hardware.org/?probe=0ab380f8ac) | Aug 23, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Dell          | XPS 13 9370                 | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [1d97fa15fb](https://linux-hardware.org/?probe=1d97fa15fb) | Aug 08, 2022 |
| Acer          | Aspire M3-581TG             | [5c73e4c75b](https://linux-hardware.org/?probe=5c73e4c75b) | Aug 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [41189cd175](https://linux-hardware.org/?probe=41189cd175) | Aug 03, 2022 |
| Notebook      | NS50_70MU                   | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [e6ccfdf23c](https://linux-hardware.org/?probe=e6ccfdf23c) | Jul 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [83e5824a05](https://linux-hardware.org/?probe=83e5824a05) | Jul 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [03839f9fef](https://linux-hardware.org/?probe=03839f9fef) | Jul 17, 2022 |
| HP            | Laptop 15-gw0xxx            | [a7f15d1696](https://linux-hardware.org/?probe=a7f15d1696) | Jul 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [4d9388058d](https://linux-hardware.org/?probe=4d9388058d) | Jul 12, 2022 |
| Acer          | Aspire E5-553               | [e7cdc97a90](https://linux-hardware.org/?probe=e7cdc97a90) | Jul 11, 2022 |
| Dell          | Latitude 7490               | [b456bca385](https://linux-hardware.org/?probe=b456bca385) | Jul 06, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [0e23c1fc2b](https://linux-hardware.org/?probe=0e23c1fc2b) | Jul 02, 2022 |
| Lenovo        | ThinkPad T530 24295L4       | [1bdf25550e](https://linux-hardware.org/?probe=1bdf25550e) | Jun 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6dfa236f76](https://linux-hardware.org/?probe=6dfa236f76) | Jun 18, 2022 |
| Notebook      | PB50_70DFx,DDx              | [21206dd6bf](https://linux-hardware.org/?probe=21206dd6bf) | Jun 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [527587d2b9](https://linux-hardware.org/?probe=527587d2b9) | Jun 14, 2022 |
| Lenovo        | ThinkPad T550 20CK003HMD    | [ea8155f580](https://linux-hardware.org/?probe=ea8155f580) | Jun 14, 2022 |
| Dell          | Latitude E7440              | [6bbb1944af](https://linux-hardware.org/?probe=6bbb1944af) | Jun 12, 2022 |
| Google        | Babytiger                   | [18f6f97122](https://linux-hardware.org/?probe=18f6f97122) | Jun 12, 2022 |
| HP            | EliteBook 2560p             | [5f1e0dfee7](https://linux-hardware.org/?probe=5f1e0dfee7) | Jun 09, 2022 |
| HP            | EliteBook 8570p             | [bd545aec1b](https://linux-hardware.org/?probe=bd545aec1b) | Jun 09, 2022 |
| Acer          | Aspire ES1-523              | [242fc61e3a](https://linux-hardware.org/?probe=242fc61e3a) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | [b9a30cba65](https://linux-hardware.org/?probe=b9a30cba65) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | [3c14a5bf10](https://linux-hardware.org/?probe=3c14a5bf10) | Jun 08, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | V330-14ARR 81B1             | [dad2acbf49](https://linux-hardware.org/?probe=dad2acbf49) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [af42d8d0b4](https://linux-hardware.org/?probe=af42d8d0b4) | May 27, 2022 |
| HP            | ProBook 6450b               | [8c35a4c278](https://linux-hardware.org/?probe=8c35a4c278) | May 26, 2022 |
| Dell          | Latitude E7440              | [975715a96b](https://linux-hardware.org/?probe=975715a96b) | May 26, 2022 |
| HP            | ProBook 6450b               | [863987eb13](https://linux-hardware.org/?probe=863987eb13) | May 26, 2022 |
| HP            | ProBook 650 G1              | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [62486fe8d6](https://linux-hardware.org/?probe=62486fe8d6) | May 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f0f481f187](https://linux-hardware.org/?probe=f0f481f187) | May 21, 2022 |
| SLIMBOOK      | PROX14-10                   | [b0d5e9b290](https://linux-hardware.org/?probe=b0d5e9b290) | May 19, 2022 |
| Dell          | XPS 13 9370                 | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [6efbcdabfc](https://linux-hardware.org/?probe=6efbcdabfc) | May 17, 2022 |
| Lenovo        | ThinkPad T480 20L6S14Y01    | [d3f3fff089](https://linux-hardware.org/?probe=d3f3fff089) | May 16, 2022 |
| Dell          | Precision 5750              | [11e888b7d9](https://linux-hardware.org/?probe=11e888b7d9) | May 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [591d3fa922](https://linux-hardware.org/?probe=591d3fa922) | May 07, 2022 |
| Packard Be... | EasyNote TE69BM             | [ed538d5b79](https://linux-hardware.org/?probe=ed538d5b79) | May 07, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [ac5b1123ad](https://linux-hardware.org/?probe=ac5b1123ad) | Apr 30, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [8694f28b60](https://linux-hardware.org/?probe=8694f28b60) | Apr 25, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [0cd6fe25ec](https://linux-hardware.org/?probe=0cd6fe25ec) | Apr 22, 2022 |
| Acer          | Aspire E5-553               | [1c736596fa](https://linux-hardware.org/?probe=1c736596fa) | Apr 21, 2022 |
| Lenovo        | B575e 36852EG               | [8f5e5f427a](https://linux-hardware.org/?probe=8f5e5f427a) | Apr 18, 2022 |
| Lenovo        | B575e 36852EG               | [4731516b58](https://linux-hardware.org/?probe=4731516b58) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440 20B7S1EV00    | [b035e7ae3e](https://linux-hardware.org/?probe=b035e7ae3e) | Apr 16, 2022 |
| HP            | EliteBook 820 G3            | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| MSI           | GF63 Thin 10SC              | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Acer          | Aspire V5-573G              | [2b608bcde8](https://linux-hardware.org/?probe=2b608bcde8) | Apr 04, 2022 |
| Lenovo        | ThinkPad X390 20Q0002LMX    | [22aaabe433](https://linux-hardware.org/?probe=22aaabe433) | Apr 03, 2022 |
| HP            | Laptop 14-dk1xxx            | [0ba5fd01fa](https://linux-hardware.org/?probe=0ba5fd01fa) | Mar 30, 2022 |
| HP            | Laptop 15-bw0xx             | [b9a21aea35](https://linux-hardware.org/?probe=b9a21aea35) | Mar 29, 2022 |
| Lenovo        | E31-80 80MX                 | [8dc93e34e9](https://linux-hardware.org/?probe=8dc93e34e9) | Mar 25, 2022 |
| HP            | Pavilion Notebook           | [3bf42ed5a6](https://linux-hardware.org/?probe=3bf42ed5a6) | Mar 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [72da14a2b2](https://linux-hardware.org/?probe=72da14a2b2) | Mar 23, 2022 |
| MSI           | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| Apple         | MacBookPro11,5              | [abc4597fe1](https://linux-hardware.org/?probe=abc4597fe1) | Mar 18, 2022 |
| Notebook      | P65xHP                      | [3222aab43a](https://linux-hardware.org/?probe=3222aab43a) | Mar 16, 2022 |
| Acer          | Aspire 3830T                | [bad3a5c2d7](https://linux-hardware.org/?probe=bad3a5c2d7) | Mar 15, 2022 |
| HP            | EliteBook 850 G5            | [ab88a095ac](https://linux-hardware.org/?probe=ab88a095ac) | Mar 10, 2022 |
| Dell          | Latitude E6410              | [d4fa7879a4](https://linux-hardware.org/?probe=d4fa7879a4) | Mar 09, 2022 |
| Dell          | Precision M4800             | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| Dell          | Latitude E6410              | [6748e5a7aa](https://linux-hardware.org/?probe=6748e5a7aa) | Feb 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [30879c05cc](https://linux-hardware.org/?probe=30879c05cc) | Feb 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [505e1dc8cc](https://linux-hardware.org/?probe=505e1dc8cc) | Feb 21, 2022 |
| Lenovo        | ThinkPad L530 24812SG       | [6eb3e0ed53](https://linux-hardware.org/?probe=6eb3e0ed53) | Feb 19, 2022 |
| HP            | Pavilion g6                 | [3971fd709d](https://linux-hardware.org/?probe=3971fd709d) | Feb 13, 2022 |
| Acer          | Aspire E5-575               | [3e75911df8](https://linux-hardware.org/?probe=3e75911df8) | Feb 12, 2022 |
| Apple         | MacBookPro7,1               | [b059819620](https://linux-hardware.org/?probe=b059819620) | Feb 11, 2022 |
| Apple         | MacBookPro7,1               | [87f4740598](https://linux-hardware.org/?probe=87f4740598) | Feb 11, 2022 |
| Toshiba       | Satellite L40               | [ba6d18935b](https://linux-hardware.org/?probe=ba6d18935b) | Feb 08, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [23c6243856](https://linux-hardware.org/?probe=23c6243856) | Feb 05, 2022 |
| Medion        | P7612                       | [e1c076ee06](https://linux-hardware.org/?probe=e1c076ee06) | Feb 03, 2022 |
| HP            | Compaq Presario CQ71        | [436407f045](https://linux-hardware.org/?probe=436407f045) | Feb 01, 2022 |
| Lenovo        | B50-50 80S2                 | [7602963c65](https://linux-hardware.org/?probe=7602963c65) | Feb 01, 2022 |
| Dell          | Latitude E6540              | [fe6720f0de](https://linux-hardware.org/?probe=fe6720f0de) | Jan 30, 2022 |
| Dell          | Latitude E6540              | [7c972de545](https://linux-hardware.org/?probe=7c972de545) | Jan 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [478d5281bd](https://linux-hardware.org/?probe=478d5281bd) | Jan 29, 2022 |
| HP            | Pavilion dv7                | [e6ec9b5f6a](https://linux-hardware.org/?probe=e6ec9b5f6a) | Jan 26, 2022 |
| Medion        | P7612                       | [50be4d531e](https://linux-hardware.org/?probe=50be4d531e) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| HP            | EliteBook 840 G3            | [82cce77f87](https://linux-hardware.org/?probe=82cce77f87) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| DukaPC        | Notebook                    | [21b4827b4b](https://linux-hardware.org/?probe=21b4827b4b) | Jan 21, 2022 |
| Acer          | Aspire F5-572G              | [221a91f679](https://linux-hardware.org/?probe=221a91f679) | Jan 19, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [cc39f1fd96](https://linux-hardware.org/?probe=cc39f1fd96) | Jan 18, 2022 |
| IBM           | ThinkPad T40 237342G        | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [4ebb815948](https://linux-hardware.org/?probe=4ebb815948) | Jan 15, 2022 |
| HP            | Pavilion g7                 | [6efd331acf](https://linux-hardware.org/?probe=6efd331acf) | Jan 14, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [4cefa23802](https://linux-hardware.org/?probe=4cefa23802) | Jan 14, 2022 |
| Acer          | Aspire E5-553               | [149c0538ca](https://linux-hardware.org/?probe=149c0538ca) | Jan 13, 2022 |
| Lenovo        | M30-70 80H8                 | [2f61d772a4](https://linux-hardware.org/?probe=2f61d772a4) | Jan 12, 2022 |
| Lenovo        | Y50-70 20378                | [ab93bc517a](https://linux-hardware.org/?probe=ab93bc517a) | Jan 12, 2022 |
| Razer         | Blade                       | [afad6aaa95](https://linux-hardware.org/?probe=afad6aaa95) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1f327abc43](https://linux-hardware.org/?probe=1f327abc43) | Jan 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [53a3989606](https://linux-hardware.org/?probe=53a3989606) | Jan 03, 2022 |
| Acer          | Aspire V5-573G              | [a7e3940936](https://linux-hardware.org/?probe=a7e3940936) | Jan 02, 2022 |
| Dell          | Inspiron 7720               | [4e1ebc00ff](https://linux-hardware.org/?probe=4e1ebc00ff) | Jan 02, 2022 |
| Apple         | MacBookAir7,2               | [6246bb8ef6](https://linux-hardware.org/?probe=6246bb8ef6) | Dec 31, 2021 |
| Lenovo        | V330-14ARR 81B1             | [290d6b4ad5](https://linux-hardware.org/?probe=290d6b4ad5) | Dec 29, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [13f35d1d12](https://linux-hardware.org/?probe=13f35d1d12) | Dec 26, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [369d18645c](https://linux-hardware.org/?probe=369d18645c) | Dec 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [e68ec90909](https://linux-hardware.org/?probe=e68ec90909) | Dec 24, 2021 |
| Medion        | P6630                       | [de245dfdb6](https://linux-hardware.org/?probe=de245dfdb6) | Dec 23, 2021 |
| Notebook      | N24_25JU                    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| Quanta        | MW1/HW1                     | [06bcb3603d](https://linux-hardware.org/?probe=06bcb3603d) | Dec 17, 2021 |
| ASUSTek       | K53SV                       | [be7844ea44](https://linux-hardware.org/?probe=be7844ea44) | Dec 17, 2021 |
| Lenovo        | ThinkPad T460s 20FAS05Q0... | [3a4b9beb1d](https://linux-hardware.org/?probe=3a4b9beb1d) | Dec 12, 2021 |
| Toshiba       | Satellite P850              | [bfc37f531a](https://linux-hardware.org/?probe=bfc37f531a) | Dec 11, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [e7144e5f86](https://linux-hardware.org/?probe=e7144e5f86) | Dec 09, 2021 |
| Fujitsu Si... | LIFEBOOK E8420              | [7ff3493cfe](https://linux-hardware.org/?probe=7ff3493cfe) | Dec 08, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| DukaPC        | Notebook                    | [cfb399153a](https://linux-hardware.org/?probe=cfb399153a) | Dec 01, 2021 |
| Razer         | Blade Stealth               | [54acf9844b](https://linux-hardware.org/?probe=54acf9844b) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [c224ffa45a](https://linux-hardware.org/?probe=c224ffa45a) | Nov 23, 2021 |
| Toshiba       | Satellite U300              | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| Dell          | Inspiron 7572               | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| HUAWEI        | KLVL-WXX9                   | [c80aeaf7b0](https://linux-hardware.org/?probe=c80aeaf7b0) | Nov 17, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [52eef25506](https://linux-hardware.org/?probe=52eef25506) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [7252f23e5f](https://linux-hardware.org/?probe=7252f23e5f) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [1a20afde4b](https://linux-hardware.org/?probe=1a20afde4b) | Nov 15, 2021 |
| Acer          | Aspire 5810T                | [c41d1671bc](https://linux-hardware.org/?probe=c41d1671bc) | Nov 14, 2021 |
| Lenovo        | ThinkPad R61 8935W7T        | [bef030b1ef](https://linux-hardware.org/?probe=bef030b1ef) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [e03bf03f1d](https://linux-hardware.org/?probe=e03bf03f1d) | Nov 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [1def6bd5d8](https://linux-hardware.org/?probe=1def6bd5d8) | Nov 10, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d2a33ad9d9](https://linux-hardware.org/?probe=d2a33ad9d9) | Nov 07, 2021 |
| HP            | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Apple         | MacBookPro14,1              | [68ebc1af79](https://linux-hardware.org/?probe=68ebc1af79) | Oct 28, 2021 |
| Lenovo        | ThinkPad T430s 23561R0      | [bef1593d06](https://linux-hardware.org/?probe=bef1593d06) | Oct 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [14d159c564](https://linux-hardware.org/?probe=14d159c564) | Oct 20, 2021 |
| Unknown       | Unknown                     | [a6e5e7b6ef](https://linux-hardware.org/?probe=a6e5e7b6ef) | Oct 18, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [a7fa6a8110](https://linux-hardware.org/?probe=a7fa6a8110) | Oct 14, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [df32df0b62](https://linux-hardware.org/?probe=df32df0b62) | Oct 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [c7239a1379](https://linux-hardware.org/?probe=c7239a1379) | Oct 13, 2021 |
| Toshiba       | Satellite P55W-C            | [f16be2ec1b](https://linux-hardware.org/?probe=f16be2ec1b) | Oct 13, 2021 |
| HP            | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| Acer          | Aspire A315-41              | [3d5d3ddf84](https://linux-hardware.org/?probe=3d5d3ddf84) | Oct 09, 2021 |
| Lenovo        | ThinkPad X201T 3113CC7      | [47f63d40d5](https://linux-hardware.org/?probe=47f63d40d5) | Oct 09, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [93c695e5ba](https://linux-hardware.org/?probe=93c695e5ba) | Oct 08, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | [85a242883c](https://linux-hardware.org/?probe=85a242883c) | Oct 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [56ce2c44cb](https://linux-hardware.org/?probe=56ce2c44cb) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [4d0eb4ccf2](https://linux-hardware.org/?probe=4d0eb4ccf2) | Oct 04, 2021 |
| Lenovo        | V330-14ARR 81B1             | [c8a0e5de69](https://linux-hardware.org/?probe=c8a0e5de69) | Oct 04, 2021 |
| HUAWEI        | EUL-WX9                     | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| Lenovo        | ThinkPad X260 20F5S31G00    | [575dd64064](https://linux-hardware.org/?probe=575dd64064) | Oct 01, 2021 |
| HP            | Pavilion dv7                | [31b035faec](https://linux-hardware.org/?probe=31b035faec) | Sep 28, 2021 |
| Acer          | Aspire 5810T                | [be3f4d5a01](https://linux-hardware.org/?probe=be3f4d5a01) | Sep 26, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [edfae5b796](https://linux-hardware.org/?probe=edfae5b796) | Sep 25, 2021 |
| HUAWEI        | MACHC-WAX9                  | [e2fc9d2585](https://linux-hardware.org/?probe=e2fc9d2585) | Sep 23, 2021 |
| Dell          | XPS 13 9370                 | [5df047615c](https://linux-hardware.org/?probe=5df047615c) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | [d7ccece3d4](https://linux-hardware.org/?probe=d7ccece3d4) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | [466841a201](https://linux-hardware.org/?probe=466841a201) | Sep 22, 2021 |
| HP            | ZBook 15                    | [206882306c](https://linux-hardware.org/?probe=206882306c) | Sep 20, 2021 |
| Lenovo        | V130-15IKB 81HN             | [f427b869d9](https://linux-hardware.org/?probe=f427b869d9) | Sep 17, 2021 |
| Lenovo        | ThinkPad X220 4291WAY       | [ca0ab89977](https://linux-hardware.org/?probe=ca0ab89977) | Sep 16, 2021 |
| Lenovo        | ThinkPad W541 20EFS01B09    | [8dd2c7497e](https://linux-hardware.org/?probe=8dd2c7497e) | Sep 13, 2021 |
| Dell          | Inspiron 3583               | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| HP            | Pavilion dv7                | [2fd3b811f6](https://linux-hardware.org/?probe=2fd3b811f6) | Sep 12, 2021 |
| Dell          | XPS 15 9510                 | [1b80533734](https://linux-hardware.org/?probe=1b80533734) | Sep 11, 2021 |
| Dell          | XPS 15 9510                 | [4befd2306c](https://linux-hardware.org/?probe=4befd2306c) | Sep 11, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5cf3ed1411](https://linux-hardware.org/?probe=5cf3ed1411) | Aug 31, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | [70585e2360](https://linux-hardware.org/?probe=70585e2360) | Aug 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [9c0457479f](https://linux-hardware.org/?probe=9c0457479f) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [23b7937411](https://linux-hardware.org/?probe=23b7937411) | Aug 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [9382443dc7](https://linux-hardware.org/?probe=9382443dc7) | Aug 27, 2021 |
| Google        | Relm                        | [12475037ed](https://linux-hardware.org/?probe=12475037ed) | Aug 27, 2021 |
| Google        | Relm                        | [36e7a1d7a1](https://linux-hardware.org/?probe=36e7a1d7a1) | Aug 26, 2021 |
| HP            | ProBook 650 G1              | [61f6289d2c](https://linux-hardware.org/?probe=61f6289d2c) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 2325AN3       | [d6b5ef49af](https://linux-hardware.org/?probe=d6b5ef49af) | Aug 24, 2021 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [900b0ce643](https://linux-hardware.org/?probe=900b0ce643) | Aug 24, 2021 |
| HP            | ZBook 15 G6                 | [93ec0ceb52](https://linux-hardware.org/?probe=93ec0ceb52) | Aug 23, 2021 |
| Lenovo        | ThinkPad E595 20NF001HMX    | [8e75269d33](https://linux-hardware.org/?probe=8e75269d33) | Aug 20, 2021 |
| Lenovo        | G550 2958                   | [5207c5584c](https://linux-hardware.org/?probe=5207c5584c) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | [b7b363db20](https://linux-hardware.org/?probe=b7b363db20) | Aug 15, 2021 |
| HP            | ProBook 445 G7              | [e42e169a72](https://linux-hardware.org/?probe=e42e169a72) | Aug 15, 2021 |
| HP            | Notebook                    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| GPD           | P2 MAX                      | [78f79b2790](https://linux-hardware.org/?probe=78f79b2790) | Jul 31, 2021 |
| ASUSTek       | GL702VM                     | [bb9d228646](https://linux-hardware.org/?probe=bb9d228646) | Jul 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [a02dac8dff](https://linux-hardware.org/?probe=a02dac8dff) | Jul 23, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | [e52365f866](https://linux-hardware.org/?probe=e52365f866) | Jul 21, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | [704fb2e1d1](https://linux-hardware.org/?probe=704fb2e1d1) | Jul 21, 2021 |
| Dell          | Latitude 7370               | [b10d4c18f2](https://linux-hardware.org/?probe=b10d4c18f2) | Jul 19, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | [7a03dbd869](https://linux-hardware.org/?probe=7a03dbd869) | Jul 17, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | [ce58f3f770](https://linux-hardware.org/?probe=ce58f3f770) | Jul 16, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [a56195f1f1](https://linux-hardware.org/?probe=a56195f1f1) | Jul 13, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [440841d04a](https://linux-hardware.org/?probe=440841d04a) | Jul 12, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [3b106f1da0](https://linux-hardware.org/?probe=3b106f1da0) | Jul 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [f8872c9e84](https://linux-hardware.org/?probe=f8872c9e84) | Jul 05, 2021 |
| AMI           | Cherry Trail CR             | [4e6f9ccc6c](https://linux-hardware.org/?probe=4e6f9ccc6c) | Jul 05, 2021 |
| DukaPC        | Notebook                    | [6d87054512](https://linux-hardware.org/?probe=6d87054512) | Jul 02, 2021 |
| HP            | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| Timi          | TM1703                      | [bd3756811d](https://linux-hardware.org/?probe=bd3756811d) | Jun 26, 2021 |
| DukaPC        | Notebook                    | [c29d208cdf](https://linux-hardware.org/?probe=c29d208cdf) | Jun 24, 2021 |
| Lenovo        | ThinkPad T420 4236Y19       | [48927432b4](https://linux-hardware.org/?probe=48927432b4) | Jun 20, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d8ad69d368](https://linux-hardware.org/?probe=d8ad69d368) | Jun 15, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0Y70... | [5e57af6782](https://linux-hardware.org/?probe=5e57af6782) | Jun 11, 2021 |
| Lenovo        | ThinkPad T420 4236PFG       | [fa5abfccf8](https://linux-hardware.org/?probe=fa5abfccf8) | Jun 04, 2021 |
| HP            | Compaq Presario CQ71        | [d4deb2b08d](https://linux-hardware.org/?probe=d4deb2b08d) | Jun 01, 2021 |
| Dell          | Latitude E6520              | [d1d0976880](https://linux-hardware.org/?probe=d1d0976880) | May 31, 2021 |
| Lenovo        | ThinkPad T400 647358G       | [b4f44d7932](https://linux-hardware.org/?probe=b4f44d7932) | May 29, 2021 |
| Toshiba       | Satellite C660              | [58d3740c30](https://linux-hardware.org/?probe=58d3740c30) | May 28, 2021 |
| Acer          | Aspire E5-553               | [70037bddcb](https://linux-hardware.org/?probe=70037bddcb) | May 27, 2021 |
| LAMINA        | T-1012B NORD                | [71e70e946a](https://linux-hardware.org/?probe=71e70e946a) | May 25, 2021 |
| LAMINA        | T-1012B NORD                | [9dc2932064](https://linux-hardware.org/?probe=9dc2932064) | May 24, 2021 |
| ASUSTek       | X553SA                      | [c470382d2a](https://linux-hardware.org/?probe=c470382d2a) | May 24, 2021 |
| ASUSTek       | X553SA                      | [31d6a914fd](https://linux-hardware.org/?probe=31d6a914fd) | May 24, 2021 |
| Acer          | Aspire E5-511               | [9edec55620](https://linux-hardware.org/?probe=9edec55620) | May 23, 2021 |
| Acer          | Aspire E5-511               | [e20c93a2c1](https://linux-hardware.org/?probe=e20c93a2c1) | May 23, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [a9e4c7793b](https://linux-hardware.org/?probe=a9e4c7793b) | May 18, 2021 |
| eMachines     | E725                        | [329f8f580e](https://linux-hardware.org/?probe=329f8f580e) | May 14, 2021 |
| ASUSTek       | K95VM                       | [58d4ed3c2b](https://linux-hardware.org/?probe=58d4ed3c2b) | May 10, 2021 |
| HP            | 15                          | [a13c097d59](https://linux-hardware.org/?probe=a13c097d59) | May 09, 2021 |
| HP            | 15                          | [c3cdcdab60](https://linux-hardware.org/?probe=c3cdcdab60) | May 09, 2021 |
| Alienware     | 17 R2                       | [a8470edc65](https://linux-hardware.org/?probe=a8470edc65) | May 06, 2021 |
| ASUSTek       | G74Sx                       | [73c1eaa647](https://linux-hardware.org/?probe=73c1eaa647) | Apr 29, 2021 |
| Lenovo        | ThinkPad T520 4243PC2       | [915d41f361](https://linux-hardware.org/?probe=915d41f361) | Apr 29, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [e259d34a4c](https://linux-hardware.org/?probe=e259d34a4c) | Apr 28, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | [e2f8b2beda](https://linux-hardware.org/?probe=e2f8b2beda) | Apr 25, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | [684f1471b1](https://linux-hardware.org/?probe=684f1471b1) | Apr 23, 2021 |
| Lenovo        | E31-80 80MX                 | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [bd14a696eb](https://linux-hardware.org/?probe=bd14a696eb) | Apr 20, 2021 |
| Lenovo        | ThinkPad T520 42434YG       | [8e0b4ee3a1](https://linux-hardware.org/?probe=8e0b4ee3a1) | Apr 17, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | [49e1959064](https://linux-hardware.org/?probe=49e1959064) | Apr 16, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | [b2853266e8](https://linux-hardware.org/?probe=b2853266e8) | Apr 15, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [4b127c0ba4](https://linux-hardware.org/?probe=4b127c0ba4) | Apr 11, 2021 |
| HP            | Laptop 15-da1xxx            | [a844e710cc](https://linux-hardware.org/?probe=a844e710cc) | Apr 09, 2021 |
| Lenovo        | ThinkPad T60 20076RG        | [aa3ea77acf](https://linux-hardware.org/?probe=aa3ea77acf) | Apr 08, 2021 |
| HP            | G72                         | [2ab4eb5fcd](https://linux-hardware.org/?probe=2ab4eb5fcd) | Apr 05, 2021 |
| ASUSTek       | K95VM                       | [81a01884d2](https://linux-hardware.org/?probe=81a01884d2) | Mar 24, 2021 |
| Lenovo        | ThinkPad W520 4284Y54       | [8d564e495b](https://linux-hardware.org/?probe=8d564e495b) | Mar 23, 2021 |
| Toshiba       | Satellite L350D             | [b083513b72](https://linux-hardware.org/?probe=b083513b72) | Mar 23, 2021 |
| Acer          | Aspire E5-553               | [0c21dc1b96](https://linux-hardware.org/?probe=0c21dc1b96) | Mar 19, 2021 |
| HP            | Pavilion dm1                | [438cf03315](https://linux-hardware.org/?probe=438cf03315) | Mar 18, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | [7e7a4bc992](https://linux-hardware.org/?probe=7e7a4bc992) | Mar 18, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | [1b8a078a19](https://linux-hardware.org/?probe=1b8a078a19) | Mar 16, 2021 |
| HP            | EliteBook 830 G5            | [248eb896a0](https://linux-hardware.org/?probe=248eb896a0) | Mar 15, 2021 |
| HP            | Compaq Presario CQ60        | [e4613a6f75](https://linux-hardware.org/?probe=e4613a6f75) | Mar 15, 2021 |
| Dell          | Latitude E5250              | [22067e0909](https://linux-hardware.org/?probe=22067e0909) | Mar 13, 2021 |
| Dell          | Latitude E5250              | [df9d913f0f](https://linux-hardware.org/?probe=df9d913f0f) | Mar 13, 2021 |
| HP            | Pavilion dv9700             | [f55ec4dd18](https://linux-hardware.org/?probe=f55ec4dd18) | Mar 11, 2021 |
| Dell          | XPS 13 9370                 | [865e070587](https://linux-hardware.org/?probe=865e070587) | Mar 10, 2021 |
| Dell          | Latitude E5250              | [78f0a24d9a](https://linux-hardware.org/?probe=78f0a24d9a) | Mar 07, 2021 |
| Acer          | Aspire E5-575G              | [18240d24d8](https://linux-hardware.org/?probe=18240d24d8) | Mar 06, 2021 |
| Toshiba       | Satellite L350D             | [ef8a29af20](https://linux-hardware.org/?probe=ef8a29af20) | Mar 05, 2021 |
| Acer          | Aspire E5-553               | [74e6da0017](https://linux-hardware.org/?probe=74e6da0017) | Feb 27, 2021 |
| HP            | 630                         | [6803747e34](https://linux-hardware.org/?probe=6803747e34) | Feb 22, 2021 |
| HP            | 630                         | [8b04fe81aa](https://linux-hardware.org/?probe=8b04fe81aa) | Feb 22, 2021 |
| Lenovo        | ThinkPad T61 7661W1D        | [6db91fdd34](https://linux-hardware.org/?probe=6db91fdd34) | Feb 17, 2021 |
| Lenovo        | 3000 G530 444622G           | [3ef99e25df](https://linux-hardware.org/?probe=3ef99e25df) | Feb 16, 2021 |
| Lenovo        | ThinkPad X240 20AMA2AE00    | [2730f6215a](https://linux-hardware.org/?probe=2730f6215a) | Feb 12, 2021 |
| Dell          | XPS 13 9360                 | [564f71d6f3](https://linux-hardware.org/?probe=564f71d6f3) | Feb 10, 2021 |
| Acer          | Aspire E5-553               | [ab7532985d](https://linux-hardware.org/?probe=ab7532985d) | Feb 05, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [ed806c00b2](https://linux-hardware.org/?probe=ed806c00b2) | Feb 04, 2021 |
| HP            | EliteBook 2560p             | [f741035d0d](https://linux-hardware.org/?probe=f741035d0d) | Feb 02, 2021 |
| HP            | EliteBook 840 G5            | [19ef5f3adb](https://linux-hardware.org/?probe=19ef5f3adb) | Jan 29, 2021 |
| Dell          | Latitude E7440              | [ee2c17a895](https://linux-hardware.org/?probe=ee2c17a895) | Jan 26, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [964b7c1b1f](https://linux-hardware.org/?probe=964b7c1b1f) | Jan 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [82da77953a](https://linux-hardware.org/?probe=82da77953a) | Jan 19, 2021 |
| Dell          | Latitude 5500               | [d7e06bd87b](https://linux-hardware.org/?probe=d7e06bd87b) | Jan 18, 2021 |
| Dell          | Latitude 5500               | [f40a2d50bc](https://linux-hardware.org/?probe=f40a2d50bc) | Jan 16, 2021 |
| Quanta        | MW1/HW1                     | [ebab0a47f8](https://linux-hardware.org/?probe=ebab0a47f8) | Jan 16, 2021 |
| Lenovo        | ThinkPad P52 20M9001GMX     | [ffdee2c6e0](https://linux-hardware.org/?probe=ffdee2c6e0) | Jan 11, 2021 |
| Dell          | XPS 13 9300                 | [229b46a693](https://linux-hardware.org/?probe=229b46a693) | Jan 10, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [fa963386d8](https://linux-hardware.org/?probe=fa963386d8) | Jan 07, 2021 |
| Toshiba       | Satellite L40               | [bd26bbbe43](https://linux-hardware.org/?probe=bd26bbbe43) | Jan 06, 2021 |
| Lenovo        | G570 4334                   | [c643363b80](https://linux-hardware.org/?probe=c643363b80) | Jan 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2ed1a3283e](https://linux-hardware.org/?probe=2ed1a3283e) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [c0c38c5aee](https://linux-hardware.org/?probe=c0c38c5aee) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [65fe7eb049](https://linux-hardware.org/?probe=65fe7eb049) | Dec 30, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c3f9fc25d4](https://linux-hardware.org/?probe=c3f9fc25d4) | Dec 29, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [dbc2669fc0](https://linux-hardware.org/?probe=dbc2669fc0) | Dec 28, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [f514e54057](https://linux-hardware.org/?probe=f514e54057) | Dec 28, 2020 |
| ASUSTek       | PU401LAC                    | [c5bf49eabf](https://linux-hardware.org/?probe=c5bf49eabf) | Dec 26, 2020 |
| HP            | EliteBook 850 G5            | [ce2a32dd24](https://linux-hardware.org/?probe=ce2a32dd24) | Dec 22, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3e419467e2](https://linux-hardware.org/?probe=3e419467e2) | Dec 22, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [87c08ecbb6](https://linux-hardware.org/?probe=87c08ecbb6) | Dec 22, 2020 |
| Notebook      | W54_55SU1,SUW               | [52e86fd2a9](https://linux-hardware.org/?probe=52e86fd2a9) | Dec 20, 2020 |
| Lenovo        | ThinkPad T490s 20NX001PM... | [af7d2d4eb5](https://linux-hardware.org/?probe=af7d2d4eb5) | Dec 20, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [14a84d3948](https://linux-hardware.org/?probe=14a84d3948) | Dec 20, 2020 |
| Lenovo        | ThinkPad T520 4243W54       | [15862aca5c](https://linux-hardware.org/?probe=15862aca5c) | Dec 20, 2020 |
| Lenovo        | ThinkPad X260 20F5S31G00    | [01b87f6602](https://linux-hardware.org/?probe=01b87f6602) | Dec 18, 2020 |
| Lenovo        | Unknown                     | [92b19a0db9](https://linux-hardware.org/?probe=92b19a0db9) | Dec 18, 2020 |
| Dell          | Latitude E7270              | [bac2c2820f](https://linux-hardware.org/?probe=bac2c2820f) | Dec 17, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [5dfa78d268](https://linux-hardware.org/?probe=5dfa78d268) | Dec 15, 2020 |
| HP            | ProBook 650 G5              | [56c46edc3f](https://linux-hardware.org/?probe=56c46edc3f) | Dec 13, 2020 |
| HP            | ProBook 650 G5              | [a035f76fcb](https://linux-hardware.org/?probe=a035f76fcb) | Dec 12, 2020 |
| Acer          | Extensa 2519                | [17bdd3b68f](https://linux-hardware.org/?probe=17bdd3b68f) | Dec 10, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [e9f3972862](https://linux-hardware.org/?probe=e9f3972862) | Dec 04, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [f98c566bb6](https://linux-hardware.org/?probe=f98c566bb6) | Dec 03, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [ff051ee214](https://linux-hardware.org/?probe=ff051ee214) | Dec 01, 2020 |
| Dell          | Latitude E6540              | [5a0fbaa262](https://linux-hardware.org/?probe=5a0fbaa262) | Nov 28, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [8b31225bd7](https://linux-hardware.org/?probe=8b31225bd7) | Nov 27, 2020 |
| Apple         | MacBookPro7,1               | [ad6bb1f253](https://linux-hardware.org/?probe=ad6bb1f253) | Nov 24, 2020 |
| Lenovo        | ThinkPad P52 20M9001MMD     | [72ba2ae6cb](https://linux-hardware.org/?probe=72ba2ae6cb) | Nov 19, 2020 |
| Acer          | Aspire V3-575G              | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| Dell          | System XPS L321X            | [3fb9a4373c](https://linux-hardware.org/?probe=3fb9a4373c) | Nov 18, 2020 |
| Lenovo        | ThinkPad T530 24292VG       | [3460614c7f](https://linux-hardware.org/?probe=3460614c7f) | Nov 15, 2020 |
| Lenovo        | ThinkPad W541 20EFS01B09    | [ee5da1d9b0](https://linux-hardware.org/?probe=ee5da1d9b0) | Nov 10, 2020 |
| Lenovo        | ThinkPad X301 2776LEG       | [2c4aa61663](https://linux-hardware.org/?probe=2c4aa61663) | Nov 09, 2020 |
| Dell          | XPS 13 9370                 | [b75b281fee](https://linux-hardware.org/?probe=b75b281fee) | Nov 08, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [de9ea1422c](https://linux-hardware.org/?probe=de9ea1422c) | Nov 08, 2020 |
| HP            | Pavilion Notebook           | [1698bf3366](https://linux-hardware.org/?probe=1698bf3366) | Nov 07, 2020 |
| HP            | EliteBook 820 G3            | [e34831e959](https://linux-hardware.org/?probe=e34831e959) | Nov 07, 2020 |
| Dell          | XPS 15 9570                 | [bb40872a6b](https://linux-hardware.org/?probe=bb40872a6b) | Nov 05, 2020 |
| HP            | ProBook 4720s               | [acb46376ad](https://linux-hardware.org/?probe=acb46376ad) | Nov 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [d65f8070e0](https://linux-hardware.org/?probe=d65f8070e0) | Nov 03, 2020 |
| HP            | Compaq 8510p                | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Dell          | XPS 15 9560                 | [5e06a37540](https://linux-hardware.org/?probe=5e06a37540) | Nov 01, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [1213098826](https://linux-hardware.org/?probe=1213098826) | Oct 30, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [de02478ef0](https://linux-hardware.org/?probe=de02478ef0) | Oct 29, 2020 |
| Lenovo        | E31-80 80MX                 | [d56dacea36](https://linux-hardware.org/?probe=d56dacea36) | Oct 29, 2020 |
| Razer         | Blade                       | [7aef75c2c6](https://linux-hardware.org/?probe=7aef75c2c6) | Oct 28, 2020 |
| Dell          | Vostro 3558                 | [eda9a94c60](https://linux-hardware.org/?probe=eda9a94c60) | Oct 28, 2020 |
| Acer          | Nitro AN515-53              | [08235cd1ad](https://linux-hardware.org/?probe=08235cd1ad) | Oct 25, 2020 |
| Acer          | Nitro AN515-53              | [80a32fe04b](https://linux-hardware.org/?probe=80a32fe04b) | Oct 24, 2020 |
| Dell          | Vostro 3558                 | [e22529c904](https://linux-hardware.org/?probe=e22529c904) | Oct 23, 2020 |
| Apple         | MacBookPro5,5               | [b7c6f0c157](https://linux-hardware.org/?probe=b7c6f0c157) | Oct 22, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [cbd374b1d9](https://linux-hardware.org/?probe=cbd374b1d9) | Oct 22, 2020 |
| Toshiba       | Satellite L40               | [3d02e46571](https://linux-hardware.org/?probe=3d02e46571) | Oct 22, 2020 |
| HP            | EliteBook 850 G5            | [1a2d14ded4](https://linux-hardware.org/?probe=1a2d14ded4) | Oct 20, 2020 |
| HP            | Pavilion dv6                | [6fd2a79436](https://linux-hardware.org/?probe=6fd2a79436) | Oct 18, 2020 |
| Toshiba       | Satellite P50-A-11J         | [720f19d566](https://linux-hardware.org/?probe=720f19d566) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| Acer          | Aspire V5-573               | [20453e8620](https://linux-hardware.org/?probe=20453e8620) | Oct 10, 2020 |
| Acer          | Aspire V5-573               | [eee8f03871](https://linux-hardware.org/?probe=eee8f03871) | Oct 10, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [4ffeac234f](https://linux-hardware.org/?probe=4ffeac234f) | Oct 09, 2020 |
| Acer          | Nitro AN515-53              | [fe2889ef02](https://linux-hardware.org/?probe=fe2889ef02) | Oct 08, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | [bea20b3463](https://linux-hardware.org/?probe=bea20b3463) | Oct 04, 2020 |
| Acer          | Aspire 7551                 | [0524a7f258](https://linux-hardware.org/?probe=0524a7f258) | Oct 04, 2020 |
| Acer          | Aspire VN7-792G             | [908eea39dd](https://linux-hardware.org/?probe=908eea39dd) | Oct 04, 2020 |
| Acer          | Nitro AN515-53              | [a1d00d9bc3](https://linux-hardware.org/?probe=a1d00d9bc3) | Oct 03, 2020 |
| Acer          | Nitro AN515-53              | [be2aafbbae](https://linux-hardware.org/?probe=be2aafbbae) | Oct 03, 2020 |
| HP            | ProBook 650 G2              | [f04b6dbdc5](https://linux-hardware.org/?probe=f04b6dbdc5) | Oct 02, 2020 |
| HP            | ProBook 650 G2              | [7b826236e8](https://linux-hardware.org/?probe=7b826236e8) | Oct 02, 2020 |
| Lenovo        | ThinkPad P51 20HH001QMD     | [9a69eca48e](https://linux-hardware.org/?probe=9a69eca48e) | Oct 01, 2020 |
| Acer          | AOD270                      | [4d7f40e97b](https://linux-hardware.org/?probe=4d7f40e97b) | Sep 30, 2020 |
| Lenovo        | 3000 N200 0769B6G           | [7e9967fb0e](https://linux-hardware.org/?probe=7e9967fb0e) | Sep 30, 2020 |
| Lenovo        | ThinkPad P51 20HH001QMD     | [3b51f51354](https://linux-hardware.org/?probe=3b51f51354) | Sep 29, 2020 |
| Notebook      | W54_55SU1,SUW               | [8616e28654](https://linux-hardware.org/?probe=8616e28654) | Sep 29, 2020 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [a3846db026](https://linux-hardware.org/?probe=a3846db026) | Sep 26, 2020 |
| Lenovo        | G710 20252                  | [6d3ef693db](https://linux-hardware.org/?probe=6d3ef693db) | Sep 23, 2020 |
| HP            | Pavilion Sleekbook 15       | [d5217dd737](https://linux-hardware.org/?probe=d5217dd737) | Sep 20, 2020 |
| Google        | Liara                       | [e6434b38e5](https://linux-hardware.org/?probe=e6434b38e5) | Sep 16, 2020 |
| HP            | 620                         | [3cd40bde20](https://linux-hardware.org/?probe=3cd40bde20) | Sep 11, 2020 |
| MSI           | PS42 8RB                    | [1f2fba4e2e](https://linux-hardware.org/?probe=1f2fba4e2e) | Sep 11, 2020 |
| MSI           | PS42 8RB                    | [46f7d12d9e](https://linux-hardware.org/?probe=46f7d12d9e) | Sep 11, 2020 |
| HP            | EliteBook 850 G5            | [826772015a](https://linux-hardware.org/?probe=826772015a) | Sep 09, 2020 |
| LG Electro... | 17Z90N-V.AA77G              | [eaeb99f180](https://linux-hardware.org/?probe=eaeb99f180) | Sep 06, 2020 |
| Apple         | MacBookPro10,1              | [3d676f563d](https://linux-hardware.org/?probe=3d676f563d) | Sep 06, 2020 |
| Lenovo        | ThinkPad X230 2325W3J       | [b076277c46](https://linux-hardware.org/?probe=b076277c46) | Sep 05, 2020 |
| Lenovo        | ThinkPad X240 20AMS39B00    | [b2f7ace5e9](https://linux-hardware.org/?probe=b2f7ace5e9) | Sep 05, 2020 |
| Notebook      | W35xSTQ_370ST               | [69960189a7](https://linux-hardware.org/?probe=69960189a7) | Sep 04, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | [392b8d8877](https://linux-hardware.org/?probe=392b8d8877) | Sep 04, 2020 |
| Lenovo        | V110-15IAP 80TG             | [74a552046a](https://linux-hardware.org/?probe=74a552046a) | Sep 02, 2020 |
| Toshiba       | Satellite L755D             | [e3aa57d80d](https://linux-hardware.org/?probe=e3aa57d80d) | Aug 30, 2020 |
| HP            | 620                         | [2abb876aa3](https://linux-hardware.org/?probe=2abb876aa3) | Aug 27, 2020 |
| Purism        | Librem 13 v2                | [23cd34d2f6](https://linux-hardware.org/?probe=23cd34d2f6) | Aug 27, 2020 |
| HP            | Pavilion dm1                | [39154c83b0](https://linux-hardware.org/?probe=39154c83b0) | Aug 27, 2020 |
| Acer          | NC-SF314-51-56Y4            | [0627a672e7](https://linux-hardware.org/?probe=0627a672e7) | Aug 27, 2020 |
| Lenovo        | Unknown                     | [74313d4eb1](https://linux-hardware.org/?probe=74313d4eb1) | Aug 24, 2020 |
| Lenovo        | ThinkPad P50s 20FLS02200    | [68d5ec0716](https://linux-hardware.org/?probe=68d5ec0716) | Aug 24, 2020 |
| HP            | ProBook 650 G2              | [4a91b4b21f](https://linux-hardware.org/?probe=4a91b4b21f) | Aug 18, 2020 |
| Razer         | Blade                       | [b8e7f44d4a](https://linux-hardware.org/?probe=b8e7f44d4a) | Aug 17, 2020 |
| HP            | EliteBook 820 G3            | [0d1ad99429](https://linux-hardware.org/?probe=0d1ad99429) | Aug 13, 2020 |
| Toshiba       | Satellite L40               | [33ec17e21b](https://linux-hardware.org/?probe=33ec17e21b) | Aug 13, 2020 |
| Lenovo        | ThinkPad P53 20QN002VMX     | [8e3eee2d07](https://linux-hardware.org/?probe=8e3eee2d07) | Aug 06, 2020 |
| Lenovo        | ThinkPad P53 20QN002VMX     | [6b9f38754c](https://linux-hardware.org/?probe=6b9f38754c) | Aug 06, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [72a1412fb1](https://linux-hardware.org/?probe=72a1412fb1) | Aug 04, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [133bc3dd52](https://linux-hardware.org/?probe=133bc3dd52) | Aug 04, 2020 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [6d4445f122](https://linux-hardware.org/?probe=6d4445f122) | Aug 02, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [c535bd5654](https://linux-hardware.org/?probe=c535bd5654) | Jul 29, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [fa42e14984](https://linux-hardware.org/?probe=fa42e14984) | Jul 28, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [e748a3510c](https://linux-hardware.org/?probe=e748a3510c) | Jul 27, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [3122f02f2c](https://linux-hardware.org/?probe=3122f02f2c) | Jul 23, 2020 |
| Packard Be... | EasyNote LJ73               | [b7cb387fea](https://linux-hardware.org/?probe=b7cb387fea) | Jul 21, 2020 |
| Dell          | Latitude E6420              | [e9238dcfff](https://linux-hardware.org/?probe=e9238dcfff) | Jul 19, 2020 |
| Dell          | Latitude E6420              | [231cadfc4a](https://linux-hardware.org/?probe=231cadfc4a) | Jul 19, 2020 |
| Toshiba       | Satellite L755D             | [a0cdb2f0bf](https://linux-hardware.org/?probe=a0cdb2f0bf) | Jul 12, 2020 |
| Toshiba       | Satellite L755D             | [f4ab460d93](https://linux-hardware.org/?probe=f4ab460d93) | Jul 12, 2020 |
| Dell          | Latitude 7480               | [c265940ec9](https://linux-hardware.org/?probe=c265940ec9) | Jul 11, 2020 |
| Apple         | MacBookPro6,1               | [432c9e6acf](https://linux-hardware.org/?probe=432c9e6acf) | Jul 05, 2020 |
| Apple         | MacBookPro14,1              | [b1b965bcfa](https://linux-hardware.org/?probe=b1b965bcfa) | Jul 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [26dfef89d5](https://linux-hardware.org/?probe=26dfef89d5) | Jun 30, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [3f43b86780](https://linux-hardware.org/?probe=3f43b86780) | Jun 29, 2020 |
| Fujitsu       | LIFEBOOK U938               | [445cfe436d](https://linux-hardware.org/?probe=445cfe436d) | Jun 28, 2020 |
| ASUSTek       | K56CB                       | [bbdd76a080](https://linux-hardware.org/?probe=bbdd76a080) | Jun 21, 2020 |
| Fujitsu       | LIFEBOOK U938               | [6fab40c5c2](https://linux-hardware.org/?probe=6fab40c5c2) | Jun 20, 2020 |
| Acer          | Mantasta                    | [fae9194978](https://linux-hardware.org/?probe=fae9194978) | Jun 19, 2020 |
| HP            | SpectreXT Pro 13-b000 PC    | [12d9fce39b](https://linux-hardware.org/?probe=12d9fce39b) | Jun 18, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [8307e528e0](https://linux-hardware.org/?probe=8307e528e0) | Jun 17, 2020 |
| HP            | Pavilion 15                 | [6d0c4b8b4f](https://linux-hardware.org/?probe=6d0c4b8b4f) | Jun 16, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [c9de665933](https://linux-hardware.org/?probe=c9de665933) | Jun 14, 2020 |
| Dell          | Latitude 7480               | [f1120b6914](https://linux-hardware.org/?probe=f1120b6914) | Jun 14, 2020 |
| Dell          | XPS 15 9560                 | [68f8b211cb](https://linux-hardware.org/?probe=68f8b211cb) | Jun 13, 2020 |
| Dell          | XPS 15 9560                 | [5e9c9bd030](https://linux-hardware.org/?probe=5e9c9bd030) | Jun 13, 2020 |
| Razer         | Blade                       | [5ed51b12b4](https://linux-hardware.org/?probe=5ed51b12b4) | Jun 12, 2020 |
| HP            | SpectreXT Pro 13-b000 PC    | [6e1571661e](https://linux-hardware.org/?probe=6e1571661e) | Jun 12, 2020 |
| Lenovo        | ThinkPad W520 4284Y19       | [ac2ade7339](https://linux-hardware.org/?probe=ac2ade7339) | Jun 07, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [1431224dcf](https://linux-hardware.org/?probe=1431224dcf) | Jun 03, 2020 |
| Dell          | XPS 15 7590                 | [386ef00203](https://linux-hardware.org/?probe=386ef00203) | May 25, 2020 |
| Dell          | XPS 15 7590                 | [544670327d](https://linux-hardware.org/?probe=544670327d) | May 21, 2020 |
| Acer          | TravelMate 6592             | [9bb4619272](https://linux-hardware.org/?probe=9bb4619272) | May 17, 2020 |
| Acer          | TravelMate 6592             | [e4e54de319](https://linux-hardware.org/?probe=e4e54de319) | May 17, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [788a18932c](https://linux-hardware.org/?probe=788a18932c) | May 16, 2020 |
| Acer          | Swift SF514-52T             | [93ede38f81](https://linux-hardware.org/?probe=93ede38f81) | May 16, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [b47983a36a](https://linux-hardware.org/?probe=b47983a36a) | May 13, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [5fbd9385df](https://linux-hardware.org/?probe=5fbd9385df) | May 13, 2020 |
| Lenovo        | ThinkPad T410 2522WPH       | [236d1e64eb](https://linux-hardware.org/?probe=236d1e64eb) | May 10, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a54bb2200a](https://linux-hardware.org/?probe=a54bb2200a) | May 06, 2020 |
| HP            | 255 G7 Notebook PC          | [0a904bfe70](https://linux-hardware.org/?probe=0a904bfe70) | May 05, 2020 |
| TUXEDO        | Unknown                     | [3f23947dd8](https://linux-hardware.org/?probe=3f23947dd8) | May 04, 2020 |
| HP            | 255 G7 Notebook PC          | [b85ac004b3](https://linux-hardware.org/?probe=b85ac004b3) | May 04, 2020 |
| Lenovo        | ThinkPad T480s 20L8S5U50... | [d295ec1834](https://linux-hardware.org/?probe=d295ec1834) | May 03, 2020 |
| Dell          | Latitude E7450              | [0f14ff60e1](https://linux-hardware.org/?probe=0f14ff60e1) | May 02, 2020 |
| HP            | EliteBook 840 G1            | [9c6700839f](https://linux-hardware.org/?probe=9c6700839f) | May 01, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [689865b9bf](https://linux-hardware.org/?probe=689865b9bf) | Apr 30, 2020 |
| Acer          | Aspire A715-72G             | [db52ab416a](https://linux-hardware.org/?probe=db52ab416a) | Apr 29, 2020 |
| HP            | EliteBook 840 G1            | [b77a2c1bdc](https://linux-hardware.org/?probe=b77a2c1bdc) | Apr 27, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0MS0... | [2ea2bebae7](https://linux-hardware.org/?probe=2ea2bebae7) | Apr 25, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0MS0... | [47ae6712b9](https://linux-hardware.org/?probe=47ae6712b9) | Apr 25, 2020 |
| HP            | Unknown                     | [7da32c9344](https://linux-hardware.org/?probe=7da32c9344) | Apr 21, 2020 |
| Dell          | Latitude E5510              | [a70ec059cf](https://linux-hardware.org/?probe=a70ec059cf) | Apr 13, 2020 |
| HP            | Pavilion dv9700             | [6096eebeb4](https://linux-hardware.org/?probe=6096eebeb4) | Apr 11, 2020 |
| Apple         | MacBookPro5,5               | [9f7081cc76](https://linux-hardware.org/?probe=9f7081cc76) | Apr 04, 2020 |
| Lenovo        | B50-10 80QR                 | [587fb80750](https://linux-hardware.org/?probe=587fb80750) | Apr 01, 2020 |
| Dixonsxp      | Unknown                     | [bfb0ade0c7](https://linux-hardware.org/?probe=bfb0ade0c7) | Apr 01, 2020 |
| Dixonsxp      | Unknown                     | [26154d1d2c](https://linux-hardware.org/?probe=26154d1d2c) | Apr 01, 2020 |
| ASUSTek       | N76VB                       | [a771ac7748](https://linux-hardware.org/?probe=a771ac7748) | Mar 24, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [069d575f4a](https://linux-hardware.org/?probe=069d575f4a) | Mar 21, 2020 |
| HP            | Pavilion dv7                | [64000a6ec8](https://linux-hardware.org/?probe=64000a6ec8) | Mar 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [69559fb5ce](https://linux-hardware.org/?probe=69559fb5ce) | Mar 18, 2020 |
| Toshiba       | Satellite C670D-10C         | [bdcd7e9b36](https://linux-hardware.org/?probe=bdcd7e9b36) | Mar 17, 2020 |
| Toshiba       | Satellite C670D-10C         | [ab2ea68be0](https://linux-hardware.org/?probe=ab2ea68be0) | Mar 17, 2020 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [86e1d115b9](https://linux-hardware.org/?probe=86e1d115b9) | Mar 15, 2020 |
| HP            | ProBook 4720s               | [a32d5c092c](https://linux-hardware.org/?probe=a32d5c092c) | Mar 15, 2020 |
| Toshiba       | Satellite L40               | [467c320928](https://linux-hardware.org/?probe=467c320928) | Mar 11, 2020 |
| Lenovo        | ThinkPad Edge E530 3259C... | [7e0acb9bed](https://linux-hardware.org/?probe=7e0acb9bed) | Mar 06, 2020 |
| HP            | ProBook 4720s               | [823553cfbd](https://linux-hardware.org/?probe=823553cfbd) | Mar 03, 2020 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [de25ec2891](https://linux-hardware.org/?probe=de25ec2891) | Feb 28, 2020 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [b333f7015a](https://linux-hardware.org/?probe=b333f7015a) | Feb 28, 2020 |
| HP            | ZBook 14u G5                | [03871e6b83](https://linux-hardware.org/?probe=03871e6b83) | Feb 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [0937d2a588](https://linux-hardware.org/?probe=0937d2a588) | Feb 20, 2020 |
| Dell          | Inspiron 3542               | [5e00c1766c](https://linux-hardware.org/?probe=5e00c1766c) | Feb 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [7f8aef2f6b](https://linux-hardware.org/?probe=7f8aef2f6b) | Feb 19, 2020 |
| MSI           | MS-1738                     | [0cbf139f1d](https://linux-hardware.org/?probe=0cbf139f1d) | Feb 11, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [7773f702ab](https://linux-hardware.org/?probe=7773f702ab) | Feb 10, 2020 |
| ASUSTek       | UX331UA                     | [62bdf0c233](https://linux-hardware.org/?probe=62bdf0c233) | Feb 10, 2020 |
| HP            | EliteBook 850 G5            | [fc9101307a](https://linux-hardware.org/?probe=fc9101307a) | Feb 07, 2020 |
| Dell          | Precision 7530              | [bb59dc45d2](https://linux-hardware.org/?probe=bb59dc45d2) | Feb 06, 2020 |
| MSI           | MS-1738                     | [1f7c3ccb75](https://linux-hardware.org/?probe=1f7c3ccb75) | Jan 29, 2020 |
| Lenovo        | IdeaPad Y500 9541           | [1435e47012](https://linux-hardware.org/?probe=1435e47012) | Jan 27, 2020 |
| ASUSTek       | X555UJ                      | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| HP            | EliteBook Folio 1040 G3     | [44ad91d4da](https://linux-hardware.org/?probe=44ad91d4da) | Jan 24, 2020 |
| Dell          | Latitude 5590               | [206a367d42](https://linux-hardware.org/?probe=206a367d42) | Jan 24, 2020 |
| HP            | EliteBook 850 G5            | [bcc6422548](https://linux-hardware.org/?probe=bcc6422548) | Jan 18, 2020 |
| Samsung       | N150/N210/N220              | [91718b856a](https://linux-hardware.org/?probe=91718b856a) | Jan 16, 2020 |
| HP            | EliteBook 840 G6            | [79936056dd](https://linux-hardware.org/?probe=79936056dd) | Jan 16, 2020 |
| HP            | Laptop 15-bw0xx             | [2aff706ca4](https://linux-hardware.org/?probe=2aff706ca4) | Jan 15, 2020 |
| Lenovo        | ThinkPad T430s 2356W1L      | [42b6186198](https://linux-hardware.org/?probe=42b6186198) | Jan 13, 2020 |
| HP            | ProBook 4710s               | [d6124de12a](https://linux-hardware.org/?probe=d6124de12a) | Jan 01, 2020 |
| HP            | ProBook 4710s               | [7eb0b2437d](https://linux-hardware.org/?probe=7eb0b2437d) | Jan 01, 2020 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [14015a6cde](https://linux-hardware.org/?probe=14015a6cde) | Dec 24, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | [c7b13e4ba2](https://linux-hardware.org/?probe=c7b13e4ba2) | Dec 23, 2019 |
| Dell          | Inspiron 1545               | [adaa5b6d54](https://linux-hardware.org/?probe=adaa5b6d54) | Dec 10, 2019 |
| Lenovo        | ThinkPad P51 20HH001RMD     | [7ab81dbd28](https://linux-hardware.org/?probe=7ab81dbd28) | Nov 30, 2019 |
| HP            | Pavilion dv6                | [fdc46ce1cd](https://linux-hardware.org/?probe=fdc46ce1cd) | Nov 26, 2019 |
| Lenovo        | ThinkPad S5-S540 20B3005... | [e84f3912be](https://linux-hardware.org/?probe=e84f3912be) | Nov 10, 2019 |
| eMachines     | E725                        | [599a7f6c54](https://linux-hardware.org/?probe=599a7f6c54) | Nov 03, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [9607f525a8](https://linux-hardware.org/?probe=9607f525a8) | Oct 29, 2019 |
| Apple         | MacBookPro9,2               | [99702307ab](https://linux-hardware.org/?probe=99702307ab) | Oct 21, 2019 |
| HP            | OMEN by Laptop              | [90ef6677b7](https://linux-hardware.org/?probe=90ef6677b7) | Oct 15, 2019 |
| Dell          | XPS 15 9570                 | [6cdbd762c1](https://linux-hardware.org/?probe=6cdbd762c1) | Oct 13, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [acd2d7dfad](https://linux-hardware.org/?probe=acd2d7dfad) | Oct 12, 2019 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [98855b1409](https://linux-hardware.org/?probe=98855b1409) | Oct 09, 2019 |
| Lenovo        | ThinkPad E480 20KN001NMX    | [4f055c0cf5](https://linux-hardware.org/?probe=4f055c0cf5) | Oct 08, 2019 |
| Dell          | Latitude 7480               | [b6627cc113](https://linux-hardware.org/?probe=b6627cc113) | Oct 08, 2019 |
| Lenovo        | ThinkPad P51 20HH001RMD     | [14671c29e5](https://linux-hardware.org/?probe=14671c29e5) | Oct 07, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [402c3e5e59](https://linux-hardware.org/?probe=402c3e5e59) | Oct 05, 2019 |
| Acer          | Aspire ES1-311              | [d9d6c865ef](https://linux-hardware.org/?probe=d9d6c865ef) | Sep 26, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [98ed6c18c5](https://linux-hardware.org/?probe=98ed6c18c5) | Sep 21, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [fd17c2893e](https://linux-hardware.org/?probe=fd17c2893e) | Sep 19, 2019 |
| HP            | EliteBook 850 G5            | [b355ce68ad](https://linux-hardware.org/?probe=b355ce68ad) | Sep 15, 2019 |
| Lenovo        | ThinkPad T430s 2356W1L      | [01545dc8fb](https://linux-hardware.org/?probe=01545dc8fb) | Sep 11, 2019 |
| HP            | EliteBook 850 G5            | [f0c27f436e](https://linux-hardware.org/?probe=f0c27f436e) | Sep 10, 2019 |
| HP            | Pavilion dv2                | [b9b30ae45c](https://linux-hardware.org/?probe=b9b30ae45c) | Sep 10, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [121e1a0f7a](https://linux-hardware.org/?probe=121e1a0f7a) | Aug 27, 2019 |
| Samsung       | 940X3G/930X3G               | [73a88e2c94](https://linux-hardware.org/?probe=73a88e2c94) | Aug 23, 2019 |
| Dell          | XPS 15 9570                 | [85fc7259b6](https://linux-hardware.org/?probe=85fc7259b6) | Aug 15, 2019 |
| Fujitsu       | LIFEBOOK U772               | [0f7c7fe35a](https://linux-hardware.org/?probe=0f7c7fe35a) | Aug 15, 2019 |
| HP            | Pavilion x2 Detachable      | [923cbd5735](https://linux-hardware.org/?probe=923cbd5735) | Aug 06, 2019 |
| Lenovo        | IdeaPad Y700-14ISK 80NU     | [0aaee3cc4f](https://linux-hardware.org/?probe=0aaee3cc4f) | Aug 02, 2019 |
| Lenovo        | ThinkPad T430s 2356W1L      | [61e8e08336](https://linux-hardware.org/?probe=61e8e08336) | Jul 31, 2019 |
| Lenovo        | ThinkPad T430s 2356W1L      | [41e069ab47](https://linux-hardware.org/?probe=41e069ab47) | Jul 31, 2019 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [3e47232411](https://linux-hardware.org/?probe=3e47232411) | Jul 26, 2019 |
| Dell          | Latitude E7470              | [90e9f8dfad](https://linux-hardware.org/?probe=90e9f8dfad) | Jul 26, 2019 |
| Lenovo        | ThinkPad S430 33642NG       | [7c0cd24986](https://linux-hardware.org/?probe=7c0cd24986) | Jul 25, 2019 |
| HP            | Pavilion dv9700             | [bfebe8555b](https://linux-hardware.org/?probe=bfebe8555b) | Jul 25, 2019 |
| HP            | Compaq CQ58                 | [0c02dfd17b](https://linux-hardware.org/?probe=0c02dfd17b) | Jul 21, 2019 |
| HP            | Compaq nx7400 (RU429ET#A... | [37b1d8aa7d](https://linux-hardware.org/?probe=37b1d8aa7d) | Jul 19, 2019 |
| Lenovo        | G580 2189                   | [f3d7e4e13d](https://linux-hardware.org/?probe=f3d7e4e13d) | Jul 19, 2019 |
| Lenovo        | G580 2189                   | [a75a2e9dae](https://linux-hardware.org/?probe=a75a2e9dae) | Jul 19, 2019 |
| HP            | Pavilion dv7                | [dda054b15d](https://linux-hardware.org/?probe=dda054b15d) | Jul 15, 2019 |
| ASUSTek       | 900                         | [db34e96f60](https://linux-hardware.org/?probe=db34e96f60) | Jul 06, 2019 |
| HP            | EliteBook 8740w (SK430UP... | [5bc72880ea](https://linux-hardware.org/?probe=5bc72880ea) | Jun 15, 2019 |
| HP            | EliteBook 8740w (SK430UP... | [25522cad27](https://linux-hardware.org/?probe=25522cad27) | Jun 13, 2019 |
| HP            | EliteBook 8740w (SK430UP... | [4ed2a6de0d](https://linux-hardware.org/?probe=4ed2a6de0d) | Jun 08, 2019 |
| Acer          | Nitro AN515-42              | [5d176e185c](https://linux-hardware.org/?probe=5d176e185c) | Jun 06, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [945dd2aedf](https://linux-hardware.org/?probe=945dd2aedf) | Jun 04, 2019 |
| ASUSTek       | X55SV                       | [4137ac8f54](https://linux-hardware.org/?probe=4137ac8f54) | May 31, 2019 |
| HP            | EliteBook 8440p             | [e1a6c35a36](https://linux-hardware.org/?probe=e1a6c35a36) | May 27, 2019 |
| HP            | EliteBook 8440p             | [cfcb01f30c](https://linux-hardware.org/?probe=cfcb01f30c) | May 27, 2019 |
| HP            | EliteBook 8760w             | [13780fae80](https://linux-hardware.org/?probe=13780fae80) | May 25, 2019 |
| HP            | EliteBook 8760w             | [93d7fd3de9](https://linux-hardware.org/?probe=93d7fd3de9) | May 25, 2019 |
| ASUSTek       | UX331UA                     | [5b86d530bf](https://linux-hardware.org/?probe=5b86d530bf) | May 07, 2019 |
| MSI           | GV62 8RE                    | [4c00b9e457](https://linux-hardware.org/?probe=4c00b9e457) | May 05, 2019 |
| Lenovo        | Unknown                     | [fd7bf6fb44](https://linux-hardware.org/?probe=fd7bf6fb44) | May 04, 2019 |
| Lenovo        | Unknown                     | [abcb8328f0](https://linux-hardware.org/?probe=abcb8328f0) | May 03, 2019 |
| ASUSTek       | UX331UA                     | [4e74668f09](https://linux-hardware.org/?probe=4e74668f09) | Apr 30, 2019 |
| AMI           | Cherry Trail CR             | [c2adff61c1](https://linux-hardware.org/?probe=c2adff61c1) | Apr 16, 2019 |
| ASUSTek       | X550JX                      | [961517bceb](https://linux-hardware.org/?probe=961517bceb) | Apr 08, 2019 |
| Acer          | TravelMate 5720             | [3c724ba732](https://linux-hardware.org/?probe=3c724ba732) | Apr 03, 2019 |
| Acer          | TravelMate 5720             | [19a257005b](https://linux-hardware.org/?probe=19a257005b) | Apr 02, 2019 |
| Lenovo        | ThinkPad W500 406333G       | [16f12d3bc8](https://linux-hardware.org/?probe=16f12d3bc8) | Apr 01, 2019 |
| Lenovo        | ThinkPad W500 406333G       | [28142e5518](https://linux-hardware.org/?probe=28142e5518) | Apr 01, 2019 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [e8fd67417e](https://linux-hardware.org/?probe=e8fd67417e) | Mar 29, 2019 |
| ASUSTek       | S551LN                      | [2c007f8b6c](https://linux-hardware.org/?probe=2c007f8b6c) | Mar 23, 2019 |
| Lenovo        | ThinkPad X201 3680HC3       | [6f637899c4](https://linux-hardware.org/?probe=6f637899c4) | Mar 12, 2019 |
| HP            | Laptop 14-ck0xxx            | [620383c937](https://linux-hardware.org/?probe=620383c937) | Mar 07, 2019 |
| Acer          | Aspire 7220                 | [918907fa0a](https://linux-hardware.org/?probe=918907fa0a) | Mar 06, 2019 |
| ASUSTek       | N750JK                      | [29d535d30f](https://linux-hardware.org/?probe=29d535d30f) | Feb 15, 2019 |
| ASUSTek       | N750JK                      | [0a21e6bf0f](https://linux-hardware.org/?probe=0a21e6bf0f) | Feb 13, 2019 |
| Lenovo        | ThinkPad X201 3680HC3       | [f5cf28dd23](https://linux-hardware.org/?probe=f5cf28dd23) | Jan 25, 2019 |
| ASUSTek       | N750JK                      | [e706aadaf7](https://linux-hardware.org/?probe=e706aadaf7) | Jan 16, 2019 |
| ASUSTek       | N750JK                      | [8e8a651043](https://linux-hardware.org/?probe=8e8a651043) | Jan 12, 2019 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [d87952f0b8](https://linux-hardware.org/?probe=d87952f0b8) | Dec 20, 2018 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [7f746478de](https://linux-hardware.org/?probe=7f746478de) | Dec 20, 2018 |
| Lenovo        | ThinkPad T530 24295XG       | [65d4845db2](https://linux-hardware.org/?probe=65d4845db2) | Dec 10, 2018 |
| Lenovo        | ThinkPad T570 20H9001EGE    | [904c160172](https://linux-hardware.org/?probe=904c160172) | Nov 25, 2018 |
| Lenovo        | ThinkPad T570 20H9001EGE    | [e71b0059ee](https://linux-hardware.org/?probe=e71b0059ee) | Nov 25, 2018 |
| Lenovo        | ThinkPad T530 24292UG       | [dc38e86871](https://linux-hardware.org/?probe=dc38e86871) | Jun 29, 2018 |
| Lenovo        | ThinkPad T530 24292UG       | [f521f460e8](https://linux-hardware.org/?probe=f521f460e8) | Jun 29, 2018 |
| Acer          | Aspire ES1-111M             | [782a0a4926](https://linux-hardware.org/?probe=782a0a4926) | Mar 25, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Denmark/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 91        | 14.13%  |
| Ubuntu 18.04       | 48        | 7.45%   |
| Ubuntu 22.04       | 42        | 6.52%   |
| Pop!_OS 22.04      | 19        | 2.95%   |
| Arch Rolling       | 17        | 2.64%   |
| Ubuntu 21.10       | 15        | 2.33%   |
| Fedora 38          | 15        | 2.33%   |
| OpenMandriva 4.2   | 12        | 1.86%   |
| Fedora 34          | 12        | 1.86%   |
| Arch               | 11        | 1.71%   |
| Debian 11          | 10        | 1.55%   |
| Manjaro            | 9         | 1.4%    |
| Fedora 36          | 9         | 1.4%    |
| Ubuntu 19.04       | 8         | 1.24%   |
| Pop!_OS 20.04      | 8         | 1.24%   |
| OpenMandriva 23.03 | 8         | 1.24%   |
| Linux Mint 21.2    | 8         | 1.24%   |
| Zorin 15           | 7         | 1.09%   |
| Pop!_OS 21.04      | 7         | 1.09%   |
| Linux Mint 21.1    | 7         | 1.09%   |
| Linux Mint 20.3    | 7         | 1.09%   |
| Linux Mint 20.2    | 7         | 1.09%   |
| KDE neon 20.04     | 7         | 1.09%   |
| Fedora 32          | 7         | 1.09%   |
| Debian 10          | 7         | 1.09%   |
| Zorin 16           | 6         | 0.93%   |
| Ubuntu 22.10       | 6         | 0.93%   |
| Ubuntu 20.10       | 6         | 0.93%   |
| Pop!_OS 21.10      | 6         | 0.93%   |
| OpenMandriva 4.3   | 6         | 0.93%   |
| Linux Mint 21      | 6         | 0.93%   |
| Linux Mint 20.1    | 6         | 0.93%   |
| Fedora 37          | 6         | 0.93%   |
| Fedora 33          | 6         | 0.93%   |
| Xubuntu 20.04      | 5         | 0.78%   |
| Ubuntu 19.10       | 5         | 0.78%   |
| Ubuntu 18.10       | 5         | 0.78%   |
| Linux Mint 20      | 5         | 0.78%   |
| Fedora 35          | 5         | 0.78%   |
| ArcoLinux Rolling  | 5         | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 215       | 35.89%  |
| Fedora       | 59        | 9.85%   |
| Linux Mint   | 53        | 8.85%   |
| Pop!_OS      | 43        | 7.18%   |
| OpenMandriva | 32        | 5.34%   |
| Arch         | 27        | 4.51%   |
| Manjaro      | 22        | 3.67%   |
| Debian       | 21        | 3.51%   |
| Zorin        | 15        | 2.5%    |
| Kubuntu      | 13        | 2.17%   |
| Xubuntu      | 11        | 1.84%   |
| KDE neon     | 11        | 1.84%   |
| SteamOS      | 6         | 1%      |
| ArcoLinux    | 6         | 1%      |
| Ubuntu Unity | 5         | 0.83%   |
| ROSA         | 5         | 0.83%   |
| Kali         | 5         | 0.83%   |
| EndeavourOS  | 5         | 0.83%   |
| Elementary   | 5         | 0.83%   |
| Void Linux   | 4         | 0.67%   |
| Ubuntu MATE  | 4         | 0.67%   |
| Parrot       | 4         | 0.67%   |
| openSUSE     | 4         | 0.67%   |
| LMDE         | 3         | 0.5%    |
| Garuda Linux | 3         | 0.5%    |
| Clear Linux  | 3         | 0.5%    |
| Xero         | 2         | 0.33%   |
| Lubuntu      | 2         | 0.33%   |
| Endless      | 2         | 0.33%   |
| antiX        | 2         | 0.33%   |
| TUXEDO OS    | 1         | 0.17%   |
| NixOS        | 1         | 0.17%   |
| LinuxFX      | 1         | 0.17%   |
| Guix         | 1         | 0.17%   |
| Gentoo       | 1         | 0.17%   |
| GalliumOS    | 1         | 0.17%   |
| BlackPanther | 1         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 14        | 1.98%   |
| 5.10.14-desktop-1omv4002 | 12        | 1.69%   |
| 6.2.6-desktop-1omv2390   | 8         | 1.13%   |
| 5.16.7-desktop-1omv4003  | 7         | 0.99%   |
| 5.15.0-56-generic        | 7         | 0.99%   |
| 5.4.0-52-generic         | 6         | 0.85%   |
| 5.4.0-48-generic         | 6         | 0.85%   |
| 5.4.0-26-generic         | 6         | 0.85%   |
| 6.2.6-76060206-generic   | 5         | 0.71%   |
| 5.4.0-7634-generic       | 5         | 0.71%   |
| 5.4.0-47-generic         | 5         | 0.71%   |
| 5.19.0-35-generic        | 5         | 0.71%   |
| 5.15.0-53-generic        | 5         | 0.71%   |
| 5.15.0-52-generic        | 5         | 0.71%   |
| 5.11.0-40-generic        | 5         | 0.71%   |
| 6.4.6-76060406-generic   | 4         | 0.56%   |
| 6.2.0-26-generic         | 4         | 0.56%   |
| 5.4.0-58-generic         | 4         | 0.56%   |
| 5.4.0-40-generic         | 4         | 0.56%   |
| 5.3.0-40-generic         | 4         | 0.56%   |
| 5.19.0-76051900-generic  | 4         | 0.56%   |
| 5.15.0-46-generic        | 4         | 0.56%   |
| 5.15.0-43-generic        | 4         | 0.56%   |
| 5.11.0-41-generic        | 4         | 0.56%   |
| 5.11.0-27-generic        | 4         | 0.56%   |
| 5.0.0-23-generic         | 4         | 0.56%   |
| 4.15.0-55-generic        | 4         | 0.56%   |
| 5.8.15-301.fc33.x86_64   | 3         | 0.42%   |
| 5.8.0-59-generic         | 3         | 0.42%   |
| 5.8.0-50-generic         | 3         | 0.42%   |
| 5.8.0-45-generic         | 3         | 0.42%   |
| 5.8.0-29-generic         | 3         | 0.42%   |
| 5.4.0-96-generic         | 3         | 0.42%   |
| 5.4.0-91-generic         | 3         | 0.42%   |
| 5.4.0-81-generic         | 3         | 0.42%   |
| 5.4.0-77-generic         | 3         | 0.42%   |
| 5.4.0-62-generic         | 3         | 0.42%   |
| 5.4.0-54-generic         | 3         | 0.42%   |
| 5.4.0-29-generic         | 3         | 0.42%   |
| 5.3.0-28-generic         | 3         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 93        | 13.98%  |
| 5.15.0  | 63        | 9.47%   |
| 5.11.0  | 36        | 5.41%   |
| 4.15.0  | 36        | 5.41%   |
| 5.13.0  | 30        | 4.51%   |
| 5.8.0   | 28        | 4.21%   |
| 5.19.0  | 28        | 4.21%   |
| 5.3.0   | 18        | 2.71%   |
| 5.0.0   | 17        | 2.56%   |
| 6.2.0   | 16        | 2.41%   |
| 6.2.6   | 15        | 2.26%   |
| 4.18.0  | 13        | 1.95%   |
| 5.10.14 | 12        | 1.8%    |
| 5.10.0  | 12        | 1.8%    |
| 5.16.7  | 7         | 1.05%   |
| 4.19.0  | 7         | 1.05%   |
| 6.1.0   | 6         | 0.9%    |
| 6.4.6   | 5         | 0.75%   |
| 6.5.0   | 4         | 0.6%    |
| 6.1.1   | 4         | 0.6%    |
| 5.7.15  | 4         | 0.6%    |
| 6.5.9   | 3         | 0.45%   |
| 6.5.6   | 3         | 0.45%   |
| 6.5.5   | 3         | 0.45%   |
| 6.3.8   | 3         | 0.45%   |
| 6.0.10  | 3         | 0.45%   |
| 5.9.0   | 3         | 0.45%   |
| 5.8.15  | 3         | 0.45%   |
| 5.4.18  | 3         | 0.45%   |
| 5.19.13 | 3         | 0.45%   |
| 5.16.0  | 3         | 0.45%   |
| 5.14.0  | 3         | 0.45%   |
| 5.13.12 | 3         | 0.45%   |
| 6.6.7   | 2         | 0.3%    |
| 6.6.2   | 2         | 0.3%    |
| 6.5.8   | 2         | 0.3%    |
| 6.5.4   | 2         | 0.3%    |
| 6.5.3   | 2         | 0.3%    |
| 6.4.8   | 2         | 0.3%    |
| 6.2.14  | 2         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 102       | 15.53%  |
| 5.15    | 83        | 12.63%  |
| 5.19    | 40        | 6.09%   |
| 5.11    | 40        | 6.09%   |
| 5.8     | 39        | 5.94%   |
| 4.15    | 36        | 5.48%   |
| 6.2     | 35        | 5.33%   |
| 5.13    | 35        | 5.33%   |
| 5.10    | 31        | 4.72%   |
| 6.1     | 21        | 3.2%    |
| 5.16    | 20        | 3.04%   |
| 6.5     | 19        | 2.89%   |
| 5.3     | 18        | 2.74%   |
| 5.0     | 18        | 2.74%   |
| 4.18    | 14        | 2.13%   |
| 5.14    | 12        | 1.83%   |
| 6.4     | 11        | 1.67%   |
| 6.0     | 11        | 1.67%   |
| 5.9     | 9         | 1.37%   |
| 4.19    | 8         | 1.22%   |
| 5.18    | 7         | 1.07%   |
| 6.3     | 6         | 0.91%   |
| 5.7     | 6         | 0.91%   |
| 5.6     | 6         | 0.91%   |
| 5.17    | 6         | 0.91%   |
| 6.6     | 5         | 0.76%   |
| 5.12    | 5         | 0.76%   |
| 5.1     | 3         | 0.46%   |
| 4.9     | 2         | 0.3%    |
| 4.4     | 2         | 0.3%    |
| 4.14    | 2         | 0.3%    |
| 5.2     | 1         | 0.15%   |
| 4.16    | 1         | 0.15%   |
| 4.13    | 1         | 0.15%   |
| 4.10    | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 559       | 96.55%  |
| i686   | 20        | 3.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 299       | 49.34%  |
| KDE5            | 94        | 15.51%  |
| Unknown         | 72        | 11.88%  |
| XFCE            | 41        | 6.77%   |
| X-Cinnamon      | 41        | 6.77%   |
| MATE            | 15        | 2.48%   |
| KDE             | 13        | 2.15%   |
| i3              | 7         | 1.16%   |
| Unity           | 5         | 0.83%   |
| Pantheon        | 4         | 0.66%   |
| LXQt            | 4         | 0.66%   |
| sway            | 2         | 0.33%   |
| icewm           | 2         | 0.33%   |
| GNOME Flashback | 2         | 0.33%   |
| Cinnamon        | 2         | 0.33%   |
| qtile-default   | 1         | 0.17%   |
| LeftWM          | 1         | 0.17%   |
| awesome         | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 427       | 70.7%   |
| Wayland | 135       | 22.35%  |
| Unknown | 37        | 6.13%   |
| Tty     | 5         | 0.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 320       | 53.51%  |
| GDM3    | 79        | 13.21%  |
| GDM     | 73        | 12.21%  |
| SDDM    | 69        | 11.54%  |
| LightDM | 41        | 6.86%   |
| TDM     | 12        | 2.01%   |
| SLIMSKI | 1         | 0.17%   |
| LY-DM   | 1         | 0.17%   |
| Ly      | 1         | 0.17%   |
| GREETD  | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 213       | 35.5%   |
| da_DK   | 177       | 29.5%   |
| en_DK   | 75        | 12.5%   |
| Unknown | 64        | 10.67%  |
| en_GB   | 34        | 5.67%   |
| de_DE   | 12        | 2%      |
| C       | 10        | 1.67%   |
| pl_PL   | 3         | 0.5%    |
| en_AG   | 2         | 0.33%   |
| zh_TW   | 1         | 0.17%   |
| pt_BR   | 1         | 0.17%   |
| nl_NL   | 1         | 0.17%   |
| it_IT   | 1         | 0.17%   |
| is_IS   | 1         | 0.17%   |
| fr_FR   | 1         | 0.17%   |
| es_ES   | 1         | 0.17%   |
| en_CA   | 1         | 0.17%   |
| en_AU   | 1         | 0.17%   |
| de_CH   | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 304       | 51.53%  |
| BIOS | 286       | 48.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 440       | 73.83%  |
| Btrfs   | 81        | 13.59%  |
| Overlay | 28        | 4.7%    |
| Unknown | 20        | 3.36%   |
| Tmpfs   | 16        | 2.68%   |
| Zfs     | 7         | 1.17%   |
| Ext2    | 3         | 0.5%    |
| Xfs     | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 337       | 56.73%  |
| GPT     | 209       | 35.19%  |
| MBR     | 48        | 8.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 524       | 89.27%  |
| Yes       | 63        | 10.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 465       | 79.22%  |
| Yes       | 122       | 20.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 218       | 37.72%  |
| Hewlett-Packard     | 93        | 16.09%  |
| Dell                | 55        | 9.52%   |
| ASUSTek Computer    | 54        | 9.34%   |
| Acer                | 44        | 7.61%   |
| Apple               | 21        | 3.63%   |
| Toshiba             | 11        | 1.9%    |
| MSI                 | 11        | 1.9%    |
| Notebook            | 9         | 1.56%   |
| Google              | 6         | 1.04%   |
| Valve               | 5         | 0.87%   |
| HUAWEI              | 5         | 0.87%   |
| Samsung Electronics | 4         | 0.69%   |
| Medion              | 4         | 0.69%   |
| Razer               | 3         | 0.52%   |
| Unknown             | 3         | 0.52%   |
| TUXEDO              | 2         | 0.35%   |
| Timi                | 2         | 0.35%   |
| Sony                | 2         | 0.35%   |
| Quanta              | 2         | 0.35%   |
| Packard Bell        | 2         | 0.35%   |
| GPD                 | 2         | 0.35%   |
| Fujitsu             | 2         | 0.35%   |
| eMachines           | 2         | 0.35%   |
| AMI                 | 2         | 0.35%   |
| System76            | 1         | 0.17%   |
| Standard            | 1         | 0.17%   |
| SLIMBOOK            | 1         | 0.17%   |
| Purism              | 1         | 0.17%   |
| LG Electronics      | 1         | 0.17%   |
| LAMINA              | 1         | 0.17%   |
| Komplett            | 1         | 0.17%   |
| IBM                 | 1         | 0.17%   |
| Gigabyte Technology | 1         | 0.17%   |
| Fujitsu Siemens     | 1         | 0.17%   |
| Framework           | 1         | 0.17%   |
| DukaPC              | 1         | 0.17%   |
| Dixonsxp            | 1         | 0.17%   |
| Alienware           | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 10        | 1.73%   |
| Valve Jupiter                         | 5         | 0.87%   |
| HP Pavilion dv7                       | 5         | 0.87%   |
| Dell XPS 15 9570                      | 4         | 0.69%   |
| Dell XPS 13 9370                      | 4         | 0.69%   |
| HP Pavilion g7                        | 3         | 0.52%   |
| HP OMEN by Laptop                     | 3         | 0.52%   |
| HP Notebook                           | 3         | 0.52%   |
| HP EliteBook 820 G3                   | 3         | 0.52%   |
| Dell Latitude 7480                    | 3         | 0.52%   |
| ASUS ROG Zephyrus G14 GA402RK_GA402RK | 3         | 0.52%   |
| Apple MacBookPro9,2                   | 3         | 0.52%   |
| Apple MacBookPro5,5                   | 3         | 0.52%   |
| Toshiba Satellite P850                | 2         | 0.35%   |
| Toshiba Satellite L40                 | 2         | 0.35%   |
| Quanta MW1/HW1                        | 2         | 0.35%   |
| Notebook W54_55SU1,SUW                | 2         | 0.35%   |
| Lenovo V110-15IAP 80TG                | 2         | 0.35%   |
| Lenovo ThinkPad T530 24295L4          | 2         | 0.35%   |
| Lenovo ThinkBook 15 G2 ARE 20VG       | 2         | 0.35%   |
| Lenovo Legion 5 15ACH6H 82JU          | 2         | 0.35%   |
| Lenovo IdeaPad Y700-15ISK 80NV        | 2         | 0.35%   |
| Lenovo IdeaPad Y500 9541              | 2         | 0.35%   |
| Lenovo IdeaPad S130-14IGM 81J2        | 2         | 0.35%   |
| Lenovo IdeaPad 310-15IKB 80TV         | 2         | 0.35%   |
| Lenovo G505 20240                     | 2         | 0.35%   |
| Lenovo E31-80 80MX                    | 2         | 0.35%   |
| HP ProBook 650 G2                     | 2         | 0.35%   |
| HP ProBook 650 G1                     | 2         | 0.35%   |
| HP Pavilion Notebook                  | 2         | 0.35%   |
| HP Pavilion 15                        | 2         | 0.35%   |
| HP Laptop 15s-eq2xxx                  | 2         | 0.35%   |
| HP Laptop 15-bw0xx                    | 2         | 0.35%   |
| HP EliteBook 845 G7 Notebook PC       | 2         | 0.35%   |
| HP EliteBook 840 G6                   | 2         | 0.35%   |
| HP EliteBook 840 G1                   | 2         | 0.35%   |
| HP Compaq Presario CQ71               | 2         | 0.35%   |
| eMachines E725                        | 2         | 0.35%   |
| Dell XPS 15 9560                      | 2         | 0.35%   |
| Dell XPS 15 7590                      | 2         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 156       | 26.99%  |
| Acer Aspire           | 30        | 5.19%   |
| HP EliteBook          | 24        | 4.15%   |
| HP Pavilion           | 23        | 3.98%   |
| Dell Latitude         | 23        | 3.98%   |
| Lenovo IdeaPad        | 21        | 3.63%   |
| Dell XPS              | 16        | 2.77%   |
| HP ProBook            | 12        | 2.08%   |
| Toshiba Satellite     | 11        | 1.9%    |
| ASUS ROG              | 11        | 1.9%    |
| HP Laptop             | 10        | 1.73%   |
| Unknown               | 10        | 1.73%   |
| ASUS ZenBook          | 8         | 1.38%   |
| Lenovo Legion         | 7         | 1.21%   |
| Dell Inspiron         | 7         | 1.21%   |
| HP Compaq             | 6         | 1.04%   |
| Valve Jupiter         | 5         | 0.87%   |
| Lenovo Yoga           | 5         | 0.87%   |
| Lenovo ThinkBook      | 5         | 0.87%   |
| Dell Precision        | 5         | 0.87%   |
| ASUS VivoBook         | 5         | 0.87%   |
| Acer Swift            | 5         | 0.87%   |
| HP OMEN               | 4         | 0.69%   |
| Razer Blade           | 3         | 0.52%   |
| HP ZBook              | 3         | 0.52%   |
| HP Notebook           | 3         | 0.52%   |
| ASUS Strix            | 3         | 0.52%   |
| Apple MacBookPro9     | 3         | 0.52%   |
| Apple MacBookPro5     | 3         | 0.52%   |
| Acer Nitro            | 3         | 0.52%   |
| Quanta MW1            | 2         | 0.35%   |
| Packard Bell EasyNote | 2         | 0.35%   |
| Notebook W54          | 2         | 0.35%   |
| MSI GV62              | 2         | 0.35%   |
| Lenovo V110-15IAP     | 2         | 0.35%   |
| Lenovo G505           | 2         | 0.35%   |
| Lenovo E31-80         | 2         | 0.35%   |
| Lenovo 3000           | 2         | 0.35%   |
| Fujitsu LIFEBOOK      | 2         | 0.35%   |
| eMachines E725        | 2         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 51        | 8.82%   |
| 2013    | 51        | 8.82%   |
| 2019    | 49        | 8.48%   |
| 2021    | 45        | 7.79%   |
| 2020    | 44        | 7.61%   |
| 2015    | 43        | 7.44%   |
| 2017    | 42        | 7.27%   |
| 2012    | 40        | 6.92%   |
| 2011    | 40        | 6.92%   |
| 2016    | 35        | 6.06%   |
| 2014    | 26        | 4.5%    |
| 2010    | 22        | 3.81%   |
| 2022    | 21        | 3.63%   |
| 2009    | 21        | 3.63%   |
| 2007    | 19        | 3.29%   |
| 2008    | 15        | 2.6%    |
| 2023    | 7         | 1.21%   |
| 2006    | 5         | 0.87%   |
| 2003    | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 578       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 513       | 87.99%  |
| Enabled  | 70        | 12.01%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 571       | 98.79%  |
| Yes  | 7         | 1.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 177       | 30%     |
| 8.01-16.0   | 119       | 20.17%  |
| 16.01-24.0  | 101       | 17.12%  |
| 3.01-4.0    | 91        | 15.42%  |
| 32.01-64.0  | 51        | 8.64%   |
| 1.01-2.0    | 16        | 2.71%   |
| 24.01-32.0  | 13        | 2.2%    |
| 2.01-3.0    | 10        | 1.69%   |
| 64.01-256.0 | 9         | 1.53%   |
| 0.51-1.0    | 2         | 0.34%   |
| 0.01-0.5    | 1         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 192       | 30%     |
| 2.01-3.0   | 187       | 29.22%  |
| 4.01-8.0   | 116       | 18.13%  |
| 3.01-4.0   | 90        | 14.06%  |
| 0.51-1.0   | 26        | 4.06%   |
| 8.01-16.0  | 18        | 2.81%   |
| 0.01-0.5   | 5         | 0.78%   |
| 24.01-32.0 | 3         | 0.47%   |
| 16.01-24.0 | 2         | 0.31%   |
| 32.01-64.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 464       | 78.51%  |
| 2      | 111       | 18.78%  |
| 3      | 12        | 2.03%   |
| 0      | 3         | 0.51%   |
| 4      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 397       | 67.86%  |
| Yes       | 188       | 32.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 484       | 83.3%   |
| No        | 97        | 16.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 571       | 98.79%  |
| No        | 7         | 1.21%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 482       | 81.83%  |
| No        | 107       | 18.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Denmark | 578       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Copenhagen            | 138       | 22.33%  |
| Frederiksberg         | 41        | 6.63%   |
| Odense                | 35        | 5.66%   |
| Aarhus                | 21        | 3.4%    |
| Bronshoj              | 17        | 2.75%   |
| Silkeborg             | 13        | 2.1%    |
| Aalborg               | 13        | 2.1%    |
| Slagelse              | 11        | 1.78%   |
| Valby                 | 10        | 1.62%   |
| Holstebro             | 10        | 1.62%   |
| Esbjerg               | 10        | 1.62%   |
| Norresundby           | 9         | 1.46%   |
| Kongens Lyngby        | 9         | 1.46%   |
| Glostrup Municipality | 8         | 1.29%   |
| Skanderborg           | 7         | 1.13%   |
| Roskilde              | 7         | 1.13%   |
| Gentofte Municipality | 7         | 1.13%   |
| Aabenraa              | 7         | 1.13%   |
| Taastrup              | 6         | 0.97%   |
| Naestved              | 6         | 0.97%   |
| Hvidovre              | 6         | 0.97%   |
| Horsens               | 6         | 0.97%   |
| Vanlose               | 5         | 0.81%   |
| Nyborg                | 5         | 0.81%   |
| Kastrup               | 5         | 0.81%   |
| Hojbjerg              | 5         | 0.81%   |
| Herlev                | 5         | 0.81%   |
| Elsinore              | 5         | 0.81%   |
| Viby J                | 4         | 0.65%   |
| Viborg                | 4         | 0.65%   |
| Thisted               | 4         | 0.65%   |
| Skive                 | 4         | 0.65%   |
| Sindal                | 4         | 0.65%   |
| Risskov               | 4         | 0.65%   |
| Køge                 | 4         | 0.65%   |
| Kolding               | 4         | 0.65%   |
| Brønderslev          | 4         | 0.65%   |
| Vejle                 | 3         | 0.49%   |
| Vaerlose              | 3         | 0.49%   |
| Sønderborg           | 3         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 168       | 227    | 24.49%  |
| WDC                         | 68        | 86     | 9.91%   |
| Seagate                     | 51        | 59     | 7.43%   |
| Kingston                    | 47        | 62     | 6.85%   |
| Toshiba                     | 45        | 64     | 6.56%   |
| SK hynix                    | 44        | 59     | 6.41%   |
| SanDisk                     | 34        | 44     | 4.96%   |
| Unknown                     | 33        | 39     | 4.81%   |
| Intel                       | 26        | 29     | 3.79%   |
| Hitachi                     | 25        | 31     | 3.64%   |
| Micron Technology           | 23        | 27     | 3.35%   |
| HGST                        | 17        | 22     | 2.48%   |
| Apple                       | 11        | 14     | 1.6%    |
| LITEON                      | 10        | 23     | 1.46%   |
| Crucial                     | 10        | 10     | 1.46%   |
| Intenso                     | 9         | 11     | 1.31%   |
| PNY                         | 8         | 8      | 1.17%   |
| A-DATA Technology           | 6         | 7      | 0.87%   |
| LITEONIT                    | 5         | 6      | 0.73%   |
| OCZ                         | 4         | 4      | 0.58%   |
| Lenovo                      | 4         | 5      | 0.58%   |
| KIOXIA                      | 4         | 5      | 0.58%   |
| China                       | 4         | 5      | 0.58%   |
| Kingston Technology Company | 3         | 3      | 0.44%   |
| USB3.0                      | 2         | 2      | 0.29%   |
| Solid State Storage         | 2         | 2      | 0.29%   |
| Silicon Motion              | 2         | 2      | 0.29%   |
| Phison Electronics          | 2         | 2      | 0.29%   |
| Fujitsu                     | 2         | 3      | 0.29%   |
| XPG                         | 1         | 1      | 0.15%   |
| UMIS                        | 1         | 1      | 0.15%   |
| Transcend                   | 1         | 1      | 0.15%   |
| SPCC                        | 1         | 1      | 0.15%   |
| Plextor                     | 1         | 1      | 0.15%   |
| Phison                      | 1         | 2      | 0.15%   |
| Micron/Crucial Technology   | 1         | 1      | 0.15%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.15%   |
| KingFast                    | 1         | 1      | 0.15%   |
| Kingchuxing                 | 1         | 1      | 0.15%   |
| Hewlett-Packard             | 1         | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 11        | 1.54%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 10        | 1.4%    |
| Samsung SSD 850 EVO 500GB                           | 9         | 1.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 9         | 1.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 9         | 1.26%   |
| Kingston SA400S37480G 480GB SSD                     | 8         | 1.12%   |
| Kingston SA400S37240G 240GB SSD                     | 7         | 0.98%   |
| Unknown MMC Card  64GB                              | 6         | 0.84%   |
| Unknown MMC Card  32GB                              | 6         | 0.84%   |
| Toshiba NVMe SSD Drive 512GB                        | 6         | 0.84%   |
| Samsung NVMe SSD Drive 512GB                        | 6         | 0.84%   |
| HGST HTS721010A9E630 1TB                            | 6         | 0.84%   |
| SK hynix NVMe SSD Drive 512GB                       | 5         | 0.7%    |
| Samsung SSD 860 EVO 500GB                           | 5         | 0.7%    |
| Samsung NVMe SSD Drive 1024GB                       | 5         | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 4         | 0.56%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 4         | 0.56%   |
| Toshiba NVMe SSD Drive 256GB                        | 4         | 0.56%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 4         | 0.56%   |
| Seagate ST2000LM015-2E8174 2TB                      | 4         | 0.56%   |
| Samsung MZVLB512HAJQ-000L7 512GB                    | 4         | 0.56%   |
| PNY CS900 120GB SSD                                 | 4         | 0.56%   |
| HGST HTS545050A7E380 500GB                          | 4         | 0.56%   |
| WDC WD2500BEVT-60ZCT1 250GB                         | 3         | 0.42%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 0.42%   |
| Unknown MMC Card  128GB                             | 3         | 0.42%   |
| Toshiba THNSFJ256GCSU 256GB SSD                     | 3         | 0.42%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB              | 3         | 0.42%   |
| SK hynix NVMe SSD Drive 256GB                       | 3         | 0.42%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 0.42%   |
| Seagate ST1000LM048-2E7172 1TB                      | 3         | 0.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.42%   |
| Seagate Expansion 1TB                               | 3         | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.42%   |
| Samsung SSD 860 EVO 1TB                             | 3         | 0.42%   |
| Samsung SSD 840 EVO 250GB                           | 3         | 0.42%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                      | 3         | 0.42%   |
| Micron NVMe SSD Drive 512GB                         | 3         | 0.42%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB             | 3         | 0.42%   |
| Kingston SV300S37A240G 240GB SSD                    | 3         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 50        | 58     | 33.33%  |
| WDC      | 38        | 50     | 25.33%  |
| Hitachi  | 25        | 31     | 16.67%  |
| HGST     | 17        | 22     | 11.33%  |
| Toshiba  | 14        | 15     | 9.33%   |
| USB3.0   | 2         | 2      | 1.33%   |
| Fujitsu  | 2         | 3      | 1.33%   |
| Apricorn | 1         | 2      | 0.67%   |
| Apple    | 1         | 2      | 0.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 88        | 111    | 33.59%  |
| Kingston            | 39        | 52     | 14.89%  |
| SanDisk             | 16        | 20     | 6.11%   |
| Toshiba             | 13        | 15     | 4.96%   |
| WDC                 | 12        | 15     | 4.58%   |
| SK hynix            | 10        | 12     | 3.82%   |
| LITEON              | 9         | 22     | 3.44%   |
| Intel               | 9         | 10     | 3.44%   |
| Crucial             | 9         | 9      | 3.44%   |
| PNY                 | 8         | 8      | 3.05%   |
| Micron Technology   | 8         | 9      | 3.05%   |
| Apple               | 8         | 8      | 3.05%   |
| Intenso             | 7         | 9      | 2.67%   |
| LITEONIT            | 5         | 6      | 1.91%   |
| A-DATA Technology   | 5         | 5      | 1.91%   |
| OCZ                 | 4         | 4      | 1.53%   |
| China               | 4         | 5      | 1.53%   |
| SPCC                | 1         | 1      | 0.38%   |
| Plextor             | 1         | 1      | 0.38%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.38%   |
| KingFast            | 1         | 1      | 0.38%   |
| Kingchuxing         | 1         | 1      | 0.38%   |
| Dogfish             | 1         | 1      | 0.38%   |
| Corsair             | 1         | 1      | 0.38%   |
| ASUS-PHISON         | 1         | 1      | 0.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 248       | 328    | 38.04%  |
| NVMe    | 224       | 324    | 34.36%  |
| HDD     | 142       | 185    | 21.78%  |
| MMC     | 34        | 40     | 5.21%   |
| Unknown | 4         | 4      | 0.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 359       | 499    | 56.62%  |
| NVMe | 224       | 324    | 35.33%  |
| MMC  | 34        | 40     | 5.36%   |
| SAS  | 17        | 18     | 2.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 287       | 395    | 73.78%  |
| 0.51-1.0   | 83        | 96     | 21.34%  |
| 1.01-2.0   | 14        | 17     | 3.6%    |
| 4.01-10.0  | 4         | 4      | 1.03%   |
| 3.01-4.0   | 1         | 1      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 193       | 31.43%  |
| 251-500        | 134       | 21.82%  |
| 501-1000       | 95        | 15.47%  |
| 1-20           | 42        | 6.84%   |
| 51-100         | 40        | 6.51%   |
| 1001-2000      | 33        | 5.37%   |
| Unknown        | 31        | 5.05%   |
| 21-50          | 20        | 3.26%   |
| More than 3000 | 13        | 2.12%   |
| 2001-3000      | 13        | 2.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 251       | 39.78%  |
| 21-50          | 109       | 17.27%  |
| 101-250        | 74        | 11.73%  |
| 51-100         | 72        | 11.41%  |
| 251-500        | 54        | 8.56%   |
| Unknown        | 31        | 4.91%   |
| 501-1000       | 24        | 3.8%    |
| 1001-2000      | 9         | 1.43%   |
| More than 3000 | 4         | 0.63%   |
| 2001-3000      | 3         | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 8.7%    |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 8.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 4.35%   |
| WDC WD5000BPVT-80HXZT3 500GB          | 1         | 1      | 4.35%   |
| WDC WD5000BEVT-35ZAT0 500GB           | 1         | 1      | 4.35%   |
| WDC WD1600BEVT-00M9YT0 160GB          | 1         | 1      | 4.35%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 4.35%   |
| Toshiba MQ02ABD100H 1TB               | 1         | 1      | 4.35%   |
| Toshiba KSG60ZSE256G SATA 256GB SSD   | 1         | 1      | 4.35%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 4.35%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 4.35%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 4.35%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 4.35%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 4.35%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 4.35%   |
| SanDisk SSD U100 24GB                 | 1         | 1      | 4.35%   |
| Micron Technology 1100 SATA 512GB SSD | 1         | 1      | 4.35%   |
| Kingston SA400S37480G 480GB SSD       | 1         | 1      | 4.35%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 4.35%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 4.35%   |
| Apple HDD HTS547550A9E384 500GB       | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 26.09%  |
| WDC               | 4         | 4      | 17.39%  |
| HGST              | 4         | 4      | 17.39%  |
| Toshiba           | 3         | 3      | 13.04%  |
| SK hynix          | 2         | 2      | 8.7%    |
| SanDisk           | 1         | 1      | 4.35%   |
| Micron Technology | 1         | 1      | 4.35%   |
| Kingston          | 1         | 1      | 4.35%   |
| Apple             | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 40%     |
| HGST    | 4         | 4      | 26.67%  |
| WDC     | 3         | 3      | 20%     |
| Toshiba | 1         | 1      | 6.67%   |
| Apple   | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 15     | 65.22%  |
| SSD  | 7         | 7      | 30.43%  |
| NVMe | 1         | 1      | 4.35%   |

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
| Detected | 389       | 601    | 63.56%  |
| Works    | 200       | 257    | 32.68%  |
| Malfunc  | 23        | 23     | 3.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 365       | 55.3%   |
| Samsung Electronics              | 91        | 13.79%  |
| AMD                              | 54        | 8.18%   |
| SanDisk                          | 35        | 5.3%    |
| SK hynix                         | 33        | 5%      |
| Toshiba America Info Systems     | 18        | 2.73%   |
| Micron Technology                | 16        | 2.42%   |
| Kingston Technology Company      | 10        | 1.52%   |
| Nvidia                           | 9         | 1.36%   |
| Silicon Motion                   | 5         | 0.76%   |
| Phison Electronics               | 4         | 0.61%   |
| Lenovo                           | 4         | 0.61%   |
| KIOXIA                           | 3         | 0.45%   |
| ADATA Technology                 | 3         | 0.45%   |
| Solid State Storage Technology   | 2         | 0.3%    |
| Apple                            | 2         | 0.3%    |
| Union Memory (Shenzhen)          | 1         | 0.15%   |
| Silicon Integrated Systems [SiS] | 1         | 0.15%   |
| Micron/Crucial Technology        | 1         | 0.15%   |
| Lite-On Technology               | 1         | 0.15%   |
| JMicron Technology               | 1         | 0.15%   |
| ASMedia Technology               | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 49        | 6.89%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 45        | 6.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 44        | 6.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 39        | 5.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 35        | 4.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 33        | 4.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 24        | 3.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 24        | 3.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 2.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 19        | 2.67%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 17        | 2.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 15        | 2.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 13        | 1.83%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 12        | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 12        | 1.69%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 11        | 1.55%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 10        | 1.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 1.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 10        | 1.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 10        | 1.41%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 1.27%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 7         | 0.98%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 6         | 0.84%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 6         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 0.84%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 5         | 0.7%    |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 0.7%    |
| Intel SSD 660P Series                                                          | 5         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 5         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 5         | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 0.7%    |
| SK hynix PC611 NVMe Solid State Drive                                          | 4         | 0.56%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 4         | 0.56%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 4         | 0.56%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 4         | 0.56%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 4         | 0.56%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 4         | 0.56%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 4         | 0.56%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 378       | 55.92%  |
| NVMe | 225       | 33.28%  |
| IDE  | 42        | 6.21%   |
| RAID | 31        | 4.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 467       | 80.8%   |
| AMD    | 111       | 19.2%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 14        | 2.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 11        | 1.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 10        | 1.73%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 10        | 1.73%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 9         | 1.56%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 9         | 1.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 8         | 1.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 8         | 1.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 8         | 1.38%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 7         | 1.21%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 7         | 1.21%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 7         | 1.21%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 7         | 1.21%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 7         | 1.21%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics  | 7         | 1.21%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 6         | 1.04%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 6         | 1.04%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 6         | 1.04%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 6         | 1.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 6         | 1.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 6         | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 1.04%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 6         | 1.04%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 5         | 0.87%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 5         | 0.87%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 5         | 0.87%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 5         | 0.87%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 5         | 0.87%   |
| AMD Ryzen 9 5900HS with Radeon Graphics     | 5         | 0.87%   |
| AMD Custom APU 0405                         | 5         | 0.87%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 4         | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 0.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 4         | 0.69%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 4         | 0.69%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 4         | 0.69%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 4         | 0.69%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 4         | 0.69%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 4         | 0.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 4         | 0.69%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 4         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 164       | 28.37%  |
| Intel Core i7                  | 161       | 27.85%  |
| Other                          | 35        | 6.06%   |
| Intel Core 2 Duo               | 26        | 4.5%    |
| AMD Ryzen 7                    | 24        | 4.15%   |
| Intel Core i3                  | 23        | 3.98%   |
| Intel Celeron                  | 19        | 3.29%   |
| AMD Ryzen 5                    | 16        | 2.77%   |
| AMD Ryzen 7 PRO                | 13        | 2.25%   |
| AMD Ryzen 9                    | 10        | 1.73%   |
| Intel Pentium                  | 9         | 1.56%   |
| Intel Pentium Dual-Core        | 7         | 1.21%   |
| Intel Atom                     | 7         | 1.21%   |
| AMD A6                         | 6         | 1.04%   |
| Intel Core i9                  | 5         | 0.87%   |
| AMD Ryzen 5 PRO                | 4         | 0.69%   |
| AMD E1                         | 4         | 0.69%   |
| AMD A8                         | 4         | 0.69%   |
| Intel Pentium Silver           | 3         | 0.52%   |
| Intel Pentium M                | 3         | 0.52%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.52%   |
| AMD Ryzen 3                    | 3         | 0.52%   |
| AMD E                          | 3         | 0.52%   |
| AMD Athlon                     | 3         | 0.52%   |
| Intel Pentium Dual             | 2         | 0.35%   |
| Intel Genuine                  | 2         | 0.35%   |
| Intel Core m3                  | 2         | 0.35%   |
| Intel Core 2                   | 2         | 0.35%   |
| AMD A4                         | 2         | 0.35%   |
| AMD A10                        | 2         | 0.35%   |
| Intel Core m7                  | 1         | 0.17%   |
| Intel Core M                   | 1         | 0.17%   |
| Intel Celeron M                | 1         | 0.17%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.17%   |
| AMD FX                         | 1         | 0.17%   |
| AMD E2                         | 1         | 0.17%   |
| AMD Athlon X2                  | 1         | 0.17%   |
| AMD Athlon Neo                 | 1         | 0.17%   |
| AMD Athlon II Neo              | 1         | 0.17%   |
| AMD Athlon II Dual-Core        | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 283       | 48.96%  |
| 4      | 181       | 31.31%  |
| 8      | 52        | 9%      |
| 6      | 39        | 6.75%   |
| 1      | 15        | 2.6%    |
| 12     | 3         | 0.52%   |
| 14     | 2         | 0.35%   |
| 10     | 2         | 0.35%   |
| 24     | 1         | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 578       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 453       | 78.37%  |
| 1      | 124       | 21.45%  |
| 4      | 1         | 0.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 561       | 96.72%  |
| Unknown        | 13        | 2.24%   |
| 32-bit         | 6         | 1.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 184       | 30.51%  |
| 0x306a9    | 29        | 4.81%   |
| 0x40651    | 28        | 4.64%   |
| 0x206a7    | 27        | 4.48%   |
| 0x406e3    | 24        | 3.98%   |
| 0x906ea    | 19        | 3.15%   |
| 0x806e9    | 19        | 3.15%   |
| 0x306c3    | 19        | 3.15%   |
| 0x1067a    | 19        | 3.15%   |
| 0x806ea    | 18        | 2.99%   |
| 0x806ec    | 16        | 2.65%   |
| 0x20655    | 14        | 2.32%   |
| 0x0a50000c | 12        | 1.99%   |
| 0x806c1    | 11        | 1.82%   |
| 0x906e9    | 9         | 1.49%   |
| 0x08600106 | 9         | 1.49%   |
| 0x906ed    | 6         | 1%      |
| 0x806eb    | 6         | 1%      |
| 0x20652    | 6         | 1%      |
| 0x0a404102 | 6         | 1%      |
| 0x08600104 | 6         | 1%      |
| 0x706e5    | 5         | 0.83%   |
| 0x506e3    | 5         | 0.83%   |
| 0x306d4    | 5         | 0.83%   |
| 0x08608103 | 5         | 0.83%   |
| 0x08108102 | 5         | 0.83%   |
| 0x07030105 | 5         | 0.83%   |
| 0x6fd      | 4         | 0.66%   |
| 0x406c3    | 4         | 0.66%   |
| 0x30678    | 4         | 0.66%   |
| 0x10676    | 4         | 0.66%   |
| 0x0810100b | 4         | 0.66%   |
| 0xa0652    | 3         | 0.5%    |
| 0x706a1    | 3         | 0.5%    |
| 0x6fb      | 3         | 0.5%    |
| 0x6d8      | 3         | 0.5%    |
| 0x406c4    | 3         | 0.5%    |
| 0x08108109 | 3         | 0.5%    |
| 0x906a3    | 2         | 0.33%   |
| 0x6fa      | 2         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 126       | 21.8%   |
| Haswell          | 62        | 10.73%  |
| Skylake          | 46        | 7.96%   |
| SandyBridge      | 40        | 6.92%   |
| IvyBridge        | 40        | 6.92%   |
| Unknown          | 29        | 5.02%   |
| Penryn           | 28        | 4.84%   |
| Westmere         | 21        | 3.63%   |
| Zen 3            | 19        | 3.29%   |
| TigerLake        | 19        | 3.29%   |
| Zen 2            | 18        | 3.11%   |
| Broadwell        | 17        | 2.94%   |
| Core             | 14        | 2.42%   |
| Silvermont       | 13        | 2.25%   |
| Zen+             | 11        | 1.9%    |
| CometLake        | 7         | 1.21%   |
| Puma             | 6         | 1.04%   |
| IceLake          | 6         | 1.04%   |
| Goldmont plus    | 6         | 1.04%   |
| Excavator        | 6         | 1.04%   |
| P6               | 5         | 0.87%   |
| Bobcat           | 5         | 0.87%   |
| Alderlake Hybrid | 5         | 0.87%   |
| Zen              | 4         | 0.69%   |
| K8 Hammer        | 4         | 0.69%   |
| K8 & K10 hybrid  | 3         | 0.52%   |
| K10              | 3         | 0.52%   |
| Goldmont         | 3         | 0.52%   |
| Bonnell          | 3         | 0.52%   |
| Steamroller      | 2         | 0.35%   |
| Nehalem          | 2         | 0.35%   |
| K10 Llano        | 2         | 0.35%   |
| Jaguar           | 2         | 0.35%   |
| Piledriver       | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 416       | 57.14%  |
| Nvidia                           | 174       | 23.9%   |
| AMD                              | 137       | 18.82%  |
| Silicon Integrated Systems [SiS] | 1         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 38        | 5.06%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 37        | 4.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 35        | 4.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 33        | 4.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 30        | 3.99%   |
| Intel UHD Graphics 620                                                                   | 27        | 3.6%    |
| Intel HD Graphics 620                                                                    | 22        | 2.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 22        | 2.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 18        | 2.4%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 18        | 2.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 2.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 2.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 1.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 1.86%   |
| Intel HD Graphics 5500                                                                   | 11        | 1.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 1.46%   |
| Intel HD Graphics 630                                                                    | 10        | 1.33%   |
| AMD Rembrandt [Radeon 680M]                                                              | 9         | 1.2%    |
| AMD Lucienne                                                                             | 9         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 1.07%   |
| Intel HD Graphics 530                                                                    | 8         | 1.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.07%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 0.93%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.8%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.67%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 5         | 0.67%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 5         | 0.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.67%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 5         | 0.67%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.67%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 4         | 0.53%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.53%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.53%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 280       | 48.19%  |
| Intel + Nvidia | 116       | 19.97%  |
| 1 x AMD        | 91        | 15.66%  |
| 1 x Nvidia     | 42        | 7.23%   |
| Intel + AMD    | 18        | 3.1%    |
| AMD + Nvidia   | 15        | 2.58%   |
| 2 x AMD        | 14        | 2.41%   |
| Other          | 2         | 0.34%   |
| 2 x Intel      | 2         | 0.34%   |
| 1 x SiS        | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 484       | 82.74%  |
| Proprietary | 86        | 14.7%   |
| Unknown     | 15        | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 373       | 63.44%  |
| 0.01-0.5   | 75        | 12.76%  |
| 1.01-2.0   | 63        | 10.71%  |
| 0.51-1.0   | 30        | 5.1%    |
| 3.01-4.0   | 28        | 4.76%   |
| 5.01-6.0   | 10        | 1.7%    |
| 7.01-8.0   | 6         | 1.02%   |
| 2.01-3.0   | 2         | 0.34%   |
| 8.01-16.0  | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 138       | 20.6%   |
| LG Display              | 104       | 15.52%  |
| Chimei Innolux          | 74        | 11.04%  |
| BOE                     | 72        | 10.75%  |
| Samsung Electronics     | 61        | 9.1%    |
| Lenovo                  | 39        | 5.82%   |
| Dell                    | 23        | 3.43%   |
| Apple                   | 21        | 3.13%   |
| Sharp                   | 19        | 2.84%   |
| Chi Mei Optoelectronics | 14        | 2.09%   |
| Philips                 | 11        | 1.64%   |
| PANDA                   | 8         | 1.19%   |
| Hewlett-Packard         | 8         | 1.19%   |
| AOC                     | 7         | 1.04%   |
| Goldstar                | 6         | 0.9%    |
| InfoVision              | 5         | 0.75%   |
| BenQ                    | 5         | 0.75%   |
| Valve                   | 4         | 0.6%    |
| Panasonic               | 4         | 0.6%    |
| ASUSTek Computer        | 4         | 0.6%    |
| Sony                    | 3         | 0.45%   |
| MSI                     | 3         | 0.45%   |
| LG Philips              | 3         | 0.45%   |
| CSO                     | 3         | 0.45%   |
| TMX                     | 2         | 0.3%    |
| Seiko/Epson             | 2         | 0.3%    |
| Packard Bell            | 2         | 0.3%    |
| LGD                     | 2         | 0.3%    |
| IBM                     | 2         | 0.3%    |
| HKC                     | 2         | 0.3%    |
| CPT                     | 2         | 0.3%    |
| Acer                    | 2         | 0.3%    |
| ViewSonic               | 1         | 0.15%   |
| Vestel Elektronik       | 1         | 0.15%   |
| Toshiba                 | 1         | 0.15%   |
| Tianma XM               | 1         | 0.15%   |
| RTK                     | 1         | 0.15%   |
| PVT                     | 1         | 0.15%   |
| Lenovo Group Limited    | 1         | 0.15%   |
| JDI                     | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 8         | 1.17%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 7         | 1.02%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 6         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 5         | 0.73%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.73%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.73%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 4         | 0.58%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 4         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.58%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 4         | 0.58%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 4         | 0.58%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 4         | 0.58%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 3         | 0.44%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch              | 3         | 0.44%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.44%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 3         | 0.44%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 3         | 0.44%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch         | 3         | 0.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 3         | 0.44%   |
| BOE LCD Monitor BOE0A1D 2560x1600 302x189mm 14.0-inch                    | 3         | 0.44%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                    | 3         | 0.44%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch           | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO12ED 1920x1080 340x190mm 15.3-inch           | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch           | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 3         | 0.44%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                   | 3         | 0.44%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                    | 3         | 0.44%   |
| TMX TL140BDXP02-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 2         | 0.29%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 2         | 0.29%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.29%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 284       | 44.87%  |
| 1366x768 (WXGA)    | 108       | 17.06%  |
| 1600x900 (HD+)     | 52        | 8.21%   |
| 3840x2160 (4K)     | 46        | 7.27%   |
| 2560x1440 (QHD)    | 31        | 4.9%    |
| 1280x800 (WXGA)    | 22        | 3.48%   |
| 1920x1200 (WUXGA)  | 15        | 2.37%   |
| 1440x900 (WXGA+)   | 12        | 1.9%    |
| 2560x1600          | 11        | 1.74%   |
| 1680x1050 (WSXGA+) | 10        | 1.58%   |
| 2880x1800          | 8         | 1.26%   |
| 800x1280           | 5         | 0.79%   |
| 3440x1440          | 4         | 0.63%   |
| 3200x1800 (QHD+)   | 3         | 0.47%   |
| 1400x1050          | 3         | 0.47%   |
| 1280x1024 (SXGA)   | 3         | 0.47%   |
| 3840x2400          | 2         | 0.32%   |
| 3000x2000          | 2         | 0.32%   |
| 1920x540           | 2         | 0.32%   |
| 1024x600           | 2         | 0.32%   |
| 3840x1600          | 1         | 0.16%   |
| 3840x1100          | 1         | 0.16%   |
| 3840x1080          | 1         | 0.16%   |
| 3072x1920          | 1         | 0.16%   |
| 2256x1504          | 1         | 0.16%   |
| 2160x1440          | 1         | 0.16%   |
| 1360x768           | 1         | 0.16%   |
| Unknown            | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 238       | 35.36%  |
| 14      | 111       | 16.49%  |
| 13      | 97        | 14.41%  |
| 17      | 52        | 7.73%   |
| 27      | 30        | 4.46%   |
| 12      | 26        | 3.86%   |
| 24      | 25        | 3.71%   |
| 23      | 13        | 1.93%   |
| Unknown | 12        | 1.78%   |
| 31      | 10        | 1.49%   |
| 22      | 6         | 0.89%   |
| 16      | 6         | 0.89%   |
| 84      | 5         | 0.74%   |
| 21      | 5         | 0.74%   |
| 18      | 5         | 0.74%   |
| 11      | 5         | 0.74%   |
| 34      | 4         | 0.59%   |
| 7       | 4         | 0.59%   |
| 72      | 3         | 0.45%   |
| 25      | 3         | 0.45%   |
| 19      | 3         | 0.45%   |
| 10      | 3         | 0.45%   |
| 74      | 1         | 0.15%   |
| 65      | 1         | 0.15%   |
| 57      | 1         | 0.15%   |
| 37      | 1         | 0.15%   |
| 32      | 1         | 0.15%   |
| 29      | 1         | 0.15%   |
| 3       | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 391       | 58.71%  |
| 201-300     | 86        | 12.91%  |
| 501-600     | 62        | 9.31%   |
| 351-400     | 61        | 9.16%   |
| 601-700     | 16        | 2.4%    |
| 401-500     | 16        | 2.4%    |
| Unknown     | 12        | 1.8%    |
| 1501-2000   | 9         | 1.35%   |
| 701-800     | 5         | 0.75%   |
| 1-100       | 5         | 0.75%   |
| 1001-1500   | 2         | 0.3%    |
| 801-900     | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 476       | 79.73%  |
| 16/10   | 86        | 14.41%  |
| Unknown | 9         | 1.51%   |
| 3/2     | 8         | 1.34%   |
| 21/9    | 5         | 0.84%   |
| 0.67    | 4         | 0.67%   |
| 5/4     | 3         | 0.5%    |
| 4/3     | 3         | 0.5%    |
| 6/5     | 1         | 0.17%   |
| 32/9    | 1         | 0.17%   |
| 3.40    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 236       | 35.33%  |
| 81-90          | 169       | 25.3%   |
| 121-130        | 41        | 6.14%   |
| 71-80          | 39        | 5.84%   |
| 201-250        | 35        | 5.24%   |
| 301-350        | 30        | 4.49%   |
| 61-70          | 23        | 3.44%   |
| 351-500        | 14        | 2.1%    |
| 251-300        | 14        | 2.1%    |
| Unknown        | 12        | 1.8%    |
| More than 1000 | 11        | 1.65%   |
| 131-140        | 11        | 1.65%   |
| 51-60          | 6         | 0.9%    |
| 141-150        | 6         | 0.9%    |
| 111-120        | 6         | 0.9%    |
| 1-40           | 5         | 0.75%   |
| 41-50          | 3         | 0.45%   |
| 151-200        | 3         | 0.45%   |
| 91-100         | 3         | 0.45%   |
| 501-1000       | 1         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 302       | 45.97%  |
| 101-120       | 156       | 23.74%  |
| 51-100        | 84        | 12.79%  |
| 161-240       | 61        | 9.28%   |
| More than 240 | 37        | 5.63%   |
| Unknown       | 12        | 1.83%   |
| 1-50          | 5         | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 473       | 79.63%  |
| 2     | 91        | 15.32%  |
| 3     | 16        | 2.69%   |
| 0     | 12        | 2.02%   |
| 4     | 2         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 363       | 40.51%  |
| Realtek Semiconductor             | 247       | 27.57%  |
| Qualcomm Atheros                  | 102       | 11.38%  |
| Broadcom                          | 52        | 5.8%    |
| MediaTek                          | 16        | 1.79%   |
| Lenovo                            | 15        | 1.67%   |
| Broadcom Limited                  | 14        | 1.56%   |
| Sierra Wireless                   | 13        | 1.45%   |
| Ericsson Business Mobile Networks | 12        | 1.34%   |
| Ralink                            | 7         | 0.78%   |
| Nvidia                            | 7         | 0.78%   |
| Qualcomm                          | 5         | 0.56%   |
| Marvell Technology Group          | 5         | 0.56%   |
| DisplayLink                       | 4         | 0.45%   |
| Dell                              | 4         | 0.45%   |
| Xiaomi                            | 3         | 0.33%   |
| Samsung Electronics               | 3         | 0.33%   |
| Ralink Technology                 | 3         | 0.33%   |
| ASIX Electronics                  | 3         | 0.33%   |
| TP-Link                           | 2         | 0.22%   |
| NetGear                           | 2         | 0.22%   |
| Hewlett-Packard                   | 2         | 0.22%   |
| D-Link System                     | 2         | 0.22%   |
| ZyXEL Communications              | 1         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.11%   |
| Philips (or NXP)                  | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.11%   |
| Linksys                           | 1         | 0.11%   |
| ICS Advent                        | 1         | 0.11%   |
| Huawei Technologies               | 1         | 0.11%   |
| Google                            | 1         | 0.11%   |
| Fibocom                           | 1         | 0.11%   |
| ASUSTek Computer                  | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 162       | 14.2%   |
| Intel Wireless 8265 / 8275                                        | 38        | 3.33%   |
| Intel Wi-Fi 6 AX200                                               | 37        | 3.24%   |
| Intel Wireless 7260                                               | 36        | 3.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 3.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 3.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 28        | 2.45%   |
| Intel Wireless 8260                                               | 26        | 2.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 1.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 21        | 1.84%   |
| Intel Wireless 7265                                               | 21        | 1.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 1.4%    |
| Intel Ethernet Connection I218-LM                                 | 16        | 1.4%    |
| Intel Wi-Fi 6 AX201                                               | 14        | 1.23%   |
| Intel Centrino Ultimate-N 6300                                    | 13        | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 13        | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 12        | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 1.05%   |
| Intel Centrino Wireless-N 2230                                    | 12        | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 11        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 0.96%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 10        | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 0.88%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 10        | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 0.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 8         | 0.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 8         | 0.7%    |
| Intel Ethernet Connection I219-V                                  | 8         | 0.7%    |
| Sierra Wireless EM7455                                            | 7         | 0.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.53%   |
| Intel Wireless-AC 9260                                            | 6         | 0.53%   |
| Intel Wireless 3165                                               | 6         | 0.53%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 6         | 0.53%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 6         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 355       | 58.48%  |
| Qualcomm Atheros                  | 81        | 13.34%  |
| Realtek Semiconductor             | 62        | 10.21%  |
| Broadcom                          | 39        | 6.43%   |
| MediaTek                          | 16        | 2.64%   |
| Sierra Wireless                   | 13        | 2.14%   |
| Broadcom Limited                  | 10        | 1.65%   |
| Ralink                            | 7         | 1.15%   |
| Qualcomm                          | 4         | 0.66%   |
| Ericsson Business Mobile Networks | 4         | 0.66%   |
| Ralink Technology                 | 3         | 0.49%   |
| Dell                              | 3         | 0.49%   |
| TP-Link                           | 2         | 0.33%   |
| NetGear                           | 2         | 0.33%   |
| D-Link System                     | 2         | 0.33%   |
| ZyXEL Communications              | 1         | 0.16%   |
| Philips (or NXP)                  | 1         | 0.16%   |
| Fibocom                           | 1         | 0.16%   |
| ASUSTek Computer                  | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 38        | 6.26%   |
| Intel Wi-Fi 6 AX200                                                     | 37        | 6.1%    |
| Intel Wireless 7260                                                     | 36        | 5.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 4.61%   |
| Intel Wireless 8260                                                     | 26        | 4.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 21        | 3.46%   |
| Intel Wireless 7265                                                     | 21        | 3.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 16        | 2.64%   |
| Intel Wi-Fi 6 AX201                                                     | 14        | 2.31%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 2.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 13        | 2.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.98%   |
| Intel Centrino Wireless-N 2230                                          | 12        | 1.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 1.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 1.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 1.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 1.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 8         | 1.32%   |
| Sierra Wireless EM7455                                                  | 7         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.99%   |
| Intel Wireless-AC 9260                                                  | 6         | 0.99%   |
| Intel Wireless 3165                                                     | 6         | 0.99%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 0.99%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.99%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 0.99%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 0.99%   |
| Sierra Wireless EM7345 4G LTE                                           | 5         | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.82%   |
| Intel Wireless 3160                                                     | 5         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 224       | 43.58%  |
| Intel                            | 188       | 36.58%  |
| Qualcomm Atheros                 | 31        | 6.03%   |
| Broadcom                         | 22        | 4.28%   |
| Lenovo                           | 15        | 2.92%   |
| Nvidia                           | 7         | 1.36%   |
| Marvell Technology Group         | 5         | 0.97%   |
| DisplayLink                      | 4         | 0.78%   |
| Broadcom Limited                 | 4         | 0.78%   |
| Xiaomi                           | 3         | 0.58%   |
| ASIX Electronics                 | 3         | 0.58%   |
| Samsung Electronics              | 2         | 0.39%   |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |
| Qualcomm                         | 1         | 0.19%   |
| Linksys                          | 1         | 0.19%   |
| ICS Advent                       | 1         | 0.19%   |
| Hewlett-Packard                  | 1         | 0.19%   |
| Google                           | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 162       | 31.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 6.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 6.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 4.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 3.65%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 3.08%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 2.31%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 2.12%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 2.12%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 1.92%   |
| Intel Ethernet Connection I219-V                                  | 8         | 1.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 1.15%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 1.15%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.96%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.96%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.96%   |
| Intel Ethernet Connection (6) I219-LM                             | 5         | 0.96%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 0.96%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 0.77%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 4         | 0.77%   |
| Lenovo ThinkPad Lan                                               | 4         | 0.77%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 0.77%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.77%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 4         | 0.77%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.58%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.58%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.58%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.58%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.58%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.58%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 3         | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 571       | 53.41%  |
| Ethernet | 484       | 45.28%  |
| Modem    | 13        | 1.22%   |
| Unknown  | 1         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 483       | 78.03%  |
| Ethernet | 136       | 21.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 446       | 76.9%   |
| 1     | 123       | 21.21%  |
| 3     | 7         | 1.21%   |
| 0     | 4         | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 551       | 95%     |
| Yes  | 29        | 5%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 267       | 54.83%  |
| Broadcom                        | 44        | 9.03%   |
| Realtek Semiconductor           | 35        | 7.19%   |
| Qualcomm Atheros Communications | 27        | 5.54%   |
| IMC Networks                    | 22        | 4.52%   |
| Lite-On Technology              | 21        | 4.31%   |
| Foxconn / Hon Hai               | 21        | 4.31%   |
| Apple                           | 17        | 3.49%   |
| Hewlett-Packard                 | 9         | 1.85%   |
| Cambridge Silicon Radio         | 4         | 0.82%   |
| USI                             | 3         | 0.62%   |
| Dell                            | 3         | 0.62%   |
| Realtek                         | 2         | 0.41%   |
| Ralink Technology               | 2         | 0.41%   |
| Ralink                          | 2         | 0.41%   |
| ASUSTek Computer                | 2         | 0.41%   |
| Toshiba                         | 1         | 0.21%   |
| Taiyo Yuden                     | 1         | 0.21%   |
| MediaTek                        | 1         | 0.21%   |
| Foxconn International           | 1         | 0.21%   |
| D-Link System                   | 1         | 0.21%   |
| Chicony Electronics             | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 132       | 27.1%   |
| Intel AX200 Bluetooth                               | 36        | 7.39%   |
| Intel AX201 Bluetooth                               | 31        | 6.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 30        | 6.16%   |
| Realtek Bluetooth Radio                             | 21        | 4.31%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 4.11%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 16        | 3.29%   |
| Apple Bluetooth Host Controller                     | 12        | 2.46%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 2.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 2.05%   |
| IMC Networks Wireless_Device                        | 9         | 1.85%   |
| IMC Networks Bluetooth Radio                        | 9         | 1.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 1.64%   |
| Intel AX210 Bluetooth                               | 8         | 1.64%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 1.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.23%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 1.23%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 1.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.23%   |
| Intel Bluetooth Device                              | 5         | 1.03%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 5         | 1.03%   |
| Apple Bluetooth USB Host Controller                 | 5         | 1.03%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.82%   |
| Lite-On Bluetooth Device                            | 4         | 0.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 0.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 0.82%   |
| USI Bluetooth Device                                | 3         | 0.62%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.62%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.62%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.62%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.62%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.62%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.41%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.41%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.41%   |
| Lite-On Atheros Bluetooth                           | 2         | 0.41%   |
| IMC Networks Bluetooth                              | 2         | 0.41%   |
| Foxconn / Hon Hai Bluetooth Adapter                 | 2         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 454       | 61.6%   |
| AMD                              | 117       | 15.88%  |
| Nvidia                           | 105       | 14.25%  |
| Lenovo                           | 14        | 1.9%    |
| GN Netcom                        | 7         | 0.95%   |
| Hewlett-Packard                  | 4         | 0.54%   |
| Plantronics                      | 3         | 0.41%   |
| Logitech                         | 3         | 0.41%   |
| C-Media Electronics              | 3         | 0.41%   |
| XMOS                             | 2         | 0.27%   |
| Realtek Semiconductor            | 2         | 0.27%   |
| Razer USA                        | 2         | 0.27%   |
| Kingston Technology              | 2         | 0.27%   |
| DSEA A/S                         | 2         | 0.27%   |
| VIA Technologies                 | 1         | 0.14%   |
| Trust                            | 1         | 0.14%   |
| Texas Instruments                | 1         | 0.14%   |
| Sony                             | 1         | 0.14%   |
| Silicon Integrated Systems [SiS] | 1         | 0.14%   |
| Samson Technologies              | 1         | 0.14%   |
| RODE Microphones                 | 1         | 0.14%   |
| Project DAC DS                   | 1         | 0.14%   |
| OPPO Electronics                 | 1         | 0.14%   |
| NAD Electronics                  | 1         | 0.14%   |
| JMTek                            | 1         | 0.14%   |
| Generalplus Technology           | 1         | 0.14%   |
| Evolution Electronics            | 1         | 0.14%   |
| Creative Technology              | 1         | 0.14%   |
| Blue Microphones                 | 1         | 0.14%   |
| Antelope Audio                   | 1         | 0.14%   |
| Afatech                          | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 90        | 9.88%   |
| AMD Family 17h/19h HD Audio Controller                                     | 72        | 7.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 43        | 4.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 43        | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 36        | 3.95%   |
| Intel Haswell-ULT HD Audio Controller                                      | 35        | 3.84%   |
| Intel 8 Series HD Audio Controller                                         | 35        | 3.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 34        | 3.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 28        | 3.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 23        | 2.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22        | 2.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 21        | 2.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 2.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 18        | 1.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 16        | 1.76%   |
| Intel Broadwell-U Audio Controller                                         | 16        | 1.76%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 16        | 1.76%   |
| AMD FCH Azalia Controller                                                  | 15        | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14        | 1.54%   |
| Intel CM238 HD Audio Controller                                            | 12        | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 12        | 1.32%   |
| Nvidia GK107 HDMI Audio Controller                                         | 10        | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 10        | 1.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 1.1%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 0.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8         | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 0.77%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 0.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 0.66%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 0.66%   |
| Nvidia GT216 HDMI Audio Controller                                         | 5         | 0.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 0.55%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 0.55%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 0.55%   |
| Nvidia Audio device                                                        | 5         | 0.55%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 99        | 30.65%  |
| SK hynix            | 80        | 24.77%  |
| Micron Technology   | 44        | 13.62%  |
| Kingston            | 32        | 9.91%   |
| Unknown             | 20        | 6.19%   |
| Crucial             | 11        | 3.41%   |
| Elpida              | 9         | 2.79%   |
| Corsair             | 6         | 1.86%   |
| Ramaxel Technology  | 4         | 1.24%   |
| Nanya Technology    | 3         | 0.93%   |
| A-DATA Technology   | 3         | 0.93%   |
| G.Skill             | 2         | 0.62%   |
| ff                  | 2         | 0.62%   |
| 4ea5                | 2         | 0.62%   |
| Transcend           | 1         | 0.31%   |
| SHARETRONIC         | 1         | 0.31%   |
| Neo Forza           | 1         | 0.31%   |
| fef5                | 1         | 0.31%   |
| Avant               | 1         | 0.31%   |
| Apacer              | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 2.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 2.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 1.76%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 1.47%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 4         | 1.17%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 1.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.17%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 1.17%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 1.17%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.17%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 4         | 1.17%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.88%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.88%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.88%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.88%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.88%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 3         | 0.88%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 3         | 0.88%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 2         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.59%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.59%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 2         | 0.59%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.59%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.59%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.59%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.59%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.59%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.59%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.59%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.59%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.59%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.59%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 2         | 0.59%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 131       | 47.81%  |
| DDR3    | 86        | 31.39%  |
| LPDDR3  | 18        | 6.57%   |
| LPDDR4  | 14        | 5.11%   |
| DDR2    | 10        | 3.65%   |
| DDR5    | 6         | 2.19%   |
| LPDDR5  | 3         | 1.09%   |
| SDRAM   | 2         | 0.73%   |
| Unknown | 2         | 0.73%   |
| DRAM    | 1         | 0.36%   |
| DDR     | 1         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 240       | 86.64%  |
| Row Of Chips | 26        | 9.39%   |
| Chip         | 5         | 1.81%   |
| Unknown      | 5         | 1.81%   |
| DIMM         | 1         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 130       | 44.22%  |
| 4096  | 69        | 23.47%  |
| 16384 | 51        | 17.35%  |
| 2048  | 24        | 8.16%   |
| 32768 | 11        | 3.74%   |
| 1024  | 7         | 2.38%   |
| 512   | 2         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 64        | 22.15%  |
| 2667    | 57        | 19.72%  |
| 3200    | 51        | 17.65%  |
| 2133    | 27        | 9.34%   |
| 2400    | 15        | 5.19%   |
| 1334    | 12        | 4.15%   |
| 1867    | 10        | 3.46%   |
| 1333    | 8         | 2.77%   |
| 667     | 8         | 2.77%   |
| 4267    | 6         | 2.08%   |
| 1067    | 6         | 2.08%   |
| Unknown | 5         | 1.73%   |
| 4266    | 4         | 1.38%   |
| 5600    | 3         | 1.04%   |
| 4800    | 3         | 1.04%   |
| 6400    | 2         | 0.69%   |
| 3266    | 2         | 0.69%   |
| 2933    | 2         | 0.69%   |
| 800     | 2         | 0.69%   |
| 8400    | 1         | 0.35%   |
| 4199    | 1         | 0.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 40%     |
| Canon              | 2         | 40%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP Officejet Pro 6230    | 1         | 20%     |
| HP DeskJet 3700 series   | 1         | 20%     |
| Canon PIXMA MX370 Series | 1         | 20%     |
| Canon PIXMA MP280        | 1         | 20%     |
| Brother HL-1210W series  | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 145       | 28.54%  |
| Bison Electronics                      | 58        | 11.42%  |
| IMC Networks                           | 53        | 10.43%  |
| Realtek Semiconductor                  | 37        | 7.28%   |
| Quanta                                 | 24        | 4.72%   |
| Microdia                               | 24        | 4.72%   |
| Lite-On Technology                     | 21        | 4.13%   |
| Syntek                                 | 20        | 3.94%   |
| Sunplus Innovation Technology          | 18        | 3.54%   |
| Suyin                                  | 17        | 3.35%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 3.15%   |
| Apple                                  | 14        | 2.76%   |
| Acer                                   | 13        | 2.56%   |
| Logitech                               | 11        | 2.17%   |
| Lenovo                                 | 8         | 1.57%   |
| Luxvisions Innotech Limited            | 7         | 1.38%   |
| Silicon Motion                         | 5         | 0.98%   |
| Samsung Electronics                    | 3         | 0.59%   |
| Primax Electronics                     | 3         | 0.59%   |
| Sonix Technology                       | 2         | 0.39%   |
| Alcor Micro                            | 2         | 0.39%   |
| Z-Star Microelectronics                | 1         | 0.2%    |
| Ricoh                                  | 1         | 0.2%    |
| MacroSilicon                           | 1         | 0.2%    |
| Genesys Logic                          | 1         | 0.2%    |
| GEMBIRD                                | 1         | 0.2%    |
| Foxconn / Hon Hai                      | 1         | 0.2%    |
| ALi                                    | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 45        | 8.84%   |
| IMC Networks Integrated Camera           | 20        | 3.93%   |
| Chicony HD WebCam                        | 17        | 3.34%   |
| Bison Integrated Camera                  | 16        | 3.14%   |
| Realtek Integrated_Webcam_HD             | 15        | 2.95%   |
| IMC Networks USB2.0 HD UVC WebCam        | 15        | 2.95%   |
| Lite-On Integrated Camera                | 13        | 2.55%   |
| Microdia Integrated_Webcam_HD            | 12        | 2.36%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 10        | 1.96%   |
| Syntek Lenovo EasyCamera                 | 8         | 1.57%   |
| Syntek Integrated Camera                 | 8         | 1.57%   |
| Bison SunplusIT Integrated Camera        | 8         | 1.57%   |
| Quanta HD User Facing                    | 6         | 1.18%   |
| Chicony HP HD Camera                     | 6         | 1.18%   |
| Bison ThinkPad P50 Integrated Camera     | 6         | 1.18%   |
| Apple Built-in iSight                    | 6         | 1.18%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 5         | 0.98%   |
| Luxvisions Innotech Limited HP HD Camera | 5         | 0.98%   |
| Chicony Integrated Camera (1280x720@30)  | 5         | 0.98%   |
| Bison SunplusIT INC. Integrated Camera   | 5         | 0.98%   |
| Bison Lenovo EasyCamera                  | 5         | 0.98%   |
| Realtek Integrated Webcam HD             | 4         | 0.79%   |
| Quanta USB2.0 HD UVC WebCam              | 4         | 0.79%   |
| Quanta HP Webcam                         | 4         | 0.79%   |
| Quanta HD Webcam                         | 4         | 0.79%   |
| Lenovo Integrated Webcam                 | 4         | 0.79%   |
| Chicony USB 2.0 Camera                   | 4         | 0.79%   |
| Chicony Lenovo EasyCamera                | 4         | 0.79%   |
| Chicony Integrated Camera [ThinkPad]     | 4         | 0.79%   |
| Chicony HP Truevision HD                 | 4         | 0.79%   |
| Bison ThinkPad Integrated Camera         | 4         | 0.79%   |
| Bison HD Webcam                          | 4         | 0.79%   |
| Apple FaceTime HD Camera                 | 4         | 0.79%   |
| Sunplus Laptop Integrated WebCam HD      | 3         | 0.59%   |
| Sunplus Integrated_Webcam_HD             | 3         | 0.59%   |
| Samsung Galaxy series, misc. (MTP mode)  | 3         | 0.59%   |
| Realtek USB Camera                       | 3         | 0.59%   |
| Microdia Integrated_Webcam_FHD           | 3         | 0.59%   |
| Microdia Integrated Webcam               | 3         | 0.59%   |
| Lite-On HP HD Webcam                     | 3         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 59        | 37.34%  |
| Synaptics                  | 49        | 31.01%  |
| Upek                       | 17        | 10.76%  |
| Shenzhen Goodix Technology | 12        | 7.59%   |
| AuthenTec                  | 10        | 6.33%   |
| Elan Microelectronics      | 6         | 3.8%    |
| STMicroelectronics         | 3         | 1.9%    |
| LighTuning Technology      | 2         | 1.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 29        | 18.35%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 12.03%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 10.76%  |
| Validity Sensors Synaptics WBDI                                            | 10        | 6.33%   |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 5.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 3.16%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 3.16%   |
| Synaptics UWP WBDI Device                                                  | 5         | 3.16%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 3.16%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 3.16%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 2.53%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 2.53%   |
| Elan ELAN:ARM-M4                                                           | 4         | 2.53%   |
| AuthenTec AES2810                                                          | 4         | 2.53%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.9%    |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 1.9%    |
| STMicroelectronics Fingerprint Reader                                      | 3         | 1.9%    |
| Validity Sensors VFS491                                                    | 2         | 1.27%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.27%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.27%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.27%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.27%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.27%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.63%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.63%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.63%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.63%   |
| Synaptics TouchPad                                                         | 1         | 0.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.63%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.63%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.63%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 50        | 62.5%   |
| Broadcom    | 21        | 26.25%  |
| Upek        | 6         | 7.5%    |
| Lenovo      | 3         | 3.75%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 50        | 62.5%   |
| Broadcom 5880                                                                | 10        | 12.5%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 7.5%    |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 7.5%    |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.75%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 3.75%   |
| Broadcom 58200                                                               | 2         | 2.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 306       | 51.52%  |
| 1     | 206       | 34.68%  |
| 2     | 68        | 11.45%  |
| 3     | 8         | 1.35%   |
| 4     | 3         | 0.51%   |
| 6     | 2         | 0.34%   |
| 10    | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 156       | 40.94%  |
| Chipcard                 | 72        | 18.9%   |
| Graphics card            | 62        | 16.27%  |
| Net/wireless             | 23        | 6.04%   |
| Multimedia controller    | 22        | 5.77%   |
| Card reader              | 10        | 2.62%   |
| Camera                   | 9         | 2.36%   |
| Bluetooth                | 7         | 1.84%   |
| Communication controller | 6         | 1.57%   |
| Storage                  | 5         | 1.31%   |
| Net/ethernet             | 4         | 1.05%   |
| Sound                    | 3         | 0.79%   |
| Wireless                 | 1         | 0.26%   |
| Modem                    | 1         | 0.26%   |

