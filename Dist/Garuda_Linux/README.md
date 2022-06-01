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

Total: 349

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [959728c7eb](https://linux-hardware.org/?probe=959728c7eb) | May 29, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [cd40cf2e16](https://linux-hardware.org/?probe=cd40cf2e16) | May 28, 2022 |
| Dell          | Latitude E6420              | Notebook    | [425a9e4f0d](https://linux-hardware.org/?probe=425a9e4f0d) | May 26, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [a214740f99](https://linux-hardware.org/?probe=a214740f99) | May 25, 2022 |
| Dell          | Latitude E5450              | Notebook    | [7d23576abb](https://linux-hardware.org/?probe=7d23576abb) | May 23, 2022 |
| Dell          | Latitude E5450              | Notebook    | [f0c746ba9e](https://linux-hardware.org/?probe=f0c746ba9e) | May 23, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [36a8a2a0ee](https://linux-hardware.org/?probe=36a8a2a0ee) | May 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [914eca828e](https://linux-hardware.org/?probe=914eca828e) | May 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [c0c592bdd7](https://linux-hardware.org/?probe=c0c592bdd7) | May 22, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [114aa0b977](https://linux-hardware.org/?probe=114aa0b977) | May 22, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| Samsung       | 730QDA                      | Convertible | [c46de205cd](https://linux-hardware.org/?probe=c46de205cd) | May 17, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Razer         | Blade                       | Notebook    | [0e1cc80117](https://linux-hardware.org/?probe=0e1cc80117) | May 07, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [bd151331c1](https://linux-hardware.org/?probe=bd151331c1) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
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
| ASUSTek       | A68HM-PLUS                  | Desktop     | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a33f627737](https://linux-hardware.org/?probe=a33f627737) | Mar 30, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| MSI           | GS76 Stealth 11UG           | Notebook    | [d05ccc7f12](https://linux-hardware.org/?probe=d05ccc7f12) | Mar 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [066b026c69](https://linux-hardware.org/?probe=066b026c69) | Mar 28, 2022 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [df2ffaa70a](https://linux-hardware.org/?probe=df2ffaa70a) | Mar 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| Toshiba       | Satellite E45DW-C           | Notebook    | [2b815d9219](https://linux-hardware.org/?probe=2b815d9219) | Mar 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [94786f0b30](https://linux-hardware.org/?probe=94786f0b30) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b4c8253286](https://linux-hardware.org/?probe=b4c8253286) | Feb 23, 2022 |
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
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
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
| MSI           | GP75 Leopard 9SD            | Notebook    | [6935c7fc83](https://linux-hardware.org/?probe=6935c7fc83) | Jan 17, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus X CODE          | Desktop     | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [10f53d4021](https://linux-hardware.org/?probe=10f53d4021) | Jan 09, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [a338d9f2d1](https://linux-hardware.org/?probe=a338d9f2d1) | Jan 08, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8a1167daea](https://linux-hardware.org/?probe=8a1167daea) | Jan 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [b75e231fb3](https://linux-hardware.org/?probe=b75e231fb3) | Jan 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1a4570a458](https://linux-hardware.org/?probe=1a4570a458) | Jan 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [34d2cd6d9c](https://linux-hardware.org/?probe=34d2cd6d9c) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [9ad04f3022](https://linux-hardware.org/?probe=9ad04f3022) | Jan 07, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [c4db605668](https://linux-hardware.org/?probe=c4db605668) | Jan 06, 2022 |
| Dell          | Precision M4500             | Notebook    | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| HP            | Pavilion 14                 | Notebook    | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| HP            | Pavilion Laptop 15z-eh10... | Notebook    | [29b9cb755b](https://linux-hardware.org/?probe=29b9cb755b) | Dec 25, 2021 |
| Dell          | G15 5515                    | Notebook    | [7e8108b3c2](https://linux-hardware.org/?probe=7e8108b3c2) | Dec 24, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [c7147f0bf8](https://linux-hardware.org/?probe=c7147f0bf8) | Dec 16, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [f8a99e7645](https://linux-hardware.org/?probe=f8a99e7645) | Dec 16, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9e73346fb8](https://linux-hardware.org/?probe=9e73346fb8) | Dec 15, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [c3144c3e22](https://linux-hardware.org/?probe=c3144c3e22) | Dec 13, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [196b460373](https://linux-hardware.org/?probe=196b460373) | Dec 13, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [df628cbd13](https://linux-hardware.org/?probe=df628cbd13) | Dec 12, 2021 |
| ASRock        | H77M-ITX                    | Desktop     | [5e98a2fce2](https://linux-hardware.org/?probe=5e98a2fce2) | Dec 11, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [e4fb1e4fe4](https://linux-hardware.org/?probe=e4fb1e4fe4) | Dec 09, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [731c890641](https://linux-hardware.org/?probe=731c890641) | Dec 08, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [a49a5a129c](https://linux-hardware.org/?probe=a49a5a129c) | Dec 07, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f499f9a375](https://linux-hardware.org/?probe=f499f9a375) | Dec 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f0df07c0e4](https://linux-hardware.org/?probe=f0df07c0e4) | Dec 06, 2021 |
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
| ASUSTek       | K53SD                       | Notebook    | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [fac556ebbe](https://linux-hardware.org/?probe=fac556ebbe) | Nov 24, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [63f386f998](https://linux-hardware.org/?probe=63f386f998) | Nov 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [bbb0689dea](https://linux-hardware.org/?probe=bbb0689dea) | Nov 21, 2021 |
| Dell          | Latitude E5570              | Notebook    | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [1ea5d23a86](https://linux-hardware.org/?probe=1ea5d23a86) | Nov 17, 2021 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [2713c3bae1](https://linux-hardware.org/?probe=2713c3bae1) | Nov 16, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [2c8fef35c1](https://linux-hardware.org/?probe=2c8fef35c1) | Nov 14, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f455ee4572](https://linux-hardware.org/?probe=f455ee4572) | Nov 14, 2021 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [d74b03de25](https://linux-hardware.org/?probe=d74b03de25) | Nov 13, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [6584d17e10](https://linux-hardware.org/?probe=6584d17e10) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ed9cd44b17](https://linux-hardware.org/?probe=ed9cd44b17) | Nov 08, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | Notebook    | [976bcf4121](https://linux-hardware.org/?probe=976bcf4121) | Nov 04, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [86f08832c0](https://linux-hardware.org/?probe=86f08832c0) | Oct 31, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| Panasonic     | CF-191HYAX1M                | Notebook    | [1aed5aedc2](https://linux-hardware.org/?probe=1aed5aedc2) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [dde814d7ca](https://linux-hardware.org/?probe=dde814d7ca) | Oct 25, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [5154b1932f](https://linux-hardware.org/?probe=5154b1932f) | Oct 24, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
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
| Notebook      | P7xxDM2(-G)                 | Notebook    | [284ab5f28e](https://linux-hardware.org/?probe=284ab5f28e) | Sep 28, 2021 |
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
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
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
| Dell          | System XPS L702X            | Notebook    | [e3af15a170](https://linux-hardware.org/?probe=e3af15a170) | Mar 09, 2021 |
| Dell          | System XPS L702X            | Notebook    | [7fb3f476cf](https://linux-hardware.org/?probe=7fb3f476cf) | Mar 09, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [3741826c9a](https://linux-hardware.org/?probe=3741826c9a) | Mar 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c1f22a7521](https://linux-hardware.org/?probe=c1f22a7521) | Mar 05, 2021 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [404dab2464](https://linux-hardware.org/?probe=404dab2464) | Feb 27, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [29784f5b45](https://linux-hardware.org/?probe=29784f5b45) | Feb 23, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [13f9fc2ef3](https://linux-hardware.org/?probe=13f9fc2ef3) | Feb 18, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [c7e8878f7b](https://linux-hardware.org/?probe=c7e8878f7b) | Feb 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2e19f3b1af](https://linux-hardware.org/?probe=2e19f3b1af) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4RC0... | Notebook    | [3e146ba45b](https://linux-hardware.org/?probe=3e146ba45b) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [de3199a457](https://linux-hardware.org/?probe=de3199a457) | Feb 17, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [f821a0035b](https://linux-hardware.org/?probe=f821a0035b) | Feb 12, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [b73941c431](https://linux-hardware.org/?probe=b73941c431) | Feb 08, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [92487a475d](https://linux-hardware.org/?probe=92487a475d) | Feb 06, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
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
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [3f895b585b](https://linux-hardware.org/?probe=3f895b585b) | Jan 22, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [61976e9745](https://linux-hardware.org/?probe=61976e9745) | Jan 18, 2021 |
| HP            | Compaq 6735b                | Notebook    | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [09f3ac6567](https://linux-hardware.org/?probe=09f3ac6567) | Jan 11, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [e392838a54](https://linux-hardware.org/?probe=e392838a54) | Jan 10, 2021 |
| ASUSTek       | CM5671                      | Desktop     | [069344a54e](https://linux-hardware.org/?probe=069344a54e) | Jan 07, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [a5612ca66a](https://linux-hardware.org/?probe=a5612ca66a) | Jan 07, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [8fe013f04a](https://linux-hardware.org/?probe=8fe013f04a) | Jan 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [2e0ef916c6](https://linux-hardware.org/?probe=2e0ef916c6) | Jan 03, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
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
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [4e573bc6ff](https://linux-hardware.org/?probe=4e573bc6ff) | Oct 28, 2020 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [4b9d2b77cb](https://linux-hardware.org/?probe=4b9d2b77cb) | Oct 26, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b7772d9ff8](https://linux-hardware.org/?probe=b7772d9ff8) | Oct 13, 2020 |
| Dell          | 0R6JMP A00                  | Desktop     | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| OEM           | Unknown                     | Desktop     | [2e7a212437](https://linux-hardware.org/?probe=2e7a212437) | Sep 26, 2020 |
| Lenovo        | ThinkCentre M91p 7033CG1    | Desktop     | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [4a3037422e](https://linux-hardware.org/?probe=4a3037422e) | Sep 04, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [7b8babe846](https://linux-hardware.org/?probe=7b8babe846) | Aug 27, 2020 |
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
| Garuda Linux Soaring | 152       | 62.3%   |
| Garuda Linux         | 87        | 35.66%  |
| Garuda Linux Rolling | 5         | 2.05%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Garuda Linux | 241       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.17.1-zen1-1-zen   | 9         | 3.26%   |
| 5.15.2-zen1-1-zen   | 7         | 2.54%   |
| 5.14.14-zen1-1-zen  | 7         | 2.54%   |
| 5.17.9-zen1-1-zen   | 6         | 2.17%   |
| 5.16.4-zen1-1-zen   | 6         | 2.17%   |
| 5.15.7-zen1-1-zen   | 5         | 1.81%   |
| 5.15.13-zen1-1-zen  | 5         | 1.81%   |
| 5.15.12-zen1-1-zen  | 5         | 1.81%   |
| 5.13.9-zen1-1-zen   | 5         | 1.81%   |
| 5.13.13-zen1-1-zen  | 5         | 1.81%   |
| 5.11.16-zen1-1-zen  | 5         | 1.81%   |
| 5.11.11-zen1-1-zen  | 5         | 1.81%   |
| 5.17.3-zen1-1-zen   | 4         | 1.45%   |
| 5.16.2-zen1-1-zen   | 4         | 1.45%   |
| 5.16.16-zen1-1-zen  | 4         | 1.45%   |
| 5.15.6-zen2-1-zen   | 4         | 1.45%   |
| 5.10.4-107-tkg-bmq  | 4         | 1.45%   |
| 5.10.1-103-tkg-bmq  | 4         | 1.45%   |
| 5.9.10-zen1-1-zen   | 3         | 1.09%   |
| 5.9.1-zen2-1-zen    | 3         | 1.09%   |
| 5.17.5-zen1-1-zen   | 3         | 1.09%   |
| 5.16.5-zen1-1-zen   | 3         | 1.09%   |
| 5.16.14-zen1-1-zen  | 3         | 1.09%   |
| 5.16.11-zen1-1-zen  | 3         | 1.09%   |
| 5.15.5-zen1-1-zen   | 3         | 1.09%   |
| 5.15.10-zen1-1-zen  | 3         | 1.09%   |
| 5.14.6-zen1-1-zen   | 3         | 1.09%   |
| 5.14.15-zen1-1-zen  | 3         | 1.09%   |
| 5.10.8-112-tkg-bmq  | 3         | 1.09%   |
| 5.10.2-104-tkg-bmq  | 3         | 1.09%   |
| 5.10.15-120-tkg-bmq | 3         | 1.09%   |
| 5.10.10-115-tkg-bmq | 3         | 1.09%   |
| 5.9.8-zen1-1-zen    | 2         | 0.72%   |
| 5.9.2-zen1-1-zen    | 2         | 0.72%   |
| 5.9.11-zen2-1-zen   | 2         | 0.72%   |
| 5.8.14-zen1-1-zen   | 2         | 0.72%   |
| 5.16.9-zen1-1-zen   | 2         | 0.72%   |
| 5.16.8-zen1-1-zen   | 2         | 0.72%   |
| 5.16.8-arch1-1      | 2         | 0.72%   |
| 5.16.10-zen1-1-zen  | 2         | 0.72%   |
| 5.16.1-zen1-1-zen   | 2         | 0.72%   |
| 5.16.0-zen1-1-zen   | 2         | 0.72%   |
| 5.15.4-zen1-1-zen   | 2         | 0.72%   |
| 5.14.9-zen2-1-zen   | 2         | 0.72%   |
| 5.14.12-zen1-1-zen  | 2         | 0.72%   |
| 5.13.5-zen1-1-zen   | 2         | 0.72%   |
| 5.13.12-zen1-1-zen  | 2         | 0.72%   |
| 5.12.9-zen1-1-zen   | 2         | 0.72%   |
| 5.12.7-zen1-1-zen   | 2         | 0.72%   |
| 5.12.4-zen1-2-zen   | 2         | 0.72%   |
| 5.12.2-153-tkg-bmq  | 2         | 0.72%   |
| 5.12.15-zen1-1-zen  | 2         | 0.72%   |
| 5.12.14-zen1-1-zen  | 2         | 0.72%   |
| 5.12.13-zen1-1-zen  | 2         | 0.72%   |
| 5.12.12-AMD-znver2  | 2         | 0.72%   |
| 5.11.6-zen1-1-zen   | 2         | 0.72%   |
| 5.10.7-111-tkg-bmq  | 2         | 0.72%   |
| 5.9.9-zen1-1-zen    | 1         | 0.36%   |
| 5.9.6-zen1-1-zen    | 1         | 0.36%   |
| 5.9.4-zen1-1-zen    | 1         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 11        | 3.99%   |
| 5.15.2  | 7         | 2.54%   |
| 5.14.14 | 7         | 2.54%   |
| 5.17.9  | 6         | 2.17%   |
| 5.17.5  | 6         | 2.17%   |
| 5.17.3  | 6         | 2.17%   |
| 5.16.4  | 6         | 2.17%   |
| 5.15.7  | 6         | 2.17%   |
| 5.11.11 | 6         | 2.17%   |
| 5.10.4  | 6         | 2.17%   |
| 5.16.5  | 5         | 1.81%   |
| 5.16.2  | 5         | 1.81%   |
| 5.15.13 | 5         | 1.81%   |
| 5.15.12 | 5         | 1.81%   |
| 5.13.9  | 5         | 1.81%   |
| 5.13.13 | 5         | 1.81%   |
| 5.11.16 | 5         | 1.81%   |
| 5.16.8  | 4         | 1.45%   |
| 5.16.16 | 4         | 1.45%   |
| 5.15.6  | 4         | 1.45%   |
| 5.15.5  | 4         | 1.45%   |
| 5.12.13 | 4         | 1.45%   |
| 5.10.15 | 4         | 1.45%   |
| 5.10.1  | 4         | 1.45%   |
| 5.9.10  | 3         | 1.09%   |
| 5.9.1   | 3         | 1.09%   |
| 5.16.14 | 3         | 1.09%   |
| 5.16.11 | 3         | 1.09%   |
| 5.16.10 | 3         | 1.09%   |
| 5.16.0  | 3         | 1.09%   |
| 5.15.10 | 3         | 1.09%   |
| 5.14.6  | 3         | 1.09%   |
| 5.14.15 | 3         | 1.09%   |
| 5.14.12 | 3         | 1.09%   |
| 5.12.9  | 3         | 1.09%   |
| 5.12.12 | 3         | 1.09%   |
| 5.11.6  | 3         | 1.09%   |
| 5.10.8  | 3         | 1.09%   |
| 5.10.2  | 3         | 1.09%   |
| 5.10.10 | 3         | 1.09%   |
| 5.9.8   | 2         | 0.72%   |
| 5.9.2   | 2         | 0.72%   |
| 5.9.11  | 2         | 0.72%   |
| 5.8.14  | 2         | 0.72%   |
| 5.16.9  | 2         | 0.72%   |
| 5.16.1  | 2         | 0.72%   |
| 5.15.4  | 2         | 0.72%   |
| 5.15.11 | 2         | 0.72%   |
| 5.14.9  | 2         | 0.72%   |
| 5.14.5  | 2         | 0.72%   |
| 5.14.11 | 2         | 0.72%   |
| 5.13.5  | 2         | 0.72%   |
| 5.13.4  | 2         | 0.72%   |
| 5.13.12 | 2         | 0.72%   |
| 5.12.7  | 2         | 0.72%   |
| 5.12.4  | 2         | 0.72%   |
| 5.12.2  | 2         | 0.72%   |
| 5.12.15 | 2         | 0.72%   |
| 5.12.14 | 2         | 0.72%   |
| 5.11.0  | 2         | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 44        | 16.6%   |
| 5.16    | 41        | 15.47%  |
| 5.10    | 36        | 13.58%  |
| 5.17    | 30        | 11.32%  |
| 5.14    | 26        | 9.81%   |
| 5.12    | 23        | 8.68%   |
| 5.11    | 23        | 8.68%   |
| 5.13    | 21        | 7.92%   |
| 5.9     | 13        | 4.91%   |
| 5.8     | 5         | 1.89%   |
| 5.6     | 1         | 0.38%   |
| 5.4     | 1         | 0.38%   |
| 5.18    | 1         | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 241       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KDE5              | 148       | 60.66%  |
| GNOME             | 35        | 14.34%  |
| KDE               | 34        | 13.93%  |
| XFCE              | 9         | 3.69%   |
| X-Cinnamon        | 4         | 1.64%   |
| sway              | 3         | 1.23%   |
| qtile-default     | 2         | 0.82%   |
| i3                | 2         | 0.82%   |
| Deepin            | 2         | 0.82%   |
| Yaru:ubuntu:GNOME | 1         | 0.41%   |
| MATE              | 1         | 0.41%   |
| LXQt              | 1         | 0.41%   |
| Budgie            | 1         | 0.41%   |
| Unknown           | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 227       | 93.8%   |
| Wayland | 12        | 4.96%   |
| Tty     | 2         | 0.83%   |
| Unknown | 1         | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 119       | 49.17%  |
| Unknown | 90        | 37.19%  |
| LightDM | 17        | 7.02%   |
| GDM     | 14        | 5.79%   |
| GREETD  | 2         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 119       | 48.97%  |
| en_GB   | 28        | 11.52%  |
| de_DE   | 18        | 7.41%   |
| en_IN   | 13        | 5.35%   |
| it_IT   | 7         | 2.88%   |
| pt_BR   | 5         | 2.06%   |
| es_ES   | 5         | 2.06%   |
| ru_RU   | 4         | 1.65%   |
| es_MX   | 4         | 1.65%   |
| en_CA   | 4         | 1.65%   |
| en_AU   | 4         | 1.65%   |
| pl_PL   | 3         | 1.23%   |
| nl_NL   | 3         | 1.23%   |
| sv_SE   | 2         | 0.82%   |
| fr_FR   | 2         | 0.82%   |
| fr_BE   | 2         | 0.82%   |
| fi_FI   | 2         | 0.82%   |
| es_VE   | 2         | 0.82%   |
| es_CO   | 2         | 0.82%   |
| en_ZA   | 2         | 0.82%   |
| tr_TR   | 1         | 0.41%   |
| sk_SK   | 1         | 0.41%   |
| nb_NO   | 1         | 0.41%   |
| ko_KR   | 1         | 0.41%   |
| iu_CA   | 1         | 0.41%   |
| es_EC   | 1         | 0.41%   |
| es_AR   | 1         | 0.41%   |
| en_DK   | 1         | 0.41%   |
| el_GR   | 1         | 0.41%   |
| de_AT   | 1         | 0.41%   |
| da_DK   | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 152       | 62.81%  |
| BIOS | 90        | 37.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 237       | 98.34%  |
| Ext4    | 2         | 0.83%   |
| Overlay | 1         | 0.41%   |
| F2fs    | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 142       | 58.68%  |
| Unknown | 87        | 35.95%  |
| MBR     | 13        | 5.37%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 209       | 86.01%  |
| Yes       | 34        | 13.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 165       | 67.9%   |
| Yes       | 78        | 32.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 41        | 17.01%  |
| Lenovo              | 39        | 16.18%  |
| Hewlett-Packard     | 32        | 13.28%  |
| Dell                | 26        | 10.79%  |
| MSI                 | 23        | 9.54%   |
| Gigabyte Technology | 17        | 7.05%   |
| Acer                | 14        | 5.81%   |
| ASRock              | 11        | 4.56%   |
| Apple               | 4         | 1.66%   |
| Samsung Electronics | 3         | 1.24%   |
| Notebook            | 3         | 1.24%   |
| Medion              | 3         | 1.24%   |
| Toshiba             | 2         | 0.83%   |
| Razer               | 2         | 0.83%   |
| Pegatron            | 2         | 0.83%   |
| HUAWEI              | 2         | 0.83%   |
| Fujitsu             | 2         | 0.83%   |
| Alienware           | 2         | 0.83%   |
| Unknown             | 2         | 0.83%   |
| Sony                | 1         | 0.41%   |
| PC Specialist       | 1         | 0.41%   |
| Panasonic           | 1         | 0.41%   |
| OEM                 | 1         | 0.41%   |
| HONOR               | 1         | 0.41%   |
| GPU Company         | 1         | 0.41%   |
| Google              | 1         | 0.41%   |
| Fujitsu Siemens     | 1         | 0.41%   |
| Chuwi               | 1         | 0.41%   |
| Casper              | 1         | 0.41%   |
| Biostar             | 1         | 0.41%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 4         | 1.66%   |
| Unknown                                    | 4         | 1.66%   |
| ASUS TUF Gaming X570-PLUS                  | 3         | 1.24%   |
| MSI MS-7C91                                | 2         | 0.83%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 0.83%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 0.83%   |
| Gigabyte AB350-Gaming 3                    | 2         | 0.83%   |
| Dell Inspiron 3668                         | 2         | 0.83%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 0.83%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 0.83%   |
| ASUS ROG Flow X13 GV301QH_GV301QH          | 2         | 0.83%   |
| ASUS All Series                            | 2         | 0.83%   |
| Acer Nitro AN515-44                        | 2         | 0.83%   |
| Toshiba Satellite E45DW-C                  | 1         | 0.41%   |
| Toshiba Satellite C55-A                    | 1         | 0.41%   |
| Sony VPCSB1C5E                             | 1         | 0.41%   |
| Samsung 730QDA                             | 1         | 0.41%   |
| Samsung 550XCJ/550XCR                      | 1         | 0.41%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.41%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.41%   |
| Razer Blade                                | 1         | 0.41%   |
| Pegatron p7-1030                           | 1         | 0.41%   |
| Pegatron h9-1301es                         | 1         | 0.41%   |
| PC Specialist GK5NPFO                      | 1         | 0.41%   |
| Panasonic CF-191HYAX1M                     | 1         | 0.41%   |
| Notebook W54_W550SU2                       | 1         | 0.41%   |
| Notebook P7xxDM2(-G)                       | 1         | 0.41%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 0.41%   |
| MSI MS-7C90                                | 1         | 0.41%   |
| MSI MS-7C83                                | 1         | 0.41%   |
| MSI MS-7C52                                | 1         | 0.41%   |
| MSI MS-7C09                                | 1         | 0.41%   |
| MSI MS-7B98                                | 1         | 0.41%   |
| MSI MS-7B86                                | 1         | 0.41%   |
| MSI MS-7B09                                | 1         | 0.41%   |
| MSI MS-7A78                                | 1         | 0.41%   |
| MSI MS-7A39                                | 1         | 0.41%   |
| MSI MS-7A32                                | 1         | 0.41%   |
| MSI MS-7818                                | 1         | 0.41%   |
| MSI MS-7816                                | 1         | 0.41%   |
| MSI MS-7758                                | 1         | 0.41%   |
| MSI GS76 Stealth 11UG                      | 1         | 0.41%   |
| MSI GP75 Leopard 9SD                       | 1         | 0.41%   |
| MSI GF63 Thin 9SC                          | 1         | 0.41%   |
| MSI GF63 Thin 10SC                         | 1         | 0.41%   |
| MSI GE75 Raider 9SE                        | 1         | 0.41%   |
| MSI GE72VR 6RF                             | 1         | 0.41%   |
| MSI GE63 Raider RGB 8RE                    | 1         | 0.41%   |
| MSI A320M-HDV R4.0                         | 1         | 0.41%   |
| Medion P861X                               | 1         | 0.41%   |
| Medion E7419 MD60025                       | 1         | 0.41%   |
| Medion Akoya P5238 F/C395                  | 1         | 0.41%   |
| Lenovo Z50-70 20354                        | 1         | 0.41%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 0.41%   |
| Lenovo ThinkStation S20 4105O1U            | 1         | 0.41%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB005WUS   | 1         | 0.41%   |
| Lenovo ThinkPad T530 24296KG               | 1         | 0.41%   |
| Lenovo ThinkPad T510 4384WB4               | 1         | 0.41%   |
| Lenovo ThinkPad T470s 20HGS0B900           | 1         | 0.41%   |
| Lenovo ThinkPad T470 20HD000RUS            | 1         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 12        | 4.98%   |
| Lenovo IdeaPad         | 11        | 4.56%   |
| Dell Inspiron          | 11        | 4.56%   |
| HP Pavilion            | 10        | 4.15%   |
| ASUS ROG               | 10        | 4.15%   |
| Dell Latitude          | 7         | 2.9%    |
| Acer Aspire            | 7         | 2.9%    |
| Lenovo Legion          | 6         | 2.49%   |
| ASUS PRIME             | 6         | 2.49%   |
| HP Laptop              | 5         | 2.07%   |
| ASUS TUF               | 5         | 2.07%   |
| Dell XPS               | 4         | 1.66%   |
| Acer Nitro             | 4         | 1.66%   |
| Unknown                | 4         | 1.66%   |
| Lenovo ThinkCentre     | 3         | 1.24%   |
| HP OMEN                | 3         | 1.24%   |
| Gigabyte B450          | 3         | 1.24%   |
| ASUS VivoBook          | 3         | 1.24%   |
| Toshiba Satellite      | 2         | 0.83%   |
| Razer Blade            | 2         | 0.83%   |
| MSI MS-7C91            | 2         | 0.83%   |
| MSI GF63               | 2         | 0.83%   |
| HP ENVY                | 2         | 0.83%   |
| HP EliteBook           | 2         | 0.83%   |
| Gigabyte X570          | 2         | 0.83%   |
| Gigabyte B550          | 2         | 0.83%   |
| Gigabyte AB350-Gaming  | 2         | 0.83%   |
| Dell OptiPlex          | 2         | 0.83%   |
| ASUS ASUS              | 2         | 0.83%   |
| ASUS All               | 2         | 0.83%   |
| ASRock X470            | 2         | 0.83%   |
| Sony VPCSB1C5E         | 1         | 0.41%   |
| Samsung 730QDA         | 1         | 0.41%   |
| Samsung 550XCJ         | 1         | 0.41%   |
| Samsung 300V3A         | 1         | 0.41%   |
| Pegatron p7-1030       | 1         | 0.41%   |
| Pegatron h9-1301es     | 1         | 0.41%   |
| PC Specialist GK5NPFO  | 1         | 0.41%   |
| Panasonic CF-191HYAX1M | 1         | 0.41%   |
| Notebook W54           | 1         | 0.41%   |
| Notebook P7xxDM2(-G)   | 1         | 0.41%   |
| Notebook N85           | 1         | 0.41%   |
| MSI MS-7C90            | 1         | 0.41%   |
| MSI MS-7C83            | 1         | 0.41%   |
| MSI MS-7C52            | 1         | 0.41%   |
| MSI MS-7C09            | 1         | 0.41%   |
| MSI MS-7B98            | 1         | 0.41%   |
| MSI MS-7B86            | 1         | 0.41%   |
| MSI MS-7B09            | 1         | 0.41%   |
| MSI MS-7A78            | 1         | 0.41%   |
| MSI MS-7A39            | 1         | 0.41%   |
| MSI MS-7A32            | 1         | 0.41%   |
| MSI MS-7818            | 1         | 0.41%   |
| MSI MS-7816            | 1         | 0.41%   |
| MSI MS-7758            | 1         | 0.41%   |
| MSI GS76               | 1         | 0.41%   |
| MSI GP75               | 1         | 0.41%   |
| MSI GE75               | 1         | 0.41%   |
| MSI GE72VR             | 1         | 0.41%   |
| MSI GE63               | 1         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 45        | 18.67%  |
| 2021 | 29        | 12.03%  |
| 2019 | 29        | 12.03%  |
| 2018 | 27        | 11.2%   |
| 2017 | 23        | 9.54%   |
| 2013 | 16        | 6.64%   |
| 2016 | 15        | 6.22%   |
| 2014 | 15        | 6.22%   |
| 2012 | 13        | 5.39%   |
| 2011 | 10        | 4.15%   |
| 2015 | 6         | 2.49%   |
| 2010 | 6         | 2.49%   |
| 2009 | 4         | 1.66%   |
| 2007 | 2         | 0.83%   |
| 2008 | 1         | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 133       | 55.19%  |
| Desktop     | 97        | 40.25%  |
| Convertible | 6         | 2.49%   |
| All in one  | 4         | 1.66%   |
| Mini pc     | 1         | 0.41%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 241       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 240       | 99.59%  |
| Yes  | 1         | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 67        | 27.57%  |
| 4.01-8.0    | 55        | 22.63%  |
| 8.01-16.0   | 52        | 21.4%   |
| 32.01-64.0  | 38        | 15.64%  |
| 3.01-4.0    | 14        | 5.76%   |
| 24.01-32.0  | 10        | 4.12%   |
| 64.01-256.0 | 6         | 2.47%   |
| 2.01-3.0    | 1         | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 96        | 37.21%  |
| 3.01-4.0   | 60        | 23.26%  |
| 2.01-3.0   | 54        | 20.93%  |
| 8.01-16.0  | 28        | 10.85%  |
| 1.01-2.0   | 13        | 5.04%   |
| 16.01-24.0 | 5         | 1.94%   |
| 32.01-64.0 | 1         | 0.39%   |
| 0.51-1.0   | 1         | 0.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 105       | 42.34%  |
| 2      | 72        | 29.03%  |
| 3      | 35        | 14.11%  |
| 4      | 19        | 7.66%   |
| 5      | 10        | 4.03%   |
| 9      | 3         | 1.21%   |
| 6      | 3         | 1.21%   |
| 14     | 1         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 74.69%  |
| Yes       | 62        | 25.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 203       | 83.88%  |
| No        | 39        | 16.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 199       | 81.22%  |
| No        | 46        | 18.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 176       | 72.13%  |
| No        | 68        | 27.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 74        | 30.58%  |
| Germany      | 25        | 10.33%  |
| UK           | 17        | 7.02%   |
| India        | 14        | 5.79%   |
| Italy        | 11        | 4.55%   |
| Canada       | 8         | 3.31%   |
| Brazil       | 6         | 2.48%   |
| Sweden       | 5         | 2.07%   |
| Spain        | 5         | 2.07%   |
| Russia       | 5         | 2.07%   |
| Romania      | 5         | 2.07%   |
| Poland       | 5         | 2.07%   |
| Netherlands  | 5         | 2.07%   |
| Mexico       | 5         | 2.07%   |
| France       | 4         | 1.65%   |
| Australia    | 4         | 1.65%   |
| Finland      | 3         | 1.24%   |
| Denmark      | 3         | 1.24%   |
| Belgium      | 3         | 1.24%   |
| Venezuela    | 2         | 0.83%   |
| Turkey       | 2         | 0.83%   |
| South Africa | 2         | 0.83%   |
| Puerto Rico  | 2         | 0.83%   |
| Latvia       | 2         | 0.83%   |
| Colombia     | 2         | 0.83%   |
| Switzerland  | 1         | 0.41%   |
| South Korea  | 1         | 0.41%   |
| Slovenia     | 1         | 0.41%   |
| Slovakia     | 1         | 0.41%   |
| Singapore    | 1         | 0.41%   |
| Serbia       | 1         | 0.41%   |
| Philippines  | 1         | 0.41%   |
| Oman         | 1         | 0.41%   |
| Norway       | 1         | 0.41%   |
| Luxembourg   | 1         | 0.41%   |
| Lithuania    | 1         | 0.41%   |
| Kuwait       | 1         | 0.41%   |
| Kenya        | 1         | 0.41%   |
| Iceland      | 1         | 0.41%   |
| Hungary      | 1         | 0.41%   |
| Greece       | 1         | 0.41%   |
| Ecuador      | 1         | 0.41%   |
| Czechia      | 1         | 0.41%   |
| China        | 1         | 0.41%   |
| Chile        | 1         | 0.41%   |
| Bahrain      | 1         | 0.41%   |
| Austria      | 1         | 0.41%   |
| Argentina    | 1         | 0.41%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| London                  | 4         | 1.59%   |
| San Jose                | 3         | 1.2%    |
| Portland                | 3         | 1.2%    |
| Chicago                 | 3         | 1.2%    |
| Berlin                  | 3         | 1.2%    |
| Wasmes                  | 2         | 0.8%    |
| Warsaw                  | 2         | 0.8%    |
| Toronto                 | 2         | 0.8%    |
| Timișoara              | 2         | 0.8%    |
| Sydney                  | 2         | 0.8%    |
| Riga                    | 2         | 0.8%    |
| Pune                    | 2         | 0.8%    |
| Puebla City             | 2         | 0.8%    |
| Oklahoma City           | 2         | 0.8%    |
| Milan                   | 2         | 0.8%    |
| Melbourne               | 2         | 0.8%    |
| Kingsport               | 2         | 0.8%    |
| Helsinki                | 2         | 0.8%    |
| Hamburg                 | 2         | 0.8%    |
| Düsseldorf             | 2         | 0.8%    |
| Delhi                   | 2         | 0.8%    |
| Copenhagen              | 2         | 0.8%    |
| Cape Town               | 2         | 0.8%    |
| Calenzano               | 2         | 0.8%    |
| Winston-Salem           | 1         | 0.4%    |
| Welwyn Garden City      | 1         | 0.4%    |
| Weiterstadt             | 1         | 0.4%    |
| Weilen unter den Rinnen | 1         | 0.4%    |
| Wasilla                 | 1         | 0.4%    |
| Voronezh                | 1         | 0.4%    |
| Volzhskiy               | 1         | 0.4%    |
| Visakhapatnam           | 1         | 0.4%    |
| Västerås              | 1         | 0.4%    |
| Vancouver               | 1         | 0.4%    |
| Valencia                | 1         | 0.4%    |
| Valence                 | 1         | 0.4%    |
| Urbandale               | 1         | 0.4%    |
| Ullerslev               | 1         | 0.4%    |
| Turku                   | 1         | 0.4%    |
| Turin                   | 1         | 0.4%    |
| Tucson                  | 1         | 0.4%    |
| Taunusstein             | 1         | 0.4%    |
| Sunrise Beach           | 1         | 0.4%    |
| Stockholm               | 1         | 0.4%    |
| Steenwijk               | 1         | 0.4%    |
| Stavropol               | 1         | 0.4%    |
| Stanley                 | 1         | 0.4%    |
| St Louis                | 1         | 0.4%    |
| Sparks                  | 1         | 0.4%    |
| Southampton             | 1         | 0.4%    |
| Singapore               | 1         | 0.4%    |
| Sindelfingen            | 1         | 0.4%    |
| Sighetu Marmaţiei      | 1         | 0.4%    |
| Shreveport              | 1         | 0.4%    |
| Seattle                 | 1         | 0.4%    |
| Satu Mare               | 1         | 0.4%    |
| Sarasota                | 1         | 0.4%    |
| Sao Paulo               | 1         | 0.4%    |
| Santa Cruz de Tenerife  | 1         | 0.4%    |
| Santa Clara             | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 79        | 139    | 17.59%  |
| Seagate                     | 69        | 96     | 15.37%  |
| WDC                         | 68        | 89     | 15.14%  |
| Toshiba                     | 28        | 32     | 6.24%   |
| SanDisk                     | 22        | 30     | 4.9%    |
| Crucial                     | 20        | 29     | 4.45%   |
| Kingston                    | 19        | 26     | 4.23%   |
| SK Hynix                    | 16        | 18     | 3.56%   |
| Unknown                     | 10        | 10     | 2.23%   |
| HGST                        | 10        | 10     | 2.23%   |
| Phison                      | 9         | 10     | 2%      |
| Intel                       | 9         | 11     | 2%      |
| Hitachi                     | 7         | 7      | 1.56%   |
| PNY                         | 6         | 6      | 1.34%   |
| SPCC                        | 5         | 5      | 1.11%   |
| Silicon Motion              | 5         | 5      | 1.11%   |
| Micron Technology           | 5         | 5      | 1.11%   |
| A-DATA Technology           | 5         | 8      | 1.11%   |
| KIOXIA                      | 4         | 5      | 0.89%   |
| Corsair                     | 4         | 7      | 0.89%   |
| China                       | 4         | 6      | 0.89%   |
| XPG                         | 3         | 4      | 0.67%   |
| LITEON                      | 3         | 3      | 0.67%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.45%   |
| Transcend                   | 2         | 2      | 0.45%   |
| Mushkin                     | 2         | 2      | 0.45%   |
| Micron/Crucial Technology   | 2         | 3      | 0.45%   |
| LITEONIT                    | 2         | 2      | 0.45%   |
| Intenso                     | 2         | 3      | 0.45%   |
| Yangtze Memory Technologies | 1         | 1      | 0.22%   |
| WDC WDS                     | 1         | 1      | 0.22%   |
| WD MediaMax                 | 1         | 1      | 0.22%   |
| VisionTek                   | 1         | 2      | 0.22%   |
| USB30                       | 1         | 2      | 0.22%   |
| UMIS                        | 1         | 1      | 0.22%   |
| TO Exter                    | 1         | 1      | 0.22%   |
| Team                        | 1         | 2      | 0.22%   |
| SSSTC                       | 1         | 1      | 0.22%   |
| ShanDianZhe                 | 1         | 1      | 0.22%   |
| SABRENT                     | 1         | 2      | 0.22%   |
| QUMO                        | 1         | 1      | 0.22%   |
| PNY CS90                    | 1         | 1      | 0.22%   |
| Phison Electronics          | 1         | 1      | 0.22%   |
| OCZ                         | 1         | 1      | 0.22%   |
| Netac                       | 1         | 1      | 0.22%   |
| Lenovo                      | 1         | 1      | 0.22%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.22%   |
| Inateck                     | 1         | 1      | 0.22%   |
| HS-SSD-E100                 | 1         | 1      | 0.22%   |
| FORESEE                     | 1         | 1      | 0.22%   |
| EMTEC                       | 1         | 1      | 0.22%   |
| ASMT                        | 1         | 1      | 0.22%   |
| ASMedia                     | 1         | 2      | 0.22%   |
| Apple                       | 1         | 1      | 0.22%   |
| Apacer                      | 1         | 1      | 0.22%   |
| Unknown                     | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB           | 10        | 1.98%   |
| Seagate ST1000LM035-1RK172 1TB       | 6         | 1.19%   |
| Samsung SSD 970 EVO Plus 500GB       | 6         | 1.19%   |
| Samsung SSD 860 EVO 500GB            | 6         | 1.19%   |
| Samsung SSD 850 EVO 250GB            | 6         | 1.19%   |
| Crucial CT1000MX500SSD1 1TB          | 6         | 1.19%   |
| Seagate ST2000DM008-2FR102 2TB       | 5         | 0.99%   |
| Seagate ST1000LM049-2GH172 1TB       | 5         | 0.99%   |
| Samsung SSD 860 EVO 1TB              | 5         | 0.99%   |
| Seagate ST1000DM010-2EP102 1TB       | 4         | 0.79%   |
| SanDisk SSD PLUS 1000GB              | 4         | 0.79%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 0.79%   |
| WDC WD10EZEX-60WN4A0 1TB             | 3         | 0.59%   |
| Toshiba MQ01ABD100 1TB               | 3         | 0.59%   |
| Toshiba DT01ACA100 1TB               | 3         | 0.59%   |
| SK Hynix NVMe SSD Drive 512GB        | 3         | 0.59%   |
| Seagate ST4000DM004-2CV104 4TB       | 3         | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.59%   |
| Seagate Portable 1TB                 | 3         | 0.59%   |
| Sandisk NVMe SSD Drive 500GB         | 3         | 0.59%   |
| Sandisk NVMe SSD Drive 1TB           | 3         | 0.59%   |
| Samsung SSD 970 EVO 250GB            | 3         | 0.59%   |
| Samsung SSD 870 EVO 500GB            | 3         | 0.59%   |
| Samsung NVMe SSD Drive 1024GB        | 3         | 0.59%   |
| PNY ELITE PSSD 480GB                 | 3         | 0.59%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 0.59%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.59%   |
| XPG NVMe SSD Drive 512GB             | 2         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB             | 2         | 0.4%    |
| WDC WD20EARX-00PASB0 2TB             | 2         | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.4%    |
| WDC WD10EZEX-00BN5A0 1TB             | 2         | 0.4%    |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 2         | 0.4%    |
| Unknown MMC Card  16GB               | 2         | 0.4%    |
| Toshiba HDWD110 1TB                  | 2         | 0.4%    |
| SPCC Solid State Disk 512GB          | 2         | 0.4%    |
| SK Hynix SC311 SATA 256GB SSD        | 2         | 0.4%    |
| Seagate ST3320820AS 320GB            | 2         | 0.4%    |
| Seagate ST3000DM001-1ER166 3TB       | 2         | 0.4%    |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 0.4%    |
| Seagate ST2000DM001-1ER164 2TB       | 2         | 0.4%    |
| Seagate ST2000DL003-9VT166 2TB       | 2         | 0.4%    |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.4%    |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.4%    |
| Seagate Expansion Desk 10TB          | 2         | 0.4%    |
| Seagate Expansion 4TB                | 2         | 0.4%    |
| Seagate Backup+ Hub BK 8TB           | 2         | 0.4%    |
| Sandisk NVMe SSD Drive 512GB         | 2         | 0.4%    |
| Samsung SSD 980 PRO 500GB            | 2         | 0.4%    |
| Samsung SSD 970 EVO Plus 2TB         | 2         | 0.4%    |
| Samsung SSD 870 QVO 1TB              | 2         | 0.4%    |
| Samsung SSD 870 EVO 2TB              | 2         | 0.4%    |
| Samsung SSD 860 EVO 250GB            | 2         | 0.4%    |
| Samsung SSD 850 EVO 500GB            | 2         | 0.4%    |
| Samsung NVMe SSD Drive 256GB         | 2         | 0.4%    |
| Samsung NVMe SSD Drive 250GB         | 2         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 91     | 42.58%  |
| WDC                 | 43        | 60     | 27.74%  |
| Toshiba             | 19        | 22     | 12.26%  |
| HGST                | 10        | 10     | 6.45%   |
| Hitachi             | 7         | 7      | 4.52%   |
| Samsung Electronics | 4         | 4      | 2.58%   |
| Unknown             | 1         | 1      | 0.65%   |
| SABRENT             | 1         | 2      | 0.65%   |
| Intenso             | 1         | 2      | 0.65%   |
| Inateck             | 1         | 1      | 0.65%   |
| ASMT                | 1         | 1      | 0.65%   |
| Apple               | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 56     | 27.27%  |
| Kingston            | 16        | 22     | 11.19%  |
| Crucial             | 16        | 23     | 11.19%  |
| SanDisk             | 11        | 18     | 7.69%   |
| WDC                 | 10        | 11     | 6.99%   |
| PNY                 | 5         | 5      | 3.5%    |
| A-DATA Technology   | 5         | 8      | 3.5%    |
| SPCC                | 4         | 4      | 2.8%    |
| SK Hynix            | 4         | 5      | 2.8%    |
| China               | 4         | 6      | 2.8%    |
| Toshiba             | 3         | 4      | 2.1%    |
| LITEON              | 3         | 3      | 2.1%    |
| Transcend           | 2         | 2      | 1.4%    |
| Mushkin             | 2         | 2      | 1.4%    |
| LITEONIT            | 2         | 2      | 1.4%    |
| WDC WDS             | 1         | 1      | 0.7%    |
| VisionTek           | 1         | 2      | 0.7%    |
| USB30               | 1         | 2      | 0.7%    |
| Unknown             | 1         | 1      | 0.7%    |
| TO Exter            | 1         | 1      | 0.7%    |
| Team                | 1         | 2      | 0.7%    |
| QUMO                | 1         | 1      | 0.7%    |
| PNY CS90            | 1         | 1      | 0.7%    |
| OCZ                 | 1         | 1      | 0.7%    |
| Netac               | 1         | 1      | 0.7%    |
| Micron Technology   | 1         | 1      | 0.7%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.7%    |
| Intenso             | 1         | 1      | 0.7%    |
| FORESEE             | 1         | 1      | 0.7%    |
| EMTEC               | 1         | 1      | 0.7%    |
| Corsair             | 1         | 1      | 0.7%    |
| ASMedia             | 1         | 2      | 0.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 125       | 194    | 32.64%  |
| HDD     | 123       | 202    | 32.11%  |
| SSD     | 116       | 192    | 30.29%  |
| Unknown | 11        | 11     | 2.87%   |
| MMC     | 8         | 8      | 2.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 173       | 358    | 51.64%  |
| NVMe | 125       | 194    | 37.31%  |
| SAS  | 29        | 47     | 8.66%   |
| MMC  | 8         | 8      | 2.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 115       | 178    | 42.12%  |
| 0.51-1.0   | 95        | 125    | 34.8%   |
| 1.01-2.0   | 36        | 54     | 13.19%  |
| 3.01-4.0   | 10        | 14     | 3.66%   |
| 2.01-3.0   | 8         | 13     | 2.93%   |
| 4.01-10.0  | 7         | 7      | 2.56%   |
| 10.01-20.0 | 2         | 3      | 0.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 95        | 38.78%  |
| 1001-2000      | 54        | 22.04%  |
| 501-1000       | 36        | 14.69%  |
| 2001-3000      | 31        | 12.65%  |
| 251-500        | 13        | 5.31%   |
| Unknown        | 10        | 4.08%   |
| 101-250        | 3         | 1.22%   |
| 1-20           | 3         | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 58        | 22.75%  |
| 251-500        | 47        | 18.43%  |
| 501-1000       | 38        | 14.9%   |
| 1001-2000      | 36        | 14.12%  |
| 51-100         | 29        | 11.37%  |
| 2001-3000      | 16        | 6.27%   |
| More than 3000 | 14        | 5.49%   |
| Unknown        | 10        | 3.92%   |
| 1-20           | 4         | 1.57%   |
| 21-50          | 3         | 1.18%   |

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
| Samsung Electronics SSD 980 1TB       | 1         | 3      | 4.17%   |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 5      | 4.17%   |
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
| Samsung Electronics | 1         | 8      | 4.35%   |
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
| NVMe | 1         | 8      | 4.35%   |

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
| Works    | 132       | 276    | 46.64%  |
| Detected | 128       | 301    | 45.23%  |
| Malfunc  | 23        | 30     | 8.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 137       | 38.81%  |
| AMD                            | 75        | 21.25%  |
| Samsung Electronics            | 44        | 12.46%  |
| Sandisk                        | 25        | 7.08%   |
| Phison Electronics             | 14        | 3.97%   |
| SK Hynix                       | 12        | 3.4%    |
| Toshiba America Info Systems   | 5         | 1.42%   |
| Silicon Motion                 | 5         | 1.42%   |
| Micron/Crucial Technology      | 5         | 1.42%   |
| ASMedia Technology             | 5         | 1.42%   |
| Union Memory (Shenzhen)        | 4         | 1.13%   |
| Kingston Technology Company    | 4         | 1.13%   |
| Micron Technology              | 3         | 0.85%   |
| KIOXIA                         | 3         | 0.85%   |
| Marvell Technology Group       | 2         | 0.57%   |
| JMicron Technology             | 2         | 0.57%   |
| ADATA Technology               | 2         | 0.57%   |
| Yangtze Memory Technologies    | 1         | 0.28%   |
| Solid State Storage Technology | 1         | 0.28%   |
| Shenzhen Longsys Electronics   | 1         | 0.28%   |
| Realtek Semiconductor          | 1         | 0.28%   |
| Nvidia                         | 1         | 0.28%   |
| Lenovo                         | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 55        | 13.72%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 36        | 8.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 3.74%   |
| AMD 400 Series Chipset SATA Controller                                           | 14        | 3.49%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 11        | 2.74%   |
| Phison E12 NVMe Controller                                                       | 10        | 2.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 2.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 2.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 2.49%   |
| AMD 500 Series Chipset SATA Controller                                           | 10        | 2.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 2%      |
| Intel SSD 660P Series                                                            | 6         | 1.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 1.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 6         | 1.5%    |
| SK Hynix BC501 NVMe Solid State Drive                                            | 5         | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 1.25%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 5         | 1.25%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 1.25%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 4         | 1%      |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 1%      |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 1%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 4         | 1%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 1%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 4         | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4         | 1%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4         | 1%      |
| AMD 300 Series Chipset SATA Controller                                           | 4         | 1%      |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.75%   |
| SK Hynix Gold P31 SSD                                                            | 3         | 0.75%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.75%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 0.75%   |
| Sandisk Non-Volatile memory controller                                           | 3         | 0.75%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3         | 0.75%   |
| Micron Non-Volatile memory controller                                            | 3         | 0.75%   |
| KIOXIA Non-Volatile memory controller                                            | 3         | 0.75%   |
| Kingston Company A2000 NVMe SSD                                                  | 3         | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.75%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 0.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.75%   |
| AMD X399 Series Chipset SATA Controller                                          | 3         | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 3         | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.75%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.5%    |
| SK Hynix BC511                                                                   | 2         | 0.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.5%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.5%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.5%    |
| Phison NVMe Storage Controller                                                   | 2         | 0.5%    |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.5%    |
| Micron/Crucial NVMe Controller                                                   | 2         | 0.5%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 0.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 0.5%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.5%    |
| Intel PROSet/Wireless WiFi Software extension                                    | 2         | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 184       | 54.12%  |
| NVMe | 124       | 36.47%  |
| RAID | 19        | 5.59%   |
| IDE  | 13        | 3.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 147       | 61%     |
| AMD    | 94        | 39%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 2.9%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 2.9%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 2.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 2.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 2.07%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.66%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 1.66%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 1.66%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.66%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 1.24%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.24%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 1.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.24%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 1.24%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 3         | 1.24%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.24%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 1.24%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.24%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.83%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.83%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.83%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.83%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2         | 0.83%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.83%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 0.83%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.83%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.83%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 2         | 0.83%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 0.83%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.83%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 0.83%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.83%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 0.83%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.83%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 0.83%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2         | 0.83%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2         | 0.83%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 0.83%   |
| Intel Xeon CPU W3550 @ 3.07GHz                | 1         | 0.41%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz           | 1         | 0.41%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.41%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.41%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.41%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.41%   |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.41%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.41%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.41%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.41%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.41%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.41%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.41%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.41%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.41%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.41%   |
| Intel Core i7-6850K CPU @ 3.60GHz             | 1         | 0.41%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.41%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 57        | 23.65%  |
| Intel Core i5           | 45        | 18.67%  |
| AMD Ryzen 7             | 30        | 12.45%  |
| AMD Ryzen 5             | 29        | 12.03%  |
| Intel Core i3           | 18        | 7.47%   |
| AMD Ryzen 9             | 10        | 4.15%   |
| Other                   | 9         | 3.73%   |
| Intel Celeron           | 7         | 2.9%    |
| AMD Ryzen 3             | 4         | 1.66%   |
| AMD Ryzen Threadripper  | 3         | 1.24%   |
| AMD FX                  | 3         | 1.24%   |
| Intel Xeon              | 2         | 0.83%   |
| Intel Pentium Silver    | 2         | 0.83%   |
| Intel Pentium Dual-Core | 2         | 0.83%   |
| Intel Pentium           | 2         | 0.83%   |
| Intel Core 2 Duo        | 2         | 0.83%   |
| AMD Ryzen 7 PRO         | 2         | 0.83%   |
| AMD A8                  | 2         | 0.83%   |
| AMD A4                  | 2         | 0.83%   |
| AMD A10                 | 2         | 0.83%   |
| Intel Core m3           | 1         | 0.41%   |
| Intel Core i9           | 1         | 0.41%   |
| Intel Core 2 Quad       | 1         | 0.41%   |
| AMD Turion              | 1         | 0.41%   |
| AMD Phenom II X6        | 1         | 0.41%   |
| AMD Phenom II X4        | 1         | 0.41%   |
| AMD Phenom II X2        | 1         | 0.41%   |
| AMD A6                  | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 83        | 34.44%  |
| 2      | 65        | 26.97%  |
| 6      | 47        | 19.5%   |
| 8      | 35        | 14.52%  |
| 12     | 5         | 2.07%   |
| 16     | 4         | 1.66%   |
| 24     | 1         | 0.41%   |
| 10     | 1         | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 241       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 193       | 80.08%  |
| 1      | 48        | 19.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 241       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 102       | 41.63%  |
| 0x306a9    | 11        | 4.49%   |
| 0x306c3    | 10        | 4.08%   |
| 0x906ea    | 9         | 3.67%   |
| 0x206a7    | 8         | 3.27%   |
| 0x906e9    | 6         | 2.45%   |
| 0x0a50000c | 6         | 2.45%   |
| 0x08701021 | 6         | 2.45%   |
| 0x0800820d | 6         | 2.45%   |
| 0xa0652    | 5         | 2.04%   |
| 0x08108109 | 5         | 2.04%   |
| 0x506e3    | 4         | 1.63%   |
| 0x08600106 | 4         | 1.63%   |
| 0x08600103 | 4         | 1.63%   |
| 0x806e9    | 3         | 1.22%   |
| 0x806c1    | 3         | 1.22%   |
| 0x08600104 | 3         | 1.22%   |
| 0x08108102 | 3         | 1.22%   |
| 0x806ec    | 2         | 0.82%   |
| 0x806ea    | 2         | 0.82%   |
| 0x406e3    | 2         | 0.82%   |
| 0x40651    | 2         | 0.82%   |
| 0x106e5    | 2         | 0.82%   |
| 0x1067a    | 2         | 0.82%   |
| 0x08608103 | 2         | 0.82%   |
| 0x08001137 | 2         | 0.82%   |
| 0x06006705 | 2         | 0.82%   |
| 0xa0660    | 1         | 0.41%   |
| 0xa0655    | 1         | 0.41%   |
| 0xa0653    | 1         | 0.41%   |
| 0x906ed    | 1         | 0.41%   |
| 0x906ec    | 1         | 0.41%   |
| 0x906eb    | 1         | 0.41%   |
| 0x706e5    | 1         | 0.41%   |
| 0x706a8    | 1         | 0.41%   |
| 0x706a1    | 1         | 0.41%   |
| 0x506c9    | 1         | 0.41%   |
| 0x406c4    | 1         | 0.41%   |
| 0x306d4    | 1         | 0.41%   |
| 0x20655    | 1         | 0.41%   |
| 0x106a5    | 1         | 0.41%   |
| 0x10676    | 1         | 0.41%   |
| 0x0a50000b | 1         | 0.41%   |
| 0x0a201204 | 1         | 0.41%   |
| 0x0a201016 | 1         | 0.41%   |
| 0x0a201009 | 1         | 0.41%   |
| 0x08701013 | 1         | 0.41%   |
| 0x08101016 | 1         | 0.41%   |
| 0x0810100b | 1         | 0.41%   |
| 0x08101007 | 1         | 0.41%   |
| 0x07030105 | 1         | 0.41%   |
| 0x0700010f | 1         | 0.41%   |
| 0x06006110 | 1         | 0.41%   |
| 0x06003106 | 1         | 0.41%   |
| 0x06000852 | 1         | 0.41%   |
| 0x010000dc | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 43        | 17.84%  |
| Zen 2           | 30        | 12.45%  |
| Zen+            | 21        | 8.71%   |
| Haswell         | 20        | 8.3%    |
| Zen 3           | 17        | 7.05%   |
| IvyBridge       | 16        | 6.64%   |
| CometLake       | 14        | 5.81%   |
| SandyBridge     | 13        | 5.39%   |
| Skylake         | 10        | 4.15%   |
| Zen             | 8         | 3.32%   |
| TigerLake       | 5         | 2.07%   |
| Penryn          | 5         | 2.07%   |
| Broadwell       | 5         | 2.07%   |
| Unknown         | 4         | 1.66%   |
| Silvermont      | 3         | 1.24%   |
| Puma            | 3         | 1.24%   |
| Piledriver      | 3         | 1.24%   |
| Nehalem         | 3         | 1.24%   |
| K10             | 3         | 1.24%   |
| Goldmont plus   | 3         | 1.24%   |
| Excavator       | 3         | 1.24%   |
| Westmere        | 2         | 0.83%   |
| Steamroller     | 2         | 0.83%   |
| IceLake         | 2         | 0.83%   |
| K8 & K10 hybrid | 1         | 0.41%   |
| Jaguar          | 1         | 0.41%   |
| Goldmont        | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 114       | 36.42%  |
| Intel  | 111       | 35.46%  |
| AMD    | 88        | 28.12%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 15        | 4.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 3.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 3.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 3.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 2.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 2.8%    |
| AMD Cezanne                                                                              | 9         | 2.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 2.48%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 2.17%   |
| Intel HD Graphics 630                                                                    | 7         | 2.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 2.17%   |
| Nvidia TU117M                                                                            | 5         | 1.55%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 1.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 1.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.55%   |
| Intel HD Graphics 620                                                                    | 5         | 1.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.55%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 1.24%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 1.24%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 4         | 1.24%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.24%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 4         | 1.24%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 1.24%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 3         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.93%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3         | 0.93%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3         | 0.93%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.93%   |
| Intel HD Graphics 5500                                                                   | 3         | 0.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.93%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.93%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 3         | 0.93%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3         | 0.93%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2         | 0.62%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.62%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.62%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2         | 0.62%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 0.62%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.62%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 2         | 0.62%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.62%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 2         | 0.62%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2         | 0.62%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.62%   |
| Intel HD Graphics 530                                                                    | 2         | 0.62%   |
| Intel HD Graphics 510                                                                    | 2         | 0.62%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.62%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.62%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 2         | 0.62%   |
| AMD Lucienne                                                                             | 2         | 0.62%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.31%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 61        | 25.31%  |
| 1 x Intel          | 60        | 24.9%   |
| 1 x Nvidia         | 51        | 21.16%  |
| Intel + Nvidia     | 39        | 16.18%  |
| AMD + Nvidia       | 20        | 8.3%    |
| Intel + AMD        | 4         | 1.66%   |
| 2 x Nvidia         | 2         | 0.83%   |
| 2 x AMD            | 2         | 0.83%   |
| Intel + 2 x Nvidia | 2         | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 151       | 62.14%  |
| Proprietary | 92        | 37.86%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 132       | 53.44%  |
| 0.01-0.5   | 28        | 11.34%  |
| 1.01-2.0   | 23        | 9.31%   |
| 7.01-8.0   | 20        | 8.1%    |
| 3.01-4.0   | 16        | 6.48%   |
| 5.01-6.0   | 11        | 4.45%   |
| 0.51-1.0   | 9         | 3.64%   |
| 8.01-16.0  | 5         | 2.02%   |
| 2.01-3.0   | 2         | 0.81%   |
| 16.01-24.0 | 1         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 35        | 11.82%  |
| Samsung Electronics     | 34        | 11.49%  |
| LG Display              | 24        | 8.11%   |
| BOE                     | 23        | 7.77%   |
| Chimei Innolux          | 20        | 6.76%   |
| Dell                    | 18        | 6.08%   |
| Acer                    | 15        | 5.07%   |
| Goldstar                | 14        | 4.73%   |
| AOC                     | 12        | 4.05%   |
| Hewlett-Packard         | 10        | 3.38%   |
| Sharp                   | 9         | 3.04%   |
| BenQ                    | 9         | 3.04%   |
| PANDA                   | 8         | 2.7%    |
| Ancor Communications    | 8         | 2.7%    |
| Unknown                 | 6         | 2.03%   |
| Lenovo                  | 5         | 1.69%   |
| ASUSTek Computer        | 5         | 1.69%   |
| Sony                    | 3         | 1.01%   |
| Philips                 | 3         | 1.01%   |
| MSI                     | 3         | 1.01%   |
| Gigabyte Technology     | 3         | 1.01%   |
| Apple                   | 3         | 1.01%   |
| Vizio                   | 2         | 0.68%   |
| Mi                      | 2         | 0.68%   |
| Iiyama                  | 2         | 0.68%   |
| CSO                     | 2         | 0.68%   |
| ONN                     | 1         | 0.34%   |
| MStar                   | 1         | 0.34%   |
| MiTAC                   | 1         | 0.34%   |
| LTM                     | 1         | 0.34%   |
| LG Electronics          | 1         | 0.34%   |
| Lenovo Group Limited    | 1         | 0.34%   |
| Insignia                | 1         | 0.34%   |
| InfoVision              | 1         | 0.34%   |
| HPN                     | 1         | 0.34%   |
| HKC                     | 1         | 0.34%   |
| G-Story                 | 1         | 0.34%   |
| Fujitsu Siemens         | 1         | 0.34%   |
| Element                 | 1         | 0.34%   |
| Eizo                    | 1         | 0.34%   |
| CPT                     | 1         | 0.34%   |
| Chi Mei Optoelectronics | 1         | 0.34%   |
| AOpen                   | 1         | 0.34%   |
| Alba                    | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 4         | 1.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 3         | 0.98%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch   | 2         | 0.65%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.65%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 2         | 0.65%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 2         | 0.65%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch           | 2         | 0.65%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                | 2         | 0.65%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.65%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 0.65%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch       | 2         | 0.65%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                  | 2         | 0.65%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 2         | 0.65%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                  | 2         | 0.65%   |
| BOE LCD Monitor BOE0610 1920x1080 344x193mm 15.5-inch                  | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch         | 2         | 0.65%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2         | 0.65%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2         | 0.65%   |
| Acer XB271HU ACR0490 2560x1440 598x336mm 27.0-inch                     | 2         | 0.65%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2         | 0.65%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1         | 0.33%   |
| Vizio D320-B1 VIZ0095 1360x768 697x392mm 31.5-inch                     | 1         | 0.33%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1         | 0.33%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1         | 0.33%   |
| Unknown LCD Monitor SAMSUNG                                            | 1         | 0.33%   |
| Unknown LCD Monitor RJT HDMI                                           | 1         | 0.33%   |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1         | 0.33%   |
| Unknown LCD Monitor Hitachi/HINT W240D DVI                             | 1         | 0.33%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.33%   |
| Sony TV SNY1802 1920x1080                                              | 1         | 0.33%   |
| Sony TV SNY0801 1360x768                                               | 1         | 0.33%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch                | 1         | 0.33%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.33%   |
| Sharp LQ133T1JW17 SHP1409 2560x1440 294x165mm 13.3-inch                | 1         | 0.33%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.33%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.33%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                | 1         | 0.33%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.33%   |
| Samsung Electronics U28E850 SAM0CCB 3840x2160 607x345mm 27.5-inch      | 1         | 0.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1         | 0.33%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 1         | 0.33%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch      | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM04D5 1920x540                        | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM00BB 1280x1024 376x301mm 19.0-inch   | 1         | 0.33%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch    | 1         | 0.33%   |
| Samsung Electronics S24E450 SAM0CA0 1920x1080 531x299mm 24.0-inch      | 1         | 0.33%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch      | 1         | 0.33%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SyncMaster 3840x1080                   | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch  | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch   | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch   | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch  | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch  | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 145       | 51.42%  |
| 1366x768 (WXGA)    | 25        | 8.87%   |
| 3840x2160 (4K)     | 23        | 8.16%   |
| 1600x900 (HD+)     | 13        | 4.61%   |
| 2560x1440 (QHD)    | 12        | 4.26%   |
| Unknown            | 9         | 3.19%   |
| 1680x1050 (WSXGA+) | 7         | 2.48%   |
| 3840x1080          | 5         | 1.77%   |
| 3440x1440          | 5         | 1.77%   |
| 2560x1080          | 4         | 1.42%   |
| 1920x1200 (WUXGA)  | 4         | 1.42%   |
| 1440x900 (WXGA+)   | 4         | 1.42%   |
| 2560x1600          | 3         | 1.06%   |
| 7680x2160          | 2         | 0.71%   |
| 2256x1504          | 2         | 0.71%   |
| 1360x768           | 2         | 0.71%   |
| 1280x800 (WXGA)    | 2         | 0.71%   |
| 1280x1024 (SXGA)   | 2         | 0.71%   |
| 9600x2160          | 1         | 0.35%   |
| 4480x1440          | 1         | 0.35%   |
| 3840x2400          | 1         | 0.35%   |
| 3840x1200          | 1         | 0.35%   |
| 3200x1800 (QHD+)   | 1         | 0.35%   |
| 2880x1440          | 1         | 0.35%   |
| 2160x1440          | 1         | 0.35%   |
| 2048x1152          | 1         | 0.35%   |
| 1920x540           | 1         | 0.35%   |
| 1680x945           | 1         | 0.35%   |
| 1600x1200          | 1         | 0.35%   |
| 1280x720 (HD)      | 1         | 0.35%   |
| 1024x768 (XGA)     | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 79        | 27.62%  |
| 27      | 33        | 11.54%  |
| Unknown | 22        | 7.69%   |
| 24      | 20        | 6.99%   |
| 14      | 19        | 6.64%   |
| 13      | 19        | 6.64%   |
| 23      | 18        | 6.29%   |
| 17      | 11        | 3.85%   |
| 22      | 7         | 2.45%   |
| 21      | 7         | 2.45%   |
| 34      | 6         | 2.1%    |
| 19      | 6         | 2.1%    |
| 31      | 5         | 1.75%   |
| 72      | 4         | 1.4%    |
| 20      | 4         | 1.4%    |
| 16      | 4         | 1.4%    |
| 49      | 3         | 1.05%   |
| 18      | 3         | 1.05%   |
| 54      | 2         | 0.7%    |
| 43      | 2         | 0.7%    |
| 40      | 2         | 0.7%    |
| 28      | 2         | 0.7%    |
| 52      | 1         | 0.35%   |
| 48      | 1         | 0.35%   |
| 47      | 1         | 0.35%   |
| 39      | 1         | 0.35%   |
| 33      | 1         | 0.35%   |
| 25      | 1         | 0.35%   |
| 12      | 1         | 0.35%   |
| 11      | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 107       | 38.21%  |
| 501-600     | 62        | 22.14%  |
| 401-500     | 25        | 8.93%   |
| Unknown     | 22        | 7.86%   |
| 201-300     | 15        | 5.36%   |
| 351-400     | 13        | 4.64%   |
| 601-700     | 12        | 4.29%   |
| 1001-1500   | 8         | 2.86%   |
| 701-800     | 7         | 2.5%    |
| 1501-2000   | 4         | 1.43%   |
| 801-900     | 3         | 1.07%   |
| 901-1000    | 2         | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 197       | 76.36%  |
| 16/10   | 25        | 9.69%   |
| Unknown | 19        | 7.36%   |
| 21/9    | 7         | 2.71%   |
| 32/9    | 3         | 1.16%   |
| 3/2     | 3         | 1.16%   |
| 5/4     | 2         | 0.78%   |
| 4/3     | 1         | 0.39%   |
| 2.00    | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 80        | 28.47%  |
| 201-250        | 40        | 14.23%  |
| 301-350        | 33        | 11.74%  |
| 81-90          | 29        | 10.32%  |
| Unknown        | 22        | 7.83%   |
| 351-500        | 13        | 4.63%   |
| 151-200        | 11        | 3.91%   |
| 121-130        | 10        | 3.56%   |
| More than 1000 | 9         | 3.2%    |
| 71-80          | 9         | 3.2%    |
| 251-300        | 8         | 2.85%   |
| 501-1000       | 8         | 2.85%   |
| 141-150        | 4         | 1.42%   |
| 111-120        | 2         | 0.71%   |
| 61-70          | 1         | 0.36%   |
| 51-60          | 1         | 0.36%   |
| 91-100         | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 92        | 34.07%  |
| 51-100        | 77        | 28.52%  |
| 101-120       | 47        | 17.41%  |
| Unknown       | 22        | 8.15%   |
| 161-240       | 15        | 5.56%   |
| 1-50          | 11        | 4.07%   |
| More than 240 | 6         | 2.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 170       | 69.96%  |
| 2     | 61        | 25.1%   |
| 3     | 9         | 3.7%    |
| 0     | 3         | 1.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 144       | 37.7%   |
| Intel                             | 126       | 32.98%  |
| Qualcomm Atheros                  | 42        | 10.99%  |
| Broadcom                          | 15        | 3.93%   |
| Ralink Technology                 | 5         | 1.31%   |
| NetGear                           | 5         | 1.31%   |
| MEDIATEK                          | 5         | 1.31%   |
| TP-Link                           | 4         | 1.05%   |
| Samsung Electronics               | 3         | 0.79%   |
| Microsoft                         | 3         | 0.79%   |
| Linksys                           | 3         | 0.79%   |
| Aquantia                          | 3         | 0.79%   |
| Ralink                            | 2         | 0.52%   |
| Qualcomm                          | 2         | 0.52%   |
| DisplayLink                       | 2         | 0.52%   |
| ASUSTek Computer                  | 2         | 0.52%   |
| ASIX Electronics                  | 2         | 0.52%   |
| Xiaomi                            | 1         | 0.26%   |
| Wacom                             | 1         | 0.26%   |
| Sierra Wireless                   | 1         | 0.26%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.26%   |
| Nvidia                            | 1         | 0.26%   |
| Lenovo                            | 1         | 0.26%   |
| InterBiometrics                   | 1         | 0.26%   |
| Holtek Semiconductor              | 1         | 0.26%   |
| Ericsson Business Mobile Networks | 1         | 0.26%   |
| Dell                              | 1         | 0.26%   |
| Broadcom Limited                  | 1         | 0.26%   |
| Belkin Components                 | 1         | 0.26%   |
| Alteon Networks                   | 1         | 0.26%   |
| Accton Technology                 | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 102       | 22.87%  |
| Intel Wi-Fi 6 AX200                                                 | 22        | 4.93%   |
| Intel I211 Gigabit Network Connection                               | 13        | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 12        | 2.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 10        | 2.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 9         | 2.02%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 9         | 2.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 8         | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 8         | 1.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 7         | 1.57%   |
| Realtek RTL8125 2.5GbE Controller                                   | 7         | 1.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 7         | 1.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 6         | 1.35%   |
| Intel Wireless-AC 9260                                              | 6         | 1.35%   |
| Intel Ethernet Controller I225-V                                    | 6         | 1.35%   |
| Intel Ethernet Connection I217-LM                                   | 6         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 5         | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 5         | 1.12%   |
| Intel Wireless 8265 / 8275                                          | 5         | 1.12%   |
| Intel Wireless 7265                                                 | 5         | 1.12%   |
| Intel Wireless 3165                                                 | 5         | 1.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 5         | 1.12%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 4         | 0.9%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 4         | 0.9%    |
| Intel Wireless 7260                                                 | 4         | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 4         | 0.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 3         | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 3         | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3         | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 3         | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3         | 0.67%   |
| Intel Wireless 8260                                                 | 3         | 0.67%   |
| Intel Wi-Fi 6 AX201                                                 | 3         | 0.67%   |
| Intel Ethernet Connection I219-LM                                   | 3         | 0.67%   |
| Intel Centrino Advanced-N 6200                                      | 3         | 0.67%   |
| Intel 82577LM Gigabit Network Connection                            | 3         | 0.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 2         | 0.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 2         | 0.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2         | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2         | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 2         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2         | 0.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2         | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2         | 0.45%   |
| NetGear A6210                                                       | 2         | 0.45%   |
| Microsoft XBOX ACC                                                  | 2         | 0.45%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter       | 2         | 0.45%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2         | 0.45%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection       | 2         | 0.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 2         | 0.45%   |
| Intel Ethernet Connection (4) I219-LM                               | 2         | 0.45%   |
| Intel Ethernet Connection (3) I218-LM                               | 2         | 0.45%   |
| Intel Ethernet Connection (2) I219-V                                | 2         | 0.45%   |
| Intel Centrino Ultimate-N 6300                                      | 2         | 0.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 0.45%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 2         | 0.45%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express              | 2         | 0.45%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 2         | 0.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                 | 2         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 102       | 47.22%  |
| Realtek Semiconductor | 41        | 18.98%  |
| Qualcomm Atheros      | 30        | 13.89%  |
| Broadcom              | 11        | 5.09%   |
| Ralink Technology     | 5         | 2.31%   |
| NetGear               | 5         | 2.31%   |
| TP-Link               | 4         | 1.85%   |
| Microsoft             | 3         | 1.39%   |
| MEDIATEK              | 3         | 1.39%   |
| Linksys               | 3         | 1.39%   |
| Ralink                | 2         | 0.93%   |
| ASUSTek Computer      | 2         | 0.93%   |
| Wacom                 | 1         | 0.46%   |
| Sierra Wireless       | 1         | 0.46%   |
| Dell                  | 1         | 0.46%   |
| Broadcom Limited      | 1         | 0.46%   |
| Accton Technology     | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 22        | 10.09%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 12        | 5.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 9         | 4.13%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 9         | 4.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 8         | 3.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 8         | 3.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 7         | 3.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 6         | 2.75%   |
| Intel Wireless-AC 9260                                                    | 6         | 2.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 6         | 2.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 5         | 2.29%   |
| Intel Wireless 8265 / 8275                                                | 5         | 2.29%   |
| Intel Wireless 7265                                                       | 5         | 2.29%   |
| Intel Wireless 3165                                                       | 5         | 2.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 5         | 2.29%   |
| Intel Wireless 7260                                                       | 4         | 1.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 4         | 1.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 3         | 1.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 3         | 1.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3         | 1.38%   |
| Intel Wireless 8260                                                       | 3         | 1.38%   |
| Intel Wi-Fi 6 AX201                                                       | 3         | 1.38%   |
| Intel Centrino Advanced-N 6200                                            | 3         | 1.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 2         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                  | 2         | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 2         | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 2         | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 2         | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 0.92%   |
| NetGear A6210                                                             | 2         | 0.92%   |
| Microsoft XBOX ACC                                                        | 2         | 0.92%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter             | 2         | 0.92%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]       | 2         | 0.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection             | 2         | 0.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 2         | 0.92%   |
| Intel Centrino Ultimate-N 6300                                            | 2         | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 2         | 0.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 2         | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                       | 2         | 0.92%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                  | 1         | 0.46%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1         | 0.46%   |
| Sierra Wireless EM7455                                                    | 1         | 0.46%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1         | 0.46%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 0.46%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 0.46%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1         | 0.46%   |
| Realtek RTL8191SEvB Wireless LAN Controller                               | 1         | 0.46%   |
| Realtek RTL8191SEvA Wireless LAN Controller                               | 1         | 0.46%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                    | 1         | 0.46%   |
| Realtek 802.11n WLAN Adapter                                              | 1         | 0.46%   |
| Ralink Wireless Adapter Canyon CN-WF511                                   | 1         | 0.46%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                         | 1         | 0.46%   |
| Ralink MT7601U Wireless Adapter                                           | 1         | 0.46%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1         | 0.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 0.46%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1         | 0.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 0.46%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1         | 0.46%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.46%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]               | 1         | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 125       | 56.31%  |
| Intel                 | 54        | 24.32%  |
| Qualcomm Atheros      | 17        | 7.66%   |
| Broadcom              | 7         | 3.15%   |
| Samsung Electronics   | 3         | 1.35%   |
| Aquantia              | 3         | 1.35%   |
| Qualcomm              | 2         | 0.9%    |
| MediaTek              | 2         | 0.9%    |
| DisplayLink           | 2         | 0.9%    |
| ASIX Electronics      | 2         | 0.9%    |
| Xiaomi                | 1         | 0.45%   |
| Nvidia                | 1         | 0.45%   |
| Lenovo                | 1         | 0.45%   |
| Belkin Components     | 1         | 0.45%   |
| Alteon Networks       | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 102       | 45.54%  |
| Intel I211 Gigabit Network Connection                               | 13        | 5.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 10        | 4.46%   |
| Realtek RTL8125 2.5GbE Controller                                   | 7         | 3.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 7         | 3.13%   |
| Intel Ethernet Controller I225-V                                    | 6         | 2.68%   |
| Intel Ethernet Connection I217-LM                                   | 6         | 2.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 5         | 2.23%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 4         | 1.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 4         | 1.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 3         | 1.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3         | 1.34%   |
| Intel Ethernet Connection I219-LM                                   | 3         | 1.34%   |
| Intel 82577LM Gigabit Network Connection                            | 3         | 1.34%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 2         | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2         | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                               | 2         | 0.89%   |
| Intel Ethernet Connection (3) I218-LM                               | 2         | 0.89%   |
| Intel Ethernet Connection (2) I219-V                                | 2         | 0.89%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 2         | 0.89%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express              | 2         | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                       | 2         | 0.89%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1         | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1         | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1         | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                              | 1         | 0.45%   |
| Qualcomm Redmi Note 9S                                              | 1         | 0.45%   |
| Qualcomm M2012K11AG                                                 | 1         | 0.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                              | 1         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1         | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1         | 0.45%   |
| Nvidia MCP79 Ethernet                                               | 1         | 0.45%   |
| MediaTek Vodafone Smart N10                                         | 1         | 0.45%   |
| MediaTek SP514                                                      | 1         | 0.45%   |
| Lenovo ThinkPad Lan                                                 | 1         | 0.45%   |
| Intel Ethernet Connection I217-V                                    | 1         | 0.45%   |
| Intel Ethernet Connection (7) I219-V                                | 1         | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                               | 1         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                               | 1         | 0.45%   |
| Intel Ethernet Connection (2) I218-V                                | 1         | 0.45%   |
| Intel Ethernet Connection (10) I219-V                               | 1         | 0.45%   |
| Intel 82579V Gigabit Network Connection                             | 1         | 0.45%   |
| DisplayLink ThinkPad USB 3.0 Dock                                   | 1         | 0.45%   |
| DisplayLink Dell D1000 USB3.0 Dock                                  | 1         | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                   | 1         | 0.45%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express             | 1         | 0.45%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                     | 1         | 0.45%   |
| Belkin Components F5D5050 100Mbps Ethernet                          | 1         | 0.45%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.45%   |
| Alteon Networks Ethernet controller                                 | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 203       | 50.12%  |
| WiFi     | 198       | 48.89%  |
| Modem    | 2         | 0.49%   |
| Unknown  | 2         | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 148       | 60.16%  |
| Ethernet | 98        | 39.84%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 135       | 55.79%  |
| 1     | 96        | 39.67%  |
| 3     | 7         | 2.89%   |
| 0     | 3         | 1.24%   |
| 4     | 1         | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 194       | 79.51%  |
| Yes  | 50        | 20.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 86        | 48.31%  |
| Realtek Semiconductor           | 26        | 14.61%  |
| Qualcomm Atheros Communications | 23        | 12.92%  |
| Cambridge Silicon Radio         | 8         | 4.49%   |
| IMC Networks                    | 7         | 3.93%   |
| Broadcom                        | 6         | 3.37%   |
| Lite-On Technology              | 4         | 2.25%   |
| Foxconn / Hon Hai               | 4         | 2.25%   |
| Apple                           | 4         | 2.25%   |
| ASUSTek Computer                | 3         | 1.69%   |
| Hewlett-Packard                 | 2         | 1.12%   |
| Dell                            | 2         | 1.12%   |
| Realtek                         | 1         | 0.56%   |
| Edimax Technology               | 1         | 0.56%   |
| Dynex                           | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                               | 22        | 12.36%  |
| Intel Bluetooth wireless interface                                                  | 18        | 10.11%  |
| Intel AX201 Bluetooth                                                               | 14        | 7.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 13        | 7.3%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 12        | 6.74%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 11        | 6.18%   |
| Realtek Bluetooth Radio                                                             | 11        | 6.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 4.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 3.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 3.37%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 3.37%   |
| Intel AX210 Bluetooth                                                               | 4         | 2.25%   |
| Realtek 802.11ac WLAN Adapter                                                       | 3         | 1.69%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.69%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.69%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.12%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.12%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.12%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.12%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.12%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.12%   |
| ASUS Bluetooth Radio                                                                | 2         | 1.12%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.56%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.56%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.56%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.56%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.56%   |
| Edimax Bluetooth Device                                                             | 1         | 0.56%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.56%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.56%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.56%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.56%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.56%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.56%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.56%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 146       | 38.52%  |
| AMD                       | 102       | 26.91%  |
| Nvidia                    | 80        | 21.11%  |
| C-Media Electronics       | 9         | 2.37%   |
| Logitech                  | 6         | 1.58%   |
| Sony                      | 2         | 0.53%   |
| Sennheiser Communications | 2         | 0.53%   |
| RODE Microphones          | 2         | 0.53%   |
| Kingston Technology       | 2         | 0.53%   |
| JMTek                     | 2         | 0.53%   |
| Generalplus Technology    | 2         | 0.53%   |
| Creative Technology       | 2         | 0.53%   |
| Creative Labs             | 2         | 0.53%   |
| Corsair                   | 2         | 0.53%   |
| Blue Microphones          | 2         | 0.53%   |
| Yamaha                    | 1         | 0.26%   |
| Turtle Beach              | 1         | 0.26%   |
| Trust                     | 1         | 0.26%   |
| Texas Instruments         | 1         | 0.26%   |
| Tenx Technology           | 1         | 0.26%   |
| SteelSeries ApS           | 1         | 0.26%   |
| Realtek Semiconductor     | 1         | 0.26%   |
| Plantronics               | 1         | 0.26%   |
| Phison Electronics        | 1         | 0.26%   |
| Jieli Technology          | 1         | 0.26%   |
| Huawei Technologies       | 1         | 0.26%   |
| Hewlett-Packard           | 1         | 0.26%   |
| GN Netcom                 | 1         | 0.26%   |
| Focusrite-Novation        | 1         | 0.26%   |
| EVGA                      | 1         | 0.26%   |
| DigiTech                  | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 40        | 8.68%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 23        | 4.99%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 3.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 3.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 3.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 3.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 2.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 2.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 13        | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 2.6%    |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 2.17%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 9         | 1.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9         | 1.95%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 1.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.52%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 7         | 1.52%   |
| Nvidia TU104 HD Audio Controller                                                                  | 6         | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.3%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 6         | 1.3%    |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.3%    |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.3%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.3%    |
| AMD FCH Azalia Controller                                                                         | 6         | 1.3%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 1.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.08%   |
| C-Media Electronics SADES Luna                                                                    | 5         | 1.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.08%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.87%   |
| Nvidia Audio device                                                                               | 4         | 0.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 0.87%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 0.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.87%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 0.87%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 0.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 0.87%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                        | 4         | 0.87%   |
| AMD Navi 10 HDMI Audio                                                                            | 4         | 0.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.65%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.65%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.65%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 0.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.65%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.65%   |
| RODE Microphones RODE NT-USB                                                                      | 2         | 0.43%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Logitech G933 Wireless Headset Dongle                                                             | 2         | 0.43%   |
| JMTek USB PnP Audio Device                                                                        | 2         | 0.43%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.43%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.43%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 24.46%  |
| SK Hynix            | 29        | 15.76%  |
| Crucial             | 17        | 9.24%   |
| Micron Technology   | 16        | 8.7%    |
| G.Skill             | 15        | 8.15%   |
| Kingston            | 12        | 6.52%   |
| Corsair             | 11        | 5.98%   |
| Unknown             | 7         | 3.8%    |
| Patriot             | 6         | 3.26%   |
| Ramaxel Technology  | 5         | 2.72%   |
| A-DATA Technology   | 4         | 2.17%   |
| Team                | 3         | 1.63%   |
| Nanya Technology    | 3         | 1.63%   |
| Unknown (ABCD)      | 2         | 1.09%   |
| Smart               | 2         | 1.09%   |
| Transcend           | 1         | 0.54%   |
| TIMETEC             | 1         | 0.54%   |
| Elpida              | 1         | 0.54%   |
| CSX                 | 1         | 0.54%   |
| Avant               | 1         | 0.54%   |
| Apacer              | 1         | 0.54%   |
| 48spaces            | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 6         | 3.03%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 5         | 2.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 5         | 2.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 4         | 2.02%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 4         | 2.02%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s       | 3         | 1.52%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 3         | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 3         | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 3         | 1.52%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s          | 3         | 1.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 2         | 1.01%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s        | 2         | 1.01%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1.01%   |
| SK Hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s        | 2         | 1.01%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 2         | 1.01%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.01%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 2         | 1.01%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 1.01%   |
| Patriot RAM 2666 C16 Series 8GB DIMM DDR4 2667MT/s             | 2         | 1.01%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s           | 2         | 1.01%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s          | 2         | 1.01%   |
| Corsair RAM CMK32GX4M4B3200C16 8192MB DIMM DDR4 3600MT/s       | 2         | 1.01%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.51%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                    | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                    | 1         | 0.51%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                           | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 0.51%   |
| Unknown RAM Module 1GB DIMM 1066MT/s                           | 1         | 0.51%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s          | 1         | 0.51%   |
| Transcend RAM JM2666HSE-16G 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.51%   |
| TIMETEC RAM SD3-1866 8GB SODIMM DDR3 1866MT/s                  | 1         | 0.51%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s             | 1         | 0.51%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s             | 1         | 0.51%   |
| Team RAM TEAMGROUP-SD4-2133 8GB SODIMM DDR4 2133MT/s           | 1         | 0.51%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s          | 1         | 0.51%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB DDR4 2667MT/s                 | 1         | 0.51%   |
| SK Hynix RAM Module 4GB Row Of Chips LPDDR3 1333MT/s           | 1         | 0.51%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 0.51%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 0.51%   |
| SK Hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s           | 1         | 0.51%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 0.51%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 0.51%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s   | 1         | 0.51%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 1         | 0.51%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 1         | 0.51%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 0.51%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s   | 1         | 0.51%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s     | 1         | 0.51%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s      | 1         | 0.51%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 0.51%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s      | 1         | 0.51%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 1         | 0.51%   |
| SK Hynix RAM H5AN8G6NDJR-XNC 4GB Row Of Chips DDR4 3200MT/s    | 1         | 0.51%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s     | 1         | 0.51%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                      | 1         | 0.51%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.51%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                     | 1         | 0.51%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 1         | 0.51%   |
| Samsung RAM M471B5273DH0-YH9 4GB SODIMM DDR3 1600MT/s          | 1         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 100       | 64.52%  |
| DDR3    | 41        | 26.45%  |
| LPDDR4  | 6         | 3.87%   |
| LPDDR3  | 3         | 1.94%   |
| Unknown | 3         | 1.94%   |
| DDR2    | 2         | 1.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 97        | 61.39%  |
| DIMM         | 47        | 29.75%  |
| Row Of Chips | 12        | 7.59%   |
| Chip         | 1         | 0.63%   |
| Unknown      | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 89        | 51.74%  |
| 4096  | 46        | 26.74%  |
| 16384 | 29        | 16.86%  |
| 2048  | 5         | 2.91%   |
| 32768 | 2         | 1.16%   |
| 1024  | 1         | 0.58%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 38        | 21.84%  |
| 2667  | 33        | 18.97%  |
| 1600  | 31        | 17.82%  |
| 2400  | 16        | 9.2%    |
| 3600  | 13        | 7.47%   |
| 2133  | 5         | 2.87%   |
| 3466  | 4         | 2.3%    |
| 3266  | 4         | 2.3%    |
| 4266  | 3         | 1.72%   |
| 2666  | 3         | 1.72%   |
| 1334  | 3         | 1.72%   |
| 1333  | 3         | 1.72%   |
| 3866  | 2         | 1.15%   |
| 1867  | 2         | 1.15%   |
| 1866  | 2         | 1.15%   |
| 1800  | 2         | 1.15%   |
| 800   | 2         | 1.15%   |
| 4267  | 1         | 0.57%   |
| 4200  | 1         | 0.57%   |
| 4000  | 1         | 0.57%   |
| 3067  | 1         | 0.57%   |
| 2933  | 1         | 0.57%   |
| 2200  | 1         | 0.57%   |
| 1066  | 1         | 0.57%   |
| 667   | 1         | 0.57%   |

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
| Chicony Electronics                    | 35        | 22.44%  |
| IMC Networks                           | 17        | 10.9%   |
| Logitech                               | 16        | 10.26%  |
| Realtek Semiconductor                  | 11        | 7.05%   |
| Microdia                               | 11        | 7.05%   |
| Acer                                   | 10        | 6.41%   |
| Quanta                                 | 8         | 5.13%   |
| Sunplus Innovation Technology          | 6         | 3.85%   |
| Microsoft                              | 6         | 3.85%   |
| Syntek                                 | 4         | 2.56%   |
| Luxvisions Innotech Limited            | 4         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.56%   |
| Apple                                  | 4         | 2.56%   |
| Suyin                                  | 3         | 1.92%   |
| Lite-On Technology                     | 3         | 1.92%   |
| Silicon Motion                         | 2         | 1.28%   |
| Jieli Technology                       | 2         | 1.28%   |
| Z-Star Microelectronics                | 1         | 0.64%   |
| WaveRider Communications               | 1         | 0.64%   |
| Unknown                                | 1         | 0.64%   |
| Sonix Technology                       | 1         | 0.64%   |
| Samsung Electronics                    | 1         | 0.64%   |
| Razer USA                              | 1         | 0.64%   |
| MacroSilicon                           | 1         | 0.64%   |
| Lenovo                                 | 1         | 0.64%   |
| Importek                               | 1         | 0.64%   |
| Genesys Logic                          | 1         | 0.64%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 8         | 5.1%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 8         | 5.1%    |
| Chicony Integrated Camera                           | 7         | 4.46%   |
| IMC Networks Integrated Camera                      | 6         | 3.82%   |
| Chicony HD WebCam                                   | 5         | 3.18%   |
| Syntek Integrated Camera                            | 4         | 2.55%   |
| Chicony HD User Facing                              | 4         | 2.55%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 1.91%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 1.91%   |
| Logitech Webcam C270                                | 3         | 1.91%   |
| Lite-On HP Wide Vision HD Camera                    | 3         | 1.91%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 1.91%   |
| Acer HD Webcam                                      | 3         | 1.91%   |
| Quanta HP Wide Vision HD Camera                     | 2         | 1.27%   |
| Microsoft LifeCam HD-5000                           | 2         | 1.27%   |
| Microsoft LifeCam HD-3000                           | 2         | 1.27%   |
| Logitech Webcam C930e                               | 2         | 1.27%   |
| Logitech HD Webcam C910                             | 2         | 1.27%   |
| Logitech HD Pro Webcam C920                         | 2         | 1.27%   |
| Logitech C922 Pro Stream Webcam                     | 2         | 1.27%   |
| Logitech BRIO Ultra HD Webcam                       | 2         | 1.27%   |
| Jieli USB PHY 2.0                                   | 2         | 1.27%   |
| IMC Networks HD Camera                              | 2         | 1.27%   |
| Chicony USB 2.0 Camera                              | 2         | 1.27%   |
| Chicony EasyCamera                                  | 2         | 1.27%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 1.27%   |
| Acer Integrated Camera                              | 2         | 1.27%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 0.64%   |
| WaveRider USB 2.0 Camera                            | 1         | 0.64%   |
| Unknown 720p HD Camera                              | 1         | 0.64%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.64%   |
| Suyin HP Integrated Webcam                          | 1         | 0.64%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.64%   |
| Sunplus MTD Camera                                  | 1         | 0.64%   |
| Sunplus Integrated Webcam                           | 1         | 0.64%   |
| Sunplus Integrated Camera                           | 1         | 0.64%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.64%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 0.64%   |
| Silicon Motion Web Camera                           | 1         | 0.64%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.64%   |
| Realtek USB Camera                                  | 1         | 0.64%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.64%   |
| Realtek Integrated_Webcam_HD                        | 1         | 0.64%   |
| Realtek Integrated Webcam                           | 1         | 0.64%   |
| Realtek HP "Truevision HD" laptop camera            | 1         | 0.64%   |
| Realtek HD WebCam                                   | 1         | 0.64%   |
| Realtek Full HD webcam                              | 1         | 0.64%   |
| Realtek FJ Camera                                   | 1         | 0.64%   |
| Realtek EasyCamera                                  | 1         | 0.64%   |
| Realtek Built-In Video Camera                       | 1         | 0.64%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 0.64%   |
| Razer USA Razer Kiyo Pro                            | 1         | 0.64%   |
| Quanta WEBCAM                                       | 1         | 0.64%   |
| Quanta USB2.0 VGA UVC WebCam                        | 1         | 0.64%   |
| Quanta USB HD Webcam                                | 1         | 0.64%   |
| Quanta HP True Vision HD Camera                     | 1         | 0.64%   |
| Quanta HD User Facing                               | 1         | 0.64%   |
| Quanta HD Camera                                    | 1         | 0.64%   |
| Microsoft Xbox NUI Camera                           | 1         | 0.64%   |
| Microsoft Modern Webcam                             | 1         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 24.14%  |
| Synaptics                  | 7         | 24.14%  |
| Shenzhen Goodix Technology | 5         | 17.24%  |
| Elan Microelectronics      | 5         | 17.24%  |
| LighTuning Technology      | 2         | 6.9%    |
| AuthenTec                  | 2         | 6.9%    |
| Samsung Electronics        | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device               | 3         | 10.34%  |
| Elan ELAN:ARM-M4                                  | 3         | 10.34%  |
| Unknown                                           | 3         | 10.34%  |
| Validity Sensors Synaptics WBDI                   | 2         | 6.9%    |
| Elan ELAN:Fingerprint                             | 2         | 6.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 3.45%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 3.45%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 3.45%   |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 3.45%   |
| Synaptics WBDI Device                             | 1         | 3.45%   |
| Synaptics  WBDI Fingerprint Reader - USB 052      | 1         | 3.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 3.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 3.45%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 3.45%   |
| Shenzhen Goodix FingerPrint                       | 1         | 3.45%   |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 3.45%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 3.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 3.45%   |
| AuthenTec AES2810                                 | 1         | 3.45%   |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 66.67%  |
| Upek        | 1         | 8.33%   |
| O2 Micro    | 1         | 8.33%   |
| Lenovo      | 1         | 8.33%   |
| Alcor Micro | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 16.67%  |
| Broadcom 5880                                                                | 2         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 8.33%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 117       | 47.56%  |
| 0     | 80        | 32.52%  |
| 2     | 41        | 16.67%  |
| 3     | 7         | 2.85%   |
| 4     | 1         | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 135       | 60.27%  |
| Fingerprint reader       | 29        | 12.95%  |
| Net/wireless             | 14        | 6.25%   |
| Graphics card            | 13        | 5.8%    |
| Chipcard                 | 12        | 5.36%   |
| Net/ethernet             | 7         | 3.13%   |
| Multimedia controller    | 4         | 1.79%   |
| Camera                   | 4         | 1.79%   |
| Storage                  | 2         | 0.89%   |
| Wireless                 | 1         | 0.45%   |
| Unassigned class         | 1         | 0.45%   |
| Network                  | 1         | 0.45%   |
| Bluetooth                | 1         | 0.45%   |

