Arch - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Arch.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Arch/Desktop/README.md) and [notebooks](/Dist/Arch/Notebook/README.md).

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

Total: 9149

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | X79-UD3                     | Desktop     | [36fed79d81](https://linux-hardware.org/?probe=36fed79d81) | Jul 01, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [ceb2b4c1c5](https://linux-hardware.org/?probe=ceb2b4c1c5) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ef49f25cf8](https://linux-hardware.org/?probe=ef49f25cf8) | Jun 30, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [a3c2f0155c](https://linux-hardware.org/?probe=a3c2f0155c) | Jun 30, 2023 |
| Lenovo        | ThinkPad E490 20N80017RT    | Notebook    | [a2a1011725](https://linux-hardware.org/?probe=a2a1011725) | Jun 30, 2023 |
| Chuwi         | CoreBook XPro               | Notebook    | [501d899938](https://linux-hardware.org/?probe=501d899938) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [31db4fffd0](https://linux-hardware.org/?probe=31db4fffd0) | Jun 30, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [6c6741deb9](https://linux-hardware.org/?probe=6c6741deb9) | Jun 30, 2023 |
| Dell          | Latitude E5440              | Notebook    | [1fd8c9652a](https://linux-hardware.org/?probe=1fd8c9652a) | Jun 30, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [45d5903c62](https://linux-hardware.org/?probe=45d5903c62) | Jun 30, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [5a88d6945d](https://linux-hardware.org/?probe=5a88d6945d) | Jun 29, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [a33602b335](https://linux-hardware.org/?probe=a33602b335) | Jun 29, 2023 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [f3482421c4](https://linux-hardware.org/?probe=f3482421c4) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [eccf186dfd](https://linux-hardware.org/?probe=eccf186dfd) | Jun 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [56e2b61337](https://linux-hardware.org/?probe=56e2b61337) | Jun 29, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [86866241cd](https://linux-hardware.org/?probe=86866241cd) | Jun 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [722b0302f4](https://linux-hardware.org/?probe=722b0302f4) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [9814b54843](https://linux-hardware.org/?probe=9814b54843) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [5b82e1dd39](https://linux-hardware.org/?probe=5b82e1dd39) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | Notebook    | [b62328e801](https://linux-hardware.org/?probe=b62328e801) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [c6402add6a](https://linux-hardware.org/?probe=c6402add6a) | Jun 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 3 ... | Convertible | [d6d67cffd3](https://linux-hardware.org/?probe=d6d67cffd3) | Jun 28, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [971852cb38](https://linux-hardware.org/?probe=971852cb38) | Jun 28, 2023 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | Notebook    | [18847b167a](https://linux-hardware.org/?probe=18847b167a) | Jun 28, 2023 |
| Dell          | 0PC5F7 A01                  | Desktop     | [133ed5cc64](https://linux-hardware.org/?probe=133ed5cc64) | Jun 28, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [238e77122e](https://linux-hardware.org/?probe=238e77122e) | Jun 28, 2023 |
| COLORFUL      | X16 Pro 23                  | Notebook    | [656cf52198](https://linux-hardware.org/?probe=656cf52198) | Jun 28, 2023 |
| Acer          | Veriton M490G               | Desktop     | [1f3da6e87f](https://linux-hardware.org/?probe=1f3da6e87f) | Jun 28, 2023 |
| MSI           | S3361                       | Server      | [81c0a2f5b6](https://linux-hardware.org/?probe=81c0a2f5b6) | Jun 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [cd0c241308](https://linux-hardware.org/?probe=cd0c241308) | Jun 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [6615a04065](https://linux-hardware.org/?probe=6615a04065) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c9cbb8f947](https://linux-hardware.org/?probe=c9cbb8f947) | Jun 27, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [48b0ff43fa](https://linux-hardware.org/?probe=48b0ff43fa) | Jun 27, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [c0af461776](https://linux-hardware.org/?probe=c0af461776) | Jun 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [47451d9f30](https://linux-hardware.org/?probe=47451d9f30) | Jun 27, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | Notebook    | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [474833dcec](https://linux-hardware.org/?probe=474833dcec) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [85c3968edc](https://linux-hardware.org/?probe=85c3968edc) | Jun 26, 2023 |
| HP            | 18E7                        | Desktop     | [1ae4c92b7f](https://linux-hardware.org/?probe=1ae4c92b7f) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [1a17b8ee06](https://linux-hardware.org/?probe=1a17b8ee06) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [2fd779cefc](https://linux-hardware.org/?probe=2fd779cefc) | Jun 26, 2023 |
| Dell          | Precision 5570              | Notebook    | [dbf68aa669](https://linux-hardware.org/?probe=dbf68aa669) | Jun 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ef2e8da48a](https://linux-hardware.org/?probe=ef2e8da48a) | Jun 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [00cf0b0faa](https://linux-hardware.org/?probe=00cf0b0faa) | Jun 26, 2023 |
| Dell          | XPS 9315                    | Notebook    | [41bb8bd332](https://linux-hardware.org/?probe=41bb8bd332) | Jun 25, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [94fe70521f](https://linux-hardware.org/?probe=94fe70521f) | Jun 25, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | Notebook    | [ba30e1369c](https://linux-hardware.org/?probe=ba30e1369c) | Jun 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8b0180f4d4](https://linux-hardware.org/?probe=8b0180f4d4) | Jun 25, 2023 |
| ASUSTek       | N501VW                      | Notebook    | [7513f535f9](https://linux-hardware.org/?probe=7513f535f9) | Jun 25, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [aa75d0dace](https://linux-hardware.org/?probe=aa75d0dace) | Jun 25, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [d02e6a9fa6](https://linux-hardware.org/?probe=d02e6a9fa6) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [2b4069db98](https://linux-hardware.org/?probe=2b4069db98) | Jun 25, 2023 |
| MSI           | GS63 7RD                    | Notebook    | [310191e110](https://linux-hardware.org/?probe=310191e110) | Jun 24, 2023 |
| HONOR         | GLO-GXXX                    | Notebook    | [0e22fb1d65](https://linux-hardware.org/?probe=0e22fb1d65) | Jun 24, 2023 |
| ASRock        | H55M                        | Desktop     | [cb9e89e20e](https://linux-hardware.org/?probe=cb9e89e20e) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [dcfef21d2b](https://linux-hardware.org/?probe=dcfef21d2b) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [62d08bd4ca](https://linux-hardware.org/?probe=62d08bd4ca) | Jun 24, 2023 |
| Dell          | Precision 3581              | Notebook    | [2e960d89db](https://linux-hardware.org/?probe=2e960d89db) | Jun 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2faa400326](https://linux-hardware.org/?probe=2faa400326) | Jun 23, 2023 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [8df9a683cb](https://linux-hardware.org/?probe=8df9a683cb) | Jun 23, 2023 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [4d419c5b63](https://linux-hardware.org/?probe=4d419c5b63) | Jun 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [56208916c9](https://linux-hardware.org/?probe=56208916c9) | Jun 23, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [4430ccf679](https://linux-hardware.org/?probe=4430ccf679) | Jun 23, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [4cfd97f850](https://linux-hardware.org/?probe=4cfd97f850) | Jun 23, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [856acf81ed](https://linux-hardware.org/?probe=856acf81ed) | Jun 22, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [83d89a8751](https://linux-hardware.org/?probe=83d89a8751) | Jun 22, 2023 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | Desktop     | [7bf78e33d4](https://linux-hardware.org/?probe=7bf78e33d4) | Jun 22, 2023 |
| IP3 Techno... | ACB19                       | Mini pc     | [db5c45e4f7](https://linux-hardware.org/?probe=db5c45e4f7) | Jun 22, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [e8391a9f3d](https://linux-hardware.org/?probe=e8391a9f3d) | Jun 22, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [928f167dee](https://linux-hardware.org/?probe=928f167dee) | Jun 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [cbf5b19c76](https://linux-hardware.org/?probe=cbf5b19c76) | Jun 21, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [9fef8732b6](https://linux-hardware.org/?probe=9fef8732b6) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [baab7764b1](https://linux-hardware.org/?probe=baab7764b1) | Jun 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [26a3b9b3e9](https://linux-hardware.org/?probe=26a3b9b3e9) | Jun 21, 2023 |
| HP            | 21EF                        | Desktop     | [6022eb31ff](https://linux-hardware.org/?probe=6022eb31ff) | Jun 21, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [a7e4d1a6bd](https://linux-hardware.org/?probe=a7e4d1a6bd) | Jun 21, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [e67932c5a0](https://linux-hardware.org/?probe=e67932c5a0) | Jun 21, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [ae2beb307a](https://linux-hardware.org/?probe=ae2beb307a) | Jun 20, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [c2c2365360](https://linux-hardware.org/?probe=c2c2365360) | Jun 20, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [092370b958](https://linux-hardware.org/?probe=092370b958) | Jun 20, 2023 |
| Acer          | Nitro AN517-51              | Notebook    | [b4423e6ac2](https://linux-hardware.org/?probe=b4423e6ac2) | Jun 20, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [dd152b03bc](https://linux-hardware.org/?probe=dd152b03bc) | Jun 20, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [3375eaaeb3](https://linux-hardware.org/?probe=3375eaaeb3) | Jun 20, 2023 |
| Lenovo        | ThinkPad T590 20N5S14V00    | Notebook    | [6f81cc6d57](https://linux-hardware.org/?probe=6f81cc6d57) | Jun 19, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9e30c629f3](https://linux-hardware.org/?probe=9e30c629f3) | Jun 19, 2023 |
| HASEE Comp... | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [2c0be5d314](https://linux-hardware.org/?probe=2c0be5d314) | Jun 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [5bd2521f5c](https://linux-hardware.org/?probe=5bd2521f5c) | Jun 19, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [0f15219a46](https://linux-hardware.org/?probe=0f15219a46) | Jun 19, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [6a63f44627](https://linux-hardware.org/?probe=6a63f44627) | Jun 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e9865c622f](https://linux-hardware.org/?probe=e9865c622f) | Jun 19, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [dcd3e79cb1](https://linux-hardware.org/?probe=dcd3e79cb1) | Jun 18, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [c1472b1c25](https://linux-hardware.org/?probe=c1472b1c25) | Jun 18, 2023 |
| Intel         | NUC5PPYB H76558-108         | Mini pc     | [1d1386c5e2](https://linux-hardware.org/?probe=1d1386c5e2) | Jun 18, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [cb20c2c912](https://linux-hardware.org/?probe=cb20c2c912) | Jun 18, 2023 |
| Acer          | Veriton M490G               | Desktop     | [f9405b8bd2](https://linux-hardware.org/?probe=f9405b8bd2) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2324CD1       | Notebook    | [9ee6ed4144](https://linux-hardware.org/?probe=9ee6ed4144) | Jun 18, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [26e276dc29](https://linux-hardware.org/?probe=26e276dc29) | Jun 18, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [978e506718](https://linux-hardware.org/?probe=978e506718) | Jun 18, 2023 |
| Dell          | Latitude E7440              | Notebook    | [60d14fe6ab](https://linux-hardware.org/?probe=60d14fe6ab) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [94999d2965](https://linux-hardware.org/?probe=94999d2965) | Jun 18, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [676efbb266](https://linux-hardware.org/?probe=676efbb266) | Jun 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9b5c44b13a](https://linux-hardware.org/?probe=9b5c44b13a) | Jun 17, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [d5ba369651](https://linux-hardware.org/?probe=d5ba369651) | Jun 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [f010c487a1](https://linux-hardware.org/?probe=f010c487a1) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [6294c25695](https://linux-hardware.org/?probe=6294c25695) | Jun 17, 2023 |
| Acer          | Nitro AN517-51              | Notebook    | [d2f2f70083](https://linux-hardware.org/?probe=d2f2f70083) | Jun 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | Notebook    | [bfa70344e3](https://linux-hardware.org/?probe=bfa70344e3) | Jun 16, 2023 |
| Samsung       | 750XDA                      | Notebook    | [e04dd13d49](https://linux-hardware.org/?probe=e04dd13d49) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c338e10965](https://linux-hardware.org/?probe=c338e10965) | Jun 16, 2023 |
| Samsung       | 930QCG                      | Convertible | [339858c7c7](https://linux-hardware.org/?probe=339858c7c7) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [176973d157](https://linux-hardware.org/?probe=176973d157) | Jun 16, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [1150629ceb](https://linux-hardware.org/?probe=1150629ceb) | Jun 16, 2023 |
| Lenovo        | ThinkPad E480 20KNA047CD    | Notebook    | [918de7de03](https://linux-hardware.org/?probe=918de7de03) | Jun 16, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [ae9d05ff3a](https://linux-hardware.org/?probe=ae9d05ff3a) | Jun 15, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [67b278ea0e](https://linux-hardware.org/?probe=67b278ea0e) | Jun 15, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [ca0cba861a](https://linux-hardware.org/?probe=ca0cba861a) | Jun 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0TG00    | Notebook    | [628c8fb554](https://linux-hardware.org/?probe=628c8fb554) | Jun 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [a6f63a08e2](https://linux-hardware.org/?probe=a6f63a08e2) | Jun 15, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [2111a059f3](https://linux-hardware.org/?probe=2111a059f3) | Jun 15, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [66cc56555d](https://linux-hardware.org/?probe=66cc56555d) | Jun 15, 2023 |
| Lenovo        | ThinkPad L420 78545EG       | Notebook    | [bb42ee1009](https://linux-hardware.org/?probe=bb42ee1009) | Jun 14, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [535950bae5](https://linux-hardware.org/?probe=535950bae5) | Jun 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [c05a02e77b](https://linux-hardware.org/?probe=c05a02e77b) | Jun 14, 2023 |
| ASUSTek       | P553UA                      | Notebook    | [2543eb4ce8](https://linux-hardware.org/?probe=2543eb4ce8) | Jun 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b548786e27](https://linux-hardware.org/?probe=b548786e27) | Jun 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [928063a305](https://linux-hardware.org/?probe=928063a305) | Jun 13, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [f0f0a1b2ac](https://linux-hardware.org/?probe=f0f0a1b2ac) | Jun 13, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [20c6793733](https://linux-hardware.org/?probe=20c6793733) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [d2e4302f28](https://linux-hardware.org/?probe=d2e4302f28) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [e858489484](https://linux-hardware.org/?probe=e858489484) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [74b5d0e60a](https://linux-hardware.org/?probe=74b5d0e60a) | Jun 13, 2023 |
| Dell          | Inspiron 7786               | Convertible | [d6fa177357](https://linux-hardware.org/?probe=d6fa177357) | Jun 12, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [0fe4687002](https://linux-hardware.org/?probe=0fe4687002) | Jun 12, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [bac6eb2f16](https://linux-hardware.org/?probe=bac6eb2f16) | Jun 12, 2023 |
| Dell          | Inspiron 7786               | Convertible | [afd9c5a18f](https://linux-hardware.org/?probe=afd9c5a18f) | Jun 12, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6fcdcaa48c](https://linux-hardware.org/?probe=6fcdcaa48c) | Jun 12, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [7082d05ede](https://linux-hardware.org/?probe=7082d05ede) | Jun 12, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [5678f7fb1f](https://linux-hardware.org/?probe=5678f7fb1f) | Jun 12, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [41526d21bc](https://linux-hardware.org/?probe=41526d21bc) | Jun 12, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [6154060edd](https://linux-hardware.org/?probe=6154060edd) | Jun 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [2aaa4324d0](https://linux-hardware.org/?probe=2aaa4324d0) | Jun 12, 2023 |
| Acer          | Veriton M490G               | Desktop     | [78ff85b0a4](https://linux-hardware.org/?probe=78ff85b0a4) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [8bc28cc12c](https://linux-hardware.org/?probe=8bc28cc12c) | Jun 11, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | Notebook    | [ba129cd52d](https://linux-hardware.org/?probe=ba129cd52d) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [e7d498373d](https://linux-hardware.org/?probe=e7d498373d) | Jun 11, 2023 |
| Medion        | E2291                       | Convertible | [4e834d645d](https://linux-hardware.org/?probe=4e834d645d) | Jun 11, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [7a081b66af](https://linux-hardware.org/?probe=7a081b66af) | Jun 11, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [4ecff82426](https://linux-hardware.org/?probe=4ecff82426) | Jun 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [0d80451f80](https://linux-hardware.org/?probe=0d80451f80) | Jun 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [b25c3a4ecb](https://linux-hardware.org/?probe=b25c3a4ecb) | Jun 11, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [823925da4a](https://linux-hardware.org/?probe=823925da4a) | Jun 11, 2023 |
| NEC Comput... | PC-LM550LS6R                | Notebook    | [695f9825a6](https://linux-hardware.org/?probe=695f9825a6) | Jun 11, 2023 |
| Dell          | Latitude E5470              | Notebook    | [cc81f6c74c](https://linux-hardware.org/?probe=cc81f6c74c) | Jun 11, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [80bc2607fb](https://linux-hardware.org/?probe=80bc2607fb) | Jun 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [57f37d5836](https://linux-hardware.org/?probe=57f37d5836) | Jun 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [0b0c11a052](https://linux-hardware.org/?probe=0b0c11a052) | Jun 09, 2023 |
| Gigabyte      | B460M DS3H                  | Desktop     | [63c9d6c822](https://linux-hardware.org/?probe=63c9d6c822) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | Notebook    | [a165849009](https://linux-hardware.org/?probe=a165849009) | Jun 09, 2023 |
| Dell          | Latitude E5470              | Notebook    | [c9b909273b](https://linux-hardware.org/?probe=c9b909273b) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | Notebook    | [05c07442a3](https://linux-hardware.org/?probe=05c07442a3) | Jun 09, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [61a0a2ea5f](https://linux-hardware.org/?probe=61a0a2ea5f) | Jun 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8b8c6949b6](https://linux-hardware.org/?probe=8b8c6949b6) | Jun 09, 2023 |
| HP            | 14                          | Notebook    | [1540a787fb](https://linux-hardware.org/?probe=1540a787fb) | Jun 09, 2023 |
| HP            | 14                          | Notebook    | [1404218cab](https://linux-hardware.org/?probe=1404218cab) | Jun 09, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [bb7335618d](https://linux-hardware.org/?probe=bb7335618d) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [fc60082dfe](https://linux-hardware.org/?probe=fc60082dfe) | Jun 08, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [5861bc7cef](https://linux-hardware.org/?probe=5861bc7cef) | Jun 08, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [97d002b53a](https://linux-hardware.org/?probe=97d002b53a) | Jun 08, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ba4bfc1fe1](https://linux-hardware.org/?probe=ba4bfc1fe1) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [5533070ec1](https://linux-hardware.org/?probe=5533070ec1) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [19c6b51f80](https://linux-hardware.org/?probe=19c6b51f80) | Jun 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3cfa2bccb7](https://linux-hardware.org/?probe=3cfa2bccb7) | Jun 08, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [ac292cca00](https://linux-hardware.org/?probe=ac292cca00) | Jun 08, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [04d84e44a5](https://linux-hardware.org/?probe=04d84e44a5) | Jun 08, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [59c8fdd841](https://linux-hardware.org/?probe=59c8fdd841) | Jun 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [2410d016d6](https://linux-hardware.org/?probe=2410d016d6) | Jun 08, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Convertible | [41dea00814](https://linux-hardware.org/?probe=41dea00814) | Jun 08, 2023 |
| Google        | Edgar                       | Notebook    | [bec197cb98](https://linux-hardware.org/?probe=bec197cb98) | Jun 07, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [e7cdd7e89b](https://linux-hardware.org/?probe=e7cdd7e89b) | Jun 07, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [45cc99775f](https://linux-hardware.org/?probe=45cc99775f) | Jun 07, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [9529a983b8](https://linux-hardware.org/?probe=9529a983b8) | Jun 07, 2023 |
| HP            | 3396                        | Desktop     | [ca540b449f](https://linux-hardware.org/?probe=ca540b449f) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [2b1a1d3e39](https://linux-hardware.org/?probe=2b1a1d3e39) | Jun 07, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [05d49007a4](https://linux-hardware.org/?probe=05d49007a4) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [3308d91565](https://linux-hardware.org/?probe=3308d91565) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1f4ef72dbd](https://linux-hardware.org/?probe=1f4ef72dbd) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [db7f17cbe1](https://linux-hardware.org/?probe=db7f17cbe1) | Jun 07, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [9636ea4dc5](https://linux-hardware.org/?probe=9636ea4dc5) | Jun 07, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [aab84214f1](https://linux-hardware.org/?probe=aab84214f1) | Jun 06, 2023 |
| Dell          | Latitude 5480               | Notebook    | [dd2fef35ee](https://linux-hardware.org/?probe=dd2fef35ee) | Jun 06, 2023 |
| Dell          | Latitude 5480               | Notebook    | [7917512387](https://linux-hardware.org/?probe=7917512387) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [662e292b55](https://linux-hardware.org/?probe=662e292b55) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [024a1f80a1](https://linux-hardware.org/?probe=024a1f80a1) | Jun 06, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [6cd3cfcacf](https://linux-hardware.org/?probe=6cd3cfcacf) | Jun 06, 2023 |
| Lenovo        | ThinkPad 21CKCT01WW         | Notebook    | [92c9ec75c4](https://linux-hardware.org/?probe=92c9ec75c4) | Jun 05, 2023 |
| MSI           | Crosshair 15 C12VF          | Notebook    | [6cd11169d0](https://linux-hardware.org/?probe=6cd11169d0) | Jun 05, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [e92db65759](https://linux-hardware.org/?probe=e92db65759) | Jun 05, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [3eb711e453](https://linux-hardware.org/?probe=3eb711e453) | Jun 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [a3089228b1](https://linux-hardware.org/?probe=a3089228b1) | Jun 05, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [6d2c05fd11](https://linux-hardware.org/?probe=6d2c05fd11) | Jun 05, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [f8f07099c7](https://linux-hardware.org/?probe=f8f07099c7) | Jun 05, 2023 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [f4e7c7034f](https://linux-hardware.org/?probe=f4e7c7034f) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [54e2e07ac6](https://linux-hardware.org/?probe=54e2e07ac6) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [292e41c0e9](https://linux-hardware.org/?probe=292e41c0e9) | Jun 05, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bfce53d6f5](https://linux-hardware.org/?probe=bfce53d6f5) | Jun 05, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [eb67866c74](https://linux-hardware.org/?probe=eb67866c74) | Jun 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [8c6a275a93](https://linux-hardware.org/?probe=8c6a275a93) | Jun 05, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [8cbfe4cdf0](https://linux-hardware.org/?probe=8cbfe4cdf0) | Jun 05, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [ecad21f91c](https://linux-hardware.org/?probe=ecad21f91c) | Jun 04, 2023 |
| MSI           | Katana GF66 11UG            | Notebook    | [d50f02e996](https://linux-hardware.org/?probe=d50f02e996) | Jun 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3d29012888](https://linux-hardware.org/?probe=3d29012888) | Jun 04, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [f92e294ba0](https://linux-hardware.org/?probe=f92e294ba0) | Jun 04, 2023 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [bdf4ee4d4f](https://linux-hardware.org/?probe=bdf4ee4d4f) | Jun 04, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [72ccbe10aa](https://linux-hardware.org/?probe=72ccbe10aa) | Jun 04, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [2eeb67613f](https://linux-hardware.org/?probe=2eeb67613f) | Jun 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7179829c20](https://linux-hardware.org/?probe=7179829c20) | Jun 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [038871f5be](https://linux-hardware.org/?probe=038871f5be) | Jun 04, 2023 |
| Unknown       | Intel X79                   | Desktop     | [0e2e65a79e](https://linux-hardware.org/?probe=0e2e65a79e) | Jun 04, 2023 |
| Cube          | i16-L                       | Notebook    | [5e0bd26a26](https://linux-hardware.org/?probe=5e0bd26a26) | Jun 04, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [fb0c1a4922](https://linux-hardware.org/?probe=fb0c1a4922) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [d45c069b9f](https://linux-hardware.org/?probe=d45c069b9f) | Jun 04, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [a90856c944](https://linux-hardware.org/?probe=a90856c944) | Jun 04, 2023 |
| ASUSTek       | Zenbook UM5401RA_RM5401R... | Notebook    | [763a52f3e8](https://linux-hardware.org/?probe=763a52f3e8) | Jun 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0523005c68](https://linux-hardware.org/?probe=0523005c68) | Jun 03, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [6754a25d1d](https://linux-hardware.org/?probe=6754a25d1d) | Jun 03, 2023 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [1908e7e6f5](https://linux-hardware.org/?probe=1908e7e6f5) | Jun 03, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | Notebook    | [e0f06316db](https://linux-hardware.org/?probe=e0f06316db) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [95ec288436](https://linux-hardware.org/?probe=95ec288436) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [7720a9f71c](https://linux-hardware.org/?probe=7720a9f71c) | Jun 03, 2023 |
| Gigabyte      | AERO 15WV8                  | Notebook    | [a8700141be](https://linux-hardware.org/?probe=a8700141be) | Jun 03, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [4f512af4c2](https://linux-hardware.org/?probe=4f512af4c2) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [d2189d4a5f](https://linux-hardware.org/?probe=d2189d4a5f) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [49ca1fd34f](https://linux-hardware.org/?probe=49ca1fd34f) | Jun 02, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [d75ea1f93f](https://linux-hardware.org/?probe=d75ea1f93f) | Jun 02, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [947c70d6b6](https://linux-hardware.org/?probe=947c70d6b6) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c9e1edde25](https://linux-hardware.org/?probe=c9e1edde25) | Jun 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [d61bd0903e](https://linux-hardware.org/?probe=d61bd0903e) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [1f18cef2df](https://linux-hardware.org/?probe=1f18cef2df) | Jun 01, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [38a0e17081](https://linux-hardware.org/?probe=38a0e17081) | Jun 01, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [7ae3edd73e](https://linux-hardware.org/?probe=7ae3edd73e) | Jun 01, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [d9bfa42b63](https://linux-hardware.org/?probe=d9bfa42b63) | Jun 01, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [aaeac4c226](https://linux-hardware.org/?probe=aaeac4c226) | Jun 01, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [b3eed1356b](https://linux-hardware.org/?probe=b3eed1356b) | Jun 01, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [f383c5193d](https://linux-hardware.org/?probe=f383c5193d) | Jun 01, 2023 |
| ASUSTek       | ROG Flow X16 GV601VI_GV6... | Convertible | [76ec545734](https://linux-hardware.org/?probe=76ec545734) | Jun 01, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [efe855c429](https://linux-hardware.org/?probe=efe855c429) | May 31, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [c56e8318db](https://linux-hardware.org/?probe=c56e8318db) | May 31, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [2c4acbbad3](https://linux-hardware.org/?probe=2c4acbbad3) | May 31, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [ceaf9120eb](https://linux-hardware.org/?probe=ceaf9120eb) | May 31, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [ac6f421fef](https://linux-hardware.org/?probe=ac6f421fef) | May 31, 2023 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [8389c76bd3](https://linux-hardware.org/?probe=8389c76bd3) | May 31, 2023 |
| Dell          | Latitude E6420              | Notebook    | [102e4634b1](https://linux-hardware.org/?probe=102e4634b1) | May 31, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [4a3e8c4d6f](https://linux-hardware.org/?probe=4a3e8c4d6f) | May 31, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | Desktop     | [4dfacbbeb1](https://linux-hardware.org/?probe=4dfacbbeb1) | May 31, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [8a6ceb7d8b](https://linux-hardware.org/?probe=8a6ceb7d8b) | May 30, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [ab97cb7f09](https://linux-hardware.org/?probe=ab97cb7f09) | May 30, 2023 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [b706fad8dc](https://linux-hardware.org/?probe=b706fad8dc) | May 30, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [b00cd1c84e](https://linux-hardware.org/?probe=b00cd1c84e) | May 30, 2023 |
| Cincoze       | 1.0.01.001                  | Desktop     | [1552e93368](https://linux-hardware.org/?probe=1552e93368) | May 30, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [c02695ea7d](https://linux-hardware.org/?probe=c02695ea7d) | May 30, 2023 |
| ASUSTek       | N61Jv                       | Notebook    | [7184d6add6](https://linux-hardware.org/?probe=7184d6add6) | May 30, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [55b500a1a9](https://linux-hardware.org/?probe=55b500a1a9) | May 30, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [4fbe93ecc5](https://linux-hardware.org/?probe=4fbe93ecc5) | May 30, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c98400b6eb](https://linux-hardware.org/?probe=c98400b6eb) | May 30, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d4cc055d3a](https://linux-hardware.org/?probe=d4cc055d3a) | May 30, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [29d2e377ad](https://linux-hardware.org/?probe=29d2e377ad) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [b8e68f9227](https://linux-hardware.org/?probe=b8e68f9227) | May 29, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [10e4fd14b5](https://linux-hardware.org/?probe=10e4fd14b5) | May 29, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [541e16d421](https://linux-hardware.org/?probe=541e16d421) | May 29, 2023 |
| HP            | 14                          | Notebook    | [977d26c9b5](https://linux-hardware.org/?probe=977d26c9b5) | May 29, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [7adfc9796d](https://linux-hardware.org/?probe=7adfc9796d) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [84781c068a](https://linux-hardware.org/?probe=84781c068a) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [97f0880258](https://linux-hardware.org/?probe=97f0880258) | May 29, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [644a5d7a16](https://linux-hardware.org/?probe=644a5d7a16) | May 29, 2023 |
| Dell          | Inspiron 5447               | Notebook    | [270e3cd993](https://linux-hardware.org/?probe=270e3cd993) | May 29, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [12838b3e3b](https://linux-hardware.org/?probe=12838b3e3b) | May 28, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [99540846c4](https://linux-hardware.org/?probe=99540846c4) | May 28, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [99c9a792f5](https://linux-hardware.org/?probe=99c9a792f5) | May 28, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [47ac3b9c43](https://linux-hardware.org/?probe=47ac3b9c43) | May 28, 2023 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [f7d00f30cb](https://linux-hardware.org/?probe=f7d00f30cb) | May 28, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [b5e36f87e6](https://linux-hardware.org/?probe=b5e36f87e6) | May 28, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [4a54b4e82c](https://linux-hardware.org/?probe=4a54b4e82c) | May 28, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [c4ee84b38e](https://linux-hardware.org/?probe=c4ee84b38e) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [462ae1c4f5](https://linux-hardware.org/?probe=462ae1c4f5) | May 28, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [807dd44df4](https://linux-hardware.org/?probe=807dd44df4) | May 28, 2023 |
| Unknown       | Unknown                     | Soc         | [cb86a495e2](https://linux-hardware.org/?probe=cb86a495e2) | May 27, 2023 |
| HP            | 2AF7                        | Desktop     | [b459ce46cb](https://linux-hardware.org/?probe=b459ce46cb) | May 27, 2023 |
| Unknown       | Unknown                     | Soc         | [0ddad101d8](https://linux-hardware.org/?probe=0ddad101d8) | May 27, 2023 |
| Lenovo        | ThinkPad T560 20FJS0CX00    | Notebook    | [cf7d5b7149](https://linux-hardware.org/?probe=cf7d5b7149) | May 27, 2023 |
| Dell          | Latitude E6440              | Notebook    | [821e3e3246](https://linux-hardware.org/?probe=821e3e3246) | May 27, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [dd79b67b18](https://linux-hardware.org/?probe=dd79b67b18) | May 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [737d3fe7fb](https://linux-hardware.org/?probe=737d3fe7fb) | May 27, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [cbcea9cc58](https://linux-hardware.org/?probe=cbcea9cc58) | May 27, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [4e7b273239](https://linux-hardware.org/?probe=4e7b273239) | May 27, 2023 |
| Dell          | Precision 3581              | Notebook    | [9fb00fd492](https://linux-hardware.org/?probe=9fb00fd492) | May 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [16ee98f9cc](https://linux-hardware.org/?probe=16ee98f9cc) | May 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [39cf075935](https://linux-hardware.org/?probe=39cf075935) | May 26, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [8b93a6ab33](https://linux-hardware.org/?probe=8b93a6ab33) | May 26, 2023 |
| Dell          | Latitude 5430               | Notebook    | [e8b9199229](https://linux-hardware.org/?probe=e8b9199229) | May 26, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [acee298918](https://linux-hardware.org/?probe=acee298918) | May 26, 2023 |
| Acer          | WG43M                       | Desktop     | [9afcfc4a44](https://linux-hardware.org/?probe=9afcfc4a44) | May 26, 2023 |
| Lenovo        | Yoga Slim 7 proX 14ARH7 ... | Notebook    | [684751d3db](https://linux-hardware.org/?probe=684751d3db) | May 26, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [a9e0505d3f](https://linux-hardware.org/?probe=a9e0505d3f) | May 26, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [db7d7cf31d](https://linux-hardware.org/?probe=db7d7cf31d) | May 26, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [f757bc2c6e](https://linux-hardware.org/?probe=f757bc2c6e) | May 25, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [8d9c3b024d](https://linux-hardware.org/?probe=8d9c3b024d) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [f876b5169a](https://linux-hardware.org/?probe=f876b5169a) | May 25, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [961a04643c](https://linux-hardware.org/?probe=961a04643c) | May 25, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [86f50d3933](https://linux-hardware.org/?probe=86f50d3933) | May 25, 2023 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [4c9595e6ea](https://linux-hardware.org/?probe=4c9595e6ea) | May 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [fb5edbbd6b](https://linux-hardware.org/?probe=fb5edbbd6b) | May 24, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [00979b3baa](https://linux-hardware.org/?probe=00979b3baa) | May 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d92b2ec905](https://linux-hardware.org/?probe=d92b2ec905) | May 24, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [84d9f5a2cc](https://linux-hardware.org/?probe=84d9f5a2cc) | May 24, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [e6c958dd68](https://linux-hardware.org/?probe=e6c958dd68) | May 24, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [82183f4762](https://linux-hardware.org/?probe=82183f4762) | May 24, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [43069955ee](https://linux-hardware.org/?probe=43069955ee) | May 23, 2023 |
| Toshiba       | Satellite C645D             | Notebook    | [97abd98fdd](https://linux-hardware.org/?probe=97abd98fdd) | May 23, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [e752398b87](https://linux-hardware.org/?probe=e752398b87) | May 23, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e4c9c425f8](https://linux-hardware.org/?probe=e4c9c425f8) | May 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [01c17ab9dc](https://linux-hardware.org/?probe=01c17ab9dc) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6e1c91c725](https://linux-hardware.org/?probe=6e1c91c725) | May 23, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [a5a990a94c](https://linux-hardware.org/?probe=a5a990a94c) | May 23, 2023 |
| HP            | Pavilion 17                 | Notebook    | [eb6c222cf7](https://linux-hardware.org/?probe=eb6c222cf7) | May 23, 2023 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [d0312b1a56](https://linux-hardware.org/?probe=d0312b1a56) | May 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [aa33ddd283](https://linux-hardware.org/?probe=aa33ddd283) | May 23, 2023 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [66b4de8c55](https://linux-hardware.org/?probe=66b4de8c55) | May 22, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [324a8d5c88](https://linux-hardware.org/?probe=324a8d5c88) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [97687a73c3](https://linux-hardware.org/?probe=97687a73c3) | May 22, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5300f7df17](https://linux-hardware.org/?probe=5300f7df17) | May 22, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [179e48239b](https://linux-hardware.org/?probe=179e48239b) | May 22, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a8e6f277e2](https://linux-hardware.org/?probe=a8e6f277e2) | May 22, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [c2d03bd839](https://linux-hardware.org/?probe=c2d03bd839) | May 22, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [88830e9fe8](https://linux-hardware.org/?probe=88830e9fe8) | May 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [cccb529fd3](https://linux-hardware.org/?probe=cccb529fd3) | May 21, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [ca280c2e18](https://linux-hardware.org/?probe=ca280c2e18) | May 21, 2023 |
| MSI           | MPG Z790 EDGE WIFI          | Desktop     | [30e9eb3dd1](https://linux-hardware.org/?probe=30e9eb3dd1) | May 21, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [1e231f6e75](https://linux-hardware.org/?probe=1e231f6e75) | May 21, 2023 |
| HP            | 339A                        | Desktop     | [d4a8f3dbb1](https://linux-hardware.org/?probe=d4a8f3dbb1) | May 21, 2023 |
| Dell          | G3 3500                     | Notebook    | [490bdc1f92](https://linux-hardware.org/?probe=490bdc1f92) | May 21, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [2229714a14](https://linux-hardware.org/?probe=2229714a14) | May 21, 2023 |
| HP            | Laptop 15-dy4xxx            | Notebook    | [d739b1ab41](https://linux-hardware.org/?probe=d739b1ab41) | May 21, 2023 |
| HASEE Comp... | V1x0PNPx                    | Notebook    | [ce5f16dcfe](https://linux-hardware.org/?probe=ce5f16dcfe) | May 20, 2023 |
| ASRock        | 970A-G                      | Desktop     | [fd39b2185b](https://linux-hardware.org/?probe=fd39b2185b) | May 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6bcf177a20](https://linux-hardware.org/?probe=6bcf177a20) | May 20, 2023 |
| HP            | 8437                        | Desktop     | [d41a0c8439](https://linux-hardware.org/?probe=d41a0c8439) | May 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [d82bf9332f](https://linux-hardware.org/?probe=d82bf9332f) | May 20, 2023 |
| ASRock        | 970A-G                      | Desktop     | [fac3e3c961](https://linux-hardware.org/?probe=fac3e3c961) | May 20, 2023 |
| Dell          | Latitude D630               | Notebook    | [d5d56f7183](https://linux-hardware.org/?probe=d5d56f7183) | May 20, 2023 |
| Dell          | Latitude D630               | Notebook    | [af41a1c303](https://linux-hardware.org/?probe=af41a1c303) | May 20, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [d52cf51575](https://linux-hardware.org/?probe=d52cf51575) | May 19, 2023 |
| Lenovo        | ThinkPad X240 20AMA21D00    | Notebook    | [a692a56bc0](https://linux-hardware.org/?probe=a692a56bc0) | May 19, 2023 |
| HP            | 8437                        | Desktop     | [ceacc79bf6](https://linux-hardware.org/?probe=ceacc79bf6) | May 19, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [515e752ecb](https://linux-hardware.org/?probe=515e752ecb) | May 19, 2023 |
| HP            | Unknown                     | Notebook    | [8ae91264ca](https://linux-hardware.org/?probe=8ae91264ca) | May 19, 2023 |
| ASUSTek       | X555LPB                     | Notebook    | [c1082eef21](https://linux-hardware.org/?probe=c1082eef21) | May 18, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | Desktop     | [693c7b6d9b](https://linux-hardware.org/?probe=693c7b6d9b) | May 18, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | Notebook    | [7df5747f30](https://linux-hardware.org/?probe=7df5747f30) | May 18, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f03dddbf42](https://linux-hardware.org/?probe=f03dddbf42) | May 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [25e9a17dd0](https://linux-hardware.org/?probe=25e9a17dd0) | May 18, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | Notebook    | [fdb0fb3d9c](https://linux-hardware.org/?probe=fdb0fb3d9c) | May 18, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [cb6f71a6c4](https://linux-hardware.org/?probe=cb6f71a6c4) | May 18, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [d58889925f](https://linux-hardware.org/?probe=d58889925f) | May 18, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [e0ebac1371](https://linux-hardware.org/?probe=e0ebac1371) | May 18, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [b07c7291d1](https://linux-hardware.org/?probe=b07c7291d1) | May 18, 2023 |
| Dell          | Latitude 5420               | Notebook    | [bd0c08b7b8](https://linux-hardware.org/?probe=bd0c08b7b8) | May 18, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [220fb1cfbc](https://linux-hardware.org/?probe=220fb1cfbc) | May 18, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [aa625a94a0](https://linux-hardware.org/?probe=aa625a94a0) | May 18, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [d23967583a](https://linux-hardware.org/?probe=d23967583a) | May 18, 2023 |
| Acer          | Swift SF315-51G             | Notebook    | [4361a75669](https://linux-hardware.org/?probe=4361a75669) | May 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [42f598550a](https://linux-hardware.org/?probe=42f598550a) | May 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [1a12100c5f](https://linux-hardware.org/?probe=1a12100c5f) | May 17, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [09e723be6f](https://linux-hardware.org/?probe=09e723be6f) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [2df1a28c50](https://linux-hardware.org/?probe=2df1a28c50) | May 17, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ffa28e78e](https://linux-hardware.org/?probe=8ffa28e78e) | May 17, 2023 |
| Emdoor        | AG958                       | Notebook    | [7ff5858830](https://linux-hardware.org/?probe=7ff5858830) | May 17, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [4d1cd4ec12](https://linux-hardware.org/?probe=4d1cd4ec12) | May 17, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [de0485927b](https://linux-hardware.org/?probe=de0485927b) | May 17, 2023 |
| Google        | Cyan                        | Notebook    | [41811cace9](https://linux-hardware.org/?probe=41811cace9) | May 17, 2023 |
| ASUSTek       | P7H55D-M PRO                | Desktop     | [dc1bf86813](https://linux-hardware.org/?probe=dc1bf86813) | May 17, 2023 |
| Dell          | Latitude 5330               | Notebook    | [3cc5328fee](https://linux-hardware.org/?probe=3cc5328fee) | May 16, 2023 |
| GPD           | MicroPC                     | Notebook    | [0da3fc7738](https://linux-hardware.org/?probe=0da3fc7738) | May 16, 2023 |
| Google        | Cyan                        | Notebook    | [65c63caab7](https://linux-hardware.org/?probe=65c63caab7) | May 16, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [377fe6aa67](https://linux-hardware.org/?probe=377fe6aa67) | May 16, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5402CBA... | Notebook    | [170341ae00](https://linux-hardware.org/?probe=170341ae00) | May 15, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [16308738b3](https://linux-hardware.org/?probe=16308738b3) | May 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b788039ba1](https://linux-hardware.org/?probe=b788039ba1) | May 15, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [dc5dd8c32a](https://linux-hardware.org/?probe=dc5dd8c32a) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [5dadcb24d0](https://linux-hardware.org/?probe=5dadcb24d0) | May 15, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [55eb2f47b9](https://linux-hardware.org/?probe=55eb2f47b9) | May 15, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [b938ce8d64](https://linux-hardware.org/?probe=b938ce8d64) | May 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2750a05721](https://linux-hardware.org/?probe=2750a05721) | May 15, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [85c2869727](https://linux-hardware.org/?probe=85c2869727) | May 15, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [66f97c57e2](https://linux-hardware.org/?probe=66f97c57e2) | May 14, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [360db31139](https://linux-hardware.org/?probe=360db31139) | May 14, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [c3bbc544d3](https://linux-hardware.org/?probe=c3bbc544d3) | May 14, 2023 |
| Lenovo        | ThinkPad T570 20H90002GE    | Notebook    | [e6ff63678e](https://linux-hardware.org/?probe=e6ff63678e) | May 14, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [0f70383aab](https://linux-hardware.org/?probe=0f70383aab) | May 14, 2023 |
| Gigabyte      | Z170X-UD5 TH-CF             | Desktop     | [6a84af6428](https://linux-hardware.org/?probe=6a84af6428) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [ba47df6545](https://linux-hardware.org/?probe=ba47df6545) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [0b6c34eefa](https://linux-hardware.org/?probe=0b6c34eefa) | May 14, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [fe36fee27a](https://linux-hardware.org/?probe=fe36fee27a) | May 14, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [b9f9ed1b25](https://linux-hardware.org/?probe=b9f9ed1b25) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [92c052d9b4](https://linux-hardware.org/?probe=92c052d9b4) | May 14, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [6bfe747b4d](https://linux-hardware.org/?probe=6bfe747b4d) | May 13, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7a38cda53d](https://linux-hardware.org/?probe=7a38cda53d) | May 13, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2c03c64f49](https://linux-hardware.org/?probe=2c03c64f49) | May 13, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [e5dbe4c6f4](https://linux-hardware.org/?probe=e5dbe4c6f4) | May 13, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [0a23198016](https://linux-hardware.org/?probe=0a23198016) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [1146828988](https://linux-hardware.org/?probe=1146828988) | May 13, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [4b296f5c40](https://linux-hardware.org/?probe=4b296f5c40) | May 12, 2023 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [f1884eebc6](https://linux-hardware.org/?probe=f1884eebc6) | May 12, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [16782746d8](https://linux-hardware.org/?probe=16782746d8) | May 12, 2023 |
| ASRock        | A320M/ac                    | Desktop     | [c244810475](https://linux-hardware.org/?probe=c244810475) | May 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [713564ccd4](https://linux-hardware.org/?probe=713564ccd4) | May 12, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [ff26b44641](https://linux-hardware.org/?probe=ff26b44641) | May 12, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [00abecb77e](https://linux-hardware.org/?probe=00abecb77e) | May 12, 2023 |
| Dell          | Latitude 7390               | Notebook    | [cbd8c5fdbe](https://linux-hardware.org/?probe=cbd8c5fdbe) | May 12, 2023 |
| Dell          | Latitude 7390               | Notebook    | [5677bfdac5](https://linux-hardware.org/?probe=5677bfdac5) | May 12, 2023 |
| Medion        | Crawler E40                 | Notebook    | [d0df38a2da](https://linux-hardware.org/?probe=d0df38a2da) | May 12, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [cfa81980a9](https://linux-hardware.org/?probe=cfa81980a9) | May 12, 2023 |
| Medion        | Crawler E40                 | Notebook    | [c58193ce55](https://linux-hardware.org/?probe=c58193ce55) | May 12, 2023 |
| Dell          | Latitude 7400               | Notebook    | [c8ce2e462f](https://linux-hardware.org/?probe=c8ce2e462f) | May 11, 2023 |
| Huanan        | X99-F8 Gaming 2021          | Desktop     | [fb4cf864f2](https://linux-hardware.org/?probe=fb4cf864f2) | May 11, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | Notebook    | [38acb76489](https://linux-hardware.org/?probe=38acb76489) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [79d149ff5c](https://linux-hardware.org/?probe=79d149ff5c) | May 11, 2023 |
| Dell          | Latitude 5480               | Notebook    | [eb671ee7d2](https://linux-hardware.org/?probe=eb671ee7d2) | May 11, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [928216a0a5](https://linux-hardware.org/?probe=928216a0a5) | May 10, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [39dd8fc09a](https://linux-hardware.org/?probe=39dd8fc09a) | May 10, 2023 |
| Microsoft     | Surface Book 2              | Tablet      | [aaa0837c89](https://linux-hardware.org/?probe=aaa0837c89) | May 10, 2023 |
| Lenovo        | ThinkPad T450s 20BWS34A0... | Notebook    | [775c2839fa](https://linux-hardware.org/?probe=775c2839fa) | May 10, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [bd5c79fbaf](https://linux-hardware.org/?probe=bd5c79fbaf) | May 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [47fea42b65](https://linux-hardware.org/?probe=47fea42b65) | May 09, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [0a1c43b710](https://linux-hardware.org/?probe=0a1c43b710) | May 09, 2023 |
| MSI           | PS42 Modern 8RA             | Notebook    | [8371e35044](https://linux-hardware.org/?probe=8371e35044) | May 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d51304433e](https://linux-hardware.org/?probe=d51304433e) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [5cbf24306a](https://linux-hardware.org/?probe=5cbf24306a) | May 08, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [8849d7a1c9](https://linux-hardware.org/?probe=8849d7a1c9) | May 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a4f5dce6d6](https://linux-hardware.org/?probe=a4f5dce6d6) | May 08, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [2cbff804d8](https://linux-hardware.org/?probe=2cbff804d8) | May 08, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [bbf20cfdad](https://linux-hardware.org/?probe=bbf20cfdad) | May 08, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [9e3f14cf8d](https://linux-hardware.org/?probe=9e3f14cf8d) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [679f0c2f88](https://linux-hardware.org/?probe=679f0c2f88) | May 07, 2023 |
| MSI           | GV63 8SE                    | Notebook    | [55bfa86f43](https://linux-hardware.org/?probe=55bfa86f43) | May 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [ecfcb0cab6](https://linux-hardware.org/?probe=ecfcb0cab6) | May 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [af9591cedc](https://linux-hardware.org/?probe=af9591cedc) | May 07, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [df056ec6f1](https://linux-hardware.org/?probe=df056ec6f1) | May 07, 2023 |
| MSI           | 970A-G46                    | Desktop     | [37f3da239a](https://linux-hardware.org/?probe=37f3da239a) | May 07, 2023 |
| ASUSTek       | M4N72-E                     | Desktop     | [30deed8e5a](https://linux-hardware.org/?probe=30deed8e5a) | May 07, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [fd7a2486f2](https://linux-hardware.org/?probe=fd7a2486f2) | May 07, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [dc317ab270](https://linux-hardware.org/?probe=dc317ab270) | May 06, 2023 |
| Dell          | Precision 7720              | Notebook    | [9e0a1bd8ef](https://linux-hardware.org/?probe=9e0a1bd8ef) | May 06, 2023 |
| Toshiba       | Satellite C855              | Notebook    | [775c7346eb](https://linux-hardware.org/?probe=775c7346eb) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [9a510bb01b](https://linux-hardware.org/?probe=9a510bb01b) | May 06, 2023 |
| Dell          | Precision 7550              | Notebook    | [5f962aaea0](https://linux-hardware.org/?probe=5f962aaea0) | May 06, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [a5252d48f3](https://linux-hardware.org/?probe=a5252d48f3) | May 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [2e02937097](https://linux-hardware.org/?probe=2e02937097) | May 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [051da44921](https://linux-hardware.org/?probe=051da44921) | May 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [c99531c4e3](https://linux-hardware.org/?probe=c99531c4e3) | May 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [3c8f9ed664](https://linux-hardware.org/?probe=3c8f9ed664) | May 06, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [756e372a11](https://linux-hardware.org/?probe=756e372a11) | May 06, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b4f013c967](https://linux-hardware.org/?probe=b4f013c967) | May 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [f2d8df2880](https://linux-hardware.org/?probe=f2d8df2880) | May 05, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [b8f920797f](https://linux-hardware.org/?probe=b8f920797f) | May 05, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [9b013ebf89](https://linux-hardware.org/?probe=9b013ebf89) | May 05, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [2b273ee426](https://linux-hardware.org/?probe=2b273ee426) | May 05, 2023 |
| Lenovo        | ThinkPad X131e 33712MU      | Notebook    | [6957336ed7](https://linux-hardware.org/?probe=6957336ed7) | May 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5f4447aa45](https://linux-hardware.org/?probe=5f4447aa45) | May 05, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [907a94ae07](https://linux-hardware.org/?probe=907a94ae07) | May 05, 2023 |
| MSI           | GV63 8SE                    | Notebook    | [1c78e3feb9](https://linux-hardware.org/?probe=1c78e3feb9) | May 05, 2023 |
| Dell          | 04HJX8 A00                  | All in one  | [d7ed216be7](https://linux-hardware.org/?probe=d7ed216be7) | May 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [bd885c202d](https://linux-hardware.org/?probe=bd885c202d) | May 05, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [4124bb2dde](https://linux-hardware.org/?probe=4124bb2dde) | May 04, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [a799667521](https://linux-hardware.org/?probe=a799667521) | May 04, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [44c5b43b8d](https://linux-hardware.org/?probe=44c5b43b8d) | May 04, 2023 |
| Quanta        | UW3 TBD                     | Notebook    | [0c951d032e](https://linux-hardware.org/?probe=0c951d032e) | May 04, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [0501f3a43b](https://linux-hardware.org/?probe=0501f3a43b) | May 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7d642208ec](https://linux-hardware.org/?probe=7d642208ec) | May 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e31ba8f396](https://linux-hardware.org/?probe=e31ba8f396) | May 04, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [ec8586e070](https://linux-hardware.org/?probe=ec8586e070) | May 04, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [abc1819fc1](https://linux-hardware.org/?probe=abc1819fc1) | May 04, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [e42327b375](https://linux-hardware.org/?probe=e42327b375) | May 04, 2023 |
| HP            | Spectre x360 Convertible    | Convertible | [a695d92fbc](https://linux-hardware.org/?probe=a695d92fbc) | May 04, 2023 |
| Lenovo        | B490 37722XP                | Notebook    | [62808a2dee](https://linux-hardware.org/?probe=62808a2dee) | May 04, 2023 |
| Quanta        | UW3 TBD                     | Notebook    | [c138f57a47](https://linux-hardware.org/?probe=c138f57a47) | May 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [02df3a407e](https://linux-hardware.org/?probe=02df3a407e) | May 03, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [f677ec7e51](https://linux-hardware.org/?probe=f677ec7e51) | May 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [df62d15ecc](https://linux-hardware.org/?probe=df62d15ecc) | May 03, 2023 |
| Timi          | Xiaomi Book Air 13 2022     | Convertible | [dc5bb44710](https://linux-hardware.org/?probe=dc5bb44710) | May 03, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [aac11fced2](https://linux-hardware.org/?probe=aac11fced2) | May 03, 2023 |
| Timi          | Xiaomi Book Air 13 2022     | Convertible | [8cf5ba1b0c](https://linux-hardware.org/?probe=8cf5ba1b0c) | May 03, 2023 |
| Acer          | Predator G9-793             | Notebook    | [b3bd1a1031](https://linux-hardware.org/?probe=b3bd1a1031) | May 03, 2023 |
| Samsung       | 750XDA                      | Notebook    | [2e99c882ff](https://linux-hardware.org/?probe=2e99c882ff) | May 03, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [7c56fae21c](https://linux-hardware.org/?probe=7c56fae21c) | May 03, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [50f922927f](https://linux-hardware.org/?probe=50f922927f) | May 03, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [66d8e4a703](https://linux-hardware.org/?probe=66d8e4a703) | May 02, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [c8b7ffa6dc](https://linux-hardware.org/?probe=c8b7ffa6dc) | May 02, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [26bb61d72f](https://linux-hardware.org/?probe=26bb61d72f) | May 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [ae3ef173a7](https://linux-hardware.org/?probe=ae3ef173a7) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [2a4cf994ac](https://linux-hardware.org/?probe=2a4cf994ac) | May 02, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [abd1474dfc](https://linux-hardware.org/?probe=abd1474dfc) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8fea3db366](https://linux-hardware.org/?probe=8fea3db366) | May 02, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [9035ec79cd](https://linux-hardware.org/?probe=9035ec79cd) | May 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [f28e109a4b](https://linux-hardware.org/?probe=f28e109a4b) | May 02, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [a5ac1bf5b4](https://linux-hardware.org/?probe=a5ac1bf5b4) | May 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ecc18e59bc](https://linux-hardware.org/?probe=ecc18e59bc) | May 01, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [c2dcdb892d](https://linux-hardware.org/?probe=c2dcdb892d) | May 01, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [56542de280](https://linux-hardware.org/?probe=56542de280) | May 01, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [8fb29cf081](https://linux-hardware.org/?probe=8fb29cf081) | May 01, 2023 |
| Dell          | Inspiron 5458               | Notebook    | [c38d3e6513](https://linux-hardware.org/?probe=c38d3e6513) | May 01, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [3fc2c4e9d9](https://linux-hardware.org/?probe=3fc2c4e9d9) | May 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [dd0a47b6fc](https://linux-hardware.org/?probe=dd0a47b6fc) | May 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [7087295cd7](https://linux-hardware.org/?probe=7087295cd7) | May 01, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [6b61472a4a](https://linux-hardware.org/?probe=6b61472a4a) | May 01, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [0aa17c06c5](https://linux-hardware.org/?probe=0aa17c06c5) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [bd460bdc62](https://linux-hardware.org/?probe=bd460bdc62) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [edfcd7daa6](https://linux-hardware.org/?probe=edfcd7daa6) | Apr 30, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [3c321c476a](https://linux-hardware.org/?probe=3c321c476a) | Apr 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [408aa18a63](https://linux-hardware.org/?probe=408aa18a63) | Apr 30, 2023 |
| MSI           | B360M MORTAR                | Desktop     | [352a47b8a0](https://linux-hardware.org/?probe=352a47b8a0) | Apr 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [df9cc0160a](https://linux-hardware.org/?probe=df9cc0160a) | Apr 30, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [2f3308a2ee](https://linux-hardware.org/?probe=2f3308a2ee) | Apr 29, 2023 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [19bb30e27a](https://linux-hardware.org/?probe=19bb30e27a) | Apr 29, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [4a8b2ebf8a](https://linux-hardware.org/?probe=4a8b2ebf8a) | Apr 29, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | Notebook    | [34420e9478](https://linux-hardware.org/?probe=34420e9478) | Apr 28, 2023 |
| ASUSTek       | S550CM                      | Notebook    | [068365f788](https://linux-hardware.org/?probe=068365f788) | Apr 28, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [c53a69bd72](https://linux-hardware.org/?probe=c53a69bd72) | Apr 28, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [2de1d6f6f5](https://linux-hardware.org/?probe=2de1d6f6f5) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [96194bc912](https://linux-hardware.org/?probe=96194bc912) | Apr 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5d0819f25c](https://linux-hardware.org/?probe=5d0819f25c) | Apr 28, 2023 |
| Dell          | 0XNNCJ A03                  | Server      | [ad555bfde2](https://linux-hardware.org/?probe=ad555bfde2) | Apr 27, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [6926565982](https://linux-hardware.org/?probe=6926565982) | Apr 27, 2023 |
| HP            | 82F2 A01                    | Desktop     | [ea8f7364db](https://linux-hardware.org/?probe=ea8f7364db) | Apr 27, 2023 |
| ASRock        | A330GC                      | Desktop     | [d1a2e8dd13](https://linux-hardware.org/?probe=d1a2e8dd13) | Apr 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [640a71aea3](https://linux-hardware.org/?probe=640a71aea3) | Apr 27, 2023 |
| Dell          | Latitude 7420               | Notebook    | [7ceeb888fd](https://linux-hardware.org/?probe=7ceeb888fd) | Apr 27, 2023 |
| Dell          | Latitude E5440              | Notebook    | [0217386dbe](https://linux-hardware.org/?probe=0217386dbe) | Apr 27, 2023 |
| Sony          | SVE11113FXW                 | Notebook    | [248c7717a4](https://linux-hardware.org/?probe=248c7717a4) | Apr 26, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [4e1caf5a7a](https://linux-hardware.org/?probe=4e1caf5a7a) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [62996d1f05](https://linux-hardware.org/?probe=62996d1f05) | Apr 26, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [1ce9a878f3](https://linux-hardware.org/?probe=1ce9a878f3) | Apr 26, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [bd406c08f8](https://linux-hardware.org/?probe=bd406c08f8) | Apr 25, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [50930ebe57](https://linux-hardware.org/?probe=50930ebe57) | Apr 25, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [bf207e9dc3](https://linux-hardware.org/?probe=bf207e9dc3) | Apr 25, 2023 |
| MSI           | Prestige 14 A12UC           | Notebook    | [137a3623dc](https://linux-hardware.org/?probe=137a3623dc) | Apr 25, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [b3a3115f0c](https://linux-hardware.org/?probe=b3a3115f0c) | Apr 25, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [7595e7d8f9](https://linux-hardware.org/?probe=7595e7d8f9) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [3f8b64c10c](https://linux-hardware.org/?probe=3f8b64c10c) | Apr 25, 2023 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [ecb3270b4a](https://linux-hardware.org/?probe=ecb3270b4a) | Apr 24, 2023 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [d1a5ad5a38](https://linux-hardware.org/?probe=d1a5ad5a38) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b4b468d0db](https://linux-hardware.org/?probe=b4b468d0db) | Apr 24, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [34278ef67e](https://linux-hardware.org/?probe=34278ef67e) | Apr 24, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [78686e5784](https://linux-hardware.org/?probe=78686e5784) | Apr 24, 2023 |
| Acer          | One S1003                   | Tablet      | [140992e52d](https://linux-hardware.org/?probe=140992e52d) | Apr 24, 2023 |
| Intel         | HM570                       | Desktop     | [1220357b3d](https://linux-hardware.org/?probe=1220357b3d) | Apr 24, 2023 |
| HP            | 240 G4                      | Notebook    | [997e6e6a0b](https://linux-hardware.org/?probe=997e6e6a0b) | Apr 24, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [f76dc1b9b7](https://linux-hardware.org/?probe=f76dc1b9b7) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [6cacf7a9f9](https://linux-hardware.org/?probe=6cacf7a9f9) | Apr 24, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [c11ea1fc19](https://linux-hardware.org/?probe=c11ea1fc19) | Apr 23, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [1a316c62a1](https://linux-hardware.org/?probe=1a316c62a1) | Apr 23, 2023 |
| Notebook      | N15_N17RD1                  | Notebook    | [8bba7a7447](https://linux-hardware.org/?probe=8bba7a7447) | Apr 23, 2023 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [0be1fdd77a](https://linux-hardware.org/?probe=0be1fdd77a) | Apr 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [52001c8ac6](https://linux-hardware.org/?probe=52001c8ac6) | Apr 23, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [b18f893905](https://linux-hardware.org/?probe=b18f893905) | Apr 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [5ecd3ed1bd](https://linux-hardware.org/?probe=5ecd3ed1bd) | Apr 23, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [332429fc14](https://linux-hardware.org/?probe=332429fc14) | Apr 23, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [ef59f5ff9b](https://linux-hardware.org/?probe=ef59f5ff9b) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [dfb9f87dad](https://linux-hardware.org/?probe=dfb9f87dad) | Apr 22, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [72088721ec](https://linux-hardware.org/?probe=72088721ec) | Apr 22, 2023 |
| HP            | 240 G4                      | Notebook    | [887b406c56](https://linux-hardware.org/?probe=887b406c56) | Apr 22, 2023 |
| ASRock        | H61M/U3S3                   | Desktop     | [8fd7aea5ea](https://linux-hardware.org/?probe=8fd7aea5ea) | Apr 22, 2023 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [5eb2235e10](https://linux-hardware.org/?probe=5eb2235e10) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0de425d51e](https://linux-hardware.org/?probe=0de425d51e) | Apr 21, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [1de5b776a3](https://linux-hardware.org/?probe=1de5b776a3) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [3f01c5df6e](https://linux-hardware.org/?probe=3f01c5df6e) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [a5ef39681b](https://linux-hardware.org/?probe=a5ef39681b) | Apr 21, 2023 |
| HP            | 15                          | Notebook    | [4f563db114](https://linux-hardware.org/?probe=4f563db114) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP47... | Convertible | [e76fb532be](https://linux-hardware.org/?probe=e76fb532be) | Apr 21, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [a7b05c2528](https://linux-hardware.org/?probe=a7b05c2528) | Apr 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [a0ee1dbeff](https://linux-hardware.org/?probe=a0ee1dbeff) | Apr 20, 2023 |
| Lenovo        | 300e 2nd Gen 82GK           | Convertible | [54c7413bc5](https://linux-hardware.org/?probe=54c7413bc5) | Apr 20, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [68e853f4c1](https://linux-hardware.org/?probe=68e853f4c1) | Apr 20, 2023 |
| Intel         | X79-SERVER V1.1             | Desktop     | [384c50e703](https://linux-hardware.org/?probe=384c50e703) | Apr 20, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [509d9126e1](https://linux-hardware.org/?probe=509d9126e1) | Apr 19, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [83b48fff59](https://linux-hardware.org/?probe=83b48fff59) | Apr 19, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [5d27011671](https://linux-hardware.org/?probe=5d27011671) | Apr 19, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [35534cbfba](https://linux-hardware.org/?probe=35534cbfba) | Apr 19, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [433c482314](https://linux-hardware.org/?probe=433c482314) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [be217cbc1e](https://linux-hardware.org/?probe=be217cbc1e) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d5e90c4b14](https://linux-hardware.org/?probe=d5e90c4b14) | Apr 19, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [ed5cdbbcd0](https://linux-hardware.org/?probe=ed5cdbbcd0) | Apr 18, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [c00d85072e](https://linux-hardware.org/?probe=c00d85072e) | Apr 18, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [146c678131](https://linux-hardware.org/?probe=146c678131) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d1d3cf9928](https://linux-hardware.org/?probe=d1d3cf9928) | Apr 17, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [786daebed0](https://linux-hardware.org/?probe=786daebed0) | Apr 17, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [65a5b3f43d](https://linux-hardware.org/?probe=65a5b3f43d) | Apr 17, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [39106da598](https://linux-hardware.org/?probe=39106da598) | Apr 17, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [40b6c3bad6](https://linux-hardware.org/?probe=40b6c3bad6) | Apr 17, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [b715989fc4](https://linux-hardware.org/?probe=b715989fc4) | Apr 16, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [213ac87204](https://linux-hardware.org/?probe=213ac87204) | Apr 16, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [7820a9b7bc](https://linux-hardware.org/?probe=7820a9b7bc) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4375bd0fb6](https://linux-hardware.org/?probe=4375bd0fb6) | Apr 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fc41269cf8](https://linux-hardware.org/?probe=fc41269cf8) | Apr 16, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8d18a06897](https://linux-hardware.org/?probe=8d18a06897) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9b05d61f11](https://linux-hardware.org/?probe=9b05d61f11) | Apr 16, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [040d876c1e](https://linux-hardware.org/?probe=040d876c1e) | Apr 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6S... | Notebook    | [6686a91041](https://linux-hardware.org/?probe=6686a91041) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [9b23be6c48](https://linux-hardware.org/?probe=9b23be6c48) | Apr 16, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [5ce7874f2e](https://linux-hardware.org/?probe=5ce7874f2e) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2fcbae14f2](https://linux-hardware.org/?probe=2fcbae14f2) | Apr 16, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [fff7f3dd1f](https://linux-hardware.org/?probe=fff7f3dd1f) | Apr 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [71e03c5459](https://linux-hardware.org/?probe=71e03c5459) | Apr 15, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d582f92277](https://linux-hardware.org/?probe=d582f92277) | Apr 15, 2023 |
| Lenovo        | ThinkPad P52 20MAS1LH00     | Notebook    | [06ba20dc47](https://linux-hardware.org/?probe=06ba20dc47) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [e9e05a1bb3](https://linux-hardware.org/?probe=e9e05a1bb3) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [0b4fdfd30e](https://linux-hardware.org/?probe=0b4fdfd30e) | Apr 15, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [0f678c5ded](https://linux-hardware.org/?probe=0f678c5ded) | Apr 15, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [ee48e89e45](https://linux-hardware.org/?probe=ee48e89e45) | Apr 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [57cc389eff](https://linux-hardware.org/?probe=57cc389eff) | Apr 14, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [c7b7e028e4](https://linux-hardware.org/?probe=c7b7e028e4) | Apr 14, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [e0ad93045c](https://linux-hardware.org/?probe=e0ad93045c) | Apr 14, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [f604f6e212](https://linux-hardware.org/?probe=f604f6e212) | Apr 14, 2023 |
| Biostar       | G31D-M7                     | Desktop     | [bb518a8623](https://linux-hardware.org/?probe=bb518a8623) | Apr 14, 2023 |
| Dell          | Latitude 9420               | Notebook    | [529aa83bbc](https://linux-hardware.org/?probe=529aa83bbc) | Apr 14, 2023 |
| Avell High... | B.ON                        | Notebook    | [0ac252a73b](https://linux-hardware.org/?probe=0ac252a73b) | Apr 14, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [9a4bce918e](https://linux-hardware.org/?probe=9a4bce918e) | Apr 14, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [71d89005dd](https://linux-hardware.org/?probe=71d89005dd) | Apr 14, 2023 |
| System76      | Pangolin                    | Notebook    | [b5dd9f13b9](https://linux-hardware.org/?probe=b5dd9f13b9) | Apr 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [03e40fe2cd](https://linux-hardware.org/?probe=03e40fe2cd) | Apr 14, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [9f723bfac9](https://linux-hardware.org/?probe=9f723bfac9) | Apr 14, 2023 |
| System76      | Pangolin                    | Notebook    | [a1a17fa4c4](https://linux-hardware.org/?probe=a1a17fa4c4) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [7ae190d0be](https://linux-hardware.org/?probe=7ae190d0be) | Apr 14, 2023 |
| Lenovo        | ThinkPad T460 20FMS0E22C    | Notebook    | [ee911053e5](https://linux-hardware.org/?probe=ee911053e5) | Apr 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [62dd8e069f](https://linux-hardware.org/?probe=62dd8e069f) | Apr 13, 2023 |
| MSI           | Prestige 14 A12UC           | Notebook    | [43e044c37a](https://linux-hardware.org/?probe=43e044c37a) | Apr 13, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [3364cf411c](https://linux-hardware.org/?probe=3364cf411c) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [1280936eba](https://linux-hardware.org/?probe=1280936eba) | Apr 13, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [8e641b5fd5](https://linux-hardware.org/?probe=8e641b5fd5) | Apr 13, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [c639e22b34](https://linux-hardware.org/?probe=c639e22b34) | Apr 13, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [b6cd64a19b](https://linux-hardware.org/?probe=b6cd64a19b) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [82bfc450e9](https://linux-hardware.org/?probe=82bfc450e9) | Apr 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | Notebook    | [6406153cbf](https://linux-hardware.org/?probe=6406153cbf) | Apr 12, 2023 |
| Dell          | XPS 9315                    | Notebook    | [20fa2b86b9](https://linux-hardware.org/?probe=20fa2b86b9) | Apr 12, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [796f3afe73](https://linux-hardware.org/?probe=796f3afe73) | Apr 12, 2023 |
| Dell          | Latitude E7440              | Notebook    | [4cfe81f687](https://linux-hardware.org/?probe=4cfe81f687) | Apr 12, 2023 |
| Toshiba       | Satellite S50-B             | Notebook    | [e9d26a9e89](https://linux-hardware.org/?probe=e9d26a9e89) | Apr 12, 2023 |
| Acer          | WG43M                       | Desktop     | [e22afb229d](https://linux-hardware.org/?probe=e22afb229d) | Apr 12, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [6bec4cb4a8](https://linux-hardware.org/?probe=6bec4cb4a8) | Apr 12, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [0daac07546](https://linux-hardware.org/?probe=0daac07546) | Apr 12, 2023 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2a108e9eed](https://linux-hardware.org/?probe=2a108e9eed) | Apr 11, 2023 |
| HP            | Laptop 14s-cr0xxx           | Notebook    | [f95d67a702](https://linux-hardware.org/?probe=f95d67a702) | Apr 10, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [c31f7b3b5c](https://linux-hardware.org/?probe=c31f7b3b5c) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [649a715fba](https://linux-hardware.org/?probe=649a715fba) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [39c6b4afbe](https://linux-hardware.org/?probe=39c6b4afbe) | Apr 10, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fff8cbca92](https://linux-hardware.org/?probe=fff8cbca92) | Apr 10, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [e762a4eb1d](https://linux-hardware.org/?probe=e762a4eb1d) | Apr 09, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [69ee985017](https://linux-hardware.org/?probe=69ee985017) | Apr 09, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [709cc4af2c](https://linux-hardware.org/?probe=709cc4af2c) | Apr 09, 2023 |
| Google        | Phaser360                   | Notebook    | [64953bc26c](https://linux-hardware.org/?probe=64953bc26c) | Apr 09, 2023 |
| Avell High... | A52 HYB                     | Notebook    | [7da3b9f780](https://linux-hardware.org/?probe=7da3b9f780) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [cc25df15df](https://linux-hardware.org/?probe=cc25df15df) | Apr 08, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [44351926f8](https://linux-hardware.org/?probe=44351926f8) | Apr 08, 2023 |
| Lenovo        | ThinkPad 10 20C1002PUK      | Tablet      | [1133b0413b](https://linux-hardware.org/?probe=1133b0413b) | Apr 08, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [5cf4615347](https://linux-hardware.org/?probe=5cf4615347) | Apr 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [08f117749f](https://linux-hardware.org/?probe=08f117749f) | Apr 08, 2023 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | Notebook    | [772414cda4](https://linux-hardware.org/?probe=772414cda4) | Apr 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | Notebook    | [ae8c333d72](https://linux-hardware.org/?probe=ae8c333d72) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [e7ba943509](https://linux-hardware.org/?probe=e7ba943509) | Apr 07, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [1927fa08d1](https://linux-hardware.org/?probe=1927fa08d1) | Apr 07, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [123883b7dd](https://linux-hardware.org/?probe=123883b7dd) | Apr 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2532af42ba](https://linux-hardware.org/?probe=2532af42ba) | Apr 06, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [afdf8d46a2](https://linux-hardware.org/?probe=afdf8d46a2) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a02839d653](https://linux-hardware.org/?probe=a02839d653) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [80bd0aed09](https://linux-hardware.org/?probe=80bd0aed09) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [712e78de35](https://linux-hardware.org/?probe=712e78de35) | Apr 05, 2023 |
| Timi          | RedmiBook Pro 15            | Notebook    | [4eb4d46bfc](https://linux-hardware.org/?probe=4eb4d46bfc) | Apr 05, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [fef3cbc941](https://linux-hardware.org/?probe=fef3cbc941) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0b4faaa32e](https://linux-hardware.org/?probe=0b4faaa32e) | Apr 05, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [3f750a4d82](https://linux-hardware.org/?probe=3f750a4d82) | Apr 05, 2023 |
| Alienware     | M17xR3                      | Notebook    | [514f79bd8e](https://linux-hardware.org/?probe=514f79bd8e) | Apr 05, 2023 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [f211babaa5](https://linux-hardware.org/?probe=f211babaa5) | Apr 04, 2023 |
| Acer          | AO756                       | Notebook    | [4e33479949](https://linux-hardware.org/?probe=4e33479949) | Apr 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a467a04489](https://linux-hardware.org/?probe=a467a04489) | Apr 04, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [c529f9d1cc](https://linux-hardware.org/?probe=c529f9d1cc) | Apr 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [b9a98e8656](https://linux-hardware.org/?probe=b9a98e8656) | Apr 03, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [d2850d3f77](https://linux-hardware.org/?probe=d2850d3f77) | Apr 03, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3a87280f55](https://linux-hardware.org/?probe=3a87280f55) | Apr 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [fc89f163b0](https://linux-hardware.org/?probe=fc89f163b0) | Apr 03, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [1cb5977d82](https://linux-hardware.org/?probe=1cb5977d82) | Apr 03, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [416152a691](https://linux-hardware.org/?probe=416152a691) | Apr 03, 2023 |
| Prestigio     | PSB133S01ZFH                | Notebook    | [ba6746febf](https://linux-hardware.org/?probe=ba6746febf) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | Notebook    | [85e0077c83](https://linux-hardware.org/?probe=85e0077c83) | Apr 03, 2023 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [e3eb0fe882](https://linux-hardware.org/?probe=e3eb0fe882) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8f8d89fe9a](https://linux-hardware.org/?probe=8f8d89fe9a) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a5d404ca3d](https://linux-hardware.org/?probe=a5d404ca3d) | Apr 02, 2023 |
| Toxic         | GM5MPHY                     | Notebook    | [9ce64fb49a](https://linux-hardware.org/?probe=9ce64fb49a) | Apr 02, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [b4207e264f](https://linux-hardware.org/?probe=b4207e264f) | Apr 02, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7bfb9086ab](https://linux-hardware.org/?probe=7bfb9086ab) | Apr 02, 2023 |
| Lenovo        | ThinkPad E480 20KQS0B800    | Notebook    | [9c9b561ca2](https://linux-hardware.org/?probe=9c9b561ca2) | Apr 02, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [c7791aac7c](https://linux-hardware.org/?probe=c7791aac7c) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| ASUSTek       | P8H67-V                     | Desktop     | [3a488490ce](https://linux-hardware.org/?probe=3a488490ce) | Apr 02, 2023 |
| Google        | Snappy                      | Notebook    | [6ca49159d2](https://linux-hardware.org/?probe=6ca49159d2) | Apr 01, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [015b741441](https://linux-hardware.org/?probe=015b741441) | Apr 01, 2023 |
| AZW           | MINI S 10                   | Desktop     | [19d66110ff](https://linux-hardware.org/?probe=19d66110ff) | Apr 01, 2023 |
| Schenker      | S405                        | Notebook    | [6d89f7e662](https://linux-hardware.org/?probe=6d89f7e662) | Apr 01, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [3a042b5160](https://linux-hardware.org/?probe=3a042b5160) | Apr 01, 2023 |
| ASUSTek       | X550LB                      | Notebook    | [3d35ff8b68](https://linux-hardware.org/?probe=3d35ff8b68) | Apr 01, 2023 |
| MSI           | P43T-C51                    | Desktop     | [d16b44b442](https://linux-hardware.org/?probe=d16b44b442) | Apr 01, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [32bdbfa581](https://linux-hardware.org/?probe=32bdbfa581) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [4057e0c5e9](https://linux-hardware.org/?probe=4057e0c5e9) | Apr 01, 2023 |
| HP            | Notebook                    | Notebook    | [7cb279c8e0](https://linux-hardware.org/?probe=7cb279c8e0) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [59c335754f](https://linux-hardware.org/?probe=59c335754f) | Apr 01, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [53717700a1](https://linux-hardware.org/?probe=53717700a1) | Mar 31, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [5d0a908832](https://linux-hardware.org/?probe=5d0a908832) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [8326806aa6](https://linux-hardware.org/?probe=8326806aa6) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [4d69417ed0](https://linux-hardware.org/?probe=4d69417ed0) | Mar 31, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [1063ba3fb9](https://linux-hardware.org/?probe=1063ba3fb9) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e2c6f05595](https://linux-hardware.org/?probe=e2c6f05595) | Mar 31, 2023 |
| ASRock        | B550M-C                     | Desktop     | [c0fcfbc0ed](https://linux-hardware.org/?probe=c0fcfbc0ed) | Mar 31, 2023 |
| ASRock        | H67DE3                      | Desktop     | [b055ccc048](https://linux-hardware.org/?probe=b055ccc048) | Mar 31, 2023 |
| ASRock        | H67DE3                      | Desktop     | [c82ba90d70](https://linux-hardware.org/?probe=c82ba90d70) | Mar 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [0ab4f4cd55](https://linux-hardware.org/?probe=0ab4f4cd55) | Mar 31, 2023 |
| Gigabyte      | Z390 M-CF                   | Desktop     | [6bce2b9bc3](https://linux-hardware.org/?probe=6bce2b9bc3) | Mar 31, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [6915349237](https://linux-hardware.org/?probe=6915349237) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [ebd6135034](https://linux-hardware.org/?probe=ebd6135034) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [88864f0e2d](https://linux-hardware.org/?probe=88864f0e2d) | Mar 31, 2023 |
| Acer          | WG43M                       | Desktop     | [3b626d2ff9](https://linux-hardware.org/?probe=3b626d2ff9) | Mar 31, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [9e43a17d1a](https://linux-hardware.org/?probe=9e43a17d1a) | Mar 30, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | Notebook    | [2e8eab25be](https://linux-hardware.org/?probe=2e8eab25be) | Mar 30, 2023 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [b593e25f2a](https://linux-hardware.org/?probe=b593e25f2a) | Mar 30, 2023 |
| Intel         | DQ45CB E30148-207           | Desktop     | [e47e1626c3](https://linux-hardware.org/?probe=e47e1626c3) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [d96583e702](https://linux-hardware.org/?probe=d96583e702) | Mar 29, 2023 |
| IP3 Tech      | IB8                         | Desktop     | [c12033f9e7](https://linux-hardware.org/?probe=c12033f9e7) | Mar 29, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [e9b1759970](https://linux-hardware.org/?probe=e9b1759970) | Mar 29, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [f6357798c5](https://linux-hardware.org/?probe=f6357798c5) | Mar 28, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [0a1739f44c](https://linux-hardware.org/?probe=0a1739f44c) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d1e1b40549](https://linux-hardware.org/?probe=d1e1b40549) | Mar 28, 2023 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [4a7e7763c1](https://linux-hardware.org/?probe=4a7e7763c1) | Mar 28, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [4b16a78f3e](https://linux-hardware.org/?probe=4b16a78f3e) | Mar 28, 2023 |
| Dell          | Inspiron 16 5630            | Notebook    | [5838554410](https://linux-hardware.org/?probe=5838554410) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [60012fd503](https://linux-hardware.org/?probe=60012fd503) | Mar 27, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [b62f0eaa0e](https://linux-hardware.org/?probe=b62f0eaa0e) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [54f096fd88](https://linux-hardware.org/?probe=54f096fd88) | Mar 27, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [29ec74ac8b](https://linux-hardware.org/?probe=29ec74ac8b) | Mar 27, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [cebc7c547a](https://linux-hardware.org/?probe=cebc7c547a) | Mar 26, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [4391dcbdd2](https://linux-hardware.org/?probe=4391dcbdd2) | Mar 26, 2023 |
| Acer          | WG43M                       | Desktop     | [74320e2d13](https://linux-hardware.org/?probe=74320e2d13) | Mar 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cba16003d7](https://linux-hardware.org/?probe=cba16003d7) | Mar 26, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [14cc8c6a5e](https://linux-hardware.org/?probe=14cc8c6a5e) | Mar 26, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [0933beb0f7](https://linux-hardware.org/?probe=0933beb0f7) | Mar 26, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [93b35b776a](https://linux-hardware.org/?probe=93b35b776a) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [c722a5f7b2](https://linux-hardware.org/?probe=c722a5f7b2) | Mar 26, 2023 |
| Dell          | G3 3590                     | Notebook    | [db70257507](https://linux-hardware.org/?probe=db70257507) | Mar 26, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [b9095b98c4](https://linux-hardware.org/?probe=b9095b98c4) | Mar 25, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [b49dbdfa77](https://linux-hardware.org/?probe=b49dbdfa77) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0YA0... | Notebook    | [f4cb79dbf8](https://linux-hardware.org/?probe=f4cb79dbf8) | Mar 25, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | Notebook    | [649b881439](https://linux-hardware.org/?probe=649b881439) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | Notebook    | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [99da9866a9](https://linux-hardware.org/?probe=99da9866a9) | Mar 25, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [2f5c339d88](https://linux-hardware.org/?probe=2f5c339d88) | Mar 25, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [3677f24e87](https://linux-hardware.org/?probe=3677f24e87) | Mar 25, 2023 |
| ASRock        | B550AM Gaming               | Desktop     | [be6e8f17cc](https://linux-hardware.org/?probe=be6e8f17cc) | Mar 25, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [d1eea40764](https://linux-hardware.org/?probe=d1eea40764) | Mar 25, 2023 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [f9ff96064b](https://linux-hardware.org/?probe=f9ff96064b) | Mar 24, 2023 |
| Toshiba       | Satellite C850-140          | Notebook    | [6682022c49](https://linux-hardware.org/?probe=6682022c49) | Mar 24, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [71d058eb0e](https://linux-hardware.org/?probe=71d058eb0e) | Mar 24, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [ae6069d9bb](https://linux-hardware.org/?probe=ae6069d9bb) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [4eb8132fd2](https://linux-hardware.org/?probe=4eb8132fd2) | Mar 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [56942672e1](https://linux-hardware.org/?probe=56942672e1) | Mar 24, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [29fce46770](https://linux-hardware.org/?probe=29fce46770) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [ded37ac14c](https://linux-hardware.org/?probe=ded37ac14c) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [13046d5580](https://linux-hardware.org/?probe=13046d5580) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [56854770ba](https://linux-hardware.org/?probe=56854770ba) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [62a95efc48](https://linux-hardware.org/?probe=62a95efc48) | Mar 23, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [748d918a61](https://linux-hardware.org/?probe=748d918a61) | Mar 23, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [38b0e00744](https://linux-hardware.org/?probe=38b0e00744) | Mar 23, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [ad1134944b](https://linux-hardware.org/?probe=ad1134944b) | Mar 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [79e1666c41](https://linux-hardware.org/?probe=79e1666c41) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [5f0061dd7b](https://linux-hardware.org/?probe=5f0061dd7b) | Mar 23, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [a36464850a](https://linux-hardware.org/?probe=a36464850a) | Mar 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [28cd6cb051](https://linux-hardware.org/?probe=28cd6cb051) | Mar 23, 2023 |
| HP            | Spectre                     | Convertible | [c9181ab4f2](https://linux-hardware.org/?probe=c9181ab4f2) | Mar 22, 2023 |
| HP            | Spectre                     | Convertible | [5e07c68683](https://linux-hardware.org/?probe=5e07c68683) | Mar 22, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [9795961bca](https://linux-hardware.org/?probe=9795961bca) | Mar 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [fab7c8ab05](https://linux-hardware.org/?probe=fab7c8ab05) | Mar 22, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [e885d387ee](https://linux-hardware.org/?probe=e885d387ee) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [0880214933](https://linux-hardware.org/?probe=0880214933) | Mar 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | Notebook    | [e7b50c8f22](https://linux-hardware.org/?probe=e7b50c8f22) | Mar 22, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [4b7801e829](https://linux-hardware.org/?probe=4b7801e829) | Mar 22, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [1e299101d8](https://linux-hardware.org/?probe=1e299101d8) | Mar 22, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [1da76d59b2](https://linux-hardware.org/?probe=1da76d59b2) | Mar 21, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [6fc76628d3](https://linux-hardware.org/?probe=6fc76628d3) | Mar 21, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [2940ea3b40](https://linux-hardware.org/?probe=2940ea3b40) | Mar 21, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [7336ce9057](https://linux-hardware.org/?probe=7336ce9057) | Mar 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [c2191470c7](https://linux-hardware.org/?probe=c2191470c7) | Mar 21, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [01e06fb483](https://linux-hardware.org/?probe=01e06fb483) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [7d1cd9aded](https://linux-hardware.org/?probe=7d1cd9aded) | Mar 20, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [217e9242da](https://linux-hardware.org/?probe=217e9242da) | Mar 20, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [b011027d1a](https://linux-hardware.org/?probe=b011027d1a) | Mar 20, 2023 |
| Gigabyte      | P31-DS3L                    | Desktop     | [7fb5a2f07e](https://linux-hardware.org/?probe=7fb5a2f07e) | Mar 20, 2023 |
| Acer          | Aspire C24-320              | All in one  | [f320bc5964](https://linux-hardware.org/?probe=f320bc5964) | Mar 20, 2023 |
| Acer          | Aspire C24-320              | All in one  | [21de7ff6d5](https://linux-hardware.org/?probe=21de7ff6d5) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [a6054e6f0e](https://linux-hardware.org/?probe=a6054e6f0e) | Mar 20, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f9c84aa26c](https://linux-hardware.org/?probe=f9c84aa26c) | Mar 20, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [ba804b8e21](https://linux-hardware.org/?probe=ba804b8e21) | Mar 20, 2023 |
| MSI           | GS63VR 7RF                  | Notebook    | [8d13f6eef9](https://linux-hardware.org/?probe=8d13f6eef9) | Mar 20, 2023 |
| MSI           | GS63VR 7RF                  | Notebook    | [5b4e0532f8](https://linux-hardware.org/?probe=5b4e0532f8) | Mar 20, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [a98665cff1](https://linux-hardware.org/?probe=a98665cff1) | Mar 20, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | Desktop     | [19a060d86d](https://linux-hardware.org/?probe=19a060d86d) | Mar 20, 2023 |
| Dell          | G15 5511                    | Notebook    | [ddb34b9c1f](https://linux-hardware.org/?probe=ddb34b9c1f) | Mar 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [0500018bce](https://linux-hardware.org/?probe=0500018bce) | Mar 19, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [ad5218c0bf](https://linux-hardware.org/?probe=ad5218c0bf) | Mar 19, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [1854e9efde](https://linux-hardware.org/?probe=1854e9efde) | Mar 19, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [aa4184ac0c](https://linux-hardware.org/?probe=aa4184ac0c) | Mar 19, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [00de843c75](https://linux-hardware.org/?probe=00de843c75) | Mar 19, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4757b31751](https://linux-hardware.org/?probe=4757b31751) | Mar 19, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [7210f8c423](https://linux-hardware.org/?probe=7210f8c423) | Mar 19, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [9727a94199](https://linux-hardware.org/?probe=9727a94199) | Mar 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS6PN0... | Notebook    | [bb86a34180](https://linux-hardware.org/?probe=bb86a34180) | Mar 18, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ed76176dfa](https://linux-hardware.org/?probe=ed76176dfa) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [e10e576833](https://linux-hardware.org/?probe=e10e576833) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [a791424f94](https://linux-hardware.org/?probe=a791424f94) | Mar 18, 2023 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [4b484ab326](https://linux-hardware.org/?probe=4b484ab326) | Mar 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | Notebook    | [434b76d9cd](https://linux-hardware.org/?probe=434b76d9cd) | Mar 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | Notebook    | [2ffc3ebd28](https://linux-hardware.org/?probe=2ffc3ebd28) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [3a565fb944](https://linux-hardware.org/?probe=3a565fb944) | Mar 18, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [a721b1b9d6](https://linux-hardware.org/?probe=a721b1b9d6) | Mar 18, 2023 |
| HONOR         | BOD-WXX9                    | Notebook    | [9bca2e7122](https://linux-hardware.org/?probe=9bca2e7122) | Mar 18, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [c20318c7c0](https://linux-hardware.org/?probe=c20318c7c0) | Mar 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [b21fb664f8](https://linux-hardware.org/?probe=b21fb664f8) | Mar 17, 2023 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [be6db6cc62](https://linux-hardware.org/?probe=be6db6cc62) | Mar 17, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [6b93d4a171](https://linux-hardware.org/?probe=6b93d4a171) | Mar 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [ccfa4fb30e](https://linux-hardware.org/?probe=ccfa4fb30e) | Mar 17, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [fc0e66fc8a](https://linux-hardware.org/?probe=fc0e66fc8a) | Mar 17, 2023 |
| Dell          | Precision 3520              | Notebook    | [2afa31184a](https://linux-hardware.org/?probe=2afa31184a) | Mar 17, 2023 |
| Dell          | Precision 3520              | Notebook    | [819b4aa330](https://linux-hardware.org/?probe=819b4aa330) | Mar 17, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | Notebook    | [e7e152095b](https://linux-hardware.org/?probe=e7e152095b) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [2215bc867b](https://linux-hardware.org/?probe=2215bc867b) | Mar 17, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [fff0c55980](https://linux-hardware.org/?probe=fff0c55980) | Mar 17, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [538477684f](https://linux-hardware.org/?probe=538477684f) | Mar 17, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1b43670875](https://linux-hardware.org/?probe=1b43670875) | Mar 16, 2023 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [03edff3e6f](https://linux-hardware.org/?probe=03edff3e6f) | Mar 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [304f8b71db](https://linux-hardware.org/?probe=304f8b71db) | Mar 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4bfe066835](https://linux-hardware.org/?probe=4bfe066835) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [f3bb3c5ef1](https://linux-hardware.org/?probe=f3bb3c5ef1) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fc7d8aee1f](https://linux-hardware.org/?probe=fc7d8aee1f) | Mar 16, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [062ba6c2b9](https://linux-hardware.org/?probe=062ba6c2b9) | Mar 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8a802fa8fe](https://linux-hardware.org/?probe=8a802fa8fe) | Mar 16, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [ae258d05b1](https://linux-hardware.org/?probe=ae258d05b1) | Mar 16, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [9765f2823e](https://linux-hardware.org/?probe=9765f2823e) | Mar 16, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [53c02c1bb8](https://linux-hardware.org/?probe=53c02c1bb8) | Mar 16, 2023 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [623a5ed92b](https://linux-hardware.org/?probe=623a5ed92b) | Mar 15, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [590a3ca248](https://linux-hardware.org/?probe=590a3ca248) | Mar 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | Notebook    | [e4254565ed](https://linux-hardware.org/?probe=e4254565ed) | Mar 15, 2023 |
| Star Labs     | StarBook                    | Notebook    | [13efc22826](https://linux-hardware.org/?probe=13efc22826) | Mar 15, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [29ebc422fe](https://linux-hardware.org/?probe=29ebc422fe) | Mar 15, 2023 |
| Timi          | RedmiBook 14                | Notebook    | [ff5feda02c](https://linux-hardware.org/?probe=ff5feda02c) | Mar 14, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [6c7886396a](https://linux-hardware.org/?probe=6c7886396a) | Mar 14, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [7649d9be35](https://linux-hardware.org/?probe=7649d9be35) | Mar 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | Notebook    | [0b9501dcc9](https://linux-hardware.org/?probe=0b9501dcc9) | Mar 14, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [a87952a308](https://linux-hardware.org/?probe=a87952a308) | Mar 14, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [42baaa40b9](https://linux-hardware.org/?probe=42baaa40b9) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2662a08251](https://linux-hardware.org/?probe=2662a08251) | Mar 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [a13648959d](https://linux-hardware.org/?probe=a13648959d) | Mar 14, 2023 |
| Star Labs     | StarBook                    | Notebook    | [3e534c533a](https://linux-hardware.org/?probe=3e534c533a) | Mar 14, 2023 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [2906d8ad11](https://linux-hardware.org/?probe=2906d8ad11) | Mar 14, 2023 |
| HP            | ProLiant DL380 G4           | Server      | [403a18bfff](https://linux-hardware.org/?probe=403a18bfff) | Mar 14, 2023 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [7f06c80526](https://linux-hardware.org/?probe=7f06c80526) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [7c96c962f0](https://linux-hardware.org/?probe=7c96c962f0) | Mar 13, 2023 |
| Monster       | ABRA A7 V11.3               | Notebook    | [724a9e65d8](https://linux-hardware.org/?probe=724a9e65d8) | Mar 13, 2023 |
| Panasonic     | FZ40-1                      | Notebook    | [1dfcc0c545](https://linux-hardware.org/?probe=1dfcc0c545) | Mar 13, 2023 |
| HP            | ProBook 6460b               | Notebook    | [c6b7f1ec98](https://linux-hardware.org/?probe=c6b7f1ec98) | Mar 13, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [d507b4619f](https://linux-hardware.org/?probe=d507b4619f) | Mar 13, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [87331b21e8](https://linux-hardware.org/?probe=87331b21e8) | Mar 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [aa74d34d26](https://linux-hardware.org/?probe=aa74d34d26) | Mar 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [12423f96f6](https://linux-hardware.org/?probe=12423f96f6) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [0b0840b785](https://linux-hardware.org/?probe=0b0840b785) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [25c6ceb9e8](https://linux-hardware.org/?probe=25c6ceb9e8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1e2dd83baa](https://linux-hardware.org/?probe=1e2dd83baa) | Mar 13, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [a7e24ac4b6](https://linux-hardware.org/?probe=a7e24ac4b6) | Mar 13, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [7c00691824](https://linux-hardware.org/?probe=7c00691824) | Mar 12, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [7ce318cc22](https://linux-hardware.org/?probe=7ce318cc22) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [5522717dc5](https://linux-hardware.org/?probe=5522717dc5) | Mar 12, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [751bedd6a9](https://linux-hardware.org/?probe=751bedd6a9) | Mar 12, 2023 |
| MSI           | Pulse GL66 11UGKV           | Notebook    | [1abb09da1a](https://linux-hardware.org/?probe=1abb09da1a) | Mar 12, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [a081c489c9](https://linux-hardware.org/?probe=a081c489c9) | Mar 12, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [7a20b4f81a](https://linux-hardware.org/?probe=7a20b4f81a) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [053e36ef52](https://linux-hardware.org/?probe=053e36ef52) | Mar 12, 2023 |
| HP            | G61                         | Notebook    | [2f5e9f6f43](https://linux-hardware.org/?probe=2f5e9f6f43) | Mar 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [062687b226](https://linux-hardware.org/?probe=062687b226) | Mar 11, 2023 |
| Intel         | JSL MRD                     | Desktop     | [28832d0a36](https://linux-hardware.org/?probe=28832d0a36) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [4664479644](https://linux-hardware.org/?probe=4664479644) | Mar 11, 2023 |
| Dell          | Latitude E6530              | Notebook    | [50a26c019d](https://linux-hardware.org/?probe=50a26c019d) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z480                | Notebook    | [eb63a9a0d3](https://linux-hardware.org/?probe=eb63a9a0d3) | Mar 10, 2023 |
| HP            | EliteBook 8730w             | Notebook    | [a012fe4bd2](https://linux-hardware.org/?probe=a012fe4bd2) | Mar 10, 2023 |
| Panasonic     | FZ40-1                      | Notebook    | [5d082aaf0e](https://linux-hardware.org/?probe=5d082aaf0e) | Mar 10, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [f1e983c2dc](https://linux-hardware.org/?probe=f1e983c2dc) | Mar 10, 2023 |
| HP            | 8754                        | Mini pc     | [4913915d6f](https://linux-hardware.org/?probe=4913915d6f) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | Notebook    | [4745f71e81](https://linux-hardware.org/?probe=4745f71e81) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | Notebook    | [98c29f81d8](https://linux-hardware.org/?probe=98c29f81d8) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [6ef05d9cbb](https://linux-hardware.org/?probe=6ef05d9cbb) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [4f916d30c4](https://linux-hardware.org/?probe=4f916d30c4) | Mar 10, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [9552c8c0ab](https://linux-hardware.org/?probe=9552c8c0ab) | Mar 10, 2023 |
| Panasonic     | FZ40-1                      | Notebook    | [9eac1dc6f5](https://linux-hardware.org/?probe=9eac1dc6f5) | Mar 10, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | Notebook    | [06971429a7](https://linux-hardware.org/?probe=06971429a7) | Mar 10, 2023 |
| Lenovo        | ThinkPad T450 20BUA05K00    | Notebook    | [a496755d7a](https://linux-hardware.org/?probe=a496755d7a) | Mar 10, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [1b0ea7bf68](https://linux-hardware.org/?probe=1b0ea7bf68) | Mar 10, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ceb2734b56](https://linux-hardware.org/?probe=ceb2734b56) | Mar 09, 2023 |
| Dell          | 0XW3KG A02                  | All in one  | [d45b4c63fa](https://linux-hardware.org/?probe=d45b4c63fa) | Mar 09, 2023 |
| Dell          | 0XW3KG A02                  | All in one  | [f4e6d8e7a0](https://linux-hardware.org/?probe=f4e6d8e7a0) | Mar 09, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [447f2ec783](https://linux-hardware.org/?probe=447f2ec783) | Mar 09, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [9c59079b1f](https://linux-hardware.org/?probe=9c59079b1f) | Mar 09, 2023 |
| Acer          | Veriton M480                | Desktop     | [8cd45e8525](https://linux-hardware.org/?probe=8cd45e8525) | Mar 09, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [8574146364](https://linux-hardware.org/?probe=8574146364) | Mar 09, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [c397e2fa8b](https://linux-hardware.org/?probe=c397e2fa8b) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [79fc708bbd](https://linux-hardware.org/?probe=79fc708bbd) | Mar 09, 2023 |
| Lenovo        | IdeaPad Z480                | Notebook    | [bc5f204a78](https://linux-hardware.org/?probe=bc5f204a78) | Mar 08, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [59bddb27c4](https://linux-hardware.org/?probe=59bddb27c4) | Mar 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [69564be379](https://linux-hardware.org/?probe=69564be379) | Mar 08, 2023 |
| Intel         | B75 V124                    | Desktop     | [8a643c9a04](https://linux-hardware.org/?probe=8a643c9a04) | Mar 08, 2023 |
| Intel         | B75 V124                    | Desktop     | [777cb32ba1](https://linux-hardware.org/?probe=777cb32ba1) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [0312ea16b6](https://linux-hardware.org/?probe=0312ea16b6) | Mar 08, 2023 |
| Dell          | Precision 3520              | Notebook    | [99eaeb743c](https://linux-hardware.org/?probe=99eaeb743c) | Mar 08, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [c768e8ff8f](https://linux-hardware.org/?probe=c768e8ff8f) | Mar 08, 2023 |
| Dell          | Precision 3520              | Notebook    | [acf74c7740](https://linux-hardware.org/?probe=acf74c7740) | Mar 08, 2023 |
| ASUSTek       | H81T                        | Desktop     | [c17251dbd9](https://linux-hardware.org/?probe=c17251dbd9) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | Notebook    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [7b405f2925](https://linux-hardware.org/?probe=7b405f2925) | Mar 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d1768ecbaa](https://linux-hardware.org/?probe=d1768ecbaa) | Mar 07, 2023 |
| Dell          | Latitude 5590               | Notebook    | [10e7ed8ff6](https://linux-hardware.org/?probe=10e7ed8ff6) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [e2c5933515](https://linux-hardware.org/?probe=e2c5933515) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [16c33be9a3](https://linux-hardware.org/?probe=16c33be9a3) | Mar 07, 2023 |
| GPD           | P2 MAX                      | Notebook    | [d73c7b9146](https://linux-hardware.org/?probe=d73c7b9146) | Mar 07, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [bbbf4112e4](https://linux-hardware.org/?probe=bbbf4112e4) | Mar 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [6485870687](https://linux-hardware.org/?probe=6485870687) | Mar 06, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [33ce987151](https://linux-hardware.org/?probe=33ce987151) | Mar 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [0047dd8b2a](https://linux-hardware.org/?probe=0047dd8b2a) | Mar 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ca073d764f](https://linux-hardware.org/?probe=ca073d764f) | Mar 06, 2023 |
| Lenovo        | Unknown                     | Notebook    | [2ae9263125](https://linux-hardware.org/?probe=2ae9263125) | Mar 06, 2023 |
| Lenovo        | ThinkPad E550 20DF002YUS    | Notebook    | [6a7ad331f8](https://linux-hardware.org/?probe=6a7ad331f8) | Mar 06, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [6a6864f933](https://linux-hardware.org/?probe=6a6864f933) | Mar 05, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [97e8238d87](https://linux-hardware.org/?probe=97e8238d87) | Mar 05, 2023 |
| IGEL Techn... | H830C                       | Notebook    | [3619b3fcee](https://linux-hardware.org/?probe=3619b3fcee) | Mar 05, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f8eea076e5](https://linux-hardware.org/?probe=f8eea076e5) | Mar 05, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [ea211d74ee](https://linux-hardware.org/?probe=ea211d74ee) | Mar 05, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6f3850aa74](https://linux-hardware.org/?probe=6f3850aa74) | Mar 05, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [24d58ff4fc](https://linux-hardware.org/?probe=24d58ff4fc) | Mar 05, 2023 |
| HP            | 3397                        | Desktop     | [5250af801f](https://linux-hardware.org/?probe=5250af801f) | Mar 04, 2023 |
| MSI           | 970A-G46                    | Desktop     | [804b0fa4da](https://linux-hardware.org/?probe=804b0fa4da) | Mar 04, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [1ccfddfbc0](https://linux-hardware.org/?probe=1ccfddfbc0) | Mar 04, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9de6b65a45](https://linux-hardware.org/?probe=9de6b65a45) | Mar 04, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [fca1ca2628](https://linux-hardware.org/?probe=fca1ca2628) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [71f2f93645](https://linux-hardware.org/?probe=71f2f93645) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [13fc723c9e](https://linux-hardware.org/?probe=13fc723c9e) | Mar 04, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [6181549e93](https://linux-hardware.org/?probe=6181549e93) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c19189c929](https://linux-hardware.org/?probe=c19189c929) | Mar 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [4679c9328e](https://linux-hardware.org/?probe=4679c9328e) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [bef62e57b0](https://linux-hardware.org/?probe=bef62e57b0) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [b42f1c3f6b](https://linux-hardware.org/?probe=b42f1c3f6b) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5715b4e8af](https://linux-hardware.org/?probe=5715b4e8af) | Mar 03, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [d8d83e3bb3](https://linux-hardware.org/?probe=d8d83e3bb3) | Mar 03, 2023 |
| HP            | Spectre                     | Convertible | [8e2fdf7f6b](https://linux-hardware.org/?probe=8e2fdf7f6b) | Mar 03, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [5823762138](https://linux-hardware.org/?probe=5823762138) | Mar 03, 2023 |
| HP            | ENVY dv6                    | Notebook    | [357b5b3506](https://linux-hardware.org/?probe=357b5b3506) | Mar 03, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [860f53436b](https://linux-hardware.org/?probe=860f53436b) | Mar 03, 2023 |
| Dell          | Latitude E6510              | Notebook    | [80edceafbc](https://linux-hardware.org/?probe=80edceafbc) | Mar 03, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e08a9cdac6](https://linux-hardware.org/?probe=e08a9cdac6) | Mar 03, 2023 |
| HP            | 82F2 A01                    | Desktop     | [305779159c](https://linux-hardware.org/?probe=305779159c) | Mar 02, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [13f585159e](https://linux-hardware.org/?probe=13f585159e) | Mar 02, 2023 |
| DTRI          | DT317CR                     | Notebook    | [b78d90835c](https://linux-hardware.org/?probe=b78d90835c) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | Notebook    | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [ee356bc253](https://linux-hardware.org/?probe=ee356bc253) | Mar 02, 2023 |
| Dell          | Precision 5520              | Notebook    | [9ce4c56521](https://linux-hardware.org/?probe=9ce4c56521) | Mar 02, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [8ac11055c8](https://linux-hardware.org/?probe=8ac11055c8) | Mar 02, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [72b59f777e](https://linux-hardware.org/?probe=72b59f777e) | Mar 01, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | Notebook    | [f61c295d09](https://linux-hardware.org/?probe=f61c295d09) | Mar 01, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [0ffe1f9541](https://linux-hardware.org/?probe=0ffe1f9541) | Feb 28, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [a08a3c36ab](https://linux-hardware.org/?probe=a08a3c36ab) | Feb 28, 2023 |
| ASRock        | B660M-STX                   | Desktop     | [5a32d2e162](https://linux-hardware.org/?probe=5a32d2e162) | Feb 28, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [9707436005](https://linux-hardware.org/?probe=9707436005) | Feb 28, 2023 |
| ASRock        | B365M-HDV                   | Desktop     | [def987e32c](https://linux-hardware.org/?probe=def987e32c) | Feb 28, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [456504fe92](https://linux-hardware.org/?probe=456504fe92) | Feb 28, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [c070966ad7](https://linux-hardware.org/?probe=c070966ad7) | Feb 28, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ec1f27de09](https://linux-hardware.org/?probe=ec1f27de09) | Feb 28, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Arch Rolling     | 3542      | 54.08%  |
| Arch             | 2982      | 45.53%  |
| Arch V20.4.11    | 3         | 0.05%   |
| Arch V19.11.3    | 3         | 0.05%   |
| Arch V20.5.7     | 2         | 0.03%   |
| Arch V20.3.4     | 2         | 0.03%   |
| Arch V19.04.4    | 2         | 0.03%   |
| Arch Workstation | 1         | 0.02%   |
| Arch V6.9.2      | 1         | 0.02%   |
| Arch V19.09.1    | 1         | 0.02%   |
| Arch V19.07.9    | 1         | 0.02%   |
| Arch V19.07.11   | 1         | 0.02%   |
| Arch V19.06.1    | 1         | 0.02%   |
| Arch V19.05.2    | 1         | 0.02%   |
| Arch V19.01.4    | 1         | 0.02%   |
| Arch Breaking    | 1         | 0.02%   |
| Arch 22.10       | 1         | 0.02%   |
| Arch 2020.09.05  | 1         | 0.02%   |
| Arch 20.08.3     | 1         | 0.02%   |
| Arch 2.7         | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Arch | 6368      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 85        | 1.13%   |
| 6.0.2-arch1-1   | 71        | 0.94%   |
| 5.8.5-arch1-1   | 70        | 0.93%   |
| 5.9.14-arch1-1  | 61        | 0.81%   |
| 5.9.1-arch1-1   | 60        | 0.8%    |
| 5.17.5-arch1-1  | 53        | 0.7%    |
| 5.17.9-arch1-1  | 51        | 0.68%   |
| 5.8.12-arch1-1  | 48        | 0.64%   |
| 5.8.10-arch1-1  | 48        | 0.64%   |
| 5.8.14-arch1-1  | 47        | 0.62%   |
| 5.7.12-arch1-1  | 46        | 0.61%   |
| 6.2.8-arch1-1   | 45        | 0.6%    |
| 6.1.1-arch1-1   | 45        | 0.6%    |
| 5.13.13-arch1-1 | 45        | 0.6%    |
| 5.8.1-arch1-1   | 43        | 0.57%   |
| 6.0.9-arch1-1   | 42        | 0.56%   |
| 6.0.12-arch1-1  | 42        | 0.56%   |
| 5.11.16-arch1-1 | 42        | 0.56%   |
| 6.3.2-arch1-1   | 38        | 0.5%    |
| 6.2.10-arch1-1  | 37        | 0.49%   |
| 6.1.12-arch1-1  | 37        | 0.49%   |
| 5.6.15-arch1-1  | 37        | 0.49%   |
| 6.1.8-arch1-1   | 34        | 0.45%   |
| 5.18.16-arch1-1 | 34        | 0.45%   |
| 5.11.6-arch1-1  | 34        | 0.45%   |
| 5.11.11-arch1-1 | 34        | 0.45%   |
| 6.3.1-arch1-1   | 33        | 0.44%   |
| 5.12.15-arch1-1 | 33        | 0.44%   |
| 5.10.16-arch1-1 | 33        | 0.44%   |
| 6.3.5-arch1-1   | 32        | 0.42%   |
| 6.2.12-arch1-1  | 32        | 0.42%   |
| 6.0.10-arch2-1  | 32        | 0.42%   |
| 5.19.13-arch1-1 | 32        | 0.42%   |
| 5.18.1-arch1-1  | 32        | 0.42%   |
| 6.2.2-arch1-1   | 31        | 0.41%   |
| 6.0.7-arch1-1   | 31        | 0.41%   |
| 5.8.3-arch1-1   | 31        | 0.41%   |
| 5.19.7-arch1-1  | 31        | 0.41%   |
| 5.15.7-arch1-1  | 31        | 0.41%   |
| 5.14.14-arch1-1 | 31        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 105       | 1.39%   |
| 5.8.5   | 92        | 1.22%   |
| 6.0.2   | 90        | 1.19%   |
| 5.9.1   | 77        | 1.02%   |
| 5.8.12  | 73        | 0.97%   |
| 5.9.14  | 72        | 0.95%   |
| 5.17.5  | 70        | 0.93%   |
| 6.3.1   | 64        | 0.85%   |
| 5.8.14  | 63        | 0.83%   |
| 5.8.10  | 62        | 0.82%   |
| 5.17.9  | 61        | 0.81%   |
| 6.1.1   | 56        | 0.74%   |
| 5.13.13 | 56        | 0.74%   |
| 6.2.2   | 54        | 0.72%   |
| 6.1.12  | 54        | 0.72%   |
| 6.2.8   | 53        | 0.7%    |
| 5.8.1   | 53        | 0.7%    |
| 5.7.12  | 53        | 0.7%    |
| 6.0.9   | 52        | 0.69%   |
| 5.11.6  | 52        | 0.69%   |
| 6.3.2   | 51        | 0.68%   |
| 6.1.9   | 51        | 0.68%   |
| 6.0.12  | 51        | 0.68%   |
| 5.11.16 | 51        | 0.68%   |
| 6.2.10  | 49        | 0.65%   |
| 6.3.5   | 47        | 0.62%   |
| 6.1.8   | 43        | 0.57%   |
| 5.11.2  | 43        | 0.57%   |
| 6.0.8   | 42        | 0.56%   |
| 5.12.15 | 42        | 0.56%   |
| 5.10.16 | 42        | 0.56%   |
| 6.0.11  | 41        | 0.54%   |
| 5.19.7  | 41        | 0.54%   |
| 5.18.16 | 41        | 0.54%   |
| 5.11.11 | 41        | 0.54%   |
| 6.0.10  | 40        | 0.53%   |
| 5.19.13 | 40        | 0.53%   |
| 6.2.12  | 39        | 0.52%   |
| 6.2.6   | 38        | 0.5%    |
| 5.7.6   | 38        | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 522       | 7.18%   |
| 5.15    | 479       | 6.59%   |
| 6.1     | 438       | 6.03%   |
| 6.0     | 412       | 5.67%   |
| 6.2     | 385       | 5.3%    |
| 5.9     | 384       | 5.28%   |
| 5.18    | 367       | 5.05%   |
| 5.10    | 355       | 4.89%   |
| 5.4     | 353       | 4.86%   |
| 5.11    | 350       | 4.82%   |
| 5.19    | 343       | 4.72%   |
| 5.17    | 342       | 4.71%   |
| 6.3     | 337       | 4.64%   |
| 5.12    | 310       | 4.27%   |
| 5.16    | 305       | 4.2%    |
| 5.6     | 263       | 3.62%   |
| 5.7     | 260       | 3.58%   |
| 5.14    | 237       | 3.26%   |
| 5.13    | 234       | 3.22%   |
| 5.5     | 148       | 2.04%   |
| 5.3     | 114       | 1.57%   |
| 4.19    | 56        | 0.77%   |
| 5.2     | 54        | 0.74%   |
| 5.0     | 41        | 0.56%   |
| 4.18    | 37        | 0.51%   |
| 5.1     | 32        | 0.44%   |
| 4.20    | 22        | 0.3%    |
| 4.17    | 19        | 0.26%   |
| 4.15    | 14        | 0.19%   |
| 4.14    | 10        | 0.14%   |
| 4.16    | 9         | 0.12%   |
| 4.9     | 5         | 0.07%   |
| 4.7     | 4         | 0.06%   |
| 4.6     | 4         | 0.06%   |
| 4.11    | 4         | 0.06%   |
| 6.4     | 3         | 0.04%   |
| 4.8     | 3         | 0.04%   |
| 4.4     | 3         | 0.04%   |
| 4.13    | 3         | 0.04%   |
| 4.10    | 2         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6362      | 99.91%  |
| i686    | 5         | 0.08%   |
| riscv64 | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 2132      | 32.09%  |
| KDE5                     | 1700      | 25.59%  |
| Unknown                  | 823       | 12.39%  |
| XFCE                     | 511       | 7.69%   |
| i3                       | 332       | 5%      |
| KDE                      | 295       | 4.44%   |
| X-Cinnamon               | 92        | 1.38%   |
| sway                     | 88        | 1.32%   |
| MATE                     | 83        | 1.25%   |
| Budgie                   | 82        | 1.23%   |
| Cinnamon                 | 81        | 1.22%   |
| Deepin                   | 67        | 1.01%   |
| LXQt                     | 53        | 0.8%    |
| Hyprland                 | 48        | 0.72%   |
| LXDE                     | 39        | 0.59%   |
| bspwm                    | 38        | 0.57%   |
| awesome                  | 33        | 0.5%    |
| qtile                    | 19        | 0.29%   |
| openbox                  | 19        | 0.29%   |
| GNOME Flashback          | 15        | 0.23%   |
| DWM                      | 15        | 0.23%   |
| xmonad                   | 14        | 0.21%   |
| Unity                    | 11        | 0.17%   |
| GNOME Classic            | 8         | 0.12%   |
| LeftWM                   | 6         | 0.09%   |
| i3-with-shmlog           | 6         | 0.09%   |
| Enlightenment            | 4         | 0.06%   |
| chadwm                   | 4         | 0.06%   |
| Wayfire                  | 2         | 0.03%   |
| river                    | 2         | 0.03%   |
| jwm                      | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| GNUstep                  | 2         | 0.03%   |
| dusk                     | 2         | 0.03%   |
| default                  | 2         | 0.03%   |
| /usr/bin/openbox-session | 2         | 0.03%   |
| Yaru:ubuntu:GNOME        | 1         | 0.02%   |
| xinitrc                  | 1         | 0.02%   |
| X-Generic                | 1         | 0.02%   |
| sway:Unity               | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3907      | 59.21%  |
| Wayland | 1616      | 24.49%  |
| Tty     | 612       | 9.27%   |
| Unknown | 463       | 7.02%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2729      | 41.51%  |
| SDDM    | 1551      | 23.59%  |
| GDM     | 933       | 14.19%  |
| LightDM | 720       | 10.95%  |
| TDM     | 398       | 6.05%   |
| Ly      | 74        | 1.13%   |
| XDM     | 56        | 0.85%   |
| LXDM    | 53        | 0.81%   |
| SLiM    | 27        | 0.41%   |
| GREETD  | 19        | 0.29%   |
| EMPTTY  | 5         | 0.08%   |
| NODM    | 4         | 0.06%   |
| LY-DM   | 2         | 0.03%   |
| XINIT   | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 3159      | 48.53%  |
| Unknown    | 628       | 9.65%   |
| en_GB      | 378       | 5.81%   |
| C          | 343       | 5.27%   |
| de_DE      | 268       | 4.12%   |
| it_IT      | 200       | 3.07%   |
| ru_RU      | 195       | 3%      |
| pt_BR      | 175       | 2.69%   |
| fr_FR      | 151       | 2.32%   |
| pl_PL      | 84        | 1.29%   |
| zh_CN      | 72        | 1.11%   |
| en_CA      | 72        | 1.11%   |
| es_ES      | 71        | 1.09%   |
| en_IN      | 66        | 1.01%   |
| en_AU      | 65        | 1%      |
| en_IE      | 35        | 0.54%   |
| en_DK      | 29        | 0.45%   |
| es_MX      | 27        | 0.41%   |
| de_AT      | 22        | 0.34%   |
| hu_HU      | 21        | 0.32%   |
| pt_PT      | 19        | 0.29%   |
| es_AR      | 18        | 0.28%   |
| en_NZ      | 17        | 0.26%   |
| tr_TR      | 16        | 0.25%   |
| nl_NL      | 16        | 0.25%   |
| ja_JP      | 16        | 0.25%   |
| cs_CZ      | 16        | 0.25%   |
| es_CO      | 14        | 0.22%   |
| es_CL      | 14        | 0.22%   |
| ru_UA      | 13        | 0.2%    |
| sv_SE      | 11        | 0.17%   |
| en_SG      | 11        | 0.17%   |
| en_ZA      | 10        | 0.15%   |
| en_US.UTF8 | 10        | 0.15%   |
| lv_LV      | 9         | 0.14%   |
| en_DE      | 9         | 0.14%   |
| de_CH      | 9         | 0.14%   |
| zh_TW      | 8         | 0.12%   |
| fi_FI      | 8         | 0.12%   |
| en_AG      | 8         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4022      | 61.85%  |
| BIOS | 2481      | 38.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4580      | 70.93%  |
| Btrfs    | 1354      | 20.97%  |
| Unknown  | 182       | 2.82%   |
| Xfs      | 155       | 2.4%    |
| F2fs     | 89        | 1.38%   |
| Zfs      | 38        | 0.59%   |
| Overlay  | 36        | 0.56%   |
| Ext2     | 8         | 0.12%   |
| XXXXX    | 4         | 0.06%   |
| Tmpfs    | 4         | 0.06%   |
| Jfs      | 2         | 0.03%   |
| Ext3     | 2         | 0.03%   |
| XXX4     | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4092      | 63.32%  |
| Unknown | 1836      | 28.41%  |
| MBR     | 534       | 8.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5560      | 86.15%  |
| Yes       | 894       | 13.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4491      | 69.31%  |
| Yes       | 1989      | 30.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 1223      | 19.21%  |
| Lenovo                 | 1148      | 18.03%  |
| Hewlett-Packard        | 678       | 10.65%  |
| Dell                   | 676       | 10.62%  |
| MSI                    | 529       | 8.31%   |
| Gigabyte Technology    | 521       | 8.18%   |
| ASRock                 | 323       | 5.07%   |
| Acer                   | 309       | 4.85%   |
| Apple                  | 100       | 1.57%   |
| Intel                  | 80        | 1.26%   |
| HUAWEI                 | 64        | 1.01%   |
| Samsung Electronics    | 61        | 0.96%   |
| Toshiba                | 47        | 0.74%   |
| Unknown                | 35        | 0.55%   |
| Microsoft              | 34        | 0.53%   |
| Notebook               | 33        | 0.52%   |
| Timi                   | 28        | 0.44%   |
| Google                 | 27        | 0.42%   |
| Sony                   | 24        | 0.38%   |
| Fujitsu                | 22        | 0.35%   |
| TUXEDO                 | 20        | 0.31%   |
| Framework              | 19        | 0.3%    |
| Alienware              | 18        | 0.28%   |
| Biostar                | 15        | 0.24%   |
| Razer                  | 14        | 0.22%   |
| Medion                 | 12        | 0.19%   |
| Pegatron               | 11        | 0.17%   |
| LG Electronics         | 11        | 0.17%   |
| Avell High Performance | 11        | 0.17%   |
| System76               | 10        | 0.16%   |
| Schenker               | 10        | 0.16%   |
| ECS                    | 10        | 0.16%   |
| Supermicro             | 8         | 0.13%   |
| Positivo               | 8         | 0.13%   |
| Packard Bell           | 8         | 0.13%   |
| MECHREVO               | 8         | 0.13%   |
| Huanan                 | 7         | 0.11%   |
| Chuwi                  | 7         | 0.11%   |
| GPD                    | 6         | 0.09%   |
| ZOTAC                  | 5         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 60        | 0.94%   |
| Unknown                          | 59        | 0.93%   |
| ASUS TUF Gaming X570-PLUS        | 30        | 0.47%   |
| MSI MS-7C37                      | 29        | 0.46%   |
| MSI MS-7C02                      | 29        | 0.46%   |
| MSI MS-7B86                      | 23        | 0.36%   |
| Gigabyte B450M DS3H              | 22        | 0.35%   |
| Dell XPS 15 9570                 | 18        | 0.28%   |
| ASUS ROG STRIX B550-F GAMING     | 18        | 0.28%   |
| MSI MS-7A34                      | 17        | 0.27%   |
| Gigabyte X570 AORUS ELITE        | 17        | 0.27%   |
| ASUS ROG STRIX B450-F GAMING     | 17        | 0.27%   |
| ASUS PRIME X470-PRO              | 17        | 0.27%   |
| MSI MS-7B89                      | 16        | 0.25%   |
| MSI MS-7B79                      | 16        | 0.25%   |
| Framework Laptop                 | 16        | 0.25%   |
| ASUS PRIME B450M-A               | 16        | 0.25%   |
| MSI MS-7C91                      | 15        | 0.24%   |
| MSI MS-7A38                      | 15        | 0.24%   |
| HP Notebook                      | 15        | 0.24%   |
| ASUS PRIME X370-PRO              | 15        | 0.24%   |
| Gigabyte X470 AORUS ULTRA GAMING | 14        | 0.22%   |
| Dell XPS 15 9500                 | 14        | 0.22%   |
| Dell XPS 13 9360                 | 13        | 0.2%    |
| ASUS TUF Gaming B550-PLUS        | 13        | 0.2%    |
| MSI MS-7C56                      | 12        | 0.19%   |
| ASUS ROG STRIX X570-E GAMING     | 12        | 0.19%   |
| Gigabyte B450 AORUS ELITE        | 11        | 0.17%   |
| Gigabyte 970A-DS3P               | 11        | 0.17%   |
| Dell XPS 13 9380                 | 11        | 0.17%   |
| ASUS ROG STRIX X470-F GAMING     | 11        | 0.17%   |
| ASUS PRIME A320M-K               | 11        | 0.17%   |
| ASRock X570 Taichi               | 11        | 0.17%   |
| ASRock B450M Pro4                | 11        | 0.17%   |
| HUAWEI NBLK-WAX9X                | 10        | 0.16%   |
| Gigabyte X570 I AORUS PRO WIFI   | 10        | 0.16%   |
| Dell XPS 13 9310                 | 10        | 0.16%   |
| Dell Latitude E6430              | 10        | 0.16%   |
| Dell Inspiron 15 7000 Gaming     | 10        | 0.16%   |
| ASUS ROG Strix G513QY_G513QY     | 10        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 625       | 9.81%   |
| ASUS ROG           | 239       | 3.75%   |
| ASUS PRIME         | 203       | 3.19%   |
| Lenovo IdeaPad     | 200       | 3.14%   |
| Acer Aspire        | 179       | 2.81%   |
| Dell Inspiron      | 168       | 2.64%   |
| Dell XPS           | 160       | 2.51%   |
| Dell Latitude      | 152       | 2.39%   |
| ASUS TUF           | 146       | 2.29%   |
| HP Pavilion        | 122       | 1.92%   |
| HP EliteBook       | 109       | 1.71%   |
| HP Laptop          | 72        | 1.13%   |
| HP ENVY            | 67        | 1.05%   |
| Lenovo Legion      | 65        | 1.02%   |
| ASUS VivoBook      | 63        | 0.99%   |
| Lenovo Yoga        | 61        | 0.96%   |
| Gigabyte X570      | 60        | 0.94%   |
| ASUS All           | 60        | 0.94%   |
| Unknown            | 59        | 0.93%   |
| HP ProBook         | 58        | 0.91%   |
| Dell Precision     | 58        | 0.91%   |
| Dell OptiPlex      | 53        | 0.83%   |
| Acer Nitro         | 44        | 0.69%   |
| Toshiba Satellite  | 38        | 0.6%    |
| Acer Swift         | 37        | 0.58%   |
| ASUS ASUS          | 36        | 0.57%   |
| Microsoft Surface  | 34        | 0.53%   |
| Gigabyte B450M     | 34        | 0.53%   |
| ASUS ZenBook       | 33        | 0.52%   |
| HP OMEN            | 31        | 0.49%   |
| Dell Vostro        | 31        | 0.49%   |
| Lenovo ThinkBook   | 30        | 0.47%   |
| ASRock X570        | 30        | 0.47%   |
| MSI MS-7C37        | 29        | 0.46%   |
| MSI MS-7C02        | 29        | 0.46%   |
| HP Spectre         | 29        | 0.46%   |
| Gigabyte B450      | 29        | 0.46%   |
| HP Compaq          | 25        | 0.39%   |
| Lenovo ThinkCentre | 24        | 0.38%   |
| MSI MS-7B86        | 23        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 925       | 14.53%  |
| 2019    | 894       | 14.04%  |
| 2020    | 834       | 13.1%   |
| 2021    | 563       | 8.84%   |
| 2017    | 541       | 8.5%    |
| 2016    | 366       | 5.75%   |
| 2012    | 351       | 5.51%   |
| 2015    | 320       | 5.03%   |
| 2013    | 317       | 4.98%   |
| 2014    | 315       | 4.95%   |
| 2022    | 269       | 4.22%   |
| 2011    | 261       | 4.1%    |
| 2010    | 158       | 2.48%   |
| 2008    | 92        | 1.44%   |
| 2009    | 82        | 1.29%   |
| 2007    | 32        | 0.5%    |
| 2023    | 29        | 0.46%   |
| 2006    | 11        | 0.17%   |
| Unknown | 4         | 0.06%   |
| 2005    | 3         | 0.05%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3476      | 54.59%  |
| Desktop        | 2462      | 38.66%  |
| Convertible    | 233       | 3.66%   |
| Tablet         | 68        | 1.07%   |
| Mini pc        | 57        | 0.9%    |
| All in one     | 43        | 0.68%   |
| Server         | 27        | 0.42%   |
| Stick pc       | 1         | 0.02%   |
| System on chip | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6301      | 98.75%  |
| Enabled  | 80        | 1.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6319      | 99.23%  |
| Yes  | 49        | 0.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1861      | 28.81%  |
| 8.01-16.0       | 1253      | 19.4%   |
| 4.01-8.0        | 1208      | 18.7%   |
| 32.01-64.0      | 1051      | 16.27%  |
| 3.01-4.0        | 529       | 8.19%   |
| 64.01-256.0     | 258       | 3.99%   |
| 24.01-32.0      | 164       | 2.54%   |
| 1.01-2.0        | 75        | 1.16%   |
| 2.01-3.0        | 38        | 0.59%   |
| 0.51-1.0        | 12        | 0.19%   |
| More than 256.0 | 8         | 0.12%   |
| Unknown         | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1680      | 23.88%  |
| 2.01-3.0    | 1655      | 23.52%  |
| 1.01-2.0    | 1485      | 21.11%  |
| 3.01-4.0    | 1149      | 16.33%  |
| 8.01-16.0   | 607       | 8.63%   |
| 0.51-1.0    | 242       | 3.44%   |
| 16.01-24.0  | 95        | 1.35%   |
| 0.01-0.5    | 61        | 0.87%   |
| 24.01-32.0  | 37        | 0.53%   |
| 32.01-64.0  | 21        | 0.3%    |
| 64.01-256.0 | 2         | 0.03%   |
| Unknown     | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3276      | 49.96%  |
| 2      | 1782      | 27.18%  |
| 3      | 732       | 11.16%  |
| 4      | 352       | 5.37%   |
| 5      | 198       | 3.02%   |
| 6      | 90        | 1.37%   |
| 7      | 48        | 0.73%   |
| 0      | 21        | 0.32%   |
| 8      | 20        | 0.31%   |
| 9      | 16        | 0.24%   |
| 11     | 5         | 0.08%   |
| 12     | 4         | 0.06%   |
| 10     | 4         | 0.06%   |
| 13     | 3         | 0.05%   |
| 14     | 2         | 0.03%   |
| 22     | 1         | 0.02%   |
| 19     | 1         | 0.02%   |
| 17     | 1         | 0.02%   |
| 15     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5053      | 78.85%  |
| Yes       | 1355      | 21.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5318      | 83.18%  |
| No        | 1075      | 16.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4976      | 77.68%  |
| No        | 1430      | 22.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4499      | 69.83%  |
| No        | 1944      | 30.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 1212      | 18.9%   |
| Germany     | 621       | 9.68%   |
| Russia      | 414       | 6.46%   |
| Italy       | 339       | 5.29%   |
| Brazil      | 338       | 5.27%   |
| France      | 285       | 4.44%   |
| UK          | 242       | 3.77%   |
| India       | 191       | 2.98%   |
| Poland      | 188       | 2.93%   |
| Canada      | 171       | 2.67%   |
| Spain       | 143       | 2.23%   |
| Netherlands | 126       | 1.97%   |
| Australia   | 109       | 1.7%    |
| China       | 104       | 1.62%   |
| Sweden      | 94        | 1.47%   |
| Austria     | 94        | 1.47%   |
| Ukraine     | 90        | 1.4%    |
| Turkey      | 78        | 1.22%   |
| Finland     | 69        | 1.08%   |
| Switzerland | 60        | 0.94%   |
| Czechia     | 59        | 0.92%   |
| Hungary     | 54        | 0.84%   |
| Mexico      | 53        | 0.83%   |
| Romania     | 52        | 0.81%   |
| Indonesia   | 50        | 0.78%   |
| Argentina   | 48        | 0.75%   |
| Portugal    | 47        | 0.73%   |
| Belgium     | 46        | 0.72%   |
| Denmark     | 44        | 0.69%   |
| Norway      | 43        | 0.67%   |
| Japan       | 42        | 0.66%   |
| Greece      | 42        | 0.66%   |
| Chile       | 38        | 0.59%   |
| Vietnam     | 37        | 0.58%   |
| New Zealand | 35        | 0.55%   |
| Iran        | 34        | 0.53%   |
| Colombia    | 33        | 0.51%   |
| Hong Kong   | 27        | 0.42%   |
| Bulgaria    | 27        | 0.42%   |
| Taiwan      | 26        | 0.41%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 120       | 1.76%   |
| Paris             | 71        | 1.04%   |
| St Petersburg     | 60        | 0.88%   |
| Berlin            | 57        | 0.84%   |
| Vienna            | 52        | 0.76%   |
| Sao Paulo         | 52        | 0.76%   |
| Milan             | 51        | 0.75%   |
| Warsaw            | 49        | 0.72%   |
| Melbourne         | 44        | 0.65%   |
| Munich            | 41        | 0.6%    |
| Helsinki          | 39        | 0.57%   |
| Frankfurt am Main | 35        | 0.51%   |
| Amsterdam         | 34        | 0.5%    |
| Los Angeles       | 30        | 0.44%   |
| Sydney            | 29        | 0.43%   |
| New York          | 28        | 0.41%   |
| Istanbul          | 28        | 0.41%   |
| Hamburg           | 28        | 0.41%   |
| Prague            | 27        | 0.4%    |
| Valencia          | 26        | 0.38%   |
| Rome              | 26        | 0.38%   |
| Kyiv              | 25        | 0.37%   |
| Montreal          | 24        | 0.35%   |
| London            | 24        | 0.35%   |
| Budapest          | 23        | 0.34%   |
| Seattle           | 22        | 0.32%   |
| Bengaluru         | 22        | 0.32%   |
| Athens            | 22        | 0.32%   |
| Singapore         | 21        | 0.31%   |
| Madrid            | 21        | 0.31%   |
| Krakow            | 20        | 0.29%   |
| Cologne           | 20        | 0.29%   |
| Beijing           | 19        | 0.28%   |
| Zurich            | 18        | 0.26%   |
| Stockholm         | 18        | 0.26%   |
| Phoenix           | 18        | 0.26%   |
| Mexico City       | 18        | 0.26%   |
| Dallas            | 18        | 0.26%   |
| Barcelona         | 18        | 0.26%   |
| Tallinn           | 17        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2132      | 3369   | 20.16%  |
| WDC                         | 1478      | 2281   | 13.97%  |
| Seagate                     | 1258      | 1891   | 11.89%  |
| SanDisk                     | 727       | 961    | 6.87%   |
| Toshiba                     | 661       | 884    | 6.25%   |
| Kingston                    | 554       | 734    | 5.24%   |
| Crucial                     | 462       | 658    | 4.37%   |
| SK hynix                    | 328       | 399    | 3.1%    |
| Intel                       | 298       | 393    | 2.82%   |
| Unknown                     | 275       | 332    | 2.6%    |
| Micron Technology           | 190       | 230    | 1.8%    |
| HGST                        | 179       | 225    | 1.69%   |
| Hitachi                     | 169       | 209    | 1.6%    |
| A-DATA Technology           | 158       | 219    | 1.49%   |
| Phison                      | 116       | 150    | 1.1%    |
| Micron/Crucial Technology   | 84        | 99     | 0.79%   |
| Phison Electronics          | 81        | 97     | 0.77%   |
| China                       | 73        | 92     | 0.69%   |
| Apple                       | 69        | 84     | 0.65%   |
| Silicon Motion              | 67        | 80     | 0.63%   |
| KIOXIA                      | 65        | 79     | 0.61%   |
| OCZ                         | 53        | 71     | 0.5%    |
| SPCC                        | 52        | 57     | 0.49%   |
| Corsair                     | 48        | 62     | 0.45%   |
| PNY                         | 47        | 56     | 0.44%   |
| Transcend                   | 46        | 61     | 0.43%   |
| Kingston Technology Company | 42        | 44     | 0.4%    |
| LITEON                      | 41        | 44     | 0.39%   |
| Patriot                     | 40        | 50     | 0.38%   |
| ADATA Technology            | 38        | 45     | 0.36%   |
| GOODRAM                     | 29        | 37     | 0.27%   |
| Realtek Semiconductor       | 28        | 35     | 0.26%   |
| XPG                         | 27        | 39     | 0.26%   |
| JMicron Technology          | 26        | 35     | 0.25%   |
| Plextor                     | 23        | 32     | 0.22%   |
| Hewlett-Packard             | 23        | 25     | 0.22%   |
| Team                        | 21        | 30     | 0.2%    |
| Lenovo                      | 20        | 24     | 0.19%   |
| Intenso                     | 20        | 21     | 0.19%   |
| Lexar                       | 19        | 26     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 208       | 1.73%   |
| Samsung SSD 850 EVO 500GB                           | 115       | 0.96%   |
| Samsung SSD 860 EVO 500GB                           | 113       | 0.94%   |
| Kingston SA400S37240G 240GB SSD                     | 107       | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 100       | 0.83%   |
| Seagate ST1000LM035-1RK172 1TB                      | 96        | 0.8%    |
| Samsung SSD 860 EVO 1TB                             | 85        | 0.71%   |
| Samsung SSD 850 EVO 250GB                           | 85        | 0.71%   |
| Samsung NVMe SSD Drive 512GB                        | 82        | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB                      | 79        | 0.66%   |
| Samsung SSD 970 EVO Plus 1TB                        | 76        | 0.63%   |
| Crucial CT500MX500SSD1 500GB                        | 75        | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                         | 74        | 0.62%   |
| Samsung NVMe SSD Drive 1TB                          | 67        | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB                      | 65        | 0.54%   |
| Samsung NVMe SSD Drive 500GB                        | 64        | 0.53%   |
| Kingston SA400S37120G 120GB SSD                     | 62        | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB                      | 61        | 0.51%   |
| HGST HTS721010A9E630 1TB                            | 58        | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 56        | 0.47%   |
| Samsung SSD 860 EVO 250GB                           | 55        | 0.46%   |
| Toshiba MQ01ABD100 1TB                              | 54        | 0.45%   |
| Kingston SA400S37480G 480GB SSD                     | 53        | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 52        | 0.43%   |
| Toshiba DT01ACA100 1TB                              | 50        | 0.42%   |
| SanDisk NVMe SSD Drive 512GB                        | 50        | 0.42%   |
| SanDisk NVMe SSD Drive 1TB                          | 50        | 0.42%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 48        | 0.4%    |
| Samsung NVMe SSD Drive 256GB                        | 48        | 0.4%    |
| Seagate ST4000DM004-2CV104 4TB                      | 46        | 0.38%   |
| Unknown MMC Card  32GB                              | 45        | 0.37%   |
| Seagate ST500DM002-1BD142 500GB                     | 45        | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB                      | 44        | 0.37%   |
| Unknown MMC Card  64GB                              | 43        | 0.36%   |
| Toshiba MQ04ABF100 1TB                              | 43        | 0.36%   |
| SK hynix NVMe SSD Drive 512GB                       | 43        | 0.36%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 43        | 0.36%   |
| Samsung SSD 860 QVO 1TB                             | 43        | 0.36%   |
| Kingston SV300S37A120G 120GB SSD                    | 41        | 0.34%   |
| Samsung SSD 840 EVO 250GB                           | 40        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1229      | 1844   | 36.1%   |
| WDC                 | 1141      | 1739   | 33.52%  |
| Toshiba             | 458       | 602    | 13.45%  |
| HGST                | 177       | 223    | 5.2%    |
| Hitachi             | 169       | 209    | 4.96%   |
| Samsung Electronics | 114       | 152    | 3.35%   |
| Unknown             | 28        | 36     | 0.82%   |
| Apple               | 26        | 26     | 0.76%   |
| Fujitsu             | 11        | 11     | 0.32%   |
| Maxtor              | 7         | 7      | 0.21%   |
| ASMT                | 5         | 5      | 0.15%   |
| HGST HTS            | 4         | 4      | 0.12%   |
| USB3.0              | 3         | 4      | 0.09%   |
| SSK                 | 2         | 2      | 0.06%   |
| SAGE                | 2         | 2      | 0.06%   |
| LaCie               | 2         | 2      | 0.06%   |
| KESU                | 2         | 2      | 0.06%   |
| Hewlett-Packard     | 2         | 2      | 0.06%   |
| Generic-            | 2         | 3      | 0.06%   |
| ASMedia             | 2         | 2      | 0.06%   |
| USB                 | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 11     | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| NeoTech             | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| LIO-ORG             | 1         | 2      | 0.03%   |
| JMicron Technology  | 1         | 8      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| H/W                 | 1         | 1      | 0.03%   |
| Config              | 1         | 1      | 0.03%   |
| ASUSTOR             | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 977       | 1399   | 27.84%  |
| Kingston            | 430       | 555    | 12.25%  |
| Crucial             | 421       | 599    | 12%     |
| SanDisk             | 345       | 475    | 9.83%   |
| WDC                 | 233       | 302    | 6.64%   |
| A-DATA Technology   | 103       | 147    | 2.94%   |
| Intel               | 84        | 97     | 2.39%   |
| China               | 73        | 92     | 2.08%   |
| Toshiba             | 55        | 94     | 1.57%   |
| OCZ                 | 53        | 71     | 1.51%   |
| SK hynix            | 49        | 57     | 1.4%    |
| Micron Technology   | 45        | 55     | 1.28%   |
| Transcend           | 43        | 58     | 1.23%   |
| SPCC                | 43        | 46     | 1.23%   |
| PNY                 | 42        | 51     | 1.2%    |
| Patriot             | 40        | 50     | 1.14%   |
| LITEON              | 36        | 38     | 1.03%   |
| Apple               | 31        | 32     | 0.88%   |
| GOODRAM             | 27        | 35     | 0.77%   |
| Corsair             | 21        | 26     | 0.6%    |
| Plextor             | 20        | 21     | 0.57%   |
| Intenso             | 19        | 20     | 0.54%   |
| Lexar               | 17        | 23     | 0.48%   |
| LITEONIT            | 16        | 16     | 0.46%   |
| Team                | 15        | 17     | 0.43%   |
| KingSpec            | 15        | 16     | 0.43%   |
| Hewlett-Packard     | 12        | 13     | 0.34%   |
| Mushkin             | 10        | 15     | 0.28%   |
| Gigabyte Technology | 10        | 10     | 0.28%   |
| TO Exter            | 9         | 14     | 0.26%   |
| Netac               | 9         | 9      | 0.26%   |
| ASMT                | 9         | 10     | 0.26%   |
| Unknown             | 8         | 9      | 0.23%   |
| Seagate             | 7         | 7      | 0.2%    |
| FORESEE             | 6         | 9      | 0.17%   |
| External            | 6         | 7      | 0.17%   |
| KingDian            | 5         | 6      | 0.14%   |
| AMD                 | 5         | 6      | 0.14%   |
| XrayDisk            | 4         | 5      | 0.11%   |
| Unknown             | 4         | 4      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 3275      | 4856   | 35.1%   |
| SSD     | 2927      | 4706   | 31.37%  |
| HDD     | 2797      | 4913   | 29.98%  |
| MMC     | 233       | 278    | 2.5%    |
| Unknown | 99        | 120    | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4217      | 9326   | 52.43%  |
| NVMe | 3257      | 4811   | 40.49%  |
| SAS  | 336       | 458    | 4.18%   |
| MMC  | 233       | 278    | 2.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2991      | 4802   | 48.68%  |
| 0.51-1.0   | 1958      | 2864   | 31.87%  |
| 1.01-2.0   | 649       | 985    | 10.56%  |
| 3.01-4.0   | 218       | 370    | 3.55%   |
| 4.01-10.0  | 163       | 311    | 2.65%   |
| 2.01-3.0   | 139       | 225    | 2.26%   |
| 10.01-20.0 | 26        | 62     | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1446      | 21.73%  |
| 101-250        | 1402      | 21.07%  |
| 501-1000       | 1230      | 18.49%  |
| 1001-2000      | 905       | 13.6%   |
| More than 3000 | 684       | 10.28%  |
| 2001-3000      | 376       | 5.65%   |
| 51-100         | 248       | 3.73%   |
| Unknown        | 171       | 2.57%   |
| 21-50          | 101       | 1.52%   |
| 1-20           | 90        | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1285      | 18.55%  |
| 101-250        | 1201      | 17.34%  |
| 21-50          | 973       | 14.05%  |
| 251-500        | 868       | 12.53%  |
| 51-100         | 842       | 12.16%  |
| 501-1000       | 720       | 10.4%   |
| 1001-2000      | 443       | 6.4%    |
| More than 3000 | 254       | 3.67%   |
| Unknown        | 171       | 2.47%   |
| 2001-3000      | 168       | 2.43%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                                 | 13        | 15     | 1.73%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 13        | 13     | 1.73%   |
| HGST HTS721010A9E630 1TB                                        | 10        | 10     | 1.33%   |
| HGST HTS541010A9E680 1TB                                        | 8         | 8      | 1.07%   |
| Seagate ST500LT012-1DG142 500GB                                 | 7         | 8      | 0.93%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 7         | 10     | 0.93%   |
| Kingston SV300S37A120G 120GB SSD                                | 7         | 7      | 0.93%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 6         | 7      | 0.8%    |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 6         | 6      | 0.8%    |
| Seagate ST9500325AS 500GB                                       | 6         | 6      | 0.8%    |
| Seagate ST2000DM006-2DM164 2TB                                  | 6         | 7      | 0.8%    |
| Seagate ST1000LX015-1U7172 1TB                                  | 6         | 8      | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 6         | 10     | 0.8%    |
| OCZ VERTEX4 256GB SSD                                           | 6         | 9      | 0.8%    |
| WDC WD20EARS-00MVWB0 2TB                                        | 5         | 7      | 0.67%   |
| Toshiba MQ01ABD100 1TB                                          | 5         | 8      | 0.67%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 5         | 8      | 0.67%   |
| Seagate ST31000528AS 1TB                                        | 5         | 5      | 0.67%   |
| Seagate ST1000LM014-SSHD-8GB                                    | 5         | 5      | 0.67%   |
| Seagate ST1000DM003-9YN162 1TB                                  | 5         | 5      | 0.67%   |
| Samsung Electronics SSD 960 EVO 250GB                           | 5         | 11     | 0.67%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 250GB | 5         | 6      | 0.67%   |
| HGST HTS725050A7E630 500GB                                      | 5         | 5      | 0.67%   |
| HGST HTS545050A7E680 500GB                                      | 5         | 6      | 0.67%   |
| Crucial CT525MX300SSD1 528GB                                    | 5         | 7      | 0.67%   |
| WDC WD20EARX-00PASB0 2TB                                        | 4         | 4      | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 4         | 4      | 0.53%   |
| WDC WD10EZEX-00WN4A0 1TB                                        | 4         | 4      | 0.53%   |
| WDC WD10EARS-00Y5B1 1TB                                         | 4         | 6      | 0.53%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 4         | 4      | 0.53%   |
| Seagate ST9250315AS 250GB                                       | 4         | 4      | 0.53%   |
| Seagate ST3320620AS 320GB                                       | 4         | 4      | 0.53%   |
| Seagate ST2000LM007-1R8174 2TB                                  | 4         | 4      | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                                  | 4         | 4      | 0.53%   |
| Seagate ST2000DM001-1CH164 2TB                                  | 4         | 4      | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 4         | 4      | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 4         | 4      | 0.53%   |
| Samsung Electronics HD103SJ 1TB                                 | 4         | 6      | 0.53%   |
| LITEON CV8-8E128-HP 128GB SSD                                   | 4         | 4      | 0.53%   |
| WDC WD5000AAKX-00ERMA0 500GB                                    | 3         | 3      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 197       | 242    | 27.44%  |
| WDC                   | 160       | 214    | 22.28%  |
| Samsung Electronics   | 63        | 86     | 8.77%   |
| Toshiba               | 51        | 63     | 7.1%    |
| Hitachi               | 45        | 49     | 6.27%   |
| HGST                  | 35        | 36     | 4.87%   |
| Kingston              | 23        | 27     | 3.2%    |
| SanDisk               | 19        | 21     | 2.65%   |
| Intel                 | 19        | 22     | 2.65%   |
| Crucial               | 19        | 23     | 2.65%   |
| SK hynix              | 13        | 14     | 1.81%   |
| OCZ                   | 10        | 17     | 1.39%   |
| A-DATA Technology     | 9         | 10     | 1.25%   |
| Micron Technology     | 5         | 6      | 0.7%    |
| LITEON                | 5         | 5      | 0.7%    |
| Transcend             | 3         | 10     | 0.42%   |
| Hewlett-Packard       | 3         | 3      | 0.42%   |
| Drevo                 | 3         | 4      | 0.42%   |
| Corsair               | 3         | 3      | 0.42%   |
| ASMT                  | 3         | 3      | 0.42%   |
| Apple                 | 3         | 3      | 0.42%   |
| XrayDisk              | 2         | 3      | 0.28%   |
| SPCC                  | 2         | 3      | 0.28%   |
| Realtek Semiconductor | 2         | 3      | 0.28%   |
| PNY                   | 2         | 3      | 0.28%   |
| Plextor               | 2         | 9      | 0.28%   |
| Patriot               | 2         | 2      | 0.28%   |
| Maxtor                | 2         | 2      | 0.28%   |
| China                 | 2         | 2      | 0.28%   |
| VNYEZ                 | 1         | 1      | 0.14%   |
| SSSTC                 | 1         | 1      | 0.14%   |
| Silicon Motion        | 1         | 1      | 0.14%   |
| KingSpec              | 1         | 1      | 0.14%   |
| Kingrich              | 1         | 1      | 0.14%   |
| JMicron Technology    | 1         | 1      | 0.14%   |
| INNOVATION IT         | 1         | 1      | 0.14%   |
| GLOWAY                | 1         | 1      | 0.14%   |
| Gigabyte Technology   | 1         | 1      | 0.14%   |
| Fujitsu               | 1         | 1      | 0.14%   |
| BAITITON              | 1         | 4      | 0.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 197       | 242    | 38.93%  |
| WDC                 | 154       | 206    | 30.43%  |
| Toshiba             | 45        | 57     | 8.89%   |
| Hitachi             | 45        | 49     | 8.89%   |
| HGST                | 35        | 36     | 6.92%   |
| Samsung Electronics | 21        | 25     | 4.15%   |
| Apple               | 3         | 3      | 0.59%   |
| Maxtor              | 2         | 2      | 0.4%    |
| ASMT                | 2         | 2      | 0.4%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| Fujitsu             | 1         | 1      | 0.2%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 469       | 624    | 69.48%  |
| SSD  | 162       | 208    | 24%     |
| NVMe | 44        | 70     | 6.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD                 | 2         | 2      | 15.38%  |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 7.69%   |
| WDC WD3200BEKT-60V5T1 320GB                      | 1         | 1      | 7.69%   |
| WDC WD2500BEVT-22ZCT0 250GB                      | 1         | 1      | 7.69%   |
| Transcend TS128GMTE850 128GB                     | 1         | 1      | 7.69%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 7.69%   |
| Seagate ST32000644NS 2TB                         | 1         | 1      | 7.69%   |
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 7.69%   |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 7.69%   |
| Samsung Electronics MZ7PC128HAFU-000H1 128GB SSD | 1         | 1      | 7.69%   |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 7.69%   |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 30.77%  |
| WDC                 | 3         | 3      | 23.08%  |
| Seagate             | 2         | 2      | 15.38%  |
| Kingston            | 2         | 2      | 15.38%  |
| Transcend           | 1         | 1      | 7.69%   |
| Phison              | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3383      | 7465   | 46.86%  |
| Detected | 3178      | 6491   | 44.02%  |
| Malfunc  | 644       | 902    | 8.92%   |
| Failed   | 13        | 14     | 0.18%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3520      | 38.96%  |
| AMD                              | 1722      | 19.06%  |
| Samsung Electronics              | 1309      | 14.49%  |
| SanDisk                          | 538       | 5.96%   |
| SK hynix                         | 276       | 3.06%   |
| Phison Electronics               | 242       | 2.68%   |
| ASMedia Technology               | 182       | 2.01%   |
| Kingston Technology Company      | 171       | 1.89%   |
| Micron Technology                | 151       | 1.67%   |
| Toshiba America Info Systems     | 148       | 1.64%   |
| Micron/Crucial Technology        | 121       | 1.34%   |
| ADATA Technology                 | 103       | 1.14%   |
| Silicon Motion                   | 87        | 0.96%   |
| Marvell Technology Group         | 70        | 0.77%   |
| KIOXIA                           | 68        | 0.75%   |
| JMicron Technology               | 40        | 0.44%   |
| Realtek Semiconductor            | 39        | 0.43%   |
| Union Memory (Shenzhen)          | 24        | 0.27%   |
| Lite-On Technology               | 20        | 0.22%   |
| Broadcom / LSI                   | 19        | 0.21%   |
| Nvidia                           | 18        | 0.2%    |
| Lenovo                           | 18        | 0.2%    |
| Solid State Storage Technology   | 17        | 0.19%   |
| Apple                            | 16        | 0.18%   |
| Seagate Technology               | 15        | 0.17%   |
| MAXIO Technology (Hangzhou)      | 14        | 0.15%   |
| Yangtze Memory Technologies      | 13        | 0.14%   |
| LSI Logic / Symbios Logic        | 11        | 0.12%   |
| Adaptec                          | 10        | 0.11%   |
| VIA Technologies                 | 7         | 0.08%   |
| Silicon Image                    | 7         | 0.08%   |
| Shenzhen Longsys Electronics     | 7         | 0.08%   |
| Hewlett-Packard                  | 6         | 0.07%   |
| Silicon Integrated Systems [SiS] | 4         | 0.04%   |
| OCZ Technology Group             | 4         | 0.04%   |
| Netac Technology                 | 4         | 0.04%   |
| INNOGRIT                         | 3         | 0.03%   |
| Biwin Storage Technology         | 3         | 0.03%   |
| Integrated Technology Express    | 2         | 0.02%   |
| Transcend                        | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1304      | 12.92%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 765       | 7.58%   |
| AMD 400 Series Chipset SATA Controller                                         | 403       | 3.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 337       | 3.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 227       | 2.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 213       | 2.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 205       | 2.03%   |
| Samsung NVMe SSD Controller 980                                                | 199       | 1.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 188       | 1.86%   |
| AMD 500 Series Chipset SATA Controller                                         | 185       | 1.83%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 173       | 1.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 169       | 1.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 163       | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 162       | 1.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 151       | 1.5%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 144       | 1.43%   |
| Intel Volume Management Device NVMe RAID Controller                            | 134       | 1.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 128       | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 124       | 1.23%   |
| Phison E12 NVMe Controller                                                     | 123       | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 120       | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 112       | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 110       | 1.09%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 107       | 1.06%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 105       | 1.04%   |
| Intel SSD 660P Series                                                          | 102       | 1.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 101       | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 82        | 0.81%   |
| Micron NVMe Storage Controller                                                 | 81        | 0.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 79        | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 78        | 0.77%   |
| Intel SATA Controller [RAID mode]                                              | 75        | 0.74%   |
| AMD 300 Series Chipset SATA Controller                                         | 74        | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 69        | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 67        | 0.66%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 65        | 0.64%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 64        | 0.63%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 62        | 0.61%   |
| AMD X370 Series Chipset SATA Controller                                        | 62        | 0.61%   |
| Intel Comet Lake SATA AHCI Controller                                          | 59        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4616      | 52.94%  |
| NVMe | 3272      | 37.53%  |
| RAID | 485       | 5.56%   |
| IDE  | 315       | 3.61%   |
| SAS  | 23        | 0.26%   |
| SCSI | 8         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor     | Computers | Percent |
|------------|-----------|---------|
| Intel      | 4233      | 66.47%  |
| AMD        | 2134      | 33.51%  |
| thead,c906 | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 113       | 1.77%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 106       | 1.66%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 98        | 1.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 87        | 1.36%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 80        | 1.25%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 78        | 1.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 78        | 1.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 78        | 1.22%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 76        | 1.19%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 75        | 1.17%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 73        | 1.14%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 68        | 1.06%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 64        | 1%      |
| AMD Ryzen 9 3900X 12-Core Processor           | 55        | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 54        | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 52        | 0.81%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 52        | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 51        | 0.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 51        | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 51        | 0.8%    |
| AMD Ryzen 7 5800X 8-Core Processor            | 49        | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 48        | 0.75%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 47        | 0.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 46        | 0.72%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 45        | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 43        | 0.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 42        | 0.66%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 42        | 0.66%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 42        | 0.66%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 41        | 0.64%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 40        | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 37        | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 37        | 0.58%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 37        | 0.58%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 37        | 0.58%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 36        | 0.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 35        | 0.55%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 35        | 0.55%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 35        | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 32        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1448      | 22.71%  |
| Intel Core i5           | 1336      | 20.95%  |
| AMD Ryzen 5             | 699       | 10.96%  |
| AMD Ryzen 7             | 643       | 10.08%  |
| Other                   | 464       | 7.28%   |
| Intel Core i3           | 295       | 4.63%   |
| AMD Ryzen 9             | 242       | 3.8%    |
| Intel Celeron           | 159       | 2.49%   |
| Intel Xeon              | 122       | 1.91%   |
| Intel Core 2 Duo        | 105       | 1.65%   |
| AMD Ryzen 3             | 97        | 1.52%   |
| Intel Pentium           | 89        | 1.4%    |
| AMD FX                  | 86        | 1.35%   |
| AMD Ryzen 7 PRO         | 71        | 1.11%   |
| Intel Core i9           | 68        | 1.07%   |
| Intel Atom              | 55        | 0.86%   |
| AMD A8                  | 32        | 0.5%    |
| AMD Ryzen Threadripper  | 31        | 0.49%   |
| AMD Ryzen 5 PRO         | 29        | 0.45%   |
| Intel Core 2 Quad       | 26        | 0.41%   |
| AMD A6                  | 26        | 0.41%   |
| AMD A10                 | 25        | 0.39%   |
| AMD Athlon              | 19        | 0.3%    |
| Intel Pentium Dual-Core | 18        | 0.28%   |
| AMD A4                  | 17        | 0.27%   |
| Intel Pentium Silver    | 16        | 0.25%   |
| AMD Phenom II X4        | 14        | 0.22%   |
| Intel Genuine           | 10        | 0.16%   |
| Intel Core m3           | 9         | 0.14%   |
| AMD E2                  | 9         | 0.14%   |
| AMD Athlon II X4        | 8         | 0.13%   |
| Intel Core 2            | 7         | 0.11%   |
| AMD E                   | 7         | 0.11%   |
| AMD Athlon II X2        | 7         | 0.11%   |
| Intel Pentium Dual      | 6         | 0.09%   |
| AMD Phenom II X6        | 6         | 0.09%   |
| AMD E1                  | 6         | 0.09%   |
| AMD Athlon 64 X2        | 6         | 0.09%   |
| Intel Core m5           | 5         | 0.08%   |
| AMD Athlon X4           | 4         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2387      | 37.41%  |
| 2       | 1609      | 25.22%  |
| 6       | 1008      | 15.8%   |
| 8       | 913       | 14.31%  |
| 12      | 185       | 2.9%    |
| 16      | 102       | 1.6%    |
| 14      | 40        | 0.63%   |
| 10      | 40        | 0.63%   |
| 1       | 36        | 0.56%   |
| 3       | 28        | 0.44%   |
| 24      | 12        | 0.19%   |
| 32      | 7         | 0.11%   |
| 64      | 4         | 0.06%   |
| Unknown | 3         | 0.05%   |
| 18      | 2         | 0.03%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 22      | 1         | 0.02%   |
| 20      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6331      | 99.42%  |
| 2       | 36        | 0.57%   |
| Unknown | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5090      | 79.83%  |
| 1       | 1283      | 20.12%  |
| Unknown | 3         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6259      | 98.13%  |
| Unknown        | 115       | 1.8%    |
| 32-bit         | 4         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2244      | 33.82%  |
| 0x08701021 | 206       | 3.1%    |
| 0x306a9    | 205       | 3.09%   |
| 0x906ea    | 201       | 3.03%   |
| 0x306c3    | 200       | 3.01%   |
| 0x206a7    | 179       | 2.7%    |
| 0x906e9    | 172       | 2.59%   |
| 0x806ea    | 168       | 2.53%   |
| 0x0800820d | 149       | 2.25%   |
| 0x806ec    | 137       | 2.06%   |
| 0x806c1    | 136       | 2.05%   |
| 0x506e3    | 122       | 1.84%   |
| 0x406e3    | 110       | 1.66%   |
| 0x0a50000c | 109       | 1.64%   |
| 0x806e9    | 104       | 1.57%   |
| 0x08701013 | 97        | 1.46%   |
| 0x306d4    | 90        | 1.36%   |
| 0x40651    | 87        | 1.31%   |
| 0x08108102 | 87        | 1.31%   |
| 0x08600106 | 81        | 1.22%   |
| 0x08108109 | 77        | 1.16%   |
| 0x1067a    | 68        | 1.02%   |
| 0xa0652    | 61        | 0.92%   |
| 0x08001138 | 60        | 0.9%    |
| 0x0a201016 | 57        | 0.86%   |
| 0x08600104 | 52        | 0.78%   |
| 0x20655    | 50        | 0.75%   |
| 0x0a201009 | 50        | 0.75%   |
| 0x806eb    | 46        | 0.69%   |
| 0x08608103 | 45        | 0.68%   |
| 0x08600103 | 43        | 0.65%   |
| 0x706e5    | 38        | 0.57%   |
| 0x906ed    | 36        | 0.54%   |
| 0x0810100b | 35        | 0.53%   |
| 0x906a3    | 28        | 0.42%   |
| 0x08001137 | 28        | 0.42%   |
| 0x406c4    | 27        | 0.41%   |
| 0x0a601203 | 27        | 0.41%   |
| 0x0a50000d | 27        | 0.41%   |
| 0x06000852 | 27        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1380      | 21.61%  |
| Zen 2            | 626       | 9.8%    |
| Haswell          | 476       | 7.45%   |
| Zen+             | 414       | 6.48%   |
| Zen 3            | 396       | 6.2%    |
| Skylake          | 382       | 5.98%   |
| IvyBridge        | 321       | 5.03%   |
| SandyBridge      | 282       | 4.42%   |
| Unknown          | 277       | 4.34%   |
| TigerLake        | 233       | 3.65%   |
| Zen              | 221       | 3.46%   |
| CometLake        | 178       | 2.79%   |
| Broadwell        | 150       | 2.35%   |
| Penryn           | 140       | 2.19%   |
| Piledriver       | 105       | 1.64%   |
| IceLake          | 105       | 1.64%   |
| Silvermont       | 104       | 1.63%   |
| Westmere         | 103       | 1.61%   |
| Alderlake Hybrid | 91        | 1.43%   |
| Goldmont plus    | 55        | 0.86%   |
| K10              | 49        | 0.77%   |
| Excavator        | 43        | 0.67%   |
| Core             | 42        | 0.66%   |
| Nehalem          | 41        | 0.64%   |
| Goldmont         | 32        | 0.5%    |
| K10 Llano        | 20        | 0.31%   |
| Bonnell          | 19        | 0.3%    |
| Bobcat           | 19        | 0.3%    |
| Steamroller      | 17        | 0.27%   |
| Puma             | 14        | 0.22%   |
| Jaguar           | 13        | 0.2%    |
| K8 Hammer        | 10        | 0.16%   |
| Tremont          | 9         | 0.14%   |
| NetBurst         | 7         | 0.11%   |
| Bulldozer        | 6         | 0.09%   |
| P6               | 2         | 0.03%   |
| K8 & K10 hybrid  | 2         | 0.03%   |
| Gracemont        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3287      | 41.64%  |
| Nvidia                           | 2478      | 31.39%  |
| AMD                              | 2093      | 26.52%  |
| Matrox Electronics Systems       | 17        | 0.22%   |
| ASPEED Technology                | 10        | 0.13%   |
| Silicon Integrated Systems [SiS] | 4         | 0.05%   |
| ATI Technologies                 | 3         | 0.04%   |
| VIA Technologies                 | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 290       | 3.59%   |
| Intel UHD Graphics 620                                                                   | 245       | 3.03%   |
| AMD Renoir                                                                               | 221       | 2.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 215       | 2.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 209       | 2.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 201       | 2.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 190       | 2.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 189       | 2.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 171       | 2.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 157       | 1.94%   |
| Intel HD Graphics 630                                                                    | 151       | 1.87%   |
| Intel HD Graphics 620                                                                    | 149       | 1.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 144       | 1.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 133       | 1.65%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 133       | 1.65%   |
| Intel HD Graphics 5500                                                                   | 113       | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 102       | 1.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 102       | 1.26%   |
| Intel HD Graphics 530                                                                    | 98        | 1.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 94        | 1.16%   |
| AMD Lucienne                                                                             | 94        | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 92        | 1.14%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 82        | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 80        | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 79        | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 78        | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 75        | 0.93%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 71        | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 64        | 0.79%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 64        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 61        | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 59        | 0.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 58        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 57        | 0.71%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 56        | 0.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 52        | 0.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 51        | 0.63%   |
| AMD Rembrandt [Radeon 680M]                                                              | 51        | 0.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 50        | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 48        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2013      | 31.33%  |
| 1 x AMD                  | 1606      | 25%     |
| 1 x Nvidia               | 1193      | 18.57%  |
| Intel + Nvidia           | 1032      | 16.06%  |
| AMD + Nvidia             | 220       | 3.42%   |
| Intel + AMD              | 164       | 2.55%   |
| 2 x AMD                  | 106       | 1.65%   |
| 2 x Nvidia               | 32        | 0.5%    |
| 1 x Matrox               | 13        | 0.2%    |
| 2 x Intel                | 12        | 0.19%   |
| Other                    | 8         | 0.12%   |
| 1 x ASPEED               | 5         | 0.08%   |
| 1 x SiS                  | 4         | 0.06%   |
| AMD + ASPEED             | 4         | 0.06%   |
| 2 x AMD + 1 x Nvidia     | 2         | 0.03%   |
| Nvidia + Matrox          | 2         | 0.03%   |
| Intel + 2 x Nvidia       | 2         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.03%   |
| AMD + Matrox             | 2         | 0.03%   |
| 3 x Nvidia               | 1         | 0.02%   |
| 1 x VIA                  | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4635      | 72.02%  |
| Proprietary | 1743      | 27.08%  |
| Unknown     | 58        | 0.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3567      | 54.31%  |
| 7.01-8.0   | 640       | 9.74%   |
| 1.01-2.0   | 589       | 8.97%   |
| 3.01-4.0   | 506       | 7.7%    |
| 0.01-0.5   | 489       | 7.45%   |
| 0.51-1.0   | 262       | 3.99%   |
| 5.01-6.0   | 256       | 3.9%    |
| 8.01-16.0  | 189       | 2.88%   |
| 2.01-3.0   | 54        | 0.82%   |
| 16.01-24.0 | 13        | 0.2%    |
| 4.01-5.0   | 3         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 852       | 11%     |
| AU Optronics            | 848       | 10.94%  |
| BOE                     | 691       | 8.92%   |
| Chimei Innolux          | 609       | 7.86%   |
| LG Display              | 601       | 7.76%   |
| Dell                    | 541       | 6.98%   |
| Goldstar                | 465       | 6%      |
| Acer                    | 302       | 3.9%    |
| AOC                     | 258       | 3.33%   |
| BenQ                    | 235       | 3.03%   |
| Hewlett-Packard         | 226       | 2.92%   |
| Sharp                   | 211       | 2.72%   |
| Ancor Communications    | 194       | 2.5%    |
| Philips                 | 143       | 1.85%   |
| Lenovo                  | 131       | 1.69%   |
| PANDA                   | 113       | 1.46%   |
| ViewSonic               | 102       | 1.32%   |
| Apple                   | 92        | 1.19%   |
| ASUSTek Computer        | 85        | 1.1%    |
| Iiyama                  | 83        | 1.07%   |
| InfoVision              | 59        | 0.76%   |
| LG Electronics          | 55        | 0.71%   |
| Sony                    | 43        | 0.55%   |
| MSI                     | 40        | 0.52%   |
| CSO                     | 39        | 0.5%    |
| Unknown                 | 37        | 0.48%   |
| NEC Computers           | 36        | 0.46%   |
| Gigabyte Technology     | 33        | 0.43%   |
| Eizo                    | 32        | 0.41%   |
| Chi Mei Optoelectronics | 30        | 0.39%   |
| Panasonic               | 21        | 0.27%   |
| Fujitsu Siemens         | 21        | 0.27%   |
| Sceptre Tech            | 17        | 0.22%   |
| Unknown                 | 17        | 0.22%   |
| Toshiba                 | 16        | 0.21%   |
| HannStar                | 15        | 0.19%   |
| Vizio                   | 14        | 0.18%   |
| TMX                     | 14        | 0.18%   |
| Pixio                   | 13        | 0.17%   |
| Valve                   | 12        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 50        | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 41        | 0.51%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 36        | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 34        | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 31        | 0.38%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 31        | 0.38%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 28        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 27        | 0.33%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 26        | 0.32%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 25        | 0.31%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 24        | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 23        | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 22        | 0.27%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 22        | 0.27%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 19        | 0.23%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 19        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 18        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 18        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 18        | 0.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch         | 17        | 0.21%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 17        | 0.21%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch     | 17        | 0.21%   |
| Unknown                                                              | 17        | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 16        | 0.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 15        | 0.19%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 15        | 0.19%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 15        | 0.19%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 15        | 0.19%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 14        | 0.17%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 14        | 0.17%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 14        | 0.17%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 14        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 14        | 0.17%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 14        | 0.17%   |
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                     | 14        | 0.17%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 13        | 0.16%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 13        | 0.16%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 12        | 0.15%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch         | 12        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3534      | 48.46%  |
| 1366x768 (WXGA)    | 839       | 11.51%  |
| 3840x2160 (4K)     | 574       | 7.87%   |
| 2560x1440 (QHD)    | 571       | 7.83%   |
| 1920x1200 (WUXGA)  | 210       | 2.88%   |
| 1600x900 (HD+)     | 196       | 2.69%   |
| 1680x1050 (WSXGA+) | 143       | 1.96%   |
| 3440x1440          | 133       | 1.82%   |
| Unknown            | 125       | 1.71%   |
| 1280x1024 (SXGA)   | 122       | 1.67%   |
| 1440x900 (WXGA+)   | 97        | 1.33%   |
| 2560x1080          | 89        | 1.22%   |
| 2560x1600          | 69        | 0.95%   |
| 1280x800 (WXGA)    | 58        | 0.8%    |
| 3840x1080          | 55        | 0.75%   |
| 2880x1800          | 48        | 0.66%   |
| 1360x768           | 47        | 0.64%   |
| 3840x2400          | 39        | 0.53%   |
| 3840x1600          | 22        | 0.3%    |
| 2256x1504          | 22        | 0.3%    |
| 3200x1800 (QHD+)   | 21        | 0.29%   |
| 2160x1440          | 21        | 0.29%   |
| 1920x540           | 20        | 0.27%   |
| 2736x1824          | 16        | 0.22%   |
| 3000x2000          | 12        | 0.16%   |
| 3072x1920          | 10        | 0.14%   |
| 1920x1280          | 10        | 0.14%   |
| 7680x2160          | 9         | 0.12%   |
| 5760x1080          | 9         | 0.12%   |
| 5120x1440          | 8         | 0.11%   |
| 4480x1440          | 8         | 0.11%   |
| 2240x1400          | 8         | 0.11%   |
| 1600x1200          | 8         | 0.11%   |
| 1280x720 (HD)      | 7         | 0.1%    |
| 1024x600           | 7         | 0.1%    |
| 3200x2000          | 6         | 0.08%   |
| 1024x768 (XGA)     | 6         | 0.08%   |
| 6400x2160          | 5         | 0.07%   |
| 3840x1200          | 5         | 0.07%   |
| 2520x1680          | 5         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1716      | 22.28%  |
| 13      | 779       | 10.11%  |
| 27      | 753       | 9.78%   |
| 24      | 735       | 9.54%   |
| 14      | 653       | 8.48%   |
| 23      | 512       | 6.65%   |
| 21      | 433       | 5.62%   |
| Unknown | 386       | 5.01%   |
| 17      | 265       | 3.44%   |
| 34      | 183       | 2.38%   |
| 31      | 166       | 2.16%   |
| 19      | 147       | 1.91%   |
| 12      | 132       | 1.71%   |
| 22      | 103       | 1.34%   |
| 18      | 103       | 1.34%   |
| 20      | 72        | 0.93%   |
| 16      | 70        | 0.91%   |
| 11      | 58        | 0.75%   |
| 84      | 42        | 0.55%   |
| 72      | 41        | 0.53%   |
| 25      | 37        | 0.48%   |
| 40      | 28        | 0.36%   |
| 48      | 25        | 0.32%   |
| 54      | 24        | 0.31%   |
| 32      | 24        | 0.31%   |
| 28      | 23        | 0.3%    |
| 26      | 20        | 0.26%   |
| 10      | 20        | 0.26%   |
| 37      | 19        | 0.25%   |
| 29      | 18        | 0.23%   |
| 46      | 11        | 0.14%   |
| 35      | 11        | 0.14%   |
| 33      | 10        | 0.13%   |
| 65      | 8         | 0.1%    |
| 49      | 7         | 0.09%   |
| 43      | 7         | 0.09%   |
| 42      | 6         | 0.08%   |
| 39      | 6         | 0.08%   |
| 74      | 5         | 0.06%   |
| 57      | 5         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2775      | 37.22%  |
| 501-600        | 1785      | 23.94%  |
| 401-500        | 758       | 10.17%  |
| 201-300        | 638       | 8.56%   |
| Unknown        | 386       | 5.18%   |
| 351-400        | 337       | 4.52%   |
| 601-700        | 281       | 3.77%   |
| 701-800        | 220       | 2.95%   |
| 1001-1500      | 98        | 1.31%   |
| 1501-2000      | 89        | 1.19%   |
| 801-900        | 69        | 0.93%   |
| 901-1000       | 14        | 0.19%   |
| 1-100          | 3         | 0.04%   |
| 101-200        | 2         | 0.03%   |
| More than 2000 | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5081      | 75.84%  |
| 16/10   | 743       | 11.09%  |
| Unknown | 330       | 4.93%   |
| 21/9    | 228       | 3.4%    |
| 5/4     | 124       | 1.85%   |
| 3/2     | 112       | 1.67%   |
| 32/9    | 33        | 0.49%   |
| 4/3     | 31        | 0.46%   |
| 2.65    | 4         | 0.06%   |
| 6/5     | 2         | 0.03%   |
| 3.40    | 2         | 0.03%   |
| 2.00    | 2         | 0.03%   |
| 1.96    | 2         | 0.03%   |
| 3.20    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.57    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1707      | 22.51%  |
| 201-250        | 1397      | 18.42%  |
| 81-90          | 1078      | 14.21%  |
| 301-350        | 772       | 10.18%  |
| 351-500        | 414       | 5.46%   |
| Unknown        | 386       | 5.09%   |
| 71-80          | 354       | 4.67%   |
| 151-200        | 309       | 4.07%   |
| 251-300        | 263       | 3.47%   |
| 121-130        | 183       | 2.41%   |
| More than 1000 | 146       | 1.93%   |
| 141-150        | 139       | 1.83%   |
| 61-70          | 118       | 1.56%   |
| 501-1000       | 115       | 1.52%   |
| 111-120        | 65        | 0.86%   |
| 51-60          | 62        | 0.82%   |
| 131-140        | 30        | 0.4%    |
| 91-100         | 24        | 0.32%   |
| 41-50          | 18        | 0.24%   |
| 1-40           | 4         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2215      | 30.3%   |
| 51-100        | 2152      | 29.44%  |
| 101-120       | 1558      | 21.31%  |
| 161-240       | 614       | 8.4%    |
| Unknown       | 386       | 5.28%   |
| More than 240 | 268       | 3.67%   |
| 1-50          | 117       | 1.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4726      | 72.46%  |
| 2     | 1409      | 21.6%   |
| 3     | 241       | 3.7%    |
| 0     | 124       | 1.9%    |
| 4     | 19        | 0.29%   |
| 5     | 2         | 0.03%   |
| 6     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3605      | 37.93%  |
| Realtek Semiconductor             | 3435      | 36.14%  |
| Qualcomm Atheros                  | 882       | 9.28%   |
| Broadcom                          | 331       | 3.48%   |
| MediaTek                          | 181       | 1.9%    |
| TP-Link                           | 99        | 1.04%   |
| Ralink Technology                 | 80        | 0.84%   |
| Microsoft                         | 67        | 0.7%    |
| Broadcom Limited                  | 64        | 0.67%   |
| Marvell Technology Group          | 57        | 0.6%    |
| ASIX Electronics                  | 51        | 0.54%   |
| Ralink                            | 46        | 0.48%   |
| Lenovo                            | 45        | 0.47%   |
| Qualcomm                          | 36        | 0.38%   |
| Sierra Wireless                   | 34        | 0.36%   |
| Samsung Electronics               | 32        | 0.34%   |
| Xiaomi                            | 29        | 0.31%   |
| DisplayLink                       | 27        | 0.28%   |
| Ericsson Business Mobile Networks | 26        | 0.27%   |
| Aquantia                          | 26        | 0.27%   |
| D-Link                            | 23        | 0.24%   |
| NetGear                           | 21        | 0.22%   |
| Qualcomm Atheros Communications   | 18        | 0.19%   |
| Google                            | 18        | 0.19%   |
| Dell                              | 18        | 0.19%   |
| Apple                             | 16        | 0.17%   |
| Hewlett-Packard                   | 15        | 0.16%   |
| Nvidia                            | 14        | 0.15%   |
| Huawei Technologies               | 14        | 0.15%   |
| Microchip Technology              | 11        | 0.12%   |
| Mellanox Technologies             | 11        | 0.12%   |
| ASUSTek Computer                  | 10        | 0.11%   |
| Linksys                           | 8         | 0.08%   |
| D-Link System                     | 8         | 0.08%   |
| Cypress Semiconductor             | 8         | 0.08%   |
| OPPO Electronics                  | 7         | 0.07%   |
| Fibocom                           | 7         | 0.07%   |
| Motorola PCS                      | 6         | 0.06%   |
| JMicron Technology                | 6         | 0.06%   |
| Edimax Technology                 | 6         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2428      | 21.67%  |
| Intel Wi-Fi 6 AX200                                               | 549       | 4.9%    |
| Intel I211 Gigabit Network Connection                             | 382       | 3.41%   |
| Intel Wireless 8265 / 8275                                        | 275       | 2.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 250       | 2.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 211       | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 208       | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 179       | 1.6%    |
| Intel Wi-Fi 6 AX201                                               | 172       | 1.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 167       | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 163       | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 161       | 1.44%   |
| Intel Ethernet Connection (2) I219-V                              | 158       | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 152       | 1.36%   |
| Intel Wireless 7265                                               | 143       | 1.28%   |
| Intel Wireless 8260                                               | 141       | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 126       | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 118       | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 113       | 1.01%   |
| Intel Wireless 7260                                               | 107       | 0.95%   |
| Intel Wireless-AC 9260                                            | 103       | 0.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 100       | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 96        | 0.86%   |
| Intel Wireless 3165                                               | 94        | 0.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 93        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 91        | 0.81%   |
| Intel Ethernet Controller I225-V                                  | 90        | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 90        | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 89        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 88        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 86        | 0.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 81        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 80        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 75        | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 67        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 66        | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 57        | 0.51%   |
| Intel Wireless 3160                                               | 51        | 0.46%   |
| Intel Ethernet Connection (2) I218-V                              | 50        | 0.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 47        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2824      | 54.07%  |
| Realtek Semiconductor           | 739       | 14.15%  |
| Qualcomm Atheros                | 691       | 13.23%  |
| Broadcom                        | 254       | 4.86%   |
| MediaTek                        | 177       | 3.39%   |
| TP-Link                         | 85        | 1.63%   |
| Ralink Technology               | 80        | 1.53%   |
| Microsoft                       | 60        | 1.15%   |
| Broadcom Limited                | 49        | 0.94%   |
| Ralink                          | 46        | 0.88%   |
| Sierra Wireless                 | 34        | 0.65%   |
| Qualcomm                        | 31        | 0.59%   |
| D-Link                          | 20        | 0.38%   |
| NetGear                         | 19        | 0.36%   |
| Qualcomm Atheros Communications | 18        | 0.34%   |
| Marvell Technology Group        | 18        | 0.34%   |
| Dell                            | 11        | 0.21%   |
| ASUSTek Computer                | 10        | 0.19%   |
| Linksys                         | 8         | 0.15%   |
| Fibocom                         | 7         | 0.13%   |
| Hewlett-Packard                 | 6         | 0.11%   |
| Edimax Technology               | 6         | 0.11%   |
| D-Link System                   | 4         | 0.08%   |
| AVM                             | 4         | 0.08%   |
| Wilocity                        | 3         | 0.06%   |
| Mercucys                        | 3         | 0.06%   |
| Belkin Components               | 3         | 0.06%   |
| Xiaomi                          | 2         | 0.04%   |
| Realtek                         | 2         | 0.04%   |
| Micro Star International        | 2         | 0.04%   |
| IMC Networks                    | 2         | 0.04%   |
| ZyXEL Communications            | 1         | 0.02%   |
| Yoctopuce Sarl                  | 1         | 0.02%   |
| Sagem                           | 1         | 0.02%   |
| Quectel Wireless Solutions      | 1         | 0.02%   |
| AboCom Systems                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 549       | 10.47%  |
| Intel Wireless 8265 / 8275                                     | 275       | 5.24%   |
| Intel Wi-Fi 6 AX201                                            | 172       | 3.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 167       | 3.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 163       | 3.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 161       | 3.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 152       | 2.9%    |
| Intel Wireless 7265                                            | 143       | 2.73%   |
| Intel Wireless 8260                                            | 141       | 2.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 126       | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 118       | 2.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 113       | 2.15%   |
| Intel Wireless 7260                                            | 107       | 2.04%   |
| Intel Wireless-AC 9260                                         | 103       | 1.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 100       | 1.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 96        | 1.83%   |
| Intel Wireless 3165                                            | 94        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 93        | 1.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 91        | 1.73%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 90        | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 89        | 1.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 88        | 1.68%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 81        | 1.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 80        | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 67        | 1.28%   |
| Intel Wireless 3160                                            | 51        | 0.97%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 47        | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 45        | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 44        | 0.84%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 44        | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 41        | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 40        | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 39        | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 35        | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 34        | 0.65%   |
| Microsoft Xbox 360 Wireless Adapter                            | 32        | 0.61%   |
| Realtek 802.11ac NIC                                           | 31        | 0.59%   |
| Broadcom BCM43142 802.11b/g/n                                  | 31        | 0.59%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 30        | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 29        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3114      | 54.76%  |
| Intel                                  | 1787      | 31.42%  |
| Qualcomm Atheros                       | 252       | 4.43%   |
| Broadcom                               | 124       | 2.18%   |
| ASIX Electronics                       | 51        | 0.9%    |
| Lenovo                                 | 43        | 0.76%   |
| Marvell Technology Group               | 39        | 0.69%   |
| Xiaomi                                 | 27        | 0.47%   |
| DisplayLink                            | 27        | 0.47%   |
| Aquantia                               | 26        | 0.46%   |
| Samsung Electronics                    | 18        | 0.32%   |
| Google                                 | 16        | 0.28%   |
| Apple                                  | 16        | 0.28%   |
| Broadcom Limited                       | 15        | 0.26%   |
| TP-Link                                | 14        | 0.25%   |
| Nvidia                                 | 14        | 0.25%   |
| Mellanox Technologies                  | 11        | 0.19%   |
| Cypress Semiconductor                  | 8         | 0.14%   |
| OPPO Electronics                       | 7         | 0.12%   |
| Huawei Technologies                    | 7         | 0.12%   |
| Microsoft                              | 6         | 0.11%   |
| JMicron Technology                     | 6         | 0.11%   |
| Qualcomm                               | 5         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.07%   |
| Motorola PCS                           | 4         | 0.07%   |
| MediaTek                               | 4         | 0.07%   |
| ICS Advent                             | 4         | 0.07%   |
| D-Link System                          | 4         | 0.07%   |
| QLogic                                 | 3         | 0.05%   |
| Hewlett-Packard                        | 3         | 0.05%   |
| D-Link                                 | 3         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.04%   |
| NetGear                                | 2         | 0.04%   |
| IBM                                    | 2         | 0.04%   |
| HMD Global                             | 2         | 0.04%   |
| American Megatrends                    | 2         | 0.04%   |
| VIA Technologies                       | 1         | 0.02%   |
| Standard Microsystems [SMC]            | 1         | 0.02%   |
| QNAP System                            | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2428      | 41.64%  |
| Intel I211 Gigabit Network Connection                             | 382       | 6.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 250       | 4.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 211       | 3.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 208       | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 179       | 3.07%   |
| Intel Ethernet Connection (2) I219-V                              | 158       | 2.71%   |
| Intel Ethernet Controller I225-V                                  | 90        | 1.54%   |
| Intel Ethernet Connection (7) I219-V                              | 86        | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 75        | 1.29%   |
| Intel Ethernet Connection (4) I219-LM                             | 66        | 1.13%   |
| Intel Ethernet Connection (4) I219-V                              | 57        | 0.98%   |
| Intel Ethernet Connection (2) I218-V                              | 50        | 0.86%   |
| Intel Ethernet Connection (6) I219-V                              | 46        | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 46        | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 44        | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 43        | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 42        | 0.72%   |
| Intel Ethernet Connection I219-LM                                 | 41        | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 40        | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 40        | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 37        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 36        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 0.58%   |
| Intel 82577LM Gigabit Network Connection                          | 31        | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 30        | 0.51%   |
| Intel I210 Gigabit Network Connection                             | 29        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 27        | 0.46%   |
| Intel Ethernet Connection I217-V                                  | 26        | 0.45%   |
| Intel Ethernet Connection (6) I219-LM                             | 25        | 0.43%   |
| Intel 82567LM Gigabit Network Connection                          | 24        | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 23        | 0.39%   |
| Intel Ethernet Connection (10) I219-V                             | 23        | 0.39%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 23        | 0.39%   |
| Intel 82574L Gigabit Network Connection                           | 22        | 0.38%   |
| Intel Ethernet Connection I219-V                                  | 21        | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18        | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 17        | 0.29%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17        | 0.29%   |
| Intel Ethernet Connection (13) I219-V                             | 17        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5307      | 51%     |
| WiFi     | 4972      | 47.78%  |
| Modem    | 113       | 1.09%   |
| Unknown  | 13        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3804      | 56.64%  |
| Ethernet | 2907      | 43.28%  |
| Modem    | 5         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3375      | 52.77%  |
| 1     | 2745      | 42.92%  |
| 3     | 186       | 2.91%   |
| 0     | 55        | 0.86%   |
| 4     | 20        | 0.31%   |
| 5     | 7         | 0.11%   |
| 6     | 5         | 0.08%   |
| 10    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5357      | 82.77%  |
| Yes  | 1115      | 17.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2484      | 54.41%  |
| Realtek Semiconductor           | 406       | 8.89%   |
| Cambridge Silicon Radio         | 311       | 6.81%   |
| Qualcomm Atheros Communications | 271       | 5.94%   |
| IMC Networks                    | 171       | 3.75%   |
| Broadcom                        | 171       | 3.75%   |
| Lite-On Technology              | 143       | 3.13%   |
| Foxconn / Hon Hai               | 132       | 2.89%   |
| ASUSTek Computer                | 106       | 2.32%   |
| Apple                           | 94        | 2.06%   |
| Realtek                         | 45        | 0.99%   |
| MediaTek                        | 38        | 0.83%   |
| Dell                            | 33        | 0.72%   |
| Hewlett-Packard                 | 20        | 0.44%   |
| TP-Link                         | 18        | 0.39%   |
| Marvell Semiconductor           | 17        | 0.37%   |
| HTC (High Tech Computer)        | 14        | 0.31%   |
| Toshiba                         | 13        | 0.28%   |
| USI                             | 11        | 0.24%   |
| Ralink                          | 11        | 0.24%   |
| Edimax Technology               | 8         | 0.18%   |
| Foxconn International           | 7         | 0.15%   |
| Dynex                           | 5         | 0.11%   |
| Opticis                         | 4         | 0.09%   |
| Integrated System Solution      | 4         | 0.09%   |
| Smart Modular Technologies      | 3         | 0.07%   |
| Micro Star International        | 3         | 0.07%   |
| Chicony Electronics             | 3         | 0.07%   |
| Askey Computer                  | 3         | 0.07%   |
| Ralink Technology               | 2         | 0.04%   |
| ISSC                            | 2         | 0.04%   |
| Belkin Components               | 2         | 0.04%   |
| Alps Electric                   | 2         | 0.04%   |
| Syntek                          | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Roper                           | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Cypress Semiconductor           | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Actions                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 784       | 17.14%  |
| Intel AX200 Bluetooth                                                | 525       | 11.48%  |
| Intel AX201 Bluetooth                                                | 388       | 8.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 327       | 7.15%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 311       | 6.8%    |
| Realtek Bluetooth Radio                                              | 266       | 5.82%   |
| Qualcomm Atheros  Bluetooth Device                                   | 142       | 3.11%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 123       | 2.69%   |
| Intel AX210 Bluetooth                                                | 113       | 2.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 95        | 2.08%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 89        | 1.95%   |
| Intel Bluetooth Device                                               | 80        | 1.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 59        | 1.29%   |
| IMC Networks Bluetooth Radio                                         | 58        | 1.27%   |
| IMC Networks Wireless_Device                                         | 57        | 1.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 48        | 1.05%   |
| Lite-On Bluetooth Device                                             | 48        | 1.05%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 46        | 1.01%   |
| Realtek Bluetooth Radio                                              | 45        | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 45        | 0.98%   |
| Apple Bluetooth USB Host Controller                                  | 43        | 0.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 42        | 0.92%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 38        | 0.83%   |
| MediaTek Wireless_Device                                             | 37        | 0.81%   |
| IMC Networks Bluetooth Device                                        | 37        | 0.81%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 36        | 0.79%   |
| Apple Bluetooth Host Controller                                      | 34        | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 29        | 0.63%   |
| Foxconn / Hon Hai Wireless_Device                                    | 27        | 0.59%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                         | 27        | 0.59%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 23        | 0.5%    |
| Qualcomm Atheros AR3011 Bluetooth                                    | 21        | 0.46%   |
| Lite-On Wireless_Device                                              | 21        | 0.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 20        | 0.44%   |
| TP-Link UB500 Adapter                                                | 18        | 0.39%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 17        | 0.37%   |
| Realtek RTL8821A Bluetooth                                           | 15        | 0.33%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 14        | 0.31%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 14        | 0.31%   |
| ASUS Bluetooth Radio                                                 | 14        | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 4104      | 40.78%  |
| AMD                         | 2440      | 24.25%  |
| Nvidia                      | 1865      | 18.53%  |
| C-Media Electronics         | 229       | 2.28%   |
| Logitech                    | 113       | 1.12%   |
| Kingston Technology         | 80        | 0.79%   |
| Texas Instruments           | 68        | 0.68%   |
| Focusrite-Novation          | 63        | 0.63%   |
| JMTek                       | 61        | 0.61%   |
| SteelSeries ApS             | 58        | 0.58%   |
| Razer USA                   | 57        | 0.57%   |
| Realtek Semiconductor       | 55        | 0.55%   |
| Lenovo                      | 44        | 0.44%   |
| Creative Labs               | 44        | 0.44%   |
| Creative Technology         | 42        | 0.42%   |
| Corsair                     | 40        | 0.4%    |
| Blue Microphones            | 37        | 0.37%   |
| ASUSTek Computer            | 28        | 0.28%   |
| GN Netcom                   | 27        | 0.27%   |
| Samson Technologies         | 26        | 0.26%   |
| Valve Software              | 21        | 0.21%   |
| Apple                       | 21        | 0.21%   |
| Generalplus Technology      | 20        | 0.2%    |
| Yamaha                      | 19        | 0.19%   |
| GYROCOM C&C                 | 19        | 0.19%   |
| BEHRINGER International     | 19        | 0.19%   |
| Sony                        | 18        | 0.18%   |
| Plantronics                 | 15        | 0.15%   |
| Audio-Technica              | 15        | 0.15%   |
| SAVITECH                    | 14        | 0.14%   |
| FiiO Electronics Technology | 14        | 0.14%   |
| XMOS                        | 13        | 0.13%   |
| RODE Microphones            | 13        | 0.13%   |
| M-Audio                     | 13        | 0.13%   |
| Sennheiser Communications   | 12        | 0.12%   |
| Hewlett-Packard             | 11        | 0.11%   |
| Cambridge Silicon Radio     | 11        | 0.11%   |
| Micro Star International    | 10        | 0.1%    |
| Dell                        | 10        | 0.1%    |
| Giga-Byte Technology        | 9         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 873       | 7.21%   |
| Intel Sunrise Point-LP HD Audio                                            | 589       | 4.86%   |
| AMD Starship/Matisse HD Audio Controller                                   | 567       | 4.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 441       | 3.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 341       | 2.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 323       | 2.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 314       | 2.59%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 290       | 2.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 259       | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 245       | 2.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 241       | 1.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 233       | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 228       | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 205       | 1.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 187       | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 176       | 1.45%   |
| Nvidia GP104 High Definition Audio Controller                              | 172       | 1.42%   |
| AMD Navi 10 HDMI Audio                                                     | 170       | 1.4%    |
| Intel 200 Series PCH HD Audio                                              | 167       | 1.38%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 156       | 1.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 140       | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                              | 137       | 1.13%   |
| Nvidia GP106 High Definition Audio Controller                              | 136       | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 134       | 1.11%   |
| Intel Broadwell-U Audio Controller                                         | 134       | 1.11%   |
| Intel 8 Series HD Audio Controller                                         | 134       | 1.11%   |
| Intel Comet Lake PCH cAVS                                                  | 130       | 1.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 129       | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 128       | 1.06%   |
| Intel CM238 HD Audio Controller                                            | 122       | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                              | 121       | 1%      |
| Intel Comet Lake PCH-LP cAVS                                               | 110       | 0.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 108       | 0.89%   |
| Nvidia GA104 High Definition Audio Controller                              | 103       | 0.85%   |
| Nvidia TU104 HD Audio Controller                                           | 101       | 0.83%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 99        | 0.82%   |
| AMD FCH Azalia Controller                                                  | 93        | 0.77%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 87        | 0.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 79        | 0.65%   |
| Nvidia GA106 High Definition Audio Controller                              | 79        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1138      | 21%     |
| SK hynix                     | 859       | 15.85%  |
| Kingston                     | 672       | 12.4%   |
| Corsair                      | 526       | 9.7%    |
| Micron Technology            | 525       | 9.69%   |
| Crucial                      | 430       | 7.93%   |
| G.Skill                      | 340       | 6.27%   |
| Unknown                      | 284       | 5.24%   |
| A-DATA Technology            | 109       | 2.01%   |
| Ramaxel Technology           | 82        | 1.51%   |
| Team                         | 49        | 0.9%    |
| Elpida                       | 49        | 0.9%    |
| Patriot                      | 45        | 0.83%   |
| GOODRAM                      | 33        | 0.61%   |
| Nanya Technology             | 27        | 0.5%    |
| Unknown (ABCD)               | 22        | 0.41%   |
| Unknown                      | 22        | 0.41%   |
| Smart                        | 19        | 0.35%   |
| Transcend                    | 17        | 0.31%   |
| PNY                          | 13        | 0.24%   |
| AMD                          | 13        | 0.24%   |
| Goldkey                      | 9         | 0.17%   |
| Apacer                       | 8         | 0.15%   |
| Teikon                       | 6         | 0.11%   |
| Smart Brazil                 | 6         | 0.11%   |
| Golden Empire                | 5         | 0.09%   |
| GeIL                         | 5         | 0.09%   |
| Wilk Elektronik              | 4         | 0.07%   |
| Silicon Power                | 4         | 0.07%   |
| Neo Forza                    | 4         | 0.07%   |
| Avant                        | 4         | 0.07%   |
| V-GeN                        | 3         | 0.06%   |
| V-Color                      | 3         | 0.06%   |
| Patriot Memory (PDP Systems) | 3         | 0.06%   |
| KLEVV                        | 3         | 0.06%   |
| Kingmax                      | 3         | 0.06%   |
| GSkill                       | 3         | 0.06%   |
| ASint Technology             | 3         | 0.06%   |
| A Force                      | 3         | 0.06%   |
| 48spaces                     | 3         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 67        | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 63        | 1.09%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 62        | 1.07%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 54        | 0.93%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 54        | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 44        | 0.76%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 39        | 0.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 36        | 0.62%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 34        | 0.59%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 31        | 0.54%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 29        | 0.5%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 28        | 0.48%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 28        | 0.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 27        | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 27        | 0.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 25        | 0.43%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 25        | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 25        | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 25        | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 0.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 25        | 0.43%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 25        | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 24        | 0.42%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 23        | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 22        | 0.38%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 22        | 0.38%   |
| Unknown                                                          | 22        | 0.38%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.36%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 21        | 0.36%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.35%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 20        | 0.35%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 20        | 0.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 19        | 0.33%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 18        | 0.31%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.31%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 18        | 0.31%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 18        | 0.31%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 18        | 0.31%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 18        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2897      | 62.22%  |
| DDR3    | 1099      | 23.6%   |
| LPDDR4  | 181       | 3.89%   |
| LPDDR3  | 141       | 3.03%   |
| DDR5    | 79        | 1.7%    |
| Unknown | 65        | 1.4%    |
| SDRAM   | 60        | 1.29%   |
| LPDDR5  | 59        | 1.27%   |
| DDR2    | 59        | 1.27%   |
| DDR     | 15        | 0.32%   |
| DRAM    | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2433      | 52.28%  |
| DIMM         | 1774      | 38.12%  |
| Row Of Chips | 394       | 8.47%   |
| Chip         | 36        | 0.77%   |
| Unknown      | 14        | 0.3%    |
| RIMM         | 2         | 0.04%   |
| FB-DIMM      | 1         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2316      | 45.93%  |
| 4096  | 1127      | 22.35%  |
| 16384 | 962       | 19.08%  |
| 2048  | 342       | 6.78%   |
| 32768 | 231       | 4.58%   |
| 1024  | 57        | 1.13%   |
| 512   | 6         | 0.12%   |
| 65536 | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 882       | 17.31%  |
| 2667    | 831       | 16.31%  |
| 1600    | 723       | 14.19%  |
| 2400    | 434       | 8.52%   |
| 3600    | 268       | 5.26%   |
| 2133    | 268       | 5.26%   |
| 1333    | 205       | 4.02%   |
| 1867    | 123       | 2.41%   |
| 4267    | 97        | 1.9%    |
| 1334    | 96        | 1.88%   |
| 3266    | 82        | 1.61%   |
| 3400    | 74        | 1.45%   |
| 6400    | 63        | 1.24%   |
| 4800    | 62        | 1.22%   |
| 3533    | 60        | 1.18%   |
| 3733    | 59        | 1.16%   |
| 3000    | 56        | 1.1%    |
| 2933    | 49        | 0.96%   |
| 667     | 48        | 0.94%   |
| 3800    | 46        | 0.9%    |
| 1067    | 37        | 0.73%   |
| 1866    | 35        | 0.69%   |
| Unknown | 34        | 0.67%   |
| 3866    | 30        | 0.59%   |
| 2800    | 30        | 0.59%   |
| 3666    | 28        | 0.55%   |
| 2666    | 28        | 0.55%   |
| 1066    | 28        | 0.55%   |
| 3466    | 27        | 0.53%   |
| 800     | 27        | 0.53%   |
| 4266    | 26        | 0.51%   |
| 4199    | 19        | 0.37%   |
| 8400    | 18        | 0.35%   |
| 1800    | 16        | 0.31%   |
| 3333    | 13        | 0.26%   |
| 400     | 12        | 0.24%   |
| 4000    | 11        | 0.22%   |
| 2048    | 10        | 0.2%    |
| 2733    | 9         | 0.18%   |
| 3151    | 8         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 34        | 36.56%  |
| Brother Industries       | 16        | 17.2%   |
| Samsung Electronics      | 13        | 13.98%  |
| Canon                    | 12        | 12.9%   |
| Seiko Epson              | 4         | 4.3%    |
| Prolific Technology      | 3         | 3.23%   |
| Dymo-CoStar              | 3         | 3.23%   |
| Zebra                    | 1         | 1.08%   |
| STMicroelectronics       | 1         | 1.08%   |
| Ricoh                    | 1         | 1.08%   |
| QinHeng Electronics      | 1         | 1.08%   |
| Philips (or NXP)         | 1         | 1.08%   |
| Magic Control Technology | 1         | 1.08%   |
| Fuji Xerox               | 1         | 1.08%   |
| Dell                     | 1         | 1.08%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung M2070 Series                                      | 3         | 3.23%   |
| Prolific PL2305 Parallel Port                             | 3         | 3.23%   |
| HP DeskJet 2130 series                                    | 3         | 3.23%   |
| Samsung SCX-4100 Scanner                                  | 2         | 2.15%   |
| HP Officejet Pro 8100                                     | 2         | 2.15%   |
| HP LaserJet P2015 series                                  | 2         | 2.15%   |
| HP LaserJet 1022                                          | 2         | 2.15%   |
| HP LaserJet 1012                                          | 2         | 2.15%   |
| HP DeskJet 840c                                           | 2         | 2.15%   |
| HP Deskjet 3050 J610 series                               | 2         | 2.15%   |
| HP DeskJet 2620 All-in-One Printer                        | 2         | 2.15%   |
| Dymo-CoStar LabelWriter 450                               | 2         | 2.15%   |
| Brother Printer                                           | 2         | 2.15%   |
| Brother HL-L2320D series                                  | 2         | 2.15%   |
| Brother HL-5370DW series                                  | 2         | 2.15%   |
| Zebra LP2844 Printer                                      | 1         | 1.08%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.08%   |
| Seiko Epson XP-7100 Series                                | 1         | 1.08%   |
| Seiko Epson WF-2530 Series                                | 1         | 1.08%   |
| Seiko Epson Printer                                       | 1         | 1.08%   |
| Seiko Epson L3110 Series                                  | 1         | 1.08%   |
| Samsung SCX-4200 series                                   | 1         | 1.08%   |
| Samsung SCX-3200 Series                                   | 1         | 1.08%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.08%   |
| Samsung ML-1610 Mono Laser Printer                        | 1         | 1.08%   |
| Samsung M267x 287x Series                                 | 1         | 1.08%   |
| Samsung M2020 Series                                      | 1         | 1.08%   |
| Samsung CLP-325 Color Laser Printer                       | 1         | 1.08%   |
| Samsung C1860 Series                                      | 1         | 1.08%   |
| Ricoh SP 150SU                                            | 1         | 1.08%   |
| QinHeng CH340S                                            | 1         | 1.08%   |
| Philips (or NXP) Gprinter USB Printer                     | 1         | 1.08%   |
| Magic Control BAY-3U1S1P Parallel Port                    | 1         | 1.08%   |
| HP PSC-1315/PSC-1317                                      | 1         | 1.08%   |
| HP OfficeJet 5600 (USBHUB)                                | 1         | 1.08%   |
| HP Officejet 4500 G510g-m                                 | 1         | 1.08%   |
| HP LaserJet P1005                                         | 1         | 1.08%   |
| HP LaserJet M14-M17                                       | 1         | 1.08%   |
| HP LaserJet 2420                                          | 1         | 1.08%   |
| HP LaserJet 1320                                          | 1         | 1.08%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 10        | 55.56%  |
| Seiko Epson    | 6         | 33.33%  |
| Mustek Systems | 2         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]                 | 2         | 11.11%  |
| Canon CanoScan N650U/N656U                                  | 2         | 11.11%  |
| Canon CanoScan LiDE 200                                     | 2         | 11.11%  |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 5.56%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]     | 1         | 5.56%   |
| Seiko Epson GT-F700 [Perfection V350]                       | 1         | 5.56%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 5.56%   |
| Mustek Systems ScanExpress 1200 UB                          | 1         | 5.56%   |
| Mustek Systems BearPaw 1200 CU Plus                         | 1         | 5.56%   |
| Canon CanoScan LiDE 60                                      | 1         | 5.56%   |
| Canon CanoScan LIDE 25                                      | 1         | 5.56%   |
| Canon CanoScan LiDE 220                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 210                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 120                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 110                                     | 1         | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 811       | 19.79%  |
| IMC Networks                           | 434       | 10.59%  |
| Logitech                               | 362       | 8.83%   |
| Microdia                               | 347       | 8.47%   |
| Realtek Semiconductor                  | 265       | 6.46%   |
| Bison Electronics                      | 229       | 5.59%   |
| Quanta                                 | 225       | 5.49%   |
| Sunplus Innovation Technology          | 177       | 4.32%   |
| Acer                                   | 144       | 3.51%   |
| Cheng Uei Precision Industry (Foxlink) | 134       | 3.27%   |
| Syntek                                 | 110       | 2.68%   |
| Lite-On Technology                     | 98        | 2.39%   |
| Apple                                  | 88        | 2.15%   |
| Luxvisions Innotech Limited            | 70        | 1.71%   |
| Suyin                                  | 64        | 1.56%   |
| Microsoft                              | 53        | 1.29%   |
| Samsung Electronics                    | 45        | 1.1%    |
| Silicon Motion                         | 42        | 1.02%   |
| Alcor Micro                            | 41        | 1%      |
| Lenovo                                 | 28        | 0.68%   |
| Z-Star Microelectronics                | 23        | 0.56%   |
| Sonix Technology                       | 21        | 0.51%   |
| Valve Software                         | 18        | 0.44%   |
| MacroSilicon                           | 18        | 0.44%   |
| SunplusIT                              | 14        | 0.34%   |
| Importek                               | 13        | 0.32%   |
| ARC International                      | 13        | 0.32%   |
| Razer USA                              | 12        | 0.29%   |
| Ricoh                                  | 11        | 0.27%   |
| KYE Systems (Mouse Systems)            | 11        | 0.27%   |
| ALi                                    | 11        | 0.27%   |
| Shenzhen Kingcome Optoelectronic       | 9         | 0.22%   |
| Primax Electronics                     | 9         | 0.22%   |
| Generalplus Technology                 | 9         | 0.22%   |
| Creative Technology                    | 9         | 0.22%   |
| Jieli Technology                       | 8         | 0.2%    |
| LG Electronics                         | 7         | 0.17%   |
| Google                                 | 6         | 0.15%   |
| Trust                                  | 5         | 0.12%   |
| Huawei Technologies                    | 5         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 229       | 5.53%   |
| Microdia Integrated_Webcam_HD                                              | 173       | 4.18%   |
| IMC Networks Integrated Camera                                             | 150       | 3.62%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 129       | 3.11%   |
| Realtek Integrated_Webcam_HD                                               | 98        | 2.37%   |
| Chicony HD WebCam                                                          | 88        | 2.12%   |
| Bison Integrated Camera                                                    | 82        | 1.98%   |
| Logitech HD Pro Webcam C920                                                | 76        | 1.83%   |
| Syntek Integrated Camera                                                   | 73        | 1.76%   |
| Sunplus Integrated_Webcam_HD                                               | 70        | 1.69%   |
| Logitech Webcam C270                                                       | 57        | 1.38%   |
| Quanta HD User Facing                                                      | 49        | 1.18%   |
| Lite-On Integrated Camera                                                  | 47        | 1.13%   |
| Acer HD Webcam                                                             | 46        | 1.11%   |
| Samsung Galaxy A5 (MTP)                                                    | 45        | 1.09%   |
| Bison SunplusIT Integrated Camera                                          | 43        | 1.04%   |
| Acer Integrated Camera                                                     | 41        | 0.99%   |
| Chicony USB2.0 Camera                                                      | 35        | 0.85%   |
| Chicony Integrated Camera (1280x720@30)                                    | 35        | 0.85%   |
| Apple FaceTime HD Camera (Built-in)                                        | 35        | 0.85%   |
| Chicony HP HD Camera                                                       | 34        | 0.82%   |
| Chicony HD User Facing                                                     | 33        | 0.8%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 32        | 0.77%   |
| Chicony HP Wide Vision HD Camera                                           | 32        | 0.77%   |
| Logitech C922 Pro Stream Webcam                                            | 31        | 0.75%   |
| Microdia Integrated Webcam                                                 | 29        | 0.7%    |
| Quanta HP Wide Vision HD Camera                                            | 27        | 0.65%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 27        | 0.65%   |
| IMC Networks ov9734_azurewave_camera                                       | 25        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 25        | 0.6%    |
| Realtek USB Camera                                                         | 24        | 0.58%   |
| Realtek Integrated Webcam                                                  | 23        | 0.56%   |
| Logitech BRIO Ultra HD Webcam                                              | 23        | 0.56%   |
| Chicony EasyCamera                                                         | 23        | 0.56%   |
| Quanta VGA WebCam                                                          | 22        | 0.53%   |
| Quanta HP TrueVision HD Camera                                             | 22        | 0.53%   |
| Chicony Integrated IR Camera                                               | 22        | 0.53%   |
| Microdia Webcam Vitade AF                                                  | 21        | 0.51%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 21        | 0.51%   |
| Chicony USB2.0 HD UVC WebCam                                               | 21        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 336       | 38.14%  |
| Validity Sensors                   | 224       | 25.43%  |
| Shenzhen Goodix Technology         | 161       | 18.27%  |
| Elan Microelectronics              | 57        | 6.47%   |
| LighTuning Technology              | 29        | 3.29%   |
| Upek                               | 27        | 3.06%   |
| AuthenTec                          | 21        | 2.38%   |
| STMicroelectronics                 | 10        | 1.14%   |
| Samsung Electronics                | 6         | 0.68%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.34%   |
| Microsoft                          | 3         | 0.34%   |
| HOLTEK                             | 2         | 0.23%   |
| Focal-systems.Corp                 | 1         | 0.11%   |
| DigitalPersona                     | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 120       | 13.62%  |
| Shenzhen Goodix  Fingerprint Device                                        | 84        | 9.53%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 52        | 5.9%    |
| Shenzhen Goodix Fingerprint Reader                                         | 46        | 5.22%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 39        | 4.43%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 36        | 4.09%   |
| Elan ELAN:Fingerprint                                                      | 33        | 3.75%   |
| Synaptics UWP WBDI                                                         | 32        | 3.63%   |
| Shenzhen Goodix FingerPrint                                                | 31        | 3.52%   |
| Validity Sensors Synaptics WBDI                                            | 27        | 3.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 25        | 2.84%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 23        | 2.61%   |
| Synaptics  WBDI                                                            | 22        | 2.5%    |
| Elan ELAN:ARM-M4                                                           | 22        | 2.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 20        | 2.27%   |
| Synaptics WBDI                                                             | 20        | 2.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 20        | 2.27%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 2.04%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 16        | 1.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.59%   |
| Validity Sensors VFS491                                                    | 13        | 1.48%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 13        | 1.48%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 1.36%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 12        | 1.36%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 11        | 1.25%   |
| AuthenTec AES2810                                                          | 11        | 1.25%   |
| Synaptics UWP WBDI Device                                                  | 10        | 1.14%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 1.14%   |
| STMicroelectronics Fingerprint Reader                                      | 10        | 1.14%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 1.02%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 0.68%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 0.57%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 5         | 0.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.45%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.45%   |
| Synaptics WBDI Device                                                      | 4         | 0.45%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.45%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.34%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.34%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 135       | 39.94%  |
| Broadcom                          | 113       | 33.43%  |
| Upek                              | 23        | 6.8%    |
| Lenovo                            | 11        | 3.25%   |
| O2 Micro                          | 8         | 2.37%   |
| Clay Logic                        | 8         | 2.37%   |
| Yubico.com                        | 6         | 1.78%   |
| Gemalto (was Gemplus)             | 6         | 1.78%   |
| Advanced Card Systems             | 6         | 1.78%   |
| SCM Microsystems                  | 5         | 1.48%   |
| Reiner SCT Kartensysteme          | 4         | 1.18%   |
| Aladdin Knowledge Systems         | 3         | 0.89%   |
| OmniKey                           | 2         | 0.59%   |
| VASCO Data Security International | 1         | 0.3%    |
| Realtek Semiconductor             | 1         | 0.3%    |
| Hewlett-Packard                   | 1         | 0.3%    |
| Fujitsu Siemens Computers         | 1         | 0.3%    |
| Chicony Electronics               | 1         | 0.3%    |
| C3PO                              | 1         | 0.3%    |
| Aladdin R.D.                      | 1         | 0.3%    |
| Aktiv                             | 1         | 0.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 133       | 39.35%  |
| Broadcom 5880                                                                | 32        | 9.47%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 30        | 8.88%   |
| Broadcom BCM5880 Secure Applications Processor                               | 25        | 7.4%    |
| Broadcom 58200                                                               | 24        | 7.1%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 23        | 6.8%    |
| Lenovo Integrated Smart Card Reader                                          | 11        | 3.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 2.07%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 6         | 1.78%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 0.89%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.89%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.89%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.89%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 0.89%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 2         | 0.59%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.59%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.59%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.59%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.59%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.3%    |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.3%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.3%    |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.3%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.3%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.3%    |
| OmniKey Smart Card Reader USB                                                | 1         | 0.3%    |
| OmniKey 5022 Smart Card Reader                                               | 1         | 0.3%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.3%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.3%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.3%    |
| Fujitsu Siemens Computers Keyboard KB100 SCR eSIG                            | 1         | 0.3%    |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.3%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.3%    |
| C3PO LTC31v2                                                                 | 1         | 0.3%    |
| Aladdin R.D. JaCarta                                                         | 1         | 0.3%    |
| Aktiv Rutoken lite                                                           | 1         | 0.3%    |
| Advanced Card Systems ACR39U                                                 | 1         | 0.3%    |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.3%    |
| Advanced Card Systems ACR122U                                                | 1         | 0.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4547      | 69.89%  |
| 1     | 1567      | 24.09%  |
| 2     | 310       | 4.76%   |
| 3     | 68        | 1.05%   |
| 4     | 10        | 0.15%   |
| 6     | 2         | 0.03%   |
| 7     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 858       | 36.42%  |
| Graphics card            | 428       | 18.17%  |
| Chipcard                 | 286       | 12.14%  |
| Net/wireless             | 208       | 8.83%   |
| Multimedia controller    | 163       | 6.92%   |
| Camera                   | 123       | 5.22%   |
| Unassigned class         | 55        | 2.33%   |
| Bluetooth                | 47        | 1.99%   |
| Communication controller | 44        | 1.87%   |
| Sound                    | 38        | 1.61%   |
| Net/ethernet             | 23        | 0.98%   |
| Network                  | 22        | 0.93%   |
| Storage                  | 18        | 0.76%   |
| Card reader              | 13        | 0.55%   |
| Modem                    | 10        | 0.42%   |
| Dvb card                 | 8         | 0.34%   |
| Wireless                 | 2         | 0.08%   |
| Storage/raid             | 2         | 0.08%   |
| Storage/nvme             | 2         | 0.08%   |
| Storage/ide              | 2         | 0.08%   |
| Tv card                  | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |
| Flash memory             | 1         | 0.04%   |
| Firewire controller      | 1         | 0.04%   |

