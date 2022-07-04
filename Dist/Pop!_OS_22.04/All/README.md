Pop!_OS 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS_22.04/Desktop/README.md) and [notebooks](/Dist/Pop!_OS_22.04/Notebook/README.md).

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

Total: 700

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [7da3547526](https://linux-hardware.org/?probe=7da3547526) | Jul 01, 2022 |
| Dell          | Precision M4600             | Notebook    | [ea07b9e45f](https://linux-hardware.org/?probe=ea07b9e45f) | Jul 01, 2022 |
| Dell          | Precision M4600             | Notebook    | [535d6029bc](https://linux-hardware.org/?probe=535d6029bc) | Jul 01, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [10ff366630](https://linux-hardware.org/?probe=10ff366630) | Jul 01, 2022 |
| Samsung       | 930XED                      | Notebook    | [56a04fa69d](https://linux-hardware.org/?probe=56a04fa69d) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d979555615](https://linux-hardware.org/?probe=d979555615) | Jul 01, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| Dell          | Precision 5530              | Notebook    | [d6dc0ecd91](https://linux-hardware.org/?probe=d6dc0ecd91) | Jul 01, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [2bdfc5f472](https://linux-hardware.org/?probe=2bdfc5f472) | Jul 01, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [b48e88849b](https://linux-hardware.org/?probe=b48e88849b) | Jul 01, 2022 |
| Dell          | Precision 5550              | Notebook    | [0ddb8905e5](https://linux-hardware.org/?probe=0ddb8905e5) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [63508059d3](https://linux-hardware.org/?probe=63508059d3) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [b7aef43e9e](https://linux-hardware.org/?probe=b7aef43e9e) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [8c29343495](https://linux-hardware.org/?probe=8c29343495) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [2631bf2ae1](https://linux-hardware.org/?probe=2631bf2ae1) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [325fec2ac6](https://linux-hardware.org/?probe=325fec2ac6) | Jul 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e35e3b2e52](https://linux-hardware.org/?probe=e35e3b2e52) | Jul 01, 2022 |
| HP            | 18E7                        | Desktop     | [1808b6dee4](https://linux-hardware.org/?probe=1808b6dee4) | Jul 01, 2022 |
| Dell          | Precision 7510              | Notebook    | [c82cc3cb0f](https://linux-hardware.org/?probe=c82cc3cb0f) | Jul 01, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [c2a91cc81e](https://linux-hardware.org/?probe=c2a91cc81e) | Jul 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ccb50bd0f4](https://linux-hardware.org/?probe=ccb50bd0f4) | Jun 30, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [ab31abf1d5](https://linux-hardware.org/?probe=ab31abf1d5) | Jun 30, 2022 |
| HP            | Pavilion 15                 | Notebook    | [f76f8dff7a](https://linux-hardware.org/?probe=f76f8dff7a) | Jun 30, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [41255f7150](https://linux-hardware.org/?probe=41255f7150) | Jun 30, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6095915fb5](https://linux-hardware.org/?probe=6095915fb5) | Jun 30, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [35ca7c4868](https://linux-hardware.org/?probe=35ca7c4868) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1f66ba5535](https://linux-hardware.org/?probe=1f66ba5535) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [b85b1f9277](https://linux-hardware.org/?probe=b85b1f9277) | Jun 30, 2022 |
| Notebook      | P7xxDM3(-G)                 | Notebook    | [6abdc9b40d](https://linux-hardware.org/?probe=6abdc9b40d) | Jun 29, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [67dc174a62](https://linux-hardware.org/?probe=67dc174a62) | Jun 29, 2022 |
| Dell          | Latitude E5470              | Notebook    | [2440e59a5a](https://linux-hardware.org/?probe=2440e59a5a) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | Desktop     | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | Desktop     | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [c5e8b7f098](https://linux-hardware.org/?probe=c5e8b7f098) | Jun 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [f01192b57e](https://linux-hardware.org/?probe=f01192b57e) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [0a66ce61c6](https://linux-hardware.org/?probe=0a66ce61c6) | Jun 29, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [6d403c021c](https://linux-hardware.org/?probe=6d403c021c) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [f2b790de57](https://linux-hardware.org/?probe=f2b790de57) | Jun 29, 2022 |
| Eluktronic... | MECH-15 G3                  | Notebook    | [d307b13800](https://linux-hardware.org/?probe=d307b13800) | Jun 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c14a32dd6b](https://linux-hardware.org/?probe=c14a32dd6b) | Jun 28, 2022 |
| HP            | 3647h                       | Desktop     | [3227f38f98](https://linux-hardware.org/?probe=3227f38f98) | Jun 28, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [8efb1d3556](https://linux-hardware.org/?probe=8efb1d3556) | Jun 28, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [93807824df](https://linux-hardware.org/?probe=93807824df) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [5b239d8bba](https://linux-hardware.org/?probe=5b239d8bba) | Jun 28, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [843cbccc63](https://linux-hardware.org/?probe=843cbccc63) | Jun 27, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [6ecc609381](https://linux-hardware.org/?probe=6ecc609381) | Jun 27, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8e17cfd388](https://linux-hardware.org/?probe=8e17cfd388) | Jun 26, 2022 |
| ASUSTek       | VM40B                       | Desktop     | [35f67bace1](https://linux-hardware.org/?probe=35f67bace1) | Jun 26, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [fd65f44d25](https://linux-hardware.org/?probe=fd65f44d25) | Jun 26, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [6580b51e30](https://linux-hardware.org/?probe=6580b51e30) | Jun 25, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [01fcd4495e](https://linux-hardware.org/?probe=01fcd4495e) | Jun 25, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [02721926a7](https://linux-hardware.org/?probe=02721926a7) | Jun 25, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [e568c96372](https://linux-hardware.org/?probe=e568c96372) | Jun 25, 2022 |
| Lenovo        | ThinkPad X230 23331R5       | Notebook    | [c6589e02c4](https://linux-hardware.org/?probe=c6589e02c4) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | Notebook    | [90c701411f](https://linux-hardware.org/?probe=90c701411f) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | Notebook    | [fb02c13e80](https://linux-hardware.org/?probe=fb02c13e80) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [490c1074fe](https://linux-hardware.org/?probe=490c1074fe) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [51d3a22bf6](https://linux-hardware.org/?probe=51d3a22bf6) | Jun 25, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0db95d58d4](https://linux-hardware.org/?probe=0db95d58d4) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | Desktop     | [44700880cf](https://linux-hardware.org/?probe=44700880cf) | Jun 24, 2022 |
| ASUSTek       | LEUCITE                     | Desktop     | [c4d2ed5723](https://linux-hardware.org/?probe=c4d2ed5723) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | Desktop     | [517a155f9b](https://linux-hardware.org/?probe=517a155f9b) | Jun 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [289b09bf25](https://linux-hardware.org/?probe=289b09bf25) | Jun 24, 2022 |
| System76      | Darter Pro                  | Notebook    | [db7f217878](https://linux-hardware.org/?probe=db7f217878) | Jun 24, 2022 |
| HP            | EliteBook 745 G2            | Notebook    | [fe87d16f84](https://linux-hardware.org/?probe=fe87d16f84) | Jun 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [c2a22e5a3d](https://linux-hardware.org/?probe=c2a22e5a3d) | Jun 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [962571591a](https://linux-hardware.org/?probe=962571591a) | Jun 24, 2022 |
| Alienware     | 14                          | Notebook    | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Toshiba       | Satellite S50-A             | Notebook    | [c2e7c1b26d](https://linux-hardware.org/?probe=c2e7c1b26d) | Jun 24, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [ee865231c1](https://linux-hardware.org/?probe=ee865231c1) | Jun 24, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [055977bdee](https://linux-hardware.org/?probe=055977bdee) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [1e7e58ae1d](https://linux-hardware.org/?probe=1e7e58ae1d) | Jun 23, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0bd1e7d592](https://linux-hardware.org/?probe=0bd1e7d592) | Jun 23, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d4492d1e5d](https://linux-hardware.org/?probe=d4492d1e5d) | Jun 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [ee06b837b0](https://linux-hardware.org/?probe=ee06b837b0) | Jun 23, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [47420af7dc](https://linux-hardware.org/?probe=47420af7dc) | Jun 23, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [592f0a2f63](https://linux-hardware.org/?probe=592f0a2f63) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ae30cadddf](https://linux-hardware.org/?probe=ae30cadddf) | Jun 22, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [21d1dc43e6](https://linux-hardware.org/?probe=21d1dc43e6) | Jun 22, 2022 |
| Dell          | Precision 5520              | Notebook    | [2216faa750](https://linux-hardware.org/?probe=2216faa750) | Jun 22, 2022 |
| Dell          | Inspiron 7560               | Notebook    | [a65b832b57](https://linux-hardware.org/?probe=a65b832b57) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [27bc9defca](https://linux-hardware.org/?probe=27bc9defca) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [941b96e6ab](https://linux-hardware.org/?probe=941b96e6ab) | Jun 22, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [5dc08ee2d7](https://linux-hardware.org/?probe=5dc08ee2d7) | Jun 22, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [c288025720](https://linux-hardware.org/?probe=c288025720) | Jun 21, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [3086580cf5](https://linux-hardware.org/?probe=3086580cf5) | Jun 21, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [0bc7456f92](https://linux-hardware.org/?probe=0bc7456f92) | Jun 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d5fd58e3b0](https://linux-hardware.org/?probe=d5fd58e3b0) | Jun 21, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1c76f3cdf4](https://linux-hardware.org/?probe=1c76f3cdf4) | Jun 21, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [8dca736a46](https://linux-hardware.org/?probe=8dca736a46) | Jun 21, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [f747d1bfd3](https://linux-hardware.org/?probe=f747d1bfd3) | Jun 21, 2022 |
| Quanta        | TWC                         | Notebook    | [6a466d7eac](https://linux-hardware.org/?probe=6a466d7eac) | Jun 21, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [b9b9d5ffda](https://linux-hardware.org/?probe=b9b9d5ffda) | Jun 21, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2974c5fa7c](https://linux-hardware.org/?probe=2974c5fa7c) | Jun 21, 2022 |
| MSI           | B550M-A PRO                 | Desktop     | [1765b91360](https://linux-hardware.org/?probe=1765b91360) | Jun 21, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [c6c4eda2cb](https://linux-hardware.org/?probe=c6c4eda2cb) | Jun 21, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [eb61c79793](https://linux-hardware.org/?probe=eb61c79793) | Jun 21, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [6ddca91c97](https://linux-hardware.org/?probe=6ddca91c97) | Jun 21, 2022 |
| System76      | Lemur Pro                   | Notebook    | [0350f8d8f7](https://linux-hardware.org/?probe=0350f8d8f7) | Jun 21, 2022 |
| Biostar       | N68S3+                      | Desktop     | [efe83d16ac](https://linux-hardware.org/?probe=efe83d16ac) | Jun 21, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [f615165669](https://linux-hardware.org/?probe=f615165669) | Jun 21, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [3bbbcaea72](https://linux-hardware.org/?probe=3bbbcaea72) | Jun 20, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [faa0749731](https://linux-hardware.org/?probe=faa0749731) | Jun 20, 2022 |
| Acer          | Iconia                      | Notebook    | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [230bdf84a1](https://linux-hardware.org/?probe=230bdf84a1) | Jun 20, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [ec3bc83e7a](https://linux-hardware.org/?probe=ec3bc83e7a) | Jun 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d5af99ece6](https://linux-hardware.org/?probe=d5af99ece6) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | Notebook    | [9bffffd652](https://linux-hardware.org/?probe=9bffffd652) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | Notebook    | [a8d859700b](https://linux-hardware.org/?probe=a8d859700b) | Jun 20, 2022 |
| Dell          | Inspiron 7590 2n1           | Convertible | [3c26fdb170](https://linux-hardware.org/?probe=3c26fdb170) | Jun 19, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ad271e0eec](https://linux-hardware.org/?probe=ad271e0eec) | Jun 19, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [3d4d492e9d](https://linux-hardware.org/?probe=3d4d492e9d) | Jun 19, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [0d3fa4ad21](https://linux-hardware.org/?probe=0d3fa4ad21) | Jun 19, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [d1d647724c](https://linux-hardware.org/?probe=d1d647724c) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [2b31dedd45](https://linux-hardware.org/?probe=2b31dedd45) | Jun 19, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [b3efe3d4b5](https://linux-hardware.org/?probe=b3efe3d4b5) | Jun 19, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [b04866cc36](https://linux-hardware.org/?probe=b04866cc36) | Jun 19, 2022 |
| HP            | 158B                        | Desktop     | [b66a2770e7](https://linux-hardware.org/?probe=b66a2770e7) | Jun 18, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [1820538c80](https://linux-hardware.org/?probe=1820538c80) | Jun 18, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [e601e834f2](https://linux-hardware.org/?probe=e601e834f2) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | Notebook    | [47b7f42708](https://linux-hardware.org/?probe=47b7f42708) | Jun 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [8121d73bc9](https://linux-hardware.org/?probe=8121d73bc9) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | Notebook    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [41eb5a7de2](https://linux-hardware.org/?probe=41eb5a7de2) | Jun 18, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [6ba04b0f37](https://linux-hardware.org/?probe=6ba04b0f37) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cb268bf1ab](https://linux-hardware.org/?probe=cb268bf1ab) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ed83fdd673](https://linux-hardware.org/?probe=ed83fdd673) | Jun 18, 2022 |
| Lenovo        | ThinkPad T450 20BUS1110E    | Notebook    | [77dd393da8](https://linux-hardware.org/?probe=77dd393da8) | Jun 18, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [d542c2f694](https://linux-hardware.org/?probe=d542c2f694) | Jun 18, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2ed64f08f3](https://linux-hardware.org/?probe=2ed64f08f3) | Jun 17, 2022 |
| Dell          | Latitude E7240              | Notebook    | [31340542c2](https://linux-hardware.org/?probe=31340542c2) | Jun 17, 2022 |
| HP            | Unknown                     | Notebook    | [4c4cdf6526](https://linux-hardware.org/?probe=4c4cdf6526) | Jun 17, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [13d72fd6f0](https://linux-hardware.org/?probe=13d72fd6f0) | Jun 17, 2022 |
| Dell          | Latitude E7240              | Notebook    | [08efb8dcc5](https://linux-hardware.org/?probe=08efb8dcc5) | Jun 17, 2022 |
| Schenker      | VIA 15 Pro                  | Notebook    | [1d1727713f](https://linux-hardware.org/?probe=1d1727713f) | Jun 17, 2022 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [ee03ec1eae](https://linux-hardware.org/?probe=ee03ec1eae) | Jun 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [617dc7c353](https://linux-hardware.org/?probe=617dc7c353) | Jun 17, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [8f60c0fb25](https://linux-hardware.org/?probe=8f60c0fb25) | Jun 17, 2022 |
| Dell          | Precision 5540              | Notebook    | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| Acer          | Aspire E5-574G              | Notebook    | [23c2dd37fe](https://linux-hardware.org/?probe=23c2dd37fe) | Jun 17, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [755ead951d](https://linux-hardware.org/?probe=755ead951d) | Jun 17, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [5241a60357](https://linux-hardware.org/?probe=5241a60357) | Jun 17, 2022 |
| Dell          | Latitude E7240              | Notebook    | [b6978a823c](https://linux-hardware.org/?probe=b6978a823c) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [f4178c276d](https://linux-hardware.org/?probe=f4178c276d) | Jun 16, 2022 |
| Acer          | Aspire 4741                 | Notebook    | [9f25816784](https://linux-hardware.org/?probe=9f25816784) | Jun 16, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [91039940ea](https://linux-hardware.org/?probe=91039940ea) | Jun 16, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [10304caa6b](https://linux-hardware.org/?probe=10304caa6b) | Jun 16, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | Desktop     | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b136496151](https://linux-hardware.org/?probe=b136496151) | Jun 16, 2022 |
| System76      | Oryx Pro                    | Notebook    | [4daa6c7d77](https://linux-hardware.org/?probe=4daa6c7d77) | Jun 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [24140a62de](https://linux-hardware.org/?probe=24140a62de) | Jun 16, 2022 |
| Dell          | Latitude E6540              | Notebook    | [93f049609f](https://linux-hardware.org/?probe=93f049609f) | Jun 16, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| System76      | Galago Pro                  | Notebook    | [440ba53ef9](https://linux-hardware.org/?probe=440ba53ef9) | Jun 16, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [145a1e77fc](https://linux-hardware.org/?probe=145a1e77fc) | Jun 16, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [d6e4d7642d](https://linux-hardware.org/?probe=d6e4d7642d) | Jun 16, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e11d001f52](https://linux-hardware.org/?probe=e11d001f52) | Jun 15, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [cc1947a21b](https://linux-hardware.org/?probe=cc1947a21b) | Jun 15, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [29cfeda814](https://linux-hardware.org/?probe=29cfeda814) | Jun 15, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [6abbac5ca2](https://linux-hardware.org/?probe=6abbac5ca2) | Jun 15, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [aa390f3eaa](https://linux-hardware.org/?probe=aa390f3eaa) | Jun 15, 2022 |
| Sony          | SVF15A1M2ES                 | Notebook    | [bdcd4a90fc](https://linux-hardware.org/?probe=bdcd4a90fc) | Jun 15, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b12643d9ac](https://linux-hardware.org/?probe=b12643d9ac) | Jun 15, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d4e4001c4c](https://linux-hardware.org/?probe=d4e4001c4c) | Jun 15, 2022 |
| Medion        | MS-7728                     | Desktop     | [ae02539c17](https://linux-hardware.org/?probe=ae02539c17) | Jun 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [5be4039515](https://linux-hardware.org/?probe=5be4039515) | Jun 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [03fb6fa23c](https://linux-hardware.org/?probe=03fb6fa23c) | Jun 15, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [507c214577](https://linux-hardware.org/?probe=507c214577) | Jun 15, 2022 |
| Dell          | Precision 5550              | Notebook    | [f5f815ceed](https://linux-hardware.org/?probe=f5f815ceed) | Jun 14, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [f7201ee1de](https://linux-hardware.org/?probe=f7201ee1de) | Jun 14, 2022 |
| HP            | 1905                        | Desktop     | [b3d0170095](https://linux-hardware.org/?probe=b3d0170095) | Jun 14, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [06bccc3696](https://linux-hardware.org/?probe=06bccc3696) | Jun 14, 2022 |
| HP            | 18E7                        | Desktop     | [9f82638329](https://linux-hardware.org/?probe=9f82638329) | Jun 14, 2022 |
| Dell          | Precision 7720              | Notebook    | [8b4da2326e](https://linux-hardware.org/?probe=8b4da2326e) | Jun 14, 2022 |
| Dell          | Precision 7720              | Notebook    | [bf25929cec](https://linux-hardware.org/?probe=bf25929cec) | Jun 14, 2022 |
| Dell          | Latitude E6540              | Notebook    | [44b876534d](https://linux-hardware.org/?probe=44b876534d) | Jun 14, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [23de86aa97](https://linux-hardware.org/?probe=23de86aa97) | Jun 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [f4ef35b902](https://linux-hardware.org/?probe=f4ef35b902) | Jun 14, 2022 |
| Dell          | Inspiron 7737               | Notebook    | [6fa74e19b1](https://linux-hardware.org/?probe=6fa74e19b1) | Jun 13, 2022 |
| Alienware     | 0R3FWM A00                  | Desktop     | [6690a39447](https://linux-hardware.org/?probe=6690a39447) | Jun 13, 2022 |
| Notebook      | P65_P67SE                   | Notebook    | [590b7204da](https://linux-hardware.org/?probe=590b7204da) | Jun 13, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [45ca271974](https://linux-hardware.org/?probe=45ca271974) | Jun 13, 2022 |
| Lenovo        | B40-80 80F6                 | Notebook    | [7449f0f8d2](https://linux-hardware.org/?probe=7449f0f8d2) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f9e74fdcd3](https://linux-hardware.org/?probe=f9e74fdcd3) | Jun 13, 2022 |
| Dell          | 073MMW A03                  | Desktop     | [3e206d2462](https://linux-hardware.org/?probe=3e206d2462) | Jun 13, 2022 |
| ASUSTek       | K70IJ                       | Notebook    | [2eb24f0195](https://linux-hardware.org/?probe=2eb24f0195) | Jun 13, 2022 |
| ASUSTek       | K70IJ                       | Notebook    | [110ff08266](https://linux-hardware.org/?probe=110ff08266) | Jun 13, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [7222fb776a](https://linux-hardware.org/?probe=7222fb776a) | Jun 13, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [cafc34944d](https://linux-hardware.org/?probe=cafc34944d) | Jun 13, 2022 |
| Dell          | Latitude E6540              | Notebook    | [91e07b8f2d](https://linux-hardware.org/?probe=91e07b8f2d) | Jun 12, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| ASUSTek       | UX430UQ                     | Notebook    | [9754c7394d](https://linux-hardware.org/?probe=9754c7394d) | Jun 12, 2022 |
| Dell          | System XPS L702X            | Notebook    | [b79115e065](https://linux-hardware.org/?probe=b79115e065) | Jun 12, 2022 |
| MSI           | Alpha 17 A4DEK              | Notebook    | [42171e02bb](https://linux-hardware.org/?probe=42171e02bb) | Jun 11, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [a332c946a2](https://linux-hardware.org/?probe=a332c946a2) | Jun 11, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [0a0828f262](https://linux-hardware.org/?probe=0a0828f262) | Jun 11, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [8ed24a5d98](https://linux-hardware.org/?probe=8ed24a5d98) | Jun 11, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [d02f89642d](https://linux-hardware.org/?probe=d02f89642d) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | Desktop     | [a4277bcba9](https://linux-hardware.org/?probe=a4277bcba9) | Jun 11, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [d88374c06d](https://linux-hardware.org/?probe=d88374c06d) | Jun 11, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [4916232f15](https://linux-hardware.org/?probe=4916232f15) | Jun 11, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [7c8c3427a9](https://linux-hardware.org/?probe=7c8c3427a9) | Jun 11, 2022 |
| HP            | ProBook 455 G3              | Notebook    | [bac60198a3](https://linux-hardware.org/?probe=bac60198a3) | Jun 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [19d1362c66](https://linux-hardware.org/?probe=19d1362c66) | Jun 10, 2022 |
| Gigabyte      | H87M-HD3                    | Desktop     | [eadd724efa](https://linux-hardware.org/?probe=eadd724efa) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| Dell          | Latitude E7270              | Notebook    | [8d8f0db52c](https://linux-hardware.org/?probe=8d8f0db52c) | Jun 10, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [839bbee3fa](https://linux-hardware.org/?probe=839bbee3fa) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [1fef4f1cf3](https://linux-hardware.org/?probe=1fef4f1cf3) | Jun 10, 2022 |
| ASUSTek       | Unknown                     | Notebook    | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [ad03ec2516](https://linux-hardware.org/?probe=ad03ec2516) | Jun 09, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [ebbea30b2b](https://linux-hardware.org/?probe=ebbea30b2b) | Jun 09, 2022 |
| Dell          | G7 7790                     | Notebook    | [58cfc35862](https://linux-hardware.org/?probe=58cfc35862) | Jun 09, 2022 |
| Dell          | G7 7790                     | Notebook    | [495cfbb6f3](https://linux-hardware.org/?probe=495cfbb6f3) | Jun 09, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [9c7b34c996](https://linux-hardware.org/?probe=9c7b34c996) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [c87c7a989a](https://linux-hardware.org/?probe=c87c7a989a) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| System76      | Oryx Pro                    | Notebook    | [bf9c9467d3](https://linux-hardware.org/?probe=bf9c9467d3) | Jun 08, 2022 |
| System76      | Oryx Pro                    | Notebook    | [2f96b6b08d](https://linux-hardware.org/?probe=2f96b6b08d) | Jun 08, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [5c2fedfca8](https://linux-hardware.org/?probe=5c2fedfca8) | Jun 08, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [ebf8dce138](https://linux-hardware.org/?probe=ebf8dce138) | Jun 07, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [37e02e84a5](https://linux-hardware.org/?probe=37e02e84a5) | Jun 07, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [d4a2222ff7](https://linux-hardware.org/?probe=d4a2222ff7) | Jun 07, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7ca8395543](https://linux-hardware.org/?probe=7ca8395543) | Jun 07, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [44a6f3e33d](https://linux-hardware.org/?probe=44a6f3e33d) | Jun 07, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [cd4b8b609f](https://linux-hardware.org/?probe=cd4b8b609f) | Jun 07, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [7bb51064db](https://linux-hardware.org/?probe=7bb51064db) | Jun 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [2607169dfe](https://linux-hardware.org/?probe=2607169dfe) | Jun 06, 2022 |
| Dell          | 0JW6C6 A01                  | Desktop     | [34d9fc3968](https://linux-hardware.org/?probe=34d9fc3968) | Jun 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [56c4428636](https://linux-hardware.org/?probe=56c4428636) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | Notebook    | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Framework     | Laptop                      | Notebook    | [ed8e682778](https://linux-hardware.org/?probe=ed8e682778) | Jun 06, 2022 |
| Samsung       | 760XDA                      | Notebook    | [46350b515c](https://linux-hardware.org/?probe=46350b515c) | Jun 06, 2022 |
| MSI           | GS75 Stealth 9SF            | Notebook    | [9d18e7094e](https://linux-hardware.org/?probe=9d18e7094e) | Jun 05, 2022 |
| ASUSTek       | X556URK                     | Notebook    | [d6da70c8bd](https://linux-hardware.org/?probe=d6da70c8bd) | Jun 05, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0e817967c8](https://linux-hardware.org/?probe=0e817967c8) | Jun 05, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a0c155ffb9](https://linux-hardware.org/?probe=a0c155ffb9) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | Notebook    | [1485986503](https://linux-hardware.org/?probe=1485986503) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | Notebook    | [2f60fd04bf](https://linux-hardware.org/?probe=2f60fd04bf) | Jun 05, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [d8a8c3c8b4](https://linux-hardware.org/?probe=d8a8c3c8b4) | Jun 05, 2022 |
| Dell          | 0YKWK2 A00                  | All in one  | [f373c43a01](https://linux-hardware.org/?probe=f373c43a01) | Jun 05, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | Notebook    | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [816b4e757d](https://linux-hardware.org/?probe=816b4e757d) | Jun 05, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [e92e195362](https://linux-hardware.org/?probe=e92e195362) | Jun 05, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [e7e3608105](https://linux-hardware.org/?probe=e7e3608105) | Jun 04, 2022 |
| Dell          | Inspiron 3502               | Notebook    | [afa1c5cd74](https://linux-hardware.org/?probe=afa1c5cd74) | Jun 04, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [a65dd5834e](https://linux-hardware.org/?probe=a65dd5834e) | Jun 04, 2022 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [f729442cad](https://linux-hardware.org/?probe=f729442cad) | Jun 04, 2022 |
| Dell          | Precision M4800             | Notebook    | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [81bfe17cb5](https://linux-hardware.org/?probe=81bfe17cb5) | Jun 04, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [44e0643923](https://linux-hardware.org/?probe=44e0643923) | Jun 03, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [95db56a864](https://linux-hardware.org/?probe=95db56a864) | Jun 03, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [605cbc489f](https://linux-hardware.org/?probe=605cbc489f) | Jun 03, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [a8c04eea72](https://linux-hardware.org/?probe=a8c04eea72) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [562348dd07](https://linux-hardware.org/?probe=562348dd07) | Jun 03, 2022 |
| Toshiba       | Satellite L850-1D5          | Notebook    | [c8a260ef80](https://linux-hardware.org/?probe=c8a260ef80) | Jun 03, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [915e2819c0](https://linux-hardware.org/?probe=915e2819c0) | Jun 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [f1f4aec562](https://linux-hardware.org/?probe=f1f4aec562) | Jun 02, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [d793b451f6](https://linux-hardware.org/?probe=d793b451f6) | Jun 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [9299688b01](https://linux-hardware.org/?probe=9299688b01) | Jun 02, 2022 |
| Dell          | Latitude E7470              | Notebook    | [f9a9090c54](https://linux-hardware.org/?probe=f9a9090c54) | Jun 02, 2022 |
| Dell          | Latitude 7390               | Notebook    | [0c7c9778aa](https://linux-hardware.org/?probe=0c7c9778aa) | Jun 02, 2022 |
| ASRock        | Z390 Phantom Gaming SLI/... | Desktop     | [5f40da7ae9](https://linux-hardware.org/?probe=5f40da7ae9) | Jun 02, 2022 |
| Dell          | Latitude E6540              | Notebook    | [de2e1727bc](https://linux-hardware.org/?probe=de2e1727bc) | Jun 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [491a4105d8](https://linux-hardware.org/?probe=491a4105d8) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [5348dd6576](https://linux-hardware.org/?probe=5348dd6576) | Jun 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [e3c9cca7e1](https://linux-hardware.org/?probe=e3c9cca7e1) | Jun 01, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [6f6e6c038a](https://linux-hardware.org/?probe=6f6e6c038a) | Jun 01, 2022 |
| Lenovo        | ThinkPad T410 2537HN3       | Notebook    | [e373330c8b](https://linux-hardware.org/?probe=e373330c8b) | Jun 01, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [fa29e357fa](https://linux-hardware.org/?probe=fa29e357fa) | Jun 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | Notebook    | [57f540db26](https://linux-hardware.org/?probe=57f540db26) | Jun 01, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [70eccb19d4](https://linux-hardware.org/?probe=70eccb19d4) | Jun 01, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [506d3fb361](https://linux-hardware.org/?probe=506d3fb361) | Jun 01, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [82b4935292](https://linux-hardware.org/?probe=82b4935292) | Jun 01, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [d0dbd3d75e](https://linux-hardware.org/?probe=d0dbd3d75e) | Jun 01, 2022 |
| Dell          | G7 7700                     | Notebook    | [25e22bc243](https://linux-hardware.org/?probe=25e22bc243) | May 31, 2022 |
| MSI           | Z170A MPOWER GAMING TITA... | Desktop     | [538feade4f](https://linux-hardware.org/?probe=538feade4f) | May 31, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [4863034bc5](https://linux-hardware.org/?probe=4863034bc5) | May 31, 2022 |
| Dell          | Inspiron 7590 2n1           | Convertible | [30a0d0ec81](https://linux-hardware.org/?probe=30a0d0ec81) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bee74ec003](https://linux-hardware.org/?probe=bee74ec003) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [871738fea2](https://linux-hardware.org/?probe=871738fea2) | May 31, 2022 |
| System76      | Thelio Major thelio-majo... | Desktop     | [291730a3bb](https://linux-hardware.org/?probe=291730a3bb) | May 31, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [ed28d49715](https://linux-hardware.org/?probe=ed28d49715) | May 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [923158d12f](https://linux-hardware.org/?probe=923158d12f) | May 30, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [6dd26d47b1](https://linux-hardware.org/?probe=6dd26d47b1) | May 30, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [14f581788f](https://linux-hardware.org/?probe=14f581788f) | May 30, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [013e0da975](https://linux-hardware.org/?probe=013e0da975) | May 30, 2022 |
| Dell          | 0D02VH A01                  | Desktop     | [fc97b0a5bf](https://linux-hardware.org/?probe=fc97b0a5bf) | May 30, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [1058cdf867](https://linux-hardware.org/?probe=1058cdf867) | May 30, 2022 |
| HP            | 8266                        | Desktop     | [d0e35451ab](https://linux-hardware.org/?probe=d0e35451ab) | May 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [c28c21c4d8](https://linux-hardware.org/?probe=c28c21c4d8) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [5d899f8fc5](https://linux-hardware.org/?probe=5d899f8fc5) | May 29, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [72b7fc79d4](https://linux-hardware.org/?probe=72b7fc79d4) | May 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d1923db949](https://linux-hardware.org/?probe=d1923db949) | May 29, 2022 |
| Dell          | Vostro V130                 | Notebook    | [abefbba5b8](https://linux-hardware.org/?probe=abefbba5b8) | May 29, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [6fe2c4a416](https://linux-hardware.org/?probe=6fe2c4a416) | May 29, 2022 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [0d556408f3](https://linux-hardware.org/?probe=0d556408f3) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| HP            | OMEN by Laptop 15z-en100    | Notebook    | [35e3478a5d](https://linux-hardware.org/?probe=35e3478a5d) | May 28, 2022 |
| Medion        | X6816                       | Notebook    | [6d7996894c](https://linux-hardware.org/?probe=6d7996894c) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7ae101b473](https://linux-hardware.org/?probe=7ae101b473) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [469ed3f68b](https://linux-hardware.org/?probe=469ed3f68b) | May 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [96bc0699c3](https://linux-hardware.org/?probe=96bc0699c3) | May 28, 2022 |
| Lenovo        | CRESCENTBAY 31900059 STD... | All in one  | [d222b1e86e](https://linux-hardware.org/?probe=d222b1e86e) | May 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b78390767c](https://linux-hardware.org/?probe=b78390767c) | May 28, 2022 |
| MSI           | MS-7717                     | Desktop     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [88c420d481](https://linux-hardware.org/?probe=88c420d481) | May 28, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [c7a5f5eef3](https://linux-hardware.org/?probe=c7a5f5eef3) | May 28, 2022 |
| MSI           | MS-7717                     | Desktop     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| HP            | 158B                        | Desktop     | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [a2f2dc2eee](https://linux-hardware.org/?probe=a2f2dc2eee) | May 27, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [3980ea8269](https://linux-hardware.org/?probe=3980ea8269) | May 27, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [bdf54228e5](https://linux-hardware.org/?probe=bdf54228e5) | May 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [65bccd9c04](https://linux-hardware.org/?probe=65bccd9c04) | May 27, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [323fc36eb6](https://linux-hardware.org/?probe=323fc36eb6) | May 27, 2022 |
| Toshiba       | QOSMIO X770                 | Notebook    | [8f7d0ba9f9](https://linux-hardware.org/?probe=8f7d0ba9f9) | May 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6e7b6eddea](https://linux-hardware.org/?probe=6e7b6eddea) | May 27, 2022 |
| Dell          | Precision 5530              | Notebook    | [2ecf3390bf](https://linux-hardware.org/?probe=2ecf3390bf) | May 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [f5195788f8](https://linux-hardware.org/?probe=f5195788f8) | May 27, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [5d1ee4048a](https://linux-hardware.org/?probe=5d1ee4048a) | May 27, 2022 |
| Acer          | Aspire A315-57G             | Notebook    | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [c4b27d79ef](https://linux-hardware.org/?probe=c4b27d79ef) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | Notebook    | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [938ab3ec5c](https://linux-hardware.org/?probe=938ab3ec5c) | May 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ae0ada290a](https://linux-hardware.org/?probe=ae0ada290a) | May 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [ab2cd65153](https://linux-hardware.org/?probe=ab2cd65153) | May 26, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [d4af21adb8](https://linux-hardware.org/?probe=d4af21adb8) | May 25, 2022 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [1d7941d921](https://linux-hardware.org/?probe=1d7941d921) | May 25, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [4c0d37687e](https://linux-hardware.org/?probe=4c0d37687e) | May 25, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [b3f7ff3d98](https://linux-hardware.org/?probe=b3f7ff3d98) | May 25, 2022 |
| Toshiba       | Satellite P850              | Notebook    | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [852a292ba3](https://linux-hardware.org/?probe=852a292ba3) | May 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4738560555](https://linux-hardware.org/?probe=4738560555) | May 25, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [ca090207b8](https://linux-hardware.org/?probe=ca090207b8) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | Notebook    | [647e502881](https://linux-hardware.org/?probe=647e502881) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | Notebook    | [0db0bd7aa8](https://linux-hardware.org/?probe=0db0bd7aa8) | May 25, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [3db2e28ef2](https://linux-hardware.org/?probe=3db2e28ef2) | May 24, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [a34eaa3e4a](https://linux-hardware.org/?probe=a34eaa3e4a) | May 24, 2022 |
| Dell          | Precision 5550              | Notebook    | [6b17026494](https://linux-hardware.org/?probe=6b17026494) | May 24, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [e6e080d6e0](https://linux-hardware.org/?probe=e6e080d6e0) | May 24, 2022 |
| HP            | 8703                        | Desktop     | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| ASRock        | H470M-ITX/ac                | Desktop     | [181f7decc6](https://linux-hardware.org/?probe=181f7decc6) | May 24, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [08527b166e](https://linux-hardware.org/?probe=08527b166e) | May 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [1122022ae1](https://linux-hardware.org/?probe=1122022ae1) | May 24, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [a59234d081](https://linux-hardware.org/?probe=a59234d081) | May 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [bf692d5408](https://linux-hardware.org/?probe=bf692d5408) | May 23, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [dbfb736222](https://linux-hardware.org/?probe=dbfb736222) | May 23, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [39f85b46d7](https://linux-hardware.org/?probe=39f85b46d7) | May 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f2e32c336d](https://linux-hardware.org/?probe=f2e32c336d) | May 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Acer          | TravelMate 7750G            | Notebook    | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | Notebook    | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [78bb2ba75c](https://linux-hardware.org/?probe=78bb2ba75c) | May 23, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [1d4f3a60c0](https://linux-hardware.org/?probe=1d4f3a60c0) | May 23, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [5ec2b88c83](https://linux-hardware.org/?probe=5ec2b88c83) | May 22, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [5a2f6291b5](https://linux-hardware.org/?probe=5a2f6291b5) | May 22, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| ASUSTek       | X505BA                      | Notebook    | [685c1f7378](https://linux-hardware.org/?probe=685c1f7378) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [21818b99b4](https://linux-hardware.org/?probe=21818b99b4) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [f1db82519f](https://linux-hardware.org/?probe=f1db82519f) | May 22, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | Notebook    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| Dell          | G3 3500                     | Notebook    | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [1993c161fd](https://linux-hardware.org/?probe=1993c161fd) | May 22, 2022 |
| MSI           | MEG Z390 ACE                | Desktop     | [0065576586](https://linux-hardware.org/?probe=0065576586) | May 22, 2022 |
| Google        | Lulu                        | Notebook    | [e7a0842114](https://linux-hardware.org/?probe=e7a0842114) | May 21, 2022 |
| Gigabyte      | H67N-USB3-B3                | Desktop     | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [97a0996658](https://linux-hardware.org/?probe=97a0996658) | May 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [1cd571d585](https://linux-hardware.org/?probe=1cd571d585) | May 21, 2022 |
| ASUSTek       | X510UR                      | Notebook    | [40b1695a67](https://linux-hardware.org/?probe=40b1695a67) | May 21, 2022 |
| ASUSTek       | X510UR                      | Notebook    | [e7cea85f09](https://linux-hardware.org/?probe=e7cea85f09) | May 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| PC Special... | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [e002072665](https://linux-hardware.org/?probe=e002072665) | May 21, 2022 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [358e85c524](https://linux-hardware.org/?probe=358e85c524) | May 21, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [540e0831b1](https://linux-hardware.org/?probe=540e0831b1) | May 20, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [77d5276ecc](https://linux-hardware.org/?probe=77d5276ecc) | May 20, 2022 |
| ASRock        | TRX40 Creator               | Desktop     | [a810336f3f](https://linux-hardware.org/?probe=a810336f3f) | May 20, 2022 |
| ASRock        | TRX40 Creator               | Desktop     | [6993400976](https://linux-hardware.org/?probe=6993400976) | May 20, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [2211d5c2a2](https://linux-hardware.org/?probe=2211d5c2a2) | May 20, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [3f21c66d5c](https://linux-hardware.org/?probe=3f21c66d5c) | May 20, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [7cae58580a](https://linux-hardware.org/?probe=7cae58580a) | May 20, 2022 |
| ASRock        | Z390 Phantom Gaming 4-IB    | Desktop     | [543ab770e8](https://linux-hardware.org/?probe=543ab770e8) | May 20, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d705be052a](https://linux-hardware.org/?probe=d705be052a) | May 20, 2022 |
| Dell          | Inspiron 5555               | Notebook    | [35c2610913](https://linux-hardware.org/?probe=35c2610913) | May 20, 2022 |
| Positivo      | POS-MI945AA                 | Desktop     | [0f9875e8fc](https://linux-hardware.org/?probe=0f9875e8fc) | May 19, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [fa1f318919](https://linux-hardware.org/?probe=fa1f318919) | May 19, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [d94f4b0a43](https://linux-hardware.org/?probe=d94f4b0a43) | May 19, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [5ddfbf547b](https://linux-hardware.org/?probe=5ddfbf547b) | May 19, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [ba19473e18](https://linux-hardware.org/?probe=ba19473e18) | May 19, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [fba154be66](https://linux-hardware.org/?probe=fba154be66) | May 18, 2022 |
| Gigabyte      | AERO 15 KC                  | Notebook    | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| Supermicro    | X8SIL                       | Desktop     | [66e8a4001f](https://linux-hardware.org/?probe=66e8a4001f) | May 18, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [fd66fd9a5a](https://linux-hardware.org/?probe=fd66fd9a5a) | May 18, 2022 |
| Supermicro    | X8SIL                       | Desktop     | [5cb6f1067b](https://linux-hardware.org/?probe=5cb6f1067b) | May 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [c9a82e1be0](https://linux-hardware.org/?probe=c9a82e1be0) | May 18, 2022 |
| HP            | 8054                        | Desktop     | [725f204fd0](https://linux-hardware.org/?probe=725f204fd0) | May 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [8ef2235464](https://linux-hardware.org/?probe=8ef2235464) | May 17, 2022 |
| System76      | Oryx Pro                    | Notebook    | [b68edfe15c](https://linux-hardware.org/?probe=b68edfe15c) | May 17, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [ca68812bf2](https://linux-hardware.org/?probe=ca68812bf2) | May 17, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [f005623f03](https://linux-hardware.org/?probe=f005623f03) | May 17, 2022 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [5bc959890b](https://linux-hardware.org/?probe=5bc959890b) | May 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [e4bf8d23b8](https://linux-hardware.org/?probe=e4bf8d23b8) | May 17, 2022 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [e23e8291e0](https://linux-hardware.org/?probe=e23e8291e0) | May 17, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [2f7a99c28b](https://linux-hardware.org/?probe=2f7a99c28b) | May 17, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [f5ade437dc](https://linux-hardware.org/?probe=f5ade437dc) | May 17, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [77a8cae8a0](https://linux-hardware.org/?probe=77a8cae8a0) | May 17, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [2d96e5ecba](https://linux-hardware.org/?probe=2d96e5ecba) | May 17, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [ee4e4a7bc7](https://linux-hardware.org/?probe=ee4e4a7bc7) | May 17, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [4806ca2a7e](https://linux-hardware.org/?probe=4806ca2a7e) | May 17, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| Alienware     | 18                          | Notebook    | [7aa82b2786](https://linux-hardware.org/?probe=7aa82b2786) | May 17, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [4d76b03e66](https://linux-hardware.org/?probe=4d76b03e66) | May 17, 2022 |
| Acer          | Aspire 7560G                | Notebook    | [d3d9aa988f](https://linux-hardware.org/?probe=d3d9aa988f) | May 16, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [eb5345a5c6](https://linux-hardware.org/?probe=eb5345a5c6) | May 16, 2022 |
| Google        | Lulu                        | Notebook    | [c402204a03](https://linux-hardware.org/?probe=c402204a03) | May 16, 2022 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [e0aab70a85](https://linux-hardware.org/?probe=e0aab70a85) | May 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [3a369eed6d](https://linux-hardware.org/?probe=3a369eed6d) | May 16, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a8fffad424](https://linux-hardware.org/?probe=a8fffad424) | May 16, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [2daea316b2](https://linux-hardware.org/?probe=2daea316b2) | May 16, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [3ecda9477c](https://linux-hardware.org/?probe=3ecda9477c) | May 16, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [aa531d1bf8](https://linux-hardware.org/?probe=aa531d1bf8) | May 15, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [2d4d81086f](https://linux-hardware.org/?probe=2d4d81086f) | May 15, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [91d8b47a30](https://linux-hardware.org/?probe=91d8b47a30) | May 15, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [62e934492d](https://linux-hardware.org/?probe=62e934492d) | May 15, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [608664ce7a](https://linux-hardware.org/?probe=608664ce7a) | May 15, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [653725bdde](https://linux-hardware.org/?probe=653725bdde) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [7f06d07456](https://linux-hardware.org/?probe=7f06d07456) | May 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [a049c51989](https://linux-hardware.org/?probe=a049c51989) | May 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [7a2fd723d6](https://linux-hardware.org/?probe=7a2fd723d6) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [98db0dde2a](https://linux-hardware.org/?probe=98db0dde2a) | May 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [66e43801f0](https://linux-hardware.org/?probe=66e43801f0) | May 13, 2022 |
| Google        | Lulu                        | Notebook    | [8d7f1657d0](https://linux-hardware.org/?probe=8d7f1657d0) | May 13, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [0cc824e2a5](https://linux-hardware.org/?probe=0cc824e2a5) | May 13, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [30bb58501e](https://linux-hardware.org/?probe=30bb58501e) | May 13, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [0a3017f333](https://linux-hardware.org/?probe=0a3017f333) | May 13, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [95339de38e](https://linux-hardware.org/?probe=95339de38e) | May 13, 2022 |
| NZXT          | N7 B550                     | Desktop     | [73441bbfc4](https://linux-hardware.org/?probe=73441bbfc4) | May 12, 2022 |
| Unknown       | BTC79X5                     | Desktop     | [42b222eb65](https://linux-hardware.org/?probe=42b222eb65) | May 12, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [fe8e3837f4](https://linux-hardware.org/?probe=fe8e3837f4) | May 12, 2022 |
| System76      | Pangolin                    | Notebook    | [0f05fa93a8](https://linux-hardware.org/?probe=0f05fa93a8) | May 12, 2022 |
| AZW           | BT3 X                       | Desktop     | [a17cb64acb](https://linux-hardware.org/?probe=a17cb64acb) | May 12, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [ee225906fc](https://linux-hardware.org/?probe=ee225906fc) | May 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [0b95d0a5d8](https://linux-hardware.org/?probe=0b95d0a5d8) | May 12, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [114ef2756f](https://linux-hardware.org/?probe=114ef2756f) | May 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [915b95cae4](https://linux-hardware.org/?probe=915b95cae4) | May 11, 2022 |
| Google        | Cyan                        | Notebook    | [cec3bd0a88](https://linux-hardware.org/?probe=cec3bd0a88) | May 11, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [16911d5e64](https://linux-hardware.org/?probe=16911d5e64) | May 11, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [78ee3350a8](https://linux-hardware.org/?probe=78ee3350a8) | May 11, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [4f25a82453](https://linux-hardware.org/?probe=4f25a82453) | May 11, 2022 |
| Gigabyte      | B660 AORUS MASTER DDR4      | Desktop     | [e5981a9f20](https://linux-hardware.org/?probe=e5981a9f20) | May 11, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0913ac4c8e](https://linux-hardware.org/?probe=0913ac4c8e) | May 11, 2022 |
| System76      | Pangolin                    | Notebook    | [da80a33b86](https://linux-hardware.org/?probe=da80a33b86) | May 11, 2022 |
| Dell          | G15 5511                    | Notebook    | [17b75bcced](https://linux-hardware.org/?probe=17b75bcced) | May 10, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0066686d1d](https://linux-hardware.org/?probe=0066686d1d) | May 10, 2022 |
| NZXT          | N7 B550                     | Desktop     | [147247dfb6](https://linux-hardware.org/?probe=147247dfb6) | May 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [396a39e5a6](https://linux-hardware.org/?probe=396a39e5a6) | May 10, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [cae0934838](https://linux-hardware.org/?probe=cae0934838) | May 10, 2022 |
| ASRock        | X370 Professional Gaming    | Desktop     | [1e22ba0468](https://linux-hardware.org/?probe=1e22ba0468) | May 10, 2022 |
| HP            | EliteBook 2730p             | Notebook    | [d4c5b7824d](https://linux-hardware.org/?probe=d4c5b7824d) | May 10, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d88f833b65](https://linux-hardware.org/?probe=d88f833b65) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0b3cda16db](https://linux-hardware.org/?probe=0b3cda16db) | May 10, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [840087bbed](https://linux-hardware.org/?probe=840087bbed) | May 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [90190717eb](https://linux-hardware.org/?probe=90190717eb) | May 09, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [d9779b1c50](https://linux-hardware.org/?probe=d9779b1c50) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [29c93ea162](https://linux-hardware.org/?probe=29c93ea162) | May 09, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [fd022c446e](https://linux-hardware.org/?probe=fd022c446e) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [20f46751c2](https://linux-hardware.org/?probe=20f46751c2) | May 08, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [c1df33620d](https://linux-hardware.org/?probe=c1df33620d) | May 08, 2022 |
| MSI           | Modern 15 A10RAS            | Notebook    | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S8H100    | Notebook    | [5eefaba8d3](https://linux-hardware.org/?probe=5eefaba8d3) | May 08, 2022 |
| ASRock        | X299 Taichi CLX             | Desktop     | [47a45fca48](https://linux-hardware.org/?probe=47a45fca48) | May 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [8964a4c5ec](https://linux-hardware.org/?probe=8964a4c5ec) | May 08, 2022 |
| ECS           | Nettle3                     | Desktop     | [36f8cde007](https://linux-hardware.org/?probe=36f8cde007) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [dcdc07525d](https://linux-hardware.org/?probe=dcdc07525d) | May 08, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [1e1f4caa54](https://linux-hardware.org/?probe=1e1f4caa54) | May 08, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [65d94c8458](https://linux-hardware.org/?probe=65d94c8458) | May 08, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [057ea02fdb](https://linux-hardware.org/?probe=057ea02fdb) | May 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S8H100    | Notebook    | [892d07e5cf](https://linux-hardware.org/?probe=892d07e5cf) | May 08, 2022 |
| Lenovo        | Legion 5 17ITH6H 82JM       | Notebook    | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| MSI           | GS63 7RD                    | Notebook    | [eff12e3973](https://linux-hardware.org/?probe=eff12e3973) | May 08, 2022 |
| ECS           | Nettle3                     | Desktop     | [646fb53a2c](https://linux-hardware.org/?probe=646fb53a2c) | May 07, 2022 |
| HP            | Pavilion 15                 | Notebook    | [a18593bb5b](https://linux-hardware.org/?probe=a18593bb5b) | May 07, 2022 |
| Google        | Lulu                        | Notebook    | [18ecc4a6e7](https://linux-hardware.org/?probe=18ecc4a6e7) | May 07, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [61a4daec98](https://linux-hardware.org/?probe=61a4daec98) | May 07, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [5790e8a0cb](https://linux-hardware.org/?probe=5790e8a0cb) | May 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [180dd73bd6](https://linux-hardware.org/?probe=180dd73bd6) | May 07, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [632a2af548](https://linux-hardware.org/?probe=632a2af548) | May 07, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Lenovo        | 3746 No DPK                 | All in one  | [910612b856](https://linux-hardware.org/?probe=910612b856) | May 07, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [5b5ceb0f53](https://linux-hardware.org/?probe=5b5ceb0f53) | May 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4fe934e84d](https://linux-hardware.org/?probe=4fe934e84d) | May 06, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [4071a1a35e](https://linux-hardware.org/?probe=4071a1a35e) | May 06, 2022 |
| Google        | Peppy                       | Notebook    | [03dc670128](https://linux-hardware.org/?probe=03dc670128) | May 06, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [f99b5cee66](https://linux-hardware.org/?probe=f99b5cee66) | May 06, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [1332984f5d](https://linux-hardware.org/?probe=1332984f5d) | May 06, 2022 |
| Lenovo        | ThinkPad Twist 33472YU      | Notebook    | [710c086b29](https://linux-hardware.org/?probe=710c086b29) | May 06, 2022 |
| Lenovo        | ThinkPad Twist 33472YU      | Notebook    | [76fb8bb966](https://linux-hardware.org/?probe=76fb8bb966) | May 06, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [080b4f2667](https://linux-hardware.org/?probe=080b4f2667) | May 06, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [66a01dfd2d](https://linux-hardware.org/?probe=66a01dfd2d) | May 05, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8ecadc1bad](https://linux-hardware.org/?probe=8ecadc1bad) | May 05, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [2853128cd0](https://linux-hardware.org/?probe=2853128cd0) | May 05, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [af36cfb1a8](https://linux-hardware.org/?probe=af36cfb1a8) | May 05, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [5f51fd4cf8](https://linux-hardware.org/?probe=5f51fd4cf8) | May 05, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [7b7f29e504](https://linux-hardware.org/?probe=7b7f29e504) | May 05, 2022 |
| Acer          | Aspire V5-431               | Notebook    | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [fa323515aa](https://linux-hardware.org/?probe=fa323515aa) | May 05, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [e133868179](https://linux-hardware.org/?probe=e133868179) | May 05, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [1c70ba9e33](https://linux-hardware.org/?probe=1c70ba9e33) | May 05, 2022 |
| Dell          | Latitude E5440              | Notebook    | [a505dc0b3c](https://linux-hardware.org/?probe=a505dc0b3c) | May 05, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [93d6fb1610](https://linux-hardware.org/?probe=93d6fb1610) | May 05, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [36cabd86ba](https://linux-hardware.org/?probe=36cabd86ba) | May 04, 2022 |
| ASUSTek       | GL552VX                     | Notebook    | [d153ef27fa](https://linux-hardware.org/?probe=d153ef27fa) | May 04, 2022 |
| Acer          | Spin SP315-51               | Convertible | [b96494c3bc](https://linux-hardware.org/?probe=b96494c3bc) | May 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [a9f5b77476](https://linux-hardware.org/?probe=a9f5b77476) | May 04, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [e5f3e5b086](https://linux-hardware.org/?probe=e5f3e5b086) | May 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [8bfd6ecc71](https://linux-hardware.org/?probe=8bfd6ecc71) | May 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [720d11c11f](https://linux-hardware.org/?probe=720d11c11f) | May 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5a8fc607c4](https://linux-hardware.org/?probe=5a8fc607c4) | May 04, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [2b6338d755](https://linux-hardware.org/?probe=2b6338d755) | May 04, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [f5e954ea5e](https://linux-hardware.org/?probe=f5e954ea5e) | May 04, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [5de9e1d61f](https://linux-hardware.org/?probe=5de9e1d61f) | May 04, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [7196bf2ec6](https://linux-hardware.org/?probe=7196bf2ec6) | May 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [2136362d58](https://linux-hardware.org/?probe=2136362d58) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [373f22a70f](https://linux-hardware.org/?probe=373f22a70f) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [91a367d874](https://linux-hardware.org/?probe=91a367d874) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [65a2309744](https://linux-hardware.org/?probe=65a2309744) | May 03, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [0f8065fda6](https://linux-hardware.org/?probe=0f8065fda6) | May 03, 2022 |
| ASUSTek       | GL552JX                     | Notebook    | [c91f42212d](https://linux-hardware.org/?probe=c91f42212d) | May 03, 2022 |
| ASUSTek       | ROG Strix G713RC_G713RC     | Notebook    | [2ce25fb058](https://linux-hardware.org/?probe=2ce25fb058) | May 03, 2022 |
| Alienware     | 0CPDXD A00                  | Desktop     | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [9645231d87](https://linux-hardware.org/?probe=9645231d87) | May 03, 2022 |
| Acer          | Spin SP315-51               | Convertible | [227f2d9f45](https://linux-hardware.org/?probe=227f2d9f45) | May 03, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [c47758f125](https://linux-hardware.org/?probe=c47758f125) | May 03, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [4b44c67cde](https://linux-hardware.org/?probe=4b44c67cde) | May 02, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [8daebf6110](https://linux-hardware.org/?probe=8daebf6110) | May 02, 2022 |
| Dell          | Latitude E6440              | Notebook    | [d2ab063048](https://linux-hardware.org/?probe=d2ab063048) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [58ff4a1984](https://linux-hardware.org/?probe=58ff4a1984) | May 02, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [6c38249bc4](https://linux-hardware.org/?probe=6c38249bc4) | May 02, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [c0ef0738b5](https://linux-hardware.org/?probe=c0ef0738b5) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [4a09f5d3f3](https://linux-hardware.org/?probe=4a09f5d3f3) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ab716981c3](https://linux-hardware.org/?probe=ab716981c3) | May 02, 2022 |
| Framework     | Laptop                      | Notebook    | [0d35134041](https://linux-hardware.org/?probe=0d35134041) | May 02, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [8cf5364699](https://linux-hardware.org/?probe=8cf5364699) | May 02, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [02872ac9a8](https://linux-hardware.org/?probe=02872ac9a8) | May 02, 2022 |
| Alienware     | 0P0JWX A00                  | Desktop     | [e6e1548aa1](https://linux-hardware.org/?probe=e6e1548aa1) | May 02, 2022 |
| MSI           | GS65 Stealth 8SG            | Notebook    | [05f80b3e70](https://linux-hardware.org/?probe=05f80b3e70) | May 02, 2022 |
| System76      | Oryx Pro                    | Notebook    | [96251b761b](https://linux-hardware.org/?probe=96251b761b) | May 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [a456619489](https://linux-hardware.org/?probe=a456619489) | May 02, 2022 |
| Acer          | Aspire V5-573P              | Notebook    | [b64d1453d5](https://linux-hardware.org/?probe=b64d1453d5) | May 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [332445f774](https://linux-hardware.org/?probe=332445f774) | May 02, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [dcea7cd8c0](https://linux-hardware.org/?probe=dcea7cd8c0) | May 02, 2022 |
| Dell          | Latitude E5570              | Notebook    | [372feb146c](https://linux-hardware.org/?probe=372feb146c) | May 02, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [5f68858e66](https://linux-hardware.org/?probe=5f68858e66) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [925447d7e9](https://linux-hardware.org/?probe=925447d7e9) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b1e331055f](https://linux-hardware.org/?probe=b1e331055f) | May 01, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [abd7ed0c5c](https://linux-hardware.org/?probe=abd7ed0c5c) | May 01, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [dec71580c4](https://linux-hardware.org/?probe=dec71580c4) | May 01, 2022 |
| LG Electro... | P430-G.BC41P1               | Notebook    | [527905ca3b](https://linux-hardware.org/?probe=527905ca3b) | May 01, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [ab6b8eaa71](https://linux-hardware.org/?probe=ab6b8eaa71) | May 01, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [be68c0201a](https://linux-hardware.org/?probe=be68c0201a) | May 01, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [32052450db](https://linux-hardware.org/?probe=32052450db) | May 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8db041a1e4](https://linux-hardware.org/?probe=8db041a1e4) | May 01, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [ac3f2c5c61](https://linux-hardware.org/?probe=ac3f2c5c61) | May 01, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [83a8bbb313](https://linux-hardware.org/?probe=83a8bbb313) | May 01, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [48afcac3f0](https://linux-hardware.org/?probe=48afcac3f0) | May 01, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [89a959efc4](https://linux-hardware.org/?probe=89a959efc4) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| Samsung       | 950QCG                      | Convertible | [3010ee5185](https://linux-hardware.org/?probe=3010ee5185) | May 01, 2022 |
| Samsung       | 950QCG                      | Convertible | [257ee40584](https://linux-hardware.org/?probe=257ee40584) | May 01, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [88fcea9210](https://linux-hardware.org/?probe=88fcea9210) | Apr 30, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [0929d58de7](https://linux-hardware.org/?probe=0929d58de7) | Apr 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [3edd5f05f7](https://linux-hardware.org/?probe=3edd5f05f7) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [d45e1e88db](https://linux-hardware.org/?probe=d45e1e88db) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [41cec63ac6](https://linux-hardware.org/?probe=41cec63ac6) | Apr 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [48d3759522](https://linux-hardware.org/?probe=48d3759522) | Apr 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [8383d306f3](https://linux-hardware.org/?probe=8383d306f3) | Apr 30, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [b48ccc106e](https://linux-hardware.org/?probe=b48ccc106e) | Apr 30, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [8074a86bc7](https://linux-hardware.org/?probe=8074a86bc7) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b92517268e](https://linux-hardware.org/?probe=b92517268e) | Apr 30, 2022 |
| EVGA          | X58 SLI Classified Tyler... | Desktop     | [07254f2dbb](https://linux-hardware.org/?probe=07254f2dbb) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| ASUSTek       | G55VW                       | Notebook    | [6bd8a1b04a](https://linux-hardware.org/?probe=6bd8a1b04a) | Apr 29, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [19f5e16bce](https://linux-hardware.org/?probe=19f5e16bce) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [bce425f138](https://linux-hardware.org/?probe=bce425f138) | Apr 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [61bb949815](https://linux-hardware.org/?probe=61bb949815) | Apr 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [ea3b16fcfd](https://linux-hardware.org/?probe=ea3b16fcfd) | Apr 29, 2022 |
| Dell          | G5 5500                     | Notebook    | [c6064853ad](https://linux-hardware.org/?probe=c6064853ad) | Apr 29, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [e37bc471b1](https://linux-hardware.org/?probe=e37bc471b1) | Apr 29, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [2b7167b16e](https://linux-hardware.org/?probe=2b7167b16e) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | Notebook    | [34015c4874](https://linux-hardware.org/?probe=34015c4874) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| System76      | Oryx Pro                    | Notebook    | [cf999d4581](https://linux-hardware.org/?probe=cf999d4581) | Apr 29, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [a5d8e73a23](https://linux-hardware.org/?probe=a5d8e73a23) | Apr 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [aed5ee3ded](https://linux-hardware.org/?probe=aed5ee3ded) | Apr 28, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [be4ab0fd27](https://linux-hardware.org/?probe=be4ab0fd27) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [995f77010e](https://linux-hardware.org/?probe=995f77010e) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [e2293170b3](https://linux-hardware.org/?probe=e2293170b3) | Apr 28, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ab83eedd1f](https://linux-hardware.org/?probe=ab83eedd1f) | Apr 28, 2022 |
| Lenovo        | ThinkPad T431s 20ACS03P0... | Notebook    | [3c0878aee3](https://linux-hardware.org/?probe=3c0878aee3) | Apr 28, 2022 |
| System76      | Oryx Pro                    | Notebook    | [ae46ece731](https://linux-hardware.org/?probe=ae46ece731) | Apr 28, 2022 |
| MSI           | H55M-E23                    | Desktop     | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fee7e96d70](https://linux-hardware.org/?probe=fee7e96d70) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [a63dc69025](https://linux-hardware.org/?probe=a63dc69025) | Apr 28, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [1f26415f58](https://linux-hardware.org/?probe=1f26415f58) | Apr 28, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [46430e1117](https://linux-hardware.org/?probe=46430e1117) | Apr 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [5046e0575b](https://linux-hardware.org/?probe=5046e0575b) | Apr 28, 2022 |
| Dell          | 0NW73C A00                  | Desktop     | [344e2b816e](https://linux-hardware.org/?probe=344e2b816e) | Apr 28, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [2d79aab0aa](https://linux-hardware.org/?probe=2d79aab0aa) | Apr 28, 2022 |
| ASUSTek       | K40IN                       | Notebook    | [ab6a95da52](https://linux-hardware.org/?probe=ab6a95da52) | Apr 28, 2022 |
| Dell          | Latitude 7275               | Tablet      | [b7443972f3](https://linux-hardware.org/?probe=b7443972f3) | Apr 28, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [b664b8720e](https://linux-hardware.org/?probe=b664b8720e) | Apr 28, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [d48ed77abc](https://linux-hardware.org/?probe=d48ed77abc) | Apr 28, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [19e0445e6f](https://linux-hardware.org/?probe=19e0445e6f) | Apr 27, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [695d362d8f](https://linux-hardware.org/?probe=695d362d8f) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [c227966510](https://linux-hardware.org/?probe=c227966510) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [1275aa643d](https://linux-hardware.org/?probe=1275aa643d) | Apr 27, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d394f4e0d9](https://linux-hardware.org/?probe=d394f4e0d9) | Apr 27, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [824ccc1317](https://linux-hardware.org/?probe=824ccc1317) | Apr 27, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3e5933fe0d](https://linux-hardware.org/?probe=3e5933fe0d) | Apr 27, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [e51ff27a5a](https://linux-hardware.org/?probe=e51ff27a5a) | Apr 27, 2022 |
| Dell          | 0R1PCR A00                  | Desktop     | [feec38a0f5](https://linux-hardware.org/?probe=feec38a0f5) | Apr 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [c9fb277b57](https://linux-hardware.org/?probe=c9fb277b57) | Apr 27, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [7c99d7d4c5](https://linux-hardware.org/?probe=7c99d7d4c5) | Apr 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [82ad7e86b5](https://linux-hardware.org/?probe=82ad7e86b5) | Apr 27, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [25041b35de](https://linux-hardware.org/?probe=25041b35de) | Apr 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [863612cc05](https://linux-hardware.org/?probe=863612cc05) | Apr 27, 2022 |
| Purism        | Librem 15 v3                | Notebook    | [d2a13c9d0a](https://linux-hardware.org/?probe=d2a13c9d0a) | Apr 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [bbb524450f](https://linux-hardware.org/?probe=bbb524450f) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | Notebook    | [1fe2032839](https://linux-hardware.org/?probe=1fe2032839) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | Notebook    | [cabf0c7464](https://linux-hardware.org/?probe=cabf0c7464) | Apr 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [b7ac79ff8f](https://linux-hardware.org/?probe=b7ac79ff8f) | Apr 27, 2022 |
| MSI           | GS66 Stealth 10UG           | Notebook    | [77b699045a](https://linux-hardware.org/?probe=77b699045a) | Apr 27, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [30a22d7be3](https://linux-hardware.org/?probe=30a22d7be3) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| Acer          | Swift SF316-51              | Notebook    | [fe42983639](https://linux-hardware.org/?probe=fe42983639) | Apr 26, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d4b7580074](https://linux-hardware.org/?probe=d4b7580074) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d994ff2a13](https://linux-hardware.org/?probe=d994ff2a13) | Apr 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [885f468161](https://linux-hardware.org/?probe=885f468161) | Apr 26, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [aae937be8b](https://linux-hardware.org/?probe=aae937be8b) | Apr 25, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [0aa3a88c0c](https://linux-hardware.org/?probe=0aa3a88c0c) | Apr 25, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [ffb9cf10be](https://linux-hardware.org/?probe=ffb9cf10be) | Apr 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [f174d4ced7](https://linux-hardware.org/?probe=f174d4ced7) | Apr 20, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [1b3267b605](https://linux-hardware.org/?probe=1b3267b605) | Apr 18, 2022 |
| Dell          | Latitude 5590               | Notebook    | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| Dell          | Latitude 5590               | Notebook    | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |
| Dell          | Latitude E7270              | Notebook    | [79cc908dcc](https://linux-hardware.org/?probe=79cc908dcc) | Apr 08, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.17.5-76051705-generic  | 387       | 70.49%  |
| 5.16.19-76051619-generic | 117       | 21.31%  |
| 5.17.15-76051715-generic | 29        | 5.28%   |
| 5.16.15-76051615-generic | 3         | 0.55%   |
| 5.17.7-051707-generic    | 2         | 0.36%   |
| 5.17.5-051705-generic    | 2         | 0.36%   |
| 5.18.6-xanmod1           | 1         | 0.18%   |
| 5.18.4-xanmod1           | 1         | 0.18%   |
| 5.18.0-051800rc1-generic | 1         | 0.18%   |
| 5.17.9-051709-generic    | 1         | 0.18%   |
| 5.17.6-051706-generic    | 1         | 0.18%   |
| 5.17.5-tkg-bmq           | 1         | 0.18%   |
| 5.17.4-051704-generic    | 1         | 0.18%   |
| 5.17.2-xanmod1           | 1         | 0.18%   |
| 5.17.0-051700-generic    | 1         | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.5  | 390       | 71.04%  |
| 5.16.19 | 117       | 21.31%  |
| 5.17.15 | 29        | 5.28%   |
| 5.16.15 | 3         | 0.55%   |
| 5.17.7  | 2         | 0.36%   |
| 5.18.6  | 1         | 0.18%   |
| 5.18.4  | 1         | 0.18%   |
| 5.18.0  | 1         | 0.18%   |
| 5.17.9  | 1         | 0.18%   |
| 5.17.6  | 1         | 0.18%   |
| 5.17.4  | 1         | 0.18%   |
| 5.17.2  | 1         | 0.18%   |
| 5.17.0  | 1         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17    | 420       | 77.35%  |
| 5.16    | 120       | 22.1%   |
| 5.18    | 3         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 534       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 526       | 98.32%  |
| KDE5            | 4         | 0.75%   |
| Unknown         | 2         | 0.37%   |
| X-Cinnamon      | 1         | 0.19%   |
| LXQt            | 1         | 0.19%   |
| GNOME Flashback | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 516       | 96.27%  |
| Wayland | 18        | 3.36%   |
| Tty     | 1         | 0.19%   |
| Unknown | 1         | 0.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 428       | 80.15%  |
| GDM3    | 104       | 19.48%  |
| SDDM    | 1         | 0.19%   |
| GDM     | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 325       | 60.63%  |
| en_GB   | 33        | 6.16%   |
| pt_BR   | 30        | 5.6%    |
| de_DE   | 19        | 3.54%   |
| en_AU   | 17        | 3.17%   |
| fr_FR   | 15        | 2.8%    |
| C       | 14        | 2.61%   |
| en_CA   | 11        | 2.05%   |
| pl_PL   | 10        | 1.87%   |
| es_ES   | 8         | 1.49%   |
| it_IT   | 7         | 1.31%   |
| ru_RU   | 5         | 0.93%   |
| sv_SE   | 4         | 0.75%   |
| es_CL   | 3         | 0.56%   |
| pt_PT   | 2         | 0.37%   |
| nl_NL   | 2         | 0.37%   |
| ja_JP   | 2         | 0.37%   |
| fr_CA   | 2         | 0.37%   |
| es_MX   | 2         | 0.37%   |
| en_ZA   | 2         | 0.37%   |
| en_NZ   | 2         | 0.37%   |
| en_IN   | 2         | 0.37%   |
| de_CH   | 2         | 0.37%   |
| ro_RO   | 1         | 0.19%   |
| nl_BE   | 1         | 0.19%   |
| nb_NO   | 1         | 0.19%   |
| fr_BE   | 1         | 0.19%   |
| fi_FI   | 1         | 0.19%   |
| es_UY   | 1         | 0.19%   |
| es_GT   | 1         | 0.19%   |
| es_CO   | 1         | 0.19%   |
| es_AR   | 1         | 0.19%   |
| en_SG   | 1         | 0.19%   |
| en_PH   | 1         | 0.19%   |
| en_IL   | 1         | 0.19%   |
| en_IE   | 1         | 0.19%   |
| en_DK   | 1         | 0.19%   |
| de_AT   | 1         | 0.19%   |
| cs_CZ   | 1         | 0.19%   |
| Unknown | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 434       | 81.27%  |
| EFI  | 100       | 18.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 510       | 95.51%  |
| Btrfs   | 16        | 3%      |
| Overlay | 6         | 1.12%   |
| Xfs     | 2         | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 427       | 79.81%  |
| GPT     | 102       | 19.07%  |
| MBR     | 6         | 1.12%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 520       | 97.38%  |
| Yes       | 14        | 2.62%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 489       | 91.4%   |
| Yes       | 46        | 8.6%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 101       | 18.91%  |
| Dell                | 87        | 16.29%  |
| Lenovo              | 58        | 10.86%  |
| Hewlett-Packard     | 50        | 9.36%   |
| Gigabyte Technology | 41        | 7.68%   |
| MSI                 | 40        | 7.49%   |
| Apple               | 30        | 5.62%   |
| Acer                | 24        | 4.49%   |
| ASRock              | 15        | 2.81%   |
| System76            | 12        | 2.25%   |
| Toshiba             | 9         | 1.69%   |
| Samsung Electronics | 7         | 1.31%   |
| Intel               | 6         | 1.12%   |
| Alienware           | 5         | 0.94%   |
| Microsoft           | 4         | 0.75%   |
| HUAWEI              | 4         | 0.75%   |
| Google              | 4         | 0.75%   |
| Unknown             | 4         | 0.75%   |
| Fujitsu             | 3         | 0.56%   |
| Notebook            | 2         | 0.37%   |
| Medion              | 2         | 0.37%   |
| Framework           | 2         | 0.37%   |
| Foxconn             | 2         | 0.37%   |
| TUXEDO              | 1         | 0.19%   |
| Timi                | 1         | 0.19%   |
| Supermicro          | 1         | 0.19%   |
| Sony                | 1         | 0.19%   |
| SIEMENS             | 1         | 0.19%   |
| Semp Toshiba        | 1         | 0.19%   |
| Schenker            | 1         | 0.19%   |
| Razer               | 1         | 0.19%   |
| Quanta              | 1         | 0.19%   |
| Purism              | 1         | 0.19%   |
| Positivo            | 1         | 0.19%   |
| PC Specialist       | 1         | 0.19%   |
| NZXT                | 1         | 0.19%   |
| Monster             | 1         | 0.19%   |
| LG Electronics      | 1         | 0.19%   |
| EVGA                | 1         | 0.19%   |
| Eluktronics         | 1         | 0.19%   |
| ECS                 | 1         | 0.19%   |
| Biostar             | 1         | 0.19%   |
| BESSTAR Tech        | 1         | 0.19%   |
| AZW                 | 1         | 0.19%   |
| A-DATA Technology   | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 7         | 1.31%   |
| System76 Oryx Pro                     | 5         | 0.94%   |
| ASUS All Series                       | 5         | 0.94%   |
| Gigabyte X570 AORUS ELITE             | 4         | 0.75%   |
| HP Pavilion Notebook                  | 3         | 0.56%   |
| Gigabyte B450 AORUS M                 | 3         | 0.56%   |
| Dell OptiPlex 3020                    | 3         | 0.56%   |
| Dell Latitude E7240                   | 3         | 0.56%   |
| ASUS ROG CROSSHAIR VIII DARK HERO     | 3         | 0.56%   |
| Apple MacBookAir7,2                   | 3         | 0.56%   |
| System76 Thelio                       | 2         | 0.37%   |
| MSI MS-7D32                           | 2         | 0.37%   |
| MSI MS-7C37                           | 2         | 0.37%   |
| Lenovo V14-IIL 82C4                   | 2         | 0.37%   |
| Lenovo IdeaPad S145-15API 81V7        | 2         | 0.37%   |
| HP ProDesk 600 G1 SFF                 | 2         | 0.37%   |
| HP OMEN Laptop 15-en0xxx              | 2         | 0.37%   |
| HP 15 Notebook PC                     | 2         | 0.37%   |
| Google Lulu                           | 2         | 0.37%   |
| Gigabyte Z170-HD3P                    | 2         | 0.37%   |
| Gigabyte Z170-Gaming K3               | 2         | 0.37%   |
| Framework Laptop                      | 2         | 0.37%   |
| Dell XPS 15 9570                      | 2         | 0.37%   |
| Dell XPS 15 9510                      | 2         | 0.37%   |
| Dell XPS 13 9310                      | 2         | 0.37%   |
| Dell Vostro 5402                      | 2         | 0.37%   |
| Dell Precision M4800                  | 2         | 0.37%   |
| Dell Latitude E7470                   | 2         | 0.37%   |
| Dell Latitude E7270                   | 2         | 0.37%   |
| Dell Latitude E6540                   | 2         | 0.37%   |
| Dell Inspiron 5566                    | 2         | 0.37%   |
| Dell Inspiron 5547                    | 2         | 0.37%   |
| Dell Inspiron 3442                    | 2         | 0.37%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 2         | 0.37%   |
| ASUS ROG STRIX B450-I GAMING          | 2         | 0.37%   |
| ASUS ROG CROSSHAIR VIII HERO          | 2         | 0.37%   |
| ASUS PRIME B450M-A                    | 2         | 0.37%   |
| ASUS P6X58D PREMIUM                   | 2         | 0.37%   |
| ASRock B450 Gaming K4                 | 2         | 0.37%   |
| Apple MacBookPro7,1                   | 2         | 0.37%   |
| Apple MacBookPro11,1                  | 2         | 0.37%   |
| Apple MacBookAir6,2                   | 2         | 0.37%   |
| Acer Aspire A515-45                   | 2         | 0.37%   |
| Toshiba Satellite S50-A               | 1         | 0.19%   |
| Toshiba Satellite P850                | 1         | 0.19%   |
| Toshiba Satellite L850-1D5            | 1         | 0.19%   |
| Toshiba Satellite L755                | 1         | 0.19%   |
| Toshiba Satellite L50D-C              | 1         | 0.19%   |
| Toshiba Satellite L10W-B-101          | 1         | 0.19%   |
| Toshiba Satellite C55t-C              | 1         | 0.19%   |
| Toshiba QOSMIO X770                   | 1         | 0.19%   |
| Toshiba PORTEGE R830                  | 1         | 0.19%   |
| Timi RedmiBook Pro 14S                | 1         | 0.19%   |
| System76 Thelio Major                 | 1         | 0.19%   |
| System76 Pangolin                     | 1         | 0.19%   |
| System76 Lemur Pro                    | 1         | 0.19%   |
| System76 Galago Pro                   | 1         | 0.19%   |
| System76 Darter Pro                   | 1         | 0.19%   |
| Supermicro X8SIL                      | 1         | 0.19%   |
| Sony SVF15A1M2ES                      | 1         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ASUS ROG              | 27        | 5.06%   |
| Dell Inspiron         | 24        | 4.49%   |
| Lenovo ThinkPad       | 22        | 4.12%   |
| Dell Latitude         | 16        | 3%      |
| Acer Aspire           | 16        | 3%      |
| Dell XPS              | 14        | 2.62%   |
| Dell Precision        | 14        | 2.62%   |
| ASUS PRIME            | 13        | 2.43%   |
| Lenovo IdeaPad        | 10        | 1.87%   |
| HP Pavilion           | 8         | 1.5%    |
| Toshiba Satellite     | 7         | 1.31%   |
| HP EliteBook          | 7         | 1.31%   |
| Gigabyte X570         | 7         | 1.31%   |
| Dell Vostro           | 7         | 1.31%   |
| Unknown               | 7         | 1.31%   |
| Lenovo Legion         | 6         | 1.12%   |
| HP ProBook            | 6         | 1.12%   |
| Dell OptiPlex         | 6         | 1.12%   |
| System76 Oryx         | 5         | 0.94%   |
| ASUS All              | 5         | 0.94%   |
| Microsoft Surface     | 4         | 0.75%   |
| HP OMEN               | 4         | 0.75%   |
| HP Laptop             | 4         | 0.75%   |
| ASUS ZenBook          | 4         | 0.75%   |
| ASUS VivoBook         | 4         | 0.75%   |
| ASUS TUF              | 4         | 0.75%   |
| System76 Thelio       | 3         | 0.56%   |
| Lenovo Yoga           | 3         | 0.56%   |
| Lenovo ThinkBook      | 3         | 0.56%   |
| HP Spectre            | 3         | 0.56%   |
| HP ENVY               | 3         | 0.56%   |
| Gigabyte B450         | 3         | 0.56%   |
| ASRock B450           | 3         | 0.56%   |
| Apple MacBookPro11    | 3         | 0.56%   |
| Apple MacBookAir7     | 3         | 0.56%   |
| Alienware Aurora      | 3         | 0.56%   |
| MSI MS-7D32           | 2         | 0.37%   |
| MSI MS-7C37           | 2         | 0.37%   |
| MSI Modern            | 2         | 0.37%   |
| MSI GF63              | 2         | 0.37%   |
| Lenovo V14-IIL        | 2         | 0.37%   |
| Lenovo ThinkCentre    | 2         | 0.37%   |
| Lenovo IdeaCentre     | 2         | 0.37%   |
| HP ZBook              | 2         | 0.37%   |
| HP ProDesk            | 2         | 0.37%   |
| HP EliteDesk          | 2         | 0.37%   |
| HP 15                 | 2         | 0.37%   |
| Google Lulu           | 2         | 0.37%   |
| Gigabyte Z390         | 2         | 0.37%   |
| Gigabyte Z170-HD3P    | 2         | 0.37%   |
| Gigabyte Z170-Gaming  | 2         | 0.37%   |
| Gigabyte X470         | 2         | 0.37%   |
| Gigabyte B550         | 2         | 0.37%   |
| Gigabyte AB350-Gaming | 2         | 0.37%   |
| Framework Laptop      | 2         | 0.37%   |
| Dell G7               | 2         | 0.37%   |
| ASUS P6X58D           | 2         | 0.37%   |
| ASRock Z390           | 2         | 0.37%   |
| Apple MacBookPro7     | 2         | 0.37%   |
| Apple MacBookPro14    | 2         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 74        | 13.86%  |
| 2020 | 70        | 13.11%  |
| 2019 | 63        | 11.8%   |
| 2018 | 52        | 9.74%   |
| 2016 | 44        | 8.24%   |
| 2013 | 38        | 7.12%   |
| 2017 | 32        | 5.99%   |
| 2011 | 30        | 5.62%   |
| 2015 | 29        | 5.43%   |
| 2014 | 28        | 5.24%   |
| 2012 | 20        | 3.75%   |
| 2009 | 18        | 3.37%   |
| 2022 | 15        | 2.81%   |
| 2010 | 14        | 2.62%   |
| 2008 | 5         | 0.94%   |
| 2007 | 1         | 0.19%   |
| 2006 | 1         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 299       | 55.99%  |
| Desktop     | 200       | 37.45%  |
| Convertible | 13        | 2.43%   |
| All in one  | 9         | 1.69%   |
| Mini pc     | 8         | 1.5%    |
| Tablet      | 5         | 0.94%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 534       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 523       | 97.94%  |
| Yes  | 11        | 2.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 149       | 27.8%   |
| 4.01-8.0        | 110       | 20.52%  |
| 8.01-16.0       | 94        | 17.54%  |
| 32.01-64.0      | 93        | 17.35%  |
| 3.01-4.0        | 60        | 11.19%  |
| 64.01-256.0     | 23        | 4.29%   |
| 24.01-32.0      | 3         | 0.56%   |
| More than 256.0 | 2         | 0.37%   |
| 1.01-2.0        | 2         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 190       | 34.05%  |
| 4.01-8.0   | 134       | 24.01%  |
| 3.01-4.0   | 118       | 21.15%  |
| 1.01-2.0   | 83        | 14.87%  |
| 8.01-16.0  | 26        | 4.66%   |
| 16.01-24.0 | 6         | 1.08%   |
| 24.01-32.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 284       | 52.99%  |
| 2      | 162       | 30.22%  |
| 3      | 53        | 9.89%   |
| 4      | 15        | 2.8%    |
| 5      | 9         | 1.68%   |
| 6      | 7         | 1.31%   |
| 7      | 2         | 0.37%   |
| 11     | 1         | 0.19%   |
| 10     | 1         | 0.19%   |
| 9      | 1         | 0.19%   |
| 0      | 1         | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 392       | 73.41%  |
| Yes       | 142       | 26.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 448       | 83.58%  |
| No        | 88        | 16.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 452       | 84.64%  |
| No        | 82        | 15.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 380       | 71.03%  |
| No        | 155       | 28.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| USA                   | 177       | 33.02%  |
| Brazil                | 42        | 7.84%   |
| Germany               | 28        | 5.22%   |
| Australia             | 24        | 4.48%   |
| UK                    | 20        | 3.73%   |
| Canada                | 20        | 3.73%   |
| France                | 18        | 3.36%   |
| India                 | 16        | 2.99%   |
| Netherlands           | 13        | 2.43%   |
| Italy                 | 10        | 1.87%   |
| Switzerland           | 9         | 1.68%   |
| Poland                | 9         | 1.68%   |
| Sweden                | 8         | 1.49%   |
| Russia                | 8         | 1.49%   |
| Norway                | 8         | 1.49%   |
| Spain                 | 7         | 1.31%   |
| Mexico                | 7         | 1.31%   |
| Japan                 | 7         | 1.31%   |
| Austria               | 5         | 0.93%   |
| Turkey                | 4         | 0.75%   |
| Thailand              | 4         | 0.75%   |
| South Africa          | 4         | 0.75%   |
| Ireland               | 4         | 0.75%   |
| Greece                | 4         | 0.75%   |
| Belgium               | 4         | 0.75%   |
| Argentina             | 4         | 0.75%   |
| Saudi Arabia          | 3         | 0.56%   |
| Romania               | 3         | 0.56%   |
| Philippines           | 3         | 0.56%   |
| New Zealand           | 3         | 0.56%   |
| Hungary               | 3         | 0.56%   |
| Hong Kong             | 3         | 0.56%   |
| Finland               | 3         | 0.56%   |
| Czechia               | 3         | 0.56%   |
| Chile                 | 3         | 0.56%   |
| Uruguay               | 2         | 0.37%   |
| Tunisia               | 2         | 0.37%   |
| Singapore             | 2         | 0.37%   |
| Portugal              | 2         | 0.37%   |
| Peru                  | 2         | 0.37%   |
| Panama                | 2         | 0.37%   |
| Morocco               | 2         | 0.37%   |
| Malaysia              | 2         | 0.37%   |
| Georgia               | 2         | 0.37%   |
| Egypt                 | 2         | 0.37%   |
| Croatia               | 2         | 0.37%   |
| Colombia              | 2         | 0.37%   |
| Bulgaria              | 2         | 0.37%   |
| Vietnam               | 1         | 0.19%   |
| Venezuela             | 1         | 0.19%   |
| Uzbekistan            | 1         | 0.19%   |
| South Korea           | 1         | 0.19%   |
| Slovenia              | 1         | 0.19%   |
| Slovakia              | 1         | 0.19%   |
| Republic of the Congo | 1         | 0.19%   |
| Nicaragua             | 1         | 0.19%   |
| Maldives              | 1         | 0.19%   |
| Lithuania             | 1         | 0.19%   |
| Latvia                | 1         | 0.19%   |
| Kosovo                | 1         | 0.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Melbourne        | 7         | 1.29%   |
| Zurich           | 6         | 1.11%   |
| Vienna           | 5         | 0.92%   |
| Sydney           | 5         | 0.92%   |
| Mannheim         | 5         | 0.92%   |
| Sao Paulo        | 4         | 0.74%   |
| Oslo             | 4         | 0.74%   |
| Istanbul         | 4         | 0.74%   |
| Warsaw           | 3         | 0.55%   |
| Toronto          | 3         | 0.55%   |
| Seattle          | 3         | 0.55%   |
| San Jose         | 3         | 0.55%   |
| San Francisco    | 3         | 0.55%   |
| San Antonio      | 3         | 0.55%   |
| Moscow           | 3         | 0.55%   |
| Denver           | 3         | 0.55%   |
| Columbus         | 3         | 0.55%   |
| Brisbane         | 3         | 0.55%   |
| Berlin           | 3         | 0.55%   |
| Tunis            | 2         | 0.37%   |
| Tucson           | 2         | 0.37%   |
| Trondheim        | 2         | 0.37%   |
| Tallahassee      | 2         | 0.37%   |
| Stuttgart        | 2         | 0.37%   |
| Springfield      | 2         | 0.37%   |
| Singapore        | 2         | 0.37%   |
| Sapporo          | 2         | 0.37%   |
| Saint Paul       | 2         | 0.37%   |
| Rome             | 2         | 0.37%   |
| Riyadh           | 2         | 0.37%   |
| Riverview        | 2         | 0.37%   |
| Rio de Janeiro   | 2         | 0.37%   |
| Richmond         | 2         | 0.37%   |
| Recife           | 2         | 0.37%   |
| Quezon City      | 2         | 0.37%   |
| Prague           | 2         | 0.37%   |
| Paris            | 2         | 0.37%   |
| Panama City      | 2         | 0.37%   |
| Ogden            | 2         | 0.37%   |
| Nuremberg        | 2         | 0.37%   |
| Munich           | 2         | 0.37%   |
| Mumbai           | 2         | 0.37%   |
| Mendoza          | 2         | 0.37%   |
| Manaus           | 2         | 0.37%   |
| Madrid           | 2         | 0.37%   |
| London           | 2         | 0.37%   |
| Kalamazoo        | 2         | 0.37%   |
| Itatiba          | 2         | 0.37%   |
| Heraklion        | 2         | 0.37%   |
| Elk Grove        | 2         | 0.37%   |
| Edmonton         | 2         | 0.37%   |
| Durham           | 2         | 0.37%   |
| Danville         | 2         | 0.37%   |
| Cork             | 2         | 0.37%   |
| Colorado Springs | 2         | 0.37%   |
| Cleveland        | 2         | 0.37%   |
| Chicago          | 2         | 0.37%   |
| Catunda          | 2         | 0.37%   |
| Cairo            | 2         | 0.37%   |
| Budapest         | 2         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 160       | 210    | 19.23%  |
| Seagate                        | 111       | 143    | 13.34%  |
| WDC                            | 94        | 126    | 11.3%   |
| SanDisk                        | 56        | 69     | 6.73%   |
| Toshiba                        | 45        | 54     | 5.41%   |
| Kingston                       | 44        | 52     | 5.29%   |
| Crucial                        | 38        | 50     | 4.57%   |
| SK hynix                       | 26        | 27     | 3.13%   |
| Phison                         | 21        | 27     | 2.52%   |
| Hitachi                        | 21        | 27     | 2.52%   |
| Intel                          | 19        | 23     | 2.28%   |
| Micron Technology              | 18        | 19     | 2.16%   |
| A-DATA Technology              | 16        | 18     | 1.92%   |
| Unknown                        | 15        | 18     | 1.8%    |
| Apple                          | 15        | 18     | 1.8%    |
| HGST                           | 14        | 14     | 1.68%   |
| Silicon Motion                 | 9         | 11     | 1.08%   |
| PNY                            | 9         | 9      | 1.08%   |
| Micron/Crucial Technology      | 6         | 8      | 0.72%   |
| KIOXIA                         | 6         | 7      | 0.72%   |
| LITEONIT                       | 5         | 5      | 0.6%    |
| Intenso                        | 5         | 5      | 0.6%    |
| LITEON                         | 4         | 4      | 0.48%   |
| China                          | 4         | 5      | 0.48%   |
| ADATA Technology               | 4         | 4      | 0.48%   |
| Union Memory (Shenzhen)        | 3         | 4      | 0.36%   |
| SPCC                           | 3         | 5      | 0.36%   |
| MyDigitalSSD                   | 3         | 3      | 0.36%   |
| Lexar                          | 3         | 3      | 0.36%   |
| KingSpec                       | 3         | 3      | 0.36%   |
| Fujitsu                        | 3         | 4      | 0.36%   |
| Team                           | 2         | 2      | 0.24%   |
| PNY USB                        | 2         | 2      | 0.24%   |
| Patriot                        | 2         | 2      | 0.24%   |
| MAXIO Technology (Hangzhou)    | 2         | 2      | 0.24%   |
| KingFast                       | 2         | 3      | 0.24%   |
| Hewlett-Packard                | 2         | 2      | 0.24%   |
| Corsair                        | 2         | 3      | 0.24%   |
| ASMT                           | 2         | 3      | 0.24%   |
| YMTC                           | 1         | 1      | 0.12%   |
| USB3.0                         | 1         | 1      | 0.12%   |
| TwinMOS                        | 1         | 1      | 0.12%   |
| TurXun                         | 1         | 1      | 0.12%   |
| Transcend                      | 1         | 2      | 0.12%   |
| TO Exter                       | 1         | 1      | 0.12%   |
| T-FORCE                        | 1         | 1      | 0.12%   |
| SSSTC                          | 1         | 1      | 0.12%   |
| Solid State Storage Technology | 1         | 1      | 0.12%   |
| SATAFIRM                       | 1         | 1      | 0.12%   |
| SABRENT                        | 1         | 2      | 0.12%   |
| Ramaxel Technology             | 1         | 1      | 0.12%   |
| Qunion                         | 1         | 1      | 0.12%   |
| PUSKILL                        | 1         | 1      | 0.12%   |
| OWC                            | 1         | 1      | 0.12%   |
| OEM                            | 1         | 1      | 0.12%   |
| OCZ                            | 1         | 1      | 0.12%   |
| Mushkin                        | 1         | 2      | 0.12%   |
| Maxtor                         | 1         | 1      | 0.12%   |
| MaxDigital                     | 1         | 1      | 0.12%   |
| Mass                           | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 18        | 1.93%   |
| Samsung NVMe SSD Drive 1TB             | 16        | 1.71%   |
| Seagate ST2000DM008-2FR102 2TB         | 13        | 1.39%   |
| SanDisk NVMe SSD Drive 1TB             | 13        | 1.39%   |
| Kingston SA400S37240G 240GB SSD        | 13        | 1.39%   |
| Samsung NVMe SSD Drive 2TB             | 11        | 1.18%   |
| Samsung SSD 850 EVO 250GB              | 9         | 0.96%   |
| Samsung NVMe SSD Drive 512GB           | 9         | 0.96%   |
| SK hynix NVMe SSD Drive 512GB          | 8         | 0.86%   |
| Crucial CT1000MX500SSD1 1TB            | 8         | 0.86%   |
| Samsung SSD 970 EVO Plus 1TB           | 7         | 0.75%   |
| Phison NVMe SSD Drive 1TB              | 7         | 0.75%   |
| SK hynix NVMe SSD Drive 1024GB         | 6         | 0.64%   |
| Seagate ST500DM002-1BD142 500GB        | 6         | 0.64%   |
| SanDisk NVMe SSD Drive 512GB           | 6         | 0.64%   |
| Samsung SSD 860 EVO 500GB              | 6         | 0.64%   |
| Samsung SSD 850 EVO 500GB              | 6         | 0.64%   |
| Samsung NVMe SSD Drive 256GB           | 6         | 0.64%   |
| Samsung NVMe SSD Drive 1024GB          | 6         | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB               | 5         | 0.54%   |
| Seagate ST4000DM004-2CV104 4TB         | 5         | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB         | 5         | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB         | 5         | 0.54%   |
| SanDisk NVMe SSD Drive 500GB           | 5         | 0.54%   |
| Samsung SSD 860 EVO 1TB                | 5         | 0.54%   |
| Phison NVMe SSD Drive 2TB              | 5         | 0.54%   |
| Kingston SA400S37120G 120GB SSD        | 5         | 0.54%   |
| Intel NVMe SSD Drive 512GB             | 5         | 0.54%   |
| Crucial CT2000MX500SSD1 2TB            | 5         | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB               | 4         | 0.43%   |
| Toshiba MQ04ABF100 1TB                 | 4         | 0.43%   |
| Toshiba DT01ACA200 2TB                 | 4         | 0.43%   |
| Seagate ST1000LM049-2GH172 1TB         | 4         | 0.43%   |
| Seagate Expansion 1TB                  | 4         | 0.43%   |
| Samsung SSD 980 1TB                    | 4         | 0.43%   |
| PNY CS900 240GB SSD                    | 4         | 0.43%   |
| Phison NVMe SSD Drive 1024GB           | 4         | 0.43%   |
| Kingston NVMe SSD Drive 512GB          | 4         | 0.43%   |
| Intel NVMe SSD Drive 1024GB            | 4         | 0.43%   |
| HGST HTS721010A9E630 1TB               | 4         | 0.43%   |
| Crucial CT240BX500SSD1 240GB           | 4         | 0.43%   |
| ADATA NVMe SSD Drive 256GB             | 4         | 0.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 3         | 0.32%   |
| Unknown MMC Card  32GB                 | 3         | 0.32%   |
| Unknown MMC Card  128GB                | 3         | 0.32%   |
| Toshiba NVMe SSD Drive 512GB           | 3         | 0.32%   |
| Toshiba MQ01ABD100 1TB                 | 3         | 0.32%   |
| Toshiba HDWD120 2TB                    | 3         | 0.32%   |
| Toshiba DT01ACA100 1TB                 | 3         | 0.32%   |
| SK hynix NVMe SSD Drive 256GB          | 3         | 0.32%   |
| Seagate ST9320325AS 320GB              | 3         | 0.32%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 3         | 0.32%   |
| Seagate ST4000DM000-1F2168 4TB         | 3         | 0.32%   |
| Seagate ST31000528AS 1TB               | 3         | 0.32%   |
| Seagate ST2000LM007-1R8174 2TB         | 3         | 0.32%   |
| Seagate ST2000DM001-1ER164 2TB         | 3         | 0.32%   |
| Seagate ST1000DM003-1ER162 1TB         | 3         | 0.32%   |
| SanDisk SSD PLUS 240GB                 | 3         | 0.32%   |
| SanDisk SSD PLUS 240 GB                | 3         | 0.32%   |
| SanDisk NVMe SSD Drive 256GB           | 3         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 107       | 136    | 40.07%  |
| WDC                 | 68        | 90     | 25.47%  |
| Toshiba             | 36        | 43     | 13.48%  |
| Hitachi             | 21        | 27     | 7.87%   |
| HGST                | 14        | 14     | 5.24%   |
| Samsung Electronics | 8         | 11     | 3%      |
| Apple               | 5         | 5      | 1.87%   |
| Fujitsu             | 2         | 3      | 0.75%   |
| ASMT                | 2         | 3      | 0.75%   |
| Unknown             | 1         | 1      | 0.37%   |
| Maxtor              | 1         | 1      | 0.37%   |
| Intenso             | 1         | 1      | 0.37%   |
| HGST HDN            | 1         | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 65        | 81     | 23.81%  |
| Kingston            | 34        | 39     | 12.45%  |
| Crucial             | 33        | 45     | 12.09%  |
| SanDisk             | 26        | 31     | 9.52%   |
| WDC                 | 17        | 21     | 6.23%   |
| A-DATA Technology   | 11        | 13     | 4.03%   |
| PNY                 | 9         | 9      | 3.3%    |
| Apple               | 9         | 10     | 3.3%    |
| Intel               | 6         | 6      | 2.2%    |
| Micron Technology   | 5         | 5      | 1.83%   |
| LITEONIT            | 5         | 5      | 1.83%   |
| China               | 4         | 5      | 1.47%   |
| SK hynix            | 3         | 3      | 1.1%    |
| MyDigitalSSD        | 3         | 3      | 1.1%    |
| LITEON              | 3         | 3      | 1.1%    |
| Lexar               | 3         | 3      | 1.1%    |
| KingSpec            | 3         | 3      | 1.1%    |
| Toshiba             | 2         | 2      | 0.73%   |
| SPCC                | 2         | 3      | 0.73%   |
| PNY USB             | 2         | 2      | 0.73%   |
| Patriot             | 2         | 2      | 0.73%   |
| Hewlett-Packard     | 2         | 2      | 0.73%   |
| USB3.0              | 1         | 1      | 0.37%   |
| TwinMOS             | 1         | 1      | 0.37%   |
| Transcend           | 1         | 2      | 0.37%   |
| TO Exter            | 1         | 1      | 0.37%   |
| Seagate             | 1         | 1      | 0.37%   |
| SATAFIRM            | 1         | 1      | 0.37%   |
| Ramaxel Technology  | 1         | 1      | 0.37%   |
| PUSKILL             | 1         | 1      | 0.37%   |
| OWC                 | 1         | 1      | 0.37%   |
| OCZ                 | 1         | 1      | 0.37%   |
| Mushkin             | 1         | 2      | 0.37%   |
| KingFast            | 1         | 1      | 0.37%   |
| KingDian            | 1         | 1      | 0.37%   |
| KINGBANK            | 1         | 1      | 0.37%   |
| Intenso             | 1         | 1      | 0.37%   |
| INTEL SS            | 1         | 1      | 0.37%   |
| Gigabyte Technology | 1         | 1      | 0.37%   |
| Fujitsu             | 1         | 1      | 0.37%   |
| FORESEE             | 1         | 2      | 0.37%   |
| Corsair             | 1         | 2      | 0.37%   |
| Apacer              | 1         | 1      | 0.37%   |
| AFOX                | 1         | 1      | 0.37%   |
| Aarvex              | 1         | 1      | 0.37%   |
| Unknown             | 1         | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 246       | 342    | 33.42%  |
| SSD     | 241       | 324    | 32.74%  |
| HDD     | 223       | 336    | 30.3%   |
| MMC     | 13        | 16     | 1.77%   |
| Unknown | 13        | 14     | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 372       | 635    | 56.02%  |
| NVMe | 246       | 338    | 37.05%  |
| SAS  | 33        | 43     | 4.97%   |
| MMC  | 13        | 16     | 1.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 255       | 338    | 50.1%   |
| 0.51-1.0   | 144       | 189    | 28.29%  |
| 1.01-2.0   | 69        | 82     | 13.56%  |
| 3.01-4.0   | 19        | 23     | 3.73%   |
| 2.01-3.0   | 12        | 15     | 2.36%   |
| 4.01-10.0  | 10        | 13     | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 148       | 27.36%  |
| 251-500        | 141       | 26.06%  |
| 501-1000       | 112       | 20.7%   |
| 1001-2000      | 49        | 9.06%   |
| More than 3000 | 36        | 6.65%   |
| 2001-3000      | 17        | 3.14%   |
| 51-100         | 16        | 2.96%   |
| 1-20           | 11        | 2.03%   |
| 21-50          | 8         | 1.48%   |
| Unknown        | 3         | 0.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 163       | 29.69%  |
| 21-50          | 132       | 24.04%  |
| 101-250        | 83        | 15.12%  |
| 51-100         | 64        | 11.66%  |
| 251-500        | 43        | 7.83%   |
| 501-1000       | 23        | 4.19%   |
| 1001-2000      | 22        | 4.01%   |
| More than 3000 | 12        | 2.19%   |
| 2001-3000      | 4         | 0.73%   |
| Unknown        | 3         | 0.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 6.25%   |
| WDC WD1001FALS-00E8B0 1TB             | 1         | 1      | 6.25%   |
| Toshiba MQ01ACF050 500GB              | 1         | 1      | 6.25%   |
| SK hynix PC711 HFS001TDE9X073N 1TB    | 1         | 1      | 6.25%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 6.25%   |
| Seagate ST500LM030-2E717D 500GB       | 1         | 1      | 6.25%   |
| Seagate ST5000LM000-2AN170 5TB        | 1         | 1      | 6.25%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 1      | 6.25%   |
| Seagate ST1000LX015-1U7172 1TB        | 1         | 1      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 850 PRO 256GB | 1         | 1      | 6.25%   |
| Kingston SV300S37A240G 240GB SSD      | 1         | 1      | 6.25%   |
| Intel SSDPEKNW010T8 1TB               | 1         | 1      | 6.25%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 2      | 6.25%   |
| Hitachi HDP725050GLA360 500GB         | 1         | 1      | 6.25%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 37.5%   |
| WDC                 | 2         | 2      | 12.5%   |
| Hitachi             | 2         | 3      | 12.5%   |
| Toshiba             | 1         | 1      | 6.25%   |
| SK hynix            | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Kingston            | 1         | 1      | 6.25%   |
| Intel               | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 50%     |
| WDC     | 2         | 2      | 16.67%  |
| Hitachi | 2         | 3      | 16.67%  |
| Toshiba | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 13     | 75%     |
| NVMe | 2         | 2      | 12.5%   |
| SSD  | 2         | 2      | 12.5%   |

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
| Detected | 436       | 834    | 76.9%   |
| Works    | 115       | 181    | 20.28%  |
| Malfunc  | 16        | 17     | 2.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 329       | 43.12%  |
| AMD                            | 127       | 16.64%  |
| Samsung Electronics            | 106       | 13.89%  |
| SanDisk                        | 38        | 4.98%   |
| Phison Electronics             | 24        | 3.15%   |
| SK hynix                       | 23        | 3.01%   |
| Micron Technology              | 13        | 1.7%    |
| Silicon Motion                 | 11        | 1.44%   |
| ASMedia Technology             | 11        | 1.44%   |
| Micron/Crucial Technology      | 10        | 1.31%   |
| Toshiba America Info Systems   | 9         | 1.18%   |
| Nvidia                         | 9         | 1.18%   |
| Kingston Technology Company    | 9         | 1.18%   |
| ADATA Technology               | 7         | 0.92%   |
| Marvell Technology Group       | 6         | 0.79%   |
| KIOXIA                         | 6         | 0.79%   |
| Union Memory (Shenzhen)        | 3         | 0.39%   |
| Seagate Technology             | 3         | 0.39%   |
| JMicron Technology             | 3         | 0.39%   |
| Solid State Storage Technology | 2         | 0.26%   |
| Realtek Semiconductor          | 2         | 0.26%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.26%   |
| Apple                          | 2         | 0.26%   |
| Yangtze Memory Technologies    | 1         | 0.13%   |
| VIA Technologies               | 1         | 0.13%   |
| Unknown                        | 1         | 0.13%   |
| Silicon Image                  | 1         | 0.13%   |
| Shenzhen Longsys Electronics   | 1         | 0.13%   |
| LSI Logic / Symbios Logic      | 1         | 0.13%   |
| Lite-On Technology             | 1         | 0.13%   |
| Broadcom / LSI                 | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 101       | 11.83%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 66        | 7.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 25        | 2.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 24        | 2.81%   |
| AMD 400 Series Chipset SATA Controller                                                  | 24        | 2.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 20        | 2.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 19        | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17        | 1.99%   |
| SK hynix Gold P31 SSD                                                                   | 16        | 1.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 16        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 15        | 1.76%   |
| Samsung NVMe SSD Controller 980                                                         | 13        | 1.52%   |
| Phison E12 NVMe Controller                                                              | 13        | 1.52%   |
| Micron Non-Volatile memory controller                                                   | 13        | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 13        | 1.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13        | 1.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 1.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12        | 1.41%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12        | 1.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 11        | 1.29%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 10        | 1.17%   |
| Intel SATA Controller [RAID mode]                                                       | 10        | 1.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 10        | 1.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10        | 1.17%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 9         | 1.05%   |
| Intel SSD 660P Series                                                                   | 9         | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 9         | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 9         | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 8         | 0.94%   |
| Samsung Electronics SATA controller                                                     | 7         | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7         | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7         | 0.82%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 6         | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6         | 0.7%    |
| KIOXIA Non-Volatile memory controller                                                   | 6         | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 6         | 0.7%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6         | 0.7%    |
| SanDisk Non-Volatile memory controller                                                  | 5         | 0.59%   |
| Phison PS5013 E13 NVMe Controller                                                       | 5         | 0.59%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 5         | 0.59%   |
| Nvidia MCP79 AHCI Controller                                                            | 5         | 0.59%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5         | 0.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 0.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 0.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 0.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 0.59%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5         | 0.59%   |
| ADATA Non-Volatile memory controller                                                    | 5         | 0.59%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 4         | 0.47%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4         | 0.47%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 4         | 0.47%   |
| Kingston Company Company Non-Volatile memory controller                                 | 4         | 0.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 0.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 0.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 0.47%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4         | 0.47%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 394       | 53.39%  |
| NVMe | 247       | 33.47%  |
| RAID | 56        | 7.59%   |
| IDE  | 39        | 5.28%   |
| SAS  | 2         | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 381       | 71.35%  |
| AMD    | 153       | 28.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 10        | 1.87%   |
| AMD Ryzen 5 3600 6-Core Processor             | 9         | 1.69%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 8         | 1.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.31%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 7         | 1.31%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.12%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 6         | 1.12%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 1.12%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 6         | 1.12%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.94%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.94%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 5         | 0.94%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 0.75%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 4         | 0.75%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 4         | 0.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 0.75%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 4         | 0.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.75%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 0.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.75%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.75%   |
| AMD FX-8350 Eight-Core Processor              | 4         | 0.75%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 4         | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 3         | 0.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.56%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 0.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.56%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.56%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 0.56%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 3         | 0.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.56%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 3         | 0.56%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 0.56%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.56%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 3         | 0.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 0.56%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 3         | 0.56%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 3         | 0.56%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.56%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 3         | 0.56%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 0.56%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 3         | 0.56%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 0.56%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 3         | 0.56%   |
| AMD Ryzen 5 1600X Six-Core Processor          | 3         | 0.56%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 2         | 0.37%   |
| Intel Core i9-10900X CPU @ 3.70GHz            | 2         | 0.37%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 0.37%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.37%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.37%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 142       | 26.59%  |
| Intel Core i5           | 97        | 18.16%  |
| AMD Ryzen 7             | 46        | 8.61%   |
| AMD Ryzen 5             | 46        | 8.61%   |
| Other                   | 42        | 7.87%   |
| Intel Core i3           | 33        | 6.18%   |
| AMD Ryzen 9             | 22        | 4.12%   |
| Intel Core 2 Duo        | 14        | 2.62%   |
| Intel Celeron           | 11        | 2.06%   |
| Intel Xeon              | 10        | 1.87%   |
| Intel Core i9           | 10        | 1.87%   |
| Intel Pentium           | 9         | 1.69%   |
| AMD FX                  | 6         | 1.12%   |
| AMD A8                  | 6         | 1.12%   |
| AMD Ryzen 7 PRO         | 5         | 0.94%   |
| AMD Ryzen 3             | 5         | 0.94%   |
| Intel Core 2 Quad       | 3         | 0.56%   |
| AMD Ryzen Threadripper  | 3         | 0.56%   |
| AMD A6                  | 3         | 0.56%   |
| Intel Pentium Gold      | 2         | 0.37%   |
| Intel Core 2            | 2         | 0.37%   |
| AMD A10                 | 2         | 0.37%   |
| Intel Pentium Silver    | 1         | 0.19%   |
| Intel Pentium Dual-Core | 1         | 0.19%   |
| Intel Pentium Dual      | 1         | 0.19%   |
| Intel Pentium D         | 1         | 0.19%   |
| Intel Core m5           | 1         | 0.19%   |
| Intel Core m3           | 1         | 0.19%   |
| Intel Atom              | 1         | 0.19%   |
| AMD Sempron             | 1         | 0.19%   |
| AMD Ryzen 5 PRO         | 1         | 0.19%   |
| AMD PRO A10             | 1         | 0.19%   |
| AMD Phenom II X6        | 1         | 0.19%   |
| AMD Phenom II X3        | 1         | 0.19%   |
| AMD Phenom              | 1         | 0.19%   |
| AMD Athlon II X4        | 1         | 0.19%   |
| AMD Athlon II X2        | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 185       | 34.64%  |
| 2      | 154       | 28.84%  |
| 8      | 85        | 15.92%  |
| 6      | 73        | 13.67%  |
| 12     | 13        | 2.43%   |
| 16     | 10        | 1.87%   |
| 10     | 5         | 0.94%   |
| 14     | 3         | 0.56%   |
| 32     | 2         | 0.37%   |
| 3      | 2         | 0.37%   |
| 24     | 1         | 0.19%   |
| 1      | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 531       | 99.44%  |
| 2      | 3         | 0.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 434       | 81.27%  |
| 1      | 100       | 18.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 534       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 414       | 77.53%  |
| 0x806ec    | 8         | 1.5%    |
| 0x806c1    | 7         | 1.31%   |
| 0x906ea    | 5         | 0.94%   |
| 0x806d1    | 5         | 0.94%   |
| 0x40651    | 5         | 0.94%   |
| 0x0a50000c | 5         | 0.94%   |
| 0x0800820d | 5         | 0.94%   |
| 0x906e9    | 4         | 0.75%   |
| 0x806ea    | 4         | 0.75%   |
| 0x806e9    | 4         | 0.75%   |
| 0x706e5    | 4         | 0.75%   |
| 0x406e3    | 4         | 0.75%   |
| 0x306c3    | 4         | 0.75%   |
| 0x306a9    | 4         | 0.75%   |
| 0x08600106 | 4         | 0.75%   |
| 0xa0652    | 3         | 0.56%   |
| 0x506e3    | 3         | 0.56%   |
| 0x08701021 | 3         | 0.56%   |
| 0x08608103 | 3         | 0.56%   |
| 0x906ec    | 2         | 0.37%   |
| 0x906a3    | 2         | 0.37%   |
| 0x90672    | 2         | 0.37%   |
| 0x806eb    | 2         | 0.37%   |
| 0x806c2    | 2         | 0.37%   |
| 0x306d4    | 2         | 0.37%   |
| 0x206a7    | 2         | 0.37%   |
| 0x0a201016 | 2         | 0.37%   |
| 0x08600104 | 2         | 0.37%   |
| 0x08600103 | 2         | 0.37%   |
| 0x08001138 | 2         | 0.37%   |
| 0xa0655    | 1         | 0.19%   |
| 0xa0653    | 1         | 0.19%   |
| 0x50657    | 1         | 0.19%   |
| 0x1067a    | 1         | 0.19%   |
| 0x10676    | 1         | 0.19%   |
| 0x0a404101 | 1         | 0.19%   |
| 0x0a201006 | 1         | 0.19%   |
| 0x08701013 | 1         | 0.19%   |
| 0x08301039 | 1         | 0.19%   |
| 0x08108109 | 1         | 0.19%   |
| 0x08101016 | 1         | 0.19%   |
| 0x0810100b | 1         | 0.19%   |
| 0x08001137 | 1         | 0.19%   |
| 0x0600611a | 1         | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 89        | 16.67%  |
| Haswell          | 56        | 10.49%  |
| Zen 3            | 45        | 8.43%   |
| Zen 2            | 40        | 7.49%   |
| Skylake          | 33        | 6.18%   |
| SandyBridge      | 32        | 5.99%   |
| Unknown          | 31        | 5.81%   |
| IvyBridge        | 28        | 5.24%   |
| CometLake        | 25        | 4.68%   |
| Zen+             | 21        | 3.93%   |
| Penryn           | 19        | 3.56%   |
| Broadwell        | 18        | 3.37%   |
| TigerLake        | 16        | 3%      |
| IceLake          | 13        | 2.43%   |
| Zen              | 10        | 1.87%   |
| Westmere         | 8         | 1.5%    |
| Nehalem          | 8         | 1.5%    |
| Silvermont       | 7         | 1.31%   |
| Piledriver       | 7         | 1.31%   |
| Puma             | 6         | 1.12%   |
| K10              | 5         | 0.94%   |
| Excavator        | 4         | 0.75%   |
| Core             | 3         | 0.56%   |
| Alderlake Hybrid | 3         | 0.56%   |
| Goldmont         | 2         | 0.37%   |
| Steamroller      | 1         | 0.19%   |
| NetBurst         | 1         | 0.19%   |
| K10 Llano        | 1         | 0.19%   |
| Jaguar           | 1         | 0.19%   |
| Goldmont plus    | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 278       | 42.64%  |
| Nvidia                     | 222       | 34.05%  |
| AMD                        | 151       | 23.16%  |
| Matrox Electronics Systems | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 26        | 3.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 2.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 2.54%   |
| AMD Cezanne                                                                              | 17        | 2.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 2.25%   |
| AMD Renoir                                                                               | 15        | 2.25%   |
| Intel HD Graphics 620                                                                    | 14        | 2.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 1.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 1.95%   |
| Intel HD Graphics 5500                                                                   | 12        | 1.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 1.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 1.65%   |
| Intel HD Graphics 530                                                                    | 10        | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 1.5%    |
| AMD Lucienne                                                                             | 10        | 1.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10        | 1.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 9         | 1.35%   |
| Intel UHD Graphics 620                                                                   | 9         | 1.35%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 9         | 1.35%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 8         | 1.2%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 8         | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.2%    |
| Intel HD Graphics 630                                                                    | 8         | 1.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 7         | 1.05%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 7         | 1.05%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6         | 0.9%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 6         | 0.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 0.9%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 6         | 0.9%    |
| Nvidia TU117M                                                                            | 5         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 0.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 0.75%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 5         | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 4         | 0.6%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.6%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 4         | 0.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 0.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.6%    |
| Intel AlderLake-S GT1                                                                    | 4         | 0.6%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 0.6%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 4         | 0.6%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 4         | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.45%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.45%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 3         | 0.45%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 0.45%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 0.45%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 0.45%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.45%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.45%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 3         | 0.45%   |
| Nvidia GA106 [GeForce RTX 3060]                                                          | 3         | 0.45%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                                       | 3         | 0.45%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 3         | 0.45%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.45%   |
| Intel HD Graphics 6000                                                                   | 3         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 178       | 33.15%  |
| 1 x Nvidia           | 120       | 22.35%  |
| 1 x AMD              | 112       | 20.86%  |
| Intel + Nvidia       | 80        | 14.9%   |
| AMD + Nvidia         | 17        | 3.17%   |
| Intel + AMD          | 12        | 2.23%   |
| 2 x AMD              | 9         | 1.68%   |
| 2 x Nvidia           | 5         | 0.93%   |
| Other                | 1         | 0.19%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.19%   |
| 1 x Matrox           | 1         | 0.19%   |
| AMD + 2 x Nvidia     | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 335       | 62.38%  |
| Proprietary | 191       | 35.57%  |
| Unknown     | 11        | 2.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 384       | 71.24%  |
| 7.01-8.0   | 38        | 7.05%   |
| 3.01-4.0   | 29        | 5.38%   |
| 5.01-6.0   | 22        | 4.08%   |
| 1.01-2.0   | 22        | 4.08%   |
| 8.01-16.0  | 21        | 3.9%    |
| 0.01-0.5   | 10        | 1.86%   |
| 2.01-3.0   | 7         | 1.3%    |
| 0.51-1.0   | 4         | 0.74%   |
| 32.01-64.0 | 1         | 0.19%   |
| 16.01-24.0 | 1         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 72        | 11.71%  |
| BOE                  | 63        | 10.24%  |
| LG Display           | 61        | 9.92%   |
| AU Optronics         | 60        | 9.76%   |
| Dell                 | 49        | 7.97%   |
| Chimei Innolux       | 48        | 7.8%    |
| Goldstar             | 38        | 6.18%   |
| Apple                | 23        | 3.74%   |
| Sharp                | 18        | 2.93%   |
| Hewlett-Packard      | 17        | 2.76%   |
| AOC                  | 17        | 2.76%   |
| Acer                 | 17        | 2.76%   |
| ASUSTek Computer     | 15        | 2.44%   |
| Ancor Communications | 13        | 2.11%   |
| BenQ                 | 11        | 1.79%   |
| PANDA                | 8         | 1.3%    |
| Lenovo               | 8         | 1.3%    |
| Iiyama               | 6         | 0.98%   |
| ViewSonic            | 4         | 0.65%   |
| Unknown              | 4         | 0.65%   |
| NEC Computers        | 4         | 0.65%   |
| MSI                  | 4         | 0.65%   |
| Sceptre Tech         | 3         | 0.49%   |
| Philips              | 3         | 0.49%   |
| InfoVision           | 3         | 0.49%   |
| Gigabyte Technology  | 3         | 0.49%   |
| CSO                  | 3         | 0.49%   |
| Vizio                | 2         | 0.33%   |
| Viotek               | 2         | 0.33%   |
| Vestel Elektronik    | 2         | 0.33%   |
| ITE                  | 2         | 0.33%   |
| Hitachi              | 2         | 0.33%   |
| Eizo                 | 2         | 0.33%   |
| ___                  | 1         | 0.16%   |
| VOXICON              | 1         | 0.16%   |
| Valve                | 1         | 0.16%   |
| Unknown (XXX)        | 1         | 0.16%   |
| TMX                  | 1         | 0.16%   |
| TCL                  | 1         | 0.16%   |
| Sony                 | 1         | 0.16%   |
| SKY                  | 1         | 0.16%   |
| SGT                  | 1         | 0.16%   |
| RTK                  | 1         | 0.16%   |
| Positivo             | 1         | 0.16%   |
| Pioneer              | 1         | 0.16%   |
| Orion                | 1         | 0.16%   |
| ONN                  | 1         | 0.16%   |
| Onkyo                | 1         | 0.16%   |
| OEM                  | 1         | 0.16%   |
| Medion Akoya         | 1         | 0.16%   |
| LG Electronics       | 1         | 0.16%   |
| KDC                  | 1         | 0.16%   |
| JDI                  | 1         | 0.16%   |
| IOD                  | 1         | 0.16%   |
| Impression           | 1         | 0.16%   |
| Huion                | 1         | 0.16%   |
| GVE                  | 1         | 0.16%   |
| GDH                  | 1         | 0.16%   |
| Fujitsu Siemens      | 1         | 0.16%   |
| CVT                  | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 5         | 0.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.79%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                     | 4         | 0.63%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                 | 4         | 0.63%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 4         | 0.63%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 3         | 0.48%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3         | 0.48%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 3         | 0.48%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 3         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.48%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch          | 3         | 0.48%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 3         | 0.48%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                         | 2         | 0.32%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 2         | 0.32%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.32%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 293x165mm 13.2-inch | 2         | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.32%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 2         | 0.32%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.32%   |
| LG Display LCD Monitor LGD0627 1920x1080 294x165mm 13.3-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.32%   |
| Lenovo LBG AIO PC LEN8000 1920x1080 476x268mm 21.5-inch               | 2         | 0.32%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 2         | 0.32%   |
| Dell U2212HM DELD048 1920x1080 475x267mm 21.5-inch                    | 2         | 0.32%   |
| Dell AW3821DW DELA17F 3840x1600 880x367mm 37.5-inch                   | 2         | 0.32%   |
| Dell 1704FPV DEL3016 1280x1024 338x270mm 17.0-inch                    | 2         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 2         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 2         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.32%   |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                 | 2         | 0.32%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 0.32%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 0.32%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 2         | 0.32%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                 | 2         | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.32%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                  | 2         | 0.32%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 0.32%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.32%   |
| AU Optronics LCD Monitor AUO4999 1920x1080 344x193mm 15.5-inch        | 2         | 0.32%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch         | 2         | 0.32%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 2         | 0.32%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.32%   |
| ASUSTek Computer VG279 AUS2782 1920x1080 598x336mm 27.0-inch          | 2         | 0.32%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                      | 2         | 0.32%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2         | 0.32%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 2         | 0.32%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 2         | 0.32%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 287       | 49.06%  |
| 1366x768 (WXGA)    | 85        | 14.53%  |
| 3840x2160 (4K)     | 44        | 7.52%   |
| 2560x1440 (QHD)    | 36        | 6.15%   |
| 1600x900 (HD+)     | 19        | 3.25%   |
| 1920x1200 (WUXGA)  | 15        | 2.56%   |
| 1680x1050 (WSXGA+) | 12        | 2.05%   |
| 3440x1440          | 11        | 1.88%   |
| 1440x900 (WXGA+)   | 11        | 1.88%   |
| 2560x1600          | 10        | 1.71%   |
| 2560x1080          | 10        | 1.71%   |
| 1280x1024 (SXGA)   | 7         | 1.2%    |
| 2880x1800          | 5         | 0.85%   |
| 3840x1080          | 4         | 0.68%   |
| 1280x800 (WXGA)    | 4         | 0.68%   |
| 3840x1600          | 3         | 0.51%   |
| Unknown            | 3         | 0.51%   |
| 2736x1824          | 2         | 0.34%   |
| 2256x1504          | 2         | 0.34%   |
| 2160x1440          | 2         | 0.34%   |
| 1920x540           | 2         | 0.34%   |
| 1360x768           | 2         | 0.34%   |
| 3840x2400          | 1         | 0.17%   |
| 3840x1200          | 1         | 0.17%   |
| 3456x2160          | 1         | 0.17%   |
| 3200x1800 (QHD+)   | 1         | 0.17%   |
| 3040x900           | 1         | 0.17%   |
| 3000x2000          | 1         | 0.17%   |
| 1920x1280          | 1         | 0.17%   |
| 1280x1080          | 1         | 0.17%   |
| 1024x768 (XGA)     | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 151       | 24.88%  |
| 13      | 66        | 10.87%  |
| 27      | 52        | 8.57%   |
| 14      | 44        | 7.25%   |
| 24      | 43        | 7.08%   |
| 23      | 42        | 6.92%   |
| 17      | 29        | 4.78%   |
| 21      | 28        | 4.61%   |
| 31      | 22        | 3.62%   |
| 34      | 19        | 3.13%   |
| 12      | 15        | 2.47%   |
| Unknown | 11        | 1.81%   |
| 22      | 9         | 1.48%   |
| 20      | 7         | 1.15%   |
| 84      | 6         | 0.99%   |
| 19      | 6         | 0.99%   |
| 16      | 6         | 0.99%   |
| 32      | 5         | 0.82%   |
| 25      | 5         | 0.82%   |
| 37      | 4         | 0.66%   |
| 18      | 4         | 0.66%   |
| 11      | 4         | 0.66%   |
| 72      | 3         | 0.49%   |
| 54      | 3         | 0.49%   |
| 48      | 3         | 0.49%   |
| 26      | 3         | 0.49%   |
| 49      | 2         | 0.33%   |
| 46      | 2         | 0.33%   |
| 28      | 2         | 0.33%   |
| 65      | 1         | 0.16%   |
| 55      | 1         | 0.16%   |
| 52      | 1         | 0.16%   |
| 47      | 1         | 0.16%   |
| 43      | 1         | 0.16%   |
| 42      | 1         | 0.16%   |
| 35      | 1         | 0.16%   |
| 33      | 1         | 0.16%   |
| 30      | 1         | 0.16%   |
| 29      | 1         | 0.16%   |
| 10      | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 229       | 38.23%  |
| 501-600     | 131       | 21.87%  |
| 201-300     | 57        | 9.52%   |
| 401-500     | 49        | 8.18%   |
| 351-400     | 35        | 5.84%   |
| 601-700     | 32        | 5.34%   |
| 701-800     | 24        | 4.01%   |
| 1001-1500   | 15        | 2.5%    |
| Unknown     | 11        | 1.84%   |
| 1501-2000   | 9         | 1.5%    |
| 801-900     | 6         | 1%      |
| 901-1000    | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 439       | 78.82%  |
| 16/10   | 62        | 11.13%  |
| 21/9    | 25        | 4.49%   |
| 3/2     | 8         | 1.44%   |
| Unknown | 8         | 1.44%   |
| 5/4     | 7         | 1.26%   |
| 32/9    | 5         | 0.9%    |
| 4/3     | 2         | 0.36%   |
| 3.20    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 153       | 25.59%  |
| 201-250        | 95        | 15.89%  |
| 81-90          | 81        | 13.55%  |
| 301-350        | 55        | 9.2%    |
| 351-500        | 50        | 8.36%   |
| 71-80          | 30        | 5.02%   |
| 121-130        | 25        | 4.18%   |
| 251-300        | 22        | 3.68%   |
| 151-200        | 18        | 3.01%   |
| More than 1000 | 15        | 2.51%   |
| 61-70          | 13        | 2.17%   |
| 501-1000       | 13        | 2.17%   |
| Unknown        | 11        | 1.84%   |
| 141-150        | 7         | 1.17%   |
| 51-60          | 4         | 0.67%   |
| 111-120        | 3         | 0.5%    |
| 91-100         | 2         | 0.33%   |
| 41-50          | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 180       | 31.14%  |
| 51-100        | 172       | 29.76%  |
| 101-120       | 146       | 25.26%  |
| 161-240       | 43        | 7.44%   |
| More than 240 | 15        | 2.6%    |
| 1-50          | 11        | 1.9%    |
| Unknown       | 11        | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 419       | 77.88%  |
| 2     | 93        | 17.29%  |
| 3     | 13        | 2.42%   |
| 0     | 12        | 2.23%   |
| 6     | 1         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 289       | 34.45%  |
| Intel                           | 281       | 33.49%  |
| Qualcomm Atheros                | 99        | 11.8%   |
| Broadcom                        | 46        | 5.48%   |
| MediaTek                        | 16        | 1.91%   |
| Broadcom Limited                | 16        | 1.91%   |
| TP-Link                         | 11        | 1.31%   |
| Ralink Technology               | 6         | 0.72%   |
| Nvidia                          | 6         | 0.72%   |
| Marvell Technology Group        | 6         | 0.72%   |
| Ralink                          | 5         | 0.6%    |
| NetGear                         | 5         | 0.6%    |
| ASIX Electronics                | 5         | 0.6%    |
| Aquantia                        | 5         | 0.6%    |
| Samsung Electronics             | 4         | 0.48%   |
| DisplayLink                     | 4         | 0.48%   |
| Dell                            | 4         | 0.48%   |
| ASUSTek Computer                | 4         | 0.48%   |
| Microsoft                       | 3         | 0.36%   |
| Xiaomi                          | 2         | 0.24%   |
| InterBiometrics                 | 2         | 0.24%   |
| Hewlett-Packard                 | 2         | 0.24%   |
| D-Link                          | 2         | 0.24%   |
| Sitecom Europe                  | 1         | 0.12%   |
| SIEMENS                         | 1         | 0.12%   |
| Qualcomm Atheros Communications | 1         | 0.12%   |
| Qualcomm                        | 1         | 0.12%   |
| Prolific Technology             | 1         | 0.12%   |
| OPPO Electronics                | 1         | 0.12%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.12%   |
| Mellanox Technologies           | 1         | 0.12%   |
| Lenovo                          | 1         | 0.12%   |
| IMC Networks                    | 1         | 0.12%   |
| Hyperkin                        | 1         | 0.12%   |
| Google                          | 1         | 0.12%   |
| Gemtek                          | 1         | 0.12%   |
| D-Link System                   | 1         | 0.12%   |
| Belkin Components               | 1         | 0.12%   |
| Accton Technology               | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 186       | 18.94%  |
| Intel Wi-Fi 6 AX200                                               | 48        | 4.89%   |
| Intel I211 Gigabit Network Connection                             | 35        | 3.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 29        | 2.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 2.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 23        | 2.34%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 16        | 1.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 1.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 14        | 1.43%   |
| Intel Wireless 7265                                               | 14        | 1.43%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 13        | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 1.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 1.22%   |
| Intel Wireless 8265 / 8275                                        | 12        | 1.22%   |
| Intel Wireless 8260                                               | 12        | 1.22%   |
| Intel Wireless 7260                                               | 12        | 1.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 12        | 1.22%   |
| Intel Ethernet Controller I225-V                                  | 12        | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 1.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 11        | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 11        | 1.12%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 11        | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 1.02%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 1.02%   |
| Intel Ethernet Connection (2) I219-V                              | 9         | 0.92%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 9         | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 7         | 0.71%   |
| Realtek 802.11ac NIC                                              | 7         | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.61%   |
| Intel Wireless-AC 9260                                            | 6         | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 6         | 0.61%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 5         | 0.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.51%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.51%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 5         | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.51%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.41%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.41%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.41%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 0.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 3         | 0.31%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.31%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3         | 0.31%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.31%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.31%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 228       | 47.6%   |
| Qualcomm Atheros                | 80        | 16.7%   |
| Realtek Semiconductor           | 54        | 11.27%  |
| Broadcom                        | 38        | 7.93%   |
| MediaTek                        | 16        | 3.34%   |
| Broadcom Limited                | 15        | 3.13%   |
| TP-Link                         | 9         | 1.88%   |
| Ralink Technology               | 6         | 1.25%   |
| Ralink                          | 5         | 1.04%   |
| NetGear                         | 5         | 1.04%   |
| Dell                            | 4         | 0.84%   |
| ASUSTek Computer                | 4         | 0.84%   |
| Microsoft                       | 3         | 0.63%   |
| Marvell Technology Group        | 3         | 0.63%   |
| D-Link                          | 2         | 0.42%   |
| Sitecom Europe                  | 1         | 0.21%   |
| Qualcomm Atheros Communications | 1         | 0.21%   |
| IMC Networks                    | 1         | 0.21%   |
| Gemtek                          | 1         | 0.21%   |
| D-Link System                   | 1         | 0.21%   |
| Belkin Components               | 1         | 0.21%   |
| Accton Technology               | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 48        | 9.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 23        | 4.75%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 16        | 3.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 14        | 2.89%   |
| Intel Wireless 7265                                            | 14        | 2.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 13        | 2.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 2.48%   |
| Intel Wireless 8265 / 8275                                     | 12        | 2.48%   |
| Intel Wireless 8260                                            | 12        | 2.48%   |
| Intel Wireless 7260                                            | 12        | 2.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 12        | 2.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 11        | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 11        | 2.27%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 11        | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 2.07%   |
| Intel Wi-Fi 6 AX201                                            | 10        | 2.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 2.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 10        | 2.07%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 9         | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 1.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 7         | 1.45%   |
| Realtek 802.11ac NIC                                           | 7         | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 1.45%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 1.24%   |
| Intel Wireless-AC 9260                                         | 6         | 1.24%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5         | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 1.03%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 5         | 1.03%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 5         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 0.83%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 0.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 0.83%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 0.62%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 0.62%   |
| NetGear A6210                                                  | 3         | 0.62%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 3         | 0.62%   |
| Intel Wireless Gigabit 17265                                   | 3         | 0.62%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 0.62%   |
| Dell Hub of E-Port Replicator                                  | 3         | 0.62%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 0.62%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.41%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.41%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 0.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 0.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.41%   |
| Microsoft Xbox 360 Wireless Adapter                            | 2         | 0.41%   |
| MediaTek WLAN controller                                       | 2         | 0.41%   |
| Intel Wireless 3165                                            | 2         | 0.41%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 0.41%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 0.41%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 0.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 0.41%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                        | 2         | 0.41%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 261       | 54.04%  |
| Intel                         | 140       | 28.99%  |
| Qualcomm Atheros              | 27        | 5.59%   |
| Broadcom                      | 17        | 3.52%   |
| Nvidia                        | 6         | 1.24%   |
| ASIX Electronics              | 5         | 1.04%   |
| Aquantia                      | 5         | 1.04%   |
| Samsung Electronics           | 4         | 0.83%   |
| DisplayLink                   | 4         | 0.83%   |
| Marvell Technology Group      | 3         | 0.62%   |
| Xiaomi                        | 2         | 0.41%   |
| TP-Link                       | 2         | 0.41%   |
| Qualcomm                      | 1         | 0.21%   |
| OPPO Electronics              | 1         | 0.21%   |
| OnePlus Technology (Shenzhen) | 1         | 0.21%   |
| Mellanox Technologies         | 1         | 0.21%   |
| Lenovo                        | 1         | 0.21%   |
| Hewlett-Packard               | 1         | 0.21%   |
| Broadcom Limited              | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 186       | 37.96%  |
| Intel I211 Gigabit Network Connection                             | 35        | 7.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 29        | 5.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 5.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 3.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 2.65%   |
| Intel Ethernet Controller I225-V                                  | 12        | 2.45%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 2.45%   |
| Intel Ethernet Connection (2) I219-V                              | 9         | 1.84%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.22%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 1.22%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 1.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.02%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 1.02%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.41%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.41%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.41%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.41%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.41%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.41%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 0.41%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.41%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.41%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.41%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.41%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.41%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.2%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.2%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.2%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.2%    |
| Realtek Realtek Ethernet controller                               | 1         | 0.2%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.2%    |
| Qualcomm Redmi 9T                                                 | 1         | 0.2%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.2%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.2%    |
| OPPO Find X2 Lite                                                 | 1         | 0.2%    |
| OnePlus (Shenzhen) SM8150-MTP _SN:63F1CF71                        | 1         | 0.2%    |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 0.2%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.2%    |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 453       | 49.89%  |
| Ethernet | 447       | 49.23%  |
| Modem    | 5         | 0.55%   |
| Unknown  | 3         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 337       | 60.94%  |
| Ethernet | 216       | 39.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 303       | 56.64%  |
| 1     | 202       | 37.76%  |
| 3     | 22        | 4.11%   |
| 0     | 6         | 1.12%   |
| 4     | 2         | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 385       | 71.83%  |
| Yes  | 151       | 28.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 204       | 53.54%  |
| Qualcomm Atheros Communications | 38        | 9.97%   |
| Apple                           | 31        | 8.14%   |
| Realtek Semiconductor           | 19        | 4.99%   |
| IMC Networks                    | 19        | 4.99%   |
| Foxconn / Hon Hai               | 14        | 3.67%   |
| Cambridge Silicon Radio         | 13        | 3.41%   |
| Broadcom                        | 11        | 2.89%   |
| Lite-On Technology              | 8         | 2.1%    |
| ASUSTek Computer                | 7         | 1.84%   |
| Toshiba                         | 4         | 1.05%   |
| Marvell Semiconductor           | 3         | 0.79%   |
| Hewlett-Packard                 | 3         | 0.79%   |
| Realtek                         | 1         | 0.26%   |
| Ralink Technology               | 1         | 0.26%   |
| Ralink                          | 1         | 0.26%   |
| Opticis                         | 1         | 0.26%   |
| MediaTek                        | 1         | 0.26%   |
| Foxconn International           | 1         | 0.26%   |
| Dell                            | 1         | 0.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 52        | 13.65%  |
| Intel Bluetooth wireless interface                  | 48        | 12.6%   |
| Intel AX200 Bluetooth                               | 44        | 11.55%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 29        | 7.61%   |
| Qualcomm Atheros  Bluetooth Device                  | 20        | 5.25%   |
| Realtek Bluetooth Radio                             | 16        | 4.2%    |
| Apple Bluetooth USB Host Controller                 | 15        | 3.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 3.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 2.89%   |
| Intel AX210 Bluetooth                               | 10        | 2.62%   |
| Apple Bluetooth Host Controller                     | 10        | 2.62%   |
| IMC Networks Bluetooth Device                       | 9         | 2.36%   |
| IMC Networks Wireless_Device                        | 6         | 1.57%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 1.57%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 1.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 1.31%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 5         | 1.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.31%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 0.79%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.79%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 0.79%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 0.79%   |
| ASUS Bluetooth Radio                                | 3         | 0.79%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.79%   |
| Apple Bluetooth HCI                                 | 3         | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.52%   |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 0.52%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 2         | 0.52%   |
| Lite-On Bluetooth Device                            | 2         | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.52%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.52%   |
| Broadcom BCM20702A0                                 | 2         | 0.52%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.26%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.26%   |
| Toshiba Bluetooth Radio                             | 1         | 0.26%   |
| Toshiba BCM43142A0                                  | 1         | 0.26%   |
| Realtek Bluetooth Radio                             | 1         | 0.26%   |
| Ralink CSR BS8510                                   | 1         | 0.26%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.26%   |
| Opticis Bluetooth Radio                             | 1         | 0.26%   |
| MediaTek Wireless_Device                            | 1         | 0.26%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.26%   |
| Lite-On Wireless_Device                             | 1         | 0.26%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.26%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.26%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.26%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.26%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.26%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.26%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 0.26%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.26%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.26%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.26%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.26%   |
| Broadcom BCM20702A0 Bluetooth                       | 1         | 0.26%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 366       | 43.42%  |
| AMD                                  | 183       | 21.71%  |
| Nvidia                               | 175       | 20.76%  |
| C-Media Electronics                  | 16        | 1.9%    |
| Logitech                             | 10        | 1.19%   |
| Kingston Technology                  | 8         | 0.95%   |
| Focusrite-Novation                   | 6         | 0.71%   |
| SteelSeries ApS                      | 5         | 0.59%   |
| GN Netcom                            | 5         | 0.59%   |
| Texas Instruments                    | 4         | 0.47%   |
| JMTek                                | 4         | 0.47%   |
| Corsair                              | 4         | 0.47%   |
| Sony                                 | 3         | 0.36%   |
| Razer USA                            | 3         | 0.36%   |
| Micro Star International             | 3         | 0.36%   |
| Lenovo                               | 3         | 0.36%   |
| Creative Labs                        | 3         | 0.36%   |
| Antlion Audio                        | 3         | 0.36%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.24%   |
| Sennheiser Communications            | 2         | 0.24%   |
| Hewlett-Packard                      | 2         | 0.24%   |
| Generalplus Technology               | 2         | 0.24%   |
| Creative Technology                  | 2         | 0.24%   |
| ASUSTek Computer                     | 2         | 0.24%   |
| Yamaha                               | 1         | 0.12%   |
| Valve Software                       | 1         | 0.12%   |
| USB MIDI                             | 1         | 0.12%   |
| Unknown                              | 1         | 0.12%   |
| Turtle Beach                         | 1         | 0.12%   |
| Shenzhen Rapoo Technology            | 1         | 0.12%   |
| SAVITECH                             | 1         | 0.12%   |
| Samsung Electronics                  | 1         | 0.12%   |
| Samson Technologies                  | 1         | 0.12%   |
| Plantronics                          | 1         | 0.12%   |
| Native Instruments                   | 1         | 0.12%   |
| Microsoft                            | 1         | 0.12%   |
| Medeli Electronics                   | 1         | 0.12%   |
| JOUNIVO JV601                        | 1         | 0.12%   |
| iConnectivity                        | 1         | 0.12%   |
| Google                               | 1         | 0.12%   |
| Giga-Byte Technology                 | 1         | 0.12%   |
| GEMBIRD                              | 1         | 0.12%   |
| FiiO Electronics Technology          | 1         | 0.12%   |
| fifinemicrophone.com                 | 1         | 0.12%   |
| FIFINE Microphones                   | 1         | 0.12%   |
| DEXP BK-20                           | 1         | 0.12%   |
| Cambridge Silicon Radio              | 1         | 0.12%   |
| C&T                                  | 1         | 0.12%   |
| Blue Microphones                     | 1         | 0.12%   |
| BEHRINGER International              | 1         | 0.12%   |
| Apple                                | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 60        | 5.98%   |
| AMD Starship/Matisse HD Audio Controller                                   | 47        | 4.68%   |
| Intel Sunrise Point-LP HD Audio                                            | 39        | 3.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 36        | 3.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30        | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 28        | 2.79%   |
| Intel Haswell-ULT HD Audio Controller                                      | 26        | 2.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 25        | 2.49%   |
| Intel 8 Series HD Audio Controller                                         | 25        | 2.49%   |
| Nvidia Audio device                                                        | 21        | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 21        | 2.09%   |
| Intel Comet Lake PCH cAVS                                                  | 20        | 1.99%   |
| Nvidia GP106 High Definition Audio Controller                              | 18        | 1.79%   |
| Nvidia GA104 High Definition Audio Controller                              | 18        | 1.79%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 18        | 1.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 18        | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16        | 1.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 16        | 1.59%   |
| Intel Broadwell-U Audio Controller                                         | 16        | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16        | 1.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 1.49%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 15        | 1.49%   |
| Intel 200 Series PCH HD Audio                                              | 14        | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13        | 1.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 1.29%   |
| Nvidia TU106 High Definition Audio Controller                              | 11        | 1.1%    |
| Nvidia GP104 High Definition Audio Controller                              | 11        | 1.1%    |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 1.1%    |
| Nvidia TU104 HD Audio Controller                                           | 10        | 1%      |
| Intel CM238 HD Audio Controller                                            | 10        | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 1%      |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 1%      |
| AMD FCH Azalia Controller                                                  | 10        | 1%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10        | 1%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 9         | 0.9%    |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.8%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 0.7%    |
| AMD Navi 10 HDMI Audio                                                     | 7         | 0.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 7         | 0.7%    |
| Nvidia GA102 High Definition Audio Controller                              | 6         | 0.6%    |
| Kingston Technology HyperX 7.1 Audio                                       | 6         | 0.6%    |
| Intel Alder Lake-S HD Audio Controller                                     | 6         | 0.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 0.6%    |
| Nvidia MCP79 High Definition Audio                                         | 5         | 0.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 0.5%    |
| Nvidia GK104 HDMI Audio Controller                                         | 5         | 0.5%    |
| Intel Audio device                                                         | 5         | 0.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5         | 0.5%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5         | 0.5%    |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 5         | 0.5%    |
| Nvidia TU102 High Definition Audio Controller                              | 4         | 0.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 0.4%    |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.4%    |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 0.4%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 0.4%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33        | 23.74%  |
| SK hynix            | 30        | 21.58%  |
| Corsair             | 16        | 11.51%  |
| Micron Technology   | 12        | 8.63%   |
| Kingston            | 8         | 5.76%   |
| G.Skill             | 6         | 4.32%   |
| Crucial             | 6         | 4.32%   |
| Unknown             | 4         | 2.88%   |
| Team                | 4         | 2.88%   |
| Smart               | 3         | 2.16%   |
| Unknown             | 3         | 2.16%   |
| Neo Forza           | 2         | 1.44%   |
| Avant               | 2         | 1.44%   |
| A-DATA Technology   | 2         | 1.44%   |
| Unknown (8A02)      | 1         | 0.72%   |
| Timetec             | 1         | 0.72%   |
| Teikon              | 1         | 0.72%   |
| PNY                 | 1         | 0.72%   |
| Patriot Memory      | 1         | 0.72%   |
| GSkill              | 1         | 0.72%   |
| Goldkey             | 1         | 0.72%   |
| Gold Key            | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.1%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 2.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 2.1%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 2.1%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 3         | 2.1%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 2.1%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 2.1%    |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s         | 3         | 2.1%    |
| Unknown                                                          | 3         | 2.1%    |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s              | 2         | 1.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 1.4%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.4%    |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 2         | 1.4%    |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.4%    |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s             | 2         | 1.4%    |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.7%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.7%    |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s             | 1         | 0.7%    |
| Unknown RAM Module 16GB DIMM DDR4 3600MT/s                       | 1         | 0.7%    |
| Unknown (8A02) RAM 8G2400MHz 8GB SODIMM DDR4 2667MT/s            | 1         | 0.7%    |
| Timetec RAM 32NUS2R8-32G 32GB SODIMM DDR4 3200MT/s               | 1         | 0.7%    |
| Teikon RAM TMT251S6CFR8C-PBHC 4GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s               | 1         | 0.7%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s               | 1         | 0.7%    |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 0.7%    |
| Smart RAM SG564568FG8NWKFSQR 2GB SODIMM DDR2 800MT/s             | 1         | 0.7%    |
| Smart RAM SF4641G8CKHIWDFSEG 8GB SODIMM DDR4 2133MT/s            | 1         | 0.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.7%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.7%    |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.7%    |
| SK hynix RAM HMT351U6CFR8C-PBA 4GB DIMM DDR3 1600MT/s            | 1         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s  | 1         | 0.7%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.7%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.7%    |
| SK hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.7%    |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 0.7%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.7%    |
| SK hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 0.7%    |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.7%    |
| Samsung RAM Module 4GB SODIMM LPDDR3 2133MT/s                    | 1         | 0.7%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 0.7%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 0.7%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.7%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 0.7%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 0.7%    |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 1         | 0.7%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.7%    |
| Samsung RAM M471A1K43BB1-CTD 8GB Row Of Chips DDR4 2667MT/s      | 1         | 0.7%    |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s         | 1         | 0.7%    |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s            | 1         | 0.7%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 1         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 90        | 72.58%  |
| DDR3    | 16        | 12.9%   |
| LPDDR4  | 8         | 6.45%   |
| LPDDR3  | 6         | 4.84%   |
| DDR2    | 2         | 1.61%   |
| SDRAM   | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 74        | 59.2%   |
| DIMM         | 32        | 25.6%   |
| Row Of Chips | 19        | 15.2%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 70        | 53.85%  |
| 16384 | 25        | 19.23%  |
| 4096  | 22        | 16.92%  |
| 32768 | 9         | 6.92%   |
| 2048  | 4         | 3.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 39        | 30%     |
| 2667  | 28        | 21.54%  |
| 1600  | 14        | 10.77%  |
| 2133  | 10        | 7.69%   |
| 3600  | 9         | 6.92%   |
| 4267  | 6         | 4.62%   |
| 2400  | 4         | 3.08%   |
| 3466  | 3         | 2.31%   |
| 1333  | 3         | 2.31%   |
| 3266  | 2         | 1.54%   |
| 3000  | 2         | 1.54%   |
| 800   | 2         | 1.54%   |
| 4800  | 1         | 0.77%   |
| 4266  | 1         | 0.77%   |
| 3733  | 1         | 0.77%   |
| 3100  | 1         | 0.77%   |
| 3067  | 1         | 0.77%   |
| 2800  | 1         | 0.77%   |
| 2666  | 1         | 0.77%   |
| 2048  | 1         | 0.77%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 28.57%  |
| Samsung Electronics | 3         | 21.43%  |
| Brother Industries  | 3         | 21.43%  |
| Seiko Epson         | 1         | 7.14%   |
| QinHeng Electronics | 1         | 7.14%   |
| Dymo-CoStar         | 1         | 7.14%   |
| Canon               | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson WF-4830 Series             | 1         | 6.67%   |
| Samsung SCX-3400 Series                | 1         | 6.67%   |
| Samsung ML-191x/ML-252x Laser Printer  | 1         | 6.67%   |
| Samsung M2070 Series                   | 1         | 6.67%   |
| QinHeng CH340S                         | 1         | 6.67%   |
| HP PSC-1315/PSC-1317                   | 1         | 6.67%   |
| HP LaserJet P2035                      | 1         | 6.67%   |
| HP Ink Tank Wireless 410 series        | 1         | 6.67%   |
| HP ENVY Pro 6400 series                | 1         | 6.67%   |
| Dymo-CoStar DYMO LabelWriter 4XL       | 1         | 6.67%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 6.67%   |
| Canon Pro9000II series                 | 1         | 6.67%   |
| Brother MFC-L2700DW                    | 1         | 6.67%   |
| Brother MFC-5440CN                     | 1         | 6.67%   |
| Brother HL-2130 series                 | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LiDE 60 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 66        | 19.13%  |
| Microdia                               | 37        | 10.72%  |
| Acer                                   | 35        | 10.14%  |
| Realtek Semiconductor                  | 33        | 9.57%   |
| IMC Networks                           | 26        | 7.54%   |
| Sunplus Innovation Technology          | 22        | 6.38%   |
| Logitech                               | 21        | 6.09%   |
| Apple                                  | 19        | 5.51%   |
| Quanta                                 | 16        | 4.64%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 2.61%   |
| Syntek                                 | 6         | 1.74%   |
| Suyin                                  | 5         | 1.45%   |
| Silicon Motion                         | 5         | 1.45%   |
| Samsung Electronics                    | 4         | 1.16%   |
| Microsoft                              | 4         | 1.16%   |
| Lite-On Technology                     | 4         | 1.16%   |
| SunplusIT                              | 3         | 0.87%   |
| Luxvisions Innotech Limited            | 3         | 0.87%   |
| Generalplus Technology                 | 3         | 0.87%   |
| Alcor Micro                            | 3         | 0.87%   |
| Sunplus IT                             | 2         | 0.58%   |
| Razer USA                              | 2         | 0.58%   |
| ARC International                      | 2         | 0.58%   |
| Z-Star Microelectronics                | 1         | 0.29%   |
| XHT-210518                             | 1         | 0.29%   |
| WaveRider Communications               | 1         | 0.29%   |
| Valve Software                         | 1         | 0.29%   |
| Unknown                                | 1         | 0.29%   |
| Sonix Technology                       | 1         | 0.29%   |
| Primax Electronics                     | 1         | 0.29%   |
| MacroSilicon                           | 1         | 0.29%   |
| LG Electronics                         | 1         | 0.29%   |
| Jieli Technology                       | 1         | 0.29%   |
| icSpring                               | 1         | 0.29%   |
| Hewlett-Packard                        | 1         | 0.29%   |
| HD WEBCAM                              | 1         | 0.29%   |
| GenesysLogic Technology                | 1         | 0.29%   |
| Creative Technology                    | 1         | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 19        | 5.44%   |
| Microdia Integrated_Webcam_HD                       | 14        | 4.01%   |
| Chicony Integrated Camera                           | 12        | 3.44%   |
| Chicony HD Webcam                                   | 10        | 2.87%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 8         | 2.29%   |
| Acer Integrated Camera                              | 8         | 2.29%   |
| Acer BisonCam,NB Pro                                | 8         | 2.29%   |
| Apple Built-in iSight                               | 7         | 2.01%   |
| Syntek Integrated Camera                            | 6         | 1.72%   |
| Microdia Integrated Webcam                          | 6         | 1.72%   |
| IMC Networks Integrated Camera                      | 6         | 1.72%   |
| Apple iPhone 5/5C/5S/6/SE                           | 6         | 1.72%   |
| Logitech Webcam C270                                | 5         | 1.43%   |
| Logitech HD Pro Webcam C920                         | 5         | 1.43%   |
| Apple FaceTime HD Camera (Built-in)                 | 5         | 1.43%   |
| Acer HD Webcam                                      | 5         | 1.43%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 1.15%   |
| Samsung Galaxy series, misc. (MTP mode)             | 4         | 1.15%   |
| Quanta HP HD Camera                                 | 4         | 1.15%   |
| Quanta HD User Facing                               | 4         | 1.15%   |
| Microdia Integrated Webcam HD                       | 4         | 1.15%   |
| Chicony TOSHIBA Web Camera - HD                     | 4         | 1.15%   |
| Logitech C922 Pro Stream Webcam                     | 3         | 0.86%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 3         | 0.86%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 0.86%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 3         | 0.86%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                  | 2         | 0.57%   |
| Sunplus SPCA2281 Web Camera                         | 2         | 0.57%   |
| Sunplus Laptop Integrated Webcam FHD                | 2         | 0.57%   |
| Sunplus HD WebCam                                   | 2         | 0.57%   |
| Sunplus Full HD webcam                              | 2         | 0.57%   |
| Sunplus 1.3M HD WebCam                              | 2         | 0.57%   |
| Silicon Motion Web Camera                           | 2         | 0.57%   |
| Realtek USB2.0 HD UVC WebCam                        | 2         | 0.57%   |
| Realtek Integrated Webcam HD                        | 2         | 0.57%   |
| Realtek Integrated Webcam                           | 2         | 0.57%   |
| Razer USA Gaming Webcam [Kiyo]                      | 2         | 0.57%   |
| Quanta HP Wide Vision HD Camera                     | 2         | 0.57%   |
| Lite-On Integrated Camera                           | 2         | 0.57%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 0.57%   |
| Generalplus 2K HD Camera                            | 2         | 0.57%   |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 0.57%   |
| Chicony USB 2.0 Camera                              | 2         | 0.57%   |
| Chicony Integrated 5M Camera                        | 2         | 0.57%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 0.57%   |
| Chicony HP Wide Vision HD                           | 2         | 0.57%   |
| Chicony HP TrueVision HD Camera                     | 2         | 0.57%   |
| Chicony HP HD Webcam                                | 2         | 0.57%   |
| Chicony HP HD Camera                                | 2         | 0.57%   |
| Chicony HD User Facing                              | 2         | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 2         | 0.57%   |
| ARC International Camera                            | 2         | 0.57%   |
| Apple FaceTime HD Camera                            | 2         | 0.57%   |
| Acer SunplusIT Integrated Camera                    | 2         | 0.57%   |
| Acer Lenovo EasyCamera                              | 2         | 0.57%   |
| Acer EasyCamera                                     | 2         | 0.57%   |
| Z-Star Sirius USB2.0 Camera                         | 1         | 0.29%   |
| XHT-210518 EC500X                                   | 1         | 0.29%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 22        | 40%     |
| Shenzhen Goodix Technology | 12        | 21.82%  |
| Validity Sensors           | 10        | 18.18%  |
| Elan Microelectronics      | 3         | 5.45%   |
| Upek                       | 2         | 3.64%   |
| LighTuning Technology      | 2         | 3.64%   |
| AuthenTec                  | 2         | 3.64%   |
| Samsung Electronics        | 1         | 1.82%   |
| HOLTEK                     | 1         | 1.82%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown                                                   | 8         | 14.55%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 7         | 12.73%  |
| Shenzhen Goodix Fingerprint Reader                        | 5         | 9.09%   |
| Shenzhen Goodix FingerPrint                               | 4         | 7.27%   |
| Shenzhen Goodix  FingerPrint Device                       | 3         | 5.45%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 3.64%   |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 3.64%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 2         | 3.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 2         | 3.64%   |
| Synaptics WBDI Device                                     | 2         | 3.64%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 3.64%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 3.64%   |
| Elan ELAN:ARM-M4                                          | 2         | 3.64%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 1.82%   |
| Validity Sensors VFS491                                   | 1         | 1.82%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 1.82%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 1.82%   |
| Synaptics  WBDI                                           | 1         | 1.82%   |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 1.82%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 1.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 1         | 1.82%   |
| HOLTEK FocalTech Fingerprint Device                       | 1         | 1.82%   |
| Elan ELAN:Fingerprint                                     | 1         | 1.82%   |
| AuthenTec AES2810                                         | 1         | 1.82%   |
| AuthenTec AES2550 Fingerprint Sensor                      | 1         | 1.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 14        | 58.33%  |
| Alcor Micro      | 5         | 20.83%  |
| O2 Micro         | 2         | 8.33%   |
| Upek             | 1         | 4.17%   |
| SCM Microsystems | 1         | 4.17%   |
| Lenovo           | 1         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 7         | 29.17%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 20.83%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 20.83%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 8.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.17%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 4.17%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 362       | 67.16%  |
| 1     | 145       | 26.9%   |
| 2     | 25        | 4.64%   |
| 3     | 6         | 1.11%   |
| 4     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 52        | 24.76%  |
| Net/wireless             | 35        | 16.67%  |
| Multimedia controller    | 33        | 15.71%  |
| Bluetooth                | 29        | 13.81%  |
| Chipcard                 | 23        | 10.95%  |
| Graphics card            | 18        | 8.57%   |
| Communication controller | 4         | 1.9%    |
| Unassigned class         | 3         | 1.43%   |
| Storage/ide              | 3         | 1.43%   |
| Sound                    | 2         | 0.95%   |
| Network                  | 2         | 0.95%   |
| Net/ethernet             | 2         | 0.95%   |
| Modem                    | 2         | 0.95%   |
| Storage                  | 1         | 0.48%   |
| Card reader              | 1         | 0.48%   |

