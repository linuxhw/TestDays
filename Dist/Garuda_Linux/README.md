Garuda Linux - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Garuda_Linux/Desktop/README.md) and [notebooks](/Dist/Garuda_Linux/Notebook/README.md).

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

Total: 366

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [66c6e57421](https://linux-hardware.org/?probe=66c6e57421) | Apr 23, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3ce5eb80eb](https://linux-hardware.org/?probe=3ce5eb80eb) | Apr 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b82721163b](https://linux-hardware.org/?probe=b82721163b) | Apr 22, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [51eac6f63f](https://linux-hardware.org/?probe=51eac6f63f) | Apr 21, 2022 |
| Dell          | Latitude E7250              | Notebook    | [fa677cf244](https://linux-hardware.org/?probe=fa677cf244) | Apr 21, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [c6d6bddd17](https://linux-hardware.org/?probe=c6d6bddd17) | Apr 18, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [6db9a3dea0](https://linux-hardware.org/?probe=6db9a3dea0) | Apr 18, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7204116754](https://linux-hardware.org/?probe=7204116754) | Apr 14, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [fcfc2b41a7](https://linux-hardware.org/?probe=fcfc2b41a7) | Apr 10, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [ba87ebf29f](https://linux-hardware.org/?probe=ba87ebf29f) | Apr 08, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2803fbf2ab](https://linux-hardware.org/?probe=2803fbf2ab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [658e58fcab](https://linux-hardware.org/?probe=658e58fcab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [67966ea318](https://linux-hardware.org/?probe=67966ea318) | Apr 04, 2022 |
| HP            | 8433 11                     | Desktop     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [c092681184](https://linux-hardware.org/?probe=c092681184) | Apr 03, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [dc11ff8996](https://linux-hardware.org/?probe=dc11ff8996) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [4a0436ece5](https://linux-hardware.org/?probe=4a0436ece5) | Apr 01, 2022 |
| Dell          | Latitude E7250              | Notebook    | [d31f6b8a4a](https://linux-hardware.org/?probe=d31f6b8a4a) | Apr 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a33f627737](https://linux-hardware.org/?probe=a33f627737) | Mar 30, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| MSI           | GS76 Stealth 11UG           | Notebook    | [d05ccc7f12](https://linux-hardware.org/?probe=d05ccc7f12) | Mar 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [066b026c69](https://linux-hardware.org/?probe=066b026c69) | Mar 28, 2022 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [df2ffaa70a](https://linux-hardware.org/?probe=df2ffaa70a) | Mar 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [21e6b2c7c3](https://linux-hardware.org/?probe=21e6b2c7c3) | Mar 22, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [d4a63f4b81](https://linux-hardware.org/?probe=d4a63f4b81) | Mar 20, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| Toshiba       | Satellite E45DW-C           | Notebook    | [2b815d9219](https://linux-hardware.org/?probe=2b815d9219) | Mar 12, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [370e992e57](https://linux-hardware.org/?probe=370e992e57) | Mar 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [94786f0b30](https://linux-hardware.org/?probe=94786f0b30) | Mar 02, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [4935a5660c](https://linux-hardware.org/?probe=4935a5660c) | Mar 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b4c8253286](https://linux-hardware.org/?probe=b4c8253286) | Feb 23, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [acb2659ec1](https://linux-hardware.org/?probe=acb2659ec1) | Feb 19, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a88902a823](https://linux-hardware.org/?probe=a88902a823) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [499191c566](https://linux-hardware.org/?probe=499191c566) | Feb 18, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [df78a2fff6](https://linux-hardware.org/?probe=df78a2fff6) | Feb 14, 2022 |
| Lenovo        | ThinkPad T530 24296KG       | Notebook    | [9940aacd34](https://linux-hardware.org/?probe=9940aacd34) | Feb 13, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [e3fd65aa29](https://linux-hardware.org/?probe=e3fd65aa29) | Feb 13, 2022 |
| HP            | 8767 A                      | Desktop     | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP            | 8767 A                      | Desktop     | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [e2b8b640f8](https://linux-hardware.org/?probe=e2b8b640f8) | Feb 11, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [1b98c3db08](https://linux-hardware.org/?probe=1b98c3db08) | Feb 11, 2022 |
| HP            | 86F3 00100                  | All in one  | [6dc9aa1e88](https://linux-hardware.org/?probe=6dc9aa1e88) | Feb 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3c46e807da](https://linux-hardware.org/?probe=3c46e807da) | Feb 09, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [9cb5307823](https://linux-hardware.org/?probe=9cb5307823) | Feb 06, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [e4beeac4a1](https://linux-hardware.org/?probe=e4beeac4a1) | Feb 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [7c19747b0a](https://linux-hardware.org/?probe=7c19747b0a) | Feb 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [2e3070dc30](https://linux-hardware.org/?probe=2e3070dc30) | Feb 04, 2022 |
| Dell          | Latitude 5480               | Notebook    | [c96d03d27f](https://linux-hardware.org/?probe=c96d03d27f) | Feb 03, 2022 |
| Lenovo        | ThinkPad P1 20MDS00P00      | Notebook    | [4ff53df600](https://linux-hardware.org/?probe=4ff53df600) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [387da722fe](https://linux-hardware.org/?probe=387da722fe) | Feb 02, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [5943c38ac0](https://linux-hardware.org/?probe=5943c38ac0) | Feb 01, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | Desktop     | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [0497eabcf7](https://linux-hardware.org/?probe=0497eabcf7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [e7efa96c01](https://linux-hardware.org/?probe=e7efa96c01) | Jan 28, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [aa0e21b159](https://linux-hardware.org/?probe=aa0e21b159) | Jan 27, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b78e96aff8](https://linux-hardware.org/?probe=b78e96aff8) | Jan 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [af6171a374](https://linux-hardware.org/?probe=af6171a374) | Jan 22, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [2227a23892](https://linux-hardware.org/?probe=2227a23892) | Jan 20, 2022 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [6935c7fc83](https://linux-hardware.org/?probe=6935c7fc83) | Jan 17, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [6261484b31](https://linux-hardware.org/?probe=6261484b31) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus X CODE          | Desktop     | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [10f53d4021](https://linux-hardware.org/?probe=10f53d4021) | Jan 09, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [a338d9f2d1](https://linux-hardware.org/?probe=a338d9f2d1) | Jan 08, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8a1167daea](https://linux-hardware.org/?probe=8a1167daea) | Jan 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [b75e231fb3](https://linux-hardware.org/?probe=b75e231fb3) | Jan 08, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [1a4570a458](https://linux-hardware.org/?probe=1a4570a458) | Jan 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [34d2cd6d9c](https://linux-hardware.org/?probe=34d2cd6d9c) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [9ad04f3022](https://linux-hardware.org/?probe=9ad04f3022) | Jan 07, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [c4db605668](https://linux-hardware.org/?probe=c4db605668) | Jan 06, 2022 |
| Dell          | Precision M4500             | Notebook    | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| HP            | Pavilion 14                 | Notebook    | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [37dc48f3f3](https://linux-hardware.org/?probe=37dc48f3f3) | Jan 02, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [f506cf2d37](https://linux-hardware.org/?probe=f506cf2d37) | Jan 02, 2022 |
| HP            | Pavilion Laptop 15z-eh10... | Notebook    | [29b9cb755b](https://linux-hardware.org/?probe=29b9cb755b) | Dec 25, 2021 |
| Dell          | G15 5515                    | Notebook    | [7e8108b3c2](https://linux-hardware.org/?probe=7e8108b3c2) | Dec 24, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [8d397e7af8](https://linux-hardware.org/?probe=8d397e7af8) | Dec 19, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [c7147f0bf8](https://linux-hardware.org/?probe=c7147f0bf8) | Dec 16, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [f8a99e7645](https://linux-hardware.org/?probe=f8a99e7645) | Dec 16, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9e73346fb8](https://linux-hardware.org/?probe=9e73346fb8) | Dec 15, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [c3144c3e22](https://linux-hardware.org/?probe=c3144c3e22) | Dec 13, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [196b460373](https://linux-hardware.org/?probe=196b460373) | Dec 13, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [df628cbd13](https://linux-hardware.org/?probe=df628cbd13) | Dec 12, 2021 |
| ASRock        | H77M-ITX                    | Desktop     | [5e98a2fce2](https://linux-hardware.org/?probe=5e98a2fce2) | Dec 11, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [e4fb1e4fe4](https://linux-hardware.org/?probe=e4fb1e4fe4) | Dec 09, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [731c890641](https://linux-hardware.org/?probe=731c890641) | Dec 08, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [a49a5a129c](https://linux-hardware.org/?probe=a49a5a129c) | Dec 07, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f499f9a375](https://linux-hardware.org/?probe=f499f9a375) | Dec 06, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [f0df07c0e4](https://linux-hardware.org/?probe=f0df07c0e4) | Dec 06, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e6b9de389b](https://linux-hardware.org/?probe=e6b9de389b) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8ce02488c4](https://linux-hardware.org/?probe=8ce02488c4) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b68e789e42](https://linux-hardware.org/?probe=b68e789e42) | Dec 06, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [c743459a71](https://linux-hardware.org/?probe=c743459a71) | Dec 04, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [f031548aac](https://linux-hardware.org/?probe=f031548aac) | Dec 01, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [48f73af82d](https://linux-hardware.org/?probe=48f73af82d) | Nov 30, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [6ee6a2bc49](https://linux-hardware.org/?probe=6ee6a2bc49) | Nov 30, 2021 |
| Acer          | Nitro AN715-52              | Notebook    | [2b74aabc3a](https://linux-hardware.org/?probe=2b74aabc3a) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b5b437249c](https://linux-hardware.org/?probe=b5b437249c) | Nov 29, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [0b1d816eff](https://linux-hardware.org/?probe=0b1d816eff) | Nov 28, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [dd3bc71908](https://linux-hardware.org/?probe=dd3bc71908) | Nov 26, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [fac556ebbe](https://linux-hardware.org/?probe=fac556ebbe) | Nov 24, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [63f386f998](https://linux-hardware.org/?probe=63f386f998) | Nov 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [bbb0689dea](https://linux-hardware.org/?probe=bbb0689dea) | Nov 21, 2021 |
| Dell          | Latitude E5570              | Notebook    | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [1ea5d23a86](https://linux-hardware.org/?probe=1ea5d23a86) | Nov 17, 2021 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [2713c3bae1](https://linux-hardware.org/?probe=2713c3bae1) | Nov 16, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [2c8fef35c1](https://linux-hardware.org/?probe=2c8fef35c1) | Nov 14, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f455ee4572](https://linux-hardware.org/?probe=f455ee4572) | Nov 14, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [0f3490892c](https://linux-hardware.org/?probe=0f3490892c) | Nov 14, 2021 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [d74b03de25](https://linux-hardware.org/?probe=d74b03de25) | Nov 13, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [6584d17e10](https://linux-hardware.org/?probe=6584d17e10) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ed9cd44b17](https://linux-hardware.org/?probe=ed9cd44b17) | Nov 08, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | Notebook    | [976bcf4121](https://linux-hardware.org/?probe=976bcf4121) | Nov 04, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [5ae2157abe](https://linux-hardware.org/?probe=5ae2157abe) | Nov 04, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [86f08832c0](https://linux-hardware.org/?probe=86f08832c0) | Oct 31, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [e153488f12](https://linux-hardware.org/?probe=e153488f12) | Oct 28, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| Panasonic     | CF-191HYAX1M                | Notebook    | [1aed5aedc2](https://linux-hardware.org/?probe=1aed5aedc2) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [dde814d7ca](https://linux-hardware.org/?probe=dde814d7ca) | Oct 25, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [5154b1932f](https://linux-hardware.org/?probe=5154b1932f) | Oct 24, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [ec046ac486](https://linux-hardware.org/?probe=ec046ac486) | Oct 24, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [9b9f21a8eb](https://linux-hardware.org/?probe=9b9f21a8eb) | Oct 19, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [d8167a915b](https://linux-hardware.org/?probe=d8167a915b) | Oct 17, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [ff6b763448](https://linux-hardware.org/?probe=ff6b763448) | Oct 16, 2021 |
| Lenovo        | ThinkPad T510 4384WB4       | Notebook    | [4a54d7fd48](https://linux-hardware.org/?probe=4a54d7fd48) | Oct 16, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [64fd7ae16c](https://linux-hardware.org/?probe=64fd7ae16c) | Oct 11, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [5070a2bdc7](https://linux-hardware.org/?probe=5070a2bdc7) | Oct 10, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [841a71eac1](https://linux-hardware.org/?probe=841a71eac1) | Oct 04, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [1963eb2e26](https://linux-hardware.org/?probe=1963eb2e26) | Sep 28, 2021 |
| Notebook      | P7xxDM2                     | Notebook    | [284ab5f28e](https://linux-hardware.org/?probe=284ab5f28e) | Sep 28, 2021 |
| Acer          | Aspire V3-572P              | Notebook    | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [10b47851d2](https://linux-hardware.org/?probe=10b47851d2) | Sep 25, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [2e3e323c0d](https://linux-hardware.org/?probe=2e3e323c0d) | Sep 21, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [91a1652ef2](https://linux-hardware.org/?probe=91a1652ef2) | Sep 18, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0b9ee7a59d](https://linux-hardware.org/?probe=0b9ee7a59d) | Sep 12, 2021 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [646d26abf7](https://linux-hardware.org/?probe=646d26abf7) | Sep 08, 2021 |
| Razer         | Blade                       | Notebook    | [1ce95784c0](https://linux-hardware.org/?probe=1ce95784c0) | Sep 05, 2021 |
| Razer         | Blade                       | Notebook    | [58a2a48dc4](https://linux-hardware.org/?probe=58a2a48dc4) | Sep 05, 2021 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [e4593929ff](https://linux-hardware.org/?probe=e4593929ff) | Sep 05, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [85fa26ea9e](https://linux-hardware.org/?probe=85fa26ea9e) | Aug 31, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| Alienware     | 0TYR0X A00                  | Desktop     | [5ea23ebfb2](https://linux-hardware.org/?probe=5ea23ebfb2) | Aug 19, 2021 |
| ASRock        | X399 Professional Gaming    | Desktop     | [bb53a385c3](https://linux-hardware.org/?probe=bb53a385c3) | Aug 19, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [c18bca5109](https://linux-hardware.org/?probe=c18bca5109) | Aug 16, 2021 |
| Google        | Kindred                     | Notebook    | [ac298188ae](https://linux-hardware.org/?probe=ac298188ae) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [4ec8d56e38](https://linux-hardware.org/?probe=4ec8d56e38) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [c8892394cf](https://linux-hardware.org/?probe=c8892394cf) | Aug 13, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| Medion        | H110H4-EM2                  | Desktop     | [f4e01958e5](https://linux-hardware.org/?probe=f4e01958e5) | Aug 10, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [a919fef17f](https://linux-hardware.org/?probe=a919fef17f) | Aug 07, 2021 |
| MSI           | Z97 MPOWER                  | Desktop     | [dee7d3af4a](https://linux-hardware.org/?probe=dee7d3af4a) | Aug 06, 2021 |
| MSI           | Z97 MPOWER                  | Desktop     | [f30e5a3a86](https://linux-hardware.org/?probe=f30e5a3a86) | Aug 06, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c505820537](https://linux-hardware.org/?probe=c505820537) | Aug 04, 2021 |
| Acer          | IPMBW-BR                    | All in one  | [a2ef77ad47](https://linux-hardware.org/?probe=a2ef77ad47) | Aug 03, 2021 |
| ASUSTek       | G750JZ                      | Notebook    | [f35df8640b](https://linux-hardware.org/?probe=f35df8640b) | Aug 02, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d25176b845](https://linux-hardware.org/?probe=d25176b845) | Jul 30, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [0340b4c57f](https://linux-hardware.org/?probe=0340b4c57f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [e436ae3019](https://linux-hardware.org/?probe=e436ae3019) | Jul 23, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [49cd19882f](https://linux-hardware.org/?probe=49cd19882f) | Jul 23, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [cfaf6bb9ab](https://linux-hardware.org/?probe=cfaf6bb9ab) | Jul 21, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| Notebook      | W54_W550SU2                 | Notebook    | [b026148da5](https://linux-hardware.org/?probe=b026148da5) | Jul 15, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [f72a03865c](https://linux-hardware.org/?probe=f72a03865c) | Jul 11, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [c65f4896a2](https://linux-hardware.org/?probe=c65f4896a2) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [2878014d7a](https://linux-hardware.org/?probe=2878014d7a) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [4cfb82cbfe](https://linux-hardware.org/?probe=4cfb82cbfe) | Jul 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [826edd51bc](https://linux-hardware.org/?probe=826edd51bc) | Jul 07, 2021 |
| Lenovo        | LEGION 5 15IMH05 82AU       | Notebook    | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [aa05cca9b7](https://linux-hardware.org/?probe=aa05cca9b7) | Jun 30, 2021 |
| Biostar       | H310MHP                     | Desktop     | [0d3f648f3e](https://linux-hardware.org/?probe=0d3f648f3e) | Jun 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cc5fd0194e](https://linux-hardware.org/?probe=cc5fd0194e) | Jun 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fb3d7de63c](https://linux-hardware.org/?probe=fb3d7de63c) | Jun 26, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [486775a989](https://linux-hardware.org/?probe=486775a989) | Jun 23, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [4629f86f56](https://linux-hardware.org/?probe=4629f86f56) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [69dea4e3cf](https://linux-hardware.org/?probe=69dea4e3cf) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [2fd89c951e](https://linux-hardware.org/?probe=2fd89c951e) | Jun 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [11e99b82d5](https://linux-hardware.org/?probe=11e99b82d5) | Jun 22, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9ead1e1bb5](https://linux-hardware.org/?probe=9ead1e1bb5) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8144c83b50](https://linux-hardware.org/?probe=8144c83b50) | Jun 22, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [92ae7459b4](https://linux-hardware.org/?probe=92ae7459b4) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8a7a518013](https://linux-hardware.org/?probe=8a7a518013) | Jun 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [376c0ff95d](https://linux-hardware.org/?probe=376c0ff95d) | Jun 15, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [34801a2f74](https://linux-hardware.org/?probe=34801a2f74) | Jun 12, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [38b9682492](https://linux-hardware.org/?probe=38b9682492) | Jun 11, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [47a7837795](https://linux-hardware.org/?probe=47a7837795) | Jun 11, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [abd01e8eac](https://linux-hardware.org/?probe=abd01e8eac) | Jun 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [a93d77d45b](https://linux-hardware.org/?probe=a93d77d45b) | Jun 06, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| MSI           | GE72VR 6RF                  | Notebook    | [faea47290a](https://linux-hardware.org/?probe=faea47290a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [e7fda6091a](https://linux-hardware.org/?probe=e7fda6091a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d2a26e0f30](https://linux-hardware.org/?probe=d2a26e0f30) | May 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [51e1e33185](https://linux-hardware.org/?probe=51e1e33185) | May 20, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [14edf3bd00](https://linux-hardware.org/?probe=14edf3bd00) | May 16, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [ffc46c9472](https://linux-hardware.org/?probe=ffc46c9472) | May 14, 2021 |
| Acer          | Spin SP513-54N              | Convertible | [aa8934716b](https://linux-hardware.org/?probe=aa8934716b) | May 13, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [066f815622](https://linux-hardware.org/?probe=066f815622) | May 12, 2021 |
| HP            | 844C                        | Desktop     | [29f7cf64ce](https://linux-hardware.org/?probe=29f7cf64ce) | May 06, 2021 |
| HP            | 844C                        | Desktop     | [0534f06ec4](https://linux-hardware.org/?probe=0534f06ec4) | May 06, 2021 |
| Alienware     | 17 R3                       | Notebook    | [f9ee772f9e](https://linux-hardware.org/?probe=f9ee772f9e) | May 05, 2021 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [cb3058760e](https://linux-hardware.org/?probe=cb3058760e) | May 04, 2021 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [08ea956bfa](https://linux-hardware.org/?probe=08ea956bfa) | Apr 24, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d9bf75c99c](https://linux-hardware.org/?probe=d9bf75c99c) | Apr 23, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [22931f83cc](https://linux-hardware.org/?probe=22931f83cc) | Apr 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [25808be952](https://linux-hardware.org/?probe=25808be952) | Apr 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3c7f354ce4](https://linux-hardware.org/?probe=3c7f354ce4) | Apr 19, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d97babb331](https://linux-hardware.org/?probe=d97babb331) | Apr 18, 2021 |
| ASUSTek       | GL503VM                     | Notebook    | [743ff3a2aa](https://linux-hardware.org/?probe=743ff3a2aa) | Apr 18, 2021 |
| Medion        | P861X                       | Notebook    | [109599a6f6](https://linux-hardware.org/?probe=109599a6f6) | Apr 15, 2021 |
| Medion        | P861X                       | Notebook    | [ae05cea55d](https://linux-hardware.org/?probe=ae05cea55d) | Apr 15, 2021 |
| Medion        | E7419 MD60025               | Notebook    | [4deb77ef82](https://linux-hardware.org/?probe=4deb77ef82) | Apr 10, 2021 |
| MSI           | Z87 MPOWER                  | Desktop     | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [2012ac3d84](https://linux-hardware.org/?probe=2012ac3d84) | Apr 07, 2021 |
| Dell          | Inspiron 5755               | Notebook    | [ae6589874e](https://linux-hardware.org/?probe=ae6589874e) | Apr 07, 2021 |
| HP            | 2B3B                        | All in one  | [1a5d2c36ec](https://linux-hardware.org/?probe=1a5d2c36ec) | Apr 06, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [9f68dee6f5](https://linux-hardware.org/?probe=9f68dee6f5) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [23502edac5](https://linux-hardware.org/?probe=23502edac5) | Apr 01, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [8cc9da4310](https://linux-hardware.org/?probe=8cc9da4310) | Apr 01, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [13b2fdddc0](https://linux-hardware.org/?probe=13b2fdddc0) | Apr 01, 2021 |
| Dell          | 07KY25 A01                  | Desktop     | [8c4f2f9922](https://linux-hardware.org/?probe=8c4f2f9922) | Mar 31, 2021 |
| Medion        | E7419 MD60025               | Notebook    | [938494cf89](https://linux-hardware.org/?probe=938494cf89) | Mar 31, 2021 |
| Dell          | 07KY25 A01                  | Desktop     | [1b9efb1b29](https://linux-hardware.org/?probe=1b9efb1b29) | Mar 24, 2021 |
| Lenovo        | ThinkPad T470 20HD000RUS    | Notebook    | [751dd3bb74](https://linux-hardware.org/?probe=751dd3bb74) | Mar 19, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [097a0d616c](https://linux-hardware.org/?probe=097a0d616c) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [22054ffd75](https://linux-hardware.org/?probe=22054ffd75) | Mar 18, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1e6cbeb181](https://linux-hardware.org/?probe=1e6cbeb181) | Mar 17, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b4580812c2](https://linux-hardware.org/?probe=b4580812c2) | Mar 15, 2021 |
| HP            | 2AF7                        | Desktop     | [e0639ea4a5](https://linux-hardware.org/?probe=e0639ea4a5) | Mar 11, 2021 |
| HP            | 2AF7                        | Desktop     | [fb8d76722c](https://linux-hardware.org/?probe=fb8d76722c) | Mar 11, 2021 |
| Dell          | XPS L702X                   | Notebook    | [e3af15a170](https://linux-hardware.org/?probe=e3af15a170) | Mar 09, 2021 |
| Dell          | XPS L702X                   | Notebook    | [7fb3f476cf](https://linux-hardware.org/?probe=7fb3f476cf) | Mar 09, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [3741826c9a](https://linux-hardware.org/?probe=3741826c9a) | Mar 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c1f22a7521](https://linux-hardware.org/?probe=c1f22a7521) | Mar 05, 2021 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [404dab2464](https://linux-hardware.org/?probe=404dab2464) | Feb 27, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [29784f5b45](https://linux-hardware.org/?probe=29784f5b45) | Feb 23, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [13f9fc2ef3](https://linux-hardware.org/?probe=13f9fc2ef3) | Feb 18, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [c7e8878f7b](https://linux-hardware.org/?probe=c7e8878f7b) | Feb 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2e19f3b1af](https://linux-hardware.org/?probe=2e19f3b1af) | Feb 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [51244d0897](https://linux-hardware.org/?probe=51244d0897) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4RC0... | Notebook    | [3e146ba45b](https://linux-hardware.org/?probe=3e146ba45b) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [de3199a457](https://linux-hardware.org/?probe=de3199a457) | Feb 17, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [f821a0035b](https://linux-hardware.org/?probe=f821a0035b) | Feb 12, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [9dececac24](https://linux-hardware.org/?probe=9dececac24) | Feb 11, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [b73941c431](https://linux-hardware.org/?probe=b73941c431) | Feb 08, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [92487a475d](https://linux-hardware.org/?probe=92487a475d) | Feb 06, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [23cece38ed](https://linux-hardware.org/?probe=23cece38ed) | Feb 02, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | Notebook    | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| HP            | 1825                        | Desktop     | [3b6b80db46](https://linux-hardware.org/?probe=3b6b80db46) | Jan 31, 2021 |
| HP            | 1825                        | Desktop     | [1df894dea4](https://linux-hardware.org/?probe=1df894dea4) | Jan 31, 2021 |
| Dell          | Latitude E6520              | Notebook    | [24cbaa1c59](https://linux-hardware.org/?probe=24cbaa1c59) | Jan 30, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [793615c0de](https://linux-hardware.org/?probe=793615c0de) | Jan 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B90... | Notebook    | [dfb9858a8f](https://linux-hardware.org/?probe=dfb9858a8f) | Jan 29, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [dd3793c498](https://linux-hardware.org/?probe=dd3793c498) | Jan 28, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [36eaf717e9](https://linux-hardware.org/?probe=36eaf717e9) | Jan 26, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [b1be9375c0](https://linux-hardware.org/?probe=b1be9375c0) | Jan 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [7332b50f98](https://linux-hardware.org/?probe=7332b50f98) | Jan 24, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [11b9018ef1](https://linux-hardware.org/?probe=11b9018ef1) | Jan 23, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [c504347399](https://linux-hardware.org/?probe=c504347399) | Jan 23, 2021 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [3f895b585b](https://linux-hardware.org/?probe=3f895b585b) | Jan 22, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [643af77934](https://linux-hardware.org/?probe=643af77934) | Jan 18, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [61976e9745](https://linux-hardware.org/?probe=61976e9745) | Jan 18, 2021 |
| HP            | Compaq 6735b                | Notebook    | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [86c3c2d1d3](https://linux-hardware.org/?probe=86c3c2d1d3) | Jan 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [09f3ac6567](https://linux-hardware.org/?probe=09f3ac6567) | Jan 11, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [e392838a54](https://linux-hardware.org/?probe=e392838a54) | Jan 10, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [ad733c377c](https://linux-hardware.org/?probe=ad733c377c) | Jan 09, 2021 |
| ASUSTek       | CM5671                      | Desktop     | [069344a54e](https://linux-hardware.org/?probe=069344a54e) | Jan 07, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [d4206bf424](https://linux-hardware.org/?probe=d4206bf424) | Jan 07, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [a5612ca66a](https://linux-hardware.org/?probe=a5612ca66a) | Jan 07, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [8fe013f04a](https://linux-hardware.org/?probe=8fe013f04a) | Jan 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [2e0ef916c6](https://linux-hardware.org/?probe=2e0ef916c6) | Jan 03, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | Notebook    | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1d461bb9db](https://linux-hardware.org/?probe=1d461bb9db) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [436a2ca3ce](https://linux-hardware.org/?probe=436a2ca3ce) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [2df3b195c6](https://linux-hardware.org/?probe=2df3b195c6) | Dec 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [ce7f267835](https://linux-hardware.org/?probe=ce7f267835) | Dec 23, 2020 |
| Toshiba       | Satellite C55-A             | Notebook    | [43dbeef737](https://linux-hardware.org/?probe=43dbeef737) | Dec 22, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [35365be0e8](https://linux-hardware.org/?probe=35365be0e8) | Dec 19, 2020 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [b02c7cd17e](https://linux-hardware.org/?probe=b02c7cd17e) | Dec 19, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [ea7a52fdac](https://linux-hardware.org/?probe=ea7a52fdac) | Dec 16, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [62a5c95d51](https://linux-hardware.org/?probe=62a5c95d51) | Dec 14, 2020 |
| HP            | 8643 SMVB                   | Desktop     | [dccfba36f1](https://linux-hardware.org/?probe=dccfba36f1) | Dec 06, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [05e3eb32c9](https://linux-hardware.org/?probe=05e3eb32c9) | Dec 03, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [e63bb99c0a](https://linux-hardware.org/?probe=e63bb99c0a) | Nov 30, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [dc6ea9bfb8](https://linux-hardware.org/?probe=dc6ea9bfb8) | Nov 29, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [d4b3f84c86](https://linux-hardware.org/?probe=d4b3f84c86) | Nov 28, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a3d68dc126](https://linux-hardware.org/?probe=a3d68dc126) | Nov 19, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9faeae0d4](https://linux-hardware.org/?probe=d9faeae0d4) | Nov 19, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [11c79940a4](https://linux-hardware.org/?probe=11c79940a4) | Nov 19, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1ff8a24823](https://linux-hardware.org/?probe=1ff8a24823) | Nov 18, 2020 |
| HP            | 18E7                        | Desktop     | [f84cbfd465](https://linux-hardware.org/?probe=f84cbfd465) | Nov 10, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [79608bd849](https://linux-hardware.org/?probe=79608bd849) | Nov 06, 2020 |
| Dell          | Latitude E6430              | Notebook    | [760e7ca474](https://linux-hardware.org/?probe=760e7ca474) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e80ddac12f](https://linux-hardware.org/?probe=e80ddac12f) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [876b039494](https://linux-hardware.org/?probe=876b039494) | Nov 01, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [428abb1a9b](https://linux-hardware.org/?probe=428abb1a9b) | Oct 31, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [4e573bc6ff](https://linux-hardware.org/?probe=4e573bc6ff) | Oct 28, 2020 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [4b9d2b77cb](https://linux-hardware.org/?probe=4b9d2b77cb) | Oct 26, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b7772d9ff8](https://linux-hardware.org/?probe=b7772d9ff8) | Oct 13, 2020 |
| Dell          | 0R6JMP A00                  | Desktop     | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| OEM           | Unknown                     | Desktop     | [2e7a212437](https://linux-hardware.org/?probe=2e7a212437) | Sep 26, 2020 |
| Lenovo        | Board                       | Desktop     | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [4a3037422e](https://linux-hardware.org/?probe=4a3037422e) | Sep 04, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [7b8babe846](https://linux-hardware.org/?probe=7b8babe846) | Aug 27, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [e8a88c2b81](https://linux-hardware.org/?probe=e8a88c2b81) | Aug 12, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [7380887fb8](https://linux-hardware.org/?probe=7380887fb8) | Aug 09, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [faac6d06ac](https://linux-hardware.org/?probe=faac6d06ac) | Aug 09, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [73462df387](https://linux-hardware.org/?probe=73462df387) | Aug 07, 2020 |
| HP            | 450                         | Notebook    | [edeb9f6780](https://linux-hardware.org/?probe=edeb9f6780) | Apr 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Garuda Linux Soaring | 147       | 63.36%  |
| Garuda Linux         | 80        | 34.48%  |
| Garuda Rolling       | 5         | 2.16%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Garuda Linux | 229       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.17.1-zen1-1-zen   | 9         | 3.42%   |
| 5.15.2-zen1-1-zen   | 7         | 2.66%   |
| 5.16.4-zen1-1-zen   | 6         | 2.28%   |
| 5.14.14-zen1-1-zen  | 6         | 2.28%   |
| 5.15.7-zen1-1-zen   | 5         | 1.9%    |
| 5.15.13-zen1-1-zen  | 5         | 1.9%    |
| 5.15.12-zen1-1-zen  | 5         | 1.9%    |
| 5.13.9-zen1-1-zen   | 5         | 1.9%    |
| 5.13.13-zen1-1-zen  | 5         | 1.9%    |
| 5.11.16-zen1-1-zen  | 5         | 1.9%    |
| 5.11.11-zen1-1-zen  | 5         | 1.9%    |
| 5.16.2-zen1-1-zen   | 4         | 1.52%   |
| 5.16.16-zen1-1-zen  | 4         | 1.52%   |
| 5.15.6-zen2-1-zen   | 4         | 1.52%   |
| 5.10.4-107-tkg-bmq  | 4         | 1.52%   |
| 5.10.1-103-tkg-bmq  | 4         | 1.52%   |
| 5.9.10-zen1-1-zen   | 3         | 1.14%   |
| 5.9.1-zen2-1-zen    | 3         | 1.14%   |
| 5.17.3-zen1-1-zen   | 3         | 1.14%   |
| 5.16.5-zen1-1-zen   | 3         | 1.14%   |
| 5.16.14-zen1-1-zen  | 3         | 1.14%   |
| 5.16.11-zen1-1-zen  | 3         | 1.14%   |
| 5.15.5-zen1-1-zen   | 3         | 1.14%   |
| 5.15.10-zen1-1-zen  | 3         | 1.14%   |
| 5.14.6-zen1-1-zen   | 3         | 1.14%   |
| 5.14.15-zen1-1-zen  | 3         | 1.14%   |
| 5.10.8-112-tkg-bmq  | 3         | 1.14%   |
| 5.10.2-104-tkg-bmq  | 3         | 1.14%   |
| 5.10.15-120-tkg-bmq | 3         | 1.14%   |
| 5.10.10-115-tkg-bmq | 3         | 1.14%   |
| 5.9.8-zen1-1-zen    | 2         | 0.76%   |
| 5.9.2-zen1-1-zen    | 2         | 0.76%   |
| 5.9.11-zen2-1-zen   | 2         | 0.76%   |
| 5.8.14-zen1-1-zen   | 2         | 0.76%   |
| 5.16.9-zen1-1-zen   | 2         | 0.76%   |
| 5.16.8-zen1-1-zen   | 2         | 0.76%   |
| 5.16.8-arch1-1      | 2         | 0.76%   |
| 5.16.15-zen1-1-zen  | 2         | 0.76%   |
| 5.16.10-zen1-1-zen  | 2         | 0.76%   |
| 5.16.1-zen1-1-zen   | 2         | 0.76%   |
| 5.16.0-zen1-1-zen   | 2         | 0.76%   |
| 5.15.4-zen1-1-zen   | 2         | 0.76%   |
| 5.14.9-zen2-1-zen   | 2         | 0.76%   |
| 5.14.12-zen1-1-zen  | 2         | 0.76%   |
| 5.13.5-zen1-1-zen   | 2         | 0.76%   |
| 5.13.12-zen1-1-zen  | 2         | 0.76%   |
| 5.12.9-zen1-1-zen   | 2         | 0.76%   |
| 5.12.7-zen1-1-zen   | 2         | 0.76%   |
| 5.12.4-zen1-2-zen   | 2         | 0.76%   |
| 5.12.2-153-tkg-bmq  | 2         | 0.76%   |
| 5.12.15-zen1-1-zen  | 2         | 0.76%   |
| 5.12.14-zen1-1-zen  | 2         | 0.76%   |
| 5.12.13-zen1-1-zen  | 2         | 0.76%   |
| 5.12.12-AMD-znver2  | 2         | 0.76%   |
| 5.11.6-zen1-1-zen   | 2         | 0.76%   |
| 5.10.7-111-tkg-bmq  | 2         | 0.76%   |
| 5.9.9-zen1-1-zen    | 1         | 0.38%   |
| 5.9.6-zen1-1-zen    | 1         | 0.38%   |
| 5.9.4-zen1-1-zen    | 1         | 0.38%   |
| 5.9.14-99-tkg-bmq   | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 11        | 4.18%   |
| 5.15.2  | 7         | 2.66%   |
| 5.16.4  | 6         | 2.28%   |
| 5.15.7  | 6         | 2.28%   |
| 5.14.14 | 6         | 2.28%   |
| 5.11.11 | 6         | 2.28%   |
| 5.10.4  | 6         | 2.28%   |
| 5.17.3  | 5         | 1.9%    |
| 5.16.5  | 5         | 1.9%    |
| 5.15.6  | 5         | 1.9%    |
| 5.15.13 | 5         | 1.9%    |
| 5.15.12 | 5         | 1.9%    |
| 5.13.9  | 5         | 1.9%    |
| 5.13.13 | 5         | 1.9%    |
| 5.11.16 | 5         | 1.9%    |
| 5.16.8  | 4         | 1.52%   |
| 5.16.2  | 4         | 1.52%   |
| 5.16.16 | 4         | 1.52%   |
| 5.15.10 | 4         | 1.52%   |
| 5.12.13 | 4         | 1.52%   |
| 5.10.15 | 4         | 1.52%   |
| 5.10.1  | 4         | 1.52%   |
| 5.9.10  | 3         | 1.14%   |
| 5.9.1   | 3         | 1.14%   |
| 5.16.14 | 3         | 1.14%   |
| 5.16.11 | 3         | 1.14%   |
| 5.16.10 | 3         | 1.14%   |
| 5.16.0  | 3         | 1.14%   |
| 5.15.5  | 3         | 1.14%   |
| 5.14.6  | 3         | 1.14%   |
| 5.14.15 | 3         | 1.14%   |
| 5.14.12 | 3         | 1.14%   |
| 5.12.9  | 3         | 1.14%   |
| 5.12.12 | 3         | 1.14%   |
| 5.11.6  | 3         | 1.14%   |
| 5.10.8  | 3         | 1.14%   |
| 5.10.2  | 3         | 1.14%   |
| 5.10.10 | 3         | 1.14%   |
| 5.9.8   | 2         | 0.76%   |
| 5.9.2   | 2         | 0.76%   |
| 5.9.11  | 2         | 0.76%   |
| 5.8.14  | 2         | 0.76%   |
| 5.16.9  | 2         | 0.76%   |
| 5.16.15 | 2         | 0.76%   |
| 5.16.1  | 2         | 0.76%   |
| 5.15.4  | 2         | 0.76%   |
| 5.15.11 | 2         | 0.76%   |
| 5.14.9  | 2         | 0.76%   |
| 5.14.5  | 2         | 0.76%   |
| 5.14.11 | 2         | 0.76%   |
| 5.13.5  | 2         | 0.76%   |
| 5.13.4  | 2         | 0.76%   |
| 5.13.19 | 2         | 0.76%   |
| 5.13.12 | 2         | 0.76%   |
| 5.12.7  | 2         | 0.76%   |
| 5.12.4  | 2         | 0.76%   |
| 5.12.2  | 2         | 0.76%   |
| 5.12.15 | 2         | 0.76%   |
| 5.12.14 | 2         | 0.76%   |
| 5.11.0  | 2         | 0.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 43        | 17.2%   |
| 5.16    | 41        | 16.4%   |
| 5.10    | 36        | 14.4%   |
| 5.14    | 25        | 10%     |
| 5.12    | 23        | 9.2%    |
| 5.11    | 23        | 9.2%    |
| 5.13    | 21        | 8.4%    |
| 5.17    | 18        | 7.2%    |
| 5.9     | 13        | 5.2%    |
| 5.8     | 5         | 2%      |
| 5.6     | 1         | 0.4%    |
| 5.4     | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 229       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KDE5              | 140       | 60.34%  |
| KDE               | 34        | 14.66%  |
| GNOME             | 33        | 14.22%  |
| XFCE              | 9         | 3.88%   |
| X-Cinnamon        | 3         | 1.29%   |
| sway              | 2         | 0.86%   |
| qtile-default     | 2         | 0.86%   |
| i3                | 2         | 0.86%   |
| Deepin            | 2         | 0.86%   |
| Yaru:ubuntu:GNOME | 1         | 0.43%   |
| MATE              | 1         | 0.43%   |
| LXQt              | 1         | 0.43%   |
| Budgie            | 1         | 0.43%   |
| Unknown           | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 216       | 93.91%  |
| Wayland | 11        | 4.78%   |
| Tty     | 2         | 0.87%   |
| Unknown | 1         | 0.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 116       | 50.43%  |
| Unknown | 83        | 36.09%  |
| LightDM | 16        | 6.96%   |
| GDM     | 14        | 6.09%   |
| GREETD  | 1         | 0.43%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 115       | 49.78%  |
| en_GB   | 27        | 11.69%  |
| de_DE   | 18        | 7.79%   |
| en_IN   | 12        | 5.19%   |
| it_IT   | 7         | 3.03%   |
| es_ES   | 5         | 2.16%   |
| ru_RU   | 4         | 1.73%   |
| pt_BR   | 4         | 1.73%   |
| es_MX   | 4         | 1.73%   |
| en_AU   | 4         | 1.73%   |
| nl_NL   | 3         | 1.3%    |
| sv_SE   | 2         | 0.87%   |
| pl_PL   | 2         | 0.87%   |
| fr_FR   | 2         | 0.87%   |
| fr_BE   | 2         | 0.87%   |
| fi_FI   | 2         | 0.87%   |
| es_VE   | 2         | 0.87%   |
| es_CO   | 2         | 0.87%   |
| en_ZA   | 2         | 0.87%   |
| en_CA   | 2         | 0.87%   |
| tr_TR   | 1         | 0.43%   |
| sk_SK   | 1         | 0.43%   |
| nb_NO   | 1         | 0.43%   |
| ko_KR   | 1         | 0.43%   |
| iu_CA   | 1         | 0.43%   |
| es_AR   | 1         | 0.43%   |
| el_GR   | 1         | 0.43%   |
| de_AT   | 1         | 0.43%   |
| da_DK   | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 147       | 63.91%  |
| BIOS | 83        | 36.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 226       | 98.69%  |
| Ext4  | 2         | 0.87%   |
| F2fs  | 1         | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 137       | 59.57%  |
| Unknown | 80        | 34.78%  |
| MBR     | 13        | 5.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 205       | 88.36%  |
| Yes       | 27        | 11.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 155       | 67.39%  |
| Yes       | 75        | 32.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 40        | 17.47%  |
| Lenovo              | 36        | 15.72%  |
| Hewlett-Packard     | 30        | 13.1%   |
| MSI                 | 23        | 10.04%  |
| Dell                | 23        | 10.04%  |
| Gigabyte Technology | 16        | 6.99%   |
| Acer                | 14        | 6.11%   |
| ASRock              | 11        | 4.8%    |
| Apple               | 4         | 1.75%   |
| Notebook            | 3         | 1.31%   |
| Medion              | 3         | 1.31%   |
| Toshiba             | 2         | 0.87%   |
| Samsung Electronics | 2         | 0.87%   |
| Razer               | 2         | 0.87%   |
| Pegatron            | 2         | 0.87%   |
| Fujitsu             | 2         | 0.87%   |
| Alienware           | 2         | 0.87%   |
| Unknown             | 2         | 0.87%   |
| Sony                | 1         | 0.44%   |
| PC Specialist       | 1         | 0.44%   |
| Panasonic           | 1         | 0.44%   |
| OEM                 | 1         | 0.44%   |
| HUAWEI              | 1         | 0.44%   |
| HONOR               | 1         | 0.44%   |
| GPU Company         | 1         | 0.44%   |
| Google              | 1         | 0.44%   |
| Fujitsu Siemens     | 1         | 0.44%   |
| Chuwi               | 1         | 0.44%   |
| Casper              | 1         | 0.44%   |
| Biostar             | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 4         | 1.75%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 3         | 1.31%   |
| ASUS TUF GAMING X570-PLUS                  | 3         | 1.31%   |
| MSI MS-7C91                                | 2         | 0.87%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 0.87%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 0.87%   |
| Gigabyte AB350-Gaming 3                    | 2         | 0.87%   |
| Dell Inspiron 3668                         | 2         | 0.87%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 0.87%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 0.87%   |
| ASUS ROG Flow X13 GV301QH_GV301QH          | 2         | 0.87%   |
| ASUS All Series                            | 2         | 0.87%   |
| Acer Nitro AN515-44                        | 2         | 0.87%   |
| Toshiba Satellite E45DW-C                  | 1         | 0.44%   |
| Toshiba Satellite C55-A                    | 1         | 0.44%   |
| Sony VPCSB1C5E                             | 1         | 0.44%   |
| Samsung 550XCJ/550XCR                      | 1         | 0.44%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.44%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.44%   |
| Razer Blade                                | 1         | 0.44%   |
| Pegatron p7-1030                           | 1         | 0.44%   |
| Pegatron h9-1301es                         | 1         | 0.44%   |
| PC Specialist GK5NPFO                      | 1         | 0.44%   |
| Panasonic CF-191HYAX1M                     | 1         | 0.44%   |
| Notebook W54_W550SU2                       | 1         | 0.44%   |
| Notebook P7xxDM2(-G)                       | 1         | 0.44%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 0.44%   |
| MSI MS-7C90                                | 1         | 0.44%   |
| MSI MS-7C83                                | 1         | 0.44%   |
| MSI MS-7C52                                | 1         | 0.44%   |
| MSI MS-7C09                                | 1         | 0.44%   |
| MSI MS-7B98                                | 1         | 0.44%   |
| MSI MS-7B86                                | 1         | 0.44%   |
| MSI MS-7B09                                | 1         | 0.44%   |
| MSI MS-7A78                                | 1         | 0.44%   |
| MSI MS-7A39                                | 1         | 0.44%   |
| MSI MS-7A32                                | 1         | 0.44%   |
| MSI MS-7818                                | 1         | 0.44%   |
| MSI MS-7816                                | 1         | 0.44%   |
| MSI MS-7758                                | 1         | 0.44%   |
| MSI GS76 Stealth 11UG                      | 1         | 0.44%   |
| MSI GP75 Leopard 9SD                       | 1         | 0.44%   |
| MSI GF63 Thin 9SC                          | 1         | 0.44%   |
| MSI GF63 Thin 10SC                         | 1         | 0.44%   |
| MSI GE75 Raider 9SE                        | 1         | 0.44%   |
| MSI GE72VR 6RF                             | 1         | 0.44%   |
| MSI GE63 Raider RGB 8RE                    | 1         | 0.44%   |
| MSI A320M-HDV R4.0                         | 1         | 0.44%   |
| Medion P861X                               | 1         | 0.44%   |
| Medion E7419 MD60025                       | 1         | 0.44%   |
| Medion Akoya P5238 F/C395                  | 1         | 0.44%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 0.44%   |
| Lenovo ThinkStation S20 4105O1U            | 1         | 0.44%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB005WUS   | 1         | 0.44%   |
| Lenovo ThinkPad T530 24296KG               | 1         | 0.44%   |
| Lenovo ThinkPad T510 4384WB4               | 1         | 0.44%   |
| Lenovo ThinkPad T470s 20HGS0B900           | 1         | 0.44%   |
| Lenovo ThinkPad T470 20HD000RUS            | 1         | 0.44%   |
| Lenovo ThinkPad T440p 20AWS58F00           | 1         | 0.44%   |
| Lenovo ThinkPad T440p 20AWS4RC00           | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 12        | 5.24%   |
| Dell Inspiron          | 11        | 4.8%    |
| Lenovo IdeaPad         | 10        | 4.37%   |
| HP Pavilion            | 10        | 4.37%   |
| ASUS ROG               | 10        | 4.37%   |
| Acer Aspire            | 7         | 3.06%   |
| ASUS PRIME             | 6         | 2.62%   |
| Lenovo Legion          | 5         | 2.18%   |
| Dell Latitude          | 5         | 2.18%   |
| ASUS TUF               | 5         | 2.18%   |
| HP Laptop              | 4         | 1.75%   |
| Dell XPS               | 4         | 1.75%   |
| Acer Nitro             | 4         | 1.75%   |
| Unknown                | 4         | 1.75%   |
| Lenovo ThinkCentre     | 3         | 1.31%   |
| HP OMEN                | 3         | 1.31%   |
| Toshiba Satellite      | 2         | 0.87%   |
| Razer Blade            | 2         | 0.87%   |
| MSI MS-7C91            | 2         | 0.87%   |
| MSI GF63               | 2         | 0.87%   |
| HP EliteBook           | 2         | 0.87%   |
| Gigabyte X570          | 2         | 0.87%   |
| Gigabyte B550          | 2         | 0.87%   |
| Gigabyte B450          | 2         | 0.87%   |
| Gigabyte AB350-Gaming  | 2         | 0.87%   |
| Dell OptiPlex          | 2         | 0.87%   |
| ASUS VivoBook          | 2         | 0.87%   |
| ASUS ASUS              | 2         | 0.87%   |
| ASUS All               | 2         | 0.87%   |
| ASRock X470            | 2         | 0.87%   |
| Sony VPCSB1C5E         | 1         | 0.44%   |
| Samsung 550XCJ         | 1         | 0.44%   |
| Samsung 300V3A         | 1         | 0.44%   |
| Pegatron p7-1030       | 1         | 0.44%   |
| Pegatron h9-1301es     | 1         | 0.44%   |
| PC Specialist GK5NPFO  | 1         | 0.44%   |
| Panasonic CF-191HYAX1M | 1         | 0.44%   |
| Notebook W54           | 1         | 0.44%   |
| Notebook P7xxDM2(-G)   | 1         | 0.44%   |
| Notebook N85           | 1         | 0.44%   |
| MSI MS-7C90            | 1         | 0.44%   |
| MSI MS-7C83            | 1         | 0.44%   |
| MSI MS-7C52            | 1         | 0.44%   |
| MSI MS-7C09            | 1         | 0.44%   |
| MSI MS-7B98            | 1         | 0.44%   |
| MSI MS-7B86            | 1         | 0.44%   |
| MSI MS-7B09            | 1         | 0.44%   |
| MSI MS-7A78            | 1         | 0.44%   |
| MSI MS-7A39            | 1         | 0.44%   |
| MSI MS-7A32            | 1         | 0.44%   |
| MSI MS-7818            | 1         | 0.44%   |
| MSI MS-7816            | 1         | 0.44%   |
| MSI MS-7758            | 1         | 0.44%   |
| MSI GS76               | 1         | 0.44%   |
| MSI GP75               | 1         | 0.44%   |
| MSI GE75               | 1         | 0.44%   |
| MSI GE72VR             | 1         | 0.44%   |
| MSI GE63               | 1         | 0.44%   |
| MSI A320M-HDV          | 1         | 0.44%   |
| Medion P861X           | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 41        | 17.9%   |
| 2019 | 29        | 12.66%  |
| 2021 | 26        | 11.35%  |
| 2018 | 25        | 10.92%  |
| 2017 | 24        | 10.48%  |
| 2013 | 16        | 6.99%   |
| 2016 | 14        | 6.11%   |
| 2014 | 13        | 5.68%   |
| 2012 | 13        | 5.68%   |
| 2011 | 9         | 3.93%   |
| 2015 | 6         | 2.62%   |
| 2010 | 6         | 2.62%   |
| 2009 | 4         | 1.75%   |
| 2007 | 2         | 0.87%   |
| 2008 | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 125       | 54.59%  |
| Desktop     | 95        | 41.48%  |
| Convertible | 4         | 1.75%   |
| All in one  | 4         | 1.75%   |
| Mini pc     | 1         | 0.44%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 229       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 228       | 99.56%  |
| Yes  | 1         | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 63        | 27.27%  |
| 4.01-8.0    | 51        | 22.08%  |
| 8.01-16.0   | 50        | 21.65%  |
| 32.01-64.0  | 38        | 16.45%  |
| 3.01-4.0    | 13        | 5.63%   |
| 24.01-32.0  | 10        | 4.33%   |
| 64.01-256.0 | 5         | 2.16%   |
| 2.01-3.0    | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 89        | 36.33%  |
| 3.01-4.0   | 58        | 23.67%  |
| 2.01-3.0   | 50        | 20.41%  |
| 8.01-16.0  | 28        | 11.43%  |
| 1.01-2.0   | 14        | 5.71%   |
| 16.01-24.0 | 4         | 1.63%   |
| 32.01-64.0 | 1         | 0.41%   |
| 0.51-1.0   | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 95        | 40.25%  |
| 2      | 73        | 30.93%  |
| 3      | 33        | 13.98%  |
| 4      | 18        | 7.63%   |
| 5      | 10        | 4.24%   |
| 9      | 3         | 1.27%   |
| 6      | 3         | 1.27%   |
| 14     | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 172       | 73.82%  |
| Yes       | 61        | 26.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 85.59%  |
| No        | 33        | 14.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 80.26%  |
| No        | 46        | 19.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 71%     |
| No        | 67        | 29%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 73        | 31.74%  |
| Germany      | 25        | 10.87%  |
| UK           | 17        | 7.39%   |
| India        | 12        | 5.22%   |
| Italy        | 11        | 4.78%   |
| Sweden       | 5         | 2.17%   |
| Spain        | 5         | 2.17%   |
| Russia       | 5         | 2.17%   |
| Romania      | 5         | 2.17%   |
| Netherlands  | 5         | 2.17%   |
| Mexico       | 5         | 2.17%   |
| Canada       | 5         | 2.17%   |
| Brazil       | 5         | 2.17%   |
| Poland       | 4         | 1.74%   |
| France       | 4         | 1.74%   |
| Australia    | 4         | 1.74%   |
| Finland      | 3         | 1.3%    |
| Belgium      | 3         | 1.3%    |
| Venezuela    | 2         | 0.87%   |
| Turkey       | 2         | 0.87%   |
| South Africa | 2         | 0.87%   |
| Puerto Rico  | 2         | 0.87%   |
| Denmark      | 2         | 0.87%   |
| Colombia     | 2         | 0.87%   |
| Switzerland  | 1         | 0.43%   |
| South Korea  | 1         | 0.43%   |
| Slovenia     | 1         | 0.43%   |
| Slovakia     | 1         | 0.43%   |
| Singapore    | 1         | 0.43%   |
| Serbia       | 1         | 0.43%   |
| Philippines  | 1         | 0.43%   |
| Norway       | 1         | 0.43%   |
| Luxembourg   | 1         | 0.43%   |
| Lithuania    | 1         | 0.43%   |
| Latvia       | 1         | 0.43%   |
| Kuwait       | 1         | 0.43%   |
| Kenya        | 1         | 0.43%   |
| Iceland      | 1         | 0.43%   |
| Hungary      | 1         | 0.43%   |
| Greece       | 1         | 0.43%   |
| Czechia      | 1         | 0.43%   |
| China        | 1         | 0.43%   |
| Chile        | 1         | 0.43%   |
| Bahrain      | 1         | 0.43%   |
| Austria      | 1         | 0.43%   |
| Argentina    | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| London                 | 5         | 2.07%   |
| Portland               | 3         | 1.24%   |
| Berlin                 | 3         | 1.24%   |
| Sydney                 | 2         | 0.83%   |
| San Jose               | 2         | 0.83%   |
| Puebla City            | 2         | 0.83%   |
| Oklahoma City          | 2         | 0.83%   |
| Milan                  | 2         | 0.83%   |
| Kingsport              | 2         | 0.83%   |
| Helsinki               | 2         | 0.83%   |
| Groningen              | 2         | 0.83%   |
| Florence               | 2         | 0.83%   |
| Chicago                | 2         | 0.83%   |
| Cape Town              | 2         | 0.83%   |
| Calenzano              | 2         | 0.83%   |
| Bryansk                | 2         | 0.83%   |
| Winston-Salem          | 1         | 0.41%   |
| Windermere             | 1         | 0.41%   |
| West Des Moines        | 1         | 0.41%   |
| Welwyn Garden City     | 1         | 0.41%   |
| Weiterstadt            | 1         | 0.41%   |
| Warsaw                 | 1         | 0.41%   |
| Vufflens-la-Ville      | 1         | 0.41%   |
| Volzhskiy              | 1         | 0.41%   |
| Volgograd              | 1         | 0.41%   |
| Viganello              | 1         | 0.41%   |
| Vienna                 | 1         | 0.41%   |
| Västerås             | 1         | 0.41%   |
| Valenzano              | 1         | 0.41%   |
| Valencia               | 1         | 0.41%   |
| Valence                | 1         | 0.41%   |
| Turku                  | 1         | 0.41%   |
| Turin                  | 1         | 0.41%   |
| Tucson                 | 1         | 0.41%   |
| Toronto                | 1         | 0.41%   |
| Toms River             | 1         | 0.41%   |
| TimiИ™oara          | 1         | 0.41%   |
| TimiÈ™oara          | 1         | 0.41%   |
| Tekoa                  | 1         | 0.41%   |
| Tampa                  | 1         | 0.41%   |
| Sunrise Beach          | 1         | 0.41%   |
| Stuttgart              | 1         | 0.41%   |
| Stockton-on-Tees       | 1         | 0.41%   |
| Stockholm              | 1         | 0.41%   |
| Stavropol              | 1         | 0.41%   |
| St Louis               | 1         | 0.41%   |
| Spring Hill            | 1         | 0.41%   |
| Spitalfields           | 1         | 0.41%   |
| Southampton            | 1         | 0.41%   |
| Singapore              | 1         | 0.41%   |
| Sighetu MarmaÅ£iei   | 1         | 0.41%   |
| Shreveport             | 1         | 0.41%   |
| Seattle                | 1         | 0.41%   |
| Satu Mare              | 1         | 0.41%   |
| Sarasota               | 1         | 0.41%   |
| Santa Cruz de Tenerife | 1         | 0.41%   |
| Santa Clara            | 1         | 0.41%   |
| San Juan               | 1         | 0.41%   |
| San Francisco          | 1         | 0.41%   |
| Salto da Divisa        | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 74        | 136    | 17.09%  |
| WDC                       | 66        | 87     | 15.24%  |
| Seagate                   | 66        | 93     | 15.24%  |
| Toshiba                   | 28        | 32     | 6.47%   |
| Sandisk                   | 21        | 29     | 4.85%   |
| Crucial                   | 20        | 29     | 4.62%   |
| Kingston                  | 19        | 26     | 4.39%   |
| SK Hynix                  | 14        | 16     | 3.23%   |
| Unknown                   | 10        | 10     | 2.31%   |
| HGST                      | 10        | 10     | 2.31%   |
| Phison                    | 9         | 10     | 2.08%   |
| Intel                     | 9         | 11     | 2.08%   |
| Hitachi                   | 7         | 7      | 1.62%   |
| PNY                       | 6         | 6      | 1.39%   |
| SPCC                      | 5         | 5      | 1.15%   |
| Micron Technology         | 5         | 5      | 1.15%   |
| A-DATA Technology         | 5         | 8      | 1.15%   |
| Silicon Motion            | 4         | 4      | 0.92%   |
| Corsair                   | 4         | 7      | 0.92%   |
| China                     | 4         | 6      | 0.92%   |
| XPG                       | 3         | 4      | 0.69%   |
| LITEON                    | 3         | 3      | 0.69%   |
| KIOXIA                    | 3         | 4      | 0.69%   |
| Union Memory (Shenzhen)   | 2         | 2      | 0.46%   |
| Transcend                 | 2         | 2      | 0.46%   |
| Mushkin                   | 2         | 2      | 0.46%   |
| Micron/Crucial Technology | 2         | 3      | 0.46%   |
| LITEONIT                  | 2         | 2      | 0.46%   |
| Intenso                   | 2         | 3      | 0.46%   |
| WDC WDS                   | 1         | 1      | 0.23%   |
| WD MediaMax               | 1         | 1      | 0.23%   |
| VisionTek                 | 1         | 2      | 0.23%   |
| USB30                     | 1         | 2      | 0.23%   |
| UMIS                      | 1         | 1      | 0.23%   |
| TO Exter                  | 1         | 1      | 0.23%   |
| Team                      | 1         | 2      | 0.23%   |
| SSSTC                     | 1         | 1      | 0.23%   |
| ShanDianZhe               | 1         | 1      | 0.23%   |
| SABRENT                   | 1         | 2      | 0.23%   |
| QUMO                      | 1         | 1      | 0.23%   |
| PNY CS90                  | 1         | 1      | 0.23%   |
| Phison Electronics        | 1         | 1      | 0.23%   |
| OCZ                       | 1         | 1      | 0.23%   |
| Netac                     | 1         | 1      | 0.23%   |
| Lenovo                    | 1         | 1      | 0.23%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.23%   |
| Inateck                   | 1         | 1      | 0.23%   |
| HS-SSD-E100               | 1         | 1      | 0.23%   |
| FORESEE                   | 1         | 1      | 0.23%   |
| EMTEC                     | 1         | 1      | 0.23%   |
| ASMT                      | 1         | 1      | 0.23%   |
| ASMedia                   | 1         | 2      | 0.23%   |
| Apple                     | 1         | 1      | 0.23%   |
| Apacer                    | 1         | 1      | 0.23%   |
| Unknown                   | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB           | 9         | 1.84%   |
| Samsung SSD 970 EVO Plus 500GB       | 6         | 1.23%   |
| Samsung SSD 860 EVO 500GB            | 6         | 1.23%   |
| Samsung SSD 850 EVO 250GB            | 6         | 1.23%   |
| Crucial CT1000MX500SSD1 1TB          | 6         | 1.23%   |
| Seagate ST2000DM008-2FR102 2TB       | 5         | 1.02%   |
| Seagate ST1000LM049-2GH172 1TB       | 5         | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 1.02%   |
| Samsung SSD 860 EVO 1TB              | 5         | 1.02%   |
| Seagate ST1000DM010-2EP102 1TB       | 4         | 0.82%   |
| SanDisk SSD PLUS 1000GB              | 4         | 0.82%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 0.82%   |
| WDC WD10EZEX-60WN4A0 1TB             | 3         | 0.61%   |
| Toshiba MQ01ABD100 1TB               | 3         | 0.61%   |
| Toshiba DT01ACA100 1TB               | 3         | 0.61%   |
| Seagate ST4000DM004-2CV104 4TB       | 3         | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.61%   |
| Seagate Portable 5TB                 | 3         | 0.61%   |
| Sandisk NVMe SSD Drive 500GB         | 3         | 0.61%   |
| Sandisk NVMe SSD Drive 1TB           | 3         | 0.61%   |
| Samsung SSD 970 EVO 250GB            | 3         | 0.61%   |
| Samsung SSD 870 EVO 500GB            | 3         | 0.61%   |
| PNY ELITE PSSD 480GB                 | 3         | 0.61%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 0.61%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.61%   |
| XPG NVMe SSD Drive 512GB             | 2         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 2         | 0.41%   |
| WDC WD20EARX-00PASB0 2TB             | 2         | 0.41%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.41%   |
| WDC WD10EZEX-00BN5A0 1TB             | 2         | 0.41%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 2         | 0.41%   |
| Unknown MMC Card  16GB               | 2         | 0.41%   |
| Toshiba HDWD110 1TB                  | 2         | 0.41%   |
| SPCC Solid State Disk 512GB          | 2         | 0.41%   |
| SK Hynix SC311 SATA 256GB SSD        | 2         | 0.41%   |
| SK Hynix NVMe SSD Drive 512GB        | 2         | 0.41%   |
| Seagate ST3320820AS 320GB            | 2         | 0.41%   |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB       | 2         | 0.41%   |
| Seagate ST2000DL003-9VT166 2TB       | 2         | 0.41%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.41%   |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.41%   |
| Seagate Expansion+ 2TB               | 2         | 0.41%   |
| Seagate Expansion Desk 4TB           | 2         | 0.41%   |
| Seagate Backup+ Hub BK 4TB           | 2         | 0.41%   |
| Samsung SSD 980 PRO 500GB            | 2         | 0.41%   |
| Samsung SSD 970 EVO Plus 2TB         | 2         | 0.41%   |
| Samsung SSD 870 QVO 1TB              | 2         | 0.41%   |
| Samsung SSD 870 EVO 2TB              | 2         | 0.41%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.41%   |
| Samsung NVMe SSD Drive 256GB         | 2         | 0.41%   |
| Samsung NVMe SSD Drive 250GB         | 2         | 0.41%   |
| Samsung NVMe SSD Drive 1024GB        | 2         | 0.41%   |
| Samsung MZYLF128HCHP-000L2 128GB SSD | 2         | 0.41%   |
| Phison NVMe SSD Drive 2TB            | 2         | 0.41%   |
| Phison NVMe SSD Drive 256GB          | 2         | 0.41%   |
| Micron/Crucial NVMe SSD Drive 1TB    | 2         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 88     | 41.72%  |
| WDC                 | 42        | 59     | 27.81%  |
| Toshiba             | 19        | 22     | 12.58%  |
| HGST                | 10        | 10     | 6.62%   |
| Hitachi             | 7         | 7      | 4.64%   |
| Samsung Electronics | 4         | 4      | 2.65%   |
| Unknown             | 1         | 1      | 0.66%   |
| SABRENT             | 1         | 2      | 0.66%   |
| Intenso             | 1         | 2      | 0.66%   |
| Inateck             | 1         | 1      | 0.66%   |
| ASMT                | 1         | 1      | 0.66%   |
| Apple               | 1         | 1      | 0.66%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 54     | 26.43%  |
| Kingston            | 16        | 22     | 11.43%  |
| Crucial             | 16        | 23     | 11.43%  |
| SanDisk             | 11        | 18     | 7.86%   |
| WDC                 | 9         | 10     | 6.43%   |
| PNY                 | 5         | 5      | 3.57%   |
| A-DATA Technology   | 5         | 8      | 3.57%   |
| SPCC                | 4         | 4      | 2.86%   |
| SK Hynix            | 4         | 5      | 2.86%   |
| China               | 4         | 6      | 2.86%   |
| Toshiba             | 3         | 4      | 2.14%   |
| LITEON              | 3         | 3      | 2.14%   |
| Transcend           | 2         | 2      | 1.43%   |
| Mushkin             | 2         | 2      | 1.43%   |
| LITEONIT            | 2         | 2      | 1.43%   |
| WDC WDS             | 1         | 1      | 0.71%   |
| VisionTek           | 1         | 2      | 0.71%   |
| USB30               | 1         | 2      | 0.71%   |
| Unknown             | 1         | 1      | 0.71%   |
| TO Exter            | 1         | 1      | 0.71%   |
| Team                | 1         | 2      | 0.71%   |
| QUMO                | 1         | 1      | 0.71%   |
| PNY CS90            | 1         | 1      | 0.71%   |
| OCZ                 | 1         | 1      | 0.71%   |
| Netac               | 1         | 1      | 0.71%   |
| Micron Technology   | 1         | 1      | 0.71%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.71%   |
| Intenso             | 1         | 1      | 0.71%   |
| FORESEE             | 1         | 1      | 0.71%   |
| EMTEC               | 1         | 1      | 0.71%   |
| Corsair             | 1         | 1      | 0.71%   |
| ASMedia             | 1         | 2      | 0.71%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 119       | 198    | 32.34%  |
| NVMe    | 116       | 187    | 31.52%  |
| SSD     | 114       | 189    | 30.98%  |
| Unknown | 11        | 11     | 2.99%   |
| MMC     | 8         | 8      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 168       | 351    | 52.34%  |
| NVMe | 116       | 187    | 36.14%  |
| SAS  | 29        | 47     | 9.03%   |
| MMC  | 8         | 8      | 2.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 112       | 174    | 41.95%  |
| 0.51-1.0   | 93        | 122    | 34.83%  |
| 1.01-2.0   | 36        | 55     | 13.48%  |
| 3.01-4.0   | 12        | 14     | 4.49%   |
| 2.01-3.0   | 8         | 14     | 3%      |
| 4.01-10.0  | 4         | 5      | 1.5%    |
| 10.01-20.0 | 2         | 3      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 92        | 39.48%  |
| 1001-2000      | 48        | 20.6%   |
| 501-1000       | 35        | 15.02%  |
| 2001-3000      | 30        | 12.88%  |
| 251-500        | 13        | 5.58%   |
| Unknown        | 10        | 4.29%   |
| 101-250        | 3         | 1.29%   |
| 1-20           | 2         | 0.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 57        | 23.46%  |
| 251-500        | 46        | 18.93%  |
| 1001-2000      | 35        | 14.4%   |
| 501-1000       | 32        | 13.17%  |
| 51-100         | 29        | 11.93%  |
| More than 3000 | 14        | 5.76%   |
| 2001-3000      | 14        | 5.76%   |
| Unknown        | 10        | 4.12%   |
| 21-50          | 3         | 1.23%   |
| 1-20           | 3         | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60A0RT0 500GB          | 1         | 1      | 4.17%   |
| WDC WD5000AAKS-00E4A0 500GB           | 1         | 1      | 4.17%   |
| WDC WD30EZRX-00DC0B0 3TB              | 1         | 1      | 4.17%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 4.17%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1         | 1      | 4.17%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 4.17%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 4.17%   |
| Seagate ST4000DM004-2CV104 4TB        | 1         | 1      | 4.17%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 4.17%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 4.17%   |
| Samsung Electronics SSD 980 1TB       | 1         | 2      | 4.17%   |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 7      | 4.17%   |
| OCZ TRION100 480GB SSD                | 1         | 1      | 4.17%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 4.17%   |
| Kingston SH103S3240G 240GB SSD        | 1         | 1      | 4.17%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 4.17%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 4.17%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 4.17%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 4.17%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 4.17%   |
| HGST HTS541075A9E680 752GB            | 1         | 1      | 4.17%   |
| Crucial CT960M500SSD1 960GB           | 1         | 1      | 4.17%   |
| Apple HDD HTS545050A7E362 500GB       | 1         | 1      | 4.17%   |
| A-DATA Technology SU800 1TB SSD       | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 26.09%  |
| Seagate             | 4         | 4      | 17.39%  |
| Hitachi             | 3         | 3      | 13.04%  |
| HGST                | 3         | 3      | 13.04%  |
| Kingston            | 2         | 2      | 8.7%    |
| Samsung Electronics | 1         | 9      | 4.35%   |
| OCZ                 | 1         | 1      | 4.35%   |
| Crucial             | 1         | 1      | 4.35%   |
| Apple               | 1         | 1      | 4.35%   |
| A-DATA Technology   | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 6      | 35.29%  |
| Seagate | 4         | 4      | 23.53%  |
| Hitachi | 3         | 3      | 17.65%  |
| HGST    | 3         | 3      | 17.65%  |
| Apple   | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 17     | 73.91%  |
| SSD  | 5         | 5      | 21.74%  |
| NVMe | 1         | 9      | 4.35%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 130       | 276    | 47.97%  |
| Detected | 118       | 286    | 43.54%  |
| Malfunc  | 23        | 31     | 8.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 133       | 39.58%  |
| AMD                            | 71        | 21.13%  |
| Samsung Electronics            | 41        | 12.2%   |
| Sandisk                        | 24        | 7.14%   |
| Phison Electronics             | 14        | 4.17%   |
| SK Hynix                       | 10        | 2.98%   |
| Toshiba America Info Systems   | 5         | 1.49%   |
| Micron/Crucial Technology      | 5         | 1.49%   |
| ASMedia Technology             | 5         | 1.49%   |
| Union Memory (Shenzhen)        | 4         | 1.19%   |
| Silicon Motion                 | 4         | 1.19%   |
| Kingston Technology Company    | 4         | 1.19%   |
| Micron Technology              | 3         | 0.89%   |
| Marvell Technology Group       | 2         | 0.6%    |
| KIOXIA                         | 2         | 0.6%    |
| JMicron Technology             | 2         | 0.6%    |
| ADATA Technology               | 2         | 0.6%    |
| Solid State Storage Technology | 1         | 0.3%    |
| Shenzhen Longsys Electronics   | 1         | 0.3%    |
| Realtek Semiconductor          | 1         | 0.3%    |
| Nvidia                         | 1         | 0.3%    |
| Lenovo                         | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 53        | 13.8%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 33        | 8.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 3.91%   |
| AMD 400 Series Chipset SATA Controller                                           | 13        | 3.39%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 10        | 2.6%    |
| Phison E12 NVMe Controller                                                       | 10        | 2.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 2.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 2.6%    |
| AMD 500 Series Chipset SATA Controller                                           | 9         | 2.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 2.08%   |
| Intel SSD 660P Series                                                            | 6         | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 1.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 6         | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 1.3%    |
| Samsung NVMe SSD Controller 980                                                  | 5         | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 5         | 1.3%    |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 1.3%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 4         | 1.04%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 4         | 1.04%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 1.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 4         | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 4         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4         | 1.04%   |
| AMD 300 Series Chipset SATA Controller                                           | 4         | 1.04%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.78%   |
| SK Hynix Gold P31 SSD                                                            | 3         | 0.78%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.78%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 0.78%   |
| Sandisk Non-Volatile memory controller                                           | 3         | 0.78%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3         | 0.78%   |
| Micron Non-Volatile memory controller                                            | 3         | 0.78%   |
| Kingston Company A2000 NVMe SSD                                                  | 3         | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.78%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.78%   |
| AMD X399 Series Chipset SATA Controller                                          | 3         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 3         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.78%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.52%   |
| SK Hynix BC511                                                                   | 2         | 0.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.52%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.52%   |
| Phison NVMe Storage Controller                                                   | 2         | 0.52%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.52%   |
| Micron/Crucial NVMe Controller                                                   | 2         | 0.52%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 0.52%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 0.52%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.52%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 2         | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 0.52%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 2         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 176       | 54.49%  |
| NVMe | 115       | 35.6%   |
| RAID | 19        | 5.88%   |
| IDE  | 13        | 4.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 141       | 61.57%  |
| AMD    | 88        | 38.43%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 3.06%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 2.62%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 2.62%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 2.18%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 2.18%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 1.75%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 1.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.31%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 1.31%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.31%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 1.31%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 1.31%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 1.31%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.31%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.31%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.87%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.87%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.87%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.87%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2         | 0.87%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.87%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.87%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 0.87%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.87%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 2         | 0.87%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.87%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2         | 0.87%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.87%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 0.87%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.87%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.87%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.87%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 0.87%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2         | 0.87%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2         | 0.87%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 0.87%   |
| Intel Xeon CPU W3550 @ 3.07GHz                | 1         | 0.44%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz           | 1         | 0.44%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.44%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.44%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.44%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.44%   |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.44%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.44%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.44%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.44%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.44%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.44%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.44%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.44%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.44%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.44%   |
| Intel Core i7-6850K CPU @ 3.60GHz             | 1         | 0.44%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.44%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 0.44%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1         | 0.44%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 55        | 24.02%  |
| Intel Core i5           | 44        | 19.21%  |
| AMD Ryzen 7             | 27        | 11.79%  |
| AMD Ryzen 5             | 27        | 11.79%  |
| Intel Core i3           | 16        | 6.99%   |
| AMD Ryzen 9             | 9         | 3.93%   |
| Other                   | 8         | 3.49%   |
| Intel Celeron           | 7         | 3.06%   |
| AMD Ryzen 3             | 4         | 1.75%   |
| AMD Ryzen Threadripper  | 3         | 1.31%   |
| AMD FX                  | 3         | 1.31%   |
| Intel Xeon              | 2         | 0.87%   |
| Intel Pentium Silver    | 2         | 0.87%   |
| Intel Pentium Dual-Core | 2         | 0.87%   |
| Intel Pentium           | 2         | 0.87%   |
| Intel Core 2 Duo        | 2         | 0.87%   |
| AMD Ryzen 7 PRO         | 2         | 0.87%   |
| AMD A8                  | 2         | 0.87%   |
| AMD A4                  | 2         | 0.87%   |
| AMD A10                 | 2         | 0.87%   |
| Intel Core m3           | 1         | 0.44%   |
| Intel Core i9           | 1         | 0.44%   |
| Intel Core 2 Quad       | 1         | 0.44%   |
| AMD Turion              | 1         | 0.44%   |
| AMD Phenom II X6        | 1         | 0.44%   |
| AMD Phenom II X4        | 1         | 0.44%   |
| AMD Phenom II X2        | 1         | 0.44%   |
| AMD A6                  | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 79        | 34.5%   |
| 2      | 61        | 26.64%  |
| 6      | 46        | 20.09%  |
| 8      | 33        | 14.41%  |
| 16     | 4         | 1.75%   |
| 12     | 4         | 1.75%   |
| 24     | 1         | 0.44%   |
| 10     | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 229       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 182       | 79.48%  |
| 1      | 47        | 20.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 229       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 95        | 40.6%   |
| 0x306a9    | 11        | 4.7%    |
| 0x306c3    | 10        | 4.27%   |
| 0x906ea    | 9         | 3.85%   |
| 0x206a7    | 8         | 3.42%   |
| 0x906e9    | 6         | 2.56%   |
| 0x0a50000c | 6         | 2.56%   |
| 0x08701021 | 6         | 2.56%   |
| 0x0800820d | 6         | 2.56%   |
| 0xa0652    | 5         | 2.14%   |
| 0x506e3    | 4         | 1.71%   |
| 0x08600103 | 4         | 1.71%   |
| 0x08108109 | 4         | 1.71%   |
| 0x806e9    | 3         | 1.28%   |
| 0x08600106 | 3         | 1.28%   |
| 0x08600104 | 3         | 1.28%   |
| 0x08108102 | 3         | 1.28%   |
| 0x806ec    | 2         | 0.85%   |
| 0x806ea    | 2         | 0.85%   |
| 0x806c1    | 2         | 0.85%   |
| 0x406e3    | 2         | 0.85%   |
| 0x40651    | 2         | 0.85%   |
| 0x106e5    | 2         | 0.85%   |
| 0x1067a    | 2         | 0.85%   |
| 0x08608103 | 2         | 0.85%   |
| 0x08001137 | 2         | 0.85%   |
| 0x06006705 | 2         | 0.85%   |
| 0xa0660    | 1         | 0.43%   |
| 0xa0655    | 1         | 0.43%   |
| 0xa0653    | 1         | 0.43%   |
| 0x906ed    | 1         | 0.43%   |
| 0x906ec    | 1         | 0.43%   |
| 0x906eb    | 1         | 0.43%   |
| 0x706e5    | 1         | 0.43%   |
| 0x706a8    | 1         | 0.43%   |
| 0x706a1    | 1         | 0.43%   |
| 0x506c9    | 1         | 0.43%   |
| 0x406c4    | 1         | 0.43%   |
| 0x20655    | 1         | 0.43%   |
| 0x106a5    | 1         | 0.43%   |
| 0x10676    | 1         | 0.43%   |
| 0x0a50000b | 1         | 0.43%   |
| 0x0a201204 | 1         | 0.43%   |
| 0x0a201016 | 1         | 0.43%   |
| 0x0a201009 | 1         | 0.43%   |
| 0x08701013 | 1         | 0.43%   |
| 0x08101016 | 1         | 0.43%   |
| 0x0810100b | 1         | 0.43%   |
| 0x08101007 | 1         | 0.43%   |
| 0x07030105 | 1         | 0.43%   |
| 0x0700010f | 1         | 0.43%   |
| 0x06006110 | 1         | 0.43%   |
| 0x06003106 | 1         | 0.43%   |
| 0x06000852 | 1         | 0.43%   |
| 0x010000dc | 1         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 41        | 17.9%   |
| Zen 2           | 27        | 11.79%  |
| Zen+            | 19        | 8.3%    |
| Haswell         | 19        | 8.3%    |
| Zen 3           | 16        | 6.99%   |
| IvyBridge       | 16        | 6.99%   |
| CometLake       | 14        | 6.11%   |
| SandyBridge     | 12        | 5.24%   |
| Skylake         | 10        | 4.37%   |
| Zen             | 8         | 3.49%   |
| Penryn          | 5         | 2.18%   |
| TigerLake       | 4         | 1.75%   |
| Broadwell       | 4         | 1.75%   |
| Unknown         | 4         | 1.75%   |
| Silvermont      | 3         | 1.31%   |
| Puma            | 3         | 1.31%   |
| Piledriver      | 3         | 1.31%   |
| Nehalem         | 3         | 1.31%   |
| K10             | 3         | 1.31%   |
| Goldmont plus   | 3         | 1.31%   |
| Excavator       | 3         | 1.31%   |
| Westmere        | 2         | 0.87%   |
| Steamroller     | 2         | 0.87%   |
| IceLake         | 2         | 0.87%   |
| K8 & K10 hybrid | 1         | 0.44%   |
| Jaguar          | 1         | 0.44%   |
| Goldmont        | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 110       | 37.04%  |
| Intel  | 105       | 35.35%  |
| AMD    | 82        | 27.61%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 13        | 4.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 3.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 3.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 2.94%   |
| AMD Cezanne                                                                              | 9         | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 2.61%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 2.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 2.29%   |
| Intel HD Graphics 630                                                                    | 7         | 2.29%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 2.29%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 1.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 1.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.63%   |
| Intel HD Graphics 620                                                                    | 5         | 1.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.63%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 1.31%   |
| Nvidia TU117M                                                                            | 4         | 1.31%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 1.31%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 4         | 1.31%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 4         | 1.31%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 1.31%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 3         | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.98%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3         | 0.98%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3         | 0.98%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.98%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3         | 0.98%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2         | 0.65%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.65%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2         | 0.65%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 0.65%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.65%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 2         | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.65%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 2         | 0.65%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2         | 0.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.65%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.65%   |
| Intel HD Graphics 530                                                                    | 2         | 0.65%   |
| Intel HD Graphics 510                                                                    | 2         | 0.65%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.65%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.65%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2         | 0.65%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 2         | 0.65%   |
| AMD Lucienne                                                                             | 2         | 0.65%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.33%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.33%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 57        | 24.89%  |
| 1 x Intel          | 56        | 24.45%  |
| 1 x Nvidia         | 50        | 21.83%  |
| Intel + Nvidia     | 37        | 16.16%  |
| AMD + Nvidia       | 19        | 8.3%    |
| Intel + AMD        | 4         | 1.75%   |
| 2 x Nvidia         | 2         | 0.87%   |
| 2 x AMD            | 2         | 0.87%   |
| Intel + 2 x Nvidia | 2         | 0.87%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 143       | 61.9%   |
| Proprietary | 88        | 38.1%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 122       | 52.14%  |
| 0.01-0.5   | 27        | 11.54%  |
| 1.01-2.0   | 21        | 8.97%   |
| 7.01-8.0   | 20        | 8.55%   |
| 3.01-4.0   | 16        | 6.84%   |
| 5.01-6.0   | 11        | 4.7%    |
| 0.51-1.0   | 9         | 3.85%   |
| 8.01-16.0  | 5         | 2.14%   |
| 2.01-3.0   | 2         | 0.85%   |
| 16.01-24.0 | 1         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 32        | 11.35%  |
| AU Optronics            | 32        | 11.35%  |
| LG Display              | 23        | 8.16%   |
| BOE                     | 20        | 7.09%   |
| Chimei Innolux          | 19        | 6.74%   |
| Dell                    | 18        | 6.38%   |
| Acer                    | 15        | 5.32%   |
| Goldstar                | 14        | 4.96%   |
| AOC                     | 12        | 4.26%   |
| Hewlett-Packard         | 10        | 3.55%   |
| Sharp                   | 8         | 2.84%   |
| BenQ                    | 8         | 2.84%   |
| Ancor Communications    | 8         | 2.84%   |
| PANDA                   | 7         | 2.48%   |
| Unknown                 | 6         | 2.13%   |
| Lenovo                  | 5         | 1.77%   |
| ASUSTek Computer        | 5         | 1.77%   |
| Sony                    | 3         | 1.06%   |
| MSI                     | 3         | 1.06%   |
| Gigabyte Technology     | 3         | 1.06%   |
| Apple                   | 3         | 1.06%   |
| Vizio                   | 2         | 0.71%   |
| Philips                 | 2         | 0.71%   |
| Mi                      | 2         | 0.71%   |
| Iiyama                  | 2         | 0.71%   |
| CSO                     | 2         | 0.71%   |
| ONN                     | 1         | 0.35%   |
| MStar                   | 1         | 0.35%   |
| MiTAC                   | 1         | 0.35%   |
| LTM                     | 1         | 0.35%   |
| LG Electronics          | 1         | 0.35%   |
| Lenovo Group Limited    | 1         | 0.35%   |
| Insignia                | 1         | 0.35%   |
| InfoVision              | 1         | 0.35%   |
| HPN                     | 1         | 0.35%   |
| HKC                     | 1         | 0.35%   |
| G-Story                 | 1         | 0.35%   |
| Fujitsu Siemens         | 1         | 0.35%   |
| Element                 | 1         | 0.35%   |
| Eizo                    | 1         | 0.35%   |
| CPT                     | 1         | 0.35%   |
| Chi Mei Optoelectronics | 1         | 0.35%   |
| AOpen                   | 1         | 0.35%   |
| Alba                    | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 4         | 1.37%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3         | 1.02%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 2         | 0.68%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch   | 2         | 0.68%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.68%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 2         | 0.68%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 2         | 0.68%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                | 2         | 0.68%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.68%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 0.68%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch       | 2         | 0.68%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                  | 2         | 0.68%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 2         | 0.68%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                  | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch         | 2         | 0.68%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2         | 0.68%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2         | 0.68%   |
| Acer XB271HU ACR0490 2560x1440 598x336mm 27.0-inch                     | 2         | 0.68%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2         | 0.68%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1         | 0.34%   |
| Vizio E320-B2 VIZ0095 1360x768 700x400mm 31.7-inch                     | 1         | 0.34%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1         | 0.34%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1         | 0.34%   |
| Unknown LCD Monitor SAMSUNG                                            | 1         | 0.34%   |
| Unknown LCD Monitor RJT HDMI                                           | 1         | 0.34%   |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1         | 0.34%   |
| Unknown LCD Monitor Hitachi/HINT W240D DVI                             | 1         | 0.34%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.34%   |
| Sony TV SNY1802 1920x1080                                              | 1         | 0.34%   |
| Sony TV SNY0801 1360x768                                               | 1         | 0.34%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch                | 1         | 0.34%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.34%   |
| Sharp LQ133T1JW17 SHP1409 2560x1440 294x165mm 13.3-inch                | 1         | 0.34%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.34%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.34%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.34%   |
| Samsung Electronics U28E850 SAM0CCB 3840x2160 607x345mm 27.5-inch      | 1         | 0.34%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 1         | 0.34%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 1         | 0.34%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch      | 1         | 0.34%   |
| Samsung Electronics SyncMaster SAM04D5 1920x540                        | 1         | 0.34%   |
| Samsung Electronics SyncMaster SAM00BB 1280x1024 376x301mm 19.0-inch   | 1         | 0.34%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch    | 1         | 0.34%   |
| Samsung Electronics S24E450 SAM0CA0 1920x1080 531x299mm 24.0-inch      | 1         | 0.34%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch      | 1         | 0.34%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SyncMaster 3840x1080                   | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch   | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch   | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SAM0FBE 3840x2160 950x540mm 43.0-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 135       | 50.37%  |
| 1366x768 (WXGA)    | 25        | 9.33%   |
| 3840x2160 (4K)     | 21        | 7.84%   |
| 2560x1440 (QHD)    | 12        | 4.48%   |
| 1600x900 (HD+)     | 12        | 4.48%   |
| Unknown            | 9         | 3.36%   |
| 1680x1050 (WSXGA+) | 7         | 2.61%   |
| 3840x1080          | 5         | 1.87%   |
| 3440x1440          | 5         | 1.87%   |
| 2560x1080          | 4         | 1.49%   |
| 1920x1200 (WUXGA)  | 4         | 1.49%   |
| 1440x900 (WXGA+)   | 4         | 1.49%   |
| 2560x1600          | 3         | 1.12%   |
| 7680x2160          | 2         | 0.75%   |
| 2256x1504          | 2         | 0.75%   |
| 1360x768           | 2         | 0.75%   |
| 1280x800 (WXGA)    | 2         | 0.75%   |
| 1280x1024 (SXGA)   | 2         | 0.75%   |
| 9600x2160          | 1         | 0.37%   |
| 4480x1440          | 1         | 0.37%   |
| 3840x2400          | 1         | 0.37%   |
| 3840x1200          | 1         | 0.37%   |
| 3200x1800 (QHD+)   | 1         | 0.37%   |
| 2880x1440          | 1         | 0.37%   |
| 2160x1440          | 1         | 0.37%   |
| 2048x1152          | 1         | 0.37%   |
| 1920x540           | 1         | 0.37%   |
| 1680x945           | 1         | 0.37%   |
| 1600x1200          | 1         | 0.37%   |
| 1024x768 (XGA)     | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 75        | 27.57%  |
| 27      | 31        | 11.4%   |
| Unknown | 22        | 8.09%   |
| 24      | 20        | 7.35%   |
| 23      | 18        | 6.62%   |
| 14      | 16        | 5.88%   |
| 13      | 16        | 5.88%   |
| 17      | 11        | 4.04%   |
| 22      | 7         | 2.57%   |
| 21      | 7         | 2.57%   |
| 34      | 6         | 2.21%   |
| 19      | 6         | 2.21%   |
| 31      | 5         | 1.84%   |
| 72      | 4         | 1.47%   |
| 20      | 4         | 1.47%   |
| 16      | 4         | 1.47%   |
| 49      | 3         | 1.1%    |
| 18      | 3         | 1.1%    |
| 54      | 2         | 0.74%   |
| 40      | 2         | 0.74%   |
| 28      | 2         | 0.74%   |
| 52      | 1         | 0.37%   |
| 48      | 1         | 0.37%   |
| 43      | 1         | 0.37%   |
| 39      | 1         | 0.37%   |
| 33      | 1         | 0.37%   |
| 25      | 1         | 0.37%   |
| 12      | 1         | 0.37%   |
| 11      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 100       | 37.59%  |
| 501-600     | 60        | 22.56%  |
| 401-500     | 25        | 9.4%    |
| Unknown     | 22        | 8.27%   |
| 351-400     | 13        | 4.89%   |
| 601-700     | 12        | 4.51%   |
| 201-300     | 12        | 4.51%   |
| 701-800     | 7         | 2.63%   |
| 1001-1500   | 7         | 2.63%   |
| 1501-2000   | 4         | 1.5%    |
| 801-900     | 3         | 1.13%   |
| 901-1000    | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 186       | 75.3%   |
| 16/10   | 25        | 10.12%  |
| Unknown | 19        | 7.69%   |
| 21/9    | 7         | 2.83%   |
| 32/9    | 3         | 1.21%   |
| 3/2     | 3         | 1.21%   |
| 5/4     | 2         | 0.81%   |
| 4/3     | 1         | 0.4%    |
| 2.00    | 1         | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 76        | 28.46%  |
| 201-250        | 40        | 14.98%  |
| 301-350        | 31        | 11.61%  |
| 81-90          | 26        | 9.74%   |
| Unknown        | 22        | 8.24%   |
| 351-500        | 13        | 4.87%   |
| 151-200        | 11        | 4.12%   |
| 121-130        | 10        | 3.75%   |
| More than 1000 | 9         | 3.37%   |
| 251-300        | 8         | 3%      |
| 71-80          | 6         | 2.25%   |
| 501-1000       | 6         | 2.25%   |
| 141-150        | 4         | 1.5%    |
| 111-120        | 2         | 0.75%   |
| 61-70          | 1         | 0.37%   |
| 51-60          | 1         | 0.37%   |
| 91-100         | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 85        | 33.2%   |
| 51-100        | 76        | 29.69%  |
| 101-120       | 47        | 18.36%  |
| Unknown       | 22        | 8.59%   |
| 161-240       | 12        | 4.69%   |
| 1-50          | 9         | 3.52%   |
| More than 240 | 5         | 1.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 162       | 70.13%  |
| 2     | 58        | 25.11%  |
| 3     | 9         | 3.9%    |
| 0     | 2         | 0.87%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 136       | 37.26%  |
| Intel                             | 120       | 32.88%  |
| Qualcomm Atheros                  | 41        | 11.23%  |
| Broadcom                          | 15        | 4.11%   |
| Ralink Technology                 | 5         | 1.37%   |
| NetGear                           | 5         | 1.37%   |
| MediaTek                          | 5         | 1.37%   |
| TP-Link                           | 3         | 0.82%   |
| Samsung Electronics               | 3         | 0.82%   |
| Microsoft                         | 3         | 0.82%   |
| Linksys                           | 3         | 0.82%   |
| Aquantia                          | 3         | 0.82%   |
| Ralink                            | 2         | 0.55%   |
| Qualcomm                          | 2         | 0.55%   |
| DisplayLink                       | 2         | 0.55%   |
| ASIX Electronics                  | 2         | 0.55%   |
| Xiaomi                            | 1         | 0.27%   |
| Wacom                             | 1         | 0.27%   |
| Sierra Wireless                   | 1         | 0.27%   |
| OnePlus                           | 1         | 0.27%   |
| Nvidia                            | 1         | 0.27%   |
| Lenovo                            | 1         | 0.27%   |
| InterBiometrics                   | 1         | 0.27%   |
| Holtek Semiconductor              | 1         | 0.27%   |
| Ericsson Business Mobile Networks | 1         | 0.27%   |
| Dell                              | 1         | 0.27%   |
| Broadcom Limited                  | 1         | 0.27%   |
| Belkin Components                 | 1         | 0.27%   |
| ASUSTek Computer                  | 1         | 0.27%   |
| Alteon Networks                   | 1         | 0.27%   |
| Accton Technology                 | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 99        | 23.4%   |
| Intel Wi-Fi 6 AX200                                                 | 22        | 5.2%    |
| Intel I211 Gigabit Network Connection                               | 12        | 2.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 11        | 2.6%    |
| Intel Comet Lake PCH CNVi WiFi                                      | 9         | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 9         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 8         | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 8         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 8         | 1.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 7         | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                   | 7         | 1.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 7         | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 6         | 1.42%   |
| Intel Ethernet Controller I225-V                                    | 6         | 1.42%   |
| Intel Ethernet Connection I217-LM                                   | 6         | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6         | 1.42%   |
| Intel Wireless-AC 9260                                              | 5         | 1.18%   |
| Intel Wireless 8265 / 8275                                          | 5         | 1.18%   |
| Intel Wireless 3165                                                 | 5         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 5         | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 4         | 0.95%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 4         | 0.95%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 4         | 0.95%   |
| Intel Wireless 7265                                                 | 4         | 0.95%   |
| Intel Wireless 7260                                                 | 4         | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3         | 0.71%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 3         | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3         | 0.71%   |
| Intel Wireless 8260                                                 | 3         | 0.71%   |
| Intel Ethernet Connection I219-LM                                   | 3         | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 3         | 0.71%   |
| Intel Centrino Advanced-N 6200                                      | 3         | 0.71%   |
| Intel 82577LM Gigabit Network Connection                            | 3         | 0.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 2         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 2         | 0.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 2         | 0.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 2         | 0.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2         | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 2         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2         | 0.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2         | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2         | 0.47%   |
| NetGear A6210                                                       | 2         | 0.47%   |
| Microsoft XBOX ACC                                                  | 2         | 0.47%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter       | 2         | 0.47%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2         | 0.47%   |
| Intel Wi-Fi 6 AX201                                                 | 2         | 0.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 2         | 0.47%   |
| Intel Ethernet Connection (4) I219-LM                               | 2         | 0.47%   |
| Intel Ethernet Connection (2) I219-V                                | 2         | 0.47%   |
| Intel Centrino Ultimate-N 6300                                      | 2         | 0.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 0.47%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 2         | 0.47%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express              | 2         | 0.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 2         | 0.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                 | 2         | 0.47%   |
| ASIX AX88179 Gigabit Ethernet                                       | 2         | 0.47%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2         | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1         | 0.24%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 96        | 47.76%  |
| Realtek Semiconductor | 35        | 17.41%  |
| Qualcomm Atheros      | 29        | 14.43%  |
| Broadcom              | 11        | 5.47%   |
| Ralink Technology     | 5         | 2.49%   |
| NetGear               | 5         | 2.49%   |
| TP-Link               | 3         | 1.49%   |
| Microsoft             | 3         | 1.49%   |
| MediaTek              | 3         | 1.49%   |
| Linksys               | 3         | 1.49%   |
| Ralink                | 2         | 1%      |
| Wacom                 | 1         | 0.5%    |
| Sierra Wireless       | 1         | 0.5%    |
| Dell                  | 1         | 0.5%    |
| Broadcom Limited      | 1         | 0.5%    |
| ASUSTek Computer      | 1         | 0.5%    |
| Accton Technology     | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 22        | 10.89%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 11        | 5.45%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 9         | 4.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 8         | 3.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 8         | 3.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 8         | 3.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 7         | 3.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 6         | 2.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 6         | 2.97%   |
| Intel Wireless-AC 9260                                                    | 5         | 2.48%   |
| Intel Wireless 8265 / 8275                                                | 5         | 2.48%   |
| Intel Wireless 3165                                                       | 5         | 2.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 5         | 2.48%   |
| Intel Wireless 7265                                                       | 4         | 1.98%   |
| Intel Wireless 7260                                                       | 4         | 1.98%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3         | 1.49%   |
| Intel Wireless 8260                                                       | 3         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 3         | 1.49%   |
| Intel Centrino Advanced-N 6200                                            | 3         | 1.49%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 2         | 0.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 2         | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 2         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 0.99%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                  | 2         | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 2         | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 2         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 0.99%   |
| NetGear A6210                                                             | 2         | 0.99%   |
| Microsoft XBOX ACC                                                        | 2         | 0.99%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter             | 2         | 0.99%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]       | 2         | 0.99%   |
| Intel Wi-Fi 6 AX201                                                       | 2         | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 2         | 0.99%   |
| Intel Centrino Ultimate-N 6300                                            | 2         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 2         | 0.99%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 2         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                       | 2         | 0.99%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                  | 1         | 0.5%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1         | 0.5%    |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                       | 1         | 0.5%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1         | 0.5%    |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 0.5%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1         | 0.5%    |
| Realtek RTL8191SEvB Wireless LAN Controller                               | 1         | 0.5%    |
| Realtek RTL8191SEvA Wireless LAN Controller                               | 1         | 0.5%    |
| Realtek RTL8188RU 802.11n WLAN Adapter                                    | 1         | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1         | 0.5%    |
| Realtek 802.11n WLAN Adapter                                              | 1         | 0.5%    |
| Ralink Wireless Adapter Canyon CN-WF511                                   | 1         | 0.5%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                         | 1         | 0.5%    |
| Ralink MT7601U Wireless Adapter                                           | 1         | 0.5%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1         | 0.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 0.5%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1         | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 0.5%    |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1         | 0.5%    |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.5%    |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]               | 1         | 0.5%    |
| Microsoft Wireless XBox Controller Dongle                                 | 1         | 0.5%    |
| MediaTek WiFi                                                             | 1         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 121       | 56.28%  |
| Intel                 | 51        | 23.72%  |
| Qualcomm Atheros      | 17        | 7.91%   |
| Broadcom              | 7         | 3.26%   |
| Samsung Electronics   | 3         | 1.4%    |
| Aquantia              | 3         | 1.4%    |
| Qualcomm              | 2         | 0.93%   |
| MediaTek              | 2         | 0.93%   |
| DisplayLink           | 2         | 0.93%   |
| ASIX Electronics      | 2         | 0.93%   |
| Xiaomi                | 1         | 0.47%   |
| Nvidia                | 1         | 0.47%   |
| Lenovo                | 1         | 0.47%   |
| Belkin Components     | 1         | 0.47%   |
| Alteon Networks       | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 99        | 45.62%  |
| Intel I211 Gigabit Network Connection                               | 12        | 5.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 9         | 4.15%   |
| Realtek RTL8125 2.5GbE Controller                                   | 7         | 3.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 7         | 3.23%   |
| Intel Ethernet Controller I225-V                                    | 6         | 2.76%   |
| Intel Ethernet Connection I217-LM                                   | 6         | 2.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 4         | 1.84%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 4         | 1.84%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 4         | 1.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 3         | 1.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3         | 1.38%   |
| Intel Ethernet Connection I219-LM                                   | 3         | 1.38%   |
| Intel 82577LM Gigabit Network Connection                            | 3         | 1.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 2         | 0.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2         | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                               | 2         | 0.92%   |
| Intel Ethernet Connection (2) I219-V                                | 2         | 0.92%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 2         | 0.92%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express              | 2         | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                       | 2         | 0.92%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2         | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1         | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1         | 0.46%   |
| Realtek Killer E3000 2.5GbE Controller                              | 1         | 0.46%   |
| Qualcomm Mobile Router                                              | 1         | 0.46%   |
| Qualcomm Mi A1                                                      | 1         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                              | 1         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1         | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1         | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1         | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1         | 0.46%   |
| Nvidia MCP79 Ethernet                                               | 1         | 0.46%   |
| MediaTek WP7                                                        | 1         | 0.46%   |
| MediaTek NOA N2                                                     | 1         | 0.46%   |
| Lenovo ThinkPad Lan                                                 | 1         | 0.46%   |
| Intel Ethernet Connection I217-V                                    | 1         | 0.46%   |
| Intel Ethernet Connection (7) I219-V                                | 1         | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                               | 1         | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                               | 1         | 0.46%   |
| Intel Ethernet Connection (3) I218-LM                               | 1         | 0.46%   |
| Intel Ethernet Connection (2) I218-V                                | 1         | 0.46%   |
| Intel Ethernet Connection (10) I219-V                               | 1         | 0.46%   |
| Intel 82579V Gigabit Network Connection                             | 1         | 0.46%   |
| DisplayLink ThinkPad USB 3.0 Dock                                   | 1         | 0.46%   |
| DisplayLink Dell D1000 USB3.0 Dock                                  | 1         | 0.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                   | 1         | 0.46%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express             | 1         | 0.46%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                     | 1         | 0.46%   |
| Belkin Components F5D5050 100Mbps Ethernet                          | 1         | 0.46%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.46%   |
| Alteon Networks Ethernet controller                                 | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 196       | 50.78%  |
| WiFi     | 186       | 48.19%  |
| Modem    | 2         | 0.52%   |
| Unknown  | 2         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 144       | 54.96%  |
| Ethernet | 117       | 44.66%  |
| Unknown  | 1         | 0.38%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 129       | 56.09%  |
| 1     | 90        | 39.13%  |
| 3     | 7         | 3.04%   |
| 0     | 3         | 1.3%    |
| 4     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 182       | 78.79%  |
| Yes  | 49        | 21.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 81        | 49.09%  |
| Qualcomm Atheros Communications | 23        | 13.94%  |
| Realtek Semiconductor           | 21        | 12.73%  |
| Cambridge Silicon Radio         | 8         | 4.85%   |
| IMC Networks                    | 6         | 3.64%   |
| Broadcom                        | 6         | 3.64%   |
| Lite-On Technology              | 4         | 2.42%   |
| Apple                           | 4         | 2.42%   |
| Foxconn / Hon Hai               | 3         | 1.82%   |
| ASUSTek Computer                | 3         | 1.82%   |
| Hewlett-Packard                 | 2         | 1.21%   |
| Dell                            | 2         | 1.21%   |
| Realtek                         | 1         | 0.61%   |
| Dynex                           | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                               | 22        | 13.33%  |
| Intel Bluetooth wireless interface                                                  | 16        | 9.7%    |
| Intel Bluetooth Device                                                              | 13        | 7.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 12        | 7.27%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 11        | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 6.67%   |
| Realtek Bluetooth Radio                                                             | 8         | 4.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 4.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 3.64%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 3.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 5         | 3.03%   |
| Intel AX210 Bluetooth                                                               | 4         | 2.42%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.21%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.21%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.21%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.21%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.21%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.21%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.21%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.21%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.21%   |
| ASUS Bluetooth Radio                                                                | 2         | 1.21%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.61%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.61%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.61%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.61%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.61%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.61%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.61%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.61%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.61%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.61%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.61%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.61%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.61%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 140       | 38.36%  |
| AMD                       | 96        | 26.3%   |
| Nvidia                    | 78        | 21.37%  |
| C-Media Electronics       | 9         | 2.47%   |
| Logitech                  | 6         | 1.64%   |
| Sony                      | 2         | 0.55%   |
| Sennheiser Communications | 2         | 0.55%   |
| RODE Microphones          | 2         | 0.55%   |
| Kingston Technology       | 2         | 0.55%   |
| JMTek                     | 2         | 0.55%   |
| Generalplus Technology    | 2         | 0.55%   |
| Creative Technology       | 2         | 0.55%   |
| Creative Labs             | 2         | 0.55%   |
| Corsair                   | 2         | 0.55%   |
| Blue Microphones          | 2         | 0.55%   |
| Yamaha                    | 1         | 0.27%   |
| Turtle Beach              | 1         | 0.27%   |
| Trust                     | 1         | 0.27%   |
| Texas Instruments         | 1         | 0.27%   |
| Tenx Technology           | 1         | 0.27%   |
| SteelSeries ApS           | 1         | 0.27%   |
| Realtek Semiconductor     | 1         | 0.27%   |
| Plantronics               | 1         | 0.27%   |
| Phison Electronics        | 1         | 0.27%   |
| Huawei Technologies       | 1         | 0.27%   |
| Hewlett-Packard           | 1         | 0.27%   |
| GN Netcom                 | 1         | 0.27%   |
| Focusrite-Novation        | 1         | 0.27%   |
| EVGA                      | 1         | 0.27%   |
| DigiTech                  | 1         | 0.27%   |
| BR25                      | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 36        | 8.18%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 21        | 4.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 3.64%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 3.41%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 3.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 2.95%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 2.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 13        | 2.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.5%    |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 2.27%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 9         | 2.05%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 1.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8         | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.36%   |
| Nvidia TU104 HD Audio Controller                                                                  | 6         | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.36%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 6         | 1.36%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.36%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.36%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.36%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 6         | 1.36%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.36%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 1.14%   |
| C-Media Electronics USB Audio Device                                                              | 5         | 1.14%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.14%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.91%   |
| Nvidia Audio device                                                                               | 4         | 0.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 0.91%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                        | 4         | 0.91%   |
| AMD Navi 10 HDMI Audio                                                                            | 4         | 0.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.68%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 0.68%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 0.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.68%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.68%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 0.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.68%   |
| RODE Microphones RODE NT-USB                                                                      | 2         | 0.45%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 0.45%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Logitech G933 Wireless Headset Dongle                                                             | 2         | 0.45%   |
| JMTek USB PnP Audio Device                                                                        | 2         | 0.45%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 23.03%  |
| SK Hynix            | 27        | 15.17%  |
| Crucial             | 17        | 9.55%   |
| Micron Technology   | 16        | 8.99%   |
| G.Skill             | 15        | 8.43%   |
| Kingston            | 12        | 6.74%   |
| Corsair             | 11        | 6.18%   |
| Unknown             | 7         | 3.93%   |
| Patriot             | 6         | 3.37%   |
| Ramaxel Technology  | 5         | 2.81%   |
| A-DATA Technology   | 4         | 2.25%   |
| Team                | 3         | 1.69%   |
| Nanya Technology    | 3         | 1.69%   |
| Unknown (ABCD)      | 2         | 1.12%   |
| Smart               | 2         | 1.12%   |
| Transcend           | 1         | 0.56%   |
| TIMETEC             | 1         | 0.56%   |
| Elpida              | 1         | 0.56%   |
| CSX                 | 1         | 0.56%   |
| Avant               | 1         | 0.56%   |
| Apacer              | 1         | 0.56%   |
| 48spaces            | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 6         | 3.13%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 2.6%    |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 5         | 2.6%    |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 4         | 2.08%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.56%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 3         | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 1.56%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s            | 3         | 1.56%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 1.04%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 1.04%   |
| SK Hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s          | 2         | 1.04%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.04%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.04%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.04%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.04%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.04%   |
| Patriot RAM 2666 C16 Series 8GB DIMM DDR4 2667MT/s               | 2         | 1.04%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4096MB SODIMM DDR3 1600MT/s          | 2         | 1.04%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 2         | 1.04%   |
| Corsair RAM CMK32GX4M4B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.04%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                             | 1         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.52%   |
| Unknown RAM Module 1GB DIMM 1066MT/s                             | 1         | 0.52%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 0.52%   |
| Transcend RAM JM2666HSE-16G 16384MB SODIMM DDR4 2667MT/s         | 1         | 0.52%   |
| TIMETEC RAM SD3-1866 8GB SODIMM DDR3 1866MT/s                    | 1         | 0.52%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s               | 1         | 0.52%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s               | 1         | 0.52%   |
| Team RAM TEAMGROUP-SD4-2133 8GB SODIMM DDR4 2133MT/s             | 1         | 0.52%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s         | 1         | 0.52%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB DDR4 2667MT/s                   | 1         | 0.52%   |
| SK Hynix RAM Module 4GB Row Of Chips LPDDR3 1333MT/s             | 1         | 0.52%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT41GU6BFR8C-PB 8192MB DIMM DDR3 1600MT/s          | 1         | 0.52%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.52%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.52%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8192MB Row Of Chips DDR4 2667MT/s  | 1         | 0.52%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4096MB SODIMM DDR4 3200MT/s        | 1         | 0.52%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s     | 1         | 0.52%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.52%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.52%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.52%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                        | 1         | 0.52%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 0.52%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                       | 1         | 0.52%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 0.52%   |
| Samsung RAM M471B5273DH0-YH9 4GB SODIMM DDR3 1600MT/s            | 1         | 0.52%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 0.52%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 98        | 65.33%  |
| DDR3    | 40        | 26.67%  |
| LPDDR4  | 5         | 3.33%   |
| Unknown | 3         | 2%      |
| LPDDR3  | 2         | 1.33%   |
| DDR2    | 2         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 95        | 62.09%  |
| DIMM         | 47        | 30.72%  |
| Row Of Chips | 9         | 5.88%   |
| Chip         | 1         | 0.65%   |
| Unknown      | 1         | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 86        | 51.5%   |
| 4096  | 44        | 26.35%  |
| 16384 | 29        | 17.37%  |
| 2048  | 5         | 2.99%   |
| 32768 | 2         | 1.2%    |
| 1024  | 1         | 0.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 37        | 21.89%  |
| 2667  | 33        | 19.53%  |
| 1600  | 30        | 17.75%  |
| 2400  | 16        | 9.47%   |
| 3600  | 13        | 7.69%   |
| 3466  | 4         | 2.37%   |
| 2133  | 4         | 2.37%   |
| 4266  | 3         | 1.78%   |
| 3266  | 3         | 1.78%   |
| 2666  | 3         | 1.78%   |
| 1334  | 3         | 1.78%   |
| 1333  | 3         | 1.78%   |
| 3866  | 2         | 1.18%   |
| 1867  | 2         | 1.18%   |
| 1866  | 2         | 1.18%   |
| 1800  | 2         | 1.18%   |
| 800   | 2         | 1.18%   |
| 4200  | 1         | 0.59%   |
| 4000  | 1         | 0.59%   |
| 3067  | 1         | 0.59%   |
| 2933  | 1         | 0.59%   |
| 2200  | 1         | 0.59%   |
| 1066  | 1         | 0.59%   |
| 667   | 1         | 0.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 37.5%   |
| Samsung Electronics | 1         | 12.5%   |
| Kyocera             | 1         | 12.5%   |
| Fuji Xerox          | 1         | 12.5%   |
| Dymo-CoStar         | 1         | 12.5%   |
| Brother Industries  | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung M337x 387x 407x Series   | 1         | 12.5%   |
| Kyocera FS-1030D printer         | 1         | 12.5%   |
| HP OfficeJet Pro 8020 series     | 1         | 12.5%   |
| HP LaserJet 200 colorMFP M275nw  | 1         | 12.5%   |
| HP DeskJet Plus 4100 series      | 1         | 12.5%   |
| Fuji Xerox DocuPrint CM315/318 z | 1         | 12.5%   |
| Dymo-CoStar LabelWriter 450      | 1         | 12.5%   |
| Brother HL-5370DW series         | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 33        | 22.6%   |
| Logitech                               | 15        | 10.27%  |
| IMC Networks                           | 15        | 10.27%  |
| Realtek Semiconductor                  | 10        | 6.85%   |
| Microdia                               | 10        | 6.85%   |
| Acer                                   | 9         | 6.16%   |
| Quanta                                 | 8         | 5.48%   |
| Sunplus Innovation Technology          | 6         | 4.11%   |
| Microsoft                              | 6         | 4.11%   |
| Syntek                                 | 4         | 2.74%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.74%   |
| Apple                                  | 4         | 2.74%   |
| Suyin                                  | 3         | 2.05%   |
| Luxvisions Innotech Limited            | 3         | 2.05%   |
| Lite-On Technology                     | 3         | 2.05%   |
| Silicon Motion                         | 2         | 1.37%   |
| Jieli Technology                       | 2         | 1.37%   |
| Z-Star Microelectronics                | 1         | 0.68%   |
| WaveRider Communications               | 1         | 0.68%   |
| Sonix Technology                       | 1         | 0.68%   |
| Samsung Electronics                    | 1         | 0.68%   |
| Razer USA                              | 1         | 0.68%   |
| MacroSilicon                           | 1         | 0.68%   |
| Lenovo                                 | 1         | 0.68%   |
| Importek                               | 1         | 0.68%   |
| Genesys Logic                          | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 7         | 4.76%   |
| Microdia Integrated_Webcam_HD                       | 6         | 4.08%   |
| IMC Networks Integrated Camera                      | 6         | 4.08%   |
| Chicony Integrated Camera                           | 6         | 4.08%   |
| Chicony HD WebCam                                   | 5         | 3.4%    |
| Syntek Integrated Camera                            | 4         | 2.72%   |
| Chicony HD User Facing                              | 4         | 2.72%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 2.04%   |
| Lite-On HP Wide Vision HD Camera                    | 3         | 2.04%   |
| Acer HD Webcam                                      | 3         | 2.04%   |
| Quanta HP Wide Vision HD Camera                     | 2         | 1.36%   |
| Microsoft LifeCam HD-5000                           | 2         | 1.36%   |
| Microsoft LifeCam HD-3000                           | 2         | 1.36%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.36%   |
| Logitech Webcam C930e                               | 2         | 1.36%   |
| Logitech Webcam C270                                | 2         | 1.36%   |
| Logitech HD Webcam C910                             | 2         | 1.36%   |
| Logitech HD Pro Webcam C920                         | 2         | 1.36%   |
| Logitech C922 Pro Stream Webcam                     | 2         | 1.36%   |
| Logitech BRIO Ultra HD Webcam                       | 2         | 1.36%   |
| Jieli USB PHY 2.0                                   | 2         | 1.36%   |
| Chicony USB 2.0 Camera                              | 2         | 1.36%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 1.36%   |
| Chicony EasyCamera                                  | 2         | 1.36%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 1.36%   |
| Acer Integrated Camera                              | 2         | 1.36%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 0.68%   |
| WaveRider USB Live camera                           | 1         | 0.68%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.68%   |
| Suyin HP Integrated Webcam                          | 1         | 0.68%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.68%   |
| Sunplus MTD Camera                                  | 1         | 0.68%   |
| Sunplus Integrated Webcam                           | 1         | 0.68%   |
| Sunplus Integrated Camera                           | 1         | 0.68%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.68%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 0.68%   |
| Silicon Motion Web Camera                           | 1         | 0.68%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.68%   |
| Realtek USB Camera                                  | 1         | 0.68%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.68%   |
| Realtek Integrated Webcam                           | 1         | 0.68%   |
| Realtek HP "Truevision HD" laptop camera            | 1         | 0.68%   |
| Realtek HD WebCam                                   | 1         | 0.68%   |
| Realtek FULL HD 1080P Webcam                        | 1         | 0.68%   |
| Realtek FJ Camera                                   | 1         | 0.68%   |
| Realtek EasyCamera                                  | 1         | 0.68%   |
| Realtek Built-In Video Camera                       | 1         | 0.68%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 0.68%   |
| Razer USA Razer Kiyo Pro                            | 1         | 0.68%   |
| Quanta WEBCAM                                       | 1         | 0.68%   |
| Quanta USB2.0 VGA UVC WebCam                        | 1         | 0.68%   |
| Quanta USB HD Webcam                                | 1         | 0.68%   |
| Quanta HP True Vision HD Camera                     | 1         | 0.68%   |
| Quanta HD User Facing                               | 1         | 0.68%   |
| Quanta HD Camera                                    | 1         | 0.68%   |
| Microsoft Xbox NUI Camera                           | 1         | 0.68%   |
| Microsoft Modern Webcam                             | 1         | 0.68%   |
| Microdia Webcam Vitade AF                           | 1         | 0.68%   |
| Microdia PC Microscope camera                       | 1         | 0.68%   |
| Microdia Integrated Webcam HD                       | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 26.92%  |
| Synaptics                  | 6         | 23.08%  |
| Shenzhen Goodix Technology | 5         | 19.23%  |
| Elan Microelectronics      | 4         | 15.38%  |
| LighTuning Technology      | 2         | 7.69%   |
| AuthenTec                  | 2         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 3         | 11.54%  |
| Elan ELAN:ARM-M4                                  | 3         | 11.54%  |
| Validity Sensors Synaptics WBDI                   | 2         | 7.69%   |
| Unknown                                           | 2         | 7.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 3.85%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 3.85%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 3.85%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 3.85%   |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 3.85%   |
| Synaptics WBDI Device                             | 1         | 3.85%   |
| Synaptics  WBDI Fingerprint Reader - USB 052      | 1         | 3.85%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 3.85%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 3.85%   |
| Shenzhen Goodix FingerPrint                       | 1         | 3.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 3.85%   |
| Elan ELAN:Fingerprint                             | 1         | 3.85%   |
| AuthenTec AES2810                                 | 1         | 3.85%   |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 3.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 60%     |
| Upek        | 1         | 10%     |
| O2 Micro    | 1         | 10%     |
| Lenovo      | 1         | 10%     |
| Alcor Micro | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 30%     |
| Broadcom 5880                                                                | 2         | 20%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 111       | 47.64%  |
| 0     | 77        | 33.05%  |
| 2     | 38        | 16.31%  |
| 3     | 6         | 2.58%   |
| 4     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 129       | 61.72%  |
| Fingerprint reader       | 26        | 12.44%  |
| Net/wireless             | 13        | 6.22%   |
| Graphics card            | 12        | 5.74%   |
| Chipcard                 | 10        | 4.78%   |
| Net/ethernet             | 7         | 3.35%   |
| Camera                   | 4         | 1.91%   |
| Multimedia controller    | 3         | 1.44%   |
| Wireless                 | 1         | 0.48%   |
| Unassigned class         | 1         | 0.48%   |
| Storage                  | 1         | 0.48%   |
| Network                  | 1         | 0.48%   |
| Bluetooth                | 1         | 0.48%   |

