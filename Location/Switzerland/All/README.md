Linux in Switzerland - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Switzerland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Switzerland/Desktop/README.md) and [notebooks](/Location/Switzerland/Notebook/README.md).

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

Total: 3793

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv3                | Notebook    | [351a45926e](https://linux-hardware.org/?probe=351a45926e) | Jan 02, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a3d3e92cce](https://linux-hardware.org/?probe=a3d3e92cce) | Jan 01, 2024 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [4e8ac17eb6](https://linux-hardware.org/?probe=4e8ac17eb6) | Dec 31, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [96395212e8](https://linux-hardware.org/?probe=96395212e8) | Dec 31, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [12c41e6a5f](https://linux-hardware.org/?probe=12c41e6a5f) | Dec 31, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [c0381749ea](https://linux-hardware.org/?probe=c0381749ea) | Dec 31, 2023 |
| HP            | 8918                        | Desktop     | [0e8d4a626d](https://linux-hardware.org/?probe=0e8d4a626d) | Dec 31, 2023 |
| Dell          | Latitude 5480               | Notebook    | [cf678e4c6d](https://linux-hardware.org/?probe=cf678e4c6d) | Dec 31, 2023 |
| Microsoft     | Surface Book 2              | Tablet      | [4351871367](https://linux-hardware.org/?probe=4351871367) | Dec 30, 2023 |
| Dell          | Latitude 5480               | Notebook    | [a1bc8df9e4](https://linux-hardware.org/?probe=a1bc8df9e4) | Dec 30, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [76f94ce16a](https://linux-hardware.org/?probe=76f94ce16a) | Dec 29, 2023 |
| Lenovo        | ThinkPad L390 20NSS29K00    | Notebook    | [a0860fbefb](https://linux-hardware.org/?probe=a0860fbefb) | Dec 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | Notebook    | [a135119148](https://linux-hardware.org/?probe=a135119148) | Dec 28, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [76305a2c98](https://linux-hardware.org/?probe=76305a2c98) | Dec 28, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [2a36715319](https://linux-hardware.org/?probe=2a36715319) | Dec 28, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [a271d8355d](https://linux-hardware.org/?probe=a271d8355d) | Dec 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ee7b7ce7cc](https://linux-hardware.org/?probe=ee7b7ce7cc) | Dec 24, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [fd17cc0e66](https://linux-hardware.org/?probe=fd17cc0e66) | Dec 23, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | Notebook    | [dbfd9ef700](https://linux-hardware.org/?probe=dbfd9ef700) | Dec 22, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [5e8dc79e2c](https://linux-hardware.org/?probe=5e8dc79e2c) | Dec 22, 2023 |
| HP            | Spectre x360 Laptop 14-e... | Convertible | [f3bc7a2912](https://linux-hardware.org/?probe=f3bc7a2912) | Dec 22, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [9109738b7f](https://linux-hardware.org/?probe=9109738b7f) | Dec 22, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [4017c676bf](https://linux-hardware.org/?probe=4017c676bf) | Dec 22, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [3e49a75ff4](https://linux-hardware.org/?probe=3e49a75ff4) | Dec 22, 2023 |
| Lenovo        | 3731 SDK0J40697 WIN 3305... | Desktop     | [090681a459](https://linux-hardware.org/?probe=090681a459) | Dec 22, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [1b860f6465](https://linux-hardware.org/?probe=1b860f6465) | Dec 21, 2023 |
| HP            | Compaq 15                   | Notebook    | [e97b5e227e](https://linux-hardware.org/?probe=e97b5e227e) | Dec 21, 2023 |
| Acer          | Aspire 6930G                | Notebook    | [3013bf91cd](https://linux-hardware.org/?probe=3013bf91cd) | Dec 20, 2023 |
| Acer          | Aspire 6930G                | Notebook    | [6bc25073be](https://linux-hardware.org/?probe=6bc25073be) | Dec 20, 2023 |
| HP            | Compaq 15                   | Notebook    | [8224a8ab3d](https://linux-hardware.org/?probe=8224a8ab3d) | Dec 20, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [17ce825521](https://linux-hardware.org/?probe=17ce825521) | Dec 20, 2023 |
| HP            | Spectre x360 Laptop 14-e... | Convertible | [a1957f79c1](https://linux-hardware.org/?probe=a1957f79c1) | Dec 20, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [176468573a](https://linux-hardware.org/?probe=176468573a) | Dec 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | Notebook    | [85531f6788](https://linux-hardware.org/?probe=85531f6788) | Dec 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | Notebook    | [4715b83a8c](https://linux-hardware.org/?probe=4715b83a8c) | Dec 19, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [79499893b8](https://linux-hardware.org/?probe=79499893b8) | Dec 19, 2023 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [ebf90075c5](https://linux-hardware.org/?probe=ebf90075c5) | Dec 18, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7c88ff72d7](https://linux-hardware.org/?probe=7c88ff72d7) | Dec 18, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6533a19479](https://linux-hardware.org/?probe=6533a19479) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [45a0b94112](https://linux-hardware.org/?probe=45a0b94112) | Dec 18, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [4802066fc1](https://linux-hardware.org/?probe=4802066fc1) | Dec 17, 2023 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | Notebook    | [6ac6a904be](https://linux-hardware.org/?probe=6ac6a904be) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VI... | Notebook    | [5a439f3bc5](https://linux-hardware.org/?probe=5a439f3bc5) | Dec 17, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [8143805d8a](https://linux-hardware.org/?probe=8143805d8a) | Dec 17, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [f8cfc75a8a](https://linux-hardware.org/?probe=f8cfc75a8a) | Dec 17, 2023 |
| HP            | ProBook 455 G2              | Notebook    | [4935ac1297](https://linux-hardware.org/?probe=4935ac1297) | Dec 17, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [f0ed04c975](https://linux-hardware.org/?probe=f0ed04c975) | Dec 16, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [c35aa056cf](https://linux-hardware.org/?probe=c35aa056cf) | Dec 16, 2023 |
| Shenzhen M... | F7BSD                       | Mini pc     | [10527fec61](https://linux-hardware.org/?probe=10527fec61) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | Desktop     | [f3938de13a](https://linux-hardware.org/?probe=f3938de13a) | Dec 16, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [c9de3b068b](https://linux-hardware.org/?probe=c9de3b068b) | Dec 15, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [a785d6574b](https://linux-hardware.org/?probe=a785d6574b) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [42b02a9d8e](https://linux-hardware.org/?probe=42b02a9d8e) | Dec 14, 2023 |
| Lenovo        | 3731 SDK0J40697 WIN 3305... | Desktop     | [71e69ec2bd](https://linux-hardware.org/?probe=71e69ec2bd) | Dec 14, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [7f788f5265](https://linux-hardware.org/?probe=7f788f5265) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480 20L50004MX    | Notebook    | [691f1ae82f](https://linux-hardware.org/?probe=691f1ae82f) | Dec 13, 2023 |
| Lenovo        | ThinkPad E560 20EV000SMZ    | Notebook    | [13b8795a4e](https://linux-hardware.org/?probe=13b8795a4e) | Dec 13, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e70de29c90](https://linux-hardware.org/?probe=e70de29c90) | Dec 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [f845d7a88e](https://linux-hardware.org/?probe=f845d7a88e) | Dec 13, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [149a7f254a](https://linux-hardware.org/?probe=149a7f254a) | Dec 13, 2023 |
| Lenovo        | ThinkPad E560 20EV000SMZ    | Notebook    | [1bb8694fda](https://linux-hardware.org/?probe=1bb8694fda) | Dec 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | Notebook    | [e99a0bd1db](https://linux-hardware.org/?probe=e99a0bd1db) | Dec 12, 2023 |
| HP            | Notebook                    | Notebook    | [972e86b7cf](https://linux-hardware.org/?probe=972e86b7cf) | Dec 12, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [d5cb60727d](https://linux-hardware.org/?probe=d5cb60727d) | Dec 12, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [c05cd1b8c9](https://linux-hardware.org/?probe=c05cd1b8c9) | Dec 12, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [e340ad2e3a](https://linux-hardware.org/?probe=e340ad2e3a) | Dec 12, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [350f7fc217](https://linux-hardware.org/?probe=350f7fc217) | Dec 10, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [ec970d7248](https://linux-hardware.org/?probe=ec970d7248) | Dec 10, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [11def2bc79](https://linux-hardware.org/?probe=11def2bc79) | Dec 10, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Notebook    | [9f6ce5cca9](https://linux-hardware.org/?probe=9f6ce5cca9) | Dec 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [a0670e0719](https://linux-hardware.org/?probe=a0670e0719) | Dec 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [3ffa0f12b7](https://linux-hardware.org/?probe=3ffa0f12b7) | Dec 08, 2023 |
| Toshiba       | Satellite L50-A-19P         | Notebook    | [cd3314169e](https://linux-hardware.org/?probe=cd3314169e) | Dec 08, 2023 |
| MSI           | MEG X399 CREATION           | Desktop     | [02adc5ef8b](https://linux-hardware.org/?probe=02adc5ef8b) | Dec 08, 2023 |
| Dell          | XPS 9320                    | Notebook    | [60c734eb9c](https://linux-hardware.org/?probe=60c734eb9c) | Dec 08, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [12186f9887](https://linux-hardware.org/?probe=12186f9887) | Dec 07, 2023 |
| Lenovo        | ThinkPad T440 20B7S0N10F    | Notebook    | [350da642e5](https://linux-hardware.org/?probe=350da642e5) | Dec 07, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VI... | Notebook    | [a7bb755e20](https://linux-hardware.org/?probe=a7bb755e20) | Dec 06, 2023 |
| HP            | ENVY 17                     | Notebook    | [b6048f107e](https://linux-hardware.org/?probe=b6048f107e) | Dec 06, 2023 |
| HP            | 2AF7                        | Desktop     | [4d98ac755f](https://linux-hardware.org/?probe=4d98ac755f) | Dec 06, 2023 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [8ed8e8f644](https://linux-hardware.org/?probe=8ed8e8f644) | Dec 05, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [8167f60069](https://linux-hardware.org/?probe=8167f60069) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | Desktop     | [31b3b0fd94](https://linux-hardware.org/?probe=31b3b0fd94) | Dec 05, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [8132e0caf0](https://linux-hardware.org/?probe=8132e0caf0) | Dec 04, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [0184d32d26](https://linux-hardware.org/?probe=0184d32d26) | Dec 04, 2023 |
| Shuttle       | DS10U                       | Desktop     | [4e3fa0f845](https://linux-hardware.org/?probe=4e3fa0f845) | Dec 02, 2023 |
| Polaroid      | MP1464PR001                 | Notebook    | [bd3fa27cfe](https://linux-hardware.org/?probe=bd3fa27cfe) | Dec 02, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VI... | Notebook    | [b127bbd876](https://linux-hardware.org/?probe=b127bbd876) | Dec 01, 2023 |
| HP            | 3398                        | Desktop     | [26c9b1fa25](https://linux-hardware.org/?probe=26c9b1fa25) | Dec 01, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [0338afa4db](https://linux-hardware.org/?probe=0338afa4db) | Dec 01, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | Desktop     | [8a625099b1](https://linux-hardware.org/?probe=8a625099b1) | Dec 01, 2023 |
| Medion        | Erazer P7643 MD60133        | Notebook    | [65f090fe28](https://linux-hardware.org/?probe=65f090fe28) | Nov 28, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [364235417e](https://linux-hardware.org/?probe=364235417e) | Nov 28, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [bbfe8e99fc](https://linux-hardware.org/?probe=bbfe8e99fc) | Nov 28, 2023 |
| Sony          | VPCF13M1E                   | Notebook    | [4a6e054f68](https://linux-hardware.org/?probe=4a6e054f68) | Nov 28, 2023 |
| Sony          | VPCSB1Z9E                   | Notebook    | [4eed6bb4ef](https://linux-hardware.org/?probe=4eed6bb4ef) | Nov 28, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [ada466b7a0](https://linux-hardware.org/?probe=ada466b7a0) | Nov 27, 2023 |
| HP            | 2B36                        | Desktop     | [3e8b681ec7](https://linux-hardware.org/?probe=3e8b681ec7) | Nov 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [ade10d9872](https://linux-hardware.org/?probe=ade10d9872) | Nov 27, 2023 |
| Acer          | Aspire S5-371               | Notebook    | [d3efa32b61](https://linux-hardware.org/?probe=d3efa32b61) | Nov 26, 2023 |
| Dell          | Precision M6700             | Notebook    | [1817097d25](https://linux-hardware.org/?probe=1817097d25) | Nov 25, 2023 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | Notebook    | [a58a5557e6](https://linux-hardware.org/?probe=a58a5557e6) | Nov 24, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [2e5bce2d86](https://linux-hardware.org/?probe=2e5bce2d86) | Nov 24, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [268acfb942](https://linux-hardware.org/?probe=268acfb942) | Nov 24, 2023 |
| Lenovo        | Legion 9 16IRX8 83AG        | Notebook    | [f511dac11e](https://linux-hardware.org/?probe=f511dac11e) | Nov 24, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [b11d29c96b](https://linux-hardware.org/?probe=b11d29c96b) | Nov 24, 2023 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | Notebook    | [7cd9c24a07](https://linux-hardware.org/?probe=7cd9c24a07) | Nov 23, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [49ec5aa905](https://linux-hardware.org/?probe=49ec5aa905) | Nov 23, 2023 |
| ASUSTek       | Q87T                        | Desktop     | [9f4fa65adc](https://linux-hardware.org/?probe=9f4fa65adc) | Nov 23, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [c5a84018e9](https://linux-hardware.org/?probe=c5a84018e9) | Nov 23, 2023 |
| ASUSTek       | Q87T                        | Desktop     | [2b57cf5c8e](https://linux-hardware.org/?probe=2b57cf5c8e) | Nov 23, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [4929f843b8](https://linux-hardware.org/?probe=4929f843b8) | Nov 22, 2023 |
| Dell          | Latitude 5280               | Notebook    | [c2d1b79aeb](https://linux-hardware.org/?probe=c2d1b79aeb) | Nov 22, 2023 |
| HP            | EliteBook Folio 1020 G1     | Notebook    | [022f885fe9](https://linux-hardware.org/?probe=022f885fe9) | Nov 22, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [f1adb28e44](https://linux-hardware.org/?probe=f1adb28e44) | Nov 21, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | Desktop     | [c69c8e4cbd](https://linux-hardware.org/?probe=c69c8e4cbd) | Nov 21, 2023 |
| Lenovo        | 32E4 SDK0T76538 WIN 3556... | Mini pc     | [ee9366dce5](https://linux-hardware.org/?probe=ee9366dce5) | Nov 21, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [700d0d389d](https://linux-hardware.org/?probe=700d0d389d) | Nov 21, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [1a76ee51c6](https://linux-hardware.org/?probe=1a76ee51c6) | Nov 21, 2023 |
| Lenovo        | ThinkPad T490s 20NY000JM... | Notebook    | [a8668f58d9](https://linux-hardware.org/?probe=a8668f58d9) | Nov 21, 2023 |
| Medion        | S1219T MD99667              | Tablet      | [21166d1dc5](https://linux-hardware.org/?probe=21166d1dc5) | Nov 20, 2023 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | Notebook    | [b7e16888b9](https://linux-hardware.org/?probe=b7e16888b9) | Nov 20, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [6ef90e528f](https://linux-hardware.org/?probe=6ef90e528f) | Nov 20, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f3a2125fad](https://linux-hardware.org/?probe=f3a2125fad) | Nov 20, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [9065a31617](https://linux-hardware.org/?probe=9065a31617) | Nov 20, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [4949cbc96a](https://linux-hardware.org/?probe=4949cbc96a) | Nov 19, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [36ce4210e3](https://linux-hardware.org/?probe=36ce4210e3) | Nov 19, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [cc1d17df2e](https://linux-hardware.org/?probe=cc1d17df2e) | Nov 19, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [65f7027c84](https://linux-hardware.org/?probe=65f7027c84) | Nov 19, 2023 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [674a7d1154](https://linux-hardware.org/?probe=674a7d1154) | Nov 18, 2023 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [34b83fef89](https://linux-hardware.org/?probe=34b83fef89) | Nov 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5fa3bbac39](https://linux-hardware.org/?probe=5fa3bbac39) | Nov 17, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e71f4dcdb1](https://linux-hardware.org/?probe=e71f4dcdb1) | Nov 17, 2023 |
| Lenovo        | ThinkPad Edge E535 32605... | Notebook    | [a42aa89d19](https://linux-hardware.org/?probe=a42aa89d19) | Nov 16, 2023 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [a9704992fa](https://linux-hardware.org/?probe=a9704992fa) | Nov 16, 2023 |
| ASUSTek       | X705UAR                     | Notebook    | [11e3d24283](https://linux-hardware.org/?probe=11e3d24283) | Nov 15, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [527e45b73b](https://linux-hardware.org/?probe=527e45b73b) | Nov 15, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [311c405672](https://linux-hardware.org/?probe=311c405672) | Nov 15, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [bceb77e476](https://linux-hardware.org/?probe=bceb77e476) | Nov 15, 2023 |
| HP            | 8918                        | Desktop     | [f1051351c4](https://linux-hardware.org/?probe=f1051351c4) | Nov 14, 2023 |
| ASRock        | Z790 PG-ITX/TB4             | Desktop     | [6a8fa4e046](https://linux-hardware.org/?probe=6a8fa4e046) | Nov 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [276c70f8ef](https://linux-hardware.org/?probe=276c70f8ef) | Nov 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [43edc485b1](https://linux-hardware.org/?probe=43edc485b1) | Nov 14, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [6dbb14b567](https://linux-hardware.org/?probe=6dbb14b567) | Nov 14, 2023 |
| Dell          | 0YNVJG A02                  | Desktop     | [7c23854d23](https://linux-hardware.org/?probe=7c23854d23) | Nov 14, 2023 |
| Dell          | 0YNVJG A02                  | Desktop     | [a641eb99bf](https://linux-hardware.org/?probe=a641eb99bf) | Nov 14, 2023 |
| Sony          | SVF13N1L2ES                 | Notebook    | [e0b7ae1d8a](https://linux-hardware.org/?probe=e0b7ae1d8a) | Nov 14, 2023 |
| Sony          | SVF13N1L2ES                 | Notebook    | [1fe409a47f](https://linux-hardware.org/?probe=1fe409a47f) | Nov 14, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [06a66f2bd2](https://linux-hardware.org/?probe=06a66f2bd2) | Nov 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c538f19c9e](https://linux-hardware.org/?probe=c538f19c9e) | Nov 13, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [2bc7d7c816](https://linux-hardware.org/?probe=2bc7d7c816) | Nov 13, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [9cdba3ee40](https://linux-hardware.org/?probe=9cdba3ee40) | Nov 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [222817ca6c](https://linux-hardware.org/?probe=222817ca6c) | Nov 11, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [bac4e43eff](https://linux-hardware.org/?probe=bac4e43eff) | Nov 11, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [59c09c7be1](https://linux-hardware.org/?probe=59c09c7be1) | Nov 11, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [4c87f0ac2c](https://linux-hardware.org/?probe=4c87f0ac2c) | Nov 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [3cad0a5b88](https://linux-hardware.org/?probe=3cad0a5b88) | Nov 10, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e8ad5598b6](https://linux-hardware.org/?probe=e8ad5598b6) | Nov 10, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [20e8acea87](https://linux-hardware.org/?probe=20e8acea87) | Nov 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [51f2c3af2f](https://linux-hardware.org/?probe=51f2c3af2f) | Nov 09, 2023 |
| HP            | 8918                        | Desktop     | [78d4c02ff8](https://linux-hardware.org/?probe=78d4c02ff8) | Nov 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [ca05263192](https://linux-hardware.org/?probe=ca05263192) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [92e6aea0e6](https://linux-hardware.org/?probe=92e6aea0e6) | Nov 07, 2023 |
| Medion        | Crawler E25                 | Notebook    | [945026c1b8](https://linux-hardware.org/?probe=945026c1b8) | Nov 07, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [4075eda03c](https://linux-hardware.org/?probe=4075eda03c) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [4303ca052b](https://linux-hardware.org/?probe=4303ca052b) | Nov 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [d63435f6d0](https://linux-hardware.org/?probe=d63435f6d0) | Nov 06, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [e2d5b50ae3](https://linux-hardware.org/?probe=e2d5b50ae3) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d61e270082](https://linux-hardware.org/?probe=d61e270082) | Nov 06, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [e6c695d4a7](https://linux-hardware.org/?probe=e6c695d4a7) | Nov 05, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [01e74da42d](https://linux-hardware.org/?probe=01e74da42d) | Nov 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [8efb96e5d7](https://linux-hardware.org/?probe=8efb96e5d7) | Nov 04, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [e6459bb42f](https://linux-hardware.org/?probe=e6459bb42f) | Nov 04, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [36646aca12](https://linux-hardware.org/?probe=36646aca12) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [97e043115e](https://linux-hardware.org/?probe=97e043115e) | Nov 04, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [05304710e4](https://linux-hardware.org/?probe=05304710e4) | Nov 03, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [62f85af4b5](https://linux-hardware.org/?probe=62f85af4b5) | Nov 03, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [792c22d04f](https://linux-hardware.org/?probe=792c22d04f) | Nov 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [7a6f17c843](https://linux-hardware.org/?probe=7a6f17c843) | Nov 03, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [ee12470303](https://linux-hardware.org/?probe=ee12470303) | Nov 03, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [f446da83f1](https://linux-hardware.org/?probe=f446da83f1) | Nov 03, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d371b7299d](https://linux-hardware.org/?probe=d371b7299d) | Nov 02, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [04f3946d05](https://linux-hardware.org/?probe=04f3946d05) | Nov 02, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [493dcbc1f8](https://linux-hardware.org/?probe=493dcbc1f8) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8c2a216d7b](https://linux-hardware.org/?probe=8c2a216d7b) | Nov 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [6cce294b99](https://linux-hardware.org/?probe=6cce294b99) | Nov 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [c985fdb0b7](https://linux-hardware.org/?probe=c985fdb0b7) | Nov 01, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [3479b99099](https://linux-hardware.org/?probe=3479b99099) | Nov 01, 2023 |
| Acer          | Predator PH18-71            | Notebook    | [a0393f21c9](https://linux-hardware.org/?probe=a0393f21c9) | Nov 01, 2023 |
| LG Electro... | 16T90R-K.ADB9U1             | Convertible | [e9f8c192f1](https://linux-hardware.org/?probe=e9f8c192f1) | Nov 01, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [df43f845a1](https://linux-hardware.org/?probe=df43f845a1) | Oct 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [924f7f81ce](https://linux-hardware.org/?probe=924f7f81ce) | Oct 30, 2023 |
| Biostar       | H61MHV2                     | Desktop     | [e8472e117d](https://linux-hardware.org/?probe=e8472e117d) | Oct 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | Notebook    | [448c3ca446](https://linux-hardware.org/?probe=448c3ca446) | Oct 30, 2023 |
| HP            | ENVY 17                     | Notebook    | [8852bab8c1](https://linux-hardware.org/?probe=8852bab8c1) | Oct 29, 2023 |
| HP            | 8918                        | Desktop     | [12336ce9fe](https://linux-hardware.org/?probe=12336ce9fe) | Oct 28, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [53cddb0f34](https://linux-hardware.org/?probe=53cddb0f34) | Oct 28, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [effde383d8](https://linux-hardware.org/?probe=effde383d8) | Oct 28, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [d48a91cce4](https://linux-hardware.org/?probe=d48a91cce4) | Oct 28, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [33d021b931](https://linux-hardware.org/?probe=33d021b931) | Oct 28, 2023 |
| HP            | ENVY 17                     | Notebook    | [aaa99aaa53](https://linux-hardware.org/?probe=aaa99aaa53) | Oct 27, 2023 |
| Notebook      | V1x0PNPx                    | Notebook    | [f1e27c662a](https://linux-hardware.org/?probe=f1e27c662a) | Oct 27, 2023 |
| System76      | Darter Pro                  | Notebook    | [9dcbc85a23](https://linux-hardware.org/?probe=9dcbc85a23) | Oct 27, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [7ac5ac2ae2](https://linux-hardware.org/?probe=7ac5ac2ae2) | Oct 27, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [4506629e6a](https://linux-hardware.org/?probe=4506629e6a) | Oct 26, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [b90fafd403](https://linux-hardware.org/?probe=b90fafd403) | Oct 25, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [e2f4e41023](https://linux-hardware.org/?probe=e2f4e41023) | Oct 25, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [39e846913d](https://linux-hardware.org/?probe=39e846913d) | Oct 25, 2023 |
| Unknown       | 1.1                         | Desktop     | [4a673ae7d0](https://linux-hardware.org/?probe=4a673ae7d0) | Oct 24, 2023 |
| Unknown       | 1.1                         | Desktop     | [c006e77646](https://linux-hardware.org/?probe=c006e77646) | Oct 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | Notebook    | [1406d2f4d5](https://linux-hardware.org/?probe=1406d2f4d5) | Oct 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | Notebook    | [56fa067caa](https://linux-hardware.org/?probe=56fa067caa) | Oct 24, 2023 |
| Dell          | Latitude 5520               | Notebook    | [0c8da2f95a](https://linux-hardware.org/?probe=0c8da2f95a) | Oct 24, 2023 |
| Lenovo        | 30C7 SDK0J40709 WIN 3259... | Desktop     | [71fd7dde1d](https://linux-hardware.org/?probe=71fd7dde1d) | Oct 23, 2023 |
| HP            | 3397                        | Desktop     | [3f8e8810c1](https://linux-hardware.org/?probe=3f8e8810c1) | Oct 23, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6ef86fc1b9](https://linux-hardware.org/?probe=6ef86fc1b9) | Oct 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [557e6a2f27](https://linux-hardware.org/?probe=557e6a2f27) | Oct 21, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [20f6750372](https://linux-hardware.org/?probe=20f6750372) | Oct 21, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [2f7b2cf78e](https://linux-hardware.org/?probe=2f7b2cf78e) | Oct 20, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b7e0b6aac3](https://linux-hardware.org/?probe=b7e0b6aac3) | Oct 19, 2023 |
| Dell          | Latitude E6530              | Notebook    | [e3126b26df](https://linux-hardware.org/?probe=e3126b26df) | Oct 19, 2023 |
| HP            | 0A68h                       | Desktop     | [376c3156a9](https://linux-hardware.org/?probe=376c3156a9) | Oct 19, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [cf4c60a0a8](https://linux-hardware.org/?probe=cf4c60a0a8) | Oct 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [e794aa4113](https://linux-hardware.org/?probe=e794aa4113) | Oct 18, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [fc8b87bfe0](https://linux-hardware.org/?probe=fc8b87bfe0) | Oct 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [cf522294f8](https://linux-hardware.org/?probe=cf522294f8) | Oct 18, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [b6b4b14ba1](https://linux-hardware.org/?probe=b6b4b14ba1) | Oct 18, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [5810a2ef0a](https://linux-hardware.org/?probe=5810a2ef0a) | Oct 17, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [ad07e33f54](https://linux-hardware.org/?probe=ad07e33f54) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [7f5a3b8e10](https://linux-hardware.org/?probe=7f5a3b8e10) | Oct 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [2a5d18299e](https://linux-hardware.org/?probe=2a5d18299e) | Oct 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [b593a4511e](https://linux-hardware.org/?probe=b593a4511e) | Oct 13, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [df89a7b20b](https://linux-hardware.org/?probe=df89a7b20b) | Oct 12, 2023 |
| HP            | Unknown                     | Convertible | [8fe4fae90f](https://linux-hardware.org/?probe=8fe4fae90f) | Oct 12, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [4bb651a7a6](https://linux-hardware.org/?probe=4bb651a7a6) | Oct 11, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [52bbb0243a](https://linux-hardware.org/?probe=52bbb0243a) | Oct 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [9ff3f35842](https://linux-hardware.org/?probe=9ff3f35842) | Oct 11, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [8ad88c7253](https://linux-hardware.org/?probe=8ad88c7253) | Oct 11, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [89748db0f1](https://linux-hardware.org/?probe=89748db0f1) | Oct 10, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [00f69fbe6c](https://linux-hardware.org/?probe=00f69fbe6c) | Oct 10, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [c98952b2ee](https://linux-hardware.org/?probe=c98952b2ee) | Oct 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [8dcc2d1ec2](https://linux-hardware.org/?probe=8dcc2d1ec2) | Oct 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [edd7c9e07a](https://linux-hardware.org/?probe=edd7c9e07a) | Oct 09, 2023 |
| HP            | 2187 A01                    | Desktop     | [8d63ab7986](https://linux-hardware.org/?probe=8d63ab7986) | Oct 09, 2023 |
| HP            | Pavilion 15                 | Notebook    | [0c8f955052](https://linux-hardware.org/?probe=0c8f955052) | Oct 08, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [7eb13e7645](https://linux-hardware.org/?probe=7eb13e7645) | Oct 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [dae43772d4](https://linux-hardware.org/?probe=dae43772d4) | Oct 08, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [1996d5a1ff](https://linux-hardware.org/?probe=1996d5a1ff) | Oct 08, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [ade2b406fd](https://linux-hardware.org/?probe=ade2b406fd) | Oct 07, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [86f56798dc](https://linux-hardware.org/?probe=86f56798dc) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9d8e06a9bf](https://linux-hardware.org/?probe=9d8e06a9bf) | Oct 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | Notebook    | [0354977d6c](https://linux-hardware.org/?probe=0354977d6c) | Oct 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [faea5bdeba](https://linux-hardware.org/?probe=faea5bdeba) | Oct 07, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [27ce5f6a61](https://linux-hardware.org/?probe=27ce5f6a61) | Oct 06, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [6347be6a54](https://linux-hardware.org/?probe=6347be6a54) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a308ec4180](https://linux-hardware.org/?probe=a308ec4180) | Oct 06, 2023 |
| HP            | Unknown                     | Convertible | [46bfa371c4](https://linux-hardware.org/?probe=46bfa371c4) | Oct 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [7eec2f8e4e](https://linux-hardware.org/?probe=7eec2f8e4e) | Oct 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [a80bc8f591](https://linux-hardware.org/?probe=a80bc8f591) | Oct 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6f6e394cdf](https://linux-hardware.org/?probe=6f6e394cdf) | Oct 05, 2023 |
| ASUSTek       | H87I-PLUS                   | Desktop     | [34c7858d89](https://linux-hardware.org/?probe=34c7858d89) | Oct 04, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [8d69a9df41](https://linux-hardware.org/?probe=8d69a9df41) | Oct 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [3fdbdfe773](https://linux-hardware.org/?probe=3fdbdfe773) | Oct 03, 2023 |
| Acer          | Swift SFE16-43              | Notebook    | [54231f7059](https://linux-hardware.org/?probe=54231f7059) | Oct 02, 2023 |
| Acer          | Swift SFE16-43              | Notebook    | [045606333c](https://linux-hardware.org/?probe=045606333c) | Oct 02, 2023 |
| Fujitsu       | STYLISTIC R726              | Notebook    | [a4c3a19501](https://linux-hardware.org/?probe=a4c3a19501) | Oct 02, 2023 |
| Lenovo        | V15 G4 IRU 83A1             | Notebook    | [c71241f73d](https://linux-hardware.org/?probe=c71241f73d) | Oct 01, 2023 |
| Lenovo        | V15 G4 IRU 83A1             | Notebook    | [b1af5494c8](https://linux-hardware.org/?probe=b1af5494c8) | Oct 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [34e5bf82de](https://linux-hardware.org/?probe=34e5bf82de) | Sep 30, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [d8c97108ad](https://linux-hardware.org/?probe=d8c97108ad) | Sep 30, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [bcbf0e5bfd](https://linux-hardware.org/?probe=bcbf0e5bfd) | Sep 30, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [caa5ce0b99](https://linux-hardware.org/?probe=caa5ce0b99) | Sep 29, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [725f1e5b25](https://linux-hardware.org/?probe=725f1e5b25) | Sep 29, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | Notebook    | [6d981e4890](https://linux-hardware.org/?probe=6d981e4890) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [47a0a8627c](https://linux-hardware.org/?probe=47a0a8627c) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3fcfddc8e9](https://linux-hardware.org/?probe=3fcfddc8e9) | Sep 27, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [af863ee3d6](https://linux-hardware.org/?probe=af863ee3d6) | Sep 27, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [e8397f6d0a](https://linux-hardware.org/?probe=e8397f6d0a) | Sep 26, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [5351027f5e](https://linux-hardware.org/?probe=5351027f5e) | Sep 25, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | Notebook    | [a34763914d](https://linux-hardware.org/?probe=a34763914d) | Sep 23, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f2bb4ee9f0](https://linux-hardware.org/?probe=f2bb4ee9f0) | Sep 23, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [f1721712f2](https://linux-hardware.org/?probe=f1721712f2) | Sep 22, 2023 |
| Gigabyte      | P55-UD4                     | Desktop     | [16f768ab94](https://linux-hardware.org/?probe=16f768ab94) | Sep 21, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [34d899f825](https://linux-hardware.org/?probe=34d899f825) | Sep 21, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [8b39e51416](https://linux-hardware.org/?probe=8b39e51416) | Sep 21, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [b1fd4a61ae](https://linux-hardware.org/?probe=b1fd4a61ae) | Sep 21, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [389282109e](https://linux-hardware.org/?probe=389282109e) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ae7455bac3](https://linux-hardware.org/?probe=ae7455bac3) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [6337af2f4c](https://linux-hardware.org/?probe=6337af2f4c) | Sep 20, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [e04968b0ab](https://linux-hardware.org/?probe=e04968b0ab) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [16c09be7f2](https://linux-hardware.org/?probe=16c09be7f2) | Sep 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [16f80f70a8](https://linux-hardware.org/?probe=16f80f70a8) | Sep 19, 2023 |
| Lenovo        | ThinkPad X61s 7666Y2X       | Notebook    | [177e40808d](https://linux-hardware.org/?probe=177e40808d) | Sep 19, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [49963f0f8a](https://linux-hardware.org/?probe=49963f0f8a) | Sep 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [06d67bab4a](https://linux-hardware.org/?probe=06d67bab4a) | Sep 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [0c21583146](https://linux-hardware.org/?probe=0c21583146) | Sep 17, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2b66c2969e](https://linux-hardware.org/?probe=2b66c2969e) | Sep 17, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [5a9f4e8791](https://linux-hardware.org/?probe=5a9f4e8791) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | Notebook    | [93d01648a0](https://linux-hardware.org/?probe=93d01648a0) | Sep 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1f152eb6fa](https://linux-hardware.org/?probe=1f152eb6fa) | Sep 17, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [38a985d781](https://linux-hardware.org/?probe=38a985d781) | Sep 16, 2023 |
| JINGSHA       | X99-D8I                     | Desktop     | [2865a9b1e6](https://linux-hardware.org/?probe=2865a9b1e6) | Sep 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [1b8a46fc57](https://linux-hardware.org/?probe=1b8a46fc57) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1400ef978f](https://linux-hardware.org/?probe=1400ef978f) | Sep 12, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [6b9804a536](https://linux-hardware.org/?probe=6b9804a536) | Sep 10, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [86f844f512](https://linux-hardware.org/?probe=86f844f512) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | Desktop     | [0562141e37](https://linux-hardware.org/?probe=0562141e37) | Sep 10, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [d824341957](https://linux-hardware.org/?probe=d824341957) | Sep 10, 2023 |
| Olivetti      | OLIBOOK PX5-XXXAES          | Notebook    | [70225c18e1](https://linux-hardware.org/?probe=70225c18e1) | Sep 10, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [bb0f6ff00d](https://linux-hardware.org/?probe=bb0f6ff00d) | Sep 09, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [4a63a68d47](https://linux-hardware.org/?probe=4a63a68d47) | Sep 09, 2023 |
| Microsoft     | Surface Laptop 2            | Tablet      | [e74f5bd967](https://linux-hardware.org/?probe=e74f5bd967) | Sep 09, 2023 |
| HP            | 2B36                        | Desktop     | [20552523c6](https://linux-hardware.org/?probe=20552523c6) | Sep 08, 2023 |
| HP            | 2B36                        | Desktop     | [7697b6ff27](https://linux-hardware.org/?probe=7697b6ff27) | Sep 08, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [86ea72cfeb](https://linux-hardware.org/?probe=86ea72cfeb) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [0de4c341fa](https://linux-hardware.org/?probe=0de4c341fa) | Sep 07, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [d3996a81e2](https://linux-hardware.org/?probe=d3996a81e2) | Sep 07, 2023 |
| HP            | 2B3C                        | Desktop     | [471f0f283b](https://linux-hardware.org/?probe=471f0f283b) | Sep 06, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | Notebook    | [b884752710](https://linux-hardware.org/?probe=b884752710) | Sep 06, 2023 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [1056a6ebb4](https://linux-hardware.org/?probe=1056a6ebb4) | Sep 06, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [051fefc7ca](https://linux-hardware.org/?probe=051fefc7ca) | Sep 05, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [a28608cf93](https://linux-hardware.org/?probe=a28608cf93) | Sep 04, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [ce450a1a6e](https://linux-hardware.org/?probe=ce450a1a6e) | Sep 03, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [e446721809](https://linux-hardware.org/?probe=e446721809) | Sep 02, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [aab4c37d85](https://linux-hardware.org/?probe=aab4c37d85) | Sep 02, 2023 |
| HP            | Compaq 15                   | Notebook    | [2d0b51ccd5](https://linux-hardware.org/?probe=2d0b51ccd5) | Sep 01, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [25b3fed672](https://linux-hardware.org/?probe=25b3fed672) | Aug 31, 2023 |
| Lenovo        | ThinkPad X200 7458AL7       | Notebook    | [763d0f46f4](https://linux-hardware.org/?probe=763d0f46f4) | Aug 31, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [1c5a7bba51](https://linux-hardware.org/?probe=1c5a7bba51) | Aug 31, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [48fe841736](https://linux-hardware.org/?probe=48fe841736) | Aug 30, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3f2dec6262](https://linux-hardware.org/?probe=3f2dec6262) | Aug 30, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [ca4ddb2663](https://linux-hardware.org/?probe=ca4ddb2663) | Aug 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [176ad353fa](https://linux-hardware.org/?probe=176ad353fa) | Aug 29, 2023 |
| HP            | 8953                        | Desktop     | [7f0a271e35](https://linux-hardware.org/?probe=7f0a271e35) | Aug 29, 2023 |
| HP            | 82A2                        | Desktop     | [44e0a72dad](https://linux-hardware.org/?probe=44e0a72dad) | Aug 28, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [fe9f235c26](https://linux-hardware.org/?probe=fe9f235c26) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [efc8be8369](https://linux-hardware.org/?probe=efc8be8369) | Aug 28, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [d238cd036a](https://linux-hardware.org/?probe=d238cd036a) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [492a021411](https://linux-hardware.org/?probe=492a021411) | Aug 27, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [0f05e92358](https://linux-hardware.org/?probe=0f05e92358) | Aug 27, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [248f2a9745](https://linux-hardware.org/?probe=248f2a9745) | Aug 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d76b06bfd3](https://linux-hardware.org/?probe=d76b06bfd3) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [c1bea53459](https://linux-hardware.org/?probe=c1bea53459) | Aug 27, 2023 |
| ASUSTek       | M3N WS                      | Desktop     | [da41c8a755](https://linux-hardware.org/?probe=da41c8a755) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [14805d08fd](https://linux-hardware.org/?probe=14805d08fd) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [f4af40c36f](https://linux-hardware.org/?probe=f4af40c36f) | Aug 24, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [08efa3dcf3](https://linux-hardware.org/?probe=08efa3dcf3) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [131e36d487](https://linux-hardware.org/?probe=131e36d487) | Aug 22, 2023 |
| Gigabyte      | MZA2-CE0-00 02010201        | Server      | [853b026197](https://linux-hardware.org/?probe=853b026197) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [f280fd203e](https://linux-hardware.org/?probe=f280fd203e) | Aug 21, 2023 |
| Dell          | Latitude E7440              | Notebook    | [7a5bd0f1a6](https://linux-hardware.org/?probe=7a5bd0f1a6) | Aug 19, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [a75b18f36c](https://linux-hardware.org/?probe=a75b18f36c) | Aug 19, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [d3aac86eac](https://linux-hardware.org/?probe=d3aac86eac) | Aug 16, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [7032d8da96](https://linux-hardware.org/?probe=7032d8da96) | Aug 16, 2023 |
| Sony          | VGN-SR19VN                  | Notebook    | [013756c475](https://linux-hardware.org/?probe=013756c475) | Aug 16, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [9f04bd8095](https://linux-hardware.org/?probe=9f04bd8095) | Aug 16, 2023 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [8e409a97d7](https://linux-hardware.org/?probe=8e409a97d7) | Aug 15, 2023 |
| ASRock        | EP2C602                     | Desktop     | [26c37b5dfa](https://linux-hardware.org/?probe=26c37b5dfa) | Aug 15, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [9825a49641](https://linux-hardware.org/?probe=9825a49641) | Aug 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [25aaeea069](https://linux-hardware.org/?probe=25aaeea069) | Aug 15, 2023 |
| Alienware     | 0XJKKD A01                  | Desktop     | [1b0f880002](https://linux-hardware.org/?probe=1b0f880002) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | Notebook    | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [37086c4564](https://linux-hardware.org/?probe=37086c4564) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ed6e0727b2](https://linux-hardware.org/?probe=ed6e0727b2) | Aug 14, 2023 |
| ASRock        | EP2C602                     | Desktop     | [c152c5a2f9](https://linux-hardware.org/?probe=c152c5a2f9) | Aug 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [fe5f1d5c1b](https://linux-hardware.org/?probe=fe5f1d5c1b) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1d5206dc94](https://linux-hardware.org/?probe=1d5206dc94) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [bcda0258e5](https://linux-hardware.org/?probe=bcda0258e5) | Aug 12, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [b83d821361](https://linux-hardware.org/?probe=b83d821361) | Aug 11, 2023 |
| Intel         | D915GEV AAC63667-501        | Desktop     | [4d65f6d8fa](https://linux-hardware.org/?probe=4d65f6d8fa) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [92fda27219](https://linux-hardware.org/?probe=92fda27219) | Aug 10, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [3bd085d1a5](https://linux-hardware.org/?probe=3bd085d1a5) | Aug 10, 2023 |
| HP            | 8433 11                     | Desktop     | [eac08c7b54](https://linux-hardware.org/?probe=eac08c7b54) | Aug 09, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [b97d54f6d8](https://linux-hardware.org/?probe=b97d54f6d8) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [11cf6b0c98](https://linux-hardware.org/?probe=11cf6b0c98) | Aug 09, 2023 |
| GPD           | P2 MAX                      | Notebook    | [064bc78973](https://linux-hardware.org/?probe=064bc78973) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [1e3f49e3a0](https://linux-hardware.org/?probe=1e3f49e3a0) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [2f32ca43ee](https://linux-hardware.org/?probe=2f32ca43ee) | Aug 09, 2023 |
| HP            | 894D                        | Desktop     | [e1c397df93](https://linux-hardware.org/?probe=e1c397df93) | Aug 09, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [62889fd683](https://linux-hardware.org/?probe=62889fd683) | Aug 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [cb5a99b4fb](https://linux-hardware.org/?probe=cb5a99b4fb) | Aug 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [04e63e59bd](https://linux-hardware.org/?probe=04e63e59bd) | Aug 07, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6c24c9f7a9](https://linux-hardware.org/?probe=6c24c9f7a9) | Aug 05, 2023 |
| HP            | 87A4 10100                  | All in one  | [ac3d0deece](https://linux-hardware.org/?probe=ac3d0deece) | Aug 05, 2023 |
| HP            | 87A4 10100                  | All in one  | [1dac28eee7](https://linux-hardware.org/?probe=1dac28eee7) | Aug 05, 2023 |
| AZW           | GTR V02                     | Desktop     | [b2afc2c53e](https://linux-hardware.org/?probe=b2afc2c53e) | Aug 04, 2023 |
| HP            | 2AF7                        | Desktop     | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [e7810a04a9](https://linux-hardware.org/?probe=e7810a04a9) | Aug 04, 2023 |
| Dell          | XPS 9320                    | Notebook    | [140f8f8b2e](https://linux-hardware.org/?probe=140f8f8b2e) | Aug 04, 2023 |
| HP            | 87A4 10100                  | All in one  | [a62908af95](https://linux-hardware.org/?probe=a62908af95) | Aug 04, 2023 |
| HP            | 87A4 10100                  | All in one  | [eb7ae8bbb2](https://linux-hardware.org/?probe=eb7ae8bbb2) | Aug 04, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [0839bbc721](https://linux-hardware.org/?probe=0839bbc721) | Aug 03, 2023 |
| Acer          | TravelMate P614-51-G2       | Notebook    | [33dd52a94f](https://linux-hardware.org/?probe=33dd52a94f) | Aug 03, 2023 |
| HP            | 843E                        | Desktop     | [dbbfb83ae4](https://linux-hardware.org/?probe=dbbfb83ae4) | Aug 03, 2023 |
| HP            | 843E                        | Desktop     | [952db006c3](https://linux-hardware.org/?probe=952db006c3) | Aug 03, 2023 |
| Dell          | Latitude E6330              | Notebook    | [75d54a8988](https://linux-hardware.org/?probe=75d54a8988) | Aug 03, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | Notebook    | [5bbbd1f3d4](https://linux-hardware.org/?probe=5bbbd1f3d4) | Aug 02, 2023 |
| Schenker      | XMG FOCUS (Mid 2021)        | Notebook    | [d7fa14789f](https://linux-hardware.org/?probe=d7fa14789f) | Aug 01, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [3efa8549a5](https://linux-hardware.org/?probe=3efa8549a5) | Aug 01, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [b298625640](https://linux-hardware.org/?probe=b298625640) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [25dd387c2c](https://linux-hardware.org/?probe=25dd387c2c) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [7f5c70c059](https://linux-hardware.org/?probe=7f5c70c059) | Aug 01, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [49a431c092](https://linux-hardware.org/?probe=49a431c092) | Jul 31, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [add6831dcd](https://linux-hardware.org/?probe=add6831dcd) | Jul 31, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [7cb3479a69](https://linux-hardware.org/?probe=7cb3479a69) | Jul 31, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [beea8be008](https://linux-hardware.org/?probe=beea8be008) | Jul 30, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [80b81f5eff](https://linux-hardware.org/?probe=80b81f5eff) | Jul 30, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [5518dab193](https://linux-hardware.org/?probe=5518dab193) | Jul 29, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [aef96d4eb8](https://linux-hardware.org/?probe=aef96d4eb8) | Jul 29, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [1006fe2c7b](https://linux-hardware.org/?probe=1006fe2c7b) | Jul 29, 2023 |
| HP            | Elite Dragonfly             | Convertible | [a44424e066](https://linux-hardware.org/?probe=a44424e066) | Jul 28, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [86d9ab8b73](https://linux-hardware.org/?probe=86d9ab8b73) | Jul 28, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [6ea424234a](https://linux-hardware.org/?probe=6ea424234a) | Jul 28, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [9c8b9571d9](https://linux-hardware.org/?probe=9c8b9571d9) | Jul 27, 2023 |
| Lenovo        | ThinkPad L380 20M50011MZ    | Notebook    | [03152e1c57](https://linux-hardware.org/?probe=03152e1c57) | Jul 26, 2023 |
| Acer          | Elena                       | Desktop     | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [45e8471971](https://linux-hardware.org/?probe=45e8471971) | Jul 26, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [5693ac5e4c](https://linux-hardware.org/?probe=5693ac5e4c) | Jul 25, 2023 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9fbb932f79](https://linux-hardware.org/?probe=9fbb932f79) | Jul 25, 2023 |
| ASUSTek       | ROG Flow X13 GV302XI_GV3... | Convertible | [a326770d26](https://linux-hardware.org/?probe=a326770d26) | Jul 25, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [47fec524e4](https://linux-hardware.org/?probe=47fec524e4) | Jul 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [dc537ae22a](https://linux-hardware.org/?probe=dc537ae22a) | Jul 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [cff40caac1](https://linux-hardware.org/?probe=cff40caac1) | Jul 24, 2023 |
| Dell          | Latitude 7480               | Notebook    | [acad753aa8](https://linux-hardware.org/?probe=acad753aa8) | Jul 23, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [f2e2436cf1](https://linux-hardware.org/?probe=f2e2436cf1) | Jul 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [d387ed9d0c](https://linux-hardware.org/?probe=d387ed9d0c) | Jul 22, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [ff6179199d](https://linux-hardware.org/?probe=ff6179199d) | Jul 22, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [988a5f870c](https://linux-hardware.org/?probe=988a5f870c) | Jul 21, 2023 |
| ASUSTek       | G551JK                      | Notebook    | [fed0cf1fce](https://linux-hardware.org/?probe=fed0cf1fce) | Jul 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [a8f79a71f7](https://linux-hardware.org/?probe=a8f79a71f7) | Jul 20, 2023 |
| Acer          | Predator PH317-56           | Notebook    | [248af0e35c](https://linux-hardware.org/?probe=248af0e35c) | Jul 18, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [b3d68108a2](https://linux-hardware.org/?probe=b3d68108a2) | Jul 18, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [fbb58d4f7c](https://linux-hardware.org/?probe=fbb58d4f7c) | Jul 18, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [f62d1b0d14](https://linux-hardware.org/?probe=f62d1b0d14) | Jul 17, 2023 |
| HP            | Pavilion dm1                | Notebook    | [135bb20fbd](https://linux-hardware.org/?probe=135bb20fbd) | Jul 17, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [798ddca1c4](https://linux-hardware.org/?probe=798ddca1c4) | Jul 16, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [236c9f5565](https://linux-hardware.org/?probe=236c9f5565) | Jul 14, 2023 |
| HP            | Pavilion dm1                | Notebook    | [3b05c5dc5c](https://linux-hardware.org/?probe=3b05c5dc5c) | Jul 14, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [d017610254](https://linux-hardware.org/?probe=d017610254) | Jul 14, 2023 |
| Dell          | 0WC7KF A00                  | All in one  | [71309341ec](https://linux-hardware.org/?probe=71309341ec) | Jul 13, 2023 |
| HP            | 83DD                        | Mini pc     | [38e991673e](https://linux-hardware.org/?probe=38e991673e) | Jul 12, 2023 |
| Dell          | XPS 12 9Q23                 | Notebook    | [5fb9db838e](https://linux-hardware.org/?probe=5fb9db838e) | Jul 12, 2023 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [fdde43af89](https://linux-hardware.org/?probe=fdde43af89) | Jul 11, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [6d76fdbcd6](https://linux-hardware.org/?probe=6d76fdbcd6) | Jul 10, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [9fd763e236](https://linux-hardware.org/?probe=9fd763e236) | Jul 09, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [b44c0d94f4](https://linux-hardware.org/?probe=b44c0d94f4) | Jul 09, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [61da77f999](https://linux-hardware.org/?probe=61da77f999) | Jul 09, 2023 |
| Medion        | MS-7667                     | Desktop     | [52ff08b634](https://linux-hardware.org/?probe=52ff08b634) | Jul 09, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [a7632f8c4b](https://linux-hardware.org/?probe=a7632f8c4b) | Jul 09, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [9b8d05afca](https://linux-hardware.org/?probe=9b8d05afca) | Jul 08, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [e0e1896cc3](https://linux-hardware.org/?probe=e0e1896cc3) | Jul 07, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [3908772779](https://linux-hardware.org/?probe=3908772779) | Jul 07, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [8da6cc6879](https://linux-hardware.org/?probe=8da6cc6879) | Jul 07, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Notebook    | [4ff583eb14](https://linux-hardware.org/?probe=4ff583eb14) | Jul 05, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [80ed1496a1](https://linux-hardware.org/?probe=80ed1496a1) | Jul 05, 2023 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [530d25db12](https://linux-hardware.org/?probe=530d25db12) | Jul 03, 2023 |
| TUXEDO        | InfinityBook 14 v2          | Notebook    | [9447ac0693](https://linux-hardware.org/?probe=9447ac0693) | Jul 02, 2023 |
| HP            | 8918                        | Desktop     | [da7b695c7b](https://linux-hardware.org/?probe=da7b695c7b) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [277a9bb8e4](https://linux-hardware.org/?probe=277a9bb8e4) | Jul 02, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [d772da19a0](https://linux-hardware.org/?probe=d772da19a0) | Jun 30, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [566b883024](https://linux-hardware.org/?probe=566b883024) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3c1007547d](https://linux-hardware.org/?probe=3c1007547d) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [1e33cadd37](https://linux-hardware.org/?probe=1e33cadd37) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [08708e8e9d](https://linux-hardware.org/?probe=08708e8e9d) | Jun 28, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ad91997e3e](https://linux-hardware.org/?probe=ad91997e3e) | Jun 28, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [7f5dfae0db](https://linux-hardware.org/?probe=7f5dfae0db) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [8619447305](https://linux-hardware.org/?probe=8619447305) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [bddefdfb2c](https://linux-hardware.org/?probe=bddefdfb2c) | Jun 27, 2023 |
| Unknown       | Unknown                     | Soc         | [baebeebbdb](https://linux-hardware.org/?probe=baebeebbdb) | Jun 27, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [731b4a6479](https://linux-hardware.org/?probe=731b4a6479) | Jun 26, 2023 |
| Star Labs     | LabTop                      | Notebook    | [87a0d9dc09](https://linux-hardware.org/?probe=87a0d9dc09) | Jun 26, 2023 |
| Star Labs     | LabTop                      | Notebook    | [a413031ef8](https://linux-hardware.org/?probe=a413031ef8) | Jun 25, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [66f2fbfdf4](https://linux-hardware.org/?probe=66f2fbfdf4) | Jun 25, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [32ab15a1eb](https://linux-hardware.org/?probe=32ab15a1eb) | Jun 25, 2023 |
| Acer          | Aspire F5-571G              | Notebook    | [fb61026d60](https://linux-hardware.org/?probe=fb61026d60) | Jun 25, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [ade3806ebb](https://linux-hardware.org/?probe=ade3806ebb) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [b82cc440a0](https://linux-hardware.org/?probe=b82cc440a0) | Jun 24, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [cb554fb8f8](https://linux-hardware.org/?probe=cb554fb8f8) | Jun 24, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [f8dee044e2](https://linux-hardware.org/?probe=f8dee044e2) | Jun 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [700914c136](https://linux-hardware.org/?probe=700914c136) | Jun 23, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [24db241d7a](https://linux-hardware.org/?probe=24db241d7a) | Jun 22, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [23ea485e5e](https://linux-hardware.org/?probe=23ea485e5e) | Jun 22, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d607d3c598](https://linux-hardware.org/?probe=d607d3c598) | Jun 22, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [8518224d34](https://linux-hardware.org/?probe=8518224d34) | Jun 21, 2023 |
| Lenovo        | ThinkPad L380 20M50011MZ    | Notebook    | [223c8d15d4](https://linux-hardware.org/?probe=223c8d15d4) | Jun 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [186a21a6f7](https://linux-hardware.org/?probe=186a21a6f7) | Jun 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [f008d4c0db](https://linux-hardware.org/?probe=f008d4c0db) | Jun 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [953a81c579](https://linux-hardware.org/?probe=953a81c579) | Jun 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e9865c622f](https://linux-hardware.org/?probe=e9865c622f) | Jun 19, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [90720c3820](https://linux-hardware.org/?probe=90720c3820) | Jun 18, 2023 |
| Lenovo        | ThinkPad E580 20KS001JMZ    | Notebook    | [780d549a32](https://linux-hardware.org/?probe=780d549a32) | Jun 18, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [4b184d1037](https://linux-hardware.org/?probe=4b184d1037) | Jun 18, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c45597704a](https://linux-hardware.org/?probe=c45597704a) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a312151081](https://linux-hardware.org/?probe=a312151081) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [7d329c0bee](https://linux-hardware.org/?probe=7d329c0bee) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [acf5c5a440](https://linux-hardware.org/?probe=acf5c5a440) | Jun 14, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [467be092e4](https://linux-hardware.org/?probe=467be092e4) | Jun 14, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8ea9d60a21](https://linux-hardware.org/?probe=8ea9d60a21) | Jun 12, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [794030a707](https://linux-hardware.org/?probe=794030a707) | Jun 12, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | Notebook    | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ec6af41f13](https://linux-hardware.org/?probe=ec6af41f13) | Jun 11, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [1cfac1228c](https://linux-hardware.org/?probe=1cfac1228c) | Jun 10, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [427db0e78b](https://linux-hardware.org/?probe=427db0e78b) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6adee93e47](https://linux-hardware.org/?probe=6adee93e47) | Jun 10, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [08a506ad4e](https://linux-hardware.org/?probe=08a506ad4e) | Jun 09, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [15185698e7](https://linux-hardware.org/?probe=15185698e7) | Jun 09, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [212ff65852](https://linux-hardware.org/?probe=212ff65852) | Jun 09, 2023 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [7346eaf346](https://linux-hardware.org/?probe=7346eaf346) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [45ee697eed](https://linux-hardware.org/?probe=45ee697eed) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [0f36ecaa7e](https://linux-hardware.org/?probe=0f36ecaa7e) | Jun 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f70195a177](https://linux-hardware.org/?probe=f70195a177) | Jun 07, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [7d33fb0564](https://linux-hardware.org/?probe=7d33fb0564) | Jun 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [82aba8957b](https://linux-hardware.org/?probe=82aba8957b) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [ae164f9998](https://linux-hardware.org/?probe=ae164f9998) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [6ae325ff9d](https://linux-hardware.org/?probe=6ae325ff9d) | Jun 06, 2023 |
| HP            | 8918                        | Desktop     | [6f94c9caa9](https://linux-hardware.org/?probe=6f94c9caa9) | Jun 06, 2023 |
| Lenovo        | ThinkPad 21CKCT01WW         | Notebook    | [92c9ec75c4](https://linux-hardware.org/?probe=92c9ec75c4) | Jun 05, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [1bd1a651bb](https://linux-hardware.org/?probe=1bd1a651bb) | Jun 05, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [d9dba3ffdf](https://linux-hardware.org/?probe=d9dba3ffdf) | Jun 04, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5b7a78b32e](https://linux-hardware.org/?probe=5b7a78b32e) | Jun 04, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [14f68da7a7](https://linux-hardware.org/?probe=14f68da7a7) | Jun 04, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [f077d744cb](https://linux-hardware.org/?probe=f077d744cb) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [4d24b9b7d5](https://linux-hardware.org/?probe=4d24b9b7d5) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [069b512b91](https://linux-hardware.org/?probe=069b512b91) | Jun 03, 2023 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [f95d5c3046](https://linux-hardware.org/?probe=f95d5c3046) | Jun 03, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d8f3391b68](https://linux-hardware.org/?probe=d8f3391b68) | Jun 02, 2023 |
| HP            | 8918                        | Desktop     | [b03f8a6eb3](https://linux-hardware.org/?probe=b03f8a6eb3) | Jun 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | Notebook    | [e920b77fbb](https://linux-hardware.org/?probe=e920b77fbb) | Jun 02, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [16d662673f](https://linux-hardware.org/?probe=16d662673f) | Jun 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [0a6e1e6be8](https://linux-hardware.org/?probe=0a6e1e6be8) | Jun 02, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [e98b2555d7](https://linux-hardware.org/?probe=e98b2555d7) | Jun 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [3cb9ad156f](https://linux-hardware.org/?probe=3cb9ad156f) | Jun 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [31eb124dfb](https://linux-hardware.org/?probe=31eb124dfb) | Jun 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [29ec12f64d](https://linux-hardware.org/?probe=29ec12f64d) | May 30, 2023 |
| HP            | 2B36                        | Desktop     | [8e4fc0d41f](https://linux-hardware.org/?probe=8e4fc0d41f) | May 29, 2023 |
| GPD           | P2 MAX                      | Notebook    | [3c083ee96d](https://linux-hardware.org/?probe=3c083ee96d) | May 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [1d8b78cbdc](https://linux-hardware.org/?probe=1d8b78cbdc) | May 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [57b9304725](https://linux-hardware.org/?probe=57b9304725) | May 27, 2023 |
| Lenovo        | 3716 SDK0T76461 WIN 3422... | Desktop     | [2f3952dcfe](https://linux-hardware.org/?probe=2f3952dcfe) | May 27, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [246b95d20f](https://linux-hardware.org/?probe=246b95d20f) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| Samsung       | 930QED                      | Convertible | [14f0193b6a](https://linux-hardware.org/?probe=14f0193b6a) | May 23, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [2cdf1c9e61](https://linux-hardware.org/?probe=2cdf1c9e61) | May 23, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [cca41e18cb](https://linux-hardware.org/?probe=cca41e18cb) | May 23, 2023 |
| Intel         | S2600STB J17012-601         | Server      | [2fa80c021a](https://linux-hardware.org/?probe=2fa80c021a) | May 23, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [a5a990a94c](https://linux-hardware.org/?probe=a5a990a94c) | May 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [aa0bf32546](https://linux-hardware.org/?probe=aa0bf32546) | May 23, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [c956e9cbab](https://linux-hardware.org/?probe=c956e9cbab) | May 22, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [ae4f01f58e](https://linux-hardware.org/?probe=ae4f01f58e) | May 22, 2023 |
| Dell          | Latitude E6530              | Notebook    | [7c04efc558](https://linux-hardware.org/?probe=7c04efc558) | May 21, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [019a851aeb](https://linux-hardware.org/?probe=019a851aeb) | May 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [4a68db15c2](https://linux-hardware.org/?probe=4a68db15c2) | May 21, 2023 |
| ASUSTek       | ROG Flow X13 GV302XI_GV3... | Convertible | [5d4070956a](https://linux-hardware.org/?probe=5d4070956a) | May 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [f59c4fec2f](https://linux-hardware.org/?probe=f59c4fec2f) | May 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [b5d454d4ec](https://linux-hardware.org/?probe=b5d454d4ec) | May 18, 2023 |
| Dell          | Latitude E6530              | Notebook    | [e6064ac95c](https://linux-hardware.org/?probe=e6064ac95c) | May 17, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [bdaec355df](https://linux-hardware.org/?probe=bdaec355df) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [b595a4a849](https://linux-hardware.org/?probe=b595a4a849) | May 15, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | Notebook    | [ec0250b092](https://linux-hardware.org/?probe=ec0250b092) | May 15, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [9f4a8a37c0](https://linux-hardware.org/?probe=9f4a8a37c0) | May 15, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [e67567bd2a](https://linux-hardware.org/?probe=e67567bd2a) | May 15, 2023 |
| Dell          | Latitude 5520               | Notebook    | [721000195d](https://linux-hardware.org/?probe=721000195d) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [64b813a7dc](https://linux-hardware.org/?probe=64b813a7dc) | May 14, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [6142fe7fbd](https://linux-hardware.org/?probe=6142fe7fbd) | May 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [09eb36df64](https://linux-hardware.org/?probe=09eb36df64) | May 13, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [26beee94a9](https://linux-hardware.org/?probe=26beee94a9) | May 12, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [d71435c79a](https://linux-hardware.org/?probe=d71435c79a) | May 12, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [62e7f77fdc](https://linux-hardware.org/?probe=62e7f77fdc) | May 12, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [f6c8b6c33e](https://linux-hardware.org/?probe=f6c8b6c33e) | May 12, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [41d9417c57](https://linux-hardware.org/?probe=41d9417c57) | May 11, 2023 |
| Acer          | Aspire 5332                 | Notebook    | [e74870bf17](https://linux-hardware.org/?probe=e74870bf17) | May 10, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [c39e7fa08d](https://linux-hardware.org/?probe=c39e7fa08d) | May 09, 2023 |
| HP            | Compaq 6910p                | Notebook    | [c17dc1abcf](https://linux-hardware.org/?probe=c17dc1abcf) | May 08, 2023 |
| Dell          | 0KRC95 A00                  | Desktop     | [f0f22d5d3f](https://linux-hardware.org/?probe=f0f22d5d3f) | May 08, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c95999b5ad](https://linux-hardware.org/?probe=c95999b5ad) | May 08, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [670e910889](https://linux-hardware.org/?probe=670e910889) | May 08, 2023 |
| Medion        | S1219T MD99922              | Tablet      | [7502ce9679](https://linux-hardware.org/?probe=7502ce9679) | May 08, 2023 |
| Medion        | MS-7797                     | Desktop     | [590e39bef4](https://linux-hardware.org/?probe=590e39bef4) | May 07, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [6089dfdeab](https://linux-hardware.org/?probe=6089dfdeab) | May 07, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [df056ec6f1](https://linux-hardware.org/?probe=df056ec6f1) | May 07, 2023 |
| Medion        | MS-7797                     | Desktop     | [d7eb2caa26](https://linux-hardware.org/?probe=d7eb2caa26) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6a4a95e86f](https://linux-hardware.org/?probe=6a4a95e86f) | May 06, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3f2fa70636](https://linux-hardware.org/?probe=3f2fa70636) | May 06, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [2a4b061b07](https://linux-hardware.org/?probe=2a4b061b07) | May 05, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [54417e14cf](https://linux-hardware.org/?probe=54417e14cf) | May 05, 2023 |
| HP            | 212B                        | Desktop     | [d71b834a1c](https://linux-hardware.org/?probe=d71b834a1c) | May 05, 2023 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [4b705b9dca](https://linux-hardware.org/?probe=4b705b9dca) | May 03, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | Desktop     | [61873cde49](https://linux-hardware.org/?probe=61873cde49) | May 03, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [bbd9496296](https://linux-hardware.org/?probe=bbd9496296) | May 03, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [71ec2fc5ea](https://linux-hardware.org/?probe=71ec2fc5ea) | May 03, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [6936dcf305](https://linux-hardware.org/?probe=6936dcf305) | May 03, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [7a44b651f4](https://linux-hardware.org/?probe=7a44b651f4) | May 03, 2023 |
| Acer          | Predator PH18-71            | Notebook    | [7c5e0a3de1](https://linux-hardware.org/?probe=7c5e0a3de1) | May 02, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [a720d9d42e](https://linux-hardware.org/?probe=a720d9d42e) | May 01, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0f77b52547](https://linux-hardware.org/?probe=0f77b52547) | May 01, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [c8c9c1e591](https://linux-hardware.org/?probe=c8c9c1e591) | Apr 30, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [7d6b0027b3](https://linux-hardware.org/?probe=7d6b0027b3) | Apr 30, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [5d77d7d922](https://linux-hardware.org/?probe=5d77d7d922) | Apr 30, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [6a102a2c37](https://linux-hardware.org/?probe=6a102a2c37) | Apr 29, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [910d4a6ad8](https://linux-hardware.org/?probe=910d4a6ad8) | Apr 29, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [e1e3261c15](https://linux-hardware.org/?probe=e1e3261c15) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [004e0007e4](https://linux-hardware.org/?probe=004e0007e4) | Apr 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [00d8186404](https://linux-hardware.org/?probe=00d8186404) | Apr 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [50e1b8e197](https://linux-hardware.org/?probe=50e1b8e197) | Apr 28, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [cb87589d9f](https://linux-hardware.org/?probe=cb87589d9f) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [ec41184680](https://linux-hardware.org/?probe=ec41184680) | Apr 27, 2023 |
| Dell          | Latitude 5520               | Notebook    | [3071d4a9d8](https://linux-hardware.org/?probe=3071d4a9d8) | Apr 26, 2023 |
| Dell          | Latitude 5520               | Notebook    | [23fe32affd](https://linux-hardware.org/?probe=23fe32affd) | Apr 26, 2023 |
| MSI           | Creator 15 A10SGS           | Notebook    | [1b364e385a](https://linux-hardware.org/?probe=1b364e385a) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a48c247194](https://linux-hardware.org/?probe=a48c247194) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [11844fed4d](https://linux-hardware.org/?probe=11844fed4d) | Apr 25, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [7afd2012e8](https://linux-hardware.org/?probe=7afd2012e8) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [c7fdbbb95b](https://linux-hardware.org/?probe=c7fdbbb95b) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [363bb28966](https://linux-hardware.org/?probe=363bb28966) | Apr 25, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d73e1b6350](https://linux-hardware.org/?probe=d73e1b6350) | Apr 24, 2023 |
| Dell          | Latitude 7530               | Notebook    | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| HP            | 8433 11                     | Desktop     | [e885f0469c](https://linux-hardware.org/?probe=e885f0469c) | Apr 22, 2023 |
| AZW           | GTR V02                     | Desktop     | [104badc0d7](https://linux-hardware.org/?probe=104badc0d7) | Apr 22, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [570077aa64](https://linux-hardware.org/?probe=570077aa64) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | Desktop     | [65c9942c32](https://linux-hardware.org/?probe=65c9942c32) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | Desktop     | [607dbbf4d8](https://linux-hardware.org/?probe=607dbbf4d8) | Apr 21, 2023 |
| Gigabyte      | P55A-UD7                    | Desktop     | [59f8c4d262](https://linux-hardware.org/?probe=59f8c4d262) | Apr 20, 2023 |
| Intel         | S2600WTTR G92187-366        | Server      | [9bb50174ef](https://linux-hardware.org/?probe=9bb50174ef) | Apr 20, 2023 |
| Dell          | 0DPRKF A01                  | Server      | [51412400ba](https://linux-hardware.org/?probe=51412400ba) | Apr 20, 2023 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [f20338e169](https://linux-hardware.org/?probe=f20338e169) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2c6da4e91f](https://linux-hardware.org/?probe=2c6da4e91f) | Apr 20, 2023 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [472922fafd](https://linux-hardware.org/?probe=472922fafd) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [a1b9ea4fd9](https://linux-hardware.org/?probe=a1b9ea4fd9) | Apr 20, 2023 |
| Intel         | DX58SO2 AAG10925-207        | Desktop     | [4e31c5af6b](https://linux-hardware.org/?probe=4e31c5af6b) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [27a629fd15](https://linux-hardware.org/?probe=27a629fd15) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f3a680d9bc](https://linux-hardware.org/?probe=f3a680d9bc) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | Desktop     | [96d5a26185](https://linux-hardware.org/?probe=96d5a26185) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [b6306c2e97](https://linux-hardware.org/?probe=b6306c2e97) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [fbedbcb213](https://linux-hardware.org/?probe=fbedbcb213) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | Desktop     | [6e77ac0ec9](https://linux-hardware.org/?probe=6e77ac0ec9) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [c1b2a75484](https://linux-hardware.org/?probe=c1b2a75484) | Apr 20, 2023 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | Desktop     | [756eccb961](https://linux-hardware.org/?probe=756eccb961) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [ef04208d0f](https://linux-hardware.org/?probe=ef04208d0f) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [c419c9200f](https://linux-hardware.org/?probe=c419c9200f) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | Desktop     | [1be8dc273c](https://linux-hardware.org/?probe=1be8dc273c) | Apr 20, 2023 |
| Intel         | S2600WTTR G92187-366        | Server      | [d765a92052](https://linux-hardware.org/?probe=d765a92052) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [244222ae5c](https://linux-hardware.org/?probe=244222ae5c) | Apr 20, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [f77fe53c69](https://linux-hardware.org/?probe=f77fe53c69) | Apr 20, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7d49aa5207](https://linux-hardware.org/?probe=7d49aa5207) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [d53ce13aa3](https://linux-hardware.org/?probe=d53ce13aa3) | Apr 20, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [ec13e17577](https://linux-hardware.org/?probe=ec13e17577) | Apr 20, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [9fde2b21fc](https://linux-hardware.org/?probe=9fde2b21fc) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | Desktop     | [ddc7ba8ccb](https://linux-hardware.org/?probe=ddc7ba8ccb) | Apr 20, 2023 |
| Fujitsu       | D3348-A2 S26361-D3348-A2    | Desktop     | [3dbd4f731c](https://linux-hardware.org/?probe=3dbd4f731c) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [d46e9b11d5](https://linux-hardware.org/?probe=d46e9b11d5) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [afbf28c15a](https://linux-hardware.org/?probe=afbf28c15a) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [f185782be2](https://linux-hardware.org/?probe=f185782be2) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [731671f1b8](https://linux-hardware.org/?probe=731671f1b8) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [463c62da83](https://linux-hardware.org/?probe=463c62da83) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [0356125777](https://linux-hardware.org/?probe=0356125777) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [0a45e9e9af](https://linux-hardware.org/?probe=0a45e9e9af) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ccf2e2bbc3](https://linux-hardware.org/?probe=ccf2e2bbc3) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3171099090](https://linux-hardware.org/?probe=3171099090) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [032f3a72c6](https://linux-hardware.org/?probe=032f3a72c6) | Apr 20, 2023 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [df7041b726](https://linux-hardware.org/?probe=df7041b726) | Apr 20, 2023 |
| ASUSTek       | P9X79 WS                    | Desktop     | [04e9cd2455](https://linux-hardware.org/?probe=04e9cd2455) | Apr 20, 2023 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [0dd9e12f5a](https://linux-hardware.org/?probe=0dd9e12f5a) | Apr 20, 2023 |
| HP            | 870B                        | Desktop     | [ad6a3cc4d0](https://linux-hardware.org/?probe=ad6a3cc4d0) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [9e668ff813](https://linux-hardware.org/?probe=9e668ff813) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [5dc0cb1f28](https://linux-hardware.org/?probe=5dc0cb1f28) | Apr 20, 2023 |
| Medion        | GA-Z170X-Gaming 7           | Desktop     | [706cfb4c50](https://linux-hardware.org/?probe=706cfb4c50) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [b3b27e0fcf](https://linux-hardware.org/?probe=b3b27e0fcf) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [bdbd8d06e2](https://linux-hardware.org/?probe=bdbd8d06e2) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [ff10999142](https://linux-hardware.org/?probe=ff10999142) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [11da8c5d96](https://linux-hardware.org/?probe=11da8c5d96) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [128d16cf7f](https://linux-hardware.org/?probe=128d16cf7f) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c2de2809a0](https://linux-hardware.org/?probe=c2de2809a0) | Apr 20, 2023 |
| Intel         | S2600WFT H48104-860         | Server      | [f5848d1ba2](https://linux-hardware.org/?probe=f5848d1ba2) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c3a3c03c3f](https://linux-hardware.org/?probe=c3a3c03c3f) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [1ae9258a0d](https://linux-hardware.org/?probe=1ae9258a0d) | Apr 20, 2023 |
| Intel         | SVRBD-ROW_T G30981-503      | Server      | [5fba63c085](https://linux-hardware.org/?probe=5fba63c085) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [ab89260502](https://linux-hardware.org/?probe=ab89260502) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3f99aeec69](https://linux-hardware.org/?probe=3f99aeec69) | Apr 20, 2023 |
| HP            | 870B                        | Desktop     | [50f654b2a0](https://linux-hardware.org/?probe=50f654b2a0) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | Desktop     | [9949a0748f](https://linux-hardware.org/?probe=9949a0748f) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [e3cfbf7435](https://linux-hardware.org/?probe=e3cfbf7435) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [9817f90648](https://linux-hardware.org/?probe=9817f90648) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | Desktop     | [cf4854d704](https://linux-hardware.org/?probe=cf4854d704) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [296676f929](https://linux-hardware.org/?probe=296676f929) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [2eeebec1ec](https://linux-hardware.org/?probe=2eeebec1ec) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [68ac671aab](https://linux-hardware.org/?probe=68ac671aab) | Apr 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a069d32b86](https://linux-hardware.org/?probe=a069d32b86) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [1b1a3da7b2](https://linux-hardware.org/?probe=1b1a3da7b2) | Apr 20, 2023 |
| Gigabyte      | MZ12-HD3-00 01010101        | Server      | [def4067c8e](https://linux-hardware.org/?probe=def4067c8e) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | Desktop     | [2a1fcefe29](https://linux-hardware.org/?probe=2a1fcefe29) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5c54edc96d](https://linux-hardware.org/?probe=5c54edc96d) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [563e45a22a](https://linux-hardware.org/?probe=563e45a22a) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0000720fb6](https://linux-hardware.org/?probe=0000720fb6) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [fdda3d6276](https://linux-hardware.org/?probe=fdda3d6276) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ee95d83f31](https://linux-hardware.org/?probe=ee95d83f31) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1e49dc0f67](https://linux-hardware.org/?probe=1e49dc0f67) | Apr 20, 2023 |
| Gigabyte      | MZ92-FS0-00 01010101        | Server      | [3e6b182473](https://linux-hardware.org/?probe=3e6b182473) | Apr 20, 2023 |
| HP            | ProLiant ML150 G6           | Desktop     | [76dc3db16a](https://linux-hardware.org/?probe=76dc3db16a) | Apr 20, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [c4c1d8086c](https://linux-hardware.org/?probe=c4c1d8086c) | Apr 20, 2023 |
| ASRock        | B560M-HDV                   | Desktop     | [b835e48fad](https://linux-hardware.org/?probe=b835e48fad) | Apr 19, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [882d6f625d](https://linux-hardware.org/?probe=882d6f625d) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8f16bcad94](https://linux-hardware.org/?probe=8f16bcad94) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [848607e7f1](https://linux-hardware.org/?probe=848607e7f1) | Apr 19, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [b076a9a807](https://linux-hardware.org/?probe=b076a9a807) | Apr 18, 2023 |
| Dell          | 0D4VY1 A00                  | All in one  | [ddbd926522](https://linux-hardware.org/?probe=ddbd926522) | Apr 18, 2023 |
| Dell          | 0R4CNN A02                  | Server      | [237a3cd682](https://linux-hardware.org/?probe=237a3cd682) | Apr 18, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [79225bdfaf](https://linux-hardware.org/?probe=79225bdfaf) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [4d802fb610](https://linux-hardware.org/?probe=4d802fb610) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [2b749e898e](https://linux-hardware.org/?probe=2b749e898e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [702377976d](https://linux-hardware.org/?probe=702377976d) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [32f7392dce](https://linux-hardware.org/?probe=32f7392dce) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [b7f40b0d8e](https://linux-hardware.org/?probe=b7f40b0d8e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [9602690aa2](https://linux-hardware.org/?probe=9602690aa2) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [bbf0a5108a](https://linux-hardware.org/?probe=bbf0a5108a) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [000ec3362e](https://linux-hardware.org/?probe=000ec3362e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [7d67899067](https://linux-hardware.org/?probe=7d67899067) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [256a2110b0](https://linux-hardware.org/?probe=256a2110b0) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [9f69cc7127](https://linux-hardware.org/?probe=9f69cc7127) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [997c25143e](https://linux-hardware.org/?probe=997c25143e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [71822fdac9](https://linux-hardware.org/?probe=71822fdac9) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [b3f9111b79](https://linux-hardware.org/?probe=b3f9111b79) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [df314b2a9c](https://linux-hardware.org/?probe=df314b2a9c) | Apr 17, 2023 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [dc155ce308](https://linux-hardware.org/?probe=dc155ce308) | Apr 17, 2023 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [aaff05d28f](https://linux-hardware.org/?probe=aaff05d28f) | Apr 17, 2023 |
| Lenovo        | ThinkPad T420 4180MG1       | Notebook    | [132e6ba829](https://linux-hardware.org/?probe=132e6ba829) | Apr 17, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [fc6c4adaa4](https://linux-hardware.org/?probe=fc6c4adaa4) | Apr 17, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [8dd4721bd1](https://linux-hardware.org/?probe=8dd4721bd1) | Apr 16, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [a0f5ba360c](https://linux-hardware.org/?probe=a0f5ba360c) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [9c885fa5cf](https://linux-hardware.org/?probe=9c885fa5cf) | Apr 16, 2023 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | Desktop     | [4d3cbcc4d9](https://linux-hardware.org/?probe=4d3cbcc4d9) | Apr 16, 2023 |
| Dell          | Latitude 7530               | Notebook    | [133059c3d6](https://linux-hardware.org/?probe=133059c3d6) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [8fb4ed64eb](https://linux-hardware.org/?probe=8fb4ed64eb) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5943787304](https://linux-hardware.org/?probe=5943787304) | Apr 16, 2023 |
| ASUSTek       | X756UJ                      | Notebook    | [a374f8dd26](https://linux-hardware.org/?probe=a374f8dd26) | Apr 15, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [8519b4cda2](https://linux-hardware.org/?probe=8519b4cda2) | Apr 15, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [c4f2e4e7d8](https://linux-hardware.org/?probe=c4f2e4e7d8) | Apr 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [a0247e45a6](https://linux-hardware.org/?probe=a0247e45a6) | Apr 13, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [f205e700dc](https://linux-hardware.org/?probe=f205e700dc) | Apr 13, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [817e4bb939](https://linux-hardware.org/?probe=817e4bb939) | Apr 13, 2023 |
| HP            | 8433 11                     | Desktop     | [61c92812be](https://linux-hardware.org/?probe=61c92812be) | Apr 12, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [d5e608b74e](https://linux-hardware.org/?probe=d5e608b74e) | Apr 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [e9ba143773](https://linux-hardware.org/?probe=e9ba143773) | Apr 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [ec028424ea](https://linux-hardware.org/?probe=ec028424ea) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [cc25df15df](https://linux-hardware.org/?probe=cc25df15df) | Apr 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9ccdf29023](https://linux-hardware.org/?probe=9ccdf29023) | Apr 08, 2023 |
| ASUSTek       | P8P67                       | Desktop     | [a62766f42e](https://linux-hardware.org/?probe=a62766f42e) | Apr 08, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [6a8c52faa7](https://linux-hardware.org/?probe=6a8c52faa7) | Apr 06, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [d741226152](https://linux-hardware.org/?probe=d741226152) | Apr 06, 2023 |
| HP            | ProBook 4540s               | Notebook    | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | Notebook    | [32f5d43e96](https://linux-hardware.org/?probe=32f5d43e96) | Apr 04, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [423c5d2481](https://linux-hardware.org/?probe=423c5d2481) | Apr 03, 2023 |
| Sony          | VPCF22C5E                   | Notebook    | [9d122b8bdd](https://linux-hardware.org/?probe=9d122b8bdd) | Apr 03, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [8566b9511a](https://linux-hardware.org/?probe=8566b9511a) | Apr 02, 2023 |
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [36d245f86b](https://linux-hardware.org/?probe=36d245f86b) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3a8d512ae4](https://linux-hardware.org/?probe=3a8d512ae4) | Apr 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [6f3e488e2b](https://linux-hardware.org/?probe=6f3e488e2b) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b0beffe006](https://linux-hardware.org/?probe=b0beffe006) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [17fb0ed43a](https://linux-hardware.org/?probe=17fb0ed43a) | Mar 31, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [1d5f866283](https://linux-hardware.org/?probe=1d5f866283) | Mar 31, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [570836875c](https://linux-hardware.org/?probe=570836875c) | Mar 31, 2023 |
| HP            | Unknown                     | Notebook    | [fb784430a5](https://linux-hardware.org/?probe=fb784430a5) | Mar 30, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [3494b0fdd9](https://linux-hardware.org/?probe=3494b0fdd9) | Mar 30, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [c885b5da6c](https://linux-hardware.org/?probe=c885b5da6c) | Mar 30, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [452a3fa4a8](https://linux-hardware.org/?probe=452a3fa4a8) | Mar 29, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [e1d01990f4](https://linux-hardware.org/?probe=e1d01990f4) | Mar 27, 2023 |
| HP            | 844C                        | Desktop     | [8270d682a8](https://linux-hardware.org/?probe=8270d682a8) | Mar 27, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [405ce5a9c8](https://linux-hardware.org/?probe=405ce5a9c8) | Mar 27, 2023 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [35e0a73e8f](https://linux-hardware.org/?probe=35e0a73e8f) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [03df3679d3](https://linux-hardware.org/?probe=03df3679d3) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [f7d3c52f58](https://linux-hardware.org/?probe=f7d3c52f58) | Mar 26, 2023 |
| Acer          | Predator G9-791             | Notebook    | [1f820516a3](https://linux-hardware.org/?probe=1f820516a3) | Mar 26, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [426c7d7939](https://linux-hardware.org/?probe=426c7d7939) | Mar 25, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [6c64b62e05](https://linux-hardware.org/?probe=6c64b62e05) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [0096d3d3b1](https://linux-hardware.org/?probe=0096d3d3b1) | Mar 25, 2023 |
| HP            | 8433 11                     | Desktop     | [5ab010ffd4](https://linux-hardware.org/?probe=5ab010ffd4) | Mar 25, 2023 |
| Purism        | Librem 13 v2                | Notebook    | [ef5cf3e08f](https://linux-hardware.org/?probe=ef5cf3e08f) | Mar 25, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [728f83932f](https://linux-hardware.org/?probe=728f83932f) | Mar 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [5a94081c24](https://linux-hardware.org/?probe=5a94081c24) | Mar 24, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [704fb36197](https://linux-hardware.org/?probe=704fb36197) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [1159055040](https://linux-hardware.org/?probe=1159055040) | Mar 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [74be0519cc](https://linux-hardware.org/?probe=74be0519cc) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [5074a23172](https://linux-hardware.org/?probe=5074a23172) | Mar 20, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [9ba3333988](https://linux-hardware.org/?probe=9ba3333988) | Mar 20, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [0fb09c29cb](https://linux-hardware.org/?probe=0fb09c29cb) | Mar 20, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [6c83c2a089](https://linux-hardware.org/?probe=6c83c2a089) | Mar 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3c00ca015f](https://linux-hardware.org/?probe=3c00ca015f) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [d7acdc8bf3](https://linux-hardware.org/?probe=d7acdc8bf3) | Mar 18, 2023 |
| Google        | Lillipup                    | Notebook    | [3eca64113c](https://linux-hardware.org/?probe=3eca64113c) | Mar 18, 2023 |
| Medion        | S1219T MD99922              | Tablet      | [4e6f4d1197](https://linux-hardware.org/?probe=4e6f4d1197) | Mar 17, 2023 |
| HP            | 2B36                        | Desktop     | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [bfdb73f825](https://linux-hardware.org/?probe=bfdb73f825) | Mar 16, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [be76f3a0a3](https://linux-hardware.org/?probe=be76f3a0a3) | Mar 15, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [839899a14d](https://linux-hardware.org/?probe=839899a14d) | Mar 15, 2023 |
| ASUSTek       | UX32A                       | Notebook    | [05121bc6af](https://linux-hardware.org/?probe=05121bc6af) | Mar 15, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f4926b859a](https://linux-hardware.org/?probe=f4926b859a) | Mar 15, 2023 |
| Dell          | Latitude E6440              | Notebook    | [76a537c18e](https://linux-hardware.org/?probe=76a537c18e) | Mar 14, 2023 |
| Notebook      | NS50MU                      | Notebook    | [f5e64711f3](https://linux-hardware.org/?probe=f5e64711f3) | Mar 14, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [31ac227c9f](https://linux-hardware.org/?probe=31ac227c9f) | Mar 14, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [36bcd11bd3](https://linux-hardware.org/?probe=36bcd11bd3) | Mar 14, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [aca12aa4c5](https://linux-hardware.org/?probe=aca12aa4c5) | Mar 13, 2023 |
| Lenovo        | ThinkPad T490s 20NX002SG... | Notebook    | [aa5eb19101](https://linux-hardware.org/?probe=aa5eb19101) | Mar 13, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [433c3d165a](https://linux-hardware.org/?probe=433c3d165a) | Mar 13, 2023 |
| HP            | 212B                        | Desktop     | [8d5ef71d93](https://linux-hardware.org/?probe=8d5ef71d93) | Mar 13, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [43c96b4e3e](https://linux-hardware.org/?probe=43c96b4e3e) | Mar 13, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [a6af61dfb4](https://linux-hardware.org/?probe=a6af61dfb4) | Mar 13, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [c2174a1837](https://linux-hardware.org/?probe=c2174a1837) | Mar 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | Notebook    | [99095e84f5](https://linux-hardware.org/?probe=99095e84f5) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [55fe24706a](https://linux-hardware.org/?probe=55fe24706a) | Mar 11, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [6c90dd73e7](https://linux-hardware.org/?probe=6c90dd73e7) | Mar 11, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [c792b83b69](https://linux-hardware.org/?probe=c792b83b69) | Mar 11, 2023 |
| Lenovo        | ThinkPad Edge E535 32605... | Notebook    | [ade1e690bb](https://linux-hardware.org/?probe=ade1e690bb) | Mar 11, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5cb06ca8ce](https://linux-hardware.org/?probe=5cb06ca8ce) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d7535fd29e](https://linux-hardware.org/?probe=d7535fd29e) | Mar 10, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [0e1279e96d](https://linux-hardware.org/?probe=0e1279e96d) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5b8db1d628](https://linux-hardware.org/?probe=5b8db1d628) | Mar 10, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [b9e49da1f7](https://linux-hardware.org/?probe=b9e49da1f7) | Mar 10, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9946c1c6dc](https://linux-hardware.org/?probe=9946c1c6dc) | Mar 09, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3c5ca39c55](https://linux-hardware.org/?probe=3c5ca39c55) | Mar 08, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [e280beba92](https://linux-hardware.org/?probe=e280beba92) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d52a175b61](https://linux-hardware.org/?probe=d52a175b61) | Mar 07, 2023 |
| AZW           | GTR V02                     | Desktop     | [030dde937b](https://linux-hardware.org/?probe=030dde937b) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [971feb34e4](https://linux-hardware.org/?probe=971feb34e4) | Mar 07, 2023 |
| Fujitsu       | CELSIUS H780                | Notebook    | [7080d07525](https://linux-hardware.org/?probe=7080d07525) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [fd6cb5c68a](https://linux-hardware.org/?probe=fd6cb5c68a) | Mar 07, 2023 |
| Acer          | Predator PH517-61           | Notebook    | [359903fe58](https://linux-hardware.org/?probe=359903fe58) | Mar 07, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [5656c3015d](https://linux-hardware.org/?probe=5656c3015d) | Mar 06, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [676eaa7960](https://linux-hardware.org/?probe=676eaa7960) | Mar 06, 2023 |
| Lenovo        | ThinkPad E590 20NB000YMZ    | Notebook    | [fb05511be8](https://linux-hardware.org/?probe=fb05511be8) | Mar 05, 2023 |
| HP            | Compaq 15                   | Notebook    | [5c8a185273](https://linux-hardware.org/?probe=5c8a185273) | Mar 05, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [e57a377381](https://linux-hardware.org/?probe=e57a377381) | Mar 05, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [e45794963a](https://linux-hardware.org/?probe=e45794963a) | Mar 04, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [a987f40464](https://linux-hardware.org/?probe=a987f40464) | Mar 04, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [6cd1e0a746](https://linux-hardware.org/?probe=6cd1e0a746) | Mar 04, 2023 |
| Timi          | TM1701                      | Notebook    | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [02df2ea534](https://linux-hardware.org/?probe=02df2ea534) | Mar 03, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [1bcec582e3](https://linux-hardware.org/?probe=1bcec582e3) | Mar 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [cacb713046](https://linux-hardware.org/?probe=cacb713046) | Mar 02, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [86ec7ef027](https://linux-hardware.org/?probe=86ec7ef027) | Mar 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [117d283b7a](https://linux-hardware.org/?probe=117d283b7a) | Mar 02, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [0f19d5c037](https://linux-hardware.org/?probe=0f19d5c037) | Mar 01, 2023 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [0780656106](https://linux-hardware.org/?probe=0780656106) | Mar 01, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8fc8fee94a](https://linux-hardware.org/?probe=8fc8fee94a) | Feb 27, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [3f0d63ab15](https://linux-hardware.org/?probe=3f0d63ab15) | Feb 27, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1412fd5885](https://linux-hardware.org/?probe=1412fd5885) | Feb 26, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [0855d319b4](https://linux-hardware.org/?probe=0855d319b4) | Feb 26, 2023 |
| Medion        | BEAST X25                   | Notebook    | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| Dell          | Latitude 5580               | Notebook    | [cd4a13ce32](https://linux-hardware.org/?probe=cd4a13ce32) | Feb 25, 2023 |
| Dell          | Latitude 5580               | Notebook    | [79da5a8efd](https://linux-hardware.org/?probe=79da5a8efd) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9755df8e75](https://linux-hardware.org/?probe=9755df8e75) | Feb 25, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | Notebook    | [2b9ed74f9d](https://linux-hardware.org/?probe=2b9ed74f9d) | Feb 25, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [af87e6ea4c](https://linux-hardware.org/?probe=af87e6ea4c) | Feb 25, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [9c0775a106](https://linux-hardware.org/?probe=9c0775a106) | Feb 25, 2023 |
| Lenovo        | ThinkPad X61s 7667CG7       | Notebook    | [f090aa4d60](https://linux-hardware.org/?probe=f090aa4d60) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [bea010d25e](https://linux-hardware.org/?probe=bea010d25e) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| Intel         | NUC7i3DNB J57625-510        | Mini pc     | [aedbb176f7](https://linux-hardware.org/?probe=aedbb176f7) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [701608fad1](https://linux-hardware.org/?probe=701608fad1) | Feb 22, 2023 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4794c72566](https://linux-hardware.org/?probe=4794c72566) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [119e106d80](https://linux-hardware.org/?probe=119e106d80) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [576314ab03](https://linux-hardware.org/?probe=576314ab03) | Feb 20, 2023 |
| ASUSTek       | GL702VM                     | Notebook    | [daa3e0f7df](https://linux-hardware.org/?probe=daa3e0f7df) | Feb 20, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | Notebook    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | Notebook    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [f8dfa838b7](https://linux-hardware.org/?probe=f8dfa838b7) | Feb 18, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | Notebook    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | Notebook    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [d773500fcb](https://linux-hardware.org/?probe=d773500fcb) | Feb 18, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [c8bc9e01fd](https://linux-hardware.org/?probe=c8bc9e01fd) | Feb 17, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [b39c940cfd](https://linux-hardware.org/?probe=b39c940cfd) | Feb 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [92a61cd4ee](https://linux-hardware.org/?probe=92a61cd4ee) | Feb 16, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| Philco        | DTC-A55                     | Desktop     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [ef74f90ec1](https://linux-hardware.org/?probe=ef74f90ec1) | Feb 16, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [e927a19203](https://linux-hardware.org/?probe=e927a19203) | Feb 16, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [826959e69e](https://linux-hardware.org/?probe=826959e69e) | Feb 13, 2023 |
| Samsung       | 930QED                      | Convertible | [9e03711ee7](https://linux-hardware.org/?probe=9e03711ee7) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [91657d5c1d](https://linux-hardware.org/?probe=91657d5c1d) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [db7a713397](https://linux-hardware.org/?probe=db7a713397) | Feb 12, 2023 |
| Lenovo        | ThinkPad P73 20QR002PMZ     | Notebook    | [458447fa93](https://linux-hardware.org/?probe=458447fa93) | Feb 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2d2e867259](https://linux-hardware.org/?probe=2d2e867259) | Feb 10, 2023 |
| HP            | 8653 A                      | Desktop     | [5854a10eb0](https://linux-hardware.org/?probe=5854a10eb0) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [40c7c2e40b](https://linux-hardware.org/?probe=40c7c2e40b) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [ddd47ed4b7](https://linux-hardware.org/?probe=ddd47ed4b7) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [f163a3dd38](https://linux-hardware.org/?probe=f163a3dd38) | Feb 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [6d9840bb7c](https://linux-hardware.org/?probe=6d9840bb7c) | Feb 08, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a73dfae3f](https://linux-hardware.org/?probe=9a73dfae3f) | Feb 08, 2023 |
| HP            | ProBook 4720s               | Notebook    | [96ec8d979e](https://linux-hardware.org/?probe=96ec8d979e) | Feb 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e7fd395c49](https://linux-hardware.org/?probe=e7fd395c49) | Feb 05, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [49a4e66cd0](https://linux-hardware.org/?probe=49a4e66cd0) | Feb 05, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | Desktop     | [384a4f7da2](https://linux-hardware.org/?probe=384a4f7da2) | Feb 05, 2023 |
| HP            | 2B36                        | Desktop     | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [9e7d0b79cf](https://linux-hardware.org/?probe=9e7d0b79cf) | Feb 05, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [90c48082e0](https://linux-hardware.org/?probe=90c48082e0) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | Notebook    | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5dbc22fda8](https://linux-hardware.org/?probe=5dbc22fda8) | Feb 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e7b6c27948](https://linux-hardware.org/?probe=e7b6c27948) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [4626133ef2](https://linux-hardware.org/?probe=4626133ef2) | Feb 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b08ab3c55c](https://linux-hardware.org/?probe=b08ab3c55c) | Feb 04, 2023 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | Notebook    | [9968b839f2](https://linux-hardware.org/?probe=9968b839f2) | Feb 03, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a66e882be4](https://linux-hardware.org/?probe=a66e882be4) | Feb 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [0ca0b99aa3](https://linux-hardware.org/?probe=0ca0b99aa3) | Feb 03, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| Medion        | MS-7728                     | Desktop     | [60cf9e4948](https://linux-hardware.org/?probe=60cf9e4948) | Jan 31, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [ff0dfe765e](https://linux-hardware.org/?probe=ff0dfe765e) | Jan 31, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [59a0c6f08f](https://linux-hardware.org/?probe=59a0c6f08f) | Jan 30, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [fddcdb0f47](https://linux-hardware.org/?probe=fddcdb0f47) | Jan 29, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [11b07d4e11](https://linux-hardware.org/?probe=11b07d4e11) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [1d79d6f224](https://linux-hardware.org/?probe=1d79d6f224) | Jan 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [14b3eb9a58](https://linux-hardware.org/?probe=14b3eb9a58) | Jan 25, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b83c8fb5a1](https://linux-hardware.org/?probe=b83c8fb5a1) | Jan 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b6afa43240](https://linux-hardware.org/?probe=b6afa43240) | Jan 24, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [141c9ffa73](https://linux-hardware.org/?probe=141c9ffa73) | Jan 24, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [e04cbf47d6](https://linux-hardware.org/?probe=e04cbf47d6) | Jan 24, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [213b4b45e5](https://linux-hardware.org/?probe=213b4b45e5) | Jan 24, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [163afb997a](https://linux-hardware.org/?probe=163afb997a) | Jan 23, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [f45af20da6](https://linux-hardware.org/?probe=f45af20da6) | Jan 23, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [50d894fc60](https://linux-hardware.org/?probe=50d894fc60) | Jan 22, 2023 |
| ASUSTek       | ROG Strix G733CX_G733CX     | Notebook    | [a02df0f932](https://linux-hardware.org/?probe=a02df0f932) | Jan 21, 2023 |
| AZW           | GTR V02                     | Desktop     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0d70d03543](https://linux-hardware.org/?probe=0d70d03543) | Jan 21, 2023 |
| Medion        | MS-7728                     | Desktop     | [93d0aaac10](https://linux-hardware.org/?probe=93d0aaac10) | Jan 21, 2023 |
| Medion        | MS-7728                     | Desktop     | [eb9cef403c](https://linux-hardware.org/?probe=eb9cef403c) | Jan 21, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [0192877edc](https://linux-hardware.org/?probe=0192877edc) | Jan 20, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [69f4adcf81](https://linux-hardware.org/?probe=69f4adcf81) | Jan 20, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [f59ce535eb](https://linux-hardware.org/?probe=f59ce535eb) | Jan 20, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [873a521bf5](https://linux-hardware.org/?probe=873a521bf5) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [bf7bab9d7c](https://linux-hardware.org/?probe=bf7bab9d7c) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [e05b7e7729](https://linux-hardware.org/?probe=e05b7e7729) | Jan 19, 2023 |
| Lenovo        | ThinkPad T470s 20HGS36U0... | Notebook    | [37fd07b937](https://linux-hardware.org/?probe=37fd07b937) | Jan 18, 2023 |
| Medion        | MS-7728                     | Desktop     | [b5e3ddf859](https://linux-hardware.org/?probe=b5e3ddf859) | Jan 18, 2023 |
| Acer          | Veriton M2110G              | Desktop     | [7097a3cf90](https://linux-hardware.org/?probe=7097a3cf90) | Jan 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [b4e1da9857](https://linux-hardware.org/?probe=b4e1da9857) | Jan 17, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [80f8925010](https://linux-hardware.org/?probe=80f8925010) | Jan 17, 2023 |
| Acer          | Aspire M5910                | Desktop     | [d2d4e86b49](https://linux-hardware.org/?probe=d2d4e86b49) | Jan 17, 2023 |
| Lenovo        | B50-10 80QR                 | Notebook    | [e5903bfd98](https://linux-hardware.org/?probe=e5903bfd98) | Jan 17, 2023 |
| HP            | 212B                        | Desktop     | [00822b2263](https://linux-hardware.org/?probe=00822b2263) | Jan 16, 2023 |
| Medion        | MS-7728                     | Desktop     | [5168c2f916](https://linux-hardware.org/?probe=5168c2f916) | Jan 16, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [340bddf38d](https://linux-hardware.org/?probe=340bddf38d) | Jan 16, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [7d0cedda95](https://linux-hardware.org/?probe=7d0cedda95) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [ca74e79834](https://linux-hardware.org/?probe=ca74e79834) | Jan 15, 2023 |
| AZW           | GTR V02                     | Desktop     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [1f30a57359](https://linux-hardware.org/?probe=1f30a57359) | Jan 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [ebb69311f7](https://linux-hardware.org/?probe=ebb69311f7) | Jan 14, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NTC... | Convertible | [03e4d52b2d](https://linux-hardware.org/?probe=03e4d52b2d) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [182eb9ffa1](https://linux-hardware.org/?probe=182eb9ffa1) | Jan 12, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f84f79fce7](https://linux-hardware.org/?probe=f84f79fce7) | Jan 11, 2023 |
| ELSKY         | QM10u                       | Desktop     | [c9bde314b5](https://linux-hardware.org/?probe=c9bde314b5) | Jan 11, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [d014e736fc](https://linux-hardware.org/?probe=d014e736fc) | Jan 11, 2023 |
| Dell          | Latitude 9420               | Convertible | [1446885eb7](https://linux-hardware.org/?probe=1446885eb7) | Jan 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a7b0b9f2e](https://linux-hardware.org/?probe=9a7b0b9f2e) | Jan 10, 2023 |
| Medion        | MS-7728                     | Desktop     | [8310cf0974](https://linux-hardware.org/?probe=8310cf0974) | Jan 10, 2023 |
| HP            | 3048h                       | Desktop     | [e13a2bdf6e](https://linux-hardware.org/?probe=e13a2bdf6e) | Jan 10, 2023 |
| HP            | 158A                        | Desktop     | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [e16bac2828](https://linux-hardware.org/?probe=e16bac2828) | Jan 09, 2023 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [d665a7f0ff](https://linux-hardware.org/?probe=d665a7f0ff) | Jan 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Switzerland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 309       | 11.5%   |
| Ubuntu 18.04                 | 271       | 10.09%  |
| Ubuntu 22.04                 | 258       | 9.61%   |
| Debian 11                    | 95        | 3.54%   |
| Linux Mint 20.3              | 57        | 2.12%   |
| Arch Rolling                 | 45        | 1.68%   |
| OpenMandriva 4.3             | 43        | 1.6%    |
| Debian 10                    | 41        | 1.53%   |
| Zorin 16                     | 39        | 1.45%   |
| openSUSE Tumbleweed-XXXXXXXX | 39        | 1.45%   |
| Ubuntu 21.10                 | 38        | 1.41%   |
| Pop!_OS 22.04                | 37        | 1.38%   |
| Linux Mint 20.2              | 36        | 1.34%   |
| Linux Mint 20.1              | 36        | 1.34%   |
| KDE neon 20.04               | 36        | 1.34%   |
| Linux Mint 21.1              | 33        | 1.23%   |
| Linux Mint 21.2              | 32        | 1.19%   |
| OpenMandriva 4.2             | 31        | 1.15%   |
| Manjaro                      | 30        | 1.12%   |
| Fedora 38                    | 29        | 1.08%   |
| Debian 12                    | 28        | 1.04%   |
| Arch                         | 28        | 1.04%   |
| Ubuntu 20.10                 | 26        | 0.97%   |
| OpenMandriva 23.01           | 24        | 0.89%   |
| Fedora 32                    | 24        | 0.89%   |
| Ubuntu 22.10                 | 23        | 0.86%   |
| Fedora 37                    | 23        | 0.86%   |
| Fedora 34                    | 23        | 0.86%   |
| Ubuntu 21.04                 | 22        | 0.82%   |
| Ubuntu 23.04                 | 21        | 0.78%   |
| Ubuntu 19.10                 | 21        | 0.78%   |
| Pop!_OS 21.04                | 21        | 0.78%   |
| Pop!_OS 20.10                | 21        | 0.78%   |
| Pop!_OS 20.04                | 21        | 0.78%   |
| Fedora 33                    | 21        | 0.78%   |
| ArcoLinux Rolling            | 21        | 0.78%   |
| Ubuntu 19.04                 | 20        | 0.74%   |
| Fedora 35                    | 20        | 0.74%   |
| Linux Mint 19.3              | 19        | 0.71%   |
| Linux Mint 21                | 18        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 930       | 37.8%   |
| Linux Mint    | 228       | 9.27%   |
| Debian        | 190       | 7.72%   |
| Fedora        | 172       | 6.99%   |
| OpenMandriva  | 135       | 5.49%   |
| Pop!_OS       | 99        | 4.02%   |
| Manjaro       | 77        | 3.13%   |
| Arch          | 72        | 2.93%   |
| Kubuntu       | 55        | 2.24%   |
| Zorin         | 54        | 2.2%    |
| openSUSE      | 53        | 2.15%   |
| KDE neon      | 43        | 1.75%   |
| Xubuntu       | 28        | 1.14%   |
| ROSA          | 26        | 1.06%   |
| ArcoLinux     | 24        | 0.98%   |
| Gentoo        | 21        | 0.85%   |
| Elementary    | 19        | 0.77%   |
| Ubuntu MATE   | 18        | 0.73%   |
| Kali          | 18        | 0.73%   |
| Lubuntu       | 15        | 0.61%   |
| EndeavourOS   | 13        | 0.53%   |
| Feren OS      | 12        | 0.49%   |
| CentOS        | 12        | 0.49%   |
| Ubuntu Budgie | 10        | 0.41%   |
| Ubuntu Unity  | 9         | 0.37%   |
| Clear Linux   | 9         | 0.37%   |
| MX            | 7         | 0.28%   |
| LMDE          | 7         | 0.28%   |
| Endless       | 7         | 0.28%   |
| BlackPanther  | 7         | 0.28%   |
| SteamOS       | 6         | 0.24%   |
| Artix         | 6         | 0.24%   |
| RHEL          | 5         | 0.2%    |
| NixOS         | 5         | 0.2%    |
| Void Linux    | 4         | 0.16%   |
| TUXEDO OS     | 4         | 0.16%   |
| Parrot        | 4         | 0.16%   |
| Garuda Linux  | 4         | 0.16%   |
| Xero          | 3         | 0.12%   |
| Virtuozzo     | 3         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 4.15.0-88-generic        | 44        | 1.46%   |
| 5.16.7-desktop-1omv4003  | 38        | 1.26%   |
| 5.15.0-67-generic        | 35        | 1.16%   |
| 5.15.0-58-generic        | 33        | 1.1%    |
| 5.4.0-42-generic         | 32        | 1.06%   |
| 5.15.0-56-generic        | 31        | 1.03%   |
| 5.15.0-69-generic        | 30        | 1%      |
| 5.10.14-desktop-1omv4002 | 30        | 1%      |
| 4.15.0-91-generic        | 27        | 0.9%    |
| 5.15.0-46-generic        | 25        | 0.83%   |
| 5.4.0-52-generic         | 22        | 0.73%   |
| 5.4.0-48-generic         | 22        | 0.73%   |
| 5.19.0-35-generic        | 22        | 0.73%   |
| 4.15.0-96-generic        | 22        | 0.73%   |
| 5.4.0-58-generic         | 21        | 0.7%    |
| 6.1.1-desktop-1omv2290   | 20        | 0.67%   |
| 5.10.0-8-arm64           | 17        | 0.57%   |
| 6.2.6-desktop-1omv2390   | 16        | 0.53%   |
| 5.8.0-43-generic         | 15        | 0.5%    |
| 5.4.0-91-generic         | 15        | 0.5%    |
| 5.15.0-60-generic        | 15        | 0.5%    |
| 5.10.0-21-amd64          | 15        | 0.5%    |
| 5.13.0-35-generic        | 14        | 0.47%   |
| 5.4.0-80-generic         | 13        | 0.43%   |
| 5.4.0-26-generic         | 13        | 0.43%   |
| 5.15.0-52-generic        | 13        | 0.43%   |
| 5.11.0-43-generic        | 13        | 0.43%   |
| 5.11.0-27-generic        | 13        | 0.43%   |
| 6.2.0-26-generic         | 12        | 0.4%    |
| 5.4.0-81-generic         | 12        | 0.4%    |
| 5.4.0-47-generic         | 12        | 0.4%    |
| 5.15.0-48-generic        | 12        | 0.4%    |
| 5.15.0-43-generic        | 12        | 0.4%    |
| 5.13.0-39-generic        | 12        | 0.4%    |
| 5.13.0-30-generic        | 12        | 0.4%    |
| 5.10.0-8-amd64           | 12        | 0.4%    |
| 5.0.0-37-generic         | 12        | 0.4%    |
| 6.2.0-37-generic         | 11        | 0.37%   |
| 5.8.0-55-generic         | 11        | 0.37%   |
| 5.8.0-53-generic         | 11        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 381       | 13.59%  |
| 5.15.0  | 346       | 12.34%  |
| 4.15.0  | 207       | 7.38%   |
| 5.8.0   | 129       | 4.6%    |
| 5.11.0  | 117       | 4.17%   |
| 5.13.0  | 108       | 3.85%   |
| 5.10.0  | 98        | 3.5%    |
| 5.19.0  | 85        | 3.03%   |
| 6.2.0   | 82        | 2.93%   |
| 5.3.0   | 72        | 2.57%   |
| 5.0.0   | 50        | 1.78%   |
| 4.18.0  | 42        | 1.5%    |
| 6.1.0   | 39        | 1.39%   |
| 5.16.7  | 39        | 1.39%   |
| 4.19.0  | 38        | 1.36%   |
| 5.10.14 | 31        | 1.11%   |
| 6.5.0   | 26        | 0.93%   |
| 6.1.1   | 24        | 0.86%   |
| 6.2.6   | 22        | 0.78%   |
| 5.14.0  | 16        | 0.57%   |
| 5.17.5  | 13        | 0.46%   |
| 6.0.0   | 12        | 0.43%   |
| 5.6.0   | 11        | 0.39%   |
| 6.4.11  | 9         | 0.32%   |
| 5.7.0   | 9         | 0.32%   |
| 5.18.0  | 9         | 0.32%   |
| 5.16.13 | 8         | 0.29%   |
| 3.10.0  | 8         | 0.29%   |
| 6.0.12  | 7         | 0.25%   |
| 5.10.7  | 7         | 0.25%   |
| 4.9.60  | 7         | 0.25%   |
| 6.5.6   | 6         | 0.21%   |
| 6.5.5   | 6         | 0.21%   |
| 6.5.4   | 6         | 0.21%   |
| 6.3.5   | 6         | 0.21%   |
| 6.0.7   | 6         | 0.21%   |
| 6.0.15  | 6         | 0.21%   |
| 5.6.14  | 6         | 0.21%   |
| 5.3.18  | 6         | 0.21%   |
| 5.16.0  | 6         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 400       | 14.51%  |
| 5.15    | 400       | 14.51%  |
| 4.15    | 208       | 7.55%   |
| 5.10    | 170       | 6.17%   |
| 5.8     | 162       | 5.88%   |
| 5.11    | 146       | 5.3%    |
| 6.2     | 127       | 4.61%   |
| 5.13    | 125       | 4.54%   |
| 5.19    | 98        | 3.56%   |
| 6.1     | 97        | 3.52%   |
| 5.3     | 85        | 3.08%   |
| 5.16    | 75        | 2.72%   |
| 6.5     | 64        | 2.32%   |
| 5.0     | 55        | 2%      |
| 6.0     | 50        | 1.81%   |
| 4.18    | 50        | 1.81%   |
| 4.19    | 45        | 1.63%   |
| 5.6     | 41        | 1.49%   |
| 5.14    | 41        | 1.49%   |
| 5.17    | 39        | 1.42%   |
| 6.4     | 31        | 1.12%   |
| 6.6     | 29        | 1.05%   |
| 5.9     | 29        | 1.05%   |
| 5.7     | 29        | 1.05%   |
| 6.3     | 28        | 1.02%   |
| 5.18    | 28        | 1.02%   |
| 5.12    | 25        | 0.91%   |
| 4.9     | 23        | 0.83%   |
| 5.5     | 11        | 0.4%    |
| 3.10    | 8         | 0.29%   |
| 4.4     | 5         | 0.18%   |
| 4.14    | 4         | 0.15%   |
| 5.2     | 3         | 0.11%   |
| 4.20    | 3         | 0.11%   |
| 4.13    | 3         | 0.11%   |
| 4.1     | 3         | 0.11%   |
| 2.6     | 3         | 0.11%   |
| 4.10    | 2         | 0.07%   |
| 3.16    | 2         | 0.07%   |
| 6.7     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2299      | 96.84%  |
| aarch64 | 40        | 1.68%   |
| i686    | 33        | 1.39%   |
| armv8l  | 1         | 0.04%   |
| armv7l  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1010      | 40.74%  |
| KDE5            | 380       | 15.33%  |
| Unknown         | 324       | 13.07%  |
| X-Cinnamon      | 184       | 7.42%   |
| GNUstep         | 153       | 6.17%   |
| XFCE            | 124       | 5%      |
| MATE            | 63        | 2.54%   |
| KDE             | 44        | 1.77%   |
| Cinnamon        | 35        | 1.41%   |
| LXQt            | 23        | 0.93%   |
| Pantheon        | 20        | 0.81%   |
| i3              | 20        | 0.81%   |
| KDE4            | 17        | 0.69%   |
| LXDE            | 16        | 0.65%   |
| Budgie          | 16        | 0.65%   |
| GNOME Flashback | 15        | 0.61%   |
| Unity           | 7         | 0.28%   |
| bspwm           | 5         | 0.2%    |
| qtile           | 4         | 0.16%   |
| Trinity         | 2         | 0.08%   |
| sway            | 2         | 0.08%   |
| ICEWM           | 2         | 0.08%   |
| Hyprland        | 2         | 0.08%   |
| GNOME Classic   | 2         | 0.08%   |
| DWM             | 2         | 0.08%   |
| xmonad          | 1         | 0.04%   |
| openbox         | 1         | 0.04%   |
| none+awesome    | 1         | 0.04%   |
| herbstluftwm    | 1         | 0.04%   |
| fluxbox         | 1         | 0.04%   |
| Deepin          | 1         | 0.04%   |
| awesome         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1674      | 66.59%  |
| Wayland | 488       | 19.41%  |
| Unknown | 182       | 7.24%   |
| Tty     | 166       | 6.6%    |
| Web     | 4         | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1017      | 40.76%  |
| LightDM | 431       | 17.27%  |
| SDDM    | 327       | 13.11%  |
| GDM3    | 315       | 12.63%  |
| GDM     | 299       | 11.98%  |
| TDM     | 80        | 3.21%   |
| KDM     | 15        | 0.6%    |
| XDM     | 4         | 0.16%   |
| SLiM    | 4         | 0.16%   |
| NODM    | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |
| GREETD  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 888       | 35.63%  |
| de_CH      | 569       | 22.83%  |
| Unknown    | 355       | 14.25%  |
| fr_CH      | 170       | 6.82%   |
| de_DE      | 166       | 6.66%   |
| en_GB      | 109       | 4.37%   |
| fr_FR      | 55        | 2.21%   |
| C          | 50        | 2.01%   |
| it_CH      | 21        | 0.84%   |
| it_IT      | 20        | 0.8%    |
| pt_PT      | 17        | 0.68%   |
| es_ES      | 11        | 0.44%   |
| pl_PL      | 9         | 0.36%   |
| ru_RU      | 8         | 0.32%   |
| en_CH      | 8         | 0.32%   |
| en_AU      | 5         | 0.2%    |
| de_AT      | 4         | 0.16%   |
| POSIX      | 3         | 0.12%   |
| en_IE      | 3         | 0.12%   |
| en_CA      | 2         | 0.08%   |
| en_AG      | 2         | 0.08%   |
| de_IT      | 2         | 0.08%   |
| tr_TR      | 1         | 0.04%   |
| sk_SK      | 1         | 0.04%   |
| ru_UA      | 1         | 0.04%   |
| pt_BR      | 1         | 0.04%   |
| nl_BE      | 1         | 0.04%   |
| hu_HU      | 1         | 0.04%   |
| hsb_DE     | 1         | 0.04%   |
| gsw_CH     | 1         | 0.04%   |
| fr_CA      | 1         | 0.04%   |
| fi_FI      | 1         | 0.04%   |
| de_LI      | 1         | 0.04%   |
| de_CH.UTF8 | 1         | 0.04%   |
| cs_CZ      | 1         | 0.04%   |
| ca_ES      | 1         | 0.04%   |
| C.UTF8     | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1382      | 56.87%  |
| BIOS | 1048      | 43.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1865      | 76.18%  |
| Btrfs   | 234       | 9.56%   |
| Overlay | 151       | 6.17%   |
| Unknown | 65        | 2.66%   |
| Tmpfs   | 58        | 2.37%   |
| Xfs     | 42        | 1.72%   |
| Zfs     | 14        | 0.57%   |
| Ext3    | 6         | 0.25%   |
| Ext2    | 6         | 0.25%   |
| F2fs    | 4         | 0.16%   |
| Jfs     | 1         | 0.04%   |
| ExX4    | 1         | 0.04%   |
| Aufs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1173      | 48.11%  |
| Unknown | 1011      | 41.47%  |
| MBR     | 254       | 10.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2063      | 84.93%  |
| Yes       | 366       | 15.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1822      | 75.38%  |
| Yes       | 595       | 24.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 439       | 18.51%  |
| Lenovo                  | 400       | 16.86%  |
| Hewlett-Packard         | 397       | 16.74%  |
| Dell                    | 192       | 8.09%   |
| Acer                    | 131       | 5.52%   |
| Apple                   | 102       | 4.3%    |
| Gigabyte Technology     | 101       | 4.26%   |
| MSI                     | 79        | 3.33%   |
| Intel                   | 70        | 2.95%   |
| ASRock                  | 70        | 2.95%   |
| Fujitsu                 | 43        | 1.81%   |
| Raspberry Pi Foundation | 34        | 1.43%   |
| Medion                  | 33        | 1.39%   |
| Supermicro              | 19        | 0.8%    |
| Microsoft               | 19        | 0.8%    |
| Toshiba                 | 18        | 0.76%   |
| Sony                    | 18        | 0.76%   |
| TUXEDO                  | 14        | 0.59%   |
| Notebook                | 13        | 0.55%   |
| Samsung Electronics     | 12        | 0.51%   |
| Unknown                 | 12        | 0.51%   |
| HUAWEI                  | 10        | 0.42%   |
| Shuttle                 | 9         | 0.38%   |
| ZOTAC                   | 8         | 0.34%   |
| TrekStor                | 7         | 0.3%    |
| Pegatron                | 7         | 0.3%    |
| PC Engines              | 7         | 0.3%    |
| Razer                   | 6         | 0.25%   |
| DALCO AG Switzerland    | 6         | 0.25%   |
| Alienware               | 6         | 0.25%   |
| Valve                   | 5         | 0.21%   |
| Schenker                | 5         | 0.21%   |
| Packard Bell            | 5         | 0.21%   |
| Biostar                 | 4         | 0.17%   |
| AMI                     | 4         | 0.17%   |
| Timi                    | 3         | 0.13%   |
| System76                | 3         | 0.13%   |
| PC Specialist           | 3         | 0.13%   |
| GPD                     | 3         | 0.13%   |
| Fujitsu Siemens         | 3         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS All Series                       | 38        | 1.6%    |
| Unknown                               | 20        | 0.84%   |
| ASUS PRIME Z590-P                     | 17        | 0.72%   |
| Fujitsu CELSIUS_W550                  | 12        | 0.51%   |
| ASUS PRIME X570-PRO                   | 12        | 0.51%   |
| ASUS ROG STRIX X570-E GAMING          | 11        | 0.46%   |
| RPi Raspberry Pi 4 Model B Rev 1.2    | 10        | 0.42%   |
| ASUS PRIME B550M-A                    | 10        | 0.42%   |
| RPi Raspberry Pi 4 Model B Rev 1.1    | 9         | 0.38%   |
| RPi Raspberry Pi 3 Model B Rev 1.2    | 8         | 0.34%   |
| MSI MS-7C02                           | 8         | 0.34%   |
| HP Pavilion dv7                       | 8         | 0.34%   |
| ASUS STRIX Z270F GAMING               | 8         | 0.34%   |
| Dell Latitude 7490                    | 7         | 0.3%    |
| ASUS P9X79 WS                         | 7         | 0.3%    |
| ASUS P8Z77-V LX                       | 7         | 0.3%    |
| Microsoft Surface Pro 4               | 6         | 0.25%   |
| HP Pavilion dv6                       | 6         | 0.25%   |
| HP Notebook                           | 6         | 0.25%   |
| DALCO AG Switzerland +41 44 908 38 38 | 6         | 0.25%   |
| Apple MacPro5,1                       | 6         | 0.25%   |
| Apple MacBookPro8,1                   | 6         | 0.25%   |
| Apple iMac12,2                        | 6         | 0.25%   |
| Valve Jupiter                         | 5         | 0.21%   |
| PC Engines APU2                       | 5         | 0.21%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU     | 5         | 0.21%   |
| Intel S4600LH                         | 5         | 0.21%   |
| Intel DP67BA AAG10219-303             | 5         | 0.21%   |
| HP ENVY 15                            | 5         | 0.21%   |
| HP EliteDesk 800 G1 SFF               | 5         | 0.21%   |
| Fujitsu CELSIUS W570                  | 5         | 0.21%   |
| Dell XPS 15 9570                      | 5         | 0.21%   |
| Dell XPS 13 9370                      | 5         | 0.21%   |
| Dell OptiPlex 9020                    | 5         | 0.21%   |
| Dell OptiPlex 790                     | 5         | 0.21%   |
| Dell OptiPlex 7010                    | 5         | 0.21%   |
| Dell Latitude E7240                   | 5         | 0.21%   |
| ASUS ROG STRIX Z370-F GAMING          | 5         | 0.21%   |
| Apple MacBookPro9,2                   | 5         | 0.21%   |
| Apple iMac8,1                         | 5         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 248       | 10.46%  |
| ASUS ROG           | 83        | 3.5%    |
| Acer Aspire        | 78        | 3.29%   |
| ASUS PRIME         | 77        | 3.25%   |
| HP EliteBook       | 72        | 3.04%   |
| HP Pavilion        | 63        | 2.66%   |
| Dell XPS           | 59        | 2.49%   |
| Dell Latitude      | 56        | 2.36%   |
| Lenovo Yoga        | 41        | 1.73%   |
| HP ProBook         | 40        | 1.69%   |
| HP ENVY            | 38        | 1.6%    |
| ASUS All           | 38        | 1.6%    |
| RPi Raspberry      | 34        | 1.43%   |
| Dell OptiPlex      | 34        | 1.43%   |
| Fujitsu CELSIUS    | 28        | 1.18%   |
| HP Compaq          | 27        | 1.14%   |
| Lenovo IdeaPad     | 25        | 1.05%   |
| HP EliteDesk       | 23        | 0.97%   |
| ASUS TUF           | 22        | 0.93%   |
| HP Laptop          | 21        | 0.89%   |
| ASUS VivoBook      | 21        | 0.89%   |
| Unknown            | 20        | 0.84%   |
| Microsoft Surface  | 19        | 0.8%    |
| HP ZBook           | 16        | 0.67%   |
| Dell Inspiron      | 15        | 0.63%   |
| Acer Swift         | 15        | 0.63%   |
| Lenovo IdeaPadFlex | 14        | 0.59%   |
| Dell Precision     | 14        | 0.59%   |
| Toshiba Satellite  | 12        | 0.51%   |
| Lenovo ThinkCentre | 12        | 0.51%   |
| HP Spectre         | 11        | 0.46%   |
| ASUS ZenBook       | 11        | 0.46%   |
| Lenovo Legion      | 10        | 0.42%   |
| ASUS STRIX         | 10        | 0.42%   |
| HP ProLiant        | 9         | 0.38%   |
| HP ProDesk         | 9         | 0.38%   |
| HP OMEN            | 9         | 0.38%   |
| Gigabyte X570      | 9         | 0.38%   |
| ASUS P9X79         | 9         | 0.38%   |
| Apple iMac12       | 9         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 233       | 9.82%   |
| 2020    | 227       | 9.57%   |
| 2019    | 227       | 9.57%   |
| 2017    | 182       | 7.67%   |
| 2012    | 172       | 7.25%   |
| 2021    | 169       | 7.12%   |
| 2011    | 148       | 6.24%   |
| 2014    | 142       | 5.99%   |
| 2013    | 142       | 5.99%   |
| 2015    | 133       | 5.61%   |
| 2016    | 117       | 4.93%   |
| 2022    | 110       | 4.64%   |
| 2010    | 106       | 4.47%   |
| 2008    | 67        | 2.82%   |
| 2009    | 61        | 2.57%   |
| 2023    | 42        | 1.77%   |
| 2007    | 38        | 1.6%    |
| Unknown | 29        | 1.22%   |
| 2006    | 17        | 0.72%   |
| 2005    | 6         | 0.25%   |
| 2004    | 3         | 0.13%   |
| 2003    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1093      | 46.08%  |
| Desktop        | 891       | 37.56%  |
| Convertible    | 137       | 5.78%   |
| Mini pc        | 59        | 2.49%   |
| All in one     | 57        | 2.4%    |
| Server         | 51        | 2.15%   |
| Tablet         | 42        | 1.77%   |
| System on chip | 39        | 1.64%   |
| Phone          | 3         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2168      | 90.6%   |
| Enabled  | 225       | 9.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2356      | 99.33%  |
| Yes  | 16        | 0.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 593       | 24.52%  |
| 4.01-8.0        | 399       | 16.5%   |
| 32.01-64.0      | 398       | 16.46%  |
| 8.01-16.0       | 382       | 15.8%   |
| 3.01-4.0        | 285       | 11.79%  |
| 64.01-256.0     | 169       | 6.99%   |
| 24.01-32.0      | 65        | 2.69%   |
| 1.01-2.0        | 59        | 2.44%   |
| More than 256.0 | 28        | 1.16%   |
| 0.51-1.0        | 22        | 0.91%   |
| 2.01-3.0        | 17        | 0.7%    |
| 0.01-0.5        | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 812       | 30.07%  |
| 2.01-3.0        | 604       | 22.37%  |
| 4.01-8.0        | 469       | 17.37%  |
| 3.01-4.0        | 332       | 12.3%   |
| 8.01-16.0       | 187       | 6.93%   |
| 0.51-1.0        | 182       | 6.74%   |
| 0.01-0.5        | 45        | 1.67%   |
| 16.01-24.0      | 33        | 1.22%   |
| 24.01-32.0      | 11        | 0.41%   |
| 32.01-64.0      | 10        | 0.37%   |
| 64.01-256.0     | 9         | 0.33%   |
| Unknown         | 4         | 0.15%   |
| More than 256.0 | 2         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1479      | 60.07%  |
| 2       | 579       | 23.52%  |
| 3       | 209       | 8.49%   |
| 4       | 80        | 3.25%   |
| 5       | 47        | 1.91%   |
| 6       | 23        | 0.93%   |
| 0       | 22        | 0.89%   |
| 7       | 17        | 0.69%   |
| 14      | 2         | 0.08%   |
| 11      | 1         | 0.04%   |
| 9       | 1         | 0.04%   |
| 8       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1586      | 66.11%  |
| Yes       | 813       | 33.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2025      | 84.73%  |
| No        | 365       | 15.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1725      | 72.3%   |
| No        | 661       | 27.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1460      | 60.76%  |
| No        | 943       | 39.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Switzerland | 2372      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Zurich                             | 671       | 25.87%  |
| Bern                               | 120       | 4.63%   |
| Geneva                             | 100       | 3.86%   |
| Lucerne                            | 69        | 2.66%   |
| Lausanne                           | 47        | 1.81%   |
| Basel                              | 44        | 1.7%    |
| Winterthur                         | 37        | 1.43%   |
| Wiesendangen / Wiesendangen (Dorf) | 33        | 1.27%   |
| Neuchatel                          | 30        | 1.16%   |
| Thun                               | 27        | 1.04%   |
| Lugano                             | 21        | 0.81%   |
| St. Gallen                         | 20        | 0.77%   |
| Lyss                               | 20        | 0.77%   |
| Dietikon                           | 20        | 0.77%   |
| Wil                                | 18        | 0.69%   |
| Herrliberg                         | 16        | 0.62%   |
| Biel/Bienne                        | 16        | 0.62%   |
| Sion                               | 13        | 0.5%    |
| Ittigen                            | 13        | 0.5%    |
| Aarau                              | 13        | 0.5%    |
| Wettingen                          | 12        | 0.46%   |
| Onex                               | 12        | 0.46%   |
| Munchenstein                       | 12        | 0.46%   |
| Dubendorf                          | 12        | 0.46%   |
| Zweidlen-Dorf                      | 11        | 0.42%   |
| Aarburg                            | 11        | 0.42%   |
| Solothurn                          | 10        | 0.39%   |
| Willisau                           | 9         | 0.35%   |
| Wetzikon                           | 9         | 0.35%   |
| Uster                              | 9         | 0.35%   |
| Schaffhausen                       | 9         | 0.35%   |
| Oberwil-Lieli                      | 9         | 0.35%   |
| Kloten                             | 9         | 0.35%   |
| Glattbrugg                         | 9         | 0.35%   |
| Bulle                              | 9         | 0.35%   |
| Baden                              | 9         | 0.35%   |
| Zug                                | 8         | 0.31%   |
| Zollikofen                         | 8         | 0.31%   |
| Widnau                             | 8         | 0.31%   |
| Wallisellen                        | 8         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 897       | 1598   | 26.56%  |
| WDC                         | 460       | 752    | 13.62%  |
| Seagate                     | 381       | 556    | 11.28%  |
| SanDisk                     | 183       | 236    | 5.42%   |
| Toshiba                     | 164       | 232    | 4.86%   |
| Unknown                     | 153       | 232    | 4.53%   |
| Intel                       | 143       | 210    | 4.23%   |
| SK hynix                    | 112       | 136    | 3.32%   |
| Hitachi                     | 105       | 143    | 3.11%   |
| Kingston                    | 102       | 146    | 3.02%   |
| Crucial                     | 97        | 135    | 2.87%   |
| Micron Technology           | 69        | 87     | 2.04%   |
| Apple                       | 48        | 54     | 1.42%   |
| HGST                        | 38        | 48     | 1.13%   |
| Corsair                     | 27        | 32     | 0.8%    |
| OCZ                         | 25        | 30     | 0.74%   |
| A-DATA Technology           | 24        | 36     | 0.71%   |
| Intenso                     | 22        | 24     | 0.65%   |
| Phison                      | 21        | 32     | 0.62%   |
| LITEON                      | 19        | 25     | 0.56%   |
| Phison Electronics          | 17        | 28     | 0.5%    |
| LITEONIT                    | 16        | 18     | 0.47%   |
| KIOXIA                      | 15        | 24     | 0.44%   |
| China                       | 14        | 16     | 0.41%   |
| Transcend                   | 13        | 23     | 0.38%   |
| ASMT                        | 10        | 15     | 0.3%    |
| SPCC                        | 9         | 10     | 0.27%   |
| Hewlett-Packard             | 9         | 11     | 0.27%   |
| Unknown                     | 9         | 11     | 0.27%   |
| Silicon Motion              | 8         | 9      | 0.24%   |
| Kingston Technology Company | 8         | 9      | 0.24%   |
| KingSpec                    | 8         | 13     | 0.24%   |
| JMicron Technology          | 8         | 8      | 0.24%   |
| Plextor                     | 7         | 8      | 0.21%   |
| LaCie                       | 7         | 7      | 0.21%   |
| Fujitsu                     | 7         | 10     | 0.21%   |
| Patriot                     | 6         | 7      | 0.18%   |
| Micron/Crucial Technology   | 6         | 9      | 0.18%   |
| Maxtor                      | 5         | 7      | 0.15%   |
| HPE                         | 5         | 12     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 500GB                           | 47        | 1.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 43        | 1.13%   |
| Samsung SSD 850 EVO 250GB                           | 39        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 37        | 0.97%   |
| Samsung SSD 860 EVO 1TB                             | 35        | 0.92%   |
| Samsung NVMe SSD Drive 1TB                          | 34        | 0.89%   |
| Samsung SSD 860 EVO 500GB                           | 30        | 0.79%   |
| Samsung SSD 860 EVO 250GB                           | 28        | 0.74%   |
| Samsung SSD 980 PRO 1TB                             | 27        | 0.71%   |
| Samsung SSD 970 EVO Plus 1TB                        | 26        | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB                      | 25        | 0.66%   |
| Samsung NVMe SSD Drive 512GB                        | 24        | 0.63%   |
| Unknown MMC Card  32GB                              | 22        | 0.58%   |
| Samsung SSD 840 EVO 250GB                           | 22        | 0.58%   |
| Seagate ST2000DM006-2DM164 2TB                      | 19        | 0.5%    |
| Unknown MMC Card  64GB                              | 18        | 0.47%   |
| Unknown MMC Card  128GB                             | 18        | 0.47%   |
| Samsung SSD 850 EVO 1TB                             | 18        | 0.47%   |
| Samsung NVMe SSD Drive 500GB                        | 18        | 0.47%   |
| Samsung SSD 970 EVO Plus 500GB                      | 16        | 0.42%   |
| Samsung SSD 860 QVO 1TB                             | 16        | 0.42%   |
| Seagate Expansion 2TB                               | 15        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                          | 15        | 0.39%   |
| HGST HTS721010A9E630 1TB                            | 15        | 0.39%   |
| Toshiba DT01ACA100 1TB                              | 14        | 0.37%   |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 0.37%   |
| Samsung NVMe SSD Drive 1024GB                       | 14        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                         | 14        | 0.37%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 13        | 0.34%   |
| SK hynix NVMe SSD Drive 512GB                       | 13        | 0.34%   |
| Seagate ST4000DM004-2CV104 4TB                      | 13        | 0.34%   |
| Seagate ST2000DM001-1ER164 2TB                      | 13        | 0.34%   |
| Samsung SSD 970 EVO Plus 2TB                        | 13        | 0.34%   |
| Samsung SSD 850 PRO 256GB                           | 13        | 0.34%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 13        | 0.34%   |
| Samsung SSD 970 EVO 1TB                             | 12        | 0.32%   |
| Samsung SSD 870 EVO 500GB                           | 12        | 0.32%   |
| Samsung SSD 840 PRO Series 256GB                    | 12        | 0.32%   |
| Samsung HD103SJ 1TB                                 | 12        | 0.32%   |
| Crucial CT500MX500SSD1 500GB                        | 12        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 370       | 532    | 35.27%  |
| WDC                 | 345       | 581    | 32.89%  |
| Hitachi             | 105       | 143    | 10.01%  |
| Toshiba             | 86        | 114    | 8.2%    |
| Samsung Electronics | 42        | 64     | 4%      |
| HGST                | 38        | 48     | 3.62%   |
| Apple               | 13        | 13     | 1.24%   |
| Unknown             | 12        | 13     | 1.14%   |
| Fujitsu             | 7         | 10     | 0.67%   |
| Maxtor              | 5         | 7      | 0.48%   |
| Intenso             | 4         | 4      | 0.38%   |
| ASMT                | 3         | 4      | 0.29%   |
| Initio              | 2         | 2      | 0.19%   |
| Hewlett-Packard     | 2         | 4      | 0.19%   |
| External            | 2         | 2      | 0.19%   |
| USB3.0              | 1         | 2      | 0.1%    |
| USB                 | 1         | 2      | 0.1%    |
| Unknown (CF)        | 1         | 1      | 0.1%    |
| TO Exter            | 1         | 1      | 0.1%    |
| SABRENT             | 1         | 1      | 0.1%    |
| MARVELL             | 1         | 1      | 0.1%    |
| IET                 | 1         | 1      | 0.1%    |
| ICY BOX             | 1         | 1      | 0.1%    |
| HPE                 | 1         | 6      | 0.1%    |
| HGST HTS            | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 2      | 0.1%    |
| ASMT109x            | 1         | 1      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 477       | 812    | 39.68%  |
| SanDisk             | 99        | 125    | 8.24%   |
| Crucial             | 88        | 125    | 7.32%   |
| Kingston            | 75        | 112    | 6.24%   |
| WDC                 | 68        | 89     | 5.66%   |
| Intel               | 67        | 86     | 5.57%   |
| Micron Technology   | 33        | 44     | 2.75%   |
| Toshiba             | 27        | 40     | 2.25%   |
| Apple               | 27        | 29     | 2.25%   |
| OCZ                 | 25        | 30     | 2.08%   |
| SK hynix            | 21        | 25     | 1.75%   |
| LITEON              | 18        | 24     | 1.5%    |
| LITEONIT            | 16        | 18     | 1.33%   |
| Intenso             | 16        | 17     | 1.33%   |
| A-DATA Technology   | 15        | 24     | 1.25%   |
| China               | 14        | 16     | 1.16%   |
| Corsair             | 13        | 14     | 1.08%   |
| Transcend           | 12        | 22     | 1%      |
| KingSpec            | 8         | 13     | 0.67%   |
| SPCC                | 7         | 8      | 0.58%   |
| Plextor             | 7         | 8      | 0.58%   |
| Patriot             | 6         | 7      | 0.5%    |
| ASMT                | 6         | 10     | 0.5%    |
| JMicron Technology  | 5         | 5      | 0.42%   |
| Seagate             | 4         | 4      | 0.33%   |
| KIOXIA-EXCERIA      | 4         | 5      | 0.33%   |
| HPE                 | 3         | 4      | 0.25%   |
| Hewlett-Packard     | 3         | 4      | 0.25%   |
| PNY                 | 2         | 3      | 0.17%   |
| Phison              | 2         | 4      | 0.17%   |
| OWC                 | 2         | 2      | 0.17%   |
| Mushkin             | 2         | 2      | 0.17%   |
| Dogfish             | 2         | 3      | 0.17%   |
| Adaptec             | 2         | 2      | 0.17%   |
| XSTAR               | 1         | 1      | 0.08%   |
| WDC WDS1            | 1         | 1      | 0.08%   |
| WDC WDS             | 1         | 1      | 0.08%   |
| WALRAM              | 1         | 1      | 0.08%   |
| VERICO              | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1054      | 1766   | 34%     |
| NVMe    | 971       | 1511   | 31.32%  |
| HDD     | 887       | 1562   | 28.61%  |
| MMC     | 150       | 224    | 4.84%   |
| Unknown | 38        | 58     | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1540      | 3202   | 55%     |
| NVMe | 971       | 1509   | 34.68%  |
| MMC  | 150       | 224    | 5.36%   |
| SAS  | 139       | 186    | 4.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1037      | 1648   | 49.43%  |
| 0.51-1.0   | 591       | 942    | 28.17%  |
| 1.01-2.0   | 266       | 428    | 12.68%  |
| 3.01-4.0   | 90        | 144    | 4.29%   |
| 2.01-3.0   | 52        | 78     | 2.48%   |
| 4.01-10.0  | 43        | 59     | 2.05%   |
| 10.01-20.0 | 19        | 29     | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 577       | 22.58%  |
| 251-500        | 480       | 18.79%  |
| 501-1000       | 405       | 15.85%  |
| 1001-2000      | 275       | 10.76%  |
| More than 3000 | 193       | 7.55%   |
| 1-20           | 180       | 7.05%   |
| 51-100         | 122       | 4.77%   |
| 2001-3000      | 120       | 4.7%    |
| Unknown        | 120       | 4.7%    |
| 21-50          | 83        | 3.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 883       | 33.18%  |
| 21-50          | 348       | 13.08%  |
| 101-250        | 340       | 12.78%  |
| 51-100         | 300       | 11.27%  |
| 251-500        | 239       | 8.98%   |
| 501-1000       | 200       | 7.52%   |
| Unknown        | 120       | 4.51%   |
| 1001-2000      | 115       | 4.32%   |
| More than 3000 | 82        | 3.08%   |
| 2001-3000      | 34        | 1.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD3000HLHX-01JJPV0 304GB          | 2         | 2      | 1.24%   |
| WDC WD20EARS-00J99B0 2TB              | 2         | 2      | 1.24%   |
| WDC WD10EARS-00Y5B1 1TB               | 2         | 2      | 1.24%   |
| WDC WD10EADS-00L5B1 1TB               | 2         | 2      | 1.24%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 2         | 2      | 1.24%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 1.24%   |
| Seagate ST3250310AS 250GB             | 2         | 2      | 1.24%   |
| Seagate ST31500341AS 1TB              | 2         | 5      | 1.24%   |
| Samsung Electronics SSD 850 EVO 1TB   | 2         | 2      | 1.24%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 3      | 1.24%   |
| Initio 3639S 500GB                    | 2         | 2      | 1.24%   |
| Hitachi HUA722020ALA330 2TB           | 2         | 2      | 1.24%   |
| Hitachi HTS545050B9SA00 500GB         | 2         | 2      | 1.24%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 2      | 1.24%   |
| XSTAR SSD 128GB                       | 1         | 1      | 0.62%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 0.62%   |
| WDC WD5000BEVT-55A0RT0 500GB          | 1         | 1      | 0.62%   |
| WDC WD5000AAKS-65A7B0 500GB           | 1         | 1      | 0.62%   |
| WDC WD5000AAKS-00TMA0 500GB           | 1         | 2      | 0.62%   |
| WDC WD5000AAKS-00E4A0 500GB           | 1         | 1      | 0.62%   |
| WDC WD40PURX-64GVNY0 4TB              | 1         | 1      | 0.62%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1         | 1      | 0.62%   |
| WDC WD40EFRX-68N32N0 4TB              | 1         | 2      | 0.62%   |
| WDC WD4003FZEX-00Z4SA0 4TB            | 1         | 2      | 0.62%   |
| WDC WD3200AAKS-00B3A0 320GB           | 1         | 1      | 0.62%   |
| WDC WD3200AAJS-40VWA1 320GB           | 1         | 1      | 0.62%   |
| WDC WD30EZRX-00D8PB0 3TB              | 1         | 1      | 0.62%   |
| WDC WD2502ABYS-01B7A0 256GB           | 1         | 1      | 0.62%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1         | 1      | 0.62%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1         | 2      | 0.62%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1         | 1      | 0.62%   |
| WDC WD20EARS-00J2GB0 2TB              | 1         | 1      | 0.62%   |
| WDC WD1600BEKT-60A25T1 160GB          | 1         | 1      | 0.62%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1         | 1      | 0.62%   |
| WDC WD10EADS-22M2B0 1TB               | 1         | 1      | 0.62%   |
| WDC WD10EADS-11M2B3 1TB               | 1         | 1      | 0.62%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1         | 1      | 0.62%   |
| WDC WD1001FALS-403AA0 1TB             | 1         | 1      | 0.62%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 1         | 1      | 0.62%   |
| Toshiba THNSN5256GPUK 256GB           | 1         | 1      | 0.62%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 36     | 19.5%   |
| Seagate             | 22        | 33     | 13.84%  |
| Samsung Electronics | 19        | 22     | 11.95%  |
| Hitachi             | 15        | 16     | 9.43%   |
| SK hynix            | 11        | 12     | 6.92%   |
| Toshiba             | 10        | 13     | 6.29%   |
| Intel               | 8         | 9      | 5.03%   |
| SanDisk             | 6         | 7      | 3.77%   |
| Kingston            | 6         | 7      | 3.77%   |
| Micron Technology   | 5         | 6      | 3.14%   |
| HGST                | 5         | 5      | 3.14%   |
| OCZ                 | 3         | 4      | 1.89%   |
| A-DATA Technology   | 3         | 5      | 1.89%   |
| Intenso             | 2         | 2      | 1.26%   |
| Initio              | 2         | 2      | 1.26%   |
| Crucial             | 2         | 2      | 1.26%   |
| Apple               | 2         | 2      | 1.26%   |
| XSTAR               | 1         | 1      | 0.63%   |
| Patriot             | 1         | 2      | 0.63%   |
| Maxtor              | 1         | 1      | 0.63%   |
| LITEONIT            | 1         | 1      | 0.63%   |
| Fujitsu             | 1         | 1      | 0.63%   |
| China               | 1         | 1      | 0.63%   |
| ASMedia             | 1         | 1      | 0.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 29        | 34     | 31.52%  |
| Seagate             | 22        | 33     | 23.91%  |
| Hitachi             | 15        | 16     | 16.3%   |
| Toshiba             | 9         | 12     | 9.78%   |
| Samsung Electronics | 5         | 6      | 5.43%   |
| HGST                | 5         | 5      | 5.43%   |
| Initio              | 2         | 2      | 2.17%   |
| Apple               | 2         | 2      | 2.17%   |
| Maxtor              | 1         | 1      | 1.09%   |
| Fujitsu             | 1         | 1      | 1.09%   |
| ASMedia             | 1         | 1      | 1.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 84        | 113    | 55.63%  |
| SSD  | 56        | 66     | 37.09%  |
| NVMe | 11        | 12     | 7.28%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3750528AS 752GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1316      | 2726   | 50.73%  |
| Works    | 1134      | 2203   | 43.72%  |
| Malfunc  | 143       | 191    | 5.51%   |
| Failed   | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1528      | 49.12%  |
| Samsung Electronics            | 481       | 15.46%  |
| AMD                            | 356       | 11.44%  |
| SanDisk                        | 135       | 4.34%   |
| SK hynix                       | 83        | 2.67%   |
| ASMedia Technology             | 66        | 2.12%   |
| Marvell Technology Group       | 61        | 1.96%   |
| Toshiba America Info Systems   | 56        | 1.8%    |
| Phison Electronics             | 51        | 1.64%   |
| Micron Technology              | 37        | 1.19%   |
| Kingston Technology Company    | 37        | 1.19%   |
| JMicron Technology             | 35        | 1.13%   |
| Nvidia                         | 34        | 1.09%   |
| LSI Logic / Symbios Logic      | 16        | 0.51%   |
| Silicon Motion                 | 14        | 0.45%   |
| KIOXIA                         | 14        | 0.45%   |
| Micron/Crucial Technology      | 13        | 0.42%   |
| Areca Technology               | 13        | 0.42%   |
| ADATA Technology               | 12        | 0.39%   |
| Seagate Technology             | 11        | 0.35%   |
| Hewlett-Packard                | 8         | 0.26%   |
| Broadcom / LSI                 | 8         | 0.26%   |
| Solid State Storage Technology | 6         | 0.19%   |
| Apple                          | 6         | 0.19%   |
| Realtek Semiconductor          | 5         | 0.16%   |
| Union Memory (Shenzhen)        | 4         | 0.13%   |
| Lite-On Technology             | 4         | 0.13%   |
| Lenovo                         | 4         | 0.13%   |
| Adaptec                        | 4         | 0.13%   |
| VIA Technologies               | 3         | 0.1%    |
| Silicon Image                  | 2         | 0.06%   |
| Transcend                      | 1         | 0.03%   |
| Tekram Technology              | 1         | 0.03%   |
| Shenzhen Longsys Electronics   | 1         | 0.03%   |
| Biwin Storage Technology       | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 244       | 6.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 237       | 6.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 119       | 3.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 108       | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 101       | 2.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 93        | 2.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 72        | 2.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 66        | 1.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 64        | 1.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 63        | 1.79%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 62        | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 61        | 1.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 57        | 1.62%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 56        | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 53        | 1.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 52        | 1.48%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 45        | 1.28%   |
| AMD 400 Series Chipset SATA Controller                                         | 45        | 1.28%   |
| Intel SATA Controller [RAID mode]                                              | 44        | 1.25%   |
| AMD 500 Series Chipset SATA Controller                                         | 42        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 38        | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 37        | 1.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 36        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 36        | 1.03%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 34        | 0.97%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 32        | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                          | 32        | 0.91%   |
| Intel SSD 660P Series                                                          | 31        | 0.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 29        | 0.83%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 28        | 0.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 27        | 0.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 27        | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 25        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 24        | 0.68%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 23        | 0.66%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 23        | 0.66%   |
| Phison E12 NVMe Controller                                                     | 23        | 0.66%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 23        | 0.66%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 23        | 0.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 22        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1617      | 52.55%  |
| NVMe | 977       | 31.75%  |
| RAID | 238       | 7.73%   |
| IDE  | 218       | 7.08%   |
| SAS  | 26        | 0.84%   |
| SCSI | 1         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1849      | 77.95%  |
| AMD          | 478       | 20.15%  |
| ARM          | 39        | 1.64%   |
| QUALCOMM     | 2         | 0.08%   |
| CentaurHauls | 2         | 0.08%   |
| Unknown      | 2         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 50        | 2.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 47        | 1.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 46        | 1.94%   |
| ARM Processor                              | 38        | 1.6%    |
| Intel Core i7-6700 CPU @ 3.40GHz           | 24        | 1.01%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 23        | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 22        | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 22        | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 21        | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 21        | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 21        | 0.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 20        | 0.84%   |
| Intel Core i7-2600 CPU @ 3.40GHz           | 20        | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 18        | 0.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 17        | 0.72%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 17        | 0.72%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 17        | 0.72%   |
| AMD Ryzen 5 3600 6-Core Processor          | 17        | 0.72%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 16        | 0.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 16        | 0.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 16        | 0.67%   |
| Intel 11th Gen Core i9-11900F @ 2.50GHz    | 16        | 0.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 15        | 0.63%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 15        | 0.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 15        | 0.63%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 14        | 0.59%   |
| Intel 12th Gen Core i7-1260P               | 14        | 0.59%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 13        | 0.55%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 13        | 0.55%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz          | 13        | 0.55%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 13        | 0.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 12        | 0.51%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 12        | 0.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 12        | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 12        | 0.51%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 11        | 0.46%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 11        | 0.46%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 11        | 0.46%   |
| Intel Core i7-6500U CPU @ 2.50GHz          | 11        | 0.46%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 11        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 733       | 30.89%  |
| Intel Core i5           | 459       | 19.34%  |
| Other                   | 254       | 10.7%   |
| AMD Ryzen 7             | 132       | 5.56%   |
| AMD Ryzen 5             | 93        | 3.92%   |
| Intel Xeon              | 92        | 3.88%   |
| Intel Core 2 Duo        | 79        | 3.33%   |
| AMD Ryzen 9             | 63        | 2.65%   |
| Intel Core i3           | 59        | 2.49%   |
| Intel Celeron           | 56        | 2.36%   |
| Intel Atom              | 36        | 1.52%   |
| Intel Pentium           | 30        | 1.26%   |
| AMD Ryzen 7 PRO         | 29        | 1.22%   |
| Intel Core i9           | 21        | 0.88%   |
| AMD FX                  | 20        | 0.84%   |
| AMD Ryzen Threadripper  | 18        | 0.76%   |
| Intel Core 2            | 15        | 0.63%   |
| Intel Pentium Dual-Core | 14        | 0.59%   |
| Intel Core 2 Quad       | 13        | 0.55%   |
| AMD Ryzen 3             | 10        | 0.42%   |
| AMD GX                  | 9         | 0.38%   |
| AMD A8                  | 9         | 0.38%   |
| AMD Quad-Core Opteron   | 8         | 0.34%   |
| AMD EPYC                | 8         | 0.34%   |
| Intel Xeon Gold         | 7         | 0.29%   |
| AMD Ryzen 5 PRO         | 6         | 0.25%   |
| AMD E                   | 6         | 0.25%   |
| Intel Pentium 4         | 5         | 0.21%   |
| AMD Phenom II X4        | 5         | 0.21%   |
| AMD Opteron             | 5         | 0.21%   |
| AMD Athlon              | 5         | 0.21%   |
| Intel Pentium Silver    | 4         | 0.17%   |
| Intel Genuine           | 4         | 0.17%   |
| Intel Core M            | 4         | 0.17%   |
| AMD Phenom II X6        | 4         | 0.17%   |
| AMD A10                 | 4         | 0.17%   |
| Intel Pentium M         | 3         | 0.13%   |
| AMD Phenom              | 3         | 0.13%   |
| AMD E2                  | 3         | 0.13%   |
| AMD E1                  | 3         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 976       | 41.09%  |
| 2       | 638       | 26.86%  |
| 8       | 279       | 11.75%  |
| 6       | 237       | 9.98%   |
| 12      | 77        | 3.24%   |
| 16      | 40        | 1.68%   |
| 14      | 26        | 1.09%   |
| 10      | 23        | 0.97%   |
| 1       | 22        | 0.93%   |
| 24      | 15        | 0.63%   |
| 32      | 11        | 0.46%   |
| 3       | 8         | 0.34%   |
| Unknown | 6         | 0.25%   |
| 40      | 5         | 0.21%   |
| 128     | 3         | 0.13%   |
| 48      | 3         | 0.13%   |
| 64      | 2         | 0.08%   |
| 18      | 2         | 0.08%   |
| 22      | 1         | 0.04%   |
| 20      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2307      | 97.22%  |
| 2       | 50        | 2.11%   |
| 4       | 11        | 0.46%   |
| Unknown | 4         | 0.17%   |
| 3       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1766      | 74.17%  |
| 1       | 609       | 25.58%  |
| Unknown | 6         | 0.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2334      | 98.11%  |
| Unknown        | 32        | 1.35%   |
| 32-bit         | 12        | 0.5%    |
| 64-bit         | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 668       | 27.12%  |
| 0x306a9    | 130       | 5.28%   |
| 0x206a7    | 109       | 4.43%   |
| 0x306c3    | 104       | 4.22%   |
| 0x806ea    | 81        | 3.29%   |
| 0x506e3    | 66        | 2.68%   |
| 0x906ea    | 62        | 2.52%   |
| 0x806ec    | 57        | 2.31%   |
| 0x806c1    | 57        | 2.31%   |
| 0x40651    | 56        | 2.27%   |
| 0x1067a    | 56        | 2.27%   |
| 0x806e9    | 53        | 2.15%   |
| 0x906e9    | 39        | 1.58%   |
| 0x306d4    | 34        | 1.38%   |
| 0x406e3    | 32        | 1.3%    |
| 0x08701021 | 32        | 1.3%    |
| 0x20655    | 25        | 1.02%   |
| 0x30678    | 23        | 0.93%   |
| 0x0a50000c | 21        | 0.85%   |
| 0xa0671    | 20        | 0.81%   |
| 0xa0655    | 19        | 0.77%   |
| 0x706e5    | 19        | 0.77%   |
| 0x0800820d | 19        | 0.77%   |
| 0x10676    | 18        | 0.73%   |
| 0x0a404102 | 18        | 0.73%   |
| 0x806eb    | 17        | 0.69%   |
| 0x406c4    | 17        | 0.69%   |
| 0x906a3    | 15        | 0.61%   |
| 0x306f2    | 15        | 0.61%   |
| 0x206d7    | 15        | 0.61%   |
| 0x106e5    | 15        | 0.61%   |
| 0x0a201016 | 15        | 0.61%   |
| 0xa0652    | 14        | 0.57%   |
| 0x906ed    | 14        | 0.57%   |
| 0x50654    | 14        | 0.57%   |
| 0x306e4    | 14        | 0.57%   |
| 0x20652    | 14        | 0.57%   |
| 0x08701013 | 13        | 0.53%   |
| 0x08600106 | 13        | 0.53%   |
| 0x206c2    | 12        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 446       | 18.73%  |
| Haswell          | 232       | 9.74%   |
| IvyBridge        | 176       | 7.39%   |
| Unknown          | 165       | 6.93%   |
| SandyBridge      | 159       | 6.68%   |
| Skylake          | 157       | 6.59%   |
| Zen 2            | 117       | 4.91%   |
| Zen 3            | 96        | 4.03%   |
| Penryn           | 91        | 3.82%   |
| TigerLake        | 83        | 3.49%   |
| Westmere         | 63        | 2.65%   |
| Silvermont       | 58        | 2.44%   |
| Alderlake Hybrid | 58        | 2.44%   |
| CometLake        | 54        | 2.27%   |
| Broadwell        | 53        | 2.23%   |
| Icelake          | 50        | 2.1%    |
| Zen+             | 47        | 1.97%   |
| Nehalem          | 39        | 1.64%   |
| Core             | 39        | 1.64%   |
| Zen              | 36        | 1.51%   |
| K10              | 30        | 1.26%   |
| Piledriver       | 23        | 0.97%   |
| Goldmont plus    | 20        | 0.84%   |
| Bobcat           | 13        | 0.55%   |
| Goldmont         | 12        | 0.5%    |
| Puma             | 10        | 0.42%   |
| Jaguar           | 10        | 0.42%   |
| K8 Hammer        | 9         | 0.38%   |
| P6               | 6         | 0.25%   |
| NetBurst         | 5         | 0.21%   |
| Excavator        | 5         | 0.21%   |
| Bulldozer        | 5         | 0.21%   |
| Bonnell          | 5         | 0.21%   |
| K10 Llano        | 4         | 0.17%   |
| Steamroller      | 3         | 0.13%   |
| Tremont          | 2         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1303      | 47.78%  |
| Nvidia                                       | 839       | 30.77%  |
| AMD                                          | 523       | 19.18%  |
| Matrox Electronics Systems                   | 35        | 1.28%   |
| ASPEED Technology                            | 16        | 0.59%   |
| XGI Technology (eXtreme Graphics Innovation) | 9         | 0.33%   |
| VIA Technologies                             | 2         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 94        | 3.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 94        | 3.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 88        | 3.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 79        | 2.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 71        | 2.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 70        | 2.52%   |
| Intel HD Graphics 620                                                                    | 60        | 2.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 54        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 48        | 1.73%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 45        | 1.62%   |
| Intel HD Graphics 530                                                                    | 42        | 1.51%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 42        | 1.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 37        | 1.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 37        | 1.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 35        | 1.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 33        | 1.19%   |
| Intel HD Graphics 5500                                                                   | 32        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 31        | 1.12%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 29        | 1.04%   |
| Intel HD Graphics 630                                                                    | 28        | 1.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 28        | 1.01%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 27        | 0.97%   |
| AMD Rembrandt [Radeon 680M]                                                              | 22        | 0.79%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 21        | 0.76%   |
| AMD Lucienne                                                                             | 21        | 0.76%   |
| Nvidia GP107GL [Quadro P400]                                                             | 20        | 0.72%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                                           | 20        | 0.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 0.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 19        | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 0.61%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 17        | 0.61%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 0.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 16        | 0.58%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 16        | 0.58%   |
| Nvidia GK107GL [Quadro K420]                                                             | 15        | 0.54%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 15        | 0.54%   |
| Intel Iris Plus Graphics G7                                                              | 15        | 0.54%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 14        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 947       | 39.64%  |
| 1 x Nvidia               | 517       | 21.64%  |
| 1 x AMD                  | 432       | 18.08%  |
| Intel + Nvidia           | 278       | 11.64%  |
| Other                    | 52        | 2.18%   |
| Intel + AMD              | 44        | 1.84%   |
| 1 x Matrox               | 32        | 1.34%   |
| AMD + Nvidia             | 31        | 1.3%    |
| 2 x AMD                  | 16        | 0.67%   |
| 1 x ASPEED               | 10        | 0.42%   |
| 1 x XGI                  | 9         | 0.38%   |
| 2 x Nvidia               | 6         | 0.25%   |
| Nvidia + ASPEED          | 5         | 0.21%   |
| 2 x Intel                | 3         | 0.13%   |
| 1 x VIA                  | 2         | 0.08%   |
| Nvidia + Matrox          | 2         | 0.08%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.04%   |
| AMD + Matrox             | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1765      | 73.57%  |
| Proprietary | 502       | 20.93%  |
| Unknown     | 132       | 5.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1330      | 54.64%  |
| 1.01-2.0   | 284       | 11.67%  |
| 0.01-0.5   | 226       | 9.29%   |
| 3.01-4.0   | 160       | 6.57%   |
| 0.51-1.0   | 156       | 6.41%   |
| 7.01-8.0   | 126       | 5.18%   |
| 8.01-16.0  | 77        | 3.16%   |
| 5.01-6.0   | 42        | 1.73%   |
| 16.01-24.0 | 16        | 0.66%   |
| 2.01-3.0   | 15        | 0.62%   |
| 4.01-5.0   | 2         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 347       | 13.5%   |
| AU Optronics            | 292       | 11.36%  |
| LG Display              | 232       | 9.03%   |
| Dell                    | 182       | 7.08%   |
| Chimei Innolux          | 145       | 5.64%   |
| BOE                     | 143       | 5.56%   |
| Hewlett-Packard         | 118       | 4.59%   |
| Acer                    | 108       | 4.2%    |
| Philips                 | 106       | 4.12%   |
| Apple                   | 100       | 3.89%   |
| BenQ                    | 79        | 3.07%   |
| Ancor Communications    | 71        | 2.76%   |
| Sharp                   | 69        | 2.68%   |
| Lenovo                  | 61        | 2.37%   |
| Goldstar                | 57        | 2.22%   |
| AOC                     | 56        | 2.18%   |
| Eizo                    | 44        | 1.71%   |
| ASUSTek Computer        | 30        | 1.17%   |
| InfoVision              | 26        | 1.01%   |
| Unknown                 | 25        | 0.97%   |
| CSO                     | 24        | 0.93%   |
| Chi Mei Optoelectronics | 23        | 0.89%   |
| Sony                    | 22        | 0.86%   |
| Iiyama                  | 16        | 0.62%   |
| NEC Computers           | 15        | 0.58%   |
| Panasonic               | 14        | 0.54%   |
| PANDA                   | 10        | 0.39%   |
| Toshiba                 | 9         | 0.35%   |
| ViewSonic               | 7         | 0.27%   |
| Vestel Elektronik       | 7         | 0.27%   |
| Medion                  | 7         | 0.27%   |
| Gigabyte Technology     | 7         | 0.27%   |
| Fujitsu Siemens         | 6         | 0.23%   |
| Valve                   | 5         | 0.19%   |
| MSI                     | 5         | 0.19%   |
| LG Philips              | 5         | 0.19%   |
| LG Electronics          | 5         | 0.19%   |
| Denver                  | 5         | 0.19%   |
| AUS                     | 5         | 0.19%   |
| LGD                     | 4         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor LF24T450F 1920x1080                    | 15        | 0.55%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch         | 13        | 0.48%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 12        | 0.44%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 11        | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 10        | 0.37%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch       | 9         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 9         | 0.33%   |
| AOC Q3279WG5B AOC3279 2560x1440 730x430mm 33.4-inch                    | 9         | 0.33%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 8         | 0.3%    |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch  | 8         | 0.3%    |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 7         | 0.26%   |
| Philips LCD Monitor PHL 272S4L 2560x1440                               | 7         | 0.26%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch               | 7         | 0.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 7         | 0.26%   |
| Dell LCD Monitor P2719H 3840x1080                                      | 7         | 0.26%   |
| Dell LCD Monitor P2719H                                                | 7         | 0.26%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                       | 7         | 0.26%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 6         | 0.22%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch   | 6         | 0.22%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 6         | 0.22%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch               | 6         | 0.22%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                  | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch       | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch       | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch          | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch          | 6         | 0.22%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                       | 6         | 0.22%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 5         | 0.18%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch      | 5         | 0.18%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 5         | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 5         | 0.18%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 5         | 0.18%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 5         | 0.18%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 5         | 0.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 5         | 0.18%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 5         | 0.18%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 5         | 0.18%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch           | 5         | 0.18%   |
| Hewlett-Packard E243i HPN3463 1920x1200 518x324mm 24.1-inch            | 5         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1028      | 41.2%   |
| 3840x2160 (4K)     | 231       | 9.26%   |
| 2560x1440 (QHD)    | 191       | 7.66%   |
| 1366x768 (WXGA)    | 171       | 6.85%   |
| 1920x1200 (WUXGA)  | 136       | 5.45%   |
| 1600x900 (HD+)     | 93        | 3.73%   |
| 1680x1050 (WSXGA+) | 82        | 3.29%   |
| 1280x1024 (SXGA)   | 69        | 2.77%   |
| Unknown            | 66        | 2.65%   |
| 3440x1440          | 52        | 2.08%   |
| 2560x1600          | 42        | 1.68%   |
| 1280x800 (WXGA)    | 40        | 1.6%    |
| 1440x900 (WXGA+)   | 35        | 1.4%    |
| 3840x1080          | 31        | 1.24%   |
| 1600x1200          | 28        | 1.12%   |
| 2880x1800          | 19        | 0.76%   |
| 3200x1800 (QHD+)   | 15        | 0.6%    |
| 3840x2400          | 14        | 0.56%   |
| 2560x1080          | 14        | 0.56%   |
| 2736x1824          | 11        | 0.44%   |
| 3840x1200          | 10        | 0.4%    |
| 3840x1600          | 9         | 0.36%   |
| 3000x2000          | 7         | 0.28%   |
| 2160x1440          | 7         | 0.28%   |
| 1920x540           | 7         | 0.28%   |
| 1360x768           | 7         | 0.28%   |
| 1024x768 (XGA)     | 7         | 0.28%   |
| 4480x1440          | 6         | 0.24%   |
| 800x1280           | 5         | 0.2%    |
| 3456x2160          | 5         | 0.2%    |
| 1024x600           | 5         | 0.2%    |
| 3520x1200          | 4         | 0.16%   |
| 7680x2160          | 3         | 0.12%   |
| 5120x1440          | 3         | 0.12%   |
| 3360x1050          | 3         | 0.12%   |
| 2048x1152          | 3         | 0.12%   |
| 6400x1440          | 2         | 0.08%   |
| 3840x1100          | 2         | 0.08%   |
| 3200x2000          | 2         | 0.08%   |
| 3200x1080          | 2         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 455       | 17.82%  |
| 27      | 273       | 10.69%  |
| 13      | 235       | 9.2%    |
| 14      | 220       | 8.61%   |
| Unknown | 220       | 8.61%   |
| 24      | 208       | 8.14%   |
| 17      | 158       | 6.19%   |
| 23      | 122       | 4.78%   |
| 21      | 99        | 3.88%   |
| 31      | 69        | 2.7%    |
| 12      | 65        | 2.55%   |
| 34      | 52        | 2.04%   |
| 20      | 41        | 1.61%   |
| 22      | 40        | 1.57%   |
| 19      | 39        | 1.53%   |
| 16      | 33        | 1.29%   |
| 32      | 19        | 0.74%   |
| 84      | 18        | 0.7%    |
| 72      | 16        | 0.63%   |
| 40      | 15        | 0.59%   |
| 11      | 15        | 0.59%   |
| 25      | 14        | 0.55%   |
| 37      | 12        | 0.47%   |
| 33      | 11        | 0.43%   |
| 46      | 10        | 0.39%   |
| 29      | 10        | 0.39%   |
| 18      | 10        | 0.39%   |
| 48      | 9         | 0.35%   |
| 54      | 7         | 0.27%   |
| 28      | 7         | 0.27%   |
| 10      | 7         | 0.27%   |
| 49      | 6         | 0.23%   |
| 26      | 5         | 0.2%    |
| 7       | 5         | 0.2%    |
| 65      | 4         | 0.16%   |
| 35      | 4         | 0.16%   |
| 55      | 3         | 0.12%   |
| 142     | 2         | 0.08%   |
| 60      | 2         | 0.08%   |
| 43      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 787       | 31.33%  |
| 501-600        | 552       | 21.97%  |
| 201-300        | 245       | 9.75%   |
| Unknown        | 220       | 8.76%   |
| 401-500        | 191       | 7.6%    |
| 351-400        | 189       | 7.52%   |
| 601-700        | 120       | 4.78%   |
| 701-800        | 82        | 3.26%   |
| 1001-1500      | 47        | 1.87%   |
| 1501-2000      | 35        | 1.39%   |
| 801-900        | 33        | 1.31%   |
| 1-100          | 5         | 0.2%    |
| 901-1000       | 3         | 0.12%   |
| More than 2000 | 2         | 0.08%   |
| 101-200        | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1523      | 65.9%   |
| 16/10   | 358       | 15.49%  |
| Unknown | 205       | 8.87%   |
| 21/9    | 68        | 2.94%   |
| 5/4     | 61        | 2.64%   |
| 3/2     | 35        | 1.51%   |
| 4/3     | 31        | 1.34%   |
| 32/9    | 12        | 0.52%   |
| 0.67    | 5         | 0.22%   |
| 6/5     | 4         | 0.17%   |
| 1.00    | 3         | 0.13%   |
| 3.40    | 2         | 0.09%   |
| 3.73    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |
| 2.50    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 453       | 17.88%  |
| 201-250        | 336       | 13.26%  |
| 81-90          | 313       | 12.36%  |
| 301-350        | 278       | 10.98%  |
| Unknown        | 220       | 8.69%   |
| 351-500        | 170       | 6.71%   |
| 71-80          | 139       | 5.49%   |
| 121-130        | 122       | 4.82%   |
| 251-300        | 114       | 4.5%    |
| 151-200        | 107       | 4.22%   |
| More than 1000 | 62        | 2.45%   |
| 61-70          | 60        | 2.37%   |
| 501-1000       | 50        | 1.97%   |
| 111-120        | 31        | 1.22%   |
| 141-150        | 25        | 0.99%   |
| 51-60          | 18        | 0.71%   |
| 131-140        | 16        | 0.63%   |
| 91-100         | 7         | 0.28%   |
| 41-50          | 6         | 0.24%   |
| 1-40           | 6         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 703       | 28.64%  |
| 121-160       | 654       | 26.64%  |
| 101-120       | 469       | 19.1%   |
| 161-240       | 221       | 9%      |
| Unknown       | 220       | 8.96%   |
| More than 240 | 130       | 5.3%    |
| 1-50          | 58        | 2.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1776      | 72.25%  |
| 2     | 436       | 17.74%  |
| 0     | 177       | 7.2%    |
| 3     | 65        | 2.64%   |
| 4     | 4         | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1430      | 40.81%  |
| Realtek Semiconductor             | 979       | 27.94%  |
| Qualcomm Atheros                  | 255       | 7.28%   |
| Broadcom                          | 204       | 5.82%   |
| MediaTek                          | 61        | 1.74%   |
| Broadcom Limited                  | 51        | 1.46%   |
| Marvell Technology Group          | 47        | 1.34%   |
| ASIX Electronics                  | 37        | 1.06%   |
| Ralink                            | 33        | 0.94%   |
| Aquantia                          | 33        | 0.94%   |
| Lenovo                            | 27        | 0.77%   |
| Nvidia                            | 26        | 0.74%   |
| Sierra Wireless                   | 22        | 0.63%   |
| Ralink Technology                 | 21        | 0.6%    |
| TP-Link                           | 20        | 0.57%   |
| Qualcomm                          | 18        | 0.51%   |
| DisplayLink                       | 17        | 0.49%   |
| Dell                              | 16        | 0.46%   |
| Hewlett-Packard                   | 15        | 0.43%   |
| Huawei Technologies               | 14        | 0.4%    |
| Ericsson Business Mobile Networks | 13        | 0.37%   |
| Edimax Technology                 | 13        | 0.37%   |
| Samsung Electronics               | 12        | 0.34%   |
| NetGear                           | 12        | 0.34%   |
| Microchip Technology              | 10        | 0.29%   |
| D-Link                            | 10        | 0.29%   |
| ASUSTek Computer                  | 10        | 0.29%   |
| Xiaomi                            | 9         | 0.26%   |
| Microsoft                         | 9         | 0.26%   |
| IMC Networks                      | 5         | 0.14%   |
| Fibocom                           | 5         | 0.14%   |
| AVM                               | 5         | 0.14%   |
| NetXen Incorporated               | 4         | 0.11%   |
| Linksys                           | 4         | 0.11%   |
| ICS Advent                        | 4         | 0.11%   |
| D-Link System                     | 4         | 0.11%   |
| Wilocity                          | 3         | 0.09%   |
| Qualcomm Atheros Communications   | 3         | 0.09%   |
| Mellanox Technologies             | 3         | 0.09%   |
| Arduino SA                        | 3         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 662       | 15.83%  |
| Intel Wi-Fi 6 AX200                                               | 144       | 3.44%   |
| Intel Wireless 8265 / 8275                                        | 113       | 2.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 98        | 2.34%   |
| Intel I211 Gigabit Network Connection                             | 98        | 2.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 97        | 2.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 84        | 2.01%   |
| Intel Wi-Fi 6 AX201                                               | 68        | 1.63%   |
| Intel Ethernet Connection (2) I219-V                              | 60        | 1.44%   |
| Intel Wireless 7260                                               | 57        | 1.36%   |
| Intel Wireless 7265                                               | 50        | 1.2%    |
| Intel Ethernet Connection I217-LM                                 | 48        | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 46        | 1.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 44        | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 43        | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 42        | 1%      |
| Intel Wireless 8260                                               | 42        | 1%      |
| Intel Ethernet Connection (2) I219-LM                             | 40        | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 39        | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 37        | 0.88%   |
| Intel 82574L Gigabit Network Connection                           | 36        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 33        | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 33        | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 32        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 31        | 0.74%   |
| Intel Ethernet Controller I225-V                                  | 30        | 0.72%   |
| Intel Ethernet Connection (6) I219-V                              | 30        | 0.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 27        | 0.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 27        | 0.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 27        | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 26        | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 26        | 0.62%   |
| Intel Wireless-AC 9260                                            | 25        | 0.6%    |
| Intel Wireless 3165                                               | 25        | 0.6%    |
| Intel Ethernet Connection (4) I219-V                              | 25        | 0.6%    |
| Intel Centrino Ultimate-N 6300                                    | 25        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 24        | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 24        | 0.57%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 24        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 991       | 54.27%  |
| Qualcomm Atheros                      | 211       | 11.56%  |
| Realtek Semiconductor                 | 192       | 10.51%  |
| Broadcom                              | 118       | 6.46%   |
| MediaTek                              | 57        | 3.12%   |
| Broadcom Limited                      | 35        | 1.92%   |
| Ralink                                | 33        | 1.81%   |
| Sierra Wireless                       | 22        | 1.2%    |
| Ralink Technology                     | 21        | 1.15%   |
| TP-Link                               | 15        | 0.82%   |
| Qualcomm                              | 15        | 0.82%   |
| Marvell Technology Group              | 13        | 0.71%   |
| Dell                                  | 12        | 0.66%   |
| NetGear                               | 11        | 0.6%    |
| ASUSTek Computer                      | 10        | 0.55%   |
| Edimax Technology                     | 9         | 0.49%   |
| D-Link                                | 9         | 0.49%   |
| Hewlett-Packard                       | 7         | 0.38%   |
| Microsoft                             | 6         | 0.33%   |
| IMC Networks                          | 5         | 0.27%   |
| Fibocom                               | 5         | 0.27%   |
| AVM                                   | 5         | 0.27%   |
| Wilocity                              | 3         | 0.16%   |
| Qualcomm Atheros Communications       | 3         | 0.16%   |
| D-Link System                         | 3         | 0.16%   |
| Micro Star International              | 2         | 0.11%   |
| Ericsson Business Mobile Networks     | 2         | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.11%   |
| ZyXEL Communications                  | 1         | 0.05%   |
| Quectel Wireless Solutions            | 1         | 0.05%   |
| Philips (or NXP)                      | 1         | 0.05%   |
| Netopia                               | 1         | 0.05%   |
| Linksys                               | 1         | 0.05%   |
| Gemtek                                | 1         | 0.05%   |
| CyberTAN Technology                   | 1         | 0.05%   |
| Belkin Components                     | 1         | 0.05%   |
| Arduino SA                            | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 144       | 7.84%   |
| Intel Wireless 8265 / 8275                                     | 113       | 6.15%   |
| Intel Wi-Fi 6 AX201                                            | 68        | 3.7%    |
| Intel Wireless 7260                                            | 57        | 3.1%    |
| Intel Wireless 7265                                            | 50        | 2.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 46        | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 43        | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 42        | 2.29%   |
| Intel Wireless 8260                                            | 42        | 2.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 39        | 2.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 33        | 1.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 33        | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 32        | 1.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 27        | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 27        | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 27        | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 26        | 1.42%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 26        | 1.42%   |
| Intel Wireless-AC 9260                                         | 25        | 1.36%   |
| Intel Wireless 3165                                            | 25        | 1.36%   |
| Intel Centrino Ultimate-N 6300                                 | 25        | 1.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 22        | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 22        | 1.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 20        | 1.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 19        | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 18        | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 18        | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 18        | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 16        | 0.87%   |
| Intel Centrino Advanced-N 6235                                 | 16        | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 15        | 0.82%   |
| Intel Wireless 3160                                            | 15        | 0.82%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 14        | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 14        | 0.76%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 13        | 0.71%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 13        | 0.71%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 12        | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 12        | 0.65%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 12        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 896       | 40.62%  |
| Intel                         | 857       | 38.85%  |
| Broadcom                      | 115       | 5.21%   |
| Qualcomm Atheros              | 72        | 3.26%   |
| ASIX Electronics              | 37        | 1.68%   |
| Marvell Technology Group      | 34        | 1.54%   |
| Aquantia                      | 33        | 1.5%    |
| Nvidia                        | 26        | 1.18%   |
| Lenovo                        | 26        | 1.18%   |
| DisplayLink                   | 17        | 0.77%   |
| Broadcom Limited              | 16        | 0.73%   |
| Xiaomi                        | 9         | 0.41%   |
| Microchip Technology          | 8         | 0.36%   |
| Huawei Technologies           | 8         | 0.36%   |
| TP-Link                       | 5         | 0.23%   |
| Samsung Electronics           | 5         | 0.23%   |
| NetXen Incorporated           | 4         | 0.18%   |
| MediaTek                      | 4         | 0.18%   |
| ICS Advent                    | 4         | 0.18%   |
| Edimax Technology             | 4         | 0.18%   |
| Qualcomm                      | 3         | 0.14%   |
| Linksys                       | 3         | 0.14%   |
| Microsoft                     | 2         | 0.09%   |
| Mellanox Technologies         | 2         | 0.09%   |
| Google                        | 2         | 0.09%   |
| Standard Microsystems         | 1         | 0.05%   |
| QNAP System                   | 1         | 0.05%   |
| OnePlus Technology (Shenzhen) | 1         | 0.05%   |
| NetGear                       | 1         | 0.05%   |
| Netchip Technology            | 1         | 0.05%   |
| MosChip Semiconductor         | 1         | 0.05%   |
| JMicron Technology            | 1         | 0.05%   |
| HMD Global                    | 1         | 0.05%   |
| Hewlett-Packard               | 1         | 0.05%   |
| D-Link System                 | 1         | 0.05%   |
| D-Link                        | 1         | 0.05%   |
| Cypress Semiconductor         | 1         | 0.05%   |
| Apple                         | 1         | 0.05%   |
| ADMtek                        | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 662       | 29%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 98        | 4.29%   |
| Intel I211 Gigabit Network Connection                             | 98        | 4.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 97        | 4.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 84        | 3.68%   |
| Intel Ethernet Connection (2) I219-V                              | 60        | 2.63%   |
| Intel Ethernet Connection I217-LM                                 | 48        | 2.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 44        | 1.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 40        | 1.75%   |
| Intel 82579V Gigabit Network Connection                           | 37        | 1.62%   |
| Intel 82574L Gigabit Network Connection                           | 36        | 1.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 31        | 1.36%   |
| Intel Ethernet Controller I225-V                                  | 30        | 1.31%   |
| Intel Ethernet Connection (6) I219-V                              | 30        | 1.31%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 1.14%   |
| Intel Ethernet Connection (4) I219-V                              | 25        | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 24        | 1.05%   |
| Intel Ethernet Connection I218-LM                                 | 24        | 1.05%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 24        | 1.05%   |
| Intel Ethernet Connection (2) I218-V                              | 23        | 1.01%   |
| Intel I210 Gigabit Network Connection                             | 22        | 0.96%   |
| Intel Ethernet Connection I219-LM                                 | 21        | 0.92%   |
| Intel I350 Gigabit Network Connection                             | 20        | 0.88%   |
| Intel Ethernet Connection (7) I219-V                              | 20        | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                             | 19        | 0.83%   |
| Intel 82577LM Gigabit Network Connection                          | 18        | 0.79%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 18        | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.74%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 14        | 0.61%   |
| Nvidia MCP79 Ethernet                                             | 12        | 0.53%   |
| Intel Ethernet Connection I217-V                                  | 12        | 0.53%   |
| Intel Ethernet Connection I219-V                                  | 11        | 0.48%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9         | 0.39%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 9         | 0.39%   |
| Lenovo ThinkPad Lan                                               | 9         | 0.39%   |
| Intel Ethernet Connection (11) I219-LM                            | 9         | 0.39%   |
| Intel 82576 Gigabit Network Connection                            | 9         | 0.39%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 8         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2015      | 53.11%  |
| WiFi     | 1720      | 45.33%  |
| Modem    | 53        | 1.4%    |
| Unknown  | 6         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1236      | 51.22%  |
| Ethernet | 1176      | 48.74%  |
| Modem    | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1209      | 50.65%  |
| 1     | 951       | 39.84%  |
| 3     | 109       | 4.57%   |
| 0     | 72        | 3.02%   |
| 4     | 29        | 1.21%   |
| 6     | 8         | 0.34%   |
| 5     | 5         | 0.21%   |
| 8     | 2         | 0.08%   |
| 10    | 1         | 0.04%   |
| 7     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1886      | 77.23%  |
| Yes  | 556       | 22.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 801       | 54.31%  |
| Realtek Semiconductor           | 97        | 6.58%   |
| Apple                           | 94        | 6.37%   |
| Broadcom                        | 79        | 5.36%   |
| Cambridge Silicon Radio         | 64        | 4.34%   |
| Qualcomm Atheros Communications | 61        | 4.14%   |
| Foxconn / Hon Hai               | 59        | 4%      |
| IMC Networks                    | 49        | 3.32%   |
| Lite-On Technology              | 36        | 2.44%   |
| ASUSTek Computer                | 30        | 2.03%   |
| Hewlett-Packard                 | 17        | 1.15%   |
| Dell                            | 15        | 1.02%   |
| MediaTek                        | 14        | 0.95%   |
| USI                             | 11        | 0.75%   |
| Marvell Semiconductor           | 11        | 0.75%   |
| Ralink                          | 9         | 0.61%   |
| Toshiba                         | 4         | 0.27%   |
| Alps Electric                   | 4         | 0.27%   |
| Realtek                         | 3         | 0.2%    |
| Micro Star International        | 3         | 0.2%    |
| TP-Link                         | 2         | 0.14%   |
| Ralink Technology               | 2         | 0.14%   |
| Edimax Technology               | 2         | 0.14%   |
| Chicony Electronics             | 2         | 0.14%   |
| Taiyo Yuden                     | 1         | 0.07%   |
| Logitech                        | 1         | 0.07%   |
| Integrated System Solution      | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |
| Foxconn International           | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 294       | 19.91%  |
| Intel Bluetooth Device                              | 202       | 13.68%  |
| Intel AX200 Bluetooth                               | 135       | 9.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 82        | 5.55%   |
| Realtek Bluetooth Radio                             | 67        | 4.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 64        | 4.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 28        | 1.9%    |
| Apple Bluetooth Host Controller                     | 28        | 1.9%    |
| Apple Bluetooth USB Host Controller                 | 27        | 1.83%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 26        | 1.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 24        | 1.62%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 24        | 1.62%   |
| Intel Wireless-AC 3168 Bluetooth                    | 22        | 1.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 1.42%   |
| Intel AX210 Bluetooth                               | 18        | 1.22%   |
| Foxconn / Hon Hai Bluetooth Device                  | 17        | 1.15%   |
| IMC Networks Bluetooth Radio                        | 16        | 1.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 15        | 1.02%   |
| IMC Networks Wireless_Device                        | 15        | 1.02%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 1.02%   |
| MediaTek Wireless_Device                            | 14        | 0.95%   |
| ASUS Bluetooth Device                               | 14        | 0.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.81%   |
| USI Bluetooth Device                                | 11        | 0.74%   |
| Apple Bluetooth HCI                                 | 11        | 0.74%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 10        | 0.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.68%   |
| Foxconn / Hon Hai Wireless_Device                   | 10        | 0.68%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.61%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 0.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.54%   |
| Marvell Bluetooth and Wireless LAN Composite        | 8         | 0.54%   |
| IMC Networks Bluetooth Device                       | 8         | 0.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.54%   |
| Lite-On Bluetooth Device                            | 7         | 0.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.47%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.47%   |
| Broadcom BCM20702A0                                 | 7         | 0.47%   |
| Foxconn / Hon Hai BCM20702A0                        | 6         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 1749      | 52.44%  |
| Nvidia                    | 642       | 19.25%  |
| AMD                       | 564       | 16.91%  |
| GN Netcom                 | 41        | 1.23%   |
| Logitech                  | 38        | 1.14%   |
| C-Media Electronics       | 35        | 1.05%   |
| ASUSTek Computer          | 22        | 0.66%   |
| Lenovo                    | 21        | 0.63%   |
| Plantronics               | 15        | 0.45%   |
| Realtek Semiconductor     | 12        | 0.36%   |
| Hewlett-Packard           | 12        | 0.36%   |
| Creative Labs             | 11        | 0.33%   |
| SteelSeries ApS           | 9         | 0.27%   |
| RODE Microphones          | 9         | 0.27%   |
| Kingston Technology       | 9         | 0.27%   |
| Razer USA                 | 8         | 0.24%   |
| Generalplus Technology    | 6         | 0.18%   |
| BEHRINGER International   | 6         | 0.18%   |
| Apple                     | 6         | 0.18%   |
| Texas Instruments         | 5         | 0.15%   |
| Tenx Technology           | 5         | 0.15%   |
| Samson Technologies       | 5         | 0.15%   |
| Micro Star International  | 5         | 0.15%   |
| Creative Technology       | 5         | 0.15%   |
| JMTek                     | 4         | 0.12%   |
| Focusrite-Novation        | 4         | 0.12%   |
| Corsair                   | 4         | 0.12%   |
| Conexant Systems          | 4         | 0.12%   |
| XMOS                      | 3         | 0.09%   |
| Sony                      | 3         | 0.09%   |
| Sennheiser Communications | 3         | 0.09%   |
| ROCCAT                    | 3         | 0.09%   |
| GYROCOM C&C               | 3         | 0.09%   |
| DSEA A/S                  | 3         | 0.09%   |
| Yamaha                    | 2         | 0.06%   |
| VIA Technologies          | 2         | 0.06%   |
| TerraTec Electronic       | 2         | 0.06%   |
| Roland                    | 2         | 0.06%   |
| Other World Computing     | 2         | 0.06%   |
| Magic Control Technology  | 2         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 226       | 5.84%   |
| AMD Family 17h/19h HD Audio Controller                                     | 172       | 4.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 165       | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 130       | 3.36%   |
| AMD Starship/Matisse HD Audio Controller                                   | 119       | 3.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 112       | 2.89%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 97        | 2.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 90        | 2.32%   |
| Intel Cannon Lake PCH cAVS                                                 | 85        | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 83        | 2.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 83        | 2.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 79        | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                      | 71        | 1.83%   |
| Intel 8 Series HD Audio Controller                                         | 71        | 1.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 68        | 1.76%   |
| Intel 200 Series PCH HD Audio                                              | 60        | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                            | 54        | 1.39%   |
| Nvidia GK107 HDMI Audio Controller                                         | 50        | 1.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 50        | 1.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 47        | 1.21%   |
| Intel Broadwell-U Audio Controller                                         | 45        | 1.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 45        | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                              | 44        | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 43        | 1.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 43        | 1.11%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 43        | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                               | 42        | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 39        | 1.01%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 37        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 36        | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 36        | 0.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 34        | 0.88%   |
| Nvidia GP102 HDMI Audio Controller                                         | 30        | 0.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 30        | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 30        | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                              | 29        | 0.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 29        | 0.75%   |
| AMD FCH Azalia Controller                                                  | 29        | 0.75%   |
| Nvidia GK104 HDMI Audio Controller                                         | 28        | 0.72%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 28        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 390       | 24%     |
| SK hynix                                | 309       | 19.02%  |
| Kingston                                | 263       | 16.18%  |
| Micron Technology                       | 187       | 11.51%  |
| Corsair                                 | 160       | 9.85%   |
| Unknown                                 | 105       | 6.46%   |
| Crucial                                 | 55        | 3.38%   |
| G.Skill                                 | 43        | 2.65%   |
| Elpida                                  | 24        | 1.48%   |
| Ramaxel Technology                      | 15        | 0.92%   |
| A-DATA Technology                       | 13        | 0.8%    |
| Nanya Technology                        | 10        | 0.62%   |
| Unknown                                 | 8         | 0.49%   |
| Patriot                                 | 5         | 0.31%   |
| Unknown (ABCD)                          | 3         | 0.18%   |
| Hewlett-Packard                         | 3         | 0.18%   |
| Avant                                   | 3         | 0.18%   |
| ASint Technology                        | 3         | 0.18%   |
| Unknown (0x9801)                        | 2         | 0.12%   |
| Team                                    | 2         | 0.12%   |
| Apacer                                  | 2         | 0.12%   |
| Unknown (0x198)                         | 1         | 0.06%   |
| Unknown (08AE)                          | 1         | 0.06%   |
| Unifosa                                 | 1         | 0.06%   |
| Smart                                   | 1         | 0.06%   |
| Silicon Power Computer & Communications | 1         | 0.06%   |
| Princeton                               | 1         | 0.06%   |
| Patriot Memory                          | 1         | 0.06%   |
| OnBoard                                 | 1         | 0.06%   |
| OCZ                                     | 1         | 0.06%   |
| Melco                                   | 1         | 0.06%   |
| Lexar                                   | 1         | 0.06%   |
| Kingmax                                 | 1         | 0.06%   |
| King Tiger                              | 1         | 0.06%   |
| KANMEIQi                                | 1         | 0.06%   |
| HPE                                     | 1         | 0.06%   |
| GOODRAM                                 | 1         | 0.06%   |
| G-Alantic                               | 1         | 0.06%   |
| Advantech                               | 1         | 0.06%   |
| A-DA                                    | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 17        | 0.97%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s      | 17        | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 15        | 0.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 13        | 0.74%   |
| Kingston RAM 9905734-415.A00G 16GB DIMM DDR4 3200MT/s         | 13        | 0.74%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s        | 13        | 0.74%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 10        | 0.57%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 9         | 0.51%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 9         | 0.51%   |
| Kingston RAM 9905734-016.A00G 16GB DIMM DDR4 3200MT/s         | 9         | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 8         | 0.46%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 8         | 0.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 8         | 0.46%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 8         | 0.46%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s      | 8         | 0.46%   |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s        | 8         | 0.46%   |
| Unknown                                                       | 8         | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 7         | 0.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 7         | 0.4%    |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s      | 7         | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 7         | 0.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 7         | 0.4%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s        | 7         | 0.4%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s        | 7         | 0.4%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 7         | 0.4%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 7         | 0.4%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 7         | 0.4%    |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s      | 7         | 0.4%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s  | 7         | 0.4%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.4%    |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s        | 7         | 0.4%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                  | 6         | 0.34%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 6         | 0.34%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 6         | 0.34%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s      | 6         | 0.34%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s        | 6         | 0.34%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 6         | 0.34%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s        | 6         | 0.34%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s         | 6         | 0.34%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                  | 5         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 727       | 49.49%  |
| DDR3    | 471       | 32.06%  |
| LPDDR3  | 66        | 4.49%   |
| LPDDR4  | 51        | 3.47%   |
| DDR2    | 42        | 2.86%   |
| DDR5    | 40        | 2.72%   |
| Unknown | 25        | 1.7%    |
| LPDDR5  | 24        | 1.63%   |
| SDRAM   | 18        | 1.23%   |
| DDR     | 5         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 741       | 50.51%  |
| DIMM         | 576       | 39.26%  |
| Row Of Chips | 129       | 8.79%   |
| Chip         | 11        | 0.75%   |
| RIMM         | 6         | 0.41%   |
| Unknown      | 3         | 0.2%    |
| FB-DIMM      | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 623       | 39.78%  |
| 16384 | 355       | 22.67%  |
| 4096  | 329       | 21.01%  |
| 2048  | 136       | 8.68%   |
| 32768 | 84        | 5.36%   |
| 1024  | 32        | 2.04%   |
| 65536 | 5         | 0.32%   |
| 49152 | 1         | 0.06%   |
| 512   | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 290       | 18.53%  |
| 3200    | 255       | 16.29%  |
| 2667    | 203       | 12.97%  |
| 2133    | 113       | 7.22%   |
| 1333    | 101       | 6.45%   |
| 2400    | 93        | 5.94%   |
| 1334    | 53        | 3.39%   |
| 1867    | 32        | 2.04%   |
| 3600    | 29        | 1.85%   |
| 4800    | 28        | 1.79%   |
| 3000    | 28        | 1.79%   |
| 4267    | 27        | 1.73%   |
| 2666    | 27        | 1.73%   |
| 800     | 26        | 1.66%   |
| 6400    | 21        | 1.34%   |
| 3400    | 20        | 1.28%   |
| 667     | 20        | 1.28%   |
| 1067    | 19        | 1.21%   |
| Unknown | 16        | 1.02%   |
| 3266    | 13        | 0.83%   |
| 3733    | 12        | 0.77%   |
| 1066    | 11        | 0.7%    |
| 3800    | 9         | 0.58%   |
| 2933    | 9         | 0.58%   |
| 8400    | 6         | 0.38%   |
| 2000    | 6         | 0.38%   |
| 1866    | 6         | 0.38%   |
| 1800    | 6         | 0.38%   |
| 5808    | 5         | 0.32%   |
| 5600    | 5         | 0.32%   |
| 4266    | 5         | 0.32%   |
| 3533    | 5         | 0.32%   |
| 3100    | 5         | 0.32%   |
| 6000    | 4         | 0.26%   |
| 4199    | 4         | 0.26%   |
| 3933    | 4         | 0.26%   |
| 3666    | 4         | 0.26%   |
| 2465    | 4         | 0.26%   |
| 2048    | 4         | 0.26%   |
| 7500    | 3         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 29        | 44.62%  |
| Brother Industries       | 16        | 24.62%  |
| Samsung Electronics      | 5         | 7.69%   |
| Canon                    | 4         | 6.15%   |
| STMicroelectronics       | 3         | 4.62%   |
| Seiko Epson              | 2         | 3.08%   |
| Oki Data                 | 2         | 3.08%   |
| Zhuhai Poskey Technology | 1         | 1.54%   |
| Prolific Technology      | 1         | 1.54%   |
| Konica Minolta           | 1         | 1.54%   |
| Dymo-CoStar              | 1         | 1.54%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 3         | 4.62%   |
| Samsung M337x 387x 407x Series                             | 2         | 3.08%   |
| Oki Data USB Device                                        | 2         | 3.08%   |
| HP OfficeJet Pro 7730 series                               | 2         | 3.08%   |
| HP OfficeJet 6950                                          | 2         | 3.08%   |
| HP LaserJet Pro M148f-M149f                                | 2         | 3.08%   |
| HP LaserJet P1102                                          | 2         | 3.08%   |
| HP LaserJet 3020                                           | 2         | 3.08%   |
| HP ENVY 5540 series                                        | 2         | 3.08%   |
| HP Deskjet 2540 series                                     | 2         | 3.08%   |
| Brother Printer                                            | 2         | 3.08%   |
| Brother MFC Composite Device                               | 2         | 3.08%   |
| Zhuhai Poskey Printer                                      | 1         | 1.54%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 1.54%   |
| Seiko Epson ET-2820 Series                                 | 1         | 1.54%   |
| Samsung M332x 382x 402x Series                             | 1         | 1.54%   |
| Samsung C48x Series                                        | 1         | 1.54%   |
| Samsung C1860 Series                                       | 1         | 1.54%   |
| Prolific PL2305 Parallel Port                              | 1         | 1.54%   |
| Konica Minolta Printer                                     | 1         | 1.54%   |
| HP Smart Tank Plus 550 series                              | 1         | 1.54%   |
| HP Smart Tank 7000 series                                  | 1         | 1.54%   |
| HP Officejet 4630 series                                   | 1         | 1.54%   |
| HP LaserJet Pro M148-M149                                  | 1         | 1.54%   |
| HP LaserJet P3010 Series                                   | 1         | 1.54%   |
| HP LaserJet P2055 series                                   | 1         | 1.54%   |
| HP Laserjet P1505                                          | 1         | 1.54%   |
| HP LaserJet 3050                                           | 1         | 1.54%   |
| HP LaserJet 1320                                           | 1         | 1.54%   |
| HP LaserJet 1020                                           | 1         | 1.54%   |
| HP Laser 107a                                              | 1         | 1.54%   |
| HP ENVY Photo 6200 series                                  | 1         | 1.54%   |
| HP ENVY 6400 series                                        | 1         | 1.54%   |
| HP ENVY 4520 series                                        | 1         | 1.54%   |
| HP DeskJet F2100 Printer series                            | 1         | 1.54%   |
| Dymo-CoStar LabelWriter 450                                | 1         | 1.54%   |
| Canon TS3300 series                                        | 1         | 1.54%   |
| Canon PIXMA TS6250                                         | 1         | 1.54%   |
| Canon PIXMA MX450 Series                                   | 1         | 1.54%   |
| Canon iP7200 series                                        | 1         | 1.54%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Canon             | 7         | 46.67%  |
| Seiko Epson       | 4         | 26.67%  |
| Hewlett-Packard   | 2         | 13.33%  |
| Fujitsu           | 1         | 6.67%   |
| Canon Electronics | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                       | 2         | 13.33%  |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                   | 1         | 6.67%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 1         | 6.67%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]       | 1         | 6.67%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 6.67%   |
| HP ScanJet 4070 PhotoSmart                                    | 1         | 6.67%   |
| HP ScanJet 2400c                                              | 1         | 6.67%   |
| Fujitsu ScanSnap SV600                                        | 1         | 6.67%   |
| Canon P-150 Scanner                                           | 1         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20                            | 1         | 6.67%   |
| Canon CanoScan N650U/N656U                                    | 1         | 6.67%   |
| Canon CanoScan LIDE 25                                        | 1         | 6.67%   |
| Canon CanoScan LiDE 200                                       | 1         | 6.67%   |
| Canon CanoScan LiDE 100                                       | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 365       | 26.66%  |
| IMC Networks                           | 105       | 7.67%   |
| Logitech                               | 99        | 7.23%   |
| Apple                                  | 92        | 6.72%   |
| Microdia                               | 82        | 5.99%   |
| Bison Electronics                      | 73        | 5.33%   |
| Realtek Semiconductor                  | 72        | 5.26%   |
| Quanta                                 | 65        | 4.75%   |
| Sunplus Innovation Technology          | 55        | 4.02%   |
| Cheng Uei Precision Industry (Foxlink) | 49        | 3.58%   |
| Lite-On Technology                     | 36        | 2.63%   |
| Suyin                                  | 35        | 2.56%   |
| Acer                                   | 28        | 2.05%   |
| Luxvisions Innotech Limited            | 26        | 1.9%    |
| Syntek                                 | 25        | 1.83%   |
| Lenovo                                 | 17        | 1.24%   |
| Microsoft                              | 15        | 1.1%    |
| Alcor Micro                            | 15        | 1.1%    |
| Ricoh                                  | 14        | 1.02%   |
| Samsung Electronics                    | 12        | 0.88%   |
| Sonix Technology                       | 8         | 0.58%   |
| Z-Star Microelectronics                | 7         | 0.51%   |
| Silicon Motion                         | 7         | 0.51%   |
| Primax Electronics                     | 5         | 0.37%   |
| Generalplus Technology                 | 5         | 0.37%   |
| ALi                                    | 5         | 0.37%   |
| Xiaomi                                 | 3         | 0.22%   |
| ShineTech                              | 3         | 0.22%   |
| Intel                                  | 3         | 0.22%   |
| Tripath Technology                     | 2         | 0.15%   |
| OmniVision Technologies                | 2         | 0.15%   |
| MacroSilicon                           | 2         | 0.15%   |
| KYE Systems (Mouse Systems)            | 2         | 0.15%   |
| Genesys Logic                          | 2         | 0.15%   |
| DigiTech                               | 2         | 0.15%   |
| Creative Technology                    | 2         | 0.15%   |
| 8SSC21D67422V1SR28902JL                | 2         | 0.15%   |
| YGTek                                  | 1         | 0.07%   |
| WCM_USB                                | 1         | 0.07%   |
| Trust                                  | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 99        | 7.11%   |
| IMC Networks Integrated Camera                      | 51        | 3.66%   |
| Microdia Integrated_Webcam_HD                       | 42        | 3.02%   |
| Chicony HD WebCam                                   | 36        | 2.59%   |
| Apple Built-in iSight                               | 29        | 2.08%   |
| Bison Integrated Camera                             | 28        | 2.01%   |
| Apple FaceTime HD Camera (Built-in)                 | 28        | 2.01%   |
| Chicony HP HD Camera                                | 26        | 1.87%   |
| Realtek Integrated_Webcam_HD                        | 23        | 1.65%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 23        | 1.65%   |
| Logitech Webcam C270                                | 18        | 1.29%   |
| Logitech HD Pro Webcam C920                         | 18        | 1.29%   |
| Lite-On Integrated Camera                           | 17        | 1.22%   |
| Chicony USB2.0 Camera                               | 17        | 1.22%   |
| Quanta HP HD Camera                                 | 16        | 1.15%   |
| Chicony HP Wide Vision HD Camera                    | 16        | 1.15%   |
| Apple iPhone 5/5C/5S/6/SE                           | 16        | 1.15%   |
| Syntek Integrated Camera                            | 15        | 1.08%   |
| Sunplus Integrated_Webcam_HD                        | 14        | 1.01%   |
| Sunplus HD WebCam                                   | 13        | 0.93%   |
| Chicony Integrated Camera (1280x720@30)             | 13        | 0.93%   |
| Samsung Galaxy series, misc. (MTP mode)             | 12        | 0.86%   |
| Lite-On HP HD Camera                                | 12        | 0.86%   |
| Microdia Integrated Webcam                          | 11        | 0.79%   |
| Chicony HP Truevision HD                            | 11        | 0.79%   |
| Apple FaceTime HD Camera                            | 11        | 0.79%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 10        | 0.72%   |
| Chicony HP HD Webcam                                | 10        | 0.72%   |
| Chicony HD User Facing                              | 10        | 0.72%   |
| Suyin HP Truevision HD                              | 9         | 0.65%   |
| Chicony Integrated IR Camera                        | 8         | 0.57%   |
| Realtek USB2.0 HD UVC WebCam                        | 7         | 0.5%    |
| Quanta HD Webcam                                    | 7         | 0.5%    |
| Quanta HD User Facing                               | 7         | 0.5%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 7         | 0.5%    |
| Logitech StreamCam                                  | 7         | 0.5%    |
| Logitech HD Webcam C615                             | 7         | 0.5%    |
| Lenovo Integrated Webcam                            | 7         | 0.5%    |
| Chicony VGA WebCam                                  | 7         | 0.5%    |
| Chicony TOSHIBA Web Camera - HD                     | 7         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 150       | 37.04%  |
| Validity Sensors                   | 149       | 36.79%  |
| Shenzhen Goodix Technology         | 35        | 8.64%   |
| Elan Microelectronics              | 21        | 5.19%   |
| Upek                               | 20        | 4.94%   |
| AuthenTec                          | 15        | 3.7%    |
| LighTuning Technology              | 11        | 2.72%   |
| STMicroelectronics                 | 3         | 0.74%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 55        | 13.58%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 35        | 8.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 20        | 4.94%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 4.2%    |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 4.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 3.95%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 3.7%    |
| Elan ELAN:ARM-M4                                                           | 15        | 3.7%    |
| Synaptics  WBDI                                                            | 13        | 3.21%   |
| Shenzhen Goodix  Fingerprint Device                                        | 13        | 3.21%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 2.96%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 2.72%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 2.72%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 2.22%   |
| Synaptics UWP WBDI                                                         | 9         | 2.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 2.22%   |
| Validity Sensors VFS491                                                    | 8         | 1.98%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 1.98%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.73%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 7         | 1.73%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 1.73%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 1.73%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.48%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.23%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.23%   |
| AuthenTec AES2810                                                          | 5         | 1.23%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.23%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 0.99%   |
| Synaptics WBDI                                                             | 4         | 0.99%   |
| Synaptics Fingerprint scanner                                              | 4         | 0.99%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.99%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 0.74%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.74%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.74%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.74%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.74%   |
| Unknown                                                                    | 3         | 0.74%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 59        | 44.7%   |
| Broadcom                  | 41        | 31.06%  |
| Upek                      | 12        | 9.09%   |
| Yubico.com                | 5         | 3.79%   |
| O2 Micro                  | 5         | 3.79%   |
| Lenovo                    | 3         | 2.27%   |
| Clay Logic                | 2         | 1.52%   |
| OmniKey                   | 1         | 0.76%   |
| Gemalto (was Gemplus)     | 1         | 0.76%   |
| Bit4id                    | 1         | 0.76%   |
| Aladdin Knowledge Systems | 1         | 0.76%   |
| Advanced Card Systems     | 1         | 0.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 59        | 44.7%   |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 9.85%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 12        | 9.09%   |
| Broadcom 5880                                                                | 12        | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 6.06%   |
| Broadcom 58200                                                               | 8         | 6.06%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 3.79%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 2.27%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.27%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                                          | 1         | 0.76%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.76%   |
| OmniKey CardMan 4321                                                         | 1         | 0.76%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.76%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.76%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.76%   |
| Bit4id miniLector-s                                                          | 1         | 0.76%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.76%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1571      | 64.28%  |
| 1     | 673       | 27.54%  |
| 2     | 153       | 6.26%   |
| 3     | 28        | 1.15%   |
| 4     | 13        | 0.53%   |
| 7     | 2         | 0.08%   |
| 6     | 2         | 0.08%   |
| 5     | 2         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 400       | 36.73%  |
| Graphics card            | 173       | 15.89%  |
| Net/wireless             | 111       | 10.19%  |
| Chipcard                 | 110       | 10.1%   |
| Multimedia controller    | 65        | 5.97%   |
| Communication controller | 52        | 4.78%   |
| Unassigned class         | 40        | 3.67%   |
| Camera                   | 33        | 3.03%   |
| Bluetooth                | 23        | 2.11%   |
| Sound                    | 19        | 1.74%   |
| Card reader              | 15        | 1.38%   |
| Net/ethernet             | 13        | 1.19%   |
| Storage                  | 8         | 0.73%   |
| Network                  | 8         | 0.73%   |
| Storage/raid             | 5         | 0.46%   |
| Modem                    | 5         | 0.46%   |
| Dvb card                 | 3         | 0.28%   |
| Storage/nvme             | 2         | 0.18%   |
| Wireless                 | 1         | 0.09%   |
| Storage/ata              | 1         | 0.09%   |
| Flash memory             | 1         | 0.09%   |
| Firewire controller      | 1         | 0.09%   |

