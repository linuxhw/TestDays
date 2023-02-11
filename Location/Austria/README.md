Linux in Austria - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Austria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Austria/Desktop/README.md) and [notebooks](/Location/Austria/Notebook/README.md).

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

Total: 2349

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | GF63 Thin 11UC              | Notebook    | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [c68678a1a5](https://linux-hardware.org/?probe=c68678a1a5) | Jan 31, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [a57a68e42f](https://linux-hardware.org/?probe=a57a68e42f) | Jan 31, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0d500d9d33](https://linux-hardware.org/?probe=0d500d9d33) | Jan 31, 2023 |
| Dell          | Latitude 5480               | Notebook    | [8b43efc7ea](https://linux-hardware.org/?probe=8b43efc7ea) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [78d987fedf](https://linux-hardware.org/?probe=78d987fedf) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [a178301183](https://linux-hardware.org/?probe=a178301183) | Jan 30, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [bfb86ee660](https://linux-hardware.org/?probe=bfb86ee660) | Jan 29, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [32d5472e21](https://linux-hardware.org/?probe=32d5472e21) | Jan 29, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [d528677cfd](https://linux-hardware.org/?probe=d528677cfd) | Jan 28, 2023 |
| HP            | 1495                        | Desktop     | [8c1f7b5fbd](https://linux-hardware.org/?probe=8c1f7b5fbd) | Jan 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c5168e6b33](https://linux-hardware.org/?probe=c5168e6b33) | Jan 27, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [4ecf66ddd9](https://linux-hardware.org/?probe=4ecf66ddd9) | Jan 27, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [4024f7c3bd](https://linux-hardware.org/?probe=4024f7c3bd) | Jan 26, 2023 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [6e5884ec0c](https://linux-hardware.org/?probe=6e5884ec0c) | Jan 26, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ea142e4848](https://linux-hardware.org/?probe=ea142e4848) | Jan 25, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [5973888b27](https://linux-hardware.org/?probe=5973888b27) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [e9c7c42a8b](https://linux-hardware.org/?probe=e9c7c42a8b) | Jan 22, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9035a00600](https://linux-hardware.org/?probe=9035a00600) | Jan 22, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [f1c0237cc0](https://linux-hardware.org/?probe=f1c0237cc0) | Jan 22, 2023 |
| Foxconn       | NETBOX NT-425/525 Ver       | Desktop     | [dfb8c476f9](https://linux-hardware.org/?probe=dfb8c476f9) | Jan 21, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [2b5b2da951](https://linux-hardware.org/?probe=2b5b2da951) | Jan 20, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | Notebook    | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| ASUSTek       | A6U                         | Notebook    | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | Notebook    | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [eddf4927eb](https://linux-hardware.org/?probe=eddf4927eb) | Jan 19, 2023 |
| MSI           | VR630                       | Notebook    | [943c1d68fa](https://linux-hardware.org/?probe=943c1d68fa) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [a5cbba39d7](https://linux-hardware.org/?probe=a5cbba39d7) | Jan 19, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [4197c5f3d3](https://linux-hardware.org/?probe=4197c5f3d3) | Jan 19, 2023 |
| ASUSTek       | K53TA                       | Notebook    | [a56a3691e9](https://linux-hardware.org/?probe=a56a3691e9) | Jan 18, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [c99128e783](https://linux-hardware.org/?probe=c99128e783) | Jan 16, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | Notebook    | [b68853abf6](https://linux-hardware.org/?probe=b68853abf6) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [a159136180](https://linux-hardware.org/?probe=a159136180) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [6f3b4fc131](https://linux-hardware.org/?probe=6f3b4fc131) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [b33bedc4c2](https://linux-hardware.org/?probe=b33bedc4c2) | Jan 15, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [80f9124e5a](https://linux-hardware.org/?probe=80f9124e5a) | Jan 14, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [81d232a246](https://linux-hardware.org/?probe=81d232a246) | Jan 14, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [ba09b2045b](https://linux-hardware.org/?probe=ba09b2045b) | Jan 13, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [5721ffbc43](https://linux-hardware.org/?probe=5721ffbc43) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c3a30838c3](https://linux-hardware.org/?probe=c3a30838c3) | Jan 13, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [64c403ce6d](https://linux-hardware.org/?probe=64c403ce6d) | Jan 13, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [806da9b386](https://linux-hardware.org/?probe=806da9b386) | Jan 12, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [29e6fcfd32](https://linux-hardware.org/?probe=29e6fcfd32) | Jan 12, 2023 |
| Dell          | Latitude E5550              | Notebook    | [0b14eb18d9](https://linux-hardware.org/?probe=0b14eb18d9) | Jan 12, 2023 |
| Medion        | E6222                       | Notebook    | [e3b3da28fa](https://linux-hardware.org/?probe=e3b3da28fa) | Jan 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e608d09ac5](https://linux-hardware.org/?probe=e608d09ac5) | Jan 11, 2023 |
| Dell          | Latitude E5550              | Notebook    | [5e76d378f9](https://linux-hardware.org/?probe=5e76d378f9) | Jan 11, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [0ddddc438d](https://linux-hardware.org/?probe=0ddddc438d) | Jan 11, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [7d56f2f733](https://linux-hardware.org/?probe=7d56f2f733) | Jan 11, 2023 |
| Dell          | Latitude E7440              | Notebook    | [bfdc9dfc63](https://linux-hardware.org/?probe=bfdc9dfc63) | Jan 11, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [0f0b38970a](https://linux-hardware.org/?probe=0f0b38970a) | Jan 11, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [b2d69bd762](https://linux-hardware.org/?probe=b2d69bd762) | Jan 11, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [3e54ca06f5](https://linux-hardware.org/?probe=3e54ca06f5) | Jan 10, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [fbde9a1dba](https://linux-hardware.org/?probe=fbde9a1dba) | Jan 10, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a365222a35](https://linux-hardware.org/?probe=a365222a35) | Jan 09, 2023 |
| MSI           | GS63VR 7RF                  | Notebook    | [95aadb3cc4](https://linux-hardware.org/?probe=95aadb3cc4) | Jan 09, 2023 |
| Sony          | SVE1512H1EB                 | Notebook    | [723e8bfbe6](https://linux-hardware.org/?probe=723e8bfbe6) | Jan 09, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [297380c89a](https://linux-hardware.org/?probe=297380c89a) | Jan 09, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [919b259ea2](https://linux-hardware.org/?probe=919b259ea2) | Jan 09, 2023 |
| Acer          | Iconia W700                 | Notebook    | [bcfec36896](https://linux-hardware.org/?probe=bcfec36896) | Jan 09, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [d67718b4e8](https://linux-hardware.org/?probe=d67718b4e8) | Jan 08, 2023 |
| Google        | Kled                        | Notebook    | [3cb98a4497](https://linux-hardware.org/?probe=3cb98a4497) | Jan 07, 2023 |
| Lenovo        | ThinkPad X220 4290KJ6       | Notebook    | [8296e61afd](https://linux-hardware.org/?probe=8296e61afd) | Jan 05, 2023 |
| Sony          | VPCEH2D0E                   | Notebook    | [78367f11f5](https://linux-hardware.org/?probe=78367f11f5) | Jan 04, 2023 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [e6ee0cd764](https://linux-hardware.org/?probe=e6ee0cd764) | Jan 04, 2023 |
| ASUSTek       | K93SM                       | Notebook    | [c0fb78e9a3](https://linux-hardware.org/?probe=c0fb78e9a3) | Jan 03, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [b1771ee07c](https://linux-hardware.org/?probe=b1771ee07c) | Jan 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a35156e0c3](https://linux-hardware.org/?probe=a35156e0c3) | Jan 02, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [8f4f98da64](https://linux-hardware.org/?probe=8f4f98da64) | Jan 02, 2023 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [f39e3e8350](https://linux-hardware.org/?probe=f39e3e8350) | Jan 02, 2023 |
| Dell          | Latitude 7430               | Notebook    | [ad796336f7](https://linux-hardware.org/?probe=ad796336f7) | Jan 01, 2023 |
| Lenovo        | ThinkPad X270 20K60018GE    | Notebook    | [a92939c1f5](https://linux-hardware.org/?probe=a92939c1f5) | Jan 01, 2023 |
| Lenovo        | ThinkPad X390 20Q00051GE    | Notebook    | [5b3d1b750d](https://linux-hardware.org/?probe=5b3d1b750d) | Dec 31, 2022 |
| Lenovo        | ThinkPad X390 20Q00051GE    | Notebook    | [775096be09](https://linux-hardware.org/?probe=775096be09) | Dec 31, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [cdc31b8338](https://linux-hardware.org/?probe=cdc31b8338) | Dec 30, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [de6ea0ae2e](https://linux-hardware.org/?probe=de6ea0ae2e) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c28fb2edb2](https://linux-hardware.org/?probe=c28fb2edb2) | Dec 30, 2022 |
| ASUSTek       | P7P55D-E                    | Desktop     | [f725a0095a](https://linux-hardware.org/?probe=f725a0095a) | Dec 30, 2022 |
| Supermicro    | H8SCM                       | Server      | [9ee42dcf6f](https://linux-hardware.org/?probe=9ee42dcf6f) | Dec 29, 2022 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [6e3a112190](https://linux-hardware.org/?probe=6e3a112190) | Dec 28, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [d680b8dd2a](https://linux-hardware.org/?probe=d680b8dd2a) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [e8dce940d8](https://linux-hardware.org/?probe=e8dce940d8) | Dec 26, 2022 |
| Medion        | X782X/X783X                 | Notebook    | [a8befc040f](https://linux-hardware.org/?probe=a8befc040f) | Dec 26, 2022 |
| Matrox Ele... | 4GPMOBIL 7449-03-0          | Desktop     | [c02a37a124](https://linux-hardware.org/?probe=c02a37a124) | Dec 26, 2022 |
| ASUSTek       | P7P55D-E                    | Desktop     | [a6be229477](https://linux-hardware.org/?probe=a6be229477) | Dec 24, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e3e2773bde](https://linux-hardware.org/?probe=e3e2773bde) | Dec 24, 2022 |
| Notebook      | P64_HJ,HK1                  | Notebook    | [26a548a6f3](https://linux-hardware.org/?probe=26a548a6f3) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [431eac7d11](https://linux-hardware.org/?probe=431eac7d11) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [b934598049](https://linux-hardware.org/?probe=b934598049) | Dec 22, 2022 |
| Lenovo        | ThinkPad T490 20N20048GE    | Notebook    | [629a725afa](https://linux-hardware.org/?probe=629a725afa) | Dec 21, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [aeb826326b](https://linux-hardware.org/?probe=aeb826326b) | Dec 20, 2022 |
| Acer          | Aspire A715-72G             | Notebook    | [8e15fef839](https://linux-hardware.org/?probe=8e15fef839) | Dec 19, 2022 |
| MSI           | GE63 Raider RGB 8RF         | Notebook    | [a85193c482](https://linux-hardware.org/?probe=a85193c482) | Dec 19, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [74207a9fec](https://linux-hardware.org/?probe=74207a9fec) | Dec 19, 2022 |
| Google        | Cyan                        | Notebook    | [fff3502929](https://linux-hardware.org/?probe=fff3502929) | Dec 19, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [88d7491a00](https://linux-hardware.org/?probe=88d7491a00) | Dec 19, 2022 |
| AXDIA Inte... | myBook PRO14 SE V2          | Notebook    | [14b79d7a8b](https://linux-hardware.org/?probe=14b79d7a8b) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [86c9426d80](https://linux-hardware.org/?probe=86c9426d80) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [05fcf7302f](https://linux-hardware.org/?probe=05fcf7302f) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [fa03fe621a](https://linux-hardware.org/?probe=fa03fe621a) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [8480834751](https://linux-hardware.org/?probe=8480834751) | Dec 17, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [12b3654541](https://linux-hardware.org/?probe=12b3654541) | Dec 15, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ffe85423d8](https://linux-hardware.org/?probe=ffe85423d8) | Dec 15, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [d0d30cd96f](https://linux-hardware.org/?probe=d0d30cd96f) | Dec 14, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [943bcd1d12](https://linux-hardware.org/?probe=943bcd1d12) | Dec 14, 2022 |
| ASRock        | X670E PG Lightning          | Desktop     | [08e4e03d36](https://linux-hardware.org/?probe=08e4e03d36) | Dec 13, 2022 |
| ASRock        | X670E PG Lightning          | Desktop     | [3a6a347ff9](https://linux-hardware.org/?probe=3a6a347ff9) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [9b02acceb3](https://linux-hardware.org/?probe=9b02acceb3) | Dec 12, 2022 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [fd77b80943](https://linux-hardware.org/?probe=fd77b80943) | Dec 12, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [37267c6b3f](https://linux-hardware.org/?probe=37267c6b3f) | Dec 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [b518609312](https://linux-hardware.org/?probe=b518609312) | Dec 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [f815a2e4a3](https://linux-hardware.org/?probe=f815a2e4a3) | Dec 12, 2022 |
| MSI           | GE63 Raider RGB 8RF         | Notebook    | [b311865418](https://linux-hardware.org/?probe=b311865418) | Dec 12, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [e0b1d50b7c](https://linux-hardware.org/?probe=e0b1d50b7c) | Dec 11, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [cc2d9043d9](https://linux-hardware.org/?probe=cc2d9043d9) | Dec 11, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [32ce05790e](https://linux-hardware.org/?probe=32ce05790e) | Dec 11, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [f6341e7afb](https://linux-hardware.org/?probe=f6341e7afb) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [50e5b72a10](https://linux-hardware.org/?probe=50e5b72a10) | Dec 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8f38dcc9d4](https://linux-hardware.org/?probe=8f38dcc9d4) | Dec 10, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [b7171256c0](https://linux-hardware.org/?probe=b7171256c0) | Dec 07, 2022 |
| Lenovo        | ThinkStation S20 4157DT6    | Desktop     | [7c45cf5115](https://linux-hardware.org/?probe=7c45cf5115) | Dec 07, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [cd166beede](https://linux-hardware.org/?probe=cd166beede) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [8d5d04f931](https://linux-hardware.org/?probe=8d5d04f931) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [4e8f04ce8f](https://linux-hardware.org/?probe=4e8f04ce8f) | Dec 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [2b34016cad](https://linux-hardware.org/?probe=2b34016cad) | Dec 04, 2022 |
| Acer          | Aspire A514-53              | Notebook    | [f0c20f1a0a](https://linux-hardware.org/?probe=f0c20f1a0a) | Dec 04, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [05131558b5](https://linux-hardware.org/?probe=05131558b5) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [9fcc18738b](https://linux-hardware.org/?probe=9fcc18738b) | Dec 03, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [027cd08fb1](https://linux-hardware.org/?probe=027cd08fb1) | Dec 03, 2022 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [74902de02b](https://linux-hardware.org/?probe=74902de02b) | Dec 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [790ae8be94](https://linux-hardware.org/?probe=790ae8be94) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4f36906529](https://linux-hardware.org/?probe=4f36906529) | Dec 02, 2022 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [373dac5bbb](https://linux-hardware.org/?probe=373dac5bbb) | Dec 02, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [d9bba42204](https://linux-hardware.org/?probe=d9bba42204) | Dec 02, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [eb13a8db03](https://linux-hardware.org/?probe=eb13a8db03) | Dec 02, 2022 |
| Acer          | Aspire A514-53              | Notebook    | [07ff06f360](https://linux-hardware.org/?probe=07ff06f360) | Dec 02, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [d7694493c0](https://linux-hardware.org/?probe=d7694493c0) | Dec 02, 2022 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [01dfdc071e](https://linux-hardware.org/?probe=01dfdc071e) | Dec 01, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [9aa4880856](https://linux-hardware.org/?probe=9aa4880856) | Dec 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e03c6b53ed](https://linux-hardware.org/?probe=e03c6b53ed) | Dec 01, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [c1f5a1f413](https://linux-hardware.org/?probe=c1f5a1f413) | Dec 01, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [d2c04dd7cd](https://linux-hardware.org/?probe=d2c04dd7cd) | Dec 01, 2022 |
| W271ELQ       | Unknown                     | Notebook    | [ae170d1e81](https://linux-hardware.org/?probe=ae170d1e81) | Dec 01, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [ae01075720](https://linux-hardware.org/?probe=ae01075720) | Nov 28, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ceb78dbe4e](https://linux-hardware.org/?probe=ceb78dbe4e) | Nov 28, 2022 |
| Lenovo        | ThinkPad T520 4243F53       | Notebook    | [8f9e96442a](https://linux-hardware.org/?probe=8f9e96442a) | Nov 27, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [ee234d62ec](https://linux-hardware.org/?probe=ee234d62ec) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| Dell          | Latitude 3520               | Notebook    | [896180c55d](https://linux-hardware.org/?probe=896180c55d) | Nov 25, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6646978243](https://linux-hardware.org/?probe=6646978243) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [ddcb37ea55](https://linux-hardware.org/?probe=ddcb37ea55) | Nov 23, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [6d3657ecde](https://linux-hardware.org/?probe=6d3657ecde) | Nov 23, 2022 |
| Dell          | Precision 5560              | Notebook    | [f20218fb35](https://linux-hardware.org/?probe=f20218fb35) | Nov 23, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [fc53a66047](https://linux-hardware.org/?probe=fc53a66047) | Nov 22, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [4fc70b9ddc](https://linux-hardware.org/?probe=4fc70b9ddc) | Nov 21, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [dc848e747b](https://linux-hardware.org/?probe=dc848e747b) | Nov 21, 2022 |
| Microsoft     | Surface Laptop              | Tablet      | [b6697363ea](https://linux-hardware.org/?probe=b6697363ea) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8c271e833d](https://linux-hardware.org/?probe=8c271e833d) | Nov 20, 2022 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [4ea8f7dbb0](https://linux-hardware.org/?probe=4ea8f7dbb0) | Nov 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [5932954a14](https://linux-hardware.org/?probe=5932954a14) | Nov 19, 2022 |
| Acer          | FMP55                       | Desktop     | [f35d63ca8b](https://linux-hardware.org/?probe=f35d63ca8b) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [478fa166bd](https://linux-hardware.org/?probe=478fa166bd) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c8c74ea1ec](https://linux-hardware.org/?probe=c8c74ea1ec) | Nov 15, 2022 |
| Dell          | Latitude E6220              | Notebook    | [b1270460e6](https://linux-hardware.org/?probe=b1270460e6) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [d6b19cfd9d](https://linux-hardware.org/?probe=d6b19cfd9d) | Nov 15, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [a83e2b1a92](https://linux-hardware.org/?probe=a83e2b1a92) | Nov 13, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [4406929fb6](https://linux-hardware.org/?probe=4406929fb6) | Nov 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [695b0b0356](https://linux-hardware.org/?probe=695b0b0356) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [24c5edc9f9](https://linux-hardware.org/?probe=24c5edc9f9) | Nov 10, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9c6a00b034](https://linux-hardware.org/?probe=9c6a00b034) | Nov 09, 2022 |
| ASUSTek       | VM40B                       | Desktop     | [5736f2e2ae](https://linux-hardware.org/?probe=5736f2e2ae) | Nov 08, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [2670a536f0](https://linux-hardware.org/?probe=2670a536f0) | Nov 08, 2022 |
| Medion        | MS-7797                     | Desktop     | [41ba0c8fdc](https://linux-hardware.org/?probe=41ba0c8fdc) | Nov 08, 2022 |
| ASUSTek       | X55A                        | Notebook    | [6391006e3d](https://linux-hardware.org/?probe=6391006e3d) | Nov 07, 2022 |
| ASUSTek       | X55A                        | Notebook    | [ae4277aa87](https://linux-hardware.org/?probe=ae4277aa87) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1a0fbb4d0d](https://linux-hardware.org/?probe=1a0fbb4d0d) | Nov 06, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [4c47d0ef97](https://linux-hardware.org/?probe=4c47d0ef97) | Nov 05, 2022 |
| Olimex        | A20-Olinuxino Micro         | Soc         | [82674b87bb](https://linux-hardware.org/?probe=82674b87bb) | Nov 03, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [7007ab7df6](https://linux-hardware.org/?probe=7007ab7df6) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [18b0671002](https://linux-hardware.org/?probe=18b0671002) | Nov 03, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [565ad502cc](https://linux-hardware.org/?probe=565ad502cc) | Nov 02, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [9d0e85aed7](https://linux-hardware.org/?probe=9d0e85aed7) | Nov 01, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [05eeb9e341](https://linux-hardware.org/?probe=05eeb9e341) | Nov 01, 2022 |
| ASUSTek       | K54L                        | Notebook    | [200f6044c2](https://linux-hardware.org/?probe=200f6044c2) | Oct 31, 2022 |
| Adlinktech    | SB-MLC                      | Notebook    | [203d95e012](https://linux-hardware.org/?probe=203d95e012) | Oct 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [8f2639b285](https://linux-hardware.org/?probe=8f2639b285) | Oct 31, 2022 |
| Lenovo        | ThinkPad T510 4384WKU       | Notebook    | [86fee6e260](https://linux-hardware.org/?probe=86fee6e260) | Oct 30, 2022 |
| Dell          | Studio 1737                 | Notebook    | [97f398804e](https://linux-hardware.org/?probe=97f398804e) | Oct 29, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d768cd4c66](https://linux-hardware.org/?probe=d768cd4c66) | Oct 29, 2022 |
| HP            | EliteBook 820 G4            | Notebook    | [c41402e832](https://linux-hardware.org/?probe=c41402e832) | Oct 29, 2022 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [c079764998](https://linux-hardware.org/?probe=c079764998) | Oct 28, 2022 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [5ef9b4213f](https://linux-hardware.org/?probe=5ef9b4213f) | Oct 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c9cd061f05](https://linux-hardware.org/?probe=c9cd061f05) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [2f6e4235f7](https://linux-hardware.org/?probe=2f6e4235f7) | Oct 28, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [5748274da1](https://linux-hardware.org/?probe=5748274da1) | Oct 27, 2022 |
| Dell          | Precision 7530              | Notebook    | [daee9e9524](https://linux-hardware.org/?probe=daee9e9524) | Oct 26, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [a943d9879c](https://linux-hardware.org/?probe=a943d9879c) | Oct 26, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [0b4711df41](https://linux-hardware.org/?probe=0b4711df41) | Oct 26, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [622aa11277](https://linux-hardware.org/?probe=622aa11277) | Oct 26, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b0f36ae0c5](https://linux-hardware.org/?probe=b0f36ae0c5) | Oct 25, 2022 |
| Lenovo        | ThinkPad P1 20MD000NGE      | Notebook    | [561f09ba0f](https://linux-hardware.org/?probe=561f09ba0f) | Oct 25, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| MSI           | Z68MA-G45                   | Desktop     | [3f398756eb](https://linux-hardware.org/?probe=3f398756eb) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | Desktop     | [d96627943d](https://linux-hardware.org/?probe=d96627943d) | Oct 23, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | Notebook    | [efb2913d22](https://linux-hardware.org/?probe=efb2913d22) | Oct 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [7435d326b7](https://linux-hardware.org/?probe=7435d326b7) | Oct 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [dcb8b694a7](https://linux-hardware.org/?probe=dcb8b694a7) | Oct 23, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [bdd6e6d3a5](https://linux-hardware.org/?probe=bdd6e6d3a5) | Oct 23, 2022 |
| Lenovo        | ThinkPad Edge S430 33643... | Notebook    | [a73e4a9246](https://linux-hardware.org/?probe=a73e4a9246) | Oct 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [b05efe341f](https://linux-hardware.org/?probe=b05efe341f) | Oct 22, 2022 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [99da3e6f09](https://linux-hardware.org/?probe=99da3e6f09) | Oct 22, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [eb651764eb](https://linux-hardware.org/?probe=eb651764eb) | Oct 22, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [80032ce2ea](https://linux-hardware.org/?probe=80032ce2ea) | Oct 22, 2022 |
| MSI           | H81M-P33                    | Desktop     | [efbd4959b8](https://linux-hardware.org/?probe=efbd4959b8) | Oct 21, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [1ce3fc664e](https://linux-hardware.org/?probe=1ce3fc664e) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [06328b7f7c](https://linux-hardware.org/?probe=06328b7f7c) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7d35a56915](https://linux-hardware.org/?probe=7d35a56915) | Oct 20, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [285e78cfbe](https://linux-hardware.org/?probe=285e78cfbe) | Oct 19, 2022 |
| Dell          | Latitude 5520               | Notebook    | [fc014585a8](https://linux-hardware.org/?probe=fc014585a8) | Oct 19, 2022 |
| Dell          | Latitude 5520               | Notebook    | [3589f77c74](https://linux-hardware.org/?probe=3589f77c74) | Oct 19, 2022 |
| Lenovo        | ThinkPad T15g Gen 1 20US... | Notebook    | [ec42bc932e](https://linux-hardware.org/?probe=ec42bc932e) | Oct 18, 2022 |
| Dell          | Precision 5510              | Notebook    | [d56d0aceaf](https://linux-hardware.org/?probe=d56d0aceaf) | Oct 18, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | Notebook    | [8c97c331b9](https://linux-hardware.org/?probe=8c97c331b9) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [76f9929a9c](https://linux-hardware.org/?probe=76f9929a9c) | Oct 17, 2022 |
| Dell          | Latitude 3520               | Notebook    | [f556b42181](https://linux-hardware.org/?probe=f556b42181) | Oct 16, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [59ecc7da84](https://linux-hardware.org/?probe=59ecc7da84) | Oct 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [766f4b2d1f](https://linux-hardware.org/?probe=766f4b2d1f) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [bf46cd0c9e](https://linux-hardware.org/?probe=bf46cd0c9e) | Oct 14, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [bc23ce28e0](https://linux-hardware.org/?probe=bc23ce28e0) | Oct 14, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [8dc5e6f530](https://linux-hardware.org/?probe=8dc5e6f530) | Oct 14, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [04147466b3](https://linux-hardware.org/?probe=04147466b3) | Oct 13, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dc990d0395](https://linux-hardware.org/?probe=dc990d0395) | Oct 12, 2022 |
| Dell          | Latitude E6440              | Notebook    | [3b13c28e46](https://linux-hardware.org/?probe=3b13c28e46) | Oct 12, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [073deeb58c](https://linux-hardware.org/?probe=073deeb58c) | Oct 11, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d1b0bd16b5](https://linux-hardware.org/?probe=d1b0bd16b5) | Oct 11, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [da36ee9925](https://linux-hardware.org/?probe=da36ee9925) | Oct 11, 2022 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [10709dd95e](https://linux-hardware.org/?probe=10709dd95e) | Oct 10, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [e860301211](https://linux-hardware.org/?probe=e860301211) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb5a512250](https://linux-hardware.org/?probe=eb5a512250) | Oct 09, 2022 |
| Dell          | 0MN1TX A01                  | Desktop     | [a9faf44fe8](https://linux-hardware.org/?probe=a9faf44fe8) | Oct 07, 2022 |
| MSI           | Modern 14 B11M              | Notebook    | [e0391b5084](https://linux-hardware.org/?probe=e0391b5084) | Oct 05, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [16b58b369a](https://linux-hardware.org/?probe=16b58b369a) | Oct 05, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [e722d17a52](https://linux-hardware.org/?probe=e722d17a52) | Oct 01, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [9667dac801](https://linux-hardware.org/?probe=9667dac801) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [e829c9c0c6](https://linux-hardware.org/?probe=e829c9c0c6) | Sep 30, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [16f1ddb076](https://linux-hardware.org/?probe=16f1ddb076) | Sep 30, 2022 |
| Unknown       | 775VM8                      | Desktop     | [114c84d76c](https://linux-hardware.org/?probe=114c84d76c) | Sep 30, 2022 |
| Unknown       | 775VM8                      | Desktop     | [903649eae9](https://linux-hardware.org/?probe=903649eae9) | Sep 30, 2022 |
| MSI           | H110 PC MATE                | Desktop     | [ac97c636a5](https://linux-hardware.org/?probe=ac97c636a5) | Sep 30, 2022 |
| Notebook      | NJ50_70CU                   | Notebook    | [4914d3ffe1](https://linux-hardware.org/?probe=4914d3ffe1) | Sep 29, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [d27bf09dc8](https://linux-hardware.org/?probe=d27bf09dc8) | Sep 27, 2022 |
| Medion        | MS-7728                     | Desktop     | [82da4b643b](https://linux-hardware.org/?probe=82da4b643b) | Sep 27, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [89303afdb5](https://linux-hardware.org/?probe=89303afdb5) | Sep 26, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [3c0a494baa](https://linux-hardware.org/?probe=3c0a494baa) | Sep 26, 2022 |
| Dell          | Latitude E6400              | Notebook    | [c1190109d0](https://linux-hardware.org/?probe=c1190109d0) | Sep 26, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [76166adede](https://linux-hardware.org/?probe=76166adede) | Sep 26, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a213c6d22a](https://linux-hardware.org/?probe=a213c6d22a) | Sep 26, 2022 |
| AMI           | Intel                       | Notebook    | [56de8f8b8a](https://linux-hardware.org/?probe=56de8f8b8a) | Sep 25, 2022 |
| AMI           | Intel                       | Notebook    | [330585dcd8](https://linux-hardware.org/?probe=330585dcd8) | Sep 25, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0047e2de0e](https://linux-hardware.org/?probe=0047e2de0e) | Sep 24, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [39dc43058e](https://linux-hardware.org/?probe=39dc43058e) | Sep 23, 2022 |
| MSI           | H110 PC MATE                | Desktop     | [006830e521](https://linux-hardware.org/?probe=006830e521) | Sep 23, 2022 |
| HP            | Compaq 15                   | Notebook    | [345fe48777](https://linux-hardware.org/?probe=345fe48777) | Sep 22, 2022 |
| Dell          | Latitude E6510              | Notebook    | [fa644f90c4](https://linux-hardware.org/?probe=fa644f90c4) | Sep 22, 2022 |
| ASUSTek       | WS C422 PRO_SE              | Desktop     | [e278a4ab5e](https://linux-hardware.org/?probe=e278a4ab5e) | Sep 21, 2022 |
| HP            | Pavilion 17                 | Notebook    | [0f7eec1f7a](https://linux-hardware.org/?probe=0f7eec1f7a) | Sep 21, 2022 |
| HP            | 1998                        | Desktop     | [5148539ae1](https://linux-hardware.org/?probe=5148539ae1) | Sep 21, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [2165b4b046](https://linux-hardware.org/?probe=2165b4b046) | Sep 20, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [233ba928b8](https://linux-hardware.org/?probe=233ba928b8) | Sep 20, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [7561f24877](https://linux-hardware.org/?probe=7561f24877) | Sep 20, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0c6c042af0](https://linux-hardware.org/?probe=0c6c042af0) | Sep 20, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [4d5fc6b39f](https://linux-hardware.org/?probe=4d5fc6b39f) | Sep 20, 2022 |
| Samsung       | R530/R730                   | Notebook    | [0d4e13e70f](https://linux-hardware.org/?probe=0d4e13e70f) | Sep 19, 2022 |
| Dell          | 02M8NY A01                  | Desktop     | [498286eb91](https://linux-hardware.org/?probe=498286eb91) | Sep 19, 2022 |
| HP            | ProBook 470 G4              | Notebook    | [c11b354c39](https://linux-hardware.org/?probe=c11b354c39) | Sep 18, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [9eba047248](https://linux-hardware.org/?probe=9eba047248) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [980e4272fb](https://linux-hardware.org/?probe=980e4272fb) | Sep 17, 2022 |
| Intel         | DH67BL AAG10189-209         | Desktop     | [3507c0cdb7](https://linux-hardware.org/?probe=3507c0cdb7) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3c37d36ba8](https://linux-hardware.org/?probe=3c37d36ba8) | Sep 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [321432c752](https://linux-hardware.org/?probe=321432c752) | Sep 12, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [cae551826b](https://linux-hardware.org/?probe=cae551826b) | Sep 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [49694d92f6](https://linux-hardware.org/?probe=49694d92f6) | Sep 09, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [07dfc865cf](https://linux-hardware.org/?probe=07dfc865cf) | Sep 08, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [df80ca89ee](https://linux-hardware.org/?probe=df80ca89ee) | Sep 08, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [044bee5e0c](https://linux-hardware.org/?probe=044bee5e0c) | Sep 07, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [b5270dfd32](https://linux-hardware.org/?probe=b5270dfd32) | Sep 07, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| Acer          | Aspire S3                   | Notebook    | [cb62300974](https://linux-hardware.org/?probe=cb62300974) | Sep 07, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [12abaecf7e](https://linux-hardware.org/?probe=12abaecf7e) | Sep 05, 2022 |
| Acer          | Aspire A517-52G             | Notebook    | [c1709e40b7](https://linux-hardware.org/?probe=c1709e40b7) | Sep 05, 2022 |
| TrekStor      | Notebook Slim S130          | Notebook    | [abd3c1ccf8](https://linux-hardware.org/?probe=abd3c1ccf8) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [e2115bf207](https://linux-hardware.org/?probe=e2115bf207) | Sep 05, 2022 |
| Lenovo        | ThinkPad T500 2241WH7       | Notebook    | [1e14648d27](https://linux-hardware.org/?probe=1e14648d27) | Sep 04, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [106bdf4d1b](https://linux-hardware.org/?probe=106bdf4d1b) | Sep 04, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [ebceb9b949](https://linux-hardware.org/?probe=ebceb9b949) | Sep 04, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [d7c48b7007](https://linux-hardware.org/?probe=d7c48b7007) | Sep 04, 2022 |
| Samsung       | 950QDB                      | Convertible | [ec7cdfdff7](https://linux-hardware.org/?probe=ec7cdfdff7) | Sep 04, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [b298d162b1](https://linux-hardware.org/?probe=b298d162b1) | Sep 04, 2022 |
| ASUSTek       | H61M-A/USB3                 | Desktop     | [7801ef775b](https://linux-hardware.org/?probe=7801ef775b) | Sep 03, 2022 |
| BESSTAR Te... | X400                        | Notebook    | [8eb69c0ad6](https://linux-hardware.org/?probe=8eb69c0ad6) | Sep 03, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [1ce3a883a0](https://linux-hardware.org/?probe=1ce3a883a0) | Sep 03, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6109fc3fa8](https://linux-hardware.org/?probe=6109fc3fa8) | Sep 02, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [9f98c80601](https://linux-hardware.org/?probe=9f98c80601) | Sep 02, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [1746053c5b](https://linux-hardware.org/?probe=1746053c5b) | Sep 01, 2022 |
| Panasonic     | CF-191HACHFG                | Notebook    | [c1f0177dcb](https://linux-hardware.org/?probe=c1f0177dcb) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [37695eb7e5](https://linux-hardware.org/?probe=37695eb7e5) | Aug 31, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [0968e0629e](https://linux-hardware.org/?probe=0968e0629e) | Aug 31, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [f07bd2b99b](https://linux-hardware.org/?probe=f07bd2b99b) | Aug 28, 2022 |
| BESSTAR Te... | X400                        | Notebook    | [ab70086ae7](https://linux-hardware.org/?probe=ab70086ae7) | Aug 27, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [e18118bf63](https://linux-hardware.org/?probe=e18118bf63) | Aug 27, 2022 |
| Foxconn       | A6VMX 0A                    | Desktop     | [f31fcbf60d](https://linux-hardware.org/?probe=f31fcbf60d) | Aug 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [adf76251c5](https://linux-hardware.org/?probe=adf76251c5) | Aug 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [7c7a83f951](https://linux-hardware.org/?probe=7c7a83f951) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [cf7da7df12](https://linux-hardware.org/?probe=cf7da7df12) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [76db86107b](https://linux-hardware.org/?probe=76db86107b) | Aug 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [fcfd89bb32](https://linux-hardware.org/?probe=fcfd89bb32) | Aug 25, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [c579b49e4c](https://linux-hardware.org/?probe=c579b49e4c) | Aug 25, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [57727c2af7](https://linux-hardware.org/?probe=57727c2af7) | Aug 23, 2022 |
| Acer          | Predator G3-710             | Desktop     | [7a58c9348e](https://linux-hardware.org/?probe=7a58c9348e) | Aug 22, 2022 |
| MSI           | 2A9C                        | Desktop     | [4f15bcded6](https://linux-hardware.org/?probe=4f15bcded6) | Aug 22, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [30ebde5edc](https://linux-hardware.org/?probe=30ebde5edc) | Aug 21, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ced2388c29](https://linux-hardware.org/?probe=ced2388c29) | Aug 21, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e4869235d8](https://linux-hardware.org/?probe=e4869235d8) | Aug 20, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [782466213a](https://linux-hardware.org/?probe=782466213a) | Aug 19, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [42245b8fc8](https://linux-hardware.org/?probe=42245b8fc8) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [859884934f](https://linux-hardware.org/?probe=859884934f) | Aug 17, 2022 |
| Shuttle       | DS437                       | Notebook    | [21e0ca6a77](https://linux-hardware.org/?probe=21e0ca6a77) | Aug 17, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9b0baef94d](https://linux-hardware.org/?probe=9b0baef94d) | Aug 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [8ea659cd8c](https://linux-hardware.org/?probe=8ea659cd8c) | Aug 17, 2022 |
| TrekStor      | Notebook Slim S130          | Notebook    | [2b5689655d](https://linux-hardware.org/?probe=2b5689655d) | Aug 16, 2022 |
| TrekStor      | Notebook Slim S130          | Notebook    | [baf685c170](https://linux-hardware.org/?probe=baf685c170) | Aug 16, 2022 |
| ASUSTek       | F2A85-V                     | Desktop     | [cc26af3a41](https://linux-hardware.org/?probe=cc26af3a41) | Aug 16, 2022 |
| VALE          | Notebook Classic C170       | Notebook    | [e1563aa775](https://linux-hardware.org/?probe=e1563aa775) | Aug 15, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [ce03a2383e](https://linux-hardware.org/?probe=ce03a2383e) | Aug 15, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [cb10c34587](https://linux-hardware.org/?probe=cb10c34587) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [76e185a2e5](https://linux-hardware.org/?probe=76e185a2e5) | Aug 15, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [24b804043b](https://linux-hardware.org/?probe=24b804043b) | Aug 14, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1C00... | Notebook    | [dbbae31450](https://linux-hardware.org/?probe=dbbae31450) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fb405688fe](https://linux-hardware.org/?probe=fb405688fe) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [62a1acd85d](https://linux-hardware.org/?probe=62a1acd85d) | Aug 13, 2022 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [4a52da1c38](https://linux-hardware.org/?probe=4a52da1c38) | Aug 13, 2022 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [f71b1992c9](https://linux-hardware.org/?probe=f71b1992c9) | Aug 13, 2022 |
| BESSTAR Te... | X400                        | Notebook    | [e8424e153d](https://linux-hardware.org/?probe=e8424e153d) | Aug 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [059e0786bf](https://linux-hardware.org/?probe=059e0786bf) | Aug 11, 2022 |
| MSI           | MS-77311                    | Desktop     | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [0f33fa05f5](https://linux-hardware.org/?probe=0f33fa05f5) | Aug 10, 2022 |
| AMI           | Intel                       | Notebook    | [8d8db9dc8b](https://linux-hardware.org/?probe=8d8db9dc8b) | Aug 09, 2022 |
| AMI           | Intel                       | Notebook    | [0958b0a578](https://linux-hardware.org/?probe=0958b0a578) | Aug 09, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3ee621b609](https://linux-hardware.org/?probe=3ee621b609) | Aug 07, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | Notebook    | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| HP            | 3031h                       | Desktop     | [2409514846](https://linux-hardware.org/?probe=2409514846) | Aug 06, 2022 |
| Dell          | Latitude E5550              | Notebook    | [c1d9204443](https://linux-hardware.org/?probe=c1d9204443) | Aug 06, 2022 |
| MSI           | 2A9C                        | Desktop     | [e279622ca6](https://linux-hardware.org/?probe=e279622ca6) | Aug 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [91998a6bfe](https://linux-hardware.org/?probe=91998a6bfe) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d19309cb56](https://linux-hardware.org/?probe=d19309cb56) | Aug 06, 2022 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [03f6cbc20a](https://linux-hardware.org/?probe=03f6cbc20a) | Aug 05, 2022 |
| HP            | 8054                        | Desktop     | [888466c84e](https://linux-hardware.org/?probe=888466c84e) | Aug 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [8f934de8ef](https://linux-hardware.org/?probe=8f934de8ef) | Aug 03, 2022 |
| Dell          | Latitude E6430              | Notebook    | [82abc4b330](https://linux-hardware.org/?probe=82abc4b330) | Aug 03, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [8251f56856](https://linux-hardware.org/?probe=8251f56856) | Aug 03, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [06c0366665](https://linux-hardware.org/?probe=06c0366665) | Aug 03, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [a43bd517bb](https://linux-hardware.org/?probe=a43bd517bb) | Aug 02, 2022 |
| Sony          | VGN-FW51ZF_H                | Notebook    | [f42e9458c7](https://linux-hardware.org/?probe=f42e9458c7) | Jul 31, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [4a518ab792](https://linux-hardware.org/?probe=4a518ab792) | Jul 31, 2022 |
| Acer          | RS880M05                    | Desktop     | [0a5ede14e3](https://linux-hardware.org/?probe=0a5ede14e3) | Jul 30, 2022 |
| Toshiba       | Satellite L70-B             | Notebook    | [bee2cdca79](https://linux-hardware.org/?probe=bee2cdca79) | Jul 29, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [31b2d82a52](https://linux-hardware.org/?probe=31b2d82a52) | Jul 29, 2022 |
| HP            | 0AA0h                       | Desktop     | [5d21c69a99](https://linux-hardware.org/?probe=5d21c69a99) | Jul 29, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [5d5fd15071](https://linux-hardware.org/?probe=5d5fd15071) | Jul 28, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [1d04421fd5](https://linux-hardware.org/?probe=1d04421fd5) | Jul 27, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [fe23b6e49a](https://linux-hardware.org/?probe=fe23b6e49a) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [c1ab099582](https://linux-hardware.org/?probe=c1ab099582) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [b690b57222](https://linux-hardware.org/?probe=b690b57222) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [af6e67c798](https://linux-hardware.org/?probe=af6e67c798) | Jul 27, 2022 |
| MSI           | X79A-GD45 Plus              | Desktop     | [5496428dac](https://linux-hardware.org/?probe=5496428dac) | Jul 27, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [611f1d79e3](https://linux-hardware.org/?probe=611f1d79e3) | Jul 26, 2022 |
| Acer          | Aspire 3810T                | Notebook    | [92f9c99b5e](https://linux-hardware.org/?probe=92f9c99b5e) | Jul 26, 2022 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [f2f3a8788e](https://linux-hardware.org/?probe=f2f3a8788e) | Jul 23, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [79113b8782](https://linux-hardware.org/?probe=79113b8782) | Jul 23, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [3e6c333747](https://linux-hardware.org/?probe=3e6c333747) | Jul 22, 2022 |
| Shuttle       | FH67H                       | Desktop     | [fe77bc1ab0](https://linux-hardware.org/?probe=fe77bc1ab0) | Jul 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [f611683c8a](https://linux-hardware.org/?probe=f611683c8a) | Jul 22, 2022 |
| Lenovo        | ThinkPad E495 20NE000BGE    | Notebook    | [bad36e8ab5](https://linux-hardware.org/?probe=bad36e8ab5) | Jul 19, 2022 |
| Lenovo        | ThinkPad T440 20B7S1QQ1P    | Notebook    | [b8220c7bb8](https://linux-hardware.org/?probe=b8220c7bb8) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [b3059e0094](https://linux-hardware.org/?probe=b3059e0094) | Jul 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1QQ1P    | Notebook    | [01fae3a07c](https://linux-hardware.org/?probe=01fae3a07c) | Jul 15, 2022 |
| MSI           | H77MA-G43                   | Desktop     | [4cb547564b](https://linux-hardware.org/?probe=4cb547564b) | Jul 13, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [05b0102f01](https://linux-hardware.org/?probe=05b0102f01) | Jul 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [bb0bb0b58f](https://linux-hardware.org/?probe=bb0bb0b58f) | Jul 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [3b7528beab](https://linux-hardware.org/?probe=3b7528beab) | Jul 07, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [0e7b73b341](https://linux-hardware.org/?probe=0e7b73b341) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [6606cb7d46](https://linux-hardware.org/?probe=6606cb7d46) | Jul 06, 2022 |
| Sony          | VPCEH2J1E                   | Notebook    | [e51b908744](https://linux-hardware.org/?probe=e51b908744) | Jul 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [454fed051a](https://linux-hardware.org/?probe=454fed051a) | Jul 06, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a5e8e3a046](https://linux-hardware.org/?probe=a5e8e3a046) | Jul 05, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9fd928b97f](https://linux-hardware.org/?probe=9fd928b97f) | Jul 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [949457a05f](https://linux-hardware.org/?probe=949457a05f) | Jul 03, 2022 |
| AXDIA Inte... | WINPAD 12                   | Notebook    | [c263197569](https://linux-hardware.org/?probe=c263197569) | Jul 02, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [42b1694c97](https://linux-hardware.org/?probe=42b1694c97) | Jul 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ccb50bd0f4](https://linux-hardware.org/?probe=ccb50bd0f4) | Jun 30, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [d400a91be1](https://linux-hardware.org/?probe=d400a91be1) | Jun 28, 2022 |
| ASRock        | Z490 Pro4                   | Desktop     | [f84c8a756c](https://linux-hardware.org/?probe=f84c8a756c) | Jun 25, 2022 |
| MSI           | MAG Z690 TORPEDO            | Desktop     | [44700880cf](https://linux-hardware.org/?probe=44700880cf) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | Desktop     | [517a155f9b](https://linux-hardware.org/?probe=517a155f9b) | Jun 24, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [a10adc5a33](https://linux-hardware.org/?probe=a10adc5a33) | Jun 24, 2022 |
| Clevo         | Modified by dsanke          | Notebook    | [b88e7a22fe](https://linux-hardware.org/?probe=b88e7a22fe) | Jun 22, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [e18983e0d8](https://linux-hardware.org/?probe=e18983e0d8) | Jun 22, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [d59ef2842d](https://linux-hardware.org/?probe=d59ef2842d) | Jun 21, 2022 |
| ASRock        | Z370 Extreme4               | Desktop     | [c971857c53](https://linux-hardware.org/?probe=c971857c53) | Jun 20, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [de5d975c12](https://linux-hardware.org/?probe=de5d975c12) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [bfc7b65dee](https://linux-hardware.org/?probe=bfc7b65dee) | Jun 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [eb60cda77f](https://linux-hardware.org/?probe=eb60cda77f) | Jun 18, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [e19c095325](https://linux-hardware.org/?probe=e19c095325) | Jun 18, 2022 |
| MSI           | 970A-G43                    | Desktop     | [9514e1e2ef](https://linux-hardware.org/?probe=9514e1e2ef) | Jun 16, 2022 |
| AZW           | U59                         | Desktop     | [5a661910dc](https://linux-hardware.org/?probe=5a661910dc) | Jun 16, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [f07dc47259](https://linux-hardware.org/?probe=f07dc47259) | Jun 16, 2022 |
| MSI           | H510M PRO                   | Desktop     | [b75b035492](https://linux-hardware.org/?probe=b75b035492) | Jun 14, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [772043704c](https://linux-hardware.org/?probe=772043704c) | Jun 13, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [7cc9d90361](https://linux-hardware.org/?probe=7cc9d90361) | Jun 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6db07f5434](https://linux-hardware.org/?probe=6db07f5434) | Jun 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c637722355](https://linux-hardware.org/?probe=c637722355) | Jun 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [2353bf0f9d](https://linux-hardware.org/?probe=2353bf0f9d) | Jun 11, 2022 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [958f8bb25b](https://linux-hardware.org/?probe=958f8bb25b) | Jun 09, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [898eff4fae](https://linux-hardware.org/?probe=898eff4fae) | Jun 09, 2022 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [2f1acce421](https://linux-hardware.org/?probe=2f1acce421) | Jun 08, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [37e02e84a5](https://linux-hardware.org/?probe=37e02e84a5) | Jun 07, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [90b2505b78](https://linux-hardware.org/?probe=90b2505b78) | Jun 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [b2f7663fc9](https://linux-hardware.org/?probe=b2f7663fc9) | Jun 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [39bb0fa0c5](https://linux-hardware.org/?probe=39bb0fa0c5) | Jun 07, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [5ad950659b](https://linux-hardware.org/?probe=5ad950659b) | Jun 06, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [722cfa9375](https://linux-hardware.org/?probe=722cfa9375) | Jun 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [24da0cf09c](https://linux-hardware.org/?probe=24da0cf09c) | Jun 06, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2aeb22bc4b](https://linux-hardware.org/?probe=2aeb22bc4b) | Jun 06, 2022 |
| ASUSTek       | H87-PRO                     | Desktop     | [fd496870e4](https://linux-hardware.org/?probe=fd496870e4) | Jun 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [eccf357f9f](https://linux-hardware.org/?probe=eccf357f9f) | Jun 03, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [38fb3963cd](https://linux-hardware.org/?probe=38fb3963cd) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [6f5f1c9373](https://linux-hardware.org/?probe=6f5f1c9373) | Jun 01, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [156b265da0](https://linux-hardware.org/?probe=156b265da0) | Jun 01, 2022 |
| Gigabyte      | 970A-UD3                    | Desktop     | [c56522071c](https://linux-hardware.org/?probe=c56522071c) | Jun 01, 2022 |
| Dell          | Latitude 5520               | Notebook    | [03622600a8](https://linux-hardware.org/?probe=03622600a8) | May 30, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [b86f47e828](https://linux-hardware.org/?probe=b86f47e828) | May 29, 2022 |
| Dell          | Latitude E6410              | Notebook    | [72345f9352](https://linux-hardware.org/?probe=72345f9352) | May 28, 2022 |
| HP            | ProBook 470 G4              | Notebook    | [6049c10c3c](https://linux-hardware.org/?probe=6049c10c3c) | May 28, 2022 |
| HP            | 158B                        | Desktop     | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| HP            | 304Bh                       | Desktop     | [eaf30cead9](https://linux-hardware.org/?probe=eaf30cead9) | May 27, 2022 |
| System76      | Lemur Pro                   | Notebook    | [dcfd3abdd6](https://linux-hardware.org/?probe=dcfd3abdd6) | May 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d6bd3ae553](https://linux-hardware.org/?probe=d6bd3ae553) | May 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [643322d821](https://linux-hardware.org/?probe=643322d821) | May 26, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [257b7363bd](https://linux-hardware.org/?probe=257b7363bd) | May 24, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [666b9afd8f](https://linux-hardware.org/?probe=666b9afd8f) | May 24, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1RS0... | Notebook    | [174f6e2270](https://linux-hardware.org/?probe=174f6e2270) | May 23, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [e4fa1610cb](https://linux-hardware.org/?probe=e4fa1610cb) | May 22, 2022 |
| ASUSTek       | F2A85-V                     | Desktop     | [4d990d8f08](https://linux-hardware.org/?probe=4d990d8f08) | May 21, 2022 |
| ASUSTek       | H61M-A/USB3                 | Desktop     | [4d5f3d8c33](https://linux-hardware.org/?probe=4d5f3d8c33) | May 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [886a958a28](https://linux-hardware.org/?probe=886a958a28) | May 20, 2022 |
| Dell          | Latitude E6410              | Notebook    | [39be06dd23](https://linux-hardware.org/?probe=39be06dd23) | May 19, 2022 |
| Acer          | Extensa 2509                | Notebook    | [46df59d8b3](https://linux-hardware.org/?probe=46df59d8b3) | May 19, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [371eb0d1b7](https://linux-hardware.org/?probe=371eb0d1b7) | May 19, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [063aeed1a1](https://linux-hardware.org/?probe=063aeed1a1) | May 19, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [9a945a6cf5](https://linux-hardware.org/?probe=9a945a6cf5) | May 17, 2022 |
| Intel         | NUC10i5FNB K61361-306       | Mini pc     | [c118c850c6](https://linux-hardware.org/?probe=c118c850c6) | May 15, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [cea36d8ad8](https://linux-hardware.org/?probe=cea36d8ad8) | May 15, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [b28d047360](https://linux-hardware.org/?probe=b28d047360) | May 14, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [36ccfac84d](https://linux-hardware.org/?probe=36ccfac84d) | May 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1185abcaaa](https://linux-hardware.org/?probe=1185abcaaa) | May 14, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [369f214ed2](https://linux-hardware.org/?probe=369f214ed2) | May 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [6003e5a67f](https://linux-hardware.org/?probe=6003e5a67f) | May 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f7d09ea6c5](https://linux-hardware.org/?probe=f7d09ea6c5) | May 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [9cf4d23a81](https://linux-hardware.org/?probe=9cf4d23a81) | May 13, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [75587e5d3e](https://linux-hardware.org/?probe=75587e5d3e) | May 12, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [d3d6871bf7](https://linux-hardware.org/?probe=d3d6871bf7) | May 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [91404c39c7](https://linux-hardware.org/?probe=91404c39c7) | May 12, 2022 |
| Dell          | Latitude 5520               | Notebook    | [927a4b0ed0](https://linux-hardware.org/?probe=927a4b0ed0) | May 12, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [17dda821a0](https://linux-hardware.org/?probe=17dda821a0) | May 11, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [62ffc7ab1a](https://linux-hardware.org/?probe=62ffc7ab1a) | May 11, 2022 |
| Apple         | MacBook1,1                  | Notebook    | [399e291a66](https://linux-hardware.org/?probe=399e291a66) | May 09, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d95a50c16a](https://linux-hardware.org/?probe=d95a50c16a) | May 09, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [36b253f8bc](https://linux-hardware.org/?probe=36b253f8bc) | May 09, 2022 |
| Dell          | Latitude E6430              | Notebook    | [a6b570e125](https://linux-hardware.org/?probe=a6b570e125) | May 08, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ee92f88374](https://linux-hardware.org/?probe=ee92f88374) | May 07, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [8fda480b12](https://linux-hardware.org/?probe=8fda480b12) | May 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS1U60... | Notebook    | [ffafca2b97](https://linux-hardware.org/?probe=ffafca2b97) | May 06, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [d2a6709c96](https://linux-hardware.org/?probe=d2a6709c96) | May 06, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [feaa2cb9fb](https://linux-hardware.org/?probe=feaa2cb9fb) | May 06, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [5190bc7cf3](https://linux-hardware.org/?probe=5190bc7cf3) | May 06, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [0bc5a5fb9f](https://linux-hardware.org/?probe=0bc5a5fb9f) | May 05, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [9a83464a3b](https://linux-hardware.org/?probe=9a83464a3b) | May 04, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [935eb1722b](https://linux-hardware.org/?probe=935eb1722b) | May 02, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [925447d7e9](https://linux-hardware.org/?probe=925447d7e9) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b1e331055f](https://linux-hardware.org/?probe=b1e331055f) | May 01, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5838cd4268](https://linux-hardware.org/?probe=5838cd4268) | Apr 30, 2022 |
| Sony          | VPCEH2J1E                   | Notebook    | [86f6b8c750](https://linux-hardware.org/?probe=86f6b8c750) | Apr 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [9f5c24d3e8](https://linux-hardware.org/?probe=9f5c24d3e8) | Apr 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [da73d0b77d](https://linux-hardware.org/?probe=da73d0b77d) | Apr 29, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [b923126955](https://linux-hardware.org/?probe=b923126955) | Apr 27, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [2b7f66b701](https://linux-hardware.org/?probe=2b7f66b701) | Apr 26, 2022 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [ace84bb1e5](https://linux-hardware.org/?probe=ace84bb1e5) | Apr 25, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [bf7a7381a8](https://linux-hardware.org/?probe=bf7a7381a8) | Apr 24, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [1251ef669d](https://linux-hardware.org/?probe=1251ef669d) | Apr 24, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [dbb48b83bf](https://linux-hardware.org/?probe=dbb48b83bf) | Apr 24, 2022 |
| ASUSTek       | M4A78-E                     | Desktop     | [e4779f4dc8](https://linux-hardware.org/?probe=e4779f4dc8) | Apr 23, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [a8038d3972](https://linux-hardware.org/?probe=a8038d3972) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [208e83a199](https://linux-hardware.org/?probe=208e83a199) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [d10be6941f](https://linux-hardware.org/?probe=d10be6941f) | Apr 20, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [bbc4928d39](https://linux-hardware.org/?probe=bbc4928d39) | Apr 19, 2022 |
| ASRock        | Z490 Pro4                   | Desktop     | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [812afb255a](https://linux-hardware.org/?probe=812afb255a) | Apr 18, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e269a6b9b8](https://linux-hardware.org/?probe=e269a6b9b8) | Apr 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [b228a9bf01](https://linux-hardware.org/?probe=b228a9bf01) | Apr 15, 2022 |
| Notebook      | NJ50_70CU                   | Notebook    | [1ec86958b8](https://linux-hardware.org/?probe=1ec86958b8) | Apr 15, 2022 |
| ASUSTek       | P7P55D LE                   | Desktop     | [381477f3e6](https://linux-hardware.org/?probe=381477f3e6) | Apr 15, 2022 |
| Fujitsu       | D3434-S2 S26361-D3434-S2    | Desktop     | [7ff488cc8d](https://linux-hardware.org/?probe=7ff488cc8d) | Apr 14, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JH00... | Convertible | [51ba8cd105](https://linux-hardware.org/?probe=51ba8cd105) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [c68c62f98c](https://linux-hardware.org/?probe=c68c62f98c) | Apr 14, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [cf0c239670](https://linux-hardware.org/?probe=cf0c239670) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9af096ef7f](https://linux-hardware.org/?probe=9af096ef7f) | Apr 13, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [cb3eb74403](https://linux-hardware.org/?probe=cb3eb74403) | Apr 13, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [b7a035ea6b](https://linux-hardware.org/?probe=b7a035ea6b) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [f75dc153d0](https://linux-hardware.org/?probe=f75dc153d0) | Apr 13, 2022 |
| Medion        | X6816                       | Notebook    | [41350ad402](https://linux-hardware.org/?probe=41350ad402) | Apr 12, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [ac82d62350](https://linux-hardware.org/?probe=ac82d62350) | Apr 12, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [60a1fc5c39](https://linux-hardware.org/?probe=60a1fc5c39) | Apr 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [3930b32e77](https://linux-hardware.org/?probe=3930b32e77) | Apr 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [1e302e1cce](https://linux-hardware.org/?probe=1e302e1cce) | Apr 12, 2022 |
| TUXEDO        | P65xHP                      | Notebook    | [a29da5ce79](https://linux-hardware.org/?probe=a29da5ce79) | Apr 11, 2022 |
| Medion        | MS-7707                     | Desktop     | [fb95ae3a92](https://linux-hardware.org/?probe=fb95ae3a92) | Apr 09, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [8779ba2891](https://linux-hardware.org/?probe=8779ba2891) | Apr 09, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [298acab48c](https://linux-hardware.org/?probe=298acab48c) | Apr 08, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [0b5e11625d](https://linux-hardware.org/?probe=0b5e11625d) | Apr 08, 2022 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | Desktop     | [fa2e3ae8ee](https://linux-hardware.org/?probe=fa2e3ae8ee) | Apr 08, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fed3e90b10](https://linux-hardware.org/?probe=fed3e90b10) | Apr 08, 2022 |
| Lenovo        | ThinkPad L13 Yoga 20R500... | Convertible | [79304f2f1b](https://linux-hardware.org/?probe=79304f2f1b) | Apr 06, 2022 |
| HP            | Pavilion dv6                | Notebook    | [b69de03677](https://linux-hardware.org/?probe=b69de03677) | Apr 06, 2022 |
| HP            | Pavilion dv6                | Notebook    | [9e8312e9c1](https://linux-hardware.org/?probe=9e8312e9c1) | Apr 06, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0e254bc578](https://linux-hardware.org/?probe=0e254bc578) | Apr 05, 2022 |
| Medion        | E7216                       | Notebook    | [58f12f9e91](https://linux-hardware.org/?probe=58f12f9e91) | Apr 05, 2022 |
| ECS           | CMLU-MINI                   | Desktop     | [742c0da37b](https://linux-hardware.org/?probe=742c0da37b) | Apr 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [edf4c472c3](https://linux-hardware.org/?probe=edf4c472c3) | Apr 05, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [16d1981053](https://linux-hardware.org/?probe=16d1981053) | Apr 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [35e0c67fed](https://linux-hardware.org/?probe=35e0c67fed) | Apr 03, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [c0c1bedcec](https://linux-hardware.org/?probe=c0c1bedcec) | Apr 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS2B000    | Notebook    | [869407eb01](https://linux-hardware.org/?probe=869407eb01) | Apr 03, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0c57600526](https://linux-hardware.org/?probe=0c57600526) | Apr 03, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [26082e6921](https://linux-hardware.org/?probe=26082e6921) | Apr 02, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [0f191252cb](https://linux-hardware.org/?probe=0f191252cb) | Apr 02, 2022 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [590d188f5d](https://linux-hardware.org/?probe=590d188f5d) | Apr 01, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | Desktop     | [a9cf0523c2](https://linux-hardware.org/?probe=a9cf0523c2) | Mar 31, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [6cabffccbe](https://linux-hardware.org/?probe=6cabffccbe) | Mar 30, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Notebook      | NJ50_70CU                   | Notebook    | [ba5b62756b](https://linux-hardware.org/?probe=ba5b62756b) | Mar 29, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | Desktop     | [99acee5d56](https://linux-hardware.org/?probe=99acee5d56) | Mar 29, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [85a3c0a47e](https://linux-hardware.org/?probe=85a3c0a47e) | Mar 29, 2022 |
| Supermicro    | X11DPG-QTA                  | Server      | [dcbb3d117a](https://linux-hardware.org/?probe=dcbb3d117a) | Mar 29, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [8696148b4a](https://linux-hardware.org/?probe=8696148b4a) | Mar 29, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [a63052c272](https://linux-hardware.org/?probe=a63052c272) | Mar 29, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [973087697b](https://linux-hardware.org/?probe=973087697b) | Mar 28, 2022 |
| Supermicro    | X11DPG-QTA                  | Server      | [ac15801ad7](https://linux-hardware.org/?probe=ac15801ad7) | Mar 28, 2022 |
| Sony          | VPCEH2J1E                   | Notebook    | [23d5b99aca](https://linux-hardware.org/?probe=23d5b99aca) | Mar 27, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [c6fa89e81f](https://linux-hardware.org/?probe=c6fa89e81f) | Mar 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [76b97dcfe7](https://linux-hardware.org/?probe=76b97dcfe7) | Mar 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ec3089df82](https://linux-hardware.org/?probe=ec3089df82) | Mar 25, 2022 |
| Medion        | E6220                       | Notebook    | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| HP            | Pavilion dv7                | Notebook    | [64d5f14244](https://linux-hardware.org/?probe=64d5f14244) | Mar 22, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e2bfdae482](https://linux-hardware.org/?probe=e2bfdae482) | Mar 22, 2022 |
| Intel         | NUC9VXQNB K47179-402        | Mini pc     | [835e767bde](https://linux-hardware.org/?probe=835e767bde) | Mar 22, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [e8bbca6adf](https://linux-hardware.org/?probe=e8bbca6adf) | Mar 21, 2022 |
| Intel         | NUC9VXQNB K47179-402        | Mini pc     | [2cd178853b](https://linux-hardware.org/?probe=2cd178853b) | Mar 21, 2022 |
| Fujitsu Si... | AMILO Pro Edition V3545     | Notebook    | [be2c23f4a5](https://linux-hardware.org/?probe=be2c23f4a5) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Medion        | E14410                      | Notebook    | [800f98d1ef](https://linux-hardware.org/?probe=800f98d1ef) | Mar 21, 2022 |
| ASUSTek       | M3A32-MVP DELUXE            | Desktop     | [1bfef458ea](https://linux-hardware.org/?probe=1bfef458ea) | Mar 20, 2022 |
| Sony          | VPCEH2J1E                   | Notebook    | [ae54fc4033](https://linux-hardware.org/?probe=ae54fc4033) | Mar 19, 2022 |
| ASUSTek       | X201EP                      | Notebook    | [864fc80ac3](https://linux-hardware.org/?probe=864fc80ac3) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [d2b4181439](https://linux-hardware.org/?probe=d2b4181439) | Mar 16, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [f4c72eaa35](https://linux-hardware.org/?probe=f4c72eaa35) | Mar 15, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [192926e183](https://linux-hardware.org/?probe=192926e183) | Mar 14, 2022 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [fc992250ca](https://linux-hardware.org/?probe=fc992250ca) | Mar 13, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [9eb7577acd](https://linux-hardware.org/?probe=9eb7577acd) | Mar 12, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [8859888f0c](https://linux-hardware.org/?probe=8859888f0c) | Mar 12, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [1aa06e7b53](https://linux-hardware.org/?probe=1aa06e7b53) | Mar 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [e2eacd6969](https://linux-hardware.org/?probe=e2eacd6969) | Mar 12, 2022 |
| Lenovo        | ThinkPad E15 20RES12P00     | Notebook    | [200b3a0b69](https://linux-hardware.org/?probe=200b3a0b69) | Mar 12, 2022 |
| MSI           | H81M-P33                    | Desktop     | [0f103bcb15](https://linux-hardware.org/?probe=0f103bcb15) | Mar 12, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [f3d0e8fbea](https://linux-hardware.org/?probe=f3d0e8fbea) | Mar 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [304738db66](https://linux-hardware.org/?probe=304738db66) | Mar 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [adf7b6c95e](https://linux-hardware.org/?probe=adf7b6c95e) | Mar 10, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [4758b6520c](https://linux-hardware.org/?probe=4758b6520c) | Mar 10, 2022 |
| ASUSTek       | UX305FA                     | Notebook    | [f1641a436c](https://linux-hardware.org/?probe=f1641a436c) | Mar 09, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [6e46455791](https://linux-hardware.org/?probe=6e46455791) | Mar 09, 2022 |
| Sony          | VPCEH2J1E                   | Notebook    | [713f08757a](https://linux-hardware.org/?probe=713f08757a) | Mar 09, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [1949849d7e](https://linux-hardware.org/?probe=1949849d7e) | Mar 09, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [d6d94816fc](https://linux-hardware.org/?probe=d6d94816fc) | Mar 08, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [b2aeea55e5](https://linux-hardware.org/?probe=b2aeea55e5) | Mar 07, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [8e3573295d](https://linux-hardware.org/?probe=8e3573295d) | Mar 07, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [d57f5c8ce3](https://linux-hardware.org/?probe=d57f5c8ce3) | Mar 07, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [5183569327](https://linux-hardware.org/?probe=5183569327) | Mar 06, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [0f5c637f94](https://linux-hardware.org/?probe=0f5c637f94) | Mar 06, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [b78185d870](https://linux-hardware.org/?probe=b78185d870) | Mar 06, 2022 |
| Lenovo        | ThinkPad E580 20KS001RGE    | Notebook    | [4ccce94591](https://linux-hardware.org/?probe=4ccce94591) | Mar 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [e9b1f4c1ec](https://linux-hardware.org/?probe=e9b1f4c1ec) | Mar 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f378d8a1df](https://linux-hardware.org/?probe=f378d8a1df) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [359368d345](https://linux-hardware.org/?probe=359368d345) | Feb 26, 2022 |
| Toshiba       | Satellite L775-166          | Notebook    | [f0ad0a4da5](https://linux-hardware.org/?probe=f0ad0a4da5) | Feb 26, 2022 |
| BESSTAR Te... | UM200 V1.0                  | Desktop     | [bae5f3ad77](https://linux-hardware.org/?probe=bae5f3ad77) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [16281a52e8](https://linux-hardware.org/?probe=16281a52e8) | Feb 26, 2022 |
| Toshiba       | Satellite P500              | Notebook    | [980cb1d4af](https://linux-hardware.org/?probe=980cb1d4af) | Feb 25, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [6bf461797c](https://linux-hardware.org/?probe=6bf461797c) | Feb 25, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [7b9e3082bf](https://linux-hardware.org/?probe=7b9e3082bf) | Feb 25, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [cd0609e2cc](https://linux-hardware.org/?probe=cd0609e2cc) | Feb 25, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [f576f08ecb](https://linux-hardware.org/?probe=f576f08ecb) | Feb 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [64955f775b](https://linux-hardware.org/?probe=64955f775b) | Feb 24, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [916b00f114](https://linux-hardware.org/?probe=916b00f114) | Feb 24, 2022 |
| Lenovo        | IdeaPad S206 2638           | Notebook    | [84772cc34d](https://linux-hardware.org/?probe=84772cc34d) | Feb 23, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [851288ccf7](https://linux-hardware.org/?probe=851288ccf7) | Feb 22, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [82000c3346](https://linux-hardware.org/?probe=82000c3346) | Feb 22, 2022 |
| Dell          | 0C4Y3R A00                  | Server      | [3b0d723e31](https://linux-hardware.org/?probe=3b0d723e31) | Feb 21, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | Notebook    | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ad584de4c3](https://linux-hardware.org/?probe=ad584de4c3) | Feb 20, 2022 |
| Acer          | Aspire A517-51              | Notebook    | [997108b078](https://linux-hardware.org/?probe=997108b078) | Feb 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [803b4d504c](https://linux-hardware.org/?probe=803b4d504c) | Feb 19, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [ae83ee4d22](https://linux-hardware.org/?probe=ae83ee4d22) | Feb 19, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [c75a02af0d](https://linux-hardware.org/?probe=c75a02af0d) | Feb 18, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [84e32bec2d](https://linux-hardware.org/?probe=84e32bec2d) | Feb 18, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [3047069a4f](https://linux-hardware.org/?probe=3047069a4f) | Feb 17, 2022 |
| ASRock        | X299 Taichi XE              | Desktop     | [04a1425dca](https://linux-hardware.org/?probe=04a1425dca) | Feb 17, 2022 |
| ASRock        | X299 Taichi XE              | Desktop     | [45b82f5330](https://linux-hardware.org/?probe=45b82f5330) | Feb 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [934591472d](https://linux-hardware.org/?probe=934591472d) | Feb 16, 2022 |
| MSI           | Z270 GAMING PRO             | Desktop     | [6c6a916a0b](https://linux-hardware.org/?probe=6c6a916a0b) | Feb 15, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [701eeea0ed](https://linux-hardware.org/?probe=701eeea0ed) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [32022a8232](https://linux-hardware.org/?probe=32022a8232) | Feb 14, 2022 |
| Supermicro    | X11DPG-QTA                  | Server      | [2cdac4454d](https://linux-hardware.org/?probe=2cdac4454d) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [372c231b58](https://linux-hardware.org/?probe=372c231b58) | Feb 14, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [31d020671e](https://linux-hardware.org/?probe=31d020671e) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [4ff66e932f](https://linux-hardware.org/?probe=4ff66e932f) | Feb 13, 2022 |
| HP            | 3397                        | Desktop     | [8ea2c45260](https://linux-hardware.org/?probe=8ea2c45260) | Feb 13, 2022 |
| Lenovo        | ThinkPad X230T 34382AG      | Notebook    | [bec561800f](https://linux-hardware.org/?probe=bec561800f) | Feb 13, 2022 |
| Lenovo        | ThinkCentre A58 7515M6G     | Desktop     | [7b86a1d792](https://linux-hardware.org/?probe=7b86a1d792) | Feb 12, 2022 |
| HP            | 3397                        | Desktop     | [f92e367657](https://linux-hardware.org/?probe=f92e367657) | Feb 12, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [b229af38f0](https://linux-hardware.org/?probe=b229af38f0) | Feb 12, 2022 |
| HP            | ProBook 4730s               | Notebook    | [2a3ff15659](https://linux-hardware.org/?probe=2a3ff15659) | Feb 12, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [8231d95ddc](https://linux-hardware.org/?probe=8231d95ddc) | Feb 12, 2022 |
| Intel         | DH67GD AAG10206-202         | Desktop     | [56c802164a](https://linux-hardware.org/?probe=56c802164a) | Feb 11, 2022 |
| HP            | Compaq 15                   | Notebook    | [78b2f3bfa6](https://linux-hardware.org/?probe=78b2f3bfa6) | Feb 11, 2022 |
| HP            | 1494                        | Desktop     | [93502b8c70](https://linux-hardware.org/?probe=93502b8c70) | Feb 11, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [577fc1abce](https://linux-hardware.org/?probe=577fc1abce) | Feb 11, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [529666b867](https://linux-hardware.org/?probe=529666b867) | Feb 10, 2022 |
| ASRock        | H81M-HDS                    | Desktop     | [5f2ada50f9](https://linux-hardware.org/?probe=5f2ada50f9) | Feb 10, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [c83ca2e528](https://linux-hardware.org/?probe=c83ca2e528) | Feb 10, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [646a1296e0](https://linux-hardware.org/?probe=646a1296e0) | Feb 10, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [4706a4f369](https://linux-hardware.org/?probe=4706a4f369) | Feb 10, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [c945332cad](https://linux-hardware.org/?probe=c945332cad) | Feb 10, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [eb3836e9d0](https://linux-hardware.org/?probe=eb3836e9d0) | Feb 10, 2022 |
| Supermicro    | X11DPG-QTA                  | Server      | [75694b38b0](https://linux-hardware.org/?probe=75694b38b0) | Feb 10, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [d4e5b617c7](https://linux-hardware.org/?probe=d4e5b617c7) | Feb 10, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [88181832a0](https://linux-hardware.org/?probe=88181832a0) | Feb 09, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [9ff4906aa1](https://linux-hardware.org/?probe=9ff4906aa1) | Feb 09, 2022 |
| Fujitsu       | LIFEBOOK E559               | Notebook    | [66696218c1](https://linux-hardware.org/?probe=66696218c1) | Feb 09, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [435e9532a8](https://linux-hardware.org/?probe=435e9532a8) | Feb 09, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [454f14e47d](https://linux-hardware.org/?probe=454f14e47d) | Feb 09, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [42d5c28f38](https://linux-hardware.org/?probe=42d5c28f38) | Feb 09, 2022 |
| Medion        | P6402 MD60800               | Notebook    | [a749ba246d](https://linux-hardware.org/?probe=a749ba246d) | Feb 08, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [ab81e91207](https://linux-hardware.org/?probe=ab81e91207) | Feb 08, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [57c513ecbc](https://linux-hardware.org/?probe=57c513ecbc) | Feb 08, 2022 |
| Acer          | Predator G9-792             | Notebook    | [8404f2e6d1](https://linux-hardware.org/?probe=8404f2e6d1) | Feb 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [82d892f3e5](https://linux-hardware.org/?probe=82d892f3e5) | Feb 07, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [8b8eda08e4](https://linux-hardware.org/?probe=8b8eda08e4) | Feb 07, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [9f98143f82](https://linux-hardware.org/?probe=9f98143f82) | Feb 07, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | Notebook    | [8337edfc91](https://linux-hardware.org/?probe=8337edfc91) | Feb 07, 2022 |
| Acer          | TravelMate 5720             | Notebook    | [9db7cd9351](https://linux-hardware.org/?probe=9db7cd9351) | Feb 06, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f5da53181](https://linux-hardware.org/?probe=9f5da53181) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [d11fb8c7b6](https://linux-hardware.org/?probe=d11fb8c7b6) | Feb 04, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [caa9365785](https://linux-hardware.org/?probe=caa9365785) | Feb 04, 2022 |
| Sony          | VPCEH2J1E                   | Notebook    | [f5ed0cbaa4](https://linux-hardware.org/?probe=f5ed0cbaa4) | Feb 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [5a1723f28e](https://linux-hardware.org/?probe=5a1723f28e) | Feb 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [7db46606ab](https://linux-hardware.org/?probe=7db46606ab) | Feb 04, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [376503f06d](https://linux-hardware.org/?probe=376503f06d) | Feb 03, 2022 |
| HP            | ProBook 4310s               | Notebook    | [6d2a66aa1e](https://linux-hardware.org/?probe=6d2a66aa1e) | Feb 02, 2022 |
| Lenovo        | ThinkPad X280 20KF001GGE    | Notebook    | [f076061f22](https://linux-hardware.org/?probe=f076061f22) | Feb 02, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [3deec16346](https://linux-hardware.org/?probe=3deec16346) | Feb 02, 2022 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [ee91c21eb4](https://linux-hardware.org/?probe=ee91c21eb4) | Feb 01, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [172fc399f5](https://linux-hardware.org/?probe=172fc399f5) | Feb 01, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [440bc30637](https://linux-hardware.org/?probe=440bc30637) | Jan 31, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [dd2d541140](https://linux-hardware.org/?probe=dd2d541140) | Jan 31, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [b48601a549](https://linux-hardware.org/?probe=b48601a549) | Jan 31, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [b62cc09b63](https://linux-hardware.org/?probe=b62cc09b63) | Jan 30, 2022 |
| Dell          | XPS M1530                   | Notebook    | [4b402569cc](https://linux-hardware.org/?probe=4b402569cc) | Jan 29, 2022 |
| ASRock        | 970 Extreme4                | Desktop     | [f024dd97a0](https://linux-hardware.org/?probe=f024dd97a0) | Jan 29, 2022 |
| Acer          | Predator G9-792             | Notebook    | [863bce4abe](https://linux-hardware.org/?probe=863bce4abe) | Jan 28, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [d112bf0361](https://linux-hardware.org/?probe=d112bf0361) | Jan 27, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [16d9024680](https://linux-hardware.org/?probe=16d9024680) | Jan 26, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [132c3acbb1](https://linux-hardware.org/?probe=132c3acbb1) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [124dcb4c34](https://linux-hardware.org/?probe=124dcb4c34) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [804f9dbb94](https://linux-hardware.org/?probe=804f9dbb94) | Jan 26, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [dfe4dda46b](https://linux-hardware.org/?probe=dfe4dda46b) | Jan 26, 2022 |
| Dell          | Precision 5510              | Notebook    | [511eeac9a0](https://linux-hardware.org/?probe=511eeac9a0) | Jan 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5edb2eb3](https://linux-hardware.org/?probe=4d5edb2eb3) | Jan 25, 2022 |
| Lenovo        | ThinkPad T495 20NJS0KB00    | Notebook    | [e92c44b58a](https://linux-hardware.org/?probe=e92c44b58a) | Jan 24, 2022 |
| Dell          | Inspiron 1720               | Notebook    | [0b6d89660a](https://linux-hardware.org/?probe=0b6d89660a) | Jan 24, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [94fe829346](https://linux-hardware.org/?probe=94fe829346) | Jan 24, 2022 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [46a5cef815](https://linux-hardware.org/?probe=46a5cef815) | Jan 23, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [619b081f40](https://linux-hardware.org/?probe=619b081f40) | Jan 23, 2022 |
| Lenovo        | ThinkPad T560 20FJS2PN00    | Notebook    | [e9f3d5c785](https://linux-hardware.org/?probe=e9f3d5c785) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [635e361ebb](https://linux-hardware.org/?probe=635e361ebb) | Jan 22, 2022 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [e19ee364b0](https://linux-hardware.org/?probe=e19ee364b0) | Jan 21, 2022 |
| HP            | 1998                        | Desktop     | [422b7b3f1c](https://linux-hardware.org/?probe=422b7b3f1c) | Jan 21, 2022 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [a0399b1c6b](https://linux-hardware.org/?probe=a0399b1c6b) | Jan 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [0410ba28b0](https://linux-hardware.org/?probe=0410ba28b0) | Jan 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [24c10d9f2d](https://linux-hardware.org/?probe=24c10d9f2d) | Jan 20, 2022 |
| Supermicro    | X11SAE                      | Server      | [79e6eafc82](https://linux-hardware.org/?probe=79e6eafc82) | Jan 20, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [f45a7eb0bb](https://linux-hardware.org/?probe=f45a7eb0bb) | Jan 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0aab49a3e3](https://linux-hardware.org/?probe=0aab49a3e3) | Jan 20, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [7ea8fc4686](https://linux-hardware.org/?probe=7ea8fc4686) | Jan 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [5ba89b6e26](https://linux-hardware.org/?probe=5ba89b6e26) | Jan 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [fca800793f](https://linux-hardware.org/?probe=fca800793f) | Jan 18, 2022 |
| Lenovo        | ThinkPad T560 20FJS2PN00    | Notebook    | [11340212f2](https://linux-hardware.org/?probe=11340212f2) | Jan 18, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [d089029f6c](https://linux-hardware.org/?probe=d089029f6c) | Jan 18, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [b8d4a9ee87](https://linux-hardware.org/?probe=b8d4a9ee87) | Jan 17, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [566e943f08](https://linux-hardware.org/?probe=566e943f08) | Jan 16, 2022 |
| Lenovo        | ThinkPad X230 2325WR3       | Notebook    | [decbecce89](https://linux-hardware.org/?probe=decbecce89) | Jan 16, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | Notebook    | [dd69f44bab](https://linux-hardware.org/?probe=dd69f44bab) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6438d5a5af](https://linux-hardware.org/?probe=6438d5a5af) | Jan 15, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [8545fedf93](https://linux-hardware.org/?probe=8545fedf93) | Jan 14, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [9404914df6](https://linux-hardware.org/?probe=9404914df6) | Jan 13, 2022 |
| Medion        | CRAWLER E10                 | Notebook    | [d658e7cd88](https://linux-hardware.org/?probe=d658e7cd88) | Jan 13, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [118b411a8c](https://linux-hardware.org/?probe=118b411a8c) | Jan 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [960bd82b34](https://linux-hardware.org/?probe=960bd82b34) | Jan 11, 2022 |
| MSI           | B360M PRO-VDH               | Desktop     | [bd136c19e0](https://linux-hardware.org/?probe=bd136c19e0) | Jan 10, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [67ab65d5f0](https://linux-hardware.org/?probe=67ab65d5f0) | Jan 10, 2022 |
| HP            | EliteBook 1030 G1           | Notebook    | [73839f5dd5](https://linux-hardware.org/?probe=73839f5dd5) | Jan 09, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [f212038b15](https://linux-hardware.org/?probe=f212038b15) | Jan 09, 2022 |
| HP            | Compaq 8510p                | Notebook    | [94c5350957](https://linux-hardware.org/?probe=94c5350957) | Jan 09, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [c5d880e138](https://linux-hardware.org/?probe=c5d880e138) | Jan 09, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [dc436bb38c](https://linux-hardware.org/?probe=dc436bb38c) | Jan 08, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [28db094e56](https://linux-hardware.org/?probe=28db094e56) | Jan 08, 2022 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | Notebook    | [2dbdfe4883](https://linux-hardware.org/?probe=2dbdfe4883) | Jan 08, 2022 |
| Dell          | Vostro 5370                 | Notebook    | [0d027d4b84](https://linux-hardware.org/?probe=0d027d4b84) | Jan 07, 2022 |
| Dell          | Precision 5510              | Notebook    | [7a763a42bb](https://linux-hardware.org/?probe=7a763a42bb) | Jan 07, 2022 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [9333fdb2cc](https://linux-hardware.org/?probe=9333fdb2cc) | Jan 06, 2022 |
| ASUSTek       | P8B-M Series                | Server      | [8a2fb874fe](https://linux-hardware.org/?probe=8a2fb874fe) | Jan 06, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [fee6068743](https://linux-hardware.org/?probe=fee6068743) | Jan 05, 2022 |
| Dell          | Latitude E6520              | Notebook    | [f9c32b0bee](https://linux-hardware.org/?probe=f9c32b0bee) | Jan 05, 2022 |
| Dell          | Latitude E7440              | Notebook    | [c8811522dd](https://linux-hardware.org/?probe=c8811522dd) | Jan 05, 2022 |
| Dell          | Latitude E5550              | Notebook    | [8956b15ec8](https://linux-hardware.org/?probe=8956b15ec8) | Jan 04, 2022 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [a5ce28f08f](https://linux-hardware.org/?probe=a5ce28f08f) | Jan 04, 2022 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [2befa53304](https://linux-hardware.org/?probe=2befa53304) | Jan 04, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [c3ddad9a30](https://linux-hardware.org/?probe=c3ddad9a30) | Jan 03, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [a321b2cfd9](https://linux-hardware.org/?probe=a321b2cfd9) | Jan 03, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [6130b11204](https://linux-hardware.org/?probe=6130b11204) | Jan 03, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| TUXEDO        | P65_67HSHP                  | Notebook    | [4d448637c0](https://linux-hardware.org/?probe=4d448637c0) | Jan 02, 2022 |
| ASUSTek       | N50Vn                       | Notebook    | [8fadb8c7af](https://linux-hardware.org/?probe=8fadb8c7af) | Jan 01, 2022 |
| Lenovo        | ThinkPad T440s 20ARS05V0... | Notebook    | [7c496e685d](https://linux-hardware.org/?probe=7c496e685d) | Dec 31, 2021 |
| ASRock        | X370 Killer SLI             | Desktop     | [7c10b6f7ae](https://linux-hardware.org/?probe=7c10b6f7ae) | Dec 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [cbe80d8c24](https://linux-hardware.org/?probe=cbe80d8c24) | Dec 30, 2021 |
| Dell          | 051FJ8 A02                  | Desktop     | [8cc53ce548](https://linux-hardware.org/?probe=8cc53ce548) | Dec 30, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [5095c47f07](https://linux-hardware.org/?probe=5095c47f07) | Dec 29, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [829dc5243a](https://linux-hardware.org/?probe=829dc5243a) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5d91acd13d](https://linux-hardware.org/?probe=5d91acd13d) | Dec 27, 2021 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [59a5f5e5c1](https://linux-hardware.org/?probe=59a5f5e5c1) | Dec 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [1724d0d357](https://linux-hardware.org/?probe=1724d0d357) | Dec 26, 2021 |
| HP            | ProBook 470 G1              | Notebook    | [0e99096fe2](https://linux-hardware.org/?probe=0e99096fe2) | Dec 26, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [fe87929ac5](https://linux-hardware.org/?probe=fe87929ac5) | Dec 26, 2021 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [536788561f](https://linux-hardware.org/?probe=536788561f) | Dec 26, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [cb2ae92d82](https://linux-hardware.org/?probe=cb2ae92d82) | Dec 25, 2021 |
| Gigabyte      | Z170N-WIFI-CF               | Desktop     | [9bcfc1e034](https://linux-hardware.org/?probe=9bcfc1e034) | Dec 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [492fc37142](https://linux-hardware.org/?probe=492fc37142) | Dec 22, 2021 |
| ASUSTek       | PN41                        | Mini pc     | [26a7b7f737](https://linux-hardware.org/?probe=26a7b7f737) | Dec 22, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [d7f3d69923](https://linux-hardware.org/?probe=d7f3d69923) | Dec 21, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [59ec7afd71](https://linux-hardware.org/?probe=59ec7afd71) | Dec 20, 2021 |
| ASUSTek       | GL702ZC                     | Notebook    | [ff27d21705](https://linux-hardware.org/?probe=ff27d21705) | Dec 20, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6653477f61](https://linux-hardware.org/?probe=6653477f61) | Dec 18, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [b3d411a4d7](https://linux-hardware.org/?probe=b3d411a4d7) | Dec 18, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [c4b9060346](https://linux-hardware.org/?probe=c4b9060346) | Dec 18, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [a8713c0bd9](https://linux-hardware.org/?probe=a8713c0bd9) | Dec 18, 2021 |
| ASUSTek       | M4A77                       | Desktop     | [4231ac26aa](https://linux-hardware.org/?probe=4231ac26aa) | Dec 17, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [175dda01f6](https://linux-hardware.org/?probe=175dda01f6) | Dec 15, 2021 |
| MSI           | Modern 14 B10MW             | Notebook    | [1771ceeb4e](https://linux-hardware.org/?probe=1771ceeb4e) | Dec 14, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9fce8b9430](https://linux-hardware.org/?probe=9fce8b9430) | Dec 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bd4a0c5d2f](https://linux-hardware.org/?probe=bd4a0c5d2f) | Dec 12, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [eef9ef9d60](https://linux-hardware.org/?probe=eef9ef9d60) | Dec 12, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [c33bc12a7a](https://linux-hardware.org/?probe=c33bc12a7a) | Dec 11, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [d5ec843ea7](https://linux-hardware.org/?probe=d5ec843ea7) | Dec 11, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [aaab078915](https://linux-hardware.org/?probe=aaab078915) | Dec 11, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [ec9930ae99](https://linux-hardware.org/?probe=ec9930ae99) | Dec 11, 2021 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [f2bfaaf185](https://linux-hardware.org/?probe=f2bfaaf185) | Dec 11, 2021 |
| Hardkernel    | ODROID-C4                   | Soc         | [3bd9548bab](https://linux-hardware.org/?probe=3bd9548bab) | Dec 10, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [89dd614f98](https://linux-hardware.org/?probe=89dd614f98) | Dec 09, 2021 |
| Dell          | XPS M1530                   | Notebook    | [ad4bfb0cbd](https://linux-hardware.org/?probe=ad4bfb0cbd) | Dec 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [9dd21ffaf4](https://linux-hardware.org/?probe=9dd21ffaf4) | Dec 08, 2021 |
| Acer          | Aspire XC-605               | Desktop     | [770f6167f6](https://linux-hardware.org/?probe=770f6167f6) | Dec 08, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [01b9229bd4](https://linux-hardware.org/?probe=01b9229bd4) | Dec 08, 2021 |
| Medion        | P7624                       | Notebook    | [05d0f23734](https://linux-hardware.org/?probe=05d0f23734) | Dec 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [9e9e0598b6](https://linux-hardware.org/?probe=9e9e0598b6) | Dec 07, 2021 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [600faccbe5](https://linux-hardware.org/?probe=600faccbe5) | Dec 07, 2021 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [06a415755c](https://linux-hardware.org/?probe=06a415755c) | Dec 06, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [d2704f29ec](https://linux-hardware.org/?probe=d2704f29ec) | Dec 06, 2021 |
| ASUSTek       | P9X79-E WS                  | Desktop     | [b65be23e52](https://linux-hardware.org/?probe=b65be23e52) | Dec 06, 2021 |
| Khadas        | VIM3                        | Soc         | [a1512911df](https://linux-hardware.org/?probe=a1512911df) | Dec 06, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [9ad6409a34](https://linux-hardware.org/?probe=9ad6409a34) | Dec 06, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [0d989a4f1f](https://linux-hardware.org/?probe=0d989a4f1f) | Dec 05, 2021 |
| ASRockRack    | C3558D4I-4L                 | Desktop     | [d563eb82ae](https://linux-hardware.org/?probe=d563eb82ae) | Dec 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c91db7e021](https://linux-hardware.org/?probe=c91db7e021) | Dec 04, 2021 |
| Sony          | SVF1532Z1EB                 | Notebook    | [d65626b69d](https://linux-hardware.org/?probe=d65626b69d) | Dec 04, 2021 |
| Lenovo        | ThinkPad W520 42844LG       | Notebook    | [cd254ead05](https://linux-hardware.org/?probe=cd254ead05) | Dec 04, 2021 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [ca35105e1a](https://linux-hardware.org/?probe=ca35105e1a) | Dec 04, 2021 |
| HP            | 21D0                        | Desktop     | [50548c11b7](https://linux-hardware.org/?probe=50548c11b7) | Dec 04, 2021 |
| HP            | ProBook 470 G1              | Notebook    | [4359617795](https://linux-hardware.org/?probe=4359617795) | Dec 03, 2021 |
| Lenovo        | ThinkPad Edge E330 33549... | Notebook    | [d8c1e34c94](https://linux-hardware.org/?probe=d8c1e34c94) | Dec 02, 2021 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [6204315459](https://linux-hardware.org/?probe=6204315459) | Dec 02, 2021 |
| HP            | Pavilion dv6                | Notebook    | [640e1f0491](https://linux-hardware.org/?probe=640e1f0491) | Dec 01, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [e6f6525ecd](https://linux-hardware.org/?probe=e6f6525ecd) | Dec 01, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [d77b252a78](https://linux-hardware.org/?probe=d77b252a78) | Dec 01, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [c77012b538](https://linux-hardware.org/?probe=c77012b538) | Nov 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a1669a775b](https://linux-hardware.org/?probe=a1669a775b) | Nov 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [0d42fdd2bf](https://linux-hardware.org/?probe=0d42fdd2bf) | Nov 30, 2021 |
| HP            | 625                         | Notebook    | [75b1dd3ee1](https://linux-hardware.org/?probe=75b1dd3ee1) | Nov 29, 2021 |
| Medion        | MS-7748                     | Desktop     | [bb473ca5d8](https://linux-hardware.org/?probe=bb473ca5d8) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [f6ab5c54f6](https://linux-hardware.org/?probe=f6ab5c54f6) | Nov 27, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [b9c1906f2b](https://linux-hardware.org/?probe=b9c1906f2b) | Nov 26, 2021 |
| Khadas        | VIM3                        | Soc         | [0a4e689e9c](https://linux-hardware.org/?probe=0a4e689e9c) | Nov 25, 2021 |
| Medion        | P15648                      | Notebook    | [1328e63002](https://linux-hardware.org/?probe=1328e63002) | Nov 25, 2021 |
| Dell          | 0T7D40 A01                  | Desktop     | [065636c444](https://linux-hardware.org/?probe=065636c444) | Nov 25, 2021 |
| MSI           | A78M-E35                    | Desktop     | [999bbc1197](https://linux-hardware.org/?probe=999bbc1197) | Nov 24, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [5632c40eac](https://linux-hardware.org/?probe=5632c40eac) | Nov 24, 2021 |
| Acer          | Revo 70                     | Desktop     | [f5cdb95334](https://linux-hardware.org/?probe=f5cdb95334) | Nov 24, 2021 |
| Acer          | Revo 70                     | Desktop     | [4c99b6ac71](https://linux-hardware.org/?probe=4c99b6ac71) | Nov 24, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c8b8a8bed7](https://linux-hardware.org/?probe=c8b8a8bed7) | Nov 24, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [1cce90a2eb](https://linux-hardware.org/?probe=1cce90a2eb) | Nov 23, 2021 |
| HP            | Pavilion g7                 | Notebook    | [fab49120f0](https://linux-hardware.org/?probe=fab49120f0) | Nov 23, 2021 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [56cd58b089](https://linux-hardware.org/?probe=56cd58b089) | Nov 23, 2021 |
| TrekStor      | Primetab T13B               | Tablet      | [59de544e38](https://linux-hardware.org/?probe=59de544e38) | Nov 23, 2021 |
| TrekStor      | Primetab T13B               | Tablet      | [19b9435dff](https://linux-hardware.org/?probe=19b9435dff) | Nov 23, 2021 |
| ASUSTek       | X751SA                      | Notebook    | [d19fd8c59f](https://linux-hardware.org/?probe=d19fd8c59f) | Nov 22, 2021 |
| MSI           | GF72 7RE                    | Notebook    | [8e48a382b9](https://linux-hardware.org/?probe=8e48a382b9) | Nov 21, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f865c0e9f8](https://linux-hardware.org/?probe=f865c0e9f8) | Nov 20, 2021 |
| HP            | ENVY 15                     | Notebook    | [f4752615c9](https://linux-hardware.org/?probe=f4752615c9) | Nov 19, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S6S... | Notebook    | [73b9b15b14](https://linux-hardware.org/?probe=73b9b15b14) | Nov 19, 2021 |
| HP            | 0AECh D                     | Desktop     | [c81bcc92ca](https://linux-hardware.org/?probe=c81bcc92ca) | Nov 19, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b4975d2237](https://linux-hardware.org/?probe=b4975d2237) | Nov 19, 2021 |
| Lenovo        | ThinkPad P50 20EQS15P00     | Notebook    | [4c9b03387c](https://linux-hardware.org/?probe=4c9b03387c) | Nov 18, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [7052b7628f](https://linux-hardware.org/?probe=7052b7628f) | Nov 18, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0178a25382](https://linux-hardware.org/?probe=0178a25382) | Nov 18, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [9e8fd0520d](https://linux-hardware.org/?probe=9e8fd0520d) | Nov 18, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [915853adf6](https://linux-hardware.org/?probe=915853adf6) | Nov 18, 2021 |
| ASUSTek       | P7P55D EVO                  | Desktop     | [f453f8d58d](https://linux-hardware.org/?probe=f453f8d58d) | Nov 18, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [cd32f937e9](https://linux-hardware.org/?probe=cd32f937e9) | Nov 17, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [79eb5a8344](https://linux-hardware.org/?probe=79eb5a8344) | Nov 16, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [348b6bc909](https://linux-hardware.org/?probe=348b6bc909) | Nov 16, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [1976dd6a72](https://linux-hardware.org/?probe=1976dd6a72) | Nov 14, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [1e333032a4](https://linux-hardware.org/?probe=1e333032a4) | Nov 14, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [039fb54354](https://linux-hardware.org/?probe=039fb54354) | Nov 12, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c34d10b1c8](https://linux-hardware.org/?probe=c34d10b1c8) | Nov 12, 2021 |
| ASRock        | P67 Pro3                    | Desktop     | [17c9af356a](https://linux-hardware.org/?probe=17c9af356a) | Nov 08, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [37f9ff3c0b](https://linux-hardware.org/?probe=37f9ff3c0b) | Nov 07, 2021 |
| Sony          | VPCEH2J1E                   | Notebook    | [02a4a3ea01](https://linux-hardware.org/?probe=02a4a3ea01) | Nov 06, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [f0d8cb68f0](https://linux-hardware.org/?probe=f0d8cb68f0) | Nov 06, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f4273d4dc1](https://linux-hardware.org/?probe=f4273d4dc1) | Nov 06, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [86f7bd9873](https://linux-hardware.org/?probe=86f7bd9873) | Nov 06, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [32aedc2d5b](https://linux-hardware.org/?probe=32aedc2d5b) | Nov 05, 2021 |
| Lenovo        | G500s 20245                 | Notebook    | [e16940fe24](https://linux-hardware.org/?probe=e16940fe24) | Nov 05, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [5cea4f8e91](https://linux-hardware.org/?probe=5cea4f8e91) | Nov 04, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6f7e1ba1c1](https://linux-hardware.org/?probe=6f7e1ba1c1) | Nov 04, 2021 |
| Medion        | E6220                       | Notebook    | [45d5f5ec30](https://linux-hardware.org/?probe=45d5f5ec30) | Nov 04, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [80cfec46fc](https://linux-hardware.org/?probe=80cfec46fc) | Nov 03, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [267a4603eb](https://linux-hardware.org/?probe=267a4603eb) | Nov 02, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [2970522382](https://linux-hardware.org/?probe=2970522382) | Nov 01, 2021 |
| Apple         | Mac-F2218FC8                | All in one  | [692df23ac8](https://linux-hardware.org/?probe=692df23ac8) | Nov 01, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [500411363b](https://linux-hardware.org/?probe=500411363b) | Nov 01, 2021 |
| Panasonic     | FZG1-3                      | Notebook    | [8a52b831d7](https://linux-hardware.org/?probe=8a52b831d7) | Oct 31, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [ba228b1ed7](https://linux-hardware.org/?probe=ba228b1ed7) | Oct 31, 2021 |
| TrekStor      | Primetab T13B               | Tablet      | [6121781d85](https://linux-hardware.org/?probe=6121781d85) | Oct 30, 2021 |
| Medion        | Akoya S4220 MD99660         | Notebook    | [fd406382b2](https://linux-hardware.org/?probe=fd406382b2) | Oct 30, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [0c865ddf24](https://linux-hardware.org/?probe=0c865ddf24) | Oct 30, 2021 |
| Dell          | Latitude 5490               | Notebook    | [4efdbaeea5](https://linux-hardware.org/?probe=4efdbaeea5) | Oct 30, 2021 |
| Gigabyte      | P55M-UD2                    | Desktop     | [b14c0e8dd2](https://linux-hardware.org/?probe=b14c0e8dd2) | Oct 29, 2021 |
| MSI           | A78M-E35                    | Desktop     | [69da26c946](https://linux-hardware.org/?probe=69da26c946) | Oct 29, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [2b361b1035](https://linux-hardware.org/?probe=2b361b1035) | Oct 28, 2021 |
| ASUSTek       | M11BB                       | Desktop     | [c049f2b753](https://linux-hardware.org/?probe=c049f2b753) | Oct 28, 2021 |
| Acer          | Aspire A317-33              | Notebook    | [ad0f3b8799](https://linux-hardware.org/?probe=ad0f3b8799) | Oct 24, 2021 |
| Acer          | TravelMate P253             | Notebook    | [d74c10f41f](https://linux-hardware.org/?probe=d74c10f41f) | Oct 24, 2021 |
| Medion        | E7216                       | Notebook    | [f4c7def4b7](https://linux-hardware.org/?probe=f4c7def4b7) | Oct 24, 2021 |
| Acer          | FIH57                       | Desktop     | [719b6ffbe5](https://linux-hardware.org/?probe=719b6ffbe5) | Oct 24, 2021 |
| Medion        | P7624                       | Notebook    | [efc2ccc6a2](https://linux-hardware.org/?probe=efc2ccc6a2) | Oct 24, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [0e913d2884](https://linux-hardware.org/?probe=0e913d2884) | Oct 23, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [6954277377](https://linux-hardware.org/?probe=6954277377) | Oct 23, 2021 |
| MSI           | Modern 14 B10MW             | Notebook    | [ae43e74753](https://linux-hardware.org/?probe=ae43e74753) | Oct 21, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5b605bad97](https://linux-hardware.org/?probe=5b605bad97) | Oct 20, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b054e02856](https://linux-hardware.org/?probe=b054e02856) | Oct 20, 2021 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [2c5d786879](https://linux-hardware.org/?probe=2c5d786879) | Oct 20, 2021 |
| Lenovo        | ThinkPad T440s 20AQS0090... | Notebook    | [415cc7fe56](https://linux-hardware.org/?probe=415cc7fe56) | Oct 18, 2021 |
| HP            | Pavilion dv6                | Notebook    | [0392f507d0](https://linux-hardware.org/?probe=0392f507d0) | Oct 18, 2021 |
| Intel         | D54250WYK H13922-303        | Desktop     | [21b715e26a](https://linux-hardware.org/?probe=21b715e26a) | Oct 17, 2021 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [b1c4af0594](https://linux-hardware.org/?probe=b1c4af0594) | Oct 17, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [ae1729d840](https://linux-hardware.org/?probe=ae1729d840) | Oct 15, 2021 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [61d5829888](https://linux-hardware.org/?probe=61d5829888) | Oct 14, 2021 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [c42ff576c7](https://linux-hardware.org/?probe=c42ff576c7) | Oct 14, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [7555392d34](https://linux-hardware.org/?probe=7555392d34) | Oct 14, 2021 |
| Teclast       | F5                          | Convertible | [e4fb415516](https://linux-hardware.org/?probe=e4fb415516) | Oct 13, 2021 |
| Medion        | P15648                      | Notebook    | [5ea319450e](https://linux-hardware.org/?probe=5ea319450e) | Oct 13, 2021 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [3968e39b0b](https://linux-hardware.org/?probe=3968e39b0b) | Oct 12, 2021 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1e047e7a9a](https://linux-hardware.org/?probe=1e047e7a9a) | Oct 12, 2021 |
| ASUSTek       | N61Jv                       | Notebook    | [0e300bafe8](https://linux-hardware.org/?probe=0e300bafe8) | Oct 12, 2021 |
| theobroma-... | puma_rk3399                 | Soc         | [16d3c3d359](https://linux-hardware.org/?probe=16d3c3d359) | Oct 11, 2021 |
| theobroma-... | puma_rk3399                 | Soc         | [64aa8d06f4](https://linux-hardware.org/?probe=64aa8d06f4) | Oct 11, 2021 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [eee2a960f5](https://linux-hardware.org/?probe=eee2a960f5) | Oct 11, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4054b4ec35](https://linux-hardware.org/?probe=4054b4ec35) | Oct 11, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [037a558c7d](https://linux-hardware.org/?probe=037a558c7d) | Oct 11, 2021 |
| HP            | 8906 SMVB                   | Desktop     | [8fca5ef20e](https://linux-hardware.org/?probe=8fca5ef20e) | Oct 11, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [971cdf3ab8](https://linux-hardware.org/?probe=971cdf3ab8) | Oct 11, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [d01c751c63](https://linux-hardware.org/?probe=d01c751c63) | Oct 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [1984f59bbe](https://linux-hardware.org/?probe=1984f59bbe) | Oct 10, 2021 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [719e7db7f5](https://linux-hardware.org/?probe=719e7db7f5) | Oct 09, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [d3c72411ee](https://linux-hardware.org/?probe=d3c72411ee) | Oct 09, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [a631c78255](https://linux-hardware.org/?probe=a631c78255) | Oct 09, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [b6715f92f7](https://linux-hardware.org/?probe=b6715f92f7) | Oct 08, 2021 |
| Dell          | Latitude E5550              | Notebook    | [a4f8896675](https://linux-hardware.org/?probe=a4f8896675) | Oct 07, 2021 |
| HP            | 212B                        | Desktop     | [a4318b7064](https://linux-hardware.org/?probe=a4318b7064) | Oct 06, 2021 |
| Medion        | E6415 MD99904               | Notebook    | [4b24e7fb1a](https://linux-hardware.org/?probe=4b24e7fb1a) | Oct 06, 2021 |
| HP            | Elite Dragonfly             | Convertible | [48cabedb1e](https://linux-hardware.org/?probe=48cabedb1e) | Oct 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [572e073021](https://linux-hardware.org/?probe=572e073021) | Oct 04, 2021 |
| Lenovo        | ThinkPad L390 20NUS01W00    | Convertible | [880201a9eb](https://linux-hardware.org/?probe=880201a9eb) | Oct 04, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [8f7011b085](https://linux-hardware.org/?probe=8f7011b085) | Oct 03, 2021 |
| ASUSTek       | X556UQK                     | Notebook    | [363c1a3642](https://linux-hardware.org/?probe=363c1a3642) | Oct 03, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [3c24d27d51](https://linux-hardware.org/?probe=3c24d27d51) | Oct 02, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [b6eca9083a](https://linux-hardware.org/?probe=b6eca9083a) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [415f0d9244](https://linux-hardware.org/?probe=415f0d9244) | Oct 01, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [2a4757a98f](https://linux-hardware.org/?probe=2a4757a98f) | Sep 30, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [a7e79f067e](https://linux-hardware.org/?probe=a7e79f067e) | Sep 30, 2021 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [4502947e1a](https://linux-hardware.org/?probe=4502947e1a) | Sep 30, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [f107c84c00](https://linux-hardware.org/?probe=f107c84c00) | Sep 30, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [0b2f645654](https://linux-hardware.org/?probe=0b2f645654) | Sep 30, 2021 |
| TrekStor      | SurfTab wintron 7.0 ST70... | Notebook    | [c63b30f0df](https://linux-hardware.org/?probe=c63b30f0df) | Sep 29, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [0aef47a401](https://linux-hardware.org/?probe=0aef47a401) | Sep 29, 2021 |
| TUXEDO        | Book BA1510                 | Notebook    | [e408c8fb46](https://linux-hardware.org/?probe=e408c8fb46) | Sep 28, 2021 |
| Acer          | Aspire ES1-332              | Notebook    | [ae6c812e4c](https://linux-hardware.org/?probe=ae6c812e4c) | Sep 28, 2021 |
| Acer          | Aspire ES1-332              | Notebook    | [6bbaec4cfc](https://linux-hardware.org/?probe=6bbaec4cfc) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [4850590ac5](https://linux-hardware.org/?probe=4850590ac5) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [e7f361c688](https://linux-hardware.org/?probe=e7f361c688) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [61fb50bdf0](https://linux-hardware.org/?probe=61fb50bdf0) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [17bef7f4cf](https://linux-hardware.org/?probe=17bef7f4cf) | Sep 27, 2021 |
| ASUSTek       | P9D-X Series                | Server      | [fec09c0bac](https://linux-hardware.org/?probe=fec09c0bac) | Sep 27, 2021 |
| ASUSTek       | P9D-X Series                | Server      | [5062e6e567](https://linux-hardware.org/?probe=5062e6e567) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3b68a00361](https://linux-hardware.org/?probe=3b68a00361) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| MSI           | 790FX-GD70                  | Desktop     | [ba5f2949aa](https://linux-hardware.org/?probe=ba5f2949aa) | Sep 26, 2021 |
| Lenovo        | N23 80UR                    | Convertible | [04e375292d](https://linux-hardware.org/?probe=04e375292d) | Sep 25, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e3cd7dfeba](https://linux-hardware.org/?probe=e3cd7dfeba) | Sep 25, 2021 |
| Dell          | Latitude E7450              | Notebook    | [f600127ab1](https://linux-hardware.org/?probe=f600127ab1) | Sep 24, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e7f05eafc3](https://linux-hardware.org/?probe=e7f05eafc3) | Sep 22, 2021 |
| Lenovo        | B575e 368523G               | Notebook    | [f795bbcedc](https://linux-hardware.org/?probe=f795bbcedc) | Sep 22, 2021 |
| HP            | Compaq nc6400 (EH522AV)     | Notebook    | [8e613adf36](https://linux-hardware.org/?probe=8e613adf36) | Sep 22, 2021 |
| Apple         | MacBookPro15,1              | Notebook    | [3a3ccf8143](https://linux-hardware.org/?probe=3a3ccf8143) | Sep 21, 2021 |
| Gigabyte      | Z590 D                      | Desktop     | [97c779cffc](https://linux-hardware.org/?probe=97c779cffc) | Sep 20, 2021 |
| TUXEDO        | N130BU                      | Notebook    | [12a72404ea](https://linux-hardware.org/?probe=12a72404ea) | Sep 18, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [369e99699a](https://linux-hardware.org/?probe=369e99699a) | Sep 18, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [318f8d1653](https://linux-hardware.org/?probe=318f8d1653) | Sep 18, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [83649103a6](https://linux-hardware.org/?probe=83649103a6) | Sep 18, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [ee40317007](https://linux-hardware.org/?probe=ee40317007) | Sep 18, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [ae610c34e9](https://linux-hardware.org/?probe=ae610c34e9) | Sep 16, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [385fd35a7e](https://linux-hardware.org/?probe=385fd35a7e) | Sep 16, 2021 |
| Samsung       | 950QDB                      | Convertible | [607bfba560](https://linux-hardware.org/?probe=607bfba560) | Sep 16, 2021 |
| TUXEDO        | Book BA1510                 | Notebook    | [2397ee987d](https://linux-hardware.org/?probe=2397ee987d) | Sep 15, 2021 |
| Apple         | MacBookPro15,1              | Notebook    | [73bab0d19c](https://linux-hardware.org/?probe=73bab0d19c) | Sep 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [5fb084ffa4](https://linux-hardware.org/?probe=5fb084ffa4) | Sep 15, 2021 |
| ASUSTek       | P5K-VM                      | Desktop     | [59fc10448f](https://linux-hardware.org/?probe=59fc10448f) | Sep 14, 2021 |
| Lenovo        | ThinkPad E580 20KS0039GE    | Notebook    | [d85ddde9ba](https://linux-hardware.org/?probe=d85ddde9ba) | Sep 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [216f21f8d5](https://linux-hardware.org/?probe=216f21f8d5) | Sep 13, 2021 |
| Dell          | Precision 5540              | Notebook    | [2888ae8d0a](https://linux-hardware.org/?probe=2888ae8d0a) | Sep 13, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [0d4ac42f55](https://linux-hardware.org/?probe=0d4ac42f55) | Sep 13, 2021 |
| MSI           | Z170-A PRO                  | Desktop     | [5b702a6c05](https://linux-hardware.org/?probe=5b702a6c05) | Sep 12, 2021 |
| ASUSTek       | G750JX                      | Notebook    | [185445c775](https://linux-hardware.org/?probe=185445c775) | Sep 12, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Austria/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 255       | 14.78%  |
| Ubuntu 18.04                 | 125       | 7.25%   |
| Ubuntu 22.04                 | 74        | 4.29%   |
| OpenMandriva 4.3             | 52        | 3.01%   |
| Arch                         | 46        | 2.67%   |
| Arch Rolling                 | 43        | 2.49%   |
| Linux Mint 20.2              | 42        | 2.43%   |
| OpenMandriva 4.2             | 40        | 2.32%   |
| Debian 11                    | 39        | 2.26%   |
| Fedora 35                    | 34        | 1.97%   |
| Manjaro                      | 30        | 1.74%   |
| Ubuntu 21.04                 | 27        | 1.57%   |
| Linux Mint 20.1              | 26        | 1.51%   |
| Linux Mint 19.3              | 26        | 1.51%   |
| Zorin 16                     | 24        | 1.39%   |
| Ubuntu 20.10                 | 23        | 1.33%   |
| Fedora 37                    | 23        | 1.33%   |
| BlackPanther 18.1            | 23        | 1.33%   |
| Fedora 33                    | 22        | 1.28%   |
| Linux Mint 20                | 20        | 1.16%   |
| Fedora 32                    | 20        | 1.16%   |
| KDE neon 20.04               | 19        | 1.1%    |
| Ubuntu 19.10                 | 18        | 1.04%   |
| Pop!_OS 22.04                | 18        | 1.04%   |
| Fedora 34                    | 18        | 1.04%   |
| Ubuntu 21.10                 | 17        | 0.99%   |
| Pop!_OS 20.10                | 17        | 0.99%   |
| Linux Mint 20.3              | 17        | 0.99%   |
| Xubuntu 20.04                | 16        | 0.93%   |
| Fedora 36                    | 15        | 0.87%   |
| Pop!_OS 20.04                | 14        | 0.81%   |
| openSUSE Tumbleweed-XXXXXXXX | 14        | 0.81%   |
| ROSA R10                     | 13        | 0.75%   |
| Debian 10                    | 13        | 0.75%   |
| Zorin 15                     | 12        | 0.7%    |
| Ubuntu 19.04                 | 12        | 0.7%    |
| Pop!_OS 21.04                | 12        | 0.7%    |
| OpenMandriva 4.50            | 12        | 0.7%    |
| Linux Mint 21                | 12        | 0.7%    |
| ROSA R11                     | 11        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 562       | 34.35%  |
| Linux Mint    | 157       | 9.6%    |
| Fedora        | 121       | 7.4%    |
| OpenMandriva  | 117       | 7.15%   |
| Manjaro       | 88        | 5.38%   |
| Arch          | 84        | 5.13%   |
| Debian        | 70        | 4.28%   |
| Pop!_OS       | 63        | 3.85%   |
| Zorin         | 36        | 2.2%    |
| ROSA          | 36        | 2.2%    |
| Kubuntu       | 29        | 1.77%   |
| Xubuntu       | 25        | 1.53%   |
| openSUSE      | 24        | 1.47%   |
| KDE neon      | 24        | 1.47%   |
| BlackPanther  | 23        | 1.41%   |
| Elementary    | 19        | 1.16%   |
| Ubuntu MATE   | 12        | 0.73%   |
| Gentoo        | 12        | 0.73%   |
| Endless       | 11        | 0.67%   |
| EndeavourOS   | 11        | 0.67%   |
| ArcoLinux     | 11        | 0.67%   |
| Ubuntu Budgie | 8         | 0.49%   |
| Ubuntu Unity  | 7         | 0.43%   |
| MX            | 7         | 0.43%   |
| LMDE          | 7         | 0.43%   |
| SteamOS       | 6         | 0.37%   |
| Clear Linux   | 6         | 0.37%   |
| Lubuntu       | 5         | 0.31%   |
| Ubuntu Studio | 4         | 0.24%   |
| Raspbian      | 4         | 0.24%   |
| Parrot        | 4         | 0.24%   |
| Nobara        | 4         | 0.24%   |
| NixOS         | 4         | 0.24%   |
| Kali          | 4         | 0.24%   |
| Deepin        | 3         | 0.18%   |
| CachyOS       | 3         | 0.18%   |
| UbuntuDDE     | 2         | 0.12%   |
| RHEL          | 2         | 0.12%   |
| Garuda Linux  | 2         | 0.12%   |
| CentOS        | 2         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 52        | 2.74%   |
| 5.10.14-desktop-1omv4002 | 39        | 2.06%   |
| 5.4.0-42-generic         | 29        | 1.53%   |
| 5.4.0-58-generic         | 21        | 1.11%   |
| 5.4.0-52-generic         | 18        | 0.95%   |
| 5.15.0-56-generic        | 18        | 0.95%   |
| 5.15.0-52-generic        | 18        | 0.95%   |
| 5.13.0-39-generic        | 17        | 0.9%    |
| 4.18.16-desktop-1bP      | 17        | 0.9%    |
| 5.3.0-46-generic         | 16        | 0.84%   |
| 5.4.0-91-generic         | 14        | 0.74%   |
| 5.15.0-43-generic        | 14        | 0.74%   |
| 5.4.0-48-generic         | 13        | 0.69%   |
| 5.4.0-26-generic         | 13        | 0.69%   |
| 5.13.0-27-generic        | 13        | 0.69%   |
| 5.4.0-33-generic         | 12        | 0.63%   |
| 5.4.0-28-generic         | 12        | 0.63%   |
| 5.13.0-28-generic        | 12        | 0.63%   |
| 5.11.0-37-generic        | 12        | 0.63%   |
| 5.4.0-74-generic         | 11        | 0.58%   |
| 5.4.0-29-generic         | 11        | 0.58%   |
| 5.3.0-26-generic         | 11        | 0.58%   |
| 5.8.0-7630-generic       | 10        | 0.53%   |
| 5.15.0-47-generic        | 10        | 0.53%   |
| 5.11.0-27-generic        | 10        | 0.53%   |
| 5.11.0-25-generic        | 10        | 0.53%   |
| 5.4.0-80-generic         | 9         | 0.47%   |
| 5.4.0-72-generic         | 9         | 0.47%   |
| 5.3.0-42-generic         | 9         | 0.47%   |
| 5.15.0-58-generic        | 9         | 0.47%   |
| 5.15.0-46-generic        | 9         | 0.47%   |
| 5.13.0-35-generic        | 9         | 0.47%   |
| 5.11.0-40-generic        | 9         | 0.47%   |
| 5.11.0-34-generic        | 9         | 0.47%   |
| 5.10.0-8-amd64           | 9         | 0.47%   |
| 6.1.1-desktop-1omv2290   | 8         | 0.42%   |
| 5.8.0-43-generic         | 8         | 0.42%   |
| 5.8.0-41-generic         | 8         | 0.42%   |
| 5.6.14-desktop-2bP       | 8         | 0.42%   |
| 5.4.0-89-generic         | 8         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 303       | 16.89%  |
| 5.15.0  | 128       | 7.13%   |
| 5.13.0  | 108       | 6.02%   |
| 5.11.0  | 101       | 5.63%   |
| 4.15.0  | 101       | 5.63%   |
| 5.8.0   | 94        | 5.24%   |
| 5.3.0   | 66        | 3.68%   |
| 5.16.7  | 54        | 3.01%   |
| 5.10.0  | 42        | 2.34%   |
| 5.10.14 | 41        | 2.29%   |
| 5.0.0   | 34        | 1.9%    |
| 4.18.0  | 32        | 1.78%   |
| 4.19.0  | 21        | 1.17%   |
| 4.18.16 | 17        | 0.95%   |
| 5.19.0  | 14        | 0.78%   |
| 5.17.5  | 11        | 0.61%   |
| 6.1.1   | 9         | 0.5%    |
| 5.12.4  | 9         | 0.5%    |
| 5.9.11  | 8         | 0.45%   |
| 5.6.14  | 8         | 0.45%   |
| 4.9.60  | 8         | 0.45%   |
| 4.4.0   | 8         | 0.45%   |
| 6.0.7   | 7         | 0.39%   |
| 5.9.16  | 7         | 0.39%   |
| 5.15.12 | 7         | 0.39%   |
| 6.0.12  | 6         | 0.33%   |
| 5.3.18  | 6         | 0.33%   |
| 5.19.7  | 6         | 0.33%   |
| 5.19.2  | 6         | 0.33%   |
| 5.16.0  | 6         | 0.33%   |
| 5.14.9  | 6         | 0.33%   |
| 5.13.19 | 6         | 0.33%   |
| 5.8.14  | 5         | 0.28%   |
| 5.17.15 | 5         | 0.28%   |
| 5.17.1  | 5         | 0.28%   |
| 5.16.18 | 5         | 0.28%   |
| 5.11.12 | 5         | 0.28%   |
| 6.1.7   | 4         | 0.22%   |
| 6.0.8   | 4         | 0.22%   |
| 6.0.2   | 4         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 338       | 19.12%  |
| 5.15    | 179       | 10.12%  |
| 5.13    | 130       | 7.35%   |
| 5.8     | 124       | 7.01%   |
| 5.10    | 123       | 6.96%   |
| 5.11    | 122       | 6.9%    |
| 4.15    | 101       | 5.71%   |
| 5.16    | 82        | 4.64%   |
| 5.3     | 79        | 4.47%   |
| 4.18    | 51        | 2.88%   |
| 6.0     | 46        | 2.6%    |
| 5.19    | 39        | 2.21%   |
| 5.17    | 37        | 2.09%   |
| 5.0     | 35        | 1.98%   |
| 5.9     | 33        | 1.87%   |
| 5.6     | 29        | 1.64%   |
| 4.19    | 29        | 1.64%   |
| 5.12    | 28        | 1.58%   |
| 5.18    | 26        | 1.47%   |
| 5.7     | 25        | 1.41%   |
| 5.14    | 22        | 1.24%   |
| 6.1     | 21        | 1.19%   |
| 4.9     | 21        | 1.19%   |
| 5.5     | 11        | 0.62%   |
| 4.4     | 9         | 0.51%   |
| 4.17    | 4         | 0.23%   |
| 4.12    | 4         | 0.23%   |
| 4.1     | 4         | 0.23%   |
| 5.2     | 3         | 0.17%   |
| 4.10    | 3         | 0.17%   |
| 5.1     | 2         | 0.11%   |
| 4.13    | 2         | 0.11%   |
| 3.10    | 2         | 0.11%   |
| 4.8     | 1         | 0.06%   |
| 4.6     | 1         | 0.06%   |
| 4.20    | 1         | 0.06%   |
| 4.14    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1557      | 97.74%  |
| i686    | 19        | 1.19%   |
| aarch64 | 11        | 0.69%   |
| armv7l  | 6         | 0.38%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 701       | 42.38%  |
| KDE5             | 290       | 17.53%  |
| Unknown          | 211       | 12.76%  |
| X-Cinnamon       | 124       | 7.5%    |
| XFCE             | 116       | 7.01%   |
| MATE             | 42        | 2.54%   |
| KDE              | 37        | 2.24%   |
| Cinnamon         | 22        | 1.33%   |
| Pantheon         | 19        | 1.15%   |
| KDE4             | 19        | 1.15%   |
| Budgie           | 12        | 0.73%   |
| i3               | 11        | 0.67%   |
| LXQt             | 9         | 0.54%   |
| Unity            | 7         | 0.42%   |
| LXDE             | 6         | 0.36%   |
| Deepin           | 6         | 0.36%   |
| awesome          | 6         | 0.36%   |
| GNOME Flashback  | 3         | 0.18%   |
| xmonad           | 2         | 0.12%   |
| sway             | 2         | 0.12%   |
| lightdm-xsession | 2         | 0.12%   |
| qtile            | 1         | 0.06%   |
| openbox          | 1         | 0.06%   |
| leftwm           | 1         | 0.06%   |
| GNOME Classic    | 1         | 0.06%   |
| fluxbox          | 1         | 0.06%   |
| DWM              | 1         | 0.06%   |
| Bspwm            | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1277      | 77.91%  |
| Wayland | 212       | 12.93%  |
| Unknown | 116       | 7.08%   |
| Tty     | 34        | 2.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 781       | 47.16%  |
| SDDM    | 268       | 16.18%  |
| GDM     | 195       | 11.78%  |
| GDM3    | 170       | 10.27%  |
| LightDM | 163       | 9.84%   |
| TDM     | 50        | 3.02%   |
| KDM     | 20        | 1.21%   |
| SLiM    | 5         | 0.3%    |
| XDM     | 2         | 0.12%   |
| MDM     | 1         | 0.06%   |
| LXDM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| de_AT      | 589       | 35.98%  |
| en_US      | 462       | 28.22%  |
| de_DE      | 234       | 14.29%  |
| Unknown    | 210       | 12.83%  |
| en_GB      | 53        | 3.24%   |
| C          | 21        | 1.28%   |
| en_IE      | 10        | 0.61%   |
| pl_PL      | 8         | 0.49%   |
| it_IT      | 5         | 0.31%   |
| es_ES      | 5         | 0.31%   |
| en_AT      | 5         | 0.31%   |
| ru_RU      | 4         | 0.24%   |
| POSIX      | 4         | 0.24%   |
| de_CH      | 4         | 0.24%   |
| tr_TR      | 3         | 0.18%   |
| uk_UA      | 2         | 0.12%   |
| hu_HU      | 2         | 0.12%   |
| en_DE      | 2         | 0.12%   |
| de_AT.UTF8 | 2         | 0.12%   |
| ro_RO      | 1         | 0.06%   |
| pt_BR      | 1         | 0.06%   |
| nl_BE      | 1         | 0.06%   |
| hr_HR      | 1         | 0.06%   |
| fa_IR      | 1         | 0.06%   |
| en_US.UTF8 | 1         | 0.06%   |
| en         | 1         | 0.06%   |
| de_LI      | 1         | 0.06%   |
| da_DK      | 1         | 0.06%   |
| cs_CZ      | 1         | 0.06%   |
| C.UTF8     | 1         | 0.06%   |
| bg_BG      | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 841       | 51.53%  |
| BIOS | 791       | 48.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1220      | 75.5%   |
| Overlay | 153       | 9.47%   |
| Btrfs   | 141       | 8.73%   |
| Unknown | 61        | 3.77%   |
| Xfs     | 15        | 0.93%   |
| Zfs     | 13        | 0.8%    |
| Ext2    | 4         | 0.25%   |
| Tmpfs   | 2         | 0.12%   |
| F2fs    | 2         | 0.12%   |
| Ext3    | 2         | 0.12%   |
| XXXXXXX | 1         | 0.06%   |
| Nfs     | 1         | 0.06%   |
| Aufs    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 845       | 51.94%  |
| GPT     | 615       | 37.8%   |
| MBR     | 167       | 10.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1349      | 83.12%  |
| Yes       | 274       | 16.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1109      | 68.41%  |
| Yes       | 512       | 31.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 286       | 17.96%  |
| ASUSTek Computer        | 282       | 17.71%  |
| Hewlett-Packard         | 223       | 14.01%  |
| Dell                    | 122       | 7.66%   |
| MSI                     | 111       | 6.97%   |
| Acer                    | 95        | 5.97%   |
| Gigabyte Technology     | 81        | 5.09%   |
| ASRock                  | 71        | 4.46%   |
| Medion                  | 44        | 2.76%   |
| Apple                   | 29        | 1.82%   |
| Toshiba                 | 22        | 1.38%   |
| Intel                   | 22        | 1.38%   |
| Sony                    | 18        | 1.13%   |
| Fujitsu                 | 18        | 1.13%   |
| TUXEDO                  | 16        | 1.01%   |
| Unknown                 | 12        | 0.75%   |
| Raspberry Pi Foundation | 11        | 0.69%   |
| TrekStor                | 7         | 0.44%   |
| Samsung Electronics     | 7         | 0.44%   |
| HUAWEI                  | 7         | 0.44%   |
| Biostar                 | 7         | 0.44%   |
| Fujitsu Siemens         | 6         | 0.38%   |
| Valve                   | 5         | 0.31%   |
| Shuttle                 | 5         | 0.31%   |
| Microsoft               | 5         | 0.31%   |
| Foxconn                 | 5         | 0.31%   |
| ZOTAC                   | 4         | 0.25%   |
| Supermicro              | 4         | 0.25%   |
| Notebook                | 4         | 0.25%   |
| Wortmann AG             | 3         | 0.19%   |
| Razer                   | 3         | 0.19%   |
| Clevo                   | 3         | 0.19%   |
| BESSTAR Tech            | 3         | 0.19%   |
| AMI                     | 3         | 0.19%   |
| VALE                    | 2         | 0.13%   |
| Timi                    | 2         | 0.13%   |
| theobroma-systems       | 2         | 0.13%   |
| Teclast                 | 2         | 0.13%   |
| System76                | 2         | 0.13%   |
| Sapphire                | 2         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 25        | 1.57%   |
| Unknown                            | 17        | 1.07%   |
| MSI MS-7C37                        | 10        | 0.63%   |
| Apple MacBookPro15,1               | 8         | 0.5%    |
| MSI MS-7B86                        | 7         | 0.44%   |
| MSI MS-7B79                        | 7         | 0.44%   |
| HP EliteBook 840 G3                | 6         | 0.38%   |
| ASRock Z87 Killer                  | 6         | 0.38%   |
| Valve Jupiter                      | 5         | 0.31%   |
| Lenovo IdeaPad 5 15ARE05 81YQ      | 5         | 0.31%   |
| HP Pavilion dv6                    | 5         | 0.31%   |
| HP EliteBook 8570p                 | 5         | 0.31%   |
| ASUS ROG STRIX B450-F GAMING       | 5         | 0.31%   |
| ASUS PRIME B450-PLUS               | 5         | 0.31%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 4         | 0.25%   |
| RPi Raspberry Pi                   | 4         | 0.25%   |
| MSI MS-7C91                        | 4         | 0.25%   |
| HP EliteBook 8460p                 | 4         | 0.25%   |
| HP EliteBook 840 G6                | 4         | 0.25%   |
| Dell XPS 15 9570                   | 4         | 0.25%   |
| Dell Latitude 5520                 | 4         | 0.25%   |
| ASUS UX303LAB                      | 4         | 0.25%   |
| ASUS TUF Gaming B550-PLUS          | 4         | 0.25%   |
| ASUS ROG STRIX B550-I GAMING       | 4         | 0.25%   |
| ASUS ROG STRIX B550-F GAMING       | 4         | 0.25%   |
| TrekStor Notebook Slim S130        | 3         | 0.19%   |
| Toshiba Satellite C70D-B           | 3         | 0.19%   |
| MSI MS-7C02                        | 3         | 0.19%   |
| MSI MS-7971                        | 3         | 0.19%   |
| MSI MS-7817                        | 3         | 0.19%   |
| MSI MS-7721                        | 3         | 0.19%   |
| Medion P15648                      | 3         | 0.19%   |
| Medion MS-7800                     | 3         | 0.19%   |
| Medion MS-7707                     | 3         | 0.19%   |
| Lenovo Yoga Slim 7 14ARE05 82A2    | 3         | 0.19%   |
| Lenovo Yoga C940-14IIL 81Q9        | 3         | 0.19%   |
| Lenovo ThinkPad E470 20H2S00700    | 3         | 0.19%   |
| Lenovo MIIX 320-10ICR 80XF         | 3         | 0.19%   |
| Intel NUC6CAYH                     | 3         | 0.19%   |
| HP ZBook 17 G5                     | 3         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 172       | 10.8%   |
| HP EliteBook       | 62        | 3.89%   |
| Acer Aspire        | 55        | 3.45%   |
| Dell Latitude      | 42        | 2.64%   |
| ASUS PRIME         | 31        | 1.95%   |
| Dell XPS           | 30        | 1.88%   |
| ASUS ROG           | 30        | 1.88%   |
| HP Pavilion        | 29        | 1.82%   |
| Lenovo IdeaPad     | 27        | 1.7%    |
| HP ProBook         | 26        | 1.63%   |
| ASUS All           | 25        | 1.57%   |
| Toshiba Satellite  | 20        | 1.26%   |
| HP Compaq          | 20        | 1.26%   |
| Lenovo Yoga        | 18        | 1.13%   |
| Lenovo ThinkCentre | 17        | 1.07%   |
| Unknown            | 17        | 1.07%   |
| Dell Inspiron      | 15        | 0.94%   |
| ASUS TUF           | 15        | 0.94%   |
| Dell OptiPlex      | 13        | 0.82%   |
| Dell Precision     | 12        | 0.75%   |
| RPi Raspberry      | 11        | 0.69%   |
| Lenovo ThinkBook   | 11        | 0.69%   |
| HP ENVY            | 11        | 0.69%   |
| ASUS VivoBook      | 11        | 0.69%   |
| MSI MS-7C37        | 10        | 0.63%   |
| HP ZBook           | 10        | 0.63%   |
| Fujitsu LIFEBOOK   | 10        | 0.63%   |
| HP Laptop          | 9         | 0.57%   |
| Acer TravelMate    | 9         | 0.57%   |
| Acer Swift         | 9         | 0.57%   |
| Gigabyte X570      | 8         | 0.5%    |
| Apple MacBookPro15 | 8         | 0.5%    |
| MSI MS-7B86        | 7         | 0.44%   |
| MSI MS-7B79        | 7         | 0.44%   |
| ASUS SABERTOOTH    | 7         | 0.44%   |
| ASRock Z87         | 7         | 0.44%   |
| Acer Nitro         | 7         | 0.44%   |
| ASUS ZenBook       | 6         | 0.38%   |
| Valve Jupiter      | 5         | 0.31%   |
| Microsoft Surface  | 5         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 188       | 11.81%  |
| 2018    | 161       | 10.11%  |
| 2019    | 159       | 9.99%   |
| 2012    | 137       | 8.61%   |
| 2011    | 121       | 7.6%    |
| 2013    | 114       | 7.16%   |
| 2017    | 101       | 6.34%   |
| 2021    | 98        | 6.16%   |
| 2015    | 95        | 5.97%   |
| 2014    | 88        | 5.53%   |
| 2016    | 83        | 5.21%   |
| 2010    | 61        | 3.83%   |
| 2009    | 55        | 3.45%   |
| 2008    | 48        | 3.02%   |
| 2007    | 33        | 2.07%   |
| 2022    | 25        | 1.57%   |
| 2006    | 11        | 0.69%   |
| Unknown | 11        | 0.69%   |
| 2005    | 3         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 853       | 53.58%  |
| Desktop        | 620       | 38.94%  |
| Convertible    | 45        | 2.83%   |
| Mini pc        | 27        | 1.7%    |
| System on chip | 17        | 1.07%   |
| Server         | 14        | 0.88%   |
| Tablet         | 12        | 0.75%   |
| All in one     | 4         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1471      | 91.48%  |
| Enabled  | 137       | 8.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1588      | 99.75%  |
| Yes  | 4         | 0.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 363       | 22.56%  |
| 4.01-8.0        | 337       | 20.94%  |
| 8.01-16.0       | 304       | 18.89%  |
| 3.01-4.0        | 242       | 15.04%  |
| 32.01-64.0      | 205       | 12.74%  |
| 64.01-256.0     | 47        | 2.92%   |
| 1.01-2.0        | 46        | 2.86%   |
| 24.01-32.0      | 35        | 2.18%   |
| 2.01-3.0        | 12        | 0.75%   |
| 0.51-1.0        | 12        | 0.75%   |
| More than 256.0 | 5         | 0.31%   |
| Unknown         | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 625       | 35.61%  |
| 2.01-3.0   | 424       | 24.16%  |
| 4.01-8.0   | 251       | 14.3%   |
| 3.01-4.0   | 211       | 12.02%  |
| 0.51-1.0   | 105       | 5.98%   |
| 8.01-16.0  | 91        | 5.19%   |
| 16.01-24.0 | 18        | 1.03%   |
| 0.01-0.5   | 18        | 1.03%   |
| 32.01-64.0 | 6         | 0.34%   |
| 24.01-32.0 | 5         | 0.28%   |
| Unknown    | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 945       | 57.52%  |
| 2      | 392       | 23.86%  |
| 3      | 150       | 9.13%   |
| 4      | 75        | 4.56%   |
| 5      | 28        | 1.7%    |
| 6      | 17        | 1.03%   |
| 9      | 10        | 0.61%   |
| 0      | 8         | 0.49%   |
| 7      | 7         | 0.43%   |
| 11     | 3         | 0.18%   |
| 10     | 3         | 0.18%   |
| 18     | 2         | 0.12%   |
| 8      | 2         | 0.12%   |
| 12     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 957       | 59.66%  |
| Yes       | 647       | 40.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1391      | 87.1%   |
| No        | 206       | 12.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1187      | 74.23%  |
| No        | 412       | 25.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 922       | 57.66%  |
| No        | 677       | 42.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Austria | 1592      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Vienna             | 914       | 54.83%  |
| Graz               | 91        | 5.46%   |
| Linz               | 49        | 2.94%   |
| Innsbruck          | 48        | 2.88%   |
| Salzburg           | 41        | 2.46%   |
| Bad Hall           | 31        | 1.86%   |
| Klagenfurt         | 20        | 1.2%    |
| Wels               | 15        | 0.9%    |
| Sankt Pölten      | 15        | 0.9%    |
| Dornbirn           | 15        | 0.9%    |
| Wiener Neustadt    | 10        | 0.6%    |
| Wörgl             | 8         | 0.48%   |
| Villach            | 8         | 0.48%   |
| Perg               | 8         | 0.48%   |
| Leonding           | 8         | 0.48%   |
| Steyr              | 7         | 0.42%   |
| Korneuburg         | 7         | 0.42%   |
| Bregenz            | 6         | 0.36%   |
| Traunkirchen       | 5         | 0.3%    |
| Mautern            | 5         | 0.3%    |
| Baden bei Wien     | 5         | 0.3%    |
| Zell am See        | 4         | 0.24%   |
| Voecklabruck       | 4         | 0.24%   |
| Umhausen           | 4         | 0.24%   |
| Seiersberg         | 4         | 0.24%   |
| Schwechat          | 4         | 0.24%   |
| Perchtoldsdorf     | 4         | 0.24%   |
| Klosterneuburg     | 4         | 0.24%   |
| Gaenserndorf       | 4         | 0.24%   |
| Feldkirch          | 4         | 0.24%   |
| Brunn am Gebirge   | 4         | 0.24%   |
| Traun              | 3         | 0.18%   |
| Sommerein          | 3         | 0.18%   |
| Mauthausen         | 3         | 0.18%   |
| Horn               | 3         | 0.18%   |
| Hard               | 3         | 0.18%   |
| Hallein            | 3         | 0.18%   |
| Hall in Tirol      | 3         | 0.18%   |
| Bad Tatzmannsdorf  | 3         | 0.18%   |
| Altenberg bei Linz | 3         | 0.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 543       | 827    | 22.63%  |
| Seagate                   | 286       | 425    | 11.92%  |
| WDC                       | 282       | 438    | 11.75%  |
| SanDisk                   | 225       | 306    | 9.38%   |
| Toshiba                   | 153       | 250    | 6.38%   |
| Kingston                  | 105       | 127    | 4.38%   |
| Crucial                   | 99        | 157    | 4.13%   |
| Unknown                   | 98        | 143    | 4.09%   |
| Intel                     | 66        | 81     | 2.75%   |
| SK hynix                  | 55        | 73     | 2.29%   |
| Hitachi                   | 54        | 59     | 2.25%   |
| Intenso                   | 41        | 48     | 1.71%   |
| Micron Technology         | 39        | 47     | 1.63%   |
| HGST                      | 38        | 59     | 1.58%   |
| Transcend                 | 26        | 31     | 1.08%   |
| Phison                    | 19        | 26     | 0.79%   |
| A-DATA Technology         | 18        | 24     | 0.75%   |
| KIOXIA                    | 15        | 25     | 0.63%   |
| Apple                     | 15        | 26     | 0.63%   |
| OCZ                       | 14        | 24     | 0.58%   |
| Corsair                   | 12        | 15     | 0.5%    |
| China                     | 12        | 16     | 0.5%    |
| Micron/Crucial Technology | 11        | 13     | 0.46%   |
| ASMT                      | 9         | 17     | 0.38%   |
| LITEON                    | 8         | 9      | 0.33%   |
| JMicron Technology        | 8         | 18     | 0.33%   |
| SABRENT                   | 7         | 8      | 0.29%   |
| LITEONIT                  | 7         | 9      | 0.29%   |
| Unknown                   | 6         | 8      | 0.25%   |
| Silicon Motion            | 5         | 6      | 0.21%   |
| Hewlett-Packard           | 5         | 11     | 0.21%   |
| GOODRAM                   | 5         | 5      | 0.21%   |
| Apacer                    | 5         | 6      | 0.21%   |
| Phison Electronics        | 4         | 5      | 0.17%   |
| Patriot                   | 4         | 5      | 0.17%   |
| Maxtor                    | 4         | 4      | 0.17%   |
| INNOVATION IT             | 4         | 4      | 0.17%   |
| UMIS                      | 3         | 3      | 0.13%   |
| TrekStor                  | 3         | 5      | 0.13%   |
| SPCC                      | 3         | 12     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 30        | 1.11%   |
| Samsung NVMe SSD Drive 512GB                        | 27        | 1%      |
| Samsung SSD 860 EVO 500GB                           | 26        | 0.96%   |
| Samsung SSD 850 EVO 500GB                           | 26        | 0.96%   |
| Seagate Expansion 240GB                             | 20        | 0.74%   |
| SanDisk SSD PLUS 240GB                              | 19        | 0.7%    |
| Samsung SSD 850 PRO 256GB                           | 19        | 0.7%    |
| Samsung SSD 840 EVO 250GB                           | 19        | 0.7%    |
| Samsung NVMe SSD Drive 500GB                        | 18        | 0.67%   |
| Samsung NVMe SSD Drive 1TB                          | 18        | 0.67%   |
| Samsung SSD 860 EVO 1TB                             | 17        | 0.63%   |
| Samsung SSD 970 EVO Plus 1TB                        | 16        | 0.59%   |
| Samsung SSD 860 EVO 250GB                           | 16        | 0.59%   |
| Crucial CT500MX500SSD1 500GB                        | 15        | 0.56%   |
| Unknown MMC Card  64GB                              | 14        | 0.52%   |
| Toshiba DT01ACA200 2TB                              | 14        | 0.52%   |
| SanDisk SSD PLUS 1000GB                             | 14        | 0.52%   |
| Toshiba MQ01ABD100 1TB                              | 13        | 0.48%   |
| SanDisk NVMe SSD Drive 512GB                        | 13        | 0.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 13        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB                         | 13        | 0.48%   |
| Unknown MMC Card  32GB                              | 12        | 0.45%   |
| SanDisk NVMe SSD Drive 1TB                          | 12        | 0.45%   |
| Samsung NVMe SSD Drive 1024GB                       | 12        | 0.45%   |
| Unknown SD/MMC/MS PRO 2GB                           | 11        | 0.41%   |
| Toshiba MQ04ABF100 1TB                              | 11        | 0.41%   |
| SanDisk SSD PLUS 480GB                              | 11        | 0.41%   |
| SanDisk SDSSDH3 1T00 1TB                            | 11        | 0.41%   |
| Samsung SSD 980 PRO 1TB                             | 11        | 0.41%   |
| Kingston SA400S37120G 120GB SSD                     | 11        | 0.41%   |
| Toshiba HDWD110 1TB                                 | 10        | 0.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 10        | 0.37%   |
| SanDisk Extreme SSD 500GB                           | 10        | 0.37%   |
| Samsung SSD 970 EVO Plus 500GB                      | 10        | 0.37%   |
| Samsung SSD 860 QVO 1TB                             | 10        | 0.37%   |
| Crucial CT240BX500SSD1 240GB                        | 10        | 0.37%   |
| Toshiba DT01ACA100 1TB                              | 9         | 0.33%   |
| Seagate ST500LT012-1DG142 500GB                     | 9         | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB                      | 9         | 0.33%   |
| SanDisk SDSSDA240G 240GB                            | 9         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 279       | 410    | 34.7%   |
| WDC                 | 223       | 353    | 27.74%  |
| Toshiba             | 110       | 171    | 13.68%  |
| Hitachi             | 54        | 59     | 6.72%   |
| Samsung Electronics | 47        | 67     | 5.85%   |
| HGST                | 38        | 59     | 4.73%   |
| Unknown             | 12        | 19     | 1.49%   |
| SABRENT             | 7         | 8      | 0.87%   |
| ASMT                | 7         | 13     | 0.87%   |
| Maxtor              | 4         | 4      | 0.5%    |
| JMicron Technology  | 4         | 11     | 0.5%    |
| Intenso             | 4         | 4      | 0.5%    |
| USB                 | 2         | 2      | 0.25%   |
| Hewlett-Packard     | 2         | 9      | 0.25%   |
| Fujitsu             | 2         | 2      | 0.25%   |
| WD MediaMax         | 1         | 1      | 0.12%   |
| TrueNAS             | 1         | 1      | 0.12%   |
| Synology            | 1         | 8      | 0.12%   |
| Magnetic Data       | 1         | 1      | 0.12%   |
| LaCie               | 1         | 1      | 0.12%   |
| IBM-ESXS            | 1         | 2      | 0.12%   |
| Ext Hard            | 1         | 1      | 0.12%   |
| ASMedia             | 1         | 1      | 0.12%   |
| Apple               | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 297       | 418    | 31.8%   |
| SanDisk             | 173       | 237    | 18.52%  |
| Crucial             | 91        | 138    | 9.74%   |
| Kingston            | 81        | 91     | 8.67%   |
| Intenso             | 32        | 39     | 3.43%   |
| Intel               | 31        | 38     | 3.32%   |
| Transcend           | 23        | 26     | 2.46%   |
| Micron Technology   | 20        | 25     | 2.14%   |
| WDC                 | 18        | 21     | 1.93%   |
| SK hynix            | 18        | 28     | 1.93%   |
| OCZ                 | 14        | 24     | 1.5%    |
| A-DATA Technology   | 13        | 18     | 1.39%   |
| China               | 12        | 16     | 1.28%   |
| Toshiba             | 9         | 11     | 0.96%   |
| LITEON              | 8         | 9      | 0.86%   |
| Corsair             | 8         | 8      | 0.86%   |
| LITEONIT            | 7         | 9      | 0.75%   |
| Apple               | 6         | 6      | 0.64%   |
| GOODRAM             | 5         | 5      | 0.54%   |
| Apacer              | 5         | 5      | 0.54%   |
| INNOVATION IT       | 4         | 4      | 0.43%   |
| Phison              | 3         | 4      | 0.32%   |
| Patriot             | 3         | 3      | 0.32%   |
| JMicron Technology  | 3         | 3      | 0.32%   |
| Verbatim            | 2         | 2      | 0.21%   |
| Unknown             | 2         | 3      | 0.21%   |
| TrekStor            | 2         | 4      | 0.21%   |
| Teclast             | 2         | 2      | 0.21%   |
| TCSUNBOW            | 2         | 2      | 0.21%   |
| SPCC                | 2         | 2      | 0.21%   |
| Seagate             | 2         | 2      | 0.21%   |
| Plextor             | 2         | 2      | 0.21%   |
| Netac               | 2         | 3      | 0.21%   |
| Leven               | 2         | 2      | 0.21%   |
| KingDian            | 2         | 2      | 0.21%   |
| Hewlett-Packard     | 2         | 2      | 0.21%   |
| Dogfish             | 2         | 2      | 0.21%   |
| BIWIN               | 2         | 2      | 0.21%   |
| WDC WDS2            | 1         | 1      | 0.11%   |
| ViperTeq            | 1         | 4      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 812       | 1246   | 37.79%  |
| HDD     | 661       | 1208   | 30.76%  |
| NVMe    | 558       | 821    | 25.97%  |
| MMC     | 84        | 120    | 3.91%   |
| Unknown | 34        | 80     | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1154      | 2319   | 60.29%  |
| NVMe | 558       | 821    | 29.15%  |
| SAS  | 118       | 215    | 6.17%   |
| MMC  | 84        | 120    | 4.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 882       | 1410   | 56.21%  |
| 0.51-1.0   | 420       | 593    | 26.77%  |
| 1.01-2.0   | 123       | 199    | 7.84%   |
| 3.01-4.0   | 59        | 110    | 3.76%   |
| 4.01-10.0  | 43        | 63     | 2.74%   |
| 2.01-3.0   | 33        | 47     | 2.1%    |
| 10.01-20.0 | 9         | 32     | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 428       | 25.51%  |
| 251-500        | 310       | 18.47%  |
| 501-1000       | 250       | 14.9%   |
| 1-20           | 135       | 8.05%   |
| 1001-2000      | 126       | 7.51%   |
| 51-100         | 112       | 6.67%   |
| More than 3000 | 108       | 6.44%   |
| Unknown        | 85        | 5.07%   |
| 21-50          | 68        | 4.05%   |
| 2001-3000      | 56        | 3.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 642       | 37.09%  |
| 21-50          | 271       | 15.66%  |
| 101-250        | 208       | 12.02%  |
| 51-100         | 158       | 9.13%   |
| 251-500        | 118       | 6.82%   |
| 501-1000       | 111       | 6.41%   |
| Unknown        | 85        | 4.91%   |
| 1001-2000      | 71        | 4.1%    |
| More than 3000 | 39        | 2.25%   |
| 2001-3000      | 28        | 1.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD10EADS-22M2B0 1TB                  | 7         | 7      | 4.9%    |
| SanDisk SD6SF1M128G1022I 128GB SSD       | 5         | 5      | 3.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 4         | 4      | 2.8%    |
| Samsung Electronics HD103UJ 1TB          | 3         | 3      | 2.1%    |
| WDC WD30EFRX-68EUZN0 3TB                 | 2         | 2      | 1.4%    |
| Toshiba MQ01ABF050 500GB                 | 2         | 3      | 1.4%    |
| Seagate ST3500413AS 500GB                | 2         | 2      | 1.4%    |
| SanDisk SSD PLUS 480GB                   | 2         | 2      | 1.4%    |
| Samsung Electronics SSD 840 Series 120GB | 2         | 2      | 1.4%    |
| Samsung Electronics HM500JI 500GB        | 2         | 2      | 1.4%    |
| Hitachi HTS547575A9E384 752GB            | 2         | 2      | 1.4%    |
| HGST HTS725050A7E630 500GB               | 2         | 10     | 1.4%    |
| HGST HTS721010A9E630 1TB                 | 2         | 3      | 1.4%    |
| WDC WD6400AACS-00G8B0 640GB              | 1         | 1      | 0.7%    |
| WDC WD5000LPLX-00ZNTT0 500GB             | 1         | 1      | 0.7%    |
| WDC WD5000AAKX-08U6AA0 500GB             | 1         | 1      | 0.7%    |
| WDC WD5000AAKS-60Z1A0 500GB              | 1         | 1      | 0.7%    |
| WDC WD5000AAKS-00UU3A0 500GB             | 1         | 1      | 0.7%    |
| WDC WD5000AADS-00M2B0 500GB              | 1         | 1      | 0.7%    |
| WDC WD3200BEVT-08A23T1 320GB             | 1         | 1      | 0.7%    |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1         | 1      | 0.7%    |
| WDC WD20EZRX-00D8PB0 2TB                 | 1         | 1      | 0.7%    |
| WDC WD20EFRX-68AX9N0 2TB                 | 1         | 10     | 0.7%    |
| WDC WD2003FYYS-02W0B1 2TB                | 1         | 1      | 0.7%    |
| WDC WD2002FYPS-02W3B0 2TB                | 1         | 1      | 0.7%    |
| WDC WD2000FYYZ-01UL1B1 2TB               | 1         | 1      | 0.7%    |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 1      | 0.7%    |
| WDC WD10EZRX-00L4HB0 1TB                 | 1         | 1      | 0.7%    |
| WDC WD10EZEX-75M2NA0 1TB                 | 1         | 1      | 0.7%    |
| WDC WD10EACS-00D6B0 1TB                  | 1         | 2      | 0.7%    |
| WDC WD1002FAEX-00Y9A0 1TB                | 1         | 1      | 0.7%    |
| WDC WD1001FALS-40K1B0 1TB                | 1         | 1      | 0.7%    |
| TrekStor TREKSTORSSD128GB                | 1         | 1      | 0.7%    |
| Transcend TS240GSSD220S 240GB            | 1         | 1      | 0.7%    |
| Toshiba MQ02ABF050H 500GB                | 1         | 1      | 0.7%    |
| Toshiba MQ01ABD100M 1TB                  | 1         | 1      | 0.7%    |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 0.7%    |
| Toshiba MK7559GSXP 752GB                 | 1         | 1      | 0.7%    |
| Toshiba MK6465GSXNW 640GB                | 1         | 1      | 0.7%    |
| Toshiba MK5055GSX 500GB                  | 1         | 1      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 38     | 19.85%  |
| Seagate             | 24        | 36     | 17.65%  |
| Samsung Electronics | 20        | 25     | 14.71%  |
| SanDisk             | 14        | 15     | 10.29%  |
| Toshiba             | 12        | 14     | 8.82%   |
| Hitachi             | 11        | 12     | 8.09%   |
| HGST                | 7         | 16     | 5.15%   |
| Intel               | 4         | 4      | 2.94%   |
| OCZ                 | 2         | 4      | 1.47%   |
| LITEONIT            | 2         | 3      | 1.47%   |
| Crucial             | 2         | 2      | 1.47%   |
| TrekStor            | 1         | 1      | 0.74%   |
| Transcend           | 1         | 1      | 0.74%   |
| SK hynix            | 1         | 7      | 0.74%   |
| Maxtor              | 1         | 1      | 0.74%   |
| LITEON              | 1         | 1      | 0.74%   |
| Kingston            | 1         | 1      | 0.74%   |
| Intenso             | 1         | 1      | 0.74%   |
| GOODRAM             | 1         | 1      | 0.74%   |
| Fujitsu             | 1         | 1      | 0.74%   |
| Corsair             | 1         | 1      | 0.74%   |
| A-DATA Technology   | 1         | 3      | 0.74%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 38     | 29.35%  |
| Seagate             | 24        | 36     | 26.09%  |
| Toshiba             | 11        | 13     | 11.96%  |
| Hitachi             | 11        | 12     | 11.96%  |
| Samsung Electronics | 10        | 11     | 10.87%  |
| HGST                | 7         | 16     | 7.61%   |
| Maxtor              | 1         | 1      | 1.09%   |
| Fujitsu             | 1         | 1      | 1.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 87        | 128    | 66.41%  |
| SSD  | 39        | 54     | 29.77%  |
| NVMe | 5         | 6      | 3.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 975       | 1937   | 55.43%  |
| Works    | 661       | 1348   | 37.58%  |
| Malfunc  | 121       | 188    | 6.88%   |
| Failed   | 1         | 1      | 0.06%   |
| Limited  | 1         | 1      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1003      | 48.11%  |
| AMD                              | 331       | 15.88%  |
| Samsung Electronics              | 249       | 11.94%  |
| SanDisk                          | 96        | 4.6%    |
| ASMedia Technology               | 56        | 2.69%   |
| SK hynix                         | 39        | 1.87%   |
| Toshiba America Info Systems     | 36        | 1.73%   |
| Marvell Technology Group         | 36        | 1.73%   |
| JMicron Technology               | 31        | 1.49%   |
| Phison Electronics               | 28        | 1.34%   |
| Kingston Technology Company      | 28        | 1.34%   |
| Nvidia                           | 20        | 0.96%   |
| Micron Technology                | 20        | 0.96%   |
| Micron/Crucial Technology        | 18        | 0.86%   |
| KIOXIA                           | 14        | 0.67%   |
| LSI Logic / Symbios Logic        | 10        | 0.48%   |
| Broadcom / LSI                   | 9         | 0.43%   |
| Apple                            | 8         | 0.38%   |
| ADATA Technology                 | 8         | 0.38%   |
| Silicon Motion                   | 7         | 0.34%   |
| VIA Technologies                 | 6         | 0.29%   |
| Union Memory (Shenzhen)          | 6         | 0.29%   |
| Seagate Technology               | 5         | 0.24%   |
| Silicon Image                    | 3         | 0.14%   |
| Lenovo                           | 3         | 0.14%   |
| Solid State Storage Technology   | 2         | 0.1%    |
| OCZ Technology Group             | 2         | 0.1%    |
| Hewlett-Packard                  | 2         | 0.1%    |
| Adaptec                          | 2         | 0.1%    |
| Transcend                        | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| Realtek Semiconductor            | 1         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.05%   |
| Lite-On Technology               | 1         | 0.05%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.05%   |
| Integrated Technology Express    | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 218       | 9.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 140       | 5.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 81        | 3.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 78        | 3.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 73        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 66        | 2.78%   |
| AMD 400 Series Chipset SATA Controller                                         | 54        | 2.27%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 51        | 2.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 50        | 2.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 49        | 2.06%   |
| Samsung NVMe SSD Controller 980                                                | 44        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 44        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 39        | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 36        | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 36        | 1.51%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 33        | 1.39%   |
| AMD 500 Series Chipset SATA Controller                                         | 33        | 1.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 32        | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 31        | 1.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 29        | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller                            | 29        | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 28        | 1.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 26        | 1.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 25        | 1.05%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 22        | 0.93%   |
| JMicron JMB363 SATA/IDE Controller                                             | 22        | 0.93%   |
| Intel SATA Controller [RAID mode]                                              | 22        | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 21        | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 20        | 0.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 20        | 0.84%   |
| Micron Non-Volatile memory controller                                          | 19        | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 19        | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 19        | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 19        | 0.8%    |
| Intel SSD 660P Series                                                          | 18        | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 18        | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 18        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 18        | 0.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 16        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1172      | 56.84%  |
| NVMe | 563       | 27.3%   |
| IDE  | 187       | 9.07%   |
| RAID | 125       | 6.06%   |
| SAS  | 8         | 0.39%   |
| SCSI | 7         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1159      | 72.8%   |
| AMD    | 416       | 26.13%  |
| ARM    | 17        | 1.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz           | 23        | 1.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 21        | 1.32%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 19        | 1.19%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 17        | 1.07%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 16        | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 16        | 1.01%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 16        | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 15        | 0.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 14        | 0.88%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 13        | 0.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 13        | 0.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 12        | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 12        | 0.75%   |
| AMD Ryzen 5 3600 6-Core Processor           | 12        | 0.75%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 11        | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 11        | 0.69%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 11        | 0.69%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 11        | 0.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 11        | 0.69%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 11        | 0.69%   |
| ARM Processor                               | 11        | 0.69%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics  | 11        | 0.69%   |
| AMD FX-8350 Eight-Core Processor            | 11        | 0.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 10        | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 10        | 0.63%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 10        | 0.63%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 10        | 0.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9         | 0.57%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 9         | 0.57%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 9         | 0.57%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 9         | 0.57%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 9         | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 8         | 0.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 8         | 0.5%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz     | 8         | 0.5%    |
| AMD Ryzen 7 4800H with Radeon Graphics      | 8         | 0.5%    |
| AMD Ryzen 5 4500U with Radeon Graphics      | 8         | 0.5%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 7         | 0.44%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 7         | 0.44%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 7         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 367       | 23.05%  |
| Intel Core i7           | 357       | 22.42%  |
| AMD Ryzen 7             | 96        | 6.03%   |
| AMD Ryzen 5             | 95        | 5.97%   |
| Other                   | 85        | 5.34%   |
| Intel Core i3           | 64        | 4.02%   |
| Intel Celeron           | 62        | 3.89%   |
| Intel Core 2 Duo        | 59        | 3.71%   |
| Intel Xeon              | 37        | 2.32%   |
| Intel Pentium           | 37        | 2.32%   |
| AMD FX                  | 30        | 1.88%   |
| Intel Atom              | 29        | 1.82%   |
| AMD Ryzen 9             | 26        | 1.63%   |
| AMD Ryzen 7 PRO         | 22        | 1.38%   |
| Intel Core i9           | 19        | 1.19%   |
| AMD Ryzen 3             | 17        | 1.07%   |
| AMD A8                  | 15        | 0.94%   |
| Intel Pentium Dual-Core | 14        | 0.88%   |
| AMD Phenom II X4        | 14        | 0.88%   |
| Intel Core 2 Quad       | 10        | 0.63%   |
| AMD A4                  | 10        | 0.63%   |
| AMD A10                 | 10        | 0.63%   |
| Intel Core 2            | 9         | 0.57%   |
| AMD Ryzen 5 PRO         | 7         | 0.44%   |
| AMD Phenom II X6        | 7         | 0.44%   |
| AMD A6                  | 7         | 0.44%   |
| Intel Pentium Silver    | 6         | 0.38%   |
| AMD E                   | 6         | 0.38%   |
| AMD Athlon II X4        | 6         | 0.38%   |
| AMD Athlon 64 X2        | 6         | 0.38%   |
| Intel Genuine           | 5         | 0.31%   |
| AMD E2                  | 5         | 0.31%   |
| AMD Athlon              | 5         | 0.31%   |
| ARM BCM                 | 4         | 0.25%   |
| AMD Ryzen Threadripper  | 4         | 0.25%   |
| AMD E1                  | 4         | 0.25%   |
| Intel Xeon Silver       | 3         | 0.19%   |
| Intel Pentium Dual      | 3         | 0.19%   |
| Intel Pentium 4         | 3         | 0.19%   |
| AMD Athlon II           | 3         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 648       | 40.63%  |
| 2       | 548       | 34.36%  |
| 6       | 157       | 9.84%   |
| 8       | 156       | 9.78%   |
| 12      | 23        | 1.44%   |
| 1       | 18        | 1.13%   |
| 16      | 17        | 1.07%   |
| 10      | 6         | 0.38%   |
| 3       | 6         | 0.38%   |
| Unknown | 6         | 0.38%   |
| 14      | 4         | 0.25%   |
| 20      | 2         | 0.13%   |
| 64      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 40      | 1         | 0.06%   |
| 24      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1575      | 98.87%  |
| 2       | 16        | 1%      |
| Unknown | 2         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1105      | 69.19%  |
| 1       | 486       | 30.43%  |
| Unknown | 6         | 0.38%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1546      | 97.05%  |
| Unknown        | 37        | 2.32%   |
| 32-bit         | 9         | 0.56%   |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 346       | 21.03%  |
| 0x206a7    | 97        | 5.9%    |
| 0x306a9    | 91        | 5.53%   |
| 0x306c3    | 74        | 4.5%    |
| 0x806ec    | 52        | 3.16%   |
| 0x506e3    | 42        | 2.55%   |
| 0x806ea    | 40        | 2.43%   |
| 0x1067a    | 40        | 2.43%   |
| 0x906ea    | 39        | 2.37%   |
| 0x806c1    | 37        | 2.25%   |
| 0x406e3    | 33        | 2.01%   |
| 0x306d4    | 33        | 2.01%   |
| 0x40651    | 30        | 1.82%   |
| 0x906e9    | 29        | 1.76%   |
| 0x806e9    | 28        | 1.7%    |
| 0x08701021 | 25        | 1.52%   |
| 0x0a50000c | 23        | 1.4%    |
| 0x506c9    | 18        | 1.09%   |
| 0x08600106 | 18        | 1.09%   |
| 0x06000852 | 16        | 0.97%   |
| 0x010000c8 | 16        | 0.97%   |
| 0x706e5    | 15        | 0.91%   |
| 0x08701013 | 15        | 0.91%   |
| 0x08108109 | 15        | 0.91%   |
| 0x106e5    | 14        | 0.85%   |
| 0x10676    | 14        | 0.85%   |
| 0x0800820d | 14        | 0.85%   |
| 0x20655    | 13        | 0.79%   |
| 0x08108102 | 13        | 0.79%   |
| 0x06001119 | 13        | 0.79%   |
| 0x406c4    | 12        | 0.73%   |
| 0x08600103 | 12        | 0.73%   |
| 0x706a8    | 11        | 0.67%   |
| 0x406c3    | 11        | 0.67%   |
| 0x30678    | 11        | 0.67%   |
| 0xa0652    | 10        | 0.61%   |
| 0x906ed    | 10        | 0.61%   |
| 0x0a201016 | 10        | 0.61%   |
| 0x08608103 | 10        | 0.61%   |
| 0x08001138 | 10        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 265       | 16.64%  |
| Haswell          | 142       | 8.91%   |
| SandyBridge      | 122       | 7.66%   |
| IvyBridge        | 119       | 7.47%   |
| Zen 2            | 110       | 6.91%   |
| Skylake          | 103       | 6.47%   |
| Penryn           | 69        | 4.33%   |
| Zen 3            | 58        | 3.64%   |
| Zen+             | 56        | 3.52%   |
| Unknown          | 50        | 3.14%   |
| TigerLake        | 44        | 2.76%   |
| Broadwell        | 39        | 2.45%   |
| Silvermont       | 38        | 2.39%   |
| Piledriver       | 38        | 2.39%   |
| K10              | 36        | 2.26%   |
| Westmere         | 33        | 2.07%   |
| Zen              | 31        | 1.95%   |
| Core             | 29        | 1.82%   |
| CometLake        | 27        | 1.69%   |
| IceLake          | 25        | 1.57%   |
| Nehalem          | 22        | 1.38%   |
| Goldmont         | 20        | 1.26%   |
| Goldmont plus    | 19        | 1.19%   |
| Excavator        | 14        | 0.88%   |
| Bonnell          | 12        | 0.75%   |
| Bobcat           | 12        | 0.75%   |
| Alderlake Hybrid | 11        | 0.69%   |
| K8 Hammer        | 10        | 0.63%   |
| Puma             | 8         | 0.5%    |
| K10 Llano        | 6         | 0.38%   |
| Steamroller      | 5         | 0.31%   |
| Jaguar           | 5         | 0.31%   |
| NetBurst         | 4         | 0.25%   |
| Bulldozer        | 4         | 0.25%   |
| Tremont          | 3         | 0.19%   |
| P6               | 3         | 0.19%   |
| K8 & K10 hybrid  | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 827       | 44.92%  |
| Nvidia                           | 529       | 28.73%  |
| AMD                              | 466       | 25.31%  |
| Matrox Electronics Systems       | 9         | 0.49%   |
| ASPEED Technology                | 7         | 0.38%   |
| ATI Technologies                 | 2         | 0.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 79        | 4.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 70        | 3.71%   |
| AMD Renoir                                                                               | 54        | 2.86%   |
| Intel UHD Graphics 620                                                                   | 42        | 2.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 41        | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 37        | 1.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 37        | 1.96%   |
| Intel HD Graphics 620                                                                    | 35        | 1.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 34        | 1.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 32        | 1.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 32        | 1.7%    |
| Intel HD Graphics 5500                                                                   | 30        | 1.59%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 30        | 1.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 30        | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 28        | 1.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 25        | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 1.33%   |
| Intel HD Graphics 530                                                                    | 22        | 1.17%   |
| Intel HD Graphics 630                                                                    | 20        | 1.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 1.01%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 1.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 0.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 0.9%    |
| Nvidia GP108M [GeForce MX250]                                                            | 15        | 0.8%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 15        | 0.8%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 15        | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 14        | 0.74%   |
| Intel HD Graphics 500                                                                    | 14        | 0.74%   |
| AMD Lucienne                                                                             | 14        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 13        | 0.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 13        | 0.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 13        | 0.69%   |
| Intel Iris Plus Graphics G7                                                              | 13        | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 0.69%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 13        | 0.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 0.64%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 11        | 0.58%   |
| Nvidia GT218 [GeForce 210]                                                               | 10        | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 10        | 0.53%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 10        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 594       | 37.03%  |
| 1 x AMD                 | 380       | 23.69%  |
| 1 x Nvidia              | 328       | 20.45%  |
| Intel + Nvidia          | 174       | 10.85%  |
| Intel + AMD             | 42        | 2.62%   |
| 2 x AMD                 | 26        | 1.62%   |
| AMD + Nvidia            | 21        | 1.31%   |
| Other                   | 18        | 1.12%   |
| 1 x Matrox              | 8         | 0.5%    |
| 1 x ASPEED              | 5         | 0.31%   |
| 2 x Nvidia              | 3         | 0.19%   |
| Nvidia + ASPEED         | 3         | 0.19%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.06%   |
| 1 x SiS                 | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1284      | 79.46%  |
| Proprietary | 269       | 16.65%  |
| Unknown     | 63        | 3.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 850       | 52.08%  |
| 1.01-2.0   | 207       | 12.68%  |
| 0.01-0.5   | 172       | 10.54%  |
| 0.51-1.0   | 125       | 7.66%   |
| 3.01-4.0   | 121       | 7.41%   |
| 7.01-8.0   | 85        | 5.21%   |
| 5.01-6.0   | 40        | 2.45%   |
| 8.01-16.0  | 18        | 1.1%    |
| 2.01-3.0   | 10        | 0.61%   |
| 16.01-24.0 | 3         | 0.18%   |
| 4.01-5.0   | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 263       | 14.64%  |
| AU Optronics            | 214       | 11.92%  |
| LG Display              | 160       | 8.91%   |
| Chimei Innolux          | 121       | 6.74%   |
| BOE                     | 112       | 6.24%   |
| Dell                    | 85        | 4.73%   |
| BenQ                    | 84        | 4.68%   |
| Goldstar                | 62        | 3.45%   |
| Hewlett-Packard         | 59        | 3.29%   |
| Acer                    | 59        | 3.29%   |
| AOC                     | 50        | 2.78%   |
| Philips                 | 45        | 2.51%   |
| Lenovo                  | 43        | 2.39%   |
| Iiyama                  | 42        | 2.34%   |
| Sharp                   | 37        | 2.06%   |
| Apple                   | 31        | 1.73%   |
| Ancor Communications    | 30        | 1.67%   |
| Eizo                    | 29        | 1.61%   |
| Medion                  | 19        | 1.06%   |
| Chi Mei Optoelectronics | 19        | 1.06%   |
| Gericom                 | 15        | 0.84%   |
| Fujitsu Siemens         | 14        | 0.78%   |
| PANDA                   | 11        | 0.61%   |
| NEC Computers           | 11        | 0.61%   |
| InfoVision              | 11        | 0.61%   |
| ViewSonic               | 10        | 0.56%   |
| Sony                    | 10        | 0.56%   |
| Unknown                 | 9         | 0.5%    |
| Toshiba                 | 8         | 0.45%   |
| HannStar                | 8         | 0.45%   |
| LG Philips              | 7         | 0.39%   |
| ASUSTek Computer        | 7         | 0.39%   |
| CSO                     | 6         | 0.33%   |
| Vestel Elektronik       | 5         | 0.28%   |
| LG Electronics          | 5         | 0.28%   |
| Idek Iiyama             | 5         | 0.28%   |
| GRM                     | 5         | 0.28%   |
| CPT                     | 5         | 0.28%   |
| Panasonic               | 4         | 0.22%   |
| TMX                     | 3         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 11        | 0.59%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 8         | 0.43%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.43%   |
| Apple Color LCD APPA040 2880x1800 331x207mm 15.4-inch                 | 8         | 0.43%   |
| Acer B193 ACR001D 1280x1024 376x301mm 19.0-inch                       | 8         | 0.43%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 7         | 0.37%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 7         | 0.37%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 7         | 0.37%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 7         | 0.37%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 7         | 0.37%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch               | 6         | 0.32%   |
| Gericom Q24 QMX2421 1920x1080 521x293mm 23.5-inch                     | 6         | 0.32%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 6         | 0.32%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 5         | 0.27%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 5         | 0.27%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 5         | 0.27%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 5         | 0.27%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch     | 5         | 0.27%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.27%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 5         | 0.27%   |
| GRM GM2600 GRM5BC6 1920x1200 550x344mm 25.5-inch                      | 5         | 0.27%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 5         | 0.27%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                 | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 309x174mm 14.0-inch        | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 5         | 0.27%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 5         | 0.27%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 4         | 0.21%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4         | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 0.21%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 4         | 0.21%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                 | 4         | 0.21%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 4         | 0.21%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch              | 4         | 0.21%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 4         | 0.21%   |
| Eizo S2202W ENC1975 1680x1050 474x297mm 22.0-inch                     | 4         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 791       | 45.96%  |
| 1366x768 (WXGA)    | 180       | 10.46%  |
| 3840x2160 (4K)     | 144       | 8.37%   |
| 2560x1440 (QHD)    | 110       | 6.39%   |
| 1600x900 (HD+)     | 75        | 4.36%   |
| 1680x1050 (WSXGA+) | 71        | 4.13%   |
| 1920x1200 (WUXGA)  | 65        | 3.78%   |
| 1280x1024 (SXGA)   | 61        | 3.54%   |
| 1280x800 (WXGA)    | 36        | 2.09%   |
| 3440x1440          | 25        | 1.45%   |
| 1440x900 (WXGA+)   | 25        | 1.45%   |
| Unknown            | 18        | 1.05%   |
| 2560x1080          | 12        | 0.7%    |
| 2560x1600          | 11        | 0.64%   |
| 3840x1080          | 10        | 0.58%   |
| 2880x1800          | 10        | 0.58%   |
| 1920x540           | 10        | 0.58%   |
| 3840x2400          | 8         | 0.46%   |
| 1024x600           | 6         | 0.35%   |
| 800x1280           | 5         | 0.29%   |
| 3200x1800 (QHD+)   | 4         | 0.23%   |
| 2048x1152          | 4         | 0.23%   |
| 1600x1200          | 4         | 0.23%   |
| 2160x1200          | 3         | 0.17%   |
| 1024x768 (XGA)     | 3         | 0.17%   |
| 5760x2160          | 2         | 0.12%   |
| 5120x1440          | 2         | 0.12%   |
| 4480x1440          | 2         | 0.12%   |
| 3456x2160          | 2         | 0.12%   |
| 2288x1287          | 2         | 0.12%   |
| 2160x1440          | 2         | 0.12%   |
| 1360x768           | 2         | 0.12%   |
| 5760x1080          | 1         | 0.06%   |
| 3840x2560          | 1         | 0.06%   |
| 3840x1200          | 1         | 0.06%   |
| 3600x1080          | 1         | 0.06%   |
| 3520x1080          | 1         | 0.06%   |
| 3360x1050          | 1         | 0.06%   |
| 3200x1080          | 1         | 0.06%   |
| 3000x2000          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 361       | 20.11%  |
| 27      | 172       | 9.58%   |
| 24      | 171       | 9.53%   |
| 13      | 155       | 8.64%   |
| 14      | 139       | 7.74%   |
| 23      | 119       | 6.63%   |
| 17      | 114       | 6.35%   |
| Unknown | 97        | 5.4%    |
| 21      | 57        | 3.18%   |
| 19      | 55        | 3.06%   |
| 22      | 49        | 2.73%   |
| 31      | 45        | 2.51%   |
| 12      | 38        | 2.12%   |
| 34      | 31        | 1.73%   |
| 25      | 26        | 1.45%   |
| 11      | 18        | 1%      |
| 84      | 16        | 0.89%   |
| 20      | 16        | 0.89%   |
| 54      | 12        | 0.67%   |
| 18      | 12        | 0.67%   |
| 40      | 10        | 0.56%   |
| 16      | 10        | 0.56%   |
| 10      | 10        | 0.56%   |
| 32      | 9         | 0.5%    |
| 28      | 9         | 0.5%    |
| 65      | 6         | 0.33%   |
| 72      | 5         | 0.28%   |
| 33      | 4         | 0.22%   |
| 42      | 3         | 0.17%   |
| 29      | 3         | 0.17%   |
| 75      | 2         | 0.11%   |
| 52      | 2         | 0.11%   |
| 49      | 2         | 0.11%   |
| 48      | 2         | 0.11%   |
| 47      | 2         | 0.11%   |
| 39      | 2         | 0.11%   |
| 35      | 2         | 0.11%   |
| 26      | 2         | 0.11%   |
| 142     | 1         | 0.06%   |
| 61      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 583       | 33.2%   |
| 501-600        | 415       | 23.63%  |
| 351-400        | 167       | 9.51%   |
| 201-300        | 148       | 8.43%   |
| 401-500        | 138       | 7.86%   |
| Unknown        | 97        | 5.52%   |
| 601-700        | 92        | 5.24%   |
| 701-800        | 44        | 2.51%   |
| 1001-1500      | 29        | 1.65%   |
| 1501-2000      | 23        | 1.31%   |
| 801-900        | 14        | 0.8%    |
| 901-1000       | 5         | 0.28%   |
| More than 2000 | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1180      | 72.84%  |
| 16/10   | 236       | 14.57%  |
| Unknown | 70        | 4.32%   |
| 5/4     | 62        | 3.83%   |
| 21/9    | 33        | 2.04%   |
| 3/2     | 13        | 0.8%    |
| 32/9    | 8         | 0.49%   |
| 4/3     | 7         | 0.43%   |
| 0.62    | 5         | 0.31%   |
| 6/5     | 3         | 0.19%   |
| 1.00    | 1         | 0.06%   |
| 0.80    | 1         | 0.06%   |
| 0.56    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 360       | 20.25%  |
| 201-250        | 296       | 16.65%  |
| 81-90          | 223       | 12.54%  |
| 301-350        | 173       | 9.73%   |
| 351-500        | 100       | 5.62%   |
| Unknown        | 97        | 5.46%   |
| 251-300        | 96        | 5.4%    |
| 151-200        | 95        | 5.34%   |
| 121-130        | 90        | 5.06%   |
| 71-80          | 71        | 3.99%   |
| More than 1000 | 46        | 2.59%   |
| 61-70          | 37        | 2.08%   |
| 501-1000       | 24        | 1.35%   |
| 141-150        | 20        | 1.12%   |
| 51-60          | 18        | 1.01%   |
| 131-140        | 13        | 0.73%   |
| 41-50          | 10        | 0.56%   |
| 111-120        | 7         | 0.39%   |
| 91-100         | 2         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 586       | 34.27%  |
| 121-160       | 502       | 29.36%  |
| 101-120       | 347       | 20.29%  |
| 161-240       | 108       | 6.32%   |
| Unknown       | 97        | 5.67%   |
| More than 240 | 40        | 2.34%   |
| 1-50          | 30        | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1248      | 76.52%  |
| 2     | 269       | 16.49%  |
| 0     | 66        | 4.05%   |
| 3     | 43        | 2.64%   |
| 4     | 5         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 885       | 37.03%  |
| Realtek Semiconductor             | 779       | 32.59%  |
| Qualcomm Atheros                  | 217       | 9.08%   |
| Broadcom                          | 97        | 4.06%   |
| Ralink                            | 25        | 1.05%   |
| Marvell Technology Group          | 25        | 1.05%   |
| Ralink Technology                 | 24        | 1%      |
| Broadcom Limited                  | 22        | 0.92%   |
| TP-Link                           | 19        | 0.79%   |
| Nvidia                            | 16        | 0.67%   |
| Ericsson Business Mobile Networks | 16        | 0.67%   |
| Sierra Wireless                   | 15        | 0.63%   |
| Dell                              | 15        | 0.63%   |
| NetGear                           | 14        | 0.59%   |
| MediaTek                          | 14        | 0.59%   |
| Lenovo                            | 12        | 0.5%    |
| IMC Networks                      | 12        | 0.5%    |
| Edimax Technology                 | 12        | 0.5%    |
| ASUSTek Computer                  | 12        | 0.5%    |
| Microsoft                         | 11        | 0.46%   |
| Huawei Technologies               | 11        | 0.46%   |
| Hewlett-Packard                   | 10        | 0.42%   |
| DisplayLink                       | 10        | 0.42%   |
| ASIX Electronics                  | 10        | 0.42%   |
| Samsung Electronics               | 9         | 0.38%   |
| Fibocom                           | 9         | 0.38%   |
| Qualcomm Atheros Communications   | 7         | 0.29%   |
| D-Link System                     | 7         | 0.29%   |
| Aquantia                          | 7         | 0.29%   |
| Qualcomm                          | 5         | 0.21%   |
| D-Link                            | 5         | 0.21%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.17%   |
| JMicron Technology                | 4         | 0.17%   |
| Google                            | 4         | 0.17%   |
| ZyXEL Communications              | 3         | 0.13%   |
| Xiaomi                            | 3         | 0.13%   |
| VIA Technologies                  | 3         | 0.13%   |
| Microchip Technology              | 3         | 0.13%   |
| Sitecom Europe                    | 2         | 0.08%   |
| Motorola PCS                      | 2         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 565       | 19.71%  |
| Intel Wi-Fi 6 AX200                                               | 107       | 3.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 76        | 2.65%   |
| Intel Wireless 8265 / 8275                                        | 62        | 2.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 53        | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 50        | 1.74%   |
| Intel I211 Gigabit Network Connection                             | 49        | 1.71%   |
| Intel Wireless 7265                                               | 39        | 1.36%   |
| Intel Ethernet Connection (2) I219-V                              | 36        | 1.26%   |
| Intel Wireless 8260                                               | 35        | 1.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 35        | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 33        | 1.15%   |
| Intel Wi-Fi 6 AX201                                               | 33        | 1.15%   |
| Realtek RTL8125 2.5GbE Controller                                 | 32        | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 28        | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 27        | 0.94%   |
| Intel Wireless 7260                                               | 27        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 27        | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 26        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 26        | 0.91%   |
| Intel Wireless 3165                                               | 25        | 0.87%   |
| Intel Ethernet Controller I225-V                                  | 25        | 0.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 24        | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 23        | 0.8%    |
| Intel Wireless-AC 9260                                            | 22        | 0.77%   |
| Intel Ethernet Connection (6) I219-V                              | 22        | 0.77%   |
| Intel Ethernet Connection I217-LM                                 | 21        | 0.73%   |
| Intel Centrino Ultimate-N 6300                                    | 21        | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 20        | 0.7%    |
| Intel Ethernet Connection (4) I219-V                              | 19        | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 19        | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 18        | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 18        | 0.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 16        | 0.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 16        | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 14        | 0.49%   |
| Intel WiFi Link 5100                                              | 14        | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 14        | 0.49%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 656       | 50.93%  |
| Realtek Semiconductor                 | 180       | 13.98%  |
| Qualcomm Atheros                      | 156       | 12.11%  |
| Broadcom                              | 69        | 5.36%   |
| Ralink                                | 25        | 1.94%   |
| Ralink Technology                     | 24        | 1.86%   |
| TP-Link                               | 19        | 1.48%   |
| Sierra Wireless                       | 15        | 1.16%   |
| MediaTek                              | 14        | 1.09%   |
| NetGear                               | 13        | 1.01%   |
| IMC Networks                          | 12        | 0.93%   |
| Edimax Technology                     | 12        | 0.93%   |
| ASUSTek Computer                      | 12        | 0.93%   |
| Microsoft                             | 11        | 0.85%   |
| Broadcom Limited                      | 11        | 0.85%   |
| Fibocom                               | 9         | 0.7%    |
| Dell                                  | 9         | 0.7%    |
| Qualcomm Atheros Communications       | 7         | 0.54%   |
| D-Link System                         | 6         | 0.47%   |
| Qualcomm                              | 4         | 0.31%   |
| Ericsson Business Mobile Networks     | 4         | 0.31%   |
| ZyXEL Communications                  | 3         | 0.23%   |
| D-Link                                | 3         | 0.23%   |
| Sitecom Europe                        | 2         | 0.16%   |
| Marvell Technology Group              | 2         | 0.16%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.16%   |
| ZyDAS                                 | 1         | 0.08%   |
| Wilocity                              | 1         | 0.08%   |
| Philips (or NXP)                      | 1         | 0.08%   |
| Linksys                               | 1         | 0.08%   |
| Hewlett-Packard                       | 1         | 0.08%   |
| BUFFALO                               | 1         | 0.08%   |
| Belkin Components                     | 1         | 0.08%   |
| AVM                                   | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 107       | 8.26%   |
| Intel Wireless 8265 / 8275                                     | 62        | 4.79%   |
| Intel Wireless 7265                                            | 39        | 3.01%   |
| Intel Wireless 8260                                            | 35        | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 35        | 2.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 33        | 2.55%   |
| Intel Wi-Fi 6 AX201                                            | 33        | 2.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 28        | 2.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 27        | 2.08%   |
| Intel Wireless 7260                                            | 27        | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 27        | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 26        | 2.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 26        | 2.01%   |
| Intel Wireless 3165                                            | 25        | 1.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 24        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 23        | 1.78%   |
| Intel Wireless-AC 9260                                         | 22        | 1.7%    |
| Intel Centrino Ultimate-N 6300                                 | 21        | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 18        | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 1.24%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 16        | 1.24%   |
| Intel WiFi Link 5100                                           | 14        | 1.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 12        | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 11        | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 11        | 0.85%   |
| Intel Wireless 3160                                            | 11        | 0.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11        | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 11        | 0.85%   |
| Intel Centrino Wireless-N 2230                                 | 11        | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 11        | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 0.77%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 10        | 0.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 9         | 0.69%   |
| Microsoft Xbox 360 Wireless Adapter                            | 9         | 0.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 9         | 0.69%   |
| Intel Centrino Advanced-N 6235                                 | 9         | 0.69%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]           | 9         | 0.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 8         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 708       | 47.58%  |
| Intel                         | 514       | 34.54%  |
| Qualcomm Atheros              | 86        | 5.78%   |
| Broadcom                      | 40        | 2.69%   |
| Marvell Technology Group      | 23        | 1.55%   |
| Nvidia                        | 16        | 1.08%   |
| Lenovo                        | 11        | 0.74%   |
| Broadcom Limited              | 11        | 0.74%   |
| DisplayLink                   | 10        | 0.67%   |
| ASIX Electronics              | 10        | 0.67%   |
| Samsung Electronics           | 9         | 0.6%    |
| Aquantia                      | 7         | 0.47%   |
| OnePlus Technology (Shenzhen) | 4         | 0.27%   |
| JMicron Technology            | 4         | 0.27%   |
| Huawei Technologies           | 4         | 0.27%   |
| Google                        | 4         | 0.27%   |
| Xiaomi                        | 3         | 0.2%    |
| VIA Technologies              | 3         | 0.2%    |
| Motorola PCS                  | 2         | 0.13%   |
| Hewlett-Packard               | 2         | 0.13%   |
| Dell                          | 2         | 0.13%   |
| D-Link                        | 2         | 0.13%   |
| Apple                         | 2         | 0.13%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.07%   |
| Research In Motion            | 1         | 0.07%   |
| Qualcomm                      | 1         | 0.07%   |
| NetGear                       | 1         | 0.07%   |
| Microchip Technology          | 1         | 0.07%   |
| Mellanox Technologies         | 1         | 0.07%   |
| Linksys                       | 1         | 0.07%   |
| IBM                           | 1         | 0.07%   |
| D-Link System                 | 1         | 0.07%   |
| Cypress Semiconductor         | 1         | 0.07%   |
| Attansic Technology           | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 565       | 37%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 76        | 4.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 53        | 3.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 50        | 3.27%   |
| Intel I211 Gigabit Network Connection                             | 49        | 3.21%   |
| Intel Ethernet Connection (2) I219-V                              | 36        | 2.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 32        | 2.1%    |
| Intel Ethernet Controller I225-V                                  | 25        | 1.64%   |
| Intel Ethernet Connection (6) I219-V                              | 22        | 1.44%   |
| Intel Ethernet Connection I217-LM                                 | 21        | 1.38%   |
| Intel Ethernet Connection (4) I219-V                              | 19        | 1.24%   |
| Intel 82579V Gigabit Network Connection                           | 19        | 1.24%   |
| Intel Ethernet Connection (7) I219-V                              | 18        | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.98%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 14        | 0.92%   |
| Intel I210 Gigabit Network Connection                             | 14        | 0.92%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 14        | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 13        | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 12        | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                             | 12        | 0.79%   |
| Intel 82567LM Gigabit Network Connection                          | 12        | 0.79%   |
| Intel Ethernet Connection (10) I219-V                             | 11        | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 11        | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10        | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 0.59%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 8         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 8         | 0.52%   |
| Intel Ethernet Connection I219-V                                  | 8         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 6         | 0.39%   |
| Lenovo USB-C Dock Ethernet                                        | 6         | 0.39%   |
| Intel I350 Gigabit Network Connection                             | 6         | 0.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1389      | 53.06%  |
| WiFi     | 1186      | 45.3%   |
| Modem    | 41        | 1.57%   |
| Unknown  | 2         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 899       | 54.82%  |
| Ethernet | 741       | 45.18%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 835       | 52.35%  |
| 1     | 661       | 41.44%  |
| 3     | 50        | 3.13%   |
| 0     | 33        | 2.07%   |
| 4     | 8         | 0.5%    |
| 5     | 3         | 0.19%   |
| 12    | 2         | 0.13%   |
| 6     | 2         | 0.13%   |
| 13    | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1429      | 88.48%  |
| Yes  | 186       | 11.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 506       | 54.12%  |
| Realtek Semiconductor           | 87        | 9.3%    |
| Qualcomm Atheros Communications | 57        | 6.1%    |
| Cambridge Silicon Radio         | 55        | 5.88%   |
| Broadcom                        | 48        | 5.13%   |
| IMC Networks                    | 30        | 3.21%   |
| Lite-On Technology              | 27        | 2.89%   |
| Apple                           | 22        | 2.35%   |
| Foxconn / Hon Hai               | 20        | 2.14%   |
| ASUSTek Computer                | 16        | 1.71%   |
| Hewlett-Packard                 | 13        | 1.39%   |
| Dell                            | 12        | 1.28%   |
| Toshiba                         | 7         | 0.75%   |
| Foxconn International           | 5         | 0.53%   |
| Ralink                          | 4         | 0.43%   |
| Marvell Semiconductor           | 4         | 0.43%   |
| Belkin Components               | 4         | 0.43%   |
| HTC (High Tech Computer)        | 3         | 0.32%   |
| TP-Link                         | 2         | 0.21%   |
| Realtek                         | 2         | 0.21%   |
| MediaTek                        | 2         | 0.21%   |
| D-Link System                   | 2         | 0.21%   |
| Alps Electric                   | 2         | 0.21%   |
| USI                             | 1         | 0.11%   |
| Micro Star International        | 1         | 0.11%   |
| Logitech                        | 1         | 0.11%   |
| i.Tech Dynamic Limited          | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 187       | 20%     |
| Intel AX200 Bluetooth                                                | 105       | 11.23%  |
| Intel Bluetooth Device                                               | 89        | 9.52%   |
| Realtek Bluetooth Radio                                              | 64        | 6.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 55        | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 52        | 5.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 21        | 2.25%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 20        | 2.14%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 19        | 2.03%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 17        | 1.82%   |
| Lite-On Bluetooth Device                                             | 17        | 1.82%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 17        | 1.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 15        | 1.6%    |
| IMC Networks Bluetooth Radio                                         | 13        | 1.39%   |
| Qualcomm Atheros  Bluetooth Device                                   | 12        | 1.28%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 12        | 1.28%   |
| Intel AX210 Bluetooth                                                | 9         | 0.96%   |
| HP Broadcom 2070 Bluetooth Combo                                     | 9         | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 9         | 0.96%   |
| Apple Bluetooth Host Controller                                      | 9         | 0.96%   |
| IMC Networks Bluetooth Device                                        | 8         | 0.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 8         | 0.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                     | 7         | 0.75%   |
| Apple Bluetooth USB Host Controller                                  | 7         | 0.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 6         | 0.64%   |
| IMC Networks Wireless_Device                                         | 5         | 0.53%   |
| Foxconn International BCM43142A0 Bluetooth module                    | 5         | 0.53%   |
| Dell BCM20702A0 Bluetooth Module                                     | 5         | 0.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5         | 0.53%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 5         | 0.53%   |
| Ralink RT3290 Bluetooth                                              | 4         | 0.43%   |
| Lite-On Wireless_Device                                              | 4         | 0.43%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 4         | 0.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 4         | 0.43%   |
| Broadcom HP Portable SoftSailing                                     | 4         | 0.43%   |
| Broadcom BCM2045 Bluetooth                                           | 4         | 0.43%   |
| Apple Bluetooth HCI                                                  | 4         | 0.43%   |
| Toshiba Bluetooth Device                                             | 3         | 0.32%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 3         | 0.32%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1099      | 48.5%   |
| AMD                                          | 502       | 22.15%  |
| Nvidia                                       | 385       | 16.99%  |
| C-Media Electronics                          | 51        | 2.25%   |
| Logitech                                     | 23        | 1.02%   |
| GN Netcom                                    | 14        | 0.62%   |
| Creative Labs                                | 13        | 0.57%   |
| Texas Instruments                            | 10        | 0.44%   |
| Realtek Semiconductor                        | 9         | 0.4%    |
| Lenovo                                       | 9         | 0.4%    |
| Apple                                        | 9         | 0.4%    |
| Hewlett-Packard                              | 8         | 0.35%   |
| Razer USA                                    | 7         | 0.31%   |
| JMTek                                        | 7         | 0.31%   |
| SteelSeries ApS                              | 6         | 0.26%   |
| Focusrite-Novation                           | 6         | 0.26%   |
| Sennheiser Communications                    | 5         | 0.22%   |
| RODE Microphones                             | 5         | 0.22%   |
| Plantronics                                  | 5         | 0.22%   |
| Creative Technology                          | 5         | 0.22%   |
| Corsair                                      | 5         | 0.22%   |
| Sony                                         | 4         | 0.18%   |
| Kingston Technology                          | 4         | 0.18%   |
| Bose                                         | 4         | 0.18%   |
| GYROCOM C&C                                  | 3         | 0.13%   |
| Generalplus Technology                       | 3         | 0.13%   |
| ASUSTek Computer                             | 3         | 0.13%   |
| ZOOM                                         | 2         | 0.09%   |
| Yamaha                                       | 2         | 0.09%   |
| XMOS                                         | 2         | 0.09%   |
| Thomann                                      | 2         | 0.09%   |
| SAVITECH                                     | 2         | 0.09%   |
| Project                                      | 2         | 0.09%   |
| Microdia                                     | 2         | 0.09%   |
| Micro Star International                     | 2         | 0.09%   |
| M-Audio                                      | 2         | 0.09%   |
| AudioQuest                                   | 2         | 0.09%   |
| Asahi Kasei Microsystems                     | 2         | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| VIA Technologies                             | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 156       | 5.78%   |
| Intel Sunrise Point-LP HD Audio                                            | 123       | 4.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 115       | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 107       | 3.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 92        | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 80        | 2.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 72        | 2.67%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 69        | 2.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 57        | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 56        | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 49        | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 46        | 1.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 45        | 1.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 44        | 1.63%   |
| AMD FCH Azalia Controller                                                  | 42        | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 39        | 1.45%   |
| Intel 8 Series HD Audio Controller                                         | 39        | 1.45%   |
| Intel Comet Lake PCH-LP cAVS                                               | 38        | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 38        | 1.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 37        | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 36        | 1.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 35        | 1.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 34        | 1.26%   |
| Nvidia GP107GL High Definition Audio Controller                            | 30        | 1.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 30        | 1.11%   |
| Intel 200 Series PCH HD Audio                                              | 28        | 1.04%   |
| Nvidia GP104 High Definition Audio Controller                              | 27        | 1%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 27        | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 23        | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 22        | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 22        | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 22        | 0.82%   |
| Nvidia GM204 High Definition Audio Controller                              | 20        | 0.74%   |
| AMD Kabini HDMI/DP Audio                                                   | 20        | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 19        | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 19        | 0.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 19        | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 19        | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 18        | 0.67%   |
| Intel Comet Lake PCH cAVS                                                  | 18        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 220       | 21.59%  |
| SK hynix              | 166       | 16.29%  |
| Kingston              | 123       | 12.07%  |
| Micron Technology     | 105       | 10.3%   |
| Corsair               | 94        | 9.22%   |
| Crucial               | 93        | 9.13%   |
| Unknown               | 80        | 7.85%   |
| G.Skill               | 59        | 5.79%   |
| Elpida                | 13        | 1.28%   |
| Ramaxel Technology    | 12        | 1.18%   |
| Unknown (ABCD)        | 10        | 0.98%   |
| A-DATA Technology     | 7         | 0.69%   |
| Nanya Technology      | 6         | 0.59%   |
| Silicon Power         | 3         | 0.29%   |
| GOODRAM               | 3         | 0.29%   |
| Avant                 | 3         | 0.29%   |
| Unknown               | 3         | 0.29%   |
| Transcend             | 2         | 0.2%    |
| Toshiba               | 2         | 0.2%    |
| JOY-IT                | 2         | 0.2%    |
| Hewlett-Packard       | 2         | 0.2%    |
| Vaseky                | 1         | 0.1%    |
| Unifosa               | 1         | 0.1%    |
| Team                  | 1         | 0.1%    |
| TakeMS                | 1         | 0.1%    |
| Smart                 | 1         | 0.1%    |
| Qimonda               | 1         | 0.1%    |
| PNY                   | 1         | 0.1%    |
| Mushkin               | 1         | 0.1%    |
| Kingmax Semiconductor | 1         | 0.1%    |
| Hitachi               | 1         | 0.1%    |
| CSX                   | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 17        | 1.56%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s            | 12        | 1.1%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 12        | 1.1%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 10        | 0.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.83%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 9         | 0.83%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 0.74%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 7         | 0.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.64%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 7         | 0.64%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.55%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.55%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.55%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.55%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.55%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.55%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 6         | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 5         | 0.46%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.46%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 5         | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.46%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 5         | 0.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.46%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.46%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 0.46%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s           | 5         | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.37%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 4         | 0.37%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.37%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.37%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.37%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.37%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.37%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s            | 4         | 0.37%   |
| Samsung RAM M4 70T5663EH3-CF7 2048MB SODIMM DDR2 975MT/s         | 4         | 0.37%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 4         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 445       | 50.63%  |
| DDR3    | 297       | 33.79%  |
| LPDDR4  | 38        | 4.32%   |
| DDR2    | 33        | 3.75%   |
| SDRAM   | 22        | 2.5%    |
| LPDDR3  | 22        | 2.5%    |
| Unknown | 13        | 1.48%   |
| LPDDR5  | 4         | 0.46%   |
| DDR     | 3         | 0.34%   |
| DDR5    | 2         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 472       | 53.82%  |
| DIMM         | 328       | 37.4%   |
| Row Of Chips | 70        | 7.98%   |
| Chip         | 7         | 0.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 394       | 41.17%  |
| 4096  | 236       | 24.66%  |
| 16384 | 177       | 18.5%   |
| 2048  | 99        | 10.34%  |
| 32768 | 24        | 2.51%   |
| 1024  | 20        | 2.09%   |
| 512   | 4         | 0.42%   |
| 65536 | 1         | 0.1%    |
| 256   | 1         | 0.1%    |
| 16    | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 196       | 20.74%  |
| 3200    | 157       | 16.61%  |
| 2667    | 126       | 13.33%  |
| 2400    | 82        | 8.68%   |
| 1333    | 62        | 6.56%   |
| 2133    | 48        | 5.08%   |
| 3600    | 32        | 3.39%   |
| 1334    | 24        | 2.54%   |
| 667     | 19        | 2.01%   |
| 4267    | 18        | 1.9%    |
| 1867    | 17        | 1.8%    |
| 3000    | 15        | 1.59%   |
| Unknown | 11        | 1.16%   |
| 1067    | 9         | 0.95%   |
| 800     | 9         | 0.95%   |
| 3733    | 8         | 0.85%   |
| 8400    | 7         | 0.74%   |
| 4199    | 7         | 0.74%   |
| 3466    | 7         | 0.74%   |
| 3266    | 7         | 0.74%   |
| 2933    | 7         | 0.74%   |
| 2666    | 7         | 0.74%   |
| 3400    | 6         | 0.63%   |
| 3866    | 5         | 0.53%   |
| 2048    | 5         | 0.53%   |
| 1866    | 5         | 0.53%   |
| 1066    | 5         | 0.53%   |
| 6400    | 4         | 0.42%   |
| 4800    | 4         | 0.42%   |
| 4266    | 4         | 0.42%   |
| 2800    | 3         | 0.32%   |
| 533     | 3         | 0.32%   |
| 3800    | 2         | 0.21%   |
| 3666    | 2         | 0.21%   |
| 3066    | 2         | 0.21%   |
| 2465    | 2         | 0.21%   |
| 1800    | 2         | 0.21%   |
| 400     | 2         | 0.21%   |
| 333     | 2         | 0.21%   |
| 266     | 2         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 14        | 30.43%  |
| Canon                 | 11        | 23.91%  |
| Brother Industries    | 9         | 19.57%  |
| Seiko Epson           | 4         | 8.7%    |
| Samsung Electronics   | 3         | 6.52%   |
| Ricoh                 | 1         | 2.17%   |
| QinHeng Electronics   | 1         | 2.17%   |
| Prolific Technology   | 1         | 2.17%   |
| Oki Data              | 1         | 2.17%   |
| Lexmark International | 1         | 2.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| HP Deskjet 3520 series                                     | 3         | 6.52%   |
| Seiko Epson WF-2530 Series                                 | 2         | 4.35%   |
| Samsung C48x Series                                        | 2         | 4.35%   |
| Brother Printer                                            | 2         | 4.35%   |
| Brother HL-3040CN series                                   | 2         | 4.35%   |
| Seiko Epson XP-230 Series                                  | 1         | 2.17%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 2.17%   |
| Samsung SCX-4300 Series                                    | 1         | 2.17%   |
| Ricoh SP 212SUw                                            | 1         | 2.17%   |
| QinHeng CH340S                                             | 1         | 2.17%   |
| Prolific PL2305 Parallel Port                              | 1         | 2.17%   |
| Oki Data USB Device                                        | 1         | 2.17%   |
| Lexmark International CS417dn                              | 1         | 2.17%   |
| HP OfficeJet Pro 7720 series                               | 1         | 2.17%   |
| HP LaserJet 1320                                           | 1         | 2.17%   |
| HP LaserJet 1200                                           | 1         | 2.17%   |
| HP LaserJet 1022                                           | 1         | 2.17%   |
| HP ENVY Pro 6400 series                                    | 1         | 2.17%   |
| HP ENVY 5000 series                                        | 1         | 2.17%   |
| HP ENVY 4520 series                                        | 1         | 2.17%   |
| HP DeskJet 940c                                            | 1         | 2.17%   |
| HP DeskJet 2700 series                                     | 1         | 2.17%   |
| HP DeskJet 2600 series                                     | 1         | 2.17%   |
| HP Deskjet 2050 J510                                       | 1         | 2.17%   |
| Canon TS5100 series                                        | 1         | 2.17%   |
| Canon PIXMA MX320 series                                   | 1         | 2.17%   |
| Canon PIXMA MG2500 Series                                  | 1         | 2.17%   |
| Canon PIXMA iX6850 Printer                                 | 1         | 2.17%   |
| Canon MG2100 series                                        | 1         | 2.17%   |
| Canon MF5650 (FAX)                                         | 1         | 2.17%   |
| Canon LBP2900                                              | 1         | 2.17%   |
| Canon LaserShot LBP-1120 Printer                           | 1         | 2.17%   |
| Canon L100/L150/L170                                       | 1         | 2.17%   |
| Canon iP7200 series                                        | 1         | 2.17%   |
| Canon CanoScan LiDE 300                                    | 1         | 2.17%   |
| Brother MFC-L2710DW series                                 | 1         | 2.17%   |
| Brother MFC-L2710DN series                                 | 1         | 2.17%   |
| Brother MFC-9142CDN                                        | 1         | 2.17%   |
| Brother DCP-J140W                                          | 1         | 2.17%   |
| Brother DCP-1510                                           | 1         | 2.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 20        | 74.07%  |
| Seiko Epson     | 3         | 11.11%  |
| Fujitsu         | 3         | 11.11%  |
| Hewlett-Packard | 1         | 3.7%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan                                           | 4         | 14.81%  |
| Fujitsu ScanSnap SV600                                   | 3         | 11.11%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 2         | 7.41%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 7.41%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 7.41%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 2         | 7.41%   |
| Canon CanoScan LiDE 220                                  | 2         | 7.41%   |
| Canon CanoScan LiDE 110                                  | 2         | 7.41%   |
| Canon CanoScan LiDE 100                                  | 2         | 7.41%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 3.7%    |
| HP ScanJet 4850C/4890C                                   | 1         | 3.7%    |
| Canon CanoScan N650U/N656U                               | 1         | 3.7%    |
| Canon CanoScan LiDE 60                                   | 1         | 3.7%    |
| Canon CanoScan LiDE 210                                  | 1         | 3.7%    |
| Canon CanoScan FB630U                                    | 1         | 3.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 243       | 26.67%  |
| IMC Networks                           | 84        | 9.22%   |
| Acer                                   | 81        | 8.89%   |
| Microdia                               | 62        | 6.81%   |
| Realtek Semiconductor                  | 51        | 5.6%    |
| Logitech                               | 51        | 5.6%    |
| Sunplus Innovation Technology          | 47        | 5.16%   |
| Quanta                                 | 43        | 4.72%   |
| Lite-On Technology                     | 31        | 3.4%    |
| Suyin                                  | 28        | 3.07%   |
| Cheng Uei Precision Industry (Foxlink) | 27        | 2.96%   |
| Apple                                  | 25        | 2.74%   |
| Syntek                                 | 17        | 1.87%   |
| Microsoft                              | 14        | 1.54%   |
| Luxvisions Innotech Limited            | 11        | 1.21%   |
| Alcor Micro                            | 11        | 1.21%   |
| Samsung Electronics                    | 9         | 0.99%   |
| Ricoh                                  | 7         | 0.77%   |
| Lenovo                                 | 7         | 0.77%   |
| Z-Star Microelectronics                | 5         | 0.55%   |
| SunplusIT                              | 5         | 0.55%   |
| Primax Electronics                     | 5         | 0.55%   |
| OmniVision Technologies                | 4         | 0.44%   |
| ARC International                      | 4         | 0.44%   |
| Silicon Motion                         | 3         | 0.33%   |
| icSpring                               | 3         | 0.33%   |
| Fujitsu                                | 3         | 0.33%   |
| Unknown                                | 2         | 0.22%   |
| Sony                                   | 2         | 0.22%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.22%   |
| KYE Systems (Mouse Systems)            | 2         | 0.22%   |
| Jieli Technology                       | 2         | 0.22%   |
| Generalplus Technology                 | 2         | 0.22%   |
| GEMBIRD                                | 2         | 0.22%   |
| DigiTech                               | 2         | 0.22%   |
| Tobii Technology AB                    | 1         | 0.11%   |
| Sunplus Technology                     | 1         | 0.11%   |
| Sonix Technology                       | 1         | 0.11%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.11%   |
| Novatek Microelectronics               | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 63        | 6.86%   |
| IMC Networks Integrated Camera                      | 43        | 4.68%   |
| Acer Integrated Camera                              | 31        | 3.37%   |
| Microdia Integrated_Webcam_HD                       | 27        | 2.94%   |
| Chicony HD WebCam                                   | 20        | 2.18%   |
| Chicony HP HD Camera                                | 18        | 1.96%   |
| Quanta HD User Facing                               | 15        | 1.63%   |
| Realtek Integrated_Webcam_HD                        | 12        | 1.31%   |
| Sunplus Integrated_Webcam_HD                        | 11        | 1.2%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 11        | 1.2%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 11        | 1.2%    |
| Quanta HP HD Camera                                 | 10        | 1.09%   |
| Logitech Webcam C270                                | 10        | 1.09%   |
| Lite-On Integrated Camera                           | 10        | 1.09%   |
| Samsung Galaxy A5 (MTP)                             | 9         | 0.98%   |
| Realtek USB2.0 HD UVC WebCam                        | 9         | 0.98%   |
| Lite-On HP HD Camera                                | 9         | 0.98%   |
| Chicony HP HD Webcam                                | 9         | 0.98%   |
| Logitech HD Pro Webcam C920                         | 8         | 0.87%   |
| Chicony VGA WebCam                                  | 8         | 0.87%   |
| Chicony USB2.0 HD UVC WebCam                        | 8         | 0.87%   |
| Chicony TOSHIBA Web Camera - HD                     | 8         | 0.87%   |
| Apple iPhone 5/5C/5S/6/SE                           | 8         | 0.87%   |
| Syntek Integrated Camera                            | 7         | 0.76%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 7         | 0.76%   |
| Chicony Integrated HP HD Webcam                     | 7         | 0.76%   |
| Chicony HP Truevision HD camera                     | 7         | 0.76%   |
| Apple Built-in iSight                               | 7         | 0.76%   |
| Acer Lenovo EasyCamera                              | 7         | 0.76%   |
| Realtek Full HD webcam                              | 6         | 0.65%   |
| Microsoft LifeCam HD-3000                           | 6         | 0.65%   |
| Microdia Webcam Vitade AF                           | 6         | 0.65%   |
| Lenovo Integrated Webcam [R5U877]                   | 6         | 0.65%   |
| Chicony USB 2.0 Camera                              | 6         | 0.65%   |
| Chicony Integrated Camera (1280x720@30)             | 6         | 0.65%   |
| Chicony HD User Facing                              | 6         | 0.65%   |
| Chicony FJ Camera                                   | 6         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 6         | 0.65%   |
| Acer SunplusIT Integrated Camera                    | 6         | 0.65%   |
| Acer BisonCam, NB Pro                               | 6         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 97        | 37.02%  |
| Synaptics                  | 97        | 37.02%  |
| Shenzhen Goodix Technology | 25        | 9.54%   |
| Upek                       | 16        | 6.11%   |
| AuthenTec                  | 13        | 4.96%   |
| LighTuning Technology      | 6         | 2.29%   |
| Elan Microelectronics      | 6         | 2.29%   |
| STMicroelectronics         | 1         | 0.38%   |
| Focal-systems.Corp         | 1         | 0.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 45        | 17.11%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 10.65%  |
| Unknown                                                                    | 19        | 7.22%   |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 6.46%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 6.08%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 4.94%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 3.8%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 3.42%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 3.42%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 2.66%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.66%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 2.28%   |
| Validity Sensors VFS491                                                    | 6         | 2.28%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 2.28%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.9%    |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.9%    |
| AuthenTec AES2810                                                          | 5         | 1.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.52%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.52%   |
| Synaptics WBDI Device                                                      | 3         | 1.14%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 3         | 1.14%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.14%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.14%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.14%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.76%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.76%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.76%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.76%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.38%   |
| Synaptics  WBDI                                                            | 1         | 0.38%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.38%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.38%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.38%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.38%   |
| AuthenTec AES1600                                                          | 1         | 0.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 61        | 49.59%  |
| Broadcom              | 33        | 26.83%  |
| Lenovo                | 11        | 8.94%   |
| Upek                  | 9         | 7.32%   |
| O2 Micro              | 3         | 2.44%   |
| Realtek Semiconductor | 2         | 1.63%   |
| Cherry                | 2         | 1.63%   |
| SCM Microsystems      | 1         | 0.81%   |
| Advanced Card Systems | 1         | 0.81%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 60        | 48.78%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 10.57%  |
| Lenovo Integrated Smart Card Reader                                          | 10        | 8.13%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 8.13%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 7.32%   |
| Broadcom 5880                                                                | 5         | 4.07%   |
| Broadcom 58200                                                               | 5         | 4.07%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 2.44%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.63%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.81%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.81%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.81%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.81%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.81%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.81%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1085      | 66.36%  |
| 1     | 412       | 25.2%   |
| 2     | 98        | 5.99%   |
| 3     | 24        | 1.47%   |
| 4     | 8         | 0.49%   |
| 5     | 4         | 0.24%   |
| 8     | 2         | 0.12%   |
| 6     | 2         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 256       | 36.26%  |
| Graphics card            | 113       | 16.01%  |
| Chipcard                 | 95        | 13.46%  |
| Net/wireless             | 82        | 11.61%  |
| Multimedia controller    | 30        | 4.25%   |
| Communication controller | 26        | 3.68%   |
| Unassigned class         | 19        | 2.69%   |
| Sound                    | 17        | 2.41%   |
| Bluetooth                | 17        | 2.41%   |
| Camera                   | 14        | 1.98%   |
| Net/ethernet             | 8         | 1.13%   |
| Card reader              | 7         | 0.99%   |
| Storage                  | 5         | 0.71%   |
| Modem                    | 5         | 0.71%   |
| Network                  | 3         | 0.42%   |
| Tv card                  | 2         | 0.28%   |
| Flash memory             | 2         | 0.28%   |
| Storage/raid             | 1         | 0.14%   |
| Storage/nvme             | 1         | 0.14%   |
| Storage/ide              | 1         | 0.14%   |
| Storage/ata              | 1         | 0.14%   |
| Firewire controller      | 1         | 0.14%   |

