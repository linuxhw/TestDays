Linux in France - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in France.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/France/Desktop/README.md) and [notebooks](/Location/France/Notebook/README.md).

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

Total: 13990

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [8a05090057](https://linux-hardware.org/?probe=8a05090057) | Sep 07, 2023 |
| MSI           | B360M GAMING PLUS           | Desktop     | [1faaa87b61](https://linux-hardware.org/?probe=1faaa87b61) | Sep 07, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [f47dacb739](https://linux-hardware.org/?probe=f47dacb739) | Sep 07, 2023 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [b11a7b69f0](https://linux-hardware.org/?probe=b11a7b69f0) | Sep 07, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [78bdf275c2](https://linux-hardware.org/?probe=78bdf275c2) | Sep 07, 2023 |
| Dell          | Latitude 7420               | Notebook    | [77df1805f6](https://linux-hardware.org/?probe=77df1805f6) | Sep 07, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [f98e7f20ca](https://linux-hardware.org/?probe=f98e7f20ca) | Sep 06, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [849ecb3c82](https://linux-hardware.org/?probe=849ecb3c82) | Sep 06, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [c9f30a2b26](https://linux-hardware.org/?probe=c9f30a2b26) | Sep 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [03e260aff4](https://linux-hardware.org/?probe=03e260aff4) | Sep 06, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c890510220](https://linux-hardware.org/?probe=c890510220) | Sep 06, 2023 |
| Dell          | 0NK5PH A01                  | Desktop     | [49e0ac3e09](https://linux-hardware.org/?probe=49e0ac3e09) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [2505f514b1](https://linux-hardware.org/?probe=2505f514b1) | Sep 06, 2023 |
| MSI           | GS60 2PC Ghost              | Notebook    | [0b971b067a](https://linux-hardware.org/?probe=0b971b067a) | Sep 06, 2023 |
| HP            | 844C                        | Desktop     | [6f4911cda7](https://linux-hardware.org/?probe=6f4911cda7) | Sep 06, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [51202f2fd7](https://linux-hardware.org/?probe=51202f2fd7) | Sep 06, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [c31e15f2ba](https://linux-hardware.org/?probe=c31e15f2ba) | Sep 05, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [6515c97b89](https://linux-hardware.org/?probe=6515c97b89) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [23f0f9321c](https://linux-hardware.org/?probe=23f0f9321c) | Sep 05, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [cd4ccc8478](https://linux-hardware.org/?probe=cd4ccc8478) | Sep 05, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [70d0d79f77](https://linux-hardware.org/?probe=70d0d79f77) | Sep 05, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d16f2005c0](https://linux-hardware.org/?probe=d16f2005c0) | Sep 05, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [f1c877be0e](https://linux-hardware.org/?probe=f1c877be0e) | Sep 05, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [1fce93cab3](https://linux-hardware.org/?probe=1fce93cab3) | Sep 05, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming-... | Desktop     | [77c07d0f70](https://linux-hardware.org/?probe=77c07d0f70) | Sep 05, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming-... | Desktop     | [a0aaf4be5d](https://linux-hardware.org/?probe=a0aaf4be5d) | Sep 05, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [59b9a21678](https://linux-hardware.org/?probe=59b9a21678) | Sep 04, 2023 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [ea823862a6](https://linux-hardware.org/?probe=ea823862a6) | Sep 04, 2023 |
| HP            | 198E                        | Desktop     | [7f57cfbacc](https://linux-hardware.org/?probe=7f57cfbacc) | Sep 04, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [49e3c842c1](https://linux-hardware.org/?probe=49e3c842c1) | Sep 04, 2023 |
| Samsung       | 950XED                      | Notebook    | [3d8ba5a34c](https://linux-hardware.org/?probe=3d8ba5a34c) | Sep 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [02c4374b47](https://linux-hardware.org/?probe=02c4374b47) | Sep 04, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [1242798344](https://linux-hardware.org/?probe=1242798344) | Sep 04, 2023 |
| ASUSTek       | VM42                        | Desktop     | [2869496e53](https://linux-hardware.org/?probe=2869496e53) | Sep 04, 2023 |
| eMachines     | Rhine V1.42                 | Notebook    | [c18c4d64bd](https://linux-hardware.org/?probe=c18c4d64bd) | Sep 04, 2023 |
| Dell          | 05WNJ2 A02                  | Server      | [7b59f7f1d7](https://linux-hardware.org/?probe=7b59f7f1d7) | Sep 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [d5f8d13304](https://linux-hardware.org/?probe=d5f8d13304) | Sep 04, 2023 |
| Dell          | Vostro 14 3435              | Notebook    | [d35ddd8539](https://linux-hardware.org/?probe=d35ddd8539) | Sep 04, 2023 |
| Dell          | Vostro 14 3435              | Notebook    | [34a27b9c29](https://linux-hardware.org/?probe=34a27b9c29) | Sep 04, 2023 |
| Dell          | Precision 3581              | Notebook    | [739b270d83](https://linux-hardware.org/?probe=739b270d83) | Sep 04, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [9918661e50](https://linux-hardware.org/?probe=9918661e50) | Sep 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ0E    | Notebook    | [c5cdf73aa5](https://linux-hardware.org/?probe=c5cdf73aa5) | Sep 04, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [9bacefd984](https://linux-hardware.org/?probe=9bacefd984) | Sep 04, 2023 |
| HP            | 8298                        | Desktop     | [49d5421cb5](https://linux-hardware.org/?probe=49d5421cb5) | Sep 03, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e30eaf0d9a](https://linux-hardware.org/?probe=e30eaf0d9a) | Sep 03, 2023 |
| Intel         | NUC8i7HNB J68197-603        | Mini pc     | [cfa756b2c1](https://linux-hardware.org/?probe=cfa756b2c1) | Sep 03, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [95b036ac9a](https://linux-hardware.org/?probe=95b036ac9a) | Sep 03, 2023 |
| Dell          | Latitude E6400              | Notebook    | [88a04ab4b8](https://linux-hardware.org/?probe=88a04ab4b8) | Sep 03, 2023 |
| Dell          | Latitude E6400              | Notebook    | [56cc7d7a27](https://linux-hardware.org/?probe=56cc7d7a27) | Sep 03, 2023 |
| Samsung       | R510/P510                   | Notebook    | [fa457144d5](https://linux-hardware.org/?probe=fa457144d5) | Sep 03, 2023 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [16eb26e2bc](https://linux-hardware.org/?probe=16eb26e2bc) | Sep 03, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [89d5a9b606](https://linux-hardware.org/?probe=89d5a9b606) | Sep 03, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [89dcb5988f](https://linux-hardware.org/?probe=89dcb5988f) | Sep 03, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [c98b2d5aba](https://linux-hardware.org/?probe=c98b2d5aba) | Sep 03, 2023 |
| Dell          | 0GK35Y A00                  | Desktop     | [d785138af0](https://linux-hardware.org/?probe=d785138af0) | Sep 03, 2023 |
| MSI           | GF63 Thin 9SC               | Notebook    | [510641439b](https://linux-hardware.org/?probe=510641439b) | Sep 03, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [1468567e45](https://linux-hardware.org/?probe=1468567e45) | Sep 03, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [8552bc9508](https://linux-hardware.org/?probe=8552bc9508) | Sep 03, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [8146fce36b](https://linux-hardware.org/?probe=8146fce36b) | Sep 03, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [7ebd20a049](https://linux-hardware.org/?probe=7ebd20a049) | Sep 03, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9903b0fbea](https://linux-hardware.org/?probe=9903b0fbea) | Sep 03, 2023 |
| EUROCOM       | RAPTOR X17                  | Notebook    | [93827ff6f1](https://linux-hardware.org/?probe=93827ff6f1) | Sep 03, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [3a5fd5b62b](https://linux-hardware.org/?probe=3a5fd5b62b) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [5ed468ca65](https://linux-hardware.org/?probe=5ed468ca65) | Sep 03, 2023 |
| Dell          | Latitude E6400              | Notebook    | [d669a79662](https://linux-hardware.org/?probe=d669a79662) | Sep 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [88673d4088](https://linux-hardware.org/?probe=88673d4088) | Sep 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6ed47558ae](https://linux-hardware.org/?probe=6ed47558ae) | Sep 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [976846f5c4](https://linux-hardware.org/?probe=976846f5c4) | Sep 03, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [57bb5d91ab](https://linux-hardware.org/?probe=57bb5d91ab) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [ca5351b378](https://linux-hardware.org/?probe=ca5351b378) | Sep 03, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [c5787921e3](https://linux-hardware.org/?probe=c5787921e3) | Sep 03, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [cdfa5060e6](https://linux-hardware.org/?probe=cdfa5060e6) | Sep 03, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [174cff0e19](https://linux-hardware.org/?probe=174cff0e19) | Sep 02, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [762498a914](https://linux-hardware.org/?probe=762498a914) | Sep 02, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b161a13302](https://linux-hardware.org/?probe=b161a13302) | Sep 02, 2023 |
| Timi          | TM1612                      | Notebook    | [b78b28d40d](https://linux-hardware.org/?probe=b78b28d40d) | Sep 02, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [6a4908587f](https://linux-hardware.org/?probe=6a4908587f) | Sep 02, 2023 |
| HP            | 2B2C                        | Desktop     | [a24d61a0f4](https://linux-hardware.org/?probe=a24d61a0f4) | Sep 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c3fe8cb8e9](https://linux-hardware.org/?probe=c3fe8cb8e9) | Sep 02, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [84cd7c1a93](https://linux-hardware.org/?probe=84cd7c1a93) | Sep 02, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [b9d50bc865](https://linux-hardware.org/?probe=b9d50bc865) | Sep 02, 2023 |
| Dell          | 02C2CP A01                  | Server      | [8928318f7a](https://linux-hardware.org/?probe=8928318f7a) | Sep 02, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [02c6b100f0](https://linux-hardware.org/?probe=02c6b100f0) | Sep 02, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [e0133bb14e](https://linux-hardware.org/?probe=e0133bb14e) | Sep 02, 2023 |
| HP            | 198E                        | Desktop     | [3f3cb2e64c](https://linux-hardware.org/?probe=3f3cb2e64c) | Sep 02, 2023 |
| Schenker      | VIA 15 Pro                  | Notebook    | [4a31ab4d2b](https://linux-hardware.org/?probe=4a31ab4d2b) | Sep 02, 2023 |
| MSI           | GP70 2OD                    | Notebook    | [4bc109f9a0](https://linux-hardware.org/?probe=4bc109f9a0) | Sep 02, 2023 |
| Sony          | SVE1513I4E                  | Notebook    | [a1009ff0be](https://linux-hardware.org/?probe=a1009ff0be) | Sep 02, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [6decc4abdd](https://linux-hardware.org/?probe=6decc4abdd) | Sep 01, 2023 |
| Acer          | Veriton M4610G              | Desktop     | [a5e1bdfce5](https://linux-hardware.org/?probe=a5e1bdfce5) | Sep 01, 2023 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [35a0110255](https://linux-hardware.org/?probe=35a0110255) | Sep 01, 2023 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [0075af1992](https://linux-hardware.org/?probe=0075af1992) | Sep 01, 2023 |
| Dell          | Latitude 7480               | Notebook    | [6c5351c835](https://linux-hardware.org/?probe=6c5351c835) | Sep 01, 2023 |
| Dell          | Latitude 7480               | Notebook    | [41fb46fed8](https://linux-hardware.org/?probe=41fb46fed8) | Sep 01, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [24d0eafc15](https://linux-hardware.org/?probe=24d0eafc15) | Sep 01, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [b2effdc956](https://linux-hardware.org/?probe=b2effdc956) | Sep 01, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [35df364c39](https://linux-hardware.org/?probe=35df364c39) | Sep 01, 2023 |
| AZW           | U59                         | Desktop     | [4cca42eeb3](https://linux-hardware.org/?probe=4cca42eeb3) | Sep 01, 2023 |
| Sony          | SVE1513I4E                  | Notebook    | [404c008e41](https://linux-hardware.org/?probe=404c008e41) | Sep 01, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [8ee240ba0b](https://linux-hardware.org/?probe=8ee240ba0b) | Sep 01, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [6010a74736](https://linux-hardware.org/?probe=6010a74736) | Sep 01, 2023 |
| Fanless Mi... | Rev JSL8                    | Mini pc     | [54433f96fd](https://linux-hardware.org/?probe=54433f96fd) | Sep 01, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [ce1e538f59](https://linux-hardware.org/?probe=ce1e538f59) | Sep 01, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [406d9fd5fc](https://linux-hardware.org/?probe=406d9fd5fc) | Sep 01, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b0f558c0a2](https://linux-hardware.org/?probe=b0f558c0a2) | Aug 31, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [43c2d13a44](https://linux-hardware.org/?probe=43c2d13a44) | Aug 31, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [a6619c179c](https://linux-hardware.org/?probe=a6619c179c) | Aug 31, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [c5fc2337ec](https://linux-hardware.org/?probe=c5fc2337ec) | Aug 31, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [b1571fcf3b](https://linux-hardware.org/?probe=b1571fcf3b) | Aug 31, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [cb84df3a99](https://linux-hardware.org/?probe=cb84df3a99) | Aug 31, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [dbc3edd473](https://linux-hardware.org/?probe=dbc3edd473) | Aug 31, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [b4eb252e8f](https://linux-hardware.org/?probe=b4eb252e8f) | Aug 31, 2023 |
| ASUSTek       | P5N-E SLI                   | Desktop     | [04688c03ea](https://linux-hardware.org/?probe=04688c03ea) | Aug 31, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [408707e9e6](https://linux-hardware.org/?probe=408707e9e6) | Aug 31, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [b00577f6ea](https://linux-hardware.org/?probe=b00577f6ea) | Aug 31, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [7de2ff1052](https://linux-hardware.org/?probe=7de2ff1052) | Aug 30, 2023 |
| ASUSTek       | K501LX                      | Notebook    | [ca56f1b803](https://linux-hardware.org/?probe=ca56f1b803) | Aug 30, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [b8492993cf](https://linux-hardware.org/?probe=b8492993cf) | Aug 30, 2023 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [9a95d4ab16](https://linux-hardware.org/?probe=9a95d4ab16) | Aug 30, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [76eb125a56](https://linux-hardware.org/?probe=76eb125a56) | Aug 30, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [a65c8bb631](https://linux-hardware.org/?probe=a65c8bb631) | Aug 30, 2023 |
| ASUSTek       | Zenbook UX6404VV_UX6404V... | Notebook    | [b7be264a8d](https://linux-hardware.org/?probe=b7be264a8d) | Aug 30, 2023 |
| ASUSTek       | A88XM-E/USB                 | Desktop     | [376615315b](https://linux-hardware.org/?probe=376615315b) | Aug 30, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [cab1480dc6](https://linux-hardware.org/?probe=cab1480dc6) | Aug 30, 2023 |
| Toshiba       | Satellite P50-B-113         | Notebook    | [a9f21477c8](https://linux-hardware.org/?probe=a9f21477c8) | Aug 30, 2023 |
| HP            | 876C SMVB                   | Desktop     | [246cb7a1ca](https://linux-hardware.org/?probe=246cb7a1ca) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ab3c1508f9](https://linux-hardware.org/?probe=ab3c1508f9) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2906fc34f6](https://linux-hardware.org/?probe=2906fc34f6) | Aug 30, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b61285544c](https://linux-hardware.org/?probe=b61285544c) | Aug 30, 2023 |
| Dell          | Latitude E5510              | Notebook    | [61f6df7426](https://linux-hardware.org/?probe=61f6df7426) | Aug 29, 2023 |
| HP            | Pavilion 17                 | Notebook    | [ba077d7ea1](https://linux-hardware.org/?probe=ba077d7ea1) | Aug 29, 2023 |
| HP            | 83EE                        | Desktop     | [d558afff67](https://linux-hardware.org/?probe=d558afff67) | Aug 29, 2023 |
| ASUSTek       | Zenbook UP5401ZA_UP5401Z... | Convertible | [63414c002c](https://linux-hardware.org/?probe=63414c002c) | Aug 29, 2023 |
| Dell          | Precision 5480              | Notebook    | [5fd5bf187d](https://linux-hardware.org/?probe=5fd5bf187d) | Aug 29, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [dadd0516b5](https://linux-hardware.org/?probe=dadd0516b5) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430 2349H86       | Notebook    | [6ed258911c](https://linux-hardware.org/?probe=6ed258911c) | Aug 29, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [9450749b35](https://linux-hardware.org/?probe=9450749b35) | Aug 29, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [b4acaedb21](https://linux-hardware.org/?probe=b4acaedb21) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0f3d530e12](https://linux-hardware.org/?probe=0f3d530e12) | Aug 29, 2023 |
| Lenovo        | IdeaPad Slim 3 14ABR8 82... | Notebook    | [4fa3f56511](https://linux-hardware.org/?probe=4fa3f56511) | Aug 29, 2023 |
| Lenovo        | IdeaPad Slim 3 14ABR8 82... | Notebook    | [9bf240bf4d](https://linux-hardware.org/?probe=9bf240bf4d) | Aug 29, 2023 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [7ac77b7bac](https://linux-hardware.org/?probe=7ac77b7bac) | Aug 28, 2023 |
| Dell          | Latitude E4310              | Notebook    | [03b37a1c55](https://linux-hardware.org/?probe=03b37a1c55) | Aug 28, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [f37ab96772](https://linux-hardware.org/?probe=f37ab96772) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [d2caf1942c](https://linux-hardware.org/?probe=d2caf1942c) | Aug 28, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [8b814da79a](https://linux-hardware.org/?probe=8b814da79a) | Aug 28, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [f54073855c](https://linux-hardware.org/?probe=f54073855c) | Aug 28, 2023 |
| Dell          | Precision 3520              | Notebook    | [a87048ecac](https://linux-hardware.org/?probe=a87048ecac) | Aug 28, 2023 |
| Dell          | Precision 3520              | Notebook    | [6afb6bacac](https://linux-hardware.org/?probe=6afb6bacac) | Aug 28, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [4bcfe8de49](https://linux-hardware.org/?probe=4bcfe8de49) | Aug 28, 2023 |
| HP            | 83EF                        | Desktop     | [05c3bcb04f](https://linux-hardware.org/?probe=05c3bcb04f) | Aug 28, 2023 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [79803f8898](https://linux-hardware.org/?probe=79803f8898) | Aug 28, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [22d4876142](https://linux-hardware.org/?probe=22d4876142) | Aug 28, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [60fddabe34](https://linux-hardware.org/?probe=60fddabe34) | Aug 28, 2023 |
| Corsair       | Voyager a1600               | Notebook    | [405bce7897](https://linux-hardware.org/?probe=405bce7897) | Aug 27, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [450512bee1](https://linux-hardware.org/?probe=450512bee1) | Aug 27, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a83bd371c4](https://linux-hardware.org/?probe=a83bd371c4) | Aug 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [90474aa183](https://linux-hardware.org/?probe=90474aa183) | Aug 27, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [e58ca6a781](https://linux-hardware.org/?probe=e58ca6a781) | Aug 27, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a571d0670](https://linux-hardware.org/?probe=9a571d0670) | Aug 27, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [033aa63d16](https://linux-hardware.org/?probe=033aa63d16) | Aug 27, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [e5600a4d2f](https://linux-hardware.org/?probe=e5600a4d2f) | Aug 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [97caef0e98](https://linux-hardware.org/?probe=97caef0e98) | Aug 27, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [3176d728c4](https://linux-hardware.org/?probe=3176d728c4) | Aug 27, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [cc91bf6584](https://linux-hardware.org/?probe=cc91bf6584) | Aug 27, 2023 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [4a3a5eb408](https://linux-hardware.org/?probe=4a3a5eb408) | Aug 27, 2023 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [81636f5198](https://linux-hardware.org/?probe=81636f5198) | Aug 27, 2023 |
| Corsair       | Voyager a1600               | Notebook    | [97a1c576f7](https://linux-hardware.org/?probe=97a1c576f7) | Aug 26, 2023 |
| HP            | 1495                        | Desktop     | [86b148e011](https://linux-hardware.org/?probe=86b148e011) | Aug 26, 2023 |
| ASUSTek       | Z10PE-D8 WS                 | Desktop     | [206043f3a7](https://linux-hardware.org/?probe=206043f3a7) | Aug 26, 2023 |
| HP            | Pavilion 17                 | Notebook    | [1d04c114d6](https://linux-hardware.org/?probe=1d04c114d6) | Aug 26, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [6a38c0266f](https://linux-hardware.org/?probe=6a38c0266f) | Aug 26, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [0620b43b6a](https://linux-hardware.org/?probe=0620b43b6a) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [211472aacc](https://linux-hardware.org/?probe=211472aacc) | Aug 26, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [88ab580175](https://linux-hardware.org/?probe=88ab580175) | Aug 26, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [c957b259a2](https://linux-hardware.org/?probe=c957b259a2) | Aug 26, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7a522c6b71](https://linux-hardware.org/?probe=7a522c6b71) | Aug 25, 2023 |
| MSI           | B150 GAMING M3              | Desktop     | [5a1ef4b710](https://linux-hardware.org/?probe=5a1ef4b710) | Aug 25, 2023 |
| Lenovo        | ThinkPad L580 20LXS1D100    | Notebook    | [f30a161506](https://linux-hardware.org/?probe=f30a161506) | Aug 25, 2023 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [5457261ab6](https://linux-hardware.org/?probe=5457261ab6) | Aug 25, 2023 |
| Lenovo        | ThinkPad T460 20FN003LFR    | Notebook    | [b6a67bea6a](https://linux-hardware.org/?probe=b6a67bea6a) | Aug 25, 2023 |
| ASUSTek       | M32CD4-K                    | Desktop     | [2a4c3a0031](https://linux-hardware.org/?probe=2a4c3a0031) | Aug 25, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [7726b35ef6](https://linux-hardware.org/?probe=7726b35ef6) | Aug 25, 2023 |
| HP            | Notebook                    | Notebook    | [c3ae6b2ed1](https://linux-hardware.org/?probe=c3ae6b2ed1) | Aug 25, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [2647e2edd8](https://linux-hardware.org/?probe=2647e2edd8) | Aug 24, 2023 |
| Acer          | Aspire XC-705               | Desktop     | [abb2a529c7](https://linux-hardware.org/?probe=abb2a529c7) | Aug 24, 2023 |
| Acer          | Aspire XC-705               | Desktop     | [1e42c10a2f](https://linux-hardware.org/?probe=1e42c10a2f) | Aug 24, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [6486781183](https://linux-hardware.org/?probe=6486781183) | Aug 24, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [e154995d9e](https://linux-hardware.org/?probe=e154995d9e) | Aug 24, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [caecc0c140](https://linux-hardware.org/?probe=caecc0c140) | Aug 24, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [0aaf8b7985](https://linux-hardware.org/?probe=0aaf8b7985) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [d3efd68f2f](https://linux-hardware.org/?probe=d3efd68f2f) | Aug 24, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | Desktop     | [18fdc0c2a2](https://linux-hardware.org/?probe=18fdc0c2a2) | Aug 24, 2023 |
| LDLC          | SPC-I                       | Notebook    | [bb114215e6](https://linux-hardware.org/?probe=bb114215e6) | Aug 24, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [85e74676ed](https://linux-hardware.org/?probe=85e74676ed) | Aug 24, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [bc15f84b8c](https://linux-hardware.org/?probe=bc15f84b8c) | Aug 24, 2023 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [17525a9aef](https://linux-hardware.org/?probe=17525a9aef) | Aug 24, 2023 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [86ca529583](https://linux-hardware.org/?probe=86ca529583) | Aug 23, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [a3de2e9813](https://linux-hardware.org/?probe=a3de2e9813) | Aug 23, 2023 |
| HP            | 870C                        | Desktop     | [e0f1f3de1f](https://linux-hardware.org/?probe=e0f1f3de1f) | Aug 23, 2023 |
| Intel         | DZ77BH-55K AAG39008-400     | Desktop     | [30c81f585a](https://linux-hardware.org/?probe=30c81f585a) | Aug 23, 2023 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [2d16969538](https://linux-hardware.org/?probe=2d16969538) | Aug 23, 2023 |
| Dell          | 0NK5PH A01                  | Desktop     | [3a15964324](https://linux-hardware.org/?probe=3a15964324) | Aug 23, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [e0770fc916](https://linux-hardware.org/?probe=e0770fc916) | Aug 23, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [7ab825e697](https://linux-hardware.org/?probe=7ab825e697) | Aug 23, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [c5ea9af7cd](https://linux-hardware.org/?probe=c5ea9af7cd) | Aug 23, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [6f0e38b5e8](https://linux-hardware.org/?probe=6f0e38b5e8) | Aug 23, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [25729bd4f8](https://linux-hardware.org/?probe=25729bd4f8) | Aug 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [824c7b257e](https://linux-hardware.org/?probe=824c7b257e) | Aug 23, 2023 |
| Dell          | 0M858N A01                  | Desktop     | [f8f62c1afb](https://linux-hardware.org/?probe=f8f62c1afb) | Aug 23, 2023 |
| LG Electro... | 16T90R-K.ADB9U1             | Convertible | [e5dedec56d](https://linux-hardware.org/?probe=e5dedec56d) | Aug 23, 2023 |
| MSI           | Stealth 17Studio A13VF      | Notebook    | [ca952946e9](https://linux-hardware.org/?probe=ca952946e9) | Aug 23, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [be00a84105](https://linux-hardware.org/?probe=be00a84105) | Aug 22, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [65747a7530](https://linux-hardware.org/?probe=65747a7530) | Aug 22, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [9ad109a4df](https://linux-hardware.org/?probe=9ad109a4df) | Aug 22, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [73c6fa6546](https://linux-hardware.org/?probe=73c6fa6546) | Aug 22, 2023 |
| Toshiba       | Satellite P500              | Notebook    | [41efb0cb7b](https://linux-hardware.org/?probe=41efb0cb7b) | Aug 22, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [044deb0ad2](https://linux-hardware.org/?probe=044deb0ad2) | Aug 22, 2023 |
| Dell          | Latitude E7270              | Notebook    | [9eaaeb2503](https://linux-hardware.org/?probe=9eaaeb2503) | Aug 22, 2023 |
| Dell          | Latitude 5400               | Notebook    | [2036f8dd50](https://linux-hardware.org/?probe=2036f8dd50) | Aug 21, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [210e9d3b38](https://linux-hardware.org/?probe=210e9d3b38) | Aug 21, 2023 |
| Dell          | Latitude 7310               | Notebook    | [f32da77ac4](https://linux-hardware.org/?probe=f32da77ac4) | Aug 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [43d120af0e](https://linux-hardware.org/?probe=43d120af0e) | Aug 21, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [87c6b8d057](https://linux-hardware.org/?probe=87c6b8d057) | Aug 21, 2023 |
| HP            | ProBook 4730s               | Notebook    | [5b4d88bc67](https://linux-hardware.org/?probe=5b4d88bc67) | Aug 21, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [0bf0d8e338](https://linux-hardware.org/?probe=0bf0d8e338) | Aug 21, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [d4f90e5eff](https://linux-hardware.org/?probe=d4f90e5eff) | Aug 21, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [8cdca3eca4](https://linux-hardware.org/?probe=8cdca3eca4) | Aug 20, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [76b5b9e85d](https://linux-hardware.org/?probe=76b5b9e85d) | Aug 20, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [bd2639e592](https://linux-hardware.org/?probe=bd2639e592) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d355f1941a](https://linux-hardware.org/?probe=d355f1941a) | Aug 20, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [30b645c7f4](https://linux-hardware.org/?probe=30b645c7f4) | Aug 20, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [47ed3b6bc8](https://linux-hardware.org/?probe=47ed3b6bc8) | Aug 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [9d10830c14](https://linux-hardware.org/?probe=9d10830c14) | Aug 20, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [0887b2e549](https://linux-hardware.org/?probe=0887b2e549) | Aug 20, 2023 |
| Dell          | Latitude E5520              | Notebook    | [35f02a2ea2](https://linux-hardware.org/?probe=35f02a2ea2) | Aug 19, 2023 |
| Gigabyte      | GA-N680SLI-DQ6              | Desktop     | [0838a31aaf](https://linux-hardware.org/?probe=0838a31aaf) | Aug 19, 2023 |
| Danew         | Dbook 131                   | Notebook    | [35ea124809](https://linux-hardware.org/?probe=35ea124809) | Aug 19, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [5768055184](https://linux-hardware.org/?probe=5768055184) | Aug 19, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [f8c85e442f](https://linux-hardware.org/?probe=f8c85e442f) | Aug 19, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [c8eaccabf2](https://linux-hardware.org/?probe=c8eaccabf2) | Aug 18, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [e5b049be3a](https://linux-hardware.org/?probe=e5b049be3a) | Aug 18, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [fdc761a52c](https://linux-hardware.org/?probe=fdc761a52c) | Aug 18, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [3dfc4104a4](https://linux-hardware.org/?probe=3dfc4104a4) | Aug 18, 2023 |
| Toshiba       | Satellite Pro C850-10N      | Notebook    | [590ac28f26](https://linux-hardware.org/?probe=590ac28f26) | Aug 18, 2023 |
| Dell          | Latitude 5420               | Notebook    | [6a758f4880](https://linux-hardware.org/?probe=6a758f4880) | Aug 18, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [687a84cc8b](https://linux-hardware.org/?probe=687a84cc8b) | Aug 18, 2023 |
| Dell          | Latitude 7300               | Notebook    | [607cb8c677](https://linux-hardware.org/?probe=607cb8c677) | Aug 18, 2023 |
| Dell          | Inspiron 7591               | Notebook    | [2e09db6501](https://linux-hardware.org/?probe=2e09db6501) | Aug 18, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [63a0a35452](https://linux-hardware.org/?probe=63a0a35452) | Aug 18, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [6b5f510903](https://linux-hardware.org/?probe=6b5f510903) | Aug 18, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [6fb9870620](https://linux-hardware.org/?probe=6fb9870620) | Aug 18, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [607356bb8f](https://linux-hardware.org/?probe=607356bb8f) | Aug 17, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [4368fbfada](https://linux-hardware.org/?probe=4368fbfada) | Aug 17, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [b07665aa45](https://linux-hardware.org/?probe=b07665aa45) | Aug 17, 2023 |
| Lenovo        | ThinkPad T430 2349TFK       | Notebook    | [390899a281](https://linux-hardware.org/?probe=390899a281) | Aug 17, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [ed669d11d8](https://linux-hardware.org/?probe=ed669d11d8) | Aug 17, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [680fae2274](https://linux-hardware.org/?probe=680fae2274) | Aug 17, 2023 |
| Google        | Coral                       | Notebook    | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Dell          | Latitude 7440               | Notebook    | [e56c46e8fe](https://linux-hardware.org/?probe=e56c46e8fe) | Aug 17, 2023 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [7c09135f98](https://linux-hardware.org/?probe=7c09135f98) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f626ffa833](https://linux-hardware.org/?probe=f626ffa833) | Aug 17, 2023 |
| Toshiba       | Satellite L670              | Notebook    | [915e37b55d](https://linux-hardware.org/?probe=915e37b55d) | Aug 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b82ccd639](https://linux-hardware.org/?probe=6b82ccd639) | Aug 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [1b29161809](https://linux-hardware.org/?probe=1b29161809) | Aug 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [fd91c311ff](https://linux-hardware.org/?probe=fd91c311ff) | Aug 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [73640f7f83](https://linux-hardware.org/?probe=73640f7f83) | Aug 16, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [e4fe24b00a](https://linux-hardware.org/?probe=e4fe24b00a) | Aug 16, 2023 |
| Dell          | Precision 7530              | Notebook    | [dfaa8829e1](https://linux-hardware.org/?probe=dfaa8829e1) | Aug 16, 2023 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [cf1c4e8c82](https://linux-hardware.org/?probe=cf1c4e8c82) | Aug 16, 2023 |
| Dell          | Latitude 7300               | Notebook    | [07c0414596](https://linux-hardware.org/?probe=07c0414596) | Aug 16, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [2db998a2ca](https://linux-hardware.org/?probe=2db998a2ca) | Aug 16, 2023 |
| BESSTAR Te... | VB9                         | Mini pc     | [f4f73b1d87](https://linux-hardware.org/?probe=f4f73b1d87) | Aug 16, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [24cd5deaa3](https://linux-hardware.org/?probe=24cd5deaa3) | Aug 16, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b42d5dec8e](https://linux-hardware.org/?probe=b42d5dec8e) | Aug 16, 2023 |
| Acer          | EM61SM/EM61PM               | Desktop     | [428f134de7](https://linux-hardware.org/?probe=428f134de7) | Aug 15, 2023 |
| Packard Be... | EasyNote TSX66HR            | Notebook    | [f1b16023fd](https://linux-hardware.org/?probe=f1b16023fd) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [6e7b731daa](https://linux-hardware.org/?probe=6e7b731daa) | Aug 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ec0576c5aa](https://linux-hardware.org/?probe=ec0576c5aa) | Aug 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [d6925a9c7a](https://linux-hardware.org/?probe=d6925a9c7a) | Aug 15, 2023 |
| Dell          | 0GX297                      | Desktop     | [0fa81b620e](https://linux-hardware.org/?probe=0fa81b620e) | Aug 14, 2023 |
| AK3V          | 1.0                         | Desktop     | [02b6f071a6](https://linux-hardware.org/?probe=02b6f071a6) | Aug 14, 2023 |
| HP            | 21F5 0A                     | Desktop     | [7a8b1ea89a](https://linux-hardware.org/?probe=7a8b1ea89a) | Aug 14, 2023 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [bed2e58bf4](https://linux-hardware.org/?probe=bed2e58bf4) | Aug 14, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [1f27d0f994](https://linux-hardware.org/?probe=1f27d0f994) | Aug 14, 2023 |
| Gigabyte      | H61N-D2V                    | Desktop     | [19259c73ab](https://linux-hardware.org/?probe=19259c73ab) | Aug 14, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [a34dfca1e3](https://linux-hardware.org/?probe=a34dfca1e3) | Aug 14, 2023 |
| Lenovo        | ThinkPad W520 4284CY1       | Notebook    | [61edf8f5ee](https://linux-hardware.org/?probe=61edf8f5ee) | Aug 14, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [57af1d89d6](https://linux-hardware.org/?probe=57af1d89d6) | Aug 14, 2023 |
| Acer          | Swift SF515-51T             | Notebook    | [9271029425](https://linux-hardware.org/?probe=9271029425) | Aug 13, 2023 |
| Tactus        | GeoBook 110                 | Notebook    | [b6897622f2](https://linux-hardware.org/?probe=b6897622f2) | Aug 13, 2023 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [42772eba76](https://linux-hardware.org/?probe=42772eba76) | Aug 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [e934dcd506](https://linux-hardware.org/?probe=e934dcd506) | Aug 13, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [7e47b7128b](https://linux-hardware.org/?probe=7e47b7128b) | Aug 13, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [e2fe66aca4](https://linux-hardware.org/?probe=e2fe66aca4) | Aug 13, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [bcf7b9bd8f](https://linux-hardware.org/?probe=bcf7b9bd8f) | Aug 13, 2023 |
| Sony          | SVE1112M1EW                 | Notebook    | [353fb8c6ff](https://linux-hardware.org/?probe=353fb8c6ff) | Aug 13, 2023 |
| Thomson       | X6-4.32GR                   | Notebook    | [454fdb4295](https://linux-hardware.org/?probe=454fdb4295) | Aug 13, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [11a7488d83](https://linux-hardware.org/?probe=11a7488d83) | Aug 12, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [1bb5ae3f67](https://linux-hardware.org/?probe=1bb5ae3f67) | Aug 12, 2023 |
| Lenovo        | ThinkPad T460p 20FXS1C30... | Notebook    | [08542d994e](https://linux-hardware.org/?probe=08542d994e) | Aug 12, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [05024005e4](https://linux-hardware.org/?probe=05024005e4) | Aug 12, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [2832e701f2](https://linux-hardware.org/?probe=2832e701f2) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [67f821bd4d](https://linux-hardware.org/?probe=67f821bd4d) | Aug 12, 2023 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | Desktop     | [ae7ae594f1](https://linux-hardware.org/?probe=ae7ae594f1) | Aug 12, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [977c66cbc0](https://linux-hardware.org/?probe=977c66cbc0) | Aug 12, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [1f4aa5bf97](https://linux-hardware.org/?probe=1f4aa5bf97) | Aug 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [2e76349d2c](https://linux-hardware.org/?probe=2e76349d2c) | Aug 12, 2023 |
| Gigabyte      | M720-US3                    | Desktop     | [222bc02e4f](https://linux-hardware.org/?probe=222bc02e4f) | Aug 11, 2023 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [361e073b5c](https://linux-hardware.org/?probe=361e073b5c) | Aug 11, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [f4a323eb82](https://linux-hardware.org/?probe=f4a323eb82) | Aug 11, 2023 |
| Sony          | SVE1513I4E                  | Notebook    | [6b8cb6d520](https://linux-hardware.org/?probe=6b8cb6d520) | Aug 11, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [f711709f3f](https://linux-hardware.org/?probe=f711709f3f) | Aug 11, 2023 |
| MSI           | H410M-A PRO                 | Desktop     | [de3739c2a5](https://linux-hardware.org/?probe=de3739c2a5) | Aug 11, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | Notebook    | [fad80ecff3](https://linux-hardware.org/?probe=fad80ecff3) | Aug 11, 2023 |
| Acer          | Aspire ES1-431              | Notebook    | [171fd219cc](https://linux-hardware.org/?probe=171fd219cc) | Aug 10, 2023 |
| HP            | 18E7                        | Desktop     | [ff27f888f0](https://linux-hardware.org/?probe=ff27f888f0) | Aug 10, 2023 |
| Acer          | Aspire ES1-431              | Notebook    | [6802a19338](https://linux-hardware.org/?probe=6802a19338) | Aug 10, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [0028486d9d](https://linux-hardware.org/?probe=0028486d9d) | Aug 10, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [96d3419a5f](https://linux-hardware.org/?probe=96d3419a5f) | Aug 10, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [0caf17e079](https://linux-hardware.org/?probe=0caf17e079) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [0521e62bf9](https://linux-hardware.org/?probe=0521e62bf9) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [198fcb1fc2](https://linux-hardware.org/?probe=198fcb1fc2) | Aug 10, 2023 |
| HP            | Pavilion 17                 | Notebook    | [65733120b0](https://linux-hardware.org/?probe=65733120b0) | Aug 09, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [304b175b3c](https://linux-hardware.org/?probe=304b175b3c) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [bf81bbf7b4](https://linux-hardware.org/?probe=bf81bbf7b4) | Aug 09, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [4448c9f2e1](https://linux-hardware.org/?probe=4448c9f2e1) | Aug 09, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [6e1d11025a](https://linux-hardware.org/?probe=6e1d11025a) | Aug 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [de8d362cb8](https://linux-hardware.org/?probe=de8d362cb8) | Aug 09, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [65d491c109](https://linux-hardware.org/?probe=65d491c109) | Aug 09, 2023 |
| Intel         | DQ77KB AAG40294-401         | Desktop     | [3a761b76d6](https://linux-hardware.org/?probe=3a761b76d6) | Aug 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0cf2ab49c0](https://linux-hardware.org/?probe=0cf2ab49c0) | Aug 09, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [5e79da69ed](https://linux-hardware.org/?probe=5e79da69ed) | Aug 09, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [c761edfea1](https://linux-hardware.org/?probe=c761edfea1) | Aug 09, 2023 |
| Dell          | 040DDP A00                  | Desktop     | [13d99d66da](https://linux-hardware.org/?probe=13d99d66da) | Aug 09, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [0620b6b11a](https://linux-hardware.org/?probe=0620b6b11a) | Aug 09, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [ced8776e4d](https://linux-hardware.org/?probe=ced8776e4d) | Aug 09, 2023 |
| Dell          | 08HPGT A01                  | Desktop     | [273e794a99](https://linux-hardware.org/?probe=273e794a99) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [057ef3751d](https://linux-hardware.org/?probe=057ef3751d) | Aug 08, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [ee7bcf8fe1](https://linux-hardware.org/?probe=ee7bcf8fe1) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [04d19635d5](https://linux-hardware.org/?probe=04d19635d5) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [671a686166](https://linux-hardware.org/?probe=671a686166) | Aug 08, 2023 |
| Dell          | 0NK5PH A01                  | Desktop     | [eb06b6713d](https://linux-hardware.org/?probe=eb06b6713d) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [d9c999ffa3](https://linux-hardware.org/?probe=d9c999ffa3) | Aug 08, 2023 |
| Dell          | Latitude 7310               | Notebook    | [19646f8e46](https://linux-hardware.org/?probe=19646f8e46) | Aug 08, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T800     | Notebook    | [8316628b28](https://linux-hardware.org/?probe=8316628b28) | Aug 08, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T800     | Notebook    | [05d33f11b5](https://linux-hardware.org/?probe=05d33f11b5) | Aug 08, 2023 |
| Notebook      | W65_W67RZ1                  | Notebook    | [ab4b3c8f47](https://linux-hardware.org/?probe=ab4b3c8f47) | Aug 08, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [187ac2792a](https://linux-hardware.org/?probe=187ac2792a) | Aug 08, 2023 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | Desktop     | [c48e0220d8](https://linux-hardware.org/?probe=c48e0220d8) | Aug 08, 2023 |
| Intel         | D33217GKE G76540-203        | Desktop     | [fa0fbda262](https://linux-hardware.org/?probe=fa0fbda262) | Aug 08, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [bf56c08196](https://linux-hardware.org/?probe=bf56c08196) | Aug 08, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [c52b1e963f](https://linux-hardware.org/?probe=c52b1e963f) | Aug 08, 2023 |
| Dell          | 0GWHMW A03                  | Desktop     | [ce5dea2bc6](https://linux-hardware.org/?probe=ce5dea2bc6) | Aug 08, 2023 |
| Dell          | 0GWHMW A03                  | Desktop     | [1ba2de9148](https://linux-hardware.org/?probe=1ba2de9148) | Aug 08, 2023 |
| Intel         | D33217GKE G76540-203        | Desktop     | [f75916b7c7](https://linux-hardware.org/?probe=f75916b7c7) | Aug 08, 2023 |
| Dell          | 08HPGT A01                  | Desktop     | [616f6ba289](https://linux-hardware.org/?probe=616f6ba289) | Aug 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [4148b505d6](https://linux-hardware.org/?probe=4148b505d6) | Aug 08, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [211978450c](https://linux-hardware.org/?probe=211978450c) | Aug 08, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [132603d7e2](https://linux-hardware.org/?probe=132603d7e2) | Aug 08, 2023 |
| Dell          | Latitude 7310               | Notebook    | [baab866835](https://linux-hardware.org/?probe=baab866835) | Aug 08, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [23dd3e572c](https://linux-hardware.org/?probe=23dd3e572c) | Aug 08, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [b00519fee7](https://linux-hardware.org/?probe=b00519fee7) | Aug 08, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [ff4ead4bd3](https://linux-hardware.org/?probe=ff4ead4bd3) | Aug 08, 2023 |
| Acer          | AO756                       | Notebook    | [1ea1658ac0](https://linux-hardware.org/?probe=1ea1658ac0) | Aug 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ef73e2e520](https://linux-hardware.org/?probe=ef73e2e520) | Aug 07, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [bb99f6f69e](https://linux-hardware.org/?probe=bb99f6f69e) | Aug 07, 2023 |
| HP            | G60                         | Notebook    | [7f3b9aec85](https://linux-hardware.org/?probe=7f3b9aec85) | Aug 07, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [a1b9b9fc2c](https://linux-hardware.org/?probe=a1b9b9fc2c) | Aug 07, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c04ac90ce8](https://linux-hardware.org/?probe=c04ac90ce8) | Aug 07, 2023 |
| MSI           | GL72 7QF                    | Notebook    | [73f4a3b852](https://linux-hardware.org/?probe=73f4a3b852) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a3dd4fadf3](https://linux-hardware.org/?probe=a3dd4fadf3) | Aug 07, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | Notebook    | [fe977cc0fe](https://linux-hardware.org/?probe=fe977cc0fe) | Aug 07, 2023 |
| Notebook      | NHxxRZQ                     | Notebook    | [0cd17c8b5c](https://linux-hardware.org/?probe=0cd17c8b5c) | Aug 07, 2023 |
| Micro Comp... | NUCXI7                      | Notebook    | [96d3ade9eb](https://linux-hardware.org/?probe=96d3ade9eb) | Aug 07, 2023 |
| ASUSTek       | P5N-E SLI                   | Desktop     | [d552e347f5](https://linux-hardware.org/?probe=d552e347f5) | Aug 07, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [d076b394d9](https://linux-hardware.org/?probe=d076b394d9) | Aug 06, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7f6aa0ed0c](https://linux-hardware.org/?probe=7f6aa0ed0c) | Aug 06, 2023 |
| MSI           | H310M PRO-D                 | Desktop     | [201844f73e](https://linux-hardware.org/?probe=201844f73e) | Aug 06, 2023 |
| Foxconn       | 2AAF                        | Desktop     | [e0b2d4efb6](https://linux-hardware.org/?probe=e0b2d4efb6) | Aug 06, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [a3c7d29211](https://linux-hardware.org/?probe=a3c7d29211) | Aug 06, 2023 |
| Dell          | Latitude E5440              | Notebook    | [326ba9627a](https://linux-hardware.org/?probe=326ba9627a) | Aug 06, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [7a15d18c93](https://linux-hardware.org/?probe=7a15d18c93) | Aug 06, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [597461a5ac](https://linux-hardware.org/?probe=597461a5ac) | Aug 06, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [b47eca38dc](https://linux-hardware.org/?probe=b47eca38dc) | Aug 06, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [5796ca55ef](https://linux-hardware.org/?probe=5796ca55ef) | Aug 06, 2023 |
| HP            | 1791                        | Desktop     | [4a89aab3d6](https://linux-hardware.org/?probe=4a89aab3d6) | Aug 05, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [9d39447e43](https://linux-hardware.org/?probe=9d39447e43) | Aug 05, 2023 |
| Dell          | Latitude 5400               | Notebook    | [e788e3a534](https://linux-hardware.org/?probe=e788e3a534) | Aug 05, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [8c56195933](https://linux-hardware.org/?probe=8c56195933) | Aug 05, 2023 |
| HP            | 829A                        | Mini pc     | [03a93a19f6](https://linux-hardware.org/?probe=03a93a19f6) | Aug 05, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [ae5361d56f](https://linux-hardware.org/?probe=ae5361d56f) | Aug 05, 2023 |
| ASUSTek       | K52Je                       | Notebook    | [34fa8887dd](https://linux-hardware.org/?probe=34fa8887dd) | Aug 05, 2023 |
| HP            | Notebook                    | Notebook    | [d86cc7b5ba](https://linux-hardware.org/?probe=d86cc7b5ba) | Aug 05, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | Notebook    | [f4f8099774](https://linux-hardware.org/?probe=f4f8099774) | Aug 05, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [f1e284ec93](https://linux-hardware.org/?probe=f1e284ec93) | Aug 04, 2023 |
| HP            | 829A                        | Mini pc     | [ce4068d660](https://linux-hardware.org/?probe=ce4068d660) | Aug 04, 2023 |
| Dell          | G5 5587                     | Notebook    | [320fffbb49](https://linux-hardware.org/?probe=320fffbb49) | Aug 04, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [f5df04e0e6](https://linux-hardware.org/?probe=f5df04e0e6) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [838f543301](https://linux-hardware.org/?probe=838f543301) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [1b9b10c938](https://linux-hardware.org/?probe=1b9b10c938) | Aug 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [87febc0242](https://linux-hardware.org/?probe=87febc0242) | Aug 04, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [0068fdf226](https://linux-hardware.org/?probe=0068fdf226) | Aug 04, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [122ba504c1](https://linux-hardware.org/?probe=122ba504c1) | Aug 04, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [cd0d64a16a](https://linux-hardware.org/?probe=cd0d64a16a) | Aug 03, 2023 |
| Dell          | Latitude 5480               | Notebook    | [c52baac4e0](https://linux-hardware.org/?probe=c52baac4e0) | Aug 03, 2023 |
| MSI           | Titan GT77HX 13VH           | Notebook    | [3acda608a1](https://linux-hardware.org/?probe=3acda608a1) | Aug 03, 2023 |
| Sony          | VGN-NS38E_S                 | Notebook    | [a21051f2a8](https://linux-hardware.org/?probe=a21051f2a8) | Aug 03, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [caac03a431](https://linux-hardware.org/?probe=caac03a431) | Aug 03, 2023 |
| Notebook      | N9x0TD_TF                   | Notebook    | [033c07e1d3](https://linux-hardware.org/?probe=033c07e1d3) | Aug 03, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [34364bb6c3](https://linux-hardware.org/?probe=34364bb6c3) | Aug 03, 2023 |
| Notebook      | N9x0TD_TF                   | Notebook    | [3ab98d3af1](https://linux-hardware.org/?probe=3ab98d3af1) | Aug 03, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [9b2c783e20](https://linux-hardware.org/?probe=9b2c783e20) | Aug 03, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [8ed1cc4a3b](https://linux-hardware.org/?probe=8ed1cc4a3b) | Aug 03, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [877d855f27](https://linux-hardware.org/?probe=877d855f27) | Aug 02, 2023 |
| TUXEDO        | Book XA15 / XA17 Gen10      | Notebook    | [18e29b97ac](https://linux-hardware.org/?probe=18e29b97ac) | Aug 02, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [c9e70623fc](https://linux-hardware.org/?probe=c9e70623fc) | Aug 02, 2023 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [db043e1572](https://linux-hardware.org/?probe=db043e1572) | Aug 02, 2023 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [251b811e9b](https://linux-hardware.org/?probe=251b811e9b) | Aug 02, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [5c8ad99a3c](https://linux-hardware.org/?probe=5c8ad99a3c) | Aug 02, 2023 |
| Fujitsu       | D3402-A1 S26361-D3402-A1    | Desktop     | [5cbdefa7c5](https://linux-hardware.org/?probe=5cbdefa7c5) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [5f2529e42b](https://linux-hardware.org/?probe=5f2529e42b) | Aug 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| Pegatron      | Benicia                     | Desktop     | [5db4c563c6](https://linux-hardware.org/?probe=5db4c563c6) | Aug 01, 2023 |
| ASUSTek       | GL502VSK                    | Notebook    | [0ed7feaa05](https://linux-hardware.org/?probe=0ed7feaa05) | Aug 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [8353d48977](https://linux-hardware.org/?probe=8353d48977) | Aug 01, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [abe7173905](https://linux-hardware.org/?probe=abe7173905) | Aug 01, 2023 |
| Dell          | Precision 7520              | Notebook    | [b5addbb003](https://linux-hardware.org/?probe=b5addbb003) | Aug 01, 2023 |
| HP            | 1496                        | Desktop     | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| AZW           | SER                         | Mini pc     | [26cf19da86](https://linux-hardware.org/?probe=26cf19da86) | Jul 31, 2023 |
| Acer          | AOD255                      | Notebook    | [bdaffcb2ef](https://linux-hardware.org/?probe=bdaffcb2ef) | Jul 31, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c7f6e64888](https://linux-hardware.org/?probe=c7f6e64888) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4e4e6cd3eb](https://linux-hardware.org/?probe=4e4e6cd3eb) | Jul 31, 2023 |
| Packard Be... | H17HV                       | Notebook    | [de2003d390](https://linux-hardware.org/?probe=de2003d390) | Jul 31, 2023 |
| Lenovo        | ThinkPad L440 20ASS19B03    | Notebook    | [560cd8b4fb](https://linux-hardware.org/?probe=560cd8b4fb) | Jul 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [11d7923fa3](https://linux-hardware.org/?probe=11d7923fa3) | Jul 31, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [aead9f82b2](https://linux-hardware.org/?probe=aead9f82b2) | Jul 31, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [9e8f131101](https://linux-hardware.org/?probe=9e8f131101) | Jul 31, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [52c5dda710](https://linux-hardware.org/?probe=52c5dda710) | Jul 31, 2023 |
| Dell          | G15 5510                    | Notebook    | [8ab77abc2e](https://linux-hardware.org/?probe=8ab77abc2e) | Jul 30, 2023 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [33ac97b0c6](https://linux-hardware.org/?probe=33ac97b0c6) | Jul 30, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [98759e7a12](https://linux-hardware.org/?probe=98759e7a12) | Jul 30, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3daec696c7](https://linux-hardware.org/?probe=3daec696c7) | Jul 30, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [3bbfa332c0](https://linux-hardware.org/?probe=3bbfa332c0) | Jul 30, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [9f95c471d0](https://linux-hardware.org/?probe=9f95c471d0) | Jul 30, 2023 |
| Lenovo        | 0C48431 WIN                 | Desktop     | [4e0d5538b2](https://linux-hardware.org/?probe=4e0d5538b2) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | Notebook    | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [18f28e3fb6](https://linux-hardware.org/?probe=18f28e3fb6) | Jul 29, 2023 |
| Pegatron      | EVANS                       | Desktop     | [323d6a7283](https://linux-hardware.org/?probe=323d6a7283) | Jul 29, 2023 |
| Intel         | D33217GKE G76540-203        | Desktop     | [d551e6904d](https://linux-hardware.org/?probe=d551e6904d) | Jul 29, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [d0ef2177c3](https://linux-hardware.org/?probe=d0ef2177c3) | Jul 29, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [bc059e2204](https://linux-hardware.org/?probe=bc059e2204) | Jul 29, 2023 |
| Acer          | Swift SF315-52G             | Notebook    | [413fcf8114](https://linux-hardware.org/?probe=413fcf8114) | Jul 29, 2023 |
| Acer          | Swift SF315-52G             | Notebook    | [aca997f2b5](https://linux-hardware.org/?probe=aca997f2b5) | Jul 29, 2023 |
| Acer          | AOD255                      | Notebook    | [53c73b6ad3](https://linux-hardware.org/?probe=53c73b6ad3) | Jul 29, 2023 |
| HP            | ProBook 4525s               | Notebook    | [f1f6309860](https://linux-hardware.org/?probe=f1f6309860) | Jul 29, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [579d4eebb8](https://linux-hardware.org/?probe=579d4eebb8) | Jul 29, 2023 |
| ASUSTek       | X102BA                      | Notebook    | [488aa4c5b4](https://linux-hardware.org/?probe=488aa4c5b4) | Jul 29, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [1753d8ab39](https://linux-hardware.org/?probe=1753d8ab39) | Jul 29, 2023 |
| Ugoos         | AM6b Plus                   | Soc         | [a5ff8e9a5d](https://linux-hardware.org/?probe=a5ff8e9a5d) | Jul 29, 2023 |
| Sony          | VGN-NS38E_S                 | Notebook    | [703b459140](https://linux-hardware.org/?probe=703b459140) | Jul 28, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [5473e8bab9](https://linux-hardware.org/?probe=5473e8bab9) | Jul 28, 2023 |
| Chitech Sh... | Tibuta_MasterPad-W100       | Notebook    | [202a9be7b7](https://linux-hardware.org/?probe=202a9be7b7) | Jul 28, 2023 |
| Chuwi         | Hi10 X                      | Tablet      | [dac7c62216](https://linux-hardware.org/?probe=dac7c62216) | Jul 28, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [4d3abb525e](https://linux-hardware.org/?probe=4d3abb525e) | Jul 28, 2023 |
| Dell          | Precision 3520              | Notebook    | [bc2e0ff018](https://linux-hardware.org/?probe=bc2e0ff018) | Jul 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [d4774401e3](https://linux-hardware.org/?probe=d4774401e3) | Jul 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [45c79840cc](https://linux-hardware.org/?probe=45c79840cc) | Jul 28, 2023 |
| Pegatron      | 2A99                        | Desktop     | [068f8c77fd](https://linux-hardware.org/?probe=068f8c77fd) | Jul 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [75dec2a4a4](https://linux-hardware.org/?probe=75dec2a4a4) | Jul 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [6e7d094f7f](https://linux-hardware.org/?probe=6e7d094f7f) | Jul 27, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [56489a32b2](https://linux-hardware.org/?probe=56489a32b2) | Jul 27, 2023 |
| Intel         | D33217GKE G76540-203        | Desktop     | [b4089ed499](https://linux-hardware.org/?probe=b4089ed499) | Jul 26, 2023 |
| Cincoze       | DS-1300.00.001              | Desktop     | [e359107d20](https://linux-hardware.org/?probe=e359107d20) | Jul 26, 2023 |
| Cincoze       | DS-1300.00.001              | Desktop     | [01309bf370](https://linux-hardware.org/?probe=01309bf370) | Jul 26, 2023 |
| Dell          | Precision 3520              | Notebook    | [2502fbaef2](https://linux-hardware.org/?probe=2502fbaef2) | Jul 26, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [c693096b39](https://linux-hardware.org/?probe=c693096b39) | Jul 26, 2023 |
| Acer          | AOD255                      | Notebook    | [4f96dbf750](https://linux-hardware.org/?probe=4f96dbf750) | Jul 25, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [86e9608516](https://linux-hardware.org/?probe=86e9608516) | Jul 25, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [f8720bbd07](https://linux-hardware.org/?probe=f8720bbd07) | Jul 25, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21HK... | Notebook    | [f22f51832b](https://linux-hardware.org/?probe=f22f51832b) | Jul 25, 2023 |
| Dell          | Studio 1537                 | Notebook    | [803a98f7e6](https://linux-hardware.org/?probe=803a98f7e6) | Jul 25, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [f03fba3891](https://linux-hardware.org/?probe=f03fba3891) | Jul 25, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [007f2e5957](https://linux-hardware.org/?probe=007f2e5957) | Jul 25, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [12902831a7](https://linux-hardware.org/?probe=12902831a7) | Jul 25, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [3b317edaf6](https://linux-hardware.org/?probe=3b317edaf6) | Jul 25, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [b34b7fa5fb](https://linux-hardware.org/?probe=b34b7fa5fb) | Jul 25, 2023 |
| MSI           | Z77A-GD65                   | Desktop     | [4df7cd69af](https://linux-hardware.org/?probe=4df7cd69af) | Jul 25, 2023 |
| Pegatron      | Benicia                     | Desktop     | [ad8b67f72e](https://linux-hardware.org/?probe=ad8b67f72e) | Jul 24, 2023 |
| Unknown       | 1.2                         | Desktop     | [b18dd168dd](https://linux-hardware.org/?probe=b18dd168dd) | Jul 24, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [d4b572d070](https://linux-hardware.org/?probe=d4b572d070) | Jul 24, 2023 |
| Dell          | Precision 7520              | Notebook    | [66922483cf](https://linux-hardware.org/?probe=66922483cf) | Jul 24, 2023 |
| Acer          | AOD255                      | Notebook    | [3543f0800e](https://linux-hardware.org/?probe=3543f0800e) | Jul 24, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [980ed56abe](https://linux-hardware.org/?probe=980ed56abe) | Jul 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [59b11daded](https://linux-hardware.org/?probe=59b11daded) | Jul 24, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [f6c6668305](https://linux-hardware.org/?probe=f6c6668305) | Jul 23, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [3cc1d4a0cd](https://linux-hardware.org/?probe=3cc1d4a0cd) | Jul 23, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [567693892b](https://linux-hardware.org/?probe=567693892b) | Jul 23, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [c052f51a67](https://linux-hardware.org/?probe=c052f51a67) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [0a146a40d9](https://linux-hardware.org/?probe=0a146a40d9) | Jul 23, 2023 |
| Lenovo        | ThinkPad L460 20FVS01J00    | Notebook    | [96fe0142cd](https://linux-hardware.org/?probe=96fe0142cd) | Jul 23, 2023 |
| Dell          | 0K7CVF A03                  | Server      | [228949ef5a](https://linux-hardware.org/?probe=228949ef5a) | Jul 23, 2023 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [26e7657871](https://linux-hardware.org/?probe=26e7657871) | Jul 23, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [881853b4dc](https://linux-hardware.org/?probe=881853b4dc) | Jul 23, 2023 |
| HP            | Elite x2 G4                 | Tablet      | [1705d2fd99](https://linux-hardware.org/?probe=1705d2fd99) | Jul 23, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [9f1e03d74d](https://linux-hardware.org/?probe=9f1e03d74d) | Jul 23, 2023 |
| Acer          | AO756                       | Notebook    | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [d95040e760](https://linux-hardware.org/?probe=d95040e760) | Jul 23, 2023 |
| Dell          | Precision M2400             | Notebook    | [86913a26b4](https://linux-hardware.org/?probe=86913a26b4) | Jul 22, 2023 |
| Lenovo        | ThinkPad T420s 4174PEG      | Notebook    | [3bedb2ae12](https://linux-hardware.org/?probe=3bedb2ae12) | Jul 22, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [f3435d221b](https://linux-hardware.org/?probe=f3435d221b) | Jul 21, 2023 |
| ASUSTek       | B53E                        | Notebook    | [08012052d5](https://linux-hardware.org/?probe=08012052d5) | Jul 21, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [cdb9b29f94](https://linux-hardware.org/?probe=cdb9b29f94) | Jul 21, 2023 |
| ASUSTek       | H110S2                      | Desktop     | [3e43d97432](https://linux-hardware.org/?probe=3e43d97432) | Jul 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [97edd15b78](https://linux-hardware.org/?probe=97edd15b78) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [3db32d6c63](https://linux-hardware.org/?probe=3db32d6c63) | Jul 21, 2023 |
| Lenovo        | ThinkPad T540p 20BFA06B0... | Notebook    | [15e3320bb0](https://linux-hardware.org/?probe=15e3320bb0) | Jul 21, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [cf2d22469b](https://linux-hardware.org/?probe=cf2d22469b) | Jul 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5c4d93901b](https://linux-hardware.org/?probe=5c4d93901b) | Jul 20, 2023 |
| ASUSTek       | UX303LB                     | Notebook    | [901f80bb60](https://linux-hardware.org/?probe=901f80bb60) | Jul 20, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [6b01835487](https://linux-hardware.org/?probe=6b01835487) | Jul 20, 2023 |
| MSI           | CR700                       | Notebook    | [5cde06d6b9](https://linux-hardware.org/?probe=5cde06d6b9) | Jul 20, 2023 |
| MSI           | CR700                       | Notebook    | [2b2e403f78](https://linux-hardware.org/?probe=2b2e403f78) | Jul 20, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [7527ca0197](https://linux-hardware.org/?probe=7527ca0197) | Jul 20, 2023 |
| MSI           | A88XM-E35 V2                | Desktop     | [7ab6252e08](https://linux-hardware.org/?probe=7ab6252e08) | Jul 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e1bfe97e63](https://linux-hardware.org/?probe=e1bfe97e63) | Jul 19, 2023 |
| Dell          | 0XC7MM A00                  | Desktop     | [8d7dd80fa4](https://linux-hardware.org/?probe=8d7dd80fa4) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | Notebook    | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [158ce24cd5](https://linux-hardware.org/?probe=158ce24cd5) | Jul 19, 2023 |
| Thomson       | N15C8BK2T                   | Notebook    | [2e04333da5](https://linux-hardware.org/?probe=2e04333da5) | Jul 19, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [94856d413f](https://linux-hardware.org/?probe=94856d413f) | Jul 19, 2023 |
| HP            | 3047h                       | Desktop     | [a45f598a92](https://linux-hardware.org/?probe=a45f598a92) | Jul 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a5485bb7e0](https://linux-hardware.org/?probe=a5485bb7e0) | Jul 18, 2023 |
| ASRock        | H370M Pro4                  | Desktop     | [7682b57f64](https://linux-hardware.org/?probe=7682b57f64) | Jul 18, 2023 |
| ASUSTek       | Z87-C                       | Desktop     | [5324c1542f](https://linux-hardware.org/?probe=5324c1542f) | Jul 18, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [9853a8cf46](https://linux-hardware.org/?probe=9853a8cf46) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [25aef4eda4](https://linux-hardware.org/?probe=25aef4eda4) | Jul 18, 2023 |
| MSI           | MS-AEC11                    | All in one  | [9b9bcbddf0](https://linux-hardware.org/?probe=9b9bcbddf0) | Jul 17, 2023 |
| HP            | 3047h                       | Desktop     | [614b6a73e0](https://linux-hardware.org/?probe=614b6a73e0) | Jul 17, 2023 |
| Thomson       | X15I5-8TU512                | Notebook    | [f2d5a7b0d5](https://linux-hardware.org/?probe=f2d5a7b0d5) | Jul 17, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [6d77ef17a0](https://linux-hardware.org/?probe=6d77ef17a0) | Jul 17, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [393e57db0c](https://linux-hardware.org/?probe=393e57db0c) | Jul 17, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [e2075c4a1e](https://linux-hardware.org/?probe=e2075c4a1e) | Jul 17, 2023 |
| Alienware     | m16 R1 AMD                  | Notebook    | [7ca76c0d32](https://linux-hardware.org/?probe=7ca76c0d32) | Jul 17, 2023 |
| Acer          | TDPS05 R3700                | Desktop     | [78a7951688](https://linux-hardware.org/?probe=78a7951688) | Jul 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [fb1a31ec95](https://linux-hardware.org/?probe=fb1a31ec95) | Jul 16, 2023 |
| Teclast       | F6 Plus                     | Notebook    | [c18a0b61ae](https://linux-hardware.org/?probe=c18a0b61ae) | Jul 16, 2023 |
| Teclast       | F6 Plus                     | Notebook    | [c95b1bb4f5](https://linux-hardware.org/?probe=c95b1bb4f5) | Jul 16, 2023 |
| Dell          | Latitude E6440              | Notebook    | [c1de0cf4d1](https://linux-hardware.org/?probe=c1de0cf4d1) | Jul 16, 2023 |
| Dell          | Latitude E6320              | Notebook    | [0087a8e5cf](https://linux-hardware.org/?probe=0087a8e5cf) | Jul 16, 2023 |
| Toshiba       | Satellite P500              | Notebook    | [c72cbade9e](https://linux-hardware.org/?probe=c72cbade9e) | Jul 16, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [1e8eeb8513](https://linux-hardware.org/?probe=1e8eeb8513) | Jul 16, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [8efa3cf99d](https://linux-hardware.org/?probe=8efa3cf99d) | Jul 16, 2023 |
| GEEKOM        | Mini IT 8                   | Desktop     | [4754a5fc1b](https://linux-hardware.org/?probe=4754a5fc1b) | Jul 16, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [7fe3a6b5b2](https://linux-hardware.org/?probe=7fe3a6b5b2) | Jul 16, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [9161db3013](https://linux-hardware.org/?probe=9161db3013) | Jul 15, 2023 |
| MSI           | Modern 15 A10RBS            | Notebook    | [fde24c2a13](https://linux-hardware.org/?probe=fde24c2a13) | Jul 15, 2023 |
| ASUSTek       | Z87-C                       | Desktop     | [33e96d6f34](https://linux-hardware.org/?probe=33e96d6f34) | Jul 15, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [4a6f56c54a](https://linux-hardware.org/?probe=4a6f56c54a) | Jul 15, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | Notebook    | [8d3168b6c4](https://linux-hardware.org/?probe=8d3168b6c4) | Jul 15, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [420ffaec41](https://linux-hardware.org/?probe=420ffaec41) | Jul 15, 2023 |
| HP            | Pavilion 17                 | Notebook    | [c8775bcc36](https://linux-hardware.org/?probe=c8775bcc36) | Jul 15, 2023 |
| Acer          | Aspire E5-773G              | Notebook    | [a4a4102548](https://linux-hardware.org/?probe=a4a4102548) | Jul 15, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [8c4fe85b51](https://linux-hardware.org/?probe=8c4fe85b51) | Jul 15, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [c36495481b](https://linux-hardware.org/?probe=c36495481b) | Jul 15, 2023 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [7e088e838b](https://linux-hardware.org/?probe=7e088e838b) | Jul 15, 2023 |
| Dell          | Inspiron MP061              | Notebook    | [0a26ffe33b](https://linux-hardware.org/?probe=0a26ffe33b) | Jul 15, 2023 |
| BESSTAR Te... | U820                        | Notebook    | [6e79cbdccc](https://linux-hardware.org/?probe=6e79cbdccc) | Jul 15, 2023 |
| BESSTAR Te... | U820                        | Notebook    | [1c9da1be8b](https://linux-hardware.org/?probe=1c9da1be8b) | Jul 15, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [41283a1f4e](https://linux-hardware.org/?probe=41283a1f4e) | Jul 15, 2023 |
| Dell          | Latitude 7490               | Notebook    | [6811ebe45a](https://linux-hardware.org/?probe=6811ebe45a) | Jul 15, 2023 |
| BESSTAR Te... | U820                        | Notebook    | [274b5bed12](https://linux-hardware.org/?probe=274b5bed12) | Jul 15, 2023 |
| Toshiba       | Satellite Pro L500          | Notebook    | [605c123888](https://linux-hardware.org/?probe=605c123888) | Jul 15, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [9727ab2451](https://linux-hardware.org/?probe=9727ab2451) | Jul 14, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [2be21e12f5](https://linux-hardware.org/?probe=2be21e12f5) | Jul 14, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [8771f0ddd0](https://linux-hardware.org/?probe=8771f0ddd0) | Jul 14, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [2f552150c5](https://linux-hardware.org/?probe=2f552150c5) | Jul 14, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [5e2e7e4f4b](https://linux-hardware.org/?probe=5e2e7e4f4b) | Jul 14, 2023 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [d2cef330bf](https://linux-hardware.org/?probe=d2cef330bf) | Jul 14, 2023 |
| AZW           | SER                         | Mini pc     | [8fdb4e6f42](https://linux-hardware.org/?probe=8fdb4e6f42) | Jul 14, 2023 |
| AZW           | SER                         | Mini pc     | [537e7c9c94](https://linux-hardware.org/?probe=537e7c9c94) | Jul 13, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | Notebook    | [ae8ecf10e7](https://linux-hardware.org/?probe=ae8ecf10e7) | Jul 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [a67315ae3e](https://linux-hardware.org/?probe=a67315ae3e) | Jul 13, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a5cdc8bb58](https://linux-hardware.org/?probe=a5cdc8bb58) | Jul 13, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [87a3354fc2](https://linux-hardware.org/?probe=87a3354fc2) | Jul 13, 2023 |
| ASUSTek       | X456UV                      | Notebook    | [b0a9e3905f](https://linux-hardware.org/?probe=b0a9e3905f) | Jul 13, 2023 |
| Lenovo        | ThinkPad X280 20KES73S06    | Notebook    | [b301164e01](https://linux-hardware.org/?probe=b301164e01) | Jul 13, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [0ae6ff1386](https://linux-hardware.org/?probe=0ae6ff1386) | Jul 13, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [7c9bb65c6a](https://linux-hardware.org/?probe=7c9bb65c6a) | Jul 13, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [3795772e96](https://linux-hardware.org/?probe=3795772e96) | Jul 13, 2023 |
| HP            | ProBook 4525s               | Notebook    | [6bae89bb98](https://linux-hardware.org/?probe=6bae89bb98) | Jul 13, 2023 |
| HP            | 1495                        | Desktop     | [fdbc0b7f33](https://linux-hardware.org/?probe=fdbc0b7f33) | Jul 13, 2023 |
| Sony          | VPCEF4E1E                   | Notebook    | [32f1860a65](https://linux-hardware.org/?probe=32f1860a65) | Jul 12, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [4875c100c1](https://linux-hardware.org/?probe=4875c100c1) | Jul 12, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [51cf410b69](https://linux-hardware.org/?probe=51cf410b69) | Jul 12, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [ce55d97846](https://linux-hardware.org/?probe=ce55d97846) | Jul 12, 2023 |
| Acer          | Swift SF515-51T             | Notebook    | [9f8a8c63e6](https://linux-hardware.org/?probe=9f8a8c63e6) | Jul 12, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [682457df13](https://linux-hardware.org/?probe=682457df13) | Jul 12, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [3ffdc0cd08](https://linux-hardware.org/?probe=3ffdc0cd08) | Jul 12, 2023 |
| ASUSTek       | GL553VW                     | Notebook    | [9946c63986](https://linux-hardware.org/?probe=9946c63986) | Jul 12, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [493d7a5ab7](https://linux-hardware.org/?probe=493d7a5ab7) | Jul 12, 2023 |
| MSI           | H81M-P32                    | Desktop     | [2bf59485a6](https://linux-hardware.org/?probe=2bf59485a6) | Jul 12, 2023 |
| Samsung       | 950XED                      | Notebook    | [2f8f9d9277](https://linux-hardware.org/?probe=2f8f9d9277) | Jul 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [738fd58ef5](https://linux-hardware.org/?probe=738fd58ef5) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [c81c5855d4](https://linux-hardware.org/?probe=c81c5855d4) | Jul 11, 2023 |
| Unknown       | 1.0                         | Desktop     | [73e4a885a4](https://linux-hardware.org/?probe=73e4a885a4) | Jul 11, 2023 |
| HP            | Compaq 6730s                | Notebook    | [1c3f1f1005](https://linux-hardware.org/?probe=1c3f1f1005) | Jul 11, 2023 |
| Dell          | 048DY8 A00                  | Desktop     | [66c586dfe4](https://linux-hardware.org/?probe=66c586dfe4) | Jul 11, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [0cc7523fc4](https://linux-hardware.org/?probe=0cc7523fc4) | Jul 10, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [c2a5a3534e](https://linux-hardware.org/?probe=c2a5a3534e) | Jul 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [c09e539c94](https://linux-hardware.org/?probe=c09e539c94) | Jul 09, 2023 |
| HP            | ENVY 17                     | Notebook    | [0d1714007f](https://linux-hardware.org/?probe=0d1714007f) | Jul 09, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [044dd1e5a7](https://linux-hardware.org/?probe=044dd1e5a7) | Jul 09, 2023 |
| AZW           | U55                         | Mini pc     | [274a292b6d](https://linux-hardware.org/?probe=274a292b6d) | Jul 09, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | Notebook    | [866af72fb6](https://linux-hardware.org/?probe=866af72fb6) | Jul 09, 2023 |
| TR            | ST Plus-KN                  | Notebook    | [3d549b50a3](https://linux-hardware.org/?probe=3d549b50a3) | Jul 09, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [2d5d457159](https://linux-hardware.org/?probe=2d5d457159) | Jul 09, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [86c4d26a95](https://linux-hardware.org/?probe=86c4d26a95) | Jul 09, 2023 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [fdb15c83de](https://linux-hardware.org/?probe=fdb15c83de) | Jul 09, 2023 |
| HP            | 3048h                       | Desktop     | [99232ecd53](https://linux-hardware.org/?probe=99232ecd53) | Jul 09, 2023 |
| Dell          | Latitude 5320               | Notebook    | [55d5b4447a](https://linux-hardware.org/?probe=55d5b4447a) | Jul 09, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [8a798fe917](https://linux-hardware.org/?probe=8a798fe917) | Jul 09, 2023 |
| Gigabyte      | H410M S2H V2                | Desktop     | [dfc7f7a309](https://linux-hardware.org/?probe=dfc7f7a309) | Jul 09, 2023 |
| MSI           | Katana GF76 11UE            | Notebook    | [05c77752ce](https://linux-hardware.org/?probe=05c77752ce) | Jul 08, 2023 |
| MSI           | Katana GF76 11UE            | Notebook    | [be128325f8](https://linux-hardware.org/?probe=be128325f8) | Jul 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [144cb029ba](https://linux-hardware.org/?probe=144cb029ba) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [89e81df1b9](https://linux-hardware.org/?probe=89e81df1b9) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [0eaaaced27](https://linux-hardware.org/?probe=0eaaaced27) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [a208acb623](https://linux-hardware.org/?probe=a208acb623) | Jul 08, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [d6a3964ff7](https://linux-hardware.org/?probe=d6a3964ff7) | Jul 08, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [3bf9689ee5](https://linux-hardware.org/?probe=3bf9689ee5) | Jul 08, 2023 |
| HP            | 3399                        | Desktop     | [432d638098](https://linux-hardware.org/?probe=432d638098) | Jul 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [1cc2699f88](https://linux-hardware.org/?probe=1cc2699f88) | Jul 08, 2023 |
| Acer          | Aspire E5-523G              | Notebook    | [6535e7c6d1](https://linux-hardware.org/?probe=6535e7c6d1) | Jul 08, 2023 |
| Toshiba       | Satellite C870D-108         | Notebook    | [90207c9016](https://linux-hardware.org/?probe=90207c9016) | Jul 08, 2023 |
| Dell          | Vostro 1720                 | Notebook    | [0bd2fdf8a5](https://linux-hardware.org/?probe=0bd2fdf8a5) | Jul 08, 2023 |
| Sony          | VGN-NS38E_S                 | Notebook    | [eac09b82f8](https://linux-hardware.org/?probe=eac09b82f8) | Jul 07, 2023 |
| Sony          | VGN-NS38E_S                 | Notebook    | [4302a878d3](https://linux-hardware.org/?probe=4302a878d3) | Jul 07, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [25e1dec3b8](https://linux-hardware.org/?probe=25e1dec3b8) | Jul 07, 2023 |
| Thomson       | N15C4SL128                  | Notebook    | [96909a5157](https://linux-hardware.org/?probe=96909a5157) | Jul 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0b4200c1e4](https://linux-hardware.org/?probe=0b4200c1e4) | Jul 07, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f86a92b9af](https://linux-hardware.org/?probe=f86a92b9af) | Jul 07, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [702534e040](https://linux-hardware.org/?probe=702534e040) | Jul 07, 2023 |
| Medion        | Erazer P7643 MD60299        | Notebook    | [2c74ffe58f](https://linux-hardware.org/?probe=2c74ffe58f) | Jul 07, 2023 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [9101223f5e](https://linux-hardware.org/?probe=9101223f5e) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | Notebook    | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [cb30ecfbff](https://linux-hardware.org/?probe=cb30ecfbff) | Jul 06, 2023 |
| HP            | 84EF 01100                  | All in one  | [d31e0669fa](https://linux-hardware.org/?probe=d31e0669fa) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | Notebook    | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [6afd29fd20](https://linux-hardware.org/?probe=6afd29fd20) | Jul 06, 2023 |
| Dell          | Inspiron 7786               | Convertible | [2cd14c5648](https://linux-hardware.org/?probe=2cd14c5648) | Jul 06, 2023 |
| HP            | 240 G7 Notebook PC          | Notebook    | [9a3f397986](https://linux-hardware.org/?probe=9a3f397986) | Jul 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [abc1cb8ab2](https://linux-hardware.org/?probe=abc1cb8ab2) | Jul 05, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [b3530f3e0e](https://linux-hardware.org/?probe=b3530f3e0e) | Jul 05, 2023 |
| Timi          | TM1612                      | Notebook    | [843293c28d](https://linux-hardware.org/?probe=843293c28d) | Jul 05, 2023 |
| Thomson       | N15C4SL128                  | Notebook    | [8ba4bb3685](https://linux-hardware.org/?probe=8ba4bb3685) | Jul 05, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ac446902dd](https://linux-hardware.org/?probe=ac446902dd) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a3a67ab04c](https://linux-hardware.org/?probe=a3a67ab04c) | Jul 05, 2023 |
| ASUSTek       | TP300LA                     | Notebook    | [0954f1ace0](https://linux-hardware.org/?probe=0954f1ace0) | Jul 05, 2023 |
| MSI           | Indio                       | Desktop     | [b61c090b7e](https://linux-hardware.org/?probe=b61c090b7e) | Jul 05, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [7502eb638e](https://linux-hardware.org/?probe=7502eb638e) | Jul 04, 2023 |
| HP            | 83EF                        | Desktop     | [5f850e2bc1](https://linux-hardware.org/?probe=5f850e2bc1) | Jul 04, 2023 |
| Dell          | 0KYWH7 A00                  | Desktop     | [0c16b66976](https://linux-hardware.org/?probe=0c16b66976) | Jul 04, 2023 |
| Intel         | X79-SERVER V1.1             | Desktop     | [b3f63a5b2b](https://linux-hardware.org/?probe=b3f63a5b2b) | Jul 04, 2023 |
| eMachines     | Padus                       | Notebook    | [008b3a48cd](https://linux-hardware.org/?probe=008b3a48cd) | Jul 04, 2023 |
| Samsung       | 950XED                      | Notebook    | [e81ef31b14](https://linux-hardware.org/?probe=e81ef31b14) | Jul 03, 2023 |
| HP            | 1791                        | Desktop     | [64fdea845b](https://linux-hardware.org/?probe=64fdea845b) | Jul 03, 2023 |
| Dell          | Precision 3561              | Notebook    | [c7bd236006](https://linux-hardware.org/?probe=c7bd236006) | Jul 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f14a5888b6](https://linux-hardware.org/?probe=f14a5888b6) | Jul 03, 2023 |
| Dell          | Vostro 1220                 | Notebook    | [293d95dec2](https://linux-hardware.org/?probe=293d95dec2) | Jul 03, 2023 |
| HP            | Pavilion 17                 | Notebook    | [e6daccb5b9](https://linux-hardware.org/?probe=e6daccb5b9) | Jul 02, 2023 |
| ASRock        | P67 Performance             | Desktop     | [5abbfdce39](https://linux-hardware.org/?probe=5abbfdce39) | Jul 02, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [aae865deb7](https://linux-hardware.org/?probe=aae865deb7) | Jul 02, 2023 |
| Dell          | Latitude E6320              | Notebook    | [6f9335ddfd](https://linux-hardware.org/?probe=6f9335ddfd) | Jul 02, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [89db1a9656](https://linux-hardware.org/?probe=89db1a9656) | Jul 02, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [0e9e13c4b5](https://linux-hardware.org/?probe=0e9e13c4b5) | Jul 02, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d703fd9378](https://linux-hardware.org/?probe=d703fd9378) | Jul 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [f252a559f2](https://linux-hardware.org/?probe=f252a559f2) | Jul 02, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7429ccb00c](https://linux-hardware.org/?probe=7429ccb00c) | Jul 01, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [b9d71582c0](https://linux-hardware.org/?probe=b9d71582c0) | Jul 01, 2023 |
| ASUSTek       | P5E Deluxe                  | Desktop     | [895759fa79](https://linux-hardware.org/?probe=895759fa79) | Jul 01, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [5270a5ddc7](https://linux-hardware.org/?probe=5270a5ddc7) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [4f7a6ff110](https://linux-hardware.org/?probe=4f7a6ff110) | Jul 01, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e10b64716f](https://linux-hardware.org/?probe=e10b64716f) | Jul 01, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [46508a63f2](https://linux-hardware.org/?probe=46508a63f2) | Jul 01, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [1cc2f89c1a](https://linux-hardware.org/?probe=1cc2f89c1a) | Jul 01, 2023 |
| HP            | Compaq 6830s                | Notebook    | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| Acer          | Aspire E5-772               | Notebook    | [b33f11c7c9](https://linux-hardware.org/?probe=b33f11c7c9) | Jul 01, 2023 |
| ASUSTek       | K52Dr                       | Notebook    | [f97425ba5f](https://linux-hardware.org/?probe=f97425ba5f) | Jun 30, 2023 |
| Sony          | VGN-NS38E_S                 | Notebook    | [270e8b9fb7](https://linux-hardware.org/?probe=270e8b9fb7) | Jun 30, 2023 |
| Sony          | VGN-NS38E_S                 | Notebook    | [ca33cfbc67](https://linux-hardware.org/?probe=ca33cfbc67) | Jun 30, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | Desktop     | [0d3ecc7c44](https://linux-hardware.org/?probe=0d3ecc7c44) | Jun 30, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [08d14942e4](https://linux-hardware.org/?probe=08d14942e4) | Jun 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [6a4f9f32d6](https://linux-hardware.org/?probe=6a4f9f32d6) | Jun 30, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [6c6741deb9](https://linux-hardware.org/?probe=6c6741deb9) | Jun 30, 2023 |
| ASUSTek       | P8H67-V                     | Desktop     | [afe93b44f3](https://linux-hardware.org/?probe=afe93b44f3) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [954ac9a8e4](https://linux-hardware.org/?probe=954ac9a8e4) | Jun 30, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [99e1623ea0](https://linux-hardware.org/?probe=99e1623ea0) | Jun 29, 2023 |
| HP            | ProBook 4530s               | Notebook    | [d1c3bf37ff](https://linux-hardware.org/?probe=d1c3bf37ff) | Jun 29, 2023 |
| MSI           | GT70                        | Notebook    | [7471aab8f7](https://linux-hardware.org/?probe=7471aab8f7) | Jun 29, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6c7621fe04](https://linux-hardware.org/?probe=6c7621fe04) | Jun 29, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [1f2cf12e26](https://linux-hardware.org/?probe=1f2cf12e26) | Jun 29, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [171e61b165](https://linux-hardware.org/?probe=171e61b165) | Jun 29, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [49f05e412e](https://linux-hardware.org/?probe=49f05e412e) | Jun 28, 2023 |
| HP            | Pavilion 17                 | Notebook    | [01c3ae7698](https://linux-hardware.org/?probe=01c3ae7698) | Jun 28, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [5c049dc792](https://linux-hardware.org/?probe=5c049dc792) | Jun 28, 2023 |
| Dell          | Precision 3560              | Notebook    | [d7dfa3c472](https://linux-hardware.org/?probe=d7dfa3c472) | Jun 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 3 ... | Convertible | [d6d67cffd3](https://linux-hardware.org/?probe=d6d67cffd3) | Jun 28, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [1025bf4027](https://linux-hardware.org/?probe=1025bf4027) | Jun 28, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [b8453a6830](https://linux-hardware.org/?probe=b8453a6830) | Jun 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0081fa215e](https://linux-hardware.org/?probe=0081fa215e) | Jun 28, 2023 |
| ASUSTek       | M4N78                       | Desktop     | [03e5d24ba1](https://linux-hardware.org/?probe=03e5d24ba1) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [cb40f5d060](https://linux-hardware.org/?probe=cb40f5d060) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [13ac46e7fb](https://linux-hardware.org/?probe=13ac46e7fb) | Jun 28, 2023 |
| ASUSTek       | N75SF                       | Notebook    | [eda2a0d726](https://linux-hardware.org/?probe=eda2a0d726) | Jun 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [90a10ed8ed](https://linux-hardware.org/?probe=90a10ed8ed) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| Dell          | Latitude E6530              | Notebook    | [f015f73aef](https://linux-hardware.org/?probe=f015f73aef) | Jun 27, 2023 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [dae5fc72df](https://linux-hardware.org/?probe=dae5fc72df) | Jun 27, 2023 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [c91c09307d](https://linux-hardware.org/?probe=c91c09307d) | Jun 27, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [177c923e5a](https://linux-hardware.org/?probe=177c923e5a) | Jun 27, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [7478cd5b81](https://linux-hardware.org/?probe=7478cd5b81) | Jun 27, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [8b04801d40](https://linux-hardware.org/?probe=8b04801d40) | Jun 27, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [465cc8968f](https://linux-hardware.org/?probe=465cc8968f) | Jun 27, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [3928ad0893](https://linux-hardware.org/?probe=3928ad0893) | Jun 27, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [f296b651e4](https://linux-hardware.org/?probe=f296b651e4) | Jun 27, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [309cb87000](https://linux-hardware.org/?probe=309cb87000) | Jun 26, 2023 |
| LG Electro... | 17Z90R-G.AD79F              | Notebook    | [0d641b84fe](https://linux-hardware.org/?probe=0d641b84fe) | Jun 26, 2023 |
| Neousys Te... | NVS-9000 Rev. ES2           | Server      | [1680be6585](https://linux-hardware.org/?probe=1680be6585) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [b8a3042b9d](https://linux-hardware.org/?probe=b8a3042b9d) | Jun 26, 2023 |
| Timi          | TM1613                      | Notebook    | [e6b5bc59c2](https://linux-hardware.org/?probe=e6b5bc59c2) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M91p 7033A1G    | Desktop     | [a3ca410b6a](https://linux-hardware.org/?probe=a3ca410b6a) | Jun 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3505659de8](https://linux-hardware.org/?probe=3505659de8) | Jun 25, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [96184db86b](https://linux-hardware.org/?probe=96184db86b) | Jun 25, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | Notebook    | [ba30e1369c](https://linux-hardware.org/?probe=ba30e1369c) | Jun 25, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [eb8a9d675b](https://linux-hardware.org/?probe=eb8a9d675b) | Jun 25, 2023 |
| Toshiba       | Satellite Pro L500          | Notebook    | [44e57dc97b](https://linux-hardware.org/?probe=44e57dc97b) | Jun 25, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [d02e6a9fa6](https://linux-hardware.org/?probe=d02e6a9fa6) | Jun 25, 2023 |
| HP            | 8055                        | Desktop     | [7fac5a1354](https://linux-hardware.org/?probe=7fac5a1354) | Jun 24, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [b7bbc8246f](https://linux-hardware.org/?probe=b7bbc8246f) | Jun 24, 2023 |
| Dell          | Latitude E6410              | Notebook    | [7d1989fd84](https://linux-hardware.org/?probe=7d1989fd84) | Jun 24, 2023 |
| Dell          | Precision 5510              | Notebook    | [38d61a4475](https://linux-hardware.org/?probe=38d61a4475) | Jun 24, 2023 |
| ASRock        | B85 Pro4                    | Desktop     | [f42da342bc](https://linux-hardware.org/?probe=f42da342bc) | Jun 24, 2023 |
| Intel         | DH55HC AAE70933-503         | Desktop     | [8dab0b7f0d](https://linux-hardware.org/?probe=8dab0b7f0d) | Jun 24, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [96f79c634a](https://linux-hardware.org/?probe=96f79c634a) | Jun 24, 2023 |
| HP            | 1496                        | Desktop     | [9d4549de6c](https://linux-hardware.org/?probe=9d4549de6c) | Jun 24, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [9151f79ebe](https://linux-hardware.org/?probe=9151f79ebe) | Jun 24, 2023 |
| HP            | Pavilion dv7                | Notebook    | [ab7310809d](https://linux-hardware.org/?probe=ab7310809d) | Jun 24, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [6ed0182e96](https://linux-hardware.org/?probe=6ed0182e96) | Jun 24, 2023 |
| Alienware     | 17                          | Notebook    | [63b34ffc64](https://linux-hardware.org/?probe=63b34ffc64) | Jun 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4a11a4190a](https://linux-hardware.org/?probe=4a11a4190a) | Jun 23, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [19350653f7](https://linux-hardware.org/?probe=19350653f7) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [ac715f3941](https://linux-hardware.org/?probe=ac715f3941) | Jun 23, 2023 |
| eMachines     | eMG520                      | Notebook    | [2a33e0b985](https://linux-hardware.org/?probe=2a33e0b985) | Jun 23, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [649bcffd26](https://linux-hardware.org/?probe=649bcffd26) | Jun 23, 2023 |
| Packard Be... | EN Butterfly m              | Notebook    | [70bae75df2](https://linux-hardware.org/?probe=70bae75df2) | Jun 23, 2023 |
| Dell          | Precision 3581              | Notebook    | [2e960d89db](https://linux-hardware.org/?probe=2e960d89db) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| Dell          | XPS 15 9575                 | Convertible | [150b8d631e](https://linux-hardware.org/?probe=150b8d631e) | Jun 23, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [622462c1d1](https://linux-hardware.org/?probe=622462c1d1) | Jun 23, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [117e92a397](https://linux-hardware.org/?probe=117e92a397) | Jun 23, 2023 |
| AZW           | SER                         | Mini pc     | [4375fcb36a](https://linux-hardware.org/?probe=4375fcb36a) | Jun 23, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [83eb8cda4a](https://linux-hardware.org/?probe=83eb8cda4a) | Jun 23, 2023 |
| Lenovo        | ThinkPad E460 20ETCTO1WW    | Notebook    | [762add0eb1](https://linux-hardware.org/?probe=762add0eb1) | Jun 22, 2023 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [b36de255fe](https://linux-hardware.org/?probe=b36de255fe) | Jun 22, 2023 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [f8f4049a95](https://linux-hardware.org/?probe=f8f4049a95) | Jun 22, 2023 |
| Acer          | WG43M                       | Desktop     | [b3eae58854](https://linux-hardware.org/?probe=b3eae58854) | Jun 22, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [fc54744449](https://linux-hardware.org/?probe=fc54744449) | Jun 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [0a065bce17](https://linux-hardware.org/?probe=0a065bce17) | Jun 22, 2023 |
| AZW           | SER                         | Mini pc     | [9ef166eb46](https://linux-hardware.org/?probe=9ef166eb46) | Jun 22, 2023 |
| Dell          | 0NKW6Y A01                  | Desktop     | [def5a35ba4](https://linux-hardware.org/?probe=def5a35ba4) | Jun 21, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [596a01e7a5](https://linux-hardware.org/?probe=596a01e7a5) | Jun 21, 2023 |
| Lenovo        | ThinkPad L440 20ASS19B03    | Notebook    | [3acd887212](https://linux-hardware.org/?probe=3acd887212) | Jun 21, 2023 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [e6b0f20906](https://linux-hardware.org/?probe=e6b0f20906) | Jun 21, 2023 |
| Dell          | Latitude 5430               | Notebook    | [458a2111da](https://linux-hardware.org/?probe=458a2111da) | Jun 21, 2023 |
| ASUSTek       | K73SD                       | Notebook    | [2dcb7bb5c9](https://linux-hardware.org/?probe=2dcb7bb5c9) | Jun 21, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [004f9be7a7](https://linux-hardware.org/?probe=004f9be7a7) | Jun 21, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [386c32d302](https://linux-hardware.org/?probe=386c32d302) | Jun 21, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [ff224b2f9d](https://linux-hardware.org/?probe=ff224b2f9d) | Jun 21, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [acbd33c5c8](https://linux-hardware.org/?probe=acbd33c5c8) | Jun 21, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [a7e4d1a6bd](https://linux-hardware.org/?probe=a7e4d1a6bd) | Jun 21, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f1acdd3081](https://linux-hardware.org/?probe=f1acdd3081) | Jun 20, 2023 |
| Dell          | Latitude E5520              | Notebook    | [4c041a09f6](https://linux-hardware.org/?probe=4c041a09f6) | Jun 20, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [ec5318fcd1](https://linux-hardware.org/?probe=ec5318fcd1) | Jun 20, 2023 |
| Dell          | 0VHRW1 A03                  | Desktop     | [f077d9dc8f](https://linux-hardware.org/?probe=f077d9dc8f) | Jun 20, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [f84ddd7cac](https://linux-hardware.org/?probe=f84ddd7cac) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5a51d4431b](https://linux-hardware.org/?probe=5a51d4431b) | Jun 20, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [68d3aeda15](https://linux-hardware.org/?probe=68d3aeda15) | Jun 20, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [d9d8f74eca](https://linux-hardware.org/?probe=d9d8f74eca) | Jun 19, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Lenovo        | ThinkPad L440 20ASS19B03    | Notebook    | [a881db7c2b](https://linux-hardware.org/?probe=a881db7c2b) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [27bfb2de7d](https://linux-hardware.org/?probe=27bfb2de7d) | Jun 19, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [257c60290f](https://linux-hardware.org/?probe=257c60290f) | Jun 19, 2023 |
| HP            | 1497                        | Desktop     | [a922d11f63](https://linux-hardware.org/?probe=a922d11f63) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Otazak        | iPC45                       | Convertible | [5448e32422](https://linux-hardware.org/?probe=5448e32422) | Jun 19, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [fcec0ed2a4](https://linux-hardware.org/?probe=fcec0ed2a4) | Jun 19, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [ade4d4c90c](https://linux-hardware.org/?probe=ade4d4c90c) | Jun 19, 2023 |
| HP            | Pavilion 17                 | Notebook    | [46ae665800](https://linux-hardware.org/?probe=46ae665800) | Jun 18, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [733af664a4](https://linux-hardware.org/?probe=733af664a4) | Jun 18, 2023 |
| Dell          | Latitude 5430               | Notebook    | [7c591ed7d8](https://linux-hardware.org/?probe=7c591ed7d8) | Jun 18, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [fcbe9b509b](https://linux-hardware.org/?probe=fcbe9b509b) | Jun 18, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4d509da42f](https://linux-hardware.org/?probe=4d509da42f) | Jun 18, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [651988e989](https://linux-hardware.org/?probe=651988e989) | Jun 18, 2023 |
| Xunlong       | Orange Pi Lite              | Soc         | [f7e41df8d6](https://linux-hardware.org/?probe=f7e41df8d6) | Jun 18, 2023 |
| HP            | Pavilion 17                 | Notebook    | [f0e1e5aae8](https://linux-hardware.org/?probe=f0e1e5aae8) | Jun 18, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [02de076b1c](https://linux-hardware.org/?probe=02de076b1c) | Jun 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [37b1f672d0](https://linux-hardware.org/?probe=37b1f672d0) | Jun 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | Notebook    | [591e97398c](https://linux-hardware.org/?probe=591e97398c) | Jun 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [8dc64586cc](https://linux-hardware.org/?probe=8dc64586cc) | Jun 18, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [6fb60cf84a](https://linux-hardware.org/?probe=6fb60cf84a) | Jun 18, 2023 |
| Toshiba       | Satellite Pro L500          | Notebook    | [14765b8284](https://linux-hardware.org/?probe=14765b8284) | Jun 18, 2023 |
| HP            | 2820h                       | Desktop     | [b6d16a685f](https://linux-hardware.org/?probe=b6d16a685f) | Jun 17, 2023 |
| Lenovo        | ThinkPad P50 20EQS4840B     | Notebook    | [a60f1ae93e](https://linux-hardware.org/?probe=a60f1ae93e) | Jun 17, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f008a78339](https://linux-hardware.org/?probe=f008a78339) | Jun 17, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [7a3f7dcd73](https://linux-hardware.org/?probe=7a3f7dcd73) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Gigabyte      | AORUS 15P XC                | Notebook    | [bc59248a6c](https://linux-hardware.org/?probe=bc59248a6c) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| Dell          | 0P301D A00                  | Desktop     | [91bec0952f](https://linux-hardware.org/?probe=91bec0952f) | Jun 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3c45e54fd2](https://linux-hardware.org/?probe=3c45e54fd2) | Jun 17, 2023 |
| MSI           | GT70                        | Notebook    | [3ccbd6cfb4](https://linux-hardware.org/?probe=3ccbd6cfb4) | Jun 17, 2023 |
| Intel         | DQ77KB AAG81483-500         | Desktop     | [f06eae8b41](https://linux-hardware.org/?probe=f06eae8b41) | Jun 17, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [bbb32d23be](https://linux-hardware.org/?probe=bbb32d23be) | Jun 17, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [ec95321dfb](https://linux-hardware.org/?probe=ec95321dfb) | Jun 17, 2023 |
| Dell          | Precision M2800             | Notebook    | [e9f259595a](https://linux-hardware.org/?probe=e9f259595a) | Jun 17, 2023 |
| ASUSTek       | P5K Premium                 | Desktop     | [dddb2b8bdf](https://linux-hardware.org/?probe=dddb2b8bdf) | Jun 17, 2023 |
| Toshiba       | Satellite C870-199          | Notebook    | [cc18b4ff53](https://linux-hardware.org/?probe=cc18b4ff53) | Jun 16, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1f5163e415](https://linux-hardware.org/?probe=1f5163e415) | Jun 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [cfea5ce0fe](https://linux-hardware.org/?probe=cfea5ce0fe) | Jun 16, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [63cf4a0f41](https://linux-hardware.org/?probe=63cf4a0f41) | Jun 16, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [4c6361a099](https://linux-hardware.org/?probe=4c6361a099) | Jun 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [ec46ef5f36](https://linux-hardware.org/?probe=ec46ef5f36) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [f94cf27a96](https://linux-hardware.org/?probe=f94cf27a96) | Jun 15, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [56c650c8b1](https://linux-hardware.org/?probe=56c650c8b1) | Jun 15, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [d517ea1435](https://linux-hardware.org/?probe=d517ea1435) | Jun 15, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [41d5c8b913](https://linux-hardware.org/?probe=41d5c8b913) | Jun 15, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [448a3cf6b1](https://linux-hardware.org/?probe=448a3cf6b1) | Jun 15, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [67b278ea0e](https://linux-hardware.org/?probe=67b278ea0e) | Jun 15, 2023 |
| Dell          | Precision 5570              | Notebook    | [76bbf6a26f](https://linux-hardware.org/?probe=76bbf6a26f) | Jun 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [1858e12df4](https://linux-hardware.org/?probe=1858e12df4) | Jun 15, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [c488929cdc](https://linux-hardware.org/?probe=c488929cdc) | Jun 15, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a3990bdddb](https://linux-hardware.org/?probe=a3990bdddb) | Jun 15, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [23a8eeaa23](https://linux-hardware.org/?probe=23a8eeaa23) | Jun 15, 2023 |
| Lenovo        | ThinkPad L420 78545EG       | Notebook    | [bb42ee1009](https://linux-hardware.org/?probe=bb42ee1009) | Jun 14, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [5540ea0d6f](https://linux-hardware.org/?probe=5540ea0d6f) | Jun 14, 2023 |
| ZOTAC         | ZBOX-EN760                  | Mini pc     | [e36c953da7](https://linux-hardware.org/?probe=e36c953da7) | Jun 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [ea8e583821](https://linux-hardware.org/?probe=ea8e583821) | Jun 14, 2023 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [887bfc11d5](https://linux-hardware.org/?probe=887bfc11d5) | Jun 14, 2023 |
| Dell          | Latitude E5570              | Notebook    | [43171e0f19](https://linux-hardware.org/?probe=43171e0f19) | Jun 14, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2f23e52c68](https://linux-hardware.org/?probe=2f23e52c68) | Jun 14, 2023 |
| Sony          | SVS1312J3EW                 | Notebook    | [6668ed0dbe](https://linux-hardware.org/?probe=6668ed0dbe) | Jun 14, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [40ec446343](https://linux-hardware.org/?probe=40ec446343) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [04f1fdc3c9](https://linux-hardware.org/?probe=04f1fdc3c9) | Jun 14, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [2bc004d4b4](https://linux-hardware.org/?probe=2bc004d4b4) | Jun 14, 2023 |
| HP            | ENVY Notebook               | Notebook    | [6e714661f6](https://linux-hardware.org/?probe=6e714661f6) | Jun 14, 2023 |
| MSI           | GT75 Titan 8RG              | Notebook    | [9e25159fb6](https://linux-hardware.org/?probe=9e25159fb6) | Jun 14, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [b3b70ef13b](https://linux-hardware.org/?probe=b3b70ef13b) | Jun 14, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [aea3f705ed](https://linux-hardware.org/?probe=aea3f705ed) | Jun 13, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [1cddf187c5](https://linux-hardware.org/?probe=1cddf187c5) | Jun 13, 2023 |
| MSI           | Z77A-G45                    | Desktop     | [db1a941e2c](https://linux-hardware.org/?probe=db1a941e2c) | Jun 13, 2023 |
| Samsung       | R540/R538/SA41/E452         | Notebook    | [678c5510d3](https://linux-hardware.org/?probe=678c5510d3) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [0f19266aaf](https://linux-hardware.org/?probe=0f19266aaf) | Jun 13, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a22e7ac3ea](https://linux-hardware.org/?probe=a22e7ac3ea) | Jun 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [6a1f1e134c](https://linux-hardware.org/?probe=6a1f1e134c) | Jun 13, 2023 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | Notebook    | [a0b003c3b1](https://linux-hardware.org/?probe=a0b003c3b1) | Jun 13, 2023 |
| Alienware     | m15 R7                      | Notebook    | [c4a2634a83](https://linux-hardware.org/?probe=c4a2634a83) | Jun 13, 2023 |
| Alienware     | m15 R7                      | Notebook    | [7b53840b8b](https://linux-hardware.org/?probe=7b53840b8b) | Jun 13, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [a515b0dbf7](https://linux-hardware.org/?probe=a515b0dbf7) | Jun 12, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | Notebook    | [20b91b813f](https://linux-hardware.org/?probe=20b91b813f) | Jun 12, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [b870560cb8](https://linux-hardware.org/?probe=b870560cb8) | Jun 12, 2023 |
| Biostar       | A520MH                      | Desktop     | [70760c5e70](https://linux-hardware.org/?probe=70760c5e70) | Jun 12, 2023 |
| Supermicro    | X9DAi                       | Desktop     | [07f73cff06](https://linux-hardware.org/?probe=07f73cff06) | Jun 12, 2023 |
| Dell          | Precision 7560              | Notebook    | [fc461aad87](https://linux-hardware.org/?probe=fc461aad87) | Jun 12, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [69f20a331c](https://linux-hardware.org/?probe=69f20a331c) | Jun 12, 2023 |
| Dell          | Latitude 5520               | Notebook    | [f0fc9a8003](https://linux-hardware.org/?probe=f0fc9a8003) | Jun 11, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c433d533f0](https://linux-hardware.org/?probe=c433d533f0) | Jun 11, 2023 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [c544318b46](https://linux-hardware.org/?probe=c544318b46) | Jun 11, 2023 |
| ASUSTek       | V-P5G43 R1.04G              | Desktop     | [e2400bfebe](https://linux-hardware.org/?probe=e2400bfebe) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [cacba08c72](https://linux-hardware.org/?probe=cacba08c72) | Jun 11, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [008148f553](https://linux-hardware.org/?probe=008148f553) | Jun 11, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [db301ecd59](https://linux-hardware.org/?probe=db301ecd59) | Jun 11, 2023 |
| Dell          | Precision 5570              | Notebook    | [32975fdf08](https://linux-hardware.org/?probe=32975fdf08) | Jun 11, 2023 |
| NEC Comput... | PC-LM550LS6R                | Notebook    | [695f9825a6](https://linux-hardware.org/?probe=695f9825a6) | Jun 11, 2023 |
| Microsoft     | Surface Laptop Studio       | Tablet      | [58dde53dbd](https://linux-hardware.org/?probe=58dde53dbd) | Jun 11, 2023 |
| Microsoft     | Surface Laptop Studio       | Tablet      | [a2c786f205](https://linux-hardware.org/?probe=a2c786f205) | Jun 11, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [99f3070065](https://linux-hardware.org/?probe=99f3070065) | Jun 11, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [81e4b3fe5c](https://linux-hardware.org/?probe=81e4b3fe5c) | Jun 10, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [b5aee5a0a1](https://linux-hardware.org/?probe=b5aee5a0a1) | Jun 10, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [89aee96c82](https://linux-hardware.org/?probe=89aee96c82) | Jun 10, 2023 |
| Lenovo        | ThinkPad X240 20AMS5XY00    | Notebook    | [3b98c592e0](https://linux-hardware.org/?probe=3b98c592e0) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [c768cfa03d](https://linux-hardware.org/?probe=c768cfa03d) | Jun 10, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | Notebook    | [3d3375df75](https://linux-hardware.org/?probe=3d3375df75) | Jun 10, 2023 |
| Pegatron      | Benicia                     | Desktop     | [c57fee6ea0](https://linux-hardware.org/?probe=c57fee6ea0) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0eae3567d9](https://linux-hardware.org/?probe=0eae3567d9) | Jun 10, 2023 |
| HP            | 339B                        | Desktop     | [bc6de07e07](https://linux-hardware.org/?probe=bc6de07e07) | Jun 09, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [77145a587d](https://linux-hardware.org/?probe=77145a587d) | Jun 09, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [c605e51eca](https://linux-hardware.org/?probe=c605e51eca) | Jun 09, 2023 |
| Dell          | XPS 9320                    | Notebook    | [c9f26e18c2](https://linux-hardware.org/?probe=c9f26e18c2) | Jun 09, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [98a10d2fd9](https://linux-hardware.org/?probe=98a10d2fd9) | Jun 08, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [65f988a0c3](https://linux-hardware.org/?probe=65f988a0c3) | Jun 08, 2023 |
| AZW           | SEi                         | Desktop     | [399b4a7add](https://linux-hardware.org/?probe=399b4a7add) | Jun 08, 2023 |
| Dell          | Precision 3551              | Notebook    | [0e484bd6a5](https://linux-hardware.org/?probe=0e484bd6a5) | Jun 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [2c3b00b1ae](https://linux-hardware.org/?probe=2c3b00b1ae) | Jun 08, 2023 |
| Dell          | Precision 5510              | Notebook    | [24317d94ff](https://linux-hardware.org/?probe=24317d94ff) | Jun 08, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [cd3bb98a1e](https://linux-hardware.org/?probe=cd3bb98a1e) | Jun 08, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [f87fe0fe34](https://linux-hardware.org/?probe=f87fe0fe34) | Jun 08, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [f78a07f792](https://linux-hardware.org/?probe=f78a07f792) | Jun 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [57b238a5ff](https://linux-hardware.org/?probe=57b238a5ff) | Jun 08, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [87f789c059](https://linux-hardware.org/?probe=87f789c059) | Jun 07, 2023 |
| MSI           | CreatorPro X17 A12UKS       | Notebook    | [ee827c186c](https://linux-hardware.org/?probe=ee827c186c) | Jun 07, 2023 |
| MSI           | A88XM-E35                   | Desktop     | [efe1285363](https://linux-hardware.org/?probe=efe1285363) | Jun 07, 2023 |
| HP            | 8169                        | Desktop     | [45543e5040](https://linux-hardware.org/?probe=45543e5040) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [933978a1ae](https://linux-hardware.org/?probe=933978a1ae) | Jun 07, 2023 |
| Dell          | Latitude 5530               | Notebook    | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [8b82994313](https://linux-hardware.org/?probe=8b82994313) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [8f3282c700](https://linux-hardware.org/?probe=8f3282c700) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [326a620bbd](https://linux-hardware.org/?probe=326a620bbd) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [9cfd61dae7](https://linux-hardware.org/?probe=9cfd61dae7) | Jun 06, 2023 |
| HP            | Pavilion g7                 | Notebook    | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| Dell          | Latitude 5530               | Notebook    | [44aa9db289](https://linux-hardware.org/?probe=44aa9db289) | Jun 06, 2023 |
| MSI           | Crosshair 15 C12VF          | Notebook    | [6cd11169d0](https://linux-hardware.org/?probe=6cd11169d0) | Jun 05, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [5534470ef5](https://linux-hardware.org/?probe=5534470ef5) | Jun 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a06e6ab7ad](https://linux-hardware.org/?probe=a06e6ab7ad) | Jun 05, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [cdb3539c93](https://linux-hardware.org/?probe=cdb3539c93) | Jun 05, 2023 |
| ASRock        | G41M-GS3                    | Desktop     | [f8789775fe](https://linux-hardware.org/?probe=f8789775fe) | Jun 05, 2023 |
| Intel         | DE3815TYKH H26998-402       | Desktop     | [d2f97c16e9](https://linux-hardware.org/?probe=d2f97c16e9) | Jun 05, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [c68dff0dd7](https://linux-hardware.org/?probe=c68dff0dd7) | Jun 05, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [74b01a9071](https://linux-hardware.org/?probe=74b01a9071) | Jun 05, 2023 |
| ASUSTek       | K95VJ                       | Notebook    | [9bbcec82c6](https://linux-hardware.org/?probe=9bbcec82c6) | Jun 05, 2023 |
| HP            | 1850                        | Desktop     | [bddc14be8b](https://linux-hardware.org/?probe=bddc14be8b) | Jun 05, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Intel         | DH55HC AAE70933-503         | Desktop     | [b3d5e112eb](https://linux-hardware.org/?probe=b3d5e112eb) | Jun 04, 2023 |
| Jumper        | EZbook                      | Notebook    | [950179fe29](https://linux-hardware.org/?probe=950179fe29) | Jun 04, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [1b9656a4a1](https://linux-hardware.org/?probe=1b9656a4a1) | Jun 04, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [f492ab6829](https://linux-hardware.org/?probe=f492ab6829) | Jun 04, 2023 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [f1b932f397](https://linux-hardware.org/?probe=f1b932f397) | Jun 04, 2023 |
| IP3 Tech      | AP1                         | Notebook    | [d24ecf10e2](https://linux-hardware.org/?probe=d24ecf10e2) | Jun 04, 2023 |
| MSI           | H81M-P32                    | Desktop     | [f2423b3ef9](https://linux-hardware.org/?probe=f2423b3ef9) | Jun 04, 2023 |
| MSI           | H81M-P32                    | Desktop     | [f1d0b1d487](https://linux-hardware.org/?probe=f1d0b1d487) | Jun 04, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [968005c798](https://linux-hardware.org/?probe=968005c798) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [d45c069b9f](https://linux-hardware.org/?probe=d45c069b9f) | Jun 04, 2023 |
| Samsung       | 950XED                      | Notebook    | [185834c02e](https://linux-hardware.org/?probe=185834c02e) | Jun 04, 2023 |
| Schenker      | XMG FOCUS (M22)             | Notebook    | [31203c3645](https://linux-hardware.org/?probe=31203c3645) | Jun 03, 2023 |
| Acer          | Aspire TC-705               | Desktop     | [8aa3bc4947](https://linux-hardware.org/?probe=8aa3bc4947) | Jun 03, 2023 |
| HONOR         | HGF-WX6                     | Notebook    | [13d0d7b145](https://linux-hardware.org/?probe=13d0d7b145) | Jun 03, 2023 |
| MSI           | H97M-G43                    | Desktop     | [6bd1b61977](https://linux-hardware.org/?probe=6bd1b61977) | Jun 03, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [75ba9fba2f](https://linux-hardware.org/?probe=75ba9fba2f) | Jun 03, 2023 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [610ba5871f](https://linux-hardware.org/?probe=610ba5871f) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [9b83a4575b](https://linux-hardware.org/?probe=9b83a4575b) | Jun 02, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d856669333](https://linux-hardware.org/?probe=d856669333) | Jun 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [d1fec35ece](https://linux-hardware.org/?probe=d1fec35ece) | Jun 02, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [558ee7e63f](https://linux-hardware.org/?probe=558ee7e63f) | Jun 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4d170e024e](https://linux-hardware.org/?probe=4d170e024e) | Jun 02, 2023 |
| Acer          | Aspire X3950                | Desktop     | [82aa882647](https://linux-hardware.org/?probe=82aa882647) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ECS           | Nettle2                     | Desktop     | [6fe297e475](https://linux-hardware.org/?probe=6fe297e475) | Jun 02, 2023 |
| Acer          | Aspire X3950                | Desktop     | [1c7f0f7567](https://linux-hardware.org/?probe=1c7f0f7567) | Jun 02, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [7739f949e1](https://linux-hardware.org/?probe=7739f949e1) | Jun 02, 2023 |
| HP            | 802E                        | Desktop     | [1837c96bfd](https://linux-hardware.org/?probe=1837c96bfd) | Jun 02, 2023 |
| MSI           | H81M-E34                    | Desktop     | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [def2c6020b](https://linux-hardware.org/?probe=def2c6020b) | Jun 01, 2023 |
| MSI           | H81M-E34                    | Desktop     | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [f517c1893a](https://linux-hardware.org/?probe=f517c1893a) | Jun 01, 2023 |
| HP            | 18E5                        | Desktop     | [9d89c3065b](https://linux-hardware.org/?probe=9d89c3065b) | Jun 01, 2023 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [0bb0a8be66](https://linux-hardware.org/?probe=0bb0a8be66) | Jun 01, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Dell          | Latitude E5510              | Notebook    | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [1b1a5c05ac](https://linux-hardware.org/?probe=1b1a5c05ac) | Jun 01, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [3ca0d2f1a7](https://linux-hardware.org/?probe=3ca0d2f1a7) | Jun 01, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [ffc6b5e345](https://linux-hardware.org/?probe=ffc6b5e345) | Jun 01, 2023 |
| Supermicro    | X12STD-F                    | Desktop     | [8511ce89ad](https://linux-hardware.org/?probe=8511ce89ad) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [f66667b7fb](https://linux-hardware.org/?probe=f66667b7fb) | Jun 01, 2023 |
| Dell          | Latitude E5510              | Notebook    | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [9faf2de183](https://linux-hardware.org/?probe=9faf2de183) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| Acer          | Aspire 3830TG               | Notebook    | [abd7d9a412](https://linux-hardware.org/?probe=abd7d9a412) | May 31, 2023 |
| Packard Be... | EasyNote LJ75               | Notebook    | [95c733d00f](https://linux-hardware.org/?probe=95c733d00f) | May 31, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [ceaf9120eb](https://linux-hardware.org/?probe=ceaf9120eb) | May 31, 2023 |
| MSI           | GE70 2QE                    | Notebook    | [a075b8b77d](https://linux-hardware.org/?probe=a075b8b77d) | May 31, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | Notebook    | [239faf8c55](https://linux-hardware.org/?probe=239faf8c55) | May 31, 2023 |
| MSI           | B85M-G43                    | Desktop     | [38fb05719a](https://linux-hardware.org/?probe=38fb05719a) | May 31, 2023 |
| Dell          | Inspiron 3502               | Notebook    | [3c734d2900](https://linux-hardware.org/?probe=3c734d2900) | May 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [6c3655186f](https://linux-hardware.org/?probe=6c3655186f) | May 31, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [ad0b57d7c6](https://linux-hardware.org/?probe=ad0b57d7c6) | May 31, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [7709d9fd16](https://linux-hardware.org/?probe=7709d9fd16) | May 31, 2023 |
| Dell          | Latitude E5510              | Notebook    | [52e1023195](https://linux-hardware.org/?probe=52e1023195) | May 31, 2023 |
| Dell          | Latitude E5510              | Notebook    | [aa0f6a81b6](https://linux-hardware.org/?probe=aa0f6a81b6) | May 30, 2023 |
| ASUSTek       | P4S8L                       | Desktop     | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1777      | 17.04%  |
| Ubuntu 22.04       | 758       | 7.27%   |
| Ubuntu 18.04       | 560       | 5.37%   |
| Debian 11          | 429       | 4.11%   |
| OpenMandriva 4.2   | 373       | 3.58%   |
| OpenMandriva 4.3   | 314       | 3.01%   |
| Xubuntu 20.04      | 198       | 1.9%    |
| Linux Mint 20.3    | 195       | 1.87%   |
| Arch Rolling       | 181       | 1.74%   |
| OpenMandriva 23.01 | 153       | 1.47%   |
| Linux Mint 21.1    | 147       | 1.41%   |
| Debian 10          | 135       | 1.29%   |
| Arch               | 124       | 1.19%   |
| Ubuntu 21.10       | 122       | 1.17%   |
| Zorin 16           | 111       | 1.06%   |
| OpenMandriva 23.03 | 111       | 1.06%   |
| Linux Mint 20.2    | 110       | 1.05%   |
| Ubuntu 20.10       | 109       | 1.05%   |
| Ubuntu 21.04       | 106       | 1.02%   |
| Linux Mint 20.1    | 106       | 1.02%   |
| Manjaro            | 99        | 0.95%   |
| Linux Mint 19.3    | 90        | 0.86%   |
| Fedora 33          | 89        | 0.85%   |
| Ubuntu 19.10       | 85        | 0.82%   |
| Pop!_OS 22.04      | 85        | 0.82%   |
| Kubuntu 20.04      | 83        | 0.8%    |
| Linux Mint 21      | 82        | 0.79%   |
| Xubuntu 18.04      | 78        | 0.75%   |
| Ubuntu 22.10       | 78        | 0.75%   |
| Linux Mint 20      | 78        | 0.75%   |
| Fedora 34          | 75        | 0.72%   |
| Ubuntu 23.04       | 72        | 0.69%   |
| Ubuntu 19.04       | 71        | 0.68%   |
| KDE neon 20.04     | 71        | 0.68%   |
| Fedora 35          | 71        | 0.68%   |
| Xubuntu 22.04      | 70        | 0.67%   |
| Fedora 37          | 69        | 0.66%   |
| Fedora 32          | 69        | 0.66%   |
| Fedora 38          | 66        | 0.63%   |
| Fedora 36          | 66        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3635      | 36.96%  |
| OpenMandriva  | 1041      | 10.58%  |
| Linux Mint    | 831       | 8.45%   |
| Debian        | 710       | 7.22%   |
| Fedora        | 474       | 4.82%   |
| Xubuntu       | 392       | 3.99%   |
| Arch          | 299       | 3.04%   |
| Manjaro       | 260       | 2.64%   |
| Pop!_OS       | 243       | 2.47%   |
| Kubuntu       | 227       | 2.31%   |
| ROSA          | 175       | 1.78%   |
| Zorin         | 158       | 1.61%   |
| Ubuntu MATE   | 136       | 1.38%   |
| Lubuntu       | 125       | 1.27%   |
| KDE neon      | 105       | 1.07%   |
| openSUSE      | 76        | 0.77%   |
| Ubuntu Unity  | 75        | 0.76%   |
| Gentoo        | 68        | 0.69%   |
| ArcoLinux     | 65        | 0.66%   |
| Kali          | 64        | 0.65%   |
| Endless       | 52        | 0.53%   |
| Elementary    | 52        | 0.53%   |
| Ubuntu Budgie | 47        | 0.48%   |
| EndeavourOS   | 42        | 0.43%   |
| LMDE          | 37        | 0.38%   |
| BlackPanther  | 36        | 0.37%   |
| SteamOS       | 31        | 0.32%   |
| CentOS        | 29        | 0.29%   |
| Ubuntu Studio | 23        | 0.23%   |
| Mageia        | 23        | 0.23%   |
| Parrot        | 21        | 0.21%   |
| Clear Linux   | 20        | 0.2%    |
| MX            | 18        | 0.18%   |
| Nobara        | 16        | 0.16%   |
| Devuan        | 15        | 0.15%   |
| Raspbian      | 13        | 0.13%   |
| NixOS         | 12        | 0.12%   |
| Kaisen        | 12        | 0.12%   |
| Artix         | 12        | 0.12%   |
| Manjaro-ARM   | 11        | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 356       | 3.12%   |
| 5.16.7-desktop-1omv4003  | 285       | 2.5%    |
| 6.1.1-desktop-1omv2290   | 135       | 1.18%   |
| 5.15.0-56-generic        | 131       | 1.15%   |
| 5.4.0-42-generic         | 128       | 1.12%   |
| 6.2.6-desktop-1omv2390   | 102       | 0.89%   |
| 5.15.0-58-generic        | 101       | 0.88%   |
| 5.4.0-58-generic         | 99        | 0.87%   |
| 5.15.0-52-generic        | 95        | 0.83%   |
| 5.4.0-52-generic         | 81        | 0.71%   |
| 5.11.0-27-generic        | 78        | 0.68%   |
| 5.11.0-38-generic        | 77        | 0.67%   |
| 5.15.0-48-generic        | 74        | 0.65%   |
| 5.4.0-26-generic         | 73        | 0.64%   |
| 5.8.0-43-generic         | 69        | 0.6%    |
| 5.4.0-48-generic         | 69        | 0.6%    |
| 5.15.0-46-generic        | 66        | 0.58%   |
| 5.11.0-37-generic        | 66        | 0.58%   |
| 5.4.0-65-generic         | 65        | 0.57%   |
| 5.8.0-50-generic         | 63        | 0.55%   |
| 5.15.0-43-generic        | 61        | 0.53%   |
| 5.19.0-38-generic        | 60        | 0.53%   |
| 5.19.0-35-generic        | 58        | 0.51%   |
| 5.15.0-47-generic        | 57        | 0.5%    |
| 5.11.0-40-generic        | 57        | 0.5%    |
| 6.2.0-26-generic         | 55        | 0.48%   |
| 5.4.0-91-generic         | 55        | 0.48%   |
| 5.4.0-29-generic         | 55        | 0.48%   |
| 5.13.0-28-generic        | 55        | 0.48%   |
| 5.8.0-44-generic         | 54        | 0.47%   |
| 5.4.0-54-generic         | 54        | 0.47%   |
| 5.8.0-48-generic         | 53        | 0.46%   |
| 5.4.0-37-generic         | 53        | 0.46%   |
| 5.13.0-39-generic        | 52        | 0.46%   |
| 5.15.0-60-generic        | 51        | 0.45%   |
| 5.11.0-43-generic        | 51        | 0.45%   |
| 5.15.0-53-generic        | 49        | 0.43%   |
| 5.4.0-81-generic         | 48        | 0.42%   |
| 5.19.0-41-generic        | 48        | 0.42%   |
| 5.11.0-34-generic        | 48        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1798      | 16.74%  |
| 5.15.0  | 1171      | 10.9%   |
| 5.11.0  | 635       | 5.91%   |
| 5.8.0   | 614       | 5.72%   |
| 5.13.0  | 523       | 4.87%   |
| 4.15.0  | 444       | 4.13%   |
| 5.10.0  | 440       | 4.1%    |
| 5.19.0  | 439       | 4.09%   |
| 5.10.14 | 359       | 3.34%   |
| 5.3.0   | 288       | 2.68%   |
| 5.16.7  | 287       | 2.67%   |
| 5.0.0   | 164       | 1.53%   |
| 6.1.1   | 149       | 1.39%   |
| 6.2.0   | 143       | 1.33%   |
| 4.18.0  | 137       | 1.28%   |
| 4.19.0  | 129       | 1.2%    |
| 6.2.6   | 121       | 1.13%   |
| 6.1.0   | 67        | 0.62%   |
| 5.14.0  | 47        | 0.44%   |
| 6.0.0   | 44        | 0.41%   |
| 5.16.13 | 38        | 0.35%   |
| 6.4.11  | 36        | 0.34%   |
| 4.9.20  | 35        | 0.33%   |
| 5.18.0  | 34        | 0.32%   |
| 5.11.12 | 34        | 0.32%   |
| 4.18.16 | 33        | 0.31%   |
| 5.18.12 | 32        | 0.3%    |
| 5.17.5  | 31        | 0.29%   |
| 4.4.0   | 30        | 0.28%   |
| 5.16.0  | 28        | 0.26%   |
| 5.9.0   | 25        | 0.23%   |
| 5.19.12 | 23        | 0.21%   |
| 5.12.4  | 23        | 0.21%   |
| 4.9.60  | 23        | 0.21%   |
| 6.4.8   | 19        | 0.18%   |
| 6.0.12  | 19        | 0.18%   |
| 5.13.19 | 19        | 0.18%   |
| 5.9.16  | 18        | 0.17%   |
| 5.9.11  | 18        | 0.17%   |
| 5.7.0   | 18        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1893      | 17.86%  |
| 5.15    | 1384      | 13.06%  |
| 5.10    | 945       | 8.92%   |
| 5.11    | 730       | 6.89%   |
| 5.8     | 703       | 6.63%   |
| 5.13    | 606       | 5.72%   |
| 5.19    | 534       | 5.04%   |
| 4.15    | 445       | 4.2%    |
| 5.16    | 422       | 3.98%   |
| 6.2     | 369       | 3.48%   |
| 6.1     | 342       | 3.23%   |
| 5.3     | 330       | 3.11%   |
| 5.0     | 177       | 1.67%   |
| 4.18    | 173       | 1.63%   |
| 6.0     | 146       | 1.38%   |
| 4.19    | 146       | 1.38%   |
| 5.14    | 137       | 1.29%   |
| 5.18    | 132       | 1.25%   |
| 6.4     | 125       | 1.18%   |
| 4.9     | 120       | 1.13%   |
| 5.9     | 119       | 1.12%   |
| 5.17    | 108       | 1.02%   |
| 6.3     | 95        | 0.9%    |
| 5.6     | 82        | 0.77%   |
| 5.7     | 73        | 0.69%   |
| 5.12    | 70        | 0.66%   |
| 5.5     | 39        | 0.37%   |
| 4.4     | 35        | 0.33%   |
| 4.1     | 24        | 0.23%   |
| 3.10    | 16        | 0.15%   |
| 5.2     | 13        | 0.12%   |
| 4.14    | 12        | 0.11%   |
| 4.12    | 9         | 0.08%   |
| 6.5     | 8         | 0.08%   |
| 4.20    | 7         | 0.07%   |
| 4.13    | 7         | 0.07%   |
| 5.1     | 6         | 0.06%   |
| 4.10    | 4         | 0.04%   |
| 4.8     | 3         | 0.03%   |
| 4.17    | 2         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 9243      | 96.85%  |
| i686    | 221       | 2.32%   |
| aarch64 | 52        | 0.54%   |
| armv7l  | 21        | 0.22%   |
| armv6l  | 4         | 0.04%   |
| armv8l  | 2         | 0.02%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 4374      | 44.09%  |
| KDE5              | 1799      | 18.14%  |
| Unknown           | 945       | 9.53%   |
| XFCE              | 875       | 8.82%   |
| X-Cinnamon        | 600       | 6.05%   |
| MATE              | 376       | 3.79%   |
| LXQt              | 151       | 1.52%   |
| Cinnamon          | 136       | 1.37%   |
| KDE               | 119       | 1.2%    |
| KDE4              | 116       | 1.17%   |
| Unity             | 76        | 0.77%   |
| i3                | 75        | 0.76%   |
| Budgie            | 60        | 0.6%    |
| Pantheon          | 55        | 0.55%   |
| LXDE              | 45        | 0.45%   |
| GNOME Flashback   | 29        | 0.29%   |
| GNOME Classic     | 14        | 0.14%   |
| Deepin            | 13        | 0.13%   |
| sway              | 10        | 0.1%    |
| awesome           | 7         | 0.07%   |
| qtile             | 5         | 0.05%   |
| Hyprland          | 5         | 0.05%   |
| bspwm             | 5         | 0.05%   |
| trinity           | 3         | 0.03%   |
| lightdm-xsession  | 3         | 0.03%   |
| ICEWM             | 3         | 0.03%   |
| i3-with-shmlog    | 3         | 0.03%   |
| Openbox           | 2         | 0.02%   |
| GNUstep           | 2         | 0.02%   |
| Enlightenment     | 2         | 0.02%   |
| Yaru:ubuntu:GNOME | 1         | 0.01%   |
| xmonad            | 1         | 0.01%   |
| wmaker-common     | 1         | 0.01%   |
| ubuntu:pika:GNOME | 1         | 0.01%   |
| Lubuntu           | 1         | 0.01%   |
| LeftWM            | 1         | 0.01%   |
| INPT              | 1         | 0.01%   |
| Hypr              | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |
| dwm-sc            | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 7486      | 76.07%  |
| Wayland | 1594      | 16.2%   |
| Unknown | 455       | 4.62%   |
| Tty     | 305       | 3.1%    |
| Xcb     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3603      | 36.24%  |
| SDDM    | 1786      | 17.96%  |
| GDM     | 1627      | 16.36%  |
| GDM3    | 1255      | 12.62%  |
| LightDM | 1184      | 11.91%  |
| TDM     | 334       | 3.36%   |
| KDM     | 111       | 1.12%   |
| SLiM    | 12        | 0.12%   |
| XDM     | 11        | 0.11%   |
| Ly      | 8         | 0.08%   |
| LXDM    | 5         | 0.05%   |
| NODM    | 3         | 0.03%   |
| GREETD  | 2         | 0.02%   |
| WDM     | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| fr_FR       | 6815      | 69.99%  |
| en_US       | 1648      | 16.93%  |
| Unknown     | 761       | 7.82%   |
| en_GB       | 167       | 1.72%   |
| C           | 108       | 1.11%   |
| de_DE       | 30        | 0.31%   |
| ru_RU       | 23        | 0.24%   |
| it_IT       | 16        | 0.16%   |
| es_ES       | 15        | 0.15%   |
| nl_NL       | 12        | 0.12%   |
| fr_CH       | 12        | 0.12%   |
| en_IE       | 12        | 0.12%   |
| pl_PL       | 10        | 0.1%    |
| fr_CA       | 10        | 0.1%    |
| pt_PT       | 8         | 0.08%   |
| fr_BE       | 7         | 0.07%   |
| POSIX       | 6         | 0.06%   |
| en_DK       | 5         | 0.05%   |
| C.UTF8      | 5         | 0.05%   |
| sv_SE       | 4         | 0.04%   |
| ru_UA       | 4         | 0.04%   |
| en_IN       | 4         | 0.04%   |
| en_AU       | 4         | 0.04%   |
| pt_BR       | 3         | 0.03%   |
| fr_LU       | 3         | 0.03%   |
| fr_FR.UTF8  | 3         | 0.03%   |
| en_AG       | 3         | 0.03%   |
| ro_RO       | 2         | 0.02%   |
| nb_NO       | 2         | 0.02%   |
| hu_HU       | 2         | 0.02%   |
| fr_FR.utf-8 | 2         | 0.02%   |
| en_CA       | 2         | 0.02%   |
| cs_CZ       | 2         | 0.02%   |
| zh_CN       | 1         | 0.01%   |
| UTF-8       | 1         | 0.01%   |
| tr_TR       | 1         | 0.01%   |
| sr_RS@latin | 1         | 0.01%   |
| sr_RS       | 1         | 0.01%   |
| sk_SK       | 1         | 0.01%   |
| oc_FR       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 5094      | 52.32%  |
| BIOS | 4643      | 47.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 7695      | 78.52%  |
| Overlay  | 901       | 9.19%   |
| Btrfs    | 629       | 6.42%   |
| Unknown  | 223       | 2.28%   |
| Tmpfs    | 141       | 1.44%   |
| Xfs      | 101       | 1.03%   |
| Zfs      | 58        | 0.59%   |
| F2fs     | 16        | 0.16%   |
| Ext2     | 16        | 0.16%   |
| Ext3     | 14        | 0.14%   |
| Reiserfs | 3         | 0.03%   |
| Rootfs   | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |
| Aufs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4509      | 45.97%  |
| Unknown | 3774      | 38.48%  |
| MBR     | 1525      | 15.55%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7913      | 81.21%  |
| Yes       | 1831      | 18.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6565      | 67.58%  |
| Yes       | 3149      | 32.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1898      | 19.9%   |
| Dell                    | 1381      | 14.48%  |
| Hewlett-Packard         | 1231      | 12.9%   |
| Lenovo                  | 1065      | 11.16%  |
| MSI                     | 796       | 8.34%   |
| Gigabyte Technology     | 565       | 5.92%   |
| Acer                    | 487       | 5.1%    |
| ASRock                  | 227       | 2.38%   |
| Toshiba                 | 178       | 1.87%   |
| Apple                   | 171       | 1.79%   |
| Intel                   | 136       | 1.43%   |
| Packard Bell            | 104       | 1.09%   |
| Notebook                | 94        | 0.99%   |
| HUAWEI                  | 84        | 0.88%   |
| Unknown                 | 77        | 0.81%   |
| Samsung Electronics     | 73        | 0.77%   |
| Sony                    | 67        | 0.7%    |
| Foxconn                 | 52        | 0.55%   |
| Fujitsu                 | 49        | 0.51%   |
| Pegatron                | 45        | 0.47%   |
| Raspberry Pi Foundation | 44        | 0.46%   |
| eMachines               | 40        | 0.42%   |
| Medion                  | 34        | 0.36%   |
| TUXEDO                  | 29        | 0.3%    |
| Valve                   | 27        | 0.28%   |
| Thomson                 | 27        | 0.28%   |
| Alienware               | 27        | 0.28%   |
| Supermicro              | 26        | 0.27%   |
| AZW                     | 26        | 0.27%   |
| Timi                    | 25        | 0.26%   |
| Microsoft               | 24        | 0.25%   |
| UNOWHY                  | 22        | 0.23%   |
| Fujitsu Siemens         | 22        | 0.23%   |
| Clevo                   | 20        | 0.21%   |
| Shuttle                 | 19        | 0.2%    |
| Chuwi                   | 16        | 0.17%   |
| BESSTAR Tech            | 16        | 0.17%   |
| PC Specialist           | 15        | 0.16%   |
| Google                  | 15        | 0.16%   |
| ZOTAC                   | 14        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| ASUS All Series           | 132       | 1.38%   |
| Unknown                   | 99        | 1.04%   |
| HP Notebook               | 42        | 0.44%   |
| HP Pavilion 17            | 32        | 0.34%   |
| Gigabyte B450M DS3H       | 29        | 0.3%    |
| HP Pavilion dv6           | 28        | 0.29%   |
| Valve Jupiter             | 27        | 0.28%   |
| HP Pavilion dv7           | 26        | 0.27%   |
| Dell OptiPlex 390         | 23        | 0.24%   |
| ASUS S551LN               | 22        | 0.23%   |
| Dell OptiPlex 7010        | 21        | 0.22%   |
| Dell OptiPlex 9020        | 20        | 0.21%   |
| HP Pavilion g7            | 18        | 0.19%   |
| Dell XPS 13 9310          | 18        | 0.19%   |
| ASUS PRIME A320M-K        | 18        | 0.19%   |
| MSI MS-7C91               | 17        | 0.18%   |
| MSI MS-7816               | 17        | 0.18%   |
| Dell OptiPlex 3020        | 16        | 0.17%   |
| MSI MS-7C37               | 15        | 0.16%   |
| MSI MS-7C02               | 15        | 0.16%   |
| HP Pavilion Notebook      | 15        | 0.16%   |
| HP EliteBook 840 G3       | 15        | 0.16%   |
| Dell XPS 13 9380          | 15        | 0.16%   |
| Dell XPS 13 7390          | 15        | 0.16%   |
| Dell Latitude E6420       | 15        | 0.16%   |
| MSI MS-7817               | 14        | 0.15%   |
| HUAWEI HVY-WXX9           | 14        | 0.15%   |
| HP Pavilion 15            | 14        | 0.15%   |
| Dell XPS 15 9570          | 14        | 0.15%   |
| Dell Latitude 5420        | 14        | 0.15%   |
| Dell Latitude 5400        | 14        | 0.15%   |
| MSI MS-7758               | 13        | 0.14%   |
| HP Pavilion g6            | 13        | 0.14%   |
| HP EliteBook 840 G2       | 13        | 0.14%   |
| HP Compaq Elite 8300 SFF  | 13        | 0.14%   |
| Gigabyte B450 AORUS ELITE | 13        | 0.14%   |
| Gigabyte 970A-DS3P        | 13        | 0.14%   |
| Dell XPS 15 9500          | 13        | 0.14%   |
| Dell XPS 15 7590          | 13        | 0.14%   |
| Dell Latitude E6400       | 13        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 521       | 5.46%   |
| Dell Latitude         | 385       | 4.04%   |
| Acer Aspire           | 323       | 3.39%   |
| HP Pavilion           | 259       | 2.71%   |
| Dell Precision        | 258       | 2.7%    |
| Dell OptiPlex         | 203       | 2.13%   |
| Dell XPS              | 189       | 1.98%   |
| HP EliteBook          | 186       | 1.95%   |
| Dell Inspiron         | 184       | 1.93%   |
| Lenovo IdeaPad        | 172       | 1.8%    |
| ASUS PRIME            | 159       | 1.67%   |
| Toshiba Satellite     | 147       | 1.54%   |
| ASUS VivoBook         | 137       | 1.44%   |
| HP ProBook            | 134       | 1.4%    |
| ASUS All              | 132       | 1.38%   |
| HP Compaq             | 128       | 1.34%   |
| ASUS ROG              | 126       | 1.32%   |
| Lenovo ThinkCentre    | 105       | 1.1%    |
| Unknown               | 99        | 1.04%   |
| ASUS TUF              | 86        | 0.9%    |
| HP Laptop             | 84        | 0.88%   |
| ASUS ZenBook          | 65        | 0.68%   |
| Dell Vostro           | 55        | 0.58%   |
| Packard Bell EasyNote | 53        | 0.56%   |
| Acer Swift            | 50        | 0.52%   |
| Lenovo Legion         | 45        | 0.47%   |
| RPi Raspberry         | 44        | 0.46%   |
| HP Notebook           | 42        | 0.44%   |
| HP ENVY               | 41        | 0.43%   |
| HP ZBook              | 38        | 0.4%    |
| Lenovo Yoga           | 37        | 0.39%   |
| Gigabyte B450M        | 35        | 0.37%   |
| ASUS ASUS             | 34        | 0.36%   |
| HP ProDesk            | 32        | 0.34%   |
| HP EliteDesk          | 32        | 0.34%   |
| Packard Bell IMEDIA   | 30        | 0.31%   |
| Acer Nitro            | 30        | 0.31%   |
| Dell PowerEdge        | 29        | 0.3%    |
| Valve Jupiter         | 27        | 0.28%   |
| Gigabyte B450         | 27        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 879       | 9.21%   |
| 2020    | 856       | 8.97%   |
| 2019    | 829       | 8.69%   |
| 2012    | 738       | 7.74%   |
| 2013    | 709       | 7.43%   |
| 2021    | 635       | 6.66%   |
| 2011    | 623       | 6.53%   |
| 2014    | 563       | 5.9%    |
| 2015    | 556       | 5.83%   |
| 2017    | 538       | 5.64%   |
| 2010    | 499       | 5.23%   |
| 2016    | 485       | 5.08%   |
| 2008    | 417       | 4.37%   |
| 2009    | 415       | 4.35%   |
| 2022    | 301       | 3.16%   |
| 2007    | 206       | 2.16%   |
| 2006    | 106       | 1.11%   |
| Unknown | 69        | 0.72%   |
| 2005    | 48        | 0.5%    |
| 2023    | 43        | 0.45%   |
| 2004    | 12        | 0.13%   |
| 2003    | 9         | 0.09%   |
| 2002    | 2         | 0.02%   |
| 2001    | 2         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 5289      | 55.44%  |
| Desktop        | 3646      | 38.22%  |
| Convertible    | 151       | 1.58%   |
| Mini pc        | 138       | 1.45%   |
| All in one     | 108       | 1.13%   |
| Server         | 74        | 0.78%   |
| System on chip | 64        | 0.67%   |
| Tablet         | 59        | 0.62%   |
| Phone          | 10        | 0.1%    |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 8785      | 91.5%   |
| Enabled  | 816       | 8.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9517      | 99.75%  |
| Yes  | 24        | 0.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 2144      | 22.14%  |
| 3.01-4.0        | 2031      | 20.97%  |
| 16.01-24.0      | 1982      | 20.47%  |
| 8.01-16.0       | 1661      | 17.15%  |
| 32.01-64.0      | 855       | 8.83%   |
| 1.01-2.0        | 373       | 3.85%   |
| 64.01-256.0     | 221       | 2.28%   |
| 2.01-3.0        | 162       | 1.67%   |
| 24.01-32.0      | 154       | 1.59%   |
| 0.51-1.0        | 69        | 0.71%   |
| 0.01-0.5        | 15        | 0.15%   |
| More than 256.0 | 12        | 0.12%   |
| Unknown         | 5         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 3660      | 34.79%  |
| 2.01-3.0    | 2587      | 24.59%  |
| 4.01-8.0    | 1536      | 14.6%   |
| 3.01-4.0    | 1353      | 12.86%  |
| 0.51-1.0    | 688       | 6.54%   |
| 8.01-16.0   | 430       | 4.09%   |
| 0.01-0.5    | 146       | 1.39%   |
| 16.01-24.0  | 67        | 0.64%   |
| 24.01-32.0  | 21        | 0.2%    |
| 32.01-64.0  | 19        | 0.18%   |
| Unknown     | 9         | 0.09%   |
| 64.01-256.0 | 5         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5726      | 58.39%  |
| 2       | 2474      | 25.23%  |
| 3       | 799       | 8.15%   |
| 4       | 377       | 3.84%   |
| 5       | 168       | 1.71%   |
| 6       | 92        | 0.94%   |
| 0       | 82        | 0.84%   |
| 7       | 46        | 0.47%   |
| 8       | 16        | 0.16%   |
| 9       | 10        | 0.1%    |
| Unknown | 4         | 0.04%   |
| 11      | 3         | 0.03%   |
| 13      | 2         | 0.02%   |
| 10      | 2         | 0.02%   |
| 25      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |
| 21      | 1         | 0.01%   |
| 17      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5456      | 56.7%   |
| Yes       | 4167      | 43.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8315      | 86.92%  |
| No        | 1251      | 13.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7055      | 73.41%  |
| No        | 2555      | 26.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5439      | 56.29%  |
| No        | 4223      | 43.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| France  | 9540      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 1469      | 14.19%  |
| Lyon             | 201       | 1.94%   |
| Marseille        | 186       | 1.8%    |
| Toulouse         | 156       | 1.51%   |
| Nantes           | 124       | 1.2%    |
| Strasbourg       | 110       | 1.06%   |
| Montpellier      | 103       | 0.99%   |
| Rennes           | 93        | 0.9%    |
| Bordeaux         | 86        | 0.83%   |
| Lille            | 79        | 0.76%   |
| Grenoble         | 76        | 0.73%   |
| Roubaix          | 73        | 0.7%    |
| Nice             | 67        | 0.65%   |
| Clichy-sous-Bois | 61        | 0.59%   |
| Brest            | 47        | 0.45%   |
| Caen             | 46        | 0.44%   |
| Villeurbanne     | 43        | 0.42%   |
| Tours            | 41        | 0.4%    |
| Poitiers         | 41        | 0.4%    |
| La Rochelle      | 40        | 0.39%   |
| Rouen            | 39        | 0.38%   |
| Toulon           | 35        | 0.34%   |
| Argenteuil       | 35        | 0.34%   |
| Clermont-Ferrand | 32        | 0.31%   |
| Aix-en-Provence  | 32        | 0.31%   |
| Nancy            | 31        | 0.3%    |
| Nîmes           | 30        | 0.29%   |
| Metz             | 30        | 0.29%   |
| Limoges          | 30        | 0.29%   |
| Dijon            | 30        | 0.29%   |
| Versailles       | 29        | 0.28%   |
| Pau              | 29        | 0.28%   |
| Orléans         | 29        | 0.28%   |
| Besançon        | 29        | 0.28%   |
| Angers           | 29        | 0.28%   |
| Amiens           | 29        | 0.28%   |
| Valenciennes     | 28        | 0.27%   |
| Perpignan        | 28        | 0.27%   |
| Cergy            | 27        | 0.26%   |
| Saint-Denis      | 25        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2206      | 3395   | 15.66%  |
| Seagate                     | 2167      | 3303   | 15.38%  |
| WDC                         | 2011      | 3088   | 14.27%  |
| Crucial                     | 972       | 1356   | 6.9%    |
| Toshiba                     | 894       | 1169   | 6.34%   |
| Sandisk                     | 692       | 891    | 4.91%   |
| Kingston                    | 670       | 833    | 4.75%   |
| Unknown                     | 534       | 710    | 3.79%   |
| Hitachi                     | 417       | 532    | 2.96%   |
| SK hynix                    | 398       | 487    | 2.82%   |
| HGST                        | 364       | 481    | 2.58%   |
| Intel                       | 312       | 389    | 2.21%   |
| Micron Technology           | 252       | 297    | 1.79%   |
| PNY                         | 180       | 220    | 1.28%   |
| KIOXIA                      | 120       | 137    | 0.85%   |
| Maxtor                      | 110       | 144    | 0.78%   |
| China                       | 104       | 127    | 0.74%   |
| LDLC                        | 102       | 150    | 0.72%   |
| Phison                      | 91        | 110    | 0.65%   |
| Transcend                   | 85        | 99     | 0.6%    |
| Corsair                     | 77        | 92     | 0.55%   |
| Micron/Crucial Technology   | 73        | 100    | 0.52%   |
| Apple                       | 68        | 86     | 0.48%   |
| SPCC                        | 67        | 84     | 0.48%   |
| OCZ                         | 54        | 73     | 0.38%   |
| LITEON                      | 52        | 58     | 0.37%   |
| Fujitsu                     | 52        | 71     | 0.37%   |
| JMicron Technology          | 47        | 61     | 0.33%   |
| Unknown                     | 44        | 51     | 0.31%   |
| A-DATA Technology           | 42        | 51     | 0.3%    |
| Phison Electronics          | 40        | 51     | 0.28%   |
| LITEONIT                    | 36        | 38     | 0.26%   |
| Emtec                       | 35        | 43     | 0.25%   |
| Silicon Motion              | 34        | 48     | 0.24%   |
| Kingston Technology Company | 30        | 32     | 0.21%   |
| Gigabyte Technology         | 27        | 32     | 0.19%   |
| ASMT                        | 24        | 31     | 0.17%   |
| Intenso                     | 23        | 27     | 0.16%   |
| KingSpec                    | 17        | 20     | 0.12%   |
| Hewlett-Packard             | 17        | 61     | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB                        | 154       | 0.99%   |
| Samsung SSD 860 EVO 500GB                           | 148       | 0.95%   |
| Crucial CT500MX500SSD1 500GB                        | 139       | 0.89%   |
| HGST HTS721010A9E630 1TB                            | 117       | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB                      | 115       | 0.74%   |
| Kingston SA400S37240G 240GB SSD                     | 112       | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 105       | 0.68%   |
| Toshiba MQ01ABD100 1TB                              | 103       | 0.66%   |
| Samsung SSD 850 EVO 250GB                           | 97        | 0.62%   |
| Samsung SSD 850 EVO 500GB                           | 96        | 0.62%   |
| Seagate ST500DM002-1BD142 500GB                     | 95        | 0.61%   |
| Seagate ST2000DM008-2FR102 2TB                      | 93        | 0.6%    |
| Crucial CT1000MX500SSD1 1TB                         | 92        | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB                      | 91        | 0.59%   |
| Unknown MMC Card  32GB                              | 80        | 0.52%   |
| Samsung SSD 860 EVO 1TB                             | 75        | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB                      | 74        | 0.48%   |
| Crucial CT480BX500SSD1 480GB                        | 74        | 0.48%   |
| Unknown MMC Card  64GB                              | 71        | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB                      | 70        | 0.45%   |
| Toshiba MQ04ABF100 1TB                              | 67        | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB                      | 66        | 0.42%   |
| Samsung SSD 860 EVO 250GB                           | 66        | 0.42%   |
| Kingston SA400S37120G 120GB SSD                     | 64        | 0.41%   |
| Samsung SSD 870 QVO 1TB                             | 63        | 0.41%   |
| HGST HTS541010A9E680 1TB                            | 63        | 0.41%   |
| Unknown SD/MMC/MS PRO 1GB                           | 62        | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB                      | 61        | 0.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 61        | 0.39%   |
| Kingston SA400S37480G 480GB SSD                     | 61        | 0.39%   |
| Toshiba DT01ACA100 1TB                              | 58        | 0.37%   |
| Samsung NVMe SSD Drive 512GB                        | 55        | 0.35%   |
| PNY CS900 120GB SSD                                 | 55        | 0.35%   |
| PNY CS900 240GB SSD                                 | 54        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD                    | 52        | 0.33%   |
| Crucial CT120BX500SSD1 120GB                        | 51        | 0.33%   |
| Samsung SSD 860 QVO 1TB                             | 50        | 0.32%   |
| SanDisk NVMe SSD Drive 512GB                        | 49        | 0.32%   |
| Seagate ST4000DM004-2CV104 4TB                      | 47        | 0.3%    |
| Samsung NVMe SSD Drive 500GB                        | 47        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2132      | 3227   | 36.3%   |
| WDC                 | 1660      | 2606   | 28.26%  |
| Toshiba             | 681       | 876    | 11.6%   |
| Hitachi             | 417       | 532    | 7.1%    |
| HGST                | 363       | 479    | 6.18%   |
| Samsung Electronics | 265       | 399    | 4.51%   |
| Maxtor              | 110       | 144    | 1.87%   |
| Unknown             | 69        | 79     | 1.17%   |
| Fujitsu             | 51        | 70     | 0.87%   |
| Apple               | 19        | 21     | 0.32%   |
| SABRENT             | 13        | 13     | 0.22%   |
| ASMT                | 11        | 16     | 0.19%   |
| Hewlett-Packard     | 9         | 24     | 0.15%   |
| Inateck             | 8         | 8      | 0.14%   |
| Magnetic Data       | 6         | 6      | 0.1%    |
| LaCie               | 5         | 5      | 0.09%   |
| IBM/Hitachi         | 5         | 6      | 0.09%   |
| ASMedia             | 5         | 5      | 0.09%   |
| USB3.0              | 4         | 4      | 0.07%   |
| JMicron Technology  | 4         | 10     | 0.07%   |
| HGST HTS            | 4         | 6      | 0.07%   |
| Intenso             | 3         | 4      | 0.05%   |
| ASMT109x            | 3         | 4      | 0.05%   |
| USB                 | 2         | 4      | 0.03%   |
| RSH-319             | 2         | 3      | 0.03%   |
| PHD 3.0             | 2         | 2      | 0.03%   |
| Initio              | 2         | 2      | 0.03%   |
| H/W                 | 2         | 16     | 0.03%   |
| External            | 2         | 2      | 0.03%   |
| Storeva             | 1         | 1      | 0.02%   |
| StoreJet            | 1         | 1      | 0.02%   |
| SILICONMOTION       | 1         | 1      | 0.02%   |
| QEMU                | 1         | 1      | 0.02%   |
| MDT                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| ICY BOX             | 1         | 1      | 0.02%   |
| IB-AC703            | 1         | 1      | 0.02%   |
| HPE                 | 1         | 4      | 0.02%   |
| Generic-            | 1         | 1      | 0.02%   |
| ExcelStor           | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1182      | 1698   | 24.97%  |
| Crucial             | 866       | 1201   | 18.29%  |
| Kingston            | 549       | 688    | 11.6%   |
| SanDisk             | 468       | 586    | 9.89%   |
| PNY                 | 163       | 198    | 3.44%   |
| WDC                 | 146       | 174    | 3.08%   |
| Intel               | 123       | 146    | 2.6%    |
| China               | 103       | 126    | 2.18%   |
| Micron Technology   | 100       | 131    | 2.11%   |
| SK hynix            | 97        | 120    | 2.05%   |
| Transcend           | 81        | 95     | 1.71%   |
| LDLC                | 74        | 97     | 1.56%   |
| Toshiba             | 59        | 75     | 1.25%   |
| SPCC                | 59        | 76     | 1.25%   |
| OCZ                 | 53        | 69     | 1.12%   |
| LITEON              | 44        | 48     | 0.93%   |
| Apple               | 43        | 55     | 0.91%   |
| Corsair             | 41        | 47     | 0.87%   |
| LITEONIT            | 36        | 38     | 0.76%   |
| A-DATA Technology   | 34        | 43     | 0.72%   |
| Emtec               | 32        | 37     | 0.68%   |
| JMicron Technology  | 28        | 35     | 0.59%   |
| KingSpec            | 17        | 20     | 0.36%   |
| Intenso             | 17        | 20     | 0.36%   |
| Unknown             | 16        | 21     | 0.34%   |
| Patriot             | 14        | 20     | 0.3%    |
| Plextor             | 12        | 19     | 0.25%   |
| Netac               | 12        | 14     | 0.25%   |
| ASMT                | 12        | 14     | 0.25%   |
| Verbatim            | 11        | 11     | 0.23%   |
| TEXTORM             | 11        | 13     | 0.23%   |
| Gigabyte Technology | 11        | 14     | 0.23%   |
| Dogfish             | 11        | 18     | 0.23%   |
| KingDian            | 10        | 15     | 0.21%   |
| BHT                 | 10        | 14     | 0.21%   |
| Teclast             | 8         | 10     | 0.17%   |
| Apacer              | 8         | 8      | 0.17%   |
| Seagate             | 7         | 7      | 0.15%   |
| BAITITON            | 7         | 7      | 0.15%   |
| Unknown             | 6         | 10     | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4895      | 8590   | 39.14%  |
| SSD     | 4097      | 6221   | 32.76%  |
| NVMe    | 2835      | 3949   | 22.67%  |
| MMC     | 480       | 638    | 3.84%   |
| Unknown | 200       | 310    | 1.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 7193      | 14324  | 65.18%  |
| NVMe | 2830      | 3930   | 25.64%  |
| SAS  | 533       | 816    | 4.83%   |
| MMC  | 480       | 638    | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 5290      | 8426   | 56.01%  |
| 0.51-1.0   | 2847      | 4230   | 30.14%  |
| 1.01-2.0   | 812       | 1302   | 8.6%    |
| 3.01-4.0   | 232       | 380    | 2.46%   |
| 2.01-3.0   | 150       | 254    | 1.59%   |
| 4.01-10.0  | 94        | 170    | 1%      |
| 10.01-20.0 | 20        | 49     | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2511      | 24.89%  |
| 251-500        | 2275      | 22.55%  |
| 501-1000       | 1646      | 16.32%  |
| 1001-2000      | 803       | 7.96%   |
| 1-20           | 799       | 7.92%   |
| 51-100         | 552       | 5.47%   |
| More than 3000 | 481       | 4.77%   |
| 21-50          | 370       | 3.67%   |
| Unknown        | 338       | 3.35%   |
| 2001-3000      | 313       | 3.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3710      | 35.63%  |
| 21-50          | 1641      | 15.76%  |
| 101-250        | 1349      | 12.95%  |
| 51-100         | 1212      | 11.64%  |
| 251-500        | 875       | 8.4%    |
| 501-1000       | 644       | 6.18%   |
| 1001-2000      | 345       | 3.31%   |
| Unknown        | 338       | 3.25%   |
| More than 3000 | 169       | 1.62%   |
| 2001-3000      | 128       | 1.23%   |
| 0              | 3         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB           | 22        | 26     | 1.79%   |
| HGST HTS541010A9E680 1TB           | 16        | 17     | 1.3%    |
| Seagate ST500LM021-1KJ152 500GB    | 15        | 17     | 1.22%   |
| Seagate ST500DM002-1BD142 500GB    | 15        | 16     | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 14        | 15     | 1.14%   |
| Toshiba MQ01ABD100 1TB             | 12        | 14     | 0.98%   |
| Seagate ST9500325AS 500GB          | 12        | 13     | 0.98%   |
| Seagate ST500LT012-1DG142 500GB    | 9         | 9      | 0.73%   |
| Seagate ST2000DM001-1CH164 2TB     | 9         | 10     | 0.73%   |
| Seagate ST1000LM035-1RK172 1TB     | 9         | 9      | 0.73%   |
| WDC WD10JPVX-22JC3T0 1TB           | 8         | 8      | 0.65%   |
| Seagate ST2000DM001-1ER164 2TB     | 8         | 11     | 0.65%   |
| WDC WD10EADS-22M2B0 1TB            | 7         | 7      | 0.57%   |
| Seagate ST31000528AS 1TB           | 7         | 7      | 0.57%   |
| Samsung Electronics HD103SJ 1TB    | 7         | 8      | 0.57%   |
| HGST HTS725050A7E630 500GB         | 7         | 9      | 0.57%   |
| Toshiba MQ01ABF050 500GB           | 6         | 6      | 0.49%   |
| Toshiba MQ01ABD050 500GB           | 6         | 6      | 0.49%   |
| Seagate ST3250310AS 250GB          | 6         | 6      | 0.49%   |
| Seagate ST320LT007-9ZV142 320GB    | 6         | 7      | 0.49%   |
| Seagate ST31000524AS 1TB           | 6         | 6      | 0.49%   |
| LDLC SSD 120GB                     | 6         | 8      | 0.49%   |
| Kingston SV300S37A120G 120GB SSD   | 6         | 8      | 0.49%   |
| HGST HTS545050A7E380 500GB         | 6         | 6      | 0.49%   |
| Crucial CT525MX300SSD1 528GB       | 6         | 6      | 0.49%   |
| Crucial CT240M500SSD1 240GB        | 6         | 7      | 0.49%   |
| WDC WD6400AAKS-22A7B2 640GB        | 5         | 8      | 0.41%   |
| WDC WD10EARS-00Y5B1 1TB            | 5         | 6      | 0.41%   |
| WDC WD10EADS-65L5B1 1TB            | 5         | 5      | 0.41%   |
| WDC WD10EADS-00M2B0 1TB            | 5         | 7      | 0.41%   |
| Toshiba DT01ACA100 1TB             | 5         | 6      | 0.41%   |
| Seagate ST3500418AS 500GB          | 5         | 5      | 0.41%   |
| Seagate ST3320820AS 320GB          | 5         | 5      | 0.41%   |
| Seagate ST1000DM003-9YN162 1TB     | 5         | 6      | 0.41%   |
| Seagate ST1000DM003-1CH162 1TB     | 5         | 5      | 0.41%   |
| Samsung Electronics HD103UJ 1TB    | 5         | 7      | 0.41%   |
| Maxtor 6V160E0 160GB               | 5         | 5      | 0.41%   |
| Hitachi HTS727575A9E364 752GB      | 5         | 5      | 0.41%   |
| Hitachi HTS547575A9E384 752GB      | 5         | 5      | 0.41%   |
| Hitachi HTS545050B9A300 500GB      | 5         | 5      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 296       | 347    | 24.69%  |
| WDC                 | 263       | 321    | 21.93%  |
| Hitachi             | 98        | 110    | 8.17%   |
| Toshiba             | 93        | 104    | 7.76%   |
| Samsung Electronics | 85        | 100    | 7.09%   |
| HGST                | 68        | 79     | 5.67%   |
| Crucial             | 44        | 48     | 3.67%   |
| Maxtor              | 38        | 43     | 3.17%   |
| Kingston            | 33        | 38     | 2.75%   |
| Intel               | 30        | 35     | 2.5%    |
| SK hynix            | 28        | 35     | 2.34%   |
| SanDisk             | 28        | 34     | 2.34%   |
| Fujitsu             | 10        | 10     | 0.83%   |
| OCZ                 | 9         | 10     | 0.75%   |
| LDLC                | 9         | 11     | 0.75%   |
| Micron Technology   | 8         | 10     | 0.67%   |
| China               | 5         | 5      | 0.42%   |
| LITEONIT            | 4         | 4      | 0.33%   |
| Corsair             | 4         | 5      | 0.33%   |
| A-DATA Technology   | 4         | 4      | 0.33%   |
| SPCC                | 3         | 3      | 0.25%   |
| Netac               | 3         | 3      | 0.25%   |
| LITEON              | 3         | 3      | 0.25%   |
| Apple               | 3         | 3      | 0.25%   |
| Apacer              | 3         | 3      | 0.25%   |
| 2.5"                | 3         | 6      | 0.25%   |
| KingSpec            | 2         | 2      | 0.17%   |
| JMicron Technology  | 2         | 2      | 0.17%   |
| Intenso             | 2         | 2      | 0.17%   |
| Hewlett-Packard     | 2         | 2      | 0.17%   |
| Dogfish             | 2         | 2      | 0.17%   |
| ASMT                | 2         | 2      | 0.17%   |
| Unknown             | 1         | 1      | 0.08%   |
| Transcend           | 1         | 2      | 0.08%   |
| TEXTORM             | 1         | 1      | 0.08%   |
| TakeMS              | 1         | 1      | 0.08%   |
| SSSTC               | 1         | 1      | 0.08%   |
| SABRENT             | 1         | 1      | 0.08%   |
| Phison              | 1         | 1      | 0.08%   |
| OCZ-VERTEX          | 1         | 1      | 0.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 296       | 347    | 32.35%  |
| WDC                 | 256       | 314    | 27.98%  |
| Hitachi             | 98        | 110    | 10.71%  |
| Toshiba             | 88        | 99     | 9.62%   |
| HGST                | 68        | 79     | 7.43%   |
| Samsung Electronics | 52        | 60     | 5.68%   |
| Maxtor              | 38        | 43     | 4.15%   |
| Fujitsu             | 10        | 10     | 1.09%   |
| Hewlett-Packard     | 2         | 2      | 0.22%   |
| ASMT                | 2         | 2      | 0.22%   |
| Unknown             | 1         | 1      | 0.11%   |
| SABRENT             | 1         | 1      | 0.11%   |
| Magnetic Data       | 1         | 1      | 0.11%   |
| IBM/Hitachi         | 1         | 1      | 0.11%   |
| Apple               | 1         | 1      | 0.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 848       | 1071   | 75.11%  |
| SSD     | 256       | 299    | 22.67%  |
| NVMe    | 23        | 27     | 2.04%   |
| Unknown | 2         | 2      | 0.18%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB                     | 2         | 3      | 5.71%   |
| WDC WD3200BEVT-11ZCT0 320GB                      | 2         | 2      | 5.71%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 2         | 5      | 5.71%   |
| WDC WD800BB-00FJA0 80GB                          | 1         | 1      | 2.86%   |
| WDC WD5000BEVT-35A0RT0 500GB                     | 1         | 1      | 2.86%   |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 2.86%   |
| WDC WD3200AAJS-22VWA0 320GB                      | 1         | 1      | 2.86%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 2      | 2.86%   |
| WDC WD20EARS-00J99B0 2TB                         | 1         | 2      | 2.86%   |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 2.86%   |
| WDC WD10EALX-759BA1 1TB                          | 1         | 1      | 2.86%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 2.86%   |
| Toshiba MQ02ABF050H 500GB                        | 1         | 1      | 2.86%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 2.86%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 2.86%   |
| Toshiba MK5055GSX 500GB                          | 1         | 1      | 2.86%   |
| Toshiba MK3259GSXP 320GB                         | 1         | 2      | 2.86%   |
| SK hynix HFS128G39TND-N210A 128GB SSD            | 1         | 1      | 2.86%   |
| Seagate ST3500418ASQ 500GB                       | 1         | 1      | 2.86%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 2.86%   |
| Seagate ST3300657SS 304GB                        | 1         | 2      | 2.86%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 2.86%   |
| Seagate ST1000LM048-2E7172 1TB                   | 1         | 1      | 2.86%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB      | 1         | 1      | 2.86%   |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 2.86%   |
| Samsung Electronics HE103SJ 1TB                  | 1         | 2      | 2.86%   |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 2.86%   |
| Samsung Electronics HD501LJ 500GB                | 1         | 1      | 2.86%   |
| Kingston SMS200S360G 64GB SSD                    | 1         | 1      | 2.86%   |
| Intel SSDSC2KW256G8 256GB                        | 1         | 1      | 2.86%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 2.86%   |
| HGST HTS545050A7E380 500GB                       | 1         | 1      | 2.86%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 15     | 34.29%  |
| Samsung Electronics | 7         | 11     | 20%     |
| Toshiba             | 6         | 7      | 17.14%  |
| Seagate             | 5         | 6      | 14.29%  |
| HGST                | 2         | 2      | 5.71%   |
| SK hynix            | 1         | 1      | 2.86%   |
| Kingston            | 1         | 1      | 2.86%   |
| Intel               | 1         | 1      | 2.86%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 4887      | 8679   | 46.14%  |
| Detected | 4576      | 9583   | 43.21%  |
| Malfunc  | 1090      | 1399   | 10.29%  |
| Failed   | 35        | 44     | 0.33%   |
| Fixed    | 2         | 2      | 0.02%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6533      | 54.65%  |
| AMD                              | 1654      | 13.84%  |
| Samsung Electronics              | 959       | 8.02%   |
| SanDisk                          | 445       | 3.72%   |
| SK hynix                         | 291       | 2.43%   |
| Nvidia                           | 210       | 1.76%   |
| Phison Electronics               | 185       | 1.55%   |
| Toshiba America Info Systems     | 182       | 1.52%   |
| Micron/Crucial Technology        | 181       | 1.51%   |
| Marvell Technology Group         | 174       | 1.46%   |
| ASMedia Technology               | 168       | 1.41%   |
| Micron Technology                | 162       | 1.36%   |
| Kingston Technology Company      | 155       | 1.3%    |
| JMicron Technology               | 149       | 1.25%   |
| KIOXIA                           | 110       | 0.92%   |
| VIA Technologies                 | 58        | 0.49%   |
| Silicon Motion                   | 47        | 0.39%   |
| Broadcom / LSI                   | 31        | 0.26%   |
| LSI Logic / Symbios Logic        | 28        | 0.23%   |
| Silicon Image                    | 24        | 0.2%    |
| Silicon Integrated Systems [SiS] | 22        | 0.18%   |
| Union Memory (Shenzhen)          | 21        | 0.18%   |
| Lite-On Technology               | 21        | 0.18%   |
| Seagate Technology               | 17        | 0.14%   |
| Solid State Storage Technology   | 16        | 0.13%   |
| ADATA Technology                 | 15        | 0.13%   |
| Realtek Semiconductor            | 11        | 0.09%   |
| Adaptec                          | 11        | 0.09%   |
| Yangtze Memory Technologies      | 10        | 0.08%   |
| Shenzhen Longsys Electronics     | 8         | 0.07%   |
| Hewlett-Packard                  | 8         | 0.07%   |
| Integrated Technology Express    | 7         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.05%   |
| Lenovo                           | 6         | 0.05%   |
| Apple                            | 6         | 0.05%   |
| Promise Technology               | 3         | 0.03%   |
| O2 Micro                         | 3         | 0.03%   |
| INNOGRIT                         | 3         | 0.03%   |
| ULi Electronics                  | 2         | 0.02%   |
| Solidigm                         | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1096      | 7.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 504       | 3.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 449       | 3.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 418       | 3.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 388       | 2.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 306       | 2.22%   |
| Intel Volume Management Device NVMe RAID Controller                            | 277       | 2.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 262       | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 235       | 1.71%   |
| Samsung NVMe SSD Controller 980                                                | 232       | 1.69%   |
| AMD 400 Series Chipset SATA Controller                                         | 230       | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 227       | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 220       | 1.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 217       | 1.58%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 208       | 1.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 198       | 1.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 195       | 1.42%   |
| Intel SATA Controller [RAID mode]                                              | 190       | 1.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 165       | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 164       | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 159       | 1.16%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 150       | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 147       | 1.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 147       | 1.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 138       | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 137       | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 134       | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 129       | 0.94%   |
| AMD 500 Series Chipset SATA Controller                                         | 129       | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 128       | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 114       | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                          | 111       | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 110       | 0.8%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 107       | 0.78%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 107       | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 101       | 0.73%   |
| Phison E12 NVMe Controller                                                     | 100       | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 99        | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 99        | 0.72%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 98        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6828      | 56.71%  |
| NVMe | 2857      | 23.73%  |
| IDE  | 1376      | 11.43%  |
| RAID | 918       | 7.62%   |
| SAS  | 39        | 0.32%   |
| SCSI | 23        | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 7368      | 77.23%  |
| AMD                   | 2091      | 21.92%  |
| ARM                   | 72        | 0.75%   |
| QUALCOMM              | 4         | 0.04%   |
| CentaurHauls          | 3         | 0.03%   |
| Marvell Semiconductor | 1         | 0.01%   |
| Unknown               | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 123       | 1.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 85        | 0.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 79        | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 77        | 0.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 73        | 0.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 72        | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 70        | 0.73%   |
| AMD Ryzen 5 3600 6-Core Processor             | 65        | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 64        | 0.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 63        | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 59        | 0.62%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 58        | 0.61%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 57        | 0.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 56        | 0.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 54        | 0.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 54        | 0.56%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 53        | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 52        | 0.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 50        | 0.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 50        | 0.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 50        | 0.52%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 49        | 0.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 49        | 0.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 48        | 0.5%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 48        | 0.5%    |
| ARM Processor                                 | 48        | 0.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 45        | 0.47%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 41        | 0.43%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 40        | 0.42%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 39        | 0.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 39        | 0.41%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 39        | 0.41%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 39        | 0.41%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 38        | 0.4%    |
| Intel Core i5-6500 CPU @ 3.20GHz              | 37        | 0.39%   |
| Intel 12th Gen Core i7-12700H                 | 37        | 0.39%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 36        | 0.38%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 36        | 0.38%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 36        | 0.38%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 36        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2127      | 22.26%  |
| Intel Core i7           | 1715      | 17.94%  |
| Intel Core i3           | 750       | 7.85%   |
| Other                   | 717       | 7.5%    |
| AMD Ryzen 5             | 486       | 5.09%   |
| Intel Celeron           | 438       | 4.58%   |
| Intel Core 2 Duo        | 422       | 4.42%   |
| AMD Ryzen 7             | 387       | 4.05%   |
| Intel Pentium           | 261       | 2.73%   |
| Intel Xeon              | 248       | 2.59%   |
| Intel Atom              | 186       | 1.95%   |
| Intel Pentium Dual-Core | 126       | 1.32%   |
| AMD Ryzen 9             | 109       | 1.14%   |
| Intel Core 2 Quad       | 100       | 1.05%   |
| AMD FX                  | 99        | 1.04%   |
| AMD Ryzen 3             | 81        | 0.85%   |
| AMD A4                  | 73        | 0.76%   |
| Intel Pentium Dual      | 70        | 0.73%   |
| AMD Athlon II X2        | 64        | 0.67%   |
| Intel Core 2            | 63        | 0.66%   |
| AMD E1                  | 63        | 0.66%   |
| Intel Core i9           | 60        | 0.63%   |
| AMD Athlon 64 X2        | 59        | 0.62%   |
| AMD A6                  | 55        | 0.58%   |
| AMD A8                  | 54        | 0.57%   |
| AMD E2                  | 46        | 0.48%   |
| AMD Ryzen 7 PRO         | 43        | 0.45%   |
| AMD Phenom II X4        | 42        | 0.44%   |
| AMD E                   | 42        | 0.44%   |
| AMD Ryzen 5 PRO         | 35        | 0.37%   |
| Intel Genuine           | 34        | 0.36%   |
| Intel Pentium 4         | 33        | 0.35%   |
| AMD Athlon              | 30        | 0.31%   |
| Intel Pentium Silver    | 25        | 0.26%   |
| AMD A10                 | 23        | 0.24%   |
| Intel Pentium D         | 21        | 0.22%   |
| Intel Pentium Gold      | 19        | 0.2%    |
| AMD Athlon 64           | 19        | 0.2%    |
| AMD Sempron             | 18        | 0.19%   |
| AMD Athlon II           | 18        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3726      | 38.94%  |
| 4       | 3577      | 37.38%  |
| 6       | 930       | 9.72%   |
| 8       | 649       | 6.78%   |
| 1       | 254       | 2.65%   |
| 12      | 149       | 1.56%   |
| 14      | 56        | 0.59%   |
| 10      | 52        | 0.54%   |
| 3       | 52        | 0.54%   |
| 16      | 41        | 0.43%   |
| Unknown | 37        | 0.39%   |
| 24      | 13        | 0.14%   |
| 20      | 13        | 0.14%   |
| 32      | 9         | 0.09%   |
| 64      | 4         | 0.04%   |
| 40      | 2         | 0.02%   |
| 104     | 1         | 0.01%   |
| 48      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 9436      | 98.86%  |
| 2       | 98        | 1.03%   |
| Unknown | 7         | 0.07%   |
| 4       | 2         | 0.02%   |
| 3       | 1         | 0.01%   |
| 0       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6033      | 63.03%  |
| 1       | 3499      | 36.55%  |
| Unknown | 37        | 0.39%   |
| 4       | 3         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 9361      | 97.94%  |
| Unknown        | 120       | 1.26%   |
| 32-bit         | 71        | 0.74%   |
| 64-bit         | 6         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2196      | 22.18%  |
| 0x206a7    | 535       | 5.4%    |
| 0x306a9    | 531       | 5.36%   |
| 0x306c3    | 529       | 5.34%   |
| 0x1067a    | 385       | 3.89%   |
| 0x906ea    | 291       | 2.94%   |
| 0x506e3    | 246       | 2.48%   |
| 0x806c1    | 240       | 2.42%   |
| 0x806ec    | 213       | 2.15%   |
| 0x806ea    | 184       | 1.86%   |
| 0x40651    | 179       | 1.81%   |
| 0x406e3    | 175       | 1.77%   |
| 0x306d4    | 174       | 1.76%   |
| 0x906e9    | 169       | 1.71%   |
| 0x806e9    | 150       | 1.51%   |
| 0x20655    | 145       | 1.46%   |
| 0x6fd      | 140       | 1.41%   |
| 0x08108109 | 111       | 1.12%   |
| 0x010000c8 | 108       | 1.09%   |
| 0x08701021 | 103       | 1.04%   |
| 0x10676    | 94        | 0.95%   |
| 0x08600106 | 89        | 0.9%    |
| 0xa0652    | 85        | 0.86%   |
| 0x30678    | 83        | 0.84%   |
| 0x0800820d | 81        | 0.82%   |
| 0x406c4    | 78        | 0.79%   |
| 0x906ed    | 72        | 0.73%   |
| 0x0a50000c | 71        | 0.72%   |
| 0x106e5    | 69        | 0.7%    |
| 0x706e5    | 61        | 0.62%   |
| 0x06001119 | 61        | 0.62%   |
| 0x506c9    | 60        | 0.61%   |
| 0x906a3    | 58        | 0.59%   |
| 0x806eb    | 57        | 0.58%   |
| 0x07030105 | 57        | 0.58%   |
| 0x06000852 | 57        | 0.58%   |
| 0x806d1    | 54        | 0.55%   |
| 0x706a8    | 54        | 0.55%   |
| 0x08701013 | 54        | 0.55%   |
| 0x05000119 | 54        | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1476      | 15.44%  |
| Haswell          | 930       | 9.73%   |
| SandyBridge      | 660       | 6.91%   |
| IvyBridge        | 654       | 6.84%   |
| Skylake          | 575       | 6.02%   |
| Penryn           | 565       | 5.91%   |
| Zen 2            | 396       | 4.14%   |
| Unknown          | 318       | 3.33%   |
| Core             | 315       | 3.3%    |
| TigerLake        | 306       | 3.2%    |
| Zen+             | 287       | 3%      |
| Silvermont       | 274       | 2.87%   |
| Westmere         | 261       | 2.73%   |
| Broadwell        | 249       | 2.61%   |
| Zen 3            | 245       | 2.56%   |
| CometLake        | 217       | 2.27%   |
| K10              | 208       | 2.18%   |
| Piledriver       | 160       | 1.67%   |
| IceLake          | 160       | 1.67%   |
| Zen              | 154       | 1.61%   |
| Alderlake Hybrid | 130       | 1.36%   |
| Goldmont plus    | 129       | 1.35%   |
| Nehalem          | 123       | 1.29%   |
| K8 Hammer        | 121       | 1.27%   |
| Bobcat           | 90        | 0.94%   |
| Excavator        | 88        | 0.92%   |
| Puma             | 81        | 0.85%   |
| Goldmont         | 81        | 0.85%   |
| Bonnell          | 77        | 0.81%   |
| NetBurst         | 60        | 0.63%   |
| Jaguar           | 49        | 0.51%   |
| K10 Llano        | 26        | 0.27%   |
| P6               | 25        | 0.26%   |
| Steamroller      | 19        | 0.2%    |
| K8 & K10 hybrid  | 15        | 0.16%   |
| Tremont          | 14        | 0.15%   |
| Bulldozer        | 13        | 0.14%   |
| K6               | 5         | 0.05%   |
| Sapphire Rapids  | 1         | 0.01%   |
| Gracemont        | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5396      | 47.55%  |
| Nvidia                                       | 3467      | 30.55%  |
| AMD                                          | 2372      | 20.9%   |
| Matrox Electronics Systems                   | 53        | 0.47%   |
| ASPEED Technology                            | 30        | 0.26%   |
| Silicon Integrated Systems [SiS]             | 14        | 0.12%   |
| VIA Technologies                             | 9         | 0.08%   |
| ATI Technologies                             | 3         | 0.03%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| S3 Graphics                                  | 1         | 0.01%   |
| Red Hat                                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 445       | 3.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 353       | 3.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 282       | 2.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 240       | 2.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 219       | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 215       | 1.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 198       | 1.7%    |
| Intel UHD Graphics 620                                                                   | 196       | 1.68%   |
| Intel HD Graphics 530                                                                    | 195       | 1.67%   |
| Intel HD Graphics 5500                                                                   | 187       | 1.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 180       | 1.54%   |
| AMD Renoir                                                                               | 179       | 1.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 178       | 1.53%   |
| Intel HD Graphics 620                                                                    | 172       | 1.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 171       | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 168       | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 157       | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 151       | 1.3%    |
| Intel HD Graphics 630                                                                    | 136       | 1.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 133       | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 119       | 1.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 110       | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 105       | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 105       | 0.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 102       | 0.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 101       | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 100       | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 97        | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 87        | 0.75%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 86        | 0.74%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 77        | 0.66%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 76        | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 70        | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 70        | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 70        | 0.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 69        | 0.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 68        | 0.58%   |
| Intel HD Graphics 500                                                                    | 64        | 0.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 62        | 0.53%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 60        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 3682      | 38.27%  |
| 1 x Nvidia           | 1952      | 20.29%  |
| 1 x AMD              | 1866      | 19.39%  |
| Intel + Nvidia       | 1359      | 14.12%  |
| Intel + AMD          | 234       | 2.43%   |
| 2 x AMD              | 137       | 1.42%   |
| AMD + Nvidia         | 137       | 1.42%   |
| Other                | 85        | 0.88%   |
| 1 x Matrox           | 48        | 0.5%    |
| 2 x Nvidia           | 29        | 0.3%    |
| 2 x Intel            | 26        | 0.27%   |
| 1 x ASPEED           | 25        | 0.26%   |
| 1 x SiS              | 14        | 0.15%   |
| 1 x VIA              | 9         | 0.09%   |
| Nvidia + Matrox      | 4         | 0.04%   |
| 3 x AMD              | 2         | 0.02%   |
| Nvidia + ASPEED      | 2         | 0.02%   |
| Intel + 2 x Nvidia   | 2         | 0.02%   |
| AMD + ASPEED         | 2         | 0.02%   |
| 3 x Nvidia           | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.01%   |
| 2 x AMD + 1 x ASPEED | 1         | 0.01%   |
| 1 x XGI              | 1         | 0.01%   |
| 1 x S3 Graphics      | 1         | 0.01%   |
| 1 x Red Hat          | 1         | 0.01%   |
| Intel + 2 x AMD      | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 7637      | 78.79%  |
| Proprietary | 1623      | 16.74%  |
| Unknown     | 433       | 4.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5213      | 53.17%  |
| 0.01-0.5   | 1257      | 12.82%  |
| 1.01-2.0   | 1191      | 12.15%  |
| 0.51-1.0   | 824       | 8.4%    |
| 3.01-4.0   | 601       | 6.13%   |
| 7.01-8.0   | 304       | 3.1%    |
| 5.01-6.0   | 213       | 2.17%   |
| 8.01-16.0  | 104       | 1.06%   |
| 2.01-3.0   | 76        | 0.78%   |
| 16.01-24.0 | 15        | 0.15%   |
| 4.01-5.0   | 5         | 0.05%   |
| 24.01-32.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1293      | 12.32%  |
| AU Optronics            | 1249      | 11.9%   |
| Chimei Innolux          | 833       | 7.94%   |
| LG Display              | 826       | 7.87%   |
| BOE                     | 764       | 7.28%   |
| Iiyama                  | 546       | 5.2%    |
| Dell                    | 541       | 5.15%   |
| Hewlett-Packard         | 424       | 4.04%   |
| Acer                    | 369       | 3.52%   |
| Goldstar                | 354       | 3.37%   |
| Ancor Communications    | 285       | 2.72%   |
| Philips                 | 274       | 2.61%   |
| AOC                     | 237       | 2.26%   |
| Sharp                   | 220       | 2.1%    |
| BenQ                    | 211       | 2.01%   |
| Lenovo                  | 169       | 1.61%   |
| Chi Mei Optoelectronics | 163       | 1.55%   |
| Apple                   | 154       | 1.47%   |
| ViewSonic               | 131       | 1.25%   |
| ASUSTek Computer        | 90        | 0.86%   |
| PANDA                   | 82        | 0.78%   |
| InfoVision              | 81        | 0.77%   |
| LG Philips              | 74        | 0.71%   |
| Sony                    | 58        | 0.55%   |
| Unknown                 | 53        | 0.51%   |
| HannStar                | 51        | 0.49%   |
| Packard Bell            | 38        | 0.36%   |
| Idek Iiyama             | 36        | 0.34%   |
| LG Electronics          | 35        | 0.33%   |
| Fujitsu Siemens         | 33        | 0.31%   |
| Vestel Elektronik       | 32        | 0.3%    |
| Toshiba                 | 29        | 0.28%   |
| NEC Computers           | 29        | 0.28%   |
| Eizo                    | 28        | 0.27%   |
| CSO                     | 26        | 0.25%   |
| MSI                     | 25        | 0.24%   |
| Denver                  | 24        | 0.23%   |
| Hitachi                 | 23        | 0.22%   |
| Panasonic               | 22        | 0.21%   |
| Medion                  | 22        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                     | 50        | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 48        | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 44        | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 37        | 0.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 35        | 0.32%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                             | 32        | 0.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 29        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 29        | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 29        | 0.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 28        | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 27        | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 27        | 0.25%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 26        | 0.24%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 26        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 26        | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 26        | 0.24%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 26        | 0.24%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 24        | 0.22%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 24        | 0.22%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 24        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 22        | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 22        | 0.2%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 21        | 0.19%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 21        | 0.19%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 21        | 0.19%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                         | 20        | 0.18%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                     | 19        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 19        | 0.18%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                    | 18        | 0.17%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 18        | 0.17%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 18        | 0.17%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                     | 18        | 0.17%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                      | 18        | 0.17%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 18        | 0.17%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 18        | 0.17%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 18        | 0.17%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 17        | 0.16%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 17        | 0.16%   |
| Iiyama PL2283H IVM562E 1920x1080 496x292mm 22.7-inch                      | 17        | 0.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 17        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4541      | 45.67%  |
| 1366x768 (WXGA)    | 1422      | 14.3%   |
| 1600x900 (HD+)     | 615       | 6.19%   |
| 3840x2160 (4K)     | 478       | 4.81%   |
| 2560x1440 (QHD)    | 442       | 4.45%   |
| 1680x1050 (WSXGA+) | 387       | 3.89%   |
| 1280x1024 (SXGA)   | 364       | 3.66%   |
| 1920x1200 (WUXGA)  | 312       | 3.14%   |
| 1440x900 (WXGA+)   | 303       | 3.05%   |
| 1280x800 (WXGA)    | 204       | 2.05%   |
| Unknown            | 120       | 1.21%   |
| 3440x1440          | 76        | 0.76%   |
| 1360x768           | 62        | 0.62%   |
| 2560x1080          | 59        | 0.59%   |
| 3840x1080          | 57        | 0.57%   |
| 2560x1600          | 54        | 0.54%   |
| 2880x1800          | 38        | 0.38%   |
| 1024x600           | 34        | 0.34%   |
| 1600x1200          | 33        | 0.33%   |
| 3840x2400          | 27        | 0.27%   |
| 2160x1440          | 27        | 0.27%   |
| 1024x768 (XGA)     | 26        | 0.26%   |
| 800x1280           | 23        | 0.23%   |
| 1920x540           | 21        | 0.21%   |
| 2288x1287          | 15        | 0.15%   |
| 3200x1800 (QHD+)   | 14        | 0.14%   |
| 3000x2000          | 11        | 0.11%   |
| 3840x1600          | 9         | 0.09%   |
| 4480x1440          | 8         | 0.08%   |
| 2736x1824          | 8         | 0.08%   |
| 1680x945           | 8         | 0.08%   |
| 3200x1080          | 7         | 0.07%   |
| 3600x1080          | 6         | 0.06%   |
| 5760x2160          | 5         | 0.05%   |
| 5760x1080          | 5         | 0.05%   |
| 3840x1200          | 5         | 0.05%   |
| 3072x1920          | 5         | 0.05%   |
| 2520x1680          | 5         | 0.05%   |
| 2048x1152          | 5         | 0.05%   |
| 1280x720 (HD)      | 5         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2290      | 21.89%  |
| 17      | 1014      | 9.69%   |
| 13      | 902       | 8.62%   |
| 24      | 880       | 8.41%   |
| 23      | 829       | 7.92%   |
| 27      | 779       | 7.45%   |
| 14      | 626       | 5.98%   |
| 21      | 611       | 5.84%   |
| Unknown | 464       | 4.44%   |
| 19      | 348       | 3.33%   |
| 22      | 250       | 2.39%   |
| 12      | 180       | 1.72%   |
| 20      | 162       | 1.55%   |
| 18      | 152       | 1.45%   |
| 31      | 131       | 1.25%   |
| 34      | 109       | 1.04%   |
| 16      | 85        | 0.81%   |
| 11      | 85        | 0.81%   |
| 84      | 68        | 0.65%   |
| 10      | 53        | 0.51%   |
| 72      | 49        | 0.47%   |
| 25      | 45        | 0.43%   |
| 32      | 44        | 0.42%   |
| 40      | 39        | 0.37%   |
| 54      | 30        | 0.29%   |
| 26      | 28        | 0.27%   |
| 33      | 23        | 0.22%   |
| 65      | 14        | 0.13%   |
| 46      | 14        | 0.13%   |
| 48      | 13        | 0.12%   |
| 7       | 13        | 0.12%   |
| 52      | 12        | 0.11%   |
| 39      | 12        | 0.11%   |
| 29      | 12        | 0.11%   |
| 142     | 11        | 0.11%   |
| 3       | 11        | 0.11%   |
| 49      | 8         | 0.08%   |
| 35      | 8         | 0.08%   |
| 42      | 7         | 0.07%   |
| 36      | 7         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3455      | 33.74%  |
| 501-600        | 2289      | 22.36%  |
| 401-500        | 1312      | 12.81%  |
| 351-400        | 1141      | 11.14%  |
| 201-300        | 824       | 8.05%   |
| Unknown        | 464       | 4.53%   |
| 601-700        | 228       | 2.23%   |
| 701-800        | 184       | 1.8%    |
| 1501-2000      | 119       | 1.16%   |
| 1001-1500      | 105       | 1.03%   |
| 801-900        | 72        | 0.7%    |
| 1-100          | 22        | 0.21%   |
| More than 2000 | 11        | 0.11%   |
| 901-1000       | 9         | 0.09%   |
| 101-200        | 4         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 6959      | 74.04%  |
| 16/10   | 1289      | 13.71%  |
| Unknown | 381       | 4.05%   |
| 5/4     | 346       | 3.68%   |
| 21/9    | 133       | 1.42%   |
| 3/2     | 107       | 1.14%   |
| 4/3     | 94        | 1%      |
| 6/5     | 29        | 0.31%   |
| 32/9    | 20        | 0.21%   |
| 0.67    | 12        | 0.13%   |
| 1.00    | 11        | 0.12%   |
| 3.20    | 4         | 0.04%   |
| 3.73    | 3         | 0.03%   |
| 11/10   | 2         | 0.02%   |
| 0.62    | 2         | 0.02%   |
| 0.56    | 2         | 0.02%   |
| 3.88    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.58    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2288      | 22.14%  |
| 201-250        | 2061      | 19.95%  |
| 81-90          | 1101      | 10.66%  |
| 301-350        | 809       | 7.83%   |
| 121-130        | 704       | 6.81%   |
| 151-200        | 699       | 6.76%   |
| Unknown        | 464       | 4.49%   |
| 71-80          | 437       | 4.23%   |
| 351-500        | 319       | 3.09%   |
| 251-300        | 310       | 3%      |
| 141-150        | 272       | 2.63%   |
| More than 1000 | 201       | 1.95%   |
| 61-70          | 155       | 1.5%    |
| 131-140        | 135       | 1.31%   |
| 501-1000       | 115       | 1.11%   |
| 51-60          | 85        | 0.82%   |
| 111-120        | 78        | 0.75%   |
| 41-50          | 54        | 0.52%   |
| 1-40           | 26        | 0.25%   |
| 91-100         | 20        | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 3622      | 36.06%  |
| 121-160       | 2529      | 25.18%  |
| 101-120       | 2518      | 25.07%  |
| 161-240       | 557       | 5.55%   |
| Unknown       | 464       | 4.62%   |
| More than 240 | 199       | 1.98%   |
| 1-50          | 154       | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 7525      | 77.09%  |
| 2     | 1565      | 16.03%  |
| 0     | 475       | 4.87%   |
| 3     | 185       | 1.9%    |
| 4     | 9         | 0.09%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5087      | 35.81%  |
| Intel                             | 4597      | 32.36%  |
| Qualcomm Atheros                  | 1650      | 11.62%  |
| Broadcom                          | 795       | 5.6%    |
| Marvell Technology Group          | 202       | 1.42%   |
| Broadcom Limited                  | 166       | 1.17%   |
| MediaTek                          | 160       | 1.13%   |
| Nvidia                            | 153       | 1.08%   |
| Ralink                            | 151       | 1.06%   |
| TP-Link                           | 108       | 0.76%   |
| ASIX Electronics                  | 87        | 0.61%   |
| NetGear                           | 85        | 0.6%    |
| Ralink Technology                 | 83        | 0.58%   |
| Samsung Electronics               | 66        | 0.46%   |
| Dell                              | 49        | 0.34%   |
| Xiaomi                            | 46        | 0.32%   |
| D-Link System                     | 42        | 0.3%    |
| DisplayLink                       | 34        | 0.24%   |
| D-Link                            | 33        | 0.23%   |
| Qualcomm                          | 30        | 0.21%   |
| Ericsson Business Mobile Networks | 29        | 0.2%    |
| Sierra Wireless                   | 28        | 0.2%    |
| Microsoft                         | 28        | 0.2%    |
| Aquantia                          | 28        | 0.2%    |
| Huawei Technologies               | 27        | 0.19%   |
| VIA Technologies                  | 25        | 0.18%   |
| JMicron Technology                | 24        | 0.17%   |
| Lenovo                            | 22        | 0.15%   |
| Belkin Components                 | 22        | 0.15%   |
| Qualcomm Atheros Communications   | 20        | 0.14%   |
| OPPO Electronics                  | 18        | 0.13%   |
| Google                            | 17        | 0.12%   |
| Guillemot                         | 16        | 0.11%   |
| ASUSTek Computer                  | 16        | 0.11%   |
| Silicon Integrated Systems [SiS]  | 15        | 0.11%   |
| Microchip Technology              | 14        | 0.1%    |
| Hewlett-Packard                   | 14        | 0.1%    |
| Attansic Technology               | 14        | 0.1%    |
| Edimax Technology                 | 10        | 0.07%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3471      | 20.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 500       | 3%      |
| Intel Wi-Fi 6 AX200                                               | 396       | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 365       | 2.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 312       | 1.87%   |
| Intel Wireless 8265 / 8275                                        | 251       | 1.51%   |
| Intel Wireless 7265                                               | 237       | 1.42%   |
| Intel Wi-Fi 6 AX201                                               | 235       | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 226       | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 200       | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 194       | 1.16%   |
| Intel Wireless 8260                                               | 192       | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 181       | 1.09%   |
| Intel Wireless 7260                                               | 178       | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 176       | 1.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 176       | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 164       | 0.98%   |
| Intel I211 Gigabit Network Connection                             | 150       | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 145       | 0.87%   |
| Intel Ethernet Connection I217-LM                                 | 144       | 0.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 141       | 0.85%   |
| Intel Ethernet Connection (2) I219-V                              | 140       | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 134       | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 134       | 0.8%    |
| Intel Wireless 3165                                               | 133       | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 125       | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 118       | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 110       | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 108       | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 99        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 98        | 0.59%   |
| Intel Wireless-AC 9260                                            | 97        | 0.58%   |
| Intel 82579V Gigabit Network Connection                           | 96        | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 87        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 87        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 86        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 85        | 0.51%   |
| Broadcom BCM43142 802.11b/g/n                                     | 85        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 83        | 0.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 80        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3400      | 46.1%   |
| Realtek Semiconductor                 | 1257      | 17.04%  |
| Qualcomm Atheros                      | 1256      | 17.03%  |
| Broadcom                              | 481       | 6.52%   |
| Ralink                                | 151       | 2.05%   |
| MediaTek                              | 145       | 1.97%   |
| TP-Link                               | 100       | 1.36%   |
| Broadcom Limited                      | 99        | 1.34%   |
| Ralink Technology                     | 83        | 1.13%   |
| NetGear                               | 81        | 1.1%    |
| D-Link                                | 31        | 0.42%   |
| Sierra Wireless                       | 28        | 0.38%   |
| Microsoft                             | 28        | 0.38%   |
| Dell                                  | 24        | 0.33%   |
| D-Link System                         | 23        | 0.31%   |
| Belkin Components                     | 22        | 0.3%    |
| Qualcomm Atheros Communications       | 20        | 0.27%   |
| Marvell Technology Group              | 19        | 0.26%   |
| Qualcomm                              | 17        | 0.23%   |
| Guillemot                             | 16        | 0.22%   |
| ASUSTek Computer                      | 16        | 0.22%   |
| Edimax Technology                     | 10        | 0.14%   |
| Fibocom                               | 8         | 0.11%   |
| Ericsson Business Mobile Networks     | 8         | 0.11%   |
| Hewlett-Packard                       | 6         | 0.08%   |
| TRENDnet                              | 5         | 0.07%   |
| Sagem                                 | 5         | 0.07%   |
| IMC Networks                          | 5         | 0.07%   |
| Gemtek                                | 4         | 0.05%   |
| ZyDAS                                 | 3         | 0.04%   |
| Tenda                                 | 3         | 0.04%   |
| Accton Technology                     | 3         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.04%   |
| Toshiba                               | 2         | 0.03%   |
| Linksys                               | 2         | 0.03%   |
| Fujitsu Siemens Computers             | 2         | 0.03%   |
| ZyXEL Communications                  | 1         | 0.01%   |
| Z-Com                                 | 1         | 0.01%   |
| Yoctopuce Sarl                        | 1         | 0.01%   |
| Wilocity                              | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 396       | 5.34%   |
| Intel Wireless 8265 / 8275                                              | 251       | 3.38%   |
| Intel Wireless 7265                                                     | 237       | 3.19%   |
| Intel Wi-Fi 6 AX201                                                     | 235       | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 226       | 3.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 200       | 2.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 194       | 2.61%   |
| Intel Wireless 8260                                                     | 192       | 2.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 181       | 2.44%   |
| Intel Wireless 7260                                                     | 178       | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 176       | 2.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 164       | 2.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 145       | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 141       | 1.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 134       | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 134       | 1.81%   |
| Intel Wireless 3165                                                     | 133       | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 125       | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 118       | 1.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 110       | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 108       | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 99        | 1.33%   |
| Intel Wireless-AC 9260                                                  | 97        | 1.31%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 87        | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                           | 85        | 1.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 73        | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 69        | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 67        | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 66        | 0.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 66        | 0.89%   |
| Intel WiFi Link 5100                                                    | 64        | 0.86%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 62        | 0.84%   |
| Intel Wireless 3160                                                     | 62        | 0.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 61        | 0.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 61        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 60        | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 58        | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 55        | 0.74%   |
| Intel Centrino Wireless-N 2230                                          | 55        | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 51        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 4616      | 51.95%  |
| Intel                            | 2339      | 26.32%  |
| Qualcomm Atheros                 | 578       | 6.5%    |
| Broadcom                         | 388       | 4.37%   |
| Marvell Technology Group         | 183       | 2.06%   |
| Nvidia                           | 153       | 1.72%   |
| ASIX Electronics                 | 87        | 0.98%   |
| Broadcom Limited                 | 70        | 0.79%   |
| Samsung Electronics              | 65        | 0.73%   |
| Xiaomi                           | 46        | 0.52%   |
| DisplayLink                      | 34        | 0.38%   |
| Aquantia                         | 28        | 0.32%   |
| JMicron Technology               | 24        | 0.27%   |
| VIA Technologies                 | 22        | 0.25%   |
| Lenovo                           | 22        | 0.25%   |
| Huawei Technologies              | 21        | 0.24%   |
| D-Link System                    | 19        | 0.21%   |
| OPPO Electronics                 | 18        | 0.2%    |
| Google                           | 17        | 0.19%   |
| Silicon Integrated Systems [SiS] | 14        | 0.16%   |
| MediaTek                         | 14        | 0.16%   |
| Attansic Technology              | 14        | 0.16%   |
| Qualcomm                         | 13        | 0.15%   |
| Microchip Technology             | 10        | 0.11%   |
| TP-Link                          | 8         | 0.09%   |
| ICS Advent                       | 8         | 0.09%   |
| OnePlus Technology (Shenzhen)    | 7         | 0.08%   |
| Motorola PCS                     | 6         | 0.07%   |
| Apple                            | 6         | 0.07%   |
| Mellanox Technologies            | 5         | 0.06%   |
| 3Com                             | 5         | 0.06%   |
| QLogic                           | 4         | 0.05%   |
| NetGear                          | 4         | 0.05%   |
| Linksys                          | 3         | 0.03%   |
| HTC (High Tech Computer)         | 3         | 0.03%   |
| Dell                             | 3         | 0.03%   |
| Hisense                          | 2         | 0.02%   |
| D-Link                           | 2         | 0.02%   |
| Cypress Semiconductor            | 2         | 0.02%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3471      | 38.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 500       | 5.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 365       | 4.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 312       | 3.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 176       | 1.93%   |
| Intel I211 Gigabit Network Connection                             | 150       | 1.65%   |
| Intel Ethernet Connection I217-LM                                 | 144       | 1.58%   |
| Intel Ethernet Connection (2) I219-V                              | 140       | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 98        | 1.08%   |
| Intel 82579V Gigabit Network Connection                           | 96        | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                             | 87        | 0.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 86        | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 85        | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 83        | 0.91%   |
| ASIX AX88179 Gigabit Ethernet                                     | 80        | 0.88%   |
| Intel Ethernet Connection I217-V                                  | 75        | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 70        | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 68        | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 67        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 66        | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                             | 66        | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 64        | 0.7%    |
| Nvidia MCP61 Ethernet                                             | 56        | 0.62%   |
| Intel Ethernet Connection (2) I218-V                              | 56        | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 53        | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 52        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 51        | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 49        | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 48        | 0.53%   |
| Intel I210 Gigabit Network Connection                             | 47        | 0.52%   |
| Intel 82574L Gigabit Network Connection                           | 47        | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 45        | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 43        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 43        | 0.47%   |
| Intel 82567LM Gigabit Network Connection                          | 43        | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 42        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 42        | 0.46%   |
| Intel Ethernet Connection I219-V                                  | 41        | 0.45%   |
| Intel Ethernet Connection (4) I219-V                              | 40        | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 40        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 8308      | 53.58%  |
| WiFi     | 7049      | 45.46%  |
| Modem    | 133       | 0.86%   |
| Unknown  | 16        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 5226      | 52.43%  |
| Ethernet | 4741      | 47.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 5161      | 53.85%  |
| 1     | 3999      | 41.73%  |
| 3     | 185       | 1.93%   |
| 0     | 182       | 1.9%    |
| 4     | 38        | 0.4%    |
| 5     | 7         | 0.07%   |
| 8     | 4         | 0.04%   |
| 6     | 4         | 0.04%   |
| 7     | 3         | 0.03%   |
| 9     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6021      | 61.13%  |
| Yes  | 3828      | 38.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2755      | 50.09%  |
| Realtek Semiconductor           | 455       | 8.27%   |
| IMC Networks                    | 366       | 6.65%   |
| Cambridge Silicon Radio         | 345       | 6.27%   |
| Qualcomm Atheros Communications | 300       | 5.45%   |
| Broadcom                        | 256       | 4.65%   |
| Apple                           | 168       | 3.05%   |
| Foxconn / Hon Hai               | 167       | 3.04%   |
| Lite-On Technology              | 155       | 2.82%   |
| ASUSTek Computer                | 105       | 1.91%   |
| Dell                            | 89        | 1.62%   |
| Realtek                         | 49        | 0.89%   |
| Hewlett-Packard                 | 44        | 0.8%    |
| Toshiba                         | 42        | 0.76%   |
| Ralink                          | 34        | 0.62%   |
| MediaTek                        | 24        | 0.44%   |
| Ralink Technology               | 22        | 0.4%    |
| TP-Link                         | 21        | 0.38%   |
| Belkin Components               | 20        | 0.36%   |
| Marvell Semiconductor           | 15        | 0.27%   |
| Foxconn International           | 14        | 0.25%   |
| Alps Electric                   | 14        | 0.25%   |
| Chicony Electronics             | 7         | 0.13%   |
| USI                             | 6         | 0.11%   |
| Integrated System Solution      | 6         | 0.11%   |
| HTC (High Tech Computer)        | 3         | 0.05%   |
| Fujitsu                         | 2         | 0.04%   |
| Conwise Technology              | 2         | 0.04%   |
| TRENDnet                        | 1         | 0.02%   |
| Syntek                          | 1         | 0.02%   |
| Roper                           | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| Kensington                      | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |
| D-Link System                   | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1005      | 18.27%  |
| Intel AX201 Bluetooth                               | 530       | 9.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 404       | 7.34%   |
| Intel AX200 Bluetooth                               | 370       | 6.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 345       | 6.27%   |
| Realtek Bluetooth Radio                             | 328       | 5.96%   |
| Intel Bluetooth Device                              | 176       | 3.2%    |
| IMC Networks Bluetooth Device                       | 133       | 2.42%   |
| IMC Networks Bluetooth Radio                        | 118       | 2.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 115       | 2.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 105       | 1.91%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 89        | 1.62%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 83        | 1.51%   |
| Apple Bluetooth Host Controller                     | 66        | 1.2%    |
| Intel AX210 Bluetooth                               | 64        | 1.16%   |
| Foxconn / Hon Hai Bluetooth Device                  | 64        | 1.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 56        | 1.02%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 55        | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 51        | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 49        | 0.89%   |
| Apple Bluetooth USB Host Controller                 | 44        | 0.8%    |
| IMC Networks Wireless_Device                        | 43        | 0.78%   |
| Realtek 802.11ac WLAN Adapter                       | 39        | 0.71%   |
| Lite-On Bluetooth Device                            | 39        | 0.71%   |
| Dell DW375 Bluetooth Module                         | 37        | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 35        | 0.64%   |
| Ralink RT3290 Bluetooth                             | 34        | 0.62%   |
| Lite-On Atheros AR3012 Bluetooth                    | 31        | 0.56%   |
| Foxconn / Hon Hai Wireless_Device                   | 31        | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 31        | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 30        | 0.55%   |
| Broadcom BCM2045B (BDC-2.1)                         | 30        | 0.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 27        | 0.49%   |
| Broadcom BCM43142A0 Bluetooth Device                | 26        | 0.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 26        | 0.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 26        | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                    | 25        | 0.45%   |
| Apple Bluetooth HCI                                 | 25        | 0.45%   |
| TP-Link UB5A Adapter                                | 21        | 0.38%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 21        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6998      | 52.17%  |
| AMD                              | 2529      | 18.85%  |
| Nvidia                           | 2469      | 18.4%   |
| C-Media Electronics              | 195       | 1.45%   |
| Logitech                         | 130       | 0.97%   |
| Creative Labs                    | 85        | 0.63%   |
| Realtek Semiconductor            | 76        | 0.57%   |
| GN Netcom                        | 71        | 0.53%   |
| Kingston Technology              | 52        | 0.39%   |
| Texas Instruments                | 47        | 0.35%   |
| JMTek                            | 46        | 0.34%   |
| Corsair                          | 45        | 0.34%   |
| Plantronics                      | 44        | 0.33%   |
| VIA Technologies                 | 40        | 0.3%    |
| Focusrite-Novation               | 39        | 0.29%   |
| SteelSeries ApS                  | 29        | 0.22%   |
| Generalplus Technology           | 28        | 0.21%   |
| Razer USA                        | 25        | 0.19%   |
| Sennheiser Communications        | 22        | 0.16%   |
| ASUSTek Computer                 | 22        | 0.16%   |
| Silicon Integrated Systems [SiS] | 21        | 0.16%   |
| Lenovo                           | 21        | 0.16%   |
| Hewlett-Packard                  | 19        | 0.14%   |
| Creative Technology              | 16        | 0.12%   |
| XMOS                             | 14        | 0.1%    |
| M-Audio                          | 14        | 0.1%    |
| Sony                             | 13        | 0.1%    |
| PreSonus Audio Electronics       | 9         | 0.07%   |
| BEHRINGER International          | 9         | 0.07%   |
| Yamaha                           | 8         | 0.06%   |
| RODE Microphones                 | 8         | 0.06%   |
| Ensoniq                          | 8         | 0.06%   |
| Turtle Beach                     | 7         | 0.05%   |
| Tenx Technology                  | 7         | 0.05%   |
| Micro Star International         | 7         | 0.05%   |
| GYROCOM C&C                      | 7         | 0.05%   |
| Dell                             | 7         | 0.05%   |
| Alesis                           | 6         | 0.04%   |
| AKAI Professional M.I.           | 6         | 0.04%   |
| ROCCAT                           | 5         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 670       | 4.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 649       | 4.13%   |
| Intel Sunrise Point-LP HD Audio                                            | 620       | 3.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 590       | 3.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 549       | 3.49%   |
| Intel Cannon Lake PCH cAVS                                                 | 417       | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 411       | 2.61%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 356       | 2.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 343       | 2.18%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 336       | 2.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 326       | 2.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 305       | 1.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 304       | 1.93%   |
| AMD Starship/Matisse HD Audio Controller                                   | 295       | 1.88%   |
| AMD FCH Azalia Controller                                                  | 287       | 1.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 259       | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 228       | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 225       | 1.43%   |
| Intel 8 Series HD Audio Controller                                         | 224       | 1.42%   |
| Intel Broadwell-U Audio Controller                                         | 221       | 1.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 220       | 1.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 217       | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 203       | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 199       | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 181       | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 170       | 1.08%   |
| Intel 200 Series PCH HD Audio                                              | 170       | 1.08%   |
| Intel Comet Lake PCH cAVS                                                  | 148       | 0.94%   |
| AMD Kabini HDMI/DP Audio                                                   | 148       | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 143       | 0.91%   |
| Nvidia High Definition Audio Controller                                    | 139       | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 139       | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 129       | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 124       | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 118       | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 118       | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 118       | 0.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 117       | 0.74%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 117       | 0.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 114       | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1625      | 22.36%  |
| SK hynix            | 1425      | 19.61%  |
| Kingston            | 723       | 9.95%   |
| Unknown             | 718       | 9.88%   |
| Micron Technology   | 710       | 9.77%   |
| Corsair             | 491       | 6.76%   |
| Crucial             | 484       | 6.66%   |
| G.Skill             | 344       | 4.73%   |
| Elpida              | 110       | 1.51%   |
| Ramaxel Technology  | 105       | 1.44%   |
| Nanya Technology    | 102       | 1.4%    |
| Unknown (ABCD)      | 69        | 0.95%   |
| A-DATA Technology   | 68        | 0.94%   |
| Unknown             | 37        | 0.51%   |
| Transcend           | 34        | 0.47%   |
| Patriot             | 19        | 0.26%   |
| Team                | 18        | 0.25%   |
| PNY                 | 16        | 0.22%   |
| Unifosa             | 14        | 0.19%   |
| Timetec             | 14        | 0.19%   |
| ASint Technology    | 10        | 0.14%   |
| Qimonda             | 8         | 0.11%   |
| Unknown (0x0C97)    | 7         | 0.1%    |
| Toshiba             | 6         | 0.08%   |
| Apacer              | 6         | 0.08%   |
| TEXTORM             | 5         | 0.07%   |
| Hewlett-Packard     | 5         | 0.07%   |
| Lexar               | 4         | 0.06%   |
| Innodisk            | 4         | 0.06%   |
| V-Color             | 3         | 0.04%   |
| Swissbit            | 3         | 0.04%   |
| Silicon Power       | 3         | 0.04%   |
| SHARETRONIC         | 3         | 0.04%   |
| OCZ                 | 3         | 0.04%   |
| Avant               | 3         | 0.04%   |
| Unknown (F301)      | 2         | 0.03%   |
| Unknown (07FB)      | 2         | 0.03%   |
| TakeMS              | 2         | 0.03%   |
| Ramos Technology    | 2         | 0.03%   |
| Neo Forza           | 2         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 68        | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 64        | 0.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 63        | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 58        | 0.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 57        | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 55        | 0.71%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 50        | 0.64%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 50        | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 49        | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 44        | 0.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 43        | 0.55%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 42        | 0.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 42        | 0.54%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 41        | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 40        | 0.52%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 40        | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 39        | 0.5%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 38        | 0.49%   |
| Unknown                                                          | 37        | 0.48%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 36        | 0.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 33        | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 32        | 0.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 32        | 0.41%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 31        | 0.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 29        | 0.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 27        | 0.35%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 26        | 0.34%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 25        | 0.32%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 24        | 0.31%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 24        | 0.31%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 24        | 0.31%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 23        | 0.3%    |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s             | 22        | 0.28%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 21        | 0.27%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.27%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 20        | 0.26%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 20        | 0.26%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 20        | 0.26%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 20        | 0.26%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 19        | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2760      | 43.62%  |
| DDR3    | 2269      | 35.86%  |
| DDR2    | 366       | 5.78%   |
| SDRAM   | 221       | 3.49%   |
| LPDDR4  | 212       | 3.35%   |
| Unknown | 180       | 2.84%   |
| LPDDR3  | 127       | 2.01%   |
| DDR5    | 65        | 1.03%   |
| DDR     | 60        | 0.95%   |
| LPDDR5  | 52        | 0.82%   |
| DRAM    | 13        | 0.21%   |
| RAM     | 1         | 0.02%   |
| EEPROM  | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3499      | 55.86%  |
| DIMM         | 2334      | 37.26%  |
| Row Of Chips | 375       | 5.99%   |
| Chip         | 23        | 0.37%   |
| Unknown      | 13        | 0.21%   |
| RIMM         | 11        | 0.18%   |
| FB-DIMM      | 9         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2497      | 36.25%  |
| 4096  | 2070      | 30.05%  |
| 2048  | 988       | 14.34%  |
| 16384 | 857       | 12.44%  |
| 1024  | 292       | 4.24%   |
| 32768 | 138       | 2%      |
| 512   | 40        | 0.58%   |
| 65536 | 3         | 0.04%   |
| 256   | 3         | 0.04%   |
| 1     | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1455      | 21.32%  |
| 3200    | 945       | 13.85%  |
| 2667    | 915       | 13.41%  |
| 2400    | 458       | 6.71%   |
| 1333    | 456       | 6.68%   |
| 2133    | 342       | 5.01%   |
| 1334    | 205       | 3%      |
| 667     | 186       | 2.73%   |
| 800     | 176       | 2.58%   |
| 1867    | 136       | 1.99%   |
| 3600    | 134       | 1.96%   |
| Unknown | 114       | 1.67%   |
| 1066    | 92        | 1.35%   |
| 4267    | 89        | 1.3%    |
| 1067    | 84        | 1.23%   |
| 3266    | 76        | 1.11%   |
| 4800    | 63        | 0.92%   |
| 1866    | 57        | 0.84%   |
| 1800    | 57        | 0.84%   |
| 2048    | 56        | 0.82%   |
| 6400    | 53        | 0.78%   |
| 3000    | 51        | 0.75%   |
| 2933    | 51        | 0.75%   |
| 2666    | 45        | 0.66%   |
| 4199    | 40        | 0.59%   |
| 3400    | 39        | 0.57%   |
| 533     | 38        | 0.56%   |
| 400     | 26        | 0.38%   |
| 975     | 25        | 0.37%   |
| 2800    | 23        | 0.34%   |
| 3733    | 22        | 0.32%   |
| 3800    | 18        | 0.26%   |
| 3533    | 18        | 0.26%   |
| 4266    | 17        | 0.25%   |
| 3466    | 17        | 0.25%   |
| 3666    | 15        | 0.22%   |
| 333     | 15        | 0.22%   |
| 2000    | 14        | 0.21%   |
| 1639    | 13        | 0.19%   |
| 3534    | 12        | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 118       | 43.07%  |
| Brother Industries    | 44        | 16.06%  |
| Canon                 | 43        | 15.69%  |
| Samsung Electronics   | 34        | 12.41%  |
| Seiko Epson           | 19        | 6.93%   |
| Ricoh                 | 3         | 1.09%   |
| Prolific Technology   | 3         | 1.09%   |
| STMicroelectronics    | 2         | 0.73%   |
| QinHeng Electronics   | 2         | 0.73%   |
| Lexmark International | 2         | 0.73%   |
| Xiaomi                | 1         | 0.36%   |
| Xerox                 | 1         | 0.36%   |
| Kyocera               | 1         | 0.36%   |
| Apple                 | 1         | 0.36%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2700 series                                    | 11        | 4%      |
| Samsung M2070 Series                                      | 9         | 3.27%   |
| HP ENVY 4520 series                                       | 9         | 3.27%   |
| HP DeskJet 3630 series                                    | 9         | 3.27%   |
| HP ENVY Photo 6200 series                                 | 6         | 2.18%   |
| HP DeskJet 2600 series                                    | 6         | 2.18%   |
| Canon PIXMA MG3600 Series                                 | 6         | 2.18%   |
| HP OfficeJet 3830 series                                  | 5         | 1.82%   |
| HP ENVY 5000 series                                       | 4         | 1.45%   |
| HP DeskJet Plus 4100 series                               | 4         | 1.45%   |
| HP DeskJet 3700 series                                    | 4         | 1.45%   |
| Brother HL-2030 Laser Printer                             | 4         | 1.45%   |
| Seiko Epson XP-240 Series                                 | 3         | 1.09%   |
| Samsung ML-1640 Series Laser Printer                      | 3         | 1.09%   |
| Samsung M2020 Series                                      | 3         | 1.09%   |
| Samsung CLX-3170 Series                                   | 3         | 1.09%   |
| Prolific PL2305 Parallel Port                             | 3         | 1.09%   |
| HP ENVY 5540 series                                       | 3         | 1.09%   |
| HP DeskJet F4200 series                                   | 3         | 1.09%   |
| HP Deskjet 3050A                                          | 3         | 1.09%   |
| Canon PIXMA MG2500 Series                                 | 3         | 1.09%   |
| Brother Printer                                           | 3         | 1.09%   |
| Brother MFC-L2710DW series                                | 3         | 1.09%   |
| Brother DCP-7055 scanner/printer                          | 3         | 1.09%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 0.73%   |
| Seiko Epson XP-255 257 Series                             | 2         | 0.73%   |
| Seiko Epson XP-2100 Series                                | 2         | 0.73%   |
| Seiko Epson WF-2830 Series                                | 2         | 0.73%   |
| Samsung SCX-3400 Series                                   | 2         | 0.73%   |
| Samsung SCX-3200 Series                                   | 2         | 0.73%   |
| Samsung ML-1660 Series                                    | 2         | 0.73%   |
| Samsung ML-1630 Series                                    | 2         | 0.73%   |
| Samsung CLX-3180 Series                                   | 2         | 0.73%   |
| QinHeng CH340S                                            | 2         | 0.73%   |
| HP OfficeJet Pro 69                                       | 2         | 0.73%   |
| HP LaserJet 1200                                          | 2         | 0.73%   |
| HP ENVY Pro 6400 series                                   | 2         | 0.73%   |
| HP ENVY 4500 series                                       | 2         | 0.73%   |
| HP DeskJet 5550                                           | 2         | 0.73%   |
| HP Deskjet 3070 B611 series                               | 2         | 0.73%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 59        | 62.11%  |
| Seiko Epson     | 24        | 25.26%  |
| Hewlett-Packard | 8         | 8.42%   |
| AGFA-Gevaert NV | 4         | 4.21%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                       | 10        | 10.53%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 9         | 9.47%   |
| Canon CanoScan N1240U/LiDE 30                                 | 9         | 9.47%   |
| Canon CanoScan LIDE 25                                        | 7         | 7.37%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 4         | 4.21%   |
| Canon CanoScan LiDE 60                                        | 3         | 3.16%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                        | 3         | 3.16%   |
| Canon CanoScan LiDE 200                                       | 3         | 3.16%   |
| AGFA-Gevaert NV SnapScan e20                                  | 3         | 3.16%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 2         | 2.11%   |
| Seiko Epson GT-F700 [Perfection V350]                         | 2         | 2.11%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 2         | 2.11%   |
| Seiko Epson GT-9800F [Perfection 3200]                        | 2         | 2.11%   |
| Seiko Epson GT-6600U [Perfection 610]                         | 2         | 2.11%   |
| HP ScanJet 3570c                                              | 2         | 2.11%   |
| Canon CanoScan N650U/N656U                                    | 2         | 2.11%   |
| Canon CanoScan LiDE 220                                       | 2         | 2.11%   |
| Canon CanoScan LiDE 210                                       | 2         | 2.11%   |
| Canon CanoScan LiDE 120                                       | 2         | 2.11%   |
| Canon CanoScan 4200F                                          | 2         | 2.11%   |
| Seiko Epson Scanner                                           | 1         | 1.05%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]              | 1         | 1.05%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                   | 1         | 1.05%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]       | 1         | 1.05%   |
| Seiko Epson GT-F600 [Perfection 4180]                         | 1         | 1.05%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 1.05%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 1.05%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]            | 1         | 1.05%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]   | 1         | 1.05%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 1.05%   |
| HP ScanJet G4010                                              | 1         | 1.05%   |
| HP ScanJet 5200c                                              | 1         | 1.05%   |
| HP ScanJet 4570c                                              | 1         | 1.05%   |
| HP ScanJet 3500c                                              | 1         | 1.05%   |
| HP ScanJet 2300c                                              | 1         | 1.05%   |
| HP PSC 1200                                                   | 1         | 1.05%   |
| Canon CanoScan LiDE 70                                        | 1         | 1.05%   |
| Canon CanoScan LiDE 100                                       | 1         | 1.05%   |
| Canon CanoScan 9000F Mark II                                  | 1         | 1.05%   |
| Canon CanoScan 8800F                                          | 1         | 1.05%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1243      | 21.86%  |
| IMC Networks                           | 571       | 10.04%  |
| Microdia                               | 524       | 9.22%   |
| Realtek Semiconductor                  | 479       | 8.43%   |
| Logitech                               | 378       | 6.65%   |
| Bison Electronics                      | 327       | 5.75%   |
| Sunplus Innovation Technology          | 325       | 5.72%   |
| Suyin                                  | 206       | 3.62%   |
| Quanta                                 | 197       | 3.47%   |
| Cheng Uei Precision Industry (Foxlink) | 196       | 3.45%   |
| Apple                                  | 155       | 2.73%   |
| Lite-On Technology                     | 126       | 2.22%   |
| Syntek                                 | 104       | 1.83%   |
| Acer                                   | 87        | 1.53%   |
| Alcor Micro                            | 68        | 1.2%    |
| Samsung Electronics                    | 65        | 1.14%   |
| Luxvisions Innotech Limited            | 65        | 1.14%   |
| Microsoft                              | 57        | 1%      |
| Ricoh                                  | 49        | 0.86%   |
| Silicon Motion                         | 47        | 0.83%   |
| Sonix Technology                       | 36        | 0.63%   |
| Guillemot                              | 25        | 0.44%   |
| Z-Star Microelectronics                | 23        | 0.4%    |
| Lenovo                                 | 22        | 0.39%   |
| Primax Electronics                     | 20        | 0.35%   |
| ARC International                      | 17        | 0.3%    |
| Importek                               | 16        | 0.28%   |
| Generalplus Technology                 | 15        | 0.26%   |
| GEMBIRD                                | 15        | 0.26%   |
| Creative Technology                    | 15        | 0.26%   |
| DigiTech                               | 14        | 0.25%   |
| ALi                                    | 13        | 0.23%   |
| Hewlett-Packard                        | 10        | 0.18%   |
| Y Media                                | 9         | 0.16%   |
| icSpring                               | 9         | 0.16%   |
| SunplusIT                              | 8         | 0.14%   |
| KYE Systems (Mouse Systems)            | 8         | 0.14%   |
| 2M UVC CAMERA                          | 8         | 0.14%   |
| Cubeternet                             | 7         | 0.12%   |
| WaveRider Communications               | 6         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 255       | 4.46%   |
| Realtek Integrated_Webcam_HD             | 211       | 3.69%   |
| Chicony Integrated Camera                | 194       | 3.4%    |
| IMC Networks USB2.0 HD UVC WebCam        | 139       | 2.43%   |
| IMC Networks Integrated Camera           | 102       | 1.79%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 97        | 1.7%    |
| Chicony HD WebCam                        | 95        | 1.66%   |
| Logitech Webcam C270                     | 86        | 1.51%   |
| Sunplus Integrated_Webcam_HD             | 81        | 1.42%   |
| Bison Integrated Camera                  | 81        | 1.42%   |
| Samsung Galaxy series, misc. (MTP mode)  | 65        | 1.14%   |
| Bison HD Webcam                          | 61        | 1.07%   |
| Realtek USB Camera                       | 59        | 1.03%   |
| Chicony USB2.0 Camera                    | 59        | 1.03%   |
| Chicony HP HD Camera                     | 58        | 1.02%   |
| Logitech HD Pro Webcam C920              | 55        | 0.96%   |
| Chicony USB2.0 VGA UVC WebCam            | 54        | 0.95%   |
| Syntek Integrated Camera                 | 49        | 0.86%   |
| Microdia Integrated Webcam               | 49        | 0.86%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 49        | 0.86%   |
| Apple Built-in iSight                    | 49        | 0.86%   |
| Chicony USB2.0 HD UVC WebCam             | 46        | 0.81%   |
| Chicony TOSHIBA Web Camera - HD          | 45        | 0.79%   |
| Chicony HP Truevision HD                 | 45        | 0.79%   |
| Sunplus Asus Webcam                      | 44        | 0.77%   |
| Chicony HP TrueVision HD Camera          | 43        | 0.75%   |
| Bison BisonCam,NB Pro                    | 41        | 0.72%   |
| Lite-On Integrated Camera                | 40        | 0.7%    |
| Chicony USB 2.0 Camera                   | 40        | 0.7%    |
| Realtek USB2.0 HD UVC WebCam             | 36        | 0.63%   |
| Quanta HP HD Camera                      | 36        | 0.63%   |
| Chicony HP HD Webcam                     | 36        | 0.63%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 34        | 0.6%    |
| Sunplus HD WebCam                        | 34        | 0.6%    |
| Bison BisonCam, NB Pro                   | 32        | 0.56%   |
| Logitech HD Webcam C525                  | 31        | 0.54%   |
| Chicony VGA Webcam                       | 30        | 0.53%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 29        | 0.51%   |
| Quanta HD User Facing                    | 28        | 0.49%   |
| IMC Networks UVC VGA Webcam              | 28        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 321       | 35.04%  |
| Synaptics                          | 213       | 23.25%  |
| Shenzhen Goodix Technology         | 171       | 18.67%  |
| AuthenTec                          | 67        | 7.31%   |
| Elan Microelectronics              | 49        | 5.35%   |
| LighTuning Technology              | 46        | 5.02%   |
| Upek                               | 36        | 3.93%   |
| STMicroelectronics                 | 11        | 1.2%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.11%   |
| Focal-systems.Corp                 | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 89        | 9.72%   |
| Shenzhen Goodix  Fingerprint Device                                        | 87        | 9.5%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 72        | 7.86%   |
| Shenzhen Goodix FingerPrint                                                | 44        | 4.8%    |
| Shenzhen Goodix Fingerprint Reader                                         | 40        | 4.37%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 40        | 4.37%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 33        | 3.6%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 31        | 3.38%   |
| Elan ELAN:Fingerprint                                                      | 27        | 2.95%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 26        | 2.84%   |
| Validity Sensors VFS491                                                    | 25        | 2.73%   |
| AuthenTec AES2810                                                          | 24        | 2.62%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 2.18%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 19        | 2.07%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 1.97%   |
| Synaptics UWP WBDI                                                         | 18        | 1.97%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 17        | 1.86%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 16        | 1.75%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 16        | 1.75%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 1.75%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 16        | 1.75%   |
| Validity Sensors Synaptics WBDI                                            | 15        | 1.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 15        | 1.64%   |
| AuthenTec Fingerprint Sensor                                               | 15        | 1.64%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 1.53%   |
| Synaptics Fingerprint reader [HP G6]                                       | 14        | 1.53%   |
| AuthenTec AES1600                                                          | 14        | 1.53%   |
| Synaptics  WBDI                                                            | 12        | 1.31%   |
| Elan ELAN:ARM-M4                                                           | 12        | 1.31%   |
| Validity Sensors VFS Fingerprint sensor                                    | 11        | 1.2%    |
| STMicroelectronics Fingerprint Reader                                      | 11        | 1.2%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 1.09%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 10        | 1.09%   |
| Unknown                                                                    | 8         | 0.87%   |
| Elan WBF Fingerprint Sensor                                                | 7         | 0.76%   |
| Synaptics WBDI                                                             | 6         | 0.66%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.55%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.55%   |
| Synaptics WBDI Device                                                      | 5         | 0.55%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 4         | 0.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 261       | 55.06%  |
| Alcor Micro               | 95        | 20.04%  |
| O2 Micro                  | 39        | 8.23%   |
| Upek                      | 17        | 3.59%   |
| Lenovo                    | 17        | 3.59%   |
| Hewlett-Packard           | 9         | 1.9%    |
| Gemalto (was Gemplus)     | 9         | 1.9%    |
| Aladdin Knowledge Systems | 5         | 1.05%   |
| Yubico.com                | 4         | 0.84%   |
| Clay Logic                | 3         | 0.63%   |
| Chicony Electronics       | 3         | 0.63%   |
| SCM Microsystems          | 2         | 0.42%   |
| Realtek Semiconductor     | 2         | 0.42%   |
| Feitian Technologies      | 2         | 0.42%   |
| ST-Ericsson               | 1         | 0.21%   |
| SpringCard                | 1         | 0.21%   |
| OmniKey                   | 1         | 0.21%   |
| Jing-Mold Enterprise      | 1         | 0.21%   |
| Cherry                    | 1         | 0.21%   |
| Advanced Card Systems     | 1         | 0.21%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 94        | 19.83%  |
| Broadcom 58200                                                               | 84        | 17.72%  |
| Broadcom BCM5880 Secure Applications Processor                               | 83        | 17.51%  |
| Broadcom 5880                                                                | 56        | 11.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 37        | 7.81%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 35        | 7.38%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 3.59%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 3.59%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 9         | 1.9%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 1.27%   |
| Aladdin Knowledge Systems Token JC                                           | 5         | 1.05%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 4         | 0.84%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 0.84%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 0.63%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.42%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.42%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.42%   |
| ST-Ericsson Chipcard Reader                                                  | 1         | 0.21%   |
| SpringCard Two                                                               | 1         | 0.21%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.21%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.21%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.21%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 0.21%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.21%   |
| Feitian Technologies U2F CCID KB                                             | 1         | 0.21%   |
| Feitian Technologies FT SCR310                                               | 1         | 0.21%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.21%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                   | 1         | 0.21%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.21%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.21%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.21%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 6928      | 70.76%  |
| 1     | 2273      | 23.22%  |
| 2     | 465       | 4.75%   |
| 3     | 88        | 0.9%    |
| 4     | 22        | 0.22%   |
| 5     | 7         | 0.07%   |
| 6     | 3         | 0.03%   |
| 8     | 2         | 0.02%   |
| 7     | 2         | 0.02%   |
| 9     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 906       | 26.28%  |
| Graphics card            | 892       | 25.87%  |
| Chipcard                 | 429       | 12.44%  |
| Net/wireless             | 356       | 10.32%  |
| Multimedia controller    | 170       | 4.93%   |
| Communication controller | 131       | 3.8%    |
| Camera                   | 121       | 3.51%   |
| Bluetooth                | 89        | 2.58%   |
| Unassigned class         | 81        | 2.35%   |
| Storage                  | 61        | 1.77%   |
| Sound                    | 54        | 1.57%   |
| Card reader              | 46        | 1.33%   |
| Net/ethernet             | 35        | 1.02%   |
| Modem                    | 21        | 0.61%   |
| Network                  | 19        | 0.55%   |
| Storage/raid             | 7         | 0.2%    |
| Firewire controller      | 7         | 0.2%    |
| Storage/ide              | 5         | 0.15%   |
| Dvb card                 | 5         | 0.15%   |
| Flash memory             | 4         | 0.12%   |
| Wireless                 | 3         | 0.09%   |
| Unclassified device      | 2         | 0.06%   |
| Tv card                  | 2         | 0.06%   |
| Storage/nvme             | 1         | 0.03%   |
| Storage/ata              | 1         | 0.03%   |

