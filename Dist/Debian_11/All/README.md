Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

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

Total: 8331

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Vector GP66 12UGS           | Notebook    | [4787e68a9c](https://linux-hardware.org/?probe=4787e68a9c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [12e105f6da](https://linux-hardware.org/?probe=12e105f6da) | Apr 01, 2023 |
| Unknown       | Unknown                     | Soc         | [15a1a38207](https://linux-hardware.org/?probe=15a1a38207) | Apr 01, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [f75af97954](https://linux-hardware.org/?probe=f75af97954) | Apr 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2175527bda](https://linux-hardware.org/?probe=2175527bda) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a5c21e7892](https://linux-hardware.org/?probe=a5c21e7892) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4b873550ab](https://linux-hardware.org/?probe=4b873550ab) | Apr 01, 2023 |
| HP            | Pavilion dv7                | Notebook    | [00bbec023a](https://linux-hardware.org/?probe=00bbec023a) | Apr 01, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [3c163a3b34](https://linux-hardware.org/?probe=3c163a3b34) | Mar 31, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [8d2858a444](https://linux-hardware.org/?probe=8d2858a444) | Mar 31, 2023 |
| ASUSTek       | X202E                       | Notebook    | [cdcccb09e7](https://linux-hardware.org/?probe=cdcccb09e7) | Mar 31, 2023 |
| ASUSTek       | X202E                       | Notebook    | [ac12ec53a3](https://linux-hardware.org/?probe=ac12ec53a3) | Mar 31, 2023 |
| ASUSTek       | TS10                        | Desktop     | [054de4f36a](https://linux-hardware.org/?probe=054de4f36a) | Mar 31, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [47f6f4653b](https://linux-hardware.org/?probe=47f6f4653b) | Mar 31, 2023 |
| Lenovo        | Yoga 3 11 80J8              | Notebook    | [fce7483fa0](https://linux-hardware.org/?probe=fce7483fa0) | Mar 31, 2023 |
| Intel         | S1200BTL E98681-352         | Server      | [6d9ff27de2](https://linux-hardware.org/?probe=6d9ff27de2) | Mar 31, 2023 |
| Intel         | S1200BTL E98681-352         | Server      | [50c3fba233](https://linux-hardware.org/?probe=50c3fba233) | Mar 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [624d23335b](https://linux-hardware.org/?probe=624d23335b) | Mar 31, 2023 |
| Dell          | Latitude E6330              | Notebook    | [ae7a7254b8](https://linux-hardware.org/?probe=ae7a7254b8) | Mar 31, 2023 |
| Dell          | Latitude E6330              | Notebook    | [2239e12384](https://linux-hardware.org/?probe=2239e12384) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [3399c2f210](https://linux-hardware.org/?probe=3399c2f210) | Mar 31, 2023 |
| Dell          | Precision M4700             | Notebook    | [7c93bc178e](https://linux-hardware.org/?probe=7c93bc178e) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [d6b6c88578](https://linux-hardware.org/?probe=d6b6c88578) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [704145641e](https://linux-hardware.org/?probe=704145641e) | Mar 31, 2023 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [56c886069b](https://linux-hardware.org/?probe=56c886069b) | Mar 31, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | Desktop     | [050875ba5f](https://linux-hardware.org/?probe=050875ba5f) | Mar 30, 2023 |
| AZW           | U59                         | Desktop     | [c87edfe3b6](https://linux-hardware.org/?probe=c87edfe3b6) | Mar 30, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [2ca1607b80](https://linux-hardware.org/?probe=2ca1607b80) | Mar 30, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [3494b0fdd9](https://linux-hardware.org/?probe=3494b0fdd9) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | Desktop     | [fbcdd4ed13](https://linux-hardware.org/?probe=fbcdd4ed13) | Mar 30, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [990f324256](https://linux-hardware.org/?probe=990f324256) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [76e79f5f19](https://linux-hardware.org/?probe=76e79f5f19) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [78d1316a55](https://linux-hardware.org/?probe=78d1316a55) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [b6226ae481](https://linux-hardware.org/?probe=b6226ae481) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [bf3d484605](https://linux-hardware.org/?probe=bf3d484605) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [3e4d9fac89](https://linux-hardware.org/?probe=3e4d9fac89) | Mar 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [4d6ae3ef0f](https://linux-hardware.org/?probe=4d6ae3ef0f) | Mar 30, 2023 |
| HP            | 213D A01                    | Desktop     | [d5fb38a71b](https://linux-hardware.org/?probe=d5fb38a71b) | Mar 30, 2023 |
| HP            | 213D A01                    | Desktop     | [79d8e1b64f](https://linux-hardware.org/?probe=79d8e1b64f) | Mar 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [18f4d18529](https://linux-hardware.org/?probe=18f4d18529) | Mar 30, 2023 |
| HP            | 3048h                       | Desktop     | [1a4d86fca8](https://linux-hardware.org/?probe=1a4d86fca8) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e85544a3d7](https://linux-hardware.org/?probe=e85544a3d7) | Mar 30, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [4976f6b6b2](https://linux-hardware.org/?probe=4976f6b6b2) | Mar 30, 2023 |
| Dell          | Precision M4800             | Notebook    | [ebd0442adc](https://linux-hardware.org/?probe=ebd0442adc) | Mar 30, 2023 |
| Lenovo        | ThinkPad T60 195143U        | Notebook    | [4de196550b](https://linux-hardware.org/?probe=4de196550b) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9251f2d561](https://linux-hardware.org/?probe=9251f2d561) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2d28ba397e](https://linux-hardware.org/?probe=2d28ba397e) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [a771622660](https://linux-hardware.org/?probe=a771622660) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [1e0c5a90c9](https://linux-hardware.org/?probe=1e0c5a90c9) | Mar 29, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [e772d0e916](https://linux-hardware.org/?probe=e772d0e916) | Mar 29, 2023 |
| AZW           | U59                         | Desktop     | [3776cd7fb3](https://linux-hardware.org/?probe=3776cd7fb3) | Mar 29, 2023 |
| AZW           | U59                         | Desktop     | [f7958b8f39](https://linux-hardware.org/?probe=f7958b8f39) | Mar 29, 2023 |
| Medion        | TJ4125                      | Desktop     | [e03693b0f0](https://linux-hardware.org/?probe=e03693b0f0) | Mar 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [38e3ecfb84](https://linux-hardware.org/?probe=38e3ecfb84) | Mar 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [7d3374d52b](https://linux-hardware.org/?probe=7d3374d52b) | Mar 29, 2023 |
| Intel         | 945GCT-M                    | Desktop     | [d7e65e945e](https://linux-hardware.org/?probe=d7e65e945e) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| ECS           | G31T-M                      | Desktop     | [d6149cbd0d](https://linux-hardware.org/?probe=d6149cbd0d) | Mar 29, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [5c6734f5e6](https://linux-hardware.org/?probe=5c6734f5e6) | Mar 29, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [bf9252a1ac](https://linux-hardware.org/?probe=bf9252a1ac) | Mar 29, 2023 |
| Medion        | P7641 MD99856               | Notebook    | [7347a28d53](https://linux-hardware.org/?probe=7347a28d53) | Mar 28, 2023 |
| HP            | 89B4 A                      | Desktop     | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| HP            | Pavilion dv5000 (EW771EA... | Notebook    | [db28f35ce0](https://linux-hardware.org/?probe=db28f35ce0) | Mar 28, 2023 |
| Pegatron      | Maureen                     | Desktop     | [0fdcf4a5bc](https://linux-hardware.org/?probe=0fdcf4a5bc) | Mar 28, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [caf2461355](https://linux-hardware.org/?probe=caf2461355) | Mar 28, 2023 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [21cf1ad0bb](https://linux-hardware.org/?probe=21cf1ad0bb) | Mar 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [8f1561c37b](https://linux-hardware.org/?probe=8f1561c37b) | Mar 28, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [f281edd494](https://linux-hardware.org/?probe=f281edd494) | Mar 28, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [11cb22743c](https://linux-hardware.org/?probe=11cb22743c) | Mar 27, 2023 |
| ASRock        | 770 Extreme3                | Desktop     | [9cd5d1485c](https://linux-hardware.org/?probe=9cd5d1485c) | Mar 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [58d5e99cd1](https://linux-hardware.org/?probe=58d5e99cd1) | Mar 27, 2023 |
| HP            | 18E6                        | Desktop     | [a406dc2463](https://linux-hardware.org/?probe=a406dc2463) | Mar 27, 2023 |
| Medion        | TJ4125                      | Desktop     | [571b476915](https://linux-hardware.org/?probe=571b476915) | Mar 27, 2023 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [6180e562dd](https://linux-hardware.org/?probe=6180e562dd) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [33608bbcda](https://linux-hardware.org/?probe=33608bbcda) | Mar 27, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [dd84425bc7](https://linux-hardware.org/?probe=dd84425bc7) | Mar 27, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [46fbf61289](https://linux-hardware.org/?probe=46fbf61289) | Mar 27, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [645c8515a1](https://linux-hardware.org/?probe=645c8515a1) | Mar 27, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [cfb8c9d396](https://linux-hardware.org/?probe=cfb8c9d396) | Mar 27, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [5dcd20300a](https://linux-hardware.org/?probe=5dcd20300a) | Mar 27, 2023 |
| ASRockRack    | D1541D4U-2T8R               | Desktop     | [012c10ae8c](https://linux-hardware.org/?probe=012c10ae8c) | Mar 27, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [d1f406ffe7](https://linux-hardware.org/?probe=d1f406ffe7) | Mar 26, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [a4f4013e4e](https://linux-hardware.org/?probe=a4f4013e4e) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [af88fa64c6](https://linux-hardware.org/?probe=af88fa64c6) | Mar 26, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e67759f49b](https://linux-hardware.org/?probe=e67759f49b) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [d2f95decbe](https://linux-hardware.org/?probe=d2f95decbe) | Mar 26, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [d1c982b241](https://linux-hardware.org/?probe=d1c982b241) | Mar 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [f0d9554e41](https://linux-hardware.org/?probe=f0d9554e41) | Mar 26, 2023 |
| HP            | 83E2                        | Desktop     | [00f64e69cd](https://linux-hardware.org/?probe=00f64e69cd) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [1377a2ea15](https://linux-hardware.org/?probe=1377a2ea15) | Mar 26, 2023 |
| Medion        | TJ4125                      | Desktop     | [74b96baec4](https://linux-hardware.org/?probe=74b96baec4) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [fb8706575a](https://linux-hardware.org/?probe=fb8706575a) | Mar 25, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [76338f95ea](https://linux-hardware.org/?probe=76338f95ea) | Mar 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6e459078e7](https://linux-hardware.org/?probe=6e459078e7) | Mar 25, 2023 |
| HP            | 83E2                        | Desktop     | [cd40c6aa18](https://linux-hardware.org/?probe=cd40c6aa18) | Mar 25, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [eb1d734a53](https://linux-hardware.org/?probe=eb1d734a53) | Mar 25, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [de369a751a](https://linux-hardware.org/?probe=de369a751a) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0C40... | Notebook    | [39b2a59543](https://linux-hardware.org/?probe=39b2a59543) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| Dell          | 0PU052                      | Desktop     | [ccea2ad8e8](https://linux-hardware.org/?probe=ccea2ad8e8) | Mar 25, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [9b8ddda3c3](https://linux-hardware.org/?probe=9b8ddda3c3) | Mar 24, 2023 |
| ALLDOCUBE     | i1025P                      | Tablet      | [d4acdf3439](https://linux-hardware.org/?probe=d4acdf3439) | Mar 24, 2023 |
| Packard Be... | H17HV                       | Notebook    | [c4bddccbd8](https://linux-hardware.org/?probe=c4bddccbd8) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Dell          | Inspiron 7348               | Notebook    | [4011322039](https://linux-hardware.org/?probe=4011322039) | Mar 24, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [cde421908c](https://linux-hardware.org/?probe=cde421908c) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [1f7c1bfa41](https://linux-hardware.org/?probe=1f7c1bfa41) | Mar 24, 2023 |
| AZW           | U59                         | Desktop     | [b4058b773d](https://linux-hardware.org/?probe=b4058b773d) | Mar 24, 2023 |
| ASUSTek       | N56VJ                       | Notebook    | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| ALLDOCUBE     | i1025P                      | Tablet      | [080e9de73f](https://linux-hardware.org/?probe=080e9de73f) | Mar 23, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [6be57a7e6f](https://linux-hardware.org/?probe=6be57a7e6f) | Mar 23, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c65fd15277](https://linux-hardware.org/?probe=c65fd15277) | Mar 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c9a721f7d1](https://linux-hardware.org/?probe=c9a721f7d1) | Mar 23, 2023 |
| HP            | 8715                        | Mini pc     | [9ce704a4b9](https://linux-hardware.org/?probe=9ce704a4b9) | Mar 23, 2023 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [05eb6d08bd](https://linux-hardware.org/?probe=05eb6d08bd) | Mar 23, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [7aa41dd248](https://linux-hardware.org/?probe=7aa41dd248) | Mar 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [32a4fc1880](https://linux-hardware.org/?probe=32a4fc1880) | Mar 23, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [cb6e3973c8](https://linux-hardware.org/?probe=cb6e3973c8) | Mar 23, 2023 |
| HP            | 0A68h                       | Desktop     | [527cad6ad0](https://linux-hardware.org/?probe=527cad6ad0) | Mar 23, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [517da38f28](https://linux-hardware.org/?probe=517da38f28) | Mar 23, 2023 |
| Unknown       | BQ-H616                     | Soc         | [ba0b4036b6](https://linux-hardware.org/?probe=ba0b4036b6) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [5e97d4fdf3](https://linux-hardware.org/?probe=5e97d4fdf3) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [92208949d5](https://linux-hardware.org/?probe=92208949d5) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [aa71c25dba](https://linux-hardware.org/?probe=aa71c25dba) | Mar 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [ef5bf53c45](https://linux-hardware.org/?probe=ef5bf53c45) | Mar 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e2fe65e540](https://linux-hardware.org/?probe=e2fe65e540) | Mar 22, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [7b10e71784](https://linux-hardware.org/?probe=7b10e71784) | Mar 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [b96104604a](https://linux-hardware.org/?probe=b96104604a) | Mar 22, 2023 |
| HP            | 3048h                       | Desktop     | [5163f9de22](https://linux-hardware.org/?probe=5163f9de22) | Mar 22, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [849f9d23c7](https://linux-hardware.org/?probe=849f9d23c7) | Mar 21, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [57a69bcf57](https://linux-hardware.org/?probe=57a69bcf57) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230s 20AHS0070... | Notebook    | [9d86eaf558](https://linux-hardware.org/?probe=9d86eaf558) | Mar 21, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [4f2e83ab00](https://linux-hardware.org/?probe=4f2e83ab00) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [4c7add7cd1](https://linux-hardware.org/?probe=4c7add7cd1) | Mar 21, 2023 |
| Gigabyte      | EX38-DS4                    | Desktop     | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [5ca3a1b044](https://linux-hardware.org/?probe=5ca3a1b044) | Mar 21, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [8657b8d645](https://linux-hardware.org/?probe=8657b8d645) | Mar 21, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [3b06195ff0](https://linux-hardware.org/?probe=3b06195ff0) | Mar 21, 2023 |
| Google        | Teemo                       | Desktop     | [3e60b11752](https://linux-hardware.org/?probe=3e60b11752) | Mar 21, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [0acde77545](https://linux-hardware.org/?probe=0acde77545) | Mar 21, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [da9a9373a6](https://linux-hardware.org/?probe=da9a9373a6) | Mar 20, 2023 |
| Dell          | Latitude E6420              | Notebook    | [e564f25125](https://linux-hardware.org/?probe=e564f25125) | Mar 20, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [1d9fe6158b](https://linux-hardware.org/?probe=1d9fe6158b) | Mar 20, 2023 |
| Supermicro    | X10DRi-T4+                  | Desktop     | [3aa5aebaee](https://linux-hardware.org/?probe=3aa5aebaee) | Mar 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [7bc035af43](https://linux-hardware.org/?probe=7bc035af43) | Mar 20, 2023 |
| HP            | 1825                        | Desktop     | [73a2e18f3a](https://linux-hardware.org/?probe=73a2e18f3a) | Mar 20, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [0c4119f8b3](https://linux-hardware.org/?probe=0c4119f8b3) | Mar 20, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [67b681a703](https://linux-hardware.org/?probe=67b681a703) | Mar 20, 2023 |
| Dell          | Latitude 7480               | Notebook    | [00d8228ec6](https://linux-hardware.org/?probe=00d8228ec6) | Mar 20, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [40d6f69489](https://linux-hardware.org/?probe=40d6f69489) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1a21f25ce5](https://linux-hardware.org/?probe=1a21f25ce5) | Mar 20, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [ea415770cb](https://linux-hardware.org/?probe=ea415770cb) | Mar 20, 2023 |
| TUXEDO        | N13xWU                      | Notebook    | [e9614af654](https://linux-hardware.org/?probe=e9614af654) | Mar 19, 2023 |
| Dell          | Latitude 7480               | Notebook    | [bbdb75bdce](https://linux-hardware.org/?probe=bbdb75bdce) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [b5d9053f1c](https://linux-hardware.org/?probe=b5d9053f1c) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [660ae0f7ed](https://linux-hardware.org/?probe=660ae0f7ed) | Mar 19, 2023 |
| HP            | Pavilion g7                 | Notebook    | [e591ea2173](https://linux-hardware.org/?probe=e591ea2173) | Mar 19, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B8M... | Notebook    | [4cb81db618](https://linux-hardware.org/?probe=4cb81db618) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [d7b27c1822](https://linux-hardware.org/?probe=d7b27c1822) | Mar 19, 2023 |
| Acer          | Aspire V5-552PG             | Notebook    | [d895f0f391](https://linux-hardware.org/?probe=d895f0f391) | Mar 19, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [22bd6400f6](https://linux-hardware.org/?probe=22bd6400f6) | Mar 19, 2023 |
| Toshiba       | Satellite C655              | Notebook    | [229dcc2cb0](https://linux-hardware.org/?probe=229dcc2cb0) | Mar 19, 2023 |
| Toshiba       | Satellite C655              | Notebook    | [5037090da8](https://linux-hardware.org/?probe=5037090da8) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [5308592de8](https://linux-hardware.org/?probe=5308592de8) | Mar 19, 2023 |
| Intel         | 945GCT-M                    | Desktop     | [ac83eeefb9](https://linux-hardware.org/?probe=ac83eeefb9) | Mar 19, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [715b1e5c6b](https://linux-hardware.org/?probe=715b1e5c6b) | Mar 18, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [eea214ee38](https://linux-hardware.org/?probe=eea214ee38) | Mar 18, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [b939c61b5a](https://linux-hardware.org/?probe=b939c61b5a) | Mar 18, 2023 |
| Medion        | TJ4125                      | Desktop     | [6895b929a4](https://linux-hardware.org/?probe=6895b929a4) | Mar 18, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1e96b578fa](https://linux-hardware.org/?probe=1e96b578fa) | Mar 18, 2023 |
| Gigabyte      | Q270M-D3H                   | Desktop     | [b244f2a8fd](https://linux-hardware.org/?probe=b244f2a8fd) | Mar 18, 2023 |
| ASRock        | X570 PG Velocita            | Desktop     | [bc3f2240b9](https://linux-hardware.org/?probe=bc3f2240b9) | Mar 18, 2023 |
| Fujitsu       | D3601-A1 S26361-D3601-A1    | Desktop     | [ec47c2dcb7](https://linux-hardware.org/?probe=ec47c2dcb7) | Mar 18, 2023 |
| Lenovo        | ThinkServer TS440           | Desktop     | [f34d8572e9](https://linux-hardware.org/?probe=f34d8572e9) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [252cd1ff88](https://linux-hardware.org/?probe=252cd1ff88) | Mar 18, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [3cdb0bbdf6](https://linux-hardware.org/?probe=3cdb0bbdf6) | Mar 17, 2023 |
| HP            | 198E                        | Desktop     | [23e214216d](https://linux-hardware.org/?probe=23e214216d) | Mar 17, 2023 |
| HP            | 198E                        | Desktop     | [d5d5af66a8](https://linux-hardware.org/?probe=d5d5af66a8) | Mar 17, 2023 |
| Dell          | PowerEdge M620              | Desktop     | [c628cb7f90](https://linux-hardware.org/?probe=c628cb7f90) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [2020cf3584](https://linux-hardware.org/?probe=2020cf3584) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [e7ebc0ec0e](https://linux-hardware.org/?probe=e7ebc0ec0e) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [c343e79a84](https://linux-hardware.org/?probe=c343e79a84) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [5391c84cf4](https://linux-hardware.org/?probe=5391c84cf4) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [8fcb466fab](https://linux-hardware.org/?probe=8fcb466fab) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [7aa3efb2fd](https://linux-hardware.org/?probe=7aa3efb2fd) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [8319fcb9da](https://linux-hardware.org/?probe=8319fcb9da) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [6bf9694348](https://linux-hardware.org/?probe=6bf9694348) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [c3c0ef4a31](https://linux-hardware.org/?probe=c3c0ef4a31) | Mar 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [551bb0a214](https://linux-hardware.org/?probe=551bb0a214) | Mar 17, 2023 |
| HP            | 871A                        | Mini pc     | [b4b1c552ad](https://linux-hardware.org/?probe=b4b1c552ad) | Mar 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7a45a46793](https://linux-hardware.org/?probe=7a45a46793) | Mar 17, 2023 |
| HP            | 255 G3                      | Notebook    | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Intel         | NUC12SNKi72 M45201-500      | Mini pc     | [67985889b2](https://linux-hardware.org/?probe=67985889b2) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Dell          | Latitude 7480               | Notebook    | [ee6015f962](https://linux-hardware.org/?probe=ee6015f962) | Mar 17, 2023 |
| MSI           | GF72 8RE                    | Notebook    | [4610dffdcc](https://linux-hardware.org/?probe=4610dffdcc) | Mar 17, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | Desktop     | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| HP            | Notebook                    | Notebook    | [e901631805](https://linux-hardware.org/?probe=e901631805) | Mar 17, 2023 |
| Gigabyte      | MZ92-FS0-00 01010101        | Server      | [f1a315b89b](https://linux-hardware.org/?probe=f1a315b89b) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [97d434b3b5](https://linux-hardware.org/?probe=97d434b3b5) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [dd101b4b05](https://linux-hardware.org/?probe=dd101b4b05) | Mar 16, 2023 |
| Dell          | Precision M6800             | Notebook    | [db62a370ed](https://linux-hardware.org/?probe=db62a370ed) | Mar 16, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [e8d00684ac](https://linux-hardware.org/?probe=e8d00684ac) | Mar 16, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [71a45943c1](https://linux-hardware.org/?probe=71a45943c1) | Mar 16, 2023 |
| MicroByte     | ezpad                       | Tablet      | [745babb415](https://linux-hardware.org/?probe=745babb415) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [57f2de5da4](https://linux-hardware.org/?probe=57f2de5da4) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [2a316e6d03](https://linux-hardware.org/?probe=2a316e6d03) | Mar 16, 2023 |
| Dell          | Latitude 7480               | Notebook    | [72069037ca](https://linux-hardware.org/?probe=72069037ca) | Mar 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [0b9755873a](https://linux-hardware.org/?probe=0b9755873a) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [4e61f760cb](https://linux-hardware.org/?probe=4e61f760cb) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [b7671cbae5](https://linux-hardware.org/?probe=b7671cbae5) | Mar 16, 2023 |
| Gigabyte      | Q270M-D3H                   | Desktop     | [8841b23ef7](https://linux-hardware.org/?probe=8841b23ef7) | Mar 16, 2023 |
| ASRock        | X570 PG Velocita            | Desktop     | [bd8bc5740e](https://linux-hardware.org/?probe=bd8bc5740e) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [3f7d27d637](https://linux-hardware.org/?probe=3f7d27d637) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [bdb510861b](https://linux-hardware.org/?probe=bdb510861b) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [75a93c0ac6](https://linux-hardware.org/?probe=75a93c0ac6) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [e670ea3583](https://linux-hardware.org/?probe=e670ea3583) | Mar 16, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [108d237ebe](https://linux-hardware.org/?probe=108d237ebe) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [b78130eae1](https://linux-hardware.org/?probe=b78130eae1) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [8ea6223dc5](https://linux-hardware.org/?probe=8ea6223dc5) | Mar 16, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ee177d0e61](https://linux-hardware.org/?probe=ee177d0e61) | Mar 15, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [a22bba0e53](https://linux-hardware.org/?probe=a22bba0e53) | Mar 15, 2023 |
| Acer          | AO756                       | Notebook    | [21ba8b2996](https://linux-hardware.org/?probe=21ba8b2996) | Mar 15, 2023 |
| Cincoze       | P1101.01.001                | Desktop     | [9443379d5e](https://linux-hardware.org/?probe=9443379d5e) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | Desktop     | [2d3c739ac5](https://linux-hardware.org/?probe=2d3c739ac5) | Mar 15, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [c8c6ab5fce](https://linux-hardware.org/?probe=c8c6ab5fce) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | Desktop     | [f6f29a0f8a](https://linux-hardware.org/?probe=f6f29a0f8a) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [ea280402ca](https://linux-hardware.org/?probe=ea280402ca) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [513385d981](https://linux-hardware.org/?probe=513385d981) | Mar 15, 2023 |
| Acer          | Aspire 7720                 | Notebook    | [0f040d8292](https://linux-hardware.org/?probe=0f040d8292) | Mar 15, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [b952483e9a](https://linux-hardware.org/?probe=b952483e9a) | Mar 15, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f4926b859a](https://linux-hardware.org/?probe=f4926b859a) | Mar 15, 2023 |
| HP            | Mini 210-1000               | Notebook    | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| Unknown       | Unknown                     | Soc         | [946622b351](https://linux-hardware.org/?probe=946622b351) | Mar 15, 2023 |
| HP            | 1495                        | Desktop     | [72769abb34](https://linux-hardware.org/?probe=72769abb34) | Mar 15, 2023 |
| Gigabyte      | H97M-HD3                    | Desktop     | [6831505433](https://linux-hardware.org/?probe=6831505433) | Mar 14, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [37a6b115cb](https://linux-hardware.org/?probe=37a6b115cb) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [634ae1ae2b](https://linux-hardware.org/?probe=634ae1ae2b) | Mar 14, 2023 |
| ASUSTek       | ZenBook UX534FAC_UX533FA... | Notebook    | [83351958e6](https://linux-hardware.org/?probe=83351958e6) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [a897cf713a](https://linux-hardware.org/?probe=a897cf713a) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [63cbbd1f57](https://linux-hardware.org/?probe=63cbbd1f57) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [f5cbc232d7](https://linux-hardware.org/?probe=f5cbc232d7) | Mar 14, 2023 |
| Dell          | 064N3D A00                  | All in one  | [4721bf0213](https://linux-hardware.org/?probe=4721bf0213) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [aeb56fbebc](https://linux-hardware.org/?probe=aeb56fbebc) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [ee034131c0](https://linux-hardware.org/?probe=ee034131c0) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [438caf3588](https://linux-hardware.org/?probe=438caf3588) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [57d173995a](https://linux-hardware.org/?probe=57d173995a) | Mar 14, 2023 |
| Acer          | Aspire 7739G                | Notebook    | [aeff2df11c](https://linux-hardware.org/?probe=aeff2df11c) | Mar 14, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [812104dae3](https://linux-hardware.org/?probe=812104dae3) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [27c3c24dfc](https://linux-hardware.org/?probe=27c3c24dfc) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [714f8e1321](https://linux-hardware.org/?probe=714f8e1321) | Mar 14, 2023 |
| Acer          | Aspire 7720                 | Notebook    | [b80fa5f7ff](https://linux-hardware.org/?probe=b80fa5f7ff) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [500bee4bb7](https://linux-hardware.org/?probe=500bee4bb7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [189b1a8ec7](https://linux-hardware.org/?probe=189b1a8ec7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [9be2c9ee2b](https://linux-hardware.org/?probe=9be2c9ee2b) | Mar 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [054bb62a67](https://linux-hardware.org/?probe=054bb62a67) | Mar 14, 2023 |
| HP            | ProLiant SL4540 Gen8        | Desktop     | [fb493ce600](https://linux-hardware.org/?probe=fb493ce600) | Mar 14, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [3a99fb6400](https://linux-hardware.org/?probe=3a99fb6400) | Mar 14, 2023 |
| sunxi         | LeMaker Banana Pi           | Soc         | [d27d307085](https://linux-hardware.org/?probe=d27d307085) | Mar 14, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [36bcd11bd3](https://linux-hardware.org/?probe=36bcd11bd3) | Mar 14, 2023 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [7733f89d7d](https://linux-hardware.org/?probe=7733f89d7d) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [aca12aa4c5](https://linux-hardware.org/?probe=aca12aa4c5) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [5c4b7a9754](https://linux-hardware.org/?probe=5c4b7a9754) | Mar 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [6c76af84cb](https://linux-hardware.org/?probe=6c76af84cb) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [481073d13f](https://linux-hardware.org/?probe=481073d13f) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [497a7bdef5](https://linux-hardware.org/?probe=497a7bdef5) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [07ceb1e102](https://linux-hardware.org/?probe=07ceb1e102) | Mar 13, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [8100c63113](https://linux-hardware.org/?probe=8100c63113) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [79fdcb1951](https://linux-hardware.org/?probe=79fdcb1951) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [73e4261a63](https://linux-hardware.org/?probe=73e4261a63) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [44784531d4](https://linux-hardware.org/?probe=44784531d4) | Mar 13, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [e58e88f5fd](https://linux-hardware.org/?probe=e58e88f5fd) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [267c6693a0](https://linux-hardware.org/?probe=267c6693a0) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [bdb4c28449](https://linux-hardware.org/?probe=bdb4c28449) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [d9226f0ad6](https://linux-hardware.org/?probe=d9226f0ad6) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [906f70a5e9](https://linux-hardware.org/?probe=906f70a5e9) | Mar 13, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [9793c62af0](https://linux-hardware.org/?probe=9793c62af0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [0cee087c15](https://linux-hardware.org/?probe=0cee087c15) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4d7dad3628](https://linux-hardware.org/?probe=4d7dad3628) | Mar 13, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [a35e76c9bf](https://linux-hardware.org/?probe=a35e76c9bf) | Mar 13, 2023 |
| Dell          | 09N44V A05                  | Server      | [d1a141052c](https://linux-hardware.org/?probe=d1a141052c) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [881e48f258](https://linux-hardware.org/?probe=881e48f258) | Mar 13, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [bd231fbff6](https://linux-hardware.org/?probe=bd231fbff6) | Mar 12, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6ddc564b5d](https://linux-hardware.org/?probe=6ddc564b5d) | Mar 12, 2023 |
| HP            | 1825                        | Desktop     | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [f69ef4ff89](https://linux-hardware.org/?probe=f69ef4ff89) | Mar 12, 2023 |
| Medion        | TJ4125                      | Desktop     | [5b8893bf40](https://linux-hardware.org/?probe=5b8893bf40) | Mar 12, 2023 |
| Lenovo        | ThinkPad X131e 3367AG9      | Notebook    | [0ff86711d1](https://linux-hardware.org/?probe=0ff86711d1) | Mar 12, 2023 |
| Dell          | Latitude 3510               | Notebook    | [13ed29770d](https://linux-hardware.org/?probe=13ed29770d) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [4dd7be5be9](https://linux-hardware.org/?probe=4dd7be5be9) | Mar 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2e839dd9f0](https://linux-hardware.org/?probe=2e839dd9f0) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| HP            | ProBook 4415s               | Notebook    | [8b974a2717](https://linux-hardware.org/?probe=8b974a2717) | Mar 12, 2023 |
| Medion        | TJ4125                      | Desktop     | [a93f645a7b](https://linux-hardware.org/?probe=a93f645a7b) | Mar 11, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [c91efb0de0](https://linux-hardware.org/?probe=c91efb0de0) | Mar 11, 2023 |
| MSI           | MS-B1831                    | Desktop     | [a9bfb4f294](https://linux-hardware.org/?probe=a9bfb4f294) | Mar 11, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [988d270005](https://linux-hardware.org/?probe=988d270005) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | Desktop     | [2d0fdf6553](https://linux-hardware.org/?probe=2d0fdf6553) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | Desktop     | [34a92205b4](https://linux-hardware.org/?probe=34a92205b4) | Mar 11, 2023 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | Desktop     | [eff63861e7](https://linux-hardware.org/?probe=eff63861e7) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | Desktop     | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | Notebook    | [f066472937](https://linux-hardware.org/?probe=f066472937) | Mar 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5d7fdfa3ab](https://linux-hardware.org/?probe=5d7fdfa3ab) | Mar 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [92e7dacbc6](https://linux-hardware.org/?probe=92e7dacbc6) | Mar 11, 2023 |
| Dell          | Latitude E6430              | Notebook    | [080ad6aa2a](https://linux-hardware.org/?probe=080ad6aa2a) | Mar 11, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [f8e050789f](https://linux-hardware.org/?probe=f8e050789f) | Mar 11, 2023 |
| AZW           | SER                         | Mini pc     | [86a3944105](https://linux-hardware.org/?probe=86a3944105) | Mar 11, 2023 |
| AZW           | SER                         | Mini pc     | [96c3aadd1e](https://linux-hardware.org/?probe=96c3aadd1e) | Mar 11, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [dc1a94966b](https://linux-hardware.org/?probe=dc1a94966b) | Mar 11, 2023 |
| ASUSTek       | AT3N7A-I                    | Desktop     | [59de62aac5](https://linux-hardware.org/?probe=59de62aac5) | Mar 11, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [823c3530a1](https://linux-hardware.org/?probe=823c3530a1) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [ffb66872c2](https://linux-hardware.org/?probe=ffb66872c2) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [9736a383d7](https://linux-hardware.org/?probe=9736a383d7) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [f9bd57cf06](https://linux-hardware.org/?probe=f9bd57cf06) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [a71d5d0d96](https://linux-hardware.org/?probe=a71d5d0d96) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [35ab0f32c5](https://linux-hardware.org/?probe=35ab0f32c5) | Mar 10, 2023 |
| HP            | ProLiant DL380 Gen9         | Server      | [5f85fdadf1](https://linux-hardware.org/?probe=5f85fdadf1) | Mar 10, 2023 |
| Dell          | 072XWF A03                  | Server      | [87ee1b58e4](https://linux-hardware.org/?probe=87ee1b58e4) | Mar 10, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [87aa621d6a](https://linux-hardware.org/?probe=87aa621d6a) | Mar 10, 2023 |
| Dell          | Latitude 7285               | Notebook    | [dfc4961010](https://linux-hardware.org/?probe=dfc4961010) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [91985ffa00](https://linux-hardware.org/?probe=91985ffa00) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [40499e56d1](https://linux-hardware.org/?probe=40499e56d1) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [3abbf961d5](https://linux-hardware.org/?probe=3abbf961d5) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [734afe2673](https://linux-hardware.org/?probe=734afe2673) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [364b9159c4](https://linux-hardware.org/?probe=364b9159c4) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | Notebook    | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [495614211e](https://linux-hardware.org/?probe=495614211e) | Mar 09, 2023 |
| FriendlyEl... | NanoPC-T4                   | Soc         | [901194d1e1](https://linux-hardware.org/?probe=901194d1e1) | Mar 09, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9946c1c6dc](https://linux-hardware.org/?probe=9946c1c6dc) | Mar 09, 2023 |
| ASRock        | G31M-VS2                    | Desktop     | [c098fa3ee0](https://linux-hardware.org/?probe=c098fa3ee0) | Mar 09, 2023 |
| AZW           | MINI S                      | Desktop     | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | Notebook    | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [326cdc81b2](https://linux-hardware.org/?probe=326cdc81b2) | Mar 09, 2023 |
| libre-comp... | aml-s905x-cc                | Soc         | [fba90acf4d](https://linux-hardware.org/?probe=fba90acf4d) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [7f3075e65e](https://linux-hardware.org/?probe=7f3075e65e) | Mar 08, 2023 |
| Medion        | E122X                       | Notebook    | [dad02f1ac7](https://linux-hardware.org/?probe=dad02f1ac7) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [07f425d57f](https://linux-hardware.org/?probe=07f425d57f) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [f62ef69dcc](https://linux-hardware.org/?probe=f62ef69dcc) | Mar 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0a5c3f157b](https://linux-hardware.org/?probe=0a5c3f157b) | Mar 08, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [4f55573ba6](https://linux-hardware.org/?probe=4f55573ba6) | Mar 08, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [d059dad473](https://linux-hardware.org/?probe=d059dad473) | Mar 08, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ac75dbf1f6](https://linux-hardware.org/?probe=ac75dbf1f6) | Mar 08, 2023 |
| HP            | 0AACh                       | Desktop     | [2f4ba72670](https://linux-hardware.org/?probe=2f4ba72670) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [69dd85d8cf](https://linux-hardware.org/?probe=69dd85d8cf) | Mar 07, 2023 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [cfb630c626](https://linux-hardware.org/?probe=cfb630c626) | Mar 07, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [ced1079ce2](https://linux-hardware.org/?probe=ced1079ce2) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [e6cbad4861](https://linux-hardware.org/?probe=e6cbad4861) | Mar 07, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [cca3440ed3](https://linux-hardware.org/?probe=cca3440ed3) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [6fa1bc8547](https://linux-hardware.org/?probe=6fa1bc8547) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [ce9ba5580b](https://linux-hardware.org/?probe=ce9ba5580b) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [9a8f396913](https://linux-hardware.org/?probe=9a8f396913) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [07709f5f79](https://linux-hardware.org/?probe=07709f5f79) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [8bbc04cb55](https://linux-hardware.org/?probe=8bbc04cb55) | Mar 07, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [a3682a5cb6](https://linux-hardware.org/?probe=a3682a5cb6) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [7b1918ab47](https://linux-hardware.org/?probe=7b1918ab47) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [0d996d4041](https://linux-hardware.org/?probe=0d996d4041) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [eb4c28b498](https://linux-hardware.org/?probe=eb4c28b498) | Mar 07, 2023 |
| MSI           | 880GM-E43                   | Desktop     | [f4027fb865](https://linux-hardware.org/?probe=f4027fb865) | Mar 07, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [124045e654](https://linux-hardware.org/?probe=124045e654) | Mar 07, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [8659fe0f82](https://linux-hardware.org/?probe=8659fe0f82) | Mar 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [242bd44f0c](https://linux-hardware.org/?probe=242bd44f0c) | Mar 07, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [5a1521197e](https://linux-hardware.org/?probe=5a1521197e) | Mar 07, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [119a07048d](https://linux-hardware.org/?probe=119a07048d) | Mar 06, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [91db409270](https://linux-hardware.org/?probe=91db409270) | Mar 06, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [5f0ab2a253](https://linux-hardware.org/?probe=5f0ab2a253) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [a0bccf2d2b](https://linux-hardware.org/?probe=a0bccf2d2b) | Mar 06, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [e93c6204c1](https://linux-hardware.org/?probe=e93c6204c1) | Mar 06, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [ae0bbd2f73](https://linux-hardware.org/?probe=ae0bbd2f73) | Mar 06, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [3f57fb1495](https://linux-hardware.org/?probe=3f57fb1495) | Mar 06, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [423b13a62d](https://linux-hardware.org/?probe=423b13a62d) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [2f63b318f6](https://linux-hardware.org/?probe=2f63b318f6) | Mar 06, 2023 |
| Gigabyte      | Z68X-UD3-B3                 | Desktop     | [f2be73745e](https://linux-hardware.org/?probe=f2be73745e) | Mar 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [4a0130d910](https://linux-hardware.org/?probe=4a0130d910) | Mar 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [2194ce4568](https://linux-hardware.org/?probe=2194ce4568) | Mar 06, 2023 |
| MSI           | PS42 8RB                    | Notebook    | [57231416e1](https://linux-hardware.org/?probe=57231416e1) | Mar 06, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [31a734c56b](https://linux-hardware.org/?probe=31a734c56b) | Mar 06, 2023 |
| AZW           | MINI S                      | Desktop     | [cb0b08973d](https://linux-hardware.org/?probe=cb0b08973d) | Mar 06, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [fc381c78e7](https://linux-hardware.org/?probe=fc381c78e7) | Mar 05, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [308b516329](https://linux-hardware.org/?probe=308b516329) | Mar 05, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [641d1c6a8f](https://linux-hardware.org/?probe=641d1c6a8f) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [b9677c823b](https://linux-hardware.org/?probe=b9677c823b) | Mar 05, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [ca566e314e](https://linux-hardware.org/?probe=ca566e314e) | Mar 05, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [cadbbe841e](https://linux-hardware.org/?probe=cadbbe841e) | Mar 05, 2023 |
| Dell          | G5 5500                     | Notebook    | [7da5494dea](https://linux-hardware.org/?probe=7da5494dea) | Mar 05, 2023 |
| HP            | G42                         | Notebook    | [7dee433139](https://linux-hardware.org/?probe=7dee433139) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [47f08e4094](https://linux-hardware.org/?probe=47f08e4094) | Mar 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| Dell          | Latitude E5450              | Notebook    | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| Intel         | powered classmate PC        | Notebook    | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [82acbe37f7](https://linux-hardware.org/?probe=82acbe37f7) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | Notebook    | [1bfad93a1e](https://linux-hardware.org/?probe=1bfad93a1e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | Notebook    | [f782f8e288](https://linux-hardware.org/?probe=f782f8e288) | Mar 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [10c4eda3a2](https://linux-hardware.org/?probe=10c4eda3a2) | Mar 04, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [29fa7c0b23](https://linux-hardware.org/?probe=29fa7c0b23) | Mar 04, 2023 |
| Unknown       | i855-W83627HF               | Desktop     | [e60d4877f4](https://linux-hardware.org/?probe=e60d4877f4) | Mar 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [a9c39c2b82](https://linux-hardware.org/?probe=a9c39c2b82) | Mar 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [a4e8543fe2](https://linux-hardware.org/?probe=a4e8543fe2) | Mar 03, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [cdaf43afa8](https://linux-hardware.org/?probe=cdaf43afa8) | Mar 03, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [02df2ea534](https://linux-hardware.org/?probe=02df2ea534) | Mar 03, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [7471275fc7](https://linux-hardware.org/?probe=7471275fc7) | Mar 03, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [31fc7e49b2](https://linux-hardware.org/?probe=31fc7e49b2) | Mar 03, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [f102669f1f](https://linux-hardware.org/?probe=f102669f1f) | Mar 03, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [7adf1c211e](https://linux-hardware.org/?probe=7adf1c211e) | Mar 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [7afe06d070](https://linux-hardware.org/?probe=7afe06d070) | Mar 03, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [54a92cd736](https://linux-hardware.org/?probe=54a92cd736) | Mar 03, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [916405bd1c](https://linux-hardware.org/?probe=916405bd1c) | Mar 03, 2023 |
| HP            | 635                         | Notebook    | [108b9443ea](https://linux-hardware.org/?probe=108b9443ea) | Mar 03, 2023 |
| Dell          | Latitude E7440              | Notebook    | [36439d1a64](https://linux-hardware.org/?probe=36439d1a64) | Mar 03, 2023 |
| Win elemen... | M600                        | Desktop     | [36ce350e0c](https://linux-hardware.org/?probe=36ce350e0c) | Mar 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [845ed95f72](https://linux-hardware.org/?probe=845ed95f72) | Mar 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [180f5c9379](https://linux-hardware.org/?probe=180f5c9379) | Mar 03, 2023 |
| Dell          | Vostro1710                  | Notebook    | [c24eab7e3d](https://linux-hardware.org/?probe=c24eab7e3d) | Mar 02, 2023 |
| Unknown       | Unknown                     | Soc         | [59b899bee2](https://linux-hardware.org/?probe=59b899bee2) | Mar 02, 2023 |
| Unknown       | Unknown                     | Soc         | [71faa2a8b1](https://linux-hardware.org/?probe=71faa2a8b1) | Mar 02, 2023 |
| Dell          | 0D6H9T A02                  | Desktop     | [0027e59622](https://linux-hardware.org/?probe=0027e59622) | Mar 02, 2023 |
| Acer          | Aspire 1640Z                | Notebook    | [915a8900d0](https://linux-hardware.org/?probe=915a8900d0) | Mar 02, 2023 |
| Dell          | Latitude E7440              | Notebook    | [b84f760e8e](https://linux-hardware.org/?probe=b84f760e8e) | Mar 02, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8f61a5507b](https://linux-hardware.org/?probe=8f61a5507b) | Mar 02, 2023 |
| AMI           | Intel                       | Desktop     | [b6d932a0ed](https://linux-hardware.org/?probe=b6d932a0ed) | Mar 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0e66878368](https://linux-hardware.org/?probe=0e66878368) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | Desktop     | [93e91a76bf](https://linux-hardware.org/?probe=93e91a76bf) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | Desktop     | [1774000cc4](https://linux-hardware.org/?probe=1774000cc4) | Mar 02, 2023 |
| ASUSTek       | X556UR                      | Notebook    | [70c4807d21](https://linux-hardware.org/?probe=70c4807d21) | Mar 02, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [11c1bf8316](https://linux-hardware.org/?probe=11c1bf8316) | Mar 02, 2023 |
| ECS           | G31T-M9                     | Desktop     | [88447490cb](https://linux-hardware.org/?probe=88447490cb) | Mar 02, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [21d1213402](https://linux-hardware.org/?probe=21d1213402) | Mar 02, 2023 |
| MSI           | Creator 15M A9SD            | Notebook    | [b19d8d936c](https://linux-hardware.org/?probe=b19d8d936c) | Mar 02, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [b53826c91c](https://linux-hardware.org/?probe=b53826c91c) | Mar 02, 2023 |
| Supermicro    | X11SPM-TF                   | Server      | [6d1f207293](https://linux-hardware.org/?probe=6d1f207293) | Mar 02, 2023 |
| Supermicro    | X11SPM-TF                   | Server      | [c4eb62ca69](https://linux-hardware.org/?probe=c4eb62ca69) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | Desktop     | [977be97551](https://linux-hardware.org/?probe=977be97551) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | Desktop     | [2191c9e96a](https://linux-hardware.org/?probe=2191c9e96a) | Mar 02, 2023 |
| Supermicro    | X8DT6                       | Server      | [6e08baab68](https://linux-hardware.org/?probe=6e08baab68) | Mar 02, 2023 |
| Supermicro    | X10DRC-LN4+                 | Server      | [6b0669d84c](https://linux-hardware.org/?probe=6b0669d84c) | Mar 02, 2023 |
| Dell          | Latitude 3510               | Notebook    | [0bad8d504d](https://linux-hardware.org/?probe=0bad8d504d) | Mar 02, 2023 |
| PC Special... | 14 Fusion IV                | Notebook    | [e465178d82](https://linux-hardware.org/?probe=e465178d82) | Mar 02, 2023 |
| Supermicro    | X11DPi-NT                   | Server      | [be6bb6833c](https://linux-hardware.org/?probe=be6bb6833c) | Mar 02, 2023 |
| Supermicro    | X11DPi-NT                   | Server      | [5a9cc71286](https://linux-hardware.org/?probe=5a9cc71286) | Mar 02, 2023 |
| Supermicro    | X11DPi-NT                   | Server      | [0dbca183b8](https://linux-hardware.org/?probe=0dbca183b8) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | Desktop     | [5b8c79ac33](https://linux-hardware.org/?probe=5b8c79ac33) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | Desktop     | [80644bb1ec](https://linux-hardware.org/?probe=80644bb1ec) | Mar 02, 2023 |
| Supermicro    | X10DRC-LN4+                 | Server      | [7faa52f1c0](https://linux-hardware.org/?probe=7faa52f1c0) | Mar 02, 2023 |
| Supermicro    | X8DT6                       | Server      | [3bf2cd3526](https://linux-hardware.org/?probe=3bf2cd3526) | Mar 02, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2894a5929b](https://linux-hardware.org/?probe=2894a5929b) | Mar 02, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [9036fa2ef1](https://linux-hardware.org/?probe=9036fa2ef1) | Mar 02, 2023 |
| GMKtec        | NucBox5                     | Notebook    | [fc11280fe6](https://linux-hardware.org/?probe=fc11280fe6) | Mar 02, 2023 |
| ZOTAC         | ZBOX-CI331NANO              | Mini pc     | [6d26f07cd1](https://linux-hardware.org/?probe=6d26f07cd1) | Mar 01, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f6b780ae7e](https://linux-hardware.org/?probe=f6b780ae7e) | Mar 01, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [aea23f5903](https://linux-hardware.org/?probe=aea23f5903) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [25112e4f96](https://linux-hardware.org/?probe=25112e4f96) | Mar 01, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [8089ba23b4](https://linux-hardware.org/?probe=8089ba23b4) | Mar 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [da2fc6826a](https://linux-hardware.org/?probe=da2fc6826a) | Mar 01, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [6e5e4d848d](https://linux-hardware.org/?probe=6e5e4d848d) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [52ecc1a9fb](https://linux-hardware.org/?probe=52ecc1a9fb) | Mar 01, 2023 |
| AZW           | MINI S                      | Desktop     | [2206d30a53](https://linux-hardware.org/?probe=2206d30a53) | Mar 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a91c417b74](https://linux-hardware.org/?probe=a91c417b74) | Mar 01, 2023 |
| HP            | 8433 11                     | Desktop     | [15dccf1191](https://linux-hardware.org/?probe=15dccf1191) | Mar 01, 2023 |
| HP            | ProBook 4415s               | Notebook    | [4e909ec0ad](https://linux-hardware.org/?probe=4e909ec0ad) | Mar 01, 2023 |
| Umbrel        | Home                        | Mini pc     | [f4afc80a6c](https://linux-hardware.org/?probe=f4afc80a6c) | Feb 28, 2023 |
| Medion        | TJ4125                      | Desktop     | [2024916642](https://linux-hardware.org/?probe=2024916642) | Feb 28, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [46c17d2c14](https://linux-hardware.org/?probe=46c17d2c14) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| HP            | 83E2                        | Desktop     | [fdbe4ec1cb](https://linux-hardware.org/?probe=fdbe4ec1cb) | Feb 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [19fd766ea6](https://linux-hardware.org/?probe=19fd766ea6) | Feb 28, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [17fcfc2758](https://linux-hardware.org/?probe=17fcfc2758) | Feb 28, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [26a7db2ed8](https://linux-hardware.org/?probe=26a7db2ed8) | Feb 28, 2023 |
| AZW           | MINI S                      | Desktop     | [e65b0d1ef6](https://linux-hardware.org/?probe=e65b0d1ef6) | Feb 28, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [49205269e7](https://linux-hardware.org/?probe=49205269e7) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [a5469adf59](https://linux-hardware.org/?probe=a5469adf59) | Feb 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b4bfab8974](https://linux-hardware.org/?probe=b4bfab8974) | Feb 28, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4d3d5e02a1](https://linux-hardware.org/?probe=4d3d5e02a1) | Feb 28, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3948048a11](https://linux-hardware.org/?probe=3948048a11) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| HP            | 3397                        | Desktop     | [8081d24eb1](https://linux-hardware.org/?probe=8081d24eb1) | Feb 27, 2023 |
| Dell          | 0MH651                      | Desktop     | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Aquarius      | AQH310CM                    | Desktop     | [a2f4d0f77e](https://linux-hardware.org/?probe=a2f4d0f77e) | Feb 27, 2023 |
| Dell          | Latitude 5400               | Notebook    | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| Dell          | Latitude 3510               | Notebook    | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [7a8e478900](https://linux-hardware.org/?probe=7a8e478900) | Feb 27, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [29f6c3c897](https://linux-hardware.org/?probe=29f6c3c897) | Feb 27, 2023 |
| ASUSTek       | K52F                        | Notebook    | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [ee5b36d127](https://linux-hardware.org/?probe=ee5b36d127) | Feb 27, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [dd2f99b3ca](https://linux-hardware.org/?probe=dd2f99b3ca) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| HP            | Pavilion g6                 | Notebook    | [41e4ef16e4](https://linux-hardware.org/?probe=41e4ef16e4) | Feb 26, 2023 |
| Olimex        | A20-OLinuXino-LIME          | Soc         | [bcb9e7b9e7](https://linux-hardware.org/?probe=bcb9e7b9e7) | Feb 26, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [787ddfd44c](https://linux-hardware.org/?probe=787ddfd44c) | Feb 26, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [3c4718f66e](https://linux-hardware.org/?probe=3c4718f66e) | Feb 26, 2023 |
| Panasonic     | CF-31WEUEEBE                | Notebook    | [40782ba0a7](https://linux-hardware.org/?probe=40782ba0a7) | Feb 26, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Server      | [ffa58f1702](https://linux-hardware.org/?probe=ffa58f1702) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430 2349GUU       | Notebook    | [95cc420bd5](https://linux-hardware.org/?probe=95cc420bd5) | Feb 26, 2023 |
| Medion        | BEAST X25                   | Notebook    | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | Notebook    | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9c64d6366e](https://linux-hardware.org/?probe=9c64d6366e) | Feb 26, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BX... | Notebook    | [633fb08804](https://linux-hardware.org/?probe=633fb08804) | Feb 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [aaa112feae](https://linux-hardware.org/?probe=aaa112feae) | Feb 26, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b05fb1c01b](https://linux-hardware.org/?probe=b05fb1c01b) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [3b2a19c835](https://linux-hardware.org/?probe=3b2a19c835) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| Unknown       | T3 MRD                      | Notebook    | [ae88920ea5](https://linux-hardware.org/?probe=ae88920ea5) | Feb 25, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| MSI           | B85M-E45                    | Desktop     | [a7748c0e8b](https://linux-hardware.org/?probe=a7748c0e8b) | Feb 25, 2023 |
| HUAWEI        | WRT-WX9                     | Notebook    | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [67e31f8e42](https://linux-hardware.org/?probe=67e31f8e42) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2bb4e30118](https://linux-hardware.org/?probe=2bb4e30118) | Feb 25, 2023 |
| Medion        | TJ4125                      | Desktop     | [bde9228741](https://linux-hardware.org/?probe=bde9228741) | Feb 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [f1db9ad466](https://linux-hardware.org/?probe=f1db9ad466) | Feb 25, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [ff08a846b0](https://linux-hardware.org/?probe=ff08a846b0) | Feb 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [2c5d6ab621](https://linux-hardware.org/?probe=2c5d6ab621) | Feb 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [15b5511875](https://linux-hardware.org/?probe=15b5511875) | Feb 25, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [b3b189e875](https://linux-hardware.org/?probe=b3b189e875) | Feb 25, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [d615820c71](https://linux-hardware.org/?probe=d615820c71) | Feb 25, 2023 |
| Intel         | JSL MRD                     | Desktop     | [84a33f3c84](https://linux-hardware.org/?probe=84a33f3c84) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Acer          | AO756                       | Notebook    | [ca83ee78ec](https://linux-hardware.org/?probe=ca83ee78ec) | Feb 24, 2023 |
| Lenovo        | KaiTian N70z G1d            | Notebook    | [cbc8e4e008](https://linux-hardware.org/?probe=cbc8e4e008) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [c2ca1fb2f3](https://linux-hardware.org/?probe=c2ca1fb2f3) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7fe6e0dcde](https://linux-hardware.org/?probe=7fe6e0dcde) | Feb 24, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [f5b4a5da72](https://linux-hardware.org/?probe=f5b4a5da72) | Feb 24, 2023 |
| HP            | Presario CQ57               | Notebook    | [b41de6d094](https://linux-hardware.org/?probe=b41de6d094) | Feb 24, 2023 |
| HP            | 82F2 A01                    | Desktop     | [efc9b2fdbf](https://linux-hardware.org/?probe=efc9b2fdbf) | Feb 24, 2023 |
| HP            | 82F2 A01                    | Desktop     | [24dc4341d3](https://linux-hardware.org/?probe=24dc4341d3) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3f28f459bf](https://linux-hardware.org/?probe=3f28f459bf) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8ed4158090](https://linux-hardware.org/?probe=8ed4158090) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [1989031eb6](https://linux-hardware.org/?probe=1989031eb6) | Feb 24, 2023 |
| Dell          | Latitude D620               | Notebook    | [fba80b099d](https://linux-hardware.org/?probe=fba80b099d) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5da2f709bb](https://linux-hardware.org/?probe=5da2f709bb) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [bf32299a30](https://linux-hardware.org/?probe=bf32299a30) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [54279e4e30](https://linux-hardware.org/?probe=54279e4e30) | Feb 24, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [788e0929de](https://linux-hardware.org/?probe=788e0929de) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [52b14c9235](https://linux-hardware.org/?probe=52b14c9235) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [a09d17dd16](https://linux-hardware.org/?probe=a09d17dd16) | Feb 24, 2023 |
| Samsung       | N150P                       | Notebook    | [662488621d](https://linux-hardware.org/?probe=662488621d) | Feb 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e3f8cf325d](https://linux-hardware.org/?probe=e3f8cf325d) | Feb 24, 2023 |
| Unknown       | Unknown                     | Soc         | [23a808c1e1](https://linux-hardware.org/?probe=23a808c1e1) | Feb 24, 2023 |
| Unknown       | Unknown                     | Soc         | [44fdfeedf2](https://linux-hardware.org/?probe=44fdfeedf2) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [0806dcb9ca](https://linux-hardware.org/?probe=0806dcb9ca) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [e3cdd0b411](https://linux-hardware.org/?probe=e3cdd0b411) | Feb 24, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [e44618f1c3](https://linux-hardware.org/?probe=e44618f1c3) | Feb 23, 2023 |
| ASUSTek       | KRPA-U16 Series             | Desktop     | [e417ffd8e7](https://linux-hardware.org/?probe=e417ffd8e7) | Feb 23, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [885478dd47](https://linux-hardware.org/?probe=885478dd47) | Feb 23, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [53eb80a44b](https://linux-hardware.org/?probe=53eb80a44b) | Feb 23, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [8d4b399341](https://linux-hardware.org/?probe=8d4b399341) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [4f19f71811](https://linux-hardware.org/?probe=4f19f71811) | Feb 23, 2023 |
| Dell          | 01V648 A03                  | Server      | [c0b7421a8b](https://linux-hardware.org/?probe=c0b7421a8b) | Feb 23, 2023 |
| LincPlus      | P2                          | Notebook    | [5d4e528621](https://linux-hardware.org/?probe=5d4e528621) | Feb 23, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [a3ea522d78](https://linux-hardware.org/?probe=a3ea522d78) | Feb 23, 2023 |
| Intel         | H61                         | Desktop     | [de757dd659](https://linux-hardware.org/?probe=de757dd659) | Feb 23, 2023 |
| Lenovo        | ThinkPad E14 20RA0036HV     | Notebook    | [eef601ff61](https://linux-hardware.org/?probe=eef601ff61) | Feb 23, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [09070f52bb](https://linux-hardware.org/?probe=09070f52bb) | Feb 23, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| AZW           | U59                         | Desktop     | [9289537f45](https://linux-hardware.org/?probe=9289537f45) | Feb 22, 2023 |
| Fujitsu       | LIFEBOOK E753               | Notebook    | [8fa3315cca](https://linux-hardware.org/?probe=8fa3315cca) | Feb 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9d233c96b5](https://linux-hardware.org/?probe=9d233c96b5) | Feb 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [8227fec538](https://linux-hardware.org/?probe=8227fec538) | Feb 22, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [fb050eaf3c](https://linux-hardware.org/?probe=fb050eaf3c) | Feb 22, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [7cf8754a48](https://linux-hardware.org/?probe=7cf8754a48) | Feb 22, 2023 |
| Acer          | AO756                       | Notebook    | [58f52941c7](https://linux-hardware.org/?probe=58f52941c7) | Feb 22, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1d2132b142](https://linux-hardware.org/?probe=1d2132b142) | Feb 22, 2023 |
| AZW           | U59                         | Desktop     | [368562790b](https://linux-hardware.org/?probe=368562790b) | Feb 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [5cf4127d47](https://linux-hardware.org/?probe=5cf4127d47) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [de56e36164](https://linux-hardware.org/?probe=de56e36164) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | Notebook    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| Dell          | 0TT740 A00                  | Server      | [2e77448a7d](https://linux-hardware.org/?probe=2e77448a7d) | Feb 21, 2023 |
| Dell          | 0TT740 A00                  | Server      | [ec75c9762a](https://linux-hardware.org/?probe=ec75c9762a) | Feb 21, 2023 |
| HP            | ProLiant ML110 G7           | Desktop     | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [6ab7953740](https://linux-hardware.org/?probe=6ab7953740) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| HP            | Stream 8 Tablet             | Tablet      | [211438a893](https://linux-hardware.org/?probe=211438a893) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Acer          | Extensa 2520G               | Notebook    | [823c5829a9](https://linux-hardware.org/?probe=823c5829a9) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | Notebook    | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58e 7269E3S    | Desktop     | [6b30da3a31](https://linux-hardware.org/?probe=6b30da3a31) | Feb 20, 2023 |
| Dell          | Latitude E7270              | Notebook    | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [53ba72d592](https://linux-hardware.org/?probe=53ba72d592) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [b778aa73ca](https://linux-hardware.org/?probe=b778aa73ca) | Feb 19, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [a2250b4489](https://linux-hardware.org/?probe=a2250b4489) | Feb 19, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [e259c81376](https://linux-hardware.org/?probe=e259c81376) | Feb 19, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [2e3da97146](https://linux-hardware.org/?probe=2e3da97146) | Feb 19, 2023 |
| Dell          | 0NHNHP A01                  | Server      | [da74244bff](https://linux-hardware.org/?probe=da74244bff) | Feb 19, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [aa198228bc](https://linux-hardware.org/?probe=aa198228bc) | Feb 19, 2023 |
| Dell          | 0T065F A01                  | Desktop     | [c8b1f8651a](https://linux-hardware.org/?probe=c8b1f8651a) | Feb 19, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [537c2d1b64](https://linux-hardware.org/?probe=537c2d1b64) | Feb 18, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [3158f1e0d5](https://linux-hardware.org/?probe=3158f1e0d5) | Feb 18, 2023 |
| Supermicro    | X11SCA-WA                   | Server      | [065427c37f](https://linux-hardware.org/?probe=065427c37f) | Feb 18, 2023 |
| Intel         | JSL MRD                     | Desktop     | [5e021f6a92](https://linux-hardware.org/?probe=5e021f6a92) | Feb 18, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | Notebook    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a782ccbba9](https://linux-hardware.org/?probe=a782ccbba9) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Dell          | Latitude E5450              | Notebook    | [56827b29dc](https://linux-hardware.org/?probe=56827b29dc) | Feb 18, 2023 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [3159aede6c](https://linux-hardware.org/?probe=3159aede6c) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Notebook    | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [bd6636c99d](https://linux-hardware.org/?probe=bd6636c99d) | Feb 17, 2023 |
| Intel         | H61                         | Desktop     | [90e4a9358f](https://linux-hardware.org/?probe=90e4a9358f) | Feb 17, 2023 |
| MSI           | X399 SLI PLUS               | Desktop     | [8741094cd9](https://linux-hardware.org/?probe=8741094cd9) | Feb 17, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [423c7bb57a](https://linux-hardware.org/?probe=423c7bb57a) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [4bf1ccfe74](https://linux-hardware.org/?probe=4bf1ccfe74) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| Dell          | System XPS L702X            | Notebook    | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | Desktop     | [cfdcc68921](https://linux-hardware.org/?probe=cfdcc68921) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | Desktop     | [7bb3c6268f](https://linux-hardware.org/?probe=7bb3c6268f) | Feb 16, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [c812182e32](https://linux-hardware.org/?probe=c812182e32) | Feb 16, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [63747d1456](https://linux-hardware.org/?probe=63747d1456) | Feb 16, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [cda38b5b9b](https://linux-hardware.org/?probe=cda38b5b9b) | Feb 16, 2023 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [387881f288](https://linux-hardware.org/?probe=387881f288) | Feb 16, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bbce6ba3b1](https://linux-hardware.org/?probe=bbce6ba3b1) | Feb 16, 2023 |
| Lenovo        | 1030 SDK0J40705 WIN 3425... | Desktop     | [daed0124f0](https://linux-hardware.org/?probe=daed0124f0) | Feb 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [a4fd7cdaa8](https://linux-hardware.org/?probe=a4fd7cdaa8) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Gigabyte      | H270M-D3H-CF                | Desktop     | [7a58ceb644](https://linux-hardware.org/?probe=7a58ceb644) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |
| Google        | Grunt                       | Notebook    | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| Gigabyte      | EP43-S3L                    | Desktop     | [82730ed699](https://linux-hardware.org/?probe=82730ed699) | Feb 15, 2023 |
| Itautec       | ST 4265                     | Desktop     | [84023fa8ac](https://linux-hardware.org/?probe=84023fa8ac) | Feb 15, 2023 |
| ASUSTek       | P5GD1 PRO                   | Desktop     | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| ASUSTek       | K53U                        | Notebook    | [e9a6a69e01](https://linux-hardware.org/?probe=e9a6a69e01) | Feb 15, 2023 |
| ASRock        | Z77 Extreme6                | Desktop     | [48328ab864](https://linux-hardware.org/?probe=48328ab864) | Feb 15, 2023 |
| Unknown       | T3 MRD                      | Notebook    | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Acer          | Aspire V5-572G              | Notebook    | [7f360258ff](https://linux-hardware.org/?probe=7f360258ff) | Feb 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [0ac84e31dd](https://linux-hardware.org/?probe=0ac84e31dd) | Feb 14, 2023 |
| Dell          | 0RN474                      | Desktop     | [5c1bf45372](https://linux-hardware.org/?probe=5c1bf45372) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [0a0e30ba0a](https://linux-hardware.org/?probe=0a0e30ba0a) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f6bcdb7c6b](https://linux-hardware.org/?probe=f6bcdb7c6b) | Feb 14, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [67b141272c](https://linux-hardware.org/?probe=67b141272c) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [345021f7f6](https://linux-hardware.org/?probe=345021f7f6) | Feb 14, 2023 |
| Lenovo        | ThinkPad P51 20HJS0AR16     | Notebook    | [ad0f22fe34](https://linux-hardware.org/?probe=ad0f22fe34) | Feb 14, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [c69ee15636](https://linux-hardware.org/?probe=c69ee15636) | Feb 14, 2023 |
| Dell          | 0RN474                      | Desktop     | [20f3c37dc2](https://linux-hardware.org/?probe=20f3c37dc2) | Feb 14, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [4750f3ad3a](https://linux-hardware.org/?probe=4750f3ad3a) | Feb 13, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [55e684c121](https://linux-hardware.org/?probe=55e684c121) | Feb 13, 2023 |
| Dell          | Latitude D630               | Notebook    | [04c083db36](https://linux-hardware.org/?probe=04c083db36) | Feb 13, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [855634fadc](https://linux-hardware.org/?probe=855634fadc) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [6fe738fa6d](https://linux-hardware.org/?probe=6fe738fa6d) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [122eded37e](https://linux-hardware.org/?probe=122eded37e) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [e83cd923a5](https://linux-hardware.org/?probe=e83cd923a5) | Feb 13, 2023 |
| Google        | Droid                       | Notebook    | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| retsamarre... | 000-F4423-UK000-2000        | Tablet      | [c24b5a1f84](https://linux-hardware.org/?probe=c24b5a1f84) | Feb 12, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [89c31e6f8c](https://linux-hardware.org/?probe=89c31e6f8c) | Feb 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [72ce8d1929](https://linux-hardware.org/?probe=72ce8d1929) | Feb 12, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [54e092f58f](https://linux-hardware.org/?probe=54e092f58f) | Feb 12, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [09266b8b06](https://linux-hardware.org/?probe=09266b8b06) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [09dff429cd](https://linux-hardware.org/?probe=09dff429cd) | Feb 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [b54b603772](https://linux-hardware.org/?probe=b54b603772) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [52674d23ad](https://linux-hardware.org/?probe=52674d23ad) | Feb 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [9fa2cd7dfb](https://linux-hardware.org/?probe=9fa2cd7dfb) | Feb 12, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [4829b991be](https://linux-hardware.org/?probe=4829b991be) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [4a6ea9bd99](https://linux-hardware.org/?probe=4a6ea9bd99) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [063d6eb482](https://linux-hardware.org/?probe=063d6eb482) | Feb 12, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [1589cfe790](https://linux-hardware.org/?probe=1589cfe790) | Feb 11, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [22fdde82eb](https://linux-hardware.org/?probe=22fdde82eb) | Feb 11, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [3932889971](https://linux-hardware.org/?probe=3932889971) | Feb 11, 2023 |
| Notebook      | MAM2120                     | Notebook    | [300a622d96](https://linux-hardware.org/?probe=300a622d96) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ed3233c97b](https://linux-hardware.org/?probe=ed3233c97b) | Feb 11, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [94ee6da4d3](https://linux-hardware.org/?probe=94ee6da4d3) | Feb 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [27323a90bb](https://linux-hardware.org/?probe=27323a90bb) | Feb 11, 2023 |
| Acer          | Predator G9-793             | Notebook    | [8c11736bf0](https://linux-hardware.org/?probe=8c11736bf0) | Feb 11, 2023 |
| ASUSTek       | P5VD2-X                     | Desktop     | [32a509e760](https://linux-hardware.org/?probe=32a509e760) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [2695a9350a](https://linux-hardware.org/?probe=2695a9350a) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [d003016397](https://linux-hardware.org/?probe=d003016397) | Feb 11, 2023 |
| AZW           | U59                         | Desktop     | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [a3f08d08aa](https://linux-hardware.org/?probe=a3f08d08aa) | Feb 11, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [5483d83053](https://linux-hardware.org/?probe=5483d83053) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [5b2605691d](https://linux-hardware.org/?probe=5b2605691d) | Feb 11, 2023 |
| AMD           | CM-iGLX Platform Board R... | Desktop     | [c256a73072](https://linux-hardware.org/?probe=c256a73072) | Feb 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [35b93693a5](https://linux-hardware.org/?probe=35b93693a5) | Feb 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| Maxtang       | EHL30 V1.0                  | Desktop     | [4d133c615c](https://linux-hardware.org/?probe=4d133c615c) | Feb 10, 2023 |
| ASRockRack    | X570D4U                     | Desktop     | [bb2c98768e](https://linux-hardware.org/?probe=bb2c98768e) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | Notebook    | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| Intel         | H61                         | Desktop     | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [0730c9228d](https://linux-hardware.org/?probe=0730c9228d) | Feb 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [8c4ab545de](https://linux-hardware.org/?probe=8c4ab545de) | Feb 09, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [fd0b6a7a49](https://linux-hardware.org/?probe=fd0b6a7a49) | Feb 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [02adcb8587](https://linux-hardware.org/?probe=02adcb8587) | Feb 09, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [fe1dac78bb](https://linux-hardware.org/?probe=fe1dac78bb) | Feb 09, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [209d4693fe](https://linux-hardware.org/?probe=209d4693fe) | Feb 09, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | Notebook    | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| AMI           | Cherry Trail CR             | Notebook    | [e7eab93323](https://linux-hardware.org/?probe=e7eab93323) | Feb 09, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [a0132107aa](https://linux-hardware.org/?probe=a0132107aa) | Feb 08, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [6231dbe6d4](https://linux-hardware.org/?probe=6231dbe6d4) | Feb 08, 2023 |
| Dell          | Latitude E6330              | Notebook    | [291e0fd64f](https://linux-hardware.org/?probe=291e0fd64f) | Feb 08, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [965758f3ea](https://linux-hardware.org/?probe=965758f3ea) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [cc897fe72d](https://linux-hardware.org/?probe=cc897fe72d) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Intel         | DH67CL AAG10212-208         | Desktop     | [e53a89d83d](https://linux-hardware.org/?probe=e53a89d83d) | Feb 08, 2023 |
| TYAN Compu... | S4985                       | Server      | [40ea5a6601](https://linux-hardware.org/?probe=40ea5a6601) | Feb 08, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [f5aeb173ba](https://linux-hardware.org/?probe=f5aeb173ba) | Feb 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3245fc2fec](https://linux-hardware.org/?probe=3245fc2fec) | Feb 08, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [8fb3a20b27](https://linux-hardware.org/?probe=8fb3a20b27) | Feb 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [def4679f84](https://linux-hardware.org/?probe=def4679f84) | Feb 07, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| Panasonic     | CF-54-1                     | Notebook    | [32a2acc07e](https://linux-hardware.org/?probe=32a2acc07e) | Feb 07, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [69f96bffa5](https://linux-hardware.org/?probe=69f96bffa5) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Dell          | Latitude E7250              | Notebook    | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| Dell          | Precision 5570              | Notebook    | [d279e97c00](https://linux-hardware.org/?probe=d279e97c00) | Feb 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7e020b928e](https://linux-hardware.org/?probe=7e020b928e) | Feb 07, 2023 |
| Inspur        | Shuyu                       | Server      | [37c2630b8f](https://linux-hardware.org/?probe=37c2630b8f) | Feb 07, 2023 |
| Toshiba       | Satellite C655              | Notebook    | [a0c2eb7db1](https://linux-hardware.org/?probe=a0c2eb7db1) | Feb 07, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [83380dcad6](https://linux-hardware.org/?probe=83380dcad6) | Feb 07, 2023 |
| Dell          | 08DM12 A00                  | Server      | [4fcfb3fb2a](https://linux-hardware.org/?probe=4fcfb3fb2a) | Feb 07, 2023 |
| Intel         | NUC5CPYB H61145-402         | Mini pc     | [9cb000ed27](https://linux-hardware.org/?probe=9cb000ed27) | Feb 06, 2023 |
| HP            | 3397                        | Desktop     | [2fb7638874](https://linux-hardware.org/?probe=2fb7638874) | Feb 06, 2023 |
| Google        | Terra                       | Notebook    | [edfe00266c](https://linux-hardware.org/?probe=edfe00266c) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | Notebook    | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [b3169f788f](https://linux-hardware.org/?probe=b3169f788f) | Feb 06, 2023 |
| ASUSTek       | X71Q                        | Notebook    | [c89b078e8f](https://linux-hardware.org/?probe=c89b078e8f) | Feb 06, 2023 |
| Aquarius      | NS585                       | Notebook    | [e9deef3f9e](https://linux-hardware.org/?probe=e9deef3f9e) | Feb 06, 2023 |
| AZW           | U59                         | Desktop     | [b97c4f6277](https://linux-hardware.org/?probe=b97c4f6277) | Feb 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | Notebook    | [112a65a03e](https://linux-hardware.org/?probe=112a65a03e) | Feb 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2891f201f0](https://linux-hardware.org/?probe=2891f201f0) | Feb 06, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [db292bc714](https://linux-hardware.org/?probe=db292bc714) | Feb 05, 2023 |
| HP            | 0A64h                       | Desktop     | [40ef639345](https://linux-hardware.org/?probe=40ef639345) | Feb 05, 2023 |
| Huanan        | X99-T8D V1.2                | Desktop     | [cb7e750cee](https://linux-hardware.org/?probe=cb7e750cee) | Feb 05, 2023 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [b708cdc12f](https://linux-hardware.org/?probe=b708cdc12f) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [6023defc83](https://linux-hardware.org/?probe=6023defc83) | Feb 05, 2023 |
| Intel         | S5500HCV E40912-458         | Server      | [1445c60562](https://linux-hardware.org/?probe=1445c60562) | Feb 05, 2023 |
| Intel         | S5500HCV E40912-458         | Server      | [95ff55d958](https://linux-hardware.org/?probe=95ff55d958) | Feb 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [2f56f41681](https://linux-hardware.org/?probe=2f56f41681) | Feb 05, 2023 |
| Google        | Ampton                      | Notebook    | [74d5b6aa4d](https://linux-hardware.org/?probe=74d5b6aa4d) | Feb 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [5a491991ef](https://linux-hardware.org/?probe=5a491991ef) | Feb 05, 2023 |
| Google        | Ampton                      | Notebook    | [2785bde3f9](https://linux-hardware.org/?probe=2785bde3f9) | Feb 05, 2023 |
| HP            | 255 G3                      | Notebook    | [dfa2e96880](https://linux-hardware.org/?probe=dfa2e96880) | Feb 05, 2023 |
| MSI           | A320M PRO-M2                | Desktop     | [3fa2ac81f2](https://linux-hardware.org/?probe=3fa2ac81f2) | Feb 05, 2023 |
| Dell          | 0D4MD1 A00                  | Desktop     | [7198c3d131](https://linux-hardware.org/?probe=7198c3d131) | Feb 05, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [e0a93d257b](https://linux-hardware.org/?probe=e0a93d257b) | Feb 05, 2023 |
| OEM           | Intel H81                   | Desktop     | [806280459d](https://linux-hardware.org/?probe=806280459d) | Feb 05, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [f2423d1d75](https://linux-hardware.org/?probe=f2423d1d75) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [2543adebba](https://linux-hardware.org/?probe=2543adebba) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | Notebook    | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| Notebook      | W65_67SJ                    | Notebook    | [870af12011](https://linux-hardware.org/?probe=870af12011) | Feb 05, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [229050fbe5](https://linux-hardware.org/?probe=229050fbe5) | Feb 05, 2023 |
| ASUSTek       | F5SL                        | Notebook    | [1e5bb7661e](https://linux-hardware.org/?probe=1e5bb7661e) | Feb 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a3cab7679b](https://linux-hardware.org/?probe=a3cab7679b) | Feb 04, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [885ad2ae95](https://linux-hardware.org/?probe=885ad2ae95) | Feb 04, 2023 |
| HP            | 1589                        | Desktop     | [7b3a0cf51b](https://linux-hardware.org/?probe=7b3a0cf51b) | Feb 04, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [4ed27fe851](https://linux-hardware.org/?probe=4ed27fe851) | Feb 04, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [018b3728ea](https://linux-hardware.org/?probe=018b3728ea) | Feb 04, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [52bb20e0b2](https://linux-hardware.org/?probe=52bb20e0b2) | Feb 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0185beaec6](https://linux-hardware.org/?probe=0185beaec6) | Feb 04, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [df8aa8c06a](https://linux-hardware.org/?probe=df8aa8c06a) | Feb 04, 2023 |
| ECS           | A780GM-A                    | Desktop     | [6f6599f880](https://linux-hardware.org/?probe=6f6599f880) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | Notebook    | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| HP            | 3048h                       | Desktop     | [03b28af2be](https://linux-hardware.org/?probe=03b28af2be) | Feb 03, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [4b85a254bc](https://linux-hardware.org/?probe=4b85a254bc) | Feb 03, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [142d89a9c0](https://linux-hardware.org/?probe=142d89a9c0) | Feb 03, 2023 |
| AZW           | MINI S                      | Desktop     | [6c746a5f95](https://linux-hardware.org/?probe=6c746a5f95) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| HP            | Pavilion 15                 | Notebook    | [5909dd08e7](https://linux-hardware.org/?probe=5909dd08e7) | Feb 03, 2023 |
| Intel         | AB2L .A004                  | Mini pc     | [568740a6b1](https://linux-hardware.org/?probe=568740a6b1) | Feb 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c0c511ec65](https://linux-hardware.org/?probe=c0c511ec65) | Feb 03, 2023 |
| Aquarius      | NS585                       | Notebook    | [7e944d88b3](https://linux-hardware.org/?probe=7e944d88b3) | Feb 03, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d0d8e49083](https://linux-hardware.org/?probe=d0d8e49083) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [ae290fa64e](https://linux-hardware.org/?probe=ae290fa64e) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [7820377760](https://linux-hardware.org/?probe=7820377760) | Feb 03, 2023 |
| Xunlong       | Orange Pi Zero              | Soc         | [3af57a322f](https://linux-hardware.org/?probe=3af57a322f) | Feb 03, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [534cdba357](https://linux-hardware.org/?probe=534cdba357) | Feb 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [656df2cea9](https://linux-hardware.org/?probe=656df2cea9) | Feb 03, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [6d39ef2792](https://linux-hardware.org/?probe=6d39ef2792) | Feb 03, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [c26be60545](https://linux-hardware.org/?probe=c26be60545) | Feb 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [2f2c8adb0c](https://linux-hardware.org/?probe=2f2c8adb0c) | Feb 02, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [6d7a27b213](https://linux-hardware.org/?probe=6d7a27b213) | Feb 02, 2023 |
| Google        | Babymega                    | Notebook    | [2a8b81c6f4](https://linux-hardware.org/?probe=2a8b81c6f4) | Feb 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3483138f98](https://linux-hardware.org/?probe=3483138f98) | Feb 02, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a75cb78ad9](https://linux-hardware.org/?probe=a75cb78ad9) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [9bb5fabf0b](https://linux-hardware.org/?probe=9bb5fabf0b) | Feb 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | Notebook    | [29660bbd04](https://linux-hardware.org/?probe=29660bbd04) | Feb 02, 2023 |
| Dell          | Latitude 7480               | Notebook    | [8a7e0b16d5](https://linux-hardware.org/?probe=8a7e0b16d5) | Feb 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2de08972b9](https://linux-hardware.org/?probe=2de08972b9) | Feb 02, 2023 |
| NEC Comput... | MS9666 011                  | Desktop     | [26a38770fe](https://linux-hardware.org/?probe=26a38770fe) | Feb 02, 2023 |
| Dell          | Latitude E6520              | Notebook    | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [9deaff7467](https://linux-hardware.org/?probe=9deaff7467) | Feb 02, 2023 |
| Lenovo        | ThinkPad 13 20J10046US      | Notebook    | [85b9d54087](https://linux-hardware.org/?probe=85b9d54087) | Feb 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [2cb0ec3b98](https://linux-hardware.org/?probe=2cb0ec3b98) | Feb 01, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [b8c8ed32e5](https://linux-hardware.org/?probe=b8c8ed32e5) | Feb 01, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [203e3fe693](https://linux-hardware.org/?probe=203e3fe693) | Feb 01, 2023 |
| Samsung       | 600B4B/600B5B               | Notebook    | [d3cf4446d5](https://linux-hardware.org/?probe=d3cf4446d5) | Feb 01, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [352c998936](https://linux-hardware.org/?probe=352c998936) | Feb 01, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [c03f7668ac](https://linux-hardware.org/?probe=c03f7668ac) | Feb 01, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | Notebook    | [ac78478b3b](https://linux-hardware.org/?probe=ac78478b3b) | Feb 01, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2f0a18ba6b](https://linux-hardware.org/?probe=2f0a18ba6b) | Feb 01, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [01e8662b39](https://linux-hardware.org/?probe=01e8662b39) | Feb 01, 2023 |
| Gigabyte      | X299 AORUS Gaming 3-CF      | Desktop     | [775a993b3a](https://linux-hardware.org/?probe=775a993b3a) | Feb 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [f2b211ff3a](https://linux-hardware.org/?probe=f2b211ff3a) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | Desktop     | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| MSI           | 870A-G54                    | Desktop     | [0aaa012de5](https://linux-hardware.org/?probe=0aaa012de5) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [daa9bd48c8](https://linux-hardware.org/?probe=daa9bd48c8) | Jan 31, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [7e25d19fae](https://linux-hardware.org/?probe=7e25d19fae) | Jan 31, 2023 |
| ASRock        | G31M-VS2                    | Desktop     | [e12dd528ea](https://linux-hardware.org/?probe=e12dd528ea) | Jan 31, 2023 |
| MSI           | H81M-E34                    | Desktop     | [19b8f90522](https://linux-hardware.org/?probe=19b8f90522) | Jan 31, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d8f44aeb4c](https://linux-hardware.org/?probe=d8f44aeb4c) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [35948f3b5e](https://linux-hardware.org/?probe=35948f3b5e) | Jan 31, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [011c3940f9](https://linux-hardware.org/?probe=011c3940f9) | Jan 31, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [e335e7282d](https://linux-hardware.org/?probe=e335e7282d) | Jan 30, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [3f17be7a85](https://linux-hardware.org/?probe=3f17be7a85) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [0ae96c2bbc](https://linux-hardware.org/?probe=0ae96c2bbc) | Jan 30, 2023 |
| NetGear       | ReadyDATA 5200              | Desktop     | [74a68eba33](https://linux-hardware.org/?probe=74a68eba33) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [f13f4da766](https://linux-hardware.org/?probe=f13f4da766) | Jan 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [79e7fde988](https://linux-hardware.org/?probe=79e7fde988) | Jan 30, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d86a1c4fb2](https://linux-hardware.org/?probe=d86a1c4fb2) | Jan 30, 2023 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [a7ef98ea02](https://linux-hardware.org/?probe=a7ef98ea02) | Jan 30, 2023 |
| HP            | 0A64h                       | Desktop     | [da7b36ad47](https://linux-hardware.org/?probe=da7b36ad47) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | Notebook    | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| Sony          | PCG-Z1VA(UC)                | Notebook    | [db4f48132e](https://linux-hardware.org/?probe=db4f48132e) | Jan 29, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [55c3e9597c](https://linux-hardware.org/?probe=55c3e9597c) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [6b634c85e8](https://linux-hardware.org/?probe=6b634c85e8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Medion        | TJ4125                      | Desktop     | [5fb5d01ae9](https://linux-hardware.org/?probe=5fb5d01ae9) | Jan 29, 2023 |
| Gigabyte      | 8IPE1000-G/L                | Desktop     | [6f83e8b57d](https://linux-hardware.org/?probe=6f83e8b57d) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [e91c24c3f9](https://linux-hardware.org/?probe=e91c24c3f9) | Jan 29, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [351106d7e5](https://linux-hardware.org/?probe=351106d7e5) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | Notebook    | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | Desktop     | [8227150e0d](https://linux-hardware.org/?probe=8227150e0d) | Jan 29, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [03171e1e33](https://linux-hardware.org/?probe=03171e1e33) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | Desktop     | [813f01976d](https://linux-hardware.org/?probe=813f01976d) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| Dell          | 0F8098                      | Desktop     | [d6066c739e](https://linux-hardware.org/?probe=d6066c739e) | Jan 28, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| Dell          | 05MW5F A00                  | Mini pc     | [dd56d67fef](https://linux-hardware.org/?probe=dd56d67fef) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | Notebook    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [24fd7df5b6](https://linux-hardware.org/?probe=24fd7df5b6) | Jan 28, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9ba078f6ab](https://linux-hardware.org/?probe=9ba078f6ab) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [376c580dcb](https://linux-hardware.org/?probe=376c580dcb) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [4a83dc2dc2](https://linux-hardware.org/?probe=4a83dc2dc2) | Jan 27, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [d5bbfc18d5](https://linux-hardware.org/?probe=d5bbfc18d5) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [e01e49f162](https://linux-hardware.org/?probe=e01e49f162) | Jan 27, 2023 |
| MSI           | Creator 17 B11UE            | Notebook    | [fcf56cfe4d](https://linux-hardware.org/?probe=fcf56cfe4d) | Jan 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | Notebook    | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| Google        | Careena                     | Notebook    | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| AZW           | MINI S                      | Desktop     | [ce5e6b1504](https://linux-hardware.org/?probe=ce5e6b1504) | Jan 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d632bd0c9f](https://linux-hardware.org/?probe=d632bd0c9f) | Jan 26, 2023 |
| HP            | 805D                        | Desktop     | [b1996094a9](https://linux-hardware.org/?probe=b1996094a9) | Jan 26, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [dee0143024](https://linux-hardware.org/?probe=dee0143024) | Jan 25, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [4643f751cf](https://linux-hardware.org/?probe=4643f751cf) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [90d383c54e](https://linux-hardware.org/?probe=90d383c54e) | Jan 25, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [e4b50b33a2](https://linux-hardware.org/?probe=e4b50b33a2) | Jan 25, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [e0eefbde94](https://linux-hardware.org/?probe=e0eefbde94) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| Panasonic     | FZ55-2                      | Notebook    | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [cc41fa5174](https://linux-hardware.org/?probe=cc41fa5174) | Jan 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8780aceeec](https://linux-hardware.org/?probe=8780aceeec) | Jan 25, 2023 |
| Samsung       | R710                        | Notebook    | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| Dell          | 0K3CM7 A00                  | Desktop     | [d3cc219bf7](https://linux-hardware.org/?probe=d3cc219bf7) | Jan 24, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| Packard Be... | EasyNote MH36               | Notebook    | [07ba548a55](https://linux-hardware.org/?probe=07ba548a55) | Jan 24, 2023 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [9ac0bac56e](https://linux-hardware.org/?probe=9ac0bac56e) | Jan 24, 2023 |
| ECS           | G31T-M9                     | Desktop     | [59747c81ca](https://linux-hardware.org/?probe=59747c81ca) | Jan 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [fe1a2d7fc6](https://linux-hardware.org/?probe=fe1a2d7fc6) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [b6bd3a3bdb](https://linux-hardware.org/?probe=b6bd3a3bdb) | Jan 23, 2023 |
| MSI           | 870A-G54                    | Desktop     | [b1baf04990](https://linux-hardware.org/?probe=b1baf04990) | Jan 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [5648fbf4a0](https://linux-hardware.org/?probe=5648fbf4a0) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [3f3b6c888d](https://linux-hardware.org/?probe=3f3b6c888d) | Jan 23, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [69164f2a61](https://linux-hardware.org/?probe=69164f2a61) | Jan 23, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7f0c7e0be](https://linux-hardware.org/?probe=e7f0c7e0be) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [5c7625e3f8](https://linux-hardware.org/?probe=5c7625e3f8) | Jan 23, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [c088868f62](https://linux-hardware.org/?probe=c088868f62) | Jan 22, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [ff727a3560](https://linux-hardware.org/?probe=ff727a3560) | Jan 22, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [df0676ac87](https://linux-hardware.org/?probe=df0676ac87) | Jan 22, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| Intel         | JSL MRD                     | Desktop     | [39dc5a7f96](https://linux-hardware.org/?probe=39dc5a7f96) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M57e 7066W57    | Desktop     | [3ddcdbb616](https://linux-hardware.org/?probe=3ddcdbb616) | Jan 22, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7afed6351](https://linux-hardware.org/?probe=e7afed6351) | Jan 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Danew         | Dbook 131                   | Notebook    | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| Clevo         | W150ER                      | Notebook    | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| Biostar       | H310MHP                     | Desktop     | [21de314a44](https://linux-hardware.org/?probe=21de314a44) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7f94d5172](https://linux-hardware.org/?probe=e7f94d5172) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [046504c970](https://linux-hardware.org/?probe=046504c970) | Jan 21, 2023 |
| DFI           | CR101-CST                   | Desktop     | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| Google        | Phaser                      | Notebook    | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [82b95a8f4e](https://linux-hardware.org/?probe=82b95a8f4e) | Jan 21, 2023 |
| Dell          | 00TD00 A00                  | All in one  | [8d09088848](https://linux-hardware.org/?probe=8d09088848) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [9f700f7e19](https://linux-hardware.org/?probe=9f700f7e19) | Jan 21, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [4af2ea2f7f](https://linux-hardware.org/?probe=4af2ea2f7f) | Jan 20, 2023 |
| Dell          | 0VC8RJ X02                  | Desktop     | [313ea92e9c](https://linux-hardware.org/?probe=313ea92e9c) | Jan 20, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [5767b63675](https://linux-hardware.org/?probe=5767b63675) | Jan 20, 2023 |
| Dell          | Latitude 5501               | Notebook    | [d31f972a20](https://linux-hardware.org/?probe=d31f972a20) | Jan 20, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [c591d80181](https://linux-hardware.org/?probe=c591d80181) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [28e6aeb27a](https://linux-hardware.org/?probe=28e6aeb27a) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [beec5d3864](https://linux-hardware.org/?probe=beec5d3864) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [6ff84d12be](https://linux-hardware.org/?probe=6ff84d12be) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [002a38370c](https://linux-hardware.org/?probe=002a38370c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [bbfb85788c](https://linux-hardware.org/?probe=bbfb85788c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [9d6c73b1c1](https://linux-hardware.org/?probe=9d6c73b1c1) | Jan 20, 2023 |
| HP            | 3397                        | Desktop     | [39391f23c4](https://linux-hardware.org/?probe=39391f23c4) | Jan 20, 2023 |
| HP            | 3397                        | Desktop     | [7b05c1fdf9](https://linux-hardware.org/?probe=7b05c1fdf9) | Jan 20, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b2c0017481](https://linux-hardware.org/?probe=b2c0017481) | Jan 20, 2023 |
| AZW           | SEi                         | Desktop     | [257b104c3a](https://linux-hardware.org/?probe=257b104c3a) | Jan 20, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d77bf1f32b](https://linux-hardware.org/?probe=d77bf1f32b) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [f7cac38f4a](https://linux-hardware.org/?probe=f7cac38f4a) | Jan 20, 2023 |
| AZW           | SEi                         | Desktop     | [481932390b](https://linux-hardware.org/?probe=481932390b) | Jan 20, 2023 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [b9f1f115ba](https://linux-hardware.org/?probe=b9f1f115ba) | Jan 20, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3447d19b00](https://linux-hardware.org/?probe=3447d19b00) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | Notebook    | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3SX0... | Notebook    | [3e08ab25c6](https://linux-hardware.org/?probe=3e08ab25c6) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [abcfca9ea7](https://linux-hardware.org/?probe=abcfca9ea7) | Jan 20, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 964       | 14.73%  |
| 5.10.0-7-amd64         | 691       | 10.56%  |
| 5.10.0-10-amd64        | 574       | 8.77%   |
| 5.10.0-16-amd64        | 370       | 5.65%   |
| 5.10.0-9-amd64         | 325       | 4.97%   |
| 5.10.0-20-amd64        | 315       | 4.81%   |
| 5.10.0-21-amd64        | 314       | 4.8%    |
| 5.10.0-19-amd64        | 287       | 4.39%   |
| 5.10.0-18-amd64        | 286       | 4.37%   |
| 5.10.0-13-amd64        | 262       | 4%      |
| 5.10.0-11-amd64        | 193       | 2.95%   |
| 5.10.0-2-amd64         | 158       | 2.41%   |
| 5.10.0-14-amd64        | 140       | 2.14%   |
| 5.10.0-17-amd64        | 126       | 1.93%   |
| 5.10.0-15-amd64        | 98        | 1.5%    |
| 5.10.0-12-amd64        | 73        | 1.12%   |
| 5.10.0-6-amd64         | 46        | 0.7%    |
| 6.0.0-0.deb11.6-amd64  | 41        | 0.63%   |
| 5.18.0-0.deb11.4-amd64 | 38        | 0.58%   |
| 5.15.0-2-amd64         | 38        | 0.58%   |
| 5.16.0-0.bpo.4-amd64   | 35        | 0.53%   |
| 5.10.0-13-686-pae      | 30        | 0.46%   |
| 6.0.0-0.deb11.2-amd64  | 28        | 0.43%   |
| 5.18.0-0.bpo.1-amd64   | 25        | 0.38%   |
| 5.14.0-0.bpo.2-amd64   | 25        | 0.38%   |
| 5.19.0-0.deb11.2-amd64 | 24        | 0.37%   |
| 5.15.74-1-pve          | 24        | 0.37%   |
| 5.13.19-6-pve          | 24        | 0.37%   |
| 5.15.85-1-pve          | 20        | 0.31%   |
| 5.10.0-8-arm64         | 18        | 0.28%   |
| 5.15.83-1-pve          | 17        | 0.26%   |
| 5.15.32-v8+            | 17        | 0.26%   |
| 5.15.30-2-pve          | 17        | 0.26%   |
| 5.19.0-2-amd64         | 16        | 0.24%   |
| 5.13.19-2-pve          | 16        | 0.24%   |
| 5.15.84-v8+            | 15        | 0.23%   |
| 5.15.76-v8+            | 15        | 0.23%   |
| 5.10.0-3-amd64         | 15        | 0.23%   |
| 5.15.53-1-pve          | 14        | 0.21%   |
| 5.10.0-8-686-pae       | 14        | 0.21%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 4984      | 82.67%  |
| 5.18.0   | 92        | 1.53%   |
| 6.0.0    | 85        | 1.41%   |
| 5.15.0   | 78        | 1.29%   |
| 5.16.0   | 65        | 1.08%   |
| 5.13.19  | 59        | 0.98%   |
| 5.19.0   | 57        | 0.95%   |
| 5.14.0   | 42        | 0.7%    |
| 5.15.74  | 28        | 0.46%   |
| 5.11.22  | 26        | 0.43%   |
| 5.17.0   | 24        | 0.4%    |
| 5.15.85  | 20        | 0.33%   |
| 5.15.39  | 18        | 0.3%    |
| 5.15.32  | 18        | 0.3%    |
| 5.15.30  | 18        | 0.3%    |
| 5.15.83  | 17        | 0.28%   |
| 5.15.35  | 17        | 0.28%   |
| 5.15.84  | 16        | 0.27%   |
| 5.15.76  | 15        | 0.25%   |
| 5.10.92  | 15        | 0.25%   |
| 6.1.0    | 14        | 0.23%   |
| 5.15.53  | 14        | 0.23%   |
| 5.15.61  | 13        | 0.22%   |
| 4.19.0   | 11        | 0.18%   |
| 5.15.60  | 7         | 0.12%   |
| 5.13.0   | 7         | 0.12%   |
| 5.10.63  | 7         | 0.12%   |
| 5.10.60  | 6         | 0.1%    |
| 5.19.17  | 5         | 0.08%   |
| 5.10.109 | 5         | 0.08%   |
| 6.1.12   | 4         | 0.07%   |
| 6.0.8    | 4         | 0.07%   |
| 5.19.11  | 4         | 0.07%   |
| 5.16.5   | 4         | 0.07%   |
| 5.15.64  | 4         | 0.07%   |
| 5.15.102 | 4         | 0.07%   |
| 5.12.0   | 4         | 0.07%   |
| 5.11.0   | 4         | 0.07%   |
| 5.10.103 | 4         | 0.07%   |
| 5.10     | 4         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 5058      | 84.22%  |
| 5.15    | 317       | 5.28%   |
| 5.18    | 101       | 1.68%   |
| 6.0     | 94        | 1.57%   |
| 5.13    | 78        | 1.3%    |
| 5.19    | 76        | 1.27%   |
| 5.16    | 74        | 1.23%   |
| 5.14    | 49        | 0.82%   |
| 5.11    | 35        | 0.58%   |
| 5.17    | 34        | 0.57%   |
| 6.1     | 28        | 0.47%   |
| 4.19    | 13        | 0.22%   |
| 5.4     | 9         | 0.15%   |
| 5.12    | 9         | 0.15%   |
| 6.2     | 5         | 0.08%   |
| 5       | 5         | 0.08%   |
| 4.4     | 4         | 0.07%   |
| 5.9     | 3         | 0.05%   |
| 5.1     | 3         | 0.05%   |
| 4.9     | 2         | 0.03%   |
| 3.18    | 2         | 0.03%   |
| 6.3     | 1         | 0.02%   |
| 5.8     | 1         | 0.02%   |
| 5.5     | 1         | 0.02%   |
| 5.15.6  | 1         | 0.02%   |
| 4.14    | 1         | 0.02%   |
| 3.8     | 1         | 0.02%   |
| 3.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5526      | 93.77%  |
| i686    | 176       | 2.99%   |
| aarch64 | 156       | 2.65%   |
| armv7l  | 29        | 0.49%   |
| riscv64 | 5         | 0.08%   |
| i586    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 2317      | 38.75%  |
| GNOME             | 1295      | 21.66%  |
| KDE5              | 653       | 10.92%  |
| XFCE              | 639       | 10.69%  |
| MATE              | 207       | 3.46%   |
| LXDE              | 182       | 3.04%   |
| X-Cinnamon        | 178       | 2.98%   |
| Cinnamon          | 144       | 2.41%   |
| LXQt              | 73        | 1.22%   |
| i3                | 67        | 1.12%   |
| KDE               | 47        | 0.79%   |
| Openbox           | 38        | 0.64%   |
| GNOME Flashback   | 36        | 0.6%    |
| lightdm-xsession  | 26        | 0.43%   |
| Trinity           | 19        | 0.32%   |
| Budgie            | 10        | 0.17%   |
| GNOME Classic     | 9         | 0.15%   |
| sway              | 5         | 0.08%   |
| awesome           | 5         | 0.08%   |
| x-session-manager | 3         | 0.05%   |
| Enlightenment     | 3         | 0.05%   |
| DWM               | 3         | 0.05%   |
| Cutefish          | 3         | 0.05%   |
| ICEWM             | 2         | 0.03%   |
| xmonad            | 1         | 0.02%   |
| wmaker-common     | 1         | 0.02%   |
| UKUI              | 1         | 0.02%   |
| Phosh:GNOME       | 1         | 0.02%   |
| matchbox          | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| gnome-xorg        | 1         | 0.02%   |
| fvwm              | 1         | 0.02%   |
| fluxbox           | 1         | 0.02%   |
| e16-session       | 1         | 0.02%   |
| default           | 1         | 0.02%   |
| Deepin            | 1         | 0.02%   |
| BunsenLabs        | 1         | 0.02%   |
| /etc/X11/Xsession | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 2649      | 44.38%  |
| Unknown     | 1784      | 29.89%  |
| Wayland     | 866       | 14.51%  |
| Tty         | 666       | 11.16%  |
| Web         | 2         | 0.03%   |
| Unspecified | 2         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2933      | 49.23%  |
| LightDM | 1098      | 18.43%  |
| GDM     | 1043      | 17.51%  |
| SDDM    | 581       | 9.75%   |
| TDM     | 155       | 2.6%    |
| GDM3    | 107       | 1.8%    |
| XDM     | 13        | 0.22%   |
| SLiM    | 12        | 0.2%    |
| LXDM    | 8         | 0.13%   |
| NODM    | 5         | 0.08%   |
| Ly      | 2         | 0.03%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1904      | 32%     |
| Unknown | 924       | 15.53%  |
| ru_RU   | 923       | 15.51%  |
| de_DE   | 328       | 5.51%   |
| en_GB   | 281       | 4.72%   |
| fr_FR   | 271       | 4.55%   |
| es_ES   | 173       | 2.91%   |
| it_IT   | 137       | 2.3%    |
| pt_BR   | 120       | 2.02%   |
| pl_PL   | 91        | 1.53%   |
| C       | 71        | 1.19%   |
| en_CA   | 66        | 1.11%   |
| en_AU   | 65        | 1.09%   |
| es_MX   | 42        | 0.71%   |
| zh_CN   | 34        | 0.57%   |
| es_AR   | 31        | 0.52%   |
| hu_HU   | 28        | 0.47%   |
| es_VE   | 27        | 0.45%   |
| en_IN   | 25        | 0.42%   |
| ja_JP   | 23        | 0.39%   |
| en_IE   | 23        | 0.39%   |
| de_CH   | 21        | 0.35%   |
| de_AT   | 19        | 0.32%   |
| pt_PT   | 16        | 0.27%   |
| nl_NL   | 16        | 0.27%   |
| fi_FI   | 14        | 0.24%   |
| en_NZ   | 14        | 0.24%   |
| sv_SE   | 13        | 0.22%   |
| es_CL   | 13        | 0.22%   |
| cs_CZ   | 11        | 0.18%   |
| nl_BE   | 10        | 0.17%   |
| fr_BE   | 10        | 0.17%   |
| es_CO   | 10        | 0.17%   |
| en_ZA   | 10        | 0.17%   |
| uk_UA   | 9         | 0.15%   |
| tr_TR   | 9         | 0.15%   |
| en_SG   | 9         | 0.15%   |
| es_PE   | 8         | 0.13%   |
| zh_TW   | 7         | 0.12%   |
| nb_NO   | 7         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3420      | 57.45%  |
| BIOS | 2533      | 42.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3718      | 62.87%  |
| Overlay | 1833      | 30.99%  |
| Btrfs   | 172       | 2.91%   |
| Zfs     | 89        | 1.5%    |
| Xfs     | 60        | 1.01%   |
| Ext3    | 14        | 0.24%   |
| Tmpfs   | 12        | 0.2%    |
| Unknown | 7         | 0.12%   |
| Ext2    | 6         | 0.1%    |
| Rootfs  | 2         | 0.03%   |
| Aufs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3551      | 59.58%  |
| MBR     | 1640      | 27.52%  |
| Unknown | 769       | 12.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4812      | 81.02%  |
| Yes       | 1127      | 18.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4095      | 68.9%   |
| Yes       | 1848      | 31.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 855       | 14.51%  |
| Lenovo                  | 839       | 14.24%  |
| Apple                   | 667       | 11.32%  |
| Hewlett-Packard         | 619       | 10.51%  |
| Dell                    | 563       | 9.56%   |
| Gigabyte Technology     | 378       | 6.42%   |
| MSI                     | 273       | 4.63%   |
| ASRock                  | 208       | 3.53%   |
| Acer                    | 200       | 3.4%    |
| Google                  | 136       | 2.31%   |
| Intel                   | 132       | 2.24%   |
| Raspberry Pi Foundation | 115       | 1.95%   |
| Unknown                 | 80        | 1.36%   |
| Supermicro              | 57        | 0.97%   |
| ECS                     | 48        | 0.81%   |
| Aquarius                | 47        | 0.8%    |
| Samsung Electronics     | 42        | 0.71%   |
| Toshiba                 | 41        | 0.7%    |
| Fujitsu                 | 40        | 0.68%   |
| HUAWEI                  | 27        | 0.46%   |
| Foxconn                 | 27        | 0.46%   |
| ASRockRack              | 25        | 0.42%   |
| AZW                     | 23        | 0.39%   |
| Sony                    | 18        | 0.31%   |
| Notebook                | 17        | 0.29%   |
| Pegatron                | 14        | 0.24%   |
| Packard Bell            | 13        | 0.22%   |
| Medion                  | 12        | 0.2%    |
| Biostar                 | 11        | 0.19%   |
| Microsoft               | 10        | 0.17%   |
| Hardkernel              | 10        | 0.17%   |
| Panasonic               | 9         | 0.15%   |
| IBM                     | 9         | 0.15%   |
| AMI                     | 9         | 0.15%   |
| Xunlong                 | 8         | 0.14%   |
| sunxi                   | 8         | 0.14%   |
| Positivo                | 8         | 0.14%   |
| Fujitsu Siemens         | 8         | 0.14%   |
| BESSTAR Tech            | 8         | 0.14%   |
| ZOTAC                   | 7         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 353       | 5.99%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 114       | 1.94%   |
| Unknown                                   | 90        | 1.53%   |
| Apple MacBookAir7,1                       | 77        | 1.31%   |
| Apple MacBookAir7,2                       | 76        | 1.29%   |
| Google Enguarde                           | 74        | 1.26%   |
| ASUS All Series                           | 73        | 1.24%   |
| ASUS S20 K29                              | 55        | 0.93%   |
| Apple MacBook2,1                          | 55        | 0.93%   |
| Aquarius NS585                            | 44        | 0.75%   |
| MSI MS-7996                               | 38        | 0.65%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 24        | 0.41%   |
| Lenovo ThinkPad E475 20H40006US           | 24        | 0.41%   |
| Google Terra                              | 23        | 0.39%   |
| ECS G31T-M9                               | 22        | 0.37%   |
| Apple MacBook4,1                          | 21        | 0.36%   |
| MSI MS-7817                               | 20        | 0.34%   |
| ASRock H470M-HVS                          | 20        | 0.34%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 19        | 0.32%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 18        | 0.31%   |
| Gigabyte H81M-S2V                         | 18        | 0.31%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 17        | 0.29%   |
| ASUS PRIME H510M-A                        | 17        | 0.29%   |
| Supermicro Super Server                   | 16        | 0.27%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.27%   |
| Gigabyte H410M S2H                        | 16        | 0.27%   |
| ECS H61H2-M13                             | 16        | 0.27%   |
| HP Notebook                               | 15        | 0.25%   |
| ASUS P8H61-M LX3 R2.0                     | 15        | 0.25%   |
| Acer Aspire A315-23                       | 15        | 0.25%   |
| ASUS 1005HA                               | 14        | 0.24%   |
| Dell OptiPlex 7010                        | 13        | 0.22%   |
| HP Pavilion g6                            | 12        | 0.2%    |
| Google Reks                               | 11        | 0.19%   |
| Gigabyte B450M DS3H                       | 10        | 0.17%   |
| ASUS PRIME B450M-A                        | 10        | 0.17%   |
| ASUS H110M-R                              | 10        | 0.17%   |
| HP EliteBook 8460p                        | 9         | 0.15%   |
| Dell Latitude E7440                       | 9         | 0.15%   |
| ASUS P8H67-M                              | 9         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 536       | 9.1%    |
| Apple MacBook5     | 353       | 5.99%   |
| Apple MacBookAir7  | 153       | 2.6%    |
| Dell Latitude      | 152       | 2.58%   |
| Acer Aspire        | 129       | 2.19%   |
| Dell Inspiron      | 128       | 2.17%   |
| RPi Raspberry      | 115       | 1.95%   |
| ASUS PRIME         | 112       | 1.9%    |
| Lenovo IdeaPad     | 98        | 1.66%   |
| Unknown            | 90        | 1.53%   |
| HP EliteBook       | 88        | 1.49%   |
| Dell OptiPlex      | 79        | 1.34%   |
| HP Pavilion        | 76        | 1.29%   |
| Google Enguarde    | 74        | 1.26%   |
| ASUS All           | 73        | 1.24%   |
| HP Compaq          | 65        | 1.1%    |
| HP Laptop          | 61        | 1.04%   |
| Dell Precision     | 60        | 1.02%   |
| ASUS S20           | 55        | 0.93%   |
| Apple MacBook2     | 55        | 0.93%   |
| HP ProBook         | 53        | 0.9%    |
| Lenovo ThinkCentre | 51        | 0.87%   |
| Dell XPS           | 49        | 0.83%   |
| ASUS ROG           | 49        | 0.83%   |
| Aquarius NS585     | 44        | 0.75%   |
| ASUS TUF           | 43        | 0.73%   |
| ASUS VivoBook      | 40        | 0.68%   |
| MSI MS-7996        | 38        | 0.65%   |
| Dell Vostro        | 37        | 0.63%   |
| Dell PowerEdge     | 35        | 0.59%   |
| Toshiba Satellite  | 34        | 0.58%   |
| HP ProLiant        | 34        | 0.58%   |
| ASUS P8H61-M       | 31        | 0.53%   |
| Gigabyte B450M     | 24        | 0.41%   |
| HP ZBook           | 23        | 0.39%   |
| Google Terra       | 23        | 0.39%   |
| ASUS ZenBook       | 23        | 0.39%   |
| ECS G31T-M9        | 22        | 0.37%   |
| ASUS ASUS          | 22        | 0.37%   |
| HP ENVY            | 21        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 710       | 12.05%  |
| 2009    | 546       | 9.27%   |
| 2021    | 543       | 9.22%   |
| 2019    | 456       | 7.74%   |
| 2018    | 405       | 6.87%   |
| 2012    | 403       | 6.84%   |
| 2013    | 333       | 5.65%   |
| 2015    | 326       | 5.53%   |
| 2016    | 307       | 5.21%   |
| 2011    | 302       | 5.13%   |
| 2017    | 291       | 4.94%   |
| 2014    | 245       | 4.16%   |
| 2022    | 232       | 3.94%   |
| 2010    | 195       | 3.31%   |
| Unknown | 166       | 2.82%   |
| 2008    | 164       | 2.78%   |
| 2007    | 153       | 2.6%    |
| 2006    | 46        | 0.78%   |
| 2005    | 34        | 0.58%   |
| 2003    | 14        | 0.24%   |
| 2004    | 8         | 0.14%   |
| 2023    | 7         | 0.12%   |
| 2001    | 3         | 0.05%   |
| 2002    | 1         | 0.02%   |
| 2000    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3053      | 51.82%  |
| Desktop        | 2152      | 36.53%  |
| Convertible    | 187       | 3.17%   |
| System on chip | 174       | 2.95%   |
| Mini pc        | 130       | 2.21%   |
| Server         | 114       | 1.94%   |
| All in one     | 45        | 0.76%   |
| Tablet         | 31        | 0.53%   |
| Phone          | 4         | 0.07%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5591      | 94.51%  |
| Enabled  | 325       | 5.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5744      | 97.49%  |
| Yes  | 148       | 2.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1354      | 22.81%  |
| 3.01-4.0        | 1087      | 18.31%  |
| 16.01-24.0      | 1061      | 17.87%  |
| 8.01-16.0       | 737       | 12.41%  |
| 1.01-2.0        | 621       | 10.46%  |
| 32.01-64.0      | 461       | 7.76%   |
| 64.01-256.0     | 266       | 4.48%   |
| 2.01-3.0        | 113       | 1.9%    |
| 0.51-1.0        | 107       | 1.8%    |
| 24.01-32.0      | 82        | 1.38%   |
| 0.01-0.5        | 28        | 0.47%   |
| More than 256.0 | 19        | 0.32%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 2139      | 34.52%  |
| 0.51-1.0        | 1156      | 18.66%  |
| 2.01-3.0        | 1023      | 16.51%  |
| 4.01-8.0        | 679       | 10.96%  |
| 3.01-4.0        | 530       | 8.55%   |
| 0.01-0.5        | 290       | 4.68%   |
| 8.01-16.0       | 222       | 3.58%   |
| 16.01-24.0      | 67        | 1.08%   |
| 32.01-64.0      | 44        | 0.71%   |
| 24.01-32.0      | 27        | 0.44%   |
| 64.01-256.0     | 16        | 0.26%   |
| Unknown         | 2         | 0.03%   |
| More than 256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 4098      | 68.55%  |
| 2      | 1059      | 17.71%  |
| 3      | 328       | 5.49%   |
| 4      | 201       | 3.36%   |
| 5      | 89        | 1.49%   |
| 6      | 48        | 0.8%    |
| 0      | 45        | 0.75%   |
| 7      | 32        | 0.54%   |
| 8      | 30        | 0.5%    |
| 13     | 10        | 0.17%   |
| 10     | 9         | 0.15%   |
| 9      | 8         | 0.13%   |
| 12     | 5         | 0.08%   |
| 14     | 4         | 0.07%   |
| 11     | 3         | 0.05%   |
| 28     | 2         | 0.03%   |
| 29     | 1         | 0.02%   |
| 27     | 1         | 0.02%   |
| 26     | 1         | 0.02%   |
| 22     | 1         | 0.02%   |
| 21     | 1         | 0.02%   |
| 18     | 1         | 0.02%   |
| 16     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4004      | 67.74%  |
| Yes       | 1907      | 32.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5067      | 85.9%   |
| No        | 832       | 14.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3992      | 67.58%  |
| No        | 1915      | 32.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3349      | 56.6%   |
| No        | 2568      | 43.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1618      | 27.41%  |
| Russia       | 971       | 16.45%  |
| Germany      | 517       | 8.76%   |
| France       | 349       | 5.91%   |
| Spain        | 223       | 3.78%   |
| Italy        | 183       | 3.1%    |
| Brazil       | 166       | 2.81%   |
| UK           | 152       | 2.57%   |
| Poland       | 137       | 2.32%   |
| Canada       | 116       | 1.96%   |
| Netherlands  | 90        | 1.52%   |
| Australia    | 87        | 1.47%   |
| Switzerland  | 82        | 1.39%   |
| Mexico       | 68        | 1.15%   |
| China        | 62        | 1.05%   |
| Argentina    | 52        | 0.88%   |
| Sweden       | 49        | 0.83%   |
| Ukraine      | 46        | 0.78%   |
| Hungary      | 46        | 0.78%   |
| Austria      | 45        | 0.76%   |
| Belgium      | 44        | 0.75%   |
| Portugal     | 37        | 0.63%   |
| Finland      | 37        | 0.63%   |
| India        | 36        | 0.61%   |
| Turkey       | 33        | 0.56%   |
| Czechia      | 33        | 0.56%   |
| Norway       | 32        | 0.54%   |
| Venezuela    | 31        | 0.53%   |
| Japan        | 30        | 0.51%   |
| Romania      | 27        | 0.46%   |
| Bulgaria     | 27        | 0.46%   |
| Ireland      | 20        | 0.34%   |
| Greece       | 20        | 0.34%   |
| New Zealand  | 19        | 0.32%   |
| Croatia      | 19        | 0.32%   |
| Colombia     | 19        | 0.32%   |
| Chile        | 18        | 0.3%    |
| Denmark      | 17        | 0.29%   |
| Taiwan       | 16        | 0.27%   |
| South Africa | 16        | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangor            | 750       | 12.19%  |
| Voronezh          | 715       | 11.62%  |
| Dover-Foxcroft    | 305       | 4.96%   |
| Moscow            | 56        | 0.91%   |
| Paris             | 54        | 0.88%   |
| Seville           | 51        | 0.83%   |
| St Petersburg     | 48        | 0.78%   |
| Berlin            | 41        | 0.67%   |
| Vienna            | 35        | 0.57%   |
| Madrid            | 35        | 0.57%   |
| Warsaw            | 30        | 0.49%   |
| Munich            | 29        | 0.47%   |
| Barcelona         | 29        | 0.47%   |
| Zurich            | 28        | 0.46%   |
| Milan             | 27        | 0.44%   |
| Amsterdam         | 27        | 0.44%   |
| Sao Paulo         | 23        | 0.37%   |
| London            | 22        | 0.36%   |
| Toronto           | 21        | 0.34%   |
| Sydney            | 21        | 0.34%   |
| Falkenstein       | 21        | 0.34%   |
| Frankfurt am Main | 19        | 0.31%   |
| Perm              | 18        | 0.29%   |
| Helsinki          | 18        | 0.29%   |
| Hamburg           | 18        | 0.29%   |
| Brisbane          | 17        | 0.28%   |
| Melbourne         | 16        | 0.26%   |
| Stuttgart         | 14        | 0.23%   |
| San Jose          | 14        | 0.23%   |
| Prague            | 14        | 0.23%   |
| Leipzig           | 14        | 0.23%   |
| Istanbul          | 14        | 0.23%   |
| Cologne           | 14        | 0.23%   |
| Budapest          | 14        | 0.23%   |
| Zagreb            | 13        | 0.21%   |
| Lyon              | 13        | 0.21%   |
| Chicago           | 13        | 0.21%   |
| Caracas           | 13        | 0.21%   |
| Buenos Aires      | 13        | 0.21%   |
| Blizniew          | 13        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1201      | 1750   | 14.95%  |
| WDC                 | 1051      | 1663   | 13.08%  |
| Seagate             | 1013      | 1714   | 12.61%  |
| Toshiba             | 569       | 827    | 7.08%   |
| Kingston            | 494       | 619    | 6.15%   |
| Unknown             | 454       | 580    | 5.65%   |
| Crucial             | 374       | 449    | 4.65%   |
| SanDisk             | 312       | 390    | 3.88%   |
| Fujitsu             | 282       | 290    | 3.51%   |
| Hitachi             | 243       | 319    | 3.02%   |
| Apple               | 188       | 222    | 2.34%   |
| Intel               | 186       | 248    | 2.31%   |
| SK hynix            | 160       | 195    | 1.99%   |
| A-DATA Technology   | 147       | 251    | 1.83%   |
| HGST                | 115       | 179    | 1.43%   |
| Micron Technology   | 106       | 128    | 1.32%   |
| China               | 85        | 100    | 1.06%   |
| Unknown             | 57        | 59     | 0.71%   |
| SPCC                | 52        | 59     | 0.65%   |
| KIOXIA              | 51        | 57     | 0.63%   |
| PNY                 | 45        | 76     | 0.56%   |
| Transcend           | 40        | 47     | 0.5%    |
| Phison              | 39        | 50     | 0.49%   |
| Intenso             | 33        | 42     | 0.41%   |
| Netac               | 32        | 92     | 0.4%    |
| LITEON              | 31        | 36     | 0.39%   |
| JMicron Technology  | 28        | 28     | 0.35%   |
| SABRENT             | 27        | 28     | 0.34%   |
| Corsair             | 26        | 45     | 0.32%   |
| Patriot             | 25        | 28     | 0.31%   |
| GOODRAM             | 25        | 41     | 0.31%   |
| Silicon Motion      | 22        | 27     | 0.27%   |
| OCZ                 | 21        | 25     | 0.26%   |
| Maxtor              | 21        | 26     | 0.26%   |
| Hewlett-Packard     | 21        | 39     | 0.26%   |
| LITEONIT            | 18        | 22     | 0.22%   |
| Gigabyte Technology | 17        | 19     | 0.21%   |
| Team                | 16        | 30     | 0.2%    |
| Apacer              | 15        | 15     | 0.19%   |
| ASMT                | 14        | 16     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 237       | 2.69%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 122       | 1.39%   |
| Kingston SA400S37240G 240GB SSD    | 113       | 1.28%   |
| Seagate ST500DM002-1BD142 500GB    | 81        | 0.92%   |
| Apple SSD AP0128H 121GB            | 77        | 0.88%   |
| Crucial CT480BX500SSD1 480GB       | 75        | 0.85%   |
| Apple SSD SM0128G 121GB            | 71        | 0.81%   |
| Kingston SA400S37120G 120GB SSD    | 61        | 0.69%   |
| Kingston SV300S37A120G 120GB SSD   | 59        | 0.67%   |
| Toshiba DT01ACA050 500GB           | 58        | 0.66%   |
| Unknown                            | 57        | 0.65%   |
| Samsung SSD 860 EVO 250GB          | 54        | 0.61%   |
| Toshiba MK1655GSXF 160GB           | 53        | 0.6%    |
| Samsung SSD 860 EVO 500GB          | 53        | 0.6%    |
| Kingston SA400S37480G 480GB SSD    | 53        | 0.6%    |
| Seagate ST1000LM035-1RK172 1TB     | 48        | 0.55%   |
| A-DATA SU800 512GB SSD             | 48        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB     | 47        | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB       | 46        | 0.52%   |
| Crucial CT500MX500SSD1 500GB       | 45        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB        | 45        | 0.51%   |
| Toshiba MK1653GSX 160GB            | 43        | 0.49%   |
| Samsung SSD 860 EVO 1TB            | 40        | 0.45%   |
| Unknown AGND3R  16GB               | 39        | 0.44%   |
| Unknown MMC Card  32GB             | 38        | 0.43%   |
| Samsung SSD 850 EVO 250GB          | 37        | 0.42%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 36        | 0.41%   |
| Toshiba DT01ACA100 1TB             | 36        | 0.41%   |
| Samsung SSD 970 EVO Plus 500GB     | 36        | 0.41%   |
| Crucial CT240BX500SSD1 240GB       | 36        | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 35        | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB           | 31        | 0.35%   |
| Hitachi HDS721050CLA362 500GB      | 31        | 0.35%   |
| Unknown HAG2e  16GB                | 30        | 0.34%   |
| Toshiba HDWD110 1TB                | 30        | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB     | 30        | 0.34%   |
| Samsung SSD 870 EVO 500GB          | 29        | 0.33%   |
| Samsung SSD 850 EVO 500GB          | 29        | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB     | 27        | 0.31%   |
| SABRENT Disk 160GB                 | 27        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 986       | 1660   | 31.78%  |
| WDC                 | 783       | 1287   | 25.23%  |
| Toshiba             | 477       | 711    | 15.37%  |
| Fujitsu             | 282       | 290    | 9.09%   |
| Hitachi             | 243       | 319    | 7.83%   |
| HGST                | 115       | 179    | 3.71%   |
| Samsung Electronics | 77        | 96     | 2.48%   |
| SABRENT             | 27        | 28     | 0.87%   |
| Unknown             | 25        | 34     | 0.81%   |
| Maxtor              | 19        | 21     | 0.61%   |
| ASMT                | 9         | 11     | 0.29%   |
| Apple               | 9         | 11     | 0.29%   |
| Intenso             | 5         | 5      | 0.16%   |
| Hewlett-Packard     | 5         | 14     | 0.16%   |
| ASMedia             | 5         | 5      | 0.16%   |
| USB3.0              | 4         | 4      | 0.13%   |
| JMicron Technology  | 3         | 3      | 0.1%    |
| QNAP                | 2         | 3      | 0.06%   |
| IBM/Hitachi         | 2         | 2      | 0.06%   |
| IBM-ESXS            | 2         | 4      | 0.06%   |
| HPE                 | 2         | 6      | 0.06%   |
| Unknown (CF)        | 1         | 1      | 0.03%   |
| TrueNAS             | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| SILICONMOTION       | 1         | 1      | 0.03%   |
| SD                  | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| pqi                 | 1         | 1      | 0.03%   |
| Pear 2TB            | 1         | 1      | 0.03%   |
| NAS                 | 1         | 5      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 4      | 0.03%   |
| MARSHAL             | 1         | 1      | 0.03%   |
| Hajaan              | 1         | 1      | 0.03%   |
| H/W                 | 1         | 3      | 0.03%   |
| China               | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |
| AMP                 | 1         | 1      | 0.03%   |
| Advantech           | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 550       | 742    | 20.61%  |
| Kingston            | 416       | 528    | 15.59%  |
| Crucial             | 332       | 393    | 12.44%  |
| SanDisk             | 212       | 265    | 7.94%   |
| WDC                 | 110       | 131    | 4.12%   |
| A-DATA Technology   | 110       | 190    | 4.12%   |
| Apple               | 94        | 101    | 3.52%   |
| China               | 83        | 98     | 3.11%   |
| Intel               | 79        | 110    | 2.96%   |
| Micron Technology   | 46        | 64     | 1.72%   |
| SPCC                | 42        | 46     | 1.57%   |
| Toshiba             | 37        | 45     | 1.39%   |
| Transcend           | 36        | 43     | 1.35%   |
| PNY                 | 34        | 62     | 1.27%   |
| Netac               | 32        | 92     | 1.2%    |
| SK hynix            | 31        | 40     | 1.16%   |
| LITEON              | 26        | 29     | 0.97%   |
| Intenso             | 25        | 32     | 0.94%   |
| Patriot             | 22        | 23     | 0.82%   |
| OCZ                 | 21        | 25     | 0.79%   |
| GOODRAM             | 20        | 27     | 0.75%   |
| LITEONIT            | 18        | 22     | 0.67%   |
| Team                | 14        | 27     | 0.52%   |
| JMicron Technology  | 14        | 14     | 0.52%   |
| Apacer              | 13        | 13     | 0.49%   |
| Unknown             | 12        | 13     | 0.45%   |
| Seagate             | 10        | 12     | 0.37%   |
| Gigabyte Technology | 10        | 10     | 0.37%   |
| Corsair             | 10        | 14     | 0.37%   |
| Hewlett-Packard     | 9         | 14     | 0.34%   |
| Plextor             | 8         | 11     | 0.3%    |
| KingDian            | 8         | 8      | 0.3%    |
| Unknown             | 7         | 10     | 0.26%   |
| Hajaan              | 7         | 8      | 0.26%   |
| Mushkin             | 6         | 7      | 0.22%   |
| Lexar               | 6         | 8      | 0.22%   |
| Xinhaike            | 5         | 8      | 0.19%   |
| LDLC                | 5         | 5      | 0.19%   |
| KIOXIA-EXCERIA      | 5         | 8      | 0.19%   |
| Dogfish             | 5         | 7      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2672      | 4726   | 36.51%  |
| SSD     | 2366      | 3465   | 32.33%  |
| NVMe    | 1717      | 2387   | 23.46%  |
| MMC     | 476       | 587    | 6.5%    |
| Unknown | 87        | 127    | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4195      | 7759   | 62.66%  |
| NVMe | 1712      | 2375   | 25.57%  |
| MMC  | 476       | 587    | 7.11%   |
| SAS  | 312       | 571    | 4.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| 0.01-0.5    | 3347      | 4690   | 63.1%   |
| 0.51-1.0    | 1184      | 1816   | 22.32%  |
| 1.01-2.0    | 350       | 617    | 6.6%    |
| 3.01-4.0    | 155       | 371    | 2.92%   |
| 4.01-10.0   | 153       | 389    | 2.88%   |
| 2.01-3.0    | 77        | 141    | 1.45%   |
| 10.01-20.0  | 36        | 162    | 0.68%   |
| 20.01-50.0  | 1         | 1      | 0.02%   |
| 50.01-100.0 | 1         | 4      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1448      | 23.97%  |
| 101-250        | 1302      | 21.55%  |
| 251-500        | 987       | 16.34%  |
| 501-1000       | 633       | 10.48%  |
| 51-100         | 352       | 5.83%   |
| 1-20           | 337       | 5.58%   |
| 1001-2000      | 328       | 5.43%   |
| More than 3000 | 283       | 4.68%   |
| 21-50          | 248       | 4.11%   |
| 2001-3000      | 123       | 2.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2204      | 35.81%  |
| Unknown        | 1448      | 23.53%  |
| 21-50          | 547       | 8.89%   |
| 101-250        | 547       | 8.89%   |
| 51-100         | 472       | 7.67%   |
| 251-500        | 337       | 5.48%   |
| 501-1000       | 259       | 4.21%   |
| 1001-2000      | 140       | 2.27%   |
| More than 3000 | 118       | 1.92%   |
| 2001-3000      | 61        | 0.99%   |
| 0              | 21        | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 25        | 25     | 2.94%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 21        | 25     | 2.47%   |
| Seagate ST500DM002-1BD142 500GB    | 20        | 28     | 2.35%   |
| Kingston SV300S37A120G 120GB SSD   | 20        | 20     | 2.35%   |
| Hitachi HTS543216L9SA02 160GB      | 11        | 11     | 1.29%   |
| Toshiba MK1655GSXF 160GB           | 9         | 9      | 1.06%   |
| Toshiba MK1653GSX 160GB            | 9         | 9      | 1.06%   |
| Seagate ST9500325AS 500GB          | 9         | 11     | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 9         | 10     | 1.06%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 8         | 8      | 0.94%   |
| Hitachi HDS721050CLA362 500GB      | 8         | 8      | 0.94%   |
| Seagate ST250DM000-1BD141 250GB    | 7         | 7      | 0.82%   |
| Toshiba DT01ACA050 500GB           | 6         | 7      | 0.71%   |
| Seagate ST9500420AS 500GB          | 6         | 6      | 0.71%   |
| Seagate ST3250318AS 250GB          | 6         | 6      | 0.71%   |
| Seagate ST1000DM003-9YN162 1TB     | 6         | 7      | 0.71%   |
| Hitachi HDS721050DLE630 500GB      | 6         | 11     | 0.71%   |
| WDC WD10EZEX-08WN4A0 1TB           | 5         | 5      | 0.59%   |
| Seagate ST500LM021-1KJ152 500GB    | 5         | 5      | 0.59%   |
| Seagate ST3500418AS 500GB          | 5         | 6      | 0.59%   |
| Seagate ST31500341AS 1TB           | 5         | 7      | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB     | 5         | 5      | 0.59%   |
| Hitachi HTS542512K9SA00 120GB      | 5         | 6      | 0.59%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 4         | 4      | 0.47%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 4         | 5      | 0.47%   |
| WDC WD20EARX-00PASB0 2TB           | 4         | 4      | 0.47%   |
| WDC WD20EARS-00MVWB0 2TB           | 4         | 4      | 0.47%   |
| WDC WD1600BUDT-63DPZY0 160GB       | 4         | 4      | 0.47%   |
| Toshiba MQ01ABD100 1TB             | 4         | 4      | 0.47%   |
| Seagate ST500LT012-9WS142 500GB    | 4         | 4      | 0.47%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 4      | 0.47%   |
| Seagate ST3500413AS 500GB          | 4         | 5      | 0.47%   |
| Seagate ST3320613AS 320GB          | 4         | 4      | 0.47%   |
| Seagate ST31000528AS 1TB           | 4         | 4      | 0.47%   |
| Seagate ST1000DM003-1CH162 1TB     | 4         | 4      | 0.47%   |
| Hitachi HTS547575A9E384 752GB      | 4         | 4      | 0.47%   |
| Hitachi HTS545050B9A300 500GB      | 4         | 4      | 0.47%   |
| HGST HTS725050A7E630 500GB         | 4         | 5      | 0.47%   |
| HGST HTS541010A9E680 1TB           | 4         | 4      | 0.47%   |
| WDC WD5000AAKX-001CA0 500GB        | 3         | 3      | 0.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 222       | 287    | 26.78%  |
| WDC                 | 180       | 222    | 21.71%  |
| Hitachi             | 89        | 107    | 10.74%  |
| Toshiba             | 60        | 63     | 7.24%   |
| Samsung Electronics | 48        | 51     | 5.79%   |
| Kingston            | 40        | 45     | 4.83%   |
| Fujitsu             | 34        | 35     | 4.1%    |
| Intel               | 31        | 37     | 3.74%   |
| HGST                | 19        | 21     | 2.29%   |
| SK hynix            | 16        | 19     | 1.93%   |
| Crucial             | 13        | 17     | 1.57%   |
| SanDisk             | 12        | 13     | 1.45%   |
| Micron Technology   | 12        | 17     | 1.45%   |
| A-DATA Technology   | 12        | 15     | 1.45%   |
| Maxtor              | 7         | 7      | 0.84%   |
| LITEONIT            | 4         | 5      | 0.48%   |
| LITEON              | 3         | 3      | 0.36%   |
| China               | 3         | 3      | 0.36%   |
| PNY                 | 2         | 7      | 0.24%   |
| OCZ                 | 2         | 2      | 0.24%   |
| Hewlett-Packard     | 2         | 3      | 0.24%   |
| Apacer              | 2         | 2      | 0.24%   |
| Unknown             | 2         | 2      | 0.24%   |
| USB3.0              | 1         | 1      | 0.12%   |
| Transcend           | 1         | 1      | 0.12%   |
| SPCC                | 1         | 1      | 0.12%   |
| ShiJi               | 1         | 1      | 0.12%   |
| Plextor             | 1         | 1      | 0.12%   |
| Netac               | 1         | 1      | 0.12%   |
| Lenovo              | 1         | 1      | 0.12%   |
| KingDian            | 1         | 1      | 0.12%   |
| JMicron Technology  | 1         | 1      | 0.12%   |
| IBM/Hitachi         | 1         | 1      | 0.12%   |
| GOODRAM             | 1         | 1      | 0.12%   |
| DGM                 | 1         | 1      | 0.12%   |
| ASMedia             | 1         | 1      | 0.12%   |
| Apple               | 1         | 1      | 0.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 222       | 287    | 35.07%  |
| WDC                 | 174       | 215    | 27.49%  |
| Hitachi             | 89        | 107    | 14.06%  |
| Toshiba             | 58        | 61     | 9.16%   |
| Fujitsu             | 34        | 35     | 5.37%   |
| Samsung Electronics | 23        | 23     | 3.63%   |
| HGST                | 19        | 21     | 3%      |
| Maxtor              | 7         | 7      | 1.11%   |
| Hewlett-Packard     | 2         | 3      | 0.32%   |
| USB3.0              | 1         | 1      | 0.16%   |
| JMicron Technology  | 1         | 1      | 0.16%   |
| IBM/Hitachi         | 1         | 1      | 0.16%   |
| ASMedia             | 1         | 1      | 0.16%   |
| Apple               | 1         | 1      | 0.16%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 606       | 764    | 75.66%  |
| SSD  | 165       | 197    | 20.6%   |
| NVMe | 30        | 36     | 3.75%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 5%      |
| WDC WD4001FFSX-68JNUN0 4TB                      | 1         | 1      | 5%      |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 5%      |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 5%      |
| Seagate ST500DM005 HD502HJ 500GB                | 1         | 1      | 5%      |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 2      | 5%      |
| Seagate ST3500830AS 500GB                       | 1         | 1      | 5%      |
| Seagate ST3500630A 500GB                        | 1         | 1      | 5%      |
| Samsung Electronics SSD 980 250GB               | 1         | 1      | 5%      |
| Samsung Electronics SSD 980 1TB                 | 1         | 1      | 5%      |
| Samsung Electronics SP0802N 80GB                | 1         | 1      | 5%      |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 5%      |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 5%      |
| Samsung Electronics HD253GJ 250GB               | 1         | 1      | 5%      |
| KingDian S400 120GB SSD                         | 1         | 1      | 5%      |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 5%      |
| HGST HUH728080ALN600 8TB                        | 1         | 1      | 5%      |
| HGST HTS725050A7E630 500GB                      | 1         | 2      | 5%      |
| HGST HDN724040ALE640 4TB                        | 1         | 1      | 5%      |
| Hewlett-Packard SSD S700 500GB                  | 1         | 2      | 5%      |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 7      | 30%     |
| Samsung Electronics | 6         | 6      | 30%     |
| HGST                | 3         | 4      | 15%     |
| WDC                 | 2         | 2      | 10%     |
| KingDian            | 1         | 1      | 5%      |
| Hitachi             | 1         | 2      | 5%      |
| Hewlett-Packard     | 1         | 2      | 5%      |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 4269      | 7573   | 65.99%  |
| Detected | 1397      | 2696   | 21.6%   |
| Malfunc  | 781       | 997    | 12.07%  |
| Failed   | 20        | 24     | 0.31%   |
| Limited  | 2         | 2      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3468      | 49.69%  |
| AMD                              | 888       | 12.72%  |
| Samsung Electronics              | 724       | 10.37%  |
| Nvidia                           | 423       | 6.06%   |
| SanDisk                          | 275       | 3.94%   |
| SK hynix                         | 123       | 1.76%   |
| ASMedia Technology               | 107       | 1.53%   |
| Phison Electronics               | 94        | 1.35%   |
| Apple                            | 85        | 1.22%   |
| Kingston Technology Company      | 84        | 1.2%    |
| Marvell Technology Group         | 70        | 1%      |
| Toshiba America Info Systems     | 63        | 0.9%    |
| JMicron Technology               | 63        | 0.9%    |
| Micron Technology                | 61        | 0.87%   |
| Micron/Crucial Technology        | 55        | 0.79%   |
| LSI Logic / Symbios Logic        | 55        | 0.79%   |
| KIOXIA                           | 55        | 0.79%   |
| Silicon Motion                   | 45        | 0.64%   |
| ADATA Technology                 | 45        | 0.64%   |
| Broadcom / LSI                   | 43        | 0.62%   |
| VIA Technologies                 | 28        | 0.4%    |
| Hewlett-Packard                  | 15        | 0.21%   |
| Solid State Storage Technology   | 14        | 0.2%    |
| Adaptec                          | 12        | 0.17%   |
| MAXIO Technology (Hangzhou)      | 10        | 0.14%   |
| Realtek Semiconductor            | 9         | 0.13%   |
| Union Memory (Shenzhen)          | 8         | 0.11%   |
| Silicon Image                    | 8         | 0.11%   |
| Seagate Technology               | 6         | 0.09%   |
| Lite-On Technology               | 6         | 0.09%   |
| Silicon Integrated Systems [SiS] | 5         | 0.07%   |
| Shenzhen Longsys Electronics     | 4         | 0.06%   |
| Lenovo                           | 4         | 0.06%   |
| INNOGRIT                         | 4         | 0.06%   |
| ULi Electronics                  | 3         | 0.04%   |
| Jiangsu Huacun Elec.             | 3         | 0.04%   |
| 3ware                            | 3         | 0.04%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| Biwin Storage Technology         | 2         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 610       | 7.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 394       | 4.9%    |
| Nvidia MCP79 AHCI Controller                                                            | 365       | 4.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 259       | 3.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 234       | 2.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 199       | 2.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 168       | 2.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 144       | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 138       | 1.72%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 135       | 1.68%   |
| AMD 400 Series Chipset SATA Controller                                                  | 133       | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 131       | 1.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 126       | 1.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 126       | 1.57%   |
| Samsung NVMe SSD Controller 980                                                         | 112       | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 105       | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 103       | 1.28%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 102       | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 98        | 1.22%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 91        | 1.13%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 87        | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 83        | 1.03%   |
| Samsung Electronics SATA controller                                                     | 83        | 1.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 81        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 81        | 1.01%   |
| AMD 500 Series Chipset SATA Controller                                                  | 80        | 1%      |
| Apple S1X NVMe Controller                                                               | 79        | 0.98%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 74        | 0.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 71        | 0.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 70        | 0.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 69        | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 69        | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 69        | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 63        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 61        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 61        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 59        | 0.73%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 58        | 0.72%   |
| Micron NVMe Storage Controller                                                          | 58        | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 55        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4101      | 57.35%  |
| NVMe | 1710      | 23.91%  |
| IDE  | 830       | 11.61%  |
| RAID | 419       | 5.86%   |
| SAS  | 75        | 1.05%   |
| SCSI | 16        | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 4619      | 78.39%  |
| AMD                   | 1076      | 18.26%  |
| ARM                   | 179       | 3.04%   |
| CentaurHauls          | 7         | 0.12%   |
| sifive,u74-mc         | 3         | 0.05%   |
| Phytium               | 3         | 0.05%   |
| Unknown               | 2         | 0.03%   |
| Qualcomm              | 1         | 0.02%   |
| Marvell Semiconductor | 1         | 0.02%   |
| HISILICON             | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 355       | 6.02%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 179       | 3.03%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 147       | 2.49%   |
| ARM Processor                                 | 147       | 2.49%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 90        | 1.53%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 68        | 1.15%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 61        | 1.03%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 60        | 1.02%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 55        | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 47        | 0.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 45        | 0.76%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 45        | 0.76%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 44        | 0.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 40        | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 36        | 0.61%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 35        | 0.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 33        | 0.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 33        | 0.56%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 30        | 0.51%   |
| AMD Ryzen 5 3600 6-Core Processor             | 30        | 0.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 29        | 0.49%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 28        | 0.47%   |
| Intel Celeron N5105 @ 2.00GHz                 | 28        | 0.47%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 27        | 0.46%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 27        | 0.46%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 27        | 0.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 25        | 0.42%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 25        | 0.42%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 25        | 0.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 25        | 0.42%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 25        | 0.42%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 24        | 0.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 24        | 0.41%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 24        | 0.41%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 24        | 0.41%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 24        | 0.41%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 24        | 0.41%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 23        | 0.39%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 23        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1150      | 19.51%  |
| Intel Core i7           | 691       | 11.72%  |
| Other                   | 642       | 10.89%  |
| Intel Core 2 Duo        | 566       | 9.6%    |
| Intel Core i3           | 433       | 7.35%   |
| Intel Celeron           | 426       | 7.23%   |
| AMD Ryzen 5             | 270       | 4.58%   |
| Intel Pentium           | 221       | 3.75%   |
| Intel Xeon              | 220       | 3.73%   |
| AMD Ryzen 7             | 181       | 3.07%   |
| Intel Atom              | 116       | 1.97%   |
| AMD Ryzen 9             | 78        | 1.32%   |
| Intel Core 2            | 76        | 1.29%   |
| Intel Pentium Dual-Core | 64        | 1.09%   |
| AMD FX                  | 60        | 1.02%   |
| AMD Ryzen 3             | 48        | 0.81%   |
| Intel Core 2 Quad       | 36        | 0.61%   |
| AMD Ryzen 7 PRO         | 32        | 0.54%   |
| Intel Core i9           | 28        | 0.48%   |
| AMD A6                  | 28        | 0.48%   |
| AMD A10                 | 28        | 0.48%   |
| AMD Ryzen Threadripper  | 25        | 0.42%   |
| Intel Pentium M         | 22        | 0.37%   |
| Intel Pentium Gold      | 22        | 0.37%   |
| AMD Ryzen 5 PRO         | 22        | 0.37%   |
| AMD Athlon              | 22        | 0.37%   |
| Intel Pentium 4         | 21        | 0.36%   |
| AMD A4                  | 21        | 0.36%   |
| Intel Genuine           | 20        | 0.34%   |
| AMD Athlon II X2        | 18        | 0.31%   |
| Intel Pentium Dual      | 17        | 0.29%   |
| AMD A8                  | 17        | 0.29%   |
| AMD Phenom II X4        | 16        | 0.27%   |
| AMD Athlon 64 X2        | 16        | 0.27%   |
| Intel Pentium Silver    | 15        | 0.25%   |
| ARM Allwinner           | 15        | 0.25%   |
| Intel Celeron M         | 10        | 0.17%   |
| AMD Phenom II X6        | 10        | 0.17%   |
| AMD Opteron             | 10        | 0.17%   |
| AMD GX                  | 10        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2577      | 43.7%   |
| 4       | 1957      | 33.19%  |
| 6       | 493       | 8.36%   |
| 8       | 388       | 6.58%   |
| 1       | 198       | 3.36%   |
| 12      | 79        | 1.34%   |
| 16      | 75        | 1.27%   |
| 10      | 33        | 0.56%   |
| 3       | 24        | 0.41%   |
| Unknown | 16        | 0.27%   |
| 32      | 13        | 0.22%   |
| 14      | 13        | 0.22%   |
| 24      | 10        | 0.17%   |
| 20      | 6         | 0.1%    |
| 28      | 3         | 0.05%   |
| 18      | 3         | 0.05%   |
| 48      | 2         | 0.03%   |
| 44      | 2         | 0.03%   |
| 128     | 1         | 0.02%   |
| 80      | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 56      | 1         | 0.02%   |
| 36      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5769      | 97.88%  |
| 2       | 105       | 1.78%   |
| Unknown | 16        | 0.27%   |
| 3       | 2         | 0.03%   |
| 8       | 1         | 0.02%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3348      | 56.77%  |
| 1       | 2533      | 42.95%  |
| Unknown | 16        | 0.27%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5722      | 97.08%  |
| 32-bit         | 108       | 1.83%   |
| Unknown        | 46        | 0.78%   |
| 64-bit         | 18        | 0.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1077      | 18.01%  |
| 0x1067a    | 535       | 8.94%   |
| 0x306a9    | 270       | 4.51%   |
| 0x806c1    | 258       | 4.31%   |
| 0x306c3    | 258       | 4.31%   |
| 0x206a7    | 250       | 4.18%   |
| 0x306d4    | 213       | 3.56%   |
| 0x906ea    | 146       | 2.44%   |
| 0x506e3    | 125       | 2.09%   |
| 0x806ec    | 116       | 1.94%   |
| 0x30678    | 115       | 1.92%   |
| 0x806e9    | 104       | 1.74%   |
| 0x806ea    | 87        | 1.45%   |
| 0x08108109 | 81        | 1.35%   |
| 0x406e3    | 78        | 1.3%    |
| 0x40651    | 78        | 1.3%    |
| 0x406c4    | 76        | 1.27%   |
| 0x906e9    | 74        | 1.24%   |
| 0xa0653    | 72        | 1.2%    |
| 0x6f6      | 71        | 1.19%   |
| 0x08701021 | 62        | 1.04%   |
| 0x906eb    | 60        | 1%      |
| 0x0a50000c | 55        | 0.92%   |
| 0x08600106 | 55        | 0.92%   |
| 0x20655    | 53        | 0.89%   |
| 0xa0652    | 51        | 0.85%   |
| 0x906c0    | 51        | 0.85%   |
| 0x10676    | 50        | 0.84%   |
| 0x706a8    | 47        | 0.79%   |
| 0x6fd      | 45        | 0.75%   |
| 0xa0655    | 40        | 0.67%   |
| 0x506c9    | 40        | 0.67%   |
| 0x706e5    | 38        | 0.64%   |
| 0x0600611a | 38        | 0.64%   |
| 0x0a201016 | 37        | 0.62%   |
| 0x08608103 | 36        | 0.6%    |
| 0x106c2    | 35        | 0.59%   |
| 0x0800820d | 33        | 0.55%   |
| 0xa0671    | 32        | 0.54%   |
| 0x206d7    | 29        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 775       | 13.14%  |
| Penryn           | 618       | 10.48%  |
| Haswell          | 441       | 7.48%   |
| IvyBridge        | 349       | 5.92%   |
| SandyBridge      | 341       | 5.78%   |
| Unknown          | 338       | 5.73%   |
| TigerLake        | 299       | 5.07%   |
| Skylake          | 268       | 4.54%   |
| Broadwell        | 249       | 4.22%   |
| Silvermont       | 240       | 4.07%   |
| Zen 2            | 206       | 3.49%   |
| CometLake        | 193       | 3.27%   |
| Zen+             | 181       | 3.07%   |
| Core             | 179       | 3.03%   |
| Zen 3            | 171       | 2.9%    |
| Westmere         | 116       | 1.97%   |
| Excavator        | 85        | 1.44%   |
| Zen              | 78        | 1.32%   |
| K10              | 77        | 1.31%   |
| Goldmont plus    | 77        | 1.31%   |
| IceLake          | 69        | 1.17%   |
| Bonnell          | 68        | 1.15%   |
| Piledriver       | 62        | 1.05%   |
| Tremont          | 54        | 0.92%   |
| P6               | 50        | 0.85%   |
| Goldmont         | 49        | 0.83%   |
| Nehalem          | 38        | 0.64%   |
| NetBurst         | 36        | 0.61%   |
| Alderlake Hybrid | 33        | 0.56%   |
| K8 Hammer        | 32        | 0.54%   |
| Bobcat           | 29        | 0.49%   |
| Puma             | 22        | 0.37%   |
| Steamroller      | 21        | 0.36%   |
| Jaguar           | 19        | 0.32%   |
| Bulldozer        | 17        | 0.29%   |
| K10 Llano        | 11        | 0.19%   |
| K8 & K10 hybrid  | 4         | 0.07%   |
| K6               | 3         | 0.05%   |
| Geode            | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3445      | 53.64%  |
| Nvidia                                       | 1667      | 25.95%  |
| AMD                                          | 1133      | 17.64%  |
| ASPEED Technology                            | 83        | 1.29%   |
| Matrox Electronics Systems                   | 79        | 1.23%   |
| VIA Technologies                             | 6         | 0.09%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.06%   |
| Zhaoxin                                      | 3         | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| S3 Graphics                                  | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 353       | 5.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 280       | 4.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 230       | 3.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 177       | 2.66%   |
| Intel HD Graphics 6000                                                                   | 154       | 2.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 149       | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 144       | 2.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 137       | 2.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 127       | 1.91%   |
| Intel UHD Graphics 620                                                                   | 108       | 1.62%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 99        | 1.49%   |
| Intel HD Graphics 620                                                                    | 99        | 1.49%   |
| AMD Renoir                                                                               | 99        | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 98        | 1.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 93        | 1.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 92        | 1.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 86        | 1.29%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 83        | 1.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 80        | 1.2%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 78        | 1.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 76        | 1.14%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 71        | 1.07%   |
| Intel HD Graphics 530                                                                    | 70        | 1.05%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 69        | 1.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 68        | 1.02%   |
| Intel HD Graphics 5500                                                                   | 68        | 1.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 64        | 0.96%   |
| Intel HD Graphics 630                                                                    | 61        | 0.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 60        | 0.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 59        | 0.89%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 57        | 0.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 54        | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 54        | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 53        | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 53        | 0.8%    |
| Intel JasperLake [UHD Graphics]                                                          | 52        | 0.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 51        | 0.77%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 51        | 0.77%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 44        | 0.66%   |
| AMD Lucienne                                                                             | 44        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 2820      | 47.69%  |
| 1 x Nvidia                        | 1098      | 18.57%  |
| 1 x AMD                           | 914       | 15.46%  |
| Intel + Nvidia                    | 474       | 8.02%   |
| Other                             | 208       | 3.52%   |
| Intel + AMD                       | 85        | 1.44%   |
| 1 x Matrox                        | 75        | 1.27%   |
| AMD + Nvidia                      | 70        | 1.18%   |
| 1 x ASPEED                        | 64        | 1.08%   |
| 2 x AMD                           | 54        | 0.91%   |
| Nvidia + ASPEED                   | 9         | 0.15%   |
| AMD + ASPEED                      | 8         | 0.14%   |
| 2 x Nvidia                        | 6         | 0.1%    |
| 1 x VIA                           | 6         | 0.1%    |
| 1 x SiS                           | 4         | 0.07%   |
| 2 x Intel                         | 3         | 0.05%   |
| 1 x Zhaoxin                       | 3         | 0.05%   |
| Nvidia + Matrox                   | 3         | 0.05%   |
| Intel + 2 x Nvidia                | 3         | 0.05%   |
| 3 x AMD                           | 1         | 0.02%   |
| 2 x Nvidia + 1 x ASPEED           | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.02%   |
| 1 x S3 Graphics                   | 1         | 0.02%   |
| Nvidia + XGI                      | 1         | 0.02%   |
| AMD + Matrox                      | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4191      | 70.71%  |
| Unknown     | 1266      | 21.36%  |
| Proprietary | 470       | 7.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 4260      | 71.56%  |
| 0.01-0.5       | 745       | 12.51%  |
| 1.01-2.0       | 308       | 5.17%   |
| 3.01-4.0       | 200       | 3.36%   |
| 0.51-1.0       | 200       | 3.36%   |
| 7.01-8.0       | 113       | 1.9%    |
| 5.01-6.0       | 67        | 1.13%   |
| 8.01-16.0      | 27        | 0.45%   |
| 2.01-3.0       | 23        | 0.39%   |
| 16.01-24.0     | 6         | 0.1%    |
| 4.01-5.0       | 2         | 0.03%   |
| More than 64.0 | 1         | 0.02%   |
| 24.01-32.0     | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Apple                   | 645       | 12.57%  |
| AU Optronics            | 623       | 12.14%  |
| Samsung Electronics     | 477       | 9.29%   |
| BOE                     | 434       | 8.46%   |
| LG Display              | 367       | 7.15%   |
| Chimei Innolux          | 361       | 7.03%   |
| Dell                    | 260       | 5.07%   |
| Goldstar                | 216       | 4.21%   |
| Hewlett-Packard         | 143       | 2.79%   |
| Acer                    | 125       | 2.44%   |
| BenQ                    | 120       | 2.34%   |
| AOC                     | 103       | 2.01%   |
| Lenovo                  | 100       | 1.95%   |
| Philips                 | 94        | 1.83%   |
| Ancor Communications    | 94        | 1.83%   |
| Sharp                   | 67        | 1.31%   |
| Chi Mei Optoelectronics | 62        | 1.21%   |
| Iiyama                  | 58        | 1.13%   |
| ViewSonic               | 57        | 1.11%   |
| Unknown                 | 57        | 1.11%   |
| InfoVision              | 52        | 1.01%   |
| Eizo                    | 37        | 0.72%   |
| ASUSTek Computer        | 35        | 0.68%   |
| PANDA                   | 34        | 0.66%   |
| HannStar                | 27        | 0.53%   |
| Sony                    | 26        | 0.51%   |
| NEC Computers           | 26        | 0.51%   |
| LG Philips              | 20        | 0.39%   |
| LG Electronics          | 19        | 0.37%   |
| Panasonic               | 15        | 0.29%   |
| MSI                     | 15        | 0.29%   |
| CSO                     | 15        | 0.29%   |
| Vestel Elektronik       | 13        | 0.25%   |
| Unknown                 | 12        | 0.23%   |
| Toshiba                 | 11        | 0.21%   |
| Vizio                   | 9         | 0.18%   |
| Medion                  | 8         | 0.16%   |
| Fujitsu Siemens         | 7         | 0.14%   |
| CPT                     | 7         | 0.14%   |
| Belinea                 | 7         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                   | 209       | 3.98%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                 | 187       | 3.56%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch         | 112       | 2.13%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                   | 52        | 0.99%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 46        | 0.88%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 42        | 0.8%    |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                   | 41        | 0.78%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch          | 39        | 0.74%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                   | 37        | 0.7%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                   | 27        | 0.51%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                   | 25        | 0.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 25        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 24        | 0.46%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                   | 22        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch        | 21        | 0.4%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch              | 19        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 19        | 0.36%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 17        | 0.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 17        | 0.32%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 15        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 15        | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 15        | 0.29%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch          | 15        | 0.29%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                   | 13        | 0.25%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 12        | 0.23%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 12        | 0.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 12        | 0.23%   |
| Unknown                                                                | 12        | 0.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 11        | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 11        | 0.21%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                   | 11        | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 10        | 0.19%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 10        | 0.19%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 10        | 0.19%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 10        | 0.19%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                      | 10        | 0.19%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch          | 10        | 0.19%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 9         | 0.17%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 9         | 0.17%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch            | 9         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1956      | 39.64%  |
| 1366x768 (WXGA)    | 867       | 17.57%  |
| 1280x800 (WXGA)    | 515       | 10.44%  |
| 3840x2160 (4K)     | 253       | 5.13%   |
| 2560x1440 (QHD)    | 187       | 3.79%   |
| 1280x1024 (SXGA)   | 181       | 3.67%   |
| 1440x900 (WXGA+)   | 153       | 3.1%    |
| 1600x900 (HD+)     | 148       | 3%      |
| 1920x1200 (WUXGA)  | 105       | 2.13%   |
| 1680x1050 (WSXGA+) | 93        | 1.88%   |
| Unknown            | 53        | 1.07%   |
| 2288x1287          | 48        | 0.97%   |
| 1024x600           | 46        | 0.93%   |
| 1024x768 (XGA)     | 37        | 0.75%   |
| 2560x1080          | 34        | 0.69%   |
| 3440x1440          | 31        | 0.63%   |
| 1360x768           | 30        | 0.61%   |
| 2560x1600          | 23        | 0.47%   |
| 1600x1200          | 21        | 0.43%   |
| 3840x1080          | 20        | 0.41%   |
| 3840x2400          | 13        | 0.26%   |
| 1920x540           | 12        | 0.24%   |
| 2880x1800          | 10        | 0.2%    |
| 2160x1440          | 9         | 0.18%   |
| 1400x1050          | 7         | 0.14%   |
| 4480x1440          | 6         | 0.12%   |
| 1920x1280          | 6         | 0.12%   |
| 2736x1824          | 5         | 0.1%    |
| 5760x1080          | 4         | 0.08%   |
| 2048x1152          | 4         | 0.08%   |
| 1280x720 (HD)      | 4         | 0.08%   |
| 3840x1600          | 3         | 0.06%   |
| 3840x1200          | 3         | 0.06%   |
| 3200x1800 (QHD+)   | 3         | 0.06%   |
| 3200x1080          | 3         | 0.06%   |
| 1800x1200          | 3         | 0.06%   |
| 1024x576           | 3         | 0.06%   |
| 5760x2160          | 2         | 0.04%   |
| 5360x1440          | 2         | 0.04%   |
| 3840x1100          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 1047      | 20.58%  |
| 15      | 939       | 18.46%  |
| 14      | 376       | 7.39%   |
| 24      | 347       | 6.82%   |
| 23      | 286       | 5.62%   |
| 27      | 284       | 5.58%   |
| 11      | 248       | 4.87%   |
| 17      | 246       | 4.83%   |
| 21      | 218       | 4.28%   |
| Unknown | 158       | 3.11%   |
| 19      | 127       | 2.5%    |
| 12      | 115       | 2.26%   |
| 18      | 91        | 1.79%   |
| 31      | 87        | 1.71%   |
| 22      | 63        | 1.24%   |
| 20      | 56        | 1.1%    |
| 10      | 53        | 1.04%   |
| 34      | 47        | 0.92%   |
| 142     | 46        | 0.9%    |
| 84      | 31        | 0.61%   |
| 32      | 23        | 0.45%   |
| 72      | 22        | 0.43%   |
| 16      | 21        | 0.41%   |
| 25      | 20        | 0.39%   |
| 54      | 16        | 0.31%   |
| 40      | 14        | 0.28%   |
| 29      | 11        | 0.22%   |
| 28      | 11        | 0.22%   |
| 26      | 11        | 0.22%   |
| 52      | 7         | 0.14%   |
| 43      | 6         | 0.12%   |
| 33      | 6         | 0.12%   |
| 65      | 5         | 0.1%    |
| 48      | 5         | 0.1%    |
| 49      | 4         | 0.08%   |
| 47      | 4         | 0.08%   |
| 46      | 4         | 0.08%   |
| 42      | 4         | 0.08%   |
| 8       | 4         | 0.08%   |
| 55      | 3         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1635      | 32.62%  |
| 201-300        | 1223      | 24.4%   |
| 501-600        | 847       | 16.9%   |
| 401-500        | 467       | 9.32%   |
| 351-400        | 265       | 5.29%   |
| Unknown        | 158       | 3.15%   |
| 601-700        | 149       | 2.97%   |
| 701-800        | 76        | 1.52%   |
| 1501-2000      | 56        | 1.12%   |
| 1001-1500      | 53        | 1.06%   |
| More than 2000 | 47        | 0.94%   |
| 801-900        | 24        | 0.48%   |
| 901-1000       | 8         | 0.16%   |
| 101-200        | 5         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3190      | 68.21%  |
| 16/10   | 934       | 19.97%  |
| 5/4     | 169       | 3.61%   |
| Unknown | 128       | 2.74%   |
| 4/3     | 78        | 1.67%   |
| 21/9    | 60        | 1.28%   |
| 1.00    | 48        | 1.03%   |
| 3/2     | 41        | 0.88%   |
| 6/5     | 10        | 0.21%   |
| 2.65    | 5         | 0.11%   |
| 32/9    | 4         | 0.09%   |
| 3.40    | 2         | 0.04%   |
| 3.20    | 2         | 0.04%   |
| 0.56    | 2         | 0.04%   |
| 3.73    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 11/10   | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 1088      | 21.58%  |
| 101-110        | 933       | 18.5%   |
| 201-250        | 718       | 14.24%  |
| 71-80          | 334       | 6.62%   |
| 301-350        | 292       | 5.79%   |
| 51-60          | 251       | 4.98%   |
| 151-200        | 251       | 4.98%   |
| 351-500        | 178       | 3.53%   |
| 141-150        | 162       | 3.21%   |
| Unknown        | 158       | 3.13%   |
| More than 1000 | 142       | 2.82%   |
| 251-300        | 139       | 2.76%   |
| 121-130        | 132       | 2.62%   |
| 61-70          | 107       | 2.12%   |
| 41-50          | 52        | 1.03%   |
| 501-1000       | 43        | 0.85%   |
| 131-140        | 27        | 0.54%   |
| 111-120        | 17        | 0.34%   |
| 91-100         | 13        | 0.26%   |
| 1-40           | 5         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1444      | 29.29%  |
| 101-120       | 1401      | 28.42%  |
| 51-100        | 1387      | 28.13%  |
| 161-240       | 350       | 7.1%    |
| Unknown       | 158       | 3.2%    |
| 1-50          | 122       | 2.47%   |
| More than 240 | 68        | 1.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3901      | 65.25%  |
| 0     | 1345      | 22.5%   |
| 2     | 657       | 10.99%  |
| 3     | 73        | 1.22%   |
| 4     | 2         | 0.03%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2727      | 32.14%  |
| Intel                             | 2617      | 30.84%  |
| Qualcomm Atheros                  | 756       | 8.91%   |
| Broadcom                          | 740       | 8.72%   |
| Nvidia                            | 413       | 4.87%   |
| Broadcom Limited                  | 251       | 2.96%   |
| Marvell Technology Group          | 132       | 1.56%   |
| MediaTek                          | 72        | 0.85%   |
| Ralink Technology                 | 71        | 0.84%   |
| TP-Link                           | 60        | 0.71%   |
| Ralink                            | 49        | 0.58%   |
| ASIX Electronics                  | 49        | 0.58%   |
| Samsung Electronics               | 37        | 0.44%   |
| Dell                              | 26        | 0.31%   |
| Sierra Wireless                   | 24        | 0.28%   |
| Microchip Technology              | 24        | 0.28%   |
| Mellanox Technologies             | 21        | 0.25%   |
| Qualcomm                          | 20        | 0.24%   |
| Qualcomm Atheros Communications   | 19        | 0.22%   |
| Huawei Technologies               | 19        | 0.22%   |
| Xiaomi                            | 18        | 0.21%   |
| DisplayLink                       | 18        | 0.21%   |
| Aquantia                          | 16        | 0.19%   |
| NetGear                           | 15        | 0.18%   |
| D-Link System                     | 14        | 0.16%   |
| Lenovo                            | 13        | 0.15%   |
| D-Link                            | 13        | 0.15%   |
| Ericsson Business Mobile Networks | 12        | 0.14%   |
| Dresden Elektronik                | 12        | 0.14%   |
| ASUSTek Computer                  | 12        | 0.14%   |
| Microsoft                         | 10        | 0.12%   |
| Hewlett-Packard                   | 10        | 0.12%   |
| American Megatrends               | 10        | 0.12%   |
| JMicron Technology                | 9         | 0.11%   |
| ICS Advent                        | 9         | 0.11%   |
| VIA Technologies                  | 8         | 0.09%   |
| Edimax Technology                 | 8         | 0.09%   |
| OPPO Electronics                  | 7         | 0.08%   |
| FIBOCOM                           | 7         | 0.08%   |
| Sigma Designs                     | 6         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1932      | 19.53%  |
| Nvidia MCP79 Ethernet                                                                 | 366       | 3.7%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 360       | 3.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 285       | 2.88%   |
| Intel Wi-Fi 6 AX201                                                                   | 245       | 2.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 189       | 1.91%   |
| Intel Wi-Fi 6 AX200                                                                   | 183       | 1.85%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 160       | 1.62%   |
| Intel Wireless 7260                                                                   | 155       | 1.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 147       | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 146       | 1.48%   |
| Intel Wireless 8265 / 8275                                                            | 143       | 1.45%   |
| Intel Wireless 7265                                                                   | 134       | 1.35%   |
| Intel Ethernet Connection (13) I219-V                                                 | 134       | 1.35%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 102       | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 93        | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 87        | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 83        | 0.84%   |
| Intel I211 Gigabit Network Connection                                                 | 82        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 82        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 81        | 0.82%   |
| Intel Wireless 8260                                                                   | 76        | 0.77%   |
| Intel Wireless 3165                                                                   | 75        | 0.76%   |
| Intel I210 Gigabit Network Connection                                                 | 75        | 0.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 74        | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 71        | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 69        | 0.7%    |
| Intel Ethernet Controller I225-V                                                      | 66        | 0.67%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 63        | 0.64%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 59        | 0.6%    |
| Intel Ethernet Connection I217-LM                                                     | 58        | 0.59%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 55        | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 54        | 0.55%   |
| Intel Ethernet Connection (2) I219-V                                                  | 53        | 0.54%   |
| Intel Ethernet Connection (4) I219-V                                                  | 51        | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 47        | 0.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 47        | 0.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 45        | 0.45%   |
| Intel 82579V Gigabit Network Connection                                               | 44        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1870      | 45%     |
| Qualcomm Atheros                      | 617       | 14.85%  |
| Broadcom                              | 549       | 13.21%  |
| Realtek Semiconductor                 | 522       | 12.56%  |
| Broadcom Limited                      | 204       | 4.91%   |
| Ralink Technology                     | 71        | 1.71%   |
| MediaTek                              | 66        | 1.59%   |
| Ralink                                | 49        | 1.18%   |
| TP-Link                               | 42        | 1.01%   |
| Sierra Wireless                       | 24        | 0.58%   |
| Qualcomm Atheros Communications       | 19        | 0.46%   |
| NetGear                               | 15        | 0.36%   |
| Dell                                  | 15        | 0.36%   |
| ASUSTek Computer                      | 12        | 0.29%   |
| D-Link                                | 11        | 0.26%   |
| Edimax Technology                     | 8         | 0.19%   |
| D-Link System                         | 8         | 0.19%   |
| Qualcomm                              | 7         | 0.17%   |
| Microsoft                             | 7         | 0.17%   |
| Fibocom                               | 7         | 0.17%   |
| Marvell Technology Group              | 6         | 0.14%   |
| Belkin Components                     | 6         | 0.14%   |
| IMC Networks                          | 3         | 0.07%   |
| Gemtek                                | 3         | 0.07%   |
| Wilocity                              | 2         | 0.05%   |
| Linksys                               | 2         | 0.05%   |
| AVM                                   | 2         | 0.05%   |
| Z-Com                                 | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| CyberTAN Technology                   | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |
| 3Com                                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 360       | 8.63%   |
| Intel Wi-Fi 6 AX201                                                                   | 245       | 5.87%   |
| Intel Wi-Fi 6 AX200                                                                   | 183       | 4.39%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 160       | 3.84%   |
| Intel Wireless 7260                                                                   | 155       | 3.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 146       | 3.5%    |
| Intel Wireless 8265 / 8275                                                            | 143       | 3.43%   |
| Intel Wireless 7265                                                                   | 134       | 3.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 93        | 2.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 87        | 2.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 83        | 1.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 82        | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 81        | 1.94%   |
| Intel Wireless 8260                                                                   | 76        | 1.82%   |
| Intel Wireless 3165                                                                   | 75        | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 74        | 1.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 71        | 1.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 69        | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 63        | 1.51%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 55        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 54        | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 47        | 1.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 47        | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 45        | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 43        | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 38        | 0.91%   |
| Intel Wireless-AC 9260                                                                | 37        | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 35        | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 34        | 0.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 30        | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 30        | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 30        | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 27        | 0.65%   |
| Intel Wireless 3160                                                                   | 27        | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 27        | 0.65%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 26        | 0.62%   |
| Realtek 802.11ac NIC                                                                  | 25        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 23        | 0.55%   |
| Intel Centrino Ultimate-N 6300                                                        | 23        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2516      | 46.39%  |
| Intel                            | 1508      | 27.81%  |
| Nvidia                           | 413       | 7.62%   |
| Broadcom                         | 232       | 4.28%   |
| Qualcomm Atheros                 | 210       | 3.87%   |
| Marvell Technology Group         | 127       | 2.34%   |
| Broadcom Limited                 | 50        | 0.92%   |
| ASIX Electronics                 | 49        | 0.9%    |
| Samsung Electronics              | 37        | 0.68%   |
| Microchip Technology             | 24        | 0.44%   |
| Xiaomi                           | 18        | 0.33%   |
| TP-Link                          | 18        | 0.33%   |
| DisplayLink                      | 18        | 0.33%   |
| Mellanox Technologies            | 17        | 0.31%   |
| Aquantia                         | 16        | 0.3%    |
| Lenovo                           | 13        | 0.24%   |
| Qualcomm                         | 12        | 0.22%   |
| Huawei Technologies              | 12        | 0.22%   |
| American Megatrends              | 10        | 0.18%   |
| JMicron Technology               | 9         | 0.17%   |
| ICS Advent                       | 9         | 0.17%   |
| VIA Technologies                 | 8         | 0.15%   |
| OPPO Electronics                 | 7         | 0.13%   |
| D-Link System                    | 6         | 0.11%   |
| Cypress Semiconductor            | 6         | 0.11%   |
| Standard Microsystems            | 5         | 0.09%   |
| Silicon Integrated Systems [SiS] | 5         | 0.09%   |
| MediaTek                         | 5         | 0.09%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.07%   |
| Motorola PCS                     | 4         | 0.07%   |
| Attansic Technology              | 4         | 0.07%   |
| 3Com                             | 4         | 0.07%   |
| QLogic                           | 3         | 0.06%   |
| NetXen Incorporated              | 3         | 0.06%   |
| Microsoft                        | 3         | 0.06%   |
| IBM                              | 3         | 0.06%   |
| Hewlett-Packard                  | 3         | 0.06%   |
| Apple                            | 3         | 0.06%   |
| Spreadtrum Communications        | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1932      | 34.55%  |
| Nvidia MCP79 Ethernet                                             | 366       | 6.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 285       | 5.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 189       | 3.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 147       | 2.63%   |
| Intel Ethernet Connection (13) I219-V                             | 134       | 2.4%    |
| Realtek RTL8125 2.5GbE Controller                                 | 102       | 1.82%   |
| Intel I211 Gigabit Network Connection                             | 82        | 1.47%   |
| Intel I210 Gigabit Network Connection                             | 75        | 1.34%   |
| Intel Ethernet Controller I225-V                                  | 66        | 1.18%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 59        | 1.06%   |
| Intel Ethernet Connection I217-LM                                 | 58        | 1.04%   |
| Intel Ethernet Connection (2) I219-V                              | 53        | 0.95%   |
| Intel Ethernet Connection (4) I219-V                              | 51        | 0.91%   |
| Intel 82579V Gigabit Network Connection                           | 44        | 0.79%   |
| Intel 82574L Gigabit Network Connection                           | 42        | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 40        | 0.72%   |
| Intel I350 Gigabit Network Connection                             | 39        | 0.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 39        | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 38        | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 38        | 0.68%   |
| Intel Ethernet Connection (14) I219-V                             | 38        | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 35        | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 33        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 32        | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 30        | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 29        | 0.52%   |
| Nvidia MCP61 Ethernet                                             | 28        | 0.5%    |
| Intel Ethernet Connection (10) I219-V                             | 28        | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 27        | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 25        | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 25        | 0.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.45%   |
| Intel 82577LM Gigabit Network Connection                          | 23        | 0.41%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 23        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 22        | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 22        | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21        | 0.38%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 20        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5064      | 55.18%  |
| WiFi     | 3989      | 43.46%  |
| Modem    | 113       | 1.23%   |
| Unknown  | 12        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3062      | 52.21%  |
| WiFi     | 2803      | 47.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3027      | 51.28%  |
| 1     | 2351      | 39.83%  |
| 0     | 240       | 4.07%   |
| 3     | 167       | 2.83%   |
| 4     | 63        | 1.07%   |
| 6     | 19        | 0.32%   |
| 5     | 19        | 0.32%   |
| 8     | 8         | 0.14%   |
| 7     | 3         | 0.05%   |
| 20    | 2         | 0.03%   |
| 14    | 1         | 0.02%   |
| 13    | 1         | 0.02%   |
| 12    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4874      | 82.14%  |
| Yes  | 1060      | 17.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1531      | 45.22%  |
| Apple                           | 653       | 19.29%  |
| Realtek Semiconductor           | 255       | 7.53%   |
| Qualcomm Atheros Communications | 218       | 6.44%   |
| Cambridge Silicon Radio         | 153       | 4.52%   |
| Broadcom                        | 127       | 3.75%   |
| IMC Networks                    | 108       | 3.19%   |
| Lite-On Technology              | 95        | 2.81%   |
| Foxconn / Hon Hai               | 61        | 1.8%    |
| ASUSTek Computer                | 37        | 1.09%   |
| Dell                            | 36        | 1.06%   |
| Hewlett-Packard                 | 26        | 0.77%   |
| Realtek                         | 15        | 0.44%   |
| MediaTek                        | 14        | 0.41%   |
| Toshiba                         | 11        | 0.32%   |
| Ralink                          | 11        | 0.32%   |
| Ralink Technology               | 4         | 0.12%   |
| Foxconn International           | 4         | 0.12%   |
| TP-Link                         | 3         | 0.09%   |
| Taiyo Yuden                     | 3         | 0.09%   |
| Alps Electric                   | 3         | 0.09%   |
| Fujitsu                         | 2         | 0.06%   |
| Edimax Technology               | 2         | 0.06%   |
| Belkin Components               | 2         | 0.06%   |
| Unknown                         | 2         | 0.06%   |
| USI                             | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Microsoft                       | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Marvell Semiconductor           | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 580       | 17.12%  |
| Intel AX201 Bluetooth                               | 385       | 11.36%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 364       | 10.74%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 204       | 6.02%   |
| Intel AX200 Bluetooth                               | 176       | 5.19%   |
| Apple Bluetooth USB Host Controller                 | 168       | 4.96%   |
| Realtek Bluetooth Radio                             | 163       | 4.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 153       | 4.52%   |
| Qualcomm Atheros  Bluetooth Device                  | 133       | 3.93%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.24%   |
| Realtek  Bluetooth 4.2 Adapter                      | 59        | 1.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 44        | 1.3%    |
| Intel AX210 Bluetooth                               | 38        | 1.12%   |
| Apple Bluetooth Host Controller                     | 38        | 1.12%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 34        | 1%      |
| IMC Networks Bluetooth Radio                        | 33        | 0.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 32        | 0.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 28        | 0.83%   |
| Intel Bluetooth Device                              | 28        | 0.83%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 27        | 0.8%    |
| Lite-On Bluetooth Device                            | 26        | 0.77%   |
| IMC Networks Bluetooth Device                       | 26        | 0.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 22        | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 0.62%   |
| IMC Networks Wireless_Device                        | 20        | 0.59%   |
| Foxconn / Hon Hai Wireless_Device                   | 19        | 0.56%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 0.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 19        | 0.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 0.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 18        | 0.53%   |
| Realtek RTL8723B Bluetooth                          | 17        | 0.5%    |
| Realtek Bluetooth Radio                             | 15        | 0.44%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 0.44%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.41%   |
| MediaTek Wireless_Device                            | 13        | 0.38%   |
| Lite-On Atheros AR3012 Bluetooth                    | 12        | 0.35%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.35%   |
| Ralink RT3290 Bluetooth                             | 11        | 0.32%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 11        | 0.32%   |
| Lite-On Wireless_Device                             | 10        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3974      | 56.01%  |
| Nvidia                                       | 1333      | 18.79%  |
| AMD                                          | 1196      | 16.86%  |
| C-Media Electronics                          | 90        | 1.27%   |
| Logitech                                     | 44        | 0.62%   |
| Creative Labs                                | 28        | 0.39%   |
| ASUSTek Computer                             | 25        | 0.35%   |
| Texas Instruments                            | 24        | 0.34%   |
| Generalplus Technology                       | 24        | 0.34%   |
| Lenovo                                       | 18        | 0.25%   |
| Realtek Semiconductor                        | 17        | 0.24%   |
| Plantronics                                  | 17        | 0.24%   |
| Creative Technology                          | 16        | 0.23%   |
| GN Netcom                                    | 15        | 0.21%   |
| JMTek                                        | 14        | 0.2%    |
| Focusrite-Novation                           | 14        | 0.2%    |
| VIA Technologies                             | 13        | 0.18%   |
| KTMicro                                      | 13        | 0.18%   |
| Kingston Technology                          | 11        | 0.16%   |
| Zoran Co. Personal Media Division (Nogatech) | 9         | 0.13%   |
| Micro Star International                     | 9         | 0.13%   |
| RODE Microphones                             | 8         | 0.11%   |
| Hewlett-Packard                              | 8         | 0.11%   |
| SteelSeries ApS                              | 7         | 0.1%    |
| Razer USA                                    | 7         | 0.1%    |
| GYROCOM C&C                                  | 7         | 0.1%    |
| Dell                                         | 7         | 0.1%    |
| Sennheiser Communications                    | 6         | 0.08%   |
| BEHRINGER International                      | 6         | 0.08%   |
| Yamaha                                       | 5         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.07%   |
| Microsoft                                    | 5         | 0.07%   |
| Cambridge Silicon Radio                      | 5         | 0.07%   |
| Tenx Technology                              | 4         | 0.06%   |
| Corsair                                      | 4         | 0.06%   |
| Blue Microphones                             | 4         | 0.06%   |
| Apple                                        | 4         | 0.06%   |
| Zhaoxin                                      | 3         | 0.04%   |
| XMOS                                         | 3         | 0.04%   |
| ULi Electronics                              | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 407       | 4.85%   |
| Nvidia MCP79 High Definition Audio                                                                | 369       | 4.4%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 342       | 4.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 310       | 3.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 298       | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 295       | 3.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 274       | 3.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 256       | 3.05%   |
| Intel Broadwell-U Audio Controller                                                                | 231       | 2.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 226       | 2.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 222       | 2.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 197       | 2.35%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 170       | 2.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 167       | 1.99%   |
| Intel Cannon Lake PCH cAVS                                                                        | 159       | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 151       | 1.8%    |
| Intel 200 Series PCH HD Audio                                                                     | 141       | 1.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 139       | 1.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 123       | 1.47%   |
| Intel Comet Lake PCH cAVS                                                                         | 113       | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 111       | 1.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 105       | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 98        | 1.17%   |
| AMD FCH Azalia Controller                                                                         | 98        | 1.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 96        | 1.14%   |
| Intel 8 Series HD Audio Controller                                                                | 96        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 90        | 1.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 89        | 1.06%   |
| AMD Kabini HDMI/DP Audio                                                                          | 87        | 1.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 85        | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 82        | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 77        | 0.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 77        | 0.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 77        | 0.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 75        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 69        | 0.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 66        | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 60        | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 59        | 0.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 55        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1223      | 21.53%  |
| SK hynix            | 1200      | 21.13%  |
| Kingston            | 590       | 10.39%  |
| Unknown             | 550       | 9.68%   |
| Crucial             | 474       | 8.35%   |
| Micron Technology   | 456       | 8.03%   |
| Corsair             | 200       | 3.52%   |
| G.Skill             | 131       | 2.31%   |
| Elpida              | 112       | 1.97%   |
| A-DATA Technology   | 94        | 1.65%   |
| Ramaxel Technology  | 75        | 1.32%   |
| Patriot             | 69        | 1.21%   |
| Unknown (ABCD)      | 53        | 0.93%   |
| Nanya Technology    | 52        | 0.92%   |
| Unknown             | 45        | 0.79%   |
| Team                | 33        | 0.58%   |
| GOODRAM             | 27        | 0.48%   |
| Smart               | 26        | 0.46%   |
| Transcend           | 21        | 0.37%   |
| Hikvision           | 21        | 0.37%   |
| AMD                 | 21        | 0.37%   |
| Hewlett-Packard     | 14        | 0.25%   |
| Apacer              | 12        | 0.21%   |
| Qimonda             | 9         | 0.16%   |
| Timetec             | 8         | 0.14%   |
| Silicon Power       | 6         | 0.11%   |
| PNY                 | 6         | 0.11%   |
| GeIL                | 6         | 0.11%   |
| ASint Technology    | 6         | 0.11%   |
| Wilk                | 5         | 0.09%   |
| Infineon            | 5         | 0.09%   |
| Goldkey             | 5         | 0.09%   |
| 48spaces            | 5         | 0.09%   |
| Unifosa             | 4         | 0.07%   |
| Toshiba             | 4         | 0.07%   |
| Kllisre             | 4         | 0.07%   |
| Avant               | 4         | 0.07%   |
| Unknown (0x5846)    | 3         | 0.05%   |
| Teikon              | 3         | 0.05%   |
| Smart Brazil        | 3         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 264       | 4.36%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 142       | 2.35%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.12%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.04%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 61        | 1.01%   |
| Unknown                                                          | 45        | 0.74%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 44        | 0.73%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 0.73%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 40        | 0.66%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 35        | 0.58%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s            | 35        | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 31        | 0.51%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s            | 31        | 0.51%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 30        | 0.5%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 30        | 0.5%    |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.48%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s           | 29        | 0.48%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 28        | 0.46%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 28        | 0.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 27        | 0.45%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 26        | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.43%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 25        | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 25        | 0.41%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.41%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 24        | 0.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 24        | 0.4%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 24        | 0.4%    |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s             | 24        | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 23        | 0.38%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 22        | 0.36%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 22        | 0.36%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.33%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s          | 20        | 0.33%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 20        | 0.33%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 19        | 0.31%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 18        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 2119      | 42.04%  |
| DDR3         | 1652      | 32.77%  |
| DDR2         | 626       | 12.42%  |
| SDRAM        | 177       | 3.51%   |
| Unknown      | 152       | 3.02%   |
| LPDDR4       | 143       | 2.84%   |
| LPDDR3       | 85        | 1.69%   |
| DDR          | 54        | 1.07%   |
| DDR5         | 19        | 0.38%   |
| DRAM         | 8         | 0.16%   |
| LPDDR5       | 5         | 0.1%    |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2907      | 57.84%  |
| DIMM         | 1862      | 37.05%  |
| Row Of Chips | 193       | 3.84%   |
| Chip         | 27        | 0.54%   |
| Unknown      | 27        | 0.54%   |
| FB-DIMM      | 7         | 0.14%   |
| RIMM         | 3         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 1696      | 31.34%  |
| 4096    | 1308      | 24.17%  |
| 2048    | 856       | 15.82%  |
| 16384   | 645       | 11.92%  |
| 1024    | 606       | 11.2%   |
| 32768   | 215       | 3.97%   |
| 512     | 58        | 1.07%   |
| 256     | 17        | 0.31%   |
| 65536   | 7         | 0.13%   |
| 1536    | 1         | 0.02%   |
| 384     | 1         | 0.02%   |
| 128     | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1108      | 20.59%  |
| 3200    | 759       | 14.11%  |
| 2667    | 665       | 12.36%  |
| 800     | 475       | 8.83%   |
| 1333    | 370       | 6.88%   |
| 2400    | 337       | 6.26%   |
| 2133    | 224       | 4.16%   |
| 667     | 194       | 3.61%   |
| Unknown | 151       | 2.81%   |
| 1334    | 112       | 2.08%   |
| 3600    | 88        | 1.64%   |
| 1867    | 73        | 1.36%   |
| 2666    | 72        | 1.34%   |
| 1866    | 67        | 1.25%   |
| 1067    | 63        | 1.17%   |
| 1066    | 51        | 0.95%   |
| 4267    | 45        | 0.84%   |
| 3266    | 44        | 0.82%   |
| 3400    | 36        | 0.67%   |
| 2933    | 36        | 0.67%   |
| 3000    | 29        | 0.54%   |
| 3733    | 28        | 0.52%   |
| 2866    | 26        | 0.48%   |
| 4199    | 23        | 0.43%   |
| 3466    | 23        | 0.43%   |
| 533     | 23        | 0.43%   |
| 4800    | 21        | 0.39%   |
| 2048    | 19        | 0.35%   |
| 1800    | 17        | 0.32%   |
| 400     | 16        | 0.3%    |
| 3800    | 12        | 0.22%   |
| 333     | 12        | 0.22%   |
| 266     | 11        | 0.2%    |
| 3866    | 10        | 0.19%   |
| 8400    | 9         | 0.17%   |
| 4266    | 9         | 0.17%   |
| 3534    | 9         | 0.17%   |
| 975     | 9         | 0.17%   |
| 6400    | 7         | 0.13%   |
| 4333    | 7         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 38        | 32.48%  |
| Brother Industries     | 22        | 18.8%   |
| Canon                  | 15        | 12.82%  |
| Samsung Electronics    | 9         | 7.69%   |
| Xerox                  | 8         | 6.84%   |
| Seiko Epson            | 5         | 4.27%   |
| Dymo-CoStar            | 4         | 3.42%   |
| Prolific Technology    | 3         | 2.56%   |
| Zebra                  | 2         | 1.71%   |
| Pantum                 | 2         | 1.71%   |
| STMicroelectronics     | 1         | 0.85%   |
| QinHeng Electronics    | 1         | 0.85%   |
| Printer                | 1         | 0.85%   |
| Panasonic (Matsushita) | 1         | 0.85%   |
| Lexmark International  | 1         | 0.85%   |
| Kyocera                | 1         | 0.85%   |
| Konica Minolta         | 1         | 0.85%   |
| GODEX INTERNATIONAL    | 1         | 0.85%   |
| Apple                  | 1         | 0.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xerox B205                                                            | 7         | 5.98%   |
| Samsung ML-1660 Series                                                | 3         | 2.56%   |
| Prolific PL2305 Parallel Port                                         | 3         | 2.56%   |
| HP LaserJet M101-M106                                                 | 3         | 2.56%   |
| HP LaserJet 1200                                                      | 3         | 2.56%   |
| HP LaserJet 1020                                                      | 3         | 2.56%   |
| HP LaserJet P1005                                                     | 2         | 1.71%   |
| HP LaserJet 1150                                                      | 2         | 1.71%   |
| HP ENVY 4520 series                                                   | 2         | 1.71%   |
| HP DeskJet 2600 series                                                | 2         | 1.71%   |
| HP DeskJet 2130 series                                                | 2         | 1.71%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 1.71%   |
| Canon PIXMA MX920 Series                                              | 2         | 1.71%   |
| Canon PIXMA MG3600 Series                                             | 2         | 1.71%   |
| Canon MF4410                                                          | 2         | 1.71%   |
| Canon LiDE 400                                                        | 2         | 1.71%   |
| Canon G3010 series                                                    | 2         | 1.71%   |
| Brother PT-9500PC                                                     | 2         | 1.71%   |
| Brother HL-L2395DW series                                             | 2         | 1.71%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.85%   |
| Zebra ZTC ZD420-203dpi ZPL                                            | 1         | 0.85%   |
| Xerox Phaser 3250                                                     | 1         | 0.85%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 0.85%   |
| Seiko Epson XP-200 Series                                             | 1         | 0.85%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.85%   |
| Seiko Epson ET-2850 Series                                            | 1         | 0.85%   |
| Seiko Epson ET-2710 Series                                            | 1         | 0.85%   |
| Seiko Epson ET-2700 Series                                            | 1         | 0.85%   |
| Samsung SCX-4x26 Series                                               | 1         | 0.85%   |
| Samsung SCX-4650 4x21S Series                                         | 1         | 0.85%   |
| Samsung SCX-3200 Series                                               | 1         | 0.85%   |
| Samsung ML-216x Series Laser Printer                                  | 1         | 0.85%   |
| Samsung ML-2010P Mono Laser Printer                                   | 1         | 0.85%   |
| Samsung ML-1520 Laser Printer                                         | 1         | 0.85%   |
| QinHeng CH340S                                                        | 1         | 0.85%   |
| Printer Printer                                                       | 1         | 0.85%   |
| Pantum P2500W series                                                  | 1         | 0.85%   |
| Pantum M6500-series                                                   | 1         | 0.85%   |
| Panasonic (Matsushita) KX-MB1500RU                                    | 1         | 0.85%   |
| Lexmark International MS710                                           | 1         | 0.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 15        | 55.56%  |
| Seiko Epson     | 7         | 25.93%  |
| Hewlett-Packard | 3         | 11.11%  |
| AGFA-Gevaert NV | 2         | 7.41%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                       | 4         | 14.81%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 3         | 11.11%  |
| Canon CanoScan LiDE 120                                       | 2         | 7.41%   |
| Canon CanoScan LiDE 110                                       | 2         | 7.41%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2         | 7.41%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 1         | 3.7%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1         | 3.7%    |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1         | 3.7%    |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 3.7%    |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 3.7%    |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                 | 1         | 3.7%    |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 3.7%    |
| HP ScanJet Pro 2500 f1                                        | 1         | 3.7%    |
| HP ScanJet 3970c                                              | 1         | 3.7%    |
| HP Scanjet 300                                                | 1         | 3.7%    |
| Canon CanoScan LIDE 25                                        | 1         | 3.7%    |
| Canon CanoScan LiDE 210                                       | 1         | 3.7%    |
| Canon CanoScan 8800F                                          | 1         | 3.7%    |
| Canon CanoScan 5600F                                          | 1         | 3.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 635       | 22.6%   |
| IMC Networks                           | 262       | 9.32%   |
| Quanta                                 | 217       | 7.72%   |
| Microdia                               | 199       | 7.08%   |
| Acer                                   | 197       | 7.01%   |
| Realtek Semiconductor                  | 177       | 6.3%    |
| Logitech                               | 161       | 5.73%   |
| Bison Electronics                      | 155       | 5.52%   |
| Sunplus Innovation Technology          | 110       | 3.91%   |
| Apple                                  | 79        | 2.81%   |
| Cheng Uei Precision Industry (Foxlink) | 76        | 2.7%    |
| Suyin                                  | 65        | 2.31%   |
| Lite-On Technology                     | 55        | 1.96%   |
| Syntek                                 | 52        | 1.85%   |
| Luxvisions Innotech Limited            | 51        | 1.81%   |
| Silicon Motion                         | 27        | 0.96%   |
| Alcor Micro                            | 24        | 0.85%   |
| Lenovo                                 | 20        | 0.71%   |
| Z-Star Microelectronics                | 15        | 0.53%   |
| Microsoft                              | 15        | 0.53%   |
| Generalplus Technology                 | 15        | 0.53%   |
| Sonix Technology                       | 13        | 0.46%   |
| Samsung Electronics                    | 12        | 0.43%   |
| Ricoh                                  | 12        | 0.43%   |
| Primax Electronics                     | 10        | 0.36%   |
| Creative Technology                    | 10        | 0.36%   |
| Genesys Logic                          | 9         | 0.32%   |
| Importek                               | 8         | 0.28%   |
| KYE Systems (Mouse Systems)            | 7         | 0.25%   |
| Jieli Technology                       | 7         | 0.25%   |
| ARC International                      | 7         | 0.25%   |
| SunplusIT                              | 6         | 0.21%   |
| Intel                                  | 5         | 0.18%   |
| ALi                                    | 5         | 0.18%   |
| Y Media                                | 4         | 0.14%   |
| USB Camera                             | 4         | 0.14%   |
| MacroSilicon                           | 4         | 0.14%   |
| GEMBIRD                                | 4         | 0.14%   |
| webcam                                 | 3         | 0.11%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 206       | 7.2%    |
| Bison Integrated Camera                             | 105       | 3.67%   |
| Microdia Integrated_Webcam_HD                       | 91        | 3.18%   |
| IMC Networks Integrated Camera                      | 82        | 2.87%   |
| Bison Integrated 5M Camera                          | 73        | 2.55%   |
| Quanta Lenovo EasyCamera                            | 68        | 2.38%   |
| Realtek Integrated_Webcam_HD                        | 64        | 2.24%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 61        | 2.13%   |
| Acer BisonCam, NB Pro                               | 53        | 1.85%   |
| Logitech Webcam C270                                | 48        | 1.68%   |
| Chicony HD WebCam                                   | 47        | 1.64%   |
| Chicony Integrated 5M Camera                        | 43        | 1.5%    |
| Sunplus Integrated_Webcam_HD                        | 38        | 1.33%   |
| Acer Integrated Camera                              | 35        | 1.22%   |
| Chicony USB2.0 HD UVC WebCam                        | 34        | 1.19%   |
| Chicony HP HD Camera                                | 31        | 1.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 28        | 0.98%   |
| Syntek Integrated Camera                            | 27        | 0.94%   |
| Quanta HD User Facing                               | 26        | 0.91%   |
| Apple Built-in iSight                               | 26        | 0.91%   |
| Quanta HP TrueVision HD Camera                      | 25        | 0.87%   |
| Quanta VGA WebCam                                   | 24        | 0.84%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 21        | 0.73%   |
| Microdia Integrated Webcam                          | 20        | 0.7%    |
| Acer SunplusIT Integrated Camera                    | 20        | 0.7%    |
| Quanta HP HD Camera                                 | 19        | 0.66%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 19        | 0.66%   |
| Realtek USB Camera                                  | 18        | 0.63%   |
| Logitech HD Pro Webcam C920                         | 18        | 0.63%   |
| Lite-On Integrated Camera                           | 18        | 0.63%   |
| Lite-On HP HD Camera                                | 17        | 0.59%   |
| Chicony Integrated Camera (1280x720@30)             | 17        | 0.59%   |
| Apple FaceTime HD Camera (Built-in)                 | 17        | 0.59%   |
| Microdia USB 2.0 Camera                             | 16        | 0.56%   |
| Chicony HP TrueVision HD Camera                     | 16        | 0.56%   |
| Acer Lenovo EasyCamera                              | 16        | 0.56%   |
| Luxvisions Innotech Limited HP HD Camera            | 15        | 0.52%   |
| Chicony HD User Facing                              | 15        | 0.52%   |
| Chicony Chromebook HD Camera                        | 15        | 0.52%   |
| Acer Lenovo Integrated Webcam                       | 15        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 272       | 45.33%  |
| Validity Sensors                   | 166       | 27.67%  |
| Shenzhen Goodix Technology         | 69        | 11.5%   |
| Upek                               | 24        | 4%      |
| Elan Microelectronics              | 23        | 3.83%   |
| AuthenTec                          | 21        | 3.5%    |
| LighTuning Technology              | 14        | 2.33%   |
| STMicroelectronics                 | 9         | 1.5%    |
| Samsung Electronics                | 1         | 0.17%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 176       | 29.33%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 39        | 6.5%    |
| Shenzhen Goodix  Fingerprint Device                                        | 38        | 6.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 31        | 5.17%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 29        | 4.83%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 3.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 3.5%    |
| Validity Sensors Synaptics WBDI                                            | 18        | 3%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 17        | 2.83%   |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 2.67%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 2.5%    |
| Elan ELAN:Fingerprint                                                      | 14        | 2.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 13        | 2.17%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 1.83%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.5%    |
| Elan ELAN:ARM-M4                                                           | 9         | 1.5%    |
| Validity Sensors VFS491                                                    | 8         | 1.33%   |
| Synaptics  WBDI                                                            | 8         | 1.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 8         | 1.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.17%   |
| Synaptics WBDI                                                             | 7         | 1.17%   |
| Synaptics UWP WBDI                                                         | 7         | 1.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 1.17%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1%      |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1%      |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 0.83%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.67%   |
| AuthenTec AES2810                                                          | 4         | 0.67%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.5%    |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.5%    |
| Validity Sensors Fingerprint scanner                                       | 3         | 0.5%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.33%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.33%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.33%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.33%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.33%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 87        | 34.25%  |
| Alcor Micro               | 86        | 33.86%  |
| Upek                      | 20        | 7.87%   |
| O2 Micro                  | 20        | 7.87%   |
| Lenovo                    | 15        | 5.91%   |
| SCM Microsystems          | 5         | 1.97%   |
| Gemalto (was Gemplus)     | 5         | 1.97%   |
| Yubico.com                | 3         | 1.18%   |
| Clay Logic                | 2         | 0.79%   |
| Cherry                    | 2         | 0.79%   |
| Aladdin Knowledge Systems | 2         | 0.79%   |
| Advanced Card Systems     | 2         | 0.79%   |
| Reiner SCT Kartensysteme  | 1         | 0.39%   |
| OmniKey                   | 1         | 0.39%   |
| Feitian Technologies      | 1         | 0.39%   |
| Chicony Electronics       | 1         | 0.39%   |
| C3PO                      | 1         | 0.39%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 84        | 33.07%  |
| Broadcom 58200                                                               | 27        | 10.63%  |
| Broadcom BCM5880 Secure Applications Processor                               | 26        | 10.24%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 20        | 7.87%   |
| Broadcom 5880                                                                | 19        | 7.48%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 17        | 6.69%   |
| Lenovo Integrated Smart Card Reader                                          | 14        | 5.51%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 5.12%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.18%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.18%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.79%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.79%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.79%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.79%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.79%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.79%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.79%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.39%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.39%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.39%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.39%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.39%   |
| OmniKey CardMan 4321                                                         | 1         | 0.39%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.39%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.39%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.39%   |
| Feitian Technologies SCR301                                                  | 1         | 0.39%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.39%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.39%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.39%   |
| C3PO LTC31v2                                                                 | 1         | 0.39%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3419      | 57.45%  |
| 1     | 2054      | 34.52%  |
| 2     | 384       | 6.45%   |
| 3     | 74        | 1.24%   |
| 4     | 13        | 0.22%   |
| 5     | 5         | 0.08%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1320      | 44.72%  |
| Fingerprint reader       | 598       | 20.26%  |
| Chipcard                 | 228       | 7.72%   |
| Net/wireless             | 227       | 7.69%   |
| Multimedia controller    | 226       | 7.66%   |
| Communication controller | 105       | 3.56%   |
| Unassigned class         | 62        | 2.1%    |
| Bluetooth                | 41        | 1.39%   |
| Sound                    | 27        | 0.91%   |
| Card reader              | 24        | 0.81%   |
| Storage                  | 23        | 0.78%   |
| Camera                   | 23        | 0.78%   |
| Net/ethernet             | 15        | 0.51%   |
| Network                  | 8         | 0.27%   |
| Modem                    | 7         | 0.24%   |
| Storage/raid             | 6         | 0.2%    |
| Tv card                  | 4         | 0.14%   |
| Flash memory             | 3         | 0.1%    |
| Firewire controller      | 2         | 0.07%   |
| Dvb card                 | 2         | 0.07%   |
| Storage/ide              | 1         | 0.03%   |

