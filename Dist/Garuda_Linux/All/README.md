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

Total: 385

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [2212732244](https://linux-hardware.org/?probe=2212732244) | Aug 01, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b7618f5c14](https://linux-hardware.org/?probe=b7618f5c14) | Jul 31, 2022 |
| Dell          | Latitude E5450              | Notebook    | [2c6979fb39](https://linux-hardware.org/?probe=2c6979fb39) | Jul 31, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [b44feede78](https://linux-hardware.org/?probe=b44feede78) | Jul 30, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [941092ee95](https://linux-hardware.org/?probe=941092ee95) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dfe6047aa7](https://linux-hardware.org/?probe=dfe6047aa7) | Jul 21, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f9996d6494](https://linux-hardware.org/?probe=f9996d6494) | Jul 21, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0687ecd744](https://linux-hardware.org/?probe=0687ecd744) | Jul 14, 2022 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [e8770aea50](https://linux-hardware.org/?probe=e8770aea50) | Jul 14, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [f44445fbe2](https://linux-hardware.org/?probe=f44445fbe2) | Jul 13, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [9ade46617e](https://linux-hardware.org/?probe=9ade46617e) | Jul 06, 2022 |
| HP            | Pavilion dv6                | Notebook    | [fcb28ad60c](https://linux-hardware.org/?probe=fcb28ad60c) | Jul 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [31941e5972](https://linux-hardware.org/?probe=31941e5972) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [dc6e8358f8](https://linux-hardware.org/?probe=dc6e8358f8) | Jul 04, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7d5ee550de](https://linux-hardware.org/?probe=7d5ee550de) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [dde2246ae8](https://linux-hardware.org/?probe=dde2246ae8) | Jul 01, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [77f0b32727](https://linux-hardware.org/?probe=77f0b32727) | Jun 30, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [5bf5fec549](https://linux-hardware.org/?probe=5bf5fec549) | Jun 27, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [b88589b731](https://linux-hardware.org/?probe=b88589b731) | Jun 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [7c08b4e995](https://linux-hardware.org/?probe=7c08b4e995) | Jun 26, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [a7a76f04f9](https://linux-hardware.org/?probe=a7a76f04f9) | Jun 19, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [f0cf5e0f30](https://linux-hardware.org/?probe=f0cf5e0f30) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5fb74a78d8](https://linux-hardware.org/?probe=5fb74a78d8) | Jun 17, 2022 |
| Lenovo        | IdeaPad Z480                | Notebook    | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [0c1e336ddc](https://linux-hardware.org/?probe=0c1e336ddc) | Jun 11, 2022 |
| Lenovo        | IdeaPad C340-15IML 81TL     | Convertible | [042c11425c](https://linux-hardware.org/?probe=042c11425c) | Jun 10, 2022 |
| T-bao         | MINI PC V1.0                | Desktop     | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [389e13e580](https://linux-hardware.org/?probe=389e13e580) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
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

![OS](./images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Garuda Linux Soaring | 172       | 63.7%   |
| Garuda Linux         | 93        | 34.44%  |
| Garuda Linux Rolling | 5         | 1.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Garuda Linux | 267       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.17.1-zen1-1-zen   | 9         | 2.93%   |
| 5.15.2-zen1-1-zen   | 7         | 2.28%   |
| 5.14.14-zen1-1-zen  | 7         | 2.28%   |
| 5.17.9-zen1-1-zen   | 6         | 1.95%   |
| 5.16.4-zen1-1-zen   | 6         | 1.95%   |
| 5.15.7-zen1-1-zen   | 5         | 1.63%   |
| 5.15.13-zen1-1-zen  | 5         | 1.63%   |
| 5.15.12-zen1-1-zen  | 5         | 1.63%   |
| 5.13.9-zen1-1-zen   | 5         | 1.63%   |
| 5.13.13-zen1-1-zen  | 5         | 1.63%   |
| 5.11.16-zen1-1-zen  | 5         | 1.63%   |
| 5.11.11-zen1-1-zen  | 5         | 1.63%   |
| 5.18.6-zen1-1-zen   | 4         | 1.3%    |
| 5.18.1-zen1-1-zen   | 4         | 1.3%    |
| 5.17.3-zen1-1-zen   | 4         | 1.3%    |
| 5.16.2-zen1-1-zen   | 4         | 1.3%    |
| 5.16.16-zen1-1-zen  | 4         | 1.3%    |
| 5.15.6-zen2-1-zen   | 4         | 1.3%    |
| 5.10.4-107-tkg-bmq  | 4         | 1.3%    |
| 5.10.1-103-tkg-bmq  | 4         | 1.3%    |
| 5.9.10-zen1-1-zen   | 3         | 0.98%   |
| 5.9.1-zen2-1-zen    | 3         | 0.98%   |
| 5.18.3-zen1-1-zen   | 3         | 0.98%   |
| 5.18.14-zen1-1-zen  | 3         | 0.98%   |
| 5.18.12-zen1-1-zen  | 3         | 0.98%   |
| 5.17.5-zen1-1-zen   | 3         | 0.98%   |
| 5.16.5-zen1-1-zen   | 3         | 0.98%   |
| 5.16.14-zen1-1-zen  | 3         | 0.98%   |
| 5.16.11-zen1-1-zen  | 3         | 0.98%   |
| 5.15.5-zen1-1-zen   | 3         | 0.98%   |
| 5.15.10-zen1-1-zen  | 3         | 0.98%   |
| 5.14.6-zen1-1-zen   | 3         | 0.98%   |
| 5.14.15-zen1-1-zen  | 3         | 0.98%   |
| 5.10.8-112-tkg-bmq  | 3         | 0.98%   |
| 5.10.2-104-tkg-bmq  | 3         | 0.98%   |
| 5.10.15-120-tkg-bmq | 3         | 0.98%   |
| 5.10.10-115-tkg-bmq | 3         | 0.98%   |
| 5.9.8-zen1-1-zen    | 2         | 0.65%   |
| 5.9.2-zen1-1-zen    | 2         | 0.65%   |
| 5.9.11-zen2-1-zen   | 2         | 0.65%   |
| 5.8.14-zen1-1-zen   | 2         | 0.65%   |
| 5.18.5-zen1-1-zen   | 2         | 0.65%   |
| 5.16.9-zen1-1-zen   | 2         | 0.65%   |
| 5.16.8-zen1-1-zen   | 2         | 0.65%   |
| 5.16.8-arch1-1      | 2         | 0.65%   |
| 5.16.10-zen1-1-zen  | 2         | 0.65%   |
| 5.16.1-zen1-1-zen   | 2         | 0.65%   |
| 5.16.0-zen1-1-zen   | 2         | 0.65%   |
| 5.15.4-zen1-1-zen   | 2         | 0.65%   |
| 5.14.9-zen2-1-zen   | 2         | 0.65%   |
| 5.14.8-zen1-1-zen   | 2         | 0.65%   |
| 5.14.12-zen1-1-zen  | 2         | 0.65%   |
| 5.13.5-zen1-1-zen   | 2         | 0.65%   |
| 5.13.12-zen1-1-zen  | 2         | 0.65%   |
| 5.12.9-zen1-1-zen   | 2         | 0.65%   |
| 5.12.7-zen1-1-zen   | 2         | 0.65%   |
| 5.12.4-zen1-2-zen   | 2         | 0.65%   |
| 5.12.2-153-tkg-bmq  | 2         | 0.65%   |
| 5.12.15-zen1-1-zen  | 2         | 0.65%   |
| 5.12.14-zen1-1-zen  | 2         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 11        | 3.58%   |
| 5.15.2  | 7         | 2.28%   |
| 5.14.14 | 7         | 2.28%   |
| 5.17.9  | 6         | 1.95%   |
| 5.17.5  | 6         | 1.95%   |
| 5.17.3  | 6         | 1.95%   |
| 5.16.4  | 6         | 1.95%   |
| 5.15.7  | 6         | 1.95%   |
| 5.11.11 | 6         | 1.95%   |
| 5.10.4  | 6         | 1.95%   |
| 5.16.5  | 5         | 1.63%   |
| 5.16.2  | 5         | 1.63%   |
| 5.15.13 | 5         | 1.63%   |
| 5.15.12 | 5         | 1.63%   |
| 5.13.9  | 5         | 1.63%   |
| 5.13.13 | 5         | 1.63%   |
| 5.11.16 | 5         | 1.63%   |
| 5.18.6  | 4         | 1.3%    |
| 5.18.3  | 4         | 1.3%    |
| 5.18.1  | 4         | 1.3%    |
| 5.16.8  | 4         | 1.3%    |
| 5.16.16 | 4         | 1.3%    |
| 5.15.6  | 4         | 1.3%    |
| 5.15.5  | 4         | 1.3%    |
| 5.12.13 | 4         | 1.3%    |
| 5.10.15 | 4         | 1.3%    |
| 5.10.1  | 4         | 1.3%    |
| 5.9.10  | 3         | 0.98%   |
| 5.9.1   | 3         | 0.98%   |
| 5.18.5  | 3         | 0.98%   |
| 5.18.14 | 3         | 0.98%   |
| 5.18.12 | 3         | 0.98%   |
| 5.16.14 | 3         | 0.98%   |
| 5.16.11 | 3         | 0.98%   |
| 5.16.10 | 3         | 0.98%   |
| 5.16.0  | 3         | 0.98%   |
| 5.15.10 | 3         | 0.98%   |
| 5.14.6  | 3         | 0.98%   |
| 5.14.15 | 3         | 0.98%   |
| 5.14.12 | 3         | 0.98%   |
| 5.12.9  | 3         | 0.98%   |
| 5.12.12 | 3         | 0.98%   |
| 5.11.6  | 3         | 0.98%   |
| 5.10.8  | 3         | 0.98%   |
| 5.10.2  | 3         | 0.98%   |
| 5.10.10 | 3         | 0.98%   |
| 5.9.8   | 2         | 0.65%   |
| 5.9.2   | 2         | 0.65%   |
| 5.9.11  | 2         | 0.65%   |
| 5.8.14  | 2         | 0.65%   |
| 5.18.9  | 2         | 0.65%   |
| 5.16.9  | 2         | 0.65%   |
| 5.16.1  | 2         | 0.65%   |
| 5.15.4  | 2         | 0.65%   |
| 5.15.11 | 2         | 0.65%   |
| 5.14.9  | 2         | 0.65%   |
| 5.14.8  | 2         | 0.65%   |
| 5.14.5  | 2         | 0.65%   |
| 5.14.11 | 2         | 0.65%   |
| 5.13.5  | 2         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 45        | 15.25%  |
| 5.16    | 41        | 13.9%   |
| 5.10    | 36        | 12.2%   |
| 5.17    | 30        | 10.17%  |
| 5.18    | 28        | 9.49%   |
| 5.14    | 27        | 9.15%   |
| 5.12    | 23        | 7.8%    |
| 5.11    | 23        | 7.8%    |
| 5.13    | 21        | 7.12%   |
| 5.9     | 13        | 4.41%   |
| 5.8     | 5         | 1.69%   |
| 5.6     | 1         | 0.34%   |
| 5.4     | 1         | 0.34%   |
| 5.19    | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 267       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KDE5              | 167       | 61.85%  |
| GNOME             | 39        | 14.44%  |
| KDE               | 34        | 12.59%  |
| XFCE              | 10        | 3.7%    |
| X-Cinnamon        | 4         | 1.48%   |
| sway              | 4         | 1.48%   |
| Deepin            | 3         | 1.11%   |
| qtile-default     | 2         | 0.74%   |
| i3                | 2         | 0.74%   |
| Yaru:ubuntu:GNOME | 1         | 0.37%   |
| MATE              | 1         | 0.37%   |
| LXQt              | 1         | 0.37%   |
| Budgie            | 1         | 0.37%   |
| Unknown           | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 247       | 92.16%  |
| Wayland | 16        | 5.97%   |
| Tty     | 3         | 1.12%   |
| Unknown | 2         | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 133       | 49.63%  |
| Unknown | 96        | 35.82%  |
| LightDM | 20        | 7.46%   |
| GDM     | 16        | 5.97%   |
| GREETD  | 3         | 1.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 135       | 50.19%  |
| en_GB   | 30        | 11.15%  |
| de_DE   | 21        | 7.81%   |
| en_IN   | 14        | 5.2%    |
| it_IT   | 8         | 2.97%   |
| ru_RU   | 5         | 1.86%   |
| pt_BR   | 5         | 1.86%   |
| es_ES   | 5         | 1.86%   |
| en_CA   | 5         | 1.86%   |
| es_MX   | 4         | 1.49%   |
| en_AU   | 4         | 1.49%   |
| pl_PL   | 3         | 1.12%   |
| nl_NL   | 3         | 1.12%   |
| sv_SE   | 2         | 0.74%   |
| fr_FR   | 2         | 0.74%   |
| fr_BE   | 2         | 0.74%   |
| fi_FI   | 2         | 0.74%   |
| es_VE   | 2         | 0.74%   |
| es_CO   | 2         | 0.74%   |
| en_ZA   | 2         | 0.74%   |
| tr_TR   | 1         | 0.37%   |
| sk_SK   | 1         | 0.37%   |
| nb_NO   | 1         | 0.37%   |
| ko_KR   | 1         | 0.37%   |
| iu_CA   | 1         | 0.37%   |
| es_EC   | 1         | 0.37%   |
| es_AR   | 1         | 0.37%   |
| en_DK   | 1         | 0.37%   |
| en_DE   | 1         | 0.37%   |
| el_GR   | 1         | 0.37%   |
| de_AT   | 1         | 0.37%   |
| da_DK   | 1         | 0.37%   |
| Unknown | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 171       | 63.81%  |
| BIOS | 97        | 36.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 262       | 98.13%  |
| Overlay | 2         | 0.75%   |
| Ext4    | 2         | 0.75%   |
| F2fs    | 1         | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 161       | 60.07%  |
| Unknown | 94        | 35.07%  |
| MBR     | 13        | 4.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 233       | 85.98%  |
| Yes       | 38        | 14.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 67.78%  |
| Yes       | 87        | 32.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 48        | 17.98%  |
| Lenovo              | 43        | 16.1%   |
| Hewlett-Packard     | 36        | 13.48%  |
| MSI                 | 27        | 10.11%  |
| Dell                | 26        | 9.74%   |
| Gigabyte Technology | 19        | 7.12%   |
| Acer                | 15        | 5.62%   |
| ASRock              | 12        | 4.49%   |
| Apple               | 4         | 1.5%    |
| Samsung Electronics | 3         | 1.12%   |
| Razer               | 3         | 1.12%   |
| Notebook            | 3         | 1.12%   |
| Medion              | 3         | 1.12%   |
| Unknown             | 3         | 1.12%   |
| Toshiba             | 2         | 0.75%   |
| Pegatron            | 2         | 0.75%   |
| HUAWEI              | 2         | 0.75%   |
| Fujitsu             | 2         | 0.75%   |
| Alienware           | 2         | 0.75%   |
| T-bao               | 1         | 0.37%   |
| Sony                | 1         | 0.37%   |
| PC Specialist       | 1         | 0.37%   |
| Panasonic           | 1         | 0.37%   |
| OEM                 | 1         | 0.37%   |
| HONOR               | 1         | 0.37%   |
| GPU Company         | 1         | 0.37%   |
| Google              | 1         | 0.37%   |
| Fujitsu Siemens     | 1         | 0.37%   |
| Chuwi               | 1         | 0.37%   |
| Casper              | 1         | 0.37%   |
| Biostar             | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 5         | 1.87%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 4         | 1.5%    |
| ASUS TUF Gaming X570-PLUS                  | 3         | 1.12%   |
| MSI MS-7C91                                | 2         | 0.75%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 0.75%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 0.75%   |
| Gigabyte X570 AORUS PRO WIFI               | 2         | 0.75%   |
| Gigabyte AB350-Gaming 3                    | 2         | 0.75%   |
| Dell Inspiron 3668                         | 2         | 0.75%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 0.75%   |
| ASUS ROG STRIX X570-E GAMING               | 2         | 0.75%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 0.75%   |
| ASUS ROG Flow X13 GV301QH_GV301QH          | 2         | 0.75%   |
| ASUS All Series                            | 2         | 0.75%   |
| Acer Nitro AN515-44                        | 2         | 0.75%   |
| Toshiba Satellite E45DW-C                  | 1         | 0.37%   |
| Toshiba Satellite C55-A                    | 1         | 0.37%   |
| T-bao MINI PC                              | 1         | 0.37%   |
| Sony VPCSB1C5E                             | 1         | 0.37%   |
| Samsung 730QDA                             | 1         | 0.37%   |
| Samsung 550XCJ/550XCR                      | 1         | 0.37%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.37%   |
| Razer Blade 17 (Mid 2021) - RZ09-0406      | 1         | 0.37%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.37%   |
| Razer Blade                                | 1         | 0.37%   |
| Pegatron p7-1030                           | 1         | 0.37%   |
| Pegatron h9-1301es                         | 1         | 0.37%   |
| PC Specialist GK5NPFO                      | 1         | 0.37%   |
| Panasonic CF-191HYAX1M                     | 1         | 0.37%   |
| Notebook W54_W550SU2                       | 1         | 0.37%   |
| Notebook P7xxDM2(-G)                       | 1         | 0.37%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 0.37%   |
| MSI MS-7C90                                | 1         | 0.37%   |
| MSI MS-7C83                                | 1         | 0.37%   |
| MSI MS-7C56                                | 1         | 0.37%   |
| MSI MS-7C52                                | 1         | 0.37%   |
| MSI MS-7C09                                | 1         | 0.37%   |
| MSI MS-7C02                                | 1         | 0.37%   |
| MSI MS-7B98                                | 1         | 0.37%   |
| MSI MS-7B89                                | 1         | 0.37%   |
| MSI MS-7B86                                | 1         | 0.37%   |
| MSI MS-7B09                                | 1         | 0.37%   |
| MSI MS-7A78                                | 1         | 0.37%   |
| MSI MS-7A39                                | 1         | 0.37%   |
| MSI MS-7A38                                | 1         | 0.37%   |
| MSI MS-7A32                                | 1         | 0.37%   |
| MSI MS-7818                                | 1         | 0.37%   |
| MSI MS-7816                                | 1         | 0.37%   |
| MSI MS-7758                                | 1         | 0.37%   |
| MSI GS76 Stealth 11UG                      | 1         | 0.37%   |
| MSI GP75 Leopard 9SD                       | 1         | 0.37%   |
| MSI GF63 Thin 9SC                          | 1         | 0.37%   |
| MSI GF63 Thin 10SC                         | 1         | 0.37%   |
| MSI GE75 Raider 9SE                        | 1         | 0.37%   |
| MSI GE72VR 6RF                             | 1         | 0.37%   |
| MSI GE63 Raider RGB 8RE                    | 1         | 0.37%   |
| MSI A320M-HDV R4.0                         | 1         | 0.37%   |
| Medion P861X                               | 1         | 0.37%   |
| Medion E7419 MD60025                       | 1         | 0.37%   |
| Medion Akoya P5238 F/C395                  | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 14        | 5.24%   |
| ASUS ROG               | 13        | 4.87%   |
| Lenovo ThinkPad        | 12        | 4.49%   |
| HP Pavilion            | 11        | 4.12%   |
| Dell Inspiron          | 11        | 4.12%   |
| Dell Latitude          | 7         | 2.62%   |
| ASUS PRIME             | 7         | 2.62%   |
| Acer Aspire            | 7         | 2.62%   |
| Lenovo Legion          | 6         | 2.25%   |
| HP Laptop              | 5         | 1.87%   |
| ASUS TUF               | 5         | 1.87%   |
| Unknown                | 5         | 1.87%   |
| HP OMEN                | 4         | 1.5%    |
| Dell XPS               | 4         | 1.5%    |
| ASUS VivoBook          | 4         | 1.5%    |
| Acer Nitro             | 4         | 1.5%    |
| Razer Blade            | 3         | 1.12%   |
| Lenovo ThinkCentre     | 3         | 1.12%   |
| Gigabyte X570          | 3         | 1.12%   |
| Gigabyte B450          | 3         | 1.12%   |
| Toshiba Satellite      | 2         | 0.75%   |
| MSI MS-7C91            | 2         | 0.75%   |
| MSI GF63               | 2         | 0.75%   |
| Lenovo Yoga            | 2         | 0.75%   |
| HP ENVY                | 2         | 0.75%   |
| HP EliteBook           | 2         | 0.75%   |
| Gigabyte B550          | 2         | 0.75%   |
| Gigabyte AB350-Gaming  | 2         | 0.75%   |
| Dell OptiPlex          | 2         | 0.75%   |
| ASUS Maximus           | 2         | 0.75%   |
| ASUS ASUS              | 2         | 0.75%   |
| ASUS All               | 2         | 0.75%   |
| ASRock X470            | 2         | 0.75%   |
| Acer Swift             | 2         | 0.75%   |
| T-bao MINI             | 1         | 0.37%   |
| Sony VPCSB1C5E         | 1         | 0.37%   |
| Samsung 730QDA         | 1         | 0.37%   |
| Samsung 550XCJ         | 1         | 0.37%   |
| Samsung 300V3A         | 1         | 0.37%   |
| Pegatron p7-1030       | 1         | 0.37%   |
| Pegatron h9-1301es     | 1         | 0.37%   |
| PC Specialist GK5NPFO  | 1         | 0.37%   |
| Panasonic CF-191HYAX1M | 1         | 0.37%   |
| Notebook W54           | 1         | 0.37%   |
| Notebook P7xxDM2(-G)   | 1         | 0.37%   |
| Notebook N85           | 1         | 0.37%   |
| MSI MS-7C90            | 1         | 0.37%   |
| MSI MS-7C83            | 1         | 0.37%   |
| MSI MS-7C56            | 1         | 0.37%   |
| MSI MS-7C52            | 1         | 0.37%   |
| MSI MS-7C09            | 1         | 0.37%   |
| MSI MS-7C02            | 1         | 0.37%   |
| MSI MS-7B98            | 1         | 0.37%   |
| MSI MS-7B89            | 1         | 0.37%   |
| MSI MS-7B86            | 1         | 0.37%   |
| MSI MS-7B09            | 1         | 0.37%   |
| MSI MS-7A78            | 1         | 0.37%   |
| MSI MS-7A39            | 1         | 0.37%   |
| MSI MS-7A38            | 1         | 0.37%   |
| MSI MS-7A32            | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 51        | 19.1%   |
| 2021 | 35        | 13.11%  |
| 2019 | 33        | 12.36%  |
| 2018 | 27        | 10.11%  |
| 2017 | 27        | 10.11%  |
| 2013 | 17        | 6.37%   |
| 2014 | 16        | 5.99%   |
| 2016 | 15        | 5.62%   |
| 2012 | 15        | 5.62%   |
| 2011 | 10        | 3.75%   |
| 2015 | 6         | 2.25%   |
| 2010 | 6         | 2.25%   |
| 2009 | 4         | 1.5%    |
| 2008 | 2         | 0.75%   |
| 2007 | 2         | 0.75%   |
| 2022 | 1         | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 144       | 53.93%  |
| Desktop     | 108       | 40.45%  |
| Convertible | 9         | 3.37%   |
| All in one  | 4         | 1.5%    |
| Tablet      | 1         | 0.37%   |
| Mini pc     | 1         | 0.37%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 267       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 266       | 99.63%  |
| Yes  | 1         | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 73        | 27.14%  |
| 4.01-8.0    | 61        | 22.68%  |
| 8.01-16.0   | 58        | 21.56%  |
| 32.01-64.0  | 43        | 15.99%  |
| 3.01-4.0    | 15        | 5.58%   |
| 24.01-32.0  | 12        | 4.46%   |
| 64.01-256.0 | 6         | 2.23%   |
| 2.01-3.0    | 1         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 108       | 37.76%  |
| 3.01-4.0   | 64        | 22.38%  |
| 2.01-3.0   | 63        | 22.03%  |
| 8.01-16.0  | 30        | 10.49%  |
| 1.01-2.0   | 14        | 4.9%    |
| 16.01-24.0 | 5         | 1.75%   |
| 32.01-64.0 | 1         | 0.35%   |
| 0.51-1.0   | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 117       | 42.55%  |
| 2      | 80        | 29.09%  |
| 3      | 37        | 13.45%  |
| 4      | 22        | 8%      |
| 5      | 11        | 4%      |
| 6      | 4         | 1.45%   |
| 9      | 3         | 1.09%   |
| 14     | 1         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 201       | 74.17%  |
| Yes       | 70        | 25.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 226       | 84.33%  |
| No        | 42        | 15.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 221       | 81.55%  |
| No        | 50        | 18.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 197       | 72.96%  |
| No        | 73        | 27.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 82        | 30.48%  |
| Germany      | 30        | 11.15%  |
| UK           | 18        | 6.69%   |
| India        | 15        | 5.58%   |
| Italy        | 13        | 4.83%   |
| Canada       | 9         | 3.35%   |
| Poland       | 7         | 2.6%    |
| Russia       | 6         | 2.23%   |
| Romania      | 6         | 2.23%   |
| Netherlands  | 6         | 2.23%   |
| Mexico       | 6         | 2.23%   |
| Brazil       | 6         | 2.23%   |
| Sweden       | 5         | 1.86%   |
| Spain        | 5         | 1.86%   |
| France       | 4         | 1.49%   |
| Belgium      | 4         | 1.49%   |
| Australia    | 4         | 1.49%   |
| Finland      | 3         | 1.12%   |
| Denmark      | 3         | 1.12%   |
| Venezuela    | 2         | 0.74%   |
| Turkey       | 2         | 0.74%   |
| South Africa | 2         | 0.74%   |
| Puerto Rico  | 2         | 0.74%   |
| Latvia       | 2         | 0.74%   |
| Colombia     | 2         | 0.74%   |
| Ukraine      | 1         | 0.37%   |
| Switzerland  | 1         | 0.37%   |
| South Korea  | 1         | 0.37%   |
| Slovenia     | 1         | 0.37%   |
| Slovakia     | 1         | 0.37%   |
| Singapore    | 1         | 0.37%   |
| Serbia       | 1         | 0.37%   |
| Philippines  | 1         | 0.37%   |
| Oman         | 1         | 0.37%   |
| Norway       | 1         | 0.37%   |
| Luxembourg   | 1         | 0.37%   |
| Lithuania    | 1         | 0.37%   |
| Kuwait       | 1         | 0.37%   |
| Kenya        | 1         | 0.37%   |
| Indonesia    | 1         | 0.37%   |
| Iceland      | 1         | 0.37%   |
| Hungary      | 1         | 0.37%   |
| Greece       | 1         | 0.37%   |
| Ecuador      | 1         | 0.37%   |
| Czechia      | 1         | 0.37%   |
| China        | 1         | 0.37%   |
| Chile        | 1         | 0.37%   |
| Bahrain      | 1         | 0.37%   |
| Austria      | 1         | 0.37%   |
| Argentina    | 1         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| London                  | 5         | 1.79%   |
| Berlin                  | 4         | 1.43%   |
| San Jose                | 3         | 1.08%   |
| Portland                | 3         | 1.08%   |
| Milan                   | 3         | 1.08%   |
| Chicago                 | 3         | 1.08%   |
| Wasmes                  | 2         | 0.72%   |
| Warsaw                  | 2         | 0.72%   |
| Toronto                 | 2         | 0.72%   |
| Timișoara              | 2         | 0.72%   |
| Sydney                  | 2         | 0.72%   |
| Seattle                 | 2         | 0.72%   |
| Riga                    | 2         | 0.72%   |
| Pune                    | 2         | 0.72%   |
| Puebla City             | 2         | 0.72%   |
| Oklahoma City           | 2         | 0.72%   |
| Montreal                | 2         | 0.72%   |
| Melbourne               | 2         | 0.72%   |
| Kingsport               | 2         | 0.72%   |
| Helsinki                | 2         | 0.72%   |
| Hamburg                 | 2         | 0.72%   |
| Frankfurt am Main       | 2         | 0.72%   |
| Düsseldorf             | 2         | 0.72%   |
| Dortmund                | 2         | 0.72%   |
| Denver                  | 2         | 0.72%   |
| Delhi                   | 2         | 0.72%   |
| Dallas                  | 2         | 0.72%   |
| Copenhagen              | 2         | 0.72%   |
| Cologne                 | 2         | 0.72%   |
| Chennai                 | 2         | 0.72%   |
| Cape Town               | 2         | 0.72%   |
| Calenzano               | 2         | 0.72%   |
| Wroclaw                 | 1         | 0.36%   |
| Winston-Salem           | 1         | 0.36%   |
| Welwyn Garden City      | 1         | 0.36%   |
| Weiterstadt             | 1         | 0.36%   |
| Weilen unter den Rinnen | 1         | 0.36%   |
| Wasilla                 | 1         | 0.36%   |
| Voronezh                | 1         | 0.36%   |
| Volzhskiy               | 1         | 0.36%   |
| Vleuten                 | 1         | 0.36%   |
| Visakhapatnam           | 1         | 0.36%   |
| Västerås              | 1         | 0.36%   |
| Vancouver               | 1         | 0.36%   |
| Valencia                | 1         | 0.36%   |
| Valence                 | 1         | 0.36%   |
| Urbandale               | 1         | 0.36%   |
| Ullerslev               | 1         | 0.36%   |
| Turku                   | 1         | 0.36%   |
| Turin                   | 1         | 0.36%   |
| Tucson                  | 1         | 0.36%   |
| Taunusstein             | 1         | 0.36%   |
| Sunrise Beach           | 1         | 0.36%   |
| Stockholm               | 1         | 0.36%   |
| Steenwijk               | 1         | 0.36%   |
| Stavropol               | 1         | 0.36%   |
| Stanley                 | 1         | 0.36%   |
| St Louis                | 1         | 0.36%   |
| Sparks                  | 1         | 0.36%   |
| Southampton             | 1         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 86        | 148    | 17.27%  |
| Seagate                     | 75        | 105    | 15.06%  |
| WDC                         | 74        | 97     | 14.86%  |
| Toshiba                     | 29        | 33     | 5.82%   |
| SanDisk                     | 24        | 32     | 4.82%   |
| Crucial                     | 21        | 30     | 4.22%   |
| Kingston                    | 20        | 27     | 4.02%   |
| SK hynix                    | 18        | 21     | 3.61%   |
| Unknown                     | 13        | 13     | 2.61%   |
| Intel                       | 13        | 17     | 2.61%   |
| Hitachi                     | 11        | 11     | 2.21%   |
| HGST                        | 10        | 10     | 2.01%   |
| Phison                      | 9         | 10     | 1.81%   |
| A-DATA Technology           | 7         | 10     | 1.41%   |
| Silicon Motion              | 6         | 6      | 1.2%    |
| PNY                         | 6         | 6      | 1.2%    |
| SPCC                        | 5         | 5      | 1%      |
| Micron Technology           | 5         | 5      | 1%      |
| KIOXIA                      | 4         | 6      | 0.8%    |
| Corsair                     | 4         | 7      | 0.8%    |
| China                       | 4         | 6      | 0.8%    |
| XPG                         | 3         | 4      | 0.6%    |
| OCZ                         | 3         | 3      | 0.6%    |
| LITEON                      | 3         | 3      | 0.6%    |
| Union Memory (Shenzhen)     | 2         | 2      | 0.4%    |
| Transcend                   | 2         | 2      | 0.4%    |
| Team                        | 2         | 3      | 0.4%    |
| Mushkin                     | 2         | 2      | 0.4%    |
| Micron/Crucial Technology   | 2         | 3      | 0.4%    |
| LITEONIT                    | 2         | 2      | 0.4%    |
| Intenso                     | 2         | 3      | 0.4%    |
| Yangtze Memory Technologies | 1         | 1      | 0.2%    |
| WODPOSIT                    | 1         | 2      | 0.2%    |
| WDC WDS                     | 1         | 1      | 0.2%    |
| WD MediaMax                 | 1         | 1      | 0.2%    |
| VisionTek                   | 1         | 2      | 0.2%    |
| USB30                       | 1         | 2      | 0.2%    |
| UMIS                        | 1         | 2      | 0.2%    |
| TO Exter                    | 1         | 1      | 0.2%    |
| T-FORCE                     | 1         | 1      | 0.2%    |
| SSSTC                       | 1         | 1      | 0.2%    |
| ShanDianZhe                 | 1         | 1      | 0.2%    |
| SABRENT                     | 1         | 2      | 0.2%    |
| Qumo                        | 1         | 1      | 0.2%    |
| PNY CS90                    | 1         | 1      | 0.2%    |
| Plextor                     | 1         | 1      | 0.2%    |
| Phison Electronics          | 1         | 1      | 0.2%    |
| Patriot                     | 1         | 1      | 0.2%    |
| Netac                       | 1         | 1      | 0.2%    |
| Lenovo                      | 1         | 1      | 0.2%    |
| KIOXIA-EXCERIA              | 1         | 1      | 0.2%    |
| Inateck                     | 1         | 1      | 0.2%    |
| HS-SSD-E100                 | 1         | 1      | 0.2%    |
| Hewlett-Packard             | 1         | 1      | 0.2%    |
| FORESEE                     | 1         | 1      | 0.2%    |
| Emtec                       | 1         | 1      | 0.2%    |
| ASMT                        | 1         | 1      | 0.2%    |
| ASMedia                     | 1         | 2      | 0.2%    |
| Apple                       | 1         | 1      | 0.2%    |
| Apacer                      | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB           | 11        | 1.96%   |
| Seagate ST1000LM035-1RK172 1TB       | 7         | 1.25%   |
| Samsung SSD 970 EVO Plus 500GB       | 6         | 1.07%   |
| Samsung SSD 860 EVO 500GB            | 6         | 1.07%   |
| Samsung SSD 860 EVO 1TB              | 6         | 1.07%   |
| Samsung SSD 850 EVO 250GB            | 6         | 1.07%   |
| Crucial CT1000MX500SSD1 1TB          | 6         | 1.07%   |
| Seagate ST2000DM008-2FR102 2TB       | 5         | 0.89%   |
| Seagate ST1000LM049-2GH172 1TB       | 5         | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB       | 4         | 0.71%   |
| SanDisk SSD PLUS 1000GB              | 4         | 0.71%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 0.71%   |
| Samsung NVMe SSD Drive 1024GB        | 4         | 0.71%   |
| WDC WD10EZEX-60WN4A0 1TB             | 3         | 0.53%   |
| Toshiba MQ01ABD100 1TB               | 3         | 0.53%   |
| Toshiba DT01ACA100 1TB               | 3         | 0.53%   |
| SK hynix NVMe SSD Drive 512GB        | 3         | 0.53%   |
| Seagate ST4000DM004-2CV104 4TB       | 3         | 0.53%   |
| Seagate ST2000DL003-9VT166 2TB       | 3         | 0.53%   |
| Seagate Portable 2TB                 | 3         | 0.53%   |
| SanDisk NVMe SSD Drive 512GB         | 3         | 0.53%   |
| SanDisk NVMe SSD Drive 500GB         | 3         | 0.53%   |
| SanDisk NVMe SSD Drive 1TB           | 3         | 0.53%   |
| Samsung SSD 970 EVO 250GB            | 3         | 0.53%   |
| Samsung SSD 870 EVO 500GB            | 3         | 0.53%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.53%   |
| Samsung SSD 850 EVO 500GB            | 3         | 0.53%   |
| PNY ELITE PSSD 480GB                 | 3         | 0.53%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 0.53%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.53%   |
| XPG NVMe SSD Drive 512GB             | 2         | 0.36%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 2         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.36%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.36%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 2         | 0.36%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 2         | 0.36%   |
| WDC WD20EARX-00PASB0 2TB             | 2         | 0.36%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.36%   |
| WDC WD10EZEX-00BN5A0 1TB             | 2         | 0.36%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 2         | 0.36%   |
| Unknown MMC Card  16GB               | 2         | 0.36%   |
| Toshiba HDWD110 1TB                  | 2         | 0.36%   |
| Toshiba DT01ACA300 3TB               | 2         | 0.36%   |
| SPCC Solid State Disk 512GB          | 2         | 0.36%   |
| SK hynix SC311 SATA 256GB SSD        | 2         | 0.36%   |
| SK hynix NVMe SSD Drive 256GB        | 2         | 0.36%   |
| Seagate ST3320820AS 320GB            | 2         | 0.36%   |
| Seagate ST3000DM001-1ER166 3TB       | 2         | 0.36%   |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 0.36%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 2         | 0.36%   |
| Seagate ST2000DM001-1ER164 2TB       | 2         | 0.36%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.36%   |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.36%   |
| Seagate Expansion Desk 4TB           | 2         | 0.36%   |
| Seagate Expansion 1TB                | 2         | 0.36%   |
| Seagate Backup+ Hub BK 4TB           | 2         | 0.36%   |
| Samsung SSD 980 PRO 500GB            | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 100    | 42.6%   |
| WDC                 | 47        | 66     | 27.81%  |
| Toshiba             | 20        | 23     | 11.83%  |
| Hitachi             | 11        | 11     | 6.51%   |
| HGST                | 10        | 10     | 5.92%   |
| Samsung Electronics | 4         | 4      | 2.37%   |
| Unknown             | 1         | 1      | 0.59%   |
| SABRENT             | 1         | 2      | 0.59%   |
| Intenso             | 1         | 2      | 0.59%   |
| ASMT                | 1         | 1      | 0.59%   |
| Apple               | 1         | 1      | 0.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 42        | 60     | 26.92%  |
| Kingston            | 16        | 22     | 10.26%  |
| Crucial             | 16        | 23     | 10.26%  |
| SanDisk             | 12        | 19     | 7.69%   |
| WDC                 | 10        | 11     | 6.41%   |
| A-DATA Technology   | 7         | 10     | 4.49%   |
| PNY                 | 5         | 5      | 3.21%   |
| SPCC                | 4         | 4      | 2.56%   |
| SK hynix            | 4         | 5      | 2.56%   |
| China               | 4         | 6      | 2.56%   |
| Toshiba             | 3         | 4      | 1.92%   |
| OCZ                 | 3         | 3      | 1.92%   |
| LITEON              | 3         | 3      | 1.92%   |
| Transcend           | 2         | 2      | 1.28%   |
| Team                | 2         | 3      | 1.28%   |
| Mushkin             | 2         | 2      | 1.28%   |
| LITEONIT            | 2         | 2      | 1.28%   |
| WODPOSIT            | 1         | 2      | 0.64%   |
| WDC WDS             | 1         | 1      | 0.64%   |
| VisionTek           | 1         | 2      | 0.64%   |
| USB30               | 1         | 2      | 0.64%   |
| Unknown             | 1         | 1      | 0.64%   |
| TO Exter            | 1         | 1      | 0.64%   |
| T-FORCE             | 1         | 1      | 0.64%   |
| Qumo                | 1         | 1      | 0.64%   |
| PNY CS90            | 1         | 1      | 0.64%   |
| Plextor             | 1         | 1      | 0.64%   |
| Netac               | 1         | 1      | 0.64%   |
| Micron Technology   | 1         | 1      | 0.64%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.64%   |
| Intenso             | 1         | 1      | 0.64%   |
| Inateck             | 1         | 1      | 0.64%   |
| FORESEE             | 1         | 1      | 0.64%   |
| Emtec               | 1         | 1      | 0.64%   |
| Corsair             | 1         | 1      | 0.64%   |
| ASMedia             | 1         | 2      | 0.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 143       | 220    | 33.89%  |
| HDD     | 133       | 221    | 31.52%  |
| SSD     | 124       | 207    | 29.38%  |
| MMC     | 11        | 11     | 2.61%   |
| Unknown | 11        | 11     | 2.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 186       | 391    | 50.27%  |
| NVMe | 143       | 220    | 38.65%  |
| SAS  | 30        | 48     | 8.11%   |
| MMC  | 11        | 11     | 2.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 122       | 193    | 40.94%  |
| 0.51-1.0   | 108       | 140    | 36.24%  |
| 1.01-2.0   | 39        | 56     | 13.09%  |
| 3.01-4.0   | 13        | 15     | 4.36%   |
| 2.01-3.0   | 9         | 15     | 3.02%   |
| 4.01-10.0  | 5         | 6      | 1.68%   |
| 10.01-20.0 | 2         | 3      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 110       | 40.44%  |
| 1001-2000      | 57        | 20.96%  |
| 501-1000       | 41        | 15.07%  |
| 2001-3000      | 33        | 12.13%  |
| 251-500        | 14        | 5.15%   |
| Unknown        | 10        | 3.68%   |
| 1-20           | 4         | 1.47%   |
| 101-250        | 3         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 62        | 21.91%  |
| 251-500        | 54        | 19.08%  |
| 501-1000       | 42        | 14.84%  |
| 1001-2000      | 40        | 14.13%  |
| 51-100         | 31        | 10.95%  |
| 2001-3000      | 19        | 6.71%   |
| More than 3000 | 17        | 6.01%   |
| Unknown        | 10        | 3.53%   |
| 1-20           | 5         | 1.77%   |
| 21-50          | 3         | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60A0RT0 500GB          | 1         | 1      | 3.33%   |
| WDC WD5000AAKS-00E4A0 500GB           | 1         | 1      | 3.33%   |
| WDC WD30EZRX-00DC0B0 3TB              | 1         | 1      | 3.33%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 3.33%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1         | 1      | 3.33%   |
| WDC WD10EADS-22M2B0 1TB               | 1         | 1      | 3.33%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 3.33%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 3.33%   |
| Seagate ST4000DM004-2CV104 4TB        | 1         | 1      | 3.33%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 1         | 1      | 3.33%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 3.33%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 3.33%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 3.33%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 980 1TB       | 1         | 3      | 3.33%   |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 5      | 3.33%   |
| OCZ TRION100 480GB SSD                | 1         | 1      | 3.33%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 3.33%   |
| Kingston SH103S3240G 240GB SSD        | 1         | 1      | 3.33%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 3.33%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 3.33%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 3.33%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 3.33%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 3.33%   |
| HGST HTS541075A9E680 752GB            | 1         | 1      | 3.33%   |
| Hewlett-Packard SSD EX900 500GB       | 1         | 1      | 3.33%   |
| Crucial CT960M500SSD1 960GB           | 1         | 1      | 3.33%   |
| Apple HDD HTS545050A7E362 500GB       | 1         | 1      | 3.33%   |
| A-DATA Technology SU800 1TB SSD       | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 24.14%  |
| Seagate             | 7         | 7      | 24.14%  |
| Hitachi             | 3         | 3      | 10.34%  |
| HGST                | 3         | 3      | 10.34%  |
| Kingston            | 2         | 2      | 6.9%    |
| SanDisk             | 1         | 1      | 3.45%   |
| Samsung Electronics | 1         | 8      | 3.45%   |
| OCZ                 | 1         | 1      | 3.45%   |
| Hewlett-Packard     | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 7      | 33.33%  |
| Seagate | 7         | 7      | 33.33%  |
| Hitachi | 3         | 3      | 14.29%  |
| HGST    | 3         | 3      | 14.29%  |
| Apple   | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 21     | 71.43%  |
| SSD  | 6         | 6      | 21.43%  |
| NVMe | 2         | 9      | 7.14%   |

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
| Works    | 148       | 314    | 47.13%  |
| Detected | 139       | 320    | 44.27%  |
| Malfunc  | 27        | 36     | 8.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 149       | 38.21%  |
| AMD                            | 85        | 21.79%  |
| Samsung Electronics            | 48        | 12.31%  |
| SanDisk                        | 28        | 7.18%   |
| SK hynix                       | 14        | 3.59%   |
| Phison Electronics             | 14        | 3.59%   |
| Silicon Motion                 | 8         | 2.05%   |
| Micron/Crucial Technology      | 6         | 1.54%   |
| Toshiba America Info Systems   | 5         | 1.28%   |
| Kingston Technology Company    | 5         | 1.28%   |
| ASMedia Technology             | 5         | 1.28%   |
| Union Memory (Shenzhen)        | 4         | 1.03%   |
| Micron Technology              | 3         | 0.77%   |
| Marvell Technology Group       | 3         | 0.77%   |
| KIOXIA                         | 3         | 0.77%   |
| JMicron Technology             | 2         | 0.51%   |
| ADATA Technology               | 2         | 0.51%   |
| Yangtze Memory Technologies    | 1         | 0.26%   |
| Solid State Storage Technology | 1         | 0.26%   |
| Shenzhen Longsys Electronics   | 1         | 0.26%   |
| Realtek Semiconductor          | 1         | 0.26%   |
| Nvidia                         | 1         | 0.26%   |
| Lenovo                         | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 61        | 13.77%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 38        | 8.58%   |
| AMD 400 Series Chipset SATA Controller                                         | 17        | 3.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 3.61%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 12        | 2.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 2.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 2.71%   |
| AMD 500 Series Chipset SATA Controller                                         | 12        | 2.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 2.48%   |
| Phison E12 NVMe Controller                                                     | 10        | 2.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 1.81%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 6         | 1.35%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 1.35%   |
| Intel SSD 660P Series                                                          | 6         | 1.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.35%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 1.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 1.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 5         | 1.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.13%   |
| Intel Non-Volatile memory controller                                           | 5         | 1.13%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.13%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.13%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 4         | 0.9%    |
| SK hynix Gold P31 SSD                                                          | 4         | 0.9%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 4         | 0.9%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 0.9%    |
| SanDisk Non-Volatile memory controller                                         | 4         | 0.9%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 4         | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 0.9%    |
| AMD 300 Series Chipset SATA Controller                                         | 4         | 0.9%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.68%   |
| Micron Non-Volatile memory controller                                          | 3         | 0.68%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 0.68%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 0.68%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 0.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.68%   |
| AMD X399 Series Chipset SATA Controller                                        | 3         | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.45%   |
| SK hynix BC511                                                                 | 2         | 0.45%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 0.45%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.45%   |
| Phison NVMe Storage Controller                                                 | 2         | 0.45%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.45%   |
| Micron/Crucial NVMe Controller                                                 | 2         | 0.45%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 2         | 0.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.45%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.45%   |
| Intel PROSet/Wireless WiFi Software extension                                  | 2         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 200       | 52.91%  |
| NVMe | 142       | 37.57%  |
| RAID | 23        | 6.08%   |
| IDE  | 13        | 3.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 160       | 59.93%  |
| AMD    | 107       | 40.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 3%      |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 3%      |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 2.25%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.87%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.87%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 1.87%   |
| AMD Ryzen 5 3600 6-Core Processor             | 5         | 1.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.5%    |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 1.12%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.12%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 1.12%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 3         | 1.12%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.12%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 1.12%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.12%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2         | 0.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.75%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.75%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.75%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.75%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2         | 0.75%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.75%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 0.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.75%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 2         | 0.75%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.75%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 0.75%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 2         | 0.75%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.75%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 0.75%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 2         | 0.75%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2         | 0.75%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.75%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 0.75%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.75%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 0.75%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 0.75%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2         | 0.75%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2         | 0.75%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 0.75%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 0.75%   |
| Intel Xeon CPU W3550 @ 3.07GHz                | 1         | 0.37%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz           | 1         | 0.37%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 0.37%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.37%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.37%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.37%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.37%   |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.37%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.37%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.37%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.37%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 60        | 22.47%  |
| Intel Core i5           | 48        | 17.98%  |
| AMD Ryzen 7             | 36        | 13.48%  |
| AMD Ryzen 5             | 33        | 12.36%  |
| Intel Core i3           | 21        | 7.87%   |
| Other                   | 12        | 4.49%   |
| AMD Ryzen 9             | 10        | 3.75%   |
| Intel Celeron           | 7         | 2.62%   |
| AMD Ryzen 3             | 6         | 2.25%   |
| Intel Xeon              | 3         | 1.12%   |
| AMD Ryzen Threadripper  | 3         | 1.12%   |
| AMD FX                  | 3         | 1.12%   |
| AMD A8                  | 3         | 1.12%   |
| Intel Pentium Silver    | 2         | 0.75%   |
| Intel Pentium Dual-Core | 2         | 0.75%   |
| Intel Pentium           | 2         | 0.75%   |
| Intel Core 2 Duo        | 2         | 0.75%   |
| AMD Ryzen 7 PRO         | 2         | 0.75%   |
| AMD A4                  | 2         | 0.75%   |
| AMD A10                 | 2         | 0.75%   |
| Intel Core m3           | 1         | 0.37%   |
| Intel Core i9           | 1         | 0.37%   |
| Intel Core 2 Quad       | 1         | 0.37%   |
| AMD Turion              | 1         | 0.37%   |
| AMD Phenom II X6        | 1         | 0.37%   |
| AMD Phenom II X4        | 1         | 0.37%   |
| AMD Phenom II X2        | 1         | 0.37%   |
| AMD A6                  | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 93        | 34.83%  |
| 2      | 71        | 26.59%  |
| 6      | 50        | 18.73%  |
| 8      | 42        | 15.73%  |
| 12     | 5         | 1.87%   |
| 16     | 4         | 1.5%    |
| 24     | 1         | 0.37%   |
| 10     | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 267       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 217       | 81.27%  |
| 1      | 50        | 18.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 267       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 111       | 40.66%  |
| 0x306a9    | 13        | 4.76%   |
| 0x306c3    | 11        | 4.03%   |
| 0x906ea    | 9         | 3.3%    |
| 0x206a7    | 8         | 2.93%   |
| 0x08701021 | 8         | 2.93%   |
| 0x0a50000c | 7         | 2.56%   |
| 0x08108109 | 7         | 2.56%   |
| 0x906e9    | 6         | 2.2%    |
| 0x0800820d | 6         | 2.2%    |
| 0xa0652    | 5         | 1.83%   |
| 0x806c1    | 5         | 1.83%   |
| 0x08600106 | 5         | 1.83%   |
| 0x506e3    | 4         | 1.47%   |
| 0x08600103 | 4         | 1.47%   |
| 0x806e9    | 3         | 1.1%    |
| 0x406e3    | 3         | 1.1%    |
| 0x08608103 | 3         | 1.1%    |
| 0x08600104 | 3         | 1.1%    |
| 0x08108102 | 3         | 1.1%    |
| 0x806ec    | 2         | 0.73%   |
| 0x806ea    | 2         | 0.73%   |
| 0x40651    | 2         | 0.73%   |
| 0x106e5    | 2         | 0.73%   |
| 0x1067a    | 2         | 0.73%   |
| 0x0a50000b | 2         | 0.73%   |
| 0x0810100b | 2         | 0.73%   |
| 0x08101007 | 2         | 0.73%   |
| 0x08001137 | 2         | 0.73%   |
| 0x06006705 | 2         | 0.73%   |
| 0xa0660    | 1         | 0.37%   |
| 0xa0655    | 1         | 0.37%   |
| 0xa0653    | 1         | 0.37%   |
| 0x906ed    | 1         | 0.37%   |
| 0x906ec    | 1         | 0.37%   |
| 0x906eb    | 1         | 0.37%   |
| 0x806d1    | 1         | 0.37%   |
| 0x706e5    | 1         | 0.37%   |
| 0x706a8    | 1         | 0.37%   |
| 0x706a1    | 1         | 0.37%   |
| 0x506c9    | 1         | 0.37%   |
| 0x406c4    | 1         | 0.37%   |
| 0x306d4    | 1         | 0.37%   |
| 0x20655    | 1         | 0.37%   |
| 0x106a5    | 1         | 0.37%   |
| 0x10676    | 1         | 0.37%   |
| 0x0a201204 | 1         | 0.37%   |
| 0x0a201016 | 1         | 0.37%   |
| 0x0a201009 | 1         | 0.37%   |
| 0x08701013 | 1         | 0.37%   |
| 0x08101016 | 1         | 0.37%   |
| 0x07030106 | 1         | 0.37%   |
| 0x07030105 | 1         | 0.37%   |
| 0x0700010f | 1         | 0.37%   |
| 0x06006110 | 1         | 0.37%   |
| 0x06003106 | 1         | 0.37%   |
| 0x06000852 | 1         | 0.37%   |
| 0x010000dc | 1         | 0.37%   |
| 0x00000000 | 1         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 47        | 17.6%   |
| Zen 2           | 33        | 12.36%  |
| Zen+            | 22        | 8.24%   |
| Zen 3           | 22        | 8.24%   |
| Haswell         | 21        | 7.87%   |
| IvyBridge       | 18        | 6.74%   |
| CometLake       | 15        | 5.62%   |
| SandyBridge     | 14        | 5.24%   |
| Skylake         | 11        | 4.12%   |
| Zen             | 10        | 3.75%   |
| TigerLake       | 7         | 2.62%   |
| Penryn          | 5         | 1.87%   |
| Broadwell       | 5         | 1.87%   |
| Unknown         | 5         | 1.87%   |
| Puma            | 4         | 1.5%    |
| Silvermont      | 3         | 1.12%   |
| Piledriver      | 3         | 1.12%   |
| Nehalem         | 3         | 1.12%   |
| K10             | 3         | 1.12%   |
| IceLake         | 3         | 1.12%   |
| Goldmont plus   | 3         | 1.12%   |
| Excavator       | 3         | 1.12%   |
| Westmere        | 2         | 0.75%   |
| Steamroller     | 2         | 0.75%   |
| K8 & K10 hybrid | 1         | 0.37%   |
| Jaguar          | 1         | 0.37%   |
| Goldmont        | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 125       | 36.02%  |
| Intel  | 122       | 35.16%  |
| AMD    | 100       | 28.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 16        | 4.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 3.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 3.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.81%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 2.81%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10        | 2.81%   |
| AMD Cezanne                                                                              | 10        | 2.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 2.25%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 2.25%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.97%   |
| Intel HD Graphics 630                                                                    | 7         | 1.97%   |
| Nvidia TU117M                                                                            | 6         | 1.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 1.69%   |
| Intel HD Graphics 620                                                                    | 6         | 1.69%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 1.4%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 1.4%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 1.4%    |
| Intel UHD Graphics 620                                                                   | 5         | 1.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.4%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 5         | 1.4%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.4%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5         | 1.4%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 1.12%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 4         | 1.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.12%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 4         | 1.12%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 3         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.84%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3         | 0.84%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3         | 0.84%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 3         | 0.84%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.84%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 3         | 0.84%   |
| Intel HD Graphics 5500                                                                   | 3         | 0.84%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3         | 0.84%   |
| AMD Lucienne                                                                             | 3         | 0.84%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2         | 0.56%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.56%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.56%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.56%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2         | 0.56%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 0.56%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.56%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.56%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 2         | 0.56%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2         | 0.56%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.56%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2         | 0.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.56%   |
| Intel HD Graphics 530                                                                    | 2         | 0.56%   |
| Intel HD Graphics 510                                                                    | 2         | 0.56%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 71        | 26.59%  |
| 1 x Intel          | 65        | 24.34%  |
| 1 x Nvidia         | 55        | 20.6%   |
| Intel + Nvidia     | 44        | 16.48%  |
| AMD + Nvidia       | 22        | 8.24%   |
| Intel + AMD        | 4         | 1.5%    |
| 2 x Nvidia         | 2         | 0.75%   |
| 2 x AMD            | 2         | 0.75%   |
| Intel + 2 x Nvidia | 2         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 166       | 61.71%  |
| Proprietary | 103       | 38.29%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 146       | 53.09%  |
| 0.01-0.5   | 32        | 11.64%  |
| 1.01-2.0   | 26        | 9.45%   |
| 7.01-8.0   | 23        | 8.36%   |
| 3.01-4.0   | 17        | 6.18%   |
| 5.01-6.0   | 11        | 4%      |
| 0.51-1.0   | 10        | 3.64%   |
| 8.01-16.0  | 7         | 2.55%   |
| 2.01-3.0   | 2         | 0.73%   |
| 16.01-24.0 | 1         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 39        | 11.85%  |
| AU Optronics            | 37        | 11.25%  |
| BOE                     | 27        | 8.21%   |
| LG Display              | 26        | 7.9%    |
| Chimei Innolux          | 23        | 6.99%   |
| Dell                    | 20        | 6.08%   |
| Acer                    | 18        | 5.47%   |
| Goldstar                | 14        | 4.26%   |
| AOC                     | 12        | 3.65%   |
| Hewlett-Packard         | 11        | 3.34%   |
| Sharp                   | 10        | 3.04%   |
| BenQ                    | 10        | 3.04%   |
| PANDA                   | 9         | 2.74%   |
| Ancor Communications    | 8         | 2.43%   |
| Unknown                 | 6         | 1.82%   |
| Lenovo                  | 5         | 1.52%   |
| ASUSTek Computer        | 5         | 1.52%   |
| Sony                    | 4         | 1.22%   |
| Philips                 | 4         | 1.22%   |
| MSI                     | 3         | 0.91%   |
| Gigabyte Technology     | 3         | 0.91%   |
| Apple                   | 3         | 0.91%   |
| Vizio                   | 2         | 0.61%   |
| NEC Computers           | 2         | 0.61%   |
| Mi                      | 2         | 0.61%   |
| InfoVision              | 2         | 0.61%   |
| Iiyama                  | 2         | 0.61%   |
| CSO                     | 2         | 0.61%   |
| ViewSonic               | 1         | 0.3%    |
| Toshiba                 | 1         | 0.3%    |
| ONN                     | 1         | 0.3%    |
| MStar                   | 1         | 0.3%    |
| MiTAC                   | 1         | 0.3%    |
| Microstep               | 1         | 0.3%    |
| LTM                     | 1         | 0.3%    |
| LG Electronics          | 1         | 0.3%    |
| Lenovo Group Limited    | 1         | 0.3%    |
| Insignia                | 1         | 0.3%    |
| HPN                     | 1         | 0.3%    |
| HKC                     | 1         | 0.3%    |
| G-Story                 | 1         | 0.3%    |
| Fujitsu Siemens         | 1         | 0.3%    |
| Element                 | 1         | 0.3%    |
| Eizo                    | 1         | 0.3%    |
| CPT                     | 1         | 0.3%    |
| Chi Mei Optoelectronics | 1         | 0.3%    |
| AOpen                   | 1         | 0.3%    |
| Alba                    | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 4         | 1.17%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 3         | 0.88%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 2         | 0.59%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch   | 2         | 0.59%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.59%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 2         | 0.59%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 2         | 0.59%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch           | 2         | 0.59%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                | 2         | 0.59%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.59%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 0.59%   |
| Dell 1909W DELA03C 1440x900 410x260mm 19.1-inch                        | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch       | 2         | 0.59%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                  | 2         | 0.59%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 2         | 0.59%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                  | 2         | 0.59%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                  | 2         | 0.59%   |
| BOE LCD Monitor BOE0610 1920x1080 344x193mm 15.5-inch                  | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch         | 2         | 0.59%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2         | 0.59%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2         | 0.59%   |
| Acer XB271HU ACR0490 2560x1440 598x336mm 27.0-inch                     | 2         | 0.59%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2         | 0.59%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1         | 0.29%   |
| Vizio E320-A0 VIZ0095 1366x768 697x392mm 31.5-inch                     | 1         | 0.29%   |
| ViewSonic VX2270 SERIES VSCE02C 1920x1080 476x267mm 21.5-inch          | 1         | 0.29%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1         | 0.29%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1         | 0.29%   |
| Unknown LCD Monitor SAMSUNG                                            | 1         | 0.29%   |
| Unknown LCD Monitor RJT HDMI                                           | 1         | 0.29%   |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1         | 0.29%   |
| Unknown LCD Monitor Hitachi/HINT W240D DVI                             | 1         | 0.29%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                       | 1         | 0.29%   |
| Sony TV SNYA301 1920x1080                                              | 1         | 0.29%   |
| Sony TV SNY1802 1920x1080                                              | 1         | 0.29%   |
| Sony TV SNY0801 1360x768                                               | 1         | 0.29%   |
| Sony TV *30 SNYB905 3840x2160 952x535mm 43.0-inch                      | 1         | 0.29%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                | 1         | 0.29%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch                | 1         | 0.29%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.29%   |
| Sharp LQ133T1JW17 SHP1409 2560x1440 294x165mm 13.3-inch                | 1         | 0.29%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.29%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.29%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                | 1         | 0.29%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.29%   |
| Samsung Electronics U28E850 SAM0CCB 3840x2160 607x345mm 27.5-inch      | 1         | 0.29%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1         | 0.29%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 1         | 0.29%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 480x270mm 21.7-inch      | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                       | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM04D5 1920x540                        | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM00BB 1280x1024 376x301mm 19.0-inch   | 1         | 0.29%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 530x300mm 24.0-inch   | 1         | 0.29%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch      | 1         | 0.29%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch    | 1         | 0.29%   |
| Samsung Electronics S24E450 SAM0CA0 1920x1080 531x299mm 24.0-inch      | 1         | 0.29%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 160       | 51.45%  |
| 1366x768 (WXGA)    | 29        | 9.32%   |
| 3840x2160 (4K)     | 25        | 8.04%   |
| 2560x1440 (QHD)    | 13        | 4.18%   |
| 1600x900 (HD+)     | 13        | 4.18%   |
| Unknown            | 9         | 2.89%   |
| 1680x1050 (WSXGA+) | 8         | 2.57%   |
| 3440x1440          | 7         | 2.25%   |
| 3840x1080          | 5         | 1.61%   |
| 1920x1200 (WUXGA)  | 5         | 1.61%   |
| 2560x1600          | 4         | 1.29%   |
| 2560x1080          | 4         | 1.29%   |
| 1440x900 (WXGA+)   | 4         | 1.29%   |
| 1280x1024 (SXGA)   | 4         | 1.29%   |
| 7680x2160          | 2         | 0.64%   |
| 2256x1504          | 2         | 0.64%   |
| 1360x768           | 2         | 0.64%   |
| 1280x800 (WXGA)    | 2         | 0.64%   |
| 9600x2160          | 1         | 0.32%   |
| 4480x1440          | 1         | 0.32%   |
| 3840x2400          | 1         | 0.32%   |
| 3840x1200          | 1         | 0.32%   |
| 3200x1800 (QHD+)   | 1         | 0.32%   |
| 2880x1440          | 1         | 0.32%   |
| 2736x1824          | 1         | 0.32%   |
| 2160x1440          | 1         | 0.32%   |
| 2048x1152          | 1         | 0.32%   |
| 1920x540           | 1         | 0.32%   |
| 1680x945           | 1         | 0.32%   |
| 1600x1200          | 1         | 0.32%   |
| 1280x720 (HD)      | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 87        | 27.27%  |
| 27      | 34        | 10.66%  |
| 24      | 26        | 8.15%   |
| Unknown | 24        | 7.52%   |
| 14      | 22        | 6.9%    |
| 13      | 21        | 6.58%   |
| 23      | 19        | 5.96%   |
| 17      | 12        | 3.76%   |
| 21      | 9         | 2.82%   |
| 19      | 8         | 2.51%   |
| 34      | 7         | 2.19%   |
| 22      | 7         | 2.19%   |
| 31      | 5         | 1.57%   |
| 20      | 5         | 1.57%   |
| 72      | 4         | 1.25%   |
| 16      | 4         | 1.25%   |
| 49      | 3         | 0.94%   |
| 40      | 3         | 0.94%   |
| 18      | 3         | 0.94%   |
| 54      | 2         | 0.63%   |
| 43      | 2         | 0.63%   |
| 28      | 2         | 0.63%   |
| 12      | 2         | 0.63%   |
| 85      | 1         | 0.31%   |
| 52      | 1         | 0.31%   |
| 48      | 1         | 0.31%   |
| 47      | 1         | 0.31%   |
| 33      | 1         | 0.31%   |
| 32      | 1         | 0.31%   |
| 25      | 1         | 0.31%   |
| 11      | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 119       | 38.02%  |
| 501-600     | 70        | 22.36%  |
| 401-500     | 28        | 8.95%   |
| Unknown     | 24        | 7.67%   |
| 201-300     | 17        | 5.43%   |
| 351-400     | 16        | 5.11%   |
| 601-700     | 12        | 3.83%   |
| 701-800     | 9         | 2.88%   |
| 1001-1500   | 8         | 2.56%   |
| 1501-2000   | 5         | 1.6%    |
| 801-900     | 3         | 0.96%   |
| 901-1000    | 2         | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 217       | 75.87%  |
| 16/10   | 28        | 9.79%   |
| Unknown | 20        | 6.99%   |
| 21/9    | 8         | 2.8%    |
| 5/4     | 4         | 1.4%    |
| 3/2     | 4         | 1.4%    |
| 32/9    | 3         | 1.05%   |
| 4/3     | 1         | 0.35%   |
| 2.00    | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 88        | 28.12%  |
| 201-250        | 48        | 15.34%  |
| 301-350        | 34        | 10.86%  |
| 81-90          | 33        | 10.54%  |
| Unknown        | 24        | 7.67%   |
| 351-500        | 15        | 4.79%   |
| 151-200        | 13        | 4.15%   |
| 121-130        | 11        | 3.51%   |
| More than 1000 | 10        | 3.19%   |
| 71-80          | 10        | 3.19%   |
| 251-300        | 9         | 2.88%   |
| 501-1000       | 8         | 2.56%   |
| 141-150        | 4         | 1.28%   |
| 61-70          | 2         | 0.64%   |
| 111-120        | 2         | 0.64%   |
| 51-60          | 1         | 0.32%   |
| 91-100         | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 99        | 33%     |
| 51-100        | 87        | 29%     |
| 101-120       | 55        | 18.33%  |
| Unknown       | 24        | 8%      |
| 161-240       | 17        | 5.67%   |
| 1-50          | 10        | 3.33%   |
| More than 240 | 8         | 2.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 189       | 69.74%  |
| 2     | 68        | 25.09%  |
| 3     | 10        | 3.69%   |
| 0     | 4         | 1.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 162       | 38.3%   |
| Intel                             | 139       | 32.86%  |
| Qualcomm Atheros                  | 46        | 10.87%  |
| Broadcom                          | 15        | 3.55%   |
| MediaTek                          | 7         | 1.65%   |
| TP-Link                           | 6         | 1.42%   |
| Ralink Technology                 | 6         | 1.42%   |
| NetGear                           | 5         | 1.18%   |
| Samsung Electronics               | 3         | 0.71%   |
| Microsoft                         | 3         | 0.71%   |
| Linksys                           | 3         | 0.71%   |
| Aquantia                          | 3         | 0.71%   |
| Ralink                            | 2         | 0.47%   |
| Qualcomm                          | 2         | 0.47%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.47%   |
| DisplayLink                       | 2         | 0.47%   |
| ASUSTek Computer                  | 2         | 0.47%   |
| ASIX Electronics                  | 2         | 0.47%   |
| Xiaomi                            | 1         | 0.24%   |
| Wacom                             | 1         | 0.24%   |
| Sierra Wireless                   | 1         | 0.24%   |
| Nvidia                            | 1         | 0.24%   |
| Lenovo                            | 1         | 0.24%   |
| InterBiometrics                   | 1         | 0.24%   |
| Holtek Semiconductor              | 1         | 0.24%   |
| Ericsson Business Mobile Networks | 1         | 0.24%   |
| Dell                              | 1         | 0.24%   |
| Broadcom Limited                  | 1         | 0.24%   |
| Belkin Components                 | 1         | 0.24%   |
| Alteon Networks                   | 1         | 0.24%   |
| Accton Technology                 | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 113       | 22.97%  |
| Intel Wi-Fi 6 AX200                                                 | 26        | 5.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 15        | 3.05%   |
| Intel I211 Gigabit Network Connection                               | 15        | 3.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 11        | 2.24%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 10        | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 10        | 2.03%   |
| Realtek RTL8125 2.5GbE Controller                                   | 9         | 1.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 9         | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 8         | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 8         | 1.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 7         | 1.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 6         | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 6         | 1.22%   |
| Intel Wireless-AC 9260                                              | 6         | 1.22%   |
| Intel Wireless 8265 / 8275                                          | 6         | 1.22%   |
| Intel Wireless 7265                                                 | 6         | 1.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 6         | 1.22%   |
| Intel Ethernet Controller I225-V                                    | 6         | 1.22%   |
| Intel Ethernet Connection I217-LM                                   | 6         | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6         | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 5         | 1.02%   |
| Intel Wireless 3165                                                 | 5         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 5         | 1.02%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 4         | 0.81%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 4         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 4         | 0.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 4         | 0.81%   |
| Intel Wireless 7260                                                 | 4         | 0.81%   |
| Intel Wi-Fi 6 AX201                                                 | 4         | 0.81%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 3         | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 3         | 0.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 3         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3         | 0.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 3         | 0.61%   |
| Intel Wireless 8260                                                 | 3         | 0.61%   |
| Intel Ethernet Connection I219-LM                                   | 3         | 0.61%   |
| Intel Ethernet Connection (2) I219-V                                | 3         | 0.61%   |
| Intel Centrino Advanced-N 6200                                      | 3         | 0.61%   |
| Intel 82577LM Gigabit Network Connection                            | 3         | 0.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 2         | 0.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 2         | 0.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2         | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 2         | 0.41%   |
| Ralink MT7601U Wireless Adapter                                     | 2         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2         | 0.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2         | 0.41%   |
| OnePlus (Shenzhen) OnePlus                                          | 2         | 0.41%   |
| NetGear A6210                                                       | 2         | 0.41%   |
| Microsoft XBOX ACC                                                  | 2         | 0.41%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2         | 0.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection       | 2         | 0.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 2         | 0.41%   |
| Intel Ethernet Connection I217-V                                    | 2         | 0.41%   |
| Intel Ethernet Connection (4) I219-LM                               | 2         | 0.41%   |
| Intel Ethernet Connection (3) I218-LM                               | 2         | 0.41%   |
| Intel Centrino Ultimate-N 6300                                      | 2         | 0.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 113       | 47.28%  |
| Realtek Semiconductor | 46        | 19.25%  |
| Qualcomm Atheros      | 33        | 13.81%  |
| Broadcom              | 11        | 4.6%    |
| Ralink Technology     | 6         | 2.51%   |
| TP-Link               | 5         | 2.09%   |
| NetGear               | 5         | 2.09%   |
| MediaTek              | 5         | 2.09%   |
| Microsoft             | 3         | 1.26%   |
| Linksys               | 3         | 1.26%   |
| Ralink                | 2         | 0.84%   |
| ASUSTek Computer      | 2         | 0.84%   |
| Wacom                 | 1         | 0.42%   |
| Sierra Wireless       | 1         | 0.42%   |
| Dell                  | 1         | 0.42%   |
| Broadcom Limited      | 1         | 0.42%   |
| Accton Technology     | 1         | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 26        | 10.79%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 15        | 6.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 11        | 4.56%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 10        | 4.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 8         | 3.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 8         | 3.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 7         | 2.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 6         | 2.49%   |
| Intel Wireless-AC 9260                                                    | 6         | 2.49%   |
| Intel Wireless 8265 / 8275                                                | 6         | 2.49%   |
| Intel Wireless 7265                                                       | 6         | 2.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 6         | 2.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 6         | 2.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 5         | 2.07%   |
| Intel Wireless 3165                                                       | 5         | 2.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 5         | 2.07%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 4         | 1.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 4         | 1.66%   |
| Intel Wireless 7260                                                       | 4         | 1.66%   |
| Intel Wi-Fi 6 AX201                                                       | 4         | 1.66%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 3         | 1.24%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                  | 3         | 1.24%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3         | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 3         | 1.24%   |
| Intel Wireless 8260                                                       | 3         | 1.24%   |
| Intel Centrino Advanced-N 6200                                            | 3         | 1.24%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 2         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 2         | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 2         | 0.83%   |
| Ralink MT7601U Wireless Adapter                                           | 2         | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 0.83%   |
| NetGear A6210                                                             | 2         | 0.83%   |
| Microsoft XBOX ACC                                                        | 2         | 0.83%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]       | 2         | 0.83%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection             | 2         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 2         | 0.83%   |
| Intel Centrino Ultimate-N 6300                                            | 2         | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 2         | 0.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 2         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                       | 2         | 0.83%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                  | 1         | 0.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 1         | 0.41%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1         | 0.41%   |
| Sierra Wireless EM7455                                                    | 1         | 0.41%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1         | 0.41%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 0.41%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 0.41%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1         | 0.41%   |
| Realtek RTL8191SEvB Wireless LAN Controller                               | 1         | 0.41%   |
| Realtek RTL8191SEvA Wireless LAN Controller                               | 1         | 0.41%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                    | 1         | 0.41%   |
| Realtek 802.11n WLAN Adapter                                              | 1         | 0.41%   |
| Ralink Wireless Adapter Canyon CN-WF511                                   | 1         | 0.41%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                         | 1         | 0.41%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1         | 0.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 0.41%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1         | 0.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 0.41%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1         | 0.41%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 141       | 57.55%  |
| Intel                         | 58        | 23.67%  |
| Qualcomm Atheros              | 18        | 7.35%   |
| Broadcom                      | 7         | 2.86%   |
| Samsung Electronics           | 3         | 1.22%   |
| Aquantia                      | 3         | 1.22%   |
| Qualcomm                      | 2         | 0.82%   |
| MediaTek                      | 2         | 0.82%   |
| DisplayLink                   | 2         | 0.82%   |
| ASIX Electronics              | 2         | 0.82%   |
| Xiaomi                        | 1         | 0.41%   |
| TP-Link                       | 1         | 0.41%   |
| OnePlus Technology (Shenzhen) | 1         | 0.41%   |
| Nvidia                        | 1         | 0.41%   |
| Lenovo                        | 1         | 0.41%   |
| Belkin Components             | 1         | 0.41%   |
| Alteon Networks               | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 113       | 45.75%  |
| Intel I211 Gigabit Network Connection                               | 15        | 6.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 10        | 4.05%   |
| Realtek RTL8125 2.5GbE Controller                                   | 9         | 3.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 9         | 3.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 6         | 2.43%   |
| Intel Ethernet Controller I225-V                                    | 6         | 2.43%   |
| Intel Ethernet Connection I217-LM                                   | 6         | 2.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 4         | 1.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 4         | 1.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 3         | 1.21%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3         | 1.21%   |
| Intel Ethernet Connection I219-LM                                   | 3         | 1.21%   |
| Intel Ethernet Connection (2) I219-V                                | 3         | 1.21%   |
| Intel 82577LM Gigabit Network Connection                            | 3         | 1.21%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 2         | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2         | 0.81%   |
| Intel Ethernet Connection I217-V                                    | 2         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                               | 2         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                               | 2         | 0.81%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 2         | 0.81%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express              | 2         | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                       | 2         | 0.81%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1         | 0.4%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                       | 1         | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1         | 0.4%    |
| Realtek Killer E3000 2.5GbE Controller                              | 1         | 0.4%    |
| Qualcomm BENGAL-QRD _SN:C5464635                                    | 1         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                              | 1         | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1         | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1         | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1         | 0.4%    |
| Qualcomm Android                                                    | 1         | 0.4%    |
| OnePlus (Shenzhen) OnePlus                                          | 1         | 0.4%    |
| Nvidia MCP79 Ethernet                                               | 1         | 0.4%    |
| MediaTek RMX3085                                                    | 1         | 0.4%    |
| MediaTek moto e(6) plus                                             | 1         | 0.4%    |
| Lenovo ThinkPad Lan                                                 | 1         | 0.4%    |
| Intel Ethernet Connection (7) I219-V                                | 1         | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                               | 1         | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                               | 1         | 0.4%    |
| Intel Ethernet Connection (2) I218-V                                | 1         | 0.4%    |
| Intel Ethernet Connection (10) I219-V                               | 1         | 0.4%    |
| Intel 82579V Gigabit Network Connection                             | 1         | 0.4%    |
| DisplayLink ThinkPad USB 3.0 Dock                                   | 1         | 0.4%    |
| DisplayLink Dell D1000 USB3.0 Dock                                  | 1         | 0.4%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                   | 1         | 0.4%    |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express             | 1         | 0.4%    |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                     | 1         | 0.4%    |
| Belkin Components F5D5050 100Mbps Ethernet                          | 1         | 0.4%    |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.4%    |
| Alteon Networks Ethernet controller                                 | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 225       | 50.11%  |
| WiFi     | 220       | 49%     |
| Modem    | 2         | 0.45%   |
| Unknown  | 2         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 162       | 59.78%  |
| Ethernet | 109       | 40.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 148       | 55.22%  |
| 1     | 108       | 40.3%   |
| 3     | 8         | 2.99%   |
| 0     | 3         | 1.12%   |
| 4     | 1         | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 208       | 76.75%  |
| Yes  | 63        | 23.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 96        | 48.24%  |
| Realtek Semiconductor           | 29        | 14.57%  |
| Qualcomm Atheros Communications | 23        | 11.56%  |
| IMC Networks                    | 11        | 5.53%   |
| Cambridge Silicon Radio         | 10        | 5.03%   |
| Broadcom                        | 6         | 3.02%   |
| Lite-On Technology              | 5         | 2.51%   |
| Foxconn / Hon Hai               | 4         | 2.01%   |
| ASUSTek Computer                | 4         | 2.01%   |
| Apple                           | 4         | 2.01%   |
| Hewlett-Packard                 | 2         | 1.01%   |
| Dell                            | 2         | 1.01%   |
| Realtek                         | 1         | 0.5%    |
| Edimax Technology               | 1         | 0.5%    |
| Dynex                           | 1         | 0.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                               | 26        | 13.07%  |
| Intel Bluetooth wireless interface                                                  | 20        | 10.05%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 17        | 8.54%   |
| Intel AX201 Bluetooth                                                               | 16        | 8.04%   |
| Realtek Bluetooth Radio                                                             | 15        | 7.54%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 14        | 7.04%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 11        | 5.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 5.03%   |
| Intel Bluetooth Device                                                              | 7         | 3.52%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 3.02%   |
| Intel AX210 Bluetooth                                                               | 5         | 2.51%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 2.51%   |
| IMC Networks Wireless_Device                                                        | 4         | 2.01%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.51%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.51%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.01%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.01%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.01%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.01%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.01%   |
| ASUS Bluetooth Radio                                                                | 2         | 1.01%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.5%    |
| Realtek Bluetooth Radio                                                             | 1         | 0.5%    |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.5%    |
| Lite-On Bluetooth Device                                                            | 1         | 0.5%    |
| IMC Networks Bluetooth Device                                                       | 1         | 0.5%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.5%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.5%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.5%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.5%    |
| Edimax Bluetooth Adapter                                                            | 1         | 0.5%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.5%    |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.5%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.5%    |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.5%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.5%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.5%    |
| Broadcom BCM2045A0                                                                  | 1         | 0.5%    |
| ASUS Qualcomm Bluetooth 4.1                                                         | 1         | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.5%    |
| Apple Bluetooth Host Controller                                                     | 1         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 159       | 37.77%  |
| AMD                       | 116       | 27.55%  |
| Nvidia                    | 88        | 20.9%   |
| C-Media Electronics       | 10        | 2.38%   |
| Logitech                  | 8         | 1.9%    |
| Sony                      | 3         | 0.71%   |
| Sennheiser Communications | 2         | 0.48%   |
| RODE Microphones          | 2         | 0.48%   |
| Kingston Technology       | 2         | 0.48%   |
| JMTek                     | 2         | 0.48%   |
| Generalplus Technology    | 2         | 0.48%   |
| Creative Technology       | 2         | 0.48%   |
| Creative Labs             | 2         | 0.48%   |
| Corsair                   | 2         | 0.48%   |
| Blue Microphones          | 2         | 0.48%   |
| Yamaha                    | 1         | 0.24%   |
| Turtle Beach              | 1         | 0.24%   |
| Trust                     | 1         | 0.24%   |
| Texas Instruments         | 1         | 0.24%   |
| Tenx Technology           | 1         | 0.24%   |
| SteelSeries ApS           | 1         | 0.24%   |
| ROCCAT                    | 1         | 0.24%   |
| Realtek Semiconductor     | 1         | 0.24%   |
| Plantronics               | 1         | 0.24%   |
| Phison Electronics        | 1         | 0.24%   |
| Jieli Technology          | 1         | 0.24%   |
| Huawei Technologies       | 1         | 0.24%   |
| Hewlett-Packard           | 1         | 0.24%   |
| GN Netcom                 | 1         | 0.24%   |
| Focusrite-Novation        | 1         | 0.24%   |
| EVGA                      | 1         | 0.24%   |
| DigiTech                  | 1         | 0.24%   |
| Audio-Technica            | 1         | 0.24%   |
| Alesis                    | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 48        | 9.28%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 27        | 5.22%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 3.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 3.68%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 3.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 16        | 3.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 2.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 2.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 13        | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 2.32%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 2.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 10        | 1.93%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 9         | 1.74%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 1.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 1.55%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 8         | 1.55%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 7         | 1.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 1.35%   |
| Intel 200 Series PCH HD Audio                                                                     | 7         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.35%   |
| AMD FCH Azalia Controller                                                                         | 7         | 1.35%   |
| Nvidia TU104 HD Audio Controller                                                                  | 6         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.16%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.16%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 0.97%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 0.97%   |
| C-Media Electronics USB Audio Device                                                              | 5         | 0.97%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                        | 5         | 0.97%   |
| AMD Navi 10 HDMI Audio                                                                            | 5         | 0.97%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 0.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 0.77%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 0.77%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 0.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 0.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.58%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.58%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 3         | 0.58%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.58%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 0.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.58%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 2         | 0.39%   |
| RODE Microphones RODE NT-USB                                                                      | 2         | 0.39%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.39%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 0.39%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.39%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.39%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.39%   |
| Logitech G933 Wireless Headset Dongle                                                             | 2         | 0.39%   |
| JMTek USB PnP Audio Device                                                                        | 2         | 0.39%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 50        | 24.39%  |
| SK hynix            | 31        | 15.12%  |
| Micron Technology   | 19        | 9.27%   |
| G.Skill             | 18        | 8.78%   |
| Crucial             | 18        | 8.78%   |
| Corsair             | 14        | 6.83%   |
| Kingston            | 12        | 5.85%   |
| Unknown             | 7         | 3.41%   |
| Patriot             | 7         | 3.41%   |
| Ramaxel Technology  | 6         | 2.93%   |
| Team                | 4         | 1.95%   |
| A-DATA Technology   | 4         | 1.95%   |
| Nanya Technology    | 3         | 1.46%   |
| Unknown (ABCD)      | 2         | 0.98%   |
| Timetec             | 2         | 0.98%   |
| Smart               | 2         | 0.98%   |
| Transcend           | 1         | 0.49%   |
| Elpida              | 1         | 0.49%   |
| CSX                 | 1         | 0.49%   |
| Avant               | 1         | 0.49%   |
| Apacer              | 1         | 0.49%   |
| 48spaces            | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 6         | 2.71%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 2.26%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 2.26%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 2.26%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 5         | 2.26%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 4         | 1.81%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.36%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.36%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 3         | 1.36%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s            | 3         | 1.36%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 0.9%    |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 2         | 0.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.9%    |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 2         | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.9%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.9%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.9%    |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.9%    |
| Patriot RAM 2666 C16 Series 16384MB DIMM DDR4 2667MT/s           | 2         | 0.9%    |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 2         | 0.9%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.9%    |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 2         | 0.9%    |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.9%    |
| Corsair RAM CMK32GX4M4B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 0.9%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 0.9%    |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                             | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.45%   |
| Unknown RAM Module 1GB DIMM 1066MT/s                             | 1         | 0.45%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 0.45%   |
| Transcend RAM JM2666HSE-16G 16384MB SODIMM DDR4 2667MT/s         | 1         | 0.45%   |
| Timetec RAM SD4-3200 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.45%   |
| Timetec RAM SD3-1866 8GB SODIMM DDR3 1866MT/s                    | 1         | 0.45%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s               | 1         | 0.45%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s              | 1         | 0.45%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s               | 1         | 0.45%   |
| Team RAM TEAMGROUP-SD4-2133 8GB SODIMM DDR4 2133MT/s             | 1         | 0.45%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 0.45%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB DDR4 2667MT/s                   | 1         | 0.45%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1333MT/s             | 1         | 0.45%   |
| SK hynix RAM HMT451S6MFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.45%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.45%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.45%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.45%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.45%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.45%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.45%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.45%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.45%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s     | 1         | 0.45%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s        | 1         | 0.45%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.45%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.45%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.45%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 116       | 66.29%  |
| DDR3    | 45        | 25.71%  |
| LPDDR4  | 6         | 3.43%   |
| LPDDR3  | 3         | 1.71%   |
| Unknown | 3         | 1.71%   |
| DDR2    | 2         | 1.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 108       | 60.67%  |
| DIMM         | 55        | 30.9%   |
| Row Of Chips | 13        | 7.3%    |
| Chip         | 1         | 0.56%   |
| Unknown      | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 101       | 52.06%  |
| 4096  | 51        | 26.29%  |
| 16384 | 32        | 16.49%  |
| 2048  | 6         | 3.09%   |
| 32768 | 3         | 1.55%   |
| 1024  | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 48        | 24.62%  |
| 2667  | 34        | 17.44%  |
| 1600  | 34        | 17.44%  |
| 2400  | 17        | 8.72%   |
| 3600  | 15        | 7.69%   |
| 2133  | 5         | 2.56%   |
| 3466  | 4         | 2.05%   |
| 3266  | 4         | 2.05%   |
| 1334  | 4         | 2.05%   |
| 4266  | 3         | 1.54%   |
| 2666  | 3         | 1.54%   |
| 1333  | 3         | 1.54%   |
| 3866  | 2         | 1.03%   |
| 1867  | 2         | 1.03%   |
| 1866  | 2         | 1.03%   |
| 1800  | 2         | 1.03%   |
| 800   | 2         | 1.03%   |
| 8400  | 1         | 0.51%   |
| 4267  | 1         | 0.51%   |
| 4200  | 1         | 0.51%   |
| 4000  | 1         | 0.51%   |
| 3733  | 1         | 0.51%   |
| 3067  | 1         | 0.51%   |
| 2933  | 1         | 0.51%   |
| 2200  | 1         | 0.51%   |
| 1200  | 1         | 0.51%   |
| 1066  | 1         | 0.51%   |
| 667   | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


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

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 38        | 22.62%  |
| IMC Networks                           | 20        | 11.9%   |
| Logitech                               | 16        | 9.52%   |
| Microdia                               | 12        | 7.14%   |
| Realtek Semiconductor                  | 11        | 6.55%   |
| Acer                                   | 10        | 5.95%   |
| Quanta                                 | 8         | 4.76%   |
| Sunplus Innovation Technology          | 7         | 4.17%   |
| Syntek                                 | 6         | 3.57%   |
| Microsoft                              | 6         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.98%   |
| Luxvisions Innotech Limited            | 4         | 2.38%   |
| Apple                                  | 4         | 2.38%   |
| Suyin                                  | 3         | 1.79%   |
| Lite-On Technology                     | 3         | 1.79%   |
| Silicon Motion                         | 2         | 1.19%   |
| Jieli Technology                       | 2         | 1.19%   |
| Z-Star Microelectronics                | 1         | 0.6%    |
| WaveRider Communications               | 1         | 0.6%    |
| Unknown                                | 1         | 0.6%    |
| Sonix Technology                       | 1         | 0.6%    |
| Samsung Electronics                    | 1         | 0.6%    |
| Razer USA                              | 1         | 0.6%    |
| MacroSilicon                           | 1         | 0.6%    |
| Lenovo                                 | 1         | 0.6%    |
| Importek                               | 1         | 0.6%    |
| Genesys Logic                          | 1         | 0.6%    |
| Creative Technology                    | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 9         | 5.33%   |
| Microdia Integrated_Webcam_HD                       | 7         | 4.14%   |
| IMC Networks Integrated Camera                      | 7         | 4.14%   |
| Chicony Integrated Camera                           | 7         | 4.14%   |
| Chicony HD WebCam                                   | 6         | 3.55%   |
| Syntek Integrated Camera                            | 5         | 2.96%   |
| Chicony HP Wide Vision HD Camera                    | 4         | 2.37%   |
| Chicony HD User Facing                              | 4         | 2.37%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 1.78%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 1.78%   |
| Logitech Webcam C270                                | 3         | 1.78%   |
| Lite-On HP Wide Vision HD Camera                    | 3         | 1.78%   |
| Acer HD Webcam                                      | 3         | 1.78%   |
| Quanta HP Wide Vision HD Camera                     | 2         | 1.18%   |
| Microsoft LifeCam HD-5000                           | 2         | 1.18%   |
| Microsoft LifeCam HD-3000                           | 2         | 1.18%   |
| Microdia Amcrest AWC2198 USB Webcam                 | 2         | 1.18%   |
| Logitech Webcam C930e                               | 2         | 1.18%   |
| Logitech HD Webcam C910                             | 2         | 1.18%   |
| Logitech HD Pro Webcam C920                         | 2         | 1.18%   |
| Logitech C922 Pro Stream Webcam                     | 2         | 1.18%   |
| Logitech BRIO Ultra HD Webcam                       | 2         | 1.18%   |
| Jieli USB PHY 2.0                                   | 2         | 1.18%   |
| IMC Networks HD Camera                              | 2         | 1.18%   |
| Chicony USB 2.0 Camera                              | 2         | 1.18%   |
| Chicony HP Truevision HD                            | 2         | 1.18%   |
| Chicony EasyCamera                                  | 2         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 1.18%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 1.18%   |
| Acer Integrated Camera                              | 2         | 1.18%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 0.59%   |
| WaveRider USB Live camera                           | 1         | 0.59%   |
| Unknown 720p HD Camera                              | 1         | 0.59%   |
| Syntek EasyCamera                                   | 1         | 0.59%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.59%   |
| Suyin HP Integrated Webcam                          | 1         | 0.59%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.59%   |
| Sunplus USB Camera                                  | 1         | 0.59%   |
| Sunplus Lenovo EasyCamera                           | 1         | 0.59%   |
| Sunplus Integrated Webcam                           | 1         | 0.59%   |
| Sunplus Integrated Camera                           | 1         | 0.59%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.59%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 0.59%   |
| Silicon Motion Web Camera                           | 1         | 0.59%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.59%   |
| Realtek USB Camera                                  | 1         | 0.59%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.59%   |
| Realtek Integrated_Webcam_HD                        | 1         | 0.59%   |
| Realtek Integrated Webcam                           | 1         | 0.59%   |
| Realtek HP "Truevision HD" laptop camera            | 1         | 0.59%   |
| Realtek HD WebCam                                   | 1         | 0.59%   |
| Realtek FULL HD 1080P Webcam                        | 1         | 0.59%   |
| Realtek FJ Camera                                   | 1         | 0.59%   |
| Realtek EasyCamera                                  | 1         | 0.59%   |
| Realtek Built-In Video Camera                       | 1         | 0.59%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 0.59%   |
| Razer USA Razer Kiyo Pro                            | 1         | 0.59%   |
| Quanta WEBCAM                                       | 1         | 0.59%   |
| Quanta USB2.0 VGA UVC WebCam                        | 1         | 0.59%   |
| Quanta USB HD Webcam                                | 1         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 24.24%  |
| Synaptics                  | 8         | 24.24%  |
| Shenzhen Goodix Technology | 5         | 15.15%  |
| Elan Microelectronics      | 5         | 15.15%  |
| LighTuning Technology      | 3         | 9.09%   |
| AuthenTec                  | 2         | 6.06%   |
| Samsung Electronics        | 1         | 3.03%   |
| Focal-systems.Corp         | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 4         | 12.12%  |
| Shenzhen Goodix  FingerPrint Device               | 3         | 9.09%   |
| Elan ELAN:ARM-M4                                  | 3         | 9.09%   |
| Validity Sensors Synaptics WBDI                   | 2         | 6.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 2         | 6.06%   |
| Elan ELAN:Fingerprint                             | 2         | 6.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 3.03%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 3.03%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 3.03%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 3.03%   |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 3.03%   |
| Validity Sensors Fingerprint scanner              | 1         | 3.03%   |
| Synaptics WBDI Device                             | 1         | 3.03%   |
| Synaptics  WBDI Fingerprint Reader - USB 052      | 1         | 3.03%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 3.03%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 3.03%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 3.03%   |
| Shenzhen Goodix FingerPrint                       | 1         | 3.03%   |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 3.03%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 3.03%   |
| Focal-systems.Corp FT9201Fingerprint.             | 1         | 3.03%   |
| AuthenTec AES2810                                 | 1         | 3.03%   |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


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

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 127       | 46.69%  |
| 0     | 92        | 33.82%  |
| 2     | 45        | 16.54%  |
| 3     | 7         | 2.57%   |
| 4     | 1         | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 147       | 60.74%  |
| Fingerprint reader       | 33        | 13.64%  |
| Net/wireless             | 15        | 6.2%    |
| Graphics card            | 13        | 5.37%   |
| Chipcard                 | 12        | 4.96%   |
| Net/ethernet             | 7         | 2.89%   |
| Camera                   | 5         | 2.07%   |
| Multimedia controller    | 4         | 1.65%   |
| Storage                  | 2         | 0.83%   |
| Wireless                 | 1         | 0.41%   |
| Unassigned class         | 1         | 0.41%   |
| Network                  | 1         | 0.41%   |
| Bluetooth                | 1         | 0.41%   |

