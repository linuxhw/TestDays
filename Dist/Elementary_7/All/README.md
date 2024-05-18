Elementary 7 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Elementary 7.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_7/Desktop/README.md) and [notebooks](/Dist/Elementary_7/Notebook/README.md).

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

Total: 364

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Medion        | E6217                       | Notebook    | [c2ca377a05](https://linux-hardware.org/?probe=c2ca377a05) | Mar 31, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [1b291de7ca](https://linux-hardware.org/?probe=1b291de7ca) | Dec 10, 2023 |
| Jetway        | TI61M5                      | Desktop     | [dff0fcc796](https://linux-hardware.org/?probe=dff0fcc796) | Nov 25, 2023 |
| Jetway        | TI61M5                      | Desktop     | [968d83ba14](https://linux-hardware.org/?probe=968d83ba14) | Nov 21, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [684c7d7bf7](https://linux-hardware.org/?probe=684c7d7bf7) | Nov 03, 2023 |
| Dell          | Latitude E6400              | Notebook    | [6a3537c763](https://linux-hardware.org/?probe=6a3537c763) | Oct 23, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [b756b81d33](https://linux-hardware.org/?probe=b756b81d33) | Oct 12, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [3513d5bcf3](https://linux-hardware.org/?probe=3513d5bcf3) | Sep 28, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [945e2bc260](https://linux-hardware.org/?probe=945e2bc260) | Sep 24, 2023 |
| Dell          | Latitude E7270              | Notebook    | [874b8a2ad5](https://linux-hardware.org/?probe=874b8a2ad5) | Sep 23, 2023 |
| HP            | Laptop 17-by4xxx            | Notebook    | [dd1d978c67](https://linux-hardware.org/?probe=dd1d978c67) | Sep 22, 2023 |
| HP            | 2ADC                        | Desktop     | [b4794f247b](https://linux-hardware.org/?probe=b4794f247b) | Sep 21, 2023 |
| HP            | 2ADC                        | Desktop     | [7e9eb06b31](https://linux-hardware.org/?probe=7e9eb06b31) | Sep 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [603ddfc4cf](https://linux-hardware.org/?probe=603ddfc4cf) | Sep 18, 2023 |
| ASUSTek       | VM42                        | Desktop     | [ca9a3b42d0](https://linux-hardware.org/?probe=ca9a3b42d0) | Sep 17, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [3941e3e259](https://linux-hardware.org/?probe=3941e3e259) | Sep 16, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [f76358580b](https://linux-hardware.org/?probe=f76358580b) | Sep 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [5a47ad5c25](https://linux-hardware.org/?probe=5a47ad5c25) | Sep 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [876175ae24](https://linux-hardware.org/?probe=876175ae24) | Sep 15, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1ea319e72e](https://linux-hardware.org/?probe=1ea319e72e) | Sep 15, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [8db6f2c947](https://linux-hardware.org/?probe=8db6f2c947) | Sep 14, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [b4c93a8e2e](https://linux-hardware.org/?probe=b4c93a8e2e) | Sep 12, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [0a25a3d2af](https://linux-hardware.org/?probe=0a25a3d2af) | Sep 12, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ef1d9bfdab](https://linux-hardware.org/?probe=ef1d9bfdab) | Sep 08, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [d3996a81e2](https://linux-hardware.org/?probe=d3996a81e2) | Sep 07, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [2ce7b78a76](https://linux-hardware.org/?probe=2ce7b78a76) | Sep 06, 2023 |
| Dell          | Latitude E5570              | Notebook    | [10d8ad7a3d](https://linux-hardware.org/?probe=10d8ad7a3d) | Sep 05, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [7a27c6dd8d](https://linux-hardware.org/?probe=7a27c6dd8d) | Sep 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [783d0f51f5](https://linux-hardware.org/?probe=783d0f51f5) | Aug 31, 2023 |
| Medion        | E15301                      | Notebook    | [7f6c4eb814](https://linux-hardware.org/?probe=7f6c4eb814) | Aug 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [24ad5e2b06](https://linux-hardware.org/?probe=24ad5e2b06) | Aug 31, 2023 |
| HP            | 350 G1                      | Notebook    | [1e317e5a51](https://linux-hardware.org/?probe=1e317e5a51) | Aug 30, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [9374424bbd](https://linux-hardware.org/?probe=9374424bbd) | Aug 30, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2a2adfdc2e](https://linux-hardware.org/?probe=2a2adfdc2e) | Aug 30, 2023 |
| Digma         | EVE 11 C421Y ES1067EW       | Notebook    | [22e88dc9a5](https://linux-hardware.org/?probe=22e88dc9a5) | Aug 29, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [7c208705e5](https://linux-hardware.org/?probe=7c208705e5) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [8741a9bb96](https://linux-hardware.org/?probe=8741a9bb96) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [7efcdba9ef](https://linux-hardware.org/?probe=7efcdba9ef) | Aug 29, 2023 |
| HP            | 350 G1                      | Notebook    | [d800790bce](https://linux-hardware.org/?probe=d800790bce) | Aug 28, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [627068909d](https://linux-hardware.org/?probe=627068909d) | Aug 25, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [ac61c512ef](https://linux-hardware.org/?probe=ac61c512ef) | Aug 25, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [5c956051fb](https://linux-hardware.org/?probe=5c956051fb) | Aug 24, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [744be89da4](https://linux-hardware.org/?probe=744be89da4) | Aug 24, 2023 |
| Google        | Eldrid                      | Notebook    | [e451d840cf](https://linux-hardware.org/?probe=e451d840cf) | Aug 24, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [190a0f1eee](https://linux-hardware.org/?probe=190a0f1eee) | Aug 23, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [0112053569](https://linux-hardware.org/?probe=0112053569) | Aug 23, 2023 |
| HP            | 18E7                        | Desktop     | [0bd07157fb](https://linux-hardware.org/?probe=0bd07157fb) | Aug 20, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [01a44fbb3b](https://linux-hardware.org/?probe=01a44fbb3b) | Aug 20, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [551dc38c00](https://linux-hardware.org/?probe=551dc38c00) | Aug 19, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [0bbf9ab6c2](https://linux-hardware.org/?probe=0bbf9ab6c2) | Aug 19, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [054a5a44ad](https://linux-hardware.org/?probe=054a5a44ad) | Aug 18, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [d05585906d](https://linux-hardware.org/?probe=d05585906d) | Aug 18, 2023 |
| Gateway       | ZX4931                      | All in one  | [953740388e](https://linux-hardware.org/?probe=953740388e) | Aug 17, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [8298417da7](https://linux-hardware.org/?probe=8298417da7) | Aug 16, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [fafbb2dbc0](https://linux-hardware.org/?probe=fafbb2dbc0) | Aug 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [ce1ba9dce0](https://linux-hardware.org/?probe=ce1ba9dce0) | Aug 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [dc696b572c](https://linux-hardware.org/?probe=dc696b572c) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [5d7e68e3ae](https://linux-hardware.org/?probe=5d7e68e3ae) | Aug 14, 2023 |
| Acer          | Swift SF515-51T             | Notebook    | [9271029425](https://linux-hardware.org/?probe=9271029425) | Aug 13, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [7c62a05800](https://linux-hardware.org/?probe=7c62a05800) | Aug 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [5d3d27c8bb](https://linux-hardware.org/?probe=5d3d27c8bb) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [80f2f711d8](https://linux-hardware.org/?probe=80f2f711d8) | Aug 10, 2023 |
| HP            | ProBook 4310s               | Notebook    | [ac0c1be078](https://linux-hardware.org/?probe=ac0c1be078) | Aug 09, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [04a319c904](https://linux-hardware.org/?probe=04a319c904) | Aug 09, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6165a2d50e](https://linux-hardware.org/?probe=6165a2d50e) | Aug 08, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [663f9e62db](https://linux-hardware.org/?probe=663f9e62db) | Aug 08, 2023 |
| Acer          | Aspire TC-710 V:1.1         | Desktop     | [f6af1382fd](https://linux-hardware.org/?probe=f6af1382fd) | Aug 08, 2023 |
| HP            | G60                         | Notebook    | [7f3b9aec85](https://linux-hardware.org/?probe=7f3b9aec85) | Aug 07, 2023 |
| Lenovo        | ThinkPad X201 Tablet 298... | Notebook    | [7132bbeb85](https://linux-hardware.org/?probe=7132bbeb85) | Aug 06, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [09ae57bb9a](https://linux-hardware.org/?probe=09ae57bb9a) | Aug 05, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [21460cac53](https://linux-hardware.org/?probe=21460cac53) | Aug 05, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [9d5490fb82](https://linux-hardware.org/?probe=9d5490fb82) | Aug 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2b8f90f79d](https://linux-hardware.org/?probe=2b8f90f79d) | Aug 03, 2023 |
| Acer          | Predator G3-571             | Notebook    | [fc950e8651](https://linux-hardware.org/?probe=fc950e8651) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | Notebook    | [73e1dd94b2](https://linux-hardware.org/?probe=73e1dd94b2) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2f4ed3cb1f](https://linux-hardware.org/?probe=2f4ed3cb1f) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | Notebook    | [a13fd4044e](https://linux-hardware.org/?probe=a13fd4044e) | Aug 01, 2023 |
| SHENZHEN Y... | A8S PRO                     | Notebook    | [829a4178a5](https://linux-hardware.org/?probe=829a4178a5) | Jul 30, 2023 |
| Acer          | Spin SP314-53GN             | Convertible | [92acef890a](https://linux-hardware.org/?probe=92acef890a) | Jul 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c7572ce663](https://linux-hardware.org/?probe=c7572ce663) | Jul 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8ac9af1db8](https://linux-hardware.org/?probe=8ac9af1db8) | Jul 29, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [36dda4bbfa](https://linux-hardware.org/?probe=36dda4bbfa) | Jul 28, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [10fa87c167](https://linux-hardware.org/?probe=10fa87c167) | Jul 28, 2023 |
| SHENZHEN Y... | A8S PRO                     | Notebook    | [08a6feda0e](https://linux-hardware.org/?probe=08a6feda0e) | Jul 28, 2023 |
| ASRock        | X570 Extreme4               | Desktop     | [5b1a74fc68](https://linux-hardware.org/?probe=5b1a74fc68) | Jul 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c2e02d1490](https://linux-hardware.org/?probe=c2e02d1490) | Jul 24, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [20ec4f50dc](https://linux-hardware.org/?probe=20ec4f50dc) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a5359c62e0](https://linux-hardware.org/?probe=a5359c62e0) | Jul 20, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [6c258335bb](https://linux-hardware.org/?probe=6c258335bb) | Jul 20, 2023 |
| Alienware     | m15 R6                      | Notebook    | [93d5e98358](https://linux-hardware.org/?probe=93d5e98358) | Jul 20, 2023 |
| HP            | Notebook                    | Notebook    | [2ccf016245](https://linux-hardware.org/?probe=2ccf016245) | Jul 19, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [a7dc2996b6](https://linux-hardware.org/?probe=a7dc2996b6) | Jul 18, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [7dd13cea49](https://linux-hardware.org/?probe=7dd13cea49) | Jul 17, 2023 |
| Google        | Phaser360                   | Notebook    | [1e66458514](https://linux-hardware.org/?probe=1e66458514) | Jul 17, 2023 |
| HP            | ENVY 15                     | Notebook    | [a173db4ea1](https://linux-hardware.org/?probe=a173db4ea1) | Jul 17, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | Notebook    | [2c05f1a964](https://linux-hardware.org/?probe=2c05f1a964) | Jul 16, 2023 |
| Acer          | Aspire TC-380               | Desktop     | [94f5f10ff2](https://linux-hardware.org/?probe=94f5f10ff2) | Jul 14, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [f0736c39fe](https://linux-hardware.org/?probe=f0736c39fe) | Jul 13, 2023 |
| Wortmann      | TERRA_PC                    | Desktop     | [60ece53188](https://linux-hardware.org/?probe=60ece53188) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [74420b09b7](https://linux-hardware.org/?probe=74420b09b7) | Jul 12, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [3532802c06](https://linux-hardware.org/?probe=3532802c06) | Jul 12, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [4e8926a95b](https://linux-hardware.org/?probe=4e8926a95b) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1a0add8887](https://linux-hardware.org/?probe=1a0add8887) | Jul 11, 2023 |
| HP            | ENVY 15                     | Notebook    | [3ccdaf4d4e](https://linux-hardware.org/?probe=3ccdaf4d4e) | Jul 10, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [784f886357](https://linux-hardware.org/?probe=784f886357) | Jul 10, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [881754a433](https://linux-hardware.org/?probe=881754a433) | Jul 09, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [8877b51b89](https://linux-hardware.org/?probe=8877b51b89) | Jul 08, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [bb065938a5](https://linux-hardware.org/?probe=bb065938a5) | Jul 07, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ee299280f8](https://linux-hardware.org/?probe=ee299280f8) | Jul 07, 2023 |
| Dell          | Latitude E7270              | Notebook    | [406e4a918b](https://linux-hardware.org/?probe=406e4a918b) | Jul 06, 2023 |
| Intel Clie... | LAPBC710                    | Notebook    | [fd97a27365](https://linux-hardware.org/?probe=fd97a27365) | Jul 06, 2023 |
| Alienware     | 07HV66 A00                  | Desktop     | [41d4d9ae84](https://linux-hardware.org/?probe=41d4d9ae84) | Jul 05, 2023 |
| Alienware     | 07HV66 A00                  | Desktop     | [2712110727](https://linux-hardware.org/?probe=2712110727) | Jul 05, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [9c0f0d40b9](https://linux-hardware.org/?probe=9c0f0d40b9) | Jul 05, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2e4a653435](https://linux-hardware.org/?probe=2e4a653435) | Jul 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f7a7db0702](https://linux-hardware.org/?probe=f7a7db0702) | Jul 04, 2023 |
| GPD           | MicroPC                     | Notebook    | [f666f4c574](https://linux-hardware.org/?probe=f666f4c574) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 23254W5       | Notebook    | [5842896b76](https://linux-hardware.org/?probe=5842896b76) | Jul 03, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [6e52890194](https://linux-hardware.org/?probe=6e52890194) | Jul 02, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [8bfe14749f](https://linux-hardware.org/?probe=8bfe14749f) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430 2349OB6       | Notebook    | [f2f66bb9d0](https://linux-hardware.org/?probe=f2f66bb9d0) | Jun 29, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [d73388baab](https://linux-hardware.org/?probe=d73388baab) | Jun 28, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [afc9f56d8d](https://linux-hardware.org/?probe=afc9f56d8d) | Jun 28, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e10153b4c9](https://linux-hardware.org/?probe=e10153b4c9) | Jun 23, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [38ae545c1c](https://linux-hardware.org/?probe=38ae545c1c) | Jun 23, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [a75e6d35da](https://linux-hardware.org/?probe=a75e6d35da) | Jun 21, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [4f5e2f9201](https://linux-hardware.org/?probe=4f5e2f9201) | Jun 21, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [293b8783a3](https://linux-hardware.org/?probe=293b8783a3) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [2f452cfce0](https://linux-hardware.org/?probe=2f452cfce0) | Jun 20, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [f49534dfa4](https://linux-hardware.org/?probe=f49534dfa4) | Jun 19, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [a57885e16c](https://linux-hardware.org/?probe=a57885e16c) | Jun 18, 2023 |
| Pegatron      | IPMIP-GS                    | Desktop     | [fb51893272](https://linux-hardware.org/?probe=fb51893272) | Jun 15, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [782fa74afe](https://linux-hardware.org/?probe=782fa74afe) | Jun 14, 2023 |
| Razer         | Blade Stealth               | Notebook    | [f218e04a1c](https://linux-hardware.org/?probe=f218e04a1c) | Jun 14, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d675395634](https://linux-hardware.org/?probe=d675395634) | Jun 11, 2023 |
| ECS           | G41T-M                      | Desktop     | [2c148573fc](https://linux-hardware.org/?probe=2c148573fc) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [08114e8a97](https://linux-hardware.org/?probe=08114e8a97) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [93555cfd25](https://linux-hardware.org/?probe=93555cfd25) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2e6d82c14f](https://linux-hardware.org/?probe=2e6d82c14f) | Jun 10, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [604f40e700](https://linux-hardware.org/?probe=604f40e700) | Jun 09, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d001c4cf1c](https://linux-hardware.org/?probe=d001c4cf1c) | Jun 09, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d487214e2a](https://linux-hardware.org/?probe=d487214e2a) | Jun 08, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [ddefeff960](https://linux-hardware.org/?probe=ddefeff960) | Jun 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [6c62565787](https://linux-hardware.org/?probe=6c62565787) | Jun 07, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [b2281ad2cb](https://linux-hardware.org/?probe=b2281ad2cb) | Jun 06, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [77fe6db865](https://linux-hardware.org/?probe=77fe6db865) | Jun 06, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [1ebf23281e](https://linux-hardware.org/?probe=1ebf23281e) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [274b78cda3](https://linux-hardware.org/?probe=274b78cda3) | Jun 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [119fd5249f](https://linux-hardware.org/?probe=119fd5249f) | Jun 03, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [532dea434a](https://linux-hardware.org/?probe=532dea434a) | Jun 02, 2023 |
| HP            | G62                         | Notebook    | [f2600c2f4b](https://linux-hardware.org/?probe=f2600c2f4b) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [71208c2344](https://linux-hardware.org/?probe=71208c2344) | Jun 01, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [827e0203ac](https://linux-hardware.org/?probe=827e0203ac) | May 31, 2023 |
| Gigabyte      | GA-E6010N                   | Desktop     | [563074319d](https://linux-hardware.org/?probe=563074319d) | May 31, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [01076d8e8b](https://linux-hardware.org/?probe=01076d8e8b) | May 30, 2023 |
| ASUSTek       | X550WA                      | Notebook    | [864236b0c9](https://linux-hardware.org/?probe=864236b0c9) | May 29, 2023 |
| PCBOX         | Kant                        | Notebook    | [1e2f772d05](https://linux-hardware.org/?probe=1e2f772d05) | May 29, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [16b9dfbbe0](https://linux-hardware.org/?probe=16b9dfbbe0) | May 29, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [35d14ed328](https://linux-hardware.org/?probe=35d14ed328) | May 29, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [36a3563566](https://linux-hardware.org/?probe=36a3563566) | May 29, 2023 |
| Chuwi         | UBook Pro                   | Tablet      | [190fe84e14](https://linux-hardware.org/?probe=190fe84e14) | May 27, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e29fb14e81](https://linux-hardware.org/?probe=e29fb14e81) | May 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [84d0d9807f](https://linux-hardware.org/?probe=84d0d9807f) | May 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [124c8183a8](https://linux-hardware.org/?probe=124c8183a8) | May 26, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [1ddb5fe9a0](https://linux-hardware.org/?probe=1ddb5fe9a0) | May 26, 2023 |
| Dell          | Precision 5530              | Notebook    | [702b4d7914](https://linux-hardware.org/?probe=702b4d7914) | May 26, 2023 |
| Dell          | Latitude E5470              | Notebook    | [6054d2ee2b](https://linux-hardware.org/?probe=6054d2ee2b) | May 25, 2023 |
| Unknown       | Unknown                     | Tablet      | [8a83b799d5](https://linux-hardware.org/?probe=8a83b799d5) | May 24, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [4ddad1d733](https://linux-hardware.org/?probe=4ddad1d733) | May 24, 2023 |
| HP            | ProBook 4310s               | Notebook    | [1a32d434c0](https://linux-hardware.org/?probe=1a32d434c0) | May 21, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [61ebf173dc](https://linux-hardware.org/?probe=61ebf173dc) | May 21, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [7f15c1b9e3](https://linux-hardware.org/?probe=7f15c1b9e3) | May 21, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [ff730fcbf6](https://linux-hardware.org/?probe=ff730fcbf6) | May 20, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [73d62695e4](https://linux-hardware.org/?probe=73d62695e4) | May 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [56aa17165e](https://linux-hardware.org/?probe=56aa17165e) | May 18, 2023 |
| HP            | ProBook 4310s               | Notebook    | [dfcb51e697](https://linux-hardware.org/?probe=dfcb51e697) | May 17, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [004f548439](https://linux-hardware.org/?probe=004f548439) | May 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8fb1a89166](https://linux-hardware.org/?probe=8fb1a89166) | May 17, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [3776285fc1](https://linux-hardware.org/?probe=3776285fc1) | May 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [155b921e10](https://linux-hardware.org/?probe=155b921e10) | May 13, 2023 |
| HP            | 1998                        | Desktop     | [b806151d9f](https://linux-hardware.org/?probe=b806151d9f) | May 12, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [81e3161a34](https://linux-hardware.org/?probe=81e3161a34) | May 11, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [1060697095](https://linux-hardware.org/?probe=1060697095) | May 10, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [58000b3a57](https://linux-hardware.org/?probe=58000b3a57) | May 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1b0786ec5e](https://linux-hardware.org/?probe=1b0786ec5e) | May 07, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [ea0b55ed61](https://linux-hardware.org/?probe=ea0b55ed61) | May 07, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [df06b3c5b3](https://linux-hardware.org/?probe=df06b3c5b3) | May 07, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [bac71eb24d](https://linux-hardware.org/?probe=bac71eb24d) | May 06, 2023 |
| Lenovo        | ThinkPad P51s 20HB001TUS    | Notebook    | [eac4ebdef0](https://linux-hardware.org/?probe=eac4ebdef0) | May 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [834d2304aa](https://linux-hardware.org/?probe=834d2304aa) | May 06, 2023 |
| Intel         | JSL MRD                     | Desktop     | [76ff5c3bd7](https://linux-hardware.org/?probe=76ff5c3bd7) | May 05, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [6a80029392](https://linux-hardware.org/?probe=6a80029392) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [fe61386871](https://linux-hardware.org/?probe=fe61386871) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [764f38bb65](https://linux-hardware.org/?probe=764f38bb65) | May 05, 2023 |
| Dell          | 02N3WF A02                  | Desktop     | [3f10b3ca43](https://linux-hardware.org/?probe=3f10b3ca43) | May 04, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [c5927045a3](https://linux-hardware.org/?probe=c5927045a3) | May 04, 2023 |
| HP            | 1998                        | Desktop     | [6f816ac95a](https://linux-hardware.org/?probe=6f816ac95a) | Apr 29, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [97acececd3](https://linux-hardware.org/?probe=97acececd3) | Apr 28, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [c188ae4d7d](https://linux-hardware.org/?probe=c188ae4d7d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [2a9fcae8c3](https://linux-hardware.org/?probe=2a9fcae8c3) | Apr 28, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [87c8761eff](https://linux-hardware.org/?probe=87c8761eff) | Apr 27, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [b03cd2f2d2](https://linux-hardware.org/?probe=b03cd2f2d2) | Apr 26, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [53dd8334ac](https://linux-hardware.org/?probe=53dd8334ac) | Apr 26, 2023 |
| HP            | 8055                        | Desktop     | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5d8b07dbbd](https://linux-hardware.org/?probe=5d8b07dbbd) | Apr 25, 2023 |
| ASRock        | B660M-C                     | Desktop     | [849fc5d462](https://linux-hardware.org/?probe=849fc5d462) | Apr 25, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [8fd18554d1](https://linux-hardware.org/?probe=8fd18554d1) | Apr 24, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | Desktop     | [eebce73217](https://linux-hardware.org/?probe=eebce73217) | Apr 23, 2023 |
| Dell          | Latitude E4300              | Notebook    | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [763953fb60](https://linux-hardware.org/?probe=763953fb60) | Apr 22, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [50a18b5e94](https://linux-hardware.org/?probe=50a18b5e94) | Apr 19, 2023 |
| Foxconn       | A76GMV                      | Desktop     | [bafa62c759](https://linux-hardware.org/?probe=bafa62c759) | Apr 18, 2023 |
| Foxconn       | A76GMV                      | Desktop     | [f129cb2de1](https://linux-hardware.org/?probe=f129cb2de1) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4d60e2b7da](https://linux-hardware.org/?probe=4d60e2b7da) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [94bf014457](https://linux-hardware.org/?probe=94bf014457) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [2ebc6a2f61](https://linux-hardware.org/?probe=2ebc6a2f61) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ff6dbdcc10](https://linux-hardware.org/?probe=ff6dbdcc10) | Apr 15, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [845e7bfdd1](https://linux-hardware.org/?probe=845e7bfdd1) | Apr 15, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [936a7d1fe3](https://linux-hardware.org/?probe=936a7d1fe3) | Apr 15, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4c6427b3fc](https://linux-hardware.org/?probe=4c6427b3fc) | Apr 14, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e311d21def](https://linux-hardware.org/?probe=e311d21def) | Apr 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [8e05a5e529](https://linux-hardware.org/?probe=8e05a5e529) | Apr 13, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [0c03014734](https://linux-hardware.org/?probe=0c03014734) | Apr 12, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [c750ece414](https://linux-hardware.org/?probe=c750ece414) | Apr 12, 2023 |
| Dell          | Latitude E5570              | Notebook    | [81eaf54f19](https://linux-hardware.org/?probe=81eaf54f19) | Apr 07, 2023 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [5c12ed53b7](https://linux-hardware.org/?probe=5c12ed53b7) | Apr 05, 2023 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [6896e5d9e2](https://linux-hardware.org/?probe=6896e5d9e2) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [3f9238067d](https://linux-hardware.org/?probe=3f9238067d) | Apr 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1a3e968dff](https://linux-hardware.org/?probe=1a3e968dff) | Apr 03, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [d3bd81c4fd](https://linux-hardware.org/?probe=d3bd81c4fd) | Apr 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [f7f207f61c](https://linux-hardware.org/?probe=f7f207f61c) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [e06d57c27a](https://linux-hardware.org/?probe=e06d57c27a) | Apr 01, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d4c718bdab](https://linux-hardware.org/?probe=d4c718bdab) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [5a83c18a3e](https://linux-hardware.org/?probe=5a83c18a3e) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [94f75ee798](https://linux-hardware.org/?probe=94f75ee798) | Apr 01, 2023 |
| ASUSTek       | Zenbook UN5401QAB_UN5401... | Convertible | [448d1a491c](https://linux-hardware.org/?probe=448d1a491c) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| Dell          | Latitude E7440              | Notebook    | [1159c854cd](https://linux-hardware.org/?probe=1159c854cd) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a9a8004509](https://linux-hardware.org/?probe=a9a8004509) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [1dccfbe9f4](https://linux-hardware.org/?probe=1dccfbe9f4) | Mar 29, 2023 |
| Dell          | Latitude 5420               | Notebook    | [d714c46c4f](https://linux-hardware.org/?probe=d714c46c4f) | Mar 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [fb22157f03](https://linux-hardware.org/?probe=fb22157f03) | Mar 28, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [5590ec1365](https://linux-hardware.org/?probe=5590ec1365) | Mar 28, 2023 |
| AZW           | U59                         | Desktop     | [7674bb8dc9](https://linux-hardware.org/?probe=7674bb8dc9) | Mar 27, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [39995c1c00](https://linux-hardware.org/?probe=39995c1c00) | Mar 24, 2023 |
| Dell          | Latitude E7440              | Notebook    | [1a986dbeb8](https://linux-hardware.org/?probe=1a986dbeb8) | Mar 24, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [df318ed208](https://linux-hardware.org/?probe=df318ed208) | Mar 21, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [e40cf4f577](https://linux-hardware.org/?probe=e40cf4f577) | Mar 18, 2023 |
| Dell          | Latitude E5570              | Notebook    | [a15d1b43ca](https://linux-hardware.org/?probe=a15d1b43ca) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [dd07b0c3b3](https://linux-hardware.org/?probe=dd07b0c3b3) | Mar 17, 2023 |
| Dell          | G3 3590                     | Notebook    | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [1674c37cf9](https://linux-hardware.org/?probe=1674c37cf9) | Mar 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [03e5d43f27](https://linux-hardware.org/?probe=03e5d43f27) | Mar 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [4c49d73583](https://linux-hardware.org/?probe=4c49d73583) | Mar 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [c6ff6d14a0](https://linux-hardware.org/?probe=c6ff6d14a0) | Mar 15, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [28f8273eb5](https://linux-hardware.org/?probe=28f8273eb5) | Mar 15, 2023 |
| HP            | 805A                        | Desktop     | [5401e12606](https://linux-hardware.org/?probe=5401e12606) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [b3c4766473](https://linux-hardware.org/?probe=b3c4766473) | Mar 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | Notebook    | [a2ee9a2818](https://linux-hardware.org/?probe=a2ee9a2818) | Mar 12, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [023f42d6d1](https://linux-hardware.org/?probe=023f42d6d1) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK A359               | Notebook    | [0fa1ebbc11](https://linux-hardware.org/?probe=0fa1ebbc11) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK A359               | Notebook    | [f977012127](https://linux-hardware.org/?probe=f977012127) | Mar 11, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [fce6120754](https://linux-hardware.org/?probe=fce6120754) | Mar 11, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [32b2d1b194](https://linux-hardware.org/?probe=32b2d1b194) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [82b5297ab8](https://linux-hardware.org/?probe=82b5297ab8) | Mar 11, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [a4ba2ff90e](https://linux-hardware.org/?probe=a4ba2ff90e) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | Notebook    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Sony          | VPCEH2C5E                   | Notebook    | [adf4a69310](https://linux-hardware.org/?probe=adf4a69310) | Mar 07, 2023 |
| Sony          | VPCEH2C5E                   | Notebook    | [9e5b625dda](https://linux-hardware.org/?probe=9e5b625dda) | Mar 07, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [3547dd712b](https://linux-hardware.org/?probe=3547dd712b) | Mar 07, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [c45e770987](https://linux-hardware.org/?probe=c45e770987) | Mar 06, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [4ecfeecd31](https://linux-hardware.org/?probe=4ecfeecd31) | Mar 06, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [5afd8e3f42](https://linux-hardware.org/?probe=5afd8e3f42) | Mar 04, 2023 |
| Microsoft     | Surface Book                | Tablet      | [cc3ad3e0d2](https://linux-hardware.org/?probe=cc3ad3e0d2) | Mar 02, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [817b72f78f](https://linux-hardware.org/?probe=817b72f78f) | Mar 02, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [053c6d5368](https://linux-hardware.org/?probe=053c6d5368) | Mar 02, 2023 |
| Microsoft     | Surface Book                | Tablet      | [d58385d1e6](https://linux-hardware.org/?probe=d58385d1e6) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [fa757fb12a](https://linux-hardware.org/?probe=fa757fb12a) | Mar 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [1025a9748f](https://linux-hardware.org/?probe=1025a9748f) | Mar 01, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [dabd3e0232](https://linux-hardware.org/?probe=dabd3e0232) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [e189c60b09](https://linux-hardware.org/?probe=e189c60b09) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3883ba28c7](https://linux-hardware.org/?probe=3883ba28c7) | Mar 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [1c5f8fef49](https://linux-hardware.org/?probe=1c5f8fef49) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [216ad20179](https://linux-hardware.org/?probe=216ad20179) | Feb 28, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [573644760d](https://linux-hardware.org/?probe=573644760d) | Feb 28, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [371a95fb3d](https://linux-hardware.org/?probe=371a95fb3d) | Feb 28, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [e331c5e257](https://linux-hardware.org/?probe=e331c5e257) | Feb 27, 2023 |
| Acer          | Predator G3620              | Desktop     | [72f3382b60](https://linux-hardware.org/?probe=72f3382b60) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| Acer          | Aspire E5-771               | Notebook    | [73c974942f](https://linux-hardware.org/?probe=73c974942f) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a66f75c107](https://linux-hardware.org/?probe=a66f75c107) | Feb 26, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [ce9dda227f](https://linux-hardware.org/?probe=ce9dda227f) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [50a16e7924](https://linux-hardware.org/?probe=50a16e7924) | Feb 25, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [b815c24c07](https://linux-hardware.org/?probe=b815c24c07) | Feb 24, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [e578b951f9](https://linux-hardware.org/?probe=e578b951f9) | Feb 24, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [0dc5add67b](https://linux-hardware.org/?probe=0dc5add67b) | Feb 24, 2023 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [b101883e65](https://linux-hardware.org/?probe=b101883e65) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [6db3a90234](https://linux-hardware.org/?probe=6db3a90234) | Feb 24, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [0a3d750f36](https://linux-hardware.org/?probe=0a3d750f36) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ddd8c34644](https://linux-hardware.org/?probe=ddd8c34644) | Feb 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | Notebook    | [c79a8f48f9](https://linux-hardware.org/?probe=c79a8f48f9) | Feb 20, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [7ee9e59831](https://linux-hardware.org/?probe=7ee9e59831) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [13a132516b](https://linux-hardware.org/?probe=13a132516b) | Feb 18, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [2751aac3e0](https://linux-hardware.org/?probe=2751aac3e0) | Feb 16, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [76ab936a75](https://linux-hardware.org/?probe=76ab936a75) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [e0f89bbca1](https://linux-hardware.org/?probe=e0f89bbca1) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| HP            | 550                         | Notebook    | [81b67f211d](https://linux-hardware.org/?probe=81b67f211d) | Feb 15, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [150c1de326](https://linux-hardware.org/?probe=150c1de326) | Feb 15, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [e8a460c42c](https://linux-hardware.org/?probe=e8a460c42c) | Feb 15, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [a92df0196e](https://linux-hardware.org/?probe=a92df0196e) | Feb 15, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [92ab9b2e0d](https://linux-hardware.org/?probe=92ab9b2e0d) | Feb 14, 2023 |
| HP            | 805D                        | Desktop     | [217784712c](https://linux-hardware.org/?probe=217784712c) | Feb 14, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [f22c83d683](https://linux-hardware.org/?probe=f22c83d683) | Feb 14, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [12431d8083](https://linux-hardware.org/?probe=12431d8083) | Feb 14, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [f0899499e5](https://linux-hardware.org/?probe=f0899499e5) | Feb 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [537d29b0d5](https://linux-hardware.org/?probe=537d29b0d5) | Feb 12, 2023 |
| Acer          | Extensa 5230                | Notebook    | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | Notebook    | [a1d85b3098](https://linux-hardware.org/?probe=a1d85b3098) | Feb 10, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [76711a4e32](https://linux-hardware.org/?probe=76711a4e32) | Feb 10, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [9de542dff7](https://linux-hardware.org/?probe=9de542dff7) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | Notebook    | [6e8ed5d5d6](https://linux-hardware.org/?probe=6e8ed5d5d6) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [b906f960a0](https://linux-hardware.org/?probe=b906f960a0) | Feb 08, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [1e6a345b00](https://linux-hardware.org/?probe=1e6a345b00) | Feb 07, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [c3607bb4c2](https://linux-hardware.org/?probe=c3607bb4c2) | Feb 07, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [73b3c1c661](https://linux-hardware.org/?probe=73b3c1c661) | Feb 06, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [07ea9d3c2f](https://linux-hardware.org/?probe=07ea9d3c2f) | Feb 06, 2023 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [30e2a88930](https://linux-hardware.org/?probe=30e2a88930) | Feb 05, 2023 |
| Acer          | Aspire 8935G                | Notebook    | [10f8560601](https://linux-hardware.org/?probe=10f8560601) | Feb 05, 2023 |
| Acer          | Aspire 8935G                | Notebook    | [be37cc70f5](https://linux-hardware.org/?probe=be37cc70f5) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [8d67e1438d](https://linux-hardware.org/?probe=8d67e1438d) | Feb 05, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8bdb86b164](https://linux-hardware.org/?probe=8bdb86b164) | Feb 04, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [3786e7a211](https://linux-hardware.org/?probe=3786e7a211) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [9d397c2187](https://linux-hardware.org/?probe=9d397c2187) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [7b676dec23](https://linux-hardware.org/?probe=7b676dec23) | Feb 04, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [8aa57f1d6d](https://linux-hardware.org/?probe=8aa57f1d6d) | Feb 03, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [78919f6127](https://linux-hardware.org/?probe=78919f6127) | Feb 03, 2023 |
| Alienware     | x17 R2                      | Notebook    | [474a70c148](https://linux-hardware.org/?probe=474a70c148) | Feb 03, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [42c3899a37](https://linux-hardware.org/?probe=42c3899a37) | Feb 02, 2023 |
| Sony          | SVF1521O4E                  | Notebook    | [e2d47879d4](https://linux-hardware.org/?probe=e2d47879d4) | Feb 02, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [fdf7b5e80e](https://linux-hardware.org/?probe=fdf7b5e80e) | Feb 02, 2023 |
| Lenovo        | ThinkPad X230 23259S9       | Notebook    | [3d9e74535f](https://linux-hardware.org/?probe=3d9e74535f) | Feb 01, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [1ce7db78c1](https://linux-hardware.org/?probe=1ce7db78c1) | Feb 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c2a4529e33](https://linux-hardware.org/?probe=c2a4529e33) | Jan 30, 2023 |
| Star Labs     | StarBook                    | Notebook    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Unknown       | HX90                        | Desktop     | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [cc7b02033a](https://linux-hardware.org/?probe=cc7b02033a) | Dec 24, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-58-generic      | 69        | 26.04%  |
| 6.2.0-26-generic       | 23        | 8.68%   |
| 5.19.0-46-generic      | 23        | 8.68%   |
| 5.19.0-41-generic      | 23        | 8.68%   |
| 5.19.0-35-generic      | 22        | 8.3%    |
| 5.19.0-32-generic      | 22        | 8.3%    |
| 5.19.0-38-generic      | 17        | 6.42%   |
| 5.19.0-43-generic      | 13        | 4.91%   |
| 5.15.0-60-generic      | 9         | 3.4%    |
| 6.2.0-32-generic       | 8         | 3.02%   |
| 5.19.0-40-generic      | 6         | 2.26%   |
| 6.2.0-31-generic       | 5         | 1.89%   |
| 5.19.0-50-generic      | 5         | 1.89%   |
| 5.19.0-42-generic      | 5         | 1.89%   |
| 5.19.0-45-generic      | 3         | 1.13%   |
| 5.15.0-56-generic      | 2         | 0.75%   |
| 6.5.5-060505-generic   | 1         | 0.38%   |
| 6.4.5-x64v3-xanmod1    | 1         | 0.38%   |
| 6.2.8-3-liquorix-amd64 | 1         | 0.38%   |
| 6.2.7-060207-generic   | 1         | 0.38%   |
| 6.2.2-surface          | 1         | 0.38%   |
| 6.2.14-surface         | 1         | 0.38%   |
| 6.1.9-060109-generic   | 1         | 0.38%   |
| 6.1.6-060106-generic   | 1         | 0.38%   |
| 6.1.0-1013-oem         | 1         | 0.38%   |
| 5.15.0-79-generic      | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 132       | 51.16%  |
| 5.15.0  | 81        | 31.4%   |
| 6.2.0   | 36        | 13.95%  |
| 6.5.5   | 1         | 0.39%   |
| 6.4.5   | 1         | 0.39%   |
| 6.2.8   | 1         | 0.39%   |
| 6.2.7   | 1         | 0.39%   |
| 6.2.2   | 1         | 0.39%   |
| 6.2.14  | 1         | 0.39%   |
| 6.1.9   | 1         | 0.39%   |
| 6.1.6   | 1         | 0.39%   |
| 6.1.0   | 1         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19    | 132       | 51.36%  |
| 5.15    | 81        | 31.52%  |
| 6.2     | 39        | 15.18%  |
| 6.1     | 3         | 1.17%   |
| 6.5     | 1         | 0.39%   |
| 6.4     | 1         | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 252       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 252       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 252       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 204       | 80.95%  |
| LightDM | 48        | 19.05%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 112       | 44.27%  |
| de_DE | 39        | 15.42%  |
| ru_RU | 21        | 8.3%    |
| es_ES | 20        | 7.91%   |
| pl_PL | 7         | 2.77%   |
| fr_FR | 7         | 2.77%   |
| it_IT | 6         | 2.37%   |
| pt_BR | 5         | 1.98%   |
| en_GB | 5         | 1.98%   |
| sv_SE | 4         | 1.58%   |
| en_AU | 4         | 1.58%   |
| nl_NL | 3         | 1.19%   |
| en_CA | 3         | 1.19%   |
| tr_TR | 2         | 0.79%   |
| pt_PT | 2         | 0.79%   |
| nb_NO | 2         | 0.79%   |
| hu_HU | 2         | 0.79%   |
| el_GR | 2         | 0.79%   |
| uk_UA | 1         | 0.4%    |
| sk_SK | 1         | 0.4%    |
| ja_JP | 1         | 0.4%    |
| fi_FI | 1         | 0.4%    |
| da_DK | 1         | 0.4%    |
| cs_CZ | 1         | 0.4%    |
| bg_BG | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 219       | 86.9%   |
| EFI  | 33        | 13.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 237       | 93.68%  |
| Tmpfs   | 9         | 3.56%   |
| Btrfs   | 3         | 1.19%   |
| Xfs     | 2         | 0.79%   |
| Overlay | 2         | 0.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 204       | 80.95%  |
| GPT     | 40        | 15.87%  |
| MBR     | 8         | 3.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 249       | 98.81%  |
| Yes       | 3         | 1.19%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 235       | 93.25%  |
| Yes       | 17        | 6.75%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Apple                       | 44        | 17.46%  |
| Hewlett-Packard             | 37        | 14.68%  |
| Lenovo                      | 33        | 13.1%   |
| ASUSTek Computer            | 32        | 12.7%   |
| Dell                        | 20        | 7.94%   |
| Acer                        | 14        | 5.56%   |
| Gigabyte Technology         | 11        | 4.37%   |
| MSI                         | 10        | 3.97%   |
| HUAWEI                      | 5         | 1.98%   |
| Toshiba                     | 3         | 1.19%   |
| Fujitsu                     | 3         | 1.19%   |
| ASRock                      | 3         | 1.19%   |
| Alienware                   | 3         | 1.19%   |
| Unknown                     | 3         | 1.19%   |
| Sony                        | 2         | 0.79%   |
| Pegatron                    | 2         | 0.79%   |
| Medion                      | 2         | 0.79%   |
| HONOR                       | 2         | 0.79%   |
| Google                      | 2         | 0.79%   |
| Foxconn                     | 2         | 0.79%   |
| Wortmann AG                 | 1         | 0.4%    |
| Star Labs                   | 1         | 0.4%    |
| SHENZHEN YOUDISI E-COMMERCE | 1         | 0.4%    |
| Samsung Electronics         | 1         | 0.4%    |
| Razer                       | 1         | 0.4%    |
| PCBOX                       | 1         | 0.4%    |
| Microsoft                   | 1         | 0.4%    |
| MACHINIST                   | 1         | 0.4%    |
| Jetway                      | 1         | 0.4%    |
| Inventec                    | 1         | 0.4%    |
| Intel                       | 1         | 0.4%    |
| GPU Company                 | 1         | 0.4%    |
| GPD                         | 1         | 0.4%    |
| Gateway                     | 1         | 0.4%    |
| ECS                         | 1         | 0.4%    |
| Digma                       | 1         | 0.4%    |
| Clevo                       | 1         | 0.4%    |
| Chuwi                       | 1         | 0.4%    |
| AZW                         | 1         | 0.4%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Apple MacBookPro9,2                        | 3         | 1.19%   |
| Apple MacBookPro8,1                        | 3         | 1.19%   |
| Apple iMac7,1                              | 3         | 1.19%   |
| Apple iMac12,1                             | 3         | 1.19%   |
| Unknown                                    | 3         | 1.19%   |
| HUAWEI BOD-WXX9                            | 2         | 0.79%   |
| HP 255 G7 Notebook PC                      | 2         | 0.79%   |
| Dell OptiPlex 790                          | 2         | 0.79%   |
| Dell Latitude E7270                        | 2         | 0.79%   |
| Dell Latitude E5570                        | 2         | 0.79%   |
| ASUS H110M-A/M.2                           | 2         | 0.79%   |
| Apple Macmini6,2                           | 2         | 0.79%   |
| Apple MacBookPro5,5                        | 2         | 0.79%   |
| Apple MacBookPro11,3                       | 2         | 0.79%   |
| Apple MacBookPro11,2                       | 2         | 0.79%   |
| Apple MacBookAir7,2                        | 2         | 0.79%   |
| Apple MacBookAir6,2                        | 2         | 0.79%   |
| Apple iMac11,2                             | 2         | 0.79%   |
| Wortmann AG TERRA_PC                       | 1         | 0.4%    |
| Toshiba TECRA Z40-C                        | 1         | 0.4%    |
| Toshiba TECRA R850                         | 1         | 0.4%    |
| Toshiba Satellite C660                     | 1         | 0.4%    |
| Star Labs StarBook                         | 1         | 0.4%    |
| Sony VPCEH2C5E                             | 1         | 0.4%    |
| Sony SVF1521O4E                            | 1         | 0.4%    |
| SHENZHEN YOUDISI E-COMMERCE A8S PRO        | 1         | 0.4%    |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.4%    |
| Razer Blade Stealth                        | 1         | 0.4%    |
| Pegatron Pro 3010 Microtower PC            | 1         | 0.4%    |
| Pegatron IPMIP-GS                          | 1         | 0.4%    |
| PCBOX Kant                                 | 1         | 0.4%    |
| MSI PE70 6QE                               | 1         | 0.4%    |
| MSI MS-7C52                                | 1         | 0.4%    |
| MSI MS-7C31                                | 1         | 0.4%    |
| MSI MS-7C02                                | 1         | 0.4%    |
| MSI MS-7B84                                | 1         | 0.4%    |
| MSI MS-7B17                                | 1         | 0.4%    |
| MSI MS-7816                                | 1         | 0.4%    |
| MSI GT72 2QE                               | 1         | 0.4%    |
| MSI GE62VR 6RF                             | 1         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 16        | 6.35%   |
| Acer Aspire        | 9         | 3.57%   |
| Dell Latitude      | 8         | 3.17%   |
| Lenovo IdeaPad     | 6         | 2.38%   |
| HP Pavilion        | 6         | 2.38%   |
| ASUS ZenBook       | 6         | 2.38%   |
| HP ProBook         | 5         | 1.98%   |
| HP Laptop          | 5         | 1.98%   |
| ASUS VivoBook      | 5         | 1.98%   |
| Apple MacBookPro11 | 5         | 1.98%   |
| ASUS PRIME         | 4         | 1.59%   |
| Apple MacBookPro8  | 4         | 1.59%   |
| Apple iMac12       | 4         | 1.59%   |
| HP 255             | 3         | 1.19%   |
| Fujitsu LIFEBOOK   | 3         | 1.19%   |
| Dell XPS           | 3         | 1.19%   |
| Dell OptiPlex      | 3         | 1.19%   |
| Dell Inspiron      | 3         | 1.19%   |
| Apple Macmini6     | 3         | 1.19%   |
| Apple MacBookPro9  | 3         | 1.19%   |
| Apple MacBookPro5  | 3         | 1.19%   |
| Apple iMac7        | 3         | 1.19%   |
| Unknown            | 3         | 1.19%   |
| Toshiba TECRA      | 2         | 0.79%   |
| Lenovo Yoga        | 2         | 0.79%   |
| Lenovo ThinkCentre | 2         | 0.79%   |
| Lenovo Legion      | 2         | 0.79%   |
| HUAWEI BOD-WXX9    | 2         | 0.79%   |
| HP ProDesk         | 2         | 0.79%   |
| HP ENVY            | 2         | 0.79%   |
| HP EliteDesk       | 2         | 0.79%   |
| HP EliteBook       | 2         | 0.79%   |
| ASUS ROG           | 2         | 0.79%   |
| ASUS H110M-A       | 2         | 0.79%   |
| Apple MacBookAir7  | 2         | 0.79%   |
| Apple MacBookAir6  | 2         | 0.79%   |
| Apple MacBookAir3  | 2         | 0.79%   |
| Apple iMac11       | 2         | 0.79%   |
| Acer Predator      | 2         | 0.79%   |
| Wortmann AG TERRA  | 1         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 25        | 9.92%   |
| 2019 | 23        | 9.13%   |
| 2012 | 23        | 9.13%   |
| 2013 | 19        | 7.54%   |
| 2020 | 18        | 7.14%   |
| 2018 | 16        | 6.35%   |
| 2016 | 16        | 6.35%   |
| 2011 | 15        | 5.95%   |
| 2009 | 15        | 5.95%   |
| 2022 | 14        | 5.56%   |
| 2014 | 14        | 5.56%   |
| 2010 | 14        | 5.56%   |
| 2015 | 11        | 4.37%   |
| 2008 | 11        | 4.37%   |
| 2017 | 10        | 3.97%   |
| 2023 | 4         | 1.59%   |
| 2007 | 4         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 155       | 61.51%  |
| Desktop     | 67        | 26.59%  |
| All in one  | 14        | 5.56%   |
| Convertible | 7         | 2.78%   |
| Mini pc     | 6         | 2.38%   |
| Tablet      | 3         | 1.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 246       | 97.62%  |
| Enabled  | 6         | 2.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 249       | 98.81%  |
| Yes  | 3         | 1.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 75        | 29.64%  |
| 16.01-24.0  | 54        | 21.34%  |
| 8.01-16.0   | 49        | 19.37%  |
| 3.01-4.0    | 46        | 18.18%  |
| 32.01-64.0  | 19        | 7.51%   |
| 64.01-256.0 | 4         | 1.58%   |
| 1.01-2.0    | 3         | 1.19%   |
| 2.01-3.0    | 2         | 0.79%   |
| 24.01-32.0  | 1         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 114       | 43.18%  |
| 1.01-2.0  | 57        | 21.59%  |
| 3.01-4.0  | 51        | 19.32%  |
| 4.01-8.0  | 32        | 12.12%  |
| 8.01-16.0 | 7         | 2.65%   |
| 0.51-1.0  | 3         | 1.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 176       | 69.57%  |
| 2      | 59        | 23.32%  |
| 3      | 10        | 3.95%   |
| 5      | 4         | 1.58%   |
| 4      | 4         | 1.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 163       | 64.43%  |
| Yes       | 90        | 35.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 204       | 80.95%  |
| No        | 48        | 19.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 213       | 84.52%  |
| No        | 39        | 15.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 75.79%  |
| No        | 61        | 24.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 49        | 19.37%  |
| Germany      | 41        | 16.21%  |
| Russia       | 19        | 7.51%   |
| Spain        | 9         | 3.56%   |
| Italy        | 8         | 3.16%   |
| France       | 8         | 3.16%   |
| Brazil       | 8         | 3.16%   |
| UK           | 7         | 2.77%   |
| Poland       | 7         | 2.77%   |
| Netherlands  | 7         | 2.77%   |
| India        | 7         | 2.77%   |
| Australia    | 7         | 2.77%   |
| Canada       | 6         | 2.37%   |
| Sweden       | 4         | 1.58%   |
| Portugal     | 4         | 1.58%   |
| Greece       | 4         | 1.58%   |
| Austria      | 4         | 1.58%   |
| Norway       | 3         | 1.19%   |
| Mexico       | 3         | 1.19%   |
| Indonesia    | 3         | 1.19%   |
| Argentina    | 3         | 1.19%   |
| Venezuela    | 2         | 0.79%   |
| Turkey       | 2         | 0.79%   |
| Thailand     | 2         | 0.79%   |
| Puerto Rico  | 2         | 0.79%   |
| Israel       | 2         | 0.79%   |
| Ireland      | 2         | 0.79%   |
| Hungary      | 2         | 0.79%   |
| Czechia      | 2         | 0.79%   |
| Colombia     | 2         | 0.79%   |
| China        | 2         | 0.79%   |
| Chile        | 2         | 0.79%   |
| Belgium      | 2         | 0.79%   |
| Ukraine      | 1         | 0.4%    |
| Tunisia      | 1         | 0.4%    |
| Switzerland  | 1         | 0.4%    |
| South Africa | 1         | 0.4%    |
| Slovakia     | 1         | 0.4%    |
| Saudi Arabia | 1         | 0.4%    |
| Panama       | 1         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 7         | 2.69%   |
| Vienna         | 4         | 1.54%   |
| Warsaw         | 3         | 1.15%   |
| Stuttgart      | 3         | 1.15%   |
| Perth          | 3         | 1.15%   |
| Munich         | 3         | 1.15%   |
| Melbourne      | 3         | 1.15%   |
| Madrid         | 3         | 1.15%   |
| Delhi          | 3         | 1.15%   |
| Berlin         | 3         | 1.15%   |
| Athens         | 3         | 1.15%   |
| Stockholm      | 2         | 0.77%   |
| St Petersburg  | 2         | 0.77%   |
| Sarasota       | 2         | 0.77%   |
| Nuremberg      | 2         | 0.77%   |
| Novosibirsk    | 2         | 0.77%   |
| Monza          | 2         | 0.77%   |
| Los Angeles    | 2         | 0.77%   |
| Las Vegas      | 2         | 0.77%   |
| Jakarta        | 2         | 0.77%   |
| Hamm           | 2         | 0.77%   |
| Hamburg        | 2         | 0.77%   |
| Faridabad      | 2         | 0.77%   |
| Córdoba       | 2         | 0.77%   |
| Cologne        | 2         | 0.77%   |
| Brampton       | 2         | 0.77%   |
| Bangkok        | 2         | 0.77%   |
| Aubagne        | 2         | 0.77%   |
| Amsterdam      | 2         | 0.77%   |
| Znojmo         | 1         | 0.38%   |
| Zhuantang      | 1         | 0.38%   |
| Zalaegerszeg   | 1         | 0.38%   |
| Yorktown       | 1         | 0.38%   |
| Yekaterinburg  | 1         | 0.38%   |
| Wouldham       | 1         | 0.38%   |
| Worcestershire | 1         | 0.38%   |
| Wilster        | 1         | 0.38%   |
| Wilsdruff      | 1         | 0.38%   |
| Wiesbaden      | 1         | 0.38%   |
| West Jordan    | 1         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 44        | 50     | 12.83%  |
| Samsung Electronics         | 41        | 50     | 11.95%  |
| Seagate                     | 28        | 35     | 8.16%   |
| Sandisk                     | 25        | 27     | 7.29%   |
| Toshiba                     | 21        | 26     | 6.12%   |
| Crucial                     | 21        | 24     | 6.12%   |
| Kingston                    | 14        | 16     | 4.08%   |
| Apple                       | 13        | 13     | 3.79%   |
| Unknown                     | 10        | 11     | 2.92%   |
| Hitachi                     | 10        | 11     | 2.92%   |
| Intel                       | 7         | 8      | 2.04%   |
| China                       | 7         | 7      | 2.04%   |
| SK hynix                    | 6         | 8      | 1.75%   |
| PNY                         | 5         | 5      | 1.46%   |
| Micron Technology           | 5         | 5      | 1.46%   |
| KIOXIA                      | 5         | 8      | 1.46%   |
| Phison Electronics          | 4         | 4      | 1.17%   |
| Intenso                     | 4         | 6      | 1.17%   |
| HGST                        | 4         | 5      | 1.17%   |
| A-DATA Technology           | 4         | 4      | 1.17%   |
| Unknown                     | 4         | 4      | 1.17%   |
| Netac                       | 3         | 4      | 0.87%   |
| Micron/Crucial Technology   | 3         | 3      | 0.87%   |
| Kingston Technology Company | 3         | 3      | 0.87%   |
| Team                        | 2         | 3      | 0.58%   |
| Silicon Motion              | 2         | 2      | 0.58%   |
| Realtek Semiconductor       | 2         | 4      | 0.58%   |
| KingDian                    | 2         | 3      | 0.58%   |
| JMicron Technology          | 2         | 2      | 0.58%   |
| Fujitsu                     | 2         | 2      | 0.58%   |
| BIWIN                       | 2         | 2      | 0.58%   |
| Apacer                      | 2         | 2      | 0.58%   |
| Yeestor                     | 1         | 1      | 0.29%   |
| XrayDisk                    | 1         | 1      | 0.29%   |
| VISIPRO                     | 1         | 1      | 0.29%   |
| Verbatim                    | 1         | 1      | 0.29%   |
| USB30                       | 1         | 1      | 0.29%   |
| USB 3.0                     | 1         | 1      | 0.29%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.29%   |
| Union Memory                | 1         | 2      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 7         | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 6         | 1.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 5         | 1.4%    |
| WDC WD10EZEX-60WN4A0 1TB                           | 4         | 1.12%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 4         | 1.12%   |
| Crucial CT500MX500SSD1 500GB                       | 4         | 1.12%   |
| Crucial CT240BX500SSD1 240GB                       | 4         | 1.12%   |
| Unknown                                            | 4         | 1.12%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 3         | 0.84%   |
| Unknown MMC Card  7GB                              | 3         | 0.84%   |
| Toshiba MQ01ABD100 1TB                             | 3         | 0.84%   |
| Toshiba DT01ACA200 2TB                             | 3         | 0.84%   |
| Samsung SSD 850 EVO 250GB                          | 3         | 0.84%   |
| Phison E12 NVMe Controller 2TB                     | 3         | 0.84%   |
| Apple SSD SD0128F 121GB                            | 3         | 0.84%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 2         | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 2         | 0.56%   |
| WDC WD6400AAKS-22A7B2 640GB                        | 2         | 0.56%   |
| WDC WD10EZEX-21WN4A0 1TB                           | 2         | 0.56%   |
| Unknown MMC Card  32GB                             | 2         | 0.56%   |
| Toshiba MK5065GSXF 500GB                           | 2         | 0.56%   |
| Toshiba DT01ACA050 500GB                           | 2         | 0.56%   |
| SK hynix BC501 NVMe Solid State Drive 512GB        | 2         | 0.56%   |
| Seagate ST9500325AS 500GB                          | 2         | 0.56%   |
| Seagate ST4000DM004-2CV104 4TB                     | 2         | 0.56%   |
| Seagate ST3500418AS 500GB                          | 2         | 0.56%   |
| Seagate Expansion 2TB                              | 2         | 0.56%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 2         | 0.56%   |
| SanDisk SDSSDA240G 240GB                           | 2         | 0.56%   |
| Samsung SSD 860 EVO 1TB                            | 2         | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB  | 2         | 0.56%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD               | 2         | 0.56%   |
| PNY CS900 480GB SSD                                | 2         | 0.56%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                | 2         | 0.56%   |
| Kingston Company SNV2S1000G 1TB                    | 2         | 0.56%   |
| KingDian S280 240GB                                | 2         | 0.56%   |
| Intenso SSD SATAIII 240GB                          | 2         | 0.56%   |
| Intel SSDPEKNU512GZ 512GB                          | 2         | 0.56%   |
| HGST HTS721010A9E630 1TB                           | 2         | 0.56%   |
| Crucial CT480BX500SSD1 480GB                       | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 35     | 32.29%  |
| Seagate             | 26        | 31     | 27.08%  |
| Toshiba             | 16        | 18     | 16.67%  |
| Hitachi             | 10        | 11     | 10.42%  |
| HGST                | 4         | 5      | 4.17%   |
| Samsung Electronics | 3         | 3      | 3.13%   |
| Fujitsu             | 2         | 2      | 2.08%   |
| Unknown             | 1         | 1      | 1.04%   |
| JMicron Technology  | 1         | 1      | 1.04%   |
| ASMT                | 1         | 1      | 1.04%   |
| Apple               | 1         | 1      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 21        | 24     | 14.69%  |
| Samsung Electronics | 17        | 23     | 11.89%  |
| SanDisk             | 14        | 15     | 9.79%   |
| Kingston            | 13        | 15     | 9.09%   |
| Apple               | 11        | 11     | 7.69%   |
| WDC                 | 9         | 11     | 6.29%   |
| China               | 7         | 7      | 4.9%    |
| PNY                 | 5         | 5      | 3.5%    |
| Toshiba             | 4         | 6      | 2.8%    |
| A-DATA Technology   | 4         | 4      | 2.8%    |
| Intenso             | 3         | 5      | 2.1%    |
| Team                | 2         | 3      | 1.4%    |
| Seagate             | 2         | 2      | 1.4%    |
| Netac               | 2         | 2      | 1.4%    |
| Micron Technology   | 2         | 2      | 1.4%    |
| KingDian            | 2         | 3      | 1.4%    |
| Apacer              | 2         | 2      | 1.4%    |
| XrayDisk            | 1         | 1      | 0.7%    |
| VISIPRO             | 1         | 1      | 0.7%    |
| Verbatim            | 1         | 1      | 0.7%    |
| USB30               | 1         | 1      | 0.7%    |
| Transcend           | 1         | 1      | 0.7%    |
| SPCC                | 1         | 1      | 0.7%    |
| SK hynix            | 1         | 1      | 0.7%    |
| SD                  | 1         | 1      | 0.7%    |
| Phison              | 1         | 1      | 0.7%    |
| OWC                 | 1         | 1      | 0.7%    |
| OCZ-VERTEX2         | 1         | 1      | 0.7%    |
| NGFF                | 1         | 1      | 0.7%    |
| MaiChai             | 1         | 1      | 0.7%    |
| LITEONIT            | 1         | 1      | 0.7%    |
| LITEON              | 1         | 1      | 0.7%    |
| KUU                 | 1         | 1      | 0.7%    |
| Intel               | 1         | 1      | 0.7%    |
| Inland              | 1         | 1      | 0.7%    |
| HS-SSD-E100         | 1         | 1      | 0.7%    |
| Hewlett-Packard     | 1         | 1      | 0.7%    |
| Corsair             | 1         | 1      | 0.7%    |
| BIWIN               | 1         | 1      | 0.7%    |
| Unknown             | 1         | 1      | 0.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 133       | 163    | 41.43%  |
| HDD     | 82        | 109    | 25.55%  |
| NVMe    | 81        | 96     | 25.23%  |
| Unknown | 15        | 16     | 4.67%   |
| MMC     | 10        | 11     | 3.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 188       | 270    | 63.51%  |
| NVMe | 81        | 96     | 27.36%  |
| SAS  | 17        | 18     | 5.74%   |
| MMC  | 10        | 11     | 3.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 145       | 181    | 66.51%  |
| 0.51-1.0   | 53        | 69     | 24.31%  |
| 1.01-2.0   | 17        | 19     | 7.8%    |
| 3.01-4.0   | 3         | 3      | 1.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 114       | 44.88%  |
| 251-500        | 68        | 26.77%  |
| 501-1000       | 40        | 15.75%  |
| 51-100         | 17        | 6.69%   |
| 2001-3000      | 5         | 1.97%   |
| 1001-2000      | 4         | 1.57%   |
| 1-20           | 3         | 1.18%   |
| 21-50          | 2         | 0.79%   |
| More than 3000 | 1         | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 123       | 47.49%  |
| 21-50          | 72        | 27.8%   |
| 51-100         | 26        | 10.04%  |
| 101-250        | 25        | 9.65%   |
| 251-500        | 8         | 3.09%   |
| 1001-2000      | 3         | 1.16%   |
| More than 3000 | 1         | 0.39%   |
| 501-1000       | 1         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 228       | 357    | 87.02%  |
| Works    | 33        | 37     | 12.6%   |
| Malfunc  | 1         | 1      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 173       | 55.99%  |
| AMD                            | 37        | 11.97%  |
| Samsung Electronics            | 29        | 9.39%   |
| SanDisk                        | 14        | 4.53%   |
| Nvidia                         | 8         | 2.59%   |
| SK hynix                       | 5         | 1.62%   |
| Phison Electronics             | 5         | 1.62%   |
| Marvell Technology Group       | 5         | 1.62%   |
| KIOXIA                         | 5         | 1.62%   |
| Kingston Technology Company    | 4         | 1.29%   |
| Micron/Crucial Technology      | 3         | 0.97%   |
| Micron Technology              | 3         | 0.97%   |
| ASMedia Technology             | 3         | 0.97%   |
| Union Memory (Shenzhen)        | 2         | 0.65%   |
| Toshiba America Info Systems   | 2         | 0.65%   |
| Solid State Storage Technology | 2         | 0.65%   |
| Silicon Motion                 | 2         | 0.65%   |
| Realtek Semiconductor          | 2         | 0.65%   |
| Shenzhen Longsys Electronics   | 1         | 0.32%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.32%   |
| JMicron Technology             | 1         | 0.32%   |
| INNOGRIT                       | 1         | 0.32%   |
| Biwin Storage Technology       | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 29        | 8.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 5.49%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 3.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11        | 3.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 2.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 2.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 2.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 2.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 2.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 2.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.73%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 1.73%   |
| Nvidia MCP79 AHCI Controller                                                   | 6         | 1.73%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 1.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 1.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.45%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 4         | 1.16%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 4         | 1.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.16%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4         | 1.16%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.16%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.87%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.87%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 3         | 0.87%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 0.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.87%   |
| Intel SSD 660P Series                                                          | 3         | 0.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 0.87%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 0.87%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 3         | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 202       | 62.93%  |
| NVMe | 80        | 24.92%  |
| RAID | 22        | 6.85%   |
| IDE  | 17        | 5.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 204       | 80.95%  |
| AMD    | 48        | 19.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 7         | 2.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 5         | 1.98%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 5         | 1.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 4         | 1.59%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 4         | 1.59%   |
| Intel Core i9-9900K CPU @ 3.60GHz               | 3         | 1.19%   |
| Intel Core i5-2435M CPU @ 2.40GHz               | 3         | 1.19%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 3         | 1.19%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 3         | 1.19%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 2         | 0.79%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 2         | 0.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 2         | 0.79%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 2         | 0.79%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz              | 2         | 0.79%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 2         | 0.79%   |
| Intel Core i7-3770S CPU @ 3.10GHz               | 2         | 0.79%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 2         | 0.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 0.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 2         | 0.79%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 2         | 0.79%   |
| Intel Core i5-2400S CPU @ 2.50GHz               | 2         | 0.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 2         | 0.79%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 2         | 0.79%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 0.79%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 0.79%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 2         | 0.79%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 2         | 0.79%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz            | 2         | 0.79%   |
| Intel Celeron N5105 @ 2.00GHz                   | 2         | 0.79%   |
| Intel 12th Gen Core i7-1260P                    | 2         | 0.79%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 0.79%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 2         | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 0.79%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 0.79%   |
| Intel Xeon CPU W3520 @ 2.67GHz                  | 1         | 0.4%    |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz             | 1         | 0.4%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz     | 1         | 0.4%    |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz     | 1         | 0.4%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 65        | 25.79%  |
| Intel Core i7           | 44        | 17.46%  |
| Other                   | 27        | 10.71%  |
| Intel Core 2 Duo        | 19        | 7.54%   |
| Intel Core i3           | 18        | 7.14%   |
| Intel Celeron           | 17        | 6.75%   |
| AMD Ryzen 7             | 12        | 4.76%   |
| AMD Ryzen 5             | 10        | 3.97%   |
| Intel Pentium           | 5         | 1.98%   |
| Intel Pentium Dual-Core | 3         | 1.19%   |
| Intel Core i9           | 3         | 1.19%   |
| AMD Ryzen 3             | 3         | 1.19%   |
| AMD Athlon              | 3         | 1.19%   |
| AMD A8                  | 3         | 1.19%   |
| Intel Xeon              | 2         | 0.79%   |
| Intel Pentium Silver    | 2         | 0.79%   |
| AMD Ryzen 9             | 2         | 0.79%   |
| AMD Ryzen 5 PRO         | 2         | 0.79%   |
| AMD A4                  | 2         | 0.79%   |
| AMD A12                 | 2         | 0.79%   |
| AMD Sempron             | 1         | 0.4%    |
| AMD Phenom II X6        | 1         | 0.4%    |
| AMD Phenom II X4        | 1         | 0.4%    |
| AMD G                   | 1         | 0.4%    |
| AMD FX                  | 1         | 0.4%    |
| AMD E1                  | 1         | 0.4%    |
| AMD Athlon 64 X2        | 1         | 0.4%    |
| AMD A6                  | 1         | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 114       | 45.06%  |
| 4      | 91        | 35.97%  |
| 8      | 19        | 7.51%   |
| 6      | 13        | 5.14%   |
| 12     | 6         | 2.37%   |
| 1      | 5         | 1.98%   |
| 10     | 2         | 0.79%   |
| 5      | 2         | 0.79%   |
| 14     | 1         | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 252       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 178       | 70.63%  |
| 1      | 74        | 29.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 252       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 215       | 84.65%  |
| 0x806ec    | 3         | 1.18%   |
| 0x806c1    | 3         | 1.18%   |
| 0x706e5    | 3         | 1.18%   |
| 0x906e9    | 2         | 0.79%   |
| 0x906a4    | 2         | 0.79%   |
| 0x806d1    | 2         | 0.79%   |
| 0x706a8    | 2         | 0.79%   |
| 0x306a9    | 2         | 0.79%   |
| 0x206a7    | 2         | 0.79%   |
| 0x0a50000c | 2         | 0.79%   |
| 0x906ec    | 1         | 0.39%   |
| 0x906c0    | 1         | 0.39%   |
| 0x906a3    | 1         | 0.39%   |
| 0x806eb    | 1         | 0.39%   |
| 0x806ea    | 1         | 0.39%   |
| 0x706a1    | 1         | 0.39%   |
| 0x40661    | 1         | 0.39%   |
| 0x40651    | 1         | 0.39%   |
| 0x1067a    | 1         | 0.39%   |
| 0x10676    | 1         | 0.39%   |
| 0x0a50000d | 1         | 0.39%   |
| 0x08600106 | 1         | 0.39%   |
| 0x08108109 | 1         | 0.39%   |
| 0x07030106 | 1         | 0.39%   |
| 0x0600611a | 1         | 0.39%   |
| 0x010000c8 | 1         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 11.9%   |
| IvyBridge        | 25        | 9.92%   |
| Haswell          | 25        | 9.92%   |
| Penryn           | 19        | 7.54%   |
| SandyBridge      | 18        | 7.14%   |
| Skylake          | 17        | 6.75%   |
| TigerLake        | 14        | 5.56%   |
| Unknown          | 14        | 5.56%   |
| Goldmont plus    | 11        | 4.37%   |
| Zen+             | 9         | 3.57%   |
| Westmere         | 9         | 3.57%   |
| Zen 3            | 7         | 2.78%   |
| Zen 2            | 7         | 2.78%   |
| IceLake          | 6         | 2.38%   |
| Broadwell        | 6         | 2.38%   |
| Zen              | 4         | 1.59%   |
| Silvermont       | 4         | 1.59%   |
| Excavator        | 4         | 1.59%   |
| Core             | 4         | 1.59%   |
| Puma             | 3         | 1.19%   |
| K10              | 3         | 1.19%   |
| Alderlake Hybrid | 3         | 1.19%   |
| Steamroller      | 2         | 0.79%   |
| Piledriver       | 2         | 0.79%   |
| Nehalem          | 2         | 0.79%   |
| Tremont          | 1         | 0.4%    |
| K8 Hammer        | 1         | 0.4%    |
| CometLake        | 1         | 0.4%    |
| Bobcat           | 1         | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 161       | 54.76%  |
| Nvidia | 67        | 22.79%  |
| AMD    | 66        | 22.45%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 18        | 6%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 15        | 5%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 10        | 3.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 10        | 3.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 9         | 3%      |
| Intel GeminiLake [UHD Graphics 600]                                       | 9         | 3%      |
| Intel Core Processor Integrated Graphics Controller                       | 7         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 7         | 2.33%   |
| Intel HD Graphics 530                                                     | 6         | 2%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 6         | 2%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 1.67%   |
| Intel HD Graphics 630                                                     | 5         | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 1.67%   |
| Nvidia C79 [GeForce 9400M]                                                | 4         | 1.33%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 4         | 1.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 1.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 1.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 1.33%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 4         | 1.33%   |
| AMD Lucienne                                                              | 4         | 1.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 3         | 1%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 1%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1%      |
| Intel HD Graphics 620                                                     | 3         | 1%      |
| Intel HD Graphics 5500                                                    | 3         | 1%      |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 3         | 1%      |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 3         | 1%      |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                    | 3         | 1%      |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 3         | 1%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3         | 1%      |
| Nvidia MCP89 [GeForce 320M]                                               | 2         | 0.67%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 2         | 0.67%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 2         | 0.67%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                               | 2         | 0.67%   |
| Nvidia GK107 [GeForce GTX 650]                                            | 2         | 0.67%   |
| Nvidia GK107 [GeForce GT 640]                                             | 2         | 0.67%   |
| Nvidia GF119 [GeForce GT 610]                                             | 2         | 0.67%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 2         | 0.67%   |
| Intel UHD Graphics 620                                                    | 2         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 121       | 48.02%  |
| 1 x AMD         | 55        | 21.83%  |
| 1 x Nvidia      | 36        | 14.29%  |
| Intel + Nvidia  | 27        | 10.71%  |
| Intel + AMD     | 5         | 1.98%   |
| 2 x AMD         | 3         | 1.19%   |
| AMD + Nvidia    | 2         | 0.79%   |
| Other           | 1         | 0.4%    |
| 2 x Nvidia      | 1         | 0.4%    |
| Intel + 2 x AMD | 1         | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 237       | 94.05%  |
| Proprietary | 12        | 4.76%   |
| Unknown     | 3         | 1.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 236       | 93.65%  |
| 1.01-2.0   | 4         | 1.59%   |
| 0.01-0.5   | 4         | 1.59%   |
| 7.01-8.0   | 3         | 1.19%   |
| 0.51-1.0   | 3         | 1.19%   |
| 3.01-4.0   | 2         | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Apple                   | 39        | 14.5%   |
| AU Optronics            | 32        | 11.9%   |
| LG Display              | 27        | 10.04%  |
| BOE                     | 24        | 8.92%   |
| Samsung Electronics     | 22        | 8.18%   |
| Chimei Innolux          | 19        | 7.06%   |
| Goldstar                | 16        | 5.95%   |
| Dell                    | 11        | 4.09%   |
| Sharp                   | 8         | 2.97%   |
| Acer                    | 7         | 2.6%    |
| Lenovo                  | 5         | 1.86%   |
| Hewlett-Packard         | 5         | 1.86%   |
| BenQ                    | 4         | 1.49%   |
| ViewSonic               | 3         | 1.12%   |
| Philips                 | 3         | 1.12%   |
| PANDA                   | 3         | 1.12%   |
| AOC                     | 3         | 1.12%   |
| Vizio                   | 2         | 0.74%   |
| Sceptre Tech            | 2         | 0.74%   |
| NEC Computers           | 2         | 0.74%   |
| Fujitsu Siemens         | 2         | 0.74%   |
| Chi Mei Optoelectronics | 2         | 0.74%   |
| ASUSTek Computer        | 2         | 0.74%   |
| ___                     | 1         | 0.37%   |
| XCX                     | 1         | 0.37%   |
| Unknown                 | 1         | 0.37%   |
| Toshiba                 | 1         | 0.37%   |
| Sony                    | 1         | 0.37%   |
| Seiki                   | 1         | 0.37%   |
| RGT                     | 1         | 0.37%   |
| RCA                     | 1         | 0.37%   |
| Positivo                | 1         | 0.37%   |
| Panasonic               | 1         | 0.37%   |
| NSL                     | 1         | 0.37%   |
| MYS                     | 1         | 0.37%   |
| MSI                     | 1         | 0.37%   |
| Mi                      | 1         | 0.37%   |
| LG Philips              | 1         | 0.37%   |
| Kogan                   | 1         | 0.37%   |
| InfoVision              | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 3         | 1.08%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                     | 3         | 1.08%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 3         | 1.08%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch        | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 0.72%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch     | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 0.72%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 2         | 0.72%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 2         | 0.72%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 2         | 0.72%   |
| Apple LCD Monitor Color LCD 2880x1800                                | 2         | 0.72%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch               | 2         | 0.72%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 2         | 0.72%   |
| Apple Color LCD APPA019 2880x1800 331x207mm 15.4-inch                | 2         | 0.72%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 2         | 0.72%   |
| Apple Color LCD APP9CDD 1920x1080 475x267mm 21.5-inch                | 2         | 0.72%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 2         | 0.72%   |
| Apple Color LCD APP9C6C 1920x1200 520x320mm 24.0-inch                | 2         | 0.72%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                | 2         | 0.72%   |
| ___ LCDTV16 ___3393 1920x1080                                        | 1         | 0.36%   |
| XCX LCD Monitor XCX0844 1366x768 256x144mm 11.6-inch                 | 1         | 0.36%   |
| Vizio E470VL VIZ0057 1920x1080 1040x580mm 46.9-inch                  | 1         | 0.36%   |
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch                   | 1         | 0.36%   |
| ViewSonic VP201b VSC6911 1600x1200 408x306mm 20.1-inch               | 1         | 0.36%   |
| Unknown LCDTV16 3393 1920x1080 1600x900mm 72.3-inch                  | 1         | 0.36%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                | 1         | 0.36%   |
| Sony TV SNY7A02 1360x768 576x324mm 26.0-inch                         | 1         | 0.36%   |
| Sharp LCD Monitor SHP151C 1920x1080 344x194mm 15.5-inch              | 1         | 0.36%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 1         | 0.36%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch              | 1         | 0.36%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch              | 1         | 0.36%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 1         | 0.36%   |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch              | 1         | 0.36%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 1         | 0.36%   |
| Sharp HDMI SHP1048 1920x1080 820x460mm 37.0-inch                     | 1         | 0.36%   |
| Seiki SC32FI SEK3201 1680x1050 698x392mm 31.5-inch                   | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 120       | 45.8%   |
| 1366x768 (WXGA)    | 46        | 17.56%  |
| 1280x800 (WXGA)    | 13        | 4.96%   |
| 3840x2160 (4K)     | 10        | 3.82%   |
| 1920x1200 (WUXGA)  | 10        | 3.82%   |
| 1440x900 (WXGA+)   | 9         | 3.44%   |
| 2880x1800          | 8         | 3.05%   |
| 2560x1440 (QHD)    | 8         | 3.05%   |
| 1680x1050 (WSXGA+) | 7         | 2.67%   |
| 1600x900 (HD+)     | 5         | 1.91%   |
| 1280x1024 (SXGA)   | 5         | 1.91%   |
| 3440x1440          | 3         | 1.15%   |
| 2560x1600          | 3         | 1.15%   |
| 2560x1080          | 3         | 1.15%   |
| 1360x768           | 3         | 1.15%   |
| 3840x2400          | 1         | 0.38%   |
| 3840x1080          | 1         | 0.38%   |
| 3360x1080          | 1         | 0.38%   |
| 2880x1920          | 1         | 0.38%   |
| 2736x1824          | 1         | 0.38%   |
| 2048x1536          | 1         | 0.38%   |
| 1920x1280          | 1         | 0.38%   |
| 1600x1200          | 1         | 0.38%   |
| Unknown            | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 74        | 27.01%  |
| 13      | 35        | 12.77%  |
| 14      | 23        | 8.39%   |
| 27      | 20        | 7.3%    |
| 21      | 19        | 6.93%   |
| 24      | 17        | 6.2%    |
| 17      | 13        | 4.74%   |
| 12      | 8         | 2.92%   |
| 23      | 7         | 2.55%   |
| 19      | 6         | 2.19%   |
| 31      | 5         | 1.82%   |
| 20      | 5         | 1.82%   |
| 18      | 5         | 1.82%   |
| 11      | 5         | 1.82%   |
| Unknown | 5         | 1.82%   |
| 34      | 4         | 1.46%   |
| 22      | 4         | 1.46%   |
| 84      | 2         | 0.73%   |
| 60      | 2         | 0.73%   |
| 42      | 2         | 0.73%   |
| 86      | 1         | 0.36%   |
| 72      | 1         | 0.36%   |
| 65      | 1         | 0.36%   |
| 54      | 1         | 0.36%   |
| 49      | 1         | 0.36%   |
| 48      | 1         | 0.36%   |
| 36      | 1         | 0.36%   |
| 35      | 1         | 0.36%   |
| 32      | 1         | 0.36%   |
| 29      | 1         | 0.36%   |
| 28      | 1         | 0.36%   |
| 26      | 1         | 0.36%   |
| 16      | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 103       | 38.01%  |
| 501-600     | 43        | 15.87%  |
| 201-300     | 41        | 15.13%  |
| 401-500     | 34        | 12.55%  |
| 351-400     | 19        | 7.01%   |
| 601-700     | 7         | 2.58%   |
| 1001-1500   | 7         | 2.58%   |
| 701-800     | 6         | 2.21%   |
| Unknown     | 5         | 1.85%   |
| 1501-2000   | 3         | 1.11%   |
| 901-1000    | 2         | 0.74%   |
| 801-900     | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 183       | 71.48%  |
| 16/10   | 49        | 19.14%  |
| 21/9    | 6         | 2.34%   |
| 3/2     | 5         | 1.95%   |
| Unknown | 4         | 1.56%   |
| 5/4     | 3         | 1.17%   |
| 4/3     | 3         | 1.17%   |
| 6/5     | 1         | 0.39%   |
| 32/9    | 1         | 0.39%   |
| 0.56    | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 75        | 27.57%  |
| 81-90          | 40        | 14.71%  |
| 201-250        | 33        | 12.13%  |
| 301-350        | 20        | 7.35%   |
| 71-80          | 18        | 6.62%   |
| 151-200        | 17        | 6.25%   |
| 351-500        | 12        | 4.41%   |
| More than 1000 | 9         | 3.31%   |
| 121-130        | 9         | 3.31%   |
| 251-300        | 8         | 2.94%   |
| 61-70          | 7         | 2.57%   |
| 51-60          | 5         | 1.84%   |
| 141-150        | 5         | 1.84%   |
| Unknown        | 5         | 1.84%   |
| 131-140        | 4         | 1.47%   |
| 501-1000       | 4         | 1.47%   |
| 111-120        | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 86        | 32.7%   |
| 101-120       | 72        | 27.38%  |
| 51-100        | 66        | 25.1%   |
| 161-240       | 20        | 7.6%    |
| 1-50          | 9         | 3.42%   |
| More than 240 | 5         | 1.9%    |
| Unknown       | 5         | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 217       | 85.77%  |
| 2     | 31        | 12.25%  |
| 0     | 3         | 1.19%   |
| 3     | 2         | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 114       | 30.08%  |
| Intel                             | 106       | 27.97%  |
| Broadcom                          | 51        | 13.46%  |
| Qualcomm Atheros                  | 41        | 10.82%  |
| Marvell Technology Group          | 8         | 2.11%   |
| Broadcom Limited                  | 7         | 1.85%   |
| Ralink Technology                 | 6         | 1.58%   |
| Nvidia                            | 6         | 1.58%   |
| TP-Link                           | 5         | 1.32%   |
| Samsung Electronics               | 5         | 1.32%   |
| Xiaomi                            | 3         | 0.79%   |
| Qualcomm                          | 3         | 0.79%   |
| MediaTek                          | 3         | 0.79%   |
| Huawei Technologies               | 3         | 0.79%   |
| Dell                              | 3         | 0.79%   |
| ASIX Electronics                  | 3         | 0.79%   |
| Ralink                            | 2         | 0.53%   |
| NetGear                           | 2         | 0.53%   |
| Ericsson Business Mobile Networks | 2         | 0.53%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.26%   |
| Sierra Wireless                   | 1         | 0.26%   |
| OPPO Electronics                  | 1         | 0.26%   |
| Motorola PCS                      | 1         | 0.26%   |
| Linksys                           | 1         | 0.26%   |
| ASUSTek Computer                  | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 73        | 15.97%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 12        | 2.63%   |
| Intel Wireless 8260                                                    | 12        | 2.63%   |
| Intel Wi-Fi 6 AX201                                                    | 12        | 2.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 12        | 2.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 11        | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 2.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 7         | 1.53%   |
| Intel Wireless 3165                                                    | 7         | 1.53%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 1.53%   |
| Nvidia MCP79 Ethernet                                                  | 6         | 1.31%   |
| Intel Wi-Fi 6 AX200                                                    | 6         | 1.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 1.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 1.09%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 5         | 1.09%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 5         | 1.09%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 5         | 1.09%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 5         | 1.09%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 5         | 1.09%   |
| Broadcom BCM4321 802.11a/b/g/n                                         | 5         | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                          | 5         | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.88%   |
| Intel Wireless 7265                                                    | 4         | 0.88%   |
| Intel Wireless 7260                                                    | 4         | 0.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 0.88%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 4         | 0.88%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 4         | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3         | 0.66%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 0.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.66%   |
| Realtek 802.11ac NIC                                                   | 3         | 0.66%   |
| Ralink RT5370 Wireless Adapter                                         | 3         | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 3         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 85        | 36.96%  |
| Broadcom                 | 42        | 18.26%  |
| Realtek Semiconductor    | 41        | 17.83%  |
| Qualcomm Atheros         | 31        | 13.48%  |
| Ralink Technology        | 6         | 2.61%   |
| Broadcom Limited         | 6         | 2.61%   |
| TP-Link                  | 4         | 1.74%   |
| MediaTek                 | 3         | 1.3%    |
| Ralink                   | 2         | 0.87%   |
| Qualcomm                 | 2         | 0.87%   |
| Marvell Technology Group | 2         | 0.87%   |
| Dell                     | 2         | 0.87%   |
| Sierra Wireless          | 1         | 0.43%   |
| NetGear                  | 1         | 0.43%   |
| Linksys                  | 1         | 0.43%   |
| ASUSTek Computer         | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 12        | 5.13%   |
| Intel Wireless 8260                                                  | 12        | 5.13%   |
| Intel Wi-Fi 6 AX201                                                  | 12        | 5.13%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 11        | 4.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 7         | 2.99%   |
| Intel Wireless 3165                                                  | 7         | 2.99%   |
| Intel Wi-Fi 6 AX200                                                  | 6         | 2.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 5         | 2.14%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 5         | 2.14%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 5         | 2.14%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 5         | 2.14%   |
| Broadcom BCM4321 802.11a/b/g/n                                       | 5         | 2.14%   |
| Broadcom BCM43142 802.11b/g/n                                        | 5         | 2.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 4         | 1.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 4         | 1.71%   |
| Intel Wireless 7265                                                  | 4         | 1.71%   |
| Intel Wireless 7260                                                  | 4         | 1.71%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 4         | 1.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 4         | 1.71%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 4         | 1.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 3         | 1.28%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 3         | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 3         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 1.28%   |
| Realtek 802.11ac NIC                                                 | 3         | 1.28%   |
| Ralink RT5370 Wireless Adapter                                       | 3         | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 1.28%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 3         | 1.28%   |
| Intel Wireless 8265 / 8275                                           | 3         | 1.28%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 3         | 1.28%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 3         | 1.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 1.28%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2         | 0.85%   |
| Realtek 802.11n WLAN Adapter                                         | 2         | 0.85%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 2         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 95        | 43.38%  |
| Intel                      | 52        | 23.74%  |
| Broadcom                   | 24        | 10.96%  |
| Qualcomm Atheros           | 16        | 7.31%   |
| Nvidia                     | 6         | 2.74%   |
| Marvell Technology Group   | 6         | 2.74%   |
| Samsung Electronics        | 5         | 2.28%   |
| Xiaomi                     | 3         | 1.37%   |
| Huawei Technologies        | 3         | 1.37%   |
| ASIX Electronics           | 3         | 1.37%   |
| ZTE WCDMA Technologies MSM | 1         | 0.46%   |
| TP-Link                    | 1         | 0.46%   |
| Qualcomm                   | 1         | 0.46%   |
| OPPO Electronics           | 1         | 0.46%   |
| NetGear                    | 1         | 0.46%   |
| Broadcom Limited           | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 73        | 33.33%  |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 12        | 5.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 4.57%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 3.2%    |
| Nvidia MCP79 Ethernet                                                  | 6         | 2.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 2.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 2.28%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 5         | 2.28%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 4         | 1.83%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 1.37%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 1.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 1.37%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 1.37%   |
| Intel Ethernet Controller I225-V                                       | 3         | 1.37%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.37%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 1.37%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.37%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 3         | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.91%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.91%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.91%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.91%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.91%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.91%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.91%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.91%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.91%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 0.91%   |
| Huawei VTR-L09                                                         | 2         | 0.91%   |
| ZTE WCDMA MSM Unisoc Phone                                             | 1         | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.46%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.46%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.46%   |
| Qualcomm Nokia G42 5G                                                  | 1         | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.46%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1         | 0.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 213       | 50.59%  |
| Ethernet | 204       | 48.46%  |
| Modem    | 3         | 0.71%   |
| Unknown  | 1         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 154       | 59.92%  |
| Ethernet | 103       | 40.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 142       | 56.35%  |
| 1     | 102       | 40.48%  |
| 3     | 5         | 1.98%   |
| 0     | 3         | 1.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 176       | 69.57%  |
| Yes  | 77        | 30.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 40.31%  |
| Apple                           | 42        | 21.99%  |
| Realtek Semiconductor           | 23        | 12.04%  |
| Qualcomm Atheros Communications | 10        | 5.24%   |
| Broadcom                        | 8         | 4.19%   |
| Lite-On Technology              | 6         | 3.14%   |
| Foxconn / Hon Hai               | 6         | 3.14%   |
| IMC Networks                    | 5         | 2.62%   |
| Cambridge Silicon Radio         | 5         | 2.62%   |
| ASUSTek Computer                | 3         | 1.57%   |
| Toshiba                         | 1         | 0.52%   |
| Ralink                          | 1         | 0.52%   |
| MediaTek                        | 1         | 0.52%   |
| Hewlett-Packard                 | 1         | 0.52%   |
| Askey Computer                  | 1         | 0.52%   |
| Unknown                         | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 17        | 8.9%    |
| Apple Bluetooth Host Controller                     | 16        | 8.38%   |
| Intel Bluetooth Device                              | 15        | 7.85%   |
| Intel Bluetooth wireless interface                  | 14        | 7.33%   |
| Realtek Bluetooth Radio                             | 12        | 6.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 6.28%   |
| Apple Bluetooth USB Host Controller                 | 12        | 6.28%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 5.24%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 9         | 4.71%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 3.14%   |
| Intel AX200 Bluetooth                               | 6         | 3.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 2.62%   |
| Apple Bluetooth HCI                                 | 5         | 2.62%   |
| Lite-On Bluetooth Device                            | 4         | 2.09%   |
| Intel AX210 Bluetooth                               | 4         | 2.09%   |
| Intel AX211 Bluetooth                               | 3         | 1.57%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.57%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.57%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.05%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.05%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.05%   |
| Toshiba Bluetooth Device                            | 1         | 0.52%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.52%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.52%   |
| MediaTek Wireless_Device                            | 1         | 0.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.52%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.52%   |
| IMC Networks Bluetooth                              | 1         | 0.52%   |
| IMC Networks BCM20702A0                             | 1         | 0.52%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.52%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.52%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.52%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.52%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.52%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 196       | 58.33%  |
| AMD                      | 64        | 19.05%  |
| Nvidia                   | 48        | 14.29%  |
| C-Media Electronics      | 9         | 2.68%   |
| Logitech                 | 5         | 1.49%   |
| Sony                     | 1         | 0.3%    |
| Samson Technologies      | 1         | 0.3%    |
| Realtek Semiconductor    | 1         | 0.3%    |
| Razer USA                | 1         | 0.3%    |
| Nordic Semiconductor ASA | 1         | 0.3%    |
| Microsoft                | 1         | 0.3%    |
| KTMicro                  | 1         | 0.3%    |
| Hewlett-Packard          | 1         | 0.3%    |
| Goldvish                 | 1         | 0.3%    |
| GN Netcom                | 1         | 0.3%    |
| Generalplus Technology   | 1         | 0.3%    |
| Dell                     | 1         | 0.3%    |
| Creative Labs            | 1         | 0.3%    |
| ASUSTek Computer         | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 25        | 6.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 22        | 5.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21        | 5.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 3.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 3.49%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 3.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 3.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 11        | 2.74%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 2.49%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 2.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 2.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 2.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 2%      |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 2%      |
| Nvidia GK107 HDMI Audio Controller                                         | 7         | 1.75%   |
| Nvidia MCP79 High Definition Audio                                         | 6         | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 1.5%    |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 1.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 1.5%    |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 1.5%    |
| AMD FCH Azalia Controller                                                  | 6         | 1.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.25%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1%      |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1%      |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1%      |
| Intel 200 Series PCH HD Audio                                              | 4         | 1%      |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4         | 1%      |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 1%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1%      |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.75%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.75%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 0.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 32.08%  |
| Micron Technology   | 11        | 20.75%  |
| SK hynix            | 6         | 11.32%  |
| Kingston            | 4         | 7.55%   |
| Unknown (ABCD)      | 2         | 3.77%   |
| Unknown             | 2         | 3.77%   |
| Unknown (0x5846)    | 1         | 1.89%   |
| Unknown             | 1         | 1.89%   |
| Ramaxel Technology  | 1         | 1.89%   |
| pqi                 | 1         | 1.89%   |
| GSkill              | 1         | 1.89%   |
| Elpida              | 1         | 1.89%   |
| CSX                 | 1         | 1.89%   |
| Crucial             | 1         | 1.89%   |
| Corsair             | 1         | 1.89%   |
| Apacer              | 1         | 1.89%   |
| A-DATA Technology   | 1         | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.77%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 3.77%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 3.77%   |
| Unknown                                                          | 2         | 3.77%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.89%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s    | 1         | 1.89%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 1.89%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.89%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.89%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.89%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.89%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 1         | 1.89%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                     | 1         | 1.89%   |
| Samsung RAM M471B5273EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.89%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.89%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.89%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.89%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.89%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.89%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.89%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s              | 1         | 1.89%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s              | 1         | 1.89%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.89%   |
| Ramaxel RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.89%   |
| pqi RAM Module 2GB SODIMM DDR2 667MT/s                           | 1         | 1.89%   |
| Micron RAM MT53E1G32D4NQ-046 8GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.89%   |
| Micron RAM MT53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.89%   |
| Micron RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 1.89%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.89%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.89%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.89%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.89%   |
| Micron RAM 16ATF4G64HZ-3G2E2 32GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| Micron RAM 16ATF2G64HZ-2G6E3 16GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 1.89%   |
| Kingston RAM HX426C16FB/4 4GB DIMM DDR4 2800MT/s                 | 1         | 1.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 22        | 46.81%  |
| DDR3    | 13        | 27.66%  |
| LPDDR4  | 7         | 14.89%  |
| SDRAM   | 1         | 2.13%   |
| LPDDR3  | 1         | 2.13%   |
| DDR5    | 1         | 2.13%   |
| DDR2    | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 63.83%  |
| Row Of Chips | 9         | 19.15%  |
| DIMM         | 8         | 17.02%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 27        | 56.25%  |
| 4096  | 11        | 22.92%  |
| 2048  | 5         | 10.42%  |
| 16384 | 4         | 8.33%   |
| 32768 | 1         | 2.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 12        | 24%     |
| 2667  | 9         | 18%     |
| 1600  | 9         | 18%     |
| 4267  | 5         | 10%     |
| 2400  | 4         | 8%      |
| 1333  | 3         | 6%      |
| 4800  | 1         | 2%      |
| 3066  | 1         | 2%      |
| 2800  | 1         | 2%      |
| 2133  | 1         | 2%      |
| 2000  | 1         | 2%      |
| 800   | 1         | 2%      |
| 667   | 1         | 2%      |
| 533   | 1         | 2%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Canon               | 1         | 20%     |
| Brother Industries  | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung M2020 Series         | 1         | 20%     |
| HP Smart Tank 580-590 series | 1         | 20%     |
| HP DeskJet 2600 series       | 1         | 20%     |
| Canon MF4320-4350            | 1         | 20%     |
| Brother MFC-J5330DW          | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson ES-H300 [GT-2500] | 1         | 33.33%  |
| Canon CanoScan LIDE 25        | 1         | 33.33%  |
| Canon CanoScan LiDE 100       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Apple                                  | 33        | 19.53%  |
| Chicony Electronics                    | 27        | 15.98%  |
| Quanta                                 | 15        | 8.88%   |
| IMC Networks                           | 14        | 8.28%   |
| Realtek Semiconductor                  | 11        | 6.51%   |
| Microdia                               | 11        | 6.51%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 5.33%   |
| Sunplus Innovation Technology          | 7         | 4.14%   |
| Bison Electronics                      | 7         | 4.14%   |
| Samsung Electronics                    | 3         | 1.78%   |
| Luxvisions Innotech Limited            | 3         | 1.78%   |
| Logitech                               | 3         | 1.78%   |
| Acer                                   | 3         | 1.78%   |
| Syntek                                 | 2         | 1.18%   |
| SunplusIT                              | 2         | 1.18%   |
| Sonix Technology                       | 2         | 1.18%   |
| Lite-On Technology                     | 2         | 1.18%   |
| Lenovo                                 | 2         | 1.18%   |
| Generalplus Technology                 | 2         | 1.18%   |
| Alcor Micro                            | 2         | 1.18%   |
| Y Media                                | 1         | 0.59%   |
| Suyin                                  | 1         | 0.59%   |
| Sunplus Technology                     | 1         | 0.59%   |
| Silicon Motion                         | 1         | 0.59%   |
| Shine-optics                           | 1         | 0.59%   |
| Intel                                  | 1         | 0.59%   |
| Cubeternet                             | 1         | 0.59%   |
| Cisco Systems                          | 1         | 0.59%   |
| AVerMedia Technologies                 | 1         | 0.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Apple Built-in iSight                            | 13        | 7.6%    |
| Chicony Integrated Camera                        | 8         | 4.68%   |
| Apple FaceTime HD Camera                         | 7         | 4.09%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 6         | 3.51%   |
| Apple FaceTime HD Camera (Built-in)              | 6         | 3.51%   |
| Microdia Integrated_Webcam_HD                    | 5         | 2.92%   |
| Realtek Integrated_Webcam_HD                     | 4         | 2.34%   |
| IMC Networks USB2.0 HD UVC WebCam                | 4         | 2.34%   |
| IMC Networks Integrated Camera                   | 4         | 2.34%   |
| Chicony HD WebCam                                | 4         | 2.34%   |
| Samsung Galaxy series, misc. (MTP mode)          | 3         | 1.75%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 1.17%   |
| Sunplus Dell E5570 integrated webcam             | 2         | 1.17%   |
| Realtek USB Camera                               | 2         | 1.17%   |
| Quanta USB2.0 HD UVC WebCam                      | 2         | 1.17%   |
| Quanta HP Wide Vision HD Camera                  | 2         | 1.17%   |
| Quanta HP TrueVision HD Camera                   | 2         | 1.17%   |
| Quanta HP HD Camera                              | 2         | 1.17%   |
| Quanta HD Camera                                 | 2         | 1.17%   |
| Microdia Webcam Vitade AF                        | 2         | 1.17%   |
| Microdia Integrated Webcam                       | 2         | 1.17%   |
| Lite-On Integrated Camera                        | 2         | 1.17%   |
| IMC Networks HD Camera                           | 2         | 1.17%   |
| Chicony HP Webcam                                | 2         | 1.17%   |
| Chicony HP TrueVision HD Camera                  | 2         | 1.17%   |
| Chicony HP Truevision HD                         | 2         | 1.17%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.17%   |
| Bison Lenovo Integrated Webcam                   | 2         | 1.17%   |
| Bison Integrated Camera                          | 2         | 1.17%   |
| Apple FaceTime Camera                            | 2         | 1.17%   |
| Y Media USB Camera                               | 1         | 0.58%   |
| Syntek Lenovo EasyCamera                         | 1         | 0.58%   |
| Syntek EasyCamera                                | 1         | 0.58%   |
| Suyin HD Video WebCam                            | 1         | 0.58%   |
| SunplusIT USB 2.0 Camera                         | 1         | 0.58%   |
| SunplusIT HD Camera                              | 1         | 0.58%   |
| Sunplus 1.3M HD WebCam                           | 1         | 0.58%   |
| Sunplus PC Camera                                | 1         | 0.58%   |
| Sunplus Integrated Camera                        | 1         | 0.58%   |
| Sunplus HD WebCam                                | 1         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 35.48%  |
| Shenzhen Goodix Technology | 8         | 25.81%  |
| Synaptics                  | 4         | 12.9%   |
| Elan Microelectronics      | 4         | 12.9%   |
| LighTuning Technology      | 2         | 6.45%   |
| Upek                       | 1         | 3.23%   |
| AuthenTec                  | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 19.35%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 9.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 6.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 6.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 6.45%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.45%   |
| Elan ELAN:ARM-M4                                                           | 2         | 6.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 3.23%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 3.23%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.23%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 3.23%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.23%   |
| LighTuning Fingerprint Reader                                              | 1         | 3.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.23%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 40%     |
| Upek        | 2         | 20%     |
| Alcor Micro | 2         | 20%     |
| OmniKey     | 1         | 10%     |
| O2 Micro    | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 170       | 67.46%  |
| 1     | 64        | 25.4%   |
| 2     | 17        | 6.75%   |
| 3     | 1         | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 30        | 30.3%   |
| Net/wireless             | 24        | 24.24%  |
| Multimedia controller    | 20        | 20.2%   |
| Chipcard                 | 10        | 10.1%   |
| Graphics card            | 8         | 8.08%   |
| Net/ethernet             | 2         | 2.02%   |
| Storage                  | 1         | 1.01%   |
| Network                  | 1         | 1.01%   |
| Communication controller | 1         | 1.01%   |
| Card reader              | 1         | 1.01%   |
| Bluetooth                | 1         | 1.01%   |

