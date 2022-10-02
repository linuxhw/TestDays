OpenMandriva 4.3 - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_4.3/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_4.3/Notebook/README.md).

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

Total: 3485

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 1545               | Notebook    | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| MSI           | MS-7235                     | Desktop     | [838e2c27f1](https://linux-hardware.org/?probe=838e2c27f1) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | Notebook    | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [68b0c0ca1a](https://linux-hardware.org/?probe=68b0c0ca1a) | Oct 01, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [1a0d8b695d](https://linux-hardware.org/?probe=1a0d8b695d) | Oct 01, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [a46521af41](https://linux-hardware.org/?probe=a46521af41) | Oct 01, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [982b143d73](https://linux-hardware.org/?probe=982b143d73) | Oct 01, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [d967f57569](https://linux-hardware.org/?probe=d967f57569) | Oct 01, 2022 |
| ASUSTek       | M5A87                       | Desktop     | [89ca067566](https://linux-hardware.org/?probe=89ca067566) | Oct 01, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [8c24fa2271](https://linux-hardware.org/?probe=8c24fa2271) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [646f4ffa8e](https://linux-hardware.org/?probe=646f4ffa8e) | Oct 01, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [75b0aa3c75](https://linux-hardware.org/?probe=75b0aa3c75) | Sep 30, 2022 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [a6b14fdcf3](https://linux-hardware.org/?probe=a6b14fdcf3) | Sep 30, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| Acer          | Batman A01                  | Desktop     | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [cfe1aba7e6](https://linux-hardware.org/?probe=cfe1aba7e6) | Sep 30, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [66877298d4](https://linux-hardware.org/?probe=66877298d4) | Sep 30, 2022 |
| Dell          | Latitude E6520              | Notebook    | [04817b4ceb](https://linux-hardware.org/?probe=04817b4ceb) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [11e4602764](https://linux-hardware.org/?probe=11e4602764) | Sep 30, 2022 |
| Dell          | Latitude 3310               | Notebook    | [3c4874fa51](https://linux-hardware.org/?probe=3c4874fa51) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| Toshiba       | Satellite L505              | Notebook    | [3e91e2bfaf](https://linux-hardware.org/?probe=3e91e2bfaf) | Sep 29, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [3990ec6cb0](https://linux-hardware.org/?probe=3990ec6cb0) | Sep 29, 2022 |
| HP            | Compaq 6720s                | Notebook    | [ddb5163310](https://linux-hardware.org/?probe=ddb5163310) | Sep 29, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [88d57c6319](https://linux-hardware.org/?probe=88d57c6319) | Sep 29, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Corei... | Desktop     | [a40d59533c](https://linux-hardware.org/?probe=a40d59533c) | Sep 29, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [9414d73ae0](https://linux-hardware.org/?probe=9414d73ae0) | Sep 29, 2022 |
| Acer          | Veriton M275                | Desktop     | [f871926a8e](https://linux-hardware.org/?probe=f871926a8e) | Sep 29, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [5a7ad7dba9](https://linux-hardware.org/?probe=5a7ad7dba9) | Sep 28, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6f1ecca2f0](https://linux-hardware.org/?probe=6f1ecca2f0) | Sep 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| Dell          | Latitude 3310               | Notebook    | [c21a321dce](https://linux-hardware.org/?probe=c21a321dce) | Sep 28, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [2e9902fee0](https://linux-hardware.org/?probe=2e9902fee0) | Sep 28, 2022 |
| Dell          | Vostro 5391                 | Notebook    | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [932a938506](https://linux-hardware.org/?probe=932a938506) | Sep 28, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [c3041b210f](https://linux-hardware.org/?probe=c3041b210f) | Sep 28, 2022 |
| Sony          | VPCEH1S1R                   | Notebook    | [5214bb023f](https://linux-hardware.org/?probe=5214bb023f) | Sep 27, 2022 |
| Dell          | Latitude 3300               | Notebook    | [365349d964](https://linux-hardware.org/?probe=365349d964) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [af23e43e99](https://linux-hardware.org/?probe=af23e43e99) | Sep 27, 2022 |
| Dell          | Latitude 3310               | Notebook    | [313ab64584](https://linux-hardware.org/?probe=313ab64584) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [d46d96565b](https://linux-hardware.org/?probe=d46d96565b) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [f5f99a7234](https://linux-hardware.org/?probe=f5f99a7234) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7cea84adb2](https://linux-hardware.org/?probe=7cea84adb2) | Sep 27, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [a33ab40c8b](https://linux-hardware.org/?probe=a33ab40c8b) | Sep 27, 2022 |
| Dell          | Latitude 3120               | Convertible | [bc34bf4d73](https://linux-hardware.org/?probe=bc34bf4d73) | Sep 27, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [3bafc34ffc](https://linux-hardware.org/?probe=3bafc34ffc) | Sep 27, 2022 |
| Packard Be... | EasyNote LS44SB             | Notebook    | [184a0768bd](https://linux-hardware.org/?probe=184a0768bd) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [56ac60a3dc](https://linux-hardware.org/?probe=56ac60a3dc) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [898f9bf963](https://linux-hardware.org/?probe=898f9bf963) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [8736347f60](https://linux-hardware.org/?probe=8736347f60) | Sep 26, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ee7c1fce66](https://linux-hardware.org/?probe=ee7c1fce66) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9d1392e945](https://linux-hardware.org/?probe=9d1392e945) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0f1fb4687f](https://linux-hardware.org/?probe=0f1fb4687f) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [6ce0a09785](https://linux-hardware.org/?probe=6ce0a09785) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [a6ce17cd6b](https://linux-hardware.org/?probe=a6ce17cd6b) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [87af9a8980](https://linux-hardware.org/?probe=87af9a8980) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [9458cffde8](https://linux-hardware.org/?probe=9458cffde8) | Sep 26, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8749a17d26](https://linux-hardware.org/?probe=8749a17d26) | Sep 25, 2022 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [a7aadaeed0](https://linux-hardware.org/?probe=a7aadaeed0) | Sep 25, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [41db205ec7](https://linux-hardware.org/?probe=41db205ec7) | Sep 25, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | Notebook    | [6c2b4ce4b1](https://linux-hardware.org/?probe=6c2b4ce4b1) | Sep 25, 2022 |
| ASUSTek       | CM1740                      | Desktop     | [6ebc913933](https://linux-hardware.org/?probe=6ebc913933) | Sep 25, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [6c6ae30eba](https://linux-hardware.org/?probe=6c6ae30eba) | Sep 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [02925c7220](https://linux-hardware.org/?probe=02925c7220) | Sep 24, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [c354f2b293](https://linux-hardware.org/?probe=c354f2b293) | Sep 24, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [7411a700cf](https://linux-hardware.org/?probe=7411a700cf) | Sep 24, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| Dell          | 0PTTT9 A00                  | Desktop     | [21bde061e9](https://linux-hardware.org/?probe=21bde061e9) | Sep 23, 2022 |
| Dell          | Latitude 3120               | Convertible | [5281ee08e1](https://linux-hardware.org/?probe=5281ee08e1) | Sep 23, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4c5dc33267](https://linux-hardware.org/?probe=4c5dc33267) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9c4d48864b](https://linux-hardware.org/?probe=9c4d48864b) | Sep 23, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | Desktop     | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [443df1ca5c](https://linux-hardware.org/?probe=443df1ca5c) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [061ef6f153](https://linux-hardware.org/?probe=061ef6f153) | Sep 23, 2022 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [a99682c38d](https://linux-hardware.org/?probe=a99682c38d) | Sep 23, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [2b37d81d4c](https://linux-hardware.org/?probe=2b37d81d4c) | Sep 22, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [2527dc6ea0](https://linux-hardware.org/?probe=2527dc6ea0) | Sep 22, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [9b451feb14](https://linux-hardware.org/?probe=9b451feb14) | Sep 22, 2022 |
| HP            | Compaq 15                   | Notebook    | [345fe48777](https://linux-hardware.org/?probe=345fe48777) | Sep 22, 2022 |
| Lenovo        | ThinkPad X200s 7470WWD      | Notebook    | [268aa65de3](https://linux-hardware.org/?probe=268aa65de3) | Sep 22, 2022 |
| ASUSTek       | K70AD                       | Notebook    | [49dff3ffb5](https://linux-hardware.org/?probe=49dff3ffb5) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | Notebook    | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [989f23b214](https://linux-hardware.org/?probe=989f23b214) | Sep 21, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| HP            | 1998                        | Desktop     | [5148539ae1](https://linux-hardware.org/?probe=5148539ae1) | Sep 21, 2022 |
| Dell          | G5 5505                     | Notebook    | [82017aa2ae](https://linux-hardware.org/?probe=82017aa2ae) | Sep 21, 2022 |
| MACHINIST     | B75 PRO V1.0                | Desktop     | [752cb8efae](https://linux-hardware.org/?probe=752cb8efae) | Sep 21, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [dd730980b1](https://linux-hardware.org/?probe=dd730980b1) | Sep 20, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a82f4ceccc](https://linux-hardware.org/?probe=a82f4ceccc) | Sep 20, 2022 |
| Lenovo        | 3728 SDK0R32862 WIN 3258... | Desktop     | [d78d85bde3](https://linux-hardware.org/?probe=d78d85bde3) | Sep 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8003baae8c](https://linux-hardware.org/?probe=8003baae8c) | Sep 19, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [a2d230d217](https://linux-hardware.org/?probe=a2d230d217) | Sep 19, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [33e582251a](https://linux-hardware.org/?probe=33e582251a) | Sep 19, 2022 |
| Lenovo        | G50-80 80R0                 | Notebook    | [f04ed15344](https://linux-hardware.org/?probe=f04ed15344) | Sep 19, 2022 |
| Samsung       | R530/R730                   | Notebook    | [0d4e13e70f](https://linux-hardware.org/?probe=0d4e13e70f) | Sep 19, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0e1784b38d](https://linux-hardware.org/?probe=0e1784b38d) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [983266d6ba](https://linux-hardware.org/?probe=983266d6ba) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [374de3c13c](https://linux-hardware.org/?probe=374de3c13c) | Sep 19, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [bc2dd8505b](https://linux-hardware.org/?probe=bc2dd8505b) | Sep 19, 2022 |
| HP            | 2B34                        | Desktop     | [a9e82bbb40](https://linux-hardware.org/?probe=a9e82bbb40) | Sep 19, 2022 |
| Dell          | Latitude 3310               | Notebook    | [55332651e0](https://linux-hardware.org/?probe=55332651e0) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [e6b9b405e8](https://linux-hardware.org/?probe=e6b9b405e8) | Sep 19, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [448ba707f6](https://linux-hardware.org/?probe=448ba707f6) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Notebook    | [558e95141d](https://linux-hardware.org/?probe=558e95141d) | Sep 19, 2022 |
| Dell          | Latitude 3300               | Notebook    | [a2513a9849](https://linux-hardware.org/?probe=a2513a9849) | Sep 19, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [892c3fb361](https://linux-hardware.org/?probe=892c3fb361) | Sep 18, 2022 |
| NEC Comput... | PC-VK26MXZCE                | Notebook    | [db8f5e4181](https://linux-hardware.org/?probe=db8f5e4181) | Sep 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| HP            | 2B29                        | Desktop     | [391e407d29](https://linux-hardware.org/?probe=391e407d29) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| HP            | 843F                        | Desktop     | [7694ed2ffa](https://linux-hardware.org/?probe=7694ed2ffa) | Sep 18, 2022 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [b9503c9c28](https://linux-hardware.org/?probe=b9503c9c28) | Sep 18, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [65c4f113d8](https://linux-hardware.org/?probe=65c4f113d8) | Sep 18, 2022 |
| HP            | ProBook 6470b               | Notebook    | [3821322b95](https://linux-hardware.org/?probe=3821322b95) | Sep 18, 2022 |
| Acer          | Switch SA5-271P             | Tablet      | [c9900a8e2f](https://linux-hardware.org/?probe=c9900a8e2f) | Sep 17, 2022 |
| HP            | Notebook                    | Notebook    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | ThinkPad E570 20H5009NUS    | Notebook    | [c64258edc0](https://linux-hardware.org/?probe=c64258edc0) | Sep 17, 2022 |
| Toshiba       | TECRA S10                   | Notebook    | [602d81b7c5](https://linux-hardware.org/?probe=602d81b7c5) | Sep 17, 2022 |
| Toshiba       | Satellite P845T             | Notebook    | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [f75308c465](https://linux-hardware.org/?probe=f75308c465) | Sep 17, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [19d0260ef6](https://linux-hardware.org/?probe=19d0260ef6) | Sep 17, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [6d8f7ffe97](https://linux-hardware.org/?probe=6d8f7ffe97) | Sep 17, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [93b43e5bb5](https://linux-hardware.org/?probe=93b43e5bb5) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | Notebook    | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e472e7fdde](https://linux-hardware.org/?probe=e472e7fdde) | Sep 16, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [1ccce4a76a](https://linux-hardware.org/?probe=1ccce4a76a) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e04ec1834f](https://linux-hardware.org/?probe=e04ec1834f) | Sep 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Lenovo        | ThinkPad T530 2429F33       | Notebook    | [790a0f2a25](https://linux-hardware.org/?probe=790a0f2a25) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9d15a7c8a2](https://linux-hardware.org/?probe=9d15a7c8a2) | Sep 14, 2022 |
| HP            | 1495                        | Desktop     | [462389df36](https://linux-hardware.org/?probe=462389df36) | Sep 14, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [832824de54](https://linux-hardware.org/?probe=832824de54) | Sep 14, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [6ee9d3e2c4](https://linux-hardware.org/?probe=6ee9d3e2c4) | Sep 14, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Timi          | TM1612                      | Notebook    | [536fc04dcb](https://linux-hardware.org/?probe=536fc04dcb) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Lenovo        | ThinkPad X230 2324GA1       | Notebook    | [c4e6cc1489](https://linux-hardware.org/?probe=c4e6cc1489) | Sep 14, 2022 |
| Toshiba       | Satellite L55-B             | Notebook    | [b593ff9e20](https://linux-hardware.org/?probe=b593ff9e20) | Sep 14, 2022 |
| HP            | Notebook                    | Notebook    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| Dell          | Latitude 3120               | Convertible | [a8315e1147](https://linux-hardware.org/?probe=a8315e1147) | Sep 13, 2022 |
| Sun Micros... | ASSY,MOTHERBOARD,X4170 5... | Server      | [ea845ec5ea](https://linux-hardware.org/?probe=ea845ec5ea) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | Notebook    | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| MSI           | Z97 MPOWER                  | Desktop     | [a98aedda05](https://linux-hardware.org/?probe=a98aedda05) | Sep 13, 2022 |
| Compal        | NCL60/61                    | Notebook    | [f1f5499af8](https://linux-hardware.org/?probe=f1f5499af8) | Sep 12, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [0937dcb89c](https://linux-hardware.org/?probe=0937dcb89c) | Sep 12, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [2eb979e980](https://linux-hardware.org/?probe=2eb979e980) | Sep 12, 2022 |
| Toshiba       | Satellite C655              | Notebook    | [16a4aa3cd8](https://linux-hardware.org/?probe=16a4aa3cd8) | Sep 12, 2022 |
| Dell          | 0H8052                      | Desktop     | [1ade497706](https://linux-hardware.org/?probe=1ade497706) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| Shuttle       | XH310V2                     | Desktop     | [c99efae947](https://linux-hardware.org/?probe=c99efae947) | Sep 12, 2022 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| HP            | 158B                        | Desktop     | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [58b48039ce](https://linux-hardware.org/?probe=58b48039ce) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| HP            | 304Bh                       | Desktop     | [0a7bcbdd9e](https://linux-hardware.org/?probe=0a7bcbdd9e) | Sep 11, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [5d0092ffc1](https://linux-hardware.org/?probe=5d0092ffc1) | Sep 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| MSI           | B560M PRO                   | Desktop     | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| HP            | Notebook                    | Notebook    | [2984aef090](https://linux-hardware.org/?probe=2984aef090) | Sep 11, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [9e730cbd6a](https://linux-hardware.org/?probe=9e730cbd6a) | Sep 11, 2022 |
| MSI           | 0A48                        | Desktop     | [2619140b48](https://linux-hardware.org/?probe=2619140b48) | Sep 10, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b5842ca017](https://linux-hardware.org/?probe=b5842ca017) | Sep 10, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [021bcda428](https://linux-hardware.org/?probe=021bcda428) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | Notebook    | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| LG Electro... | U560-G.BG31P1               | Notebook    | [741c3eddbe](https://linux-hardware.org/?probe=741c3eddbe) | Sep 10, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [40c43aff10](https://linux-hardware.org/?probe=40c43aff10) | Sep 10, 2022 |
| Samsung       | SX60P                       | Notebook    | [1e0ea8e787](https://linux-hardware.org/?probe=1e0ea8e787) | Sep 09, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [cd84312899](https://linux-hardware.org/?probe=cd84312899) | Sep 09, 2022 |
| Dell          | 04075X A00                  | All in one  | [e2ff438b3c](https://linux-hardware.org/?probe=e2ff438b3c) | Sep 09, 2022 |
| Dell          | Precision 7560              | Notebook    | [3e2d1a120c](https://linux-hardware.org/?probe=3e2d1a120c) | Sep 09, 2022 |
| Dell          | Latitude E4300              | Notebook    | [634c1467f8](https://linux-hardware.org/?probe=634c1467f8) | Sep 09, 2022 |
| Dell          | Latitude 3120               | Convertible | [6b2b6b7aa9](https://linux-hardware.org/?probe=6b2b6b7aa9) | Sep 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [36b349b529](https://linux-hardware.org/?probe=36b349b529) | Sep 09, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [5c21c2acc6](https://linux-hardware.org/?probe=5c21c2acc6) | Sep 09, 2022 |
| Positivo      | H14BT58                     | Notebook    | [669a466b1c](https://linux-hardware.org/?probe=669a466b1c) | Sep 09, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [1a5c8e32b7](https://linux-hardware.org/?probe=1a5c8e32b7) | Sep 09, 2022 |
| Lenovo        | IdeaPad S400 20195          | Notebook    | [6bd3292f42](https://linux-hardware.org/?probe=6bd3292f42) | Sep 08, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [ee7071f4e7](https://linux-hardware.org/?probe=ee7071f4e7) | Sep 08, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [036c262ad4](https://linux-hardware.org/?probe=036c262ad4) | Sep 08, 2022 |
| Lenovo        | B5400 20278                 | Notebook    | [1c9d752f91](https://linux-hardware.org/?probe=1c9d752f91) | Sep 07, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4a39ae67d5](https://linux-hardware.org/?probe=4a39ae67d5) | Sep 07, 2022 |
| Lenovo        | G580                        | Notebook    | [922ede2a50](https://linux-hardware.org/?probe=922ede2a50) | Sep 07, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [70e3d85420](https://linux-hardware.org/?probe=70e3d85420) | Sep 07, 2022 |
| MSI           | IONA                        | Desktop     | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | Desktop     | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [22171cc2a6](https://linux-hardware.org/?probe=22171cc2a6) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | Desktop     | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [14f91e3a08](https://linux-hardware.org/?probe=14f91e3a08) | Sep 07, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [cf398ae303](https://linux-hardware.org/?probe=cf398ae303) | Sep 07, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [cca59cbb3c](https://linux-hardware.org/?probe=cca59cbb3c) | Sep 07, 2022 |
| Positivo      | Mobile                      | Notebook    | [1378222b07](https://linux-hardware.org/?probe=1378222b07) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [46161b573f](https://linux-hardware.org/?probe=46161b573f) | Sep 06, 2022 |
| Lenovo        | ThinkPad Edge E531 68856... | Notebook    | [498682ac13](https://linux-hardware.org/?probe=498682ac13) | Sep 06, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [8a66fbdadd](https://linux-hardware.org/?probe=8a66fbdadd) | Sep 06, 2022 |
| Sony          | VPCSB3X9E                   | Notebook    | [03bd901e4f](https://linux-hardware.org/?probe=03bd901e4f) | Sep 06, 2022 |
| ECS           | GeForce 8000 series         | Desktop     | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4236PNP       | Notebook    | [7c3dc0af20](https://linux-hardware.org/?probe=7c3dc0af20) | Sep 06, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [78e0cb1ca2](https://linux-hardware.org/?probe=78e0cb1ca2) | Sep 06, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [39bc7728ac](https://linux-hardware.org/?probe=39bc7728ac) | Sep 06, 2022 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Lenovo        | ThinkPad L440 20ASS11T00    | Notebook    | [526d97c730](https://linux-hardware.org/?probe=526d97c730) | Sep 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [537708f71a](https://linux-hardware.org/?probe=537708f71a) | Sep 06, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [6f848cd309](https://linux-hardware.org/?probe=6f848cd309) | Sep 06, 2022 |
| Dell          | Vostro 14-5480              | Notebook    | [fb3ae25db8](https://linux-hardware.org/?probe=fb3ae25db8) | Sep 06, 2022 |
| Dell          | Latitude E6220              | Notebook    | [af87786838](https://linux-hardware.org/?probe=af87786838) | Sep 05, 2022 |
| Lenovo        | ThinkPad T530 2429W4Y       | Notebook    | [572b46f025](https://linux-hardware.org/?probe=572b46f025) | Sep 05, 2022 |
| ASUSTek       | K53BY                       | Notebook    | [efbc2be1a7](https://linux-hardware.org/?probe=efbc2be1a7) | Sep 05, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [d9a3103936](https://linux-hardware.org/?probe=d9a3103936) | Sep 05, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| Toshiba       | Satellite C55-A-157         | Notebook    | [483a0f4f49](https://linux-hardware.org/?probe=483a0f4f49) | Sep 05, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [a783dcd3ca](https://linux-hardware.org/?probe=a783dcd3ca) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| HP            | 8076                        | Desktop     | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [4d5b865aed](https://linux-hardware.org/?probe=4d5b865aed) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [e2115bf207](https://linux-hardware.org/?probe=e2115bf207) | Sep 05, 2022 |
| ASUSTek       | X45C                        | Notebook    | [7267b251b6](https://linux-hardware.org/?probe=7267b251b6) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | Desktop     | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [b36d7be7c1](https://linux-hardware.org/?probe=b36d7be7c1) | Sep 04, 2022 |
| HP            | 304Bh                       | Desktop     | [d395dd6c91](https://linux-hardware.org/?probe=d395dd6c91) | Sep 04, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [dcfbebc2dd](https://linux-hardware.org/?probe=dcfbebc2dd) | Sep 04, 2022 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [fb64be85f1](https://linux-hardware.org/?probe=fb64be85f1) | Sep 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [113f737135](https://linux-hardware.org/?probe=113f737135) | Sep 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [96d17dc188](https://linux-hardware.org/?probe=96d17dc188) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [792cbc3418](https://linux-hardware.org/?probe=792cbc3418) | Sep 04, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [3ba0635033](https://linux-hardware.org/?probe=3ba0635033) | Sep 04, 2022 |
| MSI           | MS-168B                     | Notebook    | [a0a6645eef](https://linux-hardware.org/?probe=a0a6645eef) | Sep 04, 2022 |
| Jumper        | EZbook                      | Notebook    | [d67fae436c](https://linux-hardware.org/?probe=d67fae436c) | Sep 04, 2022 |
| HP            | 8767 A                      | Desktop     | [33800541e3](https://linux-hardware.org/?probe=33800541e3) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d7c3304983](https://linux-hardware.org/?probe=d7c3304983) | Sep 04, 2022 |
| Gigabyte      | B560 AORUS PRO AX           | Desktop     | [fbd2e39516](https://linux-hardware.org/?probe=fbd2e39516) | Sep 04, 2022 |
| ECS           | H61H-G11/7.0                | Desktop     | [790b93cbee](https://linux-hardware.org/?probe=790b93cbee) | Sep 03, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [3d542c8484](https://linux-hardware.org/?probe=3d542c8484) | Sep 03, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [c2251f33ef](https://linux-hardware.org/?probe=c2251f33ef) | Sep 03, 2022 |
| HP            | 620                         | Notebook    | [34002dc814](https://linux-hardware.org/?probe=34002dc814) | Sep 02, 2022 |
| Unknown       | Intel X79                   | Desktop     | [9e666e1530](https://linux-hardware.org/?probe=9e666e1530) | Sep 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [6a2cb26049](https://linux-hardware.org/?probe=6a2cb26049) | Sep 02, 2022 |
| Getac         | B300-X                      | Notebook    | [927b99c2e0](https://linux-hardware.org/?probe=927b99c2e0) | Sep 02, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| Dell          | Latitude 3120               | Notebook    | [8716f564d8](https://linux-hardware.org/?probe=8716f564d8) | Sep 02, 2022 |
| Dell          | Latitude 3120               | Convertible | [44a711d7ce](https://linux-hardware.org/?probe=44a711d7ce) | Sep 02, 2022 |
| Dell          | Latitude 3120               | Convertible | [cb976a52d2](https://linux-hardware.org/?probe=cb976a52d2) | Sep 02, 2022 |
| HP            | 8053                        | Desktop     | [2e48f3f13e](https://linux-hardware.org/?probe=2e48f3f13e) | Sep 02, 2022 |
| Dell          | 0TP412                      | Desktop     | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [b9502cc4a9](https://linux-hardware.org/?probe=b9502cc4a9) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d27c20dcf9](https://linux-hardware.org/?probe=d27c20dcf9) | Sep 01, 2022 |
| Packard Be... | DOT S                       | Notebook    | [b5b03f1cf7](https://linux-hardware.org/?probe=b5b03f1cf7) | Sep 01, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [e2fc506c38](https://linux-hardware.org/?probe=e2fc506c38) | Sep 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [d30269b33c](https://linux-hardware.org/?probe=d30269b33c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [c9a801a4d2](https://linux-hardware.org/?probe=c9a801a4d2) | Sep 01, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7140822520](https://linux-hardware.org/?probe=7140822520) | Sep 01, 2022 |
| ASUSTek       | X550ZE                      | Notebook    | [187a6feadf](https://linux-hardware.org/?probe=187a6feadf) | Sep 01, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1a173c5ea0](https://linux-hardware.org/?probe=1a173c5ea0) | Sep 01, 2022 |
| HP            | Pavilion g6                 | Notebook    | [cc725d880c](https://linux-hardware.org/?probe=cc725d880c) | Aug 31, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [710d1e9a9b](https://linux-hardware.org/?probe=710d1e9a9b) | Aug 31, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [120400698e](https://linux-hardware.org/?probe=120400698e) | Aug 31, 2022 |
| Vorke         | V1 Plus                     | Desktop     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [0ea749e83c](https://linux-hardware.org/?probe=0ea749e83c) | Aug 30, 2022 |
| Dell          | Precision M6400             | Notebook    | [3cf32e24fa](https://linux-hardware.org/?probe=3cf32e24fa) | Aug 30, 2022 |
| HP            | 0A60h                       | Desktop     | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [33aaa7baf4](https://linux-hardware.org/?probe=33aaa7baf4) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | Desktop     | [0099ab3432](https://linux-hardware.org/?probe=0099ab3432) | Aug 29, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [536742931b](https://linux-hardware.org/?probe=536742931b) | Aug 29, 2022 |
| Dell          | Latitude 3300               | Notebook    | [bea8e53929](https://linux-hardware.org/?probe=bea8e53929) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M58p 6234CL2    | Desktop     | [14449a705a](https://linux-hardware.org/?probe=14449a705a) | Aug 29, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [99f7df96c2](https://linux-hardware.org/?probe=99f7df96c2) | Aug 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| Dell          | Studio 1735                 | Notebook    | [912f409b37](https://linux-hardware.org/?probe=912f409b37) | Aug 28, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [d8a4e4d954](https://linux-hardware.org/?probe=d8a4e4d954) | Aug 28, 2022 |
| HP            | 620                         | Notebook    | [b16c60f4cf](https://linux-hardware.org/?probe=b16c60f4cf) | Aug 28, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [91371e505d](https://linux-hardware.org/?probe=91371e505d) | Aug 28, 2022 |
| Acer          | AO722                       | Notebook    | [377ad8686f](https://linux-hardware.org/?probe=377ad8686f) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [a18db0fafd](https://linux-hardware.org/?probe=a18db0fafd) | Aug 27, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [f74dc71ad8](https://linux-hardware.org/?probe=f74dc71ad8) | Aug 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [d6c013a669](https://linux-hardware.org/?probe=d6c013a669) | Aug 27, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [67712f11d9](https://linux-hardware.org/?probe=67712f11d9) | Aug 27, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [459c7c1eee](https://linux-hardware.org/?probe=459c7c1eee) | Aug 27, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [cf0bc232f5](https://linux-hardware.org/?probe=cf0bc232f5) | Aug 26, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [22cc477cd2](https://linux-hardware.org/?probe=22cc477cd2) | Aug 26, 2022 |
| Apple         | Mac-CFF7D910A743CAAF iMa... | All in one  | [1b562e8768](https://linux-hardware.org/?probe=1b562e8768) | Aug 26, 2022 |
| MSI           | 760GM-P21                   | Desktop     | [7e45cde899](https://linux-hardware.org/?probe=7e45cde899) | Aug 26, 2022 |
| HP            | 1497                        | Desktop     | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [e4a6425675](https://linux-hardware.org/?probe=e4a6425675) | Aug 26, 2022 |
| HP            | 15                          | Notebook    | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| Dell          | 06MC09 A00                  | Mini pc     | [71402e3c39](https://linux-hardware.org/?probe=71402e3c39) | Aug 26, 2022 |
| Dell          | 0RJ290                      | Desktop     | [ca82162ed5](https://linux-hardware.org/?probe=ca82162ed5) | Aug 25, 2022 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [0b76e0f97d](https://linux-hardware.org/?probe=0b76e0f97d) | Aug 25, 2022 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [18e7da32e9](https://linux-hardware.org/?probe=18e7da32e9) | Aug 25, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [72888e9acb](https://linux-hardware.org/?probe=72888e9acb) | Aug 25, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [1c98247f4c](https://linux-hardware.org/?probe=1c98247f4c) | Aug 25, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [82da7782ec](https://linux-hardware.org/?probe=82da7782ec) | Aug 25, 2022 |
| HP            | 829A                        | Mini pc     | [76cb57e98d](https://linux-hardware.org/?probe=76cb57e98d) | Aug 25, 2022 |
| OEM           | A320                        | Desktop     | [4dffd629cf](https://linux-hardware.org/?probe=4dffd629cf) | Aug 25, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [b201192ebb](https://linux-hardware.org/?probe=b201192ebb) | Aug 25, 2022 |
| Dell          | Latitude E5510              | Notebook    | [c237161d31](https://linux-hardware.org/?probe=c237161d31) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d1cae6aca8](https://linux-hardware.org/?probe=d1cae6aca8) | Aug 24, 2022 |
| HP            | 21D0                        | Desktop     | [1bd58d519c](https://linux-hardware.org/?probe=1bd58d519c) | Aug 24, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | Notebook    | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f20e68e820](https://linux-hardware.org/?probe=f20e68e820) | Aug 24, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [e75751c55b](https://linux-hardware.org/?probe=e75751c55b) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [c824203d0a](https://linux-hardware.org/?probe=c824203d0a) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | Notebook    | [81b42d221d](https://linux-hardware.org/?probe=81b42d221d) | Aug 24, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [744f838dc2](https://linux-hardware.org/?probe=744f838dc2) | Aug 24, 2022 |
| Supermicro    | X10SDV-8C+-LN2F             | Server      | [a4ec1f93e5](https://linux-hardware.org/?probe=a4ec1f93e5) | Aug 23, 2022 |
| Acer          | Aspire A315-54K             | Notebook    | [685d6acc51](https://linux-hardware.org/?probe=685d6acc51) | Aug 23, 2022 |
| ICP / iEi     | B217 V1.0                   | Desktop     | [9b540ece9f](https://linux-hardware.org/?probe=9b540ece9f) | Aug 23, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [7dae220687](https://linux-hardware.org/?probe=7dae220687) | Aug 23, 2022 |
| Dell          | Latitude E5470              | Notebook    | [4cf5f4680f](https://linux-hardware.org/?probe=4cf5f4680f) | Aug 23, 2022 |
| HP            | 8158 A01                    | Mini pc     | [443d203df8](https://linux-hardware.org/?probe=443d203df8) | Aug 22, 2022 |
| Google        | Galtic                      | Notebook    | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [1de0aeba8f](https://linux-hardware.org/?probe=1de0aeba8f) | Aug 22, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [ca7534d4dc](https://linux-hardware.org/?probe=ca7534d4dc) | Aug 22, 2022 |
| Intel         | NUC11ATBC4 M53051-202       | Mini pc     | [6568854eef](https://linux-hardware.org/?probe=6568854eef) | Aug 22, 2022 |
| Acer          | Enduro EUN314-51WG          | Notebook    | [aa9ea3d520](https://linux-hardware.org/?probe=aa9ea3d520) | Aug 22, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [3d9c208d81](https://linux-hardware.org/?probe=3d9c208d81) | Aug 22, 2022 |
| Dell          | Latitude 3300               | Notebook    | [e8b139ecad](https://linux-hardware.org/?probe=e8b139ecad) | Aug 22, 2022 |
| Dell          | Latitude 3310               | Notebook    | [dedda1b96c](https://linux-hardware.org/?probe=dedda1b96c) | Aug 22, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [ec6fd6cddb](https://linux-hardware.org/?probe=ec6fd6cddb) | Aug 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [fa5f1121d5](https://linux-hardware.org/?probe=fa5f1121d5) | Aug 22, 2022 |
| Lenovo        | 36FB SDK0L77769 WIN 3423... | All in one  | [c65b675fc8](https://linux-hardware.org/?probe=c65b675fc8) | Aug 22, 2022 |
| Intel         | H61                         | Desktop     | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | Notebook    | [fdbec5aab2](https://linux-hardware.org/?probe=fdbec5aab2) | Aug 22, 2022 |
| Fujitsu       | LIFEBOOK UH552              | Notebook    | [15a1f49654](https://linux-hardware.org/?probe=15a1f49654) | Aug 21, 2022 |
| Acer          | AO725                       | Notebook    | [5eed64f77d](https://linux-hardware.org/?probe=5eed64f77d) | Aug 21, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [8de83c544f](https://linux-hardware.org/?probe=8de83c544f) | Aug 21, 2022 |
| HP            | 1998                        | Desktop     | [69b6b04268](https://linux-hardware.org/?probe=69b6b04268) | Aug 21, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | Notebook    | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [bb19c0586c](https://linux-hardware.org/?probe=bb19c0586c) | Aug 20, 2022 |
| Gigabyte      | B365M DS3H WIFI             | Desktop     | [142e25352d](https://linux-hardware.org/?probe=142e25352d) | Aug 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [56a34e0816](https://linux-hardware.org/?probe=56a34e0816) | Aug 20, 2022 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [2925e63a87](https://linux-hardware.org/?probe=2925e63a87) | Aug 20, 2022 |
| AZW           | MII-V                       | Desktop     | [59698f6b33](https://linux-hardware.org/?probe=59698f6b33) | Aug 20, 2022 |
| OEM           | Intel H81                   | Desktop     | [5e354c60d1](https://linux-hardware.org/?probe=5e354c60d1) | Aug 20, 2022 |
| HP            | Pavilion dv6                | Notebook    | [0aae35eb95](https://linux-hardware.org/?probe=0aae35eb95) | Aug 19, 2022 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [803031cd3b](https://linux-hardware.org/?probe=803031cd3b) | Aug 19, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [74b0bedd54](https://linux-hardware.org/?probe=74b0bedd54) | Aug 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [c954da96ad](https://linux-hardware.org/?probe=c954da96ad) | Aug 18, 2022 |
| Intel         | NUC7i7BNB J31145-310        | Mini pc     | [d9f1c174b3](https://linux-hardware.org/?probe=d9f1c174b3) | Aug 18, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [870fcf0f3c](https://linux-hardware.org/?probe=870fcf0f3c) | Aug 18, 2022 |
| Dell          | Latitude E5510              | Notebook    | [c7defb71d5](https://linux-hardware.org/?probe=c7defb71d5) | Aug 18, 2022 |
| Medion        | Akoya E6418 MD99620         | Notebook    | [6817b38103](https://linux-hardware.org/?probe=6817b38103) | Aug 18, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [d29438c201](https://linux-hardware.org/?probe=d29438c201) | Aug 18, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [a0a7a845e3](https://linux-hardware.org/?probe=a0a7a845e3) | Aug 18, 2022 |
| Gigabyte      | P43-ES3G                    | Desktop     | [de6e02672c](https://linux-hardware.org/?probe=de6e02672c) | Aug 18, 2022 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [d78fb85708](https://linux-hardware.org/?probe=d78fb85708) | Aug 18, 2022 |
| Positivo B... | S14SL03                     | Notebook    | [558f5a2f24](https://linux-hardware.org/?probe=558f5a2f24) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [859884934f](https://linux-hardware.org/?probe=859884934f) | Aug 17, 2022 |
| Acer          | MRS600M                     | Desktop     | [ec4c10d06e](https://linux-hardware.org/?probe=ec4c10d06e) | Aug 17, 2022 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [870d7102f5](https://linux-hardware.org/?probe=870d7102f5) | Aug 17, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [944a99ea66](https://linux-hardware.org/?probe=944a99ea66) | Aug 17, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [471659ffff](https://linux-hardware.org/?probe=471659ffff) | Aug 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [a99b3cef26](https://linux-hardware.org/?probe=a99b3cef26) | Aug 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [9bdceca056](https://linux-hardware.org/?probe=9bdceca056) | Aug 17, 2022 |
| ASUSTek       | N75SF                       | Notebook    | [3b6f89e145](https://linux-hardware.org/?probe=3b6f89e145) | Aug 17, 2022 |
| NEC Comput... | PC-LJ730MG6W                | Notebook    | [c0e6c7edb7](https://linux-hardware.org/?probe=c0e6c7edb7) | Aug 17, 2022 |
| Dell          | Latitude 3310               | Notebook    | [92f66bf3aa](https://linux-hardware.org/?probe=92f66bf3aa) | Aug 17, 2022 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [c8f8e78df8](https://linux-hardware.org/?probe=c8f8e78df8) | Aug 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [59080cc039](https://linux-hardware.org/?probe=59080cc039) | Aug 17, 2022 |
| ASUSTek       | Z550SA                      | Notebook    | [03ef043fd9](https://linux-hardware.org/?probe=03ef043fd9) | Aug 17, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [2b97e09efa](https://linux-hardware.org/?probe=2b97e09efa) | Aug 17, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [92c0a6fe2a](https://linux-hardware.org/?probe=92c0a6fe2a) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [a880d764be](https://linux-hardware.org/?probe=a880d764be) | Aug 16, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [7b3d6b544c](https://linux-hardware.org/?probe=7b3d6b544c) | Aug 16, 2022 |
| Lenovo        | ThinkPad L412 0585A84       | Notebook    | [637fa23dca](https://linux-hardware.org/?probe=637fa23dca) | Aug 16, 2022 |
| Dell          | Latitude 3310               | Notebook    | [1694bfcea7](https://linux-hardware.org/?probe=1694bfcea7) | Aug 16, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [ec4014a549](https://linux-hardware.org/?probe=ec4014a549) | Aug 16, 2022 |
| Acer          | Aspire ES1-532G             | Notebook    | [cf05c858ab](https://linux-hardware.org/?probe=cf05c858ab) | Aug 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [6c31827147](https://linux-hardware.org/?probe=6c31827147) | Aug 15, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [08e3444b3c](https://linux-hardware.org/?probe=08e3444b3c) | Aug 15, 2022 |
| HP            | 2AE2                        | Desktop     | [1fd0bb70dc](https://linux-hardware.org/?probe=1fd0bb70dc) | Aug 15, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [3dcdc1dc6a](https://linux-hardware.org/?probe=3dcdc1dc6a) | Aug 15, 2022 |
| Gigabyte      | P43-ES3G                    | Desktop     | [2b0691bddd](https://linux-hardware.org/?probe=2b0691bddd) | Aug 15, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [56ee42afe3](https://linux-hardware.org/?probe=56ee42afe3) | Aug 15, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [170b178361](https://linux-hardware.org/?probe=170b178361) | Aug 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [4b1440875b](https://linux-hardware.org/?probe=4b1440875b) | Aug 14, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [15ffff65c0](https://linux-hardware.org/?probe=15ffff65c0) | Aug 14, 2022 |
| HP            | ProBook 4330s               | Notebook    | [62ff6ffc08](https://linux-hardware.org/?probe=62ff6ffc08) | Aug 14, 2022 |
| HP            | 18E7                        | Desktop     | [06374a6240](https://linux-hardware.org/?probe=06374a6240) | Aug 14, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [55c4e8059c](https://linux-hardware.org/?probe=55c4e8059c) | Aug 14, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [30146876c6](https://linux-hardware.org/?probe=30146876c6) | Aug 14, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [e9c64a8a5c](https://linux-hardware.org/?probe=e9c64a8a5c) | Aug 14, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [4386fccad1](https://linux-hardware.org/?probe=4386fccad1) | Aug 14, 2022 |
| Acer          | Aspire VN7-571G             | Notebook    | [0d6dfdd6e0](https://linux-hardware.org/?probe=0d6dfdd6e0) | Aug 14, 2022 |
| HP            | Pavilion dv9500             | Notebook    | [fd3bd18049](https://linux-hardware.org/?probe=fd3bd18049) | Aug 14, 2022 |
| HP            | 829A                        | Mini pc     | [0e36f81a7b](https://linux-hardware.org/?probe=0e36f81a7b) | Aug 13, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ee169e47b3](https://linux-hardware.org/?probe=ee169e47b3) | Aug 13, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [83fcabac55](https://linux-hardware.org/?probe=83fcabac55) | Aug 13, 2022 |
| Dell          | Vostro 1520                 | Notebook    | [9dab88f3ee](https://linux-hardware.org/?probe=9dab88f3ee) | Aug 13, 2022 |
| Positivo      | EC10IS1                     | Notebook    | [b66cd42f99](https://linux-hardware.org/?probe=b66cd42f99) | Aug 13, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [4e57c20454](https://linux-hardware.org/?probe=4e57c20454) | Aug 13, 2022 |
| Lenovo        | ThinkCentre XXXX 739527G    | Desktop     | [ca5fe11e2c](https://linux-hardware.org/?probe=ca5fe11e2c) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [fd41ccab04](https://linux-hardware.org/?probe=fd41ccab04) | Aug 13, 2022 |
| HP            | 1850                        | Desktop     | [33933e3e5d](https://linux-hardware.org/?probe=33933e3e5d) | Aug 12, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [50b7221c5a](https://linux-hardware.org/?probe=50b7221c5a) | Aug 12, 2022 |
| Positivo      | Mobile                      | Notebook    | [bddf3b59d4](https://linux-hardware.org/?probe=bddf3b59d4) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [bc32ff70b7](https://linux-hardware.org/?probe=bc32ff70b7) | Aug 12, 2022 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [762d78160d](https://linux-hardware.org/?probe=762d78160d) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [ff1be50f8c](https://linux-hardware.org/?probe=ff1be50f8c) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | Notebook    | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| ASUSTek       | K73BR                       | Notebook    | [67f5d3f176](https://linux-hardware.org/?probe=67f5d3f176) | Aug 12, 2022 |
| Acer          | Aspire 4330 V1.22           | Notebook    | [dee8895134](https://linux-hardware.org/?probe=dee8895134) | Aug 12, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [c1b14847f1](https://linux-hardware.org/?probe=c1b14847f1) | Aug 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [2f3db9cd91](https://linux-hardware.org/?probe=2f3db9cd91) | Aug 12, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [d949d71a19](https://linux-hardware.org/?probe=d949d71a19) | Aug 12, 2022 |
| Lenovo        | Unknown                     | Notebook    | [79688945e1](https://linux-hardware.org/?probe=79688945e1) | Aug 11, 2022 |
| ASRock        | Z97M Pro4                   | Desktop     | [245d189a61](https://linux-hardware.org/?probe=245d189a61) | Aug 11, 2022 |
| Dell          | G5 5505                     | Notebook    | [cbbcb7c9a2](https://linux-hardware.org/?probe=cbbcb7c9a2) | Aug 11, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [29f3354492](https://linux-hardware.org/?probe=29f3354492) | Aug 11, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [73bf30c596](https://linux-hardware.org/?probe=73bf30c596) | Aug 11, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [c765f5b81c](https://linux-hardware.org/?probe=c765f5b81c) | Aug 11, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [cac00fb432](https://linux-hardware.org/?probe=cac00fb432) | Aug 11, 2022 |
| HP            | Pavilion dm3                | Notebook    | [7152a48ede](https://linux-hardware.org/?probe=7152a48ede) | Aug 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3b20387bcc](https://linux-hardware.org/?probe=3b20387bcc) | Aug 10, 2022 |
| HP            | 240 G3                      | Notebook    | [77225815d2](https://linux-hardware.org/?probe=77225815d2) | Aug 10, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [31bdc504d4](https://linux-hardware.org/?probe=31bdc504d4) | Aug 10, 2022 |
| Dell          | 07KY25 A00                  | Desktop     | [676025f81a](https://linux-hardware.org/?probe=676025f81a) | Aug 10, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [62d813423e](https://linux-hardware.org/?probe=62d813423e) | Aug 10, 2022 |
| MSI           | X470 GAMING M7 AC           | Desktop     | [58947090d5](https://linux-hardware.org/?probe=58947090d5) | Aug 09, 2022 |
| eMachines     | Veriton V2110               | Desktop     | [3492540d77](https://linux-hardware.org/?probe=3492540d77) | Aug 09, 2022 |
| Lenovo        | 36ED SDK0M26027 WIN 3273... | All in one  | [6481787b51](https://linux-hardware.org/?probe=6481787b51) | Aug 09, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [2df31a9fbf](https://linux-hardware.org/?probe=2df31a9fbf) | Aug 09, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [4f83e69c06](https://linux-hardware.org/?probe=4f83e69c06) | Aug 09, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [89a77b442f](https://linux-hardware.org/?probe=89a77b442f) | Aug 09, 2022 |
| HP            | 630                         | Notebook    | [fc9bc69e9a](https://linux-hardware.org/?probe=fc9bc69e9a) | Aug 09, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [0afee77b44](https://linux-hardware.org/?probe=0afee77b44) | Aug 09, 2022 |
| Gigabyte      | EP35-DS3P                   | Desktop     | [5c29aee903](https://linux-hardware.org/?probe=5c29aee903) | Aug 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [9d6be5eb68](https://linux-hardware.org/?probe=9d6be5eb68) | Aug 08, 2022 |
| ASUSTek       | AT3IONT-I DELUXE            | Desktop     | [642e31466d](https://linux-hardware.org/?probe=642e31466d) | Aug 08, 2022 |
| Dell          | 0782GW A01                  | Desktop     | [b3ebc3aed3](https://linux-hardware.org/?probe=b3ebc3aed3) | Aug 08, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [0dbab56588](https://linux-hardware.org/?probe=0dbab56588) | Aug 08, 2022 |
| HP            | 15                          | Notebook    | [ef66e0296e](https://linux-hardware.org/?probe=ef66e0296e) | Aug 08, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [616a031820](https://linux-hardware.org/?probe=616a031820) | Aug 08, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1f20b0f54b](https://linux-hardware.org/?probe=1f20b0f54b) | Aug 08, 2022 |
| HP            | 304Bh                       | Desktop     | [e1e3f301cb](https://linux-hardware.org/?probe=e1e3f301cb) | Aug 08, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [362398e54e](https://linux-hardware.org/?probe=362398e54e) | Aug 08, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3817e724ac](https://linux-hardware.org/?probe=3817e724ac) | Aug 08, 2022 |
| Intel         | H61                         | Desktop     | [eabc8be629](https://linux-hardware.org/?probe=eabc8be629) | Aug 08, 2022 |
| BESSTAR Te... | AB1                         | Mini pc     | [fc51f2c4b7](https://linux-hardware.org/?probe=fc51f2c4b7) | Aug 08, 2022 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [4d6a861120](https://linux-hardware.org/?probe=4d6a861120) | Aug 07, 2022 |
| HP            | Compaq 15                   | Notebook    | [de4b6e0511](https://linux-hardware.org/?probe=de4b6e0511) | Aug 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [95f444c24c](https://linux-hardware.org/?probe=95f444c24c) | Aug 07, 2022 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [6c434341ce](https://linux-hardware.org/?probe=6c434341ce) | Aug 07, 2022 |
| ASUSTek       | M3A78 PRO                   | Desktop     | [0b63e92a55](https://linux-hardware.org/?probe=0b63e92a55) | Aug 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f9850e0a1e](https://linux-hardware.org/?probe=f9850e0a1e) | Aug 07, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [4e36acba35](https://linux-hardware.org/?probe=4e36acba35) | Aug 07, 2022 |
| Dell          | Latitude 3189               | Notebook    | [63c2818521](https://linux-hardware.org/?probe=63c2818521) | Aug 07, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [810a9d1c2c](https://linux-hardware.org/?probe=810a9d1c2c) | Aug 07, 2022 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [bfceb8ba35](https://linux-hardware.org/?probe=bfceb8ba35) | Aug 07, 2022 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | Notebook    | [f3a36d0f3a](https://linux-hardware.org/?probe=f3a36d0f3a) | Aug 07, 2022 |
| Acer          | Swift SF114-31              | Notebook    | [b1cba472dc](https://linux-hardware.org/?probe=b1cba472dc) | Aug 06, 2022 |
| HP            | 2215                        | Desktop     | [75304ada6c](https://linux-hardware.org/?probe=75304ada6c) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430s 2356LNG      | Notebook    | [255560d675](https://linux-hardware.org/?probe=255560d675) | Aug 06, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [77092711a0](https://linux-hardware.org/?probe=77092711a0) | Aug 06, 2022 |
| Toshiba       | STI 006998G                 | Desktop     | [3de3fa77fc](https://linux-hardware.org/?probe=3de3fa77fc) | Aug 06, 2022 |
| ASRock        | H110M-STX                   | Desktop     | [62b1924710](https://linux-hardware.org/?probe=62b1924710) | Aug 06, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4015089c1e](https://linux-hardware.org/?probe=4015089c1e) | Aug 06, 2022 |
| MSI           | 2A9C                        | Desktop     | [8913065613](https://linux-hardware.org/?probe=8913065613) | Aug 06, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [6b1d79046a](https://linux-hardware.org/?probe=6b1d79046a) | Aug 06, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [73145490fa](https://linux-hardware.org/?probe=73145490fa) | Aug 06, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [dbf000aacd](https://linux-hardware.org/?probe=dbf000aacd) | Aug 06, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [daa1f68f01](https://linux-hardware.org/?probe=daa1f68f01) | Aug 06, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | Desktop     | [a722bef081](https://linux-hardware.org/?probe=a722bef081) | Aug 06, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [b9a68ae76c](https://linux-hardware.org/?probe=b9a68ae76c) | Aug 06, 2022 |
| MSI           | Z87-G43 GAMING              | Desktop     | [490239de9e](https://linux-hardware.org/?probe=490239de9e) | Aug 05, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [1ad9e54625](https://linux-hardware.org/?probe=1ad9e54625) | Aug 05, 2022 |
| Supermicro    | X8DTL                       | Server      | [efb288164c](https://linux-hardware.org/?probe=efb288164c) | Aug 05, 2022 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [b68c110fde](https://linux-hardware.org/?probe=b68c110fde) | Aug 05, 2022 |
| Acer          | E1-510                      | Notebook    | [05ea3ff386](https://linux-hardware.org/?probe=05ea3ff386) | Aug 05, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [f6b820d15f](https://linux-hardware.org/?probe=f6b820d15f) | Aug 05, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [273c214064](https://linux-hardware.org/?probe=273c214064) | Aug 05, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [f52779262f](https://linux-hardware.org/?probe=f52779262f) | Aug 05, 2022 |
| Dell          | Latitude 3310               | Notebook    | [97ac18f196](https://linux-hardware.org/?probe=97ac18f196) | Aug 05, 2022 |
| Dell          | Latitude 3410               | Notebook    | [8181c3588f](https://linux-hardware.org/?probe=8181c3588f) | Aug 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [25efd53898](https://linux-hardware.org/?probe=25efd53898) | Aug 05, 2022 |
| HP            | ProBook 6450b               | Notebook    | [699b27e34f](https://linux-hardware.org/?probe=699b27e34f) | Aug 05, 2022 |
| Dell          | 0KG317                      | Desktop     | [65c105e2be](https://linux-hardware.org/?probe=65c105e2be) | Aug 04, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [d5d981cf7b](https://linux-hardware.org/?probe=d5d981cf7b) | Aug 04, 2022 |
| Lenovo        | ThinkPad X230 2325U9T       | Notebook    | [0f0e8ec24f](https://linux-hardware.org/?probe=0f0e8ec24f) | Aug 04, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [8c6442a868](https://linux-hardware.org/?probe=8c6442a868) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Dell          | Latitude 3490               | Notebook    | [fa1c5f753f](https://linux-hardware.org/?probe=fa1c5f753f) | Aug 04, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [1b51c25d37](https://linux-hardware.org/?probe=1b51c25d37) | Aug 04, 2022 |
| Dell          | Latitude 3310               | Notebook    | [9b9bed6ac6](https://linux-hardware.org/?probe=9b9bed6ac6) | Aug 04, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9a4f5806f8](https://linux-hardware.org/?probe=9a4f5806f8) | Aug 04, 2022 |
| Dell          | Latitude 3120               | Convertible | [d3e0c77946](https://linux-hardware.org/?probe=d3e0c77946) | Aug 04, 2022 |
| Intel         | NUC6i7KYB H90766-403        | Mini pc     | [fa04804b78](https://linux-hardware.org/?probe=fa04804b78) | Aug 04, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [dabb21caca](https://linux-hardware.org/?probe=dabb21caca) | Aug 04, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [7893ade7cb](https://linux-hardware.org/?probe=7893ade7cb) | Aug 04, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [f9e07e62c2](https://linux-hardware.org/?probe=f9e07e62c2) | Aug 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [0725792da0](https://linux-hardware.org/?probe=0725792da0) | Aug 04, 2022 |
| Dell          | System Inspiron N4110       | Notebook    | [22938e2e62](https://linux-hardware.org/?probe=22938e2e62) | Aug 03, 2022 |
| Gigabyte      | B360M GAMING HD             | Desktop     | [95e1eb0fcb](https://linux-hardware.org/?probe=95e1eb0fcb) | Aug 03, 2022 |
| Lenovo        | ThinkPad T530 2429W4Z       | Notebook    | [2d95f7cc7e](https://linux-hardware.org/?probe=2d95f7cc7e) | Aug 03, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [f1d5a6ab3f](https://linux-hardware.org/?probe=f1d5a6ab3f) | Aug 03, 2022 |
| Lenovo        | 3102                        | Desktop     | [73e0fee2bc](https://linux-hardware.org/?probe=73e0fee2bc) | Aug 03, 2022 |
| Lenovo        | ThinkPad SL510 28477NG      | Notebook    | [5ddf195177](https://linux-hardware.org/?probe=5ddf195177) | Aug 03, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [450fee0496](https://linux-hardware.org/?probe=450fee0496) | Aug 03, 2022 |
| HP            | 2B29                        | Desktop     | [5fcf3a8320](https://linux-hardware.org/?probe=5fcf3a8320) | Aug 02, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [97dba8f5e3](https://linux-hardware.org/?probe=97dba8f5e3) | Aug 02, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [f6f97a58c4](https://linux-hardware.org/?probe=f6f97a58c4) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [6b790e8a9b](https://linux-hardware.org/?probe=6b790e8a9b) | Aug 02, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [1a35a6d7dc](https://linux-hardware.org/?probe=1a35a6d7dc) | Aug 02, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [4f1fca6662](https://linux-hardware.org/?probe=4f1fca6662) | Aug 02, 2022 |
| Dell          | Latitude E6430              | Notebook    | [15e26c7cc5](https://linux-hardware.org/?probe=15e26c7cc5) | Aug 02, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [508b0275e3](https://linux-hardware.org/?probe=508b0275e3) | Aug 02, 2022 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [71c6ba6061](https://linux-hardware.org/?probe=71c6ba6061) | Aug 01, 2022 |
| Dell          | Latitude E7450              | Notebook    | [38051fe609](https://linux-hardware.org/?probe=38051fe609) | Aug 01, 2022 |
| Packard Be... | EasyNote TK13BZ             | Notebook    | [530d3ad8db](https://linux-hardware.org/?probe=530d3ad8db) | Aug 01, 2022 |
| TrekStor      | Primebook C13               | Convertible | [e45c26fec9](https://linux-hardware.org/?probe=e45c26fec9) | Aug 01, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [daaf600950](https://linux-hardware.org/?probe=daaf600950) | Aug 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [b5fded6824](https://linux-hardware.org/?probe=b5fded6824) | Aug 01, 2022 |
| HP            | ProBook 440 G2              | Notebook    | [00dd80ba31](https://linux-hardware.org/?probe=00dd80ba31) | Aug 01, 2022 |
| Acer          | Z476                        | Notebook    | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| HP            | 339A                        | Desktop     | [251a764917](https://linux-hardware.org/?probe=251a764917) | Aug 01, 2022 |
| Toshiba       | Satellite-C845              | Notebook    | [6ee9ea90a5](https://linux-hardware.org/?probe=6ee9ea90a5) | Aug 01, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [72278643e8](https://linux-hardware.org/?probe=72278643e8) | Aug 01, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [d58be7b6d1](https://linux-hardware.org/?probe=d58be7b6d1) | Aug 01, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [7051f56dda](https://linux-hardware.org/?probe=7051f56dda) | Aug 01, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [fcadad42a5](https://linux-hardware.org/?probe=fcadad42a5) | Aug 01, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| HP            | 843F                        | Desktop     | [eeba83fecb](https://linux-hardware.org/?probe=eeba83fecb) | Aug 01, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [7102c56d5b](https://linux-hardware.org/?probe=7102c56d5b) | Aug 01, 2022 |
| Packard Be... | EasyNote TM85               | Notebook    | [a6df06f9e5](https://linux-hardware.org/?probe=a6df06f9e5) | Jul 31, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [7e6cd7bcb3](https://linux-hardware.org/?probe=7e6cd7bcb3) | Jul 31, 2022 |
| Lenovo        | ThinkPad T460 20FMS02R0G    | Notebook    | [0aa31e3c39](https://linux-hardware.org/?probe=0aa31e3c39) | Jul 31, 2022 |
| Acer          | TravelMate B118-M           | Notebook    | [490edd75cf](https://linux-hardware.org/?probe=490edd75cf) | Jul 31, 2022 |
| HP            | ProBook 6570b               | Notebook    | [333a24bdee](https://linux-hardware.org/?probe=333a24bdee) | Jul 31, 2022 |
| Acer          | Aspire VN7-791G             | Notebook    | [3e72040097](https://linux-hardware.org/?probe=3e72040097) | Jul 31, 2022 |
| Toshiba       | All In One PC MP            | All in one  | [4d493ab3df](https://linux-hardware.org/?probe=4d493ab3df) | Jul 31, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [653f46c8e3](https://linux-hardware.org/?probe=653f46c8e3) | Jul 31, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6204ce9d95](https://linux-hardware.org/?probe=6204ce9d95) | Jul 31, 2022 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [4e30dc6361](https://linux-hardware.org/?probe=4e30dc6361) | Jul 31, 2022 |
| MSI           | B85M-P33                    | Desktop     | [6e9af1d1e4](https://linux-hardware.org/?probe=6e9af1d1e4) | Jul 31, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [cb7c9442d6](https://linux-hardware.org/?probe=cb7c9442d6) | Jul 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| eMachines     | Unknown                     | Notebook    | [8c6dcb08a7](https://linux-hardware.org/?probe=8c6dcb08a7) | Jul 31, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [7b0b52e138](https://linux-hardware.org/?probe=7b0b52e138) | Jul 31, 2022 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [25db3983fe](https://linux-hardware.org/?probe=25db3983fe) | Jul 30, 2022 |
| Compaq        | Presario CQ-23              | Notebook    | [76ea82c314](https://linux-hardware.org/?probe=76ea82c314) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [10ece2cb6c](https://linux-hardware.org/?probe=10ece2cb6c) | Jul 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2171abfd3d](https://linux-hardware.org/?probe=2171abfd3d) | Jul 30, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [b846739765](https://linux-hardware.org/?probe=b846739765) | Jul 30, 2022 |
| ASUSTek       | K501LX                      | Notebook    | [8ea0c7daa9](https://linux-hardware.org/?probe=8ea0c7daa9) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [edd98c5418](https://linux-hardware.org/?probe=edd98c5418) | Jul 30, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ee5c151c3a](https://linux-hardware.org/?probe=ee5c151c3a) | Jul 30, 2022 |
| ASUSTek       | K53E                        | Notebook    | [3ca340212e](https://linux-hardware.org/?probe=3ca340212e) | Jul 30, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [a29c1c816a](https://linux-hardware.org/?probe=a29c1c816a) | Jul 30, 2022 |
| Fujitsu       | LIFEBOOK V1020              | Notebook    | [e33ac2916d](https://linux-hardware.org/?probe=e33ac2916d) | Jul 30, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [2cc4fd5d75](https://linux-hardware.org/?probe=2cc4fd5d75) | Jul 30, 2022 |
| ASUSTek       | M3A78 PRO                   | Desktop     | [c30fca013c](https://linux-hardware.org/?probe=c30fca013c) | Jul 30, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [fdb72c3ec3](https://linux-hardware.org/?probe=fdb72c3ec3) | Jul 29, 2022 |
| HP            | 2ADC                        | Desktop     | [86608333bc](https://linux-hardware.org/?probe=86608333bc) | Jul 29, 2022 |
| Acer          | Aspire A317-33              | Notebook    | [ab07e43574](https://linux-hardware.org/?probe=ab07e43574) | Jul 29, 2022 |
| Sony          | VPCEA45FL                   | Notebook    | [8079ec1351](https://linux-hardware.org/?probe=8079ec1351) | Jul 29, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | Notebook    | [5b91ff037d](https://linux-hardware.org/?probe=5b91ff037d) | Jul 29, 2022 |
| HP            | ProBook 6570b               | Notebook    | [231ebd2edc](https://linux-hardware.org/?probe=231ebd2edc) | Jul 29, 2022 |
| PCWare        | IPMH61R2                    | Desktop     | [b3245af28d](https://linux-hardware.org/?probe=b3245af28d) | Jul 29, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [02e9f6a808](https://linux-hardware.org/?probe=02e9f6a808) | Jul 29, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [a42627d17e](https://linux-hardware.org/?probe=a42627d17e) | Jul 29, 2022 |
| HP            | 0AA0h                       | Desktop     | [5d21c69a99](https://linux-hardware.org/?probe=5d21c69a99) | Jul 29, 2022 |
| HP            | 18E4                        | Desktop     | [d13265fa57](https://linux-hardware.org/?probe=d13265fa57) | Jul 29, 2022 |
| Lenovo        | ThinkPad S5 Yoga 15 20DR... | Notebook    | [147d305ac1](https://linux-hardware.org/?probe=147d305ac1) | Jul 29, 2022 |
| Lenovo        | ThinkPad X230 23253B3       | Notebook    | [fa19ec3adf](https://linux-hardware.org/?probe=fa19ec3adf) | Jul 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [e1d666e84a](https://linux-hardware.org/?probe=e1d666e84a) | Jul 29, 2022 |
| Google        | Candy                       | Notebook    | [cba2906cfd](https://linux-hardware.org/?probe=cba2906cfd) | Jul 29, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [f424705bd7](https://linux-hardware.org/?probe=f424705bd7) | Jul 29, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [e3f2dd0271](https://linux-hardware.org/?probe=e3f2dd0271) | Jul 29, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [03b39a36f1](https://linux-hardware.org/?probe=03b39a36f1) | Jul 29, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [61a6277614](https://linux-hardware.org/?probe=61a6277614) | Jul 28, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [668a02296d](https://linux-hardware.org/?probe=668a02296d) | Jul 28, 2022 |
| HP            | ProBook 4515s               | Notebook    | [b9759d3b5d](https://linux-hardware.org/?probe=b9759d3b5d) | Jul 28, 2022 |
| Dell          | OptiPlex 780                | Desktop     | [7a029315b9](https://linux-hardware.org/?probe=7a029315b9) | Jul 28, 2022 |
| ASRock        | Z97 Anniversary             | Desktop     | [768b11cbe4](https://linux-hardware.org/?probe=768b11cbe4) | Jul 28, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [1bc8def241](https://linux-hardware.org/?probe=1bc8def241) | Jul 28, 2022 |
| MSI           | AM1I                        | Desktop     | [63e6d4040e](https://linux-hardware.org/?probe=63e6d4040e) | Jul 28, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| ASUSTek       | K53U                        | Notebook    | [7db28a1538](https://linux-hardware.org/?probe=7db28a1538) | Jul 28, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [26c6af2a55](https://linux-hardware.org/?probe=26c6af2a55) | Jul 28, 2022 |
| Toshiba       | Satellite P50-B-118         | Notebook    | [b46f72c280](https://linux-hardware.org/?probe=b46f72c280) | Jul 28, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [a555c41bb7](https://linux-hardware.org/?probe=a555c41bb7) | Jul 28, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [1357e3b3d3](https://linux-hardware.org/?probe=1357e3b3d3) | Jul 28, 2022 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [93ad7b0efb](https://linux-hardware.org/?probe=93ad7b0efb) | Jul 28, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [db492973ec](https://linux-hardware.org/?probe=db492973ec) | Jul 28, 2022 |
| HP            | 2000                        | Notebook    | [531b786836](https://linux-hardware.org/?probe=531b786836) | Jul 28, 2022 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [afaf75a141](https://linux-hardware.org/?probe=afaf75a141) | Jul 28, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [cc72c3c914](https://linux-hardware.org/?probe=cc72c3c914) | Jul 28, 2022 |
| Wortmann      | TERRA_MOBILE_1528P/1748P    | Notebook    | [7bcdc30be3](https://linux-hardware.org/?probe=7bcdc30be3) | Jul 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [24e94dd87e](https://linux-hardware.org/?probe=24e94dd87e) | Jul 28, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [bf8a8c589a](https://linux-hardware.org/?probe=bf8a8c589a) | Jul 28, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [0068653ca3](https://linux-hardware.org/?probe=0068653ca3) | Jul 28, 2022 |
| Positivo      | H14BT58                     | Notebook    | [7f271e5d68](https://linux-hardware.org/?probe=7f271e5d68) | Jul 28, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [d64175b64b](https://linux-hardware.org/?probe=d64175b64b) | Jul 28, 2022 |
| Toshiba       | Satellite C850D-11K         | Notebook    | [544f2db462](https://linux-hardware.org/?probe=544f2db462) | Jul 28, 2022 |
| Sony          | VPCS110FL                   | Notebook    | [8576955f3c](https://linux-hardware.org/?probe=8576955f3c) | Jul 28, 2022 |
| ASRock        | A88M-ITX/ac                 | Desktop     | [e339941033](https://linux-hardware.org/?probe=e339941033) | Jul 27, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [71b03b93a2](https://linux-hardware.org/?probe=71b03b93a2) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [94a6b79798](https://linux-hardware.org/?probe=94a6b79798) | Jul 27, 2022 |
| Acer          | Aspire X1930                | Desktop     | [6a650f512e](https://linux-hardware.org/?probe=6a650f512e) | Jul 27, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [b7fabad758](https://linux-hardware.org/?probe=b7fabad758) | Jul 27, 2022 |
| HP            | Pavilion g7                 | Notebook    | [75fa7f0ce4](https://linux-hardware.org/?probe=75fa7f0ce4) | Jul 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [d0ef6d20cf](https://linux-hardware.org/?probe=d0ef6d20cf) | Jul 27, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [d8cbb25698](https://linux-hardware.org/?probe=d8cbb25698) | Jul 27, 2022 |
| Foxconn       | A76ML-K 30                  | Desktop     | [7b118c6a6b](https://linux-hardware.org/?probe=7b118c6a6b) | Jul 27, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [8f0daaf341](https://linux-hardware.org/?probe=8f0daaf341) | Jul 27, 2022 |
| ASUSTek       | S551LB                      | Notebook    | [8660a06086](https://linux-hardware.org/?probe=8660a06086) | Jul 27, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [610282a0e6](https://linux-hardware.org/?probe=610282a0e6) | Jul 27, 2022 |
| Dell          | Latitude E6330              | Notebook    | [5ee8d985ed](https://linux-hardware.org/?probe=5ee8d985ed) | Jul 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [17f64584bb](https://linux-hardware.org/?probe=17f64584bb) | Jul 27, 2022 |
| Dell          | 0YF8P5 A00                  | Desktop     | [04ebe8cd88](https://linux-hardware.org/?probe=04ebe8cd88) | Jul 27, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5b4bccdf27](https://linux-hardware.org/?probe=5b4bccdf27) | Jul 27, 2022 |
| HP            | Compaq 6720s                | Notebook    | [d8546f791c](https://linux-hardware.org/?probe=d8546f791c) | Jul 27, 2022 |
| HP            | 1495                        | Desktop     | [61a8f473e2](https://linux-hardware.org/?probe=61a8f473e2) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| Acer          | TravelMate P633-M           | Notebook    | [7d346db799](https://linux-hardware.org/?probe=7d346db799) | Jul 27, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [6362df4235](https://linux-hardware.org/?probe=6362df4235) | Jul 27, 2022 |
| Lenovo        | ThinkPad T420 4236CTO       | Notebook    | [6797b09b3b](https://linux-hardware.org/?probe=6797b09b3b) | Jul 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [cf1f919243](https://linux-hardware.org/?probe=cf1f919243) | Jul 27, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [44954e91a2](https://linux-hardware.org/?probe=44954e91a2) | Jul 27, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [eb1ff40d2d](https://linux-hardware.org/?probe=eb1ff40d2d) | Jul 27, 2022 |
| Sony          | VPCEB26FG                   | Notebook    | [49c139799c](https://linux-hardware.org/?probe=49c139799c) | Jul 27, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [eeb9068dca](https://linux-hardware.org/?probe=eeb9068dca) | Jul 27, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [06fe56588b](https://linux-hardware.org/?probe=06fe56588b) | Jul 27, 2022 |
| Gigabyte      | H55M-S2H                    | Desktop     | [a9a6ab85ac](https://linux-hardware.org/?probe=a9a6ab85ac) | Jul 27, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b76e9e02fa](https://linux-hardware.org/?probe=b76e9e02fa) | Jul 27, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [0cfb15d654](https://linux-hardware.org/?probe=0cfb15d654) | Jul 27, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [24e0844619](https://linux-hardware.org/?probe=24e0844619) | Jul 27, 2022 |
| Acer          | IPXHW-RL                    | Desktop     | [d99b7cb71e](https://linux-hardware.org/?probe=d99b7cb71e) | Jul 27, 2022 |
| Dell          | Latitude E7240              | Notebook    | [6af993caf7](https://linux-hardware.org/?probe=6af993caf7) | Jul 27, 2022 |
| Intel         | DH67VR AAG27177-201         | Desktop     | [3aeca135cd](https://linux-hardware.org/?probe=3aeca135cd) | Jul 26, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [faf9360275](https://linux-hardware.org/?probe=faf9360275) | Jul 26, 2022 |
| Toshiba       | Satellite C870D-116         | Notebook    | [d92af8246c](https://linux-hardware.org/?probe=d92af8246c) | Jul 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [05947b595a](https://linux-hardware.org/?probe=05947b595a) | Jul 26, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [e487b063ea](https://linux-hardware.org/?probe=e487b063ea) | Jul 26, 2022 |
| HP            | ProBook 645 G1              | Notebook    | [457c35707a](https://linux-hardware.org/?probe=457c35707a) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [17954b8ac5](https://linux-hardware.org/?probe=17954b8ac5) | Jul 26, 2022 |
| Dell          | 0C27VV A03                  | Desktop     | [c1c4edd1e5](https://linux-hardware.org/?probe=c1c4edd1e5) | Jul 26, 2022 |
| Acer          | Aspire 3810T                | Notebook    | [92f9c99b5e](https://linux-hardware.org/?probe=92f9c99b5e) | Jul 26, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [f9003ad850](https://linux-hardware.org/?probe=f9003ad850) | Jul 26, 2022 |
| Dell          | Latitude 131L               | Notebook    | [ec8717bc3f](https://linux-hardware.org/?probe=ec8717bc3f) | Jul 26, 2022 |
| HP            | 8446                        | All in one  | [ad79d02ff6](https://linux-hardware.org/?probe=ad79d02ff6) | Jul 26, 2022 |
| Dell          | Latitude 3300               | Notebook    | [64cf4b87d9](https://linux-hardware.org/?probe=64cf4b87d9) | Jul 26, 2022 |
| Toshiba       | dynabook R734/K             | Notebook    | [a5e7d4c919](https://linux-hardware.org/?probe=a5e7d4c919) | Jul 26, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [5eb6c551b0](https://linux-hardware.org/?probe=5eb6c551b0) | Jul 26, 2022 |
| Login Info... | LOG-H310M-G                 | Desktop     | [f02a0ed6dd](https://linux-hardware.org/?probe=f02a0ed6dd) | Jul 26, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [02572035c8](https://linux-hardware.org/?probe=02572035c8) | Jul 26, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [8161693c82](https://linux-hardware.org/?probe=8161693c82) | Jul 26, 2022 |
| Pegatron      | 2AE2                        | Desktop     | [772ded1d83](https://linux-hardware.org/?probe=772ded1d83) | Jul 25, 2022 |
| Dell          | 0V8WGR A01                  | Desktop     | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [da71f235a2](https://linux-hardware.org/?probe=da71f235a2) | Jul 25, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [e470dff38f](https://linux-hardware.org/?probe=e470dff38f) | Jul 25, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [660665c762](https://linux-hardware.org/?probe=660665c762) | Jul 25, 2022 |
| Lenovo        | ThinkCentre M58p 6137B28    | Desktop     | [5473e97fa6](https://linux-hardware.org/?probe=5473e97fa6) | Jul 25, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0fe12d0d48](https://linux-hardware.org/?probe=0fe12d0d48) | Jul 25, 2022 |
| Acer          | Aspire 5741G                | Notebook    | [a4f8482423](https://linux-hardware.org/?probe=a4f8482423) | Jul 25, 2022 |
| Gigabyte      | H170M-D3H-GSM-CF            | Desktop     | [ace82a6273](https://linux-hardware.org/?probe=ace82a6273) | Jul 25, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [2e1715f154](https://linux-hardware.org/?probe=2e1715f154) | Jul 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [375ba933ba](https://linux-hardware.org/?probe=375ba933ba) | Jul 25, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e6b9106560](https://linux-hardware.org/?probe=e6b9106560) | Jul 24, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [fdb0300292](https://linux-hardware.org/?probe=fdb0300292) | Jul 24, 2022 |
| Dell          | 0VHWTR A01                  | Desktop     | [9796d6eca3](https://linux-hardware.org/?probe=9796d6eca3) | Jul 24, 2022 |
| Lenovo        | ThinkPad P50 20EN0008GE     | Notebook    | [93ec0d85ab](https://linux-hardware.org/?probe=93ec0d85ab) | Jul 24, 2022 |
| Toshiba       | Portable PC                 | Notebook    | [00cd85e866](https://linux-hardware.org/?probe=00cd85e866) | Jul 24, 2022 |
| Apple         | MacBookAir9,1               | Notebook    | [cf4d815653](https://linux-hardware.org/?probe=cf4d815653) | Jul 24, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [7923ed68b5](https://linux-hardware.org/?probe=7923ed68b5) | Jul 24, 2022 |
| HP            | Notebook                    | Notebook    | [17893fb905](https://linux-hardware.org/?probe=17893fb905) | Jul 24, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7af6c5cebe](https://linux-hardware.org/?probe=7af6c5cebe) | Jul 24, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [49af56cbe0](https://linux-hardware.org/?probe=49af56cbe0) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [7bb0cce634](https://linux-hardware.org/?probe=7bb0cce634) | Jul 24, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [ea3f7e3b48](https://linux-hardware.org/?probe=ea3f7e3b48) | Jul 23, 2022 |
| Dell          | Latitude E6430              | Notebook    | [8bc3b0f962](https://linux-hardware.org/?probe=8bc3b0f962) | Jul 23, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c4c41ad0b5](https://linux-hardware.org/?probe=c4c41ad0b5) | Jul 23, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [dc8bafd932](https://linux-hardware.org/?probe=dc8bafd932) | Jul 23, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [acdc35979c](https://linux-hardware.org/?probe=acdc35979c) | Jul 23, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [bad4adf823](https://linux-hardware.org/?probe=bad4adf823) | Jul 23, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [72a44c6eea](https://linux-hardware.org/?probe=72a44c6eea) | Jul 23, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [368503425d](https://linux-hardware.org/?probe=368503425d) | Jul 23, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [7e7606e64d](https://linux-hardware.org/?probe=7e7606e64d) | Jul 23, 2022 |
| AZW           | GT-R                        | Notebook    | [eb7604ea1c](https://linux-hardware.org/?probe=eb7604ea1c) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | Notebook    | [fe5dae3d4a](https://linux-hardware.org/?probe=fe5dae3d4a) | Jul 22, 2022 |
| HP            | 0A68h                       | Desktop     | [cc4b39e6d0](https://linux-hardware.org/?probe=cc4b39e6d0) | Jul 22, 2022 |
| Lenovo        | ThinkPad T61 6458W4B        | Notebook    | [3d51bdb900](https://linux-hardware.org/?probe=3d51bdb900) | Jul 22, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [8b9c2d3dc0](https://linux-hardware.org/?probe=8b9c2d3dc0) | Jul 22, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [8fc99169c3](https://linux-hardware.org/?probe=8fc99169c3) | Jul 22, 2022 |
| Lenovo        | ThinkPad Helix 36986EU      | Notebook    | [294d96aff6](https://linux-hardware.org/?probe=294d96aff6) | Jul 22, 2022 |
| Positivo      | J14AL11                     | Notebook    | [7510e905d8](https://linux-hardware.org/?probe=7510e905d8) | Jul 22, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [80dcd8a0f7](https://linux-hardware.org/?probe=80dcd8a0f7) | Jul 22, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [e6bf6ea62f](https://linux-hardware.org/?probe=e6bf6ea62f) | Jul 21, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [321d2817a3](https://linux-hardware.org/?probe=321d2817a3) | Jul 21, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [56ce195301](https://linux-hardware.org/?probe=56ce195301) | Jul 21, 2022 |
| HP            | Notebook                    | Notebook    | [e859de5718](https://linux-hardware.org/?probe=e859de5718) | Jul 21, 2022 |
| Dell          | Latitude 3310               | Notebook    | [bc6103f96b](https://linux-hardware.org/?probe=bc6103f96b) | Jul 21, 2022 |
| HP            | 1998                        | Desktop     | [82c8302941](https://linux-hardware.org/?probe=82c8302941) | Jul 21, 2022 |
| Dell          | Latitude 3310               | Notebook    | [abe159e82a](https://linux-hardware.org/?probe=abe159e82a) | Jul 21, 2022 |
| Dell          | Latitude 3310               | Notebook    | [d90f147df3](https://linux-hardware.org/?probe=d90f147df3) | Jul 21, 2022 |
| Dell          | Latitude 3310               | Notebook    | [324b95a49a](https://linux-hardware.org/?probe=324b95a49a) | Jul 21, 2022 |
| METAPHYUNI    | MetamechBook                | Notebook    | [169a9a0636](https://linux-hardware.org/?probe=169a9a0636) | Jul 21, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [61c51541dd](https://linux-hardware.org/?probe=61c51541dd) | Jul 21, 2022 |
| Lenovo        | 1.0                         | Desktop     | [e520e716cf](https://linux-hardware.org/?probe=e520e716cf) | Jul 21, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c8243bf1a8](https://linux-hardware.org/?probe=c8243bf1a8) | Jul 20, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [34942a8abc](https://linux-hardware.org/?probe=34942a8abc) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9863a7ed67](https://linux-hardware.org/?probe=9863a7ed67) | Jul 20, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [c1d1e739cf](https://linux-hardware.org/?probe=c1d1e739cf) | Jul 20, 2022 |
| Acer          | Veriton M290                | Desktop     | [647393aa0c](https://linux-hardware.org/?probe=647393aa0c) | Jul 20, 2022 |
| PCChips       | A15G                        | Desktop     | [4cdd689308](https://linux-hardware.org/?probe=4cdd689308) | Jul 20, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [762e21d62f](https://linux-hardware.org/?probe=762e21d62f) | Jul 20, 2022 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [fe2f5a993c](https://linux-hardware.org/?probe=fe2f5a993c) | Jul 20, 2022 |
| Dell          | Latitude 3310               | Notebook    | [086f88be40](https://linux-hardware.org/?probe=086f88be40) | Jul 20, 2022 |
| Dell          | Inspiron 5579               | Notebook    | [52e88ad171](https://linux-hardware.org/?probe=52e88ad171) | Jul 20, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0cb2abc6bc](https://linux-hardware.org/?probe=0cb2abc6bc) | Jul 20, 2022 |
| Dell          | Latitude 3310               | Notebook    | [dbd9b101c2](https://linux-hardware.org/?probe=dbd9b101c2) | Jul 20, 2022 |
| Dell          | Latitude 5285               | Notebook    | [2b46125d79](https://linux-hardware.org/?probe=2b46125d79) | Jul 20, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [e45f2cd5d8](https://linux-hardware.org/?probe=e45f2cd5d8) | Jul 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [bece300d92](https://linux-hardware.org/?probe=bece300d92) | Jul 20, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [e386bc211b](https://linux-hardware.org/?probe=e386bc211b) | Jul 20, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [55fdb6713c](https://linux-hardware.org/?probe=55fdb6713c) | Jul 19, 2022 |
| Acer          | Veriton M2110G              | Desktop     | [060e101a26](https://linux-hardware.org/?probe=060e101a26) | Jul 19, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [78c2b82b87](https://linux-hardware.org/?probe=78c2b82b87) | Jul 19, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [83d1355e61](https://linux-hardware.org/?probe=83d1355e61) | Jul 19, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [8d52662820](https://linux-hardware.org/?probe=8d52662820) | Jul 19, 2022 |
| Gigabyte      | P31-DS3L                    | Desktop     | [3b8118fb89](https://linux-hardware.org/?probe=3b8118fb89) | Jul 19, 2022 |
| Gateway       | NV53A                       | Notebook    | [2674f3160f](https://linux-hardware.org/?probe=2674f3160f) | Jul 19, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [4414dd4c1b](https://linux-hardware.org/?probe=4414dd4c1b) | Jul 19, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [879d413452](https://linux-hardware.org/?probe=879d413452) | Jul 19, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [c26ed846e9](https://linux-hardware.org/?probe=c26ed846e9) | Jul 19, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [475d626fd5](https://linux-hardware.org/?probe=475d626fd5) | Jul 19, 2022 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [4a97996102](https://linux-hardware.org/?probe=4a97996102) | Jul 18, 2022 |
| HUAWEI        | MateBook D                  | Notebook    | [5d7a616dd1](https://linux-hardware.org/?probe=5d7a616dd1) | Jul 18, 2022 |
| Acer          | Aspire ES1-411              | Notebook    | [5d551a94bd](https://linux-hardware.org/?probe=5d551a94bd) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [68a78a8ed1](https://linux-hardware.org/?probe=68a78a8ed1) | Jul 18, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [d04747e05b](https://linux-hardware.org/?probe=d04747e05b) | Jul 17, 2022 |
| Teclast       | F15 Plus                    | Notebook    | [6201934176](https://linux-hardware.org/?probe=6201934176) | Jul 17, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [3b89e3e952](https://linux-hardware.org/?probe=3b89e3e952) | Jul 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [14d23344e2](https://linux-hardware.org/?probe=14d23344e2) | Jul 17, 2022 |
| HP            | ProBook 4441s               | Notebook    | [b108eaada9](https://linux-hardware.org/?probe=b108eaada9) | Jul 17, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [3e2c54f9f1](https://linux-hardware.org/?probe=3e2c54f9f1) | Jul 17, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [ec3010a13f](https://linux-hardware.org/?probe=ec3010a13f) | Jul 17, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [2349372af2](https://linux-hardware.org/?probe=2349372af2) | Jul 16, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [803b7d3211](https://linux-hardware.org/?probe=803b7d3211) | Jul 16, 2022 |
| Sony          | VPCEA3M1R                   | Notebook    | [0bdfc50874](https://linux-hardware.org/?probe=0bdfc50874) | Jul 16, 2022 |
| Digibras      | NH4CU53                     | Notebook    | [f6b402afe8](https://linux-hardware.org/?probe=f6b402afe8) | Jul 16, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [478e424482](https://linux-hardware.org/?probe=478e424482) | Jul 16, 2022 |
| MSI           | GP62 6QE                    | Notebook    | [7e7c05c6b6](https://linux-hardware.org/?probe=7e7c05c6b6) | Jul 16, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [68f6109054](https://linux-hardware.org/?probe=68f6109054) | Jul 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b511d2883b](https://linux-hardware.org/?probe=b511d2883b) | Jul 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [e6b47dedd7](https://linux-hardware.org/?probe=e6b47dedd7) | Jul 15, 2022 |
| Sony          | SVE1513H1EW                 | Notebook    | [6e4d66c2ee](https://linux-hardware.org/?probe=6e4d66c2ee) | Jul 15, 2022 |
| HP            | ProBook 4545s               | Notebook    | [12575a32d1](https://linux-hardware.org/?probe=12575a32d1) | Jul 15, 2022 |
| MSI           | GE72 6QL                    | Notebook    | [7c22c38989](https://linux-hardware.org/?probe=7c22c38989) | Jul 15, 2022 |
| ASUSTek       | P5QLD PRO                   | Desktop     | [fbf3a31304](https://linux-hardware.org/?probe=fbf3a31304) | Jul 15, 2022 |
| Dell          | Latitude E6530              | Notebook    | [67eec0ba19](https://linux-hardware.org/?probe=67eec0ba19) | Jul 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e5638d3552](https://linux-hardware.org/?probe=e5638d3552) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [4d653cf4e6](https://linux-hardware.org/?probe=4d653cf4e6) | Jul 15, 2022 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [7b6a43a9f1](https://linux-hardware.org/?probe=7b6a43a9f1) | Jul 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [775050f5d9](https://linux-hardware.org/?probe=775050f5d9) | Jul 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [7e9ba006f3](https://linux-hardware.org/?probe=7e9ba006f3) | Jul 15, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4065c23b56](https://linux-hardware.org/?probe=4065c23b56) | Jul 15, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [03eaa344c6](https://linux-hardware.org/?probe=03eaa344c6) | Jul 15, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [52a3abee65](https://linux-hardware.org/?probe=52a3abee65) | Jul 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [7a661a1449](https://linux-hardware.org/?probe=7a661a1449) | Jul 15, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | Notebook    | [b85cc7c80c](https://linux-hardware.org/?probe=b85cc7c80c) | Jul 14, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [c8bf7e091c](https://linux-hardware.org/?probe=c8bf7e091c) | Jul 14, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [c3f5c82808](https://linux-hardware.org/?probe=c3f5c82808) | Jul 14, 2022 |
| MSI           | G41M-P28                    | Desktop     | [8bd39aa164](https://linux-hardware.org/?probe=8bd39aa164) | Jul 14, 2022 |
| ASUSTek       | UX301LA                     | Notebook    | [3d4655e7cf](https://linux-hardware.org/?probe=3d4655e7cf) | Jul 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [20ea8fab3f](https://linux-hardware.org/?probe=20ea8fab3f) | Jul 14, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [eebcfac8a3](https://linux-hardware.org/?probe=eebcfac8a3) | Jul 14, 2022 |
| Purism        | Librem 14                   | Notebook    | [5a0337506b](https://linux-hardware.org/?probe=5a0337506b) | Jul 14, 2022 |
| MSI           | B250M PRO-VH                | Desktop     | [d0a4b76e78](https://linux-hardware.org/?probe=d0a4b76e78) | Jul 13, 2022 |
| HP            | 83E8                        | Desktop     | [a2dc0fc924](https://linux-hardware.org/?probe=a2dc0fc924) | Jul 13, 2022 |
| Notebook      | NL40_50GU                   | Notebook    | [d4e652dc65](https://linux-hardware.org/?probe=d4e652dc65) | Jul 13, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [25d6e4de23](https://linux-hardware.org/?probe=25d6e4de23) | Jul 13, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [24c64c6221](https://linux-hardware.org/?probe=24c64c6221) | Jul 13, 2022 |
| Foxconn       | 945 7MD Series              | Desktop     | [30585b93f0](https://linux-hardware.org/?probe=30585b93f0) | Jul 13, 2022 |
| Dell          | 048DY8 A01                  | Desktop     | [aad36ba2cd](https://linux-hardware.org/?probe=aad36ba2cd) | Jul 13, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [0005417882](https://linux-hardware.org/?probe=0005417882) | Jul 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [1c3c80b88e](https://linux-hardware.org/?probe=1c3c80b88e) | Jul 13, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [37b04a8093](https://linux-hardware.org/?probe=37b04a8093) | Jul 12, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [b0b89af62e](https://linux-hardware.org/?probe=b0b89af62e) | Jul 12, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [bbb311969a](https://linux-hardware.org/?probe=bbb311969a) | Jul 12, 2022 |
| Lenovo        | G575 4383                   | Notebook    | [8bd6296a3e](https://linux-hardware.org/?probe=8bd6296a3e) | Jul 12, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [9b24417251](https://linux-hardware.org/?probe=9b24417251) | Jul 12, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [8dbe4d55a5](https://linux-hardware.org/?probe=8dbe4d55a5) | Jul 11, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [d2b0adf1ae](https://linux-hardware.org/?probe=d2b0adf1ae) | Jul 11, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9f8f272886](https://linux-hardware.org/?probe=9f8f272886) | Jul 11, 2022 |
| Dell          | Latitude 3120               | Convertible | [948677f521](https://linux-hardware.org/?probe=948677f521) | Jul 11, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [1599e9e013](https://linux-hardware.org/?probe=1599e9e013) | Jul 11, 2022 |
| Colorful T... | H310M-T PRO V21             | Desktop     | [b922e2142b](https://linux-hardware.org/?probe=b922e2142b) | Jul 11, 2022 |
| HP            | Pavilion g4                 | Notebook    | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [d088d6021c](https://linux-hardware.org/?probe=d088d6021c) | Jul 11, 2022 |
| HP            | 339A                        | Desktop     | [a4606d9234](https://linux-hardware.org/?probe=a4606d9234) | Jul 10, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [8c5338cc67](https://linux-hardware.org/?probe=8c5338cc67) | Jul 10, 2022 |
| Apple         | MacBookAir3,2               | Notebook    | [e3f89d4d16](https://linux-hardware.org/?probe=e3f89d4d16) | Jul 10, 2022 |
| ASRock        | AMCP7A-ION                  | Desktop     | [339f0e7944](https://linux-hardware.org/?probe=339f0e7944) | Jul 10, 2022 |
| Acer          | FMCP7AM                     | Desktop     | [f2fc2e98c3](https://linux-hardware.org/?probe=f2fc2e98c3) | Jul 10, 2022 |
| ASUSTek       | A8N-VM CSM                  | Desktop     | [3cf6a895cd](https://linux-hardware.org/?probe=3cf6a895cd) | Jul 10, 2022 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [eba82e4b87](https://linux-hardware.org/?probe=eba82e4b87) | Jul 10, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [36b1a0480d](https://linux-hardware.org/?probe=36b1a0480d) | Jul 10, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [67182580cc](https://linux-hardware.org/?probe=67182580cc) | Jul 10, 2022 |
| Acer          | Aspire C22-865              | All in one  | [2e0a195007](https://linux-hardware.org/?probe=2e0a195007) | Jul 09, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [c0d1086ae8](https://linux-hardware.org/?probe=c0d1086ae8) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [ee629832da](https://linux-hardware.org/?probe=ee629832da) | Jul 09, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [cf0d8e217c](https://linux-hardware.org/?probe=cf0d8e217c) | Jul 09, 2022 |
| Gigabyte      | 945PL-S3                    | Desktop     | [72ffb35881](https://linux-hardware.org/?probe=72ffb35881) | Jul 09, 2022 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [3324f369f7](https://linux-hardware.org/?probe=3324f369f7) | Jul 09, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [03f898f89a](https://linux-hardware.org/?probe=03f898f89a) | Jul 09, 2022 |
| Acer          | Aspire Z3-710               | All in one  | [5f7d41a8ae](https://linux-hardware.org/?probe=5f7d41a8ae) | Jul 09, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [35d55776f6](https://linux-hardware.org/?probe=35d55776f6) | Jul 09, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [a39b9bab73](https://linux-hardware.org/?probe=a39b9bab73) | Jul 09, 2022 |
| Framework     | Laptop                      | Notebook    | [09fa73cc57](https://linux-hardware.org/?probe=09fa73cc57) | Jul 09, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [96de3e0656](https://linux-hardware.org/?probe=96de3e0656) | Jul 08, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [c6e9a42a66](https://linux-hardware.org/?probe=c6e9a42a66) | Jul 08, 2022 |
| Dell          | 0R849J A01                  | Desktop     | [3ea68d63c3](https://linux-hardware.org/?probe=3ea68d63c3) | Jul 08, 2022 |
| HP            | ProBook 4510s               | Notebook    | [ae51b4e466](https://linux-hardware.org/?probe=ae51b4e466) | Jul 08, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [1e64e5d64e](https://linux-hardware.org/?probe=1e64e5d64e) | Jul 08, 2022 |
| Gigabyte      | EP45-UD3                    | Desktop     | [195c60abeb](https://linux-hardware.org/?probe=195c60abeb) | Jul 08, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [9c7f4deae5](https://linux-hardware.org/?probe=9c7f4deae5) | Jul 08, 2022 |
| HP            | Notebook                    | Notebook    | [0dc44e8da9](https://linux-hardware.org/?probe=0dc44e8da9) | Jul 08, 2022 |
| ASUSTek       | P5K                         | Desktop     | [31df9a51bc](https://linux-hardware.org/?probe=31df9a51bc) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [4f02f261b3](https://linux-hardware.org/?probe=4f02f261b3) | Jul 08, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [3624ac1024](https://linux-hardware.org/?probe=3624ac1024) | Jul 08, 2022 |
| Gigabyte      | MBHM87P-00                  | Desktop     | [c02df16b43](https://linux-hardware.org/?probe=c02df16b43) | Jul 08, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [aa2ad87835](https://linux-hardware.org/?probe=aa2ad87835) | Jul 08, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [4f0cf74fe4](https://linux-hardware.org/?probe=4f0cf74fe4) | Jul 07, 2022 |
| HP            | 8432                        | All in one  | [c260601e89](https://linux-hardware.org/?probe=c260601e89) | Jul 07, 2022 |
| HP            | EliteBook x360 830 G6       | Convertible | [88e04cc797](https://linux-hardware.org/?probe=88e04cc797) | Jul 07, 2022 |
| HP            | 84EE 1100                   | All in one  | [668e6b5fdb](https://linux-hardware.org/?probe=668e6b5fdb) | Jul 07, 2022 |
| HP            | EliteBook x360 830 G6       | Convertible | [5f64d31ef3](https://linux-hardware.org/?probe=5f64d31ef3) | Jul 07, 2022 |
| ASUSTek       | P5B                         | Desktop     | [0c722e5ec0](https://linux-hardware.org/?probe=0c722e5ec0) | Jul 07, 2022 |
| HP            | ProBook 4310s               | Notebook    | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [6b5e1735a7](https://linux-hardware.org/?probe=6b5e1735a7) | Jul 07, 2022 |
| HP            | G56                         | Notebook    | [5c38722298](https://linux-hardware.org/?probe=5c38722298) | Jul 07, 2022 |
| Acer          | Aspire V3-471               | Notebook    | [75664ddf0f](https://linux-hardware.org/?probe=75664ddf0f) | Jul 07, 2022 |
| MSI           | B250M PRO-VH                | Desktop     | [cab2cbb630](https://linux-hardware.org/?probe=cab2cbb630) | Jul 07, 2022 |
| ASUSTek       | ROG Maximus X APEX          | Desktop     | [e1fa4e4923](https://linux-hardware.org/?probe=e1fa4e4923) | Jul 06, 2022 |
| Intel         | X79Turbo V1.x               | Desktop     | [497c3810d8](https://linux-hardware.org/?probe=497c3810d8) | Jul 06, 2022 |
| Intel         | DQ35MP AAD82086-702         | Desktop     | [a0cae9f6a9](https://linux-hardware.org/?probe=a0cae9f6a9) | Jul 06, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [0d26f198ff](https://linux-hardware.org/?probe=0d26f198ff) | Jul 06, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0KE0... | Notebook    | [2d63b4ba76](https://linux-hardware.org/?probe=2d63b4ba76) | Jul 06, 2022 |
| MSI           | G41M-P23                    | Desktop     | [8885c18d8c](https://linux-hardware.org/?probe=8885c18d8c) | Jul 06, 2022 |
| HP            | 843C                        | Desktop     | [5f218ccb19](https://linux-hardware.org/?probe=5f218ccb19) | Jul 06, 2022 |
| MSI           | Z97 XPOWER AC               | Desktop     | [b7324cb6ab](https://linux-hardware.org/?probe=b7324cb6ab) | Jul 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [e4a8ad0984](https://linux-hardware.org/?probe=e4a8ad0984) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [498f4edafb](https://linux-hardware.org/?probe=498f4edafb) | Jul 05, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [5819973ca4](https://linux-hardware.org/?probe=5819973ca4) | Jul 05, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [4f31f807cb](https://linux-hardware.org/?probe=4f31f807cb) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [1264fab131](https://linux-hardware.org/?probe=1264fab131) | Jul 05, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [d46da7be57](https://linux-hardware.org/?probe=d46da7be57) | Jul 05, 2022 |
| Biostar       | H310MHC2                    | Desktop     | [9fc3974ab1](https://linux-hardware.org/?probe=9fc3974ab1) | Jul 05, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [8782b09be9](https://linux-hardware.org/?probe=8782b09be9) | Jul 05, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [46d0a033ca](https://linux-hardware.org/?probe=46d0a033ca) | Jul 05, 2022 |
| Dell          | Inspiron 14-3467            | Notebook    | [b9a61ec06d](https://linux-hardware.org/?probe=b9a61ec06d) | Jul 05, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [c68e40b7eb](https://linux-hardware.org/?probe=c68e40b7eb) | Jul 05, 2022 |
| Intel         | H61                         | Desktop     | [da6d35599a](https://linux-hardware.org/?probe=da6d35599a) | Jul 04, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5c39c57896](https://linux-hardware.org/?probe=5c39c57896) | Jul 04, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [dc966787de](https://linux-hardware.org/?probe=dc966787de) | Jul 04, 2022 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [8b5f0f789c](https://linux-hardware.org/?probe=8b5f0f789c) | Jul 04, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [62d8b20ff8](https://linux-hardware.org/?probe=62d8b20ff8) | Jul 04, 2022 |
| HP            | Pavilion dv4                | Notebook    | [d40a5bd13e](https://linux-hardware.org/?probe=d40a5bd13e) | Jul 04, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [e99c8ae46f](https://linux-hardware.org/?probe=e99c8ae46f) | Jul 04, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [440b013dd2](https://linux-hardware.org/?probe=440b013dd2) | Jul 04, 2022 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [aeb0f9ca52](https://linux-hardware.org/?probe=aeb0f9ca52) | Jul 03, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | Desktop     | [a1ca3ddb17](https://linux-hardware.org/?probe=a1ca3ddb17) | Jul 03, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [98c7e055a3](https://linux-hardware.org/?probe=98c7e055a3) | Jul 03, 2022 |
| ASUSTek       | P5K-VM                      | Desktop     | [ad9d0f9183](https://linux-hardware.org/?probe=ad9d0f9183) | Jul 02, 2022 |
| Microsoft     | Surface Book                | Tablet      | [8c5e163cd5](https://linux-hardware.org/?probe=8c5e163cd5) | Jul 02, 2022 |
| Dell          | Latitude E7450              | Notebook    | [6dc8d46993](https://linux-hardware.org/?probe=6dc8d46993) | Jul 02, 2022 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [ac6fde7f04](https://linux-hardware.org/?probe=ac6fde7f04) | Jul 02, 2022 |
| HP            | 212B                        | Desktop     | [bd8ef053fd](https://linux-hardware.org/?probe=bd8ef053fd) | Jul 02, 2022 |
| Dell          | Precision M6800             | Notebook    | [ba446bde45](https://linux-hardware.org/?probe=ba446bde45) | Jul 02, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [ef2f004b52](https://linux-hardware.org/?probe=ef2f004b52) | Jul 02, 2022 |
| ASRock        | Z390 Pro4                   | Desktop     | [25bd784ca6](https://linux-hardware.org/?probe=25bd784ca6) | Jul 02, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [497939c649](https://linux-hardware.org/?probe=497939c649) | Jul 02, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [924f16c3d0](https://linux-hardware.org/?probe=924f16c3d0) | Jul 02, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [a7cc8d2654](https://linux-hardware.org/?probe=a7cc8d2654) | Jul 01, 2022 |
| Samsung       | Q210/P210                   | Notebook    | [dfc97062be](https://linux-hardware.org/?probe=dfc97062be) | Jul 01, 2022 |
| Acer          | Extensa 5220                | Notebook    | [1ee1e31b52](https://linux-hardware.org/?probe=1ee1e31b52) | Jul 01, 2022 |
| Dell          | Latitude 3120               | Convertible | [42c26ea983](https://linux-hardware.org/?probe=42c26ea983) | Jul 01, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [a082da0857](https://linux-hardware.org/?probe=a082da0857) | Jun 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [06ca24d4e1](https://linux-hardware.org/?probe=06ca24d4e1) | Jun 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [88e0a63fab](https://linux-hardware.org/?probe=88e0a63fab) | Jun 30, 2022 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [5e8ae112a5](https://linux-hardware.org/?probe=5e8ae112a5) | Jun 30, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [0ecaca17cb](https://linux-hardware.org/?probe=0ecaca17cb) | Jun 30, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [4857a7b7bf](https://linux-hardware.org/?probe=4857a7b7bf) | Jun 30, 2022 |
| Dell          | Precision M6800             | Notebook    | [1eccdbb04e](https://linux-hardware.org/?probe=1eccdbb04e) | Jun 30, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a90f7795b](https://linux-hardware.org/?probe=7a90f7795b) | Jun 30, 2022 |
| Acer          | Aspire 5735                 | Notebook    | [b930fd3fcd](https://linux-hardware.org/?probe=b930fd3fcd) | Jun 29, 2022 |
| Dell          | Precision M6800             | Notebook    | [5b30cb4b9a](https://linux-hardware.org/?probe=5b30cb4b9a) | Jun 29, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [eb884aa3ca](https://linux-hardware.org/?probe=eb884aa3ca) | Jun 29, 2022 |
| Biostar       | A68N-5600E                  | Desktop     | [d5cfa78343](https://linux-hardware.org/?probe=d5cfa78343) | Jun 29, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [da80c0d1cd](https://linux-hardware.org/?probe=da80c0d1cd) | Jun 29, 2022 |
| AMI           | Intel                       | Notebook    | [2b592e2f4a](https://linux-hardware.org/?probe=2b592e2f4a) | Jun 29, 2022 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [fc5a5d812c](https://linux-hardware.org/?probe=fc5a5d812c) | Jun 29, 2022 |
| HP            | Compaq CQ45                 | Notebook    | [74948790d0](https://linux-hardware.org/?probe=74948790d0) | Jun 29, 2022 |
| Gigabyte      | EP45-UD3                    | Desktop     | [bb62363ad2](https://linux-hardware.org/?probe=bb62363ad2) | Jun 29, 2022 |
| HP            | 18E9                        | Desktop     | [67a4877415](https://linux-hardware.org/?probe=67a4877415) | Jun 29, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [c414829bec](https://linux-hardware.org/?probe=c414829bec) | Jun 28, 2022 |
| Dell          | Precision M6800             | Notebook    | [49b1b7edec](https://linux-hardware.org/?probe=49b1b7edec) | Jun 28, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f2f78497e6](https://linux-hardware.org/?probe=f2f78497e6) | Jun 28, 2022 |
| Intel         | DP43BF AAE78171-302         | Desktop     | [0115160101](https://linux-hardware.org/?probe=0115160101) | Jun 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [ed40a2bae5](https://linux-hardware.org/?probe=ed40a2bae5) | Jun 28, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [a767fd4cb1](https://linux-hardware.org/?probe=a767fd4cb1) | Jun 28, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [6932a00eed](https://linux-hardware.org/?probe=6932a00eed) | Jun 28, 2022 |
| Dell          | 0KRC95 A00                  | Desktop     | [04aacdbccd](https://linux-hardware.org/?probe=04aacdbccd) | Jun 28, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0f4c661912](https://linux-hardware.org/?probe=0f4c661912) | Jun 27, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [371c2586d6](https://linux-hardware.org/?probe=371c2586d6) | Jun 27, 2022 |
| HP            | 3047h                       | Desktop     | [32eb7049a1](https://linux-hardware.org/?probe=32eb7049a1) | Jun 27, 2022 |
| Acer          | UI2H                        | All in one  | [136c387973](https://linux-hardware.org/?probe=136c387973) | Jun 27, 2022 |
| ASRock        | 890GM Pro3 R2.0             | Desktop     | [4b7b86cf21](https://linux-hardware.org/?probe=4b7b86cf21) | Jun 27, 2022 |
| Lenovo        | Z40-75 80DW                 | Notebook    | [1fc3b34132](https://linux-hardware.org/?probe=1fc3b34132) | Jun 27, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [ec991b1524](https://linux-hardware.org/?probe=ec991b1524) | Jun 27, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [cbb6f48321](https://linux-hardware.org/?probe=cbb6f48321) | Jun 27, 2022 |
| Dell          | Latitude E6430              | Notebook    | [76c22c2645](https://linux-hardware.org/?probe=76c22c2645) | Jun 26, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5fa355f7ec](https://linux-hardware.org/?probe=5fa355f7ec) | Jun 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [1f3399d205](https://linux-hardware.org/?probe=1f3399d205) | Jun 26, 2022 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [4d48252e22](https://linux-hardware.org/?probe=4d48252e22) | Jun 26, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [1e18ee882c](https://linux-hardware.org/?probe=1e18ee882c) | Jun 26, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [240018e48a](https://linux-hardware.org/?probe=240018e48a) | Jun 26, 2022 |
| Lenovo        | S20-30 Touch 20434          | Notebook    | [b4ebe70967](https://linux-hardware.org/?probe=b4ebe70967) | Jun 26, 2022 |
| Toshiba       | Satellite C855-2CF          | Notebook    | [9e062a8425](https://linux-hardware.org/?probe=9e062a8425) | Jun 26, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [352a224c3f](https://linux-hardware.org/?probe=352a224c3f) | Jun 26, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d690a68389](https://linux-hardware.org/?probe=d690a68389) | Jun 25, 2022 |
| Gigabyte      | Z690 UD                     | Desktop     | [2c21dadeed](https://linux-hardware.org/?probe=2c21dadeed) | Jun 25, 2022 |
| ASUSTek       | H81M-R 2016-11-08           | Desktop     | [f9ac4d3e81](https://linux-hardware.org/?probe=f9ac4d3e81) | Jun 25, 2022 |
| Toshiba       | Satellite C660D             | Notebook    | [fc25883979](https://linux-hardware.org/?probe=fc25883979) | Jun 25, 2022 |
| Foxconn       | 945 7MC Series              | Desktop     | [16836e63f5](https://linux-hardware.org/?probe=16836e63f5) | Jun 25, 2022 |
| MSI           | A78M-E45                    | Desktop     | [ca217e0ccb](https://linux-hardware.org/?probe=ca217e0ccb) | Jun 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.3/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003       | 3349      | 96.6%   |
| 5.16.13-desktop-1omv4003      | 83        | 2.39%   |
| 5.17.1-desktop-2omv4050       | 17        | 0.49%   |
| 5.14.14-desktop-1omv4050      | 4         | 0.12%   |
| 5.16.5-desktop-2omv4003       | 3         | 0.09%   |
| 5.17.1-desktop-clang-2omv4050 | 2         | 0.06%   |
| 5.16.9-desktop-1omv4003       | 2         | 0.06%   |
| 5.16.3-desktop-2omv4050       | 2         | 0.06%   |
| 5.17.7-desktop-1omv4090       | 1         | 0.03%   |
| 5.16.9-desktop-1omv4050       | 1         | 0.03%   |
| 5.16.7-desktop-clang-1omv4003 | 1         | 0.03%   |
| 5.15.14-1-lts                 | 1         | 0.03%   |
| 5.10.14-desktop-1omv4002      | 1         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.7  | 3350      | 96.63%  |
| 5.16.13 | 83        | 2.39%   |
| 5.17.1  | 19        | 0.55%   |
| 5.14.14 | 4         | 0.12%   |
| 5.16.9  | 3         | 0.09%   |
| 5.16.5  | 3         | 0.09%   |
| 5.16.3  | 2         | 0.06%   |
| 5.17.7  | 1         | 0.03%   |
| 5.15.14 | 1         | 0.03%   |
| 5.10.14 | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 3441      | 99.25%  |
| 5.17    | 20        | 0.58%   |
| 5.14    | 4         | 0.12%   |
| 5.15    | 1         | 0.03%   |
| 5.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 3467      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDE5    | 3455      | 99.65%  |
| LXQt    | 7         | 0.2%    |
| Unknown | 5         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3445      | 99.37%  |
| Wayland | 22        | 0.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SDDM | 3467      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 1980      | 57.11%  |
| de_DE | 330       | 9.52%   |
| ru_RU | 169       | 4.87%   |
| fr_FR | 154       | 4.44%   |
| pt_BR | 132       | 3.81%   |
| it_IT | 98        | 2.83%   |
| pl_PL | 93        | 2.68%   |
| en_GB | 68        | 1.96%   |
| es_ES | 65        | 1.87%   |
| es_AR | 33        | 0.95%   |
| de_AT | 30        | 0.87%   |
| cs_CZ | 27        | 0.78%   |
| es_MX | 26        | 0.75%   |
| en_IN | 24        | 0.69%   |
| hu_HU | 17        | 0.49%   |
| en_CA | 17        | 0.49%   |
| pt_PT | 16        | 0.46%   |
| tr_TR | 14        | 0.4%    |
| nl_NL | 14        | 0.4%    |
| es_CO | 14        | 0.4%    |
| de_CH | 14        | 0.4%    |
| en_AU | 12        | 0.35%   |
| es_CL | 11        | 0.32%   |
| fr_CA | 10        | 0.29%   |
| nl_BE | 9         | 0.26%   |
| ru_UA | 8         | 0.23%   |
| fr_BE | 8         | 0.23%   |
| es_VE | 8         | 0.23%   |
| nb_NO | 5         | 0.14%   |
| es_PE | 5         | 0.14%   |
| es_CR | 5         | 0.14%   |
| ro_RO | 4         | 0.12%   |
| fr_CH | 4         | 0.12%   |
| da_DK | 4         | 0.12%   |
| uk_UA | 3         | 0.09%   |
| es_SV | 3         | 0.09%   |
| es_EC | 3         | 0.09%   |
| en_ZA | 3         | 0.09%   |
| es_UY | 2         | 0.06%   |
| es_PY | 2         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1852      | 53.42%  |
| BIOS | 1615      | 46.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Overlay  | 2896      | 83.53%  |
| Ext4     | 562       | 16.21%  |
| Xfs      | 3         | 0.09%   |
| Btrfs    | 3         | 0.09%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |
| F2fs     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2341      | 67.52%  |
| MBR     | 1111      | 32.04%  |
| Unknown | 15        | 0.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1944      | 56.07%  |
| No        | 1523      | 43.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1751      | 50.5%   |
| Yes       | 1716      | 49.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ASUSTek Computer      | 547       | 15.78%  |
| Dell                  | 476       | 13.73%  |
| Hewlett-Packard       | 456       | 13.15%  |
| Lenovo                | 410       | 11.83%  |
| Gigabyte Technology   | 311       | 8.97%   |
| Acer                  | 217       | 6.26%   |
| MSI                   | 207       | 5.97%   |
| ASRock                | 147       | 4.24%   |
| Toshiba               | 82        | 2.37%   |
| Intel                 | 76        | 2.19%   |
| Fujitsu               | 56        | 1.62%   |
| Apple                 | 50        | 1.44%   |
| Sony                  | 37        | 1.07%   |
| Samsung Electronics   | 34        | 0.98%   |
| Positivo              | 25        | 0.72%   |
| Foxconn               | 22        | 0.63%   |
| Biostar               | 22        | 0.63%   |
| Medion                | 19        | 0.55%   |
| Packard Bell          | 18        | 0.52%   |
| Unknown               | 16        | 0.46%   |
| Pegatron              | 12        | 0.35%   |
| TUXEDO                | 10        | 0.29%   |
| ECS                   | 10        | 0.29%   |
| BESSTAR Tech          | 10        | 0.29%   |
| Fujitsu Siemens       | 9         | 0.26%   |
| Alienware             | 9         | 0.26%   |
| HUAWEI                | 8         | 0.23%   |
| AZW                   | 8         | 0.23%   |
| Philco                | 7         | 0.2%    |
| Shuttle               | 6         | 0.17%   |
| Notebook              | 6         | 0.17%   |
| LG Electronics        | 6         | 0.17%   |
| eMachines             | 6         | 0.17%   |
| Chuwi                 | 6         | 0.17%   |
| Supermicro            | 5         | 0.14%   |
| Microsoft             | 5         | 0.14%   |
| Gateway               | 5         | 0.14%   |
| Compaq                | 5         | 0.14%   |
| Positivo Bahia - VAIO | 4         | 0.12%   |
| Digibras              | 4         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell Latitude 3120             | 47        | 1.36%   |
| Dell Latitude 3190 2-in-1      | 33        | 0.95%   |
| ASUS All Series                | 32        | 0.92%   |
| Unknown                        | 30        | 0.87%   |
| Dell Latitude 3310             | 29        | 0.84%   |
| Gigabyte H410M H V3            | 27        | 0.78%   |
| ASUS SABERTOOTH Z77            | 18        | 0.52%   |
| HP Notebook                    | 14        | 0.4%    |
| Dell OptiPlex 7010             | 11        | 0.32%   |
| HP Pavilion g6                 | 9         | 0.26%   |
| Dell OptiPlex 780              | 9         | 0.26%   |
| Lenovo IdeaPad 1 14ADA05 82GW  | 8         | 0.23%   |
| Intel H61                      | 8         | 0.23%   |
| Dell Latitude 3300             | 8         | 0.23%   |
| HP Pavilion dv6                | 7         | 0.2%    |
| Dell OptiPlex 790              | 7         | 0.2%    |
| Dell Latitude E7450            | 7         | 0.2%    |
| Sony VGN-FZ31Z                 | 6         | 0.17%   |
| Positivo Mobile                | 6         | 0.17%   |
| MSI MS-7C91                    | 6         | 0.17%   |
| MSI MS-7A38                    | 6         | 0.17%   |
| MSI MS-7721                    | 6         | 0.17%   |
| HP Laptop 14-fq0xxx            | 6         | 0.17%   |
| HP EliteDesk 800 G1 SFF        | 6         | 0.17%   |
| HP Compaq Pro 6300 SFF         | 6         | 0.17%   |
| Dell OptiPlex 9020             | 6         | 0.17%   |
| Dell Latitude 3189             | 6         | 0.17%   |
| ASUS ROG STRIX B550-F GAMING   | 6         | 0.17%   |
| Acer Aspire A515-51G           | 6         | 0.17%   |
| MSI MS-7C84                    | 5         | 0.14%   |
| MSI MS-7C37                    | 5         | 0.14%   |
| MSI MS-7C02                    | 5         | 0.14%   |
| MSI MS-7B79                    | 5         | 0.14%   |
| Lenovo IdeaPad S340-14API 81NB | 5         | 0.14%   |
| HP ProDesk 600 G1 SFF          | 5         | 0.14%   |
| HP Pavilion dv7                | 5         | 0.14%   |
| HP Pavilion 15                 | 5         | 0.14%   |
| HP Compaq 8100 Elite CMT PC    | 5         | 0.14%   |
| HP Compaq 15                   | 5         | 0.14%   |
| Gigabyte B450M DS3H            | 5         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 244       | 7.04%   |
| Acer Aspire           | 149       | 4.3%    |
| Lenovo ThinkPad       | 134       | 3.87%   |
| Lenovo IdeaPad        | 102       | 2.94%   |
| HP Pavilion           | 86        | 2.48%   |
| Dell OptiPlex         | 82        | 2.37%   |
| HP Compaq             | 69        | 1.99%   |
| Toshiba Satellite     | 67        | 1.93%   |
| ASUS PRIME            | 62        | 1.79%   |
| Dell Inspiron         | 61        | 1.76%   |
| HP Laptop             | 52        | 1.5%    |
| Lenovo ThinkCentre    | 47        | 1.36%   |
| HP ProBook            | 42        | 1.21%   |
| ASUS VivoBook         | 38        | 1.1%    |
| ASUS TUF              | 34        | 0.98%   |
| ASUS ROG              | 33        | 0.95%   |
| ASUS All              | 32        | 0.92%   |
| Gigabyte H410M        | 30        | 0.87%   |
| Unknown               | 30        | 0.87%   |
| Dell Precision        | 28        | 0.81%   |
| HP EliteBook          | 25        | 0.72%   |
| ASUS SABERTOOTH       | 24        | 0.69%   |
| HP EliteDesk          | 23        | 0.66%   |
| Fujitsu LIFEBOOK      | 23        | 0.66%   |
| Dell XPS              | 22        | 0.63%   |
| Fujitsu ESPRIMO       | 21        | 0.61%   |
| HP ProDesk            | 19        | 0.55%   |
| Dell Vostro           | 19        | 0.55%   |
| Lenovo IdeaCentre     | 18        | 0.52%   |
| HP Notebook           | 14        | 0.4%    |
| ASUS M5A78L-M         | 14        | 0.4%    |
| Acer Swift            | 13        | 0.37%   |
| Packard Bell EasyNote | 12        | 0.35%   |
| Gigabyte B450M        | 12        | 0.35%   |
| Acer Nitro            | 11        | 0.32%   |
| Lenovo Yoga           | 10        | 0.29%   |
| Gigabyte X570         | 10        | 0.29%   |
| Acer Extensa          | 10        | 0.29%   |
| Intel H61             | 9         | 0.26%   |
| HP ENVY               | 9         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 328       | 9.46%   |
| 2021    | 298       | 8.6%    |
| 2011    | 296       | 8.54%   |
| 2019    | 292       | 8.42%   |
| 2013    | 285       | 8.22%   |
| 2020    | 272       | 7.85%   |
| 2018    | 249       | 7.18%   |
| 2010    | 231       | 6.66%   |
| 2014    | 228       | 6.58%   |
| 2016    | 180       | 5.19%   |
| 2017    | 177       | 5.11%   |
| 2015    | 162       | 4.67%   |
| 2009    | 150       | 4.33%   |
| 2008    | 142       | 4.1%    |
| 2007    | 104       | 3%      |
| 2006    | 48        | 1.38%   |
| 2022    | 17        | 0.49%   |
| 2005    | 4         | 0.12%   |
| Unknown | 4         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1624      | 46.84%  |
| Desktop     | 1596      | 46.03%  |
| Convertible | 112       | 3.23%   |
| All in one  | 58        | 1.67%   |
| Mini pc     | 56        | 1.62%   |
| Tablet      | 11        | 0.32%   |
| Server      | 10        | 0.29%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3467      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3462      | 99.86%  |
| Yes  | 5         | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1018      | 29.36%  |
| 3.01-4.0        | 863       | 24.89%  |
| 8.01-16.0       | 607       | 17.51%  |
| 16.01-24.0      | 516       | 14.88%  |
| 32.01-64.0      | 214       | 6.17%   |
| 1.01-2.0        | 112       | 3.23%   |
| 24.01-32.0      | 46        | 1.33%   |
| 64.01-256.0     | 41        | 1.18%   |
| 2.01-3.0        | 40        | 1.15%   |
| 0.51-1.0        | 8         | 0.23%   |
| More than 256.0 | 2         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 2595      | 74.85%  |
| 0.51-1.0  | 537       | 15.49%  |
| 2.01-3.0  | 246       | 7.1%    |
| 0.01-0.5  | 40        | 1.15%   |
| 3.01-4.0  | 26        | 0.75%   |
| 4.01-8.0  | 15        | 0.43%   |
| 8.01-16.0 | 8         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2023      | 58.35%  |
| 2      | 864       | 24.92%  |
| 3      | 270       | 7.79%   |
| 4      | 142       | 4.1%    |
| 0      | 66        | 1.9%    |
| 5      | 54        | 1.56%   |
| 6      | 23        | 0.66%   |
| 7      | 9         | 0.26%   |
| 8      | 6         | 0.17%   |
| 9      | 4         | 0.12%   |
| 12     | 3         | 0.09%   |
| 15     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |
| 10     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1787      | 51.54%  |
| Yes       | 1680      | 48.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3089      | 89.1%   |
| No        | 378       | 10.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2391      | 68.96%  |
| No        | 1076      | 31.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1792      | 51.69%  |
| No        | 1675      | 48.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 449       | 12.95%  |
| USA         | 415       | 11.97%  |
| Brazil      | 219       | 6.32%   |
| France      | 212       | 6.11%   |
| Russia      | 197       | 5.68%   |
| Netherlands | 184       | 5.31%   |
| Poland      | 164       | 4.73%   |
| Italy       | 146       | 4.21%   |
| UK          | 110       | 3.17%   |
| Spain       | 90        | 2.6%    |
| Canada      | 90        | 2.6%    |
| India       | 68        | 1.96%   |
| Australia   | 64        | 1.85%   |
| Mexico      | 53        | 1.53%   |
| Indonesia   | 46        | 1.33%   |
| Japan       | 45        | 1.3%    |
| Argentina   | 44        | 1.27%   |
| Portugal    | 42        | 1.21%   |
| Ukraine     | 41        | 1.18%   |
| Czechia     | 40        | 1.15%   |
| Austria     | 40        | 1.15%   |
| Switzerland | 36        | 1.04%   |
| Sweden      | 34        | 0.98%   |
| Turkey      | 31        | 0.89%   |
| Colombia    | 30        | 0.87%   |
| Romania     | 28        | 0.81%   |
| Hungary     | 28        | 0.81%   |
| Belgium     | 28        | 0.81%   |
| Serbia      | 23        | 0.66%   |
| Slovakia    | 21        | 0.61%   |
| Finland     | 20        | 0.58%   |
| Greece      | 18        | 0.52%   |
| China       | 18        | 0.52%   |
| Bulgaria    | 17        | 0.49%   |
| Egypt       | 16        | 0.46%   |
| New Zealand | 15        | 0.43%   |
| Chile       | 15        | 0.43%   |
| Peru        | 14        | 0.4%    |
| Norway      | 14        | 0.4%    |
| Israel      | 14        | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Schagen        | 135       | 3.89%   |
| Moscow         | 40        | 1.15%   |
| Berlin         | 32        | 0.92%   |
| Sao Paulo      | 29        | 0.84%   |
| Paris          | 29        | 0.84%   |
| Vienna         | 23        | 0.66%   |
| Milan          | 23        | 0.66%   |
| Gonikoppal     | 22        | 0.63%   |
| Warsaw         | 21        | 0.61%   |
| Sydney         | 17        | 0.49%   |
| Strzyzow       | 16        | 0.46%   |
| Munich         | 16        | 0.46%   |
| Hamburg        | 15        | 0.43%   |
| Istanbul       | 14        | 0.4%    |
| Belgrade       | 14        | 0.4%    |
| Rio de Janeiro | 13        | 0.37%   |
| Prague         | 13        | 0.37%   |
| Mexico City    | 13        | 0.37%   |
| Krakow         | 12        | 0.35%   |
| Jakarta        | 12        | 0.35%   |
| St Petersburg  | 11        | 0.32%   |
| Brisbane       | 11        | 0.32%   |
| Wroclaw        | 10        | 0.29%   |
| Rome           | 10        | 0.29%   |
| Lima           | 10        | 0.29%   |
| Cairo          | 10        | 0.29%   |
| Buenos Aires   | 10        | 0.29%   |
| Bengaluru      | 10        | 0.29%   |
| Zagreb         | 9         | 0.26%   |
| San José      | 9         | 0.26%   |
| Madrid         | 9         | 0.26%   |
| Helsinki       | 9         | 0.26%   |
| Dortmund       | 9         | 0.26%   |
| Curitiba       | 9         | 0.26%   |
| Yekaterinburg  | 8         | 0.23%   |
| Kyiv           | 8         | 0.23%   |
| Gdansk         | 8         | 0.23%   |
| Cascais        | 8         | 0.23%   |
| Barcelona      | 8         | 0.23%   |
| Athens         | 8         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 837       | 1005   | 16.74%  |
| Seagate             | 727       | 879    | 14.54%  |
| Samsung Electronics | 664       | 788    | 13.28%  |
| Toshiba             | 350       | 367    | 7%      |
| Kingston            | 290       | 309    | 5.8%    |
| Crucial             | 229       | 264    | 4.58%   |
| SanDisk             | 204       | 227    | 4.08%   |
| Hitachi             | 191       | 198    | 3.82%   |
| SK hynix            | 129       | 133    | 2.58%   |
| A-DATA Technology   | 128       | 136    | 2.56%   |
| Unknown             | 126       | 137    | 2.52%   |
| HGST                | 92        | 101    | 1.84%   |
| Intel               | 63        | 68     | 1.26%   |
| Micron Technology   | 48        | 48     | 0.96%   |
| China               | 48        | 52     | 0.96%   |
| Unknown             | 37        | 37     | 0.74%   |
| PNY                 | 36        | 43     | 0.72%   |
| LITEON              | 35        | 35     | 0.7%    |
| Goodram             | 35        | 37     | 0.7%    |
| SPCC                | 31        | 34     | 0.62%   |
| KIOXIA              | 31        | 31     | 0.62%   |
| Intenso             | 29        | 29     | 0.58%   |
| ASMT                | 29        | 32     | 0.58%   |
| Patriot             | 28        | 29     | 0.56%   |
| Apacer              | 26        | 27     | 0.52%   |
| Maxtor              | 24        | 28     | 0.48%   |
| JMicron Technology  | 24        | 25     | 0.48%   |
| Gigabyte Technology | 24        | 24     | 0.48%   |
| Fujitsu             | 23        | 23     | 0.46%   |
| Corsair             | 23        | 24     | 0.46%   |
| Apple               | 23        | 23     | 0.46%   |
| SSSTC               | 21        | 21     | 0.42%   |
| Phison              | 21        | 23     | 0.42%   |
| Netac               | 20        | 21     | 0.4%    |
| OCZ                 | 19        | 19     | 0.38%   |
| Transcend           | 18        | 19     | 0.36%   |
| Hewlett-Packard     | 17        | 20     | 0.34%   |
| Silicon Motion      | 16        | 18     | 0.32%   |
| KingSpec            | 16        | 16     | 0.32%   |
| Team                | 10        | 10     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 64        | 1.17%   |
| Seagate ST500DM002-1BD142 500GB    | 50        | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB     | 44        | 0.8%    |
| Kingston SA400S37120G 120GB SSD    | 39        | 0.71%   |
| Samsung SSD 860 EVO 500GB          | 38        | 0.69%   |
| Unknown                            | 37        | 0.67%   |
| Toshiba MQ01ABF050 500GB           | 36        | 0.66%   |
| Samsung SSD 860 EVO 250GB          | 35        | 0.64%   |
| Samsung SSD 850 EVO 250GB          | 35        | 0.64%   |
| Crucial CT500MX500SSD1 500GB       | 34        | 0.62%   |
| Kingston SA400S37480G 480GB SSD    | 33        | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 31        | 0.57%   |
| WDC WD10EZEX-08WN4A0 1TB           | 30        | 0.55%   |
| Unknown SD/MMC/MS PRO 2GB          | 30        | 0.55%   |
| Toshiba MQ01ABD100 1TB             | 30        | 0.55%   |
| Seagate ST2000DM008-2FR102 2TB     | 30        | 0.55%   |
| Crucial CT240BX500SSD1 240GB       | 29        | 0.53%   |
| Toshiba DT01ACA100 1TB             | 26        | 0.47%   |
| Seagate ST500LT012-1DG142 500GB    | 26        | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 25        | 0.46%   |
| Toshiba DT01ACA050 500GB           | 25        | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB     | 25        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB        | 25        | 0.46%   |
| Toshiba MQ04ABF100 1TB             | 24        | 0.44%   |
| Samsung SSD 850 EVO 500GB          | 24        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD   | 23        | 0.42%   |
| SK hynix BC711 NVMe 128GB          | 22        | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB     | 22        | 0.4%    |
| A-DATA SU750 256GB SSD             | 22        | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB     | 21        | 0.38%   |
| Crucial CT480BX500SSD1 480GB       | 20        | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 18        | 0.33%   |
| HGST HTS721010A9E630 1TB           | 18        | 0.33%   |
| Toshiba HDWD110 1TB                | 17        | 0.31%   |
| Seagate ST9500325AS 500GB          | 17        | 0.31%   |
| Seagate ST2000DM001-1ER164 2TB     | 17        | 0.31%   |
| SanDisk SSD PLUS 240GB             | 17        | 0.31%   |
| Samsung SSD 970 EVO Plus 1TB       | 17        | 0.31%   |
| JMicron Generic 120GB              | 17        | 0.31%   |
| Seagate ST3500418AS 500GB          | 16        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 715       | 858    | 31.62%  |
| WDC                 | 674       | 792    | 29.81%  |
| Toshiba             | 311       | 325    | 13.75%  |
| Hitachi             | 191       | 198    | 8.45%   |
| Samsung Electronics | 138       | 152    | 6.1%    |
| HGST                | 92        | 101    | 4.07%   |
| Unknown             | 31        | 31     | 1.37%   |
| Maxtor              | 23        | 27     | 1.02%   |
| Fujitsu             | 23        | 23     | 1.02%   |
| Apple               | 14        | 14     | 0.62%   |
| ASMT                | 8         | 11     | 0.35%   |
| WD MediaMax         | 4         | 5      | 0.18%   |
| ASMedia             | 4         | 4      | 0.18%   |
| USB3.0              | 3         | 3      | 0.13%   |
| Magnetic Data       | 3         | 3      | 0.13%   |
| JMicron Technology  | 3         | 3      | 0.13%   |
| IBM/Hitachi         | 3         | 3      | 0.13%   |
| SAGE                | 2         | 2      | 0.09%   |
| Intenso             | 2         | 2      | 0.09%   |
| HPE                 | 2         | 2      | 0.09%   |
| Hewlett-Packard     | 2         | 2      | 0.09%   |
| Unknown             | 2         | 2      | 0.09%   |
| SATAFIRM            | 1         | 1      | 0.04%   |
| RSH-339             | 1         | 1      | 0.04%   |
| Quantum             | 1         | 1      | 0.04%   |
| QC-FT-D             | 1         | 1      | 0.04%   |
| MARVELL             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 1      | 0.04%   |
| Inateck             | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| Config              | 1         | 1      | 0.04%   |
| China               | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 372       | 412    | 19.78%  |
| Kingston            | 241       | 254    | 12.81%  |
| Crucial             | 196       | 223    | 10.42%  |
| SanDisk             | 181       | 199    | 9.62%   |
| WDC                 | 104       | 110    | 5.53%   |
| A-DATA Technology   | 99        | 100    | 5.26%   |
| China               | 47        | 51     | 2.5%    |
| Micron Technology   | 36        | 36     | 1.91%   |
| SK hynix            | 35        | 36     | 1.86%   |
| GOODRAM             | 33        | 33     | 1.75%   |
| LITEON              | 32        | 32     | 1.7%    |
| PNY                 | 31        | 36     | 1.65%   |
| Toshiba             | 25        | 26     | 1.33%   |
| Intel               | 25        | 26     | 1.33%   |
| Patriot             | 24        | 25     | 1.28%   |
| Intenso             | 24        | 24     | 1.28%   |
| Apacer              | 24        | 24     | 1.28%   |
| SPCC                | 23        | 25     | 1.22%   |
| Unknown             | 22        | 22     | 1.17%   |
| OCZ                 | 19        | 19     | 1.01%   |
| ASMT                | 18        | 18     | 0.96%   |
| Transcend           | 17        | 18     | 0.9%    |
| Netac               | 17        | 18     | 0.9%    |
| KingSpec            | 16        | 16     | 0.85%   |
| Gigabyte Technology | 14        | 14     | 0.74%   |
| Team                | 10        | 10     | 0.53%   |
| LITEONIT            | 10        | 10     | 0.53%   |
| Hewlett-Packard     | 10        | 12     | 0.53%   |
| Corsair             | 10        | 10     | 0.53%   |
| Lexar               | 7         | 7      | 0.37%   |
| KingFast            | 7         | 7      | 0.37%   |
| KingDian            | 7         | 7      | 0.37%   |
| Apple               | 7         | 7      | 0.37%   |
| KIOXIA-EXCERIA      | 6         | 6      | 0.32%   |
| TCSUNBOW            | 5         | 5      | 0.27%   |
| Seagate             | 5         | 5      | 0.27%   |
| Leven               | 5         | 5      | 0.27%   |
| TO Exter            | 4         | 4      | 0.21%   |
| Plextor             | 4         | 4      | 0.21%   |
| INNOVATION IT       | 4         | 4      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1926      | 2574   | 43.28%  |
| SSD     | 1612      | 2006   | 36.22%  |
| NVMe    | 750       | 862    | 16.85%  |
| MMC     | 114       | 121    | 2.56%   |
| Unknown | 48        | 60     | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2929      | 4398   | 73.19%  |
| NVMe | 729       | 830    | 18.22%  |
| SAS  | 230       | 274    | 5.75%   |
| MMC  | 114       | 121    | 2.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2337      | 2985   | 63.84%  |
| 0.51-1.0   | 939       | 1126   | 25.65%  |
| 1.01-2.0   | 238       | 279    | 6.5%    |
| 3.01-4.0   | 53        | 73     | 1.45%   |
| 2.01-3.0   | 49        | 56     | 1.34%   |
| 4.01-10.0  | 38        | 54     | 1.04%   |
| 10.01-20.0 | 7         | 7      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2009      | 57.95%  |
| 101-250        | 463       | 13.35%  |
| 251-500        | 283       | 8.16%   |
| Unknown        | 267       | 7.7%    |
| 501-1000       | 143       | 4.12%   |
| 21-50          | 122       | 3.52%   |
| 51-100         | 113       | 3.26%   |
| 1001-2000      | 45        | 1.3%    |
| More than 3000 | 13        | 0.37%   |
| 2001-3000      | 9         | 0.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2952      | 85.15%  |
| Unknown        | 267       | 7.7%    |
| 101-250        | 70        | 2.02%   |
| 51-100         | 59        | 1.7%    |
| 21-50          | 52        | 1.5%    |
| 251-500        | 29        | 0.84%   |
| 501-1000       | 19        | 0.55%   |
| 1001-2000      | 13        | 0.37%   |
| More than 3000 | 3         | 0.09%   |
| 2001-3000      | 3         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 24        | 25     | 2.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 14        | 14     | 1.39%   |
| HGST HTS545050A7E680 500GB          | 12        | 12     | 1.19%   |
| Toshiba MQ01ABF050 500GB            | 11        | 11     | 1.09%   |
| Seagate ST9500325AS 500GB           | 11        | 11     | 1.09%   |
| HGST HTS541010A9E680 1TB            | 10        | 10     | 0.99%   |
| Seagate ST9320325AS 320GB           | 9         | 9      | 0.89%   |
| Kingston SV300S37A120G 120GB SSD    | 9         | 9      | 0.89%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 8         | 8      | 0.8%    |
| Seagate ST3500413AS 500GB           | 8         | 8      | 0.8%    |
| Hitachi HTS543232A7A384 320GB       | 8         | 8      | 0.8%    |
| Seagate ST500LT012-1DG142 500GB     | 7         | 7      | 0.7%    |
| HGST HTS721010A9E630 1TB            | 7         | 8      | 0.7%    |
| HGST HTS545050A7E380 500GB          | 7         | 7      | 0.7%    |
| Toshiba MQ01ABD100 1TB              | 6         | 6      | 0.6%    |
| Toshiba MQ01ABD050 500GB            | 6         | 6      | 0.6%    |
| Seagate ST1000LM035-1RK172 1TB      | 6         | 6      | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB      | 6         | 6      | 0.6%    |
| Seagate ST1000DM003-9YN162 1TB      | 6         | 6      | 0.6%    |
| Samsung Electronics HD322HJ 320GB   | 6         | 6      | 0.6%    |
| HGST HTS725050A7E630 500GB          | 6         | 6      | 0.6%    |
| Crucial CT240M500SSD1 240GB         | 6         | 6      | 0.6%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 5         | 5      | 0.5%    |
| Seagate ST3500418AS 500GB           | 5         | 5      | 0.5%    |
| SanDisk SSD PLUS 480GB              | 5         | 5      | 0.5%    |
| GOODRAM SSD 120GB                   | 5         | 5      | 0.5%    |
| WDC WD5000AAKX-00ERMA0 500GB        | 4         | 4      | 0.4%    |
| WDC WD5000AAKS-00V1A0 500GB         | 4         | 4      | 0.4%    |
| WDC WD5000AADS-00S9B0 500GB         | 4         | 4      | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB            | 4         | 4      | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB            | 4         | 4      | 0.4%    |
| Toshiba MK1246GSX 120GB             | 4         | 4      | 0.4%    |
| Toshiba DT01ACA050 500GB            | 4         | 4      | 0.4%    |
| Seagate ST92505610AS 250GB          | 4         | 4      | 0.4%    |
| Seagate ST9250410AS 250GB           | 4         | 4      | 0.4%    |
| Seagate ST380013AS 80GB             | 4         | 4      | 0.4%    |
| Seagate ST31000528AS 1TB            | 4         | 4      | 0.4%    |
| Seagate ST250DM000-1BD141 250GB     | 4         | 4      | 0.4%    |
| Seagate ST1000DM003-1SB102 1TB      | 4         | 4      | 0.4%    |
| SanDisk SSD PLUS 240GB              | 4         | 4      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 254       | 272    | 26.08%  |
| WDC                 | 205       | 221    | 21.05%  |
| Hitachi             | 98        | 100    | 10.06%  |
| Toshiba             | 88        | 88     | 9.03%   |
| Samsung Electronics | 85        | 88     | 8.73%   |
| HGST                | 51        | 52     | 5.24%   |
| Kingston            | 24        | 24     | 2.46%   |
| SanDisk             | 23        | 23     | 2.36%   |
| Crucial             | 20        | 21     | 2.05%   |
| Maxtor              | 15        | 15     | 1.54%   |
| A-DATA Technology   | 14        | 14     | 1.44%   |
| Intel               | 11        | 11     | 1.13%   |
| Fujitsu             | 11        | 11     | 1.13%   |
| SK hynix            | 8         | 9      | 0.82%   |
| Micron Technology   | 8         | 8      | 0.82%   |
| GOODRAM             | 5         | 5      | 0.51%   |
| China               | 4         | 4      | 0.41%   |
| Apple               | 4         | 4      | 0.41%   |
| LITEON              | 3         | 3      | 0.31%   |
| IBM/Hitachi         | 3         | 3      | 0.31%   |
| ASMT                | 3         | 3      | 0.31%   |
| Transcend           | 2         | 2      | 0.21%   |
| SPCC                | 2         | 2      | 0.21%   |
| OCZ                 | 2         | 2      | 0.21%   |
| KingSpec            | 2         | 2      | 0.21%   |
| Hewlett-Packard     | 2         | 2      | 0.21%   |
| Corsair             | 2         | 2      | 0.21%   |
| ASMedia             | 2         | 2      | 0.21%   |
| Unknown             | 2         | 2      | 0.21%   |
| WDC WDS2            | 1         | 1      | 0.1%    |
| WD MediaMax         | 1         | 1      | 0.1%    |
| Vaseky              | 1         | 1      | 0.1%    |
| TO Exter            | 1         | 1      | 0.1%    |
| TEXTORM             | 1         | 1      | 0.1%    |
| TCSUNBOW            | 1         | 1      | 0.1%    |
| RSH-339             | 1         | 1      | 0.1%    |
| PNY                 | 1         | 1      | 0.1%    |
| Patriot             | 1         | 1      | 0.1%    |
| Neo                 | 1         | 1      | 0.1%    |
| Magnetic Data       | 1         | 1      | 0.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 254       | 272    | 32.19%  |
| WDC                 | 193       | 207    | 24.46%  |
| Hitachi             | 98        | 100    | 12.42%  |
| Toshiba             | 85        | 85     | 10.77%  |
| Samsung Electronics | 68        | 70     | 8.62%   |
| HGST                | 51        | 52     | 6.46%   |
| Maxtor              | 15        | 15     | 1.9%    |
| Fujitsu             | 11        | 11     | 1.39%   |
| IBM/Hitachi         | 3         | 3      | 0.38%   |
| Apple               | 3         | 3      | 0.38%   |
| ASMedia             | 2         | 2      | 0.25%   |
| WD MediaMax         | 1         | 1      | 0.13%   |
| RSH-339             | 1         | 1      | 0.13%   |
| Magnetic Data       | 1         | 1      | 0.13%   |
| HPE                 | 1         | 1      | 0.13%   |
| ExcelStor           | 1         | 1      | 0.13%   |
| Unknown             | 1         | 1      | 0.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 731       | 826    | 79.89%  |
| SSD  | 174       | 180    | 19.02%  |
| NVMe | 10        | 10     | 1.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HD103SJ 1TB                  | 3         | 3      | 8.57%   |
| Apple HDD HTS541010A9E662 1TB                    | 3         | 3      | 8.57%   |
| WDC WD3200BEVT-11ZCT0 320GB                      | 2         | 2      | 5.71%   |
| WDC WD5000BEVT-22ZAT0 500GB                      | 1         | 1      | 2.86%   |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 2.86%   |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1         | 1      | 2.86%   |
| WDC WD2500BEVT-60ZCT1 250GB                      | 1         | 1      | 2.86%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 2.86%   |
| WDC WD1600YS-23SHB0 160GB                        | 1         | 1      | 2.86%   |
| WDC WD1600BEVT-75A23T0 160GB                     | 1         | 1      | 2.86%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 2.86%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 2.86%   |
| Toshiba MK3265GSXN 320GB                         | 1         | 1      | 2.86%   |
| Toshiba MK3256GSY 320GB                          | 1         | 1      | 2.86%   |
| Seagate STM31000528AS 1TB                        | 1         | 1      | 2.86%   |
| Seagate ST980811AS 80GB                          | 1         | 1      | 2.86%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.86%   |
| Seagate ST3160215A 160GB                         | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 2.86%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 2.86%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 2.86%   |
| Samsung Electronics HD502IJ 500GB                | 1         | 1      | 2.86%   |
| Samsung Electronics HD103UJ 1TB                  | 1         | 1      | 2.86%   |
| Intel SSDSA2BW160G3 160GB                        | 1         | 1      | 2.86%   |
| Hitachi HTS725050A7E630 500GB                    | 1         | 1      | 2.86%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 2.86%   |
| Hitachi HDS721010DLE630 1TB                      | 1         | 1      | 2.86%   |
| Hitachi HDP725050GLA360 500GB                    | 1         | 1      | 2.86%   |
| GOODRAM SSDPR-PX500-256-80 256GB                 | 1         | 1      | 2.86%   |
| Apple HDD HTS545050A7E362 500GB                  | 1         | 1      | 2.86%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 10     | 28.57%  |
| Samsung Electronics | 8         | 8      | 22.86%  |
| Seagate             | 4         | 4      | 11.43%  |
| Hitachi             | 4         | 4      | 11.43%  |
| Apple               | 4         | 4      | 11.43%  |
| Toshiba             | 3         | 3      | 8.57%   |
| Intel               | 1         | 1      | 2.86%   |
| GOODRAM             | 1         | 1      | 2.86%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2754      | 4214   | 69.04%  |
| Malfunc  | 893       | 1016   | 22.39%  |
| Detected | 308       | 358    | 7.72%   |
| Failed   | 34        | 35     | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2417      | 57.36%  |
| AMD                              | 746       | 17.7%   |
| Samsung Electronics              | 208       | 4.94%   |
| SanDisk                          | 108       | 2.56%   |
| SK hynix                         | 88        | 2.09%   |
| Nvidia                           | 71        | 1.68%   |
| JMicron Technology               | 71        | 1.68%   |
| ASMedia Technology               | 68        | 1.61%   |
| Phison Electronics               | 60        | 1.42%   |
| Marvell Technology Group         | 58        | 1.38%   |
| Kingston Technology Company      | 53        | 1.26%   |
| Silicon Motion                   | 38        | 0.9%    |
| Micron/Crucial Technology        | 37        | 0.88%   |
| KIOXIA                           | 33        | 0.78%   |
| ADATA Technology                 | 26        | 0.62%   |
| Solid State Storage Technology   | 20        | 0.47%   |
| VIA Technologies                 | 16        | 0.38%   |
| Realtek Semiconductor            | 15        | 0.36%   |
| Micron Technology                | 15        | 0.36%   |
| Toshiba America Info Systems     | 14        | 0.33%   |
| Seagate Technology               | 8         | 0.19%   |
| Broadcom / LSI                   | 7         | 0.17%   |
| Union Memory (Shenzhen)          | 6         | 0.14%   |
| Lite-On Technology               | 6         | 0.14%   |
| Silicon Integrated Systems [SiS] | 5         | 0.12%   |
| Integrated Technology Express    | 5         | 0.12%   |
| Yangtze Memory Technologies      | 2         | 0.05%   |
| Silicon Image                    | 2         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.05%   |
| LSI Logic / Symbios Logic        | 2         | 0.05%   |
| Apple                            | 2         | 0.05%   |
| Unknown                          | 1         | 0.02%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 444       | 8.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 191       | 3.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 185       | 3.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 150       | 3.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 119       | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 108       | 2.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 106       | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 104       | 2.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 99        | 2%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 97        | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 95        | 1.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 93        | 1.87%   |
| AMD 400 Series Chipset SATA Controller                                                  | 92        | 1.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 89        | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 74        | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 74        | 1.49%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 67        | 1.35%   |
| Samsung NVMe SSD Controller 980                                                         | 65        | 1.31%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 64        | 1.29%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 63        | 1.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 62        | 1.25%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 62        | 1.25%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 62        | 1.25%   |
| AMD 500 Series Chipset SATA Controller                                                  | 61        | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 60        | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 60        | 1.21%   |
| Intel SATA Controller [RAID mode]                                                       | 59        | 1.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 55        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 55        | 1.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 54        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 51        | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 50        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 47        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 47        | 0.95%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 44        | 0.89%   |
| SK hynix Gold P31 SSD                                                                   | 42        | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 34        | 0.69%   |
| AMD FCH SATA Controller D                                                               | 34        | 0.69%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 33        | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 32        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2675      | 62.71%  |
| NVMe | 726       | 17.02%  |
| IDE  | 642       | 15.05%  |
| RAID | 214       | 5.02%   |
| SAS  | 7         | 0.16%   |
| SCSI | 2         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2595      | 74.85%  |
| AMD    | 872       | 25.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N6000 @ 1.10GHz          | 53        | 1.53%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 39        | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 30        | 0.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 30        | 0.87%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 29        | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 0.75%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 26        | 0.75%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 25        | 0.72%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 23        | 0.66%   |
| AMD Ryzen 5 3600 6-Core Processor             | 23        | 0.66%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 22        | 0.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 20        | 0.58%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 20        | 0.58%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 20        | 0.58%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 19        | 0.55%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 19        | 0.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 19        | 0.55%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 18        | 0.52%   |
| AMD FX-8350 Eight-Core Processor              | 18        | 0.52%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 17        | 0.49%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 17        | 0.49%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 17        | 0.49%   |
| AMD 3020e with Radeon Graphics                | 17        | 0.49%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 16        | 0.46%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 16        | 0.46%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 16        | 0.46%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 15        | 0.43%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 15        | 0.43%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 15        | 0.43%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 15        | 0.43%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 15        | 0.43%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 14        | 0.4%    |
| Intel Core i3-4130 CPU @ 3.40GHz              | 14        | 0.4%    |
| Intel Core i3-3220 CPU @ 3.30GHz              | 14        | 0.4%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 14        | 0.4%    |
| AMD FX-6300 Six-Core Processor                | 14        | 0.4%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.37%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 13        | 0.37%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 13        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 824       | 23.77%  |
| Intel Core i3           | 368       | 10.61%  |
| Intel Core i7           | 358       | 10.33%  |
| Intel Celeron           | 253       | 7.3%    |
| Intel Core 2 Duo        | 187       | 5.39%   |
| AMD Ryzen 5             | 159       | 4.59%   |
| Intel Pentium           | 135       | 3.89%   |
| AMD Ryzen 7             | 116       | 3.35%   |
| Other                   | 103       | 2.97%   |
| Intel Pentium Silver    | 96        | 2.77%   |
| AMD FX                  | 71        | 2.05%   |
| Intel Xeon              | 61        | 1.76%   |
| Intel Pentium Dual-Core | 60        | 1.73%   |
| AMD Ryzen 3             | 54        | 1.56%   |
| Intel Core 2 Quad       | 49        | 1.41%   |
| AMD A8                  | 42        | 1.21%   |
| AMD A6                  | 37        | 1.07%   |
| AMD A4                  | 33        | 0.95%   |
| AMD A10                 | 29        | 0.84%   |
| AMD E1                  | 28        | 0.81%   |
| AMD Athlon              | 28        | 0.81%   |
| Intel Pentium Dual      | 24        | 0.69%   |
| Intel Core 2            | 24        | 0.69%   |
| Intel Atom              | 24        | 0.69%   |
| AMD Athlon II X2        | 24        | 0.69%   |
| AMD Phenom II X4        | 23        | 0.66%   |
| AMD Ryzen 9             | 22        | 0.63%   |
| AMD Athlon 64 X2        | 21        | 0.61%   |
| AMD E                   | 19        | 0.55%   |
| Intel Core i9           | 16        | 0.46%   |
| AMD E2                  | 12        | 0.35%   |
| AMD Ryzen 5 PRO         | 11        | 0.32%   |
| Intel Genuine           | 10        | 0.29%   |
| AMD C-60                | 9         | 0.26%   |
| AMD Athlon X4           | 8         | 0.23%   |
| AMD Athlon II X4        | 8         | 0.23%   |
| Intel Pentium Gold      | 7         | 0.2%    |
| AMD Sempron             | 7         | 0.2%    |
| AMD Athlon II X3        | 7         | 0.2%    |
| Intel Pentium 4         | 6         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1736      | 50.07%  |
| 4      | 1115      | 32.16%  |
| 6      | 305       | 8.8%    |
| 8      | 161       | 4.64%   |
| 1      | 79        | 2.28%   |
| 3      | 31        | 0.89%   |
| 12     | 17        | 0.49%   |
| 16     | 12        | 0.35%   |
| 10     | 8         | 0.23%   |
| 14     | 2         | 0.06%   |
| 20     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 3455      | 99.65%  |
| 2      | 12        | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1894      | 54.63%  |
| 1      | 1564      | 45.11%  |
| 8      | 8         | 0.23%   |
| 4      | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3465      | 99.94%  |
| Unknown        | 2         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 276       | 7.96%   |
| 0x206a7    | 276       | 7.96%   |
| 0x306c3    | 229       | 6.61%   |
| 0x1067a    | 207       | 5.97%   |
| Unknown    | 91        | 2.62%   |
| 0x906ea    | 89        | 2.57%   |
| 0x20655    | 88        | 2.54%   |
| 0x506e3    | 81        | 2.34%   |
| 0x406e3    | 73        | 2.11%   |
| 0x306d4    | 70        | 2.02%   |
| 0x806e9    | 65        | 1.87%   |
| 0x6fd      | 62        | 1.79%   |
| 0x08108109 | 62        | 1.79%   |
| 0x906c0    | 61        | 1.76%   |
| 0x806ea    | 59        | 1.7%    |
| 0x08701021 | 59        | 1.7%    |
| 0x906e9    | 58        | 1.67%   |
| 0x706a8    | 58        | 1.67%   |
| 0x40651    | 58        | 1.67%   |
| 0x806ec    | 54        | 1.56%   |
| 0x30678    | 49        | 1.41%   |
| 0xa0655    | 44        | 1.27%   |
| 0x706a1    | 42        | 1.21%   |
| 0x10676    | 42        | 1.21%   |
| 0x20652    | 37        | 1.07%   |
| 0x0a50000c | 36        | 1.04%   |
| 0x010000c8 | 34        | 0.98%   |
| 0xa0653    | 33        | 0.95%   |
| 0x706e5    | 33        | 0.95%   |
| 0x506c9    | 33        | 0.95%   |
| 0x06001119 | 33        | 0.95%   |
| 0x6fb      | 32        | 0.92%   |
| 0x406c4    | 32        | 0.92%   |
| 0x0800820d | 32        | 0.92%   |
| 0x806c1    | 30        | 0.87%   |
| 0x08600106 | 26        | 0.75%   |
| 0x06006705 | 26        | 0.75%   |
| 0x106e5    | 25        | 0.72%   |
| 0x07030105 | 25        | 0.72%   |
| 0x06000822 | 25        | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 388       | 11.19%  |
| Haswell          | 298       | 8.6%    |
| SandyBridge      | 289       | 8.34%   |
| IvyBridge        | 287       | 8.28%   |
| Penryn           | 255       | 7.36%   |
| Skylake          | 162       | 4.67%   |
| Core             | 137       | 3.95%   |
| Westmere         | 133       | 3.84%   |
| Zen+             | 117       | 3.37%   |
| Zen 2            | 109       | 3.14%   |
| Silvermont       | 104       | 3%      |
| Goldmont plus    | 100       | 2.88%   |
| Piledriver       | 99        | 2.86%   |
| K10              | 94        | 2.71%   |
| CometLake        | 92        | 2.65%   |
| Zen 3            | 79        | 2.28%   |
| Broadwell        | 78        | 2.25%   |
| Zen              | 77        | 2.22%   |
| Tremont          | 61        | 1.76%   |
| Icelake          | 55        | 1.59%   |
| Excavator        | 52        | 1.5%    |
| Bobcat           | 42        | 1.21%   |
| K8 Hammer        | 41        | 1.18%   |
| Nehalem          | 40        | 1.15%   |
| Puma             | 37        | 1.07%   |
| Unknown          | 35        | 1.01%   |
| Goldmont         | 34        | 0.98%   |
| TigerLake        | 32        | 0.92%   |
| Steamroller      | 28        | 0.81%   |
| Jaguar           | 27        | 0.78%   |
| Bonnell          | 21        | 0.61%   |
| K10 Llano        | 20        | 0.58%   |
| Bulldozer        | 14        | 0.4%    |
| NetBurst         | 13        | 0.37%   |
| Alderlake Hybrid | 11        | 0.32%   |
| K8 & K10 hybrid  | 6         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1933      | 50.55%  |
| Nvidia                           | 940       | 24.58%  |
| AMD                              | 938       | 24.53%  |
| Silicon Integrated Systems [SiS] | 4         | 0.1%    |
| VIA Technologies                 | 3         | 0.08%   |
| Matrox Electronics Systems       | 3         | 0.08%   |
| ASPEED Technology                | 2         | 0.05%   |
| ATI Technologies                 | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 222       | 5.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 155       | 3.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 100       | 2.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 95        | 2.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 81        | 2.07%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 74        | 1.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 69        | 1.76%   |
| Intel JasperLake [UHD Graphics]                                                          | 61        | 1.56%   |
| Intel HD Graphics 5500                                                                   | 59        | 1.51%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 59        | 1.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 57        | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 57        | 1.46%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 55        | 1.4%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 53        | 1.35%   |
| Intel HD Graphics 620                                                                    | 53        | 1.35%   |
| Intel HD Graphics 530                                                                    | 52        | 1.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 51        | 1.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 50        | 1.28%   |
| Intel UHD Graphics 620                                                                   | 49        | 1.25%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 48        | 1.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 47        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 46        | 1.17%   |
| AMD Cezanne                                                                              | 44        | 1.12%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 42        | 1.07%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 41        | 1.05%   |
| AMD Renoir                                                                               | 41        | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 40        | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 35        | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 35        | 0.89%   |
| Intel HD Graphics 630                                                                    | 35        | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 34        | 0.87%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 31        | 0.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 30        | 0.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 29        | 0.74%   |
| AMD Lucienne                                                                             | 28        | 0.72%   |
| Nvidia GT218 [GeForce 210]                                                               | 27        | 0.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 27        | 0.69%   |
| Intel HD Graphics 500                                                                    | 26        | 0.66%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 25        | 0.64%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 24        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 1593      | 45.95%  |
| 1 x AMD                 | 817       | 23.57%  |
| 1 x Nvidia              | 668       | 19.27%  |
| Intel + Nvidia          | 250       | 7.21%   |
| Intel + AMD             | 58        | 1.67%   |
| 2 x AMD                 | 49        | 1.41%   |
| AMD + Nvidia            | 15        | 0.43%   |
| 2 x Nvidia              | 5         | 0.14%   |
| 1 x SiS                 | 4         | 0.12%   |
| 1 x VIA                 | 3         | 0.09%   |
| 1 x ASPEED              | 2         | 0.06%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.03%   |
| Nvidia + Matrox         | 1         | 0.03%   |
| 1 x Matrox              | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3377      | 97.4%   |
| Unknown     | 87        | 2.51%   |
| Proprietary | 3         | 0.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1713      | 49.41%  |
| 0.01-0.5   | 512       | 14.77%  |
| 1.01-2.0   | 457       | 13.18%  |
| 0.51-1.0   | 375       | 10.82%  |
| 3.01-4.0   | 182       | 5.25%   |
| 7.01-8.0   | 118       | 3.4%    |
| 5.01-6.0   | 63        | 1.82%   |
| 2.01-3.0   | 28        | 0.81%   |
| 8.01-16.0  | 16        | 0.46%   |
| 16.01-24.0 | 3         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 454       | 13%     |
| AU Optronics            | 387       | 11.08%  |
| LG Display              | 316       | 9.05%   |
| BOE                     | 273       | 7.82%   |
| Chimei Innolux          | 260       | 7.44%   |
| Goldstar                | 215       | 6.16%   |
| Dell                    | 186       | 5.32%   |
| Hewlett-Packard         | 177       | 5.07%   |
| Acer                    | 130       | 3.72%   |
| Philips                 | 119       | 3.41%   |
| AOC                     | 114       | 3.26%   |
| BenQ                    | 77        | 2.2%    |
| Lenovo                  | 75        | 2.15%   |
| Ancor Communications    | 63        | 1.8%    |
| Chi Mei Optoelectronics | 60        | 1.72%   |
| ViewSonic               | 52        | 1.49%   |
| Apple                   | 42        | 1.2%    |
| Iiyama                  | 33        | 0.94%   |
| Sony                    | 27        | 0.77%   |
| Sharp                   | 27        | 0.77%   |
| InfoVision              | 23        | 0.66%   |
| ASUSTek Computer        | 21        | 0.6%    |
| LG Philips              | 19        | 0.54%   |
| Eizo                    | 19        | 0.54%   |
| Toshiba                 | 17        | 0.49%   |
| NEC Computers           | 16        | 0.46%   |
| HannStar                | 15        | 0.43%   |
| Fujitsu Siemens         | 14        | 0.4%    |
| PANDA                   | 13        | 0.37%   |
| Unknown                 | 10        | 0.29%   |
| Sceptre Tech            | 10        | 0.29%   |
| Panasonic               | 10        | 0.29%   |
| ___                     | 8         | 0.23%   |
| Vestel Elektronik       | 8         | 0.23%   |
| Hitachi                 | 8         | 0.23%   |
| Vizio                   | 7         | 0.2%    |
| MSI                     | 7         | 0.2%    |
| CPT                     | 7         | 0.2%    |
| TCL                     | 6         | 0.17%   |
| MiTAC                   | 5         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                     | 32        | 0.91%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                         | 22        | 0.62%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch           | 20        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 17        | 0.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 14        | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 14        | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 14        | 0.4%    |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 13        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 13        | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.37%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 13        | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 0.34%   |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch            | 12        | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 11        | 0.31%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.31%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.31%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                     | 10        | 0.28%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 10        | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 10        | 0.28%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                          | 10        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 9         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 9         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 9         | 0.26%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 9         | 0.26%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch       | 8         | 0.23%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 8         | 0.23%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 8         | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 8         | 0.23%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 8         | 0.23%   |
| BOE LCD Monitor BOE097B 1366x768 256x144mm 11.6-inch                     | 8         | 0.23%   |
| BOE LCD Monitor BOE07B9 1920x1080 293x165mm 13.2-inch                    | 8         | 0.23%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 7         | 0.2%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 7         | 0.2%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 7         | 0.2%    |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 7         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1351      | 39.45%  |
| 1366x768 (WXGA)    | 937       | 27.36%  |
| 3840x2160 (4K)     | 178       | 5.2%    |
| 1600x900 (HD+)     | 174       | 5.08%   |
| 1280x1024 (SXGA)   | 139       | 4.06%   |
| 2560x1440 (QHD)    | 121       | 3.53%   |
| 1440x900 (WXGA+)   | 102       | 2.98%   |
| 1680x1050 (WSXGA+) | 100       | 2.92%   |
| 1280x800 (WXGA)    | 87        | 2.54%   |
| 1920x1200 (WUXGA)  | 65        | 1.9%    |
| 1360x768           | 30        | 0.88%   |
| 3440x1440          | 24        | 0.7%    |
| 2560x1080          | 22        | 0.64%   |
| 1920x540           | 12        | 0.35%   |
| 1024x768 (XGA)     | 12        | 0.35%   |
| 2560x1600          | 8         | 0.23%   |
| 3200x1800 (QHD+)   | 7         | 0.2%    |
| 2160x1440          | 6         | 0.18%   |
| 1600x1200          | 6         | 0.18%   |
| 1280x720 (HD)      | 6         | 0.18%   |
| 2288x1287          | 4         | 0.12%   |
| 1920x1280          | 4         | 0.12%   |
| 1024x600           | 4         | 0.12%   |
| 2880x1800          | 3         | 0.09%   |
| 2736x1824          | 3         | 0.09%   |
| 2048x1152          | 3         | 0.09%   |
| 1280x960           | 3         | 0.09%   |
| 3840x1080          | 2         | 0.06%   |
| 2256x1504          | 2         | 0.06%   |
| 1680x945           | 2         | 0.06%   |
| 3840x2400          | 1         | 0.03%   |
| 3840x1600          | 1         | 0.03%   |
| 3840x1200          | 1         | 0.03%   |
| 3456x2160          | 1         | 0.03%   |
| 3200x2000          | 1         | 0.03%   |
| 1400x1050          | 1         | 0.03%   |
| 1280x768           | 1         | 0.03%   |
| Unknown            | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 781       | 22.35%  |
| 13      | 303       | 8.67%   |
| 27      | 271       | 7.76%   |
| 23      | 270       | 7.73%   |
| 21      | 256       | 7.33%   |
| 17      | 228       | 6.53%   |
| 24      | 217       | 6.21%   |
| 14      | 186       | 5.32%   |
| 19      | 147       | 4.21%   |
| 11      | 129       | 3.69%   |
| 18      | 104       | 2.98%   |
| 31      | 84        | 2.4%    |
| 12      | 79        | 2.26%   |
| 22      | 74        | 2.12%   |
| 20      | 61        | 1.75%   |
| 34      | 42        | 1.2%    |
| 84      | 37        | 1.06%   |
| 32      | 26        | 0.74%   |
| Unknown | 21        | 0.6%    |
| 72      | 18        | 0.52%   |
| 54      | 16        | 0.46%   |
| 26      | 16        | 0.46%   |
| 65      | 12        | 0.34%   |
| 40      | 12        | 0.34%   |
| 25      | 12        | 0.34%   |
| 16      | 11        | 0.31%   |
| 10      | 8         | 0.23%   |
| 52      | 7         | 0.2%    |
| 39      | 7         | 0.2%    |
| 33      | 6         | 0.17%   |
| 74      | 5         | 0.14%   |
| 48      | 5         | 0.14%   |
| 46      | 5         | 0.14%   |
| 142     | 4         | 0.11%   |
| 47      | 4         | 0.11%   |
| 29      | 4         | 0.11%   |
| 28      | 4         | 0.11%   |
| 43      | 3         | 0.09%   |
| 42      | 3         | 0.09%   |
| 37      | 3         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1172      | 33.8%   |
| 501-600        | 739       | 21.32%  |
| 401-500        | 568       | 16.38%  |
| 201-300        | 362       | 10.44%  |
| 351-400        | 265       | 7.64%   |
| 601-700        | 114       | 3.29%   |
| 701-800        | 74        | 2.13%   |
| 1501-2000      | 60        | 1.73%   |
| 1001-1500      | 58        | 1.67%   |
| 801-900        | 25        | 0.72%   |
| Unknown        | 21        | 0.61%   |
| 901-1000       | 5         | 0.14%   |
| More than 2000 | 4         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2699      | 80.93%  |
| 16/10   | 388       | 11.63%  |
| 5/4     | 134       | 4.02%   |
| 21/9    | 44        | 1.32%   |
| 4/3     | 32        | 0.96%   |
| 3/2     | 26        | 0.78%   |
| 1.00    | 4         | 0.12%   |
| 6/5     | 3         | 0.09%   |
| 32/9    | 2         | 0.06%   |
| 3.20    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 777       | 22.37%  |
| 201-250        | 656       | 18.89%  |
| 81-90          | 360       | 10.37%  |
| 301-350        | 285       | 8.21%   |
| 151-200        | 285       | 8.21%   |
| 351-500        | 161       | 4.64%   |
| 141-150        | 154       | 4.43%   |
| 71-80          | 137       | 3.94%   |
| 121-130        | 134       | 3.86%   |
| 51-60          | 129       | 3.71%   |
| More than 1000 | 109       | 3.14%   |
| 251-300        | 98        | 2.82%   |
| 61-70          | 70        | 2.02%   |
| 501-1000       | 45        | 1.3%    |
| 131-140        | 28        | 0.81%   |
| Unknown        | 21        | 0.6%    |
| 111-120        | 10        | 0.29%   |
| 41-50          | 8         | 0.23%   |
| 91-100         | 6         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1388      | 40.5%   |
| 101-120       | 1077      | 31.43%  |
| 121-160       | 698       | 20.37%  |
| 161-240       | 131       | 3.82%   |
| 1-50          | 91        | 2.66%   |
| More than 240 | 21        | 0.61%   |
| Unknown       | 21        | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3151      | 90.89%  |
| 2     | 258       | 7.44%   |
| 0     | 40        | 1.15%   |
| 3     | 16        | 0.46%   |
| 7     | 1         | 0.03%   |
| 4     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2037      | 40.59%  |
| Intel                             | 1482      | 29.53%  |
| Qualcomm Atheros                  | 635       | 12.65%  |
| Broadcom                          | 229       | 4.56%   |
| Ralink Technology                 | 74        | 1.47%   |
| Ralink                            | 69        | 1.38%   |
| Marvell Technology Group          | 65        | 1.3%    |
| Nvidia                            | 54        | 1.08%   |
| Broadcom Limited                  | 48        | 0.96%   |
| TP-Link                           | 39        | 0.78%   |
| MediaTek                          | 24        | 0.48%   |
| Qualcomm Atheros Communications   | 16        | 0.32%   |
| Ericsson Business Mobile Networks | 16        | 0.32%   |
| Samsung Electronics               | 15        | 0.3%    |
| Huawei Technologies               | 15        | 0.3%    |
| Dell                              | 15        | 0.3%    |
| JMicron Technology                | 14        | 0.28%   |
| D-Link System                     | 13        | 0.26%   |
| NetGear                           | 11        | 0.22%   |
| Motorola PCS                      | 11        | 0.22%   |
| D-Link                            | 11        | 0.22%   |
| ASIX Electronics                  | 10        | 0.2%    |
| Sierra Wireless                   | 9         | 0.18%   |
| VIA Technologies                  | 8         | 0.16%   |
| Microsoft                         | 7         | 0.14%   |
| Hewlett-Packard                   | 7         | 0.14%   |
| Aquantia                          | 7         | 0.14%   |
| Xiaomi                            | 5         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 5         | 0.1%    |
| ASUSTek Computer                  | 5         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 4         | 0.08%   |
| Edimax Technology                 | 4         | 0.08%   |
| DisplayLink                       | 4         | 0.08%   |
| AVM                               | 4         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.06%   |
| Linksys                           | 3         | 0.06%   |
| Google                            | 3         | 0.06%   |
| Belkin Components                 | 3         | 0.06%   |
| T & A Mobile Phones               | 2         | 0.04%   |
| Spreadtrum Communications         | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1449      | 24.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 265       | 4.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 148       | 2.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 100       | 1.72%   |
| Intel Wi-Fi 6 AX200                                               | 88        | 1.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 87        | 1.5%    |
| Intel Wireless 8265 / 8275                                        | 85        | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 84        | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 82        | 1.41%   |
| Intel Wireless 7265                                               | 77        | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 74        | 1.27%   |
| Intel Ethernet Connection I217-LM                                 | 66        | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 63        | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 60        | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 57        | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 57        | 0.98%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 56        | 0.96%   |
| Intel Wireless 3165                                               | 53        | 0.91%   |
| Intel I211 Gigabit Network Connection                             | 53        | 0.91%   |
| Intel Wireless 7260                                               | 51        | 0.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 49        | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 49        | 0.84%   |
| Intel 82579V Gigabit Network Connection                           | 49        | 0.84%   |
| Intel Wireless 8260                                               | 46        | 0.79%   |
| Intel Ethernet Connection (2) I219-V                              | 44        | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 43        | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 42        | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 40        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 36        | 0.62%   |
| Intel Wireless 3160                                               | 35        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 32        | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 32        | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 31        | 0.53%   |
| Intel Ethernet Connection (7) I219-V                              | 31        | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 29        | 0.5%    |
| Intel Ethernet Controller I225-V                                  | 28        | 0.48%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 27        | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25        | 0.43%   |
| Nvidia MCP61 Ethernet                                             | 25        | 0.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1032      | 41.65%  |
| Qualcomm Atheros                      | 508       | 20.5%   |
| Realtek Semiconductor                 | 475       | 19.17%  |
| Broadcom                              | 143       | 5.77%   |
| Ralink Technology                     | 74        | 2.99%   |
| Ralink                                | 69        | 2.78%   |
| TP-Link                               | 28        | 1.13%   |
| Broadcom Limited                      | 23        | 0.93%   |
| MediaTek                              | 22        | 0.89%   |
| Qualcomm Atheros Communications       | 16        | 0.65%   |
| D-Link                                | 11        | 0.44%   |
| Sierra Wireless                       | 9         | 0.36%   |
| NetGear                               | 9         | 0.36%   |
| Dell                                  | 8         | 0.32%   |
| Microsoft                             | 7         | 0.28%   |
| D-Link System                         | 6         | 0.24%   |
| ASUSTek Computer                      | 5         | 0.2%    |
| Marvell Technology Group              | 4         | 0.16%   |
| Edimax Technology                     | 4         | 0.16%   |
| AVM                                   | 4         | 0.16%   |
| Linksys                               | 3         | 0.12%   |
| Hewlett-Packard                       | 3         | 0.12%   |
| Ericsson Business Mobile Networks     | 3         | 0.12%   |
| Belkin Components                     | 3         | 0.12%   |
| IMC Networks                          | 2         | 0.08%   |
| Chu Yuen Enterprise                   | 2         | 0.08%   |
| ZyDAS                                 | 1         | 0.04%   |
| Sitecom Europe                        | 1         | 0.04%   |
| Logitec                               | 1         | 0.04%   |
| Guillemot                             | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 100       | 4.03%   |
| Intel Wi-Fi 6 AX200                                            | 88        | 3.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 87        | 3.5%    |
| Intel Wireless 8265 / 8275                                     | 85        | 3.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 84        | 3.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 82        | 3.3%    |
| Intel Wireless 7265                                            | 77        | 3.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 74        | 2.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 60        | 2.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 57        | 2.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 57        | 2.29%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 56        | 2.25%   |
| Intel Wireless 3165                                            | 53        | 2.13%   |
| Intel Wireless 7260                                            | 51        | 2.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 49        | 1.97%   |
| Intel Wireless 8260                                            | 46        | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 43        | 1.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 42        | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 40        | 1.61%   |
| Intel Wireless 3160                                            | 35        | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 32        | 1.29%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 32        | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 31        | 1.25%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 27        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 1.01%   |
| Ralink MT7601U Wireless Adapter                                | 24        | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 24        | 0.97%   |
| Intel Centrino Wireless-N 2230                                 | 23        | 0.93%   |
| Intel WiFi Link 5100                                           | 22        | 0.89%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 22        | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 22        | 0.89%   |
| Intel Centrino Ultimate-N 6300                                 | 22        | 0.89%   |
| Realtek 802.11ac NIC                                           | 21        | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 21        | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 21        | 0.85%   |
| Intel Wireless-AC 9260                                         | 21        | 0.85%   |
| Intel Wi-Fi 6 AX201                                            | 21        | 0.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 19        | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 18        | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 18        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1850      | 57.31%  |
| Intel                             | 783       | 24.26%  |
| Qualcomm Atheros                  | 192       | 5.95%   |
| Broadcom                          | 124       | 3.84%   |
| Marvell Technology Group          | 61        | 1.89%   |
| Nvidia                            | 54        | 1.67%   |
| Broadcom Limited                  | 25        | 0.77%   |
| Samsung Electronics               | 15        | 0.46%   |
| JMicron Technology                | 14        | 0.43%   |
| TP-Link                           | 11        | 0.34%   |
| Huawei Technologies               | 11        | 0.34%   |
| ASIX Electronics                  | 10        | 0.31%   |
| VIA Technologies                  | 8         | 0.25%   |
| D-Link System                     | 7         | 0.22%   |
| Aquantia                          | 7         | 0.22%   |
| Motorola PCS                      | 6         | 0.19%   |
| Xiaomi                            | 5         | 0.15%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.15%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.12%   |
| DisplayLink                       | 4         | 0.12%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.09%   |
| Hewlett-Packard                   | 3         | 0.09%   |
| Google                            | 3         | 0.09%   |
| T & A Mobile Phones               | 2         | 0.06%   |
| Spreadtrum Communications         | 2         | 0.06%   |
| Qualcomm                          | 2         | 0.06%   |
| OPPO Electronics                  | 2         | 0.06%   |
| NetGear                           | 2         | 0.06%   |
| MediaTek                          | 2         | 0.06%   |
| HTC (High Tech Computer)          | 2         | 0.06%   |
| 3Com                              | 2         | 0.06%   |
| Sundance Technology Inc / IC Plus | 1         | 0.03%   |
| Netchip Technology                | 1         | 0.03%   |
| Mellanox Technologies             | 1         | 0.03%   |
| Lenovo                            | 1         | 0.03%   |
| ICS Advent                        | 1         | 0.03%   |
| Emulex                            | 1         | 0.03%   |
| Adnaco Technology                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1449      | 44%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 265       | 8.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 148       | 4.49%   |
| Intel Ethernet Connection I217-LM                                              | 66        | 2%      |
| Realtek RTL8125 2.5GbE Controller                                              | 63        | 1.91%   |
| Intel I211 Gigabit Network Connection                                          | 53        | 1.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 49        | 1.49%   |
| Intel 82579V Gigabit Network Connection                                        | 49        | 1.49%   |
| Intel Ethernet Connection (2) I219-V                                           | 44        | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 36        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                                           | 31        | 0.94%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 29        | 0.88%   |
| Intel Ethernet Controller I225-V                                               | 28        | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 25        | 0.76%   |
| Nvidia MCP61 Ethernet                                                          | 25        | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 24        | 0.73%   |
| Intel Ethernet Connection I217-V                                               | 23        | 0.7%    |
| Intel 82577LM Gigabit Network Connection                                       | 20        | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 19        | 0.58%   |
| Intel Ethernet Connection I219-LM                                              | 19        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                                          | 19        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                                          | 18        | 0.55%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 0.52%   |
| Intel 82567LM Gigabit Network Connection                                       | 17        | 0.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 17        | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 16        | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 14        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 13        | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 13        | 0.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 13        | 0.39%   |
| Nvidia MCP79 Ethernet                                                          | 12        | 0.36%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 12        | 0.36%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 12        | 0.36%   |
| Intel Ethernet Connection (2) I218-V                                           | 12        | 0.36%   |
| Intel 82578DM Gigabit Network Connection                                       | 12        | 0.36%   |
| Intel 82574L Gigabit Network Connection                                        | 12        | 0.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 11        | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 11        | 0.33%   |
| Intel 82566MM Gigabit Network Connection                                       | 11        | 0.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 11        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3088      | 55.97%  |
| WiFi     | 2392      | 43.36%  |
| Modem    | 28        | 0.51%   |
| Unknown  | 9         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1886      | 55.47%  |
| WiFi     | 1514      | 44.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1805      | 52.06%  |
| 1     | 1573      | 45.37%  |
| 3     | 54        | 1.56%   |
| 0     | 29        | 0.84%   |
| 4     | 5         | 0.14%   |
| 5     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2481      | 71.56%  |
| Yes  | 986       | 28.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 781       | 43.22%  |
| Realtek Semiconductor           | 187       | 10.35%  |
| Qualcomm Atheros Communications | 162       | 8.97%   |
| Broadcom                        | 120       | 6.64%   |
| Cambridge Silicon Radio         | 113       | 6.25%   |
| Lite-On Technology              | 83        | 4.59%   |
| IMC Networks                    | 73        | 4.04%   |
| Foxconn / Hon Hai               | 52        | 2.88%   |
| Apple                           | 47        | 2.6%    |
| Dell                            | 34        | 1.88%   |
| ASUSTek Computer                | 29        | 1.6%    |
| Toshiba                         | 28        | 1.55%   |
| Ralink                          | 21        | 1.16%   |
| Hewlett-Packard                 | 21        | 1.16%   |
| Realtek                         | 6         | 0.33%   |
| Ralink Technology               | 6         | 0.33%   |
| Alps Electric                   | 6         | 0.33%   |
| MediaTek                        | 5         | 0.28%   |
| Marvell Semiconductor           | 4         | 0.22%   |
| Fujitsu                         | 3         | 0.17%   |
| Foxconn International           | 3         | 0.17%   |
| Edimax Technology               | 3         | 0.17%   |
| Unknown                         | 3         | 0.17%   |
| TP-Link                         | 2         | 0.11%   |
| Chicony Electronics             | 2         | 0.11%   |
| Belkin Components               | 2         | 0.11%   |
| Askey Computer                  | 2         | 0.11%   |
| USI                             | 1         | 0.06%   |
| Unknown                         | 1         | 0.06%   |
| Taiyo Yuden                     | 1         | 0.06%   |
| SINO WEALTH                     | 1         | 0.06%   |
| Primax Electronics              | 1         | 0.06%   |
| Opticis                         | 1         | 0.06%   |
| Integrated System Solution      | 1         | 0.06%   |
| Dynex                           | 1         | 0.06%   |
| D-Link System                   | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 350       | 19.37%  |
| Realtek Bluetooth Radio                                                             | 117       | 6.47%   |
| Intel AX201 Bluetooth                                                               | 113       | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 113       | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 101       | 5.59%   |
| Intel AX200 Bluetooth                                                               | 87        | 4.81%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 68        | 3.76%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 58        | 3.21%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 46        | 2.55%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 33        | 1.83%   |
| IMC Networks Bluetooth Radio                                                        | 33        | 1.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 28        | 1.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 27        | 1.49%   |
| IMC Networks Bluetooth Device                                                       | 27        | 1.49%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 25        | 1.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 25        | 1.38%   |
| Lite-On Bluetooth Device                                                            | 24        | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 23        | 1.27%   |
| Ralink RT3290 Bluetooth                                                             | 21        | 1.16%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 20        | 1.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 20        | 1.11%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 20        | 1.11%   |
| Dell DW375 Bluetooth Module                                                         | 17        | 0.94%   |
| Apple Bluetooth Host Controller                                                     | 17        | 0.94%   |
| Intel AX210 Bluetooth                                                               | 16        | 0.89%   |
| Apple Bluetooth USB Host Controller                                                 | 16        | 0.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 15        | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 15        | 0.83%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 11        | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 11        | 0.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 11        | 0.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 10        | 0.55%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 9         | 0.5%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 9         | 0.5%    |
| Broadcom BCM2045 Bluetooth                                                          | 9         | 0.5%    |
| Toshiba RT Bluetooth Radio                                                          | 8         | 0.44%   |
| Realtek RTL8723B Bluetooth                                                          | 8         | 0.44%   |
| Broadcom HP Portable SoftSailing                                                    | 8         | 0.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 8         | 0.44%   |
| ASUS ASUS USB-BT500                                                                 | 8         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2530      | 54.5%   |
| AMD                                          | 1048      | 22.58%  |
| Nvidia                                       | 737       | 15.88%  |
| C-Media Electronics                          | 65        | 1.4%    |
| Creative Labs                                | 44        | 0.95%   |
| Logitech                                     | 33        | 0.71%   |
| Texas Instruments                            | 17        | 0.37%   |
| JMTek                                        | 14        | 0.3%    |
| Creative Technology                          | 14        | 0.3%    |
| Generalplus Technology                       | 11        | 0.24%   |
| ASUSTek Computer                             | 8         | 0.17%   |
| GN Netcom                                    | 7         | 0.15%   |
| XMOS                                         | 5         | 0.11%   |
| VIA Technologies                             | 5         | 0.11%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.11%   |
| Realtek Semiconductor                        | 4         | 0.09%   |
| Plantronics                                  | 4         | 0.09%   |
| Blue Microphones                             | 4         | 0.09%   |
| Tenx Technology                              | 3         | 0.06%   |
| Sony                                         | 3         | 0.06%   |
| Samson Technologies                          | 3         | 0.06%   |
| Razer USA                                    | 3         | 0.06%   |
| Kingston Technology                          | 3         | 0.06%   |
| Focusrite-Novation                           | 3         | 0.06%   |
| Apple                                        | 3         | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.04%   |
| Trust                                        | 2         | 0.04%   |
| SteelSeries ApS                              | 2         | 0.04%   |
| ROCCAT                                       | 2         | 0.04%   |
| PreSonus Audio Electronics                   | 2         | 0.04%   |
| No brand                                     | 2         | 0.04%   |
| Lenovo                                       | 2         | 0.04%   |
| Hewlett-Packard                              | 2         | 0.04%   |
| GYROCOM C&C                                  | 2         | 0.04%   |
| FiiO Electronics Technology                  | 2         | 0.04%   |
| ESS Technology                               | 2         | 0.04%   |
| Corsair                                      | 2         | 0.04%   |
| Conexant Systems                             | 2         | 0.04%   |
| BEHRINGER International                      | 2         | 0.04%   |
| Audient                                      | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 295       | 5.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 266       | 4.79%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 250       | 4.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 205       | 3.69%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 195       | 3.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 183       | 3.3%    |
| AMD FCH Azalia Controller                                                                         | 170       | 3.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 160       | 2.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 148       | 2.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 137       | 2.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 121       | 2.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 108       | 1.95%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 108       | 1.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 99        | 1.78%   |
| Intel Cannon Lake PCH cAVS                                                                        | 95        | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 95        | 1.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 88        | 1.59%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 88        | 1.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 77        | 1.39%   |
| Intel Broadwell-U Audio Controller                                                                | 74        | 1.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 73        | 1.32%   |
| AMD Kabini HDMI/DP Audio                                                                          | 73        | 1.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 72        | 1.3%    |
| Intel 200 Series PCH HD Audio                                                                     | 71        | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 65        | 1.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 63        | 1.14%   |
| Intel Jasper Lake HD Audio                                                                        | 61        | 1.1%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 58        | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 58        | 1.05%   |
| Intel 8 Series HD Audio Controller                                                                | 58        | 1.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 57        | 1.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 56        | 1.01%   |
| Nvidia High Definition Audio Controller                                                           | 54        | 0.97%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 52        | 0.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 50        | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 49        | 0.88%   |
| Intel Audio device                                                                                | 48        | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 43        | 0.77%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 38        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 37        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 762       | 18.53%  |
| SK hynix            | 666       | 16.2%   |
| Unknown             | 520       | 12.65%  |
| Kingston            | 509       | 12.38%  |
| Micron Technology   | 354       | 8.61%   |
| Crucial             | 208       | 5.06%   |
| Corsair             | 173       | 4.21%   |
| G.Skill             | 141       | 3.43%   |
| A-DATA Technology   | 96        | 2.33%   |
| Ramaxel Technology  | 77        | 1.87%   |
| Elpida              | 64        | 1.56%   |
| Smart               | 50        | 1.22%   |
| Unknown             | 50        | 1.22%   |
| Nanya Technology    | 48        | 1.17%   |
| Patriot             | 40        | 0.97%   |
| Unknown (ABCD)      | 37        | 0.9%    |
| Team                | 33        | 0.8%    |
| GOODRAM             | 18        | 0.44%   |
| Transcend           | 16        | 0.39%   |
| Teikon              | 15        | 0.36%   |
| AMD                 | 14        | 0.34%   |
| Qimonda             | 10        | 0.24%   |
| ASint Technology    | 10        | 0.24%   |
| CSX                 | 9         | 0.22%   |
| Apacer              | 9         | 0.22%   |
| Silicon Power       | 8         | 0.19%   |
| PNY                 | 8         | 0.19%   |
| Unifosa             | 7         | 0.17%   |
| Kingmax             | 7         | 0.17%   |
| Smart Brazil        | 6         | 0.15%   |
| Goldkey             | 6         | 0.15%   |
| GeIL                | 6         | 0.15%   |
| Toshiba             | 5         | 0.12%   |
| Multilaser          | 5         | 0.12%   |
| Avant               | 5         | 0.12%   |
| OM Nanotech         | 4         | 0.1%    |
| KLEVV               | 4         | 0.1%    |
| High Bridge         | 4         | 0.1%    |
| Super Talent        | 3         | 0.07%   |
| Sesame              | 3         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 50        | 1.12%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 46        | 1.03%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 43        | 0.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 43        | 0.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 41        | 0.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 40        | 0.9%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 37        | 0.83%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 35        | 0.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 27        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 26        | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 26        | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 25        | 0.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 25        | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 24        | 0.54%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 22        | 0.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 22        | 0.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 22        | 0.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 21        | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 21        | 0.47%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 19        | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 18        | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.4%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.4%    |
| Micron RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s             | 18        | 0.4%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 17        | 0.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 17        | 0.38%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                         | 17        | 0.38%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s            | 17        | 0.38%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.36%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 16        | 0.36%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 16        | 0.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.36%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 16        | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 15        | 0.34%   |
| SK hynix RAM 0000000000-00000 4GB SODIMM DDR4 2400MT/s           | 15        | 0.34%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 15        | 0.34%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 15        | 0.34%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s              | 15        | 0.34%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 14        | 0.31%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 14        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 1522      | 43.64%  |
| DDR4    | 1210      | 34.69%  |
| DDR2    | 267       | 7.65%   |
| Unknown | 152       | 4.36%   |
| SDRAM   | 141       | 4.04%   |
| LPDDR4  | 126       | 3.61%   |
| LPDDR3  | 31        | 0.89%   |
| DDR     | 26        | 0.75%   |
| DRAM    | 11        | 0.32%   |
| DDR5    | 2         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1798      | 52.18%  |
| DIMM         | 1506      | 43.7%   |
| Row Of Chips | 124       | 3.6%    |
| Chip         | 11        | 0.32%   |
| Unknown      | 4         | 0.12%   |
| RIMM         | 2         | 0.06%   |
| FB-DIMM      | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1446      | 37.52%  |
| 8192  | 1172      | 30.41%  |
| 2048  | 741       | 19.23%  |
| 16384 | 248       | 6.43%   |
| 1024  | 181       | 4.7%    |
| 32768 | 49        | 1.27%   |
| 512   | 17        | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 970       | 25.19%  |
| 1333    | 381       | 9.89%   |
| 2667    | 380       | 9.87%   |
| 2400    | 302       | 7.84%   |
| 3200    | 301       | 7.82%   |
| 1334    | 161       | 4.18%   |
| 800     | 150       | 3.9%    |
| 667     | 136       | 3.53%   |
| 2133    | 128       | 3.32%   |
| Unknown | 107       | 2.78%   |
| 3600    | 95        | 2.47%   |
| 1867    | 79        | 2.05%   |
| 1067    | 77        | 2%      |
| 4267    | 58        | 1.51%   |
| 2666    | 50        | 1.3%    |
| 1866    | 45        | 1.17%   |
| 1066    | 39        | 1.01%   |
| 3266    | 28        | 0.73%   |
| 533     | 27        | 0.7%    |
| 3466    | 26        | 0.68%   |
| 2048    | 26        | 0.68%   |
| 2933    | 25        | 0.65%   |
| 3000    | 24        | 0.62%   |
| 4199    | 23        | 0.6%    |
| 1800    | 19        | 0.49%   |
| 400     | 17        | 0.44%   |
| 975     | 16        | 0.42%   |
| 3400    | 13        | 0.34%   |
| 333     | 11        | 0.29%   |
| 8400    | 10        | 0.26%   |
| 3733    | 10        | 0.26%   |
| 4266    | 9         | 0.23%   |
| 2800    | 8         | 0.21%   |
| 1639    | 8         | 0.21%   |
| 1400    | 8         | 0.21%   |
| 3066    | 7         | 0.18%   |
| 4800    | 5         | 0.13%   |
| 3800    | 5         | 0.13%   |
| 2000    | 5         | 0.13%   |
| 49926   | 4         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 51        | 41.46%  |
| Brother Industries    | 28        | 22.76%  |
| Canon                 | 16        | 13.01%  |
| Samsung Electronics   | 9         | 7.32%   |
| Seiko Epson           | 8         | 6.5%    |
| Lexmark International | 4         | 3.25%   |
| Xerox                 | 2         | 1.63%   |
| Kyocera               | 2         | 1.63%   |
| Ricoh                 | 1         | 0.81%   |
| QinHeng Electronics   | 1         | 0.81%   |
| NXP Semiconductors    | 1         | 0.81%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Brother DCP-7055W                            | 4         | 3.25%   |
| HP LaserJet 1010                             | 3         | 2.44%   |
| Seiko Epson ET-4760 Series                   | 2         | 1.63%   |
| Samsung SCX-3400 Series                      | 2         | 1.63%   |
| Samsung M2070 Series                         | 2         | 1.63%   |
| Samsung M2020 Series                         | 2         | 1.63%   |
| HP LaserJet 1200                             | 2         | 1.63%   |
| HP LaserJet 1020                             | 2         | 1.63%   |
| HP LaserJet 1018                             | 2         | 1.63%   |
| HP Ink Tank Wireless 410 series              | 2         | 1.63%   |
| HP ENVY 4520 series                          | 2         | 1.63%   |
| HP ENVY 4500 series                          | 2         | 1.63%   |
| HP Deskjet 1050 J410                         | 2         | 1.63%   |
| Brother MFC-L2710DW series                   | 2         | 1.63%   |
| Brother MFC-J470DW                           | 2         | 1.63%   |
| Xerox Phaser 6510                            | 1         | 0.81%   |
| Xerox Phaser 6010N                           | 1         | 0.81%   |
| Seiko Epson XP-2100 Series                   | 1         | 0.81%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.81%   |
| Seiko Epson L365 Series                      | 1         | 0.81%   |
| Seiko Epson L3210 Series                     | 1         | 0.81%   |
| Seiko Epson L120 Series                      | 1         | 0.81%   |
| Seiko Epson ET-3750 Series                   | 1         | 0.81%   |
| Samsung ML-2850 Series                       | 1         | 0.81%   |
| Samsung M267x 287x Series                    | 1         | 0.81%   |
| Samsung CLP-310 Color Laser Printer          | 1         | 0.81%   |
| Ricoh SP 211                                 | 1         | 0.81%   |
| QinHeng CH340S                               | 1         | 0.81%   |
| NXP Semiconductors Printer-80                | 1         | 0.81%   |
| Lexmark International X364dn                 | 1         | 0.81%   |
| Lexmark International MS710                  | 1         | 0.81%   |
| Lexmark International CX410de                | 1         | 0.81%   |
| Lexmark International B2236dw                | 1         | 0.81%   |
| Kyocera ECOSYS P5021cdw                      | 1         | 0.81%   |
| Kyocera ECOSYS P2040dw                       | 1         | 0.81%   |
| HP PSC 1400                                  | 1         | 0.81%   |
| HP PhotoSmart P1000                          | 1         | 0.81%   |
| HP Officejet Pro 8100                        | 1         | 0.81%   |
| HP OfficeJet Pro 7740 series                 | 1         | 0.81%   |
| HP OfficeJet Pro 69                          | 1         | 0.81%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 13        | 68.42%  |
| Seiko Epson     | 3         | 15.79%  |
| Mustek Systems  | 2         | 10.53%  |
| Hewlett-Packard | 1         | 5.26%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                  | 3         | 15.79%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2         | 10.53%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 10.53%  |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 10.53%  |
| Canon CanoScan LiDE 100                                  | 2         | 10.53%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 5.26%   |
| Mustek Systems SNAPSCAN e22                              | 1         | 5.26%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 5.26%   |
| HP ScanJet 2400c                                         | 1         | 5.26%   |
| Canon CanoScan LiDE 600F                                 | 1         | 5.26%   |
| Canon CanoScan LiDE 210                                  | 1         | 5.26%   |
| Canon CanoScan LiDE 120                                  | 1         | 5.26%   |
| Canon CanoScan 5200F                                     | 1         | 5.26%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 399       | 21.63%  |
| Realtek Semiconductor                  | 222       | 12.03%  |
| Microdia                               | 205       | 11.11%  |
| IMC Networks                           | 106       | 5.75%   |
| Sunplus Innovation Technology          | 105       | 5.69%   |
| Logitech                               | 98        | 5.31%   |
| Acer                                   | 94        | 5.09%   |
| Cheng Uei Precision Industry (Foxlink) | 70        | 3.79%   |
| Suyin                                  | 66        | 3.58%   |
| Quanta                                 | 66        | 3.58%   |
| Syntek                                 | 52        | 2.82%   |
| Lite-On Technology                     | 41        | 2.22%   |
| Apple                                  | 41        | 2.22%   |
| Silicon Motion                         | 32        | 1.73%   |
| Ricoh                                  | 27        | 1.46%   |
| Alcor Micro                            | 26        | 1.41%   |
| ALi                                    | 17        | 0.92%   |
| Microsoft                              | 16        | 0.87%   |
| Lenovo                                 | 13        | 0.7%    |
| Importek                               | 13        | 0.7%    |
| Z-Star Microelectronics                | 12        | 0.65%   |
| Luxvisions Innotech Limited            | 12        | 0.65%   |
| Sonix Technology                       | 9         | 0.49%   |
| Primax Electronics                     | 9         | 0.49%   |
| Generalplus Technology                 | 8         | 0.43%   |
| Sunplus Technology                     | 5         | 0.27%   |
| KYE Systems (Mouse Systems)            | 5         | 0.27%   |
| Hewlett-Packard                        | 5         | 0.27%   |
| DigiTech                               | 5         | 0.27%   |
| Unknown                                | 4         | 0.22%   |
| Trust                                  | 4         | 0.22%   |
| GEMBIRD                                | 4         | 0.22%   |
| Cubeternet                             | 4         | 0.22%   |
| ARC International                      | 4         | 0.22%   |
| Samsung Electronics                    | 3         | 0.16%   |
| Aveo Technology                        | 3         | 0.16%   |
| Pixart Imaging                         | 2         | 0.11%   |
| Nebraska Furniture Mart                | 2         | 0.11%   |
| MacroSilicon                           | 2         | 0.11%   |
| Jieli Technology                       | 2         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 96        | 5.11%   |
| Realtek Integrated_Webcam_5M             | 57        | 3.03%   |
| Chicony Integrated Camera                | 51        | 2.71%   |
| Realtek Integrated_Webcam_HD             | 48        | 2.55%   |
| Sunplus Integrated_Webcam_HD             | 45        | 2.39%   |
| Chicony HD WebCam                        | 42        | 2.24%   |
| Syntek Integrated Camera                 | 25        | 1.33%   |
| Microdia Integrated Webcam               | 23        | 1.22%   |
| Logitech Webcam C270                     | 23        | 1.22%   |
| IMC Networks USB2.0 HD UVC WebCam        | 23        | 1.22%   |
| Realtek USB Camera                       | 21        | 1.12%   |
| IMC Networks Integrated Camera           | 21        | 1.12%   |
| Chicony USB 2.0 Camera                   | 21        | 1.12%   |
| Microdia Integrated_Webcam_5M            | 17        | 0.9%    |
| IMC Networks USB2.0 VGA UVC WebCam       | 17        | 0.9%    |
| Chicony VGA WebCam                       | 17        | 0.9%    |
| Chicony USB2.0 VGA UVC WebCam            | 17        | 0.9%    |
| Chicony TOSHIBA Web Camera - HD          | 17        | 0.9%    |
| Acer Integrated Camera                   | 17        | 0.9%    |
| Chicony FJ Camera                        | 16        | 0.85%   |
| Chicony Lenovo EasyCamera                | 15        | 0.8%    |
| Apple Built-in iSight                    | 15        | 0.8%    |
| Suyin Acer/HP Integrated Webcam [CN0314] | 13        | 0.69%   |
| Microdia USB 2.0 Camera                  | 13        | 0.69%   |
| Acer Lenovo EasyCamera                   | 13        | 0.69%   |
| Realtek Lenovo EasyCamera                | 12        | 0.64%   |
| Realtek EasyCamera                       | 12        | 0.64%   |
| Quanta HP TrueVision HD Camera           | 12        | 0.64%   |
| Quanta HD User Facing                    | 12        | 0.64%   |
| Logitech HD Pro Webcam C920              | 12        | 0.64%   |
| Chicony HP Truevision HD camera          | 12        | 0.64%   |
| Chicony EasyCamera                       | 12        | 0.64%   |
| Syntek Lenovo EasyCamera                 | 11        | 0.59%   |
| Sunplus HD WebCam                        | 11        | 0.59%   |
| Realtek USB2.0 HD UVC WebCam             | 11        | 0.59%   |
| Lite-On Integrated Camera                | 11        | 0.59%   |
| Lite-On HP HD Webcam                     | 11        | 0.59%   |
| Chicony USB2.0 HD UVC WebCam             | 11        | 0.59%   |
| Chicony HP Webcam                        | 11        | 0.59%   |
| Chicony HP Truevision HD                 | 11        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 61        | 36.09%  |
| AuthenTec                  | 23        | 13.61%  |
| Upek                       | 17        | 10.06%  |
| Synaptics                  | 17        | 10.06%  |
| Elan Microelectronics      | 16        | 9.47%   |
| Shenzhen Goodix Technology | 14        | 8.28%   |
| LighTuning Technology      | 10        | 5.92%   |
| STMicroelectronics         | 8         | 4.73%   |
| Samsung Electronics        | 1         | 0.59%   |
| HOLTEK                     | 1         | 0.59%   |
| Focal-systems.Corp         | 1         | 0.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 16        | 9.47%   |
| Validity Sensors VFS495 Fingerprint Reader                  | 15        | 8.88%   |
| Shenzhen Goodix  FingerPrint Device                         | 9         | 5.33%   |
| STMicroelectronics Fingerprint Reader                       | 8         | 4.73%   |
| Elan ELAN:Fingerprint                                       | 8         | 4.73%   |
| Elan ELAN:ARM-M4                                            | 8         | 4.73%   |
| Validity Sensors VFS491                                     | 7         | 4.14%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 6         | 3.55%   |
| Validity Sensors Swipe Fingerprint Sensor                   | 6         | 3.55%   |
| AuthenTec AES2810                                           | 6         | 3.55%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 5         | 2.96%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 5         | 2.96%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 5         | 2.96%   |
| AuthenTec AES2501 Fingerprint Sensor                        | 5         | 2.96%   |
| AuthenTec AES1600                                           | 5         | 2.96%   |
| Unknown                                                     | 5         | 2.96%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 4         | 2.37%   |
| Shenzhen Goodix Fingerprint Reader                          | 4         | 2.37%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 3         | 1.78%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 3         | 1.78%   |
| Validity Sensors VFS301 Fingerprint Reader                  | 3         | 1.78%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint  | 3         | 1.78%   |
| LighTuning ES603 Swipe Fingerprint Sensor                   | 3         | 1.78%   |
| AuthenTec Fingerprint Sensor                                | 3         | 1.78%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 3         | 1.78%   |
| Validity Sensors Synaptics WBDI                             | 2         | 1.18%   |
| Validity Sensors Fingerprint scanner                        | 2         | 1.18%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor           | 1         | 0.59%   |
| Validity Sensors VFS300 Fingerprint Reader                  | 1         | 0.59%   |
| Validity Sensors VFS101 Fingerprint Reader                  | 1         | 0.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 0.59%   |
| Upek TCS5B Fingerprint sensor                               | 1         | 0.59%   |
| Synaptics WBDI Device                                       | 1         | 0.59%   |
| Synaptics  WBDI                                             | 1         | 0.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 0.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 0.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 1         | 0.59%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 0.59%   |
| Samsung Fingerprint Sensor Device - 730B                    | 1         | 0.59%   |
| LighTuning Fingerprint Sensor                               | 1         | 0.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 61        | 50.41%  |
| O2 Micro              | 16        | 13.22%  |
| Alcor Micro           | 15        | 12.4%   |
| Upek                  | 11        | 9.09%   |
| Lenovo                | 8         | 6.61%   |
| SCM Microsystems      | 3         | 2.48%   |
| Gemalto (was Gemplus) | 3         | 2.48%   |
| Realtek Semiconductor | 2         | 1.65%   |
| Cherry                | 1         | 0.83%   |
| Bit4id                | 1         | 0.83%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 28        | 23.14%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 14.88%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 12.4%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 11.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 9.09%   |
| Broadcom 5880                                                                | 10        | 8.26%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 6.61%   |
| Broadcom 58200                                                               | 5         | 4.13%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.65%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.65%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.65%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.83%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.83%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.83%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.83%   |
| Bit4id miniLector EVO                                                        | 1         | 0.83%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.83%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2873      | 82.87%  |
| 1     | 517       | 14.91%  |
| 2     | 69        | 1.99%   |
| 3     | 7         | 0.2%    |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 169       | 25.3%   |
| Graphics card            | 126       | 18.86%  |
| Chipcard                 | 117       | 17.51%  |
| Multimedia controller    | 66        | 9.88%   |
| Net/wireless             | 62        | 9.28%   |
| Bluetooth                | 44        | 6.59%   |
| Storage                  | 20        | 2.99%   |
| Communication controller | 18        | 2.69%   |
| Camera                   | 14        | 2.1%    |
| Unassigned class         | 12        | 1.8%    |
| Network                  | 5         | 0.75%   |
| Sound                    | 4         | 0.6%    |
| Wireless                 | 3         | 0.45%   |
| Flash memory             | 3         | 0.45%   |
| Net/ethernet             | 2         | 0.3%    |
| Card reader              | 2         | 0.3%    |
| Storage/raid             | 1         | 0.15%   |

